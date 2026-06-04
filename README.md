# website-builder

Preview-hosting repo for the **ai-website-business** pipeline. Each qualified lead's
preview site is published under `/<biz_key>/index.html` and served by **GitHub Pages**
at `https://savcab.github.io/website-builder/<biz_key>/`.

- **Previews only.** These are on-spec previews shared with prospects by direct link.
  Production deploys to the client's own domain happen only **after the customer agrees to buy**.
- One directory per business key (`biz_key`); the Builder (`awb-build-html`) writes
  `index.html` there and pushes. Revisions overwrite the same directory.
- Root `index.html` is `noindex`; previews are reachable by their direct URL.
