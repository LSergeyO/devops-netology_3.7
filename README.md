# devops-netology_3.7  
1. Linux:  
![img.png](img.png)  
Windows: 
![img_1.png](img_1.png)  

2. LLDP  
apt install lldpd  
![img_2.png](img_2.png)  

3. VLAN  
apt install vlan  

root@LSergeyO:~# vim /etc/network/interfaces  

auto enp37s0.1001  
iface enp37s0.1001 inet static  
        address 192.168.1.200  
        netmask 255.255.255.0  
        vlan_raw_device enp37s0  
4. 



