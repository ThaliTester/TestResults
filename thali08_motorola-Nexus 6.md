#### Test 62548124e8057a0_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
03-21 14:21:43.118  2476  2476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2609 
--------- beginning of main
03-21 14:21:43.120  2476  2476 E AtFwd AutoBoot: AtFwd Auto Boot Started Successfully
03-21 14:21:43.121  2476  2476 D AtFwdService: onCreate method
03-21 14:21:43.122  2476  2476 I AtFwdService: Instantiate AtCmdFwd Service
03-21 14:21:43.126  2476  2496 D AtCkpdCmdHandler: De-queing command
03-21 14:21:43.153   820   836 I ActivityManager: Start proc 2498:com.qualcomm.telephony/1001 for broadcast org.codeaurora.ims/.ImsServiceAutoboot
03-21 14:21:43.156   820  1292 I ActivityManager: Killing 1956:com.verizon.omadm/u0a93 (adj 15): empty #17
,03-21 14:21:43.225   375   375 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
03-21 14:21:43.333  2498  2498 E ImsService AutoBoot: ImsService Auto Boot Started Successfully
03-21 14:21:43.334   820  1288 I ActivityManager: Killing 2088:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
03-21 14:21:43.350  1294  1294 D ImsService: ImsService created!
03-21 14:21:43.366  1294  1294 D ImsSenderRxr: Starting IFMsg_Rxr
03-21 14:21:43.368  1294  2521 D ImsSenderRxr: Connecting to socket android.net.LocalSocket@f51073 impl:android.net.LocalSocketImpl@3f4d3b30 fd:FileDescriptor[65]
03-21 14:21:43.369  1294  2521 I ImsSenderRxr: Connected to 'android.net.LocalSocket@f51073 impl:android.net.LocalSocketImpl@3f4d3b30 fd:FileDescriptor[65]' socket
03-21 14:21:43.369  1294  2521 V ImsSenderRxr: Read packet: 15 bytes
03-21 14:21:43.369  1294  2521 V ImsSenderRxr: processResponse
03-21 14:21:43.369  1294  2521 D ImsSenderRxr: Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
03-21 14:21:43.370  1294  2521 D ImsSenderRxr:  Tag -1 3 213 0
03-21 14:21:43.378  1294  1294 D ImsConfigImpl: ImsConfigImpl Creates
03-21 14:21:43.444  1294  1294 D ImsConfigImpl: mcc = 0, mnc = 0
03-21 14:21:43.450  1294  1294 D ImsSenderRxr: [0000]> REQUEST_QUERY_SERVICE_STATUS
03-21 14:21:43.451  1294  1294 D ImsSenderRxr: Message data: [0, 0, 0, 12, 11, 13, 0, 0, 0, 0, 16, 1, 24, 29, 32, 0]
03-21 14:21:43.470   820  1097 I ActivityManager: Killing 2120:com.google.android.talk/u0a61 (adj 15): empty #17
03-21 14:21:43.473  1294  2521 V ImsSenderRxr: Read packet: 12 bytes
03-21 14:21:43.473  1294  2521 V ImsSenderRxr: processResponse
03-21 14:21:43.473  1294  2521 D ImsSenderRxr: Response data: [11, 13, 0, 0, 0, 0, 16, 2, 24, 29, 32, 2]
03-21 14:21:43.473  1294  2521 D ImsSenderRxr:  Tag 0 2 29 2
03-21 14:21:43.473  1294  2521 D ImsSenderRxr: [0000]< REQUEST_QUERY_SERVICE_STATUS error: 2
03-21 14:21:43.506  2518  2518 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 14:21:43.509  2518  2518 D AndroidRuntime: CheckJNI is OFF
03-21 14:21:43.587  1294  1294 D ImsServiceSub: Message received: what = 5
03-21 14:21:43.588  1294  1294 D ImsServiceSub: Received event: EVENT_GET_STATUS_UPDATE
03-21 14:21:43.588  1294  1294 E ImsServiceSub: IMS Service Status Update failed!
03-21 14:21:43.605  1249  1249 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
03-21 14:21:43.610  1294  2534 D ImsServiceClassTracker: updateVtCapability false
03-21 14:21:43.611  1294  2534 D ImsServiceSub: send new listener registered event
03-21 14:21:43.611  1294  2534 D ImsServiceSub: getServiceId returns 1
03-21 14:21:43.611  1294  2534 D ImsSenderRxr: [0001]> REQUEST_IMS_REGISTRATION_STATE
03-21 14:21:43.611  1294  2534 D ImsSenderRxr: Message data: [0, 0, 0, 12, 11, 13, 1, 0, 0, 0, 16, 1, 24, 1, 32, 0]
03-21 14:21:43.611  1294  1294 D ImsServiceSub: Message received: what = 12
03-21 14:21:43.614  1294  2534 D ImsService: Open returns serviceId 1
03-21 14:21:43.614  1294  2521 V ImsSenderRxr: Read packet: 12 bytes
03-21 14:21:43.615  1294  2521 V ImsSenderRxr: processResponse
03-21 14:21:43.615  1294  2521 D ImsSenderRxr: Response data: [11, 13, 1, 0, 0, 0, 16, 2, 24, 1, 32, 2]
03-21 14:21:43.615  1294  2521 D ImsSenderRxr:  Tag 1 2 1 2
03-21 14:21:43.615  1294  2521 D ImsSenderRxr: [0001]< REQUEST_IMS_REGISTRATION_STATE error: 2
03-21 14:21:43.615  1294  1294 D ImsServiceSub: Message received: what = 3
03-21 14:21:43.615  1294  1294 E ImsServiceSub: IMS State query failed!
03-21 14:21:43.618  1294  2534 D ImsSenderRxr: setUiTTYMode uittyMode=0
03-21 14:21:43.618  1294  2534 D ImsSenderRxr: [0002]> REQUEST_SEND_UI_TTY_MODE
03-21 14:21:43.618  1294  2534 D ImsSenderRxr: Message data: [0, 0, 0, 14, 11, 13, 2, 0, 0, 0, 16, 1, 24, 39, 32, 0, 8, 0]
03-21 14:21:43.621  1768  1768 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
03-21 14:21:43.625  1249  2535 I NotificationStore: System rebooted after Notification storage file was last written
03-21 14:21:43.625  1249  2535 I NotificationStore: Deleting the file
03-21 14:21:43.632  2518  2518 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 14:21:43.634  1249  1249 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
03-21 14:21:43.634   820  1097 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 14:21:43.642   820  1097 V WindowManager: addAppToken: AppWindowToken{46bf343 token=Token{28c820f2 ActivityRecord{148ccbfd u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-21 14:21:43.648   820   859 V WindowManager: Adding window Window{286dc4a u0 Starting com.test.thalitest} at 2 of 7 (after Window{f5d4e27 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-21 14:21:43.651  2518  2518 D AndroidRuntime: Shutting down VM
03-21 14:21:43.652  1506  1506 I HotwordDetector: Closing mic
03-21 14:21:43.653  1506  1759 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1ed1c7ee
03-21 14:21:43.688  1294  2521 V ImsSenderRxr: Read packet: 12 bytes
03-21 14:21:43.688  1294  2521 V ImsSenderRxr: processResponse
03-21 14:21:43.688  1294  2521 D ImsSenderRxr: Response data: [11, 13, 2, 0, 0, 0, 16, 2, 24, 39, 32, 0]
03-21 14:21:43.688  1294  2521 D ImsSenderRxr:  Tag 2 2 39 0
03-21 14:21:43.688  1294  2521 D ImsSenderRxr: [0002]< REQUEST_SEND_UI_TTY_MODE 
03-21 14:21:43.690   820  1369 I ActivityManager: Start proc 2543:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-21 14:21:43.709   358  1765 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-21 14:21:43.710   358  1765 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-21 14:21:43.716   358  1019 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-21 14:21:43.717  1506  1761 I HotwordRecognitionRnr: Stopping hotword detection.
03-21 14:21:43.718  1506  1762 I HotwordRecognitionRnr: Hotword detection finished
03-21 14:21:43.763   820   836 I ActivityManager: Killing 2177:com.android.keychain/1000 (adj 15): empty #17
03-21 14:21:43.764   820  1266 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658897683
03-21 14:21:43.764   820  1266 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-21 14:21:43.775  1768  1768 W InstanceID/Rpc: Found 10011
,03-21 14:21:43.912  2543  2543 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-21 14:21:43.926  2543  2543 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5838-5839)
03-21 14:21:43.927  2543  2543 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 14:21:43.939  2543  2543 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3889641}
03-21 14:21:43.940  2543  2543 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 14:21:43.940  2543  2543 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 14:21:43.950  2543  2543 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 14:21:43.952  2543  2543 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 14:21:43.953  2543  2543 E SysUtils: ApplicationContext is null in ApplicationStatus
03-21 14:21:43.959  2543  2572 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
03-21 14:21:43.963  1768  2562 D FileApkUtils: Spent 33ms computing apk sha1.
03-21 14:21:43.964  1768  2562 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
03-21 14:21:43.965  2543  2543 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-21 14:21:43.970  2543  2543 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 14:21:43.970  2543  2543 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 14:21:43.970  2543  2543 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-21 14:21:43.996  1768  2562 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d27787c4e483aadd035a354447c9e84728eb2ab4/MapsModule.apk is already optimized. Bailing.
03-21 14:21:43.997  1768  2562 D FileApkUtils: Keeping up-to-date module: module-d27787c4e483aadd035a354447c9e84728eb2ab4
03-21 14:21:44.012  1768  2562 D GmsModuleFndr: Beginning GMS chimera module scan
03-21 14:21:44.017   820   858 D BluetoothManagerService: Message: 20
03-21 14:21:44.017   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5840cdd:true
03-21 14:21:44.022  1768  2571 D GCM     : COMPAT: Multi user ser=0 current=0
03-21 14:21:44.036  1249  2595 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
03-21 14:21:44.038  1768  2593 I CheckinService: Disabling old GoogleServicesFramework version
03-21 14:21:44.045  1768  2562 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
03-21 14:21:44.045  1768  2562 D ChimeraCfgMgr: Beginning module configuration check
03-21 14:21:44.046  2543  2543 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 14:21:44.047  1768  2562 D ChimeraCfgMgr: Module APKs unchanged, check complete
03-21 14:21:44.053  2543  2543 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-21 14:21:44.053  1768  1768 D SystemUpdateService: onCreate
03-21 14:21:44.054   820  1324 I ActivityManager: Delay finish: com.google.android.gms/.tron.AlarmReceiver
03-21 14:21:44.060  1768  2600 I CheckinService: Checking schedule, now: 1458566504060 next: 1458589154466
03-21 14:21:44.060  1768  2600 I CheckinService: active receiver: disabled
03-21 14:21:44.064  2543  2543 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
03-21 14:21:44.068  2543  2543 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 14:21:44.068  2543  2543 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 14:21:44.112  2543  2610 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-21 14:21:44.116  2543  2543 D Atlas   : Validating map...
03-21 14:21:44.127   820  1097 V WindowManager: Adding window Window{33fede7c u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{286dc4a u0 Starting com.test.thalitest})
03-21 14:21:44.130  2543  2585 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-21 14:21:44.134  1768  1768 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
03-21 14:21:44.136  1768  2571 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
03-21 14:21:44.140  1249  1249 I ConfigService: onCreate
03-21 14:21:44.148  1768  1768 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
03-21 14:21:44.158  1768  2615 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
03-21 14:21:44.162  2543  2610 I OpenGLRenderer: Initialized EGL, version 1.4
03-21 14:21:44.163  1768  2615 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
03-21 14:21:44.165  1826  1826 I GCoreUlr: DispatchingService.onCreate()
03-21 14:21:44.169  2543  2610 D OpenGLRenderer: Enabling debug mode 0
03-21 14:21:44.217  1768  1768 I ConfigFetchService: service connected
03-21 14:21:44.220  1768  2611 I SystemUpdateService: active receiver: enabled
03-21 14:21:44.234  1768  2615 W BaseAppContext: Using Auth Proxy for data requests.
03-21 14:21:44.244   820   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +593ms
03-21 14:21:44.247  1768  1768 D ConfigFetchService: ConfigApi connection successful.
03-21 14:21:44.249  1225  1225 I Keyboard.Facilitator: onFinishInput()
03-21 14:21:44.250  2543  2543 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2543
03-21 14:21:44.261  1768  2615 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
03-21 14:21:44.267  1249  1715 I art     : Explicit concurrent mark sweep GC freed 12541(679KB) AllocSpace objects, 4(64KB) LOS objects, 38% free, 25MB/41MB, paused 2.894ms total 69.482ms
03-21 14:21:44.277  1768  2615 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
03-21 14:21:44.307   820  1312 I ActivityManager: Resuming delayed broadcast
03-21 14:21:44.312   820   836 I art     : Explicit concurrent mark sweep GC freed 16306(845KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 32MB/48MB, paused 1.567ms total 86.081ms
03-21 14:21:44.316  1768  1768 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-21 14:21:44.327  1768  2615 I AuthZen : Fetching signing key...
03-21 14:21:44.327  1768  1768 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
03-21 14:21:44.341  1768  2615 I AuthZen : Signing key fetched successfully!
03-21 14:21:44.349  1768  2615 W BaseAppContext: Using Auth Proxy for data requests.
03-21 14:21:44.351  2543  2543 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-21 14:21:44.354   820  1312 I ActivityManager: Start proc 2636:com.google.android.youtube/u0a86 for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
03-21 14:21:44.364  1768  2615 I AuthZen : Starting Enrollment...
03-21 14:21:44.366  1768  2611 I SystemUpdateService: Already downloaded, skipping offpeak checks.
03-21 14:21:44.380  1768  1897 I art     : Explicit concurrent mark sweep GC freed 36307(2MB) AllocSpace objects, 29(464KB) LOS objects, 38% free, 25MB/41MB, paused 1.687ms total 48.752ms
03-21 14:21:44.386  1768  2615 D AuthZen : getting auth token. Attempt 0
03-21 14:21:44.404  1249  1715 I GLSActivity: [ac] getting account id
03-21 14:21:44.415   820   858 D BluetoothManagerService: Message: 20
03-21 14:21:44.416   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2213b086:true
03-21 14:21:44.419  1826  2622 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
03-21 14:21:44.421  1249  1249 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
03-21 14:21:44.422  1249  1249 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
03-21 14:21:44.424  1768  2611 I SystemUpdateService: network: null; metered: false; mobile allowed: false
03-21 14:21:44.444  1249  1715 I GLSUser : [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
03-21 14:21:44.455  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
03-21 14:21:44.455  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:21:44.457  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:21:44.458  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-21 14:21:44.464  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 14:21:44.485  1768  2615 E AuthZen : Error getting auth token
03-21 14:21:44.485  1768  2615 E AuthZen : com.google.android.gms.auth.ad: BadAuthentication
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at android.os.Looper.loop(Looper.java:135)
03-21 14:21:44.485  1768  2615 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 14:21:44.486  1768  2615 E AuthZen : Failed to do enrollment for account: thalitester@gmail.com
03-21 14:21:44.486  1768  2615 E AuthZen : com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at android.os.Looper.loop(Looper.java:135)
03-21 14:21:44.486  1768  2615 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 14:21:44.493  2543  2620 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576405504
03-21 14:21:44.505  2543  2620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 14:21:44.505  2543  2620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 14:21:44.505  2543  2620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 14:21:44.505  2543  2620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 14:21:44.505  2543  2620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 14:21:44.505  2543  2620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b674a3 added. We now have 1 listener(s)
03-21 14:21:44.506   820  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-21 14:21:44.508  1768  2615 D a       : Opening database auth.proximity.permit_store...
03-21 14:21:44.514  1768  2615 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-21 14:21:44.515  1768  2615 D AuthZenTransactionCache: Clearing transaction cache
03-21 14:21:44.516  2543  2620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
03-21 14:21:44.516  2543  2620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-21 14:21:44.517  2543  2620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 14:21:44.517  2543  2620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 14:21:44.524  2543  2620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@243531e added. We now have 1 listener(s)
03-21 14:21:44.524  2543  2620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-21 14:21:44.537   820  1022 D WifiService: New client listening to asynchronous messages
03-21 14:21:44.540  2543  2620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-21 14:21:44.544  2543  2620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-21 14:21:44.544  2543  2620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 14:21:44.544  2543  2620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 14:21:44.544  2543  2620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-21 14:21:44.546  2543  2620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 14:21:44.546   820   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-21 14:21:44.547  2543  2620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-21 14:21:44.551  2543  2620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-21 14:21:44.551  2543  2620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 14:21:44.551  2543  2620 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 14:21:44.552  2543  2620 I io.jxcore.node.LifeCycleMonitor: start: OK
03-21 14:21:44.562  1768  2611 I DownloadAttempt: current file is /data/data/com.google.android.gms/app_download/update.zip
03-21 14:21:44.562  1768  2611 I DownloadAttempt: mSize 25802302 mDownloaded 25802302
03-21 14:21:44.563  1768  2611 I SystemUpdateService: status is 0 (complete)
03-21 14:21:44.563  1768  2611 I SystemUpdateService: now status is 0 (complete)
03-21 14:21:44.563  1768  2611 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-21 14:21:44.563  1768  2611 I SystemUpdateService: file has been verified
03-21 14:21:44.563  1768  2611 I SystemUpdateService: OTA package size = 25802302
03-21 14:21:44.572  2543  2543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-21 14:21:44.588  2543  2543 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-21 14:21:44.590  1768  2611 I SystemUpdateService: showing system update notification
03-21 14:21:44.634   820   820 I ValidateNoPeople: skipping global notification
03-21 14:21:44.634  1768  1768 D SystemUpdateService: onDestroy
03-21 14:21:44.641  1063  1083 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:21:44.641  1063  1083 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-21 14:21:44.662  1826  2622 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
03-21 14:21:44.670  1826  2622 I GCoreUlr: Unbound from all location providers
03-21 14:21:44.709  1826  1826 I GCoreUlr: DispatchingService.onDestroy()
03-21 14:21:44.712  1826  1826 I GCoreUlr: Unbound from all location providers
,03-21 14:21:44.768  2636  2662 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:21:44.769  2636  2662 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:21:44.813  2636  2662 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:21:44.889  2636  2662 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:21:45.059  2672  2672 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1873616137.jar --oat-fd=18 --oat-location=/data/data/com.google.android.youtube/cache/ads1873616137.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-21 14:21:45.094  2636  2636 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-21 14:21:45.104  2672  2672 I dex2oat : dex2oat took 45.030ms (threads: 4) arena alloc=147KB java alloc=12KB native alloc=1221KB free=6MB
,03-21 14:21:45.245  2543  2660 W jxcore-log: Initializing JXcore engine
03-21 14:21:45.245  2543  2660 W jxcore-log: JXcore engine is ready
,03-21 14:21:45.264  2636  2636 W InstanceID/Rpc: Found 10011
,03-21 14:21:45.289  2660  2660 W Thread-254: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11432]" dev="sockfs" ino=11432 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 14:21:45.289  2660  2660 W Thread-254: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-21 14:21:45.289  2660  2660 W Thread-254: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9830]" dev="sockfs" ino=9830 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 14:21:45.289  2660  2660 W Thread-254: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[17990]" dev="sockfs" ino=17990 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-21 14:21:45.311  2543  2660 W jxcore-log: Starting JXcore engine
,03-21 14:21:45.389  1768  1768 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-21 14:21:45.439  2543  2660 W jxcore-log: Platform android
03-21 14:21:45.439  2543  2660 W jxcore-log: 
03-21 14:21:45.439  2543  2660 W jxcore-log: Process ARCH arm
03-21 14:21:45.439  2543  2660 W jxcore-log: 
,03-21 14:21:45.442   820  1022 D WifiService: New client listening to asynchronous messages
,03-21 14:21:45.446  1506  1669 I VelvetNetworkClient: Network connection not availble
,03-21 14:21:45.460   820  1140 I ActivityManager: Start proc 2740:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,03-21 14:21:45.502  2740  2740 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 14:21:45.506  1506  1894 W LocationOracleImpl: Best location was null
,03-21 14:21:45.527  1506  1894 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 14:21:45.542  1506  1894 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7453-7455)
03-21 14:21:45.542  1506  1894 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 14:21:45.553  1506  1894 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 14:21:45.628  1506  1894 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 14:21:45.639  2740  2772 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-21 14:21:45.639  2740  2772 I Babel_SMS: MmsConfig.loadMmsSettings
03-21 14:21:45.639  2740  2772 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
03-21 14:21:45.639  2740  2772 I Babel_SMS: MmsConfig.loadFromDatabase
,03-21 14:21:45.655   820  1312 I ActivityManager: Killing 2195:com.google.android.dialer/u0a13 (adj 15): empty #17
,03-21 14:21:45.662  2543  2660 I jxcore-log: JXcore Cordova bridge is ready!
03-21 14:21:45.662  2543  2660 I jxcore-log: 
,03-21 14:21:45.662  2543  2660 W jxcore-log: JXcore engine is started
,03-21 14:21:45.665  2740  2772 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-21 14:21:45.665  2740  2772 I Babel_SMS: MmsConfig.loadFromResources
,03-21 14:21:45.666  2740  2772 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-21 14:21:45.667  2740  2772 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,03-21 14:21:45.670  2543  2620 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 14:21:45.671  2543  2543 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 14:21:45.783  2740  2740 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-21 14:21:45.786  2740  2740 I Babel_Crash: startup - clean
,03-21 14:21:45.809  2740  2780 I Babel   : deleted: false for 0
,03-21 14:21:45.856  2740  2740 I Babel_telephony: TeleModule.launchCompleted
,03-21 14:21:45.862   820   835 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 14:21:45.864  2740  2740 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-21 14:21:45.864  2740  2740 W Babel   : BAM#gBA: invalid account id: -1
03-21 14:21:45.864  2740  2740 W Babel   : BAM#gBA: invalid account id: -1
03-21 14:21:45.864  2740  2740 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
03-21 14:21:45.865   820  1312 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 14:21:45.921  2740  2740 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:45.961  2740  2740 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-21 14:21:45.967  2740  2740 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:45.969  2740  2740 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:45.972  2740  2740 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:45.977  2740  2740 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:45.989  2740  2740 I vclib   : onServiceConnected
,03-21 14:21:45.992  2740  2740 W Babel   : Attempted to change video mute state without an active call.
,03-21 14:21:46.023   820  1312 I ActivityManager: Start proc 2784:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.FitnessBootReceiver
03-21 14:21:46.024   820  1312 I ActivityManager: Killing 2237:com.motorola.motocit/u0a2 (adj 15): empty #17
,03-21 14:21:46.195  2784  2784 I FitnessApp: Initializers took 0 milliseconds
,03-21 14:21:46.224   820  1292 I ActivityManager: Start proc 2803:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
03-21 14:21:46.225   820  1292 I ActivityManager: Killing 1141:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,03-21 14:21:46.482   820  1324 I ActivityManager: Killing 2276:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
,03-21 14:21:46.508  2803  2803 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-21 14:21:46.508  2803  2803 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:21:46.508  2803  2803 I GAv4    :   adb logcat -s GAv4
,03-21 14:21:46.543  2803  2803 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:46.551  2803  2803 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:46.555  2803  2822 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:46.612   820  1292 I ActivityManager: Start proc 2825:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver
,03-21 14:21:46.613   820  1292 I ActivityManager: Killing 2300:com.android.managedprovisioning/u0a17 (adj 15): empty #17
,03-21 14:21:47.246  2380  2408 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
03-21 14:21:47.246  2825  2825 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 14:21:47.322  2825  2825 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-21 14:21:47.422   820  1140 I ActivityManager: Start proc 2863:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-21 14:21:47.457  2825  2825 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 14:21:47.463  2863  2863 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-21 14:21:47.463  2863  2863 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-21 14:21:47.464  2825  2825 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 14:21:47.497  2863  2863 I MultiDex: VM with version 2.1.0 has multidex support
03-21 14:21:47.497  2863  2863 I MultiDex: install
03-21 14:21:47.497  2863  2863 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 14:21:47.510  2825  2849 D Volley  : [261] DiskBasedCache.clear: Cache cleared.
,03-21 14:21:47.511  2825  2856 D Volley  : [268] DiskBasedCache.clear: Cache cleared.
,03-21 14:21:47.513  2863  2863 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:21:47.543  2863  2863 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:21:47.559   820  1097 I ActivityManager: Start proc 2885:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
,03-21 14:21:47.561   820  1097 I ActivityManager: Killing 1627:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-21 14:21:47.798  2825  2825 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-21 14:21:47.798  2825  2825 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-21 14:21:47.802  2825  2825 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-21 14:21:47.826  2825  2825 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-21 14:21:47.916  1249  1716 I art     : Explicit concurrent mark sweep GC freed 7469(399KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 625us total 18.549ms
,03-21 14:21:47.975   820  1140 I ActivityManager: Killing 2323:com.android.settings/1000 (adj 15): empty #17
,03-21 14:21:48.034  2825  2825 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-21 14:21:48.140  2885  2915 I Gmail   : getAccountsCursor
03-21 14:21:48.141  2885  2916 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-21 14:21:48.194   820  1369 I art     : Explicit concurrent mark sweep GC freed 14752(726KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 32MB/48MB, paused 983us total 47.248ms
,03-21 14:21:48.197  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:48.306   820   835 I ActivityManager: Start proc 2918:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,03-21 14:21:48.395  2885  2885 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 14:21:48.401   820  1369 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-21 14:21:48.411  2885  2939 I Gmail   : Observing account changes for notifications
,03-21 14:21:48.444  2885  2945 I Gmail   : getAccountsCursor
,03-21 14:21:48.449  1225  1225 I SystemBroadcastReceiver: Boot has been completed
,03-21 14:21:48.449  1225  1225 I SystemBroadcastReceiver: toggleAppIcon() : FLAG_SYSTEM = true
,03-21 14:21:48.453  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:48.479   820  1369 I ActivityManager: Start proc 2950:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
,03-21 14:21:48.498  2885  2885 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3f4b83a0 that was originally bound here
03-21 14:21:48.498  2885  2885 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3f4b83a0 that was originally bound here
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-21 14:21:48.498  2885  2885 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 14:21:48.499   370   370 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 345us total 18.530ms
,03-21 14:21:48.509   370   370 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 9.412ms
03-21 14:21:48.518  2918  2918 I Exchange: EasService.onCreate
03-21 14:21:48.519   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 8.341ms
03-21 14:21:48.528  2918  2969 I Exchange: RestartPingTask
03-21 14:21:48.533  2918  2918 I Exchange: RestartPingsTask did not start any pings.
03-21 14:21:48.534  2918  2918 I Exchange: PSS stopIfIdle
03-21 14:21:48.534  2918  2918 I Exchange: PSS has no active accounts; stopping service.
,03-21 14:21:48.540  2918  2918 I Exchange: onDestroy
03-21 14:21:48.540   820  1368 I ActivityManager: Killing 2344:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,03-21 14:21:48.551  2885  2946 E SQLiteLog: (283) recovered 58 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-21 14:21:48.615  2885  2967 I Gmail   : notifyAccountChanged
,03-21 14:21:48.617  2885  2967 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 14:21:48.621  2885  2967 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 14:21:48.628  2885  2967 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 14:21:48.637  2885  2967 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 14:21:48.665  2885  2946 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,03-21 14:21:48.669  2885  2946 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,03-21 14:21:48.673  2885  2946 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,03-21 14:21:48.677   820  1369 I ActivityManager: Killing 2255:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-21 14:21:48.870  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:48.872  2885  2915 I Gmail   : getAccountsCursor
,03-21 14:21:48.877  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:48.883  2885  2916 I Gmail   : getAccountsCursor
,03-21 14:21:48.886  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:48.944  2950  2950 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:48.967  2950  2950 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-21 14:21:48.983  2950  2950 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:48.988  2950  2978 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:48.994  1826  1826 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-21 14:21:48.997  2950  2978 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 14:21:49.009  2950  2982 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.012  2950  2950 I BugleUsageStatistics: PlayLogger.onLoggerConnected
03-21 14:21:49.014  2950  2978 I Bugle   : ApnsOta: OTA version -1
03-21 14:21:49.015  2950  2978 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.030   820  1324 I ActivityManager: Start proc 2984:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,03-21 14:21:49.062  2950  3001 I art     : Note: end time exceeds epoch: 
,03-21 14:21:49.068  2950  2983 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.102  2950  2980 I BugleDataModel: Fixup: Send failed - 0 Download failed - 0
,03-21 14:21:49.107  2950  2980 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.124   820  1292 I ActivityManager: Killing 2412:com.google.android.configupdater/u0a42 (adj 15): empty #17
,03-21 14:21:49.174  2950  2983 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.174  2950  2983 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.176  2950  2983 W Bugle   : PhoneUtils.getSelfRawNumber: subInfo is null for -1
,03-21 14:21:49.177  2950  2983 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.259  1249  1249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,03-21 14:21:49.308   820  1292 I ActivityManager: Start proc 3004:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,03-21 14:21:49.342  2950  2980 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-21 14:21:49.349  2950  3021 I BugleDataModel: SyncMessagesAction: Starting batch for messages from 1458562061800 to 1458566508980 (message update limit = 80, message scan limit = 4000)
,03-21 14:21:49.429  2950  3023 I BugleDataModel: SyncMessagesAction: All messages now in sync
,03-21 14:21:49.432   820  1288 I ActivityManager: Killing 1593:com.google.android.keep/u0a79 (adj 15): empty #17
,03-21 14:21:49.881  3004  3004 I MusicStore: Database version: 120
,03-21 14:21:50.098   820  1140 I art     : Explicit concurrent mark sweep GC freed 8264(398KB) AllocSpace objects, 1(14KB) LOS objects, 32% free, 32MB/48MB, paused 1.430ms total 64.305ms
,03-21 14:21:50.240  3004  3004 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:21:50.240  3004  3004 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:21:50.264  3004  3004 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,03-21 14:21:50.299  3004  3004 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL,
03-21 14:21:50.299  3004  3004 D AndroidMusic: GMSCore installation verified,
,03-21 14:21:50.340  3004  3004 I ConfigStore: Config Database version: 1,
,03-21 14:21:50.487  3004  3004 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-21 14:21:50.500  2984  2984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,03-21 14:21:50.530   820   858 D BluetoothManagerService: Message: 20
03-21 14:21:50.530   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b3d172d:true
,03-21 14:21:50.536   820   835 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 14:21:50.537  2153  3038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 14:21:50.542  1249  1249 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,03-21 14:21:50.554   820  1369 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-21 14:21:50.554  2153  3042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 14:21:50.557  2153  3042 I BtOppRfcommListener: Accept thread started.
,03-21 14:21:50.559  2984  2984 D LocalBluetoothProfileManager: Adding local A2DP profile
03-21 14:21:50.561   820   858 D BluetoothManagerService: Message: 30
,03-21 14:21:50.568  3004  3004 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
03-21 14:21:50.568  2984  2984 D LocalBluetoothProfileManager: Adding local HEADSET profile
03-21 14:21:50.570   820   858 D BluetoothManagerService: Message: 30
,03-21 14:21:50.573   820   858 D BluetoothManagerService: Message: 30
,03-21 14:21:50.577   820   858 D BluetoothManagerService: Message: 30
,03-21 14:21:50.579  2984  2984 D LocalBluetoothProfileManager: Adding local MAP profile
03-21 14:21:50.580  2984  2984 D BluetoothMap: Create BluetoothMap proxy object
,03-21 14:21:50.581   820   858 D BluetoothManagerService: Message: 30
,03-21 14:21:50.584  3004  3004 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 14:21:50.584   820   858 D BluetoothManagerService: Message: 30
,03-21 14:21:50.590  2984  2984 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,03-21 14:21:50.593  2984  2984 D DockEventReceiver: finishStartingService: stopping service
,03-21 14:21:50.594  2984  2984 D BluetoothA2dp: Proxy object connected
,03-21 14:21:50.595  2984  2984 D A2dpProfile: Bluetooth service connected
,03-21 14:21:50.596  2984  2984 D BluetoothInputDevice: Proxy object connected
03-21 14:21:50.596  2984  2984 D HidProfile: Bluetooth service connected
03-21 14:21:50.598  2984  2984 D BluetoothPan: BluetoothPAN Proxy object connected
03-21 14:21:50.598  2984  2984 D PanProfile: Bluetooth service connected
,03-21 14:21:50.599  2984  2984 D BluetoothMap: Proxy object connected
,03-21 14:21:50.601  2984  2984 D MapProfile: Bluetooth service connected
03-21 14:21:50.601  2984  2984 D BluetoothMap: getConnectedDevices()
,03-21 14:21:50.602  2984  2984 D BluetoothPbap: Proxy object connected
03-21 14:21:50.602  2984  2984 D PbapServerProfile: Bluetooth service connected
,03-21 14:21:50.626   820   836 I ActivityManager: Killing 2498:com.qualcomm.telephony/1001 (adj 15): empty #17
,03-21 14:21:50.670   820   858 D BluetoothManagerService: Message: 400
,03-21 14:21:50.670  2984  2999 D BluetoothHeadset: Proxy object connected
03-21 14:21:50.671  2984  2984 D HeadsetProfile: Bluetooth service connected
,03-21 14:21:50.807   820  1368 I ActivityManager: Start proc 3052:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
,03-21 14:21:50.866  3052  3052 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-21 14:21:50.923   820  1368 I ActivityManager: Start proc 3069:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,03-21 14:21:50.999   820   835 I ActivityManager: Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,03-21 14:21:51.005   820  1292 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:51.010   820  1369 I ActivityManager: Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,03-21 14:21:51.022   820   835 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:51.065   820   835 I ActivityManager: Start proc 3089:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-21 14:21:51.115   820   836 I ActivityManager: Delay finish: com.android.musicfx/.Compatibility$Receiver
,03-21 14:21:51.139   820  1288 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:51.141   820  1369 I ActivityManager: Killing 1869:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-21 14:21:51.159  3004  3051 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-21 14:21:51.269   820  1324 I ActivityManager: Killing 2636:com.google.android.youtube/u0a86 (adj 15): empty #17
,03-21 14:21:51.275  1768  3108 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-21 14:21:51.427   820   835 I ActivityManager: Start proc 3109:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,03-21 14:21:51.441  1768  1768 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-21 14:21:51.449  1768  1768 I ConfigFetchService: launchTask
,03-21 14:21:51.452  1768  1768 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-21 14:21:51.452  1768  1768 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,03-21 14:21:51.469  3109  3109 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:21:51.469  3109  3109 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:21:51.470  1768  3126 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WTQiBRpiz2131r_L-oerzn1jXZdwye4INyBN3K3xzkp6gz3w2SfIdTndj57N0f66Gnr1Ph5CXZoJNBrs1YPovsm1tzlV8u9Ta6kAfaU-d0_6LXz14m5OADWaVxflN3XyGehGqR8rCnwcwAzvM9TYmmjJiVXARm44pykvyJ5vIRNDxItkQVJcHWtV0Q0zAdOpHn5ys576XN3kbGT8Z1bi028e0YoA6AWW3KDwsXAoWDim5ZG6c
,03-21 14:21:51.472  1768  3126 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 14:21:51.496  3109  3109 I MultiDex: VM with version 2.1.0 has multidex support
03-21 14:21:51.496  3109  3109 I MultiDex: install
03-21 14:21:51.496  3109  3109 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 14:21:51.511  3109  3109 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:21:51.559  3109  3109 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:21:51.587   820   835 I ActivityManager: Killing 1506:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-21 14:21:51.639   820  1022 D WifiService: Client connection lost with reason: 4
,03-21 14:21:51.778   820  1312 I ActivityManager: Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,03-21 14:21:51.783   820  1140 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:51.806  1768  3132 I PeopleContactsSync: CP2 sync disabled
,03-21 14:21:51.826  1768  1768 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-21 14:21:51.826  1768  1768 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-21 14:21:51.834  1768  1768 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
,03-21 14:21:51.835  1768  3126 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
03-21 14:21:51.835  1768  1768 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,03-21 14:21:51.837  1768  1768 D Vision  : Failed to find package metadata for com.test.thalitest
03-21 14:21:51.837  1768  1768 D Vision  : No vision deps
,03-21 14:21:51.868   820  1324 I ActivityManager: Start proc 3137:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,03-21 14:21:51.872  1768  1768 I ConfigFetchService: fetch service done; releasing wakelock
,03-21 14:21:51.873  1768  1768 I ConfigFetchService: stopping self
,03-21 14:21:51.890  1768  3133 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 65 ms
,03-21 14:21:51.973   820   835 I ActivityManager: Start proc 3156:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-21 14:21:51.992  1768  3136 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 14:21:51.993  1768  3136 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 14:21:52.039  1768  3136 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 14:21:52.049  1768  3136 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 14:21:52.053  1768  3136 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 14:21:52.078  1768  3136 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 14:21:52.107   820  1324 I art     : Explicit concurrent mark sweep GC freed 6363(301KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.316ms total 46.298ms
,03-21 14:21:52.163  3137  3155 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-21 14:21:52.255  1249  1599 I art     : Explicit concurrent mark sweep GC freed 7157(371KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 756us total 19.544ms
,03-21 14:21:52.309  3137  3155 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
,03-21 14:21:52.311   820  1312 I ActivityManager: Killing 2740:com.google.android.talk/u0a61 (adj 15): empty #17
,03-21 14:21:52.518  1768  3136 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-21 14:21:52.518  1768  3136 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-21 14:21:52.622  3156  3156 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-21 14:21:52.622  3156  3156 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:21:52.622  3156  3156 I GAv4    :   adb logcat -s GAv4
,03-21 14:21:52.633  3156  3156 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:52.640  3156  3156 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:52.645  3156  3194 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:52.658  3156  3156 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-21 14:21:52.747  3156  3200 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:21:52.747  3156  3200 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:21:52.773   820  1324 I ActivityManager: Start proc 3201:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,03-21 14:21:52.774   820  1324 I ActivityManager: Killing 2803:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-21 14:21:52.917  3156  3200 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:21:52.921  3201  3201 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 14:21:52.975  3156  3200 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:21:52.983  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:53.003  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:53.355  1768  1846 I Icing   : Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,03-21 14:21:53.386  1768  1846 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-21 14:21:53.445  1768  1846 I art     : Explicit concurrent mark sweep GC freed 26239(1794KB) AllocSpace objects, 12(192KB) LOS objects, 22% free, 27MB/35MB, paused 503us total 40.522ms
,03-21 14:21:53.450  2885  2937 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 14:21:53.486  1768  1846 I Icing   : Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,03-21 14:21:53.578   820   820 I ValidateNoPeople: skipping global notification
,03-21 14:21:53.618  1249  2063 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-21 14:21:53.624  1768  1768 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-21 14:21:53.625  1768  1768 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-21 14:21:53.738   820  1292 I ActivityManager: Start proc 3239:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,03-21 14:21:53.792  3239  3239 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-21 14:21:53.856   820   835 I ActivityManager: Killing 1808:com.android.defcontainer/u0a7 (adj 15): empty #17
,03-21 14:21:53.969  3239  3239 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@6419928(com.android.providers.calendar.CalendarProvider2@3889641)
,03-21 14:21:53.994  1249  2106 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-21 14:21:54.004  1249  1249 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 14:21:54.011  1768  1768 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 14:21:54.015  3239  3264 E SQLiteLog: (284) automatic index on view_events(_id)
,03-21 14:21:54.026  3109  3109 D WearableService: callingUid 10011, callindPid: 3109
,03-21 14:21:54.031  1768  3266 D LocationInitializer: Restart initialization of location
,03-21 14:21:54.046   820  1097 I ActivityManager: Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,03-21 14:21:54.050   820   835 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:54.066   820  1324 I ActivityManager: Delay finish: com.google.android.gm/.MailIntentReceiver
,03-21 14:21:54.081  1826  1841 I art     : Explicit concurrent mark sweep GC freed 13018(763KB) AllocSpace objects, 5(80KB) LOS objects, 37% free, 26MB/42MB, paused 1.605ms total 43.831ms
,03-21 14:21:54.104   820   835 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:54.105  1826  3265 E MDM     : [163] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 14:21:54.182   820  1369 I ActivityManager: Start proc 3273:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,03-21 14:21:54.192   370   370 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 209us total 9.860ms
,03-21 14:21:54.203   370   370 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.080ms
,03-21 14:21:54.212   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 8.404ms
,03-21 14:21:54.216  3273  3273 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 14:21:54.220  2885  3269 I NotifUtils: Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,03-21 14:21:54.234  2885  3269 I NotifUtils: validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,03-21 14:21:54.256   820   998 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 14:21:54.305  1826  1826 V GmsNetworkLocationProvi: DISABLE
,03-21 14:21:54.311   820   820 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-21 14:21:54.311   820   820 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-21 14:21:54.316   820   820 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-21 14:21:54.342   820   820 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-21 14:21:54.343   820   820 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3f3545a1
,03-21 14:21:54.351  1826  1864 V GmsNetworkLocationProvi: onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,03-21 14:21:54.364  1826  1826 V GmsNetworkLocationProvi: ENABLE
,03-21 14:21:54.365  1826  1826 V GmsNetworkLocationProvi: SET-REQUEST
,03-21 14:21:54.366  1826  1826 V GmsNetworkLocationProvi: in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,03-21 14:21:54.372  3273  3301 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-21 14:21:54.372  3273  3301 I Babel_SMS: MmsConfig.loadMmsSettings
,03-21 14:21:54.380  3273  3301 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
03-21 14:21:54.380  3273  3301 I Babel_SMS: MmsConfig.loadFromDatabase
,03-21 14:21:54.395  3273  3301 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-21 14:21:54.395  3273  3301 I Babel_SMS: MmsConfig.loadFromResources
03-21 14:21:54.396  3273  3301 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-21 14:21:54.396  3273  3301 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,03-21 14:21:54.407  1314  1314 I Launcher: Deferring update until onResume
,03-21 14:21:54.422  3273  3273 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-21 14:21:54.424  3273  3273 I Babel_Crash: startup - clean
,03-21 14:21:54.470  3273  3304 I Babel   : deleted: false for 0
,03-21 14:21:54.494  3273  3273 I Babel_telephony: TeleModule.launchCompleted
,03-21 14:21:54.499   820  1368 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 14:21:54.506  3273  3273 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-21 14:21:54.506  3273  3273 W Babel   : BAM#gBA: invalid account id: -1
03-21 14:21:54.506  3273  3273 W Babel   : BAM#gBA: invalid account id: -1
03-21 14:21:54.506  3273  3273 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-21 14:21:54.507   820  1140 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 14:21:54.514  1249  2109 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-21 14:21:54.524  1249  1249 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 14:21:54.528  1768  1768 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 14:21:54.550  1826  2069 E MDM     : [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 14:21:54.554  1768  3308 D LocationInitializer: Restart initialization of location
,03-21 14:21:54.562  3273  3273 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:54.586  3273  3273 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-21 14:21:54.591  3273  3273 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:54.594  3273  3273 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-21 14:21:54.596  3273  3273 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:54.601  3273  3273 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:54.604   820   836 I art     : Explicit concurrent mark sweep GC freed 20967(1090KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.601ms total 47.985ms
,03-21 14:21:54.636  3273  3273 I vclib   : onServiceConnected
03-21 14:21:54.637  3273  3273 W Babel   : Attempted to change video mute state without an active call.
,03-21 14:21:54.643   820  1288 I ActivityManager: Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,03-21 14:21:54.653   820  1312 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:54.740  1768  3315 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-21 14:21:54.743  1768  3315 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
03-21 14:21:54.743   820  1288 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,03-21 14:21:54.747  3137  3316 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-21 14:21:54.758  3273  3273 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:21:54.758  3273  3273 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-21 14:21:54.760  1768  1846 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-21 14:21:54.773  3137  3316 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 26 ms] updated apps [took 26 ms] 
,03-21 14:21:54.777   820   836 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:54.781  1314  1314 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f846540 new=com.google.android.velvet.VelvetApplication@f846540
,03-21 14:21:54.792   820  1369 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,03-21 14:21:54.794   820  1324 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:54.797   820  1097 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,03-21 14:21:54.809  3273  3273 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:21:54.819   820  1292 I ActivityManager: Resuming delayed broadcast
,03-21 14:21:54.837  3273  3273 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:21:54.856  3273  3311 I Babel_telephony: TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,03-21 14:21:54.861  3273  3311 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:54.862  3273  3311 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:54.864  3273  3311 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 14:21:54.944  3273  3324 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,03-21 14:21:55.043  3239  3239 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-21 14:21:55.043  3239  3239 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 14:21:55.628  3004  3326 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-21 14:21:55.628  3004  3326 I MusicLeanback: Stop autocaching.
,03-21 14:21:55.647  3004  3004 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 14:21:55.647  3004  3331 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 14:21:56.321  2543  2660 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 14:21:56.321  2543  2660 I jxcore-log: 
,03-21 14:21:56.323  2543  2660 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 14:21:56.323  2543  2660 I jxcore-log: 
,03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-21 14:21:56.328  2543  2660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-21 14:21:56.332  2543  2660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-21 14:21:56.335  2543  2660 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 14:21:56.335  2543  2660 I jxcore-log: 
,03-21 14:21:56.336  2543  2660 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 14:21:56.336  2543  2660 I jxcore-log: 
,03-21 14:21:56.742   820   854 I ActivityManager: Waited long enough for: ServiceRecord{365ce3c3 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,03-21 14:21:56.890  1249  1249 I ConfigService: onDestroy
,03-21 14:21:56.913  2543  2660 I jxcore-log: Unit Test app is loaded
03-21 14:21:56.913  2543  2660 I jxcore-log: 
,03-21 14:21:56.918  2543  2660 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
03-21 14:21:56.918  2543  2660 I jxcore-log: 
,03-21 14:21:56.925  2543  2660 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED,
03-21 14:21:56.928  2543  2660 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
,03-21 14:21:56.928  2543  2660 I jxcore-log: 
,03-21 14:21:56.930  2543  2660 I jxcore-log: My device name is: motorola-Nexus 6,
03-21 14:21:56.930  2543  2660 I jxcore-log: 
,03-21 14:21:56.941  2543  2543 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74),
,03-21 14:21:57.294   820   854 I ActivityManager: Waited long enough for: ServiceRecord{1ab8ad22 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,03-21 14:21:58.120   820   854 I ActivityManager: Waited long enough for: ServiceRecord{144acdaf u0 com.qualcomm.atfwd/.AtFwdService}
,03-21 14:21:58.226   375   375 I Atfwd_Daemon: result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-21 14:21:58.226   375   375 I Atfwd_Daemon: ATFWD --> QMI Port : rmnet_usb0
,03-21 14:21:58.297   375   375 I Atfwd_Daemon: qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
,03-21 14:21:58.297   375   375 I Atfwd_Daemon: Trying to register 8 commands:
03-21 14:21:58.297   375   375 I Atfwd_Daemon: cmd0: +CKPD
,03-21 14:21:58.307   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-21 14:21:58.307   375   375 I Atfwd_Daemon: cmd1: +CTSA
,03-21 14:21:58.317   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-21 14:21:58.317   375   375 I Atfwd_Daemon: cmd2: +CFUN,
,03-21 14:21:58.327   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-21 14:21:58.327   375   375 I Atfwd_Daemon: cmd3: +CMAR
,03-21 14:21:58.337   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-21 14:21:58.337   375   375 I Atfwd_Daemon: cmd4: +CDIS
,03-21 14:21:58.347   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-21 14:21:58.347   375   375 I Atfwd_Daemon: cmd5: +CRSL,
,03-21 14:21:58.357   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-21 14:21:58.357   375   375 I Atfwd_Daemon: cmd6: +CSS
,03-21 14:21:58.367   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-21 14:21:58.367   375   375 I Atfwd_Daemon: cmd7: $QCPWRDN,
,03-21 14:21:58.377   375   375 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-21 14:21:58.377   375   375 I Atfwd_Daemon: Registered AT Commands event handler
,03-21 14:21:59.553   820  1324 I ActivityManager: Killing 2918:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,03-21 14:22:00.691  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 14:22:00.691  2543  2660 I jxcore-log: 
,03-21 14:22:01.089  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-21 14:22:01.089  2543  2660 I jxcore-log: 
,03-21 14:22:01.105  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
03-21 14:22:01.105  2543  2660 I jxcore-log: 
,03-21 14:22:01.111  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
,03-21 14:22:01.111  2543  2660 I jxcore-log: 
,03-21 14:22:01.151  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
,03-21 14:22:01.151  2543  2660 I jxcore-log: 
,03-21 14:22:01.169  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,03-21 14:22:01.169  2543  2660 I jxcore-log: 
,03-21 14:22:01.174  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
,03-21 14:22:01.174  2543  2660 I jxcore-log: 
,03-21 14:22:03.194  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 14:22:03.194  2543  2660 I jxcore-log: 
,03-21 14:22:03.213  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,03-21 14:22:03.213  2543  2660 I jxcore-log: 
,03-21 14:22:03.222  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
,03-21 14:22:03.222  2543  2660 I jxcore-log: 
,03-21 14:22:03.347  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,03-21 14:22:03.347  2543  2660 I jxcore-log: 
,03-21 14:22:03.404  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
,03-21 14:22:03.404  2543  2660 I jxcore-log: 
,03-21 14:22:03.544  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-21 14:22:03.544  2543  2660 I jxcore-log: 
,03-21 14:22:03.550  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
,03-21 14:22:03.550  2543  2660 I jxcore-log: 
,03-21 14:22:03.557  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,03-21 14:22:03.557  2543  2660 I jxcore-log: 
,03-21 14:22:03.582  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,03-21 14:22:03.582  2543  2660 I jxcore-log: 
,03-21 14:22:03.603  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,03-21 14:22:03.603  2543  2660 I jxcore-log: 
,03-21 14:22:03.708  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
,03-21 14:22:03.708  2543  2660 I jxcore-log: 
,03-21 14:22:03.715  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,03-21 14:22:03.715  2543  2660 I jxcore-log: 
,03-21 14:22:03.740  2543  2660 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,03-21 14:22:03.740  2543  2660 I jxcore-log: 
,03-21 14:22:04.144  1768  2593 I CheckinService: Done disabling old GoogleServicesFramework version
,03-21 14:22:05.247  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:22:05.869   820   854 I ActivityManager: Waited long enough for: ServiceRecord{257e4009 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,03-21 14:22:07.147   820  1097 I ActivityManager: Killing 2784:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,03-21 14:22:08.165  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:08.244  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-21 14:22:08.245  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:22:08.245  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:22:08.246  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:22:08.257  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:08.312  2825  2825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-21 14:22:08.315  2825  2825 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-21 14:22:08.318  2825  2825 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-21 14:22:12.374   820  1292 I ActivityManager: Killing 2984:com.android.settings/1000 (adj 15): empty #17
,03-21 14:22:12.481   820  1292 I ActivityManager: Killing 2950:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-21 14:22:17.792  2825  2825 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-21 14:22:17.833  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 14:22:17.902  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 14:22:17.902  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:22:17.902  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:22:17.902  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:22:17.911  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:17.953  2825  2825 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 14:22:17.974  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:18.046  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-21 14:22:18.047  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:22:18.047  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:22:18.047  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:22:18.056  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:18.123  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:18.210  1249  1599 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 14:22:18.210  1249  1599 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:22:18.211  1249  1599 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:22:18.211  1249  1599 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:22:18.223  1249  1599 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:18.276  2825  2825 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 14:22:18.707  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:18.749  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 14:22:18.749  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:22:18.749  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:22:18.749  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:22:18.754  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:18.774  2825  2825 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 14:22:18.776  2825  2825 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-21 14:22:18.788  2825  2825 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-21 14:22:18.796  2825  2825 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 257 minutes (failures=4)
,03-21 14:22:18.812  1826  1864 D DeviceConnectionService: client connected with version: 7571000
,03-21 14:22:21.374   820   836 I art     : Explicit concurrent mark sweep GC freed 23876(1143KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.367ms total 88.669ms
,03-21 14:22:21.463  1249  2318 I art     : Explicit concurrent mark sweep GC freed 28261(1435KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.118ms total 34.523ms
,03-21 14:22:22.302  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:22:39.468  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:39.517  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-21 14:22:39.518  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:22:39.518  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:22:39.518  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:22:39.523  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:39.545  2825  2825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-21 14:22:39.546  2825  2825 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-21 14:22:39.546  2825  2825 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-21 14:22:44.279  1225  1439 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-21 14:22:44.279  1225  1439 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-21 14:22:44.319  1249  1249 I ConfigService: onCreate
,03-21 14:22:49.409  1249  1249 I ConfigService: onDestroy
,03-21 14:22:59.797  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:59.855  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-21 14:22:59.855  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:22:59.855  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:22:59.855  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:22:59.865  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:59.894  2825  2825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-21 14:22:59.897  2825  2825 D Finsky  : [1] 5.onFinished: Installation state replication failed.,
03-21 14:22:59.899  2825  2825 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-21 14:23:05.248  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:23:20.134  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:20.195  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-21 14:23:20.196  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:20.196  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-21 14:23:20.196  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:20.206  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:20.241  2825  2825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-21 14:23:20.242  2825  2825 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-21 14:23:20.245  2825  2825 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-21 14:23:22.444  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-21 14:23:40.581  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:40.632  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-21 14:23:40.632  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:40.632  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:40.632  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:40.638  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:40.668  2825  2825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-21 14:23:40.670  2825  2825 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-21 14:23:40.671  2825  2825 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-21 14:23:41.003   820   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-21 14:23:41.021   820   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 14:23:41.073   259   999 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (332 us)
,03-21 14:23:41.660   820   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-21 14:23:41.661   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-21 14:23:41.661   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-21 14:23:41.666   820   820 V ActivityManager: Display changed displayId=0
,03-21 14:23:41.842   871   871 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-21 14:23:41.843   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-21 14:23:41.884   871   871 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
03-21 14:23:41.884   871   871 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-21 14:23:41.918   259   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
,03-21 14:23:41.921   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0,
03-21 14:23:41.922   820  1041 D SurfaceControl: Excessive delay in setPowerMode(): 262ms
,03-21 14:23:41.929   820   861 I DreamManagerService: Entering dreamland.
03-21 14:23:41.931   820   861 I PowerManagerService: Dozing...
03-21 14:23:41.932   820   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-21 14:23:41.948   358  1029 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-21 14:23:41.948   358  1029 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-21 14:23:41.958   820  1021 E WifiStateMachine: cancelDelayedScan -> 16
,03-21 14:23:41.963   820  1021 E native  : do suspend false
,03-21 14:23:42.016  1225  1225 I Keyboard.Facilitator: onFinishInput()
,03-21 14:23:42.022   820  1021 E WifiStateMachine: cancelDelayedScan -> 18
,03-21 14:23:42.035   820  1324 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@de9860}
,03-21 14:23:42.075   820  1021 E native  : do suspend true
,03-21 14:23:42.097   358  1020 D audio_hw_primary: adev_set_parameters: enter: screen_state=off,
03-21 14:23:42.097   358  1020 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-21 14:23:42.121   820  1266 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-21 14:23:42.151   820   835 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@de9860}
,03-21 14:23:42.153   820  1021 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-21 14:23:42.159   820  1021 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-21 14:23:42.876   871   871 I kickstart: STATUS: Received file 'm9kefs1'
03-21 14:23:42.876   871   871 I kickstart: STATUS: 950272 bytes transferred in 0.992004 seconds
03-21 14:23:42.876   871   871 I kickstart: STATUS: Successfully downloaded files from target 
03-21 14:23:42.877   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-21 14:23:42.880   871   871 I kickstart: STATUS: Sahara protocol completed
,03-21 14:23:44.511  1137  1137 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-21 14:23:44.941  1137  1137 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-21 14:23:44.976  1137  1137 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-21 14:23:44.977  1137  1137 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-21 14:23:45.009   820  1021 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-21 14:23:45.011   820  1021 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 14:23:45.014   820  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-21 14:23:45.019   820  1021 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 14:23:45.027   354   814 D CommandListener: Setting iface cfg
,03-21 14:23:45.034   820  1021 E WifiStateMachine: Start Dhcp Watchdog 1
,03-21 14:23:45.040   820  1021 E WifiStateMachine:  WifiLinkLayerStats: 
03-21 14:23:45.040   820  1021 E WifiStateMachine:  my bss beacon rx: 2
03-21 14:23:45.040   820  1021 E WifiStateMachine:  RSSI mgmt: -40
03-21 14:23:45.040   820  1021 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-21 14:23:45.040   820  1021 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-21 14:23:45.040   820  1021 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-21 14:23:45.040   820  1021 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-21 14:23:45.040   820  1021 E WifiStateMachine:  on_time : 0 tx_time=61 rx_time=63 scan_time=0
,03-21 14:23:45.152   820  1021 E native  : do suspend false
,03-21 14:23:45.169   820  1021 E WifiStateMachine: scanCount==0 - aborting
,03-21 14:23:45.416  3377  3377 I dhcpcd  : version 5.5.6 starting
,03-21 14:23:45.532  3377  3377 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-21 14:23:45.599  3377  3377 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-21 14:23:45.757  3377  3377 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-21 14:23:46.197   820  1021 E native  : do suspend true
,03-21 14:23:46.248   820  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-21 14:23:46.252   820  1023 D ConnectivityService: Adding iface wlan0 to network 100
,03-21 14:23:46.259   820  1021 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-21 14:23:46.303   820  1023 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-21 14:23:46.304   820  1023 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
03-21 14:23:46.306   820  1023 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-21 14:23:46.309   820  1023 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-21 14:23:46.312   820  1023 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-21 14:23:46.324   820  1023 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-21 14:23:46.328   820  1023 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-21 14:23:46.329   820  3375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,03-21 14:23:46.329   820  3375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-21 14:23:46.329   820  3375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,03-21 14:23:46.330   820  3375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-21 14:23:46.337   820  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 14:23:46.337   820  1023 D ConnectivityService:    accepting network in place of null
,03-21 14:23:46.342   820  1023 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-21 14:23:46.345   820  1023 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-21 14:23:46.352   820  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-21 14:23:46.354   820  1023 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true,
,03-21 14:23:46.354   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-21 14:23:46.355   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,03-21 14:23:46.355  1063  1557 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-21 14:23:46.364   820   858 D Tethering: MasterInitialState.processMessage what=3
,03-21 14:23:46.371   820  1368 V BackupManagerService: Scheduling immediate backup pass
03-21 14:23:46.375   820   820 V BackupManagerService: Running a backup pass
,03-21 14:23:46.376  1294  1311 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,03-21 14:23:46.378  1294  1311 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-21 14:23:46.376   820  1040 V BackupManagerService: clearing pending backups
,03-21 14:23:46.379   820   853 D TelephonyManager: getDataEnabled: retVal=false
,03-21 14:23:46.384  3004  3004 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 14:23:46.385  2543  2543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 14:23:46.389  2543  2543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 14:23:46.392  2543  2660 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 14:23:46.392  2543  2660 I jxcore-log: 
,03-21 14:23:46.393   820  1040 V PerformBackupTask: Beginning backup of 14 targets
,03-21 14:23:46.395  3004  3004 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
03-21 14:23:46.396   820   853 E GpsLocationProvider: No APN found to select.
,03-21 14:23:46.400   820  1040 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-21 14:23:46.407   820  1040 V BackupServiceBinder: doBackup() invoked
,03-21 14:23:46.418   820  1040 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-21 14:23:46.436   820  1097 I ActivityManager: Start proc 3417:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-21 14:23:46.440   820  1040 I BackupRestoreController: Getting widget state for user: 0
,03-21 14:23:46.491  1826  1864 W GmsBackupTransport: Unknown package in backup request: @pm@
03-21 14:23:46.491   820  1271 D AlarmManagerService: Setting time of day to sec=1458566626
03-21 14:23:46.008   820  1271 W AlarmManagerService: Unable to set rtc to 1458566626: Invalid argument
,03-21 14:23:46.009  1826  1864 V GmsBackupTransport: starting performBackup for @pm@
,03-21 14:23:46.020   820  3437 D GpsLocationProvider: NTP server returned: 1458566626008 (Mon Mar 21 14:23:46 GMT+01:00 2016) reference: 168416 certainty: 17 system time offset: -12
,03-21 14:23:46.036  1826  1864 V GmsBackupTransport: performBackup done for @pm@
,03-21 14:23:46.043  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:46.067  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-21 14:23:46.067  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:46.067  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:46.067  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:46.098   820  1292 I ActivityManager: Start proc 3450:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver,
,03-21 14:23:46.102  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:46.117  1768  3442 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-21 14:23:46.140  1249  1716 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:46.140  1249  1716 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:46.140  1249  1716 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:46.140  1249  1716 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 14:23:46.140  1249  1716 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 14:23:46.140  1249  1716 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 14:23:46.140  1249  1716 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:23:46.147  1826  1845 W GmsBackupTransport: Error sending final backup to server: 
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 14:23:46.147  1826  1845 W GmsBackupTransport: 	... 1 more
,03-21 14:23:46.149   820  1040 D BackupManagerService: Now staging backup of com.google.android.talk
,03-21 14:23:46.152   820  3375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Mar 2016 13:23:46 GMT], X-Android-Received-Millis=[1458566626152], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458566626095]}
03-21 14:23:46.152   820  3375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-21 14:23:46.152   820  1023 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,03-21 14:23:46.153   820  1023 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
,03-21 14:23:46.153   820  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 14:23:46.153   820  1023 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-21 14:23:46.153   820  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-21 14:23:46.154   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-21 14:23:46.154  1063  1557 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-21 14:23:46.162   820  1040 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-21 14:23:46.163  3450  3450 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-21 14:23:46.167   820  1040 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-21 14:23:46.171   820  1040 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-21 14:23:46.173   820  1040 D BackupManagerService: Now staging backup of com.google.android.gm
,03-21 14:23:46.179  3450  3450 D SprintDMHelper: simOperator:  IMSI: null
03-21 14:23:46.179  3450  3450 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-21 14:23:46.181   820  1040 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-21 14:23:46.183   820  1040 D BackupManagerService: Now staging backup of com.android.nfc
,03-21 14:23:46.186   820  1040 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-21 14:23:46.189   820  1040 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-21 14:23:46.190  1768  3468 W DriveInitializer: Background init thread started
,03-21 14:23:46.191  1768  1768 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-21 14:23:46.191   820  1040 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-21 14:23:46.193   820  1040 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-21 14:23:46.195  1768  1768 D SystemUpdateService: onCreate
,03-21 14:23:46.197  1768  1768 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
03-21 14:23:46.197   820  1040 D BackupManagerService: Now staging backup of com.android.vending
,03-21 14:23:46.199  1768  3469 I SystemUpdateService: active receiver: enabled
,03-21 14:23:46.200   820  1040 D BackupManagerService: Now staging backup of android
,03-21 14:23:46.200  1768  3469 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-21 14:23:46.202  1768  3469 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: false
,03-21 14:23:46.202  1768  3469 I SystemUpdateService: now status is 0 (complete)
03-21 14:23:46.202  1768  3469 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-21 14:23:46.202  1768  3469 I SystemUpdateService: file has been verified
03-21 14:23:46.202  1768  3469 I SystemUpdateService: OTA package size = 25802302
,03-21 14:23:46.203   820  1040 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-21 14:23:46.205  1768  3469 I SystemUpdateService: showing system update notification
,03-21 14:23:46.209  1826  1888 I GmsBackupTransport: Next backup will happen in 43199934 millis.
,03-21 14:23:46.213   820  1040 I BackupManagerService: Backup pass finished.
,03-21 14:23:46.216   820   820 I ValidateNoPeople: skipping global notification
,03-21 14:23:46.246  1249  1715 I art     : Explicit concurrent mark sweep GC freed 24285(1240KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 739us total 21.326ms
,03-21 14:23:46.263   820   853 I art     : Explicit concurrent mark sweep GC freed 69181(3MB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 3.072ms total 113.009ms
,03-21 14:23:46.288  1768  3468 W DriveInitializer: Background init thread ended
,03-21 14:23:46.339  1768  3490 I iu.SyncManager: SYNC; picasa accounts
,03-21 14:23:46.347  1768  1768 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-21 14:23:46.352  1768  1768 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-21 14:23:46.354  1768  1768 D SystemUpdateService: onDestroy
,03-21 14:23:46.359  1768  3490 I iu.UploadsManager: num queued entries: 0
,03-21 14:23:46.360  1768  3490 I iu.UploadsManager: num updated entries: 0
,03-21 14:23:46.361  1768  3490 I iu.SyncManager: NEXT; no task
,03-21 14:23:46.368  1768  1768 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-21 14:23:46.369  1768  1768 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-21 14:23:46.405   820  1097 I ActivityManager: Start proc 3497:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-21 14:23:46.447  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:23:46.447  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:46.447  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:46.447  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:46.450  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:46.462  3201  3485 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 14:23:46.462  3201  3485 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at blb.a(PG:3937)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:23:46.462  3201  3485 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	... 12 more
03-21 14:23:46.462  3201  3485 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at fal.a(PG:38)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:23:46.462  3201  3485 E HttpOperation: 	... 14 more
,03-21 14:23:46.493  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:23:46.493  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:46.494  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:46.494  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:46.501  3497  3497 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-21 14:23:46.501  3497  3497 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:23:46.501  3497  3497 I GAv4    :   adb logcat -s GAv4
,03-21 14:23:46.509   820   853 I ActivityManager: Start proc 3523:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-21 14:23:46.511  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:46.512  3497  3497 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:46.520  3201  3485 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 14:23:46.520  3201  3485 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at hec.a(PG:42)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at hee.a(PG:102)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at czr.a(PG:65)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at kka.a(PG:108)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at czp.a(PG:19176)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:23:46.520  3201  3485 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	... 15 more
03-21 14:23:46.520  3201  3485 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at fal.a(PG:38)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:23:46.520  3201  3485 E HttpOperation: 	... 17 more
03-21 14:23:46.520  3201  3485 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 14:23:46.520  3201  3485 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at hec.a(PG:42)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at hee.a(PG:102)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at czr.a(PG:65)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at kka.a(PG:108)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	... 15 more
03-21 14:23:46.520  3201  3485 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at fal.a(PG:38)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 14:23:46.520  3201  3485 E ExperimentLoader: 	... 17 more
03-21 14:23:46.536  3497  3497 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-21 14:23:46.539  3273  3494 I Babel   : connection state changed from DISCONNECTED to CONNECTED
03-21 14:23:46.541   820  1288 I ActivityManager: Killing 2450:com.google.android.apps.maps/u0a65 (adj 15): empty #17
03-21 14:23:46.543  3497  3541 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:46.609   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 38160, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
03-21 14:23:46.609   820  1288 I ActivityManager: Killing 3069:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-21 14:23:46.628  1249  3515 D GCM     : Connected
,03-21 14:23:46.721  1249  3515 D GCM     : Message class com.google.f.a.a.p
,03-21 14:23:46.760   820   853 I ActivityManager: Start proc 3545:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-21 14:23:46.914  3523  3577 V KeepSync: Connecting to GoogleApiClient
,03-21 14:23:46.945  3497  3497 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 14:23:46.959  3497  3497 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9355-9356)
03-21 14:23:46.959  3497  3497 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 14:23:46.964  3497  3497 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4a0adfc}
03-21 14:23:46.964  3497  3497 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 14:23:46.965  3497  3497 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 14:23:46.967  1768  3580 W BaseAppContext: Using Auth Proxy for data requests.
03-21 14:23:46.972  1768  3580 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 14:23:46.974  3497  3497 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 14:23:46.975  3497  3497 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 14:23:46.976  3497  3497 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 14:23:46.989  3497  3497 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 14:23:46.992  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-21 14:23:46.992  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:46.992  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:46.992  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:46.995  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:46.997  3497  3497 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-21 14:23:46.997  3497  3497 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 14:23:46.997  3497  3497 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: Handling authorization failure
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 14:23:47.017  1768  3580 E ClientConnectionOperation: 	... 7 more
03-21 14:23:47.019  3523  3577 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-21 14:23:47.022  3523  3577 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:23:47.028  3523  3577 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:23:47.028  3523  3577 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:23:47.052  3497  3595 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-21 14:23:47.056  3497  3497 I NSApplication: Starting up...
,03-21 14:23:47.094   820  1312 I ActivityManager: Start proc 3600:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-21 14:23:47.133  1249  1599 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-21 14:23:47.133  1249  1599 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:47.133  1249  1599 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:47.133  1249  1599 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:47.138  1249  1599 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:47.170  3523  3577 E KeepSync: IOException
03-21 14:23:47.170  3523  3577 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 14:23:47.170  3523  3577 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 14:23:47.170  3523  3577 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 14:23:47.170  3523  3577 E KeepSync: 	... 10 more
,03-21 14:23:47.170  3523  3577 W KeepSync: Sync result 2
,03-21 14:23:47.175   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38166, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:23:47.178   820  1097 I ActivityManager: Killing 3089:com.android.musicfx/u0a18 (adj 15): empty #17
,03-21 14:23:47.376  1249  2318 I art     : Explicit concurrent mark sweep GC freed 14582(860KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 1.026ms total 35.838ms
,03-21 14:23:47.398  3545  3545 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 14:23:47.405  3545  3545 I BooksApp: Created application version: 3.6.8 (30608)
,03-21 14:23:47.452  3545  3627 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 14:23:47.511  1768  3630 I ReminderSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=216:priority=5:group=main]
,03-21 14:23:47.516   820  1292 I ActivityManager: Start proc 3634:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-21 14:23:47.516   820  1292 I ActivityManager: Killing 3156:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-21 14:23:47.614   820  1288 I art     : Explicit concurrent mark sweep GC freed 35816(1578KB) AllocSpace objects, 7(152KB) LOS objects, 32% free, 33MB/49MB, paused 1.208ms total 47.567ms
,03-21 14:23:47.617  3545  3653 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 14:23:47.621   820   853 I ActivityManager: Start proc 3654:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,03-21 14:23:47.680  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:23:47.680  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:47.680  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:47.680  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:47.684  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:47.733  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:23:47.734  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:47.734  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 14:23:47.734  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:47.738  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:47.764  3545  3653 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 14:23:47.766  3545  3627 E BooksSync: Soft error
03-21 14:23:47.766  3545  3627 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:23:47.766  3545  3627 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-21 14:23:47.766  3545  3627 E BooksSync: Sync error
03-21 14:23:47.766  3545  3627 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:23:47.766  3545  3627 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 14:23:47.766  3545  3627 I BooksSync: Finished books sync
,03-21 14:23:47.770   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38167, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:23:47.771   820   835 I ActivityManager: Killing 2885:com.google.android.gm/u0a78 (adj 15): empty #17
,03-21 14:23:47.877   820   835 I ActivityManager: Killing 2863:com.google.android.gms:car/u0a11 (adj 15): empty #18
,03-21 14:23:48.023   820   853 I ActivityManager: Start proc 3671:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,03-21 14:23:48.231  3671  3671 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-21 14:23:48.231  3671  3671 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:23:48.231  3671  3671 I GAv4    :   adb logcat -s GAv4
,03-21 14:23:48.240  3671  3671 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.247  3671  3671 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.250  3671  3697 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.261  3671  3671 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-21 14:23:48.267   820  1140 I ActivityManager: Killing 1394:android.process.acore/u0a5 (adj 15): empty #17
,03-21 14:23:48.356   820  1140 I ActivityManager: Start proc 3703:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-21 14:23:48.376  3671  3671 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:23:48.376  3671  3671 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:23:48.378  3671  3714 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:23:48.378  3671  3714 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:23:48.394  3703  3703 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458566628394
03-21 14:23:48.395  3703  3703 D         : TimeServiceNative: User Time to be set is 1458566628394
03-21 14:23:48.395  3703  3703 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-21 14:23:48.395  3703  3703 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-21 14:23:48.395  3703  3703 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458566628394
03-21 14:23:48.395   373   883 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-21 14:23:48.396  3703  3703 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458566628394
03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458566628394, operation = 0
03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/7/70 9:35:32
,03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:Value read from RTC seconds = 18869732000
03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:new time 1458566628394 
03-21 14:23:48.397   373  3726 D QC-time-services: Daemon: delta 1439696896394 genoff 1439696896394 
03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896394 to memory
,03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-21 14:23:48.397   373  3726 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-21 14:23:48.402   373  3726 D QC-time-services: Updating the TOD offset
03-21 14:23:48.402   373  3726 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896394 to memory
03-21 14:23:48.402   373  3726 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-21 14:23:48.402   373  3726 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-21 14:23:48.404   373  3726 E QC-time-services: Daemon:Update to modem bit set
03-21 14:23:48.404   373  3726 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-21 14:23:48.404   373  3726 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142601828394
,03-21 14:23:48.404  3703  3703 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-21 14:23:48.404  3671  3671 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:23:48.438  3671  3671 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:23:48.466   820  1312 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3bea018a}
,03-21 14:23:48.472   373   883 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-21 14:23:48.478   373   880 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-21 14:23:48.482   820   835 I ActivityManager: Start proc 3735:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-21 14:23:48.486  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:48.489   820  1097 I ActivityManager: Killing 3137:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-21 14:23:48.499   370   370 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 214us total 16.947ms
,03-21 14:23:48.504  3654  3654 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-21 14:23:48.504  3654  3654 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:23:48.504  3654  3654 I GAv4    :   adb logcat -s GAv4
,03-21 14:23:48.511   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 11.251ms
,03-21 14:23:48.521   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.848ms
,03-21 14:23:48.618  3654  3654 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.635  3654  3654 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.642  3654  3654 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
,03-21 14:23:48.644  3654  3754 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.656  3735  3735 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-21 14:23:48.656  3735  3735 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:23:48.656  3735  3735 I GAv4    :   adb logcat -s GAv4
,03-21 14:23:48.675  3735  3735 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.691  3735  3735 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.698  3735  3758 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:48.735   820  1140 I ActivityManager: Killing 3109:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-21 14:23:48.854  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:48.886  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
03-21 14:23:48.886  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:48.886  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:48.886  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:48.889  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:48.926  3273  3273 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:23:48.926  3273  3273 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:23:48.932  1249  1293 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:48.932  1249  1293 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:48.932  1249  1293 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:48.932  1249  1293 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 14:23:48.932  1249  1293 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 14:23:48.932  1249  1293 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 14:23:48.932  1249  1293 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:23:48.933  3671  3730 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
,03-21 14:23:48.934  3654  3654 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:23:48.934  3654  3654 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:23:48.940  3654  3766 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:23:48.940  3654  3766 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: java.io.IOException
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: 	at cjw.b(PG:159)
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: 	at cju.b(PG:5072)
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: 	at dlh.b(PG:239)
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: 	at dlh.a(PG:140)
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: 	at dqo.a(PG:224)
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: 	at dlt.run(PG:9618)
03-21 14:23:48.940  3671  3730 E DefaultHttpIssuer: 	at dlr.run(PG:3031)
,03-21 14:23:48.943   820  1022 D WifiService: New client listening to asynchronous messages
,03-21 14:23:48.962  3654  3654 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:23:48.975  3671  3730 E BaseSyncManager: AuthenticatorException
03-21 14:23:48.975  3671  3730 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 14:23:48.975  3671  3730 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 14:23:48.975  3671  3730 E BaseSyncManager: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 14:23:48.975  3671  3730 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 14:23:48.975  3671  3730 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 14:23:48.975  3671  3730 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:23:48.983   820  1288 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3bea018a}
,03-21 14:23:48.995  3654  3654 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:23:49.000  1768  1918 I art     : Explicit concurrent mark sweep GC freed 14797(1137KB) AllocSpace objects, 17(272KB) LOS objects, 21% free, 28MB/36MB, paused 930us total 107.623ms
,03-21 14:23:49.026  1768  1768 V Herrevad: NQAS connected
,03-21 14:23:49.089   820   853 I ActivityManager: Start proc 3793:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,03-21 14:23:49.094  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:49.114  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-21 14:23:49.114  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:49.114  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:49.114  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:49.159   820  1312 I art     : Explicit concurrent mark sweep GC freed 17838(851KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.197ms total 47.999ms
03-21 14:23:49.159   820  1312 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@12866c54}
,03-21 14:23:49.162  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:49.172  3273  3776 E Babel   : UserRecoverableAuthException.
,03-21 14:23:49.175  3273  3776 E Babel   : eei: BadAuthentication
03-21 14:23:49.175  3273  3776 E Babel   : 	at eeg.a(Unknown Source)
03-21 14:23:49.175  3273  3776 E Babel   : 	at eeg.a(Unknown Source)
03-21 14:23:49.175  3273  3776 E Babel   : 	at eeg.a(Unknown Source)
03-21 14:23:49.175  3273  3776 E Babel   : 	at g.a(Unknown Source)
03-21 14:23:49.175  3273  3776 E Babel   : 	at cae.a(SourceFile:3089)
03-21 14:23:49.175  3273  3776 E Babel   : 	at cae.a(SourceFile:1131)
03-21 14:23:49.175  3273  3776 E Babel   : 	at cws.a(SourceFile:4333)
03-21 14:23:49.175  3273  3776 E Babel   : 	at cws.a(SourceFile:1419)
03-21 14:23:49.175  3273  3776 E Babel   : 	at crl.a(SourceFile:492)
03-21 14:23:49.175  3273  3776 E Babel   : 	at crl.a(SourceFile:1468)
03-21 14:23:49.175  3273  3776 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 14:23:49.175  3273  3776 E Babel   : 	at cas.b(SourceFile:106)
03-21 14:23:49.175  3273  3776 E Babel   : 	at cap.d(SourceFile:335)
03-21 14:23:49.175  3273  3776 E Babel   : 	at caq.run(SourceFile:81)
,03-21 14:23:49.176  3273  3776 E Babel   : Error getting auth token
,03-21 14:23:49.177  3273  3776 E Babel   : dvm
03-21 14:23:49.177  3273  3776 E Babel   : 	at g.a(Unknown Source)
03-21 14:23:49.177  3273  3776 E Babel   : 	at cae.a(SourceFile:3089)
03-21 14:23:49.177  3273  3776 E Babel   : 	at cae.a(SourceFile:1131)
03-21 14:23:49.177  3273  3776 E Babel   : 	at cws.a(SourceFile:4333)
03-21 14:23:49.177  3273  3776 E Babel   : 	at cws.a(SourceFile:1419)
03-21 14:23:49.177  3273  3776 E Babel   : 	at crl.a(SourceFile:492)
03-21 14:23:49.177  3273  3776 E Babel   : 	at crl.a(SourceFile:1468)
03-21 14:23:49.177  3273  3776 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 14:23:49.177  3273  3776 E Babel   : 	at cas.b(SourceFile:106)
03-21 14:23:49.177  3273  3776 E Babel   : 	at cap.d(SourceFile:335)
03-21 14:23:49.177  3273  3776 E Babel   : 	at caq.run(SourceFile:81)
,03-21 14:23:49.181  3273  3776 E Babel   : Account registration failed 1-Redacted-21
,03-21 14:23:49.181  3273  3776 E Babel   : cyp: null -- null
03-21 14:23:49.181  3273  3776 E Babel   : 	at cae.a(SourceFile:3121)
03-21 14:23:49.181  3273  3776 E Babel   : 	at cae.a(SourceFile:1131)
03-21 14:23:49.181  3273  3776 E Babel   : 	at cws.a(SourceFile:4333)
03-21 14:23:49.181  3273  3776 E Babel   : 	at cws.a(SourceFile:1419)
03-21 14:23:49.181  3273  3776 E Babel   : 	at crl.a(SourceFile:492)
03-21 14:23:49.181  3273  3776 E Babel   : 	at crl.a(SourceFile:1468)
03-21 14:23:49.181  3273  3776 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 14:23:49.181  3273  3776 E Babel   : 	at cas.b(SourceFile:106)
03-21 14:23:49.181  3273  3776 E Babel   : 	at cap.d(SourceFile:335)
03-21 14:23:49.181  3273  3776 E Babel   : 	at caq.run(SourceFile:81)
,03-21 14:23:49.202  3273  3776 I art     : Note: end time exceeds epoch: 
,03-21 14:23:49.206  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-21 14:23:49.206  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:49.206  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:49.206  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:49.210  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:49.221  1249  2318 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 14:23:49.240  3273  3814 E Babel   : Unexpected exception while authenticating.
,03-21 14:23:49.240  3273  3814 E Babel   : eej: User intervention required. Notification has been pushed.
03-21 14:23:49.240  3273  3814 E Babel   : 	at eeg.b(Unknown Source)
03-21 14:23:49.240  3273  3814 E Babel   : 	at eeg.b(Unknown Source)
03-21 14:23:49.240  3273  3814 E Babel   : 	at g.a(Unknown Source)
03-21 14:23:49.240  3273  3814 E Babel   : 	at cae.b(SourceFile:1146)
03-21 14:23:49.240  3273  3814 E Babel   : 	at dcg.run(SourceFile:5617)
03-21 14:23:49.240  3273  3814 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:23:49.240  3273  3814 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:23:49.240  3273  3814 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-21 14:23:49.351  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:49.368  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
,03-21 14:23:49.369  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:49.369  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:49.369  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:49.374  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:49.400  1249  1715 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:49.400  1249  1715 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:49.400  1249  1715 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:49.400  1249  1715 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 14:23:49.400  1249  1715 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 14:23:49.400  1249  1715 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 14:23:49.400  1249  1715 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:23:49.402  3654  3811 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
,03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: java.io.IOException
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at fur.b(PG:162)
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at fup.b(PG:6072)
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at gtb.b(PG:213)
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at gtb.a(PG:125)
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at gyh.a(PG:224)
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:618)
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at gtm.run(PG:2507)
03-21 14:23:49.409  3654  3811 E DefaultHttpIssuer: 	at gtk.run(PG:3031)
,03-21 14:23:49.410  3654  3811 E BaseSyncManager: AuthenticatorException,
03-21 14:23:49.410  3654  3811 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 14:23:49.410  3654  3811 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 14:23:49.410  3654  3811 E BaseSyncManager: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 14:23:49.410  3654  3811 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 14:23:49.410  3654  3811 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 14:23:49.410  3654  3811 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:23:49.413   820  1288 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@12866c54}
,03-21 14:23:50.007  3793  3820 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
03-21 14:23:50.007  3793  3820 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:23:50.007  3793  3820 I GAv4    :   adb logcat -s GAv4
,03-21 14:23:50.022  3793  3820 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:50.032  3793  3820 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:50.052  3793  3832 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:23:50.062  3793  3820 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,03-21 14:23:50.257   820   835 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@132e7b9e}
,03-21 14:23:50.348  3793  3837 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-21 14:23:50.349  3793  3837 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-21 14:23:50.349  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:50.385  3793  3837 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:23:50.416  3793  3837 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:23:50.484  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:50.501  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.sheets, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me,
03-21 14:23:50.501  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:50.501  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:50.501  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:50.504  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:50.532  1249  1293 I art     : Explicit concurrent mark sweep GC freed 20216(1334KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 1.277ms total 26.060ms
,03-21 14:23:50.572  1249  1293 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:50.572  1249  1293 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:50.572  1249  1293 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:50.572  1249  1293 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 14:23:50.572  1249  1293 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 14:23:50.572  1249  1293 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 14:23:50.572  1249  1293 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:23:50.576  3793  3847 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
,03-21 14:23:50.577  3793  3847 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
,03-21 14:23:50.584  3793  3847 E BaseSyncManager: AuthenticatorException
03-21 14:23:50.584  3793  3847 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 14:23:50.584  3793  3847 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 14:23:50.584  3793  3847 E BaseSyncManager: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 14:23:50.584  3793  3847 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 14:23:50.584  3793  3847 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 14:23:50.584  3793  3847 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:23:50.586   820  1369 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@132e7b9e}
,03-21 14:23:50.607   820  1140 I ActivityManager: Killing 3239:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-21 14:23:51.095   820   854 I ActivityManager: Start proc 3857:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,03-21 14:23:51.168  3857  3857 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-21 14:23:51.211  3857  3857 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@6419928(com.android.providers.calendar.CalendarProvider2@3889641)
,03-21 14:23:51.241  3857  3875 E SQLiteLog: (284) automatic index on view_events(_id)
,03-21 14:23:52.268  3857  3857 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-21 14:23:52.268  3857  3857 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 14:23:52.413  3545  3624 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 14:23:53.192  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:53.326  3417  3881 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 14:23:53.333  1249  3882 I VacuumService: Vacuum at: now=1458566633333 tag=VacuumService
,03-21 14:23:53.387  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-21 14:23:53.387  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:53.387  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:53.387  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:53.392  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:53.409  3417  3881 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source),
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 14:23:53.411  3417  3881 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110),
,03-21 14:23:53.557  1249  3883 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 14:23:53.580  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:54.036  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:54.160  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:54.238   820  1324 I ActivityManager: Killing 2825:com.android.vending/u0a19 (adj 15): empty #17
,03-21 14:23:54.494  1249  3883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 14:23:54.495  1249  3883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:54.495  1249  3883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:54.495  1249  3883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:54.500  1249  3883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 14:23:54.535  1249  3883 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 14:23:54.535  1249  3883 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 14:23:54.535  1249  3883 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 14:23:54.725  1249  3883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 14:23:54.726  1249  3883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:54.726  1249  3883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:54.726  1249  3883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:54.736  1249  3883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:54.804  1249  3883 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 14:23:54.804  1249  3883 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 14:23:54.804  1249  3883 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 14:23:55.117  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:55.236  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:55.372  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:55.519  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:55.674  1249  3883 W Uploader:  no longer exists, so no auth token.
,03-21 14:23:55.980  1249  3883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 14:23:55.981  1249  3883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:55.981  1249  3883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:55.981  1249  3883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:55.992  1249  3883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:56.069  1249  3883 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 14:23:56.069  1249  3883 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 14:23:56.069  1249  3883 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 14:23:56.277  1249  3883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 14:23:56.277  1249  3883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:56.277  1249  3883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:56.278  1249  3883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:56.282  1249  3883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:56.335  1249  3883 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 14:23:56.335  1249  3883 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 14:23:56.335  1249  3883 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 14:23:56.482  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:56.768  1249  3883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 14:23:56.769  1249  3883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:56.769  1249  3883 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 14:23:56.770  1249  3883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:56.782  1249  3883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:56.911   820   836 I art     : Explicit concurrent mark sweep GC freed 26070(1236KB) AllocSpace objects, 8(316KB) LOS objects, 31% free, 34MB/50MB, paused 1.489ms total 78.847ms
,03-21 14:23:56.941  1249  3883 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 14:23:56.941  1249  3883 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 14:23:56.941  1249  3883 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 14:23:57.075  1249  3883 W Uploader: No account for auth token provided
,03-21 14:23:57.206  1249  3883 W Uploader: No account for auth token provided,
,03-21 14:23:57.379   820   836 I ActivityManager: Killing 3450:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-21 14:23:57.485   820   836 I ActivityManager: Killing 3004:com.google.android.music:main/u0a66 (adj 15): empty #18
,03-21 14:23:57.765   820  1292 I ActivityManager: Start proc 3888:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-21 14:23:57.965  3888  3888 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 14:23:58.063  3888  3888 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-21 14:23:58.177   820  1097 I ActivityManager: Start proc 3924:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-21 14:23:58.213  3888  3888 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 14:23:58.214  3888  3888 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 14:23:58.227  3924  3924 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:23:58.227  3924  3924 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:23:58.265   820  1140 I ActivityManager: Killing 3497:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-21 14:23:58.272  3924  3924 I MultiDex: VM with version 2.1.0 has multidex support
03-21 14:23:58.272  3924  3924 I MultiDex: install
,03-21 14:23:58.272  3924  3924 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 14:23:58.274  3888  3903 D Finsky  : [399] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-21 14:23:58.387  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:58.393  3888  3888 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-21 14:23:58.394  3888  3888 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-21 14:23:58.408  3888  3888 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-21 14:23:58.423  3924  3924 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:23:58.439  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 14:23:58.439  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:58.439  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:58.439  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:58.445  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:58.446  3888  3888 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-21 14:23:58.465  3888  3903 D Finsky  : [399] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-21 14:23:58.496  3924  3924 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:23:58.505  1249  2113 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-21 14:23:58.512  1249  1249 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 14:23:58.522  1768  1768 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 14:23:58.589   820  1368 I ActivityManager: Start proc 3952:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-21 14:23:58.639  1768  3969 D LocationInitializer: Restart initialization of location
,03-21 14:23:58.646  3952  3952 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:23:58.646  3952  3952 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:23:58.680  3952  3952 I MultiDex: VM with version 2.1.0 has multidex support
03-21 14:23:58.680  3952  3952 I MultiDex: install
03-21 14:23:58.680  3952  3952 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 14:23:58.694  3952  3952 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 14:23:58.724  3952  3952 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:23:58.728  1249  2595 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-21 14:23:58.731  1249  1249 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 14:23:58.735  1768  1768 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 14:23:58.742  3952  3952 D WearableService: callingUid 10011, callindPid: 3952
,03-21 14:23:58.754  1768  3974 D LocationInitializer: Restart initialization of location
,03-21 14:23:58.763  1826  2107 E MDM     : [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 14:23:58.767  1826  2107 E MDM     : [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 14:23:58.932  3888  3888 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-21 14:23:59.085  3888  3888 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-21 14:23:59.112  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:59.173  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 14:23:59.173  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:59.174  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:59.174  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:59.185  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 14:23:59.217  3888  3888 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 14:23:59.229  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:59.285  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-21 14:23:59.285  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:59.286  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:59.286  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:59.296  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:59.359  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:59.471  1249  1249 I art     : Explicit concurrent mark sweep GC freed 59329(3MB) AllocSpace objects, 13(1362KB) LOS objects, 36% free, 27MB/43MB, paused 1.917ms total 72.209ms
,03-21 14:23:59.511  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 14:23:59.512  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:59.512  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:59.512  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:59.526  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:59.539  3888  3888 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 14:23:59.757  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:59.814  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-21 14:23:59.814  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:23:59.815  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:23:59.815  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:23:59.825  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:23:59.864  3888  3888 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 14:23:59.873  3888  3888 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-21 14:23:59.891  3888  3888 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-21 14:23:59.895  3888  3888 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 851 minutes (failures=5)
,03-21 14:23:59.910  1826  1841 D DeviceConnectionService: client connected with version: 7571000
,03-21 14:24:03.792   820  1292 I ActivityManager: Killing 3600:com.android.chrome/u0a40 (adj 15): empty #17
,03-21 14:24:04.025   820  1368 I ActivityManager: Killing 3201:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,03-21 14:24:04.762  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:24:19.887  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:19.954  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-21 14:24:19.954  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:19.955  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:19.955  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:19.961  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:19.991  3888  3888 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-21 14:24:19.993  3888  3888 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-21 14:24:19.995  3888  3888 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-21 14:24:22.114  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:24:27.422  3417  3991 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 14:24:27.502  1249  1599 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-21 14:24:27.503  1249  1599 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:27.503  1249  1599 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:27.503  1249  1599 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:27.515  1249  1599 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:27.540  3417  3991 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 14:24:27.542  3417  3991 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 14:24:41.534  1225  1439 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-21 14:24:41.534  1225  1439 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-21 14:24:41.575  1249  1249 I ConfigService: onCreate
,03-21 14:24:46.105   820   853 I ActivityManager: Start proc 3996:com.google.android.apps.plus/u0a74 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,03-21 14:24:46.169  3996  3996 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 14:24:46.302   820   835 I art     : Explicit concurrent mark sweep GC freed 27325(1252KB) AllocSpace objects, 8(787KB) LOS objects, 32% free, 33MB/49MB, paused 3.196ms total 69.126ms
,03-21 14:24:46.340  3523  4015 V KeepSync: Connecting to GoogleApiClient
,03-21 14:24:46.401  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-21 14:24:46.401  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 14:24:46.401  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:46.401  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
03-21 14:24:46.405  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:46.444   820  1368 I ActivityManager: Start proc 4021:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: Handling authorization failure
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 14:24:46.460  1768  4017 E ClientConnectionOperation: 	... 7 more
,03-21 14:24:46.462  3523  4015 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-21 14:24:46.465  3523  4015 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:24:46.480  3523  4015 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:24:46.482  3523  4015 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:24:46.550  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-21 14:24:46.551  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:46.551  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:46.551  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:46.554  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:46.569  4021  4045 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-21 14:24:46.578  3523  4015 E KeepSync: IOException
03-21 14:24:46.578  3523  4015 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 14:24:46.578  3523  4015 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 14:24:46.578  3523  4015 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 14:24:46.578  3523  4015 E KeepSync: 	... 10 more
03-21 14:24:46.578  3523  4015 W KeepSync: Sync result 2
,03-21 14:24:46.584   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 200184, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:24:46.634  3545  4049 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 14:24:46.644  3545  4050 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 14:24:46.664  1249  1249 I ConfigService: onDestroy
,03-21 14:24:46.665  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:24:46.665  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:46.665  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:46.665  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:46.669  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:46.681  1249  1599 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:24:46.681  1249  1599 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:46.681  1249  1599 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:46.681  1249  1599 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:46.684  1249  1599 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:46.702  3996  4035 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 14:24:46.702  3996  4035 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at blb.a(PG:3937)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at czp.a(PG:9087)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:24:46.702  3996  4035 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	... 12 more
03-21 14:24:46.702  3996  4035 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at fal.a(PG:38)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:24:46.702  3996  4035 E HttpOperation: 	... 14 more
,03-21 14:24:46.716  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:24:46.716  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:46.716  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:46.716  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:46.719  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:46.731  3545  4050 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 14:24:46.732  3545  4049 E BooksSync: Soft error
03-21 14:24:46.732  3545  4049 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:24:46.732  3545  4049 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 14:24:46.733  3545  4049 E BooksSync: Sync error
03-21 14:24:46.733  3545  4049 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:24:46.733  3545  4049 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 14:24:46.733  3545  4049 I BooksSync: Finished books sync
,03-21 14:24:46.745   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202420, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:24:46.797  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:24:46.798  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:46.798  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:46.798  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:46.801  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:46.812  3996  4054 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 14:24:46.812  3996  4054 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at blb.a(PG:3937)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:24:46.812  3996  4054 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	... 12 more
03-21 14:24:46.812  3996  4054 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at fal.a(PG:38)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:24:46.812  3996  4054 E HttpOperation: 	... 14 more
,03-21 14:24:46.845  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-21 14:24:46.845  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:24:46.845  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:24:46.845  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:24:46.849  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:24:46.863  3996  4054 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 14:24:46.863  3996  4054 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at hec.a(PG:42)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at hee.a(PG:102)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at czr.a(PG:65)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at kka.a(PG:108)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at czp.a(PG:19176)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:24:46.863  3996  4054 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	... 15 more
03-21 14:24:46.863  3996  4054 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at fal.a(PG:38)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:24:46.863  3996  4054 E HttpOperation: 	... 17 more
,03-21 14:24:46.865  3996  4054 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 14:24:46.865  3996  4054 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at hec.a(PG:42)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at hee.a(PG:102)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: ,	at czr.a(PG:65)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at kka.a(PG:108)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: ,	at jdj.a(PG:1125)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	... 15 more
03-21 14:24:46.865  3996  4054 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at fal.a(PG:38)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 14:24:46.865  3996  4054 E ExperimentLoader: 	... 17 more
,03-21 14:24:46.976   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 169006, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:24:46.982   820  1292 I ActivityManager: Killing 3703:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-21 14:24:47.102   820  1312 I ActivityManager: Killing 3735:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-21 14:24:47.312   820  1312 E libprocessgroup: failed to kill 1 processes for processgroup 3735
,03-21 14:25:04.761  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-21 14:25:46.622  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:25:46.622  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:25:46.622  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:25:46.622  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:25:46.633  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:25:46.671  3996  4069 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
03-21 14:25:46.671  3996  4069 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at jdm.a(PG:82),
,03-21 14:25:46.671  3996  4069 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:25:46.671  3996  4069 E HttpOperation: ,	at jcn.a(PG:1379)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:25:46.671  3996  4069 E HttpOperation: ,	at blb.a(PG:3937)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:25:46.671  3996  4069 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at jdj.a(PG:4091)
,03-21 14:25:46.671  3996  4069 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	... 12 more
03-21 14:25:46.671  3996  4069 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at fal.a(PG:38)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:25:46.671  3996  4069 E HttpOperation: 	... 14 more
,03-21 14:25:46.735  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-21 14:25:46.736  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:25:46.736  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:25:46.736  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:25:46.741  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:25:46.756  3996  4069 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 14:25:46.756  3996  4069 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at hec.a(PG:42)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at hee.a(PG:102)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at czr.a(PG:65)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at kka.a(PG:108)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at czp.a(PG:19176)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:25:46.756  3996  4069 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	... 15 more
03-21 14:25:46.756  3996  4069 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at fal.a(PG:38)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:25:46.756  3996  4069 E HttpOperation: 	... 17 more
03-21 14:25:46.757  3996  4069 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 14:25:46.757  3996  4069 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at hec.a(PG:42)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at hee.a(PG:102)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at czr.a(PG:65)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at kka.a(PG:108)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	... 15 more
03-21 14:25:46.757  3996  4069 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at fal.a(PG:38)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 14:25:46.757  3996  4069 E ExperimentLoader: 	... 17 more
,03-21 14:25:46.862   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 262186, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:25:50.533  3417  4074 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 14:25:50.645  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-21 14:25:50.645  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:25:50.645  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:25:50.646  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:25:50.660  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:25:50.725  1249  1715 I art     : Explicit concurrent mark sweep GC freed 41825(2MB) AllocSpace objects, 14(1543KB) LOS objects, 37% free, 26MB/42MB, paused 2.162ms total 57.160ms
,03-21 14:25:50.754  3417  4074 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 14:25:50.755  3417  4074 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 14:26:04.762  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:26:16.353  3523  4083 V KeepSync: Connecting to GoogleApiClient
,03-21 14:26:16.402   820   820 I art     : Explicit concurrent mark sweep GC freed 39662(1694KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 2.265ms total 85.986ms
,03-21 14:26:16.407  3545  4086 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 14:26:16.455  3545  4089 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 14:26:16.458  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-21 14:26:16.458  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:26:16.458  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:26:16.458  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:26:16.461  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: Handling authorization failure
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 14:26:16.474  1768  4085 E ClientConnectionOperation: 	... 7 more
,03-21 14:26:16.476  3523  4083 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-21 14:26:16.480  3523  4083 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:26:16.485  3523  4083 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-21 14:26:16.486  3523  4083 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:26:16.492  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:26:16.492  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:26:16.492  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:26:16.492  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:26:16.497  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:26:16.543  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-21 14:26:16.543  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:26:16.543  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:26:16.543  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:26:16.547  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:26:16.559  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:26:16.559  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:26:16.559  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:26:16.559  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:26:16.563  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:26:16.578  3545  4089 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 14:26:16.580  3545  4086 E BooksSync: Soft error
03-21 14:26:16.580  3545  4086 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:26:16.580  3545  4086 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-21 14:26:16.580  3545  4086 E BooksSync: Sync error
03-21 14:26:16.580  3545  4086 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:26:16.580  3545  4086 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 14:26:16.580  3545  4086 I BooksSync: Finished books sync
,03-21 14:26:16.593   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 293648, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:26:16.606  3523  4083 E KeepSync: IOException
03-21 14:26:16.606  3523  4083 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 14:26:16.606  3523  4083 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 14:26:16.606  3523  4083 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 14:26:16.606  3523  4083 E KeepSync: 	... 10 more
03-21 14:26:16.606  3523  4083 W KeepSync: Sync result 2
,03-21 14:26:16.616   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 290205, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:26:22.435  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:27:04.765  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:27:16.507  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-21 14:27:16.507  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:27:16.508  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:27:16.508  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:27:16.522  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:27:16.558  3996  4108 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 14:27:16.558  3996  4108 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at blb.a(PG:3937)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:27:16.558  3996  4108 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	... 12 more
03-21 14:27:16.558  3996  4108 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at fal.a(PG:38)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:27:16.558  3996  4108 E HttpOperation: 	... 14 more
,03-21 14:27:16.640  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:27:16.641  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:27:16.641  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:27:16.641  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:27:16.649  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 14:27:16.679  3996  4108 E HttpOperation: [getmobileexperiments] Unexpected exception,
03-21 14:27:16.679  3996  4108 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at hec.a(PG:42)
,03-21 14:27:16.679  3996  4108 E HttpOperation: 	at hee.a(PG:102)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at czr.a(PG:65)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at kka.a(PG:108)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at czp.a(PG:19176)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:27:16.679  3996  4108 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	... 15 more
03-21 14:27:16.679  3996  4108 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at fal.a(PG:38)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:27:16.679  3996  4108 E HttpOperation: 	... 17 more
03-21 14:27:16.680  3996  4108 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 14:27:16.680  3996  4108 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at hec.a(PG:42)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at hee.a(PG:102)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at czr.a(PG:65)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at kka.a(PG:108)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jdj.a(PG:1125)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	... 15 more
03-21 14:27:16.680  3996  4108 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at fal.a(PG:38)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 14:27:16.680  3996  4108 E ExperimentLoader: 	... 17 more
,03-21 14:27:16.857   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 354885, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:27:22.594  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:28:00.305  3417  4116 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 14:28:00.395  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-21 14:28:00.396  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 14:28:00.396  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:28:00.396  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:28:00.406  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:28:00.434  3417  4116 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 14:28:00.436  3417  4116 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 14:28:04.761  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:28:19.157  3523  4122 V KeepSync: Connecting to GoogleApiClient
,03-21 14:28:19.309  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
03-21 14:28:19.310  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:28:19.310  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:28:19.310  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:28:19.325  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: Handling authorization failure
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 14:28:19.365  1768  4124 E ClientConnectionOperation: 	... 7 more
03-21 14:28:19.371  3523  4122 V KeepSync: GoogleApiClient failed to connect with error code: 4,
03-21 14:28:19.378  3523  4122 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:28:19.390  3523  4122 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:28:19.391  3523  4122 E SQLiteLog: (284) automatic index on blob_node(is_deleted),
,03-21 14:28:19.481  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-21 14:28:19.482  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:28:19.482  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:28:19.482  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:28:19.492  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:28:19.553  3523  4122 E KeepSync: IOException
03-21 14:28:19.553  3523  4122 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 14:28:19.553  3523  4122 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 14:28:19.553  3523  4122 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 14:28:19.553  3523  4122 E KeepSync: 	... 10 more
03-21 14:28:19.553  3523  4122 W KeepSync: Sync result 2
,03-21 14:28:19.568   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 441461, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:28:22.753  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:28:49.199  3545  4132 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 14:28:49.239  3545  4133 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 14:28:49.343  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 14:28:49.344  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:28:49.344  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 14:28:49.345  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:28:49.357  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:28:49.494  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 14:28:49.495  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:28:49.495  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:28:49.495  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:28:49.504  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:28:49.539  3545  4133 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 14:28:49.542  3545  4132 E BooksSync: Soft error
03-21 14:28:49.542  3545  4132 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:28:49.542  3545  4132 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 14:28:49.543  3545  4132 E BooksSync: Sync error
03-21 14:28:49.543  3545  4132 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:28:49.543  3545  4132 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-21 14:28:49.543  3545  4132 I BooksSync: Finished books sync
,03-21 14:28:49.559   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 448002, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:28:58.089  1249  1249 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:28:58.199   820  1369 I art     : Explicit concurrent mark sweep GC freed 35015(1501KB) AllocSpace objects, 8(316KB) LOS objects, 32% free, 33MB/49MB, paused 1.562ms total 83.707ms
,03-21 14:28:58.274  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 14:28:58.274  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:28:58.274  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:28:58.274  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:28:58.294  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:28:58.340  1249  2318 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 14:28:58.340  1249  2318 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 14:28:58.340  1249  2318 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 14:28:58.340  1249  2318 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 14:28:58.340  1249  2318 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 14:28:58.340  1249  2318 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 14:28:58.340  1249  2318 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:28:58.356  3888  3922 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 14:28:58.356  3888  3922 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 14:28:58.356  3888  3922 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 14:28:58.356  3888  3922 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 14:28:58.356  3888  3922 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 14:28:58.356  3888  3922 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 14:28:58.356  3888  3922 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 14:28:58.386  3888  3922 W System  : Ignoring header User-Agent because its value was null.
,03-21 14:29:04.762  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:29:49.473  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-21 14:29:49.473  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:29:49.474  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 14:29:49.474  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:29:49.488  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:29:49.544  3996  4147 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 14:29:49.544  3996  4147 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at blb.a(PG:3937)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:29:49.544  3996  4147 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	... 12 more
03-21 14:29:49.544  3996  4147 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at fal.a(PG:38)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:29:49.544  3996  4147 E HttpOperation: 	... 14 more
,03-21 14:29:49.615  1249  1715 I art     : Explicit concurrent mark sweep GC freed 49703(2MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 2.294ms total 54.920ms
,03-21 14:29:49.653  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:29:49.654  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:29:49.654  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:29:49.654  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:29:49.663  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:29:49.681  3996  4147 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 14:29:49.681  3996  4147 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at hec.a(PG:42)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at hee.a(PG:102)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at czr.a(PG:65)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at kka.a(PG:108)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at czp.a(PG:19176)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:29:49.681  3996  4147 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	... 15 more
03-21 14:29:49.681  3996  4147 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at fal.a(PG:38)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:29:49.681  3996  4147 E HttpOperation: 	... 17 more
03-21 14:29:49.681  3996  4147 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 14:29:49.681  3996  4147 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at hec.a(PG:42)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at hee.a(PG:102)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at czr.a(PG:65)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at kka.a(PG:108)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	... 15 more
03-21 14:29:49.681  3996  4147 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at fal.a(PG:38)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 14:29:49.681  3996  4147 E ExperimentLoader: 	... 17 more
,03-21 14:29:49.824   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 510506, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:30:04.763  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:30:19.270   820   820 I ActivityManager: Start proc 4155:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,03-21 14:30:19.370  4155  4155 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-21 14:30:19.370  4155  4155 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:30:19.370  4155  4155 I GAv4    :   adb logcat -s GAv4
,03-21 14:30:19.388  4155  4155 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:30:19.400  4155  4155 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:30:19.411  4155  4174 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:30:19.433   820  1097 I ActivityManager: Killing 3634:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-21 14:30:23.074  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:31:04.762  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:31:23.234  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:32:00.628  3417  4192 V GoogleAuthProtoRequest: [349] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 14:32:00.715  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-21 14:32:00.715  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:32:00.715  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:32:00.715  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:32:00.722  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: [349] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: [349] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 14:32:00.737  3417  4192 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 14:32:04.763  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:32:24.518  3523  4200 V KeepSync: Connecting to GoogleApiClient
,03-21 14:32:24.667  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-21 14:32:24.667  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:32:24.668  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 14:32:24.668  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:32:24.680  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: Handling authorization failure
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
,03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
,03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 14:32:24.718  1768  4202 E ClientConnectionOperation: 	... 7 more
03-21 14:32:24.725  3523  4200 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-21 14:32:24.730  3523  4200 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:32:24.749  3523  4200 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:32:24.751  3523  4200 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:32:24.827  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-21 14:32:24.828  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:32:24.828  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:32:24.828  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:32:24.836  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:32:24.890  3523  4200 E KeepSync: IOException
03-21 14:32:24.890  3523  4200 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 14:32:24.890  3523  4200 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 14:32:24.890  3523  4200 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 14:32:24.890  3523  4200 E KeepSync: 	... 10 more
03-21 14:32:24.890  3523  4200 W KeepSync: Sync result 2
,03-21 14:32:24.899   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 686861, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:33:04.764  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:33:23.555  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:33:24.540  3545  4215 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 14:33:24.567  3545  4216 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 14:33:24.641  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 14:33:24.642  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:33:24.642  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:33:24.642  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:33:24.652  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:33:24.788  1249  1599 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:33:24.788  1249  1599 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 14:33:24.788  1249  1599 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:33:24.789  1249  1599 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:33:24.797  1249  1599 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:33:24.825  3545  4216 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 14:33:24.828  3545  4215 E BooksSync: Soft error
03-21 14:33:24.828  3545  4215 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:33:24.828  3545  4215 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-21 14:33:24.829  3545  4215 E BooksSync: Sync error
03-21 14:33:24.829  3545  4215 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:33:24.829  3545  4215 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 14:33:24.829  3545  4215 I BooksSync: Finished books sync
,03-21 14:33:24.845   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 729980, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:34:23.713  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:34:24.798  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:34:24.799  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:34:24.799  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 14:34:24.799  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:34:24.811  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:34:24.859  3996  4229 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 14:34:24.859  3996  4229 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at blb.a(PG:3937)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:34:24.859  3996  4229 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	... 12 more
03-21 14:34:24.859  3996  4229 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at fal.a(PG:38)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:34:24.859  3996  4229 E HttpOperation: 	... 14 more
,03-21 14:34:24.967  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-21 14:34:24.968  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:34:24.968  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:34:24.969  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:34:24.984  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:34:25.026  3996  4229 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 14:34:25.026  3996  4229 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at hec.a(PG:42),
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at hee.a(PG:102)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at czr.a(PG:65)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at kka.a(PG:108)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at czp.a(PG:19176)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:34:25.026  3996  4229 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:34:25.026  3996  4229 E HttpOperation: ,	... 15 more
03-21 14:34:25.026  3996  4229 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at fal.a(PG:38)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:34:25.026  3996  4229 E HttpOperation: 	... 17 more
,03-21 14:34:25.028  3996  4229 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 14:34:25.028  3996  4229 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at hec.a(PG:42)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	,at hee.a(PG:102)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at czr.a(PG:65)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at kka.a(PG:108)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: ,	at czq.run(PG:1686)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: ,	at java.lang.Thread.run(Thread.java:818)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jdj.a(PG:1125)
,03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	... 15 more
03-21 14:34:25.028  3996  4229 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at fal.a(PG:38)
03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	at jdj.a(PG:4089)
,03-21 14:34:25.028  3996  4229 E ExperimentLoader: 	... 17 more
,03-21 14:34:25.170   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 794725, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:35:04.762  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:35:15.471   820  1288 I art     : Explicit concurrent mark sweep GC freed 43702(1907KB) AllocSpace objects, 10(537KB) LOS objects, 32% free, 33MB/49MB, paused 1.693ms total 69.653ms
,03-21 14:35:15.523  1768  4239 I EventLogService: Opted in for usage reporting
03-21 14:35:15.523  1768  4239 I EventLogService: Aggregate from 1458565515249 (log), 1458565515249 (data)
,03-21 14:35:15.660  1768  4239 W EventLogAggregator: Unknown tag: snet_gcore
03-21 14:35:15.660  1768  4239 W EventLogAggregator: Unknown tag: snet_launch_service
,03-21 14:35:15.743  1768  4239 I ServiceDumpSys: dumping service [account]
,03-21 14:35:23.875  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:36:04.762  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:36:45.078  2153  2229 W bt-btm  : Stopping oneshot timer
,03-21 14:37:24.196  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:39:04.761  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:39:24.513  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:40:04.761  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:40:15.862  1249  3515 D GCM     : Message class com.google.f.a.a.i
,03-21 14:40:15.885  3417  4292 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 14:40:15.932  1249  1716 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-21 14:40:15.932  1249  1716 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 14:40:15.932  1249  1716 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:40:15.932  1249  1716 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:40:15.936  1249  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
,03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 14:40:15.951  3417  4292 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 14:40:15.956  1249  4293 I art     : Explicit concurrent mark sweep GC freed 65762(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.177ms total 29.206ms
,03-21 14:40:24.674  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:40:34.747  3523  4297 V KeepSync: Connecting to GoogleApiClient
,03-21 14:40:34.854  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-21 14:40:34.855  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:40:34.855  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:40:34.855  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:40:34.865  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: Handling authorization failure
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 14:40:34.898  1768  4299 E ClientConnectionOperation: 	... 7 more
,03-21 14:40:34.904  3523  4297 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-21 14:40:34.909  3523  4297 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:40:34.927  3523  4297 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-21 14:40:34.927  3523  4297 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 14:40:34.997  1249  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-21 14:40:34.998  1249  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:40:34.999  1249  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:40:34.999  1249  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:40:35.005  1249  2318 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:40:35.066  3523  4297 E KeepSync: IOException
03-21 14:40:35.066  3523  4297 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 14:40:35.066  3523  4297 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 14:40:35.066  3523  4297 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 14:40:35.066  3523  4297 E KeepSync: 	... 10 more
03-21 14:40:35.066  3523  4297 W KeepSync: Sync result 2
,03-21 14:40:35.082   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1177088, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:41:04.760  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:41:24.836  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:41:29.014   820   853 I UsageStatsService: User[0] Flushing usage stats to disk
,03-21 14:42:00.942  3545  4317 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 14:42:00.984  3545  4318 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 14:42:01.084  1249  1599 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 14:42:01.085  1249  1599 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 14:42:01.085  1249  1599 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:42:01.086  1249  1599 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:42:01.106  1249  1599 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:42:01.250  1249  1715 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 14:42:01.250  1249  1715 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:42:01.251  1249  1715 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:42:01.251  1249  1715 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:42:01.263  1249  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:42:01.297  3545  4318 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 14:42:01.302  3545  4317 E BooksSync: Soft error
03-21 14:42:01.302  3545  4317 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:42:01.302  3545  4317 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-21 14:42:01.303  3545  4317 E BooksSync: Sync error
03-21 14:42:01.303  3545  4317 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 14:42:01.303  3545  4317 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 14:42:01.304  3545  4317 I BooksSync: Finished books sync
,03-21 14:42:01.322   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1263290, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:42:04.762  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:42:24.994  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:43:04.761  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:43:10.323  1249  1293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:43:10.323  1249  1293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 14:43:10.323  1249  1293 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:43:10.323  1249  1293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:43:10.328  1249  1293 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:43:10.349  3996  4333 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 14:43:10.349  3996  4333 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	,at jcs.o(PG:406)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at blb.a(PG:3937)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at czp.a(PG:18188)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:43:10.349  3996  4333 E HttpOperation: ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:43:10.349  3996  4333 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	... 12 more
03-21 14:43:10.349  3996  4333 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:43:10.349  3996  4333 E HttpOperation: 	at fal.a(PG:38)
,03-21 14:43:10.349  3996  4333 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:43:10.349  3996  4333 E HttpOperation: 	... 14 more
,03-21 14:43:10.397  1249  1265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 14:43:10.397  1249  1265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 14:43:10.398  1249  1265 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 14:43:10.398  1249  1265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 14:43:10.405  1249  1265 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:43:10.428  3996  4333 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 14:43:10.428  3996  4333 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jdm.a(PG:82)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jcs.o(PG:406)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jcn.a(PG:1379)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jcs.i(PG:143)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at hec.a(PG:42)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at hee.a(PG:102)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at czr.a(PG:65)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at kka.a(PG:108)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at czp.a(PG:19176)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at czp.a(PG:9081)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at czq.run(PG:1686)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:43:10.428  3996  4333 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jdj.a(PG:4091)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jdj.a(PG:1125)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jdm.a(PG:77)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	... 15 more
03-21 14:43:10.428  3996  4333 E HttpOperation: Caused by: faj: BadAuthentication
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at fal.a(PG:38)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	at jdj.a(PG:4089)
03-21 14:43:10.428  3996  4333 E HttpOperation: 	... 17 more
03-21 14:43:10.429  3996  4333 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 14:43:10.429  3996  4333 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at hec.a(PG:42)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at hee.a(PG:102)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at czr.a(PG:65)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at kka.a(PG:108)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	... 15 more
03-21 14:43:10.429  3996  4333 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at fal.a(PG:38)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 14:43:10.429  3996  4333 E ExperimentLoader: 	... 17 more
,03-21 14:43:10.544   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1332575, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 14:43:25.156  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 14:44:25.318  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
