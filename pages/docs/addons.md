# Recommended Addons

## uBlock Origin tweaks

LibreWolf customizes the default lists present in uBO, by fetching
[Legitimate URL Shortener](https://github.com/DandelionSprout/adfilt/discussions/163),
and by enabling AdGuard URL Tracking Protection and Phishing URL Blocklist, but
you can also
[enable more filter lists](https://github.com/gorhill/uBlock/wiki/Dashboard:-Filter-lists)
in uBO's settings.

We **strongly recommend** using
[medium mode](https://github.com/gorhill/uBlock/wiki/Blocking-mode:-medium-mode)
to block all third-party scripts and control them manually.

## Password managers

We suggest that you use a more robust solution than the built-in password
manager available in the browser:

- [Bitwarden](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/):
  open source password manager that allows for synchronization across multiple
  devices.
- [KeePassXC-Browser](https://addons.mozilla.org/en-US/firefox/addon/keepassxc-browser/):
  official browser plugin for the open source password manager KeePassXC.

## Other Addons

The best suggestion is always to keep a very **minimal** addons setup, as every
extra piece makes your attack surface larger and is likely going to make you
stand out. For this reason, all the extensions mentioned in this section are
useful only for certain users, and they are **not** strictly necessary.

- [Canvas Blocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/):
  protects against some fingerprinting techniques. Suggested exclusively to
  users that [disable RFP](/docs/settings/#disable-rfp-resist-fingerprinting) or
  [enable WebGL](/docs/settings/#enable-webgl).
- [xBrowserSync](https://addons.mozilla.org/en-US/firefox/addon/xbs/): allows to
  securely store and sync bookmarks across browsers and devices.
- [LibreWolf Updater](https://addons.mozilla.org/en-US/firefox/addon/librewolf-updater/)
  (unofficial): checks for updates of LibreWolf and notifies you about them,
  which is especially useful for LibreWolf versions which don't get updated
  automatically via a package manager like the manual Windows installer. Also
  deserves the honorable mention as our first community-provided addon, although
  it's worth noting that we are not affiliated with it in any way.
