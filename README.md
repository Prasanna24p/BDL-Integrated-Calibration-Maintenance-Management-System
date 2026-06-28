# BDL Integrated Calibration & Maintenance Workflow Management System

A centralized industrial web application developed for **Bharat Dynamics Limited (BDL)** to streamline **asset calibration**, **machine maintenance**, and **operational monitoring** within a unified and traceable digital platform.

The system eliminates fragmented tracking methods by integrating calibration workflows, preventive maintenance, scheduled maintenance, asset monitoring, and centralized dashboards into a single industrial solution.

---

## Live Demo
🔗 https://bdl-integrated-calibration-maintenance-management-b8oqj0z7o.vercel.app

---

# Project Overview

The **BDL Integrated Calibration & Maintenance Workflow Management System** is designed to provide a centralized platform for managing industrial assets, calibration activities, and machine maintenance operations across departments.

The application enables organizations to maintain complete traceability of industrial equipment throughout its lifecycle while improving operational visibility and simplifying maintenance planning.

The system integrates:

* Calibration management for precision instruments and gauges
* Scheduled Maintenance (SM) management
* Preventive Maintenance (PM) management
* Asset lifecycle tracking
* Due-date monitoring
* Centralized operational dashboards
* Maintenance history logging
* Calibration certificate management
* Audit-ready documentation

The primary objective of the project is to improve operational efficiency, reduce manual record management, and provide a single source of truth for calibration and maintenance activities.

---

# Key Features

* Centralized Asset Management
* Calibration Workflow Management
* Machine Maintenance Management (SM & PM)
* Real-Time Due Tracking
* Dashboard Analytics
* Asset Traceability
* Maintenance History Logging
* Calibration Certificate Generation
* Search & Filtering
* Responsive User Interface
* Modular Architecture
* Audit-Ready Documentation

---

# System Modules

## 1. Dashboard (Central Monitoring System)

The dashboard acts as the operational control center of the application, providing real-time visibility into calibration and maintenance activities.

### Dashboard Features

* Total Assets Overview
* Maintenance Status Summary
* Calibration Status Monitoring
* Due & Overdue Activities
* Department-wise Asset Distribution
* Performance Indicators
* Operational Statistics

---

## 2. Master List (Asset Registry)

The Master List maintains a centralized repository of all industrial assets, including machines, instruments, gauges, and equipment.

| Asset Code | Asset Type | Description | Department | Status | Periodicity | Last Activity | Next Due Date |
| ---------- | ---------- | ----------- | ---------- | ------ | ----------- | ------------- | ------------- |

### Features

* Centralized Asset Repository
* Department-wise Classification
* Lifecycle Tracking
* Asset Identification
* Equipment Status Monitoring

---

## 3. Due List (Maintenance & Calibration Tracker)

The Due List provides complete visibility into upcoming, pending, and overdue calibration and maintenance activities.

| Code No | Asset Type | Activity Type | Periodicity | Last Date | Due Date | Status | Next Scheduled Date | Postponement Reason |
| ------- | ---------- | ------------- | ----------- | --------- | -------- | ------ | ------------------- | ------------------- |

### Features

* Due Date Monitoring
* Overdue Asset Tracking
* Activity Status Management
* Postponement Tracking
* Maintenance Prioritization

---

## 4. Calibration Management Module

The Calibration Module manages calibration workflows for precision measuring instruments used in industrial environments.

### Supported Equipment

* Vernier Calipers
* Micrometers
* Thread Plug Gauges
* Double Ended Gauges
* Measuring Instruments
* Inspection Equipment

### Functionalities

* Calibration Entry
* Calibration Validation
* GO / NO-GO Decision Logic
* Calibration Certificate Generation
* Calibration History
* Traceability Records
* Audit Support

---

## 5. Machine Maintenance Module

The Maintenance Module manages industrial maintenance activities for manufacturing equipment.

### Supported Equipment

* Air Compressors
* Central AC Units
* Industrial Machines
* Mechanical Equipment

### Functionalities

* Scheduled Maintenance (SM)
* Preventive Maintenance (PM)
* Work Order Tracking
* Spare Part Management
* Maintenance History
* Maintenance Planning
* Equipment Service Records

---

# Dashboard & Analytics

The system provides interactive dashboards that help monitor operational performance.

### Dashboard Includes

* Asset Summary
* Calibration Completion Rate
* Maintenance Status
* Due & Overdue Equipment
* Department Statistics
* Equipment Availability
* Performance Metrics
* Operational KPIs

---

# System Workflow

```text
Asset Registration
        │
        ▼
Calibration / Maintenance Assignment
        │
        ▼
Schedule Monitoring
        │
        ▼
Due Date Tracking
        │
        ▼
Calibration / Maintenance Execution
        │
        ▼
Status Update
        │
        ▼
History Logging
        │
        ▼
Dashboard Analytics
        │
        ▼
Report Generation
```

---

# Technology Stack

## Frontend

* React.js
* Vite
* JavaScript (ES6+)
* HTML5
* CSS3

## UI Components

* Tailwind CSS
* AG Grid
* Lucide React Icons

## Data Processing

* XLSX

## Reporting

* jsPDF
* jsPDF AutoTable

## Visualization

* Recharts

## Notifications

* React Hot Toast

## Deployment

* Vercel

---

# Industrial Relevance

The system addresses several real-world industrial challenges, including:

* Fragmented maintenance records
* Manual calibration tracking
* Limited asset visibility
* Lack of centralized monitoring
* Inefficient certificate management
* Poor maintenance scheduling transparency
* Limited audit traceability

The centralized architecture improves operational efficiency while supporting quality assurance and maintenance compliance within industrial environments.

---

# Benefits

* Centralized Asset Management
* Improved Equipment Traceability
* Reduced Manual Documentation
* Better Maintenance Planning
* Faster Calibration Tracking
* Real-Time Operational Monitoring
* Improved Audit Readiness
* Enhanced Decision Making
* Increased Operational Efficiency
* Scalable Modular Design

---

# Future Enhancements

* Role-Based Authentication
* Backend Database Integration (MongoDB / SQL)
* Cloud Deployment
* Automated Email Notifications
* Predictive Maintenance Analytics
* AI-Based Maintenance Recommendations
* Advanced KPI Dashboard
* PDF Automation
* Mobile Application Support
* IoT Device Integration

---

# Team Members

* **Lakshmi Prasanna Pandi**
* **DSVNS Srinidhi**
* **Nithya Giri Barigela**

---

# Developed For

**Bharat Dynamics Limited (BDL)**

**Quality Management Department**

Internship Project – **Integrated Calibration & Maintenance Workflow Management System**

---

# License

This project has been developed for **academic, internship, and demonstration purposes**. The application is intended to showcase industrial calibration and maintenance workflow management concepts and is not intended for commercial distribution.
