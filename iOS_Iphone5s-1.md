#### Test 81095569a7966ce_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/72D96C57-7737-468B-A1A4-CBAAB1998240/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/72D96C57-7737-468B-A1A4-CBAAB1998240/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/04E01C64-4C7D-4605-AAF8-2FC7D12049EB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49227"
,(lldb)     command script import "/tmp/72D96C57-7737-468B-A1A4-CBAAB1998240/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,error: libarclite_iphoneos.a(arclite.o) failed to load objfile for /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a
,2016-08-12 14:10:06.216 ThaliTest[219:26449] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D67DA4A-D6D9-4ED4-A8B2-2910554B70EE/Library/Cookies/Cookies.binarycookies
,2016-08-12 14:10:06.664 ThaliTest[219:26449] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-12 14:10:06.666 ThaliTest[219:26449] Multi-tasking -> Device: YES, App: YES
,2016-08-12 14:10:06.692 ThaliTest[219:26449] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-12 14:10:08.759 ThaliTest[219:26449] Using UIWebView
,2016-08-12 14:10:08.770 ThaliTest[219:26449] [CDVTimer][handleopenurl] 0.669003ms
,2016-08-12 14:10:08.779 ThaliTest[219:26449] [CDVTimer][intentandnavigationfilter] 8.230984ms
2016-08-12 14:10:08.780 ThaliTest[219:26449] [CDVTimer][gesturehandler] 0.413001ms
2016-08-12 14:10:08.780 ThaliTest[219:26449] [CDVTimer][TotalPluginStartup] 1,1.308968ms
,2016-08-12 14:10:16.143 ThaliTest[219:26449] Resetting plugins due to page load.
,2016-08-12 14:10:20.142 ThaliTest[219:26449] Finished load of: file:///var/mobile/Containers/Bundle/Application/04E01C64-4C7D-4605-AAF8-2FC7D12049EB/ThaliTest.app/www/index.html
,2016-08-12 14:10:20.385 ThaliTest[219:26449] JXcore Cordova plugin initializing
2016-08-12 14:10:20.386 ThaliTest[219:26664] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-12 14:10:29.005 ThaliTest[219:26664] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-12 14:10:29.006 ThaliTest[219:26664] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-12 14:10:29.007 ThaliTest[219:26664] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-12 14:10:29.009 ThaliTest[219:26664] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-12 14:10:29.356 ThaliTest[219:26664] Native method ExecuteNativeTests not found.
,Is Android:  false
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
