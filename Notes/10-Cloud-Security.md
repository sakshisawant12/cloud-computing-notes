# ☁️ Chapter 10 - Cloud Security Basics

## What is Cloud Security?

**Cloud Security** means protecting cloud data, applications, and resources from unauthorized access, attacks, or data loss.

### Simple Definition

> Cloud Security is the process of keeping cloud data and resources safe.

---

# Why do we need Cloud Security?

Imagine you save all your important documents in the cloud.

If there is no security:

- Anyone can access your files.
- Your data can be stolen.
- Your application can be hacked.

That's why Cloud Security is important.

---

# Real-Life Example 🏠

Think of your house.

To protect it, you use:

- 🔒 Locks
- 📹 CCTV Cameras
- 👮 Security Guards

Similarly, cloud environments use different security methods to protect data and applications.

---

# 1. Authentication 🔑

## What is Authentication?

**Authentication** is the process of verifying your identity.

It answers the question:

> **"Who are you?"**

### Example

You log in to Gmail using:

- Username
- Password

If the password is correct, your identity is verified.

This is Authentication.

---

# 2. Authorization ✅

## What is Authorization?

**Authorization** determines what actions or resources you are allowed to access after you log in.

It answers the question:

> **"What are you allowed to do?"**

### Example

In a company:

👨 Employee

- Can view files

👨‍💼 Manager

- Can view, edit, and delete files

Both users are authenticated, but they have different permissions.

---

# Authentication vs Authorization

| Authentication | Authorization |
|----------------|---------------|
| Verifies identity | Decides permissions |
| Happens first | Happens after authentication |
| Example: Login | Example: Access Control |

### Easy Trick

- 🔑 Authentication = **Who are you?**
- ✅ Authorization = **What can you do?**

---

# 3. Multi-Factor Authentication (MFA)

## What is MFA?

**Multi-Factor Authentication (MFA)** uses more than one method to verify a user's identity.

### Example

To log in:

- Password ✅
- OTP sent to your phone ✅

Both are required.

---

## Why is MFA Important?

Even if someone knows your password,

they cannot log in without the second verification method.

---

# 4. Encryption 🔐

## What is Encryption?

**Encryption** converts readable data into an unreadable format.

Only authorized users with the correct key can convert it back.

### Example

Original Text

```text
Hello
```

Encrypted Text

```text
X7@9P#L2
```

Without the correct key, the encrypted data cannot be understood.

---

## Real-Life Example

Imagine writing a secret message using a special code.

Only your friend knows how to decode it.

---

# 5. CIA Triad

The **CIA Triad** is the foundation of Information Security.

It consists of three principles.

---

## C – Confidentiality 🔒

Only authorized people should access the data.

### Example

Only you should be able to view your bank account details.

---

## I – Integrity ✅

Data should not be modified without permission.

### Example

Your exam marks should not be changed by another student.

---

## A – Availability 🌍

Data and applications should be available whenever users need them.

### Example

You should be able to access Gmail whenever required.

---

# Easy Trick

| Letter | Meaning | Easy Remember |
|---------|---------|---------------|
| C | Confidentiality | Keep data secret |
| I | Integrity | Keep data accurate |
| A | Availability | Keep services available |

---

# 6. Principle of Least Privilege (PoLP)

## What is PoLP?

The **Principle of Least Privilege (PoLP)** means users should receive **only the permissions they need** to perform their job.

Nothing more.

### Example

An intern only needs permission to:

- View reports

The intern should **not** have permission to:

- Delete the company database

---

# Advantages of Cloud Security

- ✅ Protects data
- ✅ Prevents unauthorized access
- ✅ Reduces cyber attacks
- ✅ Improves customer trust

---

# Quick Revision

| Concept | Easy Example |
|----------|--------------|
| Authentication | Login using Username & Password |
| Authorization | Employee vs Manager permissions |
| MFA | Password + OTP |
| Encryption | Secret coded message |
| Confidentiality | Only you can see your bank details |
| Integrity | Marks cannot be changed without permission |
| Availability | Gmail available whenever needed |
| Least Privilege | Give users only the permissions they need |

---

