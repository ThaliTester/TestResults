#### Test 104512680d43a431_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/104512680d43a431/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/BF6256F9-FE1C-4F88-A5FA-8816E7DF69D0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BF6256F9-FE1C-4F88-A5FA-8816E7DF69D0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/104512680d43a431/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/104512680d43a431/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6C0C2E24-AF53-4B18-BFFB-13E9741DFC79/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60380"
,(lldb)     command script import "/tmp/BF6256F9-FE1C-4F88-A5FA-8816E7DF69D0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-03 13:48:41.279 ThaliTest[3262:8604029] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/55FE0F6C-8043-49C1-B292-B9B8545E356B/Library/Cookies/Cookies.binarycookies
,2017-02-03 13:48:41.401 ThaliTest[3262:8604029] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-03 13:48:41.402 ThaliTest[3262:8604029] Multi-tasking -> Device: YES, App: YES
,2017-02-03 13:48:41.425 ThaliTest[3262:8604029] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-03 13:48:42.912 ThaliTest[3262:8604029] Using UIWebView
,2017-02-03 13:48:42.921 ThaliTest[3262:8604029] [CDVTimer][handleopenurl] 0.501037ms
,2017-02-03 13:48:42.929 ThaliTest[3262:8604029] [CDVTimer][intentandnavigationfilter] 8.116961ms
2017-02-03 13:48:42.930 ThaliTest[3262:8604029] [CDVTimer][gesturehandler] 0.351965ms
2017-02-03 13:48:42.931 ThaliTest[3262:8604029] [CDVTimer][TotalPluginS,tartup] 11.236966ms
,2017-02-03 13:48:48.609 ThaliTest[3262:8604029] Resetting plugins due to page load.
,2017-02-03 13:48:51.836 ThaliTest[3262:8604029] Finished load of: file:///var/mobile/Containers/Bundle/Application/6C0C2E24-AF53-4B18-BFFB-13E9741DFC79/ThaliTest.app/www/index.html
,2017-02-03 13:48:52.131 ThaliTest[3262:8604029] JXcore Cordova plugin initializing
,2017-02-03 13:48:52.132 ThaliTest[3262:8604243] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-03 12:49:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-03 12:49:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-03 12:49:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-02-03 12:49:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-03 12:49:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-03 12:49:32 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.69708997011185
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
