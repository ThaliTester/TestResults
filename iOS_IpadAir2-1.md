#### Test 82894682929afb6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F7E3D1D4-9F55-40CE-A94A-6383A55D6AB7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F7E3D1D4-9F55-40CE-A94A-6383A55D6AB7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F55E782D-8815-4687-B50C-FEB9AD633F4A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52929"
,(lldb)     command script import "/tmp/F7E3D1D4-9F55-40CE-A94A-6383A55D6AB7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 08:50:33.668 ThaliTest[1430:2597570] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DD30AF3B-6F59-41B0-827B-6DF4ED3AB329/Library/Cookies/Cookies.binarycookies
,2016-08-31 08:50:34.069 ThaliTest[1430:2597570] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 08:50:34.070 ThaliTest[1430:2597570] Multi-tasking -> Device: YES, App: YES
,2016-08-31 08:50:34.089 ThaliTest[1430:2597570] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 08:50:36.208 ThaliTest[1430:2597570] Using UIWebView
,2016-08-31 08:50:36.214 ThaliTest[1430:2597570] [CDVTimer][handleopenurl] 0.356019ms
,2016-08-31 08:50:36.222 ThaliTest[1430:2597570] [CDVTimer][intentandnavigationfilter] 6.708026ms
,2016-08-31 08:50:36.222 ThaliTest[1430:2597570] [CDVTimer][gesturehandler] 0.304997ms
,2016-08-31 08:50:36.223 ThaliTest[1430:2597570] [CDVTimer][TotalPluginStartup] 8.892000ms
,2016-08-31 08:50:42.761 ThaliTest[1430:2597570] Resetting plugins due to page load.
,2016-08-31 08:50:46.304 ThaliTest[1430:2597570] Finished load of: file:///var/mobile/Containers/Bundle/Application/F55E782D-8815-4687-B50C-FEB9AD633F4A/ThaliTest.app/www/index.html
,2016-08-31 08:50:46.522 ThaliTest[1430:2597570] JXcore Cordova plugin initializing
,2016-08-31 08:50:46.523 ThaliTest[1430:2597814] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-31 08:50:46.762 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:46.765 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-31 08:50:46.765 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 08:50:47.767 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:47.768 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:47.768 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:48.770 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:48.770 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:48.771 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:49.772 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:49.773 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:49.773 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:50.773 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:50.774 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:50.774 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:51.775 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:51.776 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:51.776 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:52.777 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:52.779 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:52.780 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-31 08:50:53.096 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:53.104 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:53.104 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:53.781 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:53.783 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:53.784 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:54.105 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:54.108 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:54.108 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:54.785 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:54.787 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:54.788 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:55.109 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:55.111 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:55.112 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:55.790 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:55.792 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:55.792 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:56.113 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:56.116 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:56.116 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:56.794 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:56.796 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:56.796 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:57.118 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:57.120 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:57.120 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:57.798 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:57.800 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:57.801 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:58.122 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:58.124 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:58.125 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:58.802 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:58.805 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:58.805 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:59.126 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:59.129 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:59.129 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:59.807 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:50:59.809 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:59.809 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:00.131 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:00.133 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:00.133 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:00.811 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:00.813 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:00.813 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:01.135 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:01.138 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:01.138 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:01.815 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:01.817 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:01.818 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:02.140 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:02.142 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:02.142 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:02.819 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:02.822 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:02.822 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:03.188 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:03.189 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:03.189 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:03.824 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:03.826 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:03.826 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:04.190 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:04.192 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:04.193 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:04.828 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:04.830 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:04.831 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:05.194 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:05.197 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:05.197 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:05.832 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:05.835 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:05.835 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:06.199 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:06.201 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:06.201 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:06.837 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:06.839 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:06.839 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:07.203 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:07.205 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:07.206 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:07.841 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:07.843 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:07.844 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:08.207 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:08.209 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:08.210 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:08.845 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:08.847 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:08.848 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:09.211 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:09.214 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:09.214 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:09.850 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:09.852 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:09.852 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:10.216 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:10.218 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:10.219 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:10.853 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:10.855 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:10.856 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:11.220 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:11.223 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:11.223 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:11.857 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:11.860 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:11.860 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:12.225 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:12.227 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:12.227 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:12.862 ThaliTest[1430:2597570] BTM: attaching to BTServer
,2016-08-31 08:51:12.864 ThaliTest[1430:2597570] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:12.864 ThaliTest[1430:2597570] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:13.204 ThaliTest[1430:2597570] BTM: attaching to BTServer
,Process 1430 stopped
* thread #15: tid = 0x27a3b6, 0x007aa998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007aa998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7aa998 <+1188>: trap   
    0x7aa99c <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7aa9a0 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7aa9a4 <+4>:    add    r7, sp, #12
,* thread #15: tid = 0x27a3b6, 0x007aa998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007aa998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x00048548 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x000464b6 ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x00040d32 ThaliTest`callJXcoreNative + 660
    frame #4: 0x000a4dfa ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x001e33b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x0017d928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x001e33b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x001e0998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #9: 0x001dc47c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x001e3452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x0017d928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x001e33b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x001e0998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #14: 0x001dc47c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x001e3452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x0017d928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x001e33b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x001e0998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #19: 0x001dc47c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x001e3452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x0017d928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x001e33b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x001e0998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #24: 0x001dc47c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x001e3ada ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x001e3bf2 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x00166602 ThaliTest`___lldb_unnamed_function609$$ThaliTest + 20
    frame #28: 0x000bf364 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x000bf3b8 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x000a673c ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x000a52be ThaliTest`JX_Evaluate + 40
    frame #32: 0x0004343c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x000412c8 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x22f2036c Foundation`<redacted> + 1144
    frame #35: 0x34502c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x34502bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x34500a08 libsystem_pthread.dylib`thread_start + 8

```
