# CISSP review
Welcome to the Certified Information Systems Security Professional (CISSP) Review Course offered by (ISC)2. The purpose of this course is to help you determine whether you are ready to pursue the CISSP certification. The CISSP Review Course will allow you to assess your level of preparedness to begin the intensive study required to pursue the CISSP certification exam.

This course will introduce you to the topics relevant to the certification and the exam. These topics are drawn from the exam outline, which specifies the knowledge required to hold the credential. The content covered in this course reflects topics that are in the exam outline and is intended to help you determine your own strengths and weaknesses as it relates to these topics.

In order to present the material to you in an efficient, straightforward manner, we’ve broken down the Exam Outline into seven (7) topics and arranged them in an efficient and intuitive order. We’ve grouped subject areas based on their similarity and ordered them in a manner that allows earlier material to build up to content later in the course.

We hope you find this content helpful in deciding whether you’re ready to sit for the CISSP examination, and we wish you the very best of luck in your studies!

## Security Fundamentals
### CIA Triad
Throughout our industry, the CIA triad is used to convey the intent and goals of information security efforts. The triad comprises these three ideas:

Confidentiality: Protecting data from unauthorized view
Integrity: Protecting data from unauthorized modification
Availability: Ensuring data can be accessed in authorized manner, as permitted
You will need to know the intent of each element of the CIA triad, as well as the mechanisms used to achieve those intentions.

Need to know: Information is only disclosed to those who have a business need and permission to access it.
Least privilege: Personnel are only given the minimal set of permissions necessary to perform their job function.
Separation of duties: Purposefully imposing inefficiency on a business process so that one person cannot complete an entire transaction on their own; forcing collusion.
Job rotation: Shifting personnel (usually within a given department) among various roles throughout the year, for security, morale, and continuity purposes.
Due care: The legal duty owed by an organization to its constituents (users/customers/employees/the public).
Due diligence: Documented efforts demonstrating the organization’s activities to provide due care.

### Privileged Account Management
Privileged users (those with more access/permissions than regular users) can cause more harm to the organization than regular users (and, historically, have); therefore, privileged accounts must be managed in a more restrictive and thorough manner than regular accounts.

### Risk Management Concepts
Risk: Potential harm to an organization
Threat: A factor that poses risk
Vulnerability: An avenue that causes or enhances risk

### Risk Assessment
You will also be required to know that risk can be measured/assessed either quantitatively (objectively, in numeric values) or qualitatively (subjectively, through use of expert insight). You will also need to be familiar with the common formula often used for determining quantitative risk:

ALE = SLE x ARO
(annual loss expectancy = single loss expectancy multiplied by annual rate of occurrence)

### Asset Valuation
You should understand how senior managers use this formula to determine the potential loss based on the value of specific assets (derived from the business impact analysis (BIA), explained earlier in this topic ) and weigh the loss against the cost of the proposed control(s) used to protect those assets. Generally, controls will be selected if the cost of acquiring and implementing them is considerably less than the value of the asset and/or the cost that the organization would suffer if the asset were lost or damaged.

### Risk Response
You should know that there are four general approaches to handling risk:

Acceptance: Senior management chooses to accept the risk of an activity as it is.
Avoidance: Senior management chooses to cease the activity to remove the risk.
Transference: Another party is paid to accept risk on the organization’s behalf.
Mitigation: Risk is reduced through the use of controls.
Mitigation can only reduce risk, not eliminate it; risk that remains after controls are put into operation (risk mitigation) is called residual risk.

You should understand that senior management within an organization determines the organization’s overall approach to risk; that is, the amount of risk the organization is willing to accept (or transfer, or mitigate) in order to perform business functions is often directly related to possible benefits, and senior managers are sometimes willing to accept more risk in order to realize greater benefits. It is also important to note that every organization has its own risk appetite: the amount of risk senior management has determined is acceptable.

### Apply Risk-Based Management Concepts to the Supply Chain
Risk exists throughout the production environment and even extends beyond; risk can come from the systems and assets the organization uses; from business partners, vendors, and customers who are connected to your environment; or from the way your organization does business. It is important to understand how these risks occur, how to frame them, and how to address them.

Risks Associated with Hardware, Software, and Services
You should be familiar with common risks to all aspects of the environment. These include, but are not limited to:

Hardware
- Failure at end of useful life
- Failure due to internal environmental effects
- Failure due to external natural disaster
- Attack vector for malware input (USB/disk)
- Theft or physical damage

Software
- Inherent flaws and vulnerabilities
- Subject to misuse/abuse by users/external parties
- Interoperability issues with other software/underlying hardware
- Attack vector for malware input

Services
- Subject to misuse/abuse by contracted third parties
- Failure to perform
- Provider lock-in
- Provider lock-out

### Third-Party Security Services, Third-Party Assessment, and Monitoring
An organization may determine that certain services (either operational or related to security) are outside the organization’s core competency, instead contracting with a third party to provide these services. You should be aware of the various services that might be related to IT and information security, such as:

- Network management
- Network monitoring (either/both performance/security)
- Identity and access management
- Cryptographic key management
- Antimalware
- Threat detection/monitoring (business intelligence)
Typically, both parties in this kind of arrangement (and the service providers and the organization contracting third-party providers) protect themselves through the codification and use of a service-level agreement (SLA).

