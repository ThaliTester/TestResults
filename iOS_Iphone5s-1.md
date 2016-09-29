#### Test 87116923b621cb4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F2286ABE-4861-4B7F-919C-3DB91330B2B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F2286ABE-4861-4B7F-919C-3DB91330B2B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/617C83B6-502C-4017-A554-117DFE330B84/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49307"
,(lldb)     command script import "/tmp/F2286ABE-4861-4B7F-919C-3DB91330B2B0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 10:18:59.377 ThaliTest[3507:7092171] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/15D08561-CDC7-460D-B7B1-28025C859EBF/Library/Cookies/Cookies.binarycookies
,2016-09-29 10:18:59.494 ThaliTest[3507:7092171] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 10:18:59.496 ThaliTest[3507:7092171] Multi-tasking -> Device: YES, App: YES
,2016-09-29 10:18:59.519 ThaliTest[3507:7092171] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 10:19:00.911 ThaliTest[3507:7092171] Using UIWebView
2016-09-29 10:19:00.919 ThaliTest[3507:7092171] [CDVTimer][handleopenurl] 0.461996ms
2016-09-29 10:19:00.928 ThaliTest[3507:7092171] [CDVTimer][intentandnavigationfilter] 8.457005ms
2016-09,-29 10:19:00.929 ThaliTest[3507:7092171] [CDVTimer][gesturehandler] 0.423968ms
2016-09-29 10:19:00.929 ThaliTest[3507:7092171] [CDVTimer][TotalPluginStartup] 11.027992ms
,2016-09-29 10:19:06.864 ThaliTest[3507:7092171] Resetting plugins due to page load.
,2016-09-29 10:19:10.259 ThaliTest[3507:7092171] Finished load of: file:///var/mobile/Containers/Bundle/Application/617C83B6-502C-4017-A554-117DFE330B84/ThaliTest.app/www/index.html
,2016-09-29 10:19:10.574 ThaliTest[3507:7092171] JXcore Cordova plugin initializing
,2016-09-29 10:19:10.575 ThaliTest[3507:7092374] JXcore instance initializing
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
,Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  54
Number of passed tests:  54
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  17.98771703243256
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
