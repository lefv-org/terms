# myAIPDF — Terms & Privacy

[myAIPDF](https://github.com/gwicho38/myaipdf) is a privacy-first on-device PDF
toolkit (compress, split, merge, extract, translate). All document processing
runs locally on the user's device; documents never leave the phone.

**Operating entity:** CCL Consulting LLC
**Support:** support@cclconsultingllc.com

## Canonical documents

- [Terms of Service](./terms-of-service.md)
- [Privacy Policy](./privacy-policy.md)

## Store-listing URLs

Use these URLs in App Store Connect (App Privacy) and Google Play Console
(Privacy policy URL, Terms of service URL):

- Terms: `https://github.com/lefv-org/terms/blob/main/myaipdf/terms-of-service.md`
- Privacy: `https://github.com/lefv-org/terms/blob/main/myaipdf/privacy-policy.md`

If GitHub Pages is enabled on this repo:

- Terms: `https://lefv-org.github.io/terms/myaipdf/terms-of-service.html`
- Privacy: `https://lefv-org.github.io/terms/myaipdf/privacy-policy.html`

## Sources of truth

This folder mirrors the in-app legal screens in the myAIPDF repo:

- `lib/main_pages/legal_pages/terms_of_service.dart`
- `lib/main_pages/legal_pages/privacy_policy.dart`
- `docs/privacy-policy.md`
- `docs/data-safety.md`

Keep all four in sync. If any drift, the in-app Dart text ships in the app
binary and is authoritative until this repo is updated to match.
