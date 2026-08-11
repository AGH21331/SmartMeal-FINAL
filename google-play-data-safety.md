# Google Play Data Safety draft

This is a preparation document, not a declaration. Confirm each item in Play Console against the final backend and analytics configuration.

- Personal info: user profile fields are stored locally; do not declare collection unless synced to a server.
- Photos: images selected for AI scanning are transmitted to the configured AI backend for the requested analysis.
- Audio: raw audio is handled by Android speech recognition; the app stores recognized text only when the user submits it.
- Purchases: Google Play handles payment information.
- Security: HTTPS only; API keys remain server-side.
- Deletion: local data can be erased from Settings.

Before production, publish a public privacy-policy URL and ensure the Data Safety and Health Apps declarations match the actual release.
