#### Test 828946826174a68_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7EE87121-825A-4D50-84DD-0B1092BB55DE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7EE87121-825A-4D50-84DD-0B1092BB55DE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/59E64039-0254-48AD-BE5D-B14E5FA4E65C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57761"
,(lldb)     command script import "/tmp/7EE87121-825A-4D50-84DD-0B1092BB55DE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 17:06:53.597 ThaliTest[1282:2569304] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F641AA38-B880-4151-9ADD-976100CF7A81/Library/Cookies/Cookies.binarycookies
,2016-08-30 17:06:54.018 ThaliTest[1282:2569304] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 17:06:54.020 ThaliTest[1282:2569304] Multi-tasking -> Device: YES, App: YES
,2016-08-30 17:06:54.052 ThaliTest[1282:2569304] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 17:06:55.725 ThaliTest[1282:2569304] Using UIWebView
,2016-08-30 17:06:55.733 ThaliTest[1282:2569304] [CDVTimer][handleopenurl] 0.459015ms
,2016-08-30 17:06:55.742 ThaliTest[1282:2569304] [CDVTimer][intentandnavigationfilter] 8.063018ms
2016-08-30 17:06:55.743 ThaliTest[1282:2569304] [CDVTimer][gesturehandler] 0.425994ms
2016-08-30 17:06:55.744 ThaliTest[1282:2569304] [CDVTimer][TotalPluginS,tartup] 11.243999ms
,2016-08-30 17:07:01.791 ThaliTest[1282:2569304] Resetting plugins due to page load.
,2016-08-30 17:07:04.759 ThaliTest[1282:2569304] Finished load of: file:///var/mobile/Containers/Bundle/Application/59E64039-0254-48AD-BE5D-B14E5FA4E65C/ThaliTest.app/www/index.html
,2016-08-30 17:07:05.003 ThaliTest[1282:2569304] JXcore Cordova plugin initializing
,2016-08-30 17:07:05.004 ThaliTest[1282:2569540] JXcore instance initializing
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
,2016-08-30 17:07:14.697 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:14.702 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:14.702 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:15.704 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:15.706 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:15.707 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:16.708 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:16.711 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:16.712 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:17.713 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:17.716 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:17.716 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:18.718 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:18.721 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:18.721 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:19.723 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:19.725 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:19.726 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:20.727 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:20.730 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:20.730 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:21.732 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:21.734 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:21.735 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:22.737 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:22.739 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:22.739 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:23.741 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:23.744 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:23.744 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:25.798 ThaliTest[1282:2569304] BTM: attaching to BTServer
2016-08-30 17:07:25.801 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:25.801 ThaliTest[1282:2569304] BTM: attemping ,to re-attach in 1 seconds
,2016-08-30 17:07:26.803 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:26.806 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:26.806 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:27.808 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:27.810 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:27.811 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:28.813 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:28.815 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:28.816 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:29.817 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:29.820 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:29.821 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:30.822 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:30.825 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:30.825 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:31.827 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:31.830 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:31.830 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:32.832 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:32.835 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:32.835 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:33.837 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:33.839 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:33.840 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:34.842 ThaliTest[1282:2569304] BTM: attaching to BTServer
,2016-08-30 17:07:34.844 ThaliTest[1282:2569304] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:34.844 ThaliTest[1282:2569304] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:36.827 ThaliTest[1282:2569304] BTM: attaching to BTServer
,Process 1282 stopped
* thread #15: tid = 0x273544, 0x0085a998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x0085a998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x85a998 <+1188>: trap   
    0x85a99c <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x85a9a0 <+0>:    push   {r4, r5, r6, r7, lr}
    0x85a9a4 <+4>:    add    r7, sp, #12
,* thread #15: tid = 0x273544, 0x0085a998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x0085a998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x000fd90c ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x000fba6a ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x000f6382 ThaliTest`callJXcoreNative + 660
    frame #4: 0x00158e7a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x00297436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x002319a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x00297436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x00294a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #9: 0x002904fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x002974d2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x002319a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x00297436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x00294a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #14: 0x002904fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x002974d2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x002319a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x00297436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x00294a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #19: 0x002904fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x002974d2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x002319a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x00297436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x00294a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #24: 0x002904fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x00297b5a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x00297c72 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x0021a682 ThaliTest`___lldb_unnamed_function607$$ThaliTest + 20
    frame #28: 0x001733e4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x00173438 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x0015a7bc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x0015933e ThaliTest`JX_Evaluate + 40
    frame #32: 0x000f8a8c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x000f6918 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2609336c Foundation`<redacted> + 1144
    frame #35: 0x374d6c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x374d6bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x374d4a08 libsystem_pthread.dylib`thread_start + 8

```
