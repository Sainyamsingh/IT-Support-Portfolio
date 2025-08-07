# Modify Connection Filter Policy – Microsoft Defender

## Objective

To configure the default Connection filter policy by allowing or blocking specific IP address ranges in Microsoft 365 Defender.

## Steps

1. Opened Microsoft 365 Defender portal.
2. Navigated to Email & collaboration → Policies & rules → Threat policies → Anti-spam policies.
3. Selected the default policy: `Connection filter policy (Default)`.
4. Under the policy settings:
   - Added `1.2.3.4/24` to the “Always allow messages from the following IP addresses” field.
   - Added `10.10.10.10/244` to the “Always block messages from the following IP addresses” field.
5. Saved the changes to apply the updated IP filtering configuration.

## Screenshots

<img width="1918" height="1077" alt="Screenshot 2025-08-07 150700" src="https://github.com/user-attachments/assets/267d1221-b0fd-4190-8a38-8cc777bf2616" />



## Outcome

- IP addresses were successfully added to the allow/block lists within the default Connection filter policy.
- Note: **Prebuilt policies such as this cannot be deleted — only modified.**
