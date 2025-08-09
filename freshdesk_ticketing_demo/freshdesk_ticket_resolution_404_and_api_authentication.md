Objective
Document handling of two Freshdesk tickets for Emily Garcia (Acme Inc): (1) “404 error when on a specific page” and (2) “Authentication failure (API)”. Show replies sent, status changes, and final resolution.

Steps
1) Ticket #1 – 404 error when on a specific page
- Open the ticket and confirm details from the requester.
- Reply: Explain it was a temporary server outage and ask her to retry in 5 minutes. Offer to investigate further if it persists.
- Set Status → Waiting on Customer. Priority → Urgent. Type → Incident.
- After customer confirms the page works, set Status → Closed.

2) Ticket #2 – Authentication failure (API)
- Open the ticket and confirm it concerns API access (programmatic, not web UI login).
- Reply with MFA instructions:
  - Inform about the newly enforced authentication method.
  - Ask the user to set up Microsoft Authenticator.
  - Tell them to log in and add a new Multi-Factor Authentication method when prompted.
  - Critical step: they must click the link shown after typing credentials and pressing OK; if they don’t click the link, they will see “authentication failed.”
- Set Status → Waiting on Customer. Priority → Urgent. Type → Question.
- After the customer confirms successful API access post-MFA setup, set Status → Closed.

Screenshots

<img width="1919" height="1079" alt="Screenshot 2025-08-09 121108" src="https://github.com/user-attachments/assets/37e40bd7-1d68-4b0b-ad1b-cbc074b9dfbc" />
<img width="1919" height="1079" alt="Screenshot 2025-08-09 121150" src="https://github.com/user-attachments/assets/f946d827-5729-453f-8367-16bff12238b8" />
<img width="1907" height="1057" alt="Screenshot 2025-08-09 122637" src="https://github.com/user-attachments/assets/f2ee2731-c5c1-4e1d-a3aa-96de2bc1c004" />
<img width="1918" height="1077" alt="Screenshot 2025-08-09 123511" src="https://github.com/user-attachments/assets/1609fc10-b677-4e7a-9025-a534139db554" />
<img width="1910" height="1069" alt="Screenshot 2025-08-09 123523" src="https://github.com/user-attachments/assets/9ba27d90-74e1-4a8d-88d9-1cef9e995625" />
<img width="1919" height="1079" alt="Screenshot 2025-08-09 123649" src="https://github.com/user-attachments/assets/44094d05-2160-4753-93b9-09ba1986bee6" />
<img width="1915" height="1071" alt="Screenshot 2025-08-09 124348" src="https://github.com/user-attachments/assets/43645760-479d-44b5-9621-7a904bc95881" />
<img width="1919" height="1079" alt="Screenshot 2025-08-09 124438" src="https://github.com/user-attachments/assets/33225870-6129-4497-890e-4c8566dc4c76" />
<img width="1919" height="1079" alt="Screenshot 2025-08-09 124607" src="https://github.com/user-attachments/assets/031d28fa-7cde-42e2-86c7-fda876fc0b56" />


Outcome
- Ticket #1 (404 error): Customer retried after the outage window; the page loaded successfully. Ticket closed.
- Ticket #2 (API authentication): Customer followed MFA setup with Microsoft Authenticator and clicked the post-login link. Authentication succeeded; API access restored. Ticket closed.
- **Note:** The “Message not delivered” banner was caused by having the same ticket open in multiple Chrome tabs. Messages were in fact delivered, and the customer’s reply was received.

