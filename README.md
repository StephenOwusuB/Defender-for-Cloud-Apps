## Defender for Cloud Apps - Lock Down Your Cloud Apps & Protect Data

Defender for Cloud Apps is a powerful solution that allows security operations teams to monitor and control cloud applications, ensuring data protection and security. It provides insights into the applications being used and offers mechanisms to block unwanted applications. 

### Key Features
- **Application Monitoring**: Identify and monitor cloud applications for security problems.
- **Automated Responses**: Automate responses to security threats.
- **Subscription Requirements**: Full features require an ES license or Enterprise Mobility + Security; a simplified version is available with Microsoft Business Premium.

### Enabling Defender for Cloud Apps
1. Go to the **Microsoft Defender portal**.
2. Select **Settings**.
3. Select **Endpoint**.
4. Select **Advanced Features**.
5. Scroll down to find **Microsoft Defender for Cloud Apps** and toggle it on.

### Cloud App Discovery
Defender for Cloud Apps discovers the cloud applications in your business through two methods:
1. **Upload Log Files**: Upload your log files from your local firewall (works with Business Premium).
2. **Integration with Defender for Endpoint**: Integrate with Defender for Endpoint for continuous automated reports.

### Creating a Report
1. Go to the **Microsoft Defender portal**.
2. Scroll to **Cloud Apps**.
3. Click on **Create a New Report**.
4. Select the firewall in your setup to pull data on the apps.

### Viewing Discovered Apps
- You will see a dashboard of apps, IP addresses, users, devices, and traffic.
- Select the **Discover Apps** tab to view discovered apps.

### Managing Applications
Microsoft has a catalog of over 30,000 apps scored based on 90 different factors. You can:
- **Sanction an Application**: Allow the application.
- **Unsanction an Application**: Block the application.
- **Monitor an Application**: Keep an eye on the application without blocking it.

### Cloud App Catalogs
- View the scores Microsoft has given to apps.
- Risk scores range from 0 to 10, with Microsoft apps scoring high due to their security, compliance, and legal factors.

### Action on Applications
- Search for applications in the catalog and take actions such as sanctioning, unsanctioning, or monitoring.

### Enforcing App Access
1. Go to **Settings**.
2. Select **Cloud Apps**.
3. Under **Cloud Discovery**, select **Microsoft Defender for Endpoint**.
4. Check the **Enforce App Access** checkbox.
   - This will block access to unsanctioned apps and provide warnings for monitored apps.
   - You can set user notifications, redirect URLs for warned users, and notification URLs for blocked apps.
   - Set bypass duration for warned apps.

### Policy Management
1. Go to **Cloud Apps**.
2. Scroll down to **Policies** and select **Policy Management**.
3. Click on **Create Policy**.
4. Select the policy template.
5. Specify the policy name and severity.
6. Configure alerts to be sent via email.
7. Under governance, you can sanction, unsanction, monitor, or custom tag applications.

---

This comprehensive guide helps you lock down your cloud apps and protect your data using Microsoft Defender for Cloud Apps.
