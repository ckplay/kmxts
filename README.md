# kmxts
EDLM个人发卡网（程序）是由MadDog使用Thinkphp开发的一个站长收款免签约自助提卡系统,安全、稳定、不加收任何费用、直接到账、一站式售卡系统。

支付服务使用的也是EDLM全新发布的L Pays 免签约收款服务,优势:个人收款免签约,资金直达(直接使用个人收款二维码收款),零费率！

重要：请确保主机环境已开启伪静态,使用宝塔的用户请在web面板->对应的网站->伪静态->选择Thinkphp!  
没有开启伪静态会导致 无法创建订单 无法查询卡密 无法进入后台 等情况   

搭建方法:  
0.确保程序可获得文件最高操作权限  
1.上传程序至网站根目录后解压  
2.打开网站，根据提示步骤完成安装  
3.打开根目录中的app文件夹->编辑route.php文件中的admin 为 您自设的后台地址 两个都需要修改，修改后使用你设置的入口进入后台  
  
 
默认信息：  
后台入口：网址+/admin (注意:后台最后面不要加“/”比如“km.edlm.cn/admin/” 这样是不行的,会导致后台样式出错！要把最后面的“/”去掉！)  
账号：admin  
密码：123456  
搭建演示：https://api.edlm.cn/txv.php?vid=a0870hv5095 (视频为旧版，新版本中的后台为admin)  

作者留言：  
请尊重作者的劳动功劳，勿修改版权信息  
为了防止某人盗取版权，源码特作处理，如需原版源码请联系我  
QQ交流群:399454219
  
作者VX:Edi13146  
![image](https://github.com/maddog888/images/blob/master/wx.jpg?raw=true)
