# Privacy Policy

**Application Name:** Linkn App
**Developer:** Miya.Yang
**Effective Date:** November 11, 2025
**Last Updated:** November 12, 2025

---

## Introduction

Thank you for using Linkn App. We are committed to protecting your personal privacy and data security. This Privacy Policy details how we collect, use, store, and protect your personal information.

By using Linkn App, you consent to the data collection and usage practices described in this Privacy Policy.

---

## 1. Information We Collect

We collect the following information through Firebase Authentication services for account management and core synchronization services:

### 1.1 User Identity Information
- **Email Address**: Your email address from Google or Apple Sign-In
- **User Identifier**: Unique Firebase User ID (UID)
- **Login Timestamps**: Account creation and last login times

### 1.2 Notion Integration Information
- **Notion Authorization Token**: Encrypted token authorized by you to access your Notion database
- **Notion Database ID**: Identifier of your chosen Notion database for synchronization
- This token is stored securely in Firebase Firestore and used by Cloud Functions to perform synchronization

### 1.3 Link Metadata
- **URLs**: Web links you capture or add
- **Page Titles and Descriptions**: Metadata automatically extracted from URLs
- **Status Tags**: Reading status such as To Read, On Hold, Completed
- **Custom Tags**: Classification tags you add
- **Timestamps**: Link creation and last modification times

### 1.4 Device Information
- **Device Type**: iOS, Android, or desktop platform information (used only for debugging and optimizing user experience)
- **App Version**: Used for compatibility checks

### 1.5 Usage Data (Optional)
- **Crash Reports**: Anonymous technical information when the app crashes (requires user consent)
- **Performance Data**: App loading times and response speeds (anonymized)

---

## 2. How We Use Your Information

We use the collected information solely for the following purposes:

### 2.1 Account Management
- Verify your identity and manage your Linkn App account
- Synchronize your account information across multiple devices

### 2.2 Provide Core Services
- Enable synchronization of your links to your Notion database
- Implement three-way data synchronization between local device, Firebase Cloud, and Notion
- Store your links, tags, and reading status

### 2.3 AI Processing (Paid Feature)
- Use your link metadata to call Google Gemini API
- Provide intelligent tag suggestions and content summarization services
- This is an optional paid feature requiring your explicit consent

### 2.4 Customer Support
- Respond to your inquiries and resolve technical issues
- Diagnose and fix application errors

### 2.5 Service Improvement
- Analyze app usage patterns to improve user experience (using only anonymized aggregate data)
- Develop new features and optimize existing functionality

---

## 3. Information Sharing and Third-Party Services

### 3.1 Third-Party Services We Use

