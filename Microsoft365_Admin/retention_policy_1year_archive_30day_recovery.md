## Create Retention Tag (Delete & Allow Recovery) and Apply 1-Year Archive Retention Policy

## Objective:
To create a retention tag that deletes emails but allows 30-day recovery, and apply a retention policy that moves emails older than 1 year to the archive.

## Steps:

1. Go to the Microsoft Purview compliance portal.
2. In the left-hand menu, select **Data lifecycle management**.
3. Under **Microsoft 365**, click **Retention tags**.
4. Click **+ Create a tag**.
5. Name the tag: `Delete and Allow Recovery`
6. Under **Retention settings**, configure:
   - Retain items for: **30 days**
   - Action after this period: **Delete items and allow recovery**
7. Complete the tag setup and click **Submit**.
8. Now go to the **Retention policies** section.
9. Click **+ Create policy**.
10. Name the policy: `Archive 1-Year Old Mails`
11. Under **Retention action**, select:
    - Move items to archive after: **1 year**
12. Select applicable workloads (e.g., Exchange email).
13. Complete and submit the policy.

## Screenshots:

<img width="1919" height="1079" alt="Screenshot 2025-08-06 162800" src="https://github.com/user-attachments/assets/4b43c0da-4734-4e9d-a367-e26d7896aed9" />
<img width="1919" height="1078" alt="Screenshot 2025-08-06 162825" src="https://github.com/user-attachments/assets/3edd61a3-5343-4f48-8741-7985b3c81027" />
<img width="1919" height="1076" alt="Screenshot 2025-08-06 162847" src="https://github.com/user-attachments/assets/31c54214-200c-4bcf-9fc4-49387be769d4" />
<img width="1896" height="1063" alt="Screenshot 2025-08-06 162914" src="https://github.com/user-attachments/assets/9b81ce8b-6b06-4c32-8ab7-62cbdbfd44b4" />
<img width="1918" height="1079" alt="Screenshot 2025-08-06 163043" src="https://github.com/user-attachments/assets/f384934f-f253-45a6-9f76-7029d9aa928a" />
<img width="1919" height="1079" alt="Screenshot 2025-08-06 163051" src="https://github.com/user-attachments/assets/b713c007-b283-4d1d-bc62-33602e1e1ef5" />


## Outcome:

Retention tag and archive policy were successfully created and applied.
