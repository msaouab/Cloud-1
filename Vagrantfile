#server
S_NAME = "msaouab"
S_IP = "192.168.56.20"

#common config
VAGRANT_BOX = "ubuntu/focal64"
RAM = 1024
CPU = 1

Vagrant.configure("2") do |config|
    config.vm.box = VAGRANT_BOX
    config.vm.network "private_network", ip: S_IP
    config.vm.hostname = S_NAME
    config.vm.provider "virtualbox" do |vb|
        vb.memory = RAM
        vb.cpus = CPU
    end
end