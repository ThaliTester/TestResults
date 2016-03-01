#### Test 61248225a3bd1fe_thali05_htc-Nexus 9 Logs


```
--------- beginning of main
I/GAV2    ( 3068): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime( 3161): 
D/AndroidRuntime( 3161): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3161): CheckJNI is OFF
I/GAV2    ( 3090): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 3161): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  461): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3161): Shutting down VM
I/HotwordDetector(  972): Closing mic
I/MicrophoneInputStream(  972): mic_close com.google.android.apps.gsa.speech.audio.u@220a58a7
I/ActivityManager(  461): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3175 uid=10095 gids={50095, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SoundTriggerHwService::Module(  202): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr(  972): Stopping hotword detection.
I/HotwordRecognitionRnr(  972): Hotword detection finished
E/DataBuffer( 1272): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b19de30)
I/art     ( 1272): Explicit concurrent mark sweep GC freed 14423(773KB) AllocSpace objects, 4(80KB) LOS objects, 40% free, 11MB/19MB, paused 1.262ms total 50.487ms
I/ActivityManager(  461): Killing 1983:com.google.android.calendar/u0a31 (adj 15): empty #17
I/WebViewFactory( 3175): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
,I/ActivityManager(  461): Killing 2705:com.google.android.gms:car/u0a7 (adj 15): empty #18
,W/libprocessgroup(  461): failed to open /acct/uid_10031/pid_1983/cgroup.procs: No such file or directory
,W/libprocessgroup(  461): failed to open /acct/uid_10007/pid_2705/cgroup.procs: No such file or directory
,I/LibraryLoader( 3175): Time to load native libraries: 18 ms (timestamps 4703-4721)
,I/LibraryLoader( 3175): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3175): Binding Chromium to main looper Looper (main, tid 1) {2d40d01c}
I/LibraryLoader( 3175): Expected native library version number "",actual native library version number ""
,I/chromium( 3175): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3175): Initializing chromium process, singleProcess=true
,W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3175): ApplicationContext is null in ApplicationStatus
,W/chromium( 3175): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3175): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3175): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/BluetoothManagerService(  461): Message: 20
D/BluetoothManagerService(  461): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@325c4878:true
,D/BluetoothAdapter( 3175): 775325575: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3175): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3175): CordovaWebView is running on device made by: htc
,W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3175): Render dirty regions requested: true
,W/chromium( 3175): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3175): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3175): Enabling debug mode 0
,I/Keyboard.Facilitator(  841): onFinishInput()
,I/ActivityManager(  461): Displayed com.example.hello/.MainActivity: +1s21ms
,W/BindingManager( 3175): Cannot call determinedVisibility() - never saw a connection for the pid: 3175
,I/chromium( 3175): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 3175): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3175): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 3175): JniHelper::setJavaVM(0xab326290), pthread_self() = -1417842408
D/JX-Cordova( 3175): jxcore cordova android initializing
,W/jxcore-log( 3175): Initializing JXcore engine
W/jxcore-log( 3175): JXcore engine is ready
,W/jxcore-log( 3175): Starting JXcore engine
,W/m.example.hello( 3175): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[10111]" dev="sockfs" ino=10111 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3175): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1032 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 3175): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11487]" dev="sockfs" ino=11487 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3175): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21344]" dev="sockfs" ino=21344 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3175): Platform android
W/jxcore-log( 3175): 
W/jxcore-log( 3175): Process ARCH arm
W/jxcore-log( 3175): 
,I/jxcore-log( 3175): JXcore Cordova bridge is ready!
I/jxcore-log( 3175): 
W/jxcore-log( 3175): JXcore engine is started
,E/jxcore-log( 3175): >> htc-Nexus 9
E/jxcore-log( 3175): 
,I/jxcore-log( 3175): Total memory 1925128192
I/jxcore-log( 3175): 
I/jxcore-log( 3175): Free memory 125538304
I/jxcore-log( 3175): 
I/jxcore-log( 3175): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3175): 
I/jxcore-log( 3175): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): userPath [ 'www' ]
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Size 1536 1952
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Screen Brightness 171
I/jxcore-log( 3175): 
E/jxcore-log( 3175): Dummy Error Log.
E/jxcore-log( 3175): 
,I/jxcore-log( 3175): getBuffer is called!!!!
I/jxcore-log( 3175): 
,D/Finsky  ( 2802): [285] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2802): [285] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/BluetoothManagerService(  461): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  461): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  461): Message: 2
,D/WifiService(  461): setWifiEnabled: false pid=3175, uid=10095
E/WifiService(  461): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  461): New client listening to asynchronous messages
,I/jxcore-log( 3175): ****TEST TOOK:  5088  ms ****
I/jxcore-log( 3175): 
I/jxcore-log( 3175): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3175): 
E/WifiStateMachine(  461): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  461): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  198): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1066): Read error: ssl=0x5584f9e3a0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1066): SSL shutdown failed: ssl=0x5584f9e3a0: I/O error during system call, Broken pipe
,D/ConnectivityService(  461): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  461): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  461): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10007
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): ValidatedState{ when=0 what=532488 arg1=10007 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): DefaultState{ when=0 what=532488 arg1=10007 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  461): scanCount==0 - aborting
D/ConnectivityService(  461): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  461): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  461): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  461): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  636): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  461): Disconnected - quitting
I/ActivityManager(  461): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=3263 uid=10056 gids={50056, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/WifiScanningService(  461): SCAN_AVAILABLE : 1
D/RttService(  461): SCAN_AVAILABLE : 1
,D/RttService(  461): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  461): StartedState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  461): DefaultState
,D/WifiNetworkAgent(  461): NetworkAgent: NetworkAgent channel lost
,D/CommandListener(  198): Clearing all IP addresses on wlan0
,D/ConnectivityService(  461): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  461): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory(  930): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  461): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/wpa_supplicant(  706): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
W/ResourcesManager( 3263): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/wpa_supplicant(  706): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,D/AndroidRuntime( 3269): 
D/AndroidRuntime( 3269): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3269): CheckJNI is OFF
,I/Babel_SMS( 3263): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3263): MmsConfig.loadMmsSettings
I/Babel_SMS( 3263): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=, mUaProfUrl=
I/Babel_SMS( 3263): MmsConfig.loadFromDatabase
,I/Babel_SMS( 3263): ApnsOta: OTA version -1
,E/Babel_SMS( 3263): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3263): MmsConfig.loadFromResources
E/Babel_SMS( 3263): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3263): MmsConfig.loadMmsSettings: mUserAgent=Hangouts/4.0.100406486, mUaProfUrl=https://ssl.gstatic.com/android/hangouts/hangouts_mms_ua_profile.xml
,I/Babel   ( 3263): deleted: false for 0
,W/Settings( 3263): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3263): startup - clean
,I/wpa_supplicant(  706): wlan0: CTRL-EVENT-TERMINATING 
,D/AndroidRuntime( 3269): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  461): Force stopping com.example.hello appid=10095 user=-1: uninstall pkg
I/ActivityManager(  461): Killing 3175:com.example.hello/u0a95 (adj 0): stop com.example.hello
,I/WindowState(  461): WIN DEATH: Window{29aebfa8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  461): Client connection lost with reason: 4
,W/ActivityManager(  461): Force removing ActivityRecord{3c4d222e u0 com.example.hello/.MainActivity t29}: app died, no saved state
,W/ActivityManager(  461): Spurious death for ProcessRecord{1a2d84c 3175:com.example.hello/u0a95}, curProc for 3175: null
I/ActivityManager(  461): Force stopping com.example.hello appid=10095 user=0: pkg removed
,I/Keyboard.Facilitator(  841): resetDictionaries() : en_US
W/GeofencerStateMachine( 1272): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  461): Reconfiguring input devices.  changes=0x00000010
,W/Settings( 1272): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator.DecoderInitializer(  841): run()
,I/Decoder (  841): createOrResetDecoder
,I/art     (  461): Explicit concurrent mark sweep GC freed 24210(1401KB) AllocSpace objects, 4(100KB) LOS objects, 33% free, 19MB/29MB, paused 1.043ms total 96.590ms
,I/ConfigService( 1066): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader(  841): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader(  841): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5150672, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader(  841): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  841): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader(  841): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  841): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  841): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  841): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  841): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader(  841): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper(  841): run()
I/Keyboard.Facilitator.RecurringTaskScheduler(  841): run()
I/StatsUtilsManager(  841): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder(  841): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 2781): Cleaning up data for package: com.example.hello
,I/ActivityManager(  461): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3308 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
,W/VideoCapabilities( 3263): Unsupported mime video/mpeg2
W/AudioCapabilities( 3263): Unsupported mime audio/mpeg-L2
,D/BackupManagerService(  461): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  461): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  461): removeObsoleteFile: deleting file=29_task.xml
,W/InputMethodManagerService(  461): Got RemoteException sending setActive(false) notification to pid 3175 uid 10095
W/ContextImpl( 3308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator(  841): onFinishInput()
,W/VideoCapabilities( 3263): Unrecognized level 0 for video/x-vnd.on2.vp8
,W/LocationOracleImpl(  972): Best location was null
,E/NetworkScheduler.SchedulerReceiver( 1066): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1066): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/HotwordRecognitionRnr(  972): Starting hotword detection.
,I/MicrophoneInputStream(  972): mic_starting com.google.android.apps.gsa.speech.audio.u@1e8fc5e1
,I/SoundTriggerHwService::Module(  202): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/AudioFlinger(  202): AudioFlinger's thread 0xab7233c8 ready to run
,I/MicrophoneInputStream(  972): mic_started com.google.android.apps.gsa.speech.audio.u@1e8fc5e1
,W/GCoreFlp( 1272): No location to return for getLastLocation()
,D/PackageBroadcastService( 1207): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/ChimeraCfgMgr( 1207): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1207): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1207): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1207): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1207): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi(  972): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/Launcher(  950): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2e368787 new=com.google.android.velvet.VelvetApplication@2e368787
,I/LocationSettingsChecker( 1207): Removing dialog suppression flag for package com.example.hello
,I/HotwordWorker(  972): onReady
,I/art     (  207): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 104us total 8.576ms
,I/ActivityManager(  461): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3345 uid=10039 gids={50039, 9997} abi=arm64-v8a
,I/art     (  207): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 90us total 7.948ms
,I/art     (  207): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 190us total 13.370ms
,I/VideoCapabilities( 3263): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3263): Unrecognized level 0 for video/x-vnd.on2.vp8
,W/VideoCapabilities( 3263): Unrecognized level 0 for video/x-vnd.on2.vp8
,W/GCoreFlp( 1272): No location to return for getLastLocation()
,W/VideoCapabilities( 3263): Unrecognized level 0 for video/x-vnd.on2.vp8
,D/GOOGLEHELP_CompatibleDatabase( 1207): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1207): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1207): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1207): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ConfigFetchService( 1207): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GOOGLEHELP_CompatibleDatabase( 1207): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1207): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1207): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1207): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1207): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1207): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1207): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1207): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1207): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1207): Using Auth Proxy for data requests.
W/BaseAppContext( 1207): Using Auth Proxy for data requests.
,W/Settings( 3263): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/vclib   ( 3263): onServiceConnected
,W/Babel   ( 3263): Attempted to change video mute state without an active call.
,W/GCoreFlp( 1272): No location to return for getLastLocation()
,I/ConfigFetchService( 1207): service connected
,I/PeopleContactsSync( 1207): CP2 sync disabled
,I/art     (  461): Explicit concurrent mark sweep GC freed 11794(579KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.400ms total 551.925ms
,W/GCoreFlp( 1272): No location to return for getLastLocation()
,I/Icing   ( 1207): doRemovePackageData com.example.hello
,I/UpdateIcingCorporaServi(  972): UpdateCorporaTask done [took 308 ms] updated apps [took 307 ms] 
,I/ActivityManager(  461): Killing 2594:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,D/AndroidRuntime( 3269): Shutting down VM
,W/OpenGLRenderer(  950): Incorrectly called buildLayer on View: ew, destroying layer...
,W/libprocessgroup(  461): failed to open /acct/uid_10011/pid_2594/cgroup.procs: No such file or directory
,D/Launcher.Workspace(  950): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace(  950): 11683562 - stripEmptyScreens()
,I/ActivityManager(  461): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3368 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
,I/ActivityManager(  461): Killing 2681:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  461): failed to open /acct/uid_10002/pid_2681/cgroup.procs: No such file or directory
,D/ExternalStorage( 3368): After updating volumes, found 1 active roots
,W/ResourcesManager( 2933): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2933): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3345): Update found 7 roots in 265ms
,D/Documents( 3345): Update found 7 roots in 60ms
,E/native  (  841): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  841): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  (  841): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  841): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  (  841): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  841): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  841): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  841): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp

```
