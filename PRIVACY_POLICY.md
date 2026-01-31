# Privacy Policy for FaceClock

**Last Updated:** January 30, 2026

## Introduction

FaceClock ("we," "our," or "the app") is a workforce time tracking application that uses facial recognition technology to verify employee attendance. This Privacy Policy explains how we collect, use, store, and protect your information.

## Information We Collect

### Biometric Data
- **Facial Images:** The app captures photographs of employees' faces during registration and clock-in/clock-out events.
- **Facial Embeddings:** Mathematical representations of facial features are generated and stored locally on your device for identity verification purposes.

### Employee Information
- Employee names
- Employee identification numbers
- Profile photographs

### Time and Attendance Data
- Clock-in and clock-out timestamps
- Shift duration records
- Photographs taken at clock-in/clock-out events

### Device Information
- Device settings preferences (e.g., screen timeout, maximum shift hours)

## How We Use Your Information

We use the collected information solely for:
- Verifying employee identity during clock-in and clock-out
- Recording attendance and shift data
- Generating time tracking reports
- Managing employee profiles within your organization

## Data Storage

### Local Storage Only
**All data is stored exclusively on your device.** FaceClock operates entirely offline and does not:
- Transmit data to external servers
- Use cloud storage services
- Share data with third parties
- Require internet connectivity

Data is stored in:
- A local SQLite database within the app's private directory
- The app's private file storage for photographs

### Data Security
- All data is stored in the app's private storage area, inaccessible to other applications
- Photos and database files are protected by Android's application sandboxing
- The app does not request network permissions

### No Remote Access
**Important:** The developer has no ability to remotely access, view, modify, or delete any data stored by this app. Because FaceClock:
- Does not connect to the internet
- Does not have any server infrastructure
- Stores all data exclusively on your local device

The developer cannot assist with data recovery, remote data deletion, or accessing your stored information under any circumstances. All data management must be performed directly on the device where the app is installed.

## Data Retention

### Automatic Data Cleanup
- Shift records and associated photographs older than **90 days** are automatically deleted
- This cleanup process runs periodically in the background
- Employee profiles and registration photos are retained until manually deleted by an administrator

### Manual Deletion
- Administrators can delete individual employee records at any time
- Uninstalling the app removes all stored data from the device

## Biometric Data Disclosure

In accordance with biometric privacy regulations:

1. **Purpose:** Facial recognition is used solely for employee identity verification during time tracking.

2. **Storage:** Biometric data (facial embeddings) is stored only on the local device and is never transmitted externally.

3. **Retention:** Biometric templates are retained for as long as the employee profile exists in the system.

4. **No Sale or Sharing:** We do not sell, lease, trade, or otherwise profit from biometric data.

5. **Protection:** Biometric data is protected using Android's built-in application security model.

## Google Cloud Backup

By default, Android may back up app data to Google Cloud. We recommend:
- Disabling backup for this app in your device settings if you have concerns about biometric data in cloud backups
- Consulting your organization's data protection policies regarding cloud backup of employee information

## Children's Privacy

FaceClock is intended for workplace use by adults. We do not knowingly collect information from children under 13 years of age.

## Your Rights

Since all data is stored locally on the device and the developer has no access to it, any requests regarding your personal data must be directed to the device administrator or organization that operates the FaceClock installation.

The device administrator can:
- Show you what data is stored about you in the app
- Delete your employee profile and all associated data
- Uninstall the app to remove all data completely

## Data Controller

The organization or individual that deploys FaceClock on their devices acts as the sole data controller. They are responsible for:
- Obtaining appropriate consent from employees
- Complying with applicable privacy laws
- Managing data subject requests
- All data management and deletion

**The developer (Evgeny Lazarev) is not a data controller or processor** as no data is transmitted to or accessible by the developer. The developer provides only the software application itself.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the "Last Updated" date at the top of this document. Continued use of the app after changes constitutes acceptance of the updated policy.

## Compliance

This app is designed to support compliance with:
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Illinois Biometric Information Privacy Act (BIPA)
- Other applicable biometric and data protection laws

Organizations deploying this app are responsible for ensuring their use complies with local regulations.

## Contact

For questions about this Privacy Policy or the app's data practices, please contact:

**Developer:** Evgenii Lazarev
**GitHub:** https://github.com/eslazarev/faceclock
**Email:** eslazarev@gmail.com

---

## Summary

| Data Type | Collected | Stored Locally | Sent to Servers | Retention |
|-----------|-----------|----------------|-----------------|-----------|
| Facial Images | Yes | Yes | No | Until deleted |
| Facial Embeddings | Yes | Yes | No | Until deleted |
| Employee Names/IDs | Yes | Yes | No | Until deleted |
| Shift Records | Yes | Yes | No | 90 days |
| Shift Photos | Yes | Yes | No | 90 days |

**Key Points:**
- All data stays on your device
- FaceClock never connects to the internet
- The developer cannot remotely access or delete your data
