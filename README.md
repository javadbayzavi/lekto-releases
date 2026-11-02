# Lekto

Android builds of Lekto. It writes down and translates a class as it is spoken, and practises
spoken conversation with you, using Google's Gemini models straight from the phone.

## Download

The latest APK is under [Releases](../../releases/latest). Open it on the phone to install it;
Android may ask you to allow installing apps from this source. A newer release installs over the
one you have, and keeps your notes.

It needs Android 7.0 or later, on a 64-bit ARM phone, which is nearly every Android phone today.

## You need your own Gemini API key

Lekto has no account and no key of its own: it uses yours.

1. Sign in to [Google AI Studio](https://aistudio.google.com/apikey) with a Google account.
2. Create an API key.
3. In Lekto, open Settings › General › Gemini API key, and paste it.

The key is kept only in the phone's secure storage.

## Free to use: no billing needed

Lekto only uses models that are on the Gemini API's free tier, so you do not need to set up
billing or add a payment method. The free tier has daily limits for each model; when one is
reached, wait until it resets the next day, or pick another model in Settings.

## No server in between

Lekto talks straight to Google's Gemini API (`generativelanguage.googleapis.com`), over an
encrypted connection. There is no server of ours in between, and no analytics or tracking: your
recordings, notes and conversations are stored only on the phone, and the audio and text go only
to Google, to be transcribed, translated or answered.

What Google does with them is set by Google's own terms for the Gemini API. On the free tier,
those terms allow Google to use what is sent to improve its products.

## Checking a download

Every release is signed with the same key. Its SHA-256 certificate fingerprint is:

```
E2:D5:D0:F2:64:B3:E7:16:CE:1E:DE:46:A2:8E:E2:86:24:E4:88:A6:A7:28:94:88:C1:E1:2B:B5:90:5F:62:EF
```
