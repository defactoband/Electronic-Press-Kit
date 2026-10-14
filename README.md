# Band EPK — GitHub Pages starter

This is a simple, responsive one-page EPK template. It costs nothing to host with GitHub Pages.

## 1. Personalise the page
- Open `index.html` in a text editor (TextEdit in plain-text mode, or preferably a code editor).
- Search for `YOUR BAND NAME`, `YOUR-EMAIL@example.com`, `ADD DETAILS`, and replace the placeholders.
- Replace the placeholder music/video boxes with the embed iframe code from your music/video host.
- Add your photos and adjust the photo section as described below.

## 2. Add image files
Upload image files into the same repository as `index.html`, for example `hero.jpg`, `photo-1.jpg`, `photo-2.jpg`, `photo-3.jpg`.
- In `index.html`, find the CSS comment that says “To use your own hero photo” and uncomment the `.hero { ... }` rule. Remove or leave the earlier `.hero` background rule; the later rule will override it.
- For each press photo, replace its placeholder `<span>` with an image, e.g. `<img src="photo-1.jpg" alt="Band portrait by Photographer Name">`.
- Keep images optimised for the web. A hero image around 2000px wide and press images around 1200–1800px wide are usually ample for web viewing.

## 3. Publish with GitHub Pages
1. Sign in or create an account at https://github.com/.
2. Create a new **public** repository. For the simplest personal site, name it `yourusername.github.io` (replace `yourusername` with your GitHub username).
3. Upload `index.html` and any image/download files into the repository root.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**; choose branch `main` and folder `/(root)`, then Save.
6. Wait a minute or two and visit `https://yourusername.github.io/`.

If using a repository with a different name, the URL is usually `https://yourusername.github.io/repository-name/`.

## 4. Add audio and video
- YouTube: open the video → Share → Embed → copy the `<iframe ...></iframe>` snippet. Replace the video placeholder `<div class="embed"...>` with that iframe. Add `class="embed"` to the iframe if needed, and keep `title="..."` on the iframe for accessibility.
- SoundCloud: open the track → Share → Embed → copy the iframe snippet. Replace the music placeholder with it. If the embed has a fixed width, change it to `width="100%"`; retain the provider's height.
- Spotify: use Share → Embed. You can add the iframe similarly; the visitor may need Spotify access for some content.
- Direct MP3: possible, but the audio file must be hosted somewhere publicly accessible. GitHub Pages is not designed for large media files, so prefer an established music host for audio and video.

## 5. Add downloads
If you use the links to `press-photos.zip` and `band-biography.txt`, upload files with exactly those names into the repository root. Otherwise, change or remove the links.

## Important notes
- GitHub Pages publishes the repository contents publicly. Do not upload private contact details or anything you don't want public.
- Free GitHub Pages sites are public-facing and have usage limits. Avoid uploading large audio/video files; embed them from a media host.
- The template is a starting point. Check all links, embeds, downloads and mobile layout before sending the URL to promoters.
