---
layout: post
title: 手机刷机常用命令
tags: [adb]
---

> 一篇自己手机刷机所用的命令， 希望对大家有所帮助


1. 进入fastboot：  
   adb reboot-bootloader  进入fastboot  
   fastboot devices    
   fastboot flash recovery xx.img

2. 手机进入recovery：  
    adb shell  
    su  
    reboot recovery


3. 安装  UPDATE-SuperSU-v2.46.zip （ROOT包）  
        和  
        gapps-kk-20140606-signed.zip（google服务包） 


> 需要自己手机版本对应的 `ROOT包` 和 `Google服务包` 自己网上找找

