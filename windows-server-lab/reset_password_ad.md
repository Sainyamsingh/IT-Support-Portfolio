
# Resetting a User Password in Active Directory

## Objective
Reset the password for an existing domain user account in Active Directory.

## Steps
1. Open **Server Manager** on the Domain Controller.
2. From the top menu, click **Tools** → **Active Directory Users and Computers**.
3. Expand the domain node (e.g., `lab.local`) in the left panel.
4. Navigate to the **Organizational Unit (OU)** or container where the user account is located.
5. Right-click the desired user account (e.g., `Jason Bourne`) and select **Reset Password**.
6. In the **Reset Password** dialog:
   - Enter the **New password**.
   - Re-enter it in **Confirm password**.
   - (Optional) Check **Unlock the user’s account** if the account is locked.
7. Click **OK** to save the new password.
8. Inform the user to log off and log back in with the new credentials.

## Screenshots

<img width="1903" height="1079" alt="Screenshot 2025-08-08 144304" src="https://github.com/user-attachments/assets/2454c264-aa1d-4141-8d1d-558a3d4265f5" />
<img width="1911" height="1076" alt="Screenshot 2025-08-08 144320" src="https://github.com/user-attachments/assets/81dcedaa-71c1-4a8d-8943-cf3620fb0535" />
<img width="1918" height="1079" alt="Screenshot 2025-08-08 144330" src="https://github.com/user-attachments/assets/aa80e97d-8cdb-4d2d-b4b7-c1b089dcbcfe" />



## Outcome
The selected user's password is successfully reset, and the account can now be accessed with the new credentials.
