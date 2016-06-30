#### Test 72145431fdae11f_thali02_HTC-HTC One M9 Logs


```
--------- beginning of main
06-30 10:35:38.624   497   497 E TPD     : [TPD][ERR] can't open /proc/7504/status...
--------- beginning of system
06-30 10:35:38.624  1127  3539 I ActivityManager: Recipient 7504
,06-30 10:35:38.684  6531  8187 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-30 10:35:38.694  1127  3743 I ActivityManager: Start proc 8188:com.htc.cs.dm/u0a89 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
06-30 10:35:38.704  8188  8188 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:38.704  8188  8188 W HTCLOG  : mask=0x18
06-30 10:35:38.704  6531  8187 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:35:38.704  6531  8187 W HTCLOG  : mask=0x18
06-30 10:35:38.764  8188  8188 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8188 dbg=false s=true
06-30 10:35:38.764  8188  8188 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
06-30 10:35:38.774  1127  3539 I ActivityManager: Start proc 8212:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
06-30 10:35:38.774  1127  3539 I ActivityManager: Killing 7725:com.google.android.talk/u0a103 (adj 15): empty #17
06-30 10:35:38.774  1127  3539 D Process : killProcessQuiet, pid=7725
06-30 10:35:38.774  1127  3539 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
06-30 10:35:38.784  8212  8212 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:38.784  8212  8212 W HTCLOG  : mask=0x18
06-30 10:35:38.834  8209  8209 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
06-30 10:35:38.834  8209  8209 W HTCLOG  : mask=0x18
06-30 10:35:38.854  1127  3535 I ActivityManager: Recipient 7725
06-30 10:35:38.884  1127  3060 D PMS     : acquireWL(27156db4): PARTIAL_WAKE_LOCK  *alarm* 0x1 1127 1000 WorkSource{10019}
06-30 10:35:38.884  1127  3060 V AlarmManager: sending alarm PendingIntent{38c4bddd: PendingIntentRecord{138c5d52 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=67369, Int=0
06-30 10:35:38.894  1127  3060 V AlarmManager: sending alarm PendingIntent{26ede37f: PendingIntentRecord{329c6e09 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=70138, Int=0
06-30 10:35:38.894  1127  3060 V AlarmManager: sending alarm PendingIntent{1d4bf4c: PendingIntentRecord{15d1fe20 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=71259, Int=0
06-30 10:35:38.904  1127  3497 D PMS     : acquireWL(354a44aa): PARTIAL_WAKE_LOCK  Icing 0x1 5331 10019 null
06-30 10:35:38.944  1127  3539 D PMS     : releaseWL(354a44aa): PARTIAL_WAKE_LOCK  Icing 0x1 null
06-30 10:35:38.954  1127  3365 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 10:35:38.954  1127  3550 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 10:35:38.984  8209  8236 W HTCLOG  : use specified tag [cutils-trace], func [0].
06-30 10:35:38.984  8209  8236 W HTCLOG  : mask=0x18
06-30 10:35:38.984  8209  8236 E cutils-trace: Error opening trace file: Permission denied (13)
06-30 10:35:38.984  8212  8212 D DocsApplication: Plugin installer initialized.
06-30 10:35:38.984  1127  3111 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 10:35:39.004  8212  8212 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{dd56eba com.google.android.apps.docs}
06-30 10:35:39.014  8212  8212 D TAG     : onCreate()
06-30 10:35:39.024  8212  8212 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
06-30 10:35:39.034  1127  3365 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 10:35:39.044  8209  8209 D CustomizationManager: ====startRecUseTime====
06-30 10:35:39.044  8209  8209 D htc.customization.log.level:  is 
06-30 10:35:39.044  8209  8209 W CustomizationLogLevel: Level value is invalid, use default level 2
06-30 10:35:39.044  1127  1146 D PMS     : acquireWL(34c9abe4): PARTIAL_WAKE_LOCK  Icing 0x1 5331 10019 null
06-30 10:35:39.054  6531  8187 I ApplicationLogger: canRun() : Opted Out
06-30 10:35:39.054  6531  8187 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 371 ms] updated apps [took 371 ms] 
06-30 10:35:39.114  8209  8209 D CustomizationManager:  Read ACC file spent 0.038 (s)
06-30 10:35:39.124  8209  8209 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: Parsing tag category name = application
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: Parsing tag category name = system
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 10:35:39.124  8209  8209 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 10:35:39.124  8209  8209 D CustomizationManager:  Read CID file spent 0.085 (s)
06-30 10:35:39.124  8209  8209 D CustomizationManager:  All configurations done spent 0.085 (s)
06-30 10:35:39.134  3526  3920 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
06-30 10:35:39.134  3526  3920 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2c9915b5 +
06-30 10:35:39.134  3526  3920 I Prism.WidgetManager: onLoadItems() +
06-30 10:35:39.154  3526  3920 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
06-30 10:35:39.164  1127  3494 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8209 on display 0
06-30 10:35:39.164  1127  1179 D PMS     : acquireHCC(295d84d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1127 1000 null
06-30 10:35:39.164  1127  1179 D PMS     : acquireHCC(1a42bf02): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1127 1000 null
06-30 10:35:39.174  1127  3494 V WindowManager: addAppToken: AppWindowToken{74ac49 token=Token{2367a250 ActivityRecord{22a2013 u0 com.test.thalitest/.MainActivity t43}}} to stack=1 task=43 at 0
06-30 10:35:39.184  1127  3494 I ActivityManager: Start proc 8250:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
06-30 10:35:39.184  8209  8209 W HTCLOG  : use specified tag [IPCThreadState], func [0].
06-30 10:35:39.184  8209  8209 W HTCLOG  : mask=0x18
06-30 10:35:39.184  8209  8248 W HTCLOG  : use specified tag [Vector], func [0].
06-30 10:35:39.194  8250  8250 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:39.194  8250  8250 W HTCLOG  : mask=0x18
06-30 10:35:39.184  8209  8248 W HTCLOG  : mask=0x18
06-30 10:35:39.204   546   546 I art     : Explicit concurrent mark sweep GC freed 8661(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 237us total 18.126ms
06-30 10:35:39.214  3315  3315 D DotMatrix: [EventService]  onDisplayChanged: 0
06-30 10:35:39.214  1127  1127 V ActivityManager: Display changed displayId=0
06-30 10:35:39.214   546   546 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 93us total 9.327ms
06-30 10:35:39.214  3315  3315 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
06-30 10:35:39.214  1127  3497 D ActivityManager: screenshot for ActivityRecord{22a2013 u0 com.test.thalitest/.MainActivity t43}, bitmap=null, time = 0
06-30 10:35:39.214  3526  3526 I TrimMemoryManager: [trimMemory] 20
06-30 10:35:39.224   546   546 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 94us total 7.777ms
06-30 10:35:39.264  8250  8250 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
06-30 10:35:39.314  3501  4180 D PhoneApp: EVENT_QUERY_MO_PACKAGES
06-30 10:35:39.314  3501  4180 D PhoneApp: -- N1 =0
06-30 10:35:39.314  3501  4180 D PhoneApp: -- N2 =0
06-30 10:35:39.314  3501  4180 D PhoneApp: -- N3 =0
06-30 10:35:39.314  3526  3920 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:35:39.314  8250  8250 I LibraryLoader: Time to load native libraries: 29 ms (timestamps 3779-3808)
06-30 10:35:39.314  8250  8250 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:39.324  8250  8250 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27dbbc86}
06-30 10:35:39.334  8250  8250 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:39.334  8250  8250 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:35:39.334  8250  8250 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:35:39.344  8250  8250 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:39.344  8250  8250 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 10:35:39.374  8250  8273 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
06-30 10:35:39.384  8250  8277 D BluetoothAdapter: 27543879: getState() :  mService = null. Returning STATE_OFF
06-30 10:35:39.384  8250  8250 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
06-30 10:35:39.384  8250  8250 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
06-30 10:35:39.384  8250  8250 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
06-30 10:35:39.394  8250  8250 W HTCLOG  : use specified tag [libEGL], func [3].
06-30 10:35:39.394  8250  8250 W HTCLOG  : mask=0x18
06-30 10:35:39.394  8250  8250 W HTCLOG  : use specified tag [libEGL], func [3].
06-30 10:35:39.394  8250  8250 W HTCLOG  : mask=0x18
06-30 10:35:39.394  8250  8250 I Adreno  : QUALCOMM build                   : 065751b, 
06-30 10:35:39.394  8250  8250 I Adreno  : Build Date                       : 04/15/15
06-30 10:35:39.394  8250  8250 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
06-30 10:35:39.394  8250  8250 I Adreno  : Local Branch                     : 
06-30 10:35:39.394  8250  8250 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
06-30 10:35:39.394  8250  8250 I Adreno  : Remote Branch                    : NONE
06-30 10:35:39.394  8250  8250 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,06-30 10:35:39.434  3526  3920 I Prism.WidgetManager: onLoadItems() -
06-30 10:35:39.434  3526  3920 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2c9915b5 -
,06-30 10:35:39.474  8250  8283 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup,
,06-30 10:35:39.494  8250  8250 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:39.504  8250  8250 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:35:39.514  8250  8250 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,06-30 10:35:39.514  8250  8250 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:39.514  8250  8250 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:39.544  8250  8294 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,06-30 10:35:39.544  8250  8294 W HTCLOG  : mask=0x18
,06-30 10:35:39.544  1127  3743 V WindowManager: Adding window Window{19e666f1 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{13d22f67 u0 com.htc.launcher/com.htc.launcher.Launcher})
,06-30 10:35:39.544  1127  3571 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,06-30 10:35:39.564  8250  8250 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
06-30 10:35:39.564  8250  8250 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
06-30 10:35:39.564  8250  8250 W HTCLOG  : mask=0x18
06-30 10:35:39.564  8250  8250 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:35:39.564  8250  8250 W HTCLOG  : mask=0x18
06-30 10:35:39.574  8250  8294 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,06-30 10:35:39.574  8250  8294 W HTCLOG  : mask=0x18
06-30 10:35:39.574  8250  8294 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:35:39.574  8250  8294 W HTCLOG  : mask=0x18
,06-30 10:35:39.574  8250  8294 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
06-30 10:35:39.574  8250  8294 W HTCLOG  : mask=0x18
06-30 10:35:39.574  8250  8294 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:35:39.574  8250  8294 W HTCLOG  : mask=0x18
,06-30 10:35:39.584  8250  8294 W HTCLOG  : use specified tag [Surface], func [3].
,06-30 10:35:39.584  8250  8294 W HTCLOG  : mask=0x18
06-30 10:35:39.584  8250  8294 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
06-30 10:35:39.584  8250  8294 W HTCLOG  : mask=0x18
,06-30 10:35:39.584  8250  8294 W HTCLOG  : use specified tag [qdmemalloc], func [0].
06-30 10:35:39.584  8250  8294 W HTCLOG  : mask=0x18
,06-30 10:35:39.634  1127  1170 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +420ms (total +464ms),
,06-30 10:35:39.674  8250  8250 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8250
,06-30 10:35:39.754  8212  8303 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,06-30 10:35:39.754  8212  8303 W HTCLOG  : mask=0x18
,06-30 10:35:39.754  8250  8250 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:35:39.794  8250  8297 D jxcore_app_log: JniHelper::setJavaVM(0xab519b70), pthread_self() = -1404352424
,06-30 10:35:39.804  8212  8212 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,06-30 10:35:39.804  8250  8297 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
,06-30 10:35:39.804  8250  8297 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:39.804  8250  8297 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:39.804  8250  8297 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:39.804  8250  8297 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:35:39.804  8250  8297 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b98a72 added. We now have 1 listener(s)
06-30 10:35:39.804  1127  1146 I ActivityManager: Start proc 8312:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,06-30 10:35:39.814  1127  1147 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-30 10:35:39.814  8250  8297 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
06-30 10:35:39.814  8250  8297 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
,06-30 10:35:39.814  8250  8297 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:35:39.814  8250  8297 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 10:35:39.814  8312  8312 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:39.814  8312  8312 W HTCLOG  : mask=0x18
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:35:39.814  8250  8297 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2388c279 added. We now have 1 listener(s)
06-30 10:35:39.814  1127  3086 D WifiService: New client listening to asynchronous messages
06-30 10:35:39.814  8250  8297 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 10:35:39.814  8250  8297 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:39.814  8250  8297 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:35:39.814  8250  8297 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-30 10:35:39.814  8250  8297 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:39.814  8250  8297 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:35:39.814  8250  8297 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:35:39.824  8250  8297 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:35:39.824  1127  3539 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-30 10:35:39.824  8250  8297 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
,06-30 10:35:39.824  8250  8297 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:39.824  8250  8297 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 10:35:39.824  8250  8297 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:39.824  8250  8297 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:39.824  8250  8297 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:35:39.844  8312  8312 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:39.844  8250  8250 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:40.034  1127  3550 D PMS     : acquireWL(2b5b3647): PARTIAL_WAKE_LOCK  AsyncService 0x1 8312 10128 null
,06-30 10:35:40.034  1127  3535 D PMS     : releaseWL(2b5b3647): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,06-30 10:35:40.054  5331  6758 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
,06-30 10:35:40.064  1127  1147 I ActivityManager: Killing 7490:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
,06-30 10:35:40.064  1127  1147 D Process : killProcessQuiet, pid=7490
06-30 10:35:40.064  1127  1147 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,06-30 10:35:40.074  5331  6758 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,06-30 10:35:40.144  1127  3497 I ActivityManager: Recipient 7490
,06-30 10:35:40.174  8250  8333 W jxcore-log: Initializing JXcore engine
06-30 10:35:40.174  8250  8333 W jxcore-log: JXcore engine is ready
06-30 10:35:40.174  3881  3881 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 10:35:40.174  1127  1179 D PMS     : releaseHCC(295d84d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
06-30 10:35:40.174  1127  1179 D PMS     : releaseHCC(1a42bf02): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,06-30 10:35:40.194  3881  3881 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 10:35:40.194  3881  3881 D c       : Getting all permits...
06-30 10:35:40.194  3881  3881 D a       : Opening database...
,06-30 10:35:40.204  3881  3881 D a       : Opening database auth.proximity.permit_store...
,06-30 10:35:40.204  3881  3881 D a       : Closing database...,
,06-30 10:35:40.214  5331  6758 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
06-30 10:35:40.214  5331  5331 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 10:35:40.214  1127  1147 D PMS     : releaseWL(34c9abe4): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,06-30 10:35:40.234  8250  8333 W jxcore-log: Starting JXcore engine
,06-30 10:35:40.244  1127  3494 D PMS     : acquireWL(b08ac12): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 3881 10019 null
,06-30 10:35:40.244  7611  7611 D AlarmReceiver: ACTION_RESTART_INTENT,
06-30 10:35:40.244  5331  8342 D LocationInitializer: Restart initialization of location
,06-30 10:35:40.254  7611  7611 D LocalBluetoothProfile: getPriorityOnValue = 100
06-30 10:35:40.254  1127  1127 D PMS     : releaseWL(27156db4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
06-30 10:35:40.254  7611  7611 D LocalBluetoothProfile: getPriorityOffValue = 0
06-30 10:35:40.254  7611  7611 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
06-30 10:35:40.254  7611  7611 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
06-30 10:35:40.254  3881  8343 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
06-30 10:35:40.254  3881  8343 D libc    : [NET] android_getaddrinfofornet-, err=8
06-30 10:35:40.254  3881  8343 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
06-30 10:35:40.254  3881  8343 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-30 10:35:40.254  3881  8343 D libc    : [NET] android_getaddrinfo_proxy+
06-30 10:35:40.254  3881  8343 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-30 10:35:40.254   514  8344 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,06-30 10:35:40.264   514  8344 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504,
06-30 10:35:40.264   514  8344 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
06-30 10:35:40.264   514  8344 D libc    : [NET] android_getaddrinfofornet-, err=7
06-30 10:35:40.264  3881  8343 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,06-30 10:35:40.264  1127  3111 D PMS     : releaseWL(b08ac12): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,06-30 10:35:40.274  7611  8346 D HtcModeClient: start the htcmodeservice thread
,06-30 10:35:40.274  7611  8346 D HtcModeClient: initCanAgent
,06-30 10:35:40.274  7611  8346 I CANMesgAgentLocalSocket: CANAgent Id = 0
,06-30 10:35:40.284  7611  8346 D HtcModeClient: sense info: version = none, id = 2,
06-30 10:35:40.284  7611  8346 D HtcModeClient: display info: width = 1080, height = 1776
,06-30 10:35:40.284  7611  8346 D HtcModeClient: display info: mode = 10
,06-30 10:35:40.334  8250  8333 W jxcore-log: Platform android,
06-30 10:35:40.334  8250  8333 W jxcore-log: 
06-30 10:35:40.334  8250  8333 W jxcore-log: Process ARCH arm
06-30 10:35:40.334  8250  8333 W jxcore-log: 
,06-30 10:35:40.384  7611  7611 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: CONNECTION_READY = false
06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: PHONE_PULGIN = false
,06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: Force_AWAKE = false
06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: PHONE_PULGIN = true
06-30 10:35:40.384  7611  7611 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-30 10:35:40.524  8250  8333 I jxcore-log: JXcore Cordova bridge is ready!,
06-30 10:35:40.524  8250  8333 I jxcore-log: 
06-30 10:35:40.524  8250  8333 W jxcore-log: JXcore engine is started
,06-30 10:35:40.524  8250  8297 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
06-30 10:35:40.534  8250  8250 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
06-30 10:35:40.534  8250  8333 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-30 10:35:40.534  8250  8333 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 10:35:40.544  8250  8250 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
06-30 10:35:40.544  8250  8250 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 10:35:40.554  8250  8250 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 10:35:40.554  8250  8250 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
06-30 10:35:40.554  8250  8250 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 10:35:40.554  8250  8250 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 10:35:40.554  8250  8250 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 10:35:40.554  8250  8250 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 10:35:40.554  8250  8250 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b98a72 removed from the list
06-30 10:35:40.554  8250  8250 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 10:35:40.554  8250  8250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2388c279 removed from the list
06-30 10:35:40.554  8250  8250 D io.jxcore.node.ConnectivityMonitor: stop
06-30 10:35:40.554  8250  8250 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,06-30 10:35:40.564  8250  8250 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 10:35:40.724  8349  8349 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
06-30 10:35:40.724  8349  8349 W HTCLOG  : mask=0x18
,06-30 10:35:40.934  8349  8352 W HTCLOG  : use specified tag [cutils-trace], func [0].
06-30 10:35:40.934  8349  8352 W HTCLOG  : mask=0x18
,06-30 10:35:40.934  8349  8352 E cutils-trace: Error opening trace file: Permission denied (13)
,06-30 10:35:40.994  8349  8349 D CustomizationManager: ====startRecUseTime====,
06-30 10:35:40.994  8349  8349 D htc.customization.log.level:  is 
06-30 10:35:40.994  8349  8349 W CustomizationLogLevel: Level value is invalid, use default level 2
,06-30 10:35:41.074  8349  8349 D CustomizationManager:  Read ACC file spent 0.042 (s),
,06-30 10:35:41.084  8349  8349 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
,06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: Parsing tag category name = application
06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: Parsing tag category name = system,
06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: Parsing tag category name = Settings,
06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: Parsing tag category name = ACC,
,06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000,
,06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
06-30 10:35:41.084  8349  8349 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,06-30 10:35:41.094  8349  8349 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 10:35:41.094  8349  8349 D CustomizationManager:  Read CID file spent 0.095 (s)
06-30 10:35:41.094  8349  8349 D CustomizationManager:  All configurations done spent 0.096 (s)
,06-30 10:35:41.144  1127  3539 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8349, uid=2000
,06-30 10:35:41.144  1127  1162 D Process : killProcessQuiet, pid=8250,
06-30 10:35:41.144  1127  1162 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
06-30 10:35:41.144  1127  1162 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
06-30 10:35:41.144  1127  1162 I ActivityManager: Killing 8250:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
,06-30 10:35:41.234   523   523 W HTCLOG  : use specified tag [Vector], func [0].
06-30 10:35:41.234   523   523 W HTCLOG  : mask=0x18
,06-30 10:35:41.274  1127  1146 I ActivityManager: Recipient 8250,
06-30 10:35:41.274  1127  3086 D WifiService: Client connection lost with reason: 4
,06-30 10:35:41.374  1127  1146 W ActivityManager: Spurious death for ProcessRecord{1874785b 8250:com.test.thalitest/u0a142}, curProc for 8250: null,
,06-30 10:35:41.384  1127  1181 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed,
,06-30 10:35:41.434  1127  3068 D PMS     : acquireWL(17a528f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1127 1000 null
06-30 10:35:41.444  3315  3315 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
06-30 10:35:41.444  1127  3111 D PMS     : acquireWL(b9e31d1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4296 10019 null
06-30 10:35:41.444  3315  3315 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
06-30 10:35:41.444  4296  4447 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 10:35:41.444  1127  3539 D PMS     : releaseWL(b9e31d1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
06-30 10:35:41.444  3685  4081 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,06-30 10:35:41.454  1127  3069 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
,06-30 10:35:41.464  1127  3063 W SystemReader: Cannot find grip_rejection_width, use default value instead
06-30 10:35:41.464  6531  6531 I art     : Explicit concurrent mark sweep GC freed 12279(759KB) AllocSpace objects, 2(40KB) LOS objects, 34% free, 3MB/5MB, paused 439us total 78.069ms
,06-30 10:35:41.484  5331  5331 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
06-30 10:35:41.484  3685  4081 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
06-30 10:35:41.484  3704  8367 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,06-30 10:35:41.494  1127  3535 D PMS     : acquireWL(361b26ca): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 5331 10019 null
,06-30 10:35:41.494  1127  3068 D PMS     : releaseWL(17a528f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-30 10:35:41.494  1127  3069 V NetworkPolicy: writePolicyLocked()
06-30 10:35:41.504  1127  1127 W PackageManager: Unable to load service info ResolveInfo{304e7d04 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
06-30 10:35:41.504  1127  1127 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:35:41.504  1127  1127 W PackageManager: 	,at android.os.Looper.loop(Looper.java:155)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:35:41.504  1127  1127 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:35:41.504  3526  3526 I art     : Explicit concurrent mark sweep GC freed 25639(1823KB) AllocSpace objects, 23(1436KB) LOS objects, 33% free, 31MB/47MB, paused 1.641ms total 77.352ms
06-30 10:35:41.504  3685  4081 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,06-30 10:35:41.514  1127  3069 D NetworkPolicy: notifyPoliciesChangeLocked: no change
,06-30 10:35:41.514  1127  3069 V NetworkPolicy: updateNetworkEnabledLocked()
06-30 10:35:41.514  3501  3501 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
06-30 10:35:41.514  1127  3069 V NetworkPolicy: updateNotificationsLocked(),
06-30 10:35:41.514  3881  3881 I ConfigService: onCreate
,06-30 10:35:41.524  1127  1161 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
06-30 10:35:41.514  3881  3881 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:35:41.524  5331  5331 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:35:41.524  3685  4081 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,06-30 10:35:41.534  3881  3881 I ConfigService: onBind returning update interface
,06-30 10:35:41.534  1127  1127 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,06-30 10:35:41.534  3881  3881 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,06-30 10:35:41.534  3881  3881 I ConfigService: onBind returning config service
,06-30 10:35:41.554  1127  3539 I ActivityManager: Start proc 8369:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
06-30 10:35:41.554  1127  3494 D PMS     : acquireWL(1d02cf93): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3881 10019 null
06-30 10:35:41.564  8369  8369 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:41.564  8369  8369 W HTCLOG  : mask=0x18
06-30 10:35:41.564  3685  4081 E ExternalAccountType: Unsupported attribute readOnly
06-30 10:35:41.564  1127  3365 D PMS     : releaseWL(1d02cf93): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,06-30 10:35:41.574  1127  1161 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-30 10:35:41.584  3881  3881 I ConfigService: onDestroy
,06-30 10:35:41.594  3526  3920 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,06-30 10:35:41.594  3526  3920 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-30 10:35:41.594  8369  8369 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
06-30 10:35:41.594  8369  8369 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:35:41.604  3526  3526 I Launcher: Deferring update until onResume
06-30 10:35:41.604  3526  3526 D Launcher: waitUntilResume // bindAppsRemoved,
,06-30 10:35:41.614  8369  8369 I MultiDex: VM with version 2.1.0 has multidex support
06-30 10:35:41.614  8369  8369 I MultiDex: install
,06-30 10:35:41.614  8369  8369 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:35:41.624  3526  3526 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
06-30 10:35:41.624  8369  8369 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,06-30 10:35:41.624  3526  3526 I ThreadedRenderer: Defer allocateBuffers to drawing time
,06-30 10:35:41.634  8369  8369 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,06-30 10:35:41.634  1127  1181 I art     : Explicit concurrent mark sweep GC freed 34309(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 1.786ms total 211.490ms,
06-30 10:35:41.634  1127  5655 I art     : WaitForGcToComplete blocked for 141.011ms for cause Explicit
,06-30 10:35:41.644  5331  8393 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
06-30 10:35:41.644  5331  8393 D AccountUtils: Clearing selected account for com.test.thalitest,
,06-30 10:35:41.674  1127  3550 I ActivityManager: Start proc 8396:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
,06-30 10:35:41.684  8396  8396 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:41.684  8396  8396 W HTCLOG  : mask=0x18
06-30 10:35:41.704  3461  3461 D Nfc-Utils: isNxpCodebase: isNxp=false
06-30 10:35:41.724  8349  8349 I art     : System.exit called, status: 0
06-30 10:35:41.724  8349  8349 W HTCLOG  : use specified tag [Vector], func [0].
06-30 10:35:41.724  8349  8349 W HTCLOG  : mask=0x18
06-30 10:35:41.734  5331  8423 I PeopleContactsSync: CP2 sync disabled
06-30 10:35:41.734  1127  1146 D PMS     : acquireWL(62f0a32): PARTIAL_WAKE_LOCK  Icing 0x1 5331 10019 null
06-30 10:35:41.734  5331  6758 I Icing   : doRemovePackageData com.test.thalitest
06-30 10:35:41.734  1127  3550 D PMS     : releaseWL(62f0a32): PARTIAL_WAKE_LOCK  Icing 0x1 null
06-30 10:35:41.734  1127  3535 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=5331, uid=10019, userID:0
06-30 10:35:41.744  7853  8421 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
06-30 10:35:41.754  1127  3496 D Process : killProcessQuiet, pid=7565
06-30 10:35:41.754  1127  3496 I ActivityManager: Killing 7565:com.htc.sdm/u0a61 (adj 15): empty #17
06-30 10:35:41.754  1127  3496 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
06-30 10:35:41.834  1127  5655 I art     : Explicit concurrent mark sweep GC freed 7160(372KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/22MB, paused 2.175ms total 193.710ms
06-30 10:35:41.834  1127  3111 I ActivityManager: Recipient 7565
06-30 10:35:41.864  3685  3685 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
06-30 10:35:41.874  3594  8425 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
06-30 10:35:41.874  3594  8425 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
06-30 10:35:41.884  5331  8422 W GmsApplication: Using Auth Proxy for data requests.
06-30 10:35:41.894  3526  3526 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
06-30 10:35:41.894  3526  3526 I ContextualWidget: package com.test.thalitest removed
06-30 10:35:41.894  3526  3932 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
06-30 10:35:41.904  5331  8422 W GmsApplication: Using Auth Proxy for data requests.
06-30 10:35:41.904  3526  8427 I ContextualWidget: com.test.thalitest is not installed
06-30 10:35:41.904  3526  8427 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
06-30 10:35:41.924  1127  1147 I ActivityManager: Start proc 8430:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
06-30 10:35:41.934  8430  8430 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:41.934  8430  8430 W HTCLOG  : mask=0x18
06-30 10:35:41.954  3526  3932 I ContextualWidget: MFU.onDownloadDataSetChanged
06-30 10:35:41.954  3526  3932 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
06-30 10:35:41.954  3526  3526 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId 2883125a-4e69-41a4-bbaf-f6401db475a9, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
06-30 10:35:41.954  3526  3526 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 2883125a-4e69-41a4-bbaf-f6401db475a9, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
06-30 10:35:41.974  5331  8429 I art     : Explicit concurrent mark sweep GC freed 12535(797KB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 3MB/5MB, paused 2.416ms total 64.856ms
06-30 10:35:41.974  5331  5346 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
06-30 10:35:41.974  5331  5346 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
06-30 10:35:41.974  5331  5346 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
06-30 10:35:42.014  5331  8417 W DriveInitializer: Awaiting to be initialized
06-30 10:35:42.014  5331  8453 W DriveInitializer: Background init thread started
06-30 10:35:42.014  5331  8453 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error
06-30 10:35:42.014  5331  8453 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:35:42.014  5331  8453 W HTCLOG  : mask=0x18
06-30 10:35:42.014  5331  8453 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55d3fdd540
06-30 10:35:42.024  5331  8453 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
06-30 10:35:42.024  5331  8453 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
06-30 10:35:42.024  5331  8453 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
06-30 10:35:42.024  5331  8453 W DriveInitializer: Background init thread ended
06-30 10:35:42.024  5331  8453 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
06-30 10:35:42.024  5331  8453 E AndroidRuntime: Process: com.google.android.gms, PID: 5331
06-30 10:35:42.024  5331  8453 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
06-30 10:35:42.024  5331  8453 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
06-30 10:35:42.024  5331  8417 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 10:35:42.024  5331  8417 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55d3fdd540
06-30 10:35:42.034  1127  3365 E ActivityManager: App crashed! Process: com.google.android.gms
06-30 10:35:42.034  5331  8417 E DriveAsyncService: disk I/O error (code 3850)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.034  5331  8417 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.034  5331  8453 D Process : killProcess, pid=5331
06-30 10:35:42.034  5331  8453 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
06-30 10:35:42.034  5331  8453 W HTCLOG  : use specified tag [Process], func [0].
06-30 10:35:42.034  5331  8453 W HTCLOG  : mask=0x18
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: Can't write: system_app_crash
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.044  1127  8454 E DropBoxManagerService: 	... 5 more
06-30 10:35:42.064  8430  8430 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
06-30 10:35:42.064  1127  4096 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
06-30 10:35:42.074  8430  8430 D IdefixUninstallListener: package_removed = com.test.thalitest
06-30 10:35:42.104  8430  8430 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:35:42.104  8430  8430 W HTCLOG  : mask=0x18
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:35:42.104  8430  8430 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:35:42.104  8430  8430 W System.err: java.sql.SQLException: Getting a writable database from helper a@37b2a50d failed
06-30 10:35:42.104  1127  3497 I ActivityManager: Killing 7798:com.htc.calendar/u0a6 (adj 15): empty #17
06-30 10:35:42.104  8430  8430 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
06-30 10:35:42.104  8430  8430 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
06-30 10:35:42.104  8430  8430 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
06-30 10:35:42.114  1127  3494 I ActivityManager: Recipient 5331
06-30 10:35:42.104  8430  8430 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
06-30 10:35:42.114  1127  4096 D PMS     : handleWLDeath(29a183f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
06-30 10:35:42.104  8430  8430 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
06-30 10:35:42.114  1127  1147 D PMS     : handleWLDeath(9e1ed4a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
06-30 10:35:42.104  8430  8430 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
06-30 10:35:42.104  8430  8430 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
06-30 10:35:42.114  1127  3539 D PMS     : handleWLDeath(361b26ca): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
06-30 10:35:42.104  8430  8430 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 10:35:42.104  8430  8430 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:42.104  8430  8430 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:42.104  8430  8430 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:35:42.104  8430  8430 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:35:42.104  8430  8430 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.104  8430  8430 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.104  8430  8430 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
06-30 10:35:42.104  8430  8430 W System.err: 	... 15 more
06-30 10:35:42.104  1127  3497 D Process : killProcessQuiet, pid=7798
06-30 10:35:42.104  1127  3497 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
06-30 10:35:42.184  1127  3550 I ActivityManager: Recipient 7798
06-30 10:35:42.214  1127  3494 I ActivityManager: Process com.google.android.gms (pid 5331) has died
06-30 10:35:42.214  1127  3494 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
06-30 10:35:42.214  1127  3494 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
06-30 10:35:42.224  6531  8457 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-30 10:35:42.264  1127  3111 I ActivityManager: Start proc 8458:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
06-30 10:35:42.264  3526  3825 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
06-30 10:35:42.274  6531  8457 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 10:35:42.274  6531  8457 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:35:42.274  6531  8457 W HTCLOG  : mask=0x18
06-30 10:35:42.274  6531  8457 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55d3e5bd70
06-30 10:35:42.274  8458  8458 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:42.274  8458  8458 W HTCLOG  : mask=0x18
06-30 10:35:42.284  6531  8457 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
06-30 10:35:42.284  6531  8457 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
06-30 10:35:42.284  6531  8457 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6531
06-30 10:35:42.284  6531  8457 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.284  6531  8457 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.284  1127  3111 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: Can't write: system_app_crash
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.294  1127  8479 E DropBoxManagerService: 	... 5 more
06-30 10:35:42.294  6531  8457 D Process : killProcess, pid=6531
06-30 10:35:42.294  6531  8457 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
06-30 10:35:42.294  6531  8457 W HTCLOG  : use specified tag [Process], func [0].
06-30 10:35:42.294  6531  8457 W HTCLOG  : mask=0x18
06-30 10:35:42.314  8458  8458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
06-30 10:35:42.324  8458  8482 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:35:42.324  8458  8482 W HTCLOG  : mask=0x18
06-30 10:35:42.324  8458  8482 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
06-30 10:35:42.324  8458  8482 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.keychain/databases/grants.db) - 
06-30 10:35:42.324  8458  8482 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:35:42.324  8458  8482 W HTCLOG  : mask=0x18
06-30 10:35:42.324  8458  8482 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.keychain/databases/grants.db, flag: 6, ret: 14
06-30 10:35:42.324  8458  8482 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.324  8458  8482 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.324  1127  3535 D PMS     : acquireWL(3b4f052c): PARTIAL_WAKE_LOCK  AsyncService 0x1 8312 10128 null
06-30 10:35:42.324  8458  8482 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
06-30 10:35:42.324  8458  8482 E AndroidRuntime: Process: com.android.keychain, PID: 8458
06-30 10:35:42.324  8458  8482 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.324  8458  8482 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.324  1127  3111 D PMS     : releaseWL(3b4f052c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
06-30 10:35:42.324  1127  3497 E ActivityManager: App crashed! Process: com.android.keychain
06-30 10:35:42.334  1127  3497 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 10:35:42.334  8188  8188 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
06-30 10:35:42.334  8188  8188 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
06-30 10:35:42.334  1127  3497 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.334  1127  3497 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.334  1127  3497 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.334  1127  3497 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:42.334  1127  3497 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 10:35:42.334  1127  3497 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.334  1127  3497 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.334  1127  3497 W System.err: 	... 14 more
06-30 10:35:42.334  1127  3497 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.334  1127  3497 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.334  1127  3497 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.334  1127  3497 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:42.334  1127  3497 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 10:35:42.334  1127  3497 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 10:35:42.344  1127  4096 I ActivityManager: Recipient 6531
06-30 10:35:42.334  1127  3497 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.334  1127  3497 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.344  1127  3086 D WifiService: Client connection lost with reason: 4
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.334  1127  3497 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.334  1127  3497 W System.err: 	... 14 more
06-30 10:35:42.344  8188  8188 I DeviceManagement: WorkflowService: Starting workflow service
06-30 10:35:42.344  1127  8485 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 10:35:42.344  1127  8485 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467275742352.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:42.344  1127  8485 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.344  1127  8485 E ErrorReport: 	... 4 more
06-30 10:35:42.344  8188  8484 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@140da9d] args=[Bundle[mParcelledData.dataSize=112]]
06-30 10:35:42.344  8188  8484 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-30 10:35:42.344  8188  8484 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
06-30 10:35:42.344  8188  8484 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-30 10:35:42.344  8188  8484 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
06-30 10:35:42.354  1127  3494 I ActivityManager: Start proc 8486:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
06-30 10:35:42.364  8458  8482 D Process : killProcess, pid=8458
06-30 10:35:42.354  1127  4096 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6531) has died
06-30 10:35:42.364  8458  8482 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 10:35:42.354  1127  4096 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20861ms
06-30 10:35:42.364  1127  3571 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.354  1127  4096 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 20861ms
06-30 10:35:42.364  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.364  8458  8482 W HTCLOG  : use specified tag [Process], func [0].
06-30 10:35:42.364  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.364  8458  8482 W HTCLOG  : mask=0x18
06-30 10:35:42.364  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.364  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.364  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 10:35:42.364  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 10:35:42.364  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 10:35:42.364  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 10:35:42.364  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 10:35:42.364  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 10:35:42.364  1127  3571 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.364  1127  3571 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.364  1127  3571 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.364  1127  3571 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.364  8486  8486 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:42.364  8486  8486 W HTCLOG  : mask=0x18
06-30 10:35:42.364  1127  3571 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.364  1127  3571 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.364  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.364  1127  3571 W System.err: 	... 12 more
06-30 10:35:42.374  8188  8484 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
06-30 10:35:42.384  8188  8507 I DeviceManagement: SessionStateController: Checking invariants...
06-30 10:35:42.394  7611  8346 I HtcModeClient: handler message = 4011
06-30 10:35:42.394  7611  8346 D HtcModeClient: getConnectionCheckCount first 0
06-30 10:35:42.394  7611  8346 D HtcModeClient: getConnectionCheckCount count = 4
06-30 10:35:42.394  7611  8346 E HtcModeClient: Check connection and retry 5 times.
06-30 10:35:42.394  7611  8346 D HtcModeClient: setConnectionCheckCount count = 5
06-30 10:35:42.394  7611  8346 D HtcModeClient: setupRestart delayedTime = 3000
06-30 10:35:42.394  8486  8486 W ContextImpl: Unable to create files subdir /data/data/com.android.documentsui/cache
06-30 10:35:42.394  8486  8486 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
06-30 10:35:42.394  7611  7645 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
06-30 10:35:42.394  7611  7611 D HtcModeClient: setBtPriority priority = on
06-30 10:35:42.394  7611  7611 D HtcModeClient: unbindBlueToothService
06-30 10:35:42.394  7611  7611 D HtcModeClient: Don't start project servcice
06-30 10:35:42.394  7611  7611 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
06-30 10:35:42.394  7611  7611 D HtcModeClient: connectState: CONNECTION_READY = false
06-30 10:35:42.394  7611  7611 D SilentMusic: call stop
06-30 10:35:42.394  7611  7611 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-30 10:35:42.394  7611  7611 D HtcModeClient: onDestroy
06-30 10:35:42.394  7611  8347 W CANMesgAgentLocalSocket: read the terminate packet, so break
06-30 10:35:42.424  8486  8486 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:35:42.424  8486  8486 W HTCLOG  : mask=0x18
06-30 10:35:42.424  8486  8486 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
06-30 10:35:42.424  8486  8486 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.documentsui/databases/recents.db) - 
06-30 10:35:42.424  8486  8486 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:35:42.424  8486  8486 W HTCLOG  : mask=0x18
06-30 10:35:42.424  8486  8486 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.documentsui/databases/recents.db, flag: 6, ret: 14
06-30 10:35:42.424  8486  8486 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:35:42.424  8486  8486 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: FATAL EXCEPTION: main
06-30 10:35:42.424  8486  8486 E AndroidRuntime: Process: com.android.documentsui, PID: 8486
06-30 10:35:42.424  8486  8486 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 10:35:42.424  8486  8486 E AndroidRuntime: 	... 9 more
06-30 10:35:42.424  1127  3743 I ActivityManager: Killing 7652:com.google.android.gm/u0a97 (adj 15): empty #17
06-30 10:35:42.424  1127  3743 D Process : killProcessQuiet, pid=7652
06-30 10:35:42.424  1127  3743 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
06-30 10:35:42.454  1127  1146 I ActivityManager: Recipient 8458
06-30 10:35:42.494  8188  8507 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:35:42.494  8188  8507 W HTCLOG  : mask=0x18
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 10:35:42.494  8188  8507 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,06-30 10:35:42.544  1127  3496 I ActivityManager: Recipient 7652
,06-30 10:35:42.644  1127  1146 I ActivityManager: Process com.android.keychain (pid 8458) has died
,06-30 10:35:42.644  1127  1146 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 30573ms
,06-30 10:35:42.654  5714  5857 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
06-30 10:35:42.654  1127  1147 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 10:35:42.654  5714  5857 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:35:42.654  1127  3539 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 10:35:42.654  5714  5857 W HTCLOG  : mask=0x18
06-30 10:35:42.664  1127  3550 I ActivityManager: Killing 7827:com.htc.mobiledata:remote/u0a40 (adj 15): empty #17
06-30 10:35:42.654  5714  5857 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55d3e650f0
06-30 10:35:42.654  1127  1147 E ActivityManager: App crashed! Process: com.android.documentsui
06-30 10:35:42.654  5714  5857 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
06-30 10:35:42.654  5714  5857 E AndroidRuntime: Process: android.process.media, PID: 5714
06-30 10:35:42.654  5714  5857 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.654  5714  5857 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:35:42.654  8072  8087 E AndroidHttpClient: Leak found
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: ,	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:42.654  8072  8087 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:35:42.654  ,8072  8087 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:35:42.654  1127  3539 E ActivityManager: App crashed! Process: android.process.media
06-30 10:35:42.654  8188  8507 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:42.654  8188  8484 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:42.654  8188  8484 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
06-30 10:35:42.654  1127  1147 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.654  1127  1147 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,06-30 10:35:42.654  1127  1147 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.654  1127  1147 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.654  1127  1147 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.654  1127  1147 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 10:35:42.654  1127  1147 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:42.654  1127  1147 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 10:35:42.654  1127  1147 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
,06-30 10:35:42.674  1127  3494 I ActivityManager: Recipient 7827
06-30 10:35:42.654  1127  1147 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:42.654  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:42.654  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 10:35:42.654  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:42.654  1127  1147 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
,06-30 10:35:42.654  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 10:35:42.654  1127  1147 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.654  1127  1147 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.654  1127  1147 W System.err: 	,at libcore.io.Posix.open(Native Method)
06-30 10:35:42.654  1127  1147 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.654  1127  1147 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.654  1127  1147 W System.err: 	... 14 more
06-30 10:35:42.664  1127  3550 D Process : killProcessQuiet, pid=7827
,06-30 10:35:42.664  1127  3550 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
06-30 10:35:42.664  1127  1147 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.664  1127  1147 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.664  1127  1147 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.664  1127  1147 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.664  1127  1147 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.664  1127  1147 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
,06-30 10:35:42.664  1127  1147 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:42.664  1127  1147 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 10:35:42.664  1127  1147 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 10:35:42.664  1127  1147 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:42.664  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:42.664  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
,06-30 10:35:42.664  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:42.664  1127  1147 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 10:35:42.664  1127  1147 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 10:35:42.664  1127  1147 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.664  1127  1147 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.664  1127  1147 W System.err: 	at libcore.io.Posix.open(Native Method)
,06-30 10:35:42.664  1127  1147 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.664  1127  1147 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.664  1127  1147 W System.err: 	... 14 more
06-30 10:35:42.664  1127  3539 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.664  1127  3539 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,06-30 10:35:42.664  1127  3539 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.664  1127  3539 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
,06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:42.664  1127  3539 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
,06-30 10:35:42.664  1127  3539 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.664  1127  3539 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.664  1127  3539 W System.err: 	... 14 more
,06-30 10:35:42.664  1127  3539 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.664  1127  3539 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.664  1127  3539 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.664  1127  3539 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
,06-30 10:35:42.664  1127  3539 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:42.664  1127  3539 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
,06-30 10:35:42.664  1127  3539 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 10:35:42.664  1127  3539 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.664  1127  3539 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.664  1127  3539 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.664  1127  3539 W System.err: 	... 14 more
,06-30 10:35:42.674  8188  8484 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowServic,e.onHandleIntent(WorkflowService.java:295)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.674  8188  8484 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.674  8188  8484 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@140da9d]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.674  8188  8484 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:35:42.774  8188  8188 I DeviceManagement: WorkflowService: Stopping workflow service
06-30 10:35:42.774  1127  3571 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.774  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.774  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.774  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,06-30 10:35:42.774  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,06-30 10:35:42.774  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
,06-30 10:35:42.774  1127  8511 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 10:35:42.774  1127  8511 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467275742788.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:42.774  1127  8511 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,06-30 10:35:42.774  1127  8511 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.774  1127  8511 E ErrorReport: 	... 4 more
06-30 10:35:42.774  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 10:35:42.774  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
,06-30 10:35:42.774  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 10:35:42.774  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 10:35:42.774  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 10:35:42.774  1127  3571 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.774  1127  3571 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.774  1127  3571 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.774  1127  3571 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,06-30 10:35:42.784  1127  3571 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.784  1127  3571 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.784  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.784  1127  3571 W System.err: 	... 12 more
06-30 10:35:42.784  1127  3571 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.784  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.784  1127  8510 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 10:35:42.784  1127  8510 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467275742788.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:42.784  1127  8510 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.784  1127  8510 E ErrorReport: 	... 4 more
06-30 10:35:42.784  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.784  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.784  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.784  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 10:35:42.784  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 10:35:42.784  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 10:35:42.784  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 10:35:42.784  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 10:35:42.784  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 10:35:42.784  1127  3571 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.784  1127  3571 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.784  1127  3571 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.784  1127  3571 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.784  1127  3571 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.784  1127  3571 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.784  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.784  1127  3571 W System.err: 	... 12 more
,06-30 10:35:42.794  1127  3497 I ActivityManager: Start proc 8512:com.android.externalstorage/u0a15 for content provider com.android.externalstorage/.ExternalStorageProvider
,06-30 10:35:42.804  8486  8486 D Process : killProcess, pid=8486,
06-30 10:35:42.804  8486  8486 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 10:35:42.804  8486  8486 W HTCLOG  : use specified tag [Process], func [0].
,06-30 10:35:42.804  8486  8486 W HTCLOG  : mask=0x18
,06-30 10:35:42.814  8512  8512 W HTCLOG  : use specified tag [FDManager], func [0].,
06-30 10:35:42.814  1127  1162 I ActivityManager: Start proc 8521:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
06-30 10:35:42.814  8512  8512 W HTCLOG  : mask=0x18
06-30 10:35:42.814  1127  3535 I ActivityManager: Killing 7423:com.google.android.music:main/u0a115 (adj 15): empty #17
06-30 10:35:42.814  5714  5857 D Process : killProcess, pid=5714
06-30 10:35:42.814  5714  5857 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 ,
06-30 10:35:42.814  1127  3535 D Process : killProcessQuiet, pid=7423
06-30 10:35:42.814  1127  3535 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
06-30 10:35:42.814  8521  8521 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:42.814  8521  8521 W HTCLOG  : mask=0x18
06-30 10:35:42.814  5714  5857 W HTCLOG  : use specified tag [Process], func [0].
06-30 10:35:42.814  5714  5857 W HTCLOG  : mask=0x18
,06-30 10:35:42.884  1127  1147 D MediaRouterService: Client com.google.android.music (pid 7423): Died!
06-30 10:35:42.884  1127  1147 I ActivityManager: Recipient 7423
,06-30 10:35:42.904  7038  7065 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 10:35:42.904  7038  7065 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:35:42.904  7038  7065 W HTCLOG  : mask=0x18
06-30 10:35:42.904  7038  7065 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore, handle: 0xac17c0c0
06-30 10:35:42.904  7038  7065 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 10:35:42.904  7038  7065 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore, handle: 0xac17c0c0
,06-30 10:35:42.924  1127  4096 D Process : killProcessQuiet, pid=7381,
06-30 10:35:42.924  1127  4096 I ActivityManager: Killing 7381:com.htc.mobiledata/u0a40 (adj 15): empty #17
06-30 10:35:42.924  1127  4096 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.attachApplicationLocked:6484 
,06-30 10:35:42.944  1127  3539 I ActivityManager: Recipient 5714
06-30 10:35:42.944  1127  3494 I ActivityManager: Recipient 8486
,06-30 10:35:43.024  1127  3111 I ActivityManager: Recipient 7381,
,06-30 10:35:43.054  1127  3494 I ActivityManager: Process com.android.documentsui (pid 8486) has died
,06-30 10:35:43.054  1127  3539 I ActivityManager: Process android.process.media (pid 5714) has died,
,06-30 10:35:43.054  1127  3539 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 30160ms
,06-30 10:35:43.064  3315  3765 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
,06-30 10:35:43.074  3225  3225 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,06-30 10:35:43.084  8512  8512 W ContextImpl: Unable to create files subdir /data/user/0/com.android.externalstorage/cache
06-30 10:35:43.084  8512  8512 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,06-30 10:35:43.094  8512  8512 D ExternalStorage: After updating volumes, found 1 active roots
06-30 10:35:43.094  3526  3920 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
06-30 10:35:43.094  3526  3920 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2c9915b5 +
06-30 10:35:43.094  3526  3920 I Prism.WidgetManager: onLoadItems() +
,06-30 10:35:43.094  8521  8521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 ,
,06-30 10:35:43.104  8521  8556 D PowerUtils: getUserIdOfProcess, curUserId = 0
06-30 10:35:43.104  8521  8556 D PowerUtils: isRunningUnderOwner, isOwner = true
,06-30 10:35:43.114  1127  3743 I ActivityManager: Start proc 8557:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
,06-30 10:35:43.114  3526  3920 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
06-30 10:35:43.114  8521  8556 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
06-30 10:35:43.124  8557  8557 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:35:43.124  8557  8557 W HTCLOG  : mask=0x18,
,06-30 10:35:43.124  8521  8556 D PowerUsageService: removed uid = 10142,
,06-30 10:35:43.134  8521  8556 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:35:43.134  8521  8556 W HTCLOG  : mask=0x18
,06-30 10:35:43.134   545   545 I art     : Explicit concurrent mark sweep GC freed 8662(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 133us total 23.433ms
,06-30 10:35:43.134  8521  8556 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	,at android.os.Looper.loop(Looper.java:155)
06-30 10:35:43.134  8521  8556 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
,06-30 10:35:43.134  8521  8556 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8521
06-30 10:35:43.134  8521  8556 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelpe,r.java:163)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:43.134  8521  8556 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:43.144  1127  3365 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 10:35:43.144  1127  3365 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
06-30 10:35:43.144  1127  3365 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:43.144  1127  3365 W System.err: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:43.144  1127  3365 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:43.144  1127  8578 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 10:35:43.144  1127  8578 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467275743157.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:43.144  1127  8578 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:43.144  1127  8578 E ErrorReport: 	... 4 more
06-30 10:35:43.144  1127  3365 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:43.144  1127  3365 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 10:35:43.144  1127  3365 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:43.144  1127  3365 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:43.144  1127  3365 W System.err: 	... 14 more
06-30 10:35:43.144  1127  3365 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:43.144  1127  3365 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:43.144  1127  3365 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:43.144 , 1127  3365 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 10:35:43.144  1127  3365 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 10:35:43.144  1127  3365 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 10:35:43.144  1127  3365 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:43.144  1127  3365 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:43.144  1127  3365 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:43.144  1127  3365 W System.err: 	... 14 more
,06-30 10:35:43.144  1127  3571 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 10:35:43.144  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:43.144  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:43.144  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:43.144  1127  3571 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:43.144  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 10:35:43.144  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 10:35:43.144  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 10:35:43.144  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 10:35:43.144  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 10:35:43.144  1127  3571 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 10:35:43.144  1127  3571 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:35:43.144  1127  3571 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:43.144  1127  3571 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:43.154  8521  8556 D Process : killProcess, pid=8521
06-30 10:35:43.154  8521  8556 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 10:35:43.154  8521  8556 W HTCLOG  : use specified tag [Process], func [0].
06-30 10:35:43.154  8521  8556 W HTCLOG  : mask=0x18
06-30 10:35:43.154   545   545 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 125us total 20.023ms
06-30 10:35:43.154  1127  3571 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:43.154  1127  3571 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:43.154  1127  3571 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:43.154  1127  3571 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:43.154  1127  3571 W System.err: 	... 12 more
,06-30 10:35:43.174   545   545 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 123us total 17.135ms

```
