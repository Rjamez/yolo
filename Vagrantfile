Vagrant.configure("2") do |config|
  config.vm.box = "geerlingguy/ubuntu2004"
  config.vm.hostname = "yolomy-dev"
  config.vm.network "private_network", type: "dhcp"
  
  config.vm.provision "shell", inline: <<-SHELL
  apt-get update
  apt-get install -y python3-pip
  pip3 install docker
SHELL
  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
