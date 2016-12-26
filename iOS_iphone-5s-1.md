#### Test 993736745bf9b5a_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993736745bf9b5a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B8347BC0-18DD-4110-9786-4E4922DF905F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B8347BC0-18DD-4110-9786-4E4922DF905F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993736745bf9b5a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993736745bf9b5a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F541D189-880E-4F21-914C-44301A39390F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63504"
,(lldb)     command script import "/tmp/B8347BC0-18DD-4110-9786-4E4922DF905F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 16:00:33.108 ThaliTest[1413:3051428] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8CF53FCA-78B5-483C-8FC4-32C0FE1AEBCC/Library/Cookies/Cookies.binarycookies
,2016-12-26 16:00:33.756 ThaliTest[1413:3051428] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 16:00:33.757 ThaliTest[1413:3051428] Multi-tasking -> Device: YES, App: YES
,2016-12-26 16:00:33.777 ThaliTest[1413:3051428] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 16:00:35.308 ThaliTest[1413:3051428] Using UIWebView
,2016-12-26 16:00:35.317 ThaliTest[1413:3051428] [CDVTimer][handleopenurl] 0.431001ms
,2016-12-26 16:00:35.328 ThaliTest[1413:3051428] [CDVTimer][intentandnavigationfilter] 10.168016ms
2016-12-26 16:00:35.329 ThaliTest[1413:3051428] [CDVTimer][gesturehandler] 0.419974ms
2016-12-26 16:00:35.329 ThaliTest[1413:3051428] [CDVTimer][TotalPlugin,Startup] 13.309002ms
,2016-12-26 16:00:41.143 ThaliTest[1413:3051428] Resetting plugins due to page load.
,2016-12-26 16:00:43.960 ThaliTest[1413:3051428] Finished load of: file:///var/mobile/Containers/Bundle/Application/F541D189-880E-4F21-914C-44301A39390F/ThaliTest.app/www/index.html
,2016-12-26 16:00:44.200 ThaliTest[1413:3051428] JXcore Cordova plugin initializing
,2016-12-26 16:00:44.201 ThaliTest[1413:3051639] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 15:00:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 15:00:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 15:00:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-26 15:00:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 15:00:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 15:01:23 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.96441102027893
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
