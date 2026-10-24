# Cookieren CMP: Google Tag Manager template

Google Tag Manager tag template for [Cookieren](https://cookieren.oloren.hu/), the cookie consent platform by Oloren.

What the tag does:

1. Sets the Google Consent Mode v2 defaults: `ad_storage`, `ad_user_data`, `ad_personalization`, `analytics_storage`, `functionality_storage` and `personalization_storage` are denied until the visitor decides (optionally only in the regions you list).
2. Restores a returning visitor's saved choice before any other tag fires.
3. Loads the Cookieren banner. Design, texts, services and regional rules are set in the Cookieren admin.

## Setup

1. Create a website in the Cookieren admin and copy its Site ID from the Install tab.
2. In Google Tag Manager add the **Cookieren CMP** template from the Community Template Gallery.
3. Create a tag from it, paste the Site ID, and fire it on **Consent Initialization - All Pages**.
4. Publish the container.

## Support

info@oloren.hu · [cookieren.oloren.hu](https://cookieren.oloren.hu/)

## License

Apache License 2.0, see [LICENSE](LICENSE).
