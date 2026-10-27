# StayLit

Public app and privacy pages for StayLit by SinSoft Studios. Uses the same static HTML layout and `docs/` structure as Another Tabata App.

## GitHub Pages

After committing and pushing to `main`, choose **Settings > Pages > Deploy from a branch**, branch **main**, folder **/docs**. No build is required.

Expected addresses once GitHub Pages is enabled:

- Home: https://sinsoft-studios.github.io/StayLit/
- Privacy policy: https://sinsoft-studios.github.io/StayLit/privacypolicy/staylit.html

Use the privacy-policy address in the app and store listing. Links are relative, and `docs/.nojekyll` disables Jekyll processing.

## Maintenance

The privacy policy anticipates Google AdMob banner ads and distinguishes future ad-supported versions from the current app, which has no advertising SDK. Consent and Privacy choices controls described there still need to be implemented before ads are enabled.

Before an advertising release, configure AdMob consent messages and regional choices, add the SDK and required privacy controls, and update the store's ads and Data safety declarations to match the shipped configuration. Verify the policy against the selected SDK and providers. Reference: [Google's Flutter consent guide](https://developers.google.com/admob/flutter/privacy).

Keep the policy aligned with the released app's permissions, local storage, and data practices. Update the policy date when those practices change. Do not add sensitive information to this public repository.
