# RTCS-Docs

Remote Traffic Camera Sensor Documentation

<img src="https://github.com/user-attachments/assets/b8054a3c-e638-4288-af88-839dbda3afae" height="300"/>

<img src="https://github.com/user-attachments/assets/70163436-da72-4f9b-b625-22c6db7bb2d1" height="300"/>

## Product Datasheet

<img src="https://github.com/user-attachments/assets/05e0eca2-cfee-4d59-b636-637af901935e" height="300" />

[AT-RTCS Datasheet.pdf](https://github.com/user-attachments/files/22426871/AT-RTCS.Datasheet.pdf)

## Configuration Tool

- Monitoring
  - Connections: Stores a connection list of RTCS devices
  - Camera Sessions: Reports the RTCS' active camera connections to aid in understanding if a camera is offline or unreachable
  - Tracked Objects: Near realtime live updating of tracked object identifier, speed, width (or length for vehicle side views), and classification
  - Detection Events: A listing of the detection events representing when an object has activated a camera zone or rule
  - Sample Periods:  Keeps the last 25 sample periods in memory for an easy recall of recent historical counts
  - Alerts: Detail of each session IDS alert call with attached images and videos (up to the last 50 attachments)
- Configuration
  - Firmware updates
  - Device IPv4 address management
  - Logging information for troubleshooting
  - Ping facility to diagnose connectivity
  - Service control and device rebooting for maintenance
  - Time server ocnfiguration
  - Camera outbound RTSP connection details
  - Zone (aka Lane) configuration
  - IDS alert server selection 

<img src="https://github.com/user-attachments/assets/eec5bfea-6ca3-463f-a432-a37cdd415d7d" height="300" />

[RTCSConfigSetup.msi](https://www.dropbox.com/scl/fi/ul40lld9a7q1e0uirmpiv/RTCSConfigSetup.msi?rlkey=t0fhptp5vu6zzzgcabzbh585w&dl=0)

