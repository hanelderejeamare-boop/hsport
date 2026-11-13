# Photography Club Secretary Portfolio

A single-page portfolio for Hana Elderaja Amare (Grade 11C, School of Tomorrow), applying for Secretary of the Photography Club.

Built with plain HTML, CSS and JavaScript. Everything, including the photos, is embedded in one file.

## Files

| File | Purpose |
| --- | --- |
| `hsportifolio.html` | The whole website |
| `vercel.json` | Makes the site open at the main link instead of "page not found" |
| `README.md` | This file |

## Features

- Sign-in screen with a moving photo gallery on one half and the form on the other
- Sand theme by default, with a forest theme switch
- Gallery with search and categories
- Photo viewer that adapts to each photo: tall photos show the photo on the left and the description on the right, wide photos show the photo on top and the description below
- Double-tap any photo to see the full photo

## Run it locally

Open `hsportifolio.html` in any browser.

## Deploy (Vercel)

1. Put `hsportifolio.html`, `vercel.json` and `README.md` together in the root of your project (not inside a sub-folder).
2. Deploy the project. `vercel.json` sends every link to `hsportifolio.html`.

### If you still see "page not found"

- Make sure the files are in the project root, not inside another folder.
- Make sure the file name is exactly `hsportifolio.html`, in lowercase.
- Or rename `hsportifolio.html` to `index.html`. Hosts open that name automatically, and `vercel.json` is then not needed.
