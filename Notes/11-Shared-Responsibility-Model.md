# ☁️ Chapter 11 - Shared Responsibility Model

## What is the Shared Responsibility Model?

The **Shared Responsibility Model** means that **both the Cloud Provider and the Customer share the responsibility for security.**

The cloud provider secures the **cloud infrastructure**, while the customer secures **their data, applications, and access**.

### Simple Definition

> **Security in the cloud is a shared responsibility between the Cloud Provider and the Customer.**

---

# Why do we need the Shared Responsibility Model?

Many people think:

> **"If my data is stored in the cloud, the cloud provider is responsible for everything."**

❌ This is incorrect.

The cloud provider protects the cloud infrastructure, but **you are responsible for protecting your own data, passwords, applications, and user access.**

---

# Real-Life Example 🏠

Imagine you rent an apartment.

## Apartment Owner Responsibilities

- Building
- Electricity
- Water Supply
- Lift
- Security Gate

## Your (Tenant) Responsibilities

- Locking your door
- Keeping your valuables safe
- Cleaning your room

Both have different responsibilities.

Cloud Computing works in the same way.

---

# Cloud Provider Responsibilities

The Cloud Provider is responsible for:

- ✅ Physical Servers
- ✅ Data Centers
- ✅ Networking Hardware
- ✅ Storage Hardware
- ✅ Power Supply
- ✅ Cooling System
- ✅ Physical Security

---

# Customer Responsibilities

The Customer is responsible for:

- ✅ Data
- ✅ Passwords
- ✅ User Accounts
- ✅ Applications
- ✅ Files
- ✅ Access Permissions

---

# Shared Responsibility Diagram

```text
              Shared Responsibility

      Cloud Provider        Customer
      -------------------------------
      Data Center        |   Data
      Physical Servers   |   Applications
      Network Hardware   |   User Accounts
      Storage Hardware   |   Passwords
      Cooling System     |   Permissions
      Physical Security  |   Files
```

---

# Why is it Important?

Both the Cloud Provider and the Customer have different responsibilities.

### Example

If you use a weak password and your account gets hacked,

❌ It is **not** the Cloud Provider's responsibility.

If a physical server fails,

✅ It is the **Cloud Provider's responsibility** to fix or replace it.

---

# Advantages

- ✅ Better Security
- ✅ Clear Responsibilities
- ✅ Reduces Confusion
- ✅ Protects Customer Data

---

# Quick Revision

| Cloud Provider | Customer |
|----------------|----------|
| Physical Servers | Data |
| Data Centers | Applications |
| Networking Hardware | User Accounts |
| Storage Hardware | Passwords |
| Power & Cooling | Files |
| Physical Security | Access Permissions |

---

# Easy Way to Remember

🏢 **Cloud Provider = Apartment Owner**

👤 **Customer = Tenant**

The apartment owner protects the **building**.

The tenant protects their **belongings**.

---
