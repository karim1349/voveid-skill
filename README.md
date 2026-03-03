# VoveID Claude Skill

A comprehensive Claude Skill for integrating the VoveID identity verification API and SDKs.

This skill equips Claude (via Claude Code or the desktop app) with deep knowledge of VoveID's platform, enabling it to write integration code, debug webhooks, configure SDKs, and build Know Your Business (KYB) flows.

## Features

This skill includes documentation for:
* **APIs**: Authorization, session creation, results fetching, webhook validation.
* **SDKs**: Web, React Native, Flutter, iOS, and Android.
* **KYB (Know Your Business)**: Overviews, case creation, management, and webhooks.
* **Coverage**: Identity document coverage details (MEA region, etc.).
* **Customization**: UI/UX tweaking for SDKs.

## Installation

You can install this skill directly by passing the URL to the `.skill` file. 

Anyone can install the skill using:

```bash
claude skill install https://raw.githubusercontent.com/karim1349/voveid-skill/main/voveid.skill
```

Alternatively, you can install it locally if you have the file:
```bash
claude skill install /path/to/voveid.skill
```

## How to use

Once installed, just mention "VoveID" or related concepts in your Claude prompt. The skill is optimized to trigger when you ask about:
* "How do I integrate VoveID in React Native?"
* "Create a VoveID verification session via API."
* "How do I start a KYB case?"
* "Validate a Vove webhook signature."

No need to link docs manually—Claude will instantly read the internal skill references and give you accurate, up-to-date code.

## Contributing
To update the skill:
1. Extract the `.skill` file (it is a zip archive).
2. Edit the underlying `SKILL.md` or markdown files.
3. Re-package it using the Skill Creator.
