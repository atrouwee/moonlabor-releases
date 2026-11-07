# saltLight

saltLight is a venue-agnostic Philips Hue engine that makes a room breathe. ASOP (Amsterdam) is the first site.
It is a Mac app for Apple silicon, macOS 27.0 or later.

## Install

1. Download the newest `saltLight-<version>-<build>.dmg` from [Releases](https://github.com/atrouwee/moonlabor-releases/releases).
2. Open it, and drag **saltLight** to **Applications**.
3. Open it from Applications, not from the disk image: an app opened from the image cannot update itself.

## The first time

1. **Join the café's Wi-Fi.** saltLight talks to the Hue Bridge on the café's own network.
2. **Allow Local Network.** macOS asks whether saltLight may find devices on your local network. Choose Allow: that is how it reaches the Bridge.
3. **Pair with the Bridge.** Open the pill at the top right (it names the site) and press Find. Then press the round button on the Bridge and Pair within 30 seconds.

## Updates

saltLight checks for updates by itself and asks before it installs one. It looks at
[appcast.xml](appcast.xml); each update is signed with saltLight's own key, which the app already carries, and a
file that does not match is refused. Settings AJ shares for the room (presets) arrive with the
update; your own pairing with the Bridge never leaves your Mac.

Made by Moonlabor B.V.
