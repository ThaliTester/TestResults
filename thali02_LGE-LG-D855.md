#### Test 7975101549b9187_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-12 13:47:29.605  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=808741850 [*alarm*], flags=0x0
,--------- beginning of main
08-12 13:47:45.116  6965  6965 D AndroidRuntime: 
08-12 13:47:45.116  6965  6965 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 13:47:45.123  6965  6965 D AndroidRuntime: CheckJNI is OFF
08-12 13:47:45.325  6965  6965 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 13:47:45.336  1034  1920 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 13:47:45.353  1943  4002 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 13:47:45.359  1034  1920 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 13:47:45.360  1034  1920 D ActivityManager: setTaskToReturnTo : TaskRecord{1839614a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 13:47:45.360  1034  1920 D ActivityManager: setTaskToReturnTo : TaskRecord{1839614a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 13:47:45.362  1034  1920 D WindowStateEx: AppWindowTokenEx init.. 
08-12 13:47:45.363   338   365 E GBMv2   : DFP En is all cleared set to be enabled
08-12 13:47:45.391  1034  1920 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6980 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 13:47:45.394  6965  6965 D AndroidRuntime: Shutting down VM
08-12 13:47:45.448  1943  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 13:47:45.448  1943  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{b8c321f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 13:47:45.449  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 13:47:45.449  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4f0f96c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 13:47:45.535  6980  6980 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 13:47:45.637  6980  6980 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 13:47:45.648  6980  6980 I LibraryLoader: Loading: webviewchromium
,08-12 13:47:45.651  6980  6980 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3048-3053)
08-12 13:47:45.652  6980  6980 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 13:47:45.674  6980  6980 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28af798f}
,08-12 13:47:45.676  6980  6980 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 13:47:45.677  6980  6980 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 13:47:45.691  6980  6980 I BrowserStartupController: Initializing chromium process, renderers=0
08-12 13:47:45.692  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 13:47:45.709  6980  6980 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-12 13:47:45.710  6980  6980 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 13:47:45.710  6980  6980 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 13:47:45.720   315   315 V AudioPolicyService: registerClient() client 0xb558a640, uid 10118
08-12 13:47:45.732  6980  6980 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 13:47:45.732  6980  6980 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 13:47:45.732  6980  6980 I Adreno-EGL: Build Date: 12/12/14 금
08-12 13:47:45.732  6980  6980 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 13:47:45.732  6980  6980 I Adreno-EGL: Remote Branch: 
08-12 13:47:45.732  6980  6980 I Adreno-EGL: Local Patches: 
08-12 13:47:45.732  6980  6980 I Adreno-EGL: Reconstruct Branch: 
,08-12 13:47:45.735  1034  1110 D BluetoothManagerService: Message: 20
08-12 13:47:45.735  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b96e384:true
08-12 13:47:45.835  6980  7020 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-12 13:47:45.838  6980  6980 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-12 13:47:45.858  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 13:47:45.863  6980  6980 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 13:47:45.867  6980  6980 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 13:47:45.871  6980  6980 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 13:47:45.871  6980  6980 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 13:47:45.888  6980  6980 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 13:47:45.897  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 13:47:45.897  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 13:47:45.947  6980  7035 D OpenGLRenderer: Render dirty regions requested: true
08-12 13:47:45.947  6980  7035 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 13:47:45.947  1034  1091 W ActivityManager: Activity pause timeout for ActivityRecord{154f28bb u0 com.test.thalitest/.MainActivity t6}
08-12 13:47:45.955  6980  7035 D OpenGLRenderer: Enabling debug mode 0
,08-12 13:47:45.972  6980  6980 D Atlas   : Validating map...
,08-12 13:47:45.977  1034  1049 D SplitWindow: check instance of lgWin Window{131f849e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 13:47:46.023  6980  7030 D LgDataFeature: LgDataFeature() Constructor: none
08-12 13:47:46.023  6980  7030 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 13:47:46.089  1034  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +642ms (total +725ms)
,08-12 13:47:46.090  6980  6980 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1808f9aa time:303492
08-12 13:47:46.092  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{154f28bb u0 com.test.thalitest/.MainActivity t6} time:303493
08-12 13:47:46.204  6980  6980 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 13:47:46.204  6980  6980 I chromium: 
,08-12 13:47:46.229  6980  6980 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 13:47:46.316  6980  7030 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 13:47:46.316  6980  7030 I chromium: 
,08-12 13:47:46.459  6980  7045 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435177984
,08-12 13:47:46.478  6980  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 13:47:46.478  6980  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 13:47:46.478  6980  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 13:47:46.478  6980  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 13:47:46.478  6980  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 13:47:46.479  6980  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f126e4e added. We now have 1 listener(s)
08-12 13:47:46.484  1034  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-12 13:47:46.487  6980  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 13:47:46.493  6980  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 13:47:46.497  6980  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 13:47:46.498  6980  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 13:47:46.503   338   367 E GBMv2   : DFP En is all cleared set to be enabled
08-12 13:47:46.503   338   367 E GBMv2   : Set value is all cleared set the max
08-12 13:47:46.503   338   367 I GBMv2   : DFP Enabled. Ignore VFP set
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 13:47:46.507  6980  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24236d05 added. We now have 1 listener(s)
08-12 13:47:46.507  6980  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 13:47:46.512  1034  1544 D WifiService: New client listening to asynchronous messages
,08-12 13:47:46.517  6980  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 13:47:46.517  6980  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 13:47:46.519  6980  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 13:47:46.519  6980  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 13:47:46.520  6980  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 13:47:46.526  6980  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 13:47:46.527  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 13:47:46.528  6980  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 13:47:46.541  6980  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:47:46.542  6980  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 13:47:46.542  6980  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 13:47:46.543  6980  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 13:47:46.548  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 13:47:46.551  6980  7045 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 13:47:46.551  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 13:47:46.590  6980  6980 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 13:47:47.497  6980  7048 W jxcore-log: Initializing JXcore engine
08-12 13:47:47.497  6980  7048 W jxcore-log: JXcore engine is ready
,08-12 13:47:47.537  7048  7048 W Thread-827: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6122]" dev="sockfs" ino=6122 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 13:47:47.537  7048  7048 W Thread-827: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 13:47:47.537  7048  7048 W Thread-827: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7664]" dev="sockfs" ino=7664 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 13:47:47.537  7048  7048 W Thread-827: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 13:47:47.537  7048  7048 W Thread-827: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33644]" dev="sockfs" ino=33644 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 13:47:47.560  6980  7048 W jxcore-log: Starting JXcore engine
,08-12 13:47:47.648  6980  7048 W jxcore-log: Platform android
08-12 13:47:47.648  6980  7048 W jxcore-log: 
08-12 13:47:47.648  6980  7048 W jxcore-log: Process ARCH arm
08-12 13:47:47.648  6980  7048 W jxcore-log: 
,08-12 13:47:48.069  6980  7048 I jxcore-log: JXcore Cordova bridge is ready!
08-12 13:47:48.069  6980  7048 I jxcore-log: 
,08-12 13:47:48.069  6980  7048 W jxcore-log: JXcore engine is started
,08-12 13:47:48.075  6980  7045 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 13:47:48.081  6980  6980 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 13:48:00.058  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 13:48:00.058  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 13:48:00.058  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 13:48:00.058  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-12 13:48:00.062  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 13:48:00.062  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-12 13:48:00.063  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-12 13:48:00.063  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 13:48:18.169  1034  3588 I LocationManagerService: remove 1a0cc5aa
08-12 13:48:18.169  1034  3588 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 13:48:18.170  1034  3588 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 13:48:18.170  1034  3588 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 13:48:18.171  1034  3588 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 13:48:18.171  1034  3588 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 13:48:18.819  6980  7048 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 13:48:18.819  6980  7048 I jxcore-log: 
08-12 13:48:18.822  6980  7048 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 13:48:18.822  6980  7048 I jxcore-log: 
,08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:48:18.826  6980  7048 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 13:48:18.829  6980  7048 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 13:48:18.832  6980  7048 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 13:48:18.832  6980  7048 I jxcore-log: 
08-12 13:48:18.834  6980  7048 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 13:48:18.834  6980  7048 I jxcore-log: 
08-12 13:48:19.195  6980  7048 I jxcore-log: Unit Test app is loaded
08-12 13:48:19.195  6980  7048 I jxcore-log: 
,08-12 13:48:19.205  6980  6980 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 13:48:19.211  6980  7048 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 13:48:19.211  6980  7048 I jxcore-log: 
,08-12 13:48:19.216  6980  7048 I jxcore-log: My device name is: LGE-LG-D855
08-12 13:48:19.216  6980  7048 I jxcore-log: 
08-12 13:48:23.784  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 13:48:23.784  6980  7048 I jxcore-log: 
,08-12 13:48:25.029  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 13:48:25.029  6980  7048 I jxcore-log: 
,08-12 13:48:25.081  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 13:48:25.081  6980  7048 I jxcore-log: 
,08-12 13:48:27.733  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 13:48:27.733  6980  7048 I jxcore-log: 
,08-12 13:48:28.176  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 13:48:28.176  6980  7048 I jxcore-log: 
,08-12 13:48:28.189  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 13:48:28.189  6980  7048 I jxcore-log: 
08-12 13:48:28.199  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 13:48:28.199  6980  7048 I jxcore-log: 
,08-12 13:48:28.234  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 13:48:28.234  6980  7048 I jxcore-log: 
,08-12 13:48:28.243  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 13:48:28.243  6980  7048 I jxcore-log: 
08-12 13:48:29.566  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 13:48:29.566  6980  7048 I jxcore-log: 
,08-12 13:48:29.593  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 13:48:29.593  6980  7048 I jxcore-log: 
,08-12 13:48:29.611  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 13:48:29.611  6980  7048 I jxcore-log: 
,08-12 13:48:29.625  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 13:48:29.625  6980  7048 I jxcore-log: 
08-12 13:48:29.722  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 13:48:29.722  6980  7048 I jxcore-log: 
,08-12 13:48:29.833  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 13:48:29.833  6980  7048 I jxcore-log: 
,08-12 13:48:29.849  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 13:48:29.849  6980  7048 I jxcore-log: 
08-12 13:48:30.175  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 13:48:30.175  6980  7048 I jxcore-log: 
,08-12 13:48:30.229  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 13:48:30.229  6980  7048 I jxcore-log: 
08-12 13:48:30.238  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 13:48:30.238  6980  7048 I jxcore-log: 
,08-12 13:48:30.251  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 13:48:30.251  6980  7048 I jxcore-log: 
,08-12 13:48:30.288  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 13:48:30.288  6980  7048 I jxcore-log: 
,08-12 13:48:30.454  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 13:48:30.454  6980  7048 I jxcore-log: 
,08-12 13:48:30.482  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 13:48:30.482  6980  7048 I jxcore-log: 
,08-12 13:48:30.541  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 13:48:30.541  6980  7048 I jxcore-log: 
,08-12 13:48:30.568  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 13:48:30.568  6980  7048 I jxcore-log: 
,08-12 13:48:30.607  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 13:48:30.607  6980  7048 I jxcore-log: 
,08-12 13:48:30.677  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 13:48:30.677  6980  7048 I jxcore-log: 
,08-12 13:48:30.691  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
08-12 13:48:30.691  6980  7048 I jxcore-log: 
,08-12 13:48:31.067  6980  7048 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 13:48:31.067  6980  7048 I jxcore-log: 
,08-12 13:48:31.085  6980  7048 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-12 13:48:31.090  6980  7048 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 13:48:31.090  6980  7048 I jxcore-log: 
08-12 13:48:31.584  6980  7048 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 13:48:31.584  6980  7048 I jxcore-log: 
,08-12 13:48:31.952  7093  7093 D AndroidRuntime: 
08-12 13:48:31.952  7093  7093 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 13:48:31.959  7093  7093 D AndroidRuntime: CheckJNI is OFF
08-12 13:48:32.195  7093  7093 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 13:48:32.214  1034  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 13:48:32.215  1034  1091 I ActivityManager: Killing 6980:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 13:48:32.289  1034  1983 I WindowState: WIN DEATH: Window{131f849e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 13:48:32.294  1034  1544 D WifiService: Client connection lost with reason: 4
08-12 13:48:32.297  1034  1983 D InputDispatcher: Window went away: Window{131f849e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 13:48:32.466  1034  1091 I ActivityManager:   Force finishing activity ActivityRecord{154f28bb u0 com.test.thalitest/.MainActivity t6}
,08-12 13:48:32.493   338   365 E GBMv2   : DFP En is all cleared set to be enabled
08-12 13:48:32.494  1034  1050 W ActivityManager: Spurious death for ProcessRecord{32b273e4 6980:com.test.thalitest/u0a118}, curProc for 6980: null
08-12 13:48:32.494  1034  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 13:48:32.497  1034  1123 I ActivityManager:   Force finishing activity ActivityRecord{154f28bb u0 com.test.thalitest/.MainActivity t6 f}
08-12 13:48:32.497  1034  1123 W ActivityManager: Duplicate finish request for ActivityRecord{154f28bb u0 com.test.thalitest/.MainActivity t6 f}
,08-12 13:48:32.545  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-12 13:48:32.547  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 13:48:32.550  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 13:48:32.551  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 13:48:32.551  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1c214b35 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 13:48:32.552  2035  2127 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-12 13:48:32.553  1943  4002 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 13:48:32.553  1943  4002 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f155bca co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-12 13:48:32.561  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 13:48:32.568  1034  1428 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 13:48:32.577  2513  2695 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 13:48:32.584  3906  3906 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 13:48:32.584  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 13:48:32.584  3782  3782 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-12 13:48:32.586  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 13:48:32.619  6326  6326 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 13:48:32.637  1034  1778 V SIM_STK : Menu title from STK is T-Mobile
,08-12 13:48:32.643  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 13:48:32.645  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 13:48:32.647  1907  1907 D ActionManagerService: notifyUserLog: 1000003
08-12 13:48:32.647  3782  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 13:48:32.654  4515  4515 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 13:48:32.654  4515  4515 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 13:48:32.654  4515  4515 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 13:48:32.654  4515  4515 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 13:48:32.654  4515  4515 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 13:48:32.654  4515  4515 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 13:48:32.654  4515  4515 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:48:32.654  4515  4515 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 13:48:32.654  4515  4515 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 13:48:32.654  4515  4515 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 13:48:32.654  4515  4515 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 13:48:32.654  4515  4515 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-12 13:48:32.660  4626  4626 I art     : Explicit concurrent mark sweep GC freed 7843(456KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 58.987ms total 156.069ms
08-12 13:48:32.665  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 13:48:32.667  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-12 13:48:32.683  1034  1034 I art     : Explicit concurrent mark sweep GC freed 15952(1117KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.980ms total 148.285ms
,08-12 13:48:32.687  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-12 13:48:32.688  1871  1871 D SplitUIService: removed split : 
,08-12 13:48:32.696  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-12 13:48:32.696  1603  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 13:48:32.696  1603  1654 D KeyguardModel: createShortcutInfo...
,08-12 13:48:32.700  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 13:48:32.701  1603  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 13:48:32.701  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.705  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 13:48:32.706  1603  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 13:48:32.707  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 13:48:32.708  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-12 13:48:32.720  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:32.720  1603  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 13:48:32.728  1603  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 13:48:32.728  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.728  1034  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-12 13:48:32.735  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 13:48:32.735  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 13:48:32.738  1034  1906 V SIM_STK : Menu title from STK is T-Mobile
08-12 13:48:32.738  1034  1906 V SIM_STK : Menu title from STK is T-Mobile
08-12 13:48:32.738  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 13:48:32.739  1907  1907 D ActionManagerService: notifyUserLog: 1000004
,08-12 13:48:32.740  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:32.740  1603  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 13:48:32.740  3782  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 13:48:32.742  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-12 13:48:32.742  2219  2219 I ConfigService: onCreate
08-12 13:48:32.742  1871  1871 I SplitUIService: split app #11
08-12 13:48:32.743  1603  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 13:48:32.743  2219  2219 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 13:48:32.743  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.743  3782  3798 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 13:48:32.747  1603  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 13:48:32.747  1603  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 13:48:32.748  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 13:48:32.748  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 13:48:32.749  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:32.749  1603  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 13:48:32.750  1603  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 13:48:32.750  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.750  2219  2219 I ConfigService: onBind returning update interface
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , display: false
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , animation: false }
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , display: false
08-12 13:48:32.753  2035  2035 I GBoardWebViewUtils: , animation: false }
,08-12 13:48:32.754  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-12 13:48:32.754  2035  2035 I GBoardWebViewUtils: , create_time: 1470393743569
08-12 13:48:32.754  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-12 13:48:32.754  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 13:48:32.754  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 13:48:32.754  2035  2035 I GBoardWebViewUtils: , display: false
08-12 13:48:32.754  2035  2035 I GBoardWebViewUtils: , animation: false }
08-12 13:48:32.759  2035  7136 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 13:48:32.770  2219  2219 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 13:48:32.771  2219  2219 I ConfigService: onBind returning config service
,08-12 13:48:32.778  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 13:48:32.779  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 13:48:32.783  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 13:48:32.783  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 13:48:32.791  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-12 13:48:32.791  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 13:48:32.806  1034  1034 D administrator: Handling package changes for user 0
08-12 13:48:32.809  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-12 13:48:32.827  1034  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-12 13:48:32.828  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 13:48:32.828  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 13:48:32.828  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 13:48:32.829  3906  3906 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 13:48:32.836  1034  1783 V SIM_STK : Menu title from STK is T-Mobile
08-12 13:48:32.840  1603  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 13:48:32.840  1603  1654 D KeyguardModel: createShortcutInfo...
,08-12 13:48:32.848  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 13:48:32.849  1603  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 13:48:32.849  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.850  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:32.850  1603  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 13:48:32.851  1818  1818 I ConfigFetchService: service connected
08-12 13:48:32.851  1818  1818 I ConfigClient: service connected
08-12 13:48:32.851  1603  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 13:48:32.851  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.852  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:32.853  1603  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 13:48:32.853  1603  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 13:48:32.853  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.854  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:32.854  1603  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 13:48:32.855  1603  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 13:48:32.855  1603  1654 D KeyguardModel: createShortcutInfo...
08-12 13:48:32.858  2219  2219 I ConfigService: onDestroy
,08-12 13:48:32.860  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-12 13:48:32.860  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 13:48:32.878  1818  7139 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-12 13:48:32.908  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 13:48:32.908  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 13:48:32.908  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 13:48:32.910  1034  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 13:48:32.915  6832  6832 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 13:48:32.916  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 13:48:32.918  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:48:32.920  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 13:48:32.920  5910  7143 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-12 13:48:32.921  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 13:48:32.922  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 13:48:32.923  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-12 13:48:32.940  1818  7148 I PeopleContactsSync: CP2 sync disabled
,08-12 13:48:32.943  2351  7146 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 13:48:32.944  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 13:48:32.944  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:48:32.945  2035  2180 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 13:48:32.945  2035  2180 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 13:48:32.952  1034  1983 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7149 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-12 13:48:32.956  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b8c76cd u0 com.lge.launcher2/.Launcher t5} time:350357
08-12 13:48:32.961  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 13:48:32.962  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 13:48:32.962  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:48:32.970  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-12 13:48:32.971  1818  4783 I Icing   : doRemovePackageData com.test.thalitest
08-12 13:48:32.971  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
08-12 13:48:32.972  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 13:48:32.975  2035  2035 D [Concierge]WidgetView: change position of spinner
08-12 13:48:32.984  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1471002512984
08-12 13:48:32.984  2583  2583 D [Concierge]Service: Update widget ID : 11
08-12 13:48:32.985  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
,08-12 13:48:33.004  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 372086690
08-12 13:48:33.004  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 13:48:33.005  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 13:48:33.007  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@522b2ed
08-12 13:48:33.007  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 13:48:33.008  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 13:48:33.009  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 13:48:33.013  1818  7145 W GmsApplication: Using Auth Proxy for data requests.
08-12 13:48:33.014  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 13:48:33.014  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 13:48:33.014  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 13:48:33.015  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471002190874, New one : 1471002512984
08-12 13:48:33.015  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-12 13:48:33.015  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 13:48:33.015  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:48:33.017  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 13:48:33.018  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 13:48:33.018  1818  7145 W GmsApplication: Using Auth Proxy for data requests.
08-12 13:48:33.018  7149  7149 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 13:48:33.019  7149  7149 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 13:48:33.019  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 13:48:33.020  7149  7149 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 13:48:33.020  7149  7149 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 13:48:33.020  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 13:48:33.022  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-12 13:48:33.025  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:48:33.025  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:48:33.028  1034  1123 I art     : Explicit concurrent mark sweep GC freed 11246(768KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.996ms total 329.019ms
08-12 13:48:33.074  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 13:48:33.076  7149  7149 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-12 13:48:33.085  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 13:48:33.085  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 13:48:33.087  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:48:33.090  7149  7149 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-12 13:48:33.109  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b15a83f time:350511
,08-12 13:48:33.113  7149  7149 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:33.118  2219  2239 I art     : Explicit concurrent mark sweep GC freed 3397(196KB) AllocSpace objects, 2(32KB) LOS objects, 35% free, 29MB/45MB, paused 361us total 18.900ms
08-12 13:48:33.137   324   419 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-12 13:48:33.138  3188  7170 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-12 13:48:33.163  7093  7093 D AndroidRuntime: Shutting down VM
,08-12 13:48:33.167  7149  7149 D LgDataFeature: LgDataFeature() Constructor: none
08-12 13:48:33.167  7149  7149 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 13:48:33.177  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 13:48:33.186  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 13:48:33.189  1034  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7173 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-12 13:48:33.191  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 13:48:33.217  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 13:48:33.228  1034  1778 I ActivityManager: Killing 6634:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-12 13:48:33.241  7149  7149 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 13:48:33.253  2035  2897 I GBoardtInterface: onReloaded()
,08-12 13:48:33.254  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 13:48:33.271  1034  1983 W libprocessgroup: failed to open /acct/uid_1000/pid_6634/cgroup.procs: No such file or directory
,08-12 13:48:33.271  3782  3798 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 13:48:33.273  3782  4502 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 13:48:33.278  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-12 13:48:33.279  3782  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 13:48:33.279  3782  4505 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-12 13:48:33.281  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-12 13:48:33.282  3782  4505 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 13:48:33.282  3782  4505 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 13:48:33.282  3782  4505 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 13:48:33.282  3782  4505 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
,08-12 13:48:33.283  1034  1575 I ActivityManager: Killing 6653:com.android.calendar/u0a13 (adj 15): empty #17
08-12 13:48:33.283  3782  3798 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 13:48:33.339  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 13:48:33.340  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 13:48:33.341  1034  1778 W libprocessgroup: failed to open /acct/uid_10013/pid_6653/cgroup.procs: No such file or directory
08-12 13:48:33.342  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-12 13:48:33.346  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 13:48:33.346  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 13:48:33.348  6326  6326 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 13:48:33.349  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 13:48:33.349  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 13:48:33.351  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 13:48:33.351  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 13:48:33.370  1034  1050 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7194 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 13:48:33.434  7194  7194 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 13:48:33.435  7194  7194 W LG Account v2.2: No ProfileInfo entries
08-12 13:48:33.435  7194  7194 I LG Account v2.2: isEnabled: false
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Country: EU
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Operator: OPEN
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Ranking support: false
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Comfort support: false
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Accessory: true
,08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Health device: true
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Extra Pedometer: false
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Blood glucose device: false
08-12 13:48:33.435  7194  7194 I Feature : [Lifetracker]Device Number: 3
08-12 13:48:33.436  7194  7194 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 13:48:33.465  1034  1976 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7215 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 13:48:33.466  1034  1976 I ActivityManager: Killing 6612:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-12 13:48:33.481   342   342 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 719us total 11.871ms
,08-12 13:48:33.492   342   342 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 325us total 10.199ms
,08-12 13:48:33.503   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 8.841ms

```
