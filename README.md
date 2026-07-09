# PAM-Program

This capstone draws on Module 07. The brief: Northwind’s privileged accounts are a mess — shared, permanent, unrotated, unmonitored. Design the PAM program that fixes it, and be able to narrate the full lifecycle of a single privileged action.

The brief:
Bring the Domain Admin, production root, and key service accounts under control. Choose the controls, eliminate standing privilege, and define how a privileged action flows from request to recorded completion with the credential dead afterward.

What a good PAM program includes:
Discover & onboard privileged accounts into the vault — including the hidden ones (local admins, forgotten service accounts).
Vault + rotate — no human holds a standing privileged password; credentials rotate after use and on schedule.
Exclusive checkout with MFA — one holder at a time, authenticated, with a reason, for accountability.
Session isolation + recording — privileged connections proxied through a hardened host and fully recorded.
Just-in-time, least-privilege elevation — eliminate standing admin; grant the minimum rights only at moment of need.
Monitor & report — detect anomalous privileged behavior and retain evidence.

- Denise Banks
