## Objective
Disable a specific user account in Active Directory.

## Steps
1. Open Server Manager and go to Tools > Active Directory Users and Computers.
2. Expand the domain (lab.local) and select the Users container.
3. Locate the target user (Jason Bourne), right-click, and select Disable Account.
4. Confirm that the user icon now shows a disabled arrow overlay.
5. Attempting to log in with this account will display an “Object has been disabled” message.

## Screenshots

<img width="1903" height="1079" alt="Screenshot 2025-08-08 144304" src="https://github.com/user-attachments/assets/eabce6e4-0410-4967-843f-93314d1135eb" />
<img width="1911" height="1076" alt="Screenshot 2025-08-08 144320" src="https://github.com/user-attachments/assets/7f92444e-831d-413d-8e09-44f124d57a7b" />
<img width="1919" height="987" alt="Screenshot 2025-08-08 144610" src="https://github.com/user-attachments/assets/40e7afad-69d6-47d6-b5e8-6637abfc2ed8" />

## Outcome
The selected user account is now disabled and cannot log in until re-enabled.
