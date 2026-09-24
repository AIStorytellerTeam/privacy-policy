---
title: "Privacy Policy"
permalink: /privacy/en/
lang: en
alt: /privacy/
altLabel: Русский
---
# Privacy Policy

**App:** AI Storyteller / Fairytale Gardens
**Data controller:** Turlaeva Elena Vladimirovna, Republic of Moldova
**Data contact:** aistoryteller.team@gmail.com
**Effective date:** 2026-08-31

## 1. Who and why
The account is created by an **adult** (parent/guardian). We process the minimum
data needed to run the App: creating stories, storing the family library, and
running subscriptions.

## 2. What data we collect
- **Adult account:** email; when signing in with Google — email and Google
  identifier. The password is stored hashed by the authentication provider
  (Supabase); we never see it in plain text.
- **Authentication data:** session tokens, so you are not asked to sign in on
  every launch. They are kept in the device's secure storage (Android Keystore /
  iOS Keychain) and are not shared with third parties.
- **Parent-section PIN:** stored on the device **as a salted hash**; we do not
  know the code itself and cannot recover it.
- **Biometrics (optional):** your fingerprint or face is verified by the
  **operating system itself**. The App only receives a "confirmed / not
  confirmed" answer; biometric data never leaves the device and is never sent
  to us.
- **Family and children profile (entered by the adult):** family name, child's
  name, date of birth/age, gender, chosen avatar, selected skills. This data is
  used to personalize stories. **Do not enter unnecessary personal data of children.**
- **Created content:** story texts, illustrations, audio narration — stored so
  you can return to them.
- **Technical data:** generation logs (time, plan, success/error status, which
  service handled it) — for limits, abuse prevention, and aggregated analytics.
- **Device identifier:** the identifier the operating system assigns to our app
  (ANDROID_ID on Android, identifierForVendor on iOS) and its hash. It is used
  for one purpose only — to prevent creating an unlimited number of accounts on
  a single phone to bypass the free limits. This is **not** a hardware number:
  it is app-specific, resets when the device is factory reset, and cannot be
  used to track you outside the App. We do not use it for advertising and do not
  share it with third parties. In practice this means a limited number of family
  accounts (two by default) can be registered from one device.
- **Purchase data:** the Google Play product identifier and purchase token, the
  subscription status and expiry date. The token is bound to your family so that
  a single paid receipt cannot be reused across several accounts. We **do not
  receive or store** card numbers or any other payment credentials — payment is
  handled entirely by Google Play.

We do **not** collect location or contacts, do not show personalized ads, and do
not sell data.

## 2.1. Abuse prevention
So that the free limits cannot be bypassed and the service stays available to
everyone, we apply:
- request rate limiting (how many generations per minute are allowed from one
  account) — for this, timestamps of requests are stored for a short time;
- counting the stories, illustrations and narrations created per day — to
  enforce the plan limit;
- the device binding and purchase-receipt binding described above;
- automatic suspension of generation after consecutive technical failures — so
  that neither your limits nor our resources are wasted.

The legal basis is our legitimate interest in protecting the service from abuse
(Art. 6(1)(f) GDPR for users in the EU).

## 3. Children's data
3.1. The App is operated on the child's behalf by an adult; the child's data is
entered by the adult, who can edit or delete it.
3.2. We do not ask children to provide personal data themselves and do not direct
advertising to children.
3.3. Provide only what is necessary about a child (name, age) — that is enough for
the stories.

