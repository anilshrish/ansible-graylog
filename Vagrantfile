Vagrant.configure("2") do |config|
    config.vm.define "greylog" do |subconfig|
        subconfig.vm.box = 'ubuntu/xenial64'
        subconfig.vm.hostname = "greylog"
        subconfig.vm.network :private_network, ip: "10.0.0.20"
#        subconfig.vm.provision :shell, path: "bootstrap.sh"
    end
end
