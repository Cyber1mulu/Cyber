# Tools for Identifying Malicious Activity


Introduction 

            -Network Traffic
            - Wireshark
            -Tcpdump
            - WHOIS



Objective 

            Customize the Wireshark Application
            Capture Network Traffic using the Wireshark Application
            Capture Network Traffic using Tcpdump
            Analyze Malicious Code
            Use WHOIS to Validate Domain Names
            Use AbuseIPDB to Validate Domain Names
            Use the Virustotal Website to Verify Links
                       




Monitoring Network Activities
                                      
                                      
             A Cyber Security Analyst, several tools are available that can be used to monitor and analyze network traffic.
             Analyzing network traffic is essential to detect any malicious activity on the networkty



Devices

                         - Windows Server 2022 - Domain Controller
                         -Windows Server 2022 - Domain Member Server
                         -Windows 11 - Domain Member Workstation
                         -Linux Standalone Workstation
                         -Kali Linux Standalone Workstation

<h2 style="color:lightblue;">   Task 1 - Customizing the Wireshark Application </h2>

Open wireshark on kali-linx 
<div>
            <img width="508" height="178" alt="image" src="https://github.com/user-attachments/assets/5e9a958f-0c03-4657-a98c-7140ceb9f996" />
</div>





In the Wireshark Network Analyzer window, ensure eth0 is selected and click Start
Capturing Packets.



<div>      
<img width="508" height="179" alt="image" src="https://github.com/user-attachments/assets/9a06ca45-041a-484b-8e34-3111fe1325f1" />
      </div>






In the Wireshark application, click Stop capturing packets
<div>
<img width="508" height="179" alt="image" src="https://github.com/user-attachments/assets/767abcd8-7be3-4e41-ace6-9f9229d4a8c6" />
</div>


This screenshot illustrates the perspective of cybersecurity analysts, demonstrating how professionals conduct network monitoring. 
It also shows that Wireshark allows users to add and edit columns, enabling more customized and effective analysis.

<div>
<img width="508" height="179" alt="image" src="https://github.com/user-attachments/assets/84c46c45-541f-4e11-8eed-9da419a13ddc" />
</div>





<h2 style="color:lightblue;">Task 2 - Capturing Network Traffic using the Wireshark Application</h2>

The Wireshark application will be used to capture network traffic.
In the Apply a display filter, enter the following and click Apply display filter:



http


A filter has been applied to display specific network traffic that is being
captured
<div>
            <img width="508" height="179" alt="image" src="https://github.com/user-attachments/assets/d48cff51-ba62-4b1f-a593-466dbfd9365d" />
</div>



From the captured traffic, it can be determined the destination IP address
for connecting to the internet is 142.251.179.94, and the destination port is
80. In this environment, the source address is 10.0.0.0 and uses
Port 80

<div>
<img width="508" height="197" alt="image" src="https://github.com/user-attachments/assets/a0b9957b-6709-452a-90e9-66daf0c51f22" />
</div>



In the filter field, enter the following:
the ip address 142.251.0.0/24

<div>            
            <img width="508" height="197" alt="image" src="https://github.com/user-attachments/assets/b045f901-2d82-4a9e-9ec9-f1fa07862e99" /> 
</div>          



<h3 style="color:lightblue;"> Note </h3> 

                        Applying the ip. addr == 10.0.0.0/24 filter displays all the traffic
                        from the different hosts captured by the Wireshark application. A Cyber Security
                        Specialist can use this information to determine the different types of traffic from
                        different hosts and if it is legitimate traffic.


 <h2 style="color:lightblue;">  Task 3 - Capture Network Traffic using Tcpdump </h2>


 The tcpdump application is a command line utility that can be used to capture network
 traffic. In this task, the tcpdump command line utility will be used to capture network traffic.


 <div>
             <img width="755" height="295" alt="image" src="https://github.com/user-attachments/assets/e744face-b678-4202-a76f-53f5d3af7e7f" />
</div>


<h3 style="color:lightblue:" Note </h3>
The command is executed to determine which network interface on the
device will be used to capture network traffic.

