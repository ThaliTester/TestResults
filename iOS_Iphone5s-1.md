#### Test 850469116a90ff6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F1913106-24FA-444A-A7FB-F5144EA71A3A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F1913106-24FA-444A-A7FB-F5144EA71A3A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EB8CE40C-6D00-45A2-B5E2-101F02F92E02/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50050"
,(lldb)     command script import "/tmp/F1913106-24FA-444A-A7FB-F5144EA71A3A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 07:34:09.379 ThaliTest[2641:5616598] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2A6C790B-D149-445D-B776-BFAB7CC823C3/Library/Cookies/Cookies.binarycookies
,2016-09-20 07:34:09.841 ThaliTest[2641:5616598] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-20 07:34:09.843 ThaliTest[2641:5616598] Multi-tasking -> Device: YES, App: YES
,2016-09-20 07:34:09.868 ThaliTest[2641:5616598] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 07:34:11.868 ThaliTest[2641:5616598] Using UIWebView
,2016-09-20 07:34:11.876 ThaliTest[2641:5616598] [CDVTimer][handleopenurl] 0.476003ms
,2016-09-20 07:34:11.885 ThaliTest[2641:5616598] [CDVTimer][intentandnavigationfilter] 8.607030ms
2016-09-20 07:34:11.886 ThaliTest[2641:5616598] [CDVTimer][gesturehandler] 0.432014ms
2016-09-20 07:34:11.887 ThaliTest[2641:5616598] [CDVTimer][TotalPluginStartup] 11.403978ms
,2016-09-20 07:34:18.448 ThaliTest[2641:5616598] Resetting plugins due to page load.
,2016-09-20 07:34:22.087 ThaliTest[2641:5616598] Finished load of: file:///var/mobile/Containers/Bundle/Application/EB8CE40C-6D00-45A2-B5E2-101F02F92E02/ThaliTest.app/www/index.html
,2016-09-20 07:34:22.352 ThaliTest[2641:5616598] JXcore Cordova plugin initializing
,2016-09-20 07:34:22.353 ThaliTest[2641:5616837] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 07:34:30.772 ThaliTest[2641:5616837] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 07:34:30.773 ThaliTest[2641:5616837] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 07:34:30.773 ThaliTest[2641:5,616837] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 07:34:30.776 ThaliTest[2641:5616837] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 07:34:31.180 ThaliTest[2641:5616837] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003257989883422852
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
