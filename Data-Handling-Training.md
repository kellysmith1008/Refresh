# Welcome
Welcome to the Data Handling training. In this module, you’ll learn how to classify, store, and share data securely—whether you’re in engineering, sales, or management. Get ready to move beyond general awareness and master the specific technical and commercial requirements that help safeguard your organization and maintain compliance. This training is key for the awareness of everyone across the company and provides the context for us to understand and embrace this initiative.

## Agenda
- Data Classification
- Data handling fundamentals
- Secure storage
- Sharing data safely
- Device integrity
- Role-specific responsibilities

## Data Classification 
Understanding how to properly classify and handle data is essential for compliance and operational excellence. Whether you’re an engineer, manager, or part of the sales team, knowing the fundamentals of data security ensures you protect sensitive information and support your organization’s compliance goals. This lesson will give you the practical knowledge you need to confidently manage data in your daily work.

### Four tiers of data classification

| Data type | Definition | 
| :---------- | :----------------------------------------------------------------- |
| Public | Approved for release, such as website content or open-source code. Can be accessed by anyone with the link. |
| Internal | Used for non-sensitive internal procedures. Not for public release, but not highly sensitive. |
| Confidential | Includes high-stakes data like Federal Contract Information (FCI) and Controlled Unclassified Information (CUI). Disclosure could impact contract eligibility. |
| Restricted | The most sensitive data, such as payroll, credentials, or Social Security Numbers. Unauthorized disclosure could cause severe harm. |

### Data visualization

<img width="681" height="625" alt="a rock pyramid that has a larger rock on the bottom and gets smaller in rock size until the top rock, which is very small and likely to fall off if the rock moves" src="https://github.com/user-attachments/assets/a6295a9b-dff6-4f3c-8eca-2c0dfcf94e09" />

This pyramid shows how data is classified by sensitivity and risk. Public data forms the broad base, while restricted data sits at the narrow top, representing the highest risk if mishandled. As you move up the tiers, the potential consequences of improper handling increase, making strict controls essential for confidential and restricted data.

### Classification in practice

Let's look at each data type to see what types of data belong in each tier, who typically handles them, and what can happen if they’re mishandled.

| Data type | Definition | Consequences
| :---------- | :---------------------------------------- | :---------------------------------------------- |
| Public | Public data includes information like website content, published marketing materials, or open-source code. Anyone in the organization can access and share this data, for example, when a sales team member posts a brochure on the company website. | If mishandled, there are minimal risks.
| Internal | Internal data covers non-sensitive internal procedures, such as meeting notes or internal process documents. Typically, employees across departments use this data, but it should not be shared outside the organization. | If mishandled, there may be minor operational disruptions, but no severe compliance consequences.
| Confidential | Confidential data includes FCI and CUI, such as client technical drawings or sensitive contract details. Engineers and sales/contract teams often interact with this data. | If mishandled, it could jeopardize contract eligibility or lead to regulatory penalties. |
| Restricted | Restricted data includes highly sensitive items such as payroll records, login credentials, or Social Security Numbers. Typically, only managers or HR personnel should access this data. | If mishandled, it can result in severe harm, including legal action or significant financial loss. |

### Data minimization
Data minimization means collecting and storing only the information you truly need. By limiting the amount of data you handle and favoring secure, cloud-native sharing, you reduce the risk of breaches and make compliance easier for everyone.

> Only collect the information that is necessary. Do not create local copies; instead, use cloud-native sharing methods within approved boundaries.

