# Linux
My Linux Notes


- 如何卸载Linux下的vmware
先查看安装的虚拟机
vmware-installer -l
然后会显示版本和产品名称
Product Name           Product Version     
====================== ====================
vmware-workstation     7.0.1.227600 
<br>
卸载虚拟机
sudo vmware-installer --uninstall-product vmware-workstation

- Linux内核源码安装
sudo apt-get install linux-headers-$(uname -r)
