*Minimum syntax to configure a VM instance
Vagrant.configure(2) do config | 
  config.vm.box = "USERNAME/OSIMAGE"
end

(2) = version

* Syntax to configure a basic VM and assign to private network with static IP
Vagrant.configure(2) do config | 
  config.vm.box = "USERNAME/OSIMAGE"
  config.vm.hostname = "linuxsvr1"
  config.vm.network "private_network", ip: "10.0.0.10"
end

*Syntax to configure basic VM with defined IP, local virtualization using VirtualBox provider, with graphical capabilites and graphical memory definitionVagrant.configure(2) do config | 
  config.vm.box = "USERNAME/OSIMAGE"
  config.vm.hostname = "linuxsvr1"
  config.vm.network "private_network", ip: "10.0.0.10"
  config.vm.provider "virtualbox" do |vb|
  vb.gui = true
  vb.memory = "1024"
end
