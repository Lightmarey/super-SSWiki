![越过长城，走向世界](https://cdn.laod.wang/wp-content/uploads/2018/09/cc.gif)

> ##  越过长城，走向世界
## 你首先要有台海外服务器。
###  众所周知，高墙之外，是更明媚的风光。

####  这是一篇关于科学上网的文章，专门介绍如何跨越这座长城。

**声明：本文基于参考而来，按[反996icu License来许可](https://github.com/996icu/996.ICU/blob/master/LICENSE)，仅作学习交流之用，本人不对其内容及可能造成的任何后果承担责任。**

**本文可随意转载、复制、粘贴，并请务必不要注明原作者和来源。**

 

*新手的科学上网指南：**V2ray篇***

(切记：现在防火长城已经有封锁Shadowsocks的方法)

> 外：《奇虎 360 研究员披露 Shadowsocks 流密码重定向攻击》 奇虎 360 的一位安全研究员披露了流行 SOCKS5 代理 Shadowsocks 的流密码重定向攻击漏洞。流密码是一种对称加密算法，加密和解密双方使用相同伪随机加密数据流作为密钥，明文数据每次与密钥数据流顺次对应加密，得到密文数据流。流行的流密码算法包括 ChaCha、RC4、A5/1、A5/2、Chameleon、FISH、Helix 等。研究人员发现 Shadowsocks 协议存在漏洞，会破坏流密码的保密性。利用重定向攻击被动攻击者可以轻松解密所有 Shadowsocks 的加密数据包。中间人攻击者还能实时修改流量，就好像加密根本不存在。受影响的版本包括 shadowsocks-py、shadowsocoks-go 和 shadowsocoks-nodejs，shadowsocks-libev 和 go-shadowsocks2 不受影响，研究人员还建议使用 AEAD 加密算法。漏洞是在 2018 年 12 月发现的，2019 年 3 月发布了概念 | https://www.solidot.org/story?sid=63529

> 外2：https://blog.dun.im/anonymous/gfw-report-shadowsocks.html
>
> 关于Shadowsocks的探测

> 外3:![](https://hello.2heng.xin/system/media_attachments/files/000/009/747/original/77a5d8a8ee15a099.jpg?1579931700)

> 外4:![](https://hello.2heng.xin/system/media_attachments/files/000/015/208/original/f3fbb9cc8df5680d.png?1581744576)



> ##### 所以这里不会再有ShadowSocks的搭建。。



V2ray篇

 

自行百度下载xshell

安装 ，打开软件。

点击 “文件” → “新建” → “连接”，输入 “名称” 和 “主机” （即VPS的ip）。

 

![img](https://i.loli.net/2020/02/15/SCuQGyqWo9r1UYk.jpg) 

点击 “用户身份验证”，输入用户名（默认root）和密码。确认。

 

![img](https://i.loli.net/2020/02/15/O5KtjoZ3zniafXV.jpg) 

连接 VPS，接受并保存密匙。

 

![img](https://i.loli.net/2020/02/15/eULVS7Kn1OhdDFv.jpg) 

 

![img](https://i.loli.net/2020/02/15/d7jeZgIJqaGKu2y.jpg) 

出现 root@vultr:~# 即连接成功。

 

![img](https://i.loli.net/2020/02/15/I1k7zqD26CaAfos.jpg) 

 

然后复制粘贴：

## wget -N --no-check-certificate https://raw.githubusercontent.com/q779433467/v2ray.fun/master/install.sh && bash install.sh

等待片刻
### 然后会请你设置用户名，密码，网页面板的端口号
### 设置完毕，请在浏览器打开：账户:密码@VPS的ip:端口号
### 进行一些简短的设置，然后就可以连接了
> 注意：由于IP探测已经失灵，可能需要手动更新IP。（对于快照来讲）

