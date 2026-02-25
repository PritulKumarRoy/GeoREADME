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

• Provide robust geofencing.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Provide accurate real-time location data.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Provide real-time location sharing(with consent).&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Deliver map(OSM) navigation with access to various map tiles.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Offer capture coordinate feature.
<br><br>

# PROBLEM STATEMENTS <img src="g.png" width="40" align="left"/>

1. Inaccurate reception of real-time location data.
2. Real-time location track of any user with explicit, informed and revocable consent.
3. Unavailability of a effecient mobile based system that can detect user location within predefined geographic areas while ensuring accuracy and low battery consumption.
4. OpenStreetMap lacks real-time path trajectory display based on user location data and capture coordinate ability.
<br><br>

# TECHNOLOGY STACK <img src="g.png" width="40" align="left"/>
<br>

<table> 
<tr> 
  <td> • <img src="l1.png" width="40" align="left"/> Flutter </td>
  <td> • <img src="l2.png" width="40" align="left"/> Firebase </td> 
</tr> 
<tr> 
  <td> • <img src="l3.png" width="40" align="left"/> OpenStreetMap(OSM) </td>
  <td> • <img src="l4.png" width="40" align="left"/> Java development kit(JDK) </td> 
</tr> 
<tr> 
  <td> • <img src="l5.png" width="40" align="left"/> Gradle </td>
  <td> • <img src="l8.png" width="40" align="left"/> Notepad </td> 
</tr>
<tr> 
  <td> • <img src="l6.png" width="40" align="left"/> Android studio </td>
  <td> • <img src="l7.png" width="40" align="left"/> Visual studio </td> 
</tr> 
<tr> 
  <td> • <img src="l9.png" width="40" align="left"/> Map tiler </td>
</tr> 
</table>
<br><br>

# APPLICATION WORKING ARCHITECTURE <img src="d.png" width="40" align="left"/>
<br>

<p align="center"> <img src="h.png" height="100000" width="500"/> </p>
<br><br>

# MOBILE INTERFACES <img src="i.png" width="40" align="left"/>

<table> 
  <tr valign="top">
  <td style ("border: none; text-align: left;">
  <h3>Registration screen</h3>
    <br>
  <img src="sa.png" width="400">
    </td><br>
    
  <td style ("border: none; text-align: left;">
  <h3>Login screen</h3>
    <br>
  <img src="sb.png" width="400">
    </td>
  </tr>
    
  <tr valign="top">
  <td style ("border: none; text-align: left;">
  <h3>Home screen</h3>
    <br>
  <img src="sc.png" width="400">
    </td><br>
    
  <td style ("border: none; text-align: left;">
  <h3>Location tracking screen</h3>
    <br>
  <img src="sd.png" width="400">
    </td>
  </tr>
    
  <tr valign="top">
  <td style ("border: none; text-align: left;">
  <h3>Custom geofence screen</h3>
    <br>
  <img src="se.png" width="400">
    </td><br>
    
  <td style ("border: none; text-align: left;">
  <h3>Map screen</h3>
    <br>
  <img src="sf.png" width="400">
    </td>
  </tr>
<br><br>
</table>
<br><br>

# KEY FUNCTIONS <img src="e.png" width="40" align="left"/>
<br>

<div style ("display: flex; flex-wrap: wrap; gap: 20px">
<div style ("width: 45%; min-width: 300px;">
<h3> Registration screen </h3>
  <br>
<ul> 
  <li> New user account registration. </li>
  <li> Old user account re-login. </li>
  <li> User account deletion (if-wanted). </li> 
</ul> 
</div>

<div style ("width: 45%; min-width: 300px;">
<h3> Login screen </h3>
  <br>
<ul> 
  <li> User account login (exact input of login credentials). </li>
  <li> New user registration and re-login. </li>
  <li> Access to main "Home page" of the application. </li> 
</ul> 
</div>

<div style ("width: 45%; min-width: 300px;">
<h3>Home screen</h3>
  <br>
<ul> 
  <li> User profile display. </li>
  <li> Display of the '3' main buttons of the application. </li>
  <li> User logout access. </li> 
</ul> 
</div>

<div style ("width: 45%; min-width: 300px;">
<h3>Location tracking screen</h3>
  <br>
<ul> 
  <li> User current location data analytics display </li>
  <li> Real-time location check against pre-defined geofence boundary with proper fingerprint authentication in order to detect an user is currently 'inside' or 'outside' the boundary. </li>
  <li> Based on final result displayed on screen, quick notification triggering happens with the result being saved in 'firebase' backend database. </li>
  <li> Until the screen is active the real-time location tracking goes on with updated analytics data. </li>
  <li> Until and unless the screen gets inactive, continious real-time location data fetching goes on to the 'firebase' backend database. </li>
</ul> 
</div>

<div style ("width: 45%; min-width: 300px;">
<h3>Custom geofence screen</h3>
  <br>
<ul> 
  <li> Any user's real-time location check against pre-defined geofence boundary only with availability of 'latitude' and 'longitude' data. </li>
  <li> User real-time path trajectory track on OSM display with analytics. </li>
  <li> Real-time multiple user's location sharing and display on map (with user consent). </li> 
  <li> Access to versatile map tiles like satellite view, street view, etc. </li>
</ul> 
</div>

<div style ("width: 45%; min-width: 300px;">
<h3>Map screen</h3>
  <br>
<ul> 
  <li> OpenStreetMap display with location navigation. </li>
  <li> Capture coordinate ability by clicking on any location of map. </li>
  <li> Database within application for storing, copyieng and deletion of coordinates being captured. </li>
  <li> Access to versatile map tiles like satellite view, street view, etc. </li>
</ul> 
</div>

</div>
<br><br>

# FUTURE POTENTIAL <img src="j.png" width="40" align="left"/>
<br>

• Robust geofence setup: The system can inject any geofence boundary into the application. This opens the door for advanced use cases such as region-based workflows, restricted area based detection and customizable location rules. It makes the project highly flexible and adaptable to real-world scenarios.
&nbsp;&nbsp;

• Consent based multiple user tracking: With only after proper user consent, a single user can track the real-time locations of multiple users. This enables coordinated movement, team management and safety monitoring while ensuring privacyand user control remain a priority.
<br><br><br><br>

<div style=" 
  padding: 10px; 
  outline: 3px solid white;
  border-radius: 6px; 
  color: white; 
  background: transparent; 
  display: inline-block;">
  
  <u>FINAL NOTE</u> </div>
  
  <p> Thanks for reading! If you like this project please ⭐ the repo and feel to open issues or PRs. Suggestions are always welcome! </p>
