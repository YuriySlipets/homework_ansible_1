Vagrant.configure(2) do |config|

  config.vm.define "node1" do |node1|
    node1.vm.box = "debian/stretch64"
    node1.vm.network "private_network", ip: "192.168.42.11"
    node1.vm.hostname = "node1"
  end

  config.vm.define "node2" do |node2|
    node2.vm.box = "debian/stretch64"
    node2.vm.network "private_network", ip: "192.168.42.12"
    node2.vm.hostname = "node2"
  end

end
