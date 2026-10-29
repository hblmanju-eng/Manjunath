# OneRoute Delivery — Android starter project

An Android Jetpack Compose prototype for delivery partners who work across multiple platforms. It includes a home dashboard, manual delivery stop entry, Google Maps hand-off, earnings/fuel calculator, and connection-status screen.

## Important status
- This is a **starter source project**, not a finished production app or a signed APK.
- Swiggy/Zomato live order syncing is **not implemented**. It requires authorised integration access from each platform; do not collect platform passwords or OTPs.
- Google Maps is currently opened through a URL hand-off. An embedded map and multi-stop route optimisation require a Google Maps Platform API key, billing/configuration, and route-planning implementation.
- Earnings values are in-memory in this prototype and are not yet saved to a database.
- Before Play Store release, add persistence, tests, privacy policy, permissions review, secure backend if needed, accessibility/localisation, app signing, and Play Console compliance.

## Build
1. Install Android Studio with Android SDK 35 and a compatible JDK (17 recommended).
2. Open this folder in Android Studio and allow Gradle sync.
3. Run on an Android emulator or device.
4. Create a signed release build only after configuring and testing the production features.

## Package
`com.oneroute.delivery`

## Brand
**OneRoute Delivery** — Two Platforms. One App. One Map.
