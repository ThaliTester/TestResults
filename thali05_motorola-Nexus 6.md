#### Test 502422852e23b2c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,I/MusicStore( 3084): Database version: 120
D/AndroidRuntime( 3110): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3110): CheckJNI is OFF
--------- beginning of system
W/ResourcesManager( 3084): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3084): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3084): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/AndroidRuntime( 3110): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{7f397a8 token=Token{431b3cb ActivityRecord{2bd1ee9a u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  821): Adding window Window{e04f9fd u0 Starting com.example.hello} at 3 of 8 (after Window{3bdd2296 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
D/AndroidRuntime( 3110): Shutting down VM
I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@334df49f
I/ProviderInstaller( 3084): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3084): GMSCore installation verified
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1518): Hotword detection finished
I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
I/ActivityManager(  821): Start proc 3128:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
I/ConfigStore( 3084): Config Database version: 1
I/ActivityManager(  821): Killing 2582:com.google.android.youtube/u0a86 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659151635
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/GAV2    ( 2847): Thread[GAThread,5,main]: No campaign data found.
I/WebViewFactory( 3128): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3128): Time to load native libraries: 2 ms (timestamps 6306-6308)
I/LibraryLoader( 3128): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3128): Binding Chromium to main looper Looper (main, tid 1) {580c036}
I/LibraryLoader( 3128): Expected native library version number "",actual native library version number ""
I/chromium( 3128): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/MediaRouter( 3084): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/BrowserStartupController( 3128): Initializing chromium process, singleProcess=true
W/art     ( 3128): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3128): ApplicationContext is null in ApplicationStatus
W/chromium( 3128): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3128): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3128): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3128): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3128): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/GHttpClientFactory( 3084): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 3084): Using platform SSLCertificateSocketFactory
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18b9d24e:true
D/BluetoothAdapter( 3128): 123573203: getState() :  mService = null. Returning STATE_OFF
I/art     ( 1542): Explicit concurrent mark sweep GC freed 8302(410KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 1.268ms total 25.089ms
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
W/art     ( 3128): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3128): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3128): CordovaWebView is running on device made by: motorola
W/art     ( 3128): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3128): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3128): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  821): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/Atlas   ( 3128): Validating map...
V/WindowManager(  821): Adding window Window{33379479 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{e04f9fd u0 Starting com.example.hello})
I/BackupManagerService(  821): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/chromium( 3128): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/BackupManagerService(  821): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  821): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1243ef7a
I/OpenGLRenderer( 3128): Initialized EGL, version 1.4
D/GCM     ( 1542): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/OpenGLRenderer( 3128): Enabling debug mode 0
V/GmsNetworkLocationProvi( 1760): DISABLE
D/ChimeraCfgMgr( 1790): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 1790): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 1790): [KidAccountFixer] No network connection
I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +675ms (total +23s174ms)
I/Keyboard.Facilitator( 1223): onFinishInput()
W/BindingManager( 3128): Cannot call determinedVisibility() - never saw a connection for the pid: 3128
I/chromium( 3128): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/art     (  821): Explicit concurrent mark sweep GC freed 14689(746KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.235ms total 67.340ms
V/GmsNetworkLocationProvi( 1760): ENABLE
V/GmsNetworkLocationProvi( 1760): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
V/GmsNetworkLocationProvi( 1760): SET-REQUEST
V/GmsNetworkLocationProvi( 1760): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
D/JsMessageQueue( 3128): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3128): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  821): Start proc 3200:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/Launcher( 1322): Deferring update until onResume
W/ResourcesManager( 3200): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/CalendarProvider2( 3200): Created com.android.providers.calendar.CalendarAlarmManager@33bb0dd1(com.android.providers.calendar.CalendarProvider2@580c036)
I/ActivityManager(  821): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
E/SQLiteLog( 3200): (284) automatic index on view_events(_id)
I/ActivityManager(  821): Resuming delayed broadcast
D/GCM     ( 1542): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1542): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1790): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 1822): callingUid 10011, callindPid: 1822
D/jxcore_app_log( 3128): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576519552
D/JX-Cordova( 3128): jxcore cordova android initializing
E/MDM     ( 1760): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 1790): Restart initialization of location
I/ActivityManager(  821): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
I/MediaStoreImporter( 3084): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  821): Resuming delayed broadcast
I/ActivityManager(  821): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
I/ActivityManager(  821): Resuming delayed broadcast
I/ActivityManager(  821): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  821): Resuming delayed broadcast
W/jxcore-log( 3128): Initializing JXcore engine
W/jxcore-log( 3128): JXcore engine is ready
W/jxcore-log( 3128): Starting JXcore engine
I/ActivityManager(  821): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
W/m.example.hello( 3128): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9452]" dev="sockfs" ino=9452 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3128): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3128): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10837]" dev="sockfs" ino=10837 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3128): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21026]" dev="sockfs" ino=21026 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/NotifUtils( 2847): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
W/ResourcesManager( 2681): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2681): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotifUtils( 2847): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
I/ActivityManager(  821): Resuming delayed broadcast
W/jxcore-log( 3128): Platform android
W/jxcore-log( 3128): 
W/jxcore-log( 3128): Process ARCH arm
W/jxcore-log( 3128): 
V/JNIHelp ( 2681): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/jxcore-log( 3128): JXcore Cordova bridge is ready!
I/jxcore-log( 3128): 
W/jxcore-log( 3128): JXcore engine is started
I/ProviderInstaller( 2681): Installed default security provider GmsCore_OpenSSL
E/jxcore-log( 3128): >> motorola-Nexus 6
E/jxcore-log( 3128): 
I/jxcore-log( 3128): Total memory 3113791488
I/jxcore-log( 3128): 
I/jxcore-log( 3128): Free memory 1010438144
I/jxcore-log( 3128): 
I/jxcore-log( 3128): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3128): 
I/jxcore-log( 3128): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3128): 
I/jxcore-log( 3128): userPath [ 'www' ]
I/jxcore-log( 3128): 
I/jxcore-log( 3128): Size 1440 2392
I/jxcore-log( 3128): 
D/PackageBroadcastService( 1790): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/jxcore-log( 3128): Screen Brightness 82
I/jxcore-log( 3128): 
E/jxcore-log( 3128): Dummy Error Log.
E/jxcore-log( 3128): 
I/PackageBroadcastService( 1790): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  821): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/art     ( 2681): Note: end time exceeds epoch: 
I/UpdateIcingCorporaServi( 1518): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Icing   ( 1790): updateResources: need to parse f{com.google.android.gms}
I/Babel_telephony( 2681): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
I/Babel   ( 2681): connection state changed from UNKNOWN to DISCONNECTED
W/VideoCapabilities( 2681): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2681): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2681): Unrecognized profile 2130706433 for video/avc
I/UpdateIcingCorporaServi( 1518): UpdateCorporaTask done [took 41 ms] updated apps [took 41 ms] 
I/ActivityManager(  821): Resuming delayed broadcast
W/Launcher( 1322): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@15b0a609 new=com.google.android.velvet.VelvetApplication@15b0a609
I/ActivityManager(  821): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  821): Resuming delayed broadcast
I/ActivityManager(  821): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  821): Resuming delayed broadcast
I/ActivityManager(  821): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
I/ActivityManager(  821): Resuming delayed broadcast
I/jxcore-log( 3128): getBuffer is called!!!!
I/jxcore-log( 3128): 
I/ConfigService( 1542): onDestroy
I/CalendarProvider2( 3200): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3200): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{3a1c0d88 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{3eb1e8b8 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/Atfwd_Daemon(  374): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  374): ATFWD --> QMI Port : rmnet_usb0
,I/Atfwd_Daemon(  374): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  374): Trying to register 8 commands:
I/Atfwd_Daemon(  374): cmd0: +CKPD
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  374): cmd1: +CTSA
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  374): cmd2: +CFUN
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd3: +CMAR
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{3c1a302c u0 com.qualcomm.atfwd/.AtFwdService}
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd4: +CDIS
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd5: +CRSL
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd6: +CSS
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  374): Registered AT Commands event handler
,I/MusicLeanback( 3084): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3084): Stop autocaching.
,E/GmsUtils( 3084): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3084): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  821): Killing 2766:com.google.android.deskclock/u0a44 (adj 15): empty #17
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  821): Message: 2
,D/WifiService(  821): New client listening to asynchronous messages,
,D/WifiService(  821): setWifiEnabled: false pid=3128, uid=10272,
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled,
I/jxcore-log( 3128): ****TEST TOOK:  5045  ms ****
,I/jxcore-log( 3128): 
I/jxcore-log( 3128): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 3128): 
,D/AndroidRuntime( 3264): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3264): CheckJNI is OFF
,D/AndroidRuntime( 3264): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3128:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  821): Skipping PackageSetting{2104e31d com.test.thalitest/10265} due to missing metadata
,I/WindowState(  821): WIN DEATH: Window{33379479 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  821): Client connection lost with reason: 4
,W/ActivityManager(  821): Force removing ActivityRecord{2bd1ee9a u0 com.example.hello/.MainActivity t24}: app died, no saved state
,W/ActivityManager(  821): Spurious death for ProcessRecord{19cfaa51 3128:com.example.hello/u0a272}, curProc for 3128: null
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,I/Keyboard.Facilitator( 1223): resetDictionaries() : en_US
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1223): run()
D/TaskPersister(  821): removeObsoleteFile: deleting file=24_task.xml
,D/BuaReceiver( 2951): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     ( 1074): Explicit concurrent mark sweep GC freed 37051(1554KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.073ms total 64.710ms
,I/art     (  821): Explicit concurrent mark sweep GC freed 16304(1105KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.456ms total 77.030ms
,I/art     (  821): WaitForGcToComplete blocked for 49.981ms for cause Explicit
,I/Decoder ( 1223): createOrResetDecoder
,D/VoicemailCleanupService( 1401): Cleaning up data for package: com.example.hello
,I/ActivityManager(  821): Start proc 3282:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ConfigService( 1542): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1223): run()
,W/ContextImpl( 3282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1542): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1542): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1223): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1223): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1223): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1223): run()
I/StatsUtilsManager( 1223): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1223): shouldRecordStats() = Too Soon
,D/ChimeraCfgMgr( 1790): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1790): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1790): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1790): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1790): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1790): Module APK com.google.android.play.games already loaded
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3128 uid 10272
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/UpdateIcingCorporaServi( 1518): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/Keyboard.Facilitator( 1223): onFinishInput()
,I/LocationSettingsChecker( 1790): Removing dialog suppression flag for package com.example.hello
,W/Launcher( 1322): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@15b0a609 new=com.google.android.velvet.VelvetApplication@15b0a609
,I/art     (  821): Explicit concurrent mark sweep GC freed 6333(352KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 3.364ms total 129.908ms
D/GOOGLEHELP_CompatibleDatabase( 1790): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1790): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1790): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1790): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/LocationOracleImpl( 1518): Best location was null
,W/ErrorReporter( 1518): reportError [type: 29, code: 917507]: null
D/GOOGLEHELP_CompatibleDatabase( 1790): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1790): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1790): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1790): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1790): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1790): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/HotwordRecognitionRnr( 1518): Starting hotword detection.
,D/GOOGLEHELP_CompatibleDatabase( 1790): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1790): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1790): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0,
I/MicrophoneInputStream( 1518): mic_starting com.google.android.apps.gsa.speech.audio.u@29589afb
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/AudioFlinger(  357): AudioFlinger's thread 0xb40ed000 ready to run
,I/MicrophoneInputStream( 1518): mic_started com.google.android.apps.gsa.speech.audio.u@29589afb
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/art     ( 3264): System.exit called, status: 0
I/AndroidRuntime( 3264): VM exiting with result code 0.
,I/art     ( 1790): Explicit concurrent mark sweep GC freed 27714(1967KB) AllocSpace objects, 17(272KB) LOS objects, 36% free, 28MB/44MB, paused 2.604ms total 67.924ms
,I/ActivityManager(  821): Start proc 3326:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,W/GCoreFlp( 1760): No location to return for getLastLocation()
,I/ConfigFetchService( 1790): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1790): Using Auth Proxy for data requests.
,I/HotwordWorker( 1518): onReady
,I/ConfigFetchService( 1790): service connected
,I/PeopleContactsSync( 1790): CP2 sync disabled
,W/BaseAppContext( 1790): Using Auth Proxy for data requests.
,W/GCoreFlp( 1760): No location to return for getLastLocation()
,I/Icing   ( 1790): doRemovePackageData com.example.hello
,I/UpdateIcingCorporaServi( 1518): UpdateCorporaTask done [took 226 ms] updated apps [took 226 ms] 
,D/Launcher.Workspace( 1322): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1322): 11683562 - stripEmptyScreens()
,I/art     ( 1760): Explicit concurrent mark sweep GC freed 13476(769KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 936us total 49.983ms
,W/GCoreFlp( 1760): No location to return for getLastLocation()
,W/DriveInitializer( 1790): Awaiting to be initialized
,W/DriveInitializer( 1790): Background init thread started
,W/GCoreFlp( 1760): No location to return for getLastLocation()
,W/FileUtils( 3326): Failed to chmod(/data/data/com.android.documentsui/databases/recents.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 1790): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1790): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1790): disk I/O error (code 3850)
E/DriveAsyncService( 1790): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1790): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1790): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1790): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1790): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1790): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1790): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1790): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1790): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1790): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1790): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1790): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1790): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1790): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1790): 	at java.lang.Thread.run(Thread.java:818)
,W/DriveInitializer( 1790): Background init thread ended
,--------- beginning of crash
E/AndroidRuntime( 1790): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1790): Process: com.google.android.gms, PID: 1790
E/AndroidRuntime( 1790): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1790): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1790): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1790): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1790): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1790): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1790): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1790): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/AndroidRuntime( 1790): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/AndroidRuntime( 1790): 	at com.google.android.gms.drive.database.f.e(SourceFile:804)
E/AndroidRuntime( 1790): 	at com.google.android.gms.drive.events.ao.a(SourceFile:135)
E/AndroidRuntime( 1790): 	at com.google.android.gms.drive.r.run(SourceFile:72)
,I/ActivityManager(  821): Start proc 3353:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  821): Killing 2123:com.android.defcontainer/u0a7 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659151635
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/art     (  368): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 232us total 10.004ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.795ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 189us total 9.096ms
,I/ActivityManager(  821): Killing 2882:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,W/OpenGLRenderer( 1322): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
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
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true,
,D/Atlas   (  821): Validating map...,
,D/ExternalStorage( 3353): After updating volumes, found 1 active roots
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,D/OpenGLRenderer(  821): Enabling debug mode 0
,W/ResourcesManager( 3021): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3021): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3326): Update found 7 roots in 410ms
,D/Documents( 3326): Update found 7 roots in 154ms
,I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@29589afb
,I/ActivityManager(  821): Killing 2747:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
I/HotwordRecognitionRnr( 1518): Hotword detection finished
,E/native  ( 1223): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1223): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1223): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1223): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1223): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1223): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1223): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1223): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/SQLiteLog( 2681): (3850) statement aborts at 28: [UPDATE requests SET server_target_retry=?,server_fail_count=?,fail_count=? WHERE _id=?] disk I/O error
,E/Babel_Crash( 2681): Uncaught exception in background thread Thread[default_queue1,5,main]
E/Babel_Crash( 2681): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Babel_Crash( 2681): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/Babel_Crash( 2681): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/Babel_Crash( 2681): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/Babel_Crash( 2681): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/Babel_Crash( 2681): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/Babel_Crash( 2681): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/Babel_Crash( 2681): 	at dhe.a(SourceFile:3360)
E/Babel_Crash( 2681): 	at cap.d(SourceFile:393)
E/Babel_Crash( 2681): 	at caq.run(SourceFile:81)
,E/SharedPreferencesImpl( 2681): Couldn't rename file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml to backup file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml.bak
E/AndroidRuntime( 2681): FATAL EXCEPTION: default_queue1
E/AndroidRuntime( 2681): Process: com.google.android.talk, PID: 2681
E/AndroidRuntime( 2681): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/AndroidRuntime( 2681): 	at dhe.a(SourceFile:3360)
E/AndroidRuntime( 2681): 	at cap.d(SourceFile:393)
E/AndroidRuntime( 2681): 	at caq.run(SourceFile:81)
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
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
,I/Icing   ( 1790): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/SQLiteDatabase( 1542): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1542): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1542): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1542): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1542): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1542): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1542): 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
E/SQLiteDatabase( 1542): 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
E/SQLiteDatabase( 1542): 	at com.google.android.gms.playlog.service.c.a(SourceFile:103)
E/SQLiteDatabase( 1542): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1542): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1542): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1542): 	at java.lang.Thread.run(Thread.java:818)
,E/PlayLogIntentService( 1542): not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1542): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PlayLogIntentService( 1542): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/PlayLogIntentService( 1542): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 1542): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PlayLogIntentService( 1542): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PlayLogIntentService( 1542): 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
E/PlayLogIntentService( 1542): 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
E/PlayLogIntentService( 1542): 	at com.google.android.gms.playlog.service.c.a(SourceFile:103)
E/PlayLogIntentService( 1542): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/PlayLogIntentService( 1542): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 1542): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 1542): 	at java.lang.Thread.run(Thread.java:818)
E/Icing   ( 1790): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1790): Could not init tag ds.tag.deleted
,I/Icing   ( 1790): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
E/Icing   ( 1790): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1790): Writing status failed
E/Icing   ( 1790): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/CheckinService( 1790): Done disabling old GoogleServicesFramework version
,E/SQLiteLog( 3200): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DatabaseUtils( 3200): Writing exception to parcel
E/DatabaseUtils( 3200): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 3200): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 3200): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DatabaseUtils( 3200): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 3200): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 3200): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 3200): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 3200): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1351)
E/DatabaseUtils( 3200): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1109)
E/DatabaseUtils( 3200): 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:938)
E/DatabaseUtils( 3200): 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:839)
E/DatabaseUtils( 3200): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 3200): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 3200): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 3200): 	at android.os.Binder.execTransact(Binder.java:446)
,E/AndroidRuntime( 2404): FATAL EXCEPTION: AlertService
E/AndroidRuntime( 2404): Process: com.google.android.calendar, PID: 2404
E/AndroidRuntime( 2404): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2404): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2404): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 2404): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
E/AndroidRuntime( 2404): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 2404): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 2404): 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:158)
E/AndroidRuntime( 2404): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
E/AndroidRuntime( 2404): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
E/AndroidRuntime( 2404): 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:244)
E/AndroidRuntime( 2404): 	at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:897)
E/AndroidRuntime( 2404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2404): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  821): Can't write: system_app_crash,
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop91.tmp: open failed: EROFS (Read-only file system),
E/DropBoxManagerService(  821): 	,at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
,E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
,E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{2b26baad u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ConfigService( 1542): onDestroy
,E/QMI_FW  (  821): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659151635
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  871): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  871): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  871): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  365): qmi_clnt_error_cb: with error -2 called for clnt FUSION,
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  374): Modem Out Of Service --> Release ATCOP service client handles, if any
,I/Atfwd_Daemon(  374): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
E/ThermalEngine(  365): modem_clnt_error_cb: with -2 called for clnt 0x8
,D/        (  357): csd_client_error_cb: error -2 cb_data 0xb5468060
D/        (  357): csd_client_error_cb: MDM reset
,E/        (  357): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2,
E/        (  357): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb1
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb2
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb3,
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb4
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb6
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb7
,I/ThermalEngine(  365): qmi: Instance id 157 for fusion TS
,E/        (  357): csd_service_deinit: notifier handle release rc:0
,D/        (  357): csd_service_init: qmi_client_notifier_init() successful
,V/ImsSenderRxr( 1286): Read packet: 15 bytes
V/ImsSenderRxr( 1286): processResponse
D/ImsSenderRxr( 1286): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
D/ImsSenderRxr( 1286):  Tag -1 3 213 0
,I/str_params(  357): key: 'all_call_states' value: ''
I/str_params(  357): key: 'all_call_states' value: ''
,I/str_params(  357): key: 'all_call_states' value: ''
,E/ThermalEngine(  365): qmi_clnt_error_cb: with error -2 called for clnt MODEM
,D/QC-time-services(  372): Daemon:genoff_modem_qmi_init: Initiallizing QMI 
,E/QMI_FW  (  372): QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1

```
