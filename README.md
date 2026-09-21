# Hendrix Network

**A calmer, sharper Wi-Fi cockpit for Omarchy.** Hendrix Network puts the
connection controls that matter in one native bar panel: scan and join nearby
networks, inspect live connection state, select an available Wi-Fi band, run a
speed test, and choose a DNS provider.

This is a **mod made by Hendrix**, based on the built-in Omarchy Network
plugin. Full credit for the original design, implementation, and Omarchy
platform goes to **DHH and the Omarchy contributors**. Hendrix maintains this
independent fork and its UI refinements.

## Privacy

This repository contains no personal network configuration. It does not ship
SSIDs, passphrases, custom DNS resolvers, NextDNS configuration, accounts, API
keys, or connection history. The panel reads and changes only the network
state already managed locally by Omarchy and NetworkManager.

## Install

```sh
omarchy plugin add https://github.com/HendrixBot/wifi-mod.git --enable
```

Click the bar icon to open the panel. Your existing DNS provider choices stay
local to your machine.

## Remove

```sh
omarchy plugin remove hendrix.network
```

Removing the plugin removes its checkout; it does not erase NetworkManager
connections, saved Wi-Fi credentials, DNS choices, or other local network
configuration.

## Credits and license

Derived from Omarchy's `omarchy.network` plugin, released under the MIT
License. See [NOTICE.md](NOTICE.md) for attribution.
