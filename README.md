# VPN Setup and Usage with ProtonVPN

This was a hands-on project where I set up a Virtual Machine (VM) in Azure, installed a VPN client, and experimented with how IP addresses and website behaviors change based on location. It was an exciting way to explore cloud technology, networking, and online privacy tools.

---

## **Tools and Technologies I Used:**
- **Microsoft Azure**: For creating and managing VMs  
- **Remote Desktop Protocol (RDP)**: To access and control the VM  
- **ProtonVPN**: For masking IP addresses and testing VPN functionality  

### **Operating System:**
- Windows 10 Pro (Version 22H2)

---

## **What I Did:**

### 1. Setting Up the Virtual Machine:
- First, I went to [WhatIsMyIPAddress](https://whatismyipaddress.com/) from my personal computer to check and save my current IP address for comparison.  
- Then, I logged into Azure and created a new Resource Group.  
- Next, I set up a Windows 10 VM in a completely different region—choosing a location far from mine (a different country made this more interesting).  
- Once the VM was ready, I connected to it using Remote Desktop.  
- From the VM, I checked [WhatIsMyIPAddress](https://whatismyipaddress.com/) again to see its default IP address and noted how it differed from my own machine.  

![screenshot](https://github.com/Jalal-Hatamleh/Proton-VPN/blob/main/images/1.png?raw=true)

---

### 2. Using ProtonVPN in the VM:
- On my personal computer, I signed up for ProtonVPN’s free plan at [ProtonVPN Signup](https://protonvpn.com/signup).  
- Inside the VM, I downloaded and installed the ProtonVPN client.  
- After logging in at [ProtonVPN Login](https://protonvpn.com/login), I connected to a server in another country (Japan, in this case).  
- Once the VPN was active, I checked [WhatIsMyIPAddress](https://whatismyipaddress.com/) again and recorded the new IP address.  
- For fun, I visited websites like Google, Disney, and Amazon to see how they adapted to the VPN's server location. The differences were fascinating—some sites displayed in Japanese, others showed prices in different currencies, and the URLs even changed slightly.

![screenshot](https://github.com/Jalal-Hatamleh/Proton-VPN/blob/main/images/2.png?raw=true)

---

## **Examples of IP Addresses I Observed:**

### **Without VPN (VM):**
- **IPv4:** 172.214.244.206  
- **ISP:** Microsoft Limited  
- **City:** Chicago  
- **State:** Illinois  
- **Country:** United States  

### **With VPN (VM):**
- **IPv4:** 212.8.250.219  
- **ISP:** WorldStream B.V.  
- **Service:** Network Sharing Device  
- **City:** Bucharest  
- **Region:** Bucharest  
- **Country:** Romania  

---

## **What I Learned:**

- **Creating and Managing VMs**: Setting up and accessing a Virtual Machine in Azure was a great hands-on way to understand the basics of cloud computing.  
- **Geolocation and IP Addresses**: I saw firsthand how the location of a VM or VPN server influences its IP address and how websites interpret that.  
- **VPN Functionality**: ProtonVPN showed me how easy it is to mask an IP address, providing privacy and the ability to browse as if I were in another country.  
- **Website Localization**: Watching how websites adapted to the VPN’s location—changing language, currency, and even layouts—was fascinating.  
- **Privacy and Security**: This project reinforced how important tools like VPNs are for securing online activity by encrypting traffic and hiding your true location.  

---

## **Why This Was Fun and Useful:**

This wasn’t just a technical experiment; it was a practical way to understand concepts that are highly relevant in networking, cloud computing, and cybersecurity. Plus, seeing the immediate impact of changing locations through a VPN made it feel very real. If you're curious about exploring these technologies, this is a great way to start!
