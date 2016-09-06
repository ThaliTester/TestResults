#### Test 828946820542738_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5E5639A8-BB9A-47DC-9F2A-A019776646EF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5E5639A8-BB9A-47DC-9F2A-A019776646EF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/78508064-87A8-4343-9BCA-8AFFBD803979/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57386"
,(lldb)     command script import "/tmp/5E5639A8-BB9A-47DC-9F2A-A019776646EF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:08:26.907 ThaliTest[1285:2182518] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E87FE9C4-D8DC-4DC2-8BA2-8F71844BB2CD/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:08:27.410 ThaliTest[1285:2182518] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:08:27.411 ThaliTest[1285:2182518] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:08:27.434 ThaliTest[1285:2182518] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:08:29.696 ThaliTest[1285:2182518] Using UIWebView
,2016-09-06 19:08:29.703 ThaliTest[1285:2182518] [CDVTimer][handleopenurl] 0.406027ms
,2016-09-06 19:08:29.712 ThaliTest[1285:2182518] [CDVTimer][intentandnavigationfilter] 7.295012ms
2016-09-06 19:08:29.713 ThaliTest[1285:2182518] [CDVTimer][gesturehandler] 0.335991ms
2016-09-06 19:08:29.713 ThaliTest[1285:2182518] [CDVTimer][TotalPluginStartup] 10.632992ms
,2016-09-06 19:08:37.076 ThaliTest[1285:2182518] Resetting plugins due to page load.
,2016-09-06 19:08:40.541 ThaliTest[1285:2182518] Finished load of: file:///var/mobile/Containers/Bundle/Application/78508064-87A8-4343-9BCA-8AFFBD803979/ThaliTest.app/www/index.html
,2016-09-06 19:08:40.755 ThaliTest[1285:2182518] JXcore Cordova plugin initializing
,2016-09-06 19:08:40.756 ThaliTest[1285:2182785] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-09-06 19:08:40.959 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:40.961 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:40.961 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-06 19:08:41.962 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:41.963 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:41.963 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:42.964 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:42.965 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:42.965 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:43.966 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:43.967 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:43.968 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:44.968 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:44.969 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:44.969 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:45.971 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:45.972 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:45.972 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:46.973 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:46.974 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:46.974 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-06 19:08:47.975 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:47.976 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:47.976 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:48.978 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:48.980 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:48.980 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:49.982 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:49.984 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:49.985 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:50.987 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:50.990 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:50.990 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:51.992 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:51.994 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:51.995 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:52.996 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:52.999 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:52.999 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:54.001 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:54.004 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:54.004 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:55.006 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:55.008 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:55.008 ThaliTest[1285:2182518] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:08:56.010 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:08:56.012 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:56.012 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:57.014 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:57.016 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:57.017 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:58.018 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:58.021 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:58.021 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:59.023 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:08:59.026 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:59.026 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:00.028 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:00.031 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:00.031 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:01.033 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:01.036 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:01.036 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:02.038 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:02.041 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:02.041 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:03.043 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:03.045 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:03.045 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:04.047 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:04.050 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:04.050 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:05.052 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:05.054 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:05.055 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:06.056 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:06.059 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:06.059 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:07.061 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:07.064 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:07.064 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:08.066 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:08.068 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:08.069 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:09.070 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:09.073 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:09.073 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:10.075 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:10.077 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:10.077 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:11.079 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:11.081 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:11.082 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:12.083 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:12.086 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:12.086 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:13.088 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:13.090 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:13.091 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:14.092 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:14.095 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:14.095 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:15.097 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:15.099 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:15.100 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:16.101 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:16.104 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:16.104 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:17.106 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:17.108 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:17.108 ThaliTest[1285:2182518] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:09:18.110 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:18.113 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:18.113 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:19.115 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:19.117 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:19.118 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:20.119 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:20.122 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:20.122 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:21.124 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:21.125 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:21.126 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:22.127 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:22.130 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:22.130 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:23.132 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:23.135 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:23.135 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:24.137 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:24.139 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:24.140 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:25.141 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:25.143 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:25.144 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:26.145 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:26.148 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:26.148 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:26.684 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:26.687 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:26.687 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:27.150 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:27.152 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:27.153 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:27.689 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:27.692 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:27.692 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:28.154 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:28.157 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:28.157 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:28.694 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:28.697 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:28.697 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:29.159 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:29.162 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:29.162 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:29.699 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:29.702 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:29.702 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:30.164 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:30.166 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:30.167 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:30.704 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:30.707 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:30.707 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:31.168 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:31.171 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:31.171 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:31.709 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:31.711 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:31.711 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:32.173 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:32.175 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:32.175 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:32.713 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:32.716 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:32.717 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:33.177 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:33.180 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:33.180 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:33.719 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:33.721 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:33.722 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:34.182 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:34.184 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:34.185 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:34.723 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:34.726 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:34.726 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:35.186 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:35.189 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:35.189 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:35.728 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:35.730 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:35.731 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:36.191 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:36.193 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:36.194 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:36.774 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:36.775 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:36.775 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:37.195 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:37.197 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:37.197 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:37.777 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:37.779 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:37.780 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:38.199 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:38.201 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:38.202 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:38.781 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:38.783 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:38.784 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:39.203 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:39.206 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:39.206 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:39.785 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:39.788 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:39.788 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:40.208 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:40.210 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:40.211 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:40.790 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:40.793 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:40.793 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:41.212 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:41.215 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:41.215 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:41.795 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:41.798 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:41.798 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:42.217 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:42.219 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:42.220 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:42.800 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:42.802 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:42.803 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:43.221 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:43.224 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:43.225 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:43.804 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:43.807 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:43.807 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:44.226 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:44.229 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:44.229 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:44.809 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:44.811 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:44.812 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:45.231 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:45.233 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:45.234 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:45.813 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:45.816 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:45.816 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:46.235 ThaliTest[1285:2182518] BTM: attaching to BTServer
2016-09-06 19:09:46.237 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:46.238 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:46.791 ThaliTest[1285:2182518] BTM: attaching to BTServer
,2016-09-06 19:09:46.795 ThaliTest[1285:2182518] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:46.795 ThaliTest[1285:2182518] BTM: attemping to re-attach in 1 seconds
,* thread #1: tid = 0x214d76, 0x3768bfbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x3768bfbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x3768bdbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2541748c CoreFoundation`<redacted> + 136
    frame #3: 0x25415812 CoreFoundation`<redacted> + 1050
    frame #4: 0x253680d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x25367ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2e69daf8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x295f12dc UIKit`UIApplicationMain + 144
    frame #8: 0x000f24f2 ThaliTest`main + 50
    frame #9: 0x375d0872 libdyld.dylib`<redacted> + 2

```
