# Exploring Map Viewer 🗺️

A modern web application for visualizing fitness activity tracks (GPX and FIT files) on beautiful 3D terrain maps. Perfect for analyzing running routes, cycling paths, hiking trails, and other outdoor activities recorded on GPS devices.

## ✨ Key Features

- **Dual Format Support** - Load both GPX and FIT files (Garmin fitness devices)
- **3D Terrain Visualization** - Beautiful 3D terrain with Mapterhorn elevation data
- **OpenStreetMap Integration** - Map context layer
- **Multiple Tracks** - Load and compare multiple tracks simultaneously
- **Track Statistics** - Distance, elevation gain, min/max elevation, GPS points
- **Auto-Centering** - Map automatically fits to show all loaded tracks
- **Color-Coded Tracks** - Each track gets a unique color
- **Fully Commented Code** - Comprehensive inline documentation
- **Self-Contained** - Works offline after loading libraries

## 📋 Supported File Formats

### GPX (GPS Exchange Format)
Standard XML format supported by: Strava, Garmin Connect, Apple Maps, Komoot, AllTrails

### FIT (Flexible and Interoperable Data Transfer)
Binary format used by: Garmin watches, Garmin Edge, Garmin Fenix, Garmin Forerunner

## 🚀 Quick Start

1. **Download** `mapterhorn-viewer-v2.html`
2. **Open** in any modern web browser
3. **Select** GPX or FIT files
4. **Click** "Load GPX/FIT Files"
5. **Explore** your tracks on the 3D map!

## 🛠️ Technologies Used

- **MapLibre GL JS** - 3D map library
- **toGeoJSON** - GPX parsing
- **Mapterhorn** - Elevation tiles
- **OpenStreetMap** - Map tiles

## 📊 Calculated Statistics

- **Distance** - Haversine formula between GPS points
- **Elevation Gain** - Max elevation minus min elevation
- **GPS Points** - Total coordinates in track
- **Elevation Range** - Min and max altitude

## 🌍 Browser Support

✅ Chrome 90+  
✅ Firefox 88+  
✅ Safari 14+  
✅ Edge 90+

## 📝 Code Structure

**SimpleFitParser** - Custom FIT binary parser  
**Map Initialization** - MapLibre GL setup  
**Track Management** - Track loading and display  
**Statistics Engine** - Metric calculations  
**UI Controllers** - User interface updates  

## 🔐 Privacy

- ✅ All processing local in browser
- ✅ No data sent to servers
- ✅ Files never stored
- ✅ No tracking or cookies

## 📞 Support

- Check browser console (F12) for errors
- Read code comments for detailed explanations
- Test with sample files to verify functionality

## 🎉 Have Fun Exploring!

Whether tracking your morning run, cycling adventure, or hiking expedition, enjoy analyzing your activities on beautiful 3D terrain maps!

🏃‍♂️ 🚴‍♀️ 🥾 ⛰️
