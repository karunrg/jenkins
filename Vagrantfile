Vagrant.configure("2") do |config|
   config.vm.provider "virtualbox" do |vb|
       vb.memory = 1024
   end


   config.vm.define :chefserver do |master_config|
          master_config.vm.box = "bento/centos-7.3"
          
          master_config.vm.host_name = "chefserver"

          master_config.vm.network "private_network", ip: "192.168.50.20"

end






  end

