# ASUS P8B75-V 添加 M.2(NVMe) SSD

今天（2017-10-14）跟大家分享一下
我通过刷华硕 P8B75-V PC主板 BIOS 来使该主板支持M.2接口（NVMe协议）SSD的方法
文中不涉及安装新系统的内容，请各位看官自行百度

# 所需要的武器和设备

> AI_Suitell 
>> PS：华硕主板的驱动光盘里面有,如果你找不到光盘就乖乖 [点我下载](https://share.weiyun.com/ec0ccdf3380cadb7241e420d2060d572 "点击下载AI_Suitell") 吧
> 
> 华硕官方最新BIOS 
>> PS:华硕官方最新BIOS P8B75-V-ASUS-1608 [点我下载](https://share.weiyun.com/ec0ccdf3380cadb7241e420d2060d572"点击下载官方最新BIOS") 吧
> 
> 支持 M.2接口(NVMe协议)SSD的BIOS 
>> PS：基于华硕官方BIOS修改而来 [点我下载](https://share.weiyun.com/ec0ccdf3380cadb7241e420d2060d572"点击下载官方最新BIOS") 吧
> 
> 一张 M.2接口(NVMe协议)SSD
>> PS：我的这张卡是笔记本升级时淘汰下来的
> 
> 一块 M.2接口(NVMe协议) PCIe转接卡
>> 附购买链接：[购买链接](http://zmnxbc.com/s/qfgsf?tm=38c34c"点击下载官方最新BIOS")
> 
> 主角：你准备日的PC机

# 日BIOS步骤

> 安装 AI_Suitell 软件，双击 "Setup" 进行安装，只需要勾选ASUS Update，安装完成后根据提示重启电脑
> 
> 重启后运行的 AI_Suitell 软件，点击"更新软件"选项卡，选择 ASUS Update
> 
> 选择"从文件升级BIOS"，点下一步，找到解压的文件夹(华硕官方最新BIOS)中的 P8B75-V-ASUS-1608.CAP
> 
> 以下的内容请按步骤操作
>> BIOS更新程序要先检查一下.CAP文件，当软件界面右下角出现"下一步"按钮时先不要点。
>> 
>> 我们得先做另外一件事
>> 
>> 将文件夹（支持 M.2接口(NVMe协议)SSD的BIOS）中的 P8B75-V-ASUS-1608.CAP 拷贝到文件夹（华硕官方最新BIOS）中并覆盖
>> 
>> 然后回到 ASUS Update 软件，这时再点击"下一步"按钮
>> 
>> 紧接着软件会问你是否想要变更BIOS标志（就是开机看到的ASUS logo或者自己设置一张图片来显示，各位客官根据口味不同随意吧）
>> 
>> 然后你就看到"升级"按钮啦，点它一下你就可以一边喝茶一边等着BIOS更新完成了

# 更改BIOS从SSD启动系统

> 重启PC机进入BIOS > 高级模式 > 启动 > CSM(兼容性支持模块)
> 
> 开启 CSM -> Enabled
> 
> 启动设备控制 -> 仅 UEFI
> 
> 从 PCIe/PCI 扩展设备启动 -> UEFI 驱动设备优先
> 
> 我的BIOS是这样设置的，然后F10 保存变更选"是"自动重启啦~
> 
> 最后呢
> 
> 如果你装了系统就直接从SSD启动系统了
> 
> 如果你还没装系统就先去给SSD装个系统吧
> 
> 分享完毕，再见~~~
