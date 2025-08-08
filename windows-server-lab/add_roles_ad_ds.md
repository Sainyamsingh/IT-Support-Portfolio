# Add Active Directory Domain Services (AD DS) Role

## Objective
Install the Active Directory Domain Services (AD DS) role on Windows Server 2022 to prepare the server for promotion to a Domain Controller.

## Steps
1. Log in to Windows Server 2022 as **Administrator**.
2. Open **Server Manager** (it launches automatically on login).
3. In the **Dashboard**, click **Add roles and features**.
4. On the **Before You Begin** screen, click **Next**.
5. Select **Role-based or feature-based installation** and click **Next**.
6. Choose your server from the **Server Pool** and click **Next**.
7. In the **Select server roles** list:
   - Check **Active Directory Domain Services**.
   - Click **Add Features** when prompted.
   - Click **Next**.
8. Review the **Features** screen (leave defaults) and click **Next**.
9. On the **AD DS** description page, click **Next**.
10. On the **Confirmation** screen, ensure **Restart the destination server automatically if required** is unchecked.
11. Click **Install** and wait for the installation to complete.
12. Do not close Server Manager — you will promote the server to a Domain Controller in the next step.

## Screenshots
<img width="1864" height="1076" alt="Screenshot 2025-08-08 103749" src="https://github.com/user-attachments/assets/8c3d37b9-b106-4562-8219-031bab862778" />
<img width="1903" height="1073" alt="Screenshot 2025-08-08 103757" src="https://github.com/user-attachments/assets/5aaeff8e-3b2a-484c-92fc-8dfd5c0c7120" />
<img width="1916" height="1077" alt="Screenshot 2025-08-08 103819" src="https://github.com/user-attachments/assets/a9cb2788-0d02-4952-ae87-ed908579d407" />
<img width="1834" height="1056" alt="Screenshot 2025-08-08 103900" src="https://github.com/user-attachments/assets/77cd350c-e00e-472f-affe-378c09fb346e" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 103945" src="https://github.com/user-attachments/assets/fe77c96e-f29e-48ba-ae3d-5a31fff12637" />
<img width="1887" height="1073" alt="Screenshot 2025-08-08 104038" src="https://github.com/user-attachments/assets/a65efb38-2220-4055-86eb-1179a8409d43" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 104229" src="https://github.com/user-attachments/assets/2af89d99-717e-488a-af59-e5ec105f69d1" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 104245" src="https://github.com/user-attachments/assets/9118f02c-d899-4e66-b609-ed0894e63b79" />
<img width="1893" height="1071" alt="Screenshot 2025-08-08 104552" src="https://github.com/user-attachments/assets/d789af39-d773-4f9c-9c1b-de00f65b246c" />
<img width="1896" height="1079" alt="Screenshot 2025-08-08 104804" src="https://github.com/user-attachments/assets/3d925fab-0633-4108-bb8b-0ad5aaf9ce55" />

## Outcome
The AD DS role is successfully installed on Windows Server 2022, and the server is ready to be promoted to a Domain Controller.
