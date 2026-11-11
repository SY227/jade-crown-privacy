# Jade Crown: Phoenix Rising Privacy Policy

**Last updated:** November 11, 2026

Jade Crown: Phoenix Rising (“Jade Crown,” “we,” “us”) is a single-player game developed by FoxForge Studio.

Jade Crown is designed as a local-first game. The current version does not require an account and does not transmit your gameplay progress or saved journey data to FoxForge Studio or to third-party analytics, advertising, AI, or cloud-storage services.

This Privacy Policy explains what information the game stores locally, how local saves and recovery copies work, and what choices are available to you.

---

# Summary

- Jade Crown does not require an account or login.
- Gameplay progress and settings are stored locally on your device.
- Jade Crown does not upload your journey, choices, scores, checkpoints, or settings to FoxForge Studio.
- Jade Crown does not use advertising.
- Jade Crown does not use cross-app or cross-website advertising tracking.
- Jade Crown does not include third-party analytics or crash-reporting SDKs.
- Jade Crown does not use third-party AI services.
- Jade Crown does not use CloudKit to synchronize game progress.
- Jade Crown does not use Game Center in the current release.
- Jade Crown does not request camera, microphone, location, contacts, or photo-library access.
- Jade Crown offers an optional, one-time Full Campaign in-app purchase through Apple's App Store. There is no recurring subscription.
- Local recovery and previous-journey copies may be retained on the device to protect game progress.
- Deleting Jade Crown removes data from the app's active local container, subject to normal iOS backup and restore behavior.

---

# Information stored locally

## 1) Game progress

Jade Crown stores gameplay progress locally on your device.

The local save may contain information such as:

- completed missions;
- campaign progress;
- story choices;
- discovered endings;
- mission best records;
- awarded mission rewards;
- viewed story sequences;
- current campaign act;
- selected combat style;
- selected weapon system;
- preferred support choices;
- routine support selections;
- practice records;
- mastery-trial records;
- unlocked or earned gameplay content;
- local timestamps; and
- information needed to resume the journey.

This information is used to provide the game experience and restore your progress.

Jade Crown does not transmit this saved gameplay information to FoxForge Studio.

---

## 2) Current battle checkpoint

Jade Crown can save the current state of an unfinished mission so you can continue later.

A checkpoint may contain information such as:

- current mission;
- current story screen;
- dialogue position;
- player health;
- selected powers and upgrades;
- weapon selection;
- combat style;
- enemies and objectives;
- mission state;
- current score and progress;
- battle timing;
- random game-state information required to reproduce the saved encounter; and
- other gameplay state required to resume the mission.

These checkpoint details remain local to the game's save file.

---

## 3) Game settings

Jade Crown stores settings locally, including preferences such as:

- English or Traditional Chinese language;
- music on/off;
- sound effects on/off;
- music volume;
- effects volume;
- haptics;
- reduced motion;
- visual-quality preference;
- difficulty;
- left-handed controls;
- text size;
- combat text size;
- control size; and
- whether the controls guide has already been viewed.

These preferences are stored with the local game save.

---

## 4) Chronicle, gallery, endings, and records

Jade Crown uses your locally saved progress to determine information shown in features such as:

- Chronicle;
- artwork gallery;
- unlocked story content;
- discovered endings;
- practice records;
- mastery records;
- earned styles;
- earned keepsakes; and
- mission bests.

These features are calculated from or stored with local game progress.

They are not uploaded to a FoxForge Studio server.

---

# Local save storage

## 5) Active save

Jade Crown stores its active journey in the app's private Application Support storage.

The current save format uses a local JSON file.

The app validates saved information before loading it to reduce the risk of using damaged or incompatible save data.

---

## 6) Previous valid save

When Jade Crown successfully replaces an existing valid save, it may keep the previous valid save locally as a recovery copy.

This recovery copy can be used if the newest active save cannot be read safely.

The recovery copy remains on the device and is not uploaded.

---

## 7) Legacy save migration

Older versions of Jade Crown used an earlier save format.

When compatible older data is found, Jade Crown may migrate selected information into the current save format.

Legacy information preserved during migration may include:

- completed original chapters;
- earlier story choices;
- earlier best records;
- earlier discovered endings; and
- whether an earlier battle checkpoint existed.

The current game can keep this information as a local historical record.

---

## 8) Unreadable-save recovery copies

If Jade Crown detects save data that cannot safely be read, the app is designed to preserve copies rather than silently overwrite the unreadable information.

These recovery copies remain inside Jade Crown's local application storage.

They may remain until the app's local data is removed.

---

# New Journey and archived journeys

## 9) Starting a new journey

When you choose **Begin a new journey**, Jade Crown resets the active campaign and its current story choices.

Before replacing an existing journey, the app may archive the prior journey locally.

The game explains that certain earned or discovered information can continue into the new journey, including applicable:

- styles;
- gallery discoveries;
- endings;
- best records; and
- settings.

---

## 10) Previous Journey archives

Before beginning a new campaign, Jade Crown may save the previous journey as a separate local archive.

