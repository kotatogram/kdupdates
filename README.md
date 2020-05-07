# Kotatogram Desktop update files

This repo provides update files for Kotatogram Desktop autoupdater.

### Currently provided:
* Windows
* Linux (static)
* Linux (AppImage)

After uploading update files, I need to update [feed file](https://github.com/kotatogram/kotatogram.github.io/blob/dev/public/current). But I'm planning to make this process more automatic.

## What I'm planning

* [x] Make two branches: `beta` and `stable`. To reduce repository size, they are updating by force-push.
* [ ] Make action to force-push update files from all branches to `master`, remembering new files.
* [ ] Make action to change feed file and commiting it back.

After making this, there is a possibility that I'll make uploading to Telegram. But for now it's important to make at least this.
