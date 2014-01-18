Vagrant.configure("2") do |config|

    if Vagrant.has_plugin?("vagrant-cachier")
        config.cache.auto_detect = true
    end

    config.vm.box = "precise32"
    config.vm.box_url = "http://files.vagrantup.com/precise32.box"

    config.vm.provision :shell, :path => "vagrant.sh"

end
