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

# 📘 Day 5: Dart Advanced — Async, Collections & Functional Programming
> **Goal:** Master asynchronous programming, functional collections, and modern Dart 3 features.
> *This guide covers Future, Stream, error handling, records, patterns, and real-world JSON parsing.*

---

## Table of Contents
1. [Why Async Matters in Flutter](#1-why-async-matters-in-flutter)
2. [Synchronous vs Asynchronous Programming](#2-synchronous-vs-asynchronous-programming)
3. [Future Deep Dive](#3-future-deep-dive)
4. [async & await](#4-async--await)
5. [Future Methods & Chaining](#5-future-methods--chaining)
6. [Stream Deep Dive](#6-stream-deep-dive)
7. [Stream Methods & Transformations](#7-stream-methods--transformations)
8. [Error Handling in Dart](#8-error-handling-in-dart)
9. [Functional Programming with Collections](#9-functional-programming-with-collections)
10. [Records (Dart 3)](#10-records-dart-3)
11. [Patterns & Pattern Matching (Dart 3)](#11-patterns--pattern-matching-dart-3)
12. [Hands-On Project 1: Async JSON Data Fetcher](#12-hands-on-project-1-async-json-data-fetcher)
13. [Hands-On Project 2: Real-Time Stream Dashboard](#13-hands-on-project-2-real-time-stream-dashboard)
14. [Common Mistakes & How to Avoid Them](#14-common-mistakes--how-to-avoid-them)
15. [Day 5 Checklist](#15-day-5-checklist)

---

## 1. Why Async Matters in Flutter

### The Problem
Mobile apps are **single-threaded** by default. If you do heavy work (network requests, file I/O) on the main thread, your UI **freezes**.

```
❌ SYNCHRONOUS (UI Freezes)
┌─────────────────────────────────────────────┐
│  Main Thread                                │
│  ├── Build UI                               │
│  ├── Fetch data from API (5 seconds)        │
│  │   ← UI FROZEN! User can't interact!      │
│  ├── Parse JSON                             │
│  ├── Update UI                              │
│  └── ...                                    │
└─────────────────────────────────────────────┘

✅ ASYNCHRONOUS (UI Smooth)
┌─────────────────────────────────────────────┐
│  Main Thread          │  Background Task    │
│  ├── Build UI         │                     │
│  ├── Start API call ──┼──→ Fetch data       │
│  ├── Build UI (60fps) │   (5 seconds)       │
│  ├── Build UI (60fps) │   Parse JSON        │
│  ←── Receive result ──┼── Return data       │
│  ├── Update UI        │                     │
│  └── ...              │                     │
└─────────────────────────────────────────────┘
```

### Where Async is Used in Flutter
| Scenario | Flutter Example |
|----------|----------------|
| **API Calls** | `http.get()`, `dio.get()` |
| **Database** | `sqflite` queries, `hive` reads |
| **File I/O** | `readAsString()`, `writeAsString()` |
| **SharedPreferences** | `prefs.getString()`, `prefs.setString()` |
| **Animations** | `AnimationController`, `Future.delayed()` |
| **Navigation** | `Navigator.push()`, `showDialog()` |
| **Image Loading** | `CachedNetworkImage`, `Image.network()` |

> 💡 **Rule:** Any operation that takes > 16ms (1 frame at 60fps) should be async.

---

## 2. Synchronous vs Asynchronous Programming

### Synchronous Code
```dart
void main() {
  print('Step 1: Start');

  // This blocks everything until done
  String data = fetchDataSync();  // Takes 3 seconds
  print('Step 2: Got data: $data');

  print('Step 3: Done');
}

String fetchDataSync() {
  // Simulating slow operation
  sleep(Duration(seconds: 3));  // Blocks the thread!
  return 'User Data';
}

// Output (takes 3 seconds, UI frozen):
// Step 1: Start
// [3 seconds of frozen UI]
// Step 2: Got data: User Data
// Step 3: Done
```

### Asynchronous Code
```dart
Future<void> main() async {
  print('Step 1: Start');

  // This does NOT block — other code can run
  String data = await fetchDataAsync();  // Takes 3 seconds
  print('Step 2: Got data: $data');

  print('Step 3: Done');
}

Future<String> fetchDataAsync() async {
  await Future.delayed(Duration(seconds: 3));  // Non-blocking wait
  return 'User Data';
}

// Output:
// Step 1: Start
// [UI continues running smoothly for 3 seconds]
// Step 2: Got data: User Data
// Step 3: Done
```

---

## 3. Future Deep Dive

### 3.1 What is a Future?

A `Future` is a **promise** that a value will be available at some point in the future. It's either:
- **Pending** — waiting to complete
- **Completed with value** — success
- **Completed with error** — failure

```
┌─────────────────────────────────────────────────────────────┐
│                    Future Lifecycle                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│   Future<String> ──→ Pending ──→ Completed(String) ✅       │
│                      │                                        │
│                      └─→ Completed(Error) ❌                │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### 3.2 Creating Futures

```dart
void main() {
  // Future that completes immediately with a value
  Future<String> immediate = Future.value('Hello');

  // Future that completes with an error
  Future<String> errorFuture = Future.error('Something went wrong');

  // Future that completes after a delay
  Future<String> delayed = Future.delayed(
    Duration(seconds: 2),
    () => 'Delayed result',
  );

  // Future from an async operation
  Future<String> fromAsync = fetchUserData();
}

Future<String> fetchUserData() async {
  await Future.delayed(Duration(seconds: 1));
  return 'User: Kimi';
}
```

### 3.3 Future States

```dart
void main() {
  var future = Future.delayed(Duration(seconds: 2), () => 'Done');

  // At this point, future is PENDING
  print(future);  // Instance of 'Future<String>'

  // After 2 seconds, it completes with 'Done'
  future.then((value) {
    print('Completed with: $value');  // Done
  });
}
```

### 3.4 Future with Microtasks

```dart
void main() {
  print('1. Start');

  // Microtask runs before the next event loop iteration
  Future.microtask(() => print('2. Microtask'));

  // Regular Future goes to event queue
  Future(() => print('3. Regular Future'));

  print('4. End');

  // Output:
  // 1. Start
  // 4. End
  // 2. Microtask
  // 3. Regular Future
}
```

> 🎯 **Event Loop Priority:** Synchronous code → Microtasks → Event queue (Futures, Timers)

---

## 4. async & await

### 4.1 The `async` Keyword

Mark a function with `async` to:
1. Allow using `await` inside it
2. Automatically wrap the return value in a `Future`

```dart
// Without async — returns String
String getName() {
  return 'Kimi';
}

// With async — returns Future<String>
Future<String> getNameAsync() async {
  return 'Kimi';  // Automatically wrapped in Future.value()
}

void main() {
  print(getName());        // Kimi
  print(getNameAsync());   // Instance of 'Future<String>'
}
```

### 4.2 The `await` Keyword

`await` **pauses** the function execution until the Future completes, **without blocking** other code.

```dart
Future<void> fetchUserProfile() async {
  print('Fetching user...');

  // Pause here, but DON'T block other code
  String user = await fetchUserFromAPI();
  print('User: $user');

  // Pause here again
  String orders = await fetchOrdersForUser(user);
  print('Orders: $orders');

  print('Done!');
}

Future<String> fetchUserFromAPI() async {
  await Future.delayed(Duration(seconds: 1));
  return 'Kimi';
}

Future<String> fetchOrdersForUser(String user) async {
  await Future.delayed(Duration(seconds: 1));
  return '5 orders';
}

void main() async {
  await fetchUserProfile();

  // Output (takes ~2 seconds total):
  // Fetching user...
  // [1 second passes]
  // User: Kimi
  // [1 second passes]
  // Orders: 5 orders
  // Done!
}
```

### 4.3 Sequential vs Parallel Execution

```dart
// SEQUENTIAL — one after another (slower)
Future<void> sequentialFetch() async {
  var stopwatch = Stopwatch()..start();

  var users = await fetchUsers();      // 1 second
  var posts = await fetchPosts();      // 1 second
  var comments = await fetchComments(); // 1 second

  stopwatch.stop();
  print('Sequential: ${stopwatch.elapsedMilliseconds}ms');  // ~3000ms
}

// PARALLEL — all at once (faster!)
Future<void> parallelFetch() async {
  var stopwatch = Stopwatch()..start();

  // Start all futures simultaneously
  var usersFuture = fetchUsers();
  var postsFuture = fetchPosts();
  var commentsFuture = fetchComments();

  // Wait for all to complete
  var users = await usersFuture;
  var posts = await postsFuture;
  var comments = await commentsFuture;

  stopwatch.stop();
  print('Parallel: ${stopwatch.elapsedMilliseconds}ms');  // ~1000ms
}

// EVEN BETTER — using Future.wait
Future<void> parallelFetchBetter() async {
  var stopwatch = Stopwatch()..start();

  var results = await Future.wait([
    fetchUsers(),
    fetchPosts(),
    fetchComments(),
  ]);

  stopwatch.stop();
  print('Future.wait: ${stopwatch.elapsedMilliseconds}ms');  // ~1000ms
}

Future<String> fetchUsers() => Future.delayed(Duration(seconds: 1), () => 'Users');
Future<String> fetchPosts() => Future.delayed(Duration(seconds: 1), () => 'Posts');
Future<String> fetchComments() => Future.delayed(Duration(seconds: 1), () => 'Comments');

void main() async {
  await sequentialFetch();
  await parallelFetch();
  await parallelFetchBetter();
}
```

### 4.4 `Future.wait` with Error Handling

```dart
Future<void> fetchAllData() async {
  try {
    // If ANY future fails, the whole wait fails
    var results = await Future.wait([
      fetchUsers(),
      fetchPosts(),
      fetchComments(),
    ]);
    print('All succeeded: $results');
  } catch (e) {
    print('One failed: $e');
  }

  // With eagerError: true — fail fast on first error
  try {
    var results = await Future.wait([
      fetchUsers(),
      fetchPosts(),
      Future.error('Comments failed!'),
    ], eagerError: true);
  } catch (e) {
    print('Failed fast: $e');
  }
}
```

### 4.5 `Future.any` — First to Complete Wins

```dart
Future<String> fetchWithTimeout() async {
  return await Future.any([
    fetchDataFromServer(),
    Future.delayed(Duration(seconds: 5), () => throw 'Timeout!'),
  ]);
}

Future<String> fetchDataFromServer() async {
  await Future.delayed(Duration(seconds: 2));
  return 'Server data';
}
```

---

## 5. Future Methods & Chaining

### 5.1 `then()` — Handle Success

```dart
void main() {
  fetchUser()
    .then((user) {
      print('Got user: $user');
      return fetchOrders(user);  // Return another Future
    })
    .then((orders) {
      print('Got orders: $orders');
    });
}

Future<String> fetchUser() => Future.delayed(Duration(seconds: 1), () => 'Kimi');
Future<String> fetchOrders(String user) => Future.delayed(Duration(seconds: 1), () => '5 orders');
```

### 5.2 `catchError()` — Handle Errors

```dart
void main() {
  riskyOperation()
    .then((value) => print('Success: $value'))
    .catchError((error) {
      print('Error caught: $error');
      return 'Default value';  // Provide fallback
    })
    .then((value) => print('Final value: $value'));
}

Future<String> riskyOperation() {
  return Future.error('Network failed');
}

// Output:
// Error caught: Network failed
// Final value: Default value
```

### 5.3 `whenComplete()` — Always Runs

```dart
void main() {
  fetchData()
    .then((data) => print('Data: $data'))
    .catchError((error) => print('Error: $error'))
    .whenComplete(() => print('Cleanup: Close connection'));
}

Future<String> fetchData() => Future.error('Failed');

// Output:
// Error: Failed
// Cleanup: Close connection
```

### 5.4 `timeout()` — Add Time Limit

```dart
Future<void> fetchWithTimeout() async {
  try {
    var data = await fetchSlowData()
      .timeout(Duration(seconds: 2));
    print('Data: $data');
  } on TimeoutException {
    print('Request timed out!');
  }
}

Future<String> fetchSlowData() => Future.delayed(Duration(seconds: 5), () => 'Data');
```

### 5.5 Future Chaining Summary

```dart
Future<String> operation = fetchData();

operation
  .then((value) => process(value))     // Transform success
  .catchError((e) => handleError(e))   // Handle failure
  .whenComplete(() => cleanup())       // Always run
  .timeout(Duration(seconds: 5));      // Add deadline
```

---

## 6. Stream Deep Dive

### 6.1 What is a Stream?

A `Stream` is a **sequence of asynchronous events**. While a `Future` delivers a single value, a `Stream` delivers **multiple values over time**.

```
┌─────────────────────────────────────────────────────────────┐
│              Future vs Stream                               │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Future<int> ──→ single value ──→ 42                       │
│                                                             │
│  Stream<int> ──→ multiple values ──→ 1, 2, 3, 4, 5...      │
│                                                             │
│  Think: Future = single download                            │
│        Stream = live video feed                             │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### 6.2 Creating Streams

```dart
import 'dart:async';

void main() {
  // Stream from iterable
  Stream<int> numberStream = Stream.fromIterable([1, 2, 3, 4, 5]);

  // Stream from Future
  Stream<String> futureStream = Stream.fromFuture(Future.value('Hello'));

  // Stream with periodic events
  Stream<int> timerStream = Stream.periodic(
    Duration(seconds: 1),
    (count) => count,
  );

  // Stream controller (manual control)
  StreamController<String> controller = StreamController<String>();
  controller.add('Event 1');
  controller.add('Event 2');
  controller.close();

  // Async generator (yield)
  Stream<int> asyncGenerator() async* {
    for (int i = 0; i < 5; i++) {
      await Future.delayed(Duration(seconds: 1));
      yield i;  // Emit value
    }
  }
}
```

### 6.3 Listening to Streams

```dart
void main() async {
  Stream<int> stream = Stream.fromIterable([1, 2, 3, 4, 5]);

  // Method 1: await for (async generator style)
  await for (int value in stream) {
    print('Received: $value');
  }

  // Method 2: listen() (callback style)
  Stream<int> stream2 = Stream.fromIterable([10, 20, 30]);
  stream2.listen(
    (value) => print('Data: $value'),     // onData
    onError: (error) => print('Error: $error'),  // onError
    onDone: () => print('Stream closed'),   // onDone
    cancelOnError: false,
  );
}
```

### 6.4 Single-Subscription vs Broadcast Streams

```dart
void main() {
  // Single-subscription stream (default)
  Stream<int> single = Stream.fromIterable([1, 2, 3]);

  single.listen((v) => print('Listener 1: $v'));
  // single.listen((v) => print('Listener 2: $v'));  // ❌ ERROR!

  // Broadcast stream (multiple listeners)
  StreamController<int> broadcastController = StreamController<int>.broadcast();
  Stream<int> broadcast = broadcastController.stream;

  broadcast.listen((v) => print('A: $v'));
  broadcast.listen((v) => print('B: $v'));  // ✅ OK!

  broadcastController.add(1);
  broadcastController.add(2);
  broadcastController.close();

  // Convert single to broadcast
  Stream<int> singleStream = Stream.fromIterable([1, 2, 3]);
  Stream<int> asBroadcast = singleStream.asBroadcastStream();

  asBroadcast.listen((v) => print('X: $v'));
  asBroadcast.listen((v) => print('Y: $v'));  // ✅ Works!
}
```

### 6.5 Stream Subscriptions

```dart
void main() async {
  StreamController<int> controller = StreamController<int>();

  // Get a subscription
  StreamSubscription<int> subscription = controller.stream.listen(
    (value) => print('Value: $value'),
  );

  controller.add(1);
  controller.add(2);

  // Pause the stream
  subscription.pause();
  controller.add(3);  // Not received while paused

  // Resume the stream
  await Future.delayed(Duration(seconds: 1));
  subscription.resume();

  controller.add(4);  // Received

  // Cancel subscription
  await subscription.cancel();
  controller.add(5);  // Not received

  controller.close();
}
```

---

## 7. Stream Methods & Transformations

### 7.1 Transforming Streams

```dart
void main() async {
  Stream<int> numbers = Stream.fromIterable([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]);

  // map: Transform each value
  var doubled = numbers.map((n) => n * 2);
  print(await doubled.toList());  // [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]

  // where: Filter values
  var evens = numbers.where((n) => n.isEven);
  print(await evens.toList());  // [2, 4, 6, 8, 10]

  // take: Take first N values
  var first3 = numbers.take(3);
  print(await first3.toList());  // [1, 2, 3]

  // skip: Skip first N values
  var skip3 = numbers.skip(3);
  print(await skip3.toList());  // [4, 5, 6, 7, 8, 9, 10]

  // takeWhile: Take while condition is true
  var lessThan5 = numbers.takeWhile((n) => n < 5);
  print(await lessThan5.toList());  // [1, 2, 3, 4]

  // skipWhile: Skip while condition is true
  var from5 = numbers.skipWhile((n) => n < 5);
  print(await from5.toList());  // [5, 6, 7, 8, 9, 10]

  // distinct: Remove consecutive duplicates
  Stream<int> withDups = Stream.fromIterable([1, 1, 2, 2, 2, 3, 3]);
  print(await withDups.distinct().toList());  // [1, 2, 3]

  // expand: Flatten nested streams
  var expanded = numbers.expand((n) => [n, n * 10]);
  print(await expanded.toList());  // [1, 10, 2, 20, 3, 30, ...]
}
```

### 7.2 Combining Streams

```dart
void main() async {
  // merge: Combine multiple streams
  Stream<int> stream1 = Stream.periodic(Duration(seconds: 1), (i) => i).take(3);
  Stream<int> stream2 = Stream.periodic(Duration(milliseconds: 500), (i) => i + 100).take(3);

  // StreamGroup.merge from async package (or custom)

  // zip: Combine latest from multiple streams
  // Use RxDart or combineLatest

  // concat: One after another
  var concatenated = Stream.fromIterable([1, 2, 3]).followedBy(Stream.fromIterable([4, 5, 6]));
  print(await concatenated.toList());  // [1, 2, 3, 4, 5, 6]
}
```

### 7.3 Stream.reduce & Stream.fold

```dart
void main() async {
  Stream<int> numbers = Stream.fromIterable([1, 2, 3, 4, 5]);

  // reduce: Combine to single value (first element is initial)
  int sum = await numbers.reduce((a, b) => a + b);
  print('Sum: $sum');  // 15

  // fold: Combine with custom initial value
  Stream<int> moreNumbers = Stream.fromIterable([1, 2, 3, 4, 5]);
  int product = await moreNumbers.fold(1, (a, b) => a * b);
  print('Product: $product');  // 120

  // Collect to list
  Stream<int> allNumbers = Stream.fromIterable([1, 2, 3, 4, 5]);
  List<int> list = await allNumbers.toList();
  print('List: $list');  // [1, 2, 3, 4, 5]

  // Join to string
  Stream<String> words = Stream.fromIterable(['Hello', 'Flutter', 'World']);
  String sentence = await words.join(' ');
  print(sentence);  // Hello Flutter World
}
```

### 7.4 StreamBuilder Basics (Flutter Context)

```dart
// In Flutter, you'll use StreamBuilder like this:
/*
StreamBuilder<int>(
  stream: counterStream,
  builder: (context, snapshot) {
    if (snapshot.hasError) {
      return Text('Error: ${snapshot.error}');
    }
    if (snapshot.connectionState == ConnectionState.waiting) {
      return CircularProgressIndicator();
    }
    return Text('Count: ${snapshot.data}');
  },
)
*/

// Connection states:
// - none: No stream attached
// - waiting: Waiting for first event
// - active: Receiving events
// - done: Stream closed
```

---

## 8. Error Handling in Dart

### 8.1 try / catch / finally

```dart
Future<void> fetchData() async {
  try {
    // Code that might throw
    var response = await httpGet('/api/data');
    var data = jsonDecode(response);
    print('Data: $data');
  } catch (e) {
    // Catch ANY error
    print('Error occurred: $e');
  } finally {
    // ALWAYS runs (cleanup)
    print('Closing connection...');
  }
}
```

### 8.2 Catching Specific Errors (`on`)

```dart
Future<void> fetchDataSafely() async {
  try {
    var response = await httpGet('/api/data');
    var data = jsonDecode(response);
    processData(data);
  } on FormatException catch (e) {
    // Specific error type
    print('JSON format error: $e');
  } on TimeoutException catch (e) {
    print('Request timed out: $e');
  } on SocketException catch (e) {
    print('Network error: $e');
  } catch (e, stackTrace) {
    // Catch-all with stack trace
    print('Unexpected error: $e');
    print('Stack: $stackTrace');
  } finally {
    print('Request completed');
  }
}
```

### 8.3 `rethrow` — Propagate Errors

```dart
Future<void> processUserData() async {
  try {
    var user = await fetchUser();
    await validateUser(user);
    await saveUser(user);
  } catch (e) {
    // Log the error locally
    print('Processing failed: $e');
    // But let caller handle it too
    rethrow;  // Propagates the error up the call stack
  }
}

void main() async {
  try {
    await processUserData();
  } catch (e) {
    print('Main caught: $e');  // Same error, caught here too
  }
}
```

### 8.4 Error Handling in Futures

```dart
void main() {
  // Method 1: try-catch with await
  fetchData().then((data) {
    print(data);
  }).catchError((error) {
    print('Error: $error');
  });

  // Method 2: try-catch in async function
  fetchSafely();
}

Future<void> fetchSafely() async {
  try {
    var data = await fetchData();
    print(data);
  } catch (e) {
    print('Caught: $e');
  }
}
```

### 8.5 Custom Exceptions

```dart
// Define custom exception
class NetworkException implements Exception {
  final String message;
  final int statusCode;

  NetworkException(this.message, this.statusCode);

  @override
  String toString() => 'NetworkException: $message (Status: $statusCode)';
}

class ValidationException implements Exception {
  final String field;
  final String message;

  ValidationException(this.field, this.message);

  @override
  String toString() => 'ValidationException: $field - $message';
}

// Usage
Future<void> fetchUser() async {
  var response = await httpGet('/api/user');
  if (response.statusCode != 200) {
    throw NetworkException('Failed to fetch user', response.statusCode);
  }
  if (response.body.isEmpty) {
    throw ValidationException('user', 'User data is empty');
  }
}
```

### 8.6 Result Pattern (Functional Error Handling)

```dart
// Instead of throwing, return a Result type
sealed class Result<T> {
  const Result();
}

class Success<T> extends Result<T> {
  final T data;
  const Success(this.data);
}

class Failure<T> extends Result<T> {
  final String message;
  final Exception? exception;
  const Failure(this.message, {this.exception});
}

// Usage
Future<Result<String>> fetchDataSafe() async {
  try {
    var data = await httpGet('/api/data');
    return Success(data);
  } catch (e) {
    return Failure('Failed to fetch data', exception: e as Exception?);
  }
}

void main() async {
  var result = await fetchDataSafe();

  switch (result) {
    case Success<String>(data: var data):
      print('Success: $data');
    case Failure<String>(message: var msg):
      print('Failed: $msg');
  }
}
```

---

## 9. Functional Programming with Collections

### 9.1 Collection Operations Master List

```dart
void main() {
  List<int> numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

  // map: Transform each element
  var squares = numbers.map((n) => n * n);
  print(squares.toList());  // [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

  // where: Filter elements
  var evens = numbers.where((n) => n % 2 == 0);
  print(evens.toList());  // [2, 4, 6, 8, 10]

  // reduce: Combine to single value
  var sum = numbers.reduce((a, b) => a + b);
  print(sum);  // 55

  // fold: Reduce with initial value
  var product = numbers.fold(1, (a, b) => a * b);
  print(product);  // 3628800

  // any: At least one matches?
  print(numbers.any((n) => n > 8));  // true

  // every: All match?
  print(numbers.every((n) => n > 0));  // true

  // firstWhere: Find first match
  var firstEven = numbers.firstWhere((n) => n.isEven);
  print(firstEven);  // 2

  // singleWhere: Exactly one match (throws if 0 or 2+)
  var single = numbers.singleWhere((n) => n == 5);
  print(single);  // 5

  // expand: Flatten
  var pairs = numbers.expand((n) => [n, n * 2]);
  print(pairs.toList());  // [1, 2, 2, 4, 3, 6, ...]

  // followedBy: Concatenate
  var combined = numbers.followedBy([11, 12, 13]);
  print(combined.toList());  // [1, 2, ..., 10, 11, 12, 13]

  // take / skip
  print(numbers.take(3).toList());   // [1, 2, 3]
  print(numbers.skip(7).toList());   // [8, 9, 10]

  // takeWhile / skipWhile
  print(numbers.takeWhile((n) => n < 5).toList());  // [1, 2, 3, 4]

  // sort (modifies original)
  var unsorted = [3, 1, 4, 1, 5, 9, 2, 6];
  unsorted.sort();
  print(unsorted);  // [1, 1, 2, 3, 4, 5, 6, 9]

  // reversed
  print(numbers.reversed.toList());  // [10, 9, 8, ..., 1]

  // contains
  print(numbers.contains(5));  // true

  // join
  print(numbers.join(', '));  // 1, 2, 3, 4, 5, 6, 7, 8, 9, 10

  // forEach (side effects)
  numbers.forEach((n) => print('Number: $n'));
}
```

### 9.2 Chaining Operations

```dart
void main() {
  var users = [
    {'name': 'Alice', 'age': 25, 'active': true},
    {'name': 'Bob', 'age': 17, 'active': true},
    {'name': 'Charlie', 'age': 30, 'active': false},
    {'name': 'Diana', 'age': 22, 'active': true},
    {'name': 'Eve', 'age': 19, 'active': false},
  ];

  // Pipeline: Filter → Transform → Sort → Take
  var result = users
    .where((u) => u['active'] == true)           // Active users only
    .where((u) => (u['age'] as int) >= 18)       // Adults only
    .map((u) => u['name'] as String)             // Extract names
    .map((name) => name.toUpperCase())            // Uppercase
    .toList()                                     // Convert to list
    ..sort();                                     // Sort alphabetically

  print(result);  // [ALICE, DIANA]
}
```

### 9.3 Functional Programming on Maps

```dart
void main() {
  Map<String, int> scores = {
    'Alice': 95,
    'Bob': 82,
    'Charlie': 78,
    'Diana': 91,
  };

  // map entries
  var gradeLetters = scores.map((name, score) => 
    MapEntry(name, score >= 90 ? 'A' : score >= 80 ? 'B' : 'C'));
  print(gradeLetters);  // {Alice: A, Bob: B, Charlie: C, Diana: A}

  // filter entries
  var topStudents = Map.fromEntries(
    scores.entries.where((e) => e.value >= 90)
  );
  print(topStudents);  // {Alice: 95, Diana: 91}

  // forEach
  scores.forEach((name, score) {
    print('$name: $score');
  });

  // update
  scores.update('Alice', (value) => value + 5);
  print(scores['Alice']);  // 100

  // updateAll
  scores.updateAll((key, value) => value + 2);  // Curve all grades!
  print(scores);
}
```

---

## 10. Records (Dart 3)

### 10.1 What are Records?

Records are **anonymous, immutable, aggregate types**. They let you bundle multiple values without creating a class.

```dart
void main() {
  // Positional record
  var point = (3, 4);  // Record with 2 int fields
  print(point);        // (3, 4)
  print(point.$1);     // 3 (first field)
  print(point.$2);     // 4 (second field)

  // Named record
  var person = (name: 'Kimi', age: 25);
  print(person.name);  // Kimi
  print(person.age);   // 25

  // Mixed record (positional + named)
  var user = ('Kimi', age: 25, active: true);
  print(user.$1);      // Kimi
  print(user.age);     // 25
  print(user.active);  // true

  // Record with type annotation
  (String, int) coordinates = ('A1', 42);
  ({String name, int score}) player = (name: 'Kimi', score: 100);
}
```

### 10.2 Records as Return Values

```dart
// Return multiple values without creating a class!
({int quotient, int remainder}) divide(int a, int b) {
  return (quotient: a ~/ b, remainder: a % b);
}

(String name, int age, bool isActive) getUser() {
  return ('Kimi', 25, true);
}

void main() {
  var result = divide(17, 5);
  print('${result.quotient} remainder ${result.remainder}');  // 3 remainder 2

  var user = getUser();
  print('${user.$1} is ${user.$2} years old');  // Kimi is 25 years old
}
```

### 10.3 Record Equality

```dart
void main() {
  var a = (1, 2);
  var b = (1, 2);
  var c = (1, 3);

  print(a == b);  // true (same values)
  print(a == c);  // false (different values)

  // Named records
  var x = (name: 'Kimi', age: 25);
  var y = (age: 25, name: 'Kimi');  // Order doesn't matter for named!
  print(x == y);  // true
}
```

### 10.4 Records in Flutter

```dart
// Common pattern: Return (width, height) from a function
(double, double) getScreenSize() {
  // In Flutter: return (MediaQuery.of(context).size.width, MediaQuery.of(context).size.height);
  return (392.0, 783.0);
}

// Return (success, errorMessage) from validation
(bool, String?) validateEmail(String email) {
  if (email.contains('@')) {
    return (true, null);
  }
  return (false, 'Invalid email format');
}

void main() {
  var (width, height) = getScreenSize();
  print('Screen: ${width}x${height}');

  var (isValid, error) = validateEmail('test@example.com');
  print('Valid: $isValid, Error: $error');
}
```

---

## 11. Patterns & Pattern Matching (Dart 3)

### 11.1 Destructuring with Patterns

```dart
void main() {
  // Destructuring a record
  var (x, y) = (10, 20);
  print('x=$x, y=$y');  // x=10, y=20

  // Destructuring a list
  var [first, second, ...rest] = [1, 2, 3, 4, 5];
  print('first=$first, rest=$rest');  // first=1, rest=[3, 4, 5]

  // Destructuring a map
  var {'name': name, 'age': age} = {'name': 'Kimi', 'age': 25};
  print('$name is $age');  // Kimi is 25

  // Destructuring a class
  var Point(:x, :y) = Point(10, 20);
  print('Point: ($x, $y)');  // Point: (10, 20)
}

class Point {
  final double x;
  final double y;
  Point(this.x, this.y);
}
```

### 11.2 Switch Expressions with Patterns

```dart
String describeValue(Object value) {
  return switch (value) {
    int() when value < 0 => 'Negative number',
    int() when value == 0 => 'Zero',
    int() when value < 10 => 'Single digit: $value',
    int() => 'Multi-digit number: $value',
    String() when value.isEmpty => 'Empty string',
    String() => 'String: "$value"',
    bool() => 'Boolean: $value',
    [_, _, ...] => 'List with 2+ elements',
    [] => 'Empty list',
    {'name': String name} => 'Map with name: $name',
    _ => 'Something else',
  };
}

void main() {
  print(describeValue(5));        // Single digit: 5
  print(describeValue(-3));       // Negative number
  print(describeValue('Hello'));  // String: "Hello"
  print(describeValue([1, 2, 3])); // List with 2+ elements
  print(describeValue({'name': 'Kimi'})); // Map with name: Kimi
}
```

### 11.3 if-case Patterns

```dart
void main() {
  var json = {'name': 'Kimi', 'age': 25};

  // Pattern matching in if statement
  if (json case {'name': String name, 'age': int age}) {
    print('User: $name, Age: $age');
  }

  // List pattern matching
  var numbers = [1, 2, 3];
  if (numbers case [int first, int second, ...]) {
    print('First: $first, Second: $second');
  }

  // Null check pattern
  String? maybeName = 'Kimi';
  if (maybeName case String name) {
    print('Name is: $name');
  }
}
```

### 11.4 for-loop Patterns

```dart
void main() {
  var points = [(1, 2), (3, 4), (5, 6)];

  // Destructure in for loop
  for (var (x, y) in points) {
    print('Point: ($x, $y)');
  }

  // With map entries
  var scores = {'Alice': 95, 'Bob': 87};
  for (var MapEntry(:key, :value) in scores.entries) {
    print('$key: $value');
  }
}
```

---

## 12. Hands-On Project 1: Async JSON Data Fetcher

```dart
import 'dart:convert';

// Simulated HTTP client
class HttpClient {
  static Future<String> get(String url) async {
    await Future.delayed(Duration(milliseconds: 800));  // Network delay

    if (url.contains('users')) {
      return jsonEncode([
        {'id': 1, 'name': 'Kimi', 'email': 'kimi@example.com', 'age': 25},
        {'id': 2, 'name': 'Alex', 'email': 'alex@example.com', 'age': 30},
        {'id': 3, 'name': 'Sam', 'email': 'sam@example.com', 'age': 22},
      ]);
    }

    if (url.contains('posts')) {
      return jsonEncode([
        {'id': 1, 'userId': 1, 'title': 'Flutter Tips', 'body': 'Learn widgets...'},
        {'id': 2, 'userId': 1, 'title': 'Dart Patterns', 'body': 'Records are great...'},
        {'id': 3, 'userId': 2, 'title': 'State Management', 'body': 'Use Riverpod...'},
      ]);
    }

    throw Exception('404 Not Found');
  }
}

// Model classes
class User {
  final int id;
  final String name;
  final String email;
  final int age;

  User({required this.id, required this.name, required this.email, required this.age});

  factory User.fromJson(Map<String, dynamic> json) {
    return User(
      id: json['id'],
      name: json['name'],
      email: json['email'],
      age: json['age'],
    );
  }

  Map<String, dynamic> toJson() => {'id': id, 'name': name, 'email': email, 'age': age};

  @override
  String toString() => 'User(id: $id, name: $name, email: $email, age: $age)';
}

class Post {
  final int id;
  final int userId;
  final String title;
  final String body;

  Post({required this.id, required this.userId, required this.title, required this.body});

  factory Post.fromJson(Map<String, dynamic> json) {
    return Post(
      id: json['id'],
      userId: json['userId'],
      title: json['title'],
      body: json['body'],
    );
  }

  @override
  String toString() => 'Post($title by user $userId)';
}

// API Service with error handling
class ApiService {
  static Future<List<User>> fetchUsers() async {
    try {
      final response = await HttpClient.get('/api/users')
        .timeout(Duration(seconds: 3));

      final List<dynamic> jsonList = jsonDecode(response);
      return jsonList.map((json) => User.fromJson(json)).toList();
    } on FormatException catch (e) {
      print('JSON parsing error: $e');
      return [];
    } on TimeoutException {
      print('Request timed out');
      return [];
    } catch (e) {
      print('Unexpected error: $e');
      return [];
    }
  }

  static Future<List<Post>> fetchPosts() async {
    try {
      final response = await HttpClient.get('/api/posts')
        .timeout(Duration(seconds: 3));

      final List<dynamic> jsonList = jsonDecode(response);
      return jsonList.map((json) => Post.fromJson(json)).toList();
    } catch (e) {
      print('Error fetching posts: $e');
      return [];
    }
  }

  static Future<({List<User> users, List<Post> posts})> fetchAll() async {
    final results = await Future.wait([
      fetchUsers(),
      fetchPosts(),
    ]);

    return (users: results[0] as List<User>, posts: results[1] as List<Post>);
  }
}

void main() async {
  print('╔═══════════════════════════════════════╗');
  print('║      ASYNC JSON DATA FETCHER          ║');
  print('╚═══════════════════════════════════════╝');
  print('');

  // Sequential fetch
  print('⏳ Fetching users...');
  var users = await ApiService.fetchUsers();
  print('✅ Found ${users.length} users');
  users.forEach(print);

  print('');
  print('⏳ Fetching posts...');
  var posts = await ApiService.fetchPosts();
  print('✅ Found ${posts.length} posts');
  posts.forEach(print);

  // Parallel fetch with record return
  print('');
  print('⏳ Fetching everything in parallel...');
  var all = await ApiService.fetchAll();
  print('✅ Users: ${all.users.length}, Posts: ${all.posts.length}');

  // Functional processing
  print('');
  print('📊 ANALYSIS:');

  var adults = all.users.where((u) => u.age >= 25).toList();
  print('Adult users (25+): ${adults.map((u) => u.name).join(', ')}');

  var averageAge = all.users.map((u) => u.age).reduce((a, b) => a + b) / all.users.length;
  print('Average age: ${averageAge.toStringAsFixed(1)}');

  var postsByKimi = all.posts.where((p) => p.userId == 1).toList();
  print('Posts by Kimi: ${postsByKimi.length}');
}
```

---

## 13. Hands-On Project 2: Real-Time Stream Dashboard

```dart
import 'dart:async';
import 'dart:math';

// Simulated sensor data
class SensorReading {
  final String sensorId;
  final double temperature;
  final double humidity;
  final DateTime timestamp;

  SensorReading(this.sensorId, this.temperature, this.humidity)
    : timestamp = DateTime.now();

  bool get isHot => temperature > 30;
  bool get isCold => temperature < 15;
  bool get isNormal => !isHot && !isCold;

  @override
  String toString() =>
    '[${timestamp.toString().substring(11, 19)}] $sensorId: '
    '${temperature.toStringAsFixed(1)}°C, ${humidity.toStringAsFixed(1)}% '
    '${isHot ? '🔥' : isCold ? '❄️' : '✅'}';
}

class SensorDashboard {
  final List<StreamController<SensorReading>> _controllers = [];
  final List<StreamSubscription<SensorReading>> _subscriptions = [];
  final List<SensorReading> _history = [];

  // Create a simulated sensor stream
  Stream<SensorReading> createSensor(String id, double baseTemp, double baseHumidity) {
    var controller = StreamController<SensorReading>.broadcast();
    _controllers.add(controller);

    var random = Random();

    // Emit readings every second
    Timer.periodic(Duration(seconds: 1), (timer) {
      if (controller.isClosed) {
        timer.cancel();
        return;
      }

      var temp = baseTemp + random.nextDouble() * 10 - 5;
      var humidity = baseHumidity + random.nextDouble() * 20 - 10;
      var reading = SensorReading(id, temp, humidity.clamp(0, 100));
      controller.add(reading);
    });

    return controller.stream;
  }

  void monitorSensor(Stream<SensorReading> stream, String label) {
    var sub = stream.listen(
      (reading) {
        _history.add(reading);
        print('$label $reading');

        // Alert on extreme values
        if (reading.temperature > 35) {
          print('  ⚠️  HIGH TEMPERATURE ALERT!');
        }
        if (reading.humidity > 80) {
          print('  ⚠️  HIGH HUMIDITY ALERT!');
        }
      },
      onError: (e) => print('$label Error: $e'),
      onDone: () => print('$label Stream closed'),
    );
    _subscriptions.add(sub);
  }

  void printStats() {
    if (_history.isEmpty) return;

    var temps = _history.map((r) => r.temperature);
    var humidities = _history.map((r) => r.humidity);

    print('');
    print('╔═══════════════════════════════════════╗');
    print('║         SENSOR STATISTICS             ║');
    print('╠═══════════════════════════════════════╣');
    print('║ Total Readings: ${_history.length}');
    print('║ Avg Temperature: ${(temps.reduce((a, b) => a + b) / temps.length).toStringAsFixed(1)}°C');
    print('║ Avg Humidity: ${(humidities.reduce((a, b) => a + b) / humidities.length).toStringAsFixed(1)}%');
    print('║ Max Temperature: ${temps.reduce(max).toStringAsFixed(1)}°C');
    print('║ Min Temperature: ${temps.reduce(min).toStringAsFixed(1)}°C');
    print('║ Hot Readings: ${_history.where((r) => r.isHot).length}');
    print('║ Cold Readings: ${_history.where((r) => r.isCold).length}');
    print('╚═══════════════════════════════════════╝');
  }

  Future<void> dispose() async {
    for (var sub in _subscriptions) {
      await sub.cancel();
    }
    for (var controller in _controllers) {
      await controller.close();
    }
  }
}

void main() async {
  print('╔═══════════════════════════════════════╗');
  print('║    REAL-TIME STREAM DASHBOARD         ║');
  print('╚═══════════════════════════════════════╝');
  print('Monitoring sensors for 5 seconds...');
  print('');

  var dashboard = SensorDashboard();

  // Create sensor streams
  var sensorA = dashboard.createSensor('Sensor-A', 22, 50);
  var sensorB = dashboard.createSensor('Sensor-B', 28, 60);
  var sensorC = dashboard.createSensor('Sensor-C', 18, 45);

  // Monitor all sensors
  dashboard.monitorSensor(sensorA, '🏠 Room A');
  dashboard.monitorSensor(sensorB, '🏭 Factory B');
  dashboard.monitorSensor(sensorC, '❄️ Cold Storage C');

  // Also collect to list for stats
  var allReadings = <SensorReading>[];
  sensorA.listen((r) => allReadings.add(r));
  sensorB.listen((r) => allReadings.add(r));
  sensorC.listen((r) => allReadings.add(r));

  // Wait 5 seconds
  await Future.delayed(Duration(seconds: 5));

  // Print statistics
  dashboard.printStats();

  // Filtered view
  print('');
  print('🔥 HOT READINGS (>30°C):');
  allReadings.where((r) => r.isHot).forEach((r) => print('  $r'));

  await dashboard.dispose();
  print('');
  print('Dashboard closed.');
}
```

---

## 14. Common Mistakes & How to Avoid Them

### Mistake 1: Forgetting `await`
```dart
// ❌ WRONG — Future is not awaited
void main() {
  fetchData();  // Fire and forget! Error goes unhandled!
  print('Done');  // Prints before fetch completes
}

// ✅ CORRECT
void main() async {
  await fetchData();  // Waits for completion
  print('Done');
}
```

### Mistake 2: Using `await` in Non-async Function
```dart
// ❌ WRONG
void main() {
  var data = await fetchData();  // Syntax error!
}

// ✅ CORRECT
void main() async {
  var data = await fetchData();
}
```

### Mistake 3: Not Handling Future Errors
```dart
// ❌ WRONG — Unhandled exception crashes app
Future<void> risky() async {
  var data = await fetchData();  // Might throw!
  print(data);
}

// ✅ CORRECT
Future<void> safe() async {
  try {
    var data = await fetchData();
    print(data);
  } catch (e) {
    print('Error: $e');
  }
}
```

### Mistake 4: Sequential When Parallel is Possible
```dart
// ❌ SLOW — 3 seconds total
var a = await fetchA();  // 1s
var b = await fetchB();  // 1s
var c = await fetchC();  // 1s

// ✅ FAST — ~1 second total
var results = await Future.wait([fetchA(), fetchB(), fetchC()]);
```

### Mistake 5: Listening to Single-Subscription Stream Twice
```dart
// ❌ WRONG
var stream = Stream.fromIterable([1, 2, 3]);
stream.listen(print);
stream.listen(print);  // Runtime error!

// ✅ CORRECT
var stream = Stream.fromIterable([1, 2, 3]).asBroadcastStream();
stream.listen(print);
stream.listen(print);  // Works!
```

### Mistake 6: Not Closing Stream Controllers
```dart
// ❌ WRONG — Memory leak!
var controller = StreamController<int>();
// ... use controller ...
// Forgot to close!

// ✅ CORRECT
var controller = StreamController<int>();
// ... use controller ...
await controller.close();  // Always close!
```

### Mistake 7: Catching All Errors Blindly
```dart
// ❌ WRONG — Swallows ALL errors including programming mistakes
try {
  // code
} catch (e) {  // Catches EVERYTHING
  print(e);
}

// ✅ CORRECT — Catch specific errors
import 'dart:io';
try {
  // code
} on SocketException catch (e) {
  print('Network error: $e');
} on FormatException catch (e) {
  print('Bad data: $e');
} catch (e) {
  print('Unexpected: $e');
  rethrow;  // Let caller know something unexpected happened
}
```

### Mistake 8: Confusing `map()` on List vs Stream
```dart
// List map — returns Iterable (synchronous)
[1, 2, 3].map((n) => n * 2);  // Returns Iterable<int>

// Stream map — returns Stream (asynchronous)
stream.map((n) => n * 2);  // Returns Stream<int>

// Both are lazy — call .toList() or .listen() to execute
```

---

## 15. Day 5 Checklist

Use this checklist to verify mastery:

- [ ] Understands synchronous vs asynchronous programming
- [ ] Can create and use `Future` objects
- [ ] Can write `async` functions and use `await`
- [ ] Knows the difference between sequential and parallel execution
- [ ] Can use `Future.wait`, `Future.any`, `Future.delayed`
- [ ] Can chain Futures with `then`, `catchError`, `whenComplete`, `timeout`
- [ ] Understands what a `Stream` is and when to use it
- [ ] Can create streams from iterables, futures, and controllers
- [ ] Knows the difference between single-subscription and broadcast streams
- [ ] Can listen to streams and manage subscriptions
- [ ] Can transform streams with `map`, `where`, `take`, `skip`, `distinct`
- [ ] Can use `Stream.reduce`, `Stream.fold`, `Stream.toList`
- [ ] Can handle errors with `try/catch/finally`
- [ ] Can catch specific error types with `on`
- [ ] Can use `rethrow` to propagate errors
- [ ] Can create custom exception classes
- [ ] Masters functional collection operations: `map`, `where`, `reduce`, `fold`
- [ ] Can chain collection operations into pipelines
- [ ] Can create and use records `()` for multiple return values
- [ ] Can destructure records, lists, and maps with patterns
- [ ] Can use switch expressions with pattern matching
- [ ] Can use `if-case` for pattern matching
- [ ] Built the Async JSON Data Fetcher with error handling
- [ ] Built the Real-Time Stream Dashboard
- [ ] Pushed both projects to GitHub

---

## 🧠 Key Takeaways (Memorize These!)

1. **`async` makes a function return a Future.** `await` pauses the function without blocking other code.

2. **Use `Future.wait([...])` for parallel execution.** It's much faster than sequential awaits.

3. **A `Future` is a single value in the future.** A `Stream` is multiple values over time.

4. **Always close `StreamController`s.** They cause memory leaks if left open.

5. **Single-subscription streams can only have one listener.** Use `.asBroadcastStream()` for multiple listeners.

6. **Catch specific errors with `on`.** Use `catch` as a fallback and `rethrow` when you can't handle it.

7. **`map`, `where`, `reduce` work on both Lists and Streams.** But Streams are async and lazy.

8. **Records `()` let you return multiple values** without creating a class. Use named fields for clarity.

9. **Pattern matching with `switch` expressions** is cleaner than long if-else chains in Dart 3.

10. **Any I/O operation (network, file, database) should be async.** Keep the UI thread free for 60 FPS.

---

## 📚 Extra Practice (Do These Tonight!)

1. **Weather API Client:** Create a service that fetches weather data asynchronously, handles timeouts, retries on failure, and parses JSON into models.

2. **Chat Message Stream:** Build a chat system with `StreamController` that emits messages, filters by user, and maintains a message history.

3. **File Processor:** Read a CSV file asynchronously, process each row with functional operations (map, filter), and write results to a new file.

4. **Stock Price Ticker:** Create a stream that emits random stock prices every second. Use `where` to filter significant changes and `fold` to calculate running averages.

5. **Login Flow:** Build an async login system with validation, API call, token storage, and proper error handling for network/auth/server errors.

---

> 🎉 **Congratulations!** You've completed Day 5. You now understand async programming, streams, error handling, functional collections, records, and pattern matching. These are the advanced Dart features that power real-world Flutter apps.

**Next Up → Day 6: Flutter Widgets Fundamentals**


# 📘 Day 6: Flutter Widgets Fundamentals — Complete Deep Dive
> **Goal:** Understand the widget system and build basic layouts confidently.
> *This is your first real Flutter UI day — every concept explained with visual diagrams, code, and hands-on practice.*

---

## Table of Contents
1. [The "Everything is a Widget" Philosophy](#1-the-everything-is-a-widget-philosophy)
2. [Widget Tree & Element Tree Explained](#2-widget-tree--element-tree-explained)
3. [StatelessWidget vs StatefulWidget](#3-statelesswidget-vs-statefulwidget)
4. [BuildContext Deep Dive](#4-buildcontext-deep-dive)
5. [Keys in Flutter](#5-keys-in-flutter)
6. [Basic Widgets Masterclass](#6-basic-widgets-masterclass)
7. [Layout Widgets: Row, Column, Stack](#7-layout-widgets-row-column-stack)
8. [Flexible & Expanded Explained](#8-flexible--expanded-explained)
9. [Container Deep Dive](#9-container-deep-dive)
10. [Text Widget Mastery](#10-text-widget-mastery)
11. [Hands-On Project: Business Card UI](#11-hands-on-project-business-card-ui)
12. [Common Mistakes & How to Avoid Them](#12-common-mistakes--how-to-avoid-them)
13. [Day 6 Checklist](#13-day-6-checklist)

---

## 1. The "Everything is a Widget" Philosophy

### What Does "Everything is a Widget" Mean?

In Flutter, **everything you see on screen is a widget**. But more than that — everything that *configures* what you see is also a widget.

```
┌─────────────────────────────────────────────────────────────┐
│              EVERYTHING IS A WIDGET                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Visible things are widgets:        Invisible things too:   │
│  ─────────────────────────          ─────────────────────     │
│  • Text                             • Padding               │
│  • Button                           • Margin                │
│  • Image                            • Alignment             │
│  • Icon                             • Expanded              │
│  • Container                        • Center                │
│  • List                             • GestureDetector       │
│                                                             │
│  Even the APP itself is a widget:   • MaterialApp           │
│                                     • Scaffold              │
│                                     • Theme                 │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### Widgets Are Just Configuration Objects

```dart
// A widget is NOT the actual UI element on screen
// It's a BLUEPRINT that tells Flutter WHAT to build

Text('Hello')  // This is a configuration object
               // It says: "Put text 'Hello' here"

Container(     // This is a configuration object
  width: 100,  // It says: "Make a box 100px wide"
  height: 100, // "Make it 100px tall"
  color: Colors.red,  // "Fill it with red"
)
```

### The Three-Layer Architecture

```
┌─────────────────────────────────────────────────────────────┐
│  LAYER 1: WIDGETS (Your Code)                               │
│  ─────────────────────────────                              │
│  Immutable configuration objects                            │
│  You create these in build() methods                        │
│  Cheap to create, throw away, and recreate                  │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│  LAYER 2: ELEMENTS (Flutter Engine)                         │
│  ─────────────────────────────────                          │
│  Mutable, long-lived objects                                │
│  Hold references to widgets and state                       │
│  Manage the widget lifecycle                                │
│  One Element per Widget in the tree                         │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│  LAYER 3: RENDER OBJECTS (Flutter Engine)                   │
│  ─────────────────────────────────────                      │
│  Actually paint on screen                                   │
│  Handle layout, painting, hit-testing                       │
│  Know about sizes, positions, colors                        │
│  Expensive to create — reused when possible                 │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

> 💡 **Key Insight:** You write Widgets. Flutter manages Elements and RenderObjects. When you call `setState()`, Flutter compares the new widget tree with the old one and updates only what changed.

---

## 2. Widget Tree & Element Tree Explained

### The Widget Tree (What You Write)

```dart
MaterialApp(
  home: Scaffold(
    appBar: AppBar(
      title: Text('My App'),        // Widget
    ),
    body: Center(                   // Widget
      child: Column(                // Widget
        children: [
          Text('Hello'),            // Widget
          Container(                // Widget
            child: Icon(Icons.star),// Widget
          ),
        ],
      ),
    ),
  ),
)
```

### Visual Widget Tree

```
                    MaterialApp
                         │
                    Scaffold
                    /        \
              AppBar          Body: Center
                 │                │
            Text('My App')    Column
                               /      \
                          Text      Container
                          ('Hello')      │
                                      Icon
                                    (Icons.star)
```

### How Flutter Updates the UI

```
Step 1: You call setState()
        ↓
Step 2: Flutter calls build() → New Widget Tree created
        ↓
Step 3: Flutter compares New Widget Tree vs Old Widget Tree
        ↓
Step 4: For widgets that changed type or key:
        • Destroy old Element + RenderObject
        • Create new Element + RenderObject
        ↓
Step 5: For widgets that stayed the same:
        • Update existing Element with new configuration
        • Reuse RenderObject, just update properties
        ↓
Step 6: Flutter repaints only changed areas
```

> 🎯 **This is why Flutter is fast:** It doesn't redraw everything. It only updates what changed.

---

## 3. StatelessWidget vs StatefulWidget

### The Fundamental Decision

Every time you create a widget, you must choose:

```
┌─────────────────────────────────────────────────────────────┐
│  Does this widget need to CHANGE after it's built?          │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│     NO ──→ StatelessWidget                                  │
│     │                                                       │
│     │   • Display static content                            │
│     │   • No user interaction that changes UI               │
│     │   • Configuration/settings display                    │
│     │   • Icon, Label, Static Image                         │
│     │                                                       │
│     YES ──→ StatefulWidget                                  │
│         │                                                   │
│         • User taps a button                                │
│         • Form input changes                                │
│         • Animation plays                                   │
│         • Data loads from API                               │
│         • Checkbox toggles                                  │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### StatelessWidget — Immutable UI

```dart
// A StatelessWidget NEVER changes after it's built
// If the parent rebuilds, it gets a NEW instance

class GreetingCard extends StatelessWidget {
  final String name;
  final String message;

  // Constructor with const = performance boost!
  const GreetingCard({
    super.key,
    required this.name,
    required this.message,
  });

  @override
  Widget build(BuildContext context) {
    return Card(
      child: Padding(
        padding: const EdgeInsets.all(16.0),
        child: Column(
          mainAxisSize: MainAxisSize.min,
          children: [
            Text('Hello, $name!', style: TextStyle(fontSize: 24)),
            const SizedBox(height: 8),
            Text(message),
          ],
        ),
      ),
    );
  }
}

void main() {
  runApp(MaterialApp(
    home: Scaffold(
      body: Center(
        child: GreetingCard(
          name: 'Kimi',
          message: 'Welcome to Flutter!',
        ),
      ),
    ),
  ));
}
```

**StatelessWidget Rules:**
- ✅ Use `final` fields only
- ✅ Use `const` constructor when possible
- ❌ Never call `setState()`
- ❌ Never have mutable fields (non-final)

### StatefulWidget — Mutable UI

```dart
// A StatefulWidget CAN change after it's built
// It has a separate State object that holds mutable data

class CounterApp extends StatefulWidget {
  const CounterApp({super.key});

  @override
  State<CounterApp> createState() => _CounterAppState();
}

// The State object lives longer than the widget
class _CounterAppState extends State<CounterApp> {
  int _counter = 0;  // Mutable state!

  void _increment() {
    setState(() {
      _counter++;  // Change state → triggers rebuild
    });
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('Counter')),
      body: Center(
        child: Text('Count: $_counter', style: TextStyle(fontSize: 48)),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: _increment,
        child: const Icon(Icons.add),
      ),
    );
  }
}
```

### The StatefulWidget Lifecycle

```
┌─────────────────────────────────────────────────────────────┐
│           StatefulWidget Lifecycle                          │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  1. Constructor                                             │
│     └─→ Widget created (configuration only)                 │
│                                                             │
│  2. createState()                                           │
│     └─→ State object created (lives long!)                  │
│                                                             │
│  3. initState()                                             │
│     └─→ One-time setup (subscribe to streams, etc.)         │
│                                                             │
│  4. build() ←────────────────────┐                          │
│     └─→ Create widget tree       │                          │
│                                  │                          │
│  5. setState() ──→ triggers rebuild()                       │
│     └─→ didUpdateWidget() if parent changed                 │
│                                  │                          │
│  6. deactivate() ──→ widget removed from tree               │
│                                                             │
│  7. dispose() ──→ cleanup (cancel subscriptions, etc.)      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### initState() — One-Time Setup

```dart
class _TimerWidgetState extends State<TimerWidget> {
  late Timer _timer;
  int _seconds = 0;

  @override
  void initState() {
    super.initState();  // ALWAYS call super.initState() first!

    // One-time setup
    _timer = Timer.periodic(Duration(seconds: 1), (timer) {
      setState(() {
        _seconds++;
      });
    });
  }

  @override
  void dispose() {
    _timer.cancel();  // Cleanup!
    super.dispose();  // ALWAYS call super.dispose() last!
  }

  @override
  Widget build(BuildContext context) {
    return Text('$_seconds seconds elapsed');
  }
}
```

### When to Use Which?

| Scenario | Widget Type | Why |
|----------|-------------|-----|
| Static text label | `StatelessWidget` | Never changes |
| Button that just navigates | `StatelessWidget` | No internal state |
| Counter | `StatefulWidget` | State changes on tap |
| Form input field | `StatefulWidget` | Text changes as user types |
| List from API | `StatefulWidget` | Data loads, then displays |
| App bar title | `StatelessWidget` | Set once by parent |
| Loading spinner | `StatefulWidget` | Shows/hides based on state |

---

## 4. BuildContext Deep Dive

### What is BuildContext?

`BuildContext` is a **handle to the location of a widget in the widget tree**. It's how Flutter knows where you are.

```dart
class MyWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) {  // ← This is BuildContext!
    // 'context' knows:
    // • Where this widget is in the tree
    // • How to find parent widgets (Theme, Navigator, etc.)
    // • How to register for rebuilds

    return Container();
  }
}
```

### What You Can Do With BuildContext

```dart
class ContextDemo extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    // 1. Access Theme data
    var theme = Theme.of(context);
    var primaryColor = theme.primaryColor;
    var textTheme = theme.textTheme;

    // 2. Access MediaQuery (screen size, orientation)
    var mediaQuery = MediaQuery.of(context);
    var screenWidth = mediaQuery.size.width;
    var screenHeight = mediaQuery.size.height;
    var isPortrait = mediaQuery.orientation == Orientation.portrait;
    var padding = mediaQuery.padding;  // Notch, status bar

    // 3. Navigate to new screen
    // Navigator.of(context).push(MaterialPageRoute(...));

    // 4. Show snackbar
    // ScaffoldMessenger.of(context).showSnackBar(...);

    // 5. Show dialog
    // showDialog(context: context, builder: ...);

    // 6. Find ancestor widget
    // var scaffold = Scaffold.of(context);

    return Container();
  }
}
```

### The BuildContext Tree

```
MaterialApp (context: root)
  └── Scaffold (context: scaffold)
        ├── AppBar (context: appbar)
        │     └── Text (context: text1)
        └── Body: Center (context: center)
              └── Column (context: column)
                    ├── Text (context: text2)
                    └── Button (context: button)
                          └── Text (context: text3)

Each widget has its OWN BuildContext
Context knows about ancestors, not descendants
```

### Common BuildContext Methods

```dart
// Theme
Theme.of(context)                    // Get theme data
Theme.of(context).primaryColor       // Primary color
Theme.of(context).textTheme          // Text styles

// MediaQuery
MediaQuery.of(context).size          // Screen size
MediaQuery.of(context).padding       // Safe area padding
MediaQuery.of(context).orientation   // Portrait/Landscape

// Navigation
Navigator.of(context)                // Navigator
Navigator.of(context).push(route)    // Go to new screen
Navigator.of(context).pop()          // Go back

// Scaffold
Scaffold.of(context)                 // Access Scaffold
ScaffoldMessenger.of(context)        // Show snackbars

// Localization
Localizations.of(context, type)      // Translated strings

// Inherited Widgets
Provider.of<MyModel>(context)        // State management
BlocProvider.of<MyBloc>(context)     // BLoC pattern
```

### The `context` Trap

```dart
// ❌ WRONG — Using context after async gap
void _onPressed(BuildContext context) async {
  await Future.delayed(Duration(seconds: 1));
  // ⚠️ DANGER: Widget might have been disposed!
  Navigator.of(context).pop();  // Might crash!
}

// ✅ CORRECT — Check mounted first (in StatefulWidget)
void _onPressed() async {
  await Future.delayed(Duration(seconds: 1));
  if (mounted) {  // Check if widget still exists
    Navigator.of(context).pop();
  }
}

// ✅ CORRECT — Use context safely
void _onPressed(BuildContext context) async {
  var navigator = Navigator.of(context);  // Capture before async
  await Future.delayed(Duration(seconds: 1));
  navigator.pop();  // Safe — we captured the navigator
}
```

---

## 5. Keys in Flutter

### Why Do Keys Matter?

Keys tell Flutter: **"This widget is the same one, just with updated data"** vs **"This is a completely different widget."**

```
Without Keys (PROBLEM):
┌─────────────────────────────────────────────────────────────┐
│  Old Tree              New Tree              Result          │
│  ─────────             ─────────             ──────          │
│  ListView                                    ❌ WRONG!     │
│    ├── Widget A (red)  ├── Widget B (blue)   Blue shows     │
│    └── Widget B (blue) └── Widget A (red)    where red was  │
│                                              Flutter thinks   │
│                                              A became B!    │
└─────────────────────────────────────────────────────────────┘

With Keys (FIXED):
┌─────────────────────────────────────────────────────────────┐
│  Old Tree              New Tree              Result          │
│  ─────────             ─────────             ──────          │
│  ListView                                    ✅ CORRECT!    │
│    ├── Widget A (red)  ├── Widget B (blue)   B moved to top │
│    └── Widget B (blue) └── Widget A (red)    A moved down   │
│                                              Flutter knows   │
│                                              which is which  │
└─────────────────────────────────────────────────────────────┘
```

### Types of Keys

```dart
// 1. ValueKey — Most common
// Use when widgets have a unique value
ListView.builder(
  itemCount: users.length,
  itemBuilder: (context, index) {
    return ListTile(
      key: ValueKey(users[index].id),  // Unique ID
      title: Text(users[index].name),
    );
  },
)

// 2. ObjectKey — Use the entire object as key
ListView.builder(
  itemCount: items.length,
  itemBuilder: (context, index) {
    return ListTile(
      key: ObjectKey(items[index]),  // Entire object is the key
      title: Text(items[index].name),
    );
  },
)

// 3. UniqueKey — Always unique (rarely needed)
Widget build(BuildContext context) {
  return Container(
    key: UniqueKey(),  // Different every build — forces rebuild!
  );
}

// 4. GlobalKey — Access widget from anywhere
class _MyFormState extends State<MyForm> {
  final _formKey = GlobalKey<FormState>();  // Access form state globally

  @override
  Widget build(BuildContext context) {
    return Form(
      key: _formKey,
      child: Column(
        children: [
          TextFormField(),
          ElevatedButton(
            onPressed: () {
              if (_formKey.currentState!.validate()) {
                // Form is valid!
              }
            },
            child: Text('Submit'),
          ),
        ],
      ),
    );
  }
}

// 5. PageStorageKey — Preserve scroll position
ListView(
  key: PageStorageKey('my_list'),  // Remembers scroll position
  children: [...],
)
```

### When to Use Keys

| Scenario | Key Type | Why |
|----------|----------|-----|
| Reorderable list | `ValueKey(id)` | Track items when moved |
| Form validation | `GlobalKey<FormState>()` | Access form state |
| Tab view scroll position | `PageStorageKey` | Remember position |
| Animated list | `ValueKey(id)` | Animate correct item |
| Simple static list | No key needed | Items don't move |

---

## 6. Basic Widgets Masterclass

### 6.1 Text Widget

```dart
Text(
  'Hello, Flutter!',
  style: TextStyle(
    fontSize: 24,                    // Size in logical pixels
    fontWeight: FontWeight.bold,     // w400 (normal), w700 (bold)
    color: Colors.blue,              // Text color
    fontFamily: 'Roboto',            // Custom font
    letterSpacing: 1.5,              // Space between letters
    wordSpacing: 2.0,                // Space between words
    height: 1.5,                     // Line height multiplier
    decoration: TextDecoration.underline,
    decorationColor: Colors.red,
    decorationStyle: TextDecorationStyle.dashed,
    shadows: [
      Shadow(color: Colors.black26, offset: Offset(2, 2), blurRadius: 4),
    ],
  ),
  textAlign: TextAlign.center,       // left, right, center, justify
  overflow: TextOverflow.ellipsis,   // fade, clip, ellipsis, visible
  maxLines: 2,                       // Limit lines
  softWrap: true,                    // Wrap at soft line breaks
)
```

### 6.2 Icon Widget

```dart
Icon(
  Icons.favorite,                    // Material icon
  size: 48,                         // Size in logical pixels
  color: Colors.red,                // Icon color
  semanticLabel: 'Favorite',        // Accessibility
)

// Common icons:
// Icons.home, Icons.settings, Icons.person, Icons.search
// Icons.add, Icons.delete, Icons.edit, Icons.share
// Icons.arrow_back, Icons.menu, Icons.close
// Icons.favorite, Icons.favorite_border (outlined)
// Icons.check_circle, Icons.error, Icons.warning
```

### 6.3 Image Widget

```dart
// From assets (requires pubspec.yaml configuration)
Image.asset(
  'assets/images/logo.png',
  width: 100,
  height: 100,
  fit: BoxFit.cover,                // cover, contain, fill, fitWidth, fitHeight
)

// From network URL
Image.network(
  'https://example.com/image.jpg',
  loadingBuilder: (context, child, progress) {
    if (progress == null) return child;
    return CircularProgressIndicator(
      value: progress.expectedTotalBytes != null
        ? progress.cumulativeBytesLoaded / progress.expectedTotalBytes!
        : null,
    );
  },
  errorBuilder: (context, error, stackTrace) {
    return Icon(Icons.error);
  },
)

// From memory (Uint8List)
Image.memory(bytes)

// From file
Image.file(File('/path/to/image.jpg'))
```

### 6.4 ElevatedButton

```dart
ElevatedButton(
  onPressed: () {
    print('Button pressed!');
  },
  onLongPress: () {
    print('Long press!');
  },
  style: ElevatedButton.styleFrom(
    backgroundColor: Colors.blue,     // Button color
    foregroundColor: Colors.white,    // Text/icon color
    elevation: 4,                     // Shadow depth
    padding: EdgeInsets.all(16),      // Internal padding
    shape: RoundedRectangleBorder(
      borderRadius: BorderRadius.circular(8),
    ),
    minimumSize: Size(200, 50),       // Minimum dimensions
  ),
  child: Text('Click Me'),
)

// With icon
ElevatedButton.icon(
  onPressed: () {},
  icon: Icon(Icons.send),
  label: Text('Send'),
)
```

### 6.5 Other Button Types

```dart
// TextButton — Flat, no elevation
TextButton(
  onPressed: () {},
  child: Text('Text Button'),
)

// OutlinedButton — Border only
OutlinedButton(
  onPressed: () {},
  child: Text('Outlined'),
)

// IconButton — Just an icon
IconButton(
  onPressed: () {},
  icon: Icon(Icons.favorite),
  tooltip: 'Add to favorites',
)

// FloatingActionButton
FloatingActionButton(
  onPressed: () {},
  child: Icon(Icons.add),
)

// FloatingActionButton.extended
FloatingActionButton.extended(
  onPressed: () {},
  icon: Icon(Icons.add),
  label: Text('Add'),
)
```

---

## 7. Layout Widgets: Row, Column, Stack

### 7.1 Row — Horizontal Layout

```dart
Row(
  mainAxisAlignment: MainAxisAlignment.center,  // Horizontal
  crossAxisAlignment: CrossAxisAlignment.center, // Vertical
  mainAxisSize: MainAxisSize.max,               // max or min
  children: [
    Icon(Icons.star, color: Colors.yellow),
    SizedBox(width: 8),                         // Spacing
    Text('Rating: 4.5'),
    Spacer(),                                    // Pushes next item to end
    Text('120 reviews'),
  ],
)

// MainAxisAlignment options:
// start    → Left aligned (default)
// end      → Right aligned
// center   → Centered
// spaceBetween → Equal space BETWEEN items
// spaceAround  → Equal space AROUND items
// spaceEvenly  → Equal space EVERYWHERE

// CrossAxisAlignment options:
// start    → Top aligned
// end      → Bottom aligned
// center   → Centered (default)
// stretch  → Stretch to fill height
// baseline → Align by text baseline
```

**Visual MainAxisAlignment:**
```
start:     [A][B][C]                
end:                    [A][B][C]   
center:        [A][B][C]            
spaceBetween:[A]    [B]    [C]     
spaceAround: [A]  [B]  [C]         
spaceEvenly: [ A ] [ B ] [ C ]     
```

### 7.2 Column — Vertical Layout

```dart
Column(
  mainAxisAlignment: MainAxisAlignment.center,   // Vertical
  crossAxisAlignment: CrossAxisAlignment.start,  // Horizontal
  mainAxisSize: MainAxisSize.min,                // Wrap content height
  children: [
    Text('Title', style: TextStyle(fontSize: 24)),
    SizedBox(height: 16),
    Text('Description goes here...'),
    SizedBox(height: 24),
    Row(
      mainAxisAlignment: MainAxisAlignment.spaceEvenly,
      children: [
        ElevatedButton(onPressed: () {}, child: Text('OK')),
        TextButton(onPressed: () {}, child: Text('Cancel')),
      ],
    ),
  ],
)
```

### 7.3 Stack — Overlapping Layout

```dart
Stack(
  alignment: Alignment.center,       // Default alignment for children
  fit: StackFit.expand,              // expand, loose, passthrough
  children: [
    // Bottom layer
    Image.asset('assets/background.jpg', fit: BoxFit.cover),

    // Middle layer
    Container(
      color: Colors.black.withOpacity(0.5),
    ),

    // Top layer — positioned
    Positioned(
      bottom: 20,
      left: 20,
      right: 20,
      child: Text(
        'Welcome to Flutter',
        style: TextStyle(color: Colors.white, fontSize: 24),
        textAlign: TextAlign.center,
      ),
    ),

    // Top-right corner
    Positioned(
      top: 10,
      right: 10,
      child: IconButton(
        icon: Icon(Icons.close, color: Colors.white),
        onPressed: () {},
      ),
    ),
  ],
)
```

**Stack Alignment Values:**
```
topLeft      topCenter      topRight
    │            │             │
    ├────────────┼─────────────┤
    │            │             │
centerLeft   center      centerRight
    │            │             │
    ├────────────┼─────────────┤
    │            │             │
bottomLeft  bottomCenter  bottomRight
```

---

## 8. Flexible & Expanded Explained

### The Flex Problem

```dart
// ❌ WRONG — This overflows!
Row(
  children: [
    Container(width: 200, color: Colors.red),
    Container(width: 200, color: Colors.green),
    Container(width: 200, color: Colors.blue),
  ],
)
// Total: 600px, but screen is only 400px → OVERFLOW!
```

### Expanded — Fill Available Space

```dart
// ✅ CORRECT — Each takes equal space
Row(
  children: [
    Expanded(child: Container(color: Colors.red)),
    Expanded(child: Container(color: Colors.green)),
    Expanded(child: Container(color: Colors.blue)),
  ],
)
// Each gets 1/3 of available space

// With flex factors (unequal distribution)
Row(
  children: [
    Expanded(flex: 2, child: Container(color: Colors.red)),    // 2/3
    Expanded(flex: 1, child: Container(color: Colors.green)),  // 1/3
  ],
)
```

### Flexible — Allow Shrinking

```dart
Row(
  children: [
    // Flexible allows this to shrink if needed
    Flexible(
      child: Text('This is a very long text that needs to wrap'),
    ),
    Container(width: 100, color: Colors.blue),
  ],
)

// Flexible vs Expanded:
// Expanded = Flexible with fit: FlexFit.tight (forces fill)
// Flexible = Flexible with fit: FlexFit.loose (can be smaller)
```

### Visual Comparison

```
Row with 3 children, screen width = 300px

Without Expanded:
[Child A (200px)] [Child B (200px)] [Child C (200px)]
←────────────────────── OVERFLOW! ──────────────────────→

With Expanded:
[  A (100px)  ] [  B (100px)  ] [  C (100px)  ]
←────────────────── Fits perfectly ───────────────────→

With Expanded (flex: 2, 1, 1):
[    A (150px)    ] [ B (75px) ] [ C (75px) ]
←────────────────── Fits perfectly ───────────────────→
```

---

## 9. Container Deep Dive

### The Swiss Army Knife of Widgets

```dart
Container(
  // Size
  width: 200,
  height: 100,
  constraints: BoxConstraints(
    minWidth: 100,
    maxWidth: 300,
    minHeight: 50,
    maxHeight: 200,
  ),

  // Margin (space OUTSIDE the container)
  margin: EdgeInsets.all(16),           // All sides
  // margin: EdgeInsets.symmetric(horizontal: 16, vertical: 8),
  // margin: EdgeInsets.only(left: 16, top: 8),
  // margin: EdgeInsets.fromLTRB(16, 8, 16, 8),

  // Padding (space INSIDE the container)
  padding: EdgeInsets.all(16),

  // Alignment of child
  alignment: Alignment.center,

  // Decoration (background, border, shadow, shape)
  decoration: BoxDecoration(
    color: Colors.blue,                    // Background color

    // Border radius
    borderRadius: BorderRadius.circular(12),
    // borderRadius: BorderRadius.only(topLeft: Radius.circular(12)),
    // borderRadius: BorderRadius.horizontal(left: Radius.circular(12)),

    // Border
    border: Border.all(
      color: Colors.black,
      width: 2,
    ),

    // Gradient
    gradient: LinearGradient(
      colors: [Colors.blue, Colors.purple],
      begin: Alignment.topLeft,
      end: Alignment.bottomRight,
    ),

    // Box shadow
    boxShadow: [
      BoxShadow(
        color: Colors.black.withOpacity(0.3),
        blurRadius: 10,
        spreadRadius: 2,
        offset: Offset(4, 4),  // x, y
      ),
    ],

    // Shape
    shape: BoxShape.rectangle,  // or BoxShape.circle
  ),

  // Transform
  transform: Matrix4.rotationZ(0.1),  // Rotate 0.1 radians

  // Child widget
  child: Text('Hello', style: TextStyle(color: Colors.white)),
)
```

### Container vs SizedBox vs Padding

```dart
// Container — Full featured (margin, padding, decoration, alignment)
Container(
  margin: EdgeInsets.all(16),
  padding: EdgeInsets.all(16),
  decoration: BoxDecoration(color: Colors.red),
  child: Text('Hello'),
)

// SizedBox — Just size, very lightweight
SizedBox(
  width: 100,
  height: 100,
  child: Text('Hello'),
)

// SizedBox.shrink() — Takes no space
SizedBox.shrink()

// SizedBox.expand() — Fills parent
SizedBox.expand(child: Text('Fill'))

// Padding — Just padding, lightweight
Padding(
  padding: EdgeInsets.all(16),
  child: Text('Hello'),
)

// Center — Just centering, lightweight
Center(child: Text('Hello'))
```

> 🎯 **Performance Tip:** Use the most specific widget. `Padding` is cheaper than `Container` with only padding.

---

## 10. Text Widget Mastery

### RichText for Mixed Styles

```dart
RichText(
  text: TextSpan(
    style: TextStyle(color: Colors.black, fontSize: 16),
    children: [
      TextSpan(text: 'Hello '),
      TextSpan(
        text: 'Flutter',
        style: TextStyle(
          fontWeight: FontWeight.bold,
          color: Colors.blue,
          fontSize: 20,
        ),
      ),
      TextSpan(text: ' developer! '),
      TextSpan(
        text: 'Learn more',
        style: TextStyle(
          color: Colors.blue,
          decoration: TextDecoration.underline,
        ),
        recognizer: TapGestureRecognizer()..onTap = () {
          print('Tapped!');
        },
      ),
    ],
  ),
)
```

### Text with Theme

```dart
Text(
  'Headline',
  style: Theme.of(context).textTheme.headlineLarge,
)

Text(
  'Body text',
  style: Theme.of(context).textTheme.bodyLarge,
)

// Available text styles in Material 3:
// displayLarge, displayMedium, displaySmall
// headlineLarge, headlineMedium, headlineSmall
// titleLarge, titleMedium, titleSmall
// bodyLarge, bodyMedium, bodySmall
// labelLarge, labelMedium, labelSmall
```

---

## 11. Hands-On Project: Business Card UI

Build a professional business card:

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const BusinessCardApp());
}

class BusinessCardApp extends StatelessWidget {
  const BusinessCardApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.teal),
        useMaterial3: true,
      ),
      home: const BusinessCardScreen(),
    );
  }
}

class BusinessCardScreen extends StatelessWidget {
  const BusinessCardScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Colors.teal.shade50,
      body: Center(
        child: SingleChildScrollView(
          padding: const EdgeInsets.all(24),
          child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: [
              const BusinessCard(),
              const SizedBox(height: 32),
              const SkillsSection(),
            ],
          ),
        ),
      ),
    );
  }
}

class BusinessCard extends StatelessWidget {
  const BusinessCard({super.key});

  @override
  Widget build(BuildContext context) {
    return Container(
      width: 350,
      decoration: BoxDecoration(
        color: Colors.white,
        borderRadius: BorderRadius.circular(20),
        boxShadow: [
          BoxShadow(
            color: Colors.black.withOpacity(0.15),
            blurRadius: 20,
            spreadRadius: 5,
            offset: const Offset(0, 10),
          ),
        ],
      ),
      child: Column(
        mainAxisSize: MainAxisSize.min,
        children: [
          // Header with avatar
          Container(
            padding: const EdgeInsets.all(24),
            decoration: BoxDecoration(
              gradient: LinearGradient(
                colors: [Colors.teal.shade400, Colors.teal.shade700],
                begin: Alignment.topLeft,
                end: Alignment.bottomRight,
              ),
              borderRadius: const BorderRadius.vertical(
                top: Radius.circular(20),
              ),
            ),
            child: Column(
              children: [
                // Avatar
                Container(
                  width: 100,
                  height: 100,
                  decoration: BoxDecoration(
                    color: Colors.white,
                    shape: BoxShape.circle,
                    border: Border.all(color: Colors.white, width: 4),
                    boxShadow: [
                      BoxShadow(
                        color: Colors.black.withOpacity(0.2),
                        blurRadius: 10,
                      ),
                    ],
                  ),
                  child: const Icon(
                    Icons.person,
                    size: 50,
                    color: Colors.teal,
                  ),
                ),
                const SizedBox(height: 16),
                const Text(
                  'Kimi Developer',
                  style: TextStyle(
                    color: Colors.white,
                    fontSize: 24,
                    fontWeight: FontWeight.bold,
                  ),
                ),
                const SizedBox(height: 4),
                const Text(
                  'Flutter Developer',
                  style: TextStyle(
                    color: Colors.white70,
                    fontSize: 16,
                  ),
                ),
              ],
            ),
          ),

          // Contact info
          Padding(
            padding: const EdgeInsets.all(24),
            child: Column(
              children: [
                _buildInfoRow(Icons.email, 'kimi@flutter.dev'),
                const SizedBox(height: 12),
                _buildInfoRow(Icons.phone, '+91 98765 43210'),
                const SizedBox(height: 12),
                _buildInfoRow(Icons.location_on, 'Mumbai, India'),
                const SizedBox(height: 12),
                _buildInfoRow(Icons.web, 'www.flutter.dev'),
              ],
            ),
          ),

          // Social buttons
          Padding(
            padding: const EdgeInsets.only(bottom: 24),
            child: Row(
              mainAxisAlignment: MainAxisAlignment.center,
              children: [
                _buildSocialButton(Icons.code, Colors.blue),
                const SizedBox(width: 16),
                _buildSocialButton(Icons.business, Colors.blue.shade800),
                const SizedBox(width: 16),
                _buildSocialButton(Icons.chat, Colors.green),
              ],
            ),
          ),
        ],
      ),
    );
  }

  Widget _buildInfoRow(IconData icon, String text) {
    return Row(
      children: [
        Icon(icon, color: Colors.teal, size: 20),
        const SizedBox(width: 12),
        Expanded(
          child: Text(
            text,
            style: const TextStyle(fontSize: 14, color: Colors.black87),
          ),
        ),
      ],
    );
  }

  Widget _buildSocialButton(IconData icon, Color color) {
    return Container(
      width: 44,
      height: 44,
      decoration: BoxDecoration(
        color: color.withOpacity(0.1),
        shape: BoxShape.circle,
      ),
      child: IconButton(
        icon: Icon(icon, color: color, size: 20),
        onPressed: () {},
      ),
    );
  }
}

class SkillsSection extends StatelessWidget {
  const SkillsSection({super.key});

  @override
  Widget build(BuildContext context) {
    final skills = [
      ('Flutter', 0.9, Colors.blue),
      ('Dart', 0.85, Colors.teal),
      ('Firebase', 0.75, Colors.orange),
      ('UI/UX', 0.8, Colors.purple),
    ];

    return Container(
      width: 350,
      padding: const EdgeInsets.all(24),
      decoration: BoxDecoration(
        color: Colors.white,
        borderRadius: BorderRadius.circular(20),
        boxShadow: [
          BoxShadow(
            color: Colors.black.withOpacity(0.1),
            blurRadius: 15,
            offset: const Offset(0, 5),
          ),
        ],
      ),
      child: Column(
        crossAxisAlignment: CrossAxisAlignment.start,
        children: [
          const Text(
            'Skills',
            style: TextStyle(
              fontSize: 20,
              fontWeight: FontWeight.bold,
            ),
          ),
          const SizedBox(height: 16),
          ...skills.map((skill) => _buildSkillBar(skill.$1, skill.$2, skill.$3)),
        ],
      ),
    );
  }

  Widget _buildSkillBar(String name, double progress, Color color) {
    return Padding(
      padding: const EdgeInsets.only(bottom: 12),
      child: Column(
        crossAxisAlignment: CrossAxisAlignment.start,
        children: [
          Row(
            mainAxisAlignment: MainAxisAlignment.spaceBetween,
            children: [
              Text(name, style: const TextStyle(fontSize: 14)),
              Text('${(progress * 100).toInt()}%', style: const TextStyle(fontSize: 12, color: Colors.grey)),
            ],
          ),
          const SizedBox(height: 4),
          ClipRRect(
            borderRadius: BorderRadius.circular(4),
            child: LinearProgressIndicator(
              value: progress,
              backgroundColor: Colors.grey.shade200,
              valueColor: AlwaysStoppedAnimation<Color>(color),
              minHeight: 8,
            ),
          ),
        ],
      ),
    );
  }
}
```

---

## 12. Common Mistakes & How to Avoid Them

### Mistake 1: Using `setState()` in StatelessWidget
```dart
// ❌ WRONG
class MyWidget extends StatelessWidget {
  int count = 0;  // Mutable field in StatelessWidget!

  @override
  Widget build(BuildContext context) {
    return ElevatedButton(
      onPressed: () {
        count++;  // This won't update the UI!
        // setState(() {});  // Doesn't exist here!
      },
      child: Text('$count'),
    );
  }
}

// ✅ CORRECT
class MyWidget extends StatefulWidget {
  @override
  State<MyWidget> createState() => _MyWidgetState();
}

class _MyWidgetState extends State<MyWidget> {
  int count = 0;

  @override
  Widget build(BuildContext context) {
    return ElevatedButton(
      onPressed: () {
        setState(() {
          count++;
        });
      },
      child: Text('$count'),
    );
  }
}
```

### Mistake 2: Deeply Nested Widgets (Pyramid of Doom)
```dart
// ❌ WRONG — Hard to read, hard to maintain
return Scaffold(
  body: Center(
    child: Container(
      padding: EdgeInsets.all(16),
      child: Column(
        children: [
          Row(
            children: [
              Expanded(
                child: Container(
                  child: Text('...'),
                ),
              ),
            ],
          ),
        ],
      ),
    ),
  ),
);

// ✅ CORRECT — Extract methods/widgets
return Scaffold(
  body: Center(
    child: _buildContent(),
  ),
);

Widget _buildContent() {
  return Container(
    padding: EdgeInsets.all(16),
    child: Column(
      children: [
        _buildHeader(),
        _buildBody(),
      ],
    ),
  );
}
```

### Mistake 3: Forgetting `const` Constructors
```dart
// ❌ Wasteful — Creates new instances every build
Text('Hello')

// ✅ Efficient — Reuses same instance
const Text('Hello')

// ✅ Even better — const entire subtree
const Padding(
  padding: EdgeInsets.all(16),
  child: const Text('Hello'),
)
```

### Mistake 4: Row/Column Overflow
```dart
// ❌ WRONG — Will overflow on small screens
Row(
  children: [
    Text('Very long text that might overflow the screen width'),
    Icon(Icons.arrow_forward),
  ],
)

// ✅ CORRECT — Use Expanded or Flexible
Row(
  children: [
    Expanded(
      child: Text('Very long text...'),
    ),
    Icon(Icons.arrow_forward),
  ],
)
```

### Mistake 5: Using `Container` for Everything
```dart
// ❌ Overkill
Container(
  padding: EdgeInsets.all(16),
  child: Text('Hello'),
)

// ✅ Better — Use specific widget
Padding(
  padding: EdgeInsets.all(16),
  child: Text('Hello'),
)

// ❌ Overkill
Container(
  alignment: Alignment.center,
  child: Text('Hello'),
)

// ✅ Better
Center(child: Text('Hello'))
```

### Mistake 6: Not Using `super.key`
```dart
// ❌ Missing key parameter
class MyWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) { }
}

// ✅ Correct
class MyWidget extends StatelessWidget {
  const MyWidget({super.key});
  @override
  Widget build(BuildContext context) { }
}
```

### Mistake 7: Calling `setState()` in `build()`
```dart
// ❌ WRONG — Infinite loop!
@override
Widget build(BuildContext context) {
  setState(() { count++; });  // Triggers rebuild → calls build again!
  return Text('$count');
}

// ✅ CORRECT — Only in response to user action
@override
Widget build(BuildContext context) {
  return ElevatedButton(
    onPressed: () => setState(() { count++; }),
    child: Text('$count'),
  );
}
```

### Mistake 8: Not Handling `BuildContext` After Async
```dart
// ❌ WRONG
void _onTap(BuildContext context) async {
  await Future.delayed(Duration(seconds: 1));
  Navigator.of(context).pop();  // Might crash!
}

// ✅ CORRECT
void _onTap() async {
  await Future.delayed(Duration(seconds: 1));
  if (mounted) {  // Check if still in tree
    Navigator.of(context).pop();
  }
}
```

---

## 13. Day 6 Checklist

Use this checklist to verify mastery:

- [ ] Can explain "Everything is a Widget" philosophy
- [ ] Understands the 3-layer architecture: Widget → Element → RenderObject
- [ ] Can explain how Flutter updates UI efficiently
- [ ] Knows when to use StatelessWidget vs StatefulWidget
- [ ] Understands the StatefulWidget lifecycle (initState, build, dispose)
- [ ] Knows what BuildContext is and what it provides
- [ ] Can use `Theme.of(context)`, `MediaQuery.of(context)`, `Navigator.of(context)`
- [ ] Understands when and why to use Keys
- [ ] Can use ValueKey, GlobalKey, and PageStorageKey
- [ ] Can build layouts with Row, Column, and Stack
- [ ] Understands mainAxisAlignment and crossAxisAlignment
- [ ] Can use Positioned within Stack
- [ ] Can use Expanded and Flexible to prevent overflow
- [ ] Can use Container with decoration, margin, padding, alignment
- [ ] Can create gradients, shadows, and rounded corners
- [ ] Can use Text with rich styling
- [ ] Can use RichText for mixed styles
- [ ] Can create buttons: ElevatedButton, TextButton, OutlinedButton, IconButton
- [ ] Can display images from assets and network
- [ ] Built the Business Card UI with Card, gradient, shadow
- [ ] Built the Skills Section with progress bars
- [ ] Understands performance: use `const`, use specific widgets over Container
- [ ] Pushed the project to GitHub

---

## 🧠 Key Takeaways (Memorize These!)

1. **Everything is a Widget** — Not just visible things, but also layout, padding, and gestures.

2. **StatelessWidget = immutable.** Use for static content. StatefulWidget = mutable. Use for interactive content.

3. **Widgets are cheap to create.** Flutter reuses Elements and RenderObjects. Don't worry about creating widgets.

4. **BuildContext is your location in the tree.** Use it to access Theme, MediaQuery, Navigator, and ancestor widgets.

5. **Use `const` constructors everywhere possible.** It tells Flutter: "This widget never changes, reuse it."

6. **Row = horizontal, Column = vertical, Stack = overlapping.** These are your layout building blocks.

7. **Use Expanded/Flexible to prevent overflow.** Never put unbounded width widgets in a Row without Expanded.

8. **Container is powerful but heavy.** Use Padding, Center, SizedBox when you only need one feature.

9. **Extract widgets to avoid deep nesting.** If you have more than 3-4 levels of nesting, extract a method.

10. **Keys tell Flutter which widget is which.** Essential for lists, animations, and maintaining state across rebuilds.

---

## 📚 Extra Practice (Do These Tonight!)

1. **Profile Card Variations:** Create 3 different profile card designs (minimal, colorful, corporate) using only the widgets from today.

2. **Login Screen:** Build a login screen with a logo (Icon), email field (TextField), password field, login button, and "Forgot password" link. Use Column, Padding, and Container.

3. **Product Card:** Create an e-commerce product card with an image placeholder (Container with color), product name, price, rating (Row of stars), and "Add to Cart" button. Use Stack for an "SALE" badge.

4. **Settings Screen:** Build a settings list with icons, labels, and toggle switches. Use Row for each setting item.

5. **Dashboard Grid:** Create a 2x2 grid of statistic cards using Row and Column. Each card shows an icon, number, and label.

---

> 🎉 **Congratulations!** You've completed Day 6 — your first real Flutter UI day! You now understand the widget system, can build basic layouts, and know the difference between Stateless and Stateful widgets. Tomorrow, we dive deeper into layouts and constraints!

**Next Up → Day 7: Layouts & Constraints**

# 📘 Day 7: Layouts & Constraints — Complete Deep Dive
> **Goal:** Master Flutter's layout system and scrolling widgets.
> *This guide covers constraints, scrolling, lists, grids, and page views with visual explanations and hands-on projects.*

---

## Table of Contents
1. [Flutter's Layout System Explained](#1-flutters-layout-system-explained)
2. [Box Constraints: Tight vs Loose](#2-box-constraints-tight-vs-loose)
3. [Constraint Widgets Deep Dive](#3-constraint-widgets-deep-dive)
4. [Scrolling Fundamentals](#4-scrolling-fundamentals)
5. [ListView Complete Guide](#5-listview-complete-guide)
6. [GridView Complete Guide](#6-gridview-complete-guide)
7. [PageView & TabBarView](#7-pageview--tabbarview)
8. [Slivers Introduction](#8-slivers-introduction)
9. [Hands-On Project: Photo Gallery App](#9-hands-on-project-photo-gallery-app)
10. [Common Mistakes & How to Avoid Them](#10-common-mistakes--how-to-avoid-them)
11. [Day 7 Checklist](#11-day-7-checklist)

---

## 1. Flutter's Layout System Explained

### How Flutter Layout Works

Flutter uses a **single-pass, constraint-based layout system**. It works in two phases:

```
┌─────────────────────────────────────────────────────────────┐
│              Flutter Layout Two-Phase System                │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  PHASE 1: WALK DOWN (Constraints)                           │
│  ────────────────────────────────                           │
│  Parent tells child: "You must be between 100px and 300px"  │
│                                                             │
│       Parent (constraints: 0-400px)                         │
│            │                                                │
│            ▼                                                │
│       Child (receives: 0-400px)                             │
│            │                                                │
│            ▼                                                │
│       Grandchild (receives: 0-400px)                        │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  PHASE 2: WALK UP (Sizes)                                   │
│  ─────────────────────────                                  │
│  Child tells parent: "I choose to be 200px"                 │
│                                                             │
│       Parent (final size: 400px) ◄──┐                       │
│            ▲                        │                       │
│            │                        │                       │
│       Child (chooses: 200px) ──────┘                       │
│            ▲                                                │
│            │                                                │
│       Grandchild (chooses: 200px)                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### The Golden Rule of Flutter Layout

> **"Constraints go down. Sizes go up. Parent sets position."**

| Phase | Direction | What Happens |
|-------|-----------|-------------|
| **Constraints** | Top → Down | Parent passes max/min width/height to child |
| **Sizing** | Bottom → Up | Child chooses its size within constraints |
| **Positioning** | Top → Down | Parent positions child based on alignment |

### Constraint Types

```
┌─────────────────────────────────────────────────────────────┐
│              BoxConstraint Types                            │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  TIGHT CONSTRAINTS (exact size)                            │
│  ┌─────────────────┐                                        │
│  │  minW = maxW    │  → Child MUST be exactly this size    │
│  │  minH = maxH    │                                        │
│  └─────────────────┘                                        │
│  Example: Container(width: 100, height: 100)               │
│                                                             │
│  LOOSE CONSTRAINTS (any size up to max)                    │
│  ┌─────────────────┐                                        │
│  │  minW = 0       │  → Child can be any size 0 to max     │
│  │  maxW = 400     │                                        │
│  │  minH = 0       │                                        │
│  │  maxH = 800     │                                        │
│  └─────────────────┘                                        │
│  Example: Center, ListView, Column                         │
│                                                             │
│  UNBOUNDED CONSTRAINTS (infinite)                          │
│  ┌─────────────────┐                                        │
│  │  maxW = ∞       │  → Child can be ANY width             │
│  │  maxH = ∞       │                                        │
│  └─────────────────┘                                        │
│  Example: Row's main axis, ListView scroll direction        │
│                                                             │
│  ZERO CONSTRAINTS                                          │
│  ┌─────────────────┐                                        │
│  │  minW = 0       │  → Child decides everything           │
│  │  maxW = 0       │                                        │
│  └─────────────────┘                                        │
│  Example: OverflowBox                                      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 2. Box Constraints: Tight vs Loose

### Understanding Constraints with Code

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const ConstraintsDemoApp());
}

class ConstraintsDemoApp extends StatelessWidget {
  const ConstraintsDemoApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar: AppBar(title: const Text('Constraints Demo')),
        body: const ConstraintsDemoScreen(),
      ),
    );
  }
}

class ConstraintsDemoScreen extends StatelessWidget {
  const ConstraintsDemoScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return SingleChildScrollView(
      padding: const EdgeInsets.all(16),
      child: Column(
        crossAxisAlignment: CrossAxisAlignment.start,
        children: [
          _buildSection('1. Tight Constraints (Exact Size)'),
          Container(
            color: Colors.red.shade100,
            width: 200,
            height: 100,
            child: const Center(child: Text('Exactly 200x100')),
          ),

          _buildSection('2. Loose Constraints (Max Only)'),
          Container(
            color: Colors.blue.shade100,
            width: double.infinity,
            height: 100,
            child: Container(
              color: Colors.blue,
              width: 150,  // Child chooses its own size
              height: 50,
              child: const Center(
                child: Text('I chose 150x50', style: TextStyle(color: Colors.white)),
              ),
            ),
          ),

          _buildSection('3. Unbounded Width (Row)'),
          Container(
            color: Colors.green.shade100,
            height: 100,
            child: Row(
              children: [
                Container(width: 80, height: 80, color: Colors.green),
                Container(width: 80, height: 80, color: Colors.green.shade700),
                Container(width: 80, height: 80, color: Colors.green.shade900),
              ],
            ),
          ),

          _buildSection('4. Bounded by Parent (Expanded)'),
          Container(
            color: Colors.orange.shade100,
            height: 100,
            child: Row(
              children: [
                Expanded(
                  flex: 2,
                  child: Container(color: Colors.orange, child: const Center(child: Text('2/3'))),
                ),
                Expanded(
                  flex: 1,
                  child: Container(color: Colors.orange.shade800, child: const Center(child: Text('1/3'))),
                ),
              ],
            ),
          ),

          _buildSection('5. Infinite Height (Column in List)'),
          Container(
            color: Colors.purple.shade100,
            child: Column(
              mainAxisSize: MainAxisSize.min,
              children: [
                Container(height: 50, color: Colors.purple, child: const Center(child: Text('Item 1', style: TextStyle(color: Colors.white)))),
                Container(height: 50, color: Colors.purple.shade700, child: const Center(child: Text('Item 2', style: TextStyle(color: Colors.white)))),
              ],
            ),
          ),
        ],
      ),
    );
  }

  Widget _buildSection(String title) {
    return Padding(
      padding: const EdgeInsets.only(top: 24, bottom: 8),
      child: Text(
        title,
        style: const TextStyle(fontSize: 16, fontWeight: FontWeight.bold),
      ),
    );
  }
}
```

### The "RenderBox was not laid out" Error

```dart
// ❌ WRONG — Column inside Column with unbounded height
Column(
  children: [
    Column(  // Inner Column wants infinite height!
      children: [Text('A'), Text('B')],
    ),
  ],
)

// ✅ CORRECT — Use mainAxisSize: MainAxisSize.min
Column(
  children: [
    Column(
      mainAxisSize: MainAxisSize.min,  // Only take needed space
      children: [Text('A'), Text('B')],
    ),
  ],
)

// ✅ CORRECT — Wrap in Expanded
Column(
  children: [
    Expanded(  // Takes remaining space
      child: Column(
        children: [Text('A'), Text('B')],
      ),
    ),
  ],
)
```

---

## 3. Constraint Widgets Deep Dive

### 3.1 ConstrainedBox

```dart
ConstrainedBox(
  constraints: const BoxConstraints(
    minWidth: 100,
    maxWidth: 300,
    minHeight: 50,
    maxHeight: 200,
  ),
  child: Container(
    color: Colors.blue,
    // This child will be constrained by the parent
    // If it tries to be 400px wide, it will be clamped to 300px
  ),
)
```

### 3.2 SizedBox

```dart
// Fixed size
SizedBox(
  width: 200,
  height: 100,
  child: Container(color: Colors.red),
)

// Just width
SizedBox(width: 50, child: Divider())

// Just height (common for spacing)
SizedBox(height: 16)

// Expand to fill parent
SizedBox.expand(child: Container(color: Colors.green))

// Shrink to fit child
SizedBox.shrink(child: Container(color: Colors.yellow))

// Fraction of parent size
FractionallySizedBox(
  widthFactor: 0.5,   // 50% of parent width
  heightFactor: 0.3,  // 30% of parent height
  child: Container(color: Colors.purple),
)
```

### 3.3 AspectRatio

```dart
// Forces child to maintain a specific aspect ratio
AspectRatio(
  aspectRatio: 16 / 9,  // width / height
  child: Container(
    color: Colors.blue,
    child: const Center(child: Text('16:9')),
  ),
)

// Common ratios:
// 16/9 → Widescreen video
// 4/3  → Standard photo
// 1/1  → Square (Instagram)
// 9/16 → Portrait video (TikTok)

// In a GridView:
GridView.builder(
  gridDelegate: const SliverGridDelegateWithFixedCrossAxisCount(
    crossAxisCount: 2,
    childAspectRatio: 3 / 4,  // Portrait cards
  ),
  // ...
)
```

### 3.4 LimitedBox

```dart
// Only applies limits when parent gives UNBOUNDED constraints
LimitedBox(
  maxWidth: 100,
  maxHeight: 100,
  child: Container(color: Colors.red),
)
// In bounded parent: child can be any size
// In unbounded parent: child max is 100x100
```

### 3.5 OverflowBox & SizedOverflowBox

```dart
// Allows child to overflow parent's bounds
OverflowBox(
  minWidth: 0,
  maxWidth: double.infinity,
  minHeight: 0,
  maxHeight: double.infinity,
  child: Container(
    width: 300,
    height: 300,
    color: Colors.red.withOpacity(0.5),
  ),
)
// Child will be 300x300 even if parent is smaller!

// SizedOverflowBox: parent has fixed size, child can overflow
SizedOverflowBox(
  size: const Size(100, 100),
  child: Container(
    width: 150,
    height: 150,
    color: Colors.blue.withOpacity(0.5),
  ),
)
```

### 3.6 FittedBox

```dart
// Scales child to fit within parent
FittedBox(
  fit: BoxFit.contain,  // See image fit options below
  child: Container(
    width: 300,
    height: 200,
    color: Colors.red,
    child: const Text('Scaled to fit'),
  ),
)

// BoxFit options:
// contain  → Fit within bounds, maintain aspect ratio (letterbox)
// cover    → Fill bounds, maintain aspect ratio (crop)
// fill     → Fill bounds, distort aspect ratio (stretch)
// fitWidth → Match width, scale height proportionally
// fitHeight→ Match height, scale width proportionally
// none     → No scaling, clip if too big
// scaleDown→ Like contain but never scale up
```

### 3.7 LayoutBuilder

```dart
// Build different layouts based on parent constraints
LayoutBuilder(
  builder: (context, constraints) {
    if (constraints.maxWidth > 600) {
      // Tablet/Desktop layout
      return Row(
        children: [
          Expanded(flex: 1, child: SideMenu()),
          Expanded(flex: 3, child: MainContent()),
        ],
      );
    } else {
      // Mobile layout
      return Column(
        children: [
          MainContent(),
          BottomNav(),
        ],
      );
    }
  },
)
```

### 3.8 MediaQuery

```dart
Widget build(BuildContext context) {
  final mediaQuery = MediaQuery.of(context);
  final size = mediaQuery.size;
  final padding = mediaQuery.padding;
  final orientation = mediaQuery.orientation;

  return Container(
    width: size.width * 0.8,  // 80% of screen width
    height: size.height * 0.5, // 50% of screen height
    padding: EdgeInsets.only(
      top: padding.top,      // Avoid notch/status bar
      bottom: padding.bottom, // Avoid home indicator
    ),
    child: orientation == Orientation.portrait
      ? PortraitLayout()
      : LandscapeLayout(),
  );
}
```

---

## 4. Scrolling Fundamentals

### 4.1 Why Scrolling is Special

```
┌─────────────────────────────────────────────────────────────┐
│  Without ScrollView:          With ScrollView:              │
│  ──────────────────           ───────────────               │
│                                                             │
│  ┌─────────┐                 ┌─────────┐                    │
│  │ A       │                 │ A       │ ◄── Visible       │
│  │ B       │                 │ B       │                   │
│  │ C       │                 │ C       │                   │
│  │ D       │                 │ D       │                   │
│  │ E       │                 │ E       │                   │
│  │ F       │                 │ F       │                   │
│  │ G       │ ◄── Overflow!  │ G       │ ◄── Scroll down   │
│  │ H       │    (CRASH!)    │ H       │    to see         │
│  │ I       │                 │ I       │                   │
│  └─────────┘                 └─────────┘                   │
│  Content too big             Content scrolls smoothly       │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### 4.2 Scroll Physics

```dart
// Different scroll behaviors
SingleChildScrollView(
  physics: const BouncingScrollPhysics(),  // iOS-style bounce (default on iOS)
  child: Column(children: [...]),
)

SingleChildScrollView(
  physics: const ClampingScrollPhysics(),  // Android-style clamp (default on Android)
  child: Column(children: [...]),
)

SingleChildScrollView(
  physics: const NeverScrollableScrollPhysics(),  // Disable scrolling
  child: Column(children: [...]),
)

SingleChildScrollView(
  physics: const AlwaysScrollableScrollPhysics(),  // Always scrollable
  child: Column(children: [...]),
)
```

### 4.3 ScrollController

```dart
class _ScrollDemoState extends State<ScrollDemo> {
  final ScrollController _controller = ScrollController();
  bool _showFab = false;

  @override
  void initState() {
    super.initState();
    _controller.addListener(() {
      // Show FAB when scrolled past 200px
      setState(() {
        _showFab = _controller.offset > 200;
      });
    });
  }

  @override
  void dispose() {
    _controller.dispose();  // Always dispose!
    super.dispose();
  }

  void _scrollToTop() {
    _controller.animateTo(
      0,
      duration: const Duration(milliseconds: 500),
      curve: Curves.easeInOut,
    );
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: ListView.builder(
        controller: _controller,
        itemCount: 100,
        itemBuilder: (context, index) => ListTile(title: Text('Item $index')),
      ),
      floatingActionButton: _showFab
        ? FloatingActionButton(
            onPressed: _scrollToTop,
            child: const Icon(Icons.arrow_upward),
          )
        : null,
    );
  }
}
```

---

## 5. ListView Complete Guide

### 5.1 ListView (Static, Small Lists)

```dart
ListView(
  padding: const EdgeInsets.all(16),
  scrollDirection: Axis.vertical,  // vertical or horizontal
  reverse: false,                  // Start from bottom?
  physics: const BouncingScrollPhysics(),
  children: const [
    ListTile(leading: Icon(Icons.home), title: Text('Home')),
    ListTile(leading: Icon(Icons.settings), title: Text('Settings')),
    ListTile(leading: Icon(Icons.person), title: Text('Profile')),
    // ... more items
  ],
)
```

### 5.2 ListView.builder (Large/Dynamic Lists) ⭐

```dart
ListView.builder(
  itemCount: 1000,  // Can be huge! Only builds visible items.
  padding: const EdgeInsets.all(16),
  itemBuilder: (context, index) {
    return ListTile(
      leading: CircleAvatar(child: Text('$index')),
      title: Text('Item $index'),
      subtitle: Text('Subtitle for item $index'),
      trailing: const Icon(Icons.arrow_forward_ios, size: 16),
      onTap: () {
        print('Tapped item $index');
      },
    );
  },
)
```

**Why `ListView.builder` is better for large lists:**
- Only builds widgets that are **visible on screen**
- Destroys widgets that scroll **off screen** (memory efficient)
- Can handle **millions of items** without lag

```
Screen shows items 5-15:
┌─────────────────┐
│ Item 5  ◄── Built
│ Item 6  ◄── Built
│ Item 7  ◄── Built
│ ...     ◄── Built
│ Item 15 ◄── Built
│ Item 16 ◄── NOT built yet
└─────────────────┘
Items 0-4 were destroyed when they scrolled off
```

### 5.3 ListView.separated (With Dividers) ⭐

```dart
ListView.separated(
  itemCount: 50,
  itemBuilder: (context, index) {
    return ListTile(
      leading: const Icon(Icons.image),
      title: Text('Photo ${index + 1}'),
      subtitle: Text('Taken on ${DateTime.now().subtract(Duration(days: index)).toString().substring(0, 10)}'),
    );
  },
  separatorBuilder: (context, index) {
    return const Divider(
      height: 1,
      thickness: 1,
      indent: 56,  // Align with ListTile text
      endIndent: 16,
    );
  },
)
```

### 5.4 Horizontal ListView

```dart
SizedBox(
  height: 120,  // Must constrain height!
  child: ListView.builder(
    scrollDirection: Axis.horizontal,
    itemCount: 20,
    itemBuilder: (context, index) {
      return Container(
        width: 100,
        margin: const EdgeInsets.only(right: 12),
        decoration: BoxDecoration(
          color: Colors.primaries[index % Colors.primaries.length],
          borderRadius: BorderRadius.circular(12),
        ),
        child: Center(
          child: Text(
            'Card $index',
            style: const TextStyle(color: Colors.white, fontWeight: FontWeight.bold),
          ),
        ),
      );
    },
  ),
)
```

### 5.5 ListView with Different Item Types

```dart
ListView.builder(
  itemCount: items.length,
  itemBuilder: (context, index) {
    final item = items[index];

    // Different widgets for different types
    if (item is HeaderItem) {
      return _buildHeader(item);
    } else if (item is MessageItem) {
      return _buildMessage(item);
    } else if (item is AdItem) {
      return _buildAd(item);
    }
    return const SizedBox.shrink();
  },
)
```

### 5.6 Pull-to-Refresh (RefreshIndicator)

```dart
RefreshIndicator(
  onRefresh: () async {
    // Fetch new data
    await Future.delayed(const Duration(seconds: 2));
    setState(() {
      items = fetchNewItems();
    });
  },
  child: ListView.builder(
    itemCount: items.length,
    itemBuilder: (context, index) => ListTile(title: Text(items[index])),
  ),
)
```

---

## 6. GridView Complete Guide

### 6.1 GridView.count (Fixed Columns)

```dart
GridView.count(
  crossAxisCount: 2,  // 2 columns
  mainAxisSpacing: 16,   // Vertical gap
  crossAxisSpacing: 16,  // Horizontal gap
  padding: const EdgeInsets.all(16),
  childAspectRatio: 3 / 4,  // Width / Height
  children: List.generate(
    20,
    (index) => Container(
      decoration: BoxDecoration(
        color: Colors.primaries[index % Colors.primaries.length],
        borderRadius: BorderRadius.circular(12),
      ),
      child: Center(
        child: Text(
          'Item $index',
          style: const TextStyle(color: Colors.white, fontSize: 18),
        ),
      ),
    ),
  ),
)
```

### 6.2 GridView.builder (Large/Dynamic Grids) ⭐

```dart
GridView.builder(
  padding: const EdgeInsets.all(16),
  gridDelegate: const SliverGridDelegateWithFixedCrossAxisCount(
    crossAxisCount: 2,
    mainAxisSpacing: 16,
    crossAxisSpacing: 16,
    childAspectRatio: 3 / 4,
  ),
  itemCount: 1000,  // Can be huge!
  itemBuilder: (context, index) {
    return Card(
      clipBehavior: Clip.antiAlias,
      shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(12)),
      child: Column(
        crossAxisAlignment: CrossAxisAlignment.stretch,
        children: [
          Expanded(
            child: Container(
              color: Colors.primaries[index % Colors.primaries.length],
              child: const Icon(Icons.image, size: 48, color: Colors.white54),
            ),
          ),
          Padding(
            padding: const EdgeInsets.all(12),
            child: Column(
              crossAxisAlignment: CrossAxisAlignment.start,
              children: [
                Text('Item $index', style: const TextStyle(fontWeight: FontWeight.bold)),
                const SizedBox(height: 4),
                Text('\$${(index + 1) * 10}', style: TextStyle(color: Colors.green.shade700)),
              ],
            ),
          ),
        ],
      ),
    );
  },
)
```

### 6.3 GridView with Max Cross-Axis Extent

```dart
// Automatically adjusts columns based on item width
GridView.builder(
  gridDelegate: const SliverGridDelegateWithMaxCrossAxisExtent(
    maxCrossAxisExtent: 150,  // Each item max 150px wide
    mainAxisSpacing: 16,
    crossAxisSpacing: 16,
    childAspectRatio: 1,  // Square items
  ),
  itemCount: 50,
  itemBuilder: (context, index) {
    return Container(
      color: Colors.primaries[index % Colors.primaries.length],
      child: Center(child: Text('$index')),
    );
  },
)

// Result:
// On narrow screen (320px): 2 columns (150px each + gap)
// On medium screen (400px): 2 columns
// On wide screen (600px): 4 columns
```

### 6.4 Staggered Grid (Using flutter_staggered_grid_view package)

```dart
// Add to pubspec.yaml: flutter_staggered_grid_view: ^0.7.0

MasonryGridView.count(
  crossAxisCount: 2,
  mainAxisSpacing: 16,
  crossAxisSpacing: 16,
  itemCount: 20,
  itemBuilder: (context, index) {
    // Different heights create staggered effect
    final height = 100 + (index % 5) * 50.0;
    return Container(
      height: height,
      decoration: BoxDecoration(
        color: Colors.primaries[index % Colors.primaries.length],
        borderRadius: BorderRadius.circular(12),
      ),
      child: Center(child: Text('Item $index')),
    );
  },
)
```

---

## 7. PageView & TabBarView

### 7.1 PageView

```dart
class PageViewDemo extends StatefulWidget {
  const PageViewDemo({super.key});

  @override
  State<PageViewDemo> createState() => _PageViewDemoState();
}

class _PageViewDemoState extends State<PageViewDemo> {
  final PageController _pageController = PageController();
  int _currentPage = 0;

  @override
  void dispose() {
    _pageController.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('PageView Demo')),
      body: Column(
        children: [
          // Page indicator
          Row(
            mainAxisAlignment: MainAxisAlignment.center,
            children: List.generate(3, (index) {
              return Container(
                width: 8,
                height: 8,
                margin: const EdgeInsets.symmetric(horizontal: 4, vertical: 16),
                decoration: BoxDecoration(
                  shape: BoxShape.circle,
                  color: _currentPage == index ? Colors.blue : Colors.grey,
                ),
              );
            }),
          ),

          // PageView
          Expanded(
            child: PageView(
              controller: _pageController,
              onPageChanged: (index) {
                setState(() => _currentPage = index);
              },
              // physics: const BouncingScrollPhysics(),
              // scrollDirection: Axis.vertical,  // Can be vertical too!
              children: const [
                PageContent(color: Colors.red, title: 'Page 1'),
                PageContent(color: Colors.green, title: 'Page 2'),
                PageContent(color: Colors.blue, title: 'Page 3'),
              ],
            ),
          ),

          // Navigation buttons
          Row(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: [
              ElevatedButton(
                onPressed: () {
                  _pageController.previousPage(
                    duration: const Duration(milliseconds: 300),
                    curve: Curves.easeInOut,
                  );
                },
                child: const Text('Previous'),
              ),
              ElevatedButton(
                onPressed: () {
                  _pageController.nextPage(
                    duration: const Duration(milliseconds: 300),
                    curve: Curves.easeInOut,
                  );
                },
                child: const Text('Next'),
              ),
            ],
          ),
          const SizedBox(height: 16),
        ],
      ),
    );
  }
}

class PageContent extends StatelessWidget {
  final Color color;
  final String title;
  const PageContent({super.key, required this.color, required this.title});

  @override
  Widget build(BuildContext context) {
    return Container(
      color: color.withOpacity(0.2),
      margin: const EdgeInsets.all(16),
      child: Center(
        child: Text(
          title,
          style: TextStyle(fontSize: 32, color: color, fontWeight: FontWeight.bold),
        ),
      ),
    );
  }
}
```

### 7.2 PageView.builder (Dynamic Pages)

```dart
PageView.builder(
  itemCount: 10,
  itemBuilder: (context, index) {
    return Container(
      color: Colors.primaries[index % Colors.primaries.length].withOpacity(0.2),
      child: Center(child: Text('Page $index', style: const TextStyle(fontSize: 32))),
    );
  },
)
```

### 7.3 TabBar + TabBarView

```dart
class TabBarDemo extends StatelessWidget {
  const TabBarDemo({super.key});

  @override
  Widget build(BuildContext context) {
    return DefaultTabController(
      length: 3,  // Number of tabs
      child: Scaffold(
        appBar: AppBar(
          title: const Text('TabBar Demo'),
          bottom: const TabBar(
            tabs: [
              Tab(icon: Icon(Icons.home), text: 'Home'),
              Tab(icon: Icon(Icons.favorite), text: 'Favorites'),
              Tab(icon: Icon(Icons.settings), text: 'Settings'),
            ],
            indicatorColor: Colors.white,
            indicatorWeight: 3,
            labelColor: Colors.white,
            unselectedLabelColor: Colors.white70,
          ),
        ),
        body: const TabBarView(
          children: [
            HomeTab(),
            FavoritesTab(),
            SettingsTab(),
          ],
        ),
      ),
    );
  }
}

class HomeTab extends StatelessWidget {
  const HomeTab({super.key});
  @override
  Widget build(BuildContext context) {
    return ListView.builder(
      itemCount: 20,
      itemBuilder: (context, index) => ListTile(title: Text('Home Item $index')),
    );
  }
}

class FavoritesTab extends StatelessWidget {
  const FavoritesTab({super.key});
  @override
  Widget build(BuildContext context) {
    return const Center(child: Text('Favorites', style: TextStyle(fontSize: 24)));
  }
}

class SettingsTab extends StatelessWidget {
  const SettingsTab({super.key});
  @override
  Widget build(BuildContext context) {
    return ListView(
      children: const [
        ListTile(leading: Icon(Icons.person), title: Text('Account')),
        ListTile(leading: Icon(Icons.notifications), title: Text('Notifications')),
        ListTile(leading: Icon(Icons.security), title: Text('Privacy')),
        ListTile(leading: Icon(Icons.help), title: Text('Help')),
      ],
    );
  }
}
```

### 7.4 Bottom Navigation Bar with PageView

```dart
class BottomNavWithPageView extends StatefulWidget {
  const BottomNavWithPageView({super.key});

  @override
  State<BottomNavWithPageView> createState() => _BottomNavWithPageViewState();
}

class _BottomNavWithPageViewState extends State<BottomNavWithPageView> {
  final PageController _pageController = PageController();
  int _currentIndex = 0;

  final _pages = const [
    HomePage(),
    SearchPage(),
    ProfilePage(),
  ];

  @override
  void dispose() {
    _pageController.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: PageView(
        controller: _pageController,
        onPageChanged: (index) => setState(() => _currentIndex = index),
        children: _pages,
      ),
      bottomNavigationBar: BottomNavigationBar(
        currentIndex: _currentIndex,
        onTap: (index) {
          _pageController.animateToPage(
            index,
            duration: const Duration(milliseconds: 300),
            curve: Curves.easeInOut,
          );
        },
        items: const [
          BottomNavigationBarItem(icon: Icon(Icons.home), label: 'Home'),
          BottomNavigationBarItem(icon: Icon(Icons.search), label: 'Search'),
          BottomNavigationBarItem(icon: Icon(Icons.person), label: 'Profile'),
        ],
      ),
    );
  }
}
```

---

## 8. Slivers Introduction

### 8.1 What are Slivers?

Slivers are scrollable areas that can **scroll in special ways** — collapsing headers, parallax effects, pinned items.

```dart
CustomScrollView(
  slivers: [
    // Collapsing app bar
    SliverAppBar(
      expandedHeight: 200,
      flexibleSpace: FlexibleSpaceBar(
        title: const Text('Gallery'),
        background: Image.asset('assets/header.jpg', fit: BoxFit.cover),
      ),
      pinned: true,  // Stays visible when collapsed
      floating: true, // Appears when scrolling up
    ),

    // Grid in scroll view
    SliverGrid(
      gridDelegate: const SliverGridDelegateWithFixedCrossAxisCount(
        crossAxisCount: 2,
      ),
      delegate: SliverChildBuilderDelegate(
        (context, index) => Container(color: Colors.primaries[index % 18]),
        childCount: 20,
      ),
    ),

    // List in scroll view
    SliverList(
      delegate: SliverChildBuilderDelegate(
        (context, index) => ListTile(title: Text('Item $index')),
        childCount: 50,
      ),
    ),
  ],
)
```

### 8.2 Common Sliver Widgets

```dart
CustomScrollView(
  slivers: [
    // Fixed header
    SliverToBoxAdapter(
      child: Container(
        height: 100,
        color: Colors.blue,
        child: const Center(child: Text('Header', style: TextStyle(color: Colors.white))),
      ),
    ),

    // Pinned header
    SliverPersistentHeader(
      pinned: true,
      delegate: _SliverHeaderDelegate(),
    ),

    // Padding around sliver
    SliverPadding(
      padding: const EdgeInsets.all(16),
      sliver: SliverList(...),
    ),

    // Fill remaining space
    SliverFillRemaining(
      child: Center(child: Text('Footer')),
    ),
  ],
)
```

---

## 9. Hands-On Project: Photo Gallery App

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const PhotoGalleryApp());
}

class PhotoGalleryApp extends StatelessWidget {
  const PhotoGalleryApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.indigo),
        useMaterial3: true,
      ),
      home: const GalleryHomePage(),
    );
  }
}

class GalleryHomePage extends StatefulWidget {
  const GalleryHomePage({super.key});

  @override
  State<GalleryHomePage> createState() => _GalleryHomePageState();
}

class _GalleryHomePageState extends State<GalleryHomePage> {
  int _selectedIndex = 0;
  final PageController _pageController = PageController();

  @override
  void dispose() {
    _pageController.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('Photo Gallery'),
        actions: [
          IconButton(icon: const Icon(Icons.search), onPressed: () {}),
          IconButton(icon: const Icon(Icons.more_vert), onPressed: () {}),
        ],
      ),
      body: PageView(
        controller: _pageController,
        onPageChanged: (index) => setState(() => _selectedIndex = index),
        children: const [
          AllPhotosTab(),
          AlbumsTab(),
          FavoritesTab(),
        ],
      ),
      bottomNavigationBar: NavigationBar(
        selectedIndex: _selectedIndex,
        onDestinationSelected: (index) {
          _pageController.jumpToPage(index);
        },
        destinations: const [
          NavigationDestination(icon: Icon(Icons.photo_library), label: 'All'),
          NavigationDestination(icon: Icon(Icons.folder), label: 'Albums'),
          NavigationDestination(icon: Icon(Icons.favorite), label: 'Favorites'),
        ],
      ),
    );
  }
}

// Tab 1: All Photos (Grid View)
class AllPhotosTab extends StatelessWidget {
  const AllPhotosTab({super.key});

  @override
  Widget build(BuildContext context) {
    return CustomScrollView(
      slivers: [
        // Horizontal featured scroll
        SliverToBoxAdapter(
          child: Column(
            crossAxisAlignment: CrossAxisAlignment.start,
            children: [
              const Padding(
                padding: EdgeInsets.fromLTRB(16, 16, 16, 8),
                child: Text('Featured', style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
              ),
              SizedBox(
                height: 180,
                child: ListView.builder(
                  scrollDirection: Axis.horizontal,
                  padding: const EdgeInsets.symmetric(horizontal: 16),
                  itemCount: 10,
                  itemBuilder: (context, index) {
                    return Container(
                      width: 280,
                      margin: const EdgeInsets.only(right: 12),
                      decoration: BoxDecoration(
                        color: Colors.primaries[index % Colors.primaries.length],
                        borderRadius: BorderRadius.circular(16),
                        image: const DecorationImage(
                          image: NetworkImage('https://picsum.photos/280/180'),
                          fit: BoxFit.cover,
                        ),
                      ),
                      child: Container(
                        decoration: BoxDecoration(
                          borderRadius: BorderRadius.circular(16),
                          gradient: LinearGradient(
                            begin: Alignment.bottomCenter,
                            end: Alignment.topCenter,
                            colors: [Colors.black.withOpacity(0.7), Colors.transparent],
                          ),
                        ),
                        padding: const EdgeInsets.all(16),
                        alignment: Alignment.bottomLeft,
                        child: Text(
                          'Photo ${index + 1}',
                          style: const TextStyle(color: Colors.white, fontSize: 18, fontWeight: FontWeight.bold),
                        ),
                      ),
                    );
                  },
                ),
              ),
            ],
          ),
        ),

        // Grid section header
        const SliverToBoxAdapter(
          child: Padding(
            padding: EdgeInsets.fromLTRB(16, 24, 16, 12),
            child: Text('All Photos', style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
          ),
        ),

        // Photo grid
        SliverPadding(
          padding: const EdgeInsets.symmetric(horizontal: 16),
          sliver: SliverGrid(
            gridDelegate: const SliverGridDelegateWithFixedCrossAxisCount(
              crossAxisCount: 3,
              mainAxisSpacing: 8,
              crossAxisSpacing: 8,
              childAspectRatio: 1,
            ),
            delegate: SliverChildBuilderDelegate(
              (context, index) {
                return ClipRRect(
                  borderRadius: BorderRadius.circular(8),
                  child: Container(
                    color: Colors.grey.shade300,
                    child: Stack(
                      fit: StackFit.expand,
                      children: [
                        Image.network(
                          'https://picsum.photos/200/200?random=$index',
                          fit: BoxFit.cover,
                        ),
                        if (index % 5 == 0)
                          Positioned(
                            top: 4,
                            right: 4,
                            child: Container(
                              padding: const EdgeInsets.all(4),
                              decoration: const BoxDecoration(
                                color: Colors.red,
                                shape: BoxShape.circle,
                              ),
                              child: const Icon(Icons.favorite, size: 12, color: Colors.white),
                            ),
                          ),
                      ],
                    ),
                  ),
                );
              },
              childCount: 30,
            ),
          ),
        ),

        const SliverToBoxAdapter(child: SizedBox(height: 24)),
      ],
    );
  }
}

// Tab 2: Albums (List View)
class AlbumsTab extends StatelessWidget {
  const AlbumsTab({super.key});

  @override
  Widget build(BuildContext context) {
    final albums = [
      ('Vacation 2024', 45, Colors.blue),
      ('Family', 128, Colors.green),
      ('Work', 32, Colors.orange),
      ('Nature', 67, Colors.teal),
      ('Food', 23, Colors.red),
      ('Selfies', 89, Colors.purple),
    ];

    return ListView.separated(
      padding: const EdgeInsets.all(16),
      itemCount: albums.length,
      separatorBuilder: (_, __) => const SizedBox(height: 12),
      itemBuilder: (context, index) {
        final (name, count, color) = albums[index];
        return Container(
          height: 100,
          decoration: BoxDecoration(
            color: color.withOpacity(0.1),
            borderRadius: BorderRadius.circular(16),
            border: Border.all(color: color.withOpacity(0.3)),
          ),
          child: Row(
            children: [
              Container(
                width: 100,
                height: 100,
                decoration: BoxDecoration(
                  color: color,
                  borderRadius: const BorderRadius.horizontal(left: Radius.circular(16)),
                ),
                child: const Icon(Icons.folder, color: Colors.white, size: 40),
              ),
              const SizedBox(width: 16),
              Expanded(
                child: Column(
                  mainAxisAlignment: MainAxisAlignment.center,
                  crossAxisAlignment: CrossAxisAlignment.start,
                  children: [
                    Text(name, style: const TextStyle(fontSize: 18, fontWeight: FontWeight.bold)),
                    const SizedBox(height: 4),
                    Text('$count photos', style: TextStyle(color: Colors.grey.shade600)),
                  ],
                ),
              ),
              const Icon(Icons.chevron_right, color: Colors.grey),
              const SizedBox(width: 16),
            ],
          ),
        );
      },
    );
  }
}

// Tab 3: Favorites (Staggered/Detailed List)
class FavoritesTab extends StatelessWidget {
  const FavoritesTab({super.key});

  @override
  Widget build(BuildContext context) {
    return ListView.builder(
      padding: const EdgeInsets.all(16),
      itemCount: 15,
      itemBuilder: (context, index) {
        return Card(
          margin: const EdgeInsets.only(bottom: 12),
          clipBehavior: Clip.antiAlias,
          shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(16)),
          child: Column(
            crossAxisAlignment: CrossAxisAlignment.stretch,
            children: [
              AspectRatio(
                aspectRatio: 16 / 9,
                child: Image.network(
                  'https://picsum.photos/400/225?random=${index + 100}',
                  fit: BoxFit.cover,
                ),
              ),
              Padding(
                padding: const EdgeInsets.all(16),
                child: Row(
                  children: [
                    const Icon(Icons.favorite, color: Colors.red),
                    const SizedBox(width: 8),
                    Text('Favorite Photo ${index + 1}'),
                    const Spacer(),
                    Text(
                      '${DateTime.now().subtract(Duration(days: index)).toString().substring(0, 10)}',
                      style: TextStyle(color: Colors.grey.shade600, fontSize: 12),
                    ),
                  ],
                ),
              ),
            ],
          ),
        );
      },
    );
  }
}
```

---

## 10. Common Mistakes & How to Avoid Them

### Mistake 1: Unbounded Height in Column
```dart
// ❌ WRONG
Column(
  children: [
    ListView(  // ListView wants infinite height!
      children: [...],
    ),
  ],
)

// ✅ CORRECT — Wrap in Expanded
Column(
  children: [
    Expanded(
      child: ListView(children: [...]),
    ),
  ],
)

// ✅ CORRECT — Use shrinkWrap
Column(
  children: [
    ListView(
      shrinkWrap: true,  // Only take needed space
      children: [...],
    ),
  ],
)
```

### Mistake 2: Horizontal ListView Without Height
```dart
// ❌ WRONG
ListView(
  scrollDirection: Axis.horizontal,
  children: [...],  // No height constraint = crash!
)

// ✅ CORRECT — Wrap in SizedBox
SizedBox(
  height: 120,
  child: ListView(
    scrollDirection: Axis.horizontal,
    children: [...],
  ),
)
```

### Mistake 3: Not Using builder for Large Lists
```dart
// ❌ WRONG — Builds ALL items immediately
ListView(
  children: List.generate(10000, (i) => ListTile(title: Text('$i'))),
)

// ✅ CORRECT — Only builds visible items
ListView.builder(
  itemCount: 10000,
  itemBuilder: (context, i) => ListTile(title: Text('$i')),
)
```

### Mistake 4: Forgetting to Dispose ScrollController
```dart
// ❌ WRONG — Memory leak!
class MyWidget extends StatefulWidget {
  final controller = ScrollController();  // Created but never disposed!
  // ...
}

// ✅ CORRECT
class _MyWidgetState extends State<MyWidget> {
  final _controller = ScrollController();

  @override
  void dispose() {
    _controller.dispose();  // Always dispose!
    super.dispose();
  }
}
```

### Mistake 5: Nested Scrolling Conflicts
```dart
// ❌ WRONG — Nested ListViews both try to scroll
ListView(
  children: [
    ListView(  // Inner ListView won't scroll!
      shrinkWrap: true,
      children: [...],
    ),
  ],
)

// ✅ CORRECT — Use physics: NeverScrollableScrollPhysics
ListView(
  children: [
    ListView(
      physics: const NeverScrollableScrollPhysics(),
      shrinkWrap: true,
      children: [...],
    ),
  ],
)
```

### Mistake 6: GridView Without Proper Aspect Ratio
```dart
// ❌ WRONG — Items overflow or look weird
GridView.count(
  crossAxisCount: 2,
  children: [...],  // No aspect ratio specified
)

// ✅ CORRECT — Specify aspect ratio
GridView.count(
  crossAxisCount: 2,
  childAspectRatio: 3 / 4,  // Portrait cards
  children: [...],
)
```

### Mistake 7: Using SingleChildScrollView with Column for Long Lists
```dart
// ❌ WRONG — Builds all items at once
SingleChildScrollView(
  child: Column(
    children: List.generate(1000, (i) => ListTile(title: Text('$i'))),
  ),
)

// ✅ CORRECT — Use ListView.builder
ListView.builder(
  itemCount: 1000,
  itemBuilder: (context, i) => ListTile(title: Text('$i')),
)
```

### Mistake 8: PageView Without Expanded in Column
```dart
// ❌ WRONG — PageView needs bounded size
Column(
  children: [
    PageView(  // Wants infinite height!
      children: [...],
    ),
  ],
)

// ✅ CORRECT — Wrap in Expanded
Column(
  children: [
    Expanded(
      child: PageView(children: [...]),
    ),
  ],
)
```

---

## 11. Day 7 Checklist

Use this checklist to verify mastery:

- [ ] Understands Flutter's two-phase layout system (constraints down, sizes up)
- [ ] Can explain tight vs loose vs unbounded constraints
- [ ] Can use ConstrainedBox to limit child size
- [ ] Can use SizedBox for fixed dimensions and spacing
- [ ] Can use AspectRatio to maintain proportions
- [ ] Can use FittedBox to scale children
- [ ] Can use LayoutBuilder for responsive layouts
- [ ] Can use MediaQuery to access screen dimensions
- [ ] Understands scroll physics (Bouncing, Clamping, NeverScrollable)
- [ ] Can use ScrollController to listen and control scroll position
- [ ] Can implement pull-to-refresh with RefreshIndicator
- [ ] Can build efficient lists with ListView.builder
- [ ] Can add separators with ListView.separated
- [ ] Can build horizontal scrolling lists
- [ ] Can build grids with GridView.count and GridView.builder
- [ ] Can use SliverGridDelegateWithMaxCrossAxisExtent for responsive grids
- [ ] Can build page-based UIs with PageView
- [ ] Can implement TabBar + TabBarView
- [ ] Can combine BottomNavigationBar with PageView
- [ ] Understands basic slivers (SliverAppBar, SliverList, SliverGrid)
- [ ] Built the Photo Gallery App with 3 tabs (Grid, Albums, Favorites)
- [ ] Can identify and fix common layout errors (unbounded height, overflow)
- [ ] Pushed the project to GitHub

---

## 🧠 Key Takeaways (Memorize These!)

1. **"Constraints go down, sizes go up, parent sets position."** This is the golden rule of Flutter layout.

2. **Tight constraints = exact size.** Loose constraints = any size up to max. Unbounded = infinite.

3. **Use `ListView.builder` for large lists.** It only builds visible items and destroys off-screen ones.

4. **Use `ListView.separated` for lists with dividers.** Cleaner than manually adding Dividers.

5. **Horizontal ListViews MUST have a bounded height.** Wrap them in SizedBox.

6. **GridView needs `childAspectRatio`.** Without it, items look wrong or overflow.

7. **Always dispose ScrollControllers and PageControllers.** They cause memory leaks.

8. **Use `Expanded` or `shrinkWrap: true` when putting scrollable inside Column.** Otherwise you get unbounded height errors.

9. **CustomScrollView + Slivers** create advanced scrolling effects like collapsing headers and parallax.

10. **PageView + BottomNavigationBar** is the standard pattern for multi-screen apps with swipe navigation.

---

## 📚 Extra Practice (Do These Tonight!)

1. **E-Commerce Product Grid:** Build a product grid with 2 columns, cards with image, title, price, and rating. Add a horizontal "Featured" scroll at the top.

2. **Chat Interface:** Build a chat screen with ListView.builder showing messages. Alternate left/right alignment for sender/receiver. Add a sticky date header.

3. **Settings Screen:** Build a settings page with sections (Account, Notifications, Privacy). Use ListView with different item types (headers, toggles, navigation items).

4. **Onboarding Flow:** Create a 3-page onboarding using PageView with dot indicators, skip button, and "Get Started" button on the last page.

5. **Photo Timeline:** Build a vertical scrolling timeline with year headers (sticky) and photo grids under each year using CustomScrollView with slivers.

---

> 🎉 **Congratulations!** You've completed Day 7. You now understand Flutter's constraint-based layout system, can build efficient scrolling lists and grids, and can create page-based navigation. These are the core skills for building any scrollable Flutter app.

**Next Up → Day 8: Input, Forms & Validation**


# 📘 Day 8: Input, Forms & Validation — Complete Deep Dive
> **Goal:** Handle user input professionally with TextField, forms, validation, and keyboard management.
> *This guide covers every input widget, controller, validator pattern, and a complete registration form project.*

---

## Table of Contents
1. [Why Forms Matter in Flutter](#1-why-forms-matter-in-flutter)
2. [TextField vs TextFormField](#2-textfield-vs-textformfield)
3. [TextEditingController Deep Dive](#3-texteditingcontroller-deep-dive)
4. [InputDecoration Mastery](#4-inputdecoration-mastery)
5. [FocusNode & Keyboard Management](#5-focusnode--keyboard-management)
6. [The Form Widget & GlobalKey<FormState>](#6-the-form-widget--globalkeyformstate)
7. [Validation Logic](#7-validation-logic)
8. [Keyboard Types & Actions](#8-keyboard-types--actions)
9. [Advanced Input Features](#9-advanced-input-features)
10. [Hands-On Project: Registration Form](#10-hands-on-project-registration-form)
11. [Common Mistakes & How to Avoid Them](#11-common-mistakes--how-to-avoid-them)
12. [Day 8 Checklist](#12-day-8-checklist)

---

## 1. Why Forms Matter in Flutter

### Forms Are Everywhere
Every app collects user input:
- 🔐 Login / Signup screens
- 📝 Profile editing
- 💳 Payment details
- 🔍 Search bars
- 💬 Chat input
- ⚙️ Settings

### The Input Challenge
```
┌─────────────────────────────────────────────────────────────┐
│  Input handling is MORE than just a text box:               │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ✓ Capture text as user types                               │
│  ✓ Validate input (email format, password strength)         │
│  ✓ Show error messages                                      │
│  ✓ Manage focus (next field, done button)                   │
│  ✓ Handle keyboard (types, actions, dismissal)              │
│  ✓ Format input (phone numbers, credit cards)               │
│  ✓ Show/hide password                                       │
│  ✓ Submit form with validation                              │
│  ✓ Clear/reset fields                                       │
│  ✓ Accessibility (labels, hints)                            │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 2. TextField vs TextFormField

### TextField — Standalone Input

```dart
// Basic TextField — good for simple inputs
TextField(
  decoration: const InputDecoration(
    labelText: 'Username',
    hintText: 'Enter your username',
  ),
)

// TextField with controller
TextField(
  controller: _usernameController,
  decoration: const InputDecoration(
    labelText: 'Username',
  ),
  onChanged: (value) {
    print('User typed: $value');
  },
  onSubmitted: (value) {
    print('User submitted: $value');
  },
)
```

**When to use TextField:**
- Simple one-off inputs (search bar, chat input)
- Custom validation logic
- Inputs outside of a form

### TextFormField — Form-Aware Input ⭐

```dart
// TextFormField — integrates with Form widget
TextFormField(
  decoration: const InputDecoration(
    labelText: 'Email',
  ),
  validator: (value) {
    if (value == null || value.isEmpty) {
      return 'Please enter your email';
    }
    if (!value.contains('@')) {
      return 'Please enter a valid email';
    }
    return null;  // Valid!
  },
  onSaved: (value) {
    _email = value;  // Save when form is submitted
  },
)
```

**When to use TextFormField:**
- Multiple related inputs (registration, login)
- Built-in validation with `validator`
- Form-wide operations (validate all, save all, reset)

### Comparison Table

| Feature | TextField | TextFormField |
|---------|-----------|---------------|
| **Standalone** | ✅ Yes | ✅ Yes |
| **Form integration** | ❌ Manual | ✅ Built-in |
| **validator** | ❌ No | ✅ Yes |
| **onSaved** | ❌ No | ✅ Yes |
| **Controller** | ✅ Yes | ✅ Yes |
| **Best for** | Simple inputs | Forms with validation |

---

## 3. TextEditingController Deep Dive

### What is a Controller?

A `TextEditingController` is the **brain** of a text field. It:
- Reads the current text
- Sets text programmatically
- Listens to text changes
- Controls selection/cursor

```dart
class _MyFormState extends State<MyForm> {
  // Create controllers
  final _nameController = TextEditingController();
  final _emailController = TextEditingController();
  final _passwordController = TextEditingController();

  @override
  void dispose() {
    // ALWAYS dispose controllers!
    _nameController.dispose();
    _emailController.dispose();
    _passwordController.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        TextField(controller: _nameController),
        ElevatedButton(
          onPressed: () {
            // Read text
            print('Name: ${_nameController.text}');

            // Set text
            _emailController.text = 'user@example.com';

            // Clear text
            _passwordController.clear();
          },
          child: const Text('Process'),
        ),
      ],
    );
  }
}
```

### Controller Methods & Properties

```dart
final controller = TextEditingController();

// Properties
controller.text = 'Hello';        // Set text
String current = controller.text; // Get text

// Selection (cursor position)
controller.selection = TextSelection(
  baseOffset: 0,
  extentOffset: controller.text.length,
);  // Select all text

// Move cursor to end
controller.selection = TextSelection.collapsed(
  offset: controller.text.length,
);

// Methods
controller.clear();               // Empty the field
controller.text = '';             // Same as clear()

// Listener
controller.addListener(() {
  print('Text changed: ${controller.text}');
});

// Remove listener (in dispose)
controller.removeListener(myListener);
```

### Initial Value Pattern

```dart
// ❌ WRONG — Don't use both initialValue and controller
TextFormField(
  initialValue: 'Kimi',           // ❌ Conflict!
  controller: _nameController,    // ❌ Don't use both!
)

// ✅ CORRECT — Use controller for initial value
@override
void initState() {
  super.initState();
  _nameController = TextEditingController(text: 'Kimi');
}

// ✅ CORRECT — Use initialValue without controller
TextFormField(
  initialValue: 'Kimi',  // OK when no controller needed
)
```

---

## 4. InputDecoration Mastery

### Complete InputDecoration

```dart
TextField(
  decoration: InputDecoration(
    // Label
    labelText: 'Email Address',
    labelStyle: TextStyle(color: Colors.grey.shade600),
    floatingLabelStyle: TextStyle(color: Colors.blue, fontWeight: FontWeight.bold),

    // Hint
    hintText: 'example@email.com',
    hintStyle: TextStyle(color: Colors.grey.shade400),

    // Helper text (below field)
    helperText: 'We will never share your email',
    helperStyle: TextStyle(fontSize: 12),

    // Error text (shown when validation fails)
    errorText: null,  // Set by validator
    errorStyle: TextStyle(color: Colors.red.shade700),
    errorMaxLines: 2,

    // Prefix (inside field, before text)
    prefixIcon: const Icon(Icons.email),
    prefixText: '+91 ',
    prefixStyle: TextStyle(color: Colors.grey.shade700),

    // Suffix (inside field, after text)
    suffixIcon: IconButton(
      icon: const Icon(Icons.clear),
      onPressed: () => _controller.clear(),
    ),
    suffixText: '@gmail.com',

    // Counter (character count)
    counterText: '0/100',
    counterStyle: TextStyle(fontSize: 12),

    // Border styles
    border: OutlineInputBorder(           // Default border
      borderRadius: BorderRadius.circular(12),
    ),
    enabledBorder: OutlineInputBorder(     // When NOT focused
      borderRadius: BorderRadius.circular(12),
      borderSide: BorderSide(color: Colors.grey.shade300),
    ),
    focusedBorder: OutlineInputBorder(     // When focused
      borderRadius: BorderRadius.circular(12),
      borderSide: const BorderSide(color: Colors.blue, width: 2),
    ),
    errorBorder: OutlineInputBorder(       // When has error
      borderRadius: BorderRadius.circular(12),
      borderSide: const BorderSide(color: Colors.red),
    ),
    focusedErrorBorder: OutlineInputBorder( // Focused + error
      borderRadius: BorderRadius.circular(12),
      borderSide: const BorderSide(color: Colors.red, width: 2),
    ),
    disabledBorder: OutlineInputBorder(    // When disabled
      borderRadius: BorderRadius.circular(12),
      borderSide: BorderSide(color: Colors.grey.shade200),
    ),

    // Fill
    filled: true,
    fillColor: Colors.grey.shade50,

    // Content padding
    contentPadding: const EdgeInsets.symmetric(horizontal: 16, vertical: 14),

    // Constraints
    constraints: const BoxConstraints(maxWidth: 400),

    // Visual density
    isDense: false,  // true = more compact

    // Align label
    alignLabelWithHint: true,

    // Floating label behavior
    floatingLabelBehavior: FloatingLabelBehavior.auto,  // auto, always, never
  ),
)
```

### Border Styles Visual Guide

```
┌─────────────────────────────────────────────────────────────┐
│              Input Border Styles                            │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  UnderlineInputBorder (default for TextField)              │
│  ───────────────────────────────────────────                │
│  ┌─────────────────────┐                                    │
│  │  Label              │  ← No border, just underline       │
│  └─────────────────────┘                                    │
│       ───────────                                           │
│                                                             │
│  OutlineInputBorder (default for TextFormField)            │
│  ───────────────────────────────────────────────            │
│  ┌─────────────────────┐                                    │
│  │  Label              │  ← Full border around field        │
│  └─────────────────────┘                                    │
│                                                             │
│  InputBorder.none                                          │
│  ─────────────────                                         │
│  ┌─────────────────────┐                                    │
│  │  Label              │  ← No border at all               │
│  └─────────────────────┘                                    │
│                                                             │
│  Rounded with filled background                            │
│  ───────────────────────────────                           │
│  ┌─────────────────────┐                                    │
│  │  Label              │  ← Border + background color       │
│  └─────────────────────┘                                    │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### Beautiful Input Styles

```dart
// Style 1: Modern Outline
InputDecoration(
  labelText: 'Username',
  border: OutlineInputBorder(
    borderRadius: BorderRadius.circular(12),
    borderSide: BorderSide.none,
  ),
  filled: true,
  fillColor: Colors.grey.shade100,
  prefixIcon: const Icon(Icons.person_outline),
)

// Style 2: Underline with Icon
InputDecoration(
  labelText: 'Email',
  prefixIcon: const Icon(Icons.email_outlined),
  border: const UnderlineInputBorder(),
  focusedBorder: const UnderlineInputBorder(
    borderSide: BorderSide(color: Colors.blue, width: 2),
  ),
)

// Style 3: No Border (Clean)
InputDecoration(
  hintText: 'Search...',
  prefixIcon: const Icon(Icons.search),
  border: InputBorder.none,
  filled: true,
  fillColor: Colors.grey.shade100,
  contentPadding: const EdgeInsets.all(16),
)

// Style 4: Rounded with Shadow (Card-like)
InputDecoration(
  labelText: 'Password',
  border: OutlineInputBorder(
    borderRadius: BorderRadius.circular(30),
    borderSide: BorderSide.none,
  ),
  filled: true,
  fillColor: Colors.white,
  contentPadding: const EdgeInsets.symmetric(horizontal: 24, vertical: 16),
)
```

---

## 5. FocusNode & Keyboard Management

### What is Focus?

Focus determines **which widget receives keyboard input**. Only one widget can have focus at a time.

```dart
class _FocusDemoState extends State<FocusDemo> {
  final _nameFocus = FocusNode();
  final _emailFocus = FocusNode();
  final _passwordFocus = FocusNode();

  @override
  void dispose() {
    _nameFocus.dispose();
    _emailFocus.dispose();
    _passwordFocus.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        TextField(
          focusNode: _nameFocus,
          textInputAction: TextInputAction.next,
          onSubmitted: (_) {
            // Move focus to next field
            FocusScope.of(context).requestFocus(_emailFocus);
          },
        ),
        TextField(
          focusNode: _emailFocus,
          textInputAction: TextInputAction.next,
          onSubmitted: (_) {
            FocusScope.of(context).requestFocus(_passwordFocus);
          },
        ),
        TextField(
          focusNode: _passwordFocus,
          textInputAction: TextInputAction.done,
          onSubmitted: (_) {
            _submitForm();
          },
        ),
      ],
    );
  }

  void _submitForm() {
    // Dismiss keyboard
    FocusScope.of(context).unfocus();
    // Process form...
  }
}
```

### FocusNode Methods

```dart
final focusNode = FocusNode();

// Check if focused
bool isFocused = focusNode.hasFocus;

// Request focus (show keyboard)
focusNode.requestFocus();

// Unfocus (hide keyboard)
focusNode.unfocus();

// Using FocusScope
FocusScope.of(context).requestFocus(nextFocusNode);  // Move to next
FocusScope.of(context).unfocus();                     // Hide keyboard
FocusScope.of(context).previousFocus();               // Move to previous

// Listener
focusNode.addListener(() {
  if (focusNode.hasFocus) {
    print('Field is now focused');
  } else {
    print('Field lost focus');
  }
});
```

### Dismissing Keyboard on Tap Outside

```dart
class _MyPageState extends State<MyPage> {
  @override
  Widget build(BuildContext context) {
    return GestureDetector(
      onTap: () => FocusScope.of(context).unfocus(),
      child: Scaffold(
        appBar: AppBar(title: const Text('Form')),
        body: const SingleChildScrollView(
          padding: EdgeInsets.all(16),
          child: MyForm(),
        ),
      ),
    );
  }
}
```

---

## 6. The Form Widget & GlobalKey<FormState>

### The Form Widget

`Form` is a container that groups multiple `TextFormField`s and provides form-wide operations.

```dart
class _RegistrationFormState extends State<RegistrationForm> {
  // GlobalKey gives you access to FormState
  final _formKey = GlobalKey<FormState>();

  @override
  Widget build(BuildContext context) {
    return Form(
      key: _formKey,  // Connect the key
      child: Column(
        children: [
          TextFormField(
            decoration: const InputDecoration(labelText: 'Name'),
            validator: (value) {
              if (value == null || value.isEmpty) {
                return 'Name is required';
              }
              return null;
            },
          ),
          TextFormField(
            decoration: const InputDecoration(labelText: 'Email'),
            validator: (value) {
              if (value == null || value.isEmpty) {
                return 'Email is required';
              }
              return null;
            },
          ),
          ElevatedButton(
            onPressed: () {
              // Validate ALL fields
              if (_formKey.currentState!.validate()) {
                // All fields valid!
                _formKey.currentState!.save();  // Call onSaved on all fields
                // Process data...
              }
            },
            child: const Text('Submit'),
          ),
        ],
      ),
    );
  }
}
```

### FormState Methods

```dart
final formKey = GlobalKey<FormState>();

// Validate all fields (calls each validator)
bool isValid = formKey.currentState!.validate();
// Returns true if ALL validators return null

// Save all fields (calls each onSaved)
formKey.currentState!.save();

// Reset all fields to initial values
formKey.currentState!.reset();

// Check if any field has been edited
bool isDirty = formKey.currentState!.isDirty;
```

### Form with AutovalidateMode

```dart
Form(
  key: _formKey,
  autovalidateMode: AutovalidateMode.onUserInteraction,
  // Options:
  // disabled          — Never auto-validate (default)
  // always            — Validate on every keystroke
  // onUserInteraction — Validate after user interacts
  child: Column(
    children: [
      TextFormField(
        validator: (value) => value!.isEmpty ? 'Required' : null,
      ),
    ],
  ),
)
```

---

## 7. Validation Logic

### Basic Validation Patterns

```dart
// Required field
validator: (value) {
  if (value == null || value.trim().isEmpty) {
    return 'This field is required';
  }
  return null;
}

// Minimum length
validator: (value) {
  if (value == null || value.length < 6) {
    return 'Must be at least 6 characters';
  }
  return null;
}

// Maximum length
validator: (value) {
  if (value != null && value.length > 100) {
    return 'Must be less than 100 characters';
  }
  return null;
}

// Email validation
validator: (value) {
  if (value == null || value.isEmpty) {
    return 'Email is required';
  }
  final emailRegex = RegExp(r'^[^@]+@[^@]+\.[^@]+');
  if (!emailRegex.hasMatch(value)) {
    return 'Please enter a valid email';
  }
  return null;
}

// Phone validation
validator: (value) {
  if (value == null || value.isEmpty) {
    return 'Phone is required';
  }
  final phoneRegex = RegExp(r'^\+?[0-9]{10,15}$');
  if (!phoneRegex.hasMatch(value.replaceAll(RegExp(r'\s'), ''))) {
    return 'Please enter a valid phone number';
  }
  return null;
}

// Password strength
validator: (value) {
  if (value == null || value.isEmpty) {
    return 'Password is required';
  }
  if (value.length < 8) {
    return 'Must be at least 8 characters';
  }
  if (!value.contains(RegExp(r'[A-Z]'))) {
    return 'Must contain at least one uppercase letter';
  }
  if (!value.contains(RegExp(r'[0-9]'))) {
    return 'Must contain at least one number';
  }
  if (!value.contains(RegExp(r'[!@#$%^&*(),.?":{}|<>]'))) {
    return 'Must contain at least one special character';
  }
  return null;
}

// Confirm password
TextFormField(
  controller: _confirmPasswordController,
  validator: (value) {
    if (value != _passwordController.text) {
      return 'Passwords do not match';
    }
    return null;
  },
)
```

### Reusable Validator Functions

```dart
// validators.dart
class Validators {
  static String? required(String? value, [String fieldName = 'This field']) {
    if (value == null || value.trim().isEmpty) {
      return '$fieldName is required';
    }
    return null;
  }

  static String? email(String? value) {
    if (value == null || value.isEmpty) {
      return 'Email is required';
    }
    final regex = RegExp(r'^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$');
    if (!regex.hasMatch(value)) {
      return 'Please enter a valid email';
    }
    return null;
  }

  static String? minLength(String? value, int min, [String fieldName = '']) {
    if (value == null || value.length < min) {
      return '$fieldName must be at least $min characters';
    }
    return null;
  }

  static String? phone(String? value) {
    if (value == null || value.isEmpty) return 'Phone is required';
    final cleaned = value.replaceAll(RegExp(r'\D'), '');
    if (cleaned.length < 10 || cleaned.length > 15) {
      return 'Please enter a valid phone number';
    }
    return null;
  }

  static String? match(String? value, String? other, String fieldName) {
    if (value != other) {
      return '$fieldName does not match';
    }
    return null;
  }
}

// Usage
TextFormField(
  validator: Validators.email,
)

TextFormField(
  validator: (value) => Validators.minLength(value, 6, 'Password'),
)
```

---

## 8. Keyboard Types & Actions

### TextInputType

```dart
TextField(
  keyboardType: TextInputType.text,        // Default alphanumeric
)

TextField(
  keyboardType: TextInputType.emailAddress, // Shows @ and . on keyboard
)

TextField(
  keyboardType: TextInputType.number,       // Numeric keyboard
)

TextField(
  keyboardType: TextInputType.phone,        // Phone keypad
)

TextField(
  keyboardType: TextInputType.multiline,    // Multi-line with return key
  maxLines: 5,
)

TextField(
  keyboardType: TextInputType.url,          // Shows .com, /, etc.
)

TextField(
  keyboardType: TextInputType.visiblePassword, // Shows all characters
)

TextField(
  keyboardType: const TextInputType.numberWithOptions(
    decimal: true,
    signed: true,
  ),  // Numbers with decimal and minus sign
)
```

### TextInputAction

```dart
TextField(
  textInputAction: TextInputAction.next,     // Shows "Next" button
  onSubmitted: (_) => FocusScope.of(context).nextFocus(),
)

TextField(
  textInputAction: TextInputAction.done,     // Shows "Done" button
  onSubmitted: (_) => FocusScope.of(context).unfocus(),
)

TextField(
  textInputAction: TextInputAction.search,   // Shows search icon
  onSubmitted: (value) => performSearch(value),
)

TextField(
  textInputAction: TextInputAction.send,     // Shows "Send" button
)

// All options:
// done, next, previous, continueAction, send, search, go, route
```

### TextCapitalization

```dart
TextField(
  textCapitalization: TextCapitalization.words,     // Each Word Capitalized
)

TextField(
  textCapitalization: TextCapitalization.sentences, // First word of sentence
)

TextField(
  textCapitalization: TextCapitalization.characters, // ALL CAPS
)

TextField(
  textCapitalization: TextCapitalization.none,       // No auto-capitalization
)
```

---

## 9. Advanced Input Features

### Password Visibility Toggle

```dart
class _PasswordFieldState extends State<PasswordField> {
  bool _obscureText = true;

  @override
  Widget build(BuildContext context) {
    return TextFormField(
      obscureText: _obscureText,  // Hide/show text
      decoration: InputDecoration(
        labelText: 'Password',
        prefixIcon: const Icon(Icons.lock_outline),
        suffixIcon: IconButton(
          icon: Icon(
            _obscureText ? Icons.visibility_off : Icons.visibility,
          ),
          onPressed: () {
            setState(() {
              _obscureText = !_obscureText;
            });
          },
        ),
      ),
    );
  }
}
```

### Input Formatters

```dart
import 'package:flutter/services.dart';

TextField(
  inputFormatters: [
    // Only allow digits
    FilteringTextInputFormatter.digitsOnly,

    // Allow only letters
    FilteringTextInputFormatter.allow(RegExp(r'[a-zA-Z]')),

    // Deny spaces
    FilteringTextInputFormatter.deny(RegExp(r'\s')),

    // Length limit
    LengthLimitingTextInputFormatter(10),

    // Uppercase all input
    TextInputFormatter.withFunction((oldValue, newValue) {
      return newValue.copyWith(text: newValue.text.toUpperCase());
    }),
  ],
)
```

### Credit Card Formatter

```dart
class CardNumberFormatter extends TextInputFormatter {
  @override
  TextEditingValue formatEditUpdate(
    TextEditingValue oldValue,
    TextEditingValue newValue,
  ) {
    var text = newValue.text.replaceAll(RegExp(r'\D'), '');
    var buffer = StringBuffer();

    for (int i = 0; i < text.length; i++) {
      if (i > 0 && i % 4 == 0) buffer.write(' ');
      buffer.write(text[i]);
    }

    return TextEditingValue(
      text: buffer.toString(),
      selection: TextSelection.collapsed(offset: buffer.length),
    );
  }
}

// Usage
TextField(
  keyboardType: TextInputType.number,
  inputFormatters: [
    CardNumberFormatter(),
    LengthLimitingTextInputFormatter(19),  // 16 digits + 3 spaces
  ],
)
// User types: 1234567890123456
// Displays:   1234 5678 9012 3456
```

### Phone Number Formatter

```dart
class PhoneFormatter extends TextInputFormatter {
  @override
  TextEditingValue formatEditUpdate(
    TextEditingValue oldValue,
    TextEditingValue newValue,
  ) {
    var digits = newValue.text.replaceAll(RegExp(r'\D'), '');
    if (digits.length > 10) digits = digits.substring(0, 10);

    var buffer = StringBuffer();
    if (digits.length >= 5) {
      buffer.write('${digits.substring(0, 5)}-${digits.substring(5)}');
    } else {
      buffer.write(digits);
    }

    return TextEditingValue(
      text: buffer.toString(),
      selection: TextSelection.collapsed(offset: buffer.length),
    );
  }
}
```

---

## 10. Hands-On Project: Registration Form

```dart
import 'package:flutter/material.dart';
import 'package:flutter/services.dart';

void main() {
  runApp(const RegistrationApp());
}

class RegistrationApp extends StatelessWidget {
  const RegistrationApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.indigo),
        useMaterial3: true,
        inputDecorationTheme: InputDecorationTheme(
          border: OutlineInputBorder(borderRadius: BorderRadius.circular(12)),
          filled: true,
          fillColor: Colors.grey.shade50,
          contentPadding: const EdgeInsets.symmetric(horizontal: 16, vertical: 14),
        ),
      ),
      home: const RegistrationScreen(),
    );
  }
}

class RegistrationScreen extends StatefulWidget {
  const RegistrationScreen({super.key});

  @override
  State<RegistrationScreen> createState() => _RegistrationScreenState();
}

class _RegistrationScreenState extends State<RegistrationScreen> {
  final _formKey = GlobalKey<FormState>();

  // Controllers
  final _nameController = TextEditingController();
  final _emailController = TextEditingController();
  final _phoneController = TextEditingController();
  final _passwordController = TextEditingController();
  final _confirmPasswordController = TextEditingController();

  // Focus nodes
  final _nameFocus = FocusNode();
  final _emailFocus = FocusNode();
  final _phoneFocus = FocusNode();
  final _passwordFocus = FocusNode();
  final _confirmPasswordFocus = FocusNode();

  // State
  bool _obscurePassword = true;
  bool _obscureConfirm = true;
  bool _isLoading = false;
  bool _agreeToTerms = false;

  @override
  void dispose() {
    _nameController.dispose();
    _emailController.dispose();
    _phoneController.dispose();
    _passwordController.dispose();
    _confirmPasswordController.dispose();
    _nameFocus.dispose();
    _emailFocus.dispose();
    _phoneFocus.dispose();
    _passwordFocus.dispose();
    _confirmPasswordFocus.dispose();
    super.dispose();
  }

  void _submitForm() {
    // Dismiss keyboard
    FocusScope.of(context).unfocus();

    // Validate form
    if (!_formKey.currentState!.validate()) {
      return;
    }

    if (!_agreeToTerms) {
      ScaffoldMessenger.of(context).showSnackBar(
        const SnackBar(content: Text('Please agree to the terms')),
      );
      return;
    }

    setState(() => _isLoading = true);

    // Simulate API call
    Future.delayed(const Duration(seconds: 2), () {
      setState(() => _isLoading = false);

      showDialog(
        context: context,
        builder: (context) => AlertDialog(
          icon: const Icon(Icons.check_circle, color: Colors.green, size: 48),
          title: const Text('Success!'),
          content: Text('Welcome, ${_nameController.text}! Your account has been created.'),
          actions: [
            TextButton(
              onPressed: () => Navigator.pop(context),
              child: const Text('OK'),
            ),
          ],
        ),
      );
    });
  }

  @override
  Widget build(BuildContext context) {
    return GestureDetector(
      onTap: () => FocusScope.of(context).unfocus(),
      child: Scaffold(
        appBar: AppBar(
          title: const Text('Create Account'),
          centerTitle: true,
        ),
        body: SafeArea(
          child: SingleChildScrollView(
            padding: const EdgeInsets.all(24),
            child: Form(
              key: _formKey,
              autovalidateMode: AutovalidateMode.onUserInteraction,
              child: Column(
                crossAxisAlignment: CrossAxisAlignment.stretch,
                children: [
                  // Header
                  const Icon(Icons.person_add, size: 64, color: Colors.indigo),
                  const SizedBox(height: 16),
                  const Text(
                    'Join Us Today',
                    style: TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
                    textAlign: TextAlign.center,
                  ),
                  const SizedBox(height: 4),
                  Text(
                    'Create your account to get started',
                    style: TextStyle(color: Colors.grey.shade600),
                    textAlign: TextAlign.center,
                  ),
                  const SizedBox(height: 32),

                  // Name field
                  TextFormField(
                    controller: _nameController,
                    focusNode: _nameFocus,
                    textInputAction: TextInputAction.next,
                    textCapitalization: TextCapitalization.words,
                    decoration: const InputDecoration(
                      labelText: 'Full Name',
                      prefixIcon: Icon(Icons.person_outline),
                      hintText: 'John Doe',
                    ),
                    validator: (value) {
                      if (value == null || value.trim().isEmpty) {
                        return 'Please enter your name';
                      }
                      if (value.trim().length < 2) {
                        return 'Name must be at least 2 characters';
                      }
                      return null;
                    },
                    onFieldSubmitted: (_) {
                      FocusScope.of(context).requestFocus(_emailFocus);
                    },
                  ),
                  const SizedBox(height: 16),

                  // Email field
                  TextFormField(
                    controller: _emailController,
                    focusNode: _emailFocus,
                    keyboardType: TextInputType.emailAddress,
                    textInputAction: TextInputAction.next,
                    decoration: const InputDecoration(
                      labelText: 'Email Address',
                      prefixIcon: Icon(Icons.email_outlined),
                      hintText: 'john@example.com',
                    ),
                    validator: (value) {
                      if (value == null || value.isEmpty) {
                        return 'Please enter your email';
                      }
                      final regex = RegExp(r'^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$');
                      if (!regex.hasMatch(value)) {
                        return 'Please enter a valid email';
                      }
                      return null;
                    },
                    onFieldSubmitted: (_) {
                      FocusScope.of(context).requestFocus(_phoneFocus);
                    },
                  ),
                  const SizedBox(height: 16),

                  // Phone field
                  TextFormField(
                    controller: _phoneController,
                    focusNode: _phoneFocus,
                    keyboardType: TextInputType.phone,
                    textInputAction: TextInputAction.next,
                    inputFormatters: [
                      FilteringTextInputFormatter.digitsOnly,
                      LengthLimitingTextInputFormatter(10),
                    ],
                    decoration: const InputDecoration(
                      labelText: 'Phone Number',
                      prefixIcon: Icon(Icons.phone_outlined),
                      prefixText: '+91 ',
                      hintText: '9876543210',
                    ),
                    validator: (value) {
                      if (value == null || value.isEmpty) {
                        return 'Please enter your phone number';
                      }
                      if (value.length != 10) {
                        return 'Phone number must be 10 digits';
                      }
                      return null;
                    },
                    onFieldSubmitted: (_) {
                      FocusScope.of(context).requestFocus(_passwordFocus);
                    },
                  ),
                  const SizedBox(height: 16),

                  // Password field
                  TextFormField(
                    controller: _passwordController,
                    focusNode: _passwordFocus,
                    obscureText: _obscurePassword,
                    textInputAction: TextInputAction.next,
                    decoration: InputDecoration(
                      labelText: 'Password',
                      prefixIcon: const Icon(Icons.lock_outline),
                      suffixIcon: IconButton(
                        icon: Icon(
                          _obscurePassword ? Icons.visibility_off : Icons.visibility,
                        ),
                        onPressed: () {
                          setState(() => _obscurePassword = !_obscurePassword);
                        },
                      ),
                      helperText: 'Min 8 chars, 1 uppercase, 1 number',
                    ),
                    validator: (value) {
                      if (value == null || value.isEmpty) {
                        return 'Please enter a password';
                      }
                      if (value.length < 8) {
                        return 'Password must be at least 8 characters';
                      }
                      if (!value.contains(RegExp(r'[A-Z]'))) {
                        return 'Must contain at least one uppercase letter';
                      }
                      if (!value.contains(RegExp(r'[0-9]'))) {
                        return 'Must contain at least one number';
                      }
                      return null;
                    },
                    onFieldSubmitted: (_) {
                      FocusScope.of(context).requestFocus(_confirmPasswordFocus);
                    },
                  ),
                  const SizedBox(height: 16),

                  // Confirm password field
                  TextFormField(
                    controller: _confirmPasswordController,
                    focusNode: _confirmPasswordFocus,
                    obscureText: _obscureConfirm,
                    textInputAction: TextInputAction.done,
                    decoration: InputDecoration(
                      labelText: 'Confirm Password',
                      prefixIcon: const Icon(Icons.lock_outline),
                      suffixIcon: IconButton(
                        icon: Icon(
                          _obscureConfirm ? Icons.visibility_off : Icons.visibility,
                        ),
                        onPressed: () {
                          setState(() => _obscureConfirm = !_obscureConfirm);
                        },
                      ),
                    ),
                    validator: (value) {
                      if (value == null || value.isEmpty) {
                        return 'Please confirm your password';
                      }
                      if (value != _passwordController.text) {
                        return 'Passwords do not match';
                      }
                      return null;
                    },
                    onFieldSubmitted: (_) => _submitForm(),
                  ),
                  const SizedBox(height: 16),

                  // Terms checkbox
                  Row(
                    children: [
                      Checkbox(
                        value: _agreeToTerms,
                        onChanged: (value) {
                          setState(() => _agreeToTerms = value ?? false);
                        },
                      ),
                      Expanded(
                        child: GestureDetector(
                          onTap: () {
                            setState(() => _agreeToTerms = !_agreeToTerms);
                          },
                          child: RichText(
                            text: TextSpan(
                              style: TextStyle(color: Colors.grey.shade700),
                              children: [
                                const TextSpan(text: 'I agree to the '),
                                TextSpan(
                                  text: 'Terms of Service',
                                  style: const TextStyle(
                                    color: Colors.indigo,
                                    fontWeight: FontWeight.bold,
                                  ),
                                  recognizer: TapGestureRecognizer()
                                    ..onTap = () {
                                      print('Open terms');
                                    },
                                ),
                                const TextSpan(text: ' and '),
                                TextSpan(
                                  text: 'Privacy Policy',
                                  style: const TextStyle(
                                    color: Colors.indigo,
                                    fontWeight: FontWeight.bold,
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ),
                      ),
                    ],
                  ),
                  const SizedBox(height: 24),

                  // Submit button
                  SizedBox(
                    height: 50,
                    child: ElevatedButton(
                      onPressed: _isLoading ? null : _submitForm,
                      style: ElevatedButton.styleFrom(
                        shape: RoundedRectangleBorder(
                          borderRadius: BorderRadius.circular(12),
                        ),
                      ),
                      child: _isLoading
                        ? const SizedBox(
                            width: 24,
                            height: 24,
                            child: CircularProgressIndicator(strokeWidth: 2),
                          )
                        : const Text(
                            'Create Account',
                            style: TextStyle(fontSize: 16),
                          ),
                    ),
                  ),
                  const SizedBox(height: 16),

                  // Login link
                  Row(
                    mainAxisAlignment: MainAxisAlignment.center,
                    children: [
                      Text('Already have an account?', style: TextStyle(color: Colors.grey.shade600)),
                      TextButton(
                        onPressed: () {},
                        child: const Text('Sign In'),
                      ),
                    ],
                  ),
                ],
              ),
            ),
          ),
        ),
      ),
    );
  }
}
```

---

## 11. Common Mistakes & How to Avoid Them

### Mistake 1: Not Disposing Controllers
```dart
// ❌ WRONG — Memory leak!
class MyWidget extends StatefulWidget {
  final controller = TextEditingController();  // Never disposed!
}

// ✅ CORRECT
class _MyWidgetState extends State<MyWidget> {
  final _controller = TextEditingController();

  @override
  void dispose() {
    _controller.dispose();
    super.dispose();
  }
}
```

### Mistake 2: Using Both initialValue and Controller
```dart
// ❌ WRONG — Conflict!
TextFormField(
  initialValue: 'Kimi',
  controller: _controller,
)

// ✅ CORRECT
TextEditingController(text: 'Kimi');
// OR
TextFormField(initialValue: 'Kimi');  // Without controller
```

### Mistake 3: Forgetting Form Key
```dart
// ❌ WRONG — Can't validate or save
Form(
  child: Column(...),
)

// ✅ CORRECT
final _formKey = GlobalKey<FormState>();

Form(
  key: _formKey,
  child: Column(...),
)
```

### Mistake 4: Not Dismissing Keyboard Before Validation
```dart
// ❌ WRONG — Keyboard covers error messages
void _submit() {
  _formKey.currentState!.validate();
}

// ✅ CORRECT
void _submit() {
  FocusScope.of(context).unfocus();  // Hide keyboard first
  _formKey.currentState!.validate();
}
```

### Mistake 5: Missing FocusNode Disposal
```dart
// ❌ WRONG
final _focusNode = FocusNode();
// Never disposed!

// ✅ CORRECT
@override
void dispose() {
  _focusNode.dispose();
  super.dispose();
}
```

### Mistake 6: Validating Without Trimming
```dart
// ❌ WRONG — "   " passes validation
validator: (value) {
  if (value == null || value.isEmpty) {
    return 'Required';
  }
}

// ✅ CORRECT — Trim whitespace
validator: (value) {
  if (value == null || value.trim().isEmpty) {
    return 'Required';
  }
}
```

### Mistake 7: Not Wrapping Form in Scrollable
```dart
// ❌ WRONG — Keyboard covers bottom fields
Scaffold(
  body: Form(child: Column(children: [...])),
)

// ✅ CORRECT
Scaffold(
  body: SingleChildScrollView(
    child: Form(child: Column(children: [...])),
  ),
)
```

### Mistake 8: Using setState in onChanged for Every Keystroke
```dart
// ❌ WRONG — Rebuilds entire form on every keystroke
TextField(
  onChanged: (value) {
    setState(() { _text = value; });  // Expensive!
  },
)

// ✅ CORRECT — Use controller or debounce
TextField(
  controller: _controller,  // No setState needed!
)

// ✅ For search, debounce input
TextField(
  onChanged: (value) {
    _debounce?.cancel();
    _debounce = Timer(Duration(milliseconds: 500), () {
      setState(() { _searchText = value; });
    });
  },
)
```

---

## 12. Day 8 Checklist

Use this checklist to verify mastery:

- [ ] Understands difference between TextField and TextFormField
- [ ] Can create and use TextEditingController
- [ ] Knows all controller methods: text, selection, clear, dispose
- [ ] Can style inputs with InputDecoration (label, hint, prefix, suffix, border)
- [ ] Can create different border styles (outline, underline, none)
- [ ] Can use FocusNode to manage focus between fields
- [ ] Can dismiss keyboard with FocusScope.of(context).unfocus()
- [ ] Can create and use Form widget with GlobalKey<FormState>
- [ ] Can validate all fields with formKey.currentState!.validate()
- [ ] Can save all fields with formKey.currentState!.save()
- [ ] Can reset form with formKey.currentState!.reset()
- [ ] Can write validators for: required, email, phone, min length, password match
- [ ] Can create reusable validator functions
- [ ] Can use autovalidateMode (disabled, always, onUserInteraction)
- [ ] Knows keyboard types: text, email, number, phone, multiline, url
- [ ] Knows textInputAction: next, done, search, send
- [ ] Can implement password visibility toggle
- [ ] Can use input formatters (digits only, length limit, custom)
- [ ] Can format input (credit card, phone number)
- [ ] Built the Registration Form with all fields
- [ ] Form includes: name, email, phone, password, confirm password
- [ ] Form has proper validation, focus management, and loading state
- [ ] Can dismiss keyboard by tapping outside
- [ ] Pushed the project to GitHub

---

## 🧠 Key Takeaways (Memorize These!)

1. **Use TextFormField for forms, TextField for standalone inputs.** TextFormField integrates with Form widget.

2. **Always dispose controllers and focus nodes.** They cause memory leaks if not disposed.

3. **Never use both initialValue and controller.** Use controller with initial text instead.

4. **GlobalKey<FormState> gives you form-wide control.** validate(), save(), reset() all fields at once.

5. **Trim user input before validating.** "   " should not pass a "required" check.

6. **Wrap forms in SingleChildScrollView.** Otherwise the keyboard covers bottom fields.

7. **Use FocusScope to manage focus flow.** nextFocus() for Next button, unfocus() for Done.

8. **InputFormatters are powerful.** Use them for digits-only, length limits, and custom formatting.

9. **AutovalidateMode.onUserInteraction** is the sweet spot — validates after user touches the field.

10. **Dismiss keyboard before showing dialogs or validating.** FocusScope.of(context).unfocus() first.

---

## 📚 Extra Practice (Do These Tonight!)

1. **Login Screen:** Build a login form with email, password, "Remember me" checkbox, and "Forgot password" link. Include proper validation.

2. **Profile Edit Form:** Create a profile editing form with avatar upload placeholder, name, bio (multiline), birthday (date picker), and gender (dropdown).

3. **Payment Form:** Build a credit card form with card number (formatted), expiry date, CVV, and cardholder name. Use input formatters.

4. **Search Bar with Filters:** Create a search input with dropdown filters (category, price range, sort order) and a search button.

5. **Multi-Step Form:** Build a 3-step registration wizard (Personal Info → Account Details → Review) using PageView with form validation per step.

---

> 🎉 **Congratulations!** You've completed Day 8. You now know how to build professional forms with validation, focus management, keyboard handling, and input formatting. These skills are essential for every real-world Flutter app.

**Next Up → Day 9: Navigation & Routing**

# Day 9: Navigation & Routing
## Complete Deep Dive

**Goal:** Implement multi-screen navigation professionally with Navigator 1.0, Named Routes, Arguments, Results, and Navigation 2.0 Router API. This guide covers every navigation pattern, data passing strategy, transition animations, and a complete e-commerce product browsing app.

---

# Table of Contents
1. Why Navigation Matters in Flutter
2. Understanding the Navigator & Route
3. Navigator 1.0: push & pop
4. Passing Data to Screens (Forward)
5. Returning Data from Screens (Backward)
6. Named Routes & onGenerateRoute
7. Arguments & RouteSettings
8. Navigation 2.0 / Router API (Declarative)
9. Deep Linking Basics
10. Advanced Navigation Patterns
11. Hands-On Project: E-commerce Product Browsing App
12. Common Mistakes & How to Avoid Them
13. Day 9 Checklist

---

# 1. Why Navigation Matters in Flutter

## Navigation Is Everywhere
Every multi-screen app needs navigation:
- Login → Home dashboard
- Product list → Product detail → Cart → Checkout
- Profile → Settings → Edit Profile
- Splash → Onboarding → Main App
- Bottom tabs switching

## The Navigation Challenge
| Challenge | Solution |
|---|---|
| Move between screens | Navigator push/pop |
| Pass data forward | Constructor arguments / RouteSettings |
| Return data backward | await Navigator.push / pop with result |
| Deep links from outside | Router API + deep linking |
| Browser-style URLs (Web) | Navigation 2.0 declarative routing |
| Prevent duplicate pages | pushReplacement, pushAndRemoveUntil |
| Bottom navigation state | IndexedStack or multiple Navigators |

---

# 2. Understanding the Navigator & Route

## What is a Route?
A `Route` represents a screen/page in the app. Flutter uses `MaterialPageRoute` or `CupertinoPageRoute` to wrap widgets with platform-appropriate transitions.

## What is the Navigator?
The `Navigator` is a widget that manages a stack of Route objects. It provides imperative methods to push/pop routes.

```dart
// The Navigator is already inside MaterialApp/CupertinoApp
// You access it via: Navigator.of(context)
```

## Navigation Stack Visual
```
[Screen C]  ← Top (visible)
[Screen B]
[Screen A]  ← Bottom
```
- `push()` → adds a new screen on top
- `pop()` → removes the top screen

---

# 3. Navigator 1.0: push & pop

## Basic Push
```dart
// Navigate to a new screen
Navigator.push(
  context,
  MaterialPageRoute(builder: (context) => const DetailScreen()),
);
```

## Basic Pop (Go Back)
```dart
// Return to previous screen
Navigator.pop(context);
```

## Push with Cupertino Style (iOS slide transition)
```dart
Navigator.push(
  context,
  CupertinoPageRoute(builder: (context) => const DetailScreen()),
);
```

## Push Replacement (Replace current screen)
Use when you don't want the user to come back (e.g., Login → Home).
```dart
Navigator.pushReplacement(
  context,
  MaterialPageRoute(builder: (context) => const HomeScreen()),
);
```

## Push And Remove Until (Clear stack)
Use for splash → home or logout → login.
```dart
Navigator.pushAndRemoveUntil(
  context,
  MaterialPageRoute(builder: (context) => const HomeScreen()),
  (route) => false, // Remove all previous routes
);
```

## Pop Until (Go back multiple screens)
```dart
Navigator.popUntil(context, (route) => route.isFirst);
// Or pop to a named route
Navigator.popUntil(context, ModalRoute.withName('/home'));
```

## Can Pop Check
```dart
if (Navigator.canPop(context)) {
  Navigator.pop(context);
}
```

---

# 4. Passing Data to Screens (Forward)

## Method 1: Constructor Arguments (Recommended for simple cases)
```dart
// Sending screen
Navigator.push(
  context,
  MaterialPageRoute(
    builder: (context) => const ProductDetailScreen(productId: 42),
  ),
);

// Receiving screen
class ProductDetailScreen extends StatelessWidget {
  final int productId;
  const ProductDetailScreen({super.key, required this.productId});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('Product $productId')),
    );
  }
}
```

## Method 2: Multiple Arguments
```dart
Navigator.push(
  context,
  MaterialPageRoute(
    builder: (context) => UserProfileScreen(
      userId: 'u123',
      userName: 'Kimi',
      isPremium: true,
    ),
  ),
);
```

## Method 3: Passing Objects
```dart
final product = Product(id: 1, name: 'Flutter Book', price: 29.99);

Navigator.push(
  context,
  MaterialPageRoute(
    builder: (context) => ProductScreen(product: product),
  ),
);
```

---

# 5. Returning Data from Screens (Backward)

## Using await + pop with result
```dart
// Screen A: Open selection screen and wait for result
void _openColorPicker() async {
  final selectedColor = await Navigator.push(
    context,
    MaterialPageRoute(builder: (context) => const ColorPickerScreen()),
  );

  if (selectedColor != null) {
    setState(() {
      _backgroundColor = selectedColor;
    });
  }
}
```

```dart
// Screen B: Return data when popping
class ColorPickerScreen extends StatelessWidget {
  const ColorPickerScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('Pick a Color')),
      body: ListView(
        children: [
          ListTile(
            leading: const CircleAvatar(backgroundColor: Colors.red),
            title: const Text('Red'),
            onTap: () => Navigator.pop(context, Colors.red),
          ),
          ListTile(
            leading: const CircleAvatar(backgroundColor: Colors.green),
            title: const Text('Green'),
            onTap: () => Navigator.pop(context, Colors.green),
          ),
          ListTile(
            leading: const CircleAvatar(backgroundColor: Colors.blue),
            title: const Text('Blue'),
            onTap: () => Navigator.pop(context, Colors.blue),
          ),
        ],
      ),
    );
  }
}
```

## Returning Complex Objects
```dart
// Return a result object
Navigator.pop(context, {
  'name': 'Kimi',
  'age': 25,
  'isDeveloper': true,
});

// Or a dedicated class
Navigator.pop(context, EditResult(saved: true, data: userData));
```

---

# 6. Named Routes & onGenerateRoute

## Why Named Routes?
- Avoid hardcoding routes everywhere
- Centralized route management
- Easier deep linking setup
- Cleaner code

## Setting Up Named Routes
```dart
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Navigation Demo',
      initialRoute: '/',
      routes: {
        '/': (context) => const HomeScreen(),
        '/profile': (context) => const ProfileScreen(),
        '/settings': (context) => const SettingsScreen(),
      },
    );
  }
}
```

## Navigating with Named Routes
```dart
// Push
Navigator.pushNamed(context, '/profile');

// Push and remove current
Navigator.pushReplacementNamed(context, '/home');

// Push and clear all
Navigator.pushNamedAndRemoveUntil(context, '/home', (route) => false);

// Pop
Navigator.pop(context);
```

## Limitation of Simple Named Routes
The `routes` map doesn't support passing arguments directly. Use `onGenerateRoute` for dynamic arguments.

---

# 7. Arguments & RouteSettings

## onGenerateRoute (The Professional Way)
```dart
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Navigation Demo',
      initialRoute: '/',
      onGenerateRoute: (settings) {
        // Extract arguments
        final args = settings.arguments;

        switch (settings.name) {
          case '/':
            return MaterialPageRoute(builder: (_) => const HomeScreen());

          case '/product':
            if (args is Product) {
              return MaterialPageRoute(
                builder: (_) => ProductDetailScreen(product: args),
              );
            }
            return _errorRoute();

          case '/profile':
            final userId = args as String?;
            return MaterialPageRoute(
              builder: (_) => ProfileScreen(userId: userId ?? ''),
            );

          default:
            return _errorRoute();
        }
      },
    );
  }

  static Route<dynamic> _errorRoute() {
    return MaterialPageRoute(
      builder: (_) => const Scaffold(
        body: Center(child: Text('Page not found!')),
      ),
    );
  }
}
```

## Passing Arguments with Named Routes
```dart
// Push with arguments
Navigator.pushNamed(
  context,
  '/product',
  arguments: Product(id: 1, name: 'Book', price: 29.99),
);

// Or with RouteSettings explicitly
Navigator.push(
  context,
  MaterialPageRoute(
    builder: (_) => const DetailScreen(),
    settings: const RouteSettings(
      name: '/detail',
      arguments: {'id': 42, 'title': 'Flutter'},
    ),
  ),
);
```

## Extracting Arguments in the Target Screen
```dart
class ProductDetailScreen extends StatelessWidget {
  const ProductDetailScreen({super.key});

  @override
  Widget build(BuildContext context) {
    // Extract arguments from ModalRoute
    final product = ModalRoute.of(context)!.settings.arguments as Product;

    return Scaffold(
      appBar: AppBar(title: Text(product.name)),
      body: Center(child: Text('$${product.price}')),
    );
  }
}
```

---

# 8. Navigation 2.0 / Router API (Declarative)

## Why Navigation 2.0?
- URL-aware navigation (essential for Flutter Web)
- Declarative: UI reflects the current route state
- Handle browser back/forward buttons
- Deep linking out of the box
- Sync app state with URL

## Core Components
| Component | Purpose |
|---|---|
| `Router` | Widget that handles routing |
| `RouteInformationParser` | Parses URL to route state |
| `RouterDelegate` | Builds Navigator based on app state |
| `BackButtonDispatcher` | Handles platform back button |
| `RouteInformationProvider` | Reports route changes to system |

## Simple RouterDelegate Example
```dart
// App state that represents current route
class AppRouteState extends ChangeNotifier {
  String _currentPath = '/';
  String? _selectedProductId;

  String get currentPath => _currentPath;
  String? get selectedProductId => _selectedProductId;

  void goToHome() {
    _currentPath = '/';
    _selectedProductId = null;
    notifyListeners();
  }

  void goToProduct(String id) {
    _currentPath = '/product';
    _selectedProductId = id;
    notifyListeners();
  }

  void goToProfile() {
    _currentPath = '/profile';
    _selectedProductId = null;
    notifyListeners();
  }
}

// Router Delegate
class AppRouterDelegate extends RouterDelegate<String>
    with ChangeNotifier, PopNavigatorRouterDelegateMixin<String> {

  final AppRouteState appState;

  AppRouterDelegate(this.appState) {
    appState.addListener(notifyListeners);
  }

  @override
  GlobalKey<NavigatorState> get navigatorKey => GlobalKey<NavigatorState>();

  @override
  String? get currentConfiguration => appState.currentPath;

  @override
  Widget build(BuildContext context) {
    return Navigator(
      key: navigatorKey,
      pages: [
        const MaterialPage(child: HomeScreen()),
        if (appState.currentPath == '/product' && appState.selectedProductId != null)
          MaterialPage(
            child: ProductDetailScreen(productId: appState.selectedProductId!),
          ),
        if (appState.currentPath == '/profile')
          const MaterialPage(child: ProfileScreen()),
      ],
      onPopPage: (route, result) {
        if (!route.didPop(result)) return false;
        appState.goToHome();
        return true;
      },
    );
  }

  @override
  Future<void> setNewRoutePath(String configuration) async {
    // Handle deep links here
    if (configuration.startsWith('/product/')) {
      final id = configuration.replaceFirst('/product/', '');
      appState.goToProduct(id);
    } else if (configuration == '/profile') {
      appState.goToProfile();
    } else {
      appState.goToHome();
    }
  }
}

// Route Information Parser
class AppRouteInformationParser extends RouteInformationParser<String> {
  @override
  Future<String> parseRouteInformation(RouteInformation routeInformation) async {
    final uri = Uri.parse(routeInformation.uri.toString());
    if (uri.pathSegments.isEmpty) return '/';
    if (uri.pathSegments.length == 2 && uri.pathSegments[0] == 'product') {
      return '/product/${uri.pathSegments[1]}';
    }
    return uri.path;
  }

  @override
  RouteInformation restoreRouteInformation(String configuration) {
    return RouteInformation(uri: Uri.parse(configuration));
  }
}

// Usage in MaterialApp
class MyApp extends StatelessWidget {
  final AppRouteState appState = AppRouteState();

  MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp.router(
      routerDelegate: AppRouterDelegate(appState),
      routeInformationParser: AppRouteInformationParser(),
    );
  }
}
```

## When to Use What?
| Scenario | Use Navigator 1.0 | Use Navigation 2.0 |
|---|---|---|
| Mobile-only app | ✅ Yes | Optional |
| Flutter Web | ❌ No | ✅ Yes |
| Deep linking required | Hard | ✅ Easy |
| URL sync needed | ❌ No | ✅ Yes |
| Simple app (2-5 screens) | ✅ Yes | Overkill |
| Complex state-driven UI | ❌ Hard | ✅ Yes |

---

# 9. Deep Linking Basics

## What is Deep Linking?
Opening specific screens in your app from external sources:
- Push notifications → specific screen
- Web URL → app screen
- Another app → your app screen

## Android Setup (AndroidManifest.xml)
```xml
<activity android:name=".MainActivity"
    android:launchMode="singleTop">
    <intent-filter>
        <action android:name="android.intent.action.VIEW" />
        <category android:name="android.intent.category.DEFAULT" />
        <category android:name="android.intent.category.BROWSABLE" />
        <data android:scheme="https"
              android:host="myapp.com"
              android:pathPrefix="/product" />
    </intent-filter>
</activity>
```

## iOS Setup (Info.plist)
```xml
<key>CFBundleURLTypes</key>
<array>
  <dict>
    <key>CFBundleURLSchemes</key>
    <array>
      <string>myapp</string>
    </array>
  </dict>
</array>
```

## Handling Deep Links with go_router (Recommended)
```dart
// Add dependency: go_router: ^14.0.0
import 'package:go_router/go_router.dart';

final GoRouter _router = GoRouter(
  routes: [
    GoRoute(
      path: '/',
      builder: (context, state) => const HomeScreen(),
    ),
    GoRoute(
      path: '/product/:id',
      builder: (context, state) {
        final productId = state.pathParameters['id']!;
        return ProductDetailScreen(productId: productId);
      },
    ),
    GoRoute(
      path: '/profile',
      builder: (context, state) => const ProfileScreen(),
    ),
  ],
);

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp.router(
      routerConfig: _router,
    );
  }
}

// Navigation with go_router
context.go('/');
context.go('/product/123');
context.push('/profile');
context.pop();
```

---

# 10. Advanced Navigation Patterns

## Custom Page Transitions
```dart
class SlideRightRoute extends PageRouteBuilder {
  final Widget page;

  SlideRightRoute({required this.page})
      : super(
          pageBuilder: (context, animation, secondaryAnimation) => page,
          transitionsBuilder: (context, animation, secondaryAnimation, child) {
            const begin = Offset(1.0, 0.0);
            const end = Offset.zero;
            const curve = Curves.easeInOut;
            var tween = Tween(begin: begin, end: end).chain(CurveTween(curve: curve));
            var offsetAnimation = animation.drive(tween);
            return SlideTransition(position: offsetAnimation, child: child);
          },
        );
}

// Usage
Navigator.push(context, SlideRightRoute(page: const DetailScreen()));
```

## Fade Transition
```dart
class FadeRoute extends PageRouteBuilder {
  final Widget page;
  FadeRoute({required this.page})
      : super(
          pageBuilder: (context, animation, secondaryAnimation) => page,
          transitionsBuilder: (context, animation, secondaryAnimation, child) {
            return FadeTransition(opacity: animation, child: child);
          },
        );
}
```

## Shared Axis Transition (Material)
```dart
import 'package:animations/animations.dart';

OpenContainer(
  closedBuilder: (context, action) => const ProductCard(),
  openBuilder: (context, action) => const ProductDetailScreen(),
);
```

## Bottom Sheet Navigation
```dart
// Modal Bottom Sheet
showModalBottomSheet(
  context: context,
  isScrollControlled: true,
  shape: const RoundedRectangleBorder(
    borderRadius: BorderRadius.vertical(top: Radius.circular(20)),
  ),
  builder: (context) => const FilterBottomSheet(),
);

// Persistent Bottom Sheet
showBottomSheet(
  context: context,
  builder: (context) => const PersistentBottomContent(),
);
```

## Dialog Navigation
```dart
// Alert Dialog
showDialog(
  context: context,
  builder: (context) => AlertDialog(
    title: const Text('Confirm'),
    content: const Text('Are you sure?'),
    actions: [
      TextButton(onPressed: () => Navigator.pop(context), child: const Text('Cancel')),
      TextButton(onPressed: () => Navigator.pop(context, true), child: const Text('Confirm')),
    ],
  ),
);

// Full Screen Dialog
Navigator.push(
  context,
  MaterialPageRoute(
    builder: (_) => const EditScreen(),
    fullscreenDialog: true,
  ),
);
```

## Nested Navigation (Bottom Navigation with separate stacks)
```dart
class MainScreen extends StatefulWidget {
  const MainScreen({super.key});

  @override
  State<MainScreen> createState() => _MainScreenState();
}

class _MainScreenState extends State<MainScreen> {
  int _currentIndex = 0;

  final List<GlobalKey<NavigatorState>> _navigatorKeys = [
    GlobalKey<NavigatorState>(),
    GlobalKey<NavigatorState>(),
    GlobalKey<NavigatorState>(),
  ];

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: IndexedStack(
        index: _currentIndex,
        children: [
          NavigatorPage(navigatorKey: _navigatorKeys[0], child: const HomeTab()),
          NavigatorPage(navigatorKey: _navigatorKeys[1], child: const SearchTab()),
          NavigatorPage(navigatorKey: _navigatorKeys[2], child: const ProfileTab()),
        ],
      ),
      bottomNavigationBar: BottomNavigationBar(
        currentIndex: _currentIndex,
        onTap: (index) {
          if (_currentIndex == index) {
            // Pop to first route if tapping same tab
            _navigatorKeys[index].currentState?.popUntil((route) => route.isFirst);
          }
          setState(() => _currentIndex = index);
        },
        items: const [
          BottomNavigationBarItem(icon: Icon(Icons.home), label: 'Home'),
          BottomNavigationBarItem(icon: Icon(Icons.search), label: 'Search'),
          BottomNavigationBarItem(icon: Icon(Icons.person), label: 'Profile'),
        ],
      ),
    );
  }
}

class NavigatorPage extends StatelessWidget {
  final GlobalKey<NavigatorState> navigatorKey;
  final Widget child;

  const NavigatorPage({super.key, required this.navigatorKey, required this.child});

  @override
  Widget build(BuildContext context) {
    return Navigator(
      key: navigatorKey,
      onGenerateRoute: (settings) => MaterialPageRoute(builder: (_) => child),
    );
  }
}
```

---

# 11. Hands-On Project: E-commerce Product Browsing App

## Project Overview
Build a multi-screen e-commerce app with:
- Home screen with product grid
- Product detail screen
- Cart screen
- Profile screen
- Named routes
- Data passing between screens
- Hero animations for product images
- Bottom navigation with nested stacks

## Complete Code

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const EcommerceApp());
}

// ============ MODELS ============
class Product {
  final String id;
  final String name;
  final String description;
  final double price;
  final String imageUrl;
  final String category;
  final double rating;

  Product({
    required this.id,
    required this.name,
    required this.description,
    required this.price,
    required this.imageUrl,
    required this.category,
    required this.rating,
  });
}

// ============ MOCK DATA ============
final List<Product> mockProducts = [
  Product(
    id: '1',
    name: 'Wireless Headphones',
    description: 'Premium noise-cancelling wireless headphones with 30-hour battery life.',
    price: 199.99,
    imageUrl: 'https://via.placeholder.com/300',
    category: 'Electronics',
    rating: 4.8,
  ),
  Product(
    id: '2',
    name: 'Smart Watch Pro',
    description: 'Advanced fitness tracking, heart rate monitor, and GPS.',
    price: 299.99,
    imageUrl: 'https://via.placeholder.com/300',
    category: 'Electronics',
    rating: 4.6,
  ),
  Product(
    id: '3',
    name: 'Running Shoes',
    description: 'Lightweight breathable running shoes with cushioned sole.',
    price: 89.99,
    imageUrl: 'https://via.placeholder.com/300',
    category: 'Sports',
    rating: 4.5,
  ),
  Product(
    id: '4',
    name: 'Backpack',
    description: 'Water-resistant laptop backpack with multiple compartments.',
    price: 59.99,
    imageUrl: 'https://via.placeholder.com/300',
    category: 'Accessories',
    rating: 4.7,
  ),
];

// ============ APP ============
class EcommerceApp extends StatelessWidget {
  const EcommerceApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'ShopEasy',
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.indigo),
        useMaterial3: true,
        cardTheme: CardTheme(elevation: 2, shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(12))),
      ),
      initialRoute: '/',
      routes: {
        '/': (context) => const MainNavigationScreen(),
        '/product_detail': (context) => const ProductDetailScreen(),
        '/cart': (context) => const CartScreen(),
        '/profile': (context) => const ProfileScreen(),
      },
      onGenerateRoute: (settings) {
        if (settings.name == '/product_detail') {
          final product = settings.arguments as Product?;
          if (product != null) {
            return MaterialPageRoute(
              builder: (_) => ProductDetailScreen(product: product),
            );
          }
        }
        return null;
      },
    );
  }
}

// ============ MAIN NAVIGATION WITH BOTTOM TABS ============
class MainNavigationScreen extends StatefulWidget {
  const MainNavigationScreen({super.key});

  @override
  State<MainNavigationScreen> createState() => _MainNavigationScreenState();
}

class _MainNavigationScreenState extends State<MainNavigationScreen> {
  int _currentIndex = 0;

  final List<Widget> _screens = const [
    HomeScreen(),
    SearchScreen(),
    CartScreen(),
    ProfileScreen(),
  ];

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: IndexedStack(
        index: _currentIndex,
        children: _screens,
      ),
      bottomNavigationBar: NavigationBar(
        selectedIndex: _currentIndex,
        onDestinationSelected: (index) => setState(() => _currentIndex = index),
        destinations: const [
          NavigationDestination(icon: Icon(Icons.home_outlined), selectedIcon: Icon(Icons.home), label: 'Home'),
          NavigationDestination(icon: Icon(Icons.search_outlined), selectedIcon: Icon(Icons.search), label: 'Search'),
          NavigationDestination(icon: Icon(Icons.shopping_cart_outlined), selectedIcon: Icon(Icons.shopping_cart), label: 'Cart'),
          NavigationDestination(icon: Icon(Icons.person_outlined), selectedIcon: Icon(Icons.person), label: 'Profile'),
        ],
      ),
    );
  }
}

// ============ HOME SCREEN ============
class HomeScreen extends StatelessWidget {
  const HomeScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('ShopEasy', style: TextStyle(fontWeight: FontWeight.bold)),
        centerTitle: true,
        actions: [
          IconButton(
            icon: const Icon(Icons.notifications_outlined),
            onPressed: () {},
          ),
        ],
      ),
      body: SingleChildScrollView(
        padding: const EdgeInsets.all(16),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            // Search Bar
            TextField(
              decoration: InputDecoration(
                hintText: 'Search products...',
                prefixIcon: const Icon(Icons.search),
                border: OutlineInputBorder(borderRadius: BorderRadius.circular(12)),
                filled: true,
                fillColor: Colors.grey.shade100,
              ),
            ),
            const SizedBox(height: 24),

            // Categories
            const Text('Categories', style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
            const SizedBox(height: 12),
            SizedBox(
              height: 50,
              child: ListView(
                scrollDirection: Axis.horizontal,
                children: ['All', 'Electronics', 'Sports', 'Accessories', 'Fashion']
                    .map((cat) => Padding(
                          padding: const EdgeInsets.only(right: 8),
                          child: Chip(
                            label: Text(cat),
                            backgroundColor: cat == 'All' ? Colors.indigo : Colors.grey.shade200,
                            labelStyle: TextStyle(color: cat == 'All' ? Colors.white : Colors.black87),
                          ),
                        ))
                    .toList(),
              ),
            ),
            const SizedBox(height: 24),

            // Products Grid
            const Text('Popular Products', style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
            const SizedBox(height: 12),
            GridView.builder(
              shrinkWrap: true,
              physics: const NeverScrollableScrollPhysics(),
              gridDelegate: const SliverGridDelegateWithFixedCrossAxisCount(
                crossAxisCount: 2,
                childAspectRatio: 0.75,
                crossAxisSpacing: 12,
                mainAxisSpacing: 12,
              ),
              itemCount: mockProducts.length,
              itemBuilder: (context, index) {
                final product = mockProducts[index];
                return ProductCard(product: product);
              },
            ),
          ],
        ),
      ),
    );
  }
}

// ============ PRODUCT CARD ============
class ProductCard extends StatelessWidget {
  final Product product;
  const ProductCard({super.key, required this.product});

  @override
  Widget build(BuildContext context) {
    return GestureDetector(
      onTap: () {
        Navigator.pushNamed(
          context,
          '/product_detail',
          arguments: product,
        );
      },
      child: Card(
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            Expanded(
              child: Hero(
                tag: 'product-${product.id}',
                child: Container(
                  decoration: BoxDecoration(
                    color: Colors.grey.shade300,
                    borderRadius: const BorderRadius.vertical(top: Radius.circular(12)),
                  ),
                  child: const Center(child: Icon(Icons.image, size: 50, color: Colors.grey)),
                ),
              ),
            ),
            Padding(
              padding: const EdgeInsets.all(12),
              child: Column(
                crossAxisAlignment: CrossAxisAlignment.start,
                children: [
                  Text(product.name, style: const TextStyle(fontWeight: FontWeight.bold), maxLines: 1, overflow: TextOverflow.ellipsis),
                  const SizedBox(height: 4),
                  Text('$${product.price}', style: const TextStyle(color: Colors.indigo, fontWeight: FontWeight.bold, fontSize: 16)),
                  const SizedBox(height: 4),
                  Row(
                    children: [
                      const Icon(Icons.star, size: 16, color: Colors.amber),
                      Text(' ${product.rating}'),
                    ],
                  ),
                ],
              ),
            ),
          ],
        ),
      ),
    );
  }
}

// ============ PRODUCT DETAIL SCREEN ============
class ProductDetailScreen extends StatelessWidget {
  final Product? product;
  const ProductDetailScreen({super.key, this.product});

  @override
  Widget build(BuildContext context) {
    final Product displayProduct;
    if (product != null) {
      displayProduct = product!;
    } else {
      final args = ModalRoute.of(context)?.settings.arguments;
      if (args is Product) {
        displayProduct = args;
      } else {
        return const Scaffold(body: Center(child: Text('Product not found')));
      }
    }

    return Scaffold(
      body: CustomScrollView(
        slivers: [
          SliverAppBar(
            expandedHeight: 300,
            pinned: true,
            flexibleSpace: FlexibleSpaceBar(
              background: Hero(
                tag: 'product-${displayProduct.id}',
                child: Container(
                  color: Colors.grey.shade300,
                  child: const Center(child: Icon(Icons.image, size: 100, color: Colors.grey)),
                ),
              ),
            ),
          ),
          SliverToBoxAdapter(
            child: Padding(
              padding: const EdgeInsets.all(24),
              child: Column(
                crossAxisAlignment: CrossAxisAlignment.start,
                children: [
                  Row(
                    mainAxisAlignment: MainAxisAlignment.spaceBetween,
                    children: [
                      Expanded(
                        child: Text(
                          displayProduct.name,
                          style: const TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
                        ),
                      ),
                      Container(
                        padding: const EdgeInsets.symmetric(horizontal: 12, vertical: 6),
                        decoration: BoxDecoration(
                          color: Colors.amber.shade100,
                          borderRadius: BorderRadius.circular(20),
                        ),
                        child: Row(
                          children: [
                            const Icon(Icons.star, size: 18, color: Colors.amber),
                            Text(' ${displayProduct.rating}', style: const TextStyle(fontWeight: FontWeight.bold)),
                          ],
                        ),
                      ),
                    ],
                  ),
                  const SizedBox(height: 8),
                  Text(
                    '$${displayProduct.price}',
                    style: const TextStyle(fontSize: 28, fontWeight: FontWeight.bold, color: Colors.indigo),
                  ),
                  const SizedBox(height: 16),
                  const Text('Description', style: TextStyle(fontSize: 18, fontWeight: FontWeight.bold)),
                  const SizedBox(height: 8),
                  Text(displayProduct.description, style: TextStyle(color: Colors.grey.shade700, height: 1.5)),
                  const SizedBox(height: 24),
                  SizedBox(
                    width: double.infinity,
                    height: 50,
                    child: ElevatedButton.icon(
                      onPressed: () {
                        ScaffoldMessenger.of(context).showSnackBar(
                          const SnackBar(content: Text('Added to cart!')),
                        );
                      },
                      icon: const Icon(Icons.shopping_cart),
                      label: const Text('Add to Cart', style: TextStyle(fontSize: 16)),
                      style: ElevatedButton.styleFrom(shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(12))),
                    ),
                  ),
                ],
              ),
            ),
          ),
        ],
      ),
    );
  }
}

// ============ SEARCH SCREEN ============
class SearchScreen extends StatefulWidget {
  const SearchScreen({super.key});

  @override
  State<SearchScreen> createState() => _SearchScreenState();
}

class _SearchScreenState extends State<SearchScreen> {
  String _query = '';

  List<Product> get _filteredProducts {
    if (_query.isEmpty) return mockProducts;
    return mockProducts.where((p) => p.name.toLowerCase().contains(_query.toLowerCase())).toList();
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('Search')),
      body: Column(
        children: [
          Padding(
            padding: const EdgeInsets.all(16),
            child: TextField(
              onChanged: (value) => setState(() => _query = value),
              decoration: InputDecoration(
                hintText: 'Search products...',
                prefixIcon: const Icon(Icons.search),
                border: OutlineInputBorder(borderRadius: BorderRadius.circular(12)),
              ),
            ),
          ),
          Expanded(
            child: ListView.builder(
              itemCount: _filteredProducts.length,
              itemBuilder: (context, index) {
                final product = _filteredProducts[index];
                return ListTile(
                  leading: const CircleAvatar(child: Icon(Icons.image)),
                  title: Text(product.name),
                  subtitle: Text('$${product.price}'),
                  onTap: () {
                    Navigator.pushNamed(context, '/product_detail', arguments: product);
                  },
                );
              },
            ),
          ),
        ],
      ),
    );
  }
}

// ============ CART SCREEN ============
class CartScreen extends StatelessWidget {
  const CartScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('Shopping Cart')),
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Icon(Icons.shopping_cart_outlined, size: 80, color: Colors.grey.shade400),
            const SizedBox(height: 16),
            Text('Your cart is empty', style: TextStyle(fontSize: 18, color: Colors.grey.shade600)),
            const SizedBox(height: 16),
            ElevatedButton(
              onPressed: () {
                // Navigate to home and switch tab
                Navigator.pushReplacementNamed(context, '/');
              },
              child: const Text('Start Shopping'),
            ),
          ],
        ),
      ),
    );
  }
}

// ============ PROFILE SCREEN ============
class ProfileScreen extends StatelessWidget {
  const ProfileScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('My Profile')),
      body: SingleChildScrollView(
        padding: const EdgeInsets.all(24),
        child: Column(
          children: [
            const CircleAvatar(radius: 50, child: Icon(Icons.person, size: 50)),
            const SizedBox(height: 16),
            const Text('John Doe', style: TextStyle(fontSize: 24, fontWeight: FontWeight.bold)),
            const Text('john@example.com', style: TextStyle(color: Colors.grey)),
            const SizedBox(height: 32),
            _buildMenuItem(Icons.shopping_bag, 'My Orders', () {}),
            _buildMenuItem(Icons.favorite, 'Wishlist', () {}),
            _buildMenuItem(Icons.location_on, 'Addresses', () {}),
            _buildMenuItem(Icons.payment, 'Payment Methods', () {}),
            _buildMenuItem(Icons.settings, 'Settings', () {}),
            const SizedBox(height: 16),
            SizedBox(
              width: double.infinity,
              child: OutlinedButton(
                onPressed: () {
                  // Logout: clear stack and go to login
                  Navigator.pushNamedAndRemoveUntil(context, '/', (route) => false);
                },
                child: const Text('Logout'),
              ),
            ),
          ],
        ),
      ),
    );
  }

  Widget _buildMenuItem(IconData icon, String title, VoidCallback onTap) {
    return Card(
      margin: const EdgeInsets.only(bottom: 8),
      child: ListTile(
        leading: Icon(icon, color: Colors.indigo),
        title: Text(title),
        trailing: const Icon(Icons.chevron_right),
        onTap: onTap,
      ),
    );
  }
}
```

---

# 12. Common Mistakes & How to Avoid Them

## Mistake 1: Using BuildContext After Async Gap
```dart
// WRONG — context may be invalid after await
void _navigate() async {
  await Future.delayed(const Duration(seconds: 1));
  Navigator.push(context, ...); // Crash risk!
}

// CORRECT — Check mounted or use a GlobalKey
void _navigate() async {
  await Future.delayed(const Duration(seconds: 1));
  if (mounted) {
    Navigator.push(context, ...);
  }
}
```

## Mistake 2: Not Handling Pop Result Null
```dart
// WRONG — Crashes if user presses back button
final result = await Navigator.push(...);
print(result.toString()); // Null check error!

// CORRECT
final result = await Navigator.push(...);
if (result != null) {
  print(result.toString());
}
```

## Mistake 3: Hardcoding Routes Everywhere
```dart
// WRONG — Typo-prone and hard to maintain
Navigator.pushNamed(context, '/proflie'); // Silent failure

// CORRECT — Use constants
class Routes {
  static const home = '/';
  static const profile = '/profile';
  static const productDetail = '/product_detail';
}
Navigator.pushNamed(context, Routes.profile);
```

## Mistake 4: Forgetting to Pass Arguments in Named Routes
```dart
// WRONG — Product detail expects arguments
Navigator.pushNamed(context, '/product_detail'); // Null crash!

// CORRECT
Navigator.pushNamed(context, '/product_detail', arguments: product);
```

## Mistake 5: Not Using IndexedStack for Bottom Navigation
```dart
// WRONG — State lost when switching tabs
body: _screens[_currentIndex],

// CORRECT — Preserves state and scroll position
body: IndexedStack(
  index: _currentIndex,
  children: _screens,
),
```

## Mistake 6: Blocking Back Button Without Handling
```dart
// WRONG — User is trapped
WillPopScope(
  onWillPop: () async => false,
  child: ...,
)

// CORRECT — Show confirmation or save state
WillPopScope(
  onWillPop: () async {
    return await showDialog(...) ?? false;
  },
  child: ...,
)
```

## Mistake 7: Deep Linking Without URL Encoding
```dart
// WRONG — Spaces and special characters break URLs
final url = 'https://myapp.com/product/$productName';

// CORRECT
final url = Uri.https('myapp.com', '/product/${Uri.encodeComponent(productId)}');
```

---

# 13. Day 9 Checklist

Use this checklist to verify mastery:
- [ ] Understands difference between Navigator 1.0 and 2.0
- [ ] Can push and pop screens with `Navigator.push` / `Navigator.pop`
- [ ] Can use `pushReplacement` for login → home flows
- [ ] Can use `pushAndRemoveUntil` to clear navigation stack
- [ ] Can pass data to screens via constructor arguments
- [ ] Can return data from screens using `await Navigator.push`
- [ ] Can set up named routes in `MaterialApp.routes`
- [ ] Can use `onGenerateRoute` for dynamic route handling with arguments
- [ ] Can extract arguments using `ModalRoute.of(context)!.settings.arguments`
- [ ] Understands Navigation 2.0 components (Router, RouteInformationParser, RouterDelegate)
- [ ] Can implement basic deep linking configuration
- [ ] Can use `go_router` for declarative routing
- [ ] Can create custom page transitions (Slide, Fade)
- [ ] Can show modal bottom sheets and dialogs
- [ ] Can implement bottom navigation with `IndexedStack`
- [ ] Understands nested navigation concepts
- [ ] Built the E-commerce Product Browsing App with all screens
- [ ] App includes Hero animations for product images
- [ ] App uses named routes with arguments passing
- [ ] App handles empty states and navigation edge cases
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **Use Navigator 1.0** for simple mobile apps. Use **Navigation 2.0 / go_router** for web or complex state-driven navigation.
2. **Always check `mounted`** before using context after an async operation.
3. **Use `IndexedStack`** for bottom navigation to preserve tab state and scroll positions.
4. **Never use both `initialValue` and controller** (Day 8 rule still applies everywhere).
5. **Define route constants** to avoid string typos in named routes.
6. **Pass simple data via constructors**, complex data via `RouteSettings.arguments`.
7. **Use `pushReplacement`** for auth flows so users can't go back to login.
8. **Use `go_router`** in 2026 for production apps — it's the official recommended package.
9. **Handle null results** when awaiting navigation — users can press the back button.
10. **Wrap deep link hosts** properly in AndroidManifest and Info.plist for universal links.

---

# Extra Practice (Do These Tonight!)

1. **Login Flow:** Build a splash → onboarding → login → home flow. Use `pushReplacement` and `pushAndRemoveUntil` appropriately.
2. **Settings Wizard:** Create a 3-step settings wizard that passes accumulated data forward and returns final settings to the home screen.
3. **News App with Deep Links:** Build a news app where `/article/:id` opens directly to the article detail screen from a push notification URL.
4. **E-commerce Checkout Flow:** Extend the Day 9 project with a multi-step checkout (Cart → Shipping → Payment → Confirmation) that passes order data forward.
5. **Flutter Web Portfolio:** Convert the e-commerce app to Flutter Web using `go_router` with proper URL paths for each screen.

---

**Congratulations!** You've completed Day 9. You now know how to build professional multi-screen Flutter apps with navigation, data passing, deep linking, and advanced routing patterns. These skills are essential for every real-world Flutter app.

**Next Up → Day 10: Theming, Assets & Responsive Design**

---

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 9: Navigation & Routing — Complete Deep Dive*

# Day 10: Theming, Assets & Responsive Design
## Complete Deep Dive

**Goal:** Make Flutter apps beautiful, consistent, and responsive across all screen sizes. This guide covers ThemeData, ColorScheme, custom fonts, image assets, dark mode, responsive layouts, and a complete redesigned multi-screen app.

---

# Table of Contents
1. Why Theming & Responsive Design Matter
2. ThemeData & ColorScheme Deep Dive
3. TextTheme & Typography Mastery
4. Dark Mode Implementation
5. Custom Fonts & Google Fonts
6. Assets: Images, SVG & Icons
7. Responsive Design Foundations
8. MediaQuery, LayoutBuilder & OrientationBuilder
9. flutter_screenutil & Responsive Frameworks
10. Platform Adaptive UI
11. Hands-On Project: Themed News Reader App
12. Common Mistakes & How to Avoid Them
13. Day 10 Checklist

---

# 1. Why Theming & Responsive Design Matter

## The Real-World Challenge
| Problem | Impact |
|---|---|
| Inconsistent colors across screens | Looks unprofessional, confuses users |
| Hardcoded colors everywhere | Nightmare to update brand colors |
| No dark mode support | Users complain, battery drain on OLED |
| Pixel-based sizing only | UI breaks on tablets and foldables |
| Missing asset optimization | Slow app startup, large APK size |

## What You'll Master Today
- Create a single source of truth for app styling
- Toggle between light and dark themes instantly
- Load custom fonts and SVG icons
- Make every screen adapt to phones, tablets, and desktops
- Build a production-ready themed app

---

# 2. ThemeData & ColorScheme Deep Dive

## What is ThemeData?
`ThemeData` is the configuration object that controls the visual appearance of your entire app. One change here propagates everywhere.

## Basic Theme Setup
```dart
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Themed App',
      theme: ThemeData(
        useMaterial3: true,
        colorScheme: ColorScheme.fromSeed(
          seedColor: Colors.indigo,
          brightness: Brightness.light,
        ),
      ),
      home: const HomeScreen(),
    );
  }
}
```

## ColorScheme.fromSeed (Recommended in 2026)
Material 3's dynamic color system generates a complete palette from a single seed color.
```dart
ColorScheme.fromSeed(
  seedColor: Colors.deepPurple,
  brightness: Brightness.light,
  // Optional overrides
  primary: Colors.deepPurple,
  secondary: Colors.teal,
  error: Colors.red.shade700,
)
```

## Complete ThemeData Configuration
```dart
ThemeData(
  useMaterial3: true,
  colorScheme: ColorScheme.fromSeed(seedColor: Colors.indigo),

  // AppBar theme
  appBarTheme: AppBarTheme(
    centerTitle: true,
    elevation: 0,
    backgroundColor: Colors.indigo,
    foregroundColor: Colors.white,
    titleTextStyle: const TextStyle(
      fontSize: 20,
      fontWeight: FontWeight.w600,
      color: Colors.white,
    ),
  ),

  // Card theme
  cardTheme: CardTheme(
    elevation: 2,
    shape: RoundedRectangleBorder(
      borderRadius: BorderRadius.circular(16),
    ),
    margin: const EdgeInsets.all(8),
  ),

  // ElevatedButton theme
  elevatedButtonTheme: ElevatedButtonThemeData(
    style: ElevatedButton.styleFrom(
      padding: const EdgeInsets.symmetric(horizontal: 24, vertical: 14),
      shape: RoundedRectangleBorder(
        borderRadius: BorderRadius.circular(12),
      ),
    ),
  ),

  // Input decoration theme
  inputDecorationTheme: InputDecorationTheme(
    filled: true,
    fillColor: Colors.grey.shade100,
    border: OutlineInputBorder(
      borderRadius: BorderRadius.circular(12),
      borderSide: BorderSide.none,
    ),
    contentPadding: const EdgeInsets.symmetric(horizontal: 16, vertical: 14),
  ),

  // FloatingActionButton theme
  floatingActionButtonTheme: const FloatingActionButtonThemeData(
    elevation: 4,
    shape: CircleBorder(),
  ),

  // Divider theme
  dividerTheme: DividerThemeData(
    color: Colors.grey.shade300,
    thickness: 1,
    space: 32,
  ),

  // Bottom navigation bar theme
  bottomNavigationBarTheme: BottomNavigationBarThemeData(
    type: BottomNavigationBarType.fixed,
    selectedItemColor: Colors.indigo,
    unselectedItemColor: Colors.grey.shade600,
    elevation: 8,
  ),
)
```

## Accessing Theme in Widgets
```dart
// Get the current theme
final theme = Theme.of(context);
final colorScheme = Theme.of(context).colorScheme;

// Use theme colors
Container(
  color: colorScheme.primary,
  child: Text('Hello', style: TextStyle(color: colorScheme.onPrimary)),
)

// Use theme text styles
Text('Title', style: theme.textTheme.headlineLarge)
Text('Body', style: theme.textTheme.bodyLarge)
```

---

# 3. TextTheme & Typography Mastery

## Material 3 Text Scale (2026 Standard)
| Style | Size | Weight | Usage |
|---|---|---|---|
| `displayLarge` | 57 | Regular | Hero text |
| `displayMedium` | 45 | Regular | Large headlines |
| `displaySmall` | 36 | Regular | Medium headlines |
| `headlineLarge` | 32 | Regular | Screen titles |
| `headlineMedium` | 28 | Regular | Section headers |
| `headlineSmall` | 24 | Regular | Card titles |
| `titleLarge` | 22 | Medium | App bar titles |
| `titleMedium` | 16 | Medium | List titles |
| `titleSmall` | 14 | Medium | Dialog titles |
| `bodyLarge` | 16 | Regular | Primary body text |
| `bodyMedium` | 14 | Regular | Secondary body text |
| `bodySmall` | 12 | Regular | Captions |
| `labelLarge` | 14 | Medium | Buttons |
| `labelMedium` | 12 | Medium | Small buttons |
| `labelSmall` | 11 | Medium | Overlines |

## Custom TextTheme
```dart
textTheme: TextTheme(
  displayLarge: GoogleFonts.poppins(fontSize: 57, fontWeight: FontWeight.w300),
  headlineLarge: GoogleFonts.poppins(fontSize: 32, fontWeight: FontWeight.w600),
  titleLarge: GoogleFonts.poppins(fontSize: 22, fontWeight: FontWeight.w500),
  bodyLarge: GoogleFonts.inter(fontSize: 16, fontWeight: FontWeight.w400, height: 1.5),
  bodyMedium: GoogleFonts.inter(fontSize: 14, fontWeight: FontWeight.w400),
  labelLarge: GoogleFonts.inter(fontSize: 14, fontWeight: FontWeight.w600),
),
```

## CopyWith for Local Overrides
```dart
Text(
  'Important!',
  style: Theme.of(context).textTheme.headlineMedium?.copyWith(
    color: Colors.red,
    fontWeight: FontWeight.bold,
  ),
)
```

---

# 4. Dark Mode Implementation

## Manual Theme Toggle with Provider (Recommended)

### Step 1: Create Theme Provider
```dart
import 'package:flutter/material.dart';

class ThemeProvider extends ChangeNotifier {
  ThemeMode _themeMode = ThemeMode.system;

  ThemeMode get themeMode => _themeMode;
  bool get isDarkMode => _themeMode == ThemeMode.dark;

  void toggleTheme(bool isDark) {
    _themeMode = isDark ? ThemeMode.dark : ThemeMode.light;
    notifyListeners();
  }

  void setSystemTheme() {
    _themeMode = ThemeMode.system;
    notifyListeners();
  }
}
```

### Step 2: Wrap App with ChangeNotifierProvider
```dart
void main() {
  runApp(
    ChangeNotifierProvider(
      create: (_) => ThemeProvider(),
      child: const MyApp(),
    ),
  );
}
```

### Step 3: Configure MaterialApp
```dart
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    final themeProvider = context.watch<ThemeProvider>();

    return MaterialApp(
      title: 'Adaptive Theme',
      themeMode: themeProvider.themeMode,
      theme: _buildLightTheme(),
      darkTheme: _buildDarkTheme(),
      home: const HomeScreen(),
    );
  }

  ThemeData _buildLightTheme() {
    return ThemeData(
      useMaterial3: true,
      brightness: Brightness.light,
      colorScheme: ColorScheme.fromSeed(
        seedColor: Colors.indigo,
        brightness: Brightness.light,
      ),
      scaffoldBackgroundColor: Colors.grey.shade50,
      cardTheme: CardTheme(
        color: Colors.white,
        elevation: 2,
        shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(16)),
      ),
    );
  }

  ThemeData _buildDarkTheme() {
    return ThemeData(
      useMaterial3: true,
      brightness: Brightness.dark,
      colorScheme: ColorScheme.fromSeed(
        seedColor: Colors.indigo,
        brightness: Brightness.dark,
      ),
      scaffoldBackgroundColor: const Color(0xFF121212),
      cardTheme: CardTheme(
        color: const Color(0xFF1E1E1E),
        elevation: 2,
        shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(16)),
      ),
    );
  }
}
```

### Step 4: Add Theme Toggle UI
```dart
class SettingsScreen extends StatelessWidget {
  const SettingsScreen({super.key});

  @override
  Widget build(BuildContext context) {
    final themeProvider = context.read<ThemeProvider>();
    final isDark = context.select<ThemeProvider, bool>((p) => p.isDarkMode);

    return Scaffold(
      appBar: AppBar(title: const Text('Settings')),
      body: ListView(
        children: [
          SwitchListTile(
            title: const Text('Dark Mode'),
            subtitle: const Text('Toggle between light and dark theme'),
            value: isDark,
            onChanged: (value) => themeProvider.toggleTheme(value),
          ),
        ],
      ),
    );
  }
}
```

## Adaptive Colors (Light/Dark Safe)
```dart
// Instead of hardcoded colors, use the color scheme
Container(
  color: Theme.of(context).colorScheme.surface,
  child: Text(
    'Hello',
    style: TextStyle(
      color: Theme.of(context).colorScheme.onSurface,
    ),
  ),
)

// Or use adaptive colors
Container(
  color: Theme.of(context).brightness == Brightness.dark
      ? Colors.grey.shade900
      : Colors.grey.shade50,
)
```

---

# 5. Custom Fonts & Google Fonts

## Using Google Fonts (Recommended)
```yaml
# pubspec.yaml
dependencies:
  google_fonts: ^6.2.1
```

```dart
import 'package:google_fonts/google_fonts.dart';

Text('Hello', style: GoogleFonts.poppins(fontSize: 24))
Text('Body', style: GoogleFonts.inter(fontSize: 16))
Text('Serif', style: GoogleFonts.merriweather(fontSize: 18))
```

## Using Custom Fonts (Local)

### Step 1: Add fonts to project
```
assets/
  fonts/
    Poppins-Regular.ttf
    Poppins-Bold.ttf
    Poppins-SemiBold.ttf
```

### Step 2: Declare in pubspec.yaml
```yaml
flutter:
  fonts:
    - family: Poppins
      fonts:
        - asset: assets/fonts/Poppins-Regular.ttf
          weight: 400
        - asset: assets/fonts/Poppins-SemiBold.ttf
          weight: 600
        - asset: assets/fonts/Poppins-Bold.ttf
          weight: 700
```

### Step 3: Use in Theme
```dart
textTheme: TextTheme(
  headlineLarge: const TextStyle(
    fontFamily: 'Poppins',
    fontWeight: FontWeight.w700,
    fontSize: 32,
  ),
  bodyLarge: const TextStyle(
    fontFamily: 'Poppins',
    fontWeight: FontWeight.w400,
    fontSize: 16,
  ),
),
```

---

# 6. Assets: Images, SVG & Icons

## Image Assets Setup
```yaml
# pubspec.yaml
flutter:
  assets:
    - assets/images/
    - assets/icons/
    - assets/animations/
```

## Loading Local Images
```dart
// Asset image
Image.asset('assets/images/logo.png')
Image.asset('assets/images/banner.jpg', fit: BoxFit.cover)

// With placeholder and error handling
Image.asset(
  'assets/images/photo.png',
  width: 100,
  height: 100,
  fit: BoxFit.cover,
  errorBuilder: (context, error, stackTrace) =>
      const Icon(Icons.broken_image),
)
```

## Network Images with Caching
```yaml
dependencies:
  cached_network_image: ^3.4.0
```

```dart
CachedNetworkImage(
  imageUrl: 'https://example.com/image.jpg',
  placeholder: (context, url) => const CircularProgressIndicator(),
  errorWidget: (context, url, error) => const Icon(Icons.error),
  fit: BoxFit.cover,
)
```

## SVG Support
```yaml
dependencies:
  flutter_svg: ^2.0.10
```

```dart
import 'package:flutter_svg/flutter_svg.dart';

SvgPicture.asset('assets/icons/heart.svg', width: 24, height: 24)
SvgPicture.network('https://example.com/icon.svg')
```

## App Icons & Launcher
```yaml
dependencies:
  flutter_launcher_icons: ^0.14.0
```

```yaml
# pubspec.yaml
flutter_launcher_icons:
  android: "launcher_icon"
  ios: true
  image_path: "assets/images/app_icon.png"
  adaptive_icon_background: "#FFFFFF"
  adaptive_icon_foreground: "assets/images/app_icon_foreground.png"
```

```bash
flutter pub run flutter_launcher_icons
```

---

# 7. Responsive Design Foundations

## Why Responsive Design?
| Device | Width Range | Strategy |
|---|---|---|
| Small phone | 320-375dp | Compact layout |
| Medium phone | 376-414dp | Standard layout |
| Large phone / Foldable | 415-600dp | Expanded layout |
| Tablet | 601-900dp | Two-pane layout |
| Desktop | 900dp+ | Multi-column, sidebar |

## Core Principles
1. **Use relative units** — percentages, fractions, not fixed pixels
2. **Test on multiple screen sizes** — use device preview
3. **Breakpoints matter** — adapt layout at key widths
4. **Orientation-aware** — landscape vs portrait layouts
5. **Text scaling** — respect user's accessibility settings

---

# 8. MediaQuery, LayoutBuilder & OrientationBuilder

## MediaQuery
Access device screen dimensions, padding, and platform features.

```dart
// Screen size
final size = MediaQuery.of(context).size;
final width = size.width;
final height = size.height;

// Safe area padding (notch, status bar, home indicator)
final padding = MediaQuery.of(context).padding;
final topPadding = padding.top;
final bottomPadding = padding.bottom;

// Device pixel ratio
final pixelRatio = MediaQuery.of(context).devicePixelRatio;

// Text scale factor (accessibility)
final textScale = MediaQuery.of(context).textScaleFactor;

// Platform brightness
final brightness = MediaQuery.of(context).platformBrightness;

// Keyboard visibility
final viewInsets = MediaQuery.of(context).viewInsets;
final isKeyboardOpen = viewInsets.bottom > 0;
```

## LayoutBuilder
Rebuilds based on parent constraints — perfect for responsive layouts.

```dart
LayoutBuilder(
  builder: (context, constraints) {
    if (constraints.maxWidth < 600) {
      return _buildMobileLayout();
    } else if (constraints.maxWidth < 900) {
      return _buildTabletLayout();
    } else {
      return _buildDesktopLayout();
    }
  },
)
```

## OrientationBuilder
Rebuilds when device rotates.

```dart
OrientationBuilder(
  builder: (context, orientation) {
    return GridView.count(
      crossAxisCount: orientation == Orientation.portrait ? 2 : 4,
      children: [...],
    );
  },
)
```

## Combined Responsive Widget
```dart
class ResponsiveLayout extends StatelessWidget {
  final Widget mobile;
  final Widget? tablet;
  final Widget? desktop;

  const ResponsiveLayout({
    super.key,
    required this.mobile,
    this.tablet,
    this.desktop,
  });

  @override
  Widget build(BuildContext context) {
    return LayoutBuilder(
      builder: (context, constraints) {
        if (constraints.maxWidth >= 1200 && desktop != null) {
          return desktop!;
        }
        if (constraints.maxWidth >= 600 && tablet != null) {
          return tablet!;
        }
        return mobile;
      },
    );
  }
}

// Usage
ResponsiveLayout(
  mobile: const MobileHome(),
  tablet: const TabletHome(),
  desktop: const DesktopHome(),
)
```

---

# 9. flutter_screenutil & Responsive Frameworks

## flutter_screenutil (Most Popular)
Design on a standard screen size (e.g., 375x812 iPhone X) and scale everywhere.

```yaml
dependencies:
  flutter_screenutil: ^5.9.3
```

```dart
void main() async {
  WidgetsFlutterBinding.ensureInitialized();
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return ScreenUtilInit(
      designSize: const Size(375, 812), // Base design size
      minTextAdapt: true,
      splitScreenMode: true,
      builder: (context, child) {
        return MaterialApp(
          title: 'Responsive App',
          home: child,
        );
      },
      child: const HomeScreen(),
    );
  }
}

// Usage in widgets
Container(
  width: 200.w,  // 200 logical pixels scaled
  height: 100.h,
  padding: EdgeInsets.all(16.r), // Radius-aware
  child: Text('Hello', style: TextStyle(fontSize: 16.sp)),
)
```

## responsive_builder (Alternative)
```yaml
dependencies:
  responsive_builder: ^0.7.1
```

```dart
ScreenTypeLayout(
  mobile: MobileWidget(),
  tablet: TabletWidget(),
  desktop: DesktopWidget(),
)
```

## Fractionally Sized Widgets (Built-in)
```dart
FractionallySizedBox(
  widthFactor: 0.8, // 80% of parent width
  child: MyWidget(),
)

AspectRatio(
  aspectRatio: 16 / 9,
  child: VideoPlayer(),
)

Expanded(
  flex: 2, // Takes 2/3 of remaining space
  child: Sidebar(),
)
```

---

# 10. Platform Adaptive UI

## Platform-Specific Widgets
```dart
import 'dart:io' show Platform;
import 'package:flutter/cupertino.dart';

// Adaptive button
Widget adaptiveButton({required String text, required VoidCallback onPressed}) {
  if (Platform.isIOS) {
    return CupertinoButton(
      color: Colors.indigo,
      onPressed: onPressed,
      child: Text(text),
    );
  }
  return ElevatedButton(onPressed: onPressed, child: Text(text));
}

// Adaptive dialog
Future<bool?> showAdaptiveDialog(BuildContext context) {
  if (Platform.isIOS) {
    return showCupertinoDialog(
      context: context,
      builder: (_) => CupertinoAlertDialog(
        title: const Text('Confirm'),
        actions: [
          CupertinoDialogAction(onPressed: () => Navigator.pop(context, false), child: const Text('Cancel')),
          CupertinoDialogAction(onPressed: () => Navigator.pop(context, true), child: const Text('OK')),
        ],
      ),
    );
  }
  return showDialog(
    context: context,
    builder: (_) => AlertDialog(
      title: const Text('Confirm'),
      actions: [
        TextButton(onPressed: () => Navigator.pop(context, false), child: const Text('Cancel')),
        TextButton(onPressed: () => Navigator.pop(context, true), child: const Text('OK')),
      ],
    ),
  );
}
```

## Using flutter_platform_widgets
```yaml
dependencies:
  flutter_platform_widgets: ^7.0.1
```

```dart
PlatformElevatedButton(
  onPressed: () {},
  child: const Text('Adaptive Button'),
)

PlatformScaffold(
  appBar: PlatformAppBar(title: const Text('Adaptive')),
  body: const Center(child: Text('Hello')),
)
```

---

# 11. Hands-On Project: Themed News Reader App

## Project Overview
Build a beautiful, responsive news reader app featuring:
- Light & Dark theme toggle
- Custom Google Fonts (Poppins + Inter)
- Responsive grid layout (2 cols mobile, 3 cols tablet)
- Cached network images
- SVG icons
- Adaptive cards with Material 3 design

## Complete Code

```dart
import 'package:flutter/material.dart';
import 'package:google_fonts/google_fonts.dart';
import 'package:cached_network_image/cached_network_image.dart';
import 'package:flutter_svg/flutter_svg.dart';
import 'package:provider/provider.dart';

void main() {
  runApp(
    ChangeNotifierProvider(
      create: (_) => ThemeProvider(),
      child: const NewsApp(),
    ),
  );
}

// ============ THEME PROVIDER ============
class ThemeProvider extends ChangeNotifier {
  ThemeMode _themeMode = ThemeMode.system;

  ThemeMode get themeMode => _themeMode;
  bool get isDarkMode => _themeMode == ThemeMode.dark;

  void toggleTheme(bool isDark) {
    _themeMode = isDark ? ThemeMode.dark : ThemeMode.light;
    notifyListeners();
  }
}

// ============ APP ============
class NewsApp extends StatelessWidget {
  const NewsApp({super.key});

  @override
  Widget build(BuildContext context) {
    final themeProvider = context.watch<ThemeProvider>();

    return MaterialApp(
      title: 'DailyNews',
      debugShowCheckedModeBanner: false,
      themeMode: themeProvider.themeMode,
      theme: _buildLightTheme(),
      darkTheme: _buildDarkTheme(),
      home: const HomeScreen(),
    );
  }

  ThemeData _buildLightTheme() {
    return ThemeData(
      useMaterial3: true,
      brightness: Brightness.light,
      colorScheme: ColorScheme.fromSeed(seedColor: const Color(0xFF2563EB)),
      scaffoldBackgroundColor: const Color(0xFFF8FAFC),
      textTheme: GoogleFonts.interTextTheme(),
      appBarTheme: AppBarTheme(
        centerTitle: true,
        elevation: 0,
        backgroundColor: const Color(0xFFF8FAFC),
        foregroundColor: const Color(0xFF1E293B),
        titleTextStyle: GoogleFonts.poppins(
          fontSize: 20,
          fontWeight: FontWeight.w600,
          color: const Color(0xFF1E293B),
        ),
      ),
      cardTheme: CardTheme(
        color: Colors.white,
        elevation: 0,
        shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(20)),
        margin: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
      ),
      chipTheme: ChipThemeData(
        backgroundColor: const Color(0xFFEBF5FF),
        labelStyle: GoogleFonts.inter(
          color: const Color(0xFF2563EB),
          fontWeight: FontWeight.w500,
        ),
        shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(20)),
      ),
      bottomNavigationBarTheme: const BottomNavigationBarThemeData(
        type: BottomNavigationBarType.fixed,
        selectedItemColor: Color(0xFF2563EB),
        unselectedItemColor: Color(0xFF94A3B8),
        elevation: 8,
      ),
    );
  }

  ThemeData _buildDarkTheme() {
    return ThemeData(
      useMaterial3: true,
      brightness: Brightness.dark,
      colorScheme: ColorScheme.fromSeed(
        seedColor: const Color(0xFF3B82F6),
        brightness: Brightness.dark,
      ),
      scaffoldBackgroundColor: const Color(0xFF0F172A),
      textTheme: GoogleFonts.interTextTheme(ThemeData.dark().textTheme),
      appBarTheme: AppBarTheme(
        centerTitle: true,
        elevation: 0,
        backgroundColor: const Color(0xFF0F172A),
        foregroundColor: Colors.white,
        titleTextStyle: GoogleFonts.poppins(
          fontSize: 20,
          fontWeight: FontWeight.w600,
          color: Colors.white,
        ),
      ),
      cardTheme: CardTheme(
        color: const Color(0xFF1E293B),
        elevation: 0,
        shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(20)),
        margin: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
      ),
      chipTheme: ChipThemeData(
        backgroundColor: const Color(0xFF1E3A5F),
        labelStyle: GoogleFonts.inter(
          color: const Color(0xFF60A5FA),
          fontWeight: FontWeight.w500,
        ),
        shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(20)),
      ),
      bottomNavigationBarTheme: const BottomNavigationBarThemeData(
        type: BottomNavigationBarType.fixed,
        backgroundColor: Color(0xFF0F172A),
        selectedItemColor: Color(0xFF60A5FA),
        unselectedItemColor: Color(0xFF64748B),
        elevation: 8,
      ),
    );
  }
}

// ============ MOCK DATA ============
class NewsArticle {
  final String id;
  final String title;
  final String excerpt;
  final String imageUrl;
  final String category;
  final String author;
  final String date;
  final int readTime;

  NewsArticle({
    required this.id,
    required this.title,
    required this.excerpt,
    required this.imageUrl,
    required this.category,
    required this.author,
    required this.date,
    required this.readTime,
  });
}

final List<NewsArticle> mockArticles = [
  NewsArticle(
    id: '1',
    title: 'Flutter 4.0 Announced: What's New in 2026',
    excerpt: 'Google unveils major performance improvements and new rendering engine capabilities for Flutter developers worldwide.',
    imageUrl: 'https://picsum.photos/seed/flutter1/400/250',
    category: 'Technology',
    author: 'Sarah Chen',
    date: '2 hours ago',
    readTime: 5,
  ),
  NewsArticle(
    id: '2',
    title: 'The Future of AI in Mobile Development',
    excerpt: 'How artificial intelligence is reshaping the way we build and test mobile applications in the modern era.',
    imageUrl: 'https://picsum.photos/seed/ai2/400/250',
    category: 'AI',
    author: 'James Wilson',
    date: '4 hours ago',
    readTime: 8,
  ),
  NewsArticle(
    id: '3',
    title: 'Sustainable Tech: Green Data Centers',
    excerpt: 'Leading tech companies are investing billions in carbon-neutral infrastructure and renewable energy solutions.',
    imageUrl: 'https://picsum.photos/seed/green3/400/250',
    category: 'Environment',
    author: 'Maria Garcia',
    date: '6 hours ago',
    readTime: 6,
  ),
  NewsArticle(
    id: '4',
    title: 'Remote Work Trends in 2026',
    excerpt: 'The hybrid workplace model continues to evolve with new collaboration tools and asynchronous communication.',
    imageUrl: 'https://picsum.photos/seed/remote4/400/250',
    category: 'Business',
    author: 'Alex Kumar',
    date: '8 hours ago',
    readTime: 4,
  ),
  NewsArticle(
    id: '5',
    title: 'SpaceX Mars Mission Update',
    excerpt: 'Latest developments in the ambitious plan to establish the first human settlement on Mars by 2030.',
    imageUrl: 'https://picsum.photos/seed/space5/400/250',
    category: 'Science',
    author: 'Dr. Emily Park',
    date: '12 hours ago',
    readTime: 10,
  ),
  NewsArticle(
    id: '6',
    title: 'Healthy Eating: Mediterranean Diet',
    excerpt: 'New research confirms the Mediterranean diet as the most sustainable and heart-healthy eating pattern.',
    imageUrl: 'https://picsum.photos/seed/food6/400/250',
    category: 'Health',
    author: 'Dr. Robert Lee',
    date: '1 day ago',
    readTime: 7,
  ),
];

// ============ HOME SCREEN ============
class HomeScreen extends StatefulWidget {
  const HomeScreen({super.key});

  @override
  State<HomeScreen> createState() => _HomeScreenState();
}

class _HomeScreenState extends State<HomeScreen> {
  int _currentIndex = 0;

  @override
  Widget build(BuildContext context) {
    final colorScheme = Theme.of(context).colorScheme;
    final isDark = Theme.of(context).brightness == Brightness.dark;

    return Scaffold(
      appBar: AppBar(
        title: Text('DailyNews', style: GoogleFonts.poppins(fontWeight: FontWeight.w700)),
        actions: [
          IconButton(
            icon: Icon(isDark ? Icons.light_mode : Icons.dark_mode),
            onPressed: () {
              final provider = context.read<ThemeProvider>();
              provider.toggleTheme(!provider.isDarkMode);
            },
          ),
          const SizedBox(width: 8),
        ],
      ),
      body: _currentIndex == 0 ? const NewsFeed() : const ProfileScreen(),
      bottomNavigationBar: BottomNavigationBar(
        currentIndex: _currentIndex,
        onTap: (index) => setState(() => _currentIndex = index),
        items: const [
          BottomNavigationBarItem(icon: Icon(Icons.newspaper_outlined), activeIcon: Icon(Icons.newspaper), label: 'News'),
          BottomNavigationBarItem(icon: Icon(Icons.person_outline), activeIcon: Icon(Icons.person), label: 'Profile'),
        ],
      ),
    );
  }
}

// ============ NEWS FEED ============
class NewsFeed extends StatelessWidget {
  const NewsFeed({super.key});

  @override
  Widget build(BuildContext context) {
    return LayoutBuilder(
      builder: (context, constraints) {
        final crossAxisCount = constraints.maxWidth > 900 ? 3 : (constraints.maxWidth > 600 ? 2 : 1);

        return CustomScrollView(
          slivers: [
            // Categories
            SliverToBoxAdapter(
              child: Padding(
                padding: const EdgeInsets.symmetric(vertical: 16),
                child: SizedBox(
                  height: 40,
                  child: ListView(
                    scrollDirection: Axis.horizontal,
                    padding: const EdgeInsets.symmetric(horizontal: 16),
                    children: ['All', 'Technology', 'AI', 'Science', 'Health', 'Business']
                        .map((cat) => Padding(
                              padding: const EdgeInsets.only(right: 8),
                              child: Chip(
                                label: Text(cat),
                                padding: EdgeInsets.zero,
                                visualDensity: VisualDensity.compact,
                              ),
                            ))
                        .toList(),
                  ),
                ),
              ),
            ),

            // Featured Article (first item, full width)
            SliverToBoxAdapter(
              child: Padding(
                padding: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
                child: FeaturedCard(article: mockArticles.first),
              ),
            ),

            // Section header
            SliverToBoxAdapter(
              child: Padding(
                padding: const EdgeInsets.fromLTRB(16, 24, 16, 8),
                child: Text(
                  'Latest Stories',
                  style: GoogleFonts.poppins(
                    fontSize: 20,
                    fontWeight: FontWeight.w600,
                  ),
                ),
              ),
            ),

            // Article Grid
            SliverPadding(
              padding: const EdgeInsets.symmetric(horizontal: 16),
              sliver: SliverGrid(
                gridDelegate: SliverGridDelegateWithFixedCrossAxisCount(
                  crossAxisCount: crossAxisCount,
                  childAspectRatio: 0.85,
                  crossAxisSpacing: 16,
                  mainAxisSpacing: 16,
                ),
                delegate: SliverChildBuilderDelegate(
                  (context, index) {
                    final article = mockArticles[index + 1];
                    return ArticleCard(article: article);
                  },
                  childCount: mockArticles.length - 1,
                ),
              ),
            ),

            const SliverToBoxAdapter(child: SizedBox(height: 32)),
          ],
        );
      },
    );
  }
}

// ============ FEATURED CARD ============
class FeaturedCard extends StatelessWidget {
  final NewsArticle article;
  const FeaturedCard({super.key, required this.article});

  @override
  Widget build(BuildContext context) {
    final colorScheme = Theme.of(context).colorScheme;

    return Card(
      clipBehavior: Clip.antiAlias,
      child: Column(
        crossAxisAlignment: CrossAxisAlignment.start,
        children: [
          CachedNetworkImage(
            imageUrl: article.imageUrl,
            height: 200,
            width: double.infinity,
            fit: BoxFit.cover,
            placeholder: (context, url) => Container(
              height: 200,
              color: colorScheme.surfaceContainerHighest,
              child: const Center(child: CircularProgressIndicator()),
            ),
            errorWidget: (context, url, error) => Container(
              height: 200,
              color: colorScheme.surfaceContainerHighest,
              child: const Icon(Icons.broken_image, size: 50),
            ),
          ),
          Padding(
            padding: const EdgeInsets.all(16),
            child: Column(
              crossAxisAlignment: CrossAxisAlignment.start,
              children: [
                Chip(
                  label: Text(article.category),
                  visualDensity: VisualDensity.compact,
                  padding: EdgeInsets.zero,
                ),
                const SizedBox(height: 8),
                Text(
                  article.title,
                  style: GoogleFonts.poppins(
                    fontSize: 18,
                    fontWeight: FontWeight.w600,
                    height: 1.3,
                  ),
                  maxLines: 2,
                  overflow: TextOverflow.ellipsis,
                ),
                const SizedBox(height: 8),
                Text(
                  article.excerpt,
                  style: Theme.of(context).textTheme.bodyMedium?.copyWith(
                        color: colorScheme.onSurfaceVariant,
                      ),
                  maxLines: 2,
                  overflow: TextOverflow.ellipsis,
                ),
                const SizedBox(height: 12),
                Row(
                  children: [
                    CircleAvatar(radius: 14, backgroundColor: colorScheme.primaryContainer, child: Text(article.author[0])),
                    const SizedBox(width: 8),
                    Expanded(
                      child: Text(
                        article.author,
                        style: const TextStyle(fontWeight: FontWeight.w500),
                      ),
                    ),
                    Icon(Icons.access_time, size: 14, color: colorScheme.onSurfaceVariant),
                    const SizedBox(width: 4),
                    Text('${article.readTime} min', style: TextStyle(fontSize: 12, color: colorScheme.onSurfaceVariant)),
                  ],
                ),
              ],
            ),
          ),
        ],
      ),
    );
  }
}

// ============ ARTICLE CARD ============
class ArticleCard extends StatelessWidget {
  final NewsArticle article;
  const ArticleCard({super.key, required this.article});

  @override
  Widget build(BuildContext context) {
    final colorScheme = Theme.of(context).colorScheme;

    return Card(
      clipBehavior: Clip.antiAlias,
      child: InkWell(
        onTap: () {},
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            Expanded(
              flex: 3,
              child: CachedNetworkImage(
                imageUrl: article.imageUrl,
                width: double.infinity,
                fit: BoxFit.cover,
                placeholder: (_, __) => Container(color: colorScheme.surfaceContainerHighest),
                errorWidget: (_, __, ___) => Container(
                  color: colorScheme.surfaceContainerHighest,
                  child: const Icon(Icons.broken_image),
                ),
              ),
            ),
            Expanded(
              flex: 4,
              child: Padding(
                padding: const EdgeInsets.all(12),
                child: Column(
                  crossAxisAlignment: CrossAxisAlignment.start,
                  children: [
                    Text(
                      article.category.toUpperCase(),
                      style: GoogleFonts.inter(
                        fontSize: 10,
                        fontWeight: FontWeight.w700,
                        color: colorScheme.primary,
                        letterSpacing: 1,
                      ),
                    ),
                    const SizedBox(height: 6),
                    Text(
                      article.title,
                      style: GoogleFonts.poppins(
                        fontSize: 14,
                        fontWeight: FontWeight.w600,
                        height: 1.3,
                      ),
                      maxLines: 2,
                      overflow: TextOverflow.ellipsis,
                    ),
                    const Spacer(),
                    Row(
                      children: [
                        Icon(Icons.access_time, size: 12, color: colorScheme.onSurfaceVariant),
                        const SizedBox(width: 4),
                        Text(article.date, style: TextStyle(fontSize: 11, color: colorScheme.onSurfaceVariant)),
                      ],
                    ),
                  ],
                ),
              ),
            ),
          ],
        ),
      ),
    );
  }
}

// ============ PROFILE SCREEN ============
class ProfileScreen extends StatelessWidget {
  const ProfileScreen({super.key});

  @override
  Widget build(BuildContext context) {
    final colorScheme = Theme.of(context).colorScheme;
    final isDark = Theme.of(context).brightness == Brightness.dark;

    return SingleChildScrollView(
      padding: const EdgeInsets.all(24),
      child: Column(
        children: [
          CircleAvatar(
            radius: 50,
            backgroundColor: colorScheme.primaryContainer,
            child: Icon(Icons.person, size: 50, color: colorScheme.primary),
          ),
          const SizedBox(height: 16),
          Text('John Doe', style: GoogleFonts.poppins(fontSize: 24, fontWeight: FontWeight.w600)),
          Text('john@dailynews.com', style: TextStyle(color: colorScheme.onSurfaceVariant)),
          const SizedBox(height: 32),
          _buildSettingsTile(
            context,
            icon: isDark ? Icons.light_mode : Icons.dark_mode,
            title: 'Dark Mode',
            trailing: Switch(
              value: isDark,
              onChanged: (value) => context.read<ThemeProvider>().toggleTheme(value),
            ),
          ),
          _buildSettingsTile(context, icon: Icons.notifications_outlined, title: 'Notifications', trailing: const Icon(Icons.chevron_right)),
          _buildSettingsTile(context, icon: Icons.bookmark_outline, title: 'Saved Articles', trailing: const Icon(Icons.chevron_right)),
          _buildSettingsTile(context, icon: Icons.language, title: 'Language', trailing: const Icon(Icons.chevron_right)),
          _buildSettingsTile(context, icon: Icons.help_outline, title: 'Help & Support', trailing: const Icon(Icons.chevron_right)),
          const SizedBox(height: 16),
          SizedBox(
            width: double.infinity,
            child: OutlinedButton.icon(
              onPressed: () {},
              icon: const Icon(Icons.logout),
              label: const Text('Sign Out'),
            ),
          ),
        ],
      ),
    );
  }

  Widget _buildSettingsTile(BuildContext context, {required IconData icon, required String title, required Widget trailing}) {
    return Card(
      margin: const EdgeInsets.only(bottom: 8),
      child: ListTile(
        leading: Icon(icon, color: Theme.of(context).colorScheme.primary),
        title: Text(title),
        trailing: trailing,
      ),
    );
  }
}
```

---

# 12. Common Mistakes & How to Avoid Them

## Mistake 1: Hardcoding Colors Everywhere
```dart
// WRONG — Impossible to maintain
Container(color: Colors.blue)
Text('Hello', style: TextStyle(color: Colors.black87))

// CORRECT — Use theme
Container(color: Theme.of(context).colorScheme.primary)
Text('Hello', style: TextStyle(color: Theme.of(context).colorScheme.onSurface))
```

## Mistake 2: Not Using SafeArea
```dart
// WRONG — Content hidden by notch/status bar
Scaffold(body: Column(children: [...]))

// CORRECT
Scaffold(
  body: SafeArea(child: Column(children: [...])),
)
```

## Mistake 3: Fixed Pixel Sizes for Everything
```dart
// WRONG — Breaks on tablets
Container(width: 350, height: 200)
Text('Title', style: TextStyle(fontSize: 24))

// CORRECT — Use MediaQuery or responsive units
Container(width: MediaQuery.of(context).size.width * 0.9)
Text('Title', style: TextStyle(fontSize: MediaQuery.of(context).size.width * 0.06))
```

## Mistake 4: Forgetting to Add Assets in pubspec.yaml
```yaml
# WRONG — Images won't load
# (missing assets section)

# CORRECT
flutter:
  assets:
    - assets/images/
    - assets/icons/
```

## Mistake 5: Loading Large Images Without Caching
```dart
// WRONG — Reloads every time, wastes bandwidth
Image.network('https://example.com/large_image.jpg')

// CORRECT — Cache for performance
CachedNetworkImage(imageUrl: 'https://example.com/large_image.jpg')
```

## Mistake 6: Not Testing Text Scale Factor
```dart
// WRONG — Text overflows when user increases font size
Text('Long text here that might overflow on large accessibility fonts')

// CORRECT — Wrap in Flexible or use auto-size text
Flexible(child: Text('Long text here...'))
```

## Mistake 7: Theme Not Updating Across App
```dart
// WRONG — setState only rebuilds current widget
setState(() => isDark = !isDark);

// CORRECT — Use Provider, Riverpod, or InheritedWidget
context.read<ThemeProvider>().toggleTheme(value);
```

---

# 13. Day 10 Checklist

Use this checklist to verify mastery:
- [ ] Understands ThemeData and ColorScheme
- [ ] Can create light and dark themes
- [ ] Can toggle themes dynamically with Provider
- [ ] Knows Material 3 text scale (display, headline, title, body, label)
- [ ] Can apply custom fonts (Google Fonts and local TTF)
- [ ] Can load and display asset images
- [ ] Can load and cache network images (cached_network_image)
- [ ] Can display SVG icons (flutter_svg)
- [ ] Understands MediaQuery for screen dimensions
- [ ] Can use LayoutBuilder for responsive breakpoints
- [ ] Can use OrientationBuilder for portrait/landscape
- [ ] Can implement responsive grids (1 col mobile, 2 col tablet, 3 col desktop)
- [ ] Knows flutter_screenutil for design-size scaling
- [ ] Can create platform-adaptive UI (Material vs Cupertino)
- [ ] Built the Themed News Reader App with all features
- [ ] App supports light/dark mode toggle
- [ ] App uses custom fonts (Poppins + Inter)
- [ ] App has responsive article grid layout
- [ ] App uses cached network images with placeholders
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **Always use `ColorScheme.fromSeed`** for Material 3 theming — one seed color generates the entire palette.
2. **Never hardcode colors** — use `Theme.of(context).colorScheme` for light/dark compatibility.
3. **Use `LayoutBuilder`** for responsive layouts, not just `MediaQuery` — it responds to parent constraints.
4. **Cache network images** with `cached_network_image` — essential for performance and offline viewing.
5. **Add assets to `pubspec.yaml`** — Flutter cannot access files not declared there.
6. **Use `SafeArea`** on every screen — handles notches, status bars, and home indicators.
7. **Test with text scaling** at 1.3x and 2.0x — many users need larger text.
8. **Use `flutter_screenutil`** when your designer gives you fixed-size mockups — scales perfectly.
9. **Separate light and dark themes** as complete `ThemeData` objects — don't just invert colors.
10. **Use `Provider` or `Riverpod`** for theme state — `setState` won't propagate across the app.

---

# Extra Practice (Do These Tonight!)

1. **Portfolio App:** Build a personal portfolio with light/dark mode, custom fonts, and responsive grid layout for projects.
2. **Recipe App:** Create a recipe app with category chips, responsive card grid, and hero image transitions.
3. **Weather Dashboard:** Design a weather app that adapts layout between phone (vertical) and tablet (side-by-side).
4. **E-commerce Redesign:** Take the Day 9 e-commerce app and add full theming, dark mode, and responsive product grids.
5. **Settings Screen:** Build a comprehensive settings screen with theme toggle, font size slider, notification toggles, and language selector.

---

**Congratulations!** You've completed Day 10. You now know how to build beautiful, themed, and responsive Flutter apps that look professional on any device. These skills separate beginner apps from production-quality ones.

**Next Up → Day 11: State Management — setState & InheritedWidget**

---

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 10: Theming, Assets & Responsive Design — Complete Deep Dive*


# Day 11: State Management — setState & InheritedWidget
## Complete Deep Dive

**Goal:** Understand Flutter's fundamental state management patterns. Master when to use setState, when to avoid it, and how to share state across the widget tree using InheritedWidget, ValueNotifier, and ChangeNotifier. Build a production-ready Todo app with clean state separation.

---

# Table of Contents
1. Why State Management Matters
2. Ephemeral vs App State
3. setState Deep Dive
4. When NOT to Use setState
5. The Widget Tree & BuildContext
6. InheritedWidget & InheritedModel
7. ValueNotifier & ValueListenableBuilder
8. ChangeNotifier Basics
9. State Lifting Pattern
10. Hands-On Project: Todo App with ValueNotifier
11. Common Mistakes & How to Avoid Them
12. Day 11 Checklist

---

# 1. Why State Management Matters

## The State Problem
Every interactive app has state:
- Counter value
- Form input values
- Login status
- Shopping cart items
- Theme preference
- API response data

## Without Proper State Management
| Problem | Symptom |
|---|---|
| Passing data through 5+ constructors | "Prop drilling" nightmare |
| setState rebuilds entire screen | Janky 60fps drops |
| Business logic in UI widgets | Untestable spaghetti code |
| No single source of truth | Inconsistent data across screens |
| State lost on navigation | Form resets, cart empties |

## State Management Spectrum (Flutter)
```
Simple                          Complex
setState → ValueNotifier → Provider → Riverpod → BLoC
(Local)    (Lightweight)   (Popular)  (Modern)   (Enterprise)
```

---

# 2. Ephemeral vs App State

## Ephemeral State (Local/UI State)
- Lives in a single widget
- No need to share with other widgets
- Short-lived

**Examples:**
- Current page in PageView
- Animation progress
- Checkbox checked/unchecked
- TextField current text (with controller)

```dart
class CounterButton extends StatefulWidget {
  const CounterButton({super.key});

  @override
  State<CounterButton> createState() => _CounterButtonState();
}

class _CounterButtonState extends State<CounterButton> {
  int _count = 0; // Ephemeral state

  @override
  Widget build(BuildContext context) {
    return ElevatedButton(
      onPressed: () => setState(() => _count++),
      child: Text('Count: $_count'),
    );
  }
}
```

## App State (Shared/Global State)
- Shared across multiple widgets/screens
- Persists across navigation
- Often comes from outside (API, database)

**Examples:**
- User authentication status
- Shopping cart contents
- App theme preference
- Notification count
- Cached API data

```dart
// BAD: Prop drilling through 4 levels
ScreenA(user: user)
  → ScreenB(user: user)
    → ScreenC(user: user)
      → ScreenD(user: user) // Finally uses it!

// GOOD: Access anywhere in tree
final user = UserProvider.of(context).currentUser;
```

## The Golden Rule
> **Use setState for ephemeral state. Use InheritedWidget/Provider/Riverpod for app state.**

---

# 3. setState Deep Dive

## What Does setState Actually Do?
```dart
setState(() {
  _counter++;
});
```

1. Updates the variable (`_counter++`)
2. Marks the widget as "dirty" (needs rebuild)
3. Flutter schedules a rebuild
4. `build()` runs again with new values
5. Flutter compares old vs new widget tree (diffing)
6. Only changed parts update in the DOM/render tree

## setState Syntax Patterns
```dart
// Pattern 1: Inline (fine for simple cases)
setState(() => _count++);

// Pattern 2: Block body (better for multiple changes)
setState(() {
  _count++;
  _lastUpdated = DateTime.now();
});

// Pattern 3: Pre-calculate (most efficient)
final newCount = _count + 1;
setState(() => _count = newCount);
```

## setState Rebuild Scope
**Critical concept:** `setState` rebuilds the **current widget** and **all its descendants**.

```dart
class Parent extends StatefulWidget {
  @override
  State<Parent> createState() => _ParentState();
}

class _ParentState extends State<Parent> {
  int _counter = 0;

  @override
  Widget build(BuildContext context) {
    print('Parent rebuilt!'); // ← Rebuilds
    return Column(
      children: [
        Text('Counter: $_counter'),
        ChildA(), // ← Rebuilds (descendant)
        ChildB(), // ← Rebuilds (descendant)
        ChildC(), // ← Rebuilds (descendant)
      ],
    );
  }
}
```

## Optimizing Rebuilds with const
```dart
class _ParentState extends State<Parent> {
  int _counter = 0;

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        Text('Counter: $_counter'), // Must rebuild (uses state)
        const ChildA(), // ← Skips rebuild (const + no state change)
        const ChildB(), // ← Skips rebuild
        ChildC(count: _counter), // Must rebuild (receives new prop)
      ],
    );
  }
}
```

**Rule:** Use `const` constructors for widgets that don't depend on changing state.

---

# 4. When NOT to Use setState

## Anti-Pattern 1: Sharing State Across Screens
```dart
// WRONG — State lost when navigating!
class HomeScreen extends StatefulWidget {
  @override
  State<HomeScreen> createState() => _HomeScreenState();
}

class _HomeScreenState extends State<HomeScreen> {
  List<String> todos = []; // Lost on push to DetailScreen!
}
```

## Anti-Pattern 2: Deep Nesting with Callbacks
```dart
// WRONG — Callback hell
class Parent extends StatefulWidget {
  @override
  State<Parent> createState() => _ParentState();
}

class _ParentState extends State<Parent> {
  String _filter = '';

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Column(
        children: [
          SearchBar(onChanged: (v) => setState(() => _filter = v)),
          FilterChips(
            selected: _filter,
            onSelected: (v) => setState(() => _filter = v),
          ),
          TodoList(
            filter: _filter,
            onToggle: (id) => setState(() => /* update */),
            onDelete: (id) => setState(() => /* update */),
          ),
        ],
      ),
    );
  }
}
```

## Anti-Pattern 3: setState in onChanged for Every Keystroke
```dart
// WRONG — Rebuilds entire form on every keystroke
TextField(
  onChanged: (value) {
    setState(() => _searchText = value); // Expensive!
  },
)

// CORRECT — Use controller, no setState needed
TextField(controller: _searchController)
```

## Anti-Pattern 4: Business Logic in UI
```dart
// WRONG — Untestable, tightly coupled
setState(() {
  if (_balance >= amount && amount > 0) {
    _balance -= amount;
    _transactions.add(Transaction.withdraw(amount));
    _lastTransaction = DateTime.now();
  }
});

// CORRECT — Extract to model/service
final result = account.withdraw(amount);
if (result.isSuccess) {
  setState(() => _balance = account.balance);
}
```

## The setState Decision Tree
```
Does the state need to be shared?
├── NO → Is it simple UI state?
│   ├── YES → Use setState ✅
│   └── NO  → Use ValueNotifier ✅
└── YES → Does it need to persist?
    ├── NO  → Use Provider/Riverpod ✅
    └── YES → Use BLoC + Repository ✅
```

---

# 5. The Widget Tree & BuildContext

## BuildContext is Your Location in the Tree
```dart
@override
Widget build(BuildContext context) {
  // context = "Where am I in the widget tree?"
  final theme = Theme.of(context); // Walks UP the tree to find Theme
  return Container();
}
```

## Finding Ancestors with context
```dart
// Find nearest Theme
Theme.of(context)

// Find nearest Navigator
Navigator.of(context)

// Find nearest Scaffold
Scaffold.of(context)

// Find nearest MediaQuery
MediaQuery.of(context)

// Custom: Find nearest InheritedWidget
MyProvider.of(context)
```

## The "of()" Pattern
All these use `BuildContext` to walk up the tree and find the nearest ancestor of a specific type. This is the foundation of InheritedWidget and all state management solutions.

---

# 6. InheritedWidget & InheritedModel

## What is InheritedWidget?
An `InheritedWidget` is a special widget that efficiently propagates information down the tree. Descendants can access it via `context.dependOnInheritedWidgetOfExactType()`.

## Why Use InheritedWidget?
- **Efficient:** Only rebuilds widgets that actually depend on the data
- **Scoped:** Data lives in the widget tree, not global variables
- **Flutter-native:** No external packages needed

## Building a Custom InheritedWidget

### Step 1: Create the InheritedWidget
```dart
class UserInfo extends InheritedWidget {
  final String userName;
  final int userAge;
  final bool isPremium;

  const UserInfo({
    super.key,
    required this.userName,
    required this.userAge,
    required this.isPremium,
    required super.child,
  });

  // The magic: Flutter calls this when data changes
  @override
  bool updateShouldNotify(UserInfo oldWidget) {
    return oldWidget.userName != userName ||
           oldWidget.userAge != userAge ||
           oldWidget.isPremium != isPremium;
  }

  // Helper method for easy access
  static UserInfo? of(BuildContext context) {
    return context.dependOnInheritedWidgetOfExactType<UserInfo>();
  }
}
```

### Step 2: Place it High in the Tree
```dart
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return UserInfo(
      userName: 'Kimi',
      userAge: 25,
      isPremium: true,
      child: MaterialApp(
        home: const HomeScreen(),
      ),
    );
  }
}
```

### Step 3: Access Anywhere in the Tree
```dart
class ProfileScreen extends StatelessWidget {
  const ProfileScreen({super.key});

  @override
  Widget build(BuildContext context) {
    final userInfo = UserInfo.of(context)!;

    return Scaffold(
      appBar: AppBar(title: const Text('Profile')),
      body: Column(
        children: [
          Text('Name: ${userInfo.userName}'),
          Text('Age: ${userInfo.userAge}'),
          if (userInfo.isPremium)
            const Chip(label: Text('PREMIUM')),
        ],
      ),
    );
  }
}
```

## InheritedModel (Selective Rebuilds)
`InheritedModel` is an advanced version that lets widgets subscribe to only specific aspects of the data.

```dart
class AppConfig extends InheritedModel<String> {
  final String theme;
  final String language;
  final String fontSize;

  const AppConfig({
    super.key,
    required this.theme,
    required this.language,
    required this.fontSize,
    required super.child,
  });

  @override
  bool updateShouldNotify(AppConfig oldWidget) {
    return oldWidget.theme != theme ||
           oldWidget.language != language ||
           oldWidget.fontSize != fontSize;
  }

  @override
  bool updateShouldNotifyDependent(
    AppConfig oldWidget,
    Set<String> dependencies,
  ) {
    if (dependencies.contains('theme') && oldWidget.theme != theme) {
      return true;
    }
    if (dependencies.contains('language') && oldWidget.language != language) {
      return true;
    }
    return false;
  }

  static AppConfig? of(BuildContext context, String aspect) {
    return InheritedModel.inheritFrom<AppConfig>(context, aspect: aspect);
  }
}

// Usage: Only rebuilds when 'theme' changes
final theme = AppConfig.of(context, 'theme')!.theme;
```

---

# 7. ValueNotifier & ValueListenableBuilder

## What is ValueNotifier?
A `ValueNotifier` is a simple, lightweight observable object. When its value changes, it notifies listeners. Perfect for simple state that doesn't need a full state management package.

## Basic ValueNotifier Pattern
```dart
class CounterPage extends StatefulWidget {
  const CounterPage({super.key});

  @override
  State<CounterPage> createState() => _CounterPageState();
}

class _CounterPageState extends State<CounterPage> {
  final _counter = ValueNotifier<int>(0); // ← Observable

  @override
  void dispose() {
    _counter.dispose(); // ← ALWAYS dispose!
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('ValueNotifier Demo')),
      body: Center(
        // Only rebuilds this widget, not the whole screen!
        child: ValueListenableBuilder<int>(
          valueListenable: _counter,
          builder: (context, value, child) {
            return Text(
              'Count: $value',
              style: const TextStyle(fontSize: 48),
            );
          },
        ),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: () => _counter.value++, // ← Update value
        child: const Icon(Icons.add),
      ),
    );
  }
}
```

## ValueNotifier for Form Validation
```dart
class LoginForm extends StatefulWidget {
  const LoginForm({super.key});

  @override
  State<LoginForm> createState() => _LoginFormState();
}

class _LoginFormState extends State<LoginForm> {
  final _emailController = TextEditingController();
  final _passwordController = TextEditingController();
  final _isFormValid = ValueNotifier<bool>(false);

  @override
  void initState() {
    super.initState();
    _emailController.addListener(_validate);
    _passwordController.addListener(_validate);
  }

  void _validate() {
    final emailValid = _emailController.text.contains('@');
    final passwordValid = _passwordController.text.length >= 6;
    _isFormValid.value = emailValid && passwordValid;
  }

  @override
  void dispose() {
    _emailController.dispose();
    _passwordController.dispose();
    _isFormValid.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        TextField(controller: _emailController, decoration: const InputDecoration(labelText: 'Email')),
        TextField(controller: _passwordController, decoration: const InputDecoration(labelText: 'Password'), obscureText: true),
        ValueListenableBuilder<bool>(
          valueListenable: _isFormValid,
          builder: (context, isValid, child) {
            return ElevatedButton(
              onPressed: isValid ? _submit : null,
              child: const Text('Login'),
            );
          },
        ),
      ],
    );
  }

  void _submit() {/* ... */}
}
```

## Multiple ValueNotifiers
```dart
class _FiltersState extends State<Filters> {
  final _category = ValueNotifier<String>('All');
  final _sortBy = ValueNotifier<String>('Date');
  final _isAscending = ValueNotifier<bool>(true);

  @override
  void dispose() {
    _category.dispose();
    _sortBy.dispose();
    _isAscending.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        ValueListenableBuilder<String>(
          valueListenable: _category,
          builder: (context, category, _) => DropdownButton(
            value: category,
            items: ['All', 'Work', 'Personal'].map((c) => DropdownMenuItem(value: c, child: Text(c))).toList(),
            onChanged: (v) => _category.value = v!,
          ),
        ),
        // ... other filters
      ],
    );
  }
}
```

---

# 8. ChangeNotifier Basics

## What is ChangeNotifier?
A more powerful observable class. You can notify listeners manually with `notifyListeners()`. This is the foundation of Provider and many state management solutions.

## Simple ChangeNotifier Example
```dart
import 'package:flutter/material.dart';

class CounterModel extends ChangeNotifier {
  int _count = 0;

  int get count => _count;

  void increment() {
    _count++;
    notifyListeners(); // ← Triggers rebuilds
  }

  void decrement() {
    _count--;
    notifyListeners();
  }

  void reset() {
    _count = 0;
    notifyListeners();
  }
}
```

## Using with AnimatedBuilder (or custom listener)
```dart
class CounterPage extends StatefulWidget {
  const CounterPage({super.key});

  @override
  State<CounterPage> createState() => _CounterPageState();
}

class _CounterPageState extends State<CounterPage> {
  final _counter = CounterModel();

  @override
  void initState() {
    super.initState();
    _counter.addListener(_onCounterChanged);
  }

  void _onCounterChanged() {
    setState(() {}); // Rebuild when model changes
  }

  @override
  void dispose() {
    _counter.removeListener(_onCounterChanged);
    _counter.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(child: Text('${_counter.count}')),
      floatingActionButton: FloatingActionButton(
        onPressed: _counter.increment,
        child: const Icon(Icons.add),
      ),
    );
  }
}
```

## ChangeNotifier with List Data
```dart
class TodoModel extends ChangeNotifier {
  final List<Todo> _todos = [];

  List<Todo> get todos => List.unmodifiable(_todos);
  List<Todo> get completedTodos => _todos.where((t) => t.isDone).toList();
  List<Todo> get pendingTodos => _todos.where((t) => !t.isDone).toList();
  int get todoCount => _todos.length;
  int get completedCount => completedTodos.length;

  void addTodo(String title) {
    _todos.add(Todo(id: DateTime.now().toString(), title: title));
    notifyListeners();
  }

  void toggleTodo(String id) {
    final todo = _todos.firstWhere((t) => t.id == id);
    todo.isDone = !todo.isDone;
    notifyListeners();
  }

  void deleteTodo(String id) {
    _todos.removeWhere((t) => t.id == id);
    notifyListeners();
  }
}
```

---

# 9. State Lifting Pattern

## What is Lifting State Up?
When multiple children need to share state, move the state to their **common ancestor**.

## Before (Broken)
```dart
class Parent extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Row(
      children: [
        CounterA(), // Has its own _count
        CounterB(), // Has its own _count — not shared!
      ],
    );
  }
}
```

## After (Lifted)
```dart
class Parent extends StatefulWidget {
  @override
  State<Parent> createState() => _ParentState();
}

class _ParentState extends State<Parent> {
  int _count = 0;

  void _increment() => setState(() => _count++);

  @override
  Widget build(BuildContext context) {
    return Row(
      children: [
        CounterDisplay(count: _count),
        CounterButton(onPressed: _increment),
      ],
    );
  }
}

class CounterDisplay extends StatelessWidget {
  final int count;
  const CounterDisplay({super.key, required this.count});

  @override
  Widget build(BuildContext context) {
    return Text('Count: $count');
  }
}

class CounterButton extends StatelessWidget {
  final VoidCallback onPressed;
  const CounterButton({super.key, required this.onPressed});

  @override
  Widget build(BuildContext context) {
    return ElevatedButton(onPressed: onPressed, child: const Text('+'));
  }
}
```

## State Lifting Decision Flow
```
Does Widget A need to affect Widget B?
├── NO → Keep state local in each widget
└── YES → Do they share a parent?
    ├── YES → Lift state to that parent
    └── NO → Lift state higher until common ancestor found
```

---

# 10. Hands-On Project: Todo App with ValueNotifier

## Project Overview
Build a fully functional Todo app using:
- ValueNotifier for individual todo items
- ChangeNotifier for the todo list
- InheritedWidget for app configuration
- Clean separation of UI and business logic
- Filter tabs (All / Pending / Completed)

## Complete Code

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const TodoApp());
}

// ============ MODELS ============
class Todo {
  final String id;
  String title;
  bool isDone;
  DateTime createdAt;

  Todo({
    required this.id,
    required this.title,
    this.isDone = false,
    required this.createdAt,
  });
}

// ============ APP CONFIG (InheritedWidget) ============
class AppConfig extends InheritedWidget {
  final String appName;
  final bool showCompletedCount;

  const AppConfig({
    super.key,
    required this.appName,
    required this.showCompletedCount,
    required super.child,
  });

  @override
  bool updateShouldNotify(AppConfig oldWidget) {
    return oldWidget.appName != appName ||
           oldWidget.showCompletedCount != showCompletedCount;
  }

  static AppConfig of(BuildContext context) {
    return context.dependOnInheritedWidgetOfExactType<AppConfig>()!;
  }
}

// ============ TODO SERVICE (ChangeNotifier) ============
class TodoService extends ChangeNotifier {
  final List<Todo> _todos = [];

  List<Todo> get todos => List.unmodifiable(_todos);

  List<Todo> getByFilter(String filter) {
    switch (filter) {
      case 'pending':
        return _todos.where((t) => !t.isDone).toList();
      case 'completed':
        return _todos.where((t) => t.isDone).toList();
      default:
        return List.unmodifiable(_todos);
    }
  }

  int get completedCount => _todos.where((t) => t.isDone).length;
  int get pendingCount => _todos.where((t) => !t.isDone).length;

  void addTodo(String title) {
    _todos.add(Todo(
      id: DateTime.now().millisecondsSinceEpoch.toString(),
      title: title,
      createdAt: DateTime.now(),
    ));
    notifyListeners();
  }

  void toggleTodo(String id) {
    final todo = _todos.firstWhere((t) => t.id == id);
    todo.isDone = !todo.isDone;
    notifyListeners();
  }

  void deleteTodo(String id) {
    _todos.removeWhere((t) => t.id == id);
    notifyListeners();
  }

  void editTodo(String id, String newTitle) {
    final todo = _todos.firstWhere((t) => t.id == id);
    todo.title = newTitle;
    notifyListeners();
  }
}

// ============ APP ============
class TodoApp extends StatelessWidget {
  const TodoApp({super.key});

  @override
  Widget build(BuildContext context) {
    return AppConfig(
      appName: 'TaskMaster',
      showCompletedCount: true,
      child: MaterialApp(
        title: 'TaskMaster',
        debugShowCheckedModeBanner: false,
        theme: ThemeData(
          useMaterial3: true,
          colorScheme: ColorScheme.fromSeed(seedColor: Colors.teal),
        ),
        home: const TodoHomeScreen(),
      ),
    );
  }
}

// ============ HOME SCREEN ============
class TodoHomeScreen extends StatefulWidget {
  const TodoHomeScreen({super.key});

  @override
  State<TodoHomeScreen> createState() => _TodoHomeScreenState();
}

class _TodoHomeScreenState extends State<TodoHomeScreen> {
  final _todoService = TodoService();
  final _textController = TextEditingController();
  final _filterNotifier = ValueNotifier<String>('all');

  @override
  void dispose() {
    _todoService.dispose();
    _textController.dispose();
    _filterNotifier.dispose();
    super.dispose();
  }

  @override
  Widget build(BuildContext context) {
    final appConfig = AppConfig.of(context);

    return Scaffold(
      appBar: AppBar(
        title: Text(appConfig.appName),
        centerTitle: true,
        actions: [
          if (appConfig.showCompletedCount)
            ValueListenableBuilder<String>(
              valueListenable: _filterNotifier,
              builder: (context, filter, _) {
                return AnimatedBuilder(
                  animation: _todoService,
                  builder: (context, _) {
                    return Padding(
                      padding: const EdgeInsets.only(right: 16),
                      child: Chip(
                        label: Text('${_todoService.completedCount} done'),
                        backgroundColor: Colors.green.shade100,
                      ),
                    );
                  },
                );
              },
            ),
        ],
      ),
      body: Column(
        children: [
          // Input Field
          Padding(
            padding: const EdgeInsets.all(16),
            child: Row(
              children: [
                Expanded(
                  child: TextField(
                    controller: _textController,
                    decoration: InputDecoration(
                      hintText: 'Add a new task...',
                      filled: true,
                      border: OutlineInputBorder(
                        borderRadius: BorderRadius.circular(12),
                        borderSide: BorderSide.none,
                      ),
                      contentPadding: const EdgeInsets.symmetric(horizontal: 16, vertical: 14),
                    ),
                    onSubmitted: (value) => _addTodo(),
                  ),
                ),
                const SizedBox(width: 12),
                FloatingActionButton.small(
                  onPressed: _addTodo,
                  child: const Icon(Icons.add),
                ),
              ],
            ),
          ),

          // Filter Tabs
          ValueListenableBuilder<String>(
            valueListenable: _filterNotifier,
            builder: (context, selectedFilter, _) {
              return Padding(
                padding: const EdgeInsets.symmetric(horizontal: 16),
                child: Row(
                  children: [
                    _FilterChip(
                      label: 'All',
                      count: _todoService.todos.length,
                      isSelected: selectedFilter == 'all',
                      onSelected: () => _filterNotifier.value = 'all',
                    ),
                    const SizedBox(width: 8),
                    _FilterChip(
                      label: 'Pending',
                      count: _todoService.pendingCount,
                      isSelected: selectedFilter == 'pending',
                      onSelected: () => _filterNotifier.value = 'pending',
                    ),
                    const SizedBox(width: 8),
                    _FilterChip(
                      label: 'Completed',
                      count: _todoService.completedCount,
                      isSelected: selectedFilter == 'completed',
                      onSelected: () => _filterNotifier.value = 'completed',
                    ),
                  ],
                ),
              );
            },
          ),

          const SizedBox(height: 8),

          // Todo List
          Expanded(
            child: AnimatedBuilder(
              animation: _todoService,
              builder: (context, _) {
                return ValueListenableBuilder<String>(
                  valueListenable: _filterNotifier,
                  builder: (context, filter, _) {
                    final todos = _todoService.getByFilter(filter);

                    if (todos.isEmpty) {
                      return _EmptyState(filter: filter);
                    }

                    return ListView.builder(
                      padding: const EdgeInsets.symmetric(horizontal: 16),
                      itemCount: todos.length,
                      itemBuilder: (context, index) {
                        final todo = todos[index];
                        return _TodoItem(
                          todo: todo,
                          onToggle: () => _todoService.toggleTodo(todo.id),
                          onDelete: () => _todoService.deleteTodo(todo.id),
                          onEdit: (newTitle) => _todoService.editTodo(todo.id, newTitle),
                        );
                      },
                    );
                  },
                );
              },
            ),
          ),
        ],
      ),
    );
  }

  void _addTodo() {
    final text = _textController.text.trim();
    if (text.isNotEmpty) {
      _todoService.addTodo(text);
      _textController.clear();
    }
  }
}

// ============ FILTER CHIP ============
class _FilterChip extends StatelessWidget {
  final String label;
  final int count;
  final bool isSelected;
  final VoidCallback onSelected;

  const _FilterChip({
    required this.label,
    required this.count,
    required this.isSelected,
    required this.onSelected,
  });

  @override
  Widget build(BuildContext context) {
    final colorScheme = Theme.of(context).colorScheme;

    return ActionChip(
      label: Text('$label ($count)'),
      backgroundColor: isSelected ? colorScheme.primaryContainer : null,
      labelStyle: TextStyle(
        color: isSelected ? colorScheme.primary : null,
        fontWeight: isSelected ? FontWeight.bold : null,
      ),
      onPressed: onSelected,
    );
  }
}

// ============ TODO ITEM ============
class _TodoItem extends StatelessWidget {
  final Todo todo;
  final VoidCallback onToggle;
  final VoidCallback onDelete;
  final ValueChanged<String> onEdit;

  const _TodoItem({
    required this.todo,
    required this.onToggle,
    required this.onDelete,
    required this.onEdit,
  });

  @override
  Widget build(BuildContext context) {
    return Dismissible(
      key: Key(todo.id),
      direction: DismissDirection.endToStart,
      background: Container(
        alignment: Alignment.centerRight,
        padding: const EdgeInsets.only(right: 20),
        color: Colors.red,
        child: const Icon(Icons.delete, color: Colors.white),
      ),
      onDismissed: (_) => onDelete(),
      child: Card(
        margin: const EdgeInsets.only(bottom: 8),
        child: ListTile(
          leading: Checkbox(
            value: todo.isDone,
            onChanged: (_) => onToggle(),
          ),
          title: Text(
            todo.title,
            style: TextStyle(
              decoration: todo.isDone ? TextDecoration.lineThrough : null,
              color: todo.isDone ? Colors.grey : null,
            ),
          ),
          subtitle: Text(
            '${todo.createdAt.day}/${todo.createdAt.month}/${todo.createdAt.year}',
            style: const TextStyle(fontSize: 12),
          ),
          trailing: Row(
            mainAxisSize: MainAxisSize.min,
            children: [
              IconButton(
                icon: const Icon(Icons.edit, size: 20),
                onPressed: () => _showEditDialog(context),
              ),
              IconButton(
                icon: const Icon(Icons.delete_outline, size: 20, color: Colors.red),
                onPressed: onDelete,
              ),
            ],
          ),
        ),
      ),
    );
  }

  void _showEditDialog(BuildContext context) {
    final controller = TextEditingController(text: todo.title);
    showDialog(
      context: context,
      builder: (context) => AlertDialog(
        title: const Text('Edit Task'),
        content: TextField(
          controller: controller,
          decoration: const InputDecoration(labelText: 'Task name'),
        ),
        actions: [
          TextButton(
            onPressed: () => Navigator.pop(context),
            child: const Text('Cancel'),
          ),
          TextButton(
            onPressed: () {
              onEdit(controller.text.trim());
              Navigator.pop(context);
            },
            child: const Text('Save'),
          ),
        ],
      ),
    );
  }
}

// ============ EMPTY STATE ============
class _EmptyState extends StatelessWidget {
  final String filter;
  const _EmptyState({required this.filter});

  @override
  Widget build(BuildContext context) {
    String message;
    IconData icon;

    switch (filter) {
      case 'pending':
        message = 'No pending tasks!';
        icon = Icons.check_circle;
        break;
      case 'completed':
        message = 'No completed tasks yet';
        icon = Icons.hourglass_empty;
        break;
      default:
        message = 'No tasks yet. Add one above!';
        icon = Icons.note_add;
    }

    return Center(
      child: Column(
        mainAxisAlignment: MainAxisAlignment.center,
        children: [
          Icon(icon, size: 64, color: Colors.grey.shade400),
          const SizedBox(height: 16),
          Text(
            message,
            style: TextStyle(fontSize: 16, color: Colors.grey.shade600),
          ),
        ],
      ),
    );
  }
}
```

---

# 11. Common Mistakes & How to Avoid Them

## Mistake 1: Forgetting to Dispose Notifiers
```dart
// WRONG — Memory leak!
class _MyState extends State<MyWidget> {
  final _notifier = ValueNotifier<int>(0);
  // Never disposed!

// CORRECT
@override
void dispose() {
  _notifier.dispose();
  super.dispose();
}
```

## Mistake 2: Calling setState After dispose()
```dart
// WRONG — Crash!
Future.delayed(Duration(seconds: 2), () {
  setState(() => _data = result); // Widget might be disposed!
});

// CORRECT
Future.delayed(Duration(seconds: 2), () {
  if (mounted) {
    setState(() => _data = result);
  }
});
```

## Mistake 3: setState in Build Method
```dart
// WRONG — Infinite loop!
@override
Widget build(BuildContext context) {
  setState(() => _count++); // ← NEVER do this!
  return Text('$_count');
}
```

## Mistake 4: Rebuilding Everything with setState
```dart
// WRONG — Rebuilds entire screen for a small change
setState(() => _isLoading = true); // Rebuilds AppBar, Body, FAB...

// CORRECT — Use ValueListenableBuilder for localized rebuilds
ValueListenableBuilder<bool>(
  valueListenable: _isLoading,
  builder: (context, loading, _) {
    return loading ? CircularProgressIndicator() : Content();
  },
)
```

## Mistake 5: Business Logic in Widgets
```dart
// WRONG — Can't test, tightly coupled
setState(() {
  _discount = _total * 0.15;
  _tax = (_total - _discount) * 0.08;
  _finalTotal = _total - _discount + _tax;
});

// CORRECT — Extract to model
setState(() => _invoice.calculateTotals());
```

## Mistake 6: Not Using List.unmodifiable
```dart
// WRONG — External code can mutate internal state
List<Todo> get todos => _todos; // Caller can .add() directly!

// CORRECT — Return unmodifiable view
List<Todo> get todos => List.unmodifiable(_todos);
```

## Mistake 7: Multiple setState Calls in Sequence
```dart
// WRONG — Triggers multiple rebuilds
setState(() => _step = 1);
setState(() => _isLoading = true);
setState(() => _data = fetchedData);

// CORRECT — Single setState with all changes
setState(() {
  _step = 1;
  _isLoading = true;
  _data = fetchedData;
});
```

---

# 12. Day 11 Checklist

Use this checklist to verify mastery:
- [ ] Understands difference between ephemeral state and app state
- [ ] Can identify when to use setState vs external state management
- [ ] Knows that setState rebuilds current widget + all descendants
- [ ] Can optimize rebuilds using `const` constructors
- [ ] Understands BuildContext and the "of()" pattern
- [ ] Can create a custom InheritedWidget
- [ ] Can access InheritedWidget data from descendant widgets
- [ ] Understands InheritedModel for selective rebuilds
- [ ] Can create and use ValueNotifier
- [ ] Can use ValueListenableBuilder for localized rebuilds
- [ ] Can create a ChangeNotifier with custom business logic
- [ ] Can add/remove listeners to ChangeNotifier safely
- [ ] Understands state lifting pattern
- [ ] Can lift state to a common ancestor widget
- [ ] Built the Todo App with ValueNotifier and ChangeNotifier
- [ ] App has add, toggle, delete, and edit functionality
- [ ] App uses filter tabs with ValueNotifier
- [ ] App uses InheritedWidget for app configuration
- [ ] Always disposes controllers and notifiers
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **Use setState only for ephemeral (local) UI state.** If state is shared, lift it up or use a state management solution.
2. **setState rebuilds the entire widget subtree.** Use `const`, `ValueListenableBuilder`, or `AnimatedBuilder` to limit rebuild scope.
3. **Always dispose ValueNotifiers, ChangeNotifiers, TextEditingControllers, and FocusNodes.** They cause memory leaks if not disposed.
4. **Use `List.unmodifiable()`** when exposing internal lists from your models. Prevents external mutation.
5. **Check `mounted` before calling setState after async operations.** The widget may have been disposed.
6. **Never call setState inside build().** It causes infinite loops.
7. **Lift state up to the lowest common ancestor** of all widgets that need to read or write that state.
8. **ValueNotifier is perfect for simple independent state** (checkboxes, counters, filters) without adding dependencies.
9. **ChangeNotifier is the foundation** for all advanced state management (Provider, Riverpod, BLoC all build on it).
10. **Separate business logic from UI.** Keep calculations, validation, and data transformation in models/services, not widgets.

---

# Extra Practice (Do These Tonight!)

1. **Counter with History:** Build a counter app that tracks every increment/decrement in a history list. Use ChangeNotifier for the history.
2. **Shopping Cart:** Create a product list and cart screen. Use InheritedWidget to share cart data across the app without prop drilling.
3. **Timer App:** Build a multi-timer app where each timer is a ValueNotifier. Parent shows total active timers using AnimatedBuilder.
4. **Form Wizard:** Create a 3-step form where each step's data is preserved. Use a single ChangeNotifier to hold all form data.
5. **Theme Switcher:** Build an app where each tab can have a different accent color. Use InheritedModel so only affected tabs rebuild.

---

**Congratulations!** You've completed Day 11. You now understand the fundamental state management patterns in Flutter: setState, InheritedWidget, ValueNotifier, and ChangeNotifier. These concepts are the foundation for every advanced state management solution you'll learn next.

**Next Up → Day 12: State Management — Provider**

---

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 11: State Management — setState & InheritedWidget — Complete Deep Dive*




# Day 12: State Management — Provider
## Complete Deep Dive

**Goal:** Master the most popular state management solution in Flutter. Learn ChangeNotifierProvider, Consumer, Selector, MultiProvider, FutureProvider, StreamProvider, and dependency injection. Refactor the Day 11 Todo app with Provider and add categories, priorities, and filters.

---

# Table of Contents
1. Why Provider Matters
2. Provider Package Setup
3. ChangeNotifierProvider Deep Dive
4. Consumer vs context.watch/read
5. Selector for Granular Rebuilds
6. MultiProvider for Multiple Services
7. FutureProvider & StreamProvider
8. Dependency Injection with Provider
9. Provider Patterns & Best Practices
10. Hands-On Project: Todo App with Provider + Categories
11. Common Mistakes & How to Avoid Them
12. Day 12 Checklist

---

# 1. Why Provider Matters

## The Problem with Raw InheritedWidget
| Issue | Pain Point |
|---|---|
| Verbose boilerplate | 50+ lines for a simple data holder |
| Manual listener management | Easy to forget addListener/removeListener |
| No built-in dispose | Memory leaks if not handled carefully |
| Difficult to test | Tightly coupled to widget tree |

## Why Provider Won
- **Officially recommended** by the Flutter team (2019-2023)
- **Minimal boilerplate** compared to InheritedWidget
- **Compile-safe** (no string-based lookups)
- **Lazy initialization** — creates models only when needed
- **Automatic disposal** — cleans up when widget is removed
- **Easy testing** — inject mock models directly

## Provider Architecture
```
UI Layer (Widgets)
    ↑↓
Provider (Bridge)
    ↑↓
Business Logic (ChangeNotifier/Model)
    ↑↓
Data Layer (API/Database)
```

---

# 2. Provider Package Setup

## pubspec.yaml
```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^6.1.2
```

## Import
```dart
import 'package:provider/provider.dart';
```

## Provider Types Overview
| Provider Type | Use Case |
|---|---|
| `Provider` | Immutable objects, services, utilities |
| `ChangeNotifierProvider` | Mutable state with `notifyListeners()` |
| `ValueListenableProvider` | Wraps ValueNotifier automatically |
| `FutureProvider` | Async data that resolves once |
| `StreamProvider` | Continuous async data stream |
| `MultiProvider` | Combines multiple providers |

---

# 3. ChangeNotifierProvider Deep Dive

## Basic Setup
```dart
void main() {
  runApp(
    ChangeNotifierProvider(
      create: (context) => CounterModel(),
      child: const MyApp(),
    ),
  );
}
```

## The Model (ChangeNotifier)
```dart
class CounterModel extends ChangeNotifier {
  int _count = 0;

  int get count => _count;

  void increment() {
    _count++;
    notifyListeners();
  }

  void decrement() {
    _count--;
    notifyListeners();
  }
}
```

## Reading State in Widgets
```dart
class CounterScreen extends StatelessWidget {
  const CounterScreen({super.key});

  @override
  Widget build(BuildContext context) {
    // Rebuilds when model changes
    final count = context.watch<CounterModel>().count;

    return Scaffold(
      body: Center(child: Text('Count: $count')),
      floatingActionButton: FloatingActionButton(
        // Read once, no rebuild
        onPressed: () => context.read<CounterModel>().increment(),
        child: const Icon(Icons.add),
      ),
    );
  }
}
```

## context.watch vs context.read vs context.select
```dart
// WATCH — Rebuilds widget when ANY property changes
final model = context.watch<CounterModel>();
Text('${model.count}');

// READ — One-time read, NEVER rebuilds
final model = context.read<CounterModel>();
model.increment();

// SELECT — Rebuilds ONLY when selected property changes
final count = context.select<CounterModel, int>((m) => m.count);
Text('$count'); // Only rebuilds if count changes, not if other properties change
```

## Provider.of (Legacy but still valid)
```dart
// Equivalent to context.watch
final model = Provider.of<CounterModel>(context);

// Equivalent to context.read (listen: false)
final model = Provider.of<CounterModel>(context, listen: false);
```

---

# 4. Consumer vs context.watch/read

## Consumer Widget
Use `Consumer` when you want to limit rebuilds to a specific subtree.

```dart
class MyScreen extends StatelessWidget {
  const MyScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('Consumer Demo')),
      // This part doesn't rebuild when CounterModel changes
      body: Column(
        children: [
          const Text('Static header — never rebuilds'),
          // Only this Consumer rebuilds
          Consumer<CounterModel>(
            builder: (context, model, child) {
              return Text('Count: ${model.count}');
            },
          ),
          const Text('Static footer — never rebuilds'),
        ],
      ),
    );
  }
}
```

## Consumer with child optimization
```dart
Consumer<CounterModel>(
  builder: (context, model, child) {
    return Column(
      children: [
        Text('Count: ${model.count}'), // Rebuilds
        child!, // Does NOT rebuild — cached!
      ],
    );
  },
  child: const ExpensiveWidget(), // Built once, passed to builder
)
```

## When to Use What?
| Scenario | Use |
|---|---|
| Single value in small widget | `context.watch<T>()` |
| Action button (no rebuild needed) | `context.read<T>()` |
| Specific property only | `context.select<T, V>()` |
| Isolate rebuilds to subtree | `Consumer<T>` |
| Optimize with static child | `Consumer<T>` with `child` param |

---

# 5. Selector for Granular Rebuilds

## The Problem
```dart
class UserModel extends ChangeNotifier {
  String name = 'Kimi';
  int age = 25;
  String email = 'kimi@example.com';
  // ... 20 more fields
}

// WRONG — Rebuilds when ANY field changes, even if only using name
final user = context.watch<UserModel>();
Text(user.name);
```

## The Solution: Selector
```dart
// Only rebuilds when 'name' changes
Selector<UserModel, String>(
  selector: (context, model) => model.name,
  builder: (context, name, child) {
    return Text('Name: $name');
  },
)

// Only rebuilds when 'age' changes
Selector<UserModel, int>(
  selector: (context, model) => model.age,
  builder: (context, age, child) {
    return Text('Age: $age');
  },
)
```

## Selector with shouldRebuild
```dart
Selector<CartModel, double>(
  selector: (context, cart) => cart.totalPrice,
  shouldRebuild: (previous, next) => previous != next,
  builder: (context, total, child) {
    return Text('Total: $$total');
  },
)
```

---

# 6. MultiProvider for Multiple Services

## The Problem
```dart
// WRONG — Nested providers are ugly and hard to read
ChangeNotifierProvider(
  create: (_) => AuthService(),
  child: ChangeNotifierProvider(
    create: (_) => CartService(),
    child: ChangeNotifierProvider(
      create: (_) => ThemeService(),
      child: const MyApp(),
    ),
  ),
)
```

## The Solution: MultiProvider
```dart
void main() {
  runApp(
    MultiProvider(
      providers: [
        ChangeNotifierProvider(create: (_) => AuthService()),
        ChangeNotifierProvider(create: (_) => CartService()),
        ChangeNotifierProvider(create: (_) => ThemeService()),
        Provider(create: (_) => ApiClient()), // Immutable service
        Provider(create: (_) => AnalyticsService()),
      ],
      child: const MyApp(),
    ),
  );
}
```

## Accessing Multiple Providers
```dart
class DashboardScreen extends StatelessWidget {
  const DashboardScreen({super.key});

  @override
  Widget build(BuildContext context) {
    final auth = context.watch<AuthService>();
    final cart = context.watch<CartService>();
    final theme = context.watch<ThemeService>();
    final api = context.read<ApiClient>(); // No rebuild needed

    return Scaffold(
      appBar: AppBar(title: Text('Welcome, ${auth.userName}')),
      body: Text('Cart: ${cart.itemCount} items'),
    );
  }
}
```

---

# 7. FutureProvider & StreamProvider

## FutureProvider (One-time async data)
```dart
class UserProfileScreen extends StatelessWidget {
  const UserProfileScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return FutureProvider<User?>(
      create: (context) => context.read<ApiService>().fetchUser(),
      initialData: null,
      child: const UserProfileContent(),
    );
  }
}

class UserProfileContent extends StatelessWidget {
  const UserProfileContent({super.key});

  @override
  Widget build(BuildContext context) {
    final user = context.watch<User?>();

    if (user == null) {
      return const Center(child: CircularProgressIndicator());
    }

    return Text('Hello, ${user.name}');
  }
}
```

## StreamProvider (Real-time data)
```dart
class ChatScreen extends StatelessWidget {
  const ChatScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return StreamProvider<List<Message>>(
      create: (context) => context.read<ChatService>().messageStream(),
      initialData: const [],
      child: const ChatList(),
    );
  }
}

class ChatList extends StatelessWidget {
  const ChatList({super.key});

  @override
  Widget build(BuildContext context) {
    final messages = context.watch<List<Message>>();

    return ListView.builder(
      itemCount: messages.length,
      itemBuilder: (context, index) => MessageBubble(message: messages[index]),
    );
  }
}
```

---

# 8. Dependency Injection with Provider

## Injecting Services into Models
```dart
class TodoService extends ChangeNotifier {
  final ApiClient _api;
  final AnalyticsService _analytics;

  TodoService({required ApiClient api, required AnalyticsService analytics})
      : _api = api,
        _analytics = analytics;

  Future<void> loadTodos() async {
    _todos = await _api.fetchTodos();
    notifyListeners();
  }

  void addTodo(String title) {
    // ...
    _analytics.logEvent('todo_added');
  }
}
```

## Wiring Dependencies in MultiProvider
```dart
MultiProvider(
  providers: [
    Provider(create: (_) => ApiClient(baseUrl: 'https://api.example.com')),
    Provider(create: (_) => AnalyticsService()),
    ChangeNotifierProvider(
      create: (context) => TodoService(
        api: context.read<ApiClient>(),
        analytics: context.read<AnalyticsService>(),
      ),
    ),
  ],
  child: const MyApp(),
)
```

## ProxyProvider (Dependent Providers)
```dart
MultiProvider(
  providers: [
    Provider(create: (_) => AuthToken()),
    ProxyProvider<AuthToken, ApiClient>(
      update: (context, token, previous) =>
          ApiClient(authToken: token),
    ),
  ],
  child: const MyApp(),
)
```

---

# 9. Provider Patterns & Best Practices

## Pattern 1: Repository + Service + UI
```dart
// Data Layer
class TodoRepository {
  Future<List<Todo>> fetchTodos() async { /* API call */ }
}

// Business Logic Layer
class TodoService extends ChangeNotifier {
  final TodoRepository _repository;
  List<Todo> _todos = [];

  TodoService(this._repository);

  Future<void> load() async {
    _todos = await _repository.fetchTodos();
    notifyListeners();
  }
}

// UI Layer
class TodoScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    final todos = context.watch<TodoService>().todos;
    return ListView.builder(/* ... */);
  }
}
```

## Pattern 2: ViewModel per Screen
```dart
class LoginViewModel extends ChangeNotifier {
  bool _isLoading = false;
  String? _error;

  bool get isLoading => _isLoading;
  String? get error => _error;

  Future<void> login(String email, String password) async {
    _setLoading(true);
    try {
      await authApi.login(email, password);
      _error = null;
    } catch (e) {
      _error = e.toString();
    }
    _setLoading(false);
  }

  void _setLoading(bool value) {
    _isLoading = value;
    notifyListeners();
  }
}
```

## Pattern 3: Global vs Local Providers
```dart
// GLOBAL — Available everywhere (place above MaterialApp)
MultiProvider(
  providers: [
    ChangeNotifierProvider(create: (_) => AuthService()),
    ChangeNotifierProvider(create: (_) => ThemeService()),
  ],
  child: MaterialApp(...),
)

// LOCAL — Only available on specific route
Navigator.push(
  context,
  MaterialPageRoute(
    builder: (_) => ChangeNotifierProvider(
      create: (_) => CheckoutViewModel(),
      child: const CheckoutScreen(),
    ),
  ),
);
```

---

# 10. Hands-On Project: Todo App with Provider + Categories

## Project Overview
Refactor the Day 11 Todo app using Provider with:
- ChangeNotifierProvider for TodoService
- Categories (Work, Personal, Shopping, Health)
- Priority levels (Low, Medium, High)
- Filter by category and priority
- Sort by date or priority
- Statistics (total, completed, pending counts)

## Complete Code

```dart
import 'package:flutter/material.dart';
import 'package:provider/provider.dart';

void main() {
  runApp(
    MultiProvider(
      providers: [
        ChangeNotifierProvider(create: (_) => TodoService()),
        ChangeNotifierProvider(create: (_) => FilterService()),
      ],
      child: const TaskMasterApp(),
    ),
  );
}

// ============ ENUMS ============
enum TodoCategory { work, personal, shopping, health }
enum TodoPriority { low, medium, high }

// ============ MODELS ============
class Todo {
  final String id;
  String title;
  bool isDone;
  final TodoCategory category;
  final TodoPriority priority;
  final DateTime createdAt;

  Todo({
    required this.id,
    required this.title,
    this.isDone = false,
    required this.category,
    required this.priority,
    required this.createdAt,
  });
}

// ============ TODO SERVICE ============
class TodoService extends ChangeNotifier {
  final List<Todo> _todos = [
    Todo(id: '1', title: 'Complete Flutter project', category: TodoCategory.work, priority: TodoPriority.high, createdAt: DateTime.now().subtract(const Duration(days: 1))),
    Todo(id: '2', title: 'Buy groceries', category: TodoCategory.shopping, priority: TodoPriority.medium, createdAt: DateTime.now().subtract(const Duration(hours: 5))),
    Todo(id: '3', title: 'Morning jog', category: TodoCategory.health, priority: TodoPriority.low, createdAt: DateTime.now().subtract(const Duration(hours: 2))),
    Todo(id: '4', title: 'Call mom', category: TodoCategory.personal, priority: TodoPriority.high, createdAt: DateTime.now()),
  ];

  List<Todo> get todos => List.unmodifiable(_todos);

  List<Todo> getFiltered({
    TodoCategory? category,
    TodoPriority? priority,
    String? searchQuery,
    bool? showCompleted,
  }) {
    return _todos.where((todo) {
      if (category != null && todo.category != category) return false;
      if (priority != null && todo.priority != priority) return false;
      if (searchQuery != null && searchQuery.isNotEmpty) {
        if (!todo.title.toLowerCase().contains(searchQuery.toLowerCase())) return false;
      }
      if (showCompleted == false && todo.isDone) return false;
      return true;
    }).toList();
  }

  int get totalCount => _todos.length;
  int get completedCount => _todos.where((t) => t.isDone).length;
  int get pendingCount => _todos.where((t) => !t.isDone).length;
  int get highPriorityCount => _todos.where((t) => t.priority == TodoPriority.high && !t.isDone).length;

  void addTodo(String title, TodoCategory category, TodoPriority priority) {
    _todos.add(Todo(
      id: DateTime.now().millisecondsSinceEpoch.toString(),
      title: title,
      category: category,
      priority: priority,
      createdAt: DateTime.now(),
    ));
    notifyListeners();
  }

  void toggleTodo(String id) {
    final todo = _todos.firstWhere((t) => t.id == id);
    todo.isDone = !todo.isDone;
    notifyListeners();
  }

  void deleteTodo(String id) {
    _todos.removeWhere((t) => t.id == id);
    notifyListeners();
  }
}

// ============ FILTER SERVICE ============
class FilterService extends ChangeNotifier {
  TodoCategory? _selectedCategory;
  TodoPriority? _selectedPriority;
  String _searchQuery = '';
  bool _showCompleted = true;

  TodoCategory? get selectedCategory => _selectedCategory;
  TodoPriority? get selectedPriority => _selectedPriority;
  String get searchQuery => _searchQuery;
  bool get showCompleted => _showCompleted;

  void setCategory(TodoCategory? category) {
    _selectedCategory = category;
    notifyListeners();
  }

  void setPriority(TodoPriority? priority) {
    _selectedPriority = priority;
    notifyListeners();
  }

  void setSearchQuery(String query) {
    _searchQuery = query;
    notifyListeners();
  }

  void toggleShowCompleted() {
    _showCompleted = !_showCompleted;
    notifyListeners();
  }

  void clearFilters() {
    _selectedCategory = null;
    _selectedPriority = null;
    _searchQuery = '';
    _showCompleted = true;
    notifyListeners();
  }
}

// ============ APP ============
class TaskMasterApp extends StatelessWidget {
  const TaskMasterApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'TaskMaster Pro',
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        useMaterial3: true,
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepPurple),
      ),
      home: const TodoHomeScreen(),
    );
  }
}

// ============ HOME SCREEN ============
class TodoHomeScreen extends StatelessWidget {
  const TodoHomeScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('TaskMaster'),
        centerTitle: true,
        actions: [
          IconButton(
            icon: const Icon(Icons.filter_list),
            onPressed: () => _showFilterBottomSheet(context),
          ),
        ],
      ),
      body: Column(
        children: [
          const _StatsBar(),
          const _SearchBar(),
          const _CategoryFilterChips(),
          const _PriorityFilterChips(),
          Expanded(child: _TodoList()),
        ],
      ),
      floatingActionButton: FloatingActionButton.extended(
        onPressed: () => _showAddTodoDialog(context),
        icon: const Icon(Icons.add),
        label: const Text('New Task'),
      ),
    );
  }

  void _showAddTodoDialog(BuildContext context) {
    showModalBottomSheet(
      context: context,
      isScrollControlled: true,
      shape: const RoundedRectangleBorder(
        borderRadius: BorderRadius.vertical(top: Radius.circular(20)),
      ),
      builder: (_) => const AddTodoBottomSheet(),
    );
  }

  void _showFilterBottomSheet(BuildContext context) {
    showModalBottomSheet(
      context: context,
      builder: (_) => const FilterBottomSheet(),
    );
  }
}

// ============ STATS BAR ============
class _StatsBar extends StatelessWidget {
  const _StatsBar();

  @override
  Widget build(BuildContext context) {
    return Consumer<TodoService>(
      builder: (context, service, _) {
        return Container(
          padding: const EdgeInsets.symmetric(vertical: 12, horizontal: 16),
          child: Row(
            mainAxisAlignment: MainAxisAlignment.spaceAround,
            children: [
              _StatCard(label: 'Total', value: service.totalCount, color: Colors.blue),
              _StatCard(label: 'Pending', value: service.pendingCount, color: Colors.orange),
              _StatCard(label: 'Done', value: service.completedCount, color: Colors.green),
              _StatCard(label: 'Urgent', value: service.highPriorityCount, color: Colors.red),
            ],
          ),
        );
      },
    );
  }
}

class _StatCard extends StatelessWidget {
  final String label;
  final int value;
  final Color color;

  const _StatCard({required this.label, required this.value, required this.color});

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        Container(
          padding: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
          decoration: BoxDecoration(
            color: color.withOpacity(0.1),
            borderRadius: BorderRadius.circular(12),
          ),
          child: Text(
            '$value',
            style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold, color: color),
          ),
        ),
        const SizedBox(height: 4),
        Text(label, style: const TextStyle(fontSize: 12)),
      ],
    );
  }
}

// ============ SEARCH BAR ============
class _SearchBar extends StatelessWidget {
  const _SearchBar();

  @override
  Widget build(BuildContext context) {
    return Padding(
      padding: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
      child: TextField(
        decoration: InputDecoration(
          hintText: 'Search tasks...',
          prefixIcon: const Icon(Icons.search),
          filled: true,
          border: OutlineInputBorder(borderRadius: BorderRadius.circular(12), borderSide: BorderSide.none),
        ),
        onChanged: (value) => context.read<FilterService>().setSearchQuery(value),
      ),
    );
  }
}

// ============ CATEGORY CHIPS ============
class _CategoryFilterChips extends StatelessWidget {
  const _CategoryFilterChips();

  @override
  Widget build(BuildContext context) {
    final categories = TodoCategory.values;

    return Consumer<FilterService>(
      builder: (context, filter, _) {
        return SizedBox(
          height: 40,
          child: ListView(
            scrollDirection: Axis.horizontal,
            padding: const EdgeInsets.symmetric(horizontal: 16),
            children: [
              FilterChip(
                label: const Text('All'),
                selected: filter.selectedCategory == null,
                onSelected: (_) => filter.setCategory(null),
              ),
              ...categories.map((cat) => Padding(
                padding: const EdgeInsets.only(left: 8),
                child: FilterChip(
                  label: Text(cat.name.toUpperCase()),
                  selected: filter.selectedCategory == cat,
                  onSelected: (_) => filter.setCategory(cat),
                ),
              )),
            ],
          ),
        );
      },
    );
  }
}

// ============ PRIORITY CHIPS ============
class _PriorityFilterChips extends StatelessWidget {
  const _PriorityFilterChips();

  @override
  Widget build(BuildContext context) {
    final priorities = TodoPriority.values;

    return Consumer<FilterService>(
      builder: (context, filter, _) {
        return SizedBox(
          height: 40,
          child: ListView(
            scrollDirection: Axis.horizontal,
            padding: const EdgeInsets.symmetric(horizontal: 16),
            children: [
              ChoiceChip(
                label: const Text('All Priorities'),
                selected: filter.selectedPriority == null,
                onSelected: (_) => filter.setPriority(null),
              ),
              ...priorities.map((p) => Padding(
                padding: const EdgeInsets.only(left: 8),
                child: ChoiceChip(
                  label: Text(p.name),
                  selected: filter.selectedPriority == p,
                  onSelected: (_) => filter.setPriority(p),
                ),
              )),
            ],
          ),
        );
      },
    );
  }
}

// ============ TODO LIST ============
class _TodoList extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Consumer2<TodoService, FilterService>(
      builder: (context, todoService, filterService, _) {
        final todos = todoService.getFiltered(
          category: filterService.selectedCategory,
          priority: filterService.selectedPriority,
          searchQuery: filterService.searchQuery,
          showCompleted: filterService.showCompleted,
        );

        if (todos.isEmpty) {
          return const Center(child: Text('No tasks found'));
        }

        return ListView.builder(
          padding: const EdgeInsets.all(16),
          itemCount: todos.length,
          itemBuilder: (context, index) {
            final todo = todos[index];
            return _TodoCard(todo: todo);
          },
        );
      },
    );
  }
}

// ============ TODO CARD ============
class _TodoCard extends StatelessWidget {
  final Todo todo;
  const _TodoCard({required this.todo});

  Color _getPriorityColor() {
    switch (todo.priority) {
      case TodoPriority.high: return Colors.red;
      case TodoPriority.medium: return Colors.orange;
      case TodoPriority.low: return Colors.green;
    }
  }

  Color _getCategoryColor() {
    switch (todo.category) {
      case TodoCategory.work: return Colors.blue;
      case TodoCategory.personal: return Colors.purple;
      case TodoCategory.shopping: return Colors.teal;
      case TodoCategory.health: return Colors.pink;
    }
  }

  @override
  Widget build(BuildContext context) {
    return Dismissible(
      key: Key(todo.id),
      direction: DismissDirection.endToStart,
      background: Container(
        alignment: Alignment.centerRight,
        padding: const EdgeInsets.only(right: 20),
        color: Colors.red,
        child: const Icon(Icons.delete, color: Colors.white),
      ),
      onDismissed: (_) => context.read<TodoService>().deleteTodo(todo.id),
      child: Card(
        margin: const EdgeInsets.only(bottom: 10),
        child: ListTile(
          leading: Checkbox(
            value: todo.isDone,
            onChanged: (_) => context.read<TodoService>().toggleTodo(todo.id),
          ),
          title: Text(
            todo.title,
            style: TextStyle(
              decoration: todo.isDone ? TextDecoration.lineThrough : null,
              color: todo.isDone ? Colors.grey : null,
            ),
          ),
          subtitle: Row(
            children: [
              Chip(
                label: Text(todo.category.name, style: const TextStyle(fontSize: 10)),
                backgroundColor: _getCategoryColor().withOpacity(0.1),
                labelStyle: TextStyle(color: _getCategoryColor(), fontSize: 10),
                padding: EdgeInsets.zero,
                visualDensity: VisualDensity.compact,
              ),
              const SizedBox(width: 8),
              Container(
                padding: const EdgeInsets.symmetric(horizontal: 8, vertical: 2),
                decoration: BoxDecoration(
                  color: _getPriorityColor().withOpacity(0.1),
                  borderRadius: BorderRadius.circular(4),
                ),
                child: Text(
                  todo.priority.name,
                  style: TextStyle(color: _getPriorityColor(), fontSize: 10),
                ),
              ),
            ],
          ),
        ),
      ),
    );
  }
}

// ============ ADD TODO BOTTOM SHEET ============
class AddTodoBottomSheet extends StatefulWidget {
  const AddTodoBottomSheet({super.key});

  @override
  State<AddTodoBottomSheet> createState() => _AddTodoBottomSheetState();
}

class _AddTodoBottomSheetState extends State<AddTodoBottomSheet> {
  final _controller = TextEditingController();
  TodoCategory _category = TodoCategory.work;
  TodoPriority _priority = TodoPriority.medium;

  @override
  Widget build(BuildContext context) {
    return Padding(
      padding: EdgeInsets.only(
        bottom: MediaQuery.of(context).viewInsets.bottom,
        left: 16,
        right: 16,
        top: 16,
      ),
      child: Column(
        mainAxisSize: MainAxisSize.min,
        crossAxisAlignment: CrossAxisAlignment.stretch,
        children: [
          const Text('New Task', style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
          const SizedBox(height: 16),
          TextField(
            controller: _controller,
            decoration: const InputDecoration(
              hintText: 'What needs to be done?',
              border: OutlineInputBorder(),
            ),
            autofocus: true,
          ),
          const SizedBox(height: 16),
          const Text('Category', style: TextStyle(fontWeight: FontWeight.w600)),
          Wrap(
            spacing: 8,
            children: TodoCategory.values.map((cat) => ChoiceChip(
              label: Text(cat.name),
              selected: _category == cat,
              onSelected: (_) => setState(() => _category = cat),
            )).toList(),
          ),
          const SizedBox(height: 16),
          const Text('Priority', style: TextStyle(fontWeight: FontWeight.w600)),
          Wrap(
            spacing: 8,
            children: TodoPriority.values.map((p) => ChoiceChip(
              label: Text(p.name),
              selected: _priority == p,
              onSelected: (_) => setState(() => _priority = p),
            )).toList(),
          ),
          const SizedBox(height: 16),
          ElevatedButton(
            onPressed: () {
              final text = _controller.text.trim();
              if (text.isNotEmpty) {
                context.read<TodoService>().addTodo(text, _category, _priority);
                Navigator.pop(context);
              }
            },
            child: const Text('Add Task'),
          ),
          const SizedBox(height: 16),
        ],
      ),
    );
  }
}

// ============ FILTER BOTTOM SHEET ============
class FilterBottomSheet extends StatelessWidget {
  const FilterBottomSheet({super.key});

  @override
  Widget build(BuildContext context) {
    return Consumer<FilterService>(
      builder: (context, filter, _) {
        return Container(
          padding: const EdgeInsets.all(16),
          child: Column(
            mainAxisSize: MainAxisSize.min,
            crossAxisAlignment: CrossAxisAlignment.start,
            children: [
              const Text('Filters', style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
              const SizedBox(height: 16),
              SwitchListTile(
                title: const Text('Show Completed'),
                value: filter.showCompleted,
                onChanged: (_) => filter.toggleShowCompleted(),
              ),
              const SizedBox(height: 8),
              SizedBox(
                width: double.infinity,
                child: OutlinedButton(
                  onPressed: () {
                    filter.clearFilters();
                    Navigator.pop(context);
                  },
                  child: const Text('Clear All Filters'),
                ),
              ),
            ],
          ),
        );
      },
    );
  }
}
```

---

# 11. Common Mistakes & How to Avoid Them

## Mistake 1: Using context.watch in initState / didChangeDependencies
```dart
// WRONG — Can't use context.watch in initState
@override
void initState() {
  super.initState();
  final value = context.watch<MyModel>().value; // CRASH!
}

// CORRECT — Use context.read or Provider.of with listen: false
@override
void initState() {
  super.initState();
  final value = context.read<MyModel>().value; // OK
  // Or schedule after first frame
  WidgetsBinding.instance.addPostFrameCallback((_) {
    context.read<MyModel>().loadData();
  });
}
```

## Mistake 2: Not Using MultiProvider
```dart
// WRONG — Deep nesting, unreadable
ChangeNotifierProvider(
  create: (_) => A(),
  child: ChangeNotifierProvider(
    create: (_) => B(),
    child: ChangeNotifierProvider(
      create: (_) => C(),
      child: const App(),
    ),
  ),
)

// CORRECT — Flat, readable
MultiProvider(
  providers: [
    ChangeNotifierProvider(create: (_) => A()),
    ChangeNotifierProvider(create: (_) => B()),
    ChangeNotifierProvider(create: (_) => C()),
  ],
  child: const App(),
)
```

## Mistake 3: Rebuilding Everything with context.watch
```dart
// WRONG — Entire Scaffold rebuilds on every change
@override
Widget build(BuildContext context) {
  final model = context.watch<TodoService>(); // Rebuilds everything!
  return Scaffold(
    appBar: AppBar(title: const Text('Todos')),
    body: ListView(...),
  );
}

// CORRECT — Use Consumer for targeted rebuilds
@override
Widget build(BuildContext context) {
  return Scaffold(
    appBar: AppBar(title: const Text('Todos')),
    body: Consumer<TodoService>(
      builder: (context, model, _) => ListView(...),
    ),
  );
}
```

## Mistake 4: Forgetting to Dispose in create
```dart
// WRONG — Model never disposed
ChangeNotifierProvider(create: (_) => MyModel())

// CORRECT — Provider auto-disposes ChangeNotifiers by default
// But for custom cleanup:
class MyModel extends ChangeNotifier {
  final _streamSubscription = someStream.listen(...);

  @override
  void dispose() {
    _streamSubscription.cancel();
    super.dispose();
  }
}
```

## Mistake 5: Using Provider for Everything
```dart
// WRONG — Overkill for simple, local state
ChangeNotifierProvider(create: (_) => PageIndexNotifier())

// CORRECT — Use ValueNotifier or setState for local state
final _pageIndex = ValueNotifier<int>(0);
```

## Mistake 6: Not Handling null in FutureProvider
```dart
// WRONG — May crash if initialData is wrong type
FutureProvider<User>(
  create: (_) => api.fetchUser(),
  child: const ProfileScreen(),
)

// CORRECT — Use nullable type with loading state
FutureProvider<User?>(
  create: (_) => api.fetchUser(),
  initialData: null,
  child: const ProfileScreen(),
)
```

## Mistake 7: Calling notifyListeners During build()
```dart
// WRONG — Throws exception
@override
Widget build(BuildContext context) {
  final model = context.watch<MyModel>();
  if (model.shouldLoad) {
    model.load(); // Calls notifyListeners during build!
  }
  return Container();
}

// CORRECT — Use post-frame callback or initState
@override
void initState() {
  super.initState();
  WidgetsBinding.instance.addPostFrameCallback((_) {
    context.read<MyModel>().load();
  });
}
```

---

# 12. Day 12 Checklist

Use this checklist to verify mastery:
- [ ] Understands why Provider is preferred over raw InheritedWidget
- [ ] Can set up ChangeNotifierProvider in main()
- [ ] Can create a ChangeNotifier model with getters and business methods
- [ ] Knows the difference between context.watch, context.read, context.select
- [ ] Can use Consumer to limit rebuild scope
- [ ] Can use Consumer with child parameter for optimization
- [ ] Can use Selector for property-specific rebuilds
- [ ] Can set up MultiProvider with multiple services
- [ ] Can use FutureProvider for one-time async data
- [ ] Can use StreamProvider for real-time data streams
- [ ] Can inject dependencies using Provider + context.read
- [ ] Can use ProxyProvider for dependent services
- [ ] Understands Repository + Service + UI pattern
- [ ] Built the Todo App with Provider + Categories + Priorities
- [ ] App has filter by category, priority, and search
- [ ] App shows statistics (total, pending, done, urgent)
- [ ] App uses Consumer2 for combined state access
- [ ] Never uses context.watch in initState
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **Use ChangeNotifierProvider for mutable state**, Provider for immutable services.
2. **context.watch** rebuilds the widget when model changes. **context.read** reads once and never rebuilds.
3. **Use Selector** when you only need one property — prevents unnecessary rebuilds.
4. **Use Consumer** to isolate rebuilds to a specific subtree, especially with expensive widgets.
5. **Always use MultiProvider** when you have 2+ providers — flat is better than nested.
6. **Never use context.watch in initState** — use context.read or addPostFrameCallback.
7. **Separate business logic from UI** — keep models pure, widgets dumb.
8. **FutureProvider/StreamProvider** handle loading states automatically — no manual flag needed.
9. **Provider auto-disposes ChangeNotifiers** by default, but you must clean up custom resources.
10. **Don't use Provider for everything** — local UI state still belongs in setState or ValueNotifier.

---

# Extra Practice (Do These Tonight!)

1. **Shopping Cart with Provider:** Build a product catalog + cart app. Use Provider for cart state, Selector for cart total, and MultiProvider for auth + cart + catalog.
2. **Weather App:** Use FutureProvider to fetch weather data. Show loading, error, and success states automatically.
3. **Chat App:** Use StreamProvider for real-time messages. Combine with ChangeNotifier for user typing indicators.
4. **Multi-step Form:** Build a 3-step wizard where each step is a ChangeNotifier. Use ProxyProvider to pass data between steps.
5. **Theme + Auth + Settings:** Create an app with three independent ChangeNotifiers. Use MultiProvider and test that changes in one don't rebuild unrelated widgets.

---

**Congratulations!** You've completed Day 12. You now master Provider, the most popular state management solution in Flutter. You can build scalable apps with clean separation of concerns, efficient rebuilds, and proper dependency injection.

**Next Up → Day 13: State Management — Riverpod**

---

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 12: State Management — Provider — Complete Deep Dive*
# Day 13: State Management — Riverpod
## Complete Deep Dive

**Goal:** Learn the modern, compile-safe state management solution that is officially recommended for new Flutter projects in 2026. Master StateProvider, StateNotifierProvider, FutureProvider, StreamProvider, AsyncValue, code generation with @riverpod, and build a production-grade Weather App.

---

# Table of Contents
1. Why Riverpod Over Provider
2. Riverpod Package Setup
3. Provider Types in Riverpod
4. ref.watch, ref.read, ref.listen
5. StateProvider & StateNotifierProvider
6. FutureProvider & StreamProvider
7. AsyncValue Handling
8. Family Modifiers & AutoDispose
9. Riverpod Generator & @riverpod
10. Architecture Patterns with Riverpod
11. Hands-On Project: Weather App
12. Common Mistakes & How to Avoid Them
13. Day 13 Checklist

---

# 1. Why Riverpod Over Provider

## The Problems Provider Couldn't Solve
| Problem | Provider | Riverpod |
|---|---|---|
| Compile safety | Runtime exceptions on typos | Compile-time safe |
| Testing | Must wrap widget tree | Test providers in isolation |
| Global state pollution | Providers always alive | AutoDispose by default |
| Provider lookup | String-based, error-prone | Type-safe, direct reference |
| DevTools | Limited | Full state inspection |
| Code generation | Manual boilerplate | @riverpod generates everything |

## Why Riverpod Won in 2026
- **Created by Remi Rousselet** (same author as Provider)
- **Officially recommended** for all new Flutter projects
- **Compile-safe** — no more "Provider not found" crashes
- **AutoDispose by default** — memory efficient out of the box
- **Testable without BuildContext** — pure Dart testing
- **DevTools integration** — inspect state in real-time
- **Code generation** — write less boilerplate with `@riverpod`

## Riverpod vs Provider Mental Model
```
Provider:     InheritedWidget → context.watch/read → Widget rebuilds
Riverpod:     ProviderContainer → ref.watch/read → Widget rebuilds
```

---

# 2. Riverpod Package Setup

## pubspec.yaml
```yaml
dependencies:
  flutter:
    sdk: flutter
  flutter_riverpod: ^2.5.1
  riverpod_annotation: ^2.3.5

dev_dependencies:
  riverpod_generator: ^2.4.0
  build_runner: ^2.4.9
  custom_lint: ^0.6.4
  riverpod_lint: ^2.3.10
```

## Wrap App with ProviderScope
```dart
import 'package:flutter/material.dart';
import 'package:flutter_riverpod/flutter_riverpod.dart';

void main() {
  runApp(
    const ProviderScope(
      child: MyApp(),
    ),
  );
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Riverpod App',
      home: const HomeScreen(),
    );
  }
}
```

## Widget Types
| Widget | Use When |
|---|---|
| `ConsumerWidget` | Stateless widget that reads providers |
| `ConsumerStatefulWidget` | Stateful widget that reads providers |
| `StatelessWidget` | Doesn't need any provider |

---

# 3. Provider Types in Riverpod

## Core Provider Types
| Provider | Use Case | Mutable? |
|---|---|---|
| `Provider` | Immutable values, computed state, services | No |
| `StateProvider` | Simple mutable state (primitives, enums) | Yes |
| `StateNotifierProvider` | Complex mutable state with methods | Yes |
| `FutureProvider` | Async data that resolves once | Auto |
| `StreamProvider` | Continuous async data stream | Auto |
| `ChangeNotifierProvider` | Legacy Provider migration | Yes |
| `AsyncNotifierProvider` | Async operations with loading states | Yes |

## Simple Provider (Immutable)
```dart
// Define a provider
final greetingProvider = Provider<String>((ref) => 'Hello, Riverpod!');

// Read in widget
class GreetingText extends ConsumerWidget {
  const GreetingText({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final greeting = ref.watch(greetingProvider);
    return Text(greeting);
  }
}
```

## Provider with Dependencies
```dart
final nameProvider = Provider<String>((ref) => 'Kimi');

// Computed provider that depends on another
final welcomeMessageProvider = Provider<String>((ref) {
  final name = ref.watch(nameProvider);
  return 'Welcome back, $name!';
});
```

---

# 4. ref.watch, ref.read, ref.listen

## ref.watch (Subscribe & Rebuild)
```dart
class CounterDisplay extends ConsumerWidget {
  const CounterDisplay({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    // Rebuilds whenever counterProvider's state changes
    final count = ref.watch(counterProvider);
    return Text('Count: $count');
  }
}
```

## ref.read (One-time Read)
```dart
class CounterButton extends ConsumerWidget {
  const CounterButton({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    return ElevatedButton(
      // Read once, no subscription
      onPressed: () => ref.read(counterProvider.notifier).state++,
      child: const Text('Increment'),
    );
  }
}
```

## ref.listen (Side Effects)
```dart
class LoginScreen extends ConsumerWidget {
  const LoginScreen({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    // Listen for errors and show SnackBar
    ref.listen<AsyncValue<void>>(loginProvider, (previous, next) {
      next.whenOrNull(
        error: (error, _) {
          ScaffoldMessenger.of(context).showSnackBar(
            SnackBar(content: Text('Login failed: $error')),
          );
        },
        data: (_) {
          Navigator.pushReplacementNamed(context, '/home');
        },
      );
    });

    return const LoginForm();
  }
}
```

## When to Use What?
| Method | Use When |
|---|---|
| `ref.watch` | Displaying state that should trigger rebuilds |
| `ref.read` | Event handlers (onPressed, callbacks) |
| `ref.listen` | Side effects (navigation, SnackBar, analytics) |

---

# 5. StateProvider & StateNotifierProvider

## StateProvider (Simple State)
```dart
final counterProvider = StateProvider<int>((ref) => 0);

class CounterScreen extends ConsumerWidget {
  const CounterScreen({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final count = ref.watch(counterProvider);

    return Scaffold(
      body: Center(child: Text('$count')),
      floatingActionButton: FloatingActionButton(
        onPressed: () {
          // Update state
          ref.read(counterProvider.notifier).state++;
        },
        child: const Icon(Icons.add),
      ),
    );
  }
}
```

## StateNotifierProvider (Complex State)
```dart
class CounterState {
  final int count;
  final int maxCount;
  final bool isAtMax;

  CounterState({this.count = 0, this.maxCount = 10})
      : isAtMax = count >= maxCount;

  CounterState copyWith({int? count, int? maxCount}) {
    return CounterState(
      count: count ?? this.count,
      maxCount: maxCount ?? this.maxCount,
    );
  }
}

class CounterNotifier extends StateNotifier<CounterState> {
  CounterNotifier() : super(CounterState());

  void increment() {
    if (!state.isAtMax) {
      state = state.copyWith(count: state.count + 1);
    }
  }

  void decrement() {
    if (state.count > 0) {
      state = state.copyWith(count: state.count - 1);
    }
  }

  void reset() {
    state = CounterState();
  }
}

final counterNotifierProvider = StateNotifierProvider<CounterNotifier, CounterState>((ref) {
  return CounterNotifier();
});

// Usage
class CounterScreen extends ConsumerWidget {
  const CounterScreen({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final state = ref.watch(counterNotifierProvider);
    final notifier = ref.read(counterNotifierProvider.notifier);

    return Scaffold(
      body: Column(
        children: [
          Text('Count: ${state.count}'),
          if (state.isAtMax) const Text('Maximum reached!'),
        ],
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: state.isAtMax ? null : notifier.increment,
        child: const Icon(Icons.add),
      ),
    );
  }
}
```

---

# 6. FutureProvider & StreamProvider

## FutureProvider (HTTP/API Calls)
```dart
final weatherProvider = FutureProvider<Weather>((ref) async {
  final api = ref.read(weatherApiProvider);
  return await api.fetchCurrentWeather('London');
});

class WeatherScreen extends ConsumerWidget {
  const WeatherScreen({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final weatherAsync = ref.watch(weatherProvider);

    return weatherAsync.when(
      loading: () => const Center(child: CircularProgressIndicator()),
      error: (err, stack) => Center(child: Text('Error: $err')),
      data: (weather) => WeatherCard(weather: weather),
    );
  }
}
```

## StreamProvider (Real-time Data)
```dart
final messageStreamProvider = StreamProvider<List<Message>>((ref) {
  final chatService = ref.read(chatServiceProvider);
  return chatService.messageStream();
});

class ChatList extends ConsumerWidget {
  const ChatList({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final messagesAsync = ref.watch(messageStreamProvider);

    return messagesAsync.when(
      loading: () => const Center(child: CircularProgressIndicator()),
      error: (err, _) => Center(child: Text('Error: $err')),
      data: (messages) => ListView.builder(
        itemCount: messages.length,
        itemBuilder: (context, index) => MessageBubble(message: messages[index]),
      ),
    );
  }
}
```

---

# 7. AsyncValue Handling

## What is AsyncValue?
`AsyncValue` is Riverpod's unified type for async states. It replaces manual `isLoading`, `hasError`, `data` flags.

```dart
// Instead of this mess:
bool _isLoading = true;
String? _error;
Weather? _weather;

// Riverpod gives you:
AsyncValue<Weather> weatherAsync;
```

## AsyncValue States
```dart
AsyncValue<T> can be:
├── AsyncLoading()     // Initial loading state
├── AsyncData(T value) // Success with data
└── AsyncError(Object error, StackTrace stackTrace) // Error state
```

## Handling AsyncValue
```dart
// Method 1: .when() — handles all states
final asyncValue = ref.watch(weatherProvider);

return asyncValue.when(
  loading: () => const LoadingWidget(),
  error: (err, stack) => ErrorWidget(error: err),
  data: (weather) => WeatherDisplay(weather: weather),
);

// Method 2: .whenOrNull() — handle only specific states
return asyncValue.whenOrNull(
  data: (weather) => WeatherDisplay(weather: weather),
) ?? const LoadingWidget();

// Method 3: .valueOrNull — get data or null
final weather = asyncValue.valueOrNull;
if (weather != null) {
  return WeatherDisplay(weather: weather);
}

// Method 4: .hasValue, .hasError, .isLoading
if (asyncValue.isLoading) return const LoadingWidget();
if (asyncValue.hasError) return ErrorWidget(error: asyncValue.error!);
if (asyncValue.hasValue) return WeatherDisplay(weather: asyncValue.value!);
```

## AsyncValue with Refresh (Pull-to-Refresh)
```dart
class WeatherScreen extends ConsumerWidget {
  const WeatherScreen({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final weatherAsync = ref.watch(weatherProvider);

    return RefreshIndicator(
      onRefresh: () => ref.refresh(weatherProvider.future),
      child: weatherAsync.when(
        loading: () => const Center(child: CircularProgressIndicator()),
        error: (err, _) => Center(child: Text('Error: $err')),
        data: (weather) => ListView(
          children: [WeatherCard(weather: weather)],
        ),
      ),
    );
  }
}
```

---

# 8. Family Modifiers & AutoDispose

## Provider Family (Parameterized Providers)
```dart
// Create a provider that takes a parameter
final cityWeatherProvider = FutureProvider.family<Weather, String>((ref, city) async {
  final api = ref.read(weatherApiProvider);
  return await api.fetchWeather(city);
});

// Usage
class CityWeather extends ConsumerWidget {
  final String cityName;
  const CityWeather({super.key, required this.cityName});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    // Each city gets its own cached provider instance
    final weather = ref.watch(cityWeatherProvider(cityName));
    return weather.when(
      loading: () => const CircularProgressIndicator(),
      error: (err, _) => Text('Error: $err'),
      data: (w) => Text('${w.temperature}°C'),
    );
  }
}
```

## AutoDispose (Memory Management)
```dart
// AutoDispose by default in Riverpod 2.x
final searchResultsProvider = FutureProvider.autoDispose<List<Product>>((ref) async {
  // Automatically disposed when no widget is listening
  final query = ref.watch(searchQueryProvider);
  return await api.searchProducts(query);
});

// Keep alive for caching
final cachedUserProvider = FutureProvider<User>((ref) async {
  // This provider stays alive even if no listeners
  final link = ref.keepAlive();
  return await api.fetchUser();
});

// Dispose after timeout
final tempDataProvider = FutureProvider<String>((ref) async {
  final link = ref.keepAlive();
  // Dispose after 5 minutes of inactivity
  Timer(const Duration(minutes: 5), link.close);
  return await api.fetchTempData();
});
```

---

# 9. Riverpod Generator & @riverpod

## Why Code Generation?
- Less boilerplate
- Compile-safe provider names
- Automatic family support
- Better IDE autocomplete

## Setup
```yaml
dev_dependencies:
  riverpod_generator: ^2.4.0
  build_runner: ^2.4.9
```

Run generator:
```bash
dart run build_runner watch
```

## @riverpod Annotation
```dart
import 'package:riverpod_annotation/riverpod_annotation.dart';

part 'providers.g.dart'; // Generated file

// Simple provider
@riverpod
String greeting(GreetingRef ref) {
  return 'Hello from Riverpod Generator!';
}

// Generated provider name: greetingProvider

// Future provider
@riverpod
Future<Weather> currentWeather(CurrentWeatherRef ref, String city) async {
  final api = ref.read(weatherApiProvider);
  return await api.fetchWeather(city);
}

// Generated: currentWeatherProvider

// StateNotifier with @riverpod
@riverpod
class Counter extends _$Counter {
  @override
  int build() => 0;

  void increment() => state++;
  void decrement() => state--;
}

// Generated: counterProvider
// Usage: ref.watch(counterProvider), ref.read(counterProvider.notifier).increment()
```

## Generated File (providers.g.dart)
```dart
// AUTO-GENERATED — Do not edit manually
part of 'providers.dart';

String _$greetingHash() => r'abc123';

@ProviderFor(greeting)
final greetingProvider = AutoDisposeProvider<String>(
  greeting,
  name: r'greetingProvider',
  debugGetCreateSourceHash: _$greetingHash,
);
typedef GreetingRef = AutoDisposeProviderRef<String>;

// ... more generated code
```

## AsyncNotifier with @riverpod
```dart
@riverpod
class WeatherController extends _$WeatherController {
  @override
  Future<Weather> build(String city) async {
    final api = ref.read(weatherApiProvider);
    return await api.fetchWeather(city);
  }

  Future<void> refresh() async {
    state = const AsyncLoading();
    state = await AsyncValue.guard(() async {
      final api = ref.read(weatherApiProvider);
      return await api.fetchWeather(arg); // arg = city parameter
    });
  }
}

// Usage
class WeatherScreen extends ConsumerWidget {
  final String city;
  const WeatherScreen({super.key, required this.city});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final weather = ref.watch(weatherControllerProvider(city));

    return weather.when(
      loading: () => const LoadingWidget(),
      error: (err, _) => ErrorWidget(error: err),
      data: (w) => Column(
        children: [
          WeatherCard(weather: w),
          ElevatedButton(
            onPressed: () => ref.read(weatherControllerProvider(city).notifier).refresh(),
            child: const Text('Refresh'),
          ),
        ],
      ),
    );
  }
}
```

---

# 10. Architecture Patterns with Riverpod

## Pattern 1: Repository + Service + Controller
```dart
// Data Layer
class WeatherRepository {
  final Dio _dio;
  WeatherRepository(this._dio);

  Future<Weather> fetchWeather(String city) async {
    final response = await _dio.get('/weather?q=$city');
    return Weather.fromJson(response.data);
  }
}

// Service Layer (Business Logic)
class WeatherService {
  final WeatherRepository _repository;
  WeatherService(this._repository);

  Future<Weather> getWeather(String city) async {
    return await _repository.fetchWeather(city);
  }
}

// Controller Layer (State Management)
@riverpod
class WeatherController extends _$WeatherController {
  @override
  Future<Weather> build(String city) async {
    final service = ref.read(weatherServiceProvider);
    return await service.getWeather(city);
  }

  Future<void> refresh() async {
    state = const AsyncLoading();
    state = await AsyncValue.guard(() async {
      final service = ref.read(weatherServiceProvider);
      return await service.getWeather(arg);
    });
  }
}

// UI Layer
class WeatherScreen extends ConsumerWidget {
  final String city;
  const WeatherScreen({super.key, required this.city});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final weather = ref.watch(weatherControllerProvider(city));
    return weather.when(
      loading: () => const LoadingWidget(),
      error: (err, _) => ErrorWidget(error: err),
      data: (w) => WeatherDisplay(weather: w),
    );
  }
}
```

## Pattern 2: Dependency Injection
```dart
// Repository provider
final weatherRepositoryProvider = Provider<WeatherRepository>((ref) {
  return WeatherRepository(Dio());
});

// Service provider (depends on repository)
final weatherServiceProvider = Provider<WeatherService>((ref) {
  final repository = ref.watch(weatherRepositoryProvider);
  return WeatherService(repository);
});

// Override for testing
final container = ProviderContainer(
  overrides: [
    weatherRepositoryProvider.overrideWithValue(MockWeatherRepository()),
  ],
);
```

---

# 11. Hands-On Project: Weather App

## Project Overview
Build a complete Weather App using Riverpod with:
- OpenWeatherMap API (mock data for offline testing)
- Search for any city
- Current weather display with icons
- 5-day forecast
- Pull-to-refresh
- Error handling with retry
- Riverpod Generator (@riverpod)

## Complete Code

```dart
import 'package:flutter/material.dart';
import 'package:flutter_riverpod/flutter_riverpod.dart';

void main() {
  runApp(
    const ProviderScope(
      child: WeatherApp(),
    ),
  );
}

// ============ MODELS ============
class Weather {
  final String city;
  final double temperature;
  final String condition;
  final String iconCode;
  final double humidity;
  final double windSpeed;
  final List<ForecastDay> forecast;

  Weather({
    required this.city,
    required this.temperature,
    required this.condition,
    required this.iconCode,
    required this.humidity,
    required this.windSpeed,
    required this.forecast,
  });

  factory Weather.fromMock(String city) {
    final conditions = ['Sunny', 'Cloudy', 'Rainy', 'Stormy', 'Snowy'];
    final icons = ['01d', '02d', '10d', '11d', '13d'];
    final index = city.length % conditions.length;

    return Weather(
      city: city,
      temperature: 15 + (city.hashCode % 20).toDouble(),
      condition: conditions[index],
      iconCode: icons[index],
      humidity: 40 + (city.hashCode % 50).toDouble(),
      windSpeed: 5 + (city.hashCode % 25).toDouble(),
      forecast: List.generate(5, (i) => ForecastDay.mock(i)),
    );
  }
}

class ForecastDay {
  final String day;
  final double minTemp;
  final double maxTemp;
  final String condition;

  ForecastDay({
    required this.day,
    required this.minTemp,
    required this.maxTemp,
    required this.condition,
  });

  factory ForecastDay.mock(int offset) {
    final days = ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun'];
    final dayIndex = (DateTime.now().weekday - 1 + offset) % 7;
    return ForecastDay(
      day: days[dayIndex],
      minTemp: 10 + offset * 2.toDouble(),
      maxTemp: 20 + offset * 2.toDouble(),
      condition: ['Sunny', 'Cloudy', 'Rainy'][offset % 3],
    );
  }
}

// ============ PROVIDERS ============
final searchQueryProvider = StateProvider<String>((ref) => 'London');

final weatherProvider = FutureProvider.family<Weather, String>((ref, city) async {
  // Simulate API delay
  await Future.delayed(const Duration(seconds: 1));
  // In real app: return await WeatherApi().fetchWeather(city);
  return Weather.fromMock(city);
});

final currentWeatherProvider = Provider<AsyncValue<Weather>>((ref) {
  final city = ref.watch(searchQueryProvider);
  return ref.watch(weatherProvider(city));
});

// ============ APP ============
class WeatherApp extends StatelessWidget {
  const WeatherApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'WeatherPro',
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        useMaterial3: true,
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.blue),
      ),
      home: const WeatherHomeScreen(),
    );
  }
}

// ============ HOME SCREEN ============
class WeatherHomeScreen extends ConsumerWidget {
  const WeatherHomeScreen({super.key});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final weatherAsync = ref.watch(currentWeatherProvider);
    final city = ref.watch(searchQueryProvider);

    return Scaffold(
      body: RefreshIndicator(
        onRefresh: () async {
          ref.invalidate(weatherProvider(city));
        },
        child: CustomScrollView(
          slivers: [
            SliverAppBar(
              expandedHeight: 120,
              floating: true,
              pinned: true,
              flexibleSpace: FlexibleSpaceBar(
                title: const Text('WeatherPro'),
                background: Container(
                  decoration: BoxDecoration(
                    gradient: LinearGradient(
                      colors: [Colors.blue.shade400, Colors.blue.shade800],
                      begin: Alignment.topLeft,
                      end: Alignment.bottomRight,
                    ),
                  ),
                ),
              ),
            ),
            SliverToBoxAdapter(
              child: Padding(
                padding: const EdgeInsets.all(16),
                child: _SearchBar(),
              ),
            ),
            SliverToBoxAdapter(
              child: weatherAsync.when(
                loading: () => const SizedBox(
                  height: 400,
                  child: Center(child: CircularProgressIndicator()),
                ),
                error: (err, _) => _ErrorView(error: err.toString(), city: city),
                data: (weather) => _WeatherContent(weather: weather),
              ),
            ),
          ],
        ),
      ),
    );
  }
}

// ============ SEARCH BAR ============
class _SearchBar extends ConsumerWidget {
  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final controller = TextEditingController(
      text: ref.read(searchQueryProvider),
    );

    return TextField(
      controller: controller,
      decoration: InputDecoration(
        hintText: 'Search city...',
        prefixIcon: const Icon(Icons.search),
        suffixIcon: IconButton(
          icon: const Icon(Icons.clear),
          onPressed: () {
            controller.clear();
          },
        ),
        filled: true,
        border: OutlineInputBorder(
          borderRadius: BorderRadius.circular(16),
          borderSide: BorderSide.none,
        ),
      ),
      onSubmitted: (value) {
        if (value.trim().isNotEmpty) {
          ref.read(searchQueryProvider.notifier).state = value.trim();
        }
      },
    );
  }
}

// ============ WEATHER CONTENT ============
class _WeatherContent extends StatelessWidget {
  final Weather weather;
  const _WeatherContent({required this.weather});

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        _CurrentWeatherCard(weather: weather),
        const SizedBox(height: 24),
        _WeatherDetails(weather: weather),
        const SizedBox(height: 24),
        _ForecastSection(forecast: weather.forecast),
        const SizedBox(height: 32),
      ],
    );
  }
}

// ============ CURRENT WEATHER CARD ============
class _CurrentWeatherCard extends StatelessWidget {
  final Weather weather;
  const _CurrentWeatherCard({required this.weather});

  @override
  Widget build(BuildContext context) {
    return Card(
      elevation: 4,
      shape: RoundedRectangleBorder(borderRadius: BorderRadius.circular(24)),
      child: Container(
        width: double.infinity,
        padding: const EdgeInsets.all(32),
        decoration: BoxDecoration(
          borderRadius: BorderRadius.circular(24),
          gradient: LinearGradient(
            colors: [Colors.blue.shade400, Colors.blue.shade700],
            begin: Alignment.topLeft,
            end: Alignment.bottomRight,
          ),
        ),
        child: Column(
          children: [
            Text(
              weather.city,
              style: const TextStyle(
                fontSize: 28,
                fontWeight: FontWeight.bold,
                color: Colors.white,
              ),
            ),
            const SizedBox(height: 16),
            Icon(
              _getWeatherIcon(weather.condition),
              size: 80,
              color: Colors.white,
            ),
            const SizedBox(height: 16),
            Text(
              '${weather.temperature.round()}°C',
              style: const TextStyle(
                fontSize: 64,
                fontWeight: FontWeight.w200,
                color: Colors.white,
              ),
            ),
            const SizedBox(height: 8),
            Text(
              weather.condition,
              style: const TextStyle(
                fontSize: 20,
                color: Colors.white70,
              ),
            ),
          ],
        ),
      ),
    );
  }

  IconData _getWeatherIcon(String condition) {
    switch (condition) {
      case 'Sunny': return Icons.wb_sunny;
      case 'Cloudy': return Icons.wb_cloudy;
      case 'Rainy': return Icons.water_drop;
      case 'Stormy': return Icons.thunderstorm;
      case 'Snowy': return Icons.ac_unit;
      default: return Icons.wb_sunny;
    }
  }
}

// ============ WEATHER DETAILS ============
class _WeatherDetails extends StatelessWidget {
  final Weather weather;
  const _WeatherDetails({required this.weather});

  @override
  Widget build(BuildContext context) {
    return Row(
      mainAxisAlignment: MainAxisAlignment.spaceEvenly,
      children: [
        _DetailItem(
          icon: Icons.water_drop,
          label: 'Humidity',
          value: '${weather.humidity.round()}%',
        ),
        _DetailItem(
          icon: Icons.air,
          label: 'Wind',
          value: '${weather.windSpeed.round()} km/h',
        ),
        _DetailItem(
          icon: Icons.thermostat,
          label: 'Feels Like',
          value: '${(weather.temperature + 2).round()}°C',
        ),
      ],
    );
  }
}

class _DetailItem extends StatelessWidget {
  final IconData icon;
  final String label;
  final String value;

  const _DetailItem({required this.icon, required this.label, required this.value});

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        Icon(icon, color: Colors.blue),
        const SizedBox(height: 8),
        Text(value, style: const TextStyle(fontWeight: FontWeight.bold)),
        Text(label, style: TextStyle(color: Colors.grey.shade600, fontSize: 12)),
      ],
    );
  }
}

// ============ FORECAST SECTION ============
class _ForecastSection extends StatelessWidget {
  final List<ForecastDay> forecast;
  const _ForecastSection({required this.forecast});

  @override
  Widget build(BuildContext context) {
    return Column(
      crossAxisAlignment: CrossAxisAlignment.start,
      children: [
        const Padding(
          padding: EdgeInsets.symmetric(horizontal: 16),
          child: Text(
            '5-Day Forecast',
            style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold),
          ),
        ),
        const SizedBox(height: 12),
        SizedBox(
          height: 120,
          child: ListView.builder(
            scrollDirection: Axis.horizontal,
            padding: const EdgeInsets.symmetric(horizontal: 16),
            itemCount: forecast.length,
            itemBuilder: (context, index) {
              final day = forecast[index];
              return _ForecastCard(day: day);
            },
          ),
        ),
      ],
    );
  }
}

class _ForecastCard extends StatelessWidget {
  final ForecastDay day;
  const _ForecastCard({required this.day});

  @override
  Widget build(BuildContext context) {
    return Card(
      margin: const EdgeInsets.only(right: 12),
      child: Container(
        width: 80,
        padding: const EdgeInsets.all(12),
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text(day.day, style: const TextStyle(fontWeight: FontWeight.bold)),
            const SizedBox(height: 8),
            Icon(
              day.condition == 'Sunny' ? Icons.wb_sunny :
              day.condition == 'Cloudy' ? Icons.wb_cloudy : Icons.water_drop,
              color: Colors.orange,
            ),
            const SizedBox(height: 8),
            Text('${day.maxTemp.round()}°'),
            Text('${day.minTemp.round()}°', style: TextStyle(color: Colors.grey.shade600, fontSize: 12)),
          ],
        ),
      ),
    );
  }
}

// ============ ERROR VIEW ============
class _ErrorView extends StatelessWidget {
  final String error;
  final String city;
  const _ErrorView({required this.error, required this.city});

  @override
  Widget build(BuildContext context) {
    return Center(
      child: Padding(
        padding: const EdgeInsets.all(32),
        child: Column(
          children: [
            Icon(Icons.error_outline, size: 64, color: Colors.red.shade300),
            const SizedBox(height: 16),
            Text(
              'Failed to load weather for "$city"',
              textAlign: TextAlign.center,
              style: const TextStyle(fontSize: 18),
            ),
            const SizedBox(height: 8),
            Text(
              error,
              textAlign: TextAlign.center,
              style: TextStyle(color: Colors.grey.shade600),
            ),
            const SizedBox(height: 16),
            ElevatedButton.icon(
              onPressed: () {
                // Trigger rebuild by invalidating provider
                final container = ProviderScope.containerOf(context);
                container.invalidate(weatherProvider(city));
              },
              icon: const Icon(Icons.refresh),
              label: const Text('Retry'),
            ),
          ],
        ),
      ),
    );
  }
}
```

---

# 12. Common Mistakes & How to Avoid Them

## Mistake 1: Using ref.watch in initState
```dart
// WRONG — ConsumerWidget doesn't have initState, but in ConsumerStatefulWidget:
@override
void initState() {
  super.initState();
  final value = ref.watch(myProvider); // CRASH in initState!
}

// CORRECT — Use ref.read
@override
void initState() {
  super.initState();
  final value = ref.read(myProvider); // OK
}
```

## Mistake 2: Not Using ProviderScope
```dart
// WRONG — Riverpod providers won't work
void main() => runApp(const MyApp());

// CORRECT
void main() {
  runApp(const ProviderScope(child: MyApp()));
}
```

## Mistake 3: Forgetting .notifier for StateProvider
```dart
// WRONG — Can't modify state directly
ref.read(counterProvider).state++; // Doesn't work in Riverpod 2.x

// CORRECT
ref.read(counterProvider.notifier).state++;
```

## Mistake 4: Calling notifyListeners in StateNotifier
```dart
// WRONG — StateNotifier uses state =, not notifyListeners()
class MyNotifier extends StateNotifier<int> {
  void increment() {
    state++;
    notifyListeners(); // Don't do this!
  }
}

// CORRECT — Just assign to state
class MyNotifier extends StateNotifier<int> {
  MyNotifier() : super(0);
  void increment() => state++;
}
```

## Mistake 5: Not Handling AsyncValue Loading State
```dart
// WRONG — May show null or crash
final weather = ref.watch(weatherProvider);
return Text(weather.value!.temperature.toString()); // Crash on loading!

// CORRECT — Always handle all three states
return weather.when(
  loading: () => const CircularProgressIndicator(),
  error: (err, _) => Text('Error: $err'),
  data: (w) => Text('${w.temperature}°C'),
);
```

## Mistake 6: Using Global ProviderContainer
```dart
// WRONG — Tight coupling, hard to test
final container = ProviderContainer();
final value = container.read(myProvider);

// CORRECT — Use WidgetRef in widgets, or inject container
class MyWidget extends ConsumerWidget {
  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final value = ref.watch(myProvider); // Scoped to widget tree
    return Text(value);
  }
}
```

## Mistake 7: Not Invalidating Providers on Refresh
```dart
// WRONG — Old data persists
onRefresh: () => ref.read(weatherProvider); // Returns cached value

// CORRECT — Invalidate to force re-fetch
onRefresh: () {
  ref.invalidate(weatherProvider);
  return ref.refresh(weatherProvider.future);
}
```

---

# 13. Day 13 Checklist

Use this checklist to verify mastery:
- [ ] Understands why Riverpod is preferred over Provider in 2026
- [ ] Can set up ProviderScope in main()
- [ ] Knows the difference between Provider, StateProvider, StateNotifierProvider
- [ ] Can use ref.watch for reactive state
- [ ] Can use ref.read for one-time reads and event handlers
- [ ] Can use ref.listen for side effects (Snackbar, navigation)
- [ ] Can create a StateNotifier with immutable state
- [ ] Can use FutureProvider for async data
- [ ] Can use StreamProvider for real-time data
- [ ] Understands AsyncValue (loading, data, error states)
- [ ] Can handle AsyncValue with .when(), .whenOrNull(), .valueOrNull
- [ ] Can use Provider.family for parameterized providers
- [ ] Understands autoDispose and keepAlive
- [ ] Can set up Riverpod Generator with @riverpod
- [ ] Can generate providers with build_runner
- [ ] Built the Weather App with Riverpod
- [ ] App has search, current weather, forecast
- [ ] App handles loading, error, and success states
- [ ] App supports pull-to-refresh with invalidate/refresh
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **Riverpod is compile-safe** — no more "Provider not found" runtime crashes.
2. **Use ConsumerWidget instead of StatelessWidget** when you need to read providers.
3. **ref.watch** subscribes and rebuilds. **ref.read** reads once. **ref.listen** handles side effects.
4. **StateNotifier + immutable state** is the recommended pattern for complex state in Riverpod.
5. **AsyncValue handles all three states** (loading, data, error) in one type — no manual flags needed.
6. **Use .family** when a provider needs parameters (e.g., city name for weather).
7. **Providers are autoDispose by default** — memory efficient, but use `ref.keepAlive()` for caching.
8. **Use @riverpod code generation** for less boilerplate and better IDE support.
9. **Invalidate providers** to force refresh: `ref.invalidate(provider)` or `ref.refresh(provider.future)`.
10. **Never create global ProviderContainer** — always use ProviderScope and WidgetRef.

---

# Extra Practice (Do These Tonight!)

1. **News App with Riverpod:** Build a news reader using FutureProvider for API calls, StateProvider for category filters, and pull-to-refresh.
2. **Chat App:** Use StreamProvider for real-time messages and StateNotifier for message input state.
3. **E-commerce Cart:** Use StateNotifierProvider for cart logic with add/remove/quantity methods. Use Provider.family for product details.
4. **Multi-step Wizard:** Build a 3-step form where each step's data is preserved in a StateNotifier. Use AsyncNotifier for final submission.
5. **GitHub User Search:** Use FutureProvider.family to search users by username. Implement debounced search with StateProvider.

---

**Congratulations!** You've completed Day 13. You now master Riverpod, the modern, compile-safe state management solution officially recommended for Flutter in 2026. You can build scalable, testable apps with clean architecture and minimal boilerplate.

**Next Up → Day 14: State Management — BLoC Pattern**

---
# Day 14: State Management — BLoC Pattern
## Complete Deep Dive

**Goal:** Master the Business Logic Component (BLoC) pattern — the industry-standard, predictable, and testable state management architecture used by enterprise Flutter teams worldwide. Understand Events, States, Blocs, Cubits, HydratedBloc, and build a production-grade Authentication Flow & Task Manager.

---

# Table of Contents
1. Why BLoC Pattern?
2. BLoC Core Concepts: Events, States & Transitions
3. flutter_bloc Package Setup
4. Cubit: The Lightweight BLoC
5. Bloc: Full Event-Driven Architecture
6. BlocBuilder, BlocListener, BlocConsumer
7. Multi-BlocProvider & Dependency Injection
8. BlocObserver: Global Debugging & Analytics
9. HydratedBloc: Automatic State Persistence
10. Architecture Patterns with BLoC
11. Hands-On Project: Auth Flow & Task Manager
12. Common Mistakes & How to Avoid Them
13. Day 14 Checklist

---

# 1. Why BLoC Pattern?

## The Philosophy Behind BLoC
The BLoC (Business Logic Component) pattern was introduced by Google at Google I/O 2018 as a way to separate business logic from UI — making code **predictable, testable, and reusable**.

```
UI Layer ──► (Events) ──► BLoC ──► (States) ──► UI Layer
         Input              Process          Output
```

## BLoC vs Other State Management Solutions
| Feature | setState | Provider | Riverpod | BLoC Pattern |
|---|---|---|---|---|
| Separation of Concerns | Poor | Good | Excellent | Excellent |
| Testability | Hard | Medium | Easy | Very Easy |
| Predictability | Low | Medium | High | Very High |
| Learning Curve | Easy | Easy | Medium | Medium-Hard |
| Enterprise Scale | Not suitable | Good | Excellent | Industry Standard |
| Time-Travel Debugging | No | No | Limited | Yes |
| State Persistence | Manual | Manual | Manual | Built-in (HydratedBloc) |
| Code Generation | No | No | @riverpod | @freezed + equatable |

## When to Choose BLoC
- **Enterprise applications** with complex business rules
- **Teams** where multiple developers work on the same codebase
- **Apps requiring audit trails** — every state change is traceable via events
- **Apps needing state persistence** across app restarts
- **When testability is critical** — BLoCs are 100% pure Dart, no BuildContext needed

## Mental Model: The Vending Machine
```
User Action    = Insert Coin (Event)
Vending Machine = BLoC (Business Logic)
Product + Change = State
```
Just like a vending machine: you put in a specific input (Event), the machine processes it internally (Business Logic), and gives you a predictable output (State).

---

# 2. BLoC Core Concepts: Events, States & Transitions

## The Three Pillars
```dart
// 1. EVENT — What happened (User action, System notification)
abstract class CounterEvent {}
class CounterIncrementPressed extends CounterEvent {}
class CounterDecrementPressed extends CounterEvent {}

// 2. STATE — What the UI should look like
class CounterState {
  final int count;
  final bool isAtMax;

  CounterState({this.count = 0, this.maxCount = 10})
      : isAtMax = count >= maxCount;
}

// 3. BLOC — The processor that maps Events to States
class CounterBloc extends Bloc<CounterEvent, CounterState> {
  CounterBloc() : super(CounterState()) {
    on<CounterIncrementPressed>((event, emit) {
      if (!state.isAtMax) {
        emit(CounterState(count: state.count + 1));
      }
    });
  }
}
```

## Transition Lifecycle
Every state change in BLoC follows a strict, observable lifecycle:

```
Event Received
     │
     ▼
Current State ──► Event Handler ──► New State
     │                                  │
     ▼                                  ▼
Transition Logged              UI Rebuilds
```

## Equatable: Value Equality for States
Without `Equatable`, BLoC won't know if a state has actually changed.

```dart
import 'package:equatable/equatable.dart';

class CounterState extends Equatable {
  final int count;
  final bool isAtMax;

  const CounterState({this.count = 0, this.isAtMax = false});

  CounterState copyWith({int? count, bool? isAtMax}) {
    return CounterState(
      count: count ?? this.count,
      isAtMax: isAtMax ?? this.isAtMax,
    );
  }

  @override
  List<Object?> get props => [count, isAtMax]; // Equality check fields
}
```

## Freezed: Immutable State with Union Types (2026 Recommended)
```dart
import 'package:freezed_annotation/freezed_annotation.dart';

part 'auth_state.freezed.dart';

@freezed
class AuthState with _$AuthState {
  const factory AuthState.initial() = AuthInitial;
  const factory AuthState.loading() = AuthLoading;
  const factory AuthState.authenticated(User user) = Authenticated;
  const factory AuthState.unauthenticated() = Unauthenticated;
  const factory AuthState.error(String message) = AuthError;
}
```

---

# 3. flutter_bloc Package Setup

## pubspec.yaml
```yaml
dependencies:
  flutter:
    sdk: flutter
  flutter_bloc: ^8.1.6
  equatable: ^2.0.5
  hydrated_bloc: ^9.1.5
  freezed_annotation: ^2.4.1

dev_dependencies:
  build_runner: ^2.4.9
  freezed: ^2.5.2
  json_serializable: ^6.8.0
```

## Widget Types
| Widget | Use When |
|---|---|
| `BlocBuilder` | Rebuild UI when state changes |
| `BlocListener` | Execute side effects (navigation, SnackBar) |
| `BlocConsumer` | Both rebuild UI AND handle side effects |
| `BlocProvider` | Provide a BLoC to the widget tree |
| `MultiBlocProvider` | Provide multiple BLoCs at once |
| `RepositoryProvider` | Provide repositories (data layer) |

---

# 4. Cubit: The Lightweight BLoC

## What is Cubit?
Cubit is a simplified version of BLoC. Instead of processing **Events**, you directly call **methods** that emit states.

## Cubit vs Bloc
| Aspect | Cubit | Bloc |
|---|---|---|
| Input | Direct method calls | Events |
| Use Case | Simple state | Complex business logic |
| Audit Trail | Limited | Full event history |
| Testing | Unit test methods | Unit test event handlers |
| When to Use | Simple counters, toggles | Forms, authentication, complex flows |

## Simple Counter Cubit
```dart
import 'package:flutter_bloc/flutter_bloc.dart';
import 'package:equatable/equatable.dart';

// State
class CounterState extends Equatable {
  final int count;
  const CounterState({this.count = 0});

  CounterState copyWith({int? count}) => CounterState(count: count ?? this.count);

  @override
  List<Object?> get props => [count];
}

// Cubit
class CounterCubit extends Cubit<CounterState> {
  CounterCubit() : super(const CounterState());

  void increment() => emit(state.copyWith(count: state.count + 1));
  void decrement() => emit(state.copyWith(count: state.count - 1));
  void reset() => emit(const CounterState());
}

// UI
class CounterScreen extends StatelessWidget {
  const CounterScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return BlocProvider(
      create: (_) => CounterCubit(),
      child: const CounterView(),
    );
  }
}

class CounterView extends StatelessWidget {
  const CounterView({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: BlocBuilder<CounterCubit, CounterState>(
          builder: (context, state) {
            return Text('Count: ${state.count}', style: const TextStyle(fontSize: 24));
          },
        ),
      ),
      floatingActionButton: Column(
        mainAxisAlignment: MainAxisAlignment.end,
        children: [
          FloatingActionButton(
            onPressed: () => context.read<CounterCubit>().increment(),
            child: const Icon(Icons.add),
          ),
          const SizedBox(height: 8),
          FloatingActionButton(
            onPressed: () => context.read<CounterCubit>().decrement(),
            child: const Icon(Icons.remove),
          ),
        ],
      ),
    );
  }
}
```

---

# 5. Bloc: Full Event-Driven Architecture

## Authentication Bloc (Production Pattern)
```dart
// Events
abstract class AuthEvent extends Equatable {
  const AuthEvent();
  @override
  List<Object?> get props => [];
}

class AuthLoginRequested extends AuthEvent {
  final String email;
  final String password;
  const AuthLoginRequested({required this.email, required this.password});

  @override
  List<Object?> get props => [email, password];
}

class AuthLogoutRequested extends AuthEvent {}
class AuthCheckRequested extends AuthEvent {}

// States
abstract class AuthState extends Equatable {
  const AuthState();
  @override
  List<Object?> get props => [];
}

class AuthInitial extends AuthState {}
class AuthLoading extends AuthState {}
class AuthAuthenticated extends AuthState {
  final User user;
  const AuthAuthenticated(this.user);
  @override
  List<Object?> get props => [user];
}
class AuthUnauthenticated extends AuthState {}
class AuthFailure extends AuthState {
  final String message;
  const AuthFailure(this.message);
  @override
  List<Object?> get props => [message];
}

// Bloc
class AuthBloc extends Bloc<AuthEvent, AuthState> {
  final AuthRepository authRepository;

  AuthBloc({required this.authRepository}) : super(AuthInitial()) {
    on<AuthCheckRequested>(_onCheckRequested);
    on<AuthLoginRequested>(_onLoginRequested);
    on<AuthLogoutRequested>(_onLogoutRequested);
  }

  Future<void> _onCheckRequested(
    AuthCheckRequested event,
    Emitter<AuthState> emit,
  ) async {
    emit(AuthLoading());
    try {
      final user = await authRepository.getCurrentUser();
      if (user != null) {
        emit(AuthAuthenticated(user));
      } else {
        emit(AuthUnauthenticated());
      }
    } catch (e) {
      emit(AuthUnauthenticated());
    }
  }

  Future<void> _onLoginRequested(
    AuthLoginRequested event,
    Emitter<AuthState> emit,
  ) async {
    emit(AuthLoading());
    try {
      final user = await authRepository.login(
        email: event.email,
        password: event.password,
      );
      emit(AuthAuthenticated(user));
    } catch (e) {
      emit(AuthFailure(e.toString()));
    }
  }

  Future<void> _onLogoutRequested(
    AuthLogoutRequested event,
    Emitter<AuthState> emit,
  ) async {
    emit(AuthLoading());
    await authRepository.logout();
    emit(AuthUnauthenticated());
  }
}
```

## Event Transformers: Debounce, Throttle, Sequential
```dart
import 'package:bloc_concurrency/bloc_concurrency.dart';

class SearchBloc extends Bloc<SearchEvent, SearchState> {
  SearchBloc() : super(SearchInitial()) {
    on<SearchTextChanged>(
      _onSearchTextChanged,
      transformer: debounce(const Duration(milliseconds: 500)),
    );
    on<SearchSubmitted>(
      _onSearchSubmitted,
      transformer: sequential(), // Process one at a time
    );
  }
}
```

---

# 6. BlocBuilder, BlocListener, BlocConsumer

## BlocBuilder (Rebuild UI)
```dart
BlocBuilder<AuthBloc, AuthState>(
  buildWhen: (previous, current) {
    // Optional: Only rebuild when specific state changes
    return previous.runtimeType != current.runtimeType;
  },
  builder: (context, state) {
    if (state is AuthLoading) {
      return const CircularProgressIndicator();
    } else if (state is AuthAuthenticated) {
      return HomeScreen(user: state.user);
    } else if (state is AuthFailure) {
      return ErrorWidget(message: state.message);
    }
    return const LoginScreen();
  },
)
```

## BlocListener (Side Effects)
```dart
BlocListener<AuthBloc, AuthState>(
  listenWhen: (previous, current) => current is AuthFailure,
  listener: (context, state) {
    if (state is AuthFailure) {
      ScaffoldMessenger.of(context).showSnackBar(
        SnackBar(content: Text(state.message)),
      );
    } else if (state is AuthAuthenticated) {
      Navigator.of(context).pushReplacementNamed('/home');
    }
  },
  child: const LoginForm(),
)
```

## BlocConsumer (Builder + Listener Combined)
```dart
BlocConsumer<AuthBloc, AuthState>(
  listenWhen: (previous, current) => current is AuthFailure,
  listener: (context, state) {
    if (state is AuthFailure) {
      ScaffoldMessenger.of(context).showSnackBar(
        SnackBar(content: Text(state.message)),
      );
    }
  },
  builder: (context, state) {
    if (state is AuthLoading) {
      return const Center(child: CircularProgressIndicator());
    }
    return LoginForm(
      isLoading: state is AuthLoading,
      onSubmit: (email, password) {
        context.read<AuthBloc>().add(
          AuthLoginRequested(email: email, password: password),
        );
      },
    );
  },
)
```

---

# 7. Multi-BlocProvider & Dependency Injection

## Providing Multiple Blocs
```dart
class MyApp extends StatelessWidget {
  final AuthRepository authRepository;
  final TaskRepository taskRepository;

  const MyApp({
    super.key,
    required this.authRepository,
    required this.taskRepository,
  });

  @override
  Widget build(BuildContext context) {
    return MultiBlocProvider(
      providers: [
        BlocProvider(
          create: (_) => AuthBloc(authRepository: authRepository)..add(AuthCheckRequested()),
        ),
        BlocProvider(
          create: (_) => TaskBloc(taskRepository: taskRepository),
        ),
        BlocProvider(
          create: (_) => ThemeCubit(),
        ),
      ],
      child: MaterialApp(
        title: 'Task Manager Pro',
        home: const AuthWrapper(),
      ),
    );
  }
}
```

## RepositoryProvider (Clean Architecture)
```dart
MultiRepositoryProvider(
  providers: [
    RepositoryProvider(create: (_) => AuthRepository(api: Dio())),
    RepositoryProvider(create: (_) => TaskRepository(database: Hive.box('tasks'))),
  ],
  child: MultiBlocProvider(
    providers: [
      BlocProvider(
        create: (context) => AuthBloc(
          authRepository: context.read<AuthRepository>(),
        ),
      ),
    ],
    child: const MyApp(),
  ),
)
```

---

# 8. BlocObserver: Global Debugging & Analytics

## Custom BlocObserver
```dart
import 'package:flutter_bloc/flutter_bloc.dart';

class AppBlocObserver extends BlocObserver {
  @override
  void onCreate(BlocBase bloc) {
    super.onCreate(bloc);
    debugPrint('🟢 Created: ${bloc.runtimeType}');
  }

  @override
  void onEvent(Bloc bloc, Object? event) {
    super.onEvent(bloc, event);
    debugPrint('📤 Event: ${event.runtimeType} in ${bloc.runtimeType}');
  }

  @override
  void onChange(BlocBase bloc, Change change) {
    super.onChange(bloc, change);
    debugPrint('🔄 ${bloc.runtimeType}: ${change.currentState.runtimeType} → ${change.nextState.runtimeType}');
  }

  @override
  void onTransition(Bloc bloc, Transition transition) {
    super.onTransition(bloc, transition);
    debugPrint('⏭️  Transition: ${transition.currentState.runtimeType} → ${transition.nextState.runtimeType}');
  }

  @override
  void onError(BlocBase bloc, Object error, StackTrace stackTrace) {
    super.onError(bloc, error, stackTrace);
    debugPrint('❌ Error in ${bloc.runtimeType}: $error');
  }

  @override
  void onClose(BlocBase bloc) {
    super.onClose(bloc);
    debugPrint('🔴 Closed: ${bloc.runtimeType}');
  }
}
```

## Initialize in main.dart
```dart
void main() {
  Bloc.observer = AppBlocObserver();
  runApp(const MyApp());
}
```

## Analytics Integration
```dart
@override
void onTransition(Bloc bloc, Transition transition) {
  super.onTransition(bloc, transition);

  // Send to Firebase Analytics
  FirebaseAnalytics.instance.logEvent(
    name: 'bloc_transition',
    parameters: {
      'bloc': bloc.runtimeType.toString(),
      'from': transition.currentState.runtimeType.toString(),
      'to': transition.nextState.runtimeType.toString(),
    },
  );
}
```

---

# 9. HydratedBloc: Automatic State Persistence

## What is HydratedBloc?
HydratedBloc automatically persists and restores bloc states across app restarts. Perfect for:
- User authentication sessions
- Theme preferences
- Form drafts
- App settings

## Setup
```dart
import 'package:hydrated_bloc/hydrated_bloc.dart';
import 'package:path_provider/path_provider.dart';

void main() async {
  WidgetsFlutterBinding.ensureInitialized();

  HydratedBloc.storage = await HydratedStorage.build(
    storageDirectory: await getApplicationDocumentsDirectory(),
  );

  Bloc.observer = AppBlocObserver();
  runApp(const MyApp());
}
```

## HydratedCubit Example (Theme Persistence)
```dart
class ThemeCubit extends HydratedCubit<ThemeMode> {
  ThemeCubit() : super(ThemeMode.system);

  void toggleTheme() {
    emit(state == ThemeMode.light ? ThemeMode.dark : ThemeMode.light);
  }

  void setTheme(ThemeMode mode) => emit(mode);

  @override
  ThemeMode? fromJson(Map<String, dynamic> json) {
    final themeString = json['theme'] as String?;
    return ThemeMode.values.firstWhere(
      (e) => e.name == themeString,
      orElse: () => ThemeMode.system,
    );
  }

  @override
  Map<String, dynamic>? toJson(ThemeMode state) {
    return {'theme': state.name};
  }
}
```

## HydratedBloc Example (Auth Persistence)
```dart
class AuthBloc extends HydratedBloc<AuthEvent, AuthState> {
  AuthBloc({required this.authRepository}) : super(AuthInitial()) {
    on<AuthLoginRequested>(_onLoginRequested);
    on<AuthLogoutRequested>(_onLogoutRequested);
  }

  @override
  AuthState? fromJson(Map<String, dynamic> json) {
    try {
      final userJson = json['user'] as Map<String, dynamic>?;
      if (userJson != null) {
        return AuthAuthenticated(User.fromJson(userJson));
      }
      return AuthUnauthenticated();
    } catch (_) {
      return null;
    }
  }

  @override
  Map<String, dynamic>? toJson(AuthState state) {
    if (state is AuthAuthenticated) {
      return {'user': state.user.toJson()};
    }
    return null; // Don't persist unauthenticated state
  }
}
```

---

# 10. Architecture Patterns with BLoC

## Pattern 1: Feature-First Clean Architecture
```
lib/
├── main.dart
├── app.dart
├── config/
│   ├── routes.dart
│   └── theme.dart
├── features/
│   ├── auth/
│   │   ├── data/
│   │   │   ├── models/
│   │   │   │   └── user_model.dart
│   │   │   └── repositories/
│   │   │       └── auth_repository_impl.dart
│   │   ├── domain/
│   │   │   ├── entities/
│   │   │   │   └── user.dart
│   │   │   └── repositories/
│   │   │       └── auth_repository.dart
│   │   └── presentation/
│   │       ├── bloc/
│   │       │   ├── auth_bloc.dart
│   │       │   ├── auth_event.dart
│   │       │   └── auth_state.dart
│   │       ├── screens/
│   │       │   ├── login_screen.dart
│   │       │   └── register_screen.dart
│   │       └── widgets/
│   │           └── auth_button.dart
│   └── tasks/
│       ├── data/
│       ├── domain/
│       └── presentation/
└── core/
    ├── errors/
    ├── usecases/
    └── utils/
```

## Pattern 2: BLoC with Use Cases
```dart
// Domain Layer
abstract class LoginUseCase {
  Future<User> call(String email, String password);
}

// Data Layer
class LoginUseCaseImpl implements LoginUseCase {
  final AuthRepository repository;
  LoginUseCaseImpl(this.repository);

  @override
  Future<User> call(String email, String password) {
    return repository.login(email, password);
  }
}

// Presentation Layer
class AuthBloc extends Bloc<AuthEvent, AuthState> {
  final LoginUseCase loginUseCase;
  final LogoutUseCase logoutUseCase;

  AuthBloc({
    required this.loginUseCase,
    required this.logoutUseCase,
  }) : super(AuthInitial()) {
    on<AuthLoginRequested>(_onLoginRequested);
  }

  Future<void> _onLoginRequested(
    AuthLoginRequested event,
    Emitter<AuthState> emit,
  ) async {
    emit(AuthLoading());
    final result = await loginUseCase(event.email, event.password);
    result.fold(
      (failure) => emit(AuthFailure(failure.message)),
      (user) => emit(AuthAuthenticated(user)),
    );
  }
}
```

---

# 11. Hands-On Project: Auth Flow & Task Manager

## Project Overview
Build a complete **Task Manager Pro** app using BLoC with:
- Login/Logout authentication flow
- Task CRUD operations (Create, Read, Update, Delete)
- Task filtering (All, Active, Completed)
- Persistent theme with HydratedCubit
- Global error handling with BlocListener
- State restoration with HydratedBloc

## Complete Code

```dart
import 'package:flutter/material.dart';
import 'package:flutter_bloc/flutter_bloc.dart';
import 'package:equatable/equatable.dart';
import 'package:hydrated_bloc/hydrated_bloc.dart';
import 'package:path_provider/path_provider.dart';

void main() async {
  WidgetsFlutterBinding.ensureInitialized();
  HydratedBloc.storage = await HydratedStorage.build(
    storageDirectory: await getTemporaryDirectory(),
  );
  Bloc.observer = SimpleBlocObserver();
  runApp(const TaskManagerApp());
}

// ============ BLOC OBSERVER ============
class SimpleBlocObserver extends BlocObserver {
  @override
  void onChange(BlocBase bloc, Change change) {
    super.onChange(bloc, change);
    debugPrint('${bloc.runtimeType} ${change.currentState.runtimeType}→${change.nextState.runtimeType}');
  }
}

// ============ MODELS ============
class Task extends Equatable {
  final String id;
  final String title;
  final String description;
  final bool isCompleted;
  final DateTime createdAt;

  const Task({
    required this.id,
    required this.title,
    this.description = '',
    this.isCompleted = false,
    required this.createdAt,
  });

  Task copyWith({
    String? id,
    String? title,
    String? description,
    bool? isCompleted,
    DateTime? createdAt,
  }) {
    return Task(
      id: id ?? this.id,
      title: title ?? this.title,
      description: description ?? this.description,
      isCompleted: isCompleted ?? this.isCompleted,
      createdAt: createdAt ?? this.createdAt,
    );
  }

  @override
  List<Object?> get props => [id, title, description, isCompleted, createdAt];
}

// ============ AUTH BLOC ============
abstract class AuthEvent extends Equatable {
  const AuthEvent();
  @override
  List<Object?> get props => [];
}

class AuthLoginRequested extends AuthEvent {
  final String email;
  final String password;
  const AuthLoginRequested(this.email, this.password);
  @override
  List<Object?> get props => [email, password];
}

class AuthLogoutRequested extends AuthEvent {}

abstract class AuthState extends Equatable {
  const AuthState();
  @override
  List<Object?> get props => [];
}

class AuthInitial extends AuthState {}
class AuthLoading extends AuthState {}
class AuthAuthenticated extends AuthState {
  final String username;
  const AuthAuthenticated(this.username);
  @override
  List<Object?> get props => [username];
}
class AuthUnauthenticated extends AuthState {}
class AuthError extends AuthState {
  final String message;
  const AuthError(this.message);
  @override
  List<Object?> get props => [message];
}

class AuthBloc extends HydratedBloc<AuthEvent, AuthState> {
  AuthBloc() : super(AuthUnauthenticated()) {
    on<AuthLoginRequested>(_onLoginRequested);
    on<AuthLogoutRequested>(_onLogoutRequested);
  }

  Future<void> _onLoginRequested(
    AuthLoginRequested event,
    Emitter<AuthState> emit,
  ) async {
    emit(AuthLoading());
    await Future.delayed(const Duration(seconds: 1));

    if (event.email == 'admin@example.com' && event.password == 'password') {
      emit(const AuthAuthenticated('Admin User'));
    } else {
      emit(const AuthError('Invalid credentials. Try admin@example.com / password'));
    }
  }

  void _onLogoutRequested(AuthLogoutRequested event, Emitter<AuthState> emit) {
    emit(AuthUnauthenticated());
  }

  @override
  AuthState? fromJson(Map<String, dynamic> json) {
    final username = json['username'] as String?;
    if (username != null) return AuthAuthenticated(username);
    return AuthUnauthenticated();
  }

  @override
  Map<String, dynamic>? toJson(AuthState state) {
    if (state is AuthAuthenticated) return {'username': state.username};
    return null;
  }
}

// ============ TASK BLOC ============
abstract class TaskEvent extends Equatable {
  const TaskEvent();
  @override
  List<Object?> get props => [];
}

class TaskAdded extends TaskEvent {
  final String title;
  final String description;
  const TaskAdded(this.title, this.description);
  @override
  List<Object?> get props => [title, description];
}

class TaskToggled extends TaskEvent {
  final String taskId;
  const TaskToggled(this.taskId);
  @override
  List<Object?> get props => [taskId];
}

class TaskDeleted extends TaskEvent {
  final String taskId;
  const TaskDeleted(this.taskId);
  @override
  List<Object?> get props => [taskId];
}

class TaskFilterChanged extends TaskEvent {
  final TaskFilter filter;
  const TaskFilterChanged(this.filter);
  @override
  List<Object?> get props => [filter];
}

enum TaskFilter { all, active, completed }

class TaskState extends Equatable {
  final List<Task> tasks;
  final TaskFilter filter;

  const TaskState({this.tasks = const [], this.filter = TaskFilter.all});

  List<Task> get filteredTasks {
    switch (filter) {
      case TaskFilter.active:
        return tasks.where((t) => !t.isCompleted).toList();
      case TaskFilter.completed:
        return tasks.where((t) => t.isCompleted).toList();
      case TaskFilter.all:
        return tasks;
    }
  }

  int get activeCount => tasks.where((t) => !t.isCompleted).length;
  int get completedCount => tasks.where((t) => t.isCompleted).length;

  TaskState copyWith({List<Task>? tasks, TaskFilter? filter}) {
    return TaskState(
      tasks: tasks ?? this.tasks,
      filter: filter ?? this.filter,
    );
  }

  @override
  List<Object?> get props => [tasks, filter];
}

class TaskBloc extends HydratedBloc<TaskEvent, TaskState> {
  TaskBloc() : super(const TaskState()) {
    on<TaskAdded>(_onTaskAdded);
    on<TaskToggled>(_onTaskToggled);
    on<TaskDeleted>(_onTaskDeleted);
    on<TaskFilterChanged>(_onFilterChanged);
  }

  void _onTaskAdded(TaskAdded event, Emitter<TaskState> emit) {
    final task = Task(
      id: DateTime.now().millisecondsSinceEpoch.toString(),
      title: event.title,
      description: event.description,
      createdAt: DateTime.now(),
    );
    emit(state.copyWith(tasks: [...state.tasks, task]));
  }

  void _onTaskToggled(TaskToggled event, Emitter<TaskState> emit) {
    final updatedTasks = state.tasks.map((task) {
      if (task.id == event.taskId) {
        return task.copyWith(isCompleted: !task.isCompleted);
      }
      return task;
    }).toList();
    emit(state.copyWith(tasks: updatedTasks));
  }

  void _onTaskDeleted(TaskDeleted event, Emitter<TaskState> emit) {
    final updatedTasks = state.tasks.where((t) => t.id != event.taskId).toList();
    emit(state.copyWith(tasks: updatedTasks));
  }

  void _onFilterChanged(TaskFilterChanged event, Emitter<TaskState> emit) {
    emit(state.copyWith(filter: event.filter));
  }

  @override
  TaskState? fromJson(Map<String, dynamic> json) {
    try {
      final tasksJson = json['tasks'] as List<dynamic>?;
      final filterStr = json['filter'] as String? ?? 'all';
      final tasks = tasksJson?.map((t) => Task(
        id: t['id'],
        title: t['title'],
        description: t['description'] ?? '',
        isCompleted: t['isCompleted'] ?? false,
        createdAt: DateTime.parse(t['createdAt']),
      )).toList() ?? [];
      return TaskState(
        tasks: tasks,
        filter: TaskFilter.values.firstWhere((f) => f.name == filterStr),
      );
    } catch (_) {
      return null;
    }
  }

  @override
  Map<String, dynamic>? toJson(TaskState state) {
    return {
      'tasks': state.tasks.map((t) => {
        'id': t.id,
        'title': t.title,
        'description': t.description,
        'isCompleted': t.isCompleted,
        'createdAt': t.createdAt.toIso8601String(),
      }).toList(),
      'filter': state.filter.name,
    };
  }
}

// ============ THEME CUBIT ============
class ThemeCubit extends HydratedCubit<ThemeMode> {
  ThemeCubit() : super(ThemeMode.system);

  void toggleTheme() {
    emit(state == ThemeMode.light ? ThemeMode.dark : ThemeMode.light);
  }

  @override
  ThemeMode? fromJson(Map<String, dynamic> json) {
    final theme = json['theme'] as String?;
    return ThemeMode.values.firstWhere(
      (e) => e.name == theme,
      orElse: () => ThemeMode.system,
    );
  }

  @override
  Map<String, dynamic>? toJson(ThemeMode state) {
    return {'theme': state.name};
  }
}

// ============ APP ============
class TaskManagerApp extends StatelessWidget {
  const TaskManagerApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MultiBlocProvider(
      providers: [
        BlocProvider(create: (_) => AuthBloc()),
        BlocProvider(create: (_) => TaskBloc()),
        BlocProvider(create: (_) => ThemeCubit()),
      ],
      child: BlocBuilder<ThemeCubit, ThemeMode>(
        builder: (context, themeMode) {
          return MaterialApp(
            title: 'Task Manager Pro',
            debugShowCheckedModeBanner: false,
            themeMode: themeMode,
            theme: ThemeData(
              useMaterial3: true,
              colorScheme: ColorScheme.fromSeed(seedColor: Colors.indigo),
            ),
            darkTheme: ThemeData(
              useMaterial3: true,
              colorScheme: ColorScheme.fromSeed(
                seedColor: Colors.indigo,
                brightness: Brightness.dark,
              ),
            ),
            home: const AuthWrapper(),
          );
        },
      ),
    );
  }
}

// ============ AUTH WRAPPER ============
class AuthWrapper extends StatelessWidget {
  const AuthWrapper({super.key});

  @override
  Widget build(BuildContext context) {
    return BlocConsumer<AuthBloc, AuthState>(
      listener: (context, state) {
        if (state is AuthError) {
          ScaffoldMessenger.of(context).showSnackBar(
            SnackBar(
              content: Text(state.message),
              backgroundColor: Colors.red,
              behavior: SnackBarBehavior.floating,
            ),
          );
        }
      },
      builder: (context, state) {
        if (state is AuthAuthenticated) {
          return const TaskHomeScreen();
        }
        return const LoginScreen();
      },
    );
  }
}

// ============ LOGIN SCREEN ============
class LoginScreen extends StatefulWidget {
  const LoginScreen({super.key});

  @override
  State<LoginScreen> createState() => _LoginScreenState();
}

class _LoginScreenState extends State<LoginScreen> {
  final _emailController = TextEditingController(text: 'admin@example.com');
  final _passwordController = TextEditingController(text: 'password');
  final _formKey = GlobalKey<FormState>();

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: SingleChildScrollView(
          padding: const EdgeInsets.all(24),
          child: Form(
            key: _formKey,
            child: Column(
              mainAxisAlignment: MainAxisAlignment.center,
              children: [
                Icon(Icons.task_alt, size: 80, color: Theme.of(context).colorScheme.primary),
                const SizedBox(height: 24),
                Text(
                  'Task Manager Pro',
                  style: Theme.of(context).textTheme.headlineMedium?.copyWith(
                    fontWeight: FontWeight.bold,
                  ),
                ),
                const SizedBox(height: 8),
                Text(
                  'Sign in to manage your tasks',
                  style: TextStyle(color: Colors.grey.shade600),
                ),
                const SizedBox(height: 32),
                TextFormField(
                  controller: _emailController,
                  decoration: const InputDecoration(
                    labelText: 'Email',
                    prefixIcon: Icon(Icons.email_outlined),
                    border: OutlineInputBorder(),
                  ),
                  keyboardType: TextInputType.emailAddress,
                  validator: (value) => value?.contains('@') ?? false ? null : 'Enter valid email',
                ),
                const SizedBox(height: 16),
                TextFormField(
                  controller: _passwordController,
                  decoration: const InputDecoration(
                    labelText: 'Password',
                    prefixIcon: Icon(Icons.lock_outlined),
                    border: OutlineInputBorder(),
                  ),
                  obscureText: true,
                  validator: (value) => value?.isNotEmpty ?? false ? null : 'Enter password',
                ),
                const SizedBox(height: 24),
                SizedBox(
                  width: double.infinity,
                  height: 50,
                  child: BlocBuilder<AuthBloc, AuthState>(
                    builder: (context, state) {
                      final isLoading = state is AuthLoading;
                      return FilledButton(
                        onPressed: isLoading
                            ? null
                            : () {
                                if (_formKey.currentState?.validate() ?? false) {
                                  context.read<AuthBloc>().add(
                                    AuthLoginRequested(
                                      _emailController.text,
                                      _passwordController.text,
                                    ),
                                  );
                                }
                              },
                        child: isLoading
                            ? const SizedBox(
                                height: 20,
                                width: 20,
                                child: CircularProgressIndicator(strokeWidth: 2, color: Colors.white),
                              )
                            : const Text('Sign In'),
                      );
                    },
                  ),
                ),
                const SizedBox(height: 16),
                Text(
                  'Hint: admin@example.com / password',
                  style: TextStyle(color: Colors.grey.shade500, fontSize: 12),
                ),
              ],
            ),
          ),
        ),
      ),
    );
  }

  @override
  void dispose() {
    _emailController.dispose();
    _passwordController.dispose();
    super.dispose();
  }
}

// ============ TASK HOME SCREEN ============
class TaskHomeScreen extends StatelessWidget {
  const TaskHomeScreen({super.key});

  @override
  Widget build(BuildContext context) {
    final username = (context.read<AuthBloc>().state as AuthAuthenticated).username;

    return Scaffold(
      appBar: AppBar(
        title: const Text('My Tasks'),
        centerTitle: true,
        actions: [
          IconButton(
            icon: Icon(
              context.watch<ThemeCubit>().state == ThemeMode.dark
                  ? Icons.light_mode
                  : Icons.dark_mode,
            ),
            onPressed: () => context.read<ThemeCubit>().toggleTheme(),
          ),
          IconButton(
            icon: const Icon(Icons.logout),
            onPressed: () => context.read<AuthBloc>().add(AuthLogoutRequested()),
          ),
        ],
      ),
      body: Column(
        children: [
          _TaskStatsBar(),
          _TaskFilterChips(),
          const Expanded(child: _TaskList()),
        ],
      ),
      floatingActionButton: FloatingActionButton.extended(
        onPressed: () => _showAddTaskDialog(context),
        icon: const Icon(Icons.add),
        label: const Text('New Task'),
      ),
    );
  }

  void _showAddTaskDialog(BuildContext context) {
    final titleController = TextEditingController();
    final descController = TextEditingController();

    showDialog(
      context: context,
      builder: (dialogContext) => AlertDialog(
        title: const Text('Add New Task'),
        content: Column(
          mainAxisSize: MainAxisSize.min,
          children: [
            TextField(
              controller: titleController,
              decoration: const InputDecoration(
                labelText: 'Title',
                hintText: 'What needs to be done?',
              ),
              autofocus: true,
            ),
            const SizedBox(height: 8),
            TextField(
              controller: descController,
              decoration: const InputDecoration(
                labelText: 'Description (optional)',
              ),
              maxLines: 2,
            ),
          ],
        ),
        actions: [
          TextButton(
            onPressed: () => Navigator.pop(dialogContext),
            child: const Text('Cancel'),
          ),
          FilledButton(
            onPressed: () {
              if (titleController.text.trim().isNotEmpty) {
                context.read<TaskBloc>().add(
                  TaskAdded(titleController.text.trim(), descController.text.trim()),
                );
                Navigator.pop(dialogContext);
              }
            },
            child: const Text('Add'),
          ),
        ],
      ),
    );
  }
}

// ============ TASK STATS BAR ============
class _TaskStatsBar extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return BlocBuilder<TaskBloc, TaskState>(
      builder: (context, state) {
        return Container(
          margin: const EdgeInsets.all(16),
          padding: const EdgeInsets.all(16),
          decoration: BoxDecoration(
            color: Theme.of(context).colorScheme.primaryContainer,
            borderRadius: BorderRadius.circular(16),
          ),
          child: Row(
            mainAxisAlignment: MainAxisAlignment.spaceAround,
            children: [
              _StatItem(label: 'Total', value: state.tasks.length),
              _StatItem(label: 'Active', value: state.activeCount),
              _StatItem(label: 'Done', value: state.completedCount),
            ],
          ),
        );
      },
    );
  }
}

class _StatItem extends StatelessWidget {
  final String label;
  final int value;
  const _StatItem({required this.label, required this.value});

  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        Text(
          '$value',
          style: Theme.of(context).textTheme.headlineSmall?.copyWith(
            fontWeight: FontWeight.bold,
            color: Theme.of(context).colorScheme.primary,
          ),
        ),
        Text(label, style: TextStyle(color: Colors.grey.shade600)),
      ],
    );
  }
}

// ============ TASK FILTER CHIPS ============
class _TaskFilterChips extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return BlocBuilder<TaskBloc, TaskState>(
      builder: (context, state) {
        return Padding(
          padding: const EdgeInsets.symmetric(horizontal: 16),
          child: Row(
            children: TaskFilter.values.map((filter) {
              final isSelected = state.filter == filter;
              return Padding(
                padding: const EdgeInsets.only(right: 8),
                child: ChoiceChip(
                  label: Text(filter.name.toUpperCase()),
                  selected: isSelected,
                  onSelected: (_) {
                    context.read<TaskBloc>().add(TaskFilterChanged(filter));
                  },
                  selectedColor: Theme.of(context).colorScheme.primary,
                  labelStyle: TextStyle(
                    color: isSelected ? Colors.white : null,
                    fontWeight: FontWeight.bold,
                  ),
                ),
              );
            }).toList(),
          ),
        );
      },
    );
  }
}

// ============ TASK LIST ============
class _TaskList extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return BlocBuilder<TaskBloc, TaskState>(
      builder: (context, state) {
        final tasks = state.filteredTasks;

        if (tasks.isEmpty) {
          return Center(
            child: Column(
              mainAxisAlignment: MainAxisAlignment.center,
              children: [
                Icon(Icons.inbox_outlined, size: 64, color: Colors.grey.shade400),
                const SizedBox(height: 16),
                Text(
                  'No ${state.filter.name} tasks',
                  style: TextStyle(color: Colors.grey.shade600),
                ),
              ],
            ),
          );
        }

        return ListView.builder(
          padding: const EdgeInsets.all(16),
          itemCount: tasks.length,
          itemBuilder: (context, index) {
            final task = tasks[index];
            return _TaskCard(task: task);
          },
        );
      },
    );
  }
}

// ============ TASK CARD ============
class _TaskCard extends StatelessWidget {
  final Task task;
  const _TaskCard({required this.task});

  @override
  Widget build(BuildContext context) {
    return Dismissible(
      key: Key(task.id),
      direction: DismissDirection.endToStart,
      background: Container(
        margin: const EdgeInsets.only(bottom: 8),
        decoration: BoxDecoration(
          color: Colors.red.shade100,
          borderRadius: BorderRadius.circular(12),
        ),
        alignment: Alignment.centerRight,
        padding: const EdgeInsets.only(right: 16),
        child: const Icon(Icons.delete, color: Colors.red),
      ),
      onDismissed: (_) {
        context.read<TaskBloc>().add(TaskDeleted(task.id));
        ScaffoldMessenger.of(context).showSnackBar(
          const SnackBar(
            content: Text('Task deleted'),
            behavior: SnackBarBehavior.floating,
          ),
        );
      },
      child: Card(
        margin: const EdgeInsets.only(bottom: 8),
        child: ListTile(
          contentPadding: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
          leading: Checkbox(
            value: task.isCompleted,
            onChanged: (_) {
              context.read<TaskBloc>().add(TaskToggled(task.id));
            },
          ),
          title: Text(
            task.title,
            style: TextStyle(
              decoration: task.isCompleted ? TextDecoration.lineThrough : null,
              color: task.isCompleted ? Colors.grey : null,
              fontWeight: FontWeight.w600,
            ),
          ),
          subtitle: task.description.isNotEmpty
              ? Text(
                  task.description,
                  maxLines: 2,
                  overflow: TextOverflow.ellipsis,
                  style: TextStyle(color: Colors.grey.shade600),
                )
              : null,
          trailing: Icon(
            task.isCompleted ? Icons.check_circle : Icons.circle_outlined,
            color: task.isCompleted ? Colors.green : Colors.grey,
          ),
        ),
      ),
    );
  }
}
```

---

# 12. Common Mistakes & How to Avoid Them

## Mistake 1: Not Extending Equatable on States
```dart
// WRONG — BLoC won't detect state changes
class CounterState {
  final int count;
  CounterState(this.count);
}

// CORRECT — Proper equality checks
class CounterState extends Equatable {
  final int count;
  const CounterState(this.count);
  @override
  List<Object?> get props => [count];
}
```

## Mistake 2: Mutating State Directly
```dart
// WRONG — Mutating existing state
class CounterBloc extends Bloc<CounterEvent, CounterState> {
  void increment() {
    state.count++; // NEVER mutate state directly!
    emit(state);
  }
}

// CORRECT — Always create new state objects
void increment() {
  emit(CounterState(state.count + 1));
}
```

## Mistake 3: Using BuildContext in BLoC
```dart
// WRONG — BLoC should be pure Dart, no UI dependencies
class AuthBloc extends Bloc<AuthEvent, AuthState> {
  void login() {
    Navigator.push(context, ...); // NEVER do this!
  }
}

// CORRECT — Navigation belongs in BlocListener
BlocListener<AuthBloc, AuthState>(
  listener: (context, state) {
    if (state is AuthAuthenticated) {
      Navigator.pushReplacementNamed(context, '/home');
    }
  },
  child: ...,
)
```

## Mistake 4: Not Closing Streams/Controllers
```dart
// WRONG — Memory leak
class MyBloc extends Bloc<MyEvent, MyState> {
  final stream = someDataStream(); // Never closed!
}

// CORRECT — Clean up in close()
class MyBloc extends Bloc<MyEvent, MyState> {
  StreamSubscription? _subscription;

  MyBloc() {
    _subscription = someDataStream().listen((data) {
      add(DataReceived(data));
    });
  }

  @override
  Future<void> close() {
    _subscription?.cancel();
    return super.close();
  }
}
```

## Mistake 5: Calling emit After await Without Checking isClosed
```dart
// WRONG — Can crash if BLoC is disposed
Future<void> fetchData() async {
  emit(LoadingState());
  final data = await repository.fetch(); // User navigates away...
  emit(LoadedState(data)); // CRASH: Cannot emit new states after calling close
}

// CORRECT — Check mounted state
Future<void> fetchData() async {
  emit(LoadingState());
  final data = await repository.fetch();
  if (!isClosed) {
    emit(LoadedState(data));
  }
}
```

## Mistake 6: Using context.read Instead of context.watch
```dart
// WRONG — Won't rebuild when state changes
Text('${context.read<CounterCubit>().state.count}')

// CORRECT — Use BlocBuilder or context.watch
BlocBuilder<CounterCubit, CounterState>(
  builder: (context, state) => Text('${state.count}'),
)
```

## Mistake 7: Not Using HydratedBloc with Sensitive Data
```dart
// WRONG — Never persist passwords or tokens in plain text
@override
Map<String, dynamic>? toJson(AuthState state) {
  if (state is AuthAuthenticated) {
    return {'token': state.token, 'password': state.password}; // SECURITY RISK!
  }
  return null;
}

// CORRECT — Store only non-sensitive data, use secure storage for tokens
@override
Map<String, dynamic>? toJson(AuthState state) {
  if (state is AuthAuthenticated) {
    return {'userId': state.user.id, 'username': state.user.name};
  }
  return null;
}
```

---

# 13. Day 14 Checklist

Use this checklist to verify mastery:
- [ ] Understands why BLoC is the industry standard for enterprise Flutter apps
- [ ] Can explain the difference between Events, States, and Transitions
- [ ] Knows when to use Cubit vs Bloc
- [ ] Can create a Cubit with emit() methods
- [ ] Can create a Bloc with on<Event>() handlers
- [ ] Uses Equatable (or Freezed) for proper state equality
- [ ] Can use BlocBuilder for UI rebuilds
- [ ] Can use BlocListener for side effects (navigation, SnackBar)
- [ ] Can use BlocConsumer for combined builder + listener
- [ ] Can set up MultiBlocProvider for multiple blocs
- [ ] Can set up RepositoryProvider for dependency injection
- [ ] Understands BlocObserver for global debugging
- [ ] Can implement HydratedBloc/HydratedCubit for state persistence
- [ ] Knows how to use event transformers (debounce, throttle, sequential)
- [ ] Built the Task Manager Pro app with Auth + Task + Theme blocs
- [ ] App has login/logout with HydratedBloc persistence
- [ ] App has full CRUD for tasks with filter support
- [ ] App has theme persistence across app restarts
- [ ] App handles loading, error, and success states properly
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **BLoC separates business logic from UI** — your BLoC is pure Dart with zero Flutter dependencies, making it 100% testable.
2. **Cubit for simple, Bloc for complex** — use Cubit for counters and toggles; use Bloc when you need event history, audit trails, or complex business rules.
3. **Never mutate state** — always create new state objects with `copyWith()` or constructors. BLoC relies on object equality to detect changes.
4. **Equatable is mandatory** — without `extends Equatable`, BLoC can't tell if a state actually changed, causing missed rebuilds.
5. **UI logic goes in BlocListener, not in BLoC** — navigation, SnackBars, and dialogs belong in the widget layer. BLoC should only emit states.
6. **HydratedBloc is magic for persistence** — automatically save and restore state across app kills with just `fromJson()` and `toJson()`.
7. **BlocObserver gives you superpowers** — see every event, transition, and error globally. Essential for debugging and analytics.
8. **Always close subscriptions** — if your BLoC listens to streams, cancel subscriptions in the `close()` method to prevent memory leaks.
9. **Use `buildWhen` to optimize rebuilds** — prevent unnecessary widget rebuilds by comparing previous and current states.
10. **RepositoryProvider + BlocProvider = Clean DI** — inject repositories at the root, pass them to blocs, and override for testing.

---

# Extra Practice (Do These Tonight!)

1. **Weather App with BLoC:** Convert the Day 13 Weather App to use Bloc pattern. Add location search with debounced events, pull-to-refresh with `RefreshWeather` event, and error retry with `RetryWeather` event.
2. **E-Commerce Cart:** Build a cart system with `AddToCart`, `RemoveFromCart`, `UpdateQuantity`, and `ApplyCoupon` events. Use HydratedBloc to persist cart across sessions.
3. **Multi-Step Form Wizard:** Create a 4-step registration form where each step validates before proceeding. Use BlocListener to auto-advance steps and show validation errors.
4. **Infinite Scroll List:** Implement pagination with `FetchPosts`, `FetchMorePosts`, and `RefreshPosts` events. Use `bloc_concurrency` to handle sequential loading.
5. **Real-Time Chat:** Use StreamSubscription inside a Bloc to listen to WebSocket messages. Handle connection states (connecting, connected, disconnected, reconnecting) with proper event mapping.

---

**Congratulations!** You've completed Day 14. You now master the BLoC pattern — the enterprise-grade state management solution that powers production Flutter apps at scale. You can build predictable, testable, and maintainable applications with full state traceability and persistence.

**Next Up → Day 15: Local Data Persistence (SharedPreferences, SQLite, Hive)**

---

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 14: State Management — BLoC Pattern — Complete Deep Dive*

# Day 15: Local Data Persistence
## Complete Deep Dive

**Goal:** Master every local data persistence technique in Flutter — from simple key-value storage to full SQL databases and lightning-fast NoSQL. Build an offline-first Notes App with categories, search, CRUD operations, and automatic sync architecture.

---

# Table of Contents
1. Why Local Persistence Matters
2. Choosing the Right Storage Solution
3. SharedPreferences — Simple Key-Value Storage
4. path_provider — File System Access
5. sqflite — SQLite Database
6. Hive — Lightning-Fast NoSQL
7. drift (formerly moor) — Type-Safe SQLite
8. Secure Storage with flutter_secure_storage
9. Architecture: Offline-First Pattern
10. Hands-On Project: Notes Pro App
11. Common Mistakes & How to Avoid Them
12. Day 15 Checklist

---

# 1. Why Local Persistence Matters

## The Offline-First Mindset
In 2026, users expect apps to work **flawlessly without internet**. Local persistence is not optional — it's mandatory for production-grade apps.

## Real-World Scenarios
| Scenario | Storage Solution | Why |
|---|---|---|
| Remember login state | SharedPreferences | Simple boolean/string |
| Cache API responses | Hive | Fast read/write, structured data |
| User-generated content (notes, tasks) | sqflite / drift | Relational data, queries, search |
| Store JWT tokens | flutter_secure_storage | Encrypted, OS Keychain |
| Large files (images, PDFs) | path_provider + File IO | File system storage |
| Complex relational data | drift | Type-safe SQL, migrations |

---

# 2. Choosing the Right Storage Solution

## Comparison Matrix (2026 Edition)
| Feature | SharedPreferences | sqflite | Hive | drift | Secure Storage |
|---|---|---|---|---|---|
| **Data Type** | Primitive only | Structured (SQL) | Structured (NoSQL) | Structured (Type-Safe SQL) | String only |
| **Speed** | Fast | Medium | **Fastest** | Medium | Slow (encryption) |
| **Complex Queries** | No | Yes SQL | No (basic) | Yes Type-safe SQL | No |
| **Relations** | No | Yes Foreign Keys | No | Yes Relations | No |
| **Encryption** | No | Manual | No | No | Yes Built-in |
| **Type Safety** | No | No | Partial | Yes Full | No |
| **Migrations** | N/A | Manual SQL | Automatic | Generated | N/A |
| **Best For** | Settings, flags | Complex relational data | Simple objects, caching | Enterprise apps | Tokens, passwords |

## Decision Tree
- Simple settings (theme, onboarding flag)? -> SharedPreferences
- JWT, API keys, passwords? -> flutter_secure_storage
- Simple objects, cache, config? -> Hive
- Complex relational data, search, joins? -> drift (type-safe) or sqflite (manual)
- Large files (images, PDFs)? -> path_provider + dart:io File

---

# 3. SharedPreferences — Simple Key-Value Storage

## Package Setup
```yaml
dependencies:
  shared_preferences: ^2.2.3
```

## Complete Implementation
```dart
import 'package:shared_preferences/shared_preferences.dart';

class SharedPrefsService {
  static SharedPreferences? _prefs;

  static Future<void> init() async {
    _prefs = await SharedPreferences.getInstance();
  }

  static Future<bool> setString(String key, String value) async =>
      await _prefs!.setString(key, value);
  static String? getString(String key) => _prefs!.getString(key);

  static Future<bool> setInt(String key, int value) async =>
      await _prefs!.setInt(key, value);
  static int? getInt(String key) => _prefs!.getInt(key);

  static Future<bool> setBool(String key, bool value) async =>
      await _prefs!.setBool(key, value);
  static bool getBool(String key, {bool defaultValue = false}) =>
      _prefs!.getBool(key) ?? defaultValue;

  static Future<bool> setDouble(String key, double value) async =>
      await _prefs!.setDouble(key, value);
  static double? getDouble(String key) => _prefs!.getDouble(key);

  static Future<bool> setStringList(String key, List<String> value) async =>
      await _prefs!.setStringList(key, value);
  static List<String>? getStringList(String key) => _prefs!.getStringList(key);

  static Future<bool> remove(String key) async => await _prefs!.remove(key);
  static Future<bool> clear() async => await _prefs!.clear();
  static bool containsKey(String key) => _prefs!.containsKey(key);
}
```

## Practical Usage: Theme & Onboarding
```dart
class AppSettings {
  static const String _themeKey = 'app_theme';
  static const String _onboardingKey = 'onboarding_complete';

  static Future<void> setThemeMode(ThemeMode mode) async {
    await SharedPrefsService.setString(_themeKey, mode.name);
  }

  static ThemeMode getThemeMode() {
    final themeName = SharedPrefsService.getString(_themeKey);
    return ThemeMode.values.firstWhere(
      (e) => e.name == themeName,
      orElse: () => ThemeMode.system,
    );
  }

  static Future<void> setOnboardingComplete(bool value) async {
    await SharedPrefsService.setBool(_onboardingKey, value);
  }

  static bool isOnboardingComplete() {
    return SharedPrefsService.getBool(_onboardingKey);
  }
}
```

## Storing Complex Objects (JSON Serialization)
```dart
import 'dart:convert';

class UserSettings {
  final String language;
  final bool notificationsEnabled;
  final double fontSize;

  UserSettings({this.language = 'en', this.notificationsEnabled = true, this.fontSize = 14.0});

  Map<String, dynamic> toJson() => {
    'language': language,
    'notificationsEnabled': notificationsEnabled,
    'fontSize': fontSize,
  };

  factory UserSettings.fromJson(Map<String, dynamic> json) => UserSettings(
    language: json['language'] ?? 'en',
    notificationsEnabled: json['notificationsEnabled'] ?? true,
    fontSize: json['fontSize'] ?? 14.0,
  );
}

// Save
final settings = UserSettings(language: 'es', fontSize: 16.0);
await SharedPrefsService.setString('user_settings', jsonEncode(settings.toJson()));

// Read
final jsonString = SharedPrefsService.getString('user_settings');
if (jsonString != null) {
  final settings = UserSettings.fromJson(jsonDecode(jsonString));
}
```

---

# 4. path_provider — File System Access

## Package Setup
```yaml
dependencies:
  path_provider: ^2.1.3
```

## Directory Types
| Method | Path | Use Case | Persistent? |
|---|---|---|---|
| getApplicationDocumentsDirectory() | /data/data/<pkg>/app_flutter | User-generated files | Yes |
| getApplicationSupportDirectory() | Platform-specific support dir | App support files | Yes |
| getTemporaryDirectory() | /data/data/<pkg>/cache | Temporary files | No |
| getExternalStorageDirectory() | /storage/emulated/0/... | Large files, media | Yes (Android) |
| getDownloadsDirectory() | System Downloads folder | Export files | Yes |

## Complete File Operations
```dart
import 'dart:io';
import 'package:path_provider/path_provider.dart';
import 'package:path/path.dart' as path;

class FileStorageService {
  static Future<Directory> get _docsDir async =>
      await getApplicationDocumentsDirectory();

  static Future<File> writeTextFile(String fileName, String content) async {
    final dir = await _docsDir;
    return File(path.join(dir.path, fileName)).writeAsString(content);
  }

  static Future<String?> readTextFile(String fileName) async {
    try {
      final dir = await _docsDir;
      return await File(path.join(dir.path, fileName)).readAsString();
    } catch (e) { return null; }
  }

  static Future<File> writeBinaryFile(String fileName, List<int> bytes) async {
    final dir = await _docsDir;
    return File(path.join(dir.path, fileName)).writeAsBytes(bytes);
  }

  static Future<List<int>?> readBinaryFile(String fileName) async {
    try {
      final dir = await _docsDir;
      return await File(path.join(dir.path, fileName)).readAsBytes();
    } catch (e) { return null; }
  }

  static Future<bool> deleteFile(String fileName) async {
    try {
      final dir = await _docsDir;
      await File(path.join(dir.path, fileName)).delete();
      return true;
    } catch (e) { return false; }
  }

  static Future<List<FileSystemEntity>> listFiles() async {
    final dir = await _docsDir;
    return dir.listSync();
  }

  static Future<bool> exists(String fileName) async {
    final dir = await _docsDir;
    return File(path.join(dir.path, fileName)).exists();
  }
}
```

## Export Notes to File Example
```dart
class NoteExporter {
  static Future<String> exportNotesToFile(List<Note> notes) async {
    final buffer = StringBuffer();
    buffer.writeln('=== My Notes Export ===');
    buffer.writeln('Exported: ${DateTime.now()}');
    buffer.writeln('');

    for (final note in notes) {
      buffer.writeln('--- ${note.title} ---');
      buffer.writeln('Category: ${note.category}');
      buffer.writeln(note.content);
      buffer.writeln('');
    }

    final fileName = 'notes_export_${DateTime.now().millisecondsSinceEpoch}.txt';
    await FileStorageService.writeTextFile(fileName, buffer.toString());
    return fileName;
  }
}
```

---

# 5. sqflite — SQLite Database

## Package Setup
```yaml
dependencies:
  sqflite: ^2.3.3+1
  path: ^1.9.0
```

## Database Helper (Singleton Pattern)
```dart
import 'package:sqflite/sqflite.dart';
import 'package:path/path.dart';

class DatabaseHelper {
  static final DatabaseHelper _instance = DatabaseHelper._internal();
  factory DatabaseHelper() => _instance;
  DatabaseHelper._internal();

  static Database? _database;

  Future<Database> get database async {
    _database ??= await _initDatabase();
    return _database!;
  }

  Future<Database> _initDatabase() async {
    final dbPath = await getDatabasesPath();
    final path = join(dbPath, 'notes_pro.db');

    return await openDatabase(
      path,
      version: 2,
      onCreate: _onCreate,
      onUpgrade: _onUpgrade,
      onDowngrade: onDatabaseDowngradeDelete,
    );
  }

  Future<void> _onCreate(Database db, int version) async {
    await db.execute('''
      CREATE TABLE categories (
        id INTEGER PRIMARY KEY AUTOINCREMENT,
        name TEXT NOT NULL UNIQUE,
        color INTEGER NOT NULL DEFAULT 0xFF2196F3,
        created_at TEXT NOT NULL
      )
    ''');

    await db.execute('''
      CREATE TABLE notes (
        id INTEGER PRIMARY KEY AUTOINCREMENT,
        title TEXT NOT NULL,
        content TEXT NOT NULL,
        category_id INTEGER,
        is_pinned INTEGER NOT NULL DEFAULT 0,
        is_archived INTEGER NOT NULL DEFAULT 0,
        created_at TEXT NOT NULL,
        updated_at TEXT NOT NULL,
        FOREIGN KEY (category_id) REFERENCES categories(id) ON DELETE SET NULL
      )
    ''');

    // Seed default categories
    await db.insert('categories', {
      'name': 'Personal', 'color': 0xFF2196F3,
      'created_at': DateTime.now().toIso8601String(),
    });
    await db.insert('categories', {
      'name': 'Work', 'color': 0xFF4CAF50,
      'created_at': DateTime.now().toIso8601String(),
    });
  }

  Future<void> _onUpgrade(Database db, int oldVersion, int newVersion) async {
    if (oldVersion < 2) {
      await db.execute('ALTER TABLE notes ADD COLUMN tags TEXT');
    }
  }

  // CRUD: Categories
  Future<int> insertCategory(Map<String, dynamic> category) async {
    final db = await database;
    return await db.insert('categories', category);
  }

  Future<List<Map<String, dynamic>>> getCategories() async {
    final db = await database;
    return await db.query('categories', orderBy: 'name ASC');
  }

  // CRUD: Notes
  Future<int> insertNote(Map<String, dynamic> note) async {
    final db = await database;
    return await db.insert('notes', note);
  }

  Future<List<Map<String, dynamic>>> getNotes({
    int? categoryId,
    bool includeArchived = false,
    String? searchQuery,
    String orderBy = 'updated_at DESC',
  }) async {
    final db = await database;
    String whereClause = '';
    List<dynamic> whereArgs = [];

    if (!includeArchived) whereClause = 'is_archived = 0';
    if (categoryId != null) {
      whereClause = whereClause.isEmpty
          ? 'category_id = ?'
          : '$whereClause AND category_id = ?';
      whereArgs.add(categoryId);
    }
    if (searchQuery != null && searchQuery.isNotEmpty) {
      whereClause = whereClause.isEmpty
          ? '(title LIKE ? OR content LIKE ?)'
          : '$whereClause AND (title LIKE ? OR content LIKE ?)';
      whereArgs.addAll(['%$searchQuery%', '%$searchQuery%']);
    }

    return await db.query(
      'notes',
      where: whereClause.isEmpty ? null : whereClause,
      whereArgs: whereArgs.isEmpty ? null : whereArgs,
      orderBy: orderBy,
    );
  }

  Future<int> updateNote(int id, Map<String, dynamic> note) async {
    final db = await database;
    return await db.update('notes', note, where: 'id = ?', whereArgs: [id]);
  }

  Future<int> deleteNote(int id) async {
    final db = await database;
    return await db.delete('notes', where: 'id = ?', whereArgs: [id]);
  }

  Future<int> archiveNote(int id, bool archive) async {
    final db = await database;
    return await db.update(
      'notes',
      {'is_archived': archive ? 1 : 0, 'updated_at': DateTime.now().toIso8601String()},
      where: 'id = ?', whereArgs: [id],
    );
  }

  // Advanced Queries
  Future<List<Map<String, dynamic>>> getNotesWithCategories() async {
    final db = await database;
    return await db.rawQuery('''
      SELECT notes.*, categories.name as category_name
      FROM notes
      LEFT JOIN categories ON notes.category_id = categories.id
      WHERE notes.is_archived = 0
      ORDER BY notes.is_pinned DESC, notes.updated_at DESC
    ''');
  }

  Future<void> close() async {
    final db = await database;
    await db.close();
    _database = null;
  }
}
```

---

# 6. Hive — Lightning-Fast NoSQL

## Why Hive?
- **Fastest** local database in Flutter (written in pure Dart)
- **Zero boilerplate** — no SQL, no migrations
- **Type adapters** — store any Dart object directly
- **Encrypted boxes** — built-in AES-256 encryption
- **Lazy boxes** — load data on-demand for huge datasets

## Package Setup
```yaml
dependencies:
  hive: ^2.2.3
  hive_flutter: ^1.1.0

dev_dependencies:
  hive_generator: ^2.0.1
  build_runner: ^2.4.9
```

## Initialize Hive
```dart
import 'package:hive_flutter/hive_flutter.dart';

void main() async {
  await Hive.initFlutter();
  Hive.registerAdapter(NoteAdapter());
  Hive.registerAdapter(CategoryAdapter());
  runApp(const MyApp());
}
```

## Model with Type Adapter (Code Generation)
```dart
import 'package:hive/hive.dart';

part 'note_model.g.dart'; // Generated by build_runner

@HiveType(typeId: 0)
class Note extends HiveObject {
  @HiveField(0) String id;
  @HiveField(1) String title;
  @HiveField(2) String content;
  @HiveField(3) String category;
  @HiveField(4) int colorValue;
  @HiveField(5) bool isPinned;
  @HiveField(6) bool isArchived;
  @HiveField(7) DateTime createdAt;
  @HiveField(8) DateTime updatedAt;

  Note({
    required this.id,
    required this.title,
    this.content = '',
    this.category = 'Personal',
    this.colorValue = 0xFF2196F3,
    this.isPinned = false,
    this.isArchived = false,
    required this.createdAt,
    required this.updatedAt,
  });

  Note copyWith({
    String? title, String? content, String? category,
    int? colorValue, bool? isPinned, bool? isArchived, DateTime? updatedAt,
  }) {
    return Note(
      id: id,
      title: title ?? this.title,
      content: content ?? this.content,
      category: category ?? this.category,
      colorValue: colorValue ?? this.colorValue,
      isPinned: isPinned ?? this.isPinned,
      isArchived: isArchived ?? this.isArchived,
      createdAt: createdAt,
      updatedAt: updatedAt ?? this.updatedAt,
    );
  }
}
```

## Run Code Generation
```bash
dart run build_runner build
```

## Hive Service Layer
```dart
class HiveNoteService {
  static const String _notesBoxName = 'notes';
  static const String _categoriesBoxName = 'categories';

  late Box<Note> _notesBox;
  late Box<AppCategory> _categoriesBox;

  Future<void> init() async {
    _notesBox = await Hive.openBox<Note>(_notesBoxName);
    _categoriesBox = await Hive.openBox<AppCategory>(_categoriesBoxName);

    if (_categoriesBox.isEmpty) {
      await _categoriesBox.putAll({
        'personal': AppCategory(id: 'personal', name: 'Personal', colorValue: 0xFF2196F3),
        'work': AppCategory(id: 'work', name: 'Work', colorValue: 0xFF4CAF50),
        'ideas': AppCategory(id: 'ideas', name: 'Ideas', colorValue: 0xFFFF9800),
      });
    }
  }

  Future<void> addNote(Note note) async => await _notesBox.put(note.id, note);
  Note? getNote(String id) => _notesBox.get(id);
  Future<void> updateNote(Note note) async => await _notesBox.put(note.id, note);
  Future<void> deleteNote(String id) async => await _notesBox.delete(id);

  List<Note> getAllNotes() {
    return _notesBox.values.where((n) => !n.isArchived).toList()
      ..sort((a, b) => b.updatedAt.compareTo(a.updatedAt));
  }

  List<Note> searchNotes(String query) {
    final lower = query.toLowerCase();
    return _notesBox.values
        .where((n) => !n.isArchived &&
            (n.title.toLowerCase().contains(lower) ||
             n.content.toLowerCase().contains(lower)))
        .toList()
      ..sort((a, b) => b.updatedAt.compareTo(a.updatedAt));
  }

  int get noteCount => _notesBox.values.where((n) => !n.isArchived).length;
  List<AppCategory> getAllCategories() => _categoriesBox.values.toList();

  // Encrypted Box
  Future<Box<dynamic>> openEncryptedBox(String name) async {
    final secureKey = Hive.generateSecureKey();
    return await Hive.openBox(name, encryptionCipher: HiveAesCipher(secureKey));
  }

  // Lazy Box
  Future<LazyBox<Note>> openLazyBox() async {
    return await Hive.openLazyBox<Note>('lazy_notes');
  }
}
```

---

# 7. drift (formerly moor) — Type-Safe SQLite

## Why drift?
- **Compile-time SQL safety** — catch query errors before running
- **Auto-generated code** — no manual SQL string writing
- **Migrations handled** — version control for your schema
- **Reactive queries** — auto-refresh when data changes

## Package Setup
```yaml
dependencies:
  drift: ^2.18.0
  sqlite3_flutter_libs: ^0.5.20

dev_dependencies:
  drift_dev: ^2.18.0
  build_runner: ^2.4.9
```

## Database Definition
```dart
import 'package:drift/drift.dart';
import 'package:drift_flutter/drift_flutter.dart';

part 'app_database.g.dart';

class Categories extends Table {
  IntColumn get id => integer().autoIncrement()();
  TextColumn get name => text().withLength(min: 1, max: 50)();
  IntColumn get color => integer()();
  DateTimeColumn get createdAt => dateTime().withDefault(currentDateAndTime)();
}

class Notes extends Table {
  IntColumn get id => integer().autoIncrement()();
  TextColumn get title => text().withLength(min: 1, max: 200)();
  TextColumn get content => text().nullable()();
  IntColumn get categoryId => integer().nullable().references(Categories, #id)();
  BoolColumn get isPinned => boolean().withDefault(const Constant(false))();
  BoolColumn get isArchived => boolean().withDefault(const Constant(false))();
  DateTimeColumn get createdAt => dateTime().withDefault(currentDateAndTime)();
  DateTimeColumn get updatedAt => dateTime().withDefault(currentDateAndTime)();
}

@DriftDatabase(tables: [Categories, Notes])
class AppDatabase extends _$AppDatabase {
  AppDatabase() : super(_openConnection());

  @override
  int get schemaVersion => 1;

  static QueryExecutor _openConnection() {
    return driftDatabase(name: 'notes_drift_db', native: const DriftNativeOptions());
  }

  Future<List<Category>> getAllCategories() => select(categories).get();
  Future<int> insertCategory(CategoriesCompanion category) => into(categories).insert(category);
  Future<bool> updateCategory(Category category) => update(categories).replace(category);
  Future<int> deleteCategory(int id) => (delete(categories)..where((c) => c.id.equals(id))).go();

  Future<List<Note>> getAllNotes() =>
      (select(notes)..where((n) => n.isArchived.equals(false))).get();

  Stream<List<Note>> watchAllNotes() =>
      (select(notes)..where((n) => n.isArchived.equals(false))).watch();

  Future<List<Note>> searchNotes(String query) {
    final lowerQuery = Variable('%${query.toLowerCase()}%');
    return (select(notes)
          ..where((n) => n.isArchived.equals(false) &
              (n.title.lower().like(lowerQuery) | n.content.lower().like(lowerQuery))))
        .get();
  }

  Future<int> insertNote(NotesCompanion note) => into(notes).insert(note);
  Future<bool> updateNote(Note note) => update(notes).replace(note);
  Future<int> deleteNote(int id) => (delete(notes)..where((n) => n.id.equals(id))).go();

  Future<List<NoteWithCategory>> getNotesWithCategories() async {
    final query = select(notes).join([
      leftOuterJoin(categories, categories.id.equalsExp(notes.categoryId)),
    ]);
    return query.map((row) => NoteWithCategory(
      note: row.readTable(notes),
      category: row.readTableOrNull(categories),
    )).get();
  }

  @override
  MigrationStrategy get migration => MigrationStrategy(
    onCreate: (Migrator m) async {
      await m.createAll();
      await into(categories).insert(CategoriesCompanion.insert(name: 'Personal', color: const Value(0xFF2196F3)));
      await into(categories).insert(CategoriesCompanion.insert(name: 'Work', color: const Value(0xFF4CAF50)));
    },
  );
}

class NoteWithCategory {
  final Note note;
  final Category? category;
  NoteWithCategory({required this.note, this.category});
}
```

## Run Code Generation
```bash
dart run build_runner build
```

---

# 8. Secure Storage with flutter_secure_storage

## Package Setup
```yaml
dependencies:
  flutter_secure_storage: ^9.2.2
```

## Complete Implementation
```dart
import 'package:flutter_secure_storage/flutter_secure_storage.dart';

class SecureStorageService {
  static const _storage = FlutterSecureStorage(
    aOptions: AndroidOptions(
      encryptedSharedPreferences: true,
      keyCipherAlgorithm: KeyCipherAlgorithm.RSA_ECB_PKCS1Padding,
      storageCipherAlgorithm: StorageCipherAlgorithm.AES_GCM_NoPadding,
    ),
    iOptions: IOSOptions(
      accountName: 'flutter_secure_storage_service',
      accessibility: KeychainAccessibility.first_unlock,
    ),
  );

  // Token Management
  static Future<void> setAuthToken(String token) async {
    await _storage.write(key: 'auth_token', value: token);
  }

  static Future<String?> getAuthToken() async {
    return await _storage.read(key: 'auth_token');
  }

  static Future<void> deleteAuthToken() async {
    await _storage.delete(key: 'auth_token');
  }

  // Refresh Token
  static Future<void> setRefreshToken(String token) async {
    await _storage.write(key: 'refresh_token', value: token);
  }

  static Future<String?> getRefreshToken() async {
    return await _storage.read(key: 'refresh_token');
  }

  // API Keys
  static Future<void> setApiKey(String key, String value) async {
    await _storage.write(key: 'api_key_$key', value: value);
  }

  static Future<String?> getApiKey(String key) async {
    return await _storage.read(key: 'api_key_$key');
  }

  // Clear All
  static Future<void> clearAll() async {
    await _storage.deleteAll();
  }

  // Check if key exists
  static Future<bool> containsKey(String key) async {
    return await _storage.containsKey(key: key);
  }
}
```

---

# 9. Architecture: Offline-First Pattern

## The Sync Architecture
```
UI Layer <---- BLoC/Riverpod <---- Repository Pattern
                                      |
                    +-----------------+-----------------+
                    |                 |                 |
                    v                 v                 v
              Local DB          Sync Queue         Remote API
            (Hive/sqflite)    (Pending changes)   (Firebase/REST)
```

## Repository Pattern Implementation
```dart
abstract class NoteRepository {
  Future<List<Note>> getNotes();
  Future<void> saveNote(Note note);
  Future<void> deleteNote(String id);
  Future<void> syncWithRemote();
}

class LocalNoteRepository implements NoteRepository {
  final HiveNoteService _localService;
  final NoteApiService _apiService;

  LocalNoteRepository(this._localService, this._apiService);

  @override
  Future<List<Note>> getNotes() async {
    // Always read from local first (offline-first)
    return _localService.getAllNotes();
  }

  @override
  Future<void> saveNote(Note note) async {
    // 1. Save locally immediately
    await _localService.addNote(note);

    // 2. Try to sync with remote
    try {
      await _apiService.saveNote(note);
    } catch (e) {
      // 3. Queue for later sync
      await _queueForSync(note.id, SyncAction.update);
    }
  }

  @override
  Future<void> deleteNote(String id) async {
    await _localService.deleteNote(id);
    try {
      await _apiService.deleteNote(id);
    } catch (e) {
      await _queueForSync(id, SyncAction.delete);
    }
  }

  Future<void> _queueForSync(String noteId, SyncAction action) async {
    final pendingBox = await Hive.openBox('pending_sync');
    await pendingBox.put(noteId, {
      'action': action.name,
      'timestamp': DateTime.now().toIso8601String()
    });
  }

  @override
  Future<void> syncWithRemote() async {
    final pendingBox = await Hive.openBox('pending_sync');
    final pending = pendingBox.toMap();

    for (final entry in pending.entries) {
      try {
        final note = _localService.getNote(entry.key);
        if (note != null) {
          await _apiService.saveNote(note);
          await pendingBox.delete(entry.key);
        }
      } catch (e) {
        // Keep in queue for next sync attempt
      }
    }
  }
}

enum SyncAction { create, update, delete }
```

---

# 10. Hands-On Project: Notes Pro App

## Project Overview
Build a complete **Notes Pro** app with:
- **Hive** for lightning-fast note storage
- **Categories** with custom colors
- **Full-text search** across titles and content
- **Pin, archive, delete** with swipe actions
- **Dark/Light theme** persistence via SharedPreferences
- **Export notes** to text file via path_provider
- **Beautiful UI** with Material 3 design

## Complete Code

```dart
import 'package:flutter/material.dart';
import 'package:hive_flutter/hive_flutter.dart';
import 'package:shared_preferences/shared_preferences.dart';
import 'package:path_provider/path_provider.dart';
import 'dart:io';
import 'package:intl/intl.dart';

void main() async {
  WidgetsFlutterBinding.ensureInitialized();
  await Hive.initFlutter();
  Hive.registerAdapter(NoteAdapter());
  Hive.registerAdapter(AppCategoryAdapter());
  await SharedPrefsService.init();
  runApp(const NotesProApp());
}

// ============ HIVE TYPE ADAPTERS ============
class NoteAdapter extends TypeAdapter<Note> {
  @override final int typeId = 0;

  @override
  Note read(BinaryReader reader) {
    return Note(
      id: reader.readString(),
      title: reader.readString(),
      content: reader.readString(),
      category: reader.readString(),
      colorValue: reader.readInt(),
      isPinned: reader.readBool(),
      isArchived: reader.readBool(),
      createdAt: DateTime.parse(reader.readString()),
      updatedAt: DateTime.parse(reader.readString()),
    );
  }

  @override
  void write(BinaryWriter writer, Note obj) {
    writer.writeString(obj.id);
    writer.writeString(obj.title);
    writer.writeString(obj.content);
    writer.writeString(obj.category);
    writer.writeInt(obj.colorValue);
    writer.writeBool(obj.isPinned);
    writer.writeBool(obj.isArchived);
    writer.writeString(obj.createdAt.toIso8601String());
    writer.writeString(obj.updatedAt.toIso8601String());
  }
}

class AppCategoryAdapter extends TypeAdapter<AppCategory> {
  @override final int typeId = 1;

  @override
  AppCategory read(BinaryReader reader) {
    return AppCategory(
      id: reader.readString(),
      name: reader.readString(),
      colorValue: reader.readInt(),
    );
  }

  @override
  void write(BinaryWriter writer, AppCategory obj) {
    writer.writeString(obj.id);
    writer.writeString(obj.name);
    writer.writeInt(obj.colorValue);
  }
}

// ============ MODELS ============
class Note {
  String id;
  String title;
  String content;
  String category;
  int colorValue;
  bool isPinned;
  bool isArchived;
  DateTime createdAt;
  DateTime updatedAt;

  Note({
    required this.id,
    required this.title,
    this.content = '',
    this.category = 'Personal',
    this.colorValue = 0xFF2196F3,
    this.isPinned = false,
    this.isArchived = false,
    required this.createdAt,
    required this.updatedAt,
  });

  Note copyWith({
    String? title, String? content, String? category,
    int? colorValue, bool? isPinned, bool? isArchived, DateTime? updatedAt,
  }) {
    return Note(
      id: id,
      title: title ?? this.title,
      content: content ?? this.content,
      category: category ?? this.category,
      colorValue: colorValue ?? this.colorValue,
      isPinned: isPinned ?? this.isPinned,
      isArchived: isArchived ?? this.isArchived,
      createdAt: createdAt,
      updatedAt: updatedAt ?? this.updatedAt,
    );
  }
}

class AppCategory {
  final String id;
  final String name;
  final int colorValue;
  AppCategory({required this.id, required this.name, required this.colorValue});
}

// ============ SHARED PREFERENCES SERVICE ============
class SharedPrefsService {
  static SharedPreferences? _prefs;
  static Future<void> init() async {
    _prefs = await SharedPreferences.getInstance();
  }
  static Future<bool> setString(String key, String value) async =>
      await _prefs!.setString(key, value);
  static String? getString(String key) => _prefs!.getString(key);
  static Future<bool> setBool(String key, bool value) async =>
      await _prefs!.setBool(key, value);
  static bool getBool(String key, {bool defaultValue = false}) =>
      _prefs!.getBool(key) ?? defaultValue;
}

// ============ HIVE SERVICE ============
class NotesHiveService {
  static const String _notesBoxName = 'notes_box';
  static const String _categoriesBoxName = 'categories_box';

  late Box<Note> _notesBox;
  late Box<AppCategory> _categoriesBox;

  Future<void> init() async {
    _notesBox = await Hive.openBox<Note>(_notesBoxName);
    _categoriesBox = await Hive.openBox<AppCategory>(_categoriesBoxName);

    if (_categoriesBox.isEmpty) {
      await _categoriesBox.putAll({
        'personal': AppCategory(id: 'personal', name: 'Personal', colorValue: 0xFF2196F3),
        'work': AppCategory(id: 'work', name: 'Work', colorValue: 0xFF4CAF50),
        'ideas': AppCategory(id: 'ideas', name: 'Ideas', colorValue: 0xFFFF9800),
        'shopping': AppCategory(id: 'shopping', name: 'Shopping', colorValue: 0xFFE91E63),
      });
    }
  }

  Future<void> addNote(Note note) async => await _notesBox.put(note.id, note);
  Note? getNote(String id) => _notesBox.get(id);
  Future<void> updateNote(Note note) async => await _notesBox.put(note.id, note);
  Future<void> deleteNote(String id) async => await _notesBox.delete(id);

  List<Note> getAllNotes() {
    return _notesBox.values.where((n) => !n.isArchived).toList()
      ..sort((a, b) => b.updatedAt.compareTo(a.updatedAt));
  }

  List<Note> getArchivedNotes() {
    return _notesBox.values.where((n) => n.isArchived).toList()
      ..sort((a, b) => b.updatedAt.compareTo(a.updatedAt));
  }

  List<Note> getNotesByCategory(String category) {
    return _notesBox.values
        .where((n) => n.category == category && !n.isArchived).toList()
      ..sort((a, b) => b.updatedAt.compareTo(a.updatedAt));
  }

  List<Note> searchNotes(String query) {
    final lower = query.toLowerCase();
    return _notesBox.values
        .where((n) => !n.isArchived &&
            (n.title.toLowerCase().contains(lower) ||
             n.content.toLowerCase().contains(lower)))
        .toList()
      ..sort((a, b) => b.updatedAt.compareTo(a.updatedAt));
  }

  int get noteCount => _notesBox.values.where((n) => !n.isArchived).length;
  int get archivedCount => _notesBox.values.where((n) => n.isArchived).length;

  List<AppCategory> getAllCategories() => _categoriesBox.values.toList();
  Future<void> addCategory(AppCategory cat) async => await _categoriesBox.put(cat.id, cat);
  Future<void> deleteCategory(String id) async => await _categoriesBox.delete(id);
}

// ============ APP ============
class NotesProApp extends StatefulWidget {
  const NotesProApp({super.key});
  @override State<NotesProApp> createState() => _NotesProAppState();
}

class _NotesProAppState extends State<NotesProApp> {
  final _hiveService = NotesHiveService();
  bool _isLoading = true;
  bool _isDarkMode = false;

  @override
  void initState() {
    super.initState();
    _initializeApp();
  }

  Future<void> _initializeApp() async {
    await _hiveService.init();
    final savedTheme = SharedPrefsService.getString('app_theme');
    setState(() {
      _isDarkMode = savedTheme == 'dark';
      _isLoading = false;
    });
  }

  void _toggleTheme() {
    setState(() => _isDarkMode = !_isDarkMode);
    SharedPrefsService.setString('app_theme', _isDarkMode ? 'dark' : 'light');
  }

  @override
  Widget build(BuildContext context) {
    if (_isLoading) {
      return const MaterialApp(
        home: Scaffold(body: Center(child: CircularProgressIndicator())),
      );
    }

    return MaterialApp(
      title: 'Notes Pro',
      debugShowCheckedModeBanner: false,
      themeMode: _isDarkMode ? ThemeMode.dark : ThemeMode.light,
      theme: ThemeData(
        useMaterial3: true,
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.indigo),
      ),
      darkTheme: ThemeData(
        useMaterial3: true,
        brightness: Brightness.dark,
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.indigo, brightness: Brightness.dark),
      ),
      home: NotesHomeScreen(
        hiveService: _hiveService,
        onThemeToggle: _toggleTheme,
        isDarkMode: _isDarkMode,
      ),
    );
  }
}

// ============ HOME SCREEN ============
class NotesHomeScreen extends StatefulWidget {
  final NotesHiveService hiveService;
  final VoidCallback onThemeToggle;
  final bool isDarkMode;

  const NotesHomeScreen({
    super.key,
    required this.hiveService,
    required this.onThemeToggle,
    required this.isDarkMode,
  });

  @override State<NotesHomeScreen> createState() => _NotesHomeScreenState();
}

class _NotesHomeScreenState extends State<NotesHomeScreen> {
  final _searchController = TextEditingController();
  String _selectedCategory = 'All';
  bool _showArchived = false;
  List<Note> _notes = [];
  List<AppCategory> _categories = [];

  @override
  void initState() {
    super.initState();
    _loadData();
  }

  void _loadData() {
    setState(() {
      _categories = widget.hiveService.getAllCategories();
      _refreshNotes();
    });
  }

  void _refreshNotes() {
    if (_showArchived) {
      _notes = widget.hiveService.getArchivedNotes();
    } else if (_searchController.text.isNotEmpty) {
      _notes = widget.hiveService.searchNotes(_searchController.text);
    } else if (_selectedCategory != 'All') {
      _notes = widget.hiveService.getNotesByCategory(_selectedCategory);
    } else {
      _notes = widget.hiveService.getAllNotes();
    }
  }

  @override
  Widget build(BuildContext context) {
    final colorScheme = Theme.of(context).colorScheme;

    return Scaffold(
      appBar: AppBar(
        title: const Text('Notes Pro'),
        centerTitle: true,
        elevation: 0,
        actions: [
          IconButton(
            icon: Icon(widget.isDarkMode ? Icons.light_mode : Icons.dark_mode),
            onPressed: widget.onThemeToggle,
          ),
          PopupMenuButton<String>(
            onSelected: (value) {
              if (value == 'archived') {
                setState(() { _showArchived = !_showArchived; _refreshNotes(); });
              } else if (value == 'export') { _exportNotes(); }
            },
            itemBuilder: (context) => [
              PopupMenuItem(
                value: 'archived',
                child: Row(children: [
                  Icon(_showArchived ? Icons.note : Icons.archive_outlined),
                  const SizedBox(width: 8),
                  Text(_showArchived ? 'Active Notes' : 'Archived'),
                ]),
              ),
              const PopupMenuItem(
                value: 'export',
                child: Row(children: [
                  Icon(Icons.download), SizedBox(width: 8), Text('Export to File'),
                ]),
              ),
            ],
          ),
        ],
      ),
      body: Column(
        children: [
          // Search Bar
          Padding(
            padding: const EdgeInsets.all(16),
            child: TextField(
              controller: _searchController,
              decoration: InputDecoration(
                hintText: 'Search notes...',
                prefixIcon: const Icon(Icons.search),
                suffixIcon: _searchController.text.isNotEmpty
                    ? IconButton(
                        icon: const Icon(Icons.clear),
                        onPressed: () {
                          _searchController.clear();
                          setState(() => _refreshNotes());
                        },
                      )
                    : null,
                filled: true,
                border: OutlineInputBorder(
                  borderRadius: BorderRadius.circular(16),
                  borderSide: BorderSide.none,
                ),
              ),
              onChanged: (_) => setState(() => _refreshNotes()),
            ),
          ),

          // Category Chips
          if (!_showArchived && _searchController.text.isEmpty)
            SizedBox(
              height: 50,
              child: ListView(
                scrollDirection: Axis.horizontal,
                padding: const EdgeInsets.symmetric(horizontal: 16),
                children: [
                  _CategoryChip(
                    label: 'All',
                    color: colorScheme.primary,
                    isSelected: _selectedCategory == 'All',
                    onTap: () => setState(() { _selectedCategory = 'All'; _refreshNotes(); }),
                  ),
                  ..._categories.map((cat) => _CategoryChip(
                    label: cat.name,
                    color: Color(cat.colorValue),
                    isSelected: _selectedCategory == cat.name,
                    onTap: () => setState(() { _selectedCategory = cat.name; _refreshNotes(); }),
                  )),
                ],
              ),
            ),

          // Stats Bar
          Padding(
            padding: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
            child: Row(
              children: [
                Text(
                  '${_notes.length} ${_showArchived ? 'archived' : 'notes'}',
                  style: TextStyle(color: Colors.grey.shade600),
                ),
                const Spacer(),
                if (!_showArchived)
                  Text(
                    '${widget.hiveService.archivedCount} archived',
                    style: TextStyle(color: Colors.grey.shade600, fontSize: 12),
                  ),
              ],
            ),
          ),

          // Notes List
          Expanded(
            child: _notes.isEmpty
                ? _EmptyState(showArchived: _showArchived)
                : ListView.builder(
                    padding: const EdgeInsets.all(16),
                    itemCount: _notes.length,
                    itemBuilder: (context, index) => _NoteCard(
                      note: _notes[index],
                      onTap: () => _openNoteEditor(_notes[index]),
                      onPin: () => _togglePin(_notes[index]),
                      onArchive: () => _toggleArchive(_notes[index]),
                      onDelete: () => _deleteNote(_notes[index]),
                    ),
                  ),
          ),
        ],
      ),
      floatingActionButton: FloatingActionButton.extended(
        onPressed: () => _openNoteEditor(null),
        icon: const Icon(Icons.add),
        label: const Text('New Note'),
      ),
    );
  }

  void _openNoteEditor(Note? note) async {
    final result = await Navigator.push(
      context,
      MaterialPageRoute(
        builder: (_) => NoteEditorScreen(
          note: note,
          hiveService: widget.hiveService,
          categories: _categories,
        ),
      ),
    );
    if (result == true) _loadData();
  }

  void _togglePin(Note note) async {
    final updated = note.copyWith(isPinned: !note.isPinned, updatedAt: DateTime.now());
    await widget.hiveService.updateNote(updated);
    _loadData();
  }

  void _toggleArchive(Note note) async {
    final updated = note.copyWith(isArchived: !note.isArchived, updatedAt: DateTime.now());
    await widget.hiveService.updateNote(updated);
    _loadData();
    ScaffoldMessenger.of(context).showSnackBar(
      SnackBar(
        content: Text(note.isArchived ? 'Note restored' : 'Note archived'),
        action: SnackBarAction(
          label: 'UNDO',
          onPressed: () => _toggleArchive(updated),
        ),
      ),
    );
  }

  void _deleteNote(Note note) async {
    await widget.hiveService.deleteNote(note.id);
    _loadData();
    ScaffoldMessenger.of(context).showSnackBar(
      const SnackBar(content: Text('Note deleted permanently')),
    );
  }

  Future<void> _exportNotes() async {
    final allNotes = widget.hiveService.getAllNotes();
    final buffer = StringBuffer();
    buffer.writeln('=== Notes Pro Export ===');
    buffer.writeln('Date: ${DateFormat('yyyy-MM-dd HH:mm').format(DateTime.now())}');
    buffer.writeln('Total Notes: ${allNotes.length}');
    buffer.writeln('');

    for (final note in allNotes) {
      buffer.writeln('--- ${note.title} ---');
      buffer.writeln('Category: ${note.category}');
      buffer.writeln('Created: ${DateFormat('yyyy-MM-dd').format(note.createdAt)}');
      buffer.writeln(note.content);
      buffer.writeln('');
    }

    final dir = await getApplicationDocumentsDirectory();
    final fileName = 'notes_export_${DateTime.now().millisecondsSinceEpoch}.txt';
    final file = File('${dir.path}/$fileName');
    await file.writeAsString(buffer.toString());

    if (mounted) {
      ScaffoldMessenger.of(context).showSnackBar(
        SnackBar(content: Text('Exported to: $fileName')),
      );
    }
  }

  @override
  void dispose() {
    _searchController.dispose();
    super.dispose();
  }
}

// ============ CATEGORY CHIP ============
class _CategoryChip extends StatelessWidget {
  final String label;
  final Color color;
  final bool isSelected;
  final VoidCallback onTap;

  const _CategoryChip({
    required this.label,
    required this.color,
    required this.isSelected,
    required this.onTap,
  });

  @override
  Widget build(BuildContext context) {
    return Padding(
      padding: const EdgeInsets.only(right: 8),
      child: InkWell(
        onTap: onTap,
        borderRadius: BorderRadius.circular(20),
        child: Container(
          padding: const EdgeInsets.symmetric(horizontal: 16, vertical: 8),
          decoration: BoxDecoration(
            color: isSelected ? color : color.withOpacity(0.1),
            borderRadius: BorderRadius.circular(20),
            border: Border.all(color: color.withOpacity(0.3)),
          ),
          child: Text(
            label,
            style: TextStyle(
              color: isSelected ? Colors.white : color,
              fontWeight: FontWeight.w600,
              fontSize: 13,
            ),
          ),
        ),
      ),
    );
  }
}

// ============ NOTE CARD ============
class _NoteCard extends StatelessWidget {
  final Note note;
  final VoidCallback onTap;
  final VoidCallback onPin;
  final VoidCallback onArchive;
  final VoidCallback onDelete;

  const _NoteCard({
    required this.note,
    required this.onTap,
    required this.onPin,
    required this.onArchive,
    required this.onDelete,
  });

  @override
  Widget build(BuildContext context) {
    final categoryColor = Color(note.colorValue);

    return Dismissible(
      key: Key(note.id),
      direction: DismissDirection.horizontal,
      confirmDismiss: (direction) async {
        if (direction == DismissDirection.startToEnd) {
          onArchive();
          return false;
        }
        return true;
      },
      background: Container(
        margin: const EdgeInsets.only(bottom: 12),
        decoration: BoxDecoration(
          color: Colors.orange.shade100,
          borderRadius: BorderRadius.circular(16),
        ),
        alignment: Alignment.centerLeft,
        padding: const EdgeInsets.only(left: 20),
        child: Icon(Icons.archive_outlined, color: Colors.orange.shade700),
      ),
      secondaryBackground: Container(
        margin: const EdgeInsets.only(bottom: 12),
        decoration: BoxDecoration(
          color: Colors.red.shade100,
          borderRadius: BorderRadius.circular(16),
        ),
        alignment: Alignment.centerRight,
        padding: const EdgeInsets.only(right: 20),
        child: Icon(Icons.delete_outline, color: Colors.red.shade700),
      ),
      onDismissed: (_) => onDelete(),
      child: Card(
        margin: const EdgeInsets.only(bottom: 12),
        elevation: 0,
        shape: RoundedRectangleBorder(
          borderRadius: BorderRadius.circular(16),
          side: BorderSide(color: Colors.grey.shade200),
        ),
        child: InkWell(
          onTap: onTap,
          borderRadius: BorderRadius.circular(16),
          child: Container(
            padding: const EdgeInsets.all(16),
            decoration: BoxDecoration(
              borderRadius: BorderRadius.circular(16),
              border: Border(left: BorderSide(color: categoryColor, width: 4)),
            ),
            child: Column(
              crossAxisAlignment: CrossAxisAlignment.start,
              children: [
                Row(
                  children: [
                    Expanded(
                      child: Text(
                        note.title,
                        style: const TextStyle(fontSize: 16, fontWeight: FontWeight.w600),
                        maxLines: 1,
                        overflow: TextOverflow.ellipsis,
                      ),
                    ),
                    if (note.isPinned)
                      Icon(Icons.push_pin, size: 18, color: categoryColor),
                  ],
                ),
                if (note.content.isNotEmpty) ...[
                  const SizedBox(height: 8),
                  Text(
                    note.content,
                    style: TextStyle(color: Colors.grey.shade600, fontSize: 14),
                    maxLines: 2,
                    overflow: TextOverflow.ellipsis,
                  ),
                ],
                const SizedBox(height: 12),
                Row(
                  children: [
                    Container(
                      padding: const EdgeInsets.symmetric(horizontal: 8, vertical: 2),
                      decoration: BoxDecoration(
                        color: categoryColor.withOpacity(0.1),
                        borderRadius: BorderRadius.circular(8),
                      ),
                      child: Text(
                        note.category,
                        style: TextStyle(color: categoryColor, fontSize: 11, fontWeight: FontWeight.w500),
                      ),
                    ),
                    const Spacer(),
                    Text(
                      DateFormat('MMM d').format(note.updatedAt),
                      style: TextStyle(color: Colors.grey.shade500, fontSize: 12),
                    ),
                  ],
                ),
              ],
            ),
          ),
        ),
      ),
    );
  }
}

// ============ EMPTY STATE ============
class _EmptyState extends StatelessWidget {
  final bool showArchived;
  const _EmptyState({required this.showArchived});

  @override
  Widget build(BuildContext context) {
    return Center(
      child: Column(
        mainAxisAlignment: MainAxisAlignment.center,
        children: [
          Icon(
            showArchived ? Icons.archive_outlined : Icons.note_add_outlined,
            size: 80,
            color: Colors.grey.shade400,
          ),
          const SizedBox(height: 16),
          Text(
            showArchived ? 'No archived notes' : 'No notes yet',
            style: TextStyle(fontSize: 18, color: Colors.grey.shade600, fontWeight: FontWeight.w500),
          ),
          const SizedBox(height: 8),
          Text(
            showArchived
                ? 'Archive notes to see them here'
                : 'Tap the + button to create your first note',
            style: TextStyle(color: Colors.grey.shade500),
          ),
        ],
      ),
    );
  }
}

// ============ NOTE EDITOR SCREEN ============
class NoteEditorScreen extends StatefulWidget {
  final Note? note;
  final NotesHiveService hiveService;
  final List<AppCategory> categories;

  const NoteEditorScreen({
    super.key,
    this.note,
    required this.hiveService,
    required this.categories,
  });

  @override State<NoteEditorScreen> createState() => _NoteEditorScreenState();
}

class _NoteEditorScreenState extends State<NoteEditorScreen> {
  late final TextEditingController _titleController;
  late final TextEditingController _contentController;
  late String _selectedCategory;
  late int _selectedColor;

  @override
  void initState() {
    super.initState();
    _titleController = TextEditingController(text: widget.note?.title ?? '');
    _contentController = TextEditingController(text: widget.note?.content ?? '');
    _selectedCategory = widget.note?.category ?? 'Personal';
    _selectedColor = widget.note?.colorValue ?? 0xFF2196F3;
  }

  @override
  Widget build(BuildContext context) {
    final isEditing = widget.note != null;

    return Scaffold(
      appBar: AppBar(
        title: Text(isEditing ? 'Edit Note' : 'New Note'),
        actions: [
          if (isEditing)
            IconButton(
              icon: const Icon(Icons.delete_outline),
              onPressed: () async {
                final confirm = await showDialog<bool>(
                  context: context,
                  builder: (_) => AlertDialog(
                    title: const Text('Delete Note?'),
                    content: const Text('This action cannot be undone.'),
                    actions: [
                      TextButton(
                        onPressed: () => Navigator.pop(context, false),
                        child: const Text('Cancel'),
                      ),
                      FilledButton(
                        onPressed: () => Navigator.pop(context, true),
                        child: const Text('Delete'),
                      ),
                    ],
                  ),
                );
                if (confirm == true) {
                  await widget.hiveService.deleteNote(widget.note!.id);
                  if (mounted) Navigator.pop(context, true);
                }
              },
            ),
          IconButton(
            icon: const Icon(Icons.check),
            onPressed: _saveNote,
          ),
        ],
      ),
      body: Padding(
        padding: const EdgeInsets.all(16),
        child: Column(
          children: [
            // Title
            TextField(
              controller: _titleController,
              decoration: const InputDecoration(
                hintText: 'Title',
                border: InputBorder.none,
                hintStyle: TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
              ),
              style: const TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
              maxLines: 1,
            ),
            const SizedBox(height: 8),

            // Category Selector
            SizedBox(
              height: 40,
              child: ListView(
                scrollDirection: Axis.horizontal,
                children: widget.categories.map((cat) {
                  final isSelected = _selectedCategory == cat.name;
                  return Padding(
                    padding: const EdgeInsets.only(right: 8),
                    child: ChoiceChip(
                      label: Text(cat.name),
                      selected: isSelected,
                      onSelected: (_) {
                        setState(() {
                          _selectedCategory = cat.name;
                          _selectedColor = cat.colorValue;
                        });
                      },
                      selectedColor: Color(cat.colorValue),
                      labelStyle: TextStyle(
                        color: isSelected ? Colors.white : Color(cat.colorValue),
                        fontWeight: FontWeight.w600,
                      ),
                    ),
                  );
                }).toList(),
              ),
            ),
            const Divider(),

            // Content
            Expanded(
              child: TextField(
                controller: _contentController,
                decoration: const InputDecoration(
                  hintText: 'Start typing...',
                  border: InputBorder.none,
                ),
                style: const TextStyle(fontSize: 16, height: 1.5),
                maxLines: null,
                expands: true,
                textAlignVertical: TextAlignVertical.top,
              ),
            ),
          ],
        ),
      ),
    );
  }

  void _saveNote() async {
    if (_titleController.text.trim().isEmpty) {
      ScaffoldMessenger.of(context).showSnackBar(
        const SnackBar(content: Text('Please enter a title')),
      );
      return;
    }

    final now = DateTime.now();
    if (widget.note != null) {
      final updated = widget.note!.copyWith(
        title: _titleController.text.trim(),
        content: _contentController.text.trim(),
        category: _selectedCategory,
        colorValue: _selectedColor,
        updatedAt: now,
      );
      await widget.hiveService.updateNote(updated);
    } else {
      final newNote = Note(
        id: now.millisecondsSinceEpoch.toString(),
        title: _titleController.text.trim(),
        content: _contentController.text.trim(),
        category: _selectedCategory,
        colorValue: _selectedColor,
        createdAt: now,
        updatedAt: now,
      );
      await widget.hiveService.addNote(newNote);
    }

    if (mounted) Navigator.pop(context, true);
  }

  @override
  void dispose() {
    _titleController.dispose();
    _contentController.dispose();
    super.dispose();
  }
}
```

---

# 11. Common Mistakes & How to Avoid Them

## Mistake 1: Not Initializing SharedPreferences Before Use
```dart
// WRONG - Will crash with NullPointerException
void main() {
  runApp(const MyApp()); // SharedPrefs not initialized!
}

// CORRECT - Initialize in main() before runApp
void main() async {
  WidgetsFlutterBinding.ensureInitialized();
  await SharedPrefsService.init();
  runApp(const MyApp());
}
```

## Mistake 2: Forgetting to Register Hive Adapters
```dart
// WRONG - Adapter not registered
void main() async {
  await Hive.initFlutter();
  // Missing: Hive.registerAdapter(NoteAdapter());
  await Hive.openBox<Note>('notes'); // CRASH!
  runApp(const MyApp());
}

// CORRECT - Register before opening boxes
void main() async {
  await Hive.initFlutter();
  Hive.registerAdapter(NoteAdapter());
  await Hive.openBox<Note>('notes');
  runApp(const MyApp());
}
```

## Mistake 3: Storing Sensitive Data in SharedPreferences
```dart
// WRONG - Not encrypted, easily accessible
await SharedPrefsService.setString('password', userPassword);

// CORRECT - Use flutter_secure_storage
await SecureStorageService.setCredentials(email, password);
```

## Mistake 4: Not Closing Database Connections
```dart
// WRONG - Memory leak, potential data corruption
class DatabaseHelper {
  Future<Database> get database async {
    return await openDatabase('app.db'); // Opens new connection every time!
  }
}

// CORRECT - Singleton pattern with proper cleanup
class DatabaseHelper {
  static Database? _database;
  Future<Database> get database async {
    _database ??= await _initDatabase();
    return _database!;
  }
  Future<void> close() async {
    await _database?.close();
    _database = null;
  }
}
```

## Mistake 5: Blocking the UI Thread with Heavy DB Operations
```dart
// WRONG - Blocks UI, causes jank
@override
Widget build(BuildContext context) {
  final notes = hiveService.getAllNotes(); // Synchronous, blocks UI
  return ListView(...);
}

// CORRECT - Use async/await or FutureBuilder
@override
Widget build(BuildContext context) {
  return FutureBuilder(
    future: hiveService.getAllNotesAsync(),
    builder: (context, snapshot) {
      if (snapshot.hasData) return ListView(...);
      return const CircularProgressIndicator();
    },
  );
}
```

## Mistake 6: Not Handling Database Migrations in sqflite
```dart
// WRONG - Users with old schema will crash
onUpgrade: (db, oldVersion, newVersion) async {
  // Empty - no migration logic!
}

// CORRECT - Version-by-version migration
onUpgrade: (db, oldVersion, newVersion) async {
  if (oldVersion < 2) {
    await db.execute('ALTER TABLE notes ADD COLUMN tags TEXT');
  }
  if (oldVersion < 3) {
    await db.execute('ALTER TABLE notes ADD COLUMN reminder_date TEXT');
  }
}
```

## Mistake 7: Storing Large Objects in SharedPreferences
```dart
// WRONG - SharedPreferences has ~1-2MB limit per key
final largeJson = jsonEncode(hugeListOfObjects);
await prefs.setString('cache', largeJson); // May fail silently

// CORRECT - Use Hive or sqflite for large data
await hiveBox.put('cache', hugeListOfObjects);
```

---

# 12. Day 15 Checklist

Use this checklist to verify mastery:
- [ ] Understands why local persistence is critical for offline-first apps
- [ ] Can choose the right storage solution for any scenario
- [ ] Can set up and use SharedPreferences for simple settings
- [ ] Can store and retrieve complex objects as JSON in SharedPreferences
- [ ] Can use path_provider to read/write files to the device
- [ ] Can export app data to text files
- [ ] Can create and manage an SQLite database with sqflite
- [ ] Can write SQL queries for filtering, searching, and joining data
- [ ] Can handle database migrations when schema changes
- [ ] Can set up Hive with type adapters and code generation
- [ ] Can perform CRUD operations with Hive boxes
- [ ] Can use encrypted Hive boxes for sensitive data
- [ ] Can set up drift with type-safe SQL tables
- [ ] Can use flutter_secure_storage for encrypted token storage
- [ ] Understands the offline-first repository pattern
- [ ] Built the Notes Pro app with Hive + SharedPreferences + path_provider
- [ ] App has categories with custom colors
- [ ] App has full-text search across notes
- [ ] App supports pin, archive, and delete with swipe actions
- [ ] App persists theme preference across app restarts
- [ ] App can export notes to a text file
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **SharedPreferences = Settings only** - Never store large data or sensitive info. Best for flags, themes, and small configs.
2. **Hive = Speed king** - Fastest local DB in Flutter. Perfect for caching, simple objects, and structured data without complex queries.
3. **sqflite = Full SQL power** - When you need JOINs, complex WHERE clauses, and relational data with foreign keys.
4. **drift = Type-safe SQL** - The enterprise choice. Compile-time query validation, auto-generated code, and reactive streams.
5. **flutter_secure_storage = Secrets only** - JWT tokens, API keys, passwords. Uses OS-level encryption (Keychain/Keystore).
6. **path_provider = File system** - For images, PDFs, exports, and any large binary data.
7. **Always initialize before runApp()** - SharedPreferences, Hive, and drift all need async initialization.
8. **Offline-first architecture** - Save locally first, sync to cloud in background. Queue failed syncs for retry.
9. **Close your databases** - Use singleton pattern and close connections on app termination to prevent corruption.
10. **Never store passwords in plain text** - Even in local databases. Use secure storage or proper hashing.

---

# Extra Practice (Do These Tonight!)

1. **Todo App with Hive:** Build a todo manager with categories, priorities, due dates, and reminders using Hive. Add dark mode persistence with SharedPreferences.
2. **Expense Tracker with sqflite:** Create an expense tracker with categories, monthly summaries, and charts. Use SQL queries for aggregation (SUM, GROUP BY).
3. **Journal App with drift:** Build a daily journal app using drift with reactive queries. Auto-save drafts and support rich text entries.
4. **Password Manager:** Use flutter_secure_storage + encrypted Hive to build a password manager with biometric authentication.
5. **Offline News Reader:** Cache API responses in Hive, display cached articles when offline, and sync read status when online.

---

**Congratulations!** You've completed Day 15. You now master every local data persistence technique in Flutter — from simple key-value pairs to full SQL databases and lightning-fast NoSQL. You can build offline-first apps that work flawlessly without internet.

**Next Up -> Day 16: Networking & APIs (http, dio, REST integration)**

---

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 15: Local Data Persistence - Complete Deep Dive*
# Day 16: Networking & APIs
## Complete Deep Dive

**Goal:** Master connecting Flutter apps to the internet. Learn the http vs dio debate, REST API integration, JSON parsing with code generation, error handling with retry logic, interceptors, and build a production-grade GitHub User Search app with pagination, caching, and robust error states.

---

# Table of Contents
1. Why Networking Architecture Matters
2. HTTP Fundamentals for Flutter Developers
3. http Package — The Built-in Choice
4. dio Package — The Production Standard
5. REST API Integration Patterns
6. JSON Parsing: Manual vs Code Generation
7. freezed + json_serializable — Immutable Data Classes
8. Error Handling & Retry Logic
9. dio Interceptors — Logging, Auth, Caching
10. Pagination Patterns
11. Architecture: Repository + Data Source
12. Hands-On Project: GitHub User Search Pro
13. Common Mistakes & How to Avoid Them
14. Day 16 Checklist

---

# 1. Why Networking Architecture Matters

## The Reality of Mobile Networks
```
User Tap -> API Request -> [2G/3G/4G/5G/WiFi] -> Server -> Response -> Parse -> UI
                    |
                    +-> No Internet -> Retry / Cache / Error UI
                    +-> Slow Network -> Timeout / Loading Skeleton
                    +-> Server Error -> 500 / 503 -> Fallback
                    +-> Auth Expired -> 401 -> Refresh Token -> Retry
```

## What Can Go Wrong
| Problem | Cause | Solution |
|---|---|---|
| App crashes on API call | Null safety violations in JSON | Code generation + null checks |
| Slow UI on slow network | Synchronous parsing on main thread | Async/await + isolate for heavy parsing |
| Token expires silently | No interceptor for 401 | dio interceptor + refresh token flow |
| Duplicate requests | User double-taps button | Debounce + loading states |
| Memory leaks | Streams not cancelled | CancelToken in dio |
| No offline support | No cache layer | dio cache interceptor + local DB |

## http vs dio: The 2026 Verdict
| Feature | http | dio |
|---|---|---|
| **Ease of Use** | Simple, beginner-friendly | More setup, more power |
| **Interceptors** | Manual | Built-in (request/response/error) |
| **Global Config** | Per-request | Base options, global headers |
| **File Upload/Download** | Manual multipart | Built-in FormData, progress |
| **Cancel Tokens** | No | Yes (prevents memory leaks) |
| **Retry Logic** | Manual | Built-in + interceptors |
| **Cache** | Manual | Built-in cache interceptor |
| **Transformer** | No | Yes (custom request/response handling) |
| **When to Use** | Simple GET/POST demos | Production apps, complex APIs |
| **2026 Recommendation** | Learning only | **Production standard** |

---

# 2. HTTP Fundamentals for Flutter Developers

## HTTP Methods
| Method | Use Case | Idempotent? |
|---|---|---|
| GET | Retrieve data | Yes |
| POST | Create resource | No |
| PUT | Full update | Yes |
| PATCH | Partial update | No |
| DELETE | Remove resource | Yes |

## Status Codes You Must Know
| Code | Meaning | Flutter Action |
|---|---|---|
| 200 | OK | Parse and display |
| 201 | Created | Show success, navigate |
| 400 | Bad Request | Show validation errors |
| 401 | Unauthorized | Refresh token or login |
| 403 | Forbidden | Show permission error |
| 404 | Not Found | Show "not found" UI |
| 429 | Too Many Requests | Retry with backoff |
| 500 | Server Error | Show "server error" retry |
| 503 | Service Unavailable | Retry later |

## Headers Every Request Needs
```dart
const headers = {
  'Content-Type': 'application/json',     // Tell server we're sending JSON
  'Accept': 'application/json',           // Tell server we want JSON back
  'Authorization': 'Bearer $token',       // Auth token
  'X-Request-ID': 'uuid',               // Traceability
};
```

---

# 3. http Package — The Built-in Choice

## Package Setup
```yaml
dependencies:
  http: ^1.2.1
```

## Basic CRUD Operations
```dart
import 'package:http/http.dart' as http;
import 'dart:convert';

class HttpUserService {
  static const String _baseUrl = 'https://jsonplaceholder.typicode.com';

  // GET
  static Future<List<dynamic>> fetchUsers() async {
    final response = await http.get(Uri.parse('$_baseUrl/users'));
    if (response.statusCode == 200) {
      return jsonDecode(response.body);
    }
    throw Exception('Failed to load users: ${response.statusCode}');
  }

  // GET by ID
  static Future<Map<String, dynamic>> fetchUser(int id) async {
    final response = await http.get(Uri.parse('$_baseUrl/users/$id'));
    if (response.statusCode == 200) {
      return jsonDecode(response.body);
    }
    throw Exception('Failed to load user');
  }

  // POST
  static Future<Map<String, dynamic>> createUser(Map<String, dynamic> user) async {
    final response = await http.post(
      Uri.parse('$_baseUrl/users'),
      headers: {'Content-Type': 'application/json'},
      body: jsonEncode(user),
    );
    if (response.statusCode == 201) {
      return jsonDecode(response.body);
    }
    throw Exception('Failed to create user');
  }

  // PUT (Full Update)
  static Future<Map<String, dynamic>> updateUser(int id, Map<String, dynamic> user) async {
    final response = await http.put(
      Uri.parse('$_baseUrl/users/$id'),
      headers: {'Content-Type': 'application/json'},
      body: jsonEncode(user),
    );
    if (response.statusCode == 200) {
      return jsonDecode(response.body);
    }
    throw Exception('Failed to update user');
  }

  // DELETE
  static Future<void> deleteUser(int id) async {
    final response = await http.delete(Uri.parse('$_baseUrl/users/$id'));
    if (response.statusCode != 200) {
      throw Exception('Failed to delete user');
    }
  }
}
```

## Limitations of http
- No built-in interceptors
- No global configuration
- No cancel tokens
- No retry mechanism
- Manual error handling for every call

---

# 4. dio Package — The Production Standard

## Package Setup
```yaml
dependencies:
  dio: ^5.4.3+1
  pretty_dio_logger: ^1.3.1  # For debugging

dev_dependencies:
  retrofit_generator: ^8.1.0  # Optional: Type-safe API clients
  build_runner: ^2.4.9
```

## dio Configuration (Global Setup)
```dart
import 'package:dio/dio.dart';
import 'package:pretty_dio_logger/pretty_dio_logger.dart';

class DioClient {
  static Dio? _dio;

  static Dio get instance {
    _dio ??= _createDio();
    return _dio!;
  }

  static Dio _createDio() {
    final dio = Dio(
      BaseOptions(
        baseUrl: 'https://api.github.com',
        connectTimeout: const Duration(seconds: 10),
        receiveTimeout: const Duration(seconds: 10),
        sendTimeout: const Duration(seconds: 10),
        headers: {
          'Accept': 'application/vnd.github.v3+json',
          'Content-Type': 'application/json',
        },
        validateStatus: (status) => status != null && status < 500,
      ),
    );

    // Add interceptors
    dio.interceptors.addAll([
      PrettyDioLogger(
        requestHeader: true,
        requestBody: true,
        responseBody: true,
        responseHeader: false,
        compact: true,
      ),
      _AuthInterceptor(),
      _ErrorInterceptor(),
    ]);

    return dio;
  }

  static void setAuthToken(String token) {
    instance.options.headers['Authorization'] = 'Bearer $token';
  }

  static void clearAuthToken() {
    instance.options.headers.remove('Authorization');
  }
}
```

## CRUD with dio
```dart
class GitHubApiService {
  final Dio _dio = DioClient.instance;

  // GET with query parameters
  Future<List<GitHubUser>> searchUsers(String query, {int page = 1, int perPage = 30}) async {
    final response = await _dio.get(
      '/search/users',
      queryParameters: {
        'q': query,
        'page': page,
        'per_page': perPage,
      },
    );

    final items = response.data['items'] as List<dynamic>;
    return items.map((json) => GitHubUser.fromJson(json)).toList();
  }

  // GET single user
  Future<GitHubUserDetail> getUserDetail(String username) async {
    final response = await _dio.get('/users/$username');
    return GitHubUserDetail.fromJson(response.data);
  }

  // POST with FormData (file upload)
  Future<void> uploadFile(String filePath) async {
    final formData = FormData.fromMap({
      'file': await MultipartFile.fromFile(filePath, filename: 'avatar.jpg'),
      'description': 'My avatar',
    });

    await _dio.post('/upload', data: formData);
  }

  // Download with progress
  Future<void> downloadFile(String url, String savePath) async {
    await _dio.download(
      url,
      savePath,
      onReceiveProgress: (received, total) {
        if (total != -1) {
          final progress = (received / total * 100).toStringAsFixed(0);
          debugPrint('Download progress: $progress%');
        }
      },
    );
  }

  // Cancelable request
  Future<List<GitHubUser>> searchUsersCancelable(
    String query, {
    required CancelToken cancelToken,
  }) async {
    final response = await _dio.get(
      '/search/users',
      queryParameters: {'q': query, 'per_page': 30},
      cancelToken: cancelToken,
    );
    final items = response.data['items'] as List<dynamic>;
    return items.map((json) => GitHubUser.fromJson(json)).toList();
  }
}
```

---

# 5. REST API Integration Patterns

## Pattern 1: Direct Service Call (Simple)
```dart
// UI directly calls API service
class UserListScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return FutureBuilder(
      future: GitHubApiService().searchUsers('flutter'),
      builder: (context, snapshot) {
        if (snapshot.hasData) return UserList(users: snapshot.data!);
        if (snapshot.hasError) return ErrorWidget(error: snapshot.error);
        return const LoadingWidget();
      },
    );
  }
}
```

## Pattern 2: Repository Pattern (Production)
```dart
// Domain layer - abstract
abstract class UserRepository {
  Future<List<GitHubUser>> searchUsers(String query, {int page = 1});
  Future<GitHubUserDetail> getUserDetail(String username);
}

// Data layer - implementation
class UserRepositoryImpl implements UserRepository {
  final GitHubApiService _apiService;
  final LocalCacheService _cacheService;

  UserRepositoryImpl(this._apiService, this._cacheService);

  @override
  Future<List<GitHubUser>> searchUsers(String query, {int page = 1}) async {
    // Try cache first
    final cached = await _cacheService.getCachedUsers(query, page);
    if (cached != null) return cached;

    // Fetch from API
    final users = await _apiService.searchUsers(query, page: page);

    // Save to cache
    await _cacheService.cacheUsers(query, page, users);

    return users;
  }

  @override
  Future<GitHubUserDetail> getUserDetail(String username) async {
    return await _apiService.getUserDetail(username);
  }
}
```

## Pattern 3: Data Source Pattern (Clean Architecture)
```dart
abstract class UserRemoteDataSource {
  Future<List<GitHubUser>> searchUsers(String query, int page);
}

abstract class UserLocalDataSource {
  Future<List<GitHubUser>> getCachedUsers(String query, int page);
  Future<void> cacheUsers(String query, int page, List<GitHubUser> users);
}

class UserRemoteDataSourceImpl implements UserRemoteDataSource {
  final Dio _dio;
  UserRemoteDataSourceImpl(this._dio);

  @override
  Future<List<GitHubUser>> searchUsers(String query, int page) async {
    final response = await _dio.get('/search/users', queryParameters: {
      'q': query,
      'page': page,
      'per_page': 30,
    });
    return (response.data['items'] as List)
        .map((e) => GitHubUser.fromJson(e))
        .toList();
  }
}
```

---

# 6. JSON Parsing: Manual vs Code Generation

## Manual Parsing (Error-Prone)
```dart
class GitHubUser {
  final String login;
  final String avatarUrl;
  final String htmlUrl;

  GitHubUser({required this.login, required this.avatarUrl, required this.htmlUrl});

  // Manual - easy to make mistakes
  factory GitHubUser.fromJson(Map<String, dynamic> json) {
    return GitHubUser(
      login: json['login'] ?? '',
      avatarUrl: json['avatar_url'] ?? '',  // snake_case to camelCase manually
      htmlUrl: json['html_url'] ?? '',
    );
  }

  Map<String, dynamic> toJson() {
    return {
      'login': login,
      'avatar_url': avatarUrl,
      'html_url': htmlUrl,
    };
  }
}
```

## Code Generation with json_serializable (Recommended)
```dart
import 'package:json_annotation/json_annotation.dart';

part 'github_user.g.dart'; // Generated file

@JsonSerializable()
class GitHubUser {
  final String login;

  @JsonKey(name: 'avatar_url')
  final String avatarUrl;

  @JsonKey(name: 'html_url')
  final String htmlUrl;

  @JsonKey(name: 'type')
  final String userType;

  GitHubUser({
    required this.login,
    required this.avatarUrl,
    required this.htmlUrl,
    required this.userType,
  });

  factory GitHubUser.fromJson(Map<String, dynamic> json) =>
      _$GitHubUserFromJson(json);

  Map<String, dynamic> toJson() => _$GitHubUserToJson(this);
}
```

## Run Code Generation
```bash
dart run build_runner build        # One-time
dart run build_runner watch        # Auto-regenerate on file changes
```

---

# 7. freezed + json_serializable — Immutable Data Classes

## Why freezed?
- **Immutable** objects (no accidental mutations)
- **Value equality** (== and hashCode auto-generated)
- **CopyWith** method for easy object updates
- **Union types** for sealed classes (loading, error, success)
- **toString** auto-generated for debugging

## Package Setup
```yaml
dependencies:
  freezed_annotation: ^2.4.1
  json_annotation: ^4.9.0

dev_dependencies:
  freezed: ^2.5.2
  json_serializable: ^6.8.0
  build_runner: ^2.4.9
```

## Model with freezed
```dart
import 'package:freezed_annotation/freezed_annotation.dart';

part 'github_user.freezed.dart';
part 'github_user.g.dart';

@freezed
class GitHubUser with _$GitHubUser {
  const factory GitHubUser({
    required String login,
    @JsonKey(name: 'avatar_url') required String avatarUrl,
    @JsonKey(name: 'html_url') required String htmlUrl,
    @JsonKey(name: 'type') required String userType,
    @Default(0) int id,
  }) = _GitHubUser;

  factory GitHubUser.fromJson(Map<String, dynamic> json) =>
      _$GitHubUserFromJson(json);
}

@freezed
class GitHubUserDetail with _$GitHubUserDetail {
  const factory GitHubUserDetail({
    required String login,
    @JsonKey(name: 'avatar_url') required String avatarUrl,
    @JsonKey(name: 'html_url') required String htmlUrl,
    @JsonKey(name: 'name') String? displayName,
    @JsonKey(name: 'bio') String? biography,
    @JsonKey(name: 'public_repos') @Default(0) int publicRepos,
    @JsonKey(name: 'public_gists') @Default(0) int publicGists,
    @JsonKey(name: 'followers') @Default(0) int followers,
    @JsonKey(name: 'following') @Default(0) int following,
    @JsonKey(name: 'created_at') required DateTime createdAt,
    @JsonKey(name: 'location') String? location,
    @JsonKey(name: 'company') String? company,
    @JsonKey(name: 'blog') String? blog,
  }) = _GitHubUserDetail;

  factory GitHubUserDetail.fromJson(Map<String, dynamic> json) =>
      _$GitHubUserDetailFromJson(json);
}

// API Response wrapper
@freezed
class ApiResponse<T> with _$ApiResponse<T> {
  const factory ApiResponse.loading() = ApiLoading;
  const factory ApiResponse.data(T data) = ApiData<T>;
  const factory ApiResponse.error(String message, {int? statusCode}) = ApiError;
}
```

## Using freezed Models
```dart
// Create
final user = GitHubUser(login: 'octocat', avatarUrl: '...', htmlUrl: '...', userType: 'User');

// Copy with changes
final updated = user.copyWith(login: 'newName');

// Equality check
final userA = GitHubUser(login: 'a', avatarUrl: '...', htmlUrl: '...', userType: 'User');
final userB = GitHubUser(login: 'a', avatarUrl: '...', htmlUrl: '...', userType: 'User');
print(userA == userB); // true (value equality)

// JSON
final json = user.toJson();
final fromJson = GitHubUser.fromJson(json);
```

---

# 8. Error Handling & Retry Logic

## Custom Exceptions
```dart
abstract class AppException implements Exception {
  final String message;
  final int? statusCode;
  AppException(this.message, {this.statusCode});

  @override
  String toString() => 'AppException: $message (Status: $statusCode)';
}

class NetworkException extends AppException {
  NetworkException() : super('No internet connection');
}

class ServerException extends AppException {
  ServerException(String message, {int? statusCode})
      : super(message, statusCode: statusCode);
}

class UnauthorizedException extends AppException {
  UnauthorizedException() : super('Session expired. Please login again.', statusCode: 401);
}

class NotFoundException extends AppException {
  NotFoundException() : super('Resource not found', statusCode: 404);
}

class RateLimitException extends AppException {
  RateLimitException() : super('Too many requests. Please try again later.', statusCode: 429);
}
```

## dio Error Interceptor
```dart
class _ErrorInterceptor extends Interceptor {
  @override
  void onError(DioException err, ErrorInterceptorHandler handler) async {
    switch (err.type) {
      case DioExceptionType.connectionTimeout:
      case DioExceptionType.sendTimeout:
      case DioExceptionType.receiveTimeout:
        throw NetworkException();

      case DioExceptionType.badResponse:
        final statusCode = err.response?.statusCode;
        final message = err.response?.data?['message'] ?? 'Unknown error';

        switch (statusCode) {
          case 400:
            throw ServerException(message, statusCode: statusCode);
          case 401:
            throw UnauthorizedException();
          case 404:
            throw NotFoundException();
          case 429:
            throw RateLimitException();
          case 500:
          case 503:
            throw ServerException('Server error. Please try again later.', statusCode: statusCode);
          default:
            throw ServerException(message, statusCode: statusCode);
        }

      case DioExceptionType.connectionError:
        throw NetworkException();

      default:
        throw ServerException('Something went wrong');
    }
  }
}
```

## Retry Logic with Exponential Backoff
```dart
class RetryInterceptor extends Interceptor {
  final int maxRetries;
  final Duration baseDelay;

  RetryInterceptor({this.maxRetries = 3, this.baseDelay = const Duration(seconds: 1)});

  @override
  void onError(DioException err, ErrorInterceptorHandler handler) async {
    if (_shouldRetry(err) && err.requestOptions.extra['retry_count'] != maxRetries) {
      final retryCount = (err.requestOptions.extra['retry_count'] ?? 0) + 1;
      final delay = baseDelay * retryCount; // Exponential backoff

      debugPrint('Retrying request (attempt $retryCount) after ${delay.inSeconds}s...');
      await Future.delayed(delay);

      try {
        final response = await DioClient.instance.fetch(
          err.requestOptions..extra['retry_count'] = retryCount,
        );
        handler.resolve(response);
      } catch (e) {
        handler.next(err);
      }
    } else {
      handler.next(err);
    }
  }

  bool _shouldRetry(DioException err) {
    return err.type == DioExceptionType.connectionTimeout ||
           err.type == DioExceptionType.receiveTimeout ||
           (err.response?.statusCode ?? 0) >= 500;
  }
}
```

---

# 9. dio Interceptors — Logging, Auth, Caching

## Auth Interceptor (Token Refresh)
```dart
class _AuthInterceptor extends Interceptor {
  bool _isRefreshing = false;
  final List<Function> _pendingRequests = [];

  @override
  void onRequest(RequestOptions options, RequestInterceptorHandler handler) async {
    final token = await SecureStorageService.getAuthToken();
    if (token != null) {
      options.headers['Authorization'] = 'Bearer $token';
    }
    handler.next(options);
  }

  @override
  void onError(DioException err, ErrorInterceptorHandler handler) async {
    if (err.response?.statusCode == 401) {
      final originalRequest = err.requestOptions;

      if (_isRefreshing) {
        // Queue request while token is being refreshed
        _pendingRequests.add(() async {
          final token = await SecureStorageService.getAuthToken();
          originalRequest.headers['Authorization'] = 'Bearer $token';
          final response = await DioClient.instance.fetch(originalRequest);
          handler.resolve(response);
        });
        return;
      }

      _isRefreshing = true;

      try {
        // Refresh token
        final newToken = await _refreshToken();
        await SecureStorageService.setAuthToken(newToken);

        // Retry original request
        originalRequest.headers['Authorization'] = 'Bearer $newToken';
        final response = await DioClient.instance.fetch(originalRequest);

        // Execute pending requests
        for (final request in _pendingRequests) {
          await request();
        }
        _pendingRequests.clear();

        handler.resolve(response);
      } catch (e) {
        // Refresh failed - logout user
        await SecureStorageService.clearAll();
        _pendingRequests.clear();
        handler.next(err);
      } finally {
        _isRefreshing = false;
      }
    } else {
      handler.next(err);
    }
  }

  Future<String> _refreshToken() async {
    final refreshToken = await SecureStorageService.getRefreshToken();
    final response = await Dio().post(
      'https://api.example.com/auth/refresh',
      data: {'refresh_token': refreshToken},
    );
    return response.data['access_token'];
  }
}
```

## Cache Interceptor
```dart
class CacheInterceptor extends Interceptor {
  final Map<String, Response> _cache = {};
  final Duration cacheDuration;

  CacheInterceptor({this.cacheDuration = const Duration(minutes: 5)});

  @override
  void onRequest(RequestOptions options, RequestInterceptorHandler handler) {
    if (options.method == 'GET' && options.extra['cache'] == true) {
      final cacheKey = '${options.path}?${options.queryParameters}';
      final cached = _cache[cacheKey];

      if (cached != null) {
        final age = DateTime.now().difference(cached.extra['cached_at'] as DateTime);
        if (age < cacheDuration) {
          debugPrint('Cache hit: $cacheKey');
          return handler.resolve(cached);
        }
      }
    }
    handler.next(options);
  }

  @override
  void onResponse(Response response, ResponseInterceptorHandler handler) {
    if (response.requestOptions.method == 'GET' &&
        response.requestOptions.extra['cache'] == true) {
      final cacheKey = '${response.requestOptions.path}?${response.requestOptions.queryParameters}';
      response.extra['cached_at'] = DateTime.now();
      _cache[cacheKey] = response;
      debugPrint('Cache stored: $cacheKey');
    }
    handler.next(response);
  }
}
```

---

# 10. Pagination Patterns

## Pattern 1: Offset-Based Pagination (Page + PerPage)
```dart
class PaginatedResponse<T> {
  final List<T> items;
  final int currentPage;
  final int totalPages;
  final int totalItems;
  final bool hasMore;

  PaginatedResponse({
    required this.items,
    required this.currentPage,
    required this.totalPages,
    required this.totalItems,
    required this.hasMore,
  });
}

// Usage
Future<PaginatedResponse<GitHubUser>> searchUsersPaginated(
  String query, {
  required int page,
  int perPage = 30,
}) async {
  final response = await dio.get('/search/users', queryParameters: {
    'q': query,
    'page': page,
    'per_page': perPage,
  });

  final totalCount = response.data['total_count'] as int;
  final items = (response.data['items'] as List)
      .map((e) => GitHubUser.fromJson(e))
      .toList();

  return PaginatedResponse(
    items: items,
    currentPage: page,
    totalPages: (totalCount / perPage).ceil(),
    totalItems: totalCount,
    hasMore: items.length == perPage,
  );
}
```

## Pattern 2: Cursor-Based Pagination (Infinite Scroll)
```dart
class CursorPaginatedResponse<T> {
  final List<T> items;
  final String? nextCursor;
  final bool hasMore;

  CursorPaginatedResponse({
    required this.items,
    this.nextCursor,
    required this.hasMore,
  });
}

// Usage with ListView.builder
class PaginatedListScreen<T> extends StatefulWidget {
  final Future<CursorPaginatedResponse<T>> Function(String? cursor) fetchPage;
  final Widget Function(T item) itemBuilder;

  const PaginatedListScreen({
    super.key,
    required this.fetchPage,
    required this.itemBuilder,
  });

  @override
  State<PaginatedListScreen> createState() => _PaginatedListScreenState<T>();
}

class _PaginatedListScreenState<T> extends State<PaginatedListScreen<T>> {
  final List<T> _items = [];
  String? _nextCursor;
  bool _isLoading = false;
  bool _hasMore = true;
  final _scrollController = ScrollController();

  @override
  void initState() {
    super.initState();
    _loadMore();
    _scrollController.addListener(_onScroll);
  }

  void _onScroll() {
    if (_scrollController.position.pixels >=
        _scrollController.position.maxScrollExtent - 200) {
      _loadMore();
    }
  }

  Future<void> _loadMore() async {
    if (_isLoading || !_hasMore) return;

    setState(() => _isLoading = true);

    try {
      final response = await widget.fetchPage(_nextCursor);
      setState(() {
        _items.addAll(response.items);
        _nextCursor = response.nextCursor;
        _hasMore = response.hasMore;
        _isLoading = false;
      });
    } catch (e) {
      setState(() => _isLoading = false);
    }
  }

  @override
  Widget build(BuildContext context) {
    return ListView.builder(
      controller: _scrollController,
      itemCount: _items.length + (_hasMore ? 1 : 0),
      itemBuilder: (context, index) {
        if (index >= _items.length) {
          return const Center(child: CircularProgressIndicator());
        }
        return widget.itemBuilder(_items[index]);
      },
    );
  }

  @override
  void dispose() {
    _scrollController.dispose();
    super.dispose();
  }
}
```

---

# 11. Architecture: Repository + Data Source

## Complete Architecture Diagram
```
Presentation Layer (UI)
    |
    v
State Management (Riverpod/BLoC)
    |
    v
Use Cases (Optional, Clean Architecture)
    |
    v
Repository (Abstract + Implementation)
    |
    +-> Remote Data Source (dio + API)
    +-> Local Data Source (Hive/sqflite Cache)
```

## Full Implementation
```dart
// Domain - Entities
class UserEntity {
  final String id;
  final String username;
  final String avatarUrl;

  UserEntity({required this.id, required this.username, required this.avatarUrl});
}

// Domain - Repository Interface
abstract class UserRepository {
  Future<List<UserEntity>> searchUsers(String query, int page);
  Future<UserEntity> getUserDetail(String username);
}

// Data - Models (DTOs)
class GitHubUserModel {
  final String login;
  final String avatarUrl;
  final int id;

  GitHubUserModel({required this.login, required this.avatarUrl, required this.id});

  factory GitHubUserModel.fromJson(Map<String, dynamic> json) => GitHubUserModel(
    login: json['login'],
    avatarUrl: json['avatar_url'],
    id: json['id'],
  );

  UserEntity toEntity() => UserEntity(
    id: id.toString(),
    username: login,
    avatarUrl: avatarUrl,
  );
}

// Data - Remote Data Source
abstract class UserRemoteDataSource {
  Future<List<GitHubUserModel>> searchUsers(String query, int page);
}

class UserRemoteDataSourceImpl implements UserRemoteDataSource {
  final Dio _dio;
  UserRemoteDataSourceImpl(this._dio);

  @override
  Future<List<GitHubUserModel>> searchUsers(String query, int page) async {
    final response = await _dio.get('/search/users', queryParameters: {
      'q': query,
      'page': page,
      'per_page': 30,
    });
    return (response.data['items'] as List)
        .map((e) => GitHubUserModel.fromJson(e))
        .toList();
  }
}

// Data - Repository Implementation
class UserRepositoryImpl implements UserRepository {
  final UserRemoteDataSource _remoteDataSource;

  UserRepositoryImpl(this._remoteDataSource);

  @override
  Future<List<UserEntity>> searchUsers(String query, int page) async {
    final models = await _remoteDataSource.searchUsers(query, page);
    return models.map((m) => m.toEntity()).toList();
  }

  @override
  Future<UserEntity> getUserDetail(String username) async {
    // Implementation...
    throw UnimplementedError();
  }
}
```

---

# 12. Hands-On Project: GitHub User Search Pro

## Project Overview
Build a complete **GitHub User Search** app with:
- **dio** for API calls with global configuration
- **freezed + json_serializable** for type-safe models
- **Search with debounce** (wait for user to stop typing)
- **Pagination** with infinite scroll
- **Error handling** with retry and user-friendly messages
- **Pull-to-refresh** and loading skeletons
- **User detail screen** with rich profile data
- **Cancel tokens** to prevent memory leaks

## Complete Code

```dart
import 'package:flutter/material.dart';
import 'package:dio/dio.dart';
import 'package:freezed_annotation/freezed_annotation.dart';
import 'package:flutter_riverpod/flutter_riverpod.dart';
import 'package:cached_network_image/cached_network_image.dart';
import 'package:shimmer/shimmer.dart';
import 'package:intl/intl.dart';

part 'main.freezed.dart';
part 'main.g.dart';

void main() {
  runApp(
    const ProviderScope(
      child: GitHubSearchApp(),
    ),
  );
}

// ============ DIO CONFIGURATION ============
final dioProvider = Provider<Dio>((ref) {
  final dio = Dio(
    BaseOptions(
      baseUrl: 'https://api.github.com',
      connectTimeout: const Duration(seconds: 10),
      receiveTimeout: const Duration(seconds: 10),
      headers: {
        'Accept': 'application/vnd.github.v3+json',
      },
      validateStatus: (status) => status != null && status < 500,
    ),
  );

  dio.interceptors.addAll([
    LogInterceptor(
      requestHeader: true,
      requestBody: true,
      responseBody: true,
      responseHeader: false,
    ),
    _ErrorInterceptor(),
  ]);

  return dio;
});

class _ErrorInterceptor extends Interceptor {
  @override
  void onError(DioException err, ErrorInterceptorHandler handler) {
    final statusCode = err.response?.statusCode;
    final message = err.response?.data?['message'] ?? 'An error occurred';

    switch (statusCode) {
      case 403:
        if (message.contains('rate limit')) {
          throw Exception('GitHub API rate limit exceeded. Please try again later.');
        }
        break;
      case 404:
        throw Exception('User not found');
      case 422:
        throw Exception('Invalid search query');
      default:
        throw Exception(message);
    }
    handler.next(err);
  }
}

// ============ FREEZED MODELS ============
@freezed
class GitHubUser with _$GitHubUser {
  const factory GitHubUser({
    required String login,
    @JsonKey(name: 'avatar_url') required String avatarUrl,
    @JsonKey(name: 'html_url') required String htmlUrl,
    @JsonKey(name: 'type') required String userType,
    @Default(0) int id,
  }) = _GitHubUser;

  factory GitHubUser.fromJson(Map<String, dynamic> json) =>
      _$GitHubUserFromJson(json);
}

@freezed
class GitHubUserDetail with _$GitHubUserDetail {
  const factory GitHubUserDetail({
    required String login,
    @JsonKey(name: 'avatar_url') required String avatarUrl,
    @JsonKey(name: 'html_url') required String htmlUrl,
    @JsonKey(name: 'name') String? displayName,
    @JsonKey(name: 'bio') String? biography,
    @JsonKey(name: 'public_repos') @Default(0) int publicRepos,
    @JsonKey(name: 'public_gists') @Default(0) int publicGists,
    @JsonKey(name: 'followers') @Default(0) int followers,
    @JsonKey(name: 'following') @Default(0) int following,
    @JsonKey(name: 'created_at') required DateTime createdAt,
    @JsonKey(name: 'location') String? location,
    @JsonKey(name: 'company') String? company,
    @JsonKey(name: 'blog') String? blog,
    @JsonKey(name: 'twitter_username') String? twitterUsername,
  }) = _GitHubUserDetail;

  factory GitHubUserDetail.fromJson(Map<String, dynamic> json) =>
      _$GitHubUserDetailFromJson(json);
}

@freezed
class SearchState with _$SearchState {
  const factory SearchState.initial() = SearchInitial;
  const factory SearchState.loading() = SearchLoading;
  const factory SearchState.data({
    required List<GitHubUser> users,
    required int page,
    required bool hasMore,
    required String query,
  }) = SearchData;
  const factory SearchState.error(String message) = SearchError;
}

// ============ API SERVICE ============
class GitHubApiService {
  final Dio _dio;
  GitHubApiService(this._dio);

  Future<List<GitHubUser>> searchUsers(
    String query, {
    required int page,
    CancelToken? cancelToken,
  }) async {
    if (query.trim().isEmpty) return [];

    final response = await _dio.get(
      '/search/users',
      queryParameters: {
        'q': query.trim(),
        'page': page,
        'per_page': 30,
      },
      cancelToken: cancelToken,
    );

    final items = response.data['items'] as List<dynamic>? ?? [];
    return items.map((json) => GitHubUser.fromJson(json)).toList();
  }

  Future<GitHubUserDetail> getUserDetail(String username) async {
    final response = await _dio.get('/users/$username');
    return GitHubUserDetail.fromJson(response.data);
  }
}

// ============ RIVERPOD PROVIDERS ============
final githubApiServiceProvider = Provider<GitHubApiService>((ref) {
  return GitHubApiService(ref.watch(dioProvider));
});

final searchControllerProvider = StateNotifierProvider.autoDispose<
    SearchController, SearchState>((ref) {
  return SearchController(ref.watch(githubApiServiceProvider));
});

class SearchController extends StateNotifier<SearchState> {
  final GitHubApiService _apiService;
  CancelToken? _cancelToken;

  SearchController(this._apiService) : super(const SearchState.initial());

  Future<void> search(String query) async {
    if (query.trim().isEmpty) {
      state = const SearchState.initial();
      return;
    }

    // Cancel previous request
    _cancelToken?.cancel('New search initiated');
    _cancelToken = CancelToken();

    state = const SearchState.loading();

    try {
      final users = await _apiService.searchUsers(
        query,
        page: 1,
        cancelToken: _cancelToken,
      );

      state = SearchState.data(
        users: users,
        page: 1,
        hasMore: users.length == 30,
        query: query,
      );
    } catch (e) {
      if (e is! DioException || e.type != DioExceptionType.cancel) {
        state = SearchState.error(e.toString().replaceAll('Exception: ', ''));
      }
    }
  }

  Future<void> loadMore() async {
    final current = state;
    if (current is! SearchData || !current.hasMore) return;

    _cancelToken = CancelToken();

    try {
      final newUsers = await _apiService.searchUsers(
        current.query,
        page: current.page + 1,
        cancelToken: _cancelToken,
      );

      state = current.copyWith(
        users: [...current.users, ...newUsers],
        page: current.page + 1,
        hasMore: newUsers.length == 30,
      );
    } catch (e) {
      // Keep existing data, just stop loading more
      state = current.copyWith(hasMore: false);
    }
  }

  @override
  void dispose() {
    _cancelToken?.cancel('Controller disposed');
    super.dispose();
  }
}

// ============ APP ============
class GitHubSearchApp extends StatelessWidget {
  const GitHubSearchApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'GitHub Search Pro',
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        useMaterial3: true,
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepPurple),
      ),
      darkTheme: ThemeData(
        useMaterial3: true,
        brightness: Brightness.dark,
        colorScheme: ColorScheme.fromSeed(
          seedColor: Colors.deepPurple,
          brightness: Brightness.dark,
        ),
      ),
      themeMode: ThemeMode.system,
      home: const SearchScreen(),
    );
  }
}

// ============ SEARCH SCREEN ============
class SearchScreen extends ConsumerStatefulWidget {
  const SearchScreen({super.key});

  @override
  ConsumerState<SearchScreen> createState() => _SearchScreenState();
}

class _SearchScreenState extends ConsumerState<SearchScreen> {
  final _searchController = TextEditingController();
  final _scrollController = ScrollController();

  @override
  void initState() {
    super.initState();
    _scrollController.addListener(_onScroll);
  }

  void _onScroll() {
    if (_scrollController.position.pixels >=
        _scrollController.position.maxScrollExtent - 200) {
      ref.read(searchControllerProvider.notifier).loadMore();
    }
  }

  @override
  Widget build(BuildContext context) {
    final searchState = ref.watch(searchControllerProvider);

    return Scaffold(
      appBar: AppBar(
        title: const Text('GitHub Search'),
        centerTitle: true,
        elevation: 0,
      ),
      body: Column(
        children: [
          // Search Bar
          Padding(
            padding: const EdgeInsets.all(16),
            child: TextField(
              controller: _searchController,
              decoration: InputDecoration(
                hintText: 'Search GitHub users...',
                prefixIcon: const Icon(Icons.search),
                suffixIcon: _searchController.text.isNotEmpty
                    ? IconButton(
                        icon: const Icon(Icons.clear),
                        onPressed: () {
                          _searchController.clear();
                          ref.read(searchControllerProvider.notifier)
                              .search('');
                        },
                      )
                    : null,
                filled: true,
                border: OutlineInputBorder(
                  borderRadius: BorderRadius.circular(16),
                  borderSide: BorderSide.none,
                ),
              ),
              onChanged: (value) {
                // Debounce search
                Future.delayed(const Duration(milliseconds: 500), () {
                  if (_searchController.text == value && mounted) {
                    ref.read(searchControllerProvider.notifier).search(value);
                  }
                });
              },
            ),
          ),

          // Results
          Expanded(
            child: searchState.when(
              initial: () => _InitialState(),
              loading: () => _LoadingState(),
              data: (users, page, hasMore, query) => _UserList(
                users: users,
                hasMore: hasMore,
                scrollController: _scrollController,
                onRefresh: () => ref
                    .read(searchControllerProvider.notifier)
                    .search(query),
              ),
              error: (message) => _ErrorState(
                message: message,
                onRetry: () => ref
                    .read(searchControllerProvider.notifier)
                    .search(_searchController.text),
              ),
            ),
          ),
        ],
      ),
    );
  }

  @override
  void dispose() {
    _searchController.dispose();
    _scrollController.dispose();
    super.dispose();
  }
}

// ============ UI STATES ============
class _InitialState extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Center(
      child: Column(
        mainAxisAlignment: MainAxisAlignment.center,
        children: [
          Icon(
            Icons.search,
            size: 80,
            color: Colors.grey.shade400,
          ),
          const SizedBox(height: 16),
          Text(
            'Search for GitHub users',
            style: TextStyle(
              fontSize: 18,
              color: Colors.grey.shade600,
            ),
          ),
          const SizedBox(height: 8),
          Text(
            'Try "flutter", "dart", or "google"',
            style: TextStyle(color: Colors.grey.shade500),
          ),
        ],
      ),
    );
  }
}

class _LoadingState extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return ListView.builder(
      padding: const EdgeInsets.all(16),
      itemCount: 8,
      itemBuilder: (context, index) => _UserCardSkeleton(),
    );
  }
}

class _ErrorState extends StatelessWidget {
  final String message;
  final VoidCallback onRetry;

  const _ErrorState({required this.message, required this.onRetry});

  @override
  Widget build(BuildContext context) {
    return Center(
      child: Padding(
        padding: const EdgeInsets.all(32),
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Icon(Icons.error_outline, size: 64, color: Colors.red.shade300),
            const SizedBox(height: 16),
            Text(
              message,
              textAlign: TextAlign.center,
              style: const TextStyle(fontSize: 16),
            ),
            const SizedBox(height: 16),
            FilledButton.icon(
              onPressed: onRetry,
              icon: const Icon(Icons.refresh),
              label: const Text('Retry'),
            ),
          ],
        ),
      ),
    );
  }
}

class _UserList extends StatelessWidget {
  final List<GitHubUser> users;
  final bool hasMore;
  final ScrollController scrollController;
  final VoidCallback onRefresh;

  const _UserList({
    required this.users,
    required this.hasMore,
    required this.scrollController,
    required this.onRefresh,
  });

  @override
  Widget build(BuildContext context) {
    return RefreshIndicator(
      onRefresh: () async => onRefresh(),
      child: ListView.builder(
        controller: scrollController,
        padding: const EdgeInsets.all(16),
        itemCount: users.length + (hasMore ? 1 : 0),
        itemBuilder: (context, index) {
          if (index >= users.length) {
            return const Padding(
              padding: EdgeInsets.all(16),
              child: Center(child: CircularProgressIndicator()),
            );
          }
          return _UserCard(user: users[index]);
        },
      ),
    );
  }
}

// ============ USER CARD ============
class _UserCard extends StatelessWidget {
  final GitHubUser user;
  const _UserCard({required this.user});

  @override
  Widget build(BuildContext context) {
    return Card(
      margin: const EdgeInsets.only(bottom: 12),
      child: ListTile(
        contentPadding: const EdgeInsets.all(12),
        leading: Hero(
          tag: 'avatar_${user.login}',
          child: ClipRRect(
            borderRadius: BorderRadius.circular(8),
            child: CachedNetworkImage(
              imageUrl: user.avatarUrl,
              width: 56,
              height: 56,
              fit: BoxFit.cover,
              placeholder: (context, url) => Container(
                width: 56,
                height: 56,
                color: Colors.grey.shade300,
              ),
              errorWidget: (context, url, error) => Container(
                width: 56,
                height: 56,
                color: Colors.grey.shade300,
                child: const Icon(Icons.person),
              ),
            ),
          ),
        ),
        title: Text(
          user.login,
          style: const TextStyle(fontWeight: FontWeight.bold),
        ),
        subtitle: Text(
          user.userType,
          style: TextStyle(color: Colors.grey.shade600),
        ),
        trailing: const Icon(Icons.chevron_right),
        onTap: () {
          Navigator.push(
            context,
            MaterialPageRoute(
              builder: (_) => UserDetailScreen(username: user.login),
            ),
          );
        },
      ),
    );
  }
}

// ============ SKELETON LOADING ============
class _UserCardSkeleton extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Shimmer.fromColors(
      baseColor: Colors.grey.shade300,
      highlightColor: Colors.grey.shade100,
      child: Card(
        margin: const EdgeInsets.only(bottom: 12),
        child: ListTile(
          contentPadding: const EdgeInsets.all(12),
          leading: Container(
            width: 56,
            height: 56,
            decoration: BoxDecoration(
              color: Colors.white,
              borderRadius: BorderRadius.circular(8),
            ),
          ),
          title: Container(
            height: 16,
            width: 120,
            color: Colors.white,
          ),
          subtitle: Container(
            height: 12,
            width: 80,
            margin: const EdgeInsets.only(top: 8),
            color: Colors.white,
          ),
        ),
      ),
    );
  }
}

// ============ USER DETAIL SCREEN ============
class UserDetailScreen extends ConsumerWidget {
  final String username;
  const UserDetailScreen({super.key, required this.username});

  @override
  Widget build(BuildContext context, WidgetRef ref) {
    final detailAsync = ref.watch(userDetailProvider(username));

    return Scaffold(
      appBar: AppBar(
        title: Text(username),
        centerTitle: true,
      ),
      body: detailAsync.when(
        loading: () => const Center(child: CircularProgressIndicator()),
        error: (err, _) => _ErrorState(
          message: err.toString(),
          onRetry: () => ref.invalidate(userDetailProvider(username)),
        ),
        data: (user) => _UserDetailContent(user: user),
      ),
    );
  }
}

final userDetailProvider = FutureProvider.family<GitHubUserDetail, String>(
  (ref, username) async {
    final service = ref.watch(githubApiServiceProvider);
    return await service.getUserDetail(username);
  },
);

class _UserDetailContent extends StatelessWidget {
  final GitHubUserDetail user;
  const _UserDetailContent({required this.user});

  @override
  Widget build(BuildContext context) {
    final colorScheme = Theme.of(context).colorScheme;

    return SingleChildScrollView(
      padding: const EdgeInsets.all(16),
      child: Column(
        children: [
          // Avatar
          Hero(
            tag: 'avatar_${user.login}',
            child: Container(
              width: 120,
              height: 120,
              decoration: BoxDecoration(
                shape: BoxShape.circle,
                border: Border.all(color: colorScheme.primary, width: 3),
                image: DecorationImage(
                  image: CachedNetworkImageProvider(user.avatarUrl),
                  fit: BoxFit.cover,
                ),
              ),
            ),
          ),
          const SizedBox(height: 16),

          // Name
          Text(
            user.displayName ?? user.login,
            style: const TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
          ),
          if (user.biography != null) ...[
            const SizedBox(height: 8),
            Text(
              user.biography!,
              textAlign: TextAlign.center,
              style: TextStyle(color: Colors.grey.shade600, fontSize: 14),
            ),
          ],
          const SizedBox(height: 24),

          // Stats Grid
          Row(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: [
              _StatCard(label: 'Repositories', value: user.publicRepos),
              _StatCard(label: 'Followers', value: user.followers),
              _StatCard(label: 'Following', value: user.following),
            ],
          ),
          const SizedBox(height: 24),

          // Info Cards
          if (user.company != null)
            _InfoTile(icon: Icons.business, label: 'Company', value: user.company!),
          if (user.location != null)
            _InfoTile(icon: Icons.location_on, label: 'Location', value: user.location!),
          if (user.blog != null && user.blog!.isNotEmpty)
            _InfoTile(icon: Icons.link, label: 'Website', value: user.blog!),
          if (user.twitterUsername != null)
            _InfoTile(
              icon: Icons.alternate_email,
              label: 'Twitter',
              value: '@${user.twitterUsername}',
            ),
          _InfoTile(
            icon: Icons.calendar_today,
            label: 'Joined',
            value: DateFormat('MMMM d, yyyy').format(user.createdAt),
          ),

          const SizedBox(height: 24),

          // View on GitHub Button
          SizedBox(
            width: double.infinity,
            child: FilledButton.icon(
              onPressed: () {
                // Launch URL (would use url_launcher package)
              },
              icon: const Icon(Icons.open_in_new),
              label: const Text('View on GitHub'),
            ),
          ),
        ],
      ),
    );
  }
}

class _StatCard extends StatelessWidget {
  final String label;
  final int value;
  const _StatCard({required this.label, required this.value});

  @override
  Widget build(BuildContext context) {
    return Card(
      child: Container(
        width: 100,
        padding: const EdgeInsets.all(16),
        child: Column(
          children: [
            Text(
              NumberFormat.compact().format(value),
              style: const TextStyle(fontSize: 20, fontWeight: FontWeight.bold),
            ),
            const SizedBox(height: 4),
            Text(label, style: TextStyle(color: Colors.grey.shade600, fontSize: 12)),
          ],
        ),
      ),
    );
  }
}

class _InfoTile extends StatelessWidget {
  final IconData icon;
  final String label;
  final String value;
  const _InfoTile({required this.icon, required this.label, required this.value});

  @override
  Widget build(BuildContext context) {
    return ListTile(
      leading: Icon(icon, color: Colors.grey.shade600),
      title: Text(value),
      subtitle: Text(label, style: TextStyle(color: Colors.grey.shade500)),
    );
  }
}
```

---

# 13. Common Mistakes & How to Avoid Them

## Mistake 1: Not Using a Base URL
```dart
// WRONG - Repeated strings, hard to maintain
final response = await dio.get('https://api.example.com/v1/users');
final response2 = await dio.get('https://api.example.com/v1/posts');

// CORRECT - BaseOptions with baseUrl
final dio = Dio(BaseOptions(baseUrl: 'https://api.example.com/v1'));
final response = await dio.get('/users');
final response2 = await dio.get('/posts');
```

## Mistake 2: Parsing JSON on the Main Thread for Large Data
```dart
// WRONG - Blocks UI for large JSON
final users = jsonDecode(hugeResponseBody).map((e) => User.fromJson(e)).toList();

// CORRECT - Use isolate for heavy parsing
import 'package:flutter/foundation.dart';

final users = await compute((String body) {
  return jsonDecode(body).map((e) => User.fromJson(e)).toList();
}, hugeResponseBody);
```

## Mistake 3: Not Cancelling Requests on Widget Dispose
```dart
// WRONG - Memory leak, setState after dispose
class _MyScreenState extends State<MyScreen> {
  @override
  void initState() {
    super.initState();
    dio.get('/users').then((response) {
      setState(() { users = response.data; }); // CRASH if disposed!
    });
  }
}

// CORRECT - Use CancelToken and check mounted
class _MyScreenState extends State<MyScreen> {
  final _cancelToken = CancelToken();

  @override
  void initState() {
    super.initState();
    _loadData();
  }

  Future<void> _loadData() async {
    try {
      final response = await dio.get('/users', cancelToken: _cancelToken);
      if (mounted) setState(() { users = response.data; });
    } catch (e) {
      if (!mounted || e is DioException && e.type == DioExceptionType.cancel) return;
      // Handle error
    }
  }

  @override
  void dispose() {
    _cancelToken.cancel('Widget disposed');
    super.dispose();
  }
}
```

## Mistake 4: Using dynamic Everywhere
```dart
// WRONG - No type safety, runtime errors
final response = await dio.get('/users');
final user = response.data['items'][0]; // Could be null, could be wrong type
final name = user['name']; // dynamic - no autocomplete, no safety

// CORRECT - Use generated models with freezed
final response = await dio.get('/search/users');
final users = (response.data['items'] as List)
    .map((e) => GitHubUser.fromJson(e))
    .toList();
final name = users.first.login; // String - type safe, autocomplete works
```

## Mistake 5: Not Handling Timeout
```dart
// WRONG - Request hangs forever on bad network
final dio = Dio(); // Default: no timeout

// CORRECT - Always set timeouts
final dio = Dio(
  BaseOptions(
    connectTimeout: Duration(seconds: 10),
    receiveTimeout: Duration(seconds: 10),
    sendTimeout: Duration(seconds: 10),
  ),
);
```

## Mistake 6: Storing API Keys in Code
```dart
// WRONG - Easy to extract from APK/IPA
const apiKey = 'sk-live-1234567890abcdef';

// CORRECT - Use environment variables or secure storage
import 'package:flutter_dotenv/flutter_dotenv.dart';
final apiKey = dotenv.env['API_KEY'];
// OR store in flutter_secure_storage
```

## Mistake 7: Not Checking Response Status
```dart
// WRONG - Assumes success
final response = await dio.get('/users');
return response.data; // Could be 404, 500, etc.

// CORRECT - Validate status or use interceptors
final response = await dio.get('/users');
if (response.statusCode == 200) {
  return response.data;
}
throw Exception('Failed: ${response.statusCode}');

// OR use validateStatus in BaseOptions
BaseOptions(validateStatus: (status) => status != null && status < 500)
```

---

# 14. Day 16 Checklist

Use this checklist to verify mastery:
- [ ] Understands HTTP methods (GET, POST, PUT, PATCH, DELETE)
- [ ] Knows common status codes and their meanings
- [ ] Can set up and use the http package for simple requests
- [ ] Can configure dio with BaseOptions, timeouts, and headers
- [ ] Can perform GET, POST, PUT, DELETE with dio
- [ ] Can upload files using FormData
- [ ] Can download files with progress tracking
- [ ] Understands the Repository + Data Source pattern
- [ ] Can parse JSON manually for simple cases
- [ ] Can set up freezed + json_serializable for type-safe models
- [ ] Can run build_runner to generate code
- [ ] Can handle network errors gracefully
- [ ] Can implement retry logic with exponential backoff
- [ ] Can use dio interceptors for logging
- [ ] Can implement token refresh in an interceptor
- [ ] Can implement request caching with interceptors
- [ ] Can implement offset-based pagination
- [ ] Can implement cursor-based pagination with infinite scroll
- [ ] Can use CancelToken to prevent memory leaks
- [ ] Can debounce search requests
- [ ] Built the GitHub User Search app with dio
- [ ] App has search with debounce and loading skeletons
- [ ] App has pagination with infinite scroll
- [ ] App has error handling with retry
- [ ] App has pull-to-refresh
- [ ] App has user detail screen with rich data
- [ ] Pushed the project to GitHub

---

# Key Takeaways (Memorize These!)

1. **dio is the production standard** - Use http only for learning. dio gives you interceptors, cancel tokens, global config, and retry logic out of the box.
2. **Always set timeouts** - Default is no timeout. Always configure connect, receive, and send timeouts to prevent hanging requests.
3. **Use freezed + json_serializable** - Never parse JSON manually in production. Code generation gives you type safety, null safety, and copyWith methods.
4. **Cancel tokens prevent memory leaks** - Always cancel dio requests when widgets dispose or new searches start.
5. **Repository pattern separates concerns** - UI -> State Management -> Repository -> Remote/Local Data Sources. Never call APIs directly from widgets.
6. **Interceptors are superpowers** - Log requests, refresh tokens, cache responses, add headers globally - all in one place.
7. **Handle every error case** - No internet, timeout, 401, 404, 500, rate limit. Each needs a specific user-friendly message.
8. **Debounce search inputs** - Wait 300-500ms after the user stops typing before firing API requests. Prevents spam and saves bandwidth.
9. **Never hardcode API keys** - Use environment variables (flutter_dotenv) or secure storage. Keys in code are easily extracted from APKs.
10. **Use compute() for heavy JSON parsing** - Large API responses can block the UI thread. Parse in an isolate for smooth 60fps.

---

# Extra Practice (Do These Tonight!)

1. **Weather App with Real API:** Connect the Day 13 Weather App to OpenWeatherMap API. Implement caching with dio interceptors, error retry, and offline mode with last-known data.
2. **News Reader with Pagination:** Build a news app using NewsAPI. Implement infinite scroll, search with debounce, category filters, and article caching.
3. **E-Commerce Product Catalog:** Connect to a fake store API (fakestoreapi.com). Implement product listing with pagination, search, filters, and a shopping cart that syncs to a backend.
4. **Social Media Feed:** Build a Twitter-like feed with pull-to-refresh, infinite pagination, like/unlike actions (POST), and image upload with FormData.
5. **Multi-API Dashboard:** Build a dashboard that fetches data from 3 different APIs simultaneously using Future.wait(). Show combined loading states and partial error handling.

---

**Congratulations!** You've completed Day 16. You now master networking in Flutter - from simple HTTP requests to production-grade API architectures with dio, interceptors, pagination, error handling, and type-safe code generation.

**Next Up -> Day 17: Authentication & Security (Firebase Auth, JWT, Biometric)**

---

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 16: Networking & APIs - Complete Deep Dive*

*Generated for 30 Days Flutter: Zero to Hero (2026 Edition)*
*Day 13: State Management — Riverpod — Complete Deep Dive*
