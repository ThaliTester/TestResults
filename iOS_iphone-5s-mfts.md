#### Test 995727499fee306_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1D001B0A-B0E2-4343-B6A7-DF794E64C10C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/1D001B0A-B0E2-4343-B6A7-DF794E64C10C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4520941C-46F4-4D9C-8F97-E6027149987F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55713"
,(lldb)     command script import "/tmp/1D001B0A-B0E2-4343-B6A7-DF794E64C10C/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 11:35:16.761 ThaliTest[1578:3307269] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B61C7CFB-821D-43F7-9246-E1E3C714366C/Library/Cookies/Cookies.binarycookies
,2017-01-03 11:35:16.808 ThaliTest[1578:3307269] Apache Cordova native platform version 4.3.1 is starting.
2017-01-03 11:35:16.809 ThaliTest[1578:3307269] Multi-tasking -> Device: YES, App: YES
,2017-01-03 11:35:16.822 ThaliTest[1578:3307269] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 11:35:17.145 ThaliTest[1578:3307269] Using UIWebView
,2017-01-03 11:35:17.149 ThaliTest[1578:3307269] [CDVTimer][handleopenurl] 0.283003ms
,2017-01-03 11:35:17.156 ThaliTest[1578:3307269] [CDVTimer][intentandnavigationfilter] 5.776048ms
2017-01-03 11:35:17.156 ThaliTest[1578:3307269] [CDVTimer][gesturehandler] 0.193000ms
2017-01-03 11:35:17.156 ThaliTest[1578:3307269] [CDVTimer][TotalPluginS,tartup] 7.285953ms
,2017-01-03 11:35:23.433 ThaliTest[1578:3307269] Resetting plugins due to page load.
,2017-01-03 11:35:23.816 ThaliTest[1578:3307269] Finished load of: file:///var/containers/Bundle/Application/4520941C-46F4-4D9C-8F97-E6027149987F/ThaliTest.app/www/index.html
,2017-01-03 11:35:24.222 ThaliTest[1578:3307269] JXcore Cordova plugin initializing
,2017-01-03 11:35:24.223 ThaliTest[1578:3307447] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 10:35:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-03 10:35:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 10:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-03 10:35:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-03 10:35:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)

```
