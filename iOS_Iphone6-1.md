#### Test 8289468223f5822_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F7C9F979-403C-44A8-9DB8-560938ED4EE9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F7C9F979-403C-44A8-9DB8-560938ED4EE9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F02DD3F6-B069-4479-9D09-3FE624D7A4B0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51886"
,(lldb)     command script import "/tmp/F7C9F979-403C-44A8-9DB8-560938ED4EE9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 15:09:53.857 ThaliTest[760:999893] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8293923E-1E5D-491E-AAB2-61F1F8A0E909/Library/Cookies/Cookies.binarycookies
,2016-08-29 15:09:54.242 ThaliTest[760:999893] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 15:09:54.243 ThaliTest[760:999893] Multi-tasking -> Device: YES, App: YES
,2016-08-29 15:09:54.266 ThaliTest[760:999893] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 15:09:56.008 ThaliTest[760:999893] Using UIWebView
,2016-08-29 15:09:56.018 ThaliTest[760:999893] [CDVTimer][handleopenurl] 0.606000ms
,2016-08-29 15:09:56.028 ThaliTest[760:999893] [CDVTimer][intentandnavigationfilter] 9.532034ms
2016-08-29 15:09:56.029 ThaliTest[760:999893] [CDVTimer][gesturehandler] 0.440001ms
2016-08-29 15:09:56.029 ThaliTest[760:999893] [CDVTimer][TotalPluginStartup,] 12.592018ms
,2016-08-29 15:10:02.314 ThaliTest[760:999893] Resetting plugins due to page load.
,2016-08-29 15:10:05.207 ThaliTest[760:999893] Finished load of: file:///var/mobile/Containers/Bundle/Application/F02DD3F6-B069-4479-9D09-3FE624D7A4B0/ThaliTest.app/www/index.html
,2016-08-29 15:10:05.434 ThaliTest[760:999893] JXcore Cordova plugin initializing
,2016-08-29 15:10:05.436 ThaliTest[760:1000130] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-29 15:10:05.583 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:05.584 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:05.584 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 15:10:06.585 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:06.586 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:06.586 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:07.588 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:07.588 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:07.589 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:08.590 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:08.591 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:08.591 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:09.592 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:09.593 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:09.593 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:10.594 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:10.595 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:10.595 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:11.596 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:11.597 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:11.597 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-29 15:10:12.598 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:12.599 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:12.599 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:13.782 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:13.785 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:13.786 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:14.787 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:14.790 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:14.790 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:15.792 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:15.794 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:15.795 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:16.796 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:16.799 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:16.799 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:17.801 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:17.803 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:17.803 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:18.805 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:18.807 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:18.808 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:19.810 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:19.812 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:19.812 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:20.814 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:20.816 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:20.817 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:21.818 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:21.821 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:21.821 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:22.823 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:22.825 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:22.826 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:24.875 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:24.878 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:24.879 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:25.880 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:25.883 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:25.884 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:26.885 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:26.888 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:26.888 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:27.890 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:27.893 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:27.893 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:28.895 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:28.898 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:28.898 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:29.900 ThaliTest[760:999893] BTM: attaching to BTServer
2016-08-29 15:10:29.902 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:29.903 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:30.904 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:30.907 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:30.908 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:31.909 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:31.912 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:31.912 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:32.914 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:32.917 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:32.917 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:33.919 ThaliTest[760:999893] BTM: attaching to BTServer
,2016-08-29 15:10:33.922 ThaliTest[760:999893] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:33.922 ThaliTest[760:999893] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:35.894 ThaliTest[760:999893] BTM: attaching to BTServer
,Process 760 stopped
* thread #15: tid = 0xf42c2, 0x0083e998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x0083e998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x83e998 <+1188>: trap   
    0x83e99c <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x83e9a0 <+0>:    push   {r4, r5, r6, r7, lr}
    0x83e9a4 <+4>:    add    r7, sp, #12
,* thread #15: tid = 0xf42c2, 0x0083e998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x0083e998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x000e30ac ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x000e120a ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x000dbab2 ThaliTest`callJXcoreNative + 660
    frame #4: 0x0013d1fa ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x0027b7b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x00215d28 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x0027b7b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x00278d98 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #9: 0x0027487c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x0027b852 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x00215d28 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x0027b7b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x00278d98 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #14: 0x0027487c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x0027b852 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x00215d28 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x0027b7b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x00278d98 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #19: 0x0027487c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x0027b852 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x00215d28 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x0027b7b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x00278d98 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #24: 0x0027487c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x0027beda ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x0027bff2 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x001fea02 ThaliTest`___lldb_unnamed_function607$$ThaliTest + 20
    frame #28: 0x00157764 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x001577b8 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x0013eb3c ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x0013d6be ThaliTest`JX_Evaluate + 40
    frame #32: 0x000de1bc ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x000dc048 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2622b36c Foundation`<redacted> + 1144
    frame #35: 0x3773ec7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x3773ebf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x3773ca08 libsystem_pthread.dylib`thread_start + 8

```
