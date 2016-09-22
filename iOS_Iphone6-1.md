#### Test 8504691186bae88_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/03191EB6-BDA7-4E7A-8394-7277A3D37DE7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/03191EB6-BDA7-4E7A-8394-7277A3D37DE7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/CFFE3D97-7078-4FDA-8DE7-ED1F697B85F2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54935"
,(lldb)     command script import "/tmp/03191EB6-BDA7-4E7A-8394-7277A3D37DE7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 09:59:21.074 ThaliTest[1132:1717090] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7C2E8167-A784-4D90-8CB3-A07C6062FBEF/Library/Cookies/Cookies.binarycookies
,2016-09-22 09:59:21.149 ThaliTest[1132:1717090] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 09:59:21.150 ThaliTest[1132:1717090] Multi-tasking -> Device: YES, App: YES
,2016-09-22 09:59:21.170 ThaliTest[1132:1717090] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 09:59:21.638 ThaliTest[1132:1717090] Using UIWebView
,2016-09-22 09:59:21.645 ThaliTest[1132:1717090] [CDVTimer][handleopenurl] 0.418007ms
,2016-09-22 09:59:21.653 ThaliTest[1132:1717090] [CDVTimer][intentandnavigationfilter] 6.968021ms
2016-09-22 09:59:21.653 ThaliTest[1132:1717090] [CDVTimer][gesturehandler] 0.289977ms
2016-09-22 09:59:21.654 ThaliTest[1132:1717090] [CDVTimer][TotalPluginS,tartup] 9.329975ms
,2016-09-22 09:59:26.767 ThaliTest[1132:1717090] Resetting plugins due to page load.
,2016-09-22 09:59:27.134 ThaliTest[1132:1717090] Finished load of: file:///var/containers/Bundle/Application/CFFE3D97-7078-4FDA-8DE7-ED1F697B85F2/ThaliTest.app/www/index.html
,2016-09-22 09:59:27.463 ThaliTest[1132:1717090] JXcore Cordova plugin initializing
,2016-09-22 09:59:27.464 ThaliTest[1132:1717922] JXcore instance initializing
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
,2016-09-22 09:59:35.074 ThaliTest[1132:1717090] BTM: attaching to BTServer
,2016-09-22 09:59:35.821 ThaliTest[1132:1717090] BTM: local device power state changed
2016-09-22 09:59:35.822 ThaliTest[1132:1717090] BTM: power is now on
,2016-09-22 09:59:40.549 ThaliTest[1132:1717090] BTM: local device power state changed
,2016-09-22 09:59:40.550 ThaliTest[1132:1717090] BTM: power is now off
,received session: <ThaliCore.Session: 0x127e43560>
,Optional("1FE3D658-EA8F-4BC3-89FF-ABB60B34F105")
nil
,nil
,Optional("5A6E1D8F-D3E7-4AA4-9B75-AA85DC462C9A")
,Optional("FDF25BFE-0822-41A4-B5FA-5B1B73D59FE3")
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  20.05680400133133
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
