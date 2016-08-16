#### Test 814185775e43c41_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 12:26:00.102  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-16 12:26:00.112  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 12:26:00.112  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-16 12:26:00.115  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-16 12:26:00.117  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 12:26:05.012  6788  6788 D AndroidRuntime: 
08-16 12:26:05.012  6788  6788 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 12:26:05.016  6788  6788 D AndroidRuntime: CheckJNI is OFF
08-16 12:26:05.220  6788  6788 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 12:26:05.231  1042  1060 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 12:26:05.246  1925  3996 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 12:26:05.251  1042  1060 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 12:26:05.253  1042  1060 D ActivityManager: setTaskToReturnTo : TaskRecord{89331f6 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 12:26:05.253  1042  1060 D ActivityManager: setTaskToReturnTo : TaskRecord{89331f6 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 12:26:05.254  1042  1060 D WindowStateEx: AppWindowTokenEx init.. 
08-16 12:26:05.255   334   345 E GBMv2   : DFP En is all cleared set to be enabled
08-16 12:26:05.283  1042  1060 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6803 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 12:26:05.286  6788  6788 D AndroidRuntime: Shutting down VM
08-16 12:26:05.339  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 12:26:05.339  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1aa5d637 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 12:26:05.351  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 12:26:05.352  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{56b27a4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 12:26:05.413  6803  6803 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-16 12:26:05.503  6803  6803 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 12:26:05.510  6803  6803 I LibraryLoader: Loading: webviewchromium
08-16 12:26:05.512  6803  6803 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9519-9522)
08-16 12:26:05.513  6803  6803 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:26:05.525  6803  6803 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ef5abfd}
08-16 12:26:05.526  6803  6803 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:26:05.526  6803  6803 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 12:26:05.534  6803  6803 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 12:26:05.535  6803  6803 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:26:05.547  6803  6803 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 12:26:05.548  6803  6803 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 12:26:05.548  6803  6803 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-16 12:26:05.561   318  2131 V AudioPolicyService: registerClient() client 0xb557c3c0, uid 10118
,08-16 12:26:05.565  1042  1119 D BluetoothManagerService: Message: 20
,08-16 12:26:05.565  1042  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10ad4ed0:true
08-16 12:26:05.578  6803  6803 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:26:05.578  6803  6803 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:26:05.578  6803  6803 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:26:05.578  6803  6803 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:26:05.578  6803  6803 I Adreno-EGL: Remote Branch: 
08-16 12:26:05.578  6803  6803 I Adreno-EGL: Local Patches: 
08-16 12:26:05.578  6803  6803 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:26:05.673  6803  6848 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 12:26:05.677  6803  6803 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-16 12:26:05.699  6803  6803 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:26:05.705  6803  6803 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 12:26:05.709  6803  6803 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 12:26:05.713  6803  6803 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 12:26:05.713  6803  6803 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-16 12:26:05.729  6803  6803 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 12:26:05.736  6803  6803 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 12:26:05.736  6803  6803 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:26:05.771  6803  6865 D OpenGLRenderer: Render dirty regions requested: true
08-16 12:26:05.771  6803  6865 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 12:26:05.776  6803  6865 D OpenGLRenderer: Enabling debug mode 0
08-16 12:26:05.785  6803  6803 D Atlas   : Validating map...
,08-16 12:26:05.788  1042  1971 D SplitWindow: check instance of lgWin Window{4c8c88a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 12:26:05.836  6803  6863 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:05.836  6803  6863 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:05.897  1042  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +559ms (total +641ms)
08-16 12:26:05.898  6803  6803 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24ffe6f0 time:179907
08-16 12:26:05.899  1042  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a2969f7 u0 com.test.thalitest/.MainActivity t6} time:179908
,08-16 12:26:06.064  6803  6803 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 12:26:06.239  6803  6879 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,08-16 12:26:06.257  6803  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 12:26:06.257  6803  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 12:26:06.257  6803  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 12:26:06.257  6803  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 12:26:06.257  6803  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 12:26:06.258  6803  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bc4f8b4 added. We now have 1 listener(s)
,08-16 12:26:06.268  1042  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:06.274  6803  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-16 12:26:06.281  6803  6879 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:06.282  6803  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:06.283  6803  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 12:26:06.290  6803  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd02f23 added. We now have 1 listener(s)
08-16 12:26:06.291  6803  6879 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:26:06.295  1042  1526 D WifiService: New client listening to asynchronous messages
08-16 12:26:06.299  6803  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:26:06.300  6803  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 12:26:06.300  6803  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 12:26:06.300  6803  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 12:26:06.300  6803  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 12:26:06.306  6803  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:26:06.306  1042  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:06.307  6803  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 12:26:06.317  6803  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:06.317  6803  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:06.317  6803  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 12:26:06.317  6803  6879 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:26:06.320  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:06.322  6803  6879 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 12:26:06.322  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:06.367  6803  6863 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 12:26:06.367  6803  6863 I chromium: 
,08-16 12:26:06.453  6803  6803 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 12:26:06.542  6803  6803 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 12:26:06.542  6803  6803 I chromium: 
,08-16 12:26:06.795   334   347 E GBMv2   : DFP En is all cleared set to be enabled
08-16 12:26:06.795   334   347 E GBMv2   : Set value is all cleared set the max
08-16 12:26:06.795   334   347 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 12:26:07.177  6803  6882 W jxcore-log: Initializing JXcore engine
08-16 12:26:07.177  6803  6882 W jxcore-log: JXcore engine is ready
,08-16 12:26:07.204  6882  6882 W Thread-812: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7574]" dev="sockfs" ino=7574 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 12:26:07.204  6882  6882 W Thread-812: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-16 12:26:07.204  6882  6882 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8772]" dev="sockfs" ino=8772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 12:26:07.204  6882  6882 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-16 12:26:07.204  6882  6882 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33556]" dev="sockfs" ino=33556 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 12:26:07.227  6803  6882 W jxcore-log: Starting JXcore engine
08-16 12:26:07.302  6803  6882 W jxcore-log: Platform android
08-16 12:26:07.302  6803  6882 W jxcore-log: 
08-16 12:26:07.302  6803  6882 W jxcore-log: Process ARCH arm
08-16 12:26:07.302  6803  6882 W jxcore-log: 
,08-16 12:26:07.479  6803  6882 I jxcore-log: JXcore Cordova bridge is ready!
08-16 12:26:07.479  6803  6882 I jxcore-log: 
08-16 12:26:07.480  6803  6882 W jxcore-log: JXcore engine is started
,08-16 12:26:07.483  6803  6879 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 12:26:07.486  6803  6803 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-16 12:26:14.342  1586  1586 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-16 12:26:14.342  1586  1586 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-16 12:26:14.352  1586  1586 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-16 12:26:14.352  1586  1586 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-16 12:26:14.353  4155  4307 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 12:26:14.353  1925  2060 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-16 12:26:14.353  1925  2060 D LEDHandler: Battery Level Remaining: 100%
08-16 12:26:14.353  1925  2060 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-16 12:26:14.354  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:14.354  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:14.354  1042  1526 D WifiController: battery changed pluggedType: 2
08-16 12:26:14.354  1586  1586 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-16 12:26:14.355  5511  5511 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 12:26:17.255  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 12:26:17.255  6803  6882 I jxcore-log: 
,08-16 12:26:17.257  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 12:26:17.257  6803  6882 I jxcore-log: 
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:17.261  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:17.263  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:17.265  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 12:26:17.265  6803  6882 I jxcore-log: 
08-16 12:26:17.267  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 12:26:17.267  6803  6882 I jxcore-log: 
08-16 12:26:17.591  6803  6882 D ExecuteNativeTests: Running unit tests
,08-16 12:26:17.672  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:26:17.672  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a added. We now have 2 listener(s),
08-16 12:26:17.673  1042  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:26:17.675  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 12:26:17.675  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 12:26:17.675  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:17.675  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:17.675  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb added. We now have 2 listener(s)
08-16 12:26:17.675  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:26:17.676  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:26:17.678  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:17.681  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:26:17.681  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-16 12:26:17.682  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:17.683  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:17.684  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 12:26:17.686  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 12:26:17.688  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:26:17.688  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:26:17.690  6803  6882 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 12:26:17.691  6803  6882 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 12:26:17.691  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:26:17.691  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:26:17.691  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:26:17.692  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.693  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.693  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.693  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.693  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.693  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:17.693  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:17.694  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a removed from the list
,08-16 12:26:17.694  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.694  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb removed from the list
08-16 12:26:17.694  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.694  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.694  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.694  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.695  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.695  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.695  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.695  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.697  6803  6882 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
08-16 12:26:17.697  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.697  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:26:17.697  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.698  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.698  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.698  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.698  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.698  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.698  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.698  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 12:26:17.698  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.698  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.698  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.698  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.699  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:26:17.699  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.699  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.699  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
,08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 12:26:17.705  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 12:26:17.706  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 12:26:17.706  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 12:26:17.706  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 12:26:17.706  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 12:26:17.706  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.706  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.706  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.706  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.706  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.706  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.706  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.706  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.706  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.706  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.706  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.706  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.706  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.706  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.708  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.708  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.708  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.708  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.708  6803  6882 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:26:17.710  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:17.712  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:17.713  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:17.713  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:17.714  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 12:26:17.715  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:17.715  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:17.715  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:26:17.715  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:26:17.715  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:17.715  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:26:17.718  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:26:17.718  1042  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:17.721  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:26:17.725  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:26:17.726  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
08-16 12:26:17.727  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:26:17.727  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:17.729  6803  6882 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:26:17.729  6803  6882 I io.jxcore.node.ConnectionHelper: start: OK
08-16 12:26:17.731  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.731  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.731  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.731  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.731  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.731  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:17.731  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.731  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.731  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.731  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.731  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:17.732  6803  6882 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:26:17.733  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:17.735  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:17.736  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:17.736  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:26:17.737  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 12:26:17.738  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:17.738  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:17.738  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:26:17.738  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:26:17.738  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:17.738  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
08-16 12:26:17.741  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:26:17.741  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:17.742  6803  6882 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:26:17.742  6803  6882 I io.jxcore.node.ConnectionHelper: start: OK
08-16 12:26:17.743  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:26:17.743  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.743  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.743  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.743  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.743  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:17.743  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.743  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.744  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.744  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:26:17.744  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.744  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.744  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.744  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.744  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.746  6803  6882 D BluetoothLeScanner: could not find callback wrapper,
08-16 12:26:17.746  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.746  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 12:26:17.746  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.746  6803  6882 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:26:17.747  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:17.749  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:17.750  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:26:17.750  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:17.751  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:17.752  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:17.752  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:17.753  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-16 12:26:17.753  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:26:17.753  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:17.753  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:26:17.755  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 12:26:17.755  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:17.756  6803  6882 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:26:17.756  6803  6882 I io.jxcore.node.ConnectionHelper: start: OK
08-16 12:26:17.756  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.756  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:26:17.756  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.757  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.757  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.757  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.757  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:26:17.757  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.757  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:17.758  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list,
08-16 12:26:17.758  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.758  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.758  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.758  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:17.758  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.758  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.758  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:26:17.759  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 12:26:17.759  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.759  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 12:26:17.759  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.759  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.759  6803  6882 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 12:26:17.760  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:26:17.760  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.760  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.760  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.760  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.760  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.760  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.760  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.760  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.760  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:26:17.760  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 12:26:17.760  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.760  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.760  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.761  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:26:17.761  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.761  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.761  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.761  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:26:17.761  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.762  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 12:26:17.762  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.762  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.762  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 12:26:17.762  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.762  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.763  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.763  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
,08-16 12:26:17.763  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.763  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.763  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.763  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.763  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 12:26:17.763  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.763  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.763  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.763  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:26:17.764  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.764  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.764  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.764  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.764  6803  6882 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 12:26:17.764  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.764  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.764  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.765  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.765  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.765  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.765  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.765  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.765  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.765  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:26:17.765  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.765  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.765  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.765  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.766  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:26:17.766  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.766  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.766  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.766  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 12:26:17.766  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.767  6803  6882 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 12:26:17.767  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.767  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:26:17.767  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.768  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.768  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.768  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.768  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
,08-16 12:26:17.768  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.768  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.768  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.768  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.768  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.768  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.768  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.769  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.769  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:26:17.769  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.769  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.769  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.769  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.769  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 12:26:17.769  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:26:17.769  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:26:17.770  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:26:17.770  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 12:26:17.770  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:26:17.770  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.770  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.770  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.770  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.770  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.770  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.770  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
,08-16 12:26:17.770  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 12:26:17.770  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.770  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.770  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.770  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.770  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.770  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.771  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-16 12:26:17.771  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.772  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.772  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.772  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.772  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
,08-16 12:26:17.772  6803  6882 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:26:17.772  6803  6882 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 12:26:17.772  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 12:26:17.774  6803  6882 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:26:17.774  6803  6882 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
,08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 12:26:17.774  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 12:26:17.775  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 12:26:17.775  6803  6882 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 12:26:17.775  6803  6882 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:26:17.775  6803  6882 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 12:26:17.775  6803  6882 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:26:17.775  6803  6882 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:26:17.775  6803  6882 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 12:26:17.775  6803  6882 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:26:17.775  6803  6882 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:26:17.775  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 12:26:17.777  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 12:26:17.778  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 12:26:17.778  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 12:26:17.778  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 12:26:17.778  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 12:26:17.779  6803  6882 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 12:26:17.779  6803  6882 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:26:17.779  6803  6882 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 12:26:17.779  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.779  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.779  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.779  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.779  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.779  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.780  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 12:26:17.780  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.780  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.780  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.780  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.780  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.780  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.780  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.780  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.781  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.781  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.781  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.781  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.781  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.781  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.782  6803  6882 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 12:26:17.782  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.782  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.782  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.783  6803  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
08-16 12:26:17.783  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.783  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.783  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.784  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.784  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.784  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.784  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.784  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.784  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.784  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.784  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.784  6803  6888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
08-16 12:26:17.785  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.785  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.785  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.785  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.785  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.785  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.786  6803  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
08-16 12:26:17.787  6803  6882 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 12:26:17.788  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.788  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.788  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:26:17.788  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:26:17.788  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.788  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.788  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.788  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.788  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.788  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.788  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.788  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.788  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.788  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.789  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.789  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.789  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.789  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.789  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.789  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.790  6803  6882 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 12:26:17.790  6803  6882 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 12:26:17.790  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:26:17.791  6803  6882 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 12:26:17.791  6803  6882 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 12:26:17.791  6803  6882 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 12:26:17.791  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:26:17.791  6803  6882 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 12:26:17.791  6803  6882 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 12:26:17.791  6803  6882 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 12:26:17.791  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:26:17.791  6803  6882 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 12:26:17.791  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.791  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.791  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.792  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.792  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.792  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.792  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.792  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.792  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.792  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.792  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.792  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.792  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.792  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.793  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:26:17.793  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.793  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.793  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.793  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.793  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.793  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.793  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.793  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.793  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.793  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.793  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.794  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.794  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.794  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:17.794  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.794  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.794  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.794  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.794  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.794  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.794  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:26:17.794  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.794  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.794  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.794  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.794  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.795  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
,08-16 12:26:17.795  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.795  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.795  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.795  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.795  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.795  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.795  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:17.795  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.795  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.796  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.796  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:17.796  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.796  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.797  6803  6882 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 12:26:17.797  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:17.797  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 12:26:17.798  6803  6882 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 12:26:17.798  6803  6882 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 12:26:17.799  6803  6803 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 12:26:17.799  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-16 12:26:17.799  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:26:17.800  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.800  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 12:26:17.800  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 12:26:17.800  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 12:26:17.800  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:17.800  6803  6882 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 12:26:17.800  6803  6803 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 12:26:17.800  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.800  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.801  6803  6889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 12:26:17.801  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:26:17.801  6803  6889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 12:26:17.801  6803  6882 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:26:17.801  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:26:17.803  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:26:17.803  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:17.803  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 12:26:17.803  6803  6882 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:26:17.803  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.804  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.804  6803  6882 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:26:17.804  6803  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:26:17.804  6803  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 12:26:17.805  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
,08-16 12:26:17.805  6803  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:26:17.805  6803  6803 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:26:17.805  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.805  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.805  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.805  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:26:17.805  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.805  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.805  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.805  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.805  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.805  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.805  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.805  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.805  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.805  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.806  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.806  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.806  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.806  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
,08-16 12:26:17.807  6803  6882 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 12:26:17.807  6803  6882 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 12:26:17.807  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:26:17.807  6803  6882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:26:17.807  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.807  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:26:17.807  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.807  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.808  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.808  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.808  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.808  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:26:17.808  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.808  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.808  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.808  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.808  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.808  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.808  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:26:17.808  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.808  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.808  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.809  1042  1692 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:17.810  1042  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:26:17.811  1042  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:17.811  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.811  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.811  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.811  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.811  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.811  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.811  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.811  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.811  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.811  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.812  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:26:17.812  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.812  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.812  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.812  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.812  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.812  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:26:17.812  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.813  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:17.813  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:17.813  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:17.813  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:17.813  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.813  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:17.813  6803  6882 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4155f4a not in the list
08-16 12:26:17.813  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.813  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.813  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:17.813  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.813  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:17.813  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:17.813  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:17.814  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:17.814  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:17.814  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:17.814  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e4ebb not in the list
08-16 12:26:17.815  6803  6882 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 12:26:17.815  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:26:17.815  6803  6882 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 12:26:17.815  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:26:17.815  6803  6882 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-16 12:26:17.815  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:26:17.817  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 12:26:17.817  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 12:26:17.817  6803  6882 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-16 12:26:17.817  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:26:17.817  6803  6882 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 12:26:17.817  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:26:17.817  6803  6882 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 12:26:17.817  6803  6882 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-16 12:26:17.818  6803  6882 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 12:26:17.818  6803  6882 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 12:26:17.818  6803  6882 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 12:26:17.818  6803  6882 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 12:26:17.818  6803  6882 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 12:26:17.819  6803  6882 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 12:26:17.819  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:26:17.819  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b5fa1f0 added. We now have 2 listener(s)
08-16 12:26:17.819  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:17.821  6803  6882 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 12:26:17.822  1042  1971 D WifiServiceImplEx: setWifiEnabled: true pid=6803, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:26:17.822  1042  1971 D WifiService: setWifiEnabled: true pid=6803, uid=10118
08-16 12:26:17.822  1042  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:26:17.823  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:17.823  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aaf4369 added. We now have 3 listener(s)
08-16 12:26:17.823  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:17.826  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:17.826  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f5fe1ee added. We now have 4 listener(s)
08-16 12:26:17.826  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:17.827  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:17.827  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ebde68f added. We now have 5 listener(s)
08-16 12:26:17.827  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:17.828  1042  1971 D WifiServiceImplEx: setWifiEnabled: false pid=6803, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:26:17.828  1042  1971 D WifiService: setWifiEnabled: false pid=6803, uid=10118
08-16 12:26:17.828  1042  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:26:17.847  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:26:17.847  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:26:17.847  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-16 12:26:17.848  1042  1521 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:17.848  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:17.848  1042  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:17.849  1042  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:17.849  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:17.849  1042  1693 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:17.849  1042  1521 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 12:26:17.849  1042  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:26:17.849  1042  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:26:17.850  1042  1693 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2f658fd5 mBinding = false
08-16 12:26:17.850  1042  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:26:17.850  1042  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:26:17.859  1042  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:26:17.859  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:26:17.859  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:17.859  2722  2722 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:26:17.859  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:26:17.859  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:26:17.860  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:17.860  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:26:17.860  1042  2852 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:17.860   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:26:17.869  1042  1119 D BluetoothManagerService: Message: 2
08-16 12:26:17.871  1042  1119 D BluetoothManagerService: Sending off request.
08-16 12:26:17.872  4155  4180 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 12:26:17.872  4155  4244 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 12:26:17.872  4155  4244 D BluetoothAdapterProperties: Setting state to 13
08-16 12:26:17.872  4155  4244 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 12:26:17.873  4155  4244 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 12:26:17.873  4155  4244 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 12:26:17.877  4155  4247 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:26:17.877  4155  4244 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 12:26:17.878  4155  4244 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 12:26:17.879  4155  4582 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 12:26:17.880  4155  4621 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:17.881  4155  4623 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:17.881  4155  4625 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:17.881  4155  4585 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:17.882  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 12:26:17.882  4155  4391 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 12:26:17.883  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:17.883  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0017 not found for d,eregistration
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 12:26:17.884  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 12:26:17.884  4155  4391 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 12:26:17.895  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 12:26:17.895  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 12:26:17.901  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:26:17.908  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:17.908  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 12:26:17.909  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 12:26:17.911  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:26:17.911  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-16 12:26:17.913  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:17.913  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:26:17.915  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:17.915  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:17.919  1042  1558 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 12:26:17.920  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:17.920  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:17.920  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 12:26:17.920  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:17.920  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-16 12:26:17.935  1042  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 12:26:17.935   314  6904 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 12:26:17.935  1042  1527 D DSQN    : disableDataServiceNotify
08-16 12:26:17.935  1042  1527 D DSQN    : stop dsqn bin
08-16 12:26:17.935  1042  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 12:26:17.936  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 12:26:17.942  1042  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 12:26:17.943  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:17.943  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:17.943  1042  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:17.943  1042  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 12:26:17.944  1586  2083 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 12:26:17.944  1042  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 12:26:17.944  1042  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 12:26:17.944  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:17.944  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:17.944  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:26:17.945  1042  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-16 12:26:17.949  1042  1108 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6906 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 12:26:17.950  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:17.952  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-16 12:26:17.953  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:17.953  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:17.953  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 12:26:17.954  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:17.954  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:17.954  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:26:17.955  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:17.957  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:26:17.959  4155  4155 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:17.959  4155  4155 D BluetoothMapService: STATE_TURNING_OFF
08-16 12:26:17.959  4155  4155 V BluetoothMapService: Handler(): got msg=4
08-16 12:26:17.960  4155  4155 D BluetoothMapService: MAP Service closeService in
08-16 12:26:17.960  4155  4155 D BluetoothMapMasInstance: MAP Service shutdown
08-16 12:26:17.960  4155  4155 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:26:17.960  4155  4155 V BluetoothMapService: MAP Service closeService out
08-16 12:26:17.961  4155  4155 V BtOppService: Receiver DISABLED_ACTION 
08-16 12:26:17.961  4155  4155 I BtOppRfcommListener: stopping Accept Thread
08-16 12:26:17.961  4155  4155 V BtOppRfcommListener: close mBtServerSocket
08-16 12:26:17.961  4155  4155 V BtOppRfcommListener: waiting for thread to terminate
08-16 12:26:17.962  4155  4621 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 12:26:17.962  4155  4155 V BtOppRfcommListener: done waiting for thread to terminate
08-16 12:26:17.976  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 12:26:18.003  1042  1108 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6923 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 12:26:18.003  1042  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:18.004  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 12:26:18.005  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:18.005  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:18.006  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:18.006  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:18.006  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:18.008  1042  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:26:18.009  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:26:18.009  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:26:18.009  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:26:18.009  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:26:18.011  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-16 12:26:18.012  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:18.012  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:18.012  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:26:18.015  1042  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:18.016  1042  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 12:26:18.016  1042  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:18.016  1042  1521 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 12:26:18.017  1042  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:26:18.017  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:18.017  1042  1520 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@d995ce3
08-16 12:26:18.018  4155  4155 V BtOppService: onDestroy
08-16 12:26:18.019  1042  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.019  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.019  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.020  1042  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.021  1042  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:26:18.021  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.021  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:26:18.021  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.021  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:26:18.021  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:26:18.021  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:26:18.022  1042  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.023  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.023  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:18.023  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:18.023  1042  1527 D NetworkManagementService: Removing idletimer
08-16 12:26:18.023  1042  1521 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:18.023  1042  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:18.023  1042  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:18.024  1042  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 12:26:18.025  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 12:26:18.025  1042  1042 D RttService: SCAN_AVAILABLE : 1
08-16 12:26:18.025  1042  1520 D LGWifiP2pService: P2pDisablingState
,08-16 12:26:18.025  1042  1520 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:18.025  1042  1520 D LGWifiP2pService: p2p socket connection lost
08-16 12:26:18.025  1042  1520 D LGWifiP2pService: P2pDisabledState
08-16 12:26:18.025  1042  1540 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:18.026  1042  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 12:26:18.026  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:26:18.026  2722  2722 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:26:18.026  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:26:18.026  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:18.026  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:18.027  1042  1539 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:18.027  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:26:18.027  4155  4155 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 12:26:18.028  1042  1520 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:18.028  1042  1520 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:18.028  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
,08-16 12:26:18.029   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:26:18.030  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:18.031  1042  1521 D WifiNative-p2p0: doBoolean: TERMINATE
,08-16 12:26:18.034  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:26:18.034  1925  1925 D WfdsService: WifiP2pState is changed : false
08-16 12:26:18.034  1925  2258 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 12:26:18.034  1925  2258 D WfdsService: Set the WFDS Monitor: false
08-16 12:26:18.035  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-16 12:26:18.035  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:18.035  1925  2258 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:26:18.035  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:18.035  1925  2258 D WfdsService: STATE : WfdsDisabledState - enter
08-16 12:26:18.035  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:26:18.035  1042  1521 D WifiNative-p2p0: TERMINATE: returned true
08-16 12:26:18.035  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:18.035  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:18.035  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:18.035  1925  2760 D CtrlSupplicant: Received on exit socket, terminate
08-16 12:26:18.035  1925  2760 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 12:26:18.035  1925  2760 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 12:26:18.035  1925  2760 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 12:26:18.036  1925  2258 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 12:26:18.036  1925  2259 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 12:26:18.043  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 12:26:18.044  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 12:26:18.044  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:18.044  1042  1042 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-16 12:26:18.048  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:18.048  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:18.049  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:18.049  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:18.055  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:18.055  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:18.056  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:18.056  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:18.057  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:18.057  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, B,luetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:18.058  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:18.067  1042  2852 D DhcpStateMachine: StoppedState
08-16 12:26:18.067  1042  2852 D DhcpStateMachine: StoppedState{ when=-38ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:18.068  1042  1521 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 12:26:18.068  1042  1521 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 12:26:18.077  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:26:18.078  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.079  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.079  6923  6923 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:26:18.079  6923  6923 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 12:26:18.080  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 12:26:18.080  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:18.080  6923  6923 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:18.080  6923  6923 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 12:26:18.081  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.082  6923  6923 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 12:26:18.082  6923  6923 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 12:26:18.120  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:26:18.121  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.122  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.122  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 12:26:18.122  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:18.123  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.124  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.133  6906  6906 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 12:26:18.133  6906  6906 W LG Account v2.2: No ProfileInfo entries
08-16 12:26:18.133  6906  6906 I LG Account v2.2: isEnabled: false
08-16 12:26:18.133  6906  6906 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 12:26:18.133  6906  6906 I Feature : [Lifetracker]Country: EU
08-16 12:26:18.133  6906  6906 I Feature : [Lifetracker]Operator: OPEN
08-16 12:26:18.133  6906  6906 I Feature : [Lifetracker]Ranking support: false
08-16 12:26:18.134  6906  6906 I Feature : [Lifetracker]Comfort support: false
08-16 12:26:18.134  6906  6906 I Feature : [Lifetracker]Accessory: true
08-16 12:26:18.134  6906  6906 I Feature : [Lifetracker]Health device: true
08-16 12:26:18.134  6906  6906 I Feature : [Lifetracker]Extra Pedometer: false
08-16 12:26:18.134  6906  6906 I Feature : [Lifetracker]Blood glucose device: false
08-16 12:26:18.134  6906  6906 I Feature : [Lifetracker]Device Number: 3
08-16 12:26:18.140  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:18.151  2722  2722 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 12:26:18.151  2722  2722 I wpa_supplicant: monitor socket send errors count : 1
08-16 12:26:18.151  2722  2722 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
,08-16 12:26:18.152  1042  2757 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-16 12:26:18.152  1042  2757 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 12:26:18.180  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 12:26:18.190  2722  2722 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:26:18.190  1042  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 12:26:18.190  1042  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:26:18.190  1042  2757 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:26:18.190  2722  2722 W wpa_supplicant: USIM:  scard_deinit function
08-16 12:26:18.191  1042  2757 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 12:26:18.191  1042  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:18.191  1042  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:18.191  1042  1119 D Tethering: InitialState.processMessage what=4
08-16 12:26:18.192  1042  1521 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=192188
,08-16 12:26:18.192  1042  1521 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=192189
,08-16 12:26:18.194  1042  1521 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=192190  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:26:18.195  1042  1521 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=192191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:26:18.219  1042  1558 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6943 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:26:18.220  1042  1558 I ActivityManager: Killing 6183:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 12:26:18.267  1042  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 12:26:18.268  1042  1888 W libprocessgroup: failed to open /acct/uid_10014/pid_6183/cgroup.procs: No such file or directory
08-16 12:26:18.269  1042  1521 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:18.270  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:18.274  4155  4155 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:26:18.274  4155  4155 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:18.274  4155  4155 V BluetoothPbapReceiver: ***********state = 13
08-16 12:26:18.276  4155  4155 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 12:26:18.285  4155  4155 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:26:18.285  4155  4155 V BluetoothPbapService: state: 13
08-16 12:26:18.285  4155  4155 V BluetoothPbapService: Pbap Service closeService in
08-16 12:26:18.286  1042  1119 D BluetoothManagerService: Message: 20
08-16 12:26:18.286  1042  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17644124:true
08-16 12:26:18.286  4155  4155 V BluetoothPbapService: successfully stopped pbap service
08-16 12:26:18.286  4155  4155 V BluetoothPbapService: Pbap Service closeService out
08-16 12:26:18.286  4155  4155 V BluetoothPbapService: Pbap Service onDestroy
08-16 12:26:18.286  4155  4155 V BluetoothPbapService: Pbap Service closeService in
08-16 12:26:18.286  4155  4155 V BluetoothPbapService: Pbap Service closeService out
08-16 12:26:18.287  4155  4155 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 12:26:18.288  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:26:18.302  2722  2722 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 12:26:18.305  6803  6803 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 12:26:18.307  1042  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 12:26:18.307  1042  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 12:26:18.309  1042  2757 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 12:26:18.309  1042  1521 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 12:26:18.311  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-16 12:26:18.311  1042  1521 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 12:26:18.311  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:18.311  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:18.311  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:18.312  1925  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 12:26:18.312  1925  2258 D WfdsService: Set the WFDS Monitor: false
08-16 12:26:18.312  1925  2258 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:26:18.313  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:26:18.313  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:18.315  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 12:26:18.315  1042  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 12:26:18.315  1042  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 12:26:18.316  2459  2459 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:18.317  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:18.318  1042  1119 D BluetoothManagerService: Message: 30
,08-16 12:26:18.320  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:18.326  1042  1119 D BluetoothManagerService: Message: 30
08-16 12:26:18.329  6923  6923 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 12:26:18.331  6923  6923 D BluetoothMap: Create BluetoothMap proxy object
,08-16 12:26:18.332  1042  1119 D BluetoothManagerService: Message: 30
08-16 12:26:18.336  1042  1119 D BluetoothManagerService: Message: 30
08-16 12:26:18.339  6923  6923 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 12:26:18.340  6923  6923 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 12:26:18.348  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 12:26:18.351  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:18.352  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:18.354  1042  1637 I ActivityManager: Killing 6239:com.android.defcontainer/u0a4 (adj 15): empty #17
08-16 12:26:18.394  1042  1060 W libprocessgroup: failed to open /acct/uid_10004/pid_6239/cgroup.procs: No such file or directory
,08-16 12:26:18.402  6923  6923 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 12:26:18.409  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-16 12:26:18.426  6923  6923 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:26:18.458  6923  6923 D BluetoothInputDevice: Proxy object connected
,08-16 12:26:18.461  6923  6923 D HidProfile: Bluetooth service connected
,08-16 12:26:18.462  6923  6923 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:26:18.462  6923  6923 D PanProfile: Bluetooth service connected
,08-16 12:26:18.463  6923  6923 D BluetoothMap: Proxy object connected
,08-16 12:26:18.464  6923  6923 D MapProfile: Bluetooth service connected
,08-16 12:26:18.464  6923  6923 D BluetoothMap: getConnectedDevices()
,08-16 12:26:18.466  6923  6923 D BluetoothMap: Bluetooth is Not enabled
,08-16 12:26:18.479  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:18.526  6923  6923 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:18.526  6923  6923 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:18.538  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:18.540  6923  6923 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 12:26:18.544  6923  6923 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 12:26:18.551  6923  6923 D BluetoothPermissionRequest: onReceive
08-16 12:26:18.556  6923  6923 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 12:26:18.566  1042  1924 I ActivityManager: Killing 6394:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-16 12:26:18.572  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 12:26:18.642  4155  4155 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 12:26:18.642  4155  4155 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 12:26:18.643  1042  1888 W libprocessgroup: failed to open /acct/uid_10008/pid_6394/cgroup.procs: No such file or directory
,08-16 12:26:18.647  4155  4155 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 12:26:18.659  4155  4155 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:18.660  4155  4155 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 12:26:18.710  1042  1924 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6977 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 12:26:18.718  4155  4155 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:26:18.718  4155  4155 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:18.718  4155  4155 V BluetoothFtpService: Ftp Service closeService
08-16 12:26:18.719  4155  4155 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 12:26:18.721  4155  4155 V BluetoothFtpService: successfully stopped ftp service
08-16 12:26:18.721  4155  4155 V BluetoothFtpService: Ftp Service onDestroy
08-16 12:26:18.721  4155  4155 V BluetoothFtpService: Ftp Service closeService
08-16 12:26:18.723  4155  4155 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:18.723  4155  4155 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:18.723  4155  4155 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:18.724  4155  4155 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:26:18.724  4155  4155 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-16 12:26:18.724  4155  4155 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 12:26:18.727  4155  4155 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:18.727  4155  4155 V BluetoothSapService: state: 13
08-16 12:26:18.727  4155  4155 V BluetoothSapService: Stopping SAP server process
08-16 12:26:18.728  4155  4155 V BluetoothSapService: Sap Service closeSapService in
08-16 12:26:18.729  4155  4155 V BluetoothSapService: Close listen Socket : 
08-16 12:26:18.729  4155  4155 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:26:18.729  4155  4155 V BluetoothSapService: Close sapd  Socket : 
08-16 12:26:18.731  4155  4155 V BluetoothSapService: Sap Service closeSapService out
08-16 12:26:18.732  4155  4155 V BluetoothSapService: Sap Service onDestroy
08-16 12:26:18.732  4155  4155 V BluetoothSapService: Sap Service closeSapService in
08-16 12:26:18.732  4155  4155 V BluetoothSapService: Close listen Socket : 
08-16 12:26:18.732  4155  4155 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:26:18.732  4155  4155 V BluetoothSapService: Close sapd  Socket : 
08-16 12:26:18.732  4155  4155 V BluetoothSapService: Sap Service closeSapService out
08-16 12:26:18.773  1042  1924 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7002 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:26:18.809  6977  6977 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:26:18.835  6977  6977 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 12:26:18.851  7002  7002 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:26:18.866  1042  1942 I ActivityManager: Killing 6441:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 12:26:18.869  6977  6977 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 12:26:18.870  6977  6977 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 12:26:18.870  6977  6977 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 12:26:18.871  6977  6977 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 12:26:18.871  6977  6977 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 12:26:18.873  6977  6977 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 12:26:18.878  6977  6977 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 12:26:18.885  4155  4391 W bt-btif : ag scb idx 1 not allocated
08-16 12:26:18.885  4155  4247 D bt_hci_bdroid: cleanup
08-16 12:26:18.885  4155  4391 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 12:26:18.885  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:18.885  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:18.885  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:18.885  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:26:18.885  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:18.886  4155  4573 I bt_userial_mct: exiting userial_read_thread
,08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:18.886  4155  4573 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:26:18.886  4155  4399 I bt_lpm  : LPM is already off!!!
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:18.886  4155  4391 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:18.886  4155  4391 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 12:26:18.886  4155  4247 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 12:26:18.886  4155  4399 I bt_vendor: hw_epilog_process
08-16 12:26:18.886  4155  4247 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 12:26:18.886  4155  4247 D bt_userial_mct: userial_close
08-16 12:26:18.886  4155  4247 E bt_userial_mct: pthread_join() FAILED result:3
08-16 12:26:18.886  4155  4247 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 12:26:18.897  1042  2034 W libprocessgroup: failed to open /acct/uid_10011/pid_6441/cgroup.procs: No such file or directory
,08-16 12:26:18.906  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:18.910  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:26:18.945  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 12:26:18.951  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:18.954  6977  6977 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 12:26:18.957  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 12:26:18.957  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:18.957  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:18.960  6977  6977 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 12:26:18.961  4155  4247 D bt_hci_bdroid: set_power 0
08-16 12:26:18.961  4155  4247 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 12:26:18.961  4155  4247 I bt_vendor: bluetooth satus is on
08-16 12:26:18.961  4155  4247 I bt_vendor: bt-vendor : resetting BT status
08-16 12:26:18.961  4155  4247 I bt_vendor: Starting hciattach daemon
08-16 12:26:18.961  4155  4247 I bt_vendor: try to set false
08-16 12:26:18.962  4155  4247 I bt_vendor: Starting hciattach daemon
08-16 12:26:18.962  4155  4247 I bt_vendor: try to set false
08-16 12:26:18.963  4155  4247 I bt_vendor: cleanup
08-16 12:26:18.964  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:18.965  4155  4391 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 12:26:18.965  4155  4247 I GKI_LINUX: GKI_exit_task 0 done
08-16 12:26:18.965  4155  4247 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 12:26:18.968  4155  4244 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 12:26:18.972  4155  4155 D HeadsetService: Received stop request...Stopping profile...
08-16 12:26:18.973  4155  4155 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:26:18.973  4155  4155 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:26:18.974  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1baf80f2
08-16 12:26:18.974  4155  4307 D HeadsetStateMachine: Exit Disconnected: -1
08-16 12:26:18.975  1042  1042 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:18.975  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 12:26:18.976  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:18.976  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:18.976  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:18.976  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:18.977  4155  4155 D A2dpService: Received stop request...Stopping profile...
08-16 12:26:18.978  4155  4367 D A2dpStateMachine: Exit Disconnected: -1
08-16 12:26:18.979  4155  4155 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 12:26:18.982  4155  4244 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-16 12:26:18.989  4155  4155 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 12:26:18.989  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:18.989  4155  4155 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:26:18.989  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1baf80f2
08-16 12:26:18.989  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:18.990  1042  1042 D BluetoothA2dp: Proxy object disconnected
08-16 12:26:18.990  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 12:26:18.992  4155  4155 D HidService: Received stop request...Stopping profile...
08-16 12:26:18.992  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1baf80f2
08-16 12:26:18.993  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:26:18.994  4155  4155 D HealthService: Received stop request...Stopping profile...
08-16 12:26:18.994  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1baf80f2
08-16 12:26:18.994  6923  6923 D BluetoothInputDevice: Proxy object disconnected
08-16 12:26:18.995  6923  6923 D HidProfile: Bluetooth service disconnected
,08-16 12:26:18.997  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:18.998  4155  4155 D HeadsetStateMachine: Unbinding service...
08-16 12:26:18.999  4155  4155 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:26:18.999  4155  4155 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:26:18.999  4155  4155 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:26:18.999  4155  4155 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:26:18.999  4155  4155 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 12:26:18.999  4155  4155 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:26:18.999  4155  4155 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:26:19.000  4155  4155 D PanService: Received stop request...Stopping profile...
08-16 12:26:19.004  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:26:19.004  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:19.004  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:19.004  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1baf80f2
08-16 12:26:19.005  6923  6923 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 12:26:19.005  6923  6923 D PanProfile: Bluetooth service disconnected
08-16 12:26:19.006  4155  4155 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:26:19.006  4155  4155 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 12:26:19.007  4155  4155 D BtGatt.GattService: stop()
08-16 12:26:19.007  4155  4155 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 12:26:19.010  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1baf80f2
08-16 12:26:19.010  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:19.011  4155  4155 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:26:19.011  4155  4155 D BluetoothMapService: stop()
08-16 12:26:19.012  4155  4155 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 12:26:19.012  4155  4155 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 12:26:19.013  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1baf80f2
08-16 12:26:19.014  4155  4155 I BluetoothA2dpServiceJni: cleanupNative
08-16 12:26:19.014  4155  4368 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 12:26:19.014  4155  4155 I GKI_LINUX: GKI_exit_task 2 done
08-16 12:26:19.014  4155  4155 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 12:26:19.015  4155  4155 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 12:26:19.015  4155  4155 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 12:26:19.015  4155  4155 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 12:26:19.015  4155  4155 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:26:19.015  4155  4155 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:26:19.015  4155  4155 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 12:26:19.015  4155  4155 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 12:26:19.017  4155  4155 V BluetoothMapService: Handler(): got msg=4
08-16 12:26:19.017  4155  4155 D BluetoothMapService: MAP Service closeService in
08-16 12:26:19.017  4155  4155 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:26:19.017  4155  4155 V BluetoothMapService: MAP Service closeService out
08-16 12:26:19.017  4155  4155 D BluetoothMapService: cleanup()
08-16 12:26:19.017  4155  4155 D BluetoothMapService: MAP Service closeService in
08-16 12:26:19.017  4155  4155 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:26:19.017  4155  4155 V BluetoothMapService: MAP Service closeService out
08-16 12:26:19.017  4155  4244 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 12:26:19.017  4155  4244 D BluetoothAdapterProperties: Setting state to 10
08-16 12:26:19.017  4155  4244 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 12:26:19.018  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:19.018  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 12:26:19.018  4155  4244 I BluetoothAdapterState: Entering OffState
08-16 12:26:19.018  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 12:26:19.018  6923  6938 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:26:19.019  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:26:19.021  1837  2675 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:26:19.022  1042  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:26:19.022  6923  7027 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:26:19.022  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:19.023  1042  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:26:19.023  6923  6939 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:26:19.026  6923  7027 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:26:19.027  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:26:19.028  1042  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 12:26:19.028  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 12:26:19.031  1042  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 12:26:19.031  1042  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 12:26:19.031  1042  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2f658fd5 mBinding = false
,08-16 12:26:19.032  1042  1119 D BluetoothManagerService: Sending unbind request.
08-16 12:26:19.032  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:19.033  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:19.034  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 12:26:19.035  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:26:19.037  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:19.038  1925  2085 D LGBluetoothAPIService: Message: 2
08-16 12:26:19.038  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:26:19.038  1925  2085 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@18c090d mBinding = false
08-16 12:26:19.038  1925  2085 D LGBluetoothAPIService: Sending unbind request.
08-16 12:26:19.038  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:19.039  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:19.042  6923  6923 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 12:26:19.043  6923  6923 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 12:26:19.043  6923  6923 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 12:26:19.043  4155  4247 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 12:26:19.044  4155  4155 I GKI_LINUX: GKI_exit_task 1 done
08-16 12:26:19.044  4155  4155 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 12:26:19.045  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 12:26:19.045  4155  4155 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 12:26:19.045  4155  4155 I art     : --- WEIRD: removing null entry 246
08-16 12:26:19.045  4155  4155 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
,08-16 12:26:19.045  4155  4155 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 12:26:19.047  1586  1586 D BluetoothAdapter: 1059169482: getState() :  mService = null. Returning STATE_OFF
08-16 12:26:19.047  1586  1586 D BluetoothAdapter: 1059169482: getState() :  mService = null. Returning STATE_OFF
08-16 12:26:19.088  1042  2020 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7028 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 12:26:19.092  4155  4155 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 12:26:19.097  6923  6923 D DockEventReceiver: finishStartingService: stopping service
08-16 12:26:19.097  4155  4155 I art     : System.exit called, status: 0
08-16 12:26:19.097  4155  4155 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 12:26:19.132   318  2134 V AudioFlinger: 4155 died, releasing its sessions
,08-16 12:26:19.132   318  2134 V AudioFlinger:  pid 1837 @ 0
,08-16 12:26:19.132   318  2134 V AudioFlinger:  pid 3315 @ 1
,08-16 12:26:19.132  6923  6923 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-16 12:26:19.132   318  2134 V AudioFlinger:  pid 3315 @ 2
,08-16 12:26:19.161  1042  1693 I ActivityManager: Process com.android.bluetooth (pid 4155) has died
08-16 12:26:19.162  1042  1693 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 12:26:19.175  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:26:19.191  6923  6923 D BluetoothPermissionRequest: onReceive
,08-16 12:26:19.196  6923  6923 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 12:26:19.197  6923  6923 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 12:26:19.201  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:26:19.261  1042  1971 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7047 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 12:26:19.274  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:19.277  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:26:19.285   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 23.489ms
08-16 12:26:19.290  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:26:19.305   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 19.456ms
,08-16 12:26:19.309  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:26:19.310  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:26:19.310  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:26:19.310  6923  6923 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:26:19.311  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:26:19.317  7028  7066 W FormManager: Network not available. Please check & try again.
,08-16 12:26:19.323   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 379us total 17.434ms
08-16 12:26:19.323  6923  6923 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:26:19.323  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 12:26:19.323  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:26:19.324  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:26:19.324  6923  6923 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:26:19.325  6923  6923 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:26:19.332  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 12:26:19.333  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:26:19.334  7028  7067 V FormManager: Network unavailable.
08-16 12:26:19.335  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:19.336  7028  7067 V FormManager: Network unavailable.
08-16 12:26:19.338  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:19.340  7047  7047 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 12:26:19.341  7047  7047 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:19.341  7047  7047 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 12:26:19.342  7047  7047 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 12:26:19.345  6943  6943 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-16 12:26:19.345  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:19.345  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:19.349  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:26:19.354  7028  7072 V FormManager: Network unavailable.
08-16 12:26:19.354  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:19.355  4660  7070 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:26:19.359  7047  7047 D BluetoothAdapterApp: Loading JNI Library
08-16 12:26:19.359  7028  7071 W FormManager: Network not available. Please check & try again.
08-16 12:26:19.360  7028  7072 V FormManager: Network unavailable.
,08-16 12:26:19.367  1042  1915 I ActivityManager: Killing 6464:com.android.contacts/u0a19 (adj 15): empty #17
08-16 12:26:19.368  4660  7073 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:26:19.368  4660  7073 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:26:19.382  7047  7047 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@a2875cb Instance Count = 1
,08-16 12:26:19.403  1042  1693 W libprocessgroup: failed to open /acct/uid_10019/pid_6464/cgroup.procs: No such file or directory
,08-16 12:26:19.406  7047  7047 D BluetoothAdapterApp: onCreate
08-16 12:26:19.409  6977  6977 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 12:26:19.410  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 12:26:19.411  6977  6977 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 12:26:19.435  7047  7047 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 12:26:19.435  7047  7047 D ProfileConfigQcom: Adding HeadsetService
08-16 12:26:19.435  7047  7047 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 12:26:19.435  7047  7047 D ProfileConfigQcom: Adding A2dpService
08-16 12:26:19.435  7047  7047 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 12:26:19.436  7047  7047 D ProfileConfigQcom: Adding HidService
08-16 12:26:19.436  7047  7047 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 12:26:19.436  7047  7047 D ProfileConfigQcom: Adding HealthService
08-16 12:26:19.436  7047  7047 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 12:26:19.437  7047  7047 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 12:26:19.437  7047  7047 D ProfileConfigQcom: Adding PanService
08-16 12:26:19.438  7047  7047 D ProfileConfigQcom: [BTUI] GattService is supported
,08-16 12:26:19.438  7047  7047 D ProfileConfigQcom: Adding GattService
08-16 12:26:19.438  7047  7047 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 12:26:19.438  7047  7047 D ProfileConfigQcom: Adding BluetoothMapService
08-16 12:26:19.439  7047  7047 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 12:26:19.441  7047  7047 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 12:26:19.445  6923  6923 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 12:26:19.446  6977  6977 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:19.446  6977  6977 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:26:19.447  7047  7047 V LGMDMManagerInternal: Create singleton instance
08-16 12:26:19.454  6977  6977 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 12:26:19.456  6977  6977 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 12:26:19.456  6977  6977 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 12:26:19.456  6977  6977 V SoundPool: doLoad: loading sample sampleID=1
,08-16 12:26:19.456  6977  6977 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 12:26:19.460  6977  7078 V SoundPool: Start decode
08-16 12:26:19.461  6977  7078 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 12:26:19.461   318   318 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 12:26:19.461   318   318 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 12:26:19.461   318   318 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 12:26:19.462   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 12:26:19.462   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 12:26:19.462   318   318 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 12:26:19.462   318   318 V MediaPlayerService: player type = 3
08-16 12:26:19.462   318   318 V AwesomePlayer: AwesomePlayer create()
08-16 12:26:19.462   318   318 V AwesomePlayer: reset_l() 
08-16 12:26:19.462   318   318 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:19.462   318   318 V AwesomePlayer: setAudioSink() 
08-16 12:26:19.462   318   318 V AwesomePlayer: reset_l() 
08-16 12:26:19.462   318   318 V AudioCache: notify(0xb5474500, 8, 0, 0)
08-16 12:26:19.462   318   318 V AudioCache: ignored
08-16 12:26:19.462   318   318 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:19.462   318   318 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 12:26:19.462   318   318 V AwesomePlayer: setDataSource_l dataSource
08-16 12:26:19.462   318   318 V LGParserOSAL: SniffLGParser start
08-16 12:26:19.462   318   318 V LGParserOSAL: MainType:5, SubType=0
08-16 12:26:19.462   318   318 V LGParserOSAL: #### check Mime : application/ogg
08-16 12:26:19.462   318   318 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 12:26:19.462   318   318 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 12:26:19.463  6703  6703 D UEI.SmartControl: QS Service created
08-16 12:26:19.464  6977  6977 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 12:26:19.471  6977  6977 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:26:19.472  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 12:26:19.485  6977  6977 V LGMDMManager: Create singleton instance
08-16 12:26:19.489  6703  6703 I UEI.SmartControl: Service initServices...
08-16 12:26:19.489  6703  6703 D UEI.SmartControl: QS start get config
08-16 12:26:19.505   318   318 V LGParserOSAL: supported mime: application/ogg
08-16 12:26:19.505   318   318 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 12:26:19.505   318   318 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 12:26:19.505   318   318 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 12:26:19.505   318   318 V AwesomePlayer: AudioTrack Setting
08-16 12:26:19.505   318   318 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 12:26:19.505   318   318 V AwesomePlayer: setAudioSource() 
08-16 12:26:19.505   318   318 V MediaPlayerService: prepare
08-16 12:26:19.505   318   318 V AwesomePlayer: prepareAsync_l() 
08-16 12:26:19.505   318   318 V MediaPlayerService: wait for prepare
08-16 12:26:19.505   318  7079 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 12:26:19.505   318  7079 V AwesomePlayer: initAudioDecoder() 
08-16 12:26:19.506   318  7079 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:26:19.506   318  7079 V AudioSystem: isOffloadSupported()
08-16 12:26:19.506   318  7079 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:26:19.506   318  7079 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:26:19.506   318  7079 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:26:19.506   318  7079 V AwesomePlayer: getUseOffload() = 0 
08-16 12:26:19.506   318  7079 V OMXCodec: OMXCodec::Create
08-16 12:26:19.506   318  7079 V OMXCodec: findMatchingCodecs()
08-16 12:26:19.506   318  7079 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 12:26:19.506   318  7079 V OMXCodec: matchingCodecs.size()=1
08-16 12:26:19.506   318  7079 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 12:26:19.508   318  7079 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 12:26:19.508   318  7079 V LGCodecAdapter: LG Codec Adapter start
08-16 12:26:19.508   318  7079 V OMXCodec: OMXCodec Createtor
08-16 12:26:19.508   318  7079 V OMXCodec: setComponentRole
08-16 12:26:19.508   318  7079 V OMXCodec: configureCodec protected=0
08-16 12:26:19.508   318  7079 V LGCodecAdapter: called getLGCodecSpecificData
08-16 12:26:19.508   318  7079 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 12:26:19.508   318  7079 V LGCodecOSAL: Called LGconfigureCodecMETA
,08-16 12:26:19.508   318  7079 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 12:26:19.508   318  7079 V LGCodecOSAL: Not support LGCodec
08-16 12:26:19.508   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:26:19.508   318  7079 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 12:26:19.508   318  7079 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 12:26:19.508   318  7079 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 12:26:19.508   318  7079 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:26:19.508   318  7079 V AudioSystem: isOffloadSupported()
08-16 12:26:19.508   318  7079 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:26:19.508   318  7079 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:26:19.508   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 12:26:19.508   318  7079 V OMXCodec: init()
08-16 12:26:19.508   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 12:26:19.508   318  7079 V OMXCodec: allocateBuffers
08-16 12:26:19.508   318  7079 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 12:26:19.508   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 12:26:19.509   318  7079 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 12:26:19.509   318  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-16 12:26:19.509   318  7079 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 12:26:19.511   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:26:19.511   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:26:19.511   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 12:26:19.511   318  7079 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 12:26:19.511   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 12:26:19.511   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 12:26:19.511   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 12:26:19.511   318  7079 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 12:26:19.511   318  7079 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 12:26:19.511   318  7079 V AudioCache: notify(0xb5474500, 5, 0, 0)
08-16 12:26:19.511   318  7079 V AudioCache: ignored
08-16 12:26:19.511   318  7079 V AudioCache: notify(0xb5474500, 1, 0, 0)
08-16 12:26:19.511   318  7079 V AudioCache: prepared
08-16 12:26:19.512   318   318 V AudioCache: wait - success
08-16 12:26:19.512   318   318 V MediaPlayerService: star,t
08-16 12:26:19.512   318   318 V AwesomePlayer: play_l() 
08-16 12:26:19.512   318   318 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 12:26:19.512   318   318 V AwesomePlayer: createAudioPlayer_l
08-16 12:26:19.512   318   318 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 12:26:19.512   318   318 V AwesomePlayer: startAudioPlayer_l() 
08-16 12:26:19.512   318   318 D AudioPlayer: start of Playback, useOffload 0
08-16 12:26:19.512   318   318 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:26:19.512   318   318 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 12:26:19.515   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 12:26:19.516   318  7081 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 12:26:19.516   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb790 on output port
08-16 12:26:19.517   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 12:26:19.517   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 12:26:19.517   318   318 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 12:26:19.518   318   318 V AudioCache: notify(0xb5474500, 6, 0, 0)
08-16 12:26:19.518   318   318 V AudioCache: ignored
08-16 12:26:19.518   318   318 V MediaPlayerService: wait for playback complete
08-16 12:26:19.519   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.519   318  7082 V AudioCache: memcpy(0xaf006000, 0xb0406000, 4096)
08-16 12:26:19.531   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.531   318  7082 V AudioCache: memcpy(0xaf007000, 0xb0406000, 4096)
08-16 12:26:19.532   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.532   318  7082 V AudioCache: memcpy(0xaf008000, 0xb0406000, 4096)
08-16 12:26:19.532   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.532   318  7082 V AudioCache: memcpy(0xaf009000, 0xb0406000, 4096)
08-16 12:26:19.533   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.533   318  7082 V AudioCache: memcpy(0xaf00a000, 0xb0406000, 4096)
08-16 12:26:19.533   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.533   318  7082 V AudioCache: memcpy(0xaf00b000, 0xb0406000, 4096)
08-16 12:26:19.534   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.534   318  7082 V AudioCache: memcpy(0xaf00c000, 0xb0406000, 4096)
08-16 12:26:19.535   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.535   318  7082 V AudioCache: memcpy(0xaf00d000, 0xb0406000, 4096)
08-16 12:26:19.535   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.536   318  7082 V AudioCache: memcpy(0xaf00e000, 0xb0406000, 4096)
08-16 12:26:19.536   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.536   318  7082 V AudioCache: memcpy(0xaf00f000, 0xb0406000, 4096)
08-16 12:26:19.537   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.537   318  7082 V AudioCache: memcpy(0xaf010000, 0xb0406000, 4096)
08-16 12:26:19.538   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.538   318  7082 V AudioCache: memcpy(0xaf011000, 0xb0406000, 4096)
08-16 12:26:19.538   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.538   318  7082 V AudioCache: memcpy(0xaf012000, 0xb0406000, 4096)
08-16 12:26:19.539   318  7082 V AudioCache: write(0xb0406000, 4096)
,08-16 12:26:19.539   318  7082 V AudioCache: memcpy(0xaf013000, 0xb0406000, 4096)
08-16 12:26:19.540   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.540   318  7082 V AudioCache: memcpy(0xaf014000, 0xb0406000, 4096)
08-16 12:26:19.540   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.540   318  7082 V AudioCache: memcpy(0xaf015000, 0xb0406000, 4096)
08-16 12:26:19.541   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.541   318  7082 V AudioCache: memcpy(0xaf016000, 0xb0406000, 4096)
08-16 12:26:19.542   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.542   318  7082 V AudioCache: memcpy(0xaf017000, 0xb0406000, 4096)
08-16 12:26:19.542   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.542   318  7082 V AudioCache: memcpy(0xaf018000, 0xb0406000, 4096)
08-16 12:26:19.543   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.543   318  7082 V AudioCache: memcpy(0xaf019000, 0xb0406000, 4096)
08-16 12:26:19.544   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.544   318  7082 V AudioCache: memcpy(0xaf01a000, 0xb0406000, 4096)
08-16 12:26:19.544   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.545   318  7082 V AudioCache: memcpy(0xaf01b000, 0xb0406000, 4096)
08-16 12:26:19.545   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.545   318  7082 V AudioCache: memcpy(0xaf01c000, 0xb0406000, 4096)
08-16 12:26:19.546   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.546   318  7082 V AudioCache: memcpy(0xaf01d000, 0xb0406000, 4096)
08-16 12:26:19.546   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.546   318  7082 V AudioCache: memcpy(0xaf01e000, 0xb0406000, 4096)
08-16 12:26:19.547   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.547   318  7082 V AudioCache: memcpy(0xaf01f000, 0xb0406000, 4096)
08-16 12:26:19.548   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.548   318  7082 V AudioCache: memcpy(0xaf020000, 0xb0406000, 4096)
08-16 12:26:19.548   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.548   318  7082 V AudioCache: memcpy(0xaf021000, 0xb0406000, 4096)
08-16 12:26:19.549   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.549   318  7082 V AudioCache: memcpy(0xaf022000, 0xb0406000, 4096)
08-16 12:26:19.550   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.550   318  7082 V AudioCache: memcpy(0xaf023000, 0xb0406000, 4096)
08-16 12:26:19.551   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.551   318  7082 V AudioCache: memcpy(0xaf024000, 0xb0406000, 4096)
08-16 12:26:19.551   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.551   318  7082 V AudioCache: memcpy(0xaf025000, 0xb0406000, 4096)
08-16 12:26:19.552   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.552   318  7082 V AudioCache: memcpy(0xaf026000, 0xb0406000, 4096)
08-16 12:26:19.553   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.553   318  7082 V AudioCache: memcpy(0xaf027000, 0xb0406000, 4096)
08-16 12:26:19.553   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.553   318  7082 V AudioCache: memcpy(0xaf028000, 0xb0406000, 4096)
08-16 12:26:19.554   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.554   318  7082 V AudioCache: memcpy(0xaf029000, 0xb0406000, 4096)
08-16 12:26:19.554   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.554   318  7082 V AudioCache: memcpy(0xaf02a000, 0xb0406000, 4096)
08-16 12:26:19.555   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.555   318  7082 V AudioCache: memcpy(0xaf02b000, 0xb0406000, 4096)
08-16 12:26:19.556   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.556   318  7082 V AudioCache: memcpy(0xaf02c000, 0xb0406000, 4096)
08-16 12:26:19.556   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.556   318  7082 V AudioCache: memcpy(0xaf02d000, 0xb0406000, 4096)
08-16 12:26:19.557   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.557   318  7082 V AudioCache: memcpy(0xaf02e000, 0xb0406000, 4096)
08-16 12:26:19.557   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.557   318  7082 V AudioCache: memcpy(0xaf02f000, 0xb0406000, 4096)
08-16 12:26:19.558   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.558   318  7082 V AudioCache: memcpy(0xaf030000, 0xb0406000, 4096)
08-16 12:26:19.559   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.559   318  7082 V AudioCache: memcpy(0xaf031000, 0xb0406000, 4096)
08-16 12:26:19.560   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.560   318  7082 V AudioCache: memcpy(0xaf032000, 0xb0406000, 4096)
08-16 12:26:19.560   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.560   318  7082 V AudioCache: memcpy(0xaf033000, 0xb0406000, 4096)
08-16 12:26:19.561   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.561   318  7082 V AudioCache: memcpy(0xaf034000, 0xb0406000, 4096)
08-16 12:26:19.561   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.561   318  7082 V AudioCache: memcpy(0xaf035000, 0xb0406000, 4096)
08-16 12:26:19.562   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.562   318  7082 V AudioCache: memcpy(0xaf036000, 0xb0406000, 4096)
08-16 12:26:19.563   318  7082 V AudioCache: write(0xb0406000, 4096)
08-16 12:26:19.563   318  7082 V AudioCache: memcpy(0xaf037000, 0xb0406000, 4096)
08-16 12:26:19.563   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 12:26:19.563   318  7082 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 12:26:19.563   318  7082 V AwesomePlayer: postAudioEOS() 
08-16 12:26:19.563   318  7082 V AudioCache: write(0xb0406000, 280)
08-16 12:26:19.563   318  7082 V AudioCache: memcpy(0xaf038000, 0xb0406000, 280)
08-16 12:26:19.564  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 12:26:19.564   318  7079 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 12:26:19.565   318  7079 V AwesomePlayer: onStreamDone
08-16 12:26:19.565   318  7079 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 12:26:19.565   318  7079 V AudioCache: notify(0xb5474500, 2, 0, 0)
08-16 12:26:19.565   318  7079 V AudioCache: playback complete
08-16 12:26:19.565   318  7079 V AwesomePlayer: pause_l() 
08-16 12:26:19.565   318   318 V AudioCache: wait - success
08-16 12:26:19.565   318  7079 V AudioCache: notify(0xb5474500, 7, 0, 0)
08-16 12:26:19.565   318   318 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 12:26:19.565   318  7079 V AudioCache: ignored
08-16 12:26:19.565   318  7079 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:19.565   318  7079 D AudioPlayer: Pause Playback at 1068125
08-16 12:26:19.565   318   318 V AwesomePlayer: reset_l() 
08-16 12:26:19.565   318   318 V AudioCache: notify(0xb5474500, 8, 0, 0)
08-16 12:26:19.565   318   318 V AudioCache: ignored
08-16 12:26:19.565   318   318 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:19.565   318   318 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 12:26:19.565   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 12:26:19.565   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 12:26:19.565   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 12:26:19.565   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb790 on port 1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 12:26:19.566   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 12:26:19.566   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 12:26:19.566   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 12:26:19.567   318  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 12:26:19.567   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 12:26:19.567   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 12:26:19.567   318   318 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 12:26:19.568   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 12:26:19.568   318   318 D AudioPlayer: AudioPlayer releasing audio source
08-16 12:26:19.568   318   318 D AudioPlayer: AudioPlayer done releasing audio source
08-16 12:26:19.568   318   318 V AwesomePlayer: reset_l() 
08-16 12:26:19.568   318   318 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:19.568   318   318 V AwesomePlayer: ~AwesomePlayer call
08-16 12:26:19.568  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 12:26:19.568   318   318 V AwesomePlayer: reset_l() 
08-16 12:26:19.568   318   318 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:19.568  6977  7078 V SoundPool: close(31)
08-16 12:26:19.568  6977  7078 V SoundPool: pointer = 0xa0012000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 12:26:19.572  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7583
08-16 12:26:19.580  7047  7047 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:19.584  7047  7047 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:19.584  7047  7047 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:19.584  7047  7047 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:19.585  7047  7047 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:19.586  7047  7047 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 12:26:19.595  7002  7002 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 12:26:19.832  6703  6703 I UEI.SmartControl: Supports setup maps: true
,08-16 12:26:19.835  6703  6703 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 12:26:19.835  6703  6703 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-16 12:26:19.835  6703  6703 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 12:26:19.835  6703  6703 I UEI.SmartControl: ### init IR Blaster...
08-16 12:26:19.838  6703  6703 D serial_port: Configuring serial port
08-16 12:26:19.839  6703  6703 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:26:19.839  6703  6703 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 12:26:19.839  6703  6703 I UEI.SmartControl: configuring settings for MAXQ616
08-16 12:26:19.839  6703  6703 I UEI.SmartControl: Get version...
08-16 12:26:19.858  6703  7084 D UEI.SmartControl: serial port data available: 21
,08-16 12:26:19.884  6703  6703 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 12:26:19.884  6703  6703 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 12:26:19.884  6703  6703 I UEI.SmartControl: QS saving settings...
,08-16 12:26:19.885  6703  6703 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 12:26:19.903  6703  7084 D UEI.SmartControl: serial port data available: 4
,08-16 12:26:19.936  6703  6703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 12:26:19.939  6703  6703 E UEI.SmartControl: Services init done
,08-16 12:26:19.939  6703  6703 D UEI.SmartControl: QS Service init finished
08-16 12:26:19.942  6703  7093 I UEI.SmartControl: Device manager: loading config....
08-16 12:26:19.943  6703  7093 D UEI.SmartControl: ----------- loading internal config...
08-16 12:26:19.945  6703  6703 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:26:19.945  6703  6703 D UEI.SmartControl: QS Service version code: 201091
08-16 12:26:19.946  6703  6703 D UEI.SmartControl: Service requested: Control
08-16 12:26:19.954  6703  7093 E UEI.SmartControl: Loading SETTINGS...
08-16 12:26:19.958  6703  6703 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 12:26:19.962  6977  6977 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-16 12:26:19.966  6703  6718 I UEI.SmartControl: ------ IControl API: 11
08-16 12:26:19.966  6703  6718 D UEI.SmartControl: File observer start...
08-16 12:26:19.966  6703  7093 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 12:26:19.967  6703  6718 E UEI.SmartControl: IR Port is disabled: false
08-16 12:26:19.967  6703  6703 D UEI.SmartControl: Internal service binding...
08-16 12:26:19.967  6703  6718 D UEI.SmartControl: Starting file observer...
08-16 12:26:19.968  6703  6718 I UEI.SmartControl: Registering callback...
,08-16 12:26:19.975  6703  6719 I UEI.SmartControl: ------ IControl API: 19
08-16 12:26:19.976  6703  6719 I UEI.SmartControl: Registering Services Ready callback...
08-16 12:26:19.976  6703  6719 I UEI.SmartControl: Notify client services are ready...
08-16 12:26:19.977  6977  7001 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 12:26:19.978  6977  7076 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 12:26:19.979  6977  7076 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 12:26:19.980  6977  6977 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 12:26:19.981  6977  6977 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 12:26:19.981  6703  6718 I UEI.SmartControl: ------ IControl API: 8
08-16 12:26:19.981  6703  7092 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 12:26:19.981  6977  7000 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 12:26:19.982  6703  7092 D UEI.SmartControl: -----service ready thread exits
08-16 12:26:19.983  6977  7076 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 12:26:19.983  6977  7076 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 12:26:19.985  6977  6977 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-16 12:26:19.986  6977  6977 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 12:26:19.986  6977  6977 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 12:26:19.987  6977  6977 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 12:26:19.990  6977  6977 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 12:26:19.991  6977  6977 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 12:26:19.993  6977  6977 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 12:26:19.994  6977  6977 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-16 12:26:19.995  6977  6977 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 12:26:19.995  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 12:26:19.996  6977  6977 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:26:19.996  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 12:26:19.997  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-16 12:26:19.998  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 12:26:19.999  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 12:26:20.001  6977  6977 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471343180000]
08-16 12:26:20.003  6977  6977 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 12:26:20.005  1042  1996 I ActivityManager: Killing 6515:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 12:26:20.026  6977  7095 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 12:26:20.033  1042  1996 I ActivityManager: Killing 6494:com.lge.email/u0a23 (adj 15): empty #18
08-16 12:26:20.062  1042  1558 W libprocessgroup: failed to open /acct/uid_10027/pid_6515/cgroup.procs: No such file or directory
,08-16 12:26:20.067  1042  1915 W libprocessgroup: failed to open /acct/uid_10023/pid_6494/cgroup.procs: No such file or directory
08-16 12:26:20.072  6977  6977 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 12:26:20.073  6977  6977 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:26:20.074  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 12:26:20.074  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 12:26:20.074  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 12:26:20.075  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 12:26:20.075  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-16 12:26:20.248  1042  1059 I art     : Explicit concurrent mark sweep GC freed 62071(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.075ms total 162.804ms
,08-16 12:26:20.253  6977  6977 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-16 12:26:20.880  1042  1361 D PowerManagerServiceEx: acquireWakeLockInternal: lock=250086321, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,08-16 12:26:20.896  1042  1361 V AlarmManager: ELAPSED_WAKEUP set : Alarm{231ad68f type 2 when 194873 com.google.android.gms} when 194873
,08-16 12:26:20.907   314  7100 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 12:26:20.915  1042  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 12:26:20.931  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 12:26:20.966  1042  1042 D PowerManagerServiceEx: releaseWakeLockInternal: lock=250086321 [*alarm*], flags=0x0
,08-16 12:26:21.007  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:21.012  1042  1060 D WifiServiceImplEx: setWifiEnabled: true pid=6803, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:26:21.012  1042  1060 D WifiService: setWifiEnabled: true pid=6803, uid=10118
08-16 12:26:21.012  1042  1060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:26:21.016  1042  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:26:21.023  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:26:21.027  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:21.030  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:21.038  1042  1119 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:26:21.043  1042  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:21.052  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:26:21.052  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:26:21.052  1042  1042 D Ulp_jni : JNI:system_update. Event-4
,08-16 12:26:21.057  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:21.058  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:21.059  1042  1521 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 12:26:21.059  1042  1521 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 12:26:21.062  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 12:26:21.062  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:26:21.062  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 12:26:21.062  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:26:21.062  1042  1521 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 12:26:21.062  1042  1521 E WifiHW  : unknown target_country: EU , set to default
08-16 12:26:21.062  1042  1521 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 12:26:21.062  1042  1521 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 12:26:21.062  1042  1521 I WifiUtil: gEnableBmps=1
08-16 12:26:21.065  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 12:26:21.073  6345  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:26:21.083  5754  5754 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 12:26:21.092  1042  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:21.106  5754  5754 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 12:26:21.108  1042  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:21.108  1042  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 12:26:21.124  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:21.188  1042  1637 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7118 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 12:26:21.292  7118  7118 I AppUp4:AppBoxCP: onCreate
08-16 12:26:21.293  7118  7118 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 12:26:21.304  7118  7118 I AppUp4:DB:  setFingerPrint start
,08-16 12:26:21.304  7118  7118 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-16 12:26:21.313  7118  7118 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-16 12:26:21.313  7118  7118 I AppUp4:DB:  SDK version = 21
08-16 12:26:21.313  7118  7118 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-16 12:26:21.316  7118  7118 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-16 12:26:21.317  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:26:21.317  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:21.320  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:26:21.320  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 12:26:21.332  7118  7118 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 12:26:21.396  7118  7118 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:21.396  7118  7118 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:21.405  7118  7118 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ef5abfd
08-16 12:26:21.405  7118  7118 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:26:21.405  7118  7118 D AppUp4:CustFacade: isPhone : true
08-16 12:26:21.406  7118  7118 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:26:21.407  7118  7118 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-16 12:26:21.407  7118  7118 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 12:26:21.408  7118  7137 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 12:26:21.408  7118  7137 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 12:26:21.409  7118  7137 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 12:26:21.414  1042  1637 I ActivityManager: Killing 6574:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-16 12:26:21.455  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:21.456  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:26:21.457  1042  1692 W libprocessgroup: failed to open /acct/uid_10061/pid_6574/cgroup.procs: No such file or directory
08-16 12:26:21.459  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:26:21.462  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:21.473  4660  7142 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:26:21.479  4660  7143 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:21.480  4660  7143 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:26:21.513  1042  1943 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7144 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 12:26:21.601  7144  7144 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:26:21.601  7144  7144 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:21.603  7144  7144 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 12:26:21.603  7144  7144 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 12:26:21.696  7144  7144 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 12:26:21.711  7144  7144 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 12:26:21.770  7144  7144 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 12:26:21.811  7144  7144 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:21.811  7144  7144 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:21.893  1042  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 12:26:21.893  1042  1119 D Tethering: InitialState.processMessage what=4
,08-16 12:26:21.905   314   900 D SoftapController: Softap fwReload - Ok
08-16 12:26:21.906  1042  1521 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (836ms)
08-16 12:26:21.912   314   900 D CommandListener: Setting iface cfg
08-16 12:26:21.912   314   900 D CommandListener: Trying to bring down wlan0
,08-16 12:26:21.914   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:26:21.918  1042  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 12:26:21.919  1042  1521 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 12:26:21.921  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:21.921  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:21.921  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:21.914  7172  7172 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:21.914  7172  7172 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:21.932  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 12:26:21.933  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:21.934  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 12:26:21.936  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:21.937  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:21.939  1042  1521 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 12:26:21.939  1042  1521 D WifiMonitor: connecting to supplicant
,08-16 12:26:21.947  7172  7172 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 12:26:21.982  7172  7172 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 12:26:21.982  7172  7172 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 12:26:21.997  7144  7144 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 12:26:22.026  3315  3315 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:26:22.026  3315  3315 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:22.026  3315  3315 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 12:26:22.029  7144  7144 I HubEmail: JNI_OnLoad()
08-16 12:26:22.029  7144  7144 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:26:22.029  7144  7144 I HubEmail: registerNatives()
08-16 12:26:22.029  7144  7144 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:26:22.029  7144  7144 I HubEmail: registerNativeMethods()
08-16 12:26:22.029  7144  7144 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:26:22.030  7144  7144 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 12:26:22.060  7172  7172 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 12:26:22.072  1042  1942 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7178 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 12:26:22.079  7028  7175 W FormManager: Network not available. Please check & try again.
08-16 12:26:22.084  7144  7177 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:26:22.090  7028  7176 V FormManager: Network unavailable.
08-16 12:26:22.093  7028  7176 V FormManager: Network unavailable.
08-16 12:26:22.099  7172  7172 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 12:26:22.103  1042  1059 I ActivityManager: Killing 6619:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 12:26:22.105  7172  7172 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 12:26:22.108  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:26:22.109  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 12:26:22.109  1042  7195 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 12:26:22.109  1042  7195 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 12:26:22.109  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:26:22.110  1042  1521 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:26:22.110  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.111  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 12:26:22.111  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.112  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.113  1042  1521 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 12:26:22.113  1042  1521 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 12:26:22.114  1042  1521 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 12:26:22.114  1042  1521 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 12:26:22.114  1042  1521 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-16 12:26:22.132  7172  7172 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-16 12:26:22.132  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 12:26:22.132  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 12:26:22.132  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 12:26:22.132  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 12:26:22.133  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:26:22.133  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:26:22.141  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:22.141  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:22.141  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:22.142  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.142  1042  2014 W libprocessgroup: failed to open /acct/uid_10080/pid_6619/cgroup.procs: No such file or directory
08-16 12:26:22.142  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.142  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.142  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.142  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 12:26:22.151  1042  1521 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 12:26:22.152  1042  1521 D WifiNative-wlan0: SET update_config 1: returned true
08-16 12:26:22.152  1042  1521 D WifiConfigStore: Loading config and enabling all networks 
08-16 12:26:22.152  1042  1521 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 12:26:22.153  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:22.153  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-16 12:26:22.154  1042  1521 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 12:26:22.154  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:22.154  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:22.154  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:22.154  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:22.155  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 12:26:22.155  1042  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 12:26:22.155  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:22.155  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:22.155  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:22.155  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:22.165  1042  1521 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 12:26:22.178  1042  1521 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 12:26:22.178  1042  1521 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 12:26:22.181  1042  1521 D WifiStateMachine: enableVerboseLogging : level 2
08-16 12:26:22.181  1042  1521 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-16 12:26:22.182  1042  1521 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 12:26:22.182  1042  1521 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 12:26:22.182  1042  1521 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 12:26:22.182  1042  1521 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 12:26:22.183  1042  1521 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 12:26:22.183  1042  1521 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 12:26:22.184  1042  1521 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 12:26:22.184  1042  1521 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 12:26:22.184  1042  1521 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 12:26:22.184  1042  1521 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 12:26:22.185  1042  1521 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 12:26:22.185  1042  1521 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 12:26:22.185  1042  1521 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 12:26:22.187  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-16 12:26:22.187  1925  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 12:26:22.187  1925  2258 D WfdsService: Set the WFDS Monitor: true
08-16 12:26:22.187  1925  2258 D WfdsMonitor: WfdsMonitorThread create
08-16 12:26:22.187  1042  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 12:26:22.187  1925  2258 D WfdsMonitor: WFDS Monitor is created and started
,08-16 12:26:22.187  1925  2258 D WfdsService: WiFi: Supplicant connection re-established
08-16 12:26:22.187  1042  1521 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 12:26:22.188  1042  1521 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 12:26:22.188  1042  1521 D WifiNative-HAL: Setting external_sim to 1
08-16 12:26:22.188  1042  1521 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 12:26:22.188  1925  7196 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 12:26:22.188  1042  1521 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 12:26:22.188  1042  1521 I WifiNative-HAL: startHal
08-16 12:26:22.188  1042  1521 D wifi    : setting scan oui 0xaf65b700
08-16 12:26:22.189  1925  7196 E CtrlSupplicant: Succeed to open control connection
08-16 12:26:22.189  1042  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 12:26:22.189  1042  1521 I WifiNative-HAL: startHal
08-16 12:26:22.189  1925  7196 E CtrlSupplicant: Succeed to open monitor connection
08-16 12:26:22.189  1042  1521 D wifi    : setting scan oui 0xaf65b700
08-16 12:26:22.189  1925  7196 D WfdsMonitor: Supplicant connection established
08-16 12:26:22.189  1925  2258 D WfdsService: Connected to the supplicant for wfds
08-16 12:26:22.189  1042  1521 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 12:26:22.190  1042  1521 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 12:26:22.190  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 12:26:22.190  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 12:26:22.192  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 12:26:22.192  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:26:22.192  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:26:22.193  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:26:22.193  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 12:26:22.193  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 12:26:22.194  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 12:26:22.194  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:26:22.194  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:26:22.194  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 12:26:22.194  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:26:22.194  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:26:22.195  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:26:22.195  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 12:26:22.195  7172  7172 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 12:26:22.196  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 12:26:22.196  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:26:22.196  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:26:22.196  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 12:26:22.197  1042  1521 E WifiNative: : [196,193,399 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 12:26:22.197  1042  1521 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 12:26:22.198  1042  1521 D WifiNative-wlan0: RECONNECT: returned true
08-16 12:26:22.198  1042  1521 D WifiNative-wlan0: doString: [STATUS]
08-16 12:26:22.199  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 12:26:22.199  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 12:26:22.199  1042  1521 D WifiNative-wlan0:    returned wpa_state=SCANNING, p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:26:22.199  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:22.200  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:26:22.200  1042  1520 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:26:22.201  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 12:26:22.201  1042  1042 D RttService: SCAN_AVAILABLE : 3
08-16 12:26:22.201  1042  1539 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.202  1042  1539 I WifiNative-HAL: startHal
08-16 12:26:22.202  1042  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf65b700
08-16 12:26:22.202  1042  1539 D wifi    : failed to get capabilities : -3
08-16 12:26:22.202  1042  1539 E WifiScanningService: could not get scan capabilities
08-16 12:26:22.202  1042  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.202   314   900 D CommandListener: Setting iface cfg
08-16 12:26:22.202   314   900 D CommandListener: Trying to bring up p2p0
08-16 12:26:22.203  1042  1520 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 12:26:22.203  1042  1520 D LGWifiP2pService: P2pEnablingState
08-16 12:26:22.203  1042  1520 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.203  1042  1520 D LGWifiP2pService: P2p socket connection successful
08-16 12:26:22.203  1042  1520 D LGWifiP2pService: P2pEnabledState
08-16 12:26:22.205  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 12:26:22.205  1042  1521 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:26:22.206  1042  1521 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 12:26:22.206  1925  1925 D WfdsService: WifiP2pState is changed : true
08-16 12:26:22.206  1925  2258 D WfdsService: Receive the WFDS_ENABLE Method
08-16 12:26:22.206  1925  2258 D WfdsService: Set the WFDS Monitor: true
08-16 12:26:22.206  1925  2258 D WfdsService: Connected to the supplicant for wfds
08-16 12:26:22.206  1925  2258 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 12:26:22.206  1042  1521 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 12:26:22.206  7172  7172 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 12:26:22.206  1042  1521 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 12:26:22.207  1925  2258 D WfdsService: selectPreferredScanChannel [36]
08-16 12:26:22.207  1925  2258 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 12:26:22.207  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=196203  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:26:22.208  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=196204  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:26:22.208  1042  1521 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 12:26:22.209  1042  1521 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 12:26:22.209  1042  1521 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 12:26:22.209  1042  1521 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 12:26:22.210  7172  7172 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 12:26:22.210  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:22.210  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:22.210  1042  1520 D LGWifiP2pService: sending p2p connection changed broadcast
,08-16 12:26:22.211  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.211  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.211  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 12:26:22.211  1042  1521 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 12:26:22.212  1042  1521 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 12:26:22.212  1042  1520 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 12:26:22.212  1042  1521 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,08-16 12:26:22.212  1042  1521 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 12:26:22.212  7172  7172 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 12:26:22.215  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 12:26:22.215  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:22.215  1042  1521 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 12:26:22.215  1925  1925 D WfdsService: isConnected: false
08-16 12:26:22.216  1042  1521 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 12:26:22.216  1042  1520 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 12:26:22.216  1042  1520 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 12:26:22.216  1042  1521 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 12:26:22.216  1042  1520 D WifiNative-p2p0: SET device_name G3: returned true
08-16 12:26:22.216  1042  1520 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 12:26:22.217  1042  1520 D LGWifiP2pService: before postfix = G3
08-16 12:26:22.217  1042  1520 D WifiServerServiceExt: postfix byte check : 2
08-16 12:26:22.217  1042  1520 D LGWifiP2pService: after postfix = G3
08-16 12:26:22.217  1042  1520 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 12:26:22.217  1042  1520 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 12:26:22.217  1042  1520 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 12:26:22.216  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 12:26:22.217  1042  1520 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 12:26:22.217  1042  1520 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 12:26:22.218  1042  1520 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 12:26:22.218  1042  1520 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 12:26:22.219  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 12:26:22.219  7172  7172 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.220  7172  7172 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 12:26:22.220  7172  7172 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.220  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:26:22.220  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.221  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.221  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.221  1042  7195 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.221  1042  7195 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.221  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.221  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 12:26:22.221  1042  1521 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 12:26:22.221  7172  7172 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.222  1042  1521 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:26:22.222  1042  1521 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:26:22.222  1925  7196 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.222  1925  7196 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.222  1042  1521 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:26:22.222  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 12:26:22.223  1042  7195 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.223  1042  7195 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.223  1042  1520 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 12:26:22.223  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.223  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.223  1042  1520 D WifiNative-HAL: p2pGetDeviceAddress
08-16 12:26:22.223  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 12:26:22.223  7172  7172 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:22.223  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 12:26:22.223  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:22.223  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:22.223  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:22.224  1042  1521 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 12:26:22.224  1042  1521 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 12:26:22.225  1042  1521 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 12:26:22.225  1042  1521 D WifiNative-wlan0: doBoolean: SCAN
08-16 12:26:22.226  1042  1521 D WifiNative-wlan0: SCAN: returned false
08-16 12:26:22.227  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=196224  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:26:22.228  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=196225  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:26:22.229  1042  1521 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:22.232  1042  1520 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 12:26:22.238  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.238  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.239  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 12:26:22.239  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:22.239  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:22.239  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:22.239  1042  1042 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 12:26:22.239  1042  1521 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:22.240  1042  1521 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:22.240  1042  1520 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 12:26:22.240  1042  1520 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 12:26:22.241  1042  1520 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 12:26:22.241  1042  1520 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 12:26:22.241  1042  1520 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 12:26:22.241  1042  1520 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 12:26:22.242  1042  1520 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 12:26:22.242  1042  1520 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 12:26:22.243  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 12:26:22.243  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 12:26:22.243  1925  1925 D WfdsService: Update P2p Interface State: 3
08-16 12:26:22.244  1042  1521 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:22.244  1042  1521 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:22.245  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:22.246  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:22.246  1042  1042 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 12:26:22.254  1042  1520 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 12:26:22.254  1042  1520 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 12:26:22.254  1042  1520 D LGWifiP2pService: InactiveState
08-16 12:26:22.255  1042  1520 D LGWifiP2pService: InactiveState{ when=-33ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.255  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-33ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.255  1042  1520 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 12:26:22.256  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 12:26:22.256  7172  7172 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.257  7172  7172 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 12:26:22.257  7172  7172 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.258  7172  7172 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.260  1925  7196 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:26:22.261  1925  7196 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.261  1925  7196 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.261  1042  7195 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:26:22.261  1042  7195 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.261  1042  1520 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 12:26:22.261  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.261  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:22.261  1042  7195 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.261  1042  1520 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.261  1042  7195 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.261  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.261  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.261  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.261  1042  1520 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.261  1042  7195 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:22.261  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.261  1042  7195 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.261  1042  1520 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:26:22.261  1042  7195 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 12:26:22.262  1042  7195 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:26:22.262  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.262  1042  1520 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:22.263  1042  1042 E WifiServerServiceExt: No p2p device connected
08-16 12:26:22.264  1925  2258 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 12:26:22.264  7178  7178 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:22.265  7178  7178 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:26:22.268  7178  7178 D PhoneMonitor: Register our PhoneStateListener
08-16 12:26:22.280  7178  7178 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 12:26:22.282  7178  7178 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 12:26:22.293  7178  7178 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 12:26:22.294  7178  7178 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 12:26:22.294  7178  7178 D TelephonyAutoProfiling: [parse] Load xml
08-16 12:26:22.301  7178  7178 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 12:26:22.301  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 12:26:22.301  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 12:26:22.302  7178  7178 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 12:26:22.302  7178  7178 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 12:26:22.309  7178  7178 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-16 12:26:22.335  1042  1942 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7205 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 12:26:22.335  1042  1942 I ActivityManager: Killing 6674:com.lge.eula/1000 (adj 15): empty #17
08-16 12:26:22.381  1042  1924 W libprocessgroup: failed to open /acct/uid_1000/pid_6674/cgroup.procs: No such file or directory
,08-16 12:26:22.636  1042  1942 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7229 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 12:26:22.642  1042  1942 I ActivityManager: Killing 5511:com.lge.bnr/1000 (adj 15): empty #17
08-16 12:26:22.691  1042  1924 W libprocessgroup: failed to open /acct/uid_1000/pid_5511/cgroup.procs: No such file or directory
,08-16 12:26:22.789  1042  1915 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7246 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 12:26:22.792  1042  1915 I ActivityManager: Killing 6645:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 12:26:22.844  7172  7172 E wpa_supplicant: USIM:  scard_init function
08-16 12:26:22.845  7172  7172 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 12:26:22.850  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 12:26:22.850  1042  7195 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 12:26:22.850  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 12:26:22.850  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-16 12:26:22.850  1042  7195 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 12:26:22.850  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 12:26:22.850  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 12:26:22.853  1042  1521 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 12:26:22.856  1042  1521 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 12:26:22.858  1042  1521 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 12:26:22.859  1042  1521 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-16 12:26:22.859  1042  1521 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 12:26:22.899  1042  2034 W libprocessgroup: failed to open /acct/uid_10097/pid_6645/cgroup.procs: No such file or directory
,08-16 12:26:22.923  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=196919  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 12:26:22.926  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=196923  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 12:26:22.949  7246  7246 I art     : Almond Protected OAT
,08-16 12:26:22.961  7172  7172 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 12:26:22.963  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 12:26:22.963  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 12:26:22.964  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 12:26:22.964  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 12:26:22.964  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:22.964  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 12:26:22.964  1042  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 12:26:22.965  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=196961  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 12:26:22.967  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:22.967  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:22.967  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.967  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.968  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 12:26:22.968  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:22.968  1042  1042 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 12:26:22.968  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=196962  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 12:26:22.969  1042  1521 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=196965
08-16 12:26:22.969  1042  1521 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=196966
08-16 12:26:22.969  7172  7172 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:26:22.970  7172  7172 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:26:22.970  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:22.970  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:22.970  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 12:26:22.970  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:26:22.970  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:22.971  1042  7195 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:26:22.971  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 12:26:22.972  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:26:22.972  1042  7195 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:26:22.972  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:22.972  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:22.974  1042  1521 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=196970
08-16 12:26:22.975  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=196971
08-16 12:26:22.975  1042  1521 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=196972
08-16 12:26:22.976  1042  1521 ,E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=196972  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:26:22.979  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.979  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.979  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 12:26:22.982  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=196979  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:26:22.986  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.986  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:22.987  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 12:26:22.987  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:22.987  1042  1042 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 12:26:22.987  1042  1521 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.988  1042  1521 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.988  1042  1521 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.989  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.991  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:22.991  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=196988  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 12:26:22.992  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=196988  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 12:26:22.992  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:22.992  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:22.993  1042  1521 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=196989
08-16 12:26:22.993  1042  1521 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=196990
,08-16 12:26:22.994  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:22.994  1042  1521 D WifiNative-wlan0: doString: [STATUS]
08-16 12:26:22.994  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:22.994  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:22.995  1042  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:26:22.996  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:22.996  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:22.997  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:22.997  1042  1521 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 12:26:23.003  1042  1521 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 12:26:23.003  1042  1521 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-16 12:26:23.006  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.006  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.006  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:26:23.008  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.008  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.008  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:26:23.014  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:23.014  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:23.014  1042  1521 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 12:26:23.014  1042  1527 D ConnectivityService: Got NetworkAgent Messenger
08-16 12:26:23.014  1042  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:26:23.014  1042  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:26:23.014  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 12:26:23.014  1042  1527 D ConnectivityService: NetworkAgent connected
08-16 12:26:23.015  1042  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:26:23.015  1042  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:26:23.015  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.017  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:23.017  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:23.019  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:26:23.021  1042  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:26:23.021  1042  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:26:23.021  1042  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:26:23.021  1042  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:26:23.021  1042  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:26:23.025  1042  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.025  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.025  1042  1520 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.026  1042  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:26:23.027   314   900 D CommandListener: Setting iface cfg
08-16 12:26:23.029  7246  7246 D WeatherApplication: removeAccount
08-16 12:26:23.030  7246  7246 D WeatherApplication: Account.length = 0
08-16 12:26:23.030  1042  1521 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 12:26:23.031  7246  7246 E WeatherApplication: OPERATOR:OPEN
08-16 12:26:23.031  1042  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=197028  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 12:26:23.032  1042  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=197028  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:23.036  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=197029  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:23.037  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:23.037  1042  1042 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 12:26:23.037  7246  7246 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:23
08-16 12:26:23.038  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:23.038  1042  1042 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 12:26:23.039  1042  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=197036  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:23.040  1042  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=197036  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:23.040  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=197037  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:23.041  7246  7246 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:26:23.041  7246  7246 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:26:23.043  1042  7276 D DhcpStateMachine: StoppedState
,08-16 12:26:23.043  1042  7276 D DhcpStateMachine: StoppedState{ when=-12ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.043  1042  7276 D DhcpStateMachine: WaitBeforeStartState
08-16 12:26:23.043  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:150583] from screen [on:0 period:-1830599485] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:26:23.044  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1830599484] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:26:23.044  1042  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:26:23.044  7246  7246 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:26:23.048  7246  7246 D WeatherAncestor: connectivity changed - connection : true
08-16 12:26:23.049  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.049  7246  7246 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 12:26:23.051  1042  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 12:26:23.052  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.052  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.053  1042  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.053  1042  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.054  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.054  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 12:26:23.054  1042  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 12:26:23.055  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:26:23.055  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:26:23.057  1042  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:26:23.057  1042  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:26:23.058  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:26:23.058  1042  1521 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:26:23.059  7246  7246 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:26:23.059  7246  7246 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:26:23.059  7246  7246 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 12:26:23.059  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:23.059  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:26:23.061  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:23.061  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:26:23.061  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
08-16 12:26:23.062  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
08-16 12:26:23.062  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 12:26:23.062  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 12:26:23.063  1042  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 12:26:23.063  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 12:26:23.063  1042  1521 D WifiNative-wlan0: SET ps 0: returned true
08-16 12:26:23.063  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 12:26:23.064  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 12:26:23.064  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 12:26:23.064  1042  1521 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 12:26:23.064  1042  1521 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:26:23.064  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1497f6e5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.064  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1497f6e5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.064  1042  7276 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.064  1042  7276 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 12:26:23.064  1042  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-16 12:26:23.069   314   900 D CommandListener: Setting iface cfg
08-16 12:26:23.070   314   900 D CommandListener: Trying to bring up wlan0
08-16 12:26:23.071  1042  1521 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 12:26:23.071  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.072  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.072  1042  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.073  1042  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.073  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.074  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:23.074  1042  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 12:26:23.074  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 12:26:23.075  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 12:26:23.075  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:26:23.075  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.075  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:26:23.075  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.080  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:26:23.081  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-16 12:26:23.081  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 12:26:23.081  1042  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 12:26:23.081  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:23.096  7246  7246 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 12:26:23.096  7246  7246 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:23
08-16 12:26:23.097  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:26:23.098  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:26:23.099  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:26:23.099  1042  1521 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 12:26:23.099  1042  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 12:26:23.100  1042  1527 D ConnectivityService: ignoring duplicate network state non-change
08-16 12:26:23.154  1042  2034 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7278 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 12:26:23.157  1042  2034 I ActivityManager: Killing 2138:com.lge.music/u0a34 (adj 15): empty #17
,08-16 12:26:23.191   318  2134 V AudioFlinger: 2138 died, releasing its sessions
08-16 12:26:23.191   318  2134 V AudioFlinger:  pid 1837 @ 0
08-16 12:26:23.191   318  2134 V AudioFlinger:  pid 3315 @ 1
08-16 12:26:23.191   318  2134 V AudioFlinger:  pid 3315 @ 2
,08-16 12:26:23.215  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 12:26:23.216  1042  1527 D ConnectivityService: Adding iface wlan0 to network 101
08-16 12:26:23.217  1042  1915 W libprocessgroup: failed to open /acct/uid_10034/pid_2138/cgroup.procs: No such file or directory
,08-16 12:26:23.233  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:23.233  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:23.234  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.234  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.234  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:26:23.239  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.240  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.240  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.240  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:26:23.243  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 12:26:23.244  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.244  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.244  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:26:23.248  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 12:26:23.250  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.250  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:23.251  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:26:23.251  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 12:26:23.254  1042  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 12:26:23.254  1042  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 12:26:23.255  1042  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 12:26:23.255  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:23.255  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:23.255  1042  1521 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 12:26:23.256   314   900 E Netd    : netlink response contains error (File exists)
08-16 12:26:23.256  1042  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 12:26:23.257  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.257  1042  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 12:26:23.257  1042  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 12:26:23.257  1042  1527 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 12:26:23.258  1042  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 12:26:23.258  1042  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 12:26:23.258  1042  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 12:26:23.258  1042  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 12:26:23.259  1042  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:23.259  1042  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:23.259  1042  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:26:23.259  1042  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.259  1042  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 12:26:23.259  1042  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-16 12:26:23.259  1042  1527 D ConnectivityService:    accepting network in place of null
08-16 12:26:23.259  1042  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.260  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.260  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.260  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 12:26:23.260  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:26:23.260  1042  1521 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.261  1042  1521 D WIFI    :   my score=60, my filter=[ Transports: ,WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:23.261  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:23.261  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 12:26:23.262  1042  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 12:26:23.262  1042  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 12:26:23.263  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:26:23.263   314  7298 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 12:26:23.264  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:23.265  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:26:23.265  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.266  1042  7276 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 12:26:23.267  1042  7276 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 12:26:23.267  1042  7276 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 12:26:23.254  7299  7299 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:23.272  1042  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:23.272  1042  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 12:26:23.272  1042  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 12:26:23.254  7299  7299 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:23.273  1042  1527 D ConnectivityService: validation of new default Network = false
08-16 12:26:23.273  1042  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 12:26:23.273  1042  1527 D DSQN    : enableDataServiceNotify 
08-16 12:26:23.273  1042  1527 D DSQN    : start dsqn bin
08-16 12:26:23.277  1042  1042 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 12:26:23.277  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:26:23.277  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:26:23.277  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-16 12:26:23.282  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:23.282  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:26:23.282  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.285  1042  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 12:26:23.285  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.285  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:23.285  1042  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:23.274  7300  7300 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:23.286  7299  7299 I dhcpcd  : version 5.5.6 starting
08-16 12:26:23.286  1586  2083 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 12:26:23.287  7299  7299 E dhcpcd  : get_duid: m
08-16 12:26:23.287  7299  7299 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 12:26:23.287  7299  7299 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 12:26:23.274  7300  7300 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:23.302  1042  1519 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 12:26:23.308  7300  7300 E DSQN    : DSQN ssw
08-16 12:26:23.320   314  7298 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 12:26:23.325  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:26:23.326  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.327  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.329  1802  7304 I CheckinService: active receiver: enabled
,08-16 12:26:23.337  1802  7304 I CheckinService: Preparing to send checkin request
08-16 12:26:23.337  1802  7304 I EventLogService: Accumulating logs since 1471343029616
08-16 12:26:23.344  7299  7299 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 12:26:23.344  7299  7299 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 12:26:23.344  7299  7299 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:26:23.344  7299  7299 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 12:26:23.344  7299  7299 D dhcpcd  : wlan0: sending REQUEST (xid 0xcbd53aa5), next in 3.34 seconds
08-16 12:26:23.359   314  7298 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 12:26:23.378  1802  7304 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 12:26:23.381  7299  7299 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 12:26:23.389   280   460 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:26:23.389   280   460 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 12:26:23.389   280   460 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:26:23.390  7278  7313 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 12:26:23.391   280   460 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:26:23.391   280   460 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 12:26:23.391   280   460 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:26:23.393  7278  7313 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 12:26:23.397   314   899 D LGDataListener: argv[0]=dsqncommand
08-16 12:26:23.397   314   899 D LGDataListener: argv[1]=wlan0
08-16 12:26:23.397   314   899 D LGDataListener: argv[2]=1
08-16 12:26:23.397   314   899 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 12:26:23.398  1042  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 12:26:23.398  1042  1117 D DSQN    : start to monitor internet connection
08-16 12:26:23.399   280   460 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:26:23.399   280   460 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 12:26:23.399   280   460 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:26:23.399  7278  7317 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 12:26:23.401   280   460 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:26:23.401   280   460 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 12:26:23.401   280   460 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:26:23.402  7278  7317 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 12:26:23.403  7299  7299 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 12:26:23.403  7299  7299 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 12:26:23.403  7299  7299 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 12:26:23.403  7299  7299 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 12:26:23.404  7299  7299 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:26:23.404  7299  7299 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 12:26:23.404  7299  7299 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 12:26:23.404  7299  7299 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 12:26:23.463  1042  1915 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7328 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 12:26:23.505  7328  7328 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 12:26:23.506  7328  7328 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 12:26:23.526  7328  7328 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 12:26:23.526  7328  7328 I MultiDex: install
08-16 12:26:23.526  7328  7328 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 12:26:23.534  7328  7328 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 12:26:23.580  7278  7278 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 12:26:23.588  7278  7278 I LibraryLoader: Loading: webviewchromium
08-16 12:26:23.590  7278  7278 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7596-7599)
08-16 12:26:23.590  7278  7278 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:26:23.597  7278  7278 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {894821c}
,08-16 12:26:23.599  7278  7278 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:26:23.599  7278  7278 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 12:26:23.614  7278  7278 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 12:26:23.615  7278  7278 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:26:23.616  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:26:23 GMT], X-Android-Received-Millis=[1471343183616], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471343183397]}
08-16 12:26:23.616  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 12:26:23.616  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 12:26:23.617  1042  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 12:26:23.617  1042  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 12:26:23.617  1042  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:23.617  1042  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:23.617  1042  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:26:23.617  1042  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 12:26:23.618  1042  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 12:26:23.618  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.618  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:23.619  1042  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:23.620  1586  2083 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 12:26:23.620  1042  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.621  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 12:26:23.621  1042  1521 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.621  1042  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:23.622  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:23.622  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:26:23.632  7278  7278 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 12:26:23.633  7278  7278 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 12:26:23.634  7278  7278 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 12:26:23.640   318  1369 V AudioPolicyService: registerClient() client 0xb557c360, uid 10093
08-16 12:26:23.641  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:26:23.642  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.643  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:23.643  7278  7378 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 12:26:23.661  7278  7278 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:26:23.661  7278  7278 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:26:23.661  7278  7278 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:26:23.661  7278  7278 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:26:23.661  7278  7278 I Adreno-EGL: Remote Branch: 
08-16 12:26:23.661  7278  7278 I Adreno-EGL: Local Patches: 
08-16 12:26:23.661  7278  7278 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:26:23.669  1042  7276 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 12:26:23.671  1042  7276 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 12:26:23.671  1042  7276 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 12:26:23.671  1042  7276 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 12:26:23.671  1042  7276 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 12:26:23.671  1042  7276 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:26:23.671  1042  7276 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 12:26:23.671  1042  7276 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 12:26:23.671  1042  7276 D DhcpStateMachine: RunningState
08-16 12:26:23.743  7278  7278 I NSApplication: Starting up...
,08-16 12:26:23.802  1042  2014 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7391 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 12:26:23.803  1042  2014 I ActivityManager: Killing 6536:com.android.vending/u0a44 (adj 15): empty #17
,08-16 12:26:23.849  7328  7345 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:26:23.849  7328  7345 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:26:23.865  1042  2034 W libprocessgroup: failed to open /acct/uid_10044/pid_6536/cgroup.procs: No such file or directory
,08-16 12:26:23.892  7391  7391 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:26:23.933  7408  7408 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 12:26:24.012  7408  7408 I dex2oat : dex2oat took 78.762ms (threads: 4)
,08-16 12:26:24.028  7328  7345 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:26:24.028  7328  7345 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:26:24.028  7328  7345 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:26:24.028  7328  7345 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:26:24.028  7328  7345 I Adreno-EGL: Remote Branch: 
08-16 12:26:24.028  7328  7345 I Adreno-EGL: Local Patches: 
08-16 12:26:24.028  7328  7345 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:26:24.061  1042  1971 D WifiServiceImplEx: setWifiEnabled: false pid=6803, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 12:26:24.061  1042  1971 D WifiService: setWifiEnabled: false pid=6803, uid=10118
08-16 12:26:24.061  1042  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:26:24.081  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 12:26:24.081  1042  1521 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-16 12:26:24.081  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 12:26:24.081  1042  1042 D Ulp_jni : JNI:system_update. Event-4
,08-16 12:26:24.082  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:24.082  1042  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:24.083  1042  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:24.083  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:26:24.083  1042  1521 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 12:26:24.083  1042  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:26:24.083  1042  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:26:24.084  1042  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:26:24.084  1042  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:26:24.098  1042  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:26:24.098  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:26:24.098  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.098  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:26:24.098  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.098  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:26:24.098  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:24.099  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:26:24.099  1042  7276 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.099   314   900 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:26:24.123  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 12:26:24.123  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-16 12:26:24.129  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:24.129  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:24.131  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-16 12:26:24.131  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.132  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.132  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:26:24.132  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-16 12:26:24.139  1042  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:24.140  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 12:26:24.141  1042  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.141  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.141  1042  1520 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@d995ce3
08-16 12:26:24.142  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.145  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 12:26:24.147  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:24.147  1042  1521 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 12:26:24.151  1042  1520 D LGWifiP2pService: P2pDisablingState
08-16 12:26:24.151  1042  1520 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.151  1042  1520 D LGWifiP2pService: p2p socket connection lost
08-16 12:26:24.152  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.152  1042  1520 D LGWifiP2pService: P2pDisabledState
08-16 12:26:24.152  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.152  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:26:24.152  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 12:26:24.152  1042  1042 D RttService: SCAN_AVAILABLE : 1
08-16 12:26:24.152  1042  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 12:26:24.152  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:26:24.153  1042  1539 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.153  1042  1540 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.153  1042  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.153  1042  1520 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.153  7172  7172 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:26:24.154  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:26:24.154  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:24.154  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:26:24.154  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:26:24.154  1925  1925 D WfdsService: WifiP2pState is changed : false
08-16 12:26:24.154  1925  2258 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 12:26:24.155  1925  2258 D WfdsService: Set the WFDS Monitor: false
08-16 12:26:24.155  1925  2258 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:26:24.155  1925  2258 D WfdsService: STATE : WfdsDisabledState - enter
,08-16 12:26:24.155  1925  7196 D CtrlSupplicant: Received on exit socket, terminate
08-16 12:26:24.155  1925  2259 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 12:26:24.155  1925  7196 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 12:26:24.155  1925  7196 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 12:26:24.155  1925  7196 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 12:26:24.156  1925  2258 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 12:26:24.164  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:24.164  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:24.165  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.168  7328  7345 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:26:24.168  7328  7345 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:26:24.168  7328  7345 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:26:24.168  7328  7345 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:26:24.168  7328  7345 I Adreno-EGL: Remote Branch: 
08-16 12:26:24.168  7328  7345 I Adreno-EGL: Local Patches: 
08-16 12:26:24.168  7328  7345 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:26:24.172   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:26:24.172  1042  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 12:26:24.172  1042  1527 D DSQN    : disableDataServiceNotify
08-16 12:26:24.172  1042  1527 D DSQN    : stop dsqn bin
08-16 12:26:24.173  1042  1521 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 12:26:24.174  1042  1521 D WifiNative-p2p0: TERMINATE: returned true
08-16 12:26:24.174  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:24.174  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:24.174  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:24.174  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-16 12:26:24.175  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.175  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.175  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:26:24.176  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 12:26:24.179  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 12:26:24.179  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:24.179  1042  1042 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 12:26:24.180  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:24.180  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:24.180  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:24.180  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:24.181  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 12:26:24.181  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:24.181  1042  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 12:26:24.181  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:24.181  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 12:26:24.182  1042  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:24.184  1586  2083 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 12:26:24.184  1042  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 12:26:24.184  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.184  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.184  1042  7275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 12:26:24.186  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:24.186  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:24.186  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:24.186  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.186  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:24.186  1042  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 12:26:24.186  1042  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 12:26:24.186  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:26:24.186  1042  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:24.187  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:26:24.187  1042  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:24.187  1042  1527 D ConnectivityService: Checking for replacement network to handle request, NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:24.187  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.187  1042  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:24.187  1042  1527 D NetworkManagementService: Removing idletimer
08-16 12:26:24.187  1042  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.187  1042  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 12:26:24.187  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:24.188  1042  1521 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:24.188  1042  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:24.188  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:26:24.190  1042  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:26:24.190  1042  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:26:24.190  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:26:24.191  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:26:24.191  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:26:24.191  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:26:24.191  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:26:24.191  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:26:24.191  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:26:24.191  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-16 12:26:24.219  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:26:24.220  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.221  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:26:24.230  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:26:24.231  6345  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:26:24.247  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:24.248  7328  7345 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:26:24.248  7328  7345 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:26:24.248  7328  7345 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:26:24.248  7328  7345 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:26:24.248  7328  7345 I Adreno-EGL: Remote Branch: 
08-16 12:26:24.248  7328  7345 I Adreno-EGL: Local Patches: 
08-16 12:26:24.248  7328  7345 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:26:24.255  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:26:24.256  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:26:24.256  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:24.256  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:26:24.256  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 12:26:24.256  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.256  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.258  7118  7118 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:26:24.260  7118  7118 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ef5abfd
08-16 12:26:24.260  7118  7118 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:26:24.260  7118  7118 D AppUp4:CustFacade: isPhone : true
08-16 12:26:24.260  7118  7118 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:26:24.260  7118  7118 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:26:24.263  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:24.264  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 12:26:24.265  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:24.266  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:24.271  7144  7144 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 12:26:24.271  4660  7429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:26:24.278  4660  7431 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:24.278  4660  7431 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 12:26:24.284  7172  7172 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 12:26:24.284  7172  7172 I wpa_supplicant: monitor socket send errors count : 1
08-16 12:26:24.284  7172  7172 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
08-16 12:26:24.285  1042  7195 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 12:26:24.285  1042  7195 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 12:26:24.285  1042  1527 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-16 12:26:24.287  3315  3315 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:26:24.287  3315  3315 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:24.288  3315  3315 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 12:26:24.293  7144  7433 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.293  7178  7178 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 12:26:24.293  7178  7178 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 12:26:24.299  7028  7435 W FormManager: Network not available. Please check & try again.
08-16 12:26:24.304  7246  7246 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:24
08-16 12:26:24.304  7028  7436 V FormManager: Network unavailable.
,08-16 12:26:24.306  7172  7172 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:26:24.306  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 12:26:24.306  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:26:24.306  1042  7195 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:26:24.306  1042  7195 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 12:26:24.306  7172  7172 W wpa_supplicant: USIM:  scard_deinit function
08-16 12:26:24.306  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:24.306  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:24.307  1042  1521 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=198304
08-16 12:26:24.307  1042  1521 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=198304
08-16 12:26:24.308  1042  1521 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198304  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:26:24.308  1042  1521 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198305  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:26:24.308  1042  1119 D Tethering: InitialState.processMessage what=4
08-16 12:26:24.309  1042  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 12:26:24.309  1042  1521 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:24.309  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:24.310  1042  7276 D DhcpStateMachine: StoppedState
08-16 12:26:24.310  1042  7276 D DhcpStateMachine: StoppedState{ when=-155ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:24.310  1042  1521 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 12:26:24.311  1042  1521 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 12:26:24.311  7246  7246 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:26:24.311  7246  7246 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:26:24.312  7246  7246 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:26:24.312  7246  7246 D WeatherAncestor: connectivity changed - connection : true
08-16 12:26:24.312  7246  7246 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@302fd343
08-16 12:26:24.312  7246  7246 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:26:24.312  7028  7436 V FormManager: Network unavailable.
08-16 12:26:24.313  7246  7246 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:26:24.313  7246  7246 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:26:24.313  7246  7246 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:26:24.313  7246  7246 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:24
08-16 12:26:24.340  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:26:24.340  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:26:24.340  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:26:24.340  6923  6923 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:26:24.340  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:26:24.341  6923  6923 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:26:24.341  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 12:26:24.341  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:26:24.341  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:26:24.341  6923  6923 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:26:24.341  6923  6923 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 12:26:24.348  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:24.350  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:26:24.355  7028  7441 W FormManager: Network not available. Please check & try again.
08-16 12:26:24.358  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.361  7028  7442 V FormManager: Network unavailable.
08-16 12:26:24.364  7028  7442 V FormManager: Network unavailable.
,08-16 12:26:24.372  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:24.374  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:26:24.380  7028  7444 W FormManager: Network not available. Please check & try again.
,08-16 12:26:24.382  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.382  7028  7445 V FormManager: Network unavailable.
08-16 12:26:24.386  7028  7445 V FormManager: Network unavailable.
08-16 12:26:24.394  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:26:24.395  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:26:24.396  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:26:24.398  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:24.401  4660  7446 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:26:24.401  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:24.404  4660  7447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:26:24.404  4660  7447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:26:24.406  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.411  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.418  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:24.418  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:24.421  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:26:24.431  7172  7172 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 12:26:24.433  1042  7195 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 12:26:24.433  1042  7195 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 12:26:24.433  1042  7195 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 12:26:24.433  1042  1521 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-16 12:26:24.453  1042  2014 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7448 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-16 12:26:24.466   314  7466 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 12:26:24.467  1042  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 12:26:24.469  1802  7304 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-16 12:26:24.474  1802  7304 I CheckinService: active receiver: disabled
,08-16 12:26:24.533  7448  7448 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 12:26:24.533  7448  7448 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 12:26:24.535  1042  1521 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 12:26:24.535  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:24.535  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:24.535  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:24.537  1925  1925 D WfdsService: Supplicant Connection state is changed : false
,08-16 12:26:24.537  1925  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 12:26:24.537  1925  2258 D WfdsService: Set the WFDS Monitor: false
08-16 12:26:24.537  1925  2258 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:26:24.538  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:24.538  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:26:24.540  2459  2459 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:24.542  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:24.542  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:24.542  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 12:26:24.543  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:24.543  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:24.543  1042  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 12:26:24.543  1042  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 12:26:24.544  7448  7448 V [BNRBootReceiver]: Boot Receiver Return
08-16 12:26:24.549  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:24.550  7448  7448 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 12:26:24.558  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.568  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.575  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:24.576  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:26:24.578  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:26:24.583  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 12:26:24.589  6923  6923 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-16 12:26:24.594  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:24.603  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.617  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:26:24.628  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:24.629  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:24.629  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:24.633  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:24.650  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.657  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.668  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:24.669  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:26:24.670  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 12:26:24.676  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:24.691  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.704  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.718  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:24.719  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:26:24.720  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:24.730  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:24.752  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.772  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:26:24.792  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:24.793  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:24.795  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 12:26:24.807  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:24.827  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.838  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.850  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:24.851  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:24.852  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:24.863  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:24.883  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.895  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:26:24.906  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:24.906  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:24.915  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:24.925  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:24.934  6703  7094 D UEI.SmartControl: Internal timer expired: 2
08-16 12:26:24.934  6703  7094 D UEI.SmartControl: unbind internal service
08-16 12:26:24.950  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:24.963  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:24.980  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:24.982  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:24.984  6977  6977 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:24.992  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:24.998  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 12:26:25.007  1042  1526 D WifiService: New client listening to asynchronous messages
,08-16 12:26:25.009  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:25.014  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:25.020  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:25.021  6703  7088 D serial_port: close(fd = 24)
08-16 12:26:25.024  6703  7088 I UEI.SmartControl: Serial port is closed.
08-16 12:26:25.029  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:25.030  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:25.031  6977  6977 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 12:26:25.032  6977  6977 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 12:26:25.033  6977  6977 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 12:26:25.039  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:25.044  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 12:26:25.046  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:25.050  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:25.055  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:25.062  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:25.063  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:25.064  6977  6977 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 12:26:25.066  6977  6977 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 12:26:25.066  6977  6977 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 12:26:25.068  1042  1915 I ActivityManager: Killing 6906:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 12:26:25.099  1042  1059 W libprocessgroup: failed to open /acct/uid_10037/pid_6906/cgroup.procs: No such file or directory
,08-16 12:26:25.104  2066  2066 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 12:26:25.120  2066  2066 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 12:26:25.123  2066  2066 D c       : Getting all permits...
08-16 12:26:25.123  2066  2066 D a       : Opening database...
08-16 12:26:25.134  2066  2066 D a       : Opening database auth.proximity.permit_store...
,08-16 12:26:25.136  2066  2066 D a       : Closing database...
08-16 12:26:25.153  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:25.162  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:26:25.162  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:25.162  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:25.166  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:25.172  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:25.185  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:25.186  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:26:25.192  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:26:25.198  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:25.206  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 12:26:25.206  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:25.207  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:26:25.212  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:25.220  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:25.232  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:26:25.232  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:26:25.235  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:26:25.240  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:25.243  6943  6943 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:26:25.243  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:25.243  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:25.247  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:25.255  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:26:25.263  6977  6977 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:25.264  6977  6977 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:25.266  6977  6977 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 12:26:25.279  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:26:25.283  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:26:25.290  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:25.303  7028  7475 W FormManager: Network not available. Please check & try again.
,08-16 12:26:25.314  7028  7476 V FormManager: Network unavailable.
08-16 12:26:25.317  2066  2066 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-16 12:26:25.320  7028  7476 V FormManager: Network unavailable.
,08-16 12:26:25.339  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:26:25.339  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 12:26:25.341  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:26:25.347  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:25.353  4660  7477 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:26:25.360  4660  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:26:25.360  4660  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:26:25.361  6943  6943 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 12:26:25.361  6943  6943 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:26:25.361  6943  6943 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:25.366  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:26:25.373  7028  7480 W FormManager: Network not available. Please check & try again.
08-16 12:26:25.376  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:25.382  7028  7481 V FormManager: Network unavailable.
,08-16 12:26:25.387  7028  7481 V FormManager: Network unavailable.
,08-16 12:26:26.054  1042  1521 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1830596474] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:26:26.068  1042  1521 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1830596460] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:26:26.274  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:26.284  1042  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:26:26.290  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:26:26.294  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:26.298  1042  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:26.301  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:26:26.302  6345  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:26:26.315  5754  5754 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 12:26:26.334  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:26.369  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:26:26.370  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:26.370  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:26:26.370  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 12:26:26.375  7118  7118 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:26:26.379  7118  7118 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ef5abfd
08-16 12:26:26.379  7118  7118 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:26:26.379  7118  7118 D AppUp4:CustFacade: isPhone : true
08-16 12:26:26.385  1042  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 12:26:26.389  7118  7118 I art     : WaitForGcToComplete blocked for 10.112ms for cause DisableMovingGc
08-16 12:26:26.390  7118  7118 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:26:26.390  7118  7118 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:26:26.395  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:26.395  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:26:26.397  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:26.401  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:26:26.419  7144  7144 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 12:26:26.423  4660  7500 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:26:26.436  4660  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:26.437  4660  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:26:26.597  1042  1971 I art     : Explicit concurrent mark sweep GC freed 123339(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.708ms total 168.883ms
,08-16 12:26:26.618  3315  3315 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:26:26.618  3315  3315 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:26.619  3315  3315 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 12:26:26.619  3315  3315 D PhoneState: setPdpRejectCasuse : false
08-16 12:26:26.622  7178  7178 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 12:26:26.622  7178  7178 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 12:26:26.634  7028  7508 W FormManager: Network not available. Please check & try again.
08-16 12:26:26.637  7246  7246 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:26
,08-16 12:26:26.639  7028  7509 V FormManager: Network unavailable.
,08-16 12:26:26.640  7246  7246 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:26:26.640  7246  7246 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:26:26.641  7246  7246 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:26:26.641  7028  7509 V FormManager: Network unavailable.
08-16 12:26:26.641  7246  7246 D WeatherAncestor: connectivity changed - connection : true
08-16 12:26:26.641  7246  7246 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@302fd343
08-16 12:26:26.642  7246  7246 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:26:26.642  7246  7246 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:26:26.642  7246  7246 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:26:26.642  7246  7246 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:26:26.643  7246  7246 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:26
08-16 12:26:26.660  7144  7510 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:26:27.083  1042  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:26:27.084  1042  1996 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 12:26:27.126  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:26:27.126  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:26:27.126  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-16 12:26:27.127  1042  1119 D BluetoothManagerService: Message: 1
08-16 12:26:27.127  1042  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 12:26:27.165  1042  1119 D BluetoothManagerService: Message: 20
08-16 12:26:27.166  1042  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@282f9221:true
,08-16 12:26:27.171  7047  7047 D BluetoothAdapterState: make
08-16 12:26:27.176  7047  7047 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 12:26:27.176  7047  7047 I bluedroid-qcom: init
08-16 12:26:27.178  7047  7522 I BluetoothAdapterState: Entering OffState
08-16 12:26:27.178  7047  7047 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 12:26:27.178  7047  7047 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 12:26:27.178  7047  7047 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 12:26:27.178  7047  7047 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:26:27.179  7047  7047 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 12:26:27.181  7047  7047 I bluedroid-qcom: get_profile_interface socket
08-16 12:26:27.181  7047  7047 I bluedroid-qcom: get_profile_interface map_client
,08-16 12:26:27.186  7047  7526 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 12:26:27.174  7525  7525 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:27.188  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.184  7525  7525 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:27.198  7525  7525 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 12:26:27.198  7525  7525 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 12:26:27.198  7525  7525 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 12:26:27.203  1042  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:26:27.203  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.209  7525  7525 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 12:26:27.210  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:26:27.213  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:27.222  1042  1119 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:26:27.227  7525  7525 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 12:26:27.228  7525  7525 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 12:26:27.232  7047  7526 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 12:26:27.239  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:26:27.242  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:27.246  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 12:26:27.247  1042  1119 D BluetoothManagerService: Message: 40
08-16 12:26:27.247  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 12:26:27.248  7047  7065 I bluedroid-qcom: config_hci_snoop_log
08-16 12:26:27.249  1042  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 12:26:27.249  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 12:26:27.253  7047  7526 D BluetoothAdapterProperties: Name is: G3
,08-16 12:26:27.257  7047  7522 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 12:26:27.257  7047  7522 D BluetoothAdapterProperties: Setting state to 11
08-16 12:26:27.257  7047  7522 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 12:26:27.261  7047  7522 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 12:26:27.263  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:26:27.264  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 12:26:27.265  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:27.265  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 12:26:27.265  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-16 12:26:27.268  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:27.269  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:26:27.277  1042  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:27.281  7047  7522 D BluetoothBondStateMachine: make
08-16 12:26:27.283  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:26:27.286  7047  7539 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 12:26:27.286  7047  7522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.286  7047  7522 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 12:26:27.286  7047  7522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.286  7047  7522 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 12:26:27.287  7047  7522 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 12:26:27.288  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:27.291  6923  6923 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 12:26:27.295  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:27.298  6345  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:26:27.300  7047  7522 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:27.303  5754  5754 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 12:26:27.307  7047  7047 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-16 12:26:27.308  7047  7047 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:27.308  7047  7047 V BluetoothPbapReceiver: ***********state = 11
08-16 12:26:27.313  7047  7522 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:27.314  7047  7047 D HeadsetService: Received start request. Starting profile...
08-16 12:26:27.315  7047  7047 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:26:27.315  7047  7047 D LGBluetoothHfpAdapter: Version 1.6
08-16 12:26:27.318  7047  7047 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 12:26:27.320  7047  7047 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 12:26:27.322  7047  7047 D HeadsetStateMachine: make
08-16 12:26:27.324  1042  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.325  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:26:27.331  7047  7522 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:27.332  5754  5754 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 12:26:27.338  7047  7522 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:27.366  7047  7047 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:26:27.366  7047  7047 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:26:27.388  1042  1924 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7546 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 12:26:27.403  7047  7522 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:27.409   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 20.307ms
,08-16 12:26:27.409  7047  7047 D HeadsetStateMachine: max_hf_connections = 1
08-16 12:26:27.409  7047  7047 I bluedroid-qcom: get_profile_interface handsfree
08-16 12:26:27.410  1042  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:27.411  1042  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:27.411  7047  7047 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 12:26:27.412   318   318 V AudioPolicyService: registerClient() client 0xb1025d20, uid 1002
08-16 12:26:27.412   318  2134 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:26:27.412   318  2134 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:26:27.412   318  2134 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:26:27.412  7047  7047 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 12:26:27.413   318  1369 V AudioFlinger: registerClient() client 0xb1035b68, pid 7047
08-16 12:26:27.413   318  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:27.413   318  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:27.413  1586  2054 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:27.413  1586  2054 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:27.414  1042  1558 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:27.414  1042  1558 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:27.414  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:27.414  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:27.414  3315  3331 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:27.414  3315  3331 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:27.414  7047  7065 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:27.414   318  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:27.414   318  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:27.415  1042  1692 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:27.415  1042  1692 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:27.415  1586  1609 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:27.415  1586  1609 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:27.415  3315  3330 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:27.415  3315  3330 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:27.415  7047  7065 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 12:26:27.415  7047  7065 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:27.415  7047  7065 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 12:26:27.415  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:27.415  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:27.415  7047  7047 V ToneGenerator: Create Track: 0xb4927680
08-16 12:26:27.415  7047  7047 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 12:26:27.415  7047  7047 V AudioTrack: set() streamType 8, sampleRate 0, format ,1, frameCount 0, flags 0004
08-16 12:26:27.415   318  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:26:27.415   318  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:26:27.415   318  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:26:27.415   318  1368 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:26:27.416   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:26:27.417   318  2134 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:26:27.417   318  2134 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 12:26:27.417   318  2134 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:26:27.417   318  2134 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:26:27.417  7047  7047 V AudioSystem: getLatency() output 2, latency 50
08-16 12:26:27.417  7047  7047 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 12:26:27.417  7047  7047 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 12:26:27.417   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:26:27.417   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:26:27.417   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:26:27.417   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:26:27.417   318  1369 V AudioFlinger: createTrack() lSessionId: 22
08-16 12:26:27.419  7047  7047 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 12:26:27.421   318  2131 V AudioFlinger: acquiring 22 from 7047, for 7047
08-16 12:26:27.421   318  2131 V AudioFlinger:  added new entry for 22
08-16 12:26:27.421  7047  7047 V ToneGenerator: ToneGenerator INIT OK, time: 201430
08-16 12:26:27.421  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.422  7047  7544 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 12:26:27.422  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
,08-16 12:26:27.425  7047  7047 D A2dpService: Received start request. Starting profile...
08-16 12:26:27.425  7047  7522 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:27.425  7047  7047 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 12:26:27.426   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 350us total 16.969ms
08-16 12:26:27.426  7047  7047 V Avrcp   : make
08-16 12:26:27.427  7047  7047 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 12:26:27.427  7047  7047 I bluedroid-qcom: get_profile_interface avrcp
08-16 12:26:27.428  7047  7544 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:26:27.428  7047  7544 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:26:27.428  7047  7544 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 12:26:27.429   318  1368 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7047
08-16 12:26:27.429   318  1368 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 12:26:27.429   318  1368 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 12:26:27.429   318  1368 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 12:26:27.429   318  1368 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 12:26:27.429   318  1368 V voice   : voice_set_parameters: exit with code(0)
08-16 12:26:27.429   318  1368 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 12:26:27.429   318  1368 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 12:26:27.429   318  1368 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 12:26:27.429   318  1368 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 12:26:27.429   318  1368 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 12:26:27.429   318  1368 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 12:26:27.429  7047  7544 V ToneGenerator: ToneGenerator destructor
08-16 12:26:27.429  7047  7544 V ToneGenerator: stopTone
08-16 12:26:27.429  7047  7544 V ToneGenerator: Delete Track: 0xb4927680
08-16 12:26:27.429  7047  7544 V AudioTrack: ~AudioTrack, releasing session id from 7047 on behalf of 7047
08-16 12:26:27.430   318   318 V AudioFlinger: releasing 22 from 7047 for 7047
08-16 12:26:27.431   318   318 V AudioFlinger:  decremented refcount to 0
08-16 12:26:27.431   318   318 V AudioFlinger: purging stale effects
08-16 12:26:27.431   318   318 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 12:26:27.431   318   318 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 12:26:27.431   318  1273 V AudioPolicyService: AudioCommandThread() waking up
08-16 12:26:27.431   318  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 12:26:27.431   318  1273 V AudioPolicyManager: releaseOutput() 2
08-16 12:26:27.431   318  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 12:26:27.431   318   318 V AudioFlinger: PlaybackThread::Track destructor
08-16 12:26:27.431   318   318 V AudioFlinger: removeClient_l() pid 7047, calling pid 318
08-16 12:26:27.434  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:27.441   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 282us total 13.909ms
08-16 12:26:27.447  7047  7047 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 12:26:27.449  7047  7047 E AudioManager: No RCC entry present to update
08-16 12:26:27.449  7047  7047 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 12:26:27.451  7047  7522 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:27.453  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:26:27.453  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.453  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:26:27.453  7047  7047 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 12:26:27.453  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 12:26:27.454  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 12:26:27.454  7047  7047 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 12:26:27.454  7118  7118 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:26:27.461  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 12:26:27.462  7118  7118 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ef5abfd
08-16 12:26:27.462  7118  7118 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:26:27.462  7118  7118 D AppUp4:CustFacade: isPhone : true
08-16 12:26:27.462  7118  7118 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:26:27.462  7118  7118 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:26:27.464  7047  7522 V LGMDMManager: Create singleton instance
,08-16 12:26:27.465  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.465  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:26:27.466  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:27.467  7047  7522 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 12:26:27.495  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:26:27.501  7144  7144 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 12:26:27.501  4660  7567 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:26:27.503  4660  7568 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.503  4660  7568 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:26:27.515  3315  3315 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 12:26:27.515  3315  3315 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.515  3315  3315 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 12:26:27.518  7178  7178 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 12:26:27.518  7178  7178 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 12:26:27.527  7028  7572 W FormManager: Network not available. Please check & try again.
,08-16 12:26:27.527  7246  7246 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:27
08-16 12:26:27.528  7144  7569 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:27.531  7028  7573 V FormManager: Network unavailable.
08-16 12:26:27.531  7246  7246 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:26:27.531  7246  7246 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:26:27.532  7246  7246 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:26:27.533  7246  7246 D WeatherAncestor: connectivity changed - connection : true
08-16 12:26:27.533  7246  7246 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@302fd343
08-16 12:26:27.534  7028  7573 V FormManager: Network unavailable.
08-16 12:26:27.536  7246  7246 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:26:27.536  7246  7246 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:26:27.536  7246  7246 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:26:27.536  7246  7246 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:26:27.536  7246  7246 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:27
08-16 12:26:27.537  1042  1942 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:26:27.537  1042  1942 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:26:27.539  7546  7546 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 12:26:27.539  7546  7546 W LG Account v2.2: No ProfileInfo entries
08-16 12:26:27.539  7546  7546 I LG Account v2.2: isEnabled: false
08-16 12:26:27.539  7546  7546 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 12:26:27.539  7546  7546 I Feature : [Lifetracker]Country: EU
08-16 12:26:27.539  7546  7546 I Feature : [Lifetracker]Operator: OPEN
08-16 12:26:27.539  7546  7546 I Feature : [Lifetracker]Ranking support: false
08-16 12:26:27.540  7546  7546 I Feature : [Lifetracker]Comfort support: false
08-16 12:26:27.540  7546  7546 I Feature : [Lifetracker]Accessory: true
08-16 12:26:27.540  7546  7546 I Feature : [Lifetracker]Health device: true
08-16 12:26:27.540  7546  7546 I Feature : [Lifetracker]Extra Pedometer: false
08-16 12:26:27.540  7546  7546 I Feature : [Lifetracker]Blood glucose device: false
08-16 12:26:27.540  7546  7546 I Feature : [Lifetracker]Device Number: 3
,08-16 12:26:27.552  6923  6923 D BluetoothPermissionRequest: onReceive
08-16 12:26:27.560  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 12:26:27.561  6345  6345 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:26:27.562  6345  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:26:27.573  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:26:27.578  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:26:27.578  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.578  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:26:27.578  7118  7118 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 12:26:27.579  7118  7118 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:26:27.581  7118  7118 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ef5abfd
08-16 12:26:27.581  7118  7118 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:26:27.581  7118  7118 D AppUp4:CustFacade: isPhone : true
08-16 12:26:27.582  7118  7118 D AppUp4:CustModeStarterReceiver: begin check event
,08-16 12:26:27.582  7118  7118 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:26:27.584  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.585  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:26:27.585  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:26:27.587  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:26:27.590  1042  1692 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 12:26:27.591  4660  7576 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:26:27.591  7144  7144 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 12:26:27.592  4660  7577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.592  4660  7577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:26:27.595  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:26:27.598  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 12:26:27.599  7047  7047 I BluetoothA2dpServiceJni: classInitNative
08-16 12:26:27.599  7047  7047 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:26:27.599  7047  7047 D A2dpStateMachine: make
,08-16 12:26:27.601  7047  7047 I bluedroid-qcom: get_profile_interface a2dp
08-16 12:26:27.601  7047  7581 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 12:26:27.602  7047  7047 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:26:27.602  7047  7047 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 12:26:27.603  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.603  7144  7578 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:27.603  7047  7047 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 12:26:27.604  7047  7579 D A2dpStateMachine: Enter Disconnected: -2
08-16 12:26:27.604  7047  7047 D HidService: Received start request. Starting profile...
08-16 12:26:27.605  7047  7047 I bluedroid-qcom: get_profile_interface hidhost
08-16 12:26:27.605  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.605  7047  7047 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:26:27.606  7047  7047 D HealthService: Received start request. Starting profile...
08-16 12:26:27.607  7047  7047 I bluedroid-qcom: get_profile_interface health
08-16 12:26:27.607  7028  7583 W FormManager: Network not available. Please check & try again.
08-16 12:26:27.607  7047  7047 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:26:27.607  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.607  7047  7047 D HeadsetStateMachine: Proxy object connected
08-16 12:26:27.608  7047  7047 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 12:26:27.608  7047  7047 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 12:26:27.609  7028  7584 V FormManager: Network unavailable.
08-16 12:26:27.609  7047  7047 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 12:26:27.610  7028  7584 V FormManager: Network unavailable.
08-16 12:26:27.610  7047  7047 D PanService: Received start request. Starting profile...
08-16 12:26:27.610  7047  7047 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 12:26:27.610  7047  7047 I bluedroid-qcom: get_profile_interface pan
,08-16 12:26:27.613  3315  3315 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:26:27.613  3315  3315 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:27.613  3315  3315 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 12:26:27.616  7178  7178 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 12:26:27.616  7178  7178 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 12:26:27.616  7047  7047 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 12:26:27.616  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.617  7047  7544 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 12:26:27.617  7047  7544 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 12:26:27.617  7047  7544 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 12:26:27.619  7047  7047 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:27.619  7047  7047 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 12:26:27.622  7047  7047 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:26:27.622  7047  7047 D BtGatt.GattService: Received start request. Starting profile...
08-16 12:26:27.622  7047  7047 D BtGatt.GattService: start()
08-16 12:26:27.622  7047  7047 I bluedroid-qcom: get_profile_interface gatt
08-16 12:26:27.623  7047  7047 D BtGatt.AdvertiseManager: advertise manager created
,08-16 12:26:27.624  7246  7246 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:27
08-16 12:26:27.625  7246  7246 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:26:27.625  7246  7246 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:26:27.625  7246  7246 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:26:27.625  7246  7246 D WeatherAncestor: connectivity changed - connection : true
08-16 12:26:27.626  7246  7246 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@302fd343
08-16 12:26:27.626  7246  7246 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:26:27.626  7246  7246 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:26:27.626  7246  7246 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:26:27.626  7246  7246 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:26:27.626  7246  7246 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:26:27
08-16 12:26:27.627  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.628  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.628  7047  7047 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 12:26:27.628  7047  7047 V BluetoothMapService: BluetoothMapBinder()
08-16 12:26:27.629  7047  7047 D BluetoothMapService: Received start request. Starting profile...
08-16 12:26:27.629  7047  7047 D BluetoothMapService: start()
08-16 12:26:27.631  7047  7047 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 12:26:27.631  7047  7047 D BluetoothMapEmailAppObserver: createReceiver()
08-16 12:26:27.632  7047  7047 D BluetoothMapEmailAppObserver: initObservers()
,08-16 12:26:27.632  7047  7047 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 12:26:27.636  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:27.639  7047  7047 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:27.641  7047  7047 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:27.643  7047  7047 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:27.643  7047  7047 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 12:26:27.645  7047  7047 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:27.647  7047  7047 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 12:26:27.647  7047  7047 V BluetoothMapService: Handler(): got msg=1
08-16 12:26:27.647  7047  7522 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 12:26:27.647  7047  7522 I bluedroid-qcom: enable
08-16 12:26:27.647  7047  7591 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 12:26:27.647  7047  7591 I bt-btu  : btu_task pending for preload complete event
08-16 12:26:27.647  7047  7522 I bt_hci_bdroid: init
,08-16 12:26:27.648  7047  7522 I bt_vendor: bt-vendor : init
08-16 12:26:27.648  7047  7522 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 12:26:27.648  7047  7522 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 12:26:27.648  7047  7522 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 12:26:27.648  7047  7522 D bt_userial_mct: userial_init
08-16 12:26:27.649  7047  7522 D bt_hci_bdroid: set_power 1
08-16 12:26:27.649  7047  7522 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 12:26:27.649  7047  7522 I bt_vendor: Starting hciattach daemon
08-16 12:26:27.649  7047  7522 I bt_vendor: try to set true
08-16 12:26:27.650  7047  7047 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:27.634  7594  7594 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:27.634  7594  7594 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:27.651  7047  7047 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:27.651  7047  7047 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:27.651  7047  7047 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:27.651  7047  7047 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:27.651  7047  7047 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 12:26:27.660  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 12:26:27.716  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 12:26:27.726  7602  7602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 12:26:27.750  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 12:26:27.762  7605  7605 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 12:26:27.776  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 12:26:27.785  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 12:26:27.804  7609  7609 I libmdmdetect: ESOC framework not supported
08-16 12:26:27.805  7609  7609 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 12:26:27.812  7609  7609 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 12:26:27.812  7609  7609 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-16 12:26:27.812  7609  7609 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 12:26:27.812  7609  7609 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 12:26:27.812  7609  7609 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 12:26:27.812  7609  7609 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 12:26:27.812  7609  7609 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 12:26:27.844  7609  7610 E QC-QMI  : qmi_client [7609] 14: failed to locate client data
,08-16 12:26:27.846   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 12:26:27.846   470   470 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-16 12:26:27.886  7611  7611 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 12:26:27.914  7615  7615 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 12:26:27.950  7047  7522 I bt_vendor: bluetooth satus is on
,08-16 12:26:27.952  7047  7522 D bt_hci_bdroid: preload
08-16 12:26:27.952  7047  7593 D bt_userial_mct: userial_open(port:0)
08-16 12:26:27.952  7047  7593 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 12:26:27.956  7047  7593 I bt_vendor: Done intiailizing UART
08-16 12:26:27.957  7047  7593 I bt_vendor: Done intiailizing UART
08-16 12:26:27.957  7047  7593 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 12:26:27.958  7047  7593 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 12:26:27.958  7047  7591 I bt-btu  : btu_task received preload complete event
08-16 12:26:27.958  7047  7617 D bt_userial_mct: Entering userial_read_thread()
,08-16 12:26:27.958  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 12:26:27.958  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 12:26:27.961  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 12:26:27.965  7047  7591 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 12:26:28.014  7047  7591 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 12:26:28.014  7047  7591 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0220061 
08-16 12:26:28.014  7047  7591 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0220061 
,08-16 12:26:28.029  7047  7526 E bt-btif : Calling BTA_HhEnable
,08-16 12:26:28.029  7047  7526 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-16 12:26:28.030  7047  7526 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 12:26:28.031  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 12:26:28.031  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 12:26:28.031  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 12:26:28.032  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 12:26:28.033  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 12:26:28.033  7047  7526 D BluetoothAdapterProperties: Name is: G3
08-16 12:26:28.034  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:26:28.035  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 12:26:28.036  7047  7526 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:26:28.036  7047  7526 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:26:28.036  7047  7526 D bt_hci_bdroid: postload
08-16 12:26:28.037  7047  7593 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:26:28.037  7047  7591 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 12:26:28.038  7047  7526 D bte_conf: Device ID record 1 : primary
08-16 12:26:28.038  7047  7526 D bte_conf:   vendorId            = 00c4
08-16 12:26:28.038  7047  7526 D bte_conf:   vendorIdSource      = 0001
08-16 12:26:28.038  7047  7526 D bte_conf:   product             = 13a1
08-16 12:26:28.038  7047  7526 D bte_conf:   version             = 1000
08-16 12:26:28.038  7047  7526 D bte_conf:   clientExecutableURL = 
08-16 12:26:28.038  7047  7526 D bte_conf:   serviceDescription  = 
08-16 12:26:28.038  7047  7526 D bte_conf:   documentationURL    = 
08-16 12:26:28.038  7047  7526 D bte_conf: bte_load_did_conf no section named DID2.
08-16 12:26:28.040  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:28.040  7047  7593 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:26:28.041  7047  7522 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 12:26:28.041  7047  7522 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:26:28.042  7047  7522 D BluetoothAdapterProperties: State =  11
08-16 12:26:28.042  7047  7522 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 12:26:28.042  7047  7522 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120,
08-16 12:26:28.034  7619  7619 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 12:26:28.043  7047  7593 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:26:28.043  7047  7522 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 12:26:28.044  7047  7526 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 12:26:28.045  7047  7526 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 12:26:28.034  7619  7619 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:28.050  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:28.052  7047  7522 I BluetoothAdapterState: Entering On State
08-16 12:26:28.051  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 12:26:28.053  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 12:26:28.056  7047  7591 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:28.056  7047  7591 W bt-smp  : Plain text(LSB ~ MSB) = 10 4b 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:28.056  7047  7591 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f 21 9f a5 94 13 aa 24 d6 0a 3a 98 03 85 b7 aa 
08-16 12:26:28.056  7047  7591 W bt-btm  : Stopping oneshot timer
08-16 12:26:28.057  7047  7593 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 12:26:28.059  7047  7522 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 12:26:28.059  7047  7522 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 12:26:28.060  7047  7617 E bt_mct  : hci lib postload completed
08-16 12:26:28.060  7047  7522 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 12:26:28.062  7047  7522 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:28.065  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:28.069  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:26:28.071  7047  7526 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:26:28.071  7047  7526 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 12:26:28.072  6923  6939 D BluetoothMap: onBluetoothStateChange: up=true
08-16 12:26:28.074  7047  7591 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:28.074  7047  7591 W bt-smp  : Plain text(LSB ~ MSB) = 54 6b 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:28.074  7047  7591 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b 57 c5 73 48 2c af 27 ba d0 ae a2 a1 3d 35 d8 
08-16 12:26:28.075  7047  7591 W bt-btm  : Stopping oneshot timer
08-16 12:26:28.080  1837  2675 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:26:28.081  6923  6923 D BluetoothMap: Proxy object connected
08-16 12:26:28.081  6923  6923 D MapProfile: Bluetooth service connected
08-16 12:26:28.081  6923  6923 D BluetoothMap: getConnectedDevices()
08-16 12:26:28.085  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:26:28.085  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:26:28.088  7047  7591 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:28.088  7047  7591 W bt-smp  : Plain text(LSB ~ MSB) = 5e 87 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:28.088  7047  7591 W bt-smp  : Encrypted text(LSB ~ MSB) = 3e 35 66 a3 2e 63 c5 7e bf 76 d6 e8 1d 55 2c 47 
08-16 12:26:28.088  7047  7591 W bt-btm  : Stopping oneshot timer
08-16 12:26:28.089  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:26:28.089  1042  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:26:28.090  1042  1042 D BluetoothHeadset: Proxy object connected
08-16 12:26:28.091  6923  6938 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 12:26:28.092  7047  7065 V BluetoothMapService: getConnectedDevices()
08-16 12:26:28.096  1042  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:26:28.097  6923  7027 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 12:26:28.099  7047  7591 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:28.099  7047  7591 W bt-smp  : Plain text(LSB ~ MSB) = fb 90 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:28.099  7047  7591 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 6f 1f c0 37 0b 97 46 0a f4 77 2f 58 15 4a 65 
08-16 12:26:28.099  7047  7591 W bt-btm  : Stopping oneshot timer
08-16 12:26:28.101  6923  6923 D BluetoothInputDevice: Proxy object connected
08-16 12:26:28.101  6923  6923 D HidProfile: Bluetooth service connected
08-16 12:26:28.101  1042  1042 D BluetoothA2dp: Proxy object connected
08-16 12:26:28.102  7047  7522 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 12:26:28.105  6923  6938 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:26:28.105  6923  6938 D BluetoothPan: onBluetoothStateChange call bindService
08-16 12:26:28.109  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:26:28.112  6923  6923 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:26:28.113  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:26:28.114  6923  6923 D PanProfile: Bluetooth service connected
08-16 12:26:28.116  1042  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 12:26:28.116  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 12:26:28.117  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 12:26:28.117  1042  1119 D BluetoothManagerService: Message: 40
08-16 12:26:28.117  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 12:26:28.118  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:26:28.121  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:28.121  1925  2085 D LGBluetoothAPIService: Message: 1
08-16 12:26:28.121  1925  2085 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-16 12:26:28.122  7047  7591 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:28.122  7047  7591 W bt-smp  : Plain text(LSB ~ MSB) = 47 cf 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:28.122  7047  7591 W bt-smp  : Encrypted text(LSB ~ MSB) = 4a c0 72 90 c7 6c 7c 8f da 1f f6 93 ea ae 78 c4 
08-16 12:26:28.122  7047  7591 W bt-btm  : Stopping oneshot timer
08-16 12:26:28.127  1925  2085 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 12:26:28.129  7047  7047 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:28.129  7047  7047 D BluetoothMapService: STATE_ON
08-16 12:26:28.129  7626  7626 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 12:26:28.134  7047  7047 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 12:26:28.134  7047  7047 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 12:26:28.136  7047  7047 V BluetoothMapService: Handler(): got msg=1
08-16 12:26:28.137  7047  7047 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 12:26:28.138  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 12:26:28.138  1925  2085 D LGBluetoothAPIService: Message: 100
08-16 12:26:28.138  1925  2085 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 12:26:28.138  7047  7631 D BluetoothMapMasInstance: MAS initSocket()
08-16 12:26:28.139  7047  7631 D BluetoothMapMasInstance:   masId = 00
08-16 12:26:28.139  7047  7631 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 12:26:28.139  7047  7631 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 12:26:28.139  7047  7631 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 12:26:28.141  6803  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 12:26:28.141  1042  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:28.143  7047  7631 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:28.146  7047  7631 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 12:26:28.146  7047  7631 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 12:26:28.146  7047  7631 D BluetoothMapMasInstance: Accepting socket connection...
,08-16 12:26:28.149  7047  7526 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:26:28.150  7047  7526 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 12:26:28.156  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:28.156  7047  7047 V BluetoothPbapService: Pbap Service onCreate
08-16 12:26:28.156  7047  7047 V BluetoothPbapService: Starting PBAP service
08-16 12:26:28.158  7047  7047 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 12:26:28.158  7047  7047 V BluetoothPbapService: Pbap Service onBind
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:28.160  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:26:28.161  7047  7047 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:28.161  7047  7047 V BluetoothPbapService: state: 12
08-16 12:26:28.162  7047  7047 V BluetoothPbapService: Handler(): got msg=1
08-16 12:26:28.163  6923  6923 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 12:26:28.164  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:28.165  7047  7047 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 12:26:28.166  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:28.166  7047  7634 V BluetoothPbapService: Pbap Service initSocket
08-16 12:26:28.167  1042  1119 D BluetoothManagerService: Message: 30
08-16 12:26:28.167  1042  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:28.168  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:28.168  7047  7634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:28.169  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:28.169  7047  7634 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 12:26:28.170  7047  7634 V BluetoothPbapService: Succeed to create listening socket 
08-16 12:26:28.170  7047  7634 V BluetoothPbapService: Accepting socket connection...
08-16 12:26:28.170  6923  6923 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 12:26:28.174  1042  1119 D BluetoothManagerService: Message: 30
08-16 12:26:28.179  6923  6923 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 12:26:28.181  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 12:26:28.184  6923  6923 D BluetoothPbap: Proxy object connected
08-16 12:26:28.185  7047  7047 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-16 12:26:28.185  7047  7047 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:28.185  7047  7047 V BluetoothPbapReceiver: ***********state = 12
08-16 12:26:28.185  6923  6923 D PbapServerProfile: Bluetooth service connected
08-16 12:26:28.185  6923  6923 D BluetoothA2dp: Proxy object connected
08-16 12:26:28.186  6923  6923 D A2dpProfile: Bluetooth service connected
,08-16 12:26:28.189  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:26:28.190  2066  2066 D c       : Getting all permits...
08-16 12:26:28.190  2066  2066 D a       : Opening database...
08-16 12:26:28.191  6923  6923 D BluetoothHeadset: Proxy object connected
08-16 12:26:28.192  6923  6923 D HeadsetProfile: Bluetooth service connected
08-16 12:26:28.195  2066  2066 D a       : Opening database auth.proximity.permit_store...
08-16 12:26:28.195  2066  2066 D a       : Closing database...
08-16 12:26:28.200  6923  6923 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:26:28.207  6923  6923 D BluetoothPermissionRequest: onReceive
08-16 12:26:28.209  6923  6923 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 12:26:28.212  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:26:28.221  7047  7047 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-16 12:26:28.223  7047  7047 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 12:26:28.234  7047  7047 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 12:26:28.267  7047  7047 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 12:26:28.267  7047  7047 V BtOppService: onCreate
,08-16 12:26:28.274  7047  7047 V BluetoothOppNotification: send message
08-16 12:26:28.279  7047  7047 V BtOppService: Starting RfcommListener
08-16 12:26:28.295  7047  7638 V BtOppService: Deleted complete outbound shares, number =  0
,08-16 12:26:28.297  7047  7638 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 12:26:28.301  7047  7047 D BluetoothOppPreference: Dumping Names:  
08-16 12:26:28.301  7047  7047 D BluetoothOppPreference: {}
08-16 12:26:28.301  7047  7047 D BluetoothOppPreference: Dumping Channels:  
08-16 12:26:28.301  7047  7047 D BluetoothOppPreference: {}
08-16 12:26:28.302  7047  7638 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 12:26:28.302  7047  7047 V BtOppService: onStartCommand
08-16 12:26:28.303  7047  7638 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26333e7c on behalf of 
08-16 12:26:28.304  7047  7641 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:26:28.305  7047  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:26:28.306  7047  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c39305 on behalf of 
08-16 12:26:28.307  7047  7641 V BluetoothOppNotification: update too frequent, put in queue
08-16 12:26:28.308  7047  7641 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:26:28.308  7047  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:26:28.308  7047  7047 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:28.309  7047  7047 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 12:26:28.311  7047  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14ef4f5a on behalf of 
08-16 12:26:28.313  7047  7641 V BluetoothOppNotification: update too frequent, put in queue
08-16 12:26:28.314  7047  7047 V BluetoothOppNotification: new notify threadi!
08-16 12:26:28.315  7047  7641 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 12:26:28.315  7047  7047 V BluetoothOppNotification: send delay message
08-16 12:26:28.316  7047  7047 V BtOppService: start RfcommListener
08-16 12:26:28.317  7047  7642 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 12:26:28.319  7047  7642 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dae658b on behalf of 
08-16 12:26:28.319  7047  7047 V BtOppService: RfcommListener started
08-16 12:26:28.319  7047  7047 V BtOppService: ContentObserver received notification
08-16 12:26:28.320  7047  7642 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 12:26:28.321  7047  7642 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 12:26:28.322  7047  7047 V BtOppService: ContentObserver received notification
08-16 12:26:28.322  7047  7642 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ab3c668 on behalf of 
08-16 12:26:28.323  7047  7642 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 12:26:28.323  7047  7644 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:26:28.323  7047  7644 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:26:28.325  7047  7642 V BluetoothOppNotification: outbound notification was removed.
08-16 12:26:28.325  7047  7642 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:26:28.326  7047  7644 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@316f5a81 on behalf of 
08-16 12:26:28.326  7047  7642 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ac30726 on behalf of 
08-16 12:26:28.326  7047  7643 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 12:26:28.327  7047  7642 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 12:26:28.327  1042  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:28.327  7047  7644 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 12:26:28.328  7047  7643 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:28.329  7047  7643 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 12:26:28.329  7047  7642 V BluetoothOppNotification: inbound notification was removed.
08-16 12:26:28.329  7047  7642 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:26:28.330  7047  7643 V BtOppRfcommListener: Started RFCOMM listener....
08-16 12:26:28.330  7047  7643 I BtOppRfcommListener: Accept thread started.
08-16 12:26:28.331  7047  7643 V BtOppRfcommListener: Accepting connection...
08-16 12:26:28.331  7047  7642 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e9bcf67 on behalf of 
08-16 12:26:28.346  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
,08-16 12:26:28.346  7047  7047 V BluetoothFtpService: Ftp Service onCreate
08-16 12:26:28.346  7047  7047 I BluetoothFtpService: Ftp Service onCreate
08-16 12:26:28.346  7047  7047 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:26:28.346  7047  7047 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:28.346  7047  7047 V BluetoothFtpService: Starting Listening on sockets
08-16 12:26:28.347  7047  7047 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:28.347  7047  7047 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:28.347  7047  7047 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:28.347  7047  7047 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:28.347  7047  7047 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 12:26:28.347  7047  7047 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 12:26:28.349  7047  7047 V BluetoothFtpService: Handler(): got msg=1
08-16 12:26:28.350  7047  7047 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,08-16 12:26:28.350  7047  7047 V BluetoothFtpService: Ftp Service initSocket
08-16 12:26:28.354  1042  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:28.355  7047  7047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:28.357  7047  7047 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 12:26:28.357  7047  7047 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 12:26:28.359  7047  7646 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 12:26:28.374  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:28.374  7047  7047 V BluetoothSapService: Sap Service onCreate
08-16 12:26:28.377  7047  7047 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:26:28.377  7047  7047 V BluetoothSapService: state: 12
08-16 12:26:28.377  7047  7047 V BluetoothSapService: Starting SAP server process
08-16 12:26:28.379  7047  7047 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 12:26:28.381  7047  7648 V BluetoothSapService: Sap Service initRfcommSocket
08-16 12:26:28.374  7647  7647 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:28.374  7647  7647 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:28.383  1042  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:28.384  7047  7648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:28.385  7047  7648 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 12:26:28.385  7047  7648 V BluetoothSapService: Succeed to create listening socket 
08-16 12:26:28.385  7047  7648 V BluetoothSapService: Accepting socket connection...
08-16 12:26:28.400  7278  7315 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 12:26:28.411  7647  7647 V BT_SAP  : Event pipe created
,08-16 12:26:28.411  7647  7647 V BT_SAP  : create_server_socket qcom.sap.server
08-16 12:26:28.411  7647  7647 V BT_SAP  : created socket fd 6
08-16 12:26:29.154  1042  1520 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:29.155  1042  1520 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:26:29.176  1042  1521 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 12:26:29.177  1042  1521 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 12:26:29.247  1042  2034 I ActivityManager: Killing 7448:com.lge.bnr/1000 (adj 15): empty #17
,08-16 12:26:29.282  1042  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_7448/cgroup.procs: No such file or directory
,08-16 12:26:29.318  7047  7047 V BluetoothOppNotification: new notify threadi!
,08-16 12:26:29.319  7047  7047 V BluetoothOppNotification: send delay message
,08-16 12:26:29.332  7047  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 12:26:29.334  7047  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27e6fa80 on behalf of 
08-16 12:26:29.335  7047  7660 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 12:26:29.337  7047  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 12:26:29.340  7047  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cabd8b9 on behalf of 
08-16 12:26:29.341  7047  7660 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 12:26:29.344  7047  7660 V BluetoothOppNotification: outbound notification was removed.
08-16 12:26:29.344  7047  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:26:29.347  7047  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2949d4fe on behalf of 
08-16 12:26:29.348  7047  7660 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 12:26:29.351  7047  7660 V BluetoothOppNotification: inbound notification was removed.
08-16 12:26:29.351  7047  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:26:29.352  7047  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dc9445f on behalf of 
08-16 12:26:29.467  1042  1888 I ActivityManager: Killing 6703:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 12:26:29.494  6977  6977 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 12:26:29.494  6977  6977 W System.err: android.os.DeadObjectException
08-16 12:26:29.494  6977  6977 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 12:26:29.495  6977  6977 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 12:26:29.495  6977  6977 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 12:26:29.495  6977  6977 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 12:26:29.495  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 12:26:29.495  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 12:26:29.495  6977  6977 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:26:29.495  6977  6977 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:26:29.495  6977  6977 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:26:29.495  6977  6977 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:26:29.495  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:26:29.495  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:26:29.495  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:26:29.495  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:26:29.495  6977  6977 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 12:26:29.496  6977  6977 W System.err: android.os.DeadObjectException
08-16 12:26:29.496  6977  6977 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 12:26:29.496  6977  6977 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 12:26:29.496  6977  6977 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 12:26:29.496  6977  6977 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 12:26:29.496  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 12:26:29.496  6977  6977 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 12:26:29.496  6977  6977 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:26:29.496  6977  6977 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:26:29.496  6977  6977 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:26:29.496  6977  6977 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:26:29.496  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:26:29.496  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:26:29.496  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:26:29.496  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:26:29.496  6977  6977 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 12:26:29.497  6977  6977 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-16 12:26:29.531  1042  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_6703/cgroup.procs: No such file or directory
08-16 12:26:29.531  1042  2014 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 12:26:29.538  6977  6977 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 12:26:29.539  6977  6977 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 12:26:29.580  1042  1558 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7661 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:26:29.640  6977  6977 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 12:26:29.669  7661  7661 D UEI.SmartControl: Quickset Services start...
,08-16 12:26:29.673  7661  7661 I UEI.SmartControl: Manufacture = LGE
08-16 12:26:29.674  7661  7661 D UEI.SmartControl: Id = LGNevo
08-16 12:26:29.675  7661  7661 D UEI.SmartControl: File observer start...
08-16 12:26:29.677  7661  7661 E UEI.SmartControl: IR Port is disabled: false
08-16 12:26:29.677  7661  7661 D UEI.SmartControl: Starting file observer...
08-16 12:26:29.677  7661  7661 D UEI.SmartControl: Extracting JNI libs...
08-16 12:26:29.677  7661  7661 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 12:26:29.782  7661  7661 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 12:26:29.783  7661  7661 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-16 12:26:29.783  7661  7661 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 12:26:29.824  7661  7661 I UEI.SmartControl: --- Selecting new region: 6
08-16 12:26:29.826  7661  7661 I UEI.SmartControl: Model = LG-D855
,08-16 12:26:29.828  7661  7661 D UEI.SmartControl: QS Service created
,08-16 12:26:29.861  7661  7661 I UEI.SmartControl: Service initServices...
,08-16 12:26:29.867  7661  7661 D UEI.SmartControl: QS start get config
,08-16 12:26:29.949  7661  7661 D UEI.SmartControl: Loading JNI Libs...
,08-16 12:26:30.138  1042  1693 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:30.138  1042  1693 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@80debc0 mBinding = false
,08-16 12:26:30.159  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:26:30.160  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:26:30.160  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-16 12:26:30.160  1042  1119 D BluetoothManagerService: Message: 2
08-16 12:26:30.161  1042  1119 D BluetoothManagerService: Sending off request.
08-16 12:26:30.161  7047  7624 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 12:26:30.162  7047  7522 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 12:26:30.162  7047  7522 D BluetoothAdapterProperties: Setting state to 13
08-16 12:26:30.162  7047  7522 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 12:26:30.163  7047  7522 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 12:26:30.163  7047  7522 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 12:26:30.165  7047  7526 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:26:30.166  7047  7522 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 12:26:30.167  7047  7631 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 12:26:30.168  7047  7634 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:30.168  7047  7643 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:30.169  7047  7646 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:30.169  7047  7648 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:26:30.170  7047  7522 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 12:26:30.172  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:30.172  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:30.173  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:30.173  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:30.175  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:30.175  6803  6803 V io.jxcor,e.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:30.175  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:30.175  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:30.175  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:30.175  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:26:30.175  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:30.175  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:30.175  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:30.177  6803  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:26:30.177  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:30.178  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:30.178  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 12:26:30.178  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 12:26:30.179  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 12:26:30.179  7047  7591 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 12:26:30.184  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 12:26:30.186  7047  7591 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 12:26:30.188  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:26:30.190  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.191  7047  7047 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.191  7047  7047 D BluetoothMapService: STATE_TURNING_OFF
08-16 12:26:30.191  7047  7047 V BtOppService: Receiver DISABLED_ACTION 
08-16 12:26:30.191  7047  7047 V BluetoothMapService: Handler(): got msg=4
08-16 12:26:30.191  7047  7047 D BluetoothMapService: MAP Service closeService in
08-16 12:26:30.191  7047  7047 D BluetoothMapMasInstance: MAP Service shutdown
08-16 12:26:30.191  6923  6923 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 12:26:30.191  7047  7047 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:26:30.191  7047  7047 V BluetoothMapService: MAP Service closeService out
08-16 12:26:30.192  7047  7047 I BtOppRfcommListener: stopping Accept Thread
08-16 12:26:30.192  7047  7047 V BtOppRfcommListener: close mBtServerSocket
08-16 12:26:30.192  7047  7643 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 12:26:30.193  7047  7047 V BtOppRfcommListener: waiting for thread to terminate
08-16 12:26:30.193  7047  7047 V BtOppRfcommListener: done waiting for thread to terminate
08-16 12:26:30.193  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 12:26:30.200  7047  7047 V BtOppService: onDestroy
08-16 12:26:30.201  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:30.205  7047  7047 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 12:26:30.206  7047  7047 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:26:30.206  7047  7047 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.206  7047  7047 V BluetoothPbapReceiver: ***********state = 13
08-16 12:26:30.208  6923  6923 D DockEventReceiver: finishStartingService: stopping service
08-16 12:26:30.208  7047  7047 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 12:26:30.208  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:30.210  7047  7047 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.210  7047  7047 V BluetoothPbapService: state: 13
08-16 12:26:30.210  7047  7047 V BluetoothPbapService: Pbap Service closeService in
,08-16 12:26:30.216  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:26:30.217  6923  6923 D BluetoothPbap: Proxy object disconnected
08-16 12:26:30.217  6923  6923 D PbapServerProfile: Bluetooth service disconnected
08-16 12:26:30.217  7047  7047 V BluetoothPbapService: successfully stopped pbap service
08-16 12:26:30.218  7047  7047 V BluetoothPbapService: Pbap Service closeService out
08-16 12:26:30.218  7047  7047 V BluetoothPbapService: Pbap Service onDestroy
08-16 12:26:30.219  7047  7047 V BluetoothPbapService: Pbap Service closeService in
08-16 12:26:30.219  7047  7047 V BluetoothPbapService: Pbap Service closeService out
08-16 12:26:30.219  7047  7047 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 12:26:30.236  6923  6923 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 12:26:30.243  6923  6923 D BluetoothPermissionRequest: onReceive
08-16 12:26:30.243  6923  6923 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 12:26:30.249  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:26:30.256  7047  7047 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 12:26:30.256  7047  7047 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 12:26:30.259  7047  7047 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 12:26:30.264  7047  7047 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.264  7047  7047 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 12:26:30.266  7047  7047 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:26:30.266  7047  7047 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.266  7047  7047 V BluetoothFtpService: Ftp Service closeService
08-16 12:26:30.266  7047  7047 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 12:26:30.268  7047  7047 V BluetoothFtpService: successfully stopped ftp service
,08-16 12:26:30.268  7047  7047 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:30.268  7047  7047 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:30.268  7047  7047 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:30.268  7047  7047 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.268  7047  7047 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-16 12:26:30.268  7047  7047 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 12:26:30.270  7047  7047 V BluetoothFtpService: Ftp Service onDestroy
08-16 12:26:30.270  7047  7047 V BluetoothFtpService: Ftp Service closeService
08-16 12:26:30.275  7047  7047 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:30.275  7047  7047 V BluetoothSapService: state: 13
08-16 12:26:30.275  7047  7047 V BluetoothSapService: Stopping SAP server process
08-16 12:26:30.276  7047  7047 V BluetoothSapService: Sap Service closeSapService in
,08-16 12:26:30.276  7047  7047 V BluetoothSapService: Close listen Socket : 
08-16 12:26:30.277  7047  7047 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:26:30.277  7047  7047 V BluetoothSapService: Close sapd  Socket : 
,08-16 12:26:30.280  7047  7047 V BluetoothSapService: Sap Service closeSapService out
,08-16 12:26:30.281  7047  7047 V BluetoothSapService: Sap Service onDestroy
08-16 12:26:30.281  7047  7047 V BluetoothSapService: Sap Service closeSapService in
08-16 12:26:30.281  7047  7047 V BluetoothSapService: Close listen Socket : 
08-16 12:26:30.281  7047  7047 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:26:30.281  7047  7047 V BluetoothSapService: Close sapd  Socket : 
08-16 12:26:30.283  7047  7047 V BluetoothSapService: Sap Service closeSapService out
08-16 12:26:30.429  7661  7661 I UEI.SmartControl: Supports setup maps: true
,08-16 12:26:30.433  7661  7661 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 12:26:30.433  7661  7661 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 12:26:30.433  7661  7661 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 12:26:30.433  7661  7661 I UEI.SmartControl: ### init IR Blaster...
08-16 12:26:30.439  7661  7661 D serial_port: Configuring serial port
08-16 12:26:30.443  7661  7661 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:26:30.443  7661  7661 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 12:26:30.443  7661  7661 I UEI.SmartControl: configuring settings for MAXQ616
08-16 12:26:30.443  7661  7661 I UEI.SmartControl: Get version...
,08-16 12:26:30.460  7661  7698 D UEI.SmartControl: serial port data available: 21
,08-16 12:26:30.490  7661  7661 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 12:26:30.490  7661  7661 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 12:26:30.491  7661  7661 I UEI.SmartControl: QS saving settings...
08-16 12:26:30.493  7661  7661 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 12:26:30.511  7661  7698 D UEI.SmartControl: serial port data available: 4
,08-16 12:26:30.549  7661  7701 I UEI.SmartControl: Device manager: loading config....
,08-16 12:26:30.552  7661  7701 D UEI.SmartControl: ----------- loading internal config...
08-16 12:26:30.552  7661  7661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 12:26:30.556  7661  7661 E UEI.SmartControl: Services init done
08-16 12:26:30.556  7661  7661 D UEI.SmartControl: QS Service init finished
08-16 12:26:30.559  7661  7661 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:26:30.559  7661  7661 D UEI.SmartControl: QS Service version code: 201091
08-16 12:26:30.560  7661  7661 D UEI.SmartControl: Service requested: Control
08-16 12:26:30.580  7661  7661 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 12:26:30.580  7661  7701 E UEI.SmartControl: Loading SETTINGS...
,08-16 12:26:30.585  6977  6977 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 12:26:30.586  7661  7677 I UEI.SmartControl: ------ IControl API: 11
08-16 12:26:30.588  1042  1915 I ActivityManager: Killing 6977:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 12:26:30.589  7661  7677 I UEI.SmartControl: Registering callback...
08-16 12:26:30.596  7661  7701 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 12:26:30.608  7661  7700 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 12:26:30.608  7661  7700 D UEI.SmartControl: -----service ready thread exits
08-16 12:26:30.712  1042  1888 W libprocessgroup: failed to open /acct/uid_10112/pid_6977/cgroup.procs: No such file or directory
08-16 12:26:30.713  7661  7661 D UEI.SmartControl: Internal service binding...
,08-16 12:26:31.089  7047  7526 D bt_hci_bdroid: cleanup
,08-16 12:26:31.097  7047  7593 I bt_lpm  : LPM is already off!!!
,08-16 12:26:31.097  7047  7617 I bt_userial_mct: exiting userial_read_thread
,08-16 12:26:31.097  7047  7617 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-16 12:26:31.102  7047  7591 W bt-btif : ag scb idx 1 not allocated
08-16 12:26:31.102  7047  7591 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 12:26:31.102  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:31.102  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:26:31.103  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:26:31.104  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:26:31.104  7047  7591 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:26:31.104  7047  7591 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:26:31.104  7047  7591 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:26:31.104  7047  7591 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 12:26:31.106  7047  7526 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 12:26:31.107  7047  7593 I bt_vendor: hw_epilog_process
08-16 12:26:31.112  7047  7526 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 12:26:31.112  7047  7526 D bt_userial_mct: userial_close
08-16 12:26:31.112  7047  7526 E bt_userial_mct: pthread_join() FAILED result:3
08-16 12:26:31.112  7047  7526 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 12:26:31.121  7047  7526 D bt_hci_bdroid: set_power 0
08-16 12:26:31.121  7047  7526 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 12:26:31.121  7047  7526 I bt_vendor: bluetooth satus is on
08-16 12:26:31.121  7047  7526 I bt_vendor: bt-vendor : resetting BT status
08-16 12:26:31.121  7047  7526 I bt_vendor: Starting hciattach daemon
08-16 12:26:31.121  7047  7526 I bt_vendor: try to set false
08-16 12:26:31.123  7047  7526 I bt_vendor: Starting hciattach daemon
08-16 12:26:31.123  7047  7526 I bt_vendor: try to set false
,08-16 12:26:31.127  7047  7526 I bt_vendor: cleanup
08-16 12:26:31.128  7047  7591 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 12:26:31.129  7047  7526 I GKI_LINUX: GKI_exit_task 0 done
08-16 12:26:31.129  7047  7526 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 12:26:31.131  7047  7522 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 12:26:31.137  7047  7047 D HeadsetService: Received stop request...Stopping profile...
,08-16 12:26:31.143  7047  7047 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:26:31.144  7047  7047 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:26:31.144  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:31.144  7047  7544 D HeadsetStateMachine: Exit Disconnected: -1
08-16 12:26:31.147  1042  1042 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:31.147  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 12:26:31.148  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:31.148  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:31.148  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:26:31.149  7047  7522 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 12:26:31.149  7047  7047 D A2dpService: Received stop request...Stopping profile...
08-16 12:26:31.151  7047  7579 D A2dpStateMachine: Exit Disconnected: -1
,08-16 12:26:31.155  7047  7047 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 12:26:31.157  7047  7047 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 12:26:31.157  7047  7047 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:26:31.157  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:31.159  7047  7047 D HidService: Received stop request...Stopping profile...
08-16 12:26:31.159  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:31.161  1042  1042 D BluetoothA2dp: Proxy object disconnected
08-16 12:26:31.162  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 12:26:31.163  7047  7047 D HealthService: Received stop request...Stopping profile...
08-16 12:26:31.163  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
,08-16 12:26:31.167  7047  7047 D PanService: Received stop request...Stopping profile...
08-16 12:26:31.168  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:31.169  7047  7047 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:26:31.170  7047  7047 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 12:26:31.170  7047  7047 D BtGatt.GattService: stop()
08-16 12:26:31.171  7047  7047 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 12:26:31.172  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:31.173  7047  7047 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:26:31.173  7047  7047 D BluetoothMapService: stop()
08-16 12:26:31.175  7047  7047 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 12:26:31.176  7047  7047 D BluetoothMapEmailAppObserver: removeReceiver()
,08-16 12:26:31.178  7047  7047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@302fd343
08-16 12:26:31.179  7047  7047 D HeadsetStateMachine: Unbinding service...
08-16 12:26:31.180  7047  7047 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:26:31.180  7047  7047 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:26:31.180  7047  7047 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:26:31.180  7047  7047 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:26:31.181  7047  7047 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 12:26:31.181  7047  7047 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:26:31.181  7047  7047 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:26:31.181  7047  7047 I BluetoothA2dpServiceJni: cleanupNative
08-16 12:26:31.181  7047  7581 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 12:26:31.182  7047  7047 I GKI_LINUX: GKI_exit_task 2 done
08-16 12:26:31.182  7047  7047 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 12:26:31.182  7047  7047 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 12:26:31.182  7047  7047 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 12:26:31.183  7047  7047 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 12:26:31.183  7047  7047 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:26:31.183  7047  7047 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:26:31.183  7047  7047 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 12:26:31.183  7047  7047 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 12:26:31.188  7047  7047 V BluetoothMapService: Handler(): got msg=4
08-16 12:26:31.189  7047  7047 D BluetoothMapService: MAP Service closeService in
08-16 12:26:31.189  7047  7047 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:26:31.189  7047  7047 V BluetoothMapService: MAP Service closeService out
,08-16 12:26:31.194  7047  7522 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 12:26:31.194  7047  7522 D BluetoothAdapterProperties: Setting state to 10
08-16 12:26:31.194  7047  7522 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 12:26:31.195  7047  7047 D BluetoothMapService: cleanup()
08-16 12:26:31.195  7047  7047 D BluetoothMapService: MAP Service closeService in
08-16 12:26:31.195  7047  7047 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:26:31.195  7047  7047 V BluetoothMapService: MAP Service closeService out
08-16 12:26:31.196  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:31.196  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 12:26:31.196  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 12:26:31.197  7047  7522 I BluetoothAdapterState: Entering OffState
08-16 12:26:31.197  6923  6938 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:26:31.198  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:26:31.198  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:26:31.199  6923  6938 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:26:31.199  6923  6938 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:26:31.200  1042  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:26:31.200  6923  6938 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:26:31.201  1042  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:26:31.201  6923  6938 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:26:31.202  6923  6938 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:26:31.203  1837  2675 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:26:31.207  1042  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 12:26:31.207  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 12:26:31.208  1042  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 12:26:31.208  1042  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 12:26:31.209  1042  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@80debc0 mBinding = false
08-16 12:26:31.209  1042  1119 D BluetoothManagerService: Sending unbind request.
08-16 12:26:31.214  7047  7526 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 12:26:31.215  7047  7047 I GKI_LINUX: GKI_exit_task 1 done
08-16 12:26:31.215  7047  7047 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 12:26:31.216  7047  7047 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 12:26:31.216  7047  7047 I art     : --- WEIRD: removing null entry 248
08-16 12:26:31.216  7047  7047 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 12:26:31.216  7047  7047 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-16 12:26:31.219  7047  7047 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 12:26:31.220  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 12:26:31.222  7047  7047 I art     : System.exit called, status: 0
08-16 12:26:31.222  7047  7047 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 12:26:31.246   318  2131 V AudioFlinger: 7047 died, releasing its sessions
08-16 12:26:31.246   318  2131 V AudioFlinger:  pid 1837 @ 0
08-16 12:26:31.246   318  2131 V AudioFlinger:  pid 3315 @ 1
08-16 12:26:31.246   318  2131 V AudioFlinger:  pid 3315 @ 2
,08-16 12:26:31.255  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 12:26:31.256  1925  2085 D LGBluetoothAPIService: Message: 101
08-16 12:26:31.256  1925  2085 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 12:26:31.256  1925  2085 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 12:26:31.257  1925  2085 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 12:26:31.257  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:26:31.258  6923  6923 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 12:26:31.260  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:31.260  1925  2085 D LGBluetoothAPIService: Message: 2
08-16 12:26:31.260  1925  2085 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 12:26:31.264  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:31.265  1586  1586 D BluetoothAdapter: 1059169482: getState() :  mService = null. Returning STATE_OFF
,08-16 12:26:31.265  1586  1586 D BluetoothAdapter: 1059169482: getState() :  mService = null. Returning STATE_OFF
08-16 12:26:31.265  6923  6923 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 12:26:31.265  6923  6923 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 12:26:31.267  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:31.269  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 12:26:31.321  1042  2020 I ActivityManager: Process com.android.bluetooth (pid 7047) has died
,08-16 12:26:31.321  1042  2020 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-16 12:26:31.321  1042  2020 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
08-16 12:26:31.413  1042  1942 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7733 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 12:26:31.416  6923  6923 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:26:31.484  7733  7733 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 12:26:31.484  7733  7733 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:31.485  7733  7733 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 12:26:31.486  7733  7733 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 12:26:31.506  7733  7733 D BluetoothAdapterApp: Loading JNI Library
,08-16 12:26:31.550  7733  7733 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@a2875cb Instance Count = 1
,08-16 12:26:31.556  7733  7733 D BluetoothAdapterApp: onCreate
08-16 12:26:31.583  7733  7733 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 12:26:31.583  7733  7733 D ProfileConfigQcom: Adding HeadsetService
08-16 12:26:31.584  7733  7733 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-16 12:26:31.584  7733  7733 D ProfileConfigQcom: Adding A2dpService
,08-16 12:26:31.585  7733  7733 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 12:26:31.585  7733  7733 D ProfileConfigQcom: Adding HidService
08-16 12:26:31.586  7733  7733 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 12:26:31.587  7733  7733 D ProfileConfigQcom: Adding HealthService
08-16 12:26:31.588  7733  7733 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-16 12:26:31.589  7733  7733 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 12:26:31.589  7733  7733 D ProfileConfigQcom: Adding PanService
08-16 12:26:31.590  7733  7733 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 12:26:31.590  7733  7733 D ProfileConfigQcom: Adding GattService
08-16 12:26:31.591  7733  7733 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 12:26:31.591  7733  7733 D ProfileConfigQcom: Adding BluetoothMapService
08-16 12:26:31.592  7733  7733 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 12:26:31.594  7733  7733 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:26:31.597  7733  7733 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:31.597  7733  7733 V BluetoothPbapReceiver: ***********state = 10
,08-16 12:26:31.602  7733  7733 V LGMDMManagerInternal: Create singleton instance
,08-16 12:26:31.709  7733  7733 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-16 12:26:31.710  7733  7733 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 12:26:31.712  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:26:31.725  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 12:26:31.726  1925  2085 D LGBluetoothAPIService: Message: 100
08-16 12:26:31.727  1925  2085 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 12:26:31.733  6923  6923 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 12:26:31.737  6923  6923 D BluetoothPermissionRequest: onReceive
08-16 12:26:31.739  6923  6923 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 12:26:31.739  6923  6923 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 12:26:31.742  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:26:31.748  7733  7733 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 12:26:31.755  7733  7733 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:31.758  7733  7733 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:31.758  7733  7733 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:31.759  7733  7733 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:31.760  7733  7733 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:26:31.760  7733  7733 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 12:26:31.763  7002  7002 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 12:26:33.187  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:33.187  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:33.419  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 12:26:33.445  1042  1410 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 12:26:33.520  1042  1108 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7761 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 12:26:33.526  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 12:26:33.527  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 12:26:33.540  1042  1042 D administrator: Handling package changes for user 0
,08-16 12:26:33.556  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 12:26:33.586  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 12:26:33.637  7761  7761 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 12:26:33.691  1042  1042 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 12:26:33.692  1042  1042 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 12:26:33.743  7761  7761 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:33.744  7761  7761 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:33.762  1042  1106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:26:33.771  1042  1106 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 12:26:33.783  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 12:26:33.787  2459  2459 V GmsNetworkLocationProvi: DISABLE
08-16 12:26:33.819  1042  1106 D LocationProviderProxy: applying state to connected service
,08-16 12:26:33.822  2459  2459 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 12:26:33.866  7761  7806 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 12:26:33.866  7761  7806 I Babel   : MmsConfig.loadMmsSettings
,08-16 12:26:33.868  7761  7806 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 12:26:33.868  7761  7806 I Babel   : MmsConfig.loadFromDatabase
,08-16 12:26:33.883  7761  7806 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 12:26:33.883  7761  7806 I Babel   : MmsConfig.loadFromResources
08-16 12:26:33.885  7761  7806 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 12:26:33.886  7761  7806 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 12:26:33.894  7761  7804 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 12:26:33.897  7761  7804 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 12:26:33.900  7761  7761 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:33.901  7761  7804 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 12:26:33.911  7761  7804 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 12:26:33.919  7761  7804 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 12:26:33.921  7761  7804 W AudioCapabilities: Unsupported mime audio/evrc
08-16 12:26:33.924  1802  7808 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 12:26:33.924  1802  7808 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-16 12:26:33.928  7118  7118 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:26:33.933  7118  7118 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ef5abfd
08-16 12:26:33.933  7118  7118 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:26:33.933  7118  7118 D AppUp4:CustFacade: isPhone : true
08-16 12:26:33.933  7118  7118 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:26:33.934  7118  7118 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-16 12:26:33.946  1802  5095 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 12:26:33.947  7761  7804 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 12:26:33.950  7761  7804 W VideoCapabilities: Unsupported mime video/divx
08-16 12:26:33.961  7761  7804 W VideoCapabilities: Unsupported mime video/divx311
,08-16 12:26:33.964  7761  7804 W VideoCapabilities: Unsupported mime video/divx4
08-16 12:26:33.970  7761  7804 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 12:26:33.972  1042  1915 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7811 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 12:26:33.976  1042  1943 I ActivityManager: Killing 6943:com.lge.sync/1000 (adj 15): empty #17
,08-16 12:26:33.988  1042  1526 D WifiService: Client connection lost with reason: 4
,08-16 12:26:33.994  7761  7804 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 12:26:33.997  7761  7804 W AudioCapabilities: Unsupported mime audio/eac3
08-16 12:26:33.998  7761  7804 W AudioCapabilities: Unsupported mime audio/ac3
08-16 12:26:33.998  7761  7804 W AudioCapabilities: Unsupported mime audio/g726
08-16 12:26:33.999  7761  7804 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 12:26:34.000  7761  7804 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 12:26:34.002  7761  7804 W AudioCapabilities: Unsupported mime audio/adpcm
,08-16 12:26:34.004  7761  7804 W VideoCapabilities: Unsupported mime video/theora
,08-16 12:26:34.006  7761  7804 W VideoCapabilities: Unsupported mime video/mjpg
08-16 12:26:34.102  1042  1059 W libprocessgroup: failed to open /acct/uid_1000/pid_6943/cgroup.procs: No such file or directory
,08-16 12:26:34.148  7811  7811 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:26:34.149  7811  7811 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:34.149  7811  7811 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 12:26:34.151  7811  7811 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 12:26:34.151  7811  7811 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 12:26:34.221  7811  7811 I SystemConfig: BUILD Country: EU
08-16 12:26:34.221  7811  7811 I SystemConfig: BUILD Operator: OPEN
,08-16 12:26:34.264  1042  2014 I ActivityManager: Killing 7144:com.lge.email/u0a23 (adj 15): empty #17
,08-16 12:26:34.315  1042  2020 W libprocessgroup: failed to open /acct/uid_10023/pid_7144/cgroup.procs: No such file or directory
,08-16 12:26:34.387  1042  1942 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7835 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-16 12:26:34.393  7811  7833 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 12:26:34.393  7811  7833 I SystemConfig: existFile = false
08-16 12:26:34.393  7811  7833 I SystemConfig: canReadFile = false
08-16 12:26:34.393  7811  7833 I SystemConfig: systemFeature RCS result false
08-16 12:26:34.393  7811  7833 D SystemConfig: refreshRcsSupport() :false
,08-16 12:26:34.494  7835  7835 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:26:34.495  7835  7835 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 12:26:34.495  7835  7835 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 12:26:34.495  7835  7835 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 12:26:34.756  1042  1924 I art     : Explicit concurrent mark sweep GC freed 44097(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.290ms total 157.410ms
,08-16 12:26:34.775  7835  7835 I AppConfig: Total System Memory = 2995761152
,08-16 12:26:34.789  7835  7835 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 12:26:34.893  1042  1693 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7854 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 12:26:34.895  1042  1693 I ActivityManager: Killing 7028:com.lge.formmanager/u0a26 (adj 15): empty #17
08-16 12:26:34.961  1042  1996 W libprocessgroup: failed to open /acct/uid_10026/pid_7028/cgroup.procs: No such file or directory
,08-16 12:26:35.142  7854  7854 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 12:26:35.258  7854  7854 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:35.258  7854  7854 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:35.314  7854  7854 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 12:26:35.335  7854  7854 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 12:26:35.336  7854  7854 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 12:26:35.354  7854  7854 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 12:26:35.354  7854  7854 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 12:26:35.392  1042  1637 I ActivityManager: Killing 6345:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 12:26:35.468  1042  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_6345/cgroup.procs: No such file or directory
,08-16 12:26:35.496  4912  7893 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 12:26:35.542  1042  1915 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7895 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 12:26:35.550  7661  7702 D UEI.SmartControl: Internal timer expired: 1
08-16 12:26:35.550  7661  7702 D UEI.SmartControl: unbind internal service
,08-16 12:26:35.563  7661  7661 D UEI.SmartControl: Service.onUnbind: IControl
08-16 12:26:35.563  7661  7661 D UEI.SmartControl: Service.onDestroy
,08-16 12:26:35.569  7661  7661 D UEI.SmartControl: Lock is in USE false
08-16 12:26:35.569  7661  7661 D UEI.SmartControl: unbind internal service
08-16 12:26:35.569  7661  7661 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@12f60af9
08-16 12:26:35.570  7661  7661 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 12:26:35.570  7661  7661 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 12:26:35.570  7661  7661 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:26:35.570  7661  7661 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:26:35.570  7661  7661 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:26:35.570  7661  7661 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:26:35.571  7661  7661 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:26:35.571  7661  7661 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:26:35.571  7661  7661 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@12f60af9
08-16 12:26:35.573  7661  7661 D serial_port: close(fd = 25)
08-16 12:26:35.576  3458  4237 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-16 12:26:35.576  3458  4237 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@132e9476 on behalf of 7854
08-16 12:26:35.581  7661  7661 I UEI.SmartControl: Serial port is closed.
08-16 12:26:35.581  7661  7661 I UEI.SmartControl: Serial port is closed.
08-16 12:26:35.581  7661  7661 D UEI.SmartControl: Blaster closed
08-16 12:26:35.581  7661  7661 D UEI.SmartControl: Shut down QS...
08-16 12:26:35.581  7661  7661 D UEI.SmartControl: Stopping QS lib
08-16 12:26:35.582  7661  7661 D UEI.SmartControl: QS lib stop result = true
08-16 12:26:35.582  7661  7661 D UEI.SmartControl: Stopped QS lib
08-16 12:26:35.582  7661  7661 D UEI.SmartControl: Stopped file observer...
08-16 12:26:35.582  7661  7661 D UEI.SmartControl: QS shutdown complete
,08-16 12:26:35.607  7854  7854 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-16 12:26:35.619  7854  7854 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 12:26:35.628  7895  7895 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-16 12:26:35.646  7895  7895 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 12:26:35.646  7895  7895 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 12:26:35.646  7895  7895 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 12:26:35.646  7895  7895 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 12:26:35.646  7895  7895 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 12:26:35.646  7895  7895 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 12:26:35.662  1042  1059 I ActivityManager: Killing 7178:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-16 12:26:35.682  1042  1943 W libprocessgroup: failed to open /acct/uid_10046/pid_7178/cgroup.procs: No such file or directory
,08-16 12:26:35.934  1042  1971 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:26:35.983  4912  7893 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 486 ms] updated apps [took 486 ms] 
,08-16 12:26:36.205  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:26:36.205  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30efad25 added. We now have 6 listener(s)
,08-16 12:26:36.205  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:26:36.219  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:36.219  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c6c2efa added. We now have 7 listener(s)
08-16 12:26:36.219  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:36.222  6803  6882 I System.out: IsBluetoothEnabled
08-16 12:26:36.224  1042  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:36.224  1042  1996 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-16 12:26:36.226  1042  1119 D BluetoothManagerService: Message: 2
08-16 12:26:36.230  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:36.230  1042  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:36.230  1042  1924 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 12:26:36.247  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:26:36.247  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:26:36.247  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-16 12:26:36.248  1042  1119 D BluetoothManagerService: Message: 1
08-16 12:26:36.248  1042  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 12:26:36.273  1042  1119 D BluetoothManagerService: Message: 20
08-16 12:26:36.274  1042  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16a05e1f:true
,08-16 12:26:36.279  7733  7733 D BluetoothAdapterState: make
08-16 12:26:36.284  7733  7733 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 12:26:36.284  7733  7733 I bluedroid-qcom: init
08-16 12:26:36.285  7733  7940 I BluetoothAdapterState: Entering OffState
08-16 12:26:36.285  7733  7733 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 12:26:36.286  7733  7733 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 12:26:36.286  7733  7733 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 12:26:36.286  7733  7733 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:26:36.286  7733  7733 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 12:26:36.288  7733  7733 I bluedroid-qcom: get_profile_interface socket
08-16 12:26:36.288  7733  7733 I bluedroid-qcom: get_profile_interface map_client
,08-16 12:26:36.292  7733  7944 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 12:26:36.284  7943  7943 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:36.284  7943  7943 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:36.303  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-16 12:26:36.305  1042  1119 D BluetoothManagerService: Message: 40
08-16 12:26:36.306  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 12:26:36.307  7733  7748 I bluedroid-qcom: config_hci_snoop_log
08-16 12:26:36.308  1042  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 12:26:36.309  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 12:26:36.313  7943  7943 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 12:26:36.313  7943  7943 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 12:26:36.313  7943  7943 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 12:26:36.316  7943  7943 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 12:26:36.322  7733  7940 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 12:26:36.323  7733  7940 D BluetoothAdapterProperties: Setting state to 11
08-16 12:26:36.323  7733  7940 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 12:26:36.325  7943  7943 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 12:26:36.325  7943  7943 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 12:26:36.328  7733  7944 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 12:26:36.329  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:36.329  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 12:26:36.329  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-16 12:26:36.337  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:36.337  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:26:36.341  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:36.344  6923  6923 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 12:26:36.347  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:26:36.347  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 12:26:36.352  7733  7733 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:26:36.352  7733  7733 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:36.352  7733  7733 V BluetoothPbapReceiver: ***********state = 11
08-16 12:26:36.357  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:26:36.367  7733  7944 D BluetoothAdapterProperties: Name is: G3
08-16 12:26:36.373  7733  7940 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 12:26:36.391  7733  7940 D BluetoothBondStateMachine: make
,08-16 12:26:36.399  6923  6923 D BluetoothPermissionRequest: onReceive
08-16 12:26:36.401  7733  7954 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 12:26:36.401  7733  7940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.401  7733  7940 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 12:26:36.401  7733  7940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.401  7733  7940 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 12:26:36.402  7733  7940 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 12:26:36.405  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 12:26:36.409  7733  7940 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:36.414  7733  7733 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:26:36.418  7733  7940 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:36.419  7733  7733 D HeadsetService: Received start request. Starting profile...
,08-16 12:26:36.420  7733  7733 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:26:36.420  7733  7733 D LGBluetoothHfpAdapter: Version 1.6
08-16 12:26:36.423  7733  7733 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 12:26:36.425  7733  7733 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:26:36.425  7733  7733 D HeadsetStateMachine: make
08-16 12:26:36.432  7733  7940 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:26:36.440  7733  7940 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:36.448  7733  7940 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:26:36.458  7733  7940 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:26:36.464  7733  7940 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:26:36.467  7733  7733 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:36.467  7733  7733 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:26:36.474  7733  7733 D HeadsetStateMachine: max_hf_connections = 1
08-16 12:26:36.474  7733  7733 I bluedroid-qcom: get_profile_interface handsfree
08-16 12:26:36.477  7733  7733 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 12:26:36.477   318  1369 V AudioPolicyService: registerClient() client 0xb1025b80, uid 1002
08-16 12:26:36.478   318   318 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:26:36.478   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:26:36.478   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:26:36.478  7733  7733 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 12:26:36.478   318  2131 V AudioFlinger: registerClient() client 0xb1035bb0, pid 7733
08-16 12:26:36.479   318  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:36.479   318  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-16 12:26:36.479  7733  7733 V ToneGenerator: Create Track: 0xb4928a80
08-16 12:26:36.479  7733  7733 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 12:26:36.480  7733  7733 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 12:26:36.480  1042  2020 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:36.480  1042  2020 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:36.480  1586  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:36.480  1586  1605 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:36.480  1837  2675 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:36.480  1837  2675 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-16 12:26:36.480   318  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:26:36.480   318  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:26:36.480   318  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:26:36.480   318  1368 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:26:36.480  3315  3331 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:36.480  3315  3331 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:26:36.480  7733  7733 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 12:26:36.481  7733  7748 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:26:36.481  7733  7748 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 12:26:36.481   318  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:36.481   318  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:36.481  1586  1609 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:36.481  1586  1609 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:36.481   318  2134 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:26:36.481  1042  1059 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:36.481  1042  1059 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:36.481  3315  3330 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:36.481  3315  3330 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:36.481  1837  2492 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:36.481  1837  2492 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:26:36.482   318  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:26:36.482  7733  7749 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:26:36.482   318  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 12:26:36.482   318  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:26:36.482   318  1368 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:26:36.482  7733  7749 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 12:26:36.482  7733  7733 V AudioSystem: getLatency() output 2, latency 50
08-16 12:26:36.482  7733  7733 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 12:26:36.482  7733  7733 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 12:26:36.482   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:26:36.482   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:26:36.482   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:26:36.482   318  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:26:36.482   318  1369 V AudioFlinger: createTrack() lSessionId: 23
08-16 12:26:36.483  7733  7733 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 12:26:36.484   318  1369 V AudioFlinger: acquiring 23 from 7733, for 7733
08-16 12:26:36.484   318  1369 V AudioFlinger:  added new entry for 23
08-16 12:26:36.484  7733  7733 V ToneGenerator: ToneGenerator INIT OK, time: 210493
08-16 12:26:36.484  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.484  7733  7940 V LGMDMManager: Create singleton instance
08-16 12:26:36.485  7733  7962 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 12:26:36.485  7733  7962 D He,adsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:26:36.486  7733  7962 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:26:36.486  7733  7962 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 12:26:36.486  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.486  7733  7733 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:36.486  7733  7733 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:36.486   318   318 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7733
08-16 12:26:36.486  7733  7733 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:36.487  7733  7733 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:36.487  7733  7733 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 12:26:36.487   318   318 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 12:26:36.487   318   318 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 12:26:36.487   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 12:26:36.487   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 12:26:36.487   318   318 V voice   : voice_set_parameters: exit with code(0)
08-16 12:26:36.487   318   318 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 12:26:36.488   318   318 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 12:26:36.488   318   318 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 12:26:36.488   318   318 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 12:26:36.488   318   318 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 12:26:36.488   318   318 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 12:26:36.489  7733  7733 D A2dpService: Received start request. Starting profile...
08-16 12:26:36.489  7733  7962 V ToneGenerator: ToneGenerator destructor
08-16 12:26:36.489  7733  7962 V ToneGenerator: stopTone
08-16 12:26:36.489  7733  7962 V ToneGenerator: Delete Track: 0xb4928a80
08-16 12:26:36.489  7733  7733 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 12:26:36.491   318  2134 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 12:26:36.491   318  2134 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 12:26:36.491   318  1273 V AudioPolicyService: AudioCommandThread() waking up
,08-16 12:26:36.491   318  2134 V AudioFlinger: PlaybackThread::Track destructor
,08-16 12:26:36.491   318  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 12:26:36.491   318  1273 V AudioPolicyManager: releaseOutput() 2
08-16 12:26:36.491   318  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 12:26:36.491   318  2134 V AudioFlinger: removeClient_l() pid 7733, calling pid 318
08-16 12:26:36.492  7733  7962 V AudioTrack: ~AudioTrack, releasing session id from 7733 on behalf of 7733
08-16 12:26:36.492   318  1369 V AudioFlinger: releasing 23 from 7733 for 7733
08-16 12:26:36.492   318  1369 V AudioFlinger:  decremented refcount to 0
08-16 12:26:36.492   318  1369 V AudioFlinger: purging stale effects
08-16 12:26:36.494  7733  7733 V Avrcp   : make
08-16 12:26:36.496  7733  7733 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 12:26:36.496  7733  7733 I bluedroid-qcom: get_profile_interface avrcp
08-16 12:26:36.499  7733  7940 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 12:26:36.507  7733  7733 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 12:26:36.509  7733  7733 E AudioManager: No RCC entry present to update
08-16 12:26:36.510  7733  7733 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 12:26:36.514  7733  7733 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 12:26:36.516  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 12:26:36.516  7733  7733 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 12:26:36.520  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 12:26:36.629  1042  1060 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:26:36.629  1042  1060 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:26:36.765  1042  1971 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 12:26:36.776  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 12:26:36.780  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:26:36.781  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 12:26:36.782  7733  7733 I BluetoothA2dpServiceJni: classInitNative
08-16 12:26:36.782  7733  7733 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:26:36.782  7733  7733 D A2dpStateMachine: make
,08-16 12:26:36.785  7733  7733 I bluedroid-qcom: get_profile_interface a2dp
08-16 12:26:36.785  7733  7970 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 12:26:36.788  7733  7733 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:26:36.788  7733  7733 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 12:26:36.789  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.789  7733  7733 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 12:26:36.789  7733  7969 D A2dpStateMachine: Enter Disconnected: -2
08-16 12:26:36.793  7733  7733 D HidService: Received start request. Starting profile...
08-16 12:26:36.793  7733  7733 I bluedroid-qcom: get_profile_interface hidhost
08-16 12:26:36.793  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.800  7733  7733 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 12:26:36.807  7733  7733 D HealthService: Received start request. Starting profile...
08-16 12:26:36.813  7733  7733 I bluedroid-qcom: get_profile_interface health
,08-16 12:26:36.814  7733  7733 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:26:36.814  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.817  7733  7733 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 12:26:36.822  7733  7733 D PanService: Received start request. Starting profile...
08-16 12:26:36.822  7733  7733 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 12:26:36.822  7733  7733 I bluedroid-qcom: get_profile_interface pan
,08-16 12:26:36.834  7733  7733 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 12:26:36.834  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.836  7733  7733 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 12:26:36.843  7733  7733 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:26:36.843  7733  7733 D BtGatt.GattService: Received start request. Starting profile...
08-16 12:26:36.843  7733  7733 D BtGatt.GattService: start()
08-16 12:26:36.843  7733  7733 I bluedroid-qcom: get_profile_interface gatt
08-16 12:26:36.844  7733  7733 D BtGatt.AdvertiseManager: advertise manager created
,08-16 12:26:36.852  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.854  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.855  7733  7733 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 12:26:36.856  7733  7733 V BluetoothMapService: BluetoothMapBinder()
08-16 12:26:36.857  7733  7733 D BluetoothMapService: Received start request. Starting profile...
08-16 12:26:36.857  7733  7733 D BluetoothMapService: start()
08-16 12:26:36.860  7733  7733 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 12:26:36.860  7733  7733 D BluetoothMapEmailAppObserver: createReceiver()
,08-16 12:26:36.861  7733  7733 D BluetoothMapEmailAppObserver: initObservers()
08-16 12:26:36.862  7733  7733 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 12:26:36.874  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:36.874  7733  7733 D HeadsetStateMachine: Proxy object connected
08-16 12:26:36.875  7733  7733 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 12:26:36.876  7733  7733 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 12:26:36.883  7733  7733 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:36.885  7733  7962 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 12:26:36.886  7733  7962 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 12:26:36.886  7733  7962 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 12:26:36.886  7733  7733 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:36.889  7733  7733 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 12:26:36.892  7733  7733 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:36.893  7733  7733 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 12:26:36.896  7733  7733 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:26:36.899  7733  7733 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 12:26:36.899  7733  7733 V BluetoothMapService: Handler(): got msg=1
08-16 12:26:36.900  7733  7940 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 12:26:36.900  7733  7940 I bluedroid-qcom: enable
08-16 12:26:36.901  7733  7940 I bt_hci_bdroid: init
08-16 12:26:36.902  7733  7984 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 12:26:36.902  7733  7940 I bt_vendor: bt-vendor : init
08-16 12:26:36.902  7733  7940 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 12:26:36.902  7733  7940 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 12:26:36.902  7733  7940 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 12:26:36.902  7733  7984 I bt-btu  : btu_task pending for preload complete event
08-16 12:26:36.902  7733  7940 D bt_userial_mct: userial_init
08-16 12:26:36.903  7733  7940 D bt_hci_bdroid: set_power 1
08-16 12:26:36.903  7733  7940 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 12:26:36.903  7733  7940 I bt_vendor: Starting hciattach daemon
08-16 12:26:36.903  7733  7940 I bt_vendor: try to set true
,08-16 12:26:36.894  7988  7988 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:36.894  7988  7988 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:36.919  7992  7992 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 12:26:36.992  8000  8000 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 12:26:37.007  8001  8001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 12:26:37.049  8004  8004 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 12:26:37.075  8005  8005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 12:26:37.101  8006  8006 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 12:26:37.116  8007  8007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 12:26:37.158  8009  8009 I libmdmdetect: ESOC framework not supported
,08-16 12:26:37.160  8009  8009 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 12:26:37.175  8009  8009 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 12:26:37.175  8009  8009 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 12:26:37.175  8009  8009 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 12:26:37.175  8009  8009 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 12:26:37.175  8009  8009 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 12:26:37.175  8009  8009 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 12:26:37.175  8009  8009 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 12:26:37.228  8009  8014 E QC-QMI  : qmi_client [8009] 15: failed to locate client data
08-16 12:26:37.229   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 12:26:37.229   470   470 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 12:26:37.276  8018  8018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 12:26:37.302  8019  8019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 12:26:37.356  7733  7940 I bt_vendor: bluetooth satus is on
,08-16 12:26:37.356  7733  7940 D bt_hci_bdroid: preload
,08-16 12:26:37.356  7733  7987 D bt_userial_mct: userial_open(port:0)
08-16 12:26:37.356  7733  7987 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 12:26:37.360  7733  7987 I bt_vendor: Done intiailizing UART
08-16 12:26:37.363  7733  7987 I bt_vendor: Done intiailizing UART
,08-16 12:26:37.363  7733  7987 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 12:26:37.364  7733  7987 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 12:26:37.364  7733  7984 I bt-btu  : btu_task received preload complete event
,08-16 12:26:37.365  7733  8021 D bt_userial_mct: Entering userial_read_thread()
08-16 12:26:37.365  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 12:26:37.366  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-16 12:26:37.370  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_BTM,
08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
08-16 12:26:37.389  7733  7984 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 12:26:37.390  7733  7984 I         : BTE_InitTraceLevels -- TRC_PAN,
08-16 12:26:37.390  7733  7984 I         : BTE_InitTraceLevels -- TRC_SDP,
,08-16 12:26:37.390  7733  7984 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 12:26:37.390  7733  7984 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 12:26:37.390  7733  7984 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 12:26:37.390  7733  7984 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 12:26:37.476  7733  7984 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-16 12:26:37.476  7733  7984 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0220061 
,08-16 12:26:37.476  7733  7984 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0220061 
,08-16 12:26:37.543  7733  7944 E bt-btif : Calling BTA_HhEnable
,08-16 12:26:37.544  7733  7944 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-16 12:26:37.544  7733  7944 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 12:26:37.555  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-16 12:26:37.555  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 12:26:37.555  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 12:26:37.556  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 12:26:37.556  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 12:26:37.559  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:26:37.566  7733  7944 D BluetoothAdapterProperties: Name is: G3
,08-16 12:26:37.574  7733  7944 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:26:37.574  7733  7944 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:26:37.574  7733  7944 D bt_hci_bdroid: postload
08-16 12:26:37.574  7733  7987 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:26:37.575  7733  7984 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 12:26:37.577  7733  7944 D bte_conf: Device ID record 1 : primary
08-16 12:26:37.577  7733  7944 D bte_conf:   vendorId            = 00c4
08-16 12:26:37.577  7733  7944 D bte_conf:   vendorIdSource      = 0001
08-16 12:26:37.577  7733  7944 D bte_conf:   product             = 13a1
08-16 12:26:37.577  7733  7944 D bte_conf:   version             = 1000
08-16 12:26:37.577  7733  7944 D bte_conf:   clientExecutableURL = 
08-16 12:26:37.577  7733  7944 D bte_conf:   serviceDescription  = 
08-16 12:26:37.577  7733  7944 D bte_conf:   documentationURL    = 
08-16 12:26:37.577  7733  7944 D bte_conf: bte_load_did_conf no section named DID2.
08-16 12:26:37.580  7733  7940 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 12:26:37.581  7733  7940 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:26:37.581  7733  7940 D BluetoothAdapterProperties: State =  11
08-16 12:26:37.581  7733  7940 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 12:26:37.581  7733  7940 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 12:26:37.581  7733  7940 D BluetoothAdapterProperties: Setting state to 12
08-16 12:26:37.581  7733  7940 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 12:26:37.582  7733  7944 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 12:26:37.582  7733  7944 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 12:26:37.574  8026  8026 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:37.584  8026  8026 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:37.597  1042  1119 D BluetoothManagerService: Message: 60
08-16 12:26:37.597  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 12:26:37.597  1042  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-16 12:26:37.599  7733  7940 I BluetoothAdapterState: Entering On State
08-16 12:26:37.601  7733  7984 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:37.601  7733  7984 W bt-smp  : Plain text(LSB ~ MSB) = 7d 42 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:37.601  7733  7984 W bt-smp  : Encrypted text(LSB ~ MSB) = d7 2f 13 16 15 a0 47 39 79 bc 97 47 cc e3 ed bc 
08-16 12:26:37.601  7733  7987 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:26:37.601  7733  7984 W bt-btm  : Stopping oneshot timer
08-16 12:26:37.605  7733  7940 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 12:26:37.605  7733  7940 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 12:26:37.605  7733  7940 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 12:26:37.611  7733  7987 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 12:26:37.613  7733  7940 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 12:26:37.614  7733  7987 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:26:37.615  7733  8021 E bt_mct  : hci lib postload completed
08-16 12:26:37.630  7733  7944 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:26:37.631  7733  7944 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 12:26:37.634  7733  7984 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:37.634  7733  7984 W bt-smp  : Plain text(LSB ~ MSB) = fa b4 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:37.634  7733  7984 W bt-smp  : Encrypted text(LSB ~ MSB) = 9d 1b b5 fb 4a 64 9e 50 c5 e3 d4 00 23 ae ae e0 
08-16 12:26:37.634  7733  7984 W bt-btm  : Stopping oneshot timer
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:37.643  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:26:37.646  7733  7984 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:37.646  7733  7984 W bt-smp  : Plain text(LSB ~ MSB) = d5 9e 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:37.647  7733  7984 W bt-smp  : Encrypted text(LSB ~ MSB) = 99 1b f7 70 92 35 b1 16 2d 89 ff ec 75 95 c5 79 
08-16 12:26:37.647  7733  7984 W bt-btm  : Stopping oneshot timer
08-16 12:26:37.650  7733  7940 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 12:26:37.654  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:37.654  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 12:26:37.656  6923  7027 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 12:26:37.668  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:26:37.671  7733  7984 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:37.671  7733  7984 W bt-smp  : Plain text(LSB ~ MSB) = e6 d2 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:37.671  7733  7984 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d da 3b f1 91 3f 27 81 55 87 60 30 57 dc d1 11 
08-16 12:26:37.671  7733  7984 W bt-btm  : Stopping oneshot timer
08-16 12:26:37.681  1837  1837 D BluetoothHeadset: Proxy object connected
,08-16 12:26:37.685  1837  2492 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:26:37.691  7733  7984 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:26:37.691  7733  7984 W bt-smp  : Plain text(LSB ~ MSB) = 39 42 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:26:37.691  7733  7984 W bt-smp  : Encrypted text(LSB ~ MSB) = a3 9c 1c 63 49 d1 07 a8 34 1b 7d 3a 3e f9 ba eb 
08-16 12:26:37.691  7733  7984 W bt-btm  : Stopping oneshot timer
08-16 12:26:37.707  6923  6923 D BluetoothMap: Proxy object connected
08-16 12:26:37.707  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:26:37.707  6923  6923 D MapProfile: Bluetooth service connected
08-16 12:26:37.707  6923  6923 D BluetoothMap: getConnectedDevices()
08-16 12:26:37.709  6923  7027 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:26:37.712  6923  6939 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:26:37.716  1042  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:26:37.718  1042  1042 D BluetoothHeadset: Proxy object connected
08-16 12:26:37.719  6923  6939 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 12:26:37.725  7733  7748 V BluetoothMapService: getConnectedDevices()
,08-16 12:26:37.727  8044  8044 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 12:26:37.728  1042  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:26:37.729  6923  6938 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 12:26:37.730  1042  1042 D BluetoothA2dp: Proxy object connected
08-16 12:26:37.731  6923  6923 D BluetoothHeadset: Proxy object connected
08-16 12:26:37.731  6923  6923 D HeadsetProfile: Bluetooth service connected
08-16 12:26:37.733  6923  6923 D BluetoothA2dp: Proxy object connected
08-16 12:26:37.733  6923  6923 D A2dpProfile: Bluetooth service connected
08-16 12:26:37.734  6923  6939 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:26:37.734  6923  6939 D BluetoothPan: onBluetoothStateChange call bindService
08-16 12:26:37.734  6923  6923 D BluetoothInputDevice: Proxy object connected
08-16 12:26:37.734  6923  6923 D HidProfile: Bluetooth service connected
08-16 12:26:37.737  1837  2675 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:26:37.737  6923  6923 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:26:37.737  6923  6923 D PanProfile: Bluetooth service connected
08-16 12:26:37.739  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:26:37.740  1042  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 12:26:37.740  1042  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 12:26:37.741  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-16 12:26:37.745  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.745  1925  2085 D LGBluetoothAPIService: Message: 1
08-16 12:26:37.745  1925  2085 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 12:26:37.745  1925  2085 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 12:26:37.745  1925  2085 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 12:26:37.746  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:26:37.747  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:37.749  1042  1119 D BluetoothManagerService: Message: 40
08-16 12:26:37.749  1042  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 12:26:37.751  7733  7733 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.751  7733  7733 D BluetoothMapService: STATE_ON
,08-16 12:26:37.754  6923  6923 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 12:26:37.756  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 12:26:37.764  6923  6923 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:26:37.769  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
08-16 12:26:37.769  7733  7733 V BluetoothPbapService: Pbap Service onCreate
08-16 12:26:37.769  7733  7733 V BluetoothPbapService: Starting PBAP service
08-16 12:26:37.770  7733  7733 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 12:26:37.770  7733  7733 V BluetoothMapService: Handler(): got msg=1
08-16 12:26:37.771  7733  7733 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 12:26:37.771  7733  7733 V BluetoothPbapService: Pbap Service onBind
08-16 12:26:37.772  7733  7733 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.772  7733  7733 V BluetoothPbapService: state: 12
08-16 12:26:37.773  7733  7733 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:26:37.773  7733  7733 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.773  7733  7733 V BluetoothPbapReceiver: ***********state = 12
08-16 12:26:37.773  7733  8050 D BluetoothMapMasInstance: MAS initSocket()
08-16 12:26:37.774  6923  6923 D BluetoothPbap: Proxy object connected
08-16 12:26:37.774  6923  6923 D PbapServerProfile: Bluetooth service connected
08-16 12:26:37.774  7733  7733 V BluetoothPbapService: Handler(): got msg=1
08-16 12:26:37.775  7733  7733 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 12:26:37.775  7733  8050 D BluetoothMapMasInstance:   masId = 00
08-16 12:26:37.775  7733  8050 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 12:26:37.775  7733  8050 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 12:26:37.775  7733  8050 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 12:26:37.776  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:26:37.777  1042  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:37.777  2066  2066 D c       : Getting all permits...
08-16 12:26:37.777  2066  2066 D a       : Opening database...
,08-16 12:26:37.779  7733  8051 V BluetoothPbapService: Pbap Service initSocket
08-16 12:26:37.779  7733  8050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:37.779  1042  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:37.780  7733  8051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:37.781  2066  2066 D a       : Opening database auth.proximity.permit_store...
08-16 12:26:37.781  7733  7944 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:26:37.781  7733  7944 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 12:26:37.782  2066  2066 D a       : Closing database...
08-16 12:26:37.783  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:37.783  7733  8050 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 12:26:37.784  7733  8050 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 12:26:37.784  7733  8050 D BluetoothMapMasInstance: Accepting socket connection...
08-16 12:26:37.785  7733  8051 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 12:26:37.785  7733  8051 V BluetoothPbapService: Succeed to create listening socket 
08-16 12:26:37.785  7733  8051 V BluetoothPbapService: Accepting socket connection...
08-16 12:26:37.795  6923  6923 D BluetoothPermissionRequest: onReceive
,08-16 12:26:37.796  6923  6923 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 12:26:37.798  6923  6923 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:26:37.801  7733  7733 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 12:26:37.802  7733  7733 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 12:26:37.808  7733  7733 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 12:26:37.826  7733  7733 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 12:26:37.826  7733  7733 V BtOppService: onCreate
,08-16 12:26:37.830  7733  7733 V BluetoothOppNotification: send message
,08-16 12:26:37.832  7733  7733 V BtOppService: Starting RfcommListener
08-16 12:26:37.836  7733  7733 D BluetoothOppPreference: Dumping Names:  
08-16 12:26:37.836  7733  7733 D BluetoothOppPreference: {}
08-16 12:26:37.836  7733  7733 D BluetoothOppPreference: Dumping Channels:  
08-16 12:26:37.836  7733  7733 D BluetoothOppPreference: {}
08-16 12:26:37.836  7733  7733 V BtOppService: onStartCommand
08-16 12:26:37.839  7733  8059 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:26:37.839  7733  7733 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.839  7733  7733 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 12:26:37.843  7733  7733 V BluetoothOppNotification: new notify threadi!
08-16 12:26:37.844  7733  7733 V BluetoothOppNotification: send delay message
08-16 12:26:37.845  7733  7733 V BtOppService: start RfcommListener
08-16 12:26:37.845  7733  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 12:26:37.846  7733  8056 V BtOppService: Deleted complete outbound shares, number =  0
08-16 12:26:37.847  7733  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26333e7c on behalf of 
08-16 12:26:37.848  7733  8061 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 12:26:37.848  7733  8056 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 12:26:37.848  7733  7733 V BtOppService: RfcommListener started
08-16 12:26:37.849  7733  8056 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 12:26:37.849  7733  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 12:26:37.850  7733  8062 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 12:26:37.851  7733  8056 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c39305 on behalf of 
08-16 12:26:37.851  1042  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:37.852  7733  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14ef4f5a on behalf of 
08-16 12:26:37.852  7733  8062 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:37.853  7733  8061 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 12:26:37.854  7733  8059 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:26:37.854  7733  8061 V BluetoothOppNotification: outbound notification was removed.
08-16 12:26:37.854  7733  8062 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 12:26:37.854  7733  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:26:37.854  7733  8062 V BtOppRfcommListener: Started RFCOMM listener....
08-16 12:26:37.855  7733  8062 I BtOppRfcommListener: Accept thread started.
08-16 12:26:37.855  7733  8062 V BtOppRfcommListener: Accepting connection...
08-16 12:26:37.855  7733  8059 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dae658b on behalf of 
08-16 12:26:37.855  7733  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ab3c668 on behalf of 
08-16 12:26:37.856  7733  8061 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 12:26:37.857  7733  8059 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 12:26:37.857  7733  8061 V BluetoothOppNotification: inbound notification was removed.
08-16 12:26:37.857  7733  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:26:37.859  7733  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@316f5a81 on behalf of 
,08-16 12:26:37.871  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
,08-16 12:26:37.871  7733  7733 V BluetoothFtpService: Ftp Service onCreate
08-16 12:26:37.871  7733  7733 I BluetoothFtpService: Ftp Service onCreate
08-16 12:26:37.872  7733  7733 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:26:37.872  7733  7733 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.872  7733  7733 V BluetoothFtpService: Starting Listening on sockets
08-16 12:26:37.872  7733  7733 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:26:37.873  7733  7733 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:26:37.873  7733  7733 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:26:37.873  7733  7733 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.873  7733  7733 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 12:26:37.873  7733  7733 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 12:26:37.875  7733  7733 V BtOppService: ContentObserver received notification
08-16 12:26:37.875  7733  7733 V BtOppService: ContentObserver received notification
08-16 12:26:37.875  7733  7733 V BluetoothFtpService: Handler(): got msg=1
08-16 12:26:37.876  7733  7733 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 12:26:37.876  7733  7733 V BluetoothFtpService: Ftp Service initSocket
08-16 12:26:37.877  7733  8063 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:26:37.877  7733  8063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:26:37.879  7733  8063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e9bcf67 on behalf of 
08-16 12:26:37.880  7733  8063 V BluetoothOppNotification: update too frequent, put in queue
08-16 12:26:37.881  1042  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:37.881  7733  8063 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 12:26:37.882  7733  7733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:26:37.882  7733  7733 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-16 12:26:37.883  7733  7733 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 12:26:37.886  7733  8064 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 12:26:37.900  7733  7733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f8d8dc0
,08-16 12:26:37.900  7733  7733 V BluetoothSapService: Sap Service onCreate
,08-16 12:26:37.902  7733  7733 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:26:37.902  7733  7733 V BluetoothSapService: state: 12
08-16 12:26:37.903  7733  7733 V BluetoothSapService: Starting SAP server process
08-16 12:26:37.894  8065  8065 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:37.894  8065  8065 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:37.906  7733  7733 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 12:26:37.907  7733  8066 V BluetoothSapService: Sap Service initRfcommSocket
08-16 12:26:37.908  1042  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:37.909  7733  8066 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:26:37.910  7733  8066 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 12:26:37.910  7733  8066 V BluetoothSapService: Succeed to create listening socket 
08-16 12:26:37.910  7733  8066 V BluetoothSapService: Accepting socket connection...
08-16 12:26:37.916  8065  8065 V BT_SAP  : Event pipe created
08-16 12:26:37.916  8065  8065 V BT_SAP  : create_server_socket qcom.sap.server
08-16 12:26:37.916  8065  8065 V BT_SAP  : created socket fd 6
,08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:38.271  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:26:38.276  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:38.278  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:38.278  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fbc5cab added. We now have 8 listener(s)
08-16 12:26:38.278  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:38.281  1042  1637 D WifiServiceImplEx: setWifiEnabled: false pid=6803, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:26:38.282  1042  1637 D WifiService: setWifiEnabled: false pid=6803, uid=10118
08-16 12:26:38.282  1042  1637 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:26:38.286  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:26:38.290  1042  1971 D WifiServiceImplEx: setWifiEnabled: true pid=6803, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:26:38.291  1042  1971 D WifiService: setWifiEnabled: true pid=6803, uid=10118
08-16 12:26:38.291  1042  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:26:38.307  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:26:38.308  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:26:38.308  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-16 12:26:38.309  1042  1521 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 12:26:38.309  1042  1521 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 12:26:38.312  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 12:26:38.312  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:26:38.312  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 12:26:38.312  1042  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:26:38.312  1042  1521 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 12:26:38.312  1042  1521 E WifiHW  : unknown target_country: EU , set to default
08-16 12:26:38.312  1042  1521 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 12:26:38.312  1042  1521 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 12:26:38.312  1042  1521 I WifiUtil: gEnableBmps=1
08-16 12:26:38.853  7733  7733 V BluetoothOppNotification: new notify threadi!
08-16 12:26:38.853  7733  7733 V BluetoothOppNotification: send delay message
,08-16 12:26:38.895   314   900 D SoftapController: Softap fwReload - Ok
,08-16 12:26:38.904  1042  1521 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (587ms)
08-16 12:26:38.919   314   900 D CommandListener: Setting iface cfg
08-16 12:26:38.919   314   900 D CommandListener: Trying to bring down wlan0
,08-16 12:26:38.924  1042  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 12:26:38.925   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:26:38.927  1042  1521 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 12:26:38.935  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:38.935  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:38.935  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:38.936  1042  1521 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 12:26:38.936  1042  1521 D WifiMonitor: connecting to supplicant
08-16 12:26:38.936  1042  1521 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-16 12:26:38.934  8087  8087 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:38.944  8087  8087 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 12:26:38.986  7733  8085 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 12:26:38.988  7733  8085 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@90bfb03 on behalf of 
08-16 12:26:38.990  7733  8085 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 12:26:38.993  7733  8085 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 12:26:38.995  7733  8085 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27e6fa80 on behalf of 
08-16 12:26:38.996  7733  8085 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 12:26:38.998  7733  8085 V BluetoothOppNotification: outbound notification was removed.
08-16 12:26:38.999  7733  8085 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:26:39.001  7733  8085 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cabd8b9 on behalf of 
08-16 12:26:39.002  7733  8085 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 12:26:39.003  8087  8087 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 12:26:39.007  7733  8085 V BluetoothOppNotification: inbound notification was removed.
08-16 12:26:39.007  7733  8085 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:26:39.008  7733  8085 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2949d4fe on behalf of 
,08-16 12:26:39.018  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:39.023  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:39.024  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 12:26:39.024  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 12:26:39.025  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:26:39.026  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-16 12:26:39.026  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:26:39.026  6923  6923 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:26:39.026  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:26:39.027  6923  6923 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:26:39.027  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 12:26:39.027  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:26:39.027  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:26:39.027  6923  6923 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:26:39.027  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 12:26:39.027  6923  6923 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 12:26:39.038  8087  8087 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 12:26:39.039  8087  8087 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 12:26:39.042  1042  1119 D Tethering: InitialState.processMessage what=4
,08-16 12:26:39.079  1042  1637 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8104 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 12:26:39.080  1042  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 12:26:39.126  8087  8087 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 12:26:39.173  8087  8087 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 12:26:39.182  8087  8087 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 12:26:39.216  1042  1942 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8126 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:26:39.227  8104  8124 W FormManager: Network not available. Please check & try again.
08-16 12:26:39.231  8104  8125 V FormManager: Network unavailable.
,08-16 12:26:39.235  8104  8125 V FormManager: Network unavailable.
08-16 12:26:39.255  1042  1924 I ActivityManager: Killing 7205:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 12:26:39.297  1042  1942 W libprocessgroup: failed to open /acct/uid_10057/pid_7205/cgroup.procs: No such file or directory
08-16 12:26:39.357  8126  8126 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:26:39.364  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:26:39.374  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:39.377  1042  2014 I ActivityManager: Killing 7229:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 12:26:39.444  1042  2020 W libprocessgroup: failed to open /acct/uid_10062/pid_7229/cgroup.procs: No such file or directory
,08-16 12:26:39.461  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:26:39.461  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-16 12:26:39.461  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-16 12:26:39.461  6923  6923 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:26:39.462  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:26:39.462  6923  6923 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:26:39.462  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 12:26:39.463  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:26:39.463  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:26:39.463  6923  6923 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:26:39.463  6923  6923 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:26:39.869  8087  8087 E wpa_supplicant: USIM:  scard_init function
,08-16 12:26:39.890  8087  8087 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 12:26:39.941  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:26:39.941  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 12:26:39.941  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:26:39.942  1042  1521 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:26:39.942  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:39.943  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:39.943  1042  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:39.943  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:39.944  1042  1521 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 12:26:39.944  1042  1521 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-16 12:26:39.948  1042  1521 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 12:26:39.948  1042  1521 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 12:26:39.948  1042  1521 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 12:26:39.951  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:39.951  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:39.951  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:39.951  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:39.951  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:26:39.952  1042  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:26:39.952  1042  1521 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:26:39.952  1042  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:26:39.957  1925  1925 D WfdService: Waiting for WifiP2p enabling
,08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:39.966  6803  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:26:39.968  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:26:39.974  6803  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:26:39.977  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 12:26:39.978  1042  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 12:26:39.981  1042  1521 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 12:26:39.983  1042  1521 D WifiNative-wlan0: SET update_config 1: returned true
08-16 12:26:39.983  1042  1521 D WifiConfigStore: Loading config and enabling all networks 
08-16 12:26:39.983  1042  1521 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 12:26:39.983  1042  1521 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-16 12:26:39.992  1042  1521 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 12:26:40.007  1042  1521 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 12:26:40.007  1042  1521 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 12:26:40.011  1042  1521 D WifiStateMachine: enableVerboseLogging : level 2
08-16 12:26:40.011  1042  1521 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 12:26:40.012  1042  1521 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 12:26:40.012  1042  1521 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 12:26:40.012  1042  1521 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 12:26:40.012  1042  1521 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 12:26:40.013  1042  1521 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 12:26:40.013  1042  1521 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 12:26:40.013  1042  1521 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 12:26:40.013  1042  1521 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 12:26:40.014  1042  1521 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 12:26:40.014  1042  1521 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 12:26:40.014  1042  1521 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 12:26:40.014  1042  1521 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 12:26:40.015  1042  1521 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 12:26:40.017  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-16 12:26:40.020  8087  8087 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 12:26:40.029  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 12:26:40.029  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 12:26:40.029  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 12:26:40.029  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 12:26:40.029  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:40.029  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:40.017  1925  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 12:26:40.043  1925  2258 D WfdsService: Set the WFDS Monitor: true
08-16 12:26:40.043  1925  2258 D WfdsMonitor: WfdsMonitorThread create
08-16 12:26:40.043  1925  2258 D WfdsMonitor: WFDS Monitor is created and started
08-16 12:26:40.043  1925  2258 D WfdsService: WiFi: Supplicant connection re-established
08-16 12:26:40.045  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:40.045  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:40.046  1042  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 12:26:40.047  1042  1521 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120,
,08-16 12:26:40.049  1042  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 12:26:40.049  8087  8087 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:26:40.050  8087  8087 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:26:40.053  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 12:26:40.053  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:26:40.053  1042  8156 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:26:40.053  1042  1521 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 12:26:40.053  1042  1521 D WifiNative-HAL: Setting external_sim to 1
08-16 12:26:40.053  1042  1521 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 12:26:40.053  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 12:26:40.053  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:26:40.054  1042  8156 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:26:40.054  1042  1521 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 12:26:40.054  1042  1521 I WifiNative-HAL: startHal
08-16 12:26:40.054  1042  1521 D wifi    : setting scan oui 0xaf65b700
08-16 12:26:40.054  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:40.054  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:40.054  1042  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 12:26:40.054  1042  1521 I WifiNative-HAL: startHal
08-16 12:26:40.054  1042  1521 D wifi    : setting scan oui 0xaf65b700
08-16 12:26:40.055  1042  1521 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 12:26:40.055  1042  1521 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
,08-16 12:26:40.055  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 12:26:40.055  7761  7761 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.055  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 12:26:40.056  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 12:26:40.056  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:26:40.056  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:26:40.057  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:26:40.057  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 12:26:40.057  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 12:26:40.057  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 12:26:40.057  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:26:40.057  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:26:40.058  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 12:26:40.058  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:26:40.058  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:26:40.059  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:26:40.059  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 12:26:40.059  8087  8087 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 12:26:40.060  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 12:26:40.060  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:26:40.060  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:26:40.064  1042  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 12:26:40.064  1042  1521 E WifiNative: : [214,060,708 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 12:26:40.064  1042  1521 D WifiNative-wlan0: doBoolean: RECONNECT
,08-16 12:26:40.065  1042  1521 D WifiNative-wlan0: RECONNECT: returned true
08-16 12:26:40.065  1042  1521 D WifiNative-wlan0: doString: [STATUS]
08-16 12:26:40.066  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:40.066  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:40.067  1042  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:26:40.067  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:40.067  8126  8126 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:40.068  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:26:40.068  1042  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.070   314   900 D CommandListener: Setting iface cfg
08-16 12:26:40.070   314   900 D CommandListener: Trying to bring up p2p0
08-16 12:26:40.070  1042  1520 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 12:26:40.070  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 12:26:40.070  1042  1520 D LGWifiP2pService: P2pEnablingState
08-16 12:26:40.070  1042  1520 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.070  1042  1042 D RttService: SCAN_AVAILABLE : 3
08-16 12:26:40.070  1042  1520 D LGWifiP2pService: P2p socket connection successful
,08-16 12:26:40.070  1042  1520 D LGWifiP2pService: P2pEnabledState
08-16 12:26:40.071  1042  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.071  1042  1539 I WifiNative-HAL: startHal
08-16 12:26:40.071  1042  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf65b700
08-16 12:26:40.071  1042  1539 D wifi    : failed to get capabilities : -3
08-16 12:26:40.071  1042  1539 E WifiScanningService: could not get scan capabilities
08-16 12:26:40.071  1042  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.072  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 12:26:40.072  1925  1925 D WfdsService: WifiP2pState is changed : true
08-16 12:26:40.072  1925  2258 D WfdsService: Receive the WFDS_ENABLE Method
08-16 12:26:40.072  1925  2258 D WfdsService: Set the WFDS Monitor: true
08-16 12:26:40.072  1925  2258 D WfdsService: Connected to the supplicant for wfds
08-16 12:26:40.072  1925  2258 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 12:26:40.072  1925  2258 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
08-16 12:26:40.072  1925  2258 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
08-16 12:26:40.072  1925  2258 D WfdsService: selectPreferredScanChannel [36]
08-16 12:26:40.072  1925  2258 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 12:26:40.072  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:26:40.073  1042  1521 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:26:40.073  1042  1521 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 12:26:40.073  1042  1521 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 12:26:40.074  1042  1521 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 12:26:40.074  1042  1521 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 12:26:40.074  1042  1521 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 12:26:40.075  1042  1520 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 12:26:40.075  1042  1521 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 12:26:40.075  1042  1521 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 12:26:40.075  1042  1520 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 12:26:40.075  8087  8087 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 12:26:40.076  1042  1520 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 12:26:40.076  1042  1521 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 12:26:40.076  1042  1520 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 12:26:40.076  1042  1520 D WifiNative-p2p0: SET device_name G3: returned true
08-16 12:26:40.076  1042  1520 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 12:26:40.076  1042  1520 D LGWifiP2pService: before postfix = G3
08-16 12:26:40.076  1042  1520 D WifiServerServiceExt: postfix byte check : 2
08-16 12:26:40.076  1042  1520 D LGWifiP2pService: after postfix = G3
08-16 12:26:40.077  1042  1520 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 12:26:40.077  1042  1521 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 12:26:40.077  1042  1521 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 12:26:40.077  1042  1520 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 12:26:40.077  1042  1521 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 12:26:40.077  1042  1520 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 12:26:40.077  8087  8087 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 12:26:40.078  1042  1520 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 12:26:40.078  1042  1520 D WifiNative-p2p,0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 12:26:40.079  1042  1520 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 12:26:40.079  1042  1520 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-16 12:26:40.079  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 12:26:40.080  1042  1520 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 12:26:40.080  1042  1520 D WifiNative-HAL: p2pGetDeviceAddress
08-16 12:26:40.080  1042  1520 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 12:26:40.081  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=214077  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 12:26:40.081  1925  8169 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 12:26:40.082  1925  8169 E CtrlSupplicant: Succeed to open control connection
08-16 12:26:40.082  1925  8169 E CtrlSupplicant: Succeed to open monitor connection
08-16 12:26:40.082  1042  1520 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 12:26:40.082  1042  1520 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 12:26:40.083  1042  1520 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 12:26:40.083  1042  1520 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 12:26:40.083  1042  1520 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 12:26:40.083  1042  1520 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 12:26:40.084  1042  1520 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 12:26:40.084  1042  1520 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 12:26:40.084  1925  1925 D WfdsService: isConnected: false
08-16 12:26:40.084  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 12:26:40.084  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 12:26:40.084  1925  1925 D WfdsService: Update P2p Interface State: 3
08-16 12:26:40.085  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:40.085  1925  8169 D WfdsMonitor: Supplicant connection established
08-16 12:26:40.085  1925  2258 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-16 12:26:40.089  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=214085  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 12:26:40.090  1042  1521 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214086
08-16 12:26:40.090  1042  1521 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214087
,08-16 12:26:40.094  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.094  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.094  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 12:26:40.095  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.095  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:40.096  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.097  1042  1520 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 12:26:40.097  1042  1520 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 12:26:40.097  1042  1520 D LGWifiP2pService: InactiveState
08-16 12:26:40.097  1042  1520 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.097  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.097  1042  1520 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 12:26:40.098  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 12:26:40.098  1042  1521 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214095
08-16 12:26:40.098  8087  8087 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:40.098  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214095
08-16 12:26:40.099  1042  1521 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214095
08-16 12:26:40.099  8087  8087 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 12:26:40.099  8087  8087 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.099  1042  1520 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 12:26:40.099  1042  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.099  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.099  1042  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.099  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=214096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  8087  8087 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  1042  1520 D LGWifiP2,pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.100  1042  1520 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.101  1042  8156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:26:40.101  1042  8156 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:40.101  1042  8156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:40.101  1042  8156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:26:40.101  1042  8156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:40.101  1042  8156 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.101  1042  8156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.101  1042  8156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.101  1042  8156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:40.101  1042  8156 E WifiMonitor: WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.101  1042  8156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.101  1042  8156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:26:40.101  1925  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:26:40.102  1925  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:40.102  1925  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:26:40.102  1042  1042 E WifiServerServiceExt: No p2p device connected
,08-16 12:26:40.102  1925  2258 W WfdsService: DefaultState - msg [9441285] is not handled
,08-16 12:26:40.111  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:26:40.111  4660  4660 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:26:40.114  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.114  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:26:40.114  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 12:26:40.115  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=214112  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:26:40.116  1042  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=214112  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 12:26:40.116  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.116  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:40.118  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.118  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=214115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 12:26:40.119  1042  1521 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:40.119  1042  1521 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:40.120  1042  1521 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:40.120  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:40.122  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.122  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.122  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 12:26:40.122  1042  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:26:40.123  1042  1521 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=214119
08-16 12:26:40.123  1042  1521 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=214120
08-16 12:26:40.124  1042  1521 D WifiNative-wlan0: doString: [STATUS]
08-16 12:26:40.124  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:40.124  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:26:40.125  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:26:40.126  1042  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:26:40.127  4660  4660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:26:40.128  1042  1521 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 12:26:40.128  8104  8176 V FormManager: Network unavailable.
,08-16 12:26:40.131  8104  8175 W FormManager: Network not available. Please check & try again.
08-16 12:26:40.134  1042  1521 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 12:26:40.134  1042  1521 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 12:26:40.135  8104  8176 V FormManager: Network unavailable.
08-16 12:26:40.138  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:26:40.138  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:26:40.138  6923  6923 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:26:40.138  6923  6923 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:26:40.139  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.139  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:40.140  4660  8178 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:26:40.140  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:26:40.143  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.144  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.144  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:26:40.144  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.144  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.144  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:26:40.146  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:26:40.146  6923  6923 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:26:40.146  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 12:26:40.146  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:26:40.147  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:26:40.147  6923  6923 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:26:40.147  6923  6923 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 12:26:40.147  6923  6923 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:26:40.148  4660  8179 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:26:40.148  4660  8179 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 12:26:40.150  1042  1521 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 12:26:40.150  1042  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:26:40.150  1042  1527 D ConnectivityService: Got NetworkAgent Messenger
08-16 12:26:40.150  1042  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:26:40.150  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 12:26:40.150  1042  1527 D ConnectivityService: NetworkAgent connected
08-16 12:26:40.150  1042  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:26:40.151  1042  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:26:40.156  1042  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:26:40.156  1042  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:26:40.156  1042  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:26:40.156  1042  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:26:40.156  1042  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 12:26:40.159  1042  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:26:40.161   314   900 D CommandListener: Setting iface cfg
08-16 12:26:40.171  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 12:26:40.171  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:40.172  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.174  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.174  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:40.175  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.190  1042  1943 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8183 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 12:26:40.195  1042  1521 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 12:26:40.195  1042  8182 D DhcpStateMachine: StoppedState
08-16 12:26:40.195  1042  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=214192  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.196  1042  8182 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.196  1042  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=214192  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.196  1042  8182 D DhcpStateMachine: WaitBeforeStartState
08-16 12:26:40.196  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=214193  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.197  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 12:26:40.197  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 12:26:40.198  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:26:40.198  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:26:40.198  1042  1521 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:26:40.199  1042  1521 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:26:40.199  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 12:26:40.199  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 12:26:40.199  8087  8087 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:40.199  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 12:26:40.200  1042  1521 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 12:26:40.200  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:40.200  1042  1521 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 12:26:40.200  1042  8156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:40.200  1042  8156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:26:40.200  1042  1521 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 12:26:40.200  1042  1521 D WifiNative-wlan0: doBoolean: SCAN
08-16 12:26:40.201  8087  8087 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 12:26:40.201  1042  8156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 12:26:40.201  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 12:26:40.201  1042  8156 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:26:40.201  1042  8156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:26:40.201  1042  1521 D WifiNative-wlan0: SCAN: returned true
08-16 12:26:40.202  1042  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=214198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.202  1042  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=214199  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.203  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=214199  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.203  1042  1521 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:40.204  1042  1521 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:40.204  1042  1521 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:40.204  1042  1521 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHAN,GED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:40.205  1042  1521 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:40.205  1042  1521 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:26:40.206  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:40.206  1042  1042 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-16 12:26:40.210  1042  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=214206  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.210  1042  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=214207  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.211  1042  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=214207  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:26:40.211  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:40.211  1042  1042 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 12:26:40.212  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14143] from screen [on:0 period:-1830582316] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:26:40.213  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1830582315] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:26:40.213  1042  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:26:40.307  8183  8183 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 12:26:40.308  8183  8183 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 12:26:40.317  8183  8183 V [BNRBootReceiver]: Boot Receiver Return
08-16 12:26:40.317  8183  8183 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:26:40.327  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:26:40.329  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:26:40.342  6803  6882 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 12:26:40.344  6803  6882 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 12:26:40.348  6803  6882 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8c9c497 Bundle[{}]
08-16 12:26:40.351  6803  6882 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 12:26:40.351  6803  6882 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 12:26:40.352  6803  6882 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 12:26:40.352  6803  6882 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 12:26:40.353  6803  6882 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 12:26:40.354  6803  6882 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 12:26:40.361  6803  6882 I System.out: Running OutgoingSocketThread
08-16 12:26:40.363  6803  8201 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 906)
08-16 12:26:40.364  6803  8201 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55610
08-16 12:26:40.365  6803  8201 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 12:26:40.400  1042  1059 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8202 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:26:40.402  1042  1059 I ActivityManager: Killing 7246:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 12:26:40.424   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 23.462ms
,08-16 12:26:40.445   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 20.530ms
,08-16 12:26:40.462  1042  1971 W libprocessgroup: failed to open /acct/uid_10085/pid_7246/cgroup.procs: No such file or directory
,08-16 12:26:40.464  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 12:26:40.464  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.464  1042  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.465  1042  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.465  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.465   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 19.547ms
08-16 12:26:40.465  1042  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 12:26:40.466  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.466  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.467  1042  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-16 12:26:40.467  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
08-16 12:26:40.468  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
08-16 12:26:40.468  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 12:26:40.468  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 12:26:40.468  1042  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 12:26:40.469  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 12:26:40.469  1042  1521 D WifiNative-wlan0: SET ps 0: returned true
08-16 12:26:40.469  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,08-16 12:26:40.470  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 12:26:40.471  1042  8156 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 12:26:40.471  1042  8156 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 12:26:40.471  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 12:26:40.471  1042  1521 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 12:26:40.471  1042  1521 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:26:40.471  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21624154 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.471  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21624154 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.471  1042  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 12:26:40.471  1042  8182 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.471  1042  8182 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 12:26:40.471  1925  8169 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-16 12:26:40.472  1925  8169 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-16 12:26:40.472  1042  8156 E WifiMonitor: WifiMonitor:p2p0 cnt=60 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 12:26:40.472  1042  8156 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 12:26:40.472  1042  8156 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-16 12:26:40.472  1042  8156 E WifiMonitor: WifiMonitor:p2p0 cnt=61 dispatchEvent: WPS-AP-AVAILABLE 
08-16 12:26:40.472   314   900 D CommandListener: Setting iface cfg
08-16 12:26:40.473   314   900 D CommandListener: Trying to bring up wlan0
08-16 12:26:40.473  1042  8156 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 12:26:40.472  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.473  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.473  1042  1520 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.474  1042  1521 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 12:26:40.475  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:40.475  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:26:40.476  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:40.476  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:26:40.477  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:26:40.477  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:26:40.478  1042  1521 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:26:40.478  1042  1521 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:26:40.479  1042  1521 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:26:40.479  1042  1521 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:26:40.480  1042  1521 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:26:40.480  1042  1521 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-16 12:26:40.487  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 12:26:40.487  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.488  1042  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.491  1042  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.492  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.493  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:26:40.494  1042  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 12:26:40.494  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-16 12:26:40.496  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 12:26:40.497  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:26:40.497  1042  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.497  1042  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.497  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:26:40.497  1042  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:26:40.497  1042  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 12:26:40.498  8087  8087 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 12:26:40.498  1042  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 12:26:40.498  1042  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:26:40.505  8202  8202 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:40.514  1042  1521 D WifiNative-wlan0: SET ps 1: returned true
,08-16 12:26:40.517  1042  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 12:26:40.518  1042  1521 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:26:40.518  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:26:40.518  1042  1521 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 12:26:40.519  1042  1527 D ConnectivityService: ignoring duplicate network state non-change
08-16 12:26:40.522  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.522  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:26:40.523  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.523  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.523  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:26:40.524  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.527  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.527  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.527  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:26:40.527  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.528  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 12:26:40.529  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.530  1042  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 12:26:40.531  1042  1527 D ConnectivityService: Adding iface wlan0 to network 102
08-16 12:26:40.533  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 12:26:40.536  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 12:26:40.538  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.538  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.538  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:26:40.541  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 12:26:40.550  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.550  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:26:40.550  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.551  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.551  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:26:40.551  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:26:40.551  1042  1521 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 12:26:40.554  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:26:40.554  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:26:40.556  8202  8202 D PluginManager: init()
08-16 12:26:40.557  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:26:40.573  1042  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 12:26:40.573  1042  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 12:26:40.573  1042  1521 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 12:26:40.574  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 12:26:40.574  1042  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 12:26:40.575   314   900 E Netd    : netlink response contains error (File exists)
08-16 12:26:40.575  1042  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 12:26:40.581  1042  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 12:26:40.581  1042  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 12:26:40.581  1042  1527 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 12:26:40.583  1042  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 12:26:40.583  1042  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 12:26:40.583  1042  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 12:26:40.583  1042  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 12:26:40.583  1042  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:40.583  1042  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:40.583  1042  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:26:40.583  1042  8180 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.583  1042  8180 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 12:26:40.583  1042  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.583  1042  8180 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:26:40.583  1042  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 12:26:40.583  1042  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-16 12:26:40.583  1042  1527 D ConnectivityService:    accepting network in place of null
08-16 12:26:40.583  1042  8180 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 12:26:40.583  1042  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.584  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.584  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:26:40.586  1042  1521 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.586  1042  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:40.586   314  8222 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-16 12:26:40.589  1042  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 12:26:40.589  1042  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 12:26:40.590  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:26:40.590  1042  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:26:40.590  1042  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 12:26:40.590  1042  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 12:26:40.591  1042  1527 D ConnectivityService: validation of new default Network = false
08-16 12:26:40.591  1042  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 12:26:40.591  1042  1527 D DSQN    : enableDataServiceNotify 
08-16 12:26:40.591  1042  1527 D DSQN    : start dsqn bin
08-16 12:26:40.592  1042  1042 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 12:26:40.592  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:26:40.592  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:26:40.592  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:26:40.598  1042  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,08-16 12:26:40.599  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.599  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:40.599  1042  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:40.600  1586  2083 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 12:26:40.603  1042  1519 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 12:26:40.594  8223  8223 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:40.594  8223  8223 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:40.618  8223  8223 E DSQN    : DSQN ssw
,08-16 12:26:40.622  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 12:26:40.624  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.625  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.638   314  8222 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 12:26:40.673   314  8222 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 12:26:40.677  1042  8182 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 12:26:40.679  1042  8182 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 12:26:40.679  1042  8182 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 12:26:40.674  8227  8227 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 12:26:40.674  8227  8227 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:26:40.708   314   899 D LGDataListener: argv[0]=dsqncommand
08-16 12:26:40.708   314   899 D LGDataListener: argv[1]=wlan0
08-16 12:26:40.708   314   899 D LGDataListener: argv[2]=1
08-16 12:26:40.708   314   899 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 12:26:40.708  1042  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 12:26:40.708  1042  1117 D DSQN    : start to monitor internet connection
08-16 12:26:40.711  8227  8227 I dhcpcd  : version 5.5.6 starting
,08-16 12:26:40.714  8227  8227 E dhcpcd  : get_duid: m
08-16 12:26:40.714  8227  8227 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 12:26:40.714  8227  8227 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 12:26:40.744  1042  8180 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:26:40 GMT], X-Android-Received-Millis=[1471343200744], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471343200707]}
08-16 12:26:40.744  1042  8180 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 12:26:40.744  1042  8180 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 12:26:40.744  1042  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 12:26:40.744  1042  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 12:26:40.744  1042  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:26:40.744  1042  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:40.744  1042  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:26:40.744  1042  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 12:26:40.744  1042  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 12:26:40.745  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.745  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:40.745  1042  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:40.745  1042  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.745  1042  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 12:26:40.746  1586  2083 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 12:26:40.746  1042  1521 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.746  1042  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 12:26:40.747  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:40.748  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-16 12:26:40.760  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 12:26:40.761  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.762  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:26:40.792  8227  8227 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-16 12:26:40.793  8227  8227 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-16 12:26:40.793  8227  8227 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:26:40.793  8227  8227 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 12:26:40.793  8227  8227 D dhcpcd  : wlan0: sending REQUEST (xid 0x285843ec), next in 4.76 seconds
08-16 12:26:40.831  8227  8227 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 12:26:40.851  8227  8227 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-16 12:26:40.851  8227  8227 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 12:26:40.853  8227  8227 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 12:26:40.853  8227  8227 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 12:26:40.853  8227  8227 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:26:40.854  8227  8227 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 12:26:40.854  8227  8227 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 12:26:40.854  8227  8227 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 12:26:40.871  8202  8202 W ExternalStrings: load override strings
08-16 12:26:40.871  8202  8202 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:26:40.871  8202  8202 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 12:26:40.873  8202  8202 D StatusProvider: onCreate
08-16 12:26:40.913  8202  8202 V Signer  : override build config not found
08-16 12:26:40.914  8202  8202 D Signer  : value of property debug is false
,08-16 12:26:40.938  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 12:26:40.938  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-16 12:26:40.938  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 12:26:40.938  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 12:26:40.939  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 12:26:40.939  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 12:26:40.939  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 12:26:40.939  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 12:26:40.939  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 12:26:40.939  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 12:26:40.940  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 12:26:40.940  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 12:26:40.940  8202  8202 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 12:26:40.947  8202  8202 V LGMDMManager: Create singleton instance
08-16 12:26:40.985  8202  8202 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 12:26:41.022  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:41.030  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.031  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:41.040  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:41.083  1042  8182 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 12:26:41.084  1042  1059 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8264 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 12:26:41.084  1042  1059 I ActivityManager: Killing 7278:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-16 12:26:41.086  1042  8182 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 12:26:41.086  1042  8182 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 12:26:41.087  1042  8182 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 12:26:41.087  1042  8182 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 12:26:41.087  1042  8182 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:26:41.087  1042  8182 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 12:26:41.087  1042  8182 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 12:26:41.087  1042  8182 D DhcpStateMachine: RunningState
08-16 12:26:41.174  8202  8253 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 12:26:41.310  1042  1971 W libprocessgroup: failed to open /acct/uid_10093/pid_7278/cgroup.procs: No such file or directory
,08-16 12:26:41.343  8264  8264 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:26:41.362  6803  6882 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 907)
08-16 12:26:41.362  6803  6882 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 907)
08-16 12:26:41.367  6803  6882 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 912)
08-16 12:26:41.369  6803  6882 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 12:26:41.369  6803  6882 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 913)
08-16 12:26:41.373  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.373  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb1bf08 added. We now have 2 listener(s)
08-16 12:26:41.374  1042  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:26:41.380  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.380  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.381  8264  8264 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 12:26:41.381  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.382  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.382  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3212f6a1 added. We now have 9 listener(s)
08-16 12:26:41.382  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.382  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:26:41.389  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:41.396  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:41.398  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.398  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:41.398  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.398  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e21887 added. We now have 3 listener(s)
08-16 12:26:41.399  1042  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.402  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.402  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.402  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:26:41.402  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.402  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2827c3b4 added. We now have 10 listener(s)
08-16 12:26:41.402  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.402  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:41.402  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:41.402  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:41.402  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.402  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.402  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.403  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.403  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb1bf08 removed from the list
08-16 12:26:41.403  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.403  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3212f6a1 removed from the list
08-16 12:26:41.403  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.405  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.405  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:41.405  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.406  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.406  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.407  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.407  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.407  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.407  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3212f6a1 not in the list
08-16 12:26:41.407  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.407  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.408  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.408  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.408  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.408  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: L,istener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2827c3b4 removed from the list
08-16 12:26:41.408  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.408  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.408  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.408  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.408  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e21887 removed from the list
08-16 12:26:41.409  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.409  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c75bdd added. We now have 2 listener(s)
08-16 12:26:41.410  1042  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.412  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.412  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.412  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.412  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.413  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37cda352 added. We now have 9 listener(s)
08-16 12:26:41.413  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-16 12:26:41.413  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:26:41.417  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:41.421  8264  8264 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 12:26:41.421  8264  8264 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:41.421  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:41.421  8264  8264 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 12:26:41.422  8264  8264 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 12:26:41.422  8264  8264 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 12:26:41.423  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.423  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:41.424  8264  8264 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-16 12:26:41.426  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.428  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.428  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.428  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29576720 added. We now have 3 listener(s)
08-16 12:26:41.428  1042  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.430  8264  8264 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 12:26:41.431  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.431  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.431  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.432  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.432  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e62d8d9 added. We now have 10 listener(s)
08-16 12:26:41.432  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.432  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:41.432  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:26:41.432  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:26:41.432  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:41.432  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:26:41.436  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:26:41.436  1042  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.438  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.440  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:26:41.445  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:26:41.445  8264  8264 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:41.446  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 12:26:41.452  1042  1521 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:26:41.452  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:26:41.452  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.452  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:26:41.453  1042  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:26:41.453  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.453  1042  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:26:41.453  1042  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:26:41.454  1042  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:26:41.454  1042  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 12:26:41.454  1042  1527 D ConnectivityService: identical MTU - not setting
08-16 12:26:41.455  1042  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 12:26:41.455  1042  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 12:26:41.455  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:26:41.455  1042  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 12:26:41.455  1042  1527 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:26:41.456  6803  6882 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:26:41.457  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:41.457  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:41.457  1586  2083 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 12:26:41.452  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.460  8264  8264 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 12:26:41.461  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:41.461  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:41.461  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:41.461  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.461  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.461  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.461  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.461  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c75bdd removed from the list
,08-16 12:26:41.461  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.461  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37cda352 removed from the list
08-16 12:26:41.461  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:41.461  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:41.463  8264  8264 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 12:26:41.463  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.463  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.464  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.464  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.464  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.464  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37cda352 not in the list
08-16 12:26:41.464  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.464  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.465  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.465  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:41.466  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:41.466  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.466  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.466  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e62d8d9 removed from the list
08-16 12:26:41.466  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.466  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.466  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.466  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.466  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29576720 removed from the list
08-16 12:26:41.469  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.469  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c1bd54c added. We now have 2 listener(s)
08-16 12:26:41.470  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:41.472  1042  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.475  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.475  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.475  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:41.475  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.475  6803  6882 V org.t,haliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.476  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@379f2995 added. We now have 9 listener(s)
08-16 12:26:41.476  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.477  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:26:41.482  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:41.485  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.485  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.485  8264  8264 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:41.488  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:26:41.489  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.490  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.491  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.491  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:41.491  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.491  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d71c69b added. We now have 3 listener(s)
08-16 12:26:41.493  8202  8253 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:41.493  8202  8253 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:26:41.493  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.495  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.495  1042  1693 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.498  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:41.499  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.499  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.499  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.499  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.499  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ad6fa38 added. We now have 10 listener(s)
08-16 12:26:41.499  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.499  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:41.500  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:41.500  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:26:41.500  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:26:41.500  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:41.500  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:26:41.504  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:26:41.504  1042  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.507  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:41.510  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:26:41.511  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:26:41.514  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:26:41.514  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.515  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.515  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.515  8264  8264 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:41.517  6803  6882 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:26:41.517  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:41.517  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:41.517  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:41.517  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.517  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.517  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.517  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.517  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c1bd54c removed from the list
08-16 12:26:41.517  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.518  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@379f2995 removed from the list
08-16 12:26:41.518  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:41.518  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.518  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.518  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.518  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.519  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.520  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.521  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.521  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.521  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@379f2995 not in the list
08-16 12:26:41.521  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list ,- probably already removed
08-16 12:26:41.521  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.521  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.522  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:41.522  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:41.522  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.522  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.522  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ad6fa38 removed from the list
08-16 12:26:41.522  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.523  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.523  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:41.523  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.523  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d71c69b removed from the list
08-16 12:26:41.523  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.523  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e1c3177 added. We now have 2 listener(s)
08-16 12:26:41.526  1042  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.526  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:41.529  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.529  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.529  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.529  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.529  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d81e4 added. We now have 9 listener(s)
08-16 12:26:41.529  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.530  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:26:41.534  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:41.536  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:41.539  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:41.541  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.542  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:41.542  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.543  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c618502 added. We now have 3 listener(s)
08-16 12:26:41.543  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.544  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.544  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.544  8264  8264 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:41.545  1042  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.546  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.548  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.548  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.548  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.548  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.548  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d986e13 added. We now have 10 listener(s)
08-16 12:26:41.548  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.548  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.548  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:41.548  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:26:41.548  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, sta,rt advertiser: false
08-16 12:26:41.548  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:41.548  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:26:41.548  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 12:26:41.603  8202  8253 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-16 12:26:41.673  1042  1888 I art     : Explicit concurrent mark sweep GC freed 79219(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.938ms total 122.858ms
,08-16 12:26:41.681  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:41.684  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:26:41.684  1042  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.687  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:26:41.687  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:26:41.689  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:26:41.690  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.692  6803  6882 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 12:26:41.695  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:41.695  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:41.695  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:41.695  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.695  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.696  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.696  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.696  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e1c3177 removed from the list
08-16 12:26:41.696  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.696  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d81e4 removed from the list
08-16 12:26:41.696  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:41.696  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.697  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.697  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.699  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.699  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.699  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.699  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d81e4 not in the list
08-16 12:26:41.699  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.699  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.700  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.700  6803  6882 D BluetoothLeScanner: could not find callback wrapper
08-16 12:26:41.700  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:26:41.700  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.700  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.700  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d986e13 removed from the list
08-16 12:26:41.700  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.700  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.700  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12,:26:41.700  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.700  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c618502 removed from the list
08-16 12:26:41.701  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.701  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e6ef4e added. We now have 2 listener(s)
08-16 12:26:41.702  1042  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.703  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:26:41.704  8202  8253 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 12:26:41.704  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.704  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 12:26:41.704  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.704  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.704  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a91d86f added. We now have 9 listener(s)
08-16 12:26:41.704  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.705  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:26:41.712  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:26:41.716  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.716  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:26:41.716  6803  6882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:26:41.716  8264  8264 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 12:26:41.717  6803  6882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:26:41.718  6803  6882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:26:41.718  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:26:41.718  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1ea205 added. We now have 3 listener(s)
08-16 12:26:41.719  1042  1692 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:26:41.720  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.721  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 12:26:41.721  6803  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:26:41.722  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:26:41.722  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:26:41.722  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:26:41.722  8202  8253 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 12:26:41.722  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:26:41.722  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946b25a added. We now have 10 listener(s)
08-16 12:26:41.722  6803  6882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:26:41.723  8202  8253 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 12:26:41.723  6923  6923 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 12:26:41.723  6803  6882 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:26:41.723  8202  8253 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 12:26:41.724  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:41.724  6803  6882 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:26:41.724  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.724  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.724  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:26:41.724  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.724  6803  6882 V org.thaliproject.p,2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e6ef4e removed from the list
08-16 12:26:41.724  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.724  8202  8253 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 12:26:41.724  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a91d86f removed from the list
08-16 12:26:41.724  6803  6882 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:26:41.724  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.725  8202  8253 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 12:26:41.725  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.725  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.727  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.727  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.727  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.727  6803  6882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a91d86f not in the list
08-16 12:26:41.727  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.727  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:26:41.728  8202  8253 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 12:26:41.728  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:26:41.728  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:26:41.728  6803  6882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:26:41.728  6803  6882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946b25a removed from the list
08-16 12:26:41.728  6803  6882 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:26:41.728  6803  6882 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:26:41.728  6803  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:26:41.728  6803  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:26:41.728  6803  6882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1ea205 removed from the list
08-16 12:26:41.729  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 12:26:41.729  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 12:26:41.729  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 12:26:41.729  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:26:41.730  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 12:26:41.730  6803  6882 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 12:26:41.737  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.738  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.738  8202  8253 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 12:26:41.740  6803  8299 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: My test thread name)
08-16 12:26:41.740  6803  8299 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 920, thread name: My test thread name)
08-16 12:26:41.740  6803  8299 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 920, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 12:26:41.742  6803  8300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 922, name: My test thread name)
,08-16 12:26:41.742  6803  8300 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 922, thread name: My test thread name)
08-16 12:26:41.742  6803  8300 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 922, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 12:26:41.744  6803  6882 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 12:26:41.744  6803  6882 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 12:26:41.745  6803  6882 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 12:26:41.745  6803  6882 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 12:26:41.745  6803  6882 D com.test.thalitest.ThaliTestRunner: Total duration: 24075 ms
08-16 12:26:41.746  6803  6882 I jxcore-log: Total number of executed tests:  80
08-16 12:26:41.746  6803  6882 I jxcore-log: 
08-16 12:26:41.746  6803  6882 I jxcore-log: Number of passed tests:  80
08-16 12:26:41.746  6803  6882 I jxcore-log: 
08-16 12:26:41.746  6803  6882 I jxcore-log: Number of failed tests:  0
08-16 12:26:41.746  6803  6882 I jxcore-log: 
08-16 12:26:41.746  6803  6882 I jxcore-log: Number of ignored tests:  0
08-16 12:26:41.746  6803  6882 I jxcore-log: 
08-16 12:26:41.747  6803  6882 I jxcore-log: Total duration:  24075
08-16 12:26:41.747  6803  6882 I jxcore-log: 
08-16 12:26:41.747  6803  6882 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 12:26:41.747  6803  6882 I jxcore-log: 
08-16 12:26:41.750  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.750  6803  6882 I jxcore-log: 
08-16 12:26:41.752  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:41.754  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.754  6803  6882 I jxcore-log: 
,08-16 12:26:41.756  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.756  6803  6882 I jxcore-log: 
08-16 12:26:41.757  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.757  6803  6882 I jxcore-log: 
08-16 12:26:41.758  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.758  6803  6882 I jxcore-log: 
08-16 12:26:41.760  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:26:41.760  6803  6882 I jxcore-log: 
08-16 12:26:41.760  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:41.763  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.763  6803  6882 I jxcore-log: 
08-16 12:26:41.765  6803  6803 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 12:26:41.766  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:26:41.766  6803  6882 I jxcore-log: 
,08-16 12:26:41.767  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.767  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.771  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.771  6803  6882 I jxcore-log: 
08-16 12:26:41.772  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:26:41.772  6803  6882 I jxcore-log: 
08-16 12:26:41.774  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:26:41.774  6803  6882 I jxcore-log: 
08-16 12:26:41.775  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:26:41.775  6803  6882 I jxcore-log: 
08-16 12:26:41.776  8264  8264 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:41.776  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.776  6803  6882 I jxcore-log: 
08-16 12:26:41.777  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.777  6803  6882 I jxcore-log: 
08-16 12:26:41.778  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.778  6803  6882 I jxcore-log: 
08-16 12:26:41.779  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.779  6803  6882 I jxcore-log: 
08-16 12:26:41.779  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.779  6803  6882 I jxcore-log: 
08-16 12:26:41.780  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.780  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.780  6803  6882 I jxcore-log: 
08-16 12:26:41.781  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.781  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.781  6803  6882 I jxcore-log: 
08-16 12:26:41.782  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:26:41.782  6803  6882 I jxcore-log: 
08-16 12:26:41.783  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:26:41.783  6803  6882 I jxcore-log: 
08-16 12:26:41.784  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:26:41.784  6803  6882 I jxcore-log: 
08-16 12:26:41.784  6803  6882 I jxcore-log: DEBU,G thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.784  6803  6882 I jxcore-log: 
08-16 12:26:41.785  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.785  6803  6882 I jxcore-log: 
08-16 12:26:41.786  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.786  6803  6882 I jxcore-log: 
08-16 12:26:41.786  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:41.787  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.787  6803  6882 I jxcore-log: 
08-16 12:26:41.788  6803  6882 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:26:41.788  6803  6882 I jxcore-log: 
,08-16 12:26:41.792  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:41.798  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.799  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.800  8264  8264 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:26:41.803  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:41.804  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.808  8126  8126 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 12:26:41.811  8126  8126 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:26:41.815  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:26:41.826  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:41.833  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.833  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.834  8264  8264 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 12:26:41.858  8264  8264 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 12:26:41.859  8264  8264 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 12:26:41.863  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.864  8202  8254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:26:41.867  8126  8126 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 12:26:41.867  8126  8126 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:26:41.870  6923  6923 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:26:41.878  6923  6923 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:26:41.885  8264  8264 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:26:41.885  8264  8264 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:26:41.886  8264  8264 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 12:26:41.887  8264  8264 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 12:26:41.887  8264  8264 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 12:26:41.891  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:41.923  8264  8264 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 12:26:41.924  8264  8264 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 12:26:41.925  8264  8264 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 12:26:41.963  8264  8264 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:26:41.963  8264  8264 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:41.970  8264  8264 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 12:26:41.973  8264  8264 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 12:26:41.973  8264  8264 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 12:26:41.973  8264  8264 V SoundPool: doLoad: loading sample sampleID=1
08-16 12:26:41.973  8264  8310 V SoundPool: Start decode
08-16 12:26:41.973  8264  8310 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 12:26:41.974   318  1368 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 12:26:41.974   318  1368 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 12:26:41.974   318  1368 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 12:26:41.974   318  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 12:26:41.974   318  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 12:26:41.974   318  1368 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 12:26:41.974   318  1368 V MediaPlayerService: player type = 3
08-16 12:26:41.974   318  1368 V AwesomePlayer: AwesomePlayer create()
08-16 12:26:41.975   318  1368 V AwesomePlayer: reset_l() 
08-16 12:26:41.975   318  1368 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:41.975   318  1368 V AwesomePlayer: setAudioSink() 
08-16 12:26:41.975   318  1368 V AwesomePlayer: reset_l() 
08-16 12:26:41.975   318  1368 V AudioCache: notify(0xb16a6ac0, 8, 0, 0)
08-16 12:26:41.975   318  1368 V AudioCache: ignored
08-16 12:26:41.975   318  1368 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:41.975   318  1368 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 12:26:41.975   318  1368 V AwesomePlayer: setDataSource_l dataSource
08-16 12:26:41.975   318  1368 V LGParserOSAL: SniffLGParser start
08-16 12:26:41.975   318  1368 V LGParserOSAL: MainType:5, SubType=0
08-16 12:26:41.975   318  1368 V LGParserOSAL: #### check Mime : application/ogg
08-16 12:26:41.975   318  1368 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 12:26:41.975   318  1368 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 12:26:41.975  8264  8264 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-16 12:26:41.984  7661  7661 D UEI.SmartControl: QS Service created
08-16 12:26:41.988  8264  8264 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 12:26:41.994  8264  8264 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:26:41.994  8264  8264 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 12:26:41.999  7661  7661 I UEI.SmartControl: Service initServices...
08-16 12:26:41.999  7661  7661 D UEI.SmartControl: QS start get config
08-16 12:26:42.013   318  1368 V LGParserOSAL: supported mime: application/ogg
08-16 12:26:42.013   318  1368 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 12:26:42.013   318  1368 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 12:26:42.013   318  1368 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 12:26:42.013   318  1368 V AwesomePlayer: AudioTrack Setting
08-16 12:26:42.013   318  1368 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 12:26:42.013   318  1368 V AwesomePlayer: setAudioSource() 
08-16 12:26:42.013   318  1368 V MediaPlayerService: prepare
08-16 12:26:42.013   318  1368 V AwesomePlayer: prepareAsync_l() 
08-16 12:26:42.013   318  1368 V MediaPlayerService: wait for prepare
08-16 12:26:42.014   318  8311 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 12:26:42.014   318  8311 V AwesomePlayer: initAudioDecoder() 
08-16 12:26:42.014   318  8311 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:26:42.014   318  8311 V AudioSystem: isOffloadSupported()
08-16 12:26:42.014   318  8311 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:26:42.014   318  8311 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:26:42.014   318  8311 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:26:42.014   318  8311 V AwesomePlayer: getUseOffload() = 0 
08-16 12:26:42.015   318  8311 V OMXCodec: OMXCodec::Create
08-16 12:26:42.015   318  8311 V OMXCodec: findMatchingCodecs()
08-16 12:26:42.015   318  8311 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 12:26:42.015   318  8311 V OMXCodec: matchingCodecs.size()=1
08-16 12:26:42.015   318  8311 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-16 12:26:42.017   318  8311 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 12:26:42.017   318  8311 V LGCodecAdapter: LG Codec Adapter start
08-16 12:26:42.017   318  8311 V OMXCodec: OMXCodec Createtor
08-16 12:26:42.017   318  8311 V OMXCodec: setComponentRole
08-16 12:26:42.017   318  8311 V OMXCodec: configureCodec protected=0
08-16 12:26:42.017   318  8311 V LGCodecAdapter: called getLGCodecSpecificData
08-16 12:26:42.017   318  8311 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 12:26:42.017   318  8311 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 12:26:42.017   318  8311 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 12:26:42.017   318  8311 V LGCodecOSAL: Not support LGCodec
08-16 12:26:42.017   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:26:42.018   318  8311 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 12:26:42.018   318  8311 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 12:26:42.018   318  8311 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 12:26:42.018   318  8311 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:26:42.018   318  8311 V AudioSystem: isOffloadSupported()
08-16 12:26:42.018   318  8311 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:26:42.018   318  8311 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 12:26:42.018   318  8311 V OMXCodec: init()
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 12:26:42.018   318  8311 V OMXCodec: allocateBuffers
08-16 12:26:42.018   318  8311 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 12:26:42.018   318  8311 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:26:42.018   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 12:26:42.019   318  8311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb240 on output port
08-16 12:26:42.019   318  8311 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 12:26:42.019   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:26:42.019   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:26:42.019   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 12:26:42.019   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 12:26:42.019   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 12:26:42.019   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-16 12:26:42.020   318  8311 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 12:26:42.020   318  8311 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 12:26:42.020   318  8311 V AudioCache: notify(0xb16a6ac0, 5, 0, 0)
08-16 12:26:42.020   318  8311 V AudioCache: ignored
08-16 12:26:42.020   318  8311 V AudioCache: notify(0xb16a6ac0, 1, 0, 0)
08-16 12:26:42.020   318  8311 V AudioCache: prepared
08-16 12:26:42.020   318  1368 V AudioCache: wait - success
08-16 12:26:42.020   318  1368 V MediaPlayerService: start
08-16 12:26:42.020   318  1368 V AwesomePlayer: play_l() 
08-16 12:26:42.020   318  1368 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 12:26:42.020   318  1368 V AwesomePlayer: createAudioPlayer_l
08-16 12:26:42.020   318  1368 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 12:26:42.020   318  1368 V AwesomePlayer: startAudioPlayer_l() 
08-16 12:26:42.020   318  1368 D AudioPlayer: start of Playback, useOffload 0
08-16 12:26:42.020   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:26:42.021   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:42.023   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782656
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 12:26:42.024   318  8313 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 12:26:42.024   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-16 12:26:42.025   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 12:26:42.025   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 12:26:42.026  8264  8264 V LGMDMManager: Create singleton instance
08-16 12:26:42.026   318  1368 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 12:26:42.027   318  1368 V AudioCache: notify(0xb16a6ac0, 6, 0, 0)
08-16 12:26:42.027   318  1368 V AudioCache: ignored
08-16 12:26:42.027   318  1368 V MediaPlayerService: wait for playback complete
08-16 12:26:42.028   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.028   318  8314 V AudioCache: memcpy(0xaf006000, 0xb16ea000, 4096)
08-16 12:26:42.031   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.031   318  8314 V AudioCache: memcpy(0xaf007000, 0xb16ea000, 4096)
08-16 12:26:42.031   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.031   318  8314 V AudioCache: memcpy(0xaf008000, 0xb16ea000, 4096)
08-16 12:26:42.032   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.032   318  8314 V AudioCache: memcpy(0xaf009000, 0xb16ea000, 4096)
08-16 12:26:42.033   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.033   318  8314 V AudioCache: memcpy(0xaf00a000, 0xb16ea000, 4096)
08-16 12:26:42.034   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.034   318  8314 V AudioCache: memcpy(0xaf00b000, 0xb16ea000, 4096)
08-16 12:26:42.034   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.035   318  8314 V AudioCache: memcpy(0xaf00c000, 0xb16ea000, 4096)
08-16 12:26:42.035   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.035   318  8314 V AudioCache: memcpy(0xaf00d000, 0xb16ea000, 4096)
08-16 12:26:42.036   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.036   318  8314 V AudioCache: memcpy(0xaf00e000, 0xb16ea000, 4096)
08-16 12:26:42.037   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.037   318  8314 V AudioCache: memcpy(0xaf00f000, 0xb16ea000, 4096)
08-16 12:26:42.038   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.038   318  8314 V AudioCache: memcpy(0xaf010000, 0xb16ea000, 4096)
08-16 12:26:42.039   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.039   318  8314 V AudioCache: memcpy(0xaf011000, 0xb16ea000, 4096)
08-16 12:26:42.040   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.040   318  8314 V AudioCache: memcpy(0xaf012000, 0xb16ea000, 4096)
08-16 12:26:42.042   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.042   318  8314 V AudioCache: memcpy(0xaf013000, 0xb16ea000, 4096)
08-16 12:26:42.043   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.043   318  8314 V AudioCache: memcpy(0xaf014000, 0xb16ea000, 4096)
08-16 12:26:42.044   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.044   318  8314 V AudioCache: memcpy(0xaf015000, 0xb16ea000, 4096)
08-16 12:26:42.045   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.045   318  8314 V AudioCache: memcpy(0xaf016000, 0xb16ea000, 4096)
08-16 12:26:42.045   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.045   318  8314 V AudioCache: memcpy(0xaf017000, 0xb16ea000, 4096)
08-16 12:26:42.046   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.046   318  8314 V AudioCache: memcpy(0xaf018000, 0xb16ea000, 4096)
08-16 12:26:42.047   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.047   318  8314 V AudioCache: memcpy(0xaf019000, 0xb16ea000, 4096)
08-16 12:26:42.048   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.048   318  8314 V AudioCache: memcpy(0xaf01a000, 0xb16ea000, 4096)
08-16 12:26:42.049   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.049   318  8314 V AudioCache: memcpy(0xaf01b000, 0xb16ea000, 4096)
08-16 12:26:42.049   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.049   318  8314 V AudioCache: memcpy(0xaf01c000, 0xb16ea000, 4096)
08-16 12:26:42.050   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.050   318  8314 V AudioCache: memcpy(0xaf01d000, 0xb16ea000, 4096)
08-16 12:26:42.051   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.051   318  8314 V AudioCache: memcpy(0xaf01e000, 0xb16ea000, 4096)
08-16 12:26:42.052   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.052   318  8314 V AudioCache: memcpy(0xaf01f000, 0xb16ea000, 4096)
08-16 12:26:42.053   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.053   318  8314 V AudioCache: memcpy(0xaf020000, 0xb16ea000, 4096)
08-16 12:26:42.055   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.055   318  8314 V AudioCache: memcpy(0xaf021000, 0xb16ea000, 4096)
08-16 12:26:42.056   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.056   318  8314 V AudioCache: memcpy(0xaf022000, 0xb16ea000, 4096)
08-16 12:26:42.057   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.057   318  8314 V AudioCache: memcpy(0xaf023000, 0xb16ea000, 4096)
08-16 12:26:42.058   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.058   318  8314 V AudioCache: memcpy(0xaf024000, 0xb16ea000, 4096)
08-16 12:26:42.059   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.059   318  8314 V AudioCache: memcpy(0xaf025000, 0xb16ea000, 4096)
08-16 12:26:42.059   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.059   318  8314 V AudioCache: memcpy(0xaf026000, 0xb16ea000, 4096)
08-16 12:26:42.060   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.060   318  8314 V AudioCache: memcpy(0xaf027000, 0xb16ea000, 4096)
08-16 12:26:42.061   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.061   318  8314 V AudioCache: memcpy(0xaf028000, 0xb16ea000, 4096)
,08-16 12:26:42.062   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.062   318  8314 V AudioCache: memcpy(0xaf029000, 0xb16ea000, 4096)
08-16 12:26:42.063   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.063   318  8314 V AudioCache: memcpy(0xaf02a000, 0xb16ea000, 4096)
08-16 12:26:42.064   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.064   318  8314 V AudioCache: memcpy(0xaf02b000, 0xb16ea000, 4096)
08-16 12:26:42.064   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.064   318  8314 V AudioCache: memcpy(0xaf02c000, 0xb16ea000, 4096)
08-16 12:26:42.065   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.065   318  8314 V AudioCache: memcpy(0xaf02d000, 0xb16ea000, 4096)
08-16 12:26:42.068   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.068   318  8314 V AudioCache: memcpy(0xaf02e000, 0xb16ea000, 4096)
08-16 12:26:42.068   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.068   318  8314 V AudioCache: memcpy(0xaf02f000, 0xb16ea000, 4096)
08-16 12:26:42.069   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.069   318  8314 V AudioCache: memcpy(0xaf030000, 0xb16ea000, 4096)
08-16 12:26:42.070   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.070   318  8314 V AudioCache: memcpy(0xaf031000, 0xb16ea000, 4096)
08-16 12:26:42.071   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.071   318  8314 V AudioCache: memcpy(0xaf032000, 0xb16ea000, 4096)
08-16 12:26:42.071   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.072   318  8314 V AudioCache: memcpy(0xaf033000, 0xb16ea000, 4096)
08-16 12:26:42.072   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.072   318  8314 V AudioCache: memcpy(0xaf034000, 0xb16ea000, 4096)
08-16 12:26:42.073   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.073   318  8314 V AudioCache: memcpy(0xaf035000, 0xb16ea000, 4096)
08-16 12:26:42.073   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.073   318  8314 V AudioCache: memcpy(0xaf036000, 0xb16ea000, 4096)
08-16 12:26:42.074   318  8314 V AudioCache: write(0xb16ea000, 4096)
08-16 12:26:42.074   318  8314 V AudioCache: memcpy(0xaf037000, 0xb16ea000, 4096)
08-16 12:26:42.074   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 12:26:42.075   318  8314 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 12:26:42.075   318  8314 V AwesomePlayer: postAudioEOS() 
08-16 12:26:42.075   318  8314 V AudioCache: write(0xb16ea000, 280)
08-16 12:26:42.075   318  8314 V AudioCache: memcpy(0xaf038000, 0xb16ea000, 280)
08-16 12:26:42.076   318  8311 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 12:26:42.076   318  8311 V AwesomePlayer: onStreamDone
08-16 12:26:42.076   318  8311 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 12:26:42.076   318  8311 V AudioCache: notify(0xb16a6ac0, 2, 0, 0)
08-16 12:26:42.076   318  8311 V AudioCache: playback complete
08-16 12:26:42.076   318  8311 V AwesomePlayer: pause_l() 
08-16 12:26:42.076   318  8311 V AudioCache: notify(0xb16a6ac0, 7, 0, 0)
08-16 12:26:42.076   318  8311 V AudioCache: ignored
08-16 12:26:42.076   318  8311 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:42.076   318  1368 V AudioCache: wait - success
08-16 12:26:42.076   318  1368 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 12:26:42.076   318  8311 D AudioPlayer: Pause Playback at 1068125
08-16 12:26:42.077   318  1368 V AwesomePlayer: reset_l() 
08-16 12:26:42.077   318  1368 V AudioCache: notify(0xb16a6ac0, 8, 0, 0)
08-16 12:26:42.077   318  1368 V AudioCache: ignored
08-16 12:26:42.077   318  1368 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:42.077   318  1368 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 12:26:42.077   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 12:26:42.077   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 12:26:42.077   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 12:26:42.077   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 12:26:42.077   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:26:42.078   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:26:42.078   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 12:26:42.078   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 12:26:42.078   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 12:26:42.079   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 12:26:42.079   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 12:26:42.079   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-16 12:26:42.079   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 12:26:42.079   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
08-16 12:26:42.079   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 12:26:42.080   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 12:26:42.080   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 12:26:42.080   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 12:26:42.080   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 12:26:42.080   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 12:26:42.080   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 12:26:42.081   318  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 12:26:42.081   318  1368 D AudioPlayer: AudioPlayer releasing audio source
08-16 12:26:42.081   318  1368 D AudioPlayer: AudioPlayer done releasing audio source
08-16 12:26:42.081   318  1368 V AwesomePlayer: reset_l() 
08-16 12:26:42.081   318  1368 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:42.081   318  1368 V AwesomePlayer: ~AwesomePlayer call
08-16 12:26:42.081   318  1368 V AwesomePlayer: reset_l() 
08-16 12:26:42.081   318  1368 V AwesomePlayer: cancelPlayerEvents
08-16 12:26:42.082  8264  8310 V SoundPool: close(31)
08-16 12:26:42.082  8264  8310 V SoundPool: pointer = 0xa0012000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 12:26:42.091  8264  8264 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 12:26:42.093  8264  8264 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 12:26:42.094  8264  8264 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4124
08-16 12:26:42.096  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:42.098  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:42.099  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:42.101  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:26:42.103  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:42.105  8302  8302 D AndroidRuntime: 
08-16 12:26:42.105  8302  8302 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 12:26:42.105  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:42.108  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:42.108  8302  8302 D AndroidRuntime: CheckJNI is OFF
08-16 12:26:42.110  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:26:42.290  7661  7661 I UEI.SmartControl: Supports setup maps: true
08-16 12:26:42.293  7661  7661 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 12:26:42.293  7661  7661 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 12:26:42.293  7661  7661 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 12:26:42.293  7661  7661 I UEI.SmartControl: ### init IR Blaster...
08-16 12:26:42.297  7661  7661 D serial_port: Configuring serial port
,08-16 12:26:42.297  7661  7661 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:26:42.297  7661  7661 I UEI.SmartControl: Setting serial record hearder size = 2
,08-16 12:26:42.297  7661  7661 I UEI.SmartControl: configuring settings for MAXQ616
08-16 12:26:42.297  7661  7661 I UEI.SmartControl: Get version...
,08-16 12:26:42.316  7661  8325 D UEI.SmartControl: serial port data available: 21
08-16 12:26:42.318  8302  8302 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 12:26:42.333  1042  1108 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-16 12:26:42.334  1042  1108 I ActivityManager: Killing 6803:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-16 12:26:42.343  7661  7661 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 12:26:42.343  7661  7661 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 12:26:42.343  7661  7661 I UEI.SmartControl: QS saving settings...
08-16 12:26:42.344  7661  7661 D UEI.SmartControl: IR Blaster version: 25672567
08-16 12:26:42.358  7661  8325 D UEI.SmartControl: serial port data available: 4
,08-16 12:26:42.389  7661  8330 I UEI.SmartControl: Device manager: loading config....
08-16 12:26:42.389  7661  8330 D UEI.SmartControl: ----------- loading internal config...
,08-16 12:26:42.391  7661  7661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 12:26:42.396  7661  8330 E UEI.SmartControl: Loading SETTINGS...
08-16 12:26:42.405  1042  1693 I WindowState: WIN DEATH: Window{4c8c88a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 12:26:42.406  1042  1526 D WifiService: Client connection lost with reason: 4
08-16 12:26:42.412  7661  8330 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 12:26:42.414  1042  1693 D InputDispatcher: Window went away: Window{4c8c88a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 12:26:42.432  7661  8329 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 12:26:42.432  7661  8329 D UEI.SmartControl: -----service ready thread exits
08-16 12:26:42.551  1042  1108 I ActivityManager:   Force finishing activity ActivityRecord{1a2969f7 u0 com.test.thalitest/.MainActivity t6}
,08-16 12:26:42.607   334   345 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 12:26:42.618  1042  1971 W ActivityManager: Spurious death for ProcessRecord{a9037e4 6803:com.test.thalitest/u0a118}, curProc for 6803: null
08-16 12:26:42.623  7661  7661 E UEI.SmartControl: Services init done
08-16 12:26:42.624  7661  7661 D UEI.SmartControl: QS Service init finished
,08-16 12:26:42.627  1042  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 12:26:42.629  1042  1125 I ActivityManager:   Force finishing activity ActivityRecord{1a2969f7 u0 com.test.thalitest/.MainActivity t6 f}
08-16 12:26:42.630  1042  1125 W ActivityManager: Duplicate finish request for ActivityRecord{1a2969f7 u0 com.test.thalitest/.MainActivity t6 f}
08-16 12:26:42.633  1925  3996 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 12:26:42.634  1925  3996 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1051a10 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 12:26:42.636  7661  7661 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:26:42.636  7661  7661 D UEI.SmartControl: QS Service version code: 201091
08-16 12:26:42.637  7661  7661 D UEI.SmartControl: Service requested: Control
08-16 12:26:42.641  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 12:26:42.642  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{357d2909 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-16 12:26:42.652  2016  2016 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-16 12:26:42.653  8264  8264 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 12:26:42.654  2016  2016 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 12:26:42.656  7661  7676 I UEI.SmartControl: ------ IControl API: 11
08-16 12:26:42.656  7661  7661 D UEI.SmartControl: Internal service binding...
08-16 12:26:42.656  7661  7676 D UEI.SmartControl: File observer start...
08-16 12:26:42.657  7661  7676 E UEI.SmartControl: IR Port is disabled: false
08-16 12:26:42.657  7661  7676 D UEI.SmartControl: Starting file observer...
08-16 12:26:42.657  7661  7676 I UEI.SmartControl: Registering callback...
08-16 12:26:42.658  7661  7677 I UEI.SmartControl: ------ IControl API: 19
08-16 12:26:42.658  7661  7677 I UEI.SmartControl: Registering Services Ready callback...
08-16 12:26:42.658  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 12:26:42.659  7661  7677 I UEI.SmartControl: Notify client services are ready...
08-16 12:26:42.659  8264  8279 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 12:26:42.661  8264  8308 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 12:26:42.661  8264  8308 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 12:26:42.662  8264  8264 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 12:26:42.662  8264  8264 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 12:26:42.662  7661  7676 I UEI.SmartControl: ------ IControl API: 8
08-16 12:26:42.665  8264  8264 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 12:26:42.665  8264  8264 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 12:26:42.665  8264  8264 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 12:26:42.666  8264  8264 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-16 12:26:42.676  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 12:26:42.677  3766  3766 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-16 12:26:42.677  2459  2605 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 12:26:42.679  8264  8264 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 12:26:42.680  7733  7733 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 12:26:42.680  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 12:26:42.682  4806  4806 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 12:26:42.683  4806  4806 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 12:26:42.683  4806  4806 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 12:26:42.683  4806  4806 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 12:26:42.683  4806  4806 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:26:42.683  4806  4806 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:26:42.683  4806  4806 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:26:42.683  4806  4806 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:26:42.683  8264  8264 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 12:26:42.683  4806  4806 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:26:42.683  4806  4806 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:26:42.683  4806  4806 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:26:42.683  4806  4806 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:26:42.703  1042  1410 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 12:26:42.718  4912  4912 I art     : Explicit concurrent mark sweep GC freed 8195(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 546us total 76.244ms
08-16 12:26:42.738  1042  1996 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:26:42.742  1042  1106 W InputMethodInfo: Duplicated subtype definition found: , voice
08-16 12:26:42.756  8202  8202 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 12:26:42.756  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 12:26:42.757  2016  2059 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 12:26:42.757  1042  1042 D administrator: Handling package changes for user 0
,08-16 12:26:42.773  1889  1889 D ActionManagerService: notifyUserLog: 1000003
08-16 12:26:42.773  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-16 12:26:42.773  3766  4832 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 12:26:42.778  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 12:26:42.778  8264  8264 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 12:26:42.781  2016  2016 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 12:26:42.783  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 12:26:42.786  2016  2016 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 12:26:42.787  1586  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 12:26:42.787  1586  1651 D KeyguardModel: createShortcutInfo...
,08-16 12:26:42.789  1586  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 12:26:42.789  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:42.792  2016  2016 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 12:26:42.800  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 12:26:42.800  1586  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:26:42.801  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-16 12:26:42.802  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 12:26:42.802  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 12:26:42.804  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:26:42.804  1586  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 12:26:42.804  1889  1889 D ActionManagerService: notifyUserLog: 1000004
08-16 12:26:42.805  3766  4832 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 12:26:42.805  2066  2066 I ConfigService: onCreate
08-16 12:26:42.806  2066  2066 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 12:26:42.807  1586  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 12:26:42.807  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:42.807  3766  4826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 12:26:42.816  8264  8264 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 12:26:42.816  2066  2066 I ConfigService: onBind returning update interface
,08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , display: false
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , animation: false }
,08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , display: false
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , animation: false }
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , display: false
08-16 12:26:42.819  2016  2016 I GBoardWebViewUtils: , animation: false }
08-16 12:26:42.824  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 12:26:42.824  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 12:26:42.824  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:42.827  2066  2066 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 12:26:42.827  2066  2066 I ConfigService: onBind returning config service
08-16 12:26:42.828  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 12:26:42.828  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 12:26:42.829  1042  1558 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:26:42.829  1042  1558 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:26:42.830  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:26:42.830  1586  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-16 12:26:42.833  2016  8341 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 12:26:42.834  1802  1802 I ConfigFetchService: service connected
08-16 12:26:42.846  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 12:26:42.846  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-16 12:26:42.872  1586  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 12:26:42.872  1586  1651 D KeyguardModel: createShortcutInfo...
,08-16 12:26:42.876  2066  2066 I ConfigService: onDestroy
08-16 12:26:42.877  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-16 12:26:42.878  1854  1854 D SplitUIService: removed split : 
08-16 12:26:42.884  1586  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:26:42.884  1586  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 12:26:42.884  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 12:26:42.884  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 12:26:42.889  1042  2034 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 12:26:42.889  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:26:42.890  1586  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:26:42.890  7733  7733 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 12:26:42.892  1586  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 12:26:42.892  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:42.896  1042  1637 I ActivityManager: Killing 7328:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-16 12:26:42.897  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-16 12:26:42.897  1854  1854 I SplitUIService: split app #11
08-16 12:26:42.898  1802  8343 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 12:26:42.932  1042  1942 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:26:42.949  1042  1042 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 12:26:42.950  1042  1042 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 12:26:42.950  1042  1042 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 12:26:42.983  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-16 12:26:42.983  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 12:26:42.994  1042  1996 W libprocessgroup: failed to open /acct/uid_10005/pid_7328/cgroup.procs: No such file or directory
08-16 12:26:42.998  2016  2016 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-16 12:26:43.004  1042  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 12:26:43.004  1586  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 12:26:43.004  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:43.006  1586  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 12:26:43.006  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:43.008  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:26:43.008  1586  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 12:26:43.009  1586  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 12:26:43.009  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:43.010  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:26:43.011  1586  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-16 12:26:43.018  1586  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 12:26:43.018  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:43.020  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 12:26:43.020  1586  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 12:26:43.022  1586  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 12:26:43.022  1586  1651 D KeyguardModel: createShortcutInfo...
08-16 12:26:43.028  5789  8351 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-16 12:26:43.035  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-16 12:26:43.035  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 12:26:43.036  1802  8352 I PeopleContactsSync: CP2 sync disabled
08-16 12:26:43.043  1802  5095 I Icing   : doRemovePackageData com.test.thalitest
,08-16 12:26:43.046  1042  1125 I art     : Explicit concurrent mark sweep GC freed 21517(1560KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.527ms total 208.050ms
08-16 12:26:43.071  2066  6159 I art     : Explicit concurrent mark sweep GC freed 8464(494KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 678us total 26.552ms
,08-16 12:26:43.074  7118  7118 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-16 12:26:43.088  1802  8350 W GmsApplication: Using Auth Proxy for data requests.
,08-16 12:26:43.091  2344  8355 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 12:26:43.120  1042  1971 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8356 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 12:26:43.126  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 12:26:43.128  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.129  1802  8350 W GmsApplication: Using Auth Proxy for data requests.
08-16 12:26:43.129  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 12:26:43.131  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 12:26:43.132  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 12:26:43.133  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-16 12:26:43.148  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 12:26:43.148  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.149  1042  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3bb65ec5 u0 com.lge.launcher2/.Launcher t5} time:217159
08-16 12:26:43.149  2016  2101 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 12:26:43.149  2016  2101 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-16 12:26:43.164  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-16 12:26:43.164  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 12:26:43.164  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.172  8302  8302 D AndroidRuntime: Shutting down VM
08-16 12:26:43.173  2016  2016 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 12:26:43.174  2581  2581 D [Concierge]Service: onStartCommand(). Type : 8
08-16 12:26:43.175  2581  2581 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 12:26:43.175  2581  2581 D [Concierge]Service: Update widget ID : 11
,08-16 12:26:43.177  2016  2016 D [Concierge]WidgetView: change position of spinner
08-16 12:26:43.178  2016  2016 I [Concierge]WidgetView: initWebView(). Time : 1471343203178
08-16 12:26:43.178  2581  2581 D [Concierge]Service: onStartCommand(). Type : 0
08-16 12:26:43.187  8356  8356 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:26:43.187  8356  8356 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:26:43.188  8356  8356 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 12:26:43.188  8356  8356 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 12:26:43.215  1042  1106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:26:43.219  1042  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8376 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-16 12:26:43.220  1042  1106 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 12:26:43.229  2016  2016 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 695229377
08-16 12:26:43.230  2016  2016 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-16 12:26:43.230  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 12:26:43.233  2016  2016 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@e5f920e
08-16 12:26:43.233  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-16 12:26:43.234  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 12:26:43.234  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.239  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 12:26:43.240  2016  2016 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 12:26:43.240  2016  2016 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 12:26:43.243  2016  2016 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471343013081, New one : 1471343203178
08-16 12:26:43.243  2016  2016 D [Concierge]WidgetView: Unregister all receivers
08-16 12:26:43.243  2016  2016 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 12:26:43.243  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 12:26:43.244  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.246  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-16 12:26:43.247  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 12:26:43.248  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 12:26:43.249  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 12:26:43.250  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 12:26:43.252  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.252  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.269  1042  2014 I ActivityManager: Killing 7761:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 12:26:43.295  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 12:26:43.307  2016  2016 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 12:26:43.307  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 12:26:43.308  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:26:43.328  2016  2016 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@140ef02d time:217338
,08-16 12:26:43.365  1042  1996 W libprocessgroup: failed to open /acct/uid_10072/pid_7761/cgroup.procs: No such file or directory
,08-16 12:26:43.377  8356  8356 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-16 12:26:43.408  8356  8356 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 12:26:43.461  8356  8356 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 12:26:43.465  1042  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=67.5, 0.0, 0.0  rx=61.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1830579063] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:26:43.466  1042  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=67.5, 0.0, 0.0  rx=61.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1830579062] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:26:43.466  1042  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:26:43.478  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:26:43.489  8356  8356 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:26:43.489  8356  8356 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:26:43.500  2016  2016 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-16 12:26:43.536  1042  1522 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 12:26:43.537  2016  2865 I GBoardtInterface: onReloaded()
,08-16 12:26:43.539  2016  2016 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 12:26:43.541  3766  4826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 12:26:43.545  3766  3782 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 12:26:43.552  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-16 12:26:43.553  3766  4832 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 12:26:43.553  3766  4832 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-16 12:26:43.556  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-16 12:26:43.557  3766  4832 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 12:26:43.557  3766  4832 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 12:26:43.557  3766  4832 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 12:26:43.557  3766  4832 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 12:26:43.557  3766  4826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 12:26:43.559  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 12:26:43.559  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 12:26:43.559  8356  8356 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-16 12:26:43.561  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 12:26:43.561  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 12:26:43.563  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 12:26:43.563  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 12:26:43.566  7835  7835 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
,08-16 12:26:43.567  1042  1692 I ActivityManager: Killing 7854:com.android.vending/u0a44 (adj 15): empty #17
,08-16 12:26:43.591   281   691 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
