
# Jlink_DIY
 * 个人DIY JLINK V9  高速SWD速度可达12000kHz
成品TB Link:[迷你JLink V9](https://item.taobao.com/item.htm?spm=a1z09.8149145.0.0.44cb53cdwAegGF&id=604502683248&_u=6kjj8627ebc)
* 推荐高速DAPLink&脱机烧录器：[高速DAP](https://item.taobao.com/item.htm?spm=a230r.1.14.40.7f906f07LiXFzK&id=610773587113)
*  串口波特率最高只支持**230400**
* DFU下载固件时需要将BOOT0短接3.3V同时RX引脚短接GND即可进入DFU模式
* 也可以用SWD接口直接把bootloader下载进去然后打开jlink commander 即可自动升级固件
* 如果提示了没license 就打开jlink commander 输入以下的sn  喜欢什么版本就输入什么sn
*  Exec SetSN=20281318    V9.2
*  Exec SetSN=20381318    V9.3
*  Exec SetSN=20481318    V9.4
*  Exec SetSN=20581318    V9.5
*  Exec SetSN=20681318    V9.6
*  Exec SetSN=20781318    V9.7
* 新版本的Jlink驱动要多加点内容，例如
* exec SetSN=20781318,0xCF2EF286

# Pic:<br> 
<img src="https://github.com/Kevincoooool/KS_Diy_Link/blob/master/pic/link_1.jpg" height="600px" width="804px" title="反面" style="display:inherit;"/> <br> 
<img src="https://github.com/Kevincoooool/KS_Diy_Link/blob/master/pic/link_2.jpg" height="600px" width="804px" title="正面" style="display:inherit;"/> <br> 
<img src="https://github.com/Kevincoooool/KS_Diy_Link/blob/master/pic/link_3.jpg" height="600px" width="804px" title="PCB" style="display:inherit;"/> <br>

> 另外强调一下，本仓库的项目是**GPL协议**，不支持任何形式的私自产品化（当然大家自己DIY是没有任何问题的，这里只是防止有人借我的名义坑大家）
