**【只有WS-CDN后缀的线路可以使用CND】**

**【推荐电脑使用，虽然安卓也可以但麻烦】**

**原教程**

[**https://github.com/mack-a/v2ray-agent/blob/master/documents/optimize_V2Ray.md**](https://github.com/mack-a/v2ray-agent/blob/master/documents/optimize_V2Ray.md)

**【这里教程仅以电脑为例】**

**1：下载ip优选工具**

[**https://github.com/XIU2/CloudflareSpeedTest/releases**](https://github.com/XIU2/CloudflareSpeedTest/releases)

**或者网盘下载**

**[https://wwa.lanzous.com/b0dwngrmj](https://wwa.lanzous.com/b0dwngrmj)**

**密码:6666**

**安卓运行教程**

[**https://github.com/XIU2/CloudflareSpeedTest/discussions/61**](https://github.com/XIU2/CloudflareSpeedTest/discussions/61)

**下载windows版解压**

**运行CloudflareST.exe**

**然后等待它自动跑完。**

**完成后它会从好到坏列出20个ip**

**这就是所谓的优选ip**

**2：右键WS-CDN线路，编辑**

**复制一个优选ip把主机/地址/address改为优选ip**

**伪装host和sni需要是线路本身的域名。别改。**

**【保存就可以使用了】可以说非常简单。**

**【注意】使用的话SNI选项别留空要，填写线路本身的域名**

![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/9e52db9bf2cc121e9cd6398ba1767d2d.png)![](https://raw.githubusercontent.com/DLGum/pic-bed/main/pic/74c24fe1d067cf3d057ef19906ff2ec3.png)
