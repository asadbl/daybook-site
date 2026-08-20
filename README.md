# Daybook — website

Marketing page, privacy policy and support pages for Daybook, a field
documentation app for iPhone.

Published with GitHub Pages from the root of `main`:

- <https://asadbl.github.io/daybook-site/>
- <https://asadbl.github.io/daybook-site/privacy.html>
- <https://asadbl.github.io/daybook-site/support.html>

The privacy and support URLs are compiled into the app
(`Sources/Subscription/LegalLinks.swift`) and submitted to App Store Connect, so
they must stay reachable at these paths. `privacy/` and `support/` hold copies so
the extensionless forms work too.

Plain HTML with inline CSS — no Jekyll, no build step, no dependency on pretty
permalinks.

## Assets

`img/` holds the App Store screenshot set scaled for the web, and two pages of
the sample report. Regenerate the screenshots from the app repo with:

    ./run.sh appstore-shots

which writes the full-size 6.9" set (1320×2868) to `.build/appstore-screenshots`.
