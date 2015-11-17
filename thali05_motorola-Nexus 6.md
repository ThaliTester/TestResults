#### Test 50388019c82294c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/Atfwd_Daemon(  375): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  375): ATFWD --> QMI Port : rmnet_usb0
I/Atfwd_Daemon(  375): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  375): Trying to register 8 commands:
I/Atfwd_Daemon(  375): cmd0: +CKPD
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd1: +CTSA
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd2: +CFUN
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd3: +CMAR
--------- beginning of system
I/ActivityManager(  821): Waited long enough for: ServiceRecord{1bc99319 u0 com.qualcomm.atfwd/.AtFwdService}
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
,D/AndroidRuntime( 3131): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3131): CheckJNI is OFF
D/AndroidRuntime( 3131): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{2f8f3f84 token=Token{1dade197 ActivityRecord{38464416 u0 com.example.hello/.MainActivity t20}}} to stack=1 task=20 at 0
V/WindowManager(  821): Adding window Window{aadd969 u0 Starting com.example.hello} at 3 of 8 (after Window{b236ac0 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
D/AndroidRuntime( 3131): Shutting down VM
I/HotwordDetector( 1540): Closing mic
I/MicrophoneInputStream( 1540): mic_close com.google.android.apps.gsa.speech.audio.u@9f5a1a
I/ActivityManager(  821): Start proc 3146:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1540): Hotword detection finished
I/HotwordRecognitionRnr( 1540): Stopping hotword detection.
W/GCoreFlp( 1758): No location to return for getLastLocation()
I/ActivityManager(  821): Killing 2710:com.google.android.deskclock/u0a44 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660536083
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3146): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3146): Time to load native libraries: 2 ms (timestamps 2308-2310)
I/LibraryLoader( 3146): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3146): Binding Chromium to main looper Looper (main, tid 1) {21529f1d}
,I/LibraryLoader( 3146): Expected native library version number "",actual native library version number ""
I/chromium( 3146): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3146): Initializing chromium process, singleProcess=true
W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3146): ApplicationContext is null in ApplicationStatus
,W/chromium( 3146): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3146): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3146): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3146): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3146): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9ee5c23:true
,D/BluetoothAdapter( 3146): 786556300: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3146): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3146): CordovaWebView is running on device made by: motorola
,W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3146): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3146): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3146): Validating map...
,V/WindowManager(  821): Adding window Window{323e9413 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{aadd969 u0 Starting com.example.hello})
,W/chromium( 3146): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3146): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3146): Enabling debug mode 0
,I/Keyboard.Facilitator( 1234): onFinishInput()
,I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +813ms (total +30s52ms)
,W/BindingManager( 3146): Cannot call determinedVisibility() - never saw a connection for the pid: 3146
,I/chromium( 3146): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 3146): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3146): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 3146): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576515840
,D/JX-Cordova( 3146): jxcore cordova android initializing
,W/jxcore-log( 3146): Initializing JXcore engine
W/jxcore-log( 3146): JXcore engine is ready
,W/jxcore-log( 3146): Starting JXcore engine,
,W/m.example.hello( 3146): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9424]" dev="sockfs" ino=9424 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3146): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3146): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12755]" dev="sockfs" ino=12755 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3146): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19219]" dev="sockfs" ino=19219 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3146): Platform android
W/jxcore-log( 3146): 
W/jxcore-log( 3146): Process ARCH arm
W/jxcore-log( 3146): 
,I/jxcore-log( 3146): JXcore Cordova bridge is ready!
I/jxcore-log( 3146): 
,W/jxcore-log( 3146): JXcore engine is started
,E/jxcore-log( 3146): >> motorola-Nexus 6
E/jxcore-log( 3146): 
,I/jxcore-log( 3146): Total memory 3113791488
I/jxcore-log( 3146): 
,I/jxcore-log( 3146): Free memory 1014312960
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
,I/CheckinService( 1793): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{1705d46a u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  821): Killing 2835:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  821): Message: 2
,D/WifiService(  821): New client listening to asynchronous messages,
D/WifiService(  821): setWifiEnabled: false pid=3146, uid=10272
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3146): ****TEST TOOK:  5045  ms ****
I/jxcore-log( 3146): 
,I/jxcore-log( 3146): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3146): 
,D/AndroidRuntime( 3202): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3202): CheckJNI is OFF
,D/AndroidRuntime( 3202): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
,I/ActivityManager(  821): Killing 3146:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  821): Skipping PackageSetting{1de27bb0 com.test.thalitest/10265} due to missing metadata
,I/WindowState(  821): WIN DEATH: Window{323e9413 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  821): Client connection lost with reason: 4
,W/ActivityManager(  821): Force removing ActivityRecord{38464416 u0 com.example.hello/.MainActivity t20}: app died, no saved state
,W/ActivityManager(  821): Spurious death for ProcessRecord{1ec34f68 3146:com.example.hello/u0a272}, curProc for 3146: null
I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,D/TaskPersister(  821): removeObsoleteFile: deleting file=20_task.xml
,I/Keyboard.Facilitator( 1234): resetDictionaries() : en_US
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010,
,I/Keyboard.Facilitator.DecoderInitializer( 1234): run()
I/Decoder ( 1234): createOrResetDecoder
,D/BuaReceiver( 2956): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     ( 1068): Explicit concurrent mark sweep GC freed 36309(1507KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 1.681ms total 80.408ms
,I/ConfigService( 1492): onCreate
,I/art     (  821): Explicit concurrent mark sweep GC freed 20846(1326KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.852ms total 89.573ms
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3146 uid 10272
,I/Keyboard.Facilitator( 1234): onFinishInput()
,I/art     (  821): Explicit concurrent mark sweep GC freed 6872(413KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 1.455ms total 50.178ms
I/art     (  821): WaitForGcToComplete blocked for 62.880ms for cause Explicit
,D/VoicemailCleanupService( 1399): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1234): run()
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1234): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1234): run() : Loaded (exit)
I/ActivityManager(  821): Start proc 3222:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/Keyboard.Facilitator.Delight2FileSweeper( 1234): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1234): run()
I/StatsUtilsManager( 1234): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1234): shouldRecordStats() = Too Soon
,W/LocationOracleImpl( 1540): Best location was null
,W/ErrorReporter( 1540): reportError [type: 29, code: 917507]: null
,W/GCoreFlp( 1758): No location to return for getLastLocation()
,I/HotwordRecognitionRnr( 1540): Starting hotword detection.
I/MicrophoneInputStream( 1540): mic_starting com.google.android.apps.gsa.speech.audio.u@222a18cb
I/AudioFlinger(  358): AudioFlinger's thread 0xb406a000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1540): mic_started com.google.android.apps.gsa.speech.audio.u@222a18cb
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,D/Launcher.Workspace( 1319): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1319): 11683562 - stripEmptyScreens()
,W/GCoreFlp( 1758): No location to return for getLastLocation()
,W/GCoreFlp( 1758): No location to return for getLastLocation()
,W/ContextImpl( 3222): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1492): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1492): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/HotwordWorker( 1540): onReady
,D/PackageBroadcastService( 1793): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1793): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1793): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1793): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1793): Removing dialog suppression flag for package com.example.hello
,W/GCoreFlp( 1758): No location to return for getLastLocation()
,I/UpdateIcingCorporaServi( 1540): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/GOOGLEHELP_CompatibleDatabase( 1793): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1793): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1793): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1793): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/Launcher( 1319): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2ee1e58c new=com.google.android.velvet.VelvetApplication@2ee1e58c
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660536083
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
D/GOOGLEHELP_CompatibleDatabase( 1793): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1793): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1793): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1793): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1793): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1793): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1793): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1793): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1793): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ConfigFetchService( 1793): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1793): Using Auth Proxy for data requests.
,W/BaseAppContext( 1793): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1793): CP2 sync disabled
,I/art     (  821): Explicit concurrent mark sweep GC freed 8041(346KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 2.214ms total 280.113ms
,I/Icing   ( 1793): doRemovePackageData com.example.hello
,I/UpdateIcingCorporaServi( 1540): UpdateCorporaTask done [took 114 ms] updated apps [took 113 ms] 
,I/art     ( 3202): System.exit called, status: 0
I/AndroidRuntime( 3202): VM exiting with result code 0.
I/ActivityManager(  821): Start proc 3268:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,W/DriveInitializer( 1793): Awaiting to be initialized
,W/DriveInitializer( 1793): Background init thread started
,I/ActivityManager(  821): Start proc 3290:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  821): Killing 2662:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,W/OpenGLRenderer( 1319): Incorrectly called buildLayer on View: ew, destroying layer...
,E/SQLiteLog( 1793): (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 1793): Failed to delete from FileContent112
E/DocListDatabase( 1793): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1793): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1793): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1793): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1793): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1793): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/DocListDatabase( 1793): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/DocListDatabase( 1793): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/DocListDatabase( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1793): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 1793): FATAL EXCEPTION: pool-13-thread-1
E/AndroidRuntime( 1793): Process: com.google.android.gms, PID: 1793
E/AndroidRuntime( 1793): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1793): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1793): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/AndroidRuntime( 1793): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/AndroidRuntime( 1793): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/AndroidRuntime( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1793): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
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
D/ExternalStorage( 3290): After updating volumes, found 1 active roots
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  821): Validating map...
,I/art     ( 1492): Explicit concurrent mark sweep GC freed 9067(427KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.024ms total 20.324ms
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/DriveInitializer( 1793): Background init thread ended
E/SQLiteLog( 1793): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1793): disk I/O error (code 3850)
E/DriveAsyncService( 1793): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1793): 	at java.lang.Thread.run(Thread.java:818)
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,D/OpenGLRenderer(  821): Enabling debug mode 0
,W/ResourcesManager( 3021): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3021): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3268): Update found 7 roots in 251ms
,D/Documents( 3268): Update found 7 roots in 122ms
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/HotwordDetector( 1540): Closing mic
,I/MicrophoneInputStream( 1540): mic_close com.google.android.apps.gsa.speech.audio.u@222a18cb,
,I/GLSUser ( 1492): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1492): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1492): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1492): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1492): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/ActivityManager(  821): Killing 2868:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1540): Hotword detection finished
I/HotwordRecognitionRnr( 1540): Stopping hotword detection.
,D/Finsky  ( 2733): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2733): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2733): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,I/ActivityManager(  821): Killing 2208:com.android.providers.calendar/u0a3 (adj 15): empty #17
,E/QMI_FW  (  821): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660536083
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/qdoverlay(  260): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  260): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,E/qdoverlay(  260): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  260): dst_rect mdp_rect x=0 y=0 w=720 h=2560,
E/qdoverlay(  260): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted,
E/qdoverlay(  260): MdpCtrl close error in unset
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  260): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  260): MdpCtrl close error in unset

```
