VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
 
  config.vm.box = "trusty64"
  
  config.vm.network :forwarded_port, guest: 80, host: 5000
  
  config.vm.network :private_network, ip: "10.10.10.10"

  config.vm.synced_folder "/home/jlel/train", "/home/shared"

end
