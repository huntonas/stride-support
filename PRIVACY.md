# Privacy Policy for Stride

**Effective date:** August 11, 2026

Stride ("the App") is a running recovery app for people returning to running after an injury or surgery. This policy explains what data the App collects, how it's used, and your choices.

## Local-First by Design

Stride stores your data — interval programs, workout history, and daily symptom journal entries (pain scores, symptoms, notes) — directly on your device. We do not operate an account system, and we do not have a server database of your personal health information.

## What We Send to Our Servers

Once a week (or when you request it), Stride sends a summary of your recent training load and symptom journal data to our backend so it can generate an AI-powered recommendation (Progress / Repeat / Pull Back). This request:

- Does not include your name, email address, or any account identifier — there is no account to identify you by.
- Is forwarded to Anthropic's Claude API solely to generate your recommendation, and is not used to train AI models.
- Is not stored in a database on our servers. Your IP address is briefly retained in memory (not on disk) to enforce a daily rate limit, and is discarded automatically after 24 hours.

## Terms Acceptance Records

To confirm that users have agreed to the App's Terms of Use and medical disclaimer, Stride records your acceptance on our servers when you accept them — on first launch, and again if the terms are ever updated. This is the one piece of information Stride keeps in a server-side database. Each record contains only:

- A randomly generated, anonymous device identifier. It is created on your device, is not linked to your name, email, Apple ID, or any account (there is no account), and identifies a single app installation. Reinstalling the App generates a new identifier.
- The version of the terms you accepted, the App version, and your device platform (e.g., iOS).
- The date and time you accepted.

These records contain no health data and no other personal information. They are kept solely as proof that the terms were accepted, and are never used for advertising, analytics, or AI training.

## In-App Purchases

Stride uses RevenueCat to manage optional subscription purchases (e.g., unlocking the AI-Personalized Plan). RevenueCat and Apple's App Store process purchase and device information necessary to validate your subscription, per their own privacy policies:

- RevenueCat: https://www.revenuecat.com/privacy
- Apple: https://www.apple.com/legal/privacy/

We do not receive your payment information directly.

## Analytics and Advertising

Stride does not currently include any third-party analytics, advertising, or crash-reporting SDKs.

## Your Choices

Because your health data lives on your device, you control it directly — deleting an entry in the app deletes it, and uninstalling the App removes all locally stored data. There is no server-side copy to separately delete.

## Children's Privacy

Stride is not directed at children under 13, and we do not knowingly collect data from children under 13.

## Changes to This Policy

If this policy changes, we'll update the effective date above and post the revised version at this same URL.

## Contact

Questions about this policy or your data? Open an issue at https://github.com/huntonas/stride-support/issues.
