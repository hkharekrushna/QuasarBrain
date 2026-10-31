# QuasarBrain

A lightweight static landing page for QuasarBrain, focused on the worldwide
improvement of AI content.

## Publish with GitHub Pages

1. Add `index.html`, `styles.css`, and `CNAME` to the root of the
   `hkharekrushna/QuasarBrain` repository.
2. In the repository, open **Settings → Pages** and choose **Deploy from a
   branch**, then select `main` and the `/ (root)` folder.
3. In the GitHub Pages custom domain setting, enter `quasarbrain.com` and save.
4. In Porkbun's DNS settings for `quasarbrain.com`, add the DNS records GitHub
   Pages recommends for an apex domain, and add a `www` CNAME pointing to
   `hkharekrushna.github.io`.
5. After DNS has propagated, enable **Enforce HTTPS** in the Pages settings.

DNS changes can take time to propagate. Use the current GitHub Pages custom
domain documentation to confirm the recommended DNS records before saving
them.
