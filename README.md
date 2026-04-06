# rollapaya-support

Public support assets for the Rollapaya iOS app.

## Published Site

Set your production support URL here after deployment:

- `https://<your-github-username>.github.io/rollapaya-support/`

## Repository Contents

- `index.html`: Support landing page with support contact and policy links.
- `privacy.html`: Privacy Policy covering app data handling and AdMob disclosures.
- `terms.html`: End User License Agreement (EULA) and Terms of Use.
- `app-ads.txt`: Authorized seller declaration for Google AdMob.
- `LICENSE.md`: Proprietary license and use restrictions for repository contents.

## Version Compatibility

The support site keeps stable public URLs while documenting two app behavior ranges:

- `Versions 1.1.1 and below`: legacy guidance preserved from the original launch documentation.
- `Versions 1.2 and above`: current guidance for the App Store version of the app, which may use production AdMob to request and display real ads under the non-tracking and no-ATT model.

Current disclosure direction:

- Keep `privacy.html` version-aware while preserving the current non-tracking and no-ATT disclosure model unless the app's product decision changes.
- Keep `terms.html` version-aware where third-party advertising behavior differs, but avoid splitting legal files unless the rights or obligations materially diverge.
- Keep `index.html` as the stable support landing page and route version-sensitive details into the policy pages.

Recommended information architecture:

- Keep `privacy.html` as a single stable privacy page with clearly labeled sections for each supported version range.
- Keep `terms.html` as a single stable EULA/terms page, with version-specific language only where third-party advertising behavior differs.
- Keep `index.html` as the stable support overview and add a short version-compatibility notice that points users to the policy pages for details.

Separate versioned filenames are not currently necessary. The legal and support content appears close enough to maintain in single stable pages as long as version-specific disclosures remain clearly labeled. If a future release introduces materially different legal rights, tracking behavior, consent flows, or ATT usage, separate versioned legal pages may become safer.
