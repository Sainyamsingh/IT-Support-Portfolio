
# Promote Windows Server 2022 to a Domain Controller

## Objective
Configure the Windows Server 2022 machine as the first Domain Controller in a new forest.

## Steps
1. Open **Server Manager**.
2. In the top-right corner, click the **flag notification icon** and select **Promote this server to a domain controller**.
3. In the **Deployment Configuration** screen:
   - Select **Add a new forest**.
   - Enter a root domain name (e.g., `lab.local`).
   - Click **Next**.
4. On the **Domain Controller Options** screen:
   - Set **Forest functional level** and **Domain functional level** to **Windows Server 2016** or higher.
   - Ensure **Domain Name System (DNS) server** and **Global Catalog (GC)** are checked.
   - Enter and confirm a **Directory Services Restore Mode (DSRM)** password.
   - Click **Next**.
5. On the **DNS Options** screen:
   - Leave **Create DNS delegation** unchecked.
   - Click **Next** (warnings can be safely ignored in a lab setup).
6. On the **Additional Options** screen:
   - Verify the **NetBIOS domain name** and click **Next**.
7. On the **Paths** screen:
   - Leave default paths for the **Database**, **Log files**, and **SYSVOL** folders.
   - Click **Next**.
8. On the **Review Options** screen:
   - Confirm settings are correct.
   - Click **Next**.
9. On the **Prerequisites Check** screen:
   - Ensure all checks pass (warnings are acceptable in lab environments).
   - Click **Install**.
10. Wait for the installation to complete — the server will restart automatically.

## Screenshots

<img width="1896" height="1079" alt="Screenshot 2025-08-08 104804" src="https://github.com/user-attachments/assets/120a426b-3a91-48d8-89f9-b033d52aa4bf" />
<img width="1915" height="1079" alt="Screenshot 2025-08-08 104837" src="https://github.com/user-attachments/assets/e2106bc5-188a-4a41-8fe1-16b591d83618" />
<img width="1902" height="1069" alt="Screenshot 2025-08-08 104921" src="https://github.com/user-attachments/assets/750dfdc2-f5fc-40c0-88ad-f06a6ab8ea5b" />
<img width="1908" height="1078" alt="Screenshot 2025-08-08 105001" src="https://github.com/user-attachments/assets/dc7dc9fa-e4c7-4f7a-a3d9-2cb2505a3b65" />
<img width="1898" height="1070" alt="Screenshot 2025-08-08 105142" src="https://github.com/user-attachments/assets/163336d3-7d55-478c-96c5-974dbcca8102" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 105227" src="https://github.com/user-attachments/assets/0329e986-e5b0-4588-8c61-c5edd3b8e84b" />
<img width="1918" height="1079" alt="Screenshot 2025-08-08 105239" src="https://github.com/user-attachments/assets/db09ba13-76f0-41a3-8e99-e036e1dd3d6d" />
<img width="1861" height="1072" alt="Screenshot 2025-08-08 105247" src="https://github.com/user-attachments/assets/cbbd6d44-c066-4071-a1e8-a468eefec0ff" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 105306" src="https://github.com/user-attachments/assets/644ba221-91f9-4683-80e5-a283b507e735" />
<img width="1896" height="375" alt="Screenshot 2025-08-08 105410" src="https://github.com/user-attachments/assets/0ea8b132-353f-4dbe-8404-d7de5b3ac742" />

## Outcome
The server is successfully promoted to a Domain Controller for the new domain (e.g., `lab.local`), ready for domain user creation and client join operations.
