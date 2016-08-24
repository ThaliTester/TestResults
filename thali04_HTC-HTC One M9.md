#### Test 79763830e108614_thali04_HTC-HTC One M9 Logs


```
--------- beginning of system
08-24 13:26:39.457  1114  3031 D PMS     : acquireWL(119814f9): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{10027}
08-24 13:26:39.457  1114  3031 V AlarmManager: sending alarm PendingIntent{5bafc3e: PendingIntentRecord{329447ea com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=82623, Int=0
08-24 13:26:39.457  1114  3031 V AlarmManager: sending alarm PendingIntent{3f6c7a9f: PendingIntentRecord{486d7ec android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=82176, Int=0
--------- beginning of main
08-24 13:26:39.667  3563  3974 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-24 13:26:39.667  3563  3974 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@233d3293 +
08-24 13:26:39.667  3563  3974 I Prism.WidgetManager: onLoadItems() +
08-24 13:26:39.687  9022  9040 W art     : Suspending all threads took: 5.677ms
08-24 13:26:39.697  4299  6863 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-24 13:26:39.767  4299  6863 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-24 13:26:39.777  4299  9051 I art     : Explicit concurrent mark sweep GC freed 17844(1107KB) AllocSpace objects, 4(80KB) LOS objects, 32% free, 4MB/6MB, paused 738us total 54.788ms
08-24 13:26:39.827  3541  4176 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-24 13:26:39.827  3541  4176 D PhoneApp: -- N1 =0
08-24 13:26:39.827  3541  4176 D PhoneApp: -- N2 =0
08-24 13:26:39.827  3541  4176 D PhoneApp: -- N3 =0
08-24 13:26:39.857  4299  6863 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-24 13:26:39.867  1114  3540 D PMS     : releaseWL(34fb9254): PARTIAL_WAKE_LOCK  Icing 0x1 null
,08-24 13:26:39.937  3563  3974 E Prism.WidgetManager: The same lists. No need to update. skip it.
08-24 13:26:39.937  3563  3974 I Prism.WidgetManager: onLoadItems() -
08-24 13:26:39.937  3563  3974 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@233d3293 -
08-24 13:26:40.107  9053  9053 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-24 13:26:40.107  9053  9053 W HTCLOG  : mask=0x18
08-24 13:26:40.157  9022  9057 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-24 13:26:40.157  9022  9057 W HTCLOG  : mask=0x18
08-24 13:26:40.227  9022  9022 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-24 13:26:40.227  1114  3084 D PMS     : acquireWL(152786d): PARTIAL_WAKE_LOCK  AsyncService 0x1 8122 10128 null
08-24 13:26:40.237  1114  3540 D PMS     : releaseWL(152786d): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-24 13:26:40.267  9053  9069 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-24 13:26:40.267  9053  9069 W HTCLOG  : mask=0x18
08-24 13:26:40.267  9053  9069 E cutils-trace: Error opening trace file: Permission denied (13)
08-24 13:26:40.267  8781  8781 D AlarmReceiver: ACTION_RESTART_INTENT
08-24 13:26:40.277  1114  1114 D PMS     : releaseWL(119814f9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-24 13:26:40.277  8781  8781 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 13:26:40.277  8781  8781 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 13:26:40.277  8781  8781 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 13:26:40.277  8781  8781 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-24 13:26:40.297  8781  9081 D HtcModeClient: start the htcmodeservice thread
08-24 13:26:40.297  8781  9081 D HtcModeClient: initCanAgent
08-24 13:26:40.297  8781  9081 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-24 13:26:40.297  8781  9081 D HtcModeClient: sense info: version = none, id = 2
08-24 13:26:40.297  8781  9081 D HtcModeClient: display info: width = 1080, height = 1776
08-24 13:26:40.297  8781  9081 D HtcModeClient: display info: mode = 10
08-24 13:26:40.337  9053  9053 D CustomizationManager: ====startRecUseTime====
08-24 13:26:40.337  9053  9053 D htc.customization.log.level:  is 
08-24 13:26:40.337  9053  9053 W CustomizationLogLevel: Level value is invalid, use default level 2
08-24 13:26:40.397  8781  8781 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: Force_AWAKE = false
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 13:26:40.397  8781  8781 D HtcModeClient: connectState: POWERCONNECTED_READY = true
08-24 13:26:40.417  9053  9053 D CustomizationManager:  Read ACC file spent 0.036 (s)
08-24 13:26:40.417  9053  9053 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-24 13:26:40.417  9053  9053 I CustomizationCIDLoader: Parsing tag category name = application
08-24 13:26:40.417  9053  9053 I CustomizationCIDLoader: Parsing tag category name = system
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: Parsing tag category name = Settings
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: Parsing tag category name = ACC
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-24 13:26:40.427  9053  9053 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-24 13:26:40.427  9053  9053 D CustomizationManager:  Read CID file spent 0.087 (s)
08-24 13:26:40.427  9053  9053 D CustomizationManager:  All configurations done spent 0.087 (s)
08-24 13:26:40.467  1114  5674 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 9053 on display 0
08-24 13:26:40.477  1114  1179 D PMS     : acquireHCC(130b2dfa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1114 1000 null
08-24 13:26:40.477  1114  1179 D PMS     : acquireHCC(d20efab): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1114 1000 null
08-24 13:26:40.477  1114  5674 V WindowManager: addAppToken: AppWindowToken{25ce2fc6 token=Token{6c141a1 ActivityRecord{294e5608 u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-24 13:26:40.497  1114  5674 I ActivityManager: Start proc 9086:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-24 13:26:40.497  9053  9053 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-24 13:26:40.497  9053  9053 W HTCLOG  : mask=0x18
08-24 13:26:40.497  9053  9084 W HTCLOG  : use specified tag [Vector], func [0].
08-24 13:26:40.497  9053  9084 W HTCLOG  : mask=0x18
08-24 13:26:40.497  9086  9086 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 13:26:40.497  9086  9086 W HTCLOG  : mask=0x18
08-24 13:26:40.517  3342  3342 D DotMatrix: [EventService]  onDisplayChanged: 0
08-24 13:26:40.517  1114  1114 V ActivityManager: Display changed displayId=0
08-24 13:26:40.517  3342  3342 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-24 13:26:40.517  1114  8589 D ActivityManager: screenshot for ActivityRecord{294e5608 u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-24 13:26:40.547  3563  3563 I TrimMemoryManager: [trimMemory] 20
08-24 13:26:40.557  3541  3716 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-24 13:26:40.557  3541  3716 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
08-24 13:26:40.567  9086  9086 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-24 13:26:40.627  9086  9086 I LibraryLoader: Time to load native libraries: 27 ms (timestamps 5766-5793)
08-24 13:26:40.627  9086  9086 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:26:40.637  9086  9086 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e7393dd}
08-24 13:26:40.637  9086  9086 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:26:40.637  9086  9086 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 13:26:40.647  9086  9086 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 13:26:40.647  9086  9086 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:26:40.647  9086  9086 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 13:26:40.687  5533  5576 D BluetoothAdapterService(511021191): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11adf968
08-24 13:26:40.697  9086  9086 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-24 13:26:40.697  9086  9086 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
08-24 13:26:40.697  9086  9086 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
08-24 13:26:40.697  9086  9086 W HTCLOG  : use specified tag [libEGL], func [3].
08-24 13:26:40.697  9086  9086 W HTCLOG  : mask=0x18
08-24 13:26:40.707  9086  9086 W HTCLOG  : use specified tag [libEGL], func [3].
08-24 13:26:40.707  9086  9086 W HTCLOG  : mask=0x18
08-24 13:26:40.707  9086  9086 I Adreno  : QUALCOMM build                   : 065751b, 
08-24 13:26:40.707  9086  9086 I Adreno  : Build Date                       : 04/15/15
08-24 13:26:40.707  9086  9086 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-24 13:26:40.707  9086  9086 I Adreno  : Local Branch                     : 
08-24 13:26:40.707  9086  9086 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-24 13:26:40.707  9086  9086 I Adreno  : Remote Branch                    : NONE
08-24 13:26:40.707  9086  9086 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,08-24 13:26:40.777  9086  9119 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,08-24 13:26:40.787  9086  9086 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 13:26:40.797  9086  9086 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 13:26:40.807  9086  9086 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,08-24 13:26:40.807  9086  9086 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:26:40.807  9086  9086 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 13:26:40.837  9086  9130 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,08-24 13:26:40.837  9086  9130 W HTCLOG  : mask=0x18
,08-24 13:26:40.837  1114  8589 V WindowManager: Adding window Window{1130bb6f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{88002e5 u0 com.htc.launcher/com.htc.launcher.Launcher})
,08-24 13:26:40.847  1114  3624 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-24 13:26:40.877  9086  9086 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-24 13:26:40.877  9086  9086 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-24 13:26:40.877  9086  9086 W HTCLOG  : mask=0x18
08-24 13:26:40.877  9086  9086 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 13:26:40.877  9086  9086 W HTCLOG  : mask=0x18
,08-24 13:26:40.887  9086  9130 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 13:26:40.887  9086  9130 W HTCLOG  : mask=0x18
08-24 13:26:40.887  9086  9130 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 13:26:40.887  9086  9130 W HTCLOG  : mask=0x18
,08-24 13:26:40.887  9086  9130 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 13:26:40.887  9086  9130 W HTCLOG  : mask=0x18
,08-24 13:26:40.887  9086  9130 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 13:26:40.887  9086  9130 W HTCLOG  : mask=0x18
,08-24 13:26:40.887  9086  9130 W HTCLOG  : use specified tag [Surface], func [3].
08-24 13:26:40.887  9086  9130 W HTCLOG  : mask=0x18
08-24 13:26:40.897  9086  9130 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-24 13:26:40.897  9086  9130 W HTCLOG  : mask=0x18
08-24 13:26:40.897  9086  9130 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-24 13:26:40.897  9086  9130 W HTCLOG  : mask=0x18
,08-24 13:26:40.937  1114  1170 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +417ms (total +455ms)
,08-24 13:26:40.967  9086  9086 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9086
,08-24 13:26:41.027  9086  9086 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 13:26:41.077  9086  9133 D jxcore_app_log: JniHelper::setJavaVM(0xab354b70), pthread_self() = -1406184672
,08-24 13:26:41.077  9086  9133 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 13:26:41.077  9086  9133 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 13:26:41.077  9086  9133 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 13:26:41.077  9086  9133 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 13:26:41.077  9086  9133 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 13:26:41.077  9086  9133 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7948d80 added. We now have 1 listener(s)
,08-24 13:26:41.087  1114  8591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-24 13:26:41.087  9086  9133 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-24 13:26:41.087  9086  9133 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-24 13:26:41.087  9086  9133 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 13:26:41.087  9086  9133 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 13:26:41.087  9086  9133 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3276335f added. We now have 1 listener(s)
08-24 13:26:41.087  9086  9133 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 13:26:41.087  1114  3076 D WifiService: New client listening to asynchronous messages
,08-24 13:26:41.097  9086  9133 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 13:26:41.097  9086  9133 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 13:26:41.097  9086  9133 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 13:26:41.097  9086  9133 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 13:26:41.097  9086  9133 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 13:26:41.097  9086  9133 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 13:26:41.097  1114  3385 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-24 13:26:41.097  9086  9133 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
,08-24 13:26:41.097  5533  5576 D BluetoothAdapterService(511021191): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11adf968,
08-24 13:26:41.097  9086  9133 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:26:41.097  9086  9133 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 13:26:41.097  9086  9133 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 13:26:41.097  9086  9133 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 13:26:41.097  9086  9133 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 13:26:41.107  9086  9086 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:26:41.107  9086  9086 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:26:41.147  9086  9086 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 13:26:41.467  1114  1179 D PMS     : releaseHCC(130b2dfa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,08-24 13:26:41.467  1114  1179 D PMS     : releaseHCC(d20efab): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-24 13:26:41.487  9086  9139 W jxcore-log: Initializing JXcore engine
08-24 13:26:41.487  9086  9139 W jxcore-log: JXcore engine is ready
,08-24 13:26:41.537  9086  9139 W jxcore-log: Starting JXcore engine,
,08-24 13:26:41.647  9086  9139 W jxcore-log: Platform android
08-24 13:26:41.647  9086  9139 W jxcore-log: 
08-24 13:26:41.647  9086  9139 W jxcore-log: Process ARCH arm
08-24 13:26:41.647  9086  9139 W jxcore-log: 
,08-24 13:26:41.827  9086  9139 I jxcore-log: JXcore Cordova bridge is ready!
08-24 13:26:41.827  9086  9139 I jxcore-log: 
08-24 13:26:41.827  9086  9139 W jxcore-log: JXcore engine is started
,08-24 13:26:41.837  9086  9133 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 13:26:41.837  9086  9086 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 13:26:42.277   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-24 13:26:42.407  8781  9081 I HtcModeClient: handler message = 4011
08-24 13:26:42.407  8781  9081 D HtcModeClient: getConnectionCheckCount first 0,
08-24 13:26:42.407  8781  9081 D HtcModeClient: getConnectionCheckCount count = 6
08-24 13:26:42.407  8781  9081 E HtcModeClient: Check connection and retry 7 times.
08-24 13:26:42.417  8781  9081 D HtcModeClient: setConnectionCheckCount count = 7
,08-24 13:26:42.417  8781  9081 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 13:26:42.417  8781  8781 D HtcModeClient: setBtPriority priority = on
,08-24 13:26:42.427  8781  8781 D HtcModeClient: unbindBlueToothService
08-24 13:26:42.427  8781  8781 D HtcModeClient: Don't start project servcice
08-24 13:26:42.427  8781  8781 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 13:26:42.427  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
,08-24 13:26:42.427  8781  8781 D SilentMusic: call stop
,08-24 13:26:42.427  8781  8781 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-24 13:26:42.427  8781  9083 W CANMesgAgentLocalSocket: read the terminate packet, so break
08-24 13:26:42.427  8781  8781 D HtcModeClient: onDestroy
,08-24 13:26:44.187  9022  9022 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-24 13:26:44.187  1114  3562 I ActivityManager: Killing 8513:com.google.android.setupwizard/u0a59 (adj 15): empty #17
,08-24 13:26:44.187  1114  3562 D Process : killProcessQuiet, pid=8513
08-24 13:26:44.187  1114  3562 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 13:26:44.347  1114  8589 I ActivityManager: Recipient 8513,
,08-24 13:26:45.137  9022  9056 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-24 13:26:46.587  1114  1114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,08-24 13:26:47.417  1114  3031 D PMS     : acquireWL(d44ec80): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{10027},
08-24 13:26:47.417  1114  3031 V AlarmManager: sending alarm PendingIntent{1167e2b9: PendingIntentRecord{329447ea com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=90586, Int=0
08-24 13:26:47.427  8781  8781 D AlarmReceiver: ACTION_RESTART_INTENT
,08-24 13:26:47.437  8781  8781 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 13:26:47.437  1114  1114 D PMS     : releaseWL(d44ec80): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-24 13:26:47.437  8781  8781 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 13:26:47.437  8781  8781 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 13:26:47.437  8781  8781 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 13:26:47.457  8781  9147 D HtcModeClient: start the htcmodeservice thread
,08-24 13:26:47.457  8781  9147 D HtcModeClient: initCanAgent
,08-24 13:26:47.457  8781  9147 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 13:26:47.467  8781  9147 D HtcModeClient: sense info: version = none, id = 2,
08-24 13:26:47.467  8781  9147 D HtcModeClient: display info: width = 1080, height = 1776
,08-24 13:26:47.467  8781  9147 D HtcModeClient: display info: mode = 10
,08-24 13:26:47.557  1114  3501 D PMS     : releaseWL(330b1db5): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,08-24 13:26:47.567  8781  8781 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: Force_AWAKE = false
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 13:26:47.567  8781  8781 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 13:26:49.577  8781  9147 I HtcModeClient: handler message = 4011
,08-24 13:26:49.577  8781  9147 D HtcModeClient: getConnectionCheckCount first 0
,08-24 13:26:49.577  8781  9147 D HtcModeClient: getConnectionCheckCount count = 7
,08-24 13:26:49.577  8781  9147 E HtcModeClient: Check connection and retry 8 times.
,08-24 13:26:49.577  8781  9147 D HtcModeClient: setConnectionCheckCount count = 8,
08-24 13:26:49.577  8781  9147 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 13:26:49.587  8781  8781 D HtcModeClient: setBtPriority priority = on
08-24 13:26:49.587  8781  8781 D HtcModeClient: unbindBlueToothService,
08-24 13:26:49.587  8781  8781 D HtcModeClient: Don't start project servcice
08-24 13:26:49.587  8781  8781 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 13:26:49.587  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false,
08-24 13:26:49.587  8781  8781 D SilentMusic: call stop,
,08-24 13:26:49.587  8781  8781 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode,
08-24 13:26:49.587  8781  9148 W CANMesgAgentLocalSocket: read the terminate packet, so break
08-24 13:26:49.587  8781  8781 D HtcModeClient: onDestroy
,08-24 13:26:52.967  1114  1160 I ActivityManager: Waited long enough for: ServiceRecord{2c0030a9 u0 com.google.android.gms/.wearable.service.WearableService},
,08-24 13:26:53.887  1114  3540 D PMS     : acquireWL(279407d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:26:53.887  1114  3540 I BatteryService: n_update end
08-24 13:26:53.897  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:26:53.887  1114  3540 D PMS     : releaseWL(279407d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:26:53.897  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:26:53.897  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:26:53.897  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:26:53.897  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:26:53.897  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:26:53.897  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:26:53.897  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:26:53.897  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:26:53.897  1114  1114 D HtcPowerSaver: Checking...
08-24 13:26:53.897  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:26:53.897  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:26:53.897  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:26:53.897  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:26:53.897  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:26:53.897  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:26:53.897  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:26:53.897  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:26:53.897  1114  3076 D WifiController: handleMessage: X
,08-24 13:26:53.907  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,08-24 13:26:53.907  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:26:53.907  1114  1114 I HtcPowerSaver: << updateStatus
,08-24 13:26:53.947  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:26:53.947  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:26:53.947  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false),
08-24 13:26:53.947  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:26:53.947  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:26:54.277  9086  9139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 13:26:54.277  9086  9139 I jxcore-log: 
,08-24 13:26:54.287  9086  9139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-24 13:26:54.287  9086  9139 I jxcore-log: 
,08-24 13:26:54.297  5533  5578 D BluetoothAdapterService(511021191): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11adf968
,08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:26:54.297  9086  9139 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 13:26:54.297  5533  5576 D BluetoothAdapterService(511021191): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11adf968
08-24 13:26:54.307  9086  9139 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-24 13:26:54.307  9086  9139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 13:26:54.307  9086  9139 I jxcore-log: 
,08-24 13:26:54.307  9086  9139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 13:26:54.307  9086  9139 I jxcore-log: 
,08-24 13:26:54.597  1114  3031 I ActivityManager: Start proc 9149:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService
,08-24 13:26:54.597  1114  3031 D PMS     : acquireWL(19eeba57): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{10058}
,08-24 13:26:54.597  1114  3031 V AlarmManager: sending alarm PendingIntent{3db60944: PendingIntentRecord{2becda2d com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472038012280, Int=60000,
,08-24 13:26:54.597  1114  3031 V AlarmManager: sending alarm PendingIntent{3dbaa4f3: PendingIntentRecord{2dac75b0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1472038012998, Int=0
,08-24 13:26:54.597  1114  3031 V AlarmManager: sending alarm PendingIntent{3469ec29: PendingIntentRecord{329447ea com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=97748, Int=0
08-24 13:26:54.607  8781  8781 D AlarmReceiver: ACTION_RESTART_INTENT
08-24 13:26:54.607  8781  8781 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 13:26:54.607  1114  1114 D PMS     : releaseWL(19eeba57): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-24 13:26:54.607  8781  8781 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 13:26:54.607  8781  8781 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 13:26:54.607  8781  8781 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 13:26:54.617  9149  9149 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 13:26:54.617  9149  9149 W HTCLOG  : mask=0x18
,08-24 13:26:54.657  9149  9172 D SMSBackup: SMSBackupAgentService started
08-24 13:26:54.657  9149  9172 D SMSBackup: Checking restore status
,08-24 13:26:54.657  8781  9173 D HtcModeClient: start the htcmodeservice thread
,08-24 13:26:54.657  8781  9173 D HtcModeClient: initCanAgent
,08-24 13:26:54.657  9149  9172 D SMSBackup: Restore complete,
08-24 13:26:54.657  9149  9172 D SMSBackup: cancelCheckAlarm
08-24 13:26:54.657  8781  9173 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 13:26:54.667  9149  9172 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds,
08-24 13:26:54.667  8781  9173 D HtcModeClient: sense info: version = none, id = 2
,08-24 13:26:54.667  8781  9173 D HtcModeClient: display info: width = 1080, height = 1776
08-24 13:26:54.667  8781  9173 D HtcModeClient: display info: mode = 10
,08-24 13:26:54.757  8781  8781 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
,08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: Force_AWAKE = false
08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 13:26:54.757  8781  8781 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 13:26:54.897  8683  8683 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,08-24 13:26:55.057  9086  9139 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-24 13:26:55.057  9086  9139 I jxcore-log: Failed to execute UT.
08-24 13:26:55.057  9086  9139 I jxcore-log: 
,08-24 13:26:55.057  9086  9139 I jxcore-log: Unit Test app is loaded,
08-24 13:26:55.057  9086  9139 I jxcore-log: 
,08-24 13:26:55.067  9086  9139 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-24 13:26:55.067  9086  9139 I jxcore-log: 
08-24 13:26:55.077  9086  9086 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 13:26:55.077  9086  9139 I jxcore-log: My device name is: HTC-HTC One M9
08-24 13:26:55.077  9086  9139 I jxcore-log: 
,08-24 13:26:55.077  9086  9139 I jxcore-log: WARN testUtils: myNameCallback not set!,
08-24 13:26:55.077  9086  9139 I jxcore-log: 
,08-24 13:26:56.767  8781  9173 I HtcModeClient: handler message = 4011
,08-24 13:26:56.767  8781  9173 D HtcModeClient: getConnectionCheckCount first 0
08-24 13:26:56.767  8781  9173 D HtcModeClient: getConnectionCheckCount count = 8
08-24 13:26:56.777  8781  9173 E HtcModeClient: Check connection and retry 9 times.
08-24 13:26:56.777  8781  9173 D HtcModeClient: setConnectionCheckCount count = 9
,08-24 13:26:56.777  8781  9173 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 13:26:56.787  8781  8781 D HtcModeClient: setBtPriority priority = on,
08-24 13:26:56.787  8781  8781 D HtcModeClient: unbindBlueToothService
08-24 13:26:56.787  8781  8781 D HtcModeClient: Don't start project servcice
,08-24 13:26:56.787  8781  8781 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 13:26:56.787  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 13:26:56.787  8781  8781 D SilentMusic: call stop
,08-24 13:26:56.787  8781  8781 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-24 13:26:56.787  8781  9174 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-24 13:26:56.797  8781  8781 D HtcModeClient: onDestroy,
08-24 13:26:56.797  1114  5674 I ActivityManager: Killing 8602:com.google.android.apps.maps/u0a114 (adj 15): empty #17
08-24 13:26:56.797  1114  5674 D Process : killProcessQuiet, pid=8602
08-24 13:26:56.797  1114  5674 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 13:26:56.947  1114  3490 I ActivityManager: Recipient 8602
,08-24 13:27:00.387  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 13:27:00.387  9086  9139 I jxcore-log: 
,08-24 13:27:01.517  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 13:27:01.517  9086  9139 I jxcore-log: 
,08-24 13:27:01.557  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 13:27:01.557  9086  9139 I jxcore-log: 
,08-24 13:27:01.567  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 13:27:01.567  9086  9139 I jxcore-log: 
,08-24 13:27:01.597  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 13:27:01.597  9086  9139 I jxcore-log: 
,08-24 13:27:01.597  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 13:27:01.597  9086  9139 I jxcore-log: 
,08-24 13:27:01.777  1114  3031 D PMS     : acquireWL(2dbce747): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1114 1000 WorkSource{1000}
,08-24 13:27:01.787  1114  3031 V AlarmManager: sending alarm PendingIntent{3d192745: PendingIntentRecord{120aee9a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=105154, Int=0
08-24 13:27:01.787  1114  3031 V AlarmManager: sending alarm PendingIntent{2fd04b74: PendingIntentRecord{329447ea com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=104947, Int=0
08-24 13:27:01.787  8781  8781 D AlarmReceiver: ACTION_RESTART_INTENT
,08-24 13:27:01.797  8781  8781 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 13:27:01.797  8781  8781 D LocalBluetoothProfile: getPriorityOffValue = 0,
08-24 13:27:01.797  8781  8781 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 13:27:01.797  8781  8781 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 13:27:01.827  1114  1114 D PMS     : releaseWL(2dbce747): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-24 13:27:01.827  8781  9177 D HtcModeClient: start the htcmodeservice thread
,08-24 13:27:01.827  8781  9177 D HtcModeClient: initCanAgent
,08-24 13:27:01.827  8781  9177 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 13:27:01.827  8781  9177 D HtcModeClient: sense info: version = none, id = 2,
,08-24 13:27:01.837  8781  9177 D HtcModeClient: display info: width = 1080, height = 1776
08-24 13:27:01.837  8781  9177 D HtcModeClient: display info: mode = 10
,08-24 13:27:01.927  8781  8781 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: Force_AWAKE = false
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 13:27:01.927  8781  8781 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 13:27:03.887  7559  7614 W System.err: org.apache.http.conn.ConnectTimeoutException: Connect to /54.83.203.254:7000 timed out
,08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.conn.scheme.PlainSocketFactory.connectSocket(PlainSocketFactory.java:138)
,08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:149)
08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:169)
08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:124)
08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:377)
08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:759)
08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:524)
08-24 13:27:03.887  7559  7614 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:502)
,08-24 13:27:03.887  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connect(HttpSender.java:351)
08-24 13:27:03.887  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connectByGet(HttpSender.java:222)
08-24 13:27:03.887  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.LogLib.getLoggerPolicy(LogLib.java:190)
08-24 13:27:03.887  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.BDILoggerPolicyServiceManager.requestPolicy(BDILoggerPolicyServiceManager.java:137)
08-24 13:27:03.887  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl$3.run(ULoggerThreadImpl.java:201)
08-24 13:27:03.887  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl.run(ULoggerThreadImpl.java:92)
,08-24 13:27:03.887  7559  7614 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 4
,08-24 13:27:03.887  7559  7614 D libc    : [NET] android_getaddrinfofornet-, err=8
,08-24 13:27:03.897  7559  7614 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 1024
08-24 13:27:03.897  7559  7614 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-24 13:27:03.897  7559  7614 D libc    : [NET] android_getaddrinfo_proxy+
,08-24 13:27:03.897  7559  7614 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,08-24 13:27:03.897   519  9179 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 1024
,08-24 13:27:03.897   519  9179 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,08-24 13:27:03.897   519  9179 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
08-24 13:27:03.897   519  9179 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-24 13:27:03.897  7559  7614 D libc    : [NET] android_getaddrinfo_proxy-, success
08-24 13:27:03.897  7559  7614 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35342e38332e32),sn(),hints(known),family 0,flags 4
,08-24 13:27:03.907  7559  7614 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-24 13:27:03.937  8781  9177 I HtcModeClient: handler message = 4011
,08-24 13:27:03.947  8781  9177 D HtcModeClient: getConnectionCheckCount first 0
08-24 13:27:03.947  8781  9177 D HtcModeClient: getConnectionCheckCount count = 9
,08-24 13:27:03.947  8781  9177 E HtcModeClient: Check connection and retry 10 times.
,08-24 13:27:03.947  8781  9177 D HtcModeClient: setConnectionCheckCount count = 10
,08-24 13:27:03.947  8781  9177 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 13:27:03.947  8781  8781 D HtcModeClient: setBtPriority priority = on
08-24 13:27:03.947  8781  8781 D HtcModeClient: unbindBlueToothService
08-24 13:27:03.947  8781  8781 D HtcModeClient: Don't start project servcice
,08-24 13:27:03.947  8781  8781 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-24 13:27:03.947  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
,08-24 13:27:03.947  8781  8781 D SilentMusic: call stop
08-24 13:27:03.947  8781  8781 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-24 13:27:03.947  8781  9178 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-24 13:27:03.957  8781  8781 D HtcModeClient: onDestroy
,08-24 13:27:05.677  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
08-24 13:27:05.677  9086  9139 I jxcore-log: 
,08-24 13:27:05.697  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,08-24 13:27:05.697  9086  9139 I jxcore-log: 
,08-24 13:27:05.707  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
,08-24 13:27:05.707  9086  9139 I jxcore-log: 
,08-24 13:27:05.907  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 13:27:05.907  9086  9139 I jxcore-log: 
,08-24 13:27:06.927  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
08-24 13:27:06.927  9086  9139 I jxcore-log: 
,08-24 13:27:07.297  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
08-24 13:27:07.297  9086  9139 I jxcore-log: 
,08-24 13:27:07.307  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 13:27:07.307  9086  9139 I jxcore-log: 
,08-24 13:27:07.567  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
08-24 13:27:07.567  9086  9139 I jxcore-log: 
,08-24 13:27:07.597  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 13:27:07.597  9086  9139 I jxcore-log: 
,08-24 13:27:07.607  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 13:27:07.607  9086  9139 I jxcore-log: 
,08-24 13:27:07.617  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 13:27:07.617  9086  9139 I jxcore-log: 
,08-24 13:27:07.637  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 13:27:07.637  9086  9139 I jxcore-log: 
,08-24 13:27:07.667  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 13:27:07.667  9086  9139 I jxcore-log: 
,08-24 13:27:07.767  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 13:27:07.767  9086  9139 I jxcore-log: 
,08-24 13:27:07.777  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 13:27:07.777  9086  9139 I jxcore-log: 
,08-24 13:27:07.807  9086  9139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,08-24 13:27:07.807  9086  9139 I jxcore-log: 
,08-24 13:27:07.827  5533  5578 D BluetoothAdapterService(511021191): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11adf968
,08-24 13:27:07.827  9086  9139 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-24 13:27:07.827  9086  9139 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 13:27:07.827  9086  9139 I jxcore-log: 
,08-24 13:27:08.947  1114  3031 D PMS     : acquireWL(ca24e55): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{10027}
08-24 13:27:08.947  1114  3031 V AlarmManager: sending alarm PendingIntent{3fb7706a: PendingIntentRecord{329447ea com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=112113, Int=0
,08-24 13:27:08.967  8781  8781 D AlarmReceiver: ACTION_RESTART_INTENT
,08-24 13:27:08.977  1114  1114 D PMS     : releaseWL(ca24e55): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-24 13:27:08.977  8781  8781 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 13:27:08.987  8781  8781 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 13:27:08.987  8781  8781 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 13:27:08.987  8781  8781 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 13:27:09.017  8781  9181 D HtcModeClient: start the htcmodeservice thread
,08-24 13:27:09.017  8781  9181 D HtcModeClient: initCanAgent
08-24 13:27:09.017  8781  9181 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 13:27:09.017  8781  9181 D HtcModeClient: sense info: version = none, id = 2
,08-24 13:27:09.017  8781  9181 D HtcModeClient: display info: width = 1080, height = 1776
,08-24 13:27:09.017  8781  9181 D HtcModeClient: display info: mode = 10
,08-24 13:27:09.117  8781  8781 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: Force_AWAKE = false
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 13:27:09.117  8781  8781 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 13:27:10.587  3541  3716 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,08-24 13:27:10.607  3541  3716 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,08-24 13:27:11.127  8781  9181 I HtcModeClient: handler message = 4011,
,08-24 13:27:11.137  8781  9181 D HtcModeClient: getConnectionCheckCount first 0,
,08-24 13:27:11.137  8781  9181 D HtcModeClient: getConnectionCheckCount count = 10,
,08-24 13:27:11.137  8781  9181 E HtcModeClient: Check connection and retry 11 times.,
,08-24 13:27:11.147  8781  9181 D HtcModeClient: setConnectionCheckCount count = 11,
08-24 13:27:11.147  8781  9181 D HtcModeClient: setupRestart delayedTime = 3000,
,08-24 13:27:11.167  8781  8781 D HtcModeClient: setBtPriority priority = on,
08-24 13:27:11.167  8781  8781 D HtcModeClient: unbindBlueToothService
,08-24 13:27:11.167  8781  8781 D HtcModeClient: Don't start project servcice
,08-24 13:27:11.177  8781  8781 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true,
,08-24 13:27:11.177  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false,
08-24 13:27:11.177  8781  8781 D SilentMusic: call stop,
08-24 13:27:11.177  8781  8781 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode,
,08-24 13:27:11.177  8781  9182 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-24 13:27:11.187  8781  8781 D HtcModeClient: onDestroy,
,08-24 13:27:16.167  1114  3031 D PMS     : acquireWL(28c598d3): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{1000},
08-24 13:27:16.167  1114  3031 V AlarmManager: sending alarm PendingIntent{16e48c10: PendingIntentRecord{65cb309 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472038033044, Int=0
08-24 13:27:16.177  1114  3031 V AlarmManager: sending alarm PendingIntent{35fb290e: PendingIntentRecord{329447ea com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=119329, Int=0
08-24 13:27:16.177  1114  1114 D PMS     : acquireWL(1146ef2f): PARTIAL_WAKE_LOCK  *backup* 0x1 1114 1000 null
08-24 13:27:16.187  8781  8781 D AlarmReceiver: ACTION_RESTART_INTENT
08-24 13:27:16.187  1114  3145 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
08-24 13:27:16.187  1114  3145 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
08-24 13:27:16.187  1114  3145 D PMS     : releaseWL(1146ef2f): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,08-24 13:27:16.197  1114  1114 D PMS     : releaseWL(28c598d3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027},
08-24 13:27:16.207  8781  8781 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 13:27:16.207  8781  8781 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 13:27:16.207  8781  8781 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 13:27:16.207  8781  8781 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 13:27:16.237  8781  9184 D HtcModeClient: start the htcmodeservice thread,
08-24 13:27:16.237  8781  9184 D HtcModeClient: initCanAgent
,08-24 13:27:16.237  8781  9184 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 13:27:16.237  8781  9184 D HtcModeClient: sense info: version = none, id = 2,
,08-24 13:27:16.237  8781  9184 D HtcModeClient: display info: width = 1080, height = 1776
08-24 13:27:16.247  8781  9184 D HtcModeClient: display info: mode = 10,
,08-24 13:27:16.337  8781  8781 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-24 13:27:16.347  8781  8781 D HtcModeClient: connectState: BT_TURNON_BYME = false
,08-24 13:27:16.347  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false,
,08-24 13:27:16.347  8781  8781 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false,
,08-24 13:27:16.357  8781  8781 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
,08-24 13:27:16.357  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = false,
,08-24 13:27:16.367  8781  8781 D HtcModeClient: connectState: Force_AWAKE = false
,08-24 13:27:16.367  8781  8781 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 13:27:16.367  8781  8781 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 13:27:17.277   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 13:27:18.377  8781  9184 I HtcModeClient: handler message = 4011,
,08-24 13:27:18.387  8781  9184 D HtcModeClient: getConnectionCheckCount first 0,
,08-24 13:27:18.387  8781  9184 D HtcModeClient: getConnectionCheckCount count = 11,
,08-24 13:27:18.387  8781  9184 E HtcModeClient: Check connection and retry 12 times. Time out!,
,08-24 13:27:18.397  8781  9184 D HtcModeClient: setConnectionCheckCount count = 0
,08-24 13:27:18.397  8781  9184 D HtcModeClient: cancelRestart
,08-24 13:27:18.407  8781  8781 D HtcModeClient: setBtPriority priority = on,
08-24 13:27:18.407  8781  8781 D HtcModeClient: unbindBlueToothService
08-24 13:27:18.407  8781  8781 D HtcModeClient: Don't start project servcice
08-24 13:27:18.407  8781  8781 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 13:27:18.417  8781  8781 D HtcModeClient: connectState: CONNECTION_READY = false,
,08-24 13:27:18.417  8781  8781 D SilentMusic: call stop
,08-24 13:27:18.417  8781  8781 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-24 13:27:18.417  8781  9185 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-24 13:27:18.427  8781  8781 D HtcModeClient: onDestroy,
,08-24 13:27:27.287   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 13:27:33.907  7559  7614 W System.err: org.apache.http.conn.ConnectTimeoutException: Connect to /54.83.203.254:7000 timed out,
08-24 13:27:33.907  7559  7614 W System.err: ,	at org.apache.http.conn.scheme.PlainSocketFactory.connectSocket(PlainSocketFactory.java:138)
08-24 13:27:33.917  7559  7614 W System.err: ,	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:149)
08-24 13:27:33.917  7559  7614 W System.err: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:169),
08-24 13:27:33.917  7559  7614 W System.err: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:124),
08-24 13:27:33.917  7559  7614 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:377)
,08-24 13:27:33.917  7559  7614 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:759)
,08-24 13:27:33.917  7559  7614 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:524)
08-24 13:27:33.917  7559  7614 W System.err: ,	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:502)
08-24 13:27:33.917  7559  7614 W System.err: 	,at com.htc.studio.software.BDILogger.Loglib.HttpSender.connect(HttpSender.java:351)
08-24 13:27:33.917  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connectByGet(HttpSender.java:222)
,08-24 13:27:33.917  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.LogLib.getLoggerPolicy(LogLib.java:190)
,08-24 13:27:33.917  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.BDILoggerPolicyServiceManager.requestPolicy(BDILoggerPolicyServiceManager.java:137)
08-24 13:27:33.917  7559  7614 W System.err: ,	at com.htc.studio.software.BDILogger.ULoggerThreadImpl$3.run(ULoggerThreadImpl.java:201)
08-24 13:27:33.917  7559  7614 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl.run(ULoggerThreadImpl.java:92)
,08-24 13:27:37.407  1114  1159 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA,
,08-24 13:27:37.407  1114  1159 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,08-24 13:27:37.417  1114  1159 D PMS     : acquireWL(cde93d4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 1114 1000 null,
,08-24 13:27:37.427  1114  4830 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
08-24 13:27:37.437  1114  4830 D libc    : [NET] android_getaddrinfofornet-, err=8
,08-24 13:27:37.437  1114  4830 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
08-24 13:27:37.437  1114  4830 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-24 13:27:37.437  1114  4830 D libc    : [NET] android_getaddrinfo_proxy+
08-24 13:27:37.437  1114  4830 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-24 13:27:37.437   519  9186 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
08-24 13:27:37.437   519  9186 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,08-24 13:27:37.837  1114  8589 D PMS     : releaseWL(ede39d3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,08-24 13:27:38.037   519  9186 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
08-24 13:27:38.037   519  9186 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
08-24 13:27:38.037  1114  4830 D libc    : [NET] android_getaddrinfo_proxy-, success
08-24 13:27:38.047  1114  4830 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35322e38342e31),sn(),hints(known),family 0,flags 4
08-24 13:27:38.047  1114  4830 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-24 13:27:38.387  1114  4830 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data,
,08-24 13:27:38.647  1114  3478 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0,
08-24 13:27:38.657  1114  3478 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0
08-24 13:27:38.657  1114  4830 D PMS     : acquireWL(23765cc3): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 1114 1000 null
,08-24 13:27:38.657  1114  4830 D GpsLocationProvider:  [handleDownloadXtraData]inject done.
08-24 13:27:38.657  1114  4830 D PMS     : releaseWL(cde93d4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null,
08-24 13:27:38.667  1114  1159 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,08-24 13:27:38.667  1114  1159 D PMS     : releaseWL(23765cc3): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,08-24 13:27:41.147  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:27:41.147  1114  3562 D PMS     : acquireWL(2b7b1940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:27:41.147  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:27:41.147  1114  3562 I BatteryService: n_update end
08-24 13:27:41.147  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:27:41.147  1114  3562 D PMS     : releaseWL(2b7b1940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:27:41.147  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:27:41.147  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:27:41.147  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:27:41.147  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:27:41.147  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:27:41.157  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:27:41.147  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:27:41.157  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:27:41.147  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:27:41.157  1114  1114 D HtcPowerSaver: Checking...
08-24 13:27:41.147  1114  3076 D WifiController: handleMessage: X
08-24 13:27:41.157  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:27:41.147  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:27:41.157  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:27:41.147  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:27:41.147  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:27:41.147  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-24 13:27:41.167  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:27:41.167  1114  1114 I HtcPowerSaver: << updateStatus
,08-24 13:27:41.197  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:27:41.197  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:27:41.197  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:27:41.197  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 13:27:41.207  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:27:42.297   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 13:27:46.587  1114  1114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,08-24 13:28:01.347  7690  7690 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@10b6097f for type 1,
08-24 13:28:01.347  7690  7690 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@10b6097f for type 0
,08-24 13:28:01.367  1114  8591 D Process : killProcessQuiet, pid=7690,
08-24 13:28:01.367  1114  8591 I ActivityManager: Killing 7690:com.htc.music:musicenhancer/u0a24 (adj 15): empty #17
08-24 13:28:01.367  1114  8591 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 13:28:01.507  1114  3385 I ActivityManager: Recipient 7690,
,08-24 13:28:02.297   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-24 13:28:04.327  3541  3541 D TelephonyReceiver: switchBindHtcMsgCursor: null
,08-24 13:28:12.687  1114  3031 D PMS     : acquireWL(c9b7079): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1114 1000 WorkSource{1000},
08-24 13:28:12.687  1114  3031 V AlarmManager: sending alarm PendingIntent{3d192745: PendingIntentRecord{120aee9a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=165155, Int=0
08-24 13:28:12.717  1114  3031 I ActivityManager: Start proc 9189:com.htc.sense.mms/u0a51 for service com.htc.sense.mms/.transaction.TransactionService,
08-24 13:28:12.717  1114  3031 V AlarmManager: sending alarm PendingIntent{3109f1be: PendingIntentRecord{1fd8021f com.htc.sense.mms startService}}, i=android.intent.action.ACTION_ONALARM, t=0, cnt=1, w=1472038092694, Int=0
,08-24 13:28:12.757  9189  9189 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 13:28:12.757  9189  9189 W HTCLOG  : mask=0x18
,08-24 13:28:12.767  1114  1114 D PMS     : releaseWL(c9b7079): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-24 13:28:12.807  9189  9189 D MessageFrequencyProvider: onCreate
,08-24 13:28:12.817  9189  9189 D MessageCustFlag: sense_version=7.0,
08-24 13:28:12.817  9189  9189 V GetPrviateResource: GetPrviateResource
08-24 13:28:12.817  9189  9189 V GetPrviateResource: GetPrviateResource
08-24 13:28:12.817  9189  9189 D RcsChatUtils: isSup> false
,08-24 13:28:12.827  9189  9189 D n       : createReceiver
,08-24 13:28:12.827  9189  9189 D n       : registerReceiver return intent = null
,08-24 13:28:12.857  9189  9189 W HTCLOG  : use specified tag [asset], func [0].
08-24 13:28:12.857  9189  9189 W HTCLOG  : mask=0x18
08-24 13:28:12.857  9189  9189 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
08-24 13:28:12.857  9189  9189 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
,08-24 13:28:12.857  9189  9189 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@309a6195 for type 0
,08-24 13:28:12.857  9189  9189 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@309a6195 for type 1
08-24 13:28:12.857  9189  9189 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@309a6195 for type 5
08-24 13:28:12.857  9189  9189 V TransactionService: 1-Creating TransactionService
,08-24 13:28:12.867  9189  9189 V TransactionService: onStartCommand: 1,
08-24 13:28:12.867  9189  9189 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,08-24 13:28:12.867  9189  9212 V TransactionService: 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.au }
08-24 13:28:12.867  9189  9212 V TransactionService: Loading previous transactions.
,08-24 13:28:12.887  3541  3560 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64,
,08-24 13:28:12.887  9189  9212 D TransactionService: Force clearing mTransactionList
,08-24 13:28:12.897  9189  9212 D TransactionService: Force set service start id to 1
08-24 13:28:12.897  9189  9212 V TransactionService: stopSelfIfIdle
,08-24 13:28:12.897  9189  9212 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
08-24 13:28:12.897  9189  9189 V TransactionService: Destroying TransactionService
08-24 13:28:12.897  1114  3084 I ActivityManager: Killing 8655:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-24 13:28:12.897  1114  3084 D Process : killProcessQuiet, pid=8655
08-24 13:28:12.897  1114  3084 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 13:28:13.027  1114  8591 I ActivityManager: Recipient 8655,
,08-24 13:28:13.107  9189  9212 V TransactionService: 4-Handling incoming message: { when=-215ms what=100 target=com.htc.sense.mms.transaction.au }
,08-24 13:28:13.107  9189  9212 V Scheduler: Scheduler safely quits looper.,
,08-24 13:28:14.877  9189  9189 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist,
08-24 13:28:14.887  9189  9189 D MessageCustFlag: sku_id=58,
,08-24 13:28:14.887  9189  9215 D Messaging: mNeedToUpdateDate2 start,
,08-24 13:28:14.897  9189  9189 D ReportIndicatorCache: startAsyncQueryReports --- , first = true,
,08-24 13:28:14.907  9189  9211 D ReportIndicatorCache: MSG_QUERY_REPORTS >>,
,08-24 13:28:14.907  3541  3980 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
08-24 13:28:14.907  3541  3980 D MmsSmsV2Provider:  slotId = -1
08-24 13:28:14.907  3541  3980 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,08-24 13:28:14.927  9189  9189 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@f9a90d9
,08-24 13:28:14.937  3541  3561 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
08-24 13:28:14.937  3541  3561 D MmsSmsV2Provider:  slotId = -1
08-24 13:28:14.937  3541  3561 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
08-24 13:28:14.937  9189  9210 D MmsAsyncWorkHandler: 
08-24 13:28:14.937  9189  9210 D MmsAsyncWorkHandler: HM tk = 20002
,08-24 13:28:14.947  9189  9189 D DraftCache: [DraftCache/1] DraftCache.constructor
08-24 13:28:14.947  9189  9189 D DraftCache: [DraftCache/1] refresh
,08-24 13:28:14.947  3541  4654 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
08-24 13:28:14.947  3541  4654 D MmsSmsV2Provider:  slotId = -1
08-24 13:28:14.947  3541  4654 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,08-24 13:28:14.947  9189  9215 D Messaging: mNeedToUpdateDate2: false
,08-24 13:28:14.947  9189  9218 D MmsConfig: Start to get Carrier ID
08-24 13:28:14.947  3541  4638 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
08-24 13:28:14.947  3541  4638 D MmsSmsV2Provider:  slotId = -1
08-24 13:28:14.947  3541  4638 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null
,08-24 13:28:14.957  9189  9189 D MmsConfig: networkCode: ,
08-24 13:28:14.957  3541  3560 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
08-24 13:28:14.957  3541  3560 D MmsSmsV2Provider:  slotId = -1
08-24 13:28:14.957  3541  3560 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
08-24 13:28:14.957  9189  9217 I Messaging: mccmnc> 
,08-24 13:28:14.957  9189  9220 D Messaging: ViewCache CreatePreloadOnlyConversationList
08-24 13:28:14.957  9189  9220 D MessageCustFlag: sense_version=7.0
,08-24 13:28:14.967  9189  9220 D Jerry   : start to preload cursor >>>>>>>,
,08-24 13:28:14.967  3541  4638 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
,08-24 13:28:14.967  9189  9216 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,08-24 13:28:14.977  3541  3980 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
,08-24 13:28:14.977  9189  9189 D HfmClient: getIHFMServiceHMSApiLevel: +++
,08-24 13:28:14.977  9189  9189 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
,08-24 13:28:14.977  9189  9189 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak
08-24 13:28:14.977  9189  9189 D HfmClient: getIHFMServiceHMSApiLevel: Level = 1
08-24 13:28:14.977  9189  9189 D HfmClient: HfmServiceHMS API Level = 1
,08-24 13:28:14.987  3541  4638 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102,
,08-24 13:28:14.987  9189  9189 D ew      : createReceiver
,08-24 13:28:14.987  3541  3541 D IccSmsInterfaceManager: [IccSmsInterfaceManager] Cannot get carrier id
,08-24 13:28:14.987  3541  3980 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
08-24 13:28:14.987  3541  3980 D MmsSmsV2Provider:  slotId = -1
08-24 13:28:14.987  9189  9218 D MmsConfig: Carrier ID is NULL
,08-24 13:28:14.997  1114  1134 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-24 13:28:14.997  9189  9222 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,08-24 13:28:14.997  9189  9222 D ew      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0
,08-24 13:28:15.007  9189  9189 D HtcBuildUtils: getRATByHtcTelephonyCapability:1,
08-24 13:28:15.007  3541  4638 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
08-24 13:28:15.007  3541  4638 V MmsProvider: Update uri=content://mms, match=0
08-24 13:28:15.007  3541  4638 V MmsProvider: selection=st=129 AND m_type!=134
,08-24 13:28:15.007  9189  9189 W SystemReader: Cannot find support_cw, use default value instead
08-24 13:28:15.007  9189  9189 W SystemReader: Cannot find qct_8960_interface, use default value instead
,08-24 13:28:15.007  9189  9222 D ew      : /storage/emulated/0 : mounted
,08-24 13:28:15.007  9189  9226 D Messaging: Reset downloading state: 0
08-24 13:28:15.007  1114  5674 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
08-24 13:28:15.007  9189  9222 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,08-24 13:28:15.007  9189  9210 D DraftCache: [DraftCache/186] rebuildCache
,08-24 13:28:15.017  3541  4654 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
08-24 13:28:15.017  3541  4654 D Jerry   : URI_DRAFT
08-24 13:28:15.017  9189  9220 D Messaging: ViewCache CreatePreload
08-24 13:28:15.017  9189  9220 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
,08-24 13:28:15.017  9189  9226 V Messaging: Start TransactionService after 2 minutes from now
08-24 13:28:15.017  9189  9210 D DraftCache: hasDraft() = false mNeedNotifyChange = true,
08-24 13:28:15.017  9189  9210 D DraftCache: [DraftCache/186] rebuildCache time: 1
,08-24 13:28:15.027  9189  9220 D Cust_MMSMS: _has_set_default_values_2=true
,08-24 13:28:15.027  9189  9220 D TextSizeManager: [get_list_body_TextSize]__size57,
08-24 13:28:15.027  9189  9220 D TextSizeManager: [get_list_body_TextSize]__size48
08-24 13:28:15.027  9189  9220 D TextSizeManager: [get_list_body_TextSize]__size0
08-24 13:28:15.027  9189  9220 D TextSizeManager: [get_list_body_TextSize]__size57
08-24 13:28:15.027  9189  9220 D TextSizeManager: [get_list_body_TextSize]__size66
08-24 13:28:15.027  9189  9220 D TextSizeManager: [get_list_body_TextSize]__size74
08-24 13:28:15.027  9189  9220 D TextSizeManager: [get_list_body_TextSize]__size83
08-24 13:28:15.027  9189  9220 D MsgPreferenceUtils: def_index: 0
,08-24 13:28:15.027  9189  9220 D MsgPreferenceUtils: globalIndex = 2
,08-24 13:28:15.027  9189  9220 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
08-24 13:28:15.027  1114  3385 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-24 13:28:15.037  1114  3540 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
08-24 13:28:15.037  9189  9220 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files,
,08-24 13:28:15.037  9189  9220 D MsgPreferenceUtils: phone state: true,
08-24 13:28:15.037  9189  9220 D MsgPreferenceUtils: sd state: false
08-24 13:28:15.037  9189  9220 D MsgPreferenceUtils: vIndex = 1
,08-24 13:28:15.057  9189  9242 D RcsWorkingHandler: handler msg:{ when=0 what=1 target=com.htc.sense.mms.rcschat.bo },
08-24 13:28:15.057  9189  9242 D RcsWorkingHandler: not support Rcs, return
08-24 13:28:15.057  9189  9220 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=
08-24 13:28:15.057  9189  9220 D PersonalizeUtils: isHTCThemeChange_full isChange= false
,08-24 13:28:15.057  9189  9220 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
08-24 13:28:15.057  9189  9220 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
08-24 13:28:15.057  9189  9220 D PersonalizeUtils: isHTCThemeChange_CC equal time= 1466486566,old=1466486566
08-24 13:28:15.057  9189  9220 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
,08-24 13:28:15.117  1114  5158 I art     : Explicit concurrent mark sweep GC freed 23704(1319KB) AllocSpace objects, 4(96KB) LOS objects, 33% free, 16MB/24MB, paused 1.950ms total 151.072ms
,08-24 13:28:27.307   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 13:28:40.617  1114  3031 D PMS     : acquireWL(260cdfd2): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{1000},
08-24 13:28:40.627  1114  3031 V AlarmManager: sending alarm PendingIntent{e1978a3: PendingIntentRecord{34ac37a0 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DEADLINE_EXPIRED, t=3, cnt=1, w=167762, Int=0
08-24 13:28:40.627  1114  3031 V AlarmManager: sending alarm PendingIntent{c069f59: PendingIntentRecord{3b35271e android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=205783, Int=0
,08-24 13:28:40.657  1114  1114 D PMS     : acquireWL(33591b): PARTIAL_WAKE_LOCK  *job*/com.google.android.gms/.gcm.nts.TaskExecutionService 0x1 1114 1000 WorkSource{10019},
08-24 13:28:40.667  1114  1114 D PMS     : releaseWL(260cdfd2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-24 13:28:40.677  1114  1114 D PMS     : releaseWL(33591b): PARTIAL_WAKE_LOCK  *job*/com.google.android.gms/.gcm.nts.TaskExecutionService 0x1 WorkSource{10019},
,08-24 13:28:40.687  1114  1133 D PMS     : acquireWL(e55ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 null
,08-24 13:28:40.707  1114  3540 D PMS     : acquireWL(259be091): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 WorkSource{10019 com.google.android.gms},
,08-24 13:28:40.737  1114  5674 D PMS     : releaseWL(259be091): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10019 com.google.android.gms}
,08-24 13:28:40.747  1114  1133 D PMS     : acquireWL(3a46bf7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 WorkSource{10019 com.google.android.gms},
,08-24 13:28:40.787  1114  3562 D PMS     : releaseWL(e55ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
08-24 13:28:40.787  1114  3540 D PMS     : acquireWL(3128e182): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 null
,08-24 13:28:40.787  1114  1133 D PMS     : releaseWL(3128e182): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 13:28:40.797  4016  9244 I VacuumService: Vacuum at: now=1472038120809 tag=VacuumService,
08-24 13:28:40.797  1114  3385 D PMS     : acquireWL(d8cc8d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 null
,08-24 13:28:40.807  1114  8589 D PMS     : releaseWL(d8cc8d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 13:28:40.827  1114  3084 D PMS     : releaseWL(3a46bf7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10019 com.google.android.gms}
,08-24 13:28:40.827  1114  1133 D PMS     : acquireWL(2c96e2ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 null
,08-24 13:28:40.847  1114  3502 D PMS     : releaseWL(2c96e2ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 13:28:40.847  1114  3562 D PMS     : acquireWL(1b80f085): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 null
,08-24 13:28:40.857  1114  8591 D PMS     : releaseWL(1b80f085): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 13:28:40.857  1114  1133 D PMS     : acquireWL(b0d1eda): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4016 10019 null
,08-24 13:28:40.857  1114  5674 D PMS     : releaseWL(b0d1eda): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 13:28:41.267  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:28:41.267  1114  3582 D PMS     : acquireWL(39ae4ea6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:28:41.267  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:28:41.267  1114  3582 I BatteryService: n_update end,
08-24 13:28:41.267  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:28:41.267  1114  3582 D PMS     : releaseWL(39ae4ea6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:28:41.267  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:28:41.267  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:28:41.267  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:28:41.267  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:28:41.267  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:28:41.267  1114  1114 D HtcPowerSaver: Checking...
08-24 13:28:41.267  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:28:41.267  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:28:41.267  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:28:41.267  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:28:41.267  1114  3076 D WifiController: handleMessage: X
08-24 13:28:41.277  3199  3199 D PowerUI : closing low battery warning: level=100,
08-24 13:28:41.277  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:28:41.277  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:28:41.277  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:28:41.287  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:28:41.277  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:28:41.287  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:28:41.277  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-24 13:28:41.327  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:28:41.327  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:28:41.327  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:28:41.327  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:28:41.327  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:28:42.757  3199  4885 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,08-24 13:28:42.767  3636  3636 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1dd0cd3f,
,08-24 13:28:42.777  1114  8589 D Process : killProcessQuiet, pid=8310
08-24 13:28:42.777  1114  8589 I ActivityManager: Killing 8310:com.google.android.talk/u0a103 (adj 15): empty #17
08-24 13:28:42.787  1114  8589 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 13:28:42.807  3199  4885 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
,08-24 13:28:42.927  1114  3490 I ActivityManager: Recipient 8310
,08-24 13:28:45.107  3541  3716 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-24 13:28:45.107  3541  3716 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 5 BSSID 84:b2:61:1a:ce:7b SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 10 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 15 BSSID 84:b2:61:0f:9c:30 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 17 BSSID 84:b2:61:0f:9c:32 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 22 BSSID 84:b2:61:0f:9c:3a SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 29 BSSID 00:fe:c8:73:02:06 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 31 BSSID 84:b2:61:21:47:52 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 33 BSSID 84:b2:61:1a:ce:71 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 35 BSSID 84:b2:61:0f:9c:31 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:47.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 40 BSSID 00:fe:c8:73:02:01 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:47.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
,08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 1 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 2 BSSID 58:48:22:a4:0e:72 SSID 'Xperia X_b412' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 6 BSSID 84:b2:61:1a:ce:7a SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 3 BSSID 84:b2:61:1a:ce:79 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 4 BSSID 84:b2:61:1a:ce:7f SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 8 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 7 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 41 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 11 BSSID 84:b2:61:1a:ce:72 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 9 BSSID 84:b2:61:1a:ce:75 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.317  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.317  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 12 BSSID 84:b2:61:1a:ce:76 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 13 BSSID 84:b2:61:1a:ce:74 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 42 BSSID 84:b2:61:0f:9c:34 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 14 BSSID 84:b2:61:0f:9c:36 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 23 BSSID 84:b2:61:0f:9c:3f SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_c,trl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 24 BSSID 84:b2:61:0f:9c:3b SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 19 BSSID 84:b2:61:1c:62:d5 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 18 BSSID 84:b2:61:1c:62:d6 SSID '\x00' due to wpa_bss_flush_by_age
,08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 25 BSSID 84:b2:61:1c:62:d2 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 21 BSSID 84:b2:61:0f:9c:39 SSID '\x00' due to wpa_bss_flush_by_age
,08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 20 BSSID 84:b2:61:1c:62:d4 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 43 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 16 BSSID 84:b2:61:1c:62:d0 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 44 BSSID 84:b2:61:12:64:94 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
,08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 28 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 26 BSSID 84:b2:61:12:64:90 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 27 BSSID 84:b2:61:12:64:92 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 45 BSSID 84:b2:61:12:64:96 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 46 BSSID 84:b2:61:12:64:95 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 47 BSSID 84:b2:61:21:47:5a SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 48 BSSID 84:b2:61:21:47:5f SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
,08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 49 BSSID 84:b2:61:12:64:9f SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 50 BSSID 84:b2:61:12:64:9b SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 51 BSSID 84:b2:61:12:64:9a SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 30 BSSID 00:fe:c8:73:02:00 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 52 BSSID 84:b2:61:1c:62:d9 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 53 BSSID 84:b2:61:12:64:99 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 54 BSSID 00:fe:c8:73:02:04 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
,08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 55 BSSID 84:b2:61:21:47:54 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 32 BSSID 84:b2:61:1a:ce:7e SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 34 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 36 BSSID 84:b2:61:0f:9c:33 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 56 BSSID 84:b2:61:0f:9c:3e SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 38 BSSID 84:b2:61:1c:62:d1 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 37 BSSID 84:b2:61:1c:62:d3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
,08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 57 BSSID 84:b2:61:12:64:93 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 58 BSSID 84:b2:61:12:64:91 SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 39 BSSID 00:fe:c8:73:02:03 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 59 BSSID 84:b2:61:1c:62:de SSID '\x00' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
08-24 13:28:57.327  3146  3146 D wpa_supplicant: wlan0: BSS: Remove ID 60 BSSID 84:b2:61:21:47:53 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 13:28:57.327  3146  3146 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1114-2\x00
,08-24 13:29:07.317   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 13:29:17.317   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-24 13:29:32.327   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 13:29:41.417  1114  3084 D PMS     : acquireWL(259240e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:29:41.437  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:29:41.427  1114  3084 I BatteryService: n_update end
,08-24 13:29:41.447  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:29:41.437  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:29:41.447  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:29:41.447  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:29:41.447  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:29:41.447  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:29:41.447  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:29:41.447  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:29:41.447  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:29:41.447  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:29:41.457  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:29:41.447  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:29:41.457  1114  1114 D HtcPowerSaver: Checking...
08-24 13:29:41.447  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:29:41.457  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:29:41.447  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:29:41.447  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:29:41.447  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:29:41.447  1114  3076 D WifiController: handleMessage: X
08-24 13:29:41.457  1114  3084 D PMS     : releaseWL(259240e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:29:41.457  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:29:41.467  1114  1114 I HtcPowerSaver: << updateStatus
,08-24 13:29:41.497  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:29:41.497  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:29:41.497  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:29:41.497  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:29:41.497  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:29:52.337   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-24 13:30:15.007  1114  3031 D PMS     : acquireWL(28b63494): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1114 1000 WorkSource{1000},
08-24 13:30:15.017  1114  3031 V AlarmManager: sending alarm PendingIntent{3d192745: PendingIntentRecord{120aee9a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=225155, Int=0
,08-24 13:30:15.027  9189  9189 V TransactionService: 1-Creating TransactionService
08-24 13:30:15.037  1114  3031 V AlarmManager: sending alarm PendingIntent{fe0af32: PendingIntentRecord{2ab80483 com.htc.sense.mms startService}}, i=android.intent.action.ACTION_ONALARM, t=0, cnt=1, w=1472038215020, Int=0
08-24 13:30:15.077  9189  9189 V TransactionService: onStartCommand: 1
08-24 13:30:15.077  9189  9189 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,08-24 13:30:15.087  9189  9245 V TransactionService: 4-Handling incoming message: { when=-11ms what=2 arg1=1 target=com.htc.sense.mms.transaction.au }
08-24 13:30:15.087  1114  1114 D PMS     : releaseWL(28b63494): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
08-24 13:30:15.087  9189  9245 V TransactionService: Loading previous transactions.
,08-24 13:30:15.097  3541  3561 D TelephUtils: DELETE for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
08-24 13:30:15.097  3541  3561 V MmsProvider: Delete uri=content://mms/9223372036854775807/part, match=11
08-24 13:30:15.097  3541  3561 V MmsProvider: selection=null
,08-24 13:30:15.107  3541  3969 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
,08-24 13:30:15.107  9189  9245 D TransactionService: Force clearing mTransactionList
08-24 13:30:15.107  9189  9245 D TransactionService: Force set service start id to 1
,08-24 13:30:15.107  9189  9245 V TransactionService: stopSelfIfIdle
,08-24 13:30:15.117  9189  9245 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
08-24 13:30:15.117  9189  9189 V TransactionService: Destroying TransactionService
08-24 13:30:15.117  9189  9245 V TransactionService: 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.au }
08-24 13:30:15.117  9189  9245 V Scheduler: Scheduler safely quits looper.
,08-24 13:30:17.347   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 13:30:18.837   500   500 E TPD     : [TPD][ERR] can't open /proc/13/status...,
,08-24 13:30:40.877  1114  3031 D PMS     : acquireWL(20c0600): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{1000},
08-24 13:30:40.887  1114  3031 V AlarmManager: sending alarm PendingIntent{c069f59: PendingIntentRecord{3b35271e android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=326045, Int=0
08-24 13:30:40.887  1114  1114 D PMS     : releaseWL(20c0600): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,08-24 13:30:41.577  1114  3582 D PMS     : acquireWL(2cf2be39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:30:41.597  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:30:41.577  1114  3582 I BatteryService: n_update end
08-24 13:30:41.597  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:30:41.597  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:30:41.597  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:30:41.597  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:30:41.597  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:30:41.607  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:30:41.607  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:30:41.607  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:30:41.607  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:30:41.607  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:30:41.607  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:30:41.607  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:30:41.607  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:30:41.607  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:30:41.607  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:30:41.607  1114  3076 D WifiController: handleMessage: X
,08-24 13:30:41.617  1114  1175 D HtcPowerSaver: updateBatteryInfo,
08-24 13:30:41.617  1114  1114 D HtcPowerSaver: Checking...
08-24 13:30:41.617  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:30:41.627  1114  3582 D PMS     : releaseWL(2cf2be39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:30:41.627  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:30:41.627  1114  1114 I HtcPowerSaver: << updateStatus
,08-24 13:30:41.647  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:30:41.647  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:30:41.647  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:30:41.647  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 13:30:41.647  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:31:02.347   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 13:31:12.357   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 13:31:27.367   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 13:31:41.747  1114  1133 D PMS     : acquireWL(32668c7e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:31:41.747  1114  1133 I BatteryService: n_update end
08-24 13:31:41.747  1114  1133 D PMS     : releaseWL(32668c7e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 13:31:41.757  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false),
08-24 13:31:41.757  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:31:41.757  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:31:41.757  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:31:41.757  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:31:41.757  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:31:41.757  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:31:41.757  1114  1114 D HtcPowerSaver: Checking...
08-24 13:31:41.757  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:31:41.757  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:31:41.757  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:31:41.757  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:31:41.757  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:31:41.757  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:31:41.757  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:31:41.777  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:31:41.757  1114  3076 D WifiController: handleMessage: E msg.what=155652
,08-24 13:31:41.777  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:31:41.757  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:31:41.757  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:31:41.757  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:31:41.757  1114  3076 D WifiController: handleMessage: X
,08-24 13:31:41.807  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 13:31:41.807  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:31:41.807  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:31:41.807  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:31:41.807  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:31:47.367   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-24 13:32:12.377   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 13:33:02.387   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 13:33:12.387   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 13:33:17.717  1114  3540 D PMS     : acquireWL(1bec65df): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
,08-24 13:33:17.717  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
,08-24 13:33:17.717  1114  3540 I BatteryService: n_update end
08-24 13:33:17.717  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:33:17.717  1114  3540 D PMS     : releaseWL(1bec65df): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:33:17.717  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,08-24 13:33:17.717  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:33:17.717  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:33:17.717  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:33:17.717  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:33:17.727  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:33:17.717  1114  3076 D WifiController: processMsg: DeviceActiveState
,08-24 13:33:17.727  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:33:17.717  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:33:17.727  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:33:17.717  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:33:17.727  1114  1114 D HtcPowerSaver: Checking...
08-24 13:33:17.717  1114  3076 D WifiController: handleMessage: X
08-24 13:33:17.727  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:33:17.717  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:33:17.747  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:33:17.717  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:33:17.747  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:33:17.717  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:33:17.727  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:33:17.757  1114  1160 I ActivityManager: Start proc 9258:com.android.settings/1000 for broadcast com.android.settings/.framework.app.HtcSystemReceiver
,08-24 13:33:17.757  9258  9258 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 13:33:17.757  9258  9258 W HTCLOG  : mask=0x18
,08-24 13:33:17.777  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 13:33:17.777  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:33:17.777  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:33:17.777  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:33:17.777  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:33:17.797  9258  9258 V Settings:HtcSettingsApplication: [9258/9258] onCreate(),
,08-24 13:33:17.807  9258  9258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.framework.app.HtcSystemReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:2719 
,08-24 13:33:17.817  9258  9279 D SmartNS_NSReceiver: plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,08-24 13:33:17.817  9258  9279 D SmartNS_NSReceiver: Index of the first 1 = 3
,08-24 13:33:17.817  9258  9279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1836 android.content.ContextWrapper.stopService:521 com.android.settings.NSReceiver.onReceive:182 android.support.v4.content.g.a:297 android.support.v4.content.g.b:278 
,08-24 13:33:17.817  9258  9279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 android.content.ContextWrapper.sendBroadcast:377 com.android.settings.NSReceiver.onReceive:184 android.support.v4.content.g.a:297 android.support.v4.content.g.b:278 
,08-24 13:33:17.827  9258  9279 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 13:33:17.827  9258  9279 I SmartNS_Utility: hasRemovableStorageSlot: true,
08-24 13:33:17.827  9258  9279 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
08-24 13:33:17.827  9258  9279 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,08-24 13:33:17.837  9258  9279 D SmartNS_Utility: [ACC]android_networking:tethering_guard_support=false
,08-24 13:33:17.837  9258  9279 W SystemReader: Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,08-24 13:33:17.837  1114  8589 D Process : killProcessQuiet, pid=8233
08-24 13:33:17.837  1114  8589 I ActivityManager: Killing 8233:com.google.android.gm/u0a97 (adj 15): empty #17
08-24 13:33:17.837  1114  8589 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 13:33:17.887  1114  8591 I ActivityManager: Recipient 8233
,08-24 13:33:27.397   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 13:33:47.407   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-24 13:34:12.407   580   580 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 13:34:17.897  1114  3385 D PMS     : acquireWL(323804f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
,08-24 13:34:17.897  1114  3385 I BatteryService: n_update end
08-24 13:34:17.907  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:34:17.907  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:34:17.907  3199  3199 D PowerUI : closing low battery warning: level=100
,08-24 13:34:17.907  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:34:17.917  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:34:17.917  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:34:17.917  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:34:17.917  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:34:17.917  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:34:17.917  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:34:17.927  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:34:17.917  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,08-24 13:34:17.937  1114  1114 D HtcPowerSaver: Checking...
08-24 13:34:17.917  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:34:17.937  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:34:17.917  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:34:17.937  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:34:17.917  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:34:17.937  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:34:17.917  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:34:17.947  1114  3385 D PMS     : releaseWL(323804f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 13:34:17.917  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:34:17.917  1114  3076 D WifiController: handleMessage: X
,08-24 13:34:17.967  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:34:17.967  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:34:17.967  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:34:17.967  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:34:17.967  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:35:02.417   580   580 W HTCLOG  : use specified tag [QC-QMI], func [18].,
08-24 13:35:02.417   580   580 W HTCLOG  : mask=0x18
,08-24 13:35:18.057  1114  3501 D PMS     : acquireWL(3ddaf28a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null,
08-24 13:35:18.067  1114  3501 I BatteryService: n_update end
08-24 13:35:18.077  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:35:18.077  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:35:18.077  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:35:18.077  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:35:18.087  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:35:18.077  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:35:18.087  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:35:18.087  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:35:18.087  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:35:18.087  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:35:18.087  1114  1114 D HtcPowerSaver: Checking...
08-24 13:35:18.087  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:35:18.087  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:35:18.087  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:35:18.097  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:35:18.087  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:35:18.087  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:35:18.087  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:35:18.087  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:35:18.087  1114  3076 D WifiController: handleMessage: X
08-24 13:35:18.097  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:35:18.097  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:35:18.107  1114  3501 D PMS     : releaseWL(3ddaf28a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 13:35:18.127  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:35:18.127  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:35:18.127  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:35:18.127  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:35:18.127  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:35:19.967   508   529 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,08-24 13:35:40.467  3541  3716 D ContactMessageStore: MSG_CHECK_DELETION >>,
08-24 13:35:40.467  3541  3716 D ContactMessageStore: mDeleteTask = null, bDeleting = false
,08-24 13:35:40.467  3541  3716 D AccFlag : sku_id=58,
08-24 13:35:40.477  3541  3716 D ContactMessageStore: MSG_CHECK_DELETION <<,
08-24 13:35:40.477  3541  9287 D ContactMessageStore: start background delete task...
08-24 13:35:40.477  3541  9287 D ContactMessageStore: size: 0 , 0,
08-24 13:35:40.477  3541  9287 D ContactMessageStore: Background delete complete
,08-24 13:36:18.227  1114  1133 D PMS     : acquireWL(2cdb80fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:36:18.227  1114  1133 I BatteryService: n_update end
08-24 13:36:18.227  1114  1133 D PMS     : releaseWL(2cdb80fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 13:36:18.237  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:36:18.237  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:36:18.237  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:36:18.237  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:36:18.237  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,08-24 13:36:18.237  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:36:18.237  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:36:18.247  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:36:18.247  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:36:18.247  1114  1114 D HtcPowerSaver: Checking...
08-24 13:36:18.247  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:36:18.247  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:36:18.247  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:36:18.247  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:36:18.247  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:36:18.247  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:36:18.247  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:36:18.247  1114  1114 I HtcPowerSaver: << updateStatus,
08-24 13:36:18.247  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:36:18.247  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:36:18.247  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:36:18.247  1114  3076 D WifiController: handleMessage: X
,08-24 13:36:18.287  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:36:18.287  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:36:18.287  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:36:18.287  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:36:18.287  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:36:45.167  1114  3540 D Process : killProcessQuiet, pid=8705,
08-24 13:36:45.167  1114  3540 I ActivityManager: Killing 8705:pl.tmobile.panel/u0a64 (adj 15): empty #17
08-24 13:36:45.167  1114  3540 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 13:36:45.257  1114  8589 I ActivityManager: Recipient 8705
,08-24 13:38:18.547  1114  3562 D PMS     : acquireWL(37e49518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:38:18.547  1114  3562 I BatteryService: n_update end
08-24 13:38:18.547  1114  3562 D PMS     : releaseWL(37e49518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:38:18.547  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:38:18.547  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:38:18.547  3199  3199 D PowerUI : closing low battery warning: level=100
,08-24 13:38:18.557  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:38:18.557  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:38:18.557  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:38:18.557  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:38:18.557  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:38:18.557  1114  1114 D HtcPowerSaver: Checking...
08-24 13:38:18.557  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:38:18.557  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:38:18.557  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:38:18.557  1114  3076 D WifiController: battery changed pluggedType: 2
,08-24 13:38:18.557  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:38:18.567  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:38:18.557  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:38:18.567  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:38:18.557  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:38:18.557  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:38:18.557  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:38:18.557  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:38:18.557  1114  3076 D WifiController: handleMessage: X
,08-24 13:38:18.607  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:38:18.607  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true,
08-24 13:38:18.607  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:38:18.607  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:38:18.607  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:40:57.647  1114  3031 D PMS     : acquireWL(1a50fb71): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1114 1000 WorkSource{1000}
08-24 13:40:57.657  1114  3031 V AlarmManager: sending alarm PendingIntent{3d192745: PendingIntentRecord{120aee9a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=345155, Int=0
08-24 13:40:57.667  5533  5533 D BluetoothAdapterService(511021191): handleMessage() - Message: 110
08-24 13:40:57.667  5533  5533 D BluetoothAdapterService(511021191): handleMessage() - MESSAGE_RELEASE_WAKE_ALARM
08-24 13:40:57.667  5533  5754 I bt-btm  : Received oneshot timer event complete
08-24 13:40:57.667  5533  5754 I bt-btm  : btm_ble_timeout
08-24 13:40:57.667  5533  5754 I bt-btm  : btm_gen_resolvable_private_addr
,08-24 13:40:57.677  1114  3582 D PMS     : acquireWL(b7dad56): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5533 1002 null
08-24 13:40:57.707  5533  5754 I bt-hci  : 13:40:57.717 --
08-24 13:40:57.677  1114  3031 V AlarmManager: sending alarm PendingIntent{15d731d7: PendingIntentRecord{119eac4 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=942817, Int=0
08-24 13:40:57.707  5533  5754 I bt-hci  : 13:40:57.717 SENT Command to HCI. Name: HCI_LE_Rand  (Hex Code: 0x2018  Param Len: 0) Ctrl(0)
,08-24 13:40:57.707  5533  5754 I bt-hci  : 13:40:57.717 --
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726 --
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726 RCVD Event from HCI. Name: HCI_Command_Complete  (Hex Code: 0x0e  Param Len: 12) Ctrl(0)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726 Parameters
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726                      Num HCI Cmd Packets : 1 (0x01)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726                                 Cmd Code : 0x2018  (HCI_LE_Rand)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726                                   Status : Success (0x00)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726                            Random Number : 70 60 45 9a a8 37 12 43 
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.726 --
08-24 13:40:57.717  5533  5754 D bt-btm  : btm_ble_rand_enc_complete
08-24 13:40:57.717  5533  5754 I bt-btm  : btm_gen_resolve_paddr_low
08-24 13:40:57.717  5533  5754 D bt-smp  : smp_encrypt_data
08-24 13:40:57.717  5533  5754 D bt-smp  : Key(LSB ~ MSB) = 2b d8 9e 69 23 5b 6a 34 c8 5f a4 fb f9 34 ec 0c 
08-24 13:40:57.717  5533  5754 D bt-smp  : Plain text(LSB ~ MSB) = 70 60 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 13:40:57.717  5533  5754 D bt-smp  : Encrypted text(LSB ~ MSB) = 34 e8 02 f5 15 a9 04 13 34 c2 3f 74 e1 69 92 66 
08-24 13:40:57.717  5533  5754 I bt-btm  : btm_gen_resolve_paddr_cmpl
08-24 13:40:57.717  5533  5754 I bt-hci  : 13:40:57.727 --
08-24 13:40:57.717  5533  5754 I bt-hci  : 13:40:57.727 SENT Command to HCI. Name: HCI_LE_Write_random_Address  (Hex Code: 0x2005  Param Len: 6) Ctrl(0)
08-24 13:40:57.717  5533  5754 I bt-hci  : 13:40:57.727 Parameters 
08-24 13:40:57.717  5533  5754 I bt-hci  : 13:40:57.727                           Random BD Addr : 45-60-70-02-e8-34
,08-24 13:40:57.717  5533  5754 I bt-hci  : 13:40:57.727 --
08-24 13:40:57.717  5533  5754 W bt-btm  : Stopping oneshot timer
08-24 13:40:57.717  5533  5754 D bt-btm  : Starting oneshot timer type:103 timeout:900s
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.729 --
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.729 RCVD Event from HCI. Name: HCI_Command_Complete  (Hex Code: 0x0e  Param Len: 4) Ctrl(0)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.729 Parameters
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.729                      Num HCI Cmd Packets : 1 (0x01)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.729                                 Cmd Code : 0x2005  (HCI_LE_Write_random_Address)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.729                                   Status : Success (0x00)
08-24 13:40:57.717  5533  5756 I bt-hci  : 13:40:57.729 --
,08-24 13:40:57.737  1114  1114 D PMS     : releaseWL(1a50fb71): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-24 13:40:58.707  5533  5533 D BluetoothAdapterService(511021191): handleMessage() - Message: 100,
08-24 13:40:58.707  5533  5533 D BluetoothAdapterService(511021191): handleMessage() - MESSAGE_SET_WAKE_ALARM
08-24 13:40:58.707  1114  8591 D PMS     : releaseWL(b7dad56): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,08-24 13:41:08.507  1114  3031 D PMS     : acquireWL(3528ddad): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1114 1000 WorkSource{1000}
08-24 13:41:08.517  1114  3031 V AlarmManager: sending alarm PendingIntent{3d192745: PendingIntentRecord{120aee9a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=945155, Int=0
,08-24 13:41:08.527  1114  3031 V AlarmManager: sending alarm PendingIntent{36bf48e2: PendingIntentRecord{18731473 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.intent.action.HTCPOWERMGR_SMARTSYNC_SCREEN_OFF_TIME, t=0, cnt=1, w=1472038868522, Int=0,
,08-24 13:41:08.557  1114  1160 I ActivityManager: Start proc 9300:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver,
,08-24 13:41:08.607  9300  9300 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 13:41:08.607  9300  9300 W HTCLOG  : mask=0x18
,08-24 13:41:08.677  1114  8591 D PMS     : acquireWL(3d2cef30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 9300 1000 null
,08-24 13:41:08.677  1114  3385 D Process : killProcessQuiet, pid=8828
08-24 13:41:08.677  1114  3385 I ActivityManager: Killing 8828:com.htc.sense.news/u0a56 (adj 15): empty #17
,08-24 13:41:08.677  1114  3385 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processNextBroadcast:707 
08-24 13:41:08.677  1114  1114 D PMS     : releaseWL(3528ddad): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
08-24 13:41:08.677  9300  9322 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-24 13:41:08.677  9300  9322 W HTCLOG  : mask=0x18
,08-24 13:41:08.687  1114  1134 D PMS     : releaseWL(3d2cef30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,08-24 13:41:08.697  1114  8589 D PMS     : acquireWL(2c22a7a9): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 9300 1000 null
,08-24 13:41:08.697  9300  9323 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false
,08-24 13:41:08.697  9300  9323 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,08-24 13:41:08.697  9300  9323 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1
,08-24 13:41:08.697  9300  9323 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1472101200000, randomSettingOnTime = 1472098870000
08-24 13:41:08.697  9300  9323 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1472079600000, randomSettingOffTime = 1472082317000
08-24 13:41:08.697  9300  9323 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false
,08-24 13:41:08.707  9300  9323 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true
08-24 13:41:08.707  9300  9323 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false
,08-24 13:41:08.777  1114  3582 I ActivityManager: Recipient 8828,
,08-24 13:41:08.787  1114  8591 D PMS     : releaseWL(2c22a7a9): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,08-24 13:41:19.017  1114  5674 D PMS     : acquireWL(2f8d112e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:41:19.037  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:41:19.027  1114  5674 I BatteryService: n_update end
08-24 13:41:19.037  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:41:19.037  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:41:19.037  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:41:19.037  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:41:19.047  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:41:19.047  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:41:19.047  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:41:19.047  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:41:19.047  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:41:19.047  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:41:19.047  1114  1114 D HtcPowerSaver: Checking...
08-24 13:41:19.047  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:41:19.047  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:41:19.047  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:41:19.047  1114  5674 D PMS     : releaseWL(2f8d112e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:41:19.047  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:41:19.047  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:41:19.047  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:41:19.047  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:41:19.047  1114  3076 D WifiController: handleMessage: X
,08-24 13:41:19.057  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,08-24 13:41:19.057  1114  1114 I HtcPowerSaver: << updateStatus
,08-24 13:41:19.087  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:41:19.087  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:41:19.087  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:41:19.087  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:41:19.097  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:41:32.327  1114  3031 D PMS     : acquireWL(31e084cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{10019}
,08-24 13:41:32.327  1114  3031 V AlarmManager: sending alarm PendingIntent{2c29ce5c: PendingIntentRecord{1d51565 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1472038453632, Int=1800000,
08-24 13:41:32.337  1114  3031 V AlarmManager: sending alarm PendingIntent{255d123a: PendingIntentRecord{170a9eeb com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=977478, Int=0
08-24 13:41:32.337  1114  3031 V AlarmManager: sending alarm PendingIntent{3f6c7a9f: PendingIntentRecord{486d7ec android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805447, Int=0
08-24 13:41:32.337  1114  3031 V AlarmManager: sending alarm PendingIntent{20b37448: PendingIntentRecord{347b8c8d com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1472038868626, Int=0,
,08-24 13:41:32.347  1114  3562 D PMS     : acquireWL(1186a2e1): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4299 10019 null,
,08-24 13:41:32.367  1114  3501 D PMS     : acquireWL(16723ec7): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 4016 10019 null
,08-24 13:41:32.377  1114  1133 D PMS     : releaseWL(16723ec7): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,08-24 13:41:32.387  9300  9300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,08-24 13:41:32.387  1114  8589 D PMS     : acquireWL(32af8cf4): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4299 10019 null
,08-24 13:41:32.387  1114  3540 D PMS     : releaseWL(1186a2e1): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,08-24 13:41:32.397  1114  1114 D PMS     : releaseWL(31e084cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-24 13:41:32.397  9300  9328 D PowerUtils: getUserIdOfProcess, curUserId = 0
08-24 13:41:32.397  9300  9328 D PowerUtils: isRunningUnderOwner, isOwner = true
,08-24 13:41:32.397  9300  9328 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
,08-24 13:41:32.407  9300  9328 D PowerUsageService: repeat time = 1472039792418
08-24 13:41:32.417  4299  9327 I EventLogService: Aggregate from 1472037962793 (log), 1472036653594 (data)
,08-24 13:41:32.497  1114  8591 D PMS     : releaseWL(32af8cf4): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,08-24 13:41:32.527  9300  9328 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8,
,08-24 13:41:32.547  9300  9328 D PowerUtils: getUserIdOfProcess, curUserId = 0,
,08-24 13:41:32.557  9300  9328 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-24 13:41:32.557  9300  9328 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-24 13:41:32.567  9300  9328 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-24 13:41:32.587  9300  9328 D PowerUsageService: calcPower(), no data
,08-24 13:41:32.687  1114  3540 D PMS     : acquireWL(2297cd19): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 4016 10019 null
,08-24 13:41:32.737  4016  8910 D GCM     : Message class com.google.e.a.a.h
,08-24 13:41:32.737  1114  1133 D PMS     : releaseWL(2297cd19): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,08-24 13:43:19.347  1114  3582 D PMS     : acquireWL(357621de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:43:19.357  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:43:19.347  1114  3582 I BatteryService: n_update end
08-24 13:43:19.357  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:43:19.357  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:43:19.357  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:43:19.357  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:43:19.357  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false),
08-24 13:43:19.357  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:43:19.357  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:43:19.357  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:43:19.367  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:43:19.357  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:43:19.367  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:43:19.357  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:43:19.377  1114  1114 D HtcPowerSaver: Checking...
08-24 13:43:19.357  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:43:19.377  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:43:19.357  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:43:19.377  1114  3582 D PMS     : releaseWL(357621de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:43:19.357  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:43:19.357  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:43:19.357  1114  3076 D WifiController: handleMessage: X
08-24 13:43:19.377  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:43:19.377  1114  1114 I HtcPowerSaver: << updateStatus
,08-24 13:43:19.407  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:43:19.407  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:43:19.407  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:43:19.407  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:43:19.407  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:44:19.507  1114  3502 D PMS     : acquireWL(11523fbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:44:19.507  1114  3502 I BatteryService: n_update end
08-24 13:44:19.507  1114  3502 D PMS     : releaseWL(11523fbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 13:44:19.517  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:44:19.517  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:44:19.517  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:44:19.517  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:44:19.517  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:44:19.517  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:44:19.517  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:44:19.517  1114  1114 D HtcPowerSaver: Checking...
08-24 13:44:19.517  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+,
08-24 13:44:19.517  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:44:19.517  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:44:19.527  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:44:19.517  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:44:19.527  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:44:19.517  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:44:19.537  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:44:19.527  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:44:19.537  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:44:19.527  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:44:19.527  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:44:19.527  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:44:19.527  1114  3076 D WifiController: handleMessage: X
,08-24 13:44:19.567  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:44:19.567  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:44:19.567  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:44:19.567  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:44:19.567  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:45:19.967   508   529 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,08-24 13:45:34.407  1114  1159 I UsageStatsService: User[0] Flushing usage stats to disk,
,08-24 13:46:19.807  1114  3562 D PMS     : acquireWL(3c2b868c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
,08-24 13:46:19.807  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:46:19.807  1114  3562 I BatteryService: n_update end
08-24 13:46:19.807  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:46:19.807  1114  3562 D PMS     : releaseWL(3c2b868c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:46:19.807  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:46:19.807  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:46:19.807  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:46:19.817  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:46:19.817  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:46:19.817  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:46:19.817  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:46:19.817  1114  1114 D HtcPowerSaver: Checking...
08-24 13:46:19.817  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:46:19.817  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:46:19.817  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:46:19.817  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:46:19.817  1114  3076 D WifiController: handleMessage: X
08-24 13:46:19.817  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:46:19.817  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:46:19.817  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:46:19.817  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:46:19.817  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:46:19.817  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:46:19.817  1114  1114 I HtcPowerSaver: << updateStatus,
,08-24 13:46:19.867  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:46:19.867  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:46:19.867  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:46:19.867  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:46:19.867  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:47:19.987  1114  8591 D PMS     : acquireWL(3dcf21d5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:47:19.987  1114  8591 I BatteryService: n_update end
08-24 13:47:19.987  1114  8591 D PMS     : releaseWL(3dcf21d5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 13:47:19.997  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:47:19.997  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:47:19.997  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:47:19.997  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:47:19.997  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:47:19.997  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:47:19.997  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:47:19.997  1114  1114 D HtcPowerSaver: Checking...
08-24 13:47:19.997  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:47:19.997  1114  1114 I HtcPowerSaver: >> updateStatus,
08-24 13:47:19.997  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:47:20.007  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:47:19.997  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:47:20.007  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:47:19.997  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:47:20.017  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:47:20.007  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:47:20.017  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:47:20.007  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:47:20.007  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:47:20.007  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:47:20.007  1114  3076 D WifiController: handleMessage: X
,08-24 13:47:20.047  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 13:47:20.047  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:47:20.047  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:47:20.047  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 13:47:20.047  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:48:20.147  1114  3562 D PMS     : acquireWL(2d3e7dea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:48:20.157  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:48:20.147  1114  3562 I BatteryService: n_update end
08-24 13:48:20.157  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:48:20.157  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:48:20.157  3199  3199 D PowerUI : closing low battery warning: level=100
08-24 13:48:20.157  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:48:20.157  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:48:20.157  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:48:20.167  1114  3076 D WifiController: battery changed pluggedType: 2
08-24 13:48:20.157  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:48:20.167  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:48:20.157  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:48:20.167  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:48:20.157  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:48:20.167  1114  1114 D HtcPowerSaver: Checking...
08-24 13:48:20.167  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:48:20.167  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:48:20.167  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:48:20.177  1114  3562 D PMS     : releaseWL(2d3e7dea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 13:48:20.167  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:48:20.167  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:48:20.167  1114  3076 D WifiController: handleMessage: X
,08-24 13:48:20.177  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:48:20.177  1114  1114 I HtcPowerSaver: << updateStatus
,08-24 13:48:20.207  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 13:48:20.207  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:48:20.207  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:48:20.207  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 13:48:20.207  3199  3199 I FlashlightController: batteryLevelChange:100
,08-24 13:49:20.307  1114  3502 D PMS     : acquireWL(1af518db): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1114 1000 null
08-24 13:49:20.307  1114  3502 I BatteryService: n_update end
08-24 13:49:20.307  1114  3502 D PMS     : releaseWL(1af518db): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 13:49:20.317  3199  3635 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 13:49:20.317  3199  3199 D PowerUI : closing low battery warning: level=100,
08-24 13:49:20.317  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:49:20.317  1114  1175 D HtcPowerSaver: updateBatteryInfo
08-24 13:49:20.317  3342  3342 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 13:49:20.317  1114  1114 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 13:49:20.317  3342  3342 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 13:49:20.317  1114  1114 D HtcPowerSaver: Checking...
08-24 13:49:20.317  1114  1114 D UsbnetService: BroadcastReceiver::onReceive+
08-24 13:49:20.317  1114  1114 I HtcPowerSaver: >> updateStatus
08-24 13:49:20.317  1114  1114 D UsbnetService: onReceive BATTERY_CHANGED
08-24 13:49:20.317  1114  3076 D WifiController: battery changed pluggedType: 2
,08-24 13:49:20.317  1114  1114 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 13:49:20.327  3199  3199 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 13:49:20.317  1114  1114 D UsbnetService: BroadcastReceiver::onReceive-
08-24 13:49:20.337  1114  1114 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 13:49:20.317  1114  3076 D WifiController: handleMessage: E msg.what=155652
08-24 13:49:20.337  1114  1114 I HtcPowerSaver: << updateStatus
08-24 13:49:20.317  1114  3076 D WifiController: processMsg: DeviceActiveState
08-24 13:49:20.317  1114  3076 D WifiController: processMsg: StaEnabledState
08-24 13:49:20.317  1114  3076 D WifiController: processMsg: DefaultState
08-24 13:49:20.317  1114  3076 D WifiController: handleMessage: X
,08-24 13:49:20.367  3199  3199 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 13:49:20.367  3199  3199 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 13:49:20.367  3199  3199 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 13:49:20.367  3199  3199 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 13:49:20.367  3199  3199 I FlashlightController: batteryLevelChange:100
,TIME-OUT KILL (timeout was 1400000ms)
```
