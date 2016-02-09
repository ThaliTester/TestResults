#### Test 587523534d3a10e_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 6165): 
D/AndroidRuntime( 6165): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6165): CheckJNI is OFF
D/AndroidRuntime( 6165): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6184 uid=10524 gids={50524, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6165): Shutting down VM
I/art     (  322): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 23.995ms
V/ActivityManager(  882): Display changed displayId=0
I/art     (  322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 708us total 20.659ms
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 26.871ms
--------- beginning of crash
F/libc    ( 6165): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb4f59010 in tid 6181 (Binder_1)
E/        (  297): tid 6181 does not exist in pid 6165. ignoring debug request
,I/WebViewFactory( 6184): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6184): Time to load native libraries: 2 ms (timestamps 7310-7312)
I/LibraryLoader( 6184): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6184): Binding Chromium to main looper Looper (main, tid 1) {11a89539}
I/LibraryLoader( 6184): Expected native library version number "",actual native library version number ""
I/chromium( 6184): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6184): Initializing chromium process, singleProcess=true
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6184): ApplicationContext is null in ApplicationStatus
,W/chromium( 6184): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6184): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6184): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6184): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6184): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6184): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6184): Local Branch: 
I/Adreno-EGL( 6184): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6184): Local Patches: NONE
I/Adreno-EGL( 6184): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ed80e7e:true
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{5e2390b u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6184): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6184): CordovaWebView is running on device made by: motorola
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6184): Render dirty regions requested: true
,D/Atlas   ( 6184): Validating map...
,W/chromium( 6184): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6184): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6184): Enabling debug mode 0
,I/Keyboard.Facilitator( 1421): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,940
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +846ms (total +940ms)
,W/IInputConnectionWrapper( 6184): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6184): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6184): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6184): Cannot call determinedVisibility() - never saw a connection for the pid: 6184
,D/JsMessageQueue( 6184): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6184): JniHelper::setJavaVM(0xb7d06310), pthread_self() = -1207343760
,I/chromium( 6184): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/art     ( 6184): Suspending all threads took: 10.405ms
,W/jxcore-log( 6184): Initializing JXcore engine
W/jxcore-log( 6184): JXcore engine is ready
,I/art     ( 6184): Background sticky concurrent mark sweep GC freed 9516(905KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 11.554ms total 39.901ms
,W/Thread-738( 6248): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10524 path="socket:[5607]" dev="sockfs" ino=5607 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-738( 6248): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10524 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-738( 6248): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10524 path="socket:[7420]" dev="sockfs" ino=7420 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-738( 6248): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10524 path="socket:[28927]" dev="sockfs" ino=28927 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6184): Starting JXcore engine
,W/jxcore-log( 6184): Platform android
W/jxcore-log( 6184): 
,W/jxcore-log( 6184): Process ARCH arm
W/jxcore-log( 6184): 
,I/jxcore-log( 6184): JXcore Cordova bridge is ready!
I/jxcore-log( 6184): 
W/jxcore-log( 6184): JXcore engine is started
,E/jxcore  ( 6184): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6184): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6184): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  882): Killing 5816:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_5816/cgroup.procs: No such file or directory
,W/PluginManager( 6184): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 122ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2571): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2571): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2571): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2571): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2571): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2571): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1421): onFinishInput()
W/IInputConnectionWrapper( 6184): showStatusIcon on inactive InputConnection
,D/TaskPersister(  882): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC

```
