#### Test 852639026a23328_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2F6E8C2B-D72B-4C0C-A9F5-312CC82B535E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2F6E8C2B-D72B-4C0C-A9F5-312CC82B535E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/64C2454F-59D0-4098-83F4-B3B6ABA12C44/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61052"
,(lldb)     command script import "/tmp/2F6E8C2B-D72B-4C0C-A9F5-312CC82B535E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 14:45:59.512 ThaliTest[974:1485918] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/363651E0-0ECC-4D19-9E97-7A0BD2497DA3/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:45:59.592 ThaliTest[974:1485918] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:45:59.595 ThaliTest[974:1485918] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:45:59.617 ThaliTest[974:1485918] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:46:00.141 ThaliTest[974:1485918] Using UIWebView
,2016-09-20 14:46:00.151 ThaliTest[974:1485918] [CDVTimer][handleopenurl] 0.396013ms
,2016-09-20 14:46:00.159 ThaliTest[974:1485918] [CDVTimer][intentandnavigationfilter] 7.044971ms
2016-09-20 14:46:00.159 ThaliTest[974:1485918] [CDVTimer][gesturehandler] 0.290036ms
2016-09-20 14:46:00.160 ThaliTest[974:1485918] [CDVTimer][TotalPluginStar,tup] 9.436965ms
,2016-09-20 14:46:05.345 ThaliTest[974:1485918] Resetting plugins due to page load.
,2016-09-20 14:46:05.688 ThaliTest[974:1485918] Finished load of: file:///var/containers/Bundle/Application/64C2454F-59D0-4098-83F4-B3B6ABA12C44/ThaliTest.app/www/index.html
,2016-09-20 14:46:06.096 ThaliTest[974:1485918] JXcore Cordova plugin initializing
,2016-09-20 14:46:06.097 ThaliTest[974:1486081] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x136f66b10>
,Optional("DCC64904-FB77-42B0-BAD3-BEFF64B844C7")
nil
,nil
,Optional("74C89D9C-6829-43D5-9672-1AD9620A866B")
,Optional("FF9A6E17-175A-4934-9DBB-71E866750C43")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-20 14:46:27.637 ThaliTest[974:1485918] BTM: attaching to BTServer
,2016-09-20 14:46:28.385 ThaliTest[974:1485918] BTM: local device power state changed
2016-09-20 14:46:28.386 ThaliTest[974:1485918] BTM: power is now on
,2016-09-20 14:46:33.107 ThaliTest[974:1485918] BTM: local device power state changed
2016-09-20 14:46:33.108 ThaliTest[974:1485918] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.6834619641304
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
