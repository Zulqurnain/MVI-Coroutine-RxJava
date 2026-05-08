# MVI-Coroutine-RxJava

Android playground exploring the MVI (Model-View-Intent) pattern using Kotlin Coroutines, RxJava Channels, Dagger Hilt DI, and Koin DI.

## Architecture & Tech Stack

- **Pattern**: MVI (Model-View-Intent)
- **Language**: Kotlin
- **Async**: Kotlin Coroutines + RxJava Channels
- **DI Options**: Dagger Hilt & Koin
- **Min SDK**: 24 | **Target SDK**: 35

## MVI Pattern

```
User Intent → ViewModel → State → UI
```

- **Model**: Immutable state objects
- **View**: Renders state, emits intents
- **Intent**: User actions triggering state changes

## Getting Started

```bash
git clone https://github.com/Zulqurnain/MVI-Coroutine-RxJava.git
cd MVI-Coroutine-RxJava
# Open in Android Studio Hedgehog or newer
```

---

**Built by [Zulqurnain Haider](https://zulqurnainj.com/) — Senior Full Stack Engineer**

For full portfolio visit: [https://zulqurnainj.com/](https://zulqurnainj.com/)
