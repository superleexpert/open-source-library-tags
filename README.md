###Mark下使用到开源类库以便再次复用
----------------------------------------------------------------------
[FMDB:](https://github.com/ccgus/fmdb)开源数据库，对SQLite进行了封装，可直接使用或二次封装<br>
其他 - 使用过Sqlite，需要手动进行封装，前者更易用<br>
[Demo1:](https://github.com/tangqiaoboy/FmdbSample)（表单创建、索引、删除，多线程）<br>

-----------------------------
[HYBubbleButton:](https://github.com/nathanwhy/HYBubbleButton)向上飘散动画效果，使用CAAnimation配合CGPath路径进行位移动画<br>
其他 - 类似效果也可使用Dazzle，使用了CAEmitterLayer粒子效果<br>
[Demo1:](https://github.com/superleexpert/UIButonAnimation)（匹配项目需求，连续点击和长按效果）<br>

-----------------------------
[Masonry:](https://github.com/SnapKit/Masonry)布局框架，适合在代码搭建界面使用，系统布局的一种替代方案，有对应Swift版本<br>
其他 - AutoLayout，自动布局，通过创建约束配合可视化界面来创建UI<br>
[UITabelView使用AutoLayout自适应布局](http://www.cocoachina.com/ios/20151009/13640.html)<br>
[AutoLayout全解](http://www.jianshu.com/p/683fbcbfb705)其中的[UIWebView与UITableView、UIScrollView的交互使用](http://grayluo.github.io/WeiFocusIo/autolayout/2015/02/01/autolayout4/)可以计算ContentSize的动态高度<br>
[Demo1:](https://github.com/superleexpert/AutoLayoutTest)（AutoLayout测试，使用UIScrollView时注意"建立一个与UIScrollview的父视图MainView相同EqualWidth,EqualHeight的约束）<br>

-----------------------------
[UICKeyChainStore:](https://github.com/kishikawakatsumi/UICKeyChainStore)可存储信息到Keychain，删除App后依然存在<br>

----------------------------------------------------------------------
[ZXingObjC:](https://github.com/TheLevelUp/ZXingObjC)二维码、条形码扫描识别解决方案，可设置可视区域<br>

----------------------------------------------------------------------
[IQKeyboardManager:](https://github.com/hackiftekhar/IQKeyboardManager)UITextField/UITextView键盘弹出时的遮挡自适应，简易的解决方案<br>

----------------------------------------------------------------------
[pop:](https://github.com/facebook/pop)facebook开源动画引擎，支持弹性、衰减动画，功能强大，核心使用CoreAnimation<br>
其他 - [Canvas:](https://github.com/CanvasPod/Canvas)是一个动画合集，目标"Animate in Xcode Without Code"，对于能够支持的动画效果还算易用，想要扩展有点生硬，[关于二者的比较](http://www.cocoachina.com/industry/20140515/8436.html)<br>

----------------------------------------------------------------------
[CRGradientNavigationBar:](https://github.com/chroman/CRGradientNavigationBar)可任意设置UINavigationBar的背景颜色和渐变效果，继承于UINavigationBar，支持iOS6以上<br>

----------------------------------------------------------------------
[Objective-C RegEx Categories:](https://github.com/bendytree/Objective-C-RegEx-Categories#introduction)正则表达式的扩展，添加了NSRegularExpression类目，可用来作邮箱地址有效性、校验数据合法性等验证<br>
其他 - [RegexKitLite:](https://github.com/wezm/RegexKitLite)正则是对NSString的扩展，校验必须是NSString类型<br>
[xpath](http://www.cocoachina.com/bbs/read.php?tid-29453-page-1.html)是一个正则实现的网页抓取小工具，可在网页上抓取信息<br>

----------------------------------------------------------------------
[MBProgressHUD:](https://github.com/jdg/MBProgressHUD)任务进行时的Loading显示状态，可用于页面加载、请求数据等<br>
其他 - [SVProgressHUD:](https://github.com/TransitApp/SVProgressHUD)类似的加载过程显示组件，显示样式不同于前者<br>
[MRProgress:](https://github.com/mrackwitz/MRProgress)类似的加载显示组件，可获取进度百分比<br>

----------------------------------------------------------------------
[Alcatraz:](https://github.com/supermarin/Alcatraz)Xcode包管理工具，可搜索后直接安装\卸载，下面推荐3款好用工具<br>
[KSImageNamed:](https://github.com/ksuther/KSImageNamed-Xcode)自动提示图片插件，在imageNamed后自动提示预览图片和名称补全功能，提高Coding效率<br>
[VVDocumenter:](https://github.com/onevcat/VVDocumenter-Xcode)能够快速生成注释文档，Javadoc规范，使用"///"识别<br>
[CocoaPods:](https://github.com/kattrali/cocoapods-xcode-plugin)关联性管理器，可管理第三方库之间的相互依赖，简化了类库的相互依赖、更新、维护等操作，很多主流类库已托管之上<br>

----------------------------------------------------------------------
[Reachability:](https://github.com/tonymillion/Reachability)网络相关状态监测，支持Block，使用时重命名以防审核被拒<br>
其他 - [Reachability:](https://developer.apple.com/library/prerelease/ios/samplecode/Reachability/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007324-Intro-DontLinkElementID_2)苹果官方版本，支持iOS6以上<br>

----------------------------------------------------------------------
[SDWebImage:](https://github.com/rs/SDWebImage)支持图片的网络请求、显示、缓存，添加了UIImageView类目<br>
其他 - UIImageView+AFNetworking也提供了相似的异步加载图片功能<br>

----------------------------------------------------------------------
[AFNetworking:](https://github.com/AFNetworking/AFNetworking)强大的网络请求封装，[Mattt Thompson](https://github.com/mattt/)出品，Swift版可使用[Alamofire](https://github.com/Alamofire/Alamofire)<br>

----------------------------------------------------------------------
[TTTAttributedLabel:](https://github.com/TTTAttributedLabel/TTTAttributedLabel)渲染字符串，支持链接植入，支持NSAttributedString<br>
其他 - [MLEmojiLabel:](https://github.com/molon/MLEmojiLabel)自动识别网址、邮箱、表情等<br>
[Demo1:](https://github.com/mattt/TTTAttributedLabel)（把整段string分割出link链接，里面有动态获取Cell高度的方法）<br>










