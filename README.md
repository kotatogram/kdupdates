# Kotatogram Desktop update files

This repo provides update files for Kotatogram Desktop autoupdater.

### Currently provided:
* Windows
* Linux (static)
* Linux (AppImage)

After uploading update files, I need to update [feed file](https://github.com/kotatogram/kotatogram.github.io/blob/dev/public/current). But I'm planning to make this process more automatic.

## What I'm planning
1. I'll make two branches: `beta` and `stable`. To reduce repository size, they are updating by force-push.
2. When branch is updated, GitHub CI will push files from both branches to `master`, and remember new files.
3. After pushing CI will clone updates site and change feed file, commiting and pushing it back.

After making this, there is a possibility that I'll make uploading to Telegram. But for now it's important to make at least this.
