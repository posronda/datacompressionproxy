datacompressionproxy
====================

This is an experimental extension for Google Chrome bringing Chrome Data Compression Proxy from mobile to desktop PCs.

NEW! Version 1.2 adds a custom bypass list and an adblock list.

Download You can download the extension from Chrome Web Store.

How it works The extension sends all HTTP (but not HTTPS) traffic through Chrome Data Compression Proxy server, which uses SPDY protocol to speed up web browsing. Enabled state is indicated by a green icon. You can manually disable the proxy by clicking on it. When the proxy raises an error, it is being automatically disabled for 30 sec, so that the request can be resent.

The extension uses either chrome.webRequest (slower) in Chrome Stable or chrome.declarativeWebRequest (faster) in Chrome Beta/Dev, so ignore any warnings.

Statistics You can find the savings statistics at chrome://net-internals/#bandwidth.

Disclaimer The extension is provided as is with no warranty. Use it at your own risk. It is not affiliated with Google.

Clone from: https://code.google.com/p/datacompressionproxy/source/checkout
