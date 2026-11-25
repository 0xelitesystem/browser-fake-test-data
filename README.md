# Browser Fake Test Data

Generate fake test data in your browser. No server, no tracking, no third-party scripts.

**Live demo:** https://0xelitesystem.github.io/browser-fake-test-data/

## Use

Open `index.html` in any modern browser, or visit the GitHub Pages link in the repo description.

1. Check the fields you want: name, email, phone, address, city, country, date, uuid, boolean, number, or lorem sentence.
2. Set a row count (1 to 1000).
3. Click Generate.

You get four outputs at once:

- A table preview
- JSON array of objects
- CSV (RFC 4180 style quoting)
- SQL `INSERT` statements against a table name you set

Each export block has a Copy button.

## Why this exists

Seeding a database or a test fixture usually means either hand-typing junk rows or pulling in a data-faker library and a build step. This does it in one file with no dependencies, and the SQL and CSV come out ready to paste.

## Privacy

Everything runs in your browser. The generated data never leaves your machine. There are no network requests, no analytics, and no external scripts. Verify by viewing the page source or watching the network tab in DevTools.

## Run locally

```bash
git clone https://github.com/0xelitesystem/browser-fake-test-data
cd browser-fake-test-data
# Open index.html in your browser, or:
python -m http.server 8000
```

## Build

There is no build. It is a single HTML file.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT.

## Related

- [lorem-filler-text-browser](https://github.com/0xelitesystem/lorem-filler-text-browser)
- [htaccess-redirect-generator](https://github.com/0xelitesystem/htaccess-redirect-generator)
- [jwt-inspector](https://github.com/0xelitesystem/jwt-inspector)
