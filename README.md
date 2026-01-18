# ChargeIt iOS App

## Overview
ChargeIt is an iOS application designed to help users discover and manage electric vehicle charging experiences through a clean, intuitive mobile interface. The app provides a complete onboarding and authentication flow, vehicle management, map-based discovery of charging locations, payment screens, and powerful filtering options to help users find chargers that match their vehicle’s requirements.

This project demonstrates real-world iOS development patterns including navigation-based flows, form handling, map integration, and modular feature design using UIKit.

## Implementation Status
The UI has been created using **Storyboards**, and the core functionality is **yet to be implemented**. This project currently focuses on user interface design, navigation flow, and screen structure.

---

## Features

### Authentication
- **Sign Up**
  - User registration using form-based input
- **Sign In**
  - Secure login experience
- **Forgot Password**
  - Password recovery flow

### Onboarding & Navigation
- Guided onboarding flow
- Home screen setup after authentication
- Navigation managed using `UINavigationController`

### Vehicle Management
- **Add Vehicle**
  - Capture vehicle details
  - Designed to support charger compatibility and future backend integration

### Maps & Charging Locations
- Map-based screen showing nearby charging stations
- Built using **MapKit**
- Ready for dynamic data integration

### Filters (Charging Compatibility)
Users can filter charging locations to find chargers compatible with their vehicle.

**Filter Options Include:**
- **Charging Port Type**
  - Type 1
  - CHA
  - Tesla / NACS
- **Charger Type / Speed**
  - Slow
  - Standard
  - Rapid

Filtered results update the map and listings in real time, improving user discovery and experience.

### Payments
- Payment screen UI for charging sessions
- Designed to support future integration with payment providers (Apple Pay, Stripe, etc.)

---

## User Flow

1. App launch
2. **Sign Up / Sign In**
3. Onboarding flow
4. Home screen
5. User can:
   - Add a vehicle
   - View charging stations on the map
   - Apply filters by port type and charger type
   - Proceed with payment

---

## Tech Stack
- **Language:** Swift
- **UI Framework:** UIKit
- **Navigation:** UINavigationController
- **Maps:** MapKit
- **Platform:** iOS

---

## Requirements
- Xcode 14+
- iOS 15+ (recommended)
- macOS compatible with Xcode version
