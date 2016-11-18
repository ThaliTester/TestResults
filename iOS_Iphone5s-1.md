#### Test 9215228616bd023_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9215228616bd023/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/9A614320-4C13-4DBB-8DB3-63194231A784/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9A614320-4C13-4DBB-8DB3-63194231A784/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9215228616bd023/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9215228616bd023/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BF97C06D-32FC-4C17-A898-C990308A6243/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60349"
,(lldb)     command script import "/tmp/9A614320-4C13-4DBB-8DB3-63194231A784/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 13:30:20.743 ThaliTest[5930:15020108] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B9E09A7A-FD9A-4790-AD00-3B1C92384DF8/Library/Cookies/Cookies.binarycookies
,2016-11-18 13:30:20.806 ThaliTest[5930:15020108] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 13:30:20.807 ThaliTest[5930:15020108] Multi-tasking -> Device: YES, App: YES
,2016-11-18 13:30:20.825 ThaliTest[5930:15020108] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 13:30:21.672 ThaliTest[5930:15020108] Using UIWebView
,2016-11-18 13:30:21.676 ThaliTest[5930:15020108] [CDVTimer][handleopenurl] 0.191987ms
2016-11-18 13:30:21.679 ThaliTest[5930:15020108] [CDVTimer][intentandnavigationfilter] 2.789974ms
2016-11-18 13:30:21.679 ThaliTest[5930:15020108] [CDVTimer][gesturehan,dler] 0.129998ms
2016-11-18 13:30:21.680 ThaliTest[5930:15020108] [CDVTimer][TotalPluginStartup] 3.919005ms
,2016-11-18 13:30:24.928 ThaliTest[5930:15020108] Resetting plugins due to page load.
,2016-11-18 13:30:26.483 ThaliTest[5930:15020108] Finished load of: file:///var/mobile/Containers/Bundle/Application/BF97C06D-32FC-4C17-A898-C990308A6243/ThaliTest.app/www/index.html
,2016-11-18 13:30:26.684 ThaliTest[5930:15020108] JXcore Cordova plugin initializing
2016-11-18 13:30:26.685 ThaliTest[5930:15020280] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 12:30:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 12:30:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 12:30:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-18 12:30:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 12:30:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 12:30:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-18 12:31:04 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.64924997091293
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
