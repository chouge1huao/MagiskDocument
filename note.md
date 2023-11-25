## R655F6129-kitsune

Welcome back Delta users!

### Diffs to official Magisk

- [Zygisk] New way to load Zygisk, like [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext) project
- [General] Add MagiskHide back from Magisk v23.0 with minor improvement
- [General] Add SuList, whitelist based hide
- [General] Support mounting in pre-init for modules
- [General] Support install Magisk into system partition (for emulators)
- [resetprop] Don't always deleting read-only properties before setting them

-[Zygisk]加载Zygisk的新方法，就像ZygiskNext项目 

-[General]AddMagiskHideProm Magic23.0稍有改进

-[常规]引入SuList，基于白名单的隐藏[常规]支持在预初始中安装模块

-[常规]支持将Magisk安装到系统分区(用于仿真器)

-[resetprop]在预设唯读属性之前，不要总是删除唯读属性

### Credits
- [Ptrace init based Zygisk](https://github.com/HuskyDG/Magisk/commits/ptrace-zygisk), we are using part of code from [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext) writing by [Dr-TSNG](https://github.com/Dr-TSNG/ZygiskNext) and [5ec1cff](https://github.com/5ec1cff). Credits was adding to code as