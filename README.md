# FortiGate-VM-Firewall-Configuration-Lab

# Objective

This lab focused on configuring a FortiGate VM firewall to manage traffic between different network segments (LAN, DMZ, and WAN) by setting up interfaces, creating virtual IPs, and establishing firewall policies.

# Skills Learned

**Firewall Configuration:** Gained hands-on experience in configuring firewall interfaces and roles, improving my understanding of network segmentation.

**Virtual IP Management:** Learned how to create and manage virtual IPs for enabling external access to internal resources.

**Firewall Policy Development:** Developed skills in creating and managing firewall policies to control traffic flow, including understanding the implications of NAT settings.

**Network Security Principles:** Enhanced my knowledge of network security principles, including how to restrict access and define traffic permissions based on source and destination.

**Troubleshooting Skills:** Gained experience in troubleshooting access issues by monitoring firewall logs and policies.


# 1. Interface Configuration

The initial step involved investigating the network topology and configuring the interfaces connected to the FortiGate VM.

**Steps**
1. Access the Web GUI: Logged into the FortiGate VM using the provided credentials.
  
2. Investigate Network Topology: Verified the connections for LAN, DMZ, and WAN interfaces.
   
3. Edit Interfaces: Configured the ports as follows:
   
 **Port 2:**
  
   ![image](https://github.com/user-attachments/assets/9f1da63a-5d8f-4362-a891-bb12899f8368)


**Port 3:**
  
   ![image](https://github.com/user-attachments/assets/b6b01760-de1e-4521-a51d-b026a7c72bf0)



# 2. Virtual IP Configuration
To enable external access to a web server in the DMZ, virtual IPs were created to map requests from the WAN interface to the DMZ.

**Steps**
**Create Virtual IPs:**

![image](https://github.com/user-attachments/assets/3d861337-b432-431b-bb25-9088cde3d16c)

**Second Virtual IP:**

![image](https://github.com/user-attachments/assets/38b9f469-03c1-46ee-b469-f11a817ee4be)


# 3. Firewall Policy Configuration

Firewall policies were established to control traffic flow and ensure secure communication between the network segments.

# Steps

**WAN to DMZ Policy:**

![image](https://github.com/user-attachments/assets/2def2424-9721-43f6-a958-365b455c6333)


**LAN to DMZ Policy:**

![image](https://github.com/user-attachments/assets/8ad52990-5a9b-4de0-b0b8-61ccb8b5725c)



**LAN to WAN Policy:**

![image](https://github.com/user-attachments/assets/c210fda1-4771-47e8-a40b-83eccf4f1500)
