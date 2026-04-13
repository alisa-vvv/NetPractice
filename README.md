*This project has been created as part of the 42 curriculum by avaliull*<br>

#DESCRIPTION:<br>
NetPractice is a project designed to introduce the basics of networking. It presents a set of 10 "levels" that depict fictional networks in the form of an interactive puzzle. The student has to configure the networks based on the information given by each level. Doing so requires a basic understanding of IP adressing, and the functionality of fundamental network components, namely, routers, switches, and hosts.<br>

#INSTRUCTIONS:<br>
The project contains 10 configurations for the 10 different levels in .json format. Evaluation is performed by running the net_practice testing script, which will randomize 3 levels from 6-10, and have to be solved by the student in 15 minutes.<br>
The evaluation script is not a part of the git repository. It can be downloaded from the evaluation page in a *net_practice.tgz* file. Here are the steps to run it:<br>
1. Download the net_practice.tgz file from the link provided by the evaluation sheet.
2. Extract the archive and run .../net_practice/run.sh as an executable.
3. This will open an html page. From here, two options are available:
    1) Training - to complete levels 1-10 sequentially;
    2) Evaluation - to start the evaluation.
The evaluator should chose option 2 and start the 15 minute timer. The evaluatee has to complete the 3 levels in time.
4. levelX.html files can also be opened individually.


#RESOURCES:<br>

A simple explanation of ipv4 addresses:<br>
https://whatismyipaddress.com/ipv4-parts<br>
https://whatismyipaddress.com/ip-basics<br>

TCP/IP protocol:<br>
https://www.rfc-editor.org/rfc/rfc791<br>

An article detailing the methods to calculating subnet masks and number of avaliable hosts:<br>
https://www.techtarget.com/searchnetworking/tip/IP-addressing-and-subnetting-Calculate-a-subnet-mask-using-the-hosts-formula<br>

Specific information about IP address conventions (potentially poor source):<br>
https://dev.to/leapcell/understanding-network-interfaces-loopback-local-ips-and-public-ips-2p47<br>

Default gateway:
https://www.geeksforgeeks.org/computer-networks/default-gateway-in-networking/<br>

Explanation of OSI model:<br>
https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/<br>

Explanation of CIDR:<br>
https://www.geeksforgeeks.org/computer-networks/classless-inter-domain-routing-cidr/<br>

Explanation of Switches:<br>
https://www.networkacademy.io/ccna/network-fundamentals/routers-layer3-switches<br>

IPv4 Classes:<br>
https://docs.oracle.com/cd/E19504-01/802-5753/planning3-78185/index.html<br>
