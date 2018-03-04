Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/xenial64"

    config.vm.host_name = "lancache.vm"
    config.vm.network :private_network, ip: "10.10.10.10"
    config.vm.synced_folder ".", "/home/vagrant/lancache", type: "nfs"

    # config.vm.provision "shell", path: "provision.sh"
end
