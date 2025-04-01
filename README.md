# theodora_kpis
Theodora base code for demo
In the NIST Cybersecurity Framework, the control that specifically handles unauthorized login attempts falls under the "Protect" function, within the "Access Control" (PR.AC) category.

The specific control is PR.AC-7: "Authentication and authorization processes are in place and managed for people, devices, and other assets." Under this control, organizations implement measures such as:

- Account lockout policies after a defined number of failed login attempts
- Increasing time delays between login attempts
- Monitoring and alerting on failed login attempts
- Implementing multi-factor authentication to reduce the risk of unauthorized access

Organizations typically configure their systems to lock accounts temporarily or permanently after a certain number of consecutive failed login attempts, and to alert security personnel when unusual patterns of failed logins are detected.

This is an OSCAL Component Definition for the NIST Cybersecurity Framework control PR.AC-7 specifically focused on unauthorized login attempt detection and response.
This OSCAL representation includes:

A component definition for unauthorized login attempt detection
Implementation details for PR.AC-7 with three key statements:

Monitoring failed login attempts and triggering alerts
Implementing account lockout after consecutive failed attempts
Logging and reporting unauthorized access attempts


Configurable parameters for:

Maximum failed login attempts (set to 5)
Account lockout duration (set to 30 minutes)
Alert threshold (set to 3 attempts)



This OSCAL component can be integrated into a larger security control catalog or system security plan to document compliance with the NIST Cybersecurity Framework's access control requirements.
