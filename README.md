# Grayy IconPack

一套灰色（#cccccc）图标包，目的是减少手机干扰，配合灰黑色系的简单墙纸。


## 华为主题

华为主题为 .hwt 格式的压缩包，内部 `icon` 文件为包含所有图标的压缩包，本主题图标 png 格式图片大小为 192x192，图标外沿大小约为 60x60，可以手工增加图标，使用应用的 package id 命名即可。例如 mdict 的对应图标文件为：`icons/cn.mdict.png`

另外，桌面图标不显示文字，需要修改 `com.huawei.android.launcher/theme.xml` 文件，替换 

`<color name="workspace_app_text_color">#FFFFFFFF</color>` 为

`<color name="workspace_app_text_color">#00000000</color>`

![](screen-shot.jpeg?raw=true "screen shot")

###  使用方法

拷贝 `.hwt` 的压缩包到手机 `/Huawei/Themes` ，然后在系统主题里选择应用

## 图标来源

![](icons.png?raw=true "icons")

- https://www.iconfont.cn/
- https://icons8.com/



