# Salesforce DevOps PoC

This proof of concept demonstrates how to integrate DevOps practices into a Salesforce development pipeline using GitHub Actions, Salesforce DX, and version control.

## Features

- Version-controlled Salesforce metadata
- Automated deployments using GitHub Actions
- Salesforce CLI (SFDX) integration
- Deploys to authenticated sandbox org

## Prerequisites

- Salesforce Dev Hub enabled
- Salesforce CLI installed
- GitHub account
- Sandbox or Developer Org

## Setup

1. Clone this repo
2. Authenticate Salesforce org:
   ```bash
   sfdx auth:web:login -a DevOrg
