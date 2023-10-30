# Port forwarding for virtual machines
copy to /etc/libvirt/hooks/qemu

I highly do **not** recommend use this option in real projects because restart a virtual machine is needed to delete rules from iptables
Use terraform-iptables-provider instead of it. 
I install provider here https://github.com/aabbcc101?tab=repositories#:~:text=settings_for_a_physical_server_KVM_plus_terraform,Public
How to use it you can find here https://github.com/aabbcc101/create_virtual_mashines_for_kubernetes

Wish you easy port forwording ^^
