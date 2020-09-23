# Interesting
week4
A technology that where the source port chosen by the client is same as router uses is called port preservation.
A technology where specific destination ports can be configured to always deliver data on specific nodes is called port forwarding.
A fully qualified Domain name consists of the parts. First is the sub domain e.g wwww or mail. The next part is domain name e.g google microdoft. and the last is Top level domain e.g com.
DNS is used to convert the domain name into the ip adderess. In practice DNS works with some record files or resources. The are different resource records e.g A record, mail record etc.
An A record is used to point at a certain ip like 10.1.1.10. CNMAE record is used to assign differnt subdomains to a certain ip addresses. Pointer record is used to convert ip address to a 
domain name. Name server record has all the info about the DNS or it the database of DNS. DNS uses UDP port 53 for name resolution.
A DHCP dynamically assigns ip address to each device on a LAN network. since the connecting device has no ip address so a a special message is formed with 0.0.0.0 it is then sent to every
node on the network with a broadcast message of 255.255.255.255. The DHCP server knows that is was intended for it so sends an ack message with a broadcast message to the network .The host 
compuetr knows that it was intended for it so it accpets the offer and then the dhcp server sends an ip addreess with a lease. the dhcp server can automatically assign the same ip to the 
same  machine if it is  not in use.
A technology that allows for the extension of local or private network to the clients that are not physically present on that network. it uses the tunnling protocol. it is usually a secure
way to access the outside world to hide our ip.  
A proxy serves as a server between client and the outside world. webproxies usually hold the web pages in their database which are mostly visited but this prox
NAT is technology where the public ip address of the devices is hided by the router so the router sends its own default gatways address as an ip address of the device. it can be used to 
block traffic to certain websites.
week 5  
plain old switching network is an old tephone system.USENET was used to share information across computers on a short distance.
the technology used is called USENET that uses modem which stands for Modulating/demodulating. it gets computer digital data, convets it into analogue signal and sends through copper wires of telephone.
then this data was sent to telephone exchange from where it was sent to the other copmuter. 
Broadband means fast. In netwoking technology it is reffered to something that is faster that old dial up connections. Broadband technology uses the links thar are always on.Broadband has 
shaped todays world. These are long distance connections that you dont always need to establish for each use.
T-technolgies are invented by AT&T. In this technology uses a single wire to tansfer 24 calls at time. Later this technology was used to tansfer data with 64kb*24 on each single wire which
is roughly equal to 1.5Mbps. 
In DSL,Digital Subscriber line, telephone wires usually copper are used to share data. The bandwidth is indiviual for each consumer. There are two types of speed. In asymmetric DSL,
Downloading speed is faster that uploading while in symmetric DSL both  uploading and downloading speeds are different. a router or modem known as DSLAM or digital subsriber line access
modem. The connection vanishes when DSLAM is powered off.
In cable connections usually TV cables are used by varying the frequency in a way that it does not disturb the tv tansmission. The bandwidth is shared that why when the using rate is high,
it can make the connections slow.earlier COs or central offices were used which basically connects the cable networks to the telephone central offices to provide them their purchased
bandwidth but now they can perform this task automatically. The cable modem sits at customer end to  connect it to cable modem termination system which connects a lot of networks to ISPs
core network system.
In fibre connections fibre technology is used. The are different types like FTTX. X can vary from from ISP to ISP.FTTN means fibre to the neighbouhood.
This means that fiber technologies are used to deliver data to a single physical cabinet that serves a certain amount of the population. From this cabinet, twisted pair copper or coax might
be used for the last length of distance..FTTB means fibre fibre to the bulding(usually a big building like 
residential buildings) from where it is sent through wires for the usage. FTTH means fibre to the home which is dirctly connected t the home FTTB and FTTH can also be reffered as FTTP or 
fibre to the premises. 
In WAN or wide area network you usually creates your own local network at particular physical locatiob but if you have another office in another location then instead of building another
setup you make a contract with the ISP to share your services to another office. the region between these two loation is called local hoop. 
In wireless technology we uses 802.11 standars or protocols for wireless communication. We use a specific frequency band for communication of radio waves. Internet access point is basically
a bridge between wireless and wired connection. The difference between a router and a Wireless AP is that you can only access wireless communication with Wireless AP but with router you
can even make wired and wireless communication. If we have a lot of routers then we need to configure every router but if we use WAP we just have to configure only one router and connect
every WAP to it. we can use mesh network to connect routers and WAP becuase in mesh every wap is connect to other wap and we dont need much wires to connect every router with wap.
WPA cant provide IP addresses so you will take IP through router. Two factor authentication is way where more that username or passwords is required.
In ad-hoc networks every device or node is connected to the other without any gateway or router e.g connecting differnt devices through bluetooth. In WLAN networks devices uses a router
or modem to share the data. Wireless security can be done through an flawful encryption method called WEP or wired euivalent privacy. you can also use mac filtering to allow specific
devices to connect to your router.
week 6
Error detection is the ability of a program to detect that something went wrong. Error recovery is the ability of a protocol or program to make an attempt to fix that problem.
When a network error occurs a device needs a way of communication to the souce so it uses protocol called Internet control message protocol is used but that has a specific frame.
But this protocol is not understandable by the human so we need a way to read this protocol. We use ping google.com command that basically sends an echo request in the form of 4 packets
to the server and gets an echo reply. during this an ICMP is created from each side. you can use tracert  to access the rout of a request. At transpot layer you can use Trace-NetConnection
to check the access at certain port.
You can use nslookup command to ckeck the DNS address of a website.you can also use it in interactive and noniteractive mood. By non interactive mood you just write nslook and an anchor
bracket appears. Then you can specify the name of website to check its DNS services. you can change you own DNS server to public DNS server by typing server and the IP address of the
public server. The public DNS IP address of the google is 8.8.8.8 and L3 Communication is 4.2.2.1 through 4.2.2.6.  If the DNS provided by your ISP is not working then you can use public
dNS Servers. 
Host files are basically the text files that contains the IP addresses and Hostnames. This is basically the default DNS in almost all operating systems. If your browser cannot find the
IP address for name resolution in the cache or it then looks for Host files. You can even you host files to direct traffic towards youself by a  default Ip address 127.0.0.1.
If we add 127.0.0.1 and facebook.com then the dns will resolve it to the 127.0.0.1 which is our localhost so it cannot accesss to the Facebook.com.
Ipv6 stands for internet protocol version6. Just like IPv4 is a 32 bit long number, IPv6 is a  128 bit long number means you can get number of IP addresses in the range of a 39 digit long
number. After the IPv4 ,IPv5 was just an experimental protocol was just used for connections.it was not widely opted because the connection state was handled betterly by TCP and UDP.So the 
consensus does doest adopted the term IPv5. Usually the first 64 bits are network ID and the next 64 bits are reserved for host Ids. It consists of 8 groups of hexadecimal numbers. 
You can make IPv6 address shorted by removing the leading zeros. and the groups with all zeros with a double colon::
2001:Odb8 is used for documentation in all types of education including books and courses. FF00:: is used for multicast and FE80:: is used for link-local unicast. 
In IPV6 header the first thing is Version which basically tells us what version of IP protocol is used whther it is IP v4 or Ipv6. Next is Class field which basically defines what type  of 
traffic the ID datagram contains and assign different classes different specific priorities. Next is flowlablel filed which is basically used in conjunction which CLass field and helps
routers to make decision what quality of sevice the specific datagram contains. Next is datapayload length which basically tells the length of datapayload section and the next is hop limit
just like TTL field in IPv4. 
Since the IPv6 concept is new so in order to make it compatible with IPv4 we use an IPv6 address that has 80 zeros and 16 1s in the start is basically an IPv4 mapped address. The remaining 
32 bits are just like ipv4 datagram.In order to move IPv6 over the IPv6 remnants we use IPv6 tunnling concept. In ipv6 Tunnels we use servers on both ends that converts the IPv6
datagram into IPv4 and whenit reaches the destination the other IPv6 tuneel servers convert it into IPv6 datagram.
NAT is a technology that allows gatways within a LAN usually routers to change the source IP of a datagram and rewite its own IP when the the data packet reaches to its connected LAN.it is just like
the router sent this data packet. Usually it converts the private ip address to public ip address.
you can also hide your files and protect them from others.
cp command is used to copy and rm is used to delete,while ls -a is used to list all files including hidden files. ls -a -l is used to print all the files including security checks and 
lenght of the files. wild card is used to select the files of similar type and we use -Recurse in power shell to copy and move the whole directory. we can use -Verbose to print different
lines on CLI for the confirmation of the copying.In linux we use -r to for recursive just after the command.
Parameters are used in powershell to add extra features to the command and flags are used in linux to  add extra functionalities.parameters use single - and flags uses double dashes --.
