# grouper_hostmode_charging

This is a patch for the 2012 Nexus 7 Wi-Fi kernel to allow for host mode charging with an OTG splitter. I use this for my Kegbot (https://kegbot.org/)

The code is ported (and poorly at that) from https://github.com/mehrvarz/android_kernel_asus_grouper/commit/e35cc4de7f891cf71e206c72af4b0f61820f2fea. This patch should (mostly) just include what's needed to allow host mode charging from that commit. It could definitely benefit from a bit of clean-up and TLC.

There is a pre-built copy of the kernel with the patch applied on 6ff7a516ea0284e3265075001b91e6df3e16509f in the releases section. That kernel is verfied to work on Google's 5.0 Factory Image -- https://developers.google.com/android/nexus/images SHA1: 93daa4d30d7e9201f038591d8cfb9486c54e056d. It might work on later versions as well; I'll give it a shot once I download the latest.

Grouper source: https://android.googlesource.com/device/asus/grouper/

