SPARROW AFRICA — NATIVE ANDROID PROJECT (TEST BUILD 0.1.0)

This is an Android Studio / Gradle project, not a precompiled APK.
It wraps the Sparrow Africa demo interface in a native Android application shell.
The app opens from its own Android launcher icon and does not require Chrome.

SUPPORTED DEMO CURRENCIES
USD — US Dollar
NGN — Nigerian Naira
MUR — Mauritian Rupee
KES — Kenyan Shilling
GHS — Ghanaian Cedi
USDT — Tether (demo)

DEMO ONLY
- Fixed illustrative conversion rates; not live FX.
- Demo balances and transaction records are stored locally on the device.
- Send, cash-out and P2P actions are simulations only.
- No bank, mobile-money, KYC, identity, blockchain, USDT custody or Bybit integration.
- Do not enter real identity or banking information.

HOW TO GET THE APK
The project includes a GitHub Actions workflow at .github/workflows/build-apk.yml.
1. Create a GitHub repository and upload the contents of this project.
2. Open the repository's Actions tab.
3. Run "Build Sparrow Africa APK" (or push to the main branch).
4. When the workflow completes, open the run and download the artifact named
   "sparrow-africa-debug-apk".
5. Extract the artifact ZIP on Android and tap app-debug.apk to install.
   Android may ask you to allow installation from that source.

A debug APK is for personal testing, not Play Store release. For a public release,
the app needs a signed release build, privacy policy, security review, backend,
regulated payment partners and applicable legal/regulatory approvals.
