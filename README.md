# Personal Assistant — App Information

Static information site for the personal Hermes Agent configuration operated by **0xvaneural**. No build tools, dependencies, login forms, analytics, or credentials.

## Review before publishing

- This is a draft website, not a guarantee that Google will approve branding, publishing, or verification.
- Review Privacy Policy and Terms against the real configuration before uploading. In particular, check AI providers, retention, Google data handling, and Limited Use compliance. A written policy does not change provider settings or establish actual compliance.
- The app name is written as **Hermes Agent** to match the setup discussed. If Google Cloud shows a different app name, update the website to match.
- The public contact channel is GitHub Issues in `0xvaneural/personal-assistant-info`. Keep Issues enabled when creating the repository. Never post private data there.
- Only these five website/documentation files should be uploaded. Do not add OAuth JSON files, API keys, tokens, screenshots of login callbacks, personal expenses, or server configuration.

## Files

- `index.html` — homepage
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `styles.css` — shared responsive styling
- `README.md` — upload and configuration guide

## Upload through your phone

1. Download and extract `personal-assistant-info.zip` using your phone's file manager. **GitHub does not automatically extract an uploaded ZIP. Upload the extracted files, not the ZIP.**
2. Sign in at https://github.com using your own browser. Never send your password or token to Ted.
3. Open https://github.com/new . Choose owner `0xvaneural`, repository name **personal-assistant-info**, visibility **Public**, and enable **Add a README file**. Create the repository. This publishes the repository; only do this after approving the content.
4. In the repository's **Code** tab, choose **Add file → Upload files**. If that menu is hidden on mobile, enable **Desktop site** in your browser. Select the extracted `index.html`, `privacy.html`, `terms.html`, and `styles.css` together.
5. Use commit message `Add app information website`, select the option to commit directly to `main`, then press **Commit changes**. You may separately replace the generated README with this guide, but it is not required for the site to work.
6. Confirm `index.html` and `styles.css` appear directly beside README at the repository root, **not inside another folder**.

## Enable GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Source → Deploy from a branch**.
3. Select **main** and **/(root)**, then **Save**.
4. Wait for GitHub to publish the site; refresh Pages until it reports the live URL. The expected address, **not verified until publishing**, is:

   https://0xvaneural.github.io/personal-assistant-info/

5. Open the homepage, Privacy, and Terms on your phone. Ensure every page loads and the design is styled. If deployment fails, send the nonsecret error message to Ted. Do not invent or use another site's address.

## Google Cloud — only after the website is live

Expected URLs if the repository name is exactly as above:

- Homepage: `https://0xvaneural.github.io/personal-assistant-info/`
- Privacy Policy: `https://0xvaneural.github.io/personal-assistant-info/privacy.html`
- Terms of Service: `https://0xvaneural.github.io/personal-assistant-info/terms.html`

Do **not** assume that GitHub Pages publishing alone completes Google's domain-ownership requirements. After the live pages are checked, Ted will guide Google Search Console ownership verification and the Authorized domains setting based on the actual Google UI. Do not add `github.io`, `github.com`, `google.com`, or a temporary tunnel domain merely to bypass validation.

If Google offers HTML-file or meta-tag ownership verification, request that exact verification method. The verification file or meta-tag can be added in a later commit. It is not an API key, but do not post unrelated account details or login codes.

Only after Branding is saved and Audience actually shows **In production**, restart Google authorization through a working, approved secure handoff. The old temporary HTTPS recovery page has a one-hour lifetime; ask Ted to check it rather than reusing an expired link.

## References

- Upload files: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- Configure Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Google API data policy: https://developers.google.com/terms/api-services-user-data-policy

## Preview locally (optional)

Open `index.html` in a browser. Relative links work without a server. No installation is needed.
