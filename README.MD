 
### Win32-DLL型调试器,注入dll即可调试！

这个调试器是几年前调试游戏的时候临时做的，现在翻出来共享下。

 _使用Vs编译器 version >= 2010 _ 

 _代码基本上就是C代码_ 

 _过保护的功能只在Win7sp1 x64 上运行，有几处代码稍微补下现在也是可以用的 (config.h中开启)_ 

![输入图片说明](http://git.oschina.net/uploads/images/2016/1112/150338_0fc41eef_632350.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/1112/150352_87ea9ec1_632350.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/1112/150357_3ecd89ca_632350.png "在这里输入图片标题")



除了界面内的操作，其他的快捷键分别是：
       
```
case 'G':                                       //跳转到
case VK_SPACE:				        //汇编此处
case VK_F2:					//cc断点
case VK_F3:					//条件cc断点
case VK_F7:                                     //单步 - 设置当前线程TF位继续走
case VK_F9:					//运行

```