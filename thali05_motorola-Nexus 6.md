#### Test 503880194bce128_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/WearableService( 1809): callingUid 10011, callindPid: 1809
E/MDM     ( 1755): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 1781): Restart initialization of location
--------- beginning of system
I/ActivityManager(  821): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
I/ActivityManager(  821): Resuming delayed broadcast
I/NotifUtils( 2802): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
I/NotifUtils( 2802): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
D/PackageBroadcastService( 1781): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/UpdateIcingCorporaServi( 1525): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageBroadcastService( 1781): Null package name or gms related package.  Ignoreing.
W/Launcher( 1316): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@964eca9 new=com.google.android.velvet.VelvetApplication@964eca9
W/ResourcesManager( 2666): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2666): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 1525): UpdateCorporaTask done [took 35 ms] updated apps [took 35 ms] 
I/art     ( 1781): Explicit concurrent mark sweep GC freed 23827(1641KB) AllocSpace objects, 12(192KB) LOS objects, 36% free, 27MB/43MB, paused 1.071ms total 34.992ms
I/Icing   ( 1781): updateResources: need to parse f{com.google.android.gms}
V/JNIHelp ( 2666): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 2666): Installed default security provider GmsCore_OpenSSL
I/Babel_telephony( 2666): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
I/Babel   ( 2666): connection state changed from UNKNOWN to DISCONNECTED
W/VideoCapabilities( 2666): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2666): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2666): Unrecognized profile 2130706433 for video/avc
,D/AndroidRuntime( 3140): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3140): CheckJNI is OFF
I/MusicLeanback( 2904): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2904): Stop autocaching.
D/AndroidRuntime( 3140): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{101e574a token=Token{130b04b5 ActivityRecord{9efa8ec u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3140): Shutting down VM
I/MicrophoneInputStream( 1525): mic_close com.google.android.apps.gsa.speech.audio.u@2090f641
I/HotwordDetector( 1525): Closing mic
V/WindowManager(  821): Adding window Window{fc3397 u0 Starting com.example.hello} at 3 of 8 (after Window{a17e2db u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  821): Start proc 3160:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
E/GmsUtils( 2904): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
E/GmsUtils( 2904): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1525): Hotword detection finished
I/HotwordRecognitionRnr( 1525): Stopping hotword detection.
I/art     (  821): Explicit concurrent mark sweep GC freed 17339(869KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.166ms total 56.092ms
,I/WebViewFactory( 3160): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  821): Killing 2567:com.google.android.youtube/u0a86 (adj 15): empty #17
I/LibraryLoader( 3160): Time to load native libraries: 1 ms (timestamps 7562-7563)
I/LibraryLoader( 3160): Expected native library version number "",actual native library version number ""
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659561235
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
V/WebViewChromiumFactoryProvider( 3160): Binding Chromium to main looper Looper (main, tid 1) {1553ee56}
I/LibraryLoader( 3160): Expected native library version number "",actual native library version number ""
I/chromium( 3160): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3160): Initializing chromium process, singleProcess=true
W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3160): ApplicationContext is null in ApplicationStatus
W/chromium( 3160): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3160): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3160): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ebfe8f:true
D/BluetoothAdapter( 3160): 1046532781: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3160): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3160): CordovaWebView is running on device made by: motorola
W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  821): Waited long enough for: ServiceRecord{219c43ff u0 org.simalliance.openmobileapi.service/.SmartcardService}
D/OpenGLRenderer( 3160): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3160): Validating map...
V/WindowManager(  821): Adding window Window{c192211 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{fc3397 u0 Starting com.example.hello})
W/chromium( 3160): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3160): Initialized EGL, version 1.4
D/OpenGLRenderer( 3160): Enabling debug mode 0
I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +738ms (total +25s583ms)
I/Keyboard.Facilitator( 1214): onFinishInput()
W/BindingManager( 3160): Cannot call determinedVisibility() - never saw a connection for the pid: 3160
I/chromium( 3160): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3160): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3160): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 3160): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576520832
D/JX-Cordova( 3160): jxcore cordova android initializing
,I/ConfigService( 1484): onDestroy
,W/jxcore-log( 3160): Initializing JXcore engine
W/jxcore-log( 3160): JXcore engine is ready
,W/jxcore-log( 3160): Starting JXcore engine
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{244cfbce u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,W/m.example.hello( 3160): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12909]" dev="sockfs" ino=12909 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3160): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3160): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11594]" dev="sockfs" ino=11594 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3160): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21059]" dev="sockfs" ino=21059 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3160): Platform android
W/jxcore-log( 3160): 
W/jxcore-log( 3160): Process ARCH arm
W/jxcore-log( 3160): 
,I/jxcore-log( 3160): JXcore Cordova bridge is ready!
I/jxcore-log( 3160): 
,W/jxcore-log( 3160): JXcore engine is started
,E/jxcore-log( 3160): >> motorola-Nexus 6
E/jxcore-log( 3160): 
I/jxcore-log( 3160): Total memory 3113791488
I/jxcore-log( 3160): 
I/jxcore-log( 3160): Free memory 1010892800
I/jxcore-log( 3160): 
I/jxcore-log( 3160): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3160): 
I/jxcore-log( 3160): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): userPath [ 'www' ]
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Size 1440 2392
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Screen Brightness 82
I/jxcore-log( 3160): 
,E/jxcore-log( 3160): Dummy Error Log.
E/jxcore-log( 3160): 
,I/jxcore-log( 3160): getBuffer is called!!!!
I/jxcore-log( 3160): 
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{c5665ad u0 com.qualcomm.atfwd/.AtFwdService}
,I/Atfwd_Daemon(  375): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  375): ATFWD --> QMI Port : rmnet_usb0
,I/Atfwd_Daemon(  375): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  375): Trying to register 8 commands:
I/Atfwd_Daemon(  375): cmd0: +CKPD
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  375): cmd1: +CTSA
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): cmd2: +CFUN
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  375): cmd3: +CMAR
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd4: +CDIS
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd5: +CRSL
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd6: +CSS
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): Registered AT Commands event handler
,I/ActivityManager(  821): Killing 2722:com.google.android.deskclock/u0a44 (adj 15): empty #17
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  821): Message: 2
,D/WifiService(  821): New client listening to asynchronous messages
,D/WifiService(  821): setWifiEnabled: false pid=3160, uid=10272
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3160): ****TEST TOOK:  5053  ms ****
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3160): 
,D/AndroidRuntime( 3223): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3223): CheckJNI is OFF
,D/AndroidRuntime( 3223): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3160:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  821): Skipping PackageSetting{246d7bd com.test.thalitest/10265} due to missing metadata
,D/WifiService(  821): Client connection lost with reason: 4
I/WindowState(  821): WIN DEATH: Window{c192211 u0 com.example.hello/com.example.hello.MainActivity}
,W/ActivityManager(  821): Force removing ActivityRecord{9efa8ec u0 com.example.hello/.MainActivity t24}: app died, no saved state
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  821): Spurious death for ProcessRecord{2dabf06f 3160:com.example.hello/u0a272}, curProc for 3160: null
I/Keyboard.Facilitator( 1214): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1214): run()
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 2970): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Decoder ( 1214): createOrResetDecoder
,D/TaskPersister(  821): removeObsoleteFile: deleting file=24_task.xml
,I/art     ( 1065): Explicit concurrent mark sweep GC freed 37297(1546KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 1.245ms total 67.278ms
,I/art     (  821): Explicit concurrent mark sweep GC freed 12361(928KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 32MB/48MB, paused 1.868ms total 76.901ms
,I/art     (  821): WaitForGcToComplete blocked for 36.344ms for cause Explicit
,D/VoicemailCleanupService( 1394): Cleaning up data for package: com.example.hello
,I/ActivityManager(  821): Start proc 3241:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3160 uid 10272
,I/Keyboard.Facilitator( 1214): onFinishInput()
,I/ConfigService( 1484): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): run()
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/LocationOracleImpl( 1525): Best location was null
,W/ErrorReporter( 1525): reportError [type: 29, code: 917507]: null
,W/ContextImpl( 3241): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/HotwordRecognitionRnr( 1525): Starting hotword detection.
,I/MicrophoneInputStream( 1525): mic_starting com.google.android.apps.gsa.speech.audio.u@1ea44251
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4d0e000 ready to run
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = history
E/NetworkScheduler.SchedulerReceiver( 1484): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1484): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1214): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1214): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1214): run()
I/StatsUtilsManager( 1214): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1214): shouldRecordStats() = Too Soon
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1525): mic_started com.google.android.apps.gsa.speech.audio.u@1ea44251
,W/GCoreFlp( 1755): No location to return for getLastLocation()
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
,D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,D/PackageBroadcastService( 1781): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1781): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1781): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
,W/GCoreFlp( 1755): No location to return for getLastLocation()
,I/UpdateIcingCorporaServi( 1525): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/art     (  821): Explicit concurrent mark sweep GC freed 6434(338KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 1.965ms total 183.766ms
,D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1781): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,W/Launcher( 1316): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@964eca9 new=com.google.android.velvet.VelvetApplication@964eca9
,W/GCoreFlp( 1755): No location to return for getLastLocation()
,D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/HotwordWorker( 1525): onReady
,I/ConfigFetchService( 1781): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1781): service connected
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1781): CP2 sync disabled
,I/Icing   ( 1781): doRemovePackageData com.example.hello
,I/UpdateIcingCorporaServi( 1525): UpdateCorporaTask done [took 97 ms] updated apps [took 97 ms] 
,I/art     ( 3223): System.exit called, status: 0
I/AndroidRuntime( 3223): VM exiting with result code 0.
,I/ActivityManager(  821): Start proc 3293:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,W/GCoreFlp( 1755): No location to return for getLastLocation()
,D/Launcher.Workspace( 1316): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1316): 11683562 - stripEmptyScreens()
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659561235
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/DriveInitializer( 1781): Awaiting to be initialized
,W/DriveInitializer( 1781): Background init thread started
,I/ActivityManager(  821): Killing 2835:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3319:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  821): Killing 2703:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 415us total 23.926ms
,W/OpenGLRenderer( 1316): Incorrectly called buildLayer on View: ew, destroying layer...
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 263us total 19.755ms
,I/art     ( 1484): Explicit concurrent mark sweep GC freed 11968(554KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.287ms total 28.500ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 191us total 9.275ms
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
W/DriveInitializer( 1781): Background init thread ended
,D/ExternalStorage( 3319): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 1484): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1484): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1484): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1484): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1484): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1484): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1484): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1484): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1484): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1484): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1484): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1484): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1484): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1484): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1484): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1484): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1484): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1484): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1484): Opened phenotype.db in read-only mode
,E/SQLiteLog( 1484): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1484): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1484): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
,E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1484): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1484): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1484): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1484): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1484): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1484): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 3038): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3038): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3293): Update found 7 roots in 392ms
,D/Documents( 3293): Update found 7 roots in 97ms
,I/CheckinService( 1781): Done disabling old GoogleServicesFramework version
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1781): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/Icing   ( 1781): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1781): Could not init tag ds.tag.deleted
,I/Icing   ( 1781): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1781): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system,
E/Icing   ( 1781): Writing status failed
,E/Icing   ( 1781): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{25e7f974 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  821): Killing 2868:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/ConfigService( 1484): onDestroy
,E/kickstart(  873): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  873): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  873): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,D/        (  358): csd_client_error_cb: error -2 cb_data 0xb602e060,
,D/        (  358): csd_client_error_cb: MDM reset
E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt FUSION
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb0
,I/Atfwd_Daemon(  375): Modem Out Of Service --> Release ATCOP service client handles, if any
E/        (  358): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  358): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  375): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
E/ThermalEngine(  366): modem_clnt_error_cb: with -2 called for clnt 0x7
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb7,
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb5,
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb1,
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb2
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb4
,I/ThermalEngine(  366): qmi: Instance id 157 for fusion TS
,E/        (  358): csd_service_deinit: notifier handle release rc:0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0

```
