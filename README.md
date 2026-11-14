# Wingflight Landing Page

The source of [wingflight.org](https://wingflight.org), the home page of
[Wingflight](https://github.com/WingFlight/wingflight-firmware), the open-source flight controller
firmware for fixed-wing aircraft.

The page is one static file, `index.html`, with its styles and scripts inline. Logos are in
`logos/`. There is no build step.

## Preview

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

## Deployment

Pushing to `master` publishes the folder to the `gh-pages` branch through
`.github/workflows/deploy-gh-pages.yml`.

## Related

- [Documentation](https://doc.wingflight.org) ([source](https://github.com/WingFlight/wingflight-docs))
