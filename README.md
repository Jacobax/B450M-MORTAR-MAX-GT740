# OpenCore 6.9  
![截屏2021-05-05 07 19 30](https://user-images.githubusercontent.com/23228895/117162608-82eb8d00-adf5-11eb-9d2e-eebbb6d2f0c4.png)  
# 实践安装：big sur 11.3.1  
# 安装方式：联网恢复安装  
# 详细配置  
主板：B450M MORTAR MAX  
CPU：R5 3600  
显卡：GT740  
网卡：板载  
声卡：板载  
~~机型信息为MacPro7,1~~已修改机型及三码，iMac20,1，三码建议自行修改
# 已知问题  
1. ~~不识别我的nvme，海力士pc711，折衷安装到旧sata固态~~貌似是pc711的锅，装黑苹果尽量不别选oem盘  
2. ~~开机提示安装内存超出最大支持，网上有说是MacPro7,1的锅，不影响使用，但建议修改~~修改机型及三码后已不提示（建议iMacPro1,1）
3. ~~不能登录apple id及使用相关功能~~ 可登录商店, iMessage和iCloud目前来看登陆不了  

efi制作知识来源主要为opencore官方文档及网上各位大佬的教程，在此作不点名地图炮感谢  

# 推荐网址  
[OpenCore安装指南](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites)  
[config.plist文件检验排错](https://opencore.slowgeek.com/)  

# 注意：BIOS设置above 4G项后网卡不能工作，建议关闭
