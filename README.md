# About me
My name is Rihards, but online I'm known by `mrredo`.

<p align="left"> <img src="https://komarev.com/ghpvc/?username=mrredo&label=Profile%20views&color=0e75b6&style=flat" alt="mrredo" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=mrredo" alt="mrredo" /></a> </p>

## A passionate full-stack developer from Latvia
- 💻 Building scalable backend systems with Go and Laravel
- 📱 Developing cross-platform applications with Flutter
- ☁️ Interested in distributed systems, DevOps and high-performance APIs
- 🎯 Always learning something new every day

## 🚀 Currently working on

- 📅 EduAssist - timetable and substitution tracking application
- ⚡ High performance Go backend APIs
- 📱 Flutter mobile applications
- 🌍 React Router v7 websites

---

## 🌟 Featured Projects

### ⭐ EduAssist

> A modern school timetable platform built as a distributed system for students and school administrators.

🌐 **Website:** https://eduassist.site/

![Go](https://img.shields.io/badge/Go-1.25-00ADD8?logo=go)
![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)
![Laravel](https://img.shields.io/badge/Laravel-12-FF2D20?logo=laravel)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?logo=postgresql)
![CI/CD](https://img.shields.io/badge/CI/CD-Fully_Automated-success)
![Status](https://img.shields.io/badge/Status-Production-brightgreen)

<details>
<summary><b>View Architecture & DevOps Details</b></summary>

#### 🏗️ Architecture

| Component | Technology |
|-----------|------------|
| 📱 Mobile Application | Flutter |
| ⚙️ REST API | Go • Gin |
| 🛠️ Administration Panel | Laravel • Filament |
| 🗄️ Database | PostgreSQL |
| 🚀 CI/CD | Automated build & deployment pipeline |

#### ✨ Features

- 📅 Interactive school timetables
- 🔄 Real-time substitution updates
- 🔔 Instant push notifications for sudden timetable changes
- ⚙️ Dynamic school configuration managed from the admin panel
- 🕒 Accurate lesson period scheduling
- 🍽️ Lunch availability indicator based on timetable analysis
- 📥 Direct application downloads from the website
- 🔄 Automatic in-app updates without relying on Google Play

#### 🚀 DevOps & Infrastructure

EduAssist is deployed using a fully automated CI/CD pipeline.

**Technologies**
- 🐳 Docker
- 🌐 Nginx
- ⚙️ GitHub Actions
- 🗄️ PostgreSQL

**Pipeline**
- ✅ Automatic builds on every push
- ✅ Automated backend deployment
- ✅ Automated admin panel deployment
- ✅ Flutter Android release builds
- ✅ Automatic Docker image creation
- ✅ Zero-downtime service updates
- ✅ Reverse proxy configured with Nginx
- ✅ HTTPS with SSL certificates
- ✅ Production server hosting

**Mobile Updates**
Instead of Google Play updates, EduAssist uses a custom update system.
- 📥 Downloads directly from https://eduassist.site/
- 🔄 In-app update checking
- 📦 Automatic APK version management
- 🚀 Instant release distribution
- ❌ No dependency on Google Play

#### 📦 Repository Structure

EduAssist consists of three independent applications:

📱 **eduassist-mobile**
- Flutter
- Push notifications
- Custom update system

⚙️ **eduassist-backend**
- Go
- Gin
- PostgreSQL
- REST API

🛠️ **eduassist-admin**
- Laravel
- Filament
- PostgreSQL
- School configuration management

#### 💡 Highlights
- Production-ready architecture
- Fully automated CI/CD pipeline
- Custom Android update infrastructure
- Modular multi-service architecture
- PostgreSQL-backed configuration system
- Designed for scalability and maintainability

</details>

---

### ⭐ GoSearch Engine

> A high-performance, zero-dependency product search and autocomplete engine built with Go standard library and custom algorithmic data structures.

![Go](https://img.shields.io/badge/Go-1.25-00ADD8?logo=go)
![Architecture](https://img.shields.io/badge/Dependencies-Zero_Third__Party-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

#### ✨ Key Algorithmic Features

- 🎯 **Multi-Index Hybrid Search:** Combines Inverted Index, Trie, Phonetic Index, and BK-Trees for instant, relevant retrieval.
- 🔤 **Autocomplete Engine:** Fast prefix lookup using custom Trie structures.
- 💡 **Fuzzy Matching:** Levenshtein-distance based BK-Tree implementation for typo tolerance.
- ⚡ **High Efficiency:** Sub-millisecond lookup times for datasets up to 100,000 items.

#### 🛠️ Data Structures Implemented

| Data Structure | Purpose | Search Complexity |
|:---|:---|:---:|
| **Inverted Index** | Full-text product term matching | $\mathcal{O}(1 + k)$ |
| **Trie** | Fast prefix autocomplete | $\mathcal{O}(m)$ |
| **BK-Tree** | Typo-tolerant / Fuzzy search | $\mathcal{O}(\log n)$ avg |
| **B-Tree** | Price range and date queries | $\mathcal{O}(\log n)$ |
| **Phonetic Index** | Sound-alike search matching | $\mathcal{O}(1 + k)$ |

🔗 **Repository:** [mrredo/algoritmi-6-smr](https://github.com/mrredo/algoritmi-6-smr)

---

### ⭐ Library Management System

> A comprehensive, Dockerized library resource and book borrowing management system built with Laravel and Filament.

![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?logo=php)
![Laravel](https://img.shields.io/badge/Laravel-10%2B-FF2D20?logo=laravel)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED?logo=docker)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

<details>
<summary><b>View Architecture & Features</b></summary>

#### 🏗️ Architecture & Infrastructure

| Component | Technology |
|-----------|------------|
| ⚙️ Backend Framework | Laravel |
| 🛠️ Admin Panel | Filament PHP |
| 🗄️ Database | MySQL (ACID Compliant) |
| 🐳 Deployment | Docker |

#### ✨ Key Features

- 👥 **Role-Based Access Control:** Distinct panels and permissions for Guests, Registered Users, and Administrators using Laravel Policies.
- 📚 **Resource Management:** Full CRUD capabilities for books, authors, genres, and languages.
- 🔄 **Borrowing System:** Automated book checkout requests, return tracking, and overdue penalty calculations.
- 🔍 **Optimized Search:** Fast filtering and searching powered by well-structured database indexing.
- 🔒 **Security First:** Prepared SQL statements for injection prevention, data validation, and secure password hashing.

</details>

🔗 **Repository:** [mrredo/library-system](https://github.com/mrredo/library-system)

---

## 🛠️ Tech Stack

### 💻 Languages

<p align="left">
  <a href="https://golang.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" width="40" height="40"/></a>
  <a href="https://www.typescriptlang.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40"/></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40"/></a>
  <a href="https://www.php.net"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" width="40" height="40"/></a>
  <a href="https://www.java.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40"/></a>
</p>

### 🎨 Frontend

<p align="left">
  <a href="https://react.dev"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40" height="40"/></a>
  <a href="https://tailwindcss.com"><img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="40" height="40"/></a>
  <a href="https://www.w3.org/html/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40" height="40"/></a>
  <a href="https://www.w3schools.com/css/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="40" height="40"/></a>
</p>

### ⚙️ Backend

<p align="left">
  <a href="https://laravel.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" width="40" height="40"/></a>
  <a href="https://expressjs.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="40" height="40"/></a>
  <a href="https://spring.io"><img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" width="40" height="40"/></a>
  <a href="https://nodejs.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="40" height="40"/></a>
</p>

### 📱 Mobile

<p align="left">
  <a href="https://flutter.dev"><img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" width="40" height="40"/></a>
  <a href="https://firebase.google.com"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="40" height="40"/></a>
</p>

### 🗄️ Databases

<p align="left">
  <a href="https://www.postgresql.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" height="40"/></a>
  <a href="https://redis.io"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" width="40" height="40"/></a>
  <a href="https://www.mysql.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="40" height="40"/></a>
  <a href="https://www.mongodb.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="40" height="40"/></a>
  <a href="https://www.sqlite.org"><img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" width="40" height="40"/></a>
</p>

### 🚀 DevOps & Tools

<p align="left">
  <a href="https://www.docker.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="40" height="40"/></a>
  <a href="https://www.nginx.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="40" height="40"/></a>
  <a href="https://git-scm.com"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="40" height="40"/></a>
  <a href="https://www.gnu.org/software/bash/"><img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" width="40" height="40"/></a>
  <a href="https://www.linux.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" height="40"/></a>
  <a href="https://www.postman.com"><img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="40" height="40"/></a>
  <a href="https://www.figma.com"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="40" height="40"/></a>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mrredo&show_icons=true&locale=en" alt="mrredo" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=mrredo&show_icons=true&locale=en&layout=compact" alt="mrredo" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mrredo&" alt="mrredo" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mrredo&count_private=true&show_icons=true&locale=en&include_all_commits=true?locale=en" alt="mrredo commits" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=mrredo&count_private=true&show_icons=true&locale=en&include_all_commits=true?locale=en" alt="mrredo top langs private" />
</p>

---

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.youtube.com/c/mrredogaming8885" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="mrredogaming8885" height="30" width="40" /></a>
<a href="https://www.leetcode.com/mrredo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="mrredo" height="30" width="40" /></a>
</p>
