# StoreIt File Storage & Sharing App

A modern, efficient file storage and sharing platform built with **Next.js 15** and the **Appwrite Node SDK**—designed to enable smooth file upload, management, and sharing.

## Introduction

File Storage & Sharing App empowers users to upload, manage, and share their files effortlessly. Built using Next.js 15 and Appwrite’s Node SDK, it offers a blazing-fast interface and seamless file handling backed by a powerful backend.

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


## Tech Stack

| Category     | Technologies                                   |
|--------------|------------------------------------------------|
| Frontend     | React 19, Next.js 15, TailwindCSS, ShadCN UI, TypeScript |
| Backend      | Appwrite (Authentication, File Storage with Node SDK) |



## Installation

Install the project dependencies using npm:

npm install

Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:

- **NEXT_PUBLIC_APPWRITE_ENDPOINT** - "https://cloud.appwrite.io/v1"
- **NEXT_PUBLIC_APPWRITE_PROJECT** - ""
- **NEXT_PUBLIC_APPWRITE_DATABASE** - ""
- **NEXT_PUBLIC_APPWRITE_USERS_COLLECTION** - ""
- **NEXT_PUBLIC_APPWRITE_FILES_COLLECTION** - ""
- **NEXT_PUBLIC_APPWRITE_BUCKET** - ""
- **NEXT_APPWRITE_KEY** - ""

## Running the Project

- npm run dev
  
- Open http://localhost:3000 in  browser to view the project.
