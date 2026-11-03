# Brays Gold card

This repository hosts the Brays avatar and a customized Gold activation card script for a personal Shadowrocket configuration.

The Gold feature script was adapted from `forceGold4.2.js` in [phamlong3539-stack/LOCKETGOLD](https://github.com/phamlong3539-stack/LOCKETGOLD). The original script's authorship is unchanged. The custom card displays “BRAYS 💛” and uses `brays-avatar.png`.

The Brays wrapper also merges the current server's camera and overlay settings with the Gold script's settings, so newer caption or sticker entries are not discarded by the older script. The script requests a 60-second limit, but actual recording length may still depend on the installed Locket app and account.

The public [`brays.conf`](brays.conf) keeps the original rules and script references, with the Brays Gold card script substituted. It does not include the original configuration's embedded certificate or password. After importing it into Shadowrocket, generate, install, and trust a certificate for this configuration in Shadowrocket's HTTPS Decryption settings.

The separate local `brays.conf` supplied in chat retains the original embedded certificate for users who already installed and trusted it. Do not publish that local file.
