#### Test 82894682da71698_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CB353621-0071-45CE-81D3-85279F8632AE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CB353621-0071-45CE-81D3-85279F8632AE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A297B058-4743-4BE5-B365-43C48B18680C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53408"
,(lldb)     command script import "/tmp/CB353621-0071-45CE-81D3-85279F8632AE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 00:03:54.821 ThaliTest[2073:4485266] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E20A560D-993A-44ED-B21D-D5A58D9D85E0/Library/Cookies/Cookies.binarycookies
,2016-09-13 00:03:54.884 ThaliTest[2073:4485266] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 00:03:54.885 ThaliTest[2073:4485266] Multi-tasking -> Device: YES, App: YES
,2016-09-13 00:03:54.901 ThaliTest[2073:4485266] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 00:03:55.684 ThaliTest[2073:4485266] Using UIWebView
,2016-09-13 00:03:55.688 ThaliTest[2073:4485266] [CDVTimer][handleopenurl] 0.149965ms
2016-09-13 00:03:55.691 ThaliTest[2073:4485266] [CDVTimer][intentandnavigationfilter] 2.744973ms
2016-09-13 00:03:55.692 ThaliTest[2073:4485266] [CDVTimer][gesturehandle,r] 0.140011ms
2016-09-13 00:03:55.692 ThaliTest[2073:4485266] [CDVTimer][TotalPluginStartup] 3.674984ms
,2016-09-13 00:03:58.725 ThaliTest[2073:4485266] Resetting plugins due to page load.
,2016-09-13 00:04:00.359 ThaliTest[2073:4485266] Finished load of: file:///var/mobile/Containers/Bundle/Application/A297B058-4743-4BE5-B365-43C48B18680C/ThaliTest.app/www/index.html
,2016-09-13 00:04:00.551 ThaliTest[2073:4485266] JXcore Cordova plugin initializing
,2016-09-13 00:04:00.552 ThaliTest[2073:4485433] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-13 00:04:47.785 ThaliTest[2073:4485266] BTM: attaching to BTServer
,2016-09-13 00:04:48.886 ThaliTest[2073:4485266] BTM: local device power state changed
2016-09-13 00:04:48.886 ThaliTest[2073:4485266] BTM: power is now off
,2016-09-13 00:04:49.683 ThaliTest[2073:4485266] BTM: local device power state changed
2016-09-13 00:04:49.684 ThaliTest[2073:4485266] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  40.45790499448776
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
