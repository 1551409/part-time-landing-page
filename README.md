# Part-Time Landing Page

Standalone static landing page for a remote part-time job campaign.

Update the contact jump link in `index.html`:

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
