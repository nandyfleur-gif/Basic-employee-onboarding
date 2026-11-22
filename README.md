# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
A new employee at Northstar Medical Group could not log in. The IT service provider (MSP) did not organize user accounts clearly by department. Staff set up accounts by hand, so it was easy to put an account in the wrong organizational unit (OU). This raised HIPAA concerns about who could access patient information. We checked the account settings and OU to find out why the employee could not log in.
## Solution Overview
We created a new Active Directory domain for Northstar Medical Group. We set up separate organizational units (OUs) for Finance, HR, IT, and Operations so employee accounts could be placed in the right department. We used security groups to control what employees could access based on their jobs. With flat role-based access control (RBAC), we added users directly to the groups they needed. To prevent future login problems, we limited who could create accounts and checked each new user’s OU, group membership, and ability to sign in.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* [Add your second key accomplishment here]
* [Add your third key accomplishment here]
