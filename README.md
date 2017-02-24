# CocoaChinaCodes

 个人上传到CocoaChina 所有代码的集合,仅做学习交流
 
 遇见不同阶段的自己 持续更新中
 
 1 教授视频播放器  
 
基于AVPlayer 写的视频播放器,播放退出时完美释放内存.
播放进度显示缓存进度,网络不好时有加载动画
仿哔哩哔哩发送弹幕的动画
程序进入后台停止播放
地址 http://code.cocoachina.com/view/131840

2 CYAdjustButton 设置button的 imageView 和 titleLabel 的位置

可以在 button 内部设置任意 imageView 和 titleLabel 的 frame 支持 xib 和代码创建 CYAdjustButton ,支持是否显示点击高亮状态.

代码地址 : https://github.com/ZhaoBingDong/CYAdjustButton

CocoaChina : http://code.cocoachina.com/view/131256


3 优雅设置圆型图片避免丽萍渲染

最近看了不少设置圆角图片的干货,才把项目里设置 layer.cornerRadius 地方给替换了,自己写的用 SDWebImage下载完图片后,用 Quartz2D 裁剪图片成圆形,然后给 imageView 显示,拖动表格时不加载图片,拖动停止才显示图片.缓存过的圆形图片不用再次下载和裁切.


http://code.cocoachina.com/view/129913

4  叫兽自定义视频播放器

自己基于 AVPlyer 写的一个视频播放器,实现了播放/暂停,快进,快退的基本功能.还支持横竖屏切换

http://code.cocoachina.com/view/129573

5 音乐播放器

自己写的音乐播放器,基于 AVPlayer

github 地址: https://github.com/ZhaoBingDong/CYMusic.git

6 CYNetworking+CYAlertKit+CYProgressView

自己写的网络请求库,对于 NSURLSession 的简单封装,实现了基本的 GET ,POST 表单上传图片等功能

1) 还有对系统 UIAlertController 的封装 弹出 alert 弹出 actionSheet 只需一句代码

2) 对 UIImagePickerController 的封装 获取相册相机图片只需一句代码

3) 一个带加载进度的 ImageView 类似 手机 QQ 发图片消息 图片带进度指示 需要配合 CYNetworking使用

  http://code.cocoachina.com/view/129057
  
 7 MVVM登录页面
 
 用 ReactiveCocoa框架实现的 MVVM 构架,讲业务逻辑更多的写到 ViewModel 里边,实现了 ViewController 的减负.

http://code.cocoachina.com/view/128939

8 Swift 轻量级网络请求类,一般请求就用它 (swift开发初体验)

今年8月份写的请求类,刚开始是基于 NSURLConnect 封装,近期废弃了所有 NSURLConnect 相关的 API, 全面基于 NSURLSession 用法和 AFNetworking 查不多,也有 两个 block 进行请求结果的回调.

http://code.cocoachina.com/view/128819
 9 CoreData封装第二季 支持字典转模型
 
 对于 CoreData的简单封装,自己项目中也在使用,没有实现多表查询的功能,只能存储单个模型文件.使用起来还可以吧,反正我自己用着还算可以.
 
 http://code.cocoachina.com/view/128500
 
 10 搜索联系人 通讯录联系人分组
 
 类似微信联系人搜索的界面,快速查找联系人,并支持点击查询结果
 http://code.cocoachina.com/view/128245
 
 11 数据存储管理类 
 
 一句代码存对象到沙盒，一句代码从沙盒读取对象.
http://code.cocoachina.com/view/128194

 12 解析 Emoji 表情 
 自己写的解析即时通信聊天时接受到的带表情和普通文本的消息，一句代码完成解析并转成富文本给UILabel和UITextView显示
http://code.cocoachina.com/view/128192

 
