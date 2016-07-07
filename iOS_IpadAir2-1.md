#### Test 757892685345aa0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/7ED402DA-BC6F-4CD7-858E-AF3D0AD8E679/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7ED402DA-BC6F-4CD7-858E-AF3D0AD8E679/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B5D32EBE-15A0-43AC-B50A-234B76C60BB2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51405"
,(lldb)     command script import "/tmp/7ED402DA-BC6F-4CD7-858E-AF3D0AD8E679/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 15:44:07.782 ThaliTest[3831:13928382] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A0EF79D6-1D07-4E51-95C7-E60B10CE331A/Library/Cookies/Cookies.binarycookies
,2016-07-07 15:44:08.014 ThaliTest[3831:13928382] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 15:44:08.015 ThaliTest[3831:13928382] Multi-tasking -> Device: YES, App: YES
,2016-07-07 15:44:08.031 ThaliTest[3831:13928382] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 15:44:08.834 ThaliTest[3831:13928382] Using UIWebView
,2016-07-07 15:44:08.836 ThaliTest[3831:13928382] [CDVTimer][handleopenurl] 0.122011ms
,2016-07-07 15:44:08.838 ThaliTest[3831:13928382] [CDVTimer][intentandnavigationfilter] 1.841962ms
2016-07-07 15:44:08.838 ThaliTest[3831:13928382] [CDVTimer][gesturehandler] 0.083983ms
2016-07-07 15:44:08.838 ThaliTest[3831:13928382] [CDVTimer][TotalPlug,inStartup] 2.512991ms
,2016-07-07 15:44:12.102 ThaliTest[3831:13928382] Resetting plugins due to page load.
,2016-07-07 15:44:13.531 ThaliTest[3831:13928382] Finished load of: file:///var/mobile/Containers/Bundle/Application/B5D32EBE-15A0-43AC-B50A-234B76C60BB2/ThaliTest.app/www/index.html
,2016-07-07 15:44:13.664 ThaliTest[3831:13928382] JXcore Cordova plugin initializing
,2016-07-07 15:44:13.665 ThaliTest[3831:13928563] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
