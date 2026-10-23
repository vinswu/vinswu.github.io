# WindowsPC装机推荐

## 一、安装前的准备

#### 硬件：U盘、网络、备用电脑  
#### 软件：系统、PE、镜像刻录工具、解压缩工具、激活工具、运行库、驱动

##### 系统 下载
- Microsoft Windows 下载 https://www.microsoft.com/zh-cn/software-download
- MSDN,我告诉你 https://msdn.itellyou.cn/
- HelloWindows https://hellowindows.cn/
- List of files by Microsoft https://files.rg-adguard.net/
- 远景Windows论坛* https://bbs.pcbeta.com/

##### PE 下载
- IT天空-优启通 https://www.itsk.com/
- 系统总裁-U盘魔术师 https://www.sysceo.com/usm
- 微PE（原：通用PE） https://www.wepe.com.cn/ *其他推荐：[杏雨梨云启动维护系统](https://www.xyboot.com/)；[金狐系统维护盘](http://www.jinhu.me/)；[FirPE](https://firpe.cn/)*
- 无忧启动论坛* https://bbs.wuyou.net/

##### 镜像刻录工具 下载
- Ventoy* https://www.ventoy.net/
- Rufus* https://rufus.ie/zh/
- balenaEtcher https://etcher.balena.io/
- UltraISO软碟通* https://cn.ezbsystems.com/ultraiso/download.htm  
> UltraISO软碟通 简体中文版 注册信息  

| 注册名  | 注册码 |
| :--- | :--- |
| Guanjiu | A06C-83A7-701D-6CFC |
| 累累 | 4EE9-A156-B015-A70E |
| 李明 | 509F-BA54-BBA6-73C5 |
| 王涛 | 7C81-1689-4046-626F |

##### 解压缩&文件校验工具 下载
- 7-zip* https://www.7-zip.org/
- WinRAR https://www.rarlab.com/
- Hash https://keir.net/hash.html
- OpenHashTab 插件 https://github.com/namazso/OpenHashTab
- HashCheck Shell Extension 插件 https://code.kliu.org/hashcheck/

#### 激活工具 下载
- Microsoft Activation Scripts (MAS)* https://github.com/massgravel/Microsoft-Activation-Scripts
- 知彼而知己HEU_KMS_Activator https://github.com/zbezj/HEU_KMS_Activator

##### 运行库 下载
- VC++
  - 微软官网  https://learn.microsoft.com/zh-cn/cpp/windows/latest-supported-vc-redist
  - VisualCppRedist AIO* https://github.com/abbodi1406/vcredist
  - 微软常用运行库合集-果壳剥壳 https://www.ghxi.com/yxkhj.html
  - 微软常用运行库合集-Dreamcast http://dreamcast2.ysepan.com/
  - Game Runtime Libraries Package* (GRLPackage-mefcl) https://www.mefcl.com/srlpackage.html
 
- .NET
  - 微软官网 https://dotnet.microsoft.com/zh-cn/download/dotnet
  - Microsoft .NET Framework 修复工具 https://support.microsoft.com/zh-cn/topic/microsoft-net-framework-修复工具可用-942a01e3-5b8b-7abb-c166-c34a2f4b612a
  - 微软.NET运行库合集-果壳剥壳 https://www.ghxi.com/nethj.html

- DirectX
  - DirectX修复工具 https://blog.csdn.net/VBcom/article/details/6962388

- Flash 请放弃吧
  - Clean Flash Player https://github.com/darktohka/clean-flash-builds
  - Adobe Flash Player https://www.flash.cn/

- JDK
  - Java Development Kit* https://www.oracle.com/java/technologies/downloads/
