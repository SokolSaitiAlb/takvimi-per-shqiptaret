# Takvimi për Shqiptarët

<p align="center">
  <img src="app/src/main/res/mipmap-xxxhdpi/ic_launcher.webp" width="140" alt="Takvimi për Shqiptarët"/>
</p>

An open-source Islamic companion application built specifically for Albanian-speaking Muslims.

The app provides accurate prayer times, Quran, Qibla, Dhikr, Duas, Islamic Library, Hijri Calendar, Nearby Mosques, Halal Places and many other features in a modern Material 3 interface.

---

## Features

### Prayer Times

- Accurate daily prayer times
- Next prayer countdown
- Prayer notifications
- Prayer tracking
- Daily prayer completion
- Prayer streaks
- Monthly prayer statistics

---

### Quran

- Complete Quran
- Albanian translation
- Arabic text
- Search
- Bookmarks
- Continue reading
- Audio recitation

---

### Qibla

- Accurate Qibla direction
- Compass
- Distance calculation

---

### Dhikr

- Daily Dhikr
- Tasbih Counter
- Recommended Dhikr
- Progress tracking

---

### Islamic Library

- Prophets
- Sahabah
- Hadith Collections
- Duas
- Islamic Articles
- Islamic History
- Family Trees

---

### Hijri Calendar

- Islamic Calendar
- Prayer events
- Islamic holidays
- Ramadan support
- Moon phases
- Islamic history
- Hijri birthday converter

---

### Nearby Mosques & Halal Places

Powered by:

- MapLibre
- OpenStreetMap
- Overpass API
- Nominatim

Features:

- Nearby Mosques
- Halal Restaurants
- Halal Markets
- Islamic Centers
- Islamic Bookstores
- Radius Search
- Offline Cache
- Favorites
- Smart Ranking
- Navigation Chooser

---

## Open Source Stack

- Kotlin
- Jetpack Compose
- Material 3
- Room Database
- Kotlin Serialization
- Coroutines
- StateFlow
- MVVM
- Clean Architecture
- MapLibre Native
- OpenStreetMap
- Overpass API
- Nominatim

---

## Privacy

This application does **not** depend on Google Maps Platform.

Maps are powered entirely by:

- OpenStreetMap
- MapLibre
- Overpass API
- Nominatim

Location permission is used only to:

- calculate prayer times
- determine Qibla
- find nearby mosques
- locate halal places

Your location is never sold to third parties.

---

## Offline Support

The application works offline using:

- Local JSON datasets
- Room Database
- Offline mosque database
- Cached halal places
- Cached prayer times

---

## Supported Regions

- 🇽🇰 Kosovo
- 🇦🇱 Albania
- 🇲🇰 North Macedonia
- 🇲🇪 Montenegro
- 🇷🇸 Presheva Valley
- 🌍 Albanian Diaspora

---

## Architecture

```
Presentation (Compose UI)
        │
ViewModels
        │
Repositories
        │
Room Database
        │
OpenStreetMap Services
        │
MapLibre
```

---

## Requirements

- Android 8.0+
- Kotlin
- Gradle
- Android Studio

---

## License

This project is released under the MIT License.

---

## Acknowledgements

- OpenStreetMap Contributors
- MapLibre Community
- Overpass API
- Nominatim
- Android Open Source Project

---

Made with ❤️ for Albanian Muslims.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
