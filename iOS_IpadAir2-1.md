#### Test 864825827cea8e2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7EEF79D2-207C-4F06-9C12-9F006A1B2714/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7EEF79D2-207C-4F06-9C12-9F006A1B2714/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0245A061-9766-44A8-8419-14E612E4352F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61176"
,(lldb)     command script import "/tmp/7EEF79D2-207C-4F06-9C12-9F006A1B2714/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 13:11:28.008 ThaliTest[3179:5579901] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6353F81E-D11B-484B-A97C-A0F8F9136DF2/Library/Cookies/Cookies.binarycookies
,2016-09-23 13:11:28.336 ThaliTest[3179:5579901] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 13:11:28.337 ThaliTest[3179:5579901] Multi-tasking -> Device: YES, App: YES
,2016-09-23 13:11:28.354 ThaliTest[3179:5579901] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 13:11:30.157 ThaliTest[3179:5579901] Using UIWebView
,2016-09-23 13:11:30.164 ThaliTest[3179:5579901] [CDVTimer][handleopenurl] 0.345051ms
,2016-09-23 13:11:30.171 ThaliTest[3179:5579901] [CDVTimer][intentandnavigationfilter] 6.322980ms
,2016-09-23 13:11:30.172 ThaliTest[3179:5579901] [CDVTimer][gesturehandler] 0.318050ms
2016-09-23 13:11:30.172 ThaliTest[3179:5579901] [CDVTimer][TotalPluginStartup] 8.568048ms
,2016-09-23 13:11:36.857 ThaliTest[3179:5579901] Resetting plugins due to page load.
,2016-09-23 13:11:40.401 ThaliTest[3179:5579901] Finished load of: file:///var/mobile/Containers/Bundle/Application/0245A061-9766-44A8-8419-14E612E4352F/ThaliTest.app/www/index.html
,2016-09-23 13:11:40.679 ThaliTest[3179:5579901] JXcore Cordova plugin initializing
,2016-09-23 13:11:40.680 ThaliTest[3179:5580146] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1468250d0>
,Optional("67E76199-E988-47EA-A1B3-B03E2267367B")
,nil
,nil
,Optional("BC2991B3-972B-4747-8195-5FDA287CAE6F")
,Optional("05C69735-0901-42AF-A308-AF0914BD5854")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 13:12:06.933 ThaliTest[3179:5579901] BTM: attaching to BTServer
,2016-09-23 13:12:07.736 ThaliTest[3179:5579901] BTM: local device power state changed
2016-09-23 13:12:07.737 ThaliTest[3179:5579901] BTM: power is now on
,2016-09-23 13:12:12.406 ThaliTest[3179:5579901] BTM: local device power state changed
2016-09-23 13:12:12.406 ThaliTest[3179:5579901] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.22612297534943
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
