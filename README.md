# Remora: The Past in Your Pocket

## Problem Statement
People capture countless photos and recordings, but these memories often get buried in phone galleries with no meaningful connection to the places where they were created.  
Existing online solutions are frequently data-heavy and inaccessible in areas with poor or no internet connectivity.  
There is currently no simple way for individuals to relive moments tied to specific real-world locations without scrolling endlessly through large media folders.

---

## Solution – Remora
**Remora** is an offline-first memory mapping application that enables users to attach memories (photos, audio, and notes) directly to real-world locations.

- Capture a picture or record an audio note within the app.  
- Automatically geotag content using GPS.  
- A built-in map displays small thumbnails (for images) or icons (for audio) at corresponding locations.  
- Users can zoom in/out of the map to explore their personal memory map.  
- Tap on a thumbnail to view the image or play the audio.  
- Works fully offline with data stored locally on the device.  

---

## Core Features

### 1. Capture Memories
- In-app camera for capturing photos and recording audio.  
- Automatic geotagging using device GPS.  

### 2. Map View
- Integration with **OpenStreetMap** (offline tiles).  
- Display of memories as thumbnails or icons at geotagged locations.  
- Zoom-based clustering/unclustering of nearby memories.  

### 3. Memory Playback
- Tap to view photos or play audio in fullscreen mode.  

### 4. Offline Storage
- Local storage of metadata using **SQLite** or **Hive**.  
- Files stored directly on device for complete offline access.  

---

## Technology Stack
- **Frontend:** Flutter or React Native  
- **Map:** OpenStreetMap (via `flutter_map` or `react-native-maps`)  
- **Storage:** SQLite / Hive (lightweight local database)  
- **Media:** Device camera & microphone APIs  
- **Geo-tagging:** Native device GPS (works offline)  

---

## Impact
- **For Users:** Provides a personal cultural diary to revisit places with emotional and contextual meaning, rather than browsing isolated media files.  
- **For Rural/Offline Areas:** Enables memory creation and preservation without reliance on internet connectivity.  
- **For Future Expansion:** Potential to sync with the cloud, evolving into a crowdsourced cultural archive.  

---
