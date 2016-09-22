#### Test 855258874296799_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8E26B946-E095-41FF-959B-F0191B628AE6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8E26B946-E095-41FF-959B-F0191B628AE6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1E8AB071-D1EC-49D1-9984-944846D639D0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51615"
,(lldb)     command script import "/tmp/8E26B946-E095-41FF-959B-F0191B628AE6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 14:06:22.636 ThaliTest[1188:1745465] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9D1C56FF-C4FB-44A2-9D18-2272D70ADA29/Library/Cookies/Cookies.binarycookies
,2016-09-22 14:06:22.676 ThaliTest[1188:1745465] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 14:06:22.677 ThaliTest[1188:1745465] Multi-tasking -> Device: YES, App: YES
,2016-09-22 14:06:22.689 ThaliTest[1188:1745465] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 14:06:23.052 ThaliTest[1188:1745465] Using UIWebView
,2016-09-22 14:06:23.057 ThaliTest[1188:1745465] [CDVTimer][handleopenurl] 0.280976ms
,2016-09-22 14:06:23.062 ThaliTest[1188:1745465] [CDVTimer][intentandnavigationfilter] 4.656971ms
2016-09-22 14:06:23.063 ThaliTest[1188:1745465] [CDVTimer][gesturehandler] 0.187039ms
2016-09-22 14:06:23.063 ThaliTest[1188:1745465] [CDVTimer][TotalPluginStartup] 6.276965ms
,2016-09-22 14:06:28.470 ThaliTest[1188:1745465] Resetting plugins due to page load.
,2016-09-22 14:06:28.787 ThaliTest[1188:1745465] Finished load of: file:///var/containers/Bundle/Application/1E8AB071-D1EC-49D1-9984-944846D639D0/ThaliTest.app/www/index.html
,2016-09-22 14:06:29.148 ThaliTest[1188:1745465] JXcore Cordova plugin initializing
,2016-09-22 14:06:29.149 ThaliTest[1188:1745638] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x147206080>
,Optional("9C017734-B6FC-4A87-A6DB-9965AF5E7B76")
,nil
,nil
,Optional("9B22DF5A-62F4-44F2-85B0-8F6F68407E15")
,Optional("6A060830-A148-4785-BC19-B04F8752BA7B")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 14:06:52.606 ThaliTest[1188:1745465] BTM: attaching to BTServer
,2016-09-22 14:06:53.335 ThaliTest[1188:1745465] BTM: local device power state changed
2016-09-22 14:06:53.336 ThaliTest[1188:1745465] BTM: power is now on
,2016-09-22 14:06:58.064 ThaliTest[1188:1745465] BTM: local device power state changed
2016-09-22 14:06:58.065 ThaliTest[1188:1745465] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  21.54278701543808
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
