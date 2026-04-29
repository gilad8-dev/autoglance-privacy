# AutoGlance – Privacy Policy

*Last updated: April 26, 2025*

## Overview

AutoGlance is a Chrome browser extension that provides AI-powered assistance by analyzing the content of the web pages you are viewing. This policy explains what data AutoGlance accesses, how it is used, and what is never collected.

---

## Data We Do NOT Collect

AutoGlance does not collect, transmit, store, or share any personal data. Specifically:

- We do not operate any backend server or database.
- We do not receive, log, or retain your API keys, browsing history, or page content.
- We do not use analytics, tracking pixels, or third-party telemetry services.
- We do not sell or share any information with third parties.

---

## API Keys

AutoGlance requires you to provide your own API key for an AI provider (such as Anthropic, OpenAI, or Google Gemini). Your API key is stored exclusively in Chrome's local storage on your own device using the `chrome.storage.local` API. It never leaves your device except to be sent directly to the AI provider's API endpoint when you make a request.

---

## Page Content and Screenshots

When you ask AutoGlance a question, the extension may capture the visible content or a screenshot of the current tab to provide context to the AI model. This data is sent directly from your browser to the AI provider you have configured (e.g., `api.anthropic.com`, `api.openai.com`, or `generativelanguage.googleapis.com`).

AutoGlance never sees, intercepts, or stores this data. All communication is between your browser and the AI provider. Please review the privacy policy of your chosen AI provider for information on how they handle your data.

---

## Permissions Explained

| Permission | Reason |
|---|---|
| `activeTab` / `<all_urls>` | Read the content of the page you are viewing so AutoGlance can answer questions about it |
| `storage` | Save your settings and API key locally on your device only |
| `scripting` | Extract page content and capture screenshots for AI context |
| `sidePanel` | Open the AutoGlance chat interface in Chrome's side panel |

---

## Children's Privacy

AutoGlance is not directed at children under the age of 13 and does not knowingly collect any information from children.

---

## Changes to This Policy

If this privacy policy is updated, the revised version will be published at this URL with an updated date. Continued use of the extension after changes are posted constitutes acceptance of the revised policy.

---

## Contact

**Gilad Shaked**
gilad8@post.bgu.ac.il
