#### Test 9835488260af434_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9835488260af434/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6C7A3854-98B1-4276-893D-A0A98BBBE343/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6C7A3854-98B1-4276-893D-A0A98BBBE343/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9835488260af434/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9835488260af434/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/36D24125-66C4-490F-A1B7-2B21DCC4288E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55134"
,(lldb)     command script import "/tmp/6C7A3854-98B1-4276-893D-A0A98BBBE343/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 12:53:01.229 ThaliTest[1043:1981714] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/954B84D2-1747-4DAD-896E-F92DF926DEDB/Library/Cookies/Cookies.binarycookies
,2016-12-19 12:53:01.363 ThaliTest[1043:1981714] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 12:53:01.364 ThaliTest[1043:1981714] Multi-tasking -> Device: YES, App: YES
,2016-12-19 12:53:01.387 ThaliTest[1043:1981714] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 12:53:02.603 ThaliTest[1043:1981714] Using UIWebView
,2016-12-19 12:53:02.614 ThaliTest[1043:1981714] [CDVTimer][handleopenurl] 0.454009ms
,2016-12-19 12:53:02.624 ThaliTest[1043:1981714] [CDVTimer][intentandnavigationfilter] 9.109020ms
2016-12-19 12:53:02.625 ThaliTest[1043:1981714] [CDVTimer][gesturehandler] 0.376999ms
2016-12-19 12:53:02.625 ThaliTest[1043:1981714] [CDVTimer][TotalPluginS,tartup] 11.897981ms
,2016-12-19 12:53:08.369 ThaliTest[1043:1981714] Resetting plugins due to page load.
,2016-12-19 12:53:11.733 ThaliTest[1043:1981714] Finished load of: file:///var/mobile/Containers/Bundle/Application/36D24125-66C4-490F-A1B7-2B21DCC4288E/ThaliTest.app/www/index.html
,2016-12-19 12:53:12.032 ThaliTest[1043:1981714] JXcore Cordova plugin initializing
,2016-12-19 12:53:12.033 ThaliTest[1043:1981931] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 11:53:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 11:53:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 11:53:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-19 11:53:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 11:53:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-19 11:53:50 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.48874300718307
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
