Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/trusty64"

    config.vm.define "wordpress" do |wordpress|
        wordpress.vm.network "private_network", ip: "192.168.1.13"

        wordpress.vm.provider "virtualbox" do |virtualbox|
            virtualbox.memory = 1024
            virtualbox.cpus = 2
            virtualbox.name = "wordpress"
        end
    end
end