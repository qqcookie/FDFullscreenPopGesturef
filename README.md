# FDFullscreenPopGesture
A UINavigationController's category to enable fullscreen pop gesture with iOS7+ system style.

# Overview

![snapshot](https://raw.githubusercontent.com/forkingdog/FDFullscreenPopGesture/master/Snapshots/snapshot0.gif)

这个扩展来自 @J_雨 同学的这个很天才的思路，他的文章地址：[http://www.jianshu.com/p/d39f7d22db6c](http://www.jianshu.com/p/d39f7d22db6c)

# Usage

**AOP**, just add 2 files and **no need** for any setups, all navigation controllers will be able to use fullscreen pop gesture automatically.  

To disable this pop gesture for navigation controller:  

``` objc
navigationController.fd_fullscreenPopGestureRecognizer.enabled = NO;
```

To disable this pop gesture for a single view controller:  

``` objc
viewController.fd_interactivePopDisabled = YES;
```


# Install  

Use cocoapods  

``` ruby
pod 'FDFullscreenPopGesture', '1.0'
```

# License  

MIT
