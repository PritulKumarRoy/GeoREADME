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

<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 10px;">
  <span style="background: #2a2a2a; color: white; padding: 8px 15px; border-radius: 30px; font-size: 0.95rem;">🔲 Robust geofencing</span>
  <span style="background: #2a2a2a; color: white; padding: 8px 15px; border-radius: 30px; font-size: 0.95rem;">📍 Accurate real-time location</span>
  <span style="background: #2a2a2a; color: white; padding: 8px 15px; border-radius: 30px; font-size: 0.95rem;">👥 Location sharing (consent based)</span>
  <span style="background: #2a2a2a; color: white; padding: 8px 15px; border-radius: 30px; font-size: 0.95rem;">🗺️ OSM navigation & map tiles</span>
  <span style="background: #2a2a2a; color: white; padding: 8px 15px; border-radius: 30px; font-size: 0.95rem;">📸 Capture coordinates</span>
</div>
<br><br>

# PROBLEM STATEMENTS <img src="g.png" width="40" align="left"/>

1. Inaccurate reception of real-time location data.
2. Real-time location track of any user with explicit, informed and revocable consent.
3. Unavailability of an efficient mobile based system that can detect user location within predefined geographic areas while ensuring accuracy and low battery consumption.
4. OpenStreetMap lacks real-time path trajectory display based on user location data and capture coordinate ability.
<br><br>

# TECHNOLOGY STACK <img src="d.png" width="40" align="left"/>
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

# APPLICATION WORKING ARCHITECTURE <img src="c.png" width="40" align="left"/>
<br>

<p align="center"> <img src="h.png" height="100000" width="500"/> </p>
<br><br>

# MOBILE INTERFACES <img src="i.png" width="40" align="left"/>

<table style="width: 100%; border-collapse: collapse;"> 
  <tr valign="top">
    <td style="border: none; text-align: left; width: 50%; padding: 10px;">
      <h4>📱 Registration screen</h4>
      <img src="sa.png" style="width: 100%; max-width: 380px; border-radius: 20px; box-shadow: 0 8px 20px rgba(0,0,0,0.2);">
    </td>
    <td style="border: none; text-align: left; width: 50%; padding: 10px;">
      <h4>🔐 Login screen</h4>
      <img src="sb.png" style="width: 100%; max-width: 380px; border-radius: 20px; box-shadow: 0 8px 20px rgba(0,0,0,0.2);">
    </td>
  </tr>
  <tr valign="top">
    <td style="border: none; text-align: left; padding: 10px;">
      <h4>🏠 Home screen</h4>
      <img src="sc.png" style="width: 100%; max-width: 380px; border-radius: 20px; box-shadow: 0 8px 20px rgba(0,0,0,0.2);">
    </td>
    <td style="border: none; text-align: left; padding: 10px;">
      <h4>📍 Location tracking screen</h4>
      <img src="sd.png" style="width: 100%; max-width: 380px; border-radius: 20px; box-shadow: 0 8px 20px rgba(0,0,0,0.2);">
    </td>
  </tr>
  <tr valign="top">
    <td style="border: none; text-align: left; padding: 10px;">
      <h4>🚧 Custom geofence screen</h4>
      <img src="se.png" style="width: 100%; max-width: 380px; border-radius: 20px; box-shadow: 0 8px 20px rgba(0,0,0,0.2);">
    </td>
    <td style="border: none; text-align: left; padding: 10px;">
      <h4>🗺️ Map screen</h4>
      <img src="sf.png" style="width: 100%; max-width: 380px; border-radius: 20px; box-shadow: 0 8px 20px rgba(0,0,0,0.2);">
    </td>
  </tr>
</table>
<br><br>

# KEY FUNCTIONS <img src="e.png" width="40" align="left"/>
<br>

