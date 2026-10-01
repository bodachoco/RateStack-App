<div align="center">

<img src="assets/icon.png" width="120" alt="RateStack app icon" />

# RateStack

### One amount. Every currency.

A native iOS currency converter built around a single idea:
**tap any currency, type once, and watch every row update instantly.**

[![Platform](https://img.shields.io/badge/iOS-16%2B-0F7A6C?style=flat-square&logo=apple&logoColor=white)](https://ratestack.app)
[![Swift](https://img.shields.io/badge/Swift-SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![Status](https://img.shields.io/badge/App%20Store-in%20review-2EC4B6?style=flat-square)](https://ratestack.app)
[![Privacy](https://img.shields.io/badge/data%20collected-none-111827?style=flat-square)](https://ratestack.app/privacy)

[**Website**](https://ratestack.app) · [**Privacy**](https://ratestack.app/privacy) · [**Support**](https://ratestack.app/support)

<br />

<img src="assets/01-converter.jpg" width="260" alt="RateStack converter with a calculator keypad" />

</div>

<br />

## Why RateStack

Most converters make you pick a **From**, pick a **To**, and press **Convert**. RateStack drops all of that.

Keep your currencies in one stack. Tap any row and it becomes the active currency. Type on the built-in keypad and every other row converts as you go, even offline.

- **No selectors.** No From/To pickers, no swap button, no Convert button.
- **Calculator built in.** Type `120 × 3 + 15` and every row updates with the result.
- **Works offline.** Converts from the last good rates, with the source and age always visible.
- **Private by design.** No account, no ads, no tracking, no limits.

<br />

## Features

<table>
  <tr>
    <td align="center" width="33%">
      <img src="assets/03-calculator.jpg" width="220" alt="Calculator keypad" /><br />
      <b>Calculator keypad</b><br />
      <sub>Math right in the amount field</sub>
    </td>
    <td align="center" width="33%">
      <img src="assets/04-crypto-picker.jpg" width="220" alt="Crypto currency picker" /><br />
      <b>Fiat, crypto, and metals</b><br />
      <sub>160+ currencies, 60 coins, gold, silver, platinum, palladium</sub>
    </td>
    <td align="center" width="33%">
      <img src="assets/05-chart.jpg" width="220" alt="Rate chart" /><br />
      <b>Charts and history</b><br />
      <sub>Rate history for any pair</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="assets/06-rate-alert.jpg" width="220" alt="Rate alert editor" /><br />
      <b>Rate alerts</b><br />
      <sub>Local notifications when a rate crosses your target</sub>
    </td>
    <td align="center">
      <img src="assets/07-dark-stack.jpg" width="220" alt="Dark theme stack" /><br />
      <b>Themes</b><br />
      <sub>Light, dark, and a Gold theme you earn</sub>
    </td>
    <td align="center" valign="middle">
      <b>Also included</b><br /><br />
      <sub>
        Saved stacks for travel, work, or family<br />
        Personal rates from your bank or bureau<br />
        Live crypto prices while open<br />
        Home Screen and Lock Screen widgets<br />
        Control Center control (iOS 18)<br />
        Spotlight, Shortcuts, and Siri
      </sub>
    </td>
  </tr>
</table>

<br />

## Rate sources

Every source is a free, public API, used as its provider allows. Pick one in **Settings → Rate Source**, or leave it on **Automatic** for built-in failover.

| Source | Covers |
| --- | --- |
| [Frankfurter](https://frankfurter.dev) | Official reference rates (primary) |
| [Fawaz Exchange](https://github.com/fawazahmed0/exchange-api) | Wide fiat coverage, crypto and metals fallback |
| [ExchangeRate-API](https://www.exchangerate-api.com) | Open-access daily rates |
| [FloatRates](https://www.floatrates.com) | Daily rates |
| [Coinbase](https://www.coinbase.com) | Crypto spot prices and charts |
| Parallel market | Optional unofficial street rates for NGN, ARS, and VES |

A refresh never replaces your cached rates until the new ones are validated, so a bad response can't wipe what you have.

<br />

## Built with

- **SwiftUI**, native to iOS 16 and later, with Liquid Glass controls on iOS 26
- **WidgetKit** and **App Intents** for widgets, controls, Shortcuts, and Siri
- **`Decimal` math** for every amount and rate, never floating point
- **Zero third-party runtime dependencies**

<br />

## Privacy

RateStack collects no data. There's no account, no analytics, and no advertising SDK. Your stacks, alerts, and history stay on your device. The App Store privacy label reads **Data Not Collected**. Read the full [privacy policy](https://ratestack.app/privacy).

<br />

---

<div align="center">
<sub>
Rates are indicative reference rates and may differ from banks or transfer services. RateStack doesn't execute trades or move money.<br />
This repository hosts project information only. The app's source code is private.<br /><br />
© 2026 BeggiBeggi
</sub>
</div>
