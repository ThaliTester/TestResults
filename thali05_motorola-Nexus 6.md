#### Test 503880196b4ec73_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
W/ProcessCpuTracker(  820): Skipping unknown process pid 3191
I/ActivityManager(  820): Waited long enough for: ServiceRecord{1794040e u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,--------- beginning of main
I/ConfigService( 1438): onDestroy
I/Atfwd_Daemon(  374): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  374): ATFWD --> QMI Port : rmnet_usb0
I/Atfwd_Daemon(  374): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  374): Trying to register 8 commands:
I/Atfwd_Daemon(  374): cmd0: +CKPD
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd1: +CTSA
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd2: +CFUN
D/AndroidRuntime( 3197): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3197): CheckJNI is OFF
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd3: +CMAR
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd4: +CDIS
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd5: +CRSL
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd6: +CSS
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd7: $QCPWRDN
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): Registered AT Commands event handler
I/ActivityManager(  820): Waited long enough for: ServiceRecord{64572ed u0 com.qualcomm.atfwd/.AtFwdService}
D/AndroidRuntime( 3197): Calling main entry com.android.commands.am.Am
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{2114e9e2 token=Token{1cbc62ad ActivityRecord{266463c4 u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3197): Shutting down VM
V/WindowManager(  820): Adding window Window{1e8fe1cf u0 Starting com.example.hello} at 3 of 8 (after Window{251ee0f6 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1530): Closing mic
I/MicrophoneInputStream( 1530): mic_close com.google.android.apps.gsa.speech.audio.u@21a8a05a
I/ActivityManager(  820): Start proc 3213:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1530): Stopping hotword detection.
I/HotwordRecognitionRnr( 1530): Hotword detection finished
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659188499
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     (  820): Explicit concurrent mark sweep GC freed 19475(1005KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.177ms total 43.635ms
,I/WebViewFactory( 3213): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3213): Time to load native libraries: 1 ms (timestamps 643-644)
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3213): Binding Chromium to main looper Looper (main, tid 1) {2c034e96}
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
I/chromium( 3213): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3213): Initializing chromium process, singleProcess=true
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3213): ApplicationContext is null in ApplicationStatus
W/chromium( 3213): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3213): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3213): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@139312de:true
D/BluetoothAdapter( 3213): 71732713: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3213): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3213): CordovaWebView is running on device made by: motorola
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3213): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3213): Validating map...
V/WindowManager(  820): Adding window Window{3b97ef8e u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{1e8fe1cf u0 Starting com.example.hello})
W/chromium( 3213): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3213): Initialized EGL, version 1.4
D/OpenGLRenderer( 3213): Enabling debug mode 0
I/ActivityManager(  820): Displayed com.example.hello/.MainActivity: +583ms (total +27s780ms)
I/Keyboard.Facilitator( 1230): onFinishInput()
W/BindingManager( 3213): Cannot call determinedVisibility() - never saw a connection for the pid: 3213
I/chromium( 3213): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3213): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3213): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 3213): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576519296
D/JX-Cordova( 3213): jxcore cordova android initializing
,W/jxcore-log( 3213): Initializing JXcore engine
W/jxcore-log( 3213): JXcore engine is ready
,W/jxcore-log( 3213): Starting JXcore engine
,W/m.example.hello( 3213): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10508]" dev="sockfs" ino=10508 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3213): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4601 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 3213): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10676]" dev="sockfs" ino=10676 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3213): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19088]" dev="sockfs" ino=19088 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3213): Platform android
W/jxcore-log( 3213): 
W/jxcore-log( 3213): Process ARCH arm
W/jxcore-log( 3213): 
,I/jxcore-log( 3213): JXcore Cordova bridge is ready!
I/jxcore-log( 3213): 
,W/jxcore-log( 3213): JXcore engine is started
,E/jxcore-log( 3213): >> motorola-Nexus 6
E/jxcore-log( 3213): 
,I/jxcore-log( 3213): Total memory 3113791488
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Free memory 1026727936
I/jxcore-log( 3213): 
I/jxcore-log( 3213): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3213): 
I/jxcore-log( 3213): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3213): 
I/jxcore-log( 3213): userPath [ 'www' ]
I/jxcore-log( 3213): 
I/jxcore-log( 3213): Size 1440 2392
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Screen Brightness 82
I/jxcore-log( 3213): 
E/jxcore-log( 3213): Dummy Error Log.
E/jxcore-log( 3213): 
,I/jxcore-log( 3213): getBuffer is called!!!!
I/jxcore-log( 3213): 
,I/ActivityManager(  820): Killing 2748:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/CheckinService( 1780): Done disabling old GoogleServicesFramework version
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  820): Message: 2
,D/WifiService(  820): New client listening to asynchronous messages
D/WifiService(  820): setWifiEnabled: false pid=3213, uid=10272
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3213): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3213): 
,D/AndroidRuntime( 3273): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3273): CheckJNI is OFF
,D/AndroidRuntime( 3273): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3213:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  820): Skipping PackageSetting{386594fd com.test.thalitest/10265} due to missing metadata
,I/WindowState(  820): WIN DEATH: Window{3b97ef8e u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  820): Client connection lost with reason: 4
,W/ActivityManager(  820): Force removing ActivityRecord{266463c4 u0 com.example.hello/.MainActivity t24}: app died, no saved state
,I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  820): Spurious death for ProcessRecord{1fc729a7 3213:com.example.hello/u0a272}, curProc for 3213: null
,I/Keyboard.Facilitator( 1230): resetDictionaries() : en_US
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,D/TaskPersister(  820): removeObsoleteFile: deleting file=24_task.xml
I/Keyboard.Facilitator.DecoderInitializer( 1230): run()
I/Decoder ( 1230): createOrResetDecoder
,D/BuaReceiver( 3000): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 37312(1546KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 2.348ms total 76.154ms
,W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3213 uid 10272
,I/Keyboard.Facilitator( 1230): onFinishInput()
,I/ConfigService( 1438): onCreate
,D/VoicemailCleanupService( 1403): Cleaning up data for package: com.example.hello
,I/ActivityManager(  820): Start proc 3292:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/art     (  820): Explicit concurrent mark sweep GC freed 12095(910KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 32MB/48MB, paused 1.276ms total 123.072ms
,I/art     (  820): WaitForGcToComplete blocked for 121.856ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1230): run()
,W/LocationOracleImpl( 1530): Best location was null
,W/ErrorReporter( 1530): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1530): Starting hotword detection.
I/MicrophoneInputStream( 1530): mic_starting com.google.android.apps.gsa.speech.audio.u@236abb85
,I/AudioFlinger(  357): AudioFlinger's thread 0xb4068000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1530): mic_started com.google.android.apps.gsa.speech.audio.u@236abb85
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1230): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/ContextImpl( 3292): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = contacts
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1230): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1230): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1230): run()
I/StatsUtilsManager( 1230): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1230): shouldRecordStats() = Too Soon
,E/NetworkScheduler.SchedulerReceiver( 1438): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1438): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,W/GCoreFlp( 1752): No location to return for getLastLocation()
D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/PackageBroadcastService( 1780): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1780): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1780): Removing dialog suppression flag for package com.example.hello
,I/art     (  820): Explicit concurrent mark sweep GC freed 6126(319KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 3.095ms total 140.900ms
,I/UpdateIcingCorporaServi( 1530): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/GOOGLEHELP_CompatibleDatabase( 1780): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1780): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1780): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1780): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/HotwordWorker( 1530): onReady
,W/Launcher( 1332): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4468de9 new=com.google.android.velvet.VelvetApplication@4468de9
,D/GOOGLEHELP_CompatibleDatabase( 1780): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1780): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1780): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,D/GOOGLEHELP_CompatibleDatabase( 1780): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1780): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,I/ConfigFetchService( 1780): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GOOGLEHELP_CompatibleDatabase( 1780): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1780): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1780): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1780): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ConfigFetchService( 1780): service connected
I/art     ( 3273): System.exit called, status: 0
I/AndroidRuntime( 3273): VM exiting with result code 0.
,I/PeopleContactsSync( 1780): CP2 sync disabled
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659188499
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/Icing   ( 1780): doRemovePackageData com.example.hello
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1530): UpdateCorporaTask done [took 115 ms] updated apps [took 114 ms] 
,I/ActivityManager(  820): Start proc 3341:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 261us total 13.405ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 12.081ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 9.630ms
,D/Launcher.Workspace( 1332): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1332): 11683562 - stripEmptyScreens()
,W/DriveInitializer( 1780): Awaiting to be initialized
E/SQLiteDatabase( 3341): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3341): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3341): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3341): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3341): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3341): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3341): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3341): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 3341): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3341): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3341): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 3341): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 3341): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 3341): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3341): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3341): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 3341): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3341): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3341): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 3341): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/DriveInitializer( 1780): Background init thread started
,I/ActivityManager(  820): Killing 2810:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/SQLiteLog( 1780): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
D/AndroidRuntime( 3341): Shutting down VM
E/DocListDatabase( 1780): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1780): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1780): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1780): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1780): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1780): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1780): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1780): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1780): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1780): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,--------- beginning of crash
E/AndroidRuntime( 3341): FATAL EXCEPTION: main
E/AndroidRuntime( 3341): Process: com.android.documentsui, PID: 3341
E/AndroidRuntime( 3341): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3341): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 3341): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 3341): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 3341): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3341): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3341): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 3341): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3341): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3341): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 3341): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 3341): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3341): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 3341): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3341): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3341): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3341): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3341): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 3341): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3341): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3341): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 3341): 	... 9 more
E/SQLiteLog( 1780): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1780): disk I/O error (code 3850)
E/DriveAsyncService( 1780): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1780): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1780): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1780): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1780): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1780): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1780): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1780): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1780): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1780): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1780): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1780): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1780): 	at java.lang.Thread.run(Thread.java:818)
W/DriveInitializer( 1780): Background init thread ended
E/AndroidRuntime( 1780): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1780): Process: com.google.android.gms, PID: 1780
E/AndroidRuntime( 1780): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1780): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1780): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1780): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1780): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1780): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1780): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1780): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 1780): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,W/OpenGLRenderer( 1332): Incorrectly called buildLayer on View: ew, destroying layer...
,I/ActivityManager(  820): Start proc 3362:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,W/ResourcesManager(  820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
,I/ActivityManager(  820): Killing 2864:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/ExternalStorage( 3362): After updating volumes, found 1 active roots
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  820): Initialized EGL, version 1.4
,D/OpenGLRenderer(  820): Enabling debug mode 0
,W/ResourcesManager( 3083): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3083): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3341): Update found 7 roots in 354ms
,I/HotwordDetector( 1530): Closing mic
,I/MicrophoneInputStream( 1530): mic_close com.google.android.apps.gsa.speech.audio.u@236abb85
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/ActivityManager(  820): Killing 2727:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1530): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1530): Hotword detection finished
,E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1780): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/Icing   ( 1780): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1780): Could not init tag ds.tag.deleted
,I/Icing   ( 1780): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{27cf629e u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  820): Killing 2896:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/ConfigService( 1438): onDestroy
,E/QMI_FW  (  820): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659188499
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  870): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  870): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  870): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,D/        (  357): csd_client_error_cb: error -2 cb_data 0xb601a060,
,E/ThermalEngine(  365): qmi_clnt_error_cb: with error -2 called for clnt FUSION,
D/        (  357): csd_client_error_cb: MDM reset,
E/ThermalEngine(  365): modem_clnt_error_cb: with -2 called for clnt 0x6,
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb0,
I/Atfwd_Daemon(  374): Modem Out Of Service --> Release ATCOP service client handles, if any,
I/Atfwd_Daemon(  374): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb5
,E/        (  357): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
,E/        (  357): csd_service_deinit: Error -1 deiniting CSD,
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb2,
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb3
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb6,
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb4
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb1
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb7
I/ThermalEngine(  365): qmi: Instance id 157 for fusion TS
,E/        (  357): csd_service_deinit: notifier handle release rc:0
,D/        (  357): csd_service_init: qmi_client_notifier_init() successful
,I/qdhwcomposer(  261): handle_blank_event: dpy:0 panel power state: 0

```
