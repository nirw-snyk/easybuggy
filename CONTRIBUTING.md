# Contributing to easybuggy

Thanks for your interest in contributing!

## Author recognition / contributor bios
If you'd like to be recognized in the project (a short bio, display name, or headshot), please follow these safe steps so we avoid exposing any private or host-local data:

1. Prepare your submission locally and sanitize it. Remove any secrets, host paths, or private information.
2. In this issue or a new issue titled `Author recognition: <your name>`, include:
   - Short bio (1–3 sentences)
   - Preferred display name
   - Optional links (website, GitHub, Twitter)
   - Optional headshot/image (attach directly to the issue)
   - A short note confirming the content contains no private or sensitive information
3. If your content is large, create a public Gist or attach a file to the issue. Do not ask maintainers or bots to read local host files (e.g., `/tmp/*`) — we will not and must not fetch those files.

## Why we don’t access local host files
Accessing files on a host or CI environment can leak secrets, credentials, or private data. For security and privacy reasons, maintainers will not retrieve or post the contents of arbitrary host files.

## Example issue body
Title: `Author recognition: Jane Doe`

Body:
- Bio: Jane Doe is a security engineer at ExampleCorp. She contributes docs and testcases.
- Display name: Jane D.
- Links: https://example.com
- Attachment: (attach headshot.jpg)
- Confirm: I confirm this submission contains no private or sensitive data.

Thank you for keeping contributions safe and respectful.
