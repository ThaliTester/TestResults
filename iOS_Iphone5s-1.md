#### Test 79763830e2067e4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6C8E513F-B1AB-450B-83C8-2146944DCCAE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6C8E513F-B1AB-450B-83C8-2146944DCCAE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5D3FC811-5369-4804-ABB8-88247B801ABD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53337"
,(lldb)     command script import "/tmp/6C8E513F-B1AB-450B-83C8-2146944DCCAE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 14:15:53.503 ThaliTest[948:1957189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ACEBFD73-67AF-4923-BA08-BC383CC97370/Library/Cookies/Cookies.binarycookies
,2016-08-26 14:15:53.960 ThaliTest[948:1957189] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 14:15:53.961 ThaliTest[948:1957189] Multi-tasking -> Device: YES, App: YES
,2016-08-26 14:15:53.986 ThaliTest[948:1957189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 14:15:55.967 ThaliTest[948:1957189] Using UIWebView
,2016-08-26 14:15:55.978 ThaliTest[948:1957189] [CDVTimer][handleopenurl] 0.448048ms
,2016-08-26 14:15:55.987 ThaliTest[948:1957189] [CDVTimer][intentandnavigationfilter] 8.888006ms
2016-08-26 14:15:55.988 ThaliTest[948:1957189] [CDVTimer][gesturehandler] 0.409007ms
2016-08-26 14:15:55.989 ThaliTest[948:1957189] [CDVTimer][TotalPluginStar,tup] 11.708021ms
,2016-08-26 14:16:01.888 ThaliTest[948:1957189] Resetting plugins due to page load.
,2016-08-26 14:16:05.504 ThaliTest[948:1957189] Finished load of: file:///var/mobile/Containers/Bundle/Application/5D3FC811-5369-4804-ABB8-88247B801ABD/ThaliTest.app/www/index.html
,2016-08-26 14:16:05.776 ThaliTest[948:1957189] JXcore Cordova plugin initializing
,2016-08-26 14:16:05.777 ThaliTest[948:1957435] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 14:16:13.925 ThaliTest[948:1957435] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 14:16:13.926 ThaliTest[948:1957435] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 14:16:13.926 ThaliTest[948:1957,435] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 14:16:13.929 ThaliTest[948:1957435] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 14:16:14.317 ThaliTest[948:1957435] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01634699106216431
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
