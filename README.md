# NomMetric
A Flutter-based mess tracking app designed for college use, enabling students to track meals across multiple messes, developed for OpenCode’25.

## Quick Start
Ready to contribute? Check out our [Contributing Guide](Contributing.md). It covers everything you need to know about setting up the project, claiming issues, and submitting pull requests for OpenCode'25.

### Prerequisites
Before you begin working on this project, ensure your environment meets the following requirements.

#### Core Tooling
- **Flutter SDK**: `^3.27.0`
- **Dart SDK**: `3.6.0` (bundled with Flutter 3.27.x)
- **Android SDK**:
  - **Compile SDK / Target SDK**: `API level 35` (Android 15)
- **Java Development Kit (JDK)**: `17` or `21`  
  JDK 17 is recommended for maximum compatibility with Android tooling.

#### Required Flutter Packages

Add the following dependencies to your `pubspec.yaml`.
- **flutter_riverpod**: `^2.5.1`  
  https://pub.dev/packages/flutter_riverpod

- **firebase_core**: `^3.6.0`  
  https://pub.dev/packages/firebase_core

- **cloud_firestore**: `^5.4.0`  
  https://pub.dev/packages/cloud_firestore

- **go_router**: `^14.2.0`  
  https://pub.dev/packages/go_router

### Notes
- Ensure `compileSdkVersion` and `targetSdkVersion` are set to `35`.
- Run `flutter doctor` to verify that all dependencies are correctly installed.
- Firebase projects should be configured to support Android 15.

Try checking out [contributing guide](Contributing.md) for further help.

## Setting up
1. Clone the repo
``` md
git clone https://github.com/opencodeiiita/NomMetric.git
cd NomMetric
```

2. Link the repository to your Firebase project using the application ID defined in `android/app/build.gradle`.


## Project Structure
```text
NomMetric/
├── android/           # Android native configurations
├── ios/               # iOS native configurations
├── web/               # Web platform support
├── assets/            # Images, fonts, and local data files
├── lib/               # Primary application code
│   ├── screens/       # Full-page UI components
│   ├── widgets/       # Reusable UI elements
│   ├── services/      # Logic for Firebase, Firestore, and APIs
│   ├── models/        # Data structures; (User, Meal, Rating objects)
│   ├── provider/     # State management logic (Riverpod)
├── contributors.md    # Registration file for participants
└── pubspec.yaml       # Project dependencies and configuration
```

## Contributing

We welcome contributions as part of OpenCode’25.

- Browse the repository issues and pick one that matches your interest and skill level.
- Issues may be:
  - **Open-for-all (OFA)**: No claiming required; anyone can submit a PR.
  - **Competitive**: Multiple submissions allowed; the best PR is accepted.
  - **First-come**: Must be claimed before working on it and has a time limit.

To contribute:
1. Fork the repository and create a new branch.
2. Make your changes following the project guidelines.
3. Add your details to [contributors.md](contributors.md).
4. Open a pull request with a clear title and link it to the relevant issue.

For detailed rules, issue claiming process, and PR requirements, refer to  
[Contributing.md](Contributing.md).


## Contact

If you have any questions, run into issues while setting up, or need clarification on contributions, feel free to reach out.

- **Discord**: `VirtualVard`

You can also contact me for reporting bugs, feature requests, or suggestions about this repository.

---

Happy contributing, and welcome to NomMetric!
