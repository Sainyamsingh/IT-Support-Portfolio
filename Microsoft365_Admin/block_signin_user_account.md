## Objective
Block a user's ability to sign in to Microsoft 365 to prevent access when an account is compromised or no longer in use.

## Steps
1. Sign in to the **Microsoft 365 Admin Center**.
2. Navigate to **Users** > **Active users**.
3. Select the target user (e.g., *Dexter Morgan*).
4. In the user details panel, click **Block sign-in**.
5. In the Block Sign-In window:
   - Check the box **Block this user from signing in**.
   - Review the note indicating the user will be signed out of all sessions within 60 minutes.
6. Click **Save changes**.
7. Confirm that the user’s profile now shows **Sign-in blocked**.

## Screenshots

<img width="1919" height="1079" alt="Screenshot 2025-08-07 161436" src="https://github.com/user-attachments/assets/8d901eff-274f-4bbc-a8c6-4ab3a7557da7" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 161443" src="https://github.com/user-attachments/assets/cf177532-2e42-4fa1-90c9-3f763ccad8dd" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 161451" src="https://github.com/user-attachments/assets/e1ab0d0a-c149-43ff-b78b-617bc9167866" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 161500" src="https://github.com/user-attachments/assets/ba5ab62a-d3f9-416c-8156-b381db9bb753" />


## Outcome
The selected user will no longer be able to sign in to Microsoft 365 services. Any active sessions will be terminated within 60 minutes, but the account will still be able to receive email unless additional mailbox restrictions are applied.
