# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  # Ubuntu 14.04 (Trusty Tahr) - 64bit
  config.vm.box = "ubuntu/trusty64"

  config.vm.network "private_network", ip: "192.168.56.101"
  config.vm.network "private_network", ip: "192.168.56.102"
  config.vm.network "private_network", ip: "192.168.56.103"
  config.vm.provision "shell", path: ".setup/vagrant.sh"
end
