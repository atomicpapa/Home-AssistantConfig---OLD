<h1>AtomicPapa's Home Assistant Config</h1>

If you find my repo useful, please Star it!  :-)

Above are the various configuration files for my Home Assistant (HASS) setup.  Currently, HASS is running in Docker on a Dell i3 desktop computer with 8G of RAM and a 1TB HDD.  It's running Ubuntu Server 16.04 LTS.  Besides HASS, this server is also running:
<ul>
  <li>Docker, obviously</li>
  <li>Plex Media Server</li>
  <li>Sonarr</li>
  <li>Radarr</li>
  <li>NZBget</li> 
</ul>

In Docker I am currently running:
<ul>
  <li>Home Assistant></li>
  <li>Minecraft Server 1.12.2</li>
  <li>Mosquitto MQTT Broker</li>
  <li>Transmission</li>
  <li>Dasher</li>
</ul>
and slowly moving everything over.  I am using Docker Compose and Cockpit to manage my containers.

Hardware currently connected to HASS includes:

<ul>
  <li>Kindle Fire tablets for user interfaces (more on that in a bit)</li>
  <li>5 IP cameras (cheap, chinese clones)</li>
  <li>2 Google Homes</li>
  <li>2 Google Home Minis</li>
  <li>Phillips Hue Hub</li>
  <li>Broadlink RM Mini 3</li>
  <li>1 DIY ESP8266 Motion Sensor running ESPeasy</li>  
</ul>

Additions coming quickly will include:
<ul>
  <li>Door and Window Sensors</li>
  <li>WiFi controlled RGB LED strip lights inside and outside</li>
  <li>Skybell Video Doorbell or Doorbird</li>
  <li>Zmodo 8 Ch NVR with Cams to replace the cheap Chinese clones</li>

</ul>

<h3>Custom User Interface</h3>

I am using <a href="http://www.github.com/pkozul/ha-floorplan">Floorplan</a> to provide a custom interface for Home Assistant.  This allows me to design relevant screens for each room where I place one of the Kindle Fire's.  For example, in my son's room, by his light switch, I have mounted on the wall a 7" Kindle Fire that is running <a href="http://www.ozerov.de/fully-kiosk-browser/">Fully Kiosk Browser (FKB)</a>.  FKB not only allows interaction with Home Assistant, but also opens up the tablet's camera as a motion sensor and detects iBeacons for presence detection.


<img src="https://community-home-assistant-assets.s3-us-west-2.amazonaws.com/optimized/3X/0/d/0de34d4040f0da55647f852de41e0bc1786f4647_1_690x402.jpg">
