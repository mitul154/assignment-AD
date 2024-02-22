# Title

Architecture Decisions for University Social Networking Mobile App

## Status

Proposed

## Context

The institution is creating a social networking software to facilitate communication between instructors and students, exchange academic data, and organize calendars. In addition to supporting offline mode, the app needs to be user-accessible, improve performance across a range of devices, integrate with Active Directory, offer push alerts, and guarantee data security and privacy.

## Decision

### Native, web, or hybrid app

Cross-Platform Framework: We will use a cross-platform framework like Flutter or React Native to develop the app. This allows for efficient development and maintenance across both iOS and Android platforms with a single codebase.

### UI Framework

For a hybrid app: React Native or Flutter are popular choices, offering a wide range of components and tools for building a responsive and accessible user interface.

### Backend

Node.js

### Permissions

The app will need permissions for internet access, push notifications.

### Data storage

For offline capabilities, a local database like SQLite.

### Any additional frameworks or technology stacks

Push Notification Service: Firebase Cloud Messaging (FCM) or OneSignal can be used to send push notifications to both iOS and Android devices.
