# saltAMP

saltAMP controls the Hypex FusionAmp amplifiers in the Model Ø speakers over USB: level, scenes, source, health
and backups of the installer's tuning. ASOP (Amsterdam) is the first site.
It is a Mac app for Apple silicon, macOS 14.0 or later.

## Install

1. Download the newest `saltAMP-<version>-<build>.dmg` from [Releases](https://github.com/atrouwee/moonlabor-releases/releases).
2. Open it, and drag **saltAMP** to **Applications**.
3. Open it from Applications, not from the disk image: an app opened from the image cannot update itself.

## The first time

1. **Plug this Mac into an amp.** A USB cable from this Mac to the amp's USB port; a hub works for both speakers.
2. **Only reading at first.** saltAMP reads the amps and backs each one up before it may change anything.
3. **Mute all is always there.** Muting and lowering apply at once; anything louder waits for your Apply.

## Updates

saltAMP checks for updates by itself and asks before it installs one. It looks at
[appcast.xml](appcast.xml); each update is signed with saltAMP's own key, which the app already carries, and a
file that does not match is refused. The check is the only thing saltAMP asks of the internet: nothing about you or
the speakers is sent, and the backups of the tuning never leave your Mac.

Hypex and FusionAmp are trademarks of Hypex Electronics B.V.; saltAMP works with FusionAmp amplifiers and is not
affiliated with Hypex.

Made by Moonlabor B.V.
