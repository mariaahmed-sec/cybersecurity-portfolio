# Protecting Organizational Assets — Learning Summary

## 🔑 Key Concepts Reviewed

### **Principle of Least Privilege (PoLP)**
Users should receive only the minimum access needed for their job.  
Violations occur when:
- Excessive permissions are granted  
- Access is not removed after role changes  
- Admin-level rights are given unnecessarily  

---

### **Privilege Creep**
When users accumulate access rights over time without removing outdated permissions.

---

### **Operational vs Managerial Controls**
- **Operational controls:** Awareness training, day-to-day procedures  
- **Managerial controls:** Policies, governance, oversight  

---

### **Data Custodian**
Responsible for:
- Storing data  
- Securing data  
- Transporting or handling data safely  

---

### **Encryption Knowledge**
- **Symmetric encryption:** Uses a *single shared key*  
- **Asymmetric encryption:** Uses *public/private key pairs*  
- Asymmetric is *slower* and used for:
  - Identity verification  
  - Establishing secure key exchanges  

---

### **PII vs PHI**
- **PII:** Information that identifies an individual  
- **PHI:** Health-related data regulated by HIPAA  

---

## ⚠️ Access Management Mistakes Identified
- Failure to revoke access (poor deprovisioning)  
- Broad access instead of read-only  
- Missing MFA or identity verification  

---

## ❌ Incorrect Answers and What I Learned
### **Digital Certificates**
They verify identity — not passwords.

### **Deprovisioning**
Should be **automatic**, not manual.

### **Asymmetric Encryption**
Used mostly for:
- Key exchange  
- Identity verification  
Not for encrypting large amounts of data due to slower speed.

---

## 📘 Summary
This module reinforced foundational security concepts including least privilege, secure access management, encryption types, and regulatory distinctions like PII vs PHI.  
It also highlighted areas I need to strengthen, including deprovisioning and certificate-based identity verification.
