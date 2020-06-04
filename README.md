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
