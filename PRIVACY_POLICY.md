# 12K Snow Privacy Policy

**Effective date:** [set on the day it is published]  
**App:** 12K Snow for Android (com.appodyssey.twelveksnow), including 12K Snow Pro  
**Developer:** App Odyssey  
**Contact:** app.odyssey.us@gmail.com

12K Snow shows snow forecasts, radar, snowpack and terrain maps for the places you ride. This policy explains what the app does and doesn't do with your information.

## The short version

- 12K Snow has no accounts, ads, analytics or tracking code. App Odyssey runs one small server, only to pass along public road reports, and it never receives your location, spots or rides.
- Your spots, settings and ride tracks are stored only on your phone. We never receive them.
- To get a forecast, your phone asks public weather and map services (such as the National Weather Service) directly for data about a place. That request includes the place's map coordinates.
- We don't sell or share your personal information.

## Information we collect
None. The app doesn't send your locations, spots, settings, ride tracks or usage to App Odyssey, so we have no copy of them. The only App Odyssey server the app contacts is the roads server described below, and it learns only which states' road reports to send.

## Information stored only on your device
The app keeps these in its private storage on your phone:

- **Your favorite spots:** the name and map coordinates of each spot you save (up to 30), and your order and alert choices for each.
- **Your settings:** units, ride mode, alert and quiet-hour settings, powder alarm time and amount, widget choices and map options.
- **Cached data:** recent forecasts, station readings and map pieces, so screens load quickly. They're refreshed or replaced over time.
- **Offline maps** (when that feature is available): map, terrain and forecast data for areas you choose to download.
- **Ride tracks** (when GPS ride tracking is available): the route, times, distance, speed and elevation of rides you choose to record.

You can delete spots and ride tracks in the app, clear the app's storage in Android settings, or uninstall the app to remove all of it. If Android backup is turned on, Android may include the app's settings and spots in your own device backup, which Google handles under your Google account settings. We can't see those backups.

## Location
12K Snow uses your phone's location only while you're using the app, and only for features you start:

- **"My location":** when you tap it to add a spot, the app asks Android for your approximate location once. The location becomes a spot only if you save it.
- **GPS ride tracking** (when available): when you tap Record, the app uses precise GPS to draw your route. Android shows an ongoing notification while recording, and recording stops when you tap Stop. Ride tracks are saved only on your phone, and the app never uploads your GPS position.
- **No background location:** the app doesn't request the "Allow all the time" location permission. Alerts, widgets and the powder alarm use the coordinates of your saved spots, not your current location.

Location is optional. You can add spots by search or by dropping a pin on the map instead. You can turn location access off at any time in Android settings.

On many phones, Android gets your location through Google Play services, under Google's own privacy policy.

## Notifications
If you turn on alerts or the powder alarm, the app asks for permission to show notifications. Alerts are created on your phone: about once an hour, the app checks the forecast and winter alerts for your saved spots and decides on the phone whether to notify you. Notifications aren't sent through any App Odyssey server.

## Where the app gets its data
Your phone requests data directly from these public services. Each request includes the map coordinates of a spot or map area, or the ID of a nearby weather station, along with your phone's IP address and a short app name tag, as any internet request does. These services have their own privacy policies. They're government or open-data services, not advertisers:

- National Weather Service and NOAA (api.weather.gov, digital.weather.gov, mapservices.weather.noaa.gov, opengeo.ncep.noaa.gov), including radar, snowfall and snowpack maps
- NOAA GOES lightning data, from NOAA's public cloud storage on Amazon Web Services
- USDA Natural Resources Conservation Service SNOTEL stations (wcc.sc.egov.usda.gov)
- U.S. Geological Survey elevation service (epqs.nationalmap.gov)
- Terrain map tiles (USGS elevation data) from the AWS Open Data program
- Iowa State University's Iowa Environmental Mesonet (mesonet.agron.iastate.edu), for forecast radar and weather station history
- OpenFreeMap (tiles.openfreemap.org), for the base map built from OpenStreetMap data
- avalanche.org, only when you tap a link to open it in your browser
- Caltrans (cwwp2.dot.ca.gov) and the Washington State DOT (wzdx.wsdot.wa.gov), for chain controls and work zones. These requests ask for a whole district or state, not a spot's coordinates.
- The 12K Snow roads server, run by App Odyssey on Cloudflare Workers (workers.dev), for road and pass reports. It collects public reports from state transportation departments (such as Caltrans, WSDOT, CDOT, ODOT and NDOT) every few minutes. The app asks it only for the states near a spot (for example “CO”), never for coordinates. The server keeps no request logs and doesn't store IP addresses. Cloudflare carries the connection under its own privacy policy.

When a ride is recorded or an offline area is downloaded, the app may request map pieces for that area. It doesn't send the track itself.

## Purchases
If you buy 12K Snow Pro, Google Play handles the payment. We don't receive your payment details. The app only learns whether Pro is active on your Google account.

## Data sale and sharing
We don't sell, rent or share your personal information, and we don't use it for advertising.

## Third-party code
The app is built with open-source libraries (Capacitor, MapLibre and Android Jetpack). It includes no advertising, analytics or crash-reporting code. Google Play may collect information when you download or update the app, under Google's own privacy policy.

## Children
12K Snow is intended for people 13 and older. It isn't directed at children under 13, and we don't knowingly collect personal information from anyone, including children.

## Security
All data requests use encrypted (HTTPS) connections. Data stored on your phone is protected by Android's app storage protections.

## Changes to this policy
If this policy changes, we'll post the updated version at this address and change the effective date above.

## Contact
Questions about this policy or the app: app.odyssey.us@gmail.com
