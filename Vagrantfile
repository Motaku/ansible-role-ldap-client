Vagrant.configure(2) do |config|
    config.vm.box = "hashicorp/precise64"

    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "tests/test.yml"
        ansible.sudo = true
    end
end