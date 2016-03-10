#### Test 623445121bdd37c_thali04_motorola-XT1072 Logs


```
--------- beginning of main
D/CAR.SERVICE( 5013): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 5013): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@28d77434 that was originally bound here
E/ActivityThread( 5013): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@28d77434 that was originally bound here
E/ActivityThread( 5013): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5013): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5013): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5013): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5013): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5013): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5013): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5013): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5013): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5013): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5013): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5013): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5013): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5013): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5013): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5013): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5013): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5013): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5013): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/ActivityThread( 5013): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@305383ff that was originally bound here
E/ActivityThread( 5013): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@305383ff that was originally bound here
E/ActivityThread( 5013): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5013): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5013): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5013): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5013): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5013): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5013): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5013): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5013): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5013): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5013): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5013): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5013): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5013): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5013): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5013): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5013): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5013): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ActivityManager(  895): Unbind failed: could not find connection for android.os.BinderProxy@20792249
,V/AlarmManager(  895): send {97c074e, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
V/AlarmManager(  895): done {97c074e, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [28ms]
E/SQLiteLog( 4913): (284) automatic index on view_events(_id)
D/AndroidRuntime( 5056): 
D/AndroidRuntime( 5056): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5056): CheckJNI is OFF
D/AndroidRuntime( 5056): Calling main entry com.android.commands.am.Am
I/ActivityManager(  895): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  281): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (144 us)
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5056): Shutting down VM
I/SFPerfTracer(  281):      triggers: (rate: 16:501) (compose: 0:1) (post: 0:1) (render: 0:2) (0:881 frames) (1:948)
D/SFPerfTracer(  281):        layers: (3:12) (FocusedStackFrame (0xb7452da0): 0:9)* (DimLayer (0xb745a1a0): 0:3)* (StatusBar (0xb745dc50): 0:158) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb749e7c8): 0:49)- (NavigationBar (0xb74a04e0): 0:24) (com.android.systemui.ImageWallpaper (0xb750ae90): 0:33)* (Starting com.motorola.ccc.ota (0xb750cb00): 0:34)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb750dd90): 0:29) (Starting com.example.hello (0xb750cb00): 1:1)* 
I/ActivityManager(  895): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5076 uid=10567 gids={50567, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5076): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5076): Time to load native libraries: 1 ms (timestamps 3018-3019)
I/LibraryLoader( 5076): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5076): Binding Chromium to main looper Looper (main, tid 1) {1e817d0c}
I/LibraryLoader( 5076): Expected native library version number "",actual native library version number ""
I/chromium( 5076): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5076): Initializing chromium process, singleProcess=true
W/art     ( 5076): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5076): ApplicationContext is null in ApplicationStatus
W/chromium( 5076): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5076): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5076): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5076): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5076): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5076): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5076): Local Branch: 
I/Adreno-EGL( 5076): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5076): Local Patches: NONE
I/Adreno-EGL( 5076): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  895): Message: 20
D/BluetoothManagerService(  895): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d0e4c98:true
D/BluetoothAdapter( 5076): 976992311: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5076): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5076): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5076): CordovaWebView is running on device made by: motorola
W/art     ( 5076): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5076): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5076): Render dirty regions requested: true
,D/Atlas   ( 5076): Validating map...
,W/chromium( 5076): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5076): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5076): Enabling debug mode 0
,I/Keyboard.Facilitator( 1424): onFinishInput()
,I/LaunchCheckinHandler(  895): Displayed com.example.hello/.MainActivity,cp,ca,977
I/ActivityManager(  895): Displayed com.example.hello/.MainActivity: +977ms
,E/Adreno-ES20( 5076): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5076): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5076): Cannot call determinedVisibility() - never saw a connection for the pid: 5076
,I/chromium( 5076): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5076): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5076): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5076): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5076): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5076): JniHelper::setJavaVM(0xb8434310), pthread_self() = -1199844712
D/JX-Cordova( 5076): jxcore cordova android initializing
,W/jxcore-log( 5076): Initializing JXcore engine
W/jxcore-log( 5076): JXcore engine is ready
,W/jxcore-log( 5076): Starting JXcore engine
,W/m.example.hello( 5076): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10567 path="socket:[5622]" dev="sockfs" ino=5622 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 5076): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10567 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 5076): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10567 path="socket:[7064]" dev="sockfs" ino=7064 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5076): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10567 path="socket:[23783]" dev="sockfs" ino=23783 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5076): Platform android
W/jxcore-log( 5076): 
,W/jxcore-log( 5076): Process ARCH arm
W/jxcore-log( 5076): 
,I/jxcore-log( 5076): JXcore Cordova bridge is ready!
I/jxcore-log( 5076): 
W/jxcore-log( 5076): JXcore engine is started
,E/jxcore-log( 5076): >> motorola-XT1072
E/jxcore-log( 5076): 
,I/jxcore-log( 5076): Total memory 916258816
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): Free memory 36827136
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5076): 
I/jxcore-log( 5076): userPath [ 'www' ]
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): Size 720 1184
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): Screen Brightness 82
I/jxcore-log( 5076): 
,E/jxcore-log( 5076): Dummy Error Log.
E/jxcore-log( 5076): 
,I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:316 vsyncs) (1:1045)
,I/ActivityManager(  895): Killing 2995:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/ActivityManager(  895): Killing 4986:com.motorola.context/u0a8 (adj 15): empty #8
,W/libprocessgroup(  895): failed to open /acct/uid_10049/pid_2995/cgroup.procs: No such file or directory
,W/libprocessgroup(  895): failed to open /acct/uid_10008/pid_4986/cgroup.procs: No such file or directory
,I/jxcore-log( 5076): getBuffer is called!!!!
I/jxcore-log( 5076): 
,I/SFPerfTracer(  281):      triggers: (rate: 16:502) (compose: 0:1) (post: 0:1) (render: 0:2) (12:974 frames) (13:1058)
,D/SFPerfTracer(  281):        layers: (3:11) (FocusedStackFrame (0xb7452da0): 0:14)* (DimLayer (0xb745a1a0): 0:6)* (StatusBar (0xb745dc50): 0:158) (NavigationBar (0xb74a04e0): 0:24) (com.android.systemui.ImageWallpaper (0xb750ae90): 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb750dd90): 0:57)- (Starting com.example.hello (0xb750cb00): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb749f1a8): 13:55) 
,D/TaskPersister(  895): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:35000 mC
,V/AlarmManager(  895): send {25c48be0, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  895): done {25c48be0, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [6ms]
,V/AlarmManager(  895): send {68dfe99, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  895): done {68dfe99, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  895): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  895): Message: 2
,D/WifiService(  895): New client listening to asynchronous messages
,D/WifiService(  895): setWifiEnabled: false pid=5076, uid=10567
E/WifiService(  895): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5076): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 5076): 
I/jxcore-log( 5076): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5076): 
,D/AndroidRuntime( 5153): 
D/AndroidRuntime( 5153): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5153): CheckJNI is OFF
,D/AndroidRuntime( 5153): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  895): Force stopping com.example.hello appid=10567 user=-1: uninstall pkg
I/ActivityManager(  895): Killing 5076:com.example.hello/u0a567 (adj 0): stop com.example.hello
,I/WindowState(  895): WIN DEATH: Window{357a0bc8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  895): Client connection lost with reason: 4
,W/PackageSettings(  895): Skipping PackageSetting{3db6aef com.test.thalitest/10566} due to missing metadata
,W/ActivityManager(  895): Force removing ActivityRecord{f7c017c u0 com.example.hello/.MainActivity t9}: app died, no saved state
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  895): Spurious death for ProcessRecord{115e355e 5076:com.example.hello/u0a567}, curProc for 5076: null
,I/ActivityManager(  895): Force stopping com.example.hello appid=10567 user=0: pkg removed
,W/GeofencerStateMachine( 1737): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  895): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1424): resetDictionaries() : en_US
,I/ActivityManager(  895): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5177 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Keyboard.Facilitator.DecoderInitializer( 1424): run()
,I/art     ( 2936): Explicit concurrent mark sweep GC freed 3391(180KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 7MB/12MB, paused 799us total 70.384ms
,I/art     ( 1574): Explicit concurrent mark sweep GC freed 7254(528KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 473us total 111.172ms
,I/Decoder ( 1424): createOrResetDecoder
,D/OtaApp  ( 2532): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2532): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2532): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2532): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2532): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2532): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2532): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2532): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1737): onCreate
,W/InputMethodManagerService(  895): Got RemoteException sending setActive(false) notification to pid 5076 uid 10567
,I/Keyboard.Facilitator( 1424): onFinishInput()
,I/art     (  895): Explicit concurrent mark sweep GC freed 20050(1247KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 4.002ms total 202.878ms
,I/art     (  895): WaitForGcToComplete blocked for 125.153ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1424): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1424): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1424): run()
I/StatsUtilsManager( 1424): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1424): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 5177): Cleaning up data for package: com.example.hello
,I/ActivityManager(  895): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5207 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 5177): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/BackupManagerService(  895): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  895): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  895): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  895): removeObsoleteFile: deleting file=8_task.xml
,I/Launcher( 1574): Deferring update until onResume
,I/ActivityManager(  895): Killing 5013:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/art     (  895): Explicit concurrent mark sweep GC freed 5838(332KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.609ms total 181.618ms
,W/libprocessgroup(  895): failed to open /acct/uid_10016/pid_5013/cgroup.procs: No such file or directory
,D/AndroidRuntime( 5153): Shutting down VM
,W/asset   ( 5207): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5207): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5207): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5207): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  895): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5225 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 4895:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10032/pid_4895/cgroup.procs: No such file or directory
,W/ContextImpl( 5225): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 1958): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1958): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1958): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1958): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1958): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1958): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1958): Removing dialog suppression flag for package com.example.hello
E/NetworkScheduler.SchedulerReceiver( 1737): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1737): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1958): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1958): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1958): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1958): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1958): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1958): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1958): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1958): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1958): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1958): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1958): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1958): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1958): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  895): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5254 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/SQLiteLog( 1958): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/FileUtils( 1958): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 1958): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearPendingStateOp( 1958): Runtime exception while performing operation
E/ClearPendingStateOp( 1958): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1958): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1958): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1958): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1958): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1958): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1958): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1958): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1958): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1958): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1958): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1958): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1958): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1958): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1958): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1958): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1958): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1958): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1958): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1958): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 1958): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1958): Process: com.google.android.gms, PID: 1958
E/AndroidRuntime( 1958): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1958): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1958): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1958): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1958): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1958): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1958): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1958): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1958): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1958): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1958): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/GMPM-SVC( 1958): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/DropBoxManagerService(  895): Can't write: system_app_crash
E/DropBoxManagerService(  895): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  895): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  895): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  895): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  895): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  895): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  895): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  895): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  895): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  895): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  895): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  895): 	... 5 more
E/DropBoxManagerService(  895): Can't write: system_app_wtf
E/DropBoxManagerService(  895): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  895): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  895): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  895): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  895): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  895): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  895): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  895): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  895): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  895): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  895): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  895): 	... 5 more
,W/FileUtils( 1958): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1958): Failed to open Apps corpus file.
,E/Icing   ( 1958): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1958): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
,W/ResourcesManager(  895): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  895): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SharedPreferencesImpl( 1958): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/Icing   ( 1958): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1958): Writing status failed
,E/Icing   ( 1958): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/Icing   ( 1958): doRemovePackageData com.example.hello
,D/OpenGLRenderer(  895): Render dirty regions requested: true
,D/Atlas   (  895): Validating map...
,E/qdoverlay(  281): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  281): src msmfb_img w=736 h=64 format=13 MDP_RGBA_8888
E/qdoverlay(  281): src_rect mdp_rect x=0 y=0 w=720 h=50
E/qdoverlay(  281): dst_rect mdp_rect x=0 y=0 w=720 h=50
E/qdoverlay(  281): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  281): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  281): src_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  281): dst_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  281): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  281): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  281): src_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  281): dst_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  281): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  281): MdpCtrl close error in unset
,I/Adreno-EGL(  895): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  895): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  895): Build Date: 10/28/14 Tue
I/Adreno-EGL(  895): Local Branch: 
I/Adreno-EGL(  895): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  895): Local Patches: NONE
I/Adreno-EGL(  895): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/OpenGLRenderer(  895): Initialized EGL, version 1.4
W/Launcher( 1574): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@9e0d136 new=com.google.android.velvet.VelvetApplication@9e0d136
,D/OpenGLRenderer(  895): Enabling debug mode 0
,I/ActivityManager(  895): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5292 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,E/qdoverlay(  281): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  281): MdpCtrl close error in unset
,E/qdhwcomposer(  281): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : No such device
E/SurfaceFlinger(  281): eventControl(0, 1) failed No such device
,E/qdoverlay(  281): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  281): MdpCtrl close error in unset

```
