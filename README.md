<div align="center">
  <img src="lo.png" width="120" height="120" alt="Smart GNSS System Logo"/>
</div>

<h1 align="center">SMART GNSS SYSTEM</h1>
<h3 align="center"><em>A mobile application for geofencing, navigation and location-based services.</em></h3>

<br>

---

## OVERVIEW <img src="b.png" width="40" align="left"/>

<br>

The smart GNSS system is an android based mobile application that provides efficient geofencing, location tracking and map navigation. This platform aims to solve real-world issues related to geofencing, location accuracy and navigation efficiency.

<br>

---

## OBJECTIVES <img src="f.png" width="40" align="left"/>

<br>

<div align="center">
  <table>
    <tr>
      <td align="center">• Provide robust geofencing.</td>
      <td align="center">• Provide accurate real-time location data.</td>
    </tr>
    <tr>
      <td align="center">• Provide real-time location sharing (with consent).</td>
      <td align="center">• Deliver map (OSM) navigation with access to various map tiles.</td>
    </tr>
    <tr>
      <td align="center" colspan="2">• Offer capture coordinate feature.</td>
    </tr>
  </table>
</div>

<br>

---

## PROBLEM STATEMENTS <img src="g.png" width="40" align="left"/>

<br>

1.  Inaccurate reception of real-time location data.
2.  Real-time location track of any user with explicit, informed and revocable consent.
3.  Unavailability of a efficient mobile based system that can detect user location within predefined geographic areas while ensuring accuracy and low battery consumption.
4.  OpenStreetMap lacks real-time path trajectory display based on user location data and capture coordinate ability.

<br>

---

## TECHNOLOGY STACK <img src="g.png" width="40" align="left"/>

<br>

<div align="center">

| | | |
| :---: | :---: | :---: |
| <img src="l1.png" width="40"/> Flutter | <img src="l2.png" width="40"/> Firebase | <img src="l3.png" width="40"/> OpenStreetMap |
| <img src="l4.png" width="40"/> JDK | <img src="l5.png" width="40"/> Gradle | <img src="l8.png" width="40"/> Notepad |
| <img src="l6.png" width="40"/> Android Studio | <img src="l7.png" width="40"/> Visual Studio | <img src="l9.png" width="40"/> Map Tiler |

</div>

<br>

---

## APPLICATION WORKING ARCHITECTURE <img src="d.png" width="40" align="left"/>

<br>

<p align="center">
  <img src="h.png" width="700" alt="Application Architecture Diagram"/>
</p>

<br>

---

## MOBILE INTERFACES <img src="i.png" width="40" align="left"/>

<br>

<div align="center">

| <h3>Registration Screen</h3> | <h3>Login Screen</h3> |
| :---: | :---: |
| <img src="sa.png" width="300"> | <img src="sb.png" width="300"> |

<br>

| <h3>Home Screen</h3> | <h3>Location Tracking Screen</h3> |
| :---: | :---: |
| <img src="sc.png" width="300"> | <img src="sd.png" width="300"> |

<br>

| <h3>Custom Geofence Screen</h3> | <h3>Map Screen</h3> |
| :---: | :---: |
| <img src="se.png" width="300"> | <img src="sf.png" width="300"> |

</div>

<br>

---

## KEY FUNCTIONS <img src="e.png" width="40" align="left"/>

<br>

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

<div style="width: 45%; min-width: 300px;">

### 📝 Registration Screen
- New user account registration.
- Old user account re-login.
- User account deletion (if wanted).
</div>

<div style="width: 45%; min-width: 300px;">

### 🔐 Login Screen
- User account login (exact input of login credentials).
- New user registration and re-login.
- Access to main "Home page" of the application.
</div>

<div style="width: 45%; min-width: 300px;">

### 🏠 Home Screen
- User profile display.
- Display of the '3' main buttons of the application.
- User logout access.
</div>

<div style="width: 45%; min-width: 300px;">

### 📍 Location Tracking Screen
- User current location data analytics display.
- Real-time location check against pre-defined geofence boundary with proper fingerprint authentication to detect if user is 'inside' or 'outside'.
- Quick notification triggering based on result, saved in Firebase backend.
- Continuous real-time location tracking and analytics while screen is active.
- Real-time location data fetching to Firebase backend until screen is inactive.
</div>

<div style="width: 45%; min-width: 300px;">

### 🚧 Custom Geofence Screen
- Real-time location check against pre-defined geofence using latitude/longitude data.
- User real-time path trajectory display on OSM with analytics.
- Real-time multiple user location sharing and display on map (with user consent).
- Access to versatile map tiles like satellite view, street view, etc.
</div>

<div style="width: 45%; min-width: 300px;">

### 🗺️ Map Screen
- OpenStreetMap display with location navigation.
- Capture coordinate ability by clicking on any location on the map.
- In-app database for storing, copying, and deleting captured coordinates.
- Access to versatile map tiles like satellite view, street view, etc.
</div>

</div>

<br>

---

## FUTURE POTENTIAL <img src="j.png" width="40" align="left"/>

<br>

- **Robust geofence setup:** The system can inject any geofence boundary into the application. This opens the door for advanced use cases such as region-based workflows, restricted area based detection and customizable location rules. It makes the project highly flexible and adaptable to real-world scenarios.

- **Consent based multiple user tracking:** With only after proper user consent, a single user can track the real-time locations of multiple users. This enables coordinated movement, team management and safety monitoring while ensuring privacy and user control remain a priority.

<br>

---

## FINAL NOTE

<div align="center">
  <img src="lo.png" width="60" height="60" alt="Smart GNSS System Logo"/>
  <p><strong>Thanks for reading! If you like this project please ⭐ the repo and feel free to open issues or PRs. Suggestions are always welcome!</strong></p>
</div>
