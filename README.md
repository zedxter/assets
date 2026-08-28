# assets

Shared media assets for pizdato projects.

## Structure
- `images/` — images (PNG, JPG, WEBP)
- `videos/` — videos (MP4, WEBM)

Upload files via `gh api -X PUT repos/zedxter/assets/contents/<path>` (base64 content), or PR into the repo.

Used in dev.to posts / LinkedIn / channel media as stable public raw URLs:
`https://raw.githubusercontent.com/zedxter/assets/main/<path>`
