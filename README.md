# File Storage & Sharing App

A modern, efficient file storage and sharing platform built with **Next.js 15** and the **Appwrite Node SDK**—designed to enable smooth file upload, management, and sharing.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Introduction

File Storage & Sharing App empowers users to upload, manage, and share their files effortlessly. Built using Next.js 15 and Appwrite’s Node SDK, it offers a blazing-fast interface and seamless file handling backed by a powerful backend.

---

## Features

- **User Authentication with Appwrite** — Robust signup, login, and logout using Appwrite’s authentication system.
- **Versatile File Uploads** — Supports documents, images, videos, and audio files.
- **Intuitive File Management** — Browse, preview (in a new tab), rename, or delete files stored in Appwrite.
- **One-Click Downloads** — Download files instantly for offline access.
- **Secure File Sharing** — Easily share files with others via Appwrite's mechanisms.
- **Insightful Dashboard** — View total and used storage, recent uploads, and categorized summaries of file types.
- **Global Search** — Quickly locate files and shared content across the platform.
- **Flexible Sorting** — Organize files by date, name, or size.
- **Modern & Responsive Design** — A clean, minimalist UI that works across devices.
- **Cutting-Edge Tech** — Built with React 19, Next.js 15, Appwrite, TailwindCSS, ShadCN, and TypeScript.

---

## Tech Stack

| Category     | Technologies                                   |
|--------------|------------------------------------------------|
| Frontend     | React 19, Next.js 15, TailwindCSS, ShadCN UI, TypeScript |
| Backend      | Appwrite (Authentication, File Storage with Node SDK) |

---

## Getting Started

### Prerequisites

- Node.js (v16 or above)  
- Appwrite instance (either local or hosted)

### Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install

# Duplicate environment variables
cp .env.example .env.local

# Update the following in .env.local:
# NEXT_PUBLIC_APPWRITE_ENDPOINT
# NEXT_PUBLIC_APPWRITE_PROJECT_ID
# NEXT_PUBLIC_APPWRITE_KEY
# (Other Appwrite-related variables)

npm run dev
