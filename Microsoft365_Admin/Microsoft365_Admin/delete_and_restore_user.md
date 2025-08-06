# Microsoft 365 – Delete and Restore a User

This document outlines the steps to delete a user from Microsoft 365 and later restore that user account with selected configuration options.

## Task Overview

- Delete a user account from the Microsoft 365 Admin Center
- Restore the same user account
- Set a custom password during restore
- Skip the option requiring the user to reset password on first sign-in
- Review optional email/OneDrive delegation settings (left disabled)

## Steps Performed

### 1. Deleting the User

1. Logged in to the Microsoft 365 Admin Center  
   https://admin.microsoft.com/

2. Navigated to → Users → Active users

3. Selected the user: **Dexter Morgan**

4. Clicked **Delete a user**

5. Left all additional OneDrive/email delegation options unchecked, including:
   - Give access to OneDrive
   - Convert mailbox to shared

6. Clicked **Delete user**

7. Received confirmation:
   - License unassigned  
   - User account deleted

### 2. Restoring the User

1. Navigated to → Users → Deleted users

2. Selected: **Dexter Morgan**

3. Clicked **Restore user**

4. Chose:
   - "Let me create the password"  
   - Entered a strong password manually  
   - Left "Require user to change password on first sign-in" unchecked

5. Clicked **Restore**

6. Got confirmation:
   Dexter Morgan has been restored  
   - Password reset  
   - User active again in Active users list

## Screenshots

<img width="1919" height="1079" alt="Screenshot 2025-08-06 125446" src="https://github.com/user-attachments/assets/002c6ca5-3f56-4f33-a64e-e9831bd196df" />

<img width="1919" height="1078" alt="Screenshot 2025-08-06 125600" src="https://github.com/user-attachments/assets/67278151-73e6-4401-bd00-7679d0d4fb47" />

<img width="1919" height="1079" alt="Screenshot 2025-08-06 125610" src="https://github.com/user-attachments/assets/d201b0ce-0555-4202-b184-93b85abe78b1" />

<img width="1919" height="1079" alt="Screenshot 2025-08-06 125627" src="https://github.com/user-attachments/assets/55e4c423-2d4a-4750-9b50-53aaf9a72667" />

<img width="1919" height="1079" alt="Screenshot 2025-08-06 125803" src="https://github.com/user-attachments/assets/d0222c63-06a7-41e1-a2c6-126a6d447fe6" />

<img width="1919" height="1052" alt="Screenshot 2025-08-06 125820" src="https://github.com/user-attachments/assets/04366e4d-caea-4c20-84a5-f66a4ee76242" />


## Outcome

The user `dextermorgan@aquila993.onmicrosoft.com` was deleted and then restored successfully.

- A custom password was assigned instead of using the auto-generated option.
- The option to force a password change on next sign-in was not enabled.
- OneDrive and email delegation settings were not configured during deletion, so no other user was given access to the deleted account’s data.

## Notes

- Deleted users can be restored within 30 days.
- If email or OneDrive delegation is not configured during deletion, access to those services is lost unless backed up externally.
- Password settings during restore allow manual creation for controlled sign-ins.
