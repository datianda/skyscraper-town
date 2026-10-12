# Skyscraper Town Privacy Policy

**Effective date: October 12, 2026**　|　[中文](privacy-zh.md)

Skyscraper Town (摩天小镇, "the game") is developed and operated by **WANWU LAB (玩物软件)** ("we", "us"). This policy explains what information the game collects, why, how it is stored, and what rights you have.

In short: **your saves stay on your device (and, in the Google Play version, in your own Google account if you sign in to Play Games), you can play the whole game without signing in, and the game contains no ads and no third-party analytics or advertising SDKs.**

## 1. What we collect

### 1.1 Data that stays on your device (we never receive it)

- Game saves, save thumbnails and settings (language, volume, which hints you have seen, and so on).
- The AI model address and key you enter yourself (see section 4).

Uninstalling the game or clearing its app data deletes all of it.

**Cloud saves in the Google Play version.** In this version you can sign in to Google Play Games with the Google account on your device. Signing in is optional. If you do:

- Google gives the game your Play Games player name and player ID. The game uses them only to show who is signed in. They are not sent to us.
- The game stores a copy of your saves in **your own Google account** (Play Games "Saved Games") so you can get them back after changing phones or reinstalling. Google holds that copy. It is not on our servers and we cannot see it. You can turn off automatic uploads under Cloud Saves in the game.
- How Google handles this data is described in the [Google Privacy Policy](https://policies.google.com/privacy). To delete the cloud copy, see [How to delete your account](delete-account.md).

### 1.2 Data sent automatically when the game starts

**The Google Play version sends none of the items in the table below.** It only downloads the balance configuration file described under the table.

In versions from other channels: after you tap "Agree and Continue" on first launch, the game sends the following to our server once each time it starts:

| Data | Purpose |
|---|---|
| Device identifier | A string produced by a one-way hash (SHA-256) of the system identifier combined with this game's name. It is valid only for this game, cannot be reversed into the original system identifier, and cannot be used to recognize you in other apps. Used to count installs, manage how many devices an account can be signed in on, and prevent abuse. |
| System type | For example "android" or "windows". Used to investigate compatibility problems. |
| Game version | Used to investigate problems and understand which versions are in use. |

The game also downloads a balance configuration file from our server. As with any network request, the server sees your IP address and may record it in access logs, which are used only for security and troubleshooting.

### 1.3 Data you provide when you create or sign in to an account (optional)

**The Google Play version has no account with us.** It uses the Google Play Games sign-in described in section 1.1, and this section does not apply to it.

In versions from other channels, an account is not required. Only if you choose to register or sign in do we collect:

| Data | Purpose |
|---|---|
| Email address | Your account name, used for signing in and for verifying your identity when you make a request. |
| Password | Stored only as a salted scrypt hash. We cannot see your original password. |
| Signed-in devices | The device identifier, system type, version and sign-in time described above, so you can review and remove devices. |
| Entitlements | Whether you have unlocked paid features, when they expire, and redemption codes you have used. |

### 1.4 Purchases

- **Google Play version**: paid features are bought through Google Play in-app purchases. Google processes the payment. We never receive your card or payment account details, only whether the order succeeded.
- **Versions from other channels**: payment goes through a third-party payment platform, which processes the payment details. We record only the order number and whether payment arrived.

### 1.5 What we do not collect

Location, contacts, photos, camera, microphone, SMS, call logs, the list of other apps on your device, or the Advertising ID. On Android the game requests only the Internet permission.

## 2. Visiting other towers

In the current version, "Visit" shows only sample towers built into the game and **does not upload your tower**. If online sharing is added later, your tower's layout, its name and your owner name will be sent only when you actively choose to upload, and we will update this policy first.

## 3. What we do not do

- We do not sell your personal information.
- We do not use your information for advertising or profiling.
- We do not include third-party advertising or analytics SDKs. (The Google Play version includes the Google Play Games Services SDK, used only for sign-in and cloud saves.)

## 4. AI residents (optional, off by default)

In Settings you can enter the address and key of your own AI model service so residents can use it to generate dialogue. When enabled, the game sends the dialogue context (fictional in-game content such as a resident's name, job and situation) **directly from your device to the address you entered**. It does not pass through our servers and we do not receive it. How that service handles data depends on its own privacy policy. The address and key are stored only on your device.

## 5. Retention and storage

- Account data is kept until you ask us to delete your account.
- Device identifier records that were never linked to an account are kept for up to 24 months after the last launch.
- Server access logs are kept for up to 90 days.
- Data is stored on servers we rent, and all transfers use HTTPS encryption.

## 6. Your rights

At any time you can:

- **Access and correct**: on the Account page in the game, view your email, change your password, and review or remove signed-in devices (Google Play version: the Cloud Saves page shows your sign-in status and the saves in the cloud).
- **Delete your account and related data**: see [How to delete your account](delete-account.md). We complete deletion within 30 days of verifying your identity.
- **Withdraw consent**: uninstalling the game stops all data collection.
- **Ask questions or complain**: contact us as described in section 9.

If you are in the EU, the UK, California or a similar jurisdiction, you also have the rights given by local law, such as access, portability, restriction and objection, which you can exercise through section 9. Our legal bases for processing are your consent (the device check-in) and performing our service agreement with you (accounts and paid features).

## 7. Children

The game is not directed to children under 13 (or the higher age set in your region), and we do not knowingly collect their personal information. The game includes simulated gambling minigames that involve no real money (see the [Terms of Use](terms.md)). If you are a guardian and believe your child has given us personal information, contact us and we will delete it.

## 8. Changes to this policy

When the policy changes in a material way, we update the effective date on this page and ask you to confirm again when the game starts.

## 9. Contact

- Open an issue on GitHub: <https://github.com/datianda/skyscraper-town/issues>

Please do not include passwords or other sensitive details in a public issue.
