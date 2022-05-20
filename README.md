# electron-osk-webview-test
Test app to reproduce the issue in Electron. App consists of pairs of webviews, textareas and iframes. Webviews and iframes are showing the same html file -> textarea.html. 

### Start app:

```
npm install
npm start
```

### Steps to repro issue:

- Start app on touchless device
- Press on input in any webview
- Press somewhere else except input areas
- Observe how OSK does not hide
