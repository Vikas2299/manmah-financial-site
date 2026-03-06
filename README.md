# Manmah Financial (Static Site)

Simple multi-page static website (HTML + CSS) ready for Netlify.

## Pages

- `index.html` — Home
- `about.html` — About
- `services.html` — Services
- `who-we-serve.html` — Who We Serve
- `resources.html` — Resources
- `contact.html` — Contact

## Local preview

### Option A: open the file

Open `index.html` in your browser.

### Option B: run a local server (recommended)

From the `manmah-financial` folder:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy to Netlify

### Quick deploy (no Git)

1. Zip the `manmah-financial` folder
2. Drag-and-drop it into Netlify Drop

### Git-based deploy (recommended)

1. Create a repo and push this folder
2. In Netlify: **Add new site → Import an existing project**
3. Build command: *(leave empty)*
4. Publish directory: *(repo root)*

## Update the profile photo

Current image used on Home + About:

- `assets/images/IMG-20260306-WA0001.jpg`

To replace it, overwrite that file with a new image (same filename), or update the `<img src="...">` paths in:

- `index.html`
- `about.html`

