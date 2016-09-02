#### Test 81418577ad1885e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/33D76B00-99A8-4096-942F-82F3F41A6247/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/33D76B00-99A8-4096-942F-82F3F41A6247/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/42730A3D-1455-451F-A6A6-8AC8DA3795D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55114"
,(lldb)     command script import "/tmp/33D76B00-99A8-4096-942F-82F3F41A6247/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 12:06:27.876 ThaliTest[1492:2988273] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C64DC71C-74B3-43B3-AD07-45330E8152C4/Library/Cookies/Cookies.binarycookies
,2016-09-02 12:06:28.287 ThaliTest[1492:2988273] Apache Cordova native platform version 4.1.1 is starting.
2016-09-02 12:06:28.289 ThaliTest[1492:2988273] Multi-tasking -> Device: YES, App: YES
,2016-09-02 12:06:28.309 ThaliTest[1492:2988273] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 12:06:29.957 ThaliTest[1492:2988273] Using UIWebView
,2016-09-02 12:06:29.965 ThaliTest[1492:2988273] [CDVTimer][handleopenurl] 0.458002ms
,2016-09-02 12:06:29.973 ThaliTest[1492:2988273] [CDVTimer][intentandnavigationfilter] 8.055985ms
2016-09-02 12:06:29.974 ThaliTest[1492:2988273] [CDVTimer][gesturehandler] 0.377953ms
2016-09-02 12:06:29.975 ThaliTest[1492:2988273] [CDVTimer][TotalPluginS,tartup] 10.771036ms
,2016-09-02 12:06:35.831 ThaliTest[1492:2988273] Resetting plugins due to page load.
,2016-09-02 12:06:38.748 ThaliTest[1492:2988273] Finished load of: file:///var/mobile/Containers/Bundle/Application/42730A3D-1455-451F-A6A6-8AC8DA3795D5/ThaliTest.app/www/index.html
,2016-09-02 12:06:38.999 ThaliTest[1492:2988273] JXcore Cordova plugin initializing
,2016-09-02 12:06:39.001 ThaliTest[1492:2988492] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-02 12:06:47.136 ThaliTest[1492:2988492] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-02 12:06:47.137 ThaliTest[1492:2988492] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-02 12:06:47.138 ThaliTest[1492:2988492] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-02 12:06:47.140 ThaliTest[1492:2988492] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-02 12:06:47.537 ThaliTest[1492:2988492] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004943966865539551
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
