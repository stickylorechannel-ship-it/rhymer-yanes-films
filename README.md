# Rhymer Yanes Films — Free Website

A responsive, cinematic, Netflix-inspired website for showcasing AI drama films hosted on YouTube.

## Files
- `index.html` — website layout, styling, search, video player, sharing
- `videos.js` — the list of films you publish
- `.nojekyll` — tells GitHub Pages to serve the static site directly

## Add a film
Open `videos.js` and add a film object inside `window.RY_FILMS = [ ... ];`.
Remove the `/*` and `*/` comment markers around the examples, then replace the sample fields.

Example:
```js
window.RY_FILMS = [
  {
    id: "the-last-promise",
    title: "The Last Promise",
    description: "A daughter discovers a secret that changes her family forever.",
    youtube: "https://www.youtube.com/watch?v=YOUR_VIDEO_ID",
    genre: "Family Drama",
    monogram: "LP"
  }
];
```

Rules:
- `id` must be unique; use lowercase letters, numbers, and hyphens.
- `title` is the film title.
- `description` should be a short teaser.
- `youtube` can be a standard YouTube video URL, a youtu.be link, or a YouTube Shorts URL.
- Use videos you own or have permission to embed. If a video has embedding disabled, viewers may need to watch it on YouTube.
- Do not paste private information into the public repository.

## Publish free with GitHub Pages
1. Download and unzip `rhymer-yanes-films.zip`.
2. Sign in or create an account at https://github.com.
3. Create a **new public repository** named `rhymer-yanes-films` (GitHub Free requires a public repository for Pages in this setup).
4. Open the new repository and choose **Add file → Upload files**.
5. Upload `index.html`, `videos.js`, and `.nojekyll` from the unzipped folder. Upload the files themselves, not the containing folder.
6. Scroll down and select **Commit changes**.
7. Open the repository's **Settings → Pages**.
8. Under **Build and deployment**, select **Deploy from a branch**.
9. Choose branch `main` and folder `/(root)`, then click **Save**.
10. Wait a few minutes. In Settings → Pages, click **Visit site**. Your address will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/rhymer-yanes-films/`

## Update films later
1. Open the `videos.js` file in your GitHub repository.
2. Tap the pencil/edit icon.
3. Add or update film details, then **Commit changes**.
4. Wait for GitHub Pages to publish the update.

## Share on Facebook or Messenger
- Share the homepage URL to show the full collection.
- Use each film's **Share link** button to copy/share a direct link to that film.
- The website can be opened on phones and computers.

## Important notes
- Hosting the website on GitHub Pages is free for eligible public repositories, but the website is public.
- YouTube hosts the video playback; this website does not upload or store video files.
- A preview thumbnail for Facebook/Messenger may not appear immediately or consistently for every shared URL. The site's page-level preview metadata is configured, but dynamic per-film social previews typically need server-side or per-page metadata.
- A custom domain name is optional and usually costs money; the default GitHub Pages address is free.
