Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end

  config.vm.define "server1" do |m|
      m.vm.network "private_network", ip: "172.17.177.40"
  end

  config.vm.define "server2" do |m|
      m.vm.network "private_network", ip: "172.17.177.50"
  end

end
