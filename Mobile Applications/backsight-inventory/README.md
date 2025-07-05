# 📦 Backsight Inventory - Warehouse Management System

> **Enterprise-grade mobile inventory management application built with Expo and React Native**

[![Expo](https://img.shields.io/badge/Expo-SDK%2053-black)](https://expo.dev/)
[![React Native](https://img.shields.io/badge/React%20Native-0.79.2-blue)](https://reactnative.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-blue)](https://www.typescriptlang.org/)
[![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-2.6.1-purple)](https://redux-toolkit.js.org/)

## 🎯 **Project Overview**

Backsight Inventory is a comprehensive warehouse management system designed for mobile-first inventory operations. The application provides real-time inventory tracking, barcode scanning capabilities, and complete supply chain management features for modern businesses.

## ✨ **Core Features**

### **Inventory Management**
- 📊 **Real-time Stock Tracking** - Live inventory levels and stock movements
- 📱 **Barcode Scanning** - QR code and barcode scanning with camera integration
- 🔍 **Advanced Search & Filtering** - Multi-criteria product search and categorization
- 📈 **Stock Analytics** - Inventory reports and trend analysis
- ⚠️ **Smart Alerts** - Low stock notifications and reorder point management

### **Supply Chain Operations**
- 🏢 **Supplier Management** - Complete vendor database and relationship management
- 📋 **Purchase Order Management** - Digital PO creation and tracking
- 🧾 **Invoice Generation** - Automated invoice creation and management
- 📦 **Receiving & Shipping** - Inbound and outbound logistics tracking
- 🔄 **Stock Transfers** - Inter-warehouse inventory movements

### **Production & Workflow**
- 🏭 **Production Tracking** - Manufacturing process monitoring
- 👥 **Employee Management** - Staff roles, permissions, and activity tracking
- 📅 **Task Scheduling** - Work order management and scheduling
- 📊 **Performance Metrics** - KPI tracking and productivity analytics

### **System Features**
- ⚙️ **Settings & Preferences** - Customizable app configuration
- 🌐 **Multi-language Support** - Internationalization with i18next
- 📱 **Offline Capabilities** - Local data storage and sync
- 🔒 **Role-based Access Control** - Secure user permissions and authentication

## 🛠️ **Technology Stack**

### **Frontend Framework**
- **Expo SDK 53** - Development platform and build tools
- **React Native 0.79.2** - Cross-platform mobile framework
- **TypeScript 5.8.3** - Type-safe development environment

### **State Management**
- **Redux Toolkit 2.6.1** - Modern Redux state management
- **React Redux 9.2.0** - React bindings for Redux
- **Redux Persist** - State persistence and hydration

### **UI/UX Components**
- **Expo Vector Icons** - Comprehensive icon library
- **React Native Modal** - Modal dialog components
- **React Native Linear Gradient** - Gradient styling
- **React Native Skeleton Placeholder** - Loading state components

### **Camera & Media**
- **Expo Camera 16.1.6** - Camera functionality for barcode scanning
- **Expo Image Picker 16.1.4** - Image selection and capture
- **React Native Image Viewing** - Image gallery and viewer
- **React Native Compressor** - Media compression utilities

### **Data & Storage**
- **Axios 1.8.4** - HTTP client for API communication
- **AsyncStorage** - Local data persistence
- **Expo SecureStore** - Secure credential storage

### **Development Tools**
- **Metro** - JavaScript bundler
- **Jest** - Testing framework
- **ESLint** - Code linting and quality
- **TypeScript** - Static type checking

## 🏗️ **Architecture Overview**

### **Application Structure**
```
app/
├── components/          # Reusable UI components
│   ├── inventory/      # Inventory-specific components
│   ├── scanning/       # Barcode scanning components
│   ├── forms/          # Form components
│   └── common/         # Shared components
│
├── store/              # Redux store configuration
│   ├── slices/         # Redux Toolkit slices
│   ├── api/            # RTK Query API definitions
│   └── middleware/     # Custom middleware
│
├── utils/              # Utility functions
│   ├── barcode/        # Barcode processing utilities
│   ├── validation/     # Input validation
│   └── formatters/     # Data formatting
│
├── types/              # TypeScript type definitions
├── constants/          # Application constants
├── context/            # React context providers
└── hooks/              # Custom React hooks
```

## 📱 **Key Functionalities**

### **Barcode Scanning System**
- **Multi-format Support** - QR codes, UPC, EAN, Code 128, and more
- **Real-time Recognition** - Instant barcode detection and processing
- **Batch Scanning** - Multiple item scanning for efficiency
- **Manual Entry Fallback** - Alternative input methods

### **Inventory Operations**
- **Stock Adjustments** - Real-time inventory level updates
- **Cycle Counting** - Systematic inventory verification
- **Location Management** - Multi-warehouse and bin location tracking
- **Serial Number Tracking** - Individual item traceability

### **Reporting & Analytics**
- **Stock Reports** - Comprehensive inventory reports
- **Movement History** - Complete audit trail of stock changes
- **Performance Dashboards** - Visual analytics and KPIs
- **Export Capabilities** - Data export in multiple formats

## 🔧 **Configuration & Environment**

### **Environment Variables**
```bash
# API Configuration
EXPO_PUBLIC_API_BASE_URL=https://api.zhutadeveloping.com/api/v1
EXPO_PUBLIC_JWT_SECRET=your_jwt_secret_here

# App Configuration
EXPO_PUBLIC_APP_NAME=Backsight Inventory
EXPO_PUBLIC_DEFAULT_LANGUAGE=en
EXPO_PUBLIC_TIMEOUT=10000

# Debug Configuration
EXPO_PUBLIC_DEBUG_MODE=true
EXPO_PUBLIC_LOG_LEVEL=debug
```

## 🚀 **Performance Features**

### **Optimization Techniques**
- **Lazy Loading** - On-demand component and data loading
- **Image Optimization** - Automatic image compression and caching
- **Memory Management** - Efficient memory usage patterns
- **Background Sync** - Offline data synchronization

### **Offline Capabilities**
- **Local Database** - SQLite for offline data storage
- **Sync Queue** - Automatic data synchronization when online
- **Conflict Resolution** - Smart handling of data conflicts

## 📊 **Business Impact**

### **Operational Efficiency**
- **Reduced Manual Errors** - Automated data entry and validation
- **Faster Processing** - Streamlined inventory operations
- **Real-time Visibility** - Instant access to inventory data
- **Cost Reduction** - Optimized inventory levels and reduced waste

### **Scalability Features**
- **Multi-warehouse Support** - Enterprise-scale inventory management
- **User Role Management** - Scalable permission system
- **API Integration** - Seamless ERP and WMS integration
- **Cloud Synchronization** - Centralized data management

---

**This project demonstrates expertise in enterprise mobile application development, showcasing proficiency in inventory management systems, barcode scanning technology, and scalable mobile architecture.**

