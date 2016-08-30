#### Test 828946826174a68_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/9A65068E-51E5-44E1-854C-0FE78380E36C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9A65068E-51E5-44E1-854C-0FE78380E36C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/61395C74-A25D-4580-A016-F4C37426CFCB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57757"
,(lldb)     command script import "/tmp/9A65068E-51E5-44E1-854C-0FE78380E36C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 17:06:55.893 ThaliTest[1391:2518018] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5EBAC1B2-FC89-48BD-880A-C3724F883B58/Library/Cookies/Cookies.binarycookies
,2016-08-30 17:06:56.322 ThaliTest[1391:2518018] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 17:06:56.323 ThaliTest[1391:2518018] Multi-tasking -> Device: YES, App: YES
,2016-08-30 17:06:56.342 ThaliTest[1391:2518018] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 17:06:58.182 ThaliTest[1391:2518018] Using UIWebView
,2016-08-30 17:06:58.189 ThaliTest[1391:2518018] [CDVTimer][handleopenurl] 0.405967ms
,2016-08-30 17:06:58.197 ThaliTest[1391:2518018] [CDVTimer][intentandnavigationfilter] 7.406950ms
,2016-08-30 17:06:58.197 ThaliTest[1391:2518018] [CDVTimer][gesturehandler] 0.342011ms
,2016-08-30 17:06:58.198 ThaliTest[1391:2518018] [CDVTimer][TotalPluginStartup] 9.839058ms
,2016-08-30 17:07:04.857 ThaliTest[1391:2518018] Resetting plugins due to page load.
,2016-08-30 17:07:08.436 ThaliTest[1391:2518018] Finished load of: file:///var/mobile/Containers/Bundle/Application/61395C74-A25D-4580-A016-F4C37426CFCB/ThaliTest.app/www/index.html
,2016-08-30 17:07:08.644 ThaliTest[1391:2518018] JXcore Cordova plugin initializing
,2016-08-30 17:07:08.644 ThaliTest[1391:2518259] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-30 17:07:16.264 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:16.267 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:16.268 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:17.269 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:17.272 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:17.272 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:18.273 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:18.275 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-30 17:07:18.276 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:19.277 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:19.280 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:19.280 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:20.282 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:20.284 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:20.284 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:21.286 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:21.288 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:21.289 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:22.290 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:22.292 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:22.293 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:23.294 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:23.297 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-30 17:07:23.297 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:24.299 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:24.301 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:24.301 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:25.303 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:25.306 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:25.306 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:27.354 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:27.356 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:27.357 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:28.358 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:28.361 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-30 17:07:28.361 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:29.363 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:29.365 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:29.366 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:30.367 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:30.370 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:30.370 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:31.372 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:31.374 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:31.375 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:32.376 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:32.379 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:32.379 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:33.381 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:33.383 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:33.383 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:34.385 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:34.387 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:34.387 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:35.389 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:35.391 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:35.392 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:36.393 ThaliTest[1391:2518018] BTM: attaching to BTServer
,2016-08-30 17:07:36.395 ThaliTest[1391:2518018] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:36.396 ThaliTest[1391:2518018] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:38.371 ThaliTest[1391:2518018] BTM: attaching to BTServer
,Process 1391 stopped
* thread #17: tid = 0x266cf3, 0x007f6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007f6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7f6998 <+1188>: trap   
    0x7f699c <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7f69a0 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7f69a4 <+4>:    add    r7, sp, #12
,* thread #17: tid = 0x266cf3, 0x007f6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007f6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x0009990c ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x00097a6a ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x00092382 ThaliTest`callJXcoreNative + 660
    frame #4: 0x000f4e7a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x00233436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x001cd9a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x00233436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x00230a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #9: 0x0022c4fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x002334d2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x001cd9a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x00233436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x00230a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #14: 0x0022c4fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x002334d2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x001cd9a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x00233436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x00230a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #19: 0x0022c4fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x002334d2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x001cd9a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x00233436 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x00230a18 ThaliTest`___lldb_unnamed_function985$$ThaliTest + 17664
    frame #24: 0x0022c4fc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x00233b5a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x00233c72 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x001b6682 ThaliTest`___lldb_unnamed_function607$$ThaliTest + 20
    frame #28: 0x0010f3e4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x0010f438 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x000f67bc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x000f533e ThaliTest`JX_Evaluate + 40
    frame #32: 0x00094a8c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x00092918 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x22f2036c Foundation`<redacted> + 1144
    frame #35: 0x34502c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x34502bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x34500a08 libsystem_pthread.dylib`thread_start + 8

```
