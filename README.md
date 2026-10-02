# NW Tracker — privacy notice (published copy)

This repository exists for one reason: **Google Play requires a publicly
reachable privacy policy URL**, and the app's in-app notice (screen 7.7) cannot
be opened in a browser.

## ⚠️ `index.html` is GENERATED — do not edit it here

It is built from `src/lib/privacy-policy.ts` in the app's own (private)
repository, which is the single source for three surfaces: the in-app screen,
the published markdown, and this page. Editing this copy would make the hosted
notice disagree with the one users accept inside the app — and a published
privacy notice contradicting the in-app one is worse than either alone.

To change the text, edit the TypeScript module in the app repository, run
`npm run build:docs`, then `npm run publish:privacy`.

## What this page serves

- The privacy notice, in full
- A **Deleting your account and data** section at `#delete`, giving the in-app
  route plus a contact address for anyone who cannot sign in — this is what
  satisfies Play's Data safety data-deletion URL requirement
