#### Test 61703351926082e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/Icing   ( 1636): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1636): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 2960): 
D/AndroidRuntime( 2960): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2960): CheckJNI is OFF
D/AndroidRuntime( 2960): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2960): Shutting down VM
I/ActivityManager(  757): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2980 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1346): mic_close gfk@325418d7
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1346): Hotword detection finished
I/HotwordRecognitionRnr( 1346): Stopping hotword detection.
I/WebViewFactory( 2980): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2980): Time to load native libraries: 3 ms (timestamps 6794-6797)
I/LibraryLoader( 2980): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2980): Binding Chromium to main looper Looper (main, tid 1) {3699814e}
I/LibraryLoader( 2980): Expected native library version number "",actual native library version number ""
I/chromium( 2980): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2980): Initializing chromium process, singleProcess=true
,W/art     ( 2980): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2980): ApplicationContext is null in ApplicationStatus
,W/chromium( 2980): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2980): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2980): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2980): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2980): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1825869:true
D/BluetoothAdapter( 2980): 682251915: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2980): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2980): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2980): CordovaWebView is running on device made by: LGE
,W/art     ( 2980): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 2980): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2980): Render dirty regions requested: true
,D/Finsky  ( 2025): [175] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2025): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Atlas   ( 2980): Validating map...
,W/chromium( 2980): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2980): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2980): Enabling debug mode 0
,I/Keyboard.Facilitator( 1080): onFinishInput()
,I/ActivityManager(  757): Displayed com.example.hello/.MainActivity: +453ms (total +34s959ms)
,W/BindingManager( 2980): Cannot call determinedVisibility() - never saw a connection for the pid: 2980
,I/chromium( 2980): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2980): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2980): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 2980): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,W/jxcore-log( 2980): Initializing JXcore engine
W/jxcore-log( 2980): JXcore engine is ready
,W/Thread-286( 3047): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9403]" dev="sockfs" ino=9403 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-286( 3047): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-286( 3047): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6568]" dev="sockfs" ino=6568 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-286( 3047): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19892]" dev="sockfs" ino=19892 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2980): Starting JXcore engine
,W/jxcore-log( 2980): Platform android
W/jxcore-log( 2980): 
W/jxcore-log( 2980): Process ARCH arm
W/jxcore-log( 2980): 
,I/jxcore-log( 2980): JXcore Cordova bridge is ready!
I/jxcore-log( 2980): 
,W/jxcore-log( 2980): JXcore engine is started
,E/jxcore-log( 2980): >> LGE-Nexus 5
E/jxcore-log( 2980): 
,I/jxcore-log( 2980): Total memory 1946181632
I/jxcore-log( 2980): 
I/jxcore-log( 2980): Free memory 299393024
I/jxcore-log( 2980): 
I/jxcore-log( 2980): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2980): 
I/jxcore-log( 2980): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2980): 
,I/jxcore-log( 2980): userPath [ 'www', 'www' ]
I/jxcore-log( 2980): 
,I/jxcore-log( 2980): Size 1080 1776
I/jxcore-log( 2980): 
,I/jxcore-log( 2980): Screen Brightness 82
I/jxcore-log( 2980): 
E/jxcore-log( 2980): Dummy Error Log.
E/jxcore-log( 2980): 
,I/ActivityManager(  757): Waited long enough for: ServiceRecord{9e47fd4 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/jxcore-log( 2980): getBuffer is called!!!!
I/jxcore-log( 2980): 
,I/ActivityManager(  757): Waited long enough for: ServiceRecord{3a42b7ca u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  757): Killing 2332:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10036/pid_2332/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  757): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  757): Message: 2
,D/WifiService(  757): New client listening to asynchronous messages
,D/WifiService(  757): setWifiEnabled: false pid=2980, uid=10278
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2980): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 2980): 
I/jxcore-log( 2980): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2980): 
,D/AndroidRuntime( 3086): 
D/AndroidRuntime( 3086): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3086): CheckJNI is OFF
,D/AndroidRuntime( 3086): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  757): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  757): Killing 2980:com.example.hello/u0a278 (adj 0): stop com.example.hello
,D/WifiService(  757): Client connection lost with reason: 4
,I/WindowState(  757): WIN DEATH: Window{f22d39e u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  757): Skipping PackageSetting{213d6413 com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  757): Force removing ActivityRecord{3de3e4f2 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  757): Spurious death for ProcessRecord{857b876 2980:com.example.hello/u0a278}, curProc for 2980: null
,I/ActivityManager(  757): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/Keyboard.Facilitator( 1080): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1080): run()
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1319): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1080): createOrResetDecoder
,I/art     (  757): Explicit concurrent mark sweep GC freed 21082(1285KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.374ms total 80.526ms
,I/ActivityManager(  757): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3121 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/art     (  757): WaitForGcToComplete blocked for 71.523ms for cause Explicit
,D/VoicemailCleanupService( 1374): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1080): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1080): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  757): removeObsoleteFile: deleting file=220_task.xml
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loading LM = user
,I/UpdateIcingCorporaServi( 1346): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1080): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1080): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1080): run()
I/StatsUtilsManager( 1080): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1080): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 2980 uid 10278
,I/Keyboard.Facilitator( 1080): onFinishInput()
,W/Launcher( 1287): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1516026f new=com.google.android.velvet.VelvetApplication@1516026f
,I/MicrophoneInputStream( 1346): mic_starting gfk@2380df8f
I/HotwordRecognitionRnr( 1346): Starting hotword detection.
I/AudioFlinger(  183): AudioFlinger's thread 0xb4abd000 ready to run
I/MicrophoneInputStream( 1346): mic_started gfk@2380df8f
I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3149 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
I/art     (  195): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 211us total 9.474ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 8.352ms
,I/art     (  757): Explicit concurrent mark sweep GC freed 10047(540KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 951us total 151.548ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 171us total 8.114ms
,I/ActivityManager(  757): Killing 2369:com.google.android.keep/u0a71 (adj 15): empty #17
,D/AndroidRuntime( 3086): Shutting down VM
,W/ResourcesManager( 1287): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/HotwordWorker( 1346): onReady
,W/ResourcesManager( 1287): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  757): failed to open /acct/uid_10071/pid_2369/cgroup.procs: No such file or directory
,W/ContextImpl( 3149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1636): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1636): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1636): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1636): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1636): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1636): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1319): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1319): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1636): Removing dialog suppression flag for package com.example.hello
,I/UpdateIcingCorporaServi( 1346): UpdateCorporaTask done [took 237 ms] updated apps [took 237 ms] 
,D/gH_CompatibleDatabase( 1636): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1636): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1636): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1636): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1636): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1636): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1636): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  757): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3178 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1636): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1636): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1636): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1636): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1636): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1636): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  757): Killing 2400:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2400/cgroup.procs: No such file or directory
,W/BaseAppContext( 1636): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1636): App measurement is starting up, version: 8489
I/GMPM-SVC( 1636): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1636): Using Auth Proxy for data requests.
,I/Icing   ( 1636): doRemovePackageData com.example.hello
,D/ConnectivityService(  757): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/DriveInitializer( 1636): Awaiting to be initialized
,W/DriveInitializer( 1636): Background init thread started
,E/SQLiteLog( 1636): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 1636): Background init thread ended
E/SQLiteLog( 1636): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1636): disk I/O error (code 3850)
E/DriveAsyncService( 1636): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1636): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1636): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1636): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1636): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1636): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1636): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1636): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1636): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1636): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1636): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1636): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1636): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1636): 	at java.lang.Thread.run(Thread.java:818)
,--------- beginning of crash
E/AndroidRuntime( 1636): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1636): Process: com.google.android.gms, PID: 1636
E/AndroidRuntime( 1636): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1636): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1636): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1636): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1636): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1636): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/AndroidRuntime( 1636): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/AndroidRuntime( 1636): 	at com.google.android.gms.drive.database.f.e(SourceFile:858)
E/AndroidRuntime( 1636): 	at com.google.android.gms.drive.events.av.b(SourceFile:192)
E/AndroidRuntime( 1636): 	at com.google.android.gms.drive.events.av.a(SourceFile:158)
E/AndroidRuntime( 1636): 	at com.google.android.gms.drive.t.run(SourceFile:65)
,W/ResourcesManager(  757): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  757): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/OpenGLRenderer( 1287): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1287): Incorrectly called buildLayer on View: adg, destroying layer...
,E/DropBoxManagerService(  757): Can't write: system_app_crash
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  757): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  757): 	... 5 more
,D/OpenGLRenderer(  757): Render dirty regions requested: true
D/Atlas   (  757): Validating map...
,I/Adreno-EGL(  757): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  757): Initialized EGL, version 1.4
D/OpenGLRenderer(  757): Enabling debug mode 0
,E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  172): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  172): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  172): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): Ctrl commit failed set overlay
E/qdhwcomposer(  172): configureLowRes: commit failed for low res panel
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  172): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  172): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  172): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
,E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  172): Ctrl commit failed set overlay
E/qdhwcomposer(  172): configure: commit fails
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl close error in unset
,I/MicrophoneInputStream( 1346): mic_close gfk@2380df8f
,I/CheckinService( 1636): Done disabling old GoogleServicesFramework version
,D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
,I/HotwordRecognitionRnr( 1346): Hotword detection finished
,I/HotwordRecognitionRnr( 1346): Stopping hotword detection.

```
