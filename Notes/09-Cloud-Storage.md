# ☁️ Chapter 9 - Cloud Storage Basics

## What is Storage?

**Storage** is a place where data is stored so that it can be accessed whenever needed.

Data can include:

- 📄 Documents
- 🖼️ Photos
- 🎥 Videos
- 💻 Applications
- 🗄️ Databases

### Simple Definition

> **Storage is used to save data permanently or temporarily so it can be accessed whenever required.**

---

# Why do we need Storage?

Imagine you create a Word document.

If there is no storage,

❌ The file will disappear after you turn off the computer.

Storage keeps your data safe.

---

# Real-Life Example 📚

Think of a **cupboard**.

You keep:

- Books
- Clothes
- Important Documents

Similarly, storage keeps:

- Files
- Photos
- Videos
- Applications

---

# Types of Storage

There are **three main types of storage** in Cloud Computing.

1. 🧱 Block Storage
2. 📁 File Storage
3. 🪣 Object Storage

---

# 1. Block Storage 🧱

## What is Block Storage?

Block Storage stores data in **small blocks**.

Each block has a unique ID.

The operating system combines these blocks to create a complete file.

### Example

Suppose you save a **100 MB movie**.

Instead of storing it as one file,

it is divided into multiple blocks.

```text
Movie.mp4

↓

Block 1
Block 2
Block 3
Block 4
```

When you open the movie,

the system joins all the blocks together.

---

## Where is it used?

- Operating Systems
- Databases
- Virtual Machines

Because it provides **high performance**.

---

## Advantages

- ✅ High Performance
- ✅ Low Latency
- ✅ Best for Databases

---

## Disadvantages

- ❌ More expensive
- ❌ Not suitable for storing millions of files

---

# 2. File Storage 📁

## What is File Storage?

File Storage stores data using **files and folders**, just like your computer.

```text
Documents

│

├── Resume.pdf

├── Notes.docx

└── Photos
```

---

## Real-Life Example

Think of your laptop.

You create folders such as:

- Movies
- Photos
- College

This is File Storage.

---

## Where is it used?

- Shared folders
- Office documents
- Team collaboration

---

## Advantages

- ✅ Easy to use
- ✅ Organized folder structure
- ✅ Easy file sharing

---

## Disadvantages

- ❌ Slower than Block Storage for databases

---

# 3. Object Storage 🪣

## What is Object Storage?

Object Storage stores data as **objects** instead of files or blocks.

Each object contains:

- Data
- Metadata (information about the file)
- Unique ID

---

## Example

Uploading photos to:

- Google Photos
- Google Drive
- Dropbox

These services use Object Storage concepts.

---

## Where is it used?

- Images
- Videos
- Backups
- Large files
- Cloud Applications

---

## Advantages

- ✅ Stores billions of files
- ✅ Highly scalable
- ✅ Cost-effective

---

## Disadvantages

- ❌ Not suitable for running an Operating System
- ❌ Not ideal for databases

---

# Storage Comparison

| Block Storage | File Storage | Object Storage |
|---------------|--------------|----------------|
| Stores data in blocks | Stores files and folders | Stores data as objects |
| Very fast | Easy to use | Best for storing huge amounts of data |
| Used for databases and virtual machines | Used for shared files | Used for backups, photos, and videos |

---

# Real-Life Examples

## 🧱 Block Storage

Imagine writing a book.

Each chapter is stored separately.

When someone reads the book,

all the chapters are combined.

---

## 📁 File Storage

Think of your college folder.

```text
College

├── Maths.pdf

├── Science.pdf

└── Notes.docx
```

---

## 🪣 Object Storage

Uploading a photo to Instagram.

You don't know where the photo is stored.

You simply upload it,

and the platform manages everything.

---

# Quick Revision

- 🧱 Block Storage → Best for Databases and Virtual Machines
- 📁 File Storage → Best for Files and Folders
- 🪣 Object Storage → Best for Photos, Videos, and Backups

---

