#### Test 7989656923d4b17_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 16:37:00.101  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-25 16:37:00.102  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-25 16:37:00.102  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-25 16:37:00.102  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-25 16:37:00.117  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 16:37:00.117  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-25 16:37:00.120  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-25 16:37:00.121  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-25 16:37:00.405  6637  6637 D AndroidRuntime: 
08-25 16:37:00.405  6637  6637 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 16:37:00.408  6637  6637 D AndroidRuntime: CheckJNI is OFF
08-25 16:37:00.525  6637  6637 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 16:37:00.530  1034  1647 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 16:37:00.559  1943  2735 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 16:37:00.564  1034  1647 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 16:37:00.565  1034  1647 D ActivityManager: setTaskToReturnTo : TaskRecord{3fdfc527 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 16:37:00.565  1034  1647 D ActivityManager: setTaskToReturnTo : TaskRecord{3fdfc527 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 16:37:00.566  1034  1647 D WindowStateEx: AppWindowTokenEx init.. 
08-25 16:37:00.567   335   349 E GBMv2   : DFP En is all cleared set to be enabled
08-25 16:37:00.593  1034  1647 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6658 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 16:37:00.595  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-25 16:37:00.595  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
08-25 16:37:00.595  1034  1457 D WifiController: battery changed pluggedType: 2
08-25 16:37:00.597  3889  3997 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 16:37:00.597  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:00.597  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:00.599  1943  2053 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-25 16:37:00.599  1943  2053 D LEDHandler: Battery Level Remaining: 100%
08-25 16:37:00.599  1943  2053 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-25 16:37:00.599  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-25 16:37:00.599  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-25 16:37:00.600  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-25 16:37:00.600  6539  6539 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 16:37:00.601  6637  6637 D AndroidRuntime: Shutting down VM
08-25 16:37:00.636  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 16:37:00.637  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{339c5ac2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 16:37:00.638  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 16:37:00.638  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1145f0d3 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 16:37:00.707  6658  6658 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-25 16:37:00.796  6658  6658 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-25 16:37:00.804  6658  6658 I LibraryLoader: Loading: webviewchromium
08-25 16:37:00.807  6658  6658 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8580-8584)
08-25 16:37:00.808  6658  6658 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 16:37:00.823  6658  6658 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bfcf7c0}
,08-25 16:37:00.825  6658  6658 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 16:37:00.825  6658  6658 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 16:37:00.834  6658  6658 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 16:37:00.835  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 16:37:00.844  6658  6658 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 16:37:00.845  6658  6658 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
08-25 16:37:00.845  6658  6658 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
08-25 16:37:00.851   316   316 V AudioPolicyService: registerClient() client 0xb57f51c0, uid 10118
08-25 16:37:00.856  1034  1096 D BluetoothManagerService: Message: 20
08-25 16:37:00.856  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14a2079:true
,08-25 16:37:00.862  6658  6658 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:00.862  6658  6658 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:00.862  6658  6658 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:00.862  6658  6658 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:00.862  6658  6658 I Adreno-EGL: Remote Branch: 
08-25 16:37:00.862  6658  6658 I Adreno-EGL: Local Patches: 
08-25 16:37:00.862  6658  6658 I Adreno-EGL: Reconstruct Branch: 
08-25 16:37:00.944  6658  6687 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 16:37:00.956  6658  6658 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 16:37:00.974  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 16:37:00.979  6658  6658 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 16:37:00.983  6658  6658 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-25 16:37:00.986  6658  6658 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 16:37:00.986  6658  6658 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-25 16:37:01.003  6658  6658 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-25 16:37:01.010  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 16:37:01.010  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 16:37:01.044  6658  6699 D OpenGLRenderer: Render dirty regions requested: true
08-25 16:37:01.044  6658  6699 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 16:37:01.052  6658  6699 D OpenGLRenderer: Enabling debug mode 0
,08-25 16:37:01.060  6658  6658 D Atlas   : Validating map...
08-25 16:37:01.065  1034  1942 D SplitWindow: check instance of lgWin Window{23c17f2b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 16:37:01.140  6658  6658 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@23b9218f time:188917
,08-25 16:37:01.147  6658  6697 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:01.148  6658  6697 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:01.164  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +529ms (total +597ms)
08-25 16:37:01.165  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{38303d4 u0 com.test.thalitest/.MainActivity t6} time:188942
08-25 16:37:01.306  6658  6658 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 16:37:01.446  6658  6710 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-25 16:37:01.462  6658  6710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 16:37:01.462  6658  6710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 16:37:01.462  6658  6710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 16:37:01.462  6658  6710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 16:37:01.462  6658  6710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 16:37:01.462  6658  6710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de40123 added. We now have 1 listener(s)
,08-25 16:37:01.468  1034  1647 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:01.471  6658  6710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-25 16:37:01.473  6658  6710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:01.480  6658  6710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 16:37:01.481  6658  6710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 16:37:01.491  6658  6710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@825a99e added. We now have 1 listener(s)
08-25 16:37:01.492  6658  6710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:01.499  1034  1457 D WifiService: New client listening to asynchronous messages
,08-25 16:37:01.506  6658  6710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:37:01.507  6658  6710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 16:37:01.509  6658  6710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 16:37:01.510  6658  6710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 16:37:01.510  6658  6710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 16:37:01.515  6658  6710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:37:01.516  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:01.520  6658  6710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 16:37:01.534  6658  6710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:01.535  6658  6710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:01.535  6658  6710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 16:37:01.535  6658  6710 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:01.538  6658  6710 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 16:37:01.546  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:01.549  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:01.582  6658  6697 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 16:37:01.582  6658  6697 I chromium: 
,08-25 16:37:01.666  6658  6658 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 16:37:01.753  6658  6658 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 16:37:01.753  6658  6658 I chromium: 
,08-25 16:37:02.101   335   351 E GBMv2   : DFP En is all cleared set to be enabled
08-25 16:37:02.102   335   351 E GBMv2   : Set value is all cleared set the max
08-25 16:37:02.102   335   351 I GBMv2   : DFP Enabled. Ignore VFP set
,08-25 16:37:02.533  6658  6713 W jxcore-log: Initializing JXcore engine
08-25 16:37:02.533  6658  6713 W jxcore-log: JXcore engine is ready
,08-25 16:37:02.564  6713  6713 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6111]" dev="sockfs" ino=6111 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 16:37:02.564  6713  6713 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-25 16:37:02.564  6713  6713 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10080]" dev="sockfs" ino=10080 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 16:37:02.564  6713  6713 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-25 16:37:02.564  6713  6713 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33163]" dev="sockfs" ino=33163 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 16:37:02.594  6658  6713 W jxcore-log: Starting JXcore engine
08-25 16:37:02.690  6658  6713 W jxcore-log: Platform android
08-25 16:37:02.690  6658  6713 W jxcore-log: 
08-25 16:37:02.690  6658  6713 W jxcore-log: Process ARCH arm
08-25 16:37:02.690  6658  6713 W jxcore-log: 
,08-25 16:37:02.918  6658  6713 I jxcore-log: JXcore Cordova bridge is ready!
08-25 16:37:02.918  6658  6713 I jxcore-log: 
08-25 16:37:02.918  6658  6713 W jxcore-log: JXcore engine is started
,08-25 16:37:02.925  6658  6710 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 16:37:02.927  6658  6658 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 16:37:12.615  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 16:37:12.615  6658  6713 I jxcore-log: 
,08-25 16:37:12.617  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 16:37:12.617  6658  6713 I jxcore-log: 
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:12.623  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:12.626  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:12.629  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 16:37:12.629  6658  6713 I jxcore-log: 
08-25 16:37:12.631  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 16:37:12.631  6658  6713 I jxcore-log: 
,08-25 16:37:13.145  6658  6713 D executeNativeTests: Running unit tests
,08-25 16:37:13.227  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:13.227  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 added. We now have 2 listener(s)
08-25 16:37:13.228  1034  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 16:37:13.232  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:13.232  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:13.232  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:13.232  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:13.233  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 added. We now have 2 listener(s)
08-25 16:37:13.233  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:13.233  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:37:13.236  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:13.239  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:13.240  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.240  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:13.243  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 16:37:13.246  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 16:37:13.246  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 16:37:13.249  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.250  6658  6713 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 16:37:13.251  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.251  6658  6713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 16:37:13.251  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 16:37:13.251  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 16:37:13.251  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 16:37:13.252  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.253  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.253  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.253  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.253  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.253  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:13.253  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:13.253  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 removed from the list
08-25 16:37:13.253  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.254  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 removed from the list
08-25 16:37:13.254  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.254  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.256  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.256  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.256  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.256  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.256  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.257  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.258  6658  6713 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is n,ot supported
08-25 16:37:13.258  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.258  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.258  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.259  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.259  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.259  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.259  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.259  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.259  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.259  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.259  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.259  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.259  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.259  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:37:13.260  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.260  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.260  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.260  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 16:37:13.264  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 16:37:13.265  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 16:37:13.265  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 16:37:13.265  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 16:37:13.265  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 16:37:13.265  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 16:37:13.265  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 16:37:13.265  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 16:37:13.265  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.265  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.265  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.265  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.265  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.265  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:37:13.266  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.266  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.266  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.266  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.266  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.266  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.266  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.266  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.267  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 16:37:13.267  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.267  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.267  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.268  6658  6713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 16:37:13.269  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:13.272  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
08-25 16:37:13.273  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.273  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-25 16:37:13.274  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:13.275  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.275  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:13.275  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:37:13.276  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:37:13.276  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.276  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 16:37:13.278  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 16:37:13.279  1034  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:13.283  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 16:37:13.287  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 16:37:13.289  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 16:37:13.290  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:37:13.291  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:13.292  6658  6713 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 16:37:13.292  6658  6713 I io.jxcore.node.ConnectionHelper: start: OK
08-25 16:37:13.295  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.295  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.295  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.295  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.295  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.295  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:13.295  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.295  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.295  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.295  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.295  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.296  6658  6713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 16:37:13.297  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:13.299  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:37:13.300  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.300  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:13.301  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:13.301  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:37:13.301  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:37:13.301  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.301  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 16:37:13.301  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.303  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.305  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:37:13.305  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:13.306  6658  6713 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 16:37:13.306  6658  6713 I io.jxcore.node.ConnectionHelper: start: OK
08-25 16:37:13.307  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.307  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.307  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.307  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.307  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.307  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:13.307  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.307  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.307  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.307  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.307  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.309  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.309  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.310  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.310  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 16:37:13.311  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.311  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.311  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.311  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.311  6658  6713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 16:37:13.313  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:13.315  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:13.316  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:13.316  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:13.317  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.317  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:13.317  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:37:13.317  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:37:13.317  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.317  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 16:37:13.318  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.320  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:37:13.320  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:13.321  6658  6713 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 16:37:13.321  6658  6713 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 16:37:13.321  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.321  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.321  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.322  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.322  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.322  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.322  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.322  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.322  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:13.322  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.322  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.322  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.322  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.322  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.323  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.323  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.323  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.323  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.324  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.324  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.324  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.324  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.324  6658  6713 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 16:37:13.324  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.325  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.325  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.325  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.325  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: re,lease: The given listener does not exist in the list - probably already removed
08-25 16:37:13.325  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.325  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.325  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.325  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.325  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.325  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.325  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.325  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.325  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.326  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.326  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.327  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.327  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.328  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.328  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.329  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 16:37:13.329  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.329  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.329  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.329  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.329  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.329  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.329  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.329  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.329  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.329  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.329  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.329  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.330  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.330  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.330  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.330  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.331  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.331  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.331  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.331  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.331  6658  6713 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 16:37:13.332  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.332  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.332  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.332  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.332  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.332  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.332  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.332  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.332  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.332  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.332  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.332  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.332  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.332  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.333  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.333  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.333  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.333  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.333  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.333  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.334  6658  6713 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 16:37:13.334  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.334  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.334  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.334  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.334  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.335  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.335  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.335  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.335  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.335  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.335  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.335  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.335  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.335  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.335  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.335  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.336  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.336  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.336  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.336  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.336  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 16:37:13.337  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 16:37:13.337  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 16:37:13.337  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 16:37:13.337  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 16:37:13.337  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 16:37:13.338  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.338  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.338  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.338  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.338  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.338  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.338  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.338  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.338  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.338  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.338  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.338  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.338  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.338  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.339  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.339  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.339  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.339  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.339  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.340  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.340  6658  6713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:37:13.340  6658  6713 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 16:37:13.340  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 16:37:13.347  6658  6713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:37:13.347  6658  6713 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 16:37:13.347  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 16:37:13.348  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 16:37:13.349  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 16:37:13.349  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 16:37:13.349  6658  6713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 16:37:13.349  6658  6713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 16:37:13.350  6658  6713 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 16:37:13.350  6658  6713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:37:13.350  6658  6713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 16:37:13.350  6658  6713 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 16:37:13.350  6658  6713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:37:13.350  6658  6713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 16:37:13.350  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 16:37:13.351  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 16:37:13.352  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 16:37:13.352  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 16:37:13.353  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 16:37:13.353  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 16:37:13.353  6658  6713 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 16:37:13.353  6658  6713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:37:13.353  6658  6713 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 16:37:13.354  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.354  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.354  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.354  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.354  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.354  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.354  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 16:37:13.356  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.356  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.356  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.356  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.356  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.356  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.356  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.356  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.358  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.358  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.358  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.358  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.358  6658  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-25 16:37:13.358  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.358  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.359  6658  6713 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 16:37:13.359  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.359  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.359  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.359  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.359  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.360  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.360  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.360  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.360  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.360  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.360  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.360  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.360  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.360  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.360  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.361  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 16:37:13.361  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.361  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.361  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.361  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.362  6658  6713 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 16:37:13.363  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.363  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.363  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.363  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.363  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.363  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.363  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.363  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.363  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.363  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.363  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.363  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.363  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.363  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.364  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.364  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.365  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.365  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.365  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.365  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.365  6658  6713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 16:37:13.366  6658  6713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 16:37:13.366  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 16:37:13.366  6658  6713 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 16:37:13.366  6658  6713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 16:37:13.366  6658  6713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 16:37:13.366  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 16:37:13.366  6658  6713 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 16:37:13.366  6658  6713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 16:37:13.366  6658  6713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 16:37:13.366  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 16:37:13.366  6658  6713 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 16:37:13.366  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.366  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.367  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.367  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.367  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.367  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.367  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.367  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.367  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.367  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.367  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.367  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.367  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.367  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.369  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.369  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.369  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.369  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.369  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.369  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.370  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.370  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.370  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.370  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.370  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.370  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.370  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.370  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.370  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.375  6658  6720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-25 16:37:13.375  6658  6720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
08-25 16:37:13.376  6658  6720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
08-25 16:37:13.371  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.376  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.376  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.376  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.376  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.376  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.376  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.376  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.376  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.377  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.377  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.377  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.377  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.377  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.377  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.377  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.377  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.377  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.377  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.377  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.378  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.378  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.379  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.379  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.379  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.379  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.382  6658  6713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 16:37:13.382  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.383  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 16:37:13.384  6658  6713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 16:37:13.384  6658  6713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 16:37:13.385  6658  6658 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 16:37:13.385  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 16:37:13.385  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 16:37:13.386  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.386  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 16:37:13.386  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 16:37:13.386  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 16:37:13.386  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.386  6658  6713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 16:37:13.386  6658  6658 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 16:37:13.386  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.386  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.386  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 16:37:13.386  6658  6713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 16:37:13.386  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 16:37:13.387  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 16:37:13.387  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:13.387  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:13.387  6658  6713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 16:37:13.388  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.388  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.388  6658  6713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:37:13.389  6658  6658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:37:13.389  6658  6658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:37:13.389  6658  6658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:37:13.389  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.391  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.391  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.391  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.392  6658  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 16:37:13.392  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.392  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.392  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.392  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.392  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.392  6658  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 16:37:13.392  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.392  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.392  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.392  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.392  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.392  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.392  6658  6658 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 16:37:13.393  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.393  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.393  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.393  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.393  6658  6713 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 16:37:13.393  6658  6713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 16:37:13.394  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 16:37:13.394  6658  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 16:37:13.395  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.395  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.395  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.395  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.395  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.395  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.395  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.395  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.395  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.395  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.395  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.395  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.395  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.395  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.395  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.396  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.396  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.396  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.396  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:13.397  1034  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:13.398  1034  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:13.398  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.398  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.398  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.398  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.398  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.398  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.398  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.398  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.398  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.398  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.398  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.398  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.398  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.398  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.399  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.399  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.399  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.399  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.400  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:13.400  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:13.400  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:13.400  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:13.400  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.400  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.401  6658  6713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127c933 not in the list
08-25 16:37:13.401  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.401  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.401  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:13.401  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.401  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.401  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:13.401  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:13.402  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:13.402  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:13.402  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:13.402  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db064f0 not in the list
08-25 16:37:13.403  6658  6713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 16:37:13.404  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 16:37:13.404  6658  6713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 16:37:13.404  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 16:37:13.404  6658  6713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 16:37:13.404  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 16:37:13.406  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 16:37:13.406  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 16:37:13.407  6658  6713 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 16:37:13.407  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 16:37:13.407  6658  6713 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 16:37:13.407  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 16:37:13.407  6658  6713 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 16:37:13.407  6658  6713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 16:37:13.407  6658  6713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 16:37:13.408  6658  6713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 16:37:13.408  6658  6713 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 16:37:13.408  6658  6713 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-25 16:37:13.408  6658  6713 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 16:37:13.408  6658  6713 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 16:37:13.409  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:13.409  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3999dda1 added. We now have 2 listener(s)
08-25 16:37:13.409  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:13.410  6658  6713 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 16:37:13.411  1034  1887 D WifiServiceImplEx: setWifiEnabled: true pid=6658, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 16:37:13.411  1034  1887 D WifiService: setWifiEnabled: true pid=6658, uid=10118
08-25 16:37:13.411  1034  1887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:37:13.412  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:13.412  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33909bc6 added. We now have 3 listener(s)
08-25 16:37:13.412  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:13.416  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:13.416  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@52cd787 added. We now have 4 listener(s)
08-25 16:37:13.416  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:13.417  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:13.417  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@172d16b4 added. We now have 5 listener(s)
08-25 16:37:13.417  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:13.419  1034  1996 D WifiServiceImplEx: setWifiEnabled: false pid=6658, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 16:37:13.419  1034  1996 D WifiService: setWifiEnabled: false pid=6658, uid=10118
08-25 16:37:13.419  1034  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:37:13.430  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 16:37:13.430  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 16:37:13.430  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:13.431  1034  1400 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:13.431  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:13.432  1034  1400 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:13.432  1034  1400 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:13.432  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:13.432  1034  1400 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 16:37:13.432  1034  1400 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 16:37:13.432  1034  1400 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 16:37:13.433  1034  1400 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 16:37:13.433  1034  1400 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 16:37:13.434  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:13.434  1034  2014 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@36c10eda mBinding = false
08-25 16:37:13.438  1034  1400 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 16:37:13.439  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.439  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.438  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 16:37:13.439  2731  2731 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 16:37:13.439  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 16:37:13.440  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:13.440  1034  1400 D WifiNative-wlan0: SET ps 1: returned true
08-25 16:37:13.440   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-25 16:37:13.444  1034  2867 D DhcpStateMachine: RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 16:37:13.452  1034  1096 D BluetoothManagerService: Message: 2
08-25 16:37:13.453  1034  1096 D BluetoothManagerService: Sending off request.
08-25 16:37:13.454  3889  3907 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 16:37:13.455  3889  3964 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 16:37:13.455  3889  3964 D BluetoothAdapterProperties: Setting state to 13
08-25 16:37:13.455  3889  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 16:37:13.455  3889  3964 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 16:37:13.455  3889  3964 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 16:37:13.464  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:13.464  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 16:37:13.469  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-25 16:37:13.473  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 16:37:13.474  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-25 16:37:13.475  3889  3889 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:13.475  3889  3889 D BluetoothMapService: STATE_TURNING_OFF
08-25 16:37:13.475  3889  3889 V BluetoothMapService: Handler(): got msg=4
08-25 16:37:13.475  3889  3889 D BluetoothMapService: MAP Service closeService in
08-25 16:37:13.475  3889  3889 D BluetoothMapMasInstance: MAP Service shutdown
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 16:37:13.476  3889  4267 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 16:37:13.476  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:13.476  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 16:37:13.479  3889  3889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 16:37:13.479  3889  3889 V BluetoothMapService: MAP Service closeService out
08-25 16:37:13.497  1034  2014 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-25 16:37:13.499  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.499  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.499  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 16:37:13.500  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.500  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-25 16:37:13.500  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:13.500  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:13.501  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.501  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:13.502  3889  3889 V BtOppService: Receiver DISABLED_ACTION 
08-25 16:37:13.503  3889  3889 I BtOppRfcommListener: stopping Accept Thread
08-25 16:37:13.503  3889  3889 V BtOppRfcommListener: close mBtServerSocket
08-25 16:37:13.503  3889  3889 V BtOppRfcommListener: waiting for thread to terminate
08-25 16:37:13.504  3889  4307 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:13.504  3889  4307 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 16:37:13.506  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 16:37:13.506  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 16:37:13.506  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:13.512  3889  3889 V BtOppRfcommListener: done waiting for thread to terminate
,08-25 16:37:13.523  6658  6719 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-25 16:37:13.523  6658  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-25 16:37:13.532   311  6739 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-25 16:37:13.534  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6737 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 16:37:13.535  1034  1469 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 16:37:13.535  1034  1469 D DSQN    : disableDataServiceNotify
08-25 16:37:13.535  1034  1469 D DSQN    : stop dsqn bin
08-25 16:37:13.536  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-25 16:37:13.536  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 16:37:13.537  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.537  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.537  1034  1400 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.537  1034  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@14d6025e
08-25 16:37:13.538  1034  1469 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 16:37:13.538  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:13.538  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:13.538  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 16:37:13.538  1034  1469 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:13.539  1034  1469 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 16:37:13.539  3889  3889 V BtOppService: onDestroy
08-25 16:37:13.539  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.539  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.539  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 16:37:13.539  1034  1469 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 16:37:13.539  1034  1469 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 16:37:13.539  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 16:37:13.540  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.540  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.540  1034  1400 E WifiStateMachine: , WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.541  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.541  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.541  1603  2077 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 16:37:13.542  1034  1400 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 16:37:13.542  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 16:37:13.542  1034  1400 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.542  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.543  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:13.543  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:13.543  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:13.543  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 16:37:13.545  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 16:37:13.545  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:13.545  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:13.545  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 16:37:13.545  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 16:37:13.545  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-25 16:37:13.545  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.549  1034  1391 D LGWifiP2pService: P2pDisablingState
08-25 16:37:13.549  1034  1469 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:13.549  1034  1391 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.549  1034  1391 D LGWifiP2pService: p2p socket connection lost
,08-25 16:37:13.549  1034  1391 D LGWifiP2pService: P2pDisabledState
08-25 16:37:13.549  1034  1558 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.550  3889  3889 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 16:37:13.550  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:13.550  1034  1400 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 16:37:13.550  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 16:37:13.551  2731  2731 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 16:37:13.551  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 16:37:13.551  1034  1469 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:13.551  1034  1469 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:13.551  1034  1469 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:13.551  1034  1469 D NetworkManagementService: Removing idletimer
08-25 16:37:13.551  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:13.552  1034  1469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:13.552  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 16:37:13.552  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.552  1034  1391 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.552  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 16:37:13.552  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:13.552  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:13.552  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:13.552  1034  1400 D WifiNative-wlan0: SET ps 1: returned true
08-25 16:37:13.552   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-25 16:37:13.553  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.553  6658  6713 D, io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:13.553  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:13.554  1034  1400 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 16:37:13.554  1034  1400 D WifiNative-p2p0: TERMINATE: returned true
08-25 16:37:13.554  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:13.554  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:13.554  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:13.554  1034  1400 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:13.554  1034  1400 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:13.556  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 16:37:13.556  1943  1943 D WfdsService: WifiP2pState is changed : false
08-25 16:37:13.556  1943  2228 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 16:37:13.556  1943  2228 D WfdsService: Set the WFDS Monitor: false
08-25 16:37:13.556  1943  2228 D WfdsMonitor: WFDS Monitor is stopped
08-25 16:37:13.556  1943  2228 D WfdsService: STATE : WfdsDisabledState - enter
08-25 16:37:13.556  1943  2231 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 16:37:13.557  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 16:37:13.558  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:13.558  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-25 16:37:13.561  1943  2770 D CtrlSupplicant: Received on exit socket, terminate
08-25 16:37:13.561  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 16:37:13.561  1943  2770 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 16:37:13.562  1943  2770 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 16:37:13.562  1943  2770 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 16:37:13.562  1943  2228 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 16:37:13.565  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 16:37:13.566  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:13.566  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:13.566  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.581  1034  1576 I art     : Explicit concurrent mark sweep GC freed 41256(2040KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.631ms total 124.466ms
08-25 16:37:13.582  1034  1469 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-25 16:37:13.584  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-25 16:37:13.585  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 16:37:13.585  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:13.585  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:13.585  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 16:37:13.592  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:13.592  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:13.593  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.603  1034  1942 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6756 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 16:37:13.605  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 16:37:13.605  3889  3968 D BluetoothAdapterProperties: Scan Mode:20
08-25 16:37:13.605  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:13.605  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 16:37:13.605  3889  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 16:37:13.605  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 16:37:13.605  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 16:37:13.605  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 16:37:13.605  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 16:37:13.605  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 16:37:13.605  3889  3964 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 16:37:13.605  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 16:37:13.606  3889  4310 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:13.606  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 16:37:13.606  3889  4070 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 16:37:13.606  3889  4313 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:13.606  3889  4271 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:13.607  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:13.607  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:13.607  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.607  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CA,P - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 16:37:13.608  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 16:37:13.608  3889  4070 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 16:37:13.611  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:13.611  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:13.613  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:13.613  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:13.613  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:13.613  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:13.615  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.616  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:13.617  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.626  6737  6737 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 16:37:13.626  6737  6737 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 16:37:13.627  6737  6737 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 16:37:13.627  6737  6737 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 16:37:13.628  6737  6737 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 16:37:13.628  6737  6737 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 16:37:13.634  2731  2731 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 16:37:13.634  2731  2731 I wpa_supplicant: monitor socket send errors count : 1
08-25 16:37:13.634  2731  2731 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
,08-25 16:37:13.635  1034  2759 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 16:37:13.635  1034  2759 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 16:37:13.641  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 16:37:13.641  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.642  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.649  1034  2867 D DhcpStateMachine: StoppedState
,08-25 16:37:13.649  1034  2867 D DhcpStateMachine: StoppedState{ when=-96ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:13.649  1034  1400 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 16:37:13.650  1034  1400 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 16:37:13.658  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 16:37:13.659  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.659  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.659  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 16:37:13.659  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:13.660  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.661  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.665  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 16:37:13.675  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 16:37:13.675  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:13.676  1034  1888 I ActivityManager: Killing 5883:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-25 16:37:13.680  2731  2731 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 16:37:13.680  2731  2731 W wpa_supplicant: USIM:  scard_deinit function
08-25 16:37:13.680  1034  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 16:37:13.680  1034  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 16:37:13.681  1034  2759 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 16:37:13.681  1034  2759 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 16:37:13.681  1034  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-25 16:37:13.681  1034  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:13.681  1034  1400 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201446
08-25 16:37:13.681  1034  1096 D Tethering: InitialState.processMessage what=4
08-25 16:37:13.681  1034  1400 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201447
08-25 16:37:13.682  1034  1400 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201447  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 16:37:13.682  1034  1400 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201447  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 16:37:13.715  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 16:37:13.715  1034  1576 W libprocessgroup: failed to open /acct/uid_10014/pid_5883/cgroup.procs: No such file or directory
,08-25 16:37:13.718  1034  1400 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,08-25 16:37:13.718  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:13.757  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 16:37:13.761  3889  3889 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 16:37:13.762  3889  3889 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:13.762  3889  3889 V BluetoothPbapReceiver: ***********state = 13
08-25 16:37:13.766  2731  2731 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 16:37:13.766  1034  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 16:37:13.767  1034  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 16:37:13.767  3889  3889 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 16:37:13.767  1034  2759 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 16:37:13.768  3889  3889 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:13.768  3889  3889 V BluetoothPbapService: state: 13
08-25 16:37:13.768  3889  3889 V BluetoothPbapService: Pbap Service closeService in
08-25 16:37:13.768  1034  1400 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-25 16:37:13.768  3889  3889 V BluetoothPbapService: successfully stopped pbap service
08-25 16:37:13.768  3889  3889 V BluetoothPbapService: Pbap Service closeService out
08-25 16:37:13.769  3889  3889 V BluetoothPbapService: Pbap Service onDestroy
08-25 16:37:13.769  3889  3889 V BluetoothPbapService: Pbap Service closeService in
08-25 16:37:13.769  3889  3889 V BluetoothPbapService: Pbap Service closeService out
08-25 16:37:13.769  3889  3889 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-25 16:37:13.771  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 16:37:13.787  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:13.829  1034  1942 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6777 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 16:37:13.832  6737  6737 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:13.833  6737  6737 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:13.844  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:13.852  1034  1096 D BluetoothManagerService: Message: 20
08-25 16:37:13.852  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39655b3d:true
08-25 16:37:13.863  1034  1096 D BluetoothManagerService: Message: 30
,08-25 16:37:13.867  1034  1096 D BluetoothManagerService: Message: 30
08-25 16:37:13.869  6737  6737 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 16:37:13.870  1034  1400 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 16:37:13.870  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:13.870  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:13.870  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:13.871  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-25 16:37:13.871  1943  2228 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 16:37:13.871  1943  2228 D WfdsService: Set the WFDS Monitor: false
08-25 16:37:13.871  1943  2228 D WfdsMonitor: WFDS Monitor is stopped
08-25 16:37:13.871  6737  6737 D BluetoothMap: Create BluetoothMap proxy object
08-25 16:37:13.871  1034  1096 D BluetoothManagerService: Message: 30
08-25 16:37:13.872  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:13.872  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 16:37:13.874  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 16:37:13.874  1034  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 16:37:13.874  1034  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 16:37:13.874  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:13.875  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.876  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:13.881  1034  1096 D BluetoothManagerService: Message: 30
,08-25 16:37:13.886  6737  6737 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 16:37:13.887  6737  6737 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 16:37:13.889  6658  6658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 16:37:13.903  6737  6737 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 16:37:13.905  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 16:37:13.914  6737  6737 D DockEventReceiver: finishStartingService: stopping service
08-25 16:37:13.924  6737  6737 D BluetoothInputDevice: Proxy object connected
,08-25 16:37:13.924  6737  6737 D HidProfile: Bluetooth service connected
08-25 16:37:13.925  6737  6737 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 16:37:13.926  6737  6737 D PanProfile: Bluetooth service connected
08-25 16:37:13.929  6737  6737 D BluetoothMap: Proxy object connected
08-25 16:37:13.929  6737  6737 D MapProfile: Bluetooth service connected
08-25 16:37:13.929  6737  6737 D BluetoothMap: getConnectedDevices()
08-25 16:37:13.930  6737  6737 D BluetoothMap: Bluetooth is Not enabled
08-25 16:37:13.930  6737  6737 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 16:37:13.996  1034  1576 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6801 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 16:37:14.003  1034  1576 I ActivityManager: Killing 6222:com.android.defcontainer/u0a4 (adj 15): empty #17
08-25 16:37:14.044  1034  1647 W libprocessgroup: failed to open /acct/uid_10004/pid_6222/cgroup.procs: No such file or directory
08-25 16:37:14.044  6777  6777 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-25 16:37:14.045  6777  6777 W LG Account v2.2: No ProfileInfo entries
08-25 16:37:14.045  6777  6777 I LG Account v2.2: isEnabled: false
08-25 16:37:14.045  6777  6777 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 16:37:14.045  6777  6777 I Feature : [Lifetracker]Country: EU
08-25 16:37:14.045  6777  6777 I Feature : [Lifetracker]Operator: OPEN
08-25 16:37:14.046  6777  6777 I Feature : [Lifetracker]Ranking support: false
08-25 16:37:14.046  6777  6777 I Feature : [Lifetracker]Comfort support: false
08-25 16:37:14.046  6777  6777 I Feature : [Lifetracker]Accessory: true
08-25 16:37:14.046  6777  6777 I Feature : [Lifetracker]Health device: true
08-25 16:37:14.046  6777  6777 I Feature : [Lifetracker]Extra Pedometer: false
08-25 16:37:14.046  6777  6777 I Feature : [Lifetracker]Blood glucose device: false
08-25 16:37:14.046  6777  6777 I Feature : [Lifetracker]Device Number: 3
,08-25 16:37:14.065  6737  6737 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 16:37:14.073  6737  6737 D BluetoothPermissionRequest: onReceive
08-25 16:37:14.075  6737  6737 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 16:37:14.077  6801  6801 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:14.091  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 16:37:14.093  1034  1996 I ActivityManager: Killing 6385:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-25 16:37:14.125  3889  3889 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-25 16:37:14.125  3889  3889 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 16:37:14.126  3889  3889 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 16:37:14.126  1034  1050 W libprocessgroup: failed to open /acct/uid_10008/pid_6385/cgroup.procs: No such file or directory
08-25 16:37:14.131  6801  6801 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 16:37:14.137  3889  3889 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:14.138  3889  3889 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 16:37:14.140  3889  3889 V BluetoothFtpService: Ftp Service onStartCommand
08-25 16:37:14.140  3889  3889 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:14.141  3889  3889 V BluetoothFtpService: Ftp Service closeService
08-25 16:37:14.141  3889  3889 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 16:37:14.142  3889  3889 V BluetoothFtpService: successfully stopped ftp service
08-25 16:37:14.143  3889  3889 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:14.144  3889  3889 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:14.144  3889  3889 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 16:37:14.144  3889  3889 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:14.144  3889  3889 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 16:37:14.144  3889  3889 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 16:37:14.146  3889  3889 V BluetoothFtpService: Ftp Service onDestroy
08-25 16:37:14.146  3889  3889 V BluetoothFtpService: Ftp Service closeService
08-25 16:37:14.188  6801  6801 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 16:37:14.189  6801  6801 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 16:37:14.189  6801  6801 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 16:37:14.190  6801  6801 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 16:37:14.190  6801  6801 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 16:37:14.192  6801  6801 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-25 16:37:14.199  6801  6801 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 16:37:14.222  1034  2014 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6820 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 16:37:14.223  3889  3889 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:14.223  3889  3889 V BluetoothSapService: state: 13
08-25 16:37:14.223  3889  3889 V BluetoothSapService: Stopping SAP server process
,08-25 16:37:14.226  3889  3889 V BluetoothSapService: Sap Service closeSapService in
08-25 16:37:14.226  3889  3889 V BluetoothSapService: Close listen Socket : 
08-25 16:37:14.226  3889  3889 V BluetoothSapService: Close rfcomm Socket : 
08-25 16:37:14.226  3889  3889 V BluetoothSapService: Close sapd  Socket : 
08-25 16:37:14.227  3889  3889 V BluetoothSapService: Sap Service closeSapService out
08-25 16:37:14.228  3889  3889 V BluetoothSapService: Sap Service onDestroy
08-25 16:37:14.228  3889  3889 V BluetoothSapService: Sap Service closeSapService in
08-25 16:37:14.228  3889  3889 V BluetoothSapService: Close listen Socket : 
08-25 16:37:14.228  3889  3889 V BluetoothSapService: Close rfcomm Socket : 
08-25 16:37:14.228  3889  3889 V BluetoothSapService: Close sapd  Socket : 
08-25 16:37:14.229  3889  3889 V BluetoothSapService: Sap Service closeSapService out
08-25 16:37:14.235  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:14.238  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 16:37:14.256  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 16:37:14.258  6801  6801 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 16:37:14.258  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:14.261  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 16:37:14.261  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 16:37:14.261  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:14.264  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 16:37:14.264  6801  6801 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-25 16:37:14.278  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:14.286  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:14.286  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 16:37:14.294  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 16:37:14.297  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:14.300  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 16:37:14.300  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 16:37:14.300  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 16:37:14.303  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:14.315  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:14.315  6820  6820 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:14.323  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:14.323  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:14.325  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 16:37:14.374  1034  1942 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6840 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-25 16:37:14.375  1034  1942 I ActivityManager: Killing 5992:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 16:37:14.414  1034  1576 W libprocessgroup: failed to open /acct/uid_10011/pid_5992/cgroup.procs: No such file or directory
,08-25 16:37:14.464  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 16:37:14.469  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 16:37:14.476  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 16:37:14.481  6840  6859 W FormManager: Network not available. Please check & try again.
08-25 16:37:14.492  6840  6860 V FormManager: Network unavailable.
,08-25 16:37:14.497  6840  6860 V FormManager: Network unavailable.
08-25 16:37:14.509  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 16:37:14.509  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 16:37:14.509  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 16:37:14.510  6737  6737 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 16:37:14.510  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-25 16:37:14.522  6737  6737 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 16:37:14.524  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 16:37:14.524  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 16:37:14.524  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 16:37:14.524  6737  6737 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-25 16:37:14.526  6737  6737 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 16:37:14.528  1034  1052 I ActivityManager: Killing 6014:com.android.contacts/u0a19 (adj 15): empty #17
08-25 16:37:14.598  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 16:37:14.598  1034  1576 W libprocessgroup: failed to open /acct/uid_10019/pid_6014/cgroup.procs: No such file or directory
08-25 16:37:14.598  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 16:37:14.603  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:14.608  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:14.610  3889  4070 W bt-btif : ag scb idx 1 not allocated
08-25 16:37:14.611  3889  4070 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 16:37:14.611  3889  3968 D bt_hci_bdroid: cleanup
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-25 16:37:14.611  3889  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:14.611  3889  4070 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 16:37:14.611  3889  4244 I bt_userial_mct: exiting userial_read_thread
,08-25 16:37:14.611  3889  4244 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 16:37:14.611  3889  4072 I bt_lpm  : LPM is already off!!!
08-25 16:37:14.612  3889  3968 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 16:37:14.612  3889  4072 I bt_vendor: hw_epilog_process
08-25 16:37:14.612  3889  3968 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 16:37:14.612  3889  3968 D bt_userial_mct: userial_close
08-25 16:37:14.612  3889  3968 E bt_userial_mct: pthread_join() FAILED result:3
08-25 16:37:14.613  3889  3968 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 16:37:14.622  6756  6756 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 16:37:14.622  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 16:37:14.622  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:14.623  4314  6867 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 16:37:14.624  4314  6869 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 16:37:14.624  4314  6869 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 16:37:14.626  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 16:37:14.637  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:14.637  6840  6870 W FormManager: Network not available. Please check & try again.
08-25 16:37:14.646  6840  6871 V FormManager: Network unavailable.
,08-25 16:37:14.651  6840  6871 V FormManager: Network unavailable.
08-25 16:37:14.657  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 16:37:14.658  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 16:37:14.658  6801  6801 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-25 16:37:14.696  6801  6801 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:14.696  6801  6801 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:14.703  3889  3968 D bt_hci_bdroid: set_power 0
08-25 16:37:14.703  3889  3968 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 16:37:14.704  3889  3968 I bt_vendor: bluetooth satus is on
08-25 16:37:14.704  3889  3968 I bt_vendor: bt-vendor : resetting BT status
08-25 16:37:14.704  3889  3968 I bt_vendor: Starting hciattach daemon
08-25 16:37:14.704  3889  3968 I bt_vendor: try to set false
08-25 16:37:14.704  6801  6801 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 16:37:14.705  6801  6801 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 16:37:14.705  6801  6801 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 16:37:14.705  6801  6801 V SoundPool: doLoad: loading sample sampleID=1
08-25 16:37:14.705  3889  3968 I bt_vendor: Starting hciattach daemon
08-25 16:37:14.705  3889  3968 I bt_vendor: try to set false
08-25 16:37:14.705  6801  6801 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 16:37:14.706  3889  3968 I bt_vendor: cleanup
08-25 16:37:14.708  3889  4070 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 16:37:14.708  3889  3968 I GKI_LINUX: GKI_exit_task 0 done
08-25 16:37:14.708  3889  3968 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 16:37:14.709  6801  6801 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 16:37:14.710  6801  6874 V SoundPool: Start decode
08-25 16:37:14.710  6801  6874 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 16:37:14.711  6563  6563 D UEI.SmartControl: QS Service created
08-25 16:37:14.711   316  1397 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 16:37:14.711   316  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 16:37:14.711   316  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 16:37:14.711   316  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 16:37:14.711   316  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 16:37:14.711   316  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 16:37:14.711   316  1397 V MediaPlayerService: player type = 3
08-25 16:37:14.711   316  1397 V AwesomePlayer: AwesomePlayer create()
08-25 16:37:14.711  6801  6801 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 16:37:14.711  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 16:37:14.712   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:14.712   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:14.712   316  1397 V AwesomePlayer: setAudioSink() 
08-25 16:37:14.712   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:14.712   316  1397 V AudioCache: notify(0xb04098c0, 8, 0, 0)
08-25 16:37:14.712   316  1397 V AudioCache: ignored
08-25 16:37:14.712   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:14.712   316  1397 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 16:37:14.713   316  1397 V AwesomePlayer: setDataSource_l dataSource
08-25 16:37:14.713   316  1397 V LGParserOSAL: SniffLGParser start
08-25 16:37:14.713   316  1397 V LGParserOSAL: MainType:5, SubType=0
08-25 16:37:14.713   316  1397 V LGParserOSAL: #### check Mime : application/ogg
08-25 16:37:14.713   316  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 16:37:14.713   316  1397 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 16:37:14.714  3889  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-25 16:37:14.722  3889  3889 D HeadsetService: Received stop request...Stopping profile...
08-25 16:37:14.723  3889  3889 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 16:37:14.723  3889  3889 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 16:37:14.724  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cb22cf9
08-25 16:37:14.724  3889  3997 D HeadsetStateMachine: Exit Disconnected: -1
08-25 16:37:14.725  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:14.725  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:14.725  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:14.725  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 16:37:14.726  3889  3889 D A2dpService: Received stop request...Stopping profile...
08-25 16:37:14.727  3889  4056 D A2dpStateMachine: Exit Disconnected: -1
08-25 16:37:14.727  3889  3889 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-25 16:37:14.729  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:14.729  3889  3964 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 16:37:14.730  3889  3889 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 16:37:14.730  3889  3889 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 16:37:14.730  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cb22cf9
08-25 16:37:14.731  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-25 16:37:14.731  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 16:37:14.733  3889  3889 D HidService: Received stop request...Stopping profile...
08-25 16:37:14.733  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cb22cf9
08-25 16:37:14.734  3889  3889 D HealthService: Received stop request...Stopping profile...
08-25 16:37:14.734  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cb22cf9
08-25 16:37:14.736  3889  3889 D HeadsetStateMachine: Unbinding service...
08-25 16:37:14.737  3889  3889 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 16:37:14.737  3889  3889 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 16:37:14.737  3889  3889 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 16:37:14.737  3889  3889 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 16:37:14.737  3889  3889 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 16:37:14.738  3889  3889 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 16:37:14.738  3889  3889 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 16:37:14.738  3889  3889 D PanService: Received stop request...Stopping profile...
08-25 16:37:14.739  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cb22cf9
08-25 16:37:14.739  6801  6801 V LGMDMManager: Create singleton instance
08-25 16:37:14.740  3889  3889 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 16:37:14.741  3889  3889 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 16:37:14.741  3889  3889 D BtGatt.GattService: stop()
08-25 16:37:14.741  3889  3889 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 16:37:14.742  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cb22cf9
08-25 16:37:14.743  3889  3889 D BluetoothMapService: Received stop request...Stopping profile...
08-25 16:37:14.743  3889  3889 D BluetoothMapService: stop()
08-25 16:37:14.744  3889  3889 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 16:37:14.744  3889  3889 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 16:37:14.744  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cb22cf9
08-25 16:37:14.746  3889  3889 I BluetoothA2dpServiceJni: cleanupNative
08-25 16:37:14.746  3889  4057 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 16:37:14.746  3889  3889 I GKI_LINUX: GKI_exit_task 2 done
08-25 16:37:14.746  3889  3889 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 16:37:14.747  3889  3889 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 16:37:14.747  3889  3889 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 16:37:14.747  3889  3889 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 16:37:14.747  3889  3889 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 16:37:14.747  3889  3889 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 16:37:14.748  3889  3889 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 16:37:14.748  3889  3889 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 16:37:14.750  3889  3889 V BluetoothMapService: Handler(): got msg=4
08-25 16:37:14.750  3889  3889 D BluetoothMapService: MAP Service closeService in
08-25 16:37:14.750  3889  3889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 16:37:14.750  3889  3889 V BluetoothMapService: MAP Service closeService out
08-25 16:37:14.751  3889  3889 D BluetoothMapService: cleanup()
08-25 16:37:14.751  3889  3889 D BluetoothMapService: MAP Service closeService in
08-25 16:37:14.751  3889  3889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 16:37:14.751  3889  3889 V BluetoothMapService: MAP Service closeService out
08-25 16:37:14.751  3889  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 16:37:14.751  3889  3964 D BluetoothAdapterProperties: Setting state to 10
08-25 16:37:14.751  3889  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 16:37:14.752  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:14.752  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 16:37:14.752  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 16:37:14.752  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:14.752  3889  3964 I BluetoothAdapterState: Entering OffState
08-25 16:37:14.753  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:14.754  6737  6753 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 16:37:14.754  6737  6755 D BluetoothPan: onBluetoothStateChange on: false
08-25 16:37:14.755  1853  4410 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:14.756  6737  6753 D BluetoothMap: onBluetoothStateChange: up=false
08-25 16:37:14.756  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 16:37:14.756  1853  2482 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:14.757  6737  6755 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 16:37:14.758  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 16:37:14.758  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 16:37:14.760  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 16:37:14.760  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 16:37:14.761  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@36c10eda mBinding = false
08-25 16:37:14.761  1034  1096 D BluetoothManagerService: Sending unbind request.
08-25 16:37:14.765  6563  6563 I UEI.SmartControl: Service initServices...
08-25 16:37:14.765  6563  6563 D UEI.SmartControl: QS start get config
08-25 16:37:14.780  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 16:37:14.780  3889  3968 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 16:37:14.780  3889  3889 I GKI_LINUX: GKI_exit_task 1 done
08-25 16:37:14.780  3889  3889 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-25 16:37:14.781  3889  3889 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 16:37:14.781  3889  3889 I art     : --- WEIRD: removing null entry 246
08-25 16:37:14.781  3889  3889 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 16:37:14.782  3889  3889 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 16:37:14.783  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:14.784  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 16:37:14.786  6737  6737 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 16:37:14.787  6737  6737 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 16:37:14.787  6737  6737 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 16:37:14.789  1943  2076 D LGBluetoothAPIService: Message: 2
08-25 16:37:14.789  1943  2076 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@5a0410 mBinding = false
08-25 16:37:14.789  1943  2076 D LGBluetoothAPIService: Sending unbind request.
08-25 16:37:14.794  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:14.795  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:14.798  1603  1603 D BluetoothAdapter: 1068292952: getState() :  mService = null. Returning STATE_OFF
08-25 16:37:14.798  1603  1603 D BluetoothAdapter: 1068292952: getState() :  mService = null. Returning STATE_OFF
08-25 16:37:14.799  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 16:37:14.800  3889  3889 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 16:37:14.807  3889  3889 I art     : System.exit called, status: 0
08-25 16:37:14.807  3889  3889 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 16:37:14.809  6737  6737 D DockEventReceiver: finishStartingService: stopping service
08-25 16:37:14.826   316  1397 V LGParserOSAL: supported mime: application/ogg
,08-25 16:37:14.826   316  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 16:37:14.826   316  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 16:37:14.826   316  1397 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 16:37:14.826   316  1397 V AwesomePlayer: AudioTrack Setting
08-25 16:37:14.826   316  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 16:37:14.826   316  1397 V AwesomePlayer: setAudioSource() 
08-25 16:37:14.826   316  1397 V MediaPlayerService: prepare
08-25 16:37:14.826   316  1397 V AwesomePlayer: prepareAsync_l() 
08-25 16:37:14.826   316  1397 V MediaPlayerService: wait for prepare
08-25 16:37:14.826   316  6883 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 16:37:14.826   316  6883 V AwesomePlayer: initAudioDecoder() 
08-25 16:37:14.827   316  6883 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 16:37:14.827   316  6883 V AudioSystem: isOffloadSupported()
08-25 16:37:14.827   316  6883 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 16:37:14.827   316  6883 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 16:37:14.827   316  6883 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 16:37:14.827   316  6883 V AwesomePlayer: getUseOffload() = 0 
08-25 16:37:14.827   316  6883 V OMXCodec: OMXCodec::Create
08-25 16:37:14.827   316  6883 V OMXCodec: findMatchingCodecs()
08-25 16:37:14.827   316  6883 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 16:37:14.827   316  6883 V OMXCodec: matchingCodecs.size()=1
08-25 16:37:14.827   316  6883 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 16:37:14.828   316  6883 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 16:37:14.828   316  6883 V LGCodecAdapter: LG Codec Adapter start
08-25 16:37:14.828   316  6883 V OMXCodec: OMXCodec Createtor
08-25 16:37:14.829   316  6883 V OMXCodec: setComponentRole
08-25 16:37:14.829   316  6883 V OMXCodec: configureCodec protected=0
08-25 16:37:14.829   316  6883 V LGCodecAdapter: called getLGCodecSpecificData
08-25 16:37:14.829   316  6883 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 16:37:14.829   316  6883 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 16:37:14.829   316  6883 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 16:37:14.829   316  6883 V LGCodecOSAL: Not support LGCodec
08-25 16:37:14.829   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 16:37:14.829   316  6883 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 16:37:14.829   316  6883 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 16:37:14.829   316  6883 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 16:37:14.829   316  6883 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 16:37:14.829   316  6883 V AudioSystem: isOffloadSupported()
08-25 16:37:14.829   316  6883 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 16:37:14.829   316  6883 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 16:37:14.829   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 16:37:14.829   316  6883 V OMXCodec: init()
08-25 16:37:14.829   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 16:37:14.829   316  6883 V OMXCodec: allocate,Buffers
08-25 16:37:14.829   316  6883 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 16:37:14.829   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 16:37:14.829   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-25 16:37:14.830   316  6883 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 16:37:14.830   316  6883 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-25 16:37:14.830   316  6883 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 16:37:14.832   316  2150 V AudioFlinger: 3889 died, releasing its sessions
08-25 16:37:14.832   316  2150 V AudioFlinger:  pid 1853 @ 0
08-25 16:37:14.832   316  2150 V AudioFlinger:  pid 3435 @ 1
08-25 16:37:14.832   316  2150 V AudioFlinger:  pid 3435 @ 2
08-25 16:37:14.833  6737  6737 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 16:37:14.833   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-25 16:37:14.833   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 16:37:14.833   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 16:37:14.833   316  6883 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 16:37:14.833   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 16:37:14.833   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 16:37:14.833   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 16:37:14.833   316  6883 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 16:37:14.833   316  6883 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 16:37:14.833   316  6883 V AudioCache: notify(0xb04098c0, 5, 0, 0)
08-25 16:37:14.833   316  6883 V AudioCache: ignored
08-25 16:37:14.833   316  6883 V AudioCache: notify(0xb04098c0, 1, 0, 0)
08-25 16:37:14.833   316  6883 V AudioCache: prepared
08-25 16:37:14.833   316  1397 V AudioCache: wait - success
08-25 16:37:14.834   316  1397 V MediaPlayerService: start
08-25 16:37:14.834   316  1397 V AwesomePlayer: play_l() 
08-25 16:37:14.834   316  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 16:37:14.834   316  1397 V AwesomePlayer: createAudioPlayer_l
08-25 16:37:14.834   316  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 16:37:14.834   316  1397 V AwesomePlayer: startAudioPlayer_l() 
08-25 16:37:14.834   316  1397 D AudioPlayer: start of Playback, useOffload 0
08-25 16:37:14.834   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 16:37:14.834   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 16:37:14.836   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 16:37:14.836   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 16:37:14.836   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-25 16:37:14.836   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 16:37:14.836   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 16:37:14.836   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
,08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 16:37:14.837   316  6885 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 16:37:14.837   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on output port
08-25 16:37:14.838   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 16:37:14.838   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 16:37:14.839   316  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 16:37:14.839   316  1397 V AudioCache: notify(0xb04098c0, 6, 0, 0)
,08-25 16:37:14.839   316  1397 V AudioCache: ignored
08-25 16:37:14.839   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.839   316  6886 V AudioCache: memcpy(0xaf006000, 0xb0407000, 4096)
08-25 16:37:14.841   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.841   316  6886 V AudioCache: memcpy(0xaf007000, 0xb0407000, 4096)
08-25 16:37:14.841   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.841   316  6886 V AudioCache: memcpy(0xaf008000, 0xb0407000, 4096)
08-25 16:37:14.841   316  1397 V MediaPlayerService: wait for playback complete
08-25 16:37:14.842   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.842   316  6886 V AudioCache: memcpy(0xaf009000, 0xb0407000, 4096)
08-25 16:37:14.842   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.843   316  6886 V AudioCache: memcpy(0xaf00a000, 0xb0407000, 4096)
08-25 16:37:14.844   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.844   316  6886 V AudioCache: memcpy(0xaf00b000, 0xb0407000, 4096)
08-25 16:37:14.846   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.846   316  6886 V AudioCache: memcpy(0xaf00c000, 0xb0407000, 4096)
08-25 16:37:14.846   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.846   316  6886 V AudioCache: memcpy(0xaf00d000, 0xb0407000, 4096)
08-25 16:37:14.847   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.847   316  6886 V AudioCache: memcpy(0xaf00e000, 0xb0407000, 4096)
08-25 16:37:14.848   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.848   316  6886 V AudioCache: memcpy(0xaf00f000, 0xb0407000, 4096)
08-25 16:37:14.849   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.849   316  6886 V AudioCache: memcpy(0xaf010000, 0xb0407000, 4096)
08-25 16:37:14.850   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.850   316  6886 V AudioCache: memcpy(0xaf011000, 0xb0407000, 4096)
08-25 16:37:14.850   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.850   316  6886 V AudioCache: memcpy(0xaf012000, 0xb0407000, 4096)
08-25 16:37:14.851   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.851   316  6886 V AudioCache: memcpy(0xaf013000, 0xb0407000, 4096)
08-25 16:37:14.852   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.852   316  6886 V AudioCache: memcpy(0xaf014000, 0xb0407000, 4096)
08-25 16:37:14.852   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.852   316  6886 V AudioCache: memcpy(0xaf015000, 0xb0407000, 4096)
08-25 16:37:14.853   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.853   316  6886 V AudioCache: memcpy(0xaf016000, 0xb0407000, 4096)
08-25 16:37:14.854   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.854   316  6886 V AudioCache: memcpy(0xaf017000, 0xb0407000, 4096)
,08-25 16:37:14.855   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.855   316  6886 V AudioCache: memcpy(0xaf018000, 0xb0407000, 4096)
08-25 16:37:14.856   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.856   316  6886 V AudioCache: memcpy(0xaf019000, 0xb0407000, 4096)
08-25 16:37:14.857   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.857   316  6886 V AudioCache: memcpy(0xaf01a000, 0xb0407000, 4096)
08-25 16:37:14.858   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.858   316  6886 V AudioCache: memcpy(0xaf01b000, 0xb0407000, 4096)
08-25 16:37:14.858   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.858   316  6886 V AudioCache: memcpy(0xaf01c000, 0xb0407000, 4096)
08-25 16:37:14.859   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.859   316  6886 V AudioCache: memcpy(0xaf01d000, 0xb0407000, 4096)
08-25 16:37:14.860   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.860   316  6886 V AudioCache: memcpy(0xaf01e000, 0xb0407000, 4096)
08-25 16:37:14.860   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.860   316  6886 V AudioCache: memcpy(0xaf01f000, 0xb0407000, 4096)
08-25 16:37:14.861   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.861   316  6886 V AudioCache: memcpy(0xaf020000, 0xb0407000, 4096)
08-25 16:37:14.862   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.862   316  6886 V AudioCache: memcpy(0xaf021000, 0xb0407000, 4096)
08-25 16:37:14.862   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.862   316  6886 V AudioCache: memcpy(0xaf022000, 0xb0407000, 4096)
08-25 16:37:14.863   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.863   316  6886 V AudioCache: memcpy(0xaf023000, 0xb0407000, 4096)
08-25 16:37:14.864   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.864   316  6886 V AudioCache: memcpy(0xaf024000, 0xb0407000, 4096)
08-25 16:37:14.865  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 16:37:14.865   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.865   316  6886 V AudioCache: memcpy(0xaf025000, 0xb0407000, 4096)
08-25 16:37:14.865   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.865   316  6886 V AudioCache: memcpy(0xaf026000, 0xb0407000, 4096)
08-25 16:37:14.866  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 16:37:14.866   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.866   316  6886 V AudioCache: memcpy(0xaf027000, 0xb0407000, 4096)
,08-25 16:37:14.867   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.868   316  6886 V AudioCache: memcpy(0xaf028000, 0xb0407000, 4096)
08-25 16:37:14.868   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.868   316  6886 V AudioCache: memcpy(0xaf029000, 0xb0407000, 4096)
08-25 16:37:14.869   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.869   316  6886 V AudioCache: memcpy(0xaf02a000, 0xb0407000, 4096)
08-25 16:37:14.870   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.870   316  6886 V AudioCache: memcpy(0xaf02b000, 0xb0407000, 4096)
08-25 16:37:14.870   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.870   316  6886 V AudioCache: memcpy(0xaf02c000, 0xb0407000, 4096)
08-25 16:37:14.871   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.871   316  6886 V AudioCache: memcpy(0xaf02d000, 0xb0407000, 4096)
08-25 16:37:14.872   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.872   316  6886 V AudioCache: memcpy(0xaf02e000, 0xb0407000, 4096)
08-25 16:37:14.872   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.872   316  6886 V AudioCache: memcpy(0xaf02f000, 0xb0407000, 4096)
08-25 16:37:14.873   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.873   316  6886 V AudioCache: memcpy(0xaf030000, 0xb0407000, 4096)
08-25 16:37:14.874   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.874   316  6886 V AudioCache: memcpy(0xaf031000, 0xb0407000, 4096)
08-25 16:37:14.875   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.875   316  6886 V AudioCache: memcpy(0xaf032000, 0xb0407000, 4096)
08-25 16:37:14.875   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.875   316  6886 V AudioCache: memcpy(0xaf033000, 0xb0407000, 4096)
08-25 16:37:14.876   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.876   316  6886 V AudioCache: memcpy(0xaf034000, 0xb0407000, 4096)
08-25 16:37:14.877   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.877   316  6886 V AudioCache: memcpy(0xaf035000, 0xb0407000, 4096)
08-25 16:37:14.877   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.877   316  6886 V AudioCache: memcpy(0xaf036000, 0xb0407000, 4096)
,08-25 16:37:14.878   316  6886 V AudioCache: write(0xb0407000, 4096)
08-25 16:37:14.878   316  6886 V AudioCache: memcpy(0xaf037000, 0xb0407000, 4096)
08-25 16:37:14.879   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 16:37:14.879   316  6886 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 16:37:14.879   316  6886 V AwesomePlayer: postAudioEOS() 
08-25 16:37:14.879   316  6886 V AudioCache: write(0xb0407000, 280)
08-25 16:37:14.879   316  6886 V AudioCache: memcpy(0xaf038000, 0xb0407000, 280)
08-25 16:37:14.880   316  6883 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 16:37:14.880   316  6883 V AwesomePlayer: onStreamDone
08-25 16:37:14.880   316  6883 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 16:37:14.880   316  6883 V AudioCache: notify(0xb04098c0, 2, 0, 0)
08-25 16:37:14.880   316  6883 V AudioCache: playback complete
08-25 16:37:14.880   316  6883 V AwesomePlayer: pause_l() 
08-25 16:37:14.880   316  6883 V AudioCache: notify(0xb04098c0, 7, 0, 0)
08-25 16:37:14.880   316  6883 V AudioCache: ignored
08-25 16:37:14.880   316  6883 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:14.880   316  6883 D AudioPlayer: Pause Playback at 1068125
08-25 16:37:14.880   316  1397 V AudioCache: wait - success
08-25 16:37:14.880   316  1397 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 16:37:14.881   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:14.881   316  1397 V AudioCache: notify(0xb04098c0, 8, 0, 0)
08-25 16:37:14.881   316  1397 V AudioCache: ignored
08-25 16:37:14.881   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:14.881   316  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 16:37:14.881   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 16:37:14.881   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 16:37:14.881   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 16:37:14.881   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-25 16:37:14.881   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 1
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 16:,37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:14.882   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 16:37:14.882   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 16:37:14.882   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 16:37:14.883   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 16:37:14.883   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 16:37:14.883   316  6885 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 16:37:14.883   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 16:37:14.883   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 16:37:14.883   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 16:37:14.884   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-25 16:37:14.885   316  1397 D AudioPlayer: AudioPlayer releasing audio source
08-25 16:37:14.885   316  1397 D AudioPlayer: AudioPlayer done releasing audio source
08-25 16:37:14.885   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:14.885   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:14.885   316  1397 V AwesomePlayer: ~AwesomePlayer call
,08-25 16:37:14.885   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:14.885   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:14.886  6801  6874 V SoundPool: close(31)
08-25 16:37:14.886  6801  6874 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
,08-25 16:37:14.934  1034  1888 I ActivityManager: Process com.android.bluetooth (pid 3889) has died
,08-25 16:37:14.934  1034  1888 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-25 16:37:14.954  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6640
08-25 16:37:14.955  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:37:14.969  6737  6737 D BluetoothPermissionRequest: onReceive
,08-25 16:37:14.971  6737  6737 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 16:37:14.971  6737  6737 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 16:37:14.973  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 16:37:15.025  1034  1887 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6887 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 16:37:15.046   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 424us total 19.639ms
,08-25 16:37:15.065   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 381us total 17.320ms
,08-25 16:37:15.080   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 15.063ms
08-25 16:37:15.096  6887  6887 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 16:37:15.097  6887  6887 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:15.097  6887  6887 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 16:37:15.097  6887  6887 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 16:37:15.101  6563  6563 I UEI.SmartControl: Supports setup maps: true
08-25 16:37:15.103  6563  6563 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 16:37:15.103  6563  6563 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-25 16:37:15.103  6563  6563 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 16:37:15.103  6563  6563 I UEI.SmartControl: ### init IR Blaster...
08-25 16:37:15.106  6563  6563 D serial_port: Configuring serial port
08-25 16:37:15.107  6563  6563 E UEI.SmartControl: UEIBLaster setting for 616
08-25 16:37:15.107  6563  6563 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 16:37:15.107  6563  6563 I UEI.SmartControl: configuring settings for MAXQ616
08-25 16:37:15.107  6563  6563 I UEI.SmartControl: Get version...
08-25 16:37:15.111  6887  6887 D BluetoothAdapterApp: Loading JNI Library
,08-25 16:37:15.125  6563  6904 D UEI.SmartControl: serial port data available: 21
,08-25 16:37:15.133  6887  6887 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f08be66 Instance Count = 1
,08-25 16:37:15.138  6887  6887 D BluetoothAdapterApp: onCreate
,08-25 16:37:15.151  6563  6563 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 16:37:15.151  6563  6563 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 16:37:15.151  6563  6563 I UEI.SmartControl: QS saving settings...
,08-25 16:37:15.153  6563  6563 D UEI.SmartControl: IR Blaster version: 25672567
08-25 16:37:15.157  6887  6887 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 16:37:15.157  6887  6887 D ProfileConfigQcom: Adding HeadsetService
08-25 16:37:15.158  6887  6887 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 16:37:15.158  6887  6887 D ProfileConfigQcom: Adding A2dpService
08-25 16:37:15.159  6887  6887 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 16:37:15.159  6887  6887 D ProfileConfigQcom: Adding HidService
08-25 16:37:15.160  6887  6887 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 16:37:15.160  6887  6887 D ProfileConfigQcom: Adding HealthService
08-25 16:37:15.161  6887  6887 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 16:37:15.162  6887  6887 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 16:37:15.162  6887  6887 D ProfileConfigQcom: Adding PanService
08-25 16:37:15.163  6887  6887 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 16:37:15.164  6887  6887 D ProfileConfigQcom: Adding GattService
08-25 16:37:15.164  6887  6887 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-25 16:37:15.165  6887  6887 D ProfileConfigQcom: Adding BluetoothMapService
08-25 16:37:15.165  6887  6887 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 16:37:15.169  6563  6904 D UEI.SmartControl: serial port data available: 4
08-25 16:37:15.169  6887  6887 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 16:37:15.181  6737  6737 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 16:37:15.186  6887  6887 V LGMDMManagerInternal: Create singleton instance
08-25 16:37:15.197  6563  6908 I UEI.SmartControl: Device manager: loading config....
08-25 16:37:15.198  6563  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 16:37:15.198  6563  6908 D UEI.SmartControl: ----------- loading internal config...
,08-25 16:37:15.199  6563  6563 E UEI.SmartControl: Services init done
08-25 16:37:15.199  6563  6563 D UEI.SmartControl: QS Service init finished
08-25 16:37:15.200  6563  6563 D UEI.SmartControl: QS Service version name: 2.1.91
,08-25 16:37:15.201  6563  6563 D UEI.SmartControl: QS Service version code: 201091
08-25 16:37:15.201  6563  6563 D UEI.SmartControl: Service requested: Control
08-25 16:37:15.205  6563  6908 E UEI.SmartControl: Loading SETTINGS...
08-25 16:37:15.206  6563  6563 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 16:37:15.208  6563  6563 D UEI.SmartControl: Internal service binding...
08-25 16:37:15.208  6801  6801 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 16:37:15.209  6563  6579 I UEI.SmartControl: ------ IControl API: 11
08-25 16:37:15.209  6563  6579 D UEI.SmartControl: File observer start...
08-25 16:37:15.209  6563  6579 E UEI.SmartControl: IR Port is disabled: false
08-25 16:37:15.209  6563  6579 D UEI.SmartControl: Starting file observer...
08-25 16:37:15.210  6563  6579 I UEI.SmartControl: Registering callback...
,08-25 16:37:15.211  6563  6578 I UEI.SmartControl: ------ IControl API: 19
,08-25 16:37:15.212  6563  6578 I UEI.SmartControl: Registering Services Ready callback...
08-25 16:37:15.215  6563  6908 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 16:37:15.237  6563  6907 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 16:37:15.237  6563  6907 D UEI.SmartControl: -----service ready thread exits
08-25 16:37:15.238  6801  6816 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 16:37:15.238  6801  6872 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 16:37:15.239  6801  6872 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 16:37:15.239  6801  6801 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 16:37:15.240  6801  6801 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 16:37:15.241  6563  6579 I UEI.SmartControl: ------ IControl API: 8
,08-25 16:37:15.244  6801  6801 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-25 16:37:15.245  6801  6801 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 16:37:15.246  6801  6801 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 16:37:15.246  6801  6801 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 16:37:15.247  6801  6801 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-25 16:37:15.248  6801  6801 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 16:37:15.249  6801  6801 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 16:37:15.255  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 16:37:15.257  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-25 16:37:15.258  6801  6801 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-25 16:37:15.259  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 16:37:15.264  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 16:37:15.266  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 16:37:15.267  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 16:37:15.270  6801  6801 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472135835269]
08-25 16:37:15.273  6801  6801 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-25 16:37:15.280  1034  2014 I ActivityManager: Killing 6427:com.lge.email/u0a23 (adj 15): empty #17
,08-25 16:37:15.296  6801  6910 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 16:37:15.353  1034  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_6427/cgroup.procs: No such file or directory
08-25 16:37:15.355  6887  6887 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:15.373  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-25 16:37:15.377  6801  6801 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 16:37:15.378  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 16:37:15.378  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 16:37:15.378  6887  6887 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:15.378  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 16:37:15.379  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 16:37:15.379  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-25 16:37:15.379  6887  6887 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:15.379  6887  6887 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 16:37:15.383  6887  6887 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:15.384  6887  6887 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 16:37:15.393  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-25 16:37:15.402  6820  6820 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 16:37:15.404  1034  1648 I ActivityManager: Killing 6041:com.android.gallery3d/u0a27 (adj 15): empty #17
08-25 16:37:15.455  1034  1996 W libprocessgroup: failed to open /acct/uid_10027/pid_6041/cgroup.procs: No such file or directory
,08-25 16:37:16.553  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:16.566  1034  1887 D WifiServiceImplEx: setWifiEnabled: true pid=6658, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 16:37:16.567  1034  1887 D WifiService: setWifiEnabled: true pid=6658, uid=10118
08-25 16:37:16.567  1034  1887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:37:16.570  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 16:37:16.580  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:16.585  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:16.588  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:16.590  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 16:37:16.600  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 16:37:16.601  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-25 16:37:16.603  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:16.607  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:16.608  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:16.610  1034  1400 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 16:37:16.610  1034  1400 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 16:37:16.610  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:16.612  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 16:37:16.612  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 16:37:16.613  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 16:37:16.613  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 16:37:16.613  1034  1400 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 16:37:16.613  1034  1400 E WifiHW  : unknown target_country: EU , set to default
08-25 16:37:16.613  1034  1400 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-25 16:37:16.616  1034  1400 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 16:37:16.616  1034  1400 I WifiUtil: gEnableBmps=1
08-25 16:37:16.623  5738  5738 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 16:37:16.624  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 16:37:16.626  6325  6754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 16:37:16.645  5738  5738 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 16:37:16.663  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:16.718  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:16.733  1034  1942 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6934 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 16:37:16.740  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 16:37:16.741  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 16:37:16.813  6934  6934 I AppUp4:AppBoxCP: onCreate
,08-25 16:37:16.815  6934  6934 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-25 16:37:16.825  6934  6934 I AppUp4:DB:  setFingerPrint start
08-25 16:37:16.826  6934  6934 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 16:37:16.834  6934  6934 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 16:37:16.834  6934  6934 I AppUp4:DB:  SDK version = 21
08-25 16:37:16.834  6934  6934 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-25 16:37:16.837  6934  6934 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-25 16:37:16.838  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-25 16:37:16.838  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:16.841  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 16:37:16.841  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 16:37:16.852  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 16:37:16.915  6934  6934 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 16:37:16.915  6934  6934 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:16.926  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bfcf7c0
,08-25 16:37:16.926  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 16:37:16.926  6934  6934 D AppUp4:CustFacade: isPhone : true
08-25 16:37:16.927  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
08-25 16:37:16.928  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-25 16:37:16.928  6934  6934 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 16:37:16.929  6934  6955 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 16:37:16.929  6934  6955 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 16:37:16.930  6934  6955 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-25 16:37:16.937  1034  2014 I ActivityManager: Killing 6100:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-25 16:37:16.997  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:16.998  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 16:37:17.002  1034  1978 W libprocessgroup: failed to open /acct/uid_10080/pid_6100/cgroup.procs: No such file or directory
08-25 16:37:17.003  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:17.011  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 16:37:17.026  4314  6961 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 16:37:17.032  4314  6962 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:17.032  4314  6962 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 16:37:17.075  1034  1648 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6963 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 16:37:17.151  6963  6963 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 16:37:17.152  6963  6963 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:17.155  6963  6963 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 16:37:17.155  6963  6963 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 16:37:17.261  6963  6963 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 16:37:17.276  6963  6963 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 16:37:17.317  6963  6963 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 16:37:17.352  6963  6963 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:17.353  6963  6963 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:17.387   311   880 D SoftapController: Softap fwReload - Ok
08-25 16:37:17.389  1034  1400 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (768ms)
08-25 16:37:17.391   311   880 D CommandListener: Setting iface cfg
08-25 16:37:17.391   311   880 D CommandListener: Trying to bring down wlan0
08-25 16:37:17.392   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-25 16:37:17.395  1034  1400 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 16:37:17.384  6990  6990 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:17.384  6990  6990 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:17.401  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:17.401  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:17.401  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:17.401  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 16:37:17.401  1034  1096 D Tethering: InitialState.processMessage what=4
08-25 16:37:17.405  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:17.406  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 16:37:17.407  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 16:37:17.408  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 16:37:17.408  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:17.408  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:17.409  1034  1400 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 16:37:17.409  1034  1400 D WifiMonitor: connecting to supplicant
,08-25 16:37:17.433  6990  6990 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 16:37:17.468  6990  6990 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 16:37:17.468  6990  6990 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-25 16:37:17.469  6963  6963 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 16:37:17.499  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 16:37:17.499  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:17.499  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-25 16:37:17.501  6963  6963 I HubEmail: JNI_OnLoad()
08-25 16:37:17.501  6963  6963 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 16:37:17.501  6963  6963 I HubEmail: registerNatives()
08-25 16:37:17.501  6963  6963 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 16:37:17.501  6963  6963 I HubEmail: registerNativeMethods()
08-25 16:37:17.501  6963  6963 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 16:37:17.502  6963  6963 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-25 16:37:17.526  1034  1996 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7004 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-25 16:37:17.532  6990  6990 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 16:37:17.534  6963  7002 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:17.539  6840  7001 W FormManager: Network not available. Please check & try again.
08-25 16:37:17.541  6840  7003 V FormManager: Network unavailable.
08-25 16:37:17.542  6840  7003 V FormManager: Network unavailable.
08-25 16:37:17.546  1034  1052 I ActivityManager: Killing 6465:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-25 16:37:17.585  6990  6990 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 16:37:17.585  1034  1996 W libprocessgroup: failed to open /acct/uid_10061/pid_6465/cgroup.procs: No such file or directory
08-25 16:37:17.587  6990  6990 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 16:37:17.588  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 16:37:17.589  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 16:37:17.589  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 16:37:17.589  1034  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 16:37:17.589  1034  7021 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 16:37:17.589  1034  1400 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 16:37:17.589  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:17.590  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:17.590  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:17.590  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:17.591  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 16:37:17.591  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 16:37:17.591  6990  6990 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 16:37:17.591  1034  1400 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 16:37:17.591  1034  1400 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 16:37:17.592  1034  1400 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 16:37:17.592  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 16:37:17.592  1034  1400 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 16:37:17.592  1034  1400 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 16:37:17.592  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 16:37:17.592  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 16:37:17.592  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 16:37:17.595  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:17.595  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:17.595  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:17.595  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.595  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.595  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.595  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.596  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 16:37:17.596  1034  1400 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 16:37:17.596  1034  1400 D WifiNative-wlan0: SET update_config 1: returned true
08-25 16:37:17.597  1034  1400 D WifiConfigStore: Loading config and enabling all networks 
08-25 16:37:17.597  1034  1400 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 16:37:17.597  1943  1943 D WfdService: Waiting for WifiP2p enabling
,08-25 16:37:17.598  1034  1400 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 16:37:17.598  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:17.600  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:17.600  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:17.600  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:17.600  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:17.601  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 16:37:17.601  1034  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 16:37:17.601  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:17.601  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:17.601  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:17.601  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:17.604  1034  1400 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 16:37:17.613  1034  1400 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 16:37:17.613  1034  1400 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 16:37:17.614  1034  1400 D WifiStateMachine: enableVerboseLogging : level 2
08-25 16:37:17.614  1034  1400 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-25 16:37:17.615  1034  1400 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 16:37:17.615  1034  1400 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 16:37:17.615  1034  1400 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 16:37:17.615  1034  1400 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 16:37:17.615  1034  1400 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 16:37:17.616  1034  1400 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 16:37:17.616  1034  1400 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 16:37:17.616  1034  1400 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 16:37:17.616  1034  1400 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 16:37:17.616  1034  1400 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 16:37:17.617  1034  1400 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 16:37:17.617  1034  1400 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 16:37:17.617  1034  1400 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 16:37:17.618  1034  1400 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 16:37:17.618  1034  1400 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 16:37:17.618  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-25 16:37:17.618  1034  1400 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 16:37:17.618  1034  1400 D WifiNative-HAL: Setting external_sim to 1
08-25 16:37:17.618  1034  1400 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 16:37:17.619  1943  2228 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 16:37:17.619  1943  2228 D WfdsService: Set the WFDS Monitor: true
08-25 16:37:17.619  1943  2228 D WfdsMonitor: WfdsMonitorThread create
08-25 16:37:17.619  1943  2228 D WfdsMonitor: WFDS Monitor is created and started
08-25 16:37:17.619  1943  2228 D WfdsService: WiFi: Supplicant connection re-established
08-25 16:37:17.619  1034  1400 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 16:37:17.619  1034  1400 I WifiNative-HAL: startHal
08-25 16:37:17.619  1034  1400 D wifi    : setting scan oui 0xaf4ff640
08-25 16:37:17.620  1034  1400 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 16:37:17.620  1034  1400 I WifiNative-HAL: startHal
08-25 16:37:17.620  1034  1400 D wifi    : setting scan oui 0xaf4ff640
08-25 16:37:17.620  1034  1400 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 16:37:17.621  1034  1400 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 16:37:17.621  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 16:37:17.621  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 16:37:17.621  1943  7022 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 16:37:17.621  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 16:37:17.621  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 16:37:17.621  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 16:37:17.622  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 16:37:17.622  1943  7022 E CtrlSupplicant: Succeed to open control connection
08-25 16:37:17.622  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 16:37:17.622  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 16:37:17.622  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 16:37:17.622  1943  7022 E CtrlSupplicant: Succeed to open monitor connection
08-25 16:37:17.622  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 16:37:17.623  1943  7022 D WfdsMonitor: Supplicant connection established
08-25 16:37:17.623  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 16:,37:17.623  1943  2228 D WfdsService: Connected to the supplicant for wfds
08-25 16:37:17.623  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 16:37:17.624  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 16:37:17.624  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 16:37:17.624  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 16:37:17.624  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 16:37:17.624  6990  6990 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 16:37:17.624  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 16:37:17.624  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 16:37:17.624  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 16:37:17.625  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 16:37:17.626  1034  1400 E WifiNative: : [205,390,578 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 16:37:17.626  1034  1400 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 16:37:17.626  1034  1400 D WifiNative-wlan0: RECONNECT: returned true
08-25 16:37:17.626  1034  1400 D WifiNative-wlan0: doString: [STATUS]
08-25 16:37:17.626  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 16:37:17.626  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 16:37:17.627  1034  1400 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 16:37:17.627  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:17.627  1034  1400 D WifiNative-wlan0: SET ps 1: returned true
08-25 16:37:17.627  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 16:37:17.629   311   880 D CommandListener: Setting iface cfg
08-25 16:37:17.629   311   880 D CommandListener: Trying to bring up p2p0
08-25 16:37:17.629  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 16:37:17.629  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-25 16:37:17.629  1034  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.629  1034  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 16:37:17.629  1034  1391 D LGWifiP2pService: P2pEnablingState
08-25 16:37:17.630  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.630  1034  1557 I WifiNative-HAL: startHal
08-25 16:37:17.630  1034  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.630  1034  1391 D LGWifiP2pService: P2p socket connection successful
08-25 16:37:17.630  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf4ff640
08-25 16:37:17.630  1034  1557 D wifi    : failed to get capabilities : -3
08-25 16:37:17.630  1034  1391 D LGWifiP2pService: P2pEnabledState
08-25 16:37:17.630  1034  1557 E WifiScanningService: could not get scan capabilities
08-25 16:37:17.630  1034  1391 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 16:37:17.630  1034  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 16:37:17.631  1034  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 16:37:17.631  1034  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 16:37:17.631  1034  1391 D WifiNative-p2p0: SET device_name G3: returned true
08-25 16:37:17.631  1034  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 16:37:17.631  1034  1391 D LGWifiP2pService: before postfix = G3
08-25 16:37:17.631  1034  1391 D WifiServerServiceExt: postfix byte check : 2
08-25 16:37:17.631  1034  1391 D LGWifiP2pService: after postfix = G3
08-25 16:37:17.631  1034  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 16:37:17.632  1034  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 16:37:17.632  1034  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 16:37:17.632  1034  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 16:37:17.632  1034  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 16:37:17.632  1034  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 16:37:17.632  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 16:37:17.633  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 16:37:17.633  1943  1943 D WfdsService: WifiP2pState is changed : true
08-25 16:37:17.633  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 16:37:17.633  1034  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 16:37:17.633  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress
08-25 16:37:17.633  1943  2228 D WfdsService: Receive the WFDS_ENABLE Method
08-25 16:37:17.633  1943  2228 D WfdsService: Set the WFDS Monitor: true
08-25 16:37:17.633  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 16:37:17.633  1943  2228 D WfdsService: Connected to the supplicant for wfds
08-25 16:37:17.633  1943  2228 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 16:37:17.633  6990  6990 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 16:37:17.633  1943  2228 D WfdsService: selectPreferredScanChannel [36]
08-25 16:37:17.633  1943  2228 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 16:37:17.634  1034  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 16:37:17.634  1034  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-2,5 16:37:17.634  1034  1400 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 16:37:17.634  1943  1943 D WfdsService: isConnected: false
08-25 16:37:17.634  1034  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 16:37:17.634  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 16:37:17.634  1034  1400 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 16:37:17.634  1034  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 16:37:17.634  1034  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 16:37:17.635  1034  1400 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 16:37:17.635  1034  1400 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 16:37:17.635  1034  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 16:37:17.635  1034  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 16:37:17.635  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=205401  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:17.636  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 16:37:17.636  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 16:37:17.636  1943  1943 D WfdsService: Update P2p Interface State: 3
08-25 16:37:17.638  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.638  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.638  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 16:37:17.638  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:17.638  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 16:37:17.640  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:17.641  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=205407  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:17.642  1034  1400 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 16:37:17.642  1034  1400 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 16:37:17.643  1034  1400 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 16:37:17.643  1034  1400 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 16:37:17.646  6990  6990 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-25 16:37:17.647  1034  1400 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 16:37:17.647  1034  1400 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 16:37:17.647  1034  1400 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 16:37:17.647  1034  1400 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 16:37:17.647  6990  6990 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 16:37:17.648  1034  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 16:37:17.648  1034  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 16:37:17.648  1034  1391 D LGWifiP2pService: InactiveState
08-25 16:37:17.648  1034  1391 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.648  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.648  1034  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 16:37:17.648  1034  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 16:37:17.648  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.649  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 16:37:17.649  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.649  1034  1391 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.649  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.649  6990  6990 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:17.649  1034  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 16:37:17.649  1034  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:17.649  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:17.649  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:17.649  1943  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 16:37:17.650  6990  6990 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 16:37:17.650  6990  6990 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.650  6990  6990 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 16:37:17.651  1943  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.651  1943  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.651  1034  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.651  1034  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.651  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.651  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.651  1034  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.651  1034  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.651  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.651  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.652  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.652  1034  1391 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.652  1034  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.652  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.652  1034  1391 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.652  1943  2228 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 16:37:17.652  1034  1400 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 16:37:17.653  1034  1400 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 16:37:17.653  1034  1391 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.653  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.653  1034  1391 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.653  1034  1400 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 16:37:17.653  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 16:37:17.653  1034  1034 E WifiServerServiceExt: No p2p device connected
08-25 16:37:17.654  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 16:37:17.654  6990  6990 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:17.654  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 16:37:17.654  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 16:37:17.655  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:17.655  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:17.655  6990  6990 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 16:37:17.655  6990  6990 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.655  1943  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.655  1034  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.655  1034  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.655  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.655  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.655  1034  1400 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 16:37:17.655  6990  6990 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.655  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.655  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:17.656  1943  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.656  1034  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:17.656  1034  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.656  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.656  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:17.656  1034  1400 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 16:37:17.657  1034  1400 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 16:37:17.660  1034  1400 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 16:37:17.660  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 16:37:17.660  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 16:37:17.660  6990  6990 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:17.661  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 16:37:17.661  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:17.661  1034  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:17.661  1034  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:17.661  1034  1400 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 16:37:17.661  1034  1400 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 16:37:17.662  1034  1400 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-25 16:37:17.662  1034  1400 D WifiNative-wlan0: doBoolean: SCAN
,08-25 16:37:17.662  1034  1400 D WifiNative-wlan0: SCAN: returned false
08-25 16:37:17.662  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=205428  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:17.663  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=205429  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:17.664  1034  1400 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:17.664  1034  1400 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:17.665  1034  1400 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:17.665  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.665  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:17.665  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 16:37:17.665  1034  1400 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:17.665  1034  1400 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:17.666  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:17.666  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 16:37:17.666  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:17.666  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:17.667  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:17.668  7004  7004 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:17.668  7004  7004 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 16:37:17.671  7004  7004 D PhoneMonitor: Register our PhoneStateListener
,08-25 16:37:17.681  7004  7004 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 16:37:17.683  7004  7004 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 16:37:17.694  7004  7004 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 16:37:17.695  7004  7004 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 16:37:17.695  7004  7004 D TelephonyAutoProfiling: [parse] Load xml
,08-25 16:37:17.701  7004  7004 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 16:37:17.701  7004  7004 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 16:37:17.701  7004  7004 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-25 16:37:17.707  7004  7004 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-25 16:37:17.728  1034  1648 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7025 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 16:37:17.730  1034  1648 I ActivityManager: Killing 6125:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-25 16:37:17.826  1034  1647 W libprocessgroup: failed to open /acct/uid_10097/pid_6125/cgroup.procs: No such file or directory
,08-25 16:37:18.064  1034  1906 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7049 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-25 16:37:18.065  1034  1906 I ActivityManager: Killing 6521:com.lge.eula/1000 (adj 15): empty #17
08-25 16:37:18.124  1034  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6521/cgroup.procs: No such file or directory
,08-25 16:37:18.185  6990  6990 E wpa_supplicant: USIM:  scard_init function
08-25 16:37:18.185  6990  6990 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-25 16:37:18.190  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 16:37:18.190  1034  7021 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 16:37:18.190  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 16:37:18.191  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-25 16:37:18.191  1034  7021 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 16:37:18.191  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 16:37:18.191  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 16:37:18.192  1034  1400 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 16:37:18.192  1034  1400 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 16:37:18.193  1034  1400 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 16:37:18.193  1034  1400 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 16:37:18.193  1034  1400 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 16:37:18.240  1034  1906 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7066 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 16:37:18.241  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206006  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 16:37:18.243  1034  1906 I ActivityManager: Killing 6539:com.lge.bnr/1000 (adj 15): empty #17
,08-25 16:37:18.300  6990  6990 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 16:37:18.303  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 16:37:18.303  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 16:37:18.304  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 16:37:18.304  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 16:37:18.304  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:18.304  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:18.312  6990  6990 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 16:37:18.312  6990  6990 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 16:37:18.313  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:18.313  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 16:37:18.317  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 16:37:18.317  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 16:37:18.317  1034  7021 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 16:37:18.317  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 16:37:18.317  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 16:37:18.317  1034  7021 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 16:37:18.317  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:18.318  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:18.321  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 16:37:18.324  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.324  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:18.326  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:18.328  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206093  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 16:37:18.329  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206094  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 16:37:18.330  1034  1400 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206095
08-25 16:37:18.330  1034  1400 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206096
08-25 16:37:18.332  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.332  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.332  1034  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6539/cgroup.procs: No such file or directory
08-25 16:37:18.332  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 16:37:18.334  1034  1400 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206099
08-25 16:37:18.340  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206105
,08-25 16:37:18.341  1034  1400 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206107
08-25 16:37:18.343  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206108  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 16:37:18.350  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 16:37:18.357  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.357  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 16:37:18.360  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.361  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.361  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.361  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 16:37:18.362  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206127  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 16:37:18.364  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206129  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 16:37:18.364  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206129  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 16:37:18.365  1034  1400 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206130
08-25 16:37:18.365  1034  1400 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206131
08-25 16:37:18.366  1034  1400 D WifiNative-wlan0: doString: [STATUS]
08-25 16:37:18.367  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:18.367  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:18.367  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.367  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.368  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 16:37:18.369  1034  1400 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 16:37:18.370  1034  1400 I WifiServiceExtension: setVHTCapabilityType  : false
,08-25 16:37:18.379  1034  1400 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 16:37:18.379  1034  1400 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 16:37:18.382  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:18.383  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.383  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 16:37:18.385  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.385  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:18.386  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.386  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.386  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 16:37:18.387  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.388  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.389  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:18.389  7066  7066 I art     : Almond Protected OAT
08-25 16:37:18.391  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.392  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.392  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:18.393  1034  1400 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 16:37:18.393  1034  1400 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 16:37:18.393  1034  1400 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 16:37:18.394  1034  1400 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 16:37:18.394  1034  1400 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 16:37:18.395  1034  1469 D ConnectivityService: Got NetworkAgent Messenger
08-25 16:37:18.395  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 16:37:18.395  1034  1469 D ConnectivityService: NetworkAgent connected
08-25 16:37:18.396  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.398  1034  1400 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 16:37:18.399  1034  1400 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 16:37:18.399  1034  1400 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 16:37:18.399  1034  1400 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 16:37:18.399  1034  1400 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 16:37:18.404  1034  1400 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 16:37:18.406   311   880 D CommandListener: Setting iface cfg
,08-25 16:37:18.409  1034  1400 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 16:37:18.409  1034  1400 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206174  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:18.410  1034  1400 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206175  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:18.410  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206175  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:18.411  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:18.412  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:18.412  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:18.412  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 16:37:18.412  1034  1400 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:18.412  1034  1400 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:18.413  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:18.413  1034  7095 D DhcpStateMachine: StoppedState
08-25 16:37:18.413  1034  7095 D DhcpStateMachine: StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.413  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:18.413  1034  7095 D DhcpStateMachine: WaitBeforeStartState
08-25 16:37:18.414  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:18.414  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 16:37:18.415  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:18.415  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 16:37:18.415  1034  1400 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206181  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:18.416  1034  1400 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206181  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:18.416  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=206181  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:18.417  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:160360] from screen [on:0 period:-1037944111] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 16:37:18.418  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1037944110] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 16:37:18.418  1034  1400 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 16:37:18.424  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.425  1034  1469 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 16:37:18.425  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.426  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.427  1034  1400 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.427  1034  1400 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.428  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.428  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.428  1034  1469 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 16:37:18.429  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:18.429  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-25 16:37:18.429  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 16:37:18.430  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
,08-25 16:37:18.430  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 16:37:18.430  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 16:37:18.432  1034  1400 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 16:37:18.432  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 16:37:18.432  1034  1400 D WifiNative-wlan0: SET ps 0: returned true
08-25 16:37:18.432  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 16:37:18.432  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 16:37:18.433  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 16:37:18.433  1034  1400 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 16:37:18.433  1034  1400 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 16:37:18.433  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24d114aa target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.433  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24d114aa target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.433  1034  7095 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.434  1034  7095 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 16:37:18.434  1034  1400 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 16:37:18.434   311   880 D CommandListener: Setting iface cfg
08-25 16:37:18.435   311   880 D CommandListener: Trying to bring up wlan0
08-25 16:37:18.436  1034  1400 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 16:37:18.437  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:18.437  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 16:37:18.437  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.437  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.438  1034  1400 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.438  1034  1400 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.439  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.439  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:18.440  1034  1469 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-25 16:37:18.441  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 16:37:18.441  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 16:37:18.441  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 16:37:18.442  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.442  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.442  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 16:37:18.443  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 16:37:18.443  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 16:37:18.443  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 16:37:18.443  1034  1400 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 16:37:18.443  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:18.445  7066  7066 D WeatherApplication: removeAccount
08-25 16:37:18.446  7066  7066 D WeatherApplication: Account.length = 0
08-25 16:37:18.446  7066  7066 E WeatherApplication: OPERATOR:OPEN
08-25 16:37:18.451  7066  7066 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:18
08-25 16:37:18.454  7066  7066 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-25 16:37:18.454  7066  7066 D Weather.Utils: 2 : All the weather widget is gone.
08-25 16:37:18.456  7066  7066 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 16:37:18.458  7066  7066 D WeatherAncestor: connectivity changed - connection : true
08-25 16:37:18.459  1034  1400 D WifiNative-wlan0: SET ps 1: returned true
08-25 16:37:18.459  1034  1469 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 16:37:18.459  7066  7066 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-25 16:37:18.460  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 16:37:18.460  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 16:37:18.460  1034  1400 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 16:37:18.461  1034  1469 D ConnectivityService: ignoring duplicate network state non-change
08-25 16:37:18.462  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 16:37:18.463  1034  1469 D ConnectivityService: Adding iface wlan0 to network 101
08-25 16:37:18.464  1034  1400 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 16:37:18.468  7066  7066 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 16:37:18.468  7066  7066 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-25 16:37:18.469  7066  7066 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-25 16:37:18.487  7066  7066 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-25 16:37:18.487  7066  7066 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:18
08-25 16:37:18.490  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.490  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:18.492  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.492  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.492  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 16:37:18.493  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.496  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.496  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.496  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 16:37:18.497  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 16:37:18.497  1034  1469 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 16:37:18.497  1034  1469 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 16:37:18.498  1034  1469 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 16:37:18.499  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 16:37:18.499   311   880 E Netd    : netlink response contains error (File exists)
08-25 16:37:18.500  1034  1469 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 16:37:18.501  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.501  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.501  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 16:37:18.501  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 16:37:18.501  1034  1469 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 16:37:18.501  1034  1469 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 16:37:18.501  1034  1469 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 16:37:18.505  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.505  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:18.505  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 16:37:18.515  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.515  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 16:37:18.516  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.519  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.520  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 16:37:18.520  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.524  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:18.525  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 16:37:18.525  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.543  1034  1887 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7100 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 16:37:18.544  1034  1887 I ActivityManager: Killing 2153:com.lge.music/u0a34 (adj 15): empty #17
,08-25 16:37:18.550  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.550  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.550  1034  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.554  1034  1400 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 16:37:18.555  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 16:37:18.555  1034  1400 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 16:37:18.555  1034  1400 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 16:37:18.555  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 16:37:18.556  1034  1400 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 16:37:18.560   316  2150 V AudioFlinger: 2153 died, releasing its sessions
08-25 16:37:18.560   316  2150 V AudioFlinger:  pid 1853 @ 0
08-25 16:37:18.560   316  2150 V AudioFlinger:  pid 3435 @ 1
08-25 16:37:18.560   316  2150 V AudioFlinger:  pid 3435 @ 2
,08-25 16:37:18.592  1034  1469 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 16:37:18.592  1034  1888 W libprocessgroup: failed to open /acct/uid_10034/pid_2153/cgroup.procs: No such file or directory
08-25 16:37:18.592  1034  1469 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 16:37:18.592  1034  1469 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 16:37:18.592  1034  1469 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,08-25 16:37:18.593  1034  1469 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 16:37:18.593  1034  1469 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:18.593  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.593  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 16:37:18.593  1034  1469 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 16:37:18.593  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:18.593  1034  1469 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.593  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 16:37:18.593  1034  1469 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 16:37:18.593  1034  1469 D ConnectivityService: currentScore = 0, newScore = 20
08-25 16:37:18.593  1034  1469 D ConnectivityService:    accepting network in place of null
08-25 16:37:18.593  1034  1469 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.594  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.595  1034  1400 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.595  1034  1400 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:18.595  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 16:37:18.596   311  7118 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 16:37:18.596  1034  1469 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 16:37:18.596  1034  1469 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 16:37:18.596  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 16:37:18.598  1034  1469 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:18.598  1034  1469 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 16:37:18.602  1034  1469 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisi,oningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 16:37:18.603  1034  1469 D ConnectivityService: validation of new default Network = false
08-25 16:37:18.603  1034  1469 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 16:37:18.603  1034  1469 D DSQN    : enableDataServiceNotify 
08-25 16:37:18.603  1034  1469 D DSQN    : start dsqn bin
08-25 16:37:18.605  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 16:37:18.605  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 16:37:18.605  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 16:37:18.606  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-25 16:37:18.611  1034  1469 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 16:37:18.611  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.611  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:18.611  1034  1469 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:18.612  1603  2077 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 16:37:18.604  7119  7119 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:18.604  7119  7119 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 16:37:18.634  7119  7119 E DSQN    : DSQN ssw
,08-25 16:37:18.635  1034  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-25 16:37:18.636  1034  7095 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 16:37:18.637  1034  7095 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 16:37:18.637  1034  7095 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 16:37:18.624  7124  7124 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:18.624  7124  7124 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:18.649  7124  7124 I dhcpcd  : version 5.5.6 starting
08-25 16:37:18.651  7124  7124 E dhcpcd  : get_duid: m
08-25 16:37:18.651  7124  7124 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 16:37:18.651  7124  7124 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 16:37:18.652   311  7118 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-25 16:37:18.658  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 16:37:18.659  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.659  1818  7121 I CheckinService: active receiver: enabled
08-25 16:37:18.660  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:18.672  1818  7121 I CheckinService: Preparing to send checkin request
08-25 16:37:18.672  1818  7121 I EventLogService: Accumulating logs since 1472135690296
08-25 16:37:18.691   311  7118 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 16:37:18.697  7124  7124 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 16:37:18.698  7124  7124 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 16:37:18.698  7124  7124 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 16:37:18.698  7124  7124 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 16:37:18.698  7124  7124 D dhcpcd  : wlan0: sending REQUEST (xid 0x5bda99e7), next in 4.21 seconds
08-25 16:37:18.703  1818  7121 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-25 16:37:18.718   311   879 D LGDataListener: argv[0]=dsqncommand
,08-25 16:37:18.718   311   879 D LGDataListener: argv[1]=wlan0
08-25 16:37:18.718   311   879 D LGDataListener: argv[2]=1
08-25 16:37:18.718   311   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 16:37:18.718  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 16:37:18.718  1034  1094 D DSQN    : start to monitor internet connection
08-25 16:37:18.724   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 16:37:18.724   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 16:37:18.724   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 16:37:18.724  7124  7124 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 16:37:18.725  7100  7135 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 16:37:18.728   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 16:37:18.728   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 16:37:18.728   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 16:37:18.728  7100  7135 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-25 16:37:18.738   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 16:37:18.738   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 16:37:18.738   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 16:37:18.738  7100  7137 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 16:37:18.740   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 16:37:18.740   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 16:37:18.740   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 16:37:18.741  7100  7137 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 16:37:18.743  7124  7124 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 16:37:18.743  7124  7124 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 16:37:18.743  7124  7124 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 16:37:18.743  7124  7124 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 16:37:18.743  7124  7124 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 16:37:18.744  7124  7124 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 16:37:18.744  7124  7124 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 16:37:18.744  7124  7124 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 16:37:18.753  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 14:37:18 GMT], X-Android-Received-Millis=[1472135838753], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472135838717]}
,08-25 16:37:18.754  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 16:37:18.754  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 16:37:18.754  1034  1469 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 16:37:18.754  1034  1469 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 16:37:18.754  1034  1469 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:18.754  1034  1469 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:18.754  1034  1469 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 16:37:18.754  1034  1469 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 16:37:18.754  1034  1469 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 16:37:18.754  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.754  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:18.754  1034  1469 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:18.755  1034  1469 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.755  1603  2077 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 16:37:18.755  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 16:37:18.755  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.755  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 16:37:18.756  1034  1400 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:18.756  1034  1400 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:18.801  1034  1052 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7148 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 16:37:18.809  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 16:37:18.810  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:18.811  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:18.844  7148  7148 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 16:37:18.845  7148  7148 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 16:37:18.864  7148  7148 I MultiDex: VM with version 2.1.0 has multidex support
08-25 16:37:18.865  7148  7148 I MultiDex: install
08-25 16:37:18.865  7148  7148 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 16:37:18.872  7148  7148 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-25 16:37:18.929  7100  7100 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 16:37:18.935  7100  7100 I LibraryLoader: Loading: webviewchromium
08-25 16:37:18.937  7100  7100 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6711-6714)
08-25 16:37:18.937  7100  7100 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 16:37:18.945  7100  7100 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8b047ab}
,08-25 16:37:18.947  7100  7100 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 16:37:18.948  7100  7100 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 16:37:18.964  7100  7100 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 16:37:18.965  7100  7100 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 16:37:18.980  7100  7100 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 16:37:18.982  7100  7100 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 16:37:18.982  7100  7100 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 16:37:18.988   316   316 V AudioPolicyService: registerClient() client 0xb57ebf20, uid 10093
08-25 16:37:18.989  7100  7197 W AudioManagerAndroid: Requires BLUETOOTH permission
08-25 16:37:18.999  7100  7100 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:18.999  7100  7100 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:18.999  7100  7100 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:18.999  7100  7100 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:18.999  7100  7100 I Adreno-EGL: Remote Branch: 
08-25 16:37:18.999  7100  7100 I Adreno-EGL: Local Patches: 
08-25 16:37:18.999  7100  7100 I Adreno-EGL: Reconstruct Branch: 
,08-25 16:37:19.039  1034  7095 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-25 16:37:19.041  1034  7095 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 16:37:19.041  1034  7095 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 16:37:19.041  1034  7095 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 16:37:19.041  1034  7095 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 16:37:19.041  1034  7095 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 16:37:19.041  1034  7095 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 16:37:19.041  1034  7095 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 16:37:19.042  1034  7095 D DhcpStateMachine: RunningState
,08-25 16:37:19.077  7100  7100 I NSApplication: Starting up...
,08-25 16:37:19.150  1034  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7210 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 16:37:19.153  1034  1050 I ActivityManager: Killing 6062:com.android.vending/u0a44 (adj 15): empty #17
08-25 16:37:19.259  1034  1941 W libprocessgroup: failed to open /acct/uid_10044/pid_6062/cgroup.procs: No such file or directory
,08-25 16:37:19.310  7210  7210 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 16:37:19.489  1034  1888 I art     : Explicit concurrent mark sweep GC freed 99726(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.238ms total 95.621ms
,08-25 16:37:19.563  7148  7167 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:19.563  7148  7167 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:19.611  1034  1469 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 16:37:19.614  1034  1888 D WifiServiceImplEx: setWifiEnabled: false pid=6658, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 16:37:19.614  1034  1888 D WifiService: setWifiEnabled: false pid=6658, uid=10118
08-25 16:37:19.614  1034  1888 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:37:19.623  7230  7230 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 16:37:19.625  1034  1400 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:19.626  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:19.626  1034  1400 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:19.627  1034  1400 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:19.627  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 16:37:19.627  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 16:37:19.627  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 16:37:19.627  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:19.627  1034  1400 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 16:37:19.627  1034  1400 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 16:37:19.627  1034  1400 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 16:37:19.628  1034  1400 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 16:37:19.628  1034  1400 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 16:37:19.638  1034  1400 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 16:37:19.638  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 16:37:19.638  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 16:37:19.638  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.638  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 16:37:19.638  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.638  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:19.639  1034  1400 D WifiNative-wlan0: SET ps 1: returned true
08-25 16:37:19.639   311   880 D CommandListener: Clearing all IP addresses on wlan0
,08-25 16:37:19.653  1034  7095 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.670  7230  7230 I dex2oat : dex2oat took 47.070ms (threads: 4)
,08-25 16:37:19.678  7148  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:19.678  7148  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:19.678  7148  7167 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:19.678  7148  7167 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:19.678  7148  7167 I Adreno-EGL: Remote Branch: 
08-25 16:37:19.678  7148  7167 I Adreno-EGL: Local Patches: 
08-25 16:37:19.678  7148  7167 I Adreno-EGL: Reconstruct Branch: 
08-25 16:37:19.680  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 16:37:19.680  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-25 16:37:19.681  1034  1400 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:19.681  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:19.681  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:19.681  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 16:37:19.681  1034  1400 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:19.682  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:19.682  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:19.682  1034  1400 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 16:37:19.683  1034  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.683  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.683  1034  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@14d6025e
08-25 16:37:19.684  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 16:37:19.685  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:19.685  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:19.686  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:19.687  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:19.687  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:19.691  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 16:37:19.691  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:19.691  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:19.691  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 16:37:19.691  1034  1034 D WifiHS20: hidePasspointNotification off =false
,08-25 16:37:19.696  1034  1391 D LGWifiP2pService: P2pDisablingState
08-25 16:37:19.696  1034  1391 D LGWifiP2pService: P2pDisablingState{ when=-13ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.696  1034  1391 D LGWifiP2pService: p2p socket connection lost
08-25 16:37:19.696  1034  1391 D LGWifiP2pService: P2pDisabledState
,08-25 16:37:19.697  1034  1400 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 16:37:19.697  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:19.697  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 16:37:19.697  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:19.697  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 16:37:19.697  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 16:37:19.697  6990  6990 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 16:37:19.697  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-25 16:37:19.697  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.698  1034  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.698  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.698  1034  1391 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.699  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:19.700  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 16:37:19.700  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:19.700  1034  1400 D WifiNative-wlan0: SET ps 1: returned true
08-25 16:37:19.704  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 16:37:19.704  1943  1943 D WfdsService: WifiP2pState is changed : false
08-25 16:37:19.705  1943  2228 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 16:37:19.705  1943  2228 D WfdsService: Set the WFDS Monitor: false
08-25 16:37:19.707  1943  2228 D WfdsMonitor: WFDS Monitor is stopped
08-25 16:37:19.707  1943  2228 D WfdsService: STATE : WfdsDisabledState - enter
,08-25 16:37:19.707  1943  7022 D CtrlSupplicant: Received on exit socket, terminate
08-25 16:37:19.708  1943  7022 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 16:37:19.708  1943  7022 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 16:37:19.708  1943  7022 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 16:37:19.709  1943  2231 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 16:37:19.709  1943  2228 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 16:37:19.713  6325  6754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 16:37:19.728  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:19.731  2208  2208 W GCM     : ACTIVE NETWORK NOT CONNECTED
08-25 16:37:19.734  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 16:37:19.734  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:19.734  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 16:37:19.734  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 16:37:19.735  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
08-25 16:37:19.736   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-25 16:37:19.736  1034  1469 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 16:37:19.736  1034  1469 D DSQN    : disableDataServiceNotify,
08-25 16:37:19.736  1034  1469 D DSQN    : stop dsqn bin
08-25 16:37:19.736  1034  1942 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-25 16:37:19.737  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.737  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.737  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 16:37:19.737  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.737  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-25 16:37:19.737  1034  1400 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 16:37:19.738  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 16:37:19.738  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-25 16:37:19.738  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:19.739  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:19.739  1034  1400 D WifiNative-p2p0: TERMINATE: returned true
08-25 16:37:19.739  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:19.739  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:19.739  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:19.740   311  7255 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 16:37:19.740  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 16:37:19.740  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:19.740  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:19.740  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-25 16:37:19.743  1034  1469 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 16:37:19.743  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:19.743  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:19.744  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 16:37:19.744  1034  1469 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:19.744  1034  1469 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 16:37:19.745  1034  1469 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 16:37:19.745  1034  1469 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 16:37:19.745  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 16:37:19.745  1603  2077 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 16:37:19.745  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 16:37:19.746  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:19.746  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 16:37:19.746  1034  1469 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:19.746  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
08-25 16:37:19.746  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 16:37:19.746  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.746  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.746  1034  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 16:37:19.746  1034  1469 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:19.746  1034  1469 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:19.746  1034  1469 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:19.747  1034  1469 D NetworkManagementService: Removing idletimer
08-25 16:37:19.747  1034  1469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:19.747  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 16:37:19.747  10,34  1400 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:19.747  1034  1400 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:19.748  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 16:37:19.748  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 16:37:19.748  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 16:37:19.748  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 16:37:19.748  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:19.748  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 16:37:19.748  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 16:37:19.750  1034  1469 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 16:37:19.750  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:19.750  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 16:37:19.751  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 16:37:19.751  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 16:37:19.751  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:19.751  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:19.751  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:19.751  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:19.752  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:19.752  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:19.752  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:19.7,52  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:19.752  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:19.752  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:19.752  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:19.752  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:19.752  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:19.752  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:19.752  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:19.760  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:19.762  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bfcf7c0
08-25 16:37:19.762  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 16:37:19.762  6934  6934 D AppUp4:CustFacade: isPhone : true
08-25 16:37:19.764  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
08-25 16:37:19.764  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 16:37:19.769  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:19.770  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 16:37:19.771  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:19.774  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:19.783  6963  6963 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 16:37:19.786  4314  7259 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 16:37:19.791  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 16:37:19.791  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:19.791  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:19.802  6963  7261 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:19.803  4314  7260 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:19.803  4314  7260 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 16:37:19.804  6840  7264 W FormManager: Network not available. Please check & try again.
08-25 16:37:19.805  7148  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:19.805  7148  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:19.805  7148  7167 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:19.805  7148  7167 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:19.805  7148  7167 I Adreno-EGL: Remote Branch: 
08-25 16:37:19.805  7148  7167 I Adreno-EGL: Local Patches: 
08-25 16:37:19.805  7148  7167 I Adreno-EGL: Reconstruct Branch: 
08-25 16:37:19.806  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 16:37:19.808  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:19.808  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 16:37:19.810  6840  7265 V FormManager: Network unavailable.
08-25 16:37:19.814  7004  7004 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 16:37:19.814  7004  7004 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 16:37:19.817  6840  7265 V FormManager: Network unavailable.
08-25 16:37:19.821  7066  7066 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:19
08-25 16:37:19.823  7066  7066 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-25 16:37:19.823  7066  7066 D Weather.Utils: 2 : All the weather widget is gone.
08-25 16:37:19.824  6990  6990 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 16:37:19.824  6990  6990 I wpa_supplicant: monitor socket send errors count : 1
08-25 16:37:19.824  6990  6990 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-25 16:37:19.825  7066  7066 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 16:37:19.825  7066  7066 D WeatherAncestor: connectivity changed - connection : true
08-25 16:37:19.825  7066  7066 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3327343e
08-25 16:37:19.826  1034  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 16:37:19.826  1034  7021 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 16:37:19.828  7066  7066 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 16:37:19.828  7066  7066 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 16:37:19.828  7066  7066 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 16:37:19.828  7066  7066 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 16:37:19.828  7066  7066 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:19
08-25 16:37:19.832  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 16:37:19.832  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:19.832  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:19.850  7148  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:19.850  7148  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:19.850  7148  7167 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:19.850  7148  7167 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:19.850  7148  7167 I Adreno-EGL: Remote Branch: 
08-25 16:37:19.850  7148  7167 I Adreno-EGL: Local Patches: 
08-25 16:37:19.850  7148  7167 I Adreno-EGL: Reconstruct Branch: 
08-25 16:37:19.855  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 16:37:19.855  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 16:37:19.855  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 16:37:19.855  6737  6737 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 16:37:19.856  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 16:37:19.856  6737  6737 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 16:37:19.856  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 16:37:19.856  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 16:37:19.856  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 16:37:19.856  6737  6737 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 16:37:19.856  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
,08-25 16:37:19.857  6737  6737 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 16:37:19.863  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:19.863  6990  6990 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 16:37:19.864  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 16:37:19.864  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 16:37:19.864  1034  7021 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 16:37:19.864  1034  7095 D DhcpStateMachine: StoppedState
08-25 16:37:19.864  1034  7095 D DhcpStateMachine: StoppedState{ when=-164ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:19.864  1034  7021 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 16:37:19.864  1034  1096 D Tethering: InitialState.processMessage what=4
08-25 16:37:19.864  1034  1400 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207630
08-25 16:37:19.864  6990  6990 W wpa_supplicant: USIM:  scard_deinit function
08-25 16:37:19.865  1034  1400 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207630
08-25 16:37:19.865  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:19.865  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:19.866  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 16:37:19.867  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 16:37:19.867  1034  1400 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=207632  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 16:37:19.867  1034  1400 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=207632  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 16:37:19.867  1034  1400 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-25 16:37:19.867  1034  1400 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 16:37:19.868  1034  1400 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:19.868  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:19.873  6840  7273 W FormManager: Network not available. Please check & try again.
08-25 16:37:19.876  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 16:37:19.879  6840  7274 V FormManager: Network unavailable.
08-25 16:37:19.883  6840  7274 V FormManager: Network unavailable.
08-25 16:37:19.886  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:19.888  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 16:37:19.894  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:19.895  6840  7275 W FormManager: Network not available. Please check & try again.
08-25 16:37:19.898  6840  7276 V FormManager: Network unavailable.
08-25 16:37:19.901  6840  7276 V FormManager: Network unavailable.
,08-25 16:37:19.903  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 16:37:19.903  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 16:37:19.904  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:19.905  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:19.908  4314  7277 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 16:37:19.912  4314  7278 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 16:37:19.912  4314  7278 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 16:37:19.939  1034  1960 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7279 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 16:37:19.950   311  7297 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 16:37:19.951  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 16:37:19.951  1818  7121 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-25 16:37:19.955  1034  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332546535, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-25 16:37:19.965  6990  6990 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 16:37:19.965  1034  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 16:37:19.965  1034  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 16:37:19.965  1034  7021 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 16:37:19.966  1034  1400 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-25 16:37:19.967  1818  7121 I CheckinService: active receiver: disabled
,08-25 16:37:19.981  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
08-25 16:37:20.007  7279  7279 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 16:37:20.007  7279  7279 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-25 16:37:20.010  7279  7279 V [BNRBootReceiver]: Boot Receiver Return
08-25 16:37:20.013  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.014  7279  7279 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 16:37:20.021  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.024  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.031  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 16:37:20.031  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.033  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 16:37:20.036  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.043  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.050  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.057  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 16:37:20.057  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.058  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 16:37:20.066  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 16:37:20.066  1034  1400 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 16:37:20.067  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:20.067  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:20.067  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:20.068  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-25 16:37:20.068  1943  2228 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-25 16:37:20.068  1943  2228 D WfdsService: Set the WFDS Monitor: false
08-25 16:37:20.068  1943  2228 D WfdsMonitor: WFDS Monitor is stopped
,08-25 16:37:20.071  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:20.072  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 16:37:20.073  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 16:37:20.073  1034  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 16:37:20.073  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:20.073  1034  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 16:37:20.078  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:20.078  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:20.079  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:20.079  6737  6737 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 16:37:20.091  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:20.102  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.110  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.117  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.117  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.117  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 16:37:20.121  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.127  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.133  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.140  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 16:37:20.140  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.141  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:20.145  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:20.153  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.162  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 16:37:20.176  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.176  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 16:37:20.177  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:20.186  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.197  6563  6909 D UEI.SmartControl: Internal timer expired: 2
08-25 16:37:20.198  6563  6909 D UEI.SmartControl: unbind internal service
08-25 16:37:20.198  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.206  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.215  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 16:37:20.217  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.218  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:20.225  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.240  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.247  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.256  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.257  6563  6906 D serial_port: close(fd = 24)
08-25 16:37:20.257  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 16:37:20.259  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:20.262  6563  6906 I UEI.SmartControl: Serial port is closed.
08-25 16:37:20.275  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:20.299  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.307  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.319  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.319  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 16:37:20.328  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:20.335  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.359  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.370  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 16:37:20.382  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.382  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.384  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 16:37:20.391  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.396  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 16:37:20.406  1034  1457 D WifiService: New client listening to asynchronous messages
08-25 16:37:20.407  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:20.412  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.419  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.427  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 16:37:20.428  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.429  6801  6801 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 16:37:20.431  6801  6801 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 16:37:20.431  6801  6801 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 16:37:20.439  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:20.444  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 16:37:20.449  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:20.455  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.466  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.476  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 16:37:20.476  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.478  6801  6801 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 16:37:20.479  6801  6801 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 16:37:20.479  6801  6801 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 16:37:20.484  1034  1996 I ActivityManager: Killing 6777:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-25 16:37:20.515  1034  1576 W libprocessgroup: failed to open /acct/uid_10037/pid_6777/cgroup.procs: No such file or directory
,08-25 16:37:20.525  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 16:37:20.541  2208  2208 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-25 16:37:20.542  2208  2208 D c       : Getting all permits...
,08-25 16:37:20.542  2208  2208 D a       : Opening database...
08-25 16:37:20.550  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-25 16:37:20.552  2208  2208 D a       : Closing database...
08-25 16:37:20.571  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:20.582  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 16:37:20.582  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 16:37:20.582  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:20.590  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.607  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 16:37:20.625  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.627  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 16:37:20.631  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 16:37:20.642  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:20.656  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 16:37:20.656  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 16:37:20.656  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:20.669  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.682  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.694  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.694  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 16:37:20.698  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 16:37:20.705  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:20.714  6756  6756 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 16:37:20.714  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 16:37:20.714  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:20.718  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:20.730  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.740  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:20.740  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:20.742  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 16:37:20.754  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 16:37:20.764  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 16:37:20.768  6840  7306 W FormManager: Network not available. Please check & try again.
,08-25 16:37:20.773  6840  7307 V FormManager: Network unavailable.
08-25 16:37:20.776  6840  7307 V FormManager: Network unavailable.
08-25 16:37:20.779  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 16:37:20.814  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 16:37:20.814  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 16:37:20.814  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 16:37:20.814  6737  6737 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 16:37:20.816  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 16:37:20.817  6737  6737 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 16:37:20.817  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 16:37:20.818  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 16:37:20.818  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 16:37:20.818  6737  6737 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 16:37:20.818  6737  6737 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 16:37:20.825  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-25 16:37:20.826  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6640
08-25 16:37:20.827  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332546535 [*alarm*], flags=0x0
,08-25 16:37:20.832  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-25 16:37:20.860  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 16:37:20.860  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 16:37:20.864  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:20.869  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:20.878  6756  6756 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 16:37:20.878  4314  7308 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 16:37:20.878  6756  6756 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-25 16:37:20.879  6756  6756 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 16:37:20.885  4314  7310 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 16:37:20.886  4314  7310 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 16:37:20.888  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 16:37:20.897  6840  7311 W FormManager: Network not available. Please check & try again.
08-25 16:37:20.901  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:20.907  6840  7312 V FormManager: Network unavailable.
,08-25 16:37:20.911  6840  7312 V FormManager: Network unavailable.
08-25 16:37:21.428  1034  1400 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1037941101] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 16:37:21.430  1034  1400 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1037941098] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 16:37:21.601  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:21.614  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 16:37:21.622  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:21.626  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:21.629  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:21.632  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 16:37:21.634  6325  6754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 16:37:21.644  5738  5738 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 16:37:21.663  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:21.680  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 16:37:21.680  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:21.680  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 16:37:21.680  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 16:37:21.688  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
08-25 16:37:21.691  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bfcf7c0
08-25 16:37:21.691  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 16:37:21.691  6934  6934 D AppUp4:CustFacade: isPhone : true
08-25 16:37:21.692  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
08-25 16:37:21.692  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 16:37:21.698  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:21.699  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 16:37:21.700  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 16:37:21.705  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:21.714  6963  6963 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 16:37:21.736  4314  7321 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 16:37:21.743  6963  7320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:21.753  4314  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:21.768  4314  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 16:37:21.770  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:21.771  6840  7324 V FormManager: Network unavailable.
08-25 16:37:21.779  6840  7323 W FormManager: Network not available. Please check & try again.
08-25 16:37:21.784  6840  7324 V FormManager: Network unavailable.
,08-25 16:37:21.787  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-25 16:37:21.787  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:21.788  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 16:37:21.788  3435  3435 D PhoneState: setPdpRejectCasuse : false
08-25 16:37:21.791  7004  7004 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 16:37:21.791  7004  7004 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 16:37:21.805  7066  7066 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:21
08-25 16:37:21.807  7066  7066 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 16:37:21.807  7066  7066 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 16:37:21.808  7066  7066 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 16:37:21.808  7066  7066 D WeatherAncestor: connectivity changed - connection : true
08-25 16:37:21.808  7066  7066 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3327343e
08-25 16:37:21.809  7066  7066 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 16:37:21.809  7066  7066 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 16:37:21.809  7066  7066 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 16:37:21.809  7066  7066 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 16:37:21.809  7066  7066 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:21
08-25 16:37:22.626  1034  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:22.627  1034  1942 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 16:37:22.640  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 16:37:22.640  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 16:37:22.641  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:22.641  1034  1096 D BluetoothManagerService: Message: 1
08-25 16:37:22.641  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-25 16:37:22.676  1034  1096 D BluetoothManagerService: Message: 20
08-25 16:37:22.676  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@363f41d1:true
,08-25 16:37:22.679  6887  6887 D BluetoothAdapterState: make
08-25 16:37:22.684  6887  6887 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 16:37:22.684  6887  6887 I bluedroid-qcom: init
08-25 16:37:22.686  6887  7351 I BluetoothAdapterState: Entering OffState
08-25 16:37:22.686  6887  6887 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 16:37:22.686  6887  6887 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 16:37:22.686  6887  6887 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 16:37:22.686  6887  6887 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 16:37:22.686  6887  6887 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 16:37:22.688  6887  6887 I bluedroid-qcom: get_profile_interface socket
08-25 16:37:22.688  6887  6887 I bluedroid-qcom: get_profile_interface map_client
,08-25 16:37:22.692  6887  7355 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 16:37:22.684  7354  7354 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:22.684  7354  7354 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:22.705  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-25 16:37:22.708  1034  1096 D BluetoothManagerService: Message: 40
08-25 16:37:22.708  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 16:37:22.709  6887  6903 I bluedroid-qcom: config_hci_snoop_log
08-25 16:37:22.710  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 16:37:22.710  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 16:37:22.714  7354  7354 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 16:37:22.714  7354  7354 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 16:37:22.715  7354  7354 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 16:37:22.717  7354  7354 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-25 16:37:22.723  6887  7351 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 16:37:22.723  6887  7351 D BluetoothAdapterProperties: Setting state to 11
08-25 16:37:22.723  6887  7351 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 16:37:22.725  6887  7351 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 16:37:22.726  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:22.726  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 16:37:22.726  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 16:37:22.727  7354  7354 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 16:37:22.727  7354  7354 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 16:37:22.734  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:22.737  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 16:37:22.739  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:22.742  6737  6737 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 16:37:22.746  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:22.748  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:22.750  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:22.767  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:22.776  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:22.780  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:22.785  6887  6887 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-25 16:37:22.788  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 16:37:22.789  6887  7355 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 16:37:22.790  6887  6887 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:22.790  6887  6887 V BluetoothPbapReceiver: ***********state = 11
08-25 16:37:22.794  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 16:37:22.797  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:22.798  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:22.798  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 16:37:22.800  6325  6754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 16:37:22.801  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 16:37:22.801  6887  7355 D BluetoothAdapterProperties: Name is: G3
08-25 16:37:22.801  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 16:37:22.805  6887  7351 D BluetoothBondStateMachine: make
08-25 16:37:22.806  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 16:37:22.806  5738  5738 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 16:37:22.809  6887  7351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:22.809  6887  7351 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 16:37:22.809  6887  7351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:22.809  6887  7351 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 16:37:22.809  6887  7351 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 16:37:22.810  6887  7373 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 16:37:22.813  6887  7351 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:22.815  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:22.815  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:22.816  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:22.856  1034  1941 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7376 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 16:37:22.860  5738  5738 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 16:37:22.872  6887  6887 D HeadsetService: Received start request. Starting profile...
08-25 16:37:22.872  6887  6887 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 16:37:22.873  6887  6887 D LGBluetoothHfpAdapter: Version 1.6
08-25 16:37:22.874   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 374us total 18.088ms
08-25 16:37:22.875  6887  7351 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:22.877  6887  6887 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 16:37:22.878  6887  6887 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 16:37:22.879  6887  6887 D HeadsetStateMachine: make
08-25 16:37:22.879  6887  7351 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:22.888   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.460ms
,08-25 16:37:22.894  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:22.894  6887  7351 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:22.901   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 12.210ms
,08-25 16:37:22.907  6887  7351 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:22.908  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 16:37:22.908  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:22.911  6887  7351 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:22.908  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 16:37:22.912  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 16:37:22.912  6887  6887 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:22.912  6887  6887 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:22.914  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
08-25 16:37:22.916  6887  6887 D HeadsetStateMachine: max_hf_connections = 1
08-25 16:37:22.916  6887  6887 I bluedroid-qcom: get_profile_interface handsfree
,08-25 16:37:22.917  6887  6887 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 16:37:22.918  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bfcf7c0
08-25 16:37:22.918  6887  7351 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:22.918  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 16:37:22.918  6934  6934 D AppUp4:CustFacade: isPhone : true
08-25 16:37:22.918   316  1397 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 1002
08-25 16:37:22.918   316  2150 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 16:37:22.918   316  2150 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 16:37:22.918   316  2150 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 16:37:22.918  6887  6887 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 16:37:22.919   316   316 V AudioFlinger: registerClient() client 0xb1433058, pid 6887
08-25 16:37:22.919  6887  6887 V ToneGenerator: Create Track: 0xb4928080
08-25 16:37:22.919  6887  6887 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 16:37:22.919  6887  6887 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 16:37:22.919   316  2147 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 16:37:22.919   316  2147 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 16:37:22.919   316  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 16:37:22.919   316  2147 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 16:37:22.919  6887  6887 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 16:37:22.919   316  2150 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 16:37:22.920   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 16:37:22.920   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 16:37:22.920   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 16:37:22.920   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 16:37:22.920   316  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:22.920   316  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:22.920  1603  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:22.920  1603  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:22.920  1853  4410 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:22.920  1853  4410 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:22.920  3435  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:22.920  3435  3450 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:22.920  1034  1996 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:22.920  1034  1996 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:22.921  6887  6902 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:22.921  6887  6902 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 16:37:22.921   316  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:22.921   316  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:22.921  1034  2014 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:22.921  1034  2014 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:22.921  1603  2165 V AudioSystem: ioCon,figChanged() event 0, ioHandle 2
08-25 16:37:22.921  1603  2165 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:22.921  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:22.921  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:22.921  3435  3451 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:22.921  3435  3451 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:22.921  6887  7356 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:22.921  6887  7356 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 16:37:22.921  6887  6887 V AudioSystem: getLatency() output 2, latency 50
08-25 16:37:22.921  6887  6887 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 16:37:22.921  6887  6887 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 16:37:22.921  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
08-25 16:37:22.922  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 16:37:22.922   316  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 16:37:22.922   316  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 16:37:22.922   316  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 16:37:22.922   316  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 16:37:22.922   316  1397 V AudioFlinger: createTrack() lSessionId: 20
08-25 16:37:22.922  6887  6887 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 16:37:22.923   316  1397 V AudioFlinger: acquiring 20 from 6887, for 6887
08-25 16:37:22.923   316  1397 V AudioFlinger:  added new entry for 20
08-25 16:37:22.926  6887  6887 V ToneGenerator: ToneGenerator INIT OK, time: 210703
08-25 16:37:22.926  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:22.927  6887  7393 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 16:37:22.927  6887  7393 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 16:37:22.927  6887  7393 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 16:37:22.928  6887  7393 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 16:37:22.928   316  2150 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6887
08-25 16:37:22.928   316  2150 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 16:37:22.928   316  2150 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 16:37:22.928   316  2150 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 16:37:22.928   316  2150 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 16:37:22.928   316  2150 V voice   : voice_set_parameters: exit with code(0)
08-25 16:37:22.928   316  2150 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 16:37:22.928   316  2150 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 16:37:22.928   316  2150 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 16:37:22.929   316  2150 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 16:37:22.929   316  2150 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 16:37:22.929   316  2150 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 16:37:22.930  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:22.931  6887  7393 V ToneGenerator: ToneGenerator destructor
08-25 16:37:22.931  6887  7393 V ToneGenerator: stopTone
08-25 16:37:22.931  6887  7393 V ToneGenerator: Delete Track: 0xb4928080
08-25 16:37:22.932  6887  7393 V AudioTrack: ~AudioTrack, releasing session id from 6887 on behalf of 6887
08-25 16:37:22.932   316  2147 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 16:37:22.932   316  2147 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 16:37:22.932   316   316 V AudioFlinger: releasing 20 from 6887 for 6887
08-25 16:37:22.932   316  2147 V AudioFlinger: PlaybackThread::Track destructor
08-25 16:37:22.932   316  1259 V AudioPolicyService: AudioCommandThread() waking up
08-25 16:37:22.932   316  2147 V AudioFlinger: removeClient_l() pid 6887, calling pid 316
08-25 16:37:22.932   316  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 16:37:22.932   316  1259 V AudioPolicyManager: releaseOutput() 2
08-25 16:37:22.932   316  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 16:37:22.932   316   316 V AudioFlinger:  decremented refcount to 0
08-25 16:37:22.932   316   316 V AudioFlinger: purging stale effects
08-25 16:37:22.932  6887  6887 D A2dpService: Received start request. Starting profile...
08-25 16:37:22.933  6887  6887 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 16:37:22.933  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:22.933  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 16:37:22.934  6887  6887 V Avrcp   : make
08-25 16:37:22.934  6887  6887 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 16:37:22.934  6887  6887 I bluedroid-qcom: get_profile_interface avrcp
08-25 16:37:22.934  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:22.936  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:22.940  6887  7351 V LGMDMManager: Create singleton instance
08-25 16:37:22.941  4314  7396 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 16:37:22.942  6887  6887 V AudioManager: registerRemoteController: size of Media player list: 0
08-25 16:37:22.945  6887  6887 E AudioManager: No RCC entry present to update
08-25 16:37:22.945  6887  6887 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 16:37:22.947  6963  6963 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 16:37:22.947  6887  6887 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 16:37:22.948  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 16:37:22.948  6887  6887 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 16:37:22.951  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 16:37:22.951  6887  7351 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 16:37:22.955  4314  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:22.955  4314  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 16:37:22.995  7376  7376 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 16:37:22.996  7376  7376 W LG Account v2.2: No ProfileInfo entries
08-25 16:37:22.996  7376  7376 I LG Account v2.2: isEnabled: false
08-25 16:37:22.996  7376  7376 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 16:37:22.996  7376  7376 I Feature : [Lifetracker]Country: EU
08-25 16:37:22.996  7376  7376 I Feature : [Lifetracker]Operator: OPEN
08-25 16:37:22.996  7376  7376 I Feature : [Lifetracker]Ranking support: false
08-25 16:37:22.996  7376  7376 I Feature : [Lifetracker]Comfort support: false
08-25 16:37:22.996  7376  7376 I Feature : [Lifetracker]Accessory: true
08-25 16:37:22.996  7376  7376 I Feature : [Lifetracker]Health device: true
08-25 16:37:22.997  7376  7376 I Feature : [Lifetracker]Extra Pedometer: false
08-25 16:37:22.997  7376  7376 I Feature : [Lifetracker]Blood glucose device: false
08-25 16:37:22.997  7376  7376 I Feature : [Lifetracker]Device Number: 3
,08-25 16:37:23.006  6963  7401 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:23.008  6840  7403 W FormManager: Network not available. Please check & try again.
08-25 16:37:23.015  6840  7404 V FormManager: Network unavailable.
,08-25 16:37:23.021  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 16:37:23.021  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:23.021  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 16:37:23.023  6737  6737 D BluetoothPermissionRequest: onReceive
08-25 16:37:23.025  6840  7404 V FormManager: Network unavailable.
08-25 16:37:23.027  7004  7004 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 16:37:23.028  7004  7004 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 16:37:23.036  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 16:37:23.041  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-25 16:37:23.041  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-25 16:37:23.055  7066  7066 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:23
,08-25 16:37:23.056  7066  7066 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 16:37:23.057  7066  7066 D Weather.Utils: 2 : All the weather widget is gone.
08-25 16:37:23.057  7066  7066 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 16:37:23.057  7066  7066 D WeatherAncestor: connectivity changed - connection : true
08-25 16:37:23.057  7066  7066 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3327343e
08-25 16:37:23.058  7066  7066 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 16:37:23.058  7066  7066 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 16:37:23.058  7066  7066 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 16:37:23.058  7066  7066 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 16:37:23.058  7066  7066 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:23
08-25 16:37:23.075  6325  6325 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 16:37:23.076  6325  6754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 16:37:23.090  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:37:23.100  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 16:37:23.100  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE,
08-25 16:37:23.100  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 16:37:23.100  6934  6934 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 16:37:23.102  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 16:37:23.111  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bfcf7c0
08-25 16:37:23.111  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 16:37:23.111  6934  6934 D AppUp4:CustFacade: isPhone : true
08-25 16:37:23.112  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
08-25 16:37:23.113  6934  6934 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 16:37:23.116  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:23.116  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 16:37:23.118  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:23.121  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:23.129  6963  6963 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 16:37:23.130  1034  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 16:37:23.131  4314  7406 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 16:37:23.135  4314  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:23.143  4314  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 16:37:23.146  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-25 16:37:23.150  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 16:37:23.151  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 16:37:23.152  6887  6887 I BluetoothA2dpServiceJni: classInitNative
08-25 16:37:23.152  6887  6887 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 16:37:23.152  6887  6887 D A2dpStateMachine: make
08-25 16:37:23.153  6887  6887 I bluedroid-qcom: get_profile_interface a2dp
08-25 16:37:23.153  6887  7412 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 16:37:23.155  6887  6887 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-25 16:37:23.156  6887  6887 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 16:37:23.157  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:23.158  6887  6887 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 16:37:23.159  6887  7411 D A2dpStateMachine: Enter Disconnected: -2
08-25 16:37:23.160  6887  6887 D HidService: Received start request. Starting profile...
08-25 16:37:23.160  6887  6887 I bluedroid-qcom: get_profile_interface hidhost
08-25 16:37:23.160  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:23.161  6887  6887 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 16:37:23.162  6887  6887 D HealthService: Received start request. Starting profile...
08-25 16:37:23.162  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 16:37:23.164  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:23.164  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 16:37:23.165  6887  6887 I bluedroid-qcom: get_profile_interface health
08-25 16:37:23.165  6887  6887 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 16:37:23.165  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:23.166  6887  6887 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 16:37:23.167  6887  6887 D PanService: Received start request. Starting profile...
08-25 16:37:23.168  6887  6887 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 16:37:23.168  6887  6887 I bluedroid-qcom: get_profile_interface pan
08-25 16:37:23.168  7004  7004 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 16:37:23.168  7004  7004 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 16:37:23.174  6887  6887 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 16:37:23.174  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:23.174  6963  7415 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:23.174  6840  7409 W FormManager: Network not available. Please check & try again.
08-25 16:37:23.175  6887  6887 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 16:37:23.180  7066  7066 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:23
08-25 16:37:23.182  6887  6887 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 16:37:23.182  6887  6887 D BtGatt.GattService: Received start request. Starting profile...
08-25 16:37:23.182  6887  6887 D BtGatt.GattService: start()
08-25 16:37:23.182  6887  6887 I bluedroid-qcom: get_profile_interface gatt
08-25 16:37:23.182  6840  7410 V FormManager: Network unavailable.
08-25 16:37:23.182  6887  6887 D BtGatt.AdvertiseManager: advertise manager created
08-25 16:37:23.182  7066  7066 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 16:37:23.182  7066  7066 D Weather.Utils: 2 : All the weather widget is gone.
08-25 16:37:23.183  7066  7066 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 16:37:23.183  7066  7066 D WeatherAncestor: connectivity changed - connection : true
08-25 16:37:23.183  7066  7066 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3327343e
08-25 16:37:23.184  7066  7066 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 16:37:23.184  7066  7066 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 16:37:23.184  7066  7066 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 16:37:23.184  7066  7066 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 16:37:23.184  7066  7066 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:37:23
,08-25 16:37:23.192  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:23.192  6887  6887 D HeadsetStateMachine: Proxy object connected
08-25 16:37:23.193  6887  6887 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 16:37:23.194  6887  6887 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 16:37:23.195  6840  7410 V FormManager: Network unavailable.
08-25 16:37:23.196  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:23.196  6887  6887 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 16:37:23.197  6887  6887 V BluetoothMapService: BluetoothMapBinder()
08-25 16:37:23.198  6887  6887 D BluetoothMapService: Received start request. Starting profile...
08-25 16:37:23.198  6887  6887 D BluetoothMapService: start()
,08-25 16:37:23.201  6887  6887 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 16:37:23.201  6887  6887 D BluetoothMapEmailAppObserver: createReceiver()
,08-25 16:37:23.203  6887  6887 D BluetoothMapEmailAppObserver: initObservers()
08-25 16:37:23.203  6887  6887 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 16:37:23.212  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
,08-25 16:37:23.217  6887  6887 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 16:37:23.217  6887  7393 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 16:37:23.218  6887  7393 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 16:37:23.218  6887  7393 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 16:37:23.221  6887  6887 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:23.224  6887  6887 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:23.227  6887  6887 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 16:37:23.231  6887  6887 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:23.232  6887  6887 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 16:37:23.235  6887  6887 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 16:37:23.235  6887  6887 V BluetoothMapService: Handler(): got msg=1
08-25 16:37:23.236  6887  7351 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 16:37:23.236  6887  7351 I bluedroid-qcom: enable
08-25 16:37:23.237  6887  7351 I bt_hci_bdroid: init
08-25 16:37:23.238  6887  7351 I bt_vendor: bt-vendor : init
08-25 16:37:23.238  6887  7351 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 16:37:23.238  6887  7351 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 16:37:23.238  6887  7351 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 16:37:23.238  6887  7351 D bt_userial_mct: userial_init
08-25 16:37:23.238  6887  7421 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 16:37:23.238  6887  7421 I bt-btu  : btu_task pending for preload complete event
08-25 16:37:23.238  6887  6887 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:23.239  6887  7351 D bt_hci_bdroid: set_power 1
08-25 16:37:23.239  6887  7351 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 16:37:23.239  6887  7351 I bt_vendor: Starting hciattach daemon
08-25 16:37:23.239  6887  7351 I bt_vendor: try to set true
08-25 16:37:23.224  7424  7424 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:23.242  6887  6887 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:23.242  6887  6887 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:23.242  6887  6887 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 16:37:23.242  6887  6887 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:23.242  6887  6887 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-25 16:37:23.224  7424  7424 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:23.285  7425  7425 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 16:37:23.423  7431  7431 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 16:37:23.435  7432  7432 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 16:37:23.485  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 16:37:23.499  7438  7438 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 16:37:23.512  7439  7439 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 16:37:23.528  7440  7440 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 16:37:23.555  7445  7445 I libmdmdetect: ESOC framework not supported
08-25 16:37:23.556  7445  7445 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 16:37:23.564  7445  7445 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-25 16:37:23.564  7445  7445 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 16:37:23.564  7445  7445 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-25 16:37:23.564  7445  7445 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 16:37:23.564  7445  7445 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-25 16:37:23.564  7445  7445 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-25 16:37:23.564  7445  7445 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 16:37:23.604  7445  7446 E QC-QMI  : qmi_client [7445] 14: failed to locate client data
,08-25 16:37:23.605   447   447 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 16:37:23.605   447   447 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-25 16:37:23.659  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7363
08-25 16:37:23.659  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7364
08-25 16:37:23.660  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7374
08-25 16:37:23.660  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7375
08-25 16:37:23.662  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7441
,08-25 16:37:23.684  7447  7447 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 16:37:23.696  7448  7448 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 16:37:23.740  6887  7351 I bt_vendor: bluetooth satus is on
08-25 16:37:23.741  6887  7351 D bt_hci_bdroid: preload
08-25 16:37:23.741  6887  7423 D bt_userial_mct: userial_open(port:0)
08-25 16:37:23.741  6887  7423 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 16:37:23.745  6887  7423 I bt_vendor: Done intiailizing UART
08-25 16:37:23.749  6887  7423 I bt_vendor: Done intiailizing UART
08-25 16:37:23.749  6887  7423 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 16:37:23.750  6887  7423 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 16:37:23.750  6887  7451 D bt_userial_mct: Entering userial_read_thread()
08-25 16:37:23.751  6887  7421 I bt-btu  : btu_task received preload complete event
08-25 16:37:23.752  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 16:37:23.752  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 16:37:23.760  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 16:37:23.760  7100  7138 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 16:37:23.766  6887  7421 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 16:37:23.767  6887  7421 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 16:37:23.767  6887  7421 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 16:37:23.767  6887  7421 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 16:37:23.767  6887  7421 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 16:37:23.767  6887  7421 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 16:37:23.767  6887  7421 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 16:37:23.815  6887  7421 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 16:37:23.815  6887  7421 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
08-25 16:37:23.815  6887  7421 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-25 16:37:23.845  6887  7355 E bt-btif : Calling BTA_HhEnable
08-25 16:37:23.845  6887  7355 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 16:37:23.845  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 16:37:23.845  6887  7355 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 16:37:23.845  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 16:37:23.845  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 16:37:23.846  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 16:37:23.846  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-25 16:37:23.848  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-25 16:37:23.849  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 16:37:23.850  6887  7355 D BluetoothAdapterProperties: Name is: G3
08-25 16:37:23.852  6887  7355 D BluetoothAdapterProperties: Scan Mode:20
08-25 16:37:23.852  6887  7355 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 16:37:23.853  6887  7355 D bt_hci_bdroid: postload
08-25 16:37:23.853  6887  7423 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:23.854  6887  7423 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:23.855  6887  7423 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:23.855  6887  7421 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 16:37:23.856  6887  7423 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:23.856  6887  7423 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:23.857  6887  7355 D bte_conf: Device ID record 1 : primary
08-25 16:37:23.857  6887  7355 D bte_conf:   vendorId            = 00c4
08-25 16:37:23.857  6887  7355 D bte_conf:   vendorIdSource      = 0001
08-25 16:37:23.857  6887  7355 D bte_conf:   product             = 13a1
08-25 16:37:23.857  6887  7355 D bte_conf:   version             = 1000
08-25 16:37:23.857  6887  7355 D bte_conf:   clientExecutableURL = 
08-25 16:37:23.857  6887  7355 D bte_conf:   serviceDescription  = 
08-25 16:37:23.857  6887  7355 D bte_conf:   documentationURL    = 
08-25 16:37:23.857  6887  7355 D bte_conf: bte_load_did_conf no section named DID2.
08-25 16:37:23.860  6887  7423 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:23.860  6887  7423 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 16:37:23.865  6887  7451 E bt_mct  : hci lib postload completed
,08-25 16:37:23.866  6887  7351 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 16:37:23.867  6887  7351 D BluetoothAdapterProperties: ScanMode =  20
08-25 16:37:23.867  6887  7351 D BluetoothAdapterProperties: State =  11
08-25 16:37:23.867  6887  7351 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 16:37:23.867  6887  7351 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 16:37:23.867  6887  7351 D BluetoothAdapterProperties: Setting state to 12
08-25 16:37:23.867  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:23.867  6887  7351 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 16:37:23.868  6887  7355 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 16:37:23.868  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:23.868  6887  7355 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 16:37:23.868  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 16:37:23.868  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 16:37:23.868  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:37:23.854  7454  7454 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:23.854  7454  7454 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:23.875  6887  7421 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:23.875  6887  7421 W bt-smp  : Plain text(LSB ~ MSB) = 2b 46 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:23.875  6887  7421 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 60 88 b3 7c 2c 1b 4b ae bc bf ae 04 03 73 1d 
08-25 16:37:23.875  6887  7421 W bt-btm  : Stopping oneshot timer
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:23.877  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:37:23.886  1853  2482 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:37:23.888  6887  7351 I BluetoothAdapterState: Entering On State
08-25 16:37:23.890  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:23.890  6887  7355 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 16:37:23.890  6887  7355 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 16:37:23.897  6887  7351 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 16:37:23.897  6887  7351 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 16:37:23.897  6887  7351 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 16:37:23.898  1034  1034 D BluetoothHeadset: Proxy object connected
,08-25 16:37:23.901  6887  7351 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 16:37:23.903  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 16:37:23.904  6737  6755 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 16:37:23.908  6737  6753 D BluetoothPan: onBluetoothStateChange on: true
08-25 16:37:23.908  6737  6753 D BluetoothPan: onBluetoothStateChange call bindService
08-25 16:37:23.909  6887  7421 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:23.909  6887  7421 W bt-smp  : Plain text(LSB ~ MSB) = e1 5f 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:23.909  6887  7421 W bt-smp  : Encrypted text(LSB ~ MSB) = 89 1e af 80 a1 3f 01 ba c6 73 95 ef d7 f6 6d fb 
08-25 16:37:23.909  6887  7421 W bt-btm  : Stopping oneshot timer
08-25 16:37:23.914  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:37:23.918  6737  6737 D BluetoothInputDevice: Proxy object connected
08-25 16:37:23.918  6737  6737 D HidProfile: Bluetooth service connected
08-25 16:37:23.922  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 16:37:23.923  6737  6753 D BluetoothMap: onBluetoothStateChange: up=true
08-25 16:37:23.926  6887  7421 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:23.926  6887  7421 W bt-smp  : Plain text(LSB ~ MSB) = e6 02 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:23.926  6887  7421 W bt-smp  : Encrypted text(LSB ~ MSB) = 61 12 5c 2b 44 f2 04 0a 71 3d 82 38 74 8c af eb 
08-25 16:37:23.926  6887  7421 W bt-btm  : Stopping oneshot timer
08-25 16:37:23.931  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 16:37:23.934  1034  1034 D BluetoothA2dp: Proxy object connected
08-25 16:37:23.934  6737  6737 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 16:37:23.934  6737  6737 D PanProfile: Bluetooth service connected
08-25 16:37:23.934  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:37:23.937  6737  6737 D BluetoothMap: Proxy object connected
08-25 16:37:23.937  6737  6737 D MapProfile: Bluetooth service connected
08-25 16:37:23.937  6737  6737 D BluetoothMap: getConnectedDevices()
08-25 16:37:23.939  6887  7351 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 16:37:23.939  6887  6903 V BluetoothMapService: getConnectedDevices()
08-25 16:37:23.940  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 16:37:23.940  6737  6753 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 16:37:23.941  6887  7421 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:23.941  6887  7421 W bt-smp  : Plain text(LSB ~ MSB) = c3 c5 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:23.941  6887  7421 W bt-smp  : Encrypted text(LSB ~ MSB) = 7a 24 66 17 ec 40 fa c6 15 80 12 a1 1d 21 10 78 
08-25 16:37:23.941  6887  7421 W bt-btm  : Stopping oneshot timer
08-25 16:37:23.943  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 16:37:23.943  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 16:37:23.945  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:23.948  1943  2076 D LGBluetoothAPIService: Message: 1
08-25 16:37:23.948  1943  2076 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 16:37:23.948  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 16:37:23.949  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 16:37:23.951  6887  7421 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:23.951  6887  7421 W bt-smp  : Plain text(LSB ~ MSB) = d3 f3 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:23.951  6887  7421 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 fe ad b1 4b 62 f3 4e 5d e7 c7 91 5b 75 e8 6c 
08-25 16:37:23.951  6887  7421 W bt-btm  : Stopping oneshot timer
08-25 16:37:23.957  7469  7469 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-25 16:37:23.959  6658  6658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 16:37:23.962  6887  6887 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:23.962  6887  6887 D BluetoothMapService: STATE_ON
08-25 16:37:23.964  1943  2076 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 16:37:23.967  6737  6737 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:23.968  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:23.970  1034  1096 D BluetoothManagerService: Message: 40
08-25 16:37:23.970  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 16:37:23.971  1034  1096 D BluetoothManagerService: Message: 30
,08-25 16:37:23.971  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:23.974  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:23.974  6737  6737 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 16:37:23.977  1034  1096 D BluetoothManagerService: Message: 30
08-25 16:37:23.982  6737  6737 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-25 16:37:23.983  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 16:37:23.984  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:23.984  6887  6887 V BluetoothPbapService: Pbap Service onCreate
08-25 16:37:23.985  6887  6887 V BluetoothPbapService: Starting PBAP service
,08-25 16:37:23.986  6887  6887 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 16:37:23.986  6887  6887 V BluetoothPbapService: Pbap Service onBind
08-25 16:37:23.987  6737  6737 D BluetoothA2dp: Proxy object connected
08-25 16:37:23.988  6737  6737 D A2dpProfile: Bluetooth service connected
08-25 16:37:23.990  6887  6887 V BluetoothMapService: Handler(): got msg=1
08-25 16:37:23.991  6887  6887 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 16:37:23.991  6737  6737 D BluetoothHeadset: Proxy object connected
08-25 16:37:23.991  6887  6887 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:23.992  6887  6887 V BluetoothPbapService: state: 12
08-25 16:37:23.992  6737  6737 D HeadsetProfile: Bluetooth service connected
08-25 16:37:23.993  6887  7473 D BluetoothMapMasInstance: MAS initSocket()
08-25 16:37:23.993  6887  6887 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 16:37:23.994  6887  6887 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 16:37:23.994  6887  7473 D BluetoothMapMasInstance:   masId = 00
08-25 16:37:23.994  6887  7473 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 16:37:23.994  6887  7473 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 16:37:23.994  6887  7473 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 16:37:23.994  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 16:37:23.994  6887  6887 V BluetoothPbapService: Handler(): got msg=1
08-25 16:37:23.995  1943  2076 D LGBluetoothAPIService: Message: 100
08-25 16:37:23.995  1943  2076 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 16:37:23.995  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:23.995  6887  6887 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 16:37:23.995  6887  6887 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 16:37:23.996  6887  6887 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:23.996  6887  6887 V BluetoothPbapReceiver: ***********state = 12
08-25 16:37:23.996  6887  7473 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:37:23.997  6887  7473 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 16:37:23.998  6887  7473 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 16:37:23.998  6887  7473 D BluetoothMapMasInstance: Accepting socket connection...
08-25 16:37:23.998  6887  7355 D BluetoothAdapterProperties: Scan Mode:21
08-25 16:37:23.998  6887  7355 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 16:37:23.999  6887  7476 V BluetoothPbapService: Pbap Service initSocket
08-25 16:37:24.000  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:24.002  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:24.004  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 16:37:24.004  2208  2208 D c       : Getting all permits...
08-25 16:37:24.004  2208  2208 D a       : Opening database...
08-25 16:37:24.004  1034  1647 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:24.005  6887  7476 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:24.007  6887  7476 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 16:37:24.007  6887  7476 V BluetoothPbapService: Succeed to create listening socket 
08-25 16:37:24.007  6887  7476 V BluetoothPbapService: Accepting socket connection...
08-25 16:37:24.008  2208  2208 D a       : Opening database auth.proximity.permit_store...
,08-25 16:37:24.009  6737  6737 D DockEventReceiver: finishStartingService: stopping service
,08-25 16:37:24.009  2208  2208 D a       : Closing database...
08-25 16:37:24.010  6737  6737 D BluetoothPbap: Proxy object connected
08-25 16:37:24.010  6737  6737 D PbapServerProfile: Bluetooth service connected
08-25 16:37:24.021  6737  6737 D BluetoothPermissionRequest: onReceive
,08-25 16:37:24.022  6737  6737 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 16:37:24.024  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 16:37:24.027  6887  6887 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 16:37:24.028  6887  6887 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 16:37:24.033  6887  6887 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 16:37:24.050  6887  6887 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 16:37:24.050  6887  6887 V BtOppService: onCreate
,08-25 16:37:24.056  6887  6887 V BluetoothOppNotification: send message
08-25 16:37:24.060  6887  6887 V BtOppService: Starting RfcommListener
08-25 16:37:24.070  6887  6887 D BluetoothOppPreference: Dumping Names:  
08-25 16:37:24.070  6887  7479 V BtOppService: Deleted complete outbound shares, number =  0
08-25 16:37:24.070  6887  6887 D BluetoothOppPreference: {}
08-25 16:37:24.070  6887  6887 D BluetoothOppPreference: Dumping Channels:  
,08-25 16:37:24.070  6887  6887 D BluetoothOppPreference: {}
,08-25 16:37:24.071  6887  6887 V BtOppService: onStartCommand
08-25 16:37:24.073  6887  7482 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 16:37:24.074  6887  7479 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 16:37:24.075  6887  7479 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 16:37:24.076  6887  7482 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 16:37:24.077  6887  7479 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@452f78b on behalf of 
08-25 16:37:24.078  6887  7482 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f41f068 on behalf of 
08-25 16:37:24.079  6887  6887 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:24.079  6887  6887 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 16:37:24.080  6887  7482 V BluetoothOppNotification: update too frequent, put in queue
08-25 16:37:24.083  6887  7482 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 16:37:24.083  6887  7482 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-25 16:37:24.085  6887  6887 V BluetoothOppNotification: new notify threadi!
08-25 16:37:24.085  6887  7482 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ec33c81 on behalf of 
08-25 16:37:24.086  6887  6887 V BluetoothOppNotification: send delay message
08-25 16:37:24.086  6887  7482 V BluetoothOppNotification: update too frequent, put in queue
08-25 16:37:24.087  6887  6887 V BtOppService: start RfcommListener
,08-25 16:37:24.088  6887  7483 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 16:37:24.090  6887  6887 V BtOppService: RfcommListener started
08-25 16:37:24.090  6887  6887 V BtOppService: ContentObserver received notification
08-25 16:37:24.090  6887  6887 V BtOppService: ContentObserver received notification
08-25 16:37:24.090  6887  7482 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 16:37:24.091  6887  7482 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 16:37:24.091  6887  7484 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 16:37:24.093  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:24.093  6887  7482 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2564126 on behalf of 
08-25 16:37:24.094  6887  7484 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:24.096  6887  7483 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ff78167 on behalf of 
08-25 16:37:24.096  6887  7484 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-25 16:37:24.097  6887  7484 V BtOppRfcommListener: Started RFCOMM listener....
08-25 16:37:24.097  6887  7484 I BtOppRfcommListener: Accept thread started.
08-25 16:37:24.097  6887  7484 V BtOppRfcommListener: Accepting connection...
08-25 16:37:24.098  6887  7483 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 16:37:24.099  6887  7482 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-25 16:37:24.105  6887  7483 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 16:37:24.106  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:24.106  6887  6887 V BluetoothFtpService: Ftp Service onCreate
08-25 16:37:24.106  6887  6887 I BluetoothFtpService: Ftp Service onCreate
08-25 16:37:24.106  6887  6887 V BluetoothFtpService: Ftp Service onStartCommand
08-25 16:37:24.106  6887  6887 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:24.106  6887  6887 V BluetoothFtpService: Starting Listening on sockets
08-25 16:37:24.107  6887  6887 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:24.107  6887  6887 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:24.107  6887  6887 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 16:37:24.107  6887  6887 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:24.107  6887  6887 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 16:37:24.107  6887  6887 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 16:37:24.109  6887  7483 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35661fbd on behalf of 
08-25 16:37:24.110  6887  6887 V BluetoothFtpService: Handler(): got msg=1
08-25 16:37:24.111  6887  7483 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 16:37:24.111  6887  6887 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 16:37:24.111  6887  6887 V BluetoothFtpService: Ftp Service initSocket
08-25 16:37:24.113  1034  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:24.114  6887  6887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:24.114  6887  7483 V BluetoothOppNotification: outbound notification was removed.
08-25 16:37:24.115  6887  6887 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-25 16:37:24.118  6887  7483 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 16:37:24.120  6887  7483 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@235549b2 on behalf of 
08-25 16:37:24.121  6887  7485 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 16:37:24.121  6887  7483 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 16:37:24.122  6887  7483 V BluetoothOppNotification: inbound notification was removed.
08-25 16:37:24.122  6887  7483 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 16:37:24.123  6887  7483 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3970cd03 on behalf of 
08-25 16:37:24.143  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:24.143  6887  6887 V BluetoothSapService: Sap Service onCreate
08-25 16:37:24.145  6887  6887 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:24.145  6887  6887 V BluetoothSapService: state: 12
,08-25 16:37:24.145  6887  6887 V BluetoothSapService: Starting SAP server process
08-25 16:37:24.147  6887  6887 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-25 16:37:24.134  7487  7487 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:24.134  7487  7487 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:24.150  6887  7486 V BluetoothSapService: Sap Service initRfcommSocket
08-25 16:37:24.151  1034  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:24.152  6887  7486 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:24.153  6887  7486 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 16:37:24.153  6887  7486 V BluetoothSapService: Succeed to create listening socket 
08-25 16:37:24.153  6887  7486 V BluetoothSapService: Accepting socket connection...
08-25 16:37:24.161  7487  7487 V BT_SAP  : Event pipe created
08-25 16:37:24.161  7487  7487 V BT_SAP  : create_server_socket qcom.sap.server
08-25 16:37:24.161  7487  7487 V BT_SAP  : created socket fd 6
,08-25 16:37:24.697  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 16:37:24.698  1034  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 16:37:24.739  1034  1050 I ActivityManager: Killing 7279:com.lge.bnr/1000 (adj 15): empty #17
,08-25 16:37:24.746  1034  1400 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-25 16:37:24.746  1034  1400 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-25 16:37:24.775  1034  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_7279/cgroup.procs: No such file or directory
,08-25 16:37:24.962  1034  1888 I ActivityManager: Killing 6563:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-25 16:37:24.987  6801  6801 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-25 16:37:24.988  6801  6801 W System.err: android.os.DeadObjectException
08-25 16:37:24.988  6801  6801 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 16:37:24.988  6801  6801 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 16:37:24.988  6801  6801 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 16:37:24.988  6801  6801 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 16:37:24.988  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 16:37:24.988  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 16:37:24.988  6801  6801 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 16:37:24.989  6801  6801 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 16:37:24.989  6801  6801 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 16:37:24.989  6801  6801 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 16:37:24.989  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:37:24.989  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 16:37:24.989  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 16:37:24.989  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 16:37:24.989  6801  6801 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 16:37:24.989  6801  6801 W System.err: android.os.DeadObjectException
08-25 16:37:24.990  6801  6801 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 16:37:24.990  6801  6801 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 16:37:24.990  6801  6801 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 16:37:24.990  6801  6801 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 16:37:24.990  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 16:37:24.990  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 16:37:24.990  6801  6801 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 16:37:24.990  6801  6801 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 16:37:24.990  6801  6801 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 16:37:24.990  6801  6801 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 16:37:24.990  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:37:24.990  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 16:37:24.990  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 16:37:24.990  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 16:37:24.990  6801  6801 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 16:37:24.991  6801  6801 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-25 16:37:25.028  1034  1648 W libprocessgroup: failed to open /acct/uid_1000/pid_6563/cgroup.procs: No such file or directory
,08-25 16:37:25.035  1034  1648 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-25 16:37:25.045  6801  6801 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 16:37:25.045  6801  6801 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-25 16:37:25.087  6887  6887 V BluetoothOppNotification: new notify threadi!
08-25 16:37:25.088  6887  6887 V BluetoothOppNotification: send delay message
,08-25 16:37:25.091  6887  7498 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 16:37:25.106  1034  1050 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7497 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 16:37:25.108  6801  6801 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 16:37:25.146  6887  7498 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34a9365f on behalf of 
08-25 16:37:25.147  6887  7498 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 16:37:25.165  6887  7498 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-25 16:37:25.178  6887  7498 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@271748ac on behalf of 
08-25 16:37:25.179  6887  7498 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-25 16:37:25.193  6887  7498 V BluetoothOppNotification: outbound notification was removed.
08-25 16:37:25.193  6887  7498 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-25 16:37:25.199  7497  7497 D UEI.SmartControl: Quickset Services start...
08-25 16:37:25.201  7497  7497 I UEI.SmartControl: Manufacture = LGE
08-25 16:37:25.201  7497  7497 D UEI.SmartControl: Id = LGNevo
08-25 16:37:25.203  7497  7497 D UEI.SmartControl: File observer start...
08-25 16:37:25.204  6887  7498 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e168975 on behalf of 
08-25 16:37:25.207  7497  7497 E UEI.SmartControl: IR Port is disabled: false
08-25 16:37:25.208  7497  7497 D UEI.SmartControl: Starting file observer...
08-25 16:37:25.208  7497  7497 D UEI.SmartControl: Extracting JNI libs...
08-25 16:37:25.209  7497  7497 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-25 16:37:25.219  6887  7498 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 16:37:25.220  6887  7498 V BluetoothOppNotification: inbound notification was removed.
08-25 16:37:25.220  6887  7498 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 16:37:25.303  7497  7497 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-25 16:37:25.303  7497  7497 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 16:37:25.303  7497  7497 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-25 16:37:25.321  1034  1888 I art     : Explicit concurrent mark sweep GC freed 93585(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.044ms total 96.719ms
08-25 16:37:25.322  6887  7498 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32f85d0a on behalf of 
,08-25 16:37:25.333  7497  7497 I UEI.SmartControl: --- Selecting new region: 6
08-25 16:37:25.335  7497  7497 I UEI.SmartControl: Model = LG-D855
,08-25 16:37:25.336  7497  7497 D UEI.SmartControl: QS Service created
08-25 16:37:25.346  7497  7497 I UEI.SmartControl: Service initServices...
,08-25 16:37:25.349  7497  7497 D UEI.SmartControl: QS start get config
,08-25 16:37:25.385  7497  7497 D UEI.SmartControl: Loading JNI Libs...
,08-25 16:37:25.624  7497  7497 I UEI.SmartControl: Supports setup maps: true
08-25 16:37:25.627  7497  7497 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 16:37:25.627  7497  7497 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 16:37:25.628  7497  7497 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 16:37:25.628  7497  7497 I UEI.SmartControl: ### init IR Blaster...
,08-25 16:37:25.634  7497  7497 D serial_port: Configuring serial port
08-25 16:37:25.637  7497  7497 E UEI.SmartControl: UEIBLaster setting for 616
08-25 16:37:25.637  7497  7497 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 16:37:25.637  7497  7497 I UEI.SmartControl: configuring settings for MAXQ616
08-25 16:37:25.637  7497  7497 I UEI.SmartControl: Get version...
08-25 16:37:25.648  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:25.648  1034  1576 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@34965230 mBinding = false
,08-25 16:37:25.654  7497  7539 D UEI.SmartControl: serial port data available: 21
,08-25 16:37:25.674  1034  1096 D BluetoothManagerService: Message: 2
08-25 16:37:25.674  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 16:37:25.674  1034  1096 D BluetoothManagerService: Sending off request.
08-25 16:37:25.675  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 16:37:25.675  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:25.675  6887  6903 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 16:37:25.675  6887  7351 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 16:37:25.675  6887  7351 D BluetoothAdapterProperties: Setting state to 13
08-25 16:37:25.675  6887  7351 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 16:37:25.676  6887  7351 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 16:37:25.676  6887  7351 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 16:37:25.677  6887  7355 D BluetoothAdapterProperties: Scan Mode:20
08-25 16:37:25.677  6887  7351 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 16:37:25.678  6887  7484 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 16:37:25.678  6887  7473 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 16:37:25.679  6887  7485 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:25.679  6887  7476 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:25.679  6887  7351 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 16:37:25.679  6887  7486 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:37:25.680  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 16:37:25.680  6887  7421 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 16:37:25.682  7497  7497 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 16:37:25.682  7497  7497 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 16:37:25.683  7497  7497 I UEI.SmartControl: QS saving settings...
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP -, PSM: 0x0019 not found for deregistration
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 16:37:25.685  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 16:37:25.685  6887  7421 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-25 16:37:25.691  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:25.691  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:25.692  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:25.692  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:25.693  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:25.693  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:25.694  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:37:25.694  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:25.723  7497  7497 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 16:37:25.726  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:25.726  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 16:37:25.726  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 16:37:25.727  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.730  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 16:37:25.732  6887  6887 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.732  6887  6887 D BluetoothMapService: STATE_TURNING_OFF
08-25 16:37:25.732  6887  6887 V BtOppService: Receiver DISABLED_ACTION 
08-25 16:37:25.732  6887  6887 V BluetoothMapService: Handler(): got msg=4
08-25 16:37:25.733  6887  6887 D BluetoothMapService: MAP Service closeService in
08-25 16:37:25.733  6887  6887 D BluetoothMapMasInstance: MAP Service shutdown
08-25 16:37:25.733  6887  6887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 16:37:25.733  6887  6887 V BluetoothMapService: MAP Service closeService out
08-25 16:37:25.734  6887  6887 I BtOppRfcommListener: stopping Accept Thread
08-25 16:37:25.734  6887  6887 V BtOppRfcommListener: close mBtServerSocket
08-25 16:37:25.734  6887  7484 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 16:37:25.735  6887  6887 V BtOppRfcommListener: waiting for thread to terminate
08-25 16:37:25.735  6887  6887 V BtOppRfcommListener: done waiting for thread to terminate
,08-25 16:37:25.736  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:25.738  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:25.739  6887  6887 V BtOppService: onDestroy
08-25 16:37:25.740  6737  6737 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-25 16:37:25.740  6887  6887 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 16:37:25.741  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 16:37:25.742  7497  7539 D UEI.SmartControl: serial port data available: 4
08-25 16:37:25.744  6887  6887 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 16:37:25.744  6887  6887 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.744  6887  6887 V BluetoothPbapReceiver: ***********state = 13
08-25 16:37:25.745  6887  6887 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 16:37:25.748  6887  6887 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.748  6887  6887 V BluetoothPbapService: state: 13
08-25 16:37:25.748  6887  6887 V BluetoothPbapService: Pbap Service closeService in
08-25 16:37:25.748  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:37:25.752  6887  6887 V BluetoothPbapService: successfully stopped pbap service
08-25 16:37:25.752  6887  6887 V BluetoothPbapService: Pbap Service closeService out
08-25 16:37:25.752  6887  6887 V BluetoothPbapService: Pbap Service onDestroy
08-25 16:37:25.752  6887  6887 V BluetoothPbapService: Pbap Service closeService in
08-25 16:37:25.752  6887  6887 V BluetoothPbapService: Pbap Service closeService out
08-25 16:37:25.752  6887  6887 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 16:37:25.753  6737  6737 D DockEventReceiver: finishStartingService: stopping service
08-25 16:37:25.754  6737  6737 D BluetoothPbap: Proxy object disconnected
08-25 16:37:25.754  6737  6737 D PbapServerProfile: Bluetooth service disconnected
08-25 16:37:25.759  6737  6737 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 16:37:25.763  6737  6737 D BluetoothPermissionRequest: onReceive
08-25 16:37:25.763  6737  6737 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 16:37:25.769  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 16:37:25.771  6887  6887 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 16:37:25.771  6887  6887 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-25 16:37:25.772  6887  6887 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 16:37:25.780  6887  6887 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.780  6887  6887 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 16:37:25.782  6887  6887 V BluetoothFtpService: Ftp Service onStartCommand
08-25 16:37:25.782  6887  6887 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.782  6887  6887 V BluetoothFtpService: Ftp Service closeService
08-25 16:37:25.782  6887  6887 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 16:37:25.785  6887  6887 V BluetoothFtpService: successfully stopped ftp service
,08-25 16:37:25.785  6887  6887 V BluetoothFtpService: Ftp Service onDestroy
08-25 16:37:25.785  6887  6887 V BluetoothFtpService: Ftp Service closeService
08-25 16:37:25.789  6887  6887 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:25.789  6887  6887 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:25.789  6887  6887 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 16:37:25.789  6887  6887 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.789  6887  6887 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 16:37:25.789  6887  6887 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 16:37:25.791  6887  6887 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:25.791  6887  6887 V BluetoothSapService: state: 13
08-25 16:37:25.791  6887  6887 V BluetoothSapService: Stopping SAP server process
08-25 16:37:25.793  6887  6887 V BluetoothSapService: Sap Service closeSapService in
08-25 16:37:25.793  6887  6887 V BluetoothSapService: Close listen Socket : 
08-25 16:37:25.793  6887  6887 V BluetoothSapService: Close rfcomm Socket : 
08-25 16:37:25.793  6887  6887 V BluetoothSapService: Close sapd  Socket : 
08-25 16:37:25.794  7497  7548 I UEI.SmartControl: Device manager: loading config....
08-25 16:37:25.794  6887  6887 V BluetoothSapService: Sap Service closeSapService out
08-25 16:37:25.794  6887  6887 V BluetoothSapService: Sap Service onDestroy
08-25 16:37:25.794  6887  6887 V BluetoothSapService: Sap Service closeSapService in
08-25 16:37:25.794  6887  6887 V BluetoothSapService: Close listen Socket : 
08-25 16:37:25.794  6887  6887 V BluetoothSapService: Close rfcomm Socket : 
08-25 16:37:25.794  6887  6887 V BluetoothSapService: Close sapd  Socket : 
08-25 16:37:25.794  7497  7548 D UEI.SmartControl: ----------- loading internal config...
08-25 16:37:25.795  6887  6887 V BluetoothSapService: Sap Service closeSapService out
08-25 16:37:25.798  7497  7497 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 16:37:25.801  7497  7497 E UEI.SmartControl: Services init done
08-25 16:37:25.801  7497  7497 D UEI.SmartControl: QS Service init finished
08-25 16:37:25.802  7497  7497 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 16:37:25.802  7497  7497 D UEI.SmartControl: QS Service version code: 201091
08-25 16:37:25.802  7497  7497 D UEI.SmartControl: Service requested: Control
08-25 16:37:25.804  7497  7548 E UEI.SmartControl: Loading SETTINGS...
08-25 16:37:25.807  7497  7497 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 16:37:25.808  1034  1576 I ActivityManager: Killing 6801:com.lge.qremote/u0a112 (adj 15): empty #17
08-25 16:37:25.808  7497  7548 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 16:37:25.830  7497  7547 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 16:37:25.830  7497  7547 D UEI.SmartControl: -----service ready thread exits
,08-25 16:37:25.864  1034  1941 W libprocessgroup: failed to open /acct/uid_10112/pid_6801/cgroup.procs: No such file or directory
,08-25 16:37:25.866  7497  7497 D UEI.SmartControl: Internal service binding...
,08-25 16:37:26.588  6887  7355 D bt_hci_bdroid: cleanup
,08-25 16:37:26.596  6887  7423 I bt_lpm  : LPM is already off!!!
08-25 16:37:26.597  6887  7451 I bt_userial_mct: exiting userial_read_thread
08-25 16:37:26.597  6887  7451 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 16:37:26.598  6887  7421 W bt-btif : ag scb idx 1 not allocated
08-25 16:37:26.598  6887  7421 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 16:37:26.598  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:26.598  6887  7421 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 16:37:26.599  6887  7421 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 16:37:26.600  6887  7421 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 16:37:26.602  6887  7355 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 16:37:26.605  6887  7423 I bt_vendor: hw_epilog_process
08-25 16:37:26.605  6887  7355 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 16:37:26.605  6887  7355 D bt_userial_mct: userial_close
08-25 16:37:26.606  6887  7355 E bt_userial_mct: pthread_join() FAILED result:3
08-25 16:37:26.606  6887  7355 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 16:37:26.614  6887  7355 D bt_hci_bdroid: set_power 0
08-25 16:37:26.614  6887  7355 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 16:37:26.614  6887  7355 I bt_vendor: bluetooth satus is on
08-25 16:37:26.614  6887  7355 I bt_vendor: bt-vendor : resetting BT status
08-25 16:37:26.614  6887  7355 I bt_vendor: Starting hciattach daemon
08-25 16:37:26.614  6887  7355 I bt_vendor: try to set false
08-25 16:37:26.616  6887  7355 I bt_vendor: Starting hciattach daemon
08-25 16:37:26.616  6887  7355 I bt_vendor: try to set false
08-25 16:37:26.619  6887  7355 I bt_vendor: cleanup
,08-25 16:37:26.621  6887  7421 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 16:37:26.622  6887  7355 I GKI_LINUX: GKI_exit_task 0 done
08-25 16:37:26.622  6887  7355 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 16:37:26.624  6887  7351 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 16:37:26.627  6887  6887 D HeadsetService: Received stop request...Stopping profile...
08-25 16:37:26.631  6887  6887 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 16:37:26.631  6887  6887 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 16:37:26.631  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
,08-25 16:37:26.638  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:26.638  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 16:37:26.639  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:26.639  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:26.639  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 16:37:26.641  6887  6887 D A2dpService: Received stop request...Stopping profile...
08-25 16:37:26.642  6887  7393 D HeadsetStateMachine: Exit Disconnected: -1
08-25 16:37:26.644  6887  7351 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-25 16:37:26.646  6887  6887 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 16:37:26.647  6887  7411 D A2dpStateMachine: Exit Disconnected: -1
08-25 16:37:26.648  6887  6887 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 16:37:26.649  6887  6887 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 16:37:26.649  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:26.650  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-25 16:37:26.650  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 16:37:26.651  6887  6887 D HidService: Received stop request...Stopping profile...
08-25 16:37:26.651  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:26.654  6887  6887 D HealthService: Received stop request...Stopping profile...
08-25 16:37:26.654  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:26.655  6887  6887 D PanService: Received stop request...Stopping profile...
08-25 16:37:26.657  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
,08-25 16:37:26.661  6887  6887 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 16:37:26.661  6887  6887 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 16:37:26.662  6887  6887 D BtGatt.GattService: stop()
08-25 16:37:26.662  6887  6887 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 16:37:26.663  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:26.665  6887  6887 D HeadsetStateMachine: Unbinding service...
08-25 16:37:26.666  6887  6887 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 16:37:26.666  6887  6887 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 16:37:26.666  6887  6887 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 16:37:26.666  6887  6887 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 16:37:26.666  6887  6887 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 16:37:26.666  6887  6887 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 16:37:26.666  6887  6887 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 16:37:26.668  6887  6887 D BluetoothMapService: Received stop request...Stopping profile...
08-25 16:37:26.668  6887  6887 D BluetoothMapService: stop()
08-25 16:37:26.670  6887  6887 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 16:37:26.670  6887  6887 D BluetoothMapEmailAppObserver: removeReceiver()
,08-25 16:37:26.673  6887  6887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3327343e
08-25 16:37:26.674  6887  6887 V BluetoothMapService: Handler(): got msg=4
08-25 16:37:26.674  6887  6887 D BluetoothMapService: MAP Service closeService in
08-25 16:37:26.674  6887  6887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 16:37:26.674  6887  6887 V BluetoothMapService: MAP Service closeService out
08-25 16:37:26.675  6887  7351 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 16:37:26.675  6887  7351 D BluetoothAdapterProperties: Setting state to 10
08-25 16:37:26.675  6887  7351 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 16:37:26.675  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:26.675  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 16:37:26.676  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 16:37:26.676  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:26.676  6887  7351 I BluetoothAdapterState: Entering OffState
08-25 16:37:26.676  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:26.677  6737  6753 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 16:37:26.678  6737  6753 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 16:37:26.679  6737  6753 D BluetoothPan: onBluetoothStateChange on: false
08-25 16:37:26.681  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:26.682  6887  6887 I BluetoothA2dpServiceJni: cleanupNative
,08-25 16:37:26.686  6887  7412 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 16:37:26.688  6887  6887 I GKI_LINUX: GKI_exit_task 2 done
08-25 16:37:26.688  6887  6887 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 16:37:26.689  6737  6753 D BluetoothMap: onBluetoothStateChange: up=false
08-25 16:37:26.690  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 16:37:26.690  6887  6887 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 16:37:26.690  6887  6887 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 16:37:26.691  6737  6753 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:26.691  6887  6887 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 16:37:26.691  6887  6887 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 16:37:26.691  6887  6887 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 16:37:26.692  1853  2482 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:37:26.695  6737  6753 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 16:37:26.697  6887  6887 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 16:37:26.697  6887  6887 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 16:37:26.700  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 16:37:26.700  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 16:37:26.700  6887  6887 D BluetoothMapService: cleanup()
08-25 16:37:26.700  6887  6887 D BluetoothMapService: MAP Service closeService in
08-25 16:37:26.701  6887  6887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 16:37:26.701  6887  6887 V BluetoothMapService: MAP Service closeService out
08-25 16:37:26.703  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 16:37:26.703  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 16:37:26.703  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@34965230 mBinding = false
08-25 16:37:26.704  1034  1096 D BluetoothManagerService: Sending unbind request.
08-25 16:37:26.708  6887  7355 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 16:37:26.711  6887  6887 I GKI_LINUX: GKI_exit_task 1 done
08-25 16:37:26.711  6887  6887 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 16:37:26.711  6887  6887 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 16:37:26.712  6887  6887 I art     : --- WEIRD: removing null entry 248
08-25 16:37:26.712  6887  6887 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 16:37:26.712  6887  6887 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 16:37:26.713  6887  6887 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 16:37:26.714  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 16:37:26.716  6887  6887 I art     : System.exit called, status: 0
08-25 16:37:26.716  6887  6887 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 16:37:26.737   316  2150 V AudioFlinger: 6887 died, releasing its sessions
08-25 16:37:26.737   316  2150 V AudioFlinger:  pid 1853 @ 0
08-25 16:37:26.737   316  2150 V AudioFlinger:  pid 3435 @ 1
08-25 16:37:26.737   316  2150 V AudioFlinger:  pid 3435 @ 2
,08-25 16:37:26.741  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 16:37:26.741  1943  2076 D LGBluetoothAPIService: Message: 101
08-25 16:37:26.741  1943  2076 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-25 16:37:26.741  1943  2076 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 16:37:26.741  1943  2076 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-25 16:37:26.743  6737  6737 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 16:37:26.793  1034  1050 I ActivityManager: Process com.android.bluetooth (pid 6887) has died
08-25 16:37:26.793  1034  1050 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-25 16:37:26.794  1034  1050 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-25 16:37:26.803  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:26.803  1943  2076 D LGBluetoothAPIService: Message: 2
08-25 16:37:26.803  1943  2076 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-25 16:37:26.805  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:26.806  6737  6737 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 16:37:26.806  6737  6737 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 16:37:26.806  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 16:37:26.811  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:26.814  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 16:37:26.819  1603  1603 D BluetoothAdapter: 1068292952: getState() :  mService = null. Returning STATE_OFF
08-25 16:37:26.819  1603  1603 D BluetoothAdapter: 1068292952: getState() :  mService = null. Returning STATE_OFF
,08-25 16:37:26.868  1034  1942 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7582 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 16:37:26.870  6737  6737 D DockEventReceiver: finishStartingService: stopping service
,08-25 16:37:26.942  7582  7582 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 16:37:26.943  7582  7582 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:26.943  7582  7582 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 16:37:26.944  7582  7582 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 16:37:26.966  7582  7582 D BluetoothAdapterApp: Loading JNI Library
,08-25 16:37:27.003  7582  7582 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f08be66 Instance Count = 1
,08-25 16:37:27.009  7582  7582 D BluetoothAdapterApp: onCreate
,08-25 16:37:27.035  7582  7582 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 16:37:27.036  7582  7582 D ProfileConfigQcom: Adding HeadsetService
,08-25 16:37:27.037  7582  7582 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 16:37:27.037  7582  7582 D ProfileConfigQcom: Adding A2dpService
08-25 16:37:27.037  7582  7582 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 16:37:27.038  7582  7582 D ProfileConfigQcom: Adding HidService
,08-25 16:37:27.039  7582  7582 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 16:37:27.039  7582  7582 D ProfileConfigQcom: Adding HealthService
08-25 16:37:27.040  7582  7582 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 16:37:27.041  7582  7582 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 16:37:27.042  7582  7582 D ProfileConfigQcom: Adding PanService
08-25 16:37:27.042  7582  7582 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 16:37:27.043  7582  7582 D ProfileConfigQcom: Adding GattService
08-25 16:37:27.044  7582  7582 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 16:37:27.044  7582  7582 D ProfileConfigQcom: Adding BluetoothMapService
08-25 16:37:27.045  7582  7582 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 16:37:27.048  7582  7582 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 16:37:27.051  7582  7582 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:27.051  7582  7582 V BluetoothPbapReceiver: ***********state = 10
08-25 16:37:27.055  7582  7582 V LGMDMManagerInternal: Create singleton instance
08-25 16:37:27.152  7582  7582 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 16:37:27.152  7582  7582 D LGBluetoothAPIServer: [BTUI] onBind()
,08-25 16:37:27.157  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 16:37:27.161  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 16:37:27.162  1943  2076 D LGBluetoothAPIService: Message: 100
08-25 16:37:27.162  1943  2076 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 16:37:27.173  6737  6737 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 16:37:27.179  6737  6737 D BluetoothPermissionRequest: onReceive
,08-25 16:37:27.182  6737  6737 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 16:37:27.182  6737  6737 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-25 16:37:27.185  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 16:37:27.192  7582  7582 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-25 16:37:27.198  7582  7582 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:27.202  7582  7582 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:27.203  7582  7582 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:27.203  7582  7582 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 16:37:27.204  7582  7582 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:27.204  7582  7582 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 16:37:27.208  6820  6820 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-25 16:37:28.674  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 16:37:28.674  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:37:28.752  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-25 16:37:28.803  1034  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 16:37:28.844  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7613 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 16:37:28.899  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 16:37:28.902  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 16:37:28.905  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-25 16:37:28.928  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 16:37:28.929  1034  1034 D administrator: Handling package changes for user 0
08-25 16:37:28.940  7613  7613 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 16:37:29.007  7613  7613 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:29.007  7613  7613 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:29.034  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 16:37:29.034  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 16:37:29.081  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 16:37:29.089  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-25 16:37:29.098  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 16:37:29.099  7613  7656 I Babel   : MmsConfig: mnc/mcc: 0/0
08-25 16:37:29.099  2507  2507 V GmsNetworkLocationProvi: DISABLE
08-25 16:37:29.100  7613  7656 I Babel   : MmsConfig.loadMmsSettings
,08-25 16:37:29.110  7613  7656 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 16:37:29.110  7613  7656 I Babel   : MmsConfig.loadFromDatabase
,08-25 16:37:29.128  7613  7656 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-25 16:37:29.128  7613  7656 I Babel   : MmsConfig.loadFromResources
08-25 16:37:29.138  7613  7656 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 16:37:29.138  7613  7656 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 16:37:29.139  2507  2507 E GCoreFlp: Bound FusedProviderService with LocationManager
08-25 16:37:29.140  1034  1091 D LocationProviderProxy: applying state to connected service
,08-25 16:37:29.152  7613  7613 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:29.172  7613  7655 W AudioCapabilities: Unsupported mime audio/evrc
08-25 16:37:29.174  7613  7655 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 16:37:29.177  7613  7655 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 16:37:29.177  1818  7660 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-25 16:37:29.177  1818  7660 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-25 16:37:29.181  6934  6934 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 16:37:29.185  6934  6934 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bfcf7c0
08-25 16:37:29.185  6934  6934 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 16:37:29.185  6934  6934 D AppUp4:CustFacade: isPhone : true
08-25 16:37:29.185  6934  6934 D AppUp4:CustModeStarterReceiver: begin check event
08-25 16:37:29.185  6934  6934 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-25 16:37:29.192  1818  4736 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-25 16:37:29.214  7613  7655 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-25 16:37:29.223  1034  1647 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7663 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-25 16:37:29.224  7613  7655 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 16:37:29.225  7613  7655 W AudioCapabilities: Unsupported mime audio/evrc
08-25 16:37:29.226  1034  1888 I ActivityManager: Killing 6756:com.lge.sync/1000 (adj 15): empty #17
,08-25 16:37:29.233  7613  7655 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 16:37:29.235  7613  7655 W VideoCapabilities: Unsupported mime video/divx
08-25 16:37:29.237  7613  7655 W VideoCapabilities: Unsupported mime video/divx311
08-25 16:37:29.238  7613  7655 W VideoCapabilities: Unsupported mime video/divx4
08-25 16:37:29.242  7613  7655 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-25 16:37:29.244  1034  1457 D WifiService: Client connection lost with reason: 4
08-25 16:37:29.253  7613  7655 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 16:37:29.263  7613  7655 W AudioCapabilities: Unsupported mime audio/eac3
,08-25 16:37:29.264  7613  7655 W AudioCapabilities: Unsupported mime audio/ac3
08-25 16:37:29.265  7613  7655 W AudioCapabilities: Unsupported mime audio/g726
08-25 16:37:29.265  7613  7655 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-25 16:37:29.266  7613  7655 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 16:37:29.267  7613  7655 W AudioCapabilities: Unsupported mime audio/adpcm
08-25 16:37:29.269  7613  7655 W VideoCapabilities: Unsupported mime video/theora
08-25 16:37:29.271  7613  7655 W VideoCapabilities: Unsupported mime video/mjpg
08-25 16:37:29.356  1034  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6756/cgroup.procs: No such file or directory
,08-25 16:37:29.391  7663  7663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 16:37:29.392  7663  7663 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:29.392  7663  7663 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 16:37:29.393  7663  7663 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 16:37:29.394  7663  7663 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 16:37:29.470  7663  7663 I SystemConfig: BUILD Country: EU
08-25 16:37:29.471  7663  7663 I SystemConfig: BUILD Operator: OPEN
,08-25 16:37:29.525  1034  1978 I ActivityManager: Killing 6963:com.lge.email/u0a23 (adj 15): empty #17
,08-25 16:37:29.629  1034  1576 W libprocessgroup: failed to open /acct/uid_10023/pid_6963/cgroup.procs: No such file or directory
,08-25 16:37:29.644  7663  7682 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false,
08-25 16:37:29.645  7663  7682 I SystemConfig: existFile = false
08-25 16:37:29.645  7663  7682 I SystemConfig: canReadFile = false
08-25 16:37:29.645  7663  7682 I SystemConfig: systemFeature RCS result false
08-25 16:37:29.645  7663  7682 D SystemConfig: refreshRcsSupport() :false
,08-25 16:37:29.711  1034  1978 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7684 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-25 16:37:29.754  1034  1469 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-25 16:37:29.776  7684  7684 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 16:37:29.777  7684  7684 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 16:37:29.777  7684  7684 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 16:37:29.778  7684  7684 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 16:37:29.896  7684  7684 I AppConfig: Total System Memory = 2995761152
,08-25 16:37:29.912  7684  7684 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-25 16:37:30.013  1034  1052 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7709 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 16:37:30.014  1034  1052 I ActivityManager: Killing 6840:com.lge.formmanager/u0a26 (adj 15): empty #17
08-25 16:37:30.085  1034  1050 W libprocessgroup: failed to open /acct/uid_10026/pid_6840/cgroup.procs: No such file or directory
,08-25 16:37:30.251  7709  7709 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 16:37:30.353  7709  7709 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 16:37:30.353  7709  7709 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:30.415  7709  7709 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 16:37:30.435  7709  7709 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 16:37:30.436  7709  7709 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 16:37:30.453  7709  7709 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-25 16:37:30.453  7709  7709 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-25 16:37:30.478  1034  1648 I ActivityManager: Killing 6325:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-25 16:37:30.510  2846  2865 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-25 16:37:30.511  2846  2865 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34808c77 on behalf of 7709
,08-25 16:37:30.514  1034  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6325/cgroup.procs: No such file or directory
08-25 16:37:30.520  4585  7755 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-25 16:37:30.578  1034  1942 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7756 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 16:37:30.613  7709  7709 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-25 16:37:30.657  7709  7709 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-25 16:37:30.682  7756  7756 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 16:37:30.708  7756  7756 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-25 16:37:30.709  7756  7756 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 16:37:30.709  7756  7756 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-25 16:37:30.709  7756  7756 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 16:37:30.709  7756  7756 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-25 16:37:30.709  7756  7756 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-25 16:37:30.734  1034  1052 I ActivityManager: Killing 7004:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-25 16:37:30.784  1034  1888 W libprocessgroup: failed to open /acct/uid_10046/pid_7004/cgroup.procs: No such file or directory
,08-25 16:37:30.797  7497  7549 D UEI.SmartControl: Internal timer expired: 1
08-25 16:37:30.797  7497  7549 D UEI.SmartControl: unbind internal service
,08-25 16:37:30.799  7497  7497 D UEI.SmartControl: Service.onUnbind: IControl
,08-25 16:37:30.800  7497  7497 D UEI.SmartControl: Service.onDestroy
08-25 16:37:30.800  7497  7497 D UEI.SmartControl: Lock is in USE false
08-25 16:37:30.800  7497  7497 D UEI.SmartControl: unbind internal service
08-25 16:37:30.800  7497  7497 D serial_port: close(fd = 25)
08-25 16:37:30.805  7497  7497 I UEI.SmartControl: Serial port is closed.
08-25 16:37:30.805  7497  7497 I UEI.SmartControl: Serial port is closed.
08-25 16:37:30.805  7497  7497 D UEI.SmartControl: Blaster closed
08-25 16:37:30.805  7497  7497 D UEI.SmartControl: Shut down QS...
08-25 16:37:30.805  7497  7497 D UEI.SmartControl: Stopping QS lib
08-25 16:37:30.806  7497  7497 D UEI.SmartControl: QS lib stop result = true
08-25 16:37:30.806  7497  7497 D UEI.SmartControl: Stopped QS lib
08-25 16:37:30.806  7497  7497 D UEI.SmartControl: Stopped file observer...
08-25 16:37:30.807  7497  7497 D UEI.SmartControl: QS shutdown complete
08-25 16:37:30.978  1034  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-25 16:37:31.005  4585  7755 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 485 ms] updated apps [took 485 ms] 
,08-25 16:37:31.689  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:31.690  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3aeaae52 added. We now have 6 listener(s)
08-25 16:37:31.690  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:37:31.706  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:31.706  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c756523 added. We now have 7 listener(s)
,08-25 16:37:31.709  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:31.710  6658  6713 I System.out: IsBluetoothEnabled
08-25 16:37:31.711  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:31.711  1034  1887 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 16:37:31.712  1034  1096 D BluetoothManagerService: Message: 2
08-25 16:37:31.715  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:31.716  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:31.716  1034  2014 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 16:37:31.729  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 16:37:31.730  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 16:37:31.730  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:31.730  1034  1096 D BluetoothManagerService: Message: 1
08-25 16:37:31.731  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 16:37:31.756  1034  1096 D BluetoothManagerService: Message: 20
08-25 16:37:31.756  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@318a29:true
,08-25 16:37:31.760  7582  7582 D BluetoothAdapterState: make
08-25 16:37:31.765  7582  7582 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 16:37:31.765  7582  7582 I bluedroid-qcom: init
08-25 16:37:31.767  7582  7801 I BluetoothAdapterState: Entering OffState
08-25 16:37:31.767  7582  7582 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 16:37:31.767  7582  7582 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 16:37:31.767  7582  7582 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 16:37:31.767  7582  7582 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 16:37:31.767  7582  7582 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 16:37:31.769  7582  7582 I bluedroid-qcom: get_profile_interface socket
08-25 16:37:31.769  7582  7582 I bluedroid-qcom: get_profile_interface map_client
,08-25 16:37:31.773  7582  7805 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 16:37:31.777  7582  7805 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 16:37:31.764  7804  7804 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:31.764  7804  7804 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:31.789  7804  7804 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 16:37:31.789  7804  7804 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 16:37:31.789  7804  7804 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-25 16:37:31.793  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 16:37:31.793  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 16:37:31.793  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 16:37:31.794  1034  1096 D BluetoothManagerService: Message: 40
08-25 16:37:31.794  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 16:37:31.795  7582  7600 I bluedroid-qcom: config_hci_snoop_log
08-25 16:37:31.796  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 16:37:31.796  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 16:37:31.797  7804  7804 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 16:37:31.804  7804  7804 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 16:37:31.804  7804  7804 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-25 16:37:31.809  7582  7801 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 16:37:31.809  7582  7805 D BluetoothAdapterProperties: Name is: G3
08-25 16:37:31.810  7582  7801 D BluetoothAdapterProperties: Setting state to 11
08-25 16:37:31.810  7582  7801 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 16:37:31.810  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:31.811  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 16:37:31.811  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 16:37:31.812  7582  7801 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 16:37:31.816  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:31.819  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 16:37:31.822  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:31.825  6737  6737 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 16:37:31.830  7582  7582 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 16:37:31.830  7582  7582 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:31.831  7582  7582 V BluetoothPbapReceiver: ***********state = 11
,08-25 16:37:31.844  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:37:31.858  6737  6737 D BluetoothPermissionRequest: onReceive
08-25 16:37:31.859  7582  7801 D BluetoothBondStateMachine: make
,08-25 16:37:31.864  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 16:37:31.864  7582  7821 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 16:37:31.864  7582  7801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:31.864  7582  7801 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 16:37:31.864  7582  7801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:31.864  7582  7801 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 16:37:31.865  7582  7801 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 16:37:31.869  7582  7801 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:31.872  7582  7582 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:31.876  7582  7801 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:31.877  7582  7582 D HeadsetService: Received start request. Starting profile...
08-25 16:37:31.878  7582  7582 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 16:37:31.878  7582  7582 D LGBluetoothHfpAdapter: Version 1.6
08-25 16:37:31.881  7582  7582 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 16:37:31.882  7582  7801 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:31.882  7582  7582 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 16:37:31.882  7582  7582 D HeadsetStateMachine: make
08-25 16:37:31.887  7582  7801 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:31.893  7582  7801 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:31.897  7582  7801 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 16:37:31.903  7582  7801 E BluetoothAdapterService: File transfer profiles supported!!
08-25 16:37:31.915  7582  7582 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:31.915  7582  7801 V LGMDMManager: Create singleton instance
,08-25 16:37:31.915  7582  7582 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 16:37:31.917  7582  7801 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 16:37:31.919  7582  7582 D HeadsetStateMachine: max_hf_connections = 1
08-25 16:37:31.919  7582  7582 I bluedroid-qcom: get_profile_interface handsfree
08-25 16:37:31.921  7582  7582 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 16:37:31.921   316  1397 V AudioPolicyService: registerClient() client 0xb558a420, uid 1002
08-25 16:37:31.921   316  2147 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 16:37:31.921   316  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 16:37:31.922   316  2147 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 16:37:31.922  7582  7582 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 16:37:31.922   316  1398 V AudioFlinger: registerClient() client 0xb5581658, pid 7582
08-25 16:37:31.923   316  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:31.923  7582  7582 V ToneGenerator: Create Track: 0xb4928080
08-25 16:37:31.923  7582  7582 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 16:37:31.923   316  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:31.923  7582  7582 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 16:37:31.923  1034  1942 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:31.923  1603  3111 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:31.923  1603  3111 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:31.923  1034  1942 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:31.923   316  2150 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 16:37:31.923   316  2150 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 16:37:31.923   316  2150 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 16:37:31.923   316  2150 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 16:37:31.923  7582  7582 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 16:37:31.924  7582  7600 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:31.924  7582  7600 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 16:37:31.924   316  2150 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 16:37:31.924   316  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:31.924   316  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:31.924   316  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 16:37:31.924   316  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 16:37:31.924   316  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 16:37:31.924   316  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 16:37:31.924  7582  7582 V AudioSystem: getLatency() output 2, latency 50
08-25 16:37:31.925  7582  7582 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 16:37:31.925  7582  7582 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 16:37:31.925  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:31.925  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:31.925  1034  1906 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:31.925  1034  1906 V AudioSystem: ioConfigChan,ged() opening already existing output! 4
08-25 16:37:31.925  7582  7600 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:31.925  7582  7600 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 16:37:31.925  1853  4410 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:31.926  1853  4410 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:31.926  3435  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 16:37:31.926  3435  3450 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 16:37:31.926  1853  4410 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:31.926  1853  4410 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:31.926   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 16:37:31.926  3435  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 16:37:31.926  3435  3450 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 16:37:31.926   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 16:37:31.926   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 16:37:31.926   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 16:37:31.926   316   316 V AudioFlinger: createTrack() lSessionId: 21
08-25 16:37:31.927  7582  7582 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 16:37:31.927   316   316 V AudioFlinger: acquiring 21 from 7582, for 7582
08-25 16:37:31.927   316   316 V AudioFlinger:  added new entry for 21
08-25 16:37:31.927  7582  7582 V ToneGenerator: ToneGenerator INIT OK, time: 219704
08-25 16:37:31.927  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:31.928  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:31.928  7582  7823 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 16:37:31.928  7582  7582 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:31.928  7582  7582 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:31.929  7582  7582 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 16:37:31.929  7582  7582 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:31.929  7582  7582 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 16:37:31.929  7582  7823 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 16:37:31.929  7582  7823 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 16:37:31.929  7582  7823 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 16:37:31.930   316  2150 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7582
08-25 16:37:31.932  7582  7582 D A2dpService: Received start request. Starting profile...
08-25 16:37:31.932   316  2150 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 16:37:31.932   316  2150 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 16:37:31.932   316  2150 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 16:37:31.932   316  2150 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 16:37:31.932   316  2150 V voice   : voice_set_parameters: exit with code(0)
08-25 16:37:31.932   316  2150 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 16:37:31.932   316  2150 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 16:37:31.932   316  2150 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 16:37:31.933  7582  7582 I BluetoothAvrcpServiceJni: clas,sInitNative: succeeds
08-25 16:37:31.933   316  2150 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 16:37:31.933   316  2150 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 16:37:31.933   316  2150 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 16:37:31.933  7582  7823 V ToneGenerator: ToneGenerator destructor
08-25 16:37:31.933  7582  7823 V ToneGenerator: stopTone
08-25 16:37:31.933  7582  7823 V ToneGenerator: Delete Track: 0xb4928080
08-25 16:37:31.934  7582  7582 V Avrcp   : make
08-25 16:37:31.934   316  1398 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 16:37:31.934   316  1398 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 16:37:31.934   316  1259 V AudioPolicyService: AudioCommandThread() waking up
08-25 16:37:31.934   316  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 16:37:31.934   316  1259 V AudioPolicyManager: releaseOutput() 2
08-25 16:37:31.934   316  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 16:37:31.934   316  1398 V AudioFlinger: PlaybackThread::Track destructor
08-25 16:37:31.934   316  1398 V AudioFlinger: removeClient_l() pid 7582, calling pid 316
08-25 16:37:31.934  7582  7823 V AudioTrack: ~AudioTrack, releasing session id from 7582 on behalf of 7582
08-25 16:37:31.935   316   316 V AudioFlinger: releasing 21 from 7582 for 7582
08-25 16:37:31.935   316   316 V AudioFlinger:  decremented refcount to 0
08-25 16:37:31.935   316   316 V AudioFlinger: purging stale effects
08-25 16:37:31.935  7582  7582 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 16:37:31.935  7582  7582 I bluedroid-qcom: get_profile_interface avrcp
08-25 16:37:31.936  1034  1906 W Process : Unable to open /proc/7825/status
08-25 16:37:31.943  7582  7582 V AudioManager: registerRemoteController: size of Media player list: 0
08-25 16:37:31.945  7582  7582 E AudioManager: No RCC entry present to update
08-25 16:37:31.945  7582  7582 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 16:37:31.948  7582  7582 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 16:37:31.949  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 16:37:31.950  7582  7582 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 16:37:31.953  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 16:37:32.069  1034  1648 V SIM_STK : Menu title from STK is T-Mobile
08-25 16:37:32.069  1034  1648 V SIM_STK : Menu title from STK is T-Mobile
,08-25 16:37:32.180  1034  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 16:37:32.191  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 16:37:32.195  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 16:37:32.196  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 16:37:32.197  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 16:37:32.197  7582  7582 I BluetoothA2dpServiceJni: classInitNative
08-25 16:37:32.197  7582  7582 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 16:37:32.197  7582  7582 D A2dpStateMachine: make
08-25 16:37:32.198  7582  7582 I bluedroid-qcom: get_profile_interface a2dp
08-25 16:37:32.198  7582  7833 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 16:37:32.200  7582  7582 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 16:37:32.200  7582  7582 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 16:37:32.201  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:32.202  7582  7582 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 16:37:32.203  7582  7832 D A2dpStateMachine: Enter Disconnected: -2
08-25 16:37:32.204  7582  7582 D HidService: Received start request. Starting profile...
08-25 16:37:32.204  7582  7582 I bluedroid-qcom: get_profile_interface hidhost
08-25 16:37:32.204  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:32.204  7582  7582 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 16:37:32.205  7582  7582 D HealthService: Received start request. Starting profile...
08-25 16:37:32.207  7582  7582 I bluedroid-qcom: get_profile_interface health
08-25 16:37:32.207  7582  7582 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 16:37:32.207  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:32.207  7582  7582 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 16:37:32.209  7582  7582 D PanService: Received start request. Starting profile...
08-25 16:37:32.209  7582  7582 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 16:37:32.209  7582  7582 I bluedroid-qcom: get_profile_interface pan
,08-25 16:37:32.214  7582  7582 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 16:37:32.214  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
,08-25 16:37:32.215  7582  7582 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 16:37:32.219  7582  7582 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 16:37:32.219  7582  7582 D BtGatt.GattService: Received start request. Starting profile...
08-25 16:37:32.219  7582  7582 D BtGatt.GattService: start()
08-25 16:37:32.219  7582  7582 I bluedroid-qcom: get_profile_interface gatt
08-25 16:37:32.219  7582  7582 D BtGatt.AdvertiseManager: advertise manager created
08-25 16:37:32.224  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:32.225  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:32.226  7582  7582 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 16:37:32.226  7582  7582 V BluetoothMapService: BluetoothMapBinder()
08-25 16:37:32.228  7582  7582 D BluetoothMapService: Received start request. Starting profile...
08-25 16:37:32.228  7582  7582 D BluetoothMapService: start()
,08-25 16:37:32.230  7582  7582 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 16:37:32.230  7582  7582 D BluetoothMapEmailAppObserver: createReceiver()
08-25 16:37:32.231  7582  7582 D BluetoothMapEmailAppObserver: initObservers()
08-25 16:37:32.231  7582  7582 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 16:37:32.237  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:32.237  7582  7582 D HeadsetStateMachine: Proxy object connected
08-25 16:37:32.237  7582  7582 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 16:37:32.237  7582  7582 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 16:37:32.244  7582  7582 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:32.244  7582  7823 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 16:37:32.245  7582  7823 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 16:37:32.245  7582  7823 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-25 16:37:32.249  7582  7582 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:32.250  7582  7582 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:32.252  7582  7582 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:32.252  7582  7582 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 16:37:32.254  7582  7582 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 16:37:32.256  7582  7582 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 16:37:32.256  7582  7582 V BluetoothMapService: Handler(): got msg=1
08-25 16:37:32.258  7582  7801 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 16:37:32.258  7582  7801 I bluedroid-qcom: enable
,08-25 16:37:32.258  7582  7801 I bt_hci_bdroid: init
08-25 16:37:32.259  7582  7801 I bt_vendor: bt-vendor : init
08-25 16:37:32.259  7582  7801 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 16:37:32.259  7582  7801 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 16:37:32.259  7582  7801 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 16:37:32.259  7582  7801 D bt_userial_mct: userial_init
08-25 16:37:32.259  7582  7843 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 16:37:32.260  7582  7801 D bt_hci_bdroid: set_power 1
08-25 16:37:32.260  7582  7801 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 16:37:32.260  7582  7843 I bt-btu  : btu_task pending for preload complete event
08-25 16:37:32.260  7582  7801 I bt_vendor: Starting hciattach daemon
08-25 16:37:32.260  7582  7801 I bt_vendor: try to set true
08-25 16:37:32.244  7846  7846 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:32.244  7846  7846 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:32.277  7847  7847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 16:37:32.321  7853  7853 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 16:37:32.329  7854  7854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 16:37:32.344  7856  7856 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 16:37:32.351  7857  7857 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-25 16:37:32.359  7858  7858 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 16:37:32.366  7859  7859 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-25 16:37:32.382  7861  7861 I libmdmdetect: ESOC framework not supported
,08-25 16:37:32.383  7861  7861 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 16:37:32.391  7861  7861 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 16:37:32.391  7861  7861 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-25 16:37:32.391  7861  7861 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 16:37:32.391  7861  7861 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 16:37:32.391  7861  7861 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 16:37:32.391  7861  7861 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-25 16:37:32.391  7861  7861 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 16:37:32.429  7861  7862 E QC-QMI  : qmi_client [7861] 15: failed to locate client data
08-25 16:37:32.430   447   447 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 16:37:32.430   447   447 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-25 16:37:32.483  7863  7863 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 16:37:32.502  7864  7864 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 16:37:32.562  7582  7801 I bt_vendor: bluetooth satus is on
08-25 16:37:32.562  7582  7801 D bt_hci_bdroid: preload
08-25 16:37:32.565  7582  7845 D bt_userial_mct: userial_open(port:0)
08-25 16:37:32.565  7582  7845 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 16:37:32.571  7582  7845 I bt_vendor: Done intiailizing UART
,08-25 16:37:32.574  7582  7845 I bt_vendor: Done intiailizing UART
08-25 16:37:32.575  7582  7845 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-25 16:37:32.575  7582  7845 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 16:37:32.575  7582  7866 D bt_userial_mct: Entering userial_read_thread()
08-25 16:37:32.576  7582  7843 I bt-btu  : btu_task received preload complete event
08-25 16:37:32.577  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-25 16:37:32.577  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 16:37:32.585  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 16:37:32.600  7582  7843 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 16:37:32.601  7582  7843 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 16:37:32.601  7582  7843 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 16:37:32.601  7582  7843 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 16:37:32.683  7582  7843 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 16:37:32.683  7582  7843 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
08-25 16:37:32.683  7582  7843 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-25 16:37:32.700  7582  7805 E bt-btif : Calling BTA_HhEnable
08-25 16:37:32.700  7582  7805 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 16:37:32.701  7582  7805 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 16:37:32.703  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 16:37:32.703  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 16:37:32.703  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 16:37:32.705  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 16:37:32.705  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 16:37:32.706  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 16:37:32.706  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 16:37:32.706  7582  7805 D BluetoothAdapterProperties: Name is: G3
08-25 16:37:32.707  7582  7805 D BluetoothAdapterProperties: Scan Mode:20
08-25 16:37:32.708  7582  7805 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 16:37:32.708  7582  7805 D bt_hci_bdroid: postload
08-25 16:37:32.708  7582  7845 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:32.709  7582  7843 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 16:37:32.709  7582  7805 D bte_conf: Device ID record 1 : primary
08-25 16:37:32.709  7582  7805 D bte_conf:   vendorId            = 00c4
08-25 16:37:32.709  7582  7805 D bte_conf:   vendorIdSource      = 0001
08-25 16:37:32.709  7582  7805 D bte_conf:   product             = 13a1
08-25 16:37:32.709  7582  7805 D bte_conf:   version             = 1000
08-25 16:37:32.709  7582  7805 D bte_conf:   clientExecutableURL = 
08-25 16:37:32.709  7582  7805 D bte_conf:   serviceDescription  = 
08-25 16:37:32.709  7582  7805 D bte_conf:   documentationURL    = 
08-25 16:37:32.710  7582  7805 D bte_conf: bte_load_did_conf no section named DID2.
08-25 16:37:32.713  7582  7801 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 16:37:32.713  7582  7801 D BluetoothAdapterProperties: ScanMode =  20
08-25 16:37:32.714  7582  7801 D BluetoothAdapterProperties: State =  11
08-25 16:37:32.714  7582  7801 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 16:37:32.714  7582  7801 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 16:37:32.714  7582  7801 D BluetoothAdapterProperties: Setting state to 12
08-25 16:37:32.714  7582  7801 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 16:37:32.719  7582  7805 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 16:37:32.704  7871  7871 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:32.723  7582  7801 I BluetoothAdapterState: Entering On State
08-25 16:37:32.714  7871  7871 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:32.726  1034  1096 D BluetoothManagerService: Message: 60
08-25 16:37:32.726  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 16:37:32.726  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 16:37:32.726  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:37:32.727  7582  7805 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 16:37:32.751  7582  7805 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 16:37:32.751  7582  7805 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-25 16:37:32.772  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:37:32.776  1034  1034 D BluetoothHeadset: Proxy object connected
08-25 16:37:32.776  7582  7801 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 16:37:32.776  7582  7801 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 16:37:32.776  7582  7801 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 16:37:32.780  7582  7801 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 16:37:32.780  7582  7801 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:32.781  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:32.794  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:37:32.798  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 16:37:32.800  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:32.802  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:32.802  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1edeea20 added. We now have 8 listener(s)
08-25 16:37:32.802  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:32.810  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:37:32.826  7582  7845 D bt_hci_bdroid: Used up Tx Cmd credits,
08-25 16:37:32.830  7582  7845 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 16:37:32.830  1034  1647 D WifiServiceImplEx: setWifiEnabled: false pid=6658, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 16:37:32.831  1034  1647 D WifiService: setWifiEnabled: false pid=6658, uid=10118
08-25 16:37:32.831  1034  1647 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:37:32.832  7582  7845 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 16:37:32.833  6737  6753 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 16:37:32.836  7582  7866 E bt_mct  : hci lib postload completed
08-25 16:37:32.839  6737  6755 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 16:37:32.842  7582  7843 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:32.842  7582  7843 W bt-smp  : Plain text(LSB ~ MSB) = 53 3d 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:32.842  7582  7843 W bt-smp  : Encrypted text(LSB ~ MSB) = 9d 47 b6 b0 99 2a ce f6 60 41 63 8b e2 27 77 92 
08-25 16:37:32.842  7582  7843 W bt-btm  : Stopping oneshot timer
08-25 16:37:32.842  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:32.844  1034  1887 D WifiServiceImplEx: setWifiEnabled: true pid=6658, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 16:37:32.844  1034  1887 D WifiService: setWifiEnabled: true pid=6658, uid=10118
08-25 16:37:32.844  1034  1887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:37:32.846  6737  6753 D BluetoothPan: onBluetoothStateChange on: true
08-25 16:37:32.846  6737  6753 D BluetoothPan: onBluetoothStateChange call bindService
08-25 16:37:32.854  6737  6737 D BluetoothInputDevice: Proxy object connected
08-25 16:37:32.854  6737  6737 D HidProfile: Bluetooth service connected
,08-25 16:37:32.858  1034  1400 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 16:37:32.858  7582  7843 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:32.858  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 16:37:32.858  7582  7843 W bt-smp  : Plain text(LSB ~ MSB) = e7 62 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:32.858  7582  7843 W bt-smp  : Encrypted text(LSB ~ MSB) = 81 2b a1 7e 16 18 26 c5 b8 b7 3d c9 2b a0 25 f0 
08-25 16:37:32.858  7582  7843 W bt-btm  : Stopping oneshot timer
08-25 16:37:32.859  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 16:37:32.859  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 16:37:32.858  1034  1400 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 16:37:32.863  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 16:37:32.863  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 16:37:32.863  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 16:37:32.863  1034  1400 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 16:37:32.863  1034  1400 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 16:37:32.863  1034  1400 E WifiHW  : unknown target_country: EU , set to default
08-25 16:37:32.863  1034  1400 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 16:37:32.863  1034  1400 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 16:37:32.863  1034  1400 I WifiUtil: gEnableBmps=1
08-25 16:37:32.864  7888  7888 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-25 16:37:32.871  1853  4410 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:37:32.874  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 16:37:32.875  6737  7457 D BluetoothMap: onBluetoothStateChange: up=true
08-25 16:37:32.880  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 16:37:32.881  1034  1034 D BluetoothA2dp: Proxy object connected
,08-25 16:37:32.882  6737  6737 D BluetoothA2dp: Proxy object connected
08-25 16:37:32.882  6737  6737 D A2dpProfile: Bluetooth service connected
08-25 16:37:32.883  6737  6753 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:37:32.885  1853  2482 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:37:32.885  6737  6737 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 16:37:32.885  6737  6737 D PanProfile: Bluetooth service connected
08-25 16:37:32.887  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 16:37:32.887  7582  7843 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:32.887  7582  7843 W bt-smp  : Plain text(LSB ~ MSB) = 27 f2 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:32.887  7582  7843 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e e3 46 7b be bd 9a 4a 8b 0d c7 c8 64 67 67 89 
08-25 16:37:32.887  7582  7843 W bt-btm  : Stopping oneshot timer
08-25 16:37:32.887  6737  7457 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 16:37:32.888  6737  6737 D BluetoothMap: Proxy object connected
08-25 16:37:32.888  6737  6737 D MapProfile: Bluetooth service connected
08-25 16:37:32.888  6737  6737 D BluetoothMap: getConnectedDevices()
08-25 16:37:32.889  7582  7600 V BluetoothMapService: getConnectedDevices()
08-25 16:37:32.889  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 16:37:32.889  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 16:37:32.891  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 16:37:32.892  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 16:37:32.893  1943  2076 D LGBluetoothAPIService: Message: 1
08-25 16:37:32.893  1943  2076 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 16:37:32.893  1943  2076 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-25 16:37:32.893  1943  2076 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 16:37:32.894  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:32.895  7582  7843 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:32.895  7582  7843 W bt-smp  : Plain text(LSB ~ MSB) = 07 af 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:32.895  7582  7843 W bt-smp  : Encrypted text(LSB ~ MSB) = c1 ef ff b3 c1 41 8b 26 38 20 e1 00 d7 b1 46 ab 
08-25 16:37:32.895  7582  7843 W bt-btm  : Stopping oneshot timer
08-25 16:37:32.898  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 16:37:32.898  1034  1096 D BluetoothManagerService: Message: 40
08-25 16:37:32.898  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 16:37:32.899  6737  6737 D BluetoothHeadset: Proxy object connected
08-25 16:37:32.899  6737  6737 D HeadsetProfile: Bluetooth service connected
08-25 16:37:32.902  7582  7582 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:32.902  7582  7582 D BluetoothMapService: STATE_ON
08-25 16:37:32.904  6737  6737 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 16:37:32.905  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 16:37:32.908  7582  7843 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 16:37:32.908  7582  7843 W bt-smp  : Plain text(LSB ~ MSB) = 08 bd 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 16:37:32.908  7582  7843 W bt-smp  : Encrypted text(LSB ~ MSB) = 3a 7a 74 90 83 bb 03 d3 a7 ce c3 57 e7 da d8 b7 
08-25 16:37:32.908  7582  7843 W bt-btm  : Stopping oneshot timer
,08-25 16:37:32.911  6737  6737 D DockEventReceiver: finishStartingService: stopping service
08-25 16:37:32.919  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:32.919  7582  7582 V BluetoothPbapService: Pbap Service onCreate
08-25 16:37:32.920  7582  7582 V BluetoothPbapService: Starting PBAP service
,08-25 16:37:32.921  7582  7582 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 16:37:32.921  7582  7582 V BluetoothPbapService: Pbap Service onBind
08-25 16:37:32.923  7582  7582 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:32.923  7582  7582 V BluetoothPbapService: state: 12
08-25 16:37:32.923  7582  7582 V BluetoothMapService: Handler(): got msg=1
08-25 16:37:32.923  6737  6737 D BluetoothPbap: Proxy object connected
08-25 16:37:32.923  6737  6737 D PbapServerProfile: Bluetooth service connected
08-25 16:37:32.923  7582  7582 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 16:37:32.924  7582  7582 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 16:37:32.924  7582  7582 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:32.924  7582  7582 V BluetoothPbapReceiver: ***********state = 12
08-25 16:37:32.925  7582  7899 D BluetoothMapMasInstance: MAS initSocket()
08-25 16:37:32.925  7582  7582 V BluetoothPbapService: Handler(): got msg=1
08-25 16:37:32.925  7582  7582 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 16:37:32.925  7582  7899 D BluetoothMapMasInstance:   masId = 00
08-25 16:37:32.925  7582  7899 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 16:37:32.925  7582  7899 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 16:37:32.925  7582  7899 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 16:37:32.927  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:32.927  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 16:37:32.927  2208  2208 D c       : Getting all permits...
08-25 16:37:32.927  2208  2208 D a       : Opening database...
08-25 16:37:32.927  7582  7900 V BluetoothPbapService: Pbap Service initSocket
08-25 16:37:32.928  7582  7899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:32.928  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:32.929  7582  7900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:32.930  7582  7900 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-25 16:37:32.930  7582  7899 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 16:37:32.930  7582  7899 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 16:37:32.930  7582  7899 D BluetoothMapMasInstance: Accepting socket connection...
08-25 16:37:32.930  7582  7900 V BluetoothPbapService: Succeed to create listening socket 
08-25 16:37:32.930  7582  7900 V BluetoothPbapService: Accepting socket connection...
08-25 16:37:32.931  7582  7805 D BluetoothAdapterProperties: Scan Mode:21
08-25 16:37:32.931  7582  7805 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-25 16:37:32.933  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-25 16:37:32.934  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:32.934  2208  2208 D a       : Closing database...
08-25 16:37:32.945  6737  6737 D BluetoothPermissionRequest: onReceive
,08-25 16:37:32.947  6737  6737 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 16:37:32.949  6737  6737 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 16:37:32.952  7582  7582 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 16:37:32.953  7582  7582 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 16:37:32.960  7582  7582 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 16:37:32.980  7582  7582 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 16:37:32.980  7582  7582 V BtOppService: onCreate
08-25 16:37:32.985  7582  7582 V BluetoothOppNotification: send message
08-25 16:37:32.990  7582  7582 V BtOppService: Starting RfcommListener
08-25 16:37:33.000  7582  7582 D BluetoothOppPreference: Dumping Names:  
08-25 16:37:33.000  7582  7582 D BluetoothOppPreference: {}
08-25 16:37:33.000  7582  7582 D BluetoothOppPreference: Dumping Channels:  
08-25 16:37:33.000  7582  7582 D BluetoothOppPreference: {}
08-25 16:37:33.002  7582  7582 V BtOppService: onStartCommand
08-25 16:37:33.007  7582  7582 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:33.007  7582  7582 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 16:37:33.011  7582  7582 V BluetoothOppNotification: new notify threadi!
08-25 16:37:33.012  7582  7582 V BluetoothOppNotification: send delay message
08-25 16:37:33.012  7582  7582 V BtOppService: start RfcommListener
08-25 16:37:33.015  7582  7906 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-25 16:37:33.018  7582  7903 V BtOppService: Deleted complete outbound shares, number =  0
,08-25 16:37:33.019  7582  7908 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 16:37:33.020  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:33.020  7582  7582 V BtOppService: RfcommListener started
08-25 16:37:33.021  7582  7907 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 16:37:33.021  7582  7908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:33.023  7582  7903 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 16:37:33.024  7582  7903 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 16:37:33.025  7582  7907 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@452f78b on behalf of 
08-25 16:37:33.025  7582  7908 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=73
08-25 16:37:33.025  7582  7903 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f41f068 on behalf of 
08-25 16:37:33.026  7582  7907 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 16:37:33.027  7582  7908 V BtOppRfcommListener: Started RFCOMM listener....
,08-25 16:37:33.028  7582  7908 I BtOppRfcommListener: Accept thread started.
08-25 16:37:33.028  7582  7908 V BtOppRfcommListener: Accepting connection...
08-25 16:37:33.029  7582  7906 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 16:37:33.029  7582  7907 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 16:37:33.042  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
08-25 16:37:33.042  7582  7582 V BluetoothFtpService: Ftp Service onCreate
08-25 16:37:33.042  7582  7582 I BluetoothFtpService: Ftp Service onCreate
08-25 16:37:33.042  7582  7582 V BluetoothFtpService: Ftp Service onStartCommand
08-25 16:37:33.042  7582  7582 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:33.043  7582  7582 V BluetoothFtpService: Starting Listening on sockets
08-25 16:37:33.043  7582  7582 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 16:37:33.043  7582  7582 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 16:37:33.043  7582  7582 V BluetoothSapReceiver: SapReceiver onReceive 
,08-25 16:37:33.043  7582  7582 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:33.044  7582  7582 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 16:37:33.044  7582  7582 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 16:37:33.048  7582  7582 V BtOppService: ContentObserver received notification
08-25 16:37:33.048  7582  7582 V BtOppService: ContentObserver received notification
08-25 16:37:33.048  7582  7582 V BluetoothFtpService: Handler(): got msg=1
08-25 16:37:33.049  7582  7582 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 16:37:33.049  7582  7582 V BluetoothFtpService: Ftp Service initSocket
08-25 16:37:33.056  1034  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 16:37:33.058  7582  7582 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:33.059  7582  7582 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-25 16:37:33.059  7582  7582 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 16:37:33.062  7582  7909 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 16:37:33.090  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f90529f
,08-25 16:37:33.090  7582  7582 V BluetoothSapService: Sap Service onCreate
08-25 16:37:33.092  7582  7582 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:37:33.092  7582  7582 V BluetoothSapService: state: 12
08-25 16:37:33.092  7582  7582 V BluetoothSapService: Starting SAP server process
08-25 16:37:33.094  7582  7582 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 16:37:33.084  7910  7910 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:33.084  7910  7910 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:33.096  7582  7911 V BluetoothSapService: Sap Service initRfcommSocket
08-25 16:37:33.097  1034  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:33.098  7582  7911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:37:33.099  7582  7911 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 16:37:33.099  7582  7911 V BluetoothSapService: Succeed to create listening socket 
08-25 16:37:33.099  7582  7911 V BluetoothSapService: Accepting socket connection...
08-25 16:37:33.107  7910  7910 V BT_SAP  : Event pipe created
08-25 16:37:33.107  7910  7910 V BT_SAP  : create_server_socket qcom.sap.server
08-25 16:37:33.107  7910  7910 V BT_SAP  : created socket fd 6
,08-25 16:37:33.180  1034  1888 I art     : Explicit concurrent mark sweep GC freed 27938(1364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.393ms total 146.246ms
,08-25 16:37:33.180  7582  7906 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35661fbd on behalf of 
08-25 16:37:33.181  7582  7907 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@235549b2 on behalf of 
08-25 16:37:33.182  7582  7906 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-25 16:37:33.182  7582  7906 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 16:37:33.183  7582  7907 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 16:37:33.185  7582  7906 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3970cd03 on behalf of 
08-25 16:37:33.186  7582  7906 V BluetoothOppNotification: update too frequent, put in queue
08-25 16:37:33.186  7582  7906 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 16:37:33.186  7582  7907 V BluetoothOppNotification: outbound notification was removed.
08-25 16:37:33.187  7582  7907 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 16:37:33.190  7582  7907 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26d06480 on behalf of 
08-25 16:37:33.192  7582  7907 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 16:37:33.193  7582  7907 V BluetoothOppNotification: inbound notification was removed.
08-25 16:37:33.193  7582  7907 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-25 16:37:33.196  7582  7907 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@59fab9 on behalf of 
08-25 16:37:33.673   311   880 D SoftapController: Softap fwReload - Ok
,08-25 16:37:33.677  1034  1400 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (799ms)
08-25 16:37:33.685   311   880 D CommandListener: Setting iface cfg
08-25 16:37:33.685   311   880 D CommandListener: Trying to bring down wlan0
,08-25 16:37:33.693  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 16:37:33.693  1034  1096 D Tethering: InitialState.processMessage what=4
08-25 16:37:33.713   311   880 D CommandListener: Clearing all IP addresses on wlan0
,08-25 16:37:33.717  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 16:37:33.724  1034  1400 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 16:37:33.724  7929  7929 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:33.724  7929  7929 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:33.746  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:33.746  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:33.746  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:33.766  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:33.773  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 16:37:33.791  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:33.799  1034  1400 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 16:37:33.799  1034  1400 D WifiMonitor: connecting to supplicant
08-25 16:37:33.803  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 16:37:33.804  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 16:37:33.804  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 16:37:33.804  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 16:37:33.804  6737  6737 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 16:37:33.808  7929  7929 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 16:37:33.809  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 16:37:33.811  6737  6737 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 16:37:33.811  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 16:37:33.811  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 16:37:33.811  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 16:37:33.811  6737  6737 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 16:37:33.812  6737  6737 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 16:37:33.816  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 16:37:33.816  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 16:37:33.816  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 16:37:33.816  6737  6737 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 16:37:33.817  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 16:37:33.817  6737  6737 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-25 16:37:33.817  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 16:37:33.817  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 16:37:33.817  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 16:37:33.817  6737  6737 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 16:37:33.818  6737  6737 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 16:37:33.846  7929  7929 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 16:37:33.847  7929  7929 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 16:37:33.856  1034  1648 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7947 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 16:37:33.917  7929  7929 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 16:37:33.974  7929  7929 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 16:37:33.977  7929  7929 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 16:37:33.978  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 16:37:33.978  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 16:37:33.978  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 16:37:33.979  1034  1400 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 16:37:33.979  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:33.979  1034  7972 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 16:37:33.979  1034  7972 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 16:37:33.979  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:33.979  1034  1400 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:33.980  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:33.980  1034  1400 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 16:37:33.980  1034  1400 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 16:37:33.980  1034  1960 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7969 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 16:37:33.980  1034  1400 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 16:37:33.980  1034  1400 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 16:37:33.980  1034  1400 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 16:37:33.983  1034  1400 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 16:37:33.983  1034  1400 E WifiStateMachine: useWiFiOffloading() : false
08-25 16:37:33.983  1034  1400 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 16:37:33.983  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:33.983  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:33.983  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:33.984  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:33.984  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 16:37:33.984  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 16:37:33.984  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 16:37:33.984  7929  7929 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 16:37:33.984  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 16:37:33.984  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 16:37:33.985  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 16:37:33.985  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 16:37:33.986  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:33.986  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-25 16:37:33.988  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 16:37:33.988  1034  1400 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 16:37:33.988  1034  14,44 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:33.989  6658  6658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:33.989  1034  1400 D WifiNative-wlan0: SET update_config 1: returned true
08-25 16:37:33.989  1034  1400 D WifiConfigStore: Loading config and enabling all networks 
08-25 16:37:33.989  1034  1400 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 16:37:33.989  1034  1400 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-25 16:37:33.992  6658  6658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:33.993  1034  1400 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 16:37:33.995  7947  7967 W FormManager: Network not available. Please check & try again.
08-25 16:37:33.998  1034  1400 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 16:37:33.998  1034  1400 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 16:37:33.999  1034  1400 D WifiStateMachine: enableVerboseLogging : level 2
08-25 16:37:33.999  1034  1400 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 16:37:33.999  1034  1400 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 16:37:33.999  1034  1400 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 16:37:33.999  1034  1400 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 16:37:33.999  1034  1400 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 16:37:34.000  1034  1400 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 16:37:34.001  1034  1400 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 16:37:34.002  1034  1400 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 16:37:34.002  1034  1400 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 16:37:34.002  1034  1400 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 16:37:34.002  1034  1400 D WifiNative-HAL: Setting external_sim to 1
08-25 16:37:34.002  1034  1400 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 16:37:34.003  1034  1400 D WifiNative-wlan0: SET external_sim 1: returned true
,08-25 16:37:34.003  1034  1400 I WifiNative-HAL: startHal
08-25 16:37:34.003  1034  1400 D wifi    : setting scan oui 0xaf4ff640
08-25 16:37:34.006  1034  1400 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 16:37:34.006  1034  1400 I WifiNative-HAL: startHal
08-25 16:37:34.006  1034  1400 D wifi    : setting scan oui 0xaf4ff640
08-25 16:37:34.006  1034  1400 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 16:37:34.006  1034  1400 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 16:37:34.006  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 16:37:34.006  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 16:37:34.007  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 16:37:34.007  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 16:37:34.007  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 16:37:34.007  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 16:37:34.007  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 16:37:34.007  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 16:37:34.007  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 16:37:34.007  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 16:37:34.007  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 16:37:34.008  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 16:37:34.008  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 16:37:34.008  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 16:37:34.008  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 16:37:34.008  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 16:37:34.008  7929  7929 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 16:37:34.008  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 16:37:34.008  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 16:37:34.008  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 16:37:34.009  1034  1400 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 16:37:34.009  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-25 16:37:34.009  1943  2228 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 16:37:34.009  1943  2228 D WfdsService: Set the WFDS Monitor: true
08-25 16:37:34.009  1943  2228 D WfdsMonitor: WfdsMonitorThread create
08-25 16:37:34.009  1034  1400 E WifiNative: : [221,774,379 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 16:37:34.009  1034  1400 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 16:37:34.009  1943  2228 D WfdsMonitor: WFDS Monitor is created and started
08-25 16:37:34.009  1943  2228 D WfdsService: WiFi: Supplicant connection re-established
08-25 16:37:34.009  1034  1400 D WifiNative-wlan0: RECONNECT: returned true
08-25 16:37:34.009  1034  1400 D WifiNative-wlan0: doString: [STATUS]
08-25 16:37:34.010  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 16:37:34.010  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 16:37:34.010  1943  7986 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 16:37:34.010  1034  1400 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 16:37:34.010  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:34.010  1943  7986 E CtrlSupplicant: Succeed to open control connection
08-25 16:37:34.010  1034  1400 D WifiNative-wlan0: SET ps 1: returned t,rue
08-25 16:37:34.010  1943  7986 E CtrlSupplicant: Succeed to open monitor connection
08-25 16:37:34.011  1943  7986 D WfdsMonitor: Supplicant connection established
08-25 16:37:34.011  1943  2228 D WfdsService: Connected to the supplicant for wfds
08-25 16:37:34.011  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.012   311   880 D CommandListener: Setting iface cfg
08-25 16:37:34.012   311   880 D CommandListener: Trying to bring up p2p0
08-25 16:37:34.012  1034  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 16:37:34.012  1034  1391 D LGWifiP2pService: P2pEnablingState
08-25 16:37:34.012  1034  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.012  1034  1391 D LGWifiP2pService: P2p socket connection successful
08-25 16:37:34.012  1034  1391 D LGWifiP2pService: P2pEnabledState
08-25 16:37:34.012  1034  1391 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 16:37:34.012  1034  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 16:37:34.013  7582  7582 V BluetoothOppNotification: new notify threadi!
08-25 16:37:34.013  7582  7582 V BluetoothOppNotification: send delay message
08-25 16:37:34.014  1034  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 16:37:34.014  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 16:37:34.014  1034  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 16:37:34.014  1034  1391 D WifiNative-p2p0: SET device_name G3: returned true
08-25 16:37:34.014  1943  1943 D WfdsService: WifiP2pState is changed : true
08-25 16:37:34.014  1034  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 16:37:34.014  1034  1391 D LGWifiP2pService: before postfix = G3
08-25 16:37:34.014  1034  1391 D WifiServerServiceExt: postfix byte check : 2
08-25 16:37:34.014  1034  1391 D LGWifiP2pService: after postfix = G3
08-25 16:37:34.014  1034  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 16:37:34.014  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 16:37:34.014  1034  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 16:37:34.014  1034  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 16:37:34.015  1943  1943 D WfdsService: isConnected: false
08-25 16:37:34.015  1034  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 16:37:34.015  1943  2228 D WfdsService: Receive the WFDS_ENABLE Method
08-25 16:37:34.015  1943  2228 D WfdsService: Set the WFDS Monitor: true
08-25 16:37:34.015  1943  2228 D WfdsService: Connected to the supplicant for wfds
08-25 16:37:34.015  1943  2228 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 16:37:34.015  7929  7929 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 16:37:34.016  1943  2228 D WfdsService: selectPreferredScanChannel [36]
08-25 16:37:34.016  1943  2228 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 16:37:34.018  1034  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 16:37:34.020  1034  1400 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 16:37:34.020  1034  1400 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 16:37:34.021  1034  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 16:37:34.021  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 16:37:34.021  1034  1400 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 16:37:34.021  1034  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 16:37:34.021  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress
08-25 16:37:34.021  1034  1400 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 16:37:34.021  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 16:37:34.022  1034  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 16:37:34.022  1034  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 16:37:34.022  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=221787  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:34.022  1034  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 16:37:34.022  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 16:37:34.022  1034  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 16:37:34.022  1034  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 16:37:34.023  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=221788  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:34.023  1034  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 16:37:34.023  1034  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 16:37:34.023  1034  1400 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 16:37:34.024  1034  1400 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 16:37:34.024  1034  1400 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 16:37:34.025  1034  1400 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 16:37:34.025  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 16:37:34.025  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-25 16:37:34.025  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.025  1034  1557 I WifiNative-HAL: startHal
08-25 16:37:34.025  1034  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.026  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.026  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 16:37:34.026  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.026  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 16:37:34.027  1943  1943 D WfdsService: Update P2p Interface State: 3
08-25 16:37:34.027  7947  7968 V FormManager: Network unavailable.
08-25 16:37:34.027  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.027  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.027  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 16:37:34.027  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.033  7582  7989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 16:37:34.033  7929  7929 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 16:37:34.034  1034  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 16:37:34.034  1034  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 16:37:34.034  1034  1400 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 16:37:34.034  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf4ff640
08-25 16:37:34.034  1034  1557 D wifi    : failed to get capabilities : -3
08-25 16:37:34.034  1034  1557 E WifiScanningService: could not get scan capabilities
08-25 16:37:34.034  1034  1391 D LGWifiP2pService: InactiveState
08-25 16:37:34.034  1034  1400 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 16:37:34.034  1034  1391 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.034  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.034  1034  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 16:37:34.034  7947  7968 V FormManager: Network unavailable.
08-25 16:37:34.035  1034  1400 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 16:37:34.035  1034  1400 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 16:37:34.035  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 16:37:34.035  7582  7989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34ca4efe on behalf of 
08-25 16:37:34.035  7929  7929 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:34.035  1943  7986 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 16:37:34.035  7582  7989 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 16:37:34.036  7929  7929 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 16:37:34.036  7929  7929 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 16:37:34.037  7582  7989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 16:37:34.037  7929  7929 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.037  1943  7986 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.037  7613  7613 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.037  7929  7929 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.037  1943  7986 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.038  1034  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 16:37:34.038  1034  7972 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 16:37:34.038  1034  7972 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:34.038  1034  1391 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.038  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:34.038  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.038  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:34.038  1034  1391 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.038  1034  7972 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.038  1034  7972 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.038  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.038  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.038  1034  7972 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.038  1034  7972 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.038  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.039  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.039  1034  1400 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 16:37:34.040  1034  1400 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 16:37:34.040  1034  1400 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 16:37:34.040  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 16:37:34.040  1034  1034 E WifiServerServiceExt: No p2p device connected
08-25 16:37:34.041  7582  7989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34a9365f on behalf of 
08-25 16:37:34.041  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 16:37:34.041  1943  2228 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 16:37:34.041  7582  7989 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 16:37:34.041  7929  7929 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 16:37:34.042  7929  7929 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 16:37:34.042  7582  7989 V BluetoothOppNotification: outbound notification was removed.
08-25 16:37:34.042  7582  7989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 16:37:34.042  7929  7929 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.042  1943  7986 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.043  7929  7929 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.043  1943  7986 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.043  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 16:37:34.043  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:34.044  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:34.044  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 16:37:34.044  1034  7972 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.044  1034  7972 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.044  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.044  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.044  1034  7972 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 16:37:34.044  1034  7972 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.044  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.044  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 16:37:34.045  1034  1400 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 16:37:34.045  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.045  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.045  1034  1400 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 16:37:34.045  1034  1400 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 16:37:34.046  1034  1400 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 16:37:34.046  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 16:37:34.046  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 16:37:34.046  7929  7929 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:34.046  7582  7989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@271748ac on behalf of 
08-25 16:37:34.047  7582  7989 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 16:37:34.047  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 16:37:34.047  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:34.047  1034  7972 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:34.047  1034  7972 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 16:37:34.048  1034  1400 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 16:37:34.048  1034  1400 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 16:37:34.048  7582  7989 V BluetoothOppNotification: inbound notification was removed.
08-25 16:37:34.048  7582  7989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 16:37:34.048  1034  1400 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 16:37:34.048  1034  1400 D WifiNative-wlan0: doBoolean: SCAN
08-25 16:37:34.049  7582  7989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e168975 on behalf of 
08-25 16:37:34.049  1034  1400 D WifiNative-wlan0: SCAN: returned false
08-25 16:37:34.049  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=221815  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:34.050  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=221815  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 16:37:34.051  1034  1400 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:34.051  1034  1400 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:34.051  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.051  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.051  1034  1400 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:34.052  1034  1400 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:34.052  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.052  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.052  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 16:37:34.052  1034  1400 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 16:37:34.053  1034  1647 I ActivityManager: Killing 7025:com.android.chrome/u0a57 (adj 15): empty #17
08-25 16:37:34.056  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.084  1034  1906 W libprocessgroup: failed to open /acct/uid_10057/pid_7025/cgroup.procs: No such file or directory
,08-25 16:37:34.086  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:34.086  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 16:37:34.136  7969  7969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 16:37:34.142  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 16:37:34.151  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:34.153  1034  2014 I ActivityManager: Killing 7049:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 16:37:34.228  1034  1996 W libprocessgroup: failed to open /acct/uid_10062/pid_7049/cgroup.procs: No such file or directory
,08-25 16:37:34.253  7969  7969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 16:37:34.262  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 16:37:34.273  7947  7993 W FormManager: Network not available. Please check & try again.
08-25 16:37:34.276  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:34.282  7947  7994 V FormManager: Network unavailable.
,08-25 16:37:34.287  7947  7994 V FormManager: Network unavailable.
08-25 16:37:34.294  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 16:37:34.294  4314  4314 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 16:37:34.297  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:34.303  4314  4314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 16:37:34.313  4314  7995 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 16:37:34.316  4314  7996 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 16:37:34.316  4314  7996 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 16:37:34.376  1034  1576 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8000 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 16:37:34.502  8000  8000 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 16:37:34.502  8000  8000 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 16:37:34.513  8000  8000 V [BNRBootReceiver]: Boot Receiver Return
08-25 16:37:34.515  8000  8000 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-25 16:37:34.590  7929  7929 E wpa_supplicant: USIM:  scard_init function
,08-25 16:37:34.591  7929  7929 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 16:37:34.593  1034  1941 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8018 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 16:37:34.594  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 16:37:34.594  1034  7972 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 16:37:34.594  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 16:37:34.594  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-25 16:37:34.594  1034  7972 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 16:37:34.595  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 16:37:34.595  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 16:37:34.597  1034  1400 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 16:37:34.598  1034  1400 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 16:37:34.599  1034  1400 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-25 16:37:34.606  1034  1400 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 16:37:34.607  1034  1400 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 16:37:34.609   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 22.417ms
08-25 16:37:34.611  1034  1941 I ActivityManager: Killing 7066:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-25 16:37:34.632   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 459us total 20.770ms
,08-25 16:37:34.656   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 23.692ms
,08-25 16:37:34.695  1034  1647 W libprocessgroup: failed to open /acct/uid_10085/pid_7066/cgroup.procs: No such file or directory
,08-25 16:37:34.697  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=222462  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 16:37:34.706  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.706  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.706  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 16:37:34.706  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.706  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.708  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:34.711  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=222469  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 16:37:34.712  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:34.713  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 16:37:34.722  7929  7929 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 16:37:34.722  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 16:37:34.722  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 16:37:34.722  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 16:37:34.723  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-25 16:37:34.723  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:34.723  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:34.726  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=222491  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 16:37:34.726  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=222492  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 16:37:34.727  1034  1400 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222492
08-25 16:37:34.727  1034  1400 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222493
08-25 16:37:34.728  1034  1400 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222493
08-25 16:37:34.728  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222493
08-25 16:37:34.729  1034  1400 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222494
08-25 16:37:34.730  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=222495  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 16:37:34.732  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.732  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.732  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:34.732  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:34.732  7929  7929 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 16:37:34.733  7929  7929 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 16:37:34.734  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.735  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 16:37:34.735  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 16:37:34.735  1034  7972 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 16:37:34.736  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 16:37:34.736  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 16:37:34.736  1034  7972 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-25 16:37:34.736  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:34.736  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:34.729  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:34.737  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 16:37:34.738  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.736  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 16:37:34.738  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.738  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 16:37:34.740  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=222505  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 16:37:34.740  1034  1400 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=222506  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 16:37:34.741  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=222506  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 16:37:34.741  8018  8018 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:34.742  1034  1400 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=222507
08-25 16:37:34.742  1034  1400 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=222508
08-25 16:37:34.743  1034  1400 D WifiNative-wlan0: doString: [STATUS]
08-25 16:37:34.744  1034  1400 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 16:37:34.744  1034  7972 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 16:37:34.744  1034  7972 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 16:37:34.747  1034  1400 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 16:37:34.747  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:34.747  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.747  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 16:37:34.756  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.756  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.756  1034  1400 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 16:37:34.756  1034  1400 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 16:37:34.757  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:34.762  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.762  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.762  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 16:37:34.767  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.767  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.767  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 16:37:34.774  1034  1400 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 16:37:34.774  1034  1469 D ConnectivityService: Got NetworkAgent Messenger
08-25 16:37:34.774  1034  1400 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 16:37:34.774  1034  1400 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 16:37:34.774  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 16:37:34.774  1034  1469 D ConnectivityService: NetworkAgent connected
08-25 16:37:34.775  1034  1400 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-25 16:37:34.775  1034  1400 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 16:37:34.779  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.779  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.780  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.781  8018  8018 D PluginManager: init()
08-25 16:37:34.781  1034  1400 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 16:37:34.782  1034  1400 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 16:37:34.782  1034  1400 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 16:37:34.782  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.782  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.782  1034  1400 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 16:37:34.782  1034  1400 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 16:37:34.783  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.787  1034  1400 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 16:37:34.791   311   880 D CommandListener: Setting iface cfg
08-25 16:37:34.794  1034  1400 E WifiStateMachine: Start Dhcp Watchdog 3
08-25 16:37:34.794  1034  8041 D DhcpStateMachine: StoppedState
08-25 16:37:34.794  1034  8041 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.795  1034  8041 D DhcpStateMachine: WaitBeforeStartState
08-25 16:37:34.795  1034  1400 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=222560  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:34.796  1034  1400 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=222561  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:34.798  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=222564  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:34.799  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:34.799  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:34.800  1034  1400 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:34.800  1034  1400 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-25 16:37:34.801  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:34.801  1034  1400 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 16:37:34.802  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:34.802  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 16:37:34.804  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:34.804  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 16:37:34.804  1034  1400 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=222569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:34.804  1034  1400 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=222569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:34.805  1034  1400 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=222570  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 16:37:34.806  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13375] from screen [on:0 period:-1037927722] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 16:37:34.807  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1037927721] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 16:37:34.807  1034  1400 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 16:37:34.812  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 16:37:34.813  1034  1469 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-25 16:37:34.813  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.814  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.814  1034  1400 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.814  1034  1400 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.815  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.815  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.816  1034  1469 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 16:37:34.816  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
08-25 16:37:34.817  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
08-25 16:37:34.817  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 16:37:34.817  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 16:37:34.817  1034  1400 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 16:37:34.817  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 16:37:34.818  1034  1400 D WifiNative-wlan0: SET ps 0: returned true
08-25 16:37:34.818  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 16:37:34.818  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 16:37:34.818  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 16:37:34.818  1034  1400 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 16:37:34.818  1034  1400 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 16:37:34.818  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ce13356 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.819  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ce13356 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.819  1034  1400 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 16:37:34.819  1034  8041 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.819  1034  8041 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 16:37:34.820   311   880 D CommandListener: Setting iface cfg
08-25 16:37:34.820   311   880 D CommandListener: Trying to bring up wlan0
08-25 16:37:34.822  1034  1400 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 16:37:34.823  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:34.823  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 16:37:34.824  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 16:37:34.824  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-25 16:37:34.825  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 16:37:34.825  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.826  1034  1400 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.827  1034  1400 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 16:37:34.829  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.829  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 16:37:34.830  1034  1469 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 16:37:34.830  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 16:37:34.830  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 16:37:34.830  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 16:37:34.831  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.831  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.831  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 16:37:34.831  1034  1400 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 16:37:34.831  1034  1400 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 16:37:34.831  7929  7929 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 16:37:34.832  1034  1400 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 16:37:34.832  1034  1400 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 16:37:34.848  1034  1400 D WifiNative-wlan0: SET ps 1: returned true
08-25 16:37:34.848  1034  1469 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 16:37:34.849  1034  1400 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 16:37:34.849  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 16:37:34.849  1034  1400 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 16:37:34.850  1034  1469 D ConnectivityService: ignoring duplicate network state non-change
,08-25 16:37:34.853  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.853  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 16:37:34.855  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.855  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:34.855  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.856  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 16:37:34.857  1034  1469 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 16:37:34.858  1034  1469 D ConnectivityService: Adding iface wlan0 to network 102
08-25 16:37:34.863  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.863  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.863  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-25 16:37:34.868  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 16:37:34.872  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 16:37:34.874  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:37:34.874  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.874  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 16:37:34.876  1034  1400 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 16:37:34.878  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-25 16:37:34.885  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.885  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:37:34.885  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:37:34.886  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:37:34.887  1034  1469 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 16:37:34.887  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:37:34.887  1034  1469 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 16:37:34.889  1034  1469 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 16:37:34.890   311   880 E Netd    : netlink response contains error (File exists)
08-25 16:37:34.890  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.890  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 16:37:34.890  1034  1469 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 16:37:34.891  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.891  1034  1469 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 16:37:34.891  1034  1469 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-25 16:37:34.892  1034  1469 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-25 16:37:34.893  6658  6713 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 16:37:34.893  1034  1469 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 16:37:34.893  1034  1469 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 16:37:34.893  1034  1469 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 16:37:34.893  1034  1469 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 16:37:34.893  1034  1469 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:34.893  1034  8039 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.893  1034  8039 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 16:37:34.893  1034  1469 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:34.893  1034  1469 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 16:37:34.893  1034  1469 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:34.893  1034  1469 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 16:37:34.893  1034  1469 D ConnectivityService: currentScore = 0, newScore = 20
08-25 16:37:34.894  1034  1469 D ConnectivityService:    accepting network in place of null
08-25 16:37:34.894  1034  1469 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:34.894  1034  8039 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 16:37:34.894  1034  8039 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 16:37:34.894  1034  1400 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:34.894  1034  1400 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:34.894  6658  6713 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 16:37:34.895  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.895  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 16:37:34.895  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.898  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true,, isConnectedToProvisioningNetwork: false]
08-25 16:37:34.898  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 16:37:34.898  6658  6713 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@265364a2 Bundle[{}]
08-25 16:37:34.898  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.899  6658  6713 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 16:37:34.899   311  8046 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 16:37:34.899  6658  6713 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 16:37:34.900  6658  6713 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 16:37:34.900  6658  6713 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 16:37:34.901  6658  6713 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 16:37:34.902  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:34.902  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 16:37:34.902  6658  6713 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 16:37:34.903  1034  1469 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 16:37:34.903  1034  1469 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 16:37:34.903  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 16:37:34.903  1034  1469 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:37:34.903  1034  1469 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 16:37:34.904  1034  1469 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 16:37:34.905  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 16:37:34.905  1034  1469 D ConnectivityService: validation of new default Network = false
08-25 16:37:34.905  1034  1469 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 16:37:34.905  1034  1469 D DSQN    : enableDataServiceNotify 
08-25 16:37:34.905  1034  1469 D DSQN    : start dsqn bin
,08-25 16:37:34.905  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 16:37:34.905  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 16:37:34.905  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-25 16:37:34.910  1034  1469 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 16:37:34.910  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:34.910  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:34.911  1034  1469 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:34.894  8047  8047 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:34.894  8047  8047 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:34.914  6658  6713 I System.out: Running OutgoingSocketThread
08-25 16:37:34.914  1603  2077 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 16:37:34.918  6658  8048 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
,08-25 16:37:34.919  6658  8048 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48529
08-25 16:37:34.919  6658  8048 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 16:37:34.923  8047  8047 E DSQN    : DSQN ssw
08-25 16:37:34.928  1034  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-25 16:37:34.944   311  8046 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 16:37:34.944  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 16:37:34.945  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.946  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:34.975   311  8046 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 16:37:35.003   311   879 D LGDataListener: argv[0]=dsqncommand
08-25 16:37:35.004   311   879 D LGDataListener: argv[1]=wlan0
08-25 16:37:35.004   311   879 D LGDataListener: argv[2]=1
08-25 16:37:35.004   311   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 16:37:35.004  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 16:37:35.004  1034  1094 D DSQN    : start to monitor internet connection
,08-25 16:37:35.021  1034  8041 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 16:37:35.023  1034  8041 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 16:37:35.024  1034  8041 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-25 16:37:35.029  1034  8039 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 14:37:35 GMT], X-Android-Received-Millis=[1472135855028], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472135855003]}
08-25 16:37:35.029  1034  8039 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 16:37:35.029  1034  8039 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 16:37:35.030  1034  1469 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-25 16:37:35.030  1034  1469 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 16:37:35.030  1034  1469 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:35.030  1034  1469 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:35.030  1034  1469 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 16:37:35.031  1034  1469 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-25 16:37:35.014  8054  8054 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:35.014  8054  8054 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 16:37:35.031  1034  1469 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 16:37:35.031  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:35.031  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:35.032  1034  1469 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:35.033  1034  1469 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:35.034  1034  1400 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:35.034  1034  1400 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 16:37:35.034  1603  2077 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 16:37:35.034  1034  1469 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 16:37:35.037  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:35.037  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-25 16:37:35.050  8054  8054 I dhcpcd  : version 5.5.6 starting
,08-25 16:37:35.054  8054  8054 E dhcpcd  : get_duid: m
08-25 16:37:35.054  8054  8054 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 16:37:35.054  8054  8054 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 16:37:35.068  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-25 16:37:35.069  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:35.070  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 16:37:35.115  8054  8054 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 16:37:35.115  8054  8054 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 16:37:35.115  8054  8054 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-25 16:37:35.115  8054  8054 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-25 16:37:35.115  8054  8054 D dhcpcd  : wlan0: sending REQUEST (xid 0x6ac56a9a), next in 4.81 seconds
,08-25 16:37:35.162  8054  8054 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 16:37:35.223  8054  8054 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-25 16:37:35.223  8054  8054 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-25 16:37:35.224  8054  8054 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-25 16:37:35.224  8054  8054 D dhcpcd  : wlan0: adding default route via 192.168.1.1,
08-25 16:37:35.225  8054  8054 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease',
08-25 16:37:35.226  8054  8054 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 16:37:35.226  8054  8054 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-25 16:37:35.226  8054  8054 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 16:37:35.231  8018  8018 W ExternalStrings: load override strings
08-25 16:37:35.231  8018  8018 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 16:37:35.231  8018  8018 W ExternalStrings: ,	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 16:37:35.231  8018  8018 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 16:37:35.235  8018  8018 D StatusProvider: onCreate
08-25 16:37:35.276  8018  8018 V Signer  : override build config not found
08-25 16:37:35.276  8018  8018 D Signer  : value of property debug is false
,08-25 16:37:35.299  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 16:37:35.299  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-25 16:37:35.300  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 16:37:35.300  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 16:37:35.300  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 16:37:35.300  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 16:37:35.300  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 16:37:35.300  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 16:37:35.300  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-25 16:37:35.301  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 16:37:35.301  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 16:37:35.301  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-25 16:37:35.301  8018  8018 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-25 16:37:35.308  8018  8018 V LGMDMManager: Create singleton instance
08-25 16:37:35.344  8018  8018 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-25 16:37:35.380  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:35.381  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:35.406  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:35.411  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:35.448  1034  1978 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8089 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-25 16:37:35.448  1034  1978 I ActivityManager: Killing 7100:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-25 16:37:35.529  8018  8077 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 16:37:35.632  1034  8041 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 16:37:35.700  1034  1576 W libprocessgroup: failed to open /acct/uid_10093/pid_7100/cgroup.procs: No such file or directory
,08-25 16:37:35.717  1034  1377 V AlarmManager: RTC_WAKEUP set : Alarm{30da0273 type 0 when 1472135849951 com.google.android.gms} when 1472135849951
,08-25 16:37:35.725  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{11844530 type 2 when 223302 android} when 223302
08-25 16:37:35.729  1034  8041 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 16:37:35.730  1034  8041 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 16:37:35.731  1034  8041 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 16:37:35.731  1034  8041 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 16:37:35.731  1034  8041 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 16:37:35.731  1034  8041 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 16:37:35.731  1034  8041 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 16:37:35.733  1034  8041 D DhcpStateMachine: RunningState
,08-25 16:37:35.756  8089  8089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:35.795  8089  8089 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 16:37:35.831  8089  8089 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 16:37:35.832  8089  8089 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 16:37:35.832  8089  8089 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 16:37:35.833  8089  8089 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 16:37:35.833  8089  8089 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-25 16:37:35.835  8089  8089 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 16:37:35.840  8089  8089 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 16:37:35.847  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 16:37:35.849  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:35.858  8018  8077 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:35.858  8018  8077 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:35.868  8089  8089 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 16:37:35.871  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:35.872  8089  8089 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 16:37:35.873  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:35.875  8089  8089 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 16:37:35.877  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:35.884  1034  1400 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 16:37:35.885  1034  1400 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 16:37:35.885  1034  1400 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 16:37:35.886  1034  1400 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 16:37:35.886  1034  1400 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 16:37:35.887  1034  1400 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 16:37:35.887  1034  1469 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-25 16:37:35.887  1034  1469 D ConnectivityService: identical MTU - not setting
08-25 16:37:35.887  1034  1469 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 16:37:35.887  1034  1469 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 16:37:35.887  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 16:37:35.887  1034  1469 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 16:37:35.888  1034  1469 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 16:37:35.889  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:35.889  1603  2077 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 16:37:35.896  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:35.897  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:35.899  8089  8089 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 16:37:35.904  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 16:37:35.914  6737  6737 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-25 16:37:35.917  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:35.917  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:35.921  6658  6713 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
08-25 16:37:35.921  6658  6713 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
08-25 16:37:35.923  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 16:37:35.925  6658  6713 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
08-25 16:37:35.928  6658  6713 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 16:37:35.928  6658  6713 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
08-25 16:37:35.929  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:35.931  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:35.932  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ff9fd9 added. We now have 2 listener(s)
08-25 16:37:35.932  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 16:37:35.936  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:35.937  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:35.937  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:35.937  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:35.937  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e615d9e added. We now have 9 listener(s)
08-25 16:37:35.937  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:35.937  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:37:35.942  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:35.942  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:35.943  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:35.944  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:35.949  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:35.949  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:35.950  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:35.951  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:35.951  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:35.951  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:35.951  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3618884c added. We now have 3 listener(s)
08-25 16:37:35.954  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:35.954  1034  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:35.957  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:35.957  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:35.957  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:35.957  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:35.957  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c16095 added. We now have 10 listener(s)
08-25 16:37:35.957  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:35.958  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:35.958  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:35.958  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:35.958  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:35.958  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exis,t in the list - probably already removed
08-25 16:37:35.958  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:35.958  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:35.958  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ff9fd9 removed from the list
08-25 16:37:35.958  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:35.958  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e615d9e removed from the list
08-25 16:37:35.959  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:35.959  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:35.959  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:35.960  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:35.960  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:35.960  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:35.960  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:35.960  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:35.961  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e615d9e not in the list
08-25 16:37:35.961  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:35.961  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:37:35.961  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:35.961  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:35.961  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:35.962  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c16095 removed from the list
08-25 16:37:35.962  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:35.962  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:35.962  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:35.962  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:35.962  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3618884c removed from the list
08-25 16:37:35.963  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:35.963  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e01b5aa added. We now have 2 listener(s)
08-25 16:37:35.963  1034  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:35.965  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 16:37:35.968  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:35.968  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:35.968  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:35.968  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:35.968  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3790559b added. We now have 9 listener(s)
08-25 16:37:35.968  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:35.969  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:37:35.972  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:37:35.974  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:35.978  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:35.980  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:35.981  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:35.981  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:35.981  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a47111 added. We now have 3 listener(s)
08-25 16:37:35.982  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:35.983  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:35.983  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:35.983  1034  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:35.984  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:35.986  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:35.987  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:35.987  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:35.987  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:35.987  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:35.987  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b9d8276 added. We now have 10 listener(s)
08-25 16:37:35.987  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:35.987  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:35.987  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:37:35.987  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:37:35.987  6658  6713 I org.thaliproject.p2p.btcon,nectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:35.987  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 16:37:35.990  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 16:37:35.990  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 16:37:35.991  1034  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:35.991  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 16:37:35.991  6737  6737 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 16:37:35.991  6737  6737 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 16:37:35.991  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 16:37:35.993  6737  6737 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 16:37:35.993  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 16:37:35.993  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 16:37:35.993  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 16:37:35.993  6737  6737 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 16:37:35.993  6737  6737 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 16:37:35.993  6737  6737 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 16:37:35.997  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 16:37:35.997  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 16:37:35.998  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:35.998  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:36.000  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:37:36.002  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:36.004  6658  6713 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 16:37:36.004  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:36.004  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:36.005  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:36.006  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:36.007  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:36.007  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:36.007  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.007  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.007  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:36.007  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.007  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e01b5aa removed from the list
08-25 16:37:36.007  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.007  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3790559b removed from the list
08-25 16:37:36.007  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:36.007  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.008  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.008  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.009  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.009  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.009  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.009  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3790559b not in the list
08-25 16:37:36.009  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.010  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.010  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.011  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:36.011  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:36.011  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.011  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.011  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b9d8276 removed from the list
08-25 16:37:36.011  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.011  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.011  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 ,16:37:36.011  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.011  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a47111 removed from the list
08-25 16:37:36.012  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:36.012  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cce0d4d added. We now have 2 listener(s)
08-25 16:37:36.012  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:36.013  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:36.017  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:36.017  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:36.017  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:36.017  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:36.017  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32575002 added. We now have 9 listener(s)
08-25 16:37:36.017  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:36.017  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 16:37:36.022  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:36.022  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:36.023  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:36.023  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:36.025  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:36.026  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.027  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:36.028  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:36.028  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:36.028  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:36.028  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25111b50 added. We now have 3 listener(s)
08-25 16:37:36.030  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:36.033  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:37:36.035  1034  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:36.036  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 16:37:36.038  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:36.038  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:36.038  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:36.038  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:36.038  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7b3149 added. We now have 10 listener(s)
08-25 16:37:36.038  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:36.038  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:36.039  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:36.039  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:37:36.039  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:37:36.039  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:36.039  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 16:37:36.042  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 16:37:36.042  1034  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 16:37:36.047  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:36.048  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 16:37:36.049  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 16:37:36.053  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:37:36.053  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:36.054  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:36.054  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:36.054  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:36.056  6658  6713 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 16:37:36.056  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:36.056  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:36.056  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:36.056  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.057  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.057  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:36.057  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.057  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cce0d4d removed from the list
08-25 16:37:36.057  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.057  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32575002 removed from the list
08-25 16:37:36.057  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:36.057  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.059  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.059  8018  8077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-25 16:37:36.059  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.059  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.060  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.060  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.060  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.060  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32575002 not in the list
08-25 16:37:36.060  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.060  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.060  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:36.061  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.061  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:36.062  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:36.062  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.062  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.062  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7b3149 removed from the list
08-25 16:37:36.062  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.062  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.062  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.062  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.062  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25111b50 removed from the list
08-25 16:37:36.063  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:36.063  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf49c7c added. We now have 2 listener(s)
08-25 16:37:36.065  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:36.067  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 16:37:36.067  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:36.067  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:36.067  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:,37:36.068  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:36.068  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbc9905 added. We now have 9 listener(s)
08-25 16:37:36.068  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:36.068  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:37:36.070  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:36.074  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:36.076  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:36.076  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:36.077  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:36.077  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:36.077  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6ddb8b added. We now have 3 listener(s)
08-25 16:37:36.077  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:36.078  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:36.080  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:36.080  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:36.080  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:36.080  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:36.080  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f2d0468 added. We now have 10 listener(s)
08-25 16:37:36.080  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:36.081  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:36.081  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:37:36.081  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:37:36.081  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:37:36.081  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 16:37:36.082  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:36.083  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:36.083  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:36.085  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 16:37:36.085  1034  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:36.086  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:36.089  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 16:37:36.089  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 16:37:36.091  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:37:36.091  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:36.091  8018  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-25 16:37:36.095  6658  6713 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-25 16:37:36.096  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:36.096  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:36.096  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:36.097  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.097  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.097  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:36.097  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.097  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf49c7c removed from the list
08-25 16:37:36.097  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.097  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbc9905 removed from the list
08-25 16:37:36.097  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:36.097  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.097  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.097  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.098  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.098  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.098  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.098  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbc9905 not in the list
08-25 16:37:36.098  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.098  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.099  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:36.099  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.099  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.100  6658  6713 D BluetoothLeScanner: could not find callback wrapper
08-25 16:37:36.100  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:37:36.100  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.100  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.100  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Discov,eryManager@3f2d0468 removed from the list
08-25 16:37:36.100  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.100  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.100  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.100  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.100  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6ddb8b removed from the list
08-25 16:37:36.101  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:36.101  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dca567 added. We now have 2 listener(s)
08-25 16:37:36.103  1034  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 16:37:36.107  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:36.107  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:36.107  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:36.107  8018  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-25 16:37:36.108  8018  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 16:37:36.109  8018  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 16:37:36.109  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:36.109  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2801ff14 added. We now have 9 listener(s)
08-25 16:37:36.109  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:37:36.110  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:37:36.110  8018  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-25 16:37:36.110  8018  8077 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-25 16:37:36.113  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 16:37:36.114  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:37:36.117  8018  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:37:36.117  6658  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:37:36.119  6658  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:37:36.119  6658  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:37:36.120  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:37:36.120  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c7bdb2 added. We now have 3 listener(s)
08-25 16:37:36.120  1034  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 16:37:36.121  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:36.122  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:36.124  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 16:37:36.124  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:37:36.124  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:37:36.124  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:37:36.124  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34843103 added. We now have 10 listener(s)
08-25 16:37:36.124  6658  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:37:36.125  8018  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-25 16:37:36.125  6658  6713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:37:36.125  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:37:36.125  6658  6713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:37:36.125  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.125  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.125  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:37:36.125  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:37:36.125  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.125  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dca567 removed from the list
08-25 16:37:36.125  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.125  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2801ff14 removed from the list
08-25 16:37:36.125  6658  6713 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:37:36.125  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.127  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.127  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.128  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.128  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.128  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.128  6658  6713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:, removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2801ff14 not in the list
08-25 16:37:36.128  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.128  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.130  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:37:36.130  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:37:36.130  6658  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:37:36.130  6658  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34843103 removed from the list
08-25 16:37:36.130  6658  6713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:37:36.130  6658  6713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:37:36.130  6658  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:37:36.130  6658  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:37:36.130  6658  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c7bdb2 removed from the list
08-25 16:37:36.130  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:36.131  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:36.131  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 16:37:36.131  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 16:37:36.131  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 16:37:36.131  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:37:36.132  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 16:37:36.132  6658  6713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:37:36.140  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:36.143  6658  8134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
08-25 16:37:36.143  6658  8134 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
08-25 16:37:36.144  6658  8134 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 16:37:36.144  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.144  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:36.148  6658  8135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
08-25 16:37:36.148  6658  8135 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-25 16:37:36.148  6658  8135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 16:37:36.149  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 16:37:36.150  6658  6713 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 16:37:36.150  6658  6713 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 16:37:36.150  6658  6713 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 16:37:36.151  6658  6713 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 16:37:36.151  6658  6713 D com.test.thalitest.ThaliTestRunner: Total duration: 22926 ms
08-25 16:37:36.152  6658  6713 I jxcore-log: Total number of executed tests:  80
08-25 16:37:36.152  6658  6713 I jxcore-log: 
08-25 16:37:36.152  6658  6713 I jxcore-log: Number of passed tests:  80
08-25 16:37:36.152  6658  6713 I jxcore-log: 
08-25 16:37:36.152  6658  6713 I jxcore-log: Number of failed tests:  0
08-25 16:37:36.152  6658  6713 I jxcore-log: 
08-25 16:37:36.153  6658  6713 I jxcore-log: Number of ignored tests:  0
08-25 16:37:36.153  6658  6713 I jxcore-log: 
08-25 16:37:36.153  6658  6713 I jxcore-log: Total duration:  22926
08-25 16:37:36.153  6658  6713 I jxcore-log: 
08-25 16:37:36.154  6658  6713 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 16:37:36.154  6658  6713 I jxcore-log: 
,08-25 16:37:36.156  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:36.160  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.160  6658  6713 I jxcore-log: 
08-25 16:37:36.163  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:36.163  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:36.164  8089  8089 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 16:37:36.164  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.164  6658  6713 I jxcore-log: 
08-25 16:37:36.166  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.166  6658  6713 I jxcore-log: 
08-25 16:37:36.167  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.167  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.167  6658  6713 I jxcore-log: 
08-25 16:37:36.168  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:36.168  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.168  6658  6713 I jxcore-log: 
,08-25 16:37:36.171  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 16:37:36.171  6658  6713 I jxcore-log: 
08-25 16:37:36.172  7969  7969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 16:37:36.175  6658  6658 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 16:37:36.175  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 16:37:36.175  6658  6713 I jxcore-log: 
08-25 16:37:36.176  7969  7969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:36.177  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.177  6658  6713 I jxcore-log: 
08-25 16:37:36.178  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.178  6658  6713 I jxcore-log: 
08-25 16:37:36.179  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 16:37:36.179  6658  6713 I jxcore-log: 
08-25 16:37:36.181  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:36.181  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 16:37:36.181  6658  6713 I jxcore-log: 
,08-25 16:37:36.182  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 16:37:36.182  6658  6713 I jxcore-log: 
08-25 16:37:36.183  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.183  6658  6713 I jxcore-log: 
08-25 16:37:36.184  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.184  6658  6713 I jxcore-log: 
08-25 16:37:36.185  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.185  6658  6713 I jxcore-log: 
08-25 16:37:36.186  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.186  6658  6713 I jxcore-log: 
08-25 16:37:36.186  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:36.187  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.187  6658  6713 I jxcore-log: 
08-25 16:37:36.187  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.187  6658  6713 I jxcore-log: 
08-25 16:37:36.188  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.188  6658  6713 I jxcore-log: 
08-25 16:37:36.189  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:37:36.189  6658  6713 I jxcore-log: 
08-25 16:37:36.190  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 16:37:36.190  6658  6713 I jxcore-log: 
08-25 16:37:36.191  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 16:37:36.191  6658  6713 I jxcore-log: 
08-25 16:37:36.191  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:36.192  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.192  6658  6713 I jxcore-log: 
08-25 16:37:36.192  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:36.193  8089  8089 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 16:37:36.193  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.193  6658  6713 I jxcore-log: 
08-25 16:37:36.194  8089  8089 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 16:37:36.194  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.194  6658  6713 I jxcore-log: 
08-25 16:37:36.194  8089  8089 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 16:37:36.195  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnerg,y":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.195  6658  6713 I jxcore-log: 
08-25 16:37:36.195  6658  6713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:37:36.195  6658  6713 I jxcore-log: 
,08-25 16:37:36.201  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.203  8018  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 16:37:36.205  7969  7969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 16:37:36.205  7969  7969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 16:37:36.208  6737  6737 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 16:37:36.212  6737  6737 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 16:37:36.218  8089  8089 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 16:37:36.218  8089  8089 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 16:37:36.219  8089  8089 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-25 16:37:36.223  8089  8089 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 16:37:36.224  8089  8089 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 16:37:36.228  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-25 16:37:36.243  8089  8089 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-25 16:37:36.244  8089  8089 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 16:37:36.245  8089  8089 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 16:37:36.251  1818  8139 I CheckinService: active receiver: enabled
,08-25 16:37:36.263  1818  8139 I CheckinService: Preparing to send checkin request
08-25 16:37:36.263  1818  8139 I EventLogService: Accumulating logs since 1472135838672
08-25 16:37:36.289  8089  8089 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 16:37:36.289  8089  8089 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:36.296  8089  8089 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 16:37:36.297  8089  8089 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 16:37:36.297  8089  8089 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 16:37:36.297  8089  8089 V SoundPool: doLoad: loading sample sampleID=1
08-25 16:37:36.298  8089  8089 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 16:37:36.299  8089  8145 V SoundPool: Start decode
08-25 16:37:36.299  8089  8145 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 16:37:36.300   316  1397 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 16:37:36.300   316  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 16:37:36.300   316  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 16:37:36.300   316  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 16:37:36.300   316  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 16:37:36.300   316  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 16:37:36.300   316  1397 V MediaPlayerService: player type = 3
08-25 16:37:36.300   316  1397 V AwesomePlayer: AwesomePlayer create()
08-25 16:37:36.300   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:36.300   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:36.300   316  1397 V AwesomePlayer: setAudioSink() 
08-25 16:37:36.300   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:36.300   316  1397 V AudioCache: notify(0xb0409640, 8, 0, 0)
08-25 16:37:36.300   316  1397 V AudioCache: ignored
08-25 16:37:36.300   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:36.301   316  1397 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 16:37:36.301   316  1397 V AwesomePlayer: setDataSource_l dataSource
08-25 16:37:36.301   316  1397 V LGParserOSAL: SniffLGParser start
08-25 16:37:36.301   316  1397 V LGParserOSAL: MainType:5, SubType=0
08-25 16:37:36.301   316  1397 V LGParserOSAL: #### check Mime : application/ogg
08-25 16:37:36.301   316  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 16:37:36.301   316  1397 E MediaExtractor: Use LGExtractor :application/ogg 
,08-25 16:37:36.306  1818  8139 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-25 16:37:36.306  7497  7497 D UEI.SmartControl: QS Service created
08-25 16:37:36.306  8089  8089 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 16:37:36.309  8089  8089 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 16:37:36.310  8089  8089 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 16:37:36.321  8089  8089 V LGMDMManager: Create singleton instance
,08-25 16:37:36.339  7497  7497 I UEI.SmartControl: Service initServices...
08-25 16:37:36.340  7497  7497 D UEI.SmartControl: QS start get config
,08-25 16:37:36.345   316  1397 V LGParserOSAL: supported mime: application/ogg
08-25 16:37:36.345   316  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 16:37:36.345   316  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 16:37:36.345   316  1397 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 16:37:36.345   316  1397 V AwesomePlayer: AudioTrack Setting
08-25 16:37:36.345   316  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 16:37:36.345   316  1397 V AwesomePlayer: setAudioSource() 
08-25 16:37:36.345   316  1397 V MediaPlayerService: prepare
08-25 16:37:36.345   316  1397 V AwesomePlayer: prepareAsync_l() 
08-25 16:37:36.345   316  1397 V MediaPlayerService: wait for prepare
08-25 16:37:36.345   316  8146 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 16:37:36.345   316  8146 V AwesomePlayer: initAudioDecoder() 
08-25 16:37:36.345   316  8146 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 16:37:36.346   316  8146 V AudioSystem: isOffloadSupported()
08-25 16:37:36.346   316  8146 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 16:37:36.346   316  8146 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 16:37:36.346   316  8146 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 16:37:36.346   316  8146 V AwesomePlayer: getUseOffload() = 0 
08-25 16:37:36.346   316  8146 V OMXCodec: OMXCodec::Create
08-25 16:37:36.346   316  8146 V OMXCodec: findMatchingCodecs()
08-25 16:37:36.346   316  8146 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 16:37:36.346   316  8146 V OMXCodec: matchingCodecs.size()=1
08-25 16:37:36.346   316  8146 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 16:37:36.348   316  8146 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 16:37:36.348   316  8146 V LGCodecAdapter: LG Codec Adapter start
08-25 16:37:36.348   316  8146 V OMXCodec: OMXCodec Createtor
08-25 16:37:36.348   316  8146 V OMXCodec: setComponentRole
08-25 16:37:36.348   316  8146 V OMXCodec: configureCodec protected=0
08-25 16:37:36.348   316  8146 V LGCodecAdapter: called getLGCodecSpecificData
08-25 16:37:36.348   316  8146 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 16:37:36.348   316  8146 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 16:37:36.348   316  8146 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 16:37:36.348   316  8146 V LGCodecOSAL: Not support LGCodec
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 16:37:36.348   316  8146 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 16:37:36.348   316  8146 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 16:37:36.348   316  8146 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 16:37:36.348   316  8146 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 16:37:36.348   316  8146 V AudioSystem: isOffloadSupported()
08-25 16:37:36.348   316  8146 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 16:37:36.348   316  8146 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 16:37:36.348   316  8146 V OMXCodec: init()
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-25 16:37:36.348   316  8146 V OMXCodec: allocateBuffers
08-25 16:37:36.348   316  8146 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-25 16:37:36.348   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-25 16:37:36.348   316  8146 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 16:37:36.349   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 16:37:36.349   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-25 16:37:36.349   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-25 16:37:36.349   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-25 16:37:36.349   316  8146 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 16:37:36.349   316  8146 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 16:37:36.349   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 16:37:36.349   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 16:37:36.349   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 16:37:36.349   316  8146 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 16:37:36.349   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 16:37:36.349   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 16:37:36.349   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 16:37:36.350   316  8146 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 16:37:36.350   316  8146 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 16:37:36.350   316  8146 V AudioCache: notify(0xb0409640, 5, 0, 0)
08-25 16:37:36.350   316  8146 V AudioCache: ignored
,08-25 16:37:36.350   316  8146 V AudioCache: notify(0xb0409640, 1, 0, 0)
08-25 16:37:36.350   316  8146 V AudioCache: prepared
08-25 16:37:36.350   316  1397 V AudioCache: wait - success
08-25 16:37:36.350   316  1397 V MediaPlayerService: start
08-25 16:37:36.350   316  1397 V AwesomePlayer: play_l() 
08-25 16:37:36.350   316  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 16:37:36.350   316  1397 V AwesomePlayer: createAudioPlayer_l
08-25 16:37:36.350   316  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 16:37:36.350   316  1397 V AwesomePlayer: startAudioPlayer_l() 
08-25 16:37:36.350   316  1397 D AudioPlayer: start of Playback, useOffload 0
08-25 16:37:36.350   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 16:37:36.350   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 16:37:36.353   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,08-25 16:37:36.353   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 16:37:36.353   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 16:37:36.354   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 16:37:36.355   316  8148 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 16:37:36.355   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 16:37:36.355   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
,08-25 16:37:36.355   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-25 16:37:36.355   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-25 16:37:36.355   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cd4c0 on output port
08-25 16:37:36.355   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 16:37:36.355   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 16:37:36.357   316  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 16:37:36.359   316  1397 V AudioCache: notify(0xb0409640, 6, 0, 0)
08-25 16:37:36.359   316  1397 V AudioCache: ignored
08-25 16:37:36.359   316  1397 V MediaPlayerService: wait for playback complete
,08-25 16:37:36.361   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.361   316  8149 V AudioCache: memcpy(0xaf006000, 0xb1780000, 4096)
08-25 16:37:36.363   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.363   316  8149 V AudioCache: memcpy(0xaf007000, 0xb1780000, 4096)
08-25 16:37:36.363   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.363   316  8149 V AudioCache: memcpy(0xaf008000, 0xb1780000, 4096)
08-25 16:37:36.364   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.364   316  8149 V AudioCache: memcpy(0xaf009000, 0xb1780000, 4096)
08-25 16:37:36.364   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.364   316  8149 V AudioCache: memcpy(0xaf00a000, 0xb1780000, 4096)
08-25 16:37:36.365   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.365   316  8149 V AudioCache: memcpy(0xaf00b000, 0xb1780000, 4096)
08-25 16:37:36.366   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.366   316  8149 V AudioCache: memcpy(0xaf00c000, 0xb1780000, 4096)
,08-25 16:37:36.366   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.366   316  8149 V AudioCache: memcpy(0xaf00d000, 0xb1780000, 4096)
08-25 16:37:36.367   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.367   316  8149 V AudioCache: memcpy(0xaf00e000, 0xb1780000, 4096)
08-25 16:37:36.367   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.367   316  8149 V AudioCache: memcpy(0xaf00f000, 0xb1780000, 4096)
08-25 16:37:36.368   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.368   316  8149 V AudioCache: memcpy(0xaf010000, 0xb1780000, 4096)
08-25 16:37:36.369   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.369   316  8149 V AudioCache: memcpy(0xaf011000, 0xb1780000, 4096)
08-25 16:37:36.369   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.369   316  8149 V AudioCache: memcpy(0xaf012000, 0xb1780000, 4096)
08-25 16:37:36.370   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.370   316  8149 V AudioCache: memcpy(0xaf013000, 0xb1780000, 4096)
08-25 16:37:36.370   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.370   316  8149 V AudioCache: memcpy(0xaf014000, 0xb1780000, 4096)
08-25 16:37:36.371   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.371   316  8149 V AudioCache: memcpy(0xaf015000, 0xb1780000, 4096)
08-25 16:37:36.371   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.371   316  8149 V AudioCache: memcpy(0xaf016000, 0xb1780000, 4096)
08-25 16:37:36.372   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.372   316  8149 V AudioCache: memcpy(0xaf017000, 0xb1780000, 4096)
08-25 16:37:36.373   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.373   316  8149 V AudioCache: memcpy(0xaf018000, 0xb1780000, 4096)
08-25 16:37:36.373   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.373   316  8149 V AudioCache: memcpy(0xaf019000, 0xb1780000, 4096)
08-25 16:37:36.374   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.374   316  8149 V AudioCache: memcpy(0xaf01a000, 0xb1780000, 4096)
08-25 16:37:36.374   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.374   316  8149 V AudioCache: memcpy(0xaf01b000, 0xb1780000, 4096)
08-25 16:37:36.375   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.375   316  8149 V AudioCache: memcpy(0xaf01c000, 0xb1780000, 4096)
08-25 16:37:36.375   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.376   316  8149 V AudioCache: memcpy(0xaf01d000, 0xb1780000, 4096)
08-25 16:37:36.376   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.376   316  8149 V AudioCache: memcpy(0xaf01e000, 0xb1780000, 4096)
08-25 16:37:36.377   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.377   316  8149 V AudioCache: memcpy(0xaf01f000, 0xb1780000, 4096)
08-25 16:37:36.377   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.377   316  8149 V AudioCache: memcpy(0xaf020000, 0xb1780000, 4096)
08-25 16:37:36.378   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.378   316  8149 V AudioCache: memcpy(0xaf021000, 0xb1780000, 4096)
08-25 16:37:36.378   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.378   316  8149 V AudioCache: memcpy(0xaf022000, 0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: memcpy(0xaf023000, 0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: memcpy(0xaf024000, 0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: memcpy(0xaf025000, 0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.379   316  8149 V AudioCache: memcpy(0xaf026000, 0xb1780000, 4096)
08-25 16:37:36.380   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.380   316  8149 V AudioCache: mem,cpy(0xaf027000, 0xb1780000, 4096)
08-25 16:37:36.381   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.381   316  8149 V AudioCache: memcpy(0xaf028000, 0xb1780000, 4096)
08-25 16:37:36.381   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.381   316  8149 V AudioCache: memcpy(0xaf029000, 0xb1780000, 4096)
08-25 16:37:36.381   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.381   316  8149 V AudioCache: memcpy(0xaf02a000, 0xb1780000, 4096)
08-25 16:37:36.382   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.382   316  8149 V AudioCache: memcpy(0xaf02b000, 0xb1780000, 4096)
08-25 16:37:36.382   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.383   316  8149 V AudioCache: memcpy(0xaf02c000, 0xb1780000, 4096)
08-25 16:37:36.383   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.383   316  8149 V AudioCache: memcpy(0xaf02d000, 0xb1780000, 4096)
08-25 16:37:36.383   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.383   316  8149 V AudioCache: memcpy(0xaf02e000, 0xb1780000, 4096)
08-25 16:37:36.384  8089  8089 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 16:37:36.384   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.384   316  8149 V AudioCache: memcpy(0xaf02f000, 0xb1780000, 4096)
08-25 16:37:36.384   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.384   316  8149 V AudioCache: memcpy(0xaf030000, 0xb1780000, 4096)
08-25 16:37:36.384   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.384   316  8149 V AudioCache: memcpy(0xaf031000, 0xb1780000, 4096)
08-25 16:37:36.385  8089  8089 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 16:37:36.385   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.385   316  8149 V AudioCache: memcpy(0xaf032000, 0xb1780000, 4096)
08-25 16:37:36.385   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.385   316  8149 V AudioCache: memcpy(0xaf033000, 0xb1780000, 4096)
08-25 16:37:36.386   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.386   316  8149 V AudioCache: memcpy(0xaf034000, 0xb1780000, 4096)
08-25 16:37:36.386   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.386   316  8149 V AudioCache: memcpy(0xaf035000, 0xb1780000, 4096)
08-25 16:37:36.387   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.387   316  8149 V AudioCache: memcpy(0xaf036000, 0xb1780000, 4096)
08-25 16:37:36.387  8089  8089 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6076
08-25 16:37:36.387   316  8149 V AudioCache: write(0xb1780000, 4096)
08-25 16:37:36.387   316  8149 V AudioCache: memcpy(0xaf037000, 0xb1780000, 4096)
08-25 16:37:36.387   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 16:37:36.387   316  8149 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 16:37:36.387   316  8149 V AwesomePlayer: postAudioEOS() 
08-25 16:37:36.387   316  8149 V AudioCache: write(0xb1780000, 280)
08-25 16:37:36.387   316  8149 V AudioCache: memcpy(0xaf038000, 0xb1780000, 280)
08-25 16:37:36.389   316  8146 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 16:37:36.389   316  8146 V AwesomePlayer: onStreamDone
08-25 16:37:36.389   316  8146 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 16:37:36.389   316  8146 V AudioCache: notify(0xb0409640, 2, 0, 0)
08-25 16:37:36.389   316  8146 V AudioCache: playback complete
08-25 16:37:36.389   316  8146 V AwesomePlayer: pause_l() 
08-25 16:37:36.389   316  8146 V AudioCache: notify(0xb0409640, 7, 0, 0)
08-25 16:37:36.389   316  8146 V AudioCache: ignored
08-25 16:37:36.389   316  8146 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:36.389   316  1397 V AudioCache: wait - success
08-25 16:37:36.389   316  1397 V MediaPlayerService: return size 205080,, sampleRate=48000, channelCount = 2, format = 1
08-25 16:37:36.389   316  8146 D AudioPlayer: Pause Playback at 1068125
08-25 16:37:36.391   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:36.391   316  1397 V AudioCache: notify(0xb0409640, 8, 0, 0)
08-25 16:37:36.391   316  1397 V AudioCache: ignored
08-25 16:37:36.391   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:36.391   316  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 16:37:36.391   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 16:37:36.391   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 16:37:36.391   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 16:37:36.391   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57cd4c0 on port 1
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-25 16:37:36.391   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 16:37:36.392   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 16:37:36.392   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 16:37:36.392   316  8148 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 16:37:36.392   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 16:37:36.392   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 16:37:36.392   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 16:37:36.393   316  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 16:37:36.393   316  1397 D AudioPlayer: AudioPlayer releasing audio source
08-25 16:37:36.393   316  1397 D AudioPlayer: AudioPlayer done releasing audio source
08-25 16:37:36.393  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.395   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:36.395   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:36.395   316  1397 V AwesomePlayer: ~AwesomePlayer call
08-25 16:37:36.395   316  1397 V AwesomePlayer: reset_l() 
08-25 16:37:36.395   316  1397 V AwesomePlayer: cancelPlayerEvents
08-25 16:37:36.395  8089  8145 V SoundPool: close(31)
08-25 16:37:36.395  8089  8145 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 16:37:36.415  8137  8137 D AndroidRuntime: 
08-25 16:37:36.415  8137  8137 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 16:37:36.417  8137  8137 D AndroidRuntime: CheckJNI is OFF
08-25 16:37:36.427  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:36.429  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.432  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.434  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.437  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.440  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.444  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.446  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 16:37:36.456  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 16:37:36.515  8137  8137 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 16:37:36.527  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 16:37:36.527  1034  1092 I ActivityManager: Killing 6658:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-25 16:37:36.591  1034  1887 I WindowState: WIN DEATH: Window{23c17f2b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 16:37:36.591  1034  1457 D WifiService: Client connection lost with reason: 4
08-25 16:37:36.604  1034  1887 D InputDispatcher: Window went away: Window{23c17f2b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 16:37:36.630  7497  7497 I UEI.SmartControl: Supports setup maps: true
,08-25 16:37:36.632  7497  7497 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 16:37:36.632  7497  7497 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 16:37:36.632  7497  7497 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 16:37:36.632  7497  7497 I UEI.SmartControl: ### init IR Blaster...
08-25 16:37:36.636  7497  7497 D serial_port: Configuring serial port
08-25 16:37:36.636  7497  7497 E UEI.SmartControl: UEIBLaster setting for 616
08-25 16:37:36.636  7497  7497 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 16:37:36.636  7497  7497 I UEI.SmartControl: configuring settings for MAXQ616
08-25 16:37:36.636  7497  7497 I UEI.SmartControl: Get version...
08-25 16:37:36.652  7497  8163 D UEI.SmartControl: serial port data available: 21
,08-25 16:37:36.678  7497  7497 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 16:37:36.678  7497  7497 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 16:37:36.678  7497  7497 I UEI.SmartControl: QS saving settings...
08-25 16:37:36.679  7497  7497 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 16:37:36.696  7497  8163 D UEI.SmartControl: serial port data available: 4
,08-25 16:37:36.725  7148  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:36.725  7148  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:36.725  7148  7167 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:36.725  7148  7167 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:36.725  7148  7167 I Adreno-EGL: Remote Branch: 
08-25 16:37:36.725  7148  7167 I Adreno-EGL: Local Patches: 
08-25 16:37:36.725  7148  7167 I Adreno-EGL: Reconstruct Branch: 
08-25 16:37:36.727  7497  8166 I UEI.SmartControl: Device manager: loading config....
08-25 16:37:36.729  7497  7497 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 16:37:36.731  7497  8166 D UEI.SmartControl: ----------- loading internal config...
08-25 16:37:36.739  1034  1092 E libprocessgroup: failed to kill 1 processes for processgroup 6658
,08-25 16:37:36.740  7497  8166 E UEI.SmartControl: Loading SETTINGS...
08-25 16:37:36.742  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{38303d4 u0 com.test.thalitest/.MainActivity t6}
08-25 16:37:36.763  7497  8166 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 16:37:36.765  7497  8165 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 16:37:36.765  7497  8165 D UEI.SmartControl: -----service ready thread exits
08-25 16:37:36.777   335   349 E GBMv2   : DFP En is all cleared set to be enabled
,08-25 16:37:36.779  1034  1942 W ActivityManager: Spurious death for ProcessRecord{16b388c0 6658:com.test.thalitest/u0a118}, curProc for 6658: null
08-25 16:37:36.779  1034  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 16:37:36.783  1034  1124 I ActivityManager:   Force finishing activity ActivityRecord{38303d4 u0 com.test.thalitest/.MainActivity t6 f}
08-25 16:37:36.783  1034  1124 W ActivityManager: Duplicate finish request for ActivityRecord{38303d4 u0 com.test.thalitest/.MainActivity t6 f}
,08-25 16:37:36.794  7497  7497 E UEI.SmartControl: Services init done
08-25 16:37:36.794  7497  7497 D UEI.SmartControl: QS Service init finished
08-25 16:37:36.794  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 16:37:36.795  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 16:37:36.795  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3d74c72f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 16:37:36.796  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-25 16:37:36.796  7497  7497 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 16:37:36.796  7497  7497 D UEI.SmartControl: QS Service version code: 201091
08-25 16:37:36.796  7497  7497 D UEI.SmartControl: Service requested: Control
08-25 16:37:36.797  1943  2735 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 16:37:36.798  1943  2735 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3cc3513c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 16:37:36.799  7497  7497 D UEI.SmartControl: Internal service binding...
08-25 16:37:36.799  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 16:37:36.799  8089  8089 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 16:37:36.800  2033  2082 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-25 16:37:36.801  7497  7513 I UEI.SmartControl: ------ IControl API: 11
08-25 16:37:36.801  7497  7513 D UEI.SmartControl: File observer start...
08-25 16:37:36.801  7497  7513 E UEI.SmartControl: IR Port is disabled: false
08-25 16:37:36.801  7497  7513 D UEI.SmartControl: Starting file observer...
08-25 16:37:36.802  7497  7513 I UEI.SmartControl: Registering callback...
08-25 16:37:36.803  7497  7514 I UEI.SmartControl: ------ IControl API: 19
08-25 16:37:36.804  7497  7514 I UEI.SmartControl: Registering Services Ready callback...
08-25 16:37:36.804  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-25 16:37:36.804  7497  7514 I UEI.SmartControl: Notify client services are ready...
08-25 16:37:36.804  8089  8104 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 16:37:36.805  8089  8143 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 16:37:36.805  8089  8143 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 16:37:36.806  8089  8089 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 16:37:36.806  8089  8089 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 16:37:36.806  7497  7513 I UEI.SmartControl: ------ IControl API: 8
08-25 16:37:36.807  8089  8089 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 16:37:36.808  8089  8089 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 16:37:36.808  1034  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 16:37:36.808  8089  8089 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 16:37:36.808  1907  1907 D ActionManagerService: notifyUserLog: 1000003
08-25 16:37:36.808  8089  8089 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 16:37:36.808  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-25 16:37:36.808  3832  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 16:37:36.809  8089  8089 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 16:37:36.809  8089  8089 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 16:37:36.822  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 16:37:36.822  3832  3832 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 16:37:36.824  7582  7582 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 16:37:36.824  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 16:37:36.826  7148  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:36.826  7148  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:36.826  7148  7167 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:36.826  7148  7167 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:36.826  7148  7167 I Adreno-EGL: Remote Branch: 
08-25 16:37:36.826  7148  7167 I Adreno-EGL: Local Patches: 
08-25 16:37:36.826  7148  7167 I Adreno-EGL: Reconstruct Branch: 
08-25 16:37:36.832  8018  8018 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 16:37:36.840  8089  8089 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-25 16:37:36.848  4585  4585 I art     : Explicit concurrent mark sweep GC freed 8219(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 568us total 60.741ms
08-25 16:37:36.856  2507  2672 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 16:37:36.857  4479  4479 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 16:37:36.857  4479  4479 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 16:37:36.857  4479  4479 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 16:37:36.857  4479  4479 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 16:37:36.858  4479  4479 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 16:37:36.858  4479  4479 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 16:37:36.858  4479  4479 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 16:37:36.858  4479  4479 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 16:37:36.858  4479  4479 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:37:36.858  4479  4479 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 16:37:36.858  4479  4479 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 16:37:36.858  4479  4479 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 16:37:36.862  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-25 16:37:36.890  1034  1978 V SIM_STK : Menu title from STK is T-Mobile
,08-25 16:37:36.897  1034  1034 D administrator: Handling package changes for user 0
08-25 16:37:36.904  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-25 16:37:36.912  7148  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 16:37:36.912  7148  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 16:37:36.912  7148  7167 I Adreno-EGL: Build Date: 12/12/14 금
08-25 16:37:36.912  7148  7167 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 16:37:36.912  7148  7167 I Adreno-EGL: Remote Branch: 
08-25 16:37:36.912  7148  7167 I Adreno-EGL: Local Patches: 
08-25 16:37:36.912  7148  7167 I Adreno-EGL: Reconstruct Branch: 
08-25 16:37:36.939  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-25 16:37:36.944  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 16:37:36.946  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-25 16:37:36.947  2208  2208 I ConfigService: onCreate
08-25 16:37:36.947  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 16:37:36.947  1603  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 16:37:36.947  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:36.950  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-25 16:37:36.952  1603  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 16:37:36.952  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:36.956  1603  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 16:37:36.956  1603  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 16:37:36.956  1603  1663 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 16:37:36.957  1603  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 16:37:36.962  1034  1906 V SIM_STK : Menu title from STK is T-Mobile
08-25 16:37:36.962  1034  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-25 16:37:36.964  8089  8089 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 16:37:36.967  1603  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 16:37:36.967  1603  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 16:37:36.967  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-25 16:37:36.969  2208  2208 I ConfigService: onBind returning update interface
08-25 16:37:36.973  1907  1907 D ActionManagerService: notifyUserLog: 1000004
08-25 16:37:36.974  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 16:37:36.974  3832  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 16:37:36.974  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-25 16:37:36.975  1870  1870 D SplitUIService: removed split : 
08-25 16:37:36.975  3832  3847 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 16:37:36.976  1603  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 16:37:36.976  1603  1663 D KeyguardModel: createShortcutInfo...
,08-25 16:37:36.981  1603  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 16:37:36.982  1603  1663 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:36.983  1603  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 16:37:36.983  1603  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 16:37:36.994  1603  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 16:37:36.994  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:36.994  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 16:37:36.994  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-25 16:37:36.995  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 16:37:36.995  2208  2208 I ConfigService: onBind returning config service
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , display: false
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , animation: false }
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , display: false
08-25 16:37:36.997  2033  2033 I GBoardWebViewUtils: , animation: false }
08-25 16:37:36.998  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 16:37:36.998  2033  2033 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 16:37:36.998  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-25 16:37:36.998  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 16:37:36.998  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 16:37:36.998  2033  2033 I GBoardWebViewUtils: , display: false
08-25 16:37:36.998  2033  2033 I GBoardWebViewUtils: , animation: false }
08-25 16:37:36.998  1603  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 16:37:36.998  1603  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 16:37:36.998  1603  1663 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 16:37:36.998  1603  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.split,window.jar' does not exist or contains no resources.
08-25 16:37:37.001  1603  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 16:37:37.001  1603  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-25 16:37:37.003  1603  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 16:37:37.003  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:37.014  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-25 16:37:37.017  1034  2014 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 16:37:37.018  7582  7582 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 16:37:37.019  2033  8170 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 16:37:37.021  2208  2208 I ConfigService: onDestroy
08-25 16:37:37.025  1818  8172 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 16:37:37.030  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-25 16:37:37.030  1870  1870 I SplitUIService: split app #11
08-25 16:37:37.030  1603  1603 D KeyguardModel: handleShortcutListChanged...
,08-25 16:37:37.030  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 16:37:37.036  1603  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 16:37:37.036  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:37.039  1603  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 16:37:37.039  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:37.040  1603  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 16:37:37.040  1603  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 16:37:37.042  1603  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 16:37:37.042  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:37.043  1603  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 16:37:37.043  1603  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 16:37:37.044  1603  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 16:37:37.044  1603  1663 D KeyguardModel: createShortcutInfo...
08-25 16:37:37.045  1034  1960 V SIM_STK : Menu title from STK is T-Mobile
08-25 16:37:37.048  1603  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 16:37:37.048  1603  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 16:37:37.051  1603  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 16:37:37.051  1603  1663 D KeyguardModel: createShortcutInfo...
,08-25 16:37:37.079  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 16:37:37.081  5929  8177 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-25 16:37:37.082  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 16:37:37.087   329   419 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-25 16:37:37.087  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 16:37:37.087  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 16:37:37.088  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 16:37:37.088  3192  8180 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-25 16:37:37.090  1034  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 16:37:37.091  1818  8179 I PeopleContactsSync: CP2 sync disabled
,08-25 16:37:37.103  1818  4736 I Icing   : doRemovePackageData com.test.thalitest
,08-25 16:37:37.121  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-25 16:37:37.121  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 16:37:37.142  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-25 16:37:37.146  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 16:37:37.148  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 16:37:37.149  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 16:37:37.150  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 16:37:37.151  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 16:37:37.166  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 16:37:37.167  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 16:37:37.167  2033  2200 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 16:37:37.167  2033  2200 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-25 16:37:37.175  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{74fef27 u0 com.lge.launcher2/.Launcher t5} time:224952
08-25 16:37:37.183  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-25 16:37:37.183  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-25 16:37:37.183  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 16:37:37.192  2208  2355 I art     : Explicit concurrent mark sweep GC freed 6995(403KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 687us total 57.762ms
08-25 16:37:37.193  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 16:37:37.194  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
08-25 16:37:37.194  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-25 16:37:37.196  2583  2583 D [Concierge]Service: Update widget ID : 11
08-25 16:37:37.196  1818  8178 W GmsApplication: Using Auth Proxy for data requests.
,08-25 16:37:37.198  2033  2033 D [Concierge]WidgetView: change position of spinner
08-25 16:37:37.200  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1472135857200
08-25 16:37:37.200  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
08-25 16:37:37.203   311  8186 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 16:37:37.203   311  8186 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-25 16:37:37.204  1818  8178 W GmsApplication: Using Auth Proxy for data requests.
08-25 16:37:37.213  1034  1124 I art     : Explicit concurrent mark sweep GC freed 86082(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 5.160ms total 411.025ms
08-25 16:37:37.214  6934  6934 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-25 16:37:37.227  2360  8187 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 16:37:37.242   311  8186 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-25 16:37:37.244  1034  1576 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8188 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-25 16:37:37.250  8137  8137 D AndroidRuntime: Shutting down VM
,08-25 16:37:37.277  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 933725351
08-25 16:37:37.277  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-25 16:37:37.277  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 16:37:37.280  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@a6f1828
,08-25 16:37:37.280  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-25 16:37:37.281  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 16:37:37.281  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 16:37:37.286  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 16:37:37.287  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 16:37:37.287  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 16:37:37.296  8188  8188 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 16:37:37.296  8188  8188 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 16:37:37.297  8188  8188 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 16:37:37.297  8188  8188 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 16:37:37.309  1034  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8205 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 16:37:37.314  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472135660538, New one : 1472135857200
08-25 16:37:37.314  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-25 16:37:37.314  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 16:37:37.316  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 16:37:37.318  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 16:37:37.319  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 16:37:37.320  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-25 16:37:37.321  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 16:37:37.322  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-25 16:37:37.325  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 16:37:37.325  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 16:37:37.371  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 16:37:37.376  1034  1960 I ActivityManager: Killing 7613:com.google.android.talk/u0a72 (adj 15): empty #17
08-25 16:37:37.379  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 16:37:37.379  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-25 16:37:37.381  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 16:37:37.394  1818  8139 I CheckinTask: Sending checkin request (8011 bytes)
,08-25 16:37:37.401  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d05edb0 time:225178
08-25 16:37:37.417  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 16:37:37.421  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 16:37:37.454  1034  2014 W libprocessgroup: failed to open /acct/uid_10072/pid_7613/cgroup.procs: No such file or directory
08-25 16:37:37.455  8188  8188 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 16:37:37.458  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 16:37:37.463  8188  8188 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-25 16:37:37.482  8188  8188 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 16:37:37.501  8188  8188 D LgDataFeature: LgDataFeature() Constructor: none
08-25 16:37:37.501  8188  8188 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 16:37:37.521  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-25 16:37:37.554  8188  8188 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-25 16:37:37.562  2033  2957 I GBoardtInterface: onReloaded()
,08-25 16:37:37.564  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-25 16:37:37.565  3832  3847 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 16:37:37.565  1034  2014 I ActivityManager: Killing 7709:com.android.vending/u0a44 (adj 15): empty #17
08-25 16:37:37.567  1818  8139 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-25 16:37:37.585  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 16:37:37.585  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-25 16:37:37.586  1034  1960 W libprocessgroup: failed to open /acct/uid_10044/pid_7709/cgroup.procs: No such file or directory
08-25 16:37:37.586  1818  3978 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
08-25 16:37:37.590  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-25 16:37:37.590  1818  8139 I CheckinService: active receiver: disabled
08-25 16:37:37.592  1034  1647 F PackageManager: Unable to backup user packages state file, current changes will be lost at reboot
08-25 16:37:37.592  3832  4467 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-25 16:37:37.597  8018  8,018 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 16:37:37.597  8018  8018 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: Can't write: system_server_wtf
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop19.tmp: open failed: EROFS (Read-only file system)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12444)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12257)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:12229)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:135)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 16:37:37.598  1034  1092 E DropBoxManagerService: 	... 13 more
,08-25 16:37:37.600  8018  8018 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 16:37:37.602  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-25 16:37:37.603  7376  7376 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-25 16:37:37.603  3832  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 16:37:37.603  3832  4471 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 16:37:37.607  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-25 16:37:37.607  6737  6737 D PackageIntentReceiver: Not supported Hotkey customization function 
08-25 16:37:37.608  3832  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 16:37:37.608  3832  4471 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 16:37:37.608  3832  4471 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-25 16:37:37.608  3832  4471 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
,08-25 16:37:37.611  3832  3847 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 16:37:37.613  6737  6737 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-25 16:37:37.613  6737  6737 D HideNavigationAppsReceiver: replacing : false
08-25 16:37:37.614  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-25 16:37:37.614  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-25 16:37:37.615  6737  6737 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-25 16:37:37.615  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-25 16:37:37.615  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 16:37:37.617  6737  6737 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-25 16:37:37.617  6737  6737 D ButtonCombinationReceiver: replacing : false
08-25 16:37:37.617  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-25 16:37:37.617  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 16:37:37.645  1034  1576 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8231 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 16:37:37.648  4479  4524 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: Error inserting f004=13 f005=8231 f002=1472135857647 f003=com.android.vending f006=10044
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-25 16:37:37.649  4479  4524 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)

```
