# Packet Tracer - Configure a Wireless Router and Clients
## Objectives
  * Part 1: Connect the Devices
  * Part 2: Configure the Wireless Router
  * Part 3: Configure IP Addressing and Test Connectivity
## Instructions
### Part 1: Connect the Devices
In the process of setting up home network, the connection of devices involves two main steps: connecting coaxial cables and network cables.
#### Step 1: Connecting Coaxial Cables
* ##### Accessing the Network Components:
   I started by clicking on the 'Connections' icon, represented by a lightning bolt, in the Network Components section.
* ##### Selecting the Coaxial Cable:
   Next, I located and clicked on the icon for the Coaxial cable, which is depicted as a blue zigzag line.
* ##### Connecting to the Cable Splitter:
   I then clicked on the Cable Splitter and selected the Coaxial1 port to initiate the connection.
* ##### Linking to the Cable Modem:
   Following that, I clicked on the Cable Modem and chose Port 0 to establish the internet service connection.
* ##### Connecting the Television:
   I repeated the earlier steps but this time, I connected Coaxial2 from the Cable Splitter to Port 0 on the TV to set up the video service.
* ##### Activating the TV:
   Finally, I clicked on the TV and then clicked 'ON' for Status. Upon successful connections, an image representing a TV program appeared, confirming that everything was set up correctly.
#### Step 2: Connect the network cables
Here's how I would describe the steps as I perform them, focusing on connecting the network cables within house:
* ##### Accessing Connection Tools:
   I begin by opening the 'Connections' section and selecting the 'Copper Straight-Through cable', which is represented by a solid black line.
* ##### Connecting the Cable Modem to the Router:
   Next, I connect Port 1 on the Cable Modem directly to the Internet port of the Home Wireless Router. This is essential for providing internet access to the network.
* ##### Connecting the Office PC:
   I then proceed to the Office PC and plugin the cable to the FastEthernet0 port. I navigate to the Home Wireless Router and connect the other end of the cable to the GigabitEthernet 1 port, establishing the network connection for the office PC.
* ##### Connecting the Bedroom PC:
   Following the same steps, I connect the Bedroom PC by plugging one end of another Ethernet cable into the FastEthernet0 port of the PC. I then connect the other end to the GigabitEthernet 2 port on the Home Wireless Router.

By following these steps, I have successfully set up a wired network that connects both PCs in house to the internet via the cable TV provider network, ensuring stable and reliable internet and network access.

### Part 2: Configure the Wireless Router
Here's how I went about configuring the wireless router in Natsumi's network:
#### Step 1: Access the home wireless router GUI.
* ##### Opening IP Configuration:
   On the Office PC, I clicked the Desktop tab and then the IP Configuration.
* ##### Enabling DHCP:
   I selected DHCP to automatically configure the IP settings to match the Home Wireless Router's network.
* ##### Updating IP Configuration:
   After a brief wait, I checked if the IPv4 address updated to start with 192. I clicked Fast Forward Time to speed up the DHCP process as needed.
* ##### Noting the Default Gateway:
   I made a note of the default gateway address, which is the Home Wireless Router's IP address.
* ##### Accessing the Router's GUI:
   I opened the Web Browser, entered the default gateway IP address into the URL box, and hit Go. Using the default credentials 'admin' for both username and password, I accessed the router's GUI.
#### Step 2: Configure basic settings.
* ##### Setting DHCP Limits:
   In the Setup tab under Network Setup, I found the DHCP server settings. I set the Maximum Number of Users to 10 and saved the settings. This helps secure the network in a densely populated area.
* ##### Changing Admin Password:
   Next, I navigated to the Administration tab, changed the default password to MyPassword1!, and saved. I logged in again using the new credentials to confirm the change.
#### Step 3: Configure a wireless LAN.
* ##### Activating the Wireless Network:
   I clicked on the Wireless tab and enabled the 2.4 GHz network by selecting Enable.
* ##### Setting the Network Name:
   I changed the Network Name (SSID) from Default to MyHome and saved the settings. This name will appear when searching for Wi-Fi networks.
* ##### Securing the Network:
   Under the Wireless Security settings, I selected WPA2 Personal for the 2.4 GHz network, ensuring the strongest available security.
* ##### Configuring the Passphrase:
   I set the passphrase to MyPassPhrase1! to secure the network, making sure to note the importance of capitalization.
* ##### Finalizing Settings:
   After saving all the settings, I closed the Web Browser on the Office PC.
By following these steps, I successfully configured Natsumi's wireless router to provide a secure and functional home network.

### Part 3: Configure IP Addressing and Test Connectivity
Here's the process I followed to configure IP addressing for the PCs and laptop, and to verify their connectivity to the internet:
#### Step 1: Connect the laptop to the wireless network.
* ##### Accessing Wireless Settings:
   On the Laptop located in the living room, I clicked on the Desktop tab and then on PC Wireless.
* ##### Connecting to the Network:
   I clicked the Connect tab, waited briefly, and then selected the wireless network named MyHome that I had set up earlier.
* ##### Entering Passphrase:
   I entered the passphrase MyPassPhrase1! in the Pre-shared Key field and clicked Connect.
* ##### Verifying Connection:
   After connecting, I clicked on the Link Information tab to confirm the successful connection to the access point. I checked the More Information for IP details; I used Fast Forward Time to ensure the IP address started with 192.
* ##### Testing Internet Access:
   Finally, I opened the Web Browser on the Laptop and navigated to skillsforall.srv to confirm internet connectivity, using Fast Forward Time as needed for the page to load.
#### Step 2: Test connectivity from the Office PC.
* ##### Opening Web Browser:
   On the Office PC, I clicked the Desktop tab and opened the Web Browser.
* ##### Verifying Internet Access:
   I entered skillsforall.srv in the URL box and clicked Go. The webpage loaded after a brief delay, confirming that the Office PC was connected to the internet. I used Fast Forward Time to speed up the process.
#### Step 3: Configure the Bedroom PC.
* ##### Setting IP Configuration:
   I opened the IP Configuration on the Bedroom PC and set it to DHCP. I verified that it received an IP address starting with 192.
* ##### Testing Internet Access:
   I then opened the Web Browser on the Bedroom PC, navigated to skillsforall.srv, and clicked Fast Forward Time until the page loaded, verifying internet connectivity.
## Key Learnings from the Network Setup Project
From this project, I learned several valuable lessons and skills that are essential for setting up and managing home networks:
* ##### Understanding Network Components:
   I gained a deeper understanding of how different network components like modems, routers, and switches work together. This knowledge is crucial for troubleshooting and optimizing network performance.
* ##### Configuring Network Settings:
   I learned how to access and configure the settings of a wireless router through its GUI. This includes setting up DHCP, adjusting the number of users, and securing the network with passwords.
* ##### Network Security Practices:
   The importance of changing default passwords and setting up strong wireless encryption (WPA2) to secure the network against unauthorized access was a key takeaway.
* ##### Troubleshooting Connectivity Issues:
   I practiced troubleshooting connectivity issues by verifying IP addresses and using tools like 'Fast Forward Time' to simulate network changes and speed up DHCP assignments.
* ##### Practical Application of Theoretical Knowledge:
   Applying theoretical knowledge about IP addressing and network configuration in a practical scenario helped solidify my understanding and gave me hands-on experience.
* ##### Importance of Detailed Documentation:
   I learned the importance of maintaining detailed documentation throughout the setup process. This is crucial for future troubleshooting and for others who might work on the network.
These skills and insights are not only applicable to home networks but also provide a foundation for managing larger, more complex network environments.








