# Ali Personal Finance — iOS / Android

Shared PWA: https://farham2021.github.io/Farham2021/accounting/

This folder is a **Capacitor development scaffold**, not a signed iOS/Android release. Build machines require Node.js and native SDKs (Xcode on macOS for iOS; Android Studio for Android). Install with `npm install` and initialize each native project using `npm run cap:ios` / `npm run cap:android`.

**Authentication limitation:** The current API requires Telegram Mini App signed initData. Installing as a standalone PWA or opening the native shells outside Telegram does not supply Telegram initData. Standalone login must be implemented securely before these shells can use private finance data. Do not bypass HMAC validation, embed bot tokens, or expose service-role keys in client code.

The existing Supabase data is not migrated or altered by this scaffold.
