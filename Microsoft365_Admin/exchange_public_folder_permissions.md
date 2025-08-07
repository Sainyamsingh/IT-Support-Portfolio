# Public Folder Setup and Permissions – Exchange Admin Center

## Objective

To create a public folder and mailbox in Exchange Admin Center, and assign appropriate permissions to users Dexter Morgan and Sainyam Sainyam.

## Steps

1. Opened the Exchange Admin Center and navigated to Public Folders.
2. Added a new Public Folder Mailbox named `Public Mailbox` to host public folders.
3. Created a new Public Folder with:
   - Name: `Public Folder`
   - Options checked:
     - Mail-enabled
     - Allow external users to email this public folder
4. Enabled the folder under `IPM_SUBTREE` and confirmed it is mail-enabled.
5. Assigned permissions:
   - Sainyam Sainyam: Owner
   - Dexter Morgan: Reviewer
6. Verified permission levels:
   - Sainyam has full access and modification rights.
   - Dexter has read-only access to the folder.
7. Configured message delivery settings to:
   - Accept messages from: All senders
   - Block messages from: None

## Screenshots


<img width="1919" height="1079" alt="Screenshot 2025-08-07 141521" src="https://github.com/user-attachments/assets/f570047e-c301-4012-bc91-bdef970618db" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 141609" src="https://github.com/user-attachments/assets/115a2654-c7e2-4f21-8098-09df73c84f21" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 141634" src="https://github.com/user-attachments/assets/b11535a8-bf9f-41d2-8df9-2773f54aca8a" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 142932" src="https://github.com/user-attachments/assets/7b6f1806-876c-4b53-a634-0eafcfd4b566" />
<img width="1918" height="1075" alt="Screenshot 2025-08-07 142939" src="https://github.com/user-attachments/assets/b5f8cf3c-974a-4c68-b2fe-74341037551c" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 143040" src="https://github.com/user-attachments/assets/2825dc73-e8e7-4cf1-b6c8-4f05fa46e284" />
<img width="1919" height="1036" alt="Screenshot 2025-08-07 143108" src="https://github.com/user-attachments/assets/cf85cf9e-b24f-4728-9cb8-49289febaf1c" />


## Outcome

- A public mailbox and public folder were successfully created.
- Sainyam Sainyam was granted Owner-level access with full control.
- Dexter Morgan was added with Reviewer-level access (read-only).
- Mail flow is unrestricted for all senders; the folder is mail-enabled and external email is allowed.
