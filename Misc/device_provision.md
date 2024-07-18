# ruyi device provision系统镜像版本更新情况汇总(截至24/07/06)

## ToDo
+ 上游地址可以区分类别 (参考总结中的三种类型)
+ 总结补充 (待定)

## 需要更新

### 1.freebsd

#### 1.1 freebsd-riscv64-mini-live

+ 最新版本：14.1
+ [上游地址](https://download.freebsd.org/releases/riscv/riscv64/ISO-IMAGES/14.1/FreeBSD-14.1-RELEASE-riscv-riscv64-mini-memstick.img)

### 2.ubuntu-server

#### 2.1 freebsd-riscv64-mini-live

+ 最新版本：24.04
+ [上游地址](https://cdimage.ubuntu.com/releases/24.04/release/ubuntu-24.04-preinstalled-server-riscv64+unmatched.img.xz)

### 3.openwrt

#### 3.1 openwrt-sifive-unmatched

+ 最新版本：23.05.3
+ [上游地址](https://mirror-03.infra.openwrt.org/releases/23.05.3/targets/sifiveu/generic/openwrt-23.05.3-sifiveu-generic-sifive_unmatched-ext4-sdcard.img.gz)

### 4.revyos

#### 4.1 uboot-revyos-sipeed-lpi4a-8g

+ 最新版本：20240601
+ [上游地址](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/20240601/u-boot-with-spl-lpi4a.bin)

#### 4.2 uboot-revyos-sipeed-lpi4a-16g

+ 最新版本：20240601
+ [上游地址](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/20240601/u-boot-with-spl-lpi4a-16g.bin)

#### 4.3 uboot-revyos-sipeed-lcon4a-8g

+ 最新版本：20240606
+ [上游地址](https://github.com/0x754C/sipeed-th1520-laptop-extra/releases/download/20240606/u-boot-with-spl-console8g.bin)
+ 备注：[Issue](https://github.com/weilinfox/ruyi-reimu/issues/14)中上游地址为[20240516](https://github.com/0x754C/sipeed-th1520-laptop-extra/releases/download/20240516/u-boot-with-spl-console8g.bin)

#### 4.4 uboot-revyos-sipeed-lcon4a-16g

+ 最新版本：20240606
+ [上游地址](https://github.com/0x754C/sipeed-th1520-laptop-extra/releases/download/20240606/u-boot-with-spl-console16g.bin)
+ 备注：[Issue](https://github.com/weilinfox/ruyi-reimu/issues/13)中上游地址为[20240516](https://github.com/0x754C/sipeed-th1520-laptop-extra/releases/download/20240516/u-boot-with-spl-console16g.bin)

#### 4.5 revyos-sipeed-lcon4a

+ 最新版本：20240606
+ [上游地址](https://github.com/0x754C/sipeed-th1520-laptop-extra/releases/20240606)
+ 备注：文件名已变更，请从上游地址中选择合适的镜像下载，与[4.3](#43-uboot-revyos-sipeed-lcon4a-8g)，[4.4](#44-uboot-revyos-sipeed-lcon4a-16g)

#### 4.6 uboot-revyos-milkv-meles-8g

+ 最新版本：v2024-0417
+ [上游地址](https://github.com/milkv-meles/meles-images/releases/download/v2024-0417/u-boot-with-spl-meles.bin)
+ 备注：文件名已变更，上游地址中对应名称为u-boot-with-spl-meles.bin

#### 4.7 uboot-revyos-milkv-meles-4g

+ 最新版本：v2024-0417
+ [上游地址](https://github.com/milkv-meles/meles-images/releases/download/v2024-0417/u-boot-with-spl-meles-4g.bin)
+ 备注：文件名已变更，上游地址中对应名称为u-boot-with-spl-meles-4g.bin

#### 4.8 revyos-milkv-meles

+ 最新版本：v2024-0417
+ [上游地址](https://github.com/milkv-meles/meles-images/releases/download/v2024-0417/)
+ 备注：文件名已变更，请从上游地址中选择合适的镜像下载，该镜像与[4.6](####-46-uboot-revyos-milkv-meles-8g)，[4.7](####-47-uboot-revyos-milkv-meles-4g)上游同源

#### 4.9 revyos-sg2042-milkv-pioneer

+ 最新版本：20240327
+ [上游地址](https://mirror.iscas.ac.cn/revyos/extra/images/sg2042/20240327/revyos-pioneer-20240327-180424.img.zst)

### 5.debian

#### 5.1 debian-fishwaldo-sg200x-sipeed-licheervnano

+ 最新版本：v1.4.0
+ [上游地址](https://github.com/Fishwaldo/sophgo-sg200x-debian/releases/tag/v1.4.0)

### 6.buildroot

#### 6.1 buildroot-sdk-sipeed-licheervnano

+ 最新版本：20240528
+ [上游地址](https://github.com/sipeed/LicheeRV-Nano-Build/releases/tag/20240528)

#### 6.2 buildroot-sdk-milkv-duos-sd

+ 最新版本：Duo-V1.1.1
+ [上游地址](https://github.com/milkv-duo/duo-buildroot-sdk/releases/download/Duo-V1.1.1/milkv-duos-sd-v1.1.1-2024-0528.img.zip)
+ 备注：[Issue](https://github.com/weilinfox/ruyi-reimu/issues/5)中上游地址未明确给出下载哪一具体镜像

#### 6.3 buildroot-sdk-milkv-duo256m

+ 最新版本：Duo-V1.1.1
+ [上游地址](https://github.com/milkv-duo/duo-buildroot-sdk/releases/download/Duo-V1.1.1/milkv-duo256m-v1.1.1-2024-0528.img.zip)
+ 备注：[Issue](https://github.com/weilinfox/ruyi-reimu/issues/4)中上游地址未明确给出下载哪一具体镜像

#### 6.4 buildroot-sdk-milkv-duo256m-python

+ 最新版本：Duo-V1.1.1
+ [上游地址](https://github.com/milkv-duo/duo-buildroot-sdk/releases/download/Duo-V1.1.1/)
+ 备注：[Issue](https://github.com/weilinfox/ruyi-reimu/issues/3)中上游地址未明确给出下载哪一具体镜像
  Duo256M and DuoS support python-numpy

#### 6.5 buildroot-sdk-milkv-duo

+ 最新版本：Duo-V1.1.1
+ [上游地址](https://github.com/milkv-duo/duo-buildroot-sdk/releases/download/Duo-V1.1.1/milkv-duo-v1.1.1-2024-0528.img.zip)
+ 备注：[Issue](https://github.com/weilinfox/ruyi-reimu/issues/2)中上游地址未明确给出下载哪一具体镜像

#### 6.5 buildroot-sdk-milkv-duo

+ 最新版本：Duo-V1.1.1
+ [上游地址](https://github.com/milkv-duo/duo-buildroot-sdk/releases/download/Duo-V1.1.1/)
+ 备注：[Issue](https://github.com/weilinfox/ruyi-reimu/issues/1)中上游地址未明确给出下载哪一具体镜像
  Duo256M and DuoS support python-numpy

## 不需要更新

### 1. openkylin

#### 1.1 openkylin-riscv64-sifive-unmatched

+ [上游地址](https://releases.openkylin.top/2.0/)
+ 备注：最新版为2.0 alpha，非稳定版

### 2. openeuler

### 2.1 oerv-awol-d1-xfce

+ [上游地址](https://mirror.iscas.ac.cn/openeuler-sig-riscv/openEuler-RISC-V/preview/openEuler-23.09-V1-riscv64/)
+ 原因：上游未更新

### 2.2 oerv-awol-d1-base

+ [上游地址](https://mirror.iscas.ac.cn/openeuler-sig-riscv/openEuler-RISC-V/preview/openEuler-23.09-V1-riscv64/)
+ 原因：上游未更新

## 周会提供的信息

+ canaan 上游提供的两款镜像:
  [canmv-debian-sdk-canaan-k230](https://kendryte-download.canaan-creative.com/developer/k230/canmv_debian_sdcard_sdk_1.3.img.gz)
  [canmv-ubuntu-sdk-canaan-k230](https://kendryte-download.canaan-creative.com/developer/k230/canmv_ubuntu_sdcard_1.3.img.gz)
  存在问题
+ OpenBSD 上游为 [tuna 镜像源](https://mirrors.tuna.tsinghua.edu.cn/OpenBSD/7.4/riscv64/install74.img)，非官方上游发布源，同步时间可能存在问题
+ 有些镜像存在上游名称变更的问题，如 [revyos-sipeed-lcon4a](####-4.5-revyos-sipeed-lcon4a), [revyos-milkv-meles](####-4.8-revyos-milkv-meles)
+ 剩余情况待补充

## 总结

通过 [packages-index](https://github.com/ruyisdk/packages-index) 与 [ruyi-reimu](https://github.com/weilinfox/ruyi-reimu) 可知各系统镜像上游来源可分为：

+ github release
+ iscas镜像站
+ 系统镜像发布方自行维护的上游源

且可以总结出目前各系统镜像之间并未存在一个相对统一的命名规范，因此在处理时需要找到适宜的解决方案