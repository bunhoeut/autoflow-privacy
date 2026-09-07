---
meta-viewport: width=device-width, initial-scale=1.0
title: AutoFlow — Privacy Policy
---

A

AutoFlow

Powered by Google Flow

# Privacy Policy

Last updated: September 2026

AutoFlow ("the Extension") is a Chrome browser extension developed by Phin Bunhoeut that automates batch image and video generation on Google Flow ([flow.google.com](https://flow.google.com), formerly labs.google/fx/tools/flow). This Privacy Policy explains what data the Extension collects, how it is used, how it is stored, and how it is shared.

## 1. Data Collection

AutoFlow collects and processes the following limited data solely to provide its core functionality:

- **User settings** — model selection, aspect ratio preference, automation delay settings, prompt history, and license activation status. This data is entered by the user and stored locally in the browser.
- **License key** — if you purchase AutoFlow PRO, your license key is collected at the time of activation to verify your subscription status with Gumroad's API.
- **Google Flow session** — AutoFlow reads your existing Google Flow browser session (via cookies) to submit generation requests on your behalf. The session data is used only to communicate with Google Flow and is never stored by AutoFlow.

AutoFlow does **not** collect your name, email address, IP address, location, browsing history, passwords, payment details, or any personally identifiable information beyond what is described above.

## 2. Data Use

The data described above is used exclusively for the following purposes:

- **User settings** — to restore your preferred configuration each time you open AutoFlow, so you do not need to reconfigure it.
- **License key** — to verify whether you have an active AutoFlow PRO subscription, by sending the key to Gumroad's license verification API (`api.gumroad.com`). This is the only outbound request AutoFlow makes to a non-Google server.
- **Google Flow session** — to authenticate and submit your prompts to Google Flow, trigger generation, monitor task progress, and retrieve completed results — exactly as you would do manually.

AutoFlow does not use any collected data for advertising, analytics, profiling, or any purpose unrelated to its single core function of automating Google Flow generation tasks.

## 3. Data Storage

All user settings and license status are stored using Chrome's local `storage` API, which keeps data on your device only. This data:

- Never leaves your browser except as described in the Data Use section above.
- Is not transmitted to any server operated by AutoFlow's developer.
- Remains on your device until you uninstall the Extension or manually clear your browser's extension storage.
- Is not backed up or synchronized to any cloud service by AutoFlow.

## 4. Data Sharing

AutoFlow shares data with the following third parties only, and only as necessary to operate:

| Third Party                                                        | Data Shared                                                 | Purpose                                                                  |
| ------------------------------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------------------------------------- |
| Google (flow.google.com, labs.google, aisandbox-pa.googleapis.com) | Your prompts, generation settings, and session credentials  | To submit image/video generation requests to Google Flow on your behalf |
| Gumroad (api.gumroad.com)                                          | Your PRO license key                                         | To verify whether your subscription is active at activation time        |

AutoFlow does **not** sell, rent, trade, or share your data with any other third parties, including advertisers, data brokers, or analytics providers.

## 5. Chrome Permissions Explanation

AutoFlow requests the following Chrome permissions, each necessary for its single purpose:

| Permission             | Why It Is Needed                                                                                                     |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| `storage`               | To save your settings and license status locally on your device.                                                     |
| `activeTab`             | To detect when you are on a Google Flow page so automation can run safely.                                           |
| `tabs`                  | To monitor the active Google Flow tab and refresh it during batch automation.                                        |
| `cookies`               | To read your existing Google Flow session so AutoFlow can submit requests as you, without a separate login.          |
| `scripting`             | To interact with the Google Flow page — filling the prompt box, clicking Generate, and reading results directly from the page's own interface. |
| `downloads`             | To save generated images and videos to your computer when auto-download is enabled.                                  |
| `sidePanel`             | To display AutoFlow's control panel alongside the Google Flow page.                                                  |
| Host: flow.google.com   | Google Flow's current domain — required to read and interact with the Flow page as part of the automation workflow. |
| Host: labs.google       | Google Flow's previous domain, retained for backward compatibility with existing projects still hosted there.       |

## 6. Children's Privacy

AutoFlow is not directed at children under the age of 13. We do not knowingly collect any data from children. If you believe a child has provided data through this Extension, please contact us so we can remove it.

## 7. Changes to This Policy

If this Privacy Policy changes, the updated version will be posted at this same URL ([bunhoeut.github.io/autoflow-privacy](https://bunhoeut.github.io/autoflow-privacy)) with a revised "Last updated" date. Continued use of the Extension after changes are posted constitutes acceptance of the updated policy.

## 8. Contact

If you have any questions about this Privacy Policy or how AutoFlow handles your data, please contact:

**Developer:** Phin Bunhoeut  
**Email:** <bunhoeut@gmail.com>  
**Telegram:** [@Bunhoeut](https://t.me/Bunhoeut)

AutoFlow — Made in Cambodia 🇰🇭 | [bunhoeut.gumroad.com](https://bunhoeut.gumroad.com)