## 4. Where and how data is stored
4.1. Data is stored in **Supabase** cloud infrastructure (database and file
storage). Access is restricted by security rules (RLS): a family only sees its own
data.
4.2. Illustrations and narration live in **private** storage. The app reaches
them through temporary signed links valid for a limited time; the files have no
permanent public addresses.
4.3. Third-party service secret keys are kept on the server and never sent to the app.
4.4. **On your device** the app keeps: sign-in credentials (in the operating
system's secure storage), the PIN hash, your settings, and a cache of
illustrations you have already seen. The cache makes a story open quickly and
work offline; it is size-limited, cleaned automatically as it fills up, and
removed entirely when you uninstall the app or reset data in settings.

## 4.1. Transfers outside the Republic of Moldova
Some of our providers (Supabase, Groq, Cloudflare, Together AI, Google,
ElevenLabs, Resend, Sentry) run servers in the European Union, the United States
and other countries. This means **cross-border data transfers**.

We keep what is transferred to a minimum: third-party AI services receive only
the request and scene text — no email address, no device identifier, and no link
to a child's identity beyond what the story itself needs. Transfers are made
under contracts with those providers that include Standard Contractual Clauses
(SCC) or equivalent safeguards, as required by Chapter V of the GDPR and
Articles 32-33 of Law No. 133/2011 of the Republic of Moldova.

## 5. Third-party services (sub-processors)
To run the App we send the **request/scene text** (without name or contacts, and
without linking to the child's identity beyond what is necessary) to third-party
AI services:
- **Text generation:** Groq (and, if connected, other LLM providers).
- **Illustration generation:** Cloudflare Workers AI, Together AI,
  Google (Gemini) — subject to availability.
- **Narration (optional):** cloud speech synthesis.
- **Infrastructure/authentication/storage:** Supabase.
- **Payments and distribution:** Google Play (Google).
Each service processes data under its own privacy policy. We try not to pass them
direct identity identifiers.

## 6. Legal bases
The controller is located in the Republic of Moldova, and processing is carried
out in accordance with Law No. 133/2011 of the Republic of Moldova on the
Protection of Personal Data. For users in the European Union we also rely on the
GDPR.
Grounds for processing: performance of the contract (providing the App's
features), consent (where applicable) and our legitimate interests (security,
abuse prevention).

## 7. Retention and deletion
7.1. We keep data for as long as your account exists. You can delete children's
profiles, individual stories, and the entire account from the App's settings.
7.2. **What account deletion does.** You start it from settings and it runs
immediately, with no waiting period. Deleted are:
- every database record — the family, children's profiles, stories, skills,
  achievements;
- every file in storage — illustrations and narration;
- the account itself, including the email address.

After that the data cannot be restored — neither by you nor by us.
Infrastructure backups are overwritten on the provider's cycle (up to 7 days),
after which nothing remains there either.

7.3. Specific retention periods for the rest:
- anti-abuse logs (request timestamps) — up to 24 hours;
- generation logs (time, plan, success/error) — up to 12 months, after which
  they are anonymized and survive only as aggregate statistics;
- purchase data — while the subscription is active and thereafter for the period
  required by Google Play rules and tax law.

7.4. If you simply stop using the App and do not sign in for more than 24
months, we may delete the account and its data after warning you by email first.

## 8. Your rights
8.1. You have the right to: access your data and obtain a copy of it, correct
inaccurate data, delete it, restrict or object to processing, receive your data
in a machine-readable form (portability), and withdraw consent previously given.
Withdrawal does not affect the lawfulness of processing before it.
8.2. Contact: **aistoryteller.team@gmail.com**. We reply within **30 days** at
the latest. There is no charge for this.
8.3. If you believe your rights have been infringed, you may lodge a complaint
with a supervisory authority:
- in the Republic of Moldova — the National Center for Personal Data Protection
  (Centrul Naţional pentru Protecţia Datelor cu Caracter Personal),
  [datepersonale.md](https://datepersonale.md);
- in the European Union — the data protection authority of your country of
  residence.

8.4. We make **no automated decisions** producing legal or similarly significant
effects for you, and we do not carry out profiling. The automation in the App
only writes stories and counts plan limits.

## 9. Security
9.1. We apply reasonable measures: channel encryption (HTTPS), access separated
by database rules, private file storage with temporary links, secrets stored
only on the server, and request rate limiting. No security is absolute, but we
strive to minimize risks.
9.2. **Data breach.** If a security breach occurs that could create a risk to
your rights, we will notify the supervisory authority within 72 hours of
becoming aware of it and, where the risk is high, tell you directly what
happened and what to do.

## 10. Changes to this policy
We will announce changes in the App and update the effective date.

## 11. Contacts
Privacy questions: aistoryteller.team@gmail.com.
