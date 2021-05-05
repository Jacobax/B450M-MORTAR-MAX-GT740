# OpenCore 6.9  
![截屏2021-05-05 07 19 30](https://user-images.githubusercontent.com/23228895/117162608-82eb8d00-adf5-11eb-9d2e-eebbb6d2f0c4.png)  
# 实践安装：big sur 11.3.1  
# 安装方式：联网恢复安装  
# 详细配置  
主板：B450M  
CPU：R5 3600  
显卡：GT740  
网卡：板载  
声卡：板载  
机型信息为MacPro7,1  
# 已知问题  
1. 不识别我的nvme，海力士pc711，折中安装到旧sata固态  
2. 开机提示安装内存超出最大支持，网上说有是MacPro7,1的锅，不影响使用  
3. 不能登录apple id及使用相关功能  

本人黑苹果新人，efi制作知识来源主要为opencore官方文档及网上各位大佬的教程，在此不点名感谢  

# 注意：BIOS设置above 4G项后网卡不能工作，建议关闭
