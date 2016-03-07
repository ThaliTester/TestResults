#### Test 6170335106d974e_thali04_motorola-XT1072 Logs


```
--------- beginning of system
V/AlarmManager(  884): send {11e398fc, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
V/AlarmManager(  884): done {11e398fc, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [15ms]
--------- beginning of main
D/CAR.SERVICE( 4997): mConnectedToCar = false, abort
E/ActivityThread( 4997): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 4997): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 4997): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 4997): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 4997): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 4997): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 4997): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4997): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4997): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4997): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 4997): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 4997): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 4997): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 4997): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 4997): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 4997): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 4997): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 4997): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 4997): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4997): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4997): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 4997): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4997): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4997): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 4997): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/ActivityThread( 4997): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 4997): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 4997): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 4997): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 4997): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 4997): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 4997): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4997): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 4997): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 4997): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 4997): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 4997): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 4997): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 4997): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 4997): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 4997): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 4997): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 4997): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4997): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4997): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 4997): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4997): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4997): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 4997): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ActivityManager(  884): Unbind failed: could not find connection for android.os.BinderProxy@1bb56dda
E/SQLiteLog( 5043): (284) automatic index on view_events(_id)
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 5077): 
D/AndroidRuntime( 5077): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5077): CheckJNI is OFF
D/AndroidRuntime( 5077): Calling main entry com.android.commands.am.Am
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  281): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (173 us)
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5077): Shutting down VM
I/ActivityManager(  884): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5096 uid=10555 gids={50555, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5096): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5096): Time to load native libraries: 2 ms (timestamps 3026-3028)
I/LibraryLoader( 5096): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5096): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 5096): Expected native library version number "",actual native library version number ""
,I/chromium( 5096): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5096): Initializing chromium process, singleProcess=true
,W/art     ( 5096): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5096): ApplicationContext is null in ApplicationStatus
,W/chromium( 5096): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5096): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5096): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5096): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5096): Local Branch: 
I/Adreno-EGL( 5096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5096): Local Patches: NONE
I/Adreno-EGL( 5096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  884): Message: 20
,D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1304c4d7:true
,D/BluetoothAdapter( 5096): 343958975: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5096): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5096): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5096): CordovaWebView is running on device made by: motorola
,W/art     ( 5096): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5096): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5096): Render dirty regions requested: true
,D/Atlas   ( 5096): Validating map...
,W/chromium( 5096): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5096): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5096): Enabling debug mode 0
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.example.hello/.MainActivity,cp,ca,979
I/ActivityManager(  884): Displayed com.example.hello/.MainActivity: +979ms
,E/Adreno-ES20( 5096): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5096): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5096): Cannot call determinedVisibility() - never saw a connection for the pid: 5096
,I/chromium( 5096): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5096): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5096): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5096): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5096): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5096): JniHelper::setJavaVM(0xb7a8e310), pthread_self() = -1209847328
,W/jxcore-log( 5096): Initializing JXcore engine
W/jxcore-log( 5096): JXcore engine is ready
,I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (42:323 vsyncs) (44:1160)
,I/SFPerfTracer(  281):      triggers: (rate: 12:406) (compose: 0:1) (post: 0:1) (render: 0:2) (30:1077 frames) (31:1160)
,D/SFPerfTracer(  281):        layers: (3:11) (FocusedStackFrame (0xb7823ed0): 0:14)* (DimLayer (0xb780a660): 0:6)* (StatusBar (0xb77eb478): 0:145) (NavigationBar (0xb77ef0c0): 0:25) (com.android.systemui.ImageWallpaper (0xb782cfd0): 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb77cb330): 0:51)- (Starting com.example.hello (0xb78334a8): 0:41)- (com.example.hello/com.example.hello.MainActivity (0xb77e83e8): 31:36) 
,W/Thread-592( 5146): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10555 path="socket:[9335]" dev="sockfs" ino=9335 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-592( 5146): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10555 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-592( 5146): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10555 path="socket:[9421]" dev="sockfs" ino=9421 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-592( 5146): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10555 path="socket:[22906]" dev="sockfs" ino=22906 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5096): Starting JXcore engine
,W/jxcore-log( 5096): Platform android
W/jxcore-log( 5096): 
,W/jxcore-log( 5096): Process ARCH arm
W/jxcore-log( 5096): 
,I/jxcore-log( 5096): JXcore Cordova bridge is ready!
I/jxcore-log( 5096): 
,W/jxcore-log( 5096): JXcore engine is started
,E/jxcore-log( 5096): >> motorola-XT1072
E/jxcore-log( 5096): 
,I/jxcore-log( 5096): Total memory 916258816
I/jxcore-log( 5096): 
,I/jxcore-log( 5096): Free memory 36945920
I/jxcore-log( 5096): 
I/jxcore-log( 5096): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5096): 
I/jxcore-log( 5096): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5096): 
I/jxcore-log( 5096): userPath [ 'www', 'www' ]
I/jxcore-log( 5096): 
I/jxcore-log( 5096): Size 720 1184
I/jxcore-log( 5096): 
I/jxcore-log( 5096): Screen Brightness 82
I/jxcore-log( 5096): 
E/jxcore-log( 5096): Dummy Error Log.
E/jxcore-log( 5096): 
,I/jxcore-log( 5096): getBuffer is called!!!!
I/jxcore-log( 5096): 
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:36000 mC
,V/AlarmManager(  884): send {38e1f2bf, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  884): done {38e1f2bf, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [11ms]
,V/AlarmManager(  884): send {ee4bd8c, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): done {ee4bd8c, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,I/ActivityManager(  884): Killing 4896:com.android.vending/u0a32 (adj 15): empty #7
,I/ActivityManager(  884): Killing 4997:com.google.android.gms:car/u0a16 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_4896/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_4997/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  884): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  884): Message: 2
,D/WifiService(  884): New client listening to asynchronous messages
,D/WifiService(  884): setWifiEnabled: false pid=5096, uid=10555
E/WifiService(  884): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5096): ****TEST TOOK:  5080  ms ****
I/jxcore-log( 5096): 
,I/jxcore-log( 5096): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5096): 
,D/AndroidRuntime( 5174): 
D/AndroidRuntime( 5174): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5174): CheckJNI is OFF
,D/AndroidRuntime( 5174): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  884): Force stopping com.example.hello appid=10555 user=-1: uninstall pkg
,I/ActivityManager(  884): Killing 5096:com.example.hello/u0a555 (adj 0): stop com.example.hello
,I/WindowState(  884): WIN DEATH: Window{1faa91c7 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  884): Client connection lost with reason: 4
,W/PackageSettings(  884): Skipping PackageSetting{62c8e4d com.test.thalitest/10554} due to missing metadata
,W/ActivityManager(  884): Force removing ActivityRecord{2454620b u0 com.example.hello/.MainActivity t9}: app died, no saved state
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  884): Spurious death for ProcessRecord{2f6d8cd5 5096:com.example.hello/u0a555}, curProc for 5096: null
,I/ActivityManager(  884): Force stopping com.example.hello appid=10555 user=0: pkg removed
,I/art     ( 2952): Explicit concurrent mark sweep GC freed 3529(209KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 698us total 31.521ms
,I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
W/GeofencerStateMachine( 1714): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1409): createOrResetDecoder
,I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5194 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 7359(535KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 449us total 131.103ms
,D/OtaApp  ( 2522): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2522): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2522): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2522): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2522): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1714): onCreate
,W/InputMethodManagerService(  884): Got RemoteException sending setActive(false) notification to pid 5096 uid 10555
,I/art     (  884): Explicit concurrent mark sweep GC freed 19851(1240KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 6.550ms total 169.417ms
,I/art     (  884): WaitForGcToComplete blocked for 72.371ms for cause Explicit
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 5194): Cleaning up data for package: com.example.hello
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5228 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task.xml
,I/ContactLocale( 5194): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  884): Explicit concurrent mark sweep GC freed 6177(344KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.582ms total 194.516ms
,I/Launcher( 1561): Deferring update until onResume
,I/ActivityManager(  884): Killing 4706:com.android.defcontainer/u0a10 (adj 15): empty #7
,D/AndroidRuntime( 5174): Shutting down VM
,W/libprocessgroup(  884): failed to open /acct/uid_10010/pid_4706/cgroup.procs: No such file or directory
,W/asset   ( 5228): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5228): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5228): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5228): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5249 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4968:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_4968/cgroup.procs: No such file or directory
,W/ContextImpl( 5249): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 1945): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1945): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1945): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1945): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/NetworkScheduler.SchedulerReceiver( 1714): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1714): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5274 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 1945): doRemovePackageData com.example.hello
,W/Launcher( 1561): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,E/SQLiteLog( 1561): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5301 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5324 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5344 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  884): send {10bce947, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  884): done {10bce947, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [40ms]
,I/art     (  317): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.701ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.182ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.039ms
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
