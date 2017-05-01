## 东方新闻
### 闪屏界面

<img src="https://github.com/android-jian/LBSTest/blob/master/images/splash.png" width="400"/>

### 主界面

注：APP中的数据来源：聚合数据

主界面设计：顶部使用ToolBar代替ActionBar，内容部分为ViewPager+Fragment，底部为RedioGroup。整体分为四个模块。

* 首页：
  
  首页整体分为两部分，即顶部的ViewPager指示器和ViewPager，ViewPager指示器使用了第三方开源框架。
  下方的ViewPager同样借助FragmentPagerAdapter。Fragment（头条）整体为RecyclerView，实现下拉刷新及上拉加载功能，
  根据ViewType不同，分为三个部分，顶部的HeaderView、新闻条目ItemView、底部FooterView。HeaderView又是一个
  ViewPager，进行图片轮播效果展示。ItemView作为新闻条目。FooterView用来显示加载状态。
  
  效果图展示：

  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>  <img src="https://github.com/android-jian/LBSTest/blob/master/images/loadmore.png" width="400"/>


* 美女模块：
  这部分使用了RecyclerView的瀑布流效果

  效果图展示：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>

* 话题模块还未编写

* 设置模块：

  其中设置模块的UI效果图模仿的是网易新闻客户端，小弟能力不够，好多功能都未实现。后台集成了Bmob后端云，实现了用户
  注册、邮箱及短信验证、用户登录、更换头像、新闻收藏、阅读记录、二维码扫描以及夜间模式等功能。
  
  用户注册及验证：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/> <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>
  
  登陆界面：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>
  
  上传头像：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>
  
  收藏界面：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/> <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>
  
  阅读记录：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>
  
  二维码扫描：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>
  
  夜间模式：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>

新闻详情界面：

  集成ShareSDK实现新闻分享功能，并模仿网易新闻，实现截屏分享。
  效果图展示：
  
  <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/> <img src="https://github.com/android-jian/LBSTest/blob/master/images/top.png" width="400"/>
  
## 关于作者
```javascript
  var boyumi = {
    nickName  : "Ivan Lim",
    site : "http://boyumi.com"
  }
```
```
