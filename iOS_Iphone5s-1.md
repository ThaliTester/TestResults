#### Test 8504691198a5312_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691198a5312/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3F8DA7CC-9EAD-4D8E-BCD7-A08BA0E14795/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3F8DA7CC-9EAD-4D8E-BCD7-A08BA0E14795/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691198a5312/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691198a5312/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6840156B-9605-43D8-A1B4-29733459190D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55470"
,(lldb)     command script import "/tmp/3F8DA7CC-9EAD-4D8E-BCD7-A08BA0E14795/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 08:58:58.673 ThaliTest[3224:6589648] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C210C410-2A6B-4886-A5DB-18134B349E2B/Library/Cookies/Cookies.binarycookies
,2016-09-26 08:58:58.791 ThaliTest[3224:6589648] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 08:58:58.793 ThaliTest[3224:6589648] Multi-tasking -> Device: YES, App: YES
,2016-09-26 08:58:58.813 ThaliTest[3224:6589648] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 08:59:00.786 ThaliTest[3224:6589648] Using UIWebView
,2016-09-26 08:59:00.795 ThaliTest[3224:6589648] [CDVTimer][handleopenurl] 0.478029ms
,2016-09-26 08:59:00.804 ThaliTest[3224:6589648] [CDVTimer][intentandnavigationfilter] 8.323014ms
2016-09-26 08:59:00.805 ThaliTest[3224:6589648] [CDVTimer][gesturehandler] 0.360966ms
2016-09-26 08:59:00.805 ThaliTest[3224:6589648] [CDVTimer][TotalPluginS,tartup] 11.201978ms
,2016-09-26 08:59:07.918 ThaliTest[3224:6589648] Resetting plugins due to page load.
,2016-09-26 08:59:12.042 ThaliTest[3224:6589648] Finished load of: file:///var/mobile/Containers/Bundle/Application/6840156B-9605-43D8-A1B4-29733459190D/ThaliTest.app/www/index.html
,2016-09-26 08:59:12.358 ThaliTest[3224:6589648] JXcore Cordova plugin initializing
,2016-09-26 08:59:12.359 ThaliTest[3224:6589870] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-26 08:59:21.474 ThaliTest[3224:6589648] BTM: attaching to BTServer
,2016-09-26 08:59:22.186 ThaliTest[3224:6589648] BTM: local device power state changed
2016-09-26 08:59:22.197 ThaliTest[3224:6589648] BTM: power is now on
,2016-09-26 08:59:26.937 ThaliTest[3224:6589648] BTM: local device power state changed
2016-09-26 08:59:26.938 ThaliTest[3224:6589648] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  7
Number of passed tests:  7
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.643468022346497
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
