<div align="center">

# CoMusic

### What if Apple had designed Instagram — for music? 🎧

CoMusic is a conceptual redesign of Instagram reimagined as a music app, built from scratch
in SwiftUI as a hands-on study of Apple's **Human Interface Guidelines**: feed, search,
reels and profile, rebuilt around music discovery and sharing.

<br/>

[![Platform](https://img.shields.io/badge/iOS-SwiftUI-000000?style=for-the-badge&logo=apple&logoColor=white)](https://www.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-5-FA7343?style=for-the-badge&logo=swift&logoColor=white)](https://swift.org)
[![SwiftUI](https://img.shields.io/badge/SwiftUI-0052CC?style=for-the-badge&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![License](https://img.shields.io/badge/License-MIT-3DA639?style=for-the-badge)](LICENSE)

</div>

---

## 📑 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Design Approach](#-design-approach)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Authors](#-authors)
- [License](#-license)

---

## 📖 About

CoMusic started as a study exercise: learning Apple's design guidelines in depth by
applying them to a real case. We took Instagram's interface and rebuilt it from scratch in
SwiftUI, turning it into an app for music discovery, sharing and curation, and aligning
every visual and interaction decision with the HIG — hierarchy, navigation, typography,
spacing, gestures and native iOS patterns.

The project set out to answer two questions:

- What would Instagram look like if it had been designed **by Apple**, strictly following the HIG?
- How do you adapt that same structure to a different purpose — **music** instead of generic photos and videos?

---

## 🚀 Features

- **🏠 Home** — a feed of music posts with a horizontal, story-style row at the top.
- **🔎 Search** — music discovery through an image-based explore layout.
- **🎬 Clips** — short-form vertical content in a music context, with author info.
- **👤 Profile** — profile header, information and a segmented picker for the user's content.

---

## 🎨 Design Approach

The app mirrors — and rethinks — Instagram's classic sections, applying native iOS
conventions throughout instead of custom chrome. The `Profile`, `Profile2` and `Profile3`
folders keep the alternative profile designs explored during the redesign, so the
iterations can be compared side by side.

---

## 🛠️ Tech Stack

| Area | Tech |
|------|------|
| UI | SwiftUI |
| Design reference | Apple Human Interface Guidelines |

---

## 📂 Project Structure

```
CoMusic/
├── CoMusicApp.swift            # App entry
├── Home/                       # Feed, posts, navigation bar
├── Search/                     # Explore layout
├── Reels/                      # Short-form content
├── Picker/                     # Profile content picker
├── Profile/ Profile2/ Profile3/  # Profile design iterations
└── Assets.xcassets/            # Images, icons, colors
```

---

## 🎯 Getting Started

### Requirements

- Xcode 16+

### Run

This repository contains the app's source code and assets, but no `.xcodeproj` file. To run it:

1. Clone the repository:
   ```bash
   git clone https://github.com/JonasFNMelo/CoMusic.git
   ```
2. In Xcode, create a new **iOS › App** project named `CoMusic` with the **SwiftUI** interface.
3. Delete the template's `ContentView.swift`, `CoMusicApp.swift` and `Assets.xcassets`.
4. Drag the repository's contents into the project (check *Copy items if needed* and *Create groups*).
5. Pick an iPhone simulator and run (`⌘R`).

---

## 👥 Authors

<table width="100%">
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/JonasFNMelo"><img src="https://github.com/JonasFNMelo.png" width="80" alt="Jonas Melo"/></a>
      <br/><sub><b>Jonas Melo</b></sub><br/>
      <a href="https://github.com/JonasFNMelo"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
      <a href="https://www.linkedin.com/in/jonas-melo-/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
    </td>
    <td align="center" width="50%">
      <br/><sub><b>Miqueias Saldanha</b></sub><br/>
    </td>
  </tr>
</table>

---

## 📄 License

Released under the [MIT License](LICENSE).