<div style="display: flex; flex-wrap: wrap; gap: 25px;">
  <div style="flex: 1 1 40%; min-width: 280px; background: #0d0d0d; padding: 18px 20px; border-radius: 24px; border-left: 5px solid #4a90e2;">
    <h3 style="margin-top: 0;">📝 Registration</h3>
    <ul style="padding-left: 20px;"> 
      <li>New user account registration</li>
      <li>Re-login for existing users</li>
      <li>Account deletion option</li> 
    </ul> 
  </div>

  <div style="flex: 1 1 40%; min-width: 280px; background: #0d0d0d; padding: 18px 20px; border-radius: 24px; border-left: 5px solid #e24a4a;">
    <h3 style="margin-top: 0;">🔑 Login</h3>
    <ul style="padding-left: 20px;"> 
      <li>Secure credential login</li>
      <li>Navigation to registration</li>
      <li>Access to home page</li> 
    </ul> 
  </div>

  <div style="flex: 1 1 40%; min-width: 280px; background: #0d0d0d; padding: 18px 20px; border-radius: 24px; border-left: 5px solid #42a85f;">
    <h3 style="margin-top: 0;">🏡 Home</h3>
    <ul style="padding-left: 20px;"> 
      <li>User profile display</li>
      <li>Three main feature buttons</li>
      <li>Logout access</li> 
    </ul> 
  </div>

  <div style="flex: 1 1 40%; min-width: 280px; background: #0d0d0d; padding: 18px 20px; border-radius: 24px; border-left: 5px solid #e2c14a;">
    <h3 style="margin-top: 0;">📍 Location Tracking</h3>
    <ul style="padding-left: 20px;"> 
      <li>Real-time location analytics</li>
      <li>Geofence check with fingerprint auth</li>
      <li>Instant notifications & Firebase sync</li>
      <li>Continuous location streaming</li>
    </ul> 
  </div>

  <div style="flex: 1 1 40%; min-width: 280px; background: #0d0d0d; padding: 18px 20px; border-radius: 24px; border-left: 5px solid #9b4ae2;">
    <h3 style="margin-top: 0;">🚧 Custom Geofence</h3>
    <ul style="padding-left: 20px;"> 
      <li>Location check via lat/long</li>
      <li>Real-time trajectory on OSM</li>
      <li>Multi-user location sharing (consent)</li> 
      <li>Satellite, street view tiles</li>
    </ul> 
  </div>

  <div style="flex: 1 1 40%; min-width: 280px; background: #0d0d0d; padding: 18px 20px; border-radius: 24px; border-left: 5px solid #e24a9b;">
    <h3 style="margin-top: 0;">🗺️ Map</h3>
    <ul style="padding-left: 20px;"> 
      <li>OSM with navigation</li>
      <li>Click-to-capture coordinates</li>
      <li>In-app coordinate database</li>
      <li>Multiple map tiles support</li>
    </ul> 
  </div>
</div>
<br><br>

# FUTURE POTENTIAL <img src="j.png" width="40" align="left"/>
<br>

<div style="display: flex; gap: 20px; flex-wrap: wrap;">
  <div style="flex: 1; min-width: 250px; background: linear-gradient(145deg, #1a1a1a, #0a0a0a); padding: 20px; border-radius: 20px;">
    <span style="font-size: 2rem;">📍</span>
    <h3>Robust geofence setup</h3>
    <p style="color: #ccc;">Inject any geofence boundary — enabling region-based workflows, restricted area detection, and fully customizable location rules.</p>
  </div>
  <div style="flex: 1; min-width: 250px; background: linear-gradient(145deg, #1a1a1a, #0a0a0a); padding: 20px; border-radius: 20px;">
    <span style="font-size: 2rem;">👥</span>
    <h3>Consent based multi-user tracking</h3>
    <p style="color: #ccc;">Track multiple users in real-time with explicit consent — perfect for team coordination, safety monitoring, and privacy-first design.</p>
  </div>
</div>
<br><br><br>

<div style=" 
  padding: 12px 28px; 
  outline: 3px solid #4a90e2;
  border-radius: 50px; 
  color: white; 
  background: transparent; 
  display: inline-block;
  font-weight: 600;
  letter-spacing: 1px;
  margin-bottom: 20px;">
  ⭐ FINAL NOTE 
</div>
  
<p style="font-size: 1.1rem; line-height: 1.6;"> Thanks for reading! If you like this project, please ⭐ the repo and feel free to open issues or PRs. Suggestions are always welcome! </p>
