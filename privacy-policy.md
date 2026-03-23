# Privacy Policy for Header Hub

**Last Updated: 2026-03-23**

## 1. Introduction
Header Hub ("we", "our", or "the Extension") is committed to protecting your privacy. This Privacy Policy explains how we handle your data. As a developer-focused tool, our core philosophy is **"Zero-Backend"** and **"User-Controlled Data."**

## 2. Information Collection and Use
We believe your data belongs to you. 
- **No Personal Data Collection:** We do not collect, store, or transmit any of your personal information, browsing history, or HTTP header configurations to our own servers.
- **Zero-Backend:** We do not operate any backend servers that store your data.

## 3. Data Storage and Syncing
- **Local Storage:** All your HTTP header rules and configurations are stored locally on your device using Chrome's `chrome.storage.local` API.
- **Git Synchronization (Optional):** If you enable the team sync feature, your configuration data is transmitted directly between the extension and your chosen Git provider (e.g., Gitea, GitLab or Github). We highly recommend using **on-premise Gitea or GitLab** instances hosted by your own team. This ensures the **highest level of data sovereignty** and privacy, as your configuration remains entirely within your private network.

## 4. Third-Party Services
- **Gumroad:** We use Gumroad for license management. When you purchase a license, Gumroad's privacy policy applies to the transaction. Header Hub only verifies the license key via Gumroad's API.
- **Git Providers:** When you use the team sync feature, the privacy policy of your chosen Git provider (e.g., GitHub) applies.

## 5. Security
Because all data remains on your local machine or your private Git repository, you have full control over your security. We recommend using Fine-grained Personal Access Tokens with minimal required permissions.

## 6. Permissions Justification
Header Hub requests the following permissions only to provide its core functionalities. We follow the principle of "Least Privilege":

- **`storage`**: Required to store your header modification rules and extension settings locally on your device.
- **`declarativeNetRequest`**: Required to perform high-performance HTTP header modifications (add, set, or remove headers) based on your custom rules.
- **`declarativeNetRequestWithHostAccess`**: Required to modify headers on specific domains that you define. This ensures the extension can apply your rules to the network requests of the websites you choose to manage.
- **`cookies`**: Required to read or modify cookies within the HTTP headers when your rules specifically target cookie-related headers. This is essential for developers debugging session-related or authentication-related header issues.

**Note:** All operations performed using these permissions happen locally within your browser. No data accessed through these permissions is ever transmitted to our servers.

## 7. Changes to This Policy
We may update this Privacy Policy from time to time. Any changes will be reflected by the "Last Updated" date at the top.

## 8. Contact Us
If you have any questions about this Privacy Policy, please contact us at: **duoyunan@163.com**