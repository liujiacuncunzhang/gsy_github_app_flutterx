# gsy_github_app_flutter

Github Application

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).



准备：网络请求库使用dio、flutter-redux、sqflite、css_colors



在哪里存储字符串? 如何存储不同的语言
目前，最好的做法是创建一个名为Strings的类
class Strings{
  static String welcomeMessage = "Welcome To Flutter";
}
然后在你的代码中，你可以像访问你的字符串一样：new Text(Strings.welcomeMessage)


welcome -> login

生成序列化模板
flutter packages pub run build_runner build


### 配合AutomaticKeepAliveClientMixin可以keep住tab

### 如何主动刷新refresh，如何设置appbar上的leading和bottom，如何设置tabbar的live

https://github.com/flutter/flutter/issues/19030 没有webview，残念

markdown文件详情

图片浏览

搜索

commonList的过滤

主页drawer：关于、个人信息

动态页面


仓库的： 
    动态的背景头像
    版本、tag
    浏览器打开
    下载、复制克隆间接
    分享
    
个人页面的：
    关注
    组织
    头像浏览
    