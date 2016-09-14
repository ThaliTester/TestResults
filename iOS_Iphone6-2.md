#### Test 8526390230c731c_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/820B9650-B280-4C9F-84FE-AD4CFAC034D4/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/820B9650-B280-4C9F-84FE-AD4CFAC034D4/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F70E7877-5BF0-410D-BA0A-375BC9FE915D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50166"
,(lldb)     command script import "/tmp/820B9650-B280-4C9F-84FE-AD4CFAC034D4/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 13:57:38.729 ThaliTest[744:800085] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3D65D66-9733-48DC-816D-08784439C14D/Library/Cookies/Cookies.binarycookies
,2016-09-14 13:57:38.766 ThaliTest[744:800085] Apache Cordova native platform version 4.1.1 is starting.
2016-09-14 13:57:38.767 ThaliTest[744:800085] Multi-tasking -> Device: YES, App: YES
,2016-09-14 13:57:38.780 ThaliTest[744:800085] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 13:57:39.096 ThaliTest[744:800085] Using UIWebView
2016-09-14 13:57:39.099 ThaliTest[744:800085] [CDVTimer][handleopenurl] 0.177979ms
,2016-09-14 13:57:39.104 ThaliTest[744:800085] [CDVTimer][intentandnavigationfilter] 4.240990ms
2016-09-14 13:57:39.104 ThaliTest[744:800085] [CDVTimer][gesturehandler] 0.140011ms
2016-09-14 13:57:39.104 ThaliTest[744:800085] [CDVTimer][TotalPluginStartup,] 5.312979ms
,2016-09-14 13:57:44.578 ThaliTest[744:800085] Resetting plugins due to page load.
,2016-09-14 13:57:45.090 ThaliTest[744:800085] Finished load of: file:///var/containers/Bundle/Application/F70E7877-5BF0-410D-BA0A-375BC9FE915D/ThaliTest.app/www/index.html
,2016-09-14 13:57:45.563 ThaliTest[744:800085] JXcore Cordova plugin initializing
,2016-09-14 13:57:45.563 ThaliTest[744:800248] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x162629570>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 13:58:08.958 ThaliTest[744:800085] BTM: attaching to BTServer
,2016-09-14 13:58:10.116 ThaliTest[744:800085] BTM: local device power state changed
2016-09-14 13:58:10.121 ThaliTest[744:800085] BTM: power is now off
,2016-09-14 13:58:10.879 ThaliTest[744:800085] BTM: local device power state changed
2016-09-14 13:58:10.882 ThaliTest[744:800085] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  51
Number of passed tests:  51
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  18.01497900485992
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
