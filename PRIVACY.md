# Privacy Policy for LiTemplates

**Last Updated:** December 2025

LiTemplates is committed to ensuring the privacy and security of its users. This policy explains how our Chrome extension handles data.

### 1. Data Collection
LiTemplates does not collect any personally identifiable information (PII). The extension works by reading specific text fields (such as Browser IDs and IP patterns) from pages within the `onyx.www.linkedin.com` domain strictly to generate standardized templates for the user.

### 2. Data Storage
All user-defined settings and generated templates are stored locally on your device using the `chrome.storage` API. We do not have access to this data, and it is never transmitted to our servers or any third parties.

### 3. Remote Communications
The extension performs a single network request to GitHub to check a configuration file (`config.json`). This is used solely as an emergency "kill switch" to disable the extension if the target website updates and causes the extension to malfunction. No user data is sent during this check.

### 4. Third-Party Sharing
We do not sell, trade, or share user data with any third parties.

### 5. Contact
If you have questions about this policy, please contact: operarioa@gmail.com.
