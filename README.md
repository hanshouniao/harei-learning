# harei-learning

A simple GitHub Pages website for sharing learning-related URLs and information.

## Website URL

After deployment, the website should be available at:

https://hanshouniao.github.io/harei-learning/

## How to deploy on GitHub

1. Create a new repository on GitHub named `harei-learning`.
2. Upload all files from this folder into the repository.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. Wait a minute or two for GitHub Pages to publish the site.

## How to edit links

Open `index.html` and find this pattern:

```html
<a class="link-card" href="https://example.com" target="_blank" rel="noopener noreferrer">
  <span class="link-title">Example Resource</span>
  <span class="link-description">Replace this URL and description with your own content.</span>
</a>
```

Change:
- `href="https://example.com"` to the real URL
- `Example Resource` to the link title
- the description text to whatever you want

Then commit the file on GitHub.
