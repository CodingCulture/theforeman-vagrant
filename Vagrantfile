# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  # Box info
  config.vm.box = "precise32"
  config.vm.box_url = "http://files.vagrantup.com/precise32.box"

  # Network
  config.vm.network "private_network", ip: "192.168.33.10"

  # Provisioning
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "src/ansible/vagrant.yml"
  end

end
