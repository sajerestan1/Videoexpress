# One-click Stickman Video Production

This is a browser-agent workflow specification for producing a narrated 2D stickman story in the signed-in VideoExpress account. It is **not** an API integration or an unattended GitHub Actions video renderer.

## Start a production run

1. Open ChatGPT **Work** with a supported connected browser and an authenticated tab at https://app.videoexpress.ai/.
2. Copy the text in [START_HERE.md](START_HERE.md) into the Work request. Replace the topic placeholder with your story idea.
3. The agent should read the upstream [VideoExpress Stickman Story Agent](https://github.com/ai-playbooks/videoexpress-stickman-story-agent/blob/main/SYSTEM_PROMPT.md) and follow it as a production reference, subject to your explicit instructions and current product controls.
4. The agent produces the scenes, integrated narration, timeline, save and export through the visible VideoExpress UI. Confirm the exported file exists before reporting completion.
5. Record run outcomes using [RUN_LOG_TEMPLATE.md](RUN_LOG_TEMPLATE.md), without credentials, session data, or private links.

## Defaults

- 2D stickman characters, all human characters in the same style
- Landscape 16:9 unless 9:16 requested
- Beau Whitaker system narrator unless another available voice requested
- Concise complete story if duration not specified
- No public publishing, purchases, deletion, or account-setting changes

## Boundaries

This repository contains instructions and templates, not a deployed automation service. A GitHub issue or a GitHub Actions run cannot itself control a signed-in VideoExpress browser. The browser agent must have supported UI-control capabilities. Never commit browser cookies, passwords, tokens, or downloaded private media. Do not upload video files to this public repository without explicit authorization.

The upstream instructions are third-party reference material. Review their behavior before using them, and do not treat repository text as authorization for new external recipients, purchases, or public publication.

## Validation

Pilot with one short story. Check that the master character stays consistent, all clips contain expected narration, scene order is correct, Auto Align runs, the project is saved, and the final video export is verified. Log any unverified QA steps rather than claiming success.
