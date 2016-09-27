#### Test 85046911c0a96fd_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AEF381D8-E2C4-44FF-8782-771645EDFAA5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AEF381D8-E2C4-44FF-8782-771645EDFAA5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6B326701-CB99-4282-B52B-45F5D9221C85/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56555"
,(lldb)     command script import "/tmp/AEF381D8-E2C4-44FF-8782-771645EDFAA5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 13:05:19.860 ThaliTest[1541:2379397] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2E6838BA-5656-4BA8-97D2-172075112D9D/Library/Cookies/Cookies.binarycookies
,2016-09-27 13:05:19.936 ThaliTest[1541:2379397] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 13:05:19.938 ThaliTest[1541:2379397] Multi-tasking -> Device: YES, App: YES
,2016-09-27 13:05:19.956 ThaliTest[1541:2379397] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 13:05:20.481 ThaliTest[1541:2379397] Using UIWebView
,2016-09-27 13:05:20.492 ThaliTest[1541:2379397] [CDVTimer][handleopenurl] 0.395000ms
,2016-09-27 13:05:20.499 ThaliTest[1541:2379397] [CDVTimer][intentandnavigationfilter] 7.170975ms
2016-09-27 13:05:20.500 ThaliTest[1541:2379397] [CDVTimer][gesturehandler] 0.322044ms
2016-09-27 13:05:20.501 ThaliTest[1541:2379397] [CDVTimer][TotalPluginStartup] 9.611011ms
,2016-09-27 13:05:25.852 ThaliTest[1541:2379397] Resetting plugins due to page load.
,2016-09-27 13:05:26.225 ThaliTest[1541:2379397] Finished load of: file:///var/containers/Bundle/Application/6B326701-CB99-4282-B52B-45F5D9221C85/ThaliTest.app/www/index.html
,2016-09-27 13:05:26.562 ThaliTest[1541:2379397] JXcore Cordova plugin initializing
,2016-09-27 13:05:26.562 ThaliTest[1541:2379568] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x15e2096d0>
,Optional("36DC1D35-9027-42DD-A47B-74C81CD36729")
nil
,nil
,Optional("589FACCA-26A4-426E-AC92-C57DEF1BAC97")
,Optional("0E02FCC1-88CB-4B52-A252-C397DE8CCDF5")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.68348497152328
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