A previous-journey archive can contain the gameplay information that was present in the earlier save.

These archives are stored locally in Jade Crown's private Application Support storage.

They are not uploaded to FoxForge Studio.

The current release does not provide a separate interface for individually deleting every archived previous-journey file.

Deleting Jade Crown removes files from its active local application container, subject to normal iOS backup and restore behavior.

---

# Local security

## 11) File protection

Jade Crown writes its active save and archived journeys using Apple's local file-protection mechanisms on iOS.

The current implementation uses protection that keeps applicable files protected until the device has been unlocked after startup.

The game also uses atomic file writes to reduce the risk of incomplete saves.

No storage method can be guaranteed to be completely secure.

---

## 12) Save validation

Jade Crown validates important aspects of local saves before loading them.

This may include checks on:

- save format version;
- mission identifiers;
- story-choice values;
- checkpoint consistency;
- combat state;
- practice records; and
- mastery records.

These checks occur locally and do not send your saved data to a remote service.

---

# System timing information

## 13) System uptime

Jade Crown uses Apple's system-uptime API for limited technical purposes such as:

- timing scene preparation;
- monitoring whether scene preparation has completed;
- measuring local presentation/preparation duration; and
- coordinating gameplay or interface timing.

Jade Crown's privacy manifest declares use of the applicable required-reason system boot-time API.

This system timing information is used locally for app functionality.

Jade Crown does not use system uptime to identify you, track you across apps, or build an advertising profile.

The current implementation does not transmit this system-uptime information to FoxForge Studio.

---

# Audio and haptics

## 14) Game audio

Jade Crown uses bundled game music and sound effects.

The current implementation loads game audio from resources included with the app.

Jade Crown does not require microphone access to play game audio.

---

## 15) Haptics

If haptics are enabled, Jade Crown uses Apple's local haptic-feedback APIs for gameplay feedback.

Haptic use does not require Jade Crown to collect personal information.

---

# Information Jade Crown does not request during normal gameplay

The current release does not request ordinary app access to:

- contacts;
- precise location;
- approximate location;
- camera;
- photo library;
- microphone;
- Speech Recognition;
- health data; or
- advertising tracking permission.

Jade Crown does not require a FoxForge Studio account.

---

# Network activity and third parties

## 16) No gameplay-data network service

The current Jade Crown app target does not include a developer-operated network service for gameplay data.

The current implementation does not contain an app-level URLSession networking flow for sending your journey or gameplay information to FoxForge Studio.

Jade Crown does not use:

- Firebase;
- Google Gemini;
- OpenAI;
- CloudKit;
- Game Center;
- Firebase Analytics;
- Firebase Crashlytics;
- advertising SDKs; or
- a FoxForge Studio gameplay server.

---

## 17) Apple and iOS

Jade Crown relies on Apple-provided platform technologies such as:

- iOS application sandboxing;
- SwiftUI;
- UIKit;
- SpriteKit;
- AVFoundation;
- StoreKit for product information, purchases, and verified purchase access;
- local file storage;
- file protection; and
- haptic-feedback APIs.

Apple may independently process technical information as part of operating iOS, distributing the app through the App Store, providing device backups, or supplying other operating-system services.

Apple's independent handling of information is governed by Apple's applicable policies.

Apple privacy information:

https://www.apple.com/legal/privacy/

---

# Advertising, tracking, and analytics

## 18) No advertising

Jade Crown does not display third-party advertising.

---

## 19) No tracking

The current Jade Crown privacy manifest declares tracking as disabled.

Jade Crown does not use gameplay information for cross-app or cross-website advertising tracking.

---

## 20) No analytics or crash-reporting SDK

The current release does not include a third-party analytics or crash-reporting SDK in the Jade Crown app target.

Jade Crown does not operate a remote analytics database containing your gameplay choices, battle state, or journey history.

---

# Purchases and accounts

## 21) Full Campaign in-app purchase

Jade Crown uses Apple's StoreKit to offer one optional, one-time Full Campaign purchase that unlocks missions 07–48. This is a non-consumable purchase, not a recurring subscription. Missions 01–06 remain free to play.

Apple handles payment and purchase restoration through the App Store. Buying and restoring purchases require a connection and may require Apple Account authentication.

The app reads Apple-verified transaction information, including the product identifier, transaction identifier, and entitlement, revocation, or expiration status, to determine whether the Full Campaign is unlocked. This information also lets the app restore access to a previously purchased Full Campaign and respond to refunds or revoked access.

The current Jade Crown implementation does not transmit transaction information or your saved journey to a FoxForge Studio server. FoxForge Studio does not receive your full payment-card information from Jade Crown. Apple's handling of purchase and payment information is governed by Apple's applicable policies.

---

## 22) No Jade Crown account

Jade Crown does not require you to create a developer-hosted account.

There is no FoxForge Studio Jade Crown profile, login, or cloud gameplay account in the current release.

---

# Local retention and deletion

## 23) Active gameplay data

The active local journey remains on your device until it is:

