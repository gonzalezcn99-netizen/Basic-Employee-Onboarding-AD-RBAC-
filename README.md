# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
This project was based on a fictional company called Northstar Medical Group, where the Active Directory environment lack of structure. Users were being added manually and inconsistently, with no structure at all. Some employees ended up with way more access than they should have, while others couldn’t do their jobs because they didn’t have the permissions they needed. When someone left the company, the MSP often forgot to disable their account — sometimes for months. No one documented changes to user accounts, and new hires regularly spent days dealing with access issues. Because of all this disorganization and manual work, NMG faced serious HIPAA compliance risks.
## Solution Overview
I created four Organizational Units: Finance, HR, IT, and Operations. Each user was added to their correct department and assigned to the appropriate security group, ensuring the principle of least privilege. It is now easier to track disabled/enabled accounts, move users, and maintain overall organization. I also ran a mock ticket to simulate a user being given the wrong access and walked through the steps to correct it. Northstar Medical Group now has a well‑structured and organized Active Directory/RBAC environment.

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
* Solved a mock ticket where a user was given the incorrect access.
* I fully documented my steps end-to-end.
