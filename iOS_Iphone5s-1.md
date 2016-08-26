#### Test 82894682a24f9af_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4452ACF3-E03F-4A45-820C-939241701CD3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4452ACF3-E03F-4A45-820C-939241701CD3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8F2DA0EA-9716-4611-A979-A66E21116013/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51619"
,(lldb)     command script import "/tmp/4452ACF3-E03F-4A45-820C-939241701CD3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 17:35:58.381 ThaliTest[973:1980835] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/578156F4-7DA8-48F6-AC8A-6D3F3E8C2B9C/Library/Cookies/Cookies.binarycookies
,2016-08-26 17:35:58.821 ThaliTest[973:1980835] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 17:35:58.822 ThaliTest[973:1980835] Multi-tasking -> Device: YES, App: YES
,2016-08-26 17:35:58.843 ThaliTest[973:1980835] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 17:36:00.526 ThaliTest[973:1980835] Using UIWebView
,2016-08-26 17:36:00.534 ThaliTest[973:1980835] [CDVTimer][handleopenurl] 0.472963ms
,2016-08-26 17:36:00.543 ThaliTest[973:1980835] [CDVTimer][intentandnavigationfilter] 8.082032ms
2016-08-26 17:36:00.544 ThaliTest[973:1980835] [CDVTimer][gesturehandler] 0.402987ms
2016-08-26 17:36:00.544 ThaliTest[973:1980835] [CDVTimer][TotalPluginStar,tup] 10.887980ms
,2016-08-26 17:36:06.816 ThaliTest[973:1980835] Resetting plugins due to page load.
,2016-08-26 17:36:09.929 ThaliTest[973:1980835] Finished load of: file:///var/mobile/Containers/Bundle/Application/8F2DA0EA-9716-4611-A979-A66E21116013/ThaliTest.app/www/index.html
,2016-08-26 17:36:09.945 ThaliTest[973:1980835] JXcore Cordova plugin initializing
,2016-08-26 17:36:09.947 ThaliTest[973:1981053] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","wifi":"on","bluetoothLowEnergy":"off","bluetooth":"off"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
,Total number of executed tests:  5
Number of passed tests:  5
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.00795900821685791
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
