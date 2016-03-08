#### Test 6170335145aca32_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
--------- beginning of main
I/Icing   ( 1585): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1375): UpdateCorporaTask done [took 726 ms] updated apps [took 726 ms] 
D/AndroidRuntime( 2923): 
D/AndroidRuntime( 2923): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2923): CheckJNI is OFF
D/AndroidRuntime( 2923): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2923): Shutting down VM
I/ActivityManager(  759): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2945 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1375): mic_close gfk@2fa91fe8
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1375): Hotword detection finished
I/HotwordRecognitionRnr( 1375): Stopping hotword detection.
I/WebViewFactory( 2945): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2945): Time to load native libraries: 1 ms (timestamps 4488-4489)
I/LibraryLoader( 2945): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2945): Binding Chromium to main looper Looper (main, tid 1) {1f8f1cdd}
I/LibraryLoader( 2945): Expected native library version number "",actual native library version number ""
I/chromium( 2945): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2945): Initializing chromium process, singleProcess=true
W/art     ( 2945): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2945): ApplicationContext is null in ApplicationStatus
W/chromium( 2945): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2945): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2945): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2945): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2945): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16f4a694:true
D/BluetoothAdapter( 2945): 417308574: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2945): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2945): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2945): CordovaWebView is running on device made by: LGE
W/art     ( 2945): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2945): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  759): Explicit concurrent mark sweep GC freed 17804(886KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 933us total 56.570ms
D/OpenGLRenderer( 2945): Render dirty regions requested: true
D/Atlas   ( 2945): Validating map...
W/chromium( 2945): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2945): Initialized EGL, version 1.4
D/OpenGLRenderer( 2945): Enabling debug mode 0
I/Keyboard.Facilitator( 1071): onFinishInput()
I/ActivityManager(  759): Displayed com.example.hello/.MainActivity: +589ms (total +32s633ms)
W/BindingManager( 2945): Cannot call determinedVisibility() - never saw a connection for the pid: 2945
I/chromium( 2945): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2945): Set native->JS mode to OnlineEventsBridgeMode
I/Icing   ( 1585): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
E/AndroidProtocolHandler( 2945): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/Icing   ( 1585): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/jxcore_app_log( 2945): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
W/jxcore-log( 2945): Initializing JXcore engine
W/jxcore-log( 2945): JXcore engine is ready
W/Thread-281( 3019): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8429]" dev="sockfs" ino=8429 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-281( 3019): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-281( 3019): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9470]" dev="sockfs" ino=9470 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-281( 3019): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19637]" dev="sockfs" ino=19637 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 2945): Starting JXcore engine
W/jxcore-log( 2945): Platform android
W/jxcore-log( 2945): 
W/jxcore-log( 2945): Process ARCH arm
W/jxcore-log( 2945): 
I/jxcore-log( 2945): JXcore Cordova bridge is ready!
I/jxcore-log( 2945): 
W/jxcore-log( 2945): JXcore engine is started
,E/jxcore-log( 2945): >> LGE-Nexus 5
E/jxcore-log( 2945): 
,I/jxcore-log( 2945): Total memory 1946181632
I/jxcore-log( 2945): 
I/jxcore-log( 2945): Free memory 322383872
I/jxcore-log( 2945): 
I/jxcore-log( 2945): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2945): 
I/jxcore-log( 2945): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2945): 
,I/jxcore-log( 2945): userPath [ 'www', 'www' ]
I/jxcore-log( 2945): 
,I/jxcore-log( 2945): Size 1080 1776
I/jxcore-log( 2945): 
,I/jxcore-log( 2945): Screen Brightness 82
I/jxcore-log( 2945): 
,E/jxcore-log( 2945): Dummy Error Log.
E/jxcore-log( 2945): 
,I/jxcore-log( 2945): getBuffer is called!!!!
I/jxcore-log( 2945): 
,D/Finsky  ( 1955): [170] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 1955): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{6a31038 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{1c32b54e u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  759): Killing 2284:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10036/pid_2284/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  759): Message: 2
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: false pid=2945, uid=10278
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2945): ****TEST TOOK:  5061  ms ****
I/jxcore-log( 2945): 
I/jxcore-log( 2945): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2945): 
,D/AndroidRuntime( 3057): 
D/AndroidRuntime( 3057): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3057): CheckJNI is OFF
,D/AndroidRuntime( 3057): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
,I/ActivityManager(  759): Killing 2945:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  759): WIN DEATH: Window{1cd8dcc4 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  759): Client connection lost with reason: 4
,W/PackageSettings(  759): Skipping PackageSetting{314979c6 com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  759): Force removing ActivityRecord{84b4a91 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  759): Spurious death for ProcessRecord{2eb55f65 2945:com.example.hello/u0a278}, curProc for 2945: null
,I/ActivityManager(  759): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1318): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1071): resetDictionaries() : en_US
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3082 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/art     (  759): Explicit concurrent mark sweep GC freed 9536(705KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.355ms total 81.371ms
I/Keyboard.Facilitator.DecoderInitializer( 1071): run()
,D/VoicemailCleanupService( 1366): Cleaning up data for package: com.example.hello
,I/art     (  759): WaitForGcToComplete blocked for 88.090ms for cause Explicit
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 2945 uid 10278
,I/Decoder ( 1071): createOrResetDecoder
,I/Keyboard.Facilitator( 1071): onFinishInput()
,I/MicrophoneInputStream( 1375): mic_starting gfk@2695acaf
,I/HotwordRecognitionRnr( 1375): Starting hotword detection.
,I/AudioFlinger(  183): AudioFlinger's thread 0xb4abd000 ready to run
,I/MicrophoneInputStream( 1375): mic_started gfk@2695acaf
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,D/TaskPersister(  759): removeObsoleteFile: deleting file=220_task.xml
,I/UpdateIcingCorporaServi( 1375): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/Launcher( 1256): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3aa8d052 new=com.google.android.velvet.VelvetApplication@3aa8d052
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1071): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1071): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1071): run()
I/StatsUtilsManager( 1071): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1071): shouldRecordStats() = Too Soon
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3122 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  759): Explicit concurrent mark sweep GC freed 4987(257KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.441ms total 150.934ms
,I/ActivityManager(  759): Killing 2324:com.google.android.keep/u0a71 (adj 15): empty #17
,I/HotwordWorker( 1375): onReady
,D/AndroidRuntime( 3057): Shutting down VM
,W/libprocessgroup(  759): failed to open /acct/uid_10071/pid_2324/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1375): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
,W/ContextImpl( 3122): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,W/ResourcesManager( 1256): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1585): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1585): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1585): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1585): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1585): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1585): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1585): Removing dialog suppression flag for package com.example.hello
E/NetworkScheduler.SchedulerReceiver( 1318): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1318): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1256): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1585): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1585): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1585): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1585): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1585): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1585): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1585): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3150 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1585): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1585): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1585): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1585): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1585): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1585): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 11.019ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.444ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 177us total 7.995ms
,W/BaseAppContext( 1585): Using Auth Proxy for data requests.
,I/ActivityManager(  759): Killing 2347:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2347/cgroup.procs: No such file or directory
,W/BaseAppContext( 1585): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1585): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1585): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1585): doRemovePackageData com.example.hello
,D/ConnectivityService(  759): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/OpenGLRenderer( 1256): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1256): Incorrectly called buildLayer on View: adg, destroying layer...
,E/SQLiteLog( 1585): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 1585): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 1585): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,W/DriveInitializer( 1585): Awaiting to be initialized
W/DriveInitializer( 1585): Background init thread started
,E/SQLiteLog( 1585): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,E/DocListDatabase( 1585): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1585): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1585): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1585): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1585): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1585): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1585): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1585): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1585): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1585): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1585): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 1585): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1585): Process: com.google.android.gms, PID: 1585
E/AndroidRuntime( 1585): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1585): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1585): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1585): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1585): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1585): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1585): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1585): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1585): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 1585): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1585): disk I/O error (code 3850)
E/DriveAsyncService( 1585): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1585): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1585): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1585): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1585): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1585): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1585): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1585): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1585): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1585): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1585): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1585): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1585): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1585): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1585): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1585): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  759): Can't write: system_app_crash
E/DropBoxManagerService(  759): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  759): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  759): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  759): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  759): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  759): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  759): 	... 5 more
,D/OpenGLRenderer(  759): Render dirty regions requested: true
,D/Atlas   (  759): Validating map...
,I/Adreno-EGL(  759): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  759): Initialized EGL, version 1.4
,D/OpenGLRenderer(  759): Enabling debug mode 0
,E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  170): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  170): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  170): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
,E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): Ctrl commit failed set overlay
E/qdhwcomposer(  170): configureLowRes: commit failed for low res panel
E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  170): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  170): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
,E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  170): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  170): Ctrl commit failed set overlay
E/qdhwcomposer(  170): configure: commit fails
E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl close error in unset

```
