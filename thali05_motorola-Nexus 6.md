#### Test 50388019809f971_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  822): Waited long enough for: ServiceRecord{369cd752 u0 org.simalliance.openmobileapi.service/.SmartcardService}
--------- beginning of main
I/ConfigService( 1539): onDestroy
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{2765b902 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
D/AndroidRuntime( 3152): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3152): CheckJNI is OFF
D/AndroidRuntime( 3152): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{d73e6e6 token=Token{205ce141 ActivityRecord{39dc3028 u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3152): Shutting down VM
I/HotwordDetector( 1500): Closing mic
I/MicrophoneInputStream( 1500): mic_close com.google.android.apps.gsa.speech.audio.u@3cb06d78
V/WindowManager(  822): Adding window Window{33df4bc3 u0 Starting com.example.hello} at 3 of 8 (after Window{17dabb5e u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  822): Start proc 3167:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
D/audio_hw_primary(  360): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  360): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  360): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1500): Hotword detection finished
I/HotwordRecognitionRnr( 1500): Stopping hotword detection.
I/ActivityManager(  822): Killing 2535:com.google.android.youtube/u0a86 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658766611
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3167): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3167): Time to load native libraries: 1 ms (timestamps 97-98)
I/LibraryLoader( 3167): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3167): Binding Chromium to main looper Looper (main, tid 1) {1e3ee775}
I/LibraryLoader( 3167): Expected native library version number "",actual native library version number ""
I/chromium( 3167): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3167): Initializing chromium process, singleProcess=true
W/art     ( 3167): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3167): ApplicationContext is null in ApplicationStatus
W/chromium( 3167): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3167): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3167): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3167): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3167): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/Atfwd_Daemon(  377): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  377): ATFWD --> QMI Port : rmnet_usb0
I/ActivityManager(  822): Waited long enough for: ServiceRecord{5d3e8f1 u0 com.qualcomm.atfwd/.AtFwdService}
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec052ed:true
D/BluetoothAdapter( 3167): 629342295: getState() :  mService = null. Returning STATE_OFF
I/Atfwd_Daemon(  377): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  377): Trying to register 8 commands:
I/Atfwd_Daemon(  377): cmd0: +CKPD
I/art     (  822): Explicit concurrent mark sweep GC freed 20009(1015KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 2.128ms total 77.179ms
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): cmd1: +CTSA
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): cmd2: +CFUN
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): cmd3: +CMAR
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): cmd4: +CDIS
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): cmd5: +CRSL
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): cmd6: +CSS
W/art     ( 3167): Attempt to remove local handle scope entry from IRT, ignoring
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): cmd7: $QCPWRDN
W/AwContents( 3167): onDetachedFromWindow called when already detached. Ignoring
I/Atfwd_Daemon(  377): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  377): Registered AT Commands event handler
D/SystemWebViewEngine( 3167): CordovaWebView is running on device made by: motorola
W/art     ( 3167): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3167): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3167): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3167): Validating map...
V/WindowManager(  822): Adding window Window{1468d15d u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{33df4bc3 u0 Starting com.example.hello})
W/chromium( 3167): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3167): Initialized EGL, version 1.4
D/OpenGLRenderer( 3167): Enabling debug mode 0
I/ActivityManager(  822): Displayed com.example.hello/.MainActivity: +773ms (total +27s248ms)
I/Keyboard.Facilitator( 1211): onFinishInput()
W/BindingManager( 3167): Cannot call determinedVisibility() - never saw a connection for the pid: 3167
I/chromium( 3167): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3167): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3167): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 3167): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576439552
D/JX-Cordova( 3167): jxcore cordova android initializing
,W/jxcore-log( 3167): Initializing JXcore engine
,W/jxcore-log( 3167): JXcore engine is ready
,W/jxcore-log( 3167): Starting JXcore engine
,I/ActivityManager(  822): Killing 2711:com.google.android.deskclock/u0a44 (adj 15): empty #17
,W/m.example.hello( 3167): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12548]" dev="sockfs" ino=12548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3167): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3167): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11245]" dev="sockfs" ino=11245 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3167): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21759]" dev="sockfs" ino=21759 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3167): Platform android
W/jxcore-log( 3167): 
W/jxcore-log( 3167): Process ARCH arm
W/jxcore-log( 3167): 
,I/jxcore-log( 3167): JXcore Cordova bridge is ready!
I/jxcore-log( 3167): 
,W/jxcore-log( 3167): JXcore engine is started
,E/jxcore-log( 3167): >> motorola-Nexus 6
E/jxcore-log( 3167): 
I/jxcore-log( 3167): Total memory 3113791488
I/jxcore-log( 3167): 
,I/jxcore-log( 3167): Free memory 1009475584
I/jxcore-log( 3167): 
I/jxcore-log( 3167): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3167): 
I/jxcore-log( 3167): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3167): 
,I/jxcore-log( 3167): userPath [ 'www' ]
I/jxcore-log( 3167): 
,I/jxcore-log( 3167): Size 1440 2392
I/jxcore-log( 3167): 
,I/jxcore-log( 3167): Screen Brightness 82
I/jxcore-log( 3167): 
E/jxcore-log( 3167): Dummy Error Log.
E/jxcore-log( 3167): 
,I/jxcore-log( 3167): getBuffer is called!!!!
I/jxcore-log( 3167): 
,I/CheckinService( 1781): Done disabling old GoogleServicesFramework version
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  822): Message: 2
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: false pid=3167, uid=10272
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3167): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 3167): 
,I/jxcore-log( 3167): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3167): 
,D/AndroidRuntime( 3224): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3224): CheckJNI is OFF
,D/AndroidRuntime( 3224): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
,I/ActivityManager(  822): Killing 3167:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  822): Skipping PackageSetting{153033e8 com.test.thalitest/10265} due to missing metadata
,D/WifiService(  822): Client connection lost with reason: 4
,I/WindowState(  822): WIN DEATH: Window{1468d15d u0 com.example.hello/com.example.hello.MainActivity}
,W/ActivityManager(  822): Force removing ActivityRecord{39dc3028 u0 com.example.hello/.MainActivity t24}: app died, no saved state
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=0: pkg removed
,D/TaskPersister(  822): removeObsoleteFile: deleting file=24_task.xml
,I/Keyboard.Facilitator( 1211): resetDictionaries() : en_US
,D/BuaReceiver( 2951): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,W/ActivityManager(  822): Spurious death for ProcessRecord{2fea81b 3167:com.example.hello/u0a272}, curProc for 3167: null
,I/Keyboard.Facilitator.DecoderInitializer( 1211): run()
,I/art     ( 1062): Explicit concurrent mark sweep GC freed 37351(1548KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 809us total 52.664ms
,D/VoicemailCleanupService( 1365): Cleaning up data for package: com.example.hello
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3167 uid 10272
,I/Decoder ( 1211): createOrResetDecoder
,I/Keyboard.Facilitator( 1211): onFinishInput()
,I/art     (  822): Explicit concurrent mark sweep GC freed 10427(827KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 32MB/48MB, paused 1.056ms total 95.681ms
,I/art     (  822): WaitForGcToComplete blocked for 91.534ms for cause Explicit
,I/ActivityManager(  822): Start proc 3242:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ConfigService( 1539): onCreate
,W/LocationOracleImpl( 1500): Best location was null
,W/ErrorReporter( 1500): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1500): Starting hotword detection.
,I/MicrophoneInputStream( 1500): mic_starting com.google.android.apps.gsa.speech.audio.u@3990fe99
I/AudioFlinger(  360): AudioFlinger's thread 0xb4d54000 ready to run
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1211): run()
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/SoundTriggerHwService::Module(  360): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1500): mic_started com.google.android.apps.gsa.speech.audio.u@3990fe99
W/ContextImpl( 3242): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
D/audio_hw_primary(  360): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  360): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  360): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  360): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  360): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1211): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = contacts
W/GCoreFlp( 1752): No location to return for getLastLocation()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = history
E/NetworkScheduler.SchedulerReceiver( 1539): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1539): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1211): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1211): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1211): run()
I/StatsUtilsManager( 1211): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1211): shouldRecordStats() = Too Soon
,I/art     (  822): Explicit concurrent mark sweep GC freed 5615(302KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 2.121ms total 140.626ms
,D/PackageBroadcastService( 1781): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1781): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,I/LocationSettingsChecker( 1781): Removing dialog suppression flag for package com.example.hello
,W/Launcher( 1293): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d2bd744 new=com.google.android.velvet.VelvetApplication@3d2bd744
,D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1781): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/UpdateIcingCorporaServi( 1500): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/HotwordWorker( 1500): onReady
,D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ConfigFetchService( 1781): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1781): service connected
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1781): CP2 sync disabled
,I/Icing   ( 1781): doRemovePackageData com.example.hello
,I/art     ( 3224): System.exit called, status: 0
I/AndroidRuntime( 3224): VM exiting with result code 0.
,I/ActivityManager(  822): Start proc 3291:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,I/UpdateIcingCorporaServi( 1500): UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658766611
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/DriveInitializer( 1781): Awaiting to be initialized
,W/DriveInitializer( 1781): Background init thread started
,I/ActivityManager(  822): Start proc 3312:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  822): Killing 2834:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/Launcher.Workspace( 1293): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1293): 11683562 - stripEmptyScreens()
,E/SQLiteLog( 1293): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/art     (  371): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.165ms total 12.062ms
,I/art     (  371): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 9.793ms
,I/art     (  371): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.456ms
,I/ActivityManager(  822): Killing 2692:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,W/OpenGLRenderer( 1293): Incorrectly called buildLayer on View: ew, destroying layer...
,E/SQLiteLog( 1781): (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,E/DocListDatabase( 1781): Failed to delete from FileContent112
E/DocListDatabase( 1781): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1781): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1781): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1781): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1781): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/DocListDatabase( 1781): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/DocListDatabase( 1781): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/DocListDatabase( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1781): 	at java.lang.Thread.run(Thread.java:818)
,--------- beginning of crash
E/AndroidRuntime( 1781): FATAL EXCEPTION: pool-13-thread-1
E/AndroidRuntime( 1781): Process: com.google.android.gms, PID: 1781
E/AndroidRuntime( 1781): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1781): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1781): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/AndroidRuntime( 1781): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/AndroidRuntime( 1781): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/AndroidRuntime( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1781): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  822): Validating map...
,D/ExternalStorage( 3312): After updating volumes, found 1 active roots
,I/art     ( 1539): Explicit concurrent mark sweep GC freed 15993(730KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.379ms total 40.867ms
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/DriveInitializer( 1781): Background init thread ended
,E/SQLiteLog( 1781): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1781): disk I/O error (code 3850)
E/DriveAsyncService( 1781): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1781): 	at java.lang.Thread.run(Thread.java:818)
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
,W/ResourcesManager( 3031): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3031): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3291): Update found 7 roots in 458ms
,I/HotwordDetector( 1500): Closing mic
,I/MicrophoneInputStream( 1500): mic_close com.google.android.apps.gsa.speech.audio.u@3990fe99
,D/Documents( 3291): Update found 7 roots in 222ms
,I/ActivityManager(  822): Killing 2866:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/audio_hw_primary(  360): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  360): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  360): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1500): Hotword detection finished
,I/HotwordRecognitionRnr( 1500): Stopping hotword detection.
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{1b07ac4 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1781): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/Icing   ( 1781): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1781): Could not init tag ds.tag.deleted
,I/ActivityManager(  822): Killing 2968:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/Icing   ( 1781): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1781): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1781): Writing status failed
,E/Icing   ( 1781): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/ConfigService( 1539): onDestroy
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1658766611
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  878): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  878): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  878): ERROR: function: main:268 Uploading  Image using Sahara protocol failed,
I/kickstart(  878): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  368): qmi_clnt_error_cb: with error -2 called for clnt FUSION,
E/ThermalEngine(  368): modem_clnt_error_cb: with -2 called for clnt 0x8,
D/        (  360): csd_client_error_cb: error -2 cb_data 0xb601e060
D/        (  360): csd_client_error_cb: MDM reset
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb1
,E/        (  360): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  360): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  377): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  377): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
,I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb2
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb4
,I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb5,
,I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb7
,I/ThermalEngine(  368): qmi: Instance id 157 for fusion TS
,E/        (  360): csd_service_deinit: notifier handle release rc:0
,D/        (  360): csd_service_init: qmi_client_notifier_init() successful
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
