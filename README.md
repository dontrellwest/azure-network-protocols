<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Powershell
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<h3>Step 1 - Download Windows App (**Mac Users Only, Windows Users Use Remote Desktop)</h3>
<img width="1552" alt="Step 1a - Download Windows App" src="https://github.com/user-attachments/assets/4b2ac2a6-336d-423e-be4a-dbf05e3ffec6" />
<img width="1512" alt="Step 1b - Download Windows App" src="https://github.com/user-attachments/assets/37631ba2-558b-474d-940b-bb6a5d08e74a" />
<img width="1512" alt="Step 1c - Download Windows App" src="https://github.com/user-attachments/assets/9a3ef34b-f762-4ac9-8443-b5f7ce186e52" />
<img width="1507" alt="Step 1d - Download Windows App" src="https://github.com/user-attachments/assets/688a282d-0b34-45a2-9809-7b73d2fcc71c" />
<img width="1511" alt="Step 1e - Download Windows App" src="https://github.com/user-attachments/assets/57886238-b822-49de-b25c-8e46496f1849" />

<h3>Step 2 - Download Wireshark In Remote Connection</h3>
<img width="1512" alt="Step 2a - Download Wireshark" src="https://github.com/user-attachments/assets/53a743e0-f314-49f7-97fe-cfed1a7ccc49" />

<h3>Step 3 - Ping ICMP</h3>
<img width="1512" alt="Step 3a - Ping ICMP" src="https://github.com/user-attachments/assets/994b1bcb-a21e-42a4-ab22-9b6e8316c4c8" />
<img width="1512" alt="Step 3b - Ping ICMP" src="https://github.com/user-attachments/assets/ca1b6407-4753-4836-9a74-94ce7072a2d1" />
<img width="1512" alt="Step 3c - Ping ICMP" src="https://github.com/user-attachments/assets/bedaee60-bb01-4d65-8c06-b2dc4ee44e14" />
<img width="1423" alt="Step 3d - Ping ICMP" src="https://github.com/user-attachments/assets/02e48adb-a025-4a04-bbc4-0b9fa9835229" />
<img width="1512" alt="Step 3e - Ping ICMP" src="https://github.com/user-attachments/assets/5e7200cd-96fd-4bbb-95ee-395665c36ebf" />

<h3>Step 4 - Network Security Group</h3>
<img width="1512" alt="Step 4a - Network Security Group" src="https://github.com/user-attachments/assets/4e277382-279d-49a6-aeb5-da53f0f22793" />
<img width="1628" alt="Step 4b - Network Security Group" src="https://github.com/user-attachments/assets/b1758aed-89c5-4dac-9aa0-2143c17d571d" />
<img width="1629" alt="Step 4c - Network Security Group" src="https://github.com/user-attachments/assets/42687851-ea46-4eed-bb9b-7958c4877ccb" />
<img width="1632" alt="Step 4d - Network Security Group" src="https://github.com/user-attachments/assets/8c4c9af0-10c3-4d12-b167-4f955b92fc83" />
<img width="1512" alt="Step 4e - Network Security Group" src="https://github.com/user-attachments/assets/5aa9eb51-95d4-4799-8419-dc39119023ce" />
<img width="1633" alt="Step 4f - Network Security Group" src="https://github.com/user-attachments/assets/74edcad2-3269-49c3-baf3-8b537c6cad99" />
<img width="1512" alt="Step 4g - Network Security Group" src="https://github.com/user-attachments/assets/1cbd9ded-1e4e-4277-8e85-3b15935947b2" />

<h3>Step 5 - SSH</h3>
<img width="1512" alt="Step 5a - SSH" src="https://github.com/user-attachments/assets/1674d3a6-b241-45c8-851b-33c764dfba6b" />
<img width="1512" alt="Step 5b - SSH" src="https://github.com/user-attachments/assets/28183f48-cd89-42da-9a78-71cd9ad6230a" />
<img width="544" alt="Step 5c - SSH" src="https://github.com/user-attachments/assets/5c754751-2354-4adf-a25a-35c7e4fc541c" />

<h3>Step 6 - DHCP</h3>
<img width="764" alt="Step 6a- DHCP" src="https://github.com/user-attachments/assets/c0eb6caf-6bd4-4a0a-9db7-ded146c36ec9" />
<img width="764" alt="Step 6b- DHCP" src="https://github.com/user-attachments/assets/cbe319b1-6f4d-43a8-8e04-d6c4bb58e49e" />

<h3>Step 7 - DNS</h3>
<img width="1512" alt="Step 7a- DNS" src="https://github.com/user-attachments/assets/608e00dd-723c-498a-b442-78d02f923c3b" />

<h3>Step 8 - RDP</h3>
<img width="1512" alt="Step 8a - RDP" src="https://github.com/user-attachments/assets/96cedc2b-25a4-4b0d-bedc-34199620c4e9" />


