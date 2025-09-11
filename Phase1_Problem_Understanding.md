# 🐶 Phase 1: Problem Understanding & Industry Analysis  

## 📌 1. Requirement Gathering  
Animal shelters and NGOs face challenges in managing pet adoption processes manually (spreadsheets, paper forms, phone calls).  

**Key requirements identified:**  
- Track pets available for adoption with details (age, breed, health, status).  
- Manage adopter information and adoption requests.  
- Automate communication (confirmation, approval, follow-up emails).  
- Monitor adoption trends with reports and dashboards.  

---

## 📌 2. Stakeholder Analysis  
| Stakeholder        | Role/Interest | Needs |
|--------------------|---------------|-------|
| **Shelter Admin**  | Manages pets & adoption process | Simple system to register pets, assign status, generate reports |
| **Potential Adopter** | Adopts a pet | Easy adoption request submission, timely updates |
| **Shelter Volunteer** | Supports adoption events | Access to pet/adopter info, helps coordinate follow-ups |
| **Management/NGO Board** | Oversees operations | Reports on adoption success rate, animal welfare metrics |

---

## 📌 3. Business Process Mapping  

**Current Process (Manual):**  
1. Shelter registers pets in spreadsheets.  
2. Adopters call/email to inquire.  
3. Volunteers manually track requests.  
4. Approvals communicated via phone/email.  
5. Reports prepared manually.  

**Proposed Salesforce Process:**  
1. Shelter staff create **Pet records** in Salesforce.  
2. Adopters submit **Adoption Requests**.  
3. Automated workflows update pet status & notify adopters.  
4. Reports & dashboards provide **real-time adoption insights**.  

---

## 📌 4. Industry-specific Use Case Analysis  
- **Animal Welfare / NGOs:** Need centralized adoption management.  
- **Pet Shelters:** Require streamlined processes to reduce waiting times for animals.  
- **Nonprofit Sector:** Leverage Salesforce Nonprofit Cloud features to track donors, volunteers, and adopters.  
- **Community Impact:** Improves pet adoption rates, reduces abandoned pets, enhances animal welfare.  

---

## 📌 5. AppExchange Exploration  
Explored existing Salesforce AppExchange solutions such as **Nonprofit Success Pack (NPSP)** and **Shelter Management apps**.  

**Findings:**  
- Many are **complex and enterprise-level**, not suitable for small shelters.  
- Most focus on **donor management**, not the adoption process.  

**Conclusion:**  
A lightweight, custom **Pet Adoption Tracker** built on Salesforce is more suitable for small-to-medium shelters or as a capstone project.  
