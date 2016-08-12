#### Test 797638300d10dad_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 15:12:39.291  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 15:12:39.294  3838  3952 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 15:12:39.299  6584  6584 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-12 15:12:47.110  6672  6672 D AndroidRuntime: 
08-12 15:12:47.110  6672  6672 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 15:12:47.117  6672  6672 D AndroidRuntime: CheckJNI is OFF
08-12 15:12:47.319  6672  6672 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 15:12:47.330  1035  1050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 15:12:47.344  1941  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 15:12:47.350  1035  1050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 15:12:47.351  1035  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{d9b5c7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 15:12:47.352  1035  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{d9b5c7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 15:12:47.353  1035  1050 D WindowStateEx: AppWindowTokenEx init.. 
08-12 15:12:47.354   337   352 E GBMv2   : DFP En is all cleared set to be enabled
08-12 15:12:47.382  1035  1050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6687 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 15:12:47.385  6672  6672 D AndroidRuntime: Shutting down VM
08-12 15:12:47.440  1941  2723 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 15:12:47.440  1941  2723 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35aa8271 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 15:12:47.441  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 15:12:47.441  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{21be2856 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 15:12:47.492  6687  6687 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 15:12:47.570  6687  6687 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 15:12:47.576  6687  6687 I LibraryLoader: Loading: webviewchromium
08-12 15:12:47.579  6687  6687 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6686-6689)
08-12 15:12:47.579  6687  6687 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 15:12:47.607  6687  6687 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e130647}
,08-12 15:12:47.611  6687  6687 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 15:12:47.612  6687  6687 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 15:12:47.627  6687  6687 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 15:12:47.628  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 15:12:47.641   313  2171 V AudioPolicyService: registerClient() client 0xb558a600, uid 10118
08-12 15:12:47.641  6687  6687 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 15:12:47.641  6687  6687 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-12 15:12:47.642  6687  6687 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 15:12:47.646  1035  1117 D BluetoothManagerService: Message: 20
08-12 15:12:47.646  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eab8c19:true
08-12 15:12:47.659  6687  6687 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 15:12:47.659  6687  6687 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 15:12:47.659  6687  6687 I Adreno-EGL: Build Date: 12/12/14 금
08-12 15:12:47.659  6687  6687 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 15:12:47.659  6687  6687 I Adreno-EGL: Remote Branch: 
08-12 15:12:47.659  6687  6687 I Adreno-EGL: Local Patches: 
08-12 15:12:47.659  6687  6687 I Adreno-EGL: Reconstruct Branch: 
,08-12 15:12:47.799  6687  6733 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 15:12:47.800  6687  6687 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 15:12:47.821  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 15:12:47.826  6687  6687 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 15:12:47.830  6687  6687 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 15:12:47.833  6687  6687 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 15:12:47.833  6687  6687 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 15:12:47.850  6687  6687 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 15:12:47.859  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 15:12:47.859  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 15:12:47.905  6687  6748 D OpenGLRenderer: Render dirty regions requested: true
08-12 15:12:47.905  6687  6748 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 15:12:47.930  6687  6748 D OpenGLRenderer: Enabling debug mode 0
,08-12 15:12:47.939  1035  1100 W ActivityManager: Activity pause timeout for ActivityRecord{10ff37f4 u0 com.test.thalitest/.MainActivity t6}
08-12 15:12:47.947  6687  6687 D Atlas   : Validating map...
,08-12 15:12:47.954  1035  2005 D SplitWindow: check instance of lgWin Window{7c775cb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 15:12:48.001  6687  6746 D LgDataFeature: LgDataFeature() Constructor: none
08-12 15:12:48.001  6687  6746 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 15:12:48.078  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +639ms (total +723ms)
08-12 15:12:48.080  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10ff37f4 u0 com.test.thalitest/.MainActivity t6} time:197190
08-12 15:12:48.080  6687  6687 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a2a4dc2 time:197191
08-12 15:12:48.195  6687  6687 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 15:12:48.195  6687  6687 I chromium: 
,08-12 15:12:48.234  6687  6687 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 15:12:48.406  6687  6761 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435159040
,08-12 15:12:48.423  6687  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 15:12:48.423  6687  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 15:12:48.423  6687  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 15:12:48.423  6687  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 15:12:48.423  6687  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 15:12:48.424  6687  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80006e6 added. We now have 1 listener(s)
,08-12 15:12:48.431  1035  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 15:12:48.436  6687  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 15:12:48.439  6687  6761 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-12 15:12:48.442  6687  6761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 15:12:48.443  6687  6761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 15:12:48.459  6687  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3267f07d added. We now have 1 listener(s)
,08-12 15:12:48.460  6687  6761 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 15:12:48.467  1035  1412 D WifiService: New client listening to asynchronous messages
08-12 15:12:48.473  6687  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 15:12:48.473  6687  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 15:12:48.475  6687  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 15:12:48.475  6687  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 15:12:48.475  6687  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 15:12:48.480  6687  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 15:12:48.482  1035  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 15:12:48.484  6687  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-12 15:12:48.500  6687  6761 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 15:12:48.501  6687  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 15:12:48.501  6687  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 15:12:48.501  6687  6761 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 15:12:48.504  6687  6761 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 15:12:48.504  6687  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 15:12:48.506  6687  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 15:12:48.547  6687  6746 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 15:12:48.547  6687  6746 I chromium: 
,08-12 15:12:48.626  6687  6687 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 15:12:48.747   337   354 E GBMv2   : DFP En is all cleared set to be enabled
08-12 15:12:48.747   337   354 E GBMv2   : Set value is all cleared set the max
08-12 15:12:48.747   337   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 15:12:49.496  6687  6764 W jxcore-log: Initializing JXcore engine
08-12 15:12:49.496  6687  6764 W jxcore-log: JXcore engine is ready
,08-12 15:12:49.566  6764  6764 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9764]" dev="sockfs" ino=9764 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 15:12:49.566  6764  6764 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 15:12:49.566  6764  6764 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10372]" dev="sockfs" ino=10372 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 15:12:49.566  6764  6764 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 15:12:49.566  6764  6764 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32029]" dev="sockfs" ino=32029 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 15:12:49.599  6687  6764 W jxcore-log: Starting JXcore engine
,08-12 15:12:49.750  6687  6764 W jxcore-log: Platform android
08-12 15:12:49.750  6687  6764 W jxcore-log: 
08-12 15:12:49.750  6687  6764 W jxcore-log: Process ARCH arm
08-12 15:12:49.750  6687  6764 W jxcore-log: 
,08-12 15:12:50.098  6687  6764 I jxcore-log: JXcore Cordova bridge is ready!
08-12 15:12:50.098  6687  6764 I jxcore-log: 
08-12 15:12:50.099  6687  6764 W jxcore-log: JXcore engine is started
,08-12 15:12:50.113  6687  6761 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 15:12:50.119  6687  6687 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 15:13:00.059  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 15:13:00.060  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 15:13:00.060  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 15:13:00.060  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 15:13:00.065  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 15:13:00.065  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 15:13:00.066  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 15:13:00.067  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 15:13:09.472  6687  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 15:13:09.472  6687  6764 I jxcore-log: 
08-12 15:13:09.476  6687  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 15:13:09.476  6687  6764 I jxcore-log: 
,08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 15:13:09.484  6687  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 15:13:09.487  6687  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 15:13:09.491  6687  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 15:13:09.491  6687  6764 I jxcore-log: 
08-12 15:13:09.494  6687  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 15:13:09.494  6687  6764 I jxcore-log: 
,08-12 15:13:10.136  6687  6764 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 15:13:10.136  6687  6764 I jxcore-log: Failed to execute UT.
08-12 15:13:10.136  6687  6764 I jxcore-log: 
08-12 15:13:10.136  6687  6764 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 15:13:10.136  6687  6764 I jxcore-log: 
,08-12 15:13:10.150  6687  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 15:13:10.150  6687  6764 I jxcore-log: 
08-12 15:13:10.157  6687  6687 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 15:13:10.470  6776  6776 D AndroidRuntime: 
08-12 15:13:10.470  6776  6776 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 15:13:10.475  6776  6776 D AndroidRuntime: CheckJNI is OFF
,08-12 15:13:10.697  6776  6776 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 15:13:10.712  1035  1100 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-12 15:13:10.713  1035  1100 I ActivityManager: Killing 6687:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-12 15:13:10.761  1035  2005 I WindowState: WIN DEATH: Window{7c775cb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 15:13:10.763  1035  1412 D WifiService: Client connection lost with reason: 4
08-12 15:13:10.768  1035  2005 D InputDispatcher: Window went away: Window{7c775cb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 15:13:10.834  1035  1100 I ActivityManager:   Force finishing activity ActivityRecord{10ff37f4 u0 com.test.thalitest/.MainActivity t6}
,08-12 15:13:10.855   337   352 E GBMv2   : DFP En is all cleared set to be enabled
08-12 15:13:10.855  1035  2013 W ActivityManager: Spurious death for ProcessRecord{2f0d0af9 6687:com.test.thalitest/u0a118}, curProc for 6687: null
08-12 15:13:10.856  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 15:13:10.858  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{10ff37f4 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 15:13:10.858  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{10ff37f4 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 15:13:10.901  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 15:13:10.901  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 15:13:10.901  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16c590d7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 15:13:10.902  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 15:13:10.904  1941  2723 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 15:13:10.904  1941  2723 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18a5dc4 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 15:13:10.905  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 15:13:10.906  2034  2074 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-12 15:13:10.912  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-12 15:13:10.913  2730  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 15:13:10.913  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 15:13:10.915  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 15:13:10.917  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 15:13:10.917  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 15:13:10.917  4602  4602 I art     : Explicit concurrent mark sweep GC freed 476(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 1.069ms total 50.218ms
08-12 15:13:10.917  1035  1098 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 15:13:10.931  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 15:13:10.944  3838  3838 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 15:13:10.944  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 15:13:10.954  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-12 15:13:10.955  2730  2730 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-12 15:13:10.956  2467  2621 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 15:13:11.018  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 15:13:11.019  6391  6391 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 15:13:11.025  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 15:13:11.026  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-12 15:13:11.028  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-12 15:13:11.028  2730  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 15:13:11.030  2730  2750 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 15:13:11.034  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , display: false
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , animation: false }
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , display: false
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , animation: false }
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , create_time: 1471007226523
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , display: false
08-12 15:13:11.036  2034  2034 I GBoardWebViewUtils: , animation: false }
08-12 15:13:11.050  2080  2080 I ConfigService: onCreate
08-12 15:13:11.051  2080  2080 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-12 15:13:11.059  2034  6809 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 15:13:11.063  4505  4505 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 15:13:11.063  4505  4505 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 15:13:11.063  4505  4505 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 15:13:11.063  4505  4505 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 15:13:11.064  4505  4505 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 15:13:11.064  4505  4505 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 15:13:11.064  4505  4505 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 15:13:11.064  4505  4505 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 15:13:11.064  4505  4505 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 15:13:11.064  4505  4505 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 15:13:11.064  4505  4505 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 15:13:11.064  4505  4505 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 15:13:11.066  2080  2080 I ConfigService: onBind returning update interface
08-12 15:13:11.076  2080  2080 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 15:13:11.076  2080  2080 I ConfigService: onBind returning config service
08-12 15:13:11.076  1035  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 15:13:11.078  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-12 15:13:11.082  1035  1938 V SIM_STK : Menu title from STK is T-Mobile
08-12 15:13:11.087  1817  1817 I ConfigFetchService: service connected
08-12 15:13:11.087  1817  1817 I ConfigClient: service connected
08-12 15:13:11.089  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 15:13:11.094  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-12 15:13:11.094  1869  1869 D SplitUIService: removed split : 
08-12 15:13:11.097  2080  2080 I ConfigService: onDestroy
08-12 15:13:11.103  1817  6813 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-12 15:13:11.106  1035  1035 I art     : Explicit concurrent mark sweep GC freed 42928(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 4.802ms total 206.823ms
08-12 15:13:11.108  1035  1123 I art     : WaitForGcToComplete blocked for 210.927ms for cause Explicit
08-12 15:13:11.148  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 15:13:11.173  1035  1035 D administrator: Handling package changes for user 0
,08-12 15:13:11.184  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-12 15:13:11.184  1869  1869 I SplitUIService: split app #11
08-12 15:13:11.199  5937  6820 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-12 15:13:11.211  1817  6821 I PeopleContactsSync: CP2 sync disabled
,08-12 15:13:11.216  1817  4774 I Icing   : doRemovePackageData com.test.thalitest
08-12 15:13:11.239  1817  6819 W GmsApplication: Using Auth Proxy for data requests.
,08-12 15:13:11.250  1817  6819 W GmsApplication: Using Auth Proxy for data requests.
,08-12 15:13:11.254  1035  1977 V SIM_STK : Menu title from STK is T-Mobile
08-12 15:13:11.254  1035  1977 V SIM_STK : Menu title from STK is T-Mobile
08-12 15:13:11.304  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 15:13:11.305  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 15:13:11.305  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 15:13:11.310  1035  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 15:13:11.313  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 15:13:11.313  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 15:13:11.315  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 15:13:11.318  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 15:13:11.320  1035  1652 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 15:13:11.320  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 15:13:11.321  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 15:13:11.323  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 15:13:11.324  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 15:13:11.326  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 15:13:11.335  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{92805cf u0 com.lge.launcher2/.Launcher t5} time:220446
,08-12 15:13:11.347  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 15:13:11.347  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 15:13:11.349  2034  2124 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 15:13:11.349  2034  2124 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 15:13:11.354  1035  1123 I art     : Explicit concurrent mark sweep GC freed 5471(306KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.581ms total 235.934ms
08-12 15:13:11.354  1035  1902 I art     : WaitForGcToComplete blocked for 329.662ms for cause Explicit
,08-12 15:13:11.366  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 15:13:11.367  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 15:13:11.368  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 15:13:11.374  1035  1785 V SIM_STK : Menu title from STK is T-Mobile
,08-12 15:13:11.378  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 15:13:11.390  2599  2599 D [Concierge]Service: onStartCommand(). Type : 8
08-12 15:13:11.390  2599  2599 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 15:13:11.392  2599  2599 D [Concierge]Service: Update widget ID : 11
08-12 15:13:11.394  2034  2034 D [Concierge]WidgetView: change position of spinner
08-12 15:13:11.395  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1471007591395
08-12 15:13:11.395  2599  2599 D [Concierge]Service: onStartCommand(). Type : 0
,08-12 15:13:11.417  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 113170026
08-12 15:13:11.417  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 15:13:11.417  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 15:13:11.421  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2cc8972e
08-12 15:13:11.421  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 15:13:11.422  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 15:13:11.422  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 15:13:11.424  6776  6776 D AndroidRuntime: Shutting down VM
08-12 15:13:11.429  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 15:13:11.430  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 15:13:11.430  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-12 15:13:11.432  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471007399231, New one : 1471007591395
08-12 15:13:11.432  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-12 15:13:11.433  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 15:13:11.433  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 15:13:11.435  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 15:13:11.436  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 15:13:11.437  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 15:13:11.439  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 15:13:11.440  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 15:13:11.441  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 15:13:11.441  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 15:13:11.462  1035  1902 I art     : Explicit concurrent mark sweep GC freed 5630(355KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.639ms total 107.528ms
,08-12 15:13:11.470  1602  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 15:13:11.470  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.472  1602  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 15:13:11.472  1602  1663 D KeyguardModel: createShortcutInfo...
,08-12 15:13:11.475  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 15:13:11.475  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 15:13:11.478  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 15:13:11.478  1602  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 15:13:11.479  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 15:13:11.479  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 15:13:11.481  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 15:13:11.482  1602  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 15:13:11.486  1602  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-12 15:13:11.486  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.487  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 15:13:11.491  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 15:13:11.492  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 15:13:11.494  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 15:13:11.494  1602  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 15:13:11.495  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 15:13:11.496  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 15:13:11.497  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 15:13:11.501  1602  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 15:13:11.501  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.502  6006  6006 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 15:13:11.513  1602  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 15:13:11.513  1602  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 15:13:11.513  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 15:13:11.513  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-12 15:13:11.515  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 15:13:11.515  1602  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 15:13:11.516  1602  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 15:13:11.516  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.517  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2fb74af7 time:220628
08-12 15:13:11.517  6490  6490 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 15:13:11.519  2372  6828 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 15:13:11.525  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-12 15:13:11.525  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 15:13:11.529  1602  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 15:13:11.529  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.532  1602  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 15:13:11.532  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.533  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 15:13:11.533  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 15:13:11.534  1995  1995 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 15:13:11.536  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 15:13:11.536  1602  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-12 15:13:11.538  1602  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 15:13:11.538  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.540  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 15:13:11.540  1602  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 15:13:11.541  1602  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 15:13:11.541  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.542  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 15:13:11.542  1602  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 15:13:11.543  1602  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 15:13:11.543  1602  1663 D KeyguardModel: createShortcutInfo...
08-12 15:13:11.550  6391  6391 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 15:13:11.577  1035  1785 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6830 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 15:13:11.580  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-12 15:13:11.580  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 15:13:11.649  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 15:13:11.650  6830  6830 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 15:13:11.650  6830  6830 W LG Account v2.2: No ProfileInfo entries
08-12 15:13:11.650  6830  6830 I LG Account v2.2: isEnabled: false
08-12 15:13:11.650  6830  6830 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Country: EU
08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Operator: OPEN
,08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Ranking support: false
08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Comfort support: false
08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Accessory: true
,08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Health device: true
08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Extra Pedometer: false
08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Blood glucose device: false
08-12 15:13:11.651  6830  6830 I Feature : [Lifetracker]Device Number: 3
08-12 15:13:11.652  6830  6830 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 15:13:11.695  2034  2867 I GBoardtInterface: onReloaded()
08-12 15:13:11.698  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-12 15:13:11.716  1035  1574 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6850 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-12 15:13:11.717  1035  1574 I ActivityManager: Killing 5902:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-12 15:13:11.750  1035  1785 W libprocessgroup: failed to open /acct/uid_10014/pid_5902/cgroup.procs: No such file or directory
,08-12 15:13:11.750  2730  2790 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 15:13:11.757  2730  2789 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 15:13:11.767  1906  1906 D ActionManagerService: notifyUserLog: 1000001
,08-12 15:13:11.768  2730  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 15:13:11.768  2730  4493 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 15:13:11.772  6850  6850 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 15:13:11.772  6850  6850 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 15:13:11.773  6850  6850 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 15:13:11.773  6850  6850 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 15:13:11.773  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-12 15:13:11.774  6850  6850 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 15:13:11.774  2730  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 15:13:11.775  2730  4493 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 15:13:11.775  2730  4493 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 15:13:11.775  6850  6850 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 15:13:11.775  2730  4493 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 15:13:11.776  2730  2789 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 15:13:11.778  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 15:13:11.778  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 15:13:11.781  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 15:13:11.781  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]

```
