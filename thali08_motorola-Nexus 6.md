#### Test 646138036c5f71d_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
03-31 15:14:03.554   820  1036 D WifiService: New client listening to asynchronous messages
--------- beginning of main
03-31 15:14:03.557  1568  1708 I VelvetNetworkClient: Network connection not availble
03-31 15:14:03.559  1568  1720 I SearchBackgroundTaskFac: refreshing internal icing corpora
03-31 15:14:03.593   820  1367 I ActivityManager: Start proc 2674:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,03-31 15:14:03.613   820  1367 I ActivityManager: Killing 2187:com.android.keychain/1000 (adj 15): empty #17
03-31 15:14:03.614  1568  2697 I UpdateIcingCorporaServi: Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
03-31 15:14:03.623  2674  2674 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-31 15:14:03.673  1568  2697 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 58 ms] updated apps [took 58 ms] 
03-31 15:14:03.765  1568  1901 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-31 15:14:03.785  2674  2710 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-31 15:14:03.785  2674  2710 I Babel_SMS: MmsConfig.loadMmsSettings
03-31 15:14:03.786  2674  2710 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
03-31 15:14:03.786  2674  2710 I Babel_SMS: MmsConfig.loadFromDatabase
03-31 15:14:03.789  1568  1901 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6359-6360)
03-31 15:14:03.789  1568  1901 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 15:14:03.798  2674  2710 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-31 15:14:03.798  2674  2710 I Babel_SMS: MmsConfig.loadFromResources
03-31 15:14:03.800  2674  2710 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-31 15:14:03.800  2674  2710 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
03-31 15:14:03.804  1568  1901 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 15:14:03.805  2702  2702 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 15:14:03.807  2702  2702 D AndroidRuntime: CheckJNI is OFF
03-31 15:14:03.830  2674  2674 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-31 15:14:03.832  2674  2674 I Babel_Crash: startup - clean
03-31 15:14:03.838  2674  2719 I Babel   : deleted: false for 0
03-31 15:14:03.859  1568  1901 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 15:14:03.873  2674  2674 I Babel_telephony: TeleModule.launchCompleted
03-31 15:14:03.875   820  1368 W Telecom : TelecomServiceImpl: null is not visible for the calling user
03-31 15:14:03.880  2674  2674 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 15:14:03.880  2674  2674 W Babel   : BAM#gBA: invalid account id: -1
03-31 15:14:03.880  2674  2674 W Babel   : BAM#gBA: invalid account id: -1
03-31 15:14:03.880  2674  2674 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
03-31 15:14:03.881   820  1916 W Telecom : TelecomServiceImpl: null is not visible for the calling user
03-31 15:14:03.900  2702  2702 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 15:14:03.903   820  1508 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 15:14:03.908   820  1508 V WindowManager: addAppToken: AppWindowToken{8ff0b82 token=Token{159986cd ActivityRecord{30ed0464 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-31 15:14:03.913   820   861 V WindowManager: Adding window Window{344dc285 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1070b47a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 15:14:03.916  1568  1568 I HotwordDetector: Closing mic
03-31 15:14:03.916  1568  1773 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2f996411
03-31 15:14:03.917  2702  2702 D AndroidRuntime: Shutting down VM
03-31 15:14:03.924  2674  2674 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-31 15:14:03.937   820  1912 I ActivityManager: Start proc 2742:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-31 15:14:03.965   357  1780 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 15:14:03.967   357  1780 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 15:14:03.972   357  1029 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 15:14:03.978  1568  1775 I HotwordRecognitionRnr: Stopping hotword detection.
03-31 15:14:03.980  1568  1776 I HotwordRecognitionRnr: Hotword detection finished
03-31 15:14:03.989   820  1368 I ActivityManager: Killing 2208:com.google.android.dialer/u0a13 (adj 15): empty #17
03-31 15:14:03.997  2674  2674 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-31 15:14:04.010  2674  2674 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-31 15:14:04.012  2674  2674 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-31 15:14:04.017  2674  2674 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-31 15:14:04.022  2674  2674 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-31 15:14:04.023  1811  1811 I art     : Explicit concurrent mark sweep GC freed 14632(819KB) AllocSpace objects, 5(80KB) LOS objects, 37% free, 26MB/42MB, paused 1.197ms total 32.965ms
03-31 15:14:04.050  2674  2674 I vclib   : onServiceConnected
03-31 15:14:04.051  2674  2674 W Babel   : Attempted to change video mute state without an active call.
03-31 15:14:04.056   820  1284 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659942163
03-31 15:14:04.056   820  1284 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-31 15:14:04.068  2742  2742 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-31 15:14:04.076   820  1916 I ActivityManager: Start proc 2762:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.FitnessBootReceiver
03-31 15:14:04.077   820  1916 I ActivityManager: Killing 2252:com.motorola.motocit/u0a2 (adj 15): empty #17
,03-31 15:14:04.192  2742  2742 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6761-6763)
03-31 15:14:04.192  2742  2742 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 15:14:04.202  2742  2742 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1db0aa70}
03-31 15:14:04.203  2742  2742 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 15:14:04.203  2742  2742 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 15:14:04.212  2742  2742 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-31 15:14:04.213  2742  2742 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 15:14:04.213  2742  2742 E SysUtils: ApplicationContext is null in ApplicationStatus
03-31 15:14:04.220  2742  2783 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
03-31 15:14:04.227  2742  2742 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-31 15:14:04.234  2742  2742 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 15:14:04.234  2742  2742 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 15:14:04.234  2742  2742 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-31 15:14:04.257  2762  2762 I FitnessApp: Initializers took 0 milliseconds
03-31 15:14:04.280   820  1916 I ActivityManager: Start proc 2788:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
03-31 15:14:04.280   820  1916 I ActivityManager: Killing 1162:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
03-31 15:14:04.291   820   860 D BluetoothManagerService: Message: 20
03-31 15:14:04.291   820   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d706683:true
03-31 15:14:04.467  2742  2742 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 15:14:04.475  2742  2742 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-31 15:14:04.491  2742  2742 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
03-31 15:14:04.503  2742  2742 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 15:14:04.504  2742  2742 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 15:14:04.571  2742  2824 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 15:14:04.574  2742  2742 D Atlas   : Validating map...
03-31 15:14:04.580   820   836 V WindowManager: Adding window Window{3d72e765 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{344dc285 u0 Starting com.test.thalitest})
03-31 15:14:04.582  2742  2803 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-31 15:14:04.600  2788  2788 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-31 15:14:04.600  2788  2788 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 15:14:04.600  2788  2788 I GAv4    :   adb logcat -s GAv4
03-31 15:14:04.614  2788  2788 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-31 15:14:04.622  2788  2788 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-31 15:14:04.626  2788  2827 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-31 15:14:04.627  2742  2824 I OpenGLRenderer: Initialized EGL, version 1.4
03-31 15:14:04.633  2742  2824 D OpenGLRenderer: Enabling debug mode 0
03-31 15:14:04.677  1264  1264 I Keyboard.Facilitator: onFinishInput()
03-31 15:14:04.704  2742  2742 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2742
03-31 15:14:04.710   820  1912 I ActivityManager: Start proc 2833:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver
03-31 15:14:04.711   820  1912 I ActivityManager: Killing 2291:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
03-31 15:14:04.789  2742  2742 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-31 15:14:04.817   820   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +901ms
03-31 15:14:04.875  2742  2832 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580521472
03-31 15:14:04.883  2742  2832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 15:14:04.883  2742  2832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 15:14:04.883  2742  2832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 15:14:04.883  2742  2832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 15:14:04.883  2742  2832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 15:14:04.883  2742  2832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b56e885 added. We now have 1 listener(s)
03-31 15:14:04.883   820  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 15:14:04.886  2742  2832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
03-31 15:14:04.887  2742  2832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 15:14:04.887  2742  2832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 15:14:04.887  2742  2832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 15:14:04.890  2742  2832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@172939e8 added. We now have 1 listener(s)
03-31 15:14:04.890  2742  2832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-31 15:14:04.895   820  1036 D WifiService: New client listening to asynchronous messages
03-31 15:14:04.903  2742  2832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-31 15:14:04.904  2742  2832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 15:14:04.904  2742  2832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 15:14:04.904  2742  2832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 15:14:04.904  2742  2832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-31 15:14:04.908  2742  2832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 15:14:04.909   820  1367 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 15:14:04.910  2742  2832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-31 15:14:04.918  2742  2832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-31 15:14:04.918  2742  2832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 15:14:04.918  2742  2832 D io.jxcore.node.ConnectivityMonitor: start: OK
03-31 15:14:04.921  2742  2742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 15:14:04.925  2742  2832 I io.jxcore.node.LifeCycleMonitor: start: OK
03-31 15:14:04.967  2742  2742 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 15:14:05.317  2833  2833 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-31 15:14:05.387  2833  2833 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-31 15:14:05.439   820  1255 I ActivityManager: Start proc 2876:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-31 15:14:05.461  2876  2876 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 15:14:05.461  2876  2876 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 15:14:05.474  2833  2833 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 15:14:05.477  2833  2833 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 15:14:05.482  2876  2876 I MultiDex: VM with version 2.1.0 has multidex support
,03-31 15:14:05.482  2876  2876 I MultiDex: install
03-31 15:14:05.482  2876  2876 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 15:14:05.507  2876  2876 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 15:14:05.520  2833  2869 D Volley  : [268] DiskBasedCache.clear: Cache cleared.
,03-31 15:14:05.521  2833  2862 D Volley  : [261] DiskBasedCache.clear: Cache cleared.
,03-31 15:14:05.538   820  1508 I ActivityManager: Start proc 2896:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
03-31 15:14:05.539   820  1508 I ActivityManager: Killing 2316:com.android.managedprovisioning/u0a17 (adj 15): empty #17
03-31 15:14:05.551  2876  2876 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 15:14:05.677  2833  2833 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-31 15:14:05.677  2833  2833 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-31 15:14:05.686  2833  2833 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-31 15:14:05.703  2742  2855 W jxcore-log: Initializing JXcore engine
03-31 15:14:05.703  2742  2855 W jxcore-log: JXcore engine is ready
,03-31 15:14:05.706  2833  2833 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-31 15:14:05.751  1246  1263 I art     : Explicit concurrent mark sweep GC freed 7526(406KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 756us total 22.422ms
,03-31 15:14:05.740  2855  2855 W Thread-264: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10469]" dev="sockfs" ino=10469 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-31 15:14:05.740  2855  2855 W Thread-264: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-31 15:14:05.740  2855  2855 W Thread-264: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10613]" dev="sockfs" ino=10613 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 15:14:05.740  2855  2855 W Thread-264: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[18258]" dev="sockfs" ino=18258 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-31 15:14:05.767  2742  2855 W jxcore-log: Starting JXcore engine
,03-31 15:14:05.879  2742  2855 W jxcore-log: Platform android
03-31 15:14:05.879  2742  2855 W jxcore-log: 
03-31 15:14:05.879  2742  2855 W jxcore-log: Process ARCH arm
03-31 15:14:05.879  2742  2855 W jxcore-log: 
,03-31 15:14:05.889   820  1020 I ActivityManager: Killing 1681:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-31 15:14:06.013  2833  2833 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-31 15:14:06.021  1781  1781 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-31 15:14:06.024  2392  2417 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 15:14:06.111  2896  2932 I Gmail   : getAccountsCursor
,03-31 15:14:06.113  2896  2933 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-31 15:14:06.122  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:06.136  2742  2855 I jxcore-log: JXcore Cordova bridge is ready!,
03-31 15:14:06.136  2742  2855 I jxcore-log: 
03-31 15:14:06.136  2742  2855 W jxcore-log: JXcore engine is started
,03-31 15:14:06.143  2742  2832 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 15:14:06.145  2742  2742 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 15:14:06.176   820   820 I art     : Explicit concurrent mark sweep GC freed 16649(817KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.260ms total 49.677ms
,03-31 15:14:06.220   820  1233 I ActivityManager: Start proc 2935:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,03-31 15:14:06.279  2896  2896 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 15:14:06.299   820   835 I ActivityManager: Killing 2337:com.android.settings/1000 (adj 15): empty #17
,03-31 15:14:06.405   820  1368 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-31 15:14:06.413  2935  2935 I Exchange: EasService.onCreate
,03-31 15:14:06.416  2896  2958 I Gmail   : Observing account changes for notifications
,03-31 15:14:06.420  2935  2961 I Exchange: RestartPingTask
03-31 15:14:06.427  2896  2965 I Gmail   : getAccountsCursor
,03-31 15:14:06.431  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 15:14:06.431  2935  2935 I Exchange: RestartPingsTask did not start any pings.
03-31 15:14:06.431  2935  2935 I Exchange: PSS stopIfIdle
03-31 15:14:06.431  2935  2935 I Exchange: PSS has no active accounts; stopping service.
,03-31 15:14:06.437  2935  2935 I Exchange: onDestroy
,03-31 15:14:06.439  1264  1264 I SystemBroadcastReceiver: Boot has been completed
03-31 15:14:06.440  1264  1264 I SystemBroadcastReceiver: toggleAppIcon() : FLAG_SYSTEM = true
03-31 15:14:06.440   820  1368 I ActivityManager: Killing 2354:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
03-31 15:14:06.441  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:06.496  2935  2935 I Exchange: EasService.onCreate
,03-31 15:14:06.498  2935  2971 I Exchange: RestartPingTask
,03-31 15:14:06.526   820  1368 I ActivityManager: Start proc 2972:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
,03-31 15:14:06.543   369   369 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 16.650ms
,03-31 15:14:06.555   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 11.318ms
,03-31 15:14:06.564   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 8.903ms
,03-31 15:14:06.568  2896  2967 E SQLiteLog: (283) recovered 37 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-31 15:14:06.599  2935  2935 I Exchange: RestartPingsTask did not start any pings.
03-31 15:14:06.599  2935  2935 I Exchange: PSS stopIfIdle
03-31 15:14:06.599  2935  2935 I Exchange: PSS has no active accounts; stopping service.
,03-31 15:14:06.600  2935  2935 I Exchange: onDestroy
,03-31 15:14:06.689  2896  2990 I Gmail   : notifyAccountChanged
03-31 15:14:06.690  2896  2933 I Gmail   : getAccountsCursor
,03-31 15:14:06.693  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:06.696  2896  2990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-31 15:14:06.761  2896  2967 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,03-31 15:14:06.762  2896  2990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-31 15:14:06.767  2896  2967 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,03-31 15:14:06.773  2896  2967 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,03-31 15:14:06.778   820  1367 I ActivityManager: Killing 2270:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-31 15:14:06.782  2896  2990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-31 15:14:06.783  2896  2990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-31 15:14:06.940  2896  2959 I Gmail   : getAccountsCursor
,03-31 15:14:06.944  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:07.030  2972  2997 I art     : Note: end time exceeds epoch: 
,03-31 15:14:07.048  2972  2972 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:07.070  2972  2972 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-31 15:14:07.091  2972  2972 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.097  2972  2998 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.104  1811  1811 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-31 15:14:07.105  2972  2972 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
03-31 15:14:07.105  2972  2998 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 15:14:07.119  2972  2998 I Bugle   : ApnsOta: OTA version -1
,03-31 15:14:07.124  2972  2972 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.139  2972  2998 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.146   820  1913 I ActivityManager: Start proc 3005:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,03-31 15:14:07.149  2972  3003 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.157  2972  3004 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.159  2972  2972 I BugleUsageStatistics: PlayLogger.onLoggerConnected
,03-31 15:14:07.177  2972  3002 I BugleDataModel: Fixup: Send failed - 0 Download failed - 0
,03-31 15:14:07.181  2972  3002 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.194  2972  3004 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.194  2972  3004 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.201  2972  3004 W Bugle   : PhoneUtils.getSelfRawNumber: subInfo is null for -1
,03-31 15:14:07.202  2972  3004 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.207  2972  3002 W Bugle   : PhoneUtils.getForLMR1(): invalid subId = -1
,03-31 15:14:07.208  2972  3024 I BugleDataModel: SyncMessagesAction: Starting batch for messages from 1459422173970 to 1459430047086 (message update limit = 80, message scan limit = 4000)
,03-31 15:14:07.237   820  1916 I ActivityManager: Killing 2422:com.google.android.configupdater/u0a42 (adj 15): empty #17
,03-31 15:14:07.298  1246  1246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,03-31 15:14:07.322   820  1020 I ActivityManager: Start proc 3027:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,03-31 15:14:07.338  2972  3025 I BugleDataModel: SyncMessagesAction: All messages now in sync
,03-31 15:14:07.342   820  1916 I ActivityManager: Killing 1428:android.process.acore/u0a5 (adj 15): empty #17
,03-31 15:14:07.916  3027  3027 I MusicStore: Database version: 120
,03-31 15:14:08.209   820  1233 I art     : Explicit concurrent mark sweep GC freed 10205(542KB) AllocSpace objects, 2(30KB) LOS objects, 32% free, 33MB/49MB, paused 1.025ms total 47.099ms
,03-31 15:14:08.249  3027  3027 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 15:14:08.249  3027  3027 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 15:14:08.272  3027  3027 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 15:14:08.308  3027  3027 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-31 15:14:08.308  3027  3027 D AndroidMusic: GMSCore installation verified
,03-31 15:14:08.327  3027  3027 I ConfigStore: Config Database version: 1
,03-31 15:14:08.458  3027  3027 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-31 15:14:08.468  3005  3005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,03-31 15:14:08.477   820   860 D BluetoothManagerService: Message: 20
03-31 15:14:08.478   820   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85e9a99:true
,03-31 15:14:08.496   820  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 15:14:08.497  2168  3057 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 15:14:08.503  1246  1246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,03-31 15:14:08.521  3005  3005 D LocalBluetoothProfileManager: Adding local A2DP profile
,03-31 15:14:08.523   820  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 15:14:08.525  2168  3061 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 15:14:08.527   820   860 D BluetoothManagerService: Message: 30
03-31 15:14:08.527  2168  3061 I BtOppRfcommListener: Accept thread started.
,03-31 15:14:08.530  3005  3005 D LocalBluetoothProfileManager: Adding local HEADSET profile
,03-31 15:14:08.532   820   860 D BluetoothManagerService: Message: 30
,03-31 15:14:08.533  3027  3027 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-31 15:14:08.537   820   860 D BluetoothManagerService: Message: 30
,03-31 15:14:08.545   820   860 D BluetoothManagerService: Message: 30
,03-31 15:14:08.549  3027  3027 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 15:14:08.551  3005  3005 D LocalBluetoothProfileManager: Adding local MAP profile
03-31 15:14:08.552  3005  3005 D BluetoothMap: Create BluetoothMap proxy object
,03-31 15:14:08.552   820   860 D BluetoothManagerService: Message: 30
,03-31 15:14:08.557   820   860 D BluetoothManagerService: Message: 30
,03-31 15:14:08.560  3005  3005 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,03-31 15:14:08.565  3005  3005 D DockEventReceiver: finishStartingService: stopping service
,03-31 15:14:08.566  3005  3005 D BluetoothA2dp: Proxy object connected
03-31 15:14:08.566  3005  3005 D A2dpProfile: Bluetooth service connected
,03-31 15:14:08.569  3005  3005 D BluetoothInputDevice: Proxy object connected
,03-31 15:14:08.569  3005  3005 D HidProfile: Bluetooth service connected
,03-31 15:14:08.571  3005  3005 D BluetoothPan: BluetoothPAN Proxy object connected
03-31 15:14:08.571  3005  3005 D PanProfile: Bluetooth service connected
03-31 15:14:08.571  3005  3005 D BluetoothMap: Proxy object connected
03-31 15:14:08.572  3005  3005 D MapProfile: Bluetooth service connected
03-31 15:14:08.572  3005  3005 D BluetoothMap: getConnectedDevices()
,03-31 15:14:08.574  3005  3005 D BluetoothPbap: Proxy object connected
03-31 15:14:08.574  3005  3005 D PbapServerProfile: Bluetooth service connected
,03-31 15:14:08.578   820  1917 I ActivityManager: Killing 1639:com.google.android.keep/u0a79 (adj 15): empty #17
,03-31 15:14:08.634   820   860 D BluetoothManagerService: Message: 400
,03-31 15:14:08.635  3005  3020 D BluetoothHeadset: Proxy object connected
,03-31 15:14:08.637  3005  3005 D HeadsetProfile: Bluetooth service connected
,03-31 15:14:08.838  1246  2079 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-31 15:14:08.843  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-31 15:14:08.844  1781  1781 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-31 15:14:08.870   820  1913 I ActivityManager: Start proc 3076:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
,03-31 15:14:08.923  3076  3076 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-31 15:14:08.946   820  1508 I ActivityManager: Start proc 3093:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-31 15:14:08.955  3027  3068 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-31 15:14:09.054   820   835 I ActivityManager: Start proc 3113:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,03-31 15:14:09.056   820   835 I ActivityManager: Killing 2500:com.qualcomm.telephony/1001 (adj 15): empty #17
,03-31 15:14:09.069  3093  3111 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-31 15:14:09.346   820   836 I ActivityManager: Start proc 3134:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 15:14:09.348   820  1913 I ActivityManager: Killing 1882:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-31 15:14:09.626  1781  3154 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-31 15:14:09.627  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-31 15:14:09.629  1781  1781 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,03-31 15:14:09.673   820  1913 I ActivityManager: Start proc 3155:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,03-31 15:14:09.681   820  1368 I ActivityManager: Killing 2570:com.google.android.youtube/u0a86 (adj 15): empty #17
,03-31 15:14:09.916  3155  3155 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 15:14:09.916  3155  3155 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 15:14:09.936  3155  3155 I MultiDex: VM with version 2.1.0 has multidex support
03-31 15:14:09.937  3155  3155 I MultiDex: install
03-31 15:14:09.937  3155  3155 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 15:14:09.950  3155  3155 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 15:14:09.978  3155  3155 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 15:14:09.991   820  1917 I ActivityManager: Killing 2674:com.google.android.talk/u0a61 (adj 15): empty #17
,03-31 15:14:10.098  1781  1781 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-31 15:14:10.108  1781  1781 I ConfigFetchService: launchTask
,03-31 15:14:10.132  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-31 15:14:10.133  1781  1781 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-31 15:14:10.137  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
03-31 15:14:10.138  1781  3176 I PeopleContactsSync: CP2 sync disabled
,03-31 15:14:10.140  1781  1781 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
03-31 15:14:10.140  1781  3175 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1W8tzGB0nAwunCTEAggHBNyvIBHpvldne-ugaJRyEQte-IWztDEtjBUbijTofJbo9Q3x2nVDkd6qfChEDAeqK2HZN_CkrlHRBsNxfA9uZ0hwYjuX-LGVtg5S_DjmuWzrEEMCzp7I8L1Pyt7eh1MyCsS92-J_6bSFf-LnxCMZ_4YCXBWptlZ06dRaxT6jGXDoGPcAOWg8ZBW8kTRHcnBFMCh5eRWuwKgid5hNLWdFlxkVOM83kY
,03-31 15:14:10.140  1781  1781 D Vision  : Failed to find package metadata for com.test.thalitest
03-31 15:14:10.140  1781  1781 D Vision  : No vision deps
,03-31 15:14:10.143  1781  3175 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 15:14:10.165  1781  3175 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
03-31 15:14:10.166  1781  1781 I ConfigFetchService: fetch service done; releasing wakelock
,03-31 15:14:10.167  1781  1781 I ConfigFetchService: stopping self
,03-31 15:14:10.190   820  1508 I ActivityManager: Start proc 3182:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
03-31 15:14:10.191  1568  3179 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-31 15:14:10.404  1246  1736 I art     : Explicit concurrent mark sweep GC freed 12289(596KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 996us total 26.935ms
,03-31 15:14:10.421  1781  3199 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 64 ms
,03-31 15:14:10.425  1781  3178 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:14:10.426  1781  3178 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:14:10.452   820  1913 I art     : Explicit concurrent mark sweep GC freed 8070(385KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.136ms total 48.120ms
,03-31 15:14:10.455  1568  3179 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 263 ms] updated apps [took 263 ms] 
,03-31 15:14:10.463  1781  3178 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:14:10.469  1781  3178 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:14:10.472  1781  3178 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:14:10.489  1781  3178 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:14:10.630  1781  3178 I art     : Explicit concurrent mark sweep GC freed 20061(1392KB) AllocSpace objects, 14(224KB) LOS objects, 36% free, 27MB/43MB, paused 684us total 39.416ms
,03-31 15:14:10.835  1781  3178 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-31 15:14:10.835  1781  3178 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-31 15:14:10.956  3182  3182 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-31 15:14:10.956  3182  3182 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 15:14:10.956  3182  3182 I GAv4    :   adb logcat -s GAv4
,03-31 15:14:10.964  3182  3182 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:14:10.971  3182  3182 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:14:10.974  3182  3221 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:14:10.987  3182  3182 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-31 15:14:11.080  3182  3228 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 15:14:11.082  3182  3228 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 15:14:11.097   820  3206 I ActivityManager: Start proc 3230:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,03-31 15:14:11.099   820  3206 I ActivityManager: Killing 2788:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-31 15:14:11.163  3230  3230 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-31 15:14:11.193  3182  3228 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 15:14:11.228  3182  3228 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 15:14:11.235  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:11.314  2896  2954 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 15:14:11.491  1781  1809 I Icing   : Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,03-31 15:14:11.518  1781  1809 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-31 15:14:11.561  1781  1809 I Icing   : Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,03-31 15:14:11.815   820   836 I ActivityManager: Start proc 3258:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,03-31 15:14:11.840  3258  3258 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 15:14:11.859  3258  3258 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2a8fb4b3(com.android.providers.calendar.CalendarProvider2@1db0aa70)
,03-31 15:14:11.867  1246  2119 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 15:14:11.869  1246  1246 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 15:14:11.873  1781  1781 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 15:14:11.876  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:11.889  3155  3155 D WearableService: callingUid 10011, callindPid: 3155
,03-31 15:14:11.900  1781  3283 D LocationInitializer: Restart initialization of location
,03-31 15:14:11.908  1811  3282 E MDM     : [159] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 15:14:11.909  3258  3284 E SQLiteLog: (284) automatic index on view_events(_id)
,03-31 15:14:11.921   820  1020 I ActivityManager: Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,03-31 15:14:11.927   820  1912 I ActivityManager: Resuming delayed broadcast
,03-31 15:14:11.938   820   836 I ActivityManager: Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,03-31 15:14:11.945   820  1367 I ActivityManager: Resuming delayed broadcast
,03-31 15:14:11.953   820  1255 I ActivityManager: Delay finish: com.google.android.gm/.MailIntentReceiver
,03-31 15:14:11.957   820   836 I ActivityManager: Resuming delayed broadcast
,03-31 15:14:12.003   820  1917 I ActivityManager: Start proc 3293:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,03-31 15:14:12.013   369   369 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 214us total 9.130ms
,03-31 15:14:12.022   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 8.719ms
,03-31 15:14:12.032   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 8.996ms
,03-31 15:14:12.033  3293  3293 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 15:14:12.057  2896  3290 I NotifUtils: Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,03-31 15:14:12.072  2896  3290 I NotifUtils: validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,03-31 15:14:12.127  3293  3317 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-31 15:14:12.127  3293  3317 I Babel_SMS: MmsConfig.loadMmsSettings
,03-31 15:14:12.128  3293  3317 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
03-31 15:14:12.128  3293  3317 I Babel_SMS: MmsConfig.loadFromDatabase
,03-31 15:14:12.139  3293  3317 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-31 15:14:12.139  3293  3317 I Babel_SMS: MmsConfig.loadFromResources
,03-31 15:14:12.140  3293  3317 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-31 15:14:12.140  3293  3317 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,03-31 15:14:12.171  3293  3293 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-31 15:14:12.174  3293  3293 I Babel_Crash: startup - clean,
,03-31 15:14:12.181  3293  3320 I Babel   : deleted: false for 0
,03-31 15:14:12.197  3293  3293 I Babel_telephony: TeleModule.launchCompleted
,03-31 15:14:12.200   820  1368 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 15:14:12.202  3293  3293 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,03-31 15:14:12.202  3293  3293 W Babel   : BAM#gBA: invalid account id: -1
03-31 15:14:12.202  3293  3293 W Babel   : BAM#gBA: invalid account id: -1
03-31 15:14:12.203  3293  3293 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 15:14:12.204   820  1233 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 15:14:12.220  1246  2122 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 15:14:12.224  1246  1246 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 15:14:12.228  1781  1781 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 15:14:12.246  1811  2085 E MDM     : [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 15:14:12.253  1781  3326 D LocationInitializer: Restart initialization of location
,03-31 15:14:12.268  3293  3293 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:12.333  3293  3293 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-31 15:14:12.341  3293  3293 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:12.343  3293  3293 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:12.346  3293  3293 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:12.350  3293  3293 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:12.372  3293  3293 I vclib   : onServiceConnected
,03-31 15:14:12.374  3293  3293 W Babel   : Attempted to change video mute state without an active call.
03-31 15:14:12.376   820   836 I ActivityManager: Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
03-31 15:14:12.381   820  1916 I ActivityManager: Resuming delayed broadcast
,03-31 15:14:12.456  3293  3293 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 15:14:12.456  3293  3293 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 15:14:12.470   820  1012 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 15:14:12.500  3293  3293 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 15:14:12.543  1811  1811 V GmsNetworkLocationProvi: DISABLE
,03-31 15:14:12.548   820   820 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-31 15:14:12.548   820   820 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-31 15:14:12.551   820   820 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-31 15:14:12.575   820   820 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-31 15:14:12.576   820   820 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2eefcff1
03-31 15:14:12.577  3293  3293 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 15:14:12.579  1811  1827 V GmsNetworkLocationProvi: onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,03-31 15:14:12.584   820   820 I ValidateNoPeople: skipping global notification
,03-31 15:14:12.600  1811  1811 V GmsNetworkLocationProvi: ENABLE
,03-31 15:14:12.602  1811  1811 V GmsNetworkLocationProvi: SET-REQUEST
,03-31 15:14:12.602  1811  1811 V GmsNetworkLocationProvi: in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,03-31 15:14:12.612  1371  1371 I Launcher: Deferring update until onResume
,03-31 15:14:12.623  1781  3336 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-31 15:14:12.625   820  3206 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,03-31 15:14:12.626  1781  3336 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,03-31 15:14:12.631  3293  3329 I Babel_telephony: TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,03-31 15:14:12.633  1781  1809 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-31 15:14:12.636  1568  3337 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-31 15:14:12.638  3293  3329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:12.640  3293  3329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-31 15:14:12.642  3293  3329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-31 15:14:12.661  1568  3337 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 25 ms] updated apps [took 25 ms] 
,03-31 15:14:12.663   820  1233 I ActivityManager: Resuming delayed broadcast
,03-31 15:14:12.667  1371  1371 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3393072b new=com.google.android.velvet.VelvetApplication@3393072b
,03-31 15:14:12.731  3293  3343 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,03-31 15:14:12.734   820  1913 I art     : Explicit concurrent mark sweep GC freed 21268(1074KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.402ms total 51.818ms
,03-31 15:14:12.962  3258  3258 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-31 15:14:12.962  3258  3258 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 15:14:12.972   820   836 I ActivityManager: Killing 2876:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-31 15:14:13.548  3027  3347 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-31 15:14:13.548  3027  3347 I MusicLeanback: Stop autocaching.
,03-31 15:14:13.559  3027  3027 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
03-31 15:14:13.559  3027  3352 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 15:14:15.204  1246  1246 I ConfigService: onDestroy
,03-31 15:14:15.259   820   856 I ActivityManager: Waited long enough for: ServiceRecord{12a9061e u0 org.simalliance.openmobileapi.service/.SmartcardService}
,03-31 15:14:16.156   820   856 I ActivityManager: Waited long enough for: ServiceRecord{1eb132ce u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,03-31 15:14:16.441  2742  2855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 15:14:16.441  2742  2855 I jxcore-log: 
,03-31 15:14:16.443  2742  2855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 15:14:16.443  2742  2855 I jxcore-log: 
,03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,03-31 15:14:16.460  2742  2855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-31 15:14:16.466  2742  2855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-31 15:14:16.468  2742  2855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 15:14:16.468  2742  2855 I jxcore-log: 
,03-31 15:14:16.470  2742  2855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 15:14:16.470  2742  2855 I jxcore-log: 
,03-31 15:14:16.913   820   856 I ActivityManager: Waited long enough for: ServiceRecord{33c61773 u0 com.qualcomm.atfwd/.AtFwdService}
,03-31 15:14:17.002  2742  2855 I jxcore-log: Unit Test app is loaded
03-31 15:14:17.002  2742  2855 I jxcore-log: 
,03-31 15:14:17.008  2742  2855 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
03-31 15:14:17.008  2742  2855 I jxcore-log: 
,03-31 15:14:17.011  2742  2855 I jxcore-log: My device name is: motorola-Nexus 6
03-31 15:14:17.011  2742  2855 I jxcore-log: 
03-31 15:14:17.013  2742  2855 I jxcore-log: WARN testUtils: myNameCallback not set!
03-31 15:14:17.013  2742  2855 I jxcore-log: 
,03-31 15:14:17.029  2742  2742 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 15:14:17.255   820  1508 I ActivityManager: Killing 1865:com.android.defcontainer/u0a7 (adj 15): empty #17
,03-31 15:14:17.340   374   374 I Atfwd_Daemon: result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-31 15:14:17.340   374   374 I Atfwd_Daemon: ATFWD --> QMI Port : rmnet_usb0
,03-31 15:14:17.411   374   374 I Atfwd_Daemon: qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848,
03-31 15:14:17.411   374   374 I Atfwd_Daemon: Trying to register 8 commands:
03-31 15:14:17.411   374   374 I Atfwd_Daemon: cmd0: +CKPD
,03-31 15:14:17.421   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-31 15:14:17.421   374   374 I Atfwd_Daemon: cmd1: +CTSA
,03-31 15:14:17.431   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0,
03-31 15:14:17.431   374   374 I Atfwd_Daemon: cmd2: +CFUN
,03-31 15:14:17.441   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-31 15:14:17.441   374   374 I Atfwd_Daemon: cmd3: +CMAR
,03-31 15:14:17.451   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-31 15:14:17.451   374   374 I Atfwd_Daemon: cmd4: +CDIS
,03-31 15:14:17.461   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-31 15:14:17.461   374   374 I Atfwd_Daemon: cmd5: +CRSL
,03-31 15:14:17.471   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-31 15:14:17.471   374   374 I Atfwd_Daemon: cmd6: +CSS
,03-31 15:14:17.481   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-31 15:14:17.481   374   374 I Atfwd_Daemon: cmd7: $QCPWRDN
,03-31 15:14:17.491   374   374 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-31 15:14:17.491   374   374 I Atfwd_Daemon: Registered AT Commands event handler
,03-31 15:14:20.898  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 15:14:20.898  2742  2855 I jxcore-log: 
,03-31 15:14:21.253  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 15:14:21.253  2742  2855 I jxcore-log: 
,03-31 15:14:21.266  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 15:14:21.266  2742  2855 I jxcore-log: 
,03-31 15:14:21.271  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 15:14:21.271  2742  2855 I jxcore-log: 
,03-31 15:14:21.309  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 15:14:21.309  2742  2855 I jxcore-log: 
,03-31 15:14:21.325  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 15:14:21.325  2742  2855 I jxcore-log: 
,03-31 15:14:21.331  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 15:14:21.331  2742  2855 I jxcore-log: 
,03-31 15:14:22.457  1781  2544 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 15:14:23.337  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 15:14:23.337  2742  2855 I jxcore-log: 
,03-31 15:14:23.354  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 15:14:23.354  2742  2855 I jxcore-log: 
,03-31 15:14:23.363  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 15:14:23.363  2742  2855 I jxcore-log: 
,03-31 15:14:23.622  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 15:14:23.622  2742  2855 I jxcore-log: 
,03-31 15:14:23.696  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 15:14:23.696  2742  2855 I jxcore-log: 
,03-31 15:14:23.757  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 15:14:23.757  2742  2855 I jxcore-log: 
,03-31 15:14:23.764  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
03-31 15:14:23.764  2742  2855 I jxcore-log: 
,03-31 15:14:23.775  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 15:14:23.775  2742  2855 I jxcore-log: 
,03-31 15:14:23.779  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 15:14:23.779  2742  2855 I jxcore-log: 
,03-31 15:14:23.785  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
03-31 15:14:23.785  2742  2855 I jxcore-log: 
,03-31 15:14:23.801  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 15:14:23.801  2742  2855 I jxcore-log: 
,03-31 15:14:23.819  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 15:14:23.819  2742  2855 I jxcore-log: 
,03-31 15:14:23.901  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 15:14:23.901  2742  2855 I jxcore-log: 
,03-31 15:14:23.906  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 15:14:23.906  2742  2855 I jxcore-log: 
,03-31 15:14:23.926   820   856 I ActivityManager: Waited long enough for: ServiceRecord{153c74a5 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,03-31 15:14:23.933  2742  2855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 15:14:23.933  2742  2855 I jxcore-log: 
,03-31 15:14:23.943  2742  2855 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 15:14:23.944  2742  2855 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 15:14:23.944  2742  2855 I jxcore-log: 
,03-31 15:14:24.324  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:14:24.502  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:14:24.969   820   836 I ActivityManager: Killing 2935:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,03-31 15:14:31.198   820  1916 I ActivityManager: Killing 2972:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,03-31 15:14:31.409   820  1916 I ActivityManager: Killing 2762:com.google.android.apps.fitness/u0a51 (adj 15): empty #18,
,03-31 15:14:35.686  2833  2833 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-31 15:14:35.733  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:35.794  1246  1736 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 15:14:35.794  1246  1736 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:14:35.795  1246  1736 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:14:35.795  1246  1736 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:14:35.803  1246  1736 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:35.826  2833  2833 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 15:14:35.834  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:35.870  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 15:14:35.871  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:14:35.871  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:14:35.871  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:14:35.876  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:36.093  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:36.141  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 15:14:36.142  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:14:36.142  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:14:36.142  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:14:36.150  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:36.182  2833  2833 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 15:14:36.264  1246  1726 I art     : Explicit concurrent mark sweep GC freed 23611(1252KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.296ms total 40.911ms
,03-31 15:14:36.289  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 15:14:36.289  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:14:36.289  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:14:36.289  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:14:36.296  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:36.312  2833  2833 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 15:14:36.313  2833  2833 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 15:14:36.314  2833  2833 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-31 15:14:36.458  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:36.497  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 15:14:36.498  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:14:36.498  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:14:36.498  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:14:36.505  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:36.535  2833  2833 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
03-31 15:14:36.539  2833  2833 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-31 15:14:36.556  2833  2833 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 15:14:36.564  2833  2833 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 271 minutes (failures=4)
,03-31 15:14:36.584  1811  1826 D DeviceConnectionService: client connected with version: 7571000,
,03-31 15:14:49.168  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:14:56.512  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:56.587  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 15:14:56.587  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:14:56.587  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-31 15:14:56.588  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:14:56.599  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:56.639  2833  2833 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 15:14:56.640  2833  2833 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 15:14:56.643  2833  2833 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-31 15:15:04.718  1264  1505 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 15:15:04.718  1264  1505 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 15:15:04.756  1246  1246 I ConfigService: onCreate
,03-31 15:15:09.846  1246  1246 I ConfigService: onDestroy
,03-31 15:15:16.763   820  1916 I art     : Explicit concurrent mark sweep GC freed 32189(1533KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.952ms total 82.708ms
,03-31 15:15:16.964  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:15:17.010  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 15:15:17.010  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:15:17.011  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:15:17.011  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:15:17.020  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:15:17.052  2833  2833 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 15:15:17.053  2833  2833 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 15:15:17.053  2833  2833 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-31 15:15:24.326  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:15:37.378  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:15:37.475  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 15:15:37.475  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:15:37.475  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:15:37.476  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:15:37.481  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:15:37.502  2833  2833 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 15:15:37.502  2833  2833 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 15:15:37.503  2833  2833 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-31 15:15:49.302  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:15:57.799  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:15:57.849  1246  1736 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 15:15:57.850  1246  1736 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:15:57.850  1246  1736 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:15:57.850  1246  1736 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:15:57.857  1246  1736 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:15:57.880  2833  2833 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 15:15:57.883  2833  2833 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 15:15:57.884  2833  2833 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-31 15:15:59.939   820   863 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-31 15:15:59.964   820   863 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 15:16:00.006   259   851 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (218 us)
,03-31 15:16:00.621   820   861 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-31 15:16:00.621   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-31 15:16:00.622   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-31 15:16:00.626   820   820 V ActivityManager: Display changed displayId=0
,03-31 15:16:00.804   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-31 15:16:00.804   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-31 15:16:00.845   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,03-31 15:16:00.845   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-31 15:16:00.869   259   314 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-31 15:16:00.873   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-31 15:16:00.874   820  1055 D SurfaceControl: Excessive delay in setPowerMode(): 253ms
,03-31 15:16:00.880   820   863 I DreamManagerService: Entering dreamland.
,03-31 15:16:00.883   820   863 I PowerManagerService: Dozing...
03-31 15:16:00.884   820   858 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-31 15:16:00.904   357   357 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-31 15:16:00.905   357   357 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-31 15:16:00.912   820  1035 E WifiStateMachine: cancelDelayedScan -> 16
,03-31 15:16:00.921   820  1035 E native  : do suspend false
,03-31 15:16:00.987  1264  1264 I Keyboard.Facilitator: onFinishInput()
,03-31 15:16:01.001   820  1035 E WifiStateMachine: cancelDelayedScan -> 18
,03-31 15:16:01.057   820  1035 E native  : do suspend true
,03-31 15:16:01.064   357  1425 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-31 15:16:01.064   357  1425 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-31 15:16:01.119   820  1035 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-31 15:16:01.130   820  1035 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-31 15:16:01.848   873   873 I kickstart: STATUS: Received file 'm9kefs2'
,03-31 15:16:01.848   873   873 I kickstart: STATUS: 950272 bytes transferred in 1.001899 seconds
03-31 15:16:01.848   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-31 15:16:01.849   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 15:16:01.852   873   873 I kickstart: STATUS: Sahara protocol completed
,03-31 15:16:03.475  1156  1156 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-31 15:16:03.920  1156  1156 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-31 15:16:03.958  1156  1156 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-31 15:16:03.958  1156  1156 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-31 15:16:03.992   820  1035 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-31 15:16:03.994   820  1037 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-31 15:16:03.994   820  1035 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 15:16:04.004   820  1035 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 15:16:04.012   353   800 D CommandListener: Setting iface cfg
,03-31 15:16:04.018   820  1035 E WifiStateMachine: Start Dhcp Watchdog 1
,03-31 15:16:04.023   820  1035 E WifiStateMachine:  WifiLinkLayerStats: 
03-31 15:16:04.023   820  1035 E WifiStateMachine:  my bss beacon rx: 1
03-31 15:16:04.023   820  1035 E WifiStateMachine:  RSSI mgmt: -38
03-31 15:16:04.023   820  1035 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-31 15:16:04.023   820  1035 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-31 15:16:04.023   820  1035 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-31 15:16:04.023   820  1035 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-31 15:16:04.023   820  1035 E WifiStateMachine:  on_time : 523 tx_time=62 rx_time=150 scan_time=0
,03-31 15:16:04.123   820  1035 E native  : do suspend false
,03-31 15:16:04.139   820  1035 E WifiStateMachine: scanCount==0 - aborting
,03-31 15:16:04.386  3402  3402 I dhcpcd  : version 5.5.6 starting
,03-31 15:16:04.535  3402  3402 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-31 15:16:04.712  3402  3402 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-31 15:16:04.769  3402  3402 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-31 15:16:05.163   820  1035 E native  : do suspend true
,03-31 15:16:05.193   820  1037 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-31 15:16:05.196   820  1037 D ConnectivityService: Adding iface wlan0 to network 100
03-31 15:16:05.197   820  1035 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-31 15:16:05.229   820  1037 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-31 15:16:05.229   820  1037 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-31 15:16:05.230   820  1037 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-31 15:16:05.231   820  1037 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-31 15:16:05.232   820  1037 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-31 15:16:05.243   820  1037 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-31 15:16:05.247   820  1037 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-31 15:16:05.247   820  3400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-31 15:16:05.247   820  3400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-31 15:16:05.248   820  1037 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 15:16:05.248   820  1037 D ConnectivityService:    accepting network in place of null
03-31 15:16:05.248   820  3400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-31 15:16:05.249   820  1037 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
03-31 15:16:05.249   820  3400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-31 15:16:05.250   820  1037 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-31 15:16:05.253   820  1037 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100],
,03-31 15:16:05.254   820  1037 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-31 15:16:05.254   820  1037 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-31 15:16:05.254  1076  1521 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-31 15:16:05.255   820  1037 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-31 15:16:05.257   820   860 D Tethering: MasterInitialState.processMessage what=3
,03-31 15:16:05.269  1344  1649 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-31 15:16:05.269  1344  1649 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-31 15:16:05.270   820   855 D TelephonyManager: getDataEnabled: retVal=false
,03-31 15:16:05.273   820   836 V BackupManagerService: Scheduling immediate backup pass
,03-31 15:16:05.275   820   820 V BackupManagerService: Running a backup pass
,03-31 15:16:05.276   820  1054 V BackupManagerService: clearing pending backups
,03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 15:16:05.284  2742  2742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 15:16:05.284  3027  3027 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-31 15:16:05.285  1568  1568 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-31 15:16:05.286  2742  2742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 15:16:05.289  2742  2855 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 15:16:05.289  2742  2855 I jxcore-log: 
,03-31 15:16:05.289   820  1054 V PerformBackupTask: Beginning backup of 14 targets
03-31 15:16:05.290  3027  3027 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-31 15:16:05.293   820   855 E GpsLocationProvider: No APN found to select.
,03-31 15:16:05.297   820  1054 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-31 15:16:05.300   820  1054 V BackupServiceBinder: doBackup() invoked
,03-31 15:16:05.302   820  1054 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-31 15:16:05.314   820  1054 I BackupRestoreController: Getting widget state for user: 0
,03-31 15:16:05.336   820  1917 I ActivityManager: Start proc 3442:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-31 15:16:05.379  1811  1827 W GmsBackupTransport: Unknown package in backup request: @pm@
03-31 15:16:05.380  1811  1827 V GmsBackupTransport: starting performBackup for @pm@
,03-31 15:16:05.385  1811  1827 V GmsBackupTransport: performBackup done for @pm@
,03-31 15:16:05.401  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:05.423  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-31 15:16:05.423  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:05.423  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:05.423  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:05.426  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:05.456   820  1508 I ActivityManager: Start proc 3476:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-31 15:16:05.473  1246  1726 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:16:05.473  1246  1726 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:16:05.473  1246  1726 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 15:16:05.473  1246  1726 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 15:16:05.473  1246  1726 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 15:16:05.473  1246  1726 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 15:16:05.473  1246  1726 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 15:16:05.491  1811  1848 W GmsBackupTransport: Error sending final backup to server: 
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 15:16:05.491  1811  1848 W GmsBackupTransport: 	... 1 more
,03-31 15:16:05.493   820  1054 D BackupManagerService: Now staging backup of com.google.android.talk
,03-31 15:16:05.504  3476  3476 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-31 15:16:05.508  3476  3476 D SprintDMHelper: simOperator:  IMSI: null
,03-31 15:16:05.508   820  3461 D GpsLocationProvider: NTP server returned: 1459430166264 (Thu Mar 31 15:16:06 GMT+02:00 2016) reference: 168079 certainty: 68 system time offset: 756
03-31 15:16:05.509  3476  3476 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-31 15:16:05.511   820  1305 D AlarmManagerService: Setting time of day to sec=1459430166
03-31 15:16:06.267   820  1305 W AlarmManagerService: Unable to set rtc to 1459430166: Invalid argument
,03-31 15:16:06.285   820  1054 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-31 15:16:06.292   820  1054 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-31 15:16:06.296   820  1054 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-31 15:16:06.296  1246  1736 I art     : Explicit concurrent mark sweep GC freed 26268(1386KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.112ms total 26.727ms
,03-31 15:16:06.302   820  1054 D BackupManagerService: Now staging backup of com.google.android.gm
,03-31 15:16:06.305   820  1054 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-31 15:16:06.312   820  1054 D BackupManagerService: Now staging backup of com.android.nfc
,03-31 15:16:06.317   820  1054 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-31 15:16:06.319   820  1054 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-31 15:16:06.321   820  1054 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-31 15:16:06.329  1781  3497 W DriveInitializer: Background init thread started
,03-31 15:16:06.331  1781  1781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-31 15:16:06.331   820  1054 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-31 15:16:06.334   820  1054 D BackupManagerService: Now staging backup of com.android.vending
,03-31 15:16:06.334  1781  1781 D SystemUpdateService: onCreate
,03-31 15:16:06.337  1781  1781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
03-31 15:16:06.337   820  1054 D BackupManagerService: Now staging backup of android
,03-31 15:16:06.339  1781  3499 I SystemUpdateService: active receiver: enabled
,03-31 15:16:06.342  1781  3499 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-31 15:16:06.343   820  1054 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-31 15:16:06.344  1781  3499 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-31 15:16:06.345  1781  3499 I SystemUpdateService: now status is 0 (complete)
03-31 15:16:06.345  1781  3498 W DriveInitializer: Awaiting to be initialized
03-31 15:16:06.345  1781  3499 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-31 15:16:06.345  1781  3499 I SystemUpdateService: file has been verified
03-31 15:16:06.345  1781  3499 I SystemUpdateService: OTA package size = 25802302
,03-31 15:16:06.346  1781  3499 I SystemUpdateService: showing system update notification
,03-31 15:16:06.352   820   820 I ValidateNoPeople: skipping global notification
,03-31 15:16:06.358  1811  1826 I GmsBackupTransport: Next backup will happen in 43199121 millis.
,03-31 15:16:06.361   820  1054 I BackupManagerService: Backup pass finished.
,03-31 15:16:06.364  1781  1781 D SystemUpdateService: onDestroy
,03-31 15:16:06.386   820  3400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 31 Mar 2016 13:16:06 GMT], X-Android-Received-Millis=[1459430166386], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459430166274]}
,03-31 15:16:06.389   820   855 I ActivityManager: Start proc 3505:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-31 15:16:06.391   820  3400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-31 15:16:06.391   820  1037 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-31 15:16:06.391   820  1037 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-31 15:16:06.391   820  1037 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 15:16:06.391   820  1037 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-31 15:16:06.391   820  1037 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-31 15:16:06.392   820  1037 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-31 15:16:06.392  1076  1521 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 15:16:06.415  1781  3525 I iu.SyncManager: SYNC; picasa accounts
,03-31 15:16:06.425  1781  1781 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-31 15:16:06.429  1781  1781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-31 15:16:06.439  1781  3525 I iu.UploadsManager: num queued entries: 0
03-31 15:16:06.440  1781  3525 I iu.UploadsManager: num updated entries: 0
,03-31 15:16:06.442  1781  3525 I iu.SyncManager: NEXT; no task
,03-31 15:16:06.475  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 15:16:06.475  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:06.475  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:06.475  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:06.478  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:06.495  3230  3494 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 15:16:06.495  3230  3494 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at blb.a(PG:3937)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at czp.a(PG:18188)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:16:06.495  3230  3494 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	... 12 more
03-31 15:16:06.495  3230  3494 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at fal.a(PG:38)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:16:06.495  3230  3494 E HttpOperation: 	... 14 more
,03-31 15:16:06.507  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-31 15:16:06.509  1781  1781 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
03-31 15:16:06.514  1781  3497 W DriveInitializer: Background init thread ended
,03-31 15:16:06.533   820  1912 I ActivityManager: Start proc 3541:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-31 15:16:06.553  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 15:16:06.553  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:06.553  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:06.553  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:06.597   820  1913 I art     : Explicit concurrent mark sweep GC freed 59134(3MB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.160ms total 50.517ms
,03-31 15:16:06.602  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:06.612  3230  3494 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 15:16:06.612  3230  3494 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at hec.a(PG:42)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at hee.a(PG:102)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at czr.a(PG:65)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at kka.a(PG:108)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at czp.a(PG:19176)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:16:06.612  3230  3494 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	... 15 more
03-31 15:16:06.612  3230  3494 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at fal.a(PG:38)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:16:06.612  3230  3494 E HttpOperation: 	... 17 more
03-31 15:16:06.613  3230  3494 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 15:16:06.613  3230  3494 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at hec.a(PG:42)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at hee.a(PG:102)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at czr.a(PG:65)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at kka.a(PG:108)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	... 15 more
03-31 15:16:06.613  3230  3494 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at fal.a(PG:38)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 15:16:06.613  3230  3494 E ExperimentLoader: 	... 17 more
,03-31 15:16:06.689  3541  3541 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-31 15:16:06.689  3541  3541 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 15:16:06.689  3541  3541 I GAv4    :   adb logcat -s GAv4
,03-31 15:16:06.700  3541  3541 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:16:06.702   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 37423, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:16:06.704  3505  3562 V KeepSync: Connecting to GoogleApiClient
03-31 15:16:06.704   820  1916 I ActivityManager: Killing 3005:com.android.settings/1000 (adj 15): empty #17
,03-31 15:16:06.712  3541  3541 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:16:06.715  3541  3570 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:16:06.809   820   855 I ActivityManager: Start proc 3575:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-31 15:16:06.841  1246  1735 I art     : Explicit concurrent mark sweep GC freed 10566(611KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 984us total 23.812ms
,03-31 15:16:06.845  1781  3573 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:16:06.851  1781  3573 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 15:16:06.869  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 15:16:06.869  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:06.869  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:06.869  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:06.872  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: Handling authorization failure
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 15:16:06.883  1781  3573 E ClientConnectionOperation: 	... 7 more
,03-31 15:16:06.885  3505  3562 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-31 15:16:06.886  3505  3562 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 15:16:06.890  3505  3562 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 15:16:06.890  3505  3562 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:16:06.950  1246  3571 D GCM     : Connected
,03-31 15:16:06.959  3541  3541 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 15:16:06.964  1246  3571 D GCM     : Message class com.google.f.a.a.p
,03-31 15:16:06.972  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 15:16:06.972  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:06.972  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:06.972  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:06.975  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 15:16:06.975  3541  3541 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8787-8791)
03-31 15:16:06.975  3541  3541 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 15:16:06.979  3541  3541 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {263b69d7}
03-31 15:16:06.980  3541  3541 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 15:16:06.980  3541  3541 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 15:16:06.990  3541  3541 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 15:16:06.990  3541  3541 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 15:16:06.998  3541  3541 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 15:16:07.002  3505  3562 E KeepSync: IOException
03-31 15:16:07.002  3505  3562 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 15:16:07.002  3505  3562 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 15:16:07.002  3505  3562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 15:16:07.002  3505  3562 E KeepSync: 	... 10 more
03-31 15:16:07.002  3505  3562 W KeepSync: Sync result 2
,03-31 15:16:07.010   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37430, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:16:07.016  3541  3541 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 15:16:07.021  3541  3541 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 15:16:07.021  3541  3541 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 15:16:07.021  3541  3541 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 15:16:07.071  3541  3541 I NSApplication: Starting up...
,03-31 15:16:07.076  3541  3620 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-31 15:16:07.124   820  3206 I ActivityManager: Start proc 3625:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-31 15:16:07.128   820  3206 I ActivityManager: Killing 2456:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-31 15:16:07.330  3575  3575 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 15:16:07.339  3575  3575 I BooksApp: Created application version: 3.6.8 (30608)
,03-31 15:16:07.442  3575  3647 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 15:16:07.492  3293  3537 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-31 15:16:07.495   820  1255 I ActivityManager: Killing 3113:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-31 15:16:07.620  3575  3655 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 15:16:07.676  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:16:07.676  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:07.676  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:16:07.676  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:07.700   820  1233 I ActivityManager: Start proc 3658:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-31 15:16:07.701   820  1233 I ActivityManager: Killing 3134:com.android.musicfx/u0a18 (adj 15): empty #17
,03-31 15:16:07.810  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:07.936  1246  1263 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:16:07.936  1246  1263 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:07.936  1246  1263 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:07.936  1246  1263 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:07.940  1246  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:07.952  3575  3655 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 15:16:07.953  3575  3647 E BooksSync: Soft error
03-31 15:16:07.953  3575  3647 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:16:07.953  3575  3647 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:16:07.953  3575  3647 E BooksSync: Sync error
03-31 15:16:07.953  3575  3647 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:16:07.953  3575  3647 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:16:07.954  3575  3647 I BooksSync: Finished books sync
,03-31 15:16:07.959   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37430, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:16:07.959   820  1913 I ActivityManager: Killing 2896:com.google.android.gm/u0a78 (adj 15): empty #17
,03-31 15:16:08.168   820  1913 I ActivityManager: Killing 3182:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,03-31 15:16:08.763   820   836 I ActivityManager: Killing 3093:android.process.acore/u0a5 (adj 15): empty #17
,03-31 15:16:09.095   820  1233 I ActivityManager: Start proc 3676:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-31 15:16:09.191  3676  3676 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459430169191
03-31 15:16:09.192  3676  3676 D         : TimeServiceNative: User Time to be set is 1459430169192
03-31 15:16:09.192  3676  3676 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-31 15:16:09.192  3676  3676 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-31 15:16:09.192  3676  3676 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459430169192
03-31 15:16:09.192   372   888 D QC-time-services: Daemon: Connection accepted:time_genoff
03-31 15:16:09.192  3676  3676 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459430169192
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459430169192, operation = 0
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/17/70 9:27:47
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:Value read from RTC seconds = 19733267000
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:new time 1459430169192 
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon: delta 1439696902192 genoff 1439696902192 
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696902192 to memory
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-31 15:16:09.193   372  3693 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 15:16:09.202   372  3693 D QC-time-services: Updating the TOD offset
,03-31 15:16:09.202   372  3693 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696902192 to memory
,03-31 15:16:09.202   372  3693 D QC-time-services: Daemon:Opening File: /data/time/ats_1
,03-31 15:16:09.202   372  3693 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 15:16:09.211   372  3693 E QC-time-services: Daemon:Update to modem bit set
03-31 15:16:09.211   372  3693 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-31 15:16:09.211   372  3693 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143465369192
,03-31 15:16:09.211  3676  3676 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-31 15:16:09.279   372   888 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-31 15:16:09.285   372   886 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-31 15:16:09.347   820  1367 I ActivityManager: Start proc 3695:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-31 15:16:09.353   820  3206 I ActivityManager: Killing 3155:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-31 15:16:09.655  3695  3695 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-31 15:16:09.655  3695  3695 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 15:16:09.655  3695  3695 I GAv4    :   adb logcat -s GAv4
,03-31 15:16:09.674  3695  3695 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:16:09.691  3695  3695 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:16:09.707  3695  3714 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 15:16:09.774   820  3206 I art     : Explicit concurrent mark sweep GC freed 23423(1093KB) AllocSpace objects, 5(122KB) LOS objects, 32% free, 33MB/49MB, paused 2.268ms total 68.127ms
,03-31 15:16:09.857   820  1917 I ActivityManager: Killing 1568:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-31 15:16:09.940   820  1036 D WifiService: Client connection lost with reason: 4
,03-31 15:16:10.048   820  1036 D WifiService: New client listening to asynchronous messages
,03-31 15:16:10.049  1781  1781 V Herrevad: NQAS connected
,03-31 15:16:10.053  3293  3293 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 15:16:10.053  3293  3293 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 15:16:10.119  1781  3720 I art     : Explicit concurrent mark sweep GC freed 14462(1081KB) AllocSpace objects, 13(208KB) LOS objects, 35% free, 28MB/44MB, paused 2.297ms total 36.123ms
,03-31 15:16:10.144  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:10.226  1246  3734 I VacuumService: Vacuum at: now=1459430170226 tag=VacuumService
,03-31 15:16:10.239  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-31 15:16:10.239  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:10.239  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:10.239  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:10.243  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:10.253  3293  3725 E Babel   : UserRecoverableAuthException.
,03-31 15:16:10.253  3293  3725 E Babel   : eei: BadAuthentication
03-31 15:16:10.253  3293  3725 E Babel   : 	at eeg.a(Unknown Source)
03-31 15:16:10.253  3293  3725 E Babel   : 	at eeg.a(Unknown Source)
03-31 15:16:10.253  3293  3725 E Babel   : 	at eeg.a(Unknown Source)
03-31 15:16:10.253  3293  3725 E Babel   : 	at g.a(Unknown Source)
03-31 15:16:10.253  3293  3725 E Babel   : 	at cae.a(SourceFile:3089)
03-31 15:16:10.253  3293  3725 E Babel   : 	at cae.a(SourceFile:1131)
03-31 15:16:10.253  3293  3725 E Babel   : 	at cws.a(SourceFile:4333)
03-31 15:16:10.253  3293  3725 E Babel   : 	at cws.a(SourceFile:1419)
03-31 15:16:10.253  3293  3725 E Babel   : 	at crl.a(SourceFile:492)
03-31 15:16:10.253  3293  3725 E Babel   : 	at crl.a(SourceFile:1468)
03-31 15:16:10.253  3293  3725 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 15:16:10.253  3293  3725 E Babel   : 	at cas.b(SourceFile:106)
03-31 15:16:10.253  3293  3725 E Babel   : 	at cap.d(SourceFile:335)
03-31 15:16:10.253  3293  3725 E Babel   : 	at caq.run(SourceFile:81)
,03-31 15:16:10.254  3293  3725 E Babel   : Error getting auth token
,03-31 15:16:10.255  3293  3725 E Babel   : dvm
03-31 15:16:10.255  3293  3725 E Babel   : 	at g.a(Unknown Source)
03-31 15:16:10.255  3293  3725 E Babel   : 	at cae.a(SourceFile:3089)
03-31 15:16:10.255  3293  3725 E Babel   : 	at cae.a(SourceFile:1131)
03-31 15:16:10.255  3293  3725 E Babel   : 	at cws.a(SourceFile:4333)
03-31 15:16:10.255  3293  3725 E Babel   : 	at cws.a(SourceFile:1419)
,03-31 15:16:10.255  3293  3725 E Babel   : 	at crl.a(SourceFile:492)
03-31 15:16:10.255  3293  3725 E Babel   : 	at crl.a(SourceFile:1468)
03-31 15:16:10.255  3293  3725 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 15:16:10.255  3293  3725 E Babel   : 	at cas.b(SourceFile:106)
03-31 15:16:10.255  3293  3725 E Babel   : 	at cap.d(SourceFile:335)
03-31 15:16:10.255  3293  3725 E Babel   : 	at caq.run(SourceFile:81)
,03-31 15:16:10.259  3293  3725 E Babel   : Account registration failed 1-Redacted-21
03-31 15:16:10.259  3293  3725 E Babel   : cyp: null -- null
03-31 15:16:10.259  3293  3725 E Babel   : 	at cae.a(SourceFile:3121)
03-31 15:16:10.259  3293  3725 E Babel   : 	at cae.a(SourceFile:1131)
03-31 15:16:10.259  3293  3725 E Babel   : 	at cws.a(SourceFile:4333)
03-31 15:16:10.259  3293  3725 E Babel   : 	at cws.a(SourceFile:1419)
03-31 15:16:10.259  3293  3725 E Babel   : 	at crl.a(SourceFile:492)
03-31 15:16:10.259  3293  3725 E Babel   : 	at crl.a(SourceFile:1468)
03-31 15:16:10.259  3293  3725 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 15:16:10.259  3293  3725 E Babel   : 	at cas.b(SourceFile:106)
03-31 15:16:10.259  3293  3725 E Babel   : 	at cap.d(SourceFile:335)
03-31 15:16:10.259  3293  3725 E Babel   : 	at caq.run(SourceFile:81)
,03-31 15:16:10.279  3293  3725 I art     : Note: end time exceeds epoch: 
,03-31 15:16:10.284  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-31 15:16:10.284  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:10.284  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:10.284  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:10.286  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:10.303  3442  3733 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:16:10.316  1246  1262 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 15:16:10.330  3293  3737 E Babel   : Unexpected exception while authenticating.
03-31 15:16:10.331  3293  3737 E Babel   : eej: User intervention required. Notification has been pushed.
03-31 15:16:10.331  3293  3737 E Babel   : 	at eeg.b(Unknown Source)
03-31 15:16:10.331  3293  3737 E Babel   : 	at eeg.b(Unknown Source)
03-31 15:16:10.331  3293  3737 E Babel   : 	at g.a(Unknown Source)
03-31 15:16:10.331  3293  3737 E Babel   : 	at cae.b(SourceFile:1146)
03-31 15:16:10.331  3293  3737 E Babel   : 	at dcg.run(SourceFile:5617)
03-31 15:16:10.331  3293  3737 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:10.331  3293  3737 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:10.331  3293  3737 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-31 15:16:10.342  1246  1263 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 15:16:10.342  1246  1263 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:10.342  1246  1263 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:10.342  1246  1263 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:10.345  1246  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:10.356  3442  3733 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:16:10.357  3442  3733 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:16:10.483  1246  3738 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 15:16:10.523  1246  3738 W Uploader: No account for auth token provided,
,03-31 15:16:11.460  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:11.633  1246  3738 W Uploader: No account for auth token provided,
,03-31 15:16:11.782  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:11.959  1246  3738 I art     : Explicit concurrent mark sweep GC freed 36144(2MB) AllocSpace objects, 1(39KB) LOS objects, 37% free, 26MB/42MB, paused 1.189ms total 41.627ms
,03-31 15:16:12.018  1246  3738 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 15:16:12.019  1246  3738 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:12.019  1246  3738 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:12.019  1246  3738 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:12.023  1246  3738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:12.065  1246  3738 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 15:16:12.065  1246  3738 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 15:16:12.065  1246  3738 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 15:16:12.346  3575  3645 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 15:16:12.533  1246  3738 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 15:16:12.534  1246  3738 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:16:12.534  1246  3738 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:12.535  1246  3738 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:12.548  1246  3738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:12.610  1246  3738 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
,03-31 15:16:12.610  1246  3738 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
,03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 15:16:12.610  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 15:16:12.610  1246  3738 E Uploader: ,	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 15:16:13.310  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:13.439  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:13.906  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:15.003  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:15.157  1246  3738 W Uploader:  no longer exists, so no auth token.
,03-31 15:16:15.309  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:15.535  1246  3738 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 15:16:15.535  1246  3738 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:15.536  1246  3738 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:15.536  1246  3738 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:15.549  1246  3738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:15.627  1246  3738 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-31 15:16:15.627  1246  3738 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
,03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 15:16:15.627  1246  3738 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 15:16:15.827  1246  3738 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 15:16:15.830  1246  3738 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:16:15.832  1246  3738 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:16:15.832  1246  3738 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:15.847  1246  3738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 15:16:15.932  1246  3738 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 15:16:15.932  1246  3738 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 15:16:15.932  1246  3738 E Uploader: 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 15:16:15.932  1246  3738 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 15:16:16.106  1246  3738 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 15:16:16.107  1246  3738 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:16.107  1246  3738 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:16:16.107  1246  3738 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:16.119  1246  3738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:16.194  1246  3738 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 15:16:16.194  1246  3738 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 15:16:16.194  1246  3738 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 15:16:16.678  1246  3738 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 15:16:16.679  1246  3738 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:16:16.679  1246  3738 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:16.679  1246  3738 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:16.694  1246  3738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:16.774  1246  3738 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 15:16:16.774  1246  3738 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 15:16:16.774  1246  3738 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 15:16:17.204  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:17.331  1246  3738 W Uploader: No account for auth token provided
,03-31 15:16:17.422  2833  2849 D Finsky  : [254] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-31 15:16:17.445  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:17.528  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 15:16:17.529  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-31 15:16:17.529  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:17.529  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:17.542  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:17.590  2833  2849 D Finsky  : [254] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-31 15:16:18.021   820  1508 I art     : Explicit concurrent mark sweep GC freed 20379(909KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 2.919ms total 82.844ms
,03-31 15:16:18.158  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:18.185  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 15:16:18.185  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:18.185  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:18.185  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:18.188  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:18.205  2833  2833 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 15:16:18.205  2833  2833 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 15:16:18.206  2833  2833 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-31 15:16:25.077  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:16:37.742  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 15:16:37.743  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:37.743  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:37.743  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:37.756  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:37.802  3230  3752 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 15:16:37.802  3230  3752 E HttpOperation: java.io.IOException: Cannot obtain authentication token,
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:16:37.802  3230  3752 E HttpOperation: ,	at jcn.a(PG:1379)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at blb.a(PG:3937),
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at czp.a(PG:18188)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:16:37.802  3230  3752 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error,
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	... 12 more
,03-31 15:16:37.802  3230  3752 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at fal.a(PG:38)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:16:37.802  3230  3752 E HttpOperation: 	... 14 more,
,03-31 15:16:37.876  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 15:16:37.876  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:37.876  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:16:37.876  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:37.880  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:37.897  3230  3752 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 15:16:37.897  3230  3752 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at hec.a(PG:42)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at hee.a(PG:102)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at czr.a(PG:65)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at kka.a(PG:108)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at czp.a(PG:19176)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:16:37.897  3230  3752 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	... 15 more
03-31 15:16:37.897  3230  3752 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at fal.a(PG:38)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:16:37.897  3230  3752 E HttpOperation: 	... 17 more
,03-31 15:16:37.898  3230  3752 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 15:16:37.898  3230  3752 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at hec.a(PG:42),
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at hee.a(PG:102)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at czr.a(PG:65)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at kka.a(PG:108)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at czq.run(PG:1686),
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jdm.a(PG:77)
,03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	... 15 more
03-31 15:16:37.898  3230  3752 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at fal.a(PG:38)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 15:16:37.898  3230  3752 E ExperimentLoader: 	... 17 more
,03-31 15:16:38.022   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 199299, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:16:47.939  3442  3755 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:16:47.997  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 15:16:47.998  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:16:47.998  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:16:47.998  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:16:48.005  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:16:48.023  3442  3755 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:16:48.024  3442  3755 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:16:50.213  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:17:01.783  1264  1505 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 15:17:01.783  1264  1505 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 15:17:01.822  1246  1246 I ConfigService: onCreate
,03-31 15:17:06.866  1246  1246 I ConfigService: onDestroy
,03-31 15:17:07.604  3575  3760 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 15:17:07.630  3505  3761 V KeepSync: Connecting to GoogleApiClient
,03-31 15:17:07.651  3575  3762 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 15:17:07.721  1246  1736 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 15:17:07.721  1246  1736 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:17:07.721  1246  1736 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:17:07.722  1246  1736 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:17:07.730  1246  1736 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:17:07.730  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 15:17:07.731  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:17:07.731  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:17:07.731  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:17:07.742  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: Handling authorization failure
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 15:17:07.768  1781  3763 E ClientConnectionOperation: 	... 7 more
,03-31 15:17:07.773  3505  3761 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-31 15:17:07.779  3505  3761 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:17:07.790  3505  3761 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 15:17:07.791  3505  3761 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:17:07.843  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:17:07.843  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:17:07.843  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:17:07.843  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:17:07.847  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:17:07.859  3575  3762 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 15:17:07.860  3575  3760 E BooksSync: Soft error
03-31 15:17:07.860  3575  3760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:17:07.860  3575  3760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:17:07.860  3575  3760 E BooksSync: Sync error
03-31 15:17:07.860  3575  3760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:17:07.860  3575  3760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:17:07.860  3575  3760 I BooksSync: Finished books sync
,03-31 15:17:07.865  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-31 15:17:07.865  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:17:07.865  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:17:07.865  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:17:07.867   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 200590, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:17:07.872  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:17:07.911  3505  3761 E KeepSync: IOException
03-31 15:17:07.911  3505  3761 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 15:17:07.911  3505  3761 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 15:17:07.911  3505  3761 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 15:17:07.911  3505  3761 E KeepSync: 	... 10 more
03-31 15:17:07.911  3505  3761 W KeepSync: Sync result 2
,03-31 15:17:07.923   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 200977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:17:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:17:48.098  3442  3774 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:17:48.184  1246  1263 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 15:17:48.184  1246  1263 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:17:48.184  1246  1263 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:17:48.184  1246  1263 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:17:48.191  1246  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:17:48.217  3442  3774 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
,03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:17:48.218  3442  3774 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:17:50.375  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:18:07.838  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 15:18:07.839  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:18:07.839  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:18:07.839  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:18:07.843  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:18:07.882  1246  1262 I art     : Explicit concurrent mark sweep GC freed 60666(3MB) AllocSpace objects, 10(1028KB) LOS objects, 36% free, 28MB/44MB, paused 1.300ms total 35.392ms,
,03-31 15:18:07.895  3230  3779 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 15:18:07.895  3230  3779 E HttpOperation: java.io.IOException: Cannot obtain authentication token,
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at jdm.a(PG:82),
03-31 15:18:07.895  3230  3779 E HttpOperation: 	,at jcs.o(PG:406)
,03-31 15:18:07.895  3230  3779 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at blb.a(PG:3937)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at czp.a(PG:18188)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:18:07.895  3230  3779 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	... 12 more
03-31 15:18:07.895  3230  3779 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at fal.a(PG:38)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:18:07.895  3230  3779 E HttpOperation: 	... 14 more
,03-31 15:18:07.940  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 15:18:07.940  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:18:07.940  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:18:07.940  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:18:07.944  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:18:07.956  3230  3779 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 15:18:07.956  3230  3779 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at hec.a(PG:42)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at hee.a(PG:102)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at czr.a(PG:65)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at kka.a(PG:108)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at czp.a(PG:19176)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:18:07.956  3230  3779 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	... 15 more
03-31 15:18:07.956  3230  3779 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at fal.a(PG:38)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:18:07.956  3230  3779 E HttpOperation: 	... 17 more
03-31 15:18:07.956  3230  3779 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 15:18:07.956  3230  3779 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at hec.a(PG:42)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at hee.a(PG:102)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at czr.a(PG:65)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at kka.a(PG:108)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	... 15 more
03-31 15:18:07.956  3230  3779 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at fal.a(PG:38)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 15:18:07.956  3230  3779 E ExperimentLoader: 	... 17 more
,03-31 15:18:08.053   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 261400, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:18:25.077  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:18:37.845  3575  3786 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 15:18:37.949   820  1367 I art     : Explicit concurrent mark sweep GC freed 36339(1565KB) AllocSpace objects, 12(851KB) LOS objects, 32% free, 33MB/49MB, paused 1.509ms total 90.780ms
,03-31 15:18:37.995  3505  3787 V KeepSync: Connecting to GoogleApiClient
,03-31 15:18:38.007  3575  3788 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 15:18:38.033  1246  1263 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:18:38.033  1246  1263 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:18:38.033  1246  1263 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:18:38.033  1246  1263 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:18:38.035  1246  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:18:38.036  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 15:18:38.037  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:18:38.037  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:18:38.037  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:18:38.042  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: Handling authorization failure
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 15:18:38.055  1781  3789 E ClientConnectionOperation: 	... 7 more
,03-31 15:18:38.056  3505  3787 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 15:18:38.059  3505  3787 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:18:38.063  3505  3787 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 15:18:38.064  3505  3787 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:18:38.093  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:18:38.094  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:18:38.094  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:18:38.094  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:18:38.097  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:18:38.105  3575  3788 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 15:18:38.106  3575  3786 E BooksSync: Soft error
03-31 15:18:38.106  3575  3786 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:18:38.106  3575  3786 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:18:38.106  3575  3786 E BooksSync: Sync error
03-31 15:18:38.106  3575  3786 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:18:38.106  3575  3786 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 15:18:38.106  3575  3786 I BooksSync: Finished books sync
,03-31 15:18:38.112   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 291313, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:18:38.122  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 15:18:38.122  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:18:38.122  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:18:38.122  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:18:38.126  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:18:38.148  3505  3787 E KeepSync: IOException
03-31 15:18:38.148  3505  3787 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 15:18:38.148  3505  3787 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 15:18:38.148  3505  3787 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 15:18:38.148  3505  3787 E KeepSync: 	... 10 more
,03-31 15:18:38.149  3505  3787 W KeepSync: Sync result 2
,03-31 15:18:38.154   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 294041, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:18:41.685   820   836 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@a70c124}
,03-31 15:18:41.688   820  1035 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-31 15:18:43.400   820  1368 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@a70c124}
,03-31 15:18:43.461   820  1284 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-31 15:18:43.541   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-31 15:18:43.542   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-31 15:18:43.583   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,03-31 15:18:43.583   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-31 15:18:44.560   873   873 I kickstart: STATUS: Received file 'm9kefs1'
03-31 15:18:44.560   873   873 I kickstart: STATUS: 950272 bytes transferred in 0.975586 seconds
,03-31 15:18:44.560   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-31 15:18:44.560   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
03-31 15:18:44.563   873   873 I kickstart: STATUS: Sahara protocol completed
,03-31 15:18:50.533  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:19:06.341  1246  1246 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:19:06.410  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 15:19:06.411  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:19:06.411  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:19:06.411  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:19:06.419  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:19:06.478  1246  1735 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 15:19:06.478  1246  1735 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 15:19:06.478  1246  1735 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 15:19:06.478  1246  1735 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 15:19:06.478  1246  1735 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 15:19:06.478  1246  1735 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 15:19:06.478  1246  1735 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 15:19:06.487  2833  2874 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
,03-31 15:19:06.487  2833  2874 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 15:19:06.487  2833  2874 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 15:19:06.487  2833  2874 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 15:19:06.487  2833  2874 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
,03-31 15:19:06.487  2833  2874 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 15:19:06.487  2833  2874 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 15:19:06.527  2833  2874 W System  : Ignoring header User-Agent because its value was null.
,03-31 15:19:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:19:48.286  3442  3807 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:19:48.366  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 15:19:48.366  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:19:48.366  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:19:48.366  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:19:48.376  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:19:48.390  3442  3807 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:20:11.428  1246  1263 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 15:20:11.428  1246  1263 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:20:11.428  1246  1263 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:20:11.429  1246  1263 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:20:11.434  1246  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:20:11.468  3230  3814 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 15:20:11.468  3230  3814 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at blb.a(PG:3937)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at czp.a(PG:18188)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:20:11.468  3230  3814 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	... 12 more
03-31 15:20:11.468  3230  3814 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at fal.a(PG:38)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:20:11.468  3230  3814 E HttpOperation: 	... 14 more
,03-31 15:20:11.550  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 15:20:11.551  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:20:11.551  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:20:11.551  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:20:11.559  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:20:11.584  3230  3814 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 15:20:11.584  3230  3814 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at hec.a(PG:42)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at hee.a(PG:102)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at czr.a(PG:65)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at kka.a(PG:108)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at czp.a(PG:19176)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:20:11.584  3230  3814 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	... 15 more
03-31 15:20:11.584  3230  3814 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at fal.a(PG:38)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:20:11.584  3230  3814 E HttpOperation: 	... 17 more
03-31 15:20:11.585  3230  3814 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 15:20:11.585  3230  3814 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at hec.a(PG:42)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at hee.a(PG:102)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at czr.a(PG:65)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at kka.a(PG:108)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	... 15 more
03-31 15:20:11.585  3230  3814 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at fal.a(PG:38)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 15:20:11.585  3230  3814 E ExperimentLoader: 	... 17 more
,03-31 15:20:11.752   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 412993, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:20:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:21:11.289  3575  3826 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 15:21:11.317  3505  3827 V KeepSync: Connecting to GoogleApiClient
,03-31 15:21:11.339  3575  3828 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 15:21:11.396  1246  1736 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 15:21:11.396  1246  1736 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:21:11.396  1246  1736 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:21:11.396  1246  1736 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:21:11.400  1246  1736 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:21:11.401  1246  1263 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 15:21:11.402  1246  1263 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:21:11.402  1246  1263 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:21:11.402  1246  1263 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:21:11.409  1246  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: Handling authorization failure
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 15:21:11.421  1781  3829 E ClientConnectionOperation: 	... 7 more
,03-31 15:21:11.426  3505  3827 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 15:21:11.430  3505  3827 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:21:11.440  3505  3827 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:21:11.443  3505  3827 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:21:11.485   820  1912 I art     : Explicit concurrent mark sweep GC freed 33196(1466KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.565ms total 67.342ms
,03-31 15:21:11.531  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 15:21:11.531  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:21:11.531  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:21:11.531  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:21:11.536  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:21:11.550  1246  1736 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:21:11.551  1246  1736 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:21:11.551  1246  1736 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:21:11.551  1246  1736 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:21:11.554  1246  1736 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:21:11.565  3505  3827 E KeepSync: IOException
03-31 15:21:11.565  3505  3827 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 15:21:11.565  3505  3827 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 15:21:11.565  3505  3827 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 15:21:11.565  3505  3827 E KeepSync: 	... 10 more
03-31 15:21:11.566  3505  3827 W KeepSync: Sync result 2
,03-31 15:21:11.569  3575  3828 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 15:21:11.570  3575  3826 E BooksSync: Soft error
03-31 15:21:11.570  3575  3826 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:21:11.570  3575  3826 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 15:21:11.571  3575  3826 E BooksSync: Sync error
03-31 15:21:11.571  3575  3826 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:21:11.571  3575  3826 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:21:11.571  3575  3826 I BooksSync: Finished books sync
,03-31 15:21:11.572   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 448574, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:21:11.589   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 443188, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:21:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:22:51.172  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:23:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:23:51.336  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:24:00.294  3442  3861 V GoogleAuthProtoRequest: [349] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:24:00.360  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 15:24:00.360  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:24:00.360  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:24:00.361  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:24:00.381  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:24:00.428  1246  1736 I art     : Explicit concurrent mark sweep GC freed 57131(3MB) AllocSpace objects, 19(2MB) LOS objects, 36% free, 27MB/43MB, paused 1.784ms total 55.979ms
,03-31 15:24:00.456  3442  3861 W ExperimentUpdateService: [349] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: [349] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:24:00.457  3442  3861 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:24:18.209  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 15:24:18.210  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:24:18.211  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:24:18.212  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:24:18.226  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:24:18.278  3230  3866 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 15:24:18.278  3230  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at blb.a(PG:3937)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at czp.a(PG:18188)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:24:18.278  3230  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:24:18.278  3230  3866 E HttpOperation: 	,at jdj.a(PG:4091)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	... 12 more
03-31 15:24:18.278  3230  3866 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at fal.a(PG:38)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:24:18.278  3230  3866 E HttpOperation: 	... 14 more
,03-31 15:24:18.349  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 15:24:18.349  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:24:18.349  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:24:18.349  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:24:18.353  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:24:18.368  3230  3866 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 15:24:18.368  3230  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at hec.a(PG:42)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at hee.a(PG:102)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at czr.a(PG:65)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at kka.a(PG:108)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at czp.a(PG:19176)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:24:18.368  3230  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	... 15 more
03-31 15:24:18.368  3230  3866 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at fal.a(PG:38)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:24:18.368  3230  3866 E HttpOperation: 	... 17 more
,03-31 15:24:18.369  3230  3866 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 15:24:18.369  3230  3866 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at hec.a(PG:42)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at hee.a(PG:102)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at czr.a(PG:65)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at kka.a(PG:108)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	... 15 more
03-31 15:24:18.369  3230  3866 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at fal.a(PG:38)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 15:24:18.369  3230  3866 E ExperimentLoader: 	... 17 more
,03-31 15:24:18.527   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 659816, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:25:18.148  3575  3878 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 15:25:18.185  3575  3879 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 15:25:18.282  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 15:25:18.282  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:25:18.283  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:25:18.283  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:25:18.294  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:25:18.469  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 15:25:18.469  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:25:18.470  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:25:18.470  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:25:18.485  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:25:18.510  3575  3879 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 15:25:18.512  3575  3878 E BooksSync: Soft error
03-31 15:25:18.512  3575  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:25:18.512  3575  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:25:18.512  3575  3878 E BooksSync: Sync error
03-31 15:25:18.512  3575  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:25:18.512  3575  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 15:25:18.512  3575  3878 I BooksSync: Finished books sync
,03-31 15:25:18.519   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 719925, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:25:25.076  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:25:48.221  3505  3885 V KeepSync: Connecting to GoogleApiClient
,03-31 15:25:48.318  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-31 15:25:48.319  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:25:48.319  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:25:48.319  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:25:48.328  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: Handling authorization failure
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 15:25:48.365  1781  3886 E ClientConnectionOperation: 	... 7 more
,03-31 15:25:48.372  3505  3885 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 15:25:48.378  3505  3885 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:25:48.398  3505  3885 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 15:25:48.401  3505  3885 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:25:48.481  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 15:25:48.482  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:25:48.482  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:25:48.482  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:25:48.489  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:25:48.557  3505  3885 E KeepSync: IOException
03-31 15:25:48.557  3505  3885 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 15:25:48.557  3505  3885 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 15:25:48.557  3505  3885 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 15:25:48.557  3505  3885 E KeepSync: 	... 10 more
03-31 15:25:48.557  3505  3885 W KeepSync: Sync result 2
,03-31 15:25:48.575   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 730597, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:26:51.815  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:27:25.077  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:28:25.077  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:28:52.135  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:29:04.287  2168  2243 W bt-btm  : Stopping oneshot timer
,03-31 15:29:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:29:52.294  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:30:52.456  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:31:25.077  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:32:31.111   820   855 I art     : Explicit concurrent mark sweep GC freed 49833(2MB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 1.334ms total 71.334ms
,03-31 15:32:31.325  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 15:32:31.325  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:32:31.325  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:32:31.325  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:32:31.332  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:32:31.347  3230  3961 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 15:32:31.347  3230  3961 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at blb.a(PG:3937)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at czp.a(PG:18188)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:32:31.347  3230  3961 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	... 12 more
03-31 15:32:31.347  3230  3961 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at fal.a(PG:38)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:32:31.347  3230  3961 E HttpOperation: 	... 14 more
,03-31 15:32:31.390  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 15:32:31.391  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:32:31.391  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:32:31.391  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:32:31.396  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:32:31.416  3230  3961 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 15:32:31.416  3230  3961 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jdm.a(PG:82)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jcs.o(PG:406)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jcn.a(PG:1379)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jcs.i(PG:143)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at hec.a(PG:42)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at hee.a(PG:102)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at czr.a(PG:65)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at kka.a(PG:108)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at czp.a(PG:19176)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at czp.a(PG:9081)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at czq.run(PG:1686)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:32:31.416  3230  3961 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jdj.a(PG:4091)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jdj.a(PG:1125)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jdm.a(PG:77)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	... 15 more
03-31 15:32:31.416  3230  3961 E HttpOperation: Caused by: faj: BadAuthentication
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at fal.a(PG:38)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	at jdj.a(PG:4089)
03-31 15:32:31.416  3230  3961 E HttpOperation: 	... 17 more
,03-31 15:32:31.417  3230  3961 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 15:32:31.417  3230  3961 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at hec.a(PG:42)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at hee.a(PG:102)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at czr.a(PG:65)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at kka.a(PG:108)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	... 15 more
03-31 15:32:31.417  3230  3961 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at fal.a(PG:38)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 15:32:31.417  3230  3961 E ExperimentLoader: 	... 17 more
,03-31 15:32:31.539   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1152839, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:33:00.126   820  1508 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1d5cb389}
,03-31 15:33:00.162   820  1233 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1d5cb389}
,03-31 15:33:00.164  3442  3970 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:33:00.176  1781  3968 I EventLogService: Opted in for usage reporting
,03-31 15:33:00.187  1781  3968 I EventLogService: Aggregate from 1459429215579 (log), 1459429215579 (data)
,03-31 15:33:00.263  1246  3571 D GCM     : Message class com.google.f.a.a.i
,03-31 15:33:00.273  1246  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 15:33:00.273  1246  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:33:00.273  1246  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:33:00.273  1246  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:33:00.277  1246  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:33:00.287  3442  3970 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:33:00.288  3442  3970 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:33:00.364  1781  3968 W EventLogAggregator: Unknown tag: snet_gcore
,03-31 15:33:00.364  1781  3968 W EventLogAggregator: Unknown tag: snet_launch_service
,03-31 15:33:00.416  1781  3968 I ServiceDumpSys: dumping service [account]
,03-31 15:33:25.076  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:33:31.627  3575  3979 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 15:33:31.672  3575  3980 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 15:33:31.781  1246  1246 I art     : Explicit concurrent mark sweep GC freed 63560(3MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 27MB/43MB, paused 2.115ms total 60.116ms
,03-31 15:33:31.828  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:33:31.828  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:33:31.829  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:33:31.829  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:33:31.839  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:33:31.895  1246  1736 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 15:33:31.896  1246  1736 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:33:31.896  1246  1736 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:33:31.896  1246  1736 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:33:31.903  1246  1736 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:33:31.926  3575  3980 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 15:33:31.927  3575  3979 E BooksSync: Soft error
03-31 15:33:31.927  3575  3979 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:33:31.927  3575  3979 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:33:31.927  3575  3979 E BooksSync: Sync error
03-31 15:33:31.927  3575  3979 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 15:33:31.927  3575  3979 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 15:33:31.927  3575  3979 I BooksSync: Finished books sync
,03-31 15:33:31.937   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1213375, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:33:49.400   820   855 I UsageStatsService: User[0] Flushing usage stats to disk
,03-31 15:33:52.936  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:34:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:34:31.802  3505  3991 V KeepSync: Connecting to GoogleApiClient
,03-31 15:34:31.881  1246  1263 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 15:34:31.881  1246  1263 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:34:31.881  1246  1263 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:34:31.882  1246  1263 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:34:31.885  1246  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: Handling authorization failure
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 15:34:31.902  1781  3992 E ClientConnectionOperation: 	... 7 more
,03-31 15:34:31.904  3505  3991 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-31 15:34:31.906  3505  3991 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:34:31.909  3505  3991 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 15:34:31.910  3505  3991 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 15:34:31.968  1246  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 15:34:31.969  1246  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:34:31.969  1246  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:34:31.969  1246  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:34:31.974  1246  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:34:32.022  3505  3991 E KeepSync: IOException
03-31 15:34:32.022  3505  3991 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 15:34:32.022  3505  3991 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 15:34:32.022  3505  3991 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 15:34:32.022  3505  3991 E KeepSync: 	... 10 more
03-31 15:34:32.022  3505  3991 W KeepSync: Sync result 2
,03-31 15:34:32.033   820   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1264807, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 15:34:53.097  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:35:01.572  3442  4001 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:35:01.668  1246  1736 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 15:35:01.668  1246  1736 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:35:01.668  1246  1736 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:35:01.668  1246  1736 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:35:01.673  1246  1736 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:35:01.686  3442  4001 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:35:25.077  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:35:31.875  3442  4007 V GoogleAuthProtoRequest: [352] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:35:31.950   820   836 I art     : Explicit concurrent mark sweep GC freed 33040(1579KB) AllocSpace objects, 13(585KB) LOS objects, 31% free, 34MB/50MB, paused 1.418ms total 56.977ms
,03-31 15:35:31.985  1246  1262 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 15:35:31.985  1246  1262 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 15:35:31.986  1246  1262 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 15:35:31.986  1246  1262 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:35:31.988  1246  1262 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: [352] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: [352] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:35:31.997  3442  4007 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:35:53.255  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:37:01.814  3442  4024 V GoogleAuthProtoRequest: [353] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 15:37:01.887  1246  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 15:37:01.888  1246  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 15:37:01.888  1246  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 15:37:01.888  1246  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 15:37:01.895  1246  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:37:01.911  3442  4024 W ExperimentUpdateService: [353] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: [353] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 15:37:01.913  3442  4024 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 15:37:25.078  2168  2234 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
