# LUXETECH Ecommerce App – An Inclusive , Accessibility-Focused Electronics Store Flutter App

<p align="center">

  <!-- Open Source -->
  <a href="https://github.com/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter">
    <img src="https://badges.frapsoft.com/os/v2/open-source.svg?v=10" alt="Open Source Love"/>
  </a>

  <!-- Tweet Button -->
  <a href="https://twitter.com/intent/tweet?text=Check%20out%20this%20awesome%20Flutter%20E-Commerce%20app%20for%20Electronics!%20%F0%9F%93%BA%20%23Flutter%20%23OpenSource%20by%20%40yassaYM7%0Ahttps://github.com/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter">
    <img src="https://img.shields.io/badge/Tweet-Share-blue?logo=twitter&style=social" alt="Tweet"/>
  </a>

  <!-- Stars -->
  <a href="https://github.com/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter/stargazers">
    <img src="https://img.shields.io/github/stars/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter?style=social" alt="GitHub stars"/>
  </a>

  <!-- Forks -->
  <a href="https://github.com/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter/network/members">
    <img src="https://img.shields.io/github/forks/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter?style=social" alt="GitHub forks"/>
  </a>
</p>



<p align="center">
  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/yassa-mouris-7074b628b/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge" alt="LinkedIn"/>
  </a>

  <!-- Gmail -->
  <a href="mailto:yassatawfik27@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?logo=gmail&style=for-the-badge" alt="Email"/>
  </a>
</p>

---

<p align="center">

**LuxeTech** is a dual-interface mobile application developed as part of our graduation project. It’s designed to make online electronics shopping more inclusive and efficient by focusing on accessibility and usability.
</p>

## 📱 Download App ![GitHub All Releases](https://img.shields.io/github/downloads/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter/total?color=green)
### 👨‍🦯 Primary Users UI v1.0.0
<a href="https://github.com/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter/releases/download/primary-v1.0.0/PrimaryLuxTech.apk">
  <img src="https://playerzon.com/asset/download.png" width="150">
</a>

### 👁️‍🗨️ Secondary Users UI v1.0.0
<a href="https://github.com/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter/releases/download/Secondary_v1.0.0/SecondaryLuxTech.apk">
  <img src="https://playerzon.com/asset/download.png" width="150">
</a>




<p align="center">
  <video src="https://github.com/user-attachments/assets/15bdb8e9-2aad-4fce-9d8e-ab5fb224d956" width="90%" autoplay loop muted playsinline></video>
</p>




##  The App Aims to Serve Two Groups

### 1. **Primary Users:** People with partial or complete visual impairment  
- Built-in **voice assistant** that allows full navigation and interaction through intuitive, easy-to-remember voice commands.  
- Designed for **full control without relying on visual input**.

### 2. **Secondary Users:**  
- Normally-sighted people.  
- Includes **3 color-blind-friendly themes** that change the entire app’s color scheme to suit different types of color vision deficiency.

  
<br>

 <p align="center">
  <img src="https://github.com/user-attachments/assets/c9c6b3fa-25eb-499c-a0e4-f5afcaa000ac"width="90%" style="margin-right: 20px;">&nbsp;&nbsp;

</p>

<br>

---
## App Feature Highlights

🔐 Log In & sign Up | Email confirmation | profile management (Data is synced with supabase in real time)

🛍️ Browse products by categories and search | 🛒 Add to cart , place/return orders | ⭐ Order Ratings | 🎨 Theme switcher (color blindness themes)

🗣️ Voice assistant for full voice control


---
## Admin Dashboard Features
<p align="center" style="margin: 0; padding: 0; line-height: 0;">
  <img src="https://github.com/user-attachments/assets/e33e7e7b-b4b9-465f-8b9b-2ad6233fdcec" width="20%" style="margin: 0; padding: 0; display:inline-block; vertical-align:top;">
  <img src="https://github.com/user-attachments/assets/88c7d772-a045-400b-bf7f-299d874cdad2" width="20%" style="margin: 0; padding: 0; display:inline-block; vertical-align:top;">
  <img src="https://github.com/user-attachments/assets/b123cd70-d707-4931-87b3-4deaeb68f100" width="20%" style="margin: 0; padding: 0; display:inline-block; vertical-align:top;">
  <img src="https://github.com/user-attachments/assets/62a5f3bb-7eae-433e-a0aa-5b7307874784" width="20%" style="margin: 0; padding: 0; display:inline-block; vertical-align:top;">
  <br style="margin:0; padding:0; line-height:0;">
  <img src="https://github.com/user-attachments/assets/062459ef-d3f8-40a4-923e-5abac3499a94" width="82%" style="margin: 0; padding: 0; display:block;">
</p>

- Add, edit, and delete products
- Manage user access (block/unblock users)
- 📊 View and track orders
- 💳 View refund details (after approving returns)
-  Handle returns and customer issues
-  Sales analytics 


---


## 🛠️ Tech Stack
**Frontend:** Flutter (Dart)

**Backend:** Supabase (PostgreSQL, Auth, Storage, Function , Triggers,..)

**Database:** PostgreSQL with Row-Level Security (RLS)

**State Management:**
Provider is the main state management solution. The app uses ``ChangeNotifierProvider``, ``MultiProvider``, and classes like ``ProductProvider`` , ``CartProvider``, ``AuthProvider``, ``OrderProvider``, and ``WishlistProvider`` <br>All of which extend ChangeNotifier for ``reactive updates``.

