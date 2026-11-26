# FocusOn premium theme fonts

Font files the FocusOn app downloads on demand when a user applies a premium theme.
They are served through jsDelivr from a pinned git tag of this repository, e.g.

    https://cdn.jsdelivr.net/gh/Expand-Times/focuson.expandtimes.com@<tag>/focuson-theme-fonts/v1/<FontName>.ttf

Do not edit, rename or replace files in `v1/`: the app verifies each file's size and MD5
(see `constants/themeFontsCdn.ts` in the app repo) and rejects any file that differs.
To change fonts, add a new folder (e.g. `v2/`), create a new tag, and update the app.

All fonts are licensed under the SIL Open Font License; licence texts are in `licenses/`.
