#### Test 80912877ea0a40f_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-11 12:03:32.291  6691  6691 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 12:03:40.285  6779  6779 D AndroidRuntime: 
08-11 12:03:40.285  6779  6779 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 12:03:40.291  6779  6779 D AndroidRuntime: CheckJNI is OFF
08-11 12:03:40.493  6779  6779 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 12:03:40.503  1040  1963 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 12:03:40.518  1927  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 12:03:40.523  1040  1963 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 12:03:40.525  1040  1963 D ActivityManager: setTaskToReturnTo : TaskRecord{1943db0c #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 12:03:40.525  1040  1963 D ActivityManager: setTaskToReturnTo : TaskRecord{1943db0c #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 12:03:40.527  1040  1963 D WindowStateEx: AppWindowTokenEx init.. 
08-11 12:03:40.527   332   342 E GBMv2   : DFP En is all cleared set to be enabled
08-11 12:03:40.556  1040  1963 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6794 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 12:03:40.558  6779  6779 D AndroidRuntime: Shutting down VM
08-11 12:03:40.610  1927  3955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 12:03:40.610  1927  3955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13cc230a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 12:03:40.611  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 12:03:40.611  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{454277b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 12:03:40.667  6794  6794 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 12:03:40.759  6794  6794 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-11 12:03:40.787  6794  6794 I LibraryLoader: Loading: webviewchromium
,08-11 12:03:40.796  6794  6794 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 6898-6909)
08-11 12:03:40.797  6794  6794 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:03:40.831  6794  6794 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c384f48}
,08-11 12:03:40.832  6794  6794 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:03:40.833  6794  6794 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 12:03:40.844  6794  6794 I BrowserStartupController: Initializing chromium process, renderers=0
,08-11 12:03:40.845  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:03:40.857  6794  6794 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-11 12:03:40.858  6794  6794 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-11 12:03:40.858  6794  6794 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-11 12:03:40.859   315  2152 V AudioPolicyService: registerClient() client 0xb558a400, uid 10118
08-11 12:03:40.873  1040  1118 D BluetoothManagerService: Message: 20
08-11 12:03:40.873  1040  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6e03f36:true
,08-11 12:03:40.880  6794  6794 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:03:40.880  6794  6794 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:03:40.880  6794  6794 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:03:40.880  6794  6794 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:03:40.880  6794  6794 I Adreno-EGL: Remote Branch: 
08-11 12:03:40.880  6794  6794 I Adreno-EGL: Local Patches: 
08-11 12:03:40.880  6794  6794 I Adreno-EGL: Reconstruct Branch: 
08-11 12:03:40.971  6794  6835 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-11 12:03:40.973  6794  6794 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 12:03:40.993  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 12:03:40.999  6794  6794 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 12:03:41.002  6794  6794 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 12:03:41.005  6794  6794 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 12:03:41.005  6794  6794 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-11 12:03:41.018  6794  6794 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 12:03:41.024  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:03:41.024  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 12:03:41.059  6794  6850 D OpenGLRenderer: Render dirty regions requested: true
08-11 12:03:41.059  6794  6850 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 12:03:41.070  6794  6850 D OpenGLRenderer: Enabling debug mode 0
,08-11 12:03:41.077  6794  6794 D Atlas   : Validating map...
08-11 12:03:41.088  1040  1057 D SplitWindow: check instance of lgWin Window{15bff40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:03:41.131  6794  6848 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:03:41.131  6794  6848 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:03:41.234  1040  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +625ms (total +706ms)
,08-11 12:03:41.235  1040  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{25ea1c55 u0 com.test.thalitest/.MainActivity t6} time:197348
,08-11 12:03:41.243  6794  6794 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29c8feb7 time:197356
08-11 12:03:41.341  6794  6794 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 12:03:41.438  6794  6848 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 12:03:41.438  6794  6848 I chromium: 
,08-11 12:03:41.576  6794  6861 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435040256
,08-11 12:03:41.588  6794  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 12:03:41.588  6794  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 12:03:41.588  6794  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 12:03:41.588  6794  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 12:03:41.588  6794  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 12:03:41.589  6794  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5cd5cb added. We now have 1 listener(s)
08-11 12:03:41.595  1040  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:03:41.597  6794  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 12:03:41.599  6794  6861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:03:41.600  6794  6794 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 12:03:41.600  6794  6794 I chromium: 
,08-11 12:03:41.600  6794  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 12:03:41.601  6794  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:03:41.609   332   344 E GBMv2   : DFP En is all cleared set to be enabled
08-11 12:03:41.609   332   344 E GBMv2   : Set value is all cleared set the max
08-11 12:03:41.609   332   344 I GBMv2   : DFP Enabled. Ignore VFP set
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 12:03:41.610  6794  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c76466 added. We now have 1 listener(s)
,08-11 12:03:41.611  6794  6861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:03:41.615  1040  1527 D WifiService: New client listening to asynchronous messages
,08-11 12:03:41.621  6794  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:03:41.621  6794  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 12:03:41.623  6794  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 12:03:41.623  6794  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 12:03:41.623  6794  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 12:03:41.629  6794  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:03:41.629  1040  1770 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:03:41.631  6794  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-11 12:03:41.644  6794  6861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:03:41.646  6794  6861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:03:41.646  6794  6861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 12:03:41.646  6794  6861 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:03:41.648  6794  6861 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 12:03:41.649  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:03:41.651  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:03:41.702  6794  6794 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 12:03:42.271  6794  6864 W jxcore-log: Initializing JXcore engine
08-11 12:03:42.271  6794  6864 W jxcore-log: JXcore engine is ready
,08-11 12:03:42.303  6864  6864 W Thread-776: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[6094]" dev="sockfs" ino=6094 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-11 12:03:42.303  6864  6864 W Thread-776: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-11 12:03:42.303  6864  6864 W Thread-776: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9565]" dev="sockfs" ino=9565 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 12:03:42.303  6864  6864 W Thread-776: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-11 12:03:42.303  6864  6864 W Thread-776: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33194]" dev="sockfs" ino=33194 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-11 12:03:42.319  6794  6864 W jxcore-log: Starting JXcore engine
08-11 12:03:42.395  6794  6864 W jxcore-log: Platform android
08-11 12:03:42.395  6794  6864 W jxcore-log: 
08-11 12:03:42.395  6794  6864 W jxcore-log: Process ARCH arm
08-11 12:03:42.395  6794  6864 W jxcore-log: 
,08-11 12:03:42.567  6794  6864 I jxcore-log: JXcore Cordova bridge is ready!
08-11 12:03:42.567  6794  6864 I jxcore-log: 
,08-11 12:03:42.568  6794  6864 W jxcore-log: JXcore engine is started
08-11 12:03:42.574  6794  6861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 12:03:42.576  6794  6794 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 12:03:52.389  6794  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 12:03:52.389  6794  6864 I jxcore-log: 
,08-11 12:03:52.392  6794  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 12:03:52.392  6794  6864 I jxcore-log: 
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:03:52.397  6794  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:03:52.399  6794  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:03:52.402  6794  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 12:03:52.402  6794  6864 I jxcore-log: 
,08-11 12:03:52.404  6794  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 12:03:52.404  6794  6864 I jxcore-log: 
08-11 12:03:52.728  6794  6864 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 12:03:52.728  6794  6864 I jxcore-log: Failed to execute UT.
08-11 12:03:52.728  6794  6864 I jxcore-log: 
08-11 12:03:52.728  6794  6864 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 12:03:52.728  6794  6864 I jxcore-log: 
08-11 12:03:52.730  6794  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:03:52.730  6794  6864 I jxcore-log: 
,08-11 12:03:52.754  6794  6794 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 12:03:53.068  6865  6865 D AndroidRuntime: 
08-11 12:03:53.068  6865  6865 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 12:03:53.072  6865  6865 D AndroidRuntime: CheckJNI is OFF
08-11 12:03:53.227  6865  6865 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 12:03:53.249  1040  1110 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-11 12:03:53.249  1040  1110 I ActivityManager: Killing 6794:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-11 12:03:53.287  1040  1944 I WindowState: WIN DEATH: Window{15bff40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:03:53.288  1040  1527 D WifiService: Client connection lost with reason: 4
08-11 12:03:53.296  1040  1944 D InputDispatcher: Window went away: Window{15bff40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:03:53.362  1040  1110 I ActivityManager:   Force finishing activity ActivityRecord{25ea1c55 u0 com.test.thalitest/.MainActivity t6}
,08-11 12:03:53.403   332   342 E GBMv2   : DFP En is all cleared set to be enabled
08-11 12:03:53.403  1040  1713 W ActivityManager: Spurious death for ProcessRecord{dcf9096 6794:com.test.thalitest/u0a118}, curProc for 6794: null
08-11 12:03:53.404  1040  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-11 12:03:53.410  1040  1124 I ActivityManager:   Force finishing activity ActivityRecord{25ea1c55 u0 com.test.thalitest/.MainActivity t6 f}
08-11 12:03:53.411  1040  1124 W ActivityManager: Duplicate finish request for ActivityRecord{25ea1c55 u0 com.test.thalitest/.MainActivity t6 f}
,08-11 12:03:53.468  4608  4608 I art     : Explicit concurrent mark sweep GC freed 485(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 579us total 37.591ms
,08-11 12:03:53.471  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-11 12:03:53.472  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-11 12:03:53.474  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-11 12:03:53.474  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ffe7998 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 12:03:53.475  1927  3955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-11 12:03:53.475  1927  3955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2bf645f1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 12:03:53.477  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-11 12:03:53.478  2019  2128 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-11 12:03:53.482  1040  1108 W InputMethodInfo: Duplicated subtype definition found: , voice
08-11 12:03:53.482  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-11 12:03:53.486  1040  1436 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 12:03:53.496  3848  3848 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-11 12:03:53.497  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-11 12:03:53.497  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 12:03:53.507  3801  3801 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-11 12:03:53.519  2477  2589 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 12:03:53.539  1040  1945 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:03:53.556  1890  1890 D ActionManagerService: notifyUserLog: 1000003
,08-11 12:03:53.557  3801  4507 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-11 12:03:53.557  4486  4486 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 12:03:53.558  4486  4486 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 12:03:53.558  4486  4486 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 12:03:53.558  4486  4486 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-11 12:03:53.558  4486  4486 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:03:53.558  4486  4486 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:03:53.561  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-11 12:03:53.563  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 12:03:53.570  6490  6490 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-11 12:03:53.570  4486  4486 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:03:53.570  4486  4486 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:03:53.570  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:03:53.570  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:03:53.570  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:03:53.570  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:03:53.573  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-11 12:03:53.600  1040  1040 I art     : Explicit concurrent mark sweep GC freed 40949(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.920ms total 166.913ms
08-11 12:03:53.604  1040  1560 I art     : WaitForGcToComplete blocked for 42.694ms for cause Explicit
08-11 12:03:53.614  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 12:03:53.614  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-11 12:03:53.619  1854  1854 D SplitUIManager: split_name #11 / not available #0
,08-11 12:03:53.619  1854  1854 D SplitUIService: removed split : 
08-11 12:03:53.647  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-11 12:03:53.647  1854  1854 I SplitUIService: split app #11
,08-11 12:03:53.667  1040  1040 D administrator: Handling package changes for user 0
,08-11 12:03:53.705  1040  1058 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:03:53.705  1040  1058 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:03:53.769  1040  1560 I art     : Explicit concurrent mark sweep GC freed 5455(443KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.137ms total 153.356ms
,08-11 12:03:53.770  1040  1124 I art     : WaitForGcToComplete blocked for 200.421ms for cause Explicit
08-11 12:03:53.771  1588  1639 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 12:03:53.771  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.781  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-11 12:03:53.788  1588  1639 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 12:03:53.788  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.793  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-11 12:03:53.793  1040  1872 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-11 12:03:53.793  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-11 12:03:53.793  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 12:03:53.793  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-11 12:03:53.793  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 12:03:53.793  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 12:03:53.793  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-11 12:03:53.793  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:03:53.794  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 12:03:53.794  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 12:03:53.794  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 12:03:53.794  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:03:53.794  3848  3848 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 12:03:53.798  1890  1890 D ActionManagerService: notifyUserLog: 1000004
08-11 12:03:53.799  3801  4507 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-11 12:03:53.799  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-11 12:03:53.800  2194  2194 I ConfigService: onCreate
08-11 12:03:53.800  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 12:03:53.802  1588  1639 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 12:03:53.802  1588  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:03:53.803  1588  1639 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 12:03:53.804  2194  2194 I ConfigService: onBind returning update interface
08-11 12:03:53.804  1588  1639 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 12:03:53.807  3801  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 12:03:53.807  1588  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:03:53.807  1588  1639 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-11 12:03:53.810  1588  1639 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 12:03:53.810  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.811  1040  1040 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 12:03:53.811  1040  1040 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 12:03:53.811  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 12:03:53.811  2194  2194 I ConfigService: onBind returning config service
08-11 12:03:53.811  1040  1040 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 12:03:53.812  1040  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-11 12:03:53.814  1588  1639 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 12:03:53.814  1588  1639 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:03:53.814  1040  1993 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:03:53.815  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-11 12:03:53.816  1588  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:03:53.816  1588  1639 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , display: false
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , animation: false }
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , display: false
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , animation: false }
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , create_time: 1470393743569
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , display: false
08-11 12:03:53.817  2019  2019 I GBoardWebViewUtils: , animation: false }
08-11 12:03:53.819  2019  6894 D WallpaperManager: suggestDesiredDi,mensions(2880, 2560) by package(com.lge.launcher2)
08-11 12:03:53.823  1588  1639 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 12:03:53.823  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.824  1801  1801 I ConfigFetchService: service connected
08-11 12:03:53.828  1588  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:03:53.828  1588  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 12:03:53.828  1588  1639 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 12:03:53.828  1588  1639 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 12:03:53.829  1588  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:03:53.829  1588  1639 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 12:03:53.829  1801  6895 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-11 12:03:53.830  2194  2194 I ConfigService: onDestroy
08-11 12:03:53.831  1588  1639 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 12:03:53.831  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.837  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 12:03:53.837  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-11 12:03:53.842  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-11 12:03:53.842  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 12:03:53.851  1588  1639 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 12:03:53.851  1588  1639 D KeyguardModel: createShortcutInfo...
,08-11 12:03:53.858  1588  1639 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 12:03:53.858  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.860  1588  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:03:53.860  1588  1639 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 12:03:53.862  1588  1639 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 12:03:53.862  1588  1639 D KeyguardModel: createShortcutInfo...
,08-11 12:03:53.864  1588  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:03:53.864  1588  1639 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 12:03:53.865  1588  1639 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 12:03:53.865  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.867  1588  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:03:53.867  1588  1639 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 12:03:53.869  1588  1639 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 12:03:53.869  1588  1639 D KeyguardModel: createShortcutInfo...
08-11 12:03:53.895  1801  6903 I PeopleContactsSync: CP2 sync disabled
,08-11 12:03:53.897  6010  6901 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-11 12:03:53.902  1801  4782 I Icing   : doRemovePackageData com.test.thalitest
08-11 12:03:53.904  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-11 12:03:53.914  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-11 12:03:53.914  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-11 12:03:53.919  1801  6902 W GmsApplication: Using Auth Proxy for data requests.
08-11 12:03:53.928  1801  6902 W GmsApplication: Using Auth Proxy for data requests.
08-11 12:03:53.938  6075  6075 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-11 12:03:53.949  6600  6600 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 12:03:53.953  2330  6906 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 12:03:53.959  1981  1981 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 12:03:53.959  1981  1981 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-11 12:03:53.969  1981  1981 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-11 12:03:53.975  6490  6490 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 12:03:53.995  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-11 12:03:54.001  1040  1945 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6908 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-11 12:03:54.001  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:03:54.003  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-11 12:03:54.005  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-11 12:03:54.006  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-11 12:03:54.007  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-11 12:03:54.020  1040  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d4920d3 u0 com.lge.launcher2/.Launcher t5} time:210133
,08-11 12:03:54.029  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-11 12:03:54.029  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:03:54.029  2019  2252 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-11 12:03:54.029  2019  2252 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-11 12:03:54.042  1040  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 12:03:54.046  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-11 12:03:54.046  1040  1124 I art     : Explicit concurrent mark sweep GC freed 10026(609KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 6.918ms total 275.782ms
08-11 12:03:54.046  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 12:03:54.047  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:03:54.054  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-11 12:03:54.055  2662  2662 D [Concierge]Service: onStartCommand(). Type : 8
08-11 12:03:54.055  2662  2662 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-11 12:03:54.055  1040  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-11 12:03:54.056  2662  2662 D [Concierge]Service: Update widget ID : 11
08-11 12:03:54.058  2019  2019 D [Concierge]WidgetView: change position of spinner
08-11 12:03:54.059  2662  2662 D [Concierge]Service: onStartCommand(). Type : 0
08-11 12:03:54.059  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1470909834059
08-11 12:03:54.082  6908  6908 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-11 12:03:54.082  6908  6908 W LG Account v2.2: No ProfileInfo entries
08-11 12:03:54.082  6908  6908 I LG Account v2.2: isEnabled: false
08-11 12:03:54.082  6908  6908 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Country: EU
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Operator: OPEN
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Ranking support: false
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Comfort support: false
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Accessory: true
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Health device: true
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Extra Pedometer: false
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Blood glucose device: false
08-11 12:03:54.083  6908  6908 I Feature : [Lifetracker]Device Number: 3
08-11 12:03:54.084  6908  6908 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-11 12:03:54.107  1040  1907 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6930 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 12:03:54.108  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 330058447
,08-11 12:03:54.109  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-11 12:03:54.109  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-11 12:03:54.110  6865  6865 D AndroidRuntime: Shutting down VM
08-11 12:03:54.112  1040  1907 I ActivityManager: Killing 6286:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-11 12:03:54.112  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@449e9f3
08-11 12:03:54.112  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-11 12:03:54.113  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 12:03:54.113  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:03:54.119  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-11 12:03:54.120  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-11 12:03:54.120  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-11 12:03:54.149  1040  2000 W libprocessgroup: failed to open /acct/uid_10014/pid_6286/cgroup.procs: No such file or directory
,08-11 12:03:54.150  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470909652629, New one : 1470909834059
08-11 12:03:54.150  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-11 12:03:54.150  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 12:03:54.156  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 12:03:54.158  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:03:54.161  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-11 12:03:54.163  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-11 12:03:54.166  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-11 12:03:54.168  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-11 12:03:54.168  6930  6930 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:03:54.169  6930  6930 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-11 12:03:54.169  6930  6930 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:03:54.169  6930  6930 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-11 12:03:54.170  6930  6930 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 12:03:54.170  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-11 12:03:54.171  6930  6930 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-11 12:03:54.172  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:03:54.172  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 12:03:54.216  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-11 12:03:54.229  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-11 12:03:54.230  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-11 12:03:54.232  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:03:54.251  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3252ff38 time:210364
,08-11 12:03:54.277  6930  6930 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-11 12:03:54.285  6930  6930 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-11 12:03:54.285  6930  6930 D HideNavigationAppsReceiver: replacing : false
08-11 12:03:54.289  6930  6930 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
,08-11 12:03:54.290  6930  6930 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-11 12:03:54.290  6930  6930 D ButtonCombinationReceiver: replacing : false
,08-11 12:03:54.304  1040  1770 I ActivityManager: Killing 6560:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-11 12:03:54.393  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-11 12:03:54.431  1040  1872 W libprocessgroup: failed to open /acct/uid_10008/pid_6560/cgroup.procs: No such file or directory
,08-11 12:03:54.435  2019  2931 I GBoardtInterface: onReloaded()
08-11 12:03:54.438  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-11 12:03:54.442  3801  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-11 12:03:54.446  4608  6949 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-11 12:03:54.495  1040  1945 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 12:03:54.499  3801  4503 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 12:03:54.510  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-11 12:03:54.512  3801  4507 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 12:03:54.512  3801  4507 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 12:03:54.513  1040  1770 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:03:54.513   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 313us total 15.986ms

```
