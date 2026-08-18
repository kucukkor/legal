# Privacy Policy for SVARM

**Last Updated:** August 18, 2026

SVARM is published by the game's independent developer ("we"). We value your
privacy. This policy explains how we
handle your data in "SVARM: Co-op Survival" ("SVARM"). SVARM is an **online
co-op game with its own game server**: unlike our earlier titles, some game data
is stored on our backend so your progress can follow your account across
devices. This document describes exactly what that server stores, which
third-party services are involved, and how you can delete your data.

## 1. Data Stored on Our Game Server

When you first launch SVARM, a **guest account** is created automatically. A
guest account is anonymous — it is created without any personal information. We
store the minimum needed to run the game:

- **Account record**: an internal numeric account ID, a public player code
  (friend code), and an auto-generated nickname. **We do not store your name,
  email address, phone number, precise location, or contacts.**
- **Optional sign-in link**: if you choose to link Sign in with Apple or Google
  Sign-In to protect your progress, we store only the provider's **subject
  identifier** (an opaque ID). We do not receive or store your name or email
  from the provider.
- **Game progression**: in-game gold balance, weapon unlocks, permanent upgrade
  levels, and match results (waves reached, kills).
- **Purchase records**: which in-app products your account has bought (product
  ID, store, transaction reference), so the server can grant the corresponding
  gold or unlock and restore it later. We never see your payment method.

All traffic between the app and our server uses **encrypted connections**
(HTTPS / secure WebSocket). We do not sell your data, and we do not use the
data on our server for advertising profiling.

## 2. Third-Party Services Used by SVARM

### 2.1 Sign in with Apple / Google Sign-In (optional)

Only used if you choose to link your account for cross-device recovery.
Authentication happens on your device with Apple / Google; SVARM receives a
verified token and stores only the opaque subject identifier described in §1.

- Apple's privacy policy: <https://www.apple.com/legal/privacy/>
- Google's privacy policy: <https://policies.google.com/privacy>

### 2.2 RevenueCat (in-app purchase processing)

Used to validate, deliver, and restore in-app purchases (Remove Ads
non-consumable + gold pack consumables). Purchases are associated with your
SVARM account ID so that gold and unlocks can be granted by our server and
restored on a new device. RevenueCat processes the App Store / Google Play
receipt that Apple or Google generates on your behalf.

- RevenueCat's privacy policy: <https://www.revenuecat.com/privacy/>

### 2.3 Google AdMob (interstitial + rewarded ads)

SVARM shows interstitial ads between runs and an **optional** rewarded ad for
the in-run revive. AdMob uses your **Advertising ID** (IDFA / GAID) to serve
and measure ads. On iOS, SVARM respects the App Tracking Transparency
framework — if you decline tracking, AdMob serves non-personalized ads. You can
remove interstitial ads entirely with the "Remove Ads" purchase; the rewarded
revive ad remains strictly optional.

- Google AdMob privacy: <https://policies.google.com/technologies/ads>

### 2.4 Apple Game Center / Google Play Games Services (leaderboards)

Used for leaderboards only, if you choose to sign in. Sign-in is handled by
your device's operating system (Apple ID / Google Account) — SVARM does not
store your platform handle or credentials; Apple and Google manage that data on
your behalf.

- Apple's privacy policy: <https://www.apple.com/legal/privacy/>
- Google's privacy policy: <https://policies.google.com/privacy>

### 2.5 App Stores (Apple App Store / Google Play)

All payments are processed by the App Store or Google Play. We never see or
store your payment details.

## 3. Services We Do NOT Use

To be explicit, SVARM v1.0 does **NOT** integrate:

- Google Analytics for Firebase, Firebase Crashlytics, Sentry, or any other
  third-party analytics / crash-reporting SDK beyond what AdMob includes
- Facebook / Meta SDKs of any kind
- iCloud or Google Drive save sync (progress lives on our own game server
  instead, tied to your account)

If a future version adds any such service, this policy will be updated before
that version ships.

## 4. Data on Your Device

Settings (audio, language, theme, control preferences) and session tokens are
stored locally on your device. Deleting the app removes them.

## 5. Children's Privacy

SVARM is intended for adults (18+) due to its combat theme and is not directed
at children. We do not knowingly collect personal data from children under 13.
If you believe a child has used SVARM, contact us at the email below.

## 6. Data Retention & Deletion

You can permanently delete your account **at any time, inside the app**:
**Settings → Account → Delete account.** This is immediate and irreversible:
your account record, sign-in links, progression, and in-game gold are erased
from our server. Purchase records that we are legally required to keep for
accounting purposes may be retained in a form no longer linked to a usable
account.

Other data holders:

- **RevenueCat** purchase records — deleted via RevenueCat's data subject
  request process; contact us (§7) and we will initiate it for you.
- **AdMob** ad data — managed via Google's Ads Settings (Android) or the
  Tracking settings on your device (iOS).
- **Game Center / Play Games Services** leaderboard entries — managed via your
  Apple ID / Google Account settings.
- **Local device data** — removed by deleting the app.

## 7. Contact Us

If you have any questions about this policy or your data, contact us at:
<info@esimostudios.com>

You can also reach us from inside the game: **Settings → Credits → Contact us**.
