#### Test 83268893919c9ad_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2B744427-C779-4AEF-B802-29AE33AF39F1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2B744427-C779-4AEF-B802-29AE33AF39F1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D58BB9C5-A301-49F6-B548-9B7FEC35173F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57917"
,(lldb)     command script import "/tmp/2B744427-C779-4AEF-B802-29AE33AF39F1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 10:31:49.345 ThaliTest[1148:1722344] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41D51F7F-3B10-4167-B2E4-B8703C6B54EB/Library/Cookies/Cookies.binarycookies
,2016-09-22 10:31:49.382 ThaliTest[1148:1722344] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 10:31:49.383 ThaliTest[1148:1722344] Multi-tasking -> Device: YES, App: YES
,2016-09-22 10:31:49.397 ThaliTest[1148:1722344] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 10:31:49.726 ThaliTest[1148:1722344] Using UIWebView
2016-09-22 10:31:49.729 ThaliTest[1148:1722344] [CDVTimer][handleopenurl] 0.151992ms
,2016-09-22 10:31:49.734 ThaliTest[1148:1722344] [CDVTimer][intentandnavigationfilter] 4.619956ms
2016-09-22 10:31:49.734 ThaliTest[1148:1722344] [CDVTimer][gesturehandler] 0.150979ms
2016-09-22 10:31:49.735 ThaliTest[1148:1722344] [CDVTimer][TotalPluginStartup] 5.662024ms
,2016-09-22 10:31:54.908 ThaliTest[1148:1722344] Resetting plugins due to page load.
,2016-09-22 10:31:55.292 ThaliTest[1148:1722344] Finished load of: file:///var/containers/Bundle/Application/D58BB9C5-A301-49F6-B548-9B7FEC35173F/ThaliTest.app/www/index.html
,2016-09-22 10:31:55.628 ThaliTest[1148:1722344] JXcore Cordova plugin initializing
,2016-09-22 10:31:55.629 ThaliTest[1148:1722509] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x15e9e05f0>
,Optional("01C64F42-74EE-47AD-9C9E-76B84958C7D8")
nil
,nil
,Optional("25EE2223-4D04-4C5E-929A-DA24C1E0152A")
,Optional("D74C0557-E4E8-4560-953E-AC84EEBAE01E")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 10:32:17.920 ThaliTest[1148:1722344] BTM: attaching to BTServer
,2016-09-22 10:32:18.667 ThaliTest[1148:1722344] BTM: local device power state changed
2016-09-22 10:32:18.668 ThaliTest[1148:1722344] BTM: power is now on
,2016-09-22 10:32:23.377 ThaliTest[1148:1722344] BTM: local device power state changed
,2016-09-22 10:32:23.378 ThaliTest[1148:1722344] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.2049640417099
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
