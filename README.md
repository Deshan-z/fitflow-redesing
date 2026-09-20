# FitFlow Redesign

FitFlow Redesign is a fitness tracking mobile app redesign created as part of the **IT3060 - Human Computer Interaction** module.

The main idea of this project is to improve the existing FitFlow experience by making it more **personalized, easier to use, and more engaging**. The redesign focuses on key problems identified in the case study, such as generic workout plans, difficult nutrition tracking, lack of motivation, and limited social interaction.

---

## What We Want to Improve

With this redesign, we aim to:

* Give users workout plans that better match their needs and routines.
* Make food and nutrition tracking quicker and easier.
* Show fitness progress in a simple and understandable way.
* Help users stay motivated through challenges and community features.
* Keep user accounts and fitness information secure.
* Build the system in a way that can be improved and expanded in the future.

---

## Technology Stack

### Frontend

**React Native** is selected for the mobile application because it allows us to develop for both Android and iOS using a shared codebase.

### Backend

**Node.js with Express.js** will be used to handle application logic, API requests, and communication between the mobile application and other services.

### Authentication & Real-Time Services

**Firebase Authentication** will be used for user login and authentication. Firebase services can also support real-time features such as notifications and community updates.

### Database

**PostgreSQL** will be used to store structured application data such as user information, workout data, and fitness-related records.

### AI Service

AI-related features will be handled separately using **TensorFlow Lite** and cloud-based AI services when required. These technologies can support features such as personalized workout recommendations and smarter nutrition tracking.

---

## Project Structure

```text
fitflow-redesign/
│
├── frontend/
│   └── React Native mobile application
│
├── backend/
│   └── Node.js + Express backend
│
├── ai-service/
│   └── AI and machine learning services
│
├── docs/
│   ├── comparison-matrix/
│   │   └── technology-comparison.md
│   │
│   ├── architecture/
│   │   └── fitflow-architecture.png
│   │
│   └── adr/
│       └── ADR-001-technology-stack.md
│
├── .gitignore
└── README.md
```

---

## Main Features

The proposed FitFlow redesign includes:

* Personalized workout recommendations
* Workout and progress tracking
* Easier nutrition tracking
* Community challenges and social features
* Secure user authentication
* Real-time notifications
* Better control over personal fitness information

---

## System Overview

The **React Native** mobile application communicates with the **Node.js/Express** backend through APIs.

**Firebase Authentication** handles user authentication, while Firebase services can be used for real-time notifications and community-related updates.

The **AI service** is kept separate from the main backend so that features such as workout personalization and nutrition recognition can be developed, tested, and improved independently.

---

## Documentation

This repository contains the supporting documents prepared for the FitFlow technology selection and system design:

* **Technology Comparison Matrix**
* **High-Level Architecture Diagram**
* **Architecture Decision Record (ADR)**

These documents can be found inside the `docs/` directory.

---

## Module Details

| Details          | Information                         |
| ---------------- | ----------------------------------- |
| **Module**       | IT3060 - Human Computer Interaction |
| **Year**         | 3rd Year                            |
| **Semester**     | Semester 2 - 2026                   |
| **Lab Exercise** | 05                                  |
| **Project**      | FitFlow Redesign                    |
| **Student ID**   | IT23539372                          |

---

## Project Goal

The goal of FitFlow Redesign is to create a **more personalized, user-friendly, motivating, and scalable fitness tracking experience** while applying Human Computer Interaction principles to the design and development process.

Student ID: IT23539372
