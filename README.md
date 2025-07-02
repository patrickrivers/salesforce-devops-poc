# Salesforce DevOps PoC

This repo demonstrates integrating DevOps practices into Salesforce using GitHub Actions, Salesforce DX, and version control.

## Setup

1. Authenticate Salesforce org:
   ```bash
   sfdx auth:web:login -a DevOrg
   ```
2. Export auth URL:
   ```bash
   sfdx force:org:display -u DevOrg --verbose > auth.txt
   ```
3. Copy the Sfdx Auth URL into a GitHub secret named `SALESFORCE_AUTH_URL`
4. Push to `main` to trigger deployment
