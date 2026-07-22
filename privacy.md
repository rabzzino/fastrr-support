---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy for Fastrr

**Effective date:** 2026-06-06

Fastrr ("we", "us", "the app") is an intermittent fasting tracker developed by Rabbi Ahmed ("developer"). This policy explains what data we collect, why, and how it is handled. If you do not agree with this policy, please do not use the app.

Contact: rabbiahmed958@gmail.com

## 1. Data we collect

### 1.1 Account information (only if you sign in)
- Email address
- Optional display name
- Apple ID identifier (only if you sign in with Apple)

We use Supabase to authenticate you and store your synced data. Your password (if applicable) is hashed by Supabase and never stored in plain text.

### 1.2 Fasting and health data you enter
- Start and end times of your fasting sessions
- Body weight logs, hydration logs, meal notes
- Fasting protocol (16:8, 18:6, etc.)
- Personal profile data you provide during onboarding (height, age, activity level, goals)

This data is stored locally on your device (SQLite) and optionally synced to Supabase if you sign in, so it can appear on other devices you sign in on.

### 1.3 Apple Health (HealthKit) data
If you grant permission, the app reads the following from Apple Health:
- Steps
- Active energy burned
- Heart rate (including resting heart rate)
- Body weight
- Sleep analysis
- Workouts

**HealthKit data is used only on-device to power your fasting insights.** It is never sent to our servers, analytics providers, or any third party. It is not linked to your account, marketed against, or sold. This complies with Apple's HealthKit privacy requirements.

The app may write the following to Apple Health if you allow:
- Water intake logs
- Fasting sessions as mindful minutes

### 1.4 Subscription data
If you subscribe, RevenueCat processes your subscription on our behalf. RevenueCat receives:
- An anonymous app-user identifier
- Subscription status (active, expired, trial, cancelled)
- Which product you purchased

We do not receive your Apple ID email or payment details — those stay between you and Apple.

### 1.5 Analytics data (PostHog)
We use PostHog to understand feature usage in aggregate. PostHog receives:
- Anonymous app-usage events (e.g., "fast started", "paywall viewed", "achievement unlocked")
- General device info (OS version, device model)
- Whether HealthKit data is available (boolean only — NOT the values)

We do not send PostHog any HealthKit data values, weight logs, personal profile data, or account information.

### 1.6 Crash and error reports (Sentry)
We use Sentry to detect and fix crashes. Sentry receives:
- Stack traces from crashes and unhandled errors
- Anonymous device info (OS version, model)
- Basic context (which screen was open when the crash happened)

We do not send Sentry any HealthKit values, personal health data, weight logs, or your personal profile.

## 2. What we do NOT do

- We do NOT sell your data.
- We do NOT share HealthKit data with anyone.
- We do NOT use your data for advertising or marketing to third parties.
- We do NOT use your data for research or fed to any AI/machine-learning training set outside the app itself.
- We do NOT profile you for advertising purposes.

## 3. Data location and retention

Local data: stored on your device until you delete it (via "Delete Account" in the app) or uninstall.

Synced data (Supabase): stored in Supabase's infrastructure (US region). Retained as long as your account exists. Deleted permanently within 30 days of you invoking "Delete Account".

RevenueCat data: retained per RevenueCat's policy while you have an active subscription; anonymized on account deletion.

PostHog analytics: aggregate event data retained per PostHog's retention policy.

Sentry crash data: retained per Sentry's default retention policy (typically 90 days).

## 4. Your rights (GDPR, CCPA, and others)

You have the right to:
- **Access:** email us to request a copy of your data.
- **Delete:** use "Delete Account" in the app's Profile screen. This permanently deletes your Supabase account, all synced data, and all local data. Deletion happens immediately in the app and is reflected across our systems within 30 days.
- **Export:** the app includes a Data Export feature (PDF and CSV) covering your fasting history.
- **Opt out of analytics:** disable PostHog by turning off "Share usage data" in Settings (if enabled).
- **Contact us:** rabbiahmed958@gmail.com for any privacy questions.

## 5. Children

Fastrr is not intended for use by children under 13 (or under 16 in the EU). We do not knowingly collect data from anyone in these age groups. If you believe we have, contact us and we will delete it.

## 6. Health disclaimer

Fastrr is a wellness tracking tool. It is not a medical device and does not provide medical advice. Fasting is not appropriate for everyone — including pregnant or nursing women, people with a history of eating disorders, and people on diabetes medication. Consult a qualified health professional before beginning any fasting regimen.

## 7. Changes to this policy

If we change this policy in a material way, we will notify you in the app and update the effective date at the top. Continued use of the app after changes constitutes acceptance.

## 8. Third parties referenced

- **Supabase** (authentication + sync): https://supabase.com/privacy
- **RevenueCat** (subscriptions): https://www.revenuecat.com/privacy
- **PostHog** (analytics): https://posthog.com/privacy
- **Sentry** (crash reporting): https://sentry.io/privacy
- **Apple HealthKit** (health data on-device): https://support.apple.com/en-us/HT204351

---

Contact for privacy inquiries: **rabbiahmed958@gmail.com**
