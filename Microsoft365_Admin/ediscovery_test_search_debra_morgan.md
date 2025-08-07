# eDiscovery Test Search – Debra Morgan


##  Objective

To perform an eDiscovery mailbox search for Debra Morgan using Microsoft Purview by configuring proper permissions, creating a case, and running a keyword-based query with date filter.


## Steps

### 1. Assigned Permissions
- Opened Microsoft Defender portal → Permissions tab.
- Selected role group: `eDiscovery Manager`.
- Confirmed the following roles are included:
  - Export
  - Hold
  - Preview
- Verified: `Sainyam Sainyam` is added under `eDiscovery Administrator`.

### 2. Created a New Case
- Navigated to: Microsoft Purview → eDiscovery (Standard).
- Clicked `Cases` → `Create case`.
- Named the case: `test case`.

### 3. Created a Search
- Inside the `test case`, clicked `Searches` → `Create a search`.
- Named the search: `test search`.

### 4. Configured the Query
- Used the **Condition Builder**:
  - Keyword: `Miami`
  - Date: Before `August 7, 2025`

### 5. Selected Data Sources
- Added the following mailboxes:
  -  Debra Morgan (`debramorgan@aquila993.onmicrosoft.com`)
  -  Dexter Morgan (`dextermorgan@aquila993.onmicrosoft.com`)
- Location scope: `Mailboxes only`

### 6. Ran the Search
- Clicked `Run query`



## 📸 Screenshots

<img width="1919" height="1079" alt="Screenshot 2025-08-07 124559" src="https://github.com/user-attachments/assets/4b497c5e-4848-457f-913c-224bbd6b8064" />
<img width="1919" height="1045" alt="Screenshot 2025-08-07 124613" src="https://github.com/user-attachments/assets/d4769a5b-51a2-43d9-ae08-99cb4b3ebb1a" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 124819" src="https://github.com/user-attachments/assets/9f843251-633f-40eb-bf5e-050727e2b266" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 125804" src="https://github.com/user-attachments/assets/d04157cc-b561-4df4-9ba4-0868f2625454" />
<img width="1916" height="1059" alt="Screenshot 2025-08-07 125822" src="https://github.com/user-attachments/assets/7227fe24-0011-4420-ac9d-311c72f9a0cb" />
<img width="1919" height="1070" alt="Screenshot 2025-08-07 130244" src="https://github.com/user-attachments/assets/1b5a5b44-a555-45f6-9ab1-0d9b26ebdee2" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 130458" src="https://github.com/user-attachments/assets/8f08224c-8783-46ce-8c42-4aa1e5a22cef" />



##  Outcome

- The search was created using the visual **Condition Builder**, which is why the result summary said: “Query does not contain keywords” — this is normal behavior.
- The search returned **2 matching emails** from **Debra Morgan's mailbox**, and **0** from Dexter Morgan, proving the filters were applied correctly.
- All necessary permissions were active and the search operation succeeded without error.
