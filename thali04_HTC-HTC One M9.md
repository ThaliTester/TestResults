#### Test 82337235c858ce8_thali04_HTC-HTC One M9 Logs


```
--------- beginning of main
08-23 15:46:05.807  3571  3985 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-23 15:46:05.807  3571  3985 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@31ce2d70 +
08-23 15:46:05.807  3571  3985 I Prism.WidgetManager: onLoadItems() +
--------- beginning of system
08-23 15:46:05.827  3571  3985 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-23 15:46:05.867  4046  5639 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-23 15:46:05.907  4046  5639 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-23 15:46:05.957  3549  4173 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-23 15:46:05.957  3549  4173 D PhoneApp: -- N1 =0
08-23 15:46:05.957  3549  4173 D PhoneApp: -- N2 =0
08-23 15:46:05.957  3549  4173 D PhoneApp: -- N3 =0
08-23 15:46:05.967  4046  5639 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-23 15:46:05.967  1108  4135 D PMS     : releaseWL(345e7fde): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-23 15:46:06.017  3571  3985 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 15:46:06.147  3571  3985 E Prism.WidgetManager: The same lists. No need to update. skip it.
08-23 15:46:06.147  3571  3985 I Prism.WidgetManager: onLoadItems() -
08-23 15:46:06.147  3571  3985 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@31ce2d70 -
08-23 15:46:06.287  8893  8926 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 15:46:06.287  8893  8926 W HTCLOG  : mask=0x18
,08-23 15:46:06.357  8893  8893 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-23 15:46:06.357  1108  3614 D PMS     : acquireWL(19e0ee53): PARTIAL_WAKE_LOCK  AsyncService 0x1 8621 10128 null
08-23 15:46:06.357  1108  3784 D PMS     : releaseWL(19e0ee53): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-23 15:46:06.497  8937  8937 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-23 15:46:06.497  8937  8937 W HTCLOG  : mask=0x18
08-23 15:46:06.567  3549  3742 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-23 15:46:06.567  3549  3742 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
08-23 15:46:06.707  8937  8940 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-23 15:46:06.707  8937  8940 W HTCLOG  : mask=0x18
08-23 15:46:06.707  8937  8940 E cutils-trace: Error opening trace file: Permission denied (13)
08-23 15:46:06.747  1108  3031 D PMS     : acquireWL(3701c489): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10027}
08-23 15:46:06.757  8937  8937 D CustomizationManager: ====startRecUseTime====
08-23 15:46:06.747  1108  3031 V AlarmManager: sending alarm PendingIntent{989c8e: PendingIntentRecord{5c33333 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=84754, Int=0
08-23 15:46:06.757  8937  8937 D htc.customization.log.level:  is 
08-23 15:46:06.757  8937  8937 W CustomizationLogLevel: Level value is invalid, use default level 2
08-23 15:46:06.757  1108  3031 V AlarmManager: sending alarm PendingIntent{24821caf: PendingIntentRecord{e7db8bc android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81656, Int=0
08-23 15:46:06.757  8655  8655 D AlarmReceiver: ACTION_RESTART_INTENT
08-23 15:46:06.757  8655  8655 D LocalBluetoothProfile: getPriorityOnValue = 100
08-23 15:46:06.767  1108  1108 D PMS     : releaseWL(3701c489): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-23 15:46:06.767  8655  8655 D LocalBluetoothProfile: getPriorityOffValue = 0
08-23 15:46:06.767  8655  8655 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-23 15:46:06.767  8655  8655 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-23 15:46:06.787  8655  8953 D HtcModeClient: start the htcmodeservice thread
08-23 15:46:06.787  8655  8953 D HtcModeClient: initCanAgent
08-23 15:46:06.787  8655  8953 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-23 15:46:06.787  8655  8953 D HtcModeClient: sense info: version = none, id = 2
08-23 15:46:06.797  8655  8953 D HtcModeClient: display info: width = 1080, height = 1776
08-23 15:46:06.797  8655  8953 D HtcModeClient: display info: mode = 10
08-23 15:46:06.837  8937  8937 D CustomizationManager:  Read ACC file spent 0.043 (s)
08-23 15:46:06.837  8937  8937 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: Parsing tag category name = application
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: Parsing tag category name = system
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: Parsing tag category name = Settings
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: Parsing tag category name = ACC
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-23 15:46:06.837  8937  8937 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-23 15:46:06.837  8937  8937 D CustomizationManager:  Read CID file spent 0.086 (s)
08-23 15:46:06.837  8937  8937 D CustomizationManager:  All configurations done spent 0.086 (s)
08-23 15:46:06.877  1108  1129 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8937 on display 0
08-23 15:46:06.887  1108  1129 V WindowManager: addAppToken: AppWindowToken{2fd460c0 token=Token{3ad21243 ActivityRecord{4875bf2 u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-23 15:46:06.887  8655  8655 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-23 15:46:06.887  1108  1176 D PMS     : acquireHCC(352812fd): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1108 1000 null
08-23 15:46:06.887  1108  1176 D PMS     : acquireHCC(2767e1f9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1108 1000 null
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 15:46:06.897  1108  1129 I ActivityManager: Start proc 8957:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = false
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: Force_AWAKE = false
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = true
08-23 15:46:06.897  8655  8655 D HtcModeClient: connectState: POWERCONNECTED_READY = true
08-23 15:46:06.907  8937  8937 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-23 15:46:06.907  8937  8937 W HTCLOG  : mask=0x18
08-23 15:46:06.907  8937  8955 W HTCLOG  : use specified tag [Vector], func [0].
08-23 15:46:06.907  8937  8955 W HTCLOG  : mask=0x18
08-23 15:46:06.907  8957  8957 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 15:46:06.907  8957  8957 W HTCLOG  : mask=0x18
08-23 15:46:06.917  3361  3361 D DotMatrix: [EventService]  onDisplayChanged: 0
08-23 15:46:06.917  1108  1108 V ActivityManager: Display changed displayId=0
08-23 15:46:06.917  3361  3361 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-23 15:46:06.927  1108  3528 D ActivityManager: screenshot for ActivityRecord{4875bf2 u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-23 15:46:06.947  3571  3571 I TrimMemoryManager: [trimMemory] 20
08-23 15:46:06.967  8957  8957 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-23 15:46:07.027  8957  8957 I LibraryLoader: Time to load native libraries: 26 ms (timestamps 5434-5460)
08-23 15:46:07.027  8957  8957 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:46:07.037  8957  8957 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e36bf03}
08-23 15:46:07.037  8957  8957 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:46:07.037  8957  8957 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 15:46:07.047  8957  8957 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 15:46:07.047  8957  8957 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:46:07.047  8957  8957 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 15:46:07.097  5490  5511 D BluetoothAdapterService(1057636797): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@246d2486
08-23 15:46:07.107  8957  8957 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-23 15:46:07.107  8957  8957 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
08-23 15:46:07.107  8957  8957 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
08-23 15:46:07.107  8957  8957 W HTCLOG  : use specified tag [libEGL], func [3].
08-23 15:46:07.107  8957  8957 W HTCLOG  : mask=0x18
08-23 15:46:07.117  8957  8957 W HTCLOG  : use specified tag [libEGL], func [3].
08-23 15:46:07.117  8957  8957 W HTCLOG  : mask=0x18
08-23 15:46:07.117  8957  8957 I Adreno  : QUALCOMM build                   : 065751b, 
08-23 15:46:07.117  8957  8957 I Adreno  : Build Date                       : 04/15/15
08-23 15:46:07.117  8957  8957 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-23 15:46:07.117  8957  8957 I Adreno  : Local Branch                     : 
08-23 15:46:07.117  8957  8957 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-23 15:46:07.117  8957  8957 I Adreno  : Remote Branch                    : NONE
08-23 15:46:07.117  8957  8957 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,08-23 15:46:07.187  8957  8990 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,08-23 15:46:07.197  8957  8957 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-23 15:46:07.207  8957  8957 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 15:46:07.217  8957  8957 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,08-23 15:46:07.227  8957  8957 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
08-23 15:46:07.227  8957  8957 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:46:07.247  8957  9001 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 15:46:07.247  8957  9001 W HTCLOG  : mask=0x18
,08-23 15:46:07.257  1108  3446 V WindowManager: Adding window Window{3d92eea1 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{dcf4f3c u0 com.htc.launcher/com.htc.launcher.Launcher}),
,08-23 15:46:07.257  1108  3659 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true,
,08-23 15:46:07.287  8957  8957 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
08-23 15:46:07.287  8957  8957 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-23 15:46:07.287  8957  8957 W HTCLOG  : mask=0x18
08-23 15:46:07.287  8957  8957 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 15:46:07.287  8957  8957 W HTCLOG  : mask=0x18
,08-23 15:46:07.297  8957  9001 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
08-23 15:46:07.297  8957  9001 W HTCLOG  : mask=0x18
08-23 15:46:07.297  8957  9001 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 15:46:07.297  8957  9001 W HTCLOG  : mask=0x18
08-23 15:46:07.297  8957  9001 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 15:46:07.297  8957  9001 W HTCLOG  : mask=0x18
,08-23 15:46:07.297  8957  9001 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 15:46:07.297  8957  9001 W HTCLOG  : mask=0x18
,08-23 15:46:07.307  8957  9001 W HTCLOG  : use specified tag [Surface], func [3].
,08-23 15:46:07.307  8957  9001 W HTCLOG  : mask=0x18
,08-23 15:46:07.307  8957  9001 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-23 15:46:07.307  8957  9001 W HTCLOG  : mask=0x18
08-23 15:46:07.307  8957  9001 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-23 15:46:07.307  8957  9001 W HTCLOG  : mask=0x18
,08-23 15:46:07.347  1108  1164 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +423ms (total +463ms),
,08-23 15:46:07.387  8957  8957 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8957
,08-23 15:46:07.457  8957  8957 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 15:46:07.507  8957  9004 D jxcore_app_log: JniHelper::setJavaVM(0xab2fdb70), pthread_self() = -1406556328
,08-23 15:46:07.507  8957  9004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 15:46:07.507  8957  9004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 15:46:07.507  8957  9004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 15:46:07.507  8957  9004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 15:46:07.507  8957  9004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 15:46:07.507  8957  9004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ae3e5e added. We now have 1 listener(s)
08-23 15:46:07.507  1108  1130 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,08-23 15:46:07.507  8957  9004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-23 15:46:07.517  8957  9004 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
,08-23 15:46:07.517  8957  9004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 15:46:07.517  8957  9004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 15:46:07.517  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 15:46:07.527  8957  9004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae94855 added. We now have 1 listener(s),
08-23 15:46:07.527  8957  9004 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 15:46:07.527  1108  3074 D WifiService: New client listening to asynchronous messages
,08-23 15:46:07.527  8957  9004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 15:46:07.527  8957  9004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 15:46:07.527  8957  9004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 15:46:07.527  8957  9004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
08-23 15:46:07.527  8957  9004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 15:46:07.527  8957  9004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 15:46:07.527  1108  3528 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-23 15:46:07.527  8957  9004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
,08-23 15:46:07.537  5490  5815 D BluetoothAdapterService(1057636797): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@246d2486
,08-23 15:46:07.537  8957  9004 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:46:07.537  8957  9004 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 15:46:07.537  8957  9004 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 15:46:07.537  8957  9004 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 15:46:07.537  8957  9004 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 15:46:07.537  8957  8957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:46:07.547  8957  8957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:46:07.557  8957  8957 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 15:46:07.877  1108  1176 D PMS     : releaseHCC(352812fd): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
08-23 15:46:07.877  1108  1176 D PMS     : releaseHCC(2767e1f9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-23 15:46:07.877  8957  9010 W jxcore-log: Initializing JXcore engine
,08-23 15:46:07.877  8957  9010 W jxcore-log: JXcore engine is ready
,08-23 15:46:07.897  8957  8975 I art     : Background sticky concurrent mark sweep GC freed 6991(465KB) AllocSpace objects, 0(0B) LOS objects, 3% free, 7MB/7MB, paused 7.161ms total 15.552ms
,08-23 15:46:07.907  1108  3640 D PMS     : acquireWL(159762aa): PARTIAL_WAKE_LOCK  Icing 0x1 4046 10019 null
,08-23 15:46:07.947  8957  9010 W jxcore-log: Starting JXcore engine,
,08-23 15:46:07.957  1108  3536 D PMS     : releaseWL(159762aa): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,08-23 15:46:07.967  1108  3541 D PMS     : acquireWL(3b60ff76): PARTIAL_WAKE_LOCK  Icing 0x1 4046 10019 null,
,08-23 15:46:08.007  1108  1130 D PMS     : releaseWL(3b60ff76): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,08-23 15:46:08.047  8957  9010 W jxcore-log: Platform android,
08-23 15:46:08.047  8957  9010 W jxcore-log: 
08-23 15:46:08.047  8957  9010 W jxcore-log: Process ARCH arm
08-23 15:46:08.047  8957  9010 W jxcore-log: 
,08-23 15:46:08.227  8957  9010 I jxcore-log: JXcore Cordova bridge is ready!,
08-23 15:46:08.227  8957  9010 I jxcore-log: 
08-23 15:46:08.227  8957  9010 W jxcore-log: JXcore engine is started
,08-23 15:46:08.237  8957  9004 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 15:46:08.237  8957  8957 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 15:46:08.357   566   566 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-23 15:46:08.907  8655  8953 I HtcModeClient: handler message = 4011,
08-23 15:46:08.907  8655  8953 D HtcModeClient: getConnectionCheckCount first 0
08-23 15:46:08.907  8655  8953 D HtcModeClient: getConnectionCheckCount count = 6,
,08-23 15:46:08.907  8655  8953 E HtcModeClient: Check connection and retry 7 times.
,08-23 15:46:08.917  8655  8953 D HtcModeClient: setConnectionCheckCount count = 7
,08-23 15:46:08.917  8655  8953 D HtcModeClient: setupRestart delayedTime = 3000
,08-23 15:46:08.917  8655  8655 D HtcModeClient: setBtPriority priority = on
,08-23 15:46:08.917  8655  8655 D HtcModeClient: unbindBlueToothService
08-23 15:46:08.917  8655  8655 D HtcModeClient: Don't start project servcice
08-23 15:46:08.927  8655  8655 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-23 15:46:08.927  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 15:46:08.927  8655  8655 D SilentMusic: call stop
08-23 15:46:08.927  8655  8655 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-23 15:46:08.927  8655  8954 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-23 15:46:08.927  8655  8655 D HtcModeClient: onDestroy
,08-23 15:46:10.307  8893  8893 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-23 15:46:10.307  1108  3446 D Process : killProcessQuiet, pid=8061
08-23 15:46:10.307  1108  3446 I ActivityManager: Killing 8061:com.google.android.apps.photos/u0a126 (adj 15): empty #17
08-23 15:46:10.307  1108  3446 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-23 15:46:10.407  1108  3541 I ActivityManager: Recipient 8061
,08-23 15:46:11.257  8893  8925 I GAV2    : Thread[GAThread,5,main]: No campaign data found.,
,08-23 15:46:13.017  1108  1108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,08-23 15:46:13.917  1108  3031 D PMS     : acquireWL(5b0b050): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10027},
08-23 15:46:13.927  1108  3031 V AlarmManager: sending alarm PendingIntent{2fd3a249: PendingIntentRecord{5c33333 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=90356, Int=0,
,08-23 15:46:13.927  8655  8655 D AlarmReceiver: ACTION_RESTART_INTENT
,08-23 15:46:13.937  1108  1108 D PMS     : releaseWL(5b0b050): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-23 15:46:13.937  8655  8655 D LocalBluetoothProfile: getPriorityOnValue = 100
08-23 15:46:13.937  8655  8655 D LocalBluetoothProfile: getPriorityOffValue = 0,
08-23 15:46:13.937  8655  8655 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-23 15:46:13.937  8655  8655 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-23 15:46:13.957  8655  9025 D HtcModeClient: start the htcmodeservice thread,
08-23 15:46:13.967  8655  9025 D HtcModeClient: initCanAgent
08-23 15:46:13.967  8655  9025 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-23 15:46:13.967  8655  9025 D HtcModeClient: sense info: version = none, id = 2
,08-23 15:46:13.967  8655  9025 D HtcModeClient: display info: width = 1080, height = 1776,
08-23 15:46:13.967  8655  9025 D HtcModeClient: display info: mode = 10
,08-23 15:46:14.067  8655  8655 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: BT_TURNON_BYME = false
,08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false,
08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = false
08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: Force_AWAKE = false
08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = true
08-23 15:46:14.067  8655  8655 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-23 15:46:14.257  1108  3536 D PMS     : releaseWL(3666c0aa): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,08-23 15:46:16.077  8655  9025 I HtcModeClient: handler message = 4011,
08-23 15:46:16.077  8655  9025 D HtcModeClient: getConnectionCheckCount first 0
08-23 15:46:16.077  8655  9025 D HtcModeClient: getConnectionCheckCount count = 7
08-23 15:46:16.077  8655  9025 E HtcModeClient: Check connection and retry 8 times.
08-23 15:46:16.077  8655  9025 D HtcModeClient: setConnectionCheckCount count = 8
08-23 15:46:16.077  8655  9025 D HtcModeClient: setupRestart delayedTime = 3000
,08-23 15:46:16.087  8655  8655 D HtcModeClient: setBtPriority priority = on,
08-23 15:46:16.087  8655  8655 D HtcModeClient: unbindBlueToothService
08-23 15:46:16.087  8655  8655 D HtcModeClient: Don't start project servcice
,08-23 15:46:16.087  8655  8655 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-23 15:46:16.097  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
,08-23 15:46:16.097  8655  8655 D SilentMusic: call stop
08-23 15:46:16.097  8655  8655 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-23 15:46:16.097  8655  9026 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-23 15:46:16.097  8655  8655 D HtcModeClient: onDestroy
,08-23 15:46:19.077  1108  1143 I ActivityManager: Waited long enough for: ServiceRecord{3c14df82 u0 com.google.android.gms/.wearable.service.WearableService},
,08-23 15:46:19.497  1108  3446 D PMS     : acquireWL(5e63226): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1108 1000 null
08-23 15:46:19.497  1108  3446 I BatteryService: n_update end
,08-23 15:46:19.497  1108  3446 D PMS     : releaseWL(5e63226): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-23 15:46:19.507  1108  1108 D UsbnetService: BroadcastReceiver::onReceive+
08-23 15:46:19.507  1108  1108 D UsbnetService: onReceive BATTERY_CHANGED
08-23 15:46:19.507  1108  1108 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-23 15:46:19.507  1108  1108 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-23 15:46:19.507  1108  3074 D WifiController: battery changed pluggedType: 2
08-23 15:46:19.507  1108  1108 D UsbnetService: BroadcastReceiver::onReceive-
08-23 15:46:19.507  3219  3219 D PowerUI : closing low battery warning: level=100
08-23 15:46:19.507  1108  3074 D WifiController: handleMessage: E msg.what=155652
08-23 15:46:19.507  1108  1169 D HtcPowerSaver: updateBatteryInfo
08-23 15:46:19.507  1108  3074 D WifiController: processMsg: DeviceActiveState
08-23 15:46:19.507  1108  1108 D HtcPowerSaver: Checking...
08-23 15:46:19.507  1108  3074 D WifiController: processMsg: StaEnabledState
08-23 15:46:19.507  1108  1108 I HtcPowerSaver: >> updateStatus,
08-23 15:46:19.507  1108  3074 D WifiController: processMsg: DefaultState
08-23 15:46:19.507  3219  3219 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-23 15:46:19.507  1108  3074 D WifiController: handleMessage: X
08-23 15:46:19.507  3219  3710 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-23 15:46:19.507  3361  3361 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-23 15:46:19.507  3361  3361 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-23 15:46:19.507  3361  3361 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-23 15:46:19.517  1108  1108 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-23 15:46:19.517  1108  1108 I HtcPowerSaver: << updateStatus
,08-23 15:46:19.557  3219  3219 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-23 15:46:19.557  3219  3219 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-23 15:46:19.557  3219  3219 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-23 15:46:19.557  3219  3219 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-23 15:46:19.557  3219  3219 I FlashlightController: batteryLevelChange:100
,08-23 15:46:21.107  1108  3031 I ActivityManager: Start proc 9027:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService
08-23 15:46:21.107  1108  3031 D PMS     : acquireWL(15af1e67): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10058}
08-23 15:46:21.107  1108  3031 V AlarmManager: sending alarm PendingIntent{17d8414: PendingIntentRecord{1c2784bd com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1471959978879, Int=60000
,08-23 15:46:21.117  1108  3031 V AlarmManager: sending alarm PendingIntent{1f853a03: PendingIntentRecord{24b8cd80 com.android.vending startService}}, i=null, t=0, cnt=1, w=1471959979150, Int=0,
08-23 15:46:21.117  1108  3031 V AlarmManager: sending alarm PendingIntent{224cafb9: PendingIntentRecord{5c33333 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=97519, Int=0
08-23 15:46:21.117  8655  8655 D AlarmReceiver: ACTION_RESTART_INTENT
,08-23 15:46:21.117  9027  9027 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 15:46:21.127  1108  1108 D PMS     : releaseWL(15af1e67): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-23 15:46:21.117  9027  9027 W HTCLOG  : mask=0x18
08-23 15:46:21.127  8655  8655 D LocalBluetoothProfile: getPriorityOnValue = 100
08-23 15:46:21.127  8655  8655 D LocalBluetoothProfile: getPriorityOffValue = 0
08-23 15:46:21.127  8655  8655 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-23 15:46:21.127  8655  8655 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-23 15:46:21.157  9027  9049 D SMSBackup: SMSBackupAgentService started
,08-23 15:46:21.157  9027  9049 D SMSBackup: Checking restore status
,08-23 15:46:21.167  8655  9050 D HtcModeClient: start the htcmodeservice thread,
08-23 15:46:21.167  8655  9050 D HtcModeClient: initCanAgent
,08-23 15:46:21.167  9027  9049 D SMSBackup: Restore complete
08-23 15:46:21.167  9027  9049 D SMSBackup: cancelCheckAlarm
08-23 15:46:21.177  8655  9050 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-23 15:46:21.177  9027  9049 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
08-23 15:46:21.177  8655  9050 D HtcModeClient: sense info: version = none, id = 2
08-23 15:46:21.177  8655  9050 D HtcModeClient: display info: width = 1080, height = 1776
08-23 15:46:21.177  8655  9050 D HtcModeClient: display info: mode = 10
,08-23 15:46:21.277  8655  8655 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = false
08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: Force_AWAKE = false
08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = true
08-23 15:46:21.277  8655  8655 D HtcModeClient: connectState: POWERCONNECTED_READY = true,
,08-23 15:46:21.407  8533  8533 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,08-23 15:46:22.547  8957  9010 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-23 15:46:22.547  8957  9010 I jxcore-log: 
,08-23 15:46:23.287  8655  9050 I HtcModeClient: handler message = 4011,
,08-23 15:46:23.287  8655  9050 D HtcModeClient: getConnectionCheckCount first 0
,08-23 15:46:23.287  8655  9050 D HtcModeClient: getConnectionCheckCount count = 8,
08-23 15:46:23.287  8655  9050 E HtcModeClient: Check connection and retry 9 times.,
,08-23 15:46:23.297  8655  9050 D HtcModeClient: setConnectionCheckCount count = 9
,08-23 15:46:23.297  8655  9050 D HtcModeClient: setupRestart delayedTime = 3000
,08-23 15:46:23.307  8655  8655 D HtcModeClient: setBtPriority priority = on,
08-23 15:46:23.307  8655  8655 D HtcModeClient: unbindBlueToothService,
08-23 15:46:23.307  8655  8655 D HtcModeClient: Don't start project servcice,
08-23 15:46:23.307  8655  8655 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true,
08-23 15:46:23.307  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 15:46:23.307  8655  8655 D SilentMusic: call stop
08-23 15:46:23.307  8655  8655 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode,
08-23 15:46:23.307  8655  9051 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-23 15:46:23.317  8655  8655 D HtcModeClient: onDestroy
,08-23 15:46:23.327  1108  3446 D Process : killProcessQuiet, pid=7517
08-23 15:46:23.327  1108  3446 I ActivityManager: Killing 7517:com.google.android.music:main/u0a115 (adj 15): empty #17
08-23 15:46:23.327  1108  3446 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-23 15:46:23.477  1108  3082 I ActivityManager: Recipient 7517,
08-23 15:46:23.477  1108  3630 D MediaRouterService: Client com.google.android.music (pid 7517): Died!
,08-23 15:46:24.927  8957  9010 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-23 15:46:24.927  8957  9010 I jxcore-log: 
,08-23 15:46:24.967  8957  9010 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
08-23 15:46:24.967  8957  9010 I jxcore-log: 
,08-23 15:46:24.997  8957  9010 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
08-23 15:46:24.997  8957  9010 I jxcore-log: 
,08-23 15:46:25.027  8957  9010 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 15:46:25.027  8957  9010 I jxcore-log: 
,08-23 15:46:25.037  8957  9010 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-23 15:46:25.037  8957  9010 I jxcore-log: 
,08-23 15:46:28.307  1108  3031 D PMS     : acquireWL(13a66f57): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10027},
08-23 15:46:28.307  8655  8655 D AlarmReceiver: ACTION_RESTART_INTENT
08-23 15:46:28.307  1108  3031 V AlarmManager: sending alarm PendingIntent{8141a44: PendingIntentRecord{5c33333 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=104738, Int=0
08-23 15:46:28.317  1108  1108 D PMS     : releaseWL(13a66f57): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,08-23 15:46:28.317  8655  8655 D LocalBluetoothProfile: getPriorityOnValue = 100
08-23 15:46:28.317  8655  8655 D LocalBluetoothProfile: getPriorityOffValue = 0
08-23 15:46:28.317  8655  8655 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,08-23 15:46:28.317  8655  8655 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-23 15:46:28.337  8655  9054 D HtcModeClient: start the htcmodeservice thread
08-23 15:46:28.337  8655  9054 D HtcModeClient: initCanAgent
,08-23 15:46:28.347  8655  9054 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-23 15:46:28.347  8655  9054 D HtcModeClient: sense info: version = none, id = 2
,08-23 15:46:28.347  8655  9054 D HtcModeClient: display info: width = 1080, height = 1776
08-23 15:46:28.347  8655  9054 D HtcModeClient: display info: mode = 10
,08-23 15:46:28.447  8655  8655 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = false
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: Force_AWAKE = false
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = true
08-23 15:46:28.447  8655  8655 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-23 15:46:28.917  8957  9010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-23 15:46:28.917  8957  9010 I jxcore-log: 
,08-23 15:46:28.917  8957  9010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-23 15:46:28.917  8957  9010 I jxcore-log: 
,08-23 15:46:28.927  5490  5511 D BluetoothAdapterService(1057636797): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@246d2486
,08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:46:28.937  8957  9010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 15:46:28.937  5490  5511 D BluetoothAdapterService(1057636797): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@246d2486
,08-23 15:46:28.937  8957  9010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 15:46:28.937  8957  9010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 15:46:28.937  8957  9010 I jxcore-log: 
,08-23 15:46:28.947  8957  9010 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 15:46:28.947  8957  9010 I jxcore-log: 
,08-23 15:46:29.547  7530  7575 W System.err: org.apache.http.conn.ConnectTimeoutException: Connect to /54.83.203.254:7000 timed out
08-23 15:46:29.547  7530  7575 W System.err: 	at org.apache.http.conn.scheme.PlainSocketFactory.connectSocket(PlainSocketFactory.java:138)
,08-23 15:46:29.557  7530  7575 W System.err: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:149)
08-23 15:46:29.557  7530  7575 W System.err: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:169),
08-23 15:46:29.557  7530  7575 W System.err: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:124)
08-23 15:46:29.557  7530  7575 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:377)
,08-23 15:46:29.557  7530  7575 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:759)
08-23 15:46:29.557  7530  7575 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:524),
08-23 15:46:29.557  7530  7575 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:502)
08-23 15:46:29.557  7530  7575 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connect(HttpSender.java:351)
08-23 15:46:29.557  7530  7575 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connectByGet(HttpSender.java:222)
08-23 15:46:29.557  7530  7575 W System.err: ,	at com.htc.studio.software.BDILogger.Loglib.LogLib.getLoggerPolicy(LogLib.java:190)
08-23 15:46:29.557  7530  7575 W System.err: 	at com.htc.studio.software.BDILogger.BDILoggerPolicyServiceManager.requestPolicy(BDILoggerPolicyServiceManager.java:137)
08-23 15:46:29.557  7530  7575 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl$3.run(ULoggerThreadImpl.java:201)
08-23 15:46:29.557  7530  7575 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl.run(ULoggerThreadImpl.java:92)
08-23 15:46:29.557  7530  7575 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 4,
08-23 15:46:29.557  7530  7575 D libc    : [NET] android_getaddrinfofornet-, err=8
08-23 15:46:29.557  7530  7575 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 1024
08-23 15:46:29.557  7530  7575 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-23 15:46:29.557  7530  7575 D libc    : [NET] android_getaddrinfo_proxy+
08-23 15:46:29.557  7530  7575 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-23 15:46:29.557   515  9056 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 1024,
08-23 15:46:29.557   515  9056 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
08-23 15:46:29.557   515  9056 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
08-23 15:46:29.557   515  9056 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
08-23 15:46:29.567  7530  7575 D libc    : [NET] android_getaddrinfo_proxy-, success
08-23 15:46:29.567  7530  7575 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35342e38332e32),sn(),hints(known),family 0,flags 4
08-23 15:46:29.567  7530  7575 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-23 15:46:30.457  8655  9054 I HtcModeClient: handler message = 4011
,08-23 15:46:30.457  8655  9054 D HtcModeClient: getConnectionCheckCount first 0
08-23 15:46:30.457  8655  9054 D HtcModeClient: getConnectionCheckCount count = 9
08-23 15:46:30.457  8655  9054 E HtcModeClient: Check connection and retry 10 times.
08-23 15:46:30.457  8655  9054 D HtcModeClient: setConnectionCheckCount count = 10
08-23 15:46:30.457  8655  9054 D HtcModeClient: setupRestart delayedTime = 3000
,08-23 15:46:30.457  8655  8655 D HtcModeClient: setBtPriority priority = on
08-23 15:46:30.457  8655  8655 D HtcModeClient: unbindBlueToothService
,08-23 15:46:30.457  8655  8655 D HtcModeClient: Don't start project servcice
,08-23 15:46:30.467  8655  8655 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-23 15:46:30.467  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
,08-23 15:46:30.467  8655  8655 D SilentMusic: call stop
08-23 15:46:30.467  8655  8655 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-23 15:46:30.467  8655  9055 W CANMesgAgentLocalSocket: read the terminate packet, so break,
,08-23 15:46:30.477  8655  8655 D HtcModeClient: onDestroy
,08-23 15:46:33.777  8957  9010 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
08-23 15:46:33.777  8957  9010 I jxcore-log: 
,08-23 15:46:33.917  8957  9010 I jxcore-log: ERROR runTests: ,
08-23 15:46:33.917  8957  9010 I jxcore-log: 
,08-23 15:46:33.927  8957  9010 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie',
08-23 15:46:33.927  8957  9010 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-23 15:46:33.937  8957  9010 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 15:46:33.937  8957  9010 I jxcore-log: 
08-23 15:46:33.937  8957  8957 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\nError: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\n    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 15:46:33.947  8957  8957 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
08-23 15:46:33.957  1108  3528 D Process : killProcessQuiet, pid=8402
08-23 15:46:33.957  1108  3528 I ActivityManager: Killing 8402:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-23 15:46:33.957  1108  3528 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityStack.destroyActivityLocked:3407 
,08-23 15:46:34.027  1108  3614 I ActivityManager: Recipient 8402
,08-23 15:46:34.067  8957  9004 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 120ms. Plugin should use CordovaInterface.getThreadPool().
08-23 15:46:34.067  8957  8957 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 15:46:34.067  8957  8957 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 15:46:34.067  8957  8957 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 15:46:34.067  8957  8957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 15:46:34.067  8957  8957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 15:46:34.067  8957  8957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 15:46:34.067  8957  8957 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ae3e5e removed from the list
08-23 15:46:34.067  8957  8957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 15:46:34.067  8957  8957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae94855 removed from the list
08-23 15:46:34.067  8957  8957 D io.jxcore.node.ConnectivityMonitor: stop
08-23 15:46:34.077  8957  8957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 15:46:34.077  8957  8957 I io.jxcore.node.LifeCycleMonitor: stop: OK,
,08-23 15:46:34.157  9057  9057 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
08-23 15:46:34.157  9057  9057 W HTCLOG  : mask=0x18
,08-23 15:46:34.347  9057  9062 W HTCLOG  : use specified tag [cutils-trace], func [0].,
08-23 15:46:34.347  9057  9062 W HTCLOG  : mask=0x18
08-23 15:46:34.347  9057  9062 E cutils-trace: Error opening trace file: Permission denied (13)
,08-23 15:46:34.407  9057  9057 D CustomizationManager: ====startRecUseTime====,
08-23 15:46:34.407  9057  9057 D htc.customization.log.level:  is 
08-23 15:46:34.407  9057  9057 W CustomizationLogLevel: Level value is invalid, use default level 2
,08-23 15:46:34.487  9057  9057 D CustomizationManager:  Read ACC file spent 0.039 (s),
,08-23 15:46:34.487  9057  9057 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
08-23 15:46:34.487  9057  9057 I CustomizationCIDLoader: Parsing tag category name = application
08-23 15:46:34.487  9057  9057 I CustomizationCIDLoader: Parsing tag category name = system
,08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: Parsing tag category name = Settings
08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: Parsing tag category name = ACC
,08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-23 15:46:34.497  9057  9057 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-23 15:46:34.497  9057  9057 D CustomizationManager:  Read CID file spent 0.089 (s)
08-23 15:46:34.497  9057  9057 D CustomizationManager:  All configurations done spent 0.089 (s)
,08-23 15:46:34.547  1108  3528 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=9057, uid=2000
,08-23 15:46:34.557  1108  1143 D Process : killProcessQuiet, pid=8957
08-23 15:46:34.557  1108  1143 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
08-23 15:46:34.557  1108  1143 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
08-23 15:46:34.557  1108  1143 I ActivityManager: Killing 8957:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
,08-23 15:46:34.647   529   529 W HTCLOG  : use specified tag [Vector], func [0].,
08-23 15:46:34.647   529   529 W HTCLOG  : mask=0x18
,08-23 15:46:34.717  1108  3614 I ActivityManager: Recipient 8957,
08-23 15:46:34.727  1108  3074 D WifiService: Client connection lost with reason: 4
,08-23 15:46:34.777  1108  3614 W ActivityManager: Spurious death for ProcessRecord{2851fee5 8957:com.test.thalitest/u0a142}, curProc for 8957: null,
,08-23 15:46:34.787  1108  1180 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed,
,08-23 15:46:34.867  3361  3361 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
08-23 15:46:34.877  1108  4135 D PMS     : acquireWL(7bd646b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4412 10019 null
08-23 15:46:34.867  3361  3361 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
08-23 15:46:34.877  1108  3151 D TaskPersister: removeObsoleteFile: deleting file=451_task.xml
08-23 15:46:34.877  4412  4540 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 15:46:34.877  1108  3446 D PMS     : releaseWL(7bd646b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
08-23 15:46:34.887  3744  4162 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
08-23 15:46:34.887  1108  3071 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
08-23 15:46:34.887  1108  3065 W SystemReader: Cannot find grip_rejection_width, use default value instead
08-23 15:46:34.887  1108  3070 D PMS     : acquireWL(15fe8bc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1108 1000 null
08-23 15:46:34.887  3744  4162 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
08-23 15:46:34.897  3744  4162 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
08-23 15:46:34.907  3744  4162 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
08-23 15:46:34.907  3571  3571 I art     : Explicit concurrent mark sweep GC freed 3049(140KB) AllocSpace objects, 4(254KB) LOS objects, 40% free, 20MB/33MB, paused 979us total 45.345ms
,08-23 15:46:34.917  1108  3070 D PMS     : releaseWL(15fe8bc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
08-23 15:46:34.917  1108  3071 V NetworkPolicy: writePolicyLocked()
,08-23 15:46:34.917  3549  3549 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
08-23 15:46:34.917  4046  4046 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 15:46:34.927  6037  6037 I art     : Explicit concurrent mark sweep GC freed 17121(1095KB) AllocSpace objects, 2(48KB) LOS objects, 34% free, 3MB/5MB, paused 449us total 118.039ms
,08-23 15:46:34.927  3645  3645 I ConfigService: onCreate,
,08-23 15:46:34.927  1108  3640 D PMS     : acquireWL(234bdc47): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4046 10019 null,
,08-23 15:46:34.937  3645  3645 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE,
08-23 15:46:34.937  3744  4162 E ExternalAccountType: Unsupported attribute readOnly,
,08-23 15:46:34.937  3838  9075 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest,
08-23 15:46:34.947  4046  4046 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
08-23 15:46:34.957  1108  3071 V NetworkPolicy: updateNetworkEnabledLocked()
08-23 15:46:34.947  3645  3645 I ConfigService: onBind returning update interface
08-23 15:46:34.957  1108  3071 V NetworkPolicy: updateNotificationsLocked()
08-23 15:46:34.957  1108  3071 D NetworkPolicy: notifyPoliciesChangeLocked: no change
08-23 15:46:34.957  3645  3645 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 15:46:34.957  3645  3645 I ConfigService: onBind returning config service
,08-23 15:46:34.967  3645  3645 I ConfigService: onDestroy
08-23 15:46:34.967  1108  3446 D PMS     : acquireWL(3273060c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3645 10019 null
08-23 15:46:34.977  1108  3541 I ActivityManager: Start proc 9077:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
,08-23 15:46:34.977  1108  4135 D PMS     : releaseWL(3273060c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-23 15:46:34.987  1108  3031 D PMS     : acquireWL(3ea43e5b): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10027}
,08-23 15:46:34.987  1108  3031 V AlarmManager: sending alarm PendingIntent{c5076f8: PendingIntentRecord{5c33333 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=111894, Int=0
,08-23 15:46:34.987  1108  3031 V AlarmManager: sending alarm PendingIntent{9bb9a8e: PendingIntentRecord{25cc42af android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=113423, Int=0
,08-23 15:46:34.997  9077  9077 W HTCLOG  : use specified tag [FDManager], func [0].
,08-23 15:46:34.997  9077  9077 W HTCLOG  : mask=0x18
,08-23 15:46:35.027  1108  1108 I art     : Explicit concurrent mark sweep GC freed 33542(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 16MB/24MB, paused 5.094ms total 166.150ms,
08-23 15:46:35.027  1108  1180 I art     : WaitForGcToComplete blocked for 141.815ms for cause Explicit
,08-23 15:46:35.037  1108  1142 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
08-23 15:46:35.037  9077  9077 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 15:46:35.037  9077  9077 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 15:46:35.067  9077  9077 I MultiDex: VM with version 2.1.0 has multidex support,
,08-23 15:46:35.067  9077  9077 I MultiDex: install
08-23 15:46:35.067  9077  9077 I MultiDex: VM has multidex support, MultiDex support library is disabled.,
08-23 15:46:35.077  3571  3571 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,08-23 15:46:35.077  3571  3571 I ThreadedRenderer: Defer allocateBuffers to drawing time
,08-23 15:46:35.087  9077  9077 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
,08-23 15:46:35.097  1108  1142 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-23 15:46:35.097  9077  9077 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest,
,08-23 15:46:35.127  3494  3494 D Nfc-Utils: isNxpCodebase: isNxp=false
,08-23 15:46:35.127  4046  9101 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
08-23 15:46:35.127  4046  9101 D AccountUtils: Clearing selected account for com.test.thalitest
,08-23 15:46:35.137  1108  1130 I ActivityManager: Start proc 9103:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
,08-23 15:46:35.147  9103  9103 W HTCLOG  : use specified tag [FDManager], func [0].,
08-23 15:46:35.147  9103  9103 W HTCLOG  : mask=0x18
,08-23 15:46:35.167  1108  1108 W PackageManager: Unable to load service info ResolveInfo{39095e46 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
08-23 15:46:35.167  1108  1108 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509),
08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
,08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:46:35.167  1108  1108 W PackageManager: ,	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.167  1108  1108 W PackageManager: ,	at com.android.server.SystemServer.run(SystemServer.java:331)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372),
08-23 15:46:35.167  1108  1108 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 15:46:35.167  1108  1108 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-23 15:46:35.187  8468  9128 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id),
,08-23 15:46:35.207  4046  9129 I PeopleContactsSync: CP2 sync disabled
,08-23 15:46:35.207  1108  3529 D PMS     : acquireWL(3e94c983): PARTIAL_WAKE_LOCK  Icing 0x1 4046 10019 null
,08-23 15:46:35.207  1108  3529 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4046, uid=10019, userID:0
08-23 15:46:35.207  4046  5639 I Icing   : doRemovePackageData com.test.thalitest
,08-23 15:46:35.207  1108  3784 D PMS     : releaseWL(3e94c983): PARTIAL_WAKE_LOCK  Icing 0x1 null
,08-23 15:46:35.217  4046  9127 W GmsApplication: Using Auth Proxy for data requests.,
,08-23 15:46:35.227  1108  3528 D Process : killProcessQuiet, pid=8186
08-23 15:46:35.227  1108  3528 I ActivityManager: Killing 8186:com.google.android.gm/u0a97 (adj 15): empty #17
,08-23 15:46:35.227  1108  3528 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 ,
,08-23 15:46:35.227  1108  1180 I art     : Explicit concurrent mark sweep GC freed 8572(469KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.128ms total 199.264ms,
,08-23 15:46:35.287  9057  9057 I art     : System.exit called, status: 0
,08-23 15:46:35.287  1108  3640 I ActivityManager: Recipient 8186
,08-23 15:46:35.337  1108  1108 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 15:46:35.337  3744  3744 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,08-23 15:46:35.347  3668  9135 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
,08-23 15:46:35.347  4046  9127 W GmsApplication: Using Auth Proxy for data requests.,
,08-23 15:46:35.367  3668  9135 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,08-23 15:46:35.367  3571  3571 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
08-23 15:46:35.367  3571  3571 I ContextualWidget: package com.test.thalitest removed
08-23 15:46:35.367  3571  4170 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
08-23 15:46:35.367  3571  3985 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
08-23 15:46:35.367  3571  3985 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,08-23 15:46:35.377  3571  3571 I Launcher: Deferring update until onResume
08-23 15:46:35.377  3571  3571 D Launcher: waitUntilResume // bindAppsRemoved
,08-23 15:46:35.387  3571  9136 I ContextualWidget: com.test.thalitest is not installed
08-23 15:46:35.387  3571  9136 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
08-23 15:46:35.387  1108  1130 I ActivityManager: Start proc 9138:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
08-23 15:46:35.397  4046  9137 I art     : WaitForGcToComplete blocked for 10.316ms for cause Explicit
08-23 15:46:35.397  4046  4063 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-23 15:46:35.397  4046  4063 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-23 15:46:35.397  4046  4063 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-23 15:46:35.407  9138  9138 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 15:46:35.407  9138  9138 W HTCLOG  : mask=0x18
,08-23 15:46:35.447  4046  9122 W DriveInitializer: Awaiting to be initialized
,08-23 15:46:35.447  4046  9160 W DriveInitializer: Background init thread started
,08-23 15:46:35.447  4046  9137 I art     : Explicit concurrent mark sweep GC freed 3885(179KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 2.772ms total 58.169ms
,08-23 15:46:35.457  3571  4170 I ContextualWidget: MFU.onDownloadDataSetChanged,
08-23 15:46:35.457  3571  4170 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
08-23 15:46:35.457  3571  3571 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId fe7a0bc5-b5a1-4d18-9471-4486194d412f, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
08-23 15:46:35.457  3571  3571 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId fe7a0bc5-b5a1-4d18-9471-4486194d412f, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,08-23 15:46:35.487  9138  9138 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
08-23 15:46:35.487  1108  3528 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
,08-23 15:46:35.487  9138  9138 D IdefixUninstallListener: package_removed = com.test.thalitest
,08-23 15:46:35.507  4046  9160 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files,
08-23 15:46:35.507  1108  4135 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.google.android.gms/files/
,08-23 15:46:35.517  9138  9138 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
08-23 15:46:35.517  9138  9138 W HTCLOG  : mask=0x18
,08-23 15:46:35.527  1108  3082 D Process : killProcessQuiet, pid=8262
08-23 15:46:35.527  1108  3082 I ActivityManager: Killing 8262:com.google.android.talk/u0a103 (adj 15): empty #17
08-23 15:46:35.527  1108  3082 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-23 15:46:35.627  1108  3529 I ActivityManager: Recipient 8262
,08-23 15:46:35.647  6037  9165 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,08-23 15:46:35.657  4046  9160 W DriveInitializer: Background init thread ended
08-23 15:46:35.657  4046  9122 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 15:46:35.657  4046  9122 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 15:46:35.657  4046  9122 W HTCLOG  : mask=0x18
08-23 15:46:35.657  4046  9122 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5566e2dec0
08-23 15:46:35.657  4046  9122 E DriveAsyncService: disk I/O error (code 3850)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406),
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.657  4046  9122 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.667  1108  3630 I ActivityManager: Start proc 9170:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-23 15:46:35.687  6037  9165 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
08-23 15:46:35.687  6037  9165 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 15:46:35.687  6037  9165 W HTCLOG  : mask=0x18
08-23 15:46:35.687  6037  9165 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x5566b9bf00
08-23 15:46:35.687  9170  9170 W HTCLOG  : use specified tag [FDManager], func [0].
,08-23 15:46:35.687  9170  9170 W HTCLOG  : mask=0x18
,08-23 15:46:35.697  6037  9165 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-23 15:46:35.697  6037  9165 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 15:46:35.697  6037  9165 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6037
08-23 15:46:35.697  6037  9165 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.697  6037  9165 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.697  1108  3640 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
,08-23 15:46:35.707  6037  9165 D Process : killProcess, pid=6037
08-23 15:46:35.707  6037  9165 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: Can't write: system_app_crash
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.707  1108  9193 E DropBoxManagerService: 	... 5 more
08-23 15:46:35.707  6037  9165 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:35.707  6037  9165 W HTCLOG  : mask=0x18
08-23 15:46:35.727  9170  9170 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
,08-23 15:46:35.737  1108  3528 D PMS     : acquireWL(eea4d53): PARTIAL_WAKE_LOCK  AsyncService 0x1 8621 10128 null
08-23 15:46:35.737  1108  1129 D PMS     : releaseWL(eea4d53): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-23 15:46:35.747  9170  9194 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 15:46:35.747  9170  9194 W HTCLOG  : mask=0x18
08-23 15:46:35.747  8868  8868 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.747  9170  9194 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-23 15:46:35.747  9170  9194 E AndroidRuntime: Process: com.android.keychain, PID: 9170
08-23 15:46:35.747  9170  9194 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.747  9170  91,94 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.747  9170  9194 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.747  8868  8868 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
08-23 15:46:35.747  1108  3784 E ActivityManager: App crashed! Process: com.android.keychain
08-23 15:46:35.747  8868  8868 I DeviceManagement: WorkflowService: Starting workflow service
08-23 15:46:35.757  8868  9196 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@1851f2ac] args=[Bundle[mParcelledData.dataSize=112]]
08-23 15:46:35.757  8868  9196 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-23 15:46:35.757  8868  9196 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-23 15:46:35.757  8868  9196 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-23 15:46:35.767  1108  3630 I ActivityManager: Start proc 9197:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
08-23 15:46:35.767  1108  3784 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 15:46:35.767  9197  9197 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 15:46:35.767  9197  9197 W HTCLOG  : mask=0x18
08-23 15:46:35.767  1108  3784 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.767  1108  3529 I ActivityManager: Recipient 6037
08-23 15:46:35.767  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.767  1108  3074 D WifiService: Client connection lost with reason: 4
08-23 15:46:35.767  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.767  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.767  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.767  1108  3784 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.767  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.767  1108  3784 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.767  1108  3784 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.767  1108  3784 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.767  1108  3784 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.767  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.767  1108  3784 W System.err: 	... 14 more
08-23 15:46:35.777  1108  3784 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.777  8868  9196 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
08-23 15:46:35.777  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.777  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.777  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.777  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.777  1108  3784 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.777  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.777  1108  3784 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.777  1108  3784 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.777  1108  3784 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.777  1108  3784 W System.err: 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.777  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.777  1108  3784 W System.err: 	... 14 more
08-23 15:46:35.797  8868  9196 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
08-23 15:46:35.797  1108  3529 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6037) has died
08-23 15:46:35.797  1108  3529 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
08-23 15:46:35.797  1108  3529 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
08-23 15:46:35.797  3571  3923 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
08-23 15:46:35.807  1108  9219 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 15:46:35.807  1108  9219 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471959995817.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 15:46:35.807  1108  9219 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.807  1108  9219 E ErrorReport: 	... 4 more
08-23 15:46:35.807  9170  9194 D Process : killProcess, pid=9170
08-23 15:46:35.807  9170  9194 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 15:46:35.807  1108  3659 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.807  9170  9194 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:35.807  9170  9194 W HTCLOG  : mask=0x18
08-23 15:46:35.807  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.807  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.807  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.807  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.807  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 15:46:35.807  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 15:46:35.807  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 15:46:35.807  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 15:46:35.807  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 15:46:35.807  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 15:46:35.807  1108  3659 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.807  1108  3659 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.807  1108  3659 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.807  1108  3659 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.807  1108  3659 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.807  1108  3659 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.807  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.807  1108  3659 W System.err: 	... 12 more
08-23 15:46:35.807  8868  9218 I DeviceManagement: SessionStateController: Checking invariants...
,08-23 15:46:35.847  9197  9197 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
08-23 15:46:35.847  9197  9197 W HTCLOG  : mask=0x18
,08-23 15:46:35.847  9197  9197 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 15:46:35.847  9197  9197 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: FATAL EXCEPTION: main
08-23 15:46:35.847  9197  9197 E AndroidRuntime: Process: com.android.documentsui, PID: 9197
08-23 15:46:35.847  9197  9197 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.datab,ase.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 15:46:35.847  9197  9197 E AndroidRuntime: 	... 9 more
08-23 15:46:35.857  1108  4135 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 15:46:35.857  1108  4135 E ActivityManager: App crashed! Process: com.android.documentsui
08-23 15:46:35.857  1108  3446 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 15:46:35.857  1108  4135 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  9221 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 15:46:35.857  1108  9221 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471959995874.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 15:46:35.857  1108  9221 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.857  1108  9221 E ErrorReport: 	... 4 more
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.867  1108  9222 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 15:46:35.867  1108  9222 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471959995879.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(Htc,ErrorReportManager.java:458)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 15:46:35.867  1108  9222 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.867  1108  9222 E ErrorReport: 	... 4 more
08-23 15:46:35.857  1108  4135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.877  1108  1143 I ActivityManager: Start proc 9223:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-23 15:46:35.857  1108  4135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.857  1108  4135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.857  1108  4135 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.857  1108  4135 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.857  1108  4135 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.857  1108  4135 W System.err: 	... 14 more
08-23 15:46:35.857  1108  4135 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  5558  5763 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.857  1108  4135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.857  1108  4135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.857  1108  4135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProp,erty(ErrorReportPreference.java:109)
08-23 15:46:35.857  5558  5763 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 15:46:35.857  5558  5763 W HTCLOG  : mask=0x18
08-23 15:46:35.857  1108  4135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 15:46:35.857  5558  5763 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x5566b9a320
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.857  1108  4135 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.857  1108  4135 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.857  1108  4135 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.857  1108  4135 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.857  1108  4135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.857  1108  4135 W System.err: 	... 14 more
08-23 15:46:35.857  5558  5763 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-23 15:46:35.857  5558  5763 E AndroidRuntime: Process: android.process.media, PID: 5558
08-23 15:46:35.857  5558  5763 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.857  5558  5763 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.857  1108  3446 E ActivityManager: App crashed! Process: android.process.media
08-23 15:46:35.857  1108  3446 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  3446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.857  1108  3446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.857  1108  3446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.857  1108  3446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.857  1108  3446 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.857  1108  3446 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.857  1108  3446 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  3446 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.897  1108  1130 I ActivityManager: Recipient 9170
08-23 15:46:35.857  1108  3446 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.897  1108  1130 I ActivityManager: Process com.android.keychain (pid 9170) has died
08-23 15:46:35.857  1108  3446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.897  1108  1130 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10901ms
08-23 15:46:35.857  1108  3446 W System.err: 	... 14 more
08-23 15:46:35.857  1108  3446 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.857  1108  3446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.857  1108  3446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.857  1108  3446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.857  1108  3446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:35.857  1108  3446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 15:46:35.867  1108  3446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 15:46:35.867  1108  3446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.867  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.867  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.867  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.867  1108  3446 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.867  1108  3446 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.867  1108  3446 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.867  1108  3446 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.867  1108  3659 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.867  1108  3446 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.867  1108  3659 W System.err: 	at 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.867  1108  3446 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.867  1108  3446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.867  1108  3446 W System.err: 	... 14 more
08-23 15:46:35.867  9197  9197 D Process : killProcess, pid=9197
08-23 15:46:35.867  9197  9197 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 15:46:35.867  9197  9197 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:35.867  9197  9197 W HTCLOG  : mask=0x18
08-23 15:46:35.867  1108  3659 W System.err: java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.867  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.867  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.867  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 15:46:35.867  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 15:46:35.877  5558  5763 D Process : killProcess, pid=5558
08-23 15:46:35.877  5558  5763 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 15:46:35.877  5558  5763 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:35.877  5558  5763 W HTCLOG  : mask=0x18
08-23 15:46:35.877  9223  9223 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 15:46:35.877  9223  9223 W HTCLOG  : mask=0x18
08-23 15:46:35.897   491   491 E lowmemorykiller: Error writing /proc/5558/oom_score_adj; errno=22
08-23 15:46:35.897  1108  3541 W HTCLOG  : use specified tag [JavaBinder], func [0].
08-23 15:46:35.897  1108  3541 W HTCLOG  : mask=0x18
08-23 15:46:35.897  1108  3541 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 15:46:35.897  1108  3659 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.897  1108  3659 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.897  1108  3659 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.897  1108  3659 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.897  1108  3659 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.897  1108  3659 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.897  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.897  1108  3659 W System.err: 	... 12 more
08-23 15:46:35.897  1108  3659 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.897  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.897  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.897  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.897  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 15:46:35.897  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 15:46:35.897  1108  3659 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.897  1108  3659 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.897  1108  3659 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.897  1108  3659 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.897  1108  3659 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.897  1108  3659 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.897  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.897  1108  3659 W System.err: 	... 12 more
08-23 15:46:35.907   557   557 I art     : Explicit concurrent mark sweep GC freed 8635(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 121us total 30.940ms
08-23 15:46:35.917  1108  3082 I ActivityManager: Recipient 9197
08-23 15:46:35.917  1108  3082 I ActivityManager: Process com.android.documentsui (pid 9197) has died
08-23 15:46:35.917   557   557 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 115us total 16.546ms
08-23 15:46:35.927  9223  9223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
08-23 15:46:35.927  9223  9245 D PowerUtils: getUserIdOfProcess, curUserId = 0
08-23 15:46:35.927  9223  9245 D PowerUtils: isRunningUnderOwner, isOwner = true
08-23 15:46:35.937  8868  9218 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 15:46:35.937  8868  9218 W HTCLOG  : mask=0x18
,08-23 15:46:35.937  8868  9218 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-23 15:46:35.937  8868  9218 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-23 15:46:35.937   557   557 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 114us total 16.893ms
08-23 15:46:35.947  1108  3529 I ActivityManager: Recipient 5558
08-23 15:46:35.947  1108  3536 I ActivityManager: Start proc 9246:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
08-23 15:46:35.947  8868  9218 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.947  8868  9196 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.947  1108  3529 I ActivityManager: Process android.process.media (pid 5558) has died
08-23 15:46:35.947  8868  9196 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
08-23 15:46:35.947  1108  3529 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 10847ms
08-23 15:46:35.947  9223  9245 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
08-23 15:46:35.957  3361  3386 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
08-23 15:46:35.957  9246  9246 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 15:46:35.957  9246  9246 W HTCLOG  : mask=0x18
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.957  8868  9196 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.957  8868  9196 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@1851f2ac]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.957  8868  9196 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.957  3219  3219 I NotificationStackScrollLayout: setBlockTouchEnabled:false
08-23 15:46:35.967  8868  8868 I DeviceManagement: WorkflowService: Stopping workflow service
08-23 15:46:35.977  9223  9245 D PowerUsageService: removed uid = 10142
08-23 15:46:35.977  9223  9245 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 15:46:35.977  9223  9245 W HTCLOG  : mask=0x18
,08-23 15:46:35.977  9223  9245 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.977  9223  9245 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
08-23 15:46:35.977  9223  9245 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 9223
08-23 15:46:35.977  9223  9245 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.977  9223  9245 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.977  1108  1129 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 15:46:35.977  1108  1129 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
08-23 15:46:35.977  1108  1129 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.977  1108  1129 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.977  1108  1129 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.977  1108  1129 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.977  1108  1129 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.987  1108  9268 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 15:46:35.987  1108  9268 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471959996002.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 15:46:35.987  1108  9268 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.987  1108  9268 E ErrorReport: 	... 4 more
08-23 15:46:35.977  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.977  1108  1129 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.977  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.977  1108  1129 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.977  1108  1129 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.987  1108  1129 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.987  1108  1129 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.987  1108  1129 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.987  1108  1129 W System.err: 	... 14 more
08-23 15:46:35.987  1108  1129 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.987  1108  1129 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.987  1108  1129 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.987  1108  1129 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.987  1108  1129 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:35.987  1108  1129 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:35.987  1108  1129 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:35.987  1108  1129 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:35.987  1108  1129 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.987  1108  1129 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.987  1108  1129 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.987  1108  1129 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.987  1108  1129 W System.err: 	... 14 more
08-23 15:46:35.987  9223  9245 D Process : killProcess, pid=9223
08-23 15:46:35.987  1108  3659 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 15:46:35.987  9223  9245 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 15:46:35.987  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:35.987  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:35.987  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:35.987  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:35.987  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 15:46:35.987  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 15:46:35.987  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 15:46:35.987  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 15:46:35.987  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 15:46:35.987  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 15:46:35.987  1108  3659 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:35.987  1108  3659 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:35.987  1108  3659 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:35.987  1108  3659 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:35.987  9223  9245 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:35.987  9223  9245 W HTCLOG  : mask=0x18
08-23 15:46:35.987  1108  3659 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:35.987  1108  3659 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:35.987  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:35.987  1108  3659 W System.err: 	... 12 more
08-23 15:46:36.017  9246  9269 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 15:46:36.017  9246  9269 W HTCLOG  : mask=0x18
,08-23 15:46:36.017  9246  9269 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:36.017  9246  9269 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-23 15:46:36.017  9246  9269 E AndroidRuntime: Process: com.htc.updater, PID: 9246
08-23 15:46:36.017  9246  9269 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.017  9246  9269 E AndroidRu,ntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:36.017  9246  9269 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:36.017  1108  3784 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 15:46:36.017  1108  3784 E ActivityManager: App crashed! Process: com.htc.updater
08-23 15:46:36.017  1108  3784 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:36.017  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:36.017  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:36.017  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:36.017  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:36.017  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:36.017  1108  3784 W System.err: ,	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 15:46:36.017  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 15:46:36.027  1108  9272 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 15:46:36.027  1108  9272 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471959996042.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 15:46:36.027  1108  9272 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:36.027  1108  9272 E ErrorReport: 	... 4 more
08-23 15:46:36.017  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 15:46:36.017  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:36.017  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:36.037  1108  1108 D PMS     : releaseWL(3ea43e5b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-23 15:46:36.017  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:36.017  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:36.017  1108  3784 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:36.017  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:36.017  1108  3784 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:36.017  1108  3784 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:36.017  1108  3784 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:36.017  1108  3784 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:36.017  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:36.017  1108  3784 W System.err: 	... 14 more
08-23 15:46:36.027  1108  3784 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 15:46:36.027  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:36.027  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:36.027  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:36.027  1108  3784 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReport,Preference.java:109)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 15:46:36.027  1108  3784 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 15:46:36.027  1108  3784 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 15:46:36.027  1108  3784 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 15:46:36.027  1108  3784 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:36.027  9246  9246 V UpdaterAPK | DownloadService: Service onStart
08-23 15:46:36.027  1108  3784 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:36.027  1108  3784 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:36.027  1108  3784 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:36.027  1108  3784 W System.err: 	... 14 more
08-23 15:46:36.027  9246  9270 V UpdaterAPK | DownloadService: Updating for startId 1
08-23 15:46:36.027  1108  3659 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 15:46:36.027  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:36.027  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:36.027  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 15:46:36.027  1108  3659 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 15:46:36.027  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 15:46:36.027  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 15:46:36.027  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 15:46:36.027  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 15:46:36.027  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 15:46:36.027  1108  3659 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 15:46:36.027  1108  3659 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:36.027  1108  3659 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,08-23 15:46:36.027  1108  3659 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:46:36.027  1108  3659 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:36.027  1108  3659 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:36.027  1108  3659 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:36.027  1108  3659 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:36.027  1108  3659 W System.err: 	... 12 more
08-23 15:46:36.027  9246  9269 D Process : killProcess, pid=9246
08-23 15:46:36.027  8655  8655 D AlarmReceiver: ACTION_RESTART_INTENT
08-23 15:46:36.027  9246  9269 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,08-23 15:46:36.027  9246  9270 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:98)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:36.027  9246  9270 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: Couldn't open downloads.db for writing (will try read-only):
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelp,er: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:98)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:36.027  9246  9270 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 15:46:36.047  1108  3630 I ActivityManager: Recipient 9223
08-23 15:46:36.027  9246  9269 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:36.047  1108  3630 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 9223) has died
08-23 15:46:36.027  9246  9269 W HTCLOG  : mask=0x18
08-23 15:46:36.047  1108  3630 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 20754ms
08-23 15:46:36.027  8655  8655 D LocalBluetoothProfile: getPriorityOnValue = 100
08-23 15:46:36.027  8655  8655 D LocalBluetoothProfile: getPriorityOffValue = 0
08-23 15:46:36.027  8655  8655 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,08-23 15:46:36.027  8655  8655 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-23 15:46:36.037  3645  3645 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-23 15:46:36.037  3645  3645 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-23 15:46:36.037  3645  3645 D c       : Getting all permits...
08-23 15:46:36.037  3645  3645 D a       : Opening database...
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/auth.proximity.permit_store'.
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854),
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:52)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.b.c.a(SourceFile:185)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.authorization.bt.b.a(SourceFile:217)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter.onReceive(SourceFile:239)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
,08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 15:46:36.037  3645  3645 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: FATAL EXCEPTION: main
08-23 15:46:36.047  3645  3645 E AndroidRuntime: Process: com.google.process.gapps, PID: 3645
08-23 15:46:36.047  3645  3645 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
,08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:52)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.b.c.a(SourceFile:185)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.authorization.bt.b.a(SourceFile:217)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter.onReceive(SourceFile:239)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 15:46:36.047  3645  3645 E AndroidRuntime: 	... 9 more
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: Can't write: system_app_crash
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:36.047  1108  9274 E DropBoxManagerService: 	... 5 more
08-23 15:46:36.047  1108  3528 E ActivityManager: App crashed! Process: com.google.process.gapps
08-23 15:46:36.047  3645  3645 D Process : killProcess, pid=3645
08-23 15:46:36.057  3645  3645 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,08-23 15:46:36.057  4046  4046 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-23 15:46:36.057  3645  3645 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:36.057  3645  3645 W HTCLOG  : mask=0x18
,08-23 15:46:36.057  8655  9275 D HtcModeClient: start the htcmodeservice thread
08-23 15:46:36.057  8655  9275 D HtcModeClient: initCanAgent
08-23 15:46:36.057  8655  9275 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-23 15:46:36.067  8655  9275 D HtcModeClient: sense info: version = none, id = 2
,08-23 15:46:36.067  8655  9275 D HtcModeClient: display info: width = 1080, height = 1776
08-23 15:46:36.067  8655  9275 D HtcModeClient: display info: mode = 10
,08-23 15:46:36.077  4046  9278 D LocationInitializer: Restart initialization of location
,08-23 15:46:36.117  1108  1129 I ActivityManager: Recipient 9246
08-23 15:46:36.117  1108  1129 I ActivityManager: Process com.htc.updater (pid 9246) has died
,08-23 15:46:36.117   491   491 E lowmemorykiller: Error writing /proc/3645/oom_score_adj; errno=22
08-23 15:46:36.117  1108  1129 W ActivityManager: Scheduling restart of crashed service com.htc.updater/.download.DownloadService in 30683ms
08-23 15:46:36.117  4046  4046 I GoogleURLConnFactory: binding HttpService
08-23 15:46:36.117  1108  3446 I ActivityManager: Recipient 3645
,08-23 15:46:36.117  1108  3446 I ActivityManager: Process com.google.process.gapps (pid 3645) has died
08-23 15:46:36.117  1108  3446 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 40679ms
08-23 15:46:36.117  1108  3446 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 50679ms
,08-23 15:46:36.137  1108  3640 I ActivityManager: Start proc 9279:com.google.process.gapps/u0a19 for service com.google.android.gms/.gcm.http.GoogleHttpService,
,08-23 15:46:36.137  9279  9279 W HTCLOG  : use specified tag [FDManager], func [0].,
08-23 15:46:36.137  9279  9279 W HTCLOG  : mask=0x18
,08-23 15:46:36.167  8655  8655 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-23 15:46:36.167  9279  9279 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 15:46:36.167  9279  9279 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
,08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = false
08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: Force_AWAKE = false
08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: PHONE_PULGIN = true
08-23 15:46:36.167  8655  8655 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-23 15:46:36.167  8655  8681 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak,
08-23 15:46:36.167  8655  8681 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,08-23 15:46:36.177  9279  9279 I MultiDex: VM with version 2.1.0 has multidex support,
08-23 15:46:36.177  9279  9279 I MultiDex: install
08-23 15:46:36.177  9279  9279 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 15:46:36.197  9279  9279 I GservicesProvider: Gservices pushing to system: true; secure/global: true,
08-23 15:46:36.197  9279  9279 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 15:46:36.197  9279  9279 W HTCLOG  : mask=0x18,
,08-23 15:46:36.197  9279  9279 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.,
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 15:46:36.197  9279  9279 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: FATAL EXCEPTION: main
08-23 15:46:36.197  9279  9279 E AndroidRuntime: Process: com.google.process.gapps, PID: 9279
08-23 15:46:36.197  9279  9279 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:,5725)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 15:46:36.197  9279  9279 E AndroidRuntime: 	... 11 more
08-23 15:46:36.197  1108  3536 E ActivityManager: App crashed! Process: com.google.process.gapps
,08-23 15:46:36.207  9279  9279 D Process : killProcess, pid=9279
,08-23 15:46:36.207  1108  9300 E DropBoxManagerService: Can't write: system_app_crash
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 15:46:36.207  1108  9300 E DropBoxManagerService: 	... 5 more
,08-23 15:46:36.207  9279  9279 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-23 15:46:36.207  9279  9279 W HTCLOG  : use specified tag [Process], func [0].
08-23 15:46:36.207  9279  9279 W HTCLOG  : mask=0x18
,08-23 15:46:36.287  1108  3529 I ActivityManager: Recipient 9279
08-23 15:46:36.287  1108  3529 I ActivityManager: Process com.google.process.gapps (pid 9279) has died
08-23 15:46:36.287  1108  3529 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{262c4002 u0 com.google.android.gms/.gcm.GcmService}
08-23 15:46:36.287  1108  3529 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{148b6526 u0 com.google.android.gms/.gcm.http.GoogleHttpService}
,08-23 15:46:36.637  3549  3742 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,08-23 15:46:36.637  3549  3742 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,08-23 15:46:36.707  1108  4135 D PMS     : releaseWL(1b4f4fa9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null

```
