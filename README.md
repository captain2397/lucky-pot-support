# Lucky Pot — Support & Privacy

Public pages for the Lucky Pot iOS app, hosted with GitHub Pages. These URLs are
used for the App Store Connect **Support URL** and **Privacy Policy URL** fields.

| Page | File | URL |
| --- | --- | --- |
| Support | `index.html` | https://captain2397.github.io/lucky-pot-support/ |
| Privacy Policy | `privacy.html` | https://captain2397.github.io/lucky-pot-support/privacy.html |

## Keeping these accurate

The privacy page states that the app collects and transmits nothing: game
progress and reward state live only in on-device `UserDefaults`, and there is no
analytics, advertising, tracking or third-party SDK data collection. It names
bundle identifier `org.berkeleycommunityscholars.luckypot`.

If any SDK, network call or identifier is added to the app, update
`privacy.html` (short version, section 1's data table, sections 2 and 3),
`Lucky Pot/PrivacyInfo.xcprivacy` in the app repository, and the App Store
Connect App Privacy answers together so all three agree with the shipping
binary. Apple requires these to stay accurate, including third-party code
practices:
https://developer.apple.com/help/app-store-connect/manage-app-information/manage-app-privacy
