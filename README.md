
# List Widget – Interactive List Application

[![Flutter Version](https://img.shields.io/badge/Flutter-3.0+-blue.svg)](https://flutter.dev)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web%20%7C%20Desktop-brightgreen.svg)](https://flutter.dev)

A cross-platform **list management application** built with Flutter. Allows users to display, add, edit, or delete items in a scrollable list with smooth interactions.

---

## 🎯 Problem & Solution

**Problem**  
Many applications need to display collections of data (tasks, contacts, products) in an organized, scrollable manner. Implementing efficient, interactive lists from scratch on multiple platforms is time-consuming.

**Solution**  
This app provides a **reusable list widget** that:
- Runs on iOS, Android, Web, Windows, macOS, and Linux
- Offers smooth scrolling and item interactions
- Can be customized for various data types (text, images, checkboxes)
- Demonstrates Flutter's powerful `ListView` and `ListTile` widgets

---

## ✨ Key Features

- ✅ **Scrollable List** – Displays items in a vertical, scrollable layout
- ✅ **Interactive Items** – Tap, long-press, or swipe actions on list items
- ✅ **Dynamic Data** – Add, remove, or update items programmatically
- ✅ **Cross-Platform** – One codebase deploys to 6 platforms
- ✅ **Customizable UI** – Modify item design, colors, and fonts

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Framework | Flutter (Dart) |
| List Widget | `ListView.builder` / `ListTile` |
| Platforms | Android, iOS, Web, Windows, macOS, Linux |
| State Management | (not specified – likely `setState` or simple state) |

---

## 📦 Installation & Usage

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (stable channel)
- Android Studio / Xcode (for mobile) or Chrome (for web)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shahad142/list-widget.git
   cd list-widget
   ```

2. **Get dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

### Run on specific platforms

| Platform | Command |
|----------|---------|
| Android/iOS | `flutter run` |
| Web | `flutter run -d chrome` |
| Windows | `flutter run -d windows` |
| macOS | `flutter run -d macos` |
| Linux | `flutter run -d linux` |

---

## 📱 Usage Example

Once running, you will see a scrollable list similar to:

```
+----------------------+
| > Item 1             |
| > Item 2             |
| > Item 3             |
| > Item 4             |
| > Item 5             |
|                      |
| [ + Add New Item ]   |
+----------------------+
```

**Typical interactions:**
- **Tap** an item → Select or open details
- **Long press** → Delete or edit
- **Swipe** → Archive or remove

*Note: Exact behavior depends on the implementation in `/lib/main.dart`.*

---

## 📂 Project Structure

```
list-widget/
├── android/          # Android-specific files
├── ios/              # iOS-specific files
├── linux/            # Linux desktop support
├── macos/            # macOS desktop support
├── windows/          # Windows desktop support
├── web/              # Web platform files
├── lib/              # Main Dart source code
│   └── main.dart     # Entry point (currently default template)
├── test/             # Unit tests
├── fonts/            # Custom font files
├── pubspec.yaml      # Dependencies and asset declarations
└── README.md         # This file
```

---

## 🚀 Future Improvements

- [ ] Replace default counter app UI with actual list widget implementation
- [ ] Add persistent storage (SQLite, Hive, or SharedPreferences)
- [ ] Implement search and filter functionality
- [ ] Add drag-and-drop reordering of list items


---

## 📝 Notes

> **Important:** The repository currently contains the **default Flutter template** – you will need to modify `/lib/main.dart` to implement the list widget functionality.
>
> **Assets:** The `fonts/` folder is present for custom typography if needed.
>
> **Language:** Language breakdown shows C++/CMake due to Flutter's engine dependencies, but the app code is 100% Dart.
>
> **Naming:** The project name `list_widget` suggests the focus is on demonstrating Flutter's list capabilities.

---

## 👤 Maintainer

**SHAHAD KHUZAYYIM** – [@Shahad142](https://github.com/Shahad142)

---
