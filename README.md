# active-directory-labs

 Ticket 1

This repository documents hands-on IT support tasks performed in a Windows Active Directory home lab. Each ticket demonstrates real-world troubleshooting, problem-solving, and documentation skills.  

---

## 🧾 Ticket: User Password Change Loop

**Problem Encountered:**  
- User unable to log in to domain account  
- Error message: `User password must be changed before signing in`  
- Repeated attempts to change password failed  

**Root Cause:**  
- Password reset was configured with **“User must change password at next logon”**  
- Domain password policy prevented successful password change  

**Resolution:**  
1. Reset the user password in Active Directory  
2. Removed **“User must change password at next logon”**  
3. Verified account was enabled and unlocked  
4. Successfully logged in with the new password  

**Skills Demonstrated:**  
- Active Directory user management  
- Domain authentication troubleshooting  
- Password reset & account management  
- Windows Server & Client OS administration  
- Troubleshooting & documentation  

---

## 📸 Screenshots

- Login error before password reset:  
![Login Error](screenshots/login-password-change-required.png)

- Active Directory account status:  
![AD Account Status](screenshots/ad-account-status.png)

- Reset password action:  
![Password Reset](screenshots/ad-password-reset-loop-fix.png)

- Successful login after fix:  
![Login Success](screenshots/login-success.png)

---

## 📂 Folder Structure
