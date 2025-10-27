# ⚙️ DevOps Simulator

A comprehensive CI/CD configuration management tool for enterprise deployments.

## 📊 Project Status
- **Version**: 1.0.0 (Production), 2.0.0-beta (Development)
- **Environments**: Production & Development  
- **Student**: Kotipalli Lahari Sri  
- **Student ID**: 23MH1A05I0

---

## 🚀 Features

### 🔧 Core Features
- Automated deployment scripts  
- Real-time monitoring  
- Configuration management  
- Backup and recovery system  

### 🏭 Production Features
- SSL/TLS encryption  
- Auto-scaling  
- Load balancer integration  
- Scheduled backups  

### 💻 Development Features (Beta)
- Docker Compose integration  
- Hot reload enabled  
- Debug mode active  
- Enhanced logging  
- Mock external APIs  

---

## ⚡ Quick Start (Windows)

### 💻 Development Mode

```bash
:: Set environment to development
set NODE_ENV=development

:: Install dependencies
npm install

:: Start development server
npm run dev

### 🏭 Production Mode
:: Set environment to production
set DEPLOY_ENV=production
scripts\deploy.sh