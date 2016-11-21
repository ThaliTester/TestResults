#### Test 94626375b5fe2b0_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/ECAE02F4-9250-4049-8FF1-35C55A476195/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/ECAE02F4-9250-4049-8FF1-35C55A476195/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/08E22B41-D9EF-4FF5-862D-C1C44EDEDAB4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61069"
,(lldb)     command script import "/tmp/ECAE02F4-9250-4049-8FF1-35C55A476195/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 08:37:58.643 ThaliTest[3869:8718824] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2BB9F23E-6D83-439F-9E3B-9FD040665D05/Library/Cookies/Cookies.binarycookies
,2016-11-21 08:37:58.680 ThaliTest[3869:8718824] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 08:37:58.680 ThaliTest[3869:8718824] Multi-tasking -> Device: YES, App: YES
,2016-11-21 08:37:58.692 ThaliTest[3869:8718824] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 08:37:59.010 ThaliTest[3869:8718824] Using UIWebView
,2016-11-21 08:37:59.014 ThaliTest[3869:8718824] [CDVTimer][handleopenurl] 0.272989ms
,2016-11-21 08:37:59.018 ThaliTest[3869:8718824] [CDVTimer][intentandnavigationfilter] 3.382981ms
2016-11-21 08:37:59.018 ThaliTest[3869:8718824] [CDVTimer][gesturehandler] 0.155985ms
2016-11-21 08:37:59.018 ThaliTest[3869:8718824] [CDVTimer][TotalPluginStartup] 4.598022ms
,2016-11-21 08:38:04.729 ThaliTest[3869:8718824] Resetting plugins due to page load.
,2016-11-21 08:38:05.184 ThaliTest[3869:8718824] Finished load of: file:///var/containers/Bundle/Application/08E22B41-D9EF-4FF5-862D-C1C44EDEDAB4/ThaliTest.app/www/index.html
,2016-11-21 08:38:05.536 ThaliTest[3869:8718824] JXcore Cordova plugin initializing
,2016-11-21 08:38:05.536 ThaliTest[3869:8719004] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 16:38:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 16:38:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 16:38:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 16:38:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 16:38:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 16:38:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-11-21 16:38:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)

```
