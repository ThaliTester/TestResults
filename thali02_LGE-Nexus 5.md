#### Test 61703351ed386f4_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
I/ActivityManager(  737): Waited long enough for: ServiceRecord{9aaa57c u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,--------- beginning of main
D/Finsky  ( 1966): [170] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 1966): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2918): 
D/AndroidRuntime( 2918): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2918): CheckJNI is OFF
D/AndroidRuntime( 2918): Calling main entry com.android.commands.am.Am
I/ActivityManager(  737): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2918): Shutting down VM
I/ActivityManager(  737): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2949 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1333): mic_close gfk@1409b30b
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1333): Stopping hotword detection.
I/HotwordRecognitionRnr( 1333): Hotword detection finished
I/WebViewFactory( 2949): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2949): Time to load native libraries: 2 ms (timestamps 5236-5238)
I/LibraryLoader( 2949): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2949): Binding Chromium to main looper Looper (main, tid 1) {e0e4220}
I/LibraryLoader( 2949): Expected native library version number "",actual native library version number ""
I/chromium( 2949): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2949): Initializing chromium process, singleProcess=true
W/art     ( 2949): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2949): ApplicationContext is null in ApplicationStatus
,W/chromium( 2949): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2949): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2949): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2949): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  737): Message: 20
D/BluetoothManagerService(  737): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d8604f4:true
,D/BluetoothAdapter( 2949): 533289109: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2949): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2949): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2949): CordovaWebView is running on device made by: LGE
,W/art     ( 2949): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2949): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  737): Waited long enough for: ServiceRecord{38622357 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,D/OpenGLRenderer( 2949): Render dirty regions requested: true
,D/Atlas   ( 2949): Validating map...
,W/chromium( 2949): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2949): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2949): Enabling debug mode 0
,D/SurfaceFlinger(  177): shader cache generated - 24 shaders in 153.844116 ms
,I/ActivityManager(  737): Displayed com.example.hello/.MainActivity: +583ms (total +34s56ms)
,I/Keyboard.Facilitator( 1091): onFinishInput()
,W/BindingManager( 2949): Cannot call determinedVisibility() - never saw a connection for the pid: 2949
,I/chromium( 2949): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2949): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2949): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 2949): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,W/jxcore-log( 2949): Initializing JXcore engine
W/jxcore-log( 2949): JXcore engine is ready
,W/Thread-286( 3018): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7998]" dev="sockfs" ino=7998 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-286( 3018): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-286( 3018): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6578]" dev="sockfs" ino=6578 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-286( 3018): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17346]" dev="sockfs" ino=17346 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2949): Starting JXcore engine
,W/jxcore-log( 2949): Platform android
W/jxcore-log( 2949): 
W/jxcore-log( 2949): Process ARCH arm
W/jxcore-log( 2949): 
,I/jxcore-log( 2949): JXcore Cordova bridge is ready!
I/jxcore-log( 2949): 
,W/jxcore-log( 2949): JXcore engine is started
,E/jxcore-log( 2949): >> LGE-Nexus 5
E/jxcore-log( 2949): 
,I/jxcore-log( 2949): Total memory 1946181632
I/jxcore-log( 2949): 
I/jxcore-log( 2949): Free memory 325263360
I/jxcore-log( 2949): 
I/jxcore-log( 2949): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2949): 
I/jxcore-log( 2949): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2949): 
,I/jxcore-log( 2949): userPath [ 'www', 'www' ]
I/jxcore-log( 2949): 
,I/jxcore-log( 2949): Size 1080 1776
I/jxcore-log( 2949): 
,I/jxcore-log( 2949): Screen Brightness 82
I/jxcore-log( 2949): 
,E/jxcore-log( 2949): Dummy Error Log.
E/jxcore-log( 2949): 
,I/jxcore-log( 2949): getBuffer is called!!!!
I/jxcore-log( 2949): 
,I/ActivityManager(  737): Killing 2328:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  737): failed to open /acct/uid_10071/pid_2328/cgroup.procs: No such file or directory
,I/CheckinService( 1579): Done disabling old GoogleServicesFramework version
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  737): Message: 2
,D/WifiService(  737): New client listening to asynchronous messages
,D/WifiService(  737): setWifiEnabled: false pid=2949, uid=10278
E/WifiService(  737): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2949): ****TEST TOOK:  5038  ms ****
I/jxcore-log( 2949): 
I/jxcore-log( 2949): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2949): 
,D/AndroidRuntime( 3070): 
D/AndroidRuntime( 3070): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3070): CheckJNI is OFF
,D/AndroidRuntime( 3070): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  737): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  737): Killing 2949:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  737): WIN DEATH: Window{2d2e9324 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  737): Client connection lost with reason: 4
,W/PackageSettings(  737): Skipping PackageSetting{181a36dd com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  737): Force removing ActivityRecord{23a9371 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  737): Spurious death for ProcessRecord{145f22bc 2949:com.example.hello/u0a278}, curProc for 2949: null
,I/ActivityManager(  737): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/Keyboard.Facilitator( 1091): resetDictionaries() : en_US
,I/InputReader(  737): Reconfiguring input devices.  changes=0x00000010
,W/InputMethodManagerService(  737): Got RemoteException sending setActive(false) notification to pid 2949 uid 10278
,W/GeofencerStateMachine( 1297): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1091): onFinishInput()
,I/MicrophoneInputStream( 1333): mic_starting gfk@275a799a
I/HotwordRecognitionRnr( 1333): Starting hotword detection.
,I/AudioFlinger(  184): AudioFlinger's thread 0xb5085000 ready to run
,I/MicrophoneInputStream( 1333): mic_started gfk@275a799a
D/VoicemailCleanupService( 1373): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator.DecoderInitializer( 1091): run()
D/audio_hw_primary(  184): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  184): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  184): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  184): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  737): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3110 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/art     (  737): Explicit concurrent mark sweep GC freed 22450(1328KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.589ms total 115.830ms
I/art     (  737): WaitForGcToComplete blocked for 103.527ms for cause Explicit
,D/BackupManagerService(  737): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  737): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  737): removeObsoleteFile: deleting file=220_task.xml
,I/HotwordWorker( 1333): onReady
,I/art     (  737): Explicit concurrent mark sweep GC freed 8665(483KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 993us total 101.907ms
I/art     (  737): WaitForGcToComplete blocked for 130.243ms for cause Explicit
,D/AndroidRuntime( 3070): Shutting down VM
,I/art     (  737): Explicit concurrent mark sweep GC freed 1093(52KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 1.027ms total 62.169ms
,I/Decoder ( 1091): createOrResetDecoder
,I/UpdateIcingCorporaServi( 1333): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/Launcher( 1318): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@18f817d9 new=com.google.android.velvet.VelvetApplication@18f817d9
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1091): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1091): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/ActivityManager(  737): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3135 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = contacts
,I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 188us total 9.944ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.625ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 7.876ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = history
I/ActivityManager(  737): Killing 2357:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1091): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1091): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1091): run()
I/StatsUtilsManager( 1091): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1091): shouldRecordStats() = Too Soon
,W/libprocessgroup(  737): failed to open /acct/uid_1000/pid_2357/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1333): UpdateCorporaTask done [took 116 ms] updated apps [took 116 ms] 
,W/ContextImpl( 3135): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1579): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1579): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1579): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1579): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 1318): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1579): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1579): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1297): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1297): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/ResourcesManager( 1318): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  737): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3159 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/LocationSettingsChecker( 1579): Removing dialog suppression flag for package com.example.hello
,I/ActivityManager(  737): Killing 1562:com.android.defcontainer/u0a5 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1579): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1579): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1579): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1579): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1579): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1579): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1579): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1579): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1579): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1579): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1579): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1579): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1579): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/libprocessgroup(  737): failed to open /acct/uid_10005/pid_1562/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1579): App measurement is starting up, version: 8489
I/GMPM-SVC( 1579): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/OpenGLRenderer( 1318): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1318): Incorrectly called buildLayer on View: adg, destroying layer...
,W/BaseAppContext( 1579): Using Auth Proxy for data requests.
,W/BaseAppContext( 1579): Using Auth Proxy for data requests.
,E/SQLiteDatabase( 1579): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1579): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1579): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1579): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/SQLiteDatabase( 1579): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1579): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1579): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1579): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1579): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1579): Runtime exception while performing operation
E/ClearPendingStateOp( 1579): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1579): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1579): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteOpenHel,per.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1579): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1579): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1579): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1579): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1579): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1579): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1579): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1579): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1579): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1579): 	at java.lang.Thread.run(Thread.java:818)
W/FileUtils( 1579): Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,F/ClearPendingStateOp( 1579): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1579): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1579): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1579): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1579): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1579): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1579): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1579): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1579): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1579): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1579): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1579): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1579): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1579): 	at java.lang.Thread.run(Thread.java:818)
,D/ConnectivityService(  737): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SQLiteLog( 1579): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DropBoxManagerService(  737): Can't write: system_app_wtf
E/DropBoxManagerService(  737): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  737): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  737): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  737): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  737): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  737): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  737): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  737): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  737): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  737): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  737): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  737): 	... 5 more
,I/Icing   ( 1579): doRemovePackageData com.example.hello
,W/FileUtils( 1579): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/Icing   ( 1579): Failed to open Apps corpus file.
,--------- beginning of crash
E/AndroidRuntime( 1579): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1579): Process: com.google.android.gms, PID: 1579
E/AndroidRuntime( 1579): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1579): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1579): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1579): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1579): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1579): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1579): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1579): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1579): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1579): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1579): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1579): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1579): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1579): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1579): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing   ( 1579): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
,E/DropBoxManagerService(  737): Can't write: system_app_crash
E/DropBoxManagerService(  737): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  737): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  737): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  737): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  737): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  737): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  737): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  737): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  737): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  737): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  737): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  737): 	... 5 more
,E/SQLiteDatabase( 1579): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1579): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1579): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1579): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1579): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1579): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 1579): Opening the database failed, dropping and recreating it
,E/SQLiteDatabase( 1579): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1579): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1579): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1579): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1579): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1579): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1579): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1579): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 1579): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 1579): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/GMPM-SVC( 1579): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 1579): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 1579): Error querying app: com.example.hello, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
,D/OpenGLRenderer(  737): Render dirty regions requested: true
,D/Atlas   (  737): Validating map...
,W/GMPM-SVC( 1579): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
,E/GMPM-SVC( 1579): Task exception on worker thread: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
,E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1579): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/qdhwcomposer(  177): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  177): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  177): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  177): MdpData failed to play
E/qdoverlay(  177): == Dump MdpData start ==
E/qdoverlay(  177): == Dump OvFD fd=30 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  177): mOvData msmfb_overlay_data id=64
E/qdoverlay(  177): data msmfb_data offset=0 memid=38 id=0 flags=0x0 priv=0
E/qdoverlay(  177): == Dump MdpData end ==
E/qdhwcomposer(  177): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  177): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  177): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  177): hwc_set_primary: display commit fail!
W/DriveInitializer( 1579): Awaiting to be initialized
W/DriveInitializer( 1579): Background init thread started
E/SQLiteLog( 1579): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
I/Adreno-EGL(  737): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  737): Initialized EGL, version 1.4
D/OpenGLRenderer(  737): Enabling debug mode 0
E/qdoverlay(  177): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  177): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  177): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  177): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  177): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  177): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  177): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  177): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  177): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  177): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  177): Ctrl commit failed set overlay
E/qdhwcomposer(  177): configureLowRes: commit failed for low res panel
E/qdoverlay(  177): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  177): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  177): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  177): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  177): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  177): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  177): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  177): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  177): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  177): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  177): Ctrl commit failed set overlay
E/qdhwcomposer(  177): configure: commit fails
E/qdoverlay(  177): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  177): MdpCtrl close error in unset

```
