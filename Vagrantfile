# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.synced_folder "./code", "/home/ubuntu/code"
config.vm.provision 'shell', path:'./provision.sh'
end
