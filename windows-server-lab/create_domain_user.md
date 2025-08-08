
# Create a New Domain User in Active Directory

## Objective
Add a new user account, "Jason Bourne", to the Active Directory domain (`lab.local`).

## Steps
1. Log in to the Domain Controller as **Administrator**.
2. Open **Server Manager**.
3. From the top-right menu, click **Tools** → **Active Directory Users and Computers (ADUC)**.
4. In the left pane, expand the domain (`lab.local`).
5. Right-click the **Organizational Unit (OU)** where you want to create the user (e.g., `I.T`) and select **New** → **User**.
6. In the **New Object – User** window:
   - **First name:** Jason  
   - **Last name:** Bourne  
   - **Full name:** Jason Bourne  
   - **User logon name:** `jasonb`  
   - Click **Next**.
7. Set the account password and confirm it.
8. Select desired password options:
   - User cannot change password  
   - Password never expires
9. Click **Next**, then **Finish** to create the account.

## Screenshots

<img width="1919" height="1079" alt="Screenshot 2025-08-08 105853" src="https://github.com/user-attachments/assets/6ed69252-49a3-4ca8-8e75-bf9b7890cfbe" />
<img width="1905" height="1064" alt="Screenshot 2025-08-08 110020" src="https://github.com/user-attachments/assets/d6d8b3c5-064f-4c46-bc94-4565d2ba59a4" />
<img width="1919" height="1078" alt="Screenshot 2025-08-08 110114" src="https://github.com/user-attachments/assets/a355e28e-0c9b-4407-a055-261760b9048e" />
<img width="1877" height="1077" alt="Screenshot 2025-08-08 110217" src="https://github.com/user-attachments/assets/367852a0-b3cd-4643-8f5a-992ea30b77ba" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 110322" src="https://github.com/user-attachments/assets/bdb38344-ebcd-4d96-bcbc-580324d8fe45" />
<img width="1908" height="1079" alt="Screenshot 2025-08-08 110448" src="https://github.com/user-attachments/assets/ce51033a-feb3-404e-9904-0e607d4eb523" />

## Outcome
A new domain user "Jason Bourne" (`jasonb@lab.local`) is created in Active Directory, ready to log in to domain-joined devices.
