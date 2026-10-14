# Profile README release checklist

This document applies to the preview branch `design/visual-profile-v2` only. Do not merge or publish to `main` without the owner's explicit approval.

## Automated checks
- [ ] Latest `Validate profile README` workflow run passes on the preview branch.
- [ ] Local SVG images parse and all referenced local image files exist.
- [ ] External image endpoints return image content.
- [ ] Activity widget retains `github_dark` and an official GitHub activity link.
- [ ] Featured project links and expected sections remain present.

## Manual review required
- [ ] Open the preview README on desktop, both light and dark GitHub themes.
- [ ] Open the preview README on a mobile browser; verify card wrapping, image scaling and legibility.
- [ ] Verify the hero text is not clipped and no cards overflow.
- [ ] Confirm the activity image displays and has no bright white calendar background.
- [ ] Click project, social and official activity links.
- [ ] Check external images again before publishing; their availability can change.

## Rollback
The public profile remains on `main` until approved. If a future release breaks, revert the merge commit or restore the previously known-good README and assets. GitHub Actions checks are not a guarantee that external image hosts will remain online.
