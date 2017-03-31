
DYDeviceInfo
=
喜欢的朋友可以下载下来，如果代码对你有所帮助，还请给个Star，非常感谢你的支持！
= 
 * 获取设备的各种标识符,IDFA,UDID,IDFV,MAC,IMEI,UUID.其中UDID和IMEI可能需要越狱才能尝试，给出相应的解决方案链接，有兴趣的可以尝试
 
 
 * 效果图
 
  ![image](https://github.com/DanielYK/AdAlertView/blob/master/adAlert.gif)


 * 对应文件
 * DYDeviceInfo : 设备标识符实现文件
 
 * 具体使用，你只用调用方法就可以了
<pre><code>
NSString *idfvStr = [DYDeviceInfo dy_getDeviceIDFV];
</code></pre>

* 导入类库说明
<pre><code>

framework：
AdSupport ：为了获取idfa
导入头文件：
//获取idfa
#import <AdSupport/ASIdentifierManager.h>
//获取mac
#include <sys/sysctl.h>
#include <sys/socket.h>
#include <net/if.h>
#include <net/if_dl.h>
</code></pre>

 - 使用过程中有问题请加QQ或发邮件:584379066 备注：Git DeviceInfo
