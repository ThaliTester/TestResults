#### Test 80912877ffdb7be_thali04_HTC-HTC One M9 Logs


```
--------- beginning of main
08-24 10:07:04.847  8740  8913 I HtcModeClient: handler message = 4011
08-24 10:07:04.847  8740  8913 D HtcModeClient: getConnectionCheckCount first 0
08-24 10:07:04.847  8740  8913 D HtcModeClient: getConnectionCheckCount count = 5
08-24 10:07:04.847  8740  8913 E HtcModeClient: Check connection and retry 6 times.
08-24 10:07:04.847  8740  8913 D HtcModeClient: setConnectionCheckCount count = 6
08-24 10:07:04.847  8740  8913 D HtcModeClient: setupRestart delayedTime = 3000
08-24 10:07:04.847  8740  8740 D HtcModeClient: setBtPriority priority = on
08-24 10:07:04.847  8740  8740 D HtcModeClient: unbindBlueToothService
08-24 10:07:04.847  8740  8740 D HtcModeClient: Don't start project servcice
08-24 10:07:04.847  8740  8740 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-24 10:07:04.847  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:04.847  8740  8740 D SilentMusic: call stop
08-24 10:07:04.847  8740  8740 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-24 10:07:04.857  8740  8914 W CANMesgAgentLocalSocket: read the terminate packet, so break
08-24 10:07:04.867  8740  8740 D HtcModeClient: onDestroy
--------- beginning of system
08-24 10:07:04.867  1115  5339 I ActivityManager: Killing 7713:com.google.android.gms.unstable/u0a19 (adj 15): empty #17
08-24 10:07:04.867  1115  5339 D Process : killProcessQuiet, pid=7713
08-24 10:07:04.867  1115  5339 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
08-24 10:07:04.947  1115  3537 I ActivityManager: Recipient 7713
08-24 10:07:05.107  4074  6954 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-24 10:07:05.147  4074  6954 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-24 10:07:05.227  4074  6954 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-24 10:07:05.227  1115  3503 D PMS     : releaseWL(1cea44ea): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-24 10:07:05.237  3533  3937 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-24 10:07:05.237  3533  3937 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@12573217 +
08-24 10:07:05.237  3533  3937 I Prism.WidgetManager: onLoadItems() +
08-24 10:07:05.377  3511  4265 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-24 10:07:05.377  3511  4265 D PhoneApp: -- N1 =0
08-24 10:07:05.377  3511  4265 D PhoneApp: -- N2 =0
08-24 10:07:05.377  3511  4265 D PhoneApp: -- N3 =0
,08-24 10:07:05.567  3533  3937 E Prism.WidgetManager: The same lists. No need to update. skip it.
08-24 10:07:05.567  3533  3937 I Prism.WidgetManager: onLoadItems() -
08-24 10:07:05.567  3533  3937 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@12573217 -
08-24 10:07:05.687  9069  9069 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-24 10:07:05.687  9069  9069 W HTCLOG  : mask=0x18
08-24 10:07:05.727  9041  9073 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-24 10:07:05.727  9041  9073 W HTCLOG  : mask=0x18
08-24 10:07:05.807  9041  9041 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-24 10:07:05.807  1115  5339 D PMS     : acquireWL(23cde353): PARTIAL_WAKE_LOCK  AsyncService 0x1 8707 10128 null
08-24 10:07:05.817  1115  3764 D PMS     : releaseWL(23cde353): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-24 10:07:05.867  9069  9085 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-24 10:07:05.867  9069  9085 W HTCLOG  : mask=0x18
08-24 10:07:05.867  9069  9085 E cutils-trace: Error opening trace file: Permission denied (13)
08-24 10:07:05.917  9069  9069 D CustomizationManager: ====startRecUseTime====
08-24 10:07:05.917  9069  9069 D htc.customization.log.level:  is 
08-24 10:07:05.917  9069  9069 W CustomizationLogLevel: Level value is invalid, use default level 2
08-24 10:07:05.997  9069  9069 D CustomizationManager:  Read ACC file spent 0.038 (s)
08-24 10:07:05.997  9069  9069 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-24 10:07:05.997  9069  9069 I CustomizationCIDLoader: Parsing tag category name = application
08-24 10:07:05.997  9069  9069 I CustomizationCIDLoader: Parsing tag category name = system
08-24 10:07:05.997  9069  9069 I CustomizationCIDLoader: Parsing tag category name = Settings
08-24 10:07:05.997  9069  9069 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-24 10:07:05.997  9069  9069 I CustomizationCIDLoader: Parsing tag category name = ACC
08-24 10:07:06.007  9069  9069 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-24 10:07:06.007  9069  9069 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-24 10:07:06.007  9069  9069 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-24 10:07:06.007  9069  9069 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-24 10:07:06.007  9069  9069 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-24 10:07:06.007  9069  9069 D CustomizationManager:  Read CID file spent 0.087 (s)
08-24 10:07:06.007  9069  9069 D CustomizationManager:  All configurations done spent 0.088 (s)
08-24 10:07:06.047  1115  3764 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 9069 on display 0
08-24 10:07:06.057  1115  1180 D PMS     : acquireHCC(1f1f4490): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1115 1000 null
08-24 10:07:06.057  1115  1180 D PMS     : acquireHCC(1e944189): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1115 1000 null
08-24 10:07:06.067  1115  3764 V WindowManager: addAppToken: AppWindowToken{25dc19bc token=Token{18c961af ActivityRecord{2a0dd58e u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-24 10:07:06.087  1115  3764 I ActivityManager: Start proc 9099:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-24 10:07:06.087  9069  9069 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-24 10:07:06.087  9069  9069 W HTCLOG  : mask=0x18
08-24 10:07:06.087  9069  9098 W HTCLOG  : use specified tag [Vector], func [0].
08-24 10:07:06.087  9069  9097 W HTCLOG  : use specified tag [Vector], func [0].
08-24 10:07:06.087  9069  9097 W HTCLOG  : mask=0x18
08-24 10:07:06.087  9069  9098 W HTCLOG  : mask=0x18
08-24 10:07:06.087  9099  9099 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 10:07:06.087  9099  9099 W HTCLOG  : mask=0x18
08-24 10:07:06.107  1115  1115 V ActivityManager: Display changed displayId=0
08-24 10:07:06.107  3322  3322 D DotMatrix: [EventService]  onDisplayChanged: 0
08-24 10:07:06.107  3322  3322 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-24 10:07:06.117  1115  1143 D ActivityManager: screenshot for ActivityRecord{2a0dd58e u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-24 10:07:06.147  3533  3533 I TrimMemoryManager: [trimMemory] 20
08-24 10:07:06.167  9099  9099 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-24 10:07:06.217  9099  9099 I LibraryLoader: Time to load native libraries: 27 ms (timestamps 4667-4694)
08-24 10:07:06.217  9099  9099 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 10:07:06.227  9099  9099 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {330ffb24}
08-24 10:07:06.227  9099  9099 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 10:07:06.227  9099  9099 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 10:07:06.237  9099  9099 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 10:07:06.237  9099  9099 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 10:07:06.237  9099  9099 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 10:07:06.277  5734  5785 D BluetoothAdapterService(85552822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a0380bb
08-24 10:07:06.287  9099  9099 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-24 10:07:06.287  9099  9099 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
08-24 10:07:06.287  9099  9099 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
08-24 10:07:06.287  9099  9099 W HTCLOG  : use specified tag [libEGL], func [3].
08-24 10:07:06.287  9099  9099 W HTCLOG  : mask=0x18
08-24 10:07:06.297  9099  9099 W HTCLOG  : use specified tag [libEGL], func [3].
08-24 10:07:06.297  9099  9099 W HTCLOG  : mask=0x18
08-24 10:07:06.297  9099  9099 I Adreno  : QUALCOMM build                   : 065751b, 
08-24 10:07:06.297  9099  9099 I Adreno  : Build Date                       : 04/15/15
08-24 10:07:06.297  9099  9099 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-24 10:07:06.297  9099  9099 I Adreno  : Local Branch                     : 
08-24 10:07:06.297  9099  9099 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-24 10:07:06.297  9099  9099 I Adreno  : Remote Branch                    : NONE
08-24 10:07:06.297  9099  9099 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,08-24 10:07:06.357  9099  9132 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,08-24 10:07:06.377  9099  9099 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 10:07:06.387  9099  9099 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 10:07:06.397  9099  9099 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,08-24 10:07:06.397  9099  9099 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 10:07:06.397  9099  9099 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 10:07:06.427  9099  9143 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 10:07:06.427  9099  9143 W HTCLOG  : mask=0x18
,08-24 10:07:06.427  1115  3503 V WindowManager: Adding window Window{19d7e26d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{18ab965 u0 com.htc.launcher/com.htc.launcher.Launcher}),
,08-24 10:07:06.437  1115  3640 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true,
,08-24 10:07:06.457  9099  9099 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,08-24 10:07:06.457  9099  9099 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-24 10:07:06.457  9099  9099 W HTCLOG  : mask=0x18
08-24 10:07:06.457  9099  9099 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 10:07:06.457  9099  9099 W HTCLOG  : mask=0x18
,08-24 10:07:06.467  9099  9143 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 10:07:06.467  9099  9143 W HTCLOG  : mask=0x18
08-24 10:07:06.467  9099  9143 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 10:07:06.467  9099  9143 W HTCLOG  : mask=0x18
,08-24 10:07:06.467  9099  9143 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 10:07:06.467  9099  9143 W HTCLOG  : mask=0x18
08-24 10:07:06.467  9099  9143 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-24 10:07:06.467  9099  9143 W HTCLOG  : mask=0x18
,08-24 10:07:06.477  9099  9143 W HTCLOG  : use specified tag [Surface], func [3].
08-24 10:07:06.477  9099  9143 W HTCLOG  : mask=0x18
08-24 10:07:06.477  9099  9143 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-24 10:07:06.477  9099  9143 W HTCLOG  : mask=0x18
08-24 10:07:06.477  9099  9143 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-24 10:07:06.477  9099  9143 W HTCLOG  : mask=0x18
,08-24 10:07:06.527  1115  1171 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +409ms (total +452ms)
,08-24 10:07:06.557  9099  9099 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9099
,08-24 10:07:06.617  9099  9099 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 10:07:06.667  9099  9146 D jxcore_app_log: JniHelper::setJavaVM(0xaae64b70), pthread_self() = -1411409912
,08-24 10:07:06.667  9099  9146 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 10:07:06.667  9099  9146 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 10:07:06.667  9099  9146 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 10:07:06.667  9099  9146 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 10:07:06.667  9099  9146 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 10:07:06.667  9099  9146 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b234c33 added. We now have 1 listener(s)
,08-24 10:07:06.667  1115  1143 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,08-24 10:07:06.667  9099  9146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
,08-24 10:07:06.667  9099  9146 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-24 10:07:06.667  9099  9146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 10:07:06.677  9099  9146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 10:07:06.677  9099  9146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d57bee added. We now have 1 listener(s)
08-24 10:07:06.677  9099  9146 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 10:07:06.677  1115  3071 D WifiService: New client listening to asynchronous messages
,08-24 10:07:06.677  9099  9146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 10:07:06.677  9099  9146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 10:07:06.677  9099  9146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 10:07:06.677  9099  9146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 10:07:06.677  9099  9146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 10:07:06.677  9099  9146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 10:07:06.677  1115  3390 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-24 10:07:06.687  9099  9146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
,08-24 10:07:06.687  5734  5784 D BluetoothAdapterService(85552822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a0380bb
08-24 10:07:06.687  9099  9146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:07:06.687  9099  9146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 10:07:06.687  9099  9146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 10:07:06.687  9099  9146 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 10:07:06.687  9099  9146 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 10:07:06.687  9099  9099 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 10:07:06.687  9099  9099 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 10:07:06.737  9099  9099 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 10:07:07.027  3511  3737 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-24 10:07:07.027  3511  3737 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,08-24 10:07:07.057  1115  1180 D PMS     : releaseHCC(1f1f4490): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,08-24 10:07:07.057  1115  1180 D PMS     : releaseHCC(1e944189): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-24 10:07:07.067  9099  9152 W jxcore-log: Initializing JXcore engine
08-24 10:07:07.067  9099  9152 W jxcore-log: JXcore engine is ready
,08-24 10:07:07.127  9099  9152 W jxcore-log: Starting JXcore engine
,08-24 10:07:07.227  9099  9152 W jxcore-log: Platform android
08-24 10:07:07.227  9099  9152 W jxcore-log: 
08-24 10:07:07.227  9099  9152 W jxcore-log: Process ARCH arm
08-24 10:07:07.227  9099  9152 W jxcore-log: 
,08-24 10:07:07.407  9099  9152 I jxcore-log: JXcore Cordova bridge is ready!
08-24 10:07:07.407  9099  9152 I jxcore-log: 
08-24 10:07:07.407  9099  9152 W jxcore-log: JXcore engine is started
08-24 10:07:07.417  9099  9146 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 10:07:07.417  9099  9099 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 10:07:07.747  1115  1143 D PMS     : acquireWL(3a2eb1c6): PARTIAL_WAKE_LOCK  Icing 0x1 4074 10019 null,
,08-24 10:07:07.777  1115  3505 D PMS     : releaseWL(3a2eb1c6): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,08-24 10:07:07.787  1115  3764 D PMS     : acquireWL(224340dd): PARTIAL_WAKE_LOCK  Icing 0x1 4074 10019 null
,08-24 10:07:07.837  1115  1143 D PMS     : releaseWL(224340dd): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,08-24 10:07:07.847  1115  3028 D PMS     : acquireWL(35380dd9): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{10027},
08-24 10:07:07.847  1115  3028 V AlarmManager: sending alarm PendingIntent{bec339e: PendingIntentRecord{1676128d com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=86321, Int=0
08-24 10:07:07.847  1115  3028 V AlarmManager: sending alarm PendingIntent{15804e7f: PendingIntentRecord{34c64e4c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=82163, Int=0
,08-24 10:07:07.847  8740  8740 D AlarmReceiver: ACTION_RESTART_INTENT
,08-24 10:07:07.847  8740  8740 D LocalBluetoothProfile: getPriorityOnValue = 100,
08-24 10:07:07.857  1115  1115 D PMS     : releaseWL(35380dd9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-24 10:07:07.847  8740  8740 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 10:07:07.847  8740  8740 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 10:07:07.847  8740  8740 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 10:07:07.877  8740  9163 D HtcModeClient: start the htcmodeservice thread
,08-24 10:07:07.877  8740  9163 D HtcModeClient: initCanAgent
08-24 10:07:07.877  8740  9163 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 10:07:07.877  8740  9163 D HtcModeClient: sense info: version = none, id = 2
08-24 10:07:07.877  8740  8740 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-24 10:07:07.877  8740  9163 D HtcModeClient: display info: width = 1080, height = 1776
08-24 10:07:07.877  8740  9163 D HtcModeClient: display info: mode = 10
08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: BT_TURNON_BYME = false
,08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
,08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = false
,08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: Force_AWAKE = false
08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 10:07:07.877  8740  8740 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 10:07:09.307   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 10:07:09.757  9041  9041 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-24 10:07:09.887  8740  9163 I HtcModeClient: handler message = 4011,
,08-24 10:07:09.897  8740  9163 D HtcModeClient: getConnectionCheckCount first 0
08-24 10:07:09.897  8740  9163 D HtcModeClient: getConnectionCheckCount count = 6
,08-24 10:07:09.897  8740  9163 E HtcModeClient: Check connection and retry 7 times.
,08-24 10:07:09.897  8740  9163 D HtcModeClient: setConnectionCheckCount count = 7
,08-24 10:07:09.897  8740  9163 D HtcModeClient: setupRestart delayedTime = 3000,
,08-24 10:07:09.907  8740  8740 D HtcModeClient: setBtPriority priority = on,
08-24 10:07:09.907  8740  8740 D HtcModeClient: unbindBlueToothService
08-24 10:07:09.907  8740  8740 D HtcModeClient: Don't start project servcice
08-24 10:07:09.907  8740  8740 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 10:07:09.907  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:09.907  8740  8740 D SilentMusic: call stop
08-24 10:07:09.907  8740  8740 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-24 10:07:09.907  8740  9164 W CANMesgAgentLocalSocket: read the terminate packet, so break
08-24 10:07:09.907  8740  8740 D HtcModeClient: onDestroy,
,08-24 10:07:09.907  1115  3390 D Process : killProcessQuiet, pid=7738
,08-24 10:07:09.907  1115  3390 I ActivityManager: Killing 7738:com.google.android.music:main/u0a115 (adj 15): empty #17
08-24 10:07:09.907  1115  3390 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 10:07:09.967  1115  3503 I ActivityManager: Recipient 7738
,08-24 10:07:09.967  1115  3764 D MediaRouterService: Client com.google.android.music (pid 7738): Died!
,08-24 10:07:10.717  9041  9072 I GAV2    : Thread[GAThread,5,main]: No campaign data found.,
,08-24 10:07:14.907  1115  3028 D PMS     : acquireWL(2b740150): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{10027},
08-24 10:07:14.907  1115  3028 V AlarmManager: sending alarm PendingIntent{2cab1f49: PendingIntentRecord{1676128d com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=91378, Int=0
,08-24 10:07:14.907  8740  8740 D AlarmReceiver: ACTION_RESTART_INTENT,
,08-24 10:07:14.917  8740  8740 D LocalBluetoothProfile: getPriorityOnValue = 100,
08-24 10:07:14.917  1115  1115 D PMS     : releaseWL(2b740150): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-24 10:07:14.917  8740  8740 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 10:07:14.917  8740  8740 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 10:07:14.917  8740  8740 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1),
,08-24 10:07:14.937  8740  9169 D HtcModeClient: start the htcmodeservice thread,
08-24 10:07:14.937  8740  9169 D HtcModeClient: initCanAgent
08-24 10:07:14.947  8740  9169 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-24 10:07:14.947  8740  9169 D HtcModeClient: sense info: version = none, id = 2
08-24 10:07:14.947  8740  9169 D HtcModeClient: display info: width = 1080, height = 1776
08-24 10:07:14.947  8740  9169 D HtcModeClient: display info: mode = 10
,08-24 10:07:15.047  8740  8740 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: Force_AWAKE = false
,08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 10:07:15.047  8740  8740 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 10:07:15.537  1115  1115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,08-24 10:07:16.697  1115  3764 D PMS     : releaseWL(3a126fc6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,08-24 10:07:17.057  8740  9169 I HtcModeClient: handler message = 4011
08-24 10:07:17.057  8740  9169 D HtcModeClient: getConnectionCheckCount first 0
08-24 10:07:17.057  8740  9169 D HtcModeClient: getConnectionCheckCount count = 7
08-24 10:07:17.057  8740  9169 E HtcModeClient: Check connection and retry 8 times.,
08-24 10:07:17.057  8740  9169 D HtcModeClient: setConnectionCheckCount count = 8
08-24 10:07:17.057  8740  9169 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 10:07:17.067  8740  8740 D HtcModeClient: setBtPriority priority = on
08-24 10:07:17.067  8740  8740 D HtcModeClient: unbindBlueToothService
08-24 10:07:17.067  8740  8740 D HtcModeClient: Don't start project servcice
,08-24 10:07:17.067  8740  8740 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-24 10:07:17.067  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:17.067  8740  8740 D SilentMusic: call stop
08-24 10:07:17.067  8740  8740 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode,
08-24 10:07:17.067  8740  9170 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-24 10:07:17.067  8740  8740 D HtcModeClient: onDestroy
,08-24 10:07:18.497  1115  1163 I ActivityManager: Waited long enough for: ServiceRecord{2fa7d6f7 u0 com.google.android.gms/.wearable.service.WearableService},
,08-24 10:07:19.457  1115  3545 D PMS     : acquireWL(f2a8b26): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null,
08-24 10:07:19.467  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false),
08-24 10:07:19.457  1115  3545 I BatteryService: n_update end,
,08-24 10:07:19.467  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:07:19.467  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1,
08-24 10:07:19.467  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:07:19.467  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:07:19.467  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
08-24 10:07:19.467  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:07:19.467  1115  3545 D PMS     : releaseWL(f2a8b26): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:07:19.467  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED,
08-24 10:07:19.467  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:07:19.467  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:07:19.467  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false),
08-24 10:07:19.467  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-,
08-24 10:07:19.467  1115  1115 D HtcPowerSaver: Checking...
08-24 10:07:19.467  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:07:19.467  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:07:19.467  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:07:19.467  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:07:19.467  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:07:19.467  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:07:19.467  1115  3071 D WifiController: handleMessage: X
,08-24 10:07:19.477  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:07:19.477  1115  1115 I HtcPowerSaver: << updateStatus
,08-24 10:07:19.517  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 10:07:19.517  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:07:19.517  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:07:19.517  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 10:07:19.517  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:07:19.937  9099  9152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-24 10:07:19.937  9099  9152 I jxcore-log: 
,08-24 10:07:19.937  9099  9152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-24 10:07:19.937  9099  9152 I jxcore-log: 
,08-24 10:07:19.947  5734  5785 D BluetoothAdapterService(85552822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a0380bb,
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:07:19.947  9099  9152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 10:07:19.947  5734  5785 D BluetoothAdapterService(85552822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a0380bb
08-24 10:07:19.947  9099  9152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-24 10:07:19.947  9099  9152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-24 10:07:19.947  9099  9152 I jxcore-log: 
,08-24 10:07:19.957  9099  9152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-24 10:07:19.957  9099  9152 I jxcore-log: 
,08-24 10:07:20.607  9099  9152 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests,
08-24 10:07:20.607  9099  9152 I jxcore-log: Failed to execute UT.
08-24 10:07:20.607  9099  9152 I jxcore-log: 
,08-24 10:07:20.607  9099  9152 I jxcore-log: Unit Test app is loaded
08-24 10:07:20.607  9099  9152 I jxcore-log: 
,08-24 10:07:20.617  9099  9152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-24 10:07:20.617  9099  9152 I jxcore-log: 
08-24 10:07:20.627  9099  9099 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 10:07:20.627  9099  9152 I jxcore-log: My device name is: HTC-HTC One M9
08-24 10:07:20.627  9099  9152 I jxcore-log: 
,08-24 10:07:20.627  9099  9152 I jxcore-log: WARN testUtils: myNameCallback not set!
08-24 10:07:20.627  9099  9152 I jxcore-log: ,
,08-24 10:07:22.057  1115  3028 D PMS     : acquireWL(30e70367): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{10019},
08-24 10:07:22.057  1115  3028 V AlarmManager: sending alarm PendingIntent{3e100514: PendingIntentRecord{fd671bd com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1472026032928, Int=1800000
,08-24 10:07:22.077  1115  3028 V AlarmManager: sending alarm PendingIntent{6d66f03: PendingIntentRecord{1e725e80 com.android.vending startService}}, i=null, t=0, cnt=1, w=1472026038595, Int=0,
08-24 10:07:22.087  1115  3545 D PMS     : acquireWL(267d6cb9): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4074 10019 null
,08-24 10:07:22.097  1115  3028 I ActivityManager: Start proc 9173:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService,
,08-24 10:07:22.097  1115  3028 V AlarmManager: sending alarm PendingIntent{2a9dd8fe: PendingIntentRecord{fc6f85f com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472026040774, Int=60000,
08-24 10:07:22.097  1115  3028 V AlarmManager: sending alarm PendingIntent{27ff1b75: PendingIntentRecord{1676128d com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=98536, Int=0
08-24 10:07:22.107  8740  8740 D AlarmReceiver: ACTION_RESTART_INTENT
08-24 10:07:22.107  8740  8740 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 10:07:22.107  1115  3505 D PMS     : acquireWL(337a870a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4074 10019 null,
08-24 10:07:22.107  8740  8740 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 10:07:22.107  1115  1141 D PMS     : releaseWL(267d6cb9): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,08-24 10:07:22.107  8740  8740 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 10:07:22.107  1115  1115 D PMS     : releaseWL(30e70367): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-24 10:07:22.107  9173  9173 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 10:07:22.107  9173  9173 W HTCLOG  : mask=0x18
08-24 10:07:22.107  8740  8740 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 10:07:22.147  9173  9196 D SMSBackup: SMSBackupAgentService started
08-24 10:07:22.147  9173  9196 D SMSBackup: Checking restore status
,08-24 10:07:22.147  8740  9197 D HtcModeClient: start the htcmodeservice thread
08-24 10:07:22.147  8740  9197 D HtcModeClient: initCanAgent
,08-24 10:07:22.147  8740  9197 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-24 10:07:22.147  8740  9197 D HtcModeClient: sense info: version = none, id = 2
08-24 10:07:22.147  8740  9197 D HtcModeClient: display info: width = 1080, height = 1776
08-24 10:07:22.147  9173  9196 D SMSBackup: Restore complete
08-24 10:07:22.147  9173  9196 D SMSBackup: cancelCheckAlarm
,08-24 10:07:22.147  8740  9197 D HtcModeClient: display info: mode = 10
,08-24 10:07:22.157  8740  8740 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-24 10:07:22.157  9173  9196 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: Force_AWAKE = false
,08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 10:07:22.157  8740  8740 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 10:07:22.167  4074  9186 I EventLogService: Aggregate from 1472025990083 (log), 1472024232884 (data)
,08-24 10:07:22.207  1115  3742 D PMS     : releaseWL(337a870a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,08-24 10:07:22.337  8634  8634 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,08-24 10:07:24.167  8740  9197 I HtcModeClient: handler message = 4011
08-24 10:07:24.167  8740  9197 D HtcModeClient: getConnectionCheckCount first 0
08-24 10:07:24.167  8740  9197 D HtcModeClient: getConnectionCheckCount count = 8
08-24 10:07:24.167  8740  9197 E HtcModeClient: Check connection and retry 9 times.
08-24 10:07:24.167  8740  9197 D HtcModeClient: setConnectionCheckCount count = 9
08-24 10:07:24.167  8740  9197 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 10:07:24.177  8740  8740 D HtcModeClient: setBtPriority priority = on
,08-24 10:07:24.177  8740  8740 D HtcModeClient: unbindBlueToothService
08-24 10:07:24.177  8740  8740 D HtcModeClient: Don't start project servcice
,08-24 10:07:24.177  8740  8740 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 10:07:24.177  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
,08-24 10:07:24.177  8740  8740 D SilentMusic: call stop
08-24 10:07:24.177  8740  8740 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-24 10:07:24.177  8740  9198 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-24 10:07:24.187  8740  8740 D HtcModeClient: onDestroy,
,08-24 10:07:24.187  1115  3742 D Process : killProcessQuiet, pid=8492,
08-24 10:07:24.187  1115  3742 I ActivityManager: Killing 8492:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-24 10:07:24.187  1115  3742 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 10:07:24.357  1115  5339 I ActivityManager: Recipient 8492
,08-24 10:07:25.887  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 10:07:25.887  9099  9152 I jxcore-log: 
,08-24 10:07:27.037  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-24 10:07:27.037  9099  9152 I jxcore-log: 
,08-24 10:07:27.067  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
08-24 10:07:27.067  9099  9152 I jxcore-log: 
,08-24 10:07:27.077  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
08-24 10:07:27.077  9099  9152 I jxcore-log: 
,08-24 10:07:27.097  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 10:07:27.097  9099  9152 I jxcore-log: 
,08-24 10:07:27.107  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 10:07:27.107  9099  9152 I jxcore-log: 
,08-24 10:07:29.177  1115  3028 D PMS     : acquireWL(3cc4b74f): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{10027}
08-24 10:07:29.177  8740  8740 D AlarmReceiver: ACTION_RESTART_INTENT,
08-24 10:07:29.177  1115  3028 V AlarmManager: sending alarm PendingIntent{25b64edc: PendingIntentRecord{1676128d com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=105647, Int=0
08-24 10:07:29.187  1115  1115 D PMS     : releaseWL(3cc4b74f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-24 10:07:29.187  8740  8740 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 10:07:29.187  8740  8740 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 10:07:29.187  8740  8740 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 10:07:29.187  8740  8740 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 10:07:29.207  8740  9201 D HtcModeClient: start the htcmodeservice thread
08-24 10:07:29.207  8740  9201 D HtcModeClient: initCanAgent
,08-24 10:07:29.207  8740  9201 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 10:07:29.217  8740  9201 D HtcModeClient: sense info: version = none, id = 2
,08-24 10:07:29.217  8740  9201 D HtcModeClient: display info: width = 1080, height = 1776
08-24 10:07:29.217  8740  9201 D HtcModeClient: display info: mode = 10
,08-24 10:07:29.317  8740  8740 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: BT_TURNON_BYME = false
,08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: Force_AWAKE = false
08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 10:07:29.317  8740  8740 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 10:07:31.247  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
08-24 10:07:31.247  9099  9152 I jxcore-log: 
,08-24 10:07:31.257  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
08-24 10:07:31.257  9099  9152 I jxcore-log: 
,08-24 10:07:31.277  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
08-24 10:07:31.277  9099  9152 I jxcore-log: 
,08-24 10:07:31.327  8740  9201 I HtcModeClient: handler message = 4011,
08-24 10:07:31.327  8740  9201 D HtcModeClient: getConnectionCheckCount first 0
08-24 10:07:31.327  8740  9201 D HtcModeClient: getConnectionCheckCount count = 9
08-24 10:07:31.327  8740  9201 E HtcModeClient: Check connection and retry 10 times.
08-24 10:07:31.327  8740  9201 D HtcModeClient: setConnectionCheckCount count = 10
08-24 10:07:31.327  8740  9201 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 10:07:31.337  8740  8740 D HtcModeClient: setBtPriority priority = on
,08-24 10:07:31.337  8740  8740 D HtcModeClient: unbindBlueToothService
08-24 10:07:31.337  8740  8740 D HtcModeClient: Don't start project servcice
,08-24 10:07:31.337  8740  8740 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 10:07:31.337  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:31.337  8740  8740 D SilentMusic: call stop,
08-24 10:07:31.337  8740  8740 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-24 10:07:31.337  8740  9202 W CANMesgAgentLocalSocket: read the terminate packet, so break
08-24 10:07:31.337  8740  8740 D HtcModeClient: onDestroy
,08-24 10:07:31.487  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
08-24 10:07:31.487  9099  9152 I jxcore-log: 
,08-24 10:07:32.507  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
08-24 10:07:32.507  9099  9152 I jxcore-log: 
,08-24 10:07:32.867  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
08-24 10:07:32.867  9099  9152 I jxcore-log: 
,08-24 10:07:32.877  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
08-24 10:07:32.877  9099  9152 I jxcore-log: 
,08-24 10:07:33.127  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
08-24 10:07:33.127  9099  9152 I jxcore-log: 
,08-24 10:07:33.157  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
08-24 10:07:33.157  9099  9152 I jxcore-log: 
,08-24 10:07:33.167  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 10:07:33.167  9099  9152 I jxcore-log: ,
,08-24 10:07:33.177  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 10:07:33.177  9099  9152 I jxcore-log: 
,08-24 10:07:33.197  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 10:07:33.197  9099  9152 I jxcore-log: 
,08-24 10:07:33.217  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 10:07:33.217  9099  9152 I jxcore-log: 
,08-24 10:07:33.307  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
08-24 10:07:33.307  9099  9152 I jxcore-log: 
,08-24 10:07:33.317  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,08-24 10:07:33.317  9099  9152 I jxcore-log: 
,08-24 10:07:33.357  9099  9152 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 10:07:33.357  9099  9152 I jxcore-log: 
,08-24 10:07:33.367  5734  5785 D BluetoothAdapterService(85552822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a0380bb
,08-24 10:07:33.367  9099  9152 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-24 10:07:33.377  9099  9152 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 10:07:33.377  9099  9152 I jxcore-log: 
,08-24 10:07:36.327  1115  3028 D PMS     : acquireWL(2f13929d): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{10027}
,08-24 10:07:36.347  8740  8740 D AlarmReceiver: ACTION_RESTART_INTENT
08-24 10:07:36.347  1115  3028 V AlarmManager: sending alarm PendingIntent{46f7312: PendingIntentRecord{1676128d com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=112807, Int=0
08-24 10:07:36.397  8740  8740 D LocalBluetoothProfile: getPriorityOnValue = 100
08-24 10:07:36.397  1115  1115 D PMS     : releaseWL(2f13929d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-24 10:07:36.397  8740  8740 D LocalBluetoothProfile: getPriorityOffValue = 0
08-24 10:07:36.397  8740  8740 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-24 10:07:36.397  8740  8740 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 10:07:36.427  8740  9204 D HtcModeClient: start the htcmodeservice thread,
08-24 10:07:36.427  8740  9204 D HtcModeClient: initCanAgent
,08-24 10:07:36.427  8740  9204 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 10:07:36.427  8740  9204 D HtcModeClient: sense info: version = none, id = 2
,08-24 10:07:36.447  8740  9204 D HtcModeClient: display info: width = 1080, height = 1776
,08-24 10:07:36.447  8740  9204 D HtcModeClient: display info: mode = 10
,08-24 10:07:36.527  8740  8740 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = false
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: Force_AWAKE = false
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 10:07:36.527  8740  8740 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 10:07:37.027  3511  3737 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
08-24 10:07:37.027  3511  3737 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,08-24 10:07:38.537  8740  9204 I HtcModeClient: handler message = 4011,
,08-24 10:07:38.557  8740  9204 D HtcModeClient: getConnectionCheckCount first 0
08-24 10:07:38.557  8740  9204 D HtcModeClient: getConnectionCheckCount count = 10
08-24 10:07:38.557  8740  9204 E HtcModeClient: Check connection and retry 11 times.
,08-24 10:07:38.557  8740  9204 D HtcModeClient: setConnectionCheckCount count = 11,
08-24 10:07:38.557  8740  9204 D HtcModeClient: setupRestart delayedTime = 3000
,08-24 10:07:38.567  8740  8740 D HtcModeClient: setBtPriority priority = on
08-24 10:07:38.567  8740  8740 D HtcModeClient: unbindBlueToothService
08-24 10:07:38.567  8740  8740 D HtcModeClient: Don't start project servcice
08-24 10:07:38.567  8740  8740 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 10:07:38.567  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:38.567  8740  8740 D SilentMusic: call stop
08-24 10:07:38.567  8740  8740 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-24 10:07:38.567  8740  9205 W CANMesgAgentLocalSocket: read the terminate packet, so break,
,08-24 10:07:38.577  8740  8740 D HtcModeClient: onDestroy
,08-24 10:07:43.567  1115  3028 D PMS     : acquireWL(1e55935b): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{1000},
08-24 10:07:43.567  1115  1115 D PMS     : acquireWL(10b7a7f8): PARTIAL_WAKE_LOCK  *backup* 0x1 1115 1000 null,
08-24 10:07:43.577  1115  3028 V AlarmManager: sending alarm PendingIntent{353044d1: PendingIntentRecord{252b2b36 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472026060117, Int=0,
,08-24 10:07:43.587  1115  3028 V AlarmManager: sending alarm PendingIntent{1c500a37: PendingIntentRecord{1676128d com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=120040, Int=0
08-24 10:07:43.597  8740  8740 D AlarmReceiver: ACTION_RESTART_INTENT
,08-24 10:07:43.607  1115  1115 D PMS     : releaseWL(1e55935b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027},
,08-24 10:07:43.617  8740  8740 D LocalBluetoothProfile: getPriorityOnValue = 100,
08-24 10:07:43.617  8740  8740 D LocalBluetoothProfile: getPriorityOffValue = 0
,08-24 10:07:43.617  8740  8740 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,08-24 10:07:43.617  8740  8740 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-24 10:07:43.637  1115  3122 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
08-24 10:07:43.637  1115  3122 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
08-24 10:07:43.637  1115  3122 D PMS     : releaseWL(10b7a7f8): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,08-24 10:07:43.657  8740  9207 D HtcModeClient: start the htcmodeservice thread,
08-24 10:07:43.657  8740  9207 D HtcModeClient: initCanAgent
08-24 10:07:43.657  8740  9207 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-24 10:07:43.657  8740  9207 D HtcModeClient: sense info: version = none, id = 2
08-24 10:07:43.657  8740  9207 D HtcModeClient: display info: width = 1080, height = 1776
08-24 10:07:43.657  8740  9207 D HtcModeClient: display info: mode = 10
,08-24 10:07:43.657  8740  8740 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false
08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
,08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = false
,08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: Force_AWAKE = false
08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: PHONE_PULGIN = true
08-24 10:07:43.667  8740  8740 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-24 10:07:44.317   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 10:07:45.667  8740  9207 I HtcModeClient: handler message = 4011,
08-24 10:07:45.667  8740  9207 D HtcModeClient: getConnectionCheckCount first 0,
08-24 10:07:45.667  8740  9207 D HtcModeClient: getConnectionCheckCount count = 11,
08-24 10:07:45.677  8740  9207 E HtcModeClient: Check connection and retry 12 times. Time out!,
,08-24 10:07:45.687  8740  9207 D HtcModeClient: setConnectionCheckCount count = 0,
08-24 10:07:45.687  8740  9207 D HtcModeClient: cancelRestart
,08-24 10:07:45.697  8740  8740 D HtcModeClient: setBtPriority priority = on,
08-24 10:07:45.707  8740  8740 D HtcModeClient: unbindBlueToothService,
,08-24 10:07:45.707  8740  8740 D HtcModeClient: Don't start project servcice
08-24 10:07:45.717  8740  8740 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-24 10:07:45.717  8740  8740 D HtcModeClient: connectState: CONNECTION_READY = false,
08-24 10:07:45.717  8740  8740 D SilentMusic: call stop
,08-24 10:07:45.717  8740  8740 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-24 10:07:45.717  8740  9208 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-24 10:07:45.727  8740  8740 D HtcModeClient: onDestroy,
,08-24 10:07:54.317   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 10:08:03.357  1115  3079 D PMS     : releaseWL(19274b0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,08-24 10:08:04.117  1115  1162 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA,
,08-24 10:08:04.127  1115  1162 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,08-24 10:08:04.127  1115  1162 D PMS     : acquireWL(2ba6b3c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 1115 1000 null,
,08-24 10:08:04.147  1115  4820 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
08-24 10:08:04.147  1115  4820 D libc    : [NET] android_getaddrinfofornet-, err=8
08-24 10:08:04.147  1115  4820 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
08-24 10:08:04.147  1115  4820 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-24 10:08:04.147  1115  4820 D libc    : [NET] android_getaddrinfo_proxy+
08-24 10:08:04.147  1115  4820 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
08-24 10:08:04.157   514  9209 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
08-24 10:08:04.157   514  9209 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,08-24 10:08:04.207   514  9209 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
08-24 10:08:04.207   514  9209 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
08-24 10:08:04.207  1115  4820 D libc    : [NET] android_getaddrinfo_proxy-, success,
08-24 10:08:04.217  1115  4820 D libc    : [NET] android_getaddrinfofornet+,hn 14(0x35342e3234302e),sn(),hints(known),family 0,flags 4
08-24 10:08:04.217  1115  4820 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,08-24 10:08:04.307  1115  4820 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data,
,08-24 10:08:04.687  1115  3439 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0,
08-24 10:08:04.687  1115  3439 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0
08-24 10:08:04.687  1115  4820 D PMS     : acquireWL(17de094b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 1115 1000 null
,08-24 10:08:04.687  1115  4820 D GpsLocationProvider:  [handleDownloadXtraData]inject done.
08-24 10:08:04.697  1115  4820 D PMS     : releaseWL(2ba6b3c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,08-24 10:08:04.707  1115  1162 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,08-24 10:08:04.707  1115  1162 D PMS     : releaseWL(17de094b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,08-24 10:08:09.327   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 10:08:15.537  1115  1115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,08-24 10:08:27.437  7833  7833 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@19f39e8e for type 1
08-24 10:08:27.437  7833  7833 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@19f39e8e for type 0
,08-24 10:08:27.467  1115  3504 D Process : killProcessQuiet, pid=7833,
08-24 10:08:27.467  1115  3504 I ActivityManager: Killing 7833:com.htc.music:musicenhancer/u0a24 (adj 15): empty #17
08-24 10:08:27.477  1115  3504 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 10:08:27.567  1115  3079 I ActivityManager: Recipient 7833
,08-24 10:08:29.337   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-24 10:08:31.777  3511  3511 D TelephonyReceiver: switchBindHtcMsgCursor: null
,08-24 10:08:39.117  1115  3028 D PMS     : acquireWL(b60ff28): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1115 1000 WorkSource{1000},
08-24 10:08:39.117  1115  3028 V AlarmManager: sending alarm PendingIntent{37acb5b9: PendingIntentRecord{19fdedfe android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=138465, Int=0
08-24 10:08:39.147  1115  3028 I ActivityManager: Start proc 9212:com.htc.sense.mms/u0a51 for service com.htc.sense.mms/.transaction.TransactionService
,08-24 10:08:39.147  1115  3028 V AlarmManager: sending alarm PendingIntent{26fb0441: PendingIntentRecord{1f72cde6 com.htc.sense.mms startService}}, i=android.intent.action.ACTION_ONALARM, t=0, cnt=1, w=1472026119126, Int=0
,08-24 10:08:39.187  1115  1115 D PMS     : releaseWL(b60ff28): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-24 10:08:39.197  9212  9212 W HTCLOG  : use specified tag [FDManager], func [0].,
08-24 10:08:39.197  9212  9212 W HTCLOG  : mask=0x18
,08-24 10:08:39.207   546   546 I art     : Explicit concurrent mark sweep GC freed 8657(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 201us total 20.262ms
,08-24 10:08:39.227   546   546 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 301us total 17.065ms
,08-24 10:08:39.247   546   546 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 198us total 14.240ms
,08-24 10:08:39.247  9212  9212 D MessageFrequencyProvider: onCreate,
,08-24 10:08:39.257  9212  9212 D MessageCustFlag: sense_version=7.0,
,08-24 10:08:39.257  9212  9212 V GetPrviateResource: GetPrviateResource
,08-24 10:08:39.257  9212  9212 V GetPrviateResource: GetPrviateResource
,08-24 10:08:39.257  9212  9212 D RcsChatUtils: isSup> false,
,08-24 10:08:39.267  9212  9212 D n       : createReceiver,
,08-24 10:08:39.267  9212  9212 D n       : registerReceiver return intent = null
,08-24 10:08:39.287  9212  9212 W HTCLOG  : use specified tag [asset], func [0].,
08-24 10:08:39.287  9212  9212 W HTCLOG  : mask=0x18
08-24 10:08:39.287  9212  9212 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
08-24 10:08:39.287  9212  9212 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
,08-24 10:08:39.287  9212  9212 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@38058abc for type 0,
08-24 10:08:39.287  9212  9212 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@38058abc for type 1
,08-24 10:08:39.287  9212  9212 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@38058abc for type 5
,08-24 10:08:39.287  9212  9212 V TransactionService: 1-Creating TransactionService,
,08-24 10:08:39.297  9212  9212 V TransactionService: onStartCommand: 1,
08-24 10:08:39.297  9212  9212 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
08-24 10:08:39.297  9212  9236 V TransactionService: 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.au }
08-24 10:08:39.297  9212  9236 V TransactionService: Loading previous transactions.
,08-24 10:08:39.317  3511  4303 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102,
,08-24 10:08:39.327  9212  9236 D TransactionService: Force clearing mTransactionList,
,08-24 10:08:39.327  9212  9236 D TransactionService: Force set service start id to 1
08-24 10:08:39.327  9212  9236 V TransactionService: stopSelfIfIdle
08-24 10:08:39.327  9212  9236 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
,08-24 10:08:39.327  1115  5339 I ActivityManager: Killing 8301:com.google.android.gm/u0a97 (adj 15): empty #17
08-24 10:08:39.327  9212  9212 V TransactionService: Destroying TransactionService
08-24 10:08:39.327  1115  5339 D Process : killProcessQuiet, pid=8301
08-24 10:08:39.327  1115  5339 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 10:08:39.387  1115  3504 I ActivityManager: Recipient 8301,
,08-24 10:08:39.427  1115  5173 I art     : Explicit concurrent mark sweep GC freed 23656(1335KB) AllocSpace objects, 4(96KB) LOS objects, 33% free, 16MB/24MB, paused 2.459ms total 147.615ms
,08-24 10:08:39.437  9212  9236 V TransactionService: 4-Handling incoming message: { when=-111ms what=100 target=com.htc.sense.mms.transaction.au }
,08-24 10:08:39.447  9212  9236 V Scheduler: Scheduler safely quits looper.
,08-24 10:08:41.317  9212  9212 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist
,08-24 10:08:41.317  9212  9212 D MessageCustFlag: sku_id=58
,08-24 10:08:41.327  9212  9212 D ReportIndicatorCache: startAsyncQueryReports --- , first = true,
,08-24 10:08:41.327  9212  9235 D ReportIndicatorCache: MSG_QUERY_REPORTS >>,
,08-24 10:08:41.337  3511  3535 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65,
08-24 10:08:41.337  3511  3535 D MmsSmsV2Provider:  slotId = -1
08-24 10:08:41.337  3511  3535 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null
,08-24 10:08:41.357  9212  9212 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2e3a590
08-24 10:08:41.357  3511  4219 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 88
,08-24 10:08:41.367  9212  9239 D Messaging: mNeedToUpdateDate2 start,
08-24 10:08:41.367  9212  9234 D MmsAsyncWorkHandler: 
08-24 10:08:41.367  9212  9234 D MmsAsyncWorkHandler: HM tk = 20002
,08-24 10:08:41.367  3511  3971 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78,
08-24 10:08:41.367  3511  3971 D MmsSmsV2Provider:  slotId = -1
08-24 10:08:41.367  3511  3971 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,08-24 10:08:41.377  9212  9212 D DraftCache: [DraftCache/1] DraftCache.constructor
08-24 10:08:41.377  9212  9212 D DraftCache: [DraftCache/1] refresh
,08-24 10:08:41.377  9212  9242 D MmsConfig: Start to get Carrier ID
,08-24 10:08:41.377  3511  4219 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 88
08-24 10:08:41.377  3511  4219 D MmsSmsV2Provider:  slotId = -1
08-24 10:08:41.377  3511  4219 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,08-24 10:08:41.387  9212  9241 I Messaging: mccmnc> ,
,08-24 10:08:41.387  3511  3535 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,08-24 10:08:41.387  9212  9212 D MmsConfig: networkCode: 
08-24 10:08:41.387  3511  4219 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 88
08-24 10:08:41.387  3511  4219 D MmsSmsV2Provider:  slotId = -1
08-24 10:08:41.387  3511  4219 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,08-24 10:08:41.397  3511  3535 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
08-24 10:08:41.397  3511  3535 D MmsSmsV2Provider:  slotId = -1
08-24 10:08:41.397  3511  3535 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,08-24 10:08:41.397  9212  9240 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,08-24 10:08:41.397  3511  4303 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
,08-24 10:08:41.397  9212  9245 D Messaging: ViewCache CreatePreloadOnlyConversationList
08-24 10:08:41.397  9212  9239 D Messaging: mNeedToUpdateDate2: false
,08-24 10:08:41.407  9212  9212 D HfmClient: getIHFMServiceHMSApiLevel: +++
08-24 10:08:41.407  3511  3511 D IccSmsInterfaceManager: [IccSmsInterfaceManager] Cannot get carrier id
,08-24 10:08:41.407  9212  9242 D MmsConfig: Carrier ID is NULL
,08-24 10:08:41.407  9212  9212 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
08-24 10:08:41.407  9212  9212 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak
08-24 10:08:41.407  9212  9245 D MessageCustFlag: sense_version=7.0
,08-24 10:08:41.407  9212  9212 D HfmClient: getIHFMServiceHMSApiLevel: Level = 1
08-24 10:08:41.407  9212  9212 D HfmClient: HfmServiceHMS API Level = 1
,08-24 10:08:41.407  9212  9245 D Jerry   : start to preload cursor >>>>>>>
,08-24 10:08:41.417  3511  3532 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
08-24 10:08:41.417  3511  3532 D MmsSmsV2Provider:  slotId = -1
,08-24 10:08:41.417  9212  9212 D ew      : createReceiver,
,08-24 10:08:41.417  9212  9250 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files,
08-24 10:08:41.417  1115  1141 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-24 10:08:41.427  9212  9250 D ew      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0,
08-24 10:08:41.427  9212  9234 D DraftCache: [DraftCache/207] rebuildCache
,08-24 10:08:41.427  9212  9245 D Messaging: ViewCache CreatePreload,
08-24 10:08:41.427  9212  9245 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
08-24 10:08:41.427  1115  3505 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
08-24 10:08:41.427  9212  9250 D ew      : /storage/emulated/0 : mounted
08-24 10:08:41.427  3511  4303 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
08-24 10:08:41.427  3511  4303 D Jerry   : URI_DRAFT
08-24 10:08:41.427  9212  9250 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,08-24 10:08:41.427  9212  9212 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
,08-24 10:08:41.427  9212  9212 W SystemReader: Cannot find support_cw, use default value instead
08-24 10:08:41.427  9212  9212 W SystemReader: Cannot find qct_8960_interface, use default value instead
08-24 10:08:41.427  9212  9234 D DraftCache: hasDraft() = false mNeedNotifyChange = true
08-24 10:08:41.427  9212  9234 D DraftCache: [DraftCache/207] rebuildCache time: 1
,08-24 10:08:41.437  3511  3971 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 78,
08-24 10:08:41.437  3511  3971 V MmsProvider: Update uri=content://mms, match=0
08-24 10:08:41.437  3511  3971 V MmsProvider: selection=st=129 AND m_type!=134
,08-24 10:08:41.437  9212  9251 D Messaging: Reset downloading state: 0
,08-24 10:08:41.437  9212  9245 D Cust_MMSMS: _has_set_default_values_2=true
,08-24 10:08:41.437  9212  9251 V Messaging: Start TransactionService after 2 minutes from now
,08-24 10:08:41.447  9212  9245 D TextSizeManager: [get_list_body_TextSize]__size57
,08-24 10:08:41.447  9212  9245 D TextSizeManager: [get_list_body_TextSize]__size48
08-24 10:08:41.447  9212  9245 D TextSizeManager: [get_list_body_TextSize]__size0
08-24 10:08:41.447  9212  9245 D TextSizeManager: [get_list_body_TextSize]__size57
08-24 10:08:41.447  9212  9245 D TextSizeManager: [get_list_body_TextSize]__size66
08-24 10:08:41.447  9212  9245 D TextSizeManager: [get_list_body_TextSize]__size74
08-24 10:08:41.447  9212  9245 D TextSizeManager: [get_list_body_TextSize]__size83,
08-24 10:08:41.447  9212  9245 D MsgPreferenceUtils: def_index: 0
,08-24 10:08:41.447  9212  9245 D MsgPreferenceUtils: globalIndex = 2
,08-24 10:08:41.447  1115  1141 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-24 10:08:41.447  9212  9245 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,08-24 10:08:41.447  1115  3390 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-24 10:08:41.447  9212  9245 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,08-24 10:08:41.457  9212  9245 D MsgPreferenceUtils: phone state: true,
08-24 10:08:41.457  9212  9245 D MsgPreferenceUtils: sd state: false
08-24 10:08:41.457  9212  9245 D MsgPreferenceUtils: vIndex = 1
,08-24 10:08:41.467  9212  9266 D RcsWorkingHandler: handler msg:{ when=0 what=1 target=com.htc.sense.mms.rcschat.bo }
08-24 10:08:41.467  9212  9266 D RcsWorkingHandler: not support Rcs, return
,08-24 10:08:41.467  9212  9245 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=
,08-24 10:08:41.467  9212  9245 D PersonalizeUtils: isHTCThemeChange_full isChange= false
08-24 10:08:41.477  9212  9245 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
,08-24 10:08:41.477  9212  9245 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
08-24 10:08:41.477  9212  9245 D PersonalizeUtils: isHTCThemeChange_CC equal time= 1466486566,old=1466486566
08-24 10:08:41.477  9212  9245 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
,08-24 10:08:54.337   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 10:09:06.177  1115  3028 D PMS     : acquireWL(2da565a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{1000},
08-24 10:09:06.177  1115  3028 V AlarmManager: sending alarm PendingIntent{1702bd7a: PendingIntentRecord{2842092b android broadcastIntent}}, i=android.content.jobscheduler.JOB_DEADLINE_EXPIRED, t=3, cnt=1, w=168311, Int=0
08-24 10:09:06.187  1115  3028 V AlarmManager: sending alarm PendingIntent{37acb5b9: PendingIntentRecord{19fdedfe android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=198465, Int=0
08-24 10:09:06.187  1115  3028 V AlarmManager: sending alarm PendingIntent{52b3188: PendingIntentRecord{33abb721 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=204652, Int=0
08-24 10:09:06.237  1115  1115 D PMS     : acquireWL(1fd781d2): PARTIAL_WAKE_LOCK  *job*/com.google.android.gms/.gcm.nts.TaskExecutionService 0x1 1115 1000 WorkSource{10019}
,08-24 10:09:06.237  1115  1115 D PMS     : releaseWL(2da565a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-24 10:09:06.247  1115  1115 D PMS     : releaseWL(1fd781d2): PARTIAL_WAKE_LOCK  *job*/com.google.android.gms/.gcm.nts.TaskExecutionService 0x1 WorkSource{10019}
08-24 10:09:06.247  1115  3079 D PMS     : acquireWL(32bc72a3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 null
,08-24 10:09:06.257  1115  3503 D PMS     : acquireWL(123ca9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 WorkSource{10019 com.google.android.gms}
,08-24 10:09:06.267  1115  3545 D PMS     : releaseWL(123ca9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10019 com.google.android.gms}
,08-24 10:09:06.287  1115  3390 D PMS     : acquireWL(2407e91e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 WorkSource{10019 com.google.android.gms}
,08-24 10:09:06.297  1115  3504 D PMS     : releaseWL(32bc72a3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 10:09:06.297  1115  3079 D PMS     : acquireWL(3740215): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 null
,08-24 10:09:06.297  1115  3537 D PMS     : releaseWL(3740215): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 10:09:06.307  3687  9268 I VacuumService: Vacuum at: now=1472026146317 tag=VacuumService
,08-24 10:09:06.307  1115  3742 D PMS     : acquireWL(2fb931b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 null
,08-24 10:09:06.307  1115  3505 D PMS     : releaseWL(2fb931b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
,08-24 10:09:06.337  1115  3390 D PMS     : releaseWL(2407e91e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10019 com.google.android.gms}
,08-24 10:09:06.337  1115  3764 D PMS     : acquireWL(1719fdf6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 null
,08-24 10:09:06.357  1115  1141 D PMS     : releaseWL(1719fdf6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
08-24 10:09:06.357  1115  3079 D PMS     : acquireWL(11f73c64): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 null
,08-24 10:09:06.357  1115  3764 D PMS     : releaseWL(11f73c64): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
08-24 10:09:06.357  1115  3505 D PMS     : acquireWL(14035ecd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3687 10019 null,
,08-24 10:09:06.367  1115  1141 D PMS     : releaseWL(14035ecd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-24 10:09:08.277  1115  1143 D PMS     : acquireWL(25741ac9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:09:08.287  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
,08-24 10:09:08.277  1115  1143 I BatteryService: n_update end
08-24 10:09:08.287  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:09:08.287  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:09:08.287  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:09:08.287  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:09:08.287  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:09:08.287  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:09:08.297  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:09:08.287  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:09:08.297  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:09:08.287  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:09:08.297  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:09:08.287  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:09:08.307  1115  1115 D HtcPowerSaver: Checking...
08-24 10:09:08.297  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:09:08.307  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:09:08.297  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:09:08.307  1115  1143 D PMS     : releaseWL(25741ac9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:09:08.297  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:09:08.317  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:09:08.297  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:09:08.317  1115  1115 I HtcPowerSaver: << updateStatus
08-24 10:09:08.297  1115  3071 D WifiController: handleMessage: X
,08-24 10:09:08.337  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 10:09:08.337  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:09:08.337  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:09:08.337  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 10:09:08.337  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:09:08.777  3196  4764 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,08-24 10:09:08.797  3659  3659 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@335f93ac,
,08-24 10:09:08.807  1115  3545 D Process : killProcessQuiet, pid=8378
08-24 10:09:08.807  1115  3545 I ActivityManager: Killing 8378:com.google.android.talk/u0a103 (adj 15): empty #17
08-24 10:09:08.807  1115  3545 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 10:09:08.837  3196  4764 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
,08-24 10:09:08.907  1115  1141 I ActivityManager: Recipient 8378,
,08-24 10:09:11.537  3511  3737 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
08-24 10:09:11.537  3511  3737 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<,
,08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 1 BSSID 84:b2:61:1a:ce:7b SSID '\x00' due to wpa_bss_flush_by_age,
08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 4 BSSID 84:b2:61:1a:ce:7f SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00,
08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 9 BSSID 84:b2:61:0f:9c:3a SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 13 BSSID 84:b2:61:1a:ce:76 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00,
08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 21 BSSID 84:b2:61:0f:9c:30 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 28 BSSID e4:aa:5d:fc:5b:f6 SSID '\x00' due to wpa_bss_flush_by_age
,08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 39 BSSID 84:b2:61:1c:62:d1 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:14.187  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 41 BSSID e4:aa:5d:fc:5b:f3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
,08-24 10:09:14.187  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 23 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 2 BSSID 84:b2:61:1a:ce:79 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 3 BSSID 84:b2:61:1a:ce:7a SSID '\x00' due to wpa_bss_flush_by_age
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 5 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 6 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 8 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 42 BSSID 84:b2:61:1a:ce:75 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 16 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 14 BSSID 84:b2:61:1a:ce:72 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 15 BSSID 84:b2:61:1a:ce:74 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 43 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP' due to wpa_bss_flush_by_age
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 12 BSSID 84:b2:61:0f:9c:39 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 11 BSSID 84:b2:61:0f:9c:3b SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 10 BSSID 84:b2:61:0f:9c:3f SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 44 BSSID 84:b2:61:1c:62:d2 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 45 BSSID 84:b2:61:0f:9c:32 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 46 BSSID 84:b2:61:12:64:95 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 47 BSSID 84:b2:61:12:64:94 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 26 BSSID 84:b2:61:1c:62:d0 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 48 BSSID 84:b2:61:12:64:90 SSID '\x00' due to wpa_bss_flush_by_age
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 22 BSSID 84:b2:61:12:64:96 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 49 BSSID 84:b2:61:21:47:59 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 19 BSSID 84:b2:61:0f:9c:35 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 18 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 25 BSSID 84:b2:61:1c:62:d4 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 17 BSSID 84:b2:61:12:64:92 SSID '\x00' due to wpa_bss_flush_by_age
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 50 BSSID 84:b2:61:0f:9c:36 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 51 BSSID 84:b2:61:1c:62:da SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 7 BSSID 00:fe:c8:73:02:04 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 52 BSSID 84:b2:61:1c:62:d5 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 20 BSSID 84:b2:61:0f:9c:34 SSID '\x00' due to wpa_bss_flush_by_age
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 53 BSSID 84:b2:61:12:64:99 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 54 BSSID 84:b2:61:1c:62:db SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 24 BSSID 00:fe:c8:73:02:00 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 27 BSSID 00:fe:c8:73:02:05 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 55 BSSID 84:b2:61:12:64:9b SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 56 BSSID 84:b2:61:12:64:9f SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 57 BSSID 00:fe:c8:73:02:06 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 58 BSSID 00:fe:c8:73:02:02 SSID '\x00' due to wpa_bss_flush_by_age
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 29 BSSID 84:b2:61:1a:ce:7e SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 31 BSSID 84:b2:61:1a:ce:71 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 30 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 32 BSSID 84:b2:61:0f:9c:3e SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 34 BSSID 84:b2:61:12:64:91 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 36 BSSID 84:b2:61:12:64:93 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 35 BSSID 84:b2:61:0f:9c:33 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 59 BSSID 84:b2:61:21:47:5e SSID '\x00' due to wpa_bss_flush_by_age
,08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 60 BSSID 84:b2:61:1c:62:de SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 33 BSSID 84:b2:61:0f:9c:31 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 38 BSSID 00:fe:c8:73:02:03 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 37 BSSID 84:b2:61:1c:62:d3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
08-24 10:09:24.197  3153  3153 D wpa_supplicant: wlan0: BSS: Remove ID 40 BSSID 00:fe:c8:73:02:01 SSID '\x00' due to wpa_bss_flush_by_age
08-24 10:09:24.197  3153  3153 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1115-2\x00
,08-24 10:09:34.347   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 10:09:44.357   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 10:09:59.357   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-24 10:10:08.417  1115  3503 D PMS     : acquireWL(130ed5ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null,
,08-24 10:10:08.417  1115  3503 I BatteryService: n_update end
08-24 10:10:08.417  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:10:08.417  1115  3503 D PMS     : releaseWL(130ed5ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:10:08.417  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:10:08.427  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:10:08.427  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:10:08.427  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:10:08.427  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:10:08.427  1115  1115 D HtcPowerSaver: Checking...
08-24 10:10:08.427  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:10:08.427  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:10:08.427  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:10:08.427  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:10:08.427  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:10:08.427  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:10:08.427  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:10:08.427  1115  3071 D WifiController: handleMessage: X
08-24 10:10:08.427  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:10:08.427  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:10:08.427  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:10:08.427  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-24 10:10:08.427  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:10:08.427  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:10:08.427  1115  1115 I HtcPowerSaver: << updateStatus
,08-24 10:10:08.477  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 10:10:08.477  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:10:08.477  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:10:08.477  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 10:10:08.477  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:10:19.367   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-24 10:10:41.437  1115  3028 D PMS     : acquireWL(dc9fcef): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1115 1000 WorkSource{1000},
08-24 10:10:41.447  1115  3028 V AlarmManager: sending alarm PendingIntent{37acb5b9: PendingIntentRecord{19fdedfe android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=258465, Int=0
08-24 10:10:41.457  9212  9212 V TransactionService: 1-Creating TransactionService
08-24 10:10:41.467  1115  3028 V AlarmManager: sending alarm PendingIntent{2b1a9a85: PendingIntentRecord{3d4680da com.htc.sense.mms startService}}, i=android.intent.action.ACTION_ONALARM, t=0, cnt=1, w=1472026241450, Int=0
08-24 10:10:41.507  1115  1115 D PMS     : releaseWL(dc9fcef): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
08-24 10:10:41.517  9212  9212 V TransactionService: onStartCommand: 1
08-24 10:10:41.517  9212  9212 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
08-24 10:10:41.517  9212  9269 V TransactionService: 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.au }
08-24 10:10:41.517  9212  9269 V TransactionService: Loading previous transactions.
,08-24 10:10:41.527  3511  4219 D TelephUtils: DELETE for  <hidden uri>  [ com.htc.sense.mms ] tid: 88
08-24 10:10:41.527  3511  4219 V MmsProvider: Delete uri=content://mms/9223372036854775807/part, match=11
08-24 10:10:41.527  3511  4219 V MmsProvider: selection=null
,08-24 10:10:41.527  3511  4303 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
,08-24 10:10:41.537  9212  9269 D TransactionService: Force clearing mTransactionList
,08-24 10:10:41.537  9212  9269 D TransactionService: Force set service start id to 1
08-24 10:10:41.537  9212  9269 V TransactionService: stopSelfIfIdle
08-24 10:10:41.537  9212  9269 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
,08-24 10:10:41.537  9212  9212 V TransactionService: Destroying TransactionService
,08-24 10:10:41.547  9212  9269 V TransactionService: 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.au }
08-24 10:10:41.547  9212  9269 V Scheduler: Scheduler safely quits looper.
,08-24 10:10:44.377   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 10:11:06.387  1115  3028 D PMS     : acquireWL(14e3790b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1115 1000 WorkSource{1000},
08-24 10:11:06.387  1115  3028 V AlarmManager: sending alarm PendingIntent{37acb5b9: PendingIntentRecord{19fdedfe android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=318465, Int=0
08-24 10:11:06.397  1115  3028 V AlarmManager: sending alarm PendingIntent{52b3188: PendingIntentRecord{33abb721 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=324860, Int=0
08-24 10:11:06.447  1115  1115 D PMS     : releaseWL(14e3790b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-24 10:11:29.387   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 10:11:39.387   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 10:11:54.397   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 10:12:08.757  1115  5339 D PMS     : acquireWL(1d3e13e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null,
08-24 10:12:08.757  1115  5339 I BatteryService: n_update end
08-24 10:12:08.757  1115  5339 D PMS     : releaseWL(1d3e13e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:12:08.757  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
,08-24 10:12:08.757  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:12:08.767  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:12:08.767  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:12:08.767  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:12:08.767  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:12:08.767  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:12:08.767  1115  1115 D HtcPowerSaver: Checking...
08-24 10:12:08.767  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:12:08.767  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:12:08.767  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:12:08.777  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:12:08.767  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:12:08.777  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:12:08.767  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:12:08.787  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:12:08.777  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:12:08.787  1115  1115 I HtcPowerSaver: << updateStatus
08-24 10:12:08.777  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:12:08.777  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:12:08.777  1115  3071 D WifiController: processMsg: DefaultState
,08-24 10:12:08.777  1115  3071 D WifiController: handleMessage: X
,08-24 10:12:08.817  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 10:12:08.817  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:12:08.817  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:12:08.817  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 10:12:08.817  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:12:14.407   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-24 10:12:39.407   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-24 10:13:29.417   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 10:13:39.427   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 10:13:54.427   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 10:14:09.057  1115  3742 D PMS     : acquireWL(2aef5a01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:14:09.057  1115  3742 I BatteryService: n_update end
08-24 10:14:09.057  1115  3742 D PMS     : releaseWL(2aef5a01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:14:09.067  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:14:09.067  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:14:09.067  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:14:09.067  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:14:09.067  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:14:09.067  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:14:09.067  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:14:09.067  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:14:09.067  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:14:09.067  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:14:09.067  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:14:09.067  1115  3071 D WifiController: handleMessage: X
08-24 10:14:09.067  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:14:09.067  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:14:09.067  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:14:09.067  1115  1115 D HtcPowerSaver: Checking...
08-24 10:14:09.067  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:14:09.067  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:14:09.067  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-24 10:14:09.067  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
08-24 10:14:09.077  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:14:09.077  1115  1115 I HtcPowerSaver: << updateStatus
,08-24 10:14:09.117  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 10:14:09.117  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:14:09.117  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:14:09.117  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 10:14:09.117  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:14:14.437   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-24 10:14:39.447   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-24 10:15:29.447   565   565 W HTCLOG  : use specified tag [QC-QMI], func [18].,
08-24 10:15:29.447   565   565 W HTCLOG  : mask=0x18
,08-24 10:15:46.997   504   527 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,08-24 10:16:06.827  3511  3737 D ContactMessageStore: MSG_CHECK_DELETION >>,
08-24 10:16:06.837  3511  3737 D ContactMessageStore: mDeleteTask = null, bDeleting = false
,08-24 10:16:06.837  3511  3737 D AccFlag : sku_id=58,
08-24 10:16:06.837  3511  3737 D ContactMessageStore: MSG_CHECK_DELETION <<
,08-24 10:16:06.847  3511  9289 D ContactMessageStore: start background delete task...,
,08-24 10:16:06.857  3511  9289 D ContactMessageStore: size: 0 , 0,
08-24 10:16:06.857  3511  9289 D ContactMessageStore: Background delete complete
,08-24 10:17:09.557  1115  1141 D PMS     : acquireWL(131bd0a6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:17:09.567  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:17:09.557  1115  1141 I BatteryService: n_update end
08-24 10:17:09.567  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:17:09.557  1115  1141 D PMS     : releaseWL(131bd0a6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:17:09.567  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:17:09.567  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:17:09.567  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:17:09.577  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:17:09.577  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:17:09.577  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:17:09.577  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:17:09.577  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:17:09.577  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:17:09.577  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:17:09.577  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:17:09.577  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:17:09.577  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:17:09.577  1115  3071 D WifiController: handleMessage: X
,08-24 10:17:09.577  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,08-24 10:17:09.577  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:17:09.577  1115  1115 D HtcPowerSaver: Checking...
08-24 10:17:09.587  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:17:09.587  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:17:09.587  1115  1115 I HtcPowerSaver: << updateStatus
,08-24 10:17:09.617  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 10:17:09.617  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:17:09.617  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:17:09.617  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 10:17:09.627  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:17:10.737  1115  3545 D Process : killProcessQuiet, pid=8772,
08-24 10:17:10.737  1115  3545 I ActivityManager: Killing 8772:com.htc.sense.news/u0a56 (adj 15): empty #17
08-24 10:17:10.737  1115  3545 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 10:17:10.807  1115  3504 I ActivityManager: Recipient 8772,
,08-24 10:19:09.877  1115  5339 D PMS     : acquireWL(22ce9ae7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:19:09.877  1115  5339 I BatteryService: n_update end
08-24 10:19:09.877  1115  5339 D PMS     : releaseWL(22ce9ae7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-24 10:19:09.887  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:19:09.887  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:19:09.887  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:19:09.887  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:19:09.887  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:19:09.887  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:19:09.887  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:19:09.887  1115  1115 D HtcPowerSaver: Checking...
,08-24 10:19:09.887  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:19:09.887  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:19:09.887  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:19:09.897  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:19:09.887  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:19:09.897  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:19:09.887  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:19:09.907  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:19:09.897  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:19:09.907  1115  1115 I HtcPowerSaver: << updateStatus
08-24 10:19:09.897  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:19:09.897  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:19:09.897  1115  3071 D WifiController: processMsg: DefaultState,
08-24 10:19:09.897  1115  3071 D WifiController: handleMessage: X
,08-24 10:19:09.937  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 10:19:09.937  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:19:09.937  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:19:09.937  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 10:19:09.937  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:20:10.037  1115  1143 D PMS     : acquireWL(3ad48694): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:20:10.047  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:20:10.037  1115  1143 I BatteryService: n_update end
08-24 10:20:10.047  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,08-24 10:20:10.037  1115  1143 D PMS     : releaseWL(3ad48694): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:20:10.047  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:20:10.047  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:20:10.047  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:20:10.057  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:20:10.057  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:20:10.057  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:20:10.057  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:20:10.057  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:20:10.057  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:20:10.057  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:20:10.067  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:20:10.057  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:20:10.067  1115  1115 D HtcPowerSaver: Checking...
08-24 10:20:10.057  1115  3071 D WifiController: processMsg: DeviceActiveState
,08-24 10:20:10.067  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:20:10.057  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:20:10.077  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:20:10.057  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:20:10.077  1115  1115 I HtcPowerSaver: << updateStatus
08-24 10:20:10.057  1115  3071 D WifiController: handleMessage: X
,08-24 10:20:10.097  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 10:20:10.097  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:20:10.097  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:20:10.097  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 10:20:10.107  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:21:25.027  1115  3028 D PMS     : acquireWL(37f6953d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1115 1000 WorkSource{1000}
08-24 10:21:25.027  1115  3028 V AlarmManager: sending alarm PendingIntent{37acb5b9: PendingIntentRecord{19fdedfe android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=378465, Int=0
08-24 10:21:25.027  1115  3028 V AlarmManager: sending alarm PendingIntent{1fa45132: PendingIntentRecord{85ffe83 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=943499, Int=0
,08-24 10:21:25.037  5734  5734 D BluetoothAdapterService(85552822): handleMessage() - Message: 110,
08-24 10:21:25.037  1115  3742 D PMS     : acquireWL(2cbd7800): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5734 1002 null
08-24 10:21:25.037  5734  5734 D BluetoothAdapterService(85552822): handleMessage() - MESSAGE_RELEASE_WAKE_ALARM
08-24 10:21:25.037  5734  5877 I bt-btm  : Received oneshot timer event complete
,08-24 10:21:25.037  5734  5877 I bt-btm  : btm_ble_timeout
08-24 10:21:25.037  5734  5877 I bt-btm  : btm_gen_resolvable_private_addr
08-24 10:21:25.037  5734  5877 I bt-hci  : 10:21:25.050 --
08-24 10:21:25.037  5734  5877 I bt-hci  : 10:21:25.050 SENT Command to HCI. Name: HCI_LE_Rand  (Hex Code: 0x2018  Param Len: 0) Ctrl(0)
08-24 10:21:25.037  5734  5877 I bt-hci  : 10:21:25.050 --
,08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064 --
08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064 RCVD Event from HCI. Name: HCI_Command_Complete  (Hex Code: 0x0e  Param Len: 12) Ctrl(0)
08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064 Parameters
08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064                      Num HCI Cmd Packets : 1 (0x01)
08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064                                 Cmd Code : 0x2018  (HCI_LE_Rand)
08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064                                   Status : Success (0x00)
08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064                            Random Number : 8a c7 88 75 4b a9 b4 8f 
08-24 10:21:25.047  5734  5879 I bt-hci  : 10:21:25.064 --
08-24 10:21:25.047  5734  5877 D bt-btm  : btm_ble_rand_enc_complete
,08-24 10:21:25.047  5734  5877 I bt-btm  : btm_gen_resolve_paddr_low
08-24 10:21:25.047  5734  5877 D bt-smp  : smp_encrypt_data
08-24 10:21:25.047  5734  5877 D bt-smp  : Key(LSB ~ MSB) = 2b d8 9e 69 23 5b 6a 34 c8 5f a4 fb f9 34 ec 0c 
08-24 10:21:25.047  5734  5877 D bt-smp  : Plain text(LSB ~ MSB) = 8a c7 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 10:21:25.047  5734  5877 D bt-smp  : Encrypted text(LSB ~ MSB) = e2 58 13 c1 ef fd 68 9e 2e 75 11 98 6f ae 0f ca 
08-24 10:21:25.047  5734  5877 I bt-btm  : btm_gen_resolve_paddr_cmpl
08-24 10:21:25.047  5734  5877 I bt-hci  : 10:21:25.064 --
08-24 10:21:25.047  5734  5877 I bt-hci  : 10:21:25.064 SENT Command to HCI. Name: HCI_LE_Write_random_Address  (Hex Code: 0x2005  Param Len: 6) Ctrl(0)
08-24 10:21:25.047  5734  5877 I bt-hci  : 10:21:25.064 Parameters 
08-24 10:21:25.047  5734  5877 I bt-hci  : 10:21:25.064                           Random BD Addr : 48-c7-8a-13-58-e2
08-24 10:21:25.047  5734  5877 I bt-hci  : 10:21:25.064 --
08-24 10:21:25.047  5734  5877 W bt-btm  : Stopping oneshot timer
08-24 10:21:25.047  5734  5877 D bt-btm  : Starting oneshot timer type:103 timeout:900s
08-24 10:21:25.057  5734  5879 I bt-hci  : 10:21:25.065 --
08-24 10:21:25.057  5734  5879 I bt-hci  : 10:21:25.065 RCVD Event from HCI. Name: HCI_Command_Complete  (Hex Code: 0x0e  Param Len: 4) Ctrl(0)
,08-24 10:21:25.057  5734  5879 I bt-hci  : 10:21:25.065 Parameters
08-24 10:21:25.057  5734  5879 I bt-hci  : 10:21:25.065                      Num HCI Cmd Packets : 1 (0x01)
08-24 10:21:25.057  5734  5879 I bt-hci  : 10:21:25.065                                 Cmd Code : 0x2005  (HCI_LE_Write_random_Address)
08-24 10:21:25.057  5734  5879 I bt-hci  : 10:21:25.065                                   Status : Success (0x00)
08-24 10:21:25.057  5734  5879 I bt-hci  : 10:21:25.065 --
,08-24 10:21:25.057  1115  1115 D PMS     : releaseWL(37f6953d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,08-24 10:21:26.037  5734  5734 D BluetoothAdapterService(85552822): handleMessage() - Message: 100,
08-24 10:21:26.037  5734  5734 D BluetoothAdapterService(85552822): handleMessage() - MESSAGE_SET_WAKE_ALARM
08-24 10:21:26.037  1115  3504 D PMS     : releaseWL(2cbd7800): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,08-24 10:21:30.287  1115  3028 D PMS     : acquireWL(173c4839): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{1000},
08-24 10:21:30.297  1115  3028 V AlarmManager: sending alarm PendingIntent{17c24e7e: PendingIntentRecord{519ffdf com.htc.htcpowermanager broadcastIntent}}, i=com.htc.intent.action.HTCPOWERMGR_SMARTSYNC_SCREEN_OFF_TIME, t=0, cnt=1, w=1472026890300, Int=0,
08-24 10:21:30.337  1115  1163 I ActivityManager: Start proc 9302:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver
,08-24 10:21:30.367  9302  9302 W HTCLOG  : use specified tag [FDManager], func [0].
08-24 10:21:30.367  9302  9302 W HTCLOG  : mask=0x18
,08-24 10:21:30.407  1115  1115 D PMS     : releaseWL(173c4839): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-24 10:21:30.407  1115  3079 D PMS     : acquireWL(1d82142c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 9302 1000 null
08-24 10:21:30.407  1115  3505 I ActivityManager: Killing 8829:com.htc.sense.socialplugins/u0a17 (adj 15): empty #17
08-24 10:21:30.407  1115  3505 D Process : killProcessQuiet, pid=8829
08-24 10:21:30.407  1115  3505 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processNextBroadcast:707 
,08-24 10:21:30.417  9302  9324 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-24 10:21:30.417  9302  9324 W HTCLOG  : mask=0x18
,08-24 10:21:30.427  1115  3764 D PMS     : releaseWL(1d82142c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,08-24 10:21:30.427  1115  5339 D PMS     : acquireWL(38902ef5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 9302 1000 null
,08-24 10:21:30.427  9302  9325 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false
08-24 10:21:30.427  9302  9325 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,08-24 10:21:30.437  9302  9325 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1
,08-24 10:21:30.437  9302  9325 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1472101200000, randomSettingOnTime = 1472099127000
08-24 10:21:30.437  9302  9325 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1472079600000, randomSettingOffTime = 1472083737000
08-24 10:21:30.437  9302  9325 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false
,08-24 10:21:30.437  9302  9325 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true
08-24 10:21:30.437  9302  9325 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false
,08-24 10:21:30.517  1115  3764 I ActivityManager: Recipient 8829,
,08-24 10:21:30.547  1115  3537 D PMS     : releaseWL(38902ef5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,08-24 10:21:38.237  1115  3028 D PMS     : acquireWL(a30d48a): PARTIAL_WAKE_LOCK  *alarm* 0x1 1115 1000 WorkSource{10019},
08-24 10:21:38.247  1115  3028 V AlarmManager: sending alarm PendingIntent{2448bafb: PendingIntentRecord{35124718 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=956712, Int=0
08-24 10:21:38.257  1115  3390 D PMS     : acquireWL(44faf56): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 3687 10019 null,
08-24 10:21:38.267  1115  3028 V AlarmManager: sending alarm PendingIntent{fde0bd7: PendingIntentRecord{2870bcc4 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=767387, Int=1800000
08-24 10:21:38.267  1115  3028 V AlarmManager: sending alarm PendingIntent{15804e7f: PendingIntentRecord{34c64e4c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806333, Int=0
,08-24 10:21:38.267  1115  3028 V AlarmManager: sending alarm PendingIntent{151c47ad: PendingIntentRecord{ac16377 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1472026895702, Int=0
,08-24 10:21:38.287  1115  3505 D PMS     : releaseWL(44faf56): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null,
,08-24 10:21:38.307  9302  9302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,08-24 10:21:38.307  1115  1115 D PMS     : releaseWL(a30d48a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,08-24 10:21:38.307  9302  9328 D PowerUtils: getUserIdOfProcess, curUserId = 0
,08-24 10:21:38.317  9302  9328 D PowerUtils: isRunningUnderOwner, isOwner = true
,08-24 10:21:38.317  8803  9327 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4,
08-24 10:21:38.317  8803  9327 D libc    : [NET] android_getaddrinfofornet-, err=8
08-24 10:21:38.317  9302  9328 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,08-24 10:21:38.317  8803  9327 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
08-24 10:21:38.317  8803  9327 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,08-24 10:21:38.317  8803  9327 D libc    : [NET] android_getaddrinfo_proxy+
,08-24 10:21:38.317  8803  9327 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-24 10:21:38.317   514  9330 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
08-24 10:21:38.317   514  9330 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,08-24 10:21:38.327  9302  9328 D PowerUsageService: repeat time = 1472027798334
,08-24 10:21:38.367   514  9330 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
08-24 10:21:38.367   514  9330 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-24 10:21:38.377  8803  9327 D libc    : [NET] android_getaddrinfo_proxy-, success
,08-24 10:21:38.377  1115  5339 D PMS     : acquireWL(350d8e73): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 3687 10019 null
,08-24 10:21:38.387  3687  8546 D GCM     : Message class com.google.e.a.a.h,
,08-24 10:21:38.387  1115  3505 D PMS     : releaseWL(350d8e73): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,08-24 10:21:38.417  8803  9327 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4
08-24 10:21:38.417  8803  9327 D libc    : [NET] android_getaddrinfofornet-, err=8
,08-24 10:21:38.447  9302  9328 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8
,08-24 10:21:38.467  9302  9328 D PowerUtils: getUserIdOfProcess, curUserId = 0,
,08-24 10:21:38.487  9302  9328 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,08-24 10:21:38.487  9302  9328 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-24 10:21:38.487  9302  9328 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-24 10:21:38.507  9302  9328 D PowerUsageService: calcPower(), no data
,08-24 10:23:10.507  1115  3390 D PMS     : acquireWL(181ee130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null,
08-24 10:23:10.527  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:23:10.517  1115  3390 I BatteryService: n_update end
08-24 10:23:10.527  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:23:10.527  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:23:10.527  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:23:10.527  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:23:10.537  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:23:10.537  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:23:10.537  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:23:10.537  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:23:10.537  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:23:10.537  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,08-24 10:23:10.547  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:23:10.537  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:23:10.547  1115  1115 D HtcPowerSaver: Checking...
08-24 10:23:10.537  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:23:10.547  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:23:10.537  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:23:10.547  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:23:10.537  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:23:10.547  1115  1115 I HtcPowerSaver: << updateStatus
08-24 10:23:10.537  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:23:10.547  1115  3390 D PMS     : releaseWL(181ee130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:23:10.537  1115  3071 D WifiController: handleMessage: X
,08-24 10:23:10.577  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 10:23:10.577  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:23:10.577  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:23:10.577  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 10:23:10.587  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:24:10.677  1115  5339 D PMS     : acquireWL(8e2b1a9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:24:10.687  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:24:10.677  1115  5339 I BatteryService: n_update end
08-24 10:24:10.687  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:24:10.677  1115  5339 D PMS     : releaseWL(8e2b1a9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:24:10.687  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:24:10.687  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:24:10.687  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:24:10.697  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:24:10.697  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:24:10.697  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:24:10.697  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:24:10.697  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:24:10.697  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:24:10.697  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:24:10.697  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:24:10.697  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:24:10.697  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:24:10.697  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:24:10.697  1115  3071 D WifiController: handleMessage: X
,08-24 10:24:10.697  1115  1176 D HtcPowerSaver: updateBatteryInfo
,08-24 10:24:10.697  1115  1115 D HtcPowerSaver: Checking...
08-24 10:24:10.697  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:24:10.707  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:24:10.707  1115  1115 I HtcPowerSaver: << updateStatus
,08-24 10:24:10.737  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 10:24:10.737  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:24:10.737  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false),
08-24 10:24:10.737  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 10:24:10.747  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:25:46.997   504   527 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,08-24 10:26:01.587  1115  1162 I UsageStatsService: User[0] Flushing usage stats to disk,
,08-24 10:28:45.397  1115  3545 D PMS     : acquireWL(2c5d532e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:28:45.407  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:28:45.397  1115  3545 I BatteryService: n_update end
08-24 10:28:45.407  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:28:45.397  1115  3545 D PMS     : releaseWL(2c5d532e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:28:45.407  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:28:45.417  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:28:45.417  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:28:45.417  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:28:45.417  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:28:45.417  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:28:45.417  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:28:45.417  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:28:45.427  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:28:45.417  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:28:45.417  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:28:45.417  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:28:45.417  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:28:45.417  1115  3071 D WifiController: handleMessage: X
08-24 10:28:45.417  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
,08-24 10:28:45.437  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:28:45.437  1115  1115 D HtcPowerSaver: Checking...
08-24 10:28:45.437  1115  1115 I HtcPowerSaver: >> updateStatus
,08-24 10:28:45.447  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:28:45.447  1115  1115 I HtcPowerSaver: << updateStatus
,08-24 10:28:45.447  1115  1163 I ActivityManager: Start proc 9346:com.android.settings/1000 for broadcast com.android.settings/.framework.app.HtcSystemReceiver
,08-24 10:28:45.457  9346  9346 W HTCLOG  : use specified tag [FDManager], func [0].,
08-24 10:28:45.457  9346  9346 W HTCLOG  : mask=0x18
,08-24 10:28:45.467  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-24 10:28:45.467  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:28:45.467  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:28:45.467  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-24 10:28:45.467  3196  3196 I FlashlightController: batteryLevelChange:100
,08-24 10:28:45.517  9346  9346 V Settings:HtcSettingsApplication: [9346/9346] onCreate(),
,08-24 10:28:45.527  9346  9346 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.framework.app.HtcSystemReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:2719 
,08-24 10:28:45.537  9346  9367 D SmartNS_NSReceiver: plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
08-24 10:28:45.537  9346  9367 D SmartNS_NSReceiver: Index of the first 1 = 3
,08-24 10:28:45.537  9346  9367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1836 android.content.ContextWrapper.stopService:521 com.android.settings.NSReceiver.onReceive:182 android.support.v4.content.g.a:297 android.support.v4.content.g.b:278 
,08-24 10:28:45.547  9346  9367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 android.content.ContextWrapper.sendBroadcast:377 com.android.settings.NSReceiver.onReceive:184 android.support.v4.content.g.a:297 android.support.v4.content.g.b:278 ,
,08-24 10:28:45.547  9346  9367 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 10:28:45.557  9346  9367 I SmartNS_Utility: hasRemovableStorageSlot: true,
08-24 10:28:45.557  9346  9367 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
08-24 10:28:45.557  9346  9367 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,08-24 10:28:45.557  9346  9367 D SmartNS_Utility: [ACC]android_networking:tethering_guard_support=false,
08-24 10:28:45.557  9346  9367 W SystemReader: Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
08-24 10:28:45.567  1115  3504 I ActivityManager: Killing 7667:com.htc.mediamanager/u0a23 (adj 15): empty #17
08-24 10:28:45.567  1115  3504 D Process : killProcessQuiet, pid=7667
08-24 10:28:45.567  1115  3504 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-24 10:28:45.717  1115  5339 I ActivityManager: Recipient 7667,
,08-24 10:29:45.567  1115  3742 D PMS     : acquireWL(2948e05c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1115 1000 null
08-24 10:29:45.577  3196  3709 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-24 10:29:45.567  1115  3742 I BatteryService: n_update end
08-24 10:29:45.577  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,08-24 10:29:45.567  1115  3742 D PMS     : releaseWL(2948e05c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-24 10:29:45.577  3322  3322 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-24 10:29:45.577  3322  3322 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-24 10:29:45.577  3196  3196 D PowerUI : closing low battery warning: level=100
08-24 10:29:45.577  1115  1115 D UsbnetService: BroadcastReceiver::onReceive+
08-24 10:29:45.577  1115  1115 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-24 10:29:45.577  1115  1115 D UsbnetService: onReceive BATTERY_CHANGED
08-24 10:29:45.577  1115  3071 D WifiController: battery changed pluggedType: 2
08-24 10:29:45.577  1115  1115 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-24 10:29:45.577  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-24 10:29:45.577  1115  1115 D UsbnetService: BroadcastReceiver::onReceive-
08-24 10:29:45.587  1115  1176 D HtcPowerSaver: updateBatteryInfo
08-24 10:29:45.577  1115  3071 D WifiController: handleMessage: E msg.what=155652
08-24 10:29:45.587  1115  1115 D HtcPowerSaver: Checking...
08-24 10:29:45.577  1115  3071 D WifiController: processMsg: DeviceActiveState
08-24 10:29:45.587  1115  1115 I HtcPowerSaver: >> updateStatus
08-24 10:29:45.577  1115  3071 D WifiController: processMsg: StaEnabledState
08-24 10:29:45.597  1115  1115 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-24 10:29:45.577  1115  3071 D WifiController: processMsg: DefaultState
08-24 10:29:45.597  1115  1115 I HtcPowerSaver: << updateStatus
08-24 10:29:45.577  1115  3071 D WifiController: handleMessage: X
,08-24 10:29:45.627  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-24 10:29:45.627  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-24 10:29:45.627  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-24 10:29:45.627  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-24 10:29:45.627  3196  3196 I FlashlightController: batteryLevelChange:100
,TIME-OUT KILL (timeout was 1400000ms)
```
