# MagScroll privacy page

This repository contains only MagScroll's public-facing privacy-policy page.
It does not contain the app's source code, books, user data, speech models or
signing credentials. No licence for the MagScroll application is granted here.

## Status

The page is a **pre-release draft**, not a completed commercial-release or
Google Play compliance review. The app's rights, SDK diagnostics, declarations
and exact release artifact still require review. Publishing this page does not
approve the app for distribution. Contact: onemadpunk+magscroll@gmail.com.

## GitHub Desktop

Choose **File → Add local repository**, then select this folder. Review the
files and commit them. Use **Publish repository**, name it `magscroll-policy`,
and deselect **Keep this code private** for free public GitHub Pages hosting.
Only the files in this small folder should be included—never the app folder.

If an empty `magscroll-policy` repository already exists on GitHub, clone that
repository to a different empty folder and copy only `index.html`, `.nojekyll`
and this README into it. Do not publish a duplicate repository or force-push
over existing work.

## GitHub Pages

On this repository's GitHub website, open **Settings → Pages**. Choose
**Deploy from a branch**, select **main** and **/(root)**, then **Save**.
Use the URL GitHub displays after deployment; a predicted URL is not proof
that it is live. Check the HTTPS page while logged out before using the URL.

This page requires no build, paid hosting, analytics, external fonts or scripts.
`.nojekyll` keeps it a plain static HTML page.

The source draft is maintained separately in the private development workspace
at `Magscroll/play/privacy-policy.html`. Update this repository's `index.html`
from that reviewed source when the policy changes. Remove the draft warning
only after the release-specific review is genuinely complete. Do not add a
final policy URL to the app or Play paperwork until publication is verified.

Documentation:

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
