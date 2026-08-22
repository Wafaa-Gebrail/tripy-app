# Tripy-Travel-App

Developed a Flutter-based travel management application that connects travelers, travel companies, trip coordinators, and place owners in one platform.

The application allows users to discover and register for trips, while travel companies can manage trips and participants. Trip coordinators can manage active trips and share their real-time location with travelers.

## Features

- **Traveler Features**:
  - Browse and search available trips.
  - View complete trip details, routes, stops, dates, prices, and available seats.
  - Register and cancel registration for trips.
  - Track the trip coordinator's location in real time.
  - Receive trip updates and notifications.
  - Follow travel companies and interact with trip posts.
  - View upcoming and past trips.

- **Travel Company Management**:
  - Manage company profiles.
  - Create and manage trips.
  - Define trip routes and multiple stops.
  - Manage traveler registrations.
  - Assign trip coordinators.
  - Manage company employees and roles.
  - Share trip photos, videos, and updates.

- **Trip Coordinator Features**:
  - View assigned trips and participants.
  - Start and end active trips.
  - Share real-time GPS location with travelers.
  - Manage trip stops and mark them as reached.
  - Communicate with trip participants.
  - Share photos and videos during trips.

- **Place Management**:
  - Create and manage place profiles.
  - Add products and services with prices and descriptions.
  - Define place locations on the map.
  - Allow travelers to discover nearby places.

- **Real-Time Trip Tracking**:
  - Integrated **Google Maps** for displaying routes, stops, and live locations.
  - Implemented **SignalR** for real-time communication and location updates.
  - Track the trip coordinator's location during an active trip.
  - Send trip progress and stop-reached events to travelers.
  - Location updates are sent every 3 seconds during active tracking.

- **Notifications & Localization**:
  - Receive notifications for trip events, registrations, and updates.
  - Support for **Arabic and English** languages.

## Technologies Used

- **Dart & Flutter**: For building the mobile application.
- **Cubit (flutter_bloc)**: For state management and separating business logic from the UI.
- **SignalR**: For real-time communication, location tracking, and trip events.
- **Google Maps**: For maps, routes, stops, and real-time location visualization.
- **REST APIs**: For communication with backend services.
- **Geolocation**: For obtaining and monitoring the coordinator's current location.
- **Easy Localization**: For supporting Arabic and English languages.

## Technical Highlights

- Implemented real-time trip tracking using **SignalR** and **Google Maps**.
- Implemented continuous GPS location updates during active trips.
- Used **Cubit** to manage complex application states and business logic.
- Implemented different workflows and permissions based on user roles.
- Integrated map-based trip routes and multiple stops.
- Implemented real-time trip events such as trip start, completion, stop reached, and location updates.
- Built a multi-role travel platform supporting travelers, companies, coordinators, and place owners.
