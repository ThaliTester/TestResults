#### Test 50242285feafdeb_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5A67577D-C552-497E-BF5D-F206340D9F75/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5A67577D-C552-497E-BF5D-F206340D9F75/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/137C9964-DC9C-4EA6-AF1A-65F2621AF731/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52958"
,(lldb)     command script import "/tmp/5A67577D-C552-497E-BF5D-F206340D9F75/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 23:46:14.411 HelloWorld[1766:3850939] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A110C1D0-CA2A-4947-AAED-546ABE0F5D0B/Library/Cookies/Cookies.binarycookies
,2016-01-11 23:46:14.683 HelloWorld[1766:3850939] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 23:46:14.684 HelloWorld[1766:3850939] Multi-tasking -> Device: YES, App: YES
,2016-01-11 23:46:14.687 HelloWorld[1766:3850939] Unlimited access to network resources
,2016-01-11 23:46:14.695 HelloWorld[1766:3850939] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 23:46:18.854 HelloWorld[1766:3850939] Resetting plugins due to page load.
,2016-01-11 23:46:20.353 HelloWorld[1766:3850939] Finished load of: file:///var/mobile/Containers/Bundle/Application/137C9964-DC9C-4EA6-AF1A-65F2621AF731/HelloWorld.app/www/index.html
,2016-01-11 23:46:20.421 HelloWorld[1766:3850939] JXcore Cordova plugin initializing
,2016-01-11 23:46:20.423 HelloWorld[1766:3851075] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-Iphone5s-1

Total memory 1048576000

Free memory 885882880

execPath /private/var/mobile/Containers/Bundle/Application/137C9964-DC9C-4EA6-AF1A-65F2621AF731/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/137C9964-DC9C-4EA6-AF1A-65F2621AF731/HelloWorld.app/www/jxcore/

userPath []

2016-01-11 23:46:20.632 HelloWorld[1766:3851075] Native method ScreenInfo not found.
2016-01-11 23:46:20.632 HelloWorld[1766:3851075] Native method ScreenBrightness not found.,
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5105  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
