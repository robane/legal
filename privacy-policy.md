---
title: Privacy Policy
permalink: /privacy-policy/
---

# Privacy Policy

**Effective date:** 7 September 2026
**Last updated:** 19 November 2026

This Privacy Policy explains how **robane** ("we", "us", "our") processes
personal data in connection with the mobile games we publish ("the Games",
and each one "the Game"): **Word Popping!**, **Pic Sort**, **Cube Out 3D**,
**Tap Blocks!** and **Color Mahjong**.
The policy has a common part that applies to every Game and a
[per-game section](#20-per-game-specifics) that says which parts apply to
which Game.

## Who we are

robane is the games brand of Robert Aneszko, a sole trader based in Poland.
We are the **data controller** for the purposes of the EU General Data
Protection Regulation (Regulation (EU) 2016/679, "GDPR"). You can reach us at
**robane.games@gmail.com** for any privacy-related question.

---

## 1. Summary

- You never create an account. We never ask for your name, email address,
  or anything else that identifies you directly.
- Games that back up your progress generate a **random player id** on first
  launch. It says nothing about who you are, but it is stored on your device
  and used to back up your progress and to group your gameplay statistics.
  Games that do not back up progress have no player id at all.
- Where a Game backs up progress, the backup is stored in the **European
  Union** and is read back only when the Game finds no local progress — the
  reinstall case.
- Some Games collect **gameplay analytics and crash reports** through Google
  Firebase, so we can see where a game breaks, where it is too hard, and
  which features are used.
- The Games show **ads**. On iOS the system asks at first launch whether the
  Game may track you. If you appear to be in the **EEA or the UK**, the Game
  shows a consent dialog for advertising (section 7). If you decline, or never
  answer, ads are **contextual** — not based on a profile of you. You can
  change your answer at any time in the Game under **Settings → Privacy**.
- Where a Game offers **in-app purchases**, the store (Apple or Google)
  processes the payment; we never see your payment details.
- Data the Games send travels **encrypted**
  ([section 21](#21-how-we-protect-your-data)).

---

## 2. Identifiers we and our partners use

- **Player id** — in Games that back up progress: a random identifier
  created by Firebase Authentication ("anonymous sign-in") the first time you
  open the Game. It is not connected to an Apple ID, a Google account, an
  email address, or any account. On iOS it is kept in the device keychain,
  which lets your progress backup be found again after a reinstall. On Android
  it is kept in the app's private storage; it survives a reinstall only if
  Android's own backup restores the app's data, which also restores your
  progress on the device.
- **App and device identifiers** — on iOS the vendor identifier (IDFV); where
  the Game uses Firebase, the Firebase app instance id, the Firebase
  installation id and the Crashlytics installation id.
- **Advertising identifier** — the IDFA on iOS, available to us and our
  advertising partners **only if you allow tracking** (section 6); the Google
  advertising id on Android, available unless you delete or reset it in your
  device's ad settings.
- **IP address** — seen by every service the Game contacts. It is used to
  route traffic, to derive coarse (city-level) location for ad delivery, and,
  by our consent and advertising partners, to determine whether EU/UK rules
  apply to you.

## 3. Data stored on your device

- Your game progress: current level, coins, boosters, which tutorials you
  have seen
- Your settings
- Your advertising consent choices, in the standard IAB TCF format
- In Cube Out 3D, a log of your level attempts (date and time, level, result,
  time taken, each tap and drag, boosters used, device model). We use such
  logs to test difficulty on our own devices; on yours the log stays on the
  device, and the Game never sends it to us or anyone else.

Deleting the Game removes this data from your device. The exceptions, in the
Games that have them, are the backup described next and, on iOS, the player
id (section 2), which stays in the device keychain. On Android, if your
device's own backup is turned on, Android may keep a copy of the Game's data
in your Google account and restore it when you reinstall.

## 4. Your progress backup

In Games that back up progress, your progress is copied to **Google Cloud
Firestore**, a database we operate, under a record named after your player
id. The record is a copy of the game progress and settings stored on your
device (section 3). Depending on the Game, it includes your level, coin
balance and boosters; your sound, music, vibration and language settings;
which tutorials you have seen; how long, on how many days and in how many
sessions you have played, and the day you last played; the counters and times
that pace how often ads and rating requests appear; and flags for one-time
events already recorded — plus the save-format version, the app version and
a timestamp. It contains nothing that identifies you directly, such as a name
or an email address.

In Cube Out 3D, Tap Blocks! and Color Mahjong the record also keeps a short **play journal**:
the days you played; for each level, how many attempts you made, how the
first one ended, how long they took, the boosters used, and in Tap Blocks!
the lives lost and continues taken; your last sessions (the day, the level
you started and ended on, how long you played, and whether a reminder opened
the Game); how often you saw the out-of-lives screen and the ads you watched;
and the app version you installed. It also keeps a short **description of
your connection**, taken when the Game starts: your device's country (from
your mobile network or region setting), whether a VPN or Android's Private
DNS is in use and the Private DNS host name, the addresses of the DNS servers
your network uses (for IPv6, only the part that names the internet provider),
whether the Game could reach our analytics and advertising services, and how
the ad system started. We use it to find out why some players never receive
ads or appear in our analytics. Our own test devices carry a tester flag so
we can leave them out.

The backup is hosted in the **European Union** (Google's `europe-central2`
region, Warsaw) and is read back only when the Game finds no local progress —
the reinstall case. Local progress otherwise always wins.

## 5. Analytics and crash reports

In Games that use them, we rely on **Google Firebase Analytics** and
**Firebase Crashlytics**.

Analytics events describe how the game is played — for example a level
started or completed, a booster used, an ad shown (including what it earned),
a purchase started or granted, a settings change. Each event carries your
player id, the app version, your device model and operating system version,
your language, a country derived from your IP address, and, where it applies,
the ad campaign that led to your install (section 8). Cube Out 3D and Color
Mahjong also record a coarse description of your device's capabilities (memory, processor
cores, graphics chip) each time the Game starts, so that we can choose the
right frame rate for phones like yours. If you allow notifications, Cube Out
3D, Tap Blocks! and Color Mahjong schedule their reminders on your device itself; we record
only whether you allowed them and when you open one.

Crash reports contain the technical state of the Game when it stopped
working: stack traces, device model, operating system version, and the
sequence of events leading up to the crash.

Analytics events may be exported daily into our own analysis database
(Google BigQuery, also in the EU, `europe-central2`).

We use all of this to fix bugs, balance difficulty, understand which features
are used, and measure whether our advertising pays for itself.

## 6. Advertising and tracking permission

Ads in the Games are delivered by advertising partners named per game in
section 20: **Unity LevelPlay** (the ironSource mediation platform, operated
by Unity Technologies), serving ads from the ironSource Ads and Unity Ads
networks and, in the Games that use them, Google AdMob, **Meta Audience
Network**, **Mintegral** and **InMobi** bidding inside LevelPlay; or **Google
AdMob** directly.

On iOS, at first launch, the system shows you Apple's **App Tracking
Transparency** prompt:

- **If you allow tracking**, your device's advertising identifier (IDFA) is
  made available to our advertising partners. Ads may then be personalized,
  and ad performance can be measured across apps.
- **If you decline, or never answer**, the IDFA is not available. Ads are
  contextual — chosen from the situation, not from a profile of you.

You can change this at any time in **iOS Settings → Privacy & Security →
Tracking**.

On Android there is no equivalent system prompt. Your Google advertising id
is available to our advertising partners unless you delete or reset it in
**Android Settings → Google → Ads**; where the Game shows you the consent
dialog in section 7, your answer there governs whether ads may be
personalized.

To deliver ads, cap how often you see the same ad, prevent fraud, and measure
that an ad was shown, our advertising partners may process your IP address
(and coarse, city-level location derived from it), device information (model,
operating system version, language, app version, network type, mobile
carrier), the app or vendor
identifier, the advertising identifier where available, identifiers the
partners assign to your device or installation themselves, ad interaction
events (impressions, clicks, video completions), information about any
in-app purchases made in the Game, and technical diagnostics related to ad
delivery, including crash reports.

Unity's practices are described in the
[Unity Player and App User Privacy Policy](https://unity.com/legal/game-player-and-app-user-privacy-policy);
Google's at <https://policies.google.com/privacy>; Meta's at
<https://www.facebook.com/privacy/policy/>; Mintegral's at
<https://www.mintegral.com/en/privacy/>; InMobi's at
<https://advertising.inmobi.com/privacy-policy>.

## 7. Consent in the EEA and the UK

If you appear to be in the European Economic Area or the United Kingdom, the
Game shows you a **consent dialog** at first launch, provided by Google's
User Messaging Platform, which uses your IP address to decide whether the
dialog is required where you are. Word Popping!, Cube Out 3D, Tap Blocks! and
Color Mahjong first check your device's region — on iPhone from your iPhone's region
setting; on Android from your mobile network, then your SIM card, then your
device's region setting — and ask the User Messaging Platform only when that region is
in the EEA or the UK. Your choices are recorded on your device as an IAB TCF
consent string, together with Google's additional-consent record for partners
outside that framework, such as Meta. The mediation platform and our
advertising partners use these records when serving ads.
In Games that do not serve ads through Google, the User Messaging Platform is
used for this consent record only.

You can review and change these choices at any time: open the Game's
**Settings** and tap **Privacy**.

If you do not consent to personalized advertising, you still see ads, but
they are contextual.

## 8. Install attribution

In Games where we advertise on Apple's platforms:

- **Apple SKAdNetwork.** The Game participates in Apple's SKAdNetwork
  framework, which tells advertisers that an install happened without
  identifying you. Attribution is aggregated and delayed by the operating
  system.
- **Apple Ads attribution.** If you installed the Game after tapping one of
  our ads on the App Store, iOS gives the Game a token that we exchange with
  Apple for the campaign and ad group that brought you in. We store that
  campaign information alongside your analytics data. It identifies a
  campaign, not a person.

On Android, install attribution, where we measure it, relies on the
aggregated reporting provided by Google Play and our advertising partners.

## 9. In-app purchases

Where a Game sells items (coin packs), the store processes the payment:
**Apple** on iOS, **Google Play** on Android. We never receive your card
details, your store account, or your billing address — only the store's
confirmation that a purchase completed.

We record that a purchase was started and that coins were granted, together
with the product bought and your coin balance, against your player id where
the Game has one. We use this to make sure purchases are delivered correctly
and to understand what players buy.

## 10. Remote configuration

Games that use Firebase download a small set of settings from **Firebase
Remote Config** (for example how often ads appear), so we can adjust the game
without shipping an update. The request carries standard app and device
information.

## 11. Data processed by the store

- **Store analytics.** If you have opted in to sharing analytics with
  developers in your device settings, Apple or Google provides us with
  aggregated usage statistics such as install counts and retention. These
  are anonymous aggregates; we cannot identify you from them.
- **Crash diagnostics.** The store may share crash reports with us under the
  same opt-in.

## 12. Legal basis for processing

| Processing activity | Legal basis (GDPR Art. 6) |
|---|---|
| Running the game, storing and restoring your progress | Performance of the service you request (Art. 6(1)(b)) |
| Selling and delivering in-app purchases | Performance of the service you request (Art. 6(1)(b)) |
| **Personalized advertising** in the EEA/UK | **Your consent** (Art. 6(1)(a)), given through the dialog in section 7 and withdrawable at any time |
| Contextual advertising, frequency capping, fraud prevention, and ad measurement | Legitimate interest in funding a free game (Art. 6(1)(f)) |
| Analytics and crash reporting, to keep the Game working and improve it | Legitimate interest in maintaining and improving our product (Art. 6(1)(f)) |

Where we rely on a legitimate interest, you have the right to object — see
section 15.

## 13. US state privacy rights

If you allow tracking (iOS) or keep your advertising id (Android),
identifiers about your device are shared with our advertising partners so
that ads can be personalized. Some US state privacy laws, including
California's, treat that kind of sharing as a "sale" or "sharing" of personal
information.

To opt out, turn tracking off for the Game in **iOS Settings → Privacy &
Security → Tracking**, or delete your advertising id in **Android Settings →
Google → Ads**. This removes the advertising identifier, so it can no longer
be used to personalize your ads. If you have questions about this, email us at
**robane.games@gmail.com**.

We do not knowingly sell or share the personal information of anyone under 16.

## 14. How long we keep data

- **Your progress backup** — kept while you play (each session overwrites it)
  and until you ask us to delete it.
- **Analytics events** — kept for a limited period under Google Analytics'
  retention settings and then deleted automatically. Copies exported to our
  analysis database (section 5) are kept until we delete them; we delete a
  player's copies when asked (section 15). Aggregated statistics that no
  longer identify a device may be kept longer.
- **Crash reports** — kept by Firebase Crashlytics for 90 days, then deleted.
- **Player id** — kept by Firebase Authentication until we delete it, which we
  do when asked (section 15).
- **Data held by our advertising partners** — kept according to their own
  retention schedules, described in their privacy notices.

## 15. Your rights under GDPR

You have the right to **access**, **rectify**, and **erase** your personal
data, to **restrict** or **object to** processing, to **data portability**,
and to **withdraw consent** at any time where processing is based on consent.

A practical note: we hold no name, email, or account for you. Everything
described here is keyed to the random player id on your device, where the
Game has one. If you write to us, we will do our best to find and act on your
record, and we may need details that let us locate it — roughly when you
installed the Game and the level you had reached. If we cannot identify your
data, we will tell you.

- **To delete local data**, delete the Game.
- **To delete your backup and analytics data**, email
  **robane.games@gmail.com**.
- **To withdraw advertising consent**, use **Settings → Privacy** in the Game
  (EEA/UK), turn off tracking in iOS Settings, or delete your advertising id
  in Android Settings.

You can lodge a complaint with the Polish data protection authority:

> Urząd Ochrony Danych Osobowych (UODO)
> ul. Stawki 2, 00-193 Warszawa, Poland
> <https://uodo.gov.pl>

## 16. International transfers

Progress backups and our analysis database are hosted in the European Union.
Firebase Analytics and Crashlytics are operated by Google and may process
data on servers outside the EEA, including in the United States. Our
advertising partners (Unity Technologies, including its ironSource platform,
Google and, in the Games that use them, Meta, Mintegral and InMobi) and the
store operators (Apple, Google) operate globally.

Where personal data is transferred outside the EEA, these transfers rely on
the EU-US Data Privacy Framework and/or Standard Contractual Clauses, as
required by GDPR Articles 45-46.

## 17. Children

The Games are not directed at children under 16, and we do not knowingly
collect personal data from children. If you believe a child has used a Game
and you would like the associated data removed, contact us and we will delete
it.

## 18. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the
top reflects the most recent revision. Material changes will be communicated
through the Games where reasonably possible.

## 19. Contact

robane
Poland
Email: <robane.games@gmail.com>

## 20. Per-game specifics

| | Word Popping! | Pic Sort | Cube Out 3D | Tap Blocks! | Color Mahjong |
|---|---|---|---|---|---|
| Platform | iPhone (App Store) | iPhone (App Store) | iPhone (App Store) and Android (Google Play) | Android (Google Play) | Android (Google Play) |
| In-app purchases | Yes — coin packs via Apple (section 9) | Yes — via Apple (section 9) | Yes — coin packs via Apple and Google Play (section 9) | No | Yes — coin packs via Google Play (section 9) |
| Player id and progress backup | Yes — anonymous Firebase id, backup in the EU (sections 2, 4) | No — progress stays on the device only | Yes — anonymous Firebase id, backup in the EU (sections 2, 4) | Yes — anonymous Firebase id, backup in the EU, with the play journal (sections 2, 4) | Yes — anonymous Firebase id, backup in the EU, with the play journal (sections 2, 4) |
| Analytics and crash reports | Firebase Analytics and Crashlytics (section 5) | None of ours; Apple's opt-in diagnostics only (section 11) | Firebase Analytics and Crashlytics, plus the device-capability record (section 5) | Firebase Analytics and Crashlytics (section 5) | Firebase Analytics and Crashlytics, plus the device-capability record (section 5) |
| Advertising partner | Unity LevelPlay — ironSource Ads and Unity Ads (section 6) | Google AdMob (section 6) | Unity LevelPlay — ironSource Ads and Unity Ads, plus Google AdMob, Meta Audience Network, Mintegral and InMobi bidding on Android (section 6) | Unity LevelPlay — ironSource Ads, Unity Ads and Google AdMob bidding; Meta Audience Network, Mintegral and InMobi bidding once enabled in the Game (section 6) | Unity LevelPlay — ironSource Ads, Unity Ads and Google AdMob bidding; Meta Audience Network, Mintegral and InMobi bidding once enabled in the Game (section 6) |
| Consent dialog (EEA/UK) | Google User Messaging Platform (section 7) | Google User Messaging Platform (section 7) | Google User Messaging Platform (section 7) | Google User Messaging Platform (section 7) | Google User Messaging Platform (section 7) |
| Tracking permission | Apple App Tracking Transparency (section 6) | Apple App Tracking Transparency (section 6) | iPhone: Apple App Tracking Transparency; Android: the Google advertising id (section 6) | Android: the Google advertising id (section 6) | Android: the Google advertising id (section 6) |
| Install attribution | Apple SKAdNetwork and Apple Ads attribution (section 8) | Not used | iPhone: Apple SKAdNetwork and Apple Ads attribution; Android: aggregated store and partner reporting where measured (section 8) | Android: aggregated store and partner reporting where measured (section 8) | Android: aggregated store and partner reporting where measured (section 8) |
| Remote configuration | Firebase Remote Config (section 10) | Not used | Firebase Remote Config (section 10) | Firebase Remote Config (section 10) | Firebase Remote Config (section 10) |

## 21. How we protect your data

- **Encryption in transit.** Everything the Games send over the network — to
  Firebase, to the app stores, and to our consent and advertising partners —
  travels over encrypted connections (HTTPS/TLS).
- **Encryption at rest.** In Games that use them, your progress backup (Cloud
  Firestore), your player id (Firebase Authentication), crash reports
  (Firebase Crashlytics) and our analysis database (Google BigQuery) are
  stored by Google, which encrypts that data at rest by default.
- **Access.** Only our own accounts can open our Firebase and Google Cloud
  projects and our advertising dashboards. The database rules let each Game
  installation read and change only the progress backup that belongs to its
  own player id.
- **Minimal data.** The Games never ask for your name or email address, and
  you never create an account. We keep data for the periods in section 14.
- **Incidents.** If a personal-data breach occurred, we would notify the
  Polish data protection authority (UODO) without undue delay and, where
  feasible, within 72 hours, unless the breach is unlikely to put anyone at
  risk, as GDPR Article 33 requires. If it were likely to put you at high
  risk, we would tell you, as Article 34 requires; because we hold no contact
  details for players, we would do this in the Games or on this page.
