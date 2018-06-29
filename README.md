# BlackBox Kernel - WhyRed
R-Edition of this Kernel will always be focused on Stability and the X-Edition will be Focused on Experimental features.

## Setup Build Environment and Build BlackBox
If you want to get rid of the long Google URL in the kernel version, then you need to add the following before compiling the kernel

```bash
sudo apt-get update
sudo apt-get install openjdk-8-jdk

sudo apt-get install git-core gnupg flex bison gperf build-essential zip curl zlib1g-dev gcc-multilib g++-multilib libc6-dev-i386 lib32ncurses5-dev x11proto-core-dev libx11-dev lib32z-dev libgl1-mesa-dev libxml2-utils xsltproc unzip
sudo apt-get intall python libssl-dev openssl

git clone https://github.com/KunalKene1797/AnyKernel2
git clone https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86
git clone https://github.com/BlackBox-Kernel/blackbox_whyred_TWR

mkdir flashablezips

./bb_build.sh
```
## Found bugs?

###### Contact:
Telegram: **@kunalkene1797**