**Local Storage Management:** ``shared_preferences`` is used to persist local data, including:
- Auth tokens, user info, and blocked user data (``AuthProvider``)
- Cached product data and quantities (``ProductProvider``)
- Cart items (``CartProvider``)
- Wishlist items (``WishlistProvider``)

**Each provider has dedicated methods to load/save this data using ``shared_preferences``
, Examples:**

- ``ProductProvider``: ``_saveToSharedPreferences``, ``_loadFromSharedPreferences``

- ``CartProvider``: ``_saveCartItems``, ``_loadCartItems``

- ``WishlistProvider``: ``_saveWishlistToPrefs``, ``_loadWishlistFromPrefs``

- ``AuthProvider``: ``_saveAuthData``, ``tryAutoLogin``, etc.

**Authentication:** Supabase Auth with role-based access (Admin , User)

**Realtime Sync:** Supabase Realtime Subscriptions – to sync products,and user data without reloading manually.

**Offline Caching:** Local database caches product data on the device to reduce redundant Supabase fetches. Data updates automatically via Supabase Realtime subscriptions whenever a change is detected.

**Media Hosting:** Supabase Storage – for storing and retrieving product images.



<details>
<summary>📦 <strong>Additional Libraries & Packages Used (Click to show)</strong></summary>

### 🖌️ UI/UX & Utility  
- `flutter_svg` – Render SVG images  
- `cached_network_image` – Image caching with placeholders  
- `shimmer` – Skeleton loaders  
- `carousel_slider`, `dots_indicator` – For image sliders  
- `lottie` – Animated assets  
- `fl_chart` – Graphs and charts  
- `google_fonts`, `intl` – Fonts and localization  

### 🧭 Navigation  
- `go_router` – Declarative routing and deep linking  

### 📱 Device & Platform Integration  
- `connectivity_plus` – Network status  
- `local_auth` – Fingerprint/face authentication  
- `package_info_plus`, `device_info_plus` – Device/app info  
- `path_provider` – Accessing file system  

### 🌐 HTTP Requests  
- `http` – Used for Supabase functions and other HTTP calls  

## 🗃️ Backend & Database
- ``supabase_flutter`` – Supabase integration (auth, database, storage)

## 📦 Core & State Management
``provider`` – Main state management solution 

### 🚀 Splash & Icons  
- `flutter_launcher_icons` – App icon generation  
- `flutter_native_splash` – Custom splash screen  

## 🔑 Permissions & Device
- ``permission_handler`` – Runtime permissions

### 🗣️ Voice & Accessibility
- ``speech_to_text`` – Speech recognition
- ``flutter_tts`` – Text-to-speech
</details>

---


## Full App Screenshots:
Explore the full interface for each user type by clicking the links below:
- [🧑‍🦱 Secondary Users Interface](docs/secondary.md)

- [🛡️ Admin Dashboard Interface](docs/admin.md) 

- [🦯 Primary Users Interface](docs/primary.md)

---

## Full App Video & Project Documentation and how to use voice assistant: [Here](https://drive.google.com/drive/u/2/folders/1QiA14KGVweFBvd0p_YZLZpH2SbCasOKq)

---

## 📲 Try the App Yourself
Want to explore **LuxTech** on your own device? , Download and test the latest versions below:
- 🧑‍🦱 [**Secondary Users Version(includes admin dashboard)**](https://github.com/DavidG2Q/LuxTech-ElectronicsStore/releases/tag/secondary-v1.0.0)
- 🦯 [**Primary (Voice-controlled, for visually impaired users)**](https://github.com/DavidG2Q/LuxTech-ElectronicsStore/releases/tag/primary-v1.0.0)
> ✅ Simply Install the APK directly on your Android device to experience the full functionality.
<br><br>You can also check all builds in the [Releases Section](https://github.com/DavidG2Q/LuxTech-ElectronicsStore/releases)

---

## 🙏 Special Thanks

Our Academic Doctors and Supervisors:
Thank you for your valuable guidance, insights, and constant encouragement which helped bring this project to life.<br>
Your support and collaboration were essential to the success of this work.<br>
A special thanks to my team members for their contributions during the development process, and to everyone who supported us in any capacity.

---

## 👥 Team Members
| Name             | Role                                      | GitHub                                        |
| ---------------- | ----------------------------------------- | --------------------------------------------- |
| **Yassa Mouris** | Project Manager / Team Leader             | [yassaYM7](https://github.com/yassaYM7)       |
| David Gamil      | Lead Developer                            | [DavidG2Q](https://github.com/DavidG2Q)       |
| Mostafa Hassan   | Developer                                 | [Mostafaa212](https://github.com/Mostafaa212) |
| Khaled Ashraf    | Developer                                 | [Recker-13](https://github.com/Recker-13)     |



---
## 📄 License
This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.   [![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)


You may use, copy, and adapt this project **only for non-commercial purposes** and must give appropriate credit.

🔗 [View License Details](https://creativecommons.org/licenses/by-nc/4.0/)

---

<p align="center">
  <img src="https://img.shields.io/badge/Weekly%20Views-1234-blue?style=for-the-badge&logo=github" width="420" />
  &nbsp;
  <img src="https://img.shields.io/badge/Monthly%20Views-9876-green?style=for-the-badge&logo=github" width="420" />
</p>


<p align="center">
  <a href="https://hits.seeyoufarm.com">
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/yassaYM7/E-Commerce-App-Inclusive-Electronics-with-Voice-Assistant-Flutter&count_bg=%2379C83D&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=Repo%20Views&edge_flat=false" alt="Repo Views"/>
  </a>
</p>

