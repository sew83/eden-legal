# Eden legal pages

This folder is ready to publish as a public GitHub Pages site.

## Suggested repository structure

```text
eden-legal/
├── README.md
├── privacy-policy.md
├── terms-of-use.md
└── index.md
```

Before publishing, review the text for the countries where Eden will be distributed.

## GitHub Pages

1. Create a public repository, for example `eden-legal`.
2. Copy these files to its root.
3. In **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Use the generated HTTPS address in App Store Connect and inside Eden.

Recommended URLs:

- `https://TODO.github.io/eden-legal/privacy-policy.html`
- `https://TODO.github.io/eden-legal/terms-of-use.html`

If GitHub Pages does not render Markdown with the desired URL, add equivalent `.html` pages or use a simple Jekyll theme. The URL must be public, stable and accessible without logging in.

## Before release

- Confirm the owner details and effective date.
- Add the final effective date.
- Confirm the App Privacy answers match the released binary.
- Add the privacy-policy URL in App Store Connect.
- Link the policy from the app settings.
- Review the document with a qualified legal adviser if distributing commercially.
