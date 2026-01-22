# Electroteca  
A policy-driven electronics lending platform

## Overview
Electroteca is a full-stack web application designed to support secure and transparent lending of electronic devices within academic and professional environments. The platform combines institutional inventory management, where universities publish and govern their own devices, with verified peer-to-peer lending, allowing individuals to list personal equipment and earn credits when their devices are borrowed.

Electroteca focuses on trust, accountability, and safety by integrating user verification, device condition logging, escrow-based payments, reputation tracking, and calibration records. The system provides a modern solution for managing shared electronic resources efficiently.

## Features
- **User Authentication & Security**
  - Secure Sign Up / Login
  - Email OTP & Two-Factor Authentication
  - Google OAuth
  - Role-Based Access Control
- **Device Lending System**
  - Device catalog and advanced search
  - Reservations, check-out, and check-in
  - Institutional and peer-owned devices
- **Payments & Escrow**
  - Escrow-based lending protection
  - Hybrid payments and wallet credits
- **Reputation & Safety**
  - User reputation system
  - Device condition logging
  - Dispute and damage handling
- **Communication & Notifications**
  - Automated reminders
  - System messaging and status updates
- **Administration**
  - Inventory governance
  - User moderation
  - System monitoring

## Tech Stack
**Frontend**
- React 19
- Inertia.js
- Vite
- Tailwind CSS
- TypeScript

**Backend**
- PHP 8.2
- Laravel 12
- Laravel Fortify
- Laravel Socialite
- Laravel Cashier (Paddle)

**Database**
- MySQL / PostgreSQL

**DevOps & Tooling**
- Docker & Laravel Sail
- Vite
- Pest (Testing)

## 🚀 Getting Started

### Prerequisites
- PHP 8.2+
- Composer
- Node.js 18+ & npm
- Docker & Docker Compose (recommended)

## 1. Environment Setup
Create the environment file:

```bash
cp .env.example .env

