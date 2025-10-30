---
title: Privacy Policy
permalink: /privacy-policy
layout: none
---

Privacy Policy
Effective date: [Month DD, YYYY]
This Privacy Policy explains how [Company Name] (“we”, “us”, “our”) collects, uses, and shares information when you use the FOODMap scanner mobile application (“App”).
By using the App, you agree to this Policy.
What we do in the App
Scan barcodes to fetch public product data from Open Food Facts.
Capture optional photos of food or labels to analyze potential FODMAP risk using an AI service.
Let users sign in with Apple or Google (via Clerk) to access the main app.
Offer in‑app subscriptions (via RevenueCat).
Run lightweight product analytics (via PostHog, EU host if configured).
Run an onboarding flow stored locally on your device.
Data we collect
Account data
From your chosen sign‑in provider (Apple or Google) via Clerk: unique ID, email, name (if provided by the provider).
Subscription data
Purchase status, active entitlements, receipts metadata via RevenueCat (not payment card numbers; those are handled by Apple/Google).
Usage and device data
Events such as “AppLaunched” or onboarding variant assignment via PostHog; device metadata (OS, app version). We do not log raw onboarding answers in analytics—only coarse summaries.
Scan data
Barcode values used to fetch public product info from Open Food Facts.
Photos you choose to capture for analysis (food plate or label) are converted to base64 and sent to our AI provider for processing.
Onboarding responses
Stored locally on your device using SecureStore; not uploaded to our servers.
We do not knowingly collect sensitive health data. While the App provides FODMAP‑related information, we do not store medical records or diagnoses.
How we use data
Provide core features (scan products, analyze images, show results).
Authenticate you and secure your session.
Verify and manage subscriptions.
Improve reliability and UX through aggregate analytics.
Prevent abuse and troubleshoot issues.
Where data is processed and shared
We use service providers (“processors”) to operate the App:
Authentication: Clerk (stores account and session data to sign you in).
Backend execution: Convex (runs server actions; we don’t persist your images there).
In‑app purchases: RevenueCat (links your subscription to your account).
AI analysis: OpenAI API (receives product text inputs or images you choose to analyze; returns a structured result).
Analytics: PostHog (captures product analytics; EU endpoint when configured).
Product info: Open Food Facts (public database queried by barcode).
These providers process data on our behalf to deliver the service. Data may be transferred and stored outside your country. Where required, we rely on appropriate safeguards (e.g., standard contractual clauses).
AI note: Images and text you submit for analysis are sent to OpenAI solely to generate the analysis result. According to the provider’s standard API terms, content may be retained for a limited time for abuse detection but is not used to train the provider’s models (subject to the provider’s then‑current policy).
What we do not do
We do not sell your personal information.
We do not show third‑party ads.
We do not store your analysis photos on our servers; they are transmitted to the AI provider for processing and not kept by us.
Retention
Account and subscription data: kept while your account is active and as necessary to meet legal obligations.
Onboarding answers: stored locally on your device until you reset onboarding or delete the app.
Analytics events: retained per our analytics provider’s standard retention window.
AI inputs (text/images): not retained by us; the AI provider may keep short‑term logs for abuse prevention.
Your choices and rights
Camera and photos: you can deny camera permission; some features will not work.
Account deletion: In the App, go to Settings → Delete Account. This removes your Clerk account and logs you out. Some records may remain where required by law or in provider logs kept for limited periods.
Manage subscription: iOS Settings → Apple ID → Subscriptions or in‑app “Manage Subscription” link.
Email us to exercise privacy rights (access, correction, deletion) as applicable in your region: [privacy@yourdomain.com].
Security
We use industry‑standard technical and organizational measures (HTTPS, scoped tokens). No system is 100% secure; please use a strong device passcode and keep your OS up to date.
Children
The App is not directed to children under 13 (or the age required by your jurisdiction). Do not use the App if you are under the applicable age.
Third‑party links
The App may link to third‑party sites (e.g., Apple/Google subscription pages). Their privacy practices are governed by their own policies.
Changes to this Policy
We may update this Policy. We will post the revised Policy with a new “Effective date”. Continued use of the App after changes means you accept them.
Contact
[Company Name]
[Address, City, Country]
Email: [privacy@yourdomain.com]
Terms of Use
If you do not maintain your own Terms yet, our iOS app relies on Apple’s Standard EULA as the license for end users: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
—