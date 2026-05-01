![Android](https://img.shields.io/badge/Android-API%2028%2B-brightgreen.svg)
![Kotlin](https://img.shields.io/badge/Kotlin-2.0.21-blue.svg)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-BOM%202024.09-orange.svg)
![License](https://img.shields.io/badge/license-AGPLv3-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0--alpha1-red.svg)
![Status](https://img.shields.io/badge/status-alpha-orange.svg)

[SaleFlex Ecosystem](https://github.com/SaleFlex) | [SaleFlex.PyPOS](https://github.com/SaleFlex/SaleFlex.PyPOS) | [SaleFlex.OFFICE](https://github.com/SaleFlex/SaleFlex.OFFICE) | [SaleFlex.GATE](https://github.com/SaleFlex/SaleFlex.GATE) | [SaleFlex.KITCHEN](https://github.com/SaleFlex/SaleFlex.KITCHEN) | **[SaleFlex.mPOS](https://github.com/SaleFlex/SaleFlex.mPOS)**

# SaleFlex.mPOS

**SaleFlex.mPOS** is the Android mobile point-of-sale companion to the SaleFlex ecosystem - a Jetpack Compose app built for tablets and Android POS hardware that works both online and offline.

Whether you are running a busy retail counter or a restaurant floor, SaleFlex.mPOS gives your staff a fast, touch-optimised interface to handle sales, payments, and end-of-day closures - right from an Android device.

> Developed and operated by **[Mousavi.Tech](https://mousavi.tech)**

---

## Who Is This For?

SaleFlex.mPOS is built for:

- **Retailers and restaurateurs** who want a mobile POS terminal on Android tablets or dedicated POS hardware.
- **Businesses already using SaleFlex** who need a mobile companion to SaleFlex.PyPOS or SaleFlex.OFFICE.
- **Developers and integrators** who want an open-source, extensible Android POS they can customise and deploy.
- **Tech-forward teams** who need offline-capable, self-hosted mobile POS without expensive hardware lock-in.

---

## Community Edition

> **Looking for a free, open-source POS terminal?**
> Check out **[SaleFlex.PyPOS](https://github.com/SaleFlex/SaleFlex.PyPOS)** - a fully free and open-source touch POS built with Python and PySide6, available under AGPLv3 at no cost.

SaleFlex.mPOS is an **Android mobile POS** application. While the source code is published under the [GNU Affero General Public License v3.0 (AGPLv3)](LICENSE), **ready-to-use builds and commercial deployment support are available as a paid product**. Please contact us for pricing and licensing options.

The codebase includes:

- Touch-optimised POS interface for Android tablets (landscape-first)
- Cashier login with secure password verification
- Sale screen with barcode/PLU lookup and line management
- Payment processing (cash, card, mobile pay) with change calculation
- End-of-day closure with transaction aggregation
- Local offline database (Room/SQLite)
- SaleFlex.OFFICE integration for data sync and transaction push
- Offline outbox - failed pushes are queued and retried automatically

---

## Commercial Services

Need more than the open-source edition? We offer:

- **Custom development** - tailored features, integrations, and workflows built for your business.
- **Implementation & onboarding** - hands-on setup, hardware configuration, and staff training.
- **Priority support** - dedicated support channels with guaranteed response times.
- **Integration services** - connecting SaleFlex.mPOS to your existing OFFICE, ERP, loyalty, or payment systems.

> Contact us at [saleflex.pro](https://saleflex.pro) for commercial enquiries.

---

## Managed Cloud

Pair SaleFlex.mPOS with **SaleFlex Cloud** (coming soon) for a fully managed backend:

- No server to manage - we handle updates, backups, and scaling.
- One-click OFFICE and GATE backend provisioning.
- Built-in reporting dashboards accessible from any browser.
- Enterprise-grade security and compliance.
- Multi-region availability.

> Join the waitlist at [saleflex.net](https://saleflex.net) to be notified when Managed Cloud launches.

---

## Download Ready Builds

APK builds and Play Store distribution are currently in preparation. Once available, you will be able to download pre-built releases directly.

**Until then, build from source:**

1. Clone the repository
2. Open `SaleFlex.mPOS/` in **Android Studio Meerkat** or newer
3. Sync Gradle
4. Run on a tablet emulator or device (landscape, API 28+)

> **Requirements:** Android API 28+ (Android 9.0) - Kotlin 2.0.21+ - Android Studio Meerkat+

---

## Screenshots

> Screenshots coming soon. The login screen, sale interface, payment flow, and closure summary will be showcased here.

---

## Demo Video

> A demo video is being prepared and will be published here and on the SaleFlex YouTube channel shortly.

---

## Roadmap

### Done
- Touch-optimised POS UI with Jetpack Compose (landscape tablet layout)
- Cashier login with SHA-256 password verification
- Sale screen with NumPad, barcode/PLU lookup, line management
- Payment processing with cash, card, and mobile pay options
- End-of-day closure with transaction aggregation
- Local Room database (cashiers, products, transactions, closures, sync queue)
- SaleFlex.OFFICE REST API integration (Retrofit)
- Offline outbox with sync queue entity
- Hilt dependency injection throughout
- Typed exception hierarchy and central Timber logging

### In Progress
- Settings screen (OFFICE URL, terminal/store codes, app mode)
- DataStore-based settings persistence

### Planned
- Background WorkManager sync retry worker
- Product list and search screen
- Customer management
- Barcode scanner hardware integration
- Receipt printer support (Bluetooth/USB ESC/P)
- Campaign and loyalty support (via OFFICE/GATE)
- Multi-language support
- SaleFlex.GATE direct connectivity

---

## Related Projects

| Project | Description |
|---------|-------------|
| [SaleFlex.PyPOS](https://github.com/SaleFlex/SaleFlex.PyPOS) | Python / PySide6 touch POS terminal |
| [SaleFlex.OFFICE](https://github.com/SaleFlex/SaleFlex.OFFICE) | Back-office and ERP-style management |
| [SaleFlex.GATE](https://github.com/SaleFlex/SaleFlex.GATE) | Central hub and API gateway |
| [SaleFlex.KITCHEN](https://github.com/SaleFlex/SaleFlex.KITCHEN) | Kitchen display system |
| [SaleFlex.POS](https://github.com/SaleFlex/SaleFlex.POS) | Legacy .NET POS client |

---

## License

This project is licensed under the **GNU Affero General Public License v3.0**. See [LICENSE](LICENSE) for details.

---

## Contributors

<table>
<tr>
    <td align="center">
        <a href="https://github.com/ferhat-mousavi">
            <img src="https://avatars.githubusercontent.com/u/5930760?v=4" width="100;" alt="Ferhat Mousavi"/>
            <br />
            <sub><b>Ferhat Mousavi</b></sub>
        </a>
    </td>
</tr>
</table>

## Donation and Support

If you find SaleFlex.mPOS useful and want to support its development:

- **USDT / BUSD / ETH:** `0xa5a87a939bfcd492f056c26e4febe102ea599b5b`
- **BTC:** `15qyZpi6HjYyVhKKBsCbZSXU4bLdVJ8Phe`
- **SOL:** `Gt3bDczPcJvfBeg9TTBrBJGSHLJVkvnSSTov8W3QMpQf`