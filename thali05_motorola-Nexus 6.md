#### Test 5038801932cd575_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd3: +CMAR
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd4: +CDIS
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd5: +CRSL
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd6: +CSS
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd7: $QCPWRDN
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): Registered AT Commands event handler
,D/AndroidRuntime( 3132): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3132): CheckJNI is OFF
D/AndroidRuntime( 3132): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{6bbcf15 token=Token{37d5a0cc ActivityRecord{39c75aff u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  821): Adding window Window{3dddd6f6 u0 Starting com.example.hello} at 3 of 8 (after Window{102e743b u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1494): Closing mic
I/MicrophoneInputStream( 1494): mic_close com.google.android.apps.gsa.speech.audio.u@2208e0c0
D/AndroidRuntime( 3132): Shutting down VM
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1494): Hotword detection finished
I/HotwordRecognitionRnr( 1494): Stopping hotword detection.
I/ActivityManager(  821): Start proc 3146:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
I/art     ( 1749): Explicit concurrent mark sweep GC freed 13252(764KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.277ms total 29.522ms
I/ActivityManager(  821): Killing 2681:com.google.android.deskclock/u0a44 (adj 15): empty #17
I/WebViewFactory( 3146): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659495699
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/LibraryLoader( 3146): Time to load native libraries: 3 ms (timestamps 1987-1990)
I/LibraryLoader( 3146): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3146): Binding Chromium to main looper Looper (main, tid 1) {1fc03f5b}
I/LibraryLoader( 3146): Expected native library version number "",actual native library version number ""
I/chromium( 3146): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3146): Initializing chromium process, singleProcess=true
W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3146): ApplicationContext is null in ApplicationStatus
W/chromium( 3146): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3146): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3146): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3146): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3146): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22ec44e8:true
D/BluetoothAdapter( 3146): 294012836: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3146): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3146): CordovaWebView is running on device made by: motorola
W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3146): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3146): Validating map...
V/WindowManager(  821): Adding window Window{f2eb818 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{3dddd6f6 u0 Starting com.example.hello})
W/chromium( 3146): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3146): Initialized EGL, version 1.4
D/OpenGLRenderer( 3146): Enabling debug mode 0
I/Keyboard.Facilitator( 1214): onFinishInput()
I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +684ms (total +29s754ms)
W/BindingManager( 3146): Cannot call determinedVisibility() - never saw a connection for the pid: 3146
I/chromium( 3146): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3146): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3146): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 3146): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576507264
,D/JX-Cordova( 3146): jxcore cordova android initializing
,W/jxcore-log( 3146): Initializing JXcore engine
W/jxcore-log( 3146): JXcore engine is ready
,W/jxcore-log( 3146): Starting JXcore engine
,W/m.example.hello( 3146): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9530]" dev="sockfs" ino=9530 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3146): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3146): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9732]" dev="sockfs" ino=9732 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3146): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19340]" dev="sockfs" ino=19340 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3146): Platform android
W/jxcore-log( 3146): 
,W/jxcore-log( 3146): Process ARCH arm
W/jxcore-log( 3146): 
,I/jxcore-log( 3146): JXcore Cordova bridge is ready!
I/jxcore-log( 3146): 
,W/jxcore-log( 3146): JXcore engine is started
,E/jxcore-log( 3146): >> motorola-Nexus 6
E/jxcore-log( 3146): 
,I/jxcore-log( 3146): Total memory 3113791488
I/jxcore-log( 3146): 
I/jxcore-log( 3146): Free memory 1015078912
I/jxcore-log( 3146): 
I/jxcore-log( 3146): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3146): 
,I/jxcore-log( 3146): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3146): 
,I/jxcore-log( 3146): userPath [ 'www' ]
I/jxcore-log( 3146): 
,I/jxcore-log( 3146): Size 1440 2392
I/jxcore-log( 3146): 
,I/jxcore-log( 3146): Screen Brightness 82
I/jxcore-log( 3146): 
,E/jxcore-log( 3146): Dummy Error Log.
E/jxcore-log( 3146): 
,I/jxcore-log( 3146): getBuffer is called!!!!
I/jxcore-log( 3146): 
,I/CheckinService( 1779): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{45b7ca7 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  821): Killing 2827:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  821): Message: 2
,D/WifiService(  821): setWifiEnabled: false pid=3146, uid=10272
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  821): New client listening to asynchronous messages
,I/jxcore-log( 3146): ****TEST TOOK:  5049  ms ****
I/jxcore-log( 3146): 
,I/jxcore-log( 3146): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3146): 
,D/AndroidRuntime( 3203): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3203): CheckJNI is OFF
,D/AndroidRuntime( 3203): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3146:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  821): Skipping PackageSetting{499ba06 com.test.thalitest/10265} due to missing metadata
,I/WindowState(  821): WIN DEATH: Window{f2eb818 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  821): Client connection lost with reason: 4
,W/ActivityManager(  821): Force removing ActivityRecord{39c75aff u0 com.example.hello/.MainActivity t24}: app died, no saved state
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,I/Keyboard.Facilitator( 1214): resetDictionaries() : en_US
,W/ActivityManager(  821): Spurious death for ProcessRecord{3313cc2e 3146:com.example.hello/u0a272}, curProc for 3146: null
D/TaskPersister(  821): removeObsoleteFile: deleting file=24_task.xml
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 2955): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1214): run()
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 37462(1552KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 1.366ms total 70.069ms
,I/Decoder ( 1214): createOrResetDecoder
,D/VoicemailCleanupService( 1381): Cleaning up data for package: com.example.hello
,I/ActivityManager(  821): Start proc 3221:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ConfigService( 1522): onCreate
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3146 uid 10272
,I/Keyboard.Facilitator( 1214): onFinishInput()
,I/art     (  821): Explicit concurrent mark sweep GC freed 14504(1026KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 32MB/48MB, paused 1.671ms total 123.369ms
I/art     (  821): WaitForGcToComplete blocked for 122.392ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): run()
,W/ContextImpl( 3221): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,W/LocationOracleImpl( 1494): Best location was null
,W/ErrorReporter( 1494): reportError [type: 29, code: 917507]: null
,E/NetworkScheduler.SchedulerReceiver( 1522): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1522): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/HotwordRecognitionRnr( 1494): Starting hotword detection.
,I/MicrophoneInputStream( 1494): mic_starting com.google.android.apps.gsa.speech.audio.u@31f54b17
I/AudioFlinger(  358): AudioFlinger's thread 0xb400a000 ready to run
I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1494): mic_started com.google.android.apps.gsa.speech.audio.u@31f54b17
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = history
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = user
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1779): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1779): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1779): Clearing selected account for com.example.hello
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1779): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1214): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1214): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1214): run()
,I/UpdateIcingCorporaServi( 1494): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/LocationSettingsChecker( 1779): Removing dialog suppression flag for package com.example.hello
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,I/StatsUtilsManager( 1214): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1214): shouldRecordStats() = Too Soon
,D/GOOGLEHELP_CompatibleDatabase( 1779): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1779): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1779): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1779): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/Launcher( 1305): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@28d020c2 new=com.google.android.velvet.VelvetApplication@28d020c2
,D/GOOGLEHELP_CompatibleDatabase( 1779): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1779): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1779): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ConfigFetchService( 1779): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/GOOGLEHELP_CompatibleDatabase( 1779): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1779): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1779): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1779): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1779): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1779): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/GCoreFlp( 1749): No location to return for getLastLocation()
I/ConfigFetchService( 1779): service connected
,I/PeopleContactsSync( 1779): CP2 sync disabled
,I/HotwordWorker( 1494): onReady
,W/BaseAppContext( 1779): Using Auth Proxy for data requests.
I/Icing   ( 1779): doRemovePackageData com.example.hello
,D/Launcher.Workspace( 1305): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1305): 11683562 - stripEmptyScreens()
,W/BaseAppContext( 1779): Using Auth Proxy for data requests.
,I/ActivityManager(  821): Start proc 3272:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,I/art     (  821): Explicit concurrent mark sweep GC freed 11898(602KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 1.716ms total 297.719ms
,I/UpdateIcingCorporaServi( 1494): UpdateCorporaTask done [took 193 ms] updated apps [took 193 ms] 
W/GCoreFlp( 1749): No location to return for getLastLocation()
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659495699
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/art     ( 3203): System.exit called, status: 0
I/AndroidRuntime( 3203): VM exiting with result code 0.
,W/DriveInitializer( 1779): Awaiting to be initialized
W/DriveInitializer( 1779): Background init thread started
,I/ActivityManager(  821): Start proc 3295:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  821): Killing 2662:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/ExternalStorage( 3295): After updating volumes, found 1 active roots
,W/OpenGLRenderer( 1305): Incorrectly called buildLayer on View: ew, destroying layer...
,W/DriveInitializer( 1779): Background init thread ended
E/SQLiteLog( 1779): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1779): disk I/O error (code 3850)
E/DriveAsyncService( 1779): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1779): 	at java.lang.Thread.run(Thread.java:818)
,I/art     ( 1522): Explicit concurrent mark sweep GC freed 9227(435KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 722us total 26.801ms
,E/SQLiteLog( 1522): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1522): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1522): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1522): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1522): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1522): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1522): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearcutLoggerIntentService( 1522): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1522): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1522): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1522): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1522): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1522): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1522): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 3022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3272): Update found 7 roots in 268ms
,D/Documents( 3272): Update found 7 roots in 109ms
,V/GLSActivity( 1522): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1522): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1522): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1522): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1522): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1522): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2705): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2705): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2705): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SharedPreferencesImpl( 2705): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,I/ActivityManager(  821): Killing 2864:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1779): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/Icing   ( 1779): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 1779): Could not init tag ds.tag.deleted
,I/Icing   ( 1779): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1779): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1779): Writing status failed
E/Icing   ( 1779): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/ConfigService( 1522): onDestroy
,E/SQLiteLog( 2201): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DatabaseUtils( 2201): Writing exception to parcel
E/DatabaseUtils( 2201): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 2201): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 2201): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DatabaseUtils( 2201): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 2201): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 2201): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 2201): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/DatabaseUtils( 2201): 	at com.android.providers.calendar.SQLiteContentProvider.update(SQLiteContentProvider.java:151)
E/DatabaseUtils( 2201): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/DatabaseUtils( 2201): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
E/DatabaseUtils( 2201): 	at android.os.Binder.execTransact(Binder.java:446)
,--------- beginning of crash
E/AndroidRuntime( 2350): FATAL EXCEPTION: IntentService[InitAlarmsService]
E/AndroidRuntime( 2350): Process: com.google.android.calendar, PID: 2350
E/AndroidRuntime( 2350): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2350): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2350): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 2350): 	at android.content.ContentProviderProxy.update(ContentProviderNative.java:568)
E/AndroidRuntime( 2350): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 2350): 	at com.android.calendar.alerts.InitAlarmsService.onHandleIntent(InitAlarmsService.java:54)
E/AndroidRuntime( 2350): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2350): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2350): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  821): Validating map...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,D/OpenGLRenderer(  821): Enabling debug mode 0
,E/kickstart(  877): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  877): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  877): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb2
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb1
E/ThermalEngine(  366): modem_clnt_error_cb: with -2 called for clnt 0x6
E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt FUSION
D/        (  358): csd_client_error_cb: error -2 cb_data 0xb544a060
D/        (  358): csd_client_error_cb: MDM reset
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  375): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  375): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb3
E/        (  358): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  358): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb4
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb5
I/HotwordDetector( 1494): Closing mic
I/MicrophoneInputStream( 1494): mic_close com.google.android.apps.gsa.speech.audio.u@31f54b17
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb7
,I/ThermalEngine(  366): qmi: Instance id 157 for fusion TS
,E/QMI_FW  (  821): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659495699
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  821): Killing 2201:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1494): Stopping hotword detection.
I/HotwordRecognitionRnr( 1494): Hotword detection finished
,E/        (  358): csd_service_deinit: notifier handle release rc:0
,D/        (  358): csd_service_init: qmi_client_notifier_init() successful
,V/ImsSenderRxr( 1276): Read packet: 15 bytes
,V/ImsSenderRxr( 1276): processResponse
D/ImsSenderRxr( 1276): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
D/ImsSenderRxr( 1276):  Tag -1 3 213 0
,I/str_params(  358): key: 'all_call_states' value: ''
,E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt MODEM
,I/str_params(  358): key: 'all_call_states' value: ''
,I/str_params(  358): key: 'all_call_states' value: ''
,E/QMI_FW  (  373): QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
,E/QMI_FW  (  373): QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1

```
