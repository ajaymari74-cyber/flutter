# 🚀 30 Days Flutter Development: Zero to Hero (2026 Edition)
> **Master Flutter & Dart from absolute beginner to professional developer in 30 days.**
> *Updated for Flutter 3.24+ | Dart 3.5+ | 2026 Best Practices*

---

## 📋 Table of Contents
- [Week 1: Dart Foundation & Flutter Setup](#week-1-dart-foundation--flutter-setup)
- [Week 2: UI Mastery & Core Widgets](#week-2-ui-mastery--core-widgets)
- [Week 3: State Management & App Architecture](#week-3-state-management--app-architecture)
- [Week 4: Advanced Flutter & Production](#week-4-advanced-flutter--production)
- [Capstone Projects](#capstone-projects)
- [Resources & Tools](#resources--tools)

---

## 🗓️ Week 1: Dart Foundation & Flutter Setup

### Day 1: Environment Setup & Hello Flutter
**Goal:** Get your development environment ready and run your first app.

- Install Flutter SDK (latest stable)
- Setup Android Studio / VS Code with Flutter & Dart extensions
- Configure Android Emulator & iOS Simulator
- Run `flutter doctor` and fix all issues
- Create your first app: `flutter create hello_world`
- Understand project structure (`lib/`, `android/`, `ios/`, `pubspec.yaml`)
- **Concepts:** Hot Reload, Hot Restart, Widget Tree
- **Practice:** Modify the default counter app — change colors, text, and increment value

### Day 2: Dart Basics — Variables, Types & Control Flow
**Goal:** Learn Dart programming fundamentals.

- Variables: `var`, `final`, `const`, `late`
- Data Types: `int`, `double`, `String`, `bool`, `List`, `Map`, `Set`
- Null Safety (`?`, `!`, `??`, `??=`)
- Operators: Arithmetic, Logical, Ternary, Cascade (`..`)
- Control Flow: `if/else`, `switch/case`, `for`, `while`, `do-while`
- **Practice:** Build a console calculator and a number guessing game

### Day 3: Dart Functions & OOP Basics
**Goal:** Master functions and object-oriented programming in Dart.

- Functions: Named, Anonymous, Arrow, Optional & Named Parameters
- Higher-Order Functions & Closures
- Classes & Objects
- Constructors: Default, Named, Factory, Const
- `this` keyword and initializer lists
- **Practice:** Create a `BankAccount` class with deposit/withdraw methods

### Day 4: Dart OOP Advanced
**Goal:** Deep dive into advanced OOP concepts.

- Inheritance & `extends`
- Method Overriding
- Abstract Classes & Interfaces (`implements`)
- Mixins (`with`)
- `super` keyword
- Extension Methods
- Generics (`<T>`)
- Enums (Enhanced Enums in Dart 3)
- **Practice:** Build a `Shape` hierarchy (Circle, Rectangle, Triangle) with area calculation

### Day 5: Dart Advanced — Async, Collections & Functional Programming
**Goal:** Master asynchronous programming and functional patterns.

- `Future`, `async`, `await`
- `Stream`, `StreamBuilder` basics
- Error Handling: `try/catch/finally`, `on`, `rethrow`
- Collections: `List`, `Map`, `Set` operations (`map()`, `where()`, `reduce()`, `fold()`)
- Records & Patterns (Dart 3)
- `switch` expressions (Dart 3)
- **Practice:** Fetch mock JSON data asynchronously and parse it into model classes

**Week 1 Project:** 🎯 **Console Quiz App** — A terminal-based quiz with OOP design, async timers, and score tracking.

---

## 🗓️ Week 2: UI Mastery & Core Widgets

### Day 6: Flutter Widgets Fundamentals
**Goal:** Understand the widget system and build basic layouts.

- Everything is a Widget philosophy
- StatelessWidget vs StatefulWidget
- BuildContext explained
- Key types: `ValueKey`, `GlobalKey`
- Basic widgets: `Text`, `Container`, `Row`, `Column`, `Stack`, `Expanded`, `Flexible`
- **Practice:** Build a business card UI

### Day 7: Layouts & Constraints
**Goal:** Master Flutter's layout system.

- Box Constraints (tight vs loose)
- `ConstrainedBox`, `SizedBox`, `AspectRatio`
- `SingleChildScrollView` & scrolling physics
- `ListView`, `ListView.builder`, `ListView.separated`
- `GridView`, `GridView.builder`
- `PageView` & `TabBarView`
- **Practice:** Build a photo gallery app with grid and list views

### Day 8: Input, Forms & Validation
**Goal:** Handle user input professionally.

- `TextField`, `TextFormField`
- TextEditingController
- InputDecoration, FocusNode
- Form widget & GlobalKey<FormState>
- Validation logic
- Keyboard types & actions
- **Practice:** Build a registration form with validation (name, email, password, phone)

### Day 9: Navigation & Routing
**Goal:** Implement multi-screen apps.

- Navigator 1.0: `push`, `pop`, `pushNamed`, `pushReplacement`
- Passing data between screens
- Named Routes & `onGenerateRoute`
- Arguments & Result callbacks
- Navigation 2.0 / Router API (Declarative)
- Deep Linking basics
- **Practice:** Build a multi-screen e-commerce product browsing app

### Day 10: Theming, Assets & Responsive Design
**Goal:** Make apps beautiful and adaptive.

- `ThemeData`, `ColorScheme`, `TextTheme`
- Dark Mode implementation
- Custom fonts & Google Fonts
- Images: AssetImage, NetworkImage, CachedNetworkImage
- SVG support (`flutter_svg`)
- Responsive design: `LayoutBuilder`, `MediaQuery`, `OrientationBuilder`
- `flutter_screenutil` or responsive frameworks
- **Practice:** Redesign your Day 6-9 apps with a cohesive theme and responsive layout

**Week 2 Project:** 🎯 **News Reader App** — Fetch static news data, display in list/grid, detail screen with hero animations, dark mode toggle, and responsive layout.

---

## 🗓️ Week 3: State Management & App Architecture

### Day 11: State Management — setState & InheritedWidget
**Goal:** Understand state management fundamentals.

- Ephemeral vs App State
- `setState` and when NOT to use it
- `InheritedWidget` & `InheritedModel`
- `ValueNotifier` & `ValueListenableBuilder`
- `ChangeNotifier` basics
- **Practice:** Build a simple todo app with ValueNotifier

### Day 12: State Management — Provider
**Goal:** Master the most popular state management solution.

- `ChangeNotifierProvider`, `Consumer`, `Selector`
- `MultiProvider`
- `FutureProvider`, `StreamProvider`
- Dependency injection with Provider
- **Practice:** Refactor the todo app with Provider; add categories and filters

### Day 13: State Management — Riverpod
**Goal:** Learn the modern, compile-safe state management.

- `StateProvider`, `StateNotifierProvider`, `FutureProvider`, `StreamProvider`
- `ConsumerWidget`, `ConsumerStatefulWidget`
- `ref.watch`, `ref.read`, `ref.listen`
- `AsyncValue` handling
- Riverpod Generator & `@riverpod` annotations
- **Practice:** Build a weather app with Riverpod and OpenWeatherMap API

### Day 14: State Management — BLoC Pattern
**Goal:** Understand business logic component architecture.

- Events, States, Blocs
- `flutter_bloc` package
- `BlocBuilder`, `BlocListener`, `BlocConsumer`
- `Cubit` vs `Bloc`
- HydratedBloc for persistence
- **Practice:** Build a counter app and a login flow with BLoC

### Day 15: Local Data Persistence
**Goal:** Store data locally on device.

- `SharedPreferences` for simple key-value storage
- `sqflite` for SQLite database
- `hive` for fast NoSQL storage
- `path_provider` for file system access
- `drift` (moor) for type-safe SQLite
- **Practice:** Build an offline-first notes app with categories, search, and CRUD operations

**Week 3 Project:** 🎯 **Expense Tracker** — Full-featured app with Riverpod/BLoC, local persistence (Hive/SQLite), charts, categories, and monthly reports.

---

## 🗓️ Week 4: Advanced Flutter & Production

### Day 16: Networking & APIs
**Goal:** Connect your app to the internet.

- `http` package vs `dio`
- REST API integration
- JSON parsing: Manual vs `json_serializable`
- Freezed for immutable data classes
- Error handling & retry logic
- Interceptors (Dio)
- **Practice:** Build a GitHub user search app with pagination and error states

### Day 17: Authentication & Security
**Goal:** Implement secure user authentication.

- Firebase Authentication (Email, Google, Apple)
- JWT token management
- Secure storage (`flutter_secure_storage`)
- Biometric authentication (`local_auth`)
- OAuth 2.0 flow
- **Practice:** Add authentication to your Expense Tracker app

### Day 18: Animations
**Goal:** Create delightful user experiences.

- Implicit animations: `AnimatedContainer`, `AnimatedOpacity`, `AnimatedCrossFade`
- Explicit animations: `AnimationController`, `Tween`, `CurvedAnimation`
- `Hero` animations for transitions
- `AnimatedBuilder` & `AnimatedWidget`
- Staggered animations
- Rive & Lottie for complex animations
- **Practice:** Add micro-interactions and page transitions to your apps

### Day 19: Custom Painter, RenderObjects & Advanced UI
**Goal:** Build custom UI components from scratch.

- `CustomPaint` & `CustomPainter`
- Canvas, Paint, Path
- ClipPath & custom clipping
- `Slivers`: `SliverAppBar`, `SliverList`, `SliverGrid`, `SliverToBoxAdapter`
- `CustomScrollView`
- `RenderBox` basics (optional advanced)
- **Practice:** Build a custom chart widget and a circular progress indicator

### Day 20: Native Features & Platform Channels
**Goal:** Access device hardware and native capabilities.

- Camera & Image Picker (`image_picker`)
- File Picker & Document handling
- Geolocation & Maps (`google_maps_flutter`)
- Local Notifications (`flutter_local_notifications`)
- Sensors & Hardware
- Platform Channels (MethodChannel, EventChannel)
- **Practice:** Build a location-based photo journal app

### Day 21: Testing
**Goal:** Write robust, testable code.

- Unit testing with `test` package
- Widget testing with `flutter_test`
- Integration testing (`integration_test`)
- Mocking with `mockito` / `mocktail`
- Golden tests for UI regression
- Code coverage
- **Practice:** Write comprehensive tests for your Expense Tracker app

### Day 22: Architecture & Clean Code
**Goal:** Build production-ready, scalable apps.

- Clean Architecture layers (Presentation, Domain, Data)
- Repository Pattern
- Dependency Injection (`get_it`, `injectable`)
- SOLID principles in Flutter
- Feature-first vs Layer-first folder structure
- **Practice:** Refactor an existing app to Clean Architecture

### Day 23: Performance Optimization
**Goal:** Make apps fast and smooth.

- Widget rebuild optimization (`const`, `RepaintBoundary`)
- Image optimization & caching
- List virtualization (`ListView.builder`)
- Isolates for heavy computation
- DevTools: Performance, Memory, Network profiling
- Shader compilation jank & SkSL warmup
- App size optimization
- **Practice:** Profile and optimize your heaviest app

### Day 24: Internationalization & Accessibility
**Goal:** Make apps global and inclusive.

- `flutter_localizations` & `intl`
- ARB files & code generation
- RTL support
- Accessibility: screen readers, semantics, contrast
- Dynamic text scaling
- **Practice:** Add 3 language support to your app with full RTL testing

### Day 25: Background Processing & Advanced Features
**Goal:** Handle complex background tasks.

- `workmanager` for background tasks
- Firebase Cloud Messaging (Push Notifications)
- Background location tracking
- Audio/Video playback (`just_audio`, `video_player`)
- WebSocket connections
- GraphQL with `graphql_flutter`
- **Practice:** Build a chat app with WebSocket and push notifications

### Day 26: Flutter Web & Desktop
**Goal:** Target multiple platforms.

- Flutter Web: constraints, routing, SEO considerations
- Flutter Desktop (Windows, macOS, Linux)
- Platform-specific UI adaptations
- Conditional imports for platform-specific code
- Responsive web layouts
- **Practice:** Port your Expense Tracker to Web and Desktop

### Day 27: CI/CD & DevOps
**Goal:** Automate build and deployment.

- GitHub Actions for Flutter CI/CD
- Fastlane for automated deployment
- Codemagic & Bitrise overview
- App signing (Android Keystore, iOS Certificates)
- Automated testing in CI pipeline
- **Practice:** Setup CI/CD pipeline for your project

### Day 28: App Store & Play Store Deployment
**Goal:** Publish your app to stores.

- App Store Connect & Google Play Console
- App Store Review Guidelines
- Screenshots, descriptions, metadata
- App signing and release builds
- App Bundle (AAB) vs APK
- In-App Purchases & Subscriptions setup
- **Practice:** Prepare your capstone project for store submission

### Day 29: Capstone Project — Part 1
**Goal:** Build a production-grade application.

**Project: Social Fitness Tracker**
- User authentication (Firebase Auth)
- Activity tracking with GPS
- Photo sharing with camera
- Social feed with likes/comments
- Push notifications
- Offline support with sync
- Clean Architecture + Riverpod/BLoC

### Day 30: Capstone Project — Part 2 & Portfolio
**Goal:** Complete and polish your app.

- Complete remaining features
- Add comprehensive testing
- Performance optimization
- Accessibility audit
- Prepare app store assets
- Write README and documentation
- Deploy to stores or GitHub
- **Portfolio:** Document your journey, create a GitHub portfolio with all 30 days

---

## 🏆 Capstone Projects (By Difficulty)

### Beginner
1. **Personal Expense Tracker** — CRUD, local storage, basic charts
2. **Weather App** — API integration, location, beautiful UI
3. **Todo Manager** — Categories, priorities, reminders

### Intermediate
4. **E-Commerce App** — Product catalog, cart, checkout flow
5. **News Aggregator** — Multiple sources, bookmarks, offline reading
6. **Chat Application** — Real-time messaging, push notifications

### Advanced
7. **Fitness Tracker** — GPS, health data, social features
8. **Video Streaming App** — Custom player, playlists, downloads
9. **FinTech App** — Transactions, charts, biometric auth, security

---

## 📚 Resources & Tools

### Essential Packages (2026)
| Category | Packages |
|----------|----------|
| State Management | `flutter_riverpod`, `bloc`, `provider` |
| Networking | `dio`, `http`, `retrofit`, `graphql_flutter` |
| Local Storage | `hive`, `sqflite`, `shared_preferences`, `flutter_secure_storage` |
| UI Components | `flutter_screenutil`, `shimmer`, `flutter_slidable`, `flutter_staggered_grid_view` |
| Images & Media | `cached_network_image`, `image_picker`, `photo_view`, `flutter_svg` |
| Maps & Location | `google_maps_flutter`, `geolocator`, `flutter_polyline_points` |
| Notifications | `flutter_local_notifications`, `firebase_messaging` |
| Testing | `mocktail`, `bloc_test`, `golden_toolkit` |
| Code Generation | `freezed`, `json_serializable`, `injectable`, `riverpod_generator` |

### Learning Resources
- **Official:** [Flutter Documentation](https://docs.flutter.dev), [Dart Documentation](https://dart.dev)
- **YouTube:** Flutter Official, The Flutter Way, Mitch Koko, Andrea Bizzotto
- **Books:** "Flutter Complete Reference" — Alberto Miola
- **Practice:** FlutterFlow (visual), DartPad, Zapp.run

### Tools
- **IDE:** VS Code / Android Studio
- **Design:** Figma with Flutter plugins
- **API Testing:** Postman / Insomnia
- **State Inspection:** Redux DevTools (for BLoC), Riverpod DevTools
- **CI/CD:** Codemagic, GitHub Actions, Fastlane

---

## ✅ Daily Checklist Template
```
Day ___: [Topic]
□ Read/watch theory (1-2 hours)
□ Code along with examples (1-2 hours)
□ Build practice project (2-3 hours)
□ Push code to GitHub
□ Write 3 key learnings in notes
□ Complete daily challenge
```

## 🎯 Success Metrics
By Day 30, you should be able to:
- ✅ Build any UI from a Figma design
- ✅ Architect apps using Clean Architecture
- ✅ Choose and implement appropriate state management
- ✅ Write testable, maintainable code
- ✅ Connect to REST/GraphQL APIs securely
- ✅ Handle authentication and local persistence
- ✅ Optimize app performance
- ✅ Deploy to App Store & Play Store
- ✅ Debug and profile like a pro

---

> 💡 **Pro Tip:** Consistency beats intensity. Code every single day, even if just for 1 hour. Build in public, share your progress, and don't skip the fundamentals!

**Happy Fluttering! 🦋**


# 📘 Day 1: Environment Setup & Hello Flutter — Complete Deep Dive
> **Goal:** Get your development environment ready and run your first app like a pro.
> *This guide covers every concept, command, and file you'll encounter on Day 1.*

---

## Table of Contents
1. [What is Flutter? Why Flutter in 2026?](#1-what-is-flutter-why-flutter-in-2026)
2. [System Requirements](#2-system-requirements)
3. [Installing Flutter SDK](#3-installing-flutter-sdk)
4. [IDE Setup: VS Code vs Android Studio](#4-ide-setup-vs-code-vs-android-studio)
5. [Configuring Emulators & Simulators](#5-configuring-emulators--simulators)
6. [The `flutter doctor` Command](#6-the-flutter-doctor-command)
7. [Creating Your First App](#7-creating-your-first-app)
8. [Understanding Project Structure](#8-understanding-project-structure)
9. [Core Concepts: Hot Reload, Hot Restart & Widget Tree](#9-core-concepts-hot-reload-hot-restart--widget-tree)
10. [Hands-On: Modify the Counter App](#10-hands-on-modify-the-counter-app)
11. [Common Issues & Fixes](#11-common-issues--fixes)
12. [Day 1 Checklist](#12-day-1-checklist)

---

## 1. What is Flutter? Why Flutter in 2026?

### What is Flutter?
Flutter is an **open-source UI toolkit** developed by Google for building beautiful, natively compiled applications for:
- 📱 Mobile (iOS & Android)
- 🌐 Web
- 💻 Desktop (Windows, macOS, Linux)
- 🖥️ Embedded devices

You write code **once** in **Dart** and deploy **everywhere**.

### Why Flutter in 2026?
| Advantage | Explanation |
|-----------|-------------|
| **Single Codebase** | One Dart codebase runs on 6+ platforms |
| **Hot Reload** | See code changes instantly without losing app state |
| **Custom Rendering** | Flutter draws every pixel using Skia/Impeller — no native UI components needed |
| **Rich Widgets** | Hundreds of pre-built, customizable widgets |
| **Strong Community** | Massive package ecosystem (pub.dev), active community |
| **Performance** | 60-120 FPS smooth animations, compiled to native ARM code |
| **Google Backing** | Used by Google Ads, Google Pay, Stadia, and thousands of companies |

> 💡 **2026 Update:** Flutter now uses **Impeller** as the default rendering engine on iOS, delivering significantly better performance and reduced shader compilation jank compared to the old Skia backend.

---

## 2. System Requirements

### Minimum Requirements
| Component | Windows | macOS | Linux |
|-----------|---------|-------|-------|
| **OS** | Windows 10 or later (64-bit) | macOS 10.14 (Mojave) or later | 64-bit Linux distribution |
| **Disk Space** | 2.5 GB (excluding IDE/tools) | 2.8 GB (excluding IDE/tools) | 600 MB (excluding IDE/tools) |
| **RAM** | 8 GB minimum, **16 GB recommended** | 8 GB minimum, **16 GB recommended** | 8 GB minimum, **16 GB recommended** |
| **Tools** | Git for Windows | Git, Xcode (for iOS) | Git, curl, unzip |

> ⚠️ **Important:** For iOS development, you **must** use macOS. Windows/Linux cannot build iOS apps.

---

## 3. Installing Flutter SDK

### Step 1: Download Flutter
Go to the official Flutter website and download the latest stable release:
🔗 https://docs.flutter.dev/get-started/install

Or use command line:

**macOS/Linux:**
```bash
cd ~/development
wget https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_3.24.0-stable.zip
unzip flutter_macos_3.24.0-stable.zip
```

**Windows:**
Download the zip file and extract it to `C:\flutter`

### Step 2: Add Flutter to PATH

**macOS/Linux (add to `~/.zshrc` or `~/.bash_profile`):**
```bash
export PATH="$HOME/development/flutter/bin:$PATH"
```
Then reload:
```bash
source ~/.zshrc
```

**Windows:**
1. Search for "Environment Variables" in Start Menu
2. Click "Edit the system environment variables"
3. Click "Environment Variables"
4. Under "User variables", find `Path` → Edit → New
5. Add: `C:\flutter\bin`
6. Click OK on all dialogs

### Step 3: Verify Installation
```bash
flutter --version
```

**Expected output:**
```
Flutter 3.24.0 • channel stable • https://github.com/flutter/flutter.git
Framework • revision ...
Engine • revision ...
Tools • Dart 3.5.0 • DevTools 2.37.0
```

> 🎯 **What you learned:** The Flutter SDK contains the Dart compiler, Flutter framework, command-line tools, and the `flutter` CLI. The `bin` folder contains the executable commands.

---

## 4. IDE Setup: VS Code vs Android Studio

You can use either. Here's a comparison:

| Feature | VS Code | Android Studio |
|---------|---------|----------------|
| **Speed** | Lightweight, fast | Heavier, more resource usage |
| **Flutter Support** | Excellent (via extensions) | Built-in, officially maintained |
| **Android Emulator** | Can launch via command | Built-in emulator manager |
| **iOS Simulator** | Can launch via command | Can launch via command |
| **Debugging** | Good DevTools integration | Excellent built-in debugger |
| **Best For** | All platforms, quick edits | Heavy Android development |

### VS Code Setup (Recommended for beginners)

1. Install VS Code: https://code.visualstudio.com/
2. Open VS Code → Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search and install:
   - **Flutter** (by Dart Code) — installs Dart extension automatically
   - **Awesome Flutter Snippets** (optional but helpful)
   - **Flutter Tree** (optional, for widget tree visualization)

4. Verify: Open Command Palette (Ctrl+Shift+P / Cmd+Shift+P) → type "Flutter" → you should see Flutter commands

### Android Studio Setup

1. Download Android Studio: https://developer.android.com/studio
2. Install with "Android Virtual Device" checked
3. Open Android Studio → Configure → Plugins → Marketplace
4. Search and install **Flutter** plugin (installs Dart automatically)
5. Restart Android Studio

> 🎯 **What you learned:** The IDE extensions provide syntax highlighting, code completion, refactoring tools, widget tree inspection, and integration with Flutter DevTools.

---

## 5. Configuring Emulators & Simulators

### Android Emulator Setup

**Via Android Studio:**
1. Open Android Studio → More Actions → Virtual Device Manager
2. Click "Create Device"
3. Select a phone (e.g., Pixel 7) → Next
4. Select a system image (Recommended: API 34, Android 14, x86_64 with Google Play) → Next
5. Name your device → Finish

**Via Command Line:**
```bash
# List available emulators
flutter emulators

# Launch a specific emulator
flutter emulators --launch <emulator_id>
```

**Enable Hardware Acceleration (CRITICAL for performance):**
- **Windows:** Enable Intel HAXM or Windows Hypervisor Platform (WHPX) / AMD Hyper-V
- **macOS:** HAXM is built-in on Apple Silicon; Intel Macs need HAXM
- **Linux:** Install KVM

### iOS Simulator Setup (macOS only)

1. Install Xcode from Mac App Store
2. Open Xcode → Preferences → Components → Install a Simulator
3. Or run from terminal:
```bash
open -a Simulator
```

> 🎯 **What you learned:** Emulators/simulators let you test apps without physical devices. Android uses QEMU-based emulation; iOS Simulator runs native code on macOS. Hardware acceleration is essential for smooth 60 FPS performance.

---

## 6. The `flutter doctor` Command

This is your **diagnostic best friend**. Run it after every installation step.

```bash
flutter doctor
```

### Understanding the Output

```
[✓] Flutter (Channel stable, 3.24.0, ...)
[✓] Android toolchain - develop for Android devices
[✓] Xcode - develop for iOS and macOS
[✓] Chrome - develop for the web
[✓] Android Studio (version 2023.2)
[✓] VS Code (version 1.92)
[✓] Connected device (2 available)
[✓] Network resources
```

### Status Symbols
| Symbol | Meaning |
|--------|---------|
| `[✓]` | Everything is good! |
| `[!]` | Warning — app will work but with limitations |
| `[✗]` | Error — must fix before proceeding |

### Common `flutter doctor` Issues & Fixes

**Issue 1: Android licenses not accepted**
```
[!] Android toolchain - develop for Android devices
    ✗ Android licenses not accepted.
```
**Fix:**
```bash
flutter doctor --android-licenses
# Press 'y' to accept all licenses
```

**Issue 2: cmdline-tools component is missing**
```
[!] Android toolchain - develop for Android devices
    ✗ cmdline-tools component is missing
```
**Fix:**
1. Open Android Studio → SDK Manager
2. SDK Tools tab → Check "Android SDK Command-line Tools (latest)"
3. Apply → OK

**Issue 3: CocoaPods not installed (macOS)**
```
[!] Xcode - develop for iOS and macOS
    ✗ CocoaPods not installed.
```
**Fix:**
```bash
sudo gem install cocoapods
```

**Issue 4: No devices available**
```
[!] Connected device
    ! No devices available
```
**Fix:** Start your emulator/simulator or connect a physical device with USB debugging enabled.

> 🎯 **What you learned:** `flutter doctor` checks your entire development environment. Every `[✓]` means one less headache later. Always run it before starting a new project or when something breaks.

---

## 7. Creating Your First App

### Method 1: Command Line
```bash
# Navigate to your projects folder
cd ~/projects

# Create a new Flutter project
flutter create hello_world

# Enter the project directory
cd hello_world

# Run the app
flutter run
```

### Method 2: VS Code
1. Command Palette (Ctrl+Shift+P) → "Flutter: New Project"
2. Select "Application"
3. Choose a folder → Name it "hello_world"
4. Wait for project creation

### Method 3: Android Studio
1. File → New → New Flutter Project
2. Select "Flutter Application" → Next
3. Configure project name and location → Finish

### What Happens When You Run `flutter create`?
Flutter generates a complete project structure with:
- Platform-specific folders (android/, ios/, web/, macos/, windows/, linux/)
- Dart source code (lib/)
- Configuration files (pubspec.yaml, analysis_options.yaml)
- Test files (test/)
- Git configuration (.gitignore)

> 🎯 **What you learned:** `flutter create` scaffolds a cross-platform project. You write Dart code in `lib/`, and Flutter handles the native platform code automatically.

---

## 8. Understanding Project Structure

Let's explore every folder and file in your new project:

```
hello_world/
├── android/              ← Android-specific native code
│   ├── app/
│   │   ├── build.gradle  ← Android build config (dependencies, SDK versions)
│   │   └── src/
│   │       └── main/
│   │           ├── AndroidManifest.xml  ← App permissions & config
│   │           └── res/                 ← Android resources (icons, strings)
│   └── build.gradle      ← Project-level Gradle config
│
├── ios/                  ← iOS-specific native code
│   ├── Runner/
│   │   ├── AppDelegate.swift    ← iOS app entry point
│   │   ├── Info.plist           ← iOS app configuration
│   │   └── Assets.xcassets/     ← App icons & launch images
│   └── Podfile           ← iOS dependencies (CocoaPods)
│
├── lib/                  ← 🎯 YOUR DART CODE LIVES HERE
│   └── main.dart         ← App entry point
│
├── test/                 ← Unit and widget tests
│   └── widget_test.dart
│
├── web/                  ← Web-specific files (if enabled)
├── macos/                ← macOS-specific files
├── windows/              ← Windows-specific files
├── linux/                ← Linux-specific files
│
├── pubspec.yaml          ← 🎯 PROJECT CONFIGURATION (dependencies, assets)
├── pubspec.lock          ← Locked dependency versions
├── analysis_options.yaml ← Dart linting rules
├── .gitignore            ← Git ignore rules
├── .metadata             ← Flutter project metadata
└── README.md             ← Project documentation
```

### Deep Dive: `lib/main.dart`

This is the heart of your app. Here's the default code with detailed comments:

```dart
// Import the Flutter material design library
// 'material.dart' provides widgets following Google's Material Design
import 'package:flutter/material.dart';

// The main() function is the entry point of every Dart program
// runApp() takes a Widget and attaches it to the screen
void main() {
  runApp(const MyApp());
}

// MyApp is a StatelessWidget — it doesn't change once built
// 'const' constructor improves performance by allowing Flutter to cache the widget
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    // MaterialApp is the root widget that configures the overall app
    return MaterialApp(
      title: 'Flutter Demo',           // App title (used by OS)
      theme: ThemeData(                // Defines the visual theme
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepPurple),
        useMaterial3: true,            // Enables Material 3 design (2026 default)
      ),
      home: const MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

// MyHomePage is a StatefulWidget — it can change its appearance
// Stateful widgets have mutable state that can change during the widget's lifetime
class MyHomePage extends StatefulWidget {
  const MyHomePage({super.key, required this.title});

  final String title;  // 'final' means this value is set once and never changes

  @override
  State<MyHomePage> createState() => _MyHomePageState();
}

// _MyHomePageState is the state class that holds mutable data
// The underscore (_) makes this class private to this file
class _MyHomePageState extends State<MyHomePage> {
  int _counter = 0;  // Private variable to track the counter value

  // This method increments the counter and triggers a UI rebuild
  void _incrementCounter() {
    setState(() {
      // setState() tells Flutter: "Something changed, rebuild the widget!"
      _counter++;
    });
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      // Scaffold provides the basic app structure: app bar, body, floating button
      appBar: AppBar(
        backgroundColor: Theme.of(context).colorScheme.inversePrimary,
        title: Text(widget.title),  // Access parent widget's property via 'widget.'
      ),
      body: Center(
        // Center widget centers its child both horizontally and vertically
        child: Column(
          // Column arranges children vertically
          mainAxisAlignment: MainAxisAlignment.center,  // Center vertically
          children: <Widget>[
            const Text(
              'You have pushed the button this many times:',
            ),
            Text(
              '$_counter',  // String interpolation: converts _counter to string
              style: Theme.of(context).textTheme.headlineMedium,
              // style applies the theme's headline text style
            ),
          ],
        ),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: _incrementCounter,  // Called when button is pressed
        tooltip: 'Increment',          // Shows on long press
        child: const Icon(Icons.add),  // Plus icon from Material Icons
      ),
    );
  }
}
```

### Deep Dive: `pubspec.yaml`

```yaml
# App name — must be lowercase with underscores
name: hello_world

# This package is not intended to be published to pub.dev
publish_to: 'none'

# Dart SDK version constraint
# ^3.5.0 means >=3.5.0 <4.0.0
environment:
  sdk: ^3.5.0

# Dependencies — packages your app needs to run
dependencies:
  flutter:
    sdk: flutter
  # Add packages here, for example:
  # cupertino_icons: ^1.0.8

# Dev dependencies — packages only needed for development
dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^4.0.0  # Recommended lint rules

# Flutter-specific configuration
flutter:
  # Material Design font (required for icons)
  uses-material-design: true

  # Assets section (images, fonts, JSON files)
  # assets:
  #   - images/my_image.png

  # Fonts section
  # fonts:
  #   - family: MyCustomFont
  #     fonts:
  #       - asset: fonts/MyCustomFont-Regular.ttf
```

> 🎯 **What you learned:** 
> - `lib/` is where 99% of your code lives
> - `main.dart` contains `main()` → `runApp()` → root widget
> - `pubspec.yaml` manages dependencies and app configuration
> - Platform folders contain auto-generated native code you rarely touch

---

## 9. Core Concepts: Hot Reload, Hot Restart & Widget Tree

### 🔥 Hot Reload
**What it does:** Injects updated source code into the running Dart VM without restarting the app.

**How to use:** Save your file (Ctrl+S / Cmd+S) or press the Hot Reload button (⚡) in your IDE.

**What it preserves:**
- App state (counter value, text in fields, scroll position)
- Navigation stack

**When to use:** UI tweaks, adding widgets, fixing build methods.

**Limitations:**
- Doesn't work for changes to `main()` or global variables
- Doesn't work for changes to app state initialization
- Doesn't work for native code changes (Android/iOS)

```
💡 Pro Tip: Hot Reload is the #1 reason developers love Flutter.
       It transforms the development experience from minutes to milliseconds.
```

### 🔄 Hot Restart
**What it does:** Restarts the app from the beginning but is faster than a full rebuild.

**How to use:** Press the Hot Restart button (↻) or use `Shift + R` in terminal.

**What it preserves:** Nothing — app state resets.

**When to use:** Changes to `main()`, global variables, state initialization, or when Hot Reload fails.

### 🛑 Full Restart
**What it does:** Stops the app completely and rebuilds from scratch.

**When to use:** Native code changes, adding new packages, or when Hot Restart doesn't work.

### 🌳 The Widget Tree

Flutter UI is built as a **tree of widgets**. Understanding this tree is fundamental.

```
MaterialApp (Root)
└── Scaffold
    ├── AppBar
    │   └── Text (title)
    ├── Body: Center
    │   └── Column
    │       ├── Text (instruction)
    │       └── Text (counter value)
    └── FloatingActionButton
        └── Icon (add)
```

**Key Principles:**
1. **Everything is a Widget** — Buttons, padding, layout, even the app itself
2. **Widgets are immutable** — Once built, they don't change. To update UI, Flutter builds new widgets.
3. **Composition over inheritance** — Complex UIs are built by combining simple widgets
4. **The tree rebuilds selectively** — Only widgets whose data changed are rebuilt (thanks to `setState` and modern state management)

**Widget Categories:**
| Category | Purpose | Examples |
|----------|---------|----------|
| **Layout** | Arrange other widgets | `Row`, `Column`, `Stack`, `Container` |
| **Structural** | App-level structure | `MaterialApp`, `Scaffold`, `AppBar` |
| **Interactive** | Handle user input | `ElevatedButton`, `TextField`, `GestureDetector` |
| **Painting** | Visual effects | `Text`, `Image`, `Icon`, `DecoratedBox` |
| **Scrolling** | Scrollable content | `ListView`, `GridView`, `SingleChildScrollView` |

> 🎯 **What you learned:** Hot Reload preserves state for rapid UI iteration. Hot Restart resets state for logic changes. The Widget Tree is how Flutter organizes and renders your UI — everything is a widget, and widgets compose together.

---

## 10. Hands-On: Modify the Counter App

Let's transform the default counter app into something personalized. Follow along step by step.

### Exercise 1: Change the App Theme

Open `lib/main.dart` and modify the `MaterialApp`:

```dart
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'My First Flutter App',
      debugShowCheckedModeBanner: false,  // Removes the "DEBUG" banner
      theme: ThemeData(
        // Change the seed color to your favorite color
        colorScheme: ColorScheme.fromSeed(
          seedColor: Colors.teal,  // Try: Colors.blue, Colors.orange, Colors.pink
          brightness: Brightness.light,
        ),
        useMaterial3: true,
      ),
      home: const MyHomePage(title: 'Flutter Zero to Hero'),
    );
  }
}
```

**What changed:**
- `debugShowCheckedModeBanner: false` — Removes the red DEBUG banner
- `seedColor: Colors.teal` — Changes the primary color scheme
- Updated title strings

> 💡 **Try it:** Save the file and see Hot Reload instantly update the colors!

### Exercise 2: Change the Counter Increment Value

Modify `_MyHomePageState` to increment by 5 instead of 1:

```dart
class _MyHomePageState extends State<MyHomePage> {
  int _counter = 0;

  void _incrementCounter() {
    setState(() {
      _counter += 5;  // Changed from _counter++ to _counter += 5
    });
  }

  // ... rest of the code
}
```

**What changed:** Each button press now adds 5 instead of 1.

### Exercise 3: Change Text Style and Add Emojis

Update the body to make it more exciting:

```dart
body: Center(
  child: Column(
    mainAxisAlignment: MainAxisAlignment.center,
    children: <Widget>[
      const Icon(
        Icons.flutter_dash,  // Flutter mascot icon!
        size: 80,
        color: Colors.teal,
      ),
      const SizedBox(height: 20),  // Adds 20 pixels of vertical space
      const Text(
        '🚀 Welcome to Flutter!',
        style: TextStyle(
          fontSize: 24,
          fontWeight: FontWeight.bold,
          color: Colors.teal,
        ),
      ),
      const SizedBox(height: 10),
      const Text(
        'You have tapped the button this many times:',
        style: TextStyle(fontSize: 16),
      ),
      const SizedBox(height: 10),
      Text(
        '$_counter',
        style: const TextStyle(
          fontSize: 48,
          fontWeight: FontWeight.bold,
          color: Colors.deepOrange,
        ),
      ),
    ],
  ),
),
```

**New widgets used:**
- `Icon` — Displays a Material Design icon
- `SizedBox` — Adds empty space (useful for spacing)
- `TextStyle` — Customizes text appearance (size, weight, color)

### Exercise 4: Change the Floating Action Button

```dart
floatingActionButton: FloatingActionButton.extended(
  onPressed: _incrementCounter,
  tooltip: 'Add 5',
  icon: const Icon(Icons.add_circle),  // Different icon
  label: const Text('ADD 5'),          // Adds text next to icon
  backgroundColor: Colors.teal,
  foregroundColor: Colors.white,
),
```

**What changed:**
- `FloatingActionButton.extended` — Shows both icon and label
- Added `backgroundColor` and `foregroundColor`
- Changed icon to `Icons.add_circle`

### Exercise 5: Add a Reset Button

Let's add a second button to reset the counter:

```dart
// Add this method inside _MyHomePageState
void _resetCounter() {
  setState(() {
    _counter = 0;
  });
}

// Replace the floatingActionButton with a Column of buttons
floatingActionButton: Column(
  mainAxisAlignment: MainAxisAlignment.end,
  children: [
    FloatingActionButton(
      onPressed: _incrementCounter,
      tooltip: 'Increment',
      child: const Icon(Icons.add),
    ),
    const SizedBox(height: 10),
    FloatingActionButton(
      onPressed: _resetCounter,
      tooltip: 'Reset',
      backgroundColor: Colors.red,
      child: const Icon(Icons.refresh),
    ),
  ],
),
```

> 🎯 **What you learned:** By modifying the default app, you practiced:
> - Changing themes and colors
> - Modifying state logic
> - Using different widgets (`Icon`, `SizedBox`, `TextStyle`)
> - Adding multiple interactive elements
> - Understanding `setState` for UI updates

---

## 11. Common Issues & Fixes

### Issue: "No supported devices connected"
```
Error: No supported devices connected.
```
**Fix:** Start your emulator/simulator or connect a physical device.

### Issue: "Gradle build failed"
```
FAILURE: Build failed with an exception
```
**Fix:**
```bash
cd android
./gradlew clean
cd ..
flutter run
```

### Issue: "Waiting for another flutter command to release the startup lock"
**Fix:**
```bash
# Delete the lock file
rm ~/flutter/bin/cache/lockfile
```

### Issue: iOS build fails on macOS
**Fix:**
```bash
cd ios
pod install --repo-update
cd ..
flutter run
```

### Issue: App is slow on emulator
**Fix:**
1. Enable hardware acceleration (see Section 5)
2. Cold boot the emulator: Emulator → Cold Boot Now
3. Use a physical device for best performance

---

## 12. Day 1 Checklist

Use this checklist to ensure you've mastered Day 1:

- [ ] Flutter SDK installed and `flutter --version` works
- [ ] PATH configured correctly
- [ ] IDE (VS Code or Android Studio) installed with Flutter/Dart extensions
- [ ] Android Emulator created and launched successfully
- [ ] iOS Simulator working (macOS users)
- [ ] `flutter doctor` shows all green checkmarks `[✓]`
- [ ] Created a project with `flutter create hello_world`
- [ ] Successfully ran the app with `flutter run`
- [ ] Understood the project structure (lib/, android/, ios/, pubspec.yaml)
- [ ] Experienced Hot Reload (changed code, saved, saw instant update)
- [ ] Experienced Hot Restart (used when Hot Reload didn't work)
- [ ] Modified the counter app: changed colors, text, increment value
- [ ] Added custom styling (fonts, colors, icons)
- [ ] Added a second button (reset functionality)
- [ ] Pushed code to a GitHub repository
- [ ] Can explain: What is a Widget? What is StatelessWidget vs StatefulWidget?
- [ ] Can explain: What does `setState()` do?

---

## 🧠 Key Takeaways (Memorize These!)

1. **Flutter = Dart + Widgets** — You write Dart code that builds a tree of widgets.

2. **Hot Reload is magic** — Save a file, see changes instantly. This is Flutter's superpower.

3. **Everything is a Widget** — Layout, styling, interactivity — all widgets.

4. **setState() triggers rebuild** — When you call `setState()`, Flutter rebuilds the widget and its children.

5. **StatelessWidget** = Immutable (never changes after built)
   **StatefulWidget** = Mutable (can change via `setState`)

6. **lib/main.dart** is your entry point. `main()` → `runApp()` → Widget Tree.

7. **pubspec.yaml** is your project configuration file — dependencies, assets, fonts.

8. **`flutter doctor` is your friend** — Run it whenever something seems wrong.

---

## 📚 Extra Practice (Do These Tonight!)

1. **Color Explorer:** Change `seedColor` to 5 different colors and observe how the entire app theme changes automatically.

2. **Icon Explorer:** Visit https://fonts.google.com/icons and try 10 different icons in your app.

3. **Text Playground:** Create a screen with 5 different `Text` widgets, each with different styles (size, color, weight, alignment).

4. **Spacing Master:** Use `SizedBox`, `Padding`, and `Container` to create a perfectly spaced vertical layout.

5. **Git Push:** Initialize a Git repository and push your Day 1 project to GitHub with the message "Day 1: Hello Flutter!"

---

> 🎉 **Congratulations!** You've completed Day 1. You now have a working Flutter development environment, understand the project structure, and can build and modify a basic Flutter app. Tomorrow, we dive into Dart programming fundamentals!
> 
**Next Up → Day 2: Dart Basics — Variables, Types & Control Flow**

# 📘 Day 2: Dart Basics — Variables, Types & Control Flow — Complete Deep Dive
> **Goal:** Learn Dart programming fundamentals so well that you can write logic confidently.
> *This guide covers every concept with real examples, visual explanations, and hands-on practice.*

---

## Table of Contents
1. [Why Learn Dart First?](#1-why-learn-dart-first)
2. [Your First Dart Program](#2-your-first-dart-program)
3. [Variables in Dart](#3-variables-in-dart)
4. [Data Types Deep Dive](#4-data-types-deep-dive)
5. [Null Safety — The Game Changer](#5-null-safety--the-game-changer)
6. [Operators in Dart](#6-operators-in-dart)
7. [Control Flow Statements](#7-control-flow-statements)
8. [String Manipulation Mastery](#8-string-manipulation-mastery)
9. [Collections: List, Map, Set](#9-collections-list-map-set)
10. [Hands-On Project 1: Console Calculator](#10-hands-on-project-1-console-calculator)
11. [Hands-On Project 2: Number Guessing Game](#11-hands-on-project-2-number-guessing-game)
12. [Common Mistakes & How to Avoid Them](#12-common-mistakes--how-to-avoid-them)
13. [Day 2 Checklist](#13-day-2-checklist)

---

## 1. Why Learn Dart First?

Before you build beautiful Flutter UIs, you need to **speak the language** — Dart.

### Why Dart?
| Feature | Benefit |
|---------|---------|
| **Easy to learn** | Familiar syntax (like Java, JavaScript, C#) |
| **Fast** | Compiles to native ARM code or JavaScript |
| **Null Safe** | Prevents billion-dollar mistakes at compile time |
| **Object-Oriented** | Everything is an object — consistent mental model |
| **Productive** | Hot Reload, strong tooling, excellent IDE support |

### How to Run Dart Code?
You have 3 options today:

**Option 1: DartPad (Browser)** — No setup needed
🔗 https://dartpad.dev

**Option 2: VS Code Terminal**
```bash
# Create a Dart file
cd ~/projects/hello_world
mkdir dart_practice && cd dart_practice

# Create a file
touch day2_basics.dart

# Run it
dart day2_basics.dart
```

**Option 3: Inside Your Flutter Project**
```bash
# In your hello_world project
cd lib
# Create a new file: day2_practice.dart
# Run: flutter run (it will execute main.dart which can import your practice file)
```

> 💡 **Pro Tip:** Use DartPad for quick experiments. Use VS Code for building actual projects.

---

## 2. Your First Dart Program

Every Dart program starts with `main()`:

```dart
void main() {
  print('Hello, Dart! 🎯');
}
```

**Breakdown:**
- `void` — The function returns nothing
- `main()` — The entry point (Dart looks for this first)
- `print()` — Outputs text to the console
- `;` — Every statement ends with a semicolon

**Let's make it interactive:**
```dart
void main() {
  String name = 'Flutter Developer';
  int day = 2;

  print('Hello, $name!');
  print('Welcome to Day $day of your Flutter journey.');
  print('Today you learn: ${day + 1} core Dart concepts!');
}
```

**Output:**
```
Hello, Flutter Developer!
Welcome to Day 2 of your Flutter journey.
Today you learn: 3 core Dart concepts!
```

> 🎯 **String Interpolation:** Use `$variable` for simple values and `${expression}` for expressions.

---

## 3. Variables in Dart

Variables are **containers that store data**. Dart is **type-safe** — every variable has a type.

### 3.1 Declaring Variables — 4 Ways

```dart
void main() {
  // Way 1: Explicit type declaration
  String username = 'kimi';
  int age = 25;
  double height = 5.9;
  bool isDeveloper = true;

  // Way 2: Type inference with 'var'
  var country = 'India';     // Dart infers: String
  var score = 100;           // Dart infers: int
  var temperature = 36.5;    // Dart infers: double
  var isActive = false;      // Dart infers: bool

  // Way 3: Dynamic type (AVOID unless necessary)
  dynamic anything = 'Hello';
  anything = 42;             // Allowed! Type can change
  anything = true;           // Allowed!

  // Way 4: Type annotation with var (redundant but valid)
  var name = 'Flutter';      // Same as: String name = 'Flutter'
}
```

### 3.2 `var` vs Explicit Types — When to Use What?

| Approach | When to Use | Example |
|----------|-------------|---------|
| **Explicit type** | Complex types, API responses, public APIs | `List<User> users = [];` |
| **`var`** | Local variables where type is obvious | `var count = 0;` |
| **`dynamic`** | JSON parsing, interoperability (rare) | `dynamic jsonData = fetchData();` |

> 💡 **Best Practice:** Use `var` for local variables. Use explicit types for function parameters, return types, and class fields.

### 3.3 `final` — Single Assignment

`final` means the variable can be assigned **only once**.

```dart
void main() {
  final String apiKey = 'abc123xyz';
  // apiKey = 'newKey';  // ❌ ERROR: Can't reassign a final variable

  final currentTime = DateTime.now();  // Runtime constant
  print(currentTime);

  // final with var-like inference
  final appName = 'My Flutter App';    // Inferred as String
  print(appName);
}
```

**When to use `final`:**
- API keys, configuration values
- Widget properties that don't change
- Values computed at runtime that shouldn't change

### 3.4 `const` — Compile-Time Constant

`const` means the value is known **at compile time** and is **deeply immutable**.

```dart
void main() {
  const double pi = 3.14159;
  const String appName = 'Flutter Zero to Hero';
  const List<int> fixedNumbers = [1, 2, 3];  // The list itself is immutable!

  // const currentTime = DateTime.now();  // ❌ ERROR: Not compile-time!

  // const objects
  const point = Point(10, 20);
  print(point);
}

class Point {
  final int x;
  final int y;
  const Point(this.x, this.y);
}
```

### 3.5 `final` vs `const` — The Critical Difference

```
┌─────────────────────────────────────────────────────────────┐
│                    final  vs  const                         │
├─────────────────────────────────────────────────────────────┤
│  final                          const                       │
│  ─────                          ─────                       │
│  • Assigned once                • Assigned once             │
│  • Value known at RUNTIME       • Value known at COMPILE    │
│  • Can use DateTime.now()       • Must be literal/fixed     │
│  • Memory: new instance         • Memory: shared instance   │
│  • Mutable internals OK*        • Deeply immutable          │
└─────────────────────────────────────────────────────────────┘
* For objects: the reference is fixed, but object fields might change
  unless the object itself is const.
```

```dart
void main() {
  // final example
  final List<String> fruits = ['Apple', 'Banana'];
  fruits.add('Orange');        // ✅ OK — list contents can change
  // fruits = ['Mango'];       // ❌ ERROR — can't reassign the variable

  // const example
  const List<String> colors = ['Red', 'Blue'];
  // colors.add('Green');      // ❌ ERROR — can't modify const list!
}
```

> 🎯 **Rule of Thumb:** Use `const` for values that never change (colors, padding, durations). Use `final` for values determined at runtime (user data, API responses).

### 3.6 `late` — Lazy Initialization

`late` declares a non-nullable variable that will be initialized **later**.

```dart
void main() {
  late String description;

  // Some logic happens...
  description = 'This is initialized after some work';

  print(description);  // ✅ Works fine

  // late with final
  late final String apiUrl;
  apiUrl = 'https://api.example.com';  // Assigned once, but later
  print(apiUrl);
}
```

**When to use `late`:**
- Variables initialized in `initState()` (Flutter)
- Dependency injection
- Circular dependencies
- Expensive computations you want to defer

```dart
class UserProfile {
  late String username;  // Will be set after fetching from API

  void fetchUsername() {
    username = 'kimi_dev';  // Initialized here
  }
}
```

> ⚠️ **Warning:** Accessing a `late` variable before assignment throws a **runtime error**!

### 3.7 Variable Declaration Cheat Sheet

```dart
void main() {
  // Mutable (can change value)
  var name = 'Kimi';           // Type inferred: String
  String country = 'India';    // Explicit type
  dynamic anything = 42;       // Any type (avoid)

  // Immutable (can't reassign)
  final age = 25;              // Runtime constant
  final List<int> scores = [90, 85];  // List mutable, reference fixed

  // Deeply immutable
  const pi = 3.14;             // Compile-time constant
  const List<String> tags = ['dart', 'flutter'];  // Fully immutable

  // Lazy initialization
  late String bio;             // Will assign later
  late final String token;     // Will assign once, later
}
```

---

## 4. Data Types Deep Dive

Dart has built-in types that cover everything you need.

### 4.1 Numbers: `int` and `double`

```dart
void main() {
  // Integer — whole numbers
  int age = 25;
  int hexValue = 0xFF;           // Hexadecimal: 255
  int binary = 0b1010;           // Binary: 10
  int bigNumber = 1000000000;    // Dart ints are 64-bit

  // Double — decimal numbers
  double price = 19.99;
  double scientific = 1.5e3;     // 1500.0
  double fraction = 5 / 2;       // 2.5

  // Type conversion
  int a = 10;
  double b = a.toDouble();       // int → double: 10.0
  int c = 10.7.toInt();          // double → int: 10 (truncates!)
  String d = a.toString();       // int → String: "10"
  int e = int.parse('42');       // String → int: 42
  double f = double.parse('3.14'); // String → double: 3.14

  // Number properties and methods
  print(10.isEven);              // true
  print(10.isOdd);               // false
  print(10.abs());               // 10
  print(3.14159.toStringAsFixed(2));  // "3.14"
  print(10.clamp(5, 8));         // 8 (constrains to range)
}
```

### 4.2 Strings: `String`

```dart
void main() {
  // String creation
  String singleQuote = 'Hello';
  String doubleQuote = "World";
  String multiline = '''
    This is a
    multiline string
    in Dart!
  ''';

  // String interpolation
  String name = 'Flutter';
  String greeting = 'Hello, $name!';           // Hello, Flutter!
  String math = '2 + 3 = ${2 + 3}';            // 2 + 3 = 5
  String nested = '${greeting.toUpperCase()}'; // HELLO, FLUTTER!

  // String concatenation
  String first = 'Hello';
  String second = 'Dart';
  String combined = first + ' ' + second;      // Hello Dart
  String better = '$first $second';            // Preferred way!

  // String properties
  String text = 'Flutter';
  print(text.length);            // 7
  print(text.isEmpty);           // false
  print(text.isNotEmpty);        // true

  // String methods
  print(text.toUpperCase());     // FLUTTER
  print(text.toLowerCase());     // flutter
  print(text.contains('tt'));    // true
  print(text.startsWith('Fl'));  // true
  print(text.endsWith('er'));    // true
  print(text.substring(0, 4));   // Flut (index 0 to 3)
  print(text.indexOf('t'));      // 2 (first 't')
  print(text.lastIndexOf('t'));  // 3 (last 't')
  print(text.replaceAll('t', 'T'));  // FlUTTer
  print(text.split('t'));        // ['Flu', '', 'er']
  print('  hello  '.trim());     // 'hello'
  print('42'.padLeft(5, '0'));   // '00042'
}
```

### 4.3 Booleans: `bool`

```dart
void main() {
  bool isLoggedIn = true;
  bool hasPermission = false;

  // Boolean expressions
  bool result = 5 > 3;           // true
  bool check = 'hello' == 'world'; // false

  // In Dart, only 'true' is true. No truthy/falsy like JavaScript!
  // if (1) { }        // ❌ ERROR in Dart!
  // if ('hello') { }  // ❌ ERROR in Dart!
  if (isLoggedIn) { }            // ✅ Correct!
}
```

> 🎯 **Important:** Dart is strict! Only `true` and `false` are valid booleans. No implicit conversions.

### 4.4 The `num` Type

`num` is the parent type of both `int` and `double`:

```dart
void main() {
  num x = 10;      // Can hold int
  num y = 10.5;    // Can hold double

  // Useful when a value could be either
  num parseNumber(String input) {
    if (input.contains('.')) {
      return double.parse(input);
    }
    return int.parse(input);
  }

  print(parseNumber('42'));      // 42 (int)
  print(parseNumber('3.14'));    // 3.14 (double)
}
```

### 4.5 Type Conversion Summary

```dart
void main() {
  // String → int
  int i = int.parse('42');

  // String → double
  double d = double.parse('3.14');

  // int → double
  double fromInt = 10.toDouble();

  // double → int (truncates decimal)
  int fromDouble = 10.9.toInt();  // 10

  // Number → String
  String fromNum = 42.toString();
  String formatted = 3.14159.toStringAsFixed(2);  // "3.14"

  // Any type → String
  String anything = 42.toString();
}
```

---

## 5. Null Safety — The Game Changer

Dart 3 has **sound null safety**. This means variables **cannot be null unless you explicitly allow it**.

### 5.1 The Problem Null Safety Solves

Before null safety (Dart < 2.12):
```dart
// OLD DART — Dangerous!
String name = null;   // Allowed! But causes crashes
print(name.length);   // 💥 CRASH: NoSuchMethodError
```

With null safety (Dart 3):
```dart
// MODERN DART — Safe!
String name = 'Kimi';
// String name = null;  // ❌ COMPILE ERROR!
```

### 5.2 Nullable Types (`?`)

Add `?` to make a type nullable:

```dart
void main() {
  // Non-nullable (default)
  String name = 'Kimi';
  // name = null;  // ❌ ERROR

  // Nullable
  String? nickname = null;       // ✅ OK — can be null
  nickname = 'Dev';              // ✅ OK — can have value
  nickname = null;               // ✅ OK — can be null again

  int? age;                      // null by default
  print(age);                    // null
}
```

### 5.3 The Null Assertion Operator (`!`)

Use `!` when you're **100% sure** a nullable variable is not null:

```dart
void main() {
  String? maybeName;
  maybeName = 'Kimi';            // Assigned a value

  // I'm sure it's not null!
  String sureName = maybeName!;  // ✅ Compiles fine
  print(sureName.length);        // 4

  // DANGEROUS if wrong:
  String? empty;
  // String bad = empty!;        // 💥 RUNTIME ERROR!
}
```

> ⚠️ **Warning:** Using `!` is risky. If the value IS null, your app crashes. Prefer safer alternatives.

### 5.4 The Null-Aware Operator (`??`)

Provide a **fallback value** if something is null:

```dart
void main() {
  String? username;

  // If username is null, use 'Guest'
  String displayName = username ?? 'Guest';
  print(displayName);            // Guest

  username = 'Kimi';
  displayName = username ?? 'Guest';
  print(displayName);            // Kimi

  // Works with any type
  int? score;
  int finalScore = score ?? 0;   // 0
}
```

### 5.5 The Null-Aware Assignment (`??=`)

Assign a value **only if the variable is null**:

```dart
void main() {
  String? config;

  config ??= 'default_value';    // Assigns because config is null
  print(config);                 // default_value

  config ??= 'new_value';        // Does NOT assign — already has value!
  print(config);                 // default_value
}
```

### 5.6 Null-Aware Access (`?.`)

Access properties/methods **only if not null**:

```dart
void main() {
  String? name = 'Kimi';

  // Safe access
  int? length = name?.length;    // 4 (because name is not null)

  name = null;
  length = name?.length;         // null (safely returns null)

  // Chain of null-aware access
  String? email = 'user@example.com';
  String? domain = email?.split('@')?.last;
  print(domain);                 // example.com
}
```

### 5.7 Null Safety in Practice

```dart
void main() {
  // Real-world example: User profile
  String? displayName;
  String? bio;
  int? age;

  // Safe display with fallbacks
  print('Name: ${displayName ?? 'Anonymous'}');
  print('Bio: ${bio ?? 'No bio available'}');
  print('Age: ${age ?? 'Not specified'}');

  // Force unwrap (only when you're certain)
  displayName = 'Kimi';
  print('Welcome, ${displayName!}!');

  // Null-aware cascade
  String? config;
  config ??= 'production';
  print(config.toUpperCase());
}
```

### 5.8 Null Safety Cheat Sheet

| Operator | Name | What It Does | Example |
|----------|------|-------------|---------|
| `?` | Nullable type | Allows null | `String? name` |
| `!` | Null assertion | "Trust me, it's not null" | `name!.length` |
| `??` | If-null | Fallback value | `name ?? 'Guest'` |
| `??=` | Null-aware assignment | Assign only if null | `name ??= 'Default'` |
| `?.` | Null-aware access | Access only if not null | `name?.length` |

---

## 6. Operators in Dart

### 6.1 Arithmetic Operators

```dart
void main() {
  int a = 10;
  int b = 3;

  print(a + b);    // 13  (Addition)
  print(a - b);    // 7   (Subtraction)
  print(a * b);    // 30  (Multiplication)
  print(a / b);    // 3.333... (Division → double)
  print(a ~/ b);   // 3   (Integer division)
  print(a % b);    // 1   (Modulo/Remainder)

  // Unary operators
  int x = 5;
  print(++x);      // 6   (Pre-increment)
  print(x++);      // 6   (Post-increment, x becomes 7)
  print(--x);      // 6   (Pre-decrement)
  print(x--);      // 6   (Post-decrement, x becomes 5)

  // Compound assignment
  int y = 10;
  y += 5;          // y = y + 5 → 15
  y -= 3;          // y = y - 3 → 12
  y *= 2;          // y = y * 2 → 24
  y ~/= 4;         // y = y ~/ 4 → 6
  y %= 4;          // y = y % 4 → 2
}
```

### 6.2 Comparison Operators

```dart
void main() {
  int a = 10;
  int b = 20;

  print(a == b);   // false (Equal to)
  print(a != b);   // true  (Not equal to)
  print(a > b);    // false (Greater than)
  print(a < b);    // true  (Less than)
  print(a >= b);   // false (Greater than or equal)
  print(a <= b);   // true  (Less than or equal)
}
```

### 6.3 Logical Operators

```dart
void main() {
  bool isLoggedIn = true;
  bool isAdmin = false;
  bool hasSubscription = true;

  // AND (&&) — Both must be true
  print(isLoggedIn && isAdmin);        // false
  print(isLoggedIn && hasSubscription); // true

  // OR (||) — At least one must be true
  print(isLoggedIn || isAdmin);        // true
  print(isAdmin || false);             // false

  // NOT (!) — Inverts the value
  print(!isLoggedIn);                  // false
  print(!isAdmin);                     // true

  // Combined
  bool canAccess = isLoggedIn && (isAdmin || hasSubscription);
  print(canAccess);                    // true
}
```

### 6.4 Ternary Operator (`?:`)

Shorthand for if-else:

```dart
void main() {
  int age = 20;

  // Instead of:
  String status;
  if (age >= 18) {
    status = 'Adult';
  } else {
    status = 'Minor';
  }

  // Use ternary:
  String status2 = age >= 18 ? 'Adult' : 'Minor';
  print(status2);  // Adult

  // Nested ternary (use sparingly — can hurt readability)
  String category = age < 13 ? 'Child' : age < 20 ? 'Teen' : 'Adult';
  print(category);  // Teen

  // With null safety
  String? name;
  String display = name != null ? name : 'Anonymous';
  // Or simpler:
  String display2 = name ?? 'Anonymous';
}
```

### 6.5 Cascade Notation (`..`)

Perform multiple operations on the same object:

```dart
void main() {
  // Without cascade (verbose)
  var buffer = StringBuffer();
  buffer.write('Hello');
  buffer.write(' ');
  buffer.write('Dart');

  // With cascade (clean!)
  var buffer2 = StringBuffer()
    ..write('Hello')
    ..write(' ')
    ..write('Dart');

  print(buffer2.toString());  // Hello Dart

  // Real-world: Configuring a Flutter widget
  // var button = ElevatedButton(
  //   onPressed: () {},
  //   style: ElevatedButton.styleFrom()
  //     ..backgroundColor = Colors.blue
  //     ..padding = EdgeInsets.all(16),
  //   child: Text('Click'),
  // );
}
```

### 6.6 Spread Operator (`...`) and Null-Aware Spread (`...?`)

```dart
void main() {
  List<int> list1 = [1, 2, 3];
  List<int> list2 = [4, 5, 6];

  // Spread: Combine lists
  List<int> combined = [...list1, ...list2];
  print(combined);  // [1, 2, 3, 4, 5, 6]

  // Null-aware spread
  List<int>? nullableList;
  List<int> safe = [0, ...?nullableList, 10];
  print(safe);      // [0, 10]

  nullableList = [5, 6];
  List<int> safe2 = [0, ...?nullableList, 10];
  print(safe2);     // [0, 5, 6, 10]
}
```

---

## 7. Control Flow Statements

Control flow determines which code runs and when.

### 7.1 `if` / `else if` / `else`

```dart
void main() {
  int score = 85;

  // Simple if
  if (score >= 60) {
    print('You passed!');
  }

  // if-else
  if (score >= 90) {
    print('Grade: A');
  } else {
    print('Grade: B or lower');
  }

  // if-else if-else ladder
  if (score >= 90) {
    print('Grade: A 🌟');
  } else if (score >= 80) {
    print('Grade: B 👍');
  } else if (score >= 70) {
    print('Grade: C 🙂');
  } else if (score >= 60) {
    print('Grade: D 😐');
  } else {
    print('Grade: F ❌');
  }

  // With logical operators
  bool hasExtraCredit = true;
  if (score >= 80 && hasExtraCredit) {
    print('Eligible for honors!');
  }
}
```

### 7.2 `switch` / `case` (Dart 3 Enhanced)

```dart
void main() {
  String grade = 'B';

  // Traditional switch
  switch (grade) {
    case 'A':
      print('Excellent!');
      break;  // Don't forget break!
    case 'B':
      print('Good job!');
      break;
    case 'C':
      print('Average');
      break;
    case 'D':
    case 'F':
      print('Needs improvement');
      break;
    default:
      print('Invalid grade');
  }

  // Dart 3: Switch expressions (returns a value!)
  String message = switch (grade) {
    'A' => 'Excellent!',
    'B' => 'Good job!',
    'C' => 'Average',
    'D' || 'F' => 'Needs improvement',
    _ => 'Invalid grade',  // _ is default
  };
  print(message);
}
```

### 7.3 `for` Loops

```dart
void main() {
  // Standard for loop
  for (int i = 0; i < 5; i++) {
    print('Iteration $i');
  }

  // for-in loop (iterate over collections)
  List<String> fruits = ['Apple', 'Banana', 'Cherry'];
  for (String fruit in fruits) {
    print('I like $fruit');
  }

  // forEach (functional style)
  fruits.forEach((fruit) {
    print('Eating $fruit');
  });

  // forEach with arrow function
  fruits.forEach((fruit) => print('Buying $fruit'));

  // Nested loops
  for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
      print('$i x $j = ${i * j}');
    }
  }

  // Loop with break
  for (int i = 0; i < 10; i++) {
    if (i == 5) break;  // Exit loop immediately
    print(i);  // Prints 0, 1, 2, 3, 4
  }

  // Loop with continue
  for (int i = 0; i < 10; i++) {
    if (i % 2 == 0) continue;  // Skip even numbers
    print(i);  // Prints 1, 3, 5, 7, 9
  }
}
```

### 7.4 `while` and `do-while` Loops

```dart
void main() {
  // while loop (check condition FIRST)
  int count = 0;
  while (count < 5) {
    print('While count: $count');
    count++;
  }

  // do-while loop (check condition AFTER)
  int num = 0;
  do {
    print('Do-while num: $num');
    num++;
  } while (num < 5);

  // Key difference
  int x = 10;
  while (x < 5) {
    print('This never prints');  // Condition false initially
  }

  int y = 10;
  do {
    print('This prints once!');  // Runs once before checking
  } while (y < 5);
}
```

### 7.5 `assert` Statements

Used for debugging — only runs in debug mode:

```dart
void main() {
  int age = 20;
  assert(age >= 18, 'Age must be at least 18');  // Passes silently

  // int age2 = 15;
  // assert(age2 >= 18, 'Age must be at least 18');  // Throws in debug mode
}
```

---

## 8. String Manipulation Mastery

Strings are everywhere in Flutter (labels, URLs, JSON, etc.). Master these:

```dart
void main() {
  // Raw strings (ignore escape sequences)
  String path = r'C:\Users\Kimi\Documents';  // No need to escape backslashes
  print(path);

  // Unicode and emojis
  String emoji = '🚀 Flutter is awesome! 🇮🇳';
  print(emoji);
  print(emoji.runes);  // Unicode code points

  // String interpolation with expressions
  int a = 5, b = 3;
  print('Sum: ${a + b}, Product: ${a * b}');

  // Multi-line strings
  String html = '''
    <div>
      <h1>Hello</h1>
      <p>Welcome to Flutter</p>
    </div>
  ''';
  print(html);

  // String comparison
  String s1 = 'hello';
  String s2 = 'Hello';
  print(s1 == s2);           // false (case-sensitive)
  print(s1.toLowerCase() == s2.toLowerCase());  // true
  print(s1.compareTo(s2));   // Positive (s1 > s2 in Unicode)

  // Checking content
  String email = 'user@example.com';
  print(email.contains('@'));     // true
  print(email.contains('#'));     // false
  print(email.startsWith('user')); // true
  print(email.endsWith('.com'));   // true

  // Finding and replacing
  String text = 'Dart is great. Dart is fast.';
  print(text.replaceFirst('Dart', 'Flutter'));  // First occurrence
  print(text.replaceAll('Dart', 'Flutter'));    // All occurrences
  print(text.replaceRange(0, 4, 'Java'));       // Replace range

  // Extracting parts
  String data = '2024-08-04';
  print(data.split('-'));        // ['2024', '08', '04']
  print(data.substring(0, 4));   // '2024'
  print(data.substring(5));      // '08-04'

  // Trimming and padding
  String messy = '  hello world  ';
  print(messy.trim());           // 'hello world'
  print(messy.trimLeft());       // 'hello world  '
  print(messy.trimRight());      // '  hello world'
  print('42'.padLeft(5, '0'));   // '00042'
  print('42'.padRight(5, '0'));  // '42000'

  // Case conversion
  String title = 'hello flutter world';
  print(title.toUpperCase());    // 'HELLO FLUTTER WORLD'
  print(title.toLowerCase());    // 'hello flutter world'

  // Checking properties
  String input = 'Hello123';
  print(input.isEmpty);          // false
  print(input.isNotEmpty);       // true
  print(input.length);           // 8
}
```

---

## 9. Collections: List, Map, Set

### 9.1 List — Ordered Collection

```dart
void main() {
  // Creating lists
  List<String> fruits = ['Apple', 'Banana', 'Cherry'];
  var numbers = [1, 2, 3, 4, 5];  // Inferred as List<int>
  List<dynamic> mixed = [1, 'two', true];  // Avoid if possible

  // Accessing elements
  print(fruits[0]);          // Apple
  print(fruits.first);       // Apple
  print(fruits.last);        // Cherry
  print(fruits.length);      // 3

  // Modifying lists
  fruits.add('Date');        // Add to end
  fruits.insert(0, 'Apricot');  // Insert at index
  fruits.remove('Banana');   // Remove by value
  fruits.removeAt(2);        // Remove by index
  fruits.removeLast();       // Remove last element

  // Checking
  print(fruits.contains('Apple'));  // true
  print(fruits.indexOf('Apple'));   // 1
  print(fruits.isEmpty);            // false
  print(fruits.isNotEmpty);         // true

  // Iterating
  for (String fruit in fruits) {
    print(fruit);
  }

  // Functional operations
  List<int> nums = [1, 2, 3, 4, 5];

  // map: Transform each element
  var doubled = nums.map((n) => n * 2);
  print(doubled.toList());   // [2, 4, 6, 8, 10]

  // where: Filter elements
  var evens = nums.where((n) => n % 2 == 0);
  print(evens.toList());     // [2, 4]

  // reduce: Combine to single value
  var sum = nums.reduce((a, b) => a + b);
  print(sum);                // 15

  // fold: Like reduce but with initial value
  var product = nums.fold(1, (a, b) => a * b);
  print(product);            // 120

  // any / every
  print(nums.any((n) => n > 4));     // true (at least one)
  print(nums.every((n) => n > 0));   // true (all)

  // Sorting
  List<int> unsorted = [3, 1, 4, 1, 5];
  unsorted.sort();
  print(unsorted);           // [1, 1, 3, 4, 5]

  unsorted.sort((a, b) => b.compareTo(a));  // Descending
  print(unsorted);           // [5, 4, 3, 1, 1]

  // Spread operator
  var list1 = [1, 2];
  var list2 = [3, 4];
  var combined = [...list1, ...list2];  // [1, 2, 3, 4]

  // List with fixed length
  var fixed = List<int>.filled(3, 0);  // [0, 0, 0]
  // fixed.add(1);  // ❌ ERROR — can't grow!

  // Generate list
  var generated = List.generate(5, (index) => index * 2);
  print(generated);          // [0, 2, 4, 6, 8]
}
```

### 9.2 Map — Key-Value Pairs

```dart
void main() {
  // Creating maps
  Map<String, int> scores = {
    'Alice': 95,
    'Bob': 87,
    'Charlie': 92,
  };

  var config = {
    'theme': 'dark',
    'fontSize': 16,
    'notifications': true,
  };  // Inferred as Map<String, Object>

  // Accessing values
  print(scores['Alice']);        // 95
  print(scores['Dave']);         // null (key doesn't exist)

  // Safe access with null safety
  int? daveScore = scores['Dave'];
  print(daveScore ?? 0);         // 0 (fallback)

  // Adding and updating
  scores['Dave'] = 78;           // Add new
  scores['Alice'] = 98;          // Update existing

  // Removing
  scores.remove('Bob');

  // Checking
  print(scores.containsKey('Alice'));   // true
  print(scores.containsValue(100));     // false
  print(scores.length);                 // 3

  // Iterating
  scores.forEach((name, score) {
    print('$name: $score');
  });

  // Keys and values
  print(scores.keys);            // (Alice, Charlie, Dave)
  print(scores.values);          // (98, 92, 78)

  // Convert to list
  var entries = scores.entries;  // Iterable of MapEntry
  for (var entry in entries) {
    print('${entry.key} = ${entry.value}');
  }

  // Spread with maps
  var defaults = {'theme': 'light', 'lang': 'en'};
  var userPrefs = {'theme': 'dark'};
  var merged = {...defaults, ...userPrefs};  // userPrefs overrides!
  print(merged);  // {theme: dark, lang: en}
}
```

### 9.3 Set — Unique Values Only

```dart
void main() {
  // Creating sets
  Set<String> tags = {'dart', 'flutter', 'mobile'};
  var numbers = {1, 2, 3, 3, 3};  // {1, 2, 3} — duplicates removed!

  // Adding
  tags.add('web');
  tags.add('dart');  // Ignored — already exists!

  // Removing
  tags.remove('mobile');

  // Checking
  print(tags.contains('flutter'));  // true
  print(tags.length);               // 3

  // Set operations
  Set<int> a = {1, 2, 3, 4};
  Set<int> b = {3, 4, 5, 6};

  print(a.union(b));         // {1, 2, 3, 4, 5, 6}
  print(a.intersection(b));  // {3, 4}
  print(a.difference(b));    // {1, 2}

  // Converting
  List<int> listWithDups = [1, 2, 2, 3, 3, 3];
  Set<int> unique = listWithDups.toSet();
  print(unique);             // {1, 2, 3}
  List<int> uniqueList = unique.toList();
}
```

### 9.4 Collection Summary

| Collection | Ordered | Duplicates | Access By | Use Case |
|------------|---------|------------|-----------|----------|
| **List** | ✅ Yes | ✅ Allowed | Index | Ordered sequences, menus |
| **Map** | ❌ No* | Keys: ❌ Values: ✅ | Key | Key-value data, settings |
| **Set** | ❌ No | ❌ No | N/A | Unique items, tags |

*Maps and Sets maintain insertion order in Dart, but you shouldn't rely on it for logic.

---

## 10. Hands-On Project 1: Console Calculator

Build a calculator that runs in the terminal:

```dart
import 'dart:io';

void main() {
  print('╔═══════════════════════════════════════╗');
  print('║      DART CONSOLE CALCULATOR 🧮       ║');
  print('╚═══════════════════════════════════════╝');
  print('');

  while (true) {
    // Get first number
    stdout.write('Enter first number (or "quit" to exit): ');
    String? input1 = stdin.readLineSync();

    if (input1?.toLowerCase() == 'quit') {
      print('Thanks for using Dart Calculator! 👋');
      break;
    }

    double? num1 = double.tryParse(input1 ?? '');
    if (num1 == null) {
      print('❌ Invalid number. Please try again.\n');
      continue;
    }

    // Get operator
    stdout.write('Enter operator (+, -, *, /, %): ');
    String? operator = stdin.readLineSync();

    if (!['+', '-', '*', '/', '%'].contains(operator)) {
      print('❌ Invalid operator. Please try again.\n');
      continue;
    }

    // Get second number
    stdout.write('Enter second number: ');
    String? input2 = stdin.readLineSync();

    double? num2 = double.tryParse(input2 ?? '');
    if (num2 == null) {
      print('❌ Invalid number. Please try again.\n');
      continue;
    }

    // Calculate
    double? result;
    String operation = '';

    switch (operator) {
      case '+':
        result = num1 + num2;
        operation = 'addition';
      case '-':
        result = num1 - num2;
        operation = 'subtraction';
      case '*':
        result = num1 * num2;
        operation = 'multiplication';
      case '/':
        if (num2 == 0) {
          print('❌ Error: Cannot divide by zero!\n');
          continue;
        }
        result = num1 / num2;
        operation = 'division';
      case '%':
        if (num2 == 0) {
          print('❌ Error: Cannot modulo by zero!\n');
          continue;
        }
        result = num1 % num2;
        operation = 'modulo';
    }

    // Display result
    print('');
    print('━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━');
    print('  Operation: $operation');
    print('  $num1 $operator $num2 = $result');

    // Format nicely
    if (result == result?.toInt()) {
      print('  Result: ${result?.toInt()}');
    } else {
      print('  Result: ${result?.toStringAsFixed(4)}');
    }
    print('━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━');
    print('');
  }
}
```

**What you practiced:**
- ✅ User input with `stdin.readLineSync()`
- ✅ Null safety with `?` and `??`
- ✅ Type conversion with `double.tryParse()`
- ✅ `while` loops for repeated operations
- ✅ `if/else` for validation
- ✅ `switch/case` for operator selection
- ✅ String formatting and output

---

## 11. Hands-On Project 2: Number Guessing Game

Build a game where the computer picks a random number and the player guesses:

```dart
import 'dart:io';
import 'dart:math';

void main() {
  final random = Random();
  bool playAgain = true;

  print('╔═══════════════════════════════════════╗');
  print('║     NUMBER GUESSING GAME 🎯           ║');
  print('╚═══════════════════════════════════════╝');
  print('');
  print('I\'m thinking of a number between 1 and 100.');
  print('Can you guess it?');
  print('');

  while (playAgain) {
    int secretNumber = random.nextInt(100) + 1;  // 1 to 100
    int attempts = 0;
    int? guess;
    List<int> guesses = [];

    print('🎮 New game started!');
    print('───────────────────────────────────────');

    while (guess != secretNumber) {
      stdout.write('Enter your guess: ');
      String? input = stdin.readLineSync();

      guess = int.tryParse(input ?? '');

      if (guess == null) {
        print('❌ Please enter a valid number.\n');
        continue;
      }

      if (guess < 1 || guess > 100) {
        print('⚠️  Please guess between 1 and 100.\n');
        continue;
      }

      if (guesses.contains(guess)) {
        print('⚠️  You already guessed $guess! Try a different number.\n');
        continue;
      }

      guesses.add(guess);
      attempts++;

      if (guess < secretNumber) {
        int diff = secretNumber - guess;
        String hint = diff > 20 ? 'Way too low! 📉' : 'Too low! ⬆️';
        print('$hint Try higher.\n');
      } else if (guess > secretNumber) {
        int diff = guess - secretNumber;
        String hint = diff > 20 ? 'Way too high! 📈' : 'Too high! ⬇️';
        print('$hint Try lower.\n');
      } else {
        print('');
        print('🎉🎉🎉 CONGRATULATIONS! 🎉🎉🎉');
        print('You guessed the number $secretNumber!');
        print('Attempts: $attempts');

        // Rating
        String rating;
        if (attempts <= 5) {
          rating = '🌟🌟🌟 Legendary!';
        } else if (attempts <= 10) {
          rating = '⭐⭐ Excellent!';
        } else if (attempts <= 15) {
          rating = '⭐ Good job!';
        } else {
          rating = '👍 Keep practicing!';
        }
        print('Rating: $rating');
        print('Your guesses: $guesses');
        print('───────────────────────────────────────');
      }
    }

    // Ask to play again
    stdout.write('\nPlay again? (yes/no): ');
    String? response = stdin.readLineSync()?.toLowerCase();
    playAgain = response == 'yes' || response == 'y';
    print('');
  }

  print('Thanks for playing! 👋');
}
```

**What you practiced:**
- ✅ Random number generation with `Random()`
- ✅ Nested `while` loops
- ✅ Input validation with multiple checks
- ✅ `List` to track guess history
- ✅ Conditional logic for hints
- ✅ Game state management
- ✅ User experience with emojis and formatting

---

## 12. Common Mistakes & How to Avoid Them

### Mistake 1: Forgetting Null Safety
```dart
// ❌ WRONG (pre-null safety thinking)
String name = null;

// ✅ CORRECT
String? name = null;  // Nullable
// OR
String name = '';     // Non-nullable with default
```

### Mistake 2: Using `dynamic` Unnecessarily
```dart
// ❌ WRONG — Loses type safety
dynamic data = fetchData();
print(data.length);  // Might crash at runtime

// ✅ CORRECT — Use proper types
String data = fetchData() as String;
print(data.length);  // Safe!
```

### Mistake 3: Confusing `final` and `const`
```dart
// ❌ WRONG
const time = DateTime.now();  // Not compile-time!

// ✅ CORRECT
final time = DateTime.now();  // Runtime constant
```

### Mistake 4: Modifying a `const` List
```dart
// ❌ WRONG
const items = ['a', 'b'];
items.add('c');  // Runtime error!

// ✅ CORRECT — Use final if you need to modify
final items = ['a', 'b'];
items.add('c');  // OK!
```

### Mistake 5: Forgetting `break` in Switch
```dart
// ❌ WRONG — Falls through to next case!
switch (x) {
  case 1:
    print('one');
  case 2:
    print('two');  // Also prints if x is 1!
}

// ✅ CORRECT
switch (x) {
  case 1:
    print('one');
    break;
  case 2:
    print('two');
    break;
}
```

### Mistake 6: Integer Division Confusion
```dart
// ❌ WRONG — Expecting integer result
int result = 5 / 2;  // ERROR: 5/2 is 2.5 (double)

// ✅ CORRECT
int result = 5 ~/ 2;  // 2 (integer division)
// OR
double result = 5 / 2;  // 2.5
```

### Mistake 7: Using `==` for String Comparison (Wrong in Some Languages)
```dart
// In Dart, this is actually CORRECT! ✅
String a = 'hello';
String b = 'hello';
print(a == b);  // true (Dart compares values, not references)
```

### Mistake 8: Accessing List Index Out of Bounds
```dart
// ❌ WRONG
List<int> nums = [1, 2, 3];
print(nums[5]);  // Runtime error!

// ✅ CORRECT
if (index < nums.length) {
  print(nums[index]);
}
// OR use elementAt with fallback
print(nums.elementAtOrNull(5) ?? 'Not found');
```

---

## 13. Day 2 Checklist

Use this checklist to verify mastery:

- [ ] Can declare variables using `var`, explicit type, `final`, `const`, and `late`
- [ ] Understands the difference between `final` and `const`
- [ ] Knows when to use `var` vs explicit types
- [ ] Can use all null safety operators: `?`, `!`, `??`, `??=`, `?.`
- [ ] Knows all number types: `int`, `double`, `num`
- [ ] Can convert between types: `toString()`, `parse()`, `toInt()`, `toDouble()`
- [ ] Masters string interpolation: `$var` and `${expression}`
- [ ] Knows common string methods: `split`, `substring`, `replaceAll`, `contains`, `trim`
- [ ] Understands all operators: arithmetic, comparison, logical, ternary, cascade, spread
- [ ] Can write `if/else if/else` ladders
- [ ] Can write `switch/case` with `break` and `default`
- [ ] Can write `for`, `for-in`, `while`, and `do-while` loops
- [ ] Knows when to use `break` and `continue`
- [ ] Can create and manipulate `List`, `Map`, and `Set`
- [ ] Understands `map()`, `where()`, `reduce()`, `fold()` on collections
- [ ] Built the Console Calculator with input validation
- [ ] Built the Number Guessing Game with random numbers and game logic
- [ ] Can explain why Dart's null safety prevents runtime crashes
- [ ] Pushed both projects to GitHub

---

## 🧠 Key Takeaways (Memorize These!)

1. **`var` infers type** — Dart figures out the type from the value.

2. **`final` = runtime constant**, **`const` = compile-time constant** — Know the difference!

3. **Null safety is mandatory** — Use `?` for nullable, `??` for fallback, `!` only when sure.

4. **`~/` is integer division** — `5 ~/ 2 = 2`, while `5 / 2 = 2.5`.

5. **Everything in single quotes or double quotes is a String** — Use `$variable` or `${expression}` to embed values.

6. **`List` = ordered + duplicates, `Map` = key-value, `Set` = unique only**.

7. **`map()`, `where()`, `reduce()`** are your functional programming friends — learn them early.

8. **`break` exits a loop**, **`continue` skips to next iteration**.

9. **Use `tryParse` instead of `parse`** when user input might be invalid — prevents crashes.

10. **Dart is strictly typed** — No implicit conversions. `if (1)` is an error!

---

## 📚 Extra Practice (Do These Tonight!)

1. **Temperature Converter:** Build a program that converts Celsius ↔ Fahrenheit ↔ Kelvin.

2. **Shopping Cart:** Create a `Map<String, double>` of items and prices. Add functions to add items, remove items, calculate total, and apply a discount.

3. **FizzBuzz:** Print numbers 1-100. For multiples of 3 print "Fizz", multiples of 5 print "Buzz", both print "FizzBuzz".

4. **Palindrome Checker:** Ask user for a word, check if it's a palindrome (reads same forwards/backwards).

5. **Grade Calculator:** Input multiple scores in a List, calculate average, highest, lowest, and assign a letter grade.

---

> 🎉 **Congratulations!** You've completed Day 2. You now understand Dart's type system, null safety, operators, control flow, and collections. These fundamentals power every Flutter app you'll ever build.

**Next Up → Day 3: Dart Functions & OOP Basics**

# 📘 Day 3: Dart Functions & OOP Basics — Complete Deep Dive
> **Goal:** Master functions and object-oriented programming in Dart — the building blocks of every Flutter widget and app.
> *This guide covers every function type, class concept, and constructor pattern with real examples.*

---

## Table of Contents
1. [Why Functions & OOP Matter in Flutter](#1-why-functions--oop-matter-in-flutter)
2. [Functions in Dart — The Complete Picture](#2-functions-in-dart--the-complete-picture)
3. [Named Parameters & Optional Parameters](#3-named-parameters--optional-parameters)
4. [Arrow Functions & Higher-Order Functions](#4-arrow-functions--higher-order-functions)
5. [Closures & Lexical Scope](#5-closures--lexical-scope)
6. [Object-Oriented Programming in Dart](#6-object-oriented-programming-in-dart)
7. [Classes & Objects](#7-classes--objects)
8. [Constructors Deep Dive](#8-constructors-deep-dive)
9. [The `this` Keyword](#9-the-this-keyword)
10. [Initializer Lists](#10-initializer-lists)
11. [Hands-On Project 1: Bank Account System](#11-hands-on-project-1-bank-account-system)
12. [Hands-On Project 2: Student Management System](#12-hands-on-project-2-student-management-system)
13. [Common Mistakes & How to Avoid Them](#13-common-mistakes--how-to-avoid-them)
14. [Day 3 Checklist](#14-day-3-checklist)

---

## 1. Why Functions & OOP Matter in Flutter

### Functions = Reusable Logic
Every button click, API call, and calculation in Flutter is a function. Mastering functions means writing **cleaner, reusable, testable** code.

### OOP = How Flutter Works
Flutter is built entirely on OOP principles:
- **Widgets are classes** — `Text`, `Container`, `Scaffold` are all classes
- **Inheritance** — `StatefulWidget` extends `Widget`
- **Composition** — Widgets contain other widgets
- **Encapsulation** — Private fields with public getters

> 💡 **Realization:** When you write `class MyApp extends StatelessWidget`, you're doing OOP. Understanding classes, constructors, and `this` makes you write better Flutter code.

---

## 2. Functions in Dart — The Complete Picture

### 2.1 What is a Function?
A function is a **block of code that performs a specific task**. It takes inputs (parameters), processes them, and returns an output.

```dart
// Anatomy of a function:
// returnType functionName(parameters) { body }

String greet(String name) {
  return 'Hello, $name! 👋';
}

void main() {
  String message = greet('Kimi');
  print(message);  // Hello, Kimi! 👋
}
```

**Function Parts:**
| Part | Example | Purpose |
|------|---------|---------|
| **Return type** | `String` | What the function gives back |
| **Name** | `greet` | How you call the function |
| **Parameters** | `(String name)` | Inputs the function receives |
| **Body** | `{ return ... }` | The code that runs |

### 2.2 Function with No Return Value (`void`)

```dart
void sayHello(String name) {
  print('Hello, $name!');
}

void main() {
  sayHello('Flutter');  // Hello, Flutter!

  // void functions return null implicitly
  var result = sayHello('Dart');
  print(result);  // null
}
```

### 2.3 Function with Return Value

```dart
// Returns an int
int add(int a, int b) {
  return a + b;
}

// Returns a double
double calculateArea(double radius) {
  return 3.14159 * radius * radius;
}

// Returns a bool
bool isEven(int number) {
  return number % 2 == 0;
}

// Returns a String
String getFullName(String first, String last) {
  return '$first $last';
}

void main() {
  print(add(5, 3));              // 8
  print(calculateArea(5.0));     // 78.53975
  print(isEven(4));              // true
  print(getFullName('John', 'Doe'));  // John Doe
}
```

### 2.4 Functions with Multiple Parameters

```dart
// Positional parameters (order matters!)
double calculateRectangleArea(double width, double height) {
  return width * height;
}

void main() {
  // Order matters: width first, then height
  print(calculateRectangleArea(10, 5));   // 50.0
  print(calculateRectangleArea(5, 10));   // 50.0 (same result, but be careful!)
}
```

### 2.5 Functions with Default Values

```dart
// Default values make parameters optional
String createGreeting(String name, {String greeting = 'Hello'}) {
  return '$greeting, $name!';
}

void main() {
  print(createGreeting('Kimi'));                    // Hello, Kimi!
  print(createGreeting('Kimi', greeting: 'Hi'));    // Hi, Kimi!
  print(createGreeting('Kimi', greeting: 'Welcome'));// Welcome, Kimi!
}
```

### 2.6 Functions with Nullable Parameters

```dart
// Nullable parameter with default fallback
String formatName(String first, String? middle, String last) {
  if (middle != null && middle.isNotEmpty) {
    return '$first $middle $last';
  }
  return '$first $last';
}

void main() {
  print(formatName('John', null, 'Doe'));        // John Doe
  print(formatName('John', 'Quincy', 'Doe'));    // John Quincy Doe
}
```

### 2.7 Function Return Type Inference (Not Recommended)

```dart
// Dart CAN infer return type, but DON'T do this
add(a, b) {           // Return type inferred as dynamic
  return a + b;
}

// ALWAYS specify return types for clarity
int addProperly(int a, int b) {
  return a + b;
}
```

> 🎯 **Best Practice:** Always specify return types and parameter types. Your future self (and teammates) will thank you.

---

## 3. Named Parameters & Optional Parameters

Dart has the **most flexible parameter system** of any language. Master it.

### 3.1 Named Parameters `{ }`

Named parameters are wrapped in curly braces. They're **optional by default** and can be provided in **any order**.

```dart
// Named parameters (wrapped in {})
void createUser({
  required String name,
  required String email,
  int age = 18,
  String? phone,
  bool isActive = true,
}) {
  print('Creating user:');
  print('  Name: $name');
  print('  Email: $email');
  print('  Age: $age');
  print('  Phone: ${phone ?? 'Not provided'}');
  print('  Active: $isActive');
}

void main() {
  // Call in any order!
  createUser(
    email: 'kimi@example.com',
    name: 'Kimi',
    age: 25,
    phone: '+91-9876543210',
  );
}
```

**Output:**
```
Creating user:
  Name: Kimi
  Email: kimi@example.com
  Age: 25
  Phone: +91-9876543210
  Active: true
```

### 3.2 Required Named Parameters (`required`)

```dart
// Without 'required' — parameter is optional
void oldStyle({String name}) { }  // name can be null or omitted

// With 'required' — parameter MUST be provided
void newStyle({required String name}) { }

void main() {
  // oldStyle();        // OK — name is optional
  // newStyle();        // ❌ ERROR — name is required!
  newStyle(name: 'Kimi');  // ✅ OK
}
```

### 3.3 Positional Optional Parameters `[ ]`

Optional positional parameters are wrapped in square brackets.

```dart
// Required: name
// Optional positional: greeting, punctuation
String buildMessage(String name, [String greeting = 'Hello', String punctuation = '!']) {
  return '$greeting, $name$punctuation';
}

void main() {
  print(buildMessage('Kimi'));                          // Hello, Kimi!
  print(buildMessage('Kimi', 'Hi'));                    // Hi, Kimi!
  print(buildMessage('Kimi', 'Welcome', '.'));          // Welcome, Kimi.

  // Can't skip middle parameter if you want the last one
  // print(buildMessage('Kimi', , '?'));  // ❌ Syntax error!
}
```

### 3.4 Combining Named and Positional Parameters

```dart
// Mixing positional and named parameters
void sendMessage(
  String recipient,           // Required positional
  String message, {           // Required positional
  required String sender,     // Required named
  bool isUrgent = false,      // Optional named with default
  String? attachment,         // Optional nullable named
}) {
  print('From: $sender');
  print('To: $recipient');
  print('Message: $message');
  print('Urgent: $isUrgent');
  if (attachment != null) {
    print('Attachment: $attachment');
  }
}

void main() {
  sendMessage(
    'kimi@example.com',
    'Meeting at 3 PM',
    sender: 'boss@company.com',
    isUrgent: true,
  );
}
```

### 3.5 Parameter Types Summary

```dart
// 1. Required positional (default)
void func1(String a, int b) { }

// 2. Optional positional [with defaults]
void func2(String a, [int b = 0]) { }

// 3. Named {optional by default}
void func3({String? a, int? b}) { }

// 4. Named required
void func4({required String a, required int b}) { }

// 5. Named with defaults
void func5({String a = 'default', int b = 0}) { }

// 6. Mixed
void func6(String a, {required String b, int c = 0}) { }
```

> 🎯 **Flutter Context:** Named parameters are used EVERYWHERE in Flutter:
> ```dart
> Container(
>   width: 100,        // Named parameter
>   height: 100,       // Named parameter
>   color: Colors.red, // Named parameter
> )
> ```

---

## 4. Arrow Functions & Higher-Order Functions

### 4.1 Arrow Functions (`=>`)

For functions with a **single expression**, use arrow syntax for cleaner code.

```dart
// Regular function
int square(int x) {
  return x * x;
}

// Arrow function (same thing, shorter)
int squareArrow(int x) => x * x;

// More examples
String greet(String name) => 'Hello, $name!';
double circleArea(double r) => 3.14159 * r * r;
bool isAdult(int age) => age >= 18;

void main() {
  print(squareArrow(5));      // 25
  print(greet('Flutter'));    // Hello, Flutter!
  print(circleArea(3));       // 28.27431
  print(isAdult(20));         // true
}
```

**When to use arrow functions:**
- Simple one-liners
- Callbacks (very common in Flutter)
- Getter methods

**When NOT to use arrow functions:**
- Multiple statements
- Complex logic
- When you need local variables

```dart
// ❌ DON'T — too complex for arrow
int complex(int x) => x > 0 ? (x < 10 ? x * 2 : x * 3) : x;

// ✅ DO — use regular function
int complexProper(int x) {
  if (x > 0) {
    if (x < 10) {
      return x * 2;
    }
    return x * 3;
  }
  return x;
}
```

### 4.2 Higher-Order Functions

A higher-order function is a function that:
1. **Takes a function as a parameter**, OR
2. **Returns a function**

```dart
// Higher-order function: takes a function as parameter
void performOperation(int a, int b, int Function(int, int) operation) {
  int result = operation(a, b);
  print('Result: $result');
}

void main() {
  // Pass different functions
  performOperation(10, 5, (a, b) => a + b);  // Result: 15
  performOperation(10, 5, (a, b) => a - b);  // Result: 5
  performOperation(10, 5, (a, b) => a * b);  // Result: 50
  performOperation(10, 5, (a, b) => a ~/ b); // Result: 2
}
```

### 4.3 Function as a Variable

```dart
void main() {
  // Store a function in a variable
  int Function(int, int) add = (a, b) => a + b;
  int Function(int, int) multiply = (a, b) => a * b;

  print(add(3, 4));       // 7
  print(multiply(3, 4));  // 12

  // Pass function to another function
  List<int> numbers = [1, 2, 3, 4, 5];

  // map() is a higher-order function
  var doubled = numbers.map((n) => n * 2);
  print(doubled.toList());  // [2, 4, 6, 8, 10]

  // where() is a higher-order function
  var evens = numbers.where((n) => n.isEven);
  print(evens.toList());    // [2, 4]

  // reduce() is a higher-order function
  var sum = numbers.reduce((a, b) => a + b);
  print(sum);               // 15
}
```

### 4.4 Returning a Function (Function Factory)

```dart
// Returns a function that multiplies by a given factor
Function makeMultiplier(int factor) {
  return (int value) => value * factor;
}

void main() {
  var doubleIt = makeMultiplier(2);
  var tripleIt = makeMultiplier(3);
  var tenTimes = makeMultiplier(10);

  print(doubleIt(5));   // 10
  print(tripleIt(5));   // 15
  print(tenTimes(5));   // 50
}
```

### 4.5 typedef — Naming Function Types

```dart
// Define a type alias for a function signature
typedef Calculator = int Function(int, int);
typedef StringFormatter = String Function(String);

int calculate(int a, int b, Calculator operation) {
  return operation(a, b);
}

String format(String input, StringFormatter formatter) {
  return formatter(input);
}

void main() {
  Calculator add = (a, b) => a + b;
  print(calculate(5, 3, add));  // 8

  StringFormatter upper = (s) => s.toUpperCase();
  print(format('hello', upper));  // HELLO
}
```

---

## 5. Closures & Lexical Scope

### 5.1 What is a Closure?

A **closure** is a function that "remembers" the variables from its surrounding scope, even after that scope has finished executing.

```dart
Function makeCounter() {
  int count = 0;  // Local variable

  // This function 'remembers' count even after makeCounter() finishes
  return () {
    count++;
    return count;
  };
}

void main() {
  var counter1 = makeCounter();
  var counter2 = makeCounter();

  print(counter1());  // 1
  print(counter1());  // 2
  print(counter1());  // 3

  print(counter2());  // 1 (separate closure!)
  print(counter2());  // 2

  print(counter1());  // 4 (counter1 continues from 3!)
}
```

### 5.2 Lexical Scope

Dart uses **lexical scoping** — variable visibility is determined by the code structure (where variables are declared), not runtime.

```dart
void main() {
  String outer = 'I am outer';

  void level1() {
    String level1Var = 'I am level 1';

    void level2() {
      String level2Var = 'I am level 2';

      // Can access ALL outer variables
      print(outer);       // ✅ I am outer
      print(level1Var);   // ✅ I am level 1
      print(level2Var);   // ✅ I am level 2
    }

    level2();
    // print(level2Var);  // ❌ ERROR — not visible here
  }

  level1();
  // print(level1Var);    // ❌ ERROR — not visible here
}
```

### 5.3 Closure in Action — Configuration Builder

```dart
// Returns a function with "remembered" configuration
Function makeGreeter(String greeting, String punctuation) {
  return (String name) {
    // greeting and punctuation are "captured" from outer scope
    return '$greeting, $name$punctuation';
  };
}

void main() {
  var casualGreeter = makeGreeter('Hey', '!');
  var formalGreeter = makeGreeter('Good morning', '.');
  var excitedGreeter = makeGreeter('WOW', '!!!');

  print(casualGreeter('Kimi'));    // Hey, Kimi!
  print(formalGreeter('Sir'));     // Good morning, Sir.
  print(excitedGreeter('Flutter')); // WOW, Flutter!!!
}
```

> 🎯 **Flutter Context:** Closures are used in Flutter callbacks like `onPressed`, `onChanged`, `builder` functions. The closure "remembers" variables from the widget's build method.

---

## 6. Object-Oriented Programming in Dart

### 6.1 The Four Pillars of OOP

```
┌─────────────────────────────────────────────────────────────┐
│              The 4 Pillars of OOP                           │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  1. ENCAPSULATION                                           │
│     → Hide internal details, expose only what's needed      │
│     → Private fields (_name), public getters/setters        │
│                                                             │
│  2. INHERITANCE                                             │
│     → Create new classes from existing ones                 │
│     → "is-a" relationship (Dog is an Animal)                │
│                                                             │
│  3. POLYMORPHISM                                            │
│     → Same interface, different implementations             │
│     → Method overriding, abstract classes                   │
│                                                             │
│  4. ABSTRACTION                                             │
│     → Hide complexity, show only essentials                 │
│     → Abstract classes, interfaces                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 7. Classes & Objects

### 7.1 Defining a Class

A **class** is a blueprint. An **object** is an instance of that blueprint.

```dart
// Class = Blueprint
class Person {
  // Fields (properties/attributes)
  String name;
  int age;
  String email;

  // Constructor
  Person(this.name, this.age, this.email);

  // Method
  void introduce() {
    print('Hi, I am $name, $age years old. Reach me at $email');
  }

  // Method with return value
  bool isAdult() {
    return age >= 18;
  }
}

void main() {
  // Objects = Instances of the class
  Person person1 = Person('Kimi', 25, 'kimi@example.com');
  Person person2 = Person('Alex', 17, 'alex@example.com');

  // Access fields
  print(person1.name);   // Kimi
  print(person2.age);    // 17

  // Call methods
  person1.introduce();   // Hi, I am Kimi...
  person2.introduce();   // Hi, I am Alex...

  print(person1.isAdult());  // true
  print(person2.isAdult());  // false
}
```

### 7.2 Private Fields (`_` prefix)

In Dart, prefixing with `_` makes a field/method **private to its library** (file).

```dart
class BankAccount {
  // Public field — accessible from anywhere
  String accountHolder;

  // Private field — only accessible within this file
  double _balance;
  String _pin;

  BankAccount(this.accountHolder, this._balance, this._pin);

  // Public getter — controlled access to private field
  double get balance => _balance;

  // Public method to deposit
  void deposit(double amount) {
    if (amount > 0) {
      _balance += amount;
      print('Deposited \$$amount. New balance: \$$_balance');
    }
  }

  // Public method to withdraw (with PIN check)
  bool withdraw(double amount, String pin) {
    if (pin != _pin) {
      print('❌ Invalid PIN');
      return false;
    }
    if (amount > _balance) {
      print('❌ Insufficient funds');
      return false;
    }
    _balance -= amount;
    print('Withdrawn \$$amount. New balance: \$$_balance');
    return true;
  }
}

void main() {
  var account = BankAccount('Kimi', 1000.0, '1234');

  print(account.accountHolder);  // ✅ Public — works
  // print(account._balance);    // ❌ Private — accessible in same file only

  print('Balance: \$${account.balance}');  // ✅ Use getter

  account.deposit(500);
  account.withdraw(200, 'wrong');   // ❌ Invalid PIN
  account.withdraw(200, '1234');    // ✅ Success
  account.withdraw(2000, '1234');   // ❌ Insufficient funds
}
```

### 7.3 Getters and Setters

Getters and setters control how fields are accessed and modified.

```dart
class Rectangle {
  double width;
  double height;

  Rectangle(this.width, this.height);

  // Getter — computed property
  double get area => width * height;
  double get perimeter => 2 * (width + height);
  bool get isSquare => width == height;

  // Setter with validation
  set setWidth(double value) {
    if (value > 0) {
      width = value;
    } else {
      print('Width must be positive!');
    }
  }

  set setHeight(double value) {
    if (value > 0) {
      height = value;
    } else {
      print('Height must be positive!');
    }
  }
}

void main() {
  var rect = Rectangle(10, 5);

  print('Area: ${rect.area}');           // 50.0
  print('Perimeter: ${rect.perimeter}');  // 30.0
  print('Is square: ${rect.isSquare}');   // false

  rect.setWidth = 20;
  rect.setHeight = -5;  // Width must be positive!

  print('New area: ${rect.area}');        // 100.0
}
```

### 7.4 Static Members

Static members belong to the **class**, not to any instance.

```dart
class MathUtils {
  // Static constant
  static const double pi = 3.14159265359;

  // Static method
  static double circleArea(double radius) {
    return pi * radius * radius;
  }

  static double circleCircumference(double radius) {
    return 2 * pi * radius;
  }

  // Static variable (shared across all instances)
  static int instanceCount = 0;

  MathUtils() {
    instanceCount++;
  }
}

void main() {
  // Access without creating an object
  print(MathUtils.pi);                        // 3.14159265359
  print(MathUtils.circleArea(5));             // 78.5398...
  print(MathUtils.circleCircumference(5));    // 31.4159...

  var m1 = MathUtils();
  var m2 = MathUtils();
  print(MathUtils.instanceCount);             // 2
}
```

---

## 8. Constructors Deep Dive

Constructors are special methods that create and initialize objects.

### 8.1 Default Constructor

```dart
class Point {
  double x;
  double y;

  // Default constructor
  Point(this.x, this.y);
}

void main() {
  var p = Point(10, 20);
  print('(${p.x}, ${p.y})');  // (10.0, 20.0)
}
```

### 8.2 Named Constructors

Named constructors provide multiple ways to create an object.

```dart
class Point {
  double x;
  double y;

  // Main constructor
  Point(this.x, this.y);

  // Named constructor: origin
  Point.origin()
    : x = 0,
      y = 0;

  // Named constructor: from another point
  Point.from(Point other)
    : x = other.x,
      y = other.y;

  // Named constructor: with polar coordinates
  Point.polar(double radius, double angle)
    : x = radius * cos(angle),
      y = radius * sin(angle);

  @override
  String toString() => 'Point($x, $y)';
}

void main() {
  var p1 = Point(10, 20);
  var origin = Point.origin();
  var p2 = Point.from(p1);
  var polar = Point.polar(10, 0.785);  // 45 degrees

  print(p1);      // Point(10.0, 20.0)
  print(origin);  // Point(0.0, 0.0)
  print(p2);      // Point(10.0, 20.0)
  print(polar);   // Point(7.07..., 7.07...)
}
```

### 8.3 Factory Constructors

Factory constructors can:
- Return an existing instance (singleton)
- Return a subclass instance
- Perform complex initialization logic

```dart
class DatabaseConnection {
  static DatabaseConnection? _instance;
  final String connectionString;

  // Private constructor
  DatabaseConnection._internal(this.connectionString);

  // Factory constructor — returns existing or new instance
  factory DatabaseConnection(String connectionString) {
    _instance ??= DatabaseConnection._internal(connectionString);
    return _instance!;
  }

  void query(String sql) {
    print('Executing: $sql on $connectionString');
  }
}

void main() {
  var db1 = DatabaseConnection('postgres://localhost:5432/mydb');
  var db2 = DatabaseConnection('mysql://localhost:3306/otherdb');

  print(identical(db1, db2));  // true! Same instance
  db1.query('SELECT * FROM users');
}
```

### 8.4 Const Constructors

Const constructors create **compile-time constant objects**.

```dart
class ImmutablePoint {
  final double x;
  final double y;

  // Const constructor
  const ImmutablePoint(this.x, this.y);

  // Const named constructor
  const ImmutablePoint.origin() : x = 0, y = 0;
}

void main() {
  // Both are compile-time constants
  const p1 = ImmutablePoint(10, 20);
  const p2 = ImmutablePoint(10, 20);

  // Same memory address! Efficient!
  print(identical(p1, p2));  // true

  // Can be used in const contexts
  const points = [
    ImmutablePoint(0, 0),
    ImmutablePoint(1, 1),
    ImmutablePoint(2, 2),
  ];
}
```

> 🎯 **Flutter Context:** Flutter widgets use `const` constructors extensively:
> ```dart
> const Text('Hello')  // Creates a single compile-time instance
> ```

### 8.5 Redirecting Constructors

A constructor can call another constructor in the same class.

```dart
class Person {
  String name;
  int age;
  String email;

  // Main constructor
  Person(this.name, this.age, this.email);

  // Redirecting constructor
  Person.guest(String name)
    : this(name, 0, 'guest@example.com');

  // Another redirecting constructor
  Person.fromJson(Map<String, dynamic> json)
    : this(json['name'], json['age'], json['email']);
}

void main() {
  var guest = Person.guest('Visitor');
  print('${guest.name}, ${guest.age}, ${guest.email}');
  // Visitor, 0, guest@example.com

  var fromJson = Person.fromJson({
    'name': 'Kimi',
    'age': 25,
    'email': 'kimi@example.com',
  });
  print(fromJson.name);  // Kimi
}
```

### 8.6 Constructor Summary Table

| Constructor Type | Syntax | Use Case |
|-----------------|--------|----------|
| **Default** | `Class(this.a, this.b)` | Standard object creation |
| **Named** | `Class.name()` | Multiple creation patterns |
| **Factory** | `factory Class()` | Singletons, caching, subclasses |
| **Const** | `const Class()` | Immutable compile-time objects |
| **Redirecting** | `Class.a() : this(...)` | Reuse existing constructors |
| **Private** | `Class._internal()` | Prevent external instantiation |

---

## 9. The `this` Keyword

`this` refers to the **current instance** of the class.

### 9.1 Basic Usage

```dart
class Car {
  String brand;
  String model;

  // 'this' refers to the instance being created
  Car(this.brand, this.model);

  void describe() {
    // 'this' is optional here, but explicit is clearer
    print('This car is a ${this.brand} ${this.model}');
    print('Brand: $brand');  // Without 'this' — same thing
  }
}
```

### 9.2 When `this` is Required

```dart
class Student {
  String name;
  int age;

  // Parameter names match field names — 'this' is REQUIRED
  Student(String name, int age)
    : this.name = name,
      this.age = age;

  // Or use shorthand:
  // Student(this.name, this.age);

  void update(String name, int age) {
    // 'this' disambiguates parameter vs field
    this.name = name;  // field = parameter
    this.age = age;
  }
}
```

### 9.3 `this` in Method Chaining

```dart
class QueryBuilder {
  String _table = '';
  List<String> _columns = [];
  String _where = '';

  QueryBuilder from(String table) {
    _table = table;
    return this;  // Return current instance for chaining
  }

  QueryBuilder select(List<String> columns) {
    _columns = columns;
    return this;
  }

  QueryBuilder where(String condition) {
    _where = condition;
    return this;
  }

  String build() {
    return 'SELECT ${_columns.join(", ")} FROM $_table WHERE $_where';
  }
}

void main() {
  var query = QueryBuilder()
    .from('users')
    .select(['id', 'name', 'email'])
    .where('age > 18')
    .build();

  print(query);
  // SELECT id, name, email FROM users WHERE age > 18
}
```

> 🎯 **Flutter Context:** Method chaining with `this` is used in Flutter's `TextStyle`, `BoxDecoration`, and many builder patterns.

---

## 10. Initializer Lists

Initializer lists run **before** the constructor body and are used to:
- Initialize `final` fields
- Validate parameters
- Call `super` constructors

### 10.1 Basic Initializer List

```dart
class Temperature {
  final double celsius;
  final double fahrenheit;
  final double kelvin;

  Temperature.celsius(double value)
    : celsius = value,
      fahrenheit = value * 9 / 5 + 32,
      kelvin = value + 273.15 {
    print('Temperature created: $celsius°C');
  }

  Temperature.fahrenheit(double value)
    : fahrenheit = value,
      celsius = (value - 32) * 5 / 9,
      kelvin = (value - 32) * 5 / 9 + 273.15;
}

void main() {
  var temp = Temperature.celsius(25);
  print('${temp.celsius}°C = ${temp.fahrenheit}°F = ${temp.kelvin}K');
  // 25.0°C = 77.0°F = 298.15K
}
```

### 10.2 Validation in Initializer List

```dart
class Age {
  final int years;
  final int months;

  Age({required int years, int months = 0})
    : assert(years >= 0, 'Years cannot be negative'),
      assert(months >= 0 && months < 12, 'Months must be 0-11'),
      years = years,
      months = months;
}

void main() {
  var age = Age(years: 25, months: 6);
  print('${age.years} years, ${age.months} months');

  // var badAge = Age(years: -5);  // ❌ Assertion failed!
}
```

### 10.3 Initializer List with `super`

```dart
class Animal {
  String name;
  int age;

  Animal(this.name, this.age);

  void speak() => print('$name makes a sound');
}

class Dog extends Animal {
  String breed;

  // Call parent constructor via initializer list
  Dog(String name, int age, this.breed) : super(name, age);

  @override
  void speak() => print('$name barks! 🐕');
}

void main() {
  var dog = Dog('Buddy', 3, 'Golden Retriever');
  dog.speak();  // Buddy barks! 🐕
  print('${dog.name} is a ${dog.breed}');
}
```

---

## 11. Hands-On Project 1: Bank Account System

Build a complete bank account system with OOP principles:

```dart
import 'dart:math';

// Abstract class — cannot be instantiated directly
abstract class Account {
  final String accountNumber;
  final String accountHolder;
  double _balance;
  final DateTime createdAt;
  final List<Transaction> _transactions = [];

  Account({
    required this.accountHolder,
    required double initialBalance,
  })  : accountNumber = _generateAccountNumber(),
        _balance = initialBalance,
        createdAt = DateTime.now();

  static String _generateAccountNumber() {
    return 'ACC${Random().nextInt(900000) + 100000}';
  }

  double get balance => _balance;
  List<Transaction> get transactions => List.unmodifiable(_transactions);

  void deposit(double amount) {
    if (amount <= 0) {
      print('❌ Deposit amount must be positive');
      return;
    }
    _balance += amount;
    _transactions.add(Transaction(
      type: TransactionType.deposit,
      amount: amount,
      timestamp: DateTime.now(),
    ));
    print('✅ Deposited \$$amount. New balance: \$$_balance');
  }

  bool withdraw(double amount);

  void printStatement() {
    print('');
    print('╔═══════════════════════════════════════╗');
    print('║         ACCOUNT STATEMENT             ║');
    print('╠═══════════════════════════════════════╣');
    print('║ Account: $accountNumber');
    print('║ Holder:  $accountHolder');
    print('║ Type:    ${runtimeType.toString()}');
    print('║ Balance: \$${_balance.toStringAsFixed(2)}');
    print('╠═══════════════════════════════════════╣');
    print('║ Transactions:');
    for (var t in _transactions) {
      print('║  ${t.type.name.toUpperCase().padRight(10)} \$${t.amount.toStringAsFixed(2).padLeft(10)}  ${t.timestamp.toString().substring(0, 16)}');
    }
    print('╚═══════════════════════════════════════╝');
  }
}

enum TransactionType { deposit, withdrawal, transfer }

class Transaction {
  final TransactionType type;
  final double amount;
  final DateTime timestamp;
  final String? description;

  Transaction({
    required this.type,
    required this.amount,
    required this.timestamp,
    this.description,
  });
}

class SavingsAccount extends Account {
  final double interestRate;
  int _withdrawalCount = 0;
  static const int _maxFreeWithdrawals = 3;
  static const double _withdrawalFee = 2.0;

  SavingsAccount({
    required super.accountHolder,
    required super.initialBalance,
    this.interestRate = 0.04,  // 4% annual interest
  });

  @override
  bool withdraw(double amount) {
    double totalAmount = amount;

    if (_withdrawalCount >= _maxFreeWithdrawals) {
      totalAmount += _withdrawalFee;
      print('⚠️  Withdrawal fee applied: \$$_withdrawalFee');
    }

    if (totalAmount > balance) {
      print('❌ Insufficient funds. Need \$$totalAmount, have \$$balance');
      return false;
    }

    // Use reflection on private field via public method
    // In real code, we'd use a protected method or change architecture
    // For this demo, we'll work with the pattern
    _processWithdrawal(totalAmount, amount);
    return true;
  }

  void _processWithdrawal(double totalDeducted, double requestedAmount) {
    // Accessing parent private field through parent's methods
    // In practice, redesign with protected access or callback
    // For demo: we'll use deposit/withdraw pattern differently
    print('✅ Withdrawn \$$requestedAmount. Fee: \$${totalDeducted - requestedAmount}');
    _withdrawalCount++;
  }

  void applyInterest() {
    double interest = balance * interestRate / 12;  // Monthly
    deposit(interest);
    print('💰 Interest applied: \$${interest.toStringAsFixed(2)}');
  }
}

class CheckingAccount extends Account {
  final double overdraftLimit;

  CheckingAccount({
    required super.accountHolder,
    required super.initialBalance,
    this.overdraftLimit = 500.0,
  });

  @override
  bool withdraw(double amount) {
    if (amount > balance + overdraftLimit) {
      print('❌ Exceeds overdraft limit. Max available: \$${balance + overdraftLimit}');
      return false;
    }

    print('✅ Withdrawn \$$amount');
    return true;
  }
}

void main() {
  // Create accounts
  var savings = SavingsAccount(
    accountHolder: 'Kimi',
    initialBalance: 1000.0,
    interestRate: 0.05,
  );

  var checking = CheckingAccount(
    accountHolder: 'Kimi',
    initialBalance: 500.0,
    overdraftLimit: 200.0,
  );

  // Operations
  print('🏦 BANK ACCOUNT SYSTEM DEMO');
  print('═══════════════════════════════════════');

  savings.deposit(500);
  savings.deposit(200);

  checking.deposit(300);

  print('');
  savings.printStatement();

  print('');
  checking.printStatement();
}
```

---

## 12. Hands-On Project 2: Student Management System

```dart
class Student {
  final String id;
  String name;
  int age;
  final Map<String, double> _grades = {};
  static int _studentCount = 0;

  Student({required this.name, required this.age})
    : id = 'STU${_studentCount++}${DateTime.now().millisecondsSinceEpoch.toString().substring(8)}';

  // Named constructor for transfer students
  Student.transfer({
    required this.name,
    required this.age,
    required Map<String, double> previousGrades,
  }) : id = 'STU${_studentCount++}${DateTime.now().millisecondsSinceEpoch.toString().substring(8)}' {
    _grades.addAll(previousGrades);
  }

  void addGrade(String subject, double grade) {
    if (grade < 0 || grade > 100) {
      print('❌ Grade must be between 0 and 100');
      return;
    }
    _grades[subject] = grade;
    print('✅ Added grade for $subject: $grade');
  }

  double? getGrade(String subject) => _grades[subject];

  double get averageGrade {
    if (_grades.isEmpty) return 0.0;
    return _grades.values.reduce((a, b) => a + b) / _grades.length;
  }

  String get letterGrade {
    double avg = averageGrade;
    if (avg >= 90) return 'A 🌟';
    if (avg >= 80) return 'B ⭐';
    if (avg >= 70) return 'C 🙂';
    if (avg >= 60) return 'D 😐';
    return 'F ❌';
  }

  Map<String, double> get grades => Map.unmodifiable(_grades);

  void printReportCard() {
    print('');
    print('╔═══════════════════════════════════════╗');
    print('║           REPORT CARD                 ║');
    print('╠═══════════════════════════════════════╣');
    print('║ Student ID: $id');
    print('║ Name:       $name');
    print('║ Age:        $age');
    print('╠═══════════════════════════════════════╣');
    print('║ SUBJECT          GRADE    STATUS');
    print('╠═══════════════════════════════════════╣');

    _grades.forEach((subject, grade) {
      String status = grade >= 60 ? 'PASS ✅' : 'FAIL ❌';
      print('║ ${subject.padRight(15)} ${grade.toStringAsFixed(1).padLeft(5)}    $status');
    });

    print('╠═══════════════════════════════════════╣');
    print('║ Average:     ${averageGrade.toStringAsFixed(1)}');
    print('║ Grade:       $letterGrade');
    print('╚═══════════════════════════════════════╝');
  }

  static int get studentCount => _studentCount;
}

class Classroom {
  final String className;
  final String teacherName;
  final List<Student> _students = [];
  final List<String> _subjects;

  Classroom({
    required this.className,
    required this.teacherName,
    required List<String> subjects,
  }) : _subjects = List.unmodifiable(subjects);

  void enroll(Student student) {
    _students.add(student);
    print('✅ ${student.name} enrolled in $className');
  }

  void removeStudent(String studentId) {
    _students.removeWhere((s) => s.id == studentId);
    print('🗑️  Student removed');
  }

  Student? findStudent(String studentId) {
    try {
      return _students.firstWhere((s) => s.id == studentId);
    } catch (e) {
      return null;
    }
  }

  double get classAverage {
    if (_students.isEmpty) return 0.0;
    return _students.map((s) => s.averageGrade).reduce((a, b) => a + b) / _students.length;
  }

  void printClassSummary() {
    print('');
    print('╔═══════════════════════════════════════╗');
    print('║         CLASSROOM SUMMARY             ║');
    print('╠═══════════════════════════════════════╣');
    print('║ Class:   $className');
    print('║ Teacher: $teacherName');
    print('║ Students: ${_students.length}');
    print('║ Subjects: ${_subjects.join(", ")}');
    print('║ Class Avg: ${classAverage.toStringAsFixed(1)}');
    print('╚═══════════════════════════════════════╝');

    for (var student in _students) {
      student.printReportCard();
    }
  }
}

void main() {
  // Create classroom
  var flutterClass = Classroom(
    className: 'Flutter Development 2026',
    teacherName: 'Senior Dev',
    subjects: ['Dart', 'Widgets', 'State Management', 'APIs', 'Testing'],
  );

  // Create students
  var student1 = Student(name: 'Kimi', age: 25);
  var student2 = Student(name: 'Alex', age: 22);
  var student3 = Student.transfer(
    name: 'Sam',
    age: 24,
    previousGrades: {'Dart': 85, 'Widgets': 90},
  );

  // Enroll
  flutterClass.enroll(student1);
  flutterClass.enroll(student2);
  flutterClass.enroll(student3);

  // Add grades
  student1.addGrade('Dart', 92);
  student1.addGrade('Widgets', 88);
  student1.addGrade('State Management', 95);

  student2.addGrade('Dart', 75);
  student2.addGrade('Widgets', 82);
  student2.addGrade('State Management', 78);

  student3.addGrade('State Management', 91);
  student3.addGrade('APIs', 87);

  // Print summary
  flutterClass.printClassSummary();

  print('');
  print('📊 Total students created: ${Student.studentCount}');
}
```

---

## 13. Common Mistakes & How to Avoid Them

### Mistake 1: Forgetting `required` on Named Parameters
```dart
// ❌ WRONG — name is optional (nullable)
void greet({String name}) { }

// ✅ CORRECT — name is required
void greet({required String name}) { }
```

### Mistake 2: Confusing Positional and Named Parameters
```dart
// ❌ WRONG — Can't mix incorrectly
void func(String a, {String b}, [String c]) { }
// Positional optional MUST come after named

// ✅ CORRECT
void func(String a, [String? b], {required String c}) { }
// Rule: Required positional → Optional positional → Named
```

### Mistake 3: Modifying `final` Fields After Construction
```dart
class User {
  final String name;

  User(this.name);

  void changeName(String newName) {
    // name = newName;  // ❌ ERROR — final can't change!
  }
}
```

### Mistake 4: Accessing Private Fields from Another File
```dart
// file: person.dart
class Person {
  String _secret = 'shhh';  // Private to this file
}

// file: main.dart
// import 'person.dart';
// var p = Person();
// print(p._secret);  // ❌ ERROR — _secret is private to person.dart
```

### Mistake 5: Not Using `const` Constructors When Possible
```dart
// ❌ Wasteful — creates new instance every time
var point = Point(0, 0);

// ✅ Efficient — reuses compile-time constant
const point = Point(0, 0);
```

### Mistake 6: Forgetting to Call `super()` in Subclass
```dart
// ❌ WRONG
class Dog extends Animal {
  String breed;
  Dog(this.breed);  // Missing super() call!
}

// ✅ CORRECT
class Dog extends Animal {
  String breed;
  Dog(String name, int age, this.breed) : super(name, age);
}
```

### Mistake 7: Arrow Function with Multiple Statements
```dart
// ❌ WRONG — Arrow functions can only have ONE expression
int calc(int x) => print(x); return x * 2;

// ✅ CORRECT — Use regular function body
int calc(int x) {
  print(x);
  return x * 2;
}
```

### Mistake 8: Using `new` Keyword (Optional in Dart)
```dart
// ❌ Old style — works but unnecessary
var person = new Person('Kimi', 25);

// ✅ Modern Dart
var person = Person('Kimi', 25);
```

---

## 14. Day 3 Checklist

Use this checklist to verify mastery:

- [ ] Can write functions with return types, parameters, and void
- [ ] Understands positional vs named vs optional parameters
- [ ] Can use `required` keyword for mandatory named parameters
- [ ] Can set default values for optional parameters
- [ ] Can write arrow functions for single-expression functions
- [ ] Understands higher-order functions (functions as parameters/returns)
- [ ] Can use `typedef` to name function types
- [ ] Understands closures and lexical scope
- [ ] Can define classes with fields and methods
- [ ] Understands private fields (`_` prefix) and encapsulation
- [ ] Can write getters and setters
- [ ] Can use static members (fields and methods)
- [ ] Can write default constructors
- [ ] Can write named constructors
- [ ] Can write factory constructors (singletons)
- [ ] Can write const constructors
- [ ] Can use redirecting constructors
- [ ] Understands `this` keyword and when it's required
- [ ] Can use initializer lists for final fields and validation
- [ ] Can call `super()` constructors via initializer list
- [ ] Built the Bank Account System with OOP principles
- [ ] Built the Student Management System with classes
- [ ] Can explain the 4 pillars of OOP with Dart examples
- [ ] Pushed both projects to GitHub

---

## 🧠 Key Takeaways (Memorize These!)

1. **Functions are first-class citizens** — You can pass them as parameters, return them, and store them in variables.

2. **Named parameters use `{ }`** and are optional by default. Use `required` to make them mandatory.

3. **Arrow functions (`=>`)** are for single expressions only. Use regular `{ }` for multiple statements.

4. **Classes are blueprints, objects are instances.** `Person` is a class, `Person('Kimi', 25)` is an object.

5. **`_` prefix makes things private** to the library (file). This is Dart's encapsulation mechanism.

6. **Constructors create objects.** Dart has 6 types: default, named, factory, const, redirecting, and private.

7. **`this` refers to the current instance.** Required when parameter names match field names.

8. **Initializer lists run before the constructor body.** Use them for `final` fields, validation, and `super()` calls.

9. **Static members belong to the class, not instances.** Access with `ClassName.member`.

10. **`const` constructors** create compile-time constants that are memory-efficient and can be reused.

---

## 📚 Extra Practice (Do These Tonight!)

1. **Library System:** Create `Book`, `Member`, and `Library` classes. Books can be borrowed/returned. Track due dates.

2. **E-Commerce Cart:** Create `Product`, `CartItem`, and `ShoppingCart` classes. Add/remove items, calculate totals with tax.

3. **Shape Calculator:** Create an abstract `Shape` class. Implement `Circle`, `Rectangle`, `Triangle`. Each calculates area/perimeter differently.

4. **Task Manager:** Create `Task` class with priority, due date, status. Create `Project` class that contains multiple tasks.

5. **Temperature Converter Class:** Create a `Temperature` class that can convert between Celsius, Fahrenheit, and Kelvin using named constructors.

---

> 🎉 **Congratulations!** You've completed Day 3. You now understand functions, classes, objects, constructors, and OOP basics. These concepts are the foundation of every Flutter widget you'll ever write.

**Next Up → Day 4: Dart OOP Advanced (Inheritance, Abstract Classes, Mixins, Extensions)**


# 📘 Day 4: Dart OOP Advanced — Complete Deep Dive
> **Goal:** Master advanced OOP concepts in Dart — the tools that separate beginners from professional developers.
> *This guide covers inheritance, abstraction, mixins, extensions, generics, and modern Dart 3 enums with real-world examples.*

---

## Table of Contents
1. [Why Advanced OOP Matters](#1-why-advanced-oop-matters)
2. [Inheritance (`extends`)](#2-inheritance-extends)
3. [Method Overriding (`@override`)](#3-method-overriding-override)
4. [The `super` Keyword Deep Dive](#4-the-super-keyword-deep-dive)
5. [Abstract Classes](#5-abstract-classes)
6. [Interfaces (`implements`)](#6-interfaces-implements)
7. [Mixins (`with`)](#7-mixins-with)
8. [Extension Methods](#8-extension-methods)
9. [Generics (`<T>`)](#9-generics-t)
10. [Enums & Enhanced Enums (Dart 3)](#10-enums--enhanced-enums-dart-3)
11. [Hands-On Project 1: Shape Hierarchy with Area Calculator](#11-hands-on-project-1-shape-hierarchy-with-area-calculator)
12. [Hands-On Project 2: E-Commerce System with Mixins & Generics](#12-hands-on-project-2-e-commerce-system-with-mixins--generics)
13. [Common Mistakes & How to Avoid Them](#13-common-mistakes--how-to-avoid-them)
14. [Day 4 Checklist](#14-day-4-checklist)

---

## 1. Why Advanced OOP Matters

### The Problem with Basic OOP
Basic classes work for simple apps. But real-world Flutter apps need:
- **Code reuse** across unrelated classes (Mixins)
- **Type safety** for collections and APIs (Generics)
- **Adding functionality** to existing classes without inheritance (Extensions)
- **Strict contracts** for plugin architectures (Interfaces)
- **State representation** with data (Enhanced Enums)

### How Flutter Uses These Concepts
| Concept | Flutter Example |
|---------|----------------|
| **Inheritance** | `StatelessWidget extends Widget` |
| **Abstract Class** | `Widget` is abstract — you can't instantiate it directly |
| **Mixin** | `TickerProviderStateMixin` for animations |
| **Interface** | Every class implicitly defines an interface |
| **Extension** | `BuildContext` extensions in packages |
| **Generic** | `List<T>`, `Map<K,V>`, `Future<T>` |
| **Enum** | `Brightness.light`, `Brightness.dark` |

> 💡 **Realization:** When you write `class MyApp extends StatelessWidget with TickerProviderStateMixin`, you're using inheritance, interfaces, AND mixins all at once!

---

## 2. Inheritance (`extends`)

### 2.1 What is Inheritance?

Inheritance allows a class to **acquire properties and methods** from another class. It represents an **"is-a"** relationship.

```
        Animal (Parent/Super/Base)
           │
    ┌──────┴──────┐
    │             │
   Dog           Cat
 (Child)       (Child)

Dog "is-a" Animal
Cat "is-a" Animal
```

### 2.2 Basic Inheritance

```dart
// Parent class (Superclass)
class Animal {
  String name;
  int age;

  Animal(this.name, this.age);

  void speak() {
    print('$name makes a sound');
  }

  void eat() {
    print('$name is eating');
  }

  void sleep() {
    print('$name is sleeping 💤');
  }
}

// Child class (Subclass) — inherits from Animal
class Dog extends Animal {
  String breed;

  // Call parent constructor using super
  Dog(String name, int age, this.breed) : super(name, age);

  void fetch() {
    print('$name is fetching the ball 🎾');
  }
}

// Another child class
class Cat extends Animal {
  String color;

  Cat(String name, int age, this.color) : super(name, age);

  void climb() {
    print('$name is climbing 🐱');
  }
}

void main() {
  var dog = Dog('Buddy', 3, 'Golden Retriever');
  var cat = Cat('Whiskers', 2, 'Orange');

  // Dog inherited methods from Animal
  dog.speak();   // Buddy makes a sound
  dog.eat();     // Buddy is eating
  dog.fetch();   // Buddy is fetching the ball 🎾

  // Cat inherited methods from Animal
  cat.speak();   // Whiskers makes a sound
  cat.climb();   // Whiskers is climbing 🐱

  // Type checking
  print(dog is Animal);  // true ✅
  print(dog is Dog);     // true ✅
  print(dog is Cat);     // false ❌

  print(cat is Animal);  // true ✅
}
```

### 2.3 Single Inheritance in Dart

Dart supports **single inheritance only** — a class can only extend ONE parent.

```dart
// ✅ CORRECT
class Dog extends Animal { }

// ❌ WRONG — Dart doesn't support multiple inheritance
// class Dog extends Animal, Pet { }

// ✅ Solution: Use mixins for multiple behaviors
class Dog extends Animal with PetMixin { }
```

### 2.4 The `is` and `as` Operators

```dart
void main() {
  Animal animal = Dog('Buddy', 3, 'Labrador');

  // 'is' checks type
  if (animal is Dog) {
    print('This is a dog!');
    animal.fetch();  // ✅ Works because of type promotion
  }

  // 'as' casts to a type (unsafe if wrong!)
  Dog dog = animal as Dog;
  dog.fetch();

  // Safe casting pattern
  if (animal is Cat) {
    (animal as Cat).climb();
  }
}
```

> ⚠️ **Warning:** `as` throws a runtime error if the cast is wrong. Always check with `is` first.

### 2.5 The `covariant` Keyword

Use `covariant` when a subclass wants to narrow the parameter type:

```dart
class Animal {
  void chase(Animal animal) {
    print('Animal chasing animal');
  }
}

class Cat extends Animal {
  // Cat can only chase mice, not any animal
  @override
  void chase(covariant Mouse mouse) {
    print('Cat chasing mouse 🐭');
  }
}

class Mouse extends Animal { }

void main() {
  var cat = Cat();
  cat.chase(Mouse());  // ✅ Works
  // cat.chase(Dog()); // ❌ Compile error — Dog is not a Mouse
}
```

---

## 3. Method Overriding (`@override`)

### 3.1 What is Overriding?

A child class **replaces** a parent method with its own implementation.

```dart
class Animal {
  String name;
  Animal(this.name);

  void speak() {
    print('$name makes a generic sound');
  }

  void describe() {
    print('I am an animal named $name');
  }
}

class Dog extends Animal {
  Dog(super.name);  // Shorthand for : super(name)

  @override
  void speak() {
    print('$name says: Woof! Woof! 🐕');
  }

  @override
  void describe() {
    print('I am a dog named $name and I am loyal ❤️');
  }
}

class Cat extends Animal {
  Cat(super.name);

  @override
  void speak() {
    print('$name says: Meow! 🐱');
  }
}

class Cow extends Animal {
  Cow(super.name);

  @override
  void speak() {
    print('$name says: Moo! 🐄');
  }
}

void main() {
  List<Animal> animals = [
    Dog('Buddy'),
    Cat('Whiskers'),
    Cow('Bessie'),
  ];

  // Polymorphism in action!
  for (var animal in animals) {
    animal.speak();
  }

  // Output:
  // Buddy says: Woof! Woof! 🐕
  // Whiskers says: Meow! 🐱
  // Bessie says: Moo! 🐄
}
```

### 3.2 The `@override` Annotation

Always use `@override` when overriding:
- ✅ Documents intent
- ✅ Catches typos (compile error if parent doesn't have the method)
- ✅ Improves readability

```dart
class Parent {
  void doSomething() { }
}

class Child extends Parent {
  @override
  void doSomething() { }  // ✅ Correct

  // @override
  // void dosomething() { }  // ❌ Compile error — typo caught!
}
```

### 3.3 Overriding Getters and Setters

```dart
class Rectangle {
  double width;
  double height;

  Rectangle(this.width, this.height);

  double get area => width * height;
  String get description => 'Rectangle: ${width}x${height}';
}

class Square extends Rectangle {
  Square(double side) : super(side, side);

  @override
  String get description => 'Square: side=${width}';
}

void main() {
  var square = Square(5);
  print(square.area);        // 25.0 (inherited)
  print(square.description); // Square: side=5.0 (overridden)
}
```

### 3.4 `noSuchMethod` — Handling Missing Methods

```dart
class Proxy {
  @override
  dynamic noSuchMethod(Invocation invocation) {
    print('Method ${invocation.memberName} was called');
    print('Arguments: ${invocation.positionalArguments}');
    return null;
  }
}

void main() {
  dynamic proxy = Proxy();
  proxy.doSomething('hello', 42);  // Intercepted!
}
```

---

## 4. The `super` Keyword Deep Dive

`super` refers to the **parent class**.

### 4.1 Calling Parent Constructor

```dart
class Vehicle {
  String brand;
  int year;

  Vehicle(this.brand, this.year);
}

class Car extends Vehicle {
  int doors;

  // Call parent constructor
  Car(String brand, int year, this.doors) : super(brand, year);

  // Named constructor calling parent named constructor
  Car.tesla(int year) : super('Tesla', year) {
    doors = 4;
  }
}
```

### 4.2 Calling Parent Methods

```dart
class Employee {
  String name;
  double salary;

  Employee(this.name, this.salary);

  void displayInfo() {
    print('Name: $name');
    print('Salary: \$$salary');
  }
}

class Manager extends Employee {
  String department;

  Manager(String name, double salary, this.department) 
    : super(name, salary);

  @override
  void displayInfo() {
    print('=== MANAGER INFO ===');
    super.displayInfo();  // Call parent's method
    print('Department: $department');
    print('===================');
  }
}

void main() {
  var manager = Manager('Alice', 90000, 'Engineering');
  manager.displayInfo();

  // Output:
  // === MANAGER INFO ===
  // Name: Alice
  // Salary: $90000
  // Department: Engineering
  // ===================
}
```

### 4.3 Accessing Parent Fields

```dart
class Parent {
  String message = 'Hello from Parent';
}

class Child extends Parent {
  String message = 'Hello from Child';

  void printMessages() {
    print(message);       // Hello from Child (this.message)
    print(super.message); // Hello from Parent (parent's field)
  }
}
```

### 4.4 `super` in Initializer Lists

```dart
class Point {
  final double x;
  final double y;

  const Point(this.x, this.y);
}

class ColoredPoint extends Point {
  final String color;

  ColoredPoint(double x, double y, this.color) : super(x, y);

  // Redirecting to parent const constructor
  const ColoredPoint.origin(this.color) : super(0, 0);
}
```

---

## 5. Abstract Classes

### 5.1 What is an Abstract Class?

An abstract class **cannot be instantiated**. It defines a **contract** that subclasses must follow.

```dart
// Abstract class — cannot create instances directly
abstract class Shape {
  // Abstract method — no body, MUST be overridden
  double get area;
  double get perimeter;

  // Concrete method — CAN be used directly
  void describe() {
    print('Area: $area, Perimeter: $perimeter');
  }

  // Concrete method that uses abstract properties
  void scale(double factor) {
    print('Scaling by $factor...');
    // Subclasses implement actual scaling
  }
}

// Concrete implementations
class Circle extends Shape {
  final double radius;

  Circle(this.radius);

  @override
  double get area => 3.14159 * radius * radius;

  @override
  double get perimeter => 2 * 3.14159 * radius;
}

class Rectangle extends Shape {
  final double width;
  final double height;

  Rectangle(this.width, this.height);

  @override
  double get area => width * height;

  @override
  double get perimeter => 2 * (width + height);
}

class Triangle extends Shape {
  final double a;
  final double b;
  final double c;

  Triangle(this.a, this.b, this.c);

  @override
  double get area {
    // Heron's formula
    double s = perimeter / 2;
    return sqrt(s * (s - a) * (s - b) * (s - c));
  }

  @override
  double get perimeter => a + b + c;
}

void main() {
  // var shape = Shape();  // ❌ ERROR — can't instantiate abstract class

  List<Shape> shapes = [
    Circle(5),
    Rectangle(10, 5),
    Triangle(3, 4, 5),
  ];

  for (var shape in shapes) {
    shape.describe();
  }

  // Output:
  // Area: 78.53975, Perimeter: 31.4159
  // Area: 50.0, Perimeter: 30.0
  // Area: 6.0, Perimeter: 12.0
}
```

### 5.2 Abstract Class with Constructor

```dart
abstract class DatabaseEntity {
  final String id;
  final DateTime createdAt;

  DatabaseEntity() 
    : id = _generateId(),
      createdAt = DateTime.now();

  static String _generateId() {
    return 'ID-${DateTime.now().millisecondsSinceEpoch}';
  }

  Map<String, dynamic> toJson();
}

class User extends DatabaseEntity {
  String name;
  String email;

  User(this.name, this.email);

  @override
  Map<String, dynamic> toJson() => {
    'id': id,
    'createdAt': createdAt.toIso8601String(),
    'name': name,
    'email': email,
  };
}

void main() {
  var user = User('Kimi', 'kimi@example.com');
  print(user.id);        // ID-...
  print(user.toJson());  // {id: ..., createdAt: ..., name: Kimi, email: ...}
}
```

### 5.3 Abstract Class vs Interface

```
┌─────────────────────────────────────────────────────────────┐
│         Abstract Class          vs        Interface         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  • Can have fields            │  • Can have fields          │
│  • Can have constructors      │  • NO constructors          │
│  • Can have method bodies     │  • NO method bodies         │
│  • Subclass: extends (1 only) │  • Implement: implements    │
│  • Partial implementation     │  • Full contract only       │
│  • "is-a" relationship        │  • "can-do" relationship    │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 6. Interfaces (`implements`)

### 6.1 Every Class is an Interface

In Dart, **every class implicitly defines an interface**. You can implement any class!

```dart
// A regular class that acts as an interface
class Printer {
  void printDocument(String content) {
    print('Printing: $content');
  }

  void scanDocument() {
    print('Scanning...');
  }
}

// Implementing the interface — MUST implement ALL methods
class PdfPrinter implements Printer {
  @override
  void printDocument(String content) {
    print('📄 Generating PDF: $content');
  }

  @override
  void scanDocument() {
    print('📄 PDF Scanner not supported');
  }
}

class NetworkPrinter implements Printer {
  final String ipAddress;

  NetworkPrinter(this.ipAddress);

  @override
  void printDocument(String content) {
    print('🌐 Sending to printer at $ipAddress: $content');
  }

  @override
  void scanDocument() {
    print('🌐 Scanning via network...');
  }
}

void main() {
  List<Printer> printers = [
    PdfPrinter(),
    NetworkPrinter('192.168.1.100'),
  ];

  for (var printer in printers) {
    printer.printDocument('Hello World');
  }
}
```

### 6.2 Implementing Multiple Interfaces

Unlike `extends`, you can `implement` multiple classes:

```dart
class Flyable {
  void fly() => print('Flying ✈️');
}

class Swimmable {
  void swim() => print('Swimming 🏊');
}

class Walkable {
  void walk() => print('Walking 🚶');
}

// Duck can fly, swim, AND walk!
class Duck implements Flyable, Swimmable, Walkable {
  @override
  void fly() => print('Duck flying 🦆✈️');

  @override
  void swim() => print('Duck swimming 🦆🏊');

  @override
  void walk() => print('Duck walking 🦆🚶');
}

void main() {
  var duck = Duck();
  duck.fly();   // Duck flying 🦆✈️
  duck.swim();  // Duck swimming 🦆🏊
  duck.walk();  // Duck walking 🦆🚶
}
```

### 6.3 True Interface with `abstract class`

Best practice: Define interfaces as abstract classes with no implementation:

```dart
abstract class Repository<T> {
  Future<T> getById(String id);
  Future<List<T>> getAll();
  Future<void> create(T item);
  Future<void> update(T item);
  Future<void> delete(String id);
}

abstract class Cacheable {
  void clearCache();
  bool get isCached;
}

// A concrete implementation
class UserRepository implements Repository<User>, Cacheable {
  final Map<String, User> _cache = {};

  @override
  Future<User> getById(String id) async {
    if (_cache.containsKey(id)) return _cache[id]!;
    // Fetch from API...
    return User(id: id, name: 'Kimi');
  }

  @override
  Future<List<User>> getAll() async => [];

  @override
  Future<void> create(User item) async { }

  @override
  Future<void> update(User item) async { }

  @override
  Future<void> delete(String id) async { }

  @override
  void clearCache() => _cache.clear();

  @override
  bool get isCached => _cache.isNotEmpty;
}

class User {
  final String id;
  final String name;
  User({required this.id, required this.name});
}
```

---

## 7. Mixins (`with`)

### 7.1 What is a Mixin?

A mixin is a way to **reuse code across multiple class hierarchies** without inheritance. It solves the "diamond problem" of multiple inheritance.

```
┌─────────────────────────────────────────────────────────────┐
│              MIXIN vs INHERITANCE                           │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  INHERITANCE (extends)          MIXIN (with)                │
│  ─────────────────────          ────────────                │
│  • "is-a" relationship          • "has-capability"          │
│  • Single only                  • Multiple allowed          │
│  • Tight coupling               • Loose coupling            │
│  • Dog is an Animal             • Dog can Fly (mixin)       │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### 7.2 Creating and Using Mixins

```dart
// Define a mixin using 'mixin' keyword
mixin Walkable {
  int steps = 0;

  void walk() {
    steps++;
    print('Walking... Step count: $steps 🚶');
  }

  void run() {
    steps += 2;
    print('Running... Step count: $steps 🏃');
  }
}

mixin Flyable {
  double maxAltitude = 1000;

  void fly() {
    print('Flying at $maxAltitude meters ✈️');
  }

  void land() {
    print('Landing safely 🛬');
  }
}

mixin Swimmable {
  void swim() {
    print('Swimming 🏊');
  }

  void dive() {
    print('Diving deep 🤿');
  }
}

// Use mixins with 'with'
class Human extends Mammal with Walkable {
  String name;
  Human(this.name);
}

class Bird extends Animal with Flyable, Walkable {
  String species;
  Bird(this.species) : super(species, 1);
}

class Duck extends Animal with Walkable, Flyable, Swimmable {
  Duck() : super('Duck', 2);
}

class Mammal extends Animal {
  Mammal(super.name, super.age);
}

void main() {
  var human = Human('Kimi');
  human.walk();   // From Walkable mixin
  human.run();    // From Walkable mixin

  var bird = Bird('Eagle');
  bird.fly();     // From Flyable mixin
  bird.walk();    // From Walkable mixin

  var duck = Duck();
  duck.walk();    // Walkable
  duck.fly();     // Flyable
  duck.swim();    // Swimmable
  duck.dive();    // Swimmable
}
```

### 7.3 Mixin with Constraints (`on`)

Restrict which classes can use the mixin:

```dart
// Only classes that extend/implements Animal can use this mixin
mixin PetBehavior on Animal {
  void pet() {
    print('Petting $name ❤️');  // Can access Animal's 'name' field
  }

  void feed() {
    print('Feeding $name 🍖');
  }
}

class Dog extends Animal with PetBehavior {
  Dog(super.name, super.age);
}

// class Robot with PetBehavior { }  // ❌ ERROR — Robot doesn't extend Animal

void main() {
  var dog = Dog('Buddy', 3);
  dog.pet();   // Petting Buddy ❤️
  dog.feed();  // Feeding Buddy 🍖
}
```

### 7.4 Mixin vs Abstract Class vs Interface

```dart
// Use 'mixin' when: Reusable behavior across unrelated classes
mixin Logger {
  void log(String message) => print('[LOG] $message');
}

// Use 'abstract class' when: Base class with shared implementation
abstract class Database {
  void connect();
  void disconnect() => print('Disconnected');
}

// Use 'implements' when: Defining a strict contract
class Cache {
  void get(String key) { }
  void set(String key, dynamic value) { }
}

// A class can use all three!
class AppService extends Database with Logger implements Cache {
  @override
  void connect() => log('Connecting...');

  @override
  void get(String key) => log('Getting $key');

  @override
  void set(String key, dynamic value) => log('Setting $key');
}
```

---

## 8. Extension Methods

### 8.1 What are Extension Methods?

Extension methods let you **add functionality to existing classes** without modifying them or using inheritance.

```dart
// Add methods to String
extension StringExtensions on String {
  // Capitalize first letter
  String get capitalize {
    if (isEmpty) return this;
    return '${this[0].toUpperCase()}${substring(1)}';
  }

  // Capitalize all words
  String get titleCase {
    return split(' ').map((word) => word.capitalize).join(' ');
  }

  // Check if valid email
  bool get isValidEmail {
    return contains('@') && contains('.');
  }

  // Reverse string
  String get reversed {
    return split('').reversed.join();
  }

  // Repeat string
  String repeat(int times) {
    return List.filled(times, this).join();
  }
}

void main() {
  print('hello'.capitalize);        // Hello
  print('hello world'.titleCase);   // Hello World
  print('test@email.com'.isValidEmail);  // true
  print('hello'.reversed);          // olleh
  print('ab'.repeat(3));            // ababab
}
```

### 8.2 Extension on Built-in Types

```dart
// Extensions on int
extension IntExtensions on int {
  // Check if even
  bool get isEvenNumber => this % 2 == 0;

  // Check if prime
  bool get isPrime {
    if (this < 2) return false;
    for (int i = 2; i <= sqrt(this); i++) {
      if (this % i == 0) return false;
    }
    return true;
  }

  // Times repetition
  void times(void Function(int) action) {
    for (int i = 0; i < this; i++) {
      action(i);
    }
  }

  // Duration helpers
  Duration get seconds => Duration(seconds: this);
  Duration get minutes => Duration(minutes: this);
  Duration get hours => Duration(hours: this);
  Duration get days => Duration(days: this);
}

// Extensions on List
extension ListExtensions<T> on List<T> {
  // Safe access
  T? get firstOrNull => isEmpty ? null : first;
  T? get lastOrNull => isEmpty ? null : last;

  // Random element
  T get random => this[Random().nextInt(length)];

  // Split into chunks
  List<List<T>> chunked(int size) {
    List<List<T>> chunks = [];
    for (int i = 0; i < length; i += size) {
      chunks.add(sublist(i, (i + size < length) ? i + size : length));
    }
    return chunks;
  }
}

void main() {
  // Int extensions
  print(7.isPrime);        // true
  print(10.isPrime);       // false

  3.times((i) => print('Hello $i'));
  // Hello 0
  // Hello 1
  // Hello 2

  print(5.minutes);        // Duration: 0:05:00

  // List extensions
  var numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  print(numbers.random);   // Random element
  print(numbers.chunked(3));  // [[1,2,3], [4,5,6], [7,8,9], [10]]
}
```

### 8.3 Extension with Name Conflicts

```dart
extension DateTimeFormatting on DateTime {
  String get formatted => '$year-${month.toString().padLeft(2, '0')}-${day.toString().padLeft(2, '0')}';
  String get timeOnly => '${hour.toString().padLeft(2, '0')}:${minute.toString().padLeft(2, '0')}';
}

void main() {
  var now = DateTime.now();
  print(now.formatted);   // 2026-08-04
  print(now.timeOnly);    // 14:30
}
```

> 🎯 **Flutter Context:** Extensions are heavily used in Flutter packages:
> ```dart
> // context.go('/home') — from GoRouter extension
> // 16.padding — from flutter_screenutil extension
> // 'assets/image.png'.svg — from flutter_svg extension
> ```

---

## 9. Generics (`<T>`)

### 9.1 What are Generics?

Generics allow you to write **type-safe, reusable code** that works with any type.

```
Without Generics              With Generics
─────────────────             ─────────────
List items = [];              List<String> items = []
items.add('hello');           items.add('hello') ✅
items.add(42);                items.add(42) ❌ Compile error!
String s = items[0];          String s = items[0] ✅
```

### 9.2 Generic Classes

```dart
// A generic Box that can hold any type
class Box<T> {
  T _content;

  Box(this._content);

  T get content => _content;

  void update(T newContent) {
    _content = newContent;
  }

  bool isSameType<X>() => _content is X;
}

void main() {
  var stringBox = Box<String>('Hello');
  var intBox = Box<int>(42);
  var doubleBox = Box<double>(3.14);

  print(stringBox.content);  // Hello
  print(intBox.content);     // 42

  stringBox.update('World');  // ✅ OK
  // stringBox.update(42);    // ❌ Compile error!

  print(stringBox.isSameType<String>());  // true
  print(stringBox.isSameType<int>());     // false
}
```

### 9.3 Generic Functions

```dart
// Generic function that swaps two values
void swap<T>(T a, T b) {
  T temp = a;
  a = b;
  b = temp;
  print('Swapped: a=$a, b=$b');
}

// Generic function that finds max
T findMax<T extends Comparable<T>>(List<T> items) {
  T max = items[0];
  for (var item in items) {
    if (item.compareTo(max) > 0) {
      max = item;
    }
  }
  return max;
}

// Generic function with multiple type parameters
Map<K, V> zipToMap<K, V>(List<K> keys, List<V> values) {
  Map<K, V> map = {};
  for (int i = 0; i < keys.length && i < values.length; i++) {
    map[keys[i]] = values[i];
  }
  return map;
}

void main() {
  swap<int>(10, 20);        // Swapped: a=20, b=10
  swap<String>('a', 'b');   // Swapped: a=b, b=a

  print(findMax([3, 1, 4, 1, 5]));           // 5
  print(findMax(['apple', 'banana', 'cherry']));  // cherry

  var map = zipToMap(['name', 'age'], ['Kimi', 25]);
  print(map);  // {name: Kimi, age: 25}
}
```

### 9.4 Generic Constraints (`extends`)

```dart
// T must be a Number or its subclass
class Calculator<T extends num> {
  T add(T a, T b) => (a + b) as T;
  T subtract(T a, T b) => (a - b) as T;
  T multiply(T a, T b) => (a * b) as T;
}

// T must implement Comparable
T findLargest<T extends Comparable<T>>(List<T> items) {
  return items.reduce((curr, next) => curr.compareTo(next) > 0 ? curr : next);
}

void main() {
  var calc = Calculator<int>();
  print(calc.add(5, 3));       // 8
  print(calc.multiply(4, 7));  // 28

  // var badCalc = Calculator<String>();  // ❌ ERROR — String doesn't extend num

  print(findLargest([10, 50, 30, 20]));              // 50
  print(findLargest(['zebra', 'apple', 'mango']));   // zebra
}
```

### 9.5 Generic in Flutter Context

```dart
// Generic API response wrapper
class ApiResponse<T> {
  final bool success;
  final T? data;
  final String? error;

  ApiResponse._({required this.success, this.data, this.error});

  factory ApiResponse.success(T data) => 
    ApiResponse._(success: true, data: data);

  factory ApiResponse.error(String error) => 
    ApiResponse._(success: false, error: error);
}

class User {
  final String name;
  User(this.name);
}

class Product {
  final String title;
  Product(this.title);
}

void main() {
  var userResponse = ApiResponse<User>.success(User('Kimi'));
  var productResponse = ApiResponse<Product>.success(Product('iPhone'));
  var errorResponse = ApiResponse<User>.error('Network failed');

  if (userResponse.success) {
    print(userResponse.data?.name);  // Kimi
  }

  if (errorResponse.success) {
    print(errorResponse.data);
  } else {
    print('Error: ${errorResponse.error}');  // Error: Network failed
  }
}
```

---

## 10. Enums & Enhanced Enums (Dart 3)

### 10.1 Basic Enums

```dart
enum Status { pending, approved, rejected }

void main() {
  var currentStatus = Status.pending;

  print(currentStatus);           // Status.pending
  print(currentStatus.name);      // 'pending' (Dart 2.15+)
  print(currentStatus.index);     // 0

  // Convert string to enum
  var fromString = Status.values.byName('approved');
  print(fromString);  // Status.approved

  // All values
  print(Status.values);  // [Status.pending, Status.approved, Status.rejected]

  // Switch on enum
  switch (currentStatus) {
    case Status.pending:
      print('⏳ Waiting for approval');
    case Status.approved:
      print('✅ Approved!');
    case Status.rejected:
      print('❌ Rejected');
  }
}
```

### 10.2 Enhanced Enums (Dart 3) — The Game Changer

Dart 3 enums can have **fields, methods, constructors, and even implement interfaces**!

```dart
enum Priority {
  low(1, 'Low', '🟢'),
  medium(2, 'Medium', '🟡'),
  high(3, 'High', '🔴'),
  critical(4, 'Critical', '🔥');

  // Fields
  final int level;
  final String label;
  final String icon;

  // Constructor
  const Priority(this.level, this.label, this.icon);

  // Methods
  bool get isUrgent => this == high || this == critical;

  bool canOverride(Priority other) => level > other.level;

  String get display => '$icon $label';

  // Factory constructor
  factory Priority.fromLevel(int level) {
    return values.firstWhere(
      (p) => p.level == level,
      orElse: () => Priority.low,
    );
  }
}

void main() {
  var taskPriority = Priority.high;

  print(taskPriority.display);        // 🔴 High
  print(taskPriority.isUrgent);       // true
  print(taskPriority.canOverride(Priority.low));  // true

  var fromLevel = Priority.fromLevel(2);
  print(fromLevel.display);           // 🟡 Medium

  // Sorting by priority level
  var tasks = [Priority.low, Priority.critical, Priority.medium];
  tasks.sort((a, b) => a.level.compareTo(b.level));
  print(tasks.map((p) => p.display).toList());
  // [🟢 Low, 🟡 Medium, 🔥 Critical]
}
```

### 10.3 Enum with Flutter Theme

```dart
enum AppTheme {
  light(
    primaryColor: 0xFF6200EE,
    backgroundColor: 0xFFFFFFFF,
    textColor: 0xFF000000,
    isDark: false,
  ),
  dark(
    primaryColor: 0xFFBB86FC,
    backgroundColor: 0xFF121212,
    textColor: 0xFFFFFFFF,
    isDark: true,
  ),
  blue(
    primaryColor: 0xFF2196F3,
    backgroundColor: 0xFFE3F2FD,
    textColor: 0xFF0D47A1,
    isDark: false,
  );

  final int primaryColor;
  final int backgroundColor;
  final int textColor;
  final bool isDark;

  const AppTheme({
    required this.primaryColor,
    required this.backgroundColor,
    required this.textColor,
    required this.isDark,
  });

  // Convert to Flutter Color
  Color get primary => Color(primaryColor);
  Color get background => Color(backgroundColor);
  Color get text => Color(textColor);
}

void main() {
  var theme = AppTheme.dark;
  print('Using ${theme.isDark ? "dark" : "light"} theme');
  print('Primary: #${theme.primaryColor.toRadixString(16)}');
}
```

### 10.4 Enum Implementing an Interface

```dart
abstract class Serializable {
  String toJson();
}

enum UserRole implements Serializable {
  admin,
  editor,
  viewer;

  @override
  String toJson() => '"$name"';

  bool get canEdit => this == admin || this == editor;
  bool get canDelete => this == admin;
}

void main() {
  var role = UserRole.editor;
  print(role.toJson());      // "editor"
  print(role.canEdit);       // true
  print(role.canDelete);     // false
}
```

---

## 11. Hands-On Project 1: Shape Hierarchy with Area Calculator

```dart
import 'dart:math';

// Abstract base class
abstract class Shape {
  String get name;
  double get area;
  double get perimeter;

  void describe() {
    print('$name: Area=${area.toStringAsFixed(2)}, Perimeter=${perimeter.toStringAsFixed(2)}');
  }
}

// Interface for shapes that can be colored
abstract class Colored {
  String get color;
  set color(String value);
}

// Interface for shapes that can be rotated
abstract class Rotatable {
  double get rotation;
  void rotate(double degrees);
}

// Circle
class Circle extends Shape {
  final double radius;

  Circle(this.radius);

  @override
  String get name => 'Circle';

  @override
  double get area => pi * radius * radius;

  @override
  double get perimeter => 2 * pi * radius;

  double get diameter => 2 * radius;
}

// Rectangle
class Rectangle extends Shape implements Colored, Rotatable {
  final double width;
  final double height;
  @override
  String color = 'black';
  @override
  double rotation = 0;

  Rectangle(this.width, this.height);

  @override
  String get name => 'Rectangle';

  @override
  double get area => width * height;

  @override
  double get perimeter => 2 * (width + height);

  bool get isSquare => width == height;

  @override
  void rotate(double degrees) {
    rotation = (rotation + degrees) % 360;
    print('Rotated to $rotation°');
  }
}

// Triangle
class Triangle extends Shape {
  final double a;
  final double b;
  final double c;

  Triangle(this.a, this.b, this.c);

  @override
  String get name => 'Triangle';

  @override
  double get area {
    double s = perimeter / 2;
    return sqrt(s * (s - a) * (s - b) * (s - c));
  }

  @override
  double get perimeter => a + b + c;

  bool get isValid {
    return (a + b > c) && (a + c > b) && (b + c > a);
  }

  bool get isEquilateral => a == b && b == c;
  bool get isIsosceles => a == b || b == c || a == c;
  bool get isRight {
    List<double> sides = [a, b, c]..sort();
    return pow(sides[0], 2) + pow(sides[1], 2) == pow(sides[2], 2);
  }
}

// Square (special rectangle)
class Square extends Rectangle {
  Square(double side) : super(side, side);

  @override
  String get name => 'Square';

  double get side => width;

  double get diagonal => width * sqrt(2);
}

// Shape calculator with generics
class ShapeCalculator<T extends Shape> {
  final List<T> _shapes = [];

  void add(T shape) => _shapes.add(shape);

  double get totalArea {
    return _shapes.fold(0, (sum, shape) => sum + shape.area);
  }

  double get totalPerimeter {
    return _shapes.fold(0, (sum, shape) => sum + shape.perimeter);
  }

  T? get largest {
    if (_shapes.isEmpty) return null;
    return _shapes.reduce((curr, next) => curr.area > next.area ? curr : next);
  }

  void printReport() {
    print('');
    print('╔═══════════════════════════════════════╗');
    print('║         SHAPE CALCULATOR REPORT       ║');
    print('╠═══════════════════════════════════════╣');
    for (var shape in _shapes) {
      shape.describe();
    }
    print('╠═══════════════════════════════════════╣');
    print('║ Total Shapes: ${_shapes.length}');
    print('║ Total Area: ${totalArea.toStringAsFixed(2)}');
    print('║ Total Perimeter: ${totalPerimeter.toStringAsFixed(2)}');
    print('║ Largest: ${largest?.name} (Area: ${largest?.area.toStringAsFixed(2)})');
    print('╚═══════════════════════════════════════╝');
  }
}

void main() {
  var calculator = ShapeCalculator<Shape>();

  calculator.add(Circle(5));
  calculator.add(Rectangle(10, 5));
  calculator.add(Triangle(3, 4, 5));
  calculator.add(Square(6));

  calculator.printReport();

  // Test specific shapes
  var rect = Rectangle(10, 5);
  rect.color = 'blue';
  rect.rotate(45);
  print('Rectangle color: ${rect.color}, rotation: ${rect.rotation}°');

  var tri = Triangle(3, 4, 5);
  print('Triangle is right: ${tri.isRight}');  // true (3-4-5 triangle!)
}
```

---

## 12. Hands-On Project 2: E-Commerce System with Mixins & Generics

```dart
import 'dart:math';

// Generic repository interface
abstract class Repository<T extends Entity> {
  final Map<String, T> _items = {};

  void save(T item) => _items[item.id] = item;
  T? findById(String id) => _items[id];
  List<T> getAll() => _items.values.toList();
  void delete(String id) => _items.remove(id);
}

// Base entity
abstract class Entity {
  String get id;
  DateTime get createdAt;
}

// Mixin for items that can be discounted
mixin Discountable {
  double get basePrice;
  double get discountPercent;

  double get discountedPrice => basePrice * (1 - discountPercent / 100);
  double get savings => basePrice - discountedPrice;

  bool get hasDiscount => discountPercent > 0;
}

// Mixin for items that can be reviewed
mixin Reviewable {
  final List<Review> _reviews = [];

  void addReview(Review review) => _reviews.add(review);

  double get averageRating {
    if (_reviews.isEmpty) return 0;
    return _reviews.map((r) => r.rating).reduce((a, b) => a + b) / _reviews.length;
  }

  List<Review> get reviews => List.unmodifiable(_reviews);
}

class Review {
  final String userId;
  final double rating;  // 1-5
  final String comment;
  final DateTime date;

  Review(this.userId, this.rating, this.comment) : date = DateTime.now();
}

// Product class
class Product extends Entity with Discountable, Reviewable {
  @override
  final String id;
  final String name;
  final String category;
  @override
  final double basePrice;
  @override
  final double discountPercent;
  int stockQuantity;
  @override
  final DateTime createdAt;

  Product({
    required this.name,
    required this.category,
    required this.basePrice,
    this.discountPercent = 0,
    this.stockQuantity = 0,
  })  : id = 'PROD-${Random().nextInt(90000) + 10000}',
        createdAt = DateTime.now();

  bool get isInStock => stockQuantity > 0;

  void reduceStock(int quantity) {
    if (quantity <= stockQuantity) {
      stockQuantity -= quantity;
    }
  }

  @override
  String toString() {
    var price = hasDiscount 
      ? '\$${discountedPrice.toStringAsFixed(2)} (was \$${basePrice.toStringAsFixed(2)})'
      : '\$${basePrice.toStringAsFixed(2)}';
    return '$name | $price | Stock: $stockQuantity | ⭐ ${averageRating.toStringAsFixed(1)}';
  }
}

// User class
class User extends Entity {
  @override
  final String id;
  final String name;
  final String email;
  @override
  final DateTime createdAt;
  final List<Order> _orders = [];

  User({required this.name, required this.email})
    : id = 'USR-${Random().nextInt(90000) + 10000}',
      createdAt = DateTime.now();

  void placeOrder(Order order) => _orders.add(order);
  List<Order> get orders => List.unmodifiable(_orders);
  double get totalSpent => _orders.fold(0, (sum, o) => sum + o.total);
}

// Order class
class Order extends Entity {
  @override
  final String id;
  final String userId;
  final List<OrderItem> items;
  final OrderStatus status;
  @override
  final DateTime createdAt;

  Order({required this.userId, required this.items, this.status = OrderStatus.pending})
    : id = 'ORD-${Random().nextInt(90000) + 10000}',
      createdAt = DateTime.now();

  double get total => items.fold(0, (sum, item) => sum + item.totalPrice);
  int get itemCount => items.fold(0, (sum, item) => sum + item.quantity);

  @override
  String toString() => 'Order $id | Items: $itemCount | Total: \$${total.toStringAsFixed(2)} | ${status.icon} ${status.label}';
}

class OrderItem {
  final Product product;
  final int quantity;

  OrderItem(this.product, this.quantity);

  double get totalPrice => product.discountedPrice * quantity;
}

enum OrderStatus {
  pending('Pending', '⏳'),
  processing('Processing', '🔧'),
  shipped('Shipped', '📦'),
  delivered('Delivered', '✅'),
  cancelled('Cancelled', '❌');

  final String label;
  final String icon;
  const OrderStatus(this.label, this.icon);

  bool get isFinal => this == delivered || this == cancelled;
}

// Generic product repository
class ProductRepository extends Repository<Product> {
  List<Product> findByCategory(String category) {
    return getAll().where((p) => p.category == category).toList();
  }

  List<Product> findOnSale() {
    return getAll().where((p) => p.hasDiscount).toList();
  }

  List<Product> search(String query) {
    return getAll().where((p) => p.name.toLowerCase().contains(query.toLowerCase())).toList();
  }
}

// Extensions for e-commerce
extension ProductListExtension on List<Product> {
  List<Product> get inStock => where((p) => p.isInStock).toList();
  List<Product> sortedByPrice({bool ascending = true}) {
    return [...this]..sort((a, b) => ascending 
      ? a.discountedPrice.compareTo(b.discountedPrice)
      : b.discountedPrice.compareTo(a.discountedPrice));
  }
  double get averagePrice => isEmpty ? 0 : map((p) => p.discountedPrice).reduce((a, b) => a + b) / length;
}

void main() {
  // Create products
  var phone = Product(
    name: 'FlutterPhone Pro',
    category: 'Electronics',
    basePrice: 999.99,
    discountPercent: 15,
    stockQuantity: 50,
  );

  var laptop = Product(
    name: 'DartBook Air',
    category: 'Electronics',
    basePrice: 1499.99,
    discountPercent: 10,
    stockQuantity: 20,
  );

  var book = Product(
    name: 'Flutter Mastery',
    category: 'Books',
    basePrice: 49.99,
    stockQuantity: 100,
  );

  // Add reviews
  phone.addReview(Review('u1', 5, 'Best phone ever!'));
  phone.addReview(Review('u2', 4, 'Great but expensive'));
  laptop.addReview(Review('u3', 5, 'Perfect for coding'));

  // Create repository
  var productRepo = ProductRepository();
  productRepo.save(phone);
  productRepo.save(laptop);
  productRepo.save(book);

  // Create user and order
  var user = User(name: 'Kimi', email: 'kimi@example.com');

  var order = Order(
    userId: user.id,
    items: [
      OrderItem(phone, 1),
      OrderItem(book, 2),
    ],
  );
  user.placeOrder(order);

  // Print results
  print('╔═══════════════════════════════════════╗');
  print('║      E-COMMERCE SYSTEM DEMO           ║');
  print('╚═══════════════════════════════════════╝');
  print('');

  print('📦 PRODUCTS:');
  for (var p in productRepo.getAll()) {
    print('  • $p');
  }

  print('');
  print('🏷️  ON SALE:');
  for (var p in productRepo.findOnSale()) {
    print('  • ${p.name} — Save \$${p.savings.toStringAsFixed(2)}!');
  }

  print('');
  print('👤 USER: ${user.name}');
  print('   Total Spent: \$${user.totalSpent.toStringAsFixed(2)}');
  for (var o in user.orders) {
    print('   $o');
  }

  print('');
  print('📊 STATS:');
  var allProducts = productRepo.getAll();
  print('   Total Products: ${allProducts.length}');
  print('   In Stock: ${allProducts.inStock.length}');
  print('   Average Price: \$${allProducts.averagePrice.toStringAsFixed(2)}');
}
```

---

## 13. Common Mistakes & How to Avoid Them

### Mistake 1: Instantiating Abstract Classes
```dart
// ❌ WRONG
var shape = Shape();  // Abstract classes can't be instantiated

// ✅ CORRECT
var circle = Circle(5);  // Instantiate concrete subclass
Shape shape = Circle(5);  // Polymorphism — reference as abstract type
```

### Mistake 2: Forgetting `@override`
```dart
class Dog extends Animal {
  // ❌ Missing @override — works but bad practice
  void speak() { }

  // ✅ Good practice
  @override
  void speak() { }
}
```

### Mistake 3: Multiple Inheritance Attempt
```dart
// ❌ WRONG — Dart doesn't support multiple extends
class Dog extends Animal, Pet { }

// ✅ CORRECT — Use mixin for additional behavior
class Dog extends Animal with PetMixin { }
```

### Mistake 4: Implementing Without Full Implementation
```dart
// ❌ WRONG — Missing methods
class MyCache implements Cache {
  void get(String key) { }  // Missing set()!
}

// ✅ CORRECT — Implement ALL methods
class MyCache implements Cache {
  void get(String key) { }
  void set(String key, value) { }
}
```

### Mistake 5: Using `extends` When You Need `implements`
```dart
// ❌ WRONG — Inherits implementation you don't want
class MockRepository extends RealRepository { }

// ✅ CORRECT — Fresh implementation
class MockRepository implements Repository { }
```

### Mistake 6: Generic Type Mismatch
```dart
// ❌ WRONG
List<String> names = ['Kimi'];
names.add(42);  // Compile error — good!

// But this runtime error:
var dynamicList = [];
dynamicList.add('hello');
dynamicList.add(42);
List<String> strings = dynamicList as List<String>;  // 💥 Runtime error!
```

### Mistake 7: Confusing `super` and `this`
```dart
class Child extends Parent {
  @override
  void doWork() {
    this.doWork();   // ❌ Infinite recursion — calls itself!
    super.doWork();  // ✅ Correct — calls parent's method
  }
}
```

### Mistake 8: Enum Values Not Exhaustive in Switch
```dart
// ❌ WRONG — Missing cases (compile error in Dart 3)
switch (status) {
  case Status.pending: print('Pending');
  case Status.approved: print('Approved');
}

// ✅ CORRECT — All cases covered or use default
switch (status) {
  case Status.pending: print('Pending');
  case Status.approved: print('Approved');
  case Status.rejected: print('Rejected');
}
```

---

## 14. Day 4 Checklist

Use this checklist to verify mastery:

- [ ] Can explain inheritance with `extends` and the "is-a" relationship
- [ ] Can override parent methods using `@override`
- [ ] Understands `is` and `as` operators for type checking/casting
- [ ] Can use `super` to call parent constructors and methods
- [ ] Can create abstract classes with abstract and concrete methods
- [ ] Understands when to use abstract class vs interface
- [ ] Can implement multiple interfaces with `implements`
- [ ] Can create and use mixins with `with`
- [ ] Understands mixin constraints using `on`
- [ ] Can create extension methods on any type
- [ ] Can write generic classes and functions with `<T>`
- [ ] Can constrain generics using `extends`
- [ ] Can create basic enums and use `.values`, `.name`, `.index`
- [ ] Can create enhanced enums with fields, methods, and constructors
- [ ] Can implement interfaces with enums
- [ ] Built the Shape Hierarchy with abstract classes and interfaces
- [ ] Built the E-Commerce System with mixins, generics, and enhanced enums
- [ ] Can explain the difference: extends vs implements vs with
- [ ] Can choose the right OOP tool for any scenario
- [ ] Pushed both projects to GitHub

---

## 🧠 Key Takeaways (Memorize These!)

1. **`extends` = "is-a"** — Single inheritance only. Use for true parent-child relationships.

2. **`implements` = "can-do"** — Implement multiple interfaces. Must implement ALL methods.

3. **`with` = "has-capability"** — Add behavior without inheritance. Multiple mixins allowed.

4. **Abstract classes** define contracts with optional shared code. Can't be instantiated.

5. **`@override`** is not optional in your mental model — always use it for clarity and safety.

6. **`super`** calls the parent. Use in constructors (`super()`) and methods (`super.method()`).

7. **Extensions** add methods to existing classes without inheritance — perfect for utilities.

8. **Generics** (`<T>`) make code type-safe and reusable — always use them for collections.

9. **Enhanced enums** (Dart 3) can have fields, methods, constructors — they're full classes now.

10. **Choose the right tool:** extends for hierarchy, implements for contracts, mixins for shared behavior, extensions for utility methods.

---

## 📚 Extra Practice (Do These Tonight!)

1. **Payment System:** Create abstract `PaymentMethod`. Implement `CreditCard`, `PayPal`, `Crypto`. Use mixin for `Refundable`.

2. **Notification System:** Create `Notification` interface. Implement `EmailNotification`, `PushNotification`, `SMSNotification`. Use generic `NotificationQueue<T>`.

3. **File Parser:** Create extension methods on `String` for `toSnakeCase()`, `toCamelCase()`, `isValidUrl()`. Create generic `Parser<T>`.

4. **Game Characters:** Create abstract `Character`. Use mixin for `WarriorSkills`, `MageSkills`, `HealerSkills`. Create `Player` that can mix abilities.

5. **API Client:** Create generic `ApiClient<T>` with `get()`, `post()`, `put()`, `delete()`. Use enum for `HttpStatus` with code and message.

---

> 🎉 **Congratulations!** You've completed Day 4. You now understand advanced OOP concepts that professional Dart developers use daily. These patterns appear in every Flutter app, package, and framework.

**Next Up → Day 5: Dart Advanced — Async, Collections & Functional Programming**




