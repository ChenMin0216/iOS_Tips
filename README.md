# iOS_Tips
iOS的一些示例，不定时更新~  简书地址：https://www.jianshu.com/p/a2a04cabb98d

### 目录 
> 1、暗黑模式  2、AppleID登录应用  3、AVFoundation 高仿微信相机拍摄和编辑 4、AVFoundation 人脸检测  5、AVFoundation 实时滤镜 6、GPUImage框架的使用  7、VideoToolBox和AudioToolBox音视频编解码

## 1、 暗黑模式适配

![暗黑模式](PrviewPicture/暗黑模式.gif)
  
## 2、AppleID登录应用

* 查看本仓库下的AddingTheSignInWithAppleFlowToYourApp

## 3、微信相机拍摄照片、小视频以及编辑功能  
> 效果描述：  
> * 1、自定义相机 拍摄视频和照片
> * 2、切换前后摄像头、调整焦距/设置聚焦点、横屏拍摄
> * 3、视频编辑：涂鸦、gif贴图、文字水印、视频裁剪 、添加背景音乐 
> * 4 、图片编辑：涂鸦、贴图、文字水印、马赛克、图片裁剪

> 主要类：SLAvCaptureTool(音视频采集录制工具)、SLAvEditExport(导出编辑的音视频)、

|![拍摄视频.gif](PrviewPicture/3、小视频1.gif)|![拍摄照片](PrviewPicture/3、小视频2.gif)|![横屏视频](PrviewPicture/3、小视频3.gif)|

*****

|![视频编辑](PrviewPicture/3、小视频4.gif)|![视频编辑](PrviewPicture/3、小视频5.gif)|![图片编辑](PrviewPicture/3、小视频6.gif)|

****

|![图片编辑](PrviewPicture/3、小视频7.gif)|![图片裁剪](PrviewPicture/3、小视频8.gif)|


## 4、人脸检测 

![人脸识别](PrviewPicture/4、人脸识别.gif)

## 5、实时滤镜拍摄和导出

>  主要类: 是由SLAvCaptureTool拆分的 SLAvCaptureSession（采集） + SLAvWriterInput（录制） 两个工具类，方便扩展，实现的方式也略有不同

![人脸识别](PrviewPicture/5、实时滤镜拍摄.gif)

## 6、GPUImage框架的使用

> 效果描述：实时拍摄添加水印和滤镜、本地视频添加水印、GIF图水印

* 遗留问题：一个启动周期内，第一次启动摄像头时打开特慢，之后就特别块，还没找到原因，望知道到的告知一下🤝

![GPUImage框架的使用](PrviewPicture/6、GPUImage.gif)

## 7、VideoToolBox和AudioToolBox音视频编解码

> 请查看本仓库下的 VideoEncoder&Decoder 文件

![音视频编码](PrviewPicture/7、音视频编码.gif)


## Welcome To Follow Me

>  您的follow和start，是我前进的动力，Thanks♪(･ω･)ﾉ
> * [简书](https://www.jianshu.com/u/e15d1f644bea)
> * [微博](https://weibo.com/5732733120/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1)
> * [掘金](https://juejin.im/user/5c00d97b6fb9a049fb436288)
> * [CSDN](https://blog.csdn.net/wsl2ls)
> * QQ交流群：835303405

> 欢迎扫描下方二维码关注——奔跑的程序猿iOSer——微信公众号：iOS2679114653 本公众号是一个iOS开发者们的分享，交流，学习平台，会不定时的发送技术干货，源码,也欢迎大家积极踊跃投稿，(择优上头条) ^_^分享自己开发攻城的过程，心得，相互学习，共同进步，成为攻城狮中的翘楚！

![iOS开发进阶之路.jpg](http://upload-images.jianshu.io/upload_images/1708447-c2471528cadd7c86.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

