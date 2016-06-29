Vagrant.configure(2) do |config|
#configuring new Vagrant config!!! DO NOT DELETE
 config.vm.define "puppetagent" do |puppetagent|
#creating new VM called web with specified IP
        web.vm.box = "ubuntu/trusty64"
        config.vm.network "private_network", ip: "192.168.33.12/24"
    end
 config.vm.define "puppetmaster" do |puppetmaster|
#creating new VM called db 
        db.vm.box = "ubuntu/trusty64"
        config.vm.network "private_network", ip: "192.168.33.11/24"
    end

#if vagrant up - 2 VM's will be started

end



