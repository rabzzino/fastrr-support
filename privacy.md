---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy for Fastrr

**Effective date:** 2026-06-06
**Last updated:** 2026-10-29

Fastrr ("we", "us", "the app") is an intermittent fasting tracker developed by Rabbi Ahmed ("developer"). This policy explains what data we collect, why, and how it is handled. If you do not agree with this policy, please do not use the app.

Contact: rabbiahmed958@gmail.com

## 1. Data we collect

### 1.1 Account information (only if you sign in)
- Email address
- Optional display name (the name you enter, or the name Apple shares the first time you sign in with Apple). It is synced with your account.
- Apple ID identifier (only if you sign in with Apple)

We use Supabase to authenticate you and store your synced data. Your password (if applicable) is hashed by Supabase and never stored in plain text.

We use Resend to email you the 6-digit codes that confirm your email address, reset your password or change your email. Resend receives only your email address and the email it delivers (the code). It receives none of your fasting or health data.

### 1.2 Fasting and health data you enter
- Start and end times of your fasting sessions
- Body weight logs (typed, or imported from Apple Health: see 1.3), hydration logs, the times you log a meal
- The badges you earn
- Fasting protocol (16:8, 18:6, etc.)
- Personal profile data you provide during onboarding (height, weight, age, gender, activity level, goals, and a goal weight and date if you set one), and your other onboarding answers, such as when you wake and go to sleep, your first meal, your fasting experience and what gets in your way
- A gentle-mode setting: yes or no. It is on if you told us during onboarding that you are pregnant or breastfeeding, have had an eating disorder, take insulin or other diabetes medication, or have another medical condition or take regular medication, or if you are under 18. It makes the app suggest gentler fasts and not set a weight goal. We keep only the yes or no, never which reason you chose.

This data is stored locally on your device (SQLite) and optionally synced to Supabase if you sign in, so it can appear on other devices you sign in on.

The note and the "How was it?" answer you can add to a fast stay on your device. They are not synced to your account.

### 1.3 Apple Health (HealthKit) data
If you grant permission, the app reads the following from Apple Health:
- Steps and walking or running distance
- Active energy burned and exercise minutes
- Heart rate (including resting heart rate)
- Sleep analysis
- Workouts
- Water intake
- Weight (body mass)

**Activity, heart rate, sleep, workout and water readings from HealthKit are used only on-device to power your fasting insights.** They are never sent to our servers, analytics providers, or any third party, are not linked to your account, and are not marketed against or sold.

**Weight is the exception.** Weigh-ins you bring in from Apple Health become weigh-ins in Fastrr: they are stored on your device and, like the weights you type, synced to your Fastrr account if you sign in, so your weight trend appears on every device you sign in on. A weigh-in you typed always wins over one from Health for the same day. They are never sent to analytics providers or any third party, are not used for advertising, and are not sold. This complies with Apple's HealthKit privacy requirements.

If you allow it, the app writes the water intake you log in Fastrr to Apple Health, and a weigh-in when you switch on "Save to Apple Health" for it. It does not write any other data to Apple Health.

### 1.4 Subscription data
If you subscribe, RevenueCat processes your subscription on our behalf. RevenueCat receives:
- An app-user identifier: an anonymous one while you use Fastrr without an account, or, once you sign in, your Fastrr account's user ID (a random identifier, not your name or email) so your subscription follows your account to your other devices
- Subscription status (active, expired, trial, cancelled)
- Which product you purchased
- A device identifier Apple gives each app developer (the identifier for vendor, not the advertising identifier), which RevenueCat's software sends with each request
- If RevenueCat's own subscription screen is shown (it appears only if the app can't load its own), when it was viewed and closed

We do not receive your Apple ID email or payment details — those stay between you and Apple.

### 1.5 Analytics data (PostHog)
We use PostHog to understand, in aggregate, how the app is used. PostHog receives anonymous app-usage events (e.g., "fast started", "fast ended", "paywall viewed"), with details such as:
- A fast's length, its goal and plan, and whether you added a note (never the note itself or your "How was it?" answer)
- The amount of water you log, and your daily water goal
- On the paywall, the plan you chose, its price and whether it began with a free trial
- Which onboarding steps you saw, the plan you picked and how soon you planned your first fast (never your body measurements, age, health or safety answers)
- General device and app info (OS version, device model, language, time zone, app version and the kind of build)
- A random identifier for this installation, so one phone's events can be grouped. It is replaced when you sign out and is never linked to your account
- The IP address each request comes from, as with any internet service
- Whether HealthKit data is available (yes or no only, never the values)

The app turns off PostHog's location lookup, so its events carry no location. We do not send PostHog any HealthKit readings, weight logs, your body measurements, age or health answers, your name or email, or your account's user ID.

