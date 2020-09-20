# Anime
Create a Document Package for anime to open in your favourite macOS media player

## What

Append `.anime` to the folder of your totally legal copy of an anime, and then add a custom icon through the the Get Info (⌘+I) for a nice look.

Then you would be able to simply open the package to start viewing.

## How to use
Merge `Info.plst` with the `Info.plist` of your favourite macOS media player.

Note: you may need to duplicate the app and remove `_CodeSignature` as you would be modifying the app.

## Tested with
- IINA.app
- QuickTime.app

# Why
I made this at 2AM. That doesn’t explain why.

You could theoretically just change the Document Types in `Info.plist` to allow for a one-click opening any folder-opening application (such as IINA), so try it out.