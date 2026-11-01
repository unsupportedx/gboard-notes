# Gboard Changes

Three small changes to make Gboard easier to use.

Base version: Gboard 18.5.6 beta · Final clean version: v22

## No clipboard limit

Copied items stay in the clipboard. They are not deleted after a short time, and new items do not push out the old ones.

## Microphone stays on for 60 seconds

Voice typing waits for you. The microphone does not turn off after a few seconds — it stays on for a full minute.

## Always-on microphone

The microphone opens by itself when the keyboard opens. No need to tap the microphone button every time.

## How it was done

| Change | Technical detail |
| --- | --- |
| Clipboard | Item limit raised to 100; auto-expiry removed. |
| Microphone — 60 seconds | Listening timeout changed from 5 seconds to 60 seconds. |
| Always-on microphone | Auto-start gates (wee.o / wee.n) enabled, so the microphone starts when the keyboard opens. |

## Why it isn't published

This is a modified Google app, so it is not published as an APK. There is no release — this page is only a description.
