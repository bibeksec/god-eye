# 🇳🇵 GOD'S-EYE NEPAL — by bibeksec

Nepal-only cyber + airspace situational awareness dashboard on MapLibre GL.

> ⚠️ Cyber/device/traffic data is **simulated** unless you connect your own feed. Aircraft positions are **real, public ADS-B data** from the OpenSky Network. Fleet/vehicle positions are **simulated** — wire in your own GPS feed for real tracking. Province outlines are **approximate**. This project does not and will not do public vehicle or camera surveillance.

## Features
- Real 3D terrain (AWS open elevation tiles) + sky, 3D OSM buildings (OpenFreeMap, no API key)
- Live aircraft over Nepal from OpenSky Network's public API
- Your-own-fleet vehicle layer (simulated demo movement; swap in your real GPS feed)
- Province-filtered heatmap, animated threat arcs/pulses
- Device manager (watch/tag/isolate) for assets you own or administer
- Traffic analyzer: throughput, top talkers, protocol/port mix, spike + port-scan detection
- Import flow files, optional live WebSocket feed

## Run locally
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Responsible use
Only monitor devices, vehicles, and traffic you are authorized to monitor. Aircraft data is already public (ADS-B); this app does not add any new surveillance capability for aircraft, vehicles, or people.

## License
MIT
