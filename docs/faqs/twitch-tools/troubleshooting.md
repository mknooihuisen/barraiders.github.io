---
title: Twitch Tools - Troubleshooting
description: Encountering issues with the Twitch Tools plugin on your Stream Deck? Our troubleshooting guide has the answers. Find solutions to common problems and get your setup back on track with BarRaider's plugin documentation.
---

# Twitch Tools - Troubleshooting

## General Issues

### I keep having to authenticate my account
This is a known issue if you are running Stream Deck as admin. Running Stream Deck as administrator is strongly discouraged. It's firstly a security risk as it allows 3rd party plugins to run as administrator. Secondly, it is known to cause various issues in saving plugin settings as well as losing authentication tokens.

### Action does not do anything
Some actions, like the Ban / Timeout and Timeout actions require you to be live and having active chatters in order to work.
If you are Live and have active chatters, make sure you installed the custom profiles during installation. In order to get these profiles, uninstall and reinstall the plugin.

## Validation failed error
Solution depends on what you're seeing in your browser.

### Browser shows an error
1. Try restarting the Stream Deck Software and try setting up again.
![Restarting Stream deck](https://barraider.com/images/restart.png"How to quit the Stream Deck Software")
1. Change the default browser to Edge and try again.
2. Using the Edge browser follow [this guide](https://www.whatismybrowser.com/guides/how-to-enable-javascript/edge) and when you come across the allow/block list, add `localhost:4201` to the allow list.

### Browser shows success but not connecting
This is usually a Firewall/Antivirus/VPN/PiHole blocking the connection. Find the culprit and fix/disable it and try again.