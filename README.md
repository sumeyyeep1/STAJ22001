# Dijital Banka / Digital Banking App

[Türkçe](#türkçe) | [English](#english)

---

## Türkçe

Modern, sade ve kullanıcı dostu bir arayüze sahip tam kapsamlı (full-stack) dijital bankacılık simülasyon uygulamasıdır. Kullanıcıların hesaplarını yönetmesini, bakiye takibini ve hızlı para transferlerini güvenli bir şekilde gerçekleştirmesini sağlar.

### ✨ Öne Çıkan Özellikler

- **Kimlik Doğrulama & Yetkilendirme (Auth):**
  - Güvenli Giriş ve Kayıt (Login / Register) ekranı.
  - JWT tabanlı oturum yönetimi ve rol bazlı erişim kontrolü (Customer / Admin).
- **Genel Bakış (Dashboard):**
  - Toplam bakiye ve aktif hesap sayısını tek ekranda izleme.
  - Hesap türlerine göre (Checking, Savings, Investment) dinamik listeleme ve bakiye gizleme/gösterme seçeneği.
  - Hızlı işlem kısayolları (Hesap açma, transfer, para yatır/çek).
- **Para Transferi:**
  - Kaynak hesap seçimi ve otomatik formatlamalı 26 haneli IBAN doğrulama.
  - Anlık tutar ve açıklama girişleriyle saniyeler içinde havale/EFT simülasyonu.
- **Kart Yönetimi:**
  - Kartları listeleme, limit belirleme ve kart hareketlerini inceleme.

### 🛠️ Teknolojiler

- **Backend:** .NET Core Web API (C#), Entity Framework Core
- **Frontend:** React, TypeScript, Vite, Tailwind CSS / Custom CSS
- **Veritabanı:** MSSQL / PostgreSQL (EF Core Migrations)
- **Konteynerleştirme:** Docker, Docker Compose

---

### 🚀 Kurulum ve Çalıştırma

#### 1. Backend Kurulumu
```bash
cd DigitalBanking.API # veya kök dizindeki API projesi
dotnet restore
dotnet ef database update
dotnet run
```
*API varsayılan olarak `http://localhost:5267` üzerinde çalışır.*

#### 2. Frontend Kurulumu
```bash
cd frontend
npm install
npm run dev
```
*Arayüz varsayılan olarak `http://localhost:5173` üzerinde çalışır.*

---
---

## English

A full-stack modern digital banking simulation application featuring a clean, responsive, and intuitive user interface. It empowers users to monitor their accounts, manage cards, and execute money transfers seamlessly.

### ✨ Key Features

- **Authentication & Security:**
  - Minimal and secure Login & Register views.
  - JWT token-based authentication and role-based access (Customer / Admin).
- **Interactive Dashboard:**
  - At-a-glance summary cards showing Total Balance and Active Account Count.
  - Real-time accounts list supporting Checking, Savings, and Investment types.
  - One-click balance privacy toggle (hide/show balances) and quick action shortcuts.
- **Money Transfers:**
  - Source account selection with dynamic balance updates.
  - Built-in 26-character IBAN format validation, amount, and description fields.
- **Card & Account Management:**
  - Manage linked cards, view account activity, and track recent transactions.

### 🛠️ Tech Stack

- **Backend:** .NET Core Web API (C#), Entity Framework Core
- **Frontend:** React, TypeScript, Vite, Modern CSS
- **Database:** Relational Database via EF Core Migrations
- **DevOps:** Docker & Docker Compose support

---

### 🚀 Getting Started

#### 1. Running Backend
```bash
dotnet restore
dotnet ef database update
dotnet run
```
*The API runs at `http://localhost:5267` by default.*

#### 2. Running Frontend
```bash
cd frontend
npm install
npm run dev
```
*The web client runs at `http://localhost:5173` by default.*

---

### 📸 Screenshots

| Giriş / Login | Genel Bakış / Dashboard | Para Transferi / Transfer |
| :---: | :---: | :---: |
| ![Login View] <img width="1868" height="906" alt="Ekran Görüntüsü (508)" src="https://github.com/user-attachments/assets/deab2453-01b4-476d-8c6c-2d0748d22100" />
 | ![Dashboard View]<img width="1868" height="912" alt="Ekran Görüntüsü (509)" src="https://github.com/user-attachments/assets/92e32509-9229-4d3d-99e1-b38ecf4adc3f" />
 | ![Transfer View] <img width="1866" height="907" alt="Ekran Görüntüsü (510)" src="https://github.com/user-attachments/assets/7ba4697f-0eb2-4b6d-9201-c08d77c3add5" />

