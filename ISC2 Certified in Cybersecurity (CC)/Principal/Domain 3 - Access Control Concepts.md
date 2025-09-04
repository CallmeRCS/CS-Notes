#### This is where we describe who gets access to what, why access is necessary, and how that access is managed.

The key topics are:
- Security Control Protocols
- Access Control Strategies
- User Privilege Administration
#### But at first we need to understand what is a control in cybersecurity?

A control is a safeguard or countermeasure designed to preserve Confidentiality, Integrity and Availability of data... yes, we are talking about the CIA Triad. So understanding this concept we should say the following:

"Access control involves limiting what objects can be available to what subjects according to what rules"
> An example of this, is a Firewall, which is included in a system or network to prevent something from the outside from coming in and disturbing or compromising the environment.
#### Now let's talk about control overview

At the end, everything depends on privacy and confidentiality. It is all about, who can enter and access information and who can't. [[Access is based on three elements]].
#### What is "defense in depth"?

It refers to all-access permissions includes access to building, server rooms, networks, applications and utilities. These are all implementations of access control and are part of a layered defense strategy. As the same, defense in depth describe an information security strategy that integrates people, technology, and operations capabilities to establish variables barriers across multiple layers and missions of the organization. When companies has information at multiple sensitivity levels, it might require the network traffic to be validated by rules on more than one firewall, with the most sensitive information being stored behind multiple firewalls.

![[Pasted image 20240809125710.png]]
### What it means "Privileged Access Management"

Will this defense system is based on "principle of least privilege" meaning each user is granted access to only the items they need and nothing further. Systems often monitor access to private information, and if logs indicate that someone has attempted to access a database without the proper permissions, that will automatically trigger and alarm.
>For example, only individuals working in billing will be allowed to view consumer financial data, and even fewer individuals will have the authority to change or delete that data.
#### What are Logical Access Controls?

Are electronic methods that limit someone from getting access to systems, and sometimes even to tangible assets or areas. We can list some of them:
1. Passwords
2. Biometrics (implemented on a system, such as smartphone or laptop)
3. Badge/token readers connected to a system.

You can check more on in the [[Domain 1 - Security Principles]]
#### Controls and risks

A control serves to reduce the risk according to where it falls within the risk tolerance of the individual or organization.
>As an analogy, a physical control would be the seat belt, an administrative control would be a law requiring the use of the seatbelt. These controls together serve to reduce the risk of driving to a degree that is acceptable to the driver and to society.

To keep the information the most secure, it might be recommended to install biometric scanners on all doors for example. But how we get a analysis of this situation? Control assessments help us to determine wherever it is need it to add to each door a scanner or it is just necessary to add one or two depending on the situation.
>If biometric locks on multiple doors are not necessary and access does not need to be audited, a simple deadbolt lock on all doors may provide the correct level of control.
#### In what type of environment does role-based access control work well?

Role-based access control works well in an environment with high staff turnover and multiple personnel with similar access requirements. [[Let's talk more about Role-Based Access Control (RBAC) in the Workplace]].
#### Monitoring

The use of physical access controls, monitoring personnel and equipment entering and leaving, and auditing and logging all physical events are primary elements in maintaining overall organizations security. [[Let's see some examples of monitoring]].
#### Mandatory Access Control (MAC) in the workplace

By definition MAC is determined by the owner of the assets, on an across-the-board basis, with little individual decision-making about who gets access.

For example, at certain government agencies, personnel must have a certain type of security clearance to get access to certain areas. Some of this access, normally are set in by government policy and not by an individual giving permission based on their own judgment. The organization assigns a subset of total privileges for a subset of objects, such that the subject is constrained from doing any of the following behaviors:

- Passing the information to unauthorized subjects or objects.
- Granting its privileges to other subjects.
- Changing one or more security attributes on subjects, objects, the information system or system components
- Choosing the security attributes to associated with newly created or modified objects
- Changing the rules governing access control.
>Although MAC sounds very similar to DAC, the primary difference is who can control access, With ==Mandatory Access Control==, it is mandatory for security administrators to assign access right or permissions; with ==Discretionary Access Control==, it is up to the object owner's discretion. You can check more about [[Discretionary Access Control DAC]].

> [[Summary of access control models]]

> **Remember as this: MAC is more about "The system decides the access not you" instead, DAC is more kind of "You own it, so you decide who use it"**
#### What is the key feature of just-in-time privileged access management?

>**Solution: Role-based subsets of privileges**
#### What is the separation of duties?

==Is based on the security practice that no one person should control an entire high-risk transaction from start to finish==. It is possible, of course, that two individuals can willfully work together to bypass the separation of duties to jointly commit fraud. This is called collusion. ==Dual control== in other case, it said that 2 people got a part of a puzzle (lets say a code to open a vault), each need the other to open then vault, no one person knows both combinations. ==Two-Person rule== is a security strategy that requires a minimum of 2 people to be in an area together, making it impossible for a person to be in the area alone. Many access control systems prevent an individual cardholder from entering a selected high-security area unless accompanied by a least one other person.







