### 404Human

rust, headless browsers and the security edges of both. by day i build an offline-first point-of-sale for precious-metal dealers in germany, with fiscal signing (TSE) and tax exports (DSFinV-K, DATEV) that have to be exact to the cent.

**merged upstream**

- [h4ckf0r0day/obscura](https://github.com/h4ckf0r0day/obscura), the rust headless browser for ai agents
  - [#806](https://github.com/h4ckf0r0day/obscura/pull/806) layout: fixed and absolute boxes resolve against the viewport
  - [#805](https://github.com/h4ckf0r0day/obscura/pull/805) net: navigation follows 20 redirects, not 19
  - [#804](https://github.com/h4ckf0r0day/obscura/pull/804) js: chrome-shaped blob urls
  - [#803](https://github.com/h4ckf0r0day/obscura/pull/803) js: `new FormData(form)` reads the form
  - [#120](https://github.com/h4ckf0r0day/obscura/pull/120) cdp: puppeteer connect no longer times out
- [nornsPOS/norns-xrf-agent](https://github.com/nornsPOS/norns-xrf-agent/pull/1) reliable delivery of xrf analyser results

**found**

- [obscura #816](https://github.com/h4ckf0r0day/obscura/pull/816) ssrf through ipv6 addresses that carry an ipv4 inside (6to4, nat64), reaching cloud metadata endpoints. closed in favour of the fix that landed upstream.
