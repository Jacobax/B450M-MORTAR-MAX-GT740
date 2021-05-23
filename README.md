# OpenCore 6.9  
![OC_Rog](https://user-images.githubusercontent.com/23228895/118050239-78ab2f00-b3b1-11eb-849c-84041f93d730.png)
![截屏2021-05-05 07 19 30](https://user-images.githubusercontent.com/23228895/117162608-82eb8d00-adf5-11eb-9d2e-eebbb6d2f0c4.png)
<img width="1027" alt="截屏2021-05-24 00 52 02" src="https://user-images.githubusercontent.com/23228895/119269620-342e5780-bc2b-11eb-9d51-740ac98e5c6b.png">
![截屏2021-05-24 上午12 11 00](https://user-images.githubusercontent.com/23228895/119269631-3abccf00-bc2b-11eb-94e7-9b49ceada1ec.png)


# 实践安装：big sur 11.3.1  
# 安装方式：联网恢复安装  
# 详细配置  
主板：B450M MORTAR MAX  
CPU：R5 3600  
显卡：GT740  
网卡：板载  
声卡：板载  
~~机型信息为MacPro7,1~~机型及三码建议自行修改, 如iMac Pro1,1
# 已知问题  
1. ~~不识别我的nvme，海力士pc711，折衷安装到旧sata固态~~pc711的锅，装黑苹果尽量别选oem盘  
2. ~~开机提示安装内存超出最大支持，网上有说是MacPro7,1的锅，不影响使用，但建议修改~~修改机型及三码后已不提示（建议iMacPro1,1）
3. ~~不能登录apple id及使用相关功能~~ 新号可登录商店, 其它iCloud和iMessage等iservice可参考[这里](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)解决, 用不上或懒得弄可忽略, 不影响macOS使用

# 推荐网址  
[OpenCore安装指南](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites), 非常全面，有英语功底的建议看一遍  
[config.plist文件检验排错](https://opencore.slowgeek.com/)，如果有macos环境，建议用opencore configrator检验功能

# 鸣谢
efi制作知识来源主要为opencore官方文档及网上各位大佬的教程，在此作不点名地图炮感谢  
[Rog主题来源](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1883324&highlight=%D6%F7%CC%E2) 感谢大佬的制作  

# 注意：这块主板BIOS设置above 4G项后网卡不能工作，建议关闭
