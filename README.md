# 📍 Location Selection & Submission App

This Android application allows users to select their current location either **automatically using GPS** or **manually via a Google Map interface**, and submit the coordinates to a dummy API endpoint.

---

## 📲 Features

- ✅ Runtime permission handling for location access
- 📍 Fetch current location using GPS
- 🗺️ Manually select a location by tapping on a Google Map
- 📨 Send selected coordinates (latitude & longitude) to a placeholder API via POST request
- 🧾 Displays success or error messages based on API response

---

## 🛠 Tech Stack

- **Language:** Kotlin  
- **Tools:** Android Studio  
- **Maps:** Google Maps SDK  
- **API Integration:** Retrofit (optional), HTTP POST  
- **Permissions:** AndroidX, Location Services

---

## 📦 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/LocationApp.git
   cd LocationApp
2. Open in Android Studio

Open the project folder

Let Gradle sync automatically

Make sure you have an active emulator or connected device

step 3. Add Google Maps API Key

Go to local.properties or google_maps_api.xml

Add your API key:

xml
Copy
Edit
<string name="google_maps_key" templateMergeStrategy="preserve" translatable="false">
    YOUR_API_KEY_HERE
</string>





4.Build & Run

Hit ▶️ Run on Android Studio to install and launch the app

🚀 API Details
Endpoint:
https://example.com/api/submit-location

Method: POST

Headers: Content-Type: application/json

Body Example:

json
Copy
Edit
{
  "latitude": "28.6139",
  "longitude": "77.2090"
}








📦 LocationApp
 ┣ 📁 java/com/example/locationapp
 ┃ ┣ 📄 MainActivity.kt
 ┃ ┣ 📄 MapActivity.kt
 ┣ 📁 res/layout
 ┃ ┣ 📄 activity_main.xml
 ┃ ┣ 📄 activity_map.xml
 ┣ 📄 AndroidManifest.xml
 ┣ 📄 README.md


