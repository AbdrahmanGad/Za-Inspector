# Privacy Policy for Za Inspector

**Last Updated:** January 3, 2026

## Introduction

Za Inspector ("the Extension") is a Chrome browser extension developed by Abdelrahman Gad. This privacy policy explains how we collect, use, and protect your information when you use our Extension.

## Information We Collect

### 1. Zoho Account Information
When you authenticate with Zoho CRM through our Extension, we access:
- Your name and email address (from your Zoho profile)
- Your organization/company name
- Your Zoho profile and role information

### 2. Zoho CRM Data
With your permission, the Extension accesses:
- CRM records you choose to view, export, or import
- Module and field metadata
- COQL query results

### 3. Authentication Tokens
- OAuth tokens are stored locally in your browser to maintain your session
- Tokens are never transmitted to any server other than Zoho's authentication endpoints

### 4. User Preferences
We store locally in your browser:
- Theme preference (Light/Dark/System)
- API version setting
- Saved COQL queries
- Query history

### 5. Permission Configuration
For organizations using the admin feature:
- Profile-based permission settings are stored in our Supabase database
- This includes: organization ID, profile names, and feature access permissions

## How We Use Your Information

Your information is used solely to:
- Authenticate you with Zoho CRM
- Display your CRM record data within the Extension
- Execute COQL queries on your behalf
- Export and import CRM data as you request
- Enforce organization-level feature permissions

## Data Storage

| Data Type | Storage Location |
|-----------|------------------|
| OAuth tokens | Your browser (chrome.storage.local) |
| User preferences | Your browser (chrome.storage.local) |
| CRM data | Temporarily in memory, not persisted |
| Permission configs | Supabase cloud database |

## Third-Party Services

### Zoho CRM
- We connect to Zoho CRM APIs to access your data
- Your data is transmitted directly between your browser and Zoho's servers
- Zoho's privacy policy: https://www.zoho.com/privacy.html

### Supabase
- Used only for storing organization permission configurations
- No personal CRM data is stored in Supabase
- Supabase privacy policy: https://supabase.com/privacy

## Data Sharing

We do NOT:
- Sell your personal information
- Share your data with third parties for marketing
- Use your data for advertising
- Transfer your data for purposes unrelated to the Extension's functionality

## Data Security

- All communications use HTTPS encryption
- OAuth tokens are stored securely in your browser
- No CRM data is stored on external servers
- Permission data in Supabase is protected by Row Level Security

## Your Rights

You have the right to:
- **Access**: View what data we have about you
- **Revoke**: Remove the Extension's access to your Zoho account at any time via Zoho's Connected Apps settings
- **Delete**: Uninstall the Extension to remove all locally stored data
- **Opt-out**: Choose not to use features that require certain data

## Data Retention

- Local browser data: Retained until you uninstall the Extension or clear browser data
- Permission configurations: Retained until your organization administrator removes them
- CRM data: Never persisted; only held temporarily in memory during use

## Children's Privacy

This Extension is not intended for use by children under 13 years of age. We do not knowingly collect personal information from children.

## Changes to This Policy

We may update this privacy policy from time to time. We will notify users of any material changes by updating the "Last Updated" date.

## Contact Us

If you have questions about this privacy policy or your data, please contact:

**Abdelrahman Gad**
Email: abdrahman.gad99@gmail.com

## Consent

By using Za Inspector, you consent to this privacy policy and agree to its terms.
