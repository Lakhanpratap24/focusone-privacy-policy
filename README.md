# Privacy Policy for FocusOne

Last updated: September 2026

FocusOne ("we", "our", or "the extension") is committed to protecting your privacy. This Privacy Policy explains how our browser extension handles user information.

### 1. Zero Data Collection
FocusOne operates under a strict Zero Surveillance principle. We do not collect, log, track, sell, or transmit any personally identifiable information, browsing history, website activity, or user data to external servers or third parties.

### 2. Local On-Device Storage
All extension settings—including custom blocklists, YouTube allowlists, scheduling preferences, and focus metrics—are stored 100% locally on your device via standard browser storage APIs (`chrome.storage.local`). This information never leaves your personal browser.

### 3. Permissions Usage
- **declarativeNetRequest / declarativeNetRequestWithHostAccess:** Used strictly on-device to intercept and block network requests to user-selected distracting websites and apply channel-filtering rules.
- **tabs / activeTab:** Used solely to detect the active tab's URL to determine if it matches your local blocklist and redirect to your local block screen when necessary.
- **alarms:** Used to trigger local countdown timers for scheduled focus sessions.
- **storage / unlimitedStorage:** Used exclusively to store your personal configuration, rules, and focus history on your local computer.
- **notifications:** Used solely to display local browser alerts when a focus session starts or ends.

### 4. Third-Party Services
FocusOne does not integrate third-party tracking scripts, analytics libraries, or advertising networks.

### 5. Changes to This Policy
If we update this policy, the updated version will be posted at this URL.

### 6. Contact
If you have any questions about this Privacy Policy, you can reach out via our official Chrome Web Store support listing or developer contact.
