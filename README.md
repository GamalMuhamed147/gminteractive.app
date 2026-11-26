# gminteractive.app

The website of GM Interactive, served by GitHub Pages at https://gminteractive.app

- `/` GM Interactive home
- `/stamped/` Stamped app page
- `/stamped/privacy/` Stamped privacy policy (keep in sync with `privacy_screen.dart` in the app)
- `/stamped/support/` Stamped support + FAQ
- `/stamped/data/` data files + news the app downloads (`index.json` lists a version per file, `YYYY-MM-DD`; bump it when a file changes, and the same in `kBundledDataVersions` in the app)

Plain HTML + one `style.css`, no build step. `CNAME` holds the custom domain.
