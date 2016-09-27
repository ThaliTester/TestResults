#### Test 86891305c474d20_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8BBB7B75-4ADC-4E31-A36C-A03E4DAC0EDC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8BBB7B75-4ADC-4E31-A36C-A03E4DAC0EDC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D9E15A9E-4FAF-4EC3-A055-81589C74E1D7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56510"
,(lldb)     command script import "/tmp/8BBB7B75-4ADC-4E31-A36C-A03E4DAC0EDC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:58:33.306 ThaliTest[1533:2377927] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/06A73D2A-2726-488A-8E71-917A0785178C/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:58:33.346 ThaliTest[1533:2377927] Apache Cordova native platform version 4.2.1 is starting.
2016-09-27 12:58:33.347 ThaliTest[1533:2377927] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:58:33.363 ThaliTest[1533:2377927] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:58:33.671 ThaliTest[1533:2377927] Using UIWebView
,2016-09-27 12:58:33.676 ThaliTest[1533:2377927] [CDVTimer][handleopenurl] 0.194967ms
,2016-09-27 12:58:33.680 ThaliTest[1533:2377927] [CDVTimer][intentandnavigationfilter] 3.612995ms
2016-09-27 12:58:33.680 ThaliTest[1533:2377927] [CDVTimer][gesturehandler] 0.147045ms
2016-09-27 12:58:33.681 ThaliTest[1533:2377927] [CDVTimer][TotalPluginS,tartup] 4.800022ms
,2016-09-27 12:58:38.586 ThaliTest[1533:2377927] Resetting plugins due to page load.
,2016-09-27 12:58:38.956 ThaliTest[1533:2377927] Finished load of: file:///var/containers/Bundle/Application/D9E15A9E-4FAF-4EC3-A055-81589C74E1D7/ThaliTest.app/www/index.html
,2016-09-27 12:58:39.323 ThaliTest[1533:2377927] JXcore Cordova plugin initializing
,2016-09-27 12:58:39.324 ThaliTest[1533:2378106] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x158fc5940>
,Optional("4F3065A5-D85D-461C-8331-B1909148E050")
nil
,nil
,Optional("E60F34C0-EB58-4CB2-BA38-0092328E55F8")
,Optional("08FF9203-EEEB-4E48-9F09-4FE91ADD28AB")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  14.20987302064896
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
