#### Test 84265062e3ffea4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0C989B89-F7FE-466F-A899-A60ED9B9B8C5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0C989B89-F7FE-466F-A899-A60ED9B9B8C5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ACBE4BEB-B727-4BE0-8553-4342BBD354E6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49514"
,(lldb)     command script import "/tmp/0C989B89-F7FE-466F-A899-A60ED9B9B8C5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 12:04:00.356 ThaliTest[1368:2294994] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2F202987-9246-4E68-9DE0-CED8F7093C1B/Library/Cookies/Cookies.binarycookies
,2016-09-07 12:04:00.847 ThaliTest[1368:2294994] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 12:04:00.849 ThaliTest[1368:2294994] Multi-tasking -> Device: YES, App: YES
,2016-09-07 12:04:00.871 ThaliTest[1368:2294994] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 12:04:03.161 ThaliTest[1368:2294994] Using UIWebView
,2016-09-07 12:04:03.171 ThaliTest[1368:2294994] [CDVTimer][handleopenurl] 0.406981ms
,2016-09-07 12:04:03.179 ThaliTest[1368:2294994] [CDVTimer][intentandnavigationfilter] 7.292986ms
2016-09-07 12:04:03.180 ThaliTest[1368:2294994] [CDVTimer][gesturehandler] 0.343978ms
2016-09-07 12:04:03.180 ThaliTest[1368:2294994] [CDVTimer][TotalPluginStartup] 9.736955ms
,2016-09-07 12:04:10.464 ThaliTest[1368:2294994] Resetting plugins due to page load.
,2016-09-07 12:04:14.287 ThaliTest[1368:2294994] Finished load of: file:///var/mobile/Containers/Bundle/Application/ACBE4BEB-B727-4BE0-8553-4342BBD354E6/ThaliTest.app/www/index.html
,2016-09-07 12:04:14.516 ThaliTest[1368:2294994] JXcore Cordova plugin initializing
,2016-09-07 12:04:14.516 ThaliTest[1368:2295254] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-07 12:04:21.780 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:21.782 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:21.782 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:21.797 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:21.798 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:21.798 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:22.784 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:22.786 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:22.786 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:22.799 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:22.802 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:22.802 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:23.788 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:23.790 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:23.791 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:23.804 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:04:23.806 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:23.806 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:24.792 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:24.795 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:24.795 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:24.808 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:24.810 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:24.811 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:25.797 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:25.799 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:25.800 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:25.812 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:25.815 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:25.815 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:26.801 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:26.804 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:26.804 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:26.817 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:26.819 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:26.819 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:27.805 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:27.808 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:27.808 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:27.821 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:27.823 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:27.824 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:28.810 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:28.812 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:28.812 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:28.825 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:28.828 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:28.828 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:29.814 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:29.816 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:29.817 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:29.830 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:29.832 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:29.833 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:30.818 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:30.821 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:30.821 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:30.834 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:30.837 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:30.837 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:31.900 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:31.901 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:31.901 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:32.902 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:32.905 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:32.905 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:33.907 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:33.909 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:33.909 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:34.911 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:34.913 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:34.914 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:35.915 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:35.918 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:35.918 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:36.920 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:36.922 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:36.923 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:37.924 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:37.927 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:37.927 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:38.929 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:38.931 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:38.932 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:39.934 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:39.936 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:39.936 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:40.938 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:40.940 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:40.941 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:41.918 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:41.962 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:41.962 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:42.963 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:42.966 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:42.966 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:43.968 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:43.970 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:43.971 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:44.972 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:04:44.974 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:44.975 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:45.976 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:45.979 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:45.979 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:46.981 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:46.984 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:46.984 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:47.986 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:04:47.989 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:47.989 ThaliTest[1368:2294994] BTM: attemping ,to re-attach in 1 seconds
,2016-09-07 12:04:48.991 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:04:48.993 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:48.993 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:49.995 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:49.997 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:49.998 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:50.999 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:51.002 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:51.002 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:52.004 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:52.007 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:52.007 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:53.009 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:53.011 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:53.012 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:54.013 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:54.016 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:54.016 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:55.018 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:55.020 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:55.021 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:56.022 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:04:56.025 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:56.025 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:57.027 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:57.029 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:57.030 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:58.031 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:58.034 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:58.034 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:59.036 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:04:59.038 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:59.039 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:00.040 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:00.043 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:00.043 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:01.045 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:01.048 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:01.048 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:02.050 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:05:02.052 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:02.052 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:03.054 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:05:03.056 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:03.056 ThaliTest[1368:2294994] BTM: attemping ,to re-attach in 1 seconds
,2016-09-07 12:05:04.058 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:04.060 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:04.061 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:05.062 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:05.065 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:05.065 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:06.067 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:05:06.071 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:06.071 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:07.073 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:07.075 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:07.076 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:08.078 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:05:08.080 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:08.080 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:09.082 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:09.084 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:09.085 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:10.086 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:10.089 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:10.089 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:11.091 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:11.093 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:11.094 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:12.095 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:12.098 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:12.098 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:13.100 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:13.103 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:13.103 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:14.105 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:14.107 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:14.108 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:15.109 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:05:15.111 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:15.112 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:16.113 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:16.116 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:16.116 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:17.118 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:17.120 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:17.121 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:18.122 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:18.125 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:18.125 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:19.127 ThaliTest[1368:2294994] BTM: attaching to BTServer
2016-09-07 12:05:19.129 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:19.129 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:05:20.131 ThaliTest[1368:2294994] BTM: attaching to BTServer
,2016-09-07 12:05:20.134 ThaliTest[1368:2294994] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:05:20.134 ThaliTest[1368:2294994] BTM: attemping to re-attach in 1 seconds
,Process 1368 stopped
* thread #15: tid = 0x2305d6, 0x007e97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007e97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7e97e0 <+1188>: trap   
    0x7e97e4 <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7e97e8 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7e97ec <+4>:    add    r7, sp, #12
,* thread #15: tid = 0x2305d6, 0x007e97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007e97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x0007ca84 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x0007aaae ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x000753b2 ThaliTest`callJXcoreNative + 660
    frame #4: 0x000dc57a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x0021ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x001b50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x0021ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x00218118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #9: 0x00213bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x0021abd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x001b50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x0021ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x00218118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #14: 0x00213bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x0021abd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x001b50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x0021ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x00218118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #19: 0x00213bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x0021abd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x001b50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x0021ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x00218118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #24: 0x00213bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x0021b25a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x0021b372 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x0019dd82 ThaliTest`___lldb_unnamed_function613$$ThaliTest + 20
    frame #28: 0x000f6ae4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x000f6b38 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x000ddebc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x000dca3e ThaliTest`JX_Evaluate + 40
    frame #32: 0x00077abc ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x00075948 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2622b36c Foundation`<redacted> + 1144
    frame #35: 0x3773ec7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x3773ebf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x3773ca08 libsystem_pthread.dylib`thread_start + 8

```
