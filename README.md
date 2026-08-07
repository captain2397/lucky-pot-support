# Lucky Pot — Support & Privacy

Public pages for the Lucky Pot iOS app, hosted with GitHub Pages. These URLs are
used for the App Store Connect **Support URL** and **Privacy Policy URL** fields.

| Page | File | URL |
| --- | --- | --- |
| Support | `index.html` | https://captain2397.github.io/lucky-pot-support/ |
| Privacy Policy | `privacy.html` | https://captain2397.github.io/lucky-pot-support/privacy.html |

## Keeping these accurate

The privacy page describes the SessionTracker SDK currently linked into the app:
a persistent Keychain UUID, app-usage events, and a remote web view served from
the vendor domain. If that SDK is removed or replaced before submission, update
section 2 of `privacy.html`, section 1's data table, and
`Lucky Pot/PrivacyInfo.xcprivacy` in the app repository together so all three
agree with the shipping binary.
