#### Data Handling

Data goes through its own life cycle as users **create, utilize, share and modify it**. Many different models of the life of a data item can be found, but they all have some basic operational steps in common. As a way to have a better understand we can use the ==data security life cycle model==.

The data security life cycle model is useful because it can align easily with the different roles that people and organizations perform during the evolution of data from creation to destruction. Some data handling practices include classification and labeling, where you determine the sensitivity of the data (what is available to everyone and what needs to be restricted).

Another important concept is "==retention==", is how long we store the information and where based on the requirements of our organization and perhaps regulatory agencies as well. And for last, **defensible destruction**, ==meaning that we have the regulatory mandate backing up our decision to destroy the data== (it could be physical of hard drives or computer chips or could be more logical meaning digital records). It is important to understand that it may not be any more accesible that data or information on your server but you need to be sure that it will be completely erased, you need to **Degaussing** (Process of reducing or eliminating an unwanted magnetic field or data stored on tape and disk media).

Because someone with no permission could get some of the information on this process. We need to have some recovery devices to obtain some of the lost data in the situation. Because if you are subject to regulatory compliance, you have to follow through with specific protocols and processes to destroy that information as required so that it can no longer be accessed in any way. 

So in other words, ==The data life cycle is a notional tool that can be used to map data flows==. Any security or data handling procedures should be backed up by the appropriate policies. Every security policy should have a penalty or consequence attached in case of non-compliance.

![[Pasted image 20240907190143.png]]

> As an example, in the US, the Occupational Safety and Health Administration OSHA is the federal government agency that protects the well being of workers. Under the rules of the Health Care Insurance, Portability and Accountability Act HIPA, medical records need to be kept for 10 years but under OSHA, if we have a medical record of on the job injury, that record needs to be maintained for over 30 years even after the last day or work in that particular organization, that's regulatory requirement. 
#### Encryption Overview

Cryptography is used to protect information by keeping its meaning or content secret and making it unintelligible to someone who does not have a way to decrypt (unlock) that protected information. The main goal of an encryption system is to transform an original set of data called the plaintext, into an otherwise unintelligible encrypted form, called the ciphertext.
>An encryption system is a set of hardware, software, algorithms, controls parameters, and operational methods that provide a set of encryption services.

Plaintext could be: Image, audio or video files. Human-readable text, database files or records, anything that could be information. 
##### The 2 main important characteristics on encryption are:

- Confidentiality: By hiding or obscuring a message so that it cannot be understood by anyone except the intended recipient.
- Integrity: Hash functions and digital signature can provide integrity services that allow a recipient to verify that a message has not been altered by malice or error. 

>Integrity services provided by hash functions and digital signatures allow a recipient to verify that a message has not been altered by malice or error.
#### Types of encryptions

[[Let's talk about Symmetric Encryption]]
[[Let's talk about Asymmetric Encryption]]
> As result of this research, we can now know that Asymmetric encryption is better when is about scalability and distribution, but It can not be used as a day to day because it system is more slower than the symmetric counterpart. 
#### Hashing deep dive

Hashing puts data through a hash function or algorithm to create an alphanumeric set of figures, or a digest that means nothing to people who might view it.
>No matter how long the input is, the hash digest will be the same number of characters. Any minor change in the input, misspelling or an upper-case or lower-case error, will create a completely different hash digest.

Before we go live with a software product provided by a third party, for instance, we have to make sure no one has changed anything since it was tested by you and the programmer. ==They will usually send you the digest of their code and you compare that to the original. This is also known as **checksum**==.
#### Other important topics related to encryption and cryptography
[[Most well-known standards for symmetric cryptography]]
[[Most well-known standards for asymmetric cryptography]]
[[Most widely used standards for hashing]]
#### Security Awareness Training

The purpose of awareness training is to make sure everyone knows what is expected of them, based on responsibilities and accountabilities, and to find out whether there is any carelessness or complacency that may pose a risk to the organization.
##### Activities the corporations may use:

- Education: The main goal is to help learners improve their understanding of these ideas and their ability to relate them to their own experiences and apply that learning in useful ways.
- Training: Focuses on building proficiency in a specific set of skill or actions, including sharpening the perception and judgment needed to make decisions as to which skill to use, when to use it and how to apply it.
>Training can focus on low-level skills, an entire task, or complex workflows consisting of many tasks.
- These are activities that attract and engage the learner's attention by acquainting them with aspects of an issue, concern, problem, or need.
#### How passwords work

Most of the time, your password will be stored as a fixed hash value or digest, in order to the system can matches without the password itself ever being visible. A more secure password with alphanumeric and special characters will generate a different type of hash digest. But as the world continues to grow, this system of password management is already becoming obsolete. Often, for terms of security, you will be ask to generate a new password with a minimum number of characters and the software behind it will recognize the hash function and tell you if the password is sufficiently secure to be used or it will prompt you to create a better password. [[See more advices for better passwords]].
>Attackers can use password hashes to guess your password offline. If an attacker can copy the password file, which is usually hashed from a compromised workstation or server and they know the algorithm that is used to hash the password, they can use a computer to try random sequences of letters and numbers combinations to try to match the know password hash.
#### About password managers to save and handle all our passwords

The greatest disadvantage of these solutions is the risk of compromise of the password manager. This system may be protected by a weak password or passphrase chosen by the user and easily compromised. [[Some examples of poor passwords protection that should be avoided are]].
>Organizations should encourage the use of different passwords for different systems and should provide a recommended password management solution for its users.
#### What is the role of security engineers in data security?

Security engineers get familiar with security codes and can figure out exactly who was trying to log in and whether they were using a secure or questionable port.
#### More about "Phishing"

The use of phishing attacks to target individuals, entire departments, and even companies is a significant threat that the security professional needs to be aware of and be prepared to defend against. Phishing attacks that attempt to trick highly placed officials or private individuals with sizable assets into authorizing large fund wire transfers to previously unknown entities are known as ==**Whaling attacks**==.
#### Which type of organization is likely to have a stricter acceptable use policy according to the passage.

Organizations dealing with confidential data may have stricter acceptable use policies due to the potentially devastating consequences of data compromise.
#### Let's talk about Change Management Components

As we know, we have 3 basic concepts when doing a change, it looks very similar when doing a merge in code environments, and remember always to set up different environment to test the changes before send it to prod:

1. Request for change
	>All of the major change management practices address a common set of core activities that start with a request for change (RFC) and move through various development and test stages until the change is released to the end users; each step produces accounting or log entries to document its results.
1. Approval
	>Typically include: 
	>Evaluating the RFCs for completeness, assignment to the proper based on risk and organizational practices, stakeholder reviews, resource identification and allocation, resource identification and allocation, appropriate approvals or rejections and documentations  of approval or rejection. 
1. Rollback (if something go wrong)
	>Some activities it may involve: 
	>1. Scheduling the change
	>2. Testing the change
	>3. Verifying the rollback procedure
	>4. Implement the change
	>5. Evaluating the change for proper and effective operation
	>6. Documentation of the change in prod.











