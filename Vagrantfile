# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
  
  config.vm.box = "hashicorp/precise32"

  # install necassary packages and CliNER
  config.vm.provision "packages", type: "shell", path: "vagrant-bootstrap.sh"

end
