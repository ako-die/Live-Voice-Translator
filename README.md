# LIVE VOICE TRANSLATOR

GitHub Pages-ready package.

## Publish
1. Create a **public** GitHub repository named `live-voice-translator`.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then choose **Save**.
6. Wait for GitHub Pages to publish. Open the URL shown in Settings → Pages.

## Use
- Open the published HTTPS address in Google Chrome or Microsoft Edge.
- Allow microphone access when prompted. If previously blocked, open Chrome site settings, set Microphone to **Allow**, then reload.
- Select the two languages. Each speaker presses their own microphone button when speaking.
- Keep an internet connection active.

## Limitations
- Speech recognition uses the browser Web Speech API; support varies by browser, device, language and region.
- Translation uses the public MyMemory endpoint without an API key. It has usage limits and is not a guaranteed production service.
- This prototype uses turn-taking; it does not reliably separate simultaneous speakers through one microphone.
- Text-to-Speech voices depend on those available on the device/browser.
