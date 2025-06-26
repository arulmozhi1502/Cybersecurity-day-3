## Tool: Qualys Community Edition

### Installation Summary:
- Downloaded agent from Qualys portal.
- Installed with Customer ID and Activation ID.
- Used correct WebService URI for India (`qg1` region).

1. Wait 5–15 minutes
- The agent will now automatically connect to Qualys servers
- Your system will appear under:
- Qualys Dashboard → Cloud Agent → Assets

2. Check Your Scan Results
- After a few minutes:
- Go to Cloud Agent → Assets
- Click on your PC/hostname
- u can check for your vulnerability status (`refer to screenshots attached`)



### Operation:
- Agent ran in the background.
- Scan completed automatically within 10–15 mins.

### Outcome:
- No vulnerabilities detected.
- Machine appears clean and secure.

### Troubleshooting Faced:
- Missing WebServiceUri parameter (fixed).
- Required admin privilege to run the installer (fixed).
