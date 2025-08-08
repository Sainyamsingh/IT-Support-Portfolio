


# Configuring Network for Windows Server 2022 and Windows 10 (LabNet) & Disabling Firewall

## Objective
Configure both Windows Server 2022 and Windows 10 virtual machines to be on the same internal network (`LabNet`) with static IP addresses, and disable the firewall to ensure seamless communication.

## Steps

### 1. Configure Network Adapter for Both VMs
1. Open **Oracle VirtualBox**.
2. Select the VM (Windows Server 2022 or Windows 10) → Click **Settings**.
3. Go to **Network** → **Adapter 1**.
4. Set **Attached to:** `Internal Network`.
5. In **Name**, type: `LabNet`.
6. Click **OK**.


### 2. Configure Static IP on Windows Server 2022
1. Log in to **Windows Server 2022**.
2. Open **Control Panel** → **Network and Internet** → **Network Connections**.
3. Right-click **Ethernet** → **Properties**.
4. Select **Internet Protocol Version 4 (TCP/IPv4)** → Click **Properties**.
5. Select **Use the following IP address** and enter:
   - IP address: `192.168.10.1`
   - Subnet mask: `255.255.255.0`
6. Select **Use the following DNS server addresses** and enter:
   - Preferred DNS server: `127.0.0.1`
7. Click **OK** and close all windows.


### 3. Configure Static IP on Windows 10
1. Log in to **Windows 10**.
2. Open **Control Panel** → **Network and Internet** → **Network Connections**.
3. Right-click **Ethernet** → **Properties**.
4. Select **Internet Protocol Version 4 (TCP/IPv4)** → Click **Properties**.
5. Select **Use the following IP address** and enter:
   - IP address: `192.168.10.2`
   - Subnet mask: `255.255.255.0`
6. Select **Use the following DNS server addresses** and enter:
   - Preferred DNS server: `192.168.10.1`
7. Click **OK** and close all windows.



### 4. Disable Windows Firewall on Server 2022
1. Open **Control Panel** → **System and Security** → **Windows Defender Firewall**.
2. On the left, click **Turn Windows Defender Firewall on or off**.
3. For **Domain networks**, **Private networks**, and **Public networks**, select **Turn off Windows Defender Firewall**.
4. Click **OK**.



## Screenshots
<img width="1919" height="1079" alt="Screenshot 2025-08-08 134933" src="https://github.com/user-attachments/assets/5ffe5c47-15e7-498c-86b3-7220751996f7" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 135044" src="https://github.com/user-attachments/assets/00da32b1-a85d-4f6f-b17b-60b747c0f854" />
<img width="1909" height="1078" alt="Screenshot 2025-08-08 135221" src="https://github.com/user-attachments/assets/0f089a41-c6c2-483a-8a16-7dfe4b36abd3" />
<img width="1913" height="1079" alt="Screenshot 2025-08-08 135537" src="https://github.com/user-attachments/assets/7ba30b03-09e8-44ae-a2fa-a25e218780e0" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 135739" src="https://github.com/user-attachments/assets/7927e0d2-a794-4561-b26a-62a0a20e87a5" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 135839" src="https://github.com/user-attachments/assets/8af4b4e4-c841-4402-9cc9-94d70b6a8328" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 141028" src="https://github.com/user-attachments/assets/e1b59297-bb42-4a9c-b862-a17fd96bd8e1" />
<img width="1915" height="1076" alt="Screenshot 2025-08-08 141039" src="https://github.com/user-attachments/assets/0d3825b9-d183-480f-a14a-38425c5cb543" />




## Outcome
Both Windows Server 2022 and Windows 10 are now connected on the same internal network (`LabNet`) with static IP addresses and the firewall disabled, ensuring smooth communication between them.
