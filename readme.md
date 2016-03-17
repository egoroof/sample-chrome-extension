# Sample chrome extension

This is a sample chrome extension to test [a bug](https://bugs.chromium.org/p/chromium/issues/detail?id=417112).

Tests [chrome.downloads.download](https://developer.chrome.com/extensions/downloads#method-download)
method with `saveAs = false`

## How to reproduce

1. go to **Settings** > **Show advanced settings**
2. enable checkbox **Ask where to save each file before downloading**
3. run this extension

## What is the expected result?

Download starts without dialog in which you select download location like
you didn't enable the setting.

## What happens instead of that?

You see save file dialog.
