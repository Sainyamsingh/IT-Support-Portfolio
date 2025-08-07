# force_mfa_for_all_accounts



## Objective
Enforce Multi-Factor Authentication (MFA) for all users in Microsoft 365 and confirm that login requires a second method of authentication.

## Steps Performed
1. Logged into Microsoft 365 Admin Center as Global Administrator.
2. Navigated to:
   Admin Center > Azure Active Directory > Users > Per-user MFA
3. Opened the "Multi-Factor Authentication" settings panel.
4. Selected all users and set MFA status to "Enforced".
5. Logged in as user `debramorgan@aquila993.onmicrosoft.com` to test enforcement.
6. Upon login, Microsoft forced setup of a second authentication method.
7. Chose Microsoft Authenticator App as the secondary method.
8. Completed setup of the app and confirmed successful MFA configuration.

## Screenshots

<img width="1919" height="1079" alt="Screenshot 2025-08-07 114353" src="https://github.com/user-attachments/assets/3b492901-e549-4269-b073-f71943d224b0" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 114411" src="https://github.com/user-attachments/assets/4fb7fa6e-408a-4d15-9a63-11240cbf9759" />
<img width="1908" height="1075" alt="Screenshot 2025-08-07 114451" src="https://github.com/user-attachments/assets/3c2f6388-fddc-4d18-9d4c-f5f271aa9aae" />
<img width="1918" height="1077" alt="Screenshot 2025-08-07 114518" src="https://github.com/user-attachments/assets/1d4820c5-98f1-47b8-86cd-4572ddf85903" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 114557" src="https://github.com/user-attachments/assets/97dd8a6c-2e76-4e2a-b4a1-924c79c33eb6" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 114805" src="https://github.com/user-attachments/assets/29561ec2-4d0c-40d2-9ac2-0b57218e4db7" />
<img width="1919" height="1078" alt="Screenshot 2025-08-07 114816" src="https://github.com/user-attachments/assets/22427fe6-6610-4210-9e95-ce20d0288f3e" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 114826" src="https://github.com/user-attachments/assets/66fa0698-0e8b-4727-9a4c-12ed7d9d0ba5" />
<img width="1916" height="1072" alt="Screenshot 2025-08-07 115717" src="https://github.com/user-attachments/assets/09dfb92b-058a-4f0c-882f-f49e8cad2e08" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 115733 - Copy" src="https://github.com/user-attachments/assets/63749287-992d-4f90-9b9d-5336e8a03cec" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 115746 - Copy" src="https://github.com/user-attachments/assets/f9483b5c-d83f-4f93-808b-98ffaf7a5498" />


## Outcome
- Multi-Factor Authentication was successfully enforced across all accounts.
- Confirmed functionality by logging in as Debra Morgan and verifying Microsoft Authenticator setup requirement.