## Checkpoint quiz
?[quizstart.webm](https://github.com/user-attachments/assets/d7c1e995-c489-4c3d-bbd7-6bf5e6d39466)

Let's take a moment to review what we've covered so far. Select the correct answer or answers for the next few questions.

### Which of the following is an example of violating the data minimization principle?
- [( )] Storing only essential client information in a secure cloud drive
- [(X)] Downloading confidential files to your personal laptop for convenience
- [( )] Sharing documents through approved company platforms
- [( )] Limiting access to sensitive data based on job roles

### What are the four tiers of data classification? (select all that apply)
- [[ ]] Governmental
- [[X]] Public
- [[X]] Internal
- [[ ]] FOSS
- [[ ]] Personal
- [[X]] Confidential
- [[X]] Restricted

## Mandatory Marking and Labeling
For confidential and restricted data, it is essential to use electronic labels, banners, or filename tags to clearly identify sensitive information. If you receive unmarked data that may be Controlled Unclassified Information (CUI), you have a duty to report it and ensure it is properly labeled before storing or sharing it.

### Recognizing proper labeling
Properly labeled files in Google Workspace are easy to spot—look for banners, filename tags, or workspace labels indicating _Confidential_ or _Restricted_. If a file lacks these labels but contains sensitive information, it needs to be reported and labeled before further handling.

### Handling unmarked CUI
Sometimes, you may come across files or documents that contain sensitive information but do not have the required CUI markings. It's important to know how to handle such situations to ensure compliance and protect sensitive data. Learn the steps to take when you encounter Controlled Unclassified Information (CUI) that is not properly marked.

1. Identify potential CUI.
   - Notice if a file, such as a technical drawing from a client, lacks proper labeling but appears sensitive.
2. Report to the appropriate authority.
   - Notify your manager or compliance officer about the unmarked data immediately.
3. Ensure correct marking.
   - Work with the responsible party to apply the correct electronic labels or tags before any further storage or sharing.
4. Store and share securely.
   - Once labeled, store and share the data only within approved boundaries, such as designated shared drives.

## Secure Storage
Protecting sensitive data isn’t just about knowing what information you have; it’s about how you store, share, and access it every day. Approved storage boundaries are the digital spaces where sensitive data may reside. These include company-approved cloud platforms, such as Google Workspace Shared Drives or authorized SaaS solutions. Storing data outside these boundaries—like on personal cloud accounts or local downloads—creates significant security risks, including unauthorized access, data loss, and compliance violations. Understanding and respecting these boundaries is the first step in protecting your organization’s information.

### Storing data
Let's take a look at where different types of data can be stored, who can access it, and what you should avoid doing when storing it.

- Public data:
    - Public data is approved for release and may be shared broadly, including on public websites. However, always confirm that data is truly public before sharing outside the organization. No special storage restrictions apply, but caution is still advised.
- Internal data:
    - Internal data can be stored within company-managed drives, but should not be shared externally. While less sensitive, it still must not be placed on personal or public platforms. Access is typically limited to employees within the organization.
- Confidential data:
    - Confidential data must be stored only in company-approved shared drives or authorized SaaS platforms. Access is limited to individuals with a legitimate business need. Never download confidential files to personal devices or store them on unapproved cloud services.
- Restricted data:
    - Restricted data, such as payroll or credentials, requires the highest level of protection. Store only in designated, secure folders on approved platforms. Access is strictly controlled and monitored. Storing restricted data on local devices or personal storage is strictly forbidden.

## Checkpoint quiz
?[quizstart.webm](https://github.com/user-attachments/assets/d7c1e995-c489-4c3d-bbd7-6bf5e6d39466)

Let's take a moment to review what we've covered so far. Select the correct answer or answers for the next few questions.

### Match the data examples to the correct classification tier:

|               | Public | Internal | Confidential | Restricted |
|:--------------| :---: | :---: | :---: | :---: |
| Employee login credentials | ( ) | ( ) | ( ) | (X) |
| Payroll spreadsheet | ( ) | ( ) | ( ) | (X) |
| Meeting notes about project timelines | ( ) | (X) | ( ) | ( ) |
| Technical drawing from the client | ( ) | ( ) | (X) | ( ) |
| Published product brochure | (X) | ( ) | ( ) | ( ) |

### Which of the following is an approved storage practice for confidential data?
- [( )] Saving to a personal Dropbox account
- [( )] Uploading to an unapproved SaaS platform
- [( )] Downloading to your local "Downloads" folder
- [(X)] Storing in a company-approved Google Workspace Shared Drive

## The "No Email" Rule
Sharing sensitive data requires strict adherence to secure protocols. The default approach is to use named accounts for sharing, never public links, and to avoid email for transmitting confidential or restricted information. When email is absolutely necessary, encryption protocols must be followed to ensure data remains protected.

### Safe sharing protocols
Sharing confidential or restricted data requires careful attention to security protocols. Following best practices helps ensure that sensitive information is only accessible to authorized individuals and remains protected throughout the sharing process.

Learn the essential steps to safely share confidential or restricted data and protect sensitive information from unauthorized access.

1. Confirm recipient identity.
   - Always share files using specific, named accounts. Double-check that only authorized individuals are included in the sharing permissions.
2. Avoid public links.
   - Never use the "Anyone with the link" option for sharing sensitive data. This setting is only appropriate for public information.
3. Use encryption for email exceptions.
   - If email is the only option, place the data in an AES-256 password-protected archive. The passphrase must be at least 20 characters and sent via a separate channel, such as a secure messaging app.
4. Verify secure delivery.
   - Ensure the recipient has received both the encrypted file and the passphrase through separate, secure channels before confirming completion.
  
Never send confidential or restricted data via standard email or attachments; use only approved secure channels.

## Device Integrity
Securing your devices is just as important as securing your data. Only company-managed hardware should be used for handling sensitive information, and all endpoints must have full-disk encryption enabled. For Controlled Unclassified Information (CUI), additional FIPS compliance is required to meet federal standards.

**Engineers**
- Engineers working on federal contracts must use only company-managed laptops. Personal devices are strictly prohibited. All endpoints must have full-disk encryption, and FIPS 140-2/3 validated cryptographic modules are required for handling CUI.

**Sales and managers**
- Sales, managers, project leads, directors, and executive leadership must use company-managed devices for all work involving sensitive data. Encryption and endpoint security controls must be active at all times. Never store or access sensitive information on personal laptops or mobile devices.

**All CivicActions Employees**
- No one should ever store sensitive data on unapproved devices. Always ensure that your device meets company security standards before accessing or handling Confidential or Restricted information.

## Data Handling by Roles
Each role in the organization has unique responsibilities for handling sensitive data. Let's take a look at some roles and examples:

**Engineers**: _Secure development and secrets management_:

Engineers must never use real production Confidential or CUI data in development or test environments. Instead, synthetic or masked datasets should be created and used, with masking scripts reviewed and approved. Secrets like API keys and passwords must never be stored in source code; always use the approved secrets vault.
- Practical Example: Using a company-approved tool to generate fake customer data for testing a new feature.
- Common Mistake: Copying production data for testing or leaving credentials in code repositories.

**Sales and contract teams**: _Handling proposals and slack restrictions_:

Sales and contract teams must treat all client RFPs and technical diagrams as Confidential by default. These documents should only be stored in authorized CUI enclaves and never shared via Slack or email without proper safeguards. Slack is for coordination only—not for sharing technical data.
- Practical Example: Uploading a proposal to a secure document management system instead of sending it via Slack.
- Common Mistake: Discussing sensitive details in open channels or sending unprotected files to clients or partners.

**Managers**: _Data minimization and flow-down requirements_:

Managers are responsible for ensuring that only necessary data is collected and that access is granted strictly on a need-to-know basis. Before sharing project data with subcontractors or partners, managers must ensure that subcontractors or partners understand and agree to all data handling protocols.
- Practical Example: Briefing a new subcontractor on data handling requirements before granting access to project files.
- Common Mistake: Failing to brief partners, leading to accidental exposure of sensitive information.

### Best practices
Protecting sensitive data in development and test environments is critical for compliance and risk reduction. Following these steps ensures no real Confidential or CUI data is exposed during testing.

1. Never use real production data.
   - Always avoid using actual production Confidential or CUI data in any development or test environment.
2. Create synthetic or masked datasets.
   - Develop and use synthetic or masked datasets that mimic real data without exposing sensitive information.
3. Submit masking scripts for review.
   - All masking scripts must be submitted for review and approval to ensure effectiveness and compliance.
4. Store test data in approved environments.
   - Only store test datasets in company-approved, secure environments—never on personal devices or unauthorized platforms.
5. Manage secrets in an approved vault.
   - All secrets, such as API keys and passwords, must be managed exclusively in the organization’s approved secrets vault.

## Checkpoint quiz
?[quizstart.webm](https://github.com/user-attachments/assets/d7c1e995-c489-4c3d-bbd7-6bf5e6d39466)

Let's take a moment to review what we've covered so far. Select the correct answer or answers for the next few questions.

### You need to access Confidential data remotely. Which device and security measures are required?
- [( )] Personal laptop with no encryption
- [( )] Tablet with a basic password
- [(X)] Company-managed laptop with full-disk encryption
- [( )] Any device with antivirus software

### Which of the following practices are compliant in a development or test environment? (select all that apply)
- [[X]] Using synthetic datasets for testing
- [[X]] Storing secrets in the approved vault
- [[ ]] Using real production CUI data for testing
- [[X]] Submitting masking scripts for review

## Commercial Data Handling and Flow-Down 
Sales, contract teams, and managers play a critical role in protecting sensitive commercial information. Proposals, RFPs, and technical diagrams must always be treated as Confidential and stored in authorized locations. Before sharing any project data with subcontractors or partners, it’s essential to provide clear instructions on data handling requirements to prevent accidental exposure or mishandling.

**Proposal security**:
- All client proposals, RFPs, and technical diagrams must be classified as Confidential by default. These documents should be stored only in the designated CUI enclave or authorized shared drives, never on personal devices or unapproved platforms. When sharing proposals, use secure, named account invitations and avoid sending files via email or Slack. This ensures only authorized recipients have access and maintains a clear audit trail.

**Communications restrictions**:
- Slack should only be used for coordination and not for sharing technical CUI or Confidential data. Never paste technical diagrams or sensitive details into Slack messages or channels. If technical data must be discussed, use the authorized CUI enclave or approved secure channels. This reduces the risk of accidental leaks or unauthorized access.

**Flow-down requirements**:
- Before sharing any project data with subcontractors or partners, managers must ensure they are briefed on all data handling protocols. This includes providing written instructions and confirming understanding. Never send technical or confidential data to a subcontractor before confirming they are trained and agree to follow all compliance requirements. This step is critical for maintaining contractual and regulatory obligations.

## Media Handling and Device Sanitization
Physical data security is just as important as digital safeguards. Removable media such as USB drives should be used only when absolutely necessary and always with encryption and company approval. When printing sensitive documents, minimize the number of copies, store them securely, and shred them when no longer needed. When decommissioning devices or media, cryptographic erasure ensures that data cannot be recovered, protecting your organization from accidental leaks.

**Removable media**:
- Only use removable media, such as USB drives, if absolutely necessary and with explicit company approval. All such media must be encrypted to protect sensitive data. A common mistake is using personal or unencrypted drives, which can lead to data breaches.

**Printing sensitive data**:
- Print sensitive documents only when required, and always store them in a locked container. When no longer needed, shred documents to prevent unauthorized access. Leaving printouts unattended or in open areas is a frequent error.

**Device Sanitization**:
- When decommissioning laptops or storage devices, use cryptographic erasure (destroying encryption keys) to render data unrecoverable. Simply deleting files or reformatting drives is not sufficient. Skipping this step can result in data exposure if devices are reused or discarded.

## Checkpoint quiz
?[quizstart.webm](https://github.com/user-attachments/assets/d7c1e995-c489-4c3d-bbd7-6bf5e6d39466)

Let's take a moment to review what we've covered so far. Select the correct answer or answers for the next few questions.

### Mark the actions as compliant or non-compliant:

|               | Compliant | Non-compliant |
|:--------------| :---: | :---: | 
| Store proposal in CUI enclave | (X) | ( ) |
| Use named account to share proposal | (X) | ( ) | 
| Brief a subcontractor before sharing the proposal | (X) | ( ) |
| Share RFP via slack | ( ) | (X) |
| Send technical diagram to the subcontractor before briefing them | ( ) | (X) |

### Which action is required when decommissioning a laptop that stored Confidential data??
- [(X)] Cryptographic erasure
- [( )] Simple file deletion
- [( )] Physical destruction only
- [( )] Doing nothing
