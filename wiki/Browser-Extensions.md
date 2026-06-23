# Browser Extensions

Oldoodle includes extension source for Chromium-based browsers and Firefox.

## Chromium

Folder:

```text
extensions/chromium/
```

Package outputs:

- `oldoogle-xp-chromium-extension.zip`
- `oldoogle-xp-chromium-extension.crx`

The Chromium extension:

- Overrides the new tab page.
- Adds an Oldoodle toolbox popup.
- Can call the hosted Oldoodle search API.

## Firefox

Folder:

```text
extensions/firefox/
```

Package output:

- `oldoogle-xp-firefox-extension.xpi`

The Firefox extension:

- Overrides the new tab page.
- Adds a toolbar/sidebar toolbox.
- Includes homepage override support.

## Toolbox Widgets

The extension popup includes:

- Search: query Oldoodle directly.
- Timer: quick countdowns.
- QR maker: generate a QR code from a URL or text.
- Notes: save a tiny scratch note.
- Speed: ping the search engine.
