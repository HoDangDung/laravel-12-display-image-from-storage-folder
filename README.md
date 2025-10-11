# Laravel 12 — Display Image from Storage Folder

A simple guide and example for **uploading and displaying images stored in Laravel’s storage folder**.  
This repo contains code snippets and examples from the Itstuffsolutions article: *“Laravel 12 Display Image From Storage Folder”*.  

[📄 View the blog article](https://itstuffsolutiotions.io/laravel-12-display-image-from-storage-folder/)  

---

## 🧩 Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Setup & Usage](#setup--usage)  
- [Methods Explained](#methods-explained)  
  - [Public Access via Symbolic Link](#public-access-via-symbolic-link)  
  - [Secure Streaming via Controller](#secure-streaming-via-controller)  
- [Common Problems & Tips](#common-problems--tips)  
- [License](#license)  

---

## 🌟 Overview

Laravel, by default, does not expose files stored in `storage/app` to the web.  
This example demonstrates two primary ways to serve images stored in Laravel’s **storage**:

1. **Public symbolic link** approach — easiest for public images  
2. **Controller-based streaming** — best for restricting access or controlling headers  

---

## ✅ Features / What You’ll Learn

- How to store uploaded files to the `public` disk  
- How to create the `storage:link` for public access  
- Using `Storage::url()` to generate URLs  
- Displaying images in Blade views  
- Building a secure controller method to stream images  
- Setting MIME types and handling “not found” cases  
- Tips for permissions and path issues  

---

## 🛠 Getting Started

### Prerequisites

You’ll need:

- PHP (compatible version with Laravel 12)  
- Composer  
- A Laravel 12 project  
- Web server (Apache, Nginx, etc.)  
- (Optional) local environment: Laravel Sail, Valet, or Homestead  


