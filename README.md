![alt text](https://s8.postimg.cc/5hy0iaavp/11802632.png "BlackBox")
# BlackBox Kernel

## BlackBox Kernel is Compatible with the following devices - [Download](http://kunalkene1797.github.io/downloads)

- Mi Redmi Note 5 Pro (Whyred)
- Android One First Generation (Sprout)
- Yu Yureka (Tomato)

  ---

## Build Custom Kernel From Source

Initialize Linux Distro, Clone Repositories & Execute Build Script

    // Establish Environment
    sudo apt-get update
    sudo apt-get install openjdk-8-jdk
    sudo apt-get install git-core gnupg flex bison gperf build-essential zip curl zlib1g-dev gcc-multilib g++-multilib libc6-dev-i386 lib32ncurses5-dev x11proto-core-dev libx11-dev lib32z-dev libgl1-mesa-dev libxml2-utils xsltproc unzip python libssl-dev openssl
    // Clone Repository
    git clone https://github.com/KunalKene1797/AnyKernel2
    git clone https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86
    git clone https://github.com/BlackBox-Kernel/%DEVICEDIRECTORY%
    // Make Flashable Zip Folder
    mkdir flashablezips
    // Execute Build Script
    ./bb_build.sh

---

## Have Bugs?

Contact Me (Telegram): @kunalkene1797

---

## Links

- BlackBox GitHub - [https://github.com/BlackBox-Kernel](https://github.com/BlackBox-Kernel/)
- Developer Website - [https://kunalkene1797.github.io](https://kunalkene1797.github.io)
