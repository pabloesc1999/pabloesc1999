<div align="center">

# ⚡ SHABAN SAEED

### `ANDROID DEVELOPER  •  KOTLIN  •  SOFTWARE BUILDER`

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2800&pause=900&color=7F52FF&center=true&vCenter=true&width=700&lines=Building+Android+apps+with+Kotlin;Turning+ideas+into+working+software;Build+%E2%86%92+Break+%E2%86%92+Debug+%E2%86%92+Improve;Learning+by+building+real+projects" />

<br>

<img src="https://komarev.com/ghpvc/?username=pabloesc1999&label=PROFILE+VIEWS&color=7F52FF&style=for-the-badge" alt="Profile Views" />

  

<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />

  

<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />

</div>

---

# `> whoami`

```kotlin
class Shaban {

    val role = "Android Developer"
    val primaryLanguage = "Kotlin"

    val focus = listOf(
        "Android Development",
        "Kotlin",
        "Software Engineering",
        "Git & GitHub"
    )

    val philosophy =
        "Build → Break → Debug → Understand → Build Better"
}
```

I'm an **IT student and Android developer focused on Kotlin**.

I learn by building actual applications rather than just following tutorials — then I break things, debug them, figure out *why* they failed, and improve the implementation.

Currently focused on **Kotlin fundamentals, native Android development, UI architecture, application state, persistence, and writing cleaner code.**

---

# `> tech_stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=kotlin,android,java,git,github,html,css,js,vscode,visualstudio" />

</div>

<br>

| Area            | Technologies                         |
| --------------- | ------------------------------------ |
| **Language**    | Kotlin                               |
| **Android**     | Android SDK, Activities, Intents     |
| **UI**          | XML, ConstraintLayout, Android Views |
| **View Access** | View Binding                         |
| **Persistence** | SharedPreferences                    |
| **Components**  | Material Components                  |
| **Tools**       | Android Studio, Gradle, Git, GitHub  |

---

# `> projects`

## 🧮 `Simple Calculator`

> **My first real Kotlin / Android application.**

A calculator built from scratch while learning Kotlin and native Android development.

### `FEATURES`

```text
[✓] Addition
[✓] Subtraction
[✓] Multiplication
[✓] Division
[✓] Chained calculations
[✓] Operator swapping
[✓] Decimal handling
[✓] Divide-by-zero protection
[✓] Clean number formatting
[✓] Precision-safe BigDecimal calculations
```

### `TECH`

`Kotlin` `Android Views` `ViewBinding` `BigDecimal`

**What I learned**

* Managing multi-step UI state
* Handling edge cases
* Kotlin enums for type safety
* Precision-safe arithmetic
* Separating calculation logic from UI behavior

---

## 🔐 `LoginTask`

> **A native Android authentication-flow learning project.**

A two-screen Android application demonstrating login validation, navigation, persistent sessions, and local data storage.

### `FEATURES`

```text
[✓] Login form
[✓] Username + email + password input
[✓] Input validation
[✓] Email validation
[✓] Persistent login sessions
[✓] SharedPreferences storage
[✓] Intent-based navigation
[✓] Logout functionality
[✓] Back-stack management
```

### `ARCHITECTURE FLOW`

```text
             ┌───────────────┐
             │   APP LAUNCH  │
             └───────┬───────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ SharedPreferences   │
          │  logged_in = true?  │
          └──────────┬──────────┘
                     │
             ┌───────┴───────┐
             │               │
            YES              NO
             │               │
             ▼               ▼
       ┌───────────┐    ┌───────────┐
       │ Dashboard │    │   Login   │
       └─────┬─────┘    └─────┬─────┘
             │                │
             │             VALID
             │                │
             │                ▼
             │        ┌──────────────┐
             │        │ Save Session │
             │        └──────┬───────┘
             │               │
             └───────►───────┘
```

### `TECH`

`Kotlin` `XML` `SharedPreferences` `Intents` `Android Studio`

**What I learned**

* Activity lifecycle
* Explicit Intents
* Persistent application state
* SharedPreferences
* Back-stack management
* Kotlin null safety
* Input validation

> ⚠️ **Learning project:** authentication data is intentionally stored locally to demonstrate persistence. This is not intended as production authentication.

---

## 🔢 `Counter App`

> **A focused Android UI and state-management exercise.**

A minimal counter application designed to practice UI interaction, View Binding, and state handling.

### `FEATURES`

```text
[✓] Increment counter
[✓] Reset counter
[✓] Material UI
[✓] View Binding
[✓] ConstraintLayout
[✓] Rotation-safe state
```

### `TECH`

`Kotlin` `XML` `ConstraintLayout` `View Binding` `Material Components`

**What I learned**

* Connecting UI elements to Kotlin
* Handling click listeners
* Managing application state
* View Binding
* Android configuration changes

---

# `> learning_path`

My projects are intentionally small — each one introduces a new concept.

```text
                  ANDROID DEVELOPMENT
                         │
                         ▼
              ┌─────────────────────┐
              │    COUNTER APP      │
              │                     │
              │ UI + Events + State │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │  SIMPLE CALCULATOR  │
              │                     │
              │ Logic + Edge Cases  │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │      LOGINTASK      │
              │                     │
              │ Navigation + State  │
              │    + Persistence    │
              └─────────────────────┘
```

The goal isn't to build huge applications immediately.

It's to understand **why the code works**.

---

# `> currently_learning`

```text
KOTLIN
├── Functions
├── OOP
├── Collections
├── Lambdas
├── Null Safety
├── Scope Functions
└── Advanced Kotlin

ANDROID
├── XML Layouts
├── View Binding
├── Activities
├── Intents
├── UI State
├── Persistence
└── Application Architecture

DEVELOPER TOOLS
├── Git
├── GitHub
├── Android Studio
└── Gradle
```

---

# `> development_philosophy`

```text
             ┌──────────┐
             │   LEARN  │
             └────┬─────┘
                  │
                  ▼
             ┌──────────┐
             │  BUILD   │
             └────┬─────┘
                  │
                  ▼
             ┌──────────┐
             │  BREAK   │
             └────┬─────┘
                  │
                  ▼
             ┌──────────┐
             │  DEBUG   │
             └────┬─────┘
                  │
                  ▼
             ┌──────────┐
             │UNDERSTAND│
             └────┬─────┘
                  │
                  ▼
             ┌──────────┐
             │  IMPROVE │
             └────┬─────┘
                  │
                  └──────────────► BUILD AGAIN
```

> **Don't just copy code. Understand why it works.**

---

# `> roadmap`

```text
2026
│
├── [✓] Build first Android applications
├── [✓] Start using Git & GitHub
├── [✓] Work with Kotlin + XML
├── [✓] Implement persistent local state
│
├── [ ] Build larger Android applications
├── [ ] Become genuinely comfortable with Kotlin
├── [ ] Learn Firebase
├── [ ] Learn modern Android architecture
├── [ ] Build and publish a complete Android application
├── [ ] Contribute to open source
└── [ ] Build a strong developer portfolio
```

---

# `> github_stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=pabloesc1999&show_icons=true&theme=tokyonight&hide_border=true" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=pabloesc1999&theme=tokyonight&hide_border=true" />

</div>

---

# `> connect`

<div align="center">

<a href="https://github.com/pabloesc1999">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>

<br>

<div align="center">

### `CODE  •  DEBUG  •  LEARN  •  BUILD`

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=7F52FF&height=120&section=footer" />

</div>
