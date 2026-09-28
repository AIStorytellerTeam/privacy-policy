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
**Effective date:** 2026-09-28

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
- **The adult's name — optional.** The field may be left blank or cleared
  later. The app then shows the chosen role instead ("Mom", "Dad" or your own
  wording). The role itself is required: it goes into the story, and relatives
  recognise each other by it.
- **Child profile (entered by the adult):** name, gender, chosen avatar,
  selected skills. The name is needed so the story is about that particular
  child — that is the whole point of the app. **Do not enter unnecessary
  personal data about children: surname, address, school or nursery.**

  We do **not** ask for or store a child's date of birth or age. A first name
  without a surname identifies almost no one; "name + exact date of birth"
  already does, and for a children's app that is a risk worth avoiding. The
  reading level is set differently: by default the text uses the simplest
  possible words, and if a story is wanted for an older child, the adult says
  so in the special wishes field.

  There is no family name either — people wrote their surname into it, and the
  app never needed it.
- **Created content:** story texts, illustrations, audio narration — stored so
  you can return to them.
- **Technical data:** generation logs (time, plan, success/error status, which
  service handled it) — for limits, abuse prevention, and aggregated analytics.
- **Device identifier: not collected.** We used to store a one-way hash of the
  identifier the operating system assigns to our app (ANDROID_ID on Android) so
  that an unlimited number of accounts could not be created on a single phone
  to bypass the free limits. We have dropped that too: Google Play rules for
  apps with a child audience prohibit transmitting such identifiers, and
  ANDROID_ID is named on that list explicitly. No device identifier — neither
  raw nor hashed — is transmitted or stored any more.
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
- binding the purchase receipt to a family, so one purchase cannot be used
  across several accounts;
- automatic suspension of generation after consecutive technical failures — so
  that neither your limits nor our resources are wasted.

The legal basis is our legitimate interest in protecting the service from abuse
(Art. 6(1)(f) GDPR for users in the EU).

## 3. Children's data
3.1. The App is operated on the child's behalf by an adult; the child's data is
entered by the adult, who can edit or delete it.
3.2. We do not ask children to provide personal data themselves and do not direct
advertising to children.
3.3. Provide only what is necessary about a child — a first name is enough for
the stories. We do not ask for age or date of birth at all (see section 2).
3.4. The App carries no advertising, no built-in chat, no comments and no other
way for a child to reach strangers.

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
Some of our providers (Supabase, Groq, Cloudflare, Google, ElevenLabs,
Yandex Cloud, Resend, Sentry) run servers in the European Union, the United
States, Russia and other countries. This means **cross-border data transfers**.

A separate warning about narration: cloud speech synthesis is performed by
**Yandex Cloud (Yandex SpeechKit)**, whose servers are located in Russia, and it
receives **the full text of the story** — which may contain the child's name if
the story is about them. Narration only starts when you ask for it: without
tapping the button nothing is sent, and you can read the story or listen to it
in the device's own voice without this transfer.

We keep what is transferred to a minimum, and we will say plainly what leaves:
**the child's name is sent to the AI service that writes the story** —
otherwise the hero could not carry that name, which is the whole point of the
app. Along with it go the adult's wishes text, the chosen genre and the titles
of the selected skills.

What never leaves: the email address, the password, account data, any device
identifier, purchase information. The child's name is sent without a surname,
without a date of birth and without contacts — we do not hold the latter two at
all. The request text alone cannot be tied back to a specific person.

If you would rather the child's name never left the device, turn off
"personal story" when creating one: the hero is then given an invented name and
we send nothing that relates to your child personally.

Transfers are made under contracts with those providers that include Standard
Contractual Clauses (SCC) or equivalent safeguards, as required by Chapter V of
the GDPR and Articles 32-33 of Law No. 133/2011 of the Republic of Moldova.

## 5. Third-party services (sub-processors)
To run the App we send the **request and scene text** to third-party AI
services. That text may contain the child's name — section 4.1 sets out
exactly what is sent and how to avoid it.
- **Text generation:** Groq — [policy](https://groq.com/privacy-policy/).
- **Illustration generation:** Cloudflare Workers AI —
  [policy](https://www.cloudflare.com/privacypolicy/).
- **Cloud narration (only when you ask for it):** Yandex Cloud, SpeechKit —
  [policy](https://yandex.cloud/en/docs/legal/confidential), servers in Russia.
  Receives the full story text, including the hero's name.
- **Parent-voice narration (only when you ask for it, if enabled):** ElevenLabs —
  [policy](https://elevenlabs.io/privacy-policy). Receives an adult's voice
  sample and the story text.
- **Infrastructure, authentication, storage:** Supabase —
  [policy](https://supabase.com/privacy).
- **Crash reporting:** Sentry — [policy](https://sentry.io/privacy/).
- **Support email:** Resend — [policy](https://resend.com/legal/privacy-policy).
- **Payments and distribution:** Google Play (Google) —
  [policy](https://policies.google.com/privacy).

Each service processes data under its own privacy policy and terms of use; the
links above lead to them. We do not pass these services direct identity
identifiers: they receive neither your email, nor account data, nor any device
identifier from us.

This list can change: if we add another provider or drop a current one, we will
update this section and the effective date at the top of the document.

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
8.2. **You can get a copy of your data inside the app, without contacting us:**
"Parents → Settings → My data". The export is produced on the device in two
formats — PDF to read through, and JSON, machine-readable, which you can take
to another service. It contains child profiles, every story with its full text,
selected skills, completion marks, awards, the family roster and plan details.

Deliberately excluded: the PIN hash, sign-in tokens and purchase tokens — these
are access keys rather than information about you, and handing them out would
be unsafe. Illustration and narration files are not bundled because of their
size; they remain available in the app itself.

8.3. For your other rights, contact **aistoryteller.team@gmail.com**. We reply
within **30 days** at the latest. There is no charge for this.
8.4. If you believe your rights have been infringed, you may lodge a complaint
with a supervisory authority:
- in the Republic of Moldova — the National Center for Personal Data Protection
  (Centrul Naţional pentru Protecţia Datelor cu Caracter Personal),
  [datepersonale.md](https://datepersonale.md);
- in the European Union — the data protection authority of your country of
  residence.

8.5. We make **no automated decisions** producing legal or similarly significant
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
