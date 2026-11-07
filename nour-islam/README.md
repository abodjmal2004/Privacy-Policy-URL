# Noor Al Islam privacy website

Privacy policy: https://abodjmal2004.github.io/Privacy-Policy-URL/nour-islam/

Account deletion: https://abodjmal2004.github.io/Privacy-Policy-URL/nour-islam/delete.html

## Components and request flow

- `index.html` is the Arabic privacy policy.
- `delete.html` explains account deletion and links to the developer's WhatsApp contact.
- GitHub Pages serves both files directly over HTTPS using this repository's existing Pages configuration.
- Reading the pages requires no login, authentication token, JavaScript application, or backend API.
- The deletion button opens WhatsApp. It does not directly authenticate the visitor or delete a Firebase account. The developer must verify account ownership and process the request manually as described on the page.

## Credentials and tokens

These HTML files contain no GitHub credentials, Firebase credentials, API keys, or access tokens. Publishing requires repository write access through GitHub's authenticated tools; visitors never receive those credentials. The Android app's authentication is separate from this static website.

## Updating

Edit the files in `nour-islam/` on `main`; the existing Pages workflow publishes the changes. Preserve relative navigation links so the site works under this subdirectory. Keep the root policy unchanged because it describes another service.
