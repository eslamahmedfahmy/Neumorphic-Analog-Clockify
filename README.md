# Neumorphic TimeKit

An alarm, analog clock and stopwatch app with a neumorphic design, built with Flutter.

## Features

- Alarm system with custom audio
- Analog clock with neumorphic styling
- Stopwatch
- Splash screen and bottom navigation
- Alarms stored locally with SQLite

(TODO: add screenshots or a short GIF.)

## Tech stack

| Area | Technology |
| --- | --- |
| Framework | Flutter, Dart |
| State management | Bloc (MVVM-style `view` / `view_model` / `model`) |
| UI | flutter_neumorphic, analog_clock, google_nav_bar, flutter_svg |
| Storage | sqflite, path_provider |
| Alarms | alarm package |

## Project structure

```
lib/
├── model/
├── res/
├── services/
├── view/        # alarm, clock, stopwatch, home, splash
└── view_model/
```

## Getting started

```bash
git clone https://github.com/eslamahmedfahmy/Neumorphic-Analog-Clockify.git
cd Neumorphic-Analog-Clockify
flutter pub get
flutter run
```

## Author

**Eslam Fahmy** · [LinkedIn](https://www.linkedin.com/in/eslam-ahmed-fahmy-340220202)
