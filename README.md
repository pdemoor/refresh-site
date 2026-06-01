# Refresh.app Static Website

This is a dependency-free static website for Refresh.app.

## Deploy to Vercel

1. Create a new GitHub repository.
2. Upload these files to the repository root:
   - `index.html`
   - `styles.css`
   - `vercel.json`
3. In Vercel, import the GitHub repository.
4. Use the default settings. No build command is required.
5. Point the Refresh.app domain to the Vercel project.

## Notes

- The logo and images are using the current Refresh.app media URLs.
- The video section is edge to edge and uses a native muted `<video>` tag for reliable iPhone/Safari autoplay.
- Add the video file at `assets/refresh-video.mp4` before deploying. YouTube iframe autoplay is intentionally not used because mobile Safari does not reliably allow it.
- The footer uses inline linked social icons for Instagram, LinkedIn, YouTube, and X.
- The contact form currently opens an email draft to `hello@refresh.app`. Change that address in `index.html` if another contact address should be used.
