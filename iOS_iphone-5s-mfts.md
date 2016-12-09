#### Test 97333091bbfd026_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/97333091bbfd026/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/56674488-6CB0-4242-990A-F7A39599D97D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/56674488-6CB0-4242-990A-F7A39599D97D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/97333091bbfd026/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/97333091bbfd026/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0F01425F-8E56-4CB6-ACC2-AF712769625F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63553"
,(lldb)     command script import "/tmp/56674488-6CB0-4242-990A-F7A39599D97D/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-09 17:24:37.763 ThaliTest[460:389995] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0281CD69-2A5F-41B8-AE97-BB732D315D5A/Library/Cookies/Cookies.binarycookies
,2016-12-09 17:24:37.857 ThaliTest[460:389995] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-09 17:24:37.859 ThaliTest[460:389995] Multi-tasking -> Device: YES, App: YES
,2016-12-09 17:24:37.878 ThaliTest[460:389995] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-09 17:24:38.444 ThaliTest[460:389995] Using UIWebView
,2016-12-09 17:24:38.456 ThaliTest[460:389995] [CDVTimer][handleopenurl] 0.446975ms
,2016-12-09 17:24:38.467 ThaliTest[460:389995] [CDVTimer][intentandnavigationfilter] 10.298014ms
2016-12-09 17:24:38.468 ThaliTest[460:389995] [CDVTimer][gesturehandler] 0.432968ms
2016-12-09 17:24:38.468 ThaliTest[460:389995] [CDVTimer][TotalPluginStartu,p] 13.132036ms
,2016-12-09 17:24:44.910 ThaliTest[460:389995] Resetting plugins due to page load.
,2016-12-09 17:24:45.382 ThaliTest[460:389995] Finished load of: file:///var/containers/Bundle/Application/0F01425F-8E56-4CB6-ACC2-AF712769625F/ThaliTest.app/www/index.html
,2016-12-09 17:24:45.781 ThaliTest[460:389995] JXcore Cordova plugin initializing
2016-12-09 17:24:45.782 ThaliTest[460:390172] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-09 16:24:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-09 16:24:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-09 16:24:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-09 16:24:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-09 16:24:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-09 16:25:23 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.92937505245209
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
