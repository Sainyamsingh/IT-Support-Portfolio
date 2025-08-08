# Windows Server 2022 VM Setup in VirtualBox

## Objective
Prepare and configure a VirtualBox virtual machine for installing the GUI version of Windows Server 2022.

## Steps
1. Open **Oracle VM VirtualBox** and click **New**.
2. Enter a name for the VM (e.g., `WinServer2022`).
3. Select **Microsoft Windows** as the type and **Windows 2022 (64-bit)** as the version.
4. Allocate memory (recommended: 4096 MB or more).
5. Create a new virtual hard disk (VDI) and set its size (minimum 50 GB).
6. Attach the Windows Server 2022 ISO file to the VM’s optical drive.
7. Adjust CPU count (recommended: 2 or more) under **System → Processor**.
8. Enable network adapter in **Bridged Adapter** mode for domain lab connectivity.
9. **Important:** During installation later, when prompted to choose an edition, select  
   **Windows Server 2022 Standard (Desktop Experience)** or **Datacenter (Desktop Experience)** to enable the GUI interface.
10. Save the configuration.

## Screenshots
<img width="1071" height="555" alt="Screenshot 2025-08-08 100738" src="https://github.com/user-attachments/assets/846f07f4-e4a6-400f-b0b2-afba040b0ab1" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 095845" src="https://github.com/user-attachments/assets/2b636559-430c-4832-8218-1bfbb73ce486" />
<img width="1914" height="1079" alt="Screenshot 2025-08-08 095856" src="https://github.com/user-attachments/assets/aeab68cb-6b20-49e4-a643-bc8d2c0f17d4" />
<img width="1888" height="1066" alt="Screenshot 2025-08-08 095904" src="https://github.com/user-attachments/assets/49e1b37f-400c-4808-8cf3-0661323d3955" />
<img width="1917" height="1079" alt="Screenshot 2025-08-08 095958" src="https://github.com/user-attachments/assets/f35d1164-9816-4a43-b9f6-fd8d5fb34678" />
<img width="1897" height="1079" alt="Screenshot 2025-08-08 103316" src="https://github.com/user-attachments/assets/17460ce0-8a59-4204-b13f-98632c0a69ef" />

## Outcome
A new VirtualBox virtual machine is created and configured, ready to install the GUI version of Windows Server 2022.
