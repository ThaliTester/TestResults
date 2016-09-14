#### Test 836273373ce2df7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0433E75C-0D11-453E-8EA6-BE44EC87F437/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0433E75C-0D11-453E-8EA6-BE44EC87F437/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8C7CF7D9-2852-43A5-9638-2072001E8213/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51020"
,(lldb)     command script import "/tmp/0433E75C-0D11-453E-8EA6-BE44EC87F437/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 12:08:28.278 ThaliTest[2213:4719227] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/12D7E91C-C575-49BD-AB0F-7BA712F31383/Library/Cookies/Cookies.binarycookies
,2016-09-14 12:08:28.693 ThaliTest[2213:4719227] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 12:08:28.695 ThaliTest[2213:4719227] Multi-tasking -> Device: YES, App: YES
,2016-09-14 12:08:28.721 ThaliTest[2213:4719227] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 12:08:30.550 ThaliTest[2213:4719227] Using UIWebView
,2016-09-14 12:08:30.559 ThaliTest[2213:4719227] [CDVTimer][handleopenurl] 0.756979ms
,2016-09-14 12:08:30.568 ThaliTest[2213:4719227] [CDVTimer][intentandnavigationfilter] 8.077025ms
2016-09-14 12:08:30.569 ThaliTest[2213:4719227] [CDVTimer][gesturehandler] 0.410020ms
2016-09-14 12:08:30.569 ThaliTest[2213:4719227] [CDVTimer][TotalPluginS,tartup] 11.663020ms
,2016-09-14 12:08:36.622 ThaliTest[2213:4719227] Resetting plugins due to page load.
,2016-09-14 12:08:40.133 ThaliTest[2213:4719227] Finished load of: file:///var/mobile/Containers/Bundle/Application/8C7CF7D9-2852-43A5-9638-2072001E8213/ThaliTest.app/www/index.html
,2016-09-14 12:08:40.379 ThaliTest[2213:4719227] JXcore Cordova plugin initializing
,2016-09-14 12:08:40.380 ThaliTest[2213:4719450] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 12:08:48.443 ThaliTest[2213:4719450] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-14 12:08:48.444 ThaliTest[2213:4719450] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 12:08:48.445 ThaliTest[2213:4719450] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 12:08:48.447 ThaliTest[2213:4719450] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
