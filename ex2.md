# Requirements Specification of Rebu

## Members:

-   Huy Vuong
-   Minh Nguyen
-   Vy Nguyen

## 1. Overview

### 1.1 Description

The Rebu app is a mobile application that allows users to request a ride from one location to another or share a ride with another users in the same direction. The app connects users with drivers who are available to provide transportation services. The app is designed to be user-friendly and convenient, providing a safe and reliable way for users to get to their destination.

### 1.2 Actors

-   User: The person who requests a ride using the Rebu app.
-   Driver: The person who provides transportation services using the Rebu app.
-   Payment Partner: The company that processes payments for the Rebu app.
-   Admin: The person who manages the Rebu app and its users.
-   Hacker: The person who tries to hack the Rebu app and its users.

### 1.3 Security Goals

-   System need to always update live location of the driver and user.
-   System should not be down/ Limit system downtime
-   User personal information should be secured (e.g. name, phone number, email address)
-   Driver identity should be verified based on government ID
-   Payment information should be secured (e.g. credit card information)

## 2. Use Cases

### 2.1 Use Cases

---

#### Use Case 1: Request a Ride

#### Actors:

-   User
-   Driver
-   Payment Partner
-   Rebu system

---

#### Use Case 2: Make a Payment

#### Actors:

-   User
-   Payment Partner
-   Rebu system

---

#### Use Case 3: Accept a Ride

#### Actors:

-   Driver
-   Rebu system

---

### 2.2 Detailed Use Case

#### Use Case 1: Request a Ride

#### Precondition:

-   User must have an account and be logged in.
-   User does not have any active ride request.
-   User's payment information must be verified.
-   Driver does not have any active ride on a different route to the user's destination.

#### Main flow of events:

-   Select destination
-   Select ride type (solo or ride-share; SUV or sedan)
-   Make a payment

### 2.4 Missused / Abuse case

## 3. Security Requirements

-   **Sec1:** The system must ensure that user personal information (e.g., name, phone number, email address) is encrypted and securely stored.
-   **Sec2:** The system must verify driver identity based on government-issued ID.
-   **Sec3:** The system must ensure that payment information (e.g., credit card information) is encrypted and securely processed.
-   **Sec4:** The system must update the live location of the driver and user in real-time.
-   **Sec5:** The system must limit downtime and ensure high availability.
-   **Sec6:** The system must implement measures to prevent unauthorized access and hacking attempts.

https://lucid.app/lucidchart/408b2818-44c5-4d2b-84ac-a4b629a18509/edit?view_items=kbeQPuuA~isM&invitationId=inv_94b70a47-1564-4ea4-8132-56699281a904
