<h1 align="center">
  <img src="https://github.com/wireapp/wire-desktop/raw/master/resources/icons/256x256.png" alt="Wire">
  <br />
  Wire
</h1>

<p align="center"><b>This is the snap for Wire</b>, <i>"Secure and private chat with end-to-end encryption"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

## Install

    sudo snap install wire
    snap connect wire:camera core:camera
    snap connect wire:mount-observe core:mount-observe
    snap connect wire:password-manager-service

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart: by Snapcrafters</p>

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325))
are working to land snap install documentation and
the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml)
upstream so Wire can authoritatively publish future releases. If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).
