# Logix Transportation Limited website

Static marketing site for Logix Transportation Limited (Regina, SK).

## Live hosting

GitHub Pages from this repository (public).

## Custom domain (Squarespace DNS)

Keep Google Workspace MX records unchanged.

1. Turn off domain forwarding on logixtransportation.ca if it still forwards elsewhere.
2. Add CNAME: `www` → `<user>.github.io` (or the Pages hostname GitHub shows).
3. For apex `@`, use Squarespace ALIAS/ANAME to the same target, or follow GitHub Pages custom domain A records if required.
4. In the repo Settings → Pages → Custom domain, enter `www.logixtransportation.ca` (and optionally apex).
