# Jlink_DIY
 个人DIY JLINK V9  高速SWD速度可达12000kHz
成品TB链接：https://item.taobao.com/item.htm?spm=a1z09.8149145.0.0.44cb53cdwAegGF&id=604502683248&_u=6kjj8627ebc

#  串口波特率最高只支持**230400**
* DFU下载固件时需要将BOOT0短接3.3  RX引脚短接GND即可进入DFU模式
* 也可以用SWD接口直接把bootloader下载进去 打开jlink commander
#  进入DFU模式后刷入bootloader后打开jlink commander即可自动升级固件
* 如果提示了没license 就打开jlink commander 输入以下的sn  喜欢什么版本就输入什么sn

#  Exec SetSN=20281318    V9.2
#  Exec SetSN=20381318    V9.3
#  Exec SetSN=20481318    V9.4
#  Exec SetSN=20581318    V9.5
#  Exec SetSN=20681318    V9.6
#  Exec SetSN=20781318    V9.7
### 新版本的Jlink驱动要多加点内容，例如
# exec SetSN=20781318,0xCF2EF286
> 另外强调一下，本仓库的项目是**GPL协议**，不支持任何形式的私自产品化（当然大家自己DIY是没有任何问题的，这里只是防止有人借我的名义坑大家）
