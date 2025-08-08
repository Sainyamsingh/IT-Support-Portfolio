# Configure VirtualBox Network for Windows Server 2022 and Windows 10 (Same Network)

## Objective
Configure Oracle VirtualBox network settings so that both the Windows Server 2022 VM and Windows 10 VM are connected to the same internal network (`LabNet`) for domain setup and communication.

## Steps
1. **Open VirtualBox** and select the first VM (**Windows Server 2022**).
2. Click **Settings** → **Network**.
3. In **Adapter 1**:
   - Check **Enable Network Adapter**.
   - Set **Attached to**: *Internal Network*.
   - Set **Name**: `LabNet` (must match exactly on both VMs).
4. Disable any other adapters (e.g., Adapter 2) unless internet access is needed.
5. Repeat the same steps for the **Windows 10 VM**:
   - **Adapter 1** → *Internal Network* → `LabNet`.
   - Disable Adapter 2 if not needed.
6. Start both VMs — they will now be in the same isolated network and able to communicate directly.

## Screenshots

<img width="1918" height="1079" alt="Screenshot 2025-08-08 134946" src="https://github.com/user-attachments/assets/315dda14-fe45-4c6f-9dbc-24f1f477bdcc" />

## Outcome
Both Windows Server 2022 and Windows 10 VMs are connected to the same isolated VirtualBox internal network `LabNet`, enabling domain join, ping tests, and other lab activities without internet interference.
