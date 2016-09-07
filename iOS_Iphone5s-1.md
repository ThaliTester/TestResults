#### Test 84265062e3ffea4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7A54FB3C-06A0-4238-AA3C-72C483FFA884/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7A54FB3C-06A0-4238-AA3C-72C483FFA884/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FD00A1C2-2767-4E79-8866-8FE629C44DF2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49511"
,(lldb)     command script import "/tmp/7A54FB3C-06A0-4238-AA3C-72C483FFA884/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 12:03:38.030 ThaliTest[1792:3724971] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AA350E76-FC32-48CD-8250-1AF00569A8DD/Library/Cookies/Cookies.binarycookies
,2016-09-07 12:03:38.277 ThaliTest[1792:3724971] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 12:03:38.278 ThaliTest[1792:3724971] Multi-tasking -> Device: YES, App: YES
,2016-09-07 12:03:38.299 ThaliTest[1792:3724971] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 12:03:39.075 ThaliTest[1792:3724971] Using UIWebView
2016-09-07 12:03:39.078 ThaliTest[1792:3724971] [CDVTimer][handleopenurl] 0.151992ms
,2016-09-07 12:03:39.082 ThaliTest[1792:3724971] [CDVTimer][intentandnavigationfilter] 3.760993ms
2016-09-07 12:03:39.082 ThaliTest[1792:3724971] [CDVTimer][gesturehandler] 0.145018ms
2016-09-07 12:03:39.082 ThaliTest[1792:3724971] [CDVTimer][TotalPluginS,tartup] 4.664004ms
,2016-09-07 12:03:42.005 ThaliTest[1792:3724971] Resetting plugins due to page load.
,2016-09-07 12:03:43.399 ThaliTest[1792:3724971] Finished load of: file:///var/mobile/Containers/Bundle/Application/FD00A1C2-2767-4E79-8866-8FE629C44DF2/ThaliTest.app/www/index.html
,2016-09-07 12:03:43.593 ThaliTest[1792:3724971] JXcore Cordova plugin initializing
,2016-09-07 12:03:43.593 ThaliTest[1792:3725141] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-07 12:04:30.107 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:30.108 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:30.108 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:30.128 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:30.130 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:30.130 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:31.109 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:31.110 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:31.110 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:31.130 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:31.131 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:31.131 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:32.112 ThaliTest[1792:3724971] BTM: attaching to BTServer
,2016-09-07 12:04:32.113 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:32.113 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:32.132 ThaliTest[1792:3724971] BTM: attaching to BTServer
,2016-09-07 12:04:32.133 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:32.133 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:33.114 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:33.115 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:33.115 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:33.134 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:33.135 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:33.135 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:34.116 ThaliTest[1792:3724971] BTM: attaching to BTServer
,2016-09-07 12:04:34.117 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:34.118 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:34.136 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:34.137 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:34.137 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:35.119 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:35.120 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:35.120 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:35.138 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:35.139 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:35.139 ThaliTest[1792:3724971] BTM: attemping ,to re-attach in 1 seconds
,2016-09-07 12:04:36.121 ThaliTest[1792:3724971] BTM: attaching to BTServer
,2016-09-07 12:04:36.122 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:36.122 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:36.140 ThaliTest[1792:3724971] BTM: attaching to BTServer
,2016-09-07 12:04:36.142 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:36.142 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:37.124 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:37.125 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:37.125 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:37.143 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:37.144 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:37.144 ThaliTest[1792:3724971] BTM: attemping ,to re-attach in 1 seconds
,2016-09-07 12:04:38.126 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:38.127 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:38.127 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:38.145 ThaliTest[1792:3724971] BTM: attaching to BTServer
,2016-09-07 12:04:38.146 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:38.146 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:39.128 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:39.129 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:39.129 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:39.147 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:39.148 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:39.148 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:40.173 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:40.174 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:40.175 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:41.176 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:41.177 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:41.177 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:42.178 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:42.179 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:42.179 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:43.181 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:43.182 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:43.182 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:44.183 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:44.184 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:44.184 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:45.185 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:45.186 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:45.186 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:46.188 ThaliTest[1792:3724971] BTM: attaching to BTServer
,2016-09-07 12:04:46.189 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:46.189 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:47.190 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:47.191 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:47.191 ThaliTest[1792:3724971] BTM: attemping ,to re-attach in 1 seconds
,2016-09-07 12:04:48.193 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:48.194 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:48.194 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:49.195 ThaliTest[1792:3724971] BTM: attaching to BTServer
2016-09-07 12:04:49.196 ThaliTest[1792:3724971] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:49.196 ThaliTest[1792:3724971] BTM: attemping to re-attach in 1 seconds
,Process 1792 stopped
* thread #15: tid = 0x38d755, 0x007917e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007917e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7917e0 <+1188>: trap   
    0x7917e4 <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7917e8 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7917ec <+4>:    add    r7, sp, #12
,* thread #15: tid = 0x38d755, 0x007917e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007917e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x00024a84 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x00022aae ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x0001d3b2 ThaliTest`callJXcoreNative + 660
    frame #4: 0x0008457a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x001c2b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x0015d0a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x001c2b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x001c0118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #9: 0x001bbbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x001c2bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x0015d0a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x001c2b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x001c0118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #14: 0x001bbbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x001c2bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x0015d0a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x001c2b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x001c0118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #19: 0x001bbbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x001c2bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x0015d0a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x001c2b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x001c0118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #24: 0x001bbbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x001c325a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x001c3372 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x00145d82 ThaliTest`___lldb_unnamed_function613$$ThaliTest + 20
    frame #28: 0x0009eae4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x0009eb38 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x00085ebc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x00084a3e ThaliTest`JX_Evaluate + 40
    frame #32: 0x0001fabc ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x0001d948 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2609336c Foundation`<redacted> + 1144
    frame #35: 0x374d6c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x374d6bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x374d4a08 libsystem_pthread.dylib`thread_start + 8

```
