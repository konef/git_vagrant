Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.hostname = "pet"
  config.vm.network :public_network

  config.ssh.insert_key = false

  config.vm.provider "virtualbox" do |vb|
    # Virtual Machine Name
    vb.name = "ansible-day-3"
    # Display the VirtualBox GUI when booting the machine
    vb.gui = false
    # Customize the amount of memory on the VM:
    vb.memory = "512"
  end
end
