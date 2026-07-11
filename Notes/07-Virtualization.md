# ☁️ Chapter 7 - Virtualization

## What is Virtualization?

**Virtualization** is a technology that allows **one physical server** to run **multiple Virtual Machines (VMs).**

Instead of buying many physical servers, we can create many virtual servers on one physical server.

---

# Why do we need Virtualization?

Imagine a company has **10 applications**.

### ❌ Without Virtualization

The company needs:

- 10 Physical Servers
- More electricity
- More space
- Higher cost

```text
App 1 → Server 1

App 2 → Server 2

App 3 → Server 3
```

This is expensive.

---

### ✅ With Virtualization

One powerful server can run multiple Virtual Machines.

```text
           Physical Server
                  │
      ┌───────────┼───────────┐
      │           │           │
     VM 1        VM 2        VM 3
    Linux      Windows      Ubuntu
```

Now one server performs the work of many servers.

This saves money and hardware.

---

# What is a Physical Server?

A **Physical Server** is an actual computer with physical hardware such as:

- CPU
- RAM
- Storage (Hard Disk/SSD)
- Network Card

Think of it as a very powerful computer designed to run applications and services.

---

# What is a Virtual Machine (VM)?

A **Virtual Machine (VM)** is a software-based computer that behaves like a real computer.

Each VM has its own:

- Operating System
- CPU
- RAM
- Storage
- Applications

Even though many VMs run on one physical server, each VM works independently.

---

# Real-Life Example 🏢

Imagine a building.

- 🏢 Building = Physical Server
- 🏠 Apartments = Virtual Machines

Many families can live in one building.

Similarly, many VMs can run on one physical server.

---

# What is a Hypervisor?

A **Hypervisor** is software that creates and manages Virtual Machines.

Without a Hypervisor, virtualization is not possible.

It divides the physical server's resources (CPU, RAM, and Storage) among different Virtual Machines.

```text
Applications
      │
Operating Systems
      │
Virtual Machines
      │
Hypervisor
      │
Physical Server
```

---

# Types of Hypervisor

## 1. Type 1 Hypervisor (Bare Metal)

Runs **directly on physical hardware.**

```text
Applications
      │
Virtual Machines
      │
Hypervisor
      │
Hardware
```

### Examples

- VMware ESXi
- Microsoft Hyper-V
- Xen

### Advantages

- ✅ Better performance
- ✅ More secure
- ✅ Used in data centers

---

## 2. Type 2 Hypervisor (Hosted)

Runs **on top of an operating system.**

```text
Applications
      │
Virtual Machines
      │
Hypervisor
      │
Windows / Linux
      │
Hardware
```

### Examples

- Oracle VirtualBox
- VMware Workstation

### Advantages

- ✅ Easy to install
- ✅ Good for learning and testing

---

# Type 1 vs Type 2 Hypervisor

| Type 1 | Type 2 |
|---------|---------|
| Runs directly on hardware | Runs on an operating system |
| Better performance | Slightly slower |
| Used in companies and data centers | Used on personal computers |
| Example: VMware ESXi | Example: Oracle VirtualBox |

---

# Advantages of Virtualization

- ✅ Better hardware utilization
- ✅ Saves money
- ✅ Less physical hardware required
- ✅ Easy to create new Virtual Machines
- ✅ Faster deployment

---

# Disadvantages of Virtualization

- ❌ If the physical server fails, all VMs on it may stop working.
- ❌ Requires powerful hardware.
- ❌ Managing many Virtual Machines can become complex.

---

# Virtualization vs Cloud Computing

Many people think Virtualization and Cloud Computing are the same, but they are different.

| Virtualization | Cloud Computing |
|----------------|-----------------|
| A technology | A service model |
| Creates Virtual Machines | Delivers IT services over the Internet |
| Can be used inside one company | Used by cloud providers and businesses |

---

# Easy Way to Remember

> **Virtualization is a technology that creates Virtual Machines.**

> **Cloud Computing uses virtualization to deliver IT services over the Internet.**

---

# Quick Revision

- Virtualization allows one physical server to run multiple Virtual Machines.
- A Hypervisor creates and manages Virtual Machines.
- Type 1 Hypervisor runs directly on hardware.
- Type 2 Hypervisor runs on an operating system.
- Virtualization improves hardware utilization and reduces costs.

---

