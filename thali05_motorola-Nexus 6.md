#### Test 50388019b17f598_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
W/ResourcesManager( 3047): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3047): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  822): Start proc 3089:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  822): Killing 2523:com.qualcomm.telephony/1001 (adj 15): empty #17
W/ResourcesManager( 3089): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
--------- beginning of main
I/Icing   ( 1784): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
V/JNIHelp ( 3047): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Icing   ( 1784): Loaded CLD2 Version V2.0 - 20141016
I/ProviderInstaller( 3047): Installed default security provider GmsCore_OpenSSL
I/art     ( 1505): Explicit concurrent mark sweep GC freed 7174(358KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.432ms total 46.525ms
I/Icing   ( 1784): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
V/GLSActivity( 1505): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Killing 2598:com.google.android.youtube/u0a86 (adj 15): empty #17
D/AndroidRuntime( 3110): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3110): CheckJNI is OFF
D/GCM     ( 1505): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/AndroidRuntime( 3110): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3853ab1b token=Token{40ef12a ActivityRecord{21185a15 u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
I/art     ( 1784): Explicit concurrent mark sweep GC freed 24407(1713KB) AllocSpace objects, 13(208KB) LOS objects, 36% free, 27MB/43MB, paused 3.131ms total 48.312ms
V/WindowManager(  822): Adding window Window{26b4f464 u0 Starting com.example.hello} at 3 of 8 (after Window{2f78b070 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
D/AndroidRuntime( 3110): Shutting down VM
I/HotwordDetector( 1531): Closing mic
I/MicrophoneInputStream( 1531): mic_close com.google.android.apps.gsa.speech.audio.u@32ceb222
I/ActivityManager(  822): Start proc 3136:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 1784): [KidAccountFixer] No network connection
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/GAV2    ( 2838): Thread[GAThread,5,main]: No campaign data found.
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1531): Stopping hotword detection.
I/HotwordRecognitionRnr( 1531): Hotword detection finished
I/ActivityManager(  822): Killing 2697:com.google.android.talk/u0a61 (adj 15): empty #17
I/ActivityManager(  822): Start proc 3160:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/WebViewFactory( 3136): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/GCoreFlp( 1752): No location to return for getLastLocation()
I/LibraryLoader( 3136): Time to load native libraries: 1 ms (timestamps 6557-6558)
I/LibraryLoader( 3136): Expected native library version number "",actual native library version number ""
W/ResourcesManager( 3160): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 3136): Binding Chromium to main looper Looper (main, tid 1) {3fdfeb45}
I/LibraryLoader( 3136): Expected native library version number "",actual native library version number ""
I/chromium( 3136): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3136): Initializing chromium process, singleProcess=true
W/art     ( 3136): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3136): ApplicationContext is null in ApplicationStatus
W/chromium( 3136): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3136): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/CalendarProvider2( 3160): Created com.android.providers.calendar.CalendarAlarmManager@27a4cfbc(com.android.providers.calendar.CalendarProvider2@3fdfeb45)
E/libEGL  ( 3136): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3136): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3136): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/GCM     ( 1505): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1505): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659360531
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/SQLiteLog( 3160): (284) automatic index on view_events(_id)
V/GmsCoreStatsServiceLauncher( 1784): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 1811): callingUid 10011, callindPid: 1811
D/LocationInitializer( 1784): Restart initialization of location
E/MDM     ( 1752): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f4ba3d7:true
D/BluetoothAdapter( 3136): 227937894: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  822): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  822): Resuming delayed broadcast
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
W/art     ( 3136): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3136): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3136): CordovaWebView is running on device made by: motorola
I/ActivityManager(  822): Start proc 3211:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
W/art     ( 3136): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3136): Attempt to remove local handle scope entry from IRT, ignoring
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  822): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  822): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/OpenGLRenderer( 3136): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
I/NotifUtils( 2838): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
D/Atlas   ( 3136): Validating map...
V/WindowManager(  822): Adding window Window{2610757f u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{26b4f464 u0 Starting com.example.hello})
W/chromium( 3136): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/ResourcesManager( 3211): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/OpenGLRenderer( 3136): Initialized EGL, version 1.4
D/OpenGLRenderer( 3136): Enabling debug mode 0
I/art     ( 1752): Explicit concurrent mark sweep GC freed 14150(775KB) AllocSpace objects, 5(80KB) LOS objects, 37% free, 26MB/42MB, paused 1.147ms total 53.484ms
V/BackupManagerService(  822): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  822): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a814e38
V/GmsNetworkLocationProvi( 1752): DISABLE
I/Keyboard.Facilitator( 1213): onFinishInput()
I/ActivityManager(  822): Displayed com.example.hello/.MainActivity: +510ms (total +23s947ms)
W/BindingManager( 3136): Cannot call determinedVisibility() - never saw a connection for the pid: 3136
I/chromium( 3136): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/NotifUtils( 2838): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
V/GmsNetworkLocationProvi( 1752): ENABLE
V/GmsNetworkLocationProvi( 1752): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
V/GmsNetworkLocationProvi( 1752): SET-REQUEST
V/GmsNetworkLocationProvi( 1752): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
D/JsMessageQueue( 3136): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3136): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/Launcher( 1308): Deferring update until onResume
I/Babel_SMS( 3211): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3211): MmsConfig.loadMmsSettings
I/Babel_SMS( 3211): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3211): MmsConfig.loadFromDatabase
E/Babel_SMS( 3211): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3211): MmsConfig.loadFromResources
E/Babel_SMS( 3211): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3211): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/art     (  822): Explicit concurrent mark sweep GC freed 18735(966KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.261ms total 55.897ms
D/jxcore_app_log( 3136): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576513280
D/JX-Cordova( 3136): jxcore cordova android initializing
W/Settings( 3211): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 3211): startup - clean
I/Babel   ( 3211): deleted: false for 0
I/Babel_telephony( 3211): TeleModule.launchCompleted
W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
I/Babel_telephony( 3211): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3211): BAM#gBA: invalid account id: -1
W/Babel   ( 3211): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3211): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
W/jxcore-log( 3136): Initializing JXcore engine
W/jxcore-log( 3136): JXcore engine is ready
W/jxcore-log( 3136): Starting JXcore engine
W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
W/m.example.hello( 3136): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12508]" dev="sockfs" ino=12508 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3136): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3136): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9892]" dev="sockfs" ino=9892 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3136): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20021]" dev="sockfs" ino=20021 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/VideoCapabilities( 3211): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 3211): onServiceConnected
W/Babel   ( 3211): Attempted to change video mute state without an active call.
I/ActivityManager(  822): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
W/jxcore-log( 3136): Platform android
W/jxcore-log( 3136): 
W/jxcore-log( 3136): Process ARCH arm
W/jxcore-log( 3136): 
I/ActivityManager(  822): Resuming delayed broadcast
W/ResourcesManager( 3211): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3211): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/jxcore-log( 3136): JXcore Cordova bridge is ready!
I/jxcore-log( 3136): 
W/jxcore-log( 3136): JXcore engine is started
V/JNIHelp ( 3211): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/jxcore-log( 3136): >> motorola-Nexus 6
E/jxcore-log( 3136): 
,I/jxcore-log( 3136): Total memory 3113791488
I/jxcore-log( 3136): 
I/jxcore-log( 3136): Free memory 1010413568
I/jxcore-log( 3136): 
I/jxcore-log( 3136): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3136): 
I/jxcore-log( 3136): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3136): 
,I/jxcore-log( 3136): userPath [ 'www' ]
I/jxcore-log( 3136): 
,I/jxcore-log( 3136): Size 1440 2392
I/jxcore-log( 3136): 
,I/jxcore-log( 3136): Screen Brightness 82
I/jxcore-log( 3136): 
E/jxcore-log( 3136): Dummy Error Log.
E/jxcore-log( 3136): 
I/ProviderInstaller( 3211): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  822): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,D/PackageBroadcastService( 1784): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/UpdateIcingCorporaServi( 1531): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 1784): Null package name or gms related package.  Ignoreing.
I/Babel_telephony( 3211): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,I/Icing   ( 1784): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3211): Unrecognized profile 2130706433 for video/avc
I/UpdateIcingCorporaServi( 1531): UpdateCorporaTask done [took 33 ms] updated apps [took 33 ms] 
I/ActivityManager(  822): Resuming delayed broadcast
W/Launcher( 1308): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@139d5a54 new=com.google.android.velvet.VelvetApplication@139d5a54
,I/ActivityManager(  822): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/Babel   ( 3211): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  822): Resuming delayed broadcast
,I/ActivityManager(  822): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  822): Resuming delayed broadcast
,I/CalendarProvider2( 3160): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3160): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 3136): getBuffer is called!!!!
I/jxcore-log( 3136): 
,I/MusicLeanback( 2942): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 2942): Stop autocaching.
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{12c2363a u0 org.simalliance.openmobileapi.service/.SmartcardService}
,E/GmsUtils( 2942): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2942): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{24ba6cdb u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ConfigService( 1505): onDestroy
,I/Atfwd_Daemon(  374): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  374): ATFWD --> QMI Port : rmnet_usb0
,I/Atfwd_Daemon(  374): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  374): Trying to register 8 commands:
I/Atfwd_Daemon(  374): cmd0: +CKPD
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd1: +CTSA
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd2: +CFUN
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd3: +CMAR
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd4: +CDIS
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd5: +CRSL
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): cmd6: +CSS
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  374): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  374): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  374): Registered AT Commands event handler
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{e4d6a62 u0 com.qualcomm.atfwd/.AtFwdService}
,I/ActivityManager(  822): Killing 2759:com.google.android.deskclock/u0a44 (adj 15): empty #17
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  822): Message: 2
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: false pid=3136, uid=10272
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3136): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 3136): 
,I/jxcore-log( 3136): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3136): 
,D/AndroidRuntime( 3290): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3290): CheckJNI is OFF,
,D/AndroidRuntime( 3290): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3136:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  822): Skipping PackageSetting{1dc121f8 com.test.thalitest/10265} due to missing metadata
,I/WindowState(  822): WIN DEATH: Window{2610757f u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
,W/ActivityManager(  822): Force removing ActivityRecord{21185a15 u0 com.example.hello/.MainActivity t24}: app died, no saved state,
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  822): Spurious death for ProcessRecord{3cf17d1a 3136:com.example.hello/u0a272}, curProc for 3136: null
,D/TaskPersister(  822): removeObsoleteFile: deleting file=24_task.xml
,I/Keyboard.Facilitator( 1213): resetDictionaries() : en_US
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 2982): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1213): run()
,I/Decoder ( 1213): createOrResetDecoder
,I/art     ( 1062): Explicit concurrent mark sweep GC freed 37010(1535KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 1.441ms total 70.142ms
,D/VoicemailCleanupService( 2467): Cleaning up data for package: com.example.hello
,I/art     (  822): Explicit concurrent mark sweep GC freed 13671(996KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 32MB/48MB, paused 1.331ms total 84.093ms
,I/art     (  822): WaitForGcToComplete blocked for 71.034ms for cause Explicit
,I/ActivityManager(  822): Start proc 3308:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ConfigService( 1505): onCreate
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 314us total 17.169ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 14.731ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): run()
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 230us total 10.619ms
,W/ContextImpl( 3308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = contacts
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3136 uid 10272
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1213): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1213): run()
I/Keyboard.Facilitator( 1213): onFinishInput()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1213): run()
I/StatsUtilsManager( 1213): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1213): shouldRecordStats() = Too Soon
,E/NetworkScheduler.SchedulerReceiver( 1505): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1505): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/PackageBroadcastService( 1784): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1784): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
,W/LocationOracleImpl( 1531): Best location was null
,W/ErrorReporter( 1531): reportError [type: 29, code: 917507]: null
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1784): Removing dialog suppression flag for package com.example.hello
,I/HotwordRecognitionRnr( 1531): Starting hotword detection.
,I/MicrophoneInputStream( 1531): mic_starting com.google.android.apps.gsa.speech.audio.u@2877287
,I/AudioFlinger(  357): AudioFlinger's thread 0xb43a6000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1531): mic_started com.google.android.apps.gsa.speech.audio.u@2877287
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,D/GOOGLEHELP_CompatibleDatabase( 1784): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1784): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1784): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1784): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,I/art     (  822): Explicit concurrent mark sweep GC freed 7103(374KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 2.139ms total 165.143ms
,D/GOOGLEHELP_CompatibleDatabase( 1784): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1784): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1784): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ConfigFetchService( 1784): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/ConfigFetchService( 1784): service connected
D/GOOGLEHELP_CompatibleDatabase( 1784): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1784): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1784): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1784): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1784): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1784): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PeopleContactsSync( 1784): CP2 sync disabled
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
I/Icing   ( 1784): doRemovePackageData com.example.hello
I/UpdateIcingCorporaServi( 1531): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
W/Launcher( 1308): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@139d5a54 new=com.google.android.velvet.VelvetApplication@139d5a54
,I/art     ( 3290): System.exit called, status: 0
I/AndroidRuntime( 3290): VM exiting with result code 0.
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,I/HotwordWorker( 1531): onReady
,I/ActivityManager(  822): Start proc 3358:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,D/Launcher.Workspace( 1308): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1308): 11683562 - stripEmptyScreens()
,I/UpdateIcingCorporaServi( 1531): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
W/GCoreFlp( 1752): No location to return for getLastLocation()
,E/SQLiteLog( 3160): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DatabaseUtils( 3160): Writing exception to parcel
E/DatabaseUtils( 3160): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 3160): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 3160): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DatabaseUtils( 3160): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 3160): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 3160): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 3160): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 3160): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1351)
E/DatabaseUtils( 3160): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1109)
E/DatabaseUtils( 3160): 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:938)
E/DatabaseUtils( 3160): 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:839)
E/DatabaseUtils( 3160): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 3160): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 3160): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 3160): 	at android.os.Binder.execTransact(Binder.java:446)
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659360531
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,--------- beginning of crash
E/AndroidRuntime( 2388): FATAL EXCEPTION: AlertService
E/AndroidRuntime( 2388): Process: com.google.android.calendar, PID: 2388
E/AndroidRuntime( 2388): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2388): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2388): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 2388): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
E/AndroidRuntime( 2388): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 2388): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 2388): 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:158)
E/AndroidRuntime( 2388): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
E/AndroidRuntime( 2388): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
E/AndroidRuntime( 2388): 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:244)
E/AndroidRuntime( 2388): 	at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:897)
E/AndroidRuntime( 2388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2388): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
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
,I/art     ( 1505): Explicit concurrent mark sweep GC freed 15824(734KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 2.435ms total 27.582ms
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
,W/DriveInitializer( 1784): Awaiting to be initialized
,W/DriveInitializer( 1784): Background init thread started
,E/SQLiteLog( 1784): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/DocListDatabase( 1784): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1784): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1784): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1784): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1784): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1784): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1784): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1784): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1784): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1784): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 1784): Background init thread ended
E/AndroidRuntime( 1784): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1784): Process: com.google.android.gms, PID: 1784
E/AndroidRuntime( 1784): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1784): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1784): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1784): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1784): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1784): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1784): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1784): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 1784): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/SQLiteLog( 1784): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1784): disk I/O error (code 3850)
E/DriveAsyncService( 1784): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1784): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1784): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1784): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1784): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1784): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1784): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1784): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1784): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1784): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1784): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1784): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1784): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1784): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1784): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  822): Can't write: system_app_crash
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
E/SQLiteDatabase( 3358): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3358): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3358): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3358): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3358): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3358): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3358): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3358): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 3358): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3358): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3358): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 3358): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 3358): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 3358): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3358): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3358): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 3358): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3358): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 3358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 3358): Shutting down VM
E/AndroidRuntime( 3358): FATAL EXCEPTION: main
E/AndroidRuntime( 3358): Process: com.android.documentsui, PID: 3358
E/AndroidRuntime( 3358): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3358): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 3358): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 3358): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 3358): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3358): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3358): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 3358): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3358): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 3358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 3358): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3358): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 3358): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3358): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3358): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3358): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3358): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 3358): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3358): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3358): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 3358): 	... 9 more
I/ActivityManager(  822): Killing 2873:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,D/OpenGLRenderer(  822): Enabling debug mode 0
,I/ActivityManager(  822): Start proc 3383:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop89.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  822): Killing 2740:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,W/OpenGLRenderer( 1308): Incorrectly called buildLayer on View: ew, destroying layer...
,D/ExternalStorage( 3383): After updating volumes, found 1 active roots
,W/ResourcesManager( 3047): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3047): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/HotwordDetector( 1531): Closing mic
I/MicrophoneInputStream( 1531): mic_close com.google.android.apps.gsa.speech.audio.u@2877287
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
,I/ActivityManager(  822): Killing 2906:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1531): Hotword detection finished
,D/Documents( 3358): Update found 7 roots in 448ms
,I/HotwordRecognitionRnr( 1531): Stopping hotword detection.
,E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1784): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/Icing   ( 1784): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1784): Could not init tag ds.tag.deleted
,E/SQLiteLog( 3211): (3850) statement aborts at 28: [UPDATE requests SET server_target_retry=?,server_fail_count=?,fail_count=? WHERE _id=?] disk I/O error
,E/Babel_Crash( 3211): Uncaught exception in background thread Thread[default_queue1,5,main]
E/Babel_Crash( 3211): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Babel_Crash( 3211): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/Babel_Crash( 3211): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/Babel_Crash( 3211): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/Babel_Crash( 3211): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/Babel_Crash( 3211): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/Babel_Crash( 3211): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/Babel_Crash( 3211): 	at dhe.a(SourceFile:3360)
E/Babel_Crash( 3211): 	at cap.d(SourceFile:393)
E/Babel_Crash( 3211): 	at caq.run(SourceFile:81)
,I/Icing   ( 1784): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/AndroidRuntime( 3211): FATAL EXCEPTION: default_queue1
E/AndroidRuntime( 3211): Process: com.google.android.talk, PID: 3211
E/AndroidRuntime( 3211): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3211): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3211): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 3211): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3211): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3211): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/AndroidRuntime( 3211): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/AndroidRuntime( 3211): 	at dhe.a(SourceFile:3360)
E/AndroidRuntime( 3211): 	at cap.d(SourceFile:393)
E/AndroidRuntime( 3211): 	at caq.run(SourceFile:81)
,E/SharedPreferencesImpl( 3211): Couldn't rename file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml to backup file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml.bak
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 1505): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1505): 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
E/SQLiteDatabase( 1505): 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
E/SQLiteDatabase( 1505): 	at com.google.android.gms.playlog.service.c.a(SourceFile:103)
E/SQLiteDatabase( 1505): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1505): 	at java.lang.Thread.run(Thread.java:818)
E/PlayLogIntentService( 1505): not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PlayLogIntentService( 1505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/PlayLogIntentService( 1505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 1505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelp,er.java:223)
E/PlayLogIntentService( 1505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PlayLogIntentService( 1505): 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
E/PlayLogIntentService( 1505): 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
E/PlayLogIntentService( 1505): 	at com.google.android.gms.playlog.service.c.a(SourceFile:103)
E/PlayLogIntentService( 1505): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/PlayLogIntentService( 1505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 1505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 1505): 	at java.lang.Thread.run(Thread.java:818)
E/Icing   ( 1784): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1784): Writing status failed
E/Icing   ( 1784): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/CheckinService( 1784): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{347c2ad3 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/ConfigService( 1505): onDestroy
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{2919abbe u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659360531
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  869): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  869): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  869): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  365): qmi_clnt_error_cb: with error -2 called for clnt FUSION
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  374): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  374): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
E/ThermalEngine(  365): modem_clnt_error_cb: with -2 called for clnt 0x6
D/        (  357): csd_client_error_cb: error -2 cb_data 0xb5474060
D/        (  357): csd_client_error_cb: MDM reset
,E/        (  357): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2,
E/        (  357): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb5
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb4
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb7
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb2
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb1
,I/ThermalEngine(  365): qmi: Instance id 157 for fusion TS

```
