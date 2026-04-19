# Privacy Policy for EasyEmails

**Last Updated: April 19, 2026**

EasyEmails ("we," "our," or "the Extension") is committed to protecting your privacy and being transparent about how we handle data. This Privacy Policy explains our practices regarding the collection, storage, and usage of information when you use our Chrome extension.

### 1. Data Collection and Usage
EasyEmails is a **privacy-by-design** tool. To provide its core functionality, the extension identifies and collects the following types of information from the webpages you visit:
*   **Email Addresses**: The primary data identified during scanning.
*   **Metadata**: Names, job titles, and company names found in the immediate context of an email address.
*   **Source Information**: The URL and page title where a specific email address was found.

**Important Disclosure**: While the extension collects Personally Identifiable Information (PII), **all extraction data is processed and stored locally on your device.** No contact data is ever transmitted to our servers or third parties.

### 2. Licensing and Verification
*   **Gumroad Integration**: If you upgrade to the Pro version, your license key is sent to Gumroad's API (`api.gumroad.com`) to validate your subscription.
*   **Session-Based Checks**: The extension may occasionally re-verify your license status against Gumroad at the start of a session to ensure continued access to Pro features. No PII from your extraction history is ever included in these verification requests.

### 3. Storage and Data Management
*   **Local Storage**: We use `chrome.storage.local` to store your extraction history, trial usage counts, and security-critical metadata. This data stays on your machine.
*   **Sync Storage**: We use `chrome.storage.sync` to synchronize your custom settings, such as your website blacklist, ignore rules, and theme preferences, across your logged-in Google Chrome profiles.
*   **Full User Control**: You can delete individual entries or clear your entire history at any time via the Side Panel or Options page. Uninstalling the extension automatically removes all data stored by the extension in Chrome.

### 4. Third-Party Sharing
We **do not** sell, rent, or share your data with any third parties. Outside of its communication with Gumroad for licensing, EasyEmails makes no outbound network connections.

### 5. Permissions Explained
To function correctly, EasyEmails requires the following permissions:
*   `storage`: To save your extracted data and preferences.
*   `sidePanel`: To display the management interface.
*   `contextMenus`: To allow "Right-Click to Extract" triggers.
*   `Host Permissions` (`*://*/*`): To allow the extension's scanning engine to identify contact information on the websites you choose to visit.

### 6. Security
We implement high-standard security measures, including input sanitization and XSS (Cross-Site Scripting) protection, to ensure that captured data cannot execute malicious code within the extension environment.

### 7. Contact Us
For questions regarding this policy or the extension's data practices, please reach out via the official support channels on the Chrome Web Store.

---

**By using EasyEmails, you acknowledge and agree to the local data practices described in this policy.**
