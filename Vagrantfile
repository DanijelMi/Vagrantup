Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provision/playbook.yml"
  end
end
