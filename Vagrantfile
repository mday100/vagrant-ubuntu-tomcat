Vagrant.configure(2) do |config|

  config.vm.box = "ubuntu/trusty64"
  config.vm.network "public_network", bridge: "en1: Wi-Fi (AirPort)"
  config.vm.hostname = "fdm-box"

  config.vm.provision "shell", path: "provision.sh"

end