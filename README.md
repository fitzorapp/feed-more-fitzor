# Fitzor Info Feed

Remote content for the Fitzor **Info** page. Updating `info.json` updates the page without requiring a new mobile-app release.

## Publishing

In the GitHub repository, open **Settings → Pages** and choose:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**

The feed will then be available at:

`https://fitzorapp.github.io/feed-more-fitzor/info.json`

GitHub Pages can take several minutes to publish a new commit.

## Editing content

Edit only `info.json`. Keep `schemaVersion` at `1` and increase `contentVersion` for each published change. Sections appear in array order.

Supported section types:

- `announcement`
- `credits`
- `support`
- `link`

All text is rendered as plain text by the app. Actions must use HTTPS URLs.

`info.schema.json` documents the accepted format and can be used by an editor to validate changes.
