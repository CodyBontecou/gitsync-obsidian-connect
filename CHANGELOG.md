# Changelog

## 0.1.0 — 2026-10-14

- Connect Obsidian Git to an existing GitSync.md GitHub sign-in on iPhone and iPad.
- Transfer credentials through an encrypted, expiring handoff without putting tokens in URLs or tracked vault files.
- Fill missing Git author name/email so mobile pull and commit work after cloning.
- Preserve existing credentials unless the user explicitly reconnects.
- Renew expired connection requests without cloning again.

Requires a GitSync.md app build containing the companion handoff. Tested with Obsidian 1.14.5 and Git 2.41.1 on a physical iPhone; compatibility with newer Git credential APIs is covered by fixtures, not a device test. No background token refresh is included.
