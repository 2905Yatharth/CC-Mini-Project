# CC-Mini-Project
This project aims to design a suitable network system for colleges/campuses in developing  countries and to design a network with high security and low cost. This project will help to  enhance the education of developing countries.


The advantages of networking can be seen 
clearly in terms of efficiency, security, manageability, and cost as it allows collaboration 
between users in a wide area. To improve college campus network design, the technology used 
was creating LAN and WLAN and using a cheap device to reduce the cost of the network. But 
the network can also become better by using routing protocols and other protocols. So, we are 
going to use such protocols using a smaller number of devices and will also maintain the low 
cost of the network. 
The network was constructed and implemented on the college campus. Students can 
successfully connect and utilize the internet, provided they enter the correct admin details. 
Teachers can also connect to the network that has been set up.




For Main Building: 
In the main building, there are 20 users which are provided with the high-speed internet 
wirelessly, and only authorized persons are given access to the network for this purpose we 
have used the WRT300N router which is a wireless router and is capable of providing highspeed internet to the users within its range. For providing the internet we are using DHCP 
protocol. Dynamic Host Configuration Protocol (DHCP) is a client/server protocol that 
automatically provides an Internet Protocol (IP) host with its IP address and other related 
configuration information such as the subnet mask and default gateway. The Network address 
used here is 192.168.0.0. For protection purposes, this router is using WPA2-PSK 
authentication which has a PSK pass phase. This passkey will be provided only to the 
authorized personnel. 
For Tech Park Building and Hospital Block Building: 
In the tech park building, 20 users are all connected to the same network using switches. In the 
hospital block, 10 users are all connected to the same network using switches. We are using 
2960-244TT switches to connect PCs in different rooms and to connect all of the switches we 
are using a 3560-24PS switch which is a Multi-layered switch. The network address we used 
in Tech Park is 193.161.155.0. The network address used in the hospital block is 193.161.158.0 
It is necessary to protect these networks from unauthorized users and prevent them from 
hacking, so it is necessary to maintain security in these networks by using various security 
options. To implement this, we need the best devices that can support these protocols more 
efficiently. So, we decided to use multi-layered switches which work as a switch as well as a 
router and using this router it is possible to implement the EIGRP routing protocol. By using 
EIGRP it is possible for load balancing on parallel links between sites and also manages load 
balancing. Both the buildings are then connected to the main building’s router using a fast 
Ethernet connection so to provide the internet connection available in the main building to the 
tech park and the hospital block. 
The topology we used here is BUS topology as we have to provide the internet connection to 
all the users using the main building’s internet connection.
