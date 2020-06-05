# AR_small_demo-move_and_scale_object-

Development Environment: Mac，iPhone
Development Software: Xcode
Development Languge: Objective-C
Using language Objective-C, the AR app is compiled by Mac with Xcode, and the app is used in iPhone. The function is as follows: 1 Put a model in the scene created by your camera in iPhone. 2 Change the position and the scale of it.

The details in Chinese:总结下菜鸟4天来（第1天用Scechup做模型了）的收获，走了很大弯路：以前做c数值模拟，Java很早前写过小程序，因为跨专业申博想做个展示模型，毕竟建筑自己很弱计算机好些，也就是把建筑模型放到真实场景中，可以移动变大小，用的Mac和iPhone，所以用ARKit，一开始很懵看到Objective-C的程序（在这之前用了Xcode AR自带的示例程序，开通了苹果开发者账户可以签名，会把ipa(app on iPhone)装手机上运行了），但是看了ARKit的介绍大概知道实现的逻辑，就在网上找demo，屡屡受挫，（中间也被迫补充了一些ARKit的基础实现理论和几个类）昨天多亏了一位网友小姐姐，找到一个可以运行的程序，就可以研究了，上午熟悉了OC的语法（其实swift也类似的），下午把程序过了一遍，明白了怎么回事终于。一种正确的ARkit实现AR简单程序的菜鸟入门步骤是：1会用自己的系统做一个小软件装自己手机上运行（Mac 的 Xcode 就行，Windows 的 unity 就行）。2入门级AR demo运行，了解开发语言（我竟然第五天才想起来看Objective-C，之前没想过看不懂程序的原因也是醉了）。3了解语言后读demo程序 4找相关靠谱（苹果官网和github的靠谱点）demo实现自己想实现的类似功能，读程序，修改总结。开始做新的建筑模型啦   原文链接：https://blog.csdn.net/Lily_AstroChemistry/article/details/106578243
