# Navicat 17.3.x Crack

## NOTICE

本项目仅用作二进制安全学习交流之用, 使用本项目后果自负.

## Thanks

感谢 吾爱破解`@iwolf` 提供的破解方法 [Navicat 17 破解教程](https://www.52pojie.cn/thread-2052969-1-1.html)

感谢 吾爱破解`@payallmoney` 提供的破解补丁 [navicat 17.3.2破解](https://www.52pojie.cn/thread-2055542-1-1.html)

鄙人的工作就是对于新版的navicat, `libcc.dll`文件的加解密方式没有变, 只是经过了重新编译, 函数的位置有所不同.
因此, 仍能使用 `@payallmoney` 提供的补丁, 只需要重新定位函数地址即可.
另外, 原有的补丁中替换了一处现有的字符串常量, 不保证不会出问题, 所以鄙人采取了新增一个PE section, 新增字符串常量的方式进行替换.

## 适用版本

截至本次Commit, 适用于 Navicat Premium (简体中文版) 17.3.6 (当前最新) 及以下版本.

我对 17.3.6, 17.3.4, 17.3.2 进行了测试.

## 小记

第一次被star, 谢谢大家的支持, 更感谢 `@iwolf` 和 `@payallmoney` 的无私奉献.

附注: 暂时没有macOS版本 qwq (鄙人没有macOS设备) 理论上讲分析方法和补丁思路是类似的, 欢迎有兴趣的朋友进行尝试. linux版本同理.
