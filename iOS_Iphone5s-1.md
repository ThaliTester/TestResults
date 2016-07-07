#### Test 75789268a22e351_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/7386DAED-3F99-45AC-AB85-AEEF30848D1D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7386DAED-3F99-45AC-AB85-AEEF30848D1D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D5A01A0F-0118-480B-9704-EDF0093E9D80/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51345"
,(lldb)     command script import "/tmp/7386DAED-3F99-45AC-AB85-AEEF30848D1D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 15:09:11.615 ThaliTest[6533:19671248] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/963F92AA-D746-4D1B-8B0F-DFE6C6B92749/Library/Cookies/Cookies.binarycookies
,2016-07-07 15:09:11.873 ThaliTest[6533:19671248] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 15:09:11.875 ThaliTest[6533:19671248] Multi-tasking -> Device: YES, App: YES
,2016-07-07 15:09:11.892 ThaliTest[6533:19671248] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 15:09:12.748 ThaliTest[6533:19671248] Using UIWebView
,2016-07-07 15:09:12.750 ThaliTest[6533:19671248] [CDVTimer][handleopenurl] 0.187993ms
,2016-07-07 15:09:12.753 ThaliTest[6533:19671248] [CDVTimer][intentandnavigationfilter] 2.781987ms
,2016-07-07 15:09:12.755 ThaliTest[6533:19671248] [CDVTimer][gesturehandler] 1.331031ms
2016-07-07 15:09:12.755 ThaliTest[6533:19671248] [CDVTimer][TotalPluginStartup] 5.098999ms
,2016-07-07 15:09:16.222 ThaliTest[6533:19671248] Resetting plugins due to page load.
,2016-07-07 15:09:17.784 ThaliTest[6533:19671248] Finished load of: file:///var/mobile/Containers/Bundle/Application/D5A01A0F-0118-480B-9704-EDF0093E9D80/ThaliTest.app/www/index.html
,2016-07-07 15:09:17.963 ThaliTest[6533:19671248] JXcore Cordova plugin initializing
,2016-07-07 15:09:17.965 ThaliTest[6533:19671409] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,appEnteredForeground wasn't registered

```
