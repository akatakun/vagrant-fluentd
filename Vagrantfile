# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure('2') do |config|
  config.vm.box = 'base'

  config.vm.define 'fluentd' do |vagrant|
    vagrant.vm.box_url = './ubuntu-14-04-x64-virtualbox.box'
    vagrant.vm.box = 'Ubuntu14.04'
    vagrant.vm.network :private_network, ip: '192.168.56.10'
  end
end
