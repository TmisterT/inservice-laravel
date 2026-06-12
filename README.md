<p align="center">
  <a href="#" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="300" alt="Laravel Logo">
  </a>
</p>

# Public Service Office (PSO) Inservice System

A centralized web application designed to streamline, track, and manage the end-to-end processing of in-service training and professional development applications within the public service. Built on the Laravel framework, this system transitions manual, paper-based workflows into a secure, auditable digital pipeline.

---

## 🔄 Core Workflow Pipeline

[ Applicant ] ──> Submit Application ──> [ Organisation Reviewer ] ──> Revise/HOD Parts/SRO Parts submit ──> [ PSO Admin ] ──> Final Approval

---

## 👥 System Portals & User Roles

The platform is partitioned into distinct access layers to ensure clear separation of duties and secure data boundaries:

### 💼 1. Applicants Side


### 🏢 2. Organisation Reviewer

### 👑 3. PSO & DTO Admintration (Filament Panels Optional)

## 🛠️ Built With
* **Backend Engine:** Laravel 12.x / PHP 8.2+
* **Administrative Architecture:** Filament PHP (TALL Stack)
* **Database Layer:** MySQL
---

## 🚀 Getting Started

### Prerequisites
* OS: Ubuntu 24v 
* PHP >= 8.2
* Composer
* MySQL / MariaDB

### Installation Steps

1. **Clone the repository and enter the directory:**
```bash
   git clone <repository-url>
   cd inservice-laravel
   composer install
   npm install && npm run build (optional)
cp .env.example .env
   php artisan key:generate
   php artisan migrate --seed
  php artisan serve
