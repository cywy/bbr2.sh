# bbr2.sh

建议系统 Debian 10 x86_64，理论支持Debian 8+, Ubuntu 16.04+  
仅适用于64位(x86_64)系统，不支持x86，不支持CentOS及其他系统。  
已在搬瓦工 Debian 8 9 10 , Ubuntu 16.04 18.04 中测试通过 (Ubuntu 14.04 失败)  
已在以下商家的Debian 10系统中测试通过：Oracle Public Cloud, DMIT, OLVPS, AlibabaCloud  
安装成功率100%  
    
一般用法:  
wget --no-check-certificate -q -O bbr2.sh "https://github.com/yeyingorg/bbr2.sh/raw/master/bbr2.sh" && chmod +x bbr2.sh && bash bbr2.sh  
既然称得上是一键安装脚本，当然要有......  
真·一键安装:  
wget --no-check-certificate -q -O bbr2.sh "https://github.com/yeyingorg/bbr2.sh/raw/master/bbr2.sh" && chmod +x bbr2.sh && bash bbr2.sh auto  
安装内核后自动重启，重启后自动安装BBR2和开启ECN。
