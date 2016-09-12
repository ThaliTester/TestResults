#### Test 830701775d60530_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/37F3377C-F387-4C02-B9D8-FF00CB56E488/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/37F3377C-F387-4C02-B9D8-FF00CB56E488/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EF07D509-768C-4E0A-BF67-11C33114EF2C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58220"
,(lldb)     command script import "/tmp/37F3377C-F387-4C02-B9D8-FF00CB56E488/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 14:40:14.242 ThaliTest[2120:4148526] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/80819362-3345-472E-9843-C13EABA76CE0/Library/Cookies/Cookies.binarycookies
,2016-09-12 14:40:14.482 ThaliTest[2120:4148526] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 14:40:14.482 ThaliTest[2120:4148526] Multi-tasking -> Device: YES, App: YES
,2016-09-12 14:40:14.495 ThaliTest[2120:4148526] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 14:40:15.311 ThaliTest[2120:4148526] Using UIWebView
,2016-09-12 14:40:15.312 ThaliTest[2120:4148526] [CDVTimer][handleopenurl] 0.106990ms
,2016-09-12 14:40:15.315 ThaliTest[2120:4148526] [CDVTimer][intentandnavigationfilter] 1.908004ms
2016-09-12 14:40:15.315 ThaliTest[2120:4148526] [CDVTimer][gesturehandler] 0.081003ms
2016-09-12 14:40:15.315 ThaliTest[2120:4148526] [CDVTimer][TotalPluginS,tartup] 2.524018ms
,2016-09-12 14:40:18.380 ThaliTest[2120:4148526] Resetting plugins due to page load.
,2016-09-12 14:40:19.807 ThaliTest[2120:4148526] Finished load of: file:///var/mobile/Containers/Bundle/Application/EF07D509-768C-4E0A-BF67-11C33114EF2C/ThaliTest.app/www/index.html
,2016-09-12 14:40:19.935 ThaliTest[2120:4148526] JXcore Cordova plugin initializing
2016-09-12 14:40:19.936 ThaliTest[2120:4148698] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
,Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.84332400560379
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
