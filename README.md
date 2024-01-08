# navicat16 mac version unlimited reset trial period script

<! -- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

## Disclaimer

** This script is free to use , this script is only for personal study use , the use of strict compliance with the open source license agreement . Strictly prohibited for commercial use, prohibit any profit-making activities. We are not responsible for any consequences of illegal use! **

## Script statement

- **This script applies to mac system, not for windows **
- **If you encounter any bugs, please send me an issue**.

## Instructions for use

- Download the latest version from [navicat premium](https://www.navicat.com.cn/download/navicat-premium) official website. Install and run it, and select 14 days trial.
- When the trial expires, run the reset script. `. /reset_navicat.sh`.

## Principle

- Remove the `~/Library/Preferences/com.navicat.NavicatPremium.plis` file with `key` value of `91F6C435D172C8163E0689D3DAD3F3E9` and `. B966DBD409B87EF577C9BBF3363E9614`.
  Corresponding data
  As shown (press spacebar to preview)
  ! [](image/img1.png)
- Delete the hidden files starting with `.' in the `~/Library/Application\ Support/PremiumSoft\ CyberTech/Navicat\ CC/Navicat\ Premium/` directory. ` hidden files in the `.
  As shown in the picture
  ! [](image/img.png)

## Why it doesn't work

Some users reported that it doesn't work after using it, please follow the steps below to check.

- Only Chinese version is supported, for English version, you can refer to the schematic description to write a script by yourself.
- Quit navicat and run the script again.
- Restart Mac and run the script again.
- Follow the instructions to check if the corresponding data is deleted successfully.

## Try other people's scripts.
- You can try `reset_navicat_52pojie.sh` script, provided by [52 crack](https://www.52pojie.cn/forum.php?mod=viewthread&tid=1669993).
Thanks to [@Dr-Octopus-dev](https://github.com/yhan219/navicat_reset_mac/issues/16) for providing it. **INFRINGEMENT**.
- Trying `reset_navicat_new.sh`, thanks to [pretend-m](https://github.com/pretend-m/navicat_for_mac_reset)

## License

! [](image/LGPL.svg)
