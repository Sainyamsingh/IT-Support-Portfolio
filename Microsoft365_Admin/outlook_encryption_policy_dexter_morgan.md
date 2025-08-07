# Outlook Message Encryption (OME) Configuration for Dexter Morgan

## Objective

Enable email encryption for Dexter Morgan so that he can use built-in Outlook options (e.g., Encrypt or Do Not Forward) when composing emails. This ensures secure email transmission and data protection.


## Steps Performed

### Step 1: Create New Sensitivity Label

- Open **Microsoft 365 Compliance Center**
- Go to **Information protection** under **Solutions**
- Select **Labels > Create a label**
- Label name: `Encrypt - Only Dexter Morgan`
- Description: Allows encryption for Dexter Morgan’s account only

## Step 2: Set Encryption Settings

- Under **Encryption**, enable **Encrypt emails and files**
- Choose **Assign permissions now**
- Allowed users/groups: `dextermorgan@aquila993.onmicrosoft.com`
- Permissions: `View`, `Reply`, `Reply All`, `Forward`
- Allow offline access: Yes
- Content expires: Never

## Step 3: Publish Label

- Go to **Label policies**
- Create a new policy: `Dexter Encryption Policy`
- Add the new label `Encrypt - Only Dexter Morgan`
- Assign the policy to: `dextermorgan@aquila993.onmicrosoft.com`


## 📷 Screenshots


<img width="1919" height="946" alt="Screenshot 2025-08-07 094259" src="https://github.com/user-attachments/assets/f26811a3-97ea-44da-a866-4caad149bd91" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 094530" src="https://github.com/user-attachments/assets/33e2068c-abc8-45de-abc1-ff0a256dae8d" />
<img width="1918" height="922" alt="Screenshot 2025-08-07 094542" src="https://github.com/user-attachments/assets/1713472c-0401-47a4-bd5b-1aa2bf85421d" />
<img width="1912" height="1079" alt="Screenshot 2025-08-07 094602" src="https://github.com/user-attachments/assets/a3697eb7-7dfc-42f6-b3a8-d428a56c4de9" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 094611" src="https://github.com/user-attachments/assets/9e4cc0fe-a9b4-4238-a9a3-e18978a22de2" />
<img width="1912" height="1078" alt="Screenshot 2025-08-07 094623" src="https://github.com/user-attachments/assets/32695bac-9caf-4530-9be0-97d5da6e998b" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 094708" src="https://github.com/user-attachments/assets/6f215eb4-1ebc-4733-9461-3adea1692319" />
<img width="1897" height="1017" alt="Screenshot 2025-08-07 095207" src="https://github.com/user-attachments/assets/d1874d0e-9cc1-4519-af37-31dd296559a6" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 095257" src="https://github.com/user-attachments/assets/b8eaefd6-be19-4173-957c-7b4cedb85f6a" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 094719" src="https://github.com/user-attachments/assets/dfabfa53-bc35-4d34-b4ba-0296a53008a8" />
<img width="1912" height="1077" alt="Screenshot 2025-08-07 094750" src="https://github.com/user-attachments/assets/4adba4e2-7a62-4f88-ac10-ab588c542c9d" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 094803" src="https://github.com/user-attachments/assets/bf1cbd94-f50b-4855-8258-8344e0540f0b" />
<img width="1917" height="1078" alt="Screenshot 2025-08-07 094826" src="https://github.com/user-attachments/assets/457b3dac-b52a-4e41-a945-bd4a61237c45" />
<img width="1904" height="1073" alt="Screenshot 2025-08-07 094835" src="https://github.com/user-attachments/assets/73257b35-5ac9-4c41-aa9e-b2582e0970df" />
<img width="1916" height="1026" alt="Screenshot 2025-08-07 094931" src="https://github.com/user-attachments/assets/d81b39f1-0eaf-4e38-969d-3fbbdb295434" />
<img width="1915" height="1076" alt="Screenshot 2025-08-07 095015" src="https://github.com/user-attachments/assets/5bae0f47-40c4-406a-ab00-18254acf195d" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 095533" src="https://github.com/user-attachments/assets/1ddc893b-472f-4532-b4e6-44023f1a6775" />




## Outcome

After 24 hours, Dexter Morgan will see new encryption options such as **Encrypt** and **Do Not Forward** directly in his Outlook when composing a new message.
