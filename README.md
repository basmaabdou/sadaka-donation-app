Sadaka – Clothes Donation App

A Flutter mobile app that connects donors with charity organizations. Users can find organizations on the map, donate clothes, and earn reward coins for their donations. Graduation project.

<!-- ## Screenshots <p float="left"> <img src="screenshots/home.png" width="200" /> <img src="screenshots/map.png" width="200" /> <img src="screenshots/coins.png" width="200" /> </p> -->
Features
Onboarding, registration, login and password recovery flow
Sign in with Firebase Authentication and Google Sign-In
Browse organizations and brands, with details screens
Find organizations on Google Maps using the device location
Reward coins earned from donations
Online payment with Paymob
User profile with edit profile
Companion app: qrcode scans donation QR codes
Tech Stack
Flutter / Dart
State management: Bloc / Cubit
Networking: Dio (REST APIs)
Payments: Paymob
Auth: Firebase Auth, Google Sign-In
Maps & location: google_maps_flutter, geolocator, geocoding
Local storage: shared_preferences
Run the project
bash
git clone https://github.com/basmaabdou/sadaka-donation-app.git
cd sadaka-donation-app
flutter pub get
flutter run

