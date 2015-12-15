#### Test 50388019385b4d9_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  880): send {cb97207, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  880): send {15ccc84d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): done {cb97207, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [10ms]
V/AlarmManager(  880): done {15ccc84d, *alarm*:android.intent.action.TIME_TICK} [44ms]
--------- beginning of main
D/AndroidRuntime( 5372): 
D/AndroidRuntime( 5372): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5372): CheckJNI is OFF
D/AndroidRuntime( 5372): Calling main entry com.android.commands.am.Am
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5391 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5372): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5391): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5391): Time to load native libraries: 3 ms (timestamps 4734-4737)
I/LibraryLoader( 5391): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5391): Binding Chromium to main looper Looper (main, tid 1) {1395f4a0}
,I/LibraryLoader( 5391): Expected native library version number "",actual native library version number ""
,I/chromium( 5391): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5391): Initializing chromium process, singleProcess=true
,W/art     ( 5391): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5391): ApplicationContext is null in ApplicationStatus
,W/chromium( 5391): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5391): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5391): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5391): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5391): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5391): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5391): Local Branch: 
I/Adreno-EGL( 5391): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5391): Local Patches: NONE
I/Adreno-EGL( 5391): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21a0fee3:true
,D/BluetoothAdapter( 5391): 500359445: getState() :  mService = null. Returning STATE_OFF
,I/art     (  880): Explicit concurrent mark sweep GC freed 17510(824KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.254ms total 115.938ms
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{280e52dc u0 com.example.hello/.MainActivity t3}
,W/art     ( 5391): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5391): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5391): CordovaWebView is running on device made by: motorola
,W/art     ( 5391): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5391): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5391): Render dirty regions requested: true
,D/Atlas   ( 5391): Validating map...
,W/chromium( 5391): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5391): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5391): Enabling debug mode 0
,I/Keyboard.Facilitator( 1405): onFinishInput()
,W/IInputConnectionWrapper( 5391): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  880): Displayed com.example.hello/.MainActivity,cp,ca,995
I/ActivityManager(  880): Displayed com.example.hello/.MainActivity: +908ms (total +995ms)
,E/Adreno-ES20( 5391): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5391): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5391): Cannot call determinedVisibility() - never saw a connection for the pid: 5391
,I/chromium( 5391): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5391): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5391): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5391): JniHelper::setJavaVM(0xb752f310), pthread_self() = -1215558848
,D/JX-Cordova( 5391): jxcore cordova android initializing
,W/jxcore-log( 5391): Initializing JXcore engine
W/jxcore-log( 5391): JXcore engine is ready
,W/jxcore-log( 5391): Starting JXcore engine
,W/m.example.hello( 5391): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10373 path="socket:[9491]" dev="sockfs" ino=9491 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 5391): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10373 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5391): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10373 path="socket:[9616]" dev="sockfs" ino=9616 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5391): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10373 path="socket:[23310]" dev="sockfs" ino=23310 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5391): Platform android
W/jxcore-log( 5391): 
W/jxcore-log( 5391): Process ARCH arm
W/jxcore-log( 5391): 
,I/jxcore-log( 5391): JXcore Cordova bridge is ready!
I/jxcore-log( 5391): 
,W/jxcore-log( 5391): JXcore engine is started
,E/jxcore-log( 5391): >> motorola-XT1072
E/jxcore-log( 5391): 
,I/jxcore-log( 5391): Total memory 916258816
I/jxcore-log( 5391): 
,I/jxcore-log( 5391): Free memory 35090432
I/jxcore-log( 5391): 
I/jxcore-log( 5391): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5391): 
I/jxcore-log( 5391): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5391): 
I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 5391): userPath [ 'www' ]
I/jxcore-log( 5391): 
,I/jxcore-log( 5391): Size 720 1184
I/jxcore-log( 5391): 
,I/jxcore-log( 5391): Screen Brightness 82
I/jxcore-log( 5391): 
,E/jxcore-log( 5391): Dummy Error Log.
E/jxcore-log( 5391): 
,I/jxcore-log( 5391): getBuffer is called!!!!
I/jxcore-log( 5391): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  880): Message: 2
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: false pid=5391, uid=10373
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5391): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 5391): 
I/jxcore-log( 5391): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5391): 
,D/AndroidRuntime( 5451): 
D/AndroidRuntime( 5451): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5451): CheckJNI is OFF
,D/AndroidRuntime( 5451): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5391:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/WindowState(  880): WIN DEATH: Window{2c3f66d3 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  880): Client connection lost with reason: 4
,W/PackageSettings(  880): Skipping PackageSetting{32219953 com.test.thalitest/10371} due to missing metadata
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{280e52dc u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  880): Spurious death for ProcessRecord{9646f3c 5391:com.example.hello/u0a373}, curProc for 5391: null
,I/ActivityManager(  880): Force stopping com.example.hello appid=10373 user=0: pkg removed
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{280e52dc u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager(  880): Duplicate finish request for ActivityRecord{280e52dc u0 com.example.hello/.MainActivity t3 f}
,I/art     ( 3152): Explicit concurrent mark sweep GC freed 9308(2MB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 1.207ms total 34.870ms
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1689): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1405): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1405): run()
I/Decoder ( 1405): createOrResetDecoder
,D/OtaApp  ( 2722): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2722): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2722): publish the event [tag = MOT_OTA event name = LOG]
,D/VoicemailCleanupService( 5086): Cleaning up data for package: com.example.hello
,I/art     ( 1555): Explicit concurrent mark sweep GC freed 7301(530KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 498us total 131.178ms
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5482 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/OtaApp  ( 2722): [debug] > cancelling the previous pending intent set for download later
,I/art     ( 1933): Explicit concurrent mark sweep GC freed 13710(803KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 1.012ms total 164.964ms
,I/OtaApp  ( 2722): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2722): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1689): onCreate
,I/art     (  880): Explicit concurrent mark sweep GC freed 9230(751KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 19MB/29MB, paused 7.897ms total 170.158ms
I/art     (  880): WaitForGcToComplete blocked for 110.303ms for cause Explicit
,W/asset   ( 5482): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5482): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5482): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5482): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  880): Got RemoteException sending setActive(false) notification to pid 5391 uid 10373
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1405): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1405): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1405): run()
I/StatsUtilsManager( 1405): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1405): shouldRecordStats() = Too Soon
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5509 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  880): Killing 5186:com.google.android.apps.docs/u0a57 (adj 15): empty #7
I/Launcher( 1555): Deferring update until onResume
,I/art     (  880): Explicit concurrent mark sweep GC freed 4853(260KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.676ms total 206.352ms
,D/AndroidRuntime( 5451): Shutting down VM
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_5186/cgroup.procs: No such file or directory
,W/ContextImpl( 5509): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 1933): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1933): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1933): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1933): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1933): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1933): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1933): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1933): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/NetworkScheduler.SchedulerReceiver( 1689): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1689): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1933): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1933): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1933): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1933): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1933): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1933): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1933): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1933): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1933): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5534 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1933): Module APK com.google.android.play.games already loaded
,I/Icing   ( 1933): doRemovePackageData com.example.hello
,W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1e9c6c2a new=com.google.android.velvet.VelvetApplication@1e9c6c2a
,I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5559 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
