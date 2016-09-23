#### Test 86482582895a768_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8D689B8D-CC22-4A36-BE79-3B4D19EE648E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8D689B8D-CC22-4A36-BE79-3B4D19EE648E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4F4C5C6A-2C05-4C18-8BFD-731E51B80E17/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62788"
,(lldb)     command script import "/tmp/8D689B8D-CC22-4A36-BE79-3B4D19EE648E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 16:58:17.819 ThaliTest[3109:6175021] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/87C615A6-FBA7-48B9-9420-4B4A2F1FC919/Library/Cookies/Cookies.binarycookies
,2016-09-23 16:58:17.927 ThaliTest[3109:6175021] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 16:58:17.929 ThaliTest[3109:6175021] Multi-tasking -> Device: YES, App: YES
,2016-09-23 16:58:17.948 ThaliTest[3109:6175021] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 16:58:19.475 ThaliTest[3109:6175021] Using UIWebView
,2016-09-23 16:58:19.484 ThaliTest[3109:6175021] [CDVTimer][handleopenurl] 0.712991ms
,2016-09-23 16:58:19.492 ThaliTest[3109:6175021] [CDVTimer][intentandnavigationfilter] 8.283019ms
2016-09-23 16:58:19.493 ThaliTest[3109:6175021] [CDVTimer][gesturehandler] 0.431001ms
2016-09-23 16:58:19.494 ThaliTest[3109:6175021] [CDVTimer][TotalPluginS,tartup] 11.354029ms
,2016-09-23 16:58:25.493 ThaliTest[3109:6175021] Resetting plugins due to page load.
,2016-09-23 16:58:29.093 ThaliTest[3109:6175021] Finished load of: file:///var/mobile/Containers/Bundle/Application/4F4C5C6A-2C05-4C18-8BFD-731E51B80E17/ThaliTest.app/www/index.html
,2016-09-23 16:58:29.395 ThaliTest[3109:6175021] JXcore Cordova plugin initializing
,2016-09-23 16:58:29.396 ThaliTest[3109:6175223] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15dfa7a10>
,Optional("9C5D9DDC-740E-44AF-90AA-2E776B6E483E")
,nil
,nil
,Optional("9F618F1D-2989-4F3D-A076-29584ACC8FFE")
,Optional("8341CFA7-9D5E-4467-BDB2-ADC7CA549177")
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 16:58:53.894 ThaliTest[3109:6175021] BTM: attaching to BTServer
,2016-09-23 16:58:54.596 ThaliTest[3109:6175021] BTM: local device power state changed
2016-09-23 16:58:54.597 ThaliTest[3109:6175021] BTM: power is now on
,2016-09-23 16:58:59.309 ThaliTest[3109:6175021] BTM: local device power state changed
2016-09-23 16:58:59.315 ThaliTest[3109:6175021] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  21.09622502326965
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered

```