> 拓展：[《Windows常用运行库（VC++、DirectX、.NET）》](https://blog.csdn.net/cbing2002/article/details/121263687)  
> 拓展：[《windows 10 配置Java 环境变量》](https://www.jianshu.com/p/9fc41ea941aa)

#### 驱动 下载
- 对应硬件官网的技术支持服务中心下载*
  - 笔记本：[联想](https://newsupport.lenovo.com.cn/driveDownloads_index.html)；[惠普](https://support.hp.com/cn-zh/drivers)；[戴尔](https://www.dell.com/support/home/zh-cn)……
  - 组装机（主板）：[华硕](https://www.asus.com.cn/support/download-center/)；[微星](https://www.msi.cn/support/download)；[技嘉](https://www.gigabyte.cn/Support/Consumer/Download)……
  - 显卡：[英伟达](https://www.nvidia.cn/drivers/)；[AMD](https://www.amd.com/zh-cn/support/download/drivers.html)；[英特尔](https://www.intel.cn/content/www/cn/zh/download-center/home.html)
  - 外设：[罗技](https://support.logi.com/hc/zh-cn)；[雷蛇](https://mysupport-chsi.razer.com/app/home)；[樱桃](https://www.cherry.cn/software.html)；[双飞燕](http://www.a4tech.cn/download.aspx)
- Snappy Driver Installer Origin (SDIO)* https://www.glenn.delahoy.com/snappy-driver-installer-origin/
- 联想驱动管理 https://newsupport.lenovo.com.cn/driveDownloads_index.html
- 360驱动大师* https://dm.weishi.360.cn/home.html
- IT天空-万能驱动 https://www.itsk.com/
- 系统总裁-驱动总裁 https://www.sysceo.com/dc

## 二、制作PE启动盘

#### [PE 下载](https://github.com/vinswu/notes?tab=readme-ov-file#pe-下载)
> 拓展：[无忧启动论坛](http://bbs.wuyou.net/forum.php)  

#### PE 制作（提前准备的U盘、PE、镜像刻录工具UltraISO）
> 拓展：[《微pe工具箱+软碟通 制作 U盘启动盘》](https://blog.csdn.net/yong53jun/article/details/118408973)  
> 拓展：[《ultraiso制作u盘启动盘教程图文详解纯净-U盘启动教程》](https://blog.csdn.net/qufuxiaozi/article/details/80124887)  
> 拓展：[《Windows 重装系统-U盘启动盘制作及启动》](https://blog.csdn.net/m0_55483902/article/details/123496575)

#### U盘启动进PE
> 拓展：[《如何用U盘启动电脑(系统U盘使用最重要的步骤)》](https://zhuanlan.zhihu.com/p/81344150)

## 三、进WindowsPE，部署安装系统

#### 快速分区：[DiskGenius](https://www.diskgenius.com/)（原PartitionGuru）
> 拓展：[《DiskGenius软件帮助》](https://www.diskgenius.cn/help/)

###### 分区表类型选择
- Windows7 及以下，MBR格式，Legacy启动模式
- Windows8 及以上，GUID（GPT）格式，UEFI启动模式
> 拓展：[《BIOS中的UEFI和Legacy启动模式》](https://blog.csdn.net/z15732621736/article/details/49048779)  
> 拓展：[《硬盘分区表格式GUID和MBR知识普及》](https://blog.csdn.net/z15732621736/article/details/49046367)

###### 4K对齐
- [勾选] 对齐分区到此扇区数的整数倍：[固态硬盘选4096扇区/机械硬盘2048扇区]
> 拓展：[《分区4K对齐那些事，你想知道的都在这里》](https://diskgenius.cn/exp/about-4k-alignment.php)

#### 系统安装：[WinNTSetup](https://msfn.org/board/topic/149612-winntsetup)

###### 选择包含Windows安装文件的文件夹
- 选 X:\sources\install.wim

###### 选择引导驱动器 （右侧三盏灯，绿灯、黄灯均为正常，若亮红灯说明选择引导驱动器磁盘选择错误）
- 选 C盘 或 引导盘

###### 安装磁盘的位置
- 选 C盘

###### 开始安装
- 引导扇区 [使用bootsect.exe 更新引导代码] [ALL]
- 关机：[勾选]安装成功后自动重新启动计算机

## 四、进入Windows系统，激活优化系统并安装必要程序

#### 开启Administrator账户
> 拓展：[《Win10怎么开启Administrator超级管理员账户》](https://answers.microsoft.com/zh-hans/windows/forum/all/win10%E6%80%8E%E4%B9%88%E5%BC%80%E5%90%AFadministr/b7576403-c6dc-4fe1-b55a-3803f8fae320)

#### [激活](https://github.com/vinswu/notes?tab=readme-ov-file#激活工具-下载)系统

#### 安装[运行库](https://github.com/vinswu/notes?tab=readme-ov-file#运行库-下载)

#### 安装[驱动](https://github.com/vinswu/notes?tab=readme-ov-file#驱动-下载)

## 五、Windows装机软件精选 - 使用开源软件！支持开源软件！

#### 系统维护辅助工具
- 微软电脑管家 https://pcmanager.microsoft.com/zh-CN
- PowerToys https://github.com/microsoft/PowerToys
- 360杀毒 https://sd.360.cn/  *用户基数大；容易全家桶*
- 360安全卫士 https://weishi.360.cn/ *用户基数大；建议下载使用“[360安全卫视极速版](https://weishi.360.cn/jisu/)”*
- 火绒安全* https://www.huorong.cn/ 搭配：[火绒应用商店](https://www.huorong.cn/app_store.html)  *其他：[腾讯电脑管家](https://guanjia.qq.com/ "从3Q大战后，到出火绒前，我一直用它")*
- Dism++ https://github.com/Chuyu-Team/Dism-Multi-language/releases *系统优化*
- ZyperWin++ https://github.com/ZyperWave/ZyperWinOptimize *系统优化*
- optimizerDuck https://github.com/itsfatduck/optimizerDuck *系统优化*
- Windows10Debloater https://github.com/Sycnex/Windows10Debloater *系统优化*
- Win11Debloat https://github.com/Raphire/Win11Debloat *系统优化*
- WPD* https://wpd.app/ *系统优化*
- PyDebloatX* https://github.com/Teraskull/PyDebloatX *卸载预装应用*
- CCleaner https://www.ccleaner.com/zh-cn *垃圾清理*
- FluentCleaner https://github.com/builtbybel/FluentCleaner
- Geek Uninstaller https://geekuninstaller.com/ *软件卸载*
- Bulk Crap Uninstaller https://github.com/BCUninstaller/Bulk-Crap-Uninstaller
- ContextMenuManager* https://github.com/BluePointLilac/ContextMenuManager *右键菜单管理*
- MyComputerManager* https://github.com/1357310795/MyComputerManager *此电脑内快捷方式管理*
- DriveIconManager https://github.com/Return-Log/Drive-Icon-Manager *网盘图标删除器*
- 图吧工具箱 https://www.tbtool.cn/

#### 解压缩&文件校验工具
- 7-zip* https://www.7-zip.org/
- WinRAR https://www.rarlab.com/ *[国内代理商](https://www.winrar.com.cn/)，从5.40版本之后，开始免费，但加入了广告*
- Hash https://keir.net/hash.html
- HashCheck Shell Extension 插件 https://code.kliu.org/hashcheck/

#### 输入法
- Microsoft 拼音/五笔 https://support.microsoft.com/zh-cn/windows/hardware/input-devices/microsoft-simplified-chinese-ime *系统自带*
- 小狼毫Weasel* https://rime.im/ *搭配：[雾凇拼音方案](https://github.com/iDvel/rime-ice)、[万象拼音方案](https://github.com/amzxyz/rime-wanxiang)* *了解：[Rime坊](https://rime.yougaoji.com/)*
- 自然码 https://www.ziranma.com.cn/ *推荐：[Rime+魔然（魔改自然码）](https://github.com/rimeinn/rime-moran)；或：[手心输入法+ZRM_Aux-code（自然码码表）](https://github.com/copperay/ZRM_Aux-code)*  
- 小小输入法 https://yong.dgod.net/ *永码:一个双拼加形类的编码方案，双拼部分采用自然码双拼方案，辅助码* 
- 小鹤音形输入法 https://flypy.cc/ *生态好*
- 极点五笔输入法 http://www.freewb.org/ *老牌.五笔拼音混合输入法*
- 华宇拼音输入法 https://pinyin.thunisoft.com/ *老牌。最早的智能拼音输入法*
- 逍遥笔手写输入法 http://shurufa.ihanzi.cn/
- 搜狗输入法* https://shurufa.sogou.com/  *用户基数大；臃肿，有广告。可尝试用“[QQ输入法](https://qq.pinyin.cn/)”替代。另，“[手心输入法*](https://www.xinshuru.com/)也值得一试”*
- 百度输入法 https://srf.baidu.com/
- 讯飞输入法 https://srf.xunfei.cn/
- 豆包输入法 https://shurufa.doubao.com/pc

#### 浏览器
- Mozilla Firefox* https://www.mozilla.org/zh-CN/firefox/browsers/
- Tor Browser[H] https://www.torproject.org/zh-CN/download/
- Chromium https://www.chromium.org/chromium-projects/
- Google Chrome*[H] https://www.google.com/chrome/
- Microsoft Edge https://www.microsoft.com/zh-cn/edge *Windows自带*

#### 浏览器插件
- uBlock Origin* https://ublockorigin.com/ *广告拦截。商业软件推荐：[AdGuard*](https://adguard.com/ "浏览器插件免费")*
- Bitwarden* https://bitwarden.com/ *密码管理*
- Ruffle https://ruffle.rs/ *flash播放器*
- IEability https://ieability.com/ *ie兼容模式*

#### [科学上网工具](https://github.com/vinswu/notes/blob/master/Agent.md)
- v2rayN* https://github.com/2dust/v2rayN
- Clash Verge* https://github.com/clash-verge-rev/clash-verge-rev

#### 网络传输工具
- LocalSend https://localsend.org/
- Gopeed https://github.com/GopeedLab/gopeed
- Motrix https://github.com/agalwood/Motrix
- eMule(电骡) http://emule-project.net
- qBittorrent https://www.qbittorrent.org/
- 迅雷* https://www.xunlei.com/  *用户基数大；但有广告。可以试试“迅雷精简版”无账号体系*
- 百度网盘 https://pan.baidu.com/ *用户基数大；下载龟速*
- 中国移动云盘 https://yun.139.com/
- Dropbox https://www.dropbox.com/
- 坚果云 https://www.jianguoyun.com/
- Internet Download Manager https://www.internetdownloadmanager.com/

#### 聊天工具
- Telegram[H] https://telegram.org/ *语言包:[简体中文](https://t.me/setlanguage/zh-hans-raw)*
- QQ https://im.qq.com/ *追求轻量化的，可以试试“[TIM](https://office.qq.com/)”，希望不要步“TM”的后尘*
- 微信 https://weixin.qq.com/
- 腾讯会议 https://meeting.tencent.com/

#### 远程控制软件
- RustDesk https://rustdesk.com/zh-cn/
- BilldDesk https://desk.hsslive.cn/
- 向日葵远程控制 https://sunlogin.oray.com/ *用户基数大*
- 网易UU远程 https://uuyc.163.com/

#### OA办公自动化
- 企业微信 https://work.weixin.qq.com/
- 钉钉 https://www.dingtalk.com/
- 飞书 https://www.feishu.cn/

#### 办公基础套件
- Microsoft Office 部署工具(ODT) https://learn.microsoft.com/zh-cn/officeupdates/odt-release-history
> 安装 [Office Tool Plus](https://otp.landian.vip/zh-cn/) | [LKY Office Tools](https://github.com/OdysseusYuan/LKY_OfficeTools)  
> 激活 [Ohook](https://github.com/asdcorp/ohook)  
> 插件 [OfficePLUS](https://www.officeplus.cn/addin/OPCN/)  
> 插件 [不坑盒子](https://bukenghezi.com/)  
> 插件 [小恐龙公文排版助手](https://xkonglong.com)  
> 插件 [OneKeyTools](http://oktools.xyz/)  
> 插件 [iSlide](https://www.islide.cc/)  
> 插件 [方方格子](http://www.ffcell.com/)  
> [常用办公字体](https://vinswu.lanzoue.com/b0e50lpde "密码:1024")  
- Adobe Acrobat* https://www.adobe.com/
> 更新 [Acrobat Enterprise Release Notes](https://www.adobe.com/devnet-docs/acrobatetk/tools/ReleaseNotesDC/index.html)  
> 破解 [@vposy](https://weibo.com/vposy "2023年8月11日起暂停更新") | [@m0nkrus](http://www.monkrus.ws) | [@KpoJIuK](https://repack.me/)  
> 补丁 [AMTEmu v0.9.2](https://cn.bing.com/search?q=AMTEmu+v0.9.2 "支持2017之前") | [GenP v3.8.0 - CGP](https://gen.paramore.su/ "支持2019-2026")   
> 插件 [WebPShop](https://helpx.adobe.com/cn/photoshop/kb/support-webp-image-format.html "在Photoshop中使用WebP文件")  
- WPS Office https://www.wps.cn/
- WPS PDF https://www.wpspdf.cn/
- LibreOffice* https://www.libreoffice.org/ *不联网，纯本地*
- OnlyOffice https://www.onlyoffice.com/
- PDFgear* https://www.pdfgear.com/zh/
- PDF24 Creator https://tools.pdf24.org/zh/
- PDF 补丁丁（PDFPatcher） https://github.com/wmjordan/PDFPatcher
- 数科OFD https://www.ofd.cn/

#### 办公增强工具
- 万彩办公大师 http://www.wofficebox.com/ *停更，最后版本3.1.2*
- Notepad++* https://github.com/notepad-plus-plus/notepad-plus-plus *替代记事本*
- Qalculate!* https://github.com/Qalculate/libqalculate *替代计算器*
> [Classic Apps](https://win7games.com/)

#### 笔记清单/思维导图
- 日历清单（原：桌面日历） https://www.xdiarys.com/
- OneNote https://www.onenote.com/
- Notion https://www.notion.so/zh-cn
- Xmind https://www.xmind.cn/
- MarkText https://www.marktexts.com.cn/
- Obsidian https://obsidian.md/zh/
- Joplin https://joplinapp.org/cn/
- 幕布 https://mubu.com/home
- Effie https://www.effie.co/

#### 电子书阅读器
- calibre https://calibre-ebook.com
- Koodo Reader* https://www.koodoreader.com/
- Sumatra PDF https://www.sumatrapdfreader.org/free-pdf-reader

#### 看图
- Honeyview* https://cn.bandisoft.com/honeyview/ *停更，最后版本5.53*
- ImageGlass https://imageglass.org/
- IrfanView* https://www.irfanview.com/
- FastStone Image Viewer  https://www.faststone.org/
- XnView Shell Extension 插件 https://www.xnview.com/en/xnshell/ *右键图片预览、格式转换、调整大小、等*
- FastPreview* 插件 https://github.com/nmaier/fastpreview *右键图片预览*

#### 截图/gif动图录屏
- QQ截图*
- Snipaste* https://www.snipaste.com/
- PixPin https://pixpin.cn/
- ScreenToGif https://www.screentogif.com/
- FastStone Capture https://www.faststone.org/

#### 修图
- Adobe Photoshop* https://www.adobe.com/
- GIMP https://www.gimp.org/
- 美图秀秀 https://pc.meitu.com/

#### 听音乐
- VLC Media Player* https://www.videolan.org/vlc/
- AIMP* https://www.aimp.ru/
- foobar2000 https://www.foobar2000.org/

#### 音乐编辑
- Mp3tag https://www.mp3tag.de/ *音乐标签编辑*
- Exact Audio Copy https://exactaudiocopy.de/ *音轨抓取*
- Medieval CUE Splitter http://www.medieval.it/ *音轨切割*
- Sound Organizer https://www.sonystyle.com.cn/minisite/cross/app/sound_organizer.htm

#### 看视频
- VLC Media Player* https://www.videolan.org/vlc/
- MPV* https://github.com/mpv-player/mpv
- QQ影音 https://player.qq.com/
- Potplayer* https://potplayer.tv/
- Kodi https://kodi.tv/download/
- Emby https://emby.media/
> Potplayer插件 [LAVFilters](https://github.com/Nevcairiel/LAVFilters)

#### 视频录制
- QQ截图*-屏幕录制
- Captura* https://github.com/MathewSachin/Captura
- OBS https://obsproject.com/zh-cn
- oCam* https://ohsoft.net/
> 注册 [@大眼仔~旭](https://www.dayanzai.me/ocam.html)

#### 视频剪辑
- Adobe Premiere Pro* https://www.adobe.com/
- Kdenlive https://kdenlive.org/
- Shotcut https://www.shotcut.org/
- HandBrake https://handbrake.fr/
- 剪映 https://www.capcut.cn/

#### 个性化
- Fliqlo https://fliqlo.com/ *时钟屏保*
- FlipIt* https://github.com/phaselden/FlipIt/releases *时钟屏保*
- f.lux https://justgetflux.com/ *护眼*
- noMeiryoUI https://github.com/Tatsu-syo/noMeiryoUI/releases *Windows系统字体修改*

#### 小工具
- Flow.Launcher https://github.com/Flow-Launcher/Flow.Launcher *效率神器，集成[Everything*](https://www.voidtools.com/) SDK*
- PdfInvoiceMerge https://github.com/hetaoos/PdfInvoiceMerge *PDF发票合并*
- 增值税电子发票阅读器* https://inv-veri.chinatax.gov.cn/xgxz.html
- 全国资格考试网报平台证件照片审核处理系统 http://www.cpta.com.cn/tooldown.html

## 外链（按首字母排序）
| [HapNext](https://hapnext.cn/)
| [sysin](https://sysin.org/)
| [zd423](https://www.423down.com/)
| [大眼仔~旭](https://www.dayanzai.me/)
| [果壳剥壳](https://www.ghxi.com/)
| [开源大世界](https://kydsj.vip/doku.php?id=wiki:网站目录)
| [软仓](https://www.ruancang.net/)
| [宋永志博客](http://www.songyongzhi.com/)
| [下1个好软件](https://xiaoyi.vc/win-app)
| [小众软件](https://www.appinn.com/)
| [异次元软件世界](https://www.iplaysoft.com/)
