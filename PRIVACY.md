# Privacy Policy for Amazon Supply Chain Analyzer

**Last updated:** 2026-07-12

## Data Collection

This Chrome extension collects the following data:

1. **Amazon product page content** — When you click "Generate Report" the extension extracts visible text from the current Amazon product page (review content, product details). This is done entirely client-side within your browser.

2. **AI API credentials** — You configure an API Key for DeepSeek, OpenAI, or other supported AI providers. This key is stored locally in your browser via `chrome.storage.local` and is never transmitted to any server other than the AI provider you explicitly configure.

## How Data Is Used

- **Page content** is sent to the AI API provider you configured (e.g., DeepSeek, OpenAI, SiliconFlow, etc.) solely for the purpose of generating an analysis report. No page content is sent to any other third party.
- **API credentials** are used exclusively to authenticate requests to your chosen AI provider.

## Data Storage

- All data is stored **locally** in your browser using `chrome.storage.local`.
- No data is stored on our servers. We operate no backend infrastructure.
- Data persists only as long as the extension is installed. Uninstalling the extension removes all stored data.

## Third-Party Data Sharing

- **Page content** is transmitted to the AI API provider you have configured in the extension settings. Each provider has its own privacy policy governing how they handle data sent to their APIs.
- **Minimal anonymous usage analytics** via Mixpanel is used solely for internal product improvement. We track:
  - `Extension_Installed` — fired once on first use
  - `Analysis_Completed` — fired when an analysis completes successfully
  - Properties sent are limited to: tier (free/pro), extension version, report language, and an anonymous random ID
  - **No review content, no API keys, no personal data** is ever sent to Mixpanel
- The extension communicates with the following third-party services:
  - The AI API provider you configure (e.g., DeepSeek, OpenAI)
  - GitHub Gist (for license key verification, anonymous SHA-256 hashes only)
  - Mixpanel (for anonymous usage analytics)
- We do not sell, rent, or share any user data with advertisers or other third parties.

## User Control

- You can **view, modify, or delete** your API credentials at any time via the extension's Settings page.
- You can **clear all stored data** by uninstalling the extension.
- The analysis process is **user-initiated** — no automatic or background data collection occurs.

## Changes to This Policy

If this policy is updated, the "Last updated" date at the top will reflect the change. Continued use of the extension constitutes acceptance of any changes.

## Contact

For questions about this privacy policy, please open an issue at:
https://github.com/cubeappm/amz-review-analyzer-privacy
