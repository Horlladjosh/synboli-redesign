# Synboli redesign

Independent website redesign proposal based on Synboli’s public website.

## Deploy through GitHub to Vercel

1. Import this repository into Vercel.
2. Use the **Other** framework preset and the repository root.
3. The included `vercel.json` selects `dist` as the output directory. No build command or environment variables are required.
4. Deploy and open the generated URL on desktop and mobile.

## Files

- `dist/`: ready-to-deploy HTML, CSS, JavaScript and local image assets.
- `build.py`: regenerates the HTML pages with `python3 build.py`.
- `application_content.py`: application-specific content.
- `CONTENT_SOURCES.md`: content provenance and redesign constraints.

Images are illustrative stock photographs. Credits are listed on the website’s credits page.
