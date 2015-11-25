#### Test 503880196dc97cd_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/ConfigService( 1486): onDestroy
--------- beginning of system
I/ActivityManager(  820): Waited long enough for: ServiceRecord{25001a5a u0 org.simalliance.openmobileapi.service/.SmartcardService}
I/ActivityManager(  820): Waited long enough for: ServiceRecord{2c951e75 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,D/AndroidRuntime( 3151): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3151): CheckJNI is OFF
I/ActivityManager(  820): Waited long enough for: ServiceRecord{17b5dbe0 u0 com.qualcomm.atfwd/.AtFwdService}
D/AndroidRuntime( 3151): Calling main entry com.android.commands.am.Am
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{272cb40f token=Token{b3b756e ActivityRecord{2036f4e9 u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3151): Shutting down VM
V/WindowManager(  820): Adding window Window{3864b688 u0 Starting com.example.hello} at 3 of 8 (after Window{1124fb1a u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1523): Closing mic
I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@1e22908e
I/ActivityManager(  820): Start proc 3165:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
I/Atfwd_Daemon(  374): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  374): ATFWD --> QMI Port : rmnet_usb0
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1523): Hotword detection finished
I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
I/Atfwd_Daemon(  374): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  374): Trying to register 8 commands:
I/Atfwd_Daemon(  374): cmd0: +CKPD
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659098387
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd1: +CTSA
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd2: +CFUN
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd3: +CMAR
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd4: +CDIS
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd5: +CRSL
I/WebViewFactory( 3165): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd6: +CSS
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd7: $QCPWRDN
I/LibraryLoader( 3165): Time to load native libraries: 4 ms (timestamps 397-401)
I/LibraryLoader( 3165): Expected native library version number "",actual native library version number ""
I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): Registered AT Commands event handler
,I/art     (  820): Explicit concurrent mark sweep GC freed 19280(978KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.753ms total 96.260ms
V/WebViewChromiumFactoryProvider( 3165): Binding Chromium to main looper Looper (main, tid 1) {25ec1161}
I/LibraryLoader( 3165): Expected native library version number "",actual native library version number ""
I/chromium( 3165): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  820): Killing 2566:com.google.android.youtube/u0a86 (adj 15): empty #17
I/BrowserStartupController( 3165): Initializing chromium process, singleProcess=true
W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3165): ApplicationContext is null in ApplicationStatus
W/chromium( 3165): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3165): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3165): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3165): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3165): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32a8beff:true
D/BluetoothAdapter( 3165): 234316445: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3165): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3165): CordovaWebView is running on device made by: motorola
W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3165): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3165): Validating map...
V/WindowManager(  820): Adding window Window{2193bdda u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{3864b688 u0 Starting com.example.hello})
W/chromium( 3165): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3165): Initialized EGL, version 1.4
D/OpenGLRenderer( 3165): Enabling debug mode 0
I/Keyboard.Facilitator( 1212): onFinishInput()
I/ActivityManager(  820): Displayed com.example.hello/.MainActivity: +572ms (total +27s917ms)
W/BindingManager( 3165): Cannot call determinedVisibility() - never saw a connection for the pid: 3165
I/chromium( 3165): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3165): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3165): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  820): Killing 2716:com.google.android.deskclock/u0a44 (adj 15): empty #17
D/jxcore_app_log( 3165): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576512640
D/JX-Cordova( 3165): jxcore cordova android initializing
,W/jxcore-log( 3165): Initializing JXcore engine
W/jxcore-log( 3165): JXcore engine is ready
,W/jxcore-log( 3165): Starting JXcore engine
,W/m.example.hello( 3165): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12948]" dev="sockfs" ino=12948 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3165): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 3165): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9895]" dev="sockfs" ino=9895 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3165): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20132]" dev="sockfs" ino=20132 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3165): Platform android
W/jxcore-log( 3165): 
W/jxcore-log( 3165): Process ARCH arm
W/jxcore-log( 3165): 
,I/jxcore-log( 3165): JXcore Cordova bridge is ready!
I/jxcore-log( 3165): 
W/jxcore-log( 3165): JXcore engine is started
,E/jxcore-log( 3165): >> motorola-Nexus 6
E/jxcore-log( 3165): 
,I/jxcore-log( 3165): Total memory 3113791488
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Free memory 1014538240
I/jxcore-log( 3165): 
I/jxcore-log( 3165): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3165): 
I/jxcore-log( 3165): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3165): 
I/jxcore-log( 3165): userPath [ 'www' ]
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Size 1440 2392
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Screen Brightness 82
I/jxcore-log( 3165): 
,E/jxcore-log( 3165): Dummy Error Log.
E/jxcore-log( 3165): 
,I/jxcore-log( 3165): getBuffer is called!!!!
I/jxcore-log( 3165): 
,I/CheckinService( 1777): Done disabling old GoogleServicesFramework version
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  820): Message: 2
,D/WifiService(  820): New client listening to asynchronous messages,
D/WifiService(  820): setWifiEnabled: false pid=3165, uid=10272
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3165): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3165): 
,D/AndroidRuntime( 3223): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3223): CheckJNI is OFF
,D/AndroidRuntime( 3223): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3165:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  820): Skipping PackageSetting{3cdef0c4 com.test.thalitest/10265} due to missing metadata
,I/WindowState(  820): WIN DEATH: Window{2193bdda u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  820): Client connection lost with reason: 4
,W/ActivityManager(  820): Force removing ActivityRecord{2036f4e9 u0 com.example.hello/.MainActivity t24}: app died, no saved state
,W/ActivityManager(  820): Spurious death for ProcessRecord{38df1783 3165:com.example.hello/u0a272}, curProc for 3165: null
I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=0: pkg removed
,D/TaskPersister(  820): removeObsoleteFile: deleting file=24_task.xml
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1212): resetDictionaries() : en_US
,D/BuaReceiver( 2953): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1212): run()
,I/Decoder ( 1212): createOrResetDecoder
,W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3165 uid 10272
,I/Keyboard.Facilitator( 1212): onFinishInput()
,D/VoicemailCleanupService( 1394): Cleaning up data for package: com.example.hello
,I/art     ( 1065): Explicit concurrent mark sweep GC freed 37006(1534KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 3.324ms total 64.292ms
,I/ActivityManager(  820): Start proc 3241:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/art     (  820): Explicit concurrent mark sweep GC freed 11470(887KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 32MB/48MB, paused 1.127ms total 102.444ms
I/art     (  820): WaitForGcToComplete blocked for 93.334ms for cause Explicit
,I/ConfigService( 1486): onCreate
,W/LocationOracleImpl( 1523): Best location was null
W/ErrorReporter( 1523): reportError [type: 29, code: 917507]: null
,W/ContextImpl( 3241): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/HotwordRecognitionRnr( 1523): Starting hotword detection.
I/MicrophoneInputStream( 1523): mic_starting com.google.android.apps.gsa.speech.audio.u@12abcfc2
I/AudioFlinger(  356): AudioFlinger's thread 0xb4cd4000 ready to run
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1523): mic_started com.google.android.apps.gsa.speech.audio.u@12abcfc2
I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): run()
E/NetworkScheduler.SchedulerReceiver( 1486): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1486): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
,D/PackageBroadcastService( 1777): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1777): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
,D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,I/UpdateIcingCorporaServi( 1523): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
W/Launcher( 1310): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1a012ce0 new=com.google.android.velvet.VelvetApplication@1a012ce0
,I/LocationSettingsChecker( 1777): Removing dialog suppression flag for package com.example.hello
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1212): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1212): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1212): run()
I/StatsUtilsManager( 1212): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1212): shouldRecordStats() = Too Soon
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,D/GOOGLEHELP_CompatibleDatabase( 1777): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1777): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1777): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1777): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/HotwordWorker( 1523): onReady
,I/ConfigFetchService( 1777): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GOOGLEHELP_CompatibleDatabase( 1777): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1777): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1777): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ConfigFetchService( 1777): service connected
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1777): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1777): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1777): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1777): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1777): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1777): CP2 sync disabled
D/GOOGLEHELP_CompatibleDatabase( 1777): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,I/Icing   ( 1777): doRemovePackageData com.example.hello
,I/UpdateIcingCorporaServi( 1523): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,I/art     (  820): Explicit concurrent mark sweep GC freed 10465(527KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 1.513ms total 243.827ms
,I/ActivityManager(  820): Start proc 3289:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,I/art     ( 3223): System.exit called, status: 0
I/AndroidRuntime( 3223): VM exiting with result code 0.
,D/Launcher.Workspace( 1310): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1310): 11683562 - stripEmptyScreens()
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659098387
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/DriveInitializer( 1777): Awaiting to be initialized
,W/DriveInitializer( 1777): Background init thread started
,I/ActivityManager(  820): Start proc 3311:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  820): Killing 2832:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/art     (  367): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 14.362ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 9.841ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 220us total 9.936ms
,I/ActivityManager(  820): Killing 2691:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,W/OpenGLRenderer( 1310): Incorrectly called buildLayer on View: ew, destroying layer...
,E/SQLiteLog( 1777): (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 1777): Failed to delete from FileContent112
E/DocListDatabase( 1777): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1777): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1777): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1777): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1777): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1777): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1777): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1777): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/DocListDatabase( 1777): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/DocListDatabase( 1777): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/DocListDatabase( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1777): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 1777): FATAL EXCEPTION: pool-13-thread-1
E/AndroidRuntime( 1777): Process: com.google.android.gms, PID: 1777
E/AndroidRuntime( 1777): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1777): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1777): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/AndroidRuntime( 1777): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/AndroidRuntime( 1777): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/AndroidRuntime( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1777): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager(  820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
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
,D/ExternalStorage( 3311): After updating volumes, found 1 active roots
,D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  820): Validating map...
,I/art     ( 1486): Explicit concurrent mark sweep GC freed 15907(727KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 854us total 33.598ms
,E/SQLiteLog( 1777): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1777): disk I/O error (code 3850)
E/DriveAsyncService( 1777): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1777): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1777): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1777): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1777): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1777): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1777): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1777): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1777): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1777): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1777): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1777): 	at java.lang.Thread.run(Thread.java:818)
,W/DriveInitializer( 1777): Background init thread ended
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  820): Initialized EGL, version 1.4
W/ResourcesManager( 3035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/OpenGLRenderer(  820): Enabling debug mode 0
,D/Documents( 3289): Update found 7 roots in 369ms
,D/Documents( 3289): Update found 7 roots in 113ms
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{376f41ea u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@12abcfc2
,I/HotwordDetector( 1523): Closing mic,
,I/ActivityManager(  820): Killing 2865:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1523): Hotword detection finished
,I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1777): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/Icing   ( 1777): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1777): Could not init tag ds.tag.deleted
,I/ActivityManager(  820): Killing 2970:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/Icing   ( 1777): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1777): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1777): Writing status failed
,E/Icing   ( 1777): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/ConfigService( 1486): onDestroy
,E/QMI_FW  (  820): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659098387
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  870): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1,
E/kickstart(  870): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  870): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  364): qmi_clnt_error_cb: with error -2 called for clnt FUSION
E/ThermalEngine(  364): modem_clnt_error_cb: with -2 called for clnt 0x6
D/        (  356): csd_client_error_cb: error -2 cb_data 0xb601b060,
D/        (  356): csd_client_error_cb: MDM reset
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  374): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  374): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
E/        (  356): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  356): csd_service_deinit: Error -1 deiniting CSD
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb1
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb3,
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb4,
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb7
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb2
,I/ThermalEngine(  364): qmi: Instance id 157 for fusion TS
,E/        (  356): csd_service_deinit: notifier handle release rc:0
,D/        (  356): csd_service_init: qmi_client_notifier_init() successful
,I/qdhwcomposer(  272): handle_blank_event: dpy:0 panel power state: 0

```
