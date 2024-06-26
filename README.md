![Build Status](https://img.shields.io/badge/Build-passing-green?style=for-the-badge)
![Downloads](https://img.shields.io/github/downloads/r-neuschulz/BlockStuff/total?color=green&style=for-the-badge)
![Release](https://img.shields.io/github/v/release/r-neuschulz/BlockStuff?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/r-neuschulz/BlockStuff?style=for-the-badge)

<p align="center">
  <img src="BlockStuff_logo.png" width="40%">
</p>

# BlockStuff

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Magisk](https://img.shields.io/badge/Magisk-8A2BE2?style=for-the-badge&logo=magisk&logoColor=white)
![Root](https://img.shields.io/badge/Root-ff0000?style=for-the-badge&logo=superuser&logoColor=white)

BlockStuff is a comprehensive Magisk module designed to enhance productivity by blocking advertisements, excluding focus-draining content, and eliminating time-wasting distractions. It just blocks stuff that isn't worth your valuable time, attention, and compute.

It is primarily made by me for me. But if you see a benefit for yourself, feel free to give this project a star.

# Features

- 🛑 Blocks Ads
- 🛑 Blocks Android Apps Ads
- 🛑 Blocks Systemwide Capacity Drainers (YouTube, Reddit, Facebook, TikTok, etc.)
- ✅ Allows Whatsapp and Telegram (cause I actually need those)
- 🔃 Easy Update via Magisk

# Download

- [Magisk](https://github.com/topjohnwu/Magisk/releases)
- [Magisk Module](https://github.com/r-neuschulz/BlockStuff/releases)

# Updates

This module is designed to work out-of-the-box and is regularly updated (1x/week). Additional updates may come as needed.

# Credits

- [@topjohnwu](https://github.com/topjohnwu) for Magisk.
- [@Zackptg5](https://github.com/Zackptg5/MMT-Extended) for the Magisk Template.
- [@StevenBlack](https://github.com/StevenBlack) for his amazing [hosts](https://github.com/StevenBlack/hosts) files.
- [@pantsufan](https://github.com/pantsufan) for the initial project inspiration and foundation with [BlockAds](https://github.com/pantsufan/BlockAds), thank you!


# Additional Information

BlockStuff aims to provide a streamlined, distraction-free experience for Android users by targeting and blocking sources of unwanted content and time sinks. It leverages the hosts file to ensure system-wide effectiveness and reliability. As such, it requires root. 

# ToDo

- [x] Change hosts file to a more recent repo
- [x] Allow for adding custom hosts entries
- [ ] Check for www.* prefix on hosts for comprehensive blocking 
- [x] Allow update directly through magisk
- [ ] Change module building to a .zip in the main repo (which can be independently updated from the releases .zip) 
- [ ] Add automatic deployment and testing to a rooted qemu instance
- [ ] Update to the latest [MMT-extended package](https://github.com/Zackptg5/MMT-Extended)
- [ ] Figure out a way to dynamically update hosts file (independent of module)
- [ ] Improve Changelog notification inside module.
- [ ] Add Metrics section
