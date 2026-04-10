---
layout: default
title: Privacy Policy
---

# Smooth Talker — Privacy Policy

**Last updated: April 10, 2026**

Smooth Talker is an iOS keyboard app that rewrites your draft messages to help you communicate more effectively across cultural and generational contexts. This policy explains what data we collect, how we use it, and your choices.

---

## The short version

- We **only process your text when you tap the "Smooth" button**. We never read your messages in the background.
- We do **not** log keystrokes, track what you type, or access messages you don't explicitly send to us.
- Your message text is sent to our server, processed by an AI model, and the rewrites are returned to you. We store the original text and rewrites so you can view your history. We do **not** use your messages to train AI models.
- We use anonymous accounts by default — no email, no name, no phone number required.
- You can delete your data at any time by signing out (Settings → Sign Out), which removes your account and all associated data.

---

## 1. What data we collect

### Data you provide directly

| Data | When | Why |
|---|---|---|
| **Draft message text** | When you tap the "Smooth" button | Sent to our server to generate rewrite variants. Stored with your rewrites for history. |
| **Context text** (optional) | When you tap "+ context" and paste from your clipboard | Sent alongside your draft to improve rewrite quality. Stored with the rewrite. |
| **Cultural profile** | During onboarding (heritage culture, generation, language, communication style, tone preference) | Used to tailor rewrites to your cultural context. Stored on your device and optionally on our server. |
| **Email and password** (optional) | Only if you choose to create a named account | Used for authentication. Stored securely via Supabase Auth. |

### Data collected automatically

| Data | Why |
|---|---|
| **Anonymous user ID** | Created on first launch via Supabase anonymous authentication. Used to enforce daily rewrite limits and store your history. No personally identifiable information is attached. |
| **Rewrite history** | Which variant you selected, when, and the original text. Used to show your "Recent Rewrites" in the app. |
| **Usage count** | Number of rewrites per day. Used to enforce the free tier limit (5 rewrites/day). |

### Data we do NOT collect

- **Keystrokes**: We do not log what you type on the keyboard. The keyboard extension only reads the text field content when you tap "Smooth."
- **Messages from other people**: We do not read or store messages from your contacts. If you paste context via the clipboard, that is your choice and is treated the same as your draft text.
- **Contacts, photos, location, or device identifiers**: We do not access your address book, camera roll, GPS, or advertising identifiers.
- **Browsing history or app usage**: We do not track which apps you use or which websites you visit.

---

## 2. How we use your data

| Purpose | Legal basis |
|---|---|
| Generate rewrite variants when you tap "Smooth" | Necessary to provide the service you requested |
| Store your rewrite history | Necessary to provide the history feature |
| Enforce daily rewrite limits | Necessary to operate the free tier |
| Improve rewrite quality via cultural profile | Based on the profile you provided during onboarding |
| Authenticate your account | Necessary to provide the service |

We do **not** use your data for advertising, profiling, or selling to third parties.

---

## 3. Third-party services

We use the following third-party services to operate Smooth Talker:

| Service | Purpose | Data shared | Location |
|---|---|---|---|
| **Anthropic (Claude)** | AI model that generates rewrite variants | Your draft text and context text (per-request, not stored by Anthropic beyond the API call) | United States |
| **Supabase** | Database, authentication, and user management | Anonymous user ID, cultural profile, rewrite history, usage counts | United States (AWS Oregon) |
| **Render** | Hosts our backend API server | API requests pass through Render's infrastructure | United States (Oregon) |

Anthropic's data usage policy states that API inputs are **not used to train their models**. See [Anthropic's API data policy](https://www.anthropic.com/policies/privacy) for details.

---

## 4. Data retention

| Data | Retention |
|---|---|
| Anonymous account + profile | Kept until you sign out or until we clean up inactive anonymous accounts (after 14 days of inactivity) |
| Rewrite history | Kept as long as your account exists |
| Named account (email/password) | Kept until you request deletion |

When you sign out, your authentication tokens are cleared from the device. If you created an anonymous account, the server-side data associated with that anonymous user ID will be deleted during our periodic cleanup.

---

## 5. Your rights

Regardless of where you live, you can:

- **Access your data**: View your rewrite history in the app.
- **Delete your data**: Sign out (Settings → Sign Out) to clear your local data and disassociate from your anonymous account.
- **Not use the service**: The keyboard works as a standard QWERTY keyboard even without tapping "Smooth." You can uninstall at any time.

If you are in the **European Economic Area (EEA)**, you additionally have the right to:
- Request a copy of your personal data
- Request correction of inaccurate data
- Request erasure ("right to be forgotten")
- Object to processing based on legitimate interests
- Lodge a complaint with your local data protection authority

If you are in **California**, you have rights under the CCPA including the right to know what data we collect, the right to delete, and the right to opt out of the sale of personal data. **We do not sell your personal data.**

To exercise any of these rights, contact us at the address below.

---

## 6. Keyboard extension and Full Access

Smooth Talker uses a Custom Keyboard Extension that requires **Full Access** to function. Full Access is needed because:

- The keyboard must make network requests to our server to generate rewrites.
- The keyboard must read the clipboard when you tap "+ context."

With Full Access enabled, iOS grants the keyboard extension the ability to access the network and the clipboard. We use these permissions **only** for the purposes described above. We do not use Full Access to:
- Log your keystrokes
- Read your messages in the background
- Access data from other apps
- Send data anywhere other than our server when you tap "Smooth"

You can revoke Full Access at any time in iOS Settings → General → Keyboard → Keyboards → Smooth Talker.

---

## 7. Children's privacy

Smooth Talker is not directed at children under 13. We do not knowingly collect personal information from children. If you believe a child has provided us with data, please contact us and we will delete it.

---

## 8. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top will reflect the most recent revision. If we make material changes, we will notify you through the app.

---

## 9. Contact us

If you have questions about this privacy policy or your data:

**Email**: [support@smooth-talker.app](mailto:support@smooth-talker.app)

---

*Smooth Talker is operated by Zihao Geng.*
