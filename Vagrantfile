# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |global_config|
  global_config.berkshelf.enabled = true
  global_config.omnibus.chef_version = '11.8.0'
  global_config.vm.box = "bento/ubuntu-16.04"
  global_config.vm.provider :virtualbox do |vb|
    vb.customize ["modifyvm", :id, "--memory", 2048]
  end
end




