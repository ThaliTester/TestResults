#### Test 54970261ac9928f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A023649A-33DF-4448-AB56-2D380E16C494/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A023649A-33DF-4448-AB56-2D380E16C494/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/97CF3C92-DDCD-4111-8B0E-F6400EEA8A9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50572"
,(lldb)     command script import "/tmp/A023649A-33DF-4448-AB56-2D380E16C494/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 17:11:12.889 ThaliTest[1524:3216918] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CA4BC930-347F-407D-A6AA-E7CC64B83A1C/Library/Cookies/Cookies.binarycookies
,2016-01-08 17:11:13.341 ThaliTest[1524:3216918] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 17:11:13.343 ThaliTest[1524:3216918] Multi-tasking -> Device: YES, App: YES
,2016-01-08 17:11:13.353 ThaliTest[1524:3216918] Unlimited access to network resources
,2016-01-08 17:11:13.366 ThaliTest[1524:3216918] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 17:11:22.327 ThaliTest[1524:3216918] Resetting plugins due to page load.
,2016-01-08 17:11:26.237 ThaliTest[1524:3216918] Finished load of: file:///var/mobile/Containers/Bundle/Application/97CF3C92-DDCD-4111-8B0E-F6400EEA8A9C/ThaliTest.app/www/index.html
,2016-01-08 17:11:26.444 ThaliTest[1524:3216918] JXcore Cordova plugin initializing
,2016-01-08 17:11:26.445 ThaliTest[1524:3217108] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data
,# teardown

```
