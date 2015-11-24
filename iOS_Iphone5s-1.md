#### Test 513350288bfb88c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350288bfb88c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3E6D75A5-616B-48C9-BB6D-DB55F4B9201B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3E6D75A5-616B-48C9-BB6D-DB55F4B9201B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350288bfb88c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350288bfb88c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54661"
,(lldb)     command script import "/tmp/3E6D75A5-616B-48C9-BB6D-DB55F4B9201B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 13:24:53.570 ThaliTest[1497:1251014] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DBAF0C32-57BC-4C5D-BD27-C858208BAC2F/Library/Cookies/Cookies.binarycookies
,2015-11-24 13:24:53.981 ThaliTest[1497:1251014] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 13:24:53.982 ThaliTest[1497:1251014] Multi-tasking -> Device: YES, App: YES
,2015-11-24 13:24:53.991 ThaliTest[1497:1251014] Unlimited access to network resources
,2015-11-24 13:24:53.997 ThaliTest[1497:1251014] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 13:24:57.475 ThaliTest[1497:1251014] Resetting plugins due to page load.
,2015-11-24 13:24:57.840 ThaliTest[1497:1251014] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/index.html
,2015-11-24 13:24:57.997 ThaliTest[1497:1251014] JXcore Cordova plugin initializing
,2015-11-24 13:24:57.998 ThaliTest[1497:1251130] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,2015-11-24 13:24:58.169 ThaliTest[1497:1251130] Error!: this.toggleWifi is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios/<","_lineNumber":"16","_columnNumber":"5","_msg":"    at exports.toggleRadios/<@/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js:16:5"},{"_fileName":"/p,rivate/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth/<","_lineNumber":"36","_columnNumber":"5","_msg":"    at exports.toggleBluetooth/<@/pri,vate/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js:36:5"},{"_fileName":"main.js","_functionName":"JXMobile.ToggleBluetooth","_lineNumber":"203","_columnNumber":"5","_msg":"    at JXM,obile.ToggleBluetooth@main.js:203:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth","_lineNumber":"32","_columnNumbe,r":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D19530EF-4,BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3","_msg":"    at exports.toggleRadios@/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE,3-F1D8A495EE69/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"13","_columnNumber":"1",,"_msg":"    at @/private/var/mobile/Containers/Bundle/Application/D19530EF-4BCA-435F-8FE3-F1D8A495EE69/ThaliTest.app/www/jxcore/app.js:13:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_ms,g":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_f,unctionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]

```