#### Google Firebase
- **Purpose**: Identity authentication, cloud data storage, real-time synchronization
- **Data**: User UID, email, link metadata, Notion Token (encrypted)
- **Privacy Policy**: [Firebase Privacy Policy](https://firebase.google.com/support/privacy)

#### Notion API
- **Purpose**: Synchronize links to your Notion database
- **Data**: Link URLs, titles, descriptions, tags
- **Privacy Policy**: [Notion Privacy Policy](https://www.notion.so/Privacy-Policy-3468d120cf614d4c9014c09f6adc9091)

#### Google Gemini API (Optional Paid Feature)
- **Purpose**: AI-powered summaries and tag suggestions
- **Data**: Link URLs and metadata (excluding user identity information)
- **Privacy Policy**: [Google AI Privacy Policy](https://policies.google.com/privacy)

#### Apple Sign In (iOS Users)
- **Purpose**: Identity authentication
- **Data**: Email address or anonymous email (user's choice)
- **Privacy Policy**: [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

### 3.2 What We Will NOT Do
- We **will NOT** sell your personal data to third parties
- We **will NOT** use your data for advertising purposes
- We **will NOT** share your information with third parties without your consent (except as required by law)

---

## 4. Information Storage and Security

### 4.1 Storage Location
- **Cloud Storage**: All user data is stored in Google Firebase Cloud Firestore databases
- **Data Centers**: Located in Google Cloud's United States region servers
- **Local Storage**: Link metadata is encrypted and stored on devices using SQLite

### 4.2 Security Measures
- **Encrypted Transmission**: All data transmission uses HTTPS/TLS encryption
- **Token Encryption**: Notion Tokens are encrypted before storage
- **Access Control**: Firestore security rules ensure only you can access your own data
- **Authentication**: Multi-factor authentication support based on Firebase Authentication

### 4.3 Data Retention Period
- **Active Accounts**: Data will be retained until you delete your account or data
- **Inactive Accounts**: Account data that has not been logged into for more than 2 years will be automatically deleted (with 30 days advance email notification)

---

## 5. Your Rights

Under applicable data protection laws (including GDPR and CCPA), you have the following rights:

### 5.1 Right to Access
- You can view and export all your data within the app at any time

### 5.2 Right to Rectification
- You can edit and update your link information and account settings within the app

### 5.3 Right to Deletion
- You can delete individual links or your entire account at any time
- After account deletion, all associated data will be permanently deleted from our servers within 30 days

### 5.4 Right to Data Portability
- You can export all your link data in JSON or CSV format

### 5.5 Right to Object
- You can opt out of optional data collection features (such as crash reports, AI features)

### 5.6 How to Exercise These Rights
Please contact us via email: **myang2984@gmail.com**

---

## 6. Data Retention and Deletion

### 6.1 Account Deletion Process
If you choose to delete your Linkn App account:

1. **Immediate Deletion**: Firebase authentication account information and Firestore user data are immediately marked for deletion
2. **30-Day Grace Period**: Data will be completely purged within 30 days (to prevent accidental deletion)
3. **Permanent Deletion**: After 30 days, all data is unrecoverable

### 6.2 Scope of Deletion
- **Included**: Email address, Notion Token, all link metadata, tags, reading status
- **Not Included**: Data already synchronized to your Notion database (you need to manage this yourself)

### 6.3 Data Backup
- We recommend exporting any needed data before deleting your account
- Data cannot be recovered after deletion

---

## 7. Children's Privacy Protection

Linkn App is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and discover that your child has provided us with personal information without your consent, please contact us and we will immediately delete such information.

**Complies with COPPA (Children's Online Privacy Protection Act) requirements.**

---

## 8. International Data Transfers

Linkn App uses Firebase servers located in the United States. If you are located in the European Economic Area (EEA), United Kingdom, or other regions, your data may be transferred to locations outside your jurisdiction.

We ensure such transfers comply with applicable data protection laws and employ appropriate safeguards (such as Standard Contractual Clauses).

---

## 9. Cookies and Tracking Technologies

### 9.1 Technologies We Use
- **Local Storage**: Uses SharedPreferences and SQLite to store user preference settings and link data
- **Firebase Analytics**: Collects anonymous usage data to improve the app (can be disabled in settings)

### 9.2 Technologies We Do NOT Use
- **Advertising Tracking**: Does not use advertising IDs or cross-app tracking
- **Third-Party Cookies**: Does not use third-party advertising or analytics cookies

---

## 10. Changes to Privacy Policy

We may update this Privacy Policy from time to time. When changes occur:

1. **Notification Methods**:
   - In-app notification popup
   - Notification sent to registered email
   - Update of "Last Updated" date on this page

2. **Material Changes**:
   - For material changes, we will notify you 30 days in advance
   - You may choose to accept the new policy or delete your account

3. **Effective Date**:
   - Changes will take effect 30 days after publication
   - Continued use of the service indicates acceptance of the new policy

---

## 11. California Residents Special Notice (CCPA)

If you are a California resident, under the California Consumer Privacy Act (CCPA), you have the following additional rights:

- **Right to Know**: Learn about the categories and specific personal information we collect
- **Right to Delete**: Request deletion of your personal information
- **Right to Opt-Out**: Opt out of the sale of your personal information (we do not sell user data)
- **Right to Non-Discrimination**: Exercise privacy rights without discriminatory treatment

To exercise these rights, please contact: **myang2984@gmail.com**

---

## 12. EU Residents Special Notice (GDPR)

If you are an EU resident, under the General Data Protection Regulation (GDPR), our legal basis for processing your data is:

- **Contract Performance**: To provide you with Linkn App services
- **Legitimate Interests**: To improve services and prevent fraud
- **Consent**: Optional features (such as AI processing) require your explicit consent

You may withdraw consent at any time without affecting core contract-based services.

---

## 13. Data Breach Notification

In the event of a data breach that may affect the security of your personal information, we will:

1. Notify you via email within **72 hours** of discovering the breach
2. Explain the type and scope of data breached
3. Inform you of remedial measures we have taken
4. Provide recommendations for protective measures you can take

---

## 14. Contact Us

If you have any questions, comments, or complaints about this Privacy Policy, please contact us:

**Email**: myang2984@gmail.com
**Response Time**: We will respond to your inquiry within 7 business days

For data protection-related complaints, you may also contact your local data protection supervisory authority.

---

## 15. Governing Law

This Privacy Policy is governed by and construed in accordance with:
- Personal Information Protection Law of the People's Republic of China
- European Union General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Children's Online Privacy Protection Act (COPPA)

In case of conflicting laws, the law providing stricter user privacy protection shall prevail.

---

**The latest version of this Privacy Policy will always be published here.**

**Last Updated: November 12, 2025**
