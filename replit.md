# Project setup

This project is a static Portuguese landing page for a Christian t-shirt design
bundle. The uploaded build is kept in its original structure:

- `index.html` is the page shell.
- `css/` contains the bundled stylesheet.
- `js/` contains the bundled application and Meta Pixel script.
- `images/` contains the favicon.

## Run on Replit

The configured **Start application** workflow serves the project with Python's
built-in HTTP server on port `5000`:

```bash
python3 -m http.server 5000 --bind 0.0.0.0
```

No package installation or build step is required.