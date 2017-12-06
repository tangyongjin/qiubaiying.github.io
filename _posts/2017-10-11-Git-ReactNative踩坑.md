---
layout:     post
title:      ReactNative踩坑 
subtitle:   
date:       2017-02-16
author:     BY
header-img: img/post-bg-debug.png
catalog: true
tags:
    - Mac
    - 终端
    - Git
---



#### 坑1：env: bash\r: No such file or directory

原因：  脚本文件的格式问题  
vi android/gradlew , set ff=unix

#### 坑2：时间不同步   

adb shell date -s $(date +%Y%m%d.%H%M%S)

	


adb shell date -s $(date +%Y%m%d.%H%M%S)



