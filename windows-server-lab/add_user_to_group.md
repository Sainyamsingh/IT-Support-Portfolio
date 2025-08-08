# Objective
Add an existing Active Directory user (Jason Bourne) to a specific group.

# Steps
1. Open **Server Manager** on the Windows Server 2022 VM.
2. Go to **Tools** → **Active Directory Users and Computers**.
3. Expand the domain `lab.local` and navigate to the **Users** container.
4. Locate the user **Jason Bourne** in the list.
5. Right-click **Jason Bourne** and select **Add to a group**.
6. In the **Select Groups** window:
   - Ensure **From this location** is set to `lab.local`.
   - Type the name of the target group in the **Enter the object names to select** field.
   - Click **Check Names** to verify the group exists.
   - Click **OK** to add the user to the group.
7. Close the **Active Directory Users and Computers** console.

# Screenshots

<img width="1903" height="1079" alt="Screenshot 2025-08-08 144304" src="https://github.com/user-attachments/assets/3ec88e58-0a14-464b-bfed-cb889897bd1d" />
<img width="1911" height="1076" alt="Screenshot 2025-08-08 144320" src="https://github.com/user-attachments/assets/8fe21174-2553-42c6-bda7-825e23af31d3" />
<img width="1919" height="1079" alt="Screenshot 2025-08-08 144555" src="https://github.com/user-attachments/assets/866d5b6a-710f-47df-a444-30055e86b1be" />


# Outcome
The user **Jason Bourne** is now successfully added to the specified group in Active Directory.
