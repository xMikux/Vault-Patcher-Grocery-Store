# **Vault Patcher Grocery Store丨Vault Patcher杂货铺**

维护：KlparetlR、TexTrue、X209

## 相关链接

[![Vault Patcher](https://img.shields.io/badge/github-Vault%20Patcher-blue)](https://github.com/3093FengMing/VaultPatcher)
[![modrinth-VP](https://img.shields.io/badge/modrinth-Vault%20Patcher-green)](https://modrinth.com/mod/vault-patcher/versions)
[![Hardcode Patcher](https://img.shields.io/badge/github-Hardcode%20Patcher-F16436)](https://github.com/LocalizedMC/HardcodePatcher)
[![mcmod-VP](https://img.shields.io/badge/mcmod-Vault%20Patcher-blue)](https://www.mcmod.cn/class/8765.html)
[![mcmod-HP](https://img.shields.io/badge/mcmod-Hardcode%20Patcher-blue)](https://www.mcmod.cn/class/9315.html)

## 介绍

这是一个存放Vault Patcher模组的配置+汉化以及编写工具的开源库

服务于熟悉Vault Patcher模组的**大佬**，在这里，你可以调用模组的配置文件，修提交修改配置或汉化的建议

你可以用它们去汉化整合包的硬编码，提升汉化细节程度

## 配置及翻译上传的要求及格式

请在`ModConfigs`文件夹中提交你的PR，格式为`ModConfigs/<CurseForge 项目名称>/<模组命名空间>`

<模组命名空间>会在之后用于硬编码汉化下载模组，需准确填写，一般是模组存放class文件的文件夹，在你第一次见到class文件的所在文件夹名

PR格式为`<模组英文名> <简述>`

json配置文件要求第一个对象要有"authors"，"name"，"desc"，"mods"，并且**对期内容限定**
```txt
    {
        "authors": "<隨意填>",
        "name": "<模组名>模组汉化",
        "desc": "VP<版本号>+可启用，...",
        "mods": "<模组模组，要细致到模组名、游戏版本、模组版本>",
        "dynamic": false
    },
以下为示范：
    {
        "authors": "KlparetlR、Qing_Lanovo",
        "name": "XPCoins模组汉化",
        "desc": "VP1.3.3+可启用，VPGS开源",
        "mods": "XPCoins (FORGE-1.16.4) v1.0.7",
        "dynamic": false
    },
```

可以参考CFPA的[i18n库](https://github.com/CFPAOrg/Minecraft-Mod-Language-Package/blob/main/CONTRIBUTING.md)

## 调用后的要求和限制 **（必看，须知）**

本库的协议为[CC-BY-NC-ND 4.0](https://github.com/KlparetlR/Vault-Patcher-Grocery-Store/blob/main/LICENSE.txt)，即

BY（Attribution，署名归属）：您可自由地分享和改编本作品，但您**必须注明**创作者的版权归属。

NC（Non Commercial，非商业性）：您可自由地分享和改编本作品，但您不得用于**商业目的**。

ND（No Derivatives，禁止改编）：你可自由地分享本作品，但您不得合成、转换和改造本作品。

如果你是私用，不公开，这里可以不管，如果您要**用于整合包汉化公布**等分享本作品的行为，你要在汉化文件或汉化发布视频内**注明**创作者的版权归属

以下是格式(这个是方便“复制”用的，可以不遵守格式，但要有注明)：
```txt
本<可改内容>的硬编码汉化中有使用VPGS库（KlparetlR/Vault-Patcher-Grocery-Store）提供的内容
```

## 其他的一些话

因为硬编码汉化这方面涉足的人很少，可能这个库的配置很少，但作者还是会积极努力的维护它，一般以作者主动上传和别人授权的内容上传，欢迎**大佬**提交配置和汉化（PR），Thanks♪(･ω･)ﾉ
