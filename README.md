# rclone_info

Public application information and privacy policy for a personal rclone Google Drive connection. This repository contains only static website files.

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then save.

After the Pages deployment succeeds:

| Google Auth Platform field | Value |
| --- | --- |
| Application home page | https://jameslilzs.github.io/rclone_info/ |
| Application privacy policy link | https://jameslilzs.github.io/rclone_info/privacy.html |
| Authorized domains | jameslilzs.github.io |

Open both URLs and confirm that they work before entering them in Google Cloud. These pages provide information; they do not automatically publish or verify the OAuth application. Google may request further configuration or ownership verification.

The application is currently named `rclone` in Google Auth Platform. The site identifies the maintainer's personal configuration and distinguishes it from the upstream rclone project.

## Files

- `index.html`: application purpose, permissions, operator, and privacy link.
- `privacy.html`: data access, use, storage, sharing, retention, and revocation.
- `style.css`: shared responsive styling; no external assets or scripts.
- `.nojekyll`: serves the static files without Jekyll processing.

Keep this information aligned with the actual configuration. Do not commit OAuth secrets, tokens, `rclone.conf`, cached data, or private Drive files.