- replaced through normal game behavior;
- reset as part of beginning another journey;
- removed when the app's local data is deleted; or
- otherwise affected by normal iOS backup and restore behavior.

---

## 24) Recovery and archive retention

Jade Crown may keep:

- a previous valid save;
- legacy save information;
- unreadable-save recovery copies; and
- previous-journey archives.

These copies exist to protect progress, support migration, preserve earlier journeys, or avoid destructive loss when a save cannot be read safely.

Some of these historical copies may remain locally even after the currently active journey changes.

The current release does not provide one in-game control that individually deletes every recovery or archived journey file.

---

## 25) Beginning a new journey is not complete deletion

Beginning a new journey resets the active campaign, but it is not designed as a complete privacy deletion function.

The previous journey may first be archived locally, and selected earned/discovered information may remain in the new active save.

---

## 26) Deleting the app

Deleting Jade Crown removes information stored in the app's active application container from the device, subject to normal iOS behavior.

Device or computer backups made outside Jade Crown may retain copies according to the backup system's own policies and retention behavior.

FoxForge Studio cannot delete copies controlled by Apple's device-backup systems or other backups outside the app container.

---

# Privacy manifest

## 27) Current privacy manifest

The current Jade Crown privacy manifest declares:

- tracking: **false**;
- tracking domains: none; and
- collected data types: none.

The manifest declares access to Apple's required-reason System Boot Time API for app functionality.

The privacy manifest describes the current app implementation and does not override disclosures in this Privacy Policy.

---

# Support communications

## 28) Voluntary email

Support and privacy communications are optional and separate from normal Jade Crown gameplay.

Jade Crown does not automatically attach your saved journey, battle state, choices, or local files to an email.

If you contact FoxForge Studio at **support@foxforgestudio.ai**, we receive the information you voluntarily provide.

This may include:

- your email address;
- your name, if you include it;
- the subject of your message;
- message contents;
- timestamps;
- attachments you deliberately include; and
- technical or gameplay information you choose to describe.

We use support communications to respond to your request, investigate reported problems, troubleshoot issues, prevent abuse, maintain reasonable support history, and meet applicable legal obligations.

The **support@foxforgestudio.ai** mailbox is hosted through **Google Workspace / Gmail, provided by Google LLC**.

Google processes the information necessary to route, deliver, store, secure, and filter those messages according to its applicable policies.

Google Privacy Policy:

https://policies.google.com/privacy

---

## 29) Support-message retention and deletion

Support emails may be retained while a support request is open and for a reasonable period afterward when needed for:

- follow-up;
- troubleshooting;
- security;
- abuse prevention; or
- applicable legal obligations.

FoxForge Studio does not promise one fixed automatic deletion period for support messages.

Support messages may remain in Google Workspace / Gmail according to Google's applicable retention, security, backup, and service practices.

You may request deletion of a support conversation that you previously sent by emailing:

**support@foxforgestudio.ai**

Please provide enough information to identify the applicable conversation.

Where reasonably possible, we will delete the identified communication from active support records, subject to legal, security, fraud-prevention, backup, and provider-related retention requirements.

Deleting a support conversation does not change the local Jade Crown save stored on your device.

---

# Privacy-policy hosting

## 30) GitHub Pages

This Privacy Policy is hosted using **GitHub Pages, operated by GitHub, Inc.**

Visiting this privacy-policy webpage is separate from using Jade Crown.

GitHub states that GitHub Pages logs visitors' IP addresses for security purposes.

Jade Crown does not send your local save, battle state, settings, choices, scores, or journey history to GitHub Pages.

GitHub Privacy Statement:

https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

---

# Same or equal protection

Jade Crown does not currently share gameplay or saved-journey data with third-party analytics, advertising, AI, or cloud-gameplay providers.

Apple independently provides the operating-system and App Store services described above.

Google Workspace / Gmail processes information only when you voluntarily contact FoxForge Studio.

Any third party with whom Jade Crown or FoxForge Studio shares user data will provide the **same or equal protection of user data** as stated in this Privacy Policy and as required by Apple's App Review Guidelines.

---

# Your choices

You can:

- play without creating an account;
- change game and accessibility settings;
- choose whether to use haptics;
- start a new journey;
- continue a locally saved journey;
- choose whether to send information in a support email; and
- delete the app to remove information from the active local app container, subject to normal iOS backup and restore behavior.

Starting a new journey is not equivalent to deleting every local historical or recovery copy because the game may archive the previous journey before resetting the active campaign.

---

# Children's privacy

Jade Crown does not operate an account system or online gameplay database through which children provide profile information.

The current game does not transmit locally saved gameplay information to FoxForge Studio.

---

# Changes to this policy

We may update this Privacy Policy if Jade Crown's features, providers, storage behavior, or data practices change.

The **Last updated** date above reflects the latest version.

---

# Contact

For questions or privacy requests regarding Jade Crown: Phoenix Rising, contact:

**FoxForge Studio**

**Email:** [support@foxforgestudio.ai](mailto:support@foxforgestudio.ai)

