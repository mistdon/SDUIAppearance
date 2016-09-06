# SDUIAppearance
UIAppearance tutorial, fromw Raywenderlich.com https://www.raywenderlich.com/108766/uiappearance-tutorial

Environment: Xcode 7.3, Swift 2.2


Note: 
  1. Use the UIAppearance protocol to get the appearance proxy for a class;  
    (UIAppearance是一个协议，为一个类提供代理方法)  
  2. All the + (instancetype)appearance is unique  
    + (instancetype)appearance 返回的值是唯一的，也就是当改变之后，所有随之出现的相关类，都发生了改变   
  3. All the property marked ‘UI_APPEARANCE_SELECTOR’ can be a proxy of UIAppearance protocol   
   (所有带有‘UI_APPEARANCE_SELECTOR’标签的属性都可以实现UIAppearance协议)  

Have fun!