#### Test 85046911aebbc53_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/ACF7467D-30C7-4816-BF80-651206943A75/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/ACF7467D-30C7-4816-BF80-651206943A75/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B92686D2-CDEA-49F1-8896-348F068B0923/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53435"
,(lldb)     command script import "/tmp/ACF7467D-30C7-4816-BF80-651206943A75/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 09:43:34.363 ThaliTest[2962:5414185] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/600B8A9D-C48B-414E-B2A9-8EF4F621E355/Library/Cookies/Cookies.binarycookies
,2016-09-22 09:43:34.721 ThaliTest[2962:5414185] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 09:43:34.723 ThaliTest[2962:5414185] Multi-tasking -> Device: YES, App: YES
,2016-09-22 09:43:34.745 ThaliTest[2962:5414185] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 09:43:36.671 ThaliTest[2962:5414185] Using UIWebView
,2016-09-22 09:43:36.678 ThaliTest[2962:5414185] [CDVTimer][handleopenurl] 0.310004ms
,2016-09-22 09:43:36.685 ThaliTest[2962:5414185] [CDVTimer][intentandnavigationfilter] 6.855011ms
,2016-09-22 09:43:36.686 ThaliTest[2962:5414185] [CDVTimer][gesturehandler] 0.322998ms
,2016-09-22 09:43:36.686 ThaliTest[2962:5414185] [CDVTimer][TotalPluginStartup] 9.021997ms
,2016-09-22 09:43:43.105 ThaliTest[2962:5414185] Resetting plugins due to page load.
,2016-09-22 09:43:46.071 ThaliTest[2962:5414185] Finished load of: file:///var/mobile/Containers/Bundle/Application/B92686D2-CDEA-49F1-8896-348F068B0923/ThaliTest.app/www/index.html
,2016-09-22 09:43:46.280 ThaliTest[2962:5414185] JXcore Cordova plugin initializing
,2016-09-22 09:43:46.280 ThaliTest[2962:5414457] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1609d0b50>
,Optional("0EA2DFD9-BB73-4F36-81DD-46DC359E7C57")
,nil
,nil
,Optional("317CFF86-788D-4F21-B257-A80E84C121BB")
,Optional("CF878DAE-6EA9-4385-92AD-BDB0D1E9C844")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 09:44:12.329 ThaliTest[2962:5414185] BTM: attaching to BTServer
,2016-09-22 09:44:13.149 ThaliTest[2962:5414185] BTM: local device power state changed
2016-09-22 09:44:13.150 ThaliTest[2962:5414185] BTM: power is now on
,2016-09-22 09:44:17.821 ThaliTest[2962:5414185] BTM: local device power state changed
2016-09-22 09:44:17.822 ThaliTest[2962:5414185] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.03609198331833
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
