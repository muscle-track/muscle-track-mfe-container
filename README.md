[![Netlify Status](https://api.netlify.com/api/v1/badges/39f4a3d2-46a1-4843-b45e-0fa650a693f7/deploy-status)](https://app.netlify.com/sites/muscle-track/deploys)

# muscle-track-mfe-container

Micro frontend container

## Run in Development

```bash
yarn start:dev
```

## Notes

- favicon.ico is a fontawesome icon generated with https://gauger.io/fonticon

## How was this app started?

```bash
npm install --global create-single-spa
npx create-single-spa
.
single-spa root config
yarn
y (typescript)
n (beta layouts)
michaelpmcmillan
```

## Enable dev mode

Run this from firefox/chrome console and refresh the page:

```
localStorage.setItem("devtools", true);
```

It will show a list of all loaded modules underneath the app.
