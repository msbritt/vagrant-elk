
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provision :shell, path: "bootstrap.sh"
  config.vm.network :forwarded_port, host: 80, guest: 8080

  config.vm.provider "virtualbox" do |v|
    v.memory = 4096
    v.cpus = 1
  end

end
