# Privacy Policy for EasyEmails

**Last Updated: April 13, 2026**

EasyEmails ("we," "our," or "the Extension") is committed to protecting your privacy. This Privacy Policy explains how we handle information when you use our Chrome extension.

### 1. Data Collection and Usage
EasyEmails is designed to be a **privacy-first** tool. 
*   **Automatic Extraction**: The extension scans the DOM (text and links) of webpages you visit to identify email addresses. This process happens entirely within your browser.
*   **No External Transmission**: Extracted email addresses, page titles, and URLs are stored **locally** on your device. No data is ever sent to our servers, third-party services, or any external location.

### 2. Data Storage
*   **Local Storage**: All data extracted by the extension is stored using the `chrome.storage.local` API. This data remains on your physical machine and is not synced across your Google Account unless you have Chrome's native sync enabled (and even then, only within your encrypted Google Cloud profile).
*   **User Control**: You have full control over your data. You can clear your entire extraction history or individual entries directly from the extension's popup interface at any time.

### 3. Third-Party Sharing
We **do not** share, sell, or rent your data to any third parties. Since we never collect your data on our servers, it is impossible for us to share it.

### 4. Permissions
EasyEmails requires the following permissions to function:
*   `storage`: To save your extracted emails locally.
*   `activeTab` & `scripting`: To identify emails on the webpage you are currently viewing.
*   `<all_urls>`: To allow the extension to work on any website you choose to browse.
*   `clipboardWrite`: To allow you to copy emails to your clipboard.

### 5. Changes to This Policy
We may update our Privacy Policy from time to time. Any changes will be reflected in an updated version of the extension and this document.

### 6. Contact Us
If you have any questions about this Privacy Policy, please contact the developer via the official support channels on the Chrome Web Store.

---

**By using EasyEmails, you agree to the practices described in this policy.**
