[Clash简介](#Clash简介)

[一：创建clash订阅链接](#二：安卓设置与使用)

[二：【安卓设置与使用】](#二：[安卓设置与使用])

[三：【iOS的Pharos Pro】](#三：[iOS的Pharos Pro])

[四：【windows设置与使用】](#四：[windows设置与使用])

[五：【mac与linux】详细图文教程](#五：[mac与linux]详细图文教程)

[六：【电脑注意配合浏览器插件SwitchyOmega使用】](#六：[电脑注意配合浏览器插件SwitchyOmega使用])

[七：【iOS的QuantumultX】](#七：[iOS的QuantumultX])

[八：【疑难杂症解决】](#八：[疑难杂症解决])

[九：【客户端下载地址一览】](#九：[客户端下载地址一览])

[十：【clash导入问题解决】](#十：[clash导入问题解决])


---

# Clash简介

**clash非常好用，工作稳定，小bug小毛病很少。**

**便利性拔群，生成一个订阅链接就能各大平台通用。**

**【目前唯一的缺点】是需要出墙后才能确保订阅导入成功，否则经常失败 **

# 一：创建clash订阅链接

**1：打开网站**<https://bianyuan.xyz/>

**2：复制订阅。**

**粘贴到网站“订阅链接”那个框框。**

**你有其他订阅、线路的话，一行一个填地写。**

**3：其他选项默认。点生成订阅链接。他就会生成并复制订阅链接。【现在不推荐生成短链接容易失效】**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/486193ce45948ea7074ebb06a151ad2d.png)



# 二：【安卓设置与使用】

**1：开启白名单：设置 - 网络**

**访问控制模式 - 仅允许已选择的应用**

**访问控制应用列表 - 进去选定你需要FQ的应用**

**2：设置 - 覆写 - 模式 - 规则模式**

**3：导入订阅配置 - 新配置 - ULR - 命名随意，ulr框输入短链接 – 右上角按钮保存**

# 三：【iOS的Pharos Pro】

**复制好你生成的订阅链接。**

**打开小水滴 – 添加 – 手动输入 – Clash – 下载配置 – 名称随意，地址填订阅链接。**

**（点下载后弹出添加到收藏，随意整）**

# 四：【windows设置与使用】

**Profiles页 – 订阅链接填到输入框 - download - 点击卡片空白处选定使用**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/5cb4f91b8239916dcf919a85bd259595.png)

**代理模式设置：**

**Proxies页 - 点Rule。就可以了。**

**或者，托盘图标右键菜单 - Proxy Mode - Rule**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/8776b4d2eba01b4f08df39325704f4cf.png)

**最后General页 - 开启System Proxy按钮。**

**然后就能愉快上网了。**

**需要开机启动打开start with windows按钮。**

# 五：【mac与linux】详细图文教程

**原来clashr才是mac版。现在clash也有mac版了。**

[**https://github.com/Fndroid/clash_for_windows_pkg/releases**](https://github.com/Fndroid/clash_for_windows_pkg/releases)

**其他图文教程自己搜搜。这里随便贴一个http://suo.im/5SzxxK**

# 六：【【电脑注意配合浏览器插件SwitchyOmega使用】】

**原因：不像v2可以手改pac增减网站。clash的规则手改很麻烦。**

**遇见规则没有但需要出墙的网站，客户端手改全局的话用完还要改回去。麻烦。**

**【忘记改回去会浪费大量服务器流量】**

**我们需要一个快捷的 一键切换 手段。**

**SwitchyOmega进入选项**

**第一步，新建情景模式 - 代理服务器，命名Clash，创建 -
代理协议socks5代理服务器127.0.0.1代理端口7890 - 点击左下角应用选项**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/fe770bba427d75eebf9201555e734e69.png)

**第二步，界面 - 勾选快速切换 -
拖动系统代理和Clash到上面框框。点击左下角应用选项。**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/7cc05042d29593554a552a9287b173c6.png)

**插件设置就完成了。**

**点击插件图标就能一键切换规则代理/全局代理。**

**【使用解释】**

**平时使用系统代理（插件图标是黑色圈圈），由Clash规则判断走不走代理。**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/5c2b6f68fcb335ad95b77890414ecce0.png)

**点击一下插件图标后（图标圈圈会变色），就会切换到浏览器内全局走代理。**

**就能对付打不开的网站。**

**用完再点击就能切换回去。**

**ps：**

**下次想打开插件设置，可从插件的右键菜单 - 选项 进入。**

**如果你想方便的完全断开代理。在快速切换把“直接连接”也拖上去就行。**

**直接连接模式是灰色圈圈。**

**【关于clash自动更新】可有可无。**

**电脑在profiles页面，点线路的圈圈叹号**![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/e0dbd2ab416e4b774ef3c0d31bc5b9b3.png)**按钮。就能填刷新时间改名啥的。**

**安卓导入时你们会看到第三个框。让你填写个分钟数。随便填个1000啥的。**

**规则更新没那么频繁的。订阅了机场可以填每天更新。**

# 七：【iOS的QuantumultX】

**如果你没有Pharos Pro，那也可以整一个这个。**

**需要另外生成专用订阅链接。只有一步不同。**

**【那就是生成时需要修改客户端】其他生成步骤就都一样了。**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/6cac7aa50ec7c38ca49b9600343edb4c.png)

**【生成后的使用】**

**打开QuantumultX – 点右下角风车按钮 - 弹出页面拉下去，找到配置文件栏目，点下载
\- 输入短链接 – 确定 – 弹窗点好 – 右上角保存 – 回退出去点右上角总开关 –
输入iphone密码允许vpn**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/c4a1858486be25bcae3c134411312385.png)
![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/91ac567c8810ca562d717f39dcaba3cc.png)

# 八：【疑难杂症解决】

**重启软件大法 重启电脑大法 重装软件大法**

**复制线路、订阅地址时注意别多复制了空格**

**Q1：导入失败**

**A：【此问题有单独教程】简单方法是，先翻墙后再导入基本不会失败。**

**安装Qv2ray，v2rayNG，小火箭等先用。出墙后还想用clash再去导入。**

**Q2：系统代理按钮System Proxy无法开启/用着用着自动关闭**

**A：托盘右键Force
Quic退出Clash。从Clash快捷方式右键菜单以管理员身份运行。运行后开启System
Proxy，并开启开机自启动Start with
Windows。重启电脑。如果不行，重装clash再来。有问题查看Q3。**

**Q3：直接/卸载Clash后安装clash安装版安装失败？**

**A：【彻底卸载重装clash】卸载后，用everything搜clash，搜出来的基本可全删。**

**自己稍微注意分辨一下（回想自己的东西命名有没有clash字眼）。删除后重启电脑再安装。**

**Q4：本来是Rule模式（规则代理）在用。用着用着就变成了Global模式（全局代理）。**

**答：比较少见。具体原因不明。问题1那个解法走一个，再设回Rule。。出现比较少一般影响不大。【发生此问题时，一般会出现国内网站/软件网速变慢（如视频/信息加载慢）甚至不能打开等问题】**

# 九：【客户端下载地址一览】

**- 安卓Clash 下载universal版**

[**https://github.com/Kr328/ClashForAndroid/releases**](https://github.com/Kr328/ClashForAndroid/releases)

**- Windows与MAC**

[**https://github.com/Fndroid/clash_for_windows_pkg/releases**](https://github.com/Fndroid/clash_for_windows_pkg/releases)

**- iOS的Pharos Pro不会整问群友。一般是找淘宝代购/其他国家账号。**

**- linux**

[**https://github.com/Dreamacro/clash/releases**](https://github.com/Dreamacro/clash/releases)

# 十：【Clash导入问题解决】

**一：安装Qv2ray，v2rayNG，小火箭等先出墙。**

**出墙后还想用clash再去导入。**

**二： 电脑本机生成订阅，本地导入。**

**理论上不可能导入失败。**

**还失败肯定是你问题。尝试方法一吧。**

**【教程仅以windows最简操作为例】**

**【官方详细教程地址】**

**https://github.com/tindy2013/subconverter/blob/master/README-cn.md**

**1：下载后端程序并解压**

[**https://github.com/tindy2013/subconverter/releases**](https://github.com/tindy2013/subconverter/releases)

**一般下win64版。（建议解压在路径名称不带中文的目录。）**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/dc9fd8157914298a592c8eed7b34e8eb.png)

**2：双击运行subconverter.exe运行后别关窗口**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/9dc5b3c37246ce8b848bf38ff2528d55.png)

**3：打开一个订阅生成网站**

**比如**[**https://bianyuan.xyz/**](https://bianyuan.xyz/)

**然后把后端地址改为本地**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/a4cdafde3f38828199951bdeeaa651ad.png)

**然后就完成了。**

**后面的操作就是普通的订阅生成操作。**

**忘记了查看clash图文教程。**

**【注意】**

**每次导入/刷新配置文件时需要subconverter.exe正在运行**

**导入完成后**

**当前设备生成只能当前设备导入**

