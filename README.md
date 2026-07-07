# ⚙️ Group Policy Administration Lab

## 📋 Overview

This project documents the configuration and management of Group Policy Objects (GPOs) within an Active Directory environment. The lab focuses on implementing security policies and administrative settings commonly used by IT Support, System Administrators, and enterprise environments to standardize user and computer configurations.

Through this lab, I gained hands-on experience applying Group Policy to strengthen security, enforce organizational policies, and improve centralized management of Windows systems.

---

## 🛠️ Technologies Used

- Windows Server 2022
- Group Policy Management Console (GPMC)
- Active Directory Domain Services (AD DS)
- Windows 11
- Oracle VirtualBox

---

## 🎯 Objectives

- Configure password complexity requirements
- Configure password history policies
- Set minimum and maximum password age
- Configure minimum password length
- Implement account lockout policies
- Apply Group Policy Objects (GPOs)
- Test policy application on domain users

---

## 🔧 Tasks Completed

### 🔐 Password Policy Configuration

Configured password policies to enforce stronger password requirements for domain users.

---

### 🚫 Account Lockout Policies

Configured account lockout thresholds, duration, and reset timers to help protect against brute-force attacks.

---

### ⚙️ Group Policy Management

Created and modified Group Policy Objects (GPOs) to centrally manage user and computer settings within the domain.

---

### 🖥️ Policy Validation

Verified that Group Policy settings were successfully applied to domain users and workstations.

---

## 📸 Screenshots

### 🔐 Password Policy Configuration

This screenshot shows the Default Domain Policy being configured to enforce password complexity requirements, minimum password length, password history, and password expiration settings for all domain users.

![Password Policy Configuration](images/password-policy.png)

---<img width="1536" height="1024" alt="faa43509-e9e9-4e9c-bb7f-7cef821bc4f3" src="https://github.com/user-attachments/assets/2d288852-7261-4b50-a40f-249066ec46d7" />


### 🚫 Account Lockout Policies

This screenshot shows the Account Lockout Policy configuration, including the account lockout threshold, lockout duration, and reset account lockout counter settings used to protect against brute-force attacks.

![Account Lockout Policy](images/account-lockout.png)

---<img width="1536" height="1024" alt="37922562-9b4f-469b-93e6-0957b77417c1" src="https://github.com/user-attachments/assets/c7112d1d-a04c-409e-b318-09dc6979f42d" />


### ⚙️ Group Policy Management

This screenshot shows the Group Policy Management Console (GPMC) where Group Policy Objects (GPOs) are created, edited, and linked to the domain to centrally manage user and computer configurations.

![Group Policy Management](images/group-policy-management.png)

---<img width="1536" height="1024" alt="a1292565-f1e7-411f-b650-02d91347ce65" src="https://github.com/user-attachments/assets/65b66096-8314-4641-81d0-829d6107d2dd" />


### 🖥️ Policy Validation

This screenshot demonstrates verifying that Group Policy settings were successfully applied using the `gpresult /r` command, confirming that the expected policies are active on the workstation.

![Policy Validation](images/policy-validation.png)

---<img width="1403" height="1121" alt="bef570cf-2e0b-428d-9b14-c4c1d77e36df" src="https://github.com/user-attachments/assets/268b82b6-5029-44eb-b4b0-6021103d7e9b" />




---

## 💡 Skills Demonstrated

- Group Policy Administration
- Windows Server Administration
- Password Policy Management
- Account Lockout Configuration
- Active Directory Administration
- Enterprise Security Management
- Windows Administration

---

## 📚 Lessons Learned

This lab strengthened my understanding of how organizations use Group Policy to centrally manage security settings and user configurations. I gained practical experience implementing password policies, account lockout settings, and administrative controls that help secure enterprise Windows environments.
