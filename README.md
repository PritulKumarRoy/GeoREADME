<div align="center">
  <img src="lo.png" width="120" height="120" alt="Smart GNSS System Logo"/>
</div>

<h1 align="center">SMART GNSS SYSTEM | Geo</h1>
<h3 align="center"><em>A mobile application for geofencing, navigation and location-based services.</em></h3>

<br>

---

# OVERVIEW <img src="b.png" width="40" align="left"/>

The smart GNSS system is an android based mobile application that provides efficient geofencing, location tracking and map navigation. This platform aims to solve real-world issues related to geofencing, location accuracy and navigation efficiency.
<br><br>

# OBJECTIVES <img src="f.png" width="40" align="left"/>

• Provide robust geofencing.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Provide accurate real-time location data.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Provide real-time location sharing (with consent).&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Deliver map (OSM) navigation with access to various map tiles.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Offer capture coordinate feature.
<br><br>

# PROBLEM STATEMENTS <img src="g.png" width="40" align="left"/>

1. Inaccurate reception of real-time location data.
2. Real-time location track of any user with explicit, informed and revocable consent.
3. Unavailability of an efficient mobile based system that can detect user location within predefined geographic areas while ensuring accuracy and low battery consumption.
4. OpenStreetMap lacks real-time path trajectory display based on user location data and capture coordinate ability.
<br><br>

# TECHNOLOGY STACK <img src="g.png" width="40" align="left"/>
<br>

<table> 
  <tr> 
    <td> <img src="l1.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Flutter </td>
    <td> <img src="l2.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Firebase </td> 
  </tr> 
  <tr> 
    <td> <img src="l3.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> OpenStreetMap (OSM) </td>
    <td> <img src="l4.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Java Development Kit (JDK) </td> 
  </tr> 
  <tr> 
    <td> <img src="l5.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Gradle </td>
    <td> <img src="l8.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Notepad </td> 
  </tr>
  <tr> 
    <td> <img src="l6.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Android Studio </td>
    <td> <img src="l7.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Visual Studio </td> 
  </tr> 
  <tr> 
    <td colspan="2"> <img src="l9.png" width="40" style="vertical-align: middle; margin-right: 10px;"/> Map Tiler </td>
  </tr> 
</table>
<br><br>

# APPLICATION WORKING ARCHITECTURE <img src="d.png" width="40" align="left"/>
<br>

<p align="center"> <img src="h.png" style="max-width: 500px; width: 100%; height: auto;" alt="Architecture Diagram"/> </p>
<br><br>

# MOBILE INTERFACES <img src="i.png" width="40" align="left"/>

<table style="width: 100%; border-collapse: collapse;"> 
  <tr valign="top">
    <td style="border: none; text-align: left; width: 50%; padding: 10px;">
      <h3>Registration screen</h3>
      <img src="sa.png" style="width: 100%; max-width: 400px; border-radius: 8px;">
    </td>
    <td style="border: none; text-align: left; width: 50%; padding: 10px;">
      <h3>Login screen</h3>
      <img src="sb.png" style="width: 100%; max-width: 400px; border-radius: 8px;">
    </td>
  </tr>
  <tr valign="top">
    <td style="border: none; text-align: left; padding: 10px;">
      <h3>Home screen</h3>
      <img src="sc.png" style="width: 100%; max-width: 400px; border-radius: 8px;">
    </td>
    <td style="border: none; text-align: left; padding: 10px;">
      <h3>Location tracking screen</h3>
      <img src="sd.png" style="width: 100%; max-width: 400px; border-radius: 8px;">
    </td>
  </tr>
  <tr valign="top">
    <td style="border: none; text-align: left; padding: 10px;">
      <h3>Custom geofence screen</h3>
      <img src="se.png" style="width: 100%; max-width: 400px; border-radius: 8px;">
    </td>
    <td style="border: none; text-align: left; padding: 10px;">
      <h3>Map screen</h3>
      <img src="sf.png" style="width: 100%; max-width: 400px; border-radius: 8px;">
    </td>
  </tr>
</table>
<br><br>

# KEY FUNCTIONS <img src="e.png" width="40" align="left"/>
<br>

<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="width: 45%; min-width: 300px;">
    <h3>Registration screen</h3>
    <ul> 
      <li> New user account registration. </li>
      <li> Old user account re-login. </li>
      <li> User account deletion (if wanted). </li> 
    </ul> 
  </div>

  <div style="width: 45%; min-width: 300px;">
    <h3>Login screen</h3>
    <ul> 
      <li> User account login (exact input of login credentials). </li>
      <li> New user registration and re-login. </li>
      <li> Access to main "Home page" of the application. </li> 
    </ul> 
  </div>

  <div style="width: 45%; min-width: 300px;">
    <h3>Home screen</h3>
    <ul> 
      <li> User profile display. </li>
      <li> Display of the '3' main buttons of the application. </li>
      <li> User logout access. </li> 
    </ul> 
  </div>

  <div style="width: 45%; min-width: 300px;">
    <h3>Location tracking screen</h3>
    <ul> 
      <li> User current location data analytics display. </li>
      <li> Real-time location check against pre-defined geofence boundary with proper fingerprint authentication in order to detect if a user is currently 'inside' or 'outside' the boundary. </li>
      <li> Based on final result displayed on screen, quick notification triggering happens with the result being saved in the 'Firebase' backend database. </li>
      <li> Until the screen is active, the real-time location tracking goes on with updated analytics data. </li>
      <li> Continuous real-time location data is fetched to the 'Firebase' backend database until the screen becomes inactive. </li>
    </ul> 
  </div>

  <div style="width: 45%; min-width: 300px;">
    <h3>Custom geofence screen</h3>
    <ul> 
      <li> Check any user's real-time location against a pre-defined geofence boundary using only 'latitude' and 'longitude' data. </li>
      <li> Track user real-time path trajectory on OSM display with analytics. </li>
      <li> Share and display real-time locations of multiple users on the map (with user consent). </li> 
      <li> Access versatile map tiles like satellite view, street view, etc. </li>
    </ul> 
  </div>

  <div style="width: 45%; min-width: 300px;">
    <h3>Map screen</h3>
    <ul> 
      <li> OpenStreetMap display with location navigation. </li>
      <li> Capture coordinate ability by clicking on any location on the map. </li>
      <li> In-app database for storing, copying, and deleting captured coordinates. </li>
      <li> Access to versatile map tiles like satellite view, street view, etc. </li>
    </ul> 
  </div>
</div>
<br><br>

# FUTURE POTENTIAL <img src="j.png" width="40" align="left"/>
<br>

• **Robust geofence setup:** The system can inject any geofence boundary into the application. This opens the door for advanced use cases such as region-based workflows, restricted area detection, and customizable location rules. It makes the project highly flexible and adaptable to real-world scenarios.

• **Consent based multiple user tracking:** With proper user consent, a single user can track the real-time locations of multiple users. This enables coordinated movement, team management, and safety monitoring while ensuring privacy and user control remain a priority.
<br><br><br><br>

<div style=" 
  padding: 10px 20px; 
  outline: 3px solid white;
  border-radius: 6px; 
  color: white; 
  background: transparent; 
  display: inline-block;">
  <u>FINAL NOTE</u> 
</div>
  
<p> Thanks for reading! If you like this project, please ⭐ the repo and feel free to open issues or PRs. Suggestions are always welcome! </p>
