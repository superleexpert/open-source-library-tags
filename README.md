###Mark下使用到的开源类库、工具以便总结查看
----------------------------------------------------------------------
[FMDB:](https://github.com/ccgus/fmdb)开源数据库，对SQLite进行了封装，可直接使用或二次封装<br>
其他 - 使用过Sqlite，需要手动进行封装，前者更易用<br>
[realm](https://github.com/realm/realm-cocoa) - 针对移动应用设计<br>
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
[Alcatraz:](https://github.com/supermarin/Alcatraz)Xcode包管理工具，可搜索后直接安装\卸载，下面推荐4款好用工具<br>
[KSImageNamed:](https://github.com/ksuther/KSImageNamed-Xcode)自动提示图片插件，在imageNamed后自动提示预览图片和名称补全功能，提高Coding效率<br>
[VVDocumenter:](https://github.com/onevcat/VVDocumenter-Xcode)能够快速生成注释文档，Javadoc规范，使用"///"识别<br>
[CocoaPods:](https://github.com/kattrali/cocoapods-xcode-plugin)关联性管理器，可管理第三方库之间的相互依赖，简化了类库的相互依赖、更新、维护等操作，很多主流类库已托管之上<br>
[Peckham:](https://github.com/markohlebar/Peckham)自动生成#import引入，可在任意位置触发选择器<br>

----------------------------------------------------------------------
[dSYM:](https://github.com/answer-huang/dSYMTools)线上App定位bug工具，通过出错的函数地址去查询dSYM文件中程序对应的函数名和文件名<br>

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
[Demo1:](https://github.com/mattt/TTTAttributedLabel)（把整段string分割出link链接，附有动态获取Cell高度的方法）<br>

----------------------------------------------------------------------
[FDFullscreenPopGesture:](https://github.com/forkingdog/FDFullscreenPopGesture)全屏滑动pan手势pop返回到一级页面，基于UINavigationController，返回动效贴近源生效果，支持iOS7以上<br>
其他 - [MLTransition:](https://github.com/molon/MLTransition)相似的pop拖动返回功能，号称用了unpublish的API仍然通过审核，要使用的话还是谨慎一些，不确定将来是否没问题<br>

-----------------------------
[UITableView-FDTemplateLayoutCell:](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell)根据内容动态计算UITableViewCell高度，支持文本+图片的排版<br>
其他 - [TTTAttributedLabel:](https://github.com/mattt/TTTAttributedLabel)里有Cell根据文本内容匹配高度的方法，无图片<br>
[Demo1:](https://github.com/weida-studio/QQ)（类似QQ聊天界面，纯代码布局）<br>

-----------------------------
[DateTools:](https://github.com/MatthewYork/DateTools)日期工具库，可进行日期和时间的相关操作，支持中文输出<br>

-----------------------------
[Mantle:](https://github.com/Mantle/Mantle)可以把JSON数据转化成Model模型，构建模型层<br>
其他 - [JSONModel:](https://github.com/icanzilb/JSONModel)类似的数据模型封装<br>
[MTLFMDBAdapter:](https://github.com/tanis2000/MTLFMDBAdapter)可用于Mantle和FMDB之间的转换<br>
[关于Mantle](http://www.cocoachina.com/ios/20150127/11034.html)有相关的介绍和使用方法，[为什么选择Mantle](http://get.ftqq.com/5929.get)<br>

-----------------------------
[GVUserDefaults:](https://github.com/gangverk/GVUserDefaults)对NSUserDefaults进行了封装，使NSUserDefaults的调用更加轻便<br>

-----------------------------
[FCFileManager:](https://github.com/fabiocaccamo/FCFileManager)对NSFileManager的扩展封装，使文件的操作更加简便<br>

-----------------------------
[JSONKit:](https://github.com/johnezang/JSONKit)JSON数据解析、序列化JSON，常被用作库之间的依赖<br>
其他 - [TouchJSON:](https://github.com/TouchCode/TouchJSON)类似功能的JSON解析类库<br>
NSJSONSerialization是苹果iOS5之后提供的自带解析API<br>

-----------------------------
[Shimmer:](https://github.com/facebook/Shimmer)动态的闪烁效果，可用作标题或加载指示器，facebook出品<br>

-----------------------------
[MMDrawerController:](https://github.com/mutualmobile/MMDrawerController)测拉下浮层菜单，预览视图、距离等属性可直接调整，事件处理有block回调，易扩展<br>
其他 - [ViewDeck:](https://github.com/ViewDeck/ViewDeck)左右侧下浮层菜单，类似Path2.0的侧滑效果<br>
[CSDrawerController:](https://github.com/icecreamstudios/ICSDrawerController)左侧下浮层菜单，支持点击和手势操作，回调代理有返回状态，支持iOS7以上<br>
[MSDynamicsDrawerViewController:](https://github.com/erichoracek/MSDynamicsDrawerViewController)左侧下浮层菜单，具有弹性效果<br>
[ECSlidingViewController:](https://github.com/ECSlidingViewController/ECSlidingViewController)左侧上浮层菜单，类似的视图控制器<br>
[REFrostedViewController:](https://github.com/romaonthego/REFrostedViewController)左侧上浮层菜单，具有iOS7之后的模糊效果，实现了拖动和点击<br>

-----------------------------
[iCarousel:](https://github.com/nicklockwood/iCarousel)旋转木马的视图切换效果，包括CoverFlow、TimeMachine等3D效果，可用作对ViewController集合的管理器<br>

-----------------------------
[SDVersion:](https://github.com/sebyddd/SDVersion)可检测设备版本和屏幕尺寸，包含了iOS和Mac OS的轻量级工具库<br>

-----------------------------
[VPImageCropper:](https://github.com/windshg/VPImageCropper)图片选择器，可拍照或从图库选择，获取后可编辑图片位置，返回头像形圆图<br>

-----------------------------
[KNSemiModalViewController:](https://github.com/kentnguyen/KNSemiModalViewController)实现缩放ViewController后弹出半模态视图，带有叠加动画，可用作底部弹出分享面板、工具栏等<br>

-----------------------------
[Color:](https://github.com/thisandagain/color)UIColor颜色设置的封装，包含RGB等<br>
其他 - [iOS7Colors:](https://github.com/claaslange/iOS7Colors)iOS7下颜色的设置，UIColor类目下类方法实现<br>

-----------------------------
[FRDLivelyButton:](https://github.com/sebastienwindal/FRDLivelyButton)扁平风格导航按钮，有菜单、关闭、添加等图形，切换间具有动画效果，UIButton的子类封装<br>
其他 - [TBIconTransitionKit:](https://github.com/AlexeyBelezeko/TBIconTransitionKit)类似的icon动画切换效果，有不同的过度方式<br>

-----------------------------
[NJKWebViewProgress:](https://github.com/ninjinkun/NJKWebViewProgress)实现了UIWebView的加载进度条显示<br>

-----------------------------
[SwipeView:](https://github.com/nicklockwood/SwipeView)水平方向滚动视图加载，基于UIScrollView，可实现动态加载效果<br>

-----------------------------
[TMCache:](https://github.com/tumblr/TMCache)缓存数据解决方案，可以缓存到Memory或者Disk<br>

-----------------------------
[SlackTextViewController:](https://github.com/slackhq/SlackTextViewController)滑动视图下方文字输入框高度自适应，可复制单元格内容等<br>

-----------------------------
[FXBlurView:](https://github.com/nicklockwood/FXBlurView)通过UIView的子类，提供了视图的模糊、虚化效果<br>
[VVBlurPresentation:](https://github.com/onevcat/VVBlurPresentation)基于ViewController，喵神出品<br>

-----------------------------
[Knuff:](https://github.com/KnuffApp/Knuff)苹果推送通知APNs调试工具<br>

-----------------------------
[MMNumberKeyboard:](https://github.com/matmartinez/MMNumberKeyboard)一款自定义的简洁数字键盘，包含小数点“.”，继承于UIInputView，支持iOS7以上<br>

-----------------------------
[MWPhotoBrowser:](https://github.com/mwaterfall/MWPhotoBrowser)照片选择和浏览控件<br>
其他 - [CTAssetsPickerController:](https://github.com/chiunam/CTAssetsPickerController)图片选择器组件，支持从图片库选择多张图片<br>
[TZImagePickerController:](https://github.com/banchichen/TZImagePickerController)支持多选、选原图和视频的图片选择器<br>

-----------------------------
[SDCycleScrollView:](https://github.com/gsdios/SDCycleScrollView)无限循环图片轮播器,使用了UICollectionView实现<br>

-----------------------------
[ZYCornerRadius:](https://github.com/liuzhiyi1992/ZYCornerRadius)实现设置圆角，两种工作方式：Category和UIImageView子类<br>

-
