---
title: Himal VPN privacy policy
---

# Himal VPN privacy policy

Last updated: 6 October 2026

Himal VPN is run by **Sundar Shahi** ("we"). This policy covers the Himal VPN Chrome extension and
the Himal servers it connects to. Questions: **shahithakurisundar@gmail.com**.

## What Himal does

When you connect, the extension sends your Chrome traffic through an encrypted connection to a
Himal server in the country you choose. Websites see the server's IP address instead of yours.
It protects pages you open in Chrome, not other apps on your device.

## What stays on your device

- **Your access key.** It holds the list of servers and the password the extension uses to
  sign in to them. It's stored in Chrome on your device and sent only to Himal servers, to
  sign in.
- **Your settings and site rules.** These include favourites, rules like "open this site
  without the VPN", the theme, and the kill-switch and leak-protection choices. They are
  stored in Chrome on your device and never sent to us.
- **Recent connection details.** This means the IP address sites see, how long you've been
  connected, and how fast each server answers. Shown to you, kept on your device.

## What passes through our servers

While you're connected, your Chrome traffic goes through the Himal server you picked, so that
server can see which sites you connect to. Pages on secure (https) sites stay encrypted between
Chrome and the site.

- **Not recorded:** our servers don't record the sites you visit, what you do on them, or your
  traffic.
- **Short error logs:** servers keep their own error messages, such as a failed certificate
  renewal, for up to 2 days. These don't include the sites you visit.
- **WireGuard:** if you use the WireGuard app on a phone or computer, the same applies. The
  server knows your device's name and key so it can let it in, and it doesn't record your
  traffic.

## Other services the extension uses

- **Cloudflare and ipify.** To show which IP address sites see, the extension loads
  https://www.cloudflare.com/cdn-cgi/trace or https://api.ipify.org. Like any website, they
  receive your IP address (or the server's, while you're connected).
- **Google's STUN server.** Only if you press "Run leak test" in Settings: the test asks
  stun.l.google.com which addresses video-call features would reveal.
- **Hosting companies.** Our servers run on rented machines in each country. Those companies
  carry the encrypted traffic but can't see inside it.

## What we never do

- We don't sell or share your data, and we don't use it for ads.
- We don't use analytics or tracking in the extension.
- We use your data only to connect you. We never use it to decide credit or lending.

## Your choices

- **Disconnect:** Chrome goes back to connecting directly.
- **Remove your key:** do it in Settings, or remove the extension. Either one deletes what the
  extension stored on your device.
- **Remove a WireGuard device:** ask us at shahithakurisundar@gmail.com, and the server deletes its key.

## Children

Himal VPN isn't meant for children under 13, and we don't knowingly serve them.

## Changes

If we change how Himal handles data, we'll update this page and the date at the top before the
change takes effect. If the change matters, we'll also tell you in the extension.

## Contact

Sundar Shahi · shahithakurisundar@gmail.com
