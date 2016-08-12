
## LYTitleBarController
* 快速创建一个带导航标题按钮的控制器

## Contents
* 使用简单方便
* 导航条可以自定义
* 标题文字可以自定义
* 选中指示器可自定义
* 跑马灯特效
 
##How to use LYTitleBarController
1.继承后,添加子控制器就行并设置控制器View的Frame*必须添加子控制器(不设置frame可能出现一些异常)
2.添加控制器的时候需要设置控制器的title,不然标题为空
3.其他属性自选设置,不设置都会初始化默认值

注意点:展示内容的控制器View请自行根据导航条的高度和状态栏高度计算Frame  如果控制器的View为tableView或者继承自scrollView的View想要穿透效果,可以把frame设置为屏幕的bounds,再设置contentInset属性实现

PS:在使用中遇到什么BUG或者你有什么好的建议或者意见欢迎联系378018674@qq.com进行探讨!

## Demo

![image](https://raw.githubusercontent.com/kakaxixixi/LYTitleBarController/master/LYTitleBarController/LYTitleBarController/Picture/test1.gif)



