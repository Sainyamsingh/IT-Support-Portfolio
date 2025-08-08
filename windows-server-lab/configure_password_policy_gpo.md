
# Configure Password Policy via Group Policy Object (GPO)

## Objective
To configure and enforce domain-wide password policies such as complexity requirements and minimum password length using a Group Policy Object (GPO) in Windows Server 2022.

## Steps
1. Open **Group Policy Management** (`gpmc.msc`) on the domain controller.
2. Expand **Forest: labnet.local** → **Domains** → **labnet.local**.
3. Right-click **labnet.local** → **Create a GPO in this domain, and Link it here…**.
4. Name the GPO **Enforce Password Policy**.
5. Right-click the GPO → **Edit**.
6. Navigate to **Computer Configuration** → **Policies** → **Windows Settings** → **Security Settings** → **Account Policies** → **Password Policy**.
7. Configure the following:
   - **Enforce password history** → 5 passwords remembered  
   - **Maximum password age** → 40 days  
   - **Minimum password length** → 6 characters  
   - **Password must meet complexity requirements** → Enabled
8. Close the editor.
9. Open Command Prompt (Admin) → run `gpupdate /force` to apply changes.
10. Verify settings with the command `net accounts`.

## Screenshots

<img width="1919" height="1073" alt="Screenshot 2025-08-08 145510" src="https://github.com/user-attachments/assets/70df9a0c-1d87-466b-ad2e-c0e0c850a311" />
<img width="1915" height="1079" alt="Screenshot 2025-08-08 145518" src="https://github.com/user-attachments/assets/8bac7c09-9d6b-46b2-9c7e-b5958a545080" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 145545" src="https://github.com/user-attachments/assets/13e59053-6dbb-4fce-80ae-a91c9bb4ccbf" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 145731" src="https://github.com/user-attachments/assets/336edff5-b66b-4991-94ac-82cfc12abc4a" />
<img width="1913" height="1075" alt="Screenshot 2025-08-08 145834" src="https://github.com/user-attachments/assets/c07a0321-1085-45c8-a92f-5f8c25a0a6fd" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 145857" src="https://github.com/user-attachments/assets/167b7fef-a889-47ce-9403-eafb9cae7368" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 150039" src="https://github.com/user-attachments/assets/10b35214-406a-406b-9024-a8d86cddd3fa" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 150130" src="https://github.com/user-attachments/assets/16e563f7-0333-4a9d-832f-51e2fc1e5df4" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 150224" src="https://github.com/user-attachments/assets/75f2588b-2ca9-4b5c-baac-d6f5e3be0ec1" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 150245" src="https://github.com/user-attachments/assets/68653a2e-c459-4d2e-9a68-9854a7df578f" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 150304" src="https://github.com/user-attachments/assets/07dd1634-38a8-4167-95a7-bd4bb628cc6e" />



## Outcome
Password complexity and minimum length policies are now enforced across the domain via Group Policy.
