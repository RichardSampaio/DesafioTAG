Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/focal64"
  
    config.vm.provider "virtualbox" do |v|
      v.memory = 1024
    end
  
    config.vm.define "linux" do |m|
      m.vm.network "private_network", ip: "172.17.177.41"
    end
  
  end