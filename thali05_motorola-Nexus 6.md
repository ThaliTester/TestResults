#### Test 503880190437b9b_thali05_motorola-Nexus 6 Logs


```--------- beginning of main
11-17 18:01:34.378  1820  1820 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
11-17 18:01:34.426  1507  1522 I art     : Explicit concurrent mark sweep GC freed 32902(1914KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 25MB/41MB, paused 763us total 21.586ms
11-17 18:01:34.431  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
11-17 18:01:34.434  1507  1518 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
11-17 18:01:34.439  1507  1507 D a       : Opening database auth.proximity.permit_store...
11-17 18:01:34.443  1820  1820 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:01:34.483  1787  1787 E GmsWearableLS: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
11-17 18:01:34.488  1787  2086 E MDM     : [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
11-17 18:01:34.521  1820  2090 D LocationInitializer: Restart initialization of location
11-17 18:01:34.575  1507  2098 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
11-17 18:01:34.576  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
11-17 18:01:34.583  1820  1820 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:01:34.595  1787  2099 E MDM     : [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
11-17 18:01:34.597  1820  2100 D LocationInitializer: Restart initialization of location
11-17 18:01:34.610  1787  1787 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
--------- beginning of system
11-17 18:01:34.666   823  1303 I ActivityManager: Start proc 2105:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
11-17 18:01:34.942  2105  2105 I FitnessApp: Initializers took 15 milliseconds
11-17 18:01:34.971  1507  2124 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
11-17 18:01:34.974  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
11-17 18:01:34.978  1820  1820 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:01:34.987  1787  2125 E MDM     : [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
11-17 18:01:34.994  1820  2126 D LocationInitializer: Restart initialization of location
11-17 18:01:34.995  1507  2127 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
11-17 18:01:35.001  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
11-17 18:01:35.006  1820  1820 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:01:35.025  1787  2129 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
11-17 18:01:35.057   823  1501 I ActivityManager: Start proc 2131:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
11-17 18:01:35.058  1820  2130 D LocationInitializer: Restart initialization of location
11-17 18:01:35.424  1787  1787 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.android.location.internal.server.ACTION_RESTARTED}]
11-17 18:01:35.430  1787  1787 I GCoreUlr: DispatchingService.onCreate()
11-17 18:01:35.431   377   377 I ServiceManager: Waiting for service AtCmdFwd...
11-17 18:01:35.481   823  1227 I ActivityManager: Start proc 2157:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
11-17 18:01:35.503  1787  1817 I art     : Explicit concurrent mark sweep GC freed 52371(2MB) AllocSpace objects, 7(497KB) LOS objects, 37% free, 26MB/42MB, paused 657us total 27.268ms
11-17 18:01:35.506  2157  2157 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
11-17 18:01:35.521  1820  2155 I art     : Explicit concurrent mark sweep GC freed 58206(3MB) AllocSpace objects, 31(496KB) LOS objects, 37% free, 27MB/43MB, paused 764us total 81.313ms
11-17 18:01:35.532   823  1491 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@259b2df9}
11-17 18:01:35.555   823  1501 I ActivityManager: Start proc 2177:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
11-17 18:01:35.562   823  1371 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@259b2df9}
11-17 18:01:35.565  1787  2156 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.android.location.internal.server.ACTION_RESTARTED
11-17 18:01:35.595  1820  2196 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
11-17 18:01:35.595  1820  1820 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:01:35.595  1820  1820 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:01:35.628  1507  1525 I art     : Explicit concurrent mark sweep GC freed 17549(831KB) AllocSpace objects, 4(64KB) LOS objects, 38% free, 25MB/41MB, paused 824us total 24.529ms
11-17 18:01:35.645   823  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659798803
11-17 18:01:35.645   823  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
11-17 18:01:35.652  1820  1820 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
11-17 18:01:35.655  1820  1820 I ConfigFetchService: launchTask
11-17 18:01:35.662  1820  1820 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:01:35.662  1820  1820 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:01:35.665  1820  1820 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
11-17 18:01:35.667  1820  1820 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
11-17 18:01:35.667  1820  1820 D Vision  : Failed to find package metadata for com.example.hello
11-17 18:01:35.668  1820  1820 D Vision  : No vision deps
11-17 18:01:35.668  1820  1820 I ConfigFetchService: service connected
11-17 18:01:35.673  1820  1820 D ConfigFetchService: ConfigApi connection successful.
11-17 18:01:35.676  1820  2201 I PeopleContactsSync: CP2 sync disabled
11-17 18:01:35.683  1787  2156 I GCoreUlr: WorldUpdater:com.google.android.location.internal.server.ACTION_RESTARTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
11-17 18:01:35.686  1820  2200 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VJySshyHn1bDsKfyH8ZB6G6rYfVio6Pa7ovo1MEN8TQfpkWyZve8gkZTsj87g_-r_NkeuhPp6UFqyPrVpfxNtm-1zE1qsi85IKgh4_tvOQd9MleG0Wny6xAL-6dqRD7PodsD8y0zpjIPjv_t70GKjHMbxW9jM37Px3Wx36NSmssrf0oGS_0ZyypN7pOefUAEWzeUNrRqoHtBMlyXot2P99LbhuLRqairYhD2N1HkmeqMJcc8U
11-17 18:01:35.690  1820  2200 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-17 18:01:35.711   823  1303 I ActivityManager: Start proc 2208:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
11-17 18:01:35.730   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 8.841ms total 18.595ms
11-17 18:01:35.733  1530  2205 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
11-17 18:01:35.741   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 10.838ms
11-17 18:01:35.752   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 272us total 10.591ms
11-17 18:01:35.765  1820  2200 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
11-17 18:01:35.767  1820  1820 I ConfigFetchService: fetch service done; releasing wakelock
11-17 18:01:35.788   823  1352 I art     : Explicit concurrent mark sweep GC freed 14321(729KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 32MB/48MB, paused 1.214ms total 55.153ms
11-17 18:01:35.789  1820  1820 I ConfigFetchService: stopping self
11-17 18:01:35.795  1787  2156 I GCoreUlr: Unbound from all location providers
11-17 18:01:35.805  1530  2205 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 71 ms] updated apps [took 71 ms] 
11-17 18:01:35.811  1787  1787 I GCoreUlr: DispatchingService.onDestroy()
11-17 18:01:35.815  1787  1787 I GCoreUlr: Unbound from all location providers
11-17 18:01:35.822  1820  2202 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:01:35.829  1820  2202 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
11-17 18:01:35.836  1820  2202 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
11-17 18:01:35.841  1820  2202 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:01:35.877  1820  2202 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:01:35.895  1820  2202 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:01:35.900  1820  2202 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:01:35.918  1820  2202 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:01:36.417  2238  2238 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-17 18:01:36.419  2238  2238 D AndroidRuntime: CheckJNI is OFF
11-17 18:01:36.431   377   377 I ServiceManager: Waiting for service AtCmdFwd...
11-17 18:01:36.464  2208  2208 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
11-17 18:01:36.464  2208  2208 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-17 18:01:36.464  2208  2208 I GAv4    :   adb logcat -s GAv4
11-17 18:01:36.479  2208  2208 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
11-17 18:01:36.530  2238  2238 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:01:36.533   823   839 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:01:36.537   823   839 V WindowManager: addAppToken: AppWindowToken{f48b4c6 token=Token{392ebaa1 ActivityRecord{3d921308 u0 com.example.hello/.MainActivity t20}}} to stack=1 task=20 at 0
11-17 18:01:36.539  2238  2238 D AndroidRuntime: Shutting down VM
11-17 18:01:36.540  1530  1530 I HotwordDetector: Closing mic
11-17 18:01:36.541  1530  1851 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@351368ef
11-17 18:01:36.564  2208  2208 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
11-17 18:01:36.569  2208  2258 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
11-17 18:01:36.571   823  1303 I ActivityManager: Start proc 2259:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
11-17 18:01:36.585  2208  2208 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
11-17 18:01:36.603   360  1857 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-17 18:01:36.604   360  1857 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
11-17 18:01:36.608   360  1020 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-17 18:01:36.610  1530  1852 I HotwordRecognitionRnr: Stopping hotword detection.
11-17 18:01:36.612  1530  1854 I HotwordRecognitionRnr: Hotword detection finished
11-17 18:01:36.623  1787  1839 W GCoreFlp: No location to return for getLastLocation()
11-17 18:01:36.651  2259  2259 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
11-17 18:01:36.661  2259  2259 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1248-1249)
11-17 18:01:36.661  2259  2259 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:36.672  2259  2259 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d404f23}
11-17 18:01:36.673  2259  2259 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:36.673  2259  2259 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:01:36.682  2259  2259 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-17 18:01:36.682  2259  2259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:36.683  2259  2259 E SysUtils: ApplicationContext is null in ApplicationStatus
11-17 18:01:36.689  2259  2283 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
11-17 18:01:36.694  2259  2259 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-17 18:01:36.696   823  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659798803
11-17 18:01:36.696   823  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
11-17 18:01:36.699  2259  2259 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:01:36.699  2259  2259 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:01:36.699  2259  2259 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
11-17 18:01:36.708  2208  2290 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:01:36.709  2208  2290 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
11-17 18:01:36.728   823  1491 I ActivityManager: Start proc 2291:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
11-17 18:01:36.748   823   861 D BluetoothManagerService: Message: 20
11-17 18:01:36.748   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bee7eaa:true
11-17 18:01:36.749  2259  2315 D BluetoothAdapter: 37898828: getState() :  mService = null. Returning STATE_OFF
,11-17 18:01:36.773  2208  2290 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,11-17 18:01:36.778  2259  2259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:01:36.794  2259  2259 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-17 18:01:36.804  2259  2259 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,11-17 18:01:36.808  2208  2290 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-17 18:01:36.809  2259  2259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:36.809  2259  2259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:01:36.821  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:36.848  2259  2328 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-17 18:01:36.851  2259  2259 D Atlas   : Validating map...
,11-17 18:01:36.855   823  1501 V WindowManager: Adding window Window{3820e26 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 8 (after Window{3f57640a u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
,11-17 18:01:36.857  2259  2312 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-17 18:01:36.878  2259  2328 I OpenGLRenderer: Initialized EGL, version 1.4
,11-17 18:01:36.887  2259  2328 D OpenGLRenderer: Enabling debug mode 0
,11-17 18:01:36.919   823   862 I ActivityManager: Displayed com.example.hello/.MainActivity: +380ms (total +8s685ms)
,11-17 18:01:36.921  1218  1218 I Keyboard.Facilitator: onFinishInput()
,11-17 18:01:36.953  2259  2259 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2259
,11-17 18:01:36.973  2259  2259 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,--------- beginning of crash
11-17 18:01:37.018   328   331 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x0 in tid 331 (BootAnimation)
,11-17 18:01:37.059  2259  2259 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 18:01:37.069   357   357 E DEBUG   : unexpected waitpid response: n=331, status=00000000
11-17 18:01:37.069   357   357 E DEBUG   : tid exited before attach completed: tid 331
,11-17 18:01:37.075  2259  2320 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:01:37.134   823   862 I SystemServiceManager: Starting phase 1000
,11-17 18:01:37.192  2259  2329 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576513920
,11-17 18:01:37.192  2259  2329 D JX-Cordova: jxcore cordova android initializing
,11-17 18:01:37.258  2291  2291 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,11-17 18:01:37.274  2259  2259 W jxcore-log: Initializing JXcore engine
11-17 18:01:37.274  2259  2259 W jxcore-log: JXcore engine is ready
,11-17 18:01:37.277  2259  2259 W jxcore-log: Starting JXcore engine
,11-17 18:01:37.323  2291  2291 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,11-17 18:01:37.320  2259  2259 W m.example.hello: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10595]" dev="sockfs" ino=10595 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 18:01:37.330  2259  2259 W m.example.hello: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-17 18:01:37.330  2259  2259 W m.example.hello: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13069]" dev="sockfs" ino=13069 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 18:01:37.330  2259  2259 W m.example.hello: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[17843]" dev="sockfs" ino=17843 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 18:01:37.379   823  1100 I ActivityManager: Start proc 2354:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,11-17 18:01:37.407  2354  2354 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:01:37.407  2354  2354 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:01:37.412  2291  2291 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:01:37.413  2291  2291 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:01:37.432   377   377 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 18:01:37.437  2354  2354 I MultiDex: VM with version 2.1.0 has multidex support
11-17 18:01:37.437  2354  2354 I MultiDex: install
11-17 18:01:37.437  2354  2354 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,11-17 18:01:37.449  2259  2259 W jxcore-log: Platform android
11-17 18:01:37.449  2259  2259 W jxcore-log: 
11-17 18:01:37.449  2259  2259 W jxcore-log: Process ARCH arm
11-17 18:01:37.449  2259  2259 W jxcore-log: 
,11-17 18:01:37.475   823  1501 I ActivityManager: Start proc 2375:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,11-17 18:01:37.481  2291  2291 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,11-17 18:01:37.481  2291  2291 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,11-17 18:01:37.486  2259  2259 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:01:37.486  2259  2259 I jxcore-log: 
11-17 18:01:37.486  2259  2259 W jxcore-log: JXcore engine is started
,11-17 18:01:37.491  2354  2354 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,11-17 18:01:37.493  2291  2291 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,11-17 18:01:37.498  2375  2375 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:01:37.505  2291  2291 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,11-17 18:01:37.519  2259  2259 E jxcore-log: >> motorola-Nexus 6
11-17 18:01:37.519  2259  2259 E jxcore-log: 
11-17 18:01:37.520  2259  2259 I jxcore-log: Total memory 3113791488
11-17 18:01:37.520  2259  2259 I jxcore-log: 
,11-17 18:01:37.520  2259  2259 I jxcore-log: Free memory 1219252224
11-17 18:01:37.520  2259  2259 I jxcore-log: 
,11-17 18:01:37.521  2259  2259 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:01:37.521  2259  2259 I jxcore-log: 
11-17 18:01:37.521  2259  2259 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:01:37.521  2259  2259 I jxcore-log: 
11-17 18:01:37.525  2259  2259 I jxcore-log: userPath [ 'www' ]
11-17 18:01:37.525  2259  2259 I jxcore-log: 
,11-17 18:01:37.526  2259  2259 I jxcore-log: Size 1440 2392
11-17 18:01:37.526  2259  2259 I jxcore-log: 
,11-17 18:01:37.528  2259  2259 I jxcore-log: Screen Brightness 82
11-17 18:01:37.528  2259  2259 I jxcore-log: 
11-17 18:01:37.528  2259  2259 E jxcore-log: Dummy Error Log.
11-17 18:01:37.528  2259  2259 E jxcore-log: 
,11-17 18:01:37.546  2354  2354 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-17 18:01:37.711  2291  2291 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,11-17 18:01:38.041  2259  2259 I jxcore-log: getBuffer is called!!!!
11-17 18:01:38.041  2259  2259 I jxcore-log: 
,11-17 18:01:38.136   823  1501 I ActivityManager: Start proc 2408:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,11-17 18:01:38.160  2408  2408 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,11-17 18:01:38.433   377   377 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 18:01:38.661  2408  2431 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
11-17 18:01:38.661  2408  2431 I Babel_SMS: MmsConfig.loadMmsSettings
,11-17 18:01:38.665  2408  2431 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
11-17 18:01:38.665  2408  2431 I Babel_SMS: MmsConfig.loadFromDatabase
,11-17 18:01:38.680  2408  2431 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,11-17 18:01:38.680  2408  2431 I Babel_SMS: MmsConfig.loadFromResources
11-17 18:01:38.682  2408  2431 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
11-17 18:01:38.682  2408  2431 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,11-17 18:01:38.726  2408  2408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:01:38.729  2408  2408 I Babel_Crash: startup - clean
,11-17 18:01:38.779  2408  2434 I Babel   : deleted: false for 0
,11-17 18:01:38.854  2408  2408 I Babel_telephony: TeleModule.launchCompleted
,11-17 18:01:38.857   823  1371 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,11-17 18:01:38.859  2408  2408 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
11-17 18:01:38.859  2408  2408 W Babel   : BAM#gBA: invalid account id: -1
11-17 18:01:38.859  2408  2408 W Babel   : BAM#gBA: invalid account id: -1
11-17 18:01:38.859  2408  2408 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
11-17 18:01:38.860   823  1303 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,11-17 18:01:38.907  2408  2408 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:38.909   823  2438 I ActivityManager: Start proc 2440:com.android.keychain/1000 for service com.android.keychain/.KeyChainService
,11-17 18:01:38.920   823  2457 I RecoverySystem: No recovery log file
,11-17 18:01:38.943  2408  2408 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,11-17 18:01:38.952  2408  2408 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:38.953   823  1227 I ActivityManager: Start proc 2462:com.google.android.dialer/u0a13 for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver
,11-17 18:01:38.964  2408  2408 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:38.967  2408  2408 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:38.970  2408  2408 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:38.980   823  2457 I BootReceiver: Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
,11-17 18:01:39.006   823  2457 I BootReceiver: Copying audit failures to DropBox
11-17 18:01:39.006   823   838 I art     : Explicit concurrent mark sweep GC freed 17639(937KB) AllocSpace objects, 8(625KB) LOS objects, 32% free, 33MB/49MB, paused 1.216ms total 50.070ms
,11-17 18:01:39.014   823  1491 I ActivityManager: Killing 1458:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,11-17 18:01:39.015   823  2457 I BootReceiver: Copied 2621 worth of audits to DropBox
,11-17 18:01:39.019   823  2457 I BootReceiver: Checking for fsck errors
,11-17 18:01:39.023  2462  2462 W ResourcesManager: Asset path '/system/framework/com.google.android.dialer.support.jar' does not exist or contains no resources.
,11-17 18:01:39.122  2408  2408 I vclib   : onServiceConnected
,11-17 18:01:39.122  2408  2408 W Babel   : Attempted to change video mute state without an active call.
,11-17 18:01:39.137   823  1303 I ActivityManager: Killing 1910:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,11-17 18:01:39.290   823  1027 D WIFI    : Registering NetworkFactory
11-17 18:01:39.291   823  1027 D WIFI_UT : Registering NetworkFactory
11-17 18:01:39.291   823  1029 D ConnectivityService: Got NetworkFactory Messenger for WIFI
11-17 18:01:39.291   823  1029 D ConnectivityService: Got NetworkFactory Messenger for WIFI_UT
11-17 18:01:39.291   823  1027 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
11-17 18:01:39.291   823  1027 D WIFI_UT : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,11-17 18:01:39.315   823   823 I ActivityManager: Start proc 2487:com.motorola.motocit/u0a2 for broadcast com.motorola.motocit/.CQATestBootReceiver
,11-17 18:01:39.321  2291  2291 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,11-17 18:01:39.329  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:39.352  1507  1507 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
11-17 18:01:39.352  1507  1507 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,11-17 18:01:39.368  1507  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
11-17 18:01:39.368  1507  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,11-17 18:01:39.369  1507  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
,11-17 18:01:39.373  1507  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,11-17 18:01:39.376  1507  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:39.429   823   839 I ActivityManager: Start proc 2504:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarReceiver
,11-17 18:01:39.433   377   377 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 18:01:39.434  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:39.451  1507  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
11-17 18:01:39.451  1507  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
11-17 18:01:39.451  1507  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
11-17 18:01:39.451  1507  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,11-17 18:01:39.455  1507  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:39.462  2504  2504 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:01:39.465  2291  2291 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,11-17 18:01:39.501  2504  2504 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@9c70052(com.android.providers.calendar.CalendarProvider2@1d404f23)
,11-17 18:01:39.543   823  1303 I ActivityManager: Start proc 2526:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.BootCompletedReceiver
,11-17 18:01:39.606  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:39.624  1507  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
11-17 18:01:39.624  1507  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
11-17 18:01:39.624  1507  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
11-17 18:01:39.624  1507  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,11-17 18:01:39.627  1507  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:39.660  1507  1748 I art     : Explicit concurrent mark sweep GC freed 15010(815KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.090ms total 21.682ms
,11-17 18:01:39.666  2291  2291 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,11-17 18:01:39.668  2291  2291 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,11-17 18:01:39.674  2291  2291 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,11-17 18:01:39.677  2291  2291 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,11-17 18:01:39.682  1787  1833 D DeviceConnectionService: client connected with version: 7571000
,11-17 18:01:39.684   823   838 I ActivityManager: Killing 2004:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-17 18:01:39.788   823   838 I ActivityManager: Killing 2041:com.android.cellbroadcastreceiver/u0a4 (adj 15): empty #18
,11-17 18:01:40.031   823   838 I ActivityManager: Start proc 2555:com.google.android.onetimeinitializer/u0a15 for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,11-17 18:01:40.033   823   838 I ActivityManager: Killing 2023:com.verizon.omadm/u0a93 (adj 15): empty #17
,11-17 18:01:40.049   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 337us total 16.640ms
,11-17 18:01:40.064   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 335us total 14.782ms
,11-17 18:01:40.080   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 332us total 14.778ms
,11-17 18:01:40.149   823  1501 I ActivityManager: Killing 1373:com.android.printspooler/u0a81 (adj 15): empty #17
,11-17 18:01:40.188  2555  2555 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,11-17 18:01:40.277  2555  2572 V OneTimeService: OneTimeService.onHandleIntent
,11-17 18:01:40.403   823   839 I ActivityManager: Start proc 2579:com.android.managedprovisioning/u0a17 for broadcast com.android.managedprovisioning/.BootReminder
,11-17 18:01:40.433   377   377 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-17 18:01:40.477  1604  1604 I RlzPingService: Setting next ping for 1448384500476
,11-17 18:01:40.507   823  1352 I ActivityManager: Killing 2105:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,11-17 18:01:40.552  2504  2504 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
11-17 18:01:40.552  2504  2504 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,11-17 18:01:40.639   823  1303 I ActivityManager: Killing 2131:com.google.android.keep/u0a79 (adj 15): empty #17
,11-17 18:01:40.854   823  1303 I ActivityManager: Killing 2177:com.android.musicfx/u0a18 (adj 15): empty #17
,11-17 18:01:40.971  1507  1507 I ConfigService: onDestroy
,11-17 18:01:41.020  1091  2599 E SQLiteLog: (283) recovered 135 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,11-17 18:01:41.029   823  1303 I ActivityManager: Start proc 2601:com.android.settings/1000 for broadcast com.android.settings/.sim.SimBootReceiver
,11-17 18:01:41.032  1091  1091 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,11-17 18:01:41.068   823  1100 I ActivityManager: Killing 2208:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,11-17 18:01:41.110  1091  2599 W MediaScanner: Error opening directory '/oem/media/', skipping: Permission denied.
,11-17 18:01:41.228   823   838 I ActivityManager: Start proc 2619:org.simalliance.openmobileapi.service/u0a23 for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver
,11-17 18:01:41.229   823   838 I ActivityManager: Killing 1530:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,11-17 18:01:41.353  2619  2619 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,11-17 18:01:41.381  2619  2619 V SmartcardService: main Received broadcast
11-17 18:01:41.381  2619  2619 V SmartcardService: Starting smartcard service after boot completed
,11-17 18:01:41.440   823  1227 I art     : Explicit concurrent mark sweep GC freed 13558(752KB) AllocSpace objects, 10(801KB) LOS objects, 32% free, 32MB/48MB, paused 1.413ms total 74.261ms
,11-17 18:01:41.446   823  1100 I ActivityManager: Start proc 2638:org.simalliance.openmobileapi.service:remote/u0a23 for service org.simalliance.openmobileapi.service/.SmartcardService
,11-17 18:01:41.487   823  1303 I ActivityManager: Start proc 2656:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,11-17 18:01:41.496  2638  2638 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,11-17 18:01:41.524   823   838 I ActivityManager: Killing 2375:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,11-17 18:01:41.528  1820  2636 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,11-17 18:01:41.529  2638  2638 V SmartcardService: main smartcard service onCreate
,11-17 18:01:41.551  2638  2638 V SmartcardService: main adding SIM - UICC
,11-17 18:01:41.573  2638  2675 I SmartcardService: Initializing Access Control
,11-17 18:01:41.576  2638  2675 I SmartcardService: NOT initializing Access Control for SIM - UICC SE not present.
,11-17 18:01:41.576  2638  2638 I SmartcardService: OnPostExecute()
11-17 18:01:41.576  2638  2638 V SmartcardService: register SIM_STATE_CHANGED event
,11-17 18:01:41.578  2638  2638 V SmartcardService: register ADAPTER_STATE_CHANGED event
,11-17 18:01:41.579  2638  2638 V SmartcardService: register MEDIA_MOUNTED event
,11-17 18:01:41.602  1820  2636 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 74 ms
,11-17 18:01:41.605   823  1371 I ActivityManager: Killing 2408:com.google.android.talk/u0a61 (adj 15): empty #17
,11-17 18:01:41.636  1091  2599 V MediaScanner: pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@12de7c
,11-17 18:01:41.637  1091  2599 V MediaScanner: /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@12de7c
,11-17 18:01:41.730  2656  2656 E SQLiteLog: (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,11-17 18:01:41.916   823   838 I ActivityManager: Start proc 2683:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,11-17 18:01:41.956  2656  2656 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,11-17 18:01:42.213  2683  2683 E UpdateRequestReceiver: ignoring update request
,11-17 18:01:42.259  2683  2683 E UpdateRequestReceiver: ignoring update request
,11-17 18:01:42.296  2683  2683 E UpdateRequestReceiver: ignoring update request
,11-17 18:01:42.307  2683  2683 E UpdateRequestReceiver: ignoring update request
,11-17 18:01:42.318  2683  2683 E UpdateRequestReceiver: ignoring update request
,11-17 18:01:42.326  2683  2683 E UpdateRequestReceiver: ignoring update request
,11-17 18:01:42.327   823  1303 I ActivityManager: Killing 2440:com.android.keychain/1000 (adj 15): empty #17
,11-17 18:01:42.539   823  1501 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
11-17 18:01:42.539   823  1501 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
11-17 18:01:42.540   823   861 D BluetoothManagerService: Message: 2,
,11-17 18:01:42.556   823  1491 D WifiService: setWifiEnabled: false pid=2259, uid=10272
,11-17 18:01:42.556   823  1491 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 18:01:42.556   823  1028 D WifiService: New client listening to asynchronous messages
,11-17 18:01:42.559  2259  2259 I jxcore-log: ****TEST TOOK:  5044  ms ****
11-17 18:01:42.559  2259  2259 I jxcore-log: 
,11-17 18:01:42.562  2259  2259 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:01:42.562  2259  2259 I jxcore-log: 
,11-17 18:01:42.564  1507  2716 I GoogleHttpClient: GMS http client unavailable, use old client
,11-17 18:01:42.608   823  1100 I ActivityManager: Start proc 2718:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-17 18:01:42.841  2733  2733 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-17 18:01:42.844  2733  2733 D AndroidRuntime: CheckJNI is OFF
,11-17 18:01:42.959  2733  2733 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:01:42.966   823   857 I ActivityManager: Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
,11-17 18:01:42.967   823   857 I ActivityManager: Killing 2259:com.example.hello/u0a272 (adj 0): stop com.example.hello
,11-17 18:01:43.007   823   867 W PackageSettings: Skipping PackageSetting{1f24286e com.test.thalitest/10265} due to missing metadata
,11-17 18:01:43.037  2718  2718 D StrictMode: StrictMode policy violation; ~duration=327 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.io.File.doAccess(File.java:283)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.io.File.exists(File.java:363)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.037  2718  2718 D StrictMode: StrictMode policy violation; ~duration=327 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.io.File.doAccess(File.java:283)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.io.File.exists(File.java:363)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.037  2718  2718 D StrictMode: StrictMode policy violation; ~duration=323 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.System.loadLibrary(System.java:988)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.037  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.038  2718  2718 D StrictMode: StrictMode policy violation; ~duration=317 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.038  2718  2718 D StrictMode: StrictMode policy violation; ~duration=258 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.System.loadLibrary(System.java:988)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.038  2718  2718 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Binder.execTransact(Binder.java:446)
11-17 18:01:43.038  2718  2718 D StrictMode: # via Binder call with stack:
11-17 18:01:43.038  2718  2718 D StrictMode: android.os.StrictMode$LogStackTrace
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.content.ContentResolver.query(ContentResolver.java:478)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.content.ContentResolver.query(ContentResolver.java:422)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.c.c.a(PG:87)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.c.c.a(PG:107)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.b.a.by.a(PG:125)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.038  2718  2718 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.io.File.doAccess(File.java:283)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.io.File.exists(File.java:363)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.038  2718  2718 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.038  2718  2718 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.038  2718  2718 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.p.j.c(PG:1152)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.p.j.a(PG:121)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.t.b.a.dr.<init>(PG:24)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.t.b.a.ds.a(PG:61)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.p.e.a(PG:170)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.p.e.b(PG:21)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.038  2718  2718 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,11-17 18:01:43.070  2718  2718 W com.google.a.a.a.b.a: Application name is not set. Call Builder#setApplicationName.
,11-17 18:01:43.126   823  1028 D WifiService: Client connection lost with reason: 4
11-17 18:01:43.126   823  1371 I WindowState: WIN DEATH: Window{3820e26 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:01:43.175   823   857 W ActivityManager: Force removing ActivityRecord{3d921308 u0 com.example.hello/.MainActivity t20}: app died, no saved state
,11-17 18:01:43.185   823   867 I ActivityManager: Force stopping com.example.hello appid=10272 user=0: pkg removed
,11-17 18:01:43.193   823  1303 W ActivityManager: Spurious death for ProcessRecord{292100a9 2259:com.example.hello/u0a272}, curProc for 2259: null
,11-17 18:01:43.194   823  1049 D TaskPersister: removeObsoleteFile: deleting file=20_task.xml
,11-17 18:01:43.202  1218  1218 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-17 18:01:43.207  1218  2754 I Keyboard.Facilitator.DecoderInitializer: run()
,11-17 18:01:43.210   823  1005 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:01:43.212   823   861 D BluetoothManagerService: Message: 20
11-17 18:01:43.212   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a5abb5c:true
,11-17 18:01:43.223  1218  2754 I Decoder : createOrResetDecoder
,11-17 18:01:43.251   823  1352 I ActivityManager: Start proc 2755:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,11-17 18:01:43.252   823  1352 I ActivityManager: Killing 2462:com.google.android.dialer/u0a13 (adj 15): empty #17
,11-17 18:01:43.261  1069  1069 I art     : Explicit concurrent mark sweep GC freed 35537(1448KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 1.480ms total 57.764ms
,11-17 18:01:43.295   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:01:43.295   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:01:43.312  1507  1507 I ConfigService: onCreate
,11-17 18:01:43.316   823   867 I art     : Explicit concurrent mark sweep GC freed 11876(897KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 32MB/48MB, paused 1.433ms total 117.127ms
,11-17 18:01:43.334  1218  2754 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-17 18:01:43.348  2733  2733 I art     : System.exit called, status: 0
11-17 18:01:43.348  2733  2733 I AndroidRuntime: VM exiting with result code 0.
11-17 18:01:43.353   823  1227 I ActivityManager: Start proc 2775:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
11-17 18:01:43.355   823  1501 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 2259 uid 10272
11-17 18:01:43.356  1218  1218 I Keyboard.Facilitator: onFinishInput()
,11-17 18:01:43.369  1218  2754 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,11-17 18:01:43.370  1218  2754 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-17 18:01:43.370  1218  2754 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-17 18:01:43.381  1218  2754 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-17 18:01:43.381  1218  2754 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-17 18:01:43.382  1218  2754 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-17 18:01:43.382  1218  2754 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,11-17 18:01:43.385  1218  2754 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-17 18:01:43.385  1218  2754 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit),
11-17 18:01:43.385  1218  2754 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-17 18:01:43.385  1218  2754 I Keyboard.Facilitator.RecurringTaskScheduler: run(),
11-17 18:01:43.385  1218  2754 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-17 18:01:43.385  1218  2754 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-17 18:01:43.386  1340  1340 D Launcher.Workspace: 11683562 - stripEmptyScreens()
11-17 18:01:43.386  1340  1340 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,11-17 18:01:43.522  1507  1701 I art     : Explicit concurrent mark sweep GC freed 5763(279KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 813us total 21.261ms
,11-17 18:01:43.580  2755  2806 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:01:43.587  2755  2806 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #2
11-17 18:01:43.587  2755  2806 E AndroidRuntime: Process: com.google.android.keep, PID: 2755
11-17 18:01:43.587  2755  2806 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at com.android.common.content.SQLiteContentProvider.update(SourceFile:153)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1333)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at com.google.android.keep.task.o.doInBackground(SourceFile:106)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at com.google.android.keep.task.o.doInBackground(SourceFile:69)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:01:43.587  2755  2806 E AndroidRuntime: 	... 4 more
,11-17 18:01:43.598  2755  2808 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:01:43.612   823  2813 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:01:43.612   823  2813 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop84.tmp: open failed: EROFS (Read-only file system)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:43.612   823  2813 E DropBoxManagerService: 	... 5 more
,11-17 18:01:43.637   823  2815 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-17 18:01:43.638   823   857 D Atlas   : Validating map...
,11-17 18:01:43.643  2755  2811 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:01:43.645  2755  2811 I Process : Sending signal. PID: 2755 SIG: 9
,11-17 18:01:43.667   823  2815 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,11-17 18:01:43.674   823  1100 I ActivityManager: Start proc 2817:com.qualcomm.telephony/1000 for broadcast com.qualcomm.atfwd/.AtFwdAutoboot
,11-17 18:01:43.676   823  2815 I OpenGLRenderer: Initialized EGL, version 1.4
,11-17 18:01:43.683   823  2815 D OpenGLRenderer: Enabling debug mode 0
,11-17 18:01:43.688   823   838 I ActivityManager: Process com.google.android.keep (pid 2755) has died
11-17 18:01:43.688   823   838 W ActivityManager: Scheduling restart of crashed service com.google.android.keep/.notification.AlertService in 1000ms
11-17 18:01:43.688   823   838 W ActivityManager: Scheduling restart of crashed service com.google.android.keep/.sharing.SharingNotificationService in 11000ms
,11-17 18:01:43.720  2817  2817 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2609 
,11-17 18:01:43.725  2817  2817 E AtFwd AutoBoot: AtFwd Auto Boot Started Successfully
,11-17 18:01:43.727  2817  2817 D AtFwdService: onCreate method
11-17 18:01:43.727  2817  2817 I AtFwdService: Instantiate AtCmdFwd Service
,11-17 18:01:43.728  2775  2775 D AndroidRuntime: Shutting down VM
,11-17 18:01:43.741  2817  2845 D AtCkpdCmdHandler: De-queing command
,11-17 18:01:43.747   823   838 I ActivityManager: Start proc 2847:com.qualcomm.telephony/1001 for broadcast org.codeaurora.ims/.ImsServiceAutoboot
,11-17 18:01:43.756   371   371 I art     : Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 227us total 9.693ms
,11-17 18:01:43.767   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 223us total 9.012ms
,11-17 18:01:43.776   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.574ms
,11-17 18:01:43.794   823   839 I ActivityManager: Start proc 2864:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-17 18:01:43.800  2775  2775 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,11-17 18:01:43.800  2775  2775 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:01:43.800  2775  2775 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2775
11-17 18:01:43.800  2775  2775 E AndroidRuntime: java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.search.core.bh$2.onFailure(SearchController.java:381)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.a.r$1.run(TaskRunnerImpl.java:329)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.d$1.call(LazyListenableFuture.java:46)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	... 5 more
11-17 18:01:43.800  2775  2775 E AndroidRuntime: Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:941)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
11-17 18:01:43.8,00  2775  2775 E AndroidRuntime: 	... 9 more
11-17 18:01:43.800  2775  2775 E AndroidRuntime: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:934)
11-17 18:01:43.800  2775  2775 E AndroidRuntime: 	... 11 more
11-17 18:01:43.805   823  2875 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:01:43.805   823  2875 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:43.805   823  2875 E DropBoxManagerService: 	... 5 more
,11-17 18:01:43.848  2847  2847 E ImsService AutoBoot: ImsService Auto Boot Started Successfully
,11-17 18:01:43.855  1287  1287 D ImsService: ImsService created!
,11-17 18:01:43.861   823   838 I ActivityManager: Killing 2354:com.google.android.gms:car/u0a11 (adj 15): empty #17
,11-17 18:01:43.867  1287  1287 D ImsSenderRxr: Starting IFMsg_Rxr
,11-17 18:01:43.871  1287  1287 D ImsConfigImpl: ImsConfigImpl Creates
11-17 18:01:43.872  1340  1648 W OpenGLRenderer: Incorrectly called buildLayer on View: ew, destroying layer...
,11-17 18:01:43.874   823  1371 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@38a089a4 attribute=null, token = android.os.BinderProxy@3a75ec4d
,11-17 18:01:43.880  1287  2884 D ImsSenderRxr: Connecting to socket android.net.LocalSocket@2ccd752f impl:android.net.LocalSocketImpl@3e89673c fd:FileDescriptor[68]
11-17 18:01:43.881  1287  2884 I ImsSenderRxr: Connected to 'android.net.LocalSocket@2ccd752f impl:android.net.LocalSocketImpl@3e89673c fd:FileDescriptor[68]' socket
11-17 18:01:43.881  1287  2884 V ImsSenderRxr: Read packet: 15 bytes
11-17 18:01:43.881  1287  2884 V ImsSenderRxr: processResponse
11-17 18:01:43.881  1287  2884 D ImsSenderRxr: Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
11-17 18:01:43.882  1287  2884 D ImsSenderRxr:  Tag -1 3 213 0
,11-17 18:01:43.885   260   260 E qdoverlay: Bad ov dump:  mdp_overlay z=3 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:01:43.885   260   260 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
11-17 18:01:43.885   260   260 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: Bad ov dump:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:01:43.885   260   260 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
11-17 18:01:43.885   260   260 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:01:43.885   260   260 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
11-17 18:01:43.885   260   260 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:01:43.885   260   260 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
11-17 18:01:43.885   260   260 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
11-17 18:01:43.885   260   260 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
11-17 18:01:43.885   260   260 E qdoverlay: MdpCtrl close error in unset
,11-17 18:01:43.980  1287  1287 D ImsConfigImpl: mcc = 0, mnc = 0
,11-17 18:01:43.981  1287  1287 D ImsSenderRxr: [0000]> REQUEST_QUERY_SERVICE_STATUS
11-17 18:01:43.981  1287  1287 D ImsSenderRxr: Message data: [0, 0, 0, 12, 11, 13, 0, 0, 0, 0, 16, 1, 24, 29, 32, 0],
,11-17 18:01:43.984  1287  2884 V ImsSenderRxr: Read packet: 12 bytes
11-17 18:01:43.984  1287  2884 V ImsSenderRxr: processResponse
11-17 18:01:43.984  1287  2884 D ImsSenderRxr: Response data: [11, 13, 0, 0, 0, 0, 16, 2, 24, 29, 32, 2]
,11-17 18:01:43.984  1287  2884 D ImsSenderRxr:  Tag 0 2 29 2
11-17 18:01:43.984  1287  2884 D ImsSenderRxr: [0000]< REQUEST_QUERY_SERVICE_STATUS error: 2
```
