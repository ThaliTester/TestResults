#### Test 85960304ae0496b_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/59A9AD43-D2BF-42C8-83A0-84FC4E609053/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/59A9AD43-D2BF-42C8-83A0-84FC4E609053/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8D50EBE4-C744-4452-85D5-E59E3EBA2F30/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58076"
,(lldb)     command script import "/tmp/59A9AD43-D2BF-42C8-83A0-84FC4E609053/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-20 05:11:21.266 ThaliTest[1115:1427661] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AC2F9A1F-A56C-4458-AB0C-121EBAB25017/Library/Cookies/Cookies.binarycookies
,2016-09-20 05:11:21.616 ThaliTest[1115:1427661] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 05:11:21.618 ThaliTest[1115:1427661] Multi-tasking -> Device: YES, App: YES
,2016-09-20 05:11:21.643 ThaliTest[1115:1427661] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 05:11:22.177 ThaliTest[1115:1427661] Using UIWebView
,2016-09-20 05:11:22.183 ThaliTest[1115:1427661] [CDVTimer][handleopenurl] 0.380993ms
,2016-09-20 05:11:22.191 ThaliTest[1115:1427661] [CDVTimer][intentandnavigationfilter] 7.322013ms
2016-09-20 05:11:22.192 ThaliTest[1115:1427661] [CDVTimer][gesturehandler] 0.304043ms
2016-09-20 05:11:22.192 ThaliTest[1115:1427661] [CDVTimer][TotalPluginS,tartup] 9.743035ms
,2016-09-20 05:11:27.730 ThaliTest[1115:1427661] Resetting plugins due to page load.
,2016-09-20 05:11:28.126 ThaliTest[1115:1427661] Finished load of: file:///var/containers/Bundle/Application/8D50EBE4-C744-4452-85D5-E59E3EBA2F30/ThaliTest.app/www/index.html
,2016-09-20 05:11:28.601 ThaliTest[1115:1427661] JXcore Cordova plugin initializing
,2016-09-20 05:11:28.602 ThaliTest[1115:1427835] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 05:11:35.339 ThaliTest[1115:1427835] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 05:11:35.340 ThaliTest[1115:1427835] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 05:11:35.340 ThaliTest[1115:1,427835] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 05:11:35.342 ThaliTest[1115:1427835] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 05:11:35.749 ThaliTest[1115:1427835] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.002691984176635742
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
