# Sample chrome extension (filename branch)

This is a sample chrome extension to test [a bug](https://github.com/egoroof/yandex-music-fisher/issues/41).

Tests [chrome.downloads.download](https://developer.chrome.com/extensions/downloads#method-download)
method with `filename` prorepty.

## How to reproduce

Run this extension (from `filename` branch)

## What is the expected result?

The file is downloaded with the correct name from `filename` property and in the correct path within the default download directory.

## What happens instead of that?

The file is downloaded and saved with the original's URL filename (i.e. `filename` property is ignored), in the root of the default download directory.
