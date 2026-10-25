# 💙 CHANSEY AI

**AI-Powered Elderly Companion with Low-Bandwidth Teleconsultation**

> “Always Caring. Always Connected.”

## 📌 Overview

CHANSEY AI is an AI-powered elderly-care platform designed to help senior citizens living alone maintain daily routines, connect with family members, and access healthcare professionals.

The platform combines multilingual voice interaction, medication reminders, caregiver notifications, symptom collection, and low-bandwidth teleconsultation. Its offline-first communication system queues non-urgent messages during network interruptions and synchronizes them when connectivity returns.

## 🚨 The Problem

- Elderly people living alone may struggle to access timely healthcare.
- Conventional telemedicine apps can be difficult for seniors with limited digital literacy.
- Rural and coastal communities often experience unreliable internet connectivity.
- Language barriers can complicate communication with healthcare professionals.
- Families may find it difficult to coordinate reminders and remote care.

## 💡 The Solution

CHANSEY AI provides:

- **Voice-First Companion:** Simple conversational assistance in supported regional languages.
- **Teleconsultation:** Chat and audio communication with healthcare professionals.
- **AI-Assisted Symptom Collection:** Structures user-reported concerns for clinician review.
- **Offline Messaging:** Queues messages and synchronizes them after reconnection.
- **Smart Reminders:** Scheduled medication and meal reminders with acknowledgements.
- **Caregiver Dashboard:** Displays consultation status, reminders, and consent-based alerts.
- **Emergency Guidance:** Identifies predefined warning signs and directs users to appropriate emergency assistance.

## ⚙️ Detailed System Flow

### 1. User Interaction
The elderly user speaks or selects an option in the mobile application.

### 2. Voice Processing
Speech-to-text converts supported-language speech into text. The assistant responds using text-to-speech.

### 3. Symptom Collection
A guided questionnaire collects the user's concerns and generates a structured summary.

### 4. Consultation Routing
Predefined rules route the request to an appropriate clinician queue, with escalation guidance for urgent warning signs.

### 5. Teleconsultation
The clinician reviews the request and responds through chat or audio, depending on connectivity.

### 6. Offline Synchronization
When connectivity is unavailable, non-urgent messages are stored locally and queued for secure synchronization.

### 7. Reminders and Caregiver Updates
Scheduled reminders are delivered, and authorized caregivers receive relevant updates based on consent and configured preferences.

## 🏗️ System Architecture

**Frontend — Flutter**
- Elder-friendly mobile interface.
- Voice interaction, chat, reminders, and caregiver dashboard.
- Local offline message queue.

**Backend — Python FastAPI**
- Authentication and user management.
- Consultation and symptom-processing APIs.
- Routing rules, notifications, and synchronization.

**Database**
- PostgreSQL for server-side profiles, consultation records, and reminders.
- SQLite for local offline data and pending messages.

**AI and Voice Services**
- Speech-to-text and text-to-speech.
- Conversational assistance and structured symptom summaries.
- Rule-based triage and clinician routing.

**Communication**
- WebRTC for audio consultations.
- REST APIs and WebSocket for messaging and status updates.
- Firebase Cloud Messaging for online push notifications.

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Flutter, Dart |
| Backend | Python, FastAPI |
| Server Database | PostgreSQL |
| Local Database | SQLite |
| Voice Processing | Speech-to-Text, Text-to-Speech |
| AI Assistance | LLM API, rule-based workflows |
| Teleconsultation | WebRTC |
| Real-Time Messaging | WebSocket, REST |
| Notifications | Firebase Cloud Messaging |
| Authentication | JWT, role-based access |
| Deployment | Docker, cloud hosting |

*These are proposed technologies for the implementation; specific providers and integrations should be selected and tested during development.*

## 🧠 Why CHANSEY AI?

Traditional telemedicine often requires users to navigate multiple screens and maintain a stable connection.

CHANSEY AI combines voice-first interaction with offline message queuing, guided consultation requests, and caregiver coordination in one accessible platform.

Its focus is not to replace doctors, but to make reaching them easier for elderly users.

## 🌟 Key Features

- Multilingual voice assistance.
- Low-bandwidth teleconsultation.
- Offline message storage and synchronization.
- Symptom collection and consultation routing.
- Medication and meal reminders.
- Caregiver notifications.
- Accessible interface for elderly users.
- Privacy-focused health information handling.

## 📈 Scalability Roadmap

**Phase 1 — Prototype**
Build voice interaction, reminders, consultation requests, and offline messaging.

**Phase 2 — Local Pilot**
Test with elderly users, caregivers, and healthcare professionals in coastal Karnataka.

**Phase 3 — Healthcare Partnerships**
Integrate clinics, primary health centres, and senior-care organizations.

**Phase 4 — Regional Expansion**
Add validated regional languages and expand to underserved communities across India.

## 💼 Business Model

- **Family subscriptions:** Affordable optional premium features.
- **Clinic subscriptions:** Consultation and patient-coordination tools.
- **Institutional partnerships:** Deployments for NGOs and senior-care organizations.
- **Public-health partnerships:** Potential collaboration with eligible rural healthcare programmes.

Essential safety guidance should remain accessible regardless of subscription status.

## 🔒 Security and Safety

- Secure authentication and role-based access.
- Encryption for data in transit and appropriate protection for stored data.
- Consent-based sharing with caregivers and healthcare professionals.
- Minimal collection and retention of sensitive information.
- Clear delivery status for queued messages.

CHANSEY AI does not diagnose medical conditions, prescribe medicines, or replace professional medical care. Offline messaging cannot guarantee immediate emergency assistance.

## 🎯 Expected Impact

- Improve access to healthcare communication.
- Reduce barriers caused by language and digital literacy.
- Support daily care routines and independent living.
- Improve coordination between elders, families, and clinicians.
- Extend teleconsultation access to low-connectivity communities.

## 🚀 Future Enhancements

- Expanded Kannada, Tulu, Malayalam, and other regional-language support.
- Optional fall and inactivity detection.
- SMS fallback for selected alerts.
- Integration with authorized healthcare systems.
- Improved offline voice processing and accessibility.

## 📄 Project Summary

**CHANSEY AI — Bringing Care Closer to Every Elder.**

An accessible, voice-first elderly companion that combines companionship, reminders, caregiver coordination, and low-bandwidth teleconsultation to help older adults stay connected to care.
