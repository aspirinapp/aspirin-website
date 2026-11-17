# aspirin.app website

Source of the [aspirin.app](https://aspirin.app) website, in English, German, Spanish, French and Ukrainian.

aspirin.app is an AI helper for safe medicine use at home: it spots duplicate ingredients, tracks expiry dates and explains leaflets in plain words, in your language. The product is in development. This website explains the product, the AI and safety approach, plans for partners, pricing, the funding summary and the founding programme.

## Technology

- One static page: HTML, CSS and plain JavaScript in a single `index.html`. No framework and no build step.
- All five languages live inside `index.html`. The language switcher (EN, DE, ES, FR, UA) changes the text in the browser.
- Light and dark themes.
- No cookies, no analytics and no tracking. The chosen language and colour theme are saved only in the visitor's browser (local storage).
- Forms do not send data to any server. They open the visitor's own email app with a ready message to info@aspirin.app.
- Fonts (Geologica, Ysabeau Office, Martian Mono) are loaded from Google Fonts.

## Structure

```
index.html                      the whole website, all five languages
img/                            photos used on the page (illustrative, not real customers)
aspirin-app-summary-en.pdf      project summary, English
aspirin-app-summary-de.pdf      project summary, German
aspirin-app-summary-es.pdf      project summary, Spanish
aspirin-app-summary-fr.pdf      project summary, French
aspirin-app-summary-uk.pdf      project summary, Ukrainian
```

## View locally

```bash
git clone https://github.com/aspirinapp/aspirin-website.git
cd aspirin-website
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Licence

All rights reserved. See [LICENSE](LICENSE). The fonts are third-party and licensed under the SIL Open Font License 1.1. Aspirin® is a registered trademark of Bayer AG; aspirin.app is independent and not affiliated with Bayer AG.

## Contact

Typos, broken links or translation fixes: open an issue. Anything else: [info@aspirin.app](mailto:info@aspirin.app).
