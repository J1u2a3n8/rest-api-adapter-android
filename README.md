# rest-api-adapter-android

> REST API Adapter Pattern in Android

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/rest-api-adapter-android)
![License](https://img.shields.io/github/license/J1u2a3n8/rest-api-adapter-android)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/rest-api-adapter-android)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/rest-api-adapter-android?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/rest-api-adapter-android)

## Description

Android networking layer using Retrofit with Adapter pattern for clean API integration. Demonstrates interceptors, authentication, caching, error handling, and pagination with Kotlin Coroutines and Flow.

## Architecture

Repository → Retrofit Service → Interceptor Chain → Adapter → Domain Model

## Quick Start

### Prerequisites

Android Studio Ladybug+, JDK 17, Android SDK 34

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/rest-api-adapter-android.git
cd rest-api-adapter-android

./gradlew build
```

### Usage

```bash
./gradlew installDebug
```

## Testing

```bash
./gradlew test
```

## Project Structure

```
rest-api-adapter-android/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

Kotlin, Android SDK, Retrofit, OkHttp, Moshi, Coroutines, Flow, Paging 3

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://linkedin.com/in/juanluiscanedo)

---

⭐ If you found this project useful, give it a star!
