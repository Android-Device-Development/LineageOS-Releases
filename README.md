# LilBlinx's LineageOS Releases

## Introduction

This repository contains personal builds of LineageOS 16.0 for Xiaomi Redmi Note 4X (mido).

## Requirements

- Unlocked bootloader (if you haven't unlocked already check this link: [Fastest way to Unlock the Bootlader](https://forum.xda-developers.com/redmi-note-4/how-to/fastest-to-unlock-bootlader-t3689116))

- Stable and working internet connection

- Battery percentage at least 50%

## Downloads

- [LineageOS 16.0](https://github.com/davidtrpcevski/LineageOS-Releases/releases)

## Installation

1. Download latest [TWRP](https://dl.twrp.me/mido/)

2. Download the latest [build](https://github.com/davidtrpcevski/LineageOS-Releases/releases)

3. Download the latest [firmware](https://xiaomifirmwareupdater.com/firmware/mido/)

4. Download latest GApps package from [OpenGApps](https://opengapps.org/)

5. Download latest Magisk package from [Magisk](https://github.com/topjohnwu/Magisk/releases)

6. Flash TWRP image (use this guide: [How to Install TWRP](https://www.xda-developers.com/how-to-install-twrp/))

7. Reboot to recovery

8. (Optional or if coming from other ROM) Wipe everything by going to Wipe -> Advanced Wipe and tick every checkbox

9. (Optional or if coming from other ROM) Wipe data by going to Wipe -> Format Data

10. Flash the firmware first

11. Flash the latest build

12. Flash OpenGapps

13. Flash Magisk

14. Reboot

## Bug reports

- Create a bug report in the [Issues](https://github.com/davidtrpcevski/LineageOS-Releases/issues) section.

- For easier report, use the Bug report template.

- Please include full logs when you report bugs. Bug reports without logs will be closed and ignored!

## FAQ

1. Why are you building LineageOS 16.0 when there is an official support?

   - I'd rather flash MIUI than to use those builds with those trees.

2. What's different from official builds?

   - I'm adding few things here and there that I need and which you can check in the changelogs and they are available my GitHub repos.

3. Does it support Over-the-Air updates?

   - Yes!

4. Will your builds pass the root check, CTS and won't have problems with banking apps?

   - Yes, the builds are signed with personal keys and are using release-keys for build tag!

5. Awesome, what can I do to switch to your builds?

   - If coming from other ROM, back up your data and clean flash the build. Then just sit and enjoy!

6. Can I dirty flash these builds, i.e. not wiping my data?

   - I personally don't recommend to dirty flash between builds, but there are reports from users that it worked for them. I am not responsible for any data loss or malfunction if you go with this route.

7. Please, can you include feature XYZ?

   - No and I will never include something I don't use. Please don't message me or create issues that will lead to a feature requests. They will be ignored!

8. Why did you close your threads at XDA and leave?

   - Because of their greedy behaviour at making money, slow load and reponse or not loading at all and the arrogant interaction between the staff and users.
   - More info can be found [here](https://medium.com/@mazdarider23/anti-xda-stance-16a0e1867f5b)

9. I like your builds, how can I support you?

   - First of all, thank you so much! Yes, you can support me by donating to the PayPal link below.

## Donations

- [PayPal Donation Link](https://www.paypal.me/CiggyDevs)

- [Be my Patreon](https://www.patreon.com/lilblinx)

## Social

- Feel free to join the Telegram group here: [LineageOS Releases](https://t.me/losreleases)

## Sources

- [Kernel Tree](https://github.com/davidtrpcevski/kernel_xiaomi_msm8953)

- [Device Tree](https://github.com/davidtrpcevski/android_device_xiaomi_mido)

- [Vendor Tree](https://github.com/davidtrpcevski/proprietary_vendor_xiaomi)

## Credits

- Warabhishek for the initial trees

- Zeelog for Device and Vendor trees

- KrasCGQ for Kernel source

- LineageOS for the ROM source
