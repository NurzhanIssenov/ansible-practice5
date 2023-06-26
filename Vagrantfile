VAGRANTFILE_API_VERSION = 2

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.ssh.insert_key = false
  
  config.vm.define "vagrant1" do |vagrant1|
    vagrant1.vm.box = "ubuntu/focal64"
    vagrant1.vm.network "private_network", ip: "192.168.56.11"
  end
  
  config.vm.define "vagrant2" do |vagrant2|
    vagrant2.vm.box = "ubuntu/focal64"
    vagrant2.vm.network "private_network", ip: "192.168.56.12"
  end
  
  config.vm.define "vagrant3" do |vagrant3|
    vagrant3.vm.box = "ubuntu/focal64"
    vagrant3.vm.network "private_network", ip: "192.168.56.13"
  end
  
  config.vm.define "vagrant4" do |vagrant4|
    vagrant4.vm.box = "ubuntu/focal64"
    vagrant4.vm.network "private_network", ip: "192.168.56.14"
  end
  
end