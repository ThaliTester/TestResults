#### Test 797510159e44f0b_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 22:00:34.076  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 22:00:34.076  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,--------- beginning of system
08-12 22:00:34.093  1939  2070 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 22:00:34.093  1939  2070 D LEDHandler: Battery Level Remaining: 100%
08-12 22:00:34.093  1939  2070 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
08-12 22:00:34.096  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
08-12 22:00:34.097  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 22:00:34.098  1032  1544 D WifiController: battery changed pluggedType: 2
08-12 22:00:34.099  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 22:00:34.102  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 22:00:34.102  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 22:00:34.103  3863  3982 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 22:00:34.109  6567  6567 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-12 22:00:34.374  6704  6704 D AndroidRuntime: 
08-12 22:00:34.374  6704  6704 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 22:00:34.377  6704  6704 D AndroidRuntime: CheckJNI is OFF
08-12 22:00:34.504  6704  6704 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 22:00:34.509  1032  2028 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 22:00:34.519  1939  1954 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 22:00:34.523  1032  2028 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 22:00:34.524  1032  2028 D ActivityManager: setTaskToReturnTo : TaskRecord{18d1c621 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 22:00:34.524  1032  2028 D ActivityManager: setTaskToReturnTo : TaskRecord{18d1c621 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 22:00:34.525  1032  2028 D WindowStateEx: AppWindowTokenEx init.. 
08-12 22:00:34.526   339   351 E GBMv2   : DFP En is all cleared set to be enabled
08-12 22:00:34.572  1032  2028 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6724 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 22:00:34.574  6704  6704 D AndroidRuntime: Shutting down VM
08-12 22:00:34.619  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 22:00:34.619  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33fa684b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 22:00:34.620  1939  3973 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 22:00:34.620  1939  3973 D SplitWindowPolicy: topRunningActivity=ActivityInfo{22677228 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 22:00:34.697  6724  6724 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 22:00:34.780  6724  6724 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 22:00:34.791  6724  6724 I LibraryLoader: Loading: webviewchromium
08-12 22:00:34.795  6724  6724 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9396-9401)
08-12 22:00:34.795  6724  6724 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 22:00:34.812  6724  6724 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f6beb31}
,08-12 22:00:34.814  6724  6724 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 22:00:34.814  6724  6724 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 22:00:34.823  6724  6724 I BrowserStartupController: Initializing chromium process, renderers=0
08-12 22:00:34.824  6724  6724 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:00:34.833  6724  6724 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-12 22:00:34.836  6724  6724 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 22:00:34.836  6724  6724 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 22:00:34.841   319  2151 V AudioPolicyService: registerClient() client 0xb558adc0, uid 10118
08-12 22:00:34.846  1032  1097 D BluetoothManagerService: Message: 20
08-12 22:00:34.846  1032  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27da09a3:true
,08-12 22:00:34.859  6724  6724 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 22:00:34.859  6724  6724 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 22:00:34.859  6724  6724 I Adreno-EGL: Build Date: 12/12/14 금
08-12 22:00:34.859  6724  6724 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 22:00:34.859  6724  6724 I Adreno-EGL: Remote Branch: 
08-12 22:00:34.859  6724  6724 I Adreno-EGL: Local Patches: 
08-12 22:00:34.859  6724  6724 I Adreno-EGL: Reconstruct Branch: 
,08-12 22:00:34.936  6724  6754 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-12 22:00:34.939  6724  6724 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-12 22:00:34.959  6724  6724 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 22:00:34.966  6724  6724 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 22:00:34.969  6724  6724 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 22:00:34.973  6724  6724 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 22:00:34.973  6724  6724 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 22:00:34.989  6724  6724 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 22:00:34.997  6724  6724 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:00:34.997  6724  6724 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 22:00:35.026  6724  6766 D OpenGLRenderer: Render dirty regions requested: true
08-12 22:00:35.033  6724  6766 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 22:00:35.040  6724  6766 D OpenGLRenderer: Enabling debug mode 0
,08-12 22:00:35.050  6724  6724 D Atlas   : Validating map...
08-12 22:00:35.054  1032  1646 D SplitWindow: check instance of lgWin Window{1aa93985 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:00:35.096  6724  6764 D LgDataFeature: LgDataFeature() Constructor: none
08-12 22:00:35.096  6724  6764 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 22:00:35.200  1032  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +582ms (total +673ms)
08-12 22:00:35.201  1032  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a359a46 u0 com.test.thalitest/.MainActivity t6} time:309807
,08-12 22:00:35.205  6724  6724 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28123fb4 time:309811
08-12 22:00:35.322  6724  6724 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 22:00:35.322  6724  6724 I chromium: 
,08-12 22:00:35.368  6724  6724 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 22:00:35.527  6724  6777 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-12 22:00:35.547  6724  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 22:00:35.547  6724  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 22:00:35.547  6724  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 22:00:35.547  6724  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 22:00:35.547  6724  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 22:00:35.547  6724  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11f8b638 added. We now have 1 listener(s)
08-12 22:00:35.556  1032  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 22:00:35.562  6724  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-12 22:00:35.566  6724  6777 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 22:00:35.571  6724  6777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 22:00:35.573  6724  6777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 22:00:35.588  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 22:00:35.589  6724  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b061d77 added. We now have 1 listener(s)
,08-12 22:00:35.590  6724  6777 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 22:00:35.597  1032  1544 D WifiService: New client listening to asynchronous messages
08-12 22:00:35.602  6724  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 22:00:35.602  6724  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 22:00:35.604  6724  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 22:00:35.604  6724  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 22:00:35.604  6724  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 22:00:35.610  6724  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 22:00:35.610  1032  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 22:00:35.611  6724  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 22:00:35.622  6724  6777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:00:35.622  6724  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 22:00:35.622  6724  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 22:00:35.622  6724  6777 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 22:00:35.625  6724  6777 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 22:00:35.626  6724  6724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 22:00:35.628  6724  6724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 22:00:35.685  6724  6764 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 22:00:35.685  6724  6764 I chromium: 
,08-12 22:00:35.753  6724  6724 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 22:00:36.247   339   353 E GBMv2   : DFP En is all cleared set to be enabled
08-12 22:00:36.247   339   353 E GBMv2   : Set value is all cleared set the max
08-12 22:00:36.247   339   353 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 22:00:36.605  6724  6780 W jxcore-log: Initializing JXcore engine
08-12 22:00:36.605  6724  6780 W jxcore-log: JXcore engine is ready
,08-12 22:00:36.626  6780  6780 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10329]" dev="sockfs" ino=10329 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 22:00:36.626  6780  6780 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-12 22:00:36.636  6780  6780 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7628]" dev="sockfs" ino=7628 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 22:00:36.636  6780  6780 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 22:00:36.636  6780  6780 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32955]" dev="sockfs" ino=32955 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 22:00:36.659  6724  6780 W jxcore-log: Starting JXcore engine
,08-12 22:00:36.734  6724  6780 W jxcore-log: Platform android
08-12 22:00:36.734  6724  6780 W jxcore-log: 
08-12 22:00:36.734  6724  6780 W jxcore-log: Process ARCH arm
08-12 22:00:36.734  6724  6780 W jxcore-log: 
,08-12 22:00:36.966  6724  6780 I jxcore-log: JXcore Cordova bridge is ready!
08-12 22:00:36.966  6724  6780 I jxcore-log: 
08-12 22:00:36.966  6724  6780 W jxcore-log: JXcore engine is started
,08-12 22:00:36.975  6724  6777 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 22:00:36.977  6724  6724 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 22:00:52.776  6724  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 22:00:52.776  6724  6780 I jxcore-log: 
,08-12 22:00:52.779  6724  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 22:00:52.779  6724  6780 I jxcore-log: 
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:00:52.782  6724  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 22:00:52.784  6724  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 22:00:52.786  6724  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 22:00:52.786  6724  6780 I jxcore-log: 
08-12 22:00:52.788  6724  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 22:00:52.788  6724  6780 I jxcore-log: 
08-12 22:00:53.126  6724  6780 I jxcore-log: Unit Test app is loaded
08-12 22:00:53.126  6724  6780 I jxcore-log: 
,08-12 22:00:53.145  6724  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 22:00:53.145  6724  6780 I jxcore-log: 
08-12 22:00:53.145  6724  6724 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 22:00:53.150  6724  6780 I jxcore-log: My device name is: LGE-LG-D855
08-12 22:00:53.150  6724  6780 I jxcore-log: 
08-12 22:00:55.545  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 22:00:55.545  6724  6780 I jxcore-log: 
,08-12 22:00:56.185  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 22:00:56.185  6724  6780 I jxcore-log: 
,08-12 22:00:56.212  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 22:00:56.212  6724  6780 I jxcore-log: 
,08-12 22:00:57.558  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 22:00:57.558  6724  6780 I jxcore-log: 
,08-12 22:00:57.788  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 22:00:57.788  6724  6780 I jxcore-log: 
08-12 22:00:57.793  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 22:00:57.793  6724  6780 I jxcore-log: 
,08-12 22:00:57.800  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 22:00:57.800  6724  6780 I jxcore-log: 
08-12 22:00:57.816  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 22:00:57.816  6724  6780 I jxcore-log: 
08-12 22:00:57.820  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 22:00:57.820  6724  6780 I jxcore-log: 
,08-12 22:00:58.485  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 22:00:58.485  6724  6780 I jxcore-log: 
,08-12 22:00:58.499  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 22:00:58.499  6724  6780 I jxcore-log: 
08-12 22:00:58.507  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 22:00:58.507  6724  6780 I jxcore-log: 
08-12 22:00:58.513  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 22:00:58.513  6724  6780 I jxcore-log: 
,08-12 22:00:58.561  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 22:00:58.561  6724  6780 I jxcore-log: 
,08-12 22:00:58.616  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 22:00:58.616  6724  6780 I jxcore-log: 
,08-12 22:00:58.625  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 22:00:58.625  6724  6780 I jxcore-log: 
,08-12 22:00:58.791  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 22:00:58.791  6724  6780 I jxcore-log: 
,08-12 22:00:58.820  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 22:00:58.820  6724  6780 I jxcore-log: 
,08-12 22:00:58.826  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 22:00:58.826  6724  6780 I jxcore-log: 
08-12 22:00:58.832  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 22:00:58.832  6724  6780 I jxcore-log: 
08-12 22:00:58.851  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 22:00:58.851  6724  6780 I jxcore-log: 
,08-12 22:00:58.933  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 22:00:58.933  6724  6780 I jxcore-log: 
,08-12 22:00:58.947  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 22:00:58.947  6724  6780 I jxcore-log: 
,08-12 22:00:58.975  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 22:00:58.975  6724  6780 I jxcore-log: 
,08-12 22:00:58.989  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 22:00:58.989  6724  6780 I jxcore-log: 
,08-12 22:00:59.007  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 22:00:59.007  6724  6780 I jxcore-log: 
,08-12 22:00:59.042  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 22:00:59.042  6724  6780 I jxcore-log: 
,08-12 22:00:59.047  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 22:00:59.047  6724  6780 I jxcore-log: 
08-12 22:00:59.254  6724  6780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 22:00:59.254  6724  6780 I jxcore-log: 
,08-12 22:00:59.263  6724  6780 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-12 22:00:59.264  6724  6780 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 22:00:59.264  6724  6780 I jxcore-log: 
08-12 22:01:00.055  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 22:01:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 22:01:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 22:01:00.056  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 22:01:00.068  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 22:01:00.068  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 22:01:00.070  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 22:01:00.072  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 22:01:00.218  1032  3545 I LocationManagerService: remove 292364ab
,08-12 22:01:00.226  1032  3545 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 22:01:00.226  1032  3545 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 22:01:00.228  1032  3545 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 22:01:00.230  1032  3545 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 22:01:00.232  1032  3545 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 22:01:04.029  6724  6780 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 22:01:04.029  6724  6780 I jxcore-log: 
,08-12 22:01:04.361  6792  6792 D AndroidRuntime: 
08-12 22:01:04.361  6792  6792 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 22:01:04.368  6792  6792 D AndroidRuntime: CheckJNI is OFF
08-12 22:01:04.498  6792  6792 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 22:01:04.509  1032  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 22:01:04.510  1032  1092 I ActivityManager: Killing 6724:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-12 22:01:04.557  1032  2003 I WindowState: WIN DEATH: Window{1aa93985 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:01:04.559  1032  1544 D WifiService: Client connection lost with reason: 4
08-12 22:01:04.562  1032  2003 D InputDispatcher: Window went away: Window{1aa93985 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:01:04.733  1032  1092 I ActivityManager:   Force finishing activity ActivityRecord{1a359a46 u0 com.test.thalitest/.MainActivity t6}
,08-12 22:01:04.756   339   351 E GBMv2   : DFP En is all cleared set to be enabled
08-12 22:01:04.758  1032  2028 W ActivityManager: Spurious death for ProcessRecord{3e151583 6724:com.test.thalitest/u0a118}, curProc for 6724: null
,08-12 22:01:04.764  1032  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 22:01:04.768  1032  1103 I ActivityManager:   Force finishing activity ActivityRecord{1a359a46 u0 com.test.thalitest/.MainActivity t6 f}
08-12 22:01:04.768  1032  1103 W ActivityManager: Duplicate finish request for ActivityRecord{1a359a46 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 22:01:04.802  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 22:01:04.802  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 22:01:04.803  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1dc3fb41 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 22:01:04.805  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 22:01:04.805  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3845f8e6 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 22:01:04.806  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-12 22:01:04.810  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 22:01:04.811  2032  2103 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-12 22:01:04.814  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 22:01:04.815  1032  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 22:01:04.828  2462  2599 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 22:01:04.829  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-12 22:01:04.829  3863  3863 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
,08-12 22:01:04.829  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 22:01:04.829  1032  1429 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 22:01:04.831  3814  3814 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-12 22:01:04.845  4593  4593 I art     : Explicit concurrent mark sweep GC freed 445(29KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 635us total 68.645ms
,08-12 22:01:04.892  4480  4480 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 22:01:04.892  4480  4480 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 22:01:04.892  4480  4480 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 22:01:04.892  4480  4480 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 22:01:04.892  4480  4480 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 22:01:04.892  4480  4480 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 22:01:04.892  4480  4480 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:01:04.892  4480  4480 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 22:01:04.892  4480  4480 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:01:04.892  4480  4480 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-12 22:01:04.892  4480  4480 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 22:01:04.892  4480  4480 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 22:01:04.897  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 22:01:04.901  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-12 22:01:04.904  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-12 22:01:04.914  2171  2171 I ConfigService: onCreate
08-12 22:01:04.918  1032  1575 V SIM_STK : Menu title from STK is T-Mobile
,08-12 22:01:04.924  2171  2171 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 22:01:04.930  2171  2171 I ConfigService: onBind returning update interface
08-12 22:01:04.936  2171  2171 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 22:01:04.936  2171  2171 I ConfigService: onBind returning config service
,08-12 22:01:04.939  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 22:01:04.948  1815  1815 I ConfigFetchService: service connected
08-12 22:01:04.948  1867  1867 D SplitUIManager: split_name #11 / not available #0
,08-12 22:01:04.948  1815  1815 I ConfigClient: service connected
08-12 22:01:04.948  1867  1867 D SplitUIService: removed split : 
,08-12 22:01:04.954  2171  2171 I ConfigService: onDestroy
08-12 22:01:04.956  1815  6827 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 22:01:04.985  1032  1032 I art     : Explicit concurrent mark sweep GC freed 38050(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.259ms total 193.862ms
,08-12 22:01:04.986  1032  1103 I art     : WaitForGcToComplete blocked for 184.432ms for cause Explicit
,08-12 22:01:04.992  5903  6833 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-12 22:01:04.997  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-12 22:01:04.997  1867  1867 I SplitUIService: split app #11
08-12 22:01:05.010  1815  6834 I PeopleContactsSync: CP2 sync disabled
,08-12 22:01:05.016  1815  4644 I Icing   : doRemovePackageData com.test.thalitest
08-12 22:01:05.024  1815  6832 W GmsApplication: Using Auth Proxy for data requests.
,08-12 22:01:05.028  1815  6832 W GmsApplication: Using Auth Proxy for data requests.
08-12 22:01:05.057  1032  1938 V SIM_STK : Menu title from STK is T-Mobile
08-12 22:01:05.057  1032  1938 V SIM_STK : Menu title from STK is T-Mobile
,08-12 22:01:05.124  1032  1032 D administrator: Handling package changes for user 0
,08-12 22:01:05.132  1032  2028 V SIM_STK : Menu title from STK is T-Mobile
08-12 22:01:05.135  1032  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 22:01:05.136  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 22:01:05.165  1032  1103 I art     : Explicit concurrent mark sweep GC freed 5754(379KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.752ms total 179.347ms
,08-12 22:01:05.166  1032  1784 I art     : WaitForGcToComplete blocked for 353.839ms for cause Explicit
08-12 22:01:05.205  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 22:01:05.205  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 22:01:05.205  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 22:01:05.212  1032  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 22:01:05.245  1032  1784 I art     : Explicit concurrent mark sweep GC freed 5370(306KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.931ms total 79.014ms
08-12 22:01:05.247  1032  1092 W ActivityManager: Activity pause timeout for ActivityRecord{3b98b86c u0 com.lge.launcher2/.Launcher t5}
,08-12 22:01:05.248  1602  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 22:01:05.248  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.250  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 22:01:05.250  1602  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 22:01:05.250  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.251  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 22:01:05.251  1903  1903 D ActionManagerService: notifyUserLog: 1000003
08-12 22:01:05.252  3814  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 22:01:05.255  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 22:01:05.255  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 22:01:05.255  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 22:01:05.255  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 22:01:05.256  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 22:01:05.257  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:01:05.257  1602  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 22:01:05.258  1602  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 22:01:05.258  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.259  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 22:01:05.259  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-12 22:01:05.261  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 22:01:05.261  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 22:01:05.261  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:01:05.261  1602  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 22:01:05.262  1602  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 22:01:05.262  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.264  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 22:01:05.266  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-12 22:01:05.266  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 22:01:05.267  3814  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 22:01:05.267  3814  3829 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 22:01:05.269  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 22:01:05.269  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 22:01:05.269  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 22:01:05.269  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , display: false
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , display: false
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , create_time: 1471007226523
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , displa,y: false
08-12 22:01:05.269  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 22:01:05.270  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:01:05.270  1602  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 22:01:05.272  1602  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 22:01:05.272  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.274  2032  6838 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 22:01:05.276  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-12 22:01:05.276  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 22:01:05.281  1602  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 22:01:05.281  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.281  5981  5981 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 22:01:05.284  1602  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 22:01:05.284  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.286  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:01:05.286  1602  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 22:01:05.289  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 22:01:05.291  6480  6480 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 22:01:05.291  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 22:01:05.291  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 22:01:05.291  2365  6840 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 22:01:05.294  1602  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 22:01:05.294  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.295  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:01:05.295  1602  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 22:01:05.298  1602  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 22:01:05.298  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.299  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:01:05.299  1602  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 22:01:05.304  1602  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 22:01:05.304  1602  1656 D KeyguardModel: createShortcutInfo...
08-12 22:01:05.309  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-12 22:01:05.309  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 22:01:05.324  6792  6792 D AndroidRuntime: Shutting down VM
,08-12 22:01:05.335  1993  1993 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 22:01:05.335  1993  1993 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 22:01:05.337  1993  1993 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 22:01:05.340  6386  6386 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 22:01:05.360  1032  1973 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6842 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 22:01:05.421  1032  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 22:01:05.427  1032  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 22:01:05.430  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 22:01:05.434  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 22:01:05.436  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 22:01:05.437  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 22:01:05.438  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 22:01:05.439  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 22:01:05.445  6842  6842 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 22:01:05.445  6842  6842 W LG Account v2.2: No ProfileInfo entries
08-12 22:01:05.446  6842  6842 I LG Account v2.2: isEnabled: false
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Country: EU
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Operator: OPEN
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Ranking support: false
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Comfort support: false
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Accessory: true
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Health device: true
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Extra Pedometer: false
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Blood glucose device: false
08-12 22:01:05.446  6842  6842 I Feature : [Lifetracker]Device Number: 3
08-12 22:01:05.447  6842  6842 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-12 22:01:05.464  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 22:01:05.465  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-12 22:01:05.465  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:01:05.466  1032  1646 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6862 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 22:01:05.467  1032  1646 I ActivityManager: Killing 2154:com.lge.music/u0a34 (adj 15): empty #17
08-12 22:01:05.477  2032  2193 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 22:01:05.478  2032  2193 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 22:01:05.479   319   319 V AudioFlinger: 2154 died, releasing its sessions
08-12 22:01:05.479   319   319 V AudioFlinger:  pid 1850 @ 0
08-12 22:01:05.479   319   319 V AudioFlinger:  pid 3501 @ 1
08-12 22:01:05.479   319   319 V AudioFlinger:  pid 3501 @ 2
08-12 22:01:05.482  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 22:01:05.483  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 22:01:05.483  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:01:05.491  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-12 22:01:05.549  2604  2604 D [Concierge]Service: onStartCommand(). Type : 8
08-12 22:01:05.550  2604  2604 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 22:01:05.554  2604  2604 D [Concierge]Service: Update widget ID : 11
08-12 22:01:05.557  1032  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b98b86c u0 com.lge.launcher2/.Launcher t5} time:340163
08-12 22:01:05.564  2032  2032 D [Concierge]WidgetView: change position of spinner
08-12 22:01:05.564  1032  1938 W libprocessgroup: failed to open /acct/uid_10034/pid_2154/cgroup.procs: No such file or directory
,08-12 22:01:05.568  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1471032065568
08-12 22:01:05.568  2604  2604 D [Concierge]Service: onStartCommand(). Type : 0
08-12 22:01:05.582  6862  6862 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 22:01:05.582  6862  6862 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 22:01:05.582  6862  6862 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 22:01:05.583  6862  6862 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 22:01:05.585  6862  6862 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 22:01:05.586  6862  6862 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 22:01:05.586  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 759156716
08-12 22:01:05.587  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 22:01:05.588  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 22:01:05.593  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3ec1816c
08-12 22:01:05.593  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 22:01:05.595  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-12 22:01:05.596  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:01:05.603  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 22:01:05.603  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 22:01:05.604  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 22:01:05.604  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471031752948, New one : 1471032065568
08-12 22:01:05.604  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-12 22:01:05.605  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-12 22:01:05.606  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:01:05.608  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 22:01:05.610  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 22:01:05.611  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 22:01:05.613  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 22:01:05.614  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 22:01:05.616  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:01:05.616  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 22:01:05.640  6862  6862 W FileUtils: Failed to chmod(/data/data/com.android.settings/databases/vibrateuserpattern.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-12 22:01:05.651  6862  6862 E SQLiteDatabase: Failed to open database '/data/data/com.android.settings/databases/exceptscan.db'.
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at com.android.settings.wifi.ExceptScanProvider.onCreate(ExceptScanProvider.java:163)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 22:01:05.651  6862  6862 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 22:01:05.652  6862  6862 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-12 22:01:05.652  6862  6862 E AndroidRuntime: FATAL EXCEPTION: main
08-12 22:01:05.652  6862  6862 E AndroidRuntime: Process: com.android.settings, PID: 6862
08-12 22:01:05.652  6862  6862 E AndroidRuntime: java,.lang.RuntimeException: Unable to get provider com.android.settings.wifi.ExceptScanProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at com.android.settings.wifi.ExceptScanProvider.onCreate(ExceptScanProvider.java:163)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-12 22:01:05.652  6862  6862 E AndroidRuntime: 	... 11 more
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 22:01:05.658  1032  6883 E DropBoxManagerService: 	... 5 more
08-12 22:01:05.660  6862  6862 I Process : Sending signal. PID: 6862 SIG: 9
08-12 22:01:05.679  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 22:01:05.688  4480  4533 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: Error inserting f004=20 f005=6862 f002=1471032065685 f003= f006=-1
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:01:05.689  4480  4533 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-12 22:01:05.689  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 22:01:05.689  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 22:01:05.691  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:01:05.710  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3366b861 time:340316
08-12 22:01:05.711  2032  2272 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
```