### 1.6 Crash and error reports (Sentry)
We use Sentry to detect and fix crashes and errors. Sentry receives:
- Stack traces from crashes and unhandled errors
- Reports of errors the app handled (for example, a sign-in or sync request that failed), with an error code and the name of the feature or data type involved
- Anonymous device info (OS version, model)
- Basic context (which screen was open, and the app's recent steps before the error)
- Performance timings (such as how long the app took to start) for a sample of app sessions

Before a report leaves your device, the app removes email addresses, sign-in tokens, keys and account IDs from it. Reports are not linked to your account: they carry a random identifier for this installation and a device code made for this app, never your user ID or email. We do not send Sentry any HealthKit values, personal health data, weight logs, or your personal profile.

## 2. What we do NOT do

- We do NOT sell your data.
- We do NOT share HealthKit data with anyone.
- We do NOT use your data for advertising or marketing to third parties.
- We do NOT use your data for research or fed to any AI/machine-learning training set outside the app itself.
- We do NOT profile you for advertising purposes.

## 3. Data location and retention

Local data: stored on your device until you delete it (via "Delete Account" in the app), sign out (signing out removes Fastrr's data from that device), or uninstall.

Synced data (Supabase): stored in Supabase's London region (eu-west-2, United Kingdom). Retained as long as your account exists. When you delete your account, your account and every synced record are deleted at once. Supabase's daily backups may hold a copy for up to 7 days after that, until they expire.

Sign-in security log (Supabase): Supabase's sign-in service keeps a log of account events, such as sign-ins and the deletion of an account. Each entry can include your email address and the IP address used. These entries are kept for security purposes for 90 days, including after your account is deleted, and then deleted.

Email delivery (Resend): Resend keeps a record of the emails it delivered (your address, the time and whether it arrived) per Resend's retention policy.

RevenueCat data: retained per RevenueCat's policy while you have an active subscription. When you delete your account, we delete your RevenueCat customer record. Apple keeps its own record of your purchases.

PostHog analytics: aggregate event data retained per PostHog's retention policy.

Sentry crash data: retained per Sentry's default retention policy (typically 90 days).

## 4. Your rights (GDPR, CCPA, and others)

You have the right to:
- **Access:** Settings → Data → Export my data makes a CSV file of the fasts, weigh-ins and water on your phone, at any time and with or without an account. For everything your account holds, email us from your account's email address and we send you a file.
- **Delete:** in the app, go to Profile → Settings (gear icon) → Account details → Delete Account, and confirm with your password, or with Apple if you use Sign in with Apple. This immediately and permanently deletes:
  - your Fastrr account and every synced record;
  - your RevenueCat customer record;
  - Fastrr's access through Sign in with Apple, when you confirm with Apple. If Apple can't complete this, the app shows you how to stop using Sign in with Apple for Fastrr in your Apple ID settings;
  - all Fastrr data on that device.

  Backups and the sign-in security log follow the periods in section 3. Deleting your account does not cancel a subscription: cancel it in your Apple ID settings (Settings → your name → Subscriptions). If you can't use the app (for example, you lost your phone), email us from your account's email address and we will delete the account for you; in that case, stop using Sign in with Apple for Fastrr yourself in your Apple ID settings, as we can't do it without your device.
- **Analytics:** PostHog events are anonymous and never linked to your account or email. Contact us if you have questions about analytics data.
- **Contact us:** rabbiahmed958@gmail.com for any privacy questions.

## 5. Children

Fastrr is not intended for use by children under 13 (or under 16 in the EU). We do not knowingly collect data from anyone in these age groups. If you believe we have, contact us and we will delete it.

## 6. Health disclaimer

Fastrr is a wellness tracking tool. It is not a medical device and does not provide medical advice. Fasting is not appropriate for everyone — including pregnant or nursing women, people with a history of eating disorders, and people on diabetes medication. Consult a qualified health professional before beginning any fasting regimen.

## 7. Changes to this policy

If we change this policy in a material way, we will notify you in the app and update the effective date at the top. Continued use of the app after changes constitutes acceptance.

## 8. Third parties referenced

- **Supabase** (authentication + sync): https://supabase.com/privacy
- **Resend** (sign-in code emails): https://resend.com/legal/privacy-policy
- **RevenueCat** (subscriptions): https://www.revenuecat.com/privacy
- **PostHog** (analytics): https://posthog.com/privacy
- **Sentry** (crash reporting): https://sentry.io/privacy
- **Apple HealthKit** (health data on-device): https://support.apple.com/en-us/HT204351

---

Contact for privacy inquiries: **rabbiahmed958@gmail.com**
