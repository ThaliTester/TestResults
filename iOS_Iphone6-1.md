#### Test 81418577ad1885e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/22A52A57-E7B4-40E2-A961-FB18A0CEF82A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/22A52A57-E7B4-40E2-A961-FB18A0CEF82A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7FE35526-F396-4A4A-A48B-EE0E02EAD41A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55111"
,(lldb)     command script import "/tmp/22A52A57-E7B4-40E2-A961-FB18A0CEF82A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 12:06:26.738 ThaliTest[1067:1562967] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8B1B57C6-E0C9-4FDA-99C3-203D312C27D0/Library/Cookies/Cookies.binarycookies
,2016-09-02 12:06:27.204 ThaliTest[1067:1562967] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 12:06:27.206 ThaliTest[1067:1562967] Multi-tasking -> Device: YES, App: YES
,2016-09-02 12:06:27.230 ThaliTest[1067:1562967] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 12:06:28.978 ThaliTest[1067:1562967] Using UIWebView
,2016-09-02 12:06:28.985 ThaliTest[1067:1562967] [CDVTimer][handleopenurl] 0.557005ms
,2016-09-02 12:06:28.993 ThaliTest[1067:1562967] [CDVTimer][intentandnavigationfilter] 7.189035ms
2016-09-02 12:06:28.993 ThaliTest[1067:1562967] [CDVTimer][gesturehandler] 0.349998ms
2016-09-02 12:06:28.994 ThaliTest[1067:1562967] [CDVTimer][TotalPluginS,tartup] 9.751022ms
,2016-09-02 12:06:34.972 ThaliTest[1067:1562967] Resetting plugins due to page load.
,2016-09-02 12:06:38.012 ThaliTest[1067:1562967] Finished load of: file:///var/mobile/Containers/Bundle/Application/7FE35526-F396-4A4A-A48B-EE0E02EAD41A/ThaliTest.app/www/index.html
,2016-09-02 12:06:38.241 ThaliTest[1067:1562967] JXcore Cordova plugin initializing
2016-09-02 12:06:38.241 ThaliTest[1067:1563214] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-02 12:06:45.189 ThaliTest[1067:1563214] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-02 12:06:45.190 ThaliTest[1067:1563214] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-02 12:06:45.190 ThaliTest[1067:1563214] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-02 12:06:45.192 ThaliTest[1067:1563214] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-02 12:06:45.520 ThaliTest[1067:1563214] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003738045692443848
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
