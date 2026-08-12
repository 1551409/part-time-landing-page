# Part-Time Landing Page

Standalone static landing page for a remote part-time job campaign.

Update the WhatsApp number in `index.html`.
Use digits only, including the country code, without `+`, spaces, or hyphens:

```js
const WHATSAPP_NUMBER = "";
```

Example: `573001234567`.

If you need to use a non-WhatsApp link, leave `WHATSAPP_NUMBER` empty and update:

```js
const CONTACT_LINK = "";
```

Update the Meta/Facebook Pixel ID in `index.html`:

```js
const META_PIXEL_ID = "";
```

Language preview links:

- English: `/?lang=en`
- Latin American Spanish: `/?lang=es`
- Argentina Spanish: `/?lang=es-ar`

Without a `lang` parameter, the page uses the browser's primary language:

- `es-AR` -> Argentina Spanish
- other `es-*` languages -> Latin American Spanish
- all other languages -> English