The SLA describes—objectively, specifically, and numerically—the terms of service the provider will deliver on a regular basis. It is the part of the contract that distinctly allows both parties to determine whether the provider has met the needs of the customer organization. The customer organization will have to determine the service level requirements (the basic performance metrics used to determine if the SLA is met) and the minimum security requirements necessary to receive the service with sufficient security protections to meet the organization’s risk appetite and any compliance requirements.

Risk and Security Control Frameworks
Organizations often use frameworks as tools to describe, model, and document risk to the organization, performance requirements, and security controls. You should be familiar with the risk and security frameworks commonly associated with the industry, including the following:

National Institute of Standards and Technology --

NIST SP 800-37: Guide for applying Risk Management Framework (RMF)
NIST SP 800-53: Catalog of security controls for use in conjunction with the RMF
NIST FIPS 140-2: Cryptographic module approval list
NIST FIPS 199: Standards for security categorization
International Standards Organization

ISO 27000 series: International Organization for Standardization (ISO) guidance on information security, particularly:
ISO 27001: The information security management system (ISMS)
ISO 27002: Security controls list for use with the ISMS
COBIT: ISACA framework for security management and governance
CSA STAR: The Cloud Security Alliance Security Trust, Assurance, and Risk program for cloud service providers
FedRAMP: U.S. federal government framework for cloud service providers
PCI-DSS: The Payment Card Industry Data Security Standard

### Develop, Document, and Implement Security Policy, Standards, Procedures, and Guidelines
We discussed governance earlier in the topic—the methods and resources used by the organization to make decisions (and security governance, for decisions made about security). This section deals with the documented aspects of security governance: the security policies, standards, procedures, and guidelines.

You should be familiar with these terms and concepts, for both certification and practical use:
- Security policy: The organization’s strategic security direction and mandates, published and signed by senior management
- Security standards: Minimum target levels and security best practices; may be created within the organization and imposed on all business units or may be taken from external creators (such as standards bodies like ISO, PCI, or SANS)
- Security procedures: Specific instructions for performing security-related tasks
- Security guidelines: Recommendations (not mandates) for security best practices; usually from sources external to the organization

### Securely Provisioning Resources
In order to secure the organization’s assets, it is imperative to know what assets the organization has, as well as information about those assets (such as location, responsibility, status, and so on). This is the purpose of the asset inventory, or a tool/method for tracking all assets within the organization. This should be done for all hardware, software, and media assets.

One of the aspects the inventory should include is the identification and tracking of the asset owner. This is the party/person/office within the organization that is explicitly responsible for maintaining, operating, and storing the asset properly and securely, in compliance with appropriate guidance. The asset owner should have direct managerial and operational control of the asset, as well as accept the liability for its disposition. In many cases, the asset owner will be responsible not only for a given IT asset but for the data that resides on it.

### Understand and Participate in Change Management Processes
You will also need a process for constantly updating/maintaining the inventory, to monitor and reflect continual changes to the environment. There are two terms associated with this effort:

- Configuration management: The process, method, and resources used to determine baseline settings and version of assets in the inventory
- Change management: The process, method, and resources used to modify the configuration of assets in the inventory

In many organizations, there is one overall CM effort, which incorporates both concepts. For all IT-related assets, version control is crucial; the organization needs to know which updates/upgrades have been applied to which assets and which settings have been modified, in order to create uniformity throughout the environment and have a documented known-good template for expanding the environment and for use in audit/compliance efforts. Moreover, specifically for software, licensing of the asset is important, and tracking and maintaining licenses should be an element of the inventory.

You should also be aware of the security practitioner’s role in the CM process; as a security subject matter expert, you will be called on to review suggested/requested changes to the environment, identify potential risks, and make recommendations to senior management regarding whether the proposed modifications are reasonable and/or will need additional protections.

Apply Resource Protection Techniques
You should be familiar with standard practices for protecting assets; these include controls that mitigate against attempts to damage, take, or exploit assets. For instance, the organization should deploy security controls to prevent physical threats to assets, such as fences, locked doors, stickers/tags, temperature/humidity management, and so on.

When controls are used to prevent the asset from being misused or exploited as an avenue of attack, it is called hardening. Asset hardening often entails use of a configuration baseline and techniques such as:
- Removing default accounts (particularly default administrator accounts)
- Removing unnecessary services
- Installing antimalware/intrusion prevention/egress monitoring/additional access control tools
- Increasing logging

### Ensure Appropriate Asset Retention
You should be familiar with the need to preserve and maintain assets (in particular, data) for an appropriate length of time. This duration may vary from asset to asset within the organization and varies widely from organization to organization (as well as industry to industry and jurisdiction to jurisdiction). Asset retention durations can be assigned by statutory mandate, contractual obligation, internal policy, and/or industry standard.

The organization must determine every asset’s retention duration and ensure the asset is appropriately protected until that time is reached. Often, retention periods exceed useful production purpose of an asset, and assets will be stored in an archive until the retention period is reached. At the end of the retention period (and the end of the information lifecycle), the organization must dispose of the asset in a secure manner.
