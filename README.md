# XMTPDemo

This simple demo shows how to connect to the XMTP network in a browser.

The app uses [`ethers`](https://cdn.jsdelivr.net/npm/ethers@5.7.2/) and the
[`@xmtp/browser-sdk`](https://github.com/xmtp/xmtp-js) loaded from a CDN.
Include the SDK in your module script using:

```html
<script type="module">
  import { Client } from 'https://cdn.jsdelivr.net/npm/@xmtp/browser-sdk@3.0.1/dist/index.js';
  // your code here
</script>
```

Open `index.html` in a modern browser to try the chat example.
