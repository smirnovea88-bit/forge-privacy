# Forge — Privacy Policy

**Version:** 1.0  
**Effective date:** 8 October 2026  
**Contact:** foreg.app.support26@gmail.com  
**Other languages:** [Русская версия](ru.html)

Forge ("Forge", "we", "us") is an Android app for logging strength workouts. This policy explains what
data Forge handles, why, who receives it, how long it is kept, and what choices you have.

## 1. Summary

- Your workouts, history, exercises, templates and settings stay **on your device**. We do not receive them.
- An account is **optional**. You need one only for the AI analysis feature (and, in the future, a paid plan).
- The AI analysis is **optional** and works only after you sign in and give a separate consent. When you
  run it, summary figures of your workouts are sent to our server and on to the AI provider, Anthropic.
  Your name, email and user ID are not sent to Anthropic.
- We **do not sell** your data, we **do not show ads**, and we **do not use analytics or tracking SDKs**.
- You can delete your account in the app at any time.

## 2. Data that stays on your device

Forge works offline. The following is stored only in the app's private storage on your device:

- workouts, sets, exercises (including exercises you create), templates, history and progress figures;
- your weight-unit setting and interface language;
- saved AI analyses (up to the 100 most recent; older ones are deleted automatically).

We do not have access to this data. It is removed when you uninstall the app or clear its data.

**Android backup and transfer.** Forge's database is excluded from Android cloud backup (Google Drive).
When you move to a new phone with Android's direct device-to-device transfer (Android 12 and later),
the data may be copied to the new device. Your sign-in session is never backed up or transferred.
You can also create an export file in the app; where it is saved and who can read it is up to you.

## 3. Account (optional)

If you choose to sign in, you use **Sign in with Google**. We receive from Google:

- your email address and an internal account identifier;
- basic profile details that Google includes in the sign-in result (for example, your name and a link to your
  profile picture). Forge does not display your name or picture.

We use this to create and secure your account, to recognise you on later sign-ins and to apply AI usage
limits. Your sign-in session is kept on your device and is excluded from backup.

## 4. AI analysis (optional)

The AI analysis needs an account, an internet connection and your **separate consent** (shown in the app
before the first request). You can withdraw consent at any time on the AI screen.

**What is sent when you request an analysis**

- summary figures for the period you choose (4, 8 or 12 weeks): number of workouts, frequency, total volume,
  volume by muscle-group category, top exercises by volume, personal records and progress signals;
- exercise names, including exercises you have named yourself;
- for the detailed analysis only: individual sets from the last 4 weeks (weight, repetitions and whether a set
  is a warm-up), together with the week of the period and the day of the week.

**What is not sent:** your name, your email address, your user ID, exact timestamps of sets, or any data
outside the chosen period. Please do not put personal information into names of custom exercises: those names
are sent as part of the analysis.

**How the request travels.** Your app sends the request to our server (a function hosted at Supabase). The
server checks your sign-in and consent and forwards the request to **Anthropic** (the Claude model), which
generates the analysis. The result comes back through our server to your app.

**What we store about it.** We do **not** store the content of your requests or of the answers on our server.
We store only technical metadata about each request, linked to your account, in order to apply usage limits and
keep the service working: the time of the request, its type (short or detailed), the model name, token
counts, and the result status or error code. We also store your consent record: the consent version and text
you accepted, the time you accepted it and, if applicable, the time you withdrew it. The analysis itself
is saved only on your device.

**Anthropic.** Anthropic processes the data it receives under its own terms and privacy policy
(<https://www.anthropic.com/legal/privacy>). We do not control how Anthropic handles data on its side.
AI analyses are informational and are not medical advice.

## 5. Who receives data

| Recipient | Role | Data |
|---|---|---|
| Google | Sign-in provider | Sign-in with your Google account (governed by Google's own privacy policy) |
| Supabase | Hosting provider of our account database and server functions (our processor) | Account data, consent record, request metadata, and the content of AI requests while they pass through the server function |
| Anthropic | AI provider | The AI request data described in section 4 |

We do not sell personal data, we do not share it for advertising, and we do not use it for profiling.
We may disclose data if required by law.

## 6. International processing

Our server infrastructure is hosted in Singapore, and Anthropic may process data in the United States and
other countries. Where the law requires safeguards for such transfers (for example for users in the European
Economic Area or the United Kingdom), we rely on the safeguards offered by our providers, such as standard
contractual clauses.

## 7. Legal bases (GDPR and similar laws)

| Purpose | Legal basis |
|---|---|
| Creating and operating your account | Performance of the service you request (Art. 6(1)(b)) |
| Sending your data to the AI provider for an analysis | Your consent (Art. 6(1)(a)), which you can withdraw at any time |
| Recording your consent, applying usage limits, preventing abuse and keeping the service secure | Our legitimate interests (Art. 6(1)(f)) and, for the consent record, our legal obligation to demonstrate consent |

Withdrawing consent does not affect the lawfulness of processing carried out before the withdrawal.

## 8. How long we keep data

| Data | Where | Retention |
|---|---|---|
| Workouts, history, exercises, templates, settings | Your device | Until you delete them or uninstall the app |
| Saved AI analyses | Your device | The 100 most recent; older ones are deleted automatically; you can delete any analysis yourself |
| Account data (email, identifier, profile details from Google) | Our server | Until you delete your account |
| Consent record | Our server | Until you delete your account. Withdrawing consent marks the record as withdrawn (with the time); it does not delete the record |
| AI request metadata (time, type, model, token counts, status) | Our server | Until you delete your account |
| Content of AI requests and answers | Not stored by us | Not applicable (Anthropic's own retention is governed by its terms) |

## 9. Your rights and choices

Depending on where you live, you may have the right to access, correct, delete, restrict or object to the
processing of your personal data, to receive it in a portable form, to withdraw consent, and to lodge a complaint
with a data-protection authority. In practice:

- **Your workout data** is on your device. You can view, edit, delete and export it in the app.
- **Withdraw AI consent:** AI screen → "Revoke consent". New AI requests stop immediately; analyses saved on your
  device and the usage counters on the server remain until you delete them or your account.
- **Delete your account:** Settings → Account → "Delete account". Your account record, consent record and AI
  request metadata are deleted from our server immediately. Data on your device is not affected.
- **Delete your account without the app, or ask about the data we hold:** write to
  foreg.app.support26@gmail.com from the email address of the Google account. We will verify that the request
  comes from the account owner and respond within 30 days.
- **Delete a saved analysis:** AI screen → analysis history.

## 10. Security

Data sent between the app and our server is encrypted in transit (HTTPS/TLS). Access to account data is
restricted by access-control rules so that an account can reach only its own records, and the keys that give
full access to our database are kept on the server and never in the app. No method of transmission or storage
is completely secure, and we cannot guarantee absolute security.

## 11. Children

Forge is not directed to children. Do not use the account and AI features if you are under 13 (or under 16 in
the European Economic Area or where local law sets a higher age). If you believe a child has provided us
personal data, contact us and we will delete it.

## 12. Changes to this policy

We may update this policy. The version and effective date at the top show the latest revision. If a change
affects what you consented to for the AI analysis (for example, a different provider or different data), the
app asks for your consent again before the next AI request.

## 13. Contact

foreg.app.support26@gmail.com
