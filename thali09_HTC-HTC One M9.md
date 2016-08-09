#### Test 79751015cf21110_thali09_HTC-HTC One M9 Logs


```
--------- beginning of system
08-09 07:50:47.460  1108  3028 D PMS     : acquireWL(23c6c348): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10027}
,08-09 07:50:47.460  1108  3028 V AlarmManager: sending alarm PendingIntent{1cd145e1: PendingIntentRecord{c52c55b com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=103841, Int=0
--------- beginning of main
08-09 07:50:47.480  7493  7493 D AlarmReceiver: ACTION_RESTART_INTENT
08-09 07:50:47.520  7493  7493 D LocalBluetoothProfile: getPriorityOnValue = 100
08-09 07:50:47.530  1108  1108 D PMS     : releaseWL(23c6c348): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-09 07:50:47.520  7493  7493 D LocalBluetoothProfile: getPriorityOffValue = 0
08-09 07:50:47.520  7493  7493 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-09 07:50:47.520  7493  7493 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-09 07:50:47.560  7493  8209 D HtcModeClient: start the htcmodeservice thread
08-09 07:50:47.560  7493  8209 D HtcModeClient: initCanAgent
08-09 07:50:47.560  7493  8209 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-09 07:50:47.560  7493  8209 D HtcModeClient: sense info: version = none, id = 2
08-09 07:50:47.560  7493  8209 D HtcModeClient: display info: width = 1080, height = 1776
08-09 07:50:47.560  7493  8209 D HtcModeClient: display info: mode = 10
08-09 07:50:47.660  8206  8206 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-09 07:50:47.660  8206  8206 W HTCLOG  : mask=0x18
08-09 07:50:47.660  7493  7493 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: CONNECTION_READY = false
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: PHONE_PULGIN = false
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: Force_AWAKE = false
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: PHONE_PULGIN = true
08-09 07:50:47.660  7493  7493 D HtcModeClient: connectState: POWERCONNECTED_READY = true
08-09 07:50:47.830  8206  8212 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-09 07:50:47.830  8206  8212 W HTCLOG  : mask=0x18
08-09 07:50:47.830  8206  8212 E cutils-trace: Error opening trace file: Permission denied (13)
08-09 07:50:47.890  8206  8206 D CustomizationManager: ====startRecUseTime====
08-09 07:50:47.890  8206  8206 D htc.customization.log.level:  is 
08-09 07:50:47.890  8206  8206 W CustomizationLogLevel: Level value is invalid, use default level 2
08-09 07:50:47.970  8206  8206 D CustomizationManager:  Read ACC file spent 0.041 (s)
08-09 07:50:47.980  8206  8206 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: Parsing tag category name = application
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: Parsing tag category name = system
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: Parsing tag category name = Settings
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: Parsing tag category name = ACC
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-09 07:50:47.980  8206  8206 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-09 07:50:47.980  8206  8206 D CustomizationManager:  Read CID file spent 0.095 (s)
08-09 07:50:47.980  8206  8206 D CustomizationManager:  All configurations done spent 0.095 (s)
08-09 07:50:48.050  1108  3509 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8206 on display 0
08-09 07:50:48.050  1108  1173 D PMS     : acquireHCC(15cd68de): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1108 1000 null
08-09 07:50:48.050  1108  1173 D PMS     : acquireHCC(181d7abf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1108 1000 null
08-09 07:50:48.060  1108  3509 V WindowManager: addAppToken: AppWindowToken{94334ea token=Token{1ea854d5 ActivityRecord{2eada58c u0 com.test.thalitest/.MainActivity t444}}} to stack=1 task=444 at 0
08-09 07:50:48.070  1108  3509 I ActivityManager: Start proc 8226:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-09 07:50:48.070  8206  8206 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-09 07:50:48.070  8206  8206 W HTCLOG  : mask=0x18
08-09 07:50:48.080  8206  8224 W HTCLOG  : use specified tag [Vector], func [0].
08-09 07:50:48.080  8206  8224 W HTCLOG  : mask=0x18
08-09 07:50:48.080  8226  8226 W HTCLOG  : use specified tag [FDManager], func [0].
08-09 07:50:48.080  8226  8226 W HTCLOG  : mask=0x18
08-09 07:50:48.080   561   561 I art     : Explicit concurrent mark sweep GC freed 8662(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 127us total 13.503ms
08-09 07:50:48.090   561   561 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 99us total 8.172ms
08-09 07:50:48.100  3293  3293 D DotMatrix: [EventService]  onDisplayChanged: 0
08-09 07:50:48.100  1108  1108 V ActivityManager: Display changed displayId=0
08-09 07:50:48.100  3293  3293 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-09 07:50:48.100  1108  3079 D ActivityManager: screenshot for ActivityRecord{2eada58c u0 com.test.thalitest/.MainActivity t444}, bitmap=null, time = 0
08-09 07:50:48.100   561   561 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 96us total 9.958ms
08-09 07:50:48.130  3528  3528 I TrimMemoryManager: [trimMemory] 20
08-09 07:50:48.150  8226  8226 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-09 07:50:48.200  8226  8226 I LibraryLoader: Time to load native libraries: 26 ms (timestamps 6570-6596)
08-09 07:50:48.200  8226  8226 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 07:50:48.210  8226  8226 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {16760e1}
08-09 07:50:48.210  8226  8226 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 07:50:48.210  8226  8226 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 07:50:48.220  8226  8226 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-09 07:50:48.220  8226  8226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 07:50:48.220  8226  8226 E SysUtils: ApplicationContext is null in ApplicationStatus
08-09 07:50:48.250  8226  8249 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
08-09 07:50:48.260  8226  8253 D BluetoothAdapter: 663682566: getState() :  mService = null. Returning STATE_OFF
08-09 07:50:48.260  8226  8226 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-09 07:50:48.260  8226  8226 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
08-09 07:50:48.260  8226  8226 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
08-09 07:50:48.270  8226  8226 W HTCLOG  : use specified tag [libEGL], func [3].
08-09 07:50:48.270  8226  8226 W HTCLOG  : mask=0x18
08-09 07:50:48.270  8226  8226 W HTCLOG  : use specified tag [libEGL], func [3].
08-09 07:50:48.270  8226  8226 W HTCLOG  : mask=0x18
08-09 07:50:48.270  8226  8226 I Adreno  : QUALCOMM build                   : 065751b, 
08-09 07:50:48.270  8226  8226 I Adreno  : Build Date                       : 04/15/15
08-09 07:50:48.270  8226  8226 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-09 07:50:48.270  8226  8226 I Adreno  : Local Branch                     : 
08-09 07:50:48.270  8226  8226 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-09 07:50:48.270  8226  8226 I Adreno  : Remote Branch                    : NONE
08-09 07:50:48.270  8226  8226 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,08-09 07:50:48.340  8226  8259 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup,
,08-09 07:50:48.350  8226  8226 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-09 07:50:48.360  8226  8226 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,08-09 07:50:48.370  8226  8226 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,08-09 07:50:48.380  8226  8226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 07:50:48.380  8226  8226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 07:50:48.400  8226  8270 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,08-09 07:50:48.400  8226  8270 W HTCLOG  : mask=0x18
,08-09 07:50:48.410  1108  3079 V WindowManager: Adding window Window{11ca34f2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{22da4039 u0 com.htc.launcher/com.htc.launcher.Launcher})
,08-09 07:50:48.410  1108  3588 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-09 07:50:48.450  8226  8226 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-09 07:50:48.450  8226  8226 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-09 07:50:48.450  8226  8226 W HTCLOG  : mask=0x18
,08-09 07:50:48.450  8226  8226 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-09 07:50:48.450  8226  8226 W HTCLOG  : mask=0x18
,08-09 07:50:48.450  8226  8270 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,08-09 07:50:48.450  8226  8270 W HTCLOG  : mask=0x18
08-09 07:50:48.450  8226  8270 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-09 07:50:48.450  8226  8270 W HTCLOG  : mask=0x18
,08-09 07:50:48.460  1108  5445 I art     : Explicit concurrent mark sweep GC freed 24549(1283KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.128ms total 101.364ms
08-09 07:50:48.460  8226  8270 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-09 07:50:48.460  8226  8270 W HTCLOG  : mask=0x18
08-09 07:50:48.460  8226  8270 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-09 07:50:48.460  8226  8270 W HTCLOG  : mask=0x18
,08-09 07:50:48.460  8226  8270 W HTCLOG  : use specified tag [Surface], func [3].
08-09 07:50:48.460  8226  8270 W HTCLOG  : mask=0x18
08-09 07:50:48.460  8226  8270 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-09 07:50:48.460  8226  8270 W HTCLOG  : mask=0x18
08-09 07:50:48.460  8226  8270 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-09 07:50:48.460  8226  8270 W HTCLOG  : mask=0x18
,08-09 07:50:48.500  1108  1151 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +405ms (total +446ms)
,08-09 07:50:48.540  8226  8226 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8226
,08-09 07:50:48.600  8226  8226 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 07:50:48.650  8226  8276 D jxcore_app_log: JniHelper::setJavaVM(0xab4a9b70), pthread_self() = -1405010384
,08-09 07:50:48.650  8226  8276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
08-09 07:50:48.650  8226  8276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 07:50:48.650  8226  8276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 07:50:48.650  8226  8276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 07:50:48.650  8226  8276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-09 07:50:48.650  8226  8276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150a23f2 added. We now have 1 listener(s)
,08-09 07:50:48.650  1108  1131 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-09 07:50:48.650  8226  8276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-09 07:50:48.650  8226  8276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-09 07:50:48.650  8226  8276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:50:48.650  8226  8276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1,
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 07:50:48.660  8226  8276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bf49f9 added. We now have 1 listener(s)
08-09 07:50:48.660  8226  8276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 07:50:48.660  1108  3071 D WifiService: New client listening to asynchronous messages
,08-09 07:50:48.660  8226  8276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:50:48.660  8226  8276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-09 07:50:48.660  8226  8276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 07:50:48.660  8226  8276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 07:50:48.660  8226  8276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
08-09 07:50:48.660  8226  8276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:50:48.660  1108  3490 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-09 07:50:48.660  8226  8276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
,08-09 07:50:48.660  8226  8276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:50:48.660  8226  8276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:50:48.660  8226  8276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
08-09 07:50:48.660  8226  8276 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:50:48.660  8226  8276 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-09 07:50:48.710  8226  8226 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 07:50:49.050  1108  1173 D PMS     : releaseHCC(15cd68de): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,08-09 07:50:49.050  1108  1173 D PMS     : releaseHCC(181d7abf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-09 07:50:49.090  8226  8282 W jxcore-log: Initializing JXcore engine,
08-09 07:50:49.090  8226  8282 W jxcore-log: JXcore engine is ready
,08-09 07:50:49.140  8226  8282 W jxcore-log: Starting JXcore engine,
,08-09 07:50:49.230  8226  8282 W jxcore-log: Platform android,
08-09 07:50:49.230  8226  8282 W jxcore-log: 
08-09 07:50:49.230  8226  8282 W jxcore-log: Process ARCH arm
08-09 07:50:49.230  8226  8282 W jxcore-log: 
,08-09 07:50:49.440  8226  8282 I jxcore-log: JXcore Cordova bridge is ready!
08-09 07:50:49.440  8226  8282 I jxcore-log: 
,08-09 07:50:49.440  8226  8282 W jxcore-log: JXcore engine is started
08-09 07:50:49.450  8226  8276 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-09 07:50:49.450  8226  8226 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-09 07:50:49.470  8226  8282 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
08-09 07:50:49.470  8226  8282 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,08-09 07:50:49.470  8226  8226 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
08-09 07:50:49.470  8226  8226 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-09 07:50:49.480  8226  8226 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-09 07:50:49.490  8226  8226 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-09 07:50:49.490  8226  8226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:50:49.490  8226  8226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:50:49.490  8226  8226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:50:49.490  8226  8226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:50:49.490  8226  8226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150a23f2 removed from the list
08-09 07:50:49.490  8226  8226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 07:50:49.490  8226  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bf49f9 removed from the list
08-09 07:50:49.490  8226  8226 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:50:49.490  8226  8226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-09 07:50:49.490  8226  8226 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-09 07:50:49.650  8284  8284 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
08-09 07:50:49.650  8284  8284 W HTCLOG  : mask=0x18
,08-09 07:50:49.670  7493  8209 I HtcModeClient: handler message = 4011,
08-09 07:50:49.670  7493  8209 D HtcModeClient: getConnectionCheckCount first 0
08-09 07:50:49.670  7493  8209 D HtcModeClient: getConnectionCheckCount count = 9
08-09 07:50:49.670  7493  8209 E HtcModeClient: Check connection and retry 10 times.
08-09 07:50:49.670  7493  8209 D HtcModeClient: setConnectionCheckCount count = 10
08-09 07:50:49.670  7493  8209 D HtcModeClient: setupRestart delayedTime = 3000
,08-09 07:50:49.670  7493  7493 D HtcModeClient: setBtPriority priority = on
08-09 07:50:49.670  7493  7493 D HtcModeClient: unbindBlueToothService
08-09 07:50:49.670  7493  7493 D HtcModeClient: Don't start project servcice
08-09 07:50:49.670  7493  7493 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-09 07:50:49.670  7493  7493 D HtcModeClient: connectState: CONNECTION_READY = false,
08-09 07:50:49.670  7493  7493 D SilentMusic: call stop
,08-09 07:50:49.670  7493  7493 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-09 07:50:49.670  7493  8210 W CANMesgAgentLocalSocket: read the terminate packet, so break
08-09 07:50:49.680  7493  7493 D HtcModeClient: onDestroy
,08-09 07:50:49.680  1108  3509 D Process : killProcessQuiet, pid=7583
08-09 07:50:49.680  1108  3509 I ActivityManager: Killing 7583:com.google.android.gm/u0a97 (adj 15): empty #17
,08-09 07:50:49.680  1108  3509 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-09 07:50:49.740  1108  3394 I ActivityManager: Recipient 7583,
,08-09 07:50:49.830  8284  8289 W HTCLOG  : use specified tag [cutils-trace], func [0].
,08-09 07:50:49.830  8284  8289 W HTCLOG  : mask=0x18
08-09 07:50:49.830  8284  8289 E cutils-trace: Error opening trace file: Permission denied (13)
,08-09 07:50:49.890  8284  8284 D CustomizationManager: ====startRecUseTime====,
08-09 07:50:49.890  8284  8284 D htc.customization.log.level:  is 
08-09 07:50:49.890  8284  8284 W CustomizationLogLevel: Level value is invalid, use default level 2
,08-09 07:50:49.970  8284  8284 D CustomizationManager:  Read ACC file spent 0.042 (s),
,08-09 07:50:49.970  8284  8284 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: Parsing tag category name = application
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: Parsing tag category name = system
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: Parsing tag category name = Settings
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: Parsing tag category name = ACC
,08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-09 07:50:49.980  8284  8284 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-09 07:50:49.980  8284  8284 D CustomizationManager:  Read CID file spent 0.096 (s),
08-09 07:50:49.980  8284  8284 D CustomizationManager:  All configurations done spent 0.096 (s)
,08-09 07:50:50.030  1108  1130 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8284, uid=2000,
,08-09 07:50:50.030  1108  1143 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
08-09 07:50:50.040  1108  1143 D Process : killProcessQuiet, pid=8226
08-09 07:50:50.040  1108  1143 I ActivityManager: Killing 8226:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
08-09 07:50:50.040  1108  1143 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,08-09 07:50:50.140   525   525 W HTCLOG  : use specified tag [Vector], func [0].
08-09 07:50:50.140   525   525 W HTCLOG  : mask=0x18
,08-09 07:50:50.150  1108  3550 I ActivityManager: Recipient 8226
,08-09 07:50:50.150  1108  3071 D WifiService: Client connection lost with reason: 4
,08-09 07:50:50.250  1108  3550 W ActivityManager: Spurious death for ProcessRecord{1df9a8d8 8226:com.test.thalitest/u0a142}, curProc for 8226: null,
,08-09 07:50:50.260  1108  1178 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed,
,08-09 07:50:50.310  1108  3067 D PMS     : acquireWL(3cee431): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1108 1000 null,
08-09 07:50:50.320  3293  3293 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
08-09 07:50:50.320  3293  3293 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,08-09 07:50:50.320  1108  3924 D PMS     : acquireWL(17844716): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4296 10019 null
,08-09 07:50:50.320  4296  4768 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-09 07:50:50.320  1108  3496 D PMS     : releaseWL(17844716): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
08-09 07:50:50.320  3685  4135 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,08-09 07:50:50.330  1108  3068 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
,08-09 07:50:50.340  3685  4135 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,08-09 07:50:50.350  5247  5247 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-09 07:50:50.350  3742  8303 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-09 07:50:50.360  1108  3031 W SystemReader: Cannot find grip_rejection_width, use default value instead,
08-09 07:50:50.360  1108  3067 D PMS     : releaseWL(3cee431): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
08-09 07:50:50.360  1108  3068 V NetworkPolicy: writePolicyLocked(),
08-09 07:50:50.370  6413  6413 I art     : Explicit concurrent mark sweep GC freed 12884(806KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 3MB/5MB, paused 466us total 84.476ms
08-09 07:50:50.360  1108  3509 D PMS     : acquireWL(303b733): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 5247 10019 null
,08-09 07:50:50.370  3685  4135 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
08-09 07:50:50.380  3528  3528 I art     : Explicit concurrent mark sweep GC freed 35613(2MB) AllocSpace objects, 47(4MB) LOS objects, 39% free, 20MB/34MB, paused 1.120ms total 79.534ms
08-09 07:50:50.380  3685  4135 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,08-09 07:50:50.390  5247  5247 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-09 07:50:50.390  3894  3894 I ConfigService: onCreate
08-09 07:50:50.390  3894  3894 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-09 07:50:50.400  1108  3068 D NetworkPolicy: notifyPoliciesChangeLocked: no change
08-09 07:50:50.400  1108  3068 V NetworkPolicy: updateNetworkEnabledLocked()
08-09 07:50:50.400  1108  3068 V NetworkPolicy: updateNotificationsLocked()
,08-09 07:50:50.410  3894  3894 I ConfigService: onBind returning update interface
08-09 07:50:50.410  3894  3894 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-09 07:50:50.410  3894  3894 I ConfigService: onBind returning config service
08-09 07:50:50.410  1108  1131 D PMS     : acquireWL(3083839b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3894 10019 null
,08-09 07:50:50.410  3505  3505 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
08-09 07:50:50.420  3685  4135 E ExternalAccountType: Unsupported attribute readOnly
08-09 07:50:50.420  1108  3496 I ActivityManager: Start proc 8305:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
08-09 07:50:50.430  1108  1131 D PMS     : releaseWL(3083839b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-09 07:50:50.440  8305  8305 W HTCLOG  : use specified tag [FDManager], func [0].
08-09 07:50:50.440  8305  8305 W HTCLOG  : mask=0x18
,08-09 07:50:50.450  1108  3028 I ActivityManager: Start proc 8325:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService
08-09 07:50:50.450  1108  3028 D PMS     : acquireWL(b550876): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10058}
08-09 07:50:50.450  1108  3028 V AlarmManager: sending alarm PendingIntent{3d0cbe77: PendingIntentRecord{277f8ae4 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1470721841556, Int=60000
,08-09 07:50:50.460  1108  3028 V AlarmManager: sending alarm PendingIntent{3e13c5a: PendingIntentRecord{ee64e8b android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=108823, Int=0
,08-09 07:50:50.460  3894  3894 I ConfigService: onDestroy
,08-09 07:50:50.470  8325  8325 W HTCLOG  : use specified tag [FDManager], func [0].
,08-09 07:50:50.470  8325  8325 W HTCLOG  : mask=0x18
,08-09 07:50:50.480  1108  1108 W PackageManager: Unable to load service info ResolveInfo{224a285f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
08-09 07:50:50.480  1108  1108 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:50.480  1108  1108 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:50.480  ,1108  1108 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-09 07:50:50.500  8305  8305 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-09 07:50:50.500  8305  8305 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-09 07:50:50.510  3528  3528 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-09 07:50:50.510  3528  3528 I ThreadedRenderer: Defer allocateBuffers to drawing time
08-09 07:50:50.520  1108  1142 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
08-09 07:50:50.510  8325  8347 D SMSBackup: SMSBackupAgentService started
08-09 07:50:50.510  8325  8347 D SMSBackup: Checking restore status
08-09 07:50:50.530  8325  8347 D SMSBackup: Restore complete
,08-09 07:50:50.530  8325  8347 D SMSBackup: cancelCheckAlarm
08-09 07:50:50.530  8325  8347 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
,08-09 07:50:50.530  8305  8305 I MultiDex: VM with version 2.1.0 has multidex support
08-09 07:50:50.530  8305  8305 I MultiDex: install
08-09 07:50:50.530  8305  8305 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-09 07:50:50.550  8305  8305 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
08-09 07:50:50.560  1108  1178 I art     : Explicit concurrent mark sweep GC freed 21865(1590KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 3.281ms total 255.673ms
,08-09 07:50:50.560  8305  8305 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest,
,08-09 07:50:50.560  3471  3471 D Nfc-Utils: isNxpCodebase: isNxp=false
,08-09 07:50:50.570  1108  3549 D Process : killProcessQuiet, pid=7297
08-09 07:50:50.570  1108  3549 I ActivityManager: Killing 7297:com.google.android.music:main/u0a115 (adj 15): empty #17,
08-09 07:50:50.570  1108  3549 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-09 07:50:50.580  1108  1142 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-09 07:50:50.630  1108  1108 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,08-09 07:50:50.670  8284  8284 I art     : System.exit called, status: 0,
08-09 07:50:50.670  8284  8284 W HTCLOG  : use specified tag [Vector], func [0].
08-09 07:50:50.670  8284  8284 W HTCLOG  : mask=0x18
08-09 07:50:50.680  1108  3934 I ActivityManager: Recipient 7297
08-09 07:50:50.680  1108  3550 D MediaRouterService: Client com.google.android.music (pid 7297): Died!,
,08-09 07:50:50.830  1108  3491 I ActivityManager: Start proc 8355:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
,08-09 07:50:50.840  3528  3890 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
08-09 07:50:50.840  3528  3890 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,08-09 07:50:50.850  5247  8354 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
08-09 07:50:50.850  5247  8354 D AccountUtils: Clearing selected account for com.test.thalitest
08-09 07:50:50.850  3528  3528 I Launcher: Deferring update until onResume
08-09 07:50:50.850  3528  3528 D Launcher: waitUntilResume // bindAppsRemoved
,08-09 07:50:50.850  8355  8355 W HTCLOG  : use specified tag [FDManager], func [0].,
,08-09 07:50:50.850  8355  8355 W HTCLOG  : mask=0x18
,08-09 07:50:50.890  7736  8380 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id),
,08-09 07:50:50.900  5247  8382 I PeopleContactsSync: CP2 sync disabled,
,08-09 07:50:50.900  1108  3496 D PMS     : acquireWL(d8fad7a): PARTIAL_WAKE_LOCK  Icing 0x1 5247 10019 null
08-09 07:50:50.900  5247  6630 I Icing   : doRemovePackageData com.test.thalitest
,08-09 07:50:50.910  1108  3079 D Process : killProcessQuiet, pid=7782
,08-09 07:50:50.910  1108  3079 I ActivityManager: Killing 7782:com.htc.mobiledata:remote/u0a40 (adj 15): empty #17
08-09 07:50:50.910  1108  3079 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-09 07:50:50.910  1108  3394 D PMS     : releaseWL(d8fad7a): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-09 07:50:50.910  1108  3924 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=5247, uid=10019, userID:0
,08-09 07:50:51.020  1108  3550 I ActivityManager: Recipient 7782,
,08-09 07:50:51.120  3685  3685 E PackageActionReceiver: ACTION_PACKAGE_REMOVED,
,08-09 07:50:51.130  3597  8385 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,08-09 07:50:51.130  3597  8385 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,08-09 07:50:51.130  3597  8385 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-09 07:50:51.140  3597  8385 W HTCLOG  : mask=0x18
08-09 07:50:51.140  3597  8385 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/registry.db, handle: 0x55ce1c1720
,08-09 07:50:51.140  5247  8384 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:591)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:585)
08-09 07:50:51.140  5247  8384 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.run(SourceFile:608)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: FATAL EXCEPTION: Open database in background
08-09 07:50:51.140  5247  8384 E AndroidRuntime: Process: com.google.android.gms, PID: 5247
08-09 07:50:51.140  5247  8384 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:591)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:585)
08-09 07:50:51.140  5247  8384 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.run(SourceFile:608)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: provider may killed!
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.140  3597  8385 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.140  1108  3934 E ActivityManager: App crashed! Process: com.google.android.gms
08-09 07:50:51.150  5247  8384 D Process : killProcess, pid=5247
08-09 07:50:51.150  5247  8384 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-09 07:50:51.150  3597  8385 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
08-09 07:50:51.150  5247  8384 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.150  5247  8384 W HTCLOG  : mask=0x18
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: Can't write: system_app_crash,
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.150  1108  8386 E DropBoxManagerService: 	... 5 more
08-09 07:50:51.150  3528  3528 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
08-09 07:50:51.150  3528  3528 I ContextualWidget: package com.test.thalitest removed
08-09 07:50:51.160  3528  3938 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
08-09 07:50:51.170  3528  8387 I ContextualWidget: com.test.thalitest is not installed
08-09 07:50:51.170  3528  8387 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
08-09 07:50:51.170  3528  8387 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
08-09 07:50:51.170  3528  8387 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-09 07:50:51.170  3528  8387 W HTCLOG  : mask=0x18
08-09 07:50:51.170  3528  8387 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xac102a70
08-09 07:50:51.170  3528  8387 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
08-09 07:50:51.170  3528  8387 E AndroidRuntime: Process: com.htc.launcher, PID: 3528
08-09 07:50:51.170  3528  8387 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.170  3528  8387 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 07:50:51.180  1108  1130 I ActivityManager: Start proc 8388:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
08-09 07:50:51.180  1108  3079 E ActivityManager: App crashed! Process: com.htc.launcher
08-09 07:50:51.180  1108  3079 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-09 07:50:51.190  1108  3079 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.190  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.190  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.190  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.190  1108  3079 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.190  1108  3079 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.190  1108  3079 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.190  1108  3079 W System.err: 	... 14 more
08-09 07:50:51.190  1108  3079 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.190  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.190  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.190  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.190  1108  3079 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.190  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.190  1108  3079 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.190  1108  3079 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.190  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.190  1108  3079 W System.err: 	... 14 more
08-09 07:50:51.190  1108  3079 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-09 07:50:51.200  1108  8401 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-09 07:50:51.200  1108  8401 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1470721851204.dbox_tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:50:51.200  1108  8401 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.200  1108  8401 E ErrorReport: 	... 4 more
08-09 07:50:51.200  8388  8388 W HTCLOG  : use specified tag [FDManager], func [0].
08-09 07:50:51.200  8388  8388 W HTCLOG  : mask=0x18
08-09 07:50:51.200  1108  3588 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.200  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.200  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.200  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.200  3528  8387 D Process : killProcess, pid=3528
08-09 07:50:51.200  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.200  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-09 07:50:51.200  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-09 07:50:51.200  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-09 07:50:51.200  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-09 07:50:51.200  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-09 07:50:51.200  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-09 07:50:51.200  1108  3588 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.200  1108  3588 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.200  1108  3588 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.200  3528  8387 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-09 07:50:51.210  1108  3509 I ActivityManager: Recipient 5247
08-09 07:50:51.200  1108  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.210  1108  3491 D PMS     : handleWLDeath(10a27c85): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-09 07:50:51.200  1108  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.210  1108  3496 D PMS     : handleWLDeath(303b733): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-09 07:50:51.200  1108  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.210  1108  3509 I ActivityManager: Process com.google.android.gms (pid 5247) has died
08-09 07:50:51.200  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.210  1108  3509 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-09 07:50:51.200  3528  8387 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.210  1108  3509 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
08-09 07:50:51.200  1108  3588 W System.err: 	... 12 more
08-09 07:50:51.210  1108  3509 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
08-09 07:50:51.200  3528  8387 W HTCLOG  : mask=0x18
08-09 07:50:51.220  1108  3509 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,08-09 07:50:51.220   491   491 E lowmemorykiller: Error writing /proc/3528/oom_score_adj; errno=22
08-09 07:50:51.220  1108  3509 V WindowManager: addAppToken: AppWindowToken{96b3d07 token=Token{db2746 ActivityRecord{35916721 u0 com.htc.launcher/.Launcher t445}}} to stack=0 task=445 at 0
,08-09 07:50:51.280  1108  3549 I ActivityManager: Recipient 3528
08-09 07:50:51.280  1108  3925 I WindowState: WIN DEATH: Window{22da4039 u0 com.htc.launcher/com.htc.launcher.Launcher}
,08-09 07:50:51.280  1108  3549 I ActivityManager: Process com.htc.launcher (pid 3528) has died
08-09 07:50:51.280  1108  3549 W ActivityManager: Scheduling restart of crashed service com.htc.launcher/.htcwidget.HtcContextualWidgetService in 10931ms
,08-09 07:50:51.300  1108  3549 I ActivityManager: Start proc 8414:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-09 07:50:51.300  1108  3588 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-09 07:50:51.300  8414  8414 W HTCLOG  : use specified tag [FDManager], func [0].,
08-09 07:50:51.300  8414  8414 W HTCLOG  : mask=0x18
,08-09 07:50:51.310  1108  1131 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
08-09 07:50:51.310  8388  8388 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,08-09 07:50:51.310  8388  8388 D IdefixUninstallListener: package_removed = com.test.thalitest,
,08-09 07:50:51.340  8388  8388 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-09 07:50:51.340  8388  8388 W HTCLOG  : mask=0x18
,08-09 07:50:51.340  8388  8388 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: ,	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
,08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030),
08-09 07:50:51.340  8388  8388 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.340  8388  8388 W System.err: java.sql.SQLException: Getting a writable database from helper a@2bb7a642 failed
08-09 07:50:51.340  1108  3496 I ActivityManager: Killing 7463:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-09 07:50:51.340  8388  8388 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
08-09 07:50:51.340  8388  8388 W System.err: ,	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
08-09 07:50:51.340  8388  8388 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-09 07:50:51.340  8388  8388 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-09 07:50:51.340  8388  8388 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196),
08-09 07:50:51.340  8388  8388 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-09 07:50:51.340  8388  8388 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-09 07:50:51.340  8388  8388 W System.err: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,08-09 07:50:51.340  8388  8388 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.340  8388  8388 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.340  8388  8388 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.340  8388  8388 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
,08-09 07:50:51.340  8388  8388 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.340  8388  8388 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
,08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268),
08-09 07:50:51.340  8388  8388 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-09 07:50:51.340  8388  8388 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.340  8388  8388 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-09 07:50:51.340  8388  8388 W System.err: 	... 15 more
08-09 07:50:51.340  1108  3496 D Process : killProcessQuiet, pid=7463
08-09 07:50:51.340  1108  3496 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-09 07:50:51.350  8414  8414 I MultiDex: VM with version 2.1.0 has multidex support
,08-09 07:50:51.350  8414  8414 I MultiDex: install
08-09 07:50:51.350  8414  8414 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-09 07:50:51.360  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-09 07:50:51.360  8414  8414 D FaceDetectTask: checkIsOmronEnable start
,08-09 07:50:51.360  8414  8414 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-09 07:50:51.360  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.360  8414  8414 D FaceDetectTask: IsOmronEnable : true
,08-09 07:50:51.360  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.360  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-09 07:50:51.370  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.370  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.370  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:51.370  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.370  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.370  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:51.370  8414  8414 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:51.370  8414  8414 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
,08-09 07:50:51.370  8414  8414 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-09 07:50:51.370  8414  8414 W HTCLOG  : mask=0x18
,08-09 07:50:51.370  8414  8414 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase:, 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: ,	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	,at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.370  8414  8414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-09 07:50:51.370  8414  8414 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.370  8414  8414 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286),
08-09 07:50:51.380  8414  8414 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.380  8414  8414 W System.err: 	,at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-09 07:50:51.380  8414  8414 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
,08-09 07:50:51.380  8414  8414 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
,08-09 07:50:51.380  8414  8414 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.380  8414  8414 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,08-09 07:50:51.380  8414  8414 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.380  8414  8414 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-09 07:50:51.380  8414  8414 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.380  8414  8414 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.380  8414  8414 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-09 07:50:51.380  8414  8414 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752),
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
,08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	,at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.380  8414  8414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-09 07:50:51.380  8414  8414 E AndroidRuntime: FATAL EXCEPTION: main
08-09 07:50:51.380  8414  8414 E AndroidRuntime: Process: com.htc.launcher, PID: 8414
08-09 07:50:51.380  8414  8414 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: ,	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method),
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: ,	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:51.380  8414  8414 E AndroidRuntime: 	,... 11 more
,08-09 07:50:51.480  1108  3359 I ActivityManager: Recipient 7463,
,08-09 07:50:51.560  1108  3924 E ActivityManager: App crashed! Process: com.htc.launcher
08-09 07:50:51.560  1108  3924 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-09 07:50:51.560  1108  3924 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.560  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.560  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.560  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.560  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
,08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-09 07:50:51.570  1108  3924 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.560  1108  3924 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.560  1108  3924 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.560  1108  3924 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.560  1108  3924 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.560  1108  3924 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.560  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.560  1108  3924 W System.err: 	... 14 more
08-09 07:50:51.560  1108  3924 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.560  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.560  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.560  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.560  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.560  1108  3924 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.560  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.560  1108  3924 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.560  1108  3924 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.570  1108  3924 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.570  1108  39,24 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.570  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.570  1108  3924 W System.err: 	... 14 more
08-09 07:50:51.580  8414  8414 D Process : killProcess, pid=8414
08-09 07:50:51.580  8414  8414 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-09 07:50:51.580  8414  8414 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.580  8414  8414 W HTCLOG  : mask=0x18
08-09 07:50:51.580  1108  3588 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.580  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.580  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.580  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.580  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.580  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-09 07:50:51.580  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-09 07:50:51.580  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-09 07:50:51.580  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-09 07:50:51.580  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-09 07:50:51.580  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-09 07:50:51.590  1108  8443 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-09 07:50:51.590  1108  8443 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1470721851596.dbox_tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:50:51.590  1108  8443 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.590  1108  8443 E ErrorReport: 	... 4 more
08-09 07:50:51.580  1108  3588 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.580  1108  3588 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.580  1108  3588 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.580  1108  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.580  1108  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.580  1108  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.580  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.580  1108  3588 W System.err: 	... 12 more
,08-09 07:50:51.600  6413  8444 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,08-09 07:50:51.620  1108  3925 I ActivityManager: Start proc 8445:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-09 07:50:51.640  8445  8445 W HTCLOG  : use specified tag [FDManager], func [0].,
08-09 07:50:51.640  8445  8445 W HTCLOG  : mask=0x18
,08-09 07:50:51.640  6413  8444 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-09 07:50:51.640  6413  8444 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
,08-09 07:50:51.640  6413  8444 W HTCLOG  : mask=0x18
08-09 07:50:51.640  6413  8444 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55ce16bc30
,08-09 07:50:51.650  6413  8444 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,08-09 07:50:51.650  6413  8444 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService],
08-09 07:50:51.650  6413  8444 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6413
08-09 07:50:51.650  6413  8444 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method),
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	,at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.650  6413  8444 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.650  1108  3490 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: Can't write: system_app_crash
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.650  1108  8467 E DropBoxManagerService: 	... 5 more
08-09 07:50:51.650  6413  8444 D Process : killProcess, pid=6413
08-09 07:50:51.650  6413  8444 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
08-09 07:50:51.650  6413  8444 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.650  6413  8444 W HTCLOG  : mask=0x18
,08-09 07:50:51.680  8445  8445 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 ,
,08-09 07:50:51.690  8445  8468 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-09 07:50:51.690  8445  8468 W HTCLOG  : mask=0x18
08-09 07:50:51.690  1108  3491 D PMS     : acquireWL(19f4a2a3): PARTIAL_WAKE_LOCK  AsyncService 0x1 8139 10128 null
,08-09 07:50:51.690  8445  8468 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468),
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.690  8445  8468 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-09 07:50:51.690  8445  8468 E AndroidRuntime: Process: com.android.keychain, PID: 8445
08-09 07:50:51.690  8445  8468 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-09 07,:50:51.690  8445  8468 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.690  8445  8468 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.690  1108  1131 D PMS     : releaseWL(19f4a2a3): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-09 07:50:51.690  1108  3509 E ActivityManager: App crashed! Process: com.android.keychain
08-09 07:50:51.690  1108  3509 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-09 07:50:51.690  1108  3509 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.700  1108  3925 I ActivityManager: Recipient 8414
08-09 07:50:51.690  1108  3509 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.700  1108  3925 I ActivityManager: Process com.htc.launcher (pid 8414) has died
08-09 07:50:51.690  1108  3509 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.690  1108  3509 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.690  1108  3509 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.690  1108  3509 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.690  1108  3509 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.690  1108  3509 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-09 07:50:51.690  1108  3509 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-09 07:50:51.700  1108  8470 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-09 07:50:51.700  1108  8470 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1470721851711.dbox_tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:50:51.700  1108  8470 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.700  1108  8470 E ErrorReport: 	... 4 more
,08-09 07:50:51.690  1108  3509 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.700  1108  3925 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-09 07:50:51.690  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.700  1108  3925 V WindowManager: addAppToken: AppWindowToken{624c5ff token=Token{1201d91e ActivityRecord{142ed959 u0 com.htc.launcher/.Launcher t446}}} to stack=0 task=446 at 0
08-09 07:50:51.690  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.690  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.690  1108  3509 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.690  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.690  1108  3509 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.690  1108  3509 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.690  8088  8088 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-09 07:50:51.690  1108  3509 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.690  1108  3509 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.690  1108  3509 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.690  1108  3509 W System.err: 	... 14 more
08-09 07:50:51.690  1108  3509 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.690  8088  8088 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
08-09 07:50:51.690  1108  3509 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.690  1108  3509 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.690  1108  3509 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,08-09 07:50:51.690  1108  3509 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.690  1108  3509 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.700  1108  3509 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.700  1108  3509 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-09 07:50:51.700  1108  3509 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-09 07:50:51.700  1108  3509 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,08-09 07:50:51.700  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.700  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.700  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.700  1108  3509 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.700  1108  3509 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.700  1108  3509 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,08-09 07:50:51.700  1108  3509 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.700  1108  3509 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.700  1108  3509 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.700  1108  3509 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.700  1108  3509 W System.err: 	... 14 more
08-09 07:50:51.700  8088  8088 I DeviceManagement: WorkflowService: Starting workflow service
08-09 07:50:51.710  8088  8471 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2f0cf492] args=[Bundle[mParcelledData.dataSize=112]]
,08-09 07:50:51.710  8088  8471 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,08-09 07:50:51.710  8088  8471 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-09 07:50:51.710  8088  8471 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-09 07:50:51.720  8088  8471 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
08-09 07:50:51.720  1108  3925 I ActivityManager: Start proc 8472:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-09 07:50:51.720  8472  8472 W HTCLOG  : use specified tag [FDManager], func [0].
08-09 07:50:51.720  8472  8472 W HTCLOG  : mask=0x18
,08-09 07:50:51.720  8445  8468 D Process : killProcess, pid=8445
,08-09 07:50:51.720  1108  3588 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-09 07:50:51.720  8445  8468 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-09 07:50:51.720  8445  8468 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.720  8445  8468 W HTCLOG  : mask=0x18
,08-09 07:50:51.730  1108  3588 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.730  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.730  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,08-09 07:50:51.730  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.730  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.730  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-09 07:50:51.730  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
,08-09 07:50:51.730  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-09 07:50:51.730  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-09 07:50:51.730  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-09 07:50:51.730  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-09 07:50:51.730  1108  3588 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-09 07:50:51.730  1108  3588 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.730  1108  3588 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.730  1108  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.730  1108  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.730  1108  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,08-09 07:50:51.730  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.730  1108  3588 W System.err: 	... 12 more
,08-09 07:50:51.740  8492  8492 W HTCLOG  : use specified tag [FDManager], func [0].
08-09 07:50:51.740  1108  3491 I ActivityManager: Start proc 8492:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
08-09 07:50:51.740  8492  8492 W HTCLOG  : mask=0x18
08-09 07:50:51.740  8088  8471 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,08-09 07:50:51.750  8088  8511 I DeviceManagement: SessionStateController: Checking invariants...
08-09 07:50:51.750  1108  3496 I ActivityManager: Recipient 6413
08-09 07:50:51.750  1108  3071 D WifiService: Client connection lost with reason: 4
,08-09 07:50:51.760  1108  3496 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6413) has died
08-09 07:50:51.760  1108  3496 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10459ms
08-09 07:50:51.760  1108  3496 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10458ms
,08-09 07:50:51.780  8472  8472 I MultiDex: VM with version 2.1.0 has multidex support,
08-09 07:50:51.780  8472  8472 I MultiDex: install
08-09 07:50:51.780  8472  8472 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-09 07:50:51.790  1108  3359 I ActivityManager: Recipient 8445
08-09 07:50:51.790  1108  3359 I ActivityManager: Process com.android.keychain (pid 8445) has died
08-09 07:50:51.790  1108  3359 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20428ms
,08-09 07:50:51.790  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-09 07:50:51.790  8472  8472 D FaceDetectTask: checkIsOmronEnable start
08-09 07:50:51.790  8472  8472 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:51.800  8472  8472 D FaceDetectTask: IsOmronEnable : true
08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:51.800  8472  8472 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:51.810  8472  8472 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-09 07:50:51.810  8472  8472 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-09 07:50:51.810  8472  8472 W HTCLOG  : mask=0x18
,08-09 07:50:51.810  8472  8472 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.,
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	,at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429),
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	,at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: ,	,at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.810  8472  8472 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.820  1108  3549 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.820  1108  3549 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-09 07:50:51.810  8472  8472 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.810  8472  8472 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-09 07:50:51.810  8472  8472 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-09 07:50:51.820  1108  8526 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-09 07:50:51.820  1108  8526 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1470721851835.dbox_tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:50:51.820  1108  8526 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at libcore.io.Posix.open(Native Method),
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.820  1108  8526 E ErrorReport: 	... 4 more
08-09 07:50:51.810  8472  8472 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.810  8472  8472 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.810  8472  8472 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.810  8472  8472 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.810  8472  8472 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.810  8472  8472 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppS,tateProvider.onCreate(ExternalAppStateProvider.java:25)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.810  8472  8472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: FATAL EXCEPTION: main
08-09 07:50:51.820  8472  8472 E AndroidRuntime: Process: com.htc.launcher, PID: 8472
08-09 07:50:51.820  8472  8472 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.820  8472  8472 E AndroidRuntim,e: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:51.820  8472  8472 E AndroidRuntime: 	... 11 more
08-09 07:50:51.830  1108  1131 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-09 07:50:51.820  1108  3549 E ActivityManager: App crashed! Process: com.htc.launcher
08-09 07:50:51.820  1108  3549 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.820  1108  3549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.820  1108  3549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.820  1108  3549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.840  1108  3079 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-09 07:50:51.820  1108  3549 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.820  1108  3549 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.820  1108  3549 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.820  1108  3549 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.820  1108  3549 W System.err: 	... 14 more
08-09 07:50:51.820  1108  3549 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.820  1108  3549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.820  1108  3549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.820  1108  3549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.820  1108  3549 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.820  1108  3549 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.820  1108  3549 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.820  1108  3549 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.820  1108  3549 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.820  1108  3549 W System.err: 	... 14 more
08-09 07:50:51.820  8472  8472 D Process : killProcess, pid=8472
08-09 07:50:51.820  8472  8472 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-09 07:50:51.820  8472  8472 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.820  8472  8472 W HTCLOG  : mask=0x18
08-09 07:50:51.830  1108  3588 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.830  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.830  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.830  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.830  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.830  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-09 07:50:51.830  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-09 07:50:51.830  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-09 07:50:51.830  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-09 07:50:51.830  8492  8492 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-09 07:50:51.830  8492  8492 W HTCLOG  : mask=0x18
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.830  8492  8492 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: FATAL EXCEPTION: main
08-09 07:50:51.830  8492  8492 E AndroidRuntime: Process: com.android.documentsui, PID: 8492
08-09 07:50:51.830  8492  8492 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-09 07:50:51.830  8492  8492 E AndroidRuntime: 	... 9 more
08-09 07:50:51.850  1108  8528 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-09 07:50:51.850  1108  8528 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1470721851861.dbox_tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:50:51.850  1108  8528 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.850  1108  8528 E ErrorReport: 	... 4 more
08-09 07:50:51.830  1108  1131 E ActivityManager: App crashed! Process: com.android.documentsui
08-09 07:50:51.850  1108  8527 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-09 07:50:51.850  1108  8527 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1470721851863.dbox_tmp: open failed: EROFS (Read-only file system)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:50:51.850  1108  8527 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.850  1108  8527 E ErrorReport: 	... 4 more
08-09 07:50:51.840  5494  5649 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-09 07:50:51.860  1108  3924 I ActivityManager: Recipient 8492
08-09 07:50:51.840  5494  5649 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-09 07:50:51.860  1108  1143 I ActivityManager: Start proc 8529:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-09 07:50:51.840  5494  5649 W HTCLOG  : mask=0x18
08-09 07:50:51.840  5494  5649 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55ce12afc0
08-09 07:50:51.840  1108  1131 W System.err: 	at java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.840  1108  3588 W System.err: com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-09 07:50:51.840  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-09 07:50:51.840  1108  3588 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.840  1108  3588 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.840  1108  3588 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.840  1108  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-09 07:50:51.840  5494  5649 E AndroidRuntime: Process: android.process.media, PID: 5494
08-09 07:50:51.840  5494  5649 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: ,	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.840  5494  5649 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.840  1108  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.840  1108  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.840  1108  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-09 07:50:51.840  1108  3588 W System.err: 	at 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)libcore.io.Posix.open(Native Method)
08-09 07:50:51.840  1108  1131 W System.err: 	at 
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.840  1108  1131 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.840  1108  1131 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.840  1108  1131 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.840  1108  3079 E ActivityManager: App crashed! Process: android.process.media
08-09 07:50:51.840  1108  3588 W System.err: libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.840  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.840  1108  1131 W System.err: 	... 14 more
08-09 07:50:51.840  1108  1131 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.840  1108  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.840  1108  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.840  1108  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.840  1108  1131 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.840  1108  1131 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.840  1108  1131 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.840  1108  1131 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.840  1108  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.840  1108  1131 W System.err: 	... 14 more
08-09 07:50:51.840  1108  3079 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.840  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.840  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.840  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.840  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.840  1108  3079 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.840  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.840  1108  3079 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.840  1108  3079 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.840  1108  3079 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.840  1108  3079 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.840  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.840  1108  3079 W System.err: 	... 14 more
08-09 07:50:51.850  1108  3079 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.850  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.850  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.850  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.850  1108  3079 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:51.850  1108  3079 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:51.850  1108  3079 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:51.850  1108  3079 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:51.850  1108  3079 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.850  1108  3079 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.850  1108  3079 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.850  1108  3079 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.850  1108  3079 W System.err: 	... 14 more
08-09 07:50:51.850  8492  8492 D Process : killProcess, pid=8492
08-09 07:50:51.850  8492  8492 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-09 07:50:51.850  8492  8492 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.850  8492  8492 W HTCLOG  : mask=0x18
08-09 07:50:51.850  1108  3588 W System.err: 	... 12 more
08-09 07:50:51.860  1108  3588 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.860  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.860  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.860  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-09 07:50:51.860  1108  3588 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.860  1108  3588 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.860  1108  3588 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.860  1108  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.860  1108  3588 W System.err: 	... 12 more
08-09 07:50:51.860  1108  3588 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:51.860  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:51.860  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:51.860  1108  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-09 07:50:51.860  1108  3588 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-09 07:50:51.860  1108  3588 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:51.860  1108  3588 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:51.860  1108  3588 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:51.860  1108  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:51.860  1108  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:51.860  1108  3588 W System.err: 	... 12 more
08-09 07:50:51.860  8529  8529 W HTCLOG  : use specified tag [FDManager], func [0].
08-09 07:50:51.860  8529  8529 W HTCLOG  : mask=0x18
08-09 07:50:51.880  8088  8511 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-09 07:50:51.880  8088  8511 W HTCLOG  : mask=0x18
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-09 07:50:51.880  8088  8511 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-09 07:50:51.960  1108  3359 I ActivityManager: Recipient 8472
,08-09 07:50:51.970  1108  3924 I ActivityManager: Process com.android.documentsui (pid 8492) has died
,08-09 07:50:51.970  1108  3924 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,08-09 07:50:51.980  1108  3924 V WindowManager: addAppToken: AppWindowToken{32d8ac64 token=Token{3e7775f7 ActivityRecord{2c61edf6 u0 com.htc.launcher/.Launcher t447}}} to stack=0 task=447 at 0
,08-09 07:50:51.990  5494  5649 D Process : killProcess, pid=5494
08-09 07:50:52.000  1108  3550 W ActivityManager: Exception when starting activity com.htc.launcher/.Launcher
08-09 07:50:52.000  1108  3550 W ActivityManager: android.os.DeadObjectException
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:504)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:855)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1227)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1327)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:1304)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:3061)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.attachApplicationLocked(ActivityStackSupervisor.java:575)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityManagerService.attachApplicationLocked(ActivityManagerService.java:6433)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityManagerService.attachApplication(ActivityManagerService.java:6495)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:487)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:52.000  1108  3550 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:454)
,08-09 07:50:51.990  5494  5649 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-09 07:50:51.990  5494  5649 W HTCLOG  : use specified tag [Process], func [0].
08-09 07:50:51.990  5494  5649 W HTCLOG  : mask=0x18
,08-09 07:50:52.010  1108  3550 I ActivityManager: Start proc 8551:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-09 07:50:52.010  1108  3359 W ActivityManager: Spurious death for ProcessRecord{12abcac9 8551:com.htc.launcher/u0a56}, curProc for 8472: null
,08-09 07:50:52.010  8088  8511 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.010  8088  8471 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.010  8088  8471 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,08-09 07:50:52.020  8088  8471 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowServic,e.onHandleIntent(WorkflowService.java:295)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:52.020  8088  8471 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 07:50:52.020  8551  8551 W HTCLOG  : use specified tag [FDManager], func [0].
08-09 07:50:52.020  8551  8551 W HTCLOG  : mask=0x18
08-09 07:50:52.020  8088  8471 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@2f0cf492]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:52.020  8088  8471 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 07:50:52.020  8088  8088 I DeviceManagement: WorkflowService: Stopping workflow service
,08-09 07:50:52.040  1108  3925 I ActivityManager: Recipient 5494
,08-09 07:50:52.060  8551  8551 I MultiDex: VM with version 2.1.0 has multidex support,
08-09 07:50:52.060  8551  8551 I MultiDex: install
08-09 07:50:52.060  8551  8551 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-09 07:50:52.070  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : null,
08-09 07:50:52.070  8551  8551 D FaceDetectTask: checkIsOmronEnable start
,08-09 07:50:52.070  8551  8551 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so,
,08-09 07:50:52.070  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-09 07:50:52.070  8551  8551 D FaceDetectTask: IsOmronEnable : true
08-09 07:50:52.070  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:52.070  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-09 07:50:52.070  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-09 07:50:52.070  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:52.070  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:52.080  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-09 07:50:52.080  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:52.080  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:52.080  8551  8551 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-09 07:50:52.080  8551  8551 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-09 07:50:52.080  8551  8551 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-09 07:50:52.080  8551  8551 W HTCLOG  : mask=0x18
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:52.080  8551  855,1 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:52.080  8551  8551 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:52.080  8551  8551 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:52.080  8551  8551 W System.err: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:52.080  8551  8551 W System.err: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:52.080  8551  8551 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-09 07:50:52.080  8551  8551 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
,08-09 07:50:52.080  8551  8551 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:52.080  8551  8551 W System.err: 	,at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442),
08-09 07:50:52.080  8551  8551 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:52.080  8551  8551 W System.err: ,	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:52.080  8551  8551 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:52.080  8551  8551 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:52.080  8551  8551 W System.err: 	,at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:52.080  8551  8551 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:52.080  8551  8551 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
,08-09 07:50:52.090  8551  8551 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
,08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:52.090  8551  8551 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: FATAL EXCEPTION: main
08-09 07:50:52.090  8551  8551 E AndroidRuntime: Process: com.htc.launcher, PID: 8551
08-09 07:50:52.090  8551  8551 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at ,android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-09 07:50:52.090  8551  8551 E AndroidRuntime: 	... 11 more
08-09 07:50:52.090  1108  3925 I ActivityManager: Process android.process.media (pid 5494) has died
08-09 07:50:52.090  1108  3925 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20122ms
08-09 07:50:52.100  3293  3313 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
08-09 07:50:52.100  1108  3924 E ActivityManager: App crashed! Process: com.htc.launcher
08-09 07:50:52.100  1108  3924 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-09 07:50:52.100  1108  3924 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:52.100  8529  8529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:52.100  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:52.100  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:52.100  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProp,erty(ErrorReportPreference.java:109)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:52.100  1108  3924 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:52.100  1108  3924 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:52.100  1108  3924 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:52.100  1108  3924 W System.err: 	... 14 more
08-09 07:50:52.100  1108  3924 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:52.100  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:52.100  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-09 07:50:52.100  1108  3924 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-09 07:50:52.110  1108  8580 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-09 07:50:52.110  1108  8580 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1470721852118.dbox_tmp: open failed: EROFS (Read-only file system)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:50:52.110  1108  8580 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:52.110  1108  8580 E ErrorReport: 	... 4 more
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-09 07:50:52.100  1108  3924 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-09 07:50:52.100  1108  3924 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-09 07:50:52.100  1108  3924 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-09 07:50:52.100  1108  3924 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.Posix.open(Native Method)
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 07:50:52.100  1108  3924 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 07:50:52.100  1108  3924 W System.err: 	... 14 more
08-09 07:50:52.100  3224  3224 I NotificationStackScrollLayout: setBlockTouchEnabled:false

```
