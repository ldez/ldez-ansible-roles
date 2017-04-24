# -*- mode: ruby -*-
# vi: set ft=ruby ts=2 sw=2 tw=0 et :

boxes = [
  {
    :name => "ubuntu-1604",
    :box => "ubuntu/xenial64",
    :ip => '10.0.77.13',
    :cpus => "1",
    :cpu_cap => "50",
    :ram => "512"
  }
]

Vagrant.configure("2") do |config|
  boxes.each do |box|
    config.vm.define box[:name] do |vms|
      vms.vm.box = box[:box]
      vms.vm.box_url = box[:url]

      vms.vm.provider "virtualbox" do |v|
        v.customize ["modifyvm", :id, "--cpus", box[:cpus]]
        v.customize ["modifyvm", :id, "--cpuexecutioncap", box[:cpu_cap]]
        v.customize ["modifyvm", :id, "--memory", box[:ram]]
      end

      vms.vm.network :private_network, ip: box[:ip]

      # neccessary for ubuntu 16.04 and harmless for the rest
      vms.vm.provision :shell do |shell|
        shell.inline = "DEBIAN_FRONTEND=noninteractive apt-get -y install python-simplejson"
      end

      vms.vm.provision :ansible do |ansible|
        ansible.playbook = "tests/vagrant.yml"
        ansible.verbose = "vv"
      end
    end
  end
end
