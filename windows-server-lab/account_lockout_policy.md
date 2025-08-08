## Objective
Configure account lockout settings in Windows Server 2022 to prevent brute-force login attempts and enhance account security.


## Steps
1. On the Domain Controller, open **Group Policy Management** by pressing `Windows + R`, typing `gpmc.msc`, and pressing **Enter**.
2. In the left pane, expand: `Forest: labnet.local → Domains → labnet.local`
3. Right-click the existing **Enforce Password Policy** GPO and select **Edit**.
4. In the Group Policy Management Editor, go to: `Computer Configuration → Policies → Windows Settings → Security Settings → Account Policies → Account Lockout Policy`
5. Set the following:
   - **Account lockout duration** → `35 minutes`
   - **Account lockout threshold** → `5 invalid logon attempts`
   - **Reset account lockout counter after** → `30 minutes`
6. Close the editor and run: `gpupdate /force` to apply the policy.
7. Verify settings by opening Command Prompt and typing: `net accounts.



## Screenshots

<img width="1916" height="1078" alt="Screenshot 2025-08-08 152606" src="https://github.com/user-attachments/assets/61e6fa15-d02a-40fd-a8b6-befac10c8d05" />
<img width="1917" height="1079" alt="Screenshot 2025-08-08 152632" src="https://github.com/user-attachments/assets/af35995a-545c-4949-8988-5c2b44c0a52d" />
<img width="1918" height="1079" alt="Screenshot 2025-08-08 152709" src="https://github.com/user-attachments/assets/79df0e3c-6db2-4198-bc26-179d27425010" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 152724" src="https://github.com/user-attachments/assets/32fc2c39-db9f-4c0e-8bb7-e2d0c5329d07" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 152849" src="https://github.com/user-attachments/assets/2ac6b860-3a65-4028-b143-02588d0709f6" />

## Outcome
The account lockout policy is now active with a threshold of 5 invalid logon attempts, a lockout duration of 35 minutes, and a reset time of 30 minutes.
