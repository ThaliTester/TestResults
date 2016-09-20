#### Test 852639026a23328_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/529BC968-A15B-4D72-AE6B-9E1D39CC46C7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/529BC968-A15B-4D72-AE6B-9E1D39CC46C7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/31880870-FDB2-41BE-AB4E-41E78700CCC6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61105"
,(lldb)     command script import "/tmp/529BC968-A15B-4D72-AE6B-9E1D39CC46C7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 14:46:04.785 ThaliTest[2694:5669230] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F4FED36-06F5-4E10-92A5-8323608CEEBA/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:46:05.421 ThaliTest[2694:5669230] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:46:05.422 ThaliTest[2694:5669230] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:46:05.444 ThaliTest[2694:5669230] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:46:06.956 ThaliTest[2694:5669230] Using UIWebView
,2016-09-20 14:46:06.965 ThaliTest[2694:5669230] [CDVTimer][handleopenurl] 0.513971ms
,2016-09-20 14:46:06.974 ThaliTest[2694:5669230] [CDVTimer][intentandnavigationfilter] 8.489966ms
2016-09-20 14:46:06.975 ThaliTest[2694:5669230] [CDVTimer][gesturehandler] 0.421047ms
2016-09-20 14:46:06.975 ThaliTest[2694:5669230] [CDVTimer][TotalPluginS,tartup] 11.328995ms
,2016-09-20 14:46:12.831 ThaliTest[2694:5669230] Resetting plugins due to page load.
,2016-09-20 14:46:15.584 ThaliTest[2694:5669230] Finished load of: file:///var/mobile/Containers/Bundle/Application/31880870-FDB2-41BE-AB4E-41E78700CCC6/ThaliTest.app/www/index.html
,2016-09-20 14:46:15.909 ThaliTest[2694:5669230] JXcore Cordova plugin initializing
,2016-09-20 14:46:15.910 ThaliTest[2694:5669434] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-20 14:46:24.986 ThaliTest[2694:5669230] BTM: attaching to BTServer
,2016-09-20 14:46:29.581 ThaliTest[2694:5669230] BTM: local device power state changed
2016-09-20 14:46:29.584 ThaliTest[2694:5669230] BTM: power is now off
,2016-09-20 14:46:30.273 ThaliTest[2694:5669230] BTM: local device power state changed
2016-09-20 14:46:30.274 ThaliTest[2694:5669230] BTM: power is now on
,received session: <ThaliCore.Session: 0x10982a9b0>
,Optional("AF3381C5-D214-42A3-8E25-DA9745B47595")
,nil
,nil
,Optional("A22DCB99-8275-4569-A8CA-6E64518719B2")
,Optional("56D2FC8E-FDE2-4D54-8D3C-7E2189E50628")
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  18.37980300188065
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
