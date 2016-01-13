#### Test 558973767bac5c9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/558973767bac5c9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6F3E5D67-FD8F-4E3B-86C6-53E2CD191CE1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6F3E5D67-FD8F-4E3B-86C6-53E2CD191CE1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/558973767bac5c9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/558973767bac5c9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2E3D4CCA-78D6-4E31-B12F-EB843392FF09/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54830"
,(lldb)     command script import "/tmp/6F3E5D67-FD8F-4E3B-86C6-53E2CD191CE1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 14:50:48.065 ThaliTest[1861:4219645] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/713CDE2D-0A8B-459A-9E6A-07949B858249/Library/Cookies/Cookies.binarycookies
,2016-01-13 14:50:48.351 ThaliTest[1861:4219645] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 14:50:48.352 ThaliTest[1861:4219645] Multi-tasking -> Device: YES, App: YES
,2016-01-13 14:50:48.359 ThaliTest[1861:4219645] Unlimited access to network resources
,2016-01-13 14:50:48.367 ThaliTest[1861:4219645] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 14:50:52.749 ThaliTest[1861:4219645] Resetting plugins due to page load.
,2016-01-13 14:50:54.312 ThaliTest[1861:4219645] Finished load of: file:///var/mobile/Containers/Bundle/Application/2E3D4CCA-78D6-4E31-B12F-EB843392FF09/ThaliTest.app/www/index.html
,2016-01-13 14:50:54.507 ThaliTest[1861:4219645] JXcore Cordova plugin initializing
,2016-01-13 14:50:54.509 ThaliTest[1861:4219802] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test app app.js loaded
,
,TAP version 13

,# setup

,# multiplex can send data


```
