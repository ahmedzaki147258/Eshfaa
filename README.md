# Eshfaa

## Overview
The Medical Management System is a comprehensive platform designed to facilitate various aspects of healthcare management. It comprises four applications, each tailored to different user roles and functionalities. This README provides an overview of the API endpoints and functionalities available within each application.

## Applications

### 1. Patient Application
The Patient Application allows users to manage their healthcare needs. It includes the following features:
- **Account Management**: Users can create accounts and verify them using email or SMS.
- **Password Recovery**: Options for password recovery via email or SMS.
- **Doctor Search**: Patients can search for doctors and view their schedules.
- **Appointment Booking**: Patients can book appointments with doctors for online consultations, including real-time chatting, voice calls, or video calls using Socket.io.
- **Hospital/Clinic Search**: Patients can search for hospitals or clinics and book appointments with doctors for in-person consultations.
- **Notification**: Firebase Cloud Messaging (FCM) is utilized to send notifications to patients about appointment updates and reminders.

### 2. Doctor Application
The Doctor Application allows medical practitioners to manage their schedules and patient consultations. Key features include:
- **Login and Password Recovery**: Doctors can log in and recover passwords within the application.
- **Appointment Management**: Doctors can manage appointment schedules and consult with patients online, including accepting or rejecting bookings and providing consultation summaries.
- **Notification**: FCM is used to send notifications to doctors about appointment requests, updates, and reminders.

### 3. Admin Application
The Admin Application provides administrative control over the system. Features include:
- **System Control**: Admins can manage specialties, doctors, appointments, and consultations.
- **Appointment Review**: Admins can review consultation summaries written by doctors and accept or reject them.
- **Facility Management**: Admins can add hospitals, clinics, and promotional offers.
- **Notification**: FCM is utilized to send notifications to admins about system events and updates.

### 4. Clinic/Hospital Application
The Clinic/Hospital Application is designed for managing clinic or hospital operations. Features include:
- **Doctor Management**: Add and manage doctors associated with the clinic or hospital.
- **Appointment Handling**: Manage booked appointments, including accepting or rejecting bookings.
- **Services Management**: Offer additional services such as radiology or laboratory tests, allowing patients to book desired services.
- **Notification**: FCM is used to send notifications to clinic/hospital staff about appointment requests, updates, and other relevant information.

## Conclusion
The Medical Management System is a versatile platform that provides comprehensive healthcare management solutions. From patient bookings and doctor consultations to administrative control and facility management, each application is designed to streamline healthcare processes and improve patient care, with the added benefit of Firebase Cloud Messaging for efficient communication and notification delivery.
