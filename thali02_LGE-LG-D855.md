#### Test 832688936f8f85f_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
09-02 11:36:08.253  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=136832183 [*alarm*], flags=0x0
,--------- beginning of main
09-02 11:36:33.143  6189  6189 D AndroidRuntime: 
09-02 11:36:33.143  6189  6189 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 11:36:33.147  6189  6189 D AndroidRuntime: CheckJNI is OFF
09-02 11:36:33.353  6189  6189 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 11:36:33.364  1036  1923 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 11:36:33.379  1942  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-02 11:36:33.385  1036  1923 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-02 11:36:33.386  1036  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{3cb429cc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 11:36:33.386  1036  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{3cb429cc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 11:36:33.388  1036  1923 D WindowStateEx: AppWindowTokenEx init.. 
09-02 11:36:33.389   346   386 E GBMv2   : DFP En is all cleared set to be enabled
09-02 11:36:33.416  1036  1923 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6204 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 11:36:33.419  6189  6189 D AndroidRuntime: Shutting down VM
09-02 11:36:33.474  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-02 11:36:33.474  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3836706c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 11:36:33.475  1942  3866 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-02 11:36:33.475  1942  3866 D SplitWindowPolicy: topRunningActivity=ActivityInfo{24f6f635 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 11:36:33.510  6204  6204 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-02 11:36:33.639  6204  6204 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 11:36:33.647  6204  6204 I LibraryLoader: Loading: webviewchromium
09-02 11:36:33.649  6204  6204 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9183-9186)
09-02 11:36:33.649  6204  6204 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 11:36:33.668  6204  6204 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {20096d08}
09-02 11:36:33.669  6204  6204 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 11:36:33.669  6204  6204 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 11:36:33.678  6204  6204 I BrowserStartupController: Initializing chromium process, renderers=0
09-02 11:36:33.679  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 11:36:33.691  6204  6239 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,09-02 11:36:33.694   319  1383 V AudioPolicyService: registerClient() client 0xb04100c0, uid 10118
09-02 11:36:33.699  6204  6204 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-02 11:36:33.700  6204  6204 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-02 11:36:33.700  6204  6204 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-02 11:36:33.702  1036  1118 D BluetoothManagerService: Message: 20
09-02 11:36:33.702  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16e017f6:true
09-02 11:36:33.742  6204  6204 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 11:36:33.742  6204  6204 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 11:36:33.742  6204  6204 I Adreno-EGL: Build Date: 12/12/14 금
09-02 11:36:33.742  6204  6204 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 11:36:33.742  6204  6204 I Adreno-EGL: Remote Branch: 
09-02 11:36:33.742  6204  6204 I Adreno-EGL: Local Patches: 
09-02 11:36:33.742  6204  6204 I Adreno-EGL: Reconstruct Branch: 
,09-02 11:36:33.835  6204  6250 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-02 11:36:33.838  6204  6204 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-02 11:36:33.857  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 11:36:33.863  6204  6204 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 11:36:33.867  6204  6204 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-02 11:36:33.871  6204  6204 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-02 11:36:33.871  6204  6204 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-02 11:36:33.885  6204  6204 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-02 11:36:33.898  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 11:36:33.898  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 11:36:33.922  6204  6263 D OpenGLRenderer: Render dirty regions requested: true
09-02 11:36:33.922  6204  6263 I OpenGLRenderer: Initialized EGL, version 1.4
09-02 11:36:33.936  6204  6263 D OpenGLRenderer: Enabling debug mode 0
,09-02 11:36:33.951  6204  6204 D Atlas   : Validating map...
,09-02 11:36:33.955  1036  2050 D SplitWindow: check instance of lgWin Window{38294200 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 11:36:34.006  6204  6261 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:36:34.006  6204  6261 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 11:36:34.099  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +628ms (total +708ms)
09-02 11:36:34.100  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d3a2415 u0 com.test.thalitest/.MainActivity t6} time:169636
,09-02 11:36:34.100  6204  6204 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@136fb777 time:169637
09-02 11:36:34.237  6204  6204 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-02 11:36:34.237  6204  6204 I chromium: 
,09-02 11:36:34.272  6204  6204 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 11:36:34.370  6204  6261 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-02 11:36:34.370  6204  6261 I chromium: 
,09-02 11:36:34.548  6204  6280 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435123584
,09-02 11:36:34.565  6204  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 11:36:34.565  6204  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 11:36:34.565  6204  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 11:36:34.565  6204  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 11:36:34.565  6204  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 11:36:34.565  6204  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192a328b added. We now have 1 listener(s)
09-02 11:36:34.571  1036  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:34.574  6204  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-02 11:36:34.575  6204  6280 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:36:34.576  6204  6280 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:34.577  6204  6280 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 11:36:34.585  6204  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd6f826 added. We now have 1 listener(s)
09-02 11:36:34.586  6204  6280 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:34.590  1036  1542 D WifiService: New client listening to asynchronous messages
,09-02 11:36:34.598  6204  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:36:34.599  6204  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 11:36:34.601  6204  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 11:36:34.601  6204  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 11:36:34.602  6204  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-02 11:36:34.606  6204  6280 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:34.606  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:34.608  6204  6280 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-02 11:36:34.615  6204  6280 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:34.616  6204  6280 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:34.616  6204  6280 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 11:36:34.616  6204  6280 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 11:36:34.618  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:34.620  6204  6280 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 11:36:34.656  6204  6204 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 11:36:35.351   346   388 E GBMv2   : DFP En is all cleared set to be enabled
09-02 11:36:35.351   346   388 E GBMv2   : Set value is all cleared set the max
09-02 11:36:35.351   346   388 I GBMv2   : DFP Enabled. Ignore VFP set
,09-02 11:36:35.804  6204  6283 W jxcore-log: Initializing JXcore engine
09-02 11:36:35.804  6204  6283 W jxcore-log: JXcore engine is ready
,09-02 11:36:35.868  6283  6283 W Thread-697: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7612]" dev="sockfs" ino=7612 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-02 11:36:35.868  6283  6283 W Thread-697: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-02 11:36:35.868  6283  6283 W Thread-697: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10459]" dev="sockfs" ino=10459 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 11:36:35.868  6283  6283 W Thread-697: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-02 11:36:35.868  6283  6283 W Thread-697: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[30558]" dev="sockfs" ino=30558 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-02 11:36:35.907  6204  6283 W jxcore-log: Starting JXcore engine
,09-02 11:36:36.070  6204  6283 W jxcore-log: Platform android
09-02 11:36:36.070  6204  6283 W jxcore-log: 
09-02 11:36:36.071  6204  6283 W jxcore-log: Process ARCH arm
09-02 11:36:36.071  6204  6283 W jxcore-log: 
,09-02 11:36:36.468  6204  6283 I jxcore-log: JXcore Cordova bridge is ready!
09-02 11:36:36.468  6204  6283 I jxcore-log: 
,09-02 11:36:36.468  6204  6283 W jxcore-log: JXcore engine is started
09-02 11:36:36.474  6204  6280 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-02 11:36:36.479  6204  6204 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-02 11:36:39.726  1036  1398 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d2ac956 type 2 when 175246 com.google.android.gms} when 175246
,09-02 11:36:39.973  1036  1904 I art     : Explicit concurrent mark sweep GC freed 39579(1828KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.101ms total 195.036ms
,09-02 11:36:47.712  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 11:36:47.712  6204  6283 I jxcore-log: 
,09-02 11:36:47.715  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 11:36:47.715  6204  6283 I jxcore-log: 
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:47.719  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:47.721  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:47.724  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 11:36:47.724  6204  6283 I jxcore-log: 
09-02 11:36:47.725  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 11:36:47.725  6204  6283 I jxcore-log: 
,09-02 11:36:48.224  6204  6283 D executeNativeTests: Running unit tests
,09-02 11:36:48.304  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-02 11:36:48.304  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 added. We now have 2 listener(s)
,09-02 11:36:48.305  1036  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:48.307  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:36:48.307  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:48.307  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:36:48.307  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:48.307  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa added. We now have 2 listener(s)
09-02 11:36:48.307  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:48.309  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:36:48.310  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:48.312  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:48.314  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:48.314  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:36:48.316  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 11:36:48.316  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:48.317  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 11:36:48.317  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 11:36:48.318  6204  6283 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-02 11:36:48.318  6204  6283 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-02 11:36:48.319  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 11:36:48.319  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 11:36:48.319  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 11:36:48.319  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.320  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.320  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.320  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.320  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.320  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:48.320  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:36:48.321  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 removed from the list
09-02 11:36:48.321  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.321  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa removed from the list
09-02 11:36:48.321  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.321  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.322  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.322  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.322  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.323  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.323  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.323  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.325  6204  6283 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-02 11:36:48.325  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.325  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.325  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.326  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.326  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.326  6204  6283 D o,rg.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.326  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.326  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.326  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.326  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.326  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.326  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.326  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.326  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.326  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.326  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.326  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.327  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 11:36:48.330  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 11:36:48.331  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 11:36:48.331  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.331  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.331  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.333  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.333  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.333  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.333  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.333  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.333  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.333  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.333  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.333  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.333  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.333  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-02 11:36:48.334  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.334  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.334  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.334  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.334  6204  6283 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
09-02 11:36:48.335  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:48.337  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:36:48.338  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:48.338  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:36:48.339  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-02 11:36:48.339  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:36:48.340  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:36:48.340  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:36:48.340  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.340  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:36:48.343  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 11:36:48.343  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:48.346  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 11:36:48.350  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 11:36:48.352  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 11:36:48.352  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:36:48.353  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:48.354  6204  6283 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 11:36:48.355  6204  6283 I io.jxcore.node.ConnectionHelper: start: OK
09-02 11:36:48.357  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.357  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.357  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.357  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.357  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.357  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:48.357  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.357  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.357  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.357  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.357  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.358  6204  6283 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 11:36:48.359  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:48.360  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:48.361  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:48.361  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:36:48.362  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:48.362  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 11:36:48.362  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:36:48.362  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:36:48.362  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.362  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:36:48.365  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:36:48.365  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:48.366  6204  6283 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 11:36:48.366  6204  6283 I io.jxcore.node.ConnectionHelper: start: OK
09-02 11:36:48.367  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.367  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.367  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 11:36:48.367  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.367  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.367  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:48.367  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.367  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.367  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list,
09-02 11:36:48.367  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.367  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.368  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.368  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.368  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.368  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:36:48.369  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.369  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.369  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.369  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.370  6204  6283 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 11:36:48.371  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:48.373  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:48.374  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:48.374  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:36:48.374  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:48.375  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:36:48.375  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:36:48.375  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:36:48.375  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.375  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:36:48.377  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:36:48.377  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:48.378  6204  6283 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 11:36:48.378  6204  6283 I io.jxcore.node.ConnectionHelper: start: OK
09-02 11:36:48.378  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.379  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.379  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.379  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.379  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.379  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.380  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.380  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.380  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:48.380  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.380  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.380  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.380  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.380  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.380  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.380  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.381  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.381  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.381  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.381  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.381  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 11:36:48.381  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.381  6204  6283 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 11:36:48.382  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.382  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.382  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 11:36:48.382  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.382  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-02 11:36:48.382  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.382  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.382  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.382  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.382  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop,
09-02 11:36:48.382  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.382  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.382  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.382  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.383  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.383  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.383  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.383  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.383  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.383  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.384  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 11:36:48.384  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 11:36:48.384  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.384  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.384  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.385  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.385  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.385  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.385  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.385  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.385  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.385  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.385  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.385  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.385  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.386  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.386  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 11:36:48.386  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.386  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.386  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.386  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.387  6204  6283 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
09-02 11:36:48.387  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.387  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.387  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.387  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.387  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:36:48.387  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.387  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.387  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.387  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.387  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 11:36:48.387  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.387  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.387  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.387  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.388  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.388  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.388  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.388  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.388  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 11:36:48.388  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.389  6204  6283 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 11:36:48.389  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.389  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:48.389  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.389  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.389  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.389  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.389  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.389  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.389  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.389  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 11:36:48.389  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.389  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.390  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.390  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.390  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.390  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.391  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.391  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.391  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 11:36:48.391  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.391  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 11:36:48.391  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-02 11:36:48.391  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 11:36:48.391  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 11:36:48.391  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-02 11:36:48.391  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 11:36:48.391  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.391  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.391  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 11:36:48.392  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.392  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.392  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.392  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.392  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.392  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
,09-02 11:36:48.392  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.392  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.392  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.392  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.392  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.393  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.393  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.394  6204  6283 D BluetoothLeScanner: could not find callback wrapper
,09-02 11:36:48.394  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.394  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.394  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.394  6204  6283 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
,09-02 11:36:48.394  6204  6283 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 11:36:48.394  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 11:36:48.396  6204  6283 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 11:36:48.396  6204  6283 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 11:36:48.396  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 11:36:48.397  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 11:36:48.397  6204  6283 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 11:36:48.397  6204  6283 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 11:36:48.397  6204  6283 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-02 11:36:48.397  6204  6283 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 11:36:48.397  6204  6283 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 11:36:48.397  6204  6283 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 11:36:48.397  6204  6283 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-02 11:36:48.397  6204  6283 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 11:36:48.397  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 11:36:48.400  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 11:36:48.401  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 11:36:48.401  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
09-02 11:36:48.401  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 11:36:48.401  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 11:36:48.401  6204  6283 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 11:36:48.402  6204  6283 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
,09-02 11:36:48.402  6204  6283 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-02 11:36:48.402  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.402  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.402  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 11:36:48.402  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.402  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.402  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.402  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 11:36:48.404  6204  6302 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 761)
09-02 11:36:48.413  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
,09-02 11:36:48.413  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 11:36:48.413  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.413  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 11:36:48.413  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.413  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.413  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:36:48.413  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.415  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.415  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:36:48.415  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.415  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.415  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.415  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list,
09-02 11:36:48.416  6204  6283 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported,
09-02 11:36:48.416  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.417  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.417  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 11:36:48.417  6204  6303 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 761
09-02 11:36:48.417  6204  6303 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 761)
09-02 11:36:48.417  6204  6303 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 761)
,09-02 11:36:48.417  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.417  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.418  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.418  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.418  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 11:36:48.418  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.418  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.418  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.418  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-02 11:36:48.418  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.418  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.418  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.418  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 11:36:48.419  6204  6283 D BluetoothLeScanner: could not find callback wrapper,
09-02 11:36:48.419  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.419  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.419  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list,
09-02 11:36:48.419  6204  6283 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 11:36:48.420  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.420  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:48.420  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.420  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.420  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:36:48.420  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.420  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.420  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.420  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.420  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.420  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.420  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.420  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.420  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.421  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.421  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.422  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.422  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.422  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.422  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.422  6204  6283 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 11:36:48.422  6204  6283 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 11:36:48.422  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 11:36:48.423  6204  6283 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 11:36:48.423  6204  6283 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 11:36:48.423  6204  6283 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 11:36:48.423  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 11:36:48.423  6204  6283 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 11:36:48.423  6204  6283 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 11:36:48.423  6204  6283 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 11:36:48.423  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 11:36:48.423  6204  6283 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 11:36:48.424  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.424  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.424  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.424  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.424  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.424  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.424  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.424  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.424  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.424  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.424  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.424  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.424  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.424  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.425  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.425  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.426  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.426  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 11:36:48.426  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.426  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.427  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.427  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.427  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:48.427  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.427  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.427  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.427  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.428  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.428  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.428  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.428  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.428  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.428  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.428  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.428  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
,09-02 11:36:48.428  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.428  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.428  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.428  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.428  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.428  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.428  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.428  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.428  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.428  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.428  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.429  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.429  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.429  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.429  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.429  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.430  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.430  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.430  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.430  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.431  6204  6283 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 11:36:48.431  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:48.431  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 11:36:48.432  6204  6283 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 11:36:48.432  6204  6283 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 11:36:48.432  6204  6204 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 11:36:48.432  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 11:36:48.432  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 11:36:48.433  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.433  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 11:36:48.433  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 11:36:48.433  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 11:36:48.433  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.433  6204  6283 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 11:36:48.434  6204  6304 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 11:36:48.434  6204  6304 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 11:36:48.435  6204  6204 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 11:36:48.435  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.435  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.435  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:36:48.435  6204  6283 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 11:36:48.435  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:36:48.435  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 11:36:48.436  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:36:48.437  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:48.437  6204  6283 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 11:36:48.437  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.437  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.438  6204  6283 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:36:48.439  6204  6204 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:36:48.439  6204  6204 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 11:36:48.439  6204  6204 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:36:48.439  6204  6204 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:36:48.439  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.439  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.439  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.439  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.439  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.439  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.439  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.439  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.439  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.439  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.439  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.439  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.439  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.439  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.440  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.440  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.440  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.440  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.440  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.441  6204  6283 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 11:36:48.441  6204  6283 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 11:36:48.441  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 11:36:48.442  6204  6283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 11:36:48.442  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.442  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.442  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.444  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.444  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.444  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.444  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.444  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.444  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.445  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.445  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.445  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.445  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.445  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.445  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.445  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.445  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.446  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.446  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:48.447  1036  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:48.448  1036  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:48.449  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.449  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.449  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.450  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.450  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.450  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.450  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.450  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.450  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.450  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.450  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.450  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.450  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.450  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.453  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.453  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.453  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.453  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.454  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:48.454  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:48.454  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:48.454  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:48.454  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.454  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.454  6204  6283 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e02a395 not in the list
09-02 11:36:48.454  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.454  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.454  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:48.454  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.454  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.454  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:48.454  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:48.455  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:48.455  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:48.455  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:48.455  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f353caa not in the list
09-02 11:36:48.456  6204  6283 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 11:36:48.456  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 11:36:48.457  6204  6283 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 11:36:48.457  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 11:36:48.457  6204  6283 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 11:36:48.457  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 11:36:48.458  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 11:36:48.458  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 11:36:48.458  6204  6283 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 11:36:48.458  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 11:36:48.458  6204  6283 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 11:36:48.459  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 11:36:48.459  6204  6283 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 11:36:48.459  6204  6283 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 11:36:48.465  6204  6283 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 11:36:48.465  6204  6283 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 11:36:48.470  6204  6283 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 11:36:48.470  6204  6283 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 11:36:48.470  6204  6283 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 11:36:48.470  6204  6283 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 11:36:48.471  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:48.471  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27a0b813 added. We now have 2 listener(s)
09-02 11:36:48.471  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:48.472  6204  6283 D BluetoothAdapter: enable(): BT is already enabled..!
,09-02 11:36:48.474  1036  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6204, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 11:36:48.474  1036  1052 D WifiService: setWifiEnabled: true pid=6204, uid=10118
09-02 11:36:48.474  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 11:36:48.475  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:48.476  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9365a50 added. We now have 3 listener(s)
09-02 11:36:48.476  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:48.479  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:48.479  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25890449 added. We now have 4 listener(s)
09-02 11:36:48.479  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:48.480  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:48.480  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@141b414e added. We now have 5 listener(s)
09-02 11:36:48.480  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:48.482  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6204, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 11:36:48.482  1036  1052 D WifiService: setWifiEnabled: false pid=6204, uid=10118
09-02 11:36:48.482  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 11:36:48.491  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:36:48.491  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:36:48.491  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-02 11:36:48.491  1036  1536 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:48.492  1036  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:48.492  1036  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:48.493  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:48.494  1036  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:48.494  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 11:36:48.494  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-02 11:36:48.494  1036  2050 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15885919 mBinding = false
09-02 11:36:48.494  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:48.494  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:48.494  1036  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:48.494  1036  1555 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:48.494  1036  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@73658e6
09-02 11:36:48.494  1036  1535 D LGWifiP2pService: P2pDisablingState
09-02 11:36:48.494  1036  1535 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:48.495  1036  1535 D LGWifiP2pService: p2p socket connection lost
09-02 11:36:48.495  1036  1535 D LGWifiP2pService: P2pDisabledState
09-02 11:36:48.496  1036  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 11:36:48.496  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 11:36:48.496   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 11:36:48.496  1942  1942 D WfdsService: WifiP2pState is changed : false
09-02 11:36:48.496  1942  2258 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 11:36:48.496  1942  2258 D WfdsService: Set the WFDS Monitor: false
09-02 11:36:48.497  1942  2258 D WfdsMonitor: WFDS Monitor is stopped
09-02 11:36:48.497  1942  2258 D WfdsService: STATE : WfdsDisabledState - enter
09-02 11:36:48.497  1942  2814 D CtrlSupplicant: Received on exit socket, terminate
09-02 11:36:48.497  1942  2814 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 11:36:48.497  1942  2814 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 11:36:48.497  1942  2814 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 11:36:48.497  1942  2260 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 11:36:48.497  1942  2258 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 11:36:48.501  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 11:36:48.501  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 11:36:48.503  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-02 11:36:48.503  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:48.503  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:48.503  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 11:36:48.505  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:48.506  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-02 11:36:48.506  1036  1536 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 11:36:48.506  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:36:48.506  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:36:48.506  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-02 11:36:48.506  1036  1536 D WifiNative-p2p0: TERMINATE: returned true
09-02 11:36:48.506  1036  1118 D BluetoothManagerService: Message: 2
09-02 11:36:48.506  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:36:48.506  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:36:48.506  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 11:36:48.507  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:48.507  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:48.507  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 11:36:48.508  1036  1118 D BluetoothManagerService: Sending off request.
09-02 11:36:48.509  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 11:36:48.509  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 11:36:48.509  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:48.509  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 11:36:48.511  3780  3899 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 11:36:48.511  3780  3854 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 11:36:48.511  3780  3854 D BluetoothAdapterProperties: Setting state to 13
09-02 11:36:48.512  3780  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 11:36:48.512  3780  3854 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 11:36:48.512  3780  3854 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:48.512  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:48.512  6204  6204 W org.thaliprojec,t.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:48.512  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:36:48.516  3780  3861 D BluetoothAdapterProperties: Scan Mode:20
09-02 11:36:48.517  3780  3854 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 11:36:48.517  3780  3854 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 11:36:48.519  3780  4138 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 11:36:48.519  3780  4139 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:36:48.520  3780  4160 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:36:48.520  3780  4163 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:36:48.520  3780  4166 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:36:48.522  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 11:36:48.522  3780  3959 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 11:36:48.526  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 11:36:48.526  3780  3959 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 11:36:48.527  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:36:48.527  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 11:36:48.527  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 11:36:48.528  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor:   ,  - is Wi-Fi Direct supported: true
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:48.528  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:48.528  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:48.528  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:48.529  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:48.529  3780  3780 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:48.529  3780  3780 D BluetoothMapService: STATE_TURNING_OFF
09-02 11:36:48.529  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:48.529  3780  3780 V BluetoothMapService: Handler(): got msg=4
09-02 11:36:48.529  3780  3780 D BluetoothMapService: MAP Service closeService in
09-02 11:36:48.529  3780  3780 D BluetoothMapMasInstance: MAP Service shutdown
09-02 11:36:48.530  3780  3780 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 11:36:48.530  3780  3780 V BluetoothMapService: MAP Service closeService out
09-02 11:36:48.530  3780  3780 V BtOppService: Receiver DISABLED_ACTION 
09-02 11:36:48.530  3780  3780 I BtOppRfcommListener: stopping Accept Thread
09-02 11:36:48.530  3780  3780 V BtOppRfcommListener: close mBtServerSocket
09-02 11:36:48.530  3780  3780 V BtOppRfcommListener: waiting for thread to terminate
09-02 11:36:48.531  3780  4160 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 11:36:48.531  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:48.532  3780  3780 V BtOppRfcommListener: done waiting for thread to terminate
09-02 11:36:48.536  6204  6302 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-02 11:36:48.537  6204  6302 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 761)
09-02 11:36:48.544  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 11:36:48.544  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 11:36:48.546  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:48.547  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:48.548  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 11:36:48.562  1036  1102 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6319 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 11:36:48.563  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:36:48.565  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:48.565  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:48.565  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:48.565  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:48.565  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:36:48.566  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:48.598  1036  2012 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6336 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 11:36:48.600  3780  3780 V BtOppService: onDestroy
09-02 11:36:48.603  3780  3780 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 11:36:48.612  6319  6319 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 11:36:48.613  6319  6319 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-02 11:36:48.613  6319  6319 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 11:36:48.613  6319  6319 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-02 11:36:48.614  2672  2672 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 11:36:48.614  2672  2672 I wpa_supplicant: monitor socket send errors count : 1
09-02 11:36:48.614  2672  2672 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
09-02 11:36:48.614  6319  6319 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 11:36:48.614  6319  6319 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 11:36:48.615  1036  2812 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 11:36:48.615  1036  2812 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 11:36:48.641  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-02 11:36:48.644  6336  6336 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 11:36:48.644  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:48.646  1036  1903 I ActivityManager: Killing 4850:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-02 11:36:48.652  2672  2672 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 11:36:48.652  1036  2812 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 11:36:48.652  1036  2812 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 11:36:48.652  1036  2812 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 11:36:48.652  1036  2812 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,09-02 11:36:48.653  2672  2672 W wpa_supplicant: USIM:  scard_deinit function
09-02 11:36:48.655  1036  1118 D Tethering: InitialState.processMessage what=4
09-02 11:36:48.655  1036  2812 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:36:48.655  1036  2812 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:36:48.655  1036  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=184182
09-02 11:36:48.656  1036  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=184182
09-02 11:36:48.656  1036  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=184183  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 11:36:48.656  1036  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=184183  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 11:36:48.675  1036  1574 W libprocessgroup: failed to open /acct/uid_10014/pid_4850/cgroup.procs: No such file or directory
,09-02 11:36:48.677  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 11:36:48.678  1036  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:48.678  1036  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:48.680   315  6357 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 11:36:48.680  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-02 11:36:48.725  2672  2672 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 11:36:48.725  1036  2812 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 11:36:48.725  1036  2812 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 11:36:48.726  1036  2812 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 11:36:48.727  1036  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
,09-02 11:36:48.729  6319  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 11:36:48.732  3780  3780 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-02 11:36:48.732  3780  3780 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:48.733  3780  3780 V BluetoothPbapReceiver: ***********state = 13
09-02 11:36:48.736  3780  3780 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-02 11:36:48.740  3780  3780 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:48.740  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:36:48.740  3780  3780 V BluetoothPbapService: state: 13
09-02 11:36:48.741  3780  3780 V BluetoothPbapService: Pbap Service closeService in
,09-02 11:36:48.744  3780  3780 V BluetoothPbapService: successfully stopped pbap service
09-02 11:36:48.744  3780  3780 V BluetoothPbapService: Pbap Service closeService out
09-02 11:36:48.745  3780  3780 V BluetoothPbapService: Pbap Service onDestroy
09-02 11:36:48.745  3780  3780 V BluetoothPbapService: Pbap Service closeService in
09-02 11:36:48.745  3780  3780 V BluetoothPbapService: Pbap Service closeService out
09-02 11:36:48.745  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:36:48.745  3780  3780 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-02 11:36:48.771  1036  1923 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6359 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-02 11:36:48.789  6319  6319 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 11:36:48.789  6319  6319 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 11:36:48.797  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:48.801  1036  1118 D BluetoothManagerService: Message: 20
09-02 11:36:48.801  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@368144db:true
,09-02 11:36:48.809  1036  1118 D BluetoothManagerService: Message: 30
09-02 11:36:48.813  1036  1118 D BluetoothManagerService: Message: 30
,09-02 11:36:48.818  6319  6319 D LocalBluetoothProfileManager: Adding local MAP profile
09-02 11:36:48.819  6319  6319 D BluetoothMap: Create BluetoothMap proxy object
09-02 11:36:48.820  1036  1118 D BluetoothManagerService: Message: 30
09-02 11:36:48.824  1036  1118 D BluetoothManagerService: Message: 30
,09-02 11:36:48.829  1036  1536 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 11:36:48.830  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:36:48.830  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:36:48.830  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 11:36:48.830  1942  1942 D WfdsService: Supplicant Connection state is changed : false
09-02 11:36:48.831  1942  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 11:36:48.831  1942  2258 D WfdsService: Set the WFDS Monitor: false
09-02 11:36:48.831  1942  2258 D WfdsMonitor: WFDS Monitor is stopped
09-02 11:36:48.832  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 11:36:48.832  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:48.832  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 11:36:48.833  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 11:36:48.833  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 11:36:48.833  6319  6319 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-02 11:36:48.834  2466  2466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:48.835  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:48.837  6319  6319 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-02 11:36:48.841  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:48.862  6319  6319 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-02 11:36:48.866  6319  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-02 11:36:48.875  6319  6319 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:36:48.877  6359  6359 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-02 11:36:48.877  6359  6359 W LG Account v2.2: No ProfileInfo entries
09-02 11:36:48.878  6359  6359 I LG Account v2.2: isEnabled: false
,09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Country: EU
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Operator: OPEN
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Ranking support: false
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Comfort support: false
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Accessory: true
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Health device: true
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Extra Pedometer: false
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Blood glucose device: false
09-02 11:36:48.878  6359  6359 I Feature : [Lifetracker]Device Number: 3
09-02 11:36:48.881  1036  1923 I ActivityManager: Killing 5681:com.android.defcontainer/u0a4 (adj 15): empty #17
09-02 11:36:48.884  6319  6319 D BluetoothInputDevice: Proxy object connected
09-02 11:36:48.885  6319  6319 D HidProfile: Bluetooth service connected
09-02 11:36:48.885  6319  6319 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 11:36:48.886  6319  6319 D PanProfile: Bluetooth service connected
09-02 11:36:48.886  6319  6319 D BluetoothMap: Proxy object connected
09-02 11:36:48.887  6319  6319 D MapProfile: Bluetooth service connected
09-02 11:36:48.887  6319  6319 D BluetoothMap: getConnectedDevices()
,09-02 11:36:48.888  6319  6319 D BluetoothMap: Bluetooth is Not enabled
,09-02 11:36:48.888  6319  6319 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 11:36:48.904  1036  1959 W libprocessgroup: failed to open /acct/uid_10004/pid_5681/cgroup.procs: No such file or directory
,09-02 11:36:48.908  6319  6319 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 11:36:48.911  6319  6319 D BluetoothPermissionRequest: onReceive
09-02 11:36:48.913  6319  6319 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 11:36:48.917  1036  1959 I ActivityManager: Killing 5777:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-02 11:36:48.919  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:36:48.939  6204  6204 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 11:36:48.949  3780  3780 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 11:36:48.950  3780  3780 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 11:36:48.951  3780  3780 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 11:36:48.952  1036  1785 W libprocessgroup: failed to open /acct/uid_10008/pid_5777/cgroup.procs: No such file or directory
,09-02 11:36:49.038  1036  1959 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6385 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-02 11:36:49.044  3780  3780 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:49.044  3780  3780 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 11:36:49.045  3780  3780 V BluetoothFtpService: Ftp Service onStartCommand
09-02 11:36:49.045  3780  3780 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:49.046  3780  3780 V BluetoothFtpService: Ftp Service closeService
09-02 11:36:49.046  3780  3780 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 11:36:49.049  3780  3780 V BluetoothFtpService: successfully stopped ftp service
09-02 11:36:49.050  3780  3780 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:36:49.050  3780  3780 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 11:36:49.050  3780  3780 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 11:36:49.050  3780  3780 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:49.050  3780  3780 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 11:36:49.050  3780  3780 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 11:36:49.052  3780  3780 V BluetoothFtpService: Ftp Service onDestroy
09-02 11:36:49.052  3780  3780 V BluetoothFtpService: Ftp Service closeService
,09-02 11:36:49.111  1036  1977 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6402 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 11:36:49.112  3780  3780 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:49.112  3780  3780 V BluetoothSapService: state: 13
,09-02 11:36:49.113  3780  3780 V BluetoothSapService: Stopping SAP server process
09-02 11:36:49.114  3780  3780 V BluetoothSapService: Sap Service closeSapService in
09-02 11:36:49.114  3780  3780 V BluetoothSapService: Close listen Socket : 
09-02 11:36:49.114  3780  3780 V BluetoothSapService: Close rfcomm Socket : 
09-02 11:36:49.114  3780  3780 V BluetoothSapService: Close sapd  Socket : 
09-02 11:36:49.120  3780  3780 V BluetoothSapService: Sap Service closeSapService out
09-02 11:36:49.123  3780  3780 V BluetoothSapService: Sap Service onDestroy
09-02 11:36:49.123  3780  3780 V BluetoothSapService: Sap Service closeSapService in
09-02 11:36:49.123  3780  3780 V BluetoothSapService: Close listen Socket : 
09-02 11:36:49.123  3780  3780 V BluetoothSapService: Close rfcomm Socket : 
09-02 11:36:49.123  3780  3780 V BluetoothSapService: Close sapd  Socket : 
,09-02 11:36:49.126  3780  3780 V BluetoothSapService: Sap Service closeSapService out
09-02 11:36:49.150  6385  6385 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 11:36:49.178  6385  6385 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-02 11:36:49.178  6402  6402 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 11:36:49.196  1036  1574 I ActivityManager: Killing 5810:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-02 11:36:49.216  6385  6385 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-02 11:36:49.217  6385  6385 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 11:36:49.217  6385  6385 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-02 11:36:49.217  6385  6385 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-02 11:36:49.218  6385  6385 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-02 11:36:49.220  6385  6385 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-02 11:36:49.226  6385  6385 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-02 11:36:49.280  1036  1785 W libprocessgroup: failed to open /acct/uid_10011/pid_5810/cgroup.procs: No such file or directory
,09-02 11:36:49.306  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 11:36:49.314  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 11:36:49.344  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 11:36:49.348  6385  6385 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-02 11:36:49.352  6385  6385 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-02 11:36:49.352  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:49.364  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-02 11:36:49.364  6336  6336 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 11:36:49.364  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:49.370  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:49.379  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:49.388  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:49.389  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:49.391  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 11:36:49.459  1036  1941 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6428 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 11:36:49.534  3780  3861 D bt_hci_bdroid: cleanup
09-02 11:36:49.534  3780  3962 I bt_lpm  : LPM is already off!!!
,09-02 11:36:49.535  3780  4108 I bt_userial_mct: exiting userial_read_thread
09-02 11:36:49.535  3780  4108 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 11:36:49.535  3780  3959 W bt-btif : ag scb idx 1 not allocated
09-02 11:36:49.535  3780  3959 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:36:49.535  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:36:49.536  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:36:49.536  3780  3959 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:36:49.536  3780  3959 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:36:49.536  3780  3959 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:36:49.536  3780  3959 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 11:36:49.536  3780  3861 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 11:36:49.536  3780  3962 I bt_vendor: hw_epilog_process
09-02 11:36:49.536  3780  3861 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 11:36:49.536  3780  3861 D bt_userial_mct: userial_close
09-02 11:36:49.536  3780  3861 E bt_userial_mct: pthread_join() FAILED result:3
09-02 11:36:49.536  3780  3861 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 11:36:49.546  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 11:36:49.551  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 11:36:49.558  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:49.583  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:36:49.583  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 11:36:49.583  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:36:49.584  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-02 11:36:49.587  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:36:49.591  6428  6448 W FormManager: Network not available. Please check & try again.
09-02 11:36:49.597  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:36:49.597  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,09-02 11:36:49.598  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:36:49.598  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:36:49.598  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,09-02 11:36:49.598  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 11:36:49.604  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 11:36:49.604  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 11:36:49.606  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:36:49.610  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:36:49.611  6428  6449 V FormManager: Network unavailable.
09-02 11:36:49.620  6336  6336 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 11:36:49.620  6336  6336 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 11:36:49.620  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 11:36:49.623  3780  3861 D bt_hci_bdroid: set_power 0
09-02 11:36:49.623  3780  3861 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 11:36:49.623  3780  3861 I bt_vendor: bluetooth satus is on
09-02 11:36:49.623  3780  3861 I bt_vendor: bt-vendor : resetting BT status
09-02 11:36:49.623  3780  3861 I bt_vendor: Starting hciattach daemon
09-02 11:36:49.623  3780  3861 I bt_vendor: try to set false
09-02 11:36:49.625  3780  3861 I bt_vendor: Starting hciattach daemon
09-02 11:36:49.625  3780  3861 I bt_vendor: try to set false
09-02 11:36:49.626  3780  3861 I bt_vendor: cleanup
09-02 11:36:49.626  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 11:36:49.626  3780  3959 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 11:36:49.627  3780  3861 I GKI_LINUX: GKI_exit_task 0 done
09-02 11:36:49.627  3780  3861 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 11:36:49.628  3780  3854 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 11:36:49.629  6428  6449 V FormManager: Network unavailable.
09-02 11:36:49.632  3780  3780 D HeadsetService: Received stop request...Stopping profile...
09-02 11:36:49.633  3780  3780 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 11:36:49.633  3780  3780 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:36:49.633  3780  3890 D HeadsetStateMachine: Exit Disconnected: -1
,09-02 11:36:49.642  3780  3854 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 11:36:49.638  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0ca1
,09-02 11:36:49.652  1036  1036 D BluetoothHeadset: Proxy object disconnected
09-02 11:36:49.652  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 11:36:49.653  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-02 11:36:49.653  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-02 11:36:49.653  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-02 11:36:49.654  3780  3780 D A2dpService: Received stop request...Stopping profile...
09-02 11:36:49.655  3780  3780 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 11:36:49.657  3780  3780 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 11:36:49.657  3780  3780 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:36:49.657  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0ca1
09-02 11:36:49.657  3780  3921 D A2dpStateMachine: Exit Disconnected: -1
09-02 11:36:49.663  1036  1036 D BluetoothA2dp: Proxy object disconnected
09-02 11:36:49.663  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 11:36:49.666  3780  3780 D HidService: Received stop request...Stopping profile...
09-02 11:36:49.666  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0ca1
09-02 11:36:49.667  4241  6459 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 11:36:49.667  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:49.668  3780  3780 D HealthService: Received stop request...Stopping profile...
09-02 11:36:49.669  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0ca1
09-02 11:36:49.669  6319  6319 D BluetoothInputDevice: Proxy object disconnected
09-02 11:36:49.670  6319  6319 D HidProfile: Bluetooth service disconnected
09-02 11:36:49.670  4241  6459 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 11:36:49.671  4241  6452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 11:36:49.676  3780  3780 D PanService: Received stop request...Stopping profile...
,09-02 11:36:49.679  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0ca1
,09-02 11:36:49.680  6319  6319 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 11:36:49.680  6319  6319 D PanProfile: Bluetooth service disconnected
09-02 11:36:49.680  3780  3780 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 11:36:49.681  6428  6457 W FormManager: Network not available. Please check & try again.
09-02 11:36:49.681  3780  3780 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 11:36:49.681  3780  3780 D BtGatt.GattService: stop()
09-02 11:36:49.681  3780  3780 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 11:36:49.682  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0ca1
09-02 11:36:49.684  3780  3780 D BluetoothMapService: Received stop request...Stopping profile...
09-02 11:36:49.684  3780  3780 D BluetoothMapService: stop()
09-02 11:36:49.685  3780  3780 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 11:36:49.685  3780  3780 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 11:36:49.685  6428  6458 V FormManager: Network unavailable.
09-02 11:36:49.686  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0ca1
09-02 11:36:49.687  6319  6319 D BluetoothMap: Proxy object disconnected
09-02 11:36:49.687  6319  6319 D MapProfile: Bluetooth service disconnected
09-02 11:36:49.687  3780  3780 D HeadsetStateMachine: Unbinding service...
,09-02 11:36:49.690  3780  3780 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 11:36:49.690  3780  3780 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 11:36:49.691  3780  3780 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 11:36:49.691  3780  3780 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 11:36:49.691  3780  3780 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 11:36:49.691  3780  3780 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:36:49.691  3780  3780 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 11:36:49.691  3780  3780 I BluetoothA2dpServiceJni: cleanupNative
09-02 11:36:49.691  3780  3922 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 11:36:49.692  3780  3780 I GKI_LINUX: GKI_exit_task 2 done
09-02 11:36:49.692  3780  3780 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 11:36:49.692  3780  3780 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 11:36:49.692  3780  3780 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 11:36:49.692  3780  3780 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 11:36:49.692  3780  3780 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 11:36:49.692  3780  3780 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 11:36:49.693  3780  3780 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 11:36:49.693  3780  3780 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 11:36:49.695  3780  3780 V BluetoothMapService: Handler(): got msg=4
09-02 11:36:49.695  3780  3780 D BluetoothMapService: MAP Service closeService in
09-02 11:36:49.695  3780  3780 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 11:36:49.695  3780  3780 V BluetoothMapService: MAP Service closeService out
09-02 11:36:49.695  3780  3780 D BluetoothMapService: cleanup()
09-02 11:36:49.695  3780  3780 D BluetoothMapService: MAP Service closeService in
09-02 11:36:49.695  3780  3780 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 11:36:49.696  3780  3780 V BluetoothMapService: MAP Service closeService out
09-02 11:36:49.696  3780  3854 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 11:36:49.696  3780  3854 D BluetoothAdapterProperties: Setting state to 10
09-02 11:36:49.696  3780  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 11:36:49.696  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:36:49.696  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 11:36:49.696  3780  3854 I BluetoothAdapterState: Entering OffState
09-02 11:36:49.696  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-02 11:36:49.696  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:36:49.698  6319  6334 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 11:36:49.701  1851  4341 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:36:49.703  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 11:36:49.703  6428  6458 V FormManager: Network unavailable.
09-02 11:36:49.703  6319  6335 D BluetoothMap: onBluetoothStateChange: up=false
09-02 11:36:49.704  6385  6385 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-02 11:36:49.704  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 11:36:49.705  6385  6385 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-02 11:36:49.707  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:36:49.707  6319  6334 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 11:36:49.708  6319  6335 D BluetoothPan: onBluetoothStateChange on: false
09-02 11:36:49.708  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:36:49.709  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 11:36:49.710  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 11:36:49.712  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 11:36:49.712  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 11:36:49.713  1036  1885 I ActivityManager: Killing 5827:com.android.contacts/u0a19 (adj 15): empty #17
09-02 11:36:49.713  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@15885919 mBinding = false
09-02 11:36:49.714  1036  1118 D BluetoothManagerService: Sending unbind request.
09-02 11:36:49.747  6385  6385 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:36:49.747  6385  6385 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 11:36:49.756  6385  6385 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-02 11:36:49.757  6385  6385 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-02 11:36:49.757  6385  6385 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-02 11:36:49.757  6385  6385 V SoundPool: doLoad: loading sample sampleID=1
09-02 11:36:49.758  6385  6385 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 11:36:49.760  6385  6470 V SoundPool: Start decode
09-02 11:36:49.760  6385  6470 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-02 11:36:49.761   319  1382 V MediaPlayerService: decode(22, 10857164, 17813)
09-02 11:36:49.761   319  1382 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-02 11:36:49.761   319  1382 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-02 11:36:49.761   319  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-02 11:36:49.761   319  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-02 11:36:49.762   319  1382 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-02 11:36:49.762   319  1382 V MediaPlayerService: player type = 3
09-02 11:36:49.762   319  1382 V AwesomePlayer: AwesomePlayer create()
09-02 11:36:49.762   319  1382 V AwesomePlayer: reset_l() 
,09-02 11:36:49.762   319  1382 V AwesomePlayer: cancelPlayerEvents
09-02 11:36:49.762   319  1382 V AwesomePlayer: setAudioSink() 
09-02 11:36:49.762   319  1382 V AwesomePlayer: reset_l() 
09-02 11:36:49.762   319  1382 V AudioCache: notify(0xb100c280, 8, 0, 0)
09-02 11:36:49.762   319  1382 V AudioCache: ignored
09-02 11:36:49.762   319  1382 V AwesomePlayer: cancelPlayerEvents
09-02 11:36:49.762   319  1382 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-02 11:36:49.762  1036  1626 W libprocessgroup: failed to open /acct/uid_10019/pid_5827/cgroup.procs: No such file or directory
09-02 11:36:49.762   319  1382 V AwesomePlayer: setDataSource_l dataSource
09-02 11:36:49.762   319  1382 V LGParserOSAL: SniffLGParser start
09-02 11:36:49.762  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 11:36:49.762   319  1382 V LGParserOSAL: MainType:5, SubType=0
09-02 11:36:49.762   319  1382 V LGParserOSAL: #### check Mime : application/ogg
09-02 11:36:49.762   319  1382 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-02 11:36:49.762   319  1382 E MediaExtractor: Use LGExtractor :application/ogg 
09-02 11:36:49.769  6116  6116 D UEI.SmartControl: QS Service created
,09-02 11:36:49.771  6385  6385 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-02 11:36:49.774  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 11:36:49.776  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:49.776  1942  2110 D LGBluetoothAPIService: Message: 2
09-02 11:36:49.777  1942  2110 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1e292aca mBinding = false
09-02 11:36:49.777  1942  2110 D LGBluetoothAPIService: Sending unbind request.
09-02 11:36:49.778  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:49.779  3780  3861 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 11:36:49.780  3780  3780 I GKI_LINUX: GKI_exit_task 1 done
09-02 11:36:49.780  3780  3780 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 11:36:49.780  3780  3780 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 11:36:49.781  3780  3780 I art     : --- WEIRD: removing null entry 246
09-02 11:36:49.781  3780  3780 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-02 11:36:49.781  3780  3780 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 11:36:49.782  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:49.784  6319  6319 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 11:36:49.785  6319  6319 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 11:36:49.785  6319  6319 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 11:36:49.787  6319  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 11:36:49.789  3780  3780 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 11:36:49.791  3780  3780 I art     : System.exit called, status: 0
09-02 11:36:49.791  3780  3780 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 11:36:49.796  1601  1601 D BluetoothAdapter: 210567513: getState() :  mService = null. Returning STATE_OFF
09-02 11:36:49.796  1601  1601 D BluetoothAdapter: 210567513: getState() :  mService = null. Returning STATE_OFF
09-02 11:36:49.800  6319  6319 D DockEventReceiver: finishStartingService: stopping service
09-02 11:36:49.804  6385  6385 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 11:36:49.804  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 11:36:49.809  6116  6116 I UEI.SmartControl: Service initServices...
09-02 11:36:49.810  6116  6116 D UEI.SmartControl: QS start get config
,09-02 11:36:49.810   319  1383 V AudioFlinger: 3780 died, releasing its sessions
09-02 11:36:49.810   319  1383 V AudioFlinger:  pid 1851 @ 0
09-02 11:36:49.810   319  1383 V AudioFlinger:  pid 3306 @ 1
09-02 11:36:49.810   319  1383 V AudioFlinger:  pid 3306 @ 2
,09-02 11:36:49.811  6319  6319 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 11:36:49.818   319  1382 V LGParserOSAL: supported mime: application/ogg
09-02 11:36:49.818   319  1382 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-02 11:36:49.818   319  1382 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-02 11:36:49.818   319  1382 V AwesomePlayer: mBitrate = -1 bits/sec
09-02 11:36:49.818   319  1382 V AwesomePlayer: AudioTrack Setting
09-02 11:36:49.818   319  1382 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-02 11:36:49.818   319  1382 V AwesomePlayer: setAudioSource() 
09-02 11:36:49.818   319  1382 V MediaPlayerService: prepare
09-02 11:36:49.818   319  1382 V AwesomePlayer: prepareAsync_l() 
09-02 11:36:49.819   319  1382 V MediaPlayerService: wait for prepare
09-02 11:36:49.819   319  6474 V AwesomePlayer: onPrepareAsyncEvent() 
09-02 11:36:49.819   319  6474 V AwesomePlayer: initAudioDecoder() 
09-02 11:36:49.819   319  6474 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,09-02 11:36:49.819   319  6474 V AudioSystem: isOffloadSupported()
09-02 11:36:49.819   319  6474 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 11:36:49.819   319  6474 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 11:36:49.819   319  6474 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 11:36:49.819   319  6474 V AwesomePlayer: getUseOffload() = 0 
09-02 11:36:49.819   319  6474 V OMXCodec: OMXCodec::Create
09-02 11:36:49.819   319  6474 V OMXCodec: findMatchingCodecs()
09-02 11:36:49.819   319  6474 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-02 11:36:49.819   319  6474 V OMXCodec: matchingCodecs.size()=1
09-02 11:36:49.819   319  6474 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-02 11:36:49.820   319  6474 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-02 11:36:49.821   319  6474 V LGCodecAdapter: LG Codec Adapter start
09-02 11:36:49.821   319  6474 V OMXCodec: OMXCodec Createtor
09-02 11:36:49.821   319  6474 V OMXCodec: setComponentRole
09-02 11:36:49.821   319  6474 V OMXCodec: configureCodec protected=0
09-02 11:36:49.821   319  6474 V LGCodecAdapter: called getLGCodecSpecificData
09-02 11:36:49.821   319  6474 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-02 11:36:49.821   319  6474 V LGCodecOSAL: Called LGconfigureCodecMETA
09-02 11:36:49.821   319  6474 V LGCodecOSAL: Called LGconfigureCodecMSG
09-02 11:36:49.821   319  6474 V LGCodecOSAL: Not support LGCodec
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 11:36:49.821   319  6474 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-02 11:36:49.821   319  6474 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-02 11:36:49.821   319  6474 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-02 11:36:49.821   319  6474 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 11:36:49.821   319  6474 V AudioSystem: isOffloadSupported()
09-02 11:36:49.821   319  6474 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 11:36:49.821   319  6474 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-02 11:36:49.821   319  6474 V OMXCodec: init()
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
,09-02 11:36:49.821   319  6474 V OMXCodec: allocateBuffers
09-02 11:36:49.821   319  6474 V OMXCodec: allocateBuffersOnPort portIndex=0
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on input port
,09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on input port
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on input port
09-02 11:36:49.821   319  6474 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 11:36:49.821   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,09-02 11:36:49.822   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17820b0 on output port
09-02 11:36:49.822   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1782150 on output port
09-02 11:36:49.822   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17821a0 on output port
09-02 11:36:49.822   319  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17821f0 on output port
09-02 11:36:49.822   319  6474 V OMXCodec: init() mAsyncCompletion wait!!! 
09-02 11:36:49.822   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 11:36:49.822   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 11:36:49.822   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-02 11:36:49.822   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-02 11:36:49.822   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-02 11:36:49.822   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-02 11:36:49.822   319  6474 V OMXCodec: init() mAsyncCompletion wait free! 
09-02 11:36:49.822   319  6474 V AwesomePlayer: finishAsyncPrepare_l() 
09-02 11:36:49.822   319  6474 V AudioCache: notify(0xb100c280, 5, 0, 0)
09-02 11:36:49.822   319  6474 V AudioCache: ignored
09-02 11:36:49.822   319  6474 V AudioCache: notify(0xb100c280, 1, 0, 0)
09-02 11:36:49.822   319  6474 V AudioCache: prepared
09-02 11:36:49.822   319  1382 V AudioCache: wait - success
09-02 11:36:49.822   319  1382 V MediaPlayerService: start
09-02 11:36:49.822   319  1382 V AwesomePlayer: play_l() 
09-02 11:36:49.822   319  1382 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-02 11:36:49.822   319  1382 V AwesomePlayer: createAudioPlayer_l
09-02 11:36:49.822   319  1382 V AwesomePlayer: seekAudioIfNecessary_l() 
09-02 11:36:49.822   319  1382 V AwesomePlayer: startAudioPlayer_l() 
09-02 11:36:49.822   319  1382 D AudioPlayer: start of Playback, useOffload 0
09-02 11:36:49.822   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 11:36:49.822   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 11:36:49.823  6385  6385 V LGMDMManager: Create singleton instance
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977439920
09-02 11:36:49.825   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977440080
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977440160
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977440240
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 11:36:49.826   319 , 6476 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-02 11:36:49.826   319  6476 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17821a0 on output port
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1782150 on output port
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17820b0 on output port
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on output port
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-02 11:36:49.826   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-02 11:36:49.827   319  1382 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-02 11:36:49.827   319  1382 V AudioCache: notify(0xb100c280, 6, 0, 0)
09-02 11:36:49.827   319  1382 V AudioCache: ignored
09-02 11:36:49.827   319  1382 V MediaPlayerService: wait for playback complete
09-02 11:36:49.828   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.828   319  6477 V AudioCache: memcpy(0xac300000, 0xb57c6000, 4096)
09-02 11:36:49.832   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.832   319  6477 V AudioCache: memcpy(0xac301000, 0xb57c6000, 4096)
09-02 11:36:49.833   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.833   319  6477 V AudioCache: memcpy(0xac302000, 0xb57c6000, 4096)
09-02 11:36:49.833   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.833   319  6477 V AudioCache: memcpy(0xac303000, 0xb57c6000, 4096)
09-02 11:36:49.834   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.834   319  6477 V AudioCache: memcpy(0xac304000, 0xb57c6000, 4096)
09-02 11:36:49.834   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.834   319  6477 V AudioCache: memcpy(0xac305000, 0xb57c6000, 4096)
09-02 11:36:49.835   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.835   319  6477 V AudioCache: memcpy(0xac306000, 0xb57c6000, 4096)
09-02 11:36:49.835   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.835   319  6477 V AudioCache: memcpy(0xac307000, 0xb57c6000, 4096)
09-02 11:36:49.836   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.836   319  6477 V AudioCache: memcpy(0xac308000, 0xb57c6000, 4096)
09-02 11:36:49.836   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.836   319  6477 V AudioCache: memcpy(0xac309000, 0xb57c6000, 4096)
09-02 11:36:49.837   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.837   319  6477 V AudioCache: memcpy(0xac30a000, 0xb57c6000, 4096)
09-02 11:36:49.837   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.837   319  6477 V AudioCache: memcpy(0xac30b000, 0xb57c6000, 4096)
09-02 11:36:49.838   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.838   319  6477 V AudioCache: memcpy(0xac30c000, 0xb57c6000, 4096)
,09-02 11:36:49.838   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.838   319  6477 V AudioCache: memcpy(0xac30d000, 0xb57c6000, 4096)
09-02 11:36:49.839   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.839   319  6477 V AudioCache: memcpy(0xac30e000, 0xb57c6000, 4096)
09-02 11:36:49.839   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.839   319  6477 V AudioCache: memcpy(0xac30f000, 0xb57c6000, 4096)
09-02 11:36:49.839   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.839   319  6477 V AudioCache: memcpy(0xac310000, 0xb57c6000, 4096)
09-02 11:36:49.840   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.840   319  6477 V AudioCache: memcpy(0xac311000, 0xb57c6000, 4096)
,09-02 11:36:49.841   319  6477 V AudioCache: write(0xb57c6000, 4096),
09-02 11:36:49.841   319  6477 V AudioCache: memcpy(0xac312000, 0xb57c6000, 4096)
09-02 11:36:49.841   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.841   319  6477 V AudioCache: memcpy(0xac313000, 0xb57c6000, 4096)
09-02 11:36:49.842   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.842   319  6477 V AudioCache: memcpy(0xac314000, 0xb57c6000, 4096)
,09-02 11:36:49.842   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.842   319  6477 V AudioCache: memcpy(0xac315000, 0xb57c6000, 4096)
09-02 11:36:49.842   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.843   319  6477 V AudioCache: memcpy(0xac316000, 0xb57c6000, 4096)
09-02 11:36:49.843   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.843   319  6477 V AudioCache: memcpy(0xac317000, 0xb57c6000, 4096),
09-02 11:36:49.844   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.844   319  6477 V AudioCache: memcpy(0xac318000, 0xb57c6000, 4096)
09-02 11:36:49.844   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.844   319  6477 V AudioCache: memcpy(0xac319000, 0xb57c6000, 4096)
09-02 11:36:49.845   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.845   319  6477 V AudioCache: memcpy(0xac31a000, 0xb57c6000, 4096)
,09-02 11:36:49.846   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.846   319  6477 V AudioCache: memcpy(0xac31b000, 0xb57c6000, 4096)
09-02 11:36:49.847   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.847   319  6477 V AudioCache: memcpy(0xac31c000, 0xb57c6000, 4096)
09-02 11:36:49.847   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.847   319  6477 V AudioCache: memcpy(0xac31d000, 0xb57c6000, 4096)
09-02 11:36:49.848   319  6477 V AudioCache: write(0xb57c6000, 4096)
,09-02 11:36:49.848   319  6477 V AudioCache: memcpy(0xac31e000, 0xb57c6000, 4096)
09-02 11:36:49.849   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.849   319  6477 V AudioCache: memcpy(0xac31f000, 0xb57c6000, 4096)
09-02 11:36:49.849   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.849   319  6477 V AudioCache: memcpy(0xac320000, 0xb57c6000, 4096)
09-02 11:36:49.850   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.850   319  6477 V AudioCache: memcpy(0xac321000, 0xb57c6000, 4096)
,09-02 11:36:49.850   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.850   319  6477 V AudioCache: memcpy(0xac322000, 0xb57c6000, 4096)
09-02 11:36:49.851   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.851   319  6477 V AudioCache: memcpy(0xac323000, 0xb57c6000, 4096)
09-02 11:36:49.852   319  6477 V AudioCache: write(0xb57c6000, 4096)
,09-02 11:36:49.852   319  6477 V AudioCache: memcpy(0xac324000, 0xb57c6000, 4096),
09-02 11:36:49.852   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.852   319  6477 V AudioCache: memcpy(0xac325000, 0xb57c6000, 4096)
09-02 11:36:49.854   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.854   319  6477 V AudioCache: memcpy(0xac326000, 0xb57c6000, 4096)
09-02 11:36:49.854   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.854   319  6477 V AudioCache: memcpy(0xac327000, 0xb57c6000, 4096)
,09-02 11:36:49.855   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.855   319  6477 V AudioCache: memcpy(0xac328000, 0xb57c6000, 4096)
09-02 11:36:49.856   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.856   319  6477 V AudioCache: memcpy(0xac329000, 0xb57c6000, 4096)
09-02 11:36:49.857   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.857   319  6477 V AudioCache: memcpy(0xac32a000, 0xb57c6000, 4096)
09-02 11:36:49.857   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.857   319  6477 V AudioCache: memcpy(0xac32b000, 0xb57c6000, 4096)
,09-02 11:36:49.858   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.858   319  6477 V AudioCache: memcpy(0xac32c000, 0xb57c6000, 4096)
09-02 11:36:49.858   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.858   319  6477 V AudioCache: memcpy(0xac32d000, 0xb57c6000, 4096)
09-02 11:36:49.859   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.859   319  6477 V AudioCache: memcpy(0xac32e000, 0xb57c6000, 4096)
09-02 11:36:49.860   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.860   319  6477 V AudioCache: memcpy(0xac32f000, 0xb57c6000, 4096)
,09-02 11:36:49.860   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.860   319  6477 V AudioCache: memcpy(0xac330000, 0xb57c6000, 4096)
09-02 11:36:49.861   319  6477 V AudioCache: write(0xb57c6000, 4096)
09-02 11:36:49.861   319  6477 V AudioCache: memcpy(0xac331000, 0xb57c6000, 4096)
09-02 11:36:49.861   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-02 11:36:49.861   319  6477 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-02 11:36:49.861   319  6477 V AwesomePlayer: postAudioEOS() 
09-02 11:36:49.861   319  6477 V AudioCache: write(0xb57c6000, 280)
09-02 11:36:49.861   319  6477 V AudioCache: memcpy(0xac332000, 0xb57c6000, 280)
09-02 11:36:49.863   319  6474 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-02 11:36:49.863   319  6474 V AwesomePlayer: onStreamDone
09-02 11:36:49.863   319  6474 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-02 11:36:49.863   319  6474 V AudioCache: notify(0xb100c280, 2, 0, 0)
09-02 11:36:49.863   319  6474 V AudioCache: playback complete
09-02 11:36:49.863   319  6474 V AwesomePlayer: pause_l() 
09-02 11:36:49.863   319  1382 V AudioCache: wait - success
09-02 11:36:49.863   319  6474 V AudioCache: notify(0xb100c280, 7, 0, 0)
09-02 11:36:49.863   319  6474 V AudioCache: ignored
09-02 11:36:49.863   319  1382 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-02 11:36:49.863   319  6474 V AwesomePlayer: cancelPlayerEvents
09-02 11:36:49.863   319  6474 D AudioPlayer: Pause Playback at 1068125
09-02 11:36:49.864   319  1382 V AwesomePlayer: reset_l() 
09-02 11:36:49.864   319  1382 V AudioCache: notify(0xb100c280, 8, 0, 0)
09-02 11:36:49.864   319  1382 V AudioCache: ignored
09-02 11:36:49.864   319  1382 V AwesomePlayer: cancelPlayerEvents
09-02 11:36:49.864   319  1382 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-02 11:36:49.864   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-02 11:36:49.864   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-02 11:36:49.864   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-02 11:36:49.864   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 11:36:49.864   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 11:36:49.864   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 11:36:49.864   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-02 11:36:49.864   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 0
09-02 11:36:49.864   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-02 11:36:49.864   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 0
09-02 11:36:49.864   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 0
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb17820b0 on port 1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1782150 on port 1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb17821a0 on port 1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-02 11:36:49.865   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 11:36:49.865   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-02 11:36:49.865   319  6476 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-02 11:36:49.865   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 11:36:49.865   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-02 11:36:49.865   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-02 11:36:49.866   319  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-02 11:36:49.866   319  1382 D AudioPlayer: AudioPlayer releasing audio source
,09-02 11:36:49.866   319  1382 D AudioPlayer: AudioPlayer done releasing audio source
09-02 11:36:49.866   319  1382 V AwesomePlayer: reset_l() 
09-02 11:36:49.866   319  1382 V AwesomePlayer: cancelPlayerEvents
09-02 11:36:49.866   319  1382 V AwesomePlayer: ~AwesomePlayer call
09-02 11:36:49.866   319  1382 V AwesomePlayer: reset_l() 
09-02 11:36:49.866   319  1382 V AwesomePlayer: cancelPlayerEvents
09-02 11:36:49.867  6385  6470 V SoundPool: close(31)
09-02 11:36:49.867  6385  6470 V SoundPool: pointer = 0x9fffe000, size = 205080, sampleRate = 48000, numChannels = 2
09-02 11:36:49.883  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 11:36:49.884  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-02 11:36:49.893  1036  1051 I ActivityManager: Process com.android.bluetooth (pid 3780) has died
09-02 11:36:49.893  1036  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-02 11:36:49.896  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6855
09-02 11:36:49.896  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:36:49.904  6319  6319 D BluetoothPermissionRequest: onReceive
09-02 11:36:49.905  6319  6319 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 11:36:49.905  6319  6319 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-02 11:36:49.908  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:36:49.954  1036  1885 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6478 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 11:36:50.003  6478  6478 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 11:36:50.003  6478  6478 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 11:36:50.004  6478  6478 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 11:36:50.005  6478  6478 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 11:36:50.022  6478  6478 D BluetoothAdapterApp: Loading JNI Library
,09-02 11:36:50.057  6478  6478 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@25cc7fee Instance Count = 1
,09-02 11:36:50.064  6478  6478 D BluetoothAdapterApp: onCreate
09-02 11:36:50.087  6478  6478 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 11:36:50.087  6478  6478 D ProfileConfigQcom: Adding HeadsetService
09-02 11:36:50.088  6478  6478 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 11:36:50.088  6478  6478 D ProfileConfigQcom: Adding A2dpService
09-02 11:36:50.088  6478  6478 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 11:36:50.088  6478  6478 D ProfileConfigQcom: Adding HidService
09-02 11:36:50.088  6478  6478 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 11:36:50.088  6478  6478 D ProfileConfigQcom: Adding HealthService
09-02 11:36:50.089  6478  6478 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-02 11:36:50.090  6478  6478 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 11:36:50.090  6478  6478 D ProfileConfigQcom: Adding PanService
09-02 11:36:50.090  6478  6478 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 11:36:50.090  6478  6478 D ProfileConfigQcom: Adding GattService
09-02 11:36:50.091  6478  6478 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 11:36:50.091  6478  6478 D ProfileConfigQcom: Adding BluetoothMapService
09-02 11:36:50.091  6478  6478 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 11:36:50.093  6478  6478 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-02 11:36:50.100  6319  6319 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-02 11:36:50.102  6478  6478 V LGMDMManagerInternal: Create singleton instance
09-02 11:36:50.199  6116  6116 I UEI.SmartControl: Supports setup maps: true
,09-02 11:36:50.209  6478  6478 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:50.212  6116  6116 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 11:36:50.212  6116  6116 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 11:36:50.212  6116  6116 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 11:36:50.212  6116  6116 I UEI.SmartControl: ### init IR Blaster...
09-02 11:36:50.213  6478  6478 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:36:50.214  6478  6478 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-02 11:36:50.214  6478  6478 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 11:36:50.216  6478  6478 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:50.216  6478  6478 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 11:36:50.224  6116  6116 D serial_port: Configuring serial port
09-02 11:36:50.225  6116  6116 E UEI.SmartControl: UEIBLaster setting for 616
09-02 11:36:50.225  6116  6116 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 11:36:50.225  6116  6116 I UEI.SmartControl: configuring settings for MAXQ616
09-02 11:36:50.225  6116  6116 I UEI.SmartControl: Get version...
09-02 11:36:50.226  6402  6402 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-02 11:36:50.243  6116  6500 D UEI.SmartControl: serial port data available: 21
,09-02 11:36:50.269  6116  6116 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 11:36:50.269  6116  6116 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 11:36:50.269  6116  6116 I UEI.SmartControl: QS saving settings...
09-02 11:36:50.271  6116  6116 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 11:36:50.288  6116  6500 D UEI.SmartControl: serial port data available: 4
,09-02 11:36:50.320  6116  6503 I UEI.SmartControl: Device manager: loading config....
,09-02 11:36:50.321  6116  6503 D UEI.SmartControl: ----------- loading internal config...
,09-02 11:36:50.322  6116  6116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-02 11:36:50.327  6116  6116 E UEI.SmartControl: Services init done
09-02 11:36:50.327  6116  6116 D UEI.SmartControl: QS Service init finished
09-02 11:36:50.329  6116  6116 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 11:36:50.329  6116  6116 D UEI.SmartControl: QS Service version code: 201091
09-02 11:36:50.330  6116  6116 D UEI.SmartControl: Service requested: Control
09-02 11:36:50.336  6116  6116 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-02 11:36:50.336  6116  6503 E UEI.SmartControl: Loading SETTINGS...
09-02 11:36:50.339  6385  6385 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-02 11:36:50.340  6116  6131 I UEI.SmartControl: ------ IControl API: 11
09-02 11:36:50.341  6116  6131 D UEI.SmartControl: File observer start...
09-02 11:36:50.341  6116  6116 D UEI.SmartControl: Internal service binding...
09-02 11:36:50.342  6116  6131 E UEI.SmartControl: IR Port is disabled: false
09-02 11:36:50.342  6116  6131 D UEI.SmartControl: Starting file observer...
09-02 11:36:50.345  6116  6131 I UEI.SmartControl: Registering callback...
09-02 11:36:50.346  6116  6132 I UEI.SmartControl: ------ IControl API: 19
09-02 11:36:50.347  6116  6132 I UEI.SmartControl: Registering Services Ready callback...
09-02 11:36:50.350  6116  6503 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 11:36:50.360  6116  6502 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 11:36:50.361  6116  6502 D UEI.SmartControl: -----service ready thread exits
,09-02 11:36:50.362  6385  6401 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-02 11:36:50.363  6385  6468 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-02 11:36:50.364  6385  6468 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-02 11:36:50.366  6385  6385 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-02 11:36:50.367  6385  6385 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-02 11:36:50.367  6116  6131 I UEI.SmartControl: ------ IControl API: 8
09-02 11:36:50.371  6385  6385 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,09-02 11:36:50.372  6385  6385 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-02 11:36:50.372  6385  6385 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,09-02 11:36:50.374  6385  6385 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-02 11:36:50.375  6385  6385 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-02 11:36:50.375  6385  6385 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-02 11:36:50.378  6385  6385 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-02 11:36:50.380  6385  6385 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-02 11:36:50.381  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 11:36:50.381  6385  6385 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 11:36:50.382  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 11:36:50.383  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 11:36:50.384  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-02 11:36:50.384  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-02 11:36:50.386  6385  6385 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472809010385]
09-02 11:36:50.389  6385  6385 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-02 11:36:50.392  1036  1051 I ActivityManager: Killing 5883:com.android.gallery3d/u0a27 (adj 15): empty #17
09-02 11:36:50.412  6385  6505 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-02 11:36:50.454  1036  1051 I ActivityManager: Killing 5854:com.lge.email/u0a23 (adj 15): empty #18
,09-02 11:36:50.556  1036  2013 W libprocessgroup: failed to open /acct/uid_10027/pid_5883/cgroup.procs: No such file or directory
,09-02 11:36:50.576  1036  1626 W libprocessgroup: failed to open /acct/uid_10023/pid_5854/cgroup.procs: No such file or directory
09-02 11:36:50.579  6385  6385 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-02 11:36:50.582  6385  6385 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 11:36:50.583  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-02 11:36:50.584  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-02 11:36:50.585  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-02 11:36:50.585  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-02 11:36:50.585  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-02 11:36:50.595  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-02 11:36:51.570  1036  1903 D WifiServiceImplEx: setWifiEnabled: true pid=6204, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 11:36:51.572  1036  1903 D WifiService: setWifiEnabled: true pid=6204, uid=10118
09-02 11:36:51.572  1036  1903 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:36:51.601  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:36:51.601  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:36:51.601  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,09-02 11:36:51.605  1036  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 11:36:51.605  1036  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-02 11:36:51.608  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 11:36:51.608  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 11:36:51.608  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 11:36:51.608  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 11:36:51.608  1036  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 11:36:51.608  1036  1536 E WifiHW  : unknown target_country: EU , set to default
09-02 11:36:51.608  1036  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 11:36:51.608  1036  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 11:36:51.609  1036  1536 I WifiUtil: gEnableBmps=1
09-02 11:36:52.189  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-02 11:36:52.204   315   894 D SoftapController: Softap fwReload - Ok
,09-02 11:36:52.209  1036  1536 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (593ms)
09-02 11:36:52.216   315   894 D CommandListener: Setting iface cfg
09-02 11:36:52.216   315   894 D CommandListener: Trying to bring down wlan0
,09-02 11:36:52.224   315  6527 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 11:36:52.235  1036  1118 D Tethering: InitialState.processMessage what=4
09-02 11:36:52.235  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 11:36:52.237   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 11:36:52.244  1036  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 11:36:52.253  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-02 11:36:52.248  6528  6528 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:52.263  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:36:52.263  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:36:52.263  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 11:36:52.258  6528  6528 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 11:36:52.275  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:52.283  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-02 11:36:52.297  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:52.300  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:52.301  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-02 11:36:52.301  1036  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 11:36:52.301  1036  1536 D WifiMonitor: connecting to supplicant
09-02 11:36:52.309  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:36:52.309  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-02 11:36:52.314  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:36:52.314  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 11:36:52.316  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:36:52.317  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:36:52.318  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 11:36:52.318  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:36:52.318  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:36:52.318  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 11:36:52.318  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 11:36:52.319  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 11:36:52.325  6528  6528 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 11:36:52.328  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:36:52.328  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 11:36:52.328  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:36:52.328  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 11:36:52.329  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:36:52.329  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:36:52.329  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 11:36:52.329  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:36:52.329  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:36:52.330  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 11:36:52.330  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 11:36:52.337  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:52.340  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 11:36:52.347  6428  6547 W FormManager: Network not available. Please check & try again.
09-02 11:36:52.347  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:52.360  6528  6528 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 11:36:52.360  6528  6528 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-02 11:36:52.361  6428  6548 V FormManager: Network unavailable.
,09-02 11:36:52.364  6428  6548 V FormManager: Network unavailable.
09-02 11:36:52.466  6528  6528 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 11:36:52.486  6528  6528 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-02 11:36:52.492  6528  6528 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-02 11:36:52.495  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-02 11:36:52.495  6528  6528 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-02 11:36:52.496  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 11:36:52.497  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 11:36:52.498  1036  6550 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-02 11:36:52.498  1036  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 11:36:52.498  1036  6550 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 11:36:52.498  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 11:36:52.498  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 11:36:52.499  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 11:36:52.499  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 11:36:52.499  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 11:36:52.499  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 11:36:52.499  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:52.500  1036  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:52.502  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:52.503  1036  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:52.506  1036  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,09-02 11:36:52.506  1036  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 11:36:52.507  1036  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 11:36:52.508  1036  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 11:36:52.508  1036  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 11:36:52.509  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:36:52.509  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:36:52.509  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 11:36:52.510  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.511  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.511  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.511  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.511  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 11:36:52.512  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:52.513  1036  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 11:36:52.515  1942  1942 D WfdService: Waiting for WifiP2p enabling
09-02 11:36:52.515  1036  1536 D WifiNative-wlan0: SET update_config 1: returned true
09-02 11:36:52.515  1036  1536 D WifiConfigStore: Loading config and enabling all networks 
09-02 11:36:52.515  1036  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 11:36:52.516  1036  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 11:36:52.518  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:36:52.518  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:52.518  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:52.518  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:52.518  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:52.519  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 11:36:52.519  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:52.519  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:52.519  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:52.520  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:52.524  1036  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 11:36:52.530  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:52.534  1036  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 11:36:52.534  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 11:36:52.534  1036  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 11:36:52.535  1036  1536 D WifiStateMachine: enableVerboseLogging : level 2
09-02 11:36:52.535  1036  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-02 11:36:52.535  1036  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 11:36:52.535  1036  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 11:36:52.535  1036  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 11:36:52.536  1036  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 11:36:52.536  1036  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 11:36:52.536  1036  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 11:36:52.536  1036  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
,09-02 11:36:52.536  1036  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 11:36:52.537  1036  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 11:36:52.537  1036  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 11:36:52.537  1036  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,09-02 11:36:52.537  1036  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 11:36:52.538  1036  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 11:36:52.538  1036  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 11:36:52.538  1036  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-02 11:36:52.539  1036  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 11:36:52.539  1036  1536 D WifiNative-HAL: Setting external_sim to 1
09-02 11:36:52.539  1036  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 11:36:52.539  1036  1536 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 11:36:52.539  1036  1536 I WifiNative-HAL: startHal
09-02 11:36:52.539  1036  1536 D wifi    : setting scan oui 0xaf56f040
,09-02 11:36:52.539  1942  1942 D WfdsService: Supplicant Connection state is changed : true
09-02 11:36:52.540  1942  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 11:36:52.540  1942  2258 D WfdsService: Set the WFDS Monitor: true
,09-02 11:36:52.540  1942  2258 D WfdsMonitor: WfdsMonitorThread create
09-02 11:36:52.540  1036  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 11:36:52.540  1036  1536 I WifiNative-HAL: startHal
09-02 11:36:52.540  1036  1536 D wifi    : setting scan oui 0xaf56f040
,09-02 11:36:52.540  1942  2258 D WfdsMonitor: WFDS Monitor is created and started
09-02 11:36:52.540  1942  2258 D WfdsService: WiFi: Supplicant connection re-established
09-02 11:36:52.540  1036  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,09-02 11:36:52.540  1036  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 11:36:52.540  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 11:36:52.541  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 11:36:52.541  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true,
09-02 11:36:52.541  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 11:36:52.541  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 11:36:52.542  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,09-02 11:36:52.542  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 11:36:52.542  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 11:36:52.542  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 11:36:52.542  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,09-02 11:36:52.542  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 11:36:52.542  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 11:36:52.542  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 11:36:52.543  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-02 11:36:52.543  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 11:36:52.543  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 11:36:52.543  6528  6528 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 11:36:52.544  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,09-02 11:36:52.544  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 11:36:52.544  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 11:36:52.544  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 11:36:52.545  1036  1536 E WifiNative: : [188,071,343 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 11:36:52.545  1036  1536 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 11:36:52.545  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 11:36:52.545  1036  1536 D WifiNative-wlan0: RECONNECT: returned true
09-02 11:36:52.545  1036  1536 D WifiNative-wlan0: doString: [STATUS]
09-02 11:36:52.546  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,09-02 11:36:52.546  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 11:36:52.546  1036  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4,
09-02 11:36:52.546  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 1,
09-02 11:36:52.547  1942  6552 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 11:36:52.548  1942  6552 E CtrlSupplicant: Succeed to open control connection
09-02 11:36:52.548  1942  6552 E CtrlSupplicant: Succeed to open monitor connection
,09-02 11:36:52.549  1036  1536 D WifiNative-wlan0: SET ps 1: returned true
09-02 11:36:52.549  1036  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.550  1036  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 11:36:52.550  1036  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 11:36:52.551  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 11:36:52.551  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-02 11:36:52.551  1036  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.551  1036  1554 I WifiNative-HAL: startHal
09-02 11:36:52.551  1036  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf56f040
09-02 11:36:52.551  1036  1554 D wifi    : failed to get capabilities : -3
09-02 11:36:52.551  1036  1554 E WifiScanningService: could not get scan capabilities
09-02 11:36:52.552  1036  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.552   315   894 D CommandListener: Setting iface cfg
09-02 11:36:52.552   315   894 D CommandListener: Trying to bring up p2p0
09-02 11:36:52.552  1036  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 11:36:52.552  1036  1535 D LGWifiP2pService: P2pEnablingState
09-02 11:36:52.552  1036  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.552  1036  1535 D LGWifiP2pService: P2p socket connection successful
09-02 11:36:52.552  1036  1535 D LGWifiP2pService: P2pEnabledState
09-02 11:36:52.553  1942  6552 D WfdsMonitor: Supplicant connection established
09-02 11:36:52.553  1036  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 11:36:52.553  1036  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 11:36:52.553  1942  2258 D WfdsService: Connected to the supplicant for wfds
,09-02 11:36:52.554  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 11:36:52.554  1942  1942 D WfdsService: WifiP2pState is changed : true
09-02 11:36:52.554  1942  2258 D WfdsService: Receive the WFDS_ENABLE Method
09-02 11:36:52.555  1942  2258 D WfdsService: Set the WFDS Monitor: true
09-02 11:36:52.555  1942  2258 D WfdsService: Connected to the supplicant for wfds
09-02 11:36:52.555  1942  2258 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 11:36:52.555  6528  6528 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 11:36:52.555  1942  2258 D WfdsService: selectPreferredScanChannel [36]
09-02 11:36:52.555  1942  2258 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 11:36:52.555  1036  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 11:36:52.556  1036  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 11:36:52.556  1036  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 11:36:52.556  1036  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
,09-02 11:36:52.556  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=188083  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 11:36:52.557  1036  1535 D WifiNative-p2p0: SET device_name G3: returned true
09-02 11:36:52.557  1036  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 11:36:52.557  1036  1535 D LGWifiP2pService: before postfix = G3
09-02 11:36:52.557  1036  1535 D WifiServerServiceExt: postfix byte check : 2
09-02 11:36:52.557  1036  1535 D LGWifiP2pService: after postfix = G3
09-02 11:36:52.557  1036  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 11:36:52.557  1036  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 11:36:52.558  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=188085  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 11:36:52.557  1036  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 11:36:52.558  1036  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 11:36:52.558  1036  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 11:36:52.559  1036  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 11:36:52.559  1036  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
,09-02 11:36:52.559  1036  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 11:36:52.559  1036  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 11:36:52.560  1036  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 11:36:52.560  1036  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 11:36:52.560  6528  6528 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 11:36:52.561  1036  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 11:36:52.562  1036  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 11:36:52.562  1036  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 11:36:52.562  1036  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 11:36:52.562  6528  6528 E wpa_supplicant: disconnect_rssi_lvl: -100
,09-02 11:36:52.563  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 11:36:52.563  1942  1942 D WfdsService: isConnected: false
09-02 11:36:52.565  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:52.565  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 11:36:52.565  1036  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 11:36:52.565  1036  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-02 11:36:52.566  1036  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-02 11:36:52.566  1036  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 11:36:52.567  1036  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 11:36:52.567  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:52.568  1036  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 11:36:52.568  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 11:36:52.569  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 11:36:52.569  6528  6528 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:36:52.570  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.570  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.570  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 11:36:52.570  6528  6528 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 11:36:52.570  6528  6528 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.571  6528  6528 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.572  1942  6552 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.572  1942  6552 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.572  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 11:36:52.572  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:36:52.572  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:36:52.572  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-02 11:36:52.572  1036  6550 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.572  1036  6550 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.572  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.573  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.573  1036  6550 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.573  1036  6550 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.573  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.573  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.573  1036  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 11:36:52.574  1036  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 11:36:52.574  1036  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 11:36:52.574  1036  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 11:36:52.574  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 11:36:52.575  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 11:36:52.575  6528  6528 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 11:36:52.575  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 11:36:52.575  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 11:36:52.575  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 11:36:52.575  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 11:36:52.576  1036  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 11:36:52.576  1036  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 11:36:52.576  1036  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 11:36:52.576  1036  1536 D WifiNative-wlan0: doBoolean: SCAN
09-02 11:36:52.576  1036  1536 D WifiNative-wlan0: SCAN: returned false
09-02 11:36:52.577  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=188104  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 11:36:52.578  1036  1535 D LGWifiP2pService: DeviceAddress: 
09-02 11:36:52.578  1036  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 11:36:52.579  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 11:36:52.579  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 11:36:52.579  1942  1942 D WfdsService: Update P2p Interface State: 3
09-02 11:36:52.579  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=188106  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 11:36:52.580  1036  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 11:36:52.580  1036  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 11:36:52.580  1036  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-02 11:36:52.580  1036  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 11:36:52.580  1036  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 11:36:52.580  1036  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:36:52.581  1036  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:36:52.581  1036  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:36:52.581  1036  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 11:36:52.582  1036  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 11:36:52.582  1036  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:36:52.583  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.583  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:52.583  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 11:36:52.583  6428  6553 W FormManager: Network not available. Please check & try again.
09-02 11:36:52.586  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:52.586  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-02 11:36:52.586  6428  6554 V FormManager: Network unavailable.
09-02 11:36:52.584  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 11:36:52.586  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 11:36:52.588  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 11:36:52.588  6428  6554 V FormManager: Network unavailable.
09-02 11:36:52.589  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:52.589  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:52.590  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:36:52.590  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:52.592  1036  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-02 11:36:52.592  1036  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-02 11:36:52.593  1036  1535 D LGWifiP2pService: InactiveState
09-02 11:36:52.594  1036  1535 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.594  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.594  1036  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 11:36:52.594  6088  6088 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 11:36:52.594  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 11:36:52.595  6528  6528 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:36:52.595  1036  6550 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 11:36:52.595  1036  6550 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:36:52.595  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:36:52.595  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:36:52.595  6528  6528 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 11:36:52.595  6528  6528 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.596  1036  6550 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.596  1036  6550 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.596  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.596  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.596  6528  6528 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.596  1036  6550 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.596  1036  6550 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.597  1036  6550 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.597  1036  6550 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:36:52.597  6088  6088 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-02 11:36:52.597  1942  6552 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 11:36:52.597  1942  6552 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.597  1942  6552 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:36:52.598  1036  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  4241  6555 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.598  1036  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.599  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.599  1942  2258 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 11:36:52.599  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.599  1036  1535 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:52.599  1036  1036 E WifiServerServiceExt: No p2p device connected
09-02 11:36:52.602  4241  6556 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 11:36:52.602  6088  6088 V [BNRBootReceiver]: Boot Receiver Return
09-02 11:36:52.602  4241  6556 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 11:36:52.607  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:52.613  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:52.617  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:52.623  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:52.623  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:52.624  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 11:36:52.627  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 11:36:52.631  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:36:52.636  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:52.640  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 11:36:52.640  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:52.642  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 11:36:53.055  6528  6528 E wpa_supplicant: USIM:  scard_init function
09-02 11:36:53.056  6528  6528 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-02 11:36:53.066  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 11:36:53.066  1036  6550 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 11:36:53.067  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 11:36:53.067  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
09-02 11:36:53.067  1036  6550 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 11:36:53.067  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 11:36:53.067  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 11:36:53.070  1036  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-02 11:36:53.071  1036  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-02 11:36:53.073  1036  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,09-02 11:36:53.079  1036  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-02 11:36:53.079  1036  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 11:36:53.096  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=188623  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 11:36:53.102  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=188629  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 11:36:53.106  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:53.106  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:53.108  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.108  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.108  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 11:36:53.109  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:36:53.117  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:53.117  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-02 11:36:53.120  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-02 11:36:53.127  6319  6319 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 11:36:53.137  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 11:36:53.149  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:53.157  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:53.165  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 11:36:53.168  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:53.169  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:36:53.188  6528  6528 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 11:36:53.196  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 11:36:53.196  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 11:36:53.196  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 11:36:53.196  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 11:36:53.197  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:36:53.197  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:36:53.199  6528  6528 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 11:36:53.199  6528  6528 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 11:36:53.202  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=188728  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 11:36:53.202  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=188729  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 11:36:53.209  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:36:53.209  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:36:53.210  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 11:36:53.210  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 11:36:53.210  1036  6550 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 11:36:53.210  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 11:36:53.210  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 11:36:53.211  1036  6550 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 11:36:53.211  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:36:53.211  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:36:53.212  1036  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188739
,09-02 11:36:53.217  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 11:36:53.217  1036  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188744
09-02 11:36:53.218  1036  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188745
09-02 11:36:53.219  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188746
09-02 11:36:53.221  1036  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188747
09-02 11:36:53.221  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:36:53.221  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 11:36:53.221  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:36:53.221  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 11:36:53.221  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:36:53.222  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:36:53.222  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 11:36:53.222  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=188749  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 11:36:53.222  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:36:53.222  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:36:53.222  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 11:36:53.222  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 11:36:53.222  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 11:36:53.226  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:53.226  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 11:36:53.229  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:53.231  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.231  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.231  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 11:36:53.235  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:53.239  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=188765  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-02 11:36:53.241  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.241  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.241  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 11:36:53.248  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:53.248  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 11:36:53.249  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=188775  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 11:36:53.250  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:53.250  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:53.250  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=188776  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 11:36:53.251  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:53.251  1036  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=188778
09-02 11:36:53.252  1036  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=188779
,09-02 11:36:53.254  1036  1536 D WifiNative-wlan0: doString: [STATUS]
,09-02 11:36:53.255  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:36:53.255  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 11:36:53.261  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:36:53.261  1036  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 11:36:53.265  1036  1536 I WifiServiceExtension: setVHTCapabilityType  : false
,09-02 11:36:53.269  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:53.272  1036  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 11:36:53.272  1036  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-02 11:36:53.276  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:53.277  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:53.277  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 11:36:53.280  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:53.280  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:53.282  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.282  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.282  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 11:36:53.282  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:53.284  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:53.287  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.287  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:53.287  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-02 11:36:53.294  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:36:53.302  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:53.302  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:53.303  1036  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 11:36:53.304  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:53.304  1036  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:36:53.304  1036  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 11:36:53.304  1036  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 11:36:53.304  1036  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 11:36:53.305  1036  1543 D ConnectivityService: Got NetworkAgent Messenger
09-02 11:36:53.305  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 11:36:53.306  1036  1543 D ConnectivityService: NetworkAgent connected
09-02 11:36:53.308  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:53.309  1036  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 11:36:53.309  1036  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 11:36:53.310  1036  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 11:36:53.310  1036  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 11:36:53.310  1036  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 11:36:53.314  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:53.314  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:53.314  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:36:53.314  1036  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 11:36:53.316   315   894 D CommandListener: Setting iface cfg
,09-02 11:36:53.320  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:53.321  1036  1536 E WifiStateMachine: Start Dhcp Watchdog 1
09-02 11:36:53.322  1036  6585 D DhcpStateMachine: StoppedState
09-02 11:36:53.322  1036  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=188848  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:36:53.322  1036  6585 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:53.322  1036  6585 D DhcpStateMachine: WaitBeforeStartState
,09-02 11:36:53.322  1036  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=188849  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:36:53.323  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=188850  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:36:53.324  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:53.324  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:53.324  1036  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:53.325  1036  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:53.325  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:53.325  1036  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:53.327  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:36:53.328  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:53.328  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 11:36:53.328  1036  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=188855  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:36:53.329  1036  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=188855  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-02 11:36:53.329  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=188856  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:36:53.331  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-364769197] from screen [on:0 period:-364769197]
09-02 11:36:53.332  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-364769196]
09-02 11:36:53.332  1036  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 11:36:53.333  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:53.340  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:53.343  1036  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
09-02 11:36:53.340  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 11:36:53.343  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.343  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:36:53.343  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.344  1036  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.344  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:53.345  1036  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.345  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.345  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.346  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-02 11:36:53.346  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
09-02 11:36:53.347  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
09-02 11:36:53.347  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 11:36:53.347  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:53.347  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 11:36:53.348  1036  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 11:36:53.348  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 11:36:53.348  1036  1536 D WifiNative-wlan0: SET ps 0: returned true
09-02 11:36:53.348  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 11:36:53.348  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 11:36:53.349  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 11:36:53.349  1036  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 11:36:53.349  1036  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 11:36:53.349  1036  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 11:36:53.349  1036  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
09-02 11:36:53.350  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@104c0a8b target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:53.350  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@104c0a8b target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:53.350  1036  6585 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:53.351  1036  6585 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 11:36:53.352  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:53.352  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 11:36:53.355  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:53.357  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:53.357  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 11:36:53.361  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:53.368  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:53.368  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:53.368  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 11:36:53.494  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:53.495  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 11:36:53.495  1036  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:53.508  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 11:36:53.509  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 11:36:53.511  1036  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 11:36:53.512  1036  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-02 11:36:53.514  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 11:36:53.516  1036  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 11:36:53.554  1036  6585 D DhcpStateMachine: DHCPV4 request on wlan0
,09-02 11:36:53.556  1036  6585 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 11:36:53.556  1036  6585 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 11:36:53.568  6588  6588 W dhcpcd  : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:53.568  6588  6588 W dhcpcd  : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 11:36:53.598  6588  6588 I dhcpcd  : version 5.5.6 starting
,09-02 11:36:53.601  6588  6588 E dhcpcd  : get_duid: m
09-02 11:36:53.601  6588  6588 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 11:36:53.601  6588  6588 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 11:36:53.690  6588  6588 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 11:36:53.690  6588  6588 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 11:36:53.690  6588  6588 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-02 11:36:53.693  6588  6588 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-02 11:36:53.693  6588  6588 D dhcpcd  : wlan0: sending REQUEST (xid 0xc95567e2), next in 4.38 seconds
09-02 11:36:53.765  6588  6588 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-02 11:36:53.773  6588  6588 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 11:36:53.774  6588  6588 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 11:36:53.775  6588  6588 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 11:36:53.775  6588  6588 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 11:36:53.776  6588  6588 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 11:36:53.777  6588  6588 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 11:36:53.777  6588  6588 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 11:36:53.777  6588  6588 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 11:36:53.780  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.781  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 11:36:53.783  1036  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.784  1036  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.786  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.787  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:53.788  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-02 11:36:54.163  1036  6585 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-02 11:36:54.167  1036  6585 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 11:36:54.167  1036  6585 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 11:36:54.168  1036  6585 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 11:36:54.168  1036  6585 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 11:36:54.168  1036  6585 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 11:36:54.168  1036  6585 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
09-02 11:36:54.169  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 11:36:54.169  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 11:36:54.170  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 11:36:54.170  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 11:36:54.170  1036  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.170  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.171  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 11:36:54.171  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 11:36:54.171  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 11:36:54.172  1036  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 11:36:54.172  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 11:36:54.172  1036  6585 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 11:36:54.174  1036  6585 D DhcpStateMachine: RunningState
09-02 11:36:54.188  1036  1536 D WifiNative-wlan0: SET ps 1: returned true
09-02 11:36:54.189  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 11:36:54.190  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 11:36:54.190  1036  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-02 11:36:54.196  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-02 11:36:54.196  1036  1543 D ConnectivityService: ignoring duplicate network state non-change
,09-02 11:36:54.219  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:54.219  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:54.225  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.225  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.225  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 11:36:54.233  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 11:36:54.237  1036  1543 D ConnectivityService: Adding iface wlan0 to network 100
09-02 11:36:54.243  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.243  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.243  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 11:36:54.246  1036  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 11:36:54.264  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:36:54.275  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:54.275  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:54.279  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-02 11:36:54.287  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-02 11:36:54.299  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.300  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.300  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.300  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 11:36:54.314  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-02 11:36:54.332  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 11:36:54.336  1036  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 11:36:54.336  1036  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,09-02 11:36:54.340  1036  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
09-02 11:36:54.343  1036  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
09-02 11:36:54.344  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 11:36:54.345  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.346  1036  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 11:36:54.346  1036  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
09-02 11:36:54.347  1036  1543 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
09-02 11:36:54.356  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 11:36:54.356  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.356  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 11:36:54.359  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 11:36:54.359  1036  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.359  1036  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.360  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.360  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:36:54.360  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.360  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 11:36:54.360  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.360  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 11:36:54.361  1036  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-02 11:36:54.361  1036  1543 D ConnectivityService:    accepting network in place of null
09-02 11:36:54.361  1036  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.361  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.361  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 11:36:54.361  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.362  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 11:36:54.363  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.363  1036  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.364  1036  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:36:54.364  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 11:36:54.364  1036  1543 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
09-02 11:36:54.365  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:54.370  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:54.370  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,09-02 11:36:54.371   315  6639 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 11:36:54.379  1036  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 11:36:54.379  1036  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 11:36:54.380  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 11:36:54.380  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.387  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:54.387  1036  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 11:36:54.388  1036  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,09-02 11:36:54.391  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 11:36:54.391  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 11:36:54.391  1036  1543 D ConnectivityService: validation of new default Network = false
09-02 11:36:54.391  1036  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 11:36:54.391  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 11:36:54.392   315  6644 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-02 11:36:54.392  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 11:36:54.392  1036  1036 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
09-02 11:36:54.392   315  6644 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
09-02 11:36:54.397  1036  1543 D DSQN    : enableDataServiceNotify 
09-02 11:36:54.397  1036  1543 D DSQN    : start dsqn bin
09-02 11:36:54.398  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:54.402   315  6646 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-02 11:36:54.402   315  6646 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
09-02 11:36:54.408  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:54.417  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.417  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.417  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-02 11:36:54.417  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.418  1601  2128 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 11:36:54.408  6647  6647 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:54.408  6647  6647 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:54.426   315  6644 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
09-02 11:36:54.428  1036  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:36:54.429  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:36:54.429  1036  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:36:54.430  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:54.430  1036  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:36:54.430  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:54.430  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:36:54.431  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:36:54.431  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
09-02 11:36:54.431  1036  1543 D ConnectivityService: identical MTU - not setting
09-02 11:36:54.432  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 11:36:54.432  1036  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-02 11:36:54.432  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.432  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.432  1036  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-02 11:36:54.435  1601  2128 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-02 11:36:54.437   315  6639 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-02 11:36:54.438  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:36:54.443  6647  6647 E DSQN    : DSQN ssw
09-02 11:36:54.443  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:54.443  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 11:36:54.444  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:36:54.445  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.451  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:54.456  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:54.459  1036  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-02 11:36:54.463  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:54.464  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:54.464  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:36:54.466   315  6646 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
09-02 11:36:54.468  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 11:36:54.469   315  6639 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-02 11:36:54.471  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 11:36:54.476  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:54.478  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:54.482  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:54.488  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:54.488  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:54.489  6385  6385 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 11:36:54.490  6385  6385 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 11:36:54.490  6385  6385 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-02 11:36:54.494  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:54.498  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 11:36:54.498  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 11:36:54.501  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:54.505   315   893 D LGDataListener: argv[0]=dsqncommand
,09-02 11:36:54.505   315   893 D LGDataListener: argv[1]=wlan0
09-02 11:36:54.505   315   893 D LGDataListener: argv[2]=1
09-02 11:36:54.505   315   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 11:36:54.505  1036  6645 D LocSvc_java: NTP server : europe.pool.ntp.org
,09-02 11:36:54.506  1036  6645 D LocSvc_java: NTP server returned: 1472809014268 (Fri Sep 02 11:36:54 GMT+02:00 2016) reference: 190032 certainty: 19 system time offset: -237
09-02 11:36:54.506  1036  6645 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
09-02 11:36:54.506  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 11:36:54.506  1036  1116 D DSQN    : start to monitor internet connection
09-02 11:36:54.509  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:54.520  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:54.520  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:54.521  6385  6385 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 11:36:54.521  6385  6385 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 11:36:54.522  6385  6385 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-02 11:36:54.535  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 09:36:54 GMT], X-Android-Received-Millis=[1472809014534], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472809014505]}
09-02 11:36:54.535  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 11:36:54.536  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 11:36:54.536  1036  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.536  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.536  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:36:54.536  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.536  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 11:36:54.537  1036  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
09-02 11:36:54.537  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.537  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.537  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.537  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.538  1036  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.538  1601  2128 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 11:36:54.538  1036  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.538  1036  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:36:54.538  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 11:36:54.539  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 11:36:54.539  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 11:36:54.564  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 11:36:54.565  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:36:54.566  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.609  1036  2013 D WifiServiceImplEx: setWifiEnabled: false pid=6204, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 11:36:54.609  1036  2013 D WifiService: setWifiEnabled: false pid=6204, uid=10118
09-02 11:36:54.609  1036  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:36:54.637  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:36:54.638  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:36:54.638  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-02 11:36:54.639  1036  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:54.640  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:54.641  1036  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:54.642  1036  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:54.644  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 11:36:54.644  1036  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 11:36:54.644  1036  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 11:36:54.644  1036  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 11:36:54.646  1036  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 11:36:54.646  1036  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 11:36:54.661  1036  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 11:36:54.662  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,09-02 11:36:54.662  1036  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.662  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.663  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 11:36:54.664  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 11:36:54.664  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 11:36:54.665  1036  1536 D WifiNative-wlan0: SET ps 1: returned true
09-02 11:36:54.667  1036  6585 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.672   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 11:36:54.732  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 11:36:54.733  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-02 11:36:54.743  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.743  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 11:36:54.743  1036  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@73658e6
09-02 11:36:54.744  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-02 11:36:54.744  1036  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:54.744  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:54.745  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:54.746  1036  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:54.746  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:54.747  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:36:54.748  1036  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 11:36:54.749  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 11:36:54.751  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:54.751  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 11:36:54.755  1036  1535 D LGWifiP2pService: P2pDisablingState
09-02 11:36:54.756  1036  1535 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.756  1036  1535 D LGWifiP2pService: p2p socket connection lost
09-02 11:36:54.756  1036  1535 D LGWifiP2pService: P2pDisabledState
09-02 11:36:54.756  1036  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 11:36:54.756  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 11:36:54.756  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.757  6528  6528 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 11:36:54.757  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.757  1036  1535 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.757  1036  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.757  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 11:36:54.757  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 11:36:54.757  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 11:36:54.758  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-02 11:36:54.758  1036  1536 D WifiNative-wlan0: SET ps 1: returned true
09-02 11:36:54.758  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.758  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.758  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 11:36:54.759  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 11:36:54.759  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-02 11:36:54.759  1036  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.759  1036  1555 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.762  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 11:36:54.762  1942  1942 D WfdsService: WifiP2pState is changed : false
09-02 11:36:54.762  1942  2258 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 11:36:54.762  1942  2258 D WfdsService: Set the WFDS Monitor: false
09-02 11:36:54.765  1942  2258 D WfdsMonitor: WFDS Monitor is stopped
09-02 11:36:54.765  1942  2258 D WfdsService: STATE : WfdsDisabledState - enter
09-02 11:36:54.766  1942  2260 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 11:36:54.766  1942  6552 D CtrlSupplicant: Received on exit socket, terminate
09-02 11:36:54.766  1942  6552 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 11:36:54.766  1942  6552 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 11:36:54.766  1942  6552 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,09-02 11:36:54.767  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.769  1942  2258 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 11:36:54.769  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:54.769  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 11:36:54.770  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:54.770  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.773  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 11:36:54.774  6336  6336 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 11:36:54.774  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:54.778  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:54.784  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:54.794  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:36:54.794  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 11:36:54.796  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 11:36:54.797  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:54.800  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-02 11:36:54.801  6336  6336 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 11:36:54.801  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:54.804  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:36:54.816  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:54.821  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 11:36:54.822  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:36:54.823  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 11:36:54.826  1036  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 11:36:54.826  1036  1543 D DSQN    : disableDataServiceNotify
09-02 11:36:54.826  1036  1543 D DSQN    : stop dsqn bin
09-02 11:36:54.826   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 11:36:54.828  1036  1536 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 11:36:54.829  1036  1536 D WifiNative-p2p0: TERMINATE: returned true
09-02 11:36:54.829  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-02 11:36:54.829  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:36:54.829  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:36:54.829  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 11:36:54.830  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 11:36:54.830  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:36:54.831  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.831  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.832  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 11:36:54.832  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:36:54.834  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 11:36:54.837  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:36:54.837  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:54.837  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:36:54.837  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:54.837  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:54.837  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 11:36:54.838  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:36:54.838  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 11:36:54.839  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:54.839  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:36:54.839  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:54.839  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:54.841  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 11:36:54.841  6336  6336 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 11:36:54.841  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:54.843  1036  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 11:36:54.844  1036  1543 D ConnectivityService:  sending notification for NetworkRequest ,[ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 11:36:54.844  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.844  1036  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:36:54.845  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 11:36:54.845  1601  2128 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 11:36:54.845  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:36:54.845  1036  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 11:36:54.845  1036  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 11:36:54.845  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 11:36:54.846  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:54.846  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 11:36:54.846  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:54.846  1036  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.846  1036  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.847  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.847  1036  1543 D NetworkManagementService: Removing idletimer
09-02 11:36:54.847  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.847  1036  6584 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 11:36:54.847  1036  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 11:36:54.847  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.847  1036  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:54.847  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 11:36:54.847  1036  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:54.848  1036  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN ,LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:36:54.848  1036  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 11:36:54.849  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 11:36:54.849  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 11:36:54.849  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 11:36:54.849  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 11:36:54.849  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 11:36:54.849  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 11:36:54.849  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 11:36:54.849  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 11:36:54.850  1036  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 11:36:54.853  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:36:54.864  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 11:36:54.873  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 11:36:54.873  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 11:36:54.876  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 11:36:54.884  1036  6585 D DhcpStateMachine: StoppedState
09-02 11:36:54.884  1036  6585 D DhcpStateMachine: StoppedState{ when=-126ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:54.884  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:36:54.886  1036  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,09-02 11:36:54.886  1036  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-02 11:36:54.890  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 11:36:54.895  6428  6661 W FormManager: Network not available. Please check & try again.
09-02 11:36:54.896  6528  6528 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 11:36:54.897  6528  6528 I wpa_supplicant: monitor socket send errors count : 1
09-02 11:36:54.897  6528  6528 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
09-02 11:36:54.897  1036  6550 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 11:36:54.897  1036  6550 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-02 11:36:54.900  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:36:54.902  6428  6662 V FormManager: Network unavailable.
09-02 11:36:54.908  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 11:36:54.909  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.910  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.912  6428  6662 V FormManager: Network unavailable.
,09-02 11:36:54.936  6528  6528 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 11:36:54.936  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 11:36:54.936  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 11:36:54.936  1036  6550 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 11:36:54.936  1036  6550 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 11:36:54.937  6528  6528 W wpa_supplicant: USIM:  scard_deinit function
09-02 11:36:54.938  1036  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=190464
09-02 11:36:54.938  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:36:54.938  1036  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=190465
09-02 11:36:54.938  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:36:54.938  1036  1118 D Tethering: InitialState.processMessage what=4
09-02 11:36:54.939  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 11:36:54.939  1036  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=190466  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 11:36:54.940  1036  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=190466  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 11:36:54.940  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.940  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:54.941  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 11:36:54.943  1036  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:54.944  1036  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:36:54.945  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:36:54.945  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 11:36:54.945  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:36:54.945  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 11:36:54.946  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:36:54.947  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:36:54.947  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 11:36:54.947  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:36:54.947  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:36:54.947  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 11:36:54.947  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 11:36:55.037  6528  6528 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-02 11:36:55.039  1036  6550 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 11:36:55.039  1036  6550 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 11:36:55.039  1036  6550 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 11:36:55.040  1036  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
09-02 11:36:55.148  1942  1942 D WfdsService: Supplicant Connection state is changed : false
09-02 11:36:55.149  1942  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-02 11:36:55.151  1942  2258 D WfdsService: Set the WFDS Monitor: false
09-02 11:36:55.151  1942  2258 D WfdsMonitor: WFDS Monitor is stopped
,09-02 11:36:55.159  1036  1536 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 11:36:55.159  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:36:55.159  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:36:55.159  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 11:36:55.161  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 11:36:55.161  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 11:36:55.166  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 11:36:55.166  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:36:55.167  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:36:55.171  2466  2466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 11:36:55.173  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:55.174  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:55.175  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 11:36:55.176  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 11:36:55.176  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 11:36:55.177  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:55.177  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:55.179  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:36:55.195  6336  6336 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 11:36:55.195  6336  6336 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 11:36:55.195  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 11:36:55.198  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 11:36:55.203  6428  6668 V FormManager: Network unavailable.
09-02 11:36:55.206  6428  6667 W FormManager: Network not available. Please check & try again.
09-02 11:36:55.207  6428  6668 V FormManager: Network unavailable.
09-02 11:36:55.207  4241  6669 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 11:36:55.209  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 11:36:55.217  4241  6670 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-02 11:36:55.218  4241  6670 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 11:36:55.321  6116  6504 D UEI.SmartControl: Internal timer expired: 2
09-02 11:36:55.321  6116  6504 D UEI.SmartControl: unbind internal service
,09-02 11:36:55.611  6116  6501 D serial_port: close(fd = 24)
,09-02 11:36:55.627  6116  6501 I UEI.SmartControl: Serial port is closed.
09-02 11:36:56.345  1036  1536 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-364766183] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 11:36:56.348  1036  1536 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-364766180] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-02 11:36:57.390  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:36:57.410  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,09-02 11:36:57.418  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:57.419  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:57.427  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 11:36:57.433  3674  6317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 11:36:57.434  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:57.449  5366  5366 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 11:36:57.469  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 11:36:57.503  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:36:57.515  1036  1100 E GpsLocationProvider: No APN found to select.
09-02 11:36:57.579  1036  1051 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6688 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-02 11:36:57.601   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 21.944ms
,09-02 11:36:57.624   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 20.507ms
09-02 11:36:57.640  1036  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 11:36:57.640  1036  1574 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-02 11:36:57.645   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 523us total 20.647ms
,09-02 11:36:57.661  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:36:57.662  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:36:57.662  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-02 11:36:57.663  1036  1118 D BluetoothManagerService: Message: 1
09-02 11:36:57.663  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 11:36:57.668  6688  6688 I AppUp4:AppBoxCP: onCreate
09-02 11:36:57.669  6688  6688 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-02 11:36:57.678  6688  6688 I AppUp4:DB:  setFingerPrint start
,09-02 11:36:57.679  6688  6688 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-02 11:36:57.683  1036  1118 D BluetoothManagerService: Message: 20
09-02 11:36:57.683  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36036475:true
09-02 11:36:57.684  6478  6478 D BluetoothAdapterState: make
09-02 11:36:57.687  6688  6688 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-02 11:36:57.687  6688  6688 I AppUp4:DB:  SDK version = 21
09-02 11:36:57.687  6688  6688 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-02 11:36:57.688  6478  6478 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 11:36:57.689  6478  6478 I bluedroid-qcom: init
09-02 11:36:57.689  6688  6688 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-02 11:36:57.689  6478  6713 I BluetoothAdapterState: Entering OffState
09-02 11:36:57.690  6478  6478 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 11:36:57.690  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 11:36:57.690  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:57.690  6478  6478 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 11:36:57.690  6478  6478 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 11:36:57.690  6478  6478 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 11:36:57.690  6478  6478 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 11:36:57.691  6478  6478 I bluedroid-qcom: get_profile_interface socket
09-02 11:36:57.691  6478  6478 I bluedroid-qcom: get_profile_interface map_client
09-02 11:36:57.692  6478  6716 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 11:36:57.678  6717  6717 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:57.678  6717  6717 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 11:36:57.694  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-02 11:36:57.694  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 11:36:57.697  6478  6716 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 11:36:57.699  6717  6717 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 11:36:57.699  6717  6717 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 11:36:57.699  6717  6717 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-02 11:36:57.699  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-02 11:36:57.699  6478  6716 D BluetoothAdapterProperties: Name is: G3
09-02 11:36:57.700  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 11:36:57.700  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 11:36:57.700  1036  1118 D BluetoothManagerService: Message: 40
09-02 11:36:57.700  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 11:36:57.701  6478  6493 I bluedroid-qcom: config_hci_snoop_log
09-02 11:36:57.702  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 11:36:57.702  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 11:36:57.702  6688  6688 I AppUp4:CustModeStarterReceiver: onReceive
09-02 11:36:57.706  6717  6717 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-02 11:36:57.708  6478  6713 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 11:36:57.709  6478  6713 D BluetoothAdapterProperties: Setting state to 11
09-02 11:36:57.709  6478  6713 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 11:36:57.709  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:36:57.710  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 11:36:57.710  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 11:36:57.712  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 11:36:57.713  6319  6319 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-02 11:36:57.714  6717  6717 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 11:36:57.714  6717  6717 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 11:36:57.714  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:57.715  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:57.717  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:57.717  6478  6713 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 11:36:57.724  6478  6478 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-02 11:36:57.725  6478  6478 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:57.726  6478  6478 V BluetoothPbapReceiver: ***********state = 11
09-02 11:36:57.729  6478  6713 D BluetoothBondStateMachine: make
09-02 11:36:57.729  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:36:57.734  6478  6722 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 11:36:57.735  6478  6713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:57.735  6478  6713 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 11:36:57.735  6478  6713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:57.735  6478  6713 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 11:36:57.736  6478  6713 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 11:36:57.736  6688  6688 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:36:57.736  6688  6688 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 11:36:57.741  6319  6319 D BluetoothPermissionRequest: onReceive
,09-02 11:36:57.742  6688  6688 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20096d08
09-02 11:36:57.742  6688  6688 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 11:36:57.742  6688  6688 D AppUp4:CustFacade: isPhone : true
09-02 11:36:57.742  6478  6713 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:36:57.742  6688  6688 D AppUp4:CustModeStarterReceiver: begin check event
09-02 11:36:57.743  6688  6688 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-02 11:36:57.743  6688  6688 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-02 11:36:57.745  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:36:57.750  6478  6478 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:57.752  6478  6713 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 11:36:57.754  6478  6478 D HeadsetService: Received start request. Starting profile...
09-02 11:36:57.755  6478  6478 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 11:36:57.755  6478  6478 D LGBluetoothHfpAdapter: Version 1.6
09-02 11:36:57.758  6478  6478 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 11:36:57.758  6688  6718 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-02 11:36:57.758  6688  6718 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-02 11:36:57.758  6688  6718 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-02 11:36:57.759  6478  6478 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 11:36:57.760  6478  6478 D HeadsetStateMachine: make
09-02 11:36:57.761  6478  6713 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:36:57.763  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:57.764  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 11:36:57.765  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 11:36:57.766  6478  6713 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:36:57.768  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:36:57.770  6478  6713 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:36:57.774  4241  6724 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 11:36:57.776  6478  6713 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:36:57.776  4241  6725 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:57.776  4241  6725 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 11:36:57.785  6478  6478 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:36:57.785  6478  6478 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 11:36:57.808  1036  1626 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6726 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 11:36:57.812  6478  6478 D HeadsetStateMachine: max_hf_connections = 1
09-02 11:36:57.812  6478  6478 I bluedroid-qcom: get_profile_interface handsfree
09-02 11:36:57.813  6478  6478 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 11:36:57.813   319  1383 V AudioPolicyService: registerClient() client 0xb04107e0, uid 1002
09-02 11:36:57.814   319  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 11:36:57.814   319  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 11:36:57.814   319  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 11:36:57.815  6478  6478 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 11:36:57.815   319  2195 V AudioFlinger: registerClient() client 0xb55815f8, pid 6478
09-02 11:36:57.816   319  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:36:57.816   319  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:36:57.816  6478  6478 V ToneGenerator: Create Track: 0xb4928a80
09-02 11:36:57.816  6478  6478 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 11:36:57.816  6478  6478 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 11:36:57.816  1601  3390 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:36:57.816  1601  3390 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:36:57.816  3306  4830 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:36:57.816  3306  4830 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:36:57.816   319  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 11:36:57.816   319  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:36:57.816   319  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 11:36:57.816   319  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:36:57.816   319  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 11:36:57.816   319  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 11:36:57.816  6478  6478 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 11:36:57.816   319  1383 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 11:36:57.817   319  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 11:36:57.817   319  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 11:36:57.817  1036  2013 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:36:57.817   319  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 11:36:57.817   319  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 11:36:57.817  1036  2013 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:36:57.817  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:36:57.817  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:36:57.817  6478  6493 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:36:57.817  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:36:57.817  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:36:57.817  6478  6493 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 11:36:57.817  2176  2194 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:36:57.817  2176  2194 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:36:57.817  2176  2194 V AudioSystem: ioConfigChanged(), event 0, ioHandle 4
09-02 11:36:57.817  2176  2194 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:36:57.817  3306  3325 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:36:57.817  3306  3325 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:36:57.817  1601  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:36:57.818  1601  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:36:57.818  6478  6478 V AudioSystem: getLatency() output 2, latency 50
09-02 11:36:57.818  6478  6478 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 11:36:57.818  6478  6478 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 11:36:57.818   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 11:36:57.818   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 11:36:57.818   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 11:36:57.818   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 11:36:57.818   319   319 V AudioFlinger: createTrack() lSessionId: 22
09-02 11:36:57.818  6478  6493 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:36:57.818  6478  6493 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 11:36:57.818  1036  2013 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:36:57.818  1036  2013 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:36:57.818  6478  6713 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:36:57.819  6478  6478 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 11:36:57.819   319  2195 V AudioFlinger: acquiring 22 from 6478, for 6478
09-02 11:36:57.819   319  2195 V AudioFlinger:  added new entry for 22
09-02 11:36:57.819  6478  6478 V ToneGenerator: ToneGenerator INIT OK, time: 193356
09-02 11:36:57.819  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:57.820  6478  6723 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 11:36:57.820  6478  6723 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 11:36:57.821  6478  6723 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 11:36:57.821  6478  6723 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 11:36:57.821   319  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6478
09-02 11:36:57.822   319  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 11:36:57.822   319  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
,09-02 11:36:57.822   319  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 11:36:57.822   319  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 11:36:57.822   319  1383 V voice   : voice_set_parameters: exit with code(0)
09-02 11:36:57.822   319  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 11:36:57.822   319  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 11:36:57.822   319  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 11:36:57.822   319  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 11:36:57.822   319  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 11:36:57.822   319  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 11:36:57.822  6478  6723 V ToneGenerator: ToneGenerator destructor
,09-02 11:36:57.822  6478  6723 V ToneGenerator: stopTone
09-02 11:36:57.822  6478  6723 V ToneGenerator: Delete Track: 0xb4928a80
09-02 11:36:57.822  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:57.822  6478  6478 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:36:57.822  6478  6478 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 11:36:57.822  6478  6478 V BluetoothSapReceiver: SapReceiver onReceive ,
09-02 11:36:57.823  6478  6478 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:57.823  6478  6478 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-02 11:36:57.824  6478  6478 D A2dpService: Received start request. Starting profile...
09-02 11:36:57.825  6478  6478 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 11:36:57.825  6478  6478 V Avrcp   : make
09-02 11:36:57.825  6478  6478 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 11:36:57.825  6478  6478 I bluedroid-qcom: get_profile_interface avrcp
09-02 11:36:57.829  6478  6723 V AudioTrack: ~AudioTrack, releasing session id from 6478 on behalf of 6478
09-02 11:36:57.829  1036  2032 W Process : Unable to open /proc/6740/status
09-02 11:36:57.830   319  1382 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 11:36:57.830   319  1382 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 11:36:57.830   319  1382 V AudioFlinger: PlaybackThread::Track destructor
09-02 11:36:57.830   319  1273 V AudioPolicyService: AudioCommandThread() waking up
09-02 11:36:57.830   319  1382 V AudioFlinger: removeClient_l() pid 6478, calling pid 319
09-02 11:36:57.830   319  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 11:36:57.830   319  1273 V AudioPolicyManager: releaseOutput() 2
09-02 11:36:57.830   319  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 11:36:57.830   319  1382 V AudioFlinger: releasing 22 from 6478 for 6478
09-02 11:36:57.830   319  1382 V AudioFlinger:  decremented refcount to 0
09-02 11:36:57.830   319  1382 V AudioFlinger: purging stale effects
09-02 11:36:57.837  6478  6713 V LGMDMManager: Create singleton instance
09-02 11:36:57.838  6478  6713 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 11:36:57.840  6478  6478 V AudioManager: registerRemoteController: size of Media player list: 0
09-02 11:36:57.846  6478  6478 E AudioManager: No RCC entry present to update
09-02 11:36:57.846  6478  6478 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 11:36:57.847  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:57.848  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:57.848  6478  6478 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 11:36:57.848  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-02 11:36:57.849  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 11:36:57.849  6478  6478 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 11:36:57.850  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:36:57.851  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-02 11:36:57.853  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:57.855  5366  5366 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 11:36:57.855  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 11:36:57.856  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:57.856  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:36:57.856  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:57.856  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 11:36:57.858  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:57.913  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:57.913  5366  5366 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 11:36:57.940  6726  6726 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 11:36:57.941  6726  6726 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 11:36:57.944  6726  6726 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 11:36:57.945  6726  6726 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 11:36:57.985  1036  1626 V SIM_STK : Menu title from STK is T-Mobile
09-02 11:36:57.985  1036  1626 V SIM_STK : Menu title from STK is T-Mobile
,09-02 11:36:58.057  6726  6726 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-02 11:36:58.082  1036  1885 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 11:36:58.087  6726  6726 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-02 11:36:58.093  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 11:36:58.100  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 11:36:58.101  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 11:36:58.102  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 11:36:58.102  6478  6478 I BluetoothA2dpServiceJni: classInitNative
09-02 11:36:58.102  6478  6478 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 11:36:58.102  6478  6478 D A2dpStateMachine: make
09-02 11:36:58.104  6478  6478 I bluedroid-qcom: get_profile_interface a2dp
09-02 11:36:58.105  6478  6749 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 11:36:58.107  6478  6478 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 11:36:58.107  6478  6478 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 11:36:58.108  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.108  6478  6748 D A2dpStateMachine: Enter Disconnected: -2
,09-02 11:36:58.110  6478  6478 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 11:36:58.112  6478  6478 D HidService: Received start request. Starting profile...
09-02 11:36:58.112  6478  6478 I bluedroid-qcom: get_profile_interface hidhost
09-02 11:36:58.113  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.114  6478  6478 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 11:36:58.116  6478  6478 D HealthService: Received start request. Starting profile...
09-02 11:36:58.118  6478  6478 I bluedroid-qcom: get_profile_interface health
09-02 11:36:58.118  6478  6478 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 11:36:58.119  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.119  6478  6478 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 11:36:58.121  6478  6478 D PanService: Received start request. Starting profile...
09-02 11:36:58.121  6478  6478 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 11:36:58.121  6478  6478 I bluedroid-qcom: get_profile_interface pan
,09-02 11:36:58.129  6478  6478 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 11:36:58.130  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.132  6726  6726 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 11:36:58.133  6478  6478 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-02 11:36:58.147  6478  6478 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 11:36:58.148  6478  6478 D BtGatt.GattService: Received start request. Starting profile...
09-02 11:36:58.148  6478  6478 D BtGatt.GattService: start()
09-02 11:36:58.148  6478  6478 I bluedroid-qcom: get_profile_interface gatt
09-02 11:36:58.148  6478  6478 D BtGatt.AdvertiseManager: advertise manager created
09-02 11:36:58.155  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.156  6478  6478 D HeadsetStateMachine: Proxy object connected
09-02 11:36:58.157  6478  6478 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 11:36:58.157  6478  6478 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 11:36:58.162  6478  6478 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:36:58.162  6478  6723 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 11:36:58.164  6478  6723 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 11:36:58.164  6478  6723 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-02 11:36:58.167  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.167  6726  6726 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:36:58.167  6726  6726 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 11:36:58.168  6478  6478 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 11:36:58.171  6478  6478 V BluetoothMapService: BluetoothMapBinder()
09-02 11:36:58.172  6478  6478 D BluetoothMapService: Received start request. Starting profile...
09-02 11:36:58.172  6478  6478 D BluetoothMapService: start()
09-02 11:36:58.175  6478  6478 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 11:36:58.175  6478  6478 D BluetoothMapEmailAppObserver: createReceiver()
09-02 11:36:58.176  6478  6478 D BluetoothMapEmailAppObserver: initObservers()
09-02 11:36:58.176  6478  6478 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-02 11:36:58.183  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.186  6478  6478 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:36:58.188  6478  6478 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:36:58.190  6478  6478 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 11:36:58.191  6478  6478 V PanService: [BTUI] SIM Extra State :ABSENT,
09-02 11:36:58.194  6478  6478 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:36:58.196  6478  6478 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-02 11:36:58.196  6478  6478 V BluetoothMapService: Handler(): got msg=1
09-02 11:36:58.197  6478  6713 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,09-02 11:36:58.197  6478  6713 I bluedroid-qcom: enable
09-02 11:36:58.197  6478  6757 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 11:36:58.197  6478  6757 I bt-btu  : btu_task pending for preload complete event
09-02 11:36:58.197  6478  6713 I bt_hci_bdroid: init
,09-02 11:36:58.198  6478  6713 I bt_vendor: bt-vendor : init
,09-02 11:36:58.199  6478  6713 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 11:36:58.199  6478  6713 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 11:36:58.199  6478  6713 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 11:36:58.199  6478  6713 D bt_userial_mct: userial_init
09-02 11:36:58.199  6478  6713 D bt_hci_bdroid: set_power 1
09-02 11:36:58.199  6478  6713 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 11:36:58.199  6478  6713 I bt_vendor: Starting hciattach daemon
09-02 11:36:58.199  6478  6713 I bt_vendor: try to set true
09-02 11:36:58.188  6760  6760 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:58.188  6760  6760 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 11:36:58.238  6763  6763 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-02 11:36:58.276  6726  6726 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 11:36:58.307  3306  3306 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 11:36:58.307  3306  3306 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:36:58.308  6726  6726 I HubEmail: JNI_OnLoad()
09-02 11:36:58.308  6726  6726 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 11:36:58.308  6726  6726 I HubEmail: registerNatives()
09-02 11:36:58.308  6726  6726 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 11:36:58.308  6726  6726 I HubEmail: registerNativeMethods()
09-02 11:36:58.308  6726  6726 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 11:36:58.308  6726  6726 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-02 11:36:58.309  3306  3306 I LgeMiscReceiver: networkInfo.isConnected() = true
09-02 11:36:58.309  3306  3306 D PhoneState: setPdpRejectCasuse : false
09-02 11:36:58.334  6774  6774 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 11:36:58.345  6775  6775 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-02 11:36:58.357  1036  1626 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6777 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-02 11:36:58.362  6428  6771 W FormManager: Network not available. Please check & try again.
09-02 11:36:58.365  6726  6773 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:36:58.368  6787  6787 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 11:36:58.369  6428  6772 V FormManager: Network unavailable.
09-02 11:36:58.374  6428  6772 V FormManager: Network unavailable.
09-02 11:36:58.378  1036  1941 I ActivityManager: Killing 2176:com.lge.music/u0a34 (adj 15): empty #17
,09-02 11:36:58.378  6791  6791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-02 11:36:58.390  6794  6794 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-02 11:36:58.394   319   319 V AudioFlinger: 2176 died, releasing its sessions
09-02 11:36:58.394   319   319 V AudioFlinger:  pid 1851 @ 0
09-02 11:36:58.394   319   319 V AudioFlinger:  pid 3306 @ 1
09-02 11:36:58.394   319   319 V AudioFlinger:  pid 3306 @ 2
,09-02 11:36:58.400  6797  6797 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-02 11:36:58.420  6799  6799 I libmdmdetect: ESOC framework not supported
,09-02 11:36:58.423  6799  6799 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-02 11:36:58.431  6799  6799 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-02 11:36:58.431  6799  6799 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 11:36:58.431  6799  6799 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 11:36:58.431  6799  6799 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 11:36:58.431  6799  6799 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 11:36:58.431  6799  6799 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 11:36:58.431  6799  6799 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 11:36:58.434  1036  2012 W libprocessgroup: failed to open /acct/uid_10034/pid_2176/cgroup.procs: No such file or directory
,09-02 11:36:58.471  6799  6800 E QC-QMI  : qmi_client [6799] 14: failed to locate client data
09-02 11:36:58.474   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 11:36:58.474   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-02 11:36:58.500  6777  6777 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:36:58.500  6777  6777 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 11:36:58.503  6777  6777 D PhoneMonitor: Register our PhoneStateListener
,09-02 11:36:58.528  6777  6777 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-02 11:36:58.532  6777  6777 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-02 11:36:58.561  6802  6802 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
09-02 11:36:58.569  6777  6777 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-02 11:36:58.570  6777  6777 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-02 11:36:58.571  6777  6777 D TelephonyAutoProfiling: [parse] Load xml
,09-02 11:36:58.577  6777  6777 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-02 11:36:58.577  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-02 11:36:58.577  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-02 11:36:58.577  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-02 11:36:58.577  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-02 11:36:58.577  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-02 11:36:58.577  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-02 11:36:58.577  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-02 11:36:58.578  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-02 11:36:58.578  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-02 11:36:58.578  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-02 11:36:58.578  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-02 11:36:58.578  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-02 11:36:58.578  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-02 11:36:58.578  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-02 11:36:58.579  6777  6777 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-02 11:36:58.579  6777  6777 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-02 11:36:58.588  6804  6804 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-02 11:36:58.589  6777  6777 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-02 11:36:58.610  1036  1923 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6806 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 11:36:58.611  1036  1923 I ActivityManager: Killing 5956:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-02 11:36:58.652  6478  6713 I bt_vendor: bluetooth satus is on
09-02 11:36:58.652  6478  6713 D bt_hci_bdroid: preload
09-02 11:36:58.652  6478  6759 D bt_userial_mct: userial_open(port:0)
09-02 11:36:58.652  6478  6759 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 11:36:58.656  6478  6759 I bt_vendor: Done intiailizing UART
,09-02 11:36:58.660  6478  6759 I bt_vendor: Done intiailizing UART
09-02 11:36:58.661  6478  6759 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 11:36:58.661  6478  6759 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 11:36:58.661  6478  6823 D bt_userial_mct: Entering userial_read_thread()
09-02 11:36:58.661  6478  6757 I bt-btu  : btu_task received preload complete event
09-02 11:36:58.662  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 11:36:58.662  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 11:36:58.664  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 11:36:58.667  6478  6757 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 11:36:58.668  6478  6757 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 11:36:58.669  1036  1904 W libprocessgroup: failed to open /acct/uid_10061/pid_5956/cgroup.procs: No such file or directory
,09-02 11:36:58.757  6478  6757 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 11:36:58.757  6478  6757 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020c061 
09-02 11:36:58.758  6478  6757 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020c061 
,09-02 11:36:58.795  6478  6716 E bt-btif : Calling BTA_HhEnable
09-02 11:36:58.795  6478  6716 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 11:36:58.795  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 11:36:58.795  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 11:36:58.795  6478  6716 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 11:36:58.795  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 11:36:58.796  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 11:36:58.796  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 11:36:58.798  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 11:36:58.798  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 11:36:58.798  6478  6716 D BluetoothAdapterProperties: Name is: G3
09-02 11:36:58.800  6478  6716 D BluetoothAdapterProperties: Scan Mode:20
09-02 11:36:58.801  6478  6716 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 11:36:58.802  6478  6716 D bt_hci_bdroid: postload
09-02 11:36:58.802  6478  6759 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 11:36:58.803  6478  6716 D bte_conf: Device ID record 1 : primary
09-02 11:36:58.803  6478  6716 D bte_conf:   vendorId            = 00c4
09-02 11:36:58.803  6478  6716 D bte_conf:   vendorIdSource      = 0001
09-02 11:36:58.803  6478  6716 D bte_conf:   product             = 13a1
09-02 11:36:58.803  6478  6716 D bte_conf:   version             = 1000
09-02 11:36:58.803  6478  6716 D bte_conf:   clientExecutableURL = 
,09-02 11:36:58.803  6478  6716 D bte_conf:   serviceDescription  = 
09-02 11:36:58.803  6478  6716 D bte_conf:   documentationURL    = 
09-02 11:36:58.804  6478  6716 D bte_conf: bte_load_did_conf no section named DID2.
09-02 11:36:58.804  6478  6757 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 11:36:58.806  6478  6759 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 11:36:58.807  6478  6759 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 11:36:58.807  6478  6713 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 11:36:58.807  6478  6713 D BluetoothAdapterProperties: ScanMode =  20
09-02 11:36:58.807  6478  6713 D BluetoothAdapterProperties: State =  11
09-02 11:36:58.808  6478  6713 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 11:36:58.808  6478  6713 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 11:36:58.808  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:58.798  6825  6825 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:58.798  6825  6825 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:58.809  6478  6713 D BluetoothAdapterProperties: Setting state to 12
09-02 11:36:58.809  6478  6713 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 11:36:58.809  6478  6716 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 11:36:58.810  6478  6713 I BluetoothAdapterState: Entering On State
09-02 11:36:58.810  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:36:58.810  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 11:36:58.810  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-02 11:36:58.810  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:58.812  6478  6716 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 11:36:58.817  6478  6713 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 11:36:58.817  6478  6713 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 11:36:58.817  1036  1036 D BluetoothHeadset: Proxy object connected
09-02 11:36:58.817  6478  6713 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-02 11:36:58.818  6478  6823 E bt_mct  : hci lib postload completed
09-02 11:36:58.818  6478  6757 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:36:58.818  6478  6757 W bt-smp  : Plain text(LSB ~ MSB) = 69 c2 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:36:58.818  6478  6757 W bt-smp  : Encrypted text(LSB ~ MSB) = 11 1c 5b dd eb 94 a8 91 7e 1b 04 b5 d8 f4 95 ef 
09-02 11:36:58.818  6478  6757 W bt-btm  : Stopping oneshot timer
,09-02 11:36:58.820  6319  6335 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 11:36:58.821  6478  6713 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 11:36:58.823  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:58.824  1851  1851 D BluetoothHeadset: Proxy object connected
09-02 11:36:58.824  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:36:58.825  6319  6334 D BluetoothMap: onBluetoothStateChange: up=true
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:58.826  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:58.829  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:36:58.831  1036  1036 D BluetoothA2dp: Proxy object connected
09-02 11:36:58.832  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:58.833  6319  6319 D BluetoothInputDevice: Proxy object connected
,09-02 11:36:58.833  6319  6319 D HidProfile: Bluetooth service connected
09-02 11:36:58.835  1851  1851 D BluetoothHeadset: Proxy object connected
09-02 11:36:58.836  6319  6335 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 11:36:58.837  6319  6319 D BluetoothMap: Proxy object connected
09-02 11:36:58.837  6319  6319 D MapProfile: Bluetooth service connected
09-02 11:36:58.837  6319  6319 D BluetoothMap: getConnectedDevices()
09-02 11:36:58.837  6319  6334 D BluetoothPan: onBluetoothStateChange on: true
09-02 11:36:58.837  6319  6334 D BluetoothPan: onBluetoothStateChange call bindService
09-02 11:36:58.838  6478  6743 V BluetoothMapService: getConnectedDevices()
09-02 11:36:58.841  1851  4341 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:58.848  6478  6757 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:36:58.848  6478  6757 W bt-smp  : Plain text(LSB ~ MSB) = 21 3e 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:36:58.848  6478  6757 W bt-smp  : Encrypted text(LSB ~ MSB) = ca 46 aa 85 40 5e 63 d8 97 ee 09 b7 fe 71 ca 36 
09-02 11:36:58.848  6478  6757 W bt-btm  : Stopping oneshot timer
,09-02 11:36:58.859  6478  6713 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 11:36:58.862  6478  6757 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:36:58.862  6478  6757 W bt-smp  : Plain text(LSB ~ MSB) = 3d ff 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:36:58.862  6478  6757 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 49 33 8c eb ef b5 06 dc 34 bc d9 f6 23 71 7c 
09-02 11:36:58.862  6478  6757 W bt-btm  : Stopping oneshot timer
,09-02 11:36:58.867  6832  6832 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-02 11:36:58.873  6478  6757 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:36:58.873  6478  6757 W bt-smp  : Plain text(LSB ~ MSB) = cf a4 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:36:58.873  6478  6757 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 93 9b cf 5d 84 7d 4d 68 2b 07 72 ae a3 e4 b0 
09-02 11:36:58.873  6478  6757 W bt-btm  : Stopping oneshot timer
09-02 11:36:58.880  6478  6716 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 11:36:58.880  6478  6716 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 11:36:58.883  6478  6757 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-02 11:36:58.883  6478  6757 W bt-smp  : Plain text(LSB ~ MSB) = 83 dc 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:36:58.883  6478  6757 W bt-smp  : Encrypted text(LSB ~ MSB) = cd bb 3a 29 43 a0 58 e2 66 21 fa b2 38 fe 86 b2 
09-02 11:36:58.883  6478  6757 W bt-btm  : Stopping oneshot timer
09-02 11:36:58.964  1036  2012 I art     : Explicit concurrent mark sweep GC freed 131138(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.479ms total 122.721ms
09-02 11:36:58.965  1851  1851 D BluetoothHeadset: Proxy object connected
09-02 11:36:58.965  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 11:36:58.965  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-02 11:36:58.966  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 11:36:58.967  1036  1118 D BluetoothManagerService: Message: 40
09-02 11:36:58.967  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 11:36:58.967  6319  6319 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 11:36:58.967  6319  6319 D PanProfile: Bluetooth service connected
09-02 11:36:58.968  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 11:36:58.969  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:58.969  1942  2110 D LGBluetoothAPIService: Message: 1
09-02 11:36:58.969  1942  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 11:36:58.970  6204  6204 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 11:36:58.971  1942  2110 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-02 11:36:58.972  6478  6478 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:58.973  6478  6478 D BluetoothMapService: STATE_ON
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:58.973  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:36:58.974  6319  6319 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 11:36:58.975  6478  6478 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 11:36:58.976  6478  6478 D LGBluetoothAPIServer: [BTUI] onBind()
09-02 11:36:58.976  1036  1118 D BluetoothManagerService: Message: 30
09-02 11:36:58.978  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 11:36:58.978  1942  2110 D LGBluetoothAPIService: Message: 100
09-02 11:36:58.978  1942  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-02 11:36:58.981  6319  6319 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-02 11:36:58.982  1036  1118 D BluetoothManagerService: Message: 30
09-02 11:36:58.985  6319  6319 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 11:36:58.986  6319  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 11:36:58.988  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:58.988  6478  6478 V BluetoothPbapService: Pbap Service onCreate
09-02 11:36:58.988  6478  6478 V BluetoothPbapService: Starting PBAP service
09-02 11:36:58.988  6319  6319 D BluetoothA2dp: Proxy object connected
09-02 11:36:58.989  6319  6319 D A2dpProfile: Bluetooth service connected
09-02 11:36:58.989  6478  6478 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 11:36:58.989  6478  6478 V BluetoothPbapService: Pbap Service onBind
,09-02 11:36:58.991  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:58.991  6478  6478 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:58.991  6478  6478 V BluetoothPbapService: state: 12
09-02 11:36:58.991  6478  6478 V BluetoothMapService: Handler(): got msg=1
09-02 11:36:58.992  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:58.992  6478  6478 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 11:36:58.993  6478  6478 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 11:36:58.993  6478  6478 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:58.993  6478  6478 V BluetoothPbapReceiver: ***********state = 12
09-02 11:36:58.994  6478  6478 V BluetoothPbapService: Handler(): got msg=1
09-02 11:36:58.994  6478  6834 D BluetoothMapMasInstance: MAS initSocket()
09-02 11:36:58.995  6478  6834 D BluetoothMapMasInstance:   masId = 00
09-02 11:36:58.995  6478  6834 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 11:36:58.995  6478  6834 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 11:36:58.995  6478  6834 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 11:36:58.997  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:36:58.997  2080  2080 D c       : Getting all permits...
09-02 11:36:58.997  2080  2080 D a       : Opening database...
09-02 11:36:58.999  2080  2080 D a       : Opening database auth.proximity.permit_store...
09-02 11:36:59.000  2080  2080 D a       : Closing database...
09-02 11:36:59.000  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:59.002  6478  6478 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 11:36:59.002  6319  6319 D BluetoothHeadset: Proxy object connected
09-02 11:36:59.003  6478  6834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:36:59.003  6319  6319 D HeadsetProfile: Bluetooth service connected
09-02 11:36:59.003  6478  6835 V BluetoothPbapService: Pbap Service initSocket
09-02 11:36:59.004  1036  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:59.004  6478  6835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:36:59.005  6478  6835 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 11:36:59.005  6478  6716 D BluetoothAdapterProperties: Scan Mode:21
09-02 11:36:59.005  6478  6716 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 11:36:59.005  6478  6835 V BluetoothPbapService: Succeed to create listening socket 
09-02 11:36:59.006  6478  6835 V BluetoothPbapService: Accepting socket connection...
,09-02 11:36:59.009  6478  6834 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 11:36:59.009  6478  6834 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 11:36:59.009  6478  6834 D BluetoothMapMasInstance: Accepting socket connection...
09-02 11:36:59.010  6319  6319 D DockEventReceiver: finishStartingService: stopping service
09-02 11:36:59.010  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:59.010  6319  6319 D BluetoothPbap: Proxy object connected
09-02 11:36:59.010  6319  6319 D PbapServerProfile: Bluetooth service connected
09-02 11:36:59.011  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:59.014  6319  6319 D BluetoothPermissionRequest: onReceive
09-02 11:36:59.015  6319  6319 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 11:36:59.016  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:36:59.019  6478  6478 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 11:36:59.019  6478  6478 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-02 11:36:59.025  6478  6478 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-02 11:36:59.044  6478  6478 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 11:36:59.044  6478  6478 V BtOppService: onCreate
,09-02 11:36:59.048  6478  6478 V BluetoothOppNotification: send message
09-02 11:36:59.053  6478  6839 V BtOppService: Deleted complete outbound shares, number =  0
09-02 11:36:59.054  6478  6839 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 11:36:59.055  6478  6839 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-02 11:36:59.056  6478  6839 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@63c6a62 on behalf of 
09-02 11:36:59.056  1036  1923 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6840 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-02 11:36:59.057  1036  1923 I ActivityManager: Killing 5998:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-02 11:36:59.095  6478  6478 V BtOppService: Starting RfcommListener
,09-02 11:36:59.097  6478  6478 D BluetoothOppPreference: Dumping Names:  
09-02 11:36:59.097  6478  6478 D BluetoothOppPreference: {}
09-02 11:36:59.097  6478  6478 D BluetoothOppPreference: Dumping Channels:  
09-02 11:36:59.097  6478  6478 D BluetoothOppPreference: {}
09-02 11:36:59.098  6478  6478 V BtOppService: onStartCommand
09-02 11:36:59.098  1036  1626 W libprocessgroup: failed to open /acct/uid_10080/pid_5998/cgroup.procs: No such file or directory
09-02 11:36:59.099  6478  6859 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 11:36:59.099  6478  6859 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 11:36:59.100  6478  6478 V BluetoothOppNotification: new notify threadi!
09-02 11:36:59.100  6478  6859 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10a6acb0 on behalf of 
09-02 11:36:59.101  6478  6478 V BluetoothOppNotification: send delay message
09-02 11:36:59.101  6478  6859 V BluetoothOppNotification: update too frequent, put in queue
09-02 11:36:59.102  6478  6478 V BtOppService: ContentObserver received notification
09-02 11:36:59.102  6478  6478 V BtOppService: ContentObserver received notification
09-02 11:36:59.102  6478  6478 V BtOppService: start RfcommListener
09-02 11:36:59.105  6478  6478 V BtOppService: RfcommListener started
09-02 11:36:59.105  6478  6861 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 11:36:59.106  1036  1626 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:59.106  6478  6859 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 11:36:59.106  6478  6478 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:59.106  6478  6860 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 11:36:59.106  6478  6478 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 11:36:59.107  6478  6861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:36:59.108  6478  6859 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-02 11:36:59.109  6478  6859 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fb55729 on behalf of 
09-02 11:36:59.110  6478  6861 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-02 11:36:59.110  6478  6860 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@137acaae on behalf of 
09-02 11:36:59.110  6478  6861 V BtOppRfcommListener: Started RFCOMM listener....
09-02 11:36:59.110  6478  6861 I BtOppRfcommListener: Accept thread started.
09-02 11:36:59.110  6478  6861 V BtOppRfcommListener: Accepting connection...
09-02 11:36:59.112  6478  6859 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 11:36:59.112  6478  6860 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 11:36:59.114  6478  6860 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 11:36:59.115  6478  6860 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@259d804f on behalf of 
09-02 11:36:59.115  6478  6860 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 11:36:59.117  6478  6860 V BluetoothOppNotification: outbound notification was removed.
09-02 11:36:59.117  6478  6860 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 11:36:59.118  6478  6860 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d41e3dc on behalf of 
09-02 11:36:59.118  6478  6860 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-02 11:36:59.123  6478  6860 V BluetoothOppNotification: inbound notification was removed.
09-02 11:36:59.123  6478  6860 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 11:36:59.125  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:59.125  6478  6478 V BluetoothFtpService: Ftp Service onCreate
09-02 11:36:59.125  6478  6478 I BluetoothFtpService: Ftp Service onCreate
09-02 11:36:59.125  6478  6478 V BluetoothFtpService: Ftp Service onStartCommand
09-02 11:36:59.125  6478  6478 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:59.125  6478  6860 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@102ce3ba on behalf of 
09-02 11:36:59.125  6478  6478 V BluetoothFtpService: Starting Listening on sockets
09-02 11:36:59.126  6478  6478 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:36:59.126  6478  6478 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 11:36:59.126  6478  6478 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 11:36:59.126  6478  6478 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:59.126  6478  6478 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 11:36:59.126  6478  6478 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 11:36:59.127  6478  6478 V BluetoothFtpService: Handler(): got msg=1
09-02 11:36:59.128  6478  6478 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 11:36:59.128  6478  6478 V BluetoothFtpService: Ftp Service initSocket
09-02 11:36:59.130  6840  6840 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
09-02 11:36:59.131  6840  6840 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
09-02 11:36:59.131  1036  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:59.132  6478  6478 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:36:59.134  6478  6478 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-02 11:36:59.134  6478  6478 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 11:36:59.135  6478  6862 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-02 11:36:59.137  6840  6840 V DrmService: Service onCreate
09-02 11:36:59.137  6840  6840 D DrmService: Received new request = 2
09-02 11:36:59.140  6840  6863 I DrmSntpClient: Start Sync process
09-02 11:36:59.141  6840  6863 D DrmSntpClient: Server : 0
09-02 11:36:59.148  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:36:59.148  6478  6478 V BluetoothSapService: Sap Service onCreate
,09-02 11:36:59.157  1036  1885 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6864 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 11:36:59.158  6478  6478 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:59.158  6478  6478 V BluetoothSapService: state: 12
09-02 11:36:59.159  6478  6478 V BluetoothSapService: Starting SAP server process
,09-02 11:36:59.148  6874  6874 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:59.148  6874  6874 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:36:59.159  6840  6863 D DrmSntpClient: Automatic sync but WiFi isn't enabled
09-02 11:36:59.160  6840  6840 D DrmService: Completed !! request = 2
09-02 11:36:59.160  6840  6840 D DrmService: Request count = 0
09-02 11:36:59.161  6478  6478 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-02 11:36:59.163  6840  6840 V DrmService: Service onDestroy
09-02 11:36:59.163  6478  6875 V BluetoothSapService: Sap Service initRfcommSocket
09-02 11:36:59.165  1036  1051 I ActivityManager: Killing 6025:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-02 11:36:59.166  6874  6874 V BT_SAP  : Event pipe created
09-02 11:36:59.166  6874  6874 V BT_SAP  : create_server_socket qcom.sap.server
09-02 11:36:59.166  6874  6874 V BT_SAP  : created socket fd 6
09-02 11:36:59.204  1036  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:36:59.204  1036  1626 W libprocessgroup: failed to open /acct/uid_10097/pid_6025/cgroup.procs: No such file or directory
,09-02 11:36:59.205  6478  6875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:36:59.212  6478  6875 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-02 11:36:59.212  6478  6875 V BluetoothSapService: Succeed to create listening socket 
09-02 11:36:59.212  6478  6875 V BluetoothSapService: Accepting socket connection...
09-02 11:36:59.229  6864  6864 I art     : Almond Protected OAT
,09-02 11:36:59.288  6864  6864 D WeatherApplication: removeAccount
,09-02 11:36:59.289  6864  6864 D WeatherApplication: Account.length = 0
09-02 11:36:59.289  6864  6864 E WeatherApplication: OPERATOR:OPEN
09-02 11:36:59.294  6864  6864 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:36:59
,09-02 11:36:59.297  6864  6864 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 11:36:59.297  6864  6864 D Weather.Utils: 2 : All the weather widget is gone.
09-02 11:36:59.299  6864  6864 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 11:36:59.302  6864  6864 D WeatherAncestor: connectivity changed - connection : true
09-02 11:36:59.303  6864  6864 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-02 11:36:59.317  6864  6864 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-02 11:36:59.318  6864  6864 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 11:36:59.318  6864  6864 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-02 11:36:59.350  6864  6864 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-02 11:36:59.350  6864  6864 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:36:59
,09-02 11:36:59.438  1036  1903 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6887 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 11:36:59.441  1036  1903 I ActivityManager: Killing 6062:com.lge.eula/1000 (adj 15): empty #17
,09-02 11:36:59.484  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6062/cgroup.procs: No such file or directory
,09-02 11:36:59.635   280   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 11:36:59.635   280   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 11:36:59.636   280   420 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 11:36:59.639  6887  6905 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-02 11:36:59.645   280   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 11:36:59.645   280   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 11:36:59.645   280   420 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 11:36:59.646  6887  6905 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-02 11:36:59.660   280   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 11:36:59.660   280   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 11:36:59.660   280   420 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 11:36:59.664  6887  6909 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-02 11:36:59.667   280   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 11:36:59.667   280   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 11:36:59.667   280   420 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 11:36:59.670  6887  6909 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-02 11:36:59.760  1036  1535 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:36:59.761  1036  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 11:36:59.833  1036  1536 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-02 11:36:59.834  1036  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 11:36:59.913  6887  6887 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 11:36:59.930  6887  6887 I LibraryLoader: Loading: webviewchromium
,09-02 11:36:59.934  6887  6887 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5466-5471)
09-02 11:36:59.935  6887  6887 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 11:36:59.941  6887  6887 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {859ec4d}
,09-02 11:36:59.943  6887  6887 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 11:36:59.944  6887  6887 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 11:36:59.958  6887  6887 I BrowserStartupController: Initializing chromium process, renderers=0
,09-02 11:36:59.959  6887  6887 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 11:36:59.974  6887  6887 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-02 11:36:59.975  6887  6887 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,09-02 11:36:59.975   319  2195 V AudioPolicyService: registerClient() client 0xb04105c0, uid 10093
,09-02 11:36:59.975  6887  6887 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-02 11:36:59.979  6887  6929 W AudioManagerAndroid: Requires BLUETOOTH permission
09-02 11:36:59.994  6887  6887 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 11:36:59.994  6887  6887 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 11:36:59.994  6887  6887 I Adreno-EGL: Build Date: 12/12/14 금
09-02 11:36:59.994  6887  6887 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 11:36:59.994  6887  6887 I Adreno-EGL: Remote Branch: 
09-02 11:36:59.994  6887  6887 I Adreno-EGL: Local Patches: 
09-02 11:36:59.994  6887  6887 I Adreno-EGL: Reconstruct Branch: 
,09-02 11:37:00.001  1036  1398 D PowerManagerServiceEx: acquireWakeLockInternal: lock=136832183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
09-02 11:37:00.037  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,09-02 11:37:00.047  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-02 11:37:00.047  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
09-02 11:37:00.047  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-02 11:37:00.048  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
09-02 11:37:00.049  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
09-02 11:37:00.049  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-02 11:37:00.050  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-02 11:37:00.051  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,09-02 11:37:00.087  6887  6887 I NSApplication: Starting up...
,09-02 11:37:00.104  6478  6478 V BluetoothOppNotification: new notify threadi!
09-02 11:37:00.104  6478  6478 V BluetoothOppNotification: send delay message
,09-02 11:37:00.106  6478  6942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-02 11:37:00.110  6478  6942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30b58186 on behalf of 
09-02 11:37:00.111  6478  6942 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 11:37:00.113  6478  6942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 11:37:00.114  6478  6942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e632a47 on behalf of 
09-02 11:37:00.115  6478  6942 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-02 11:37:00.117  6478  6942 V BluetoothOppNotification: outbound notification was removed.
09-02 11:37:00.117  6478  6942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 11:37:00.120  6478  6942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@104d274 on behalf of 
09-02 11:37:00.121  6478  6942 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 11:37:00.123  6478  6942 V BluetoothOppNotification: inbound notification was removed.
09-02 11:37:00.124  6478  6942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 11:37:00.125  6478  6942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20e5239d on behalf of 
09-02 11:37:00.148  1036  1904 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6943 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-02 11:37:00.150  1036  1941 I ActivityManager: Killing 5918:com.android.vending/u0a44 (adj 15): empty #17
09-02 11:37:00.207  1036  2050 W libprocessgroup: failed to open /acct/uid_10044/pid_5918/cgroup.procs: No such file or directory
,09-02 11:37:00.250  6943  6943 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 11:37:00.533  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 11:37:00.539  3674  6317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 11:37:00.556  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:37:00.565  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 11:37:00.566  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 11:37:00.566  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 11:37:00.566  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 11:37:00.567  6688  6688 I AppUp4:CustModeStarterReceiver: onReceive
09-02 11:37:00.570  6688  6688 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20096d08
09-02 11:37:00.570  6688  6688 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 11:37:00.570  6688  6688 D AppUp4:CustFacade: isPhone : true
,09-02 11:37:00.570  6688  6688 D AppUp4:CustModeStarterReceiver: begin check event
09-02 11:37:00.571  6688  6688 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 11:37:00.574  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 11:37:00.574  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 11:37:00.577  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:37:00.580  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:37:00.587  6726  6726 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 11:37:00.599  4241  6976 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 11:37:00.603  4241  6979 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 11:37:00.603  4241  6979 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 11:37:00.604  6726  6978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:00.613  3306  3306 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 11:37:00.613  3306  3306 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:37:00.615  3306  3306 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 11:37:00.617  6777  6777 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 11:37:00.617  6777  6777 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 11:37:00.619  6428  6982 W FormManager: Network not available. Please check & try again.
09-02 11:37:00.631  6864  6864 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:0
,09-02 11:37:00.635  6428  6984 V FormManager: Network unavailable.
09-02 11:37:00.635  6864  6864 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 11:37:00.635  6864  6864 D Weather.Utils: 2 : All the weather widget is gone.
09-02 11:37:00.636  6864  6864 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 11:37:00.636  6864  6864 D WeatherAncestor: connectivity changed - connection : true
09-02 11:37:00.637  6864  6864 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@32609ec6
09-02 11:37:00.637  6864  6864 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 11:37:00.637  6864  6864 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 11:37:00.637  6864  6864 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 11:37:00.637  6864  6864 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 11:37:00.638  6864  6864 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:0
09-02 11:37:00.638  6428  6984 V FormManager: Network unavailable.
09-02 11:37:00.663  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 11:37:00.664  3674  6317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-02 11:37:00.670  1036  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:00.670  1036  1959 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15164865 mBinding = false
09-02 11:37:00.687  2080  2080 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:37:00.693  1036  1118 D BluetoothManagerService: Message: 2
09-02 11:37:00.694  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:37:00.694  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:37:00.694  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-02 11:37:00.698  1036  1118 D BluetoothManagerService: Sending off request.
09-02 11:37:00.699  6478  6493 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,09-02 11:37:00.700  6478  6713 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 11:37:00.700  6478  6713 D BluetoothAdapterProperties: Setting state to 13
09-02 11:37:00.700  6478  6713 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 11:37:00.701  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:37:00.701  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 11:37:00.701  6478  6713 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 11:37:00.701  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 11:37:00.701  6478  6713 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 11:37:00.704  6478  6716 D BluetoothAdapterProperties: Scan Mode:20
09-02 11:37:00.704  6478  6713 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-02 11:37:00.705  6478  6713 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 11:37:00.705  6478  6835 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:37:00.705  6478  6875 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 11:37:00.705  6478  6834 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 11:37:00.707  6319  6319 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-02 11:37:00.707  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 11:37:00.708  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.709  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:37:00.710  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:37:00.710  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 11:37:00.710  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:37:00.710  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:37:00.711  6478  6861 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:37:00.711  6478  6478 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.711  6478  6862 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:37:00.712  6478  6478 D BluetoothMapService: STATE_TURNING_OFF
09-02 11:37:00.712  6478  6478 V Blue,toothMapService: Handler(): got msg=4
09-02 11:37:00.712  6478  6757 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 11:37:00.712  6478  6478 D BluetoothMapService: MAP Service closeService in
09-02 11:37:00.712  6478  6478 D BluetoothMapMasInstance: MAP Service shutdown
09-02 11:37:00.714  6478  6478 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 11:37:00.714  6478  6478 V BluetoothMapService: MAP Service closeService out
09-02 11:37:00.714  6478  6478 V BtOppService: Receiver DISABLED_ACTION 
09-02 11:37:00.715  6478  6478 I BtOppRfcommListener: stopping Accept Thread
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:37:00.715  6478  6478 V BtOppRfcommListener: close mBtServerSocket
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 11:37:00.715  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 11:37:00.715  6478  6757 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 11:37:00.715  6478  6478 V BtOppRfcommListener: waiting for thread to terminate
09-02 11:37:00.715  6478  6861 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 11:37:00.716  6478  6478 V BtOppRfcommListener: done waiting for thread to terminate
09-02 11:37:00.717  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:37:00.717  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:37:00.718  6478  6478 V BtOppService: onDestroy
,09-02 11:37:00.719  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:37:00.719  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:37:00.723  6478  6478 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 11:37:00.724  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:00.725  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:00.728  6319  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 11:37:00.729  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 11:37:00.729  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 11:37:00.729  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 11:37:00.729  6688  6688 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 11:37:00.733  6688  6688 I AppUp4:CustModeStarterReceiver: onReceive
09-02 11:37:00.734  6478  6478 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 11:37:00.734  6478  6478 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.735  6478  6478 V BluetoothPbapReceiver: ***********state = 13
09-02 11:37:00.736  6319  6319 D DockEventReceiver: finishStartingService: stopping service
09-02 11:37:00.736  6478  6478 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-02 11:37:00.737  6478  6478 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.737  6478  6478 V BluetoothPbapService: state: 13
09-02 11:37:00.738  6478  6478 V BluetoothPbapService: Pbap Service closeService in
09-02 11:37:00.738  6688  6688 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20096d08
09-02 11:37:00.738  6688  6688 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 11:37:00.738  6688  6688 D AppUp4:CustFacade: isPhone : true
09-02 11:37:00.738  6688  6688 D AppUp4:CustModeStarterReceiver: begin check event
09-02 11:37:00.739  6688  6688 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 11:37:00.740  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:37:00.741  6319  6319 D BluetoothPbap: Proxy object disconnected
09-02 11:37:00.741  6319  6319 D PbapServerProfile: Bluetooth service disconnected
09-02 11:37:00.741  6478  6478 V BluetoothPbapService: successfully stopped pbap service
09-02 11:37:00.741  6478  6478 V BluetoothPbapService: Pbap Service closeService out
09-02 11:37:00.741  6478  6478 V BluetoothPbapService: Pbap Service onDestroy
09-02 11:37:00.742  6478  6478 V BluetoothPbapService: Pbap Service closeService in
09-02 11:37:00.742  6478  6478 V BluetoothPbapService: Pbap Service closeService out
09-02 11:37:00.742  6478  6478 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-02 11:37:00.748  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:37:00.748  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 11:37:00.749  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:37:00.755  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:37:00.757  6319  6319 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 11:37:00.761  6319  6319 D BluetoothPermissionRequest: onReceive
09-02 11:37:00.761  6319  6319 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 11:37:00.763  4241  6996 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 11:37:00.763  6726  6726 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 11:37:00.765  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:37:00.767  4241  6997 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 11:37:00.767  4241  6997 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 11:37:00.769  6478  6478 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 11:37:00.770  6478  6478 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 11:37:00.770  6478  6478 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 11:37:00.775  6478  6478 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.775  6478  6478 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-02 11:37:00.776  6478  6478 V BluetoothFtpService: Ftp Service onStartCommand
09-02 11:37:00.776  6478  6478 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.776  6478  6478 V BluetoothFtpService: Ftp Service closeService
09-02 11:37:00.777  6478  6478 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 11:37:00.778  6478  6478 V BluetoothFtpService: successfully stopped ftp service
09-02 11:37:00.778  6478  6478 V BluetoothFtpService: Ftp Service onDestroy
09-02 11:37:00.778  6478  6478 V BluetoothFtpService: Ftp Service closeService
09-02 11:37:00.781  6726  6998 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:00.782  6428  7000 W FormManager: Network not available. Please check & try again.
09-02 11:37:00.782  6478  6478 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:37:00.783  6478  6478 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 11:37:00.783  6478  6478 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 11:37:00.783  6478  6478 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.783  6478  6478 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 11:37:00.783  6478  6478 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 11:37:00.785  6478  6478 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:00.785  6478  6478 V BluetoothSapService: state: 13
09-02 11:37:00.786  6478  6478 V BluetoothSapService: Stopping SAP server process
09-02 11:37:00.786  6478  6478 V BluetoothSapService: Sap Service closeSapService in
09-02 11:37:00.786  6478  6478 V BluetoothSapService: Close listen Socket : 
09-02 11:37:00.786  6478  6478 V BluetoothSapService: Close rfcomm Socket : 
09-02 11:37:00.787  6478  6478 V BluetoothSapService: Close sapd  Socket : 
,09-02 11:37:00.790  6478  6478 V BluetoothSapService: Sap Service closeSapService out
09-02 11:37:00.790  6478  6478 V BluetoothSapService: Sap Service onDestroy
09-02 11:37:00.791  6478  6478 V BluetoothSapService: Sap Service closeSapService in
09-02 11:37:00.791  6478  6478 V BluetoothSapService: Close listen Socket : 
09-02 11:37:00.791  6478  6478 V BluetoothSapService: Close rfcomm Socket : 
09-02 11:37:00.791  6478  6478 V BluetoothSapService: Close sapd  Socket : 
09-02 11:37:00.791  6478  6478 V BluetoothSapService: Sap Service closeSapService out
09-02 11:37:00.794  3306  3306 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 11:37:00.794  3306  3306 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 11:37:00.795  3306  3306 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 11:37:00.798  6428  7001 V FormManager: Network unavailable.
09-02 11:37:00.799  6777  6777 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 11:37:00.800  6777  6777 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-02 11:37:00.804  6428  7001 V FormManager: Network unavailable.
09-02 11:37:00.810  6864  6864 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:0
09-02 11:37:00.811  6864  6864 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-02 11:37:00.811  6864  6864 D Weather.Utils: 2 : All the weather widget is gone.
09-02 11:37:00.812  6864  6864 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 11:37:00.812  6864  6864 D WeatherAncestor: connectivity changed - connection : true
09-02 11:37:00.812  6864  6864 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@32609ec6
09-02 11:37:00.813  6864  6864 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 11:37:00.813  6864  6864 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 11:37:00.813  6864  6864 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 11:37:00.813  6864  6864 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 11:37:00.813  6864  6864 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:0
09-02 11:37:00.837  6385  6385 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-02 11:37:00.837  6385  6385 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6855
09-02 11:37:00.838  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=136832183 [*alarm*], flags=0x0
,09-02 11:37:01.672  6478  6716 D bt_hci_bdroid: cleanup
,09-02 11:37:01.679  6478  6759 I bt_lpm  : LPM is already off!!!
09-02 11:37:01.680  6478  6757 W bt-btif : ag scb idx 1 not allocated
09-02 11:37:01.681  6478  6757 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:37:01.681  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 11:37:01.682  6478  6757 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:37:01.682  6478  6757 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 11:37:01.682  6478  6757 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 11:37:01.682  6478  6757 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 11:37:01.686  6478  6823 I bt_userial_mct: exiting userial_read_thread
09-02 11:37:01.686  6478  6823 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 11:37:01.686  6478  6716 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 11:37:01.686  6478  6759 I bt_vendor: hw_epilog_process
09-02 11:37:01.686  6478  6716 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 11:37:01.686  6478  6716 D bt_userial_mct: userial_close
09-02 11:37:01.686  6478  6716 E bt_userial_mct: pthread_join() FAILED result:3
09-02 11:37:01.686  6478  6716 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 11:37:01.694  6478  6716 D bt_hci_bdroid: set_power 0
09-02 11:37:01.694  6478  6716 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 11:37:01.694  6478  6716 I bt_vendor: bluetooth satus is on
09-02 11:37:01.694  6478  6716 I bt_vendor: bt-vendor : resetting BT status
09-02 11:37:01.694  6478  6716 I bt_vendor: Starting hciattach daemon
09-02 11:37:01.694  6478  6716 I bt_vendor: try to set false
,09-02 11:37:01.700  6478  6716 I bt_vendor: Starting hciattach daemon
09-02 11:37:01.700  6478  6716 I bt_vendor: try to set false
09-02 11:37:01.701  6478  6716 I bt_vendor: cleanup
09-02 11:37:01.702  6478  6757 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 11:37:01.703  6478  6716 I GKI_LINUX: GKI_exit_task 0 done
09-02 11:37:01.703  6478  6716 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 11:37:01.704  6478  6713 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 11:37:01.707  6478  6478 D HeadsetService: Received stop request...Stopping profile...
,09-02 11:37:01.710  6478  6478 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 11:37:01.710  6478  6478 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:37:01.711  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:37:01.713  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-02 11:37:01.714  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-02 11:37:01.714  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-02 11:37:01.715  6478  6478 D HeadsetStateMachine: Unbinding service...
09-02 11:37:01.716  6478  6723 D HeadsetStateMachine: Exit Disconnected: -1
09-02 11:37:01.717  1036  1036 D BluetoothHeadset: Proxy object disconnected
09-02 11:37:01.717  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 11:37:01.717  6478  6478 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 11:37:01.717  6478  6478 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 11:37:01.717  6478  6478 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 11:37:01.717  6478  6478 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 11:37:01.718  6478  6478 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 11:37:01.718  6478  6478 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:37:01.718  6478  6478 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 11:37:01.724  6478  6478 D A2dpService: Received stop request...Stopping profile...
,09-02 11:37:01.728  6478  6748 D A2dpStateMachine: Exit Disconnected: -1
09-02 11:37:01.730  6478  6478 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 11:37:01.733  6478  6713 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 11:37:01.734  6478  6478 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 11:37:01.734  6478  6478 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:37:01.734  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:37:01.735  1036  1036 D BluetoothA2dp: Proxy object disconnected
09-02 11:37:01.735  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 11:37:01.736  6478  6478 D HidService: Received stop request...Stopping profile...
09-02 11:37:01.736  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:37:01.739  6478  6478 D HealthService: Received stop request...Stopping profile...
09-02 11:37:01.740  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
,09-02 11:37:01.744  6478  6478 D PanService: Received stop request...Stopping profile...
09-02 11:37:01.745  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:37:01.746  6478  6478 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 11:37:01.748  6478  6478 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 11:37:01.748  6478  6478 D BtGatt.GattService: stop()
09-02 11:37:01.748  6478  6478 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 11:37:01.750  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:37:01.752  6478  6478 D BluetoothMapService: Received stop request...Stopping profile...
09-02 11:37:01.752  6478  6478 D BluetoothMapService: stop()
,09-02 11:37:01.755  6478  6478 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 11:37:01.755  6478  6478 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 11:37:01.756  6478  6478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32609ec6
09-02 11:37:01.757  6478  6478 I BluetoothA2dpServiceJni: cleanupNative
09-02 11:37:01.757  6478  6749 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 11:37:01.758  6478  6478 I GKI_LINUX: GKI_exit_task 2 done
09-02 11:37:01.758  6478  6478 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 11:37:01.758  6478  6478 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 11:37:01.758  6478  6478 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 11:37:01.758  6478  6478 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 11:37:01.759  6478  6478 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 11:37:01.759  6478  6478 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 11:37:01.759  6478  6478 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 11:37:01.759  6478  6478 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 11:37:01.762  6478  6478 V BluetoothMapService: Handler(): got msg=4
09-02 11:37:01.762  6478  6478 D BluetoothMapService: MAP Service closeService in
09-02 11:37:01.762  6478  6478 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 11:37:01.762  6478  6478 V BluetoothMapService: MAP Service closeService out
09-02 11:37:01.764  6478  6713 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 11:37:01.764  6478  6713 D BluetoothAdapterProperties: Setting state to 10
09-02 11:37:01.764  6478  6713 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-02 11:37:01.767  6478  6478 D BluetoothMapService: cleanup()
09-02 11:37:01.767  6478  6478 D BluetoothMapService: MAP Service closeService in
09-02 11:37:01.767  6478  6478 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 11:37:01.767  6478  6478 V BluetoothMapService: MAP Service closeService out
09-02 11:37:01.768  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:37:01.768  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 11:37:01.769  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-02 11:37:01.769  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:37:01.769  6478  6713 I BluetoothAdapterState: Entering OffState
09-02 11:37:01.772  6319  6335 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 11:37:01.772  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:37:01.773  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 11:37:01.774  6319  6335 D BluetoothMap: onBluetoothStateChange: up=false
09-02 11:37:01.774  6319  6335 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 11:37:01.776  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 11:37:01.779  6319  6335 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 11:37:01.779  6319  6335 D BluetoothPan: onBluetoothStateChange on: false
09-02 11:37:01.780  1851  2457 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:37:01.781  6319  6335 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:37:01.782  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 11:37:01.782  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 11:37:01.784  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 11:37:01.784  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 11:37:01.784  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@15164865 mBinding = false
09-02 11:37:01.785  1036  1118 D BluetoothManagerService: Sending unbind request.
09-02 11:37:01.790  6478  6716 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 11:37:01.793  6478  6478 I GKI_LINUX: GKI_exit_task 1 done
09-02 11:37:01.793  6478  6478 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 11:37:01.793  6478  6478 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 11:37:01.793  6478  6478 I art     : --- WEIRD: removing null entry 248
09-02 11:37:01.793  6478  6478 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-02 11:37:01.793  6478  6478 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 11:37:01.795  6478  6478 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 11:37:01.796  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 11:37:01.798  6478  6478 I art     : System.exit called, status: 0
09-02 11:37:01.798  6478  6478 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-02 11:37:01.818   319   319 V AudioFlinger: 6478 died, releasing its sessions
09-02 11:37:01.818   319   319 V AudioFlinger:  pid 1851 @ 0
09-02 11:37:01.818   319   319 V AudioFlinger:  pid 3306 @ 1
09-02 11:37:01.818   319   319 V AudioFlinger:  pid 3306 @ 2
,09-02 11:37:01.821  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,09-02 11:37:01.822  1942  2110 D LGBluetoothAPIService: Message: 101
09-02 11:37:01.822  1942  2110 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-02 11:37:01.822  1942  2110 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-02 11:37:01.822  1942  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-02 11:37:01.829  6319  6319 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 11:37:01.923  1036  2012 I ActivityManager: Process com.android.bluetooth (pid 6478) has died
09-02 11:37:01.924  1036  2012 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-02 11:37:01.924  1036  2012 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-02 11:37:01.934  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:01.934  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 11:37:01.935  1942  2110 D LGBluetoothAPIService: Message: 2
09-02 11:37:01.935  1942  2110 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-02 11:37:01.938  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:01.940  6319  6319 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 11:37:01.940  6319  6319 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-02 11:37:01.943  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:37:01.947  6319  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 11:37:01.966  1601  1601 D BluetoothAdapter: 210567513: getState() :  mService = null. Returning STATE_OFF
09-02 11:37:01.966  1601  1601 D BluetoothAdapter: 210567513: getState() :  mService = null. Returning STATE_OFF
,09-02 11:37:02.012  1036  1903 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7032 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-02 11:37:02.014  6319  6319 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:37:02.106  7032  7032 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-02 11:37:02.107  7032  7032 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 11:37:02.107  7032  7032 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 11:37:02.108  7032  7032 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 11:37:02.130  7032  7032 D BluetoothAdapterApp: Loading JNI Library
,09-02 11:37:02.168  7032  7032 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@25cc7fee Instance Count = 1
,09-02 11:37:02.175  7032  7032 D BluetoothAdapterApp: onCreate
09-02 11:37:02.210  7032  7032 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 11:37:02.210  7032  7032 D ProfileConfigQcom: Adding HeadsetService
09-02 11:37:02.210  7032  7032 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 11:37:02.210  7032  7032 D ProfileConfigQcom: Adding A2dpService
09-02 11:37:02.211  7032  7032 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 11:37:02.211  7032  7032 D ProfileConfigQcom: Adding HidService
09-02 11:37:02.211  7032  7032 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 11:37:02.211  7032  7032 D ProfileConfigQcom: Adding HealthService
09-02 11:37:02.212  7032  7032 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-02 11:37:02.213  7032  7032 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 11:37:02.213  7032  7032 D ProfileConfigQcom: Adding PanService
09-02 11:37:02.214  7032  7032 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 11:37:02.214  7032  7032 D ProfileConfigQcom: Adding GattService
09-02 11:37:02.214  7032  7032 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 11:37:02.214  7032  7032 D ProfileConfigQcom: Adding BluetoothMapService
09-02 11:37:02.215  7032  7032 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 11:37:02.216  7032  7032 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-02 11:37:02.217  7032  7032 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:02.217  7032  7032 V BluetoothPbapReceiver: ***********state = 10
09-02 11:37:02.219  7032  7032 V LGMDMManagerInternal: Create singleton instance
09-02 11:37:02.313  7032  7032 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 11:37:02.314  7032  7032 D LGBluetoothAPIServer: [BTUI] onBind()
09-02 11:37:02.318  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-02 11:37:02.318  1942  2110 D LGBluetoothAPIService: Message: 100
09-02 11:37:02.318  1942  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 11:37:02.319  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:37:02.322  6319  6319 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 11:37:02.341  6319  6319 D BluetoothPermissionRequest: onReceive
,09-02 11:37:02.347  6319  6319 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-02 11:37:02.347  6319  6319 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 11:37:02.351  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:37:02.363  7032  7032 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-02 11:37:02.368  7032  7032 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:02.372  7032  7032 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:37:02.372  7032  7032 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 11:37:02.372  7032  7032 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 11:37:02.374  7032  7032 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:02.374  7032  7032 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 11:37:02.378  6402  6402 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-02 11:37:03.698  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 11:37:03.698  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:37:04.671  6887  6907 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-02 11:37:04.856  1036  1543 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-02 11:37:05.553  1036  2050 I ActivityManager: Killing 6088:com.lge.bnr/1000 (adj 15): empty #17
,09-02 11:37:05.590  1036  1959 W libprocessgroup: failed to open /acct/uid_1000/pid_6088/cgroup.procs: No such file or directory
,09-02 11:37:06.711  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:06.711  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d6e245a added. We now have 6 listener(s)
09-02 11:37:06.712  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:37:06.724  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:06.724  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e95168b added. We now have 7 listener(s)
09-02 11:37:06.724  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:06.725  6204  6283 I System.out: IsBluetoothEnabled
09-02 11:37:06.727  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:06.727  1036  1052 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-02 11:37:06.728  1036  1118 D BluetoothManagerService: Message: 2
,09-02 11:37:06.733  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:06.734  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:06.734  1036  2032 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-02 11:37:06.759  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:37:06.759  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:37:06.759  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-02 11:37:06.760  1036  1118 D BluetoothManagerService: Message: 1
09-02 11:37:06.760  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 11:37:06.785  1036  1118 D BluetoothManagerService: Message: 20
09-02 11:37:06.785  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@194314d5:true
,09-02 11:37:06.789  7032  7032 D BluetoothAdapterState: make
09-02 11:37:06.794  7032  7032 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 11:37:06.794  7032  7032 I bluedroid-qcom: init
09-02 11:37:06.796  7032  7064 I BluetoothAdapterState: Entering OffState
09-02 11:37:06.796  7032  7032 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 11:37:06.796  7032  7032 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 11:37:06.796  7032  7032 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 11:37:06.796  7032  7032 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 11:37:06.796  7032  7032 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 11:37:06.798  7032  7032 I bluedroid-qcom: get_profile_interface socket
09-02 11:37:06.798  7032  7032 I bluedroid-qcom: get_profile_interface map_client
,09-02 11:37:06.803  7032  7068 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 11:37:06.798  7067  7067 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:06.798  7067  7067 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:06.814  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-02 11:37:06.817  1036  1118 D BluetoothManagerService: Message: 40
09-02 11:37:06.817  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 11:37:06.818  7032  7047 I bluedroid-qcom: config_hci_snoop_log
09-02 11:37:06.819  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 11:37:06.819  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 11:37:06.824  7067  7067 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 11:37:06.824  7067  7067 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 11:37:06.825  7032  7068 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 11:37:06.826  7067  7067 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-02 11:37:06.829  7067  7067 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-02 11:37:06.830  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 11:37:06.830  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 11:37:06.830  7032  7068 D BluetoothAdapterProperties: Name is: G3
09-02 11:37:06.838  7067  7067 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 11:37:06.838  7067  7067 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-02 11:37:06.842  7032  7064 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 11:37:06.842  7032  7064 D BluetoothAdapterProperties: Setting state to 11
09-02 11:37:06.843  7032  7064 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 11:37:06.844  7032  7064 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 11:37:06.847  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:37:06.847  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 11:37:06.847  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 11:37:06.851  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 11:37:06.853  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 11:37:06.857  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:06.858  6319  6319 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-02 11:37:06.877  7032  7032 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 11:37:06.877  7032  7032 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:06.877  7032  7032 V BluetoothPbapReceiver: ***********state = 11
,09-02 11:37:06.884  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:37:06.885  7032  7064 D BluetoothBondStateMachine: make
09-02 11:37:06.889  7032  7082 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 11:37:06.889  7032  7064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:06.890  7032  7064 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,09-02 11:37:06.890  7032  7064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:06.890  7032  7064 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 11:37:06.891  7032  7064 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 11:37:06.896  7032  7064 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:37:06.902  6319  6319 D BluetoothPermissionRequest: onReceive
,09-02 11:37:06.905  7032  7032 D HeadsetService: Received start request. Starting profile...
09-02 11:37:06.905  7032  7032 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 11:37:06.906  7032  7064 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:37:06.906  7032  7032 D LGBluetoothHfpAdapter: Version 1.6
09-02 11:37:06.908  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:37:06.909  7032  7032 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 11:37:06.910  7032  7032 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 11:37:06.911  7032  7032 D HeadsetStateMachine: make
09-02 11:37:06.912  7032  7064 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:37:06.922  7032  7064 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 11:37:06.927  7032  7064 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:37:06.932  7032  7064 E BluetoothAdapterService: File transfer profiles supported!!
09-02 11:37:06.937  7032  7064 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 11:37:06.951  7032  7032 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:37:06.951  7032  7032 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 11:37:06.953  7032  7064 V LGMDMManager: Create singleton instance
,09-02 11:37:06.956  7032  7064 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 11:37:06.956  7032  7032 D HeadsetStateMachine: max_hf_connections = 1
09-02 11:37:06.956  7032  7032 I bluedroid-qcom: get_profile_interface handsfree
09-02 11:37:06.958  7032  7032 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 11:37:06.959   319   319 V AudioPolicyService: registerClient() client 0xb1427180, uid 1002
09-02 11:37:06.959   319  2195 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 11:37:06.959   319  2195 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 11:37:06.959   319  2195 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 11:37:06.960  7032  7032 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 11:37:06.960   319  1383 V AudioFlinger: registerClient() client 0xb14336a0, pid 7032
09-02 11:37:06.960   319  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:37:06.960   319  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:37:06.961   319  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:37:06.961   319  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:37:06.961  1036  1885 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:37:06.961  1036  1885 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:37:06.961  3306  3324 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:37:06.961  1036  1885 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:37:06.961  3306  3324 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:37:06.961  1036  1885 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:37:06.961  3306  3324 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:37:06.961  3306  3324 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:37:06.961  1601  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:37:06.961  1601  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:37:06.961  1601  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:37:06.961  1601  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:37:06.961  1851  4341 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:37:06.961  1851  4341 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 11:37:06.961  1851  4341 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:37:06.961  1851  4341 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 11:37:06.961  7032  7048 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 11:37:06.962  7032  7048 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 11:37:06.962  7032  7048 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 11:37:06.962  7032  7048 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 11:37:06.962  7032  7032 V ToneGenerator: Create Track: 0xb4928080
09-02 11:37:06.962  7032  7032 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 11:37:06.962  7032  7032 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 11:37:06.962   319   319 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 11:37:06.962   319   319 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 11:37:06.962   319   319 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 11:37:06.962   319   319 V Au,dioPolicyManagerEx: getOutput() returns output 2
09-02 11:37:06.962   319  2195 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 11:37:06.963   319  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 11:37:06.963   319  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 11:37:06.963   319  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 11:37:06.963   319  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 11:37:06.963  7032  7032 V AudioSystem: getLatency() output 2, latency 50
09-02 11:37:06.963  7032  7032 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 11:37:06.963  7032  7032 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 11:37:06.963   319  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 11:37:06.963   319  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 11:37:06.963   319  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 11:37:06.963   319  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 11:37:06.963   319  1382 V AudioFlinger: createTrack() lSessionId: 23
09-02 11:37:06.964  7032  7032 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,09-02 11:37:06.965   319   319 V AudioFlinger: acquiring 23 from 7032, for 7032
,09-02 11:37:06.965   319   319 V AudioFlinger:  added new entry for 23
09-02 11:37:06.965  7032  7032 V ToneGenerator: ToneGenerator INIT OK, time: 202502
09-02 11:37:06.965  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:06.967  7032  7086 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 11:37:06.968  7032  7086 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 11:37:06.968  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:06.968  7032  7086 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 11:37:06.968  7032  7086 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 11:37:06.968   319  2195 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7032
09-02 11:37:06.970   319  2195 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 11:37:06.970   319  2195 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 11:37:06.970   319  2195 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 11:37:06.970   319  2195 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 11:37:06.970   319  2195 V voice   : voice_set_parameters: exit with code(0)
09-02 11:37:06.970   319  2195 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 11:37:06.970   319  2195 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 11:37:06.970  7032  7032 D A2dpService: Received start request. Starting profile...
09-02 11:37:06.970   319  2195 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 11:37:06.970   319  2195 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 11:37:06.970   319  2195 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 11:37:06.970   319  2195 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 11:37:06.970  7032  7086 V ToneGenerator: ToneGenerator destructor
09-02 11:37:06.970  7032  7086 V ToneGenerator: stopTone
09-02 11:37:06.971  7032  7032 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 11:37:06.971  7032  7086 V ToneGenerator: Delete Track: 0xb4928080
09-02 11:37:06.971  7032  7086 V AudioTrack: ~AudioTrack, releasing session id from 7032 on behalf of 7032
09-02 11:37:06.971   319  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 11:37:06.971   319  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 11:37:06.971   319  1383 V AudioFlinger: PlaybackThread::Track destructor
09-02 11:37:06.971   319  1273 V AudioPolicyService: AudioCommandThread() waking up
09-02 11:37:06.971   319  1383 V AudioFlinger: removeClient_l() pid 7032, calling pid 319
09-02 11:37:06.971   319  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 11:37:06.971   319  1273 V AudioPolicyManager: releaseOutput() 2
09-02 11:37:06.971   319  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 11:37:06.971   319   319 V AudioFlinger: releasing 23 from 7032 for 7032
09-02 11:37:06.972   319   319 V AudioFlinger:  decremented refcount to 0
09-02 11:37:06.972   319   319 V AudioFlinger: purging stale effects
09-02 11:37:06.972  7032  7032 V Avrcp   : make
09-02 11:37:06.973  7032  7032 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 11:37:06.973  7032  7032 I bluedroid-qcom: get_profile_interface avrcp
09-02 11:37:06.982  7032  7032 V AudioManager: registerRemoteController: size of Media player list: 0
,09-02 11:37:06.984  7032  7032 E AudioManager: No RCC entry present to update
09-02 11:37:06.984  7032  7032 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 11:37:06.988  7032  7032 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 11:37:06.990  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 11:37:06.990  7032  7032 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 11:37:06.994  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 11:37:07.148  1036  1977 V SIM_STK : Menu title from STK is T-Mobile
09-02 11:37:07.148  1036  1977 V SIM_STK : Menu title from STK is T-Mobile
,09-02 11:37:07.276  1036  1923 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 11:37:07.288  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 11:37:07.292  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 11:37:07.293  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 11:37:07.294  7032  7032 I BluetoothA2dpServiceJni: classInitNative
09-02 11:37:07.294  7032  7032 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 11:37:07.294  7032  7032 D A2dpStateMachine: make
09-02 11:37:07.297  7032  7032 I bluedroid-qcom: get_profile_interface a2dp
09-02 11:37:07.297  7032  7099 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-02 11:37:07.303  7032  7032 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 11:37:07.303  7032  7032 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,09-02 11:37:07.304  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:07.305  7032  7032 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 11:37:07.306  7032  7032 D HidService: Received start request. Starting profile...
09-02 11:37:07.306  7032  7032 I bluedroid-qcom: get_profile_interface hidhost
09-02 11:37:07.306  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:07.307  7032  7032 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 11:37:07.308  7032  7032 D HealthService: Received start request. Starting profile...
09-02 11:37:07.309  7032  7032 I bluedroid-qcom: get_profile_interface health
09-02 11:37:07.310  7032  7032 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 11:37:07.310  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:07.310  7032  7098 D A2dpStateMachine: Enter Disconnected: -2
09-02 11:37:07.310  7032  7032 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 11:37:07.314  7032  7032 D PanService: Received start request. Starting profile...
09-02 11:37:07.314  7032  7032 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 11:37:07.314  7032  7032 I bluedroid-qcom: get_profile_interface pan
09-02 11:37:07.321  7032  7032 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 11:37:07.321  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:07.322  7032  7032 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-02 11:37:07.325  7032  7032 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 11:37:07.326  7032  7032 D BtGatt.GattService: Received start request. Starting profile...
09-02 11:37:07.326  7032  7032 D BtGatt.GattService: start()
09-02 11:37:07.326  7032  7032 I bluedroid-qcom: get_profile_interface gatt
09-02 11:37:07.326  7032  7032 D BtGatt.AdvertiseManager: advertise manager created
09-02 11:37:07.330  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:07.331  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:07.332  7032  7032 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 11:37:07.332  7032  7032 V BluetoothMapService: BluetoothMapBinder()
09-02 11:37:07.333  7032  7032 D BluetoothMapService: Received start request. Starting profile...
09-02 11:37:07.333  7032  7032 D BluetoothMapService: start()
09-02 11:37:07.335  7032  7032 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 11:37:07.335  7032  7032 D BluetoothMapEmailAppObserver: createReceiver()
09-02 11:37:07.336  7032  7032 D BluetoothMapEmailAppObserver: initObservers()
09-02 11:37:07.336  7032  7032 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-02 11:37:07.341  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:07.342  7032  7032 D HeadsetStateMachine: Proxy object connected
09-02 11:37:07.342  7032  7032 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 11:37:07.342  7032  7032 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 11:37:07.345  7032  7032 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:37:07.345  7032  7086 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 11:37:07.346  7032  7086 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 11:37:07.346  7032  7086 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 11:37:07.348  7032  7032 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:37:07.350  7032  7032 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 11:37:07.353  7032  7032 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:07.356  7032  7032 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:37:07.357  7032  7032 V PanService: [BTUI] SIM Extra State :ABSENT
09-02 11:37:07.359  7032  7032 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 11:37:07.361  7032  7032 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 11:37:07.361  7032  7032 V BluetoothMapService: Handler(): got msg=1
09-02 11:37:07.362  7032  7032 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:37:07.362  7032  7032 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 11:37:07.362  7032  7032 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 11:37:07.363  7032  7032 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:07.363  7032  7032 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-02 11:37:07.363  7032  7064 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 11:37:07.363  7032  7064 I bluedroid-qcom: enable
09-02 11:37:07.363  7032  7064 I bt_hci_bdroid: init
09-02 11:37:07.364  7032  7106 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 11:37:07.365  7032  7106 I bt-btu  : btu_task pending for preload complete event
09-02 11:37:07.365  7032  7064 I bt_vendor: bt-vendor : init
09-02 11:37:07.365  7032  7064 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 11:37:07.365  7032  7064 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 11:37:07.365  7032  7064 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 11:37:07.365  7032  7064 D bt_userial_mct: userial_init
09-02 11:37:07.366  7032  7064 D bt_hci_bdroid: set_power 1
09-02 11:37:07.366  7032  7064 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 11:37:07.366  7032  7064 I bt_vendor: Starting hciattach daemon
09-02 11:37:07.366  7032  7064 I bt_vendor: try to set true
09-02 11:37:07.358  7109  7109 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:07.358  7109  7109 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:07.393  7110  7110 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 11:37:07.490  7122  7122 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 11:37:07.504  7123  7123 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 11:37:07.532  7125  7125 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 11:37:07.546  7126  7126 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-02 11:37:07.572  7127  7127 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 11:37:07.590  7128  7128 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-02 11:37:07.614  7130  7130 I libmdmdetect: ESOC framework not supported
09-02 11:37:07.616  7130  7130 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 11:37:07.626  7130  7130 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-02 11:37:07.627  7130  7130 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 11:37:07.627  7130  7130 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 11:37:07.627  7130  7130 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 11:37:07.627  7130  7130 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 11:37:07.627  7130  7130 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 11:37:07.627  7130  7130 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 11:37:07.669  7130  7131 E QC-QMI  : qmi_client [7130] 15: failed to locate client data
09-02 11:37:07.671   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 11:37:07.671   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-02 11:37:07.704  7135  7135 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 11:37:07.717  7136  7136 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-02 11:37:07.769  7032  7064 I bt_vendor: bluetooth satus is on
09-02 11:37:07.769  7032  7064 D bt_hci_bdroid: preload
09-02 11:37:07.770  7032  7108 D bt_userial_mct: userial_open(port:0)
,09-02 11:37:07.770  7032  7108 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-02 11:37:07.774  7032  7108 I bt_vendor: Done intiailizing UART
,09-02 11:37:07.777  7032  7108 I bt_vendor: Done intiailizing UART
,09-02 11:37:07.777  7032  7108 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-02 11:37:07.778  7032  7108 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 11:37:07.778  7032  7106 I bt-btu  : btu_task received preload complete event
09-02 11:37:07.779  7032  7138 D bt_userial_mct: Entering userial_read_thread()
09-02 11:37:07.780  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 11:37:07.781  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 11:37:07.788  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 11:37:07.799  7032  7106 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 11:37:07.852  7032  7106 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 11:37:07.852  7032  7106 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020c061 
09-02 11:37:07.852  7032  7106 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020c061 
,09-02 11:37:07.876  7032  7068 E bt-btif : Calling BTA_HhEnable
09-02 11:37:07.876  7032  7068 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 11:37:07.877  7032  7068 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 11:37:07.881  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-02 11:37:07.882  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 11:37:07.882  7032  7068 D BluetoothAdapterProperties: Name is: G3
09-02 11:37:07.886  7032  7068 D BluetoothAdapterProperties: Scan Mode:20
09-02 11:37:07.887  7032  7068 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 11:37:07.887  7032  7068 D bt_hci_bdroid: postload
09-02 11:37:07.889  7032  7068 D bte_conf: Device ID record 1 : primary
09-02 11:37:07.889  7032  7068 D bte_conf:   vendorId            = 00c4
09-02 11:37:07.889  7032  7068 D bte_conf:   vendorIdSource      = 0001
09-02 11:37:07.889  7032  7068 D bte_conf:   product             = 13a1
09-02 11:37:07.889  7032  7068 D bte_conf:   version             = 1000
09-02 11:37:07.889  7032  7068 D bte_conf:   clientExecutableURL = 
09-02 11:37:07.889  7032  7068 D bte_conf:   serviceDescription  = 
09-02 11:37:07.889  7032  7068 D bte_conf:   documentationURL    = 
,09-02 11:37:07.895  7032  7108 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 11:37:07.896  7032  7068 D bte_conf: bte_load_did_conf no section named DID2.
09-02 11:37:07.899  7032  7064 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 11:37:07.899  7032  7064 D BluetoothAdapterProperties: ScanMode =  20
09-02 11:37:07.899  7032  7064 D BluetoothAdapterProperties: State =  11
09-02 11:37:07.899  7032  7064 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 11:37:07.900  7032  7064 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 11:37:07.900  7032  7064 D BluetoothAdapterProperties: Setting state to 12
09-02 11:37:07.900  7032  7064 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 11:37:07.901  7032  7068 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 11:37:07.903  1036  1118 D BluetoothManagerService: Message: 60
09-02 11:37:07.903  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 11:37:07.903  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-02 11:37:07.903  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:37:07.898  7143  7143 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 11:37:07.898  7143  7143 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:07.929  7032  7064 I BluetoothAdapterState: Entering On State
,09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:37:07.943  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:37:07.947  7032  7068 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 11:37:07.947  7032  7068 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 11:37:07.952  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:37:07.955  7032  7108 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 11:37:07.962  7032  7064 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 11:37:07.962  7032  7064 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 11:37:07.962  7032  7064 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-02 11:37:07.965  7032  7064 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 11:37:07.965  1036  1036 D BluetoothHeadset: Proxy object connected
09-02 11:37:07.972  7032  7064 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-02 11:37:07.975  7032  7108 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 11:37:07.976  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 11:37:07.976  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 11:37:07.976  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 11:37:07.976  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 11:37:07.976  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 11:37:07.976  7032  7106 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 11:37:07.977  7032  7068 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 11:37:07.981  7032  7138 E bt_mct  : hci lib postload completed
09-02 11:37:07.981  6319  6335 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 11:37:08.003  7032  7106 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:37:08.003  7032  7106 W bt-smp  : Plain text(LSB ~ MSB) = 73 a0 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:37:08.004  7032  7106 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 3d 6d b9 0f eb 92 cb 44 98 e6 e7 40 90 65 64 
09-02 11:37:08.004  7032  7106 W bt-btm  : Stopping oneshot timer
,09-02 11:37:08.011  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:37:08.022  7149  7149 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-02 11:37:08.027  1851  1851 D BluetoothHeadset: Proxy object connected
,09-02 11:37:08.028  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:37:08.032  1036  1036 D BluetoothA2dp: Proxy object connected
09-02 11:37:08.041  6319  6319 D BluetoothInputDevice: Proxy object connected
09-02 11:37:08.041  6319  6319 D HidProfile: Bluetooth service connected
09-02 11:37:08.041  6319  6335 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 11:37:08.049  7032  7106 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:37:08.049  7032  7106 W bt-smp  : Plain text(LSB ~ MSB) = 5f a6 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:37:08.050  7032  7106 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b ae 52 3e aa 1f 26 4a b3 15 ab ff 5f ce 32 03 
09-02 11:37:08.050  7032  7106 W bt-btm  : Stopping oneshot timer
09-02 11:37:08.054  6319  6334 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:37:08.055  6319  6319 D BluetoothMap: Proxy object connected
09-02 11:37:08.055  6319  6319 D MapProfile: Bluetooth service connected
09-02 11:37:08.055  6319  6319 D BluetoothMap: getConnectedDevices()
,09-02 11:37:08.058  7032  7145 V BluetoothMapService: getConnectedDevices()
,09-02 11:37:08.059  1851  4341 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 11:37:08.059  6319  6319 D BluetoothA2dp: Proxy object connected
09-02 11:37:08.059  6319  6319 D A2dpProfile: Bluetooth service connected
09-02 11:37:08.062  1851  1851 D BluetoothHeadset: Proxy object connected
09-02 11:37:08.062  6319  6828 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 11:37:08.064  6319  6335 D BluetoothPan: onBluetoothStateChange on: true
09-02 11:37:08.064  6319  6335 D BluetoothPan: onBluetoothStateChange call bindService
09-02 11:37:08.065  7032  7106 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:37:08.065  7032  7106 W bt-smp  : Plain text(LSB ~ MSB) = 1b eb 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:37:08.065  7032  7106 W bt-smp  : Encrypted text(LSB ~ MSB) = 8c d0 53 88 ca da 00 f0 0c 53 50 20 86 5a 6e db 
09-02 11:37:08.065  7032  7106 W bt-btm  : Stopping oneshot timer
09-02 11:37:08.067  6319  6319 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 11:37:08.068  6319  6319 D PanProfile: Bluetooth service connected
,09-02 11:37:08.070  1851  2457 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 11:37:08.073  1851  1851 D BluetoothHeadset: Proxy object connected
09-02 11:37:08.074  6319  6828 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:37:08.075  6319  6319 D BluetoothHeadset: Proxy object connected
09-02 11:37:08.076  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 11:37:08.076  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-02 11:37:08.077  7032  7106 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-02 11:37:08.077  7032  7106 W bt-smp  : Plain text(LSB ~ MSB) = de 4c 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:37:08.077  7032  7106 W bt-smp  : Encrypted text(LSB ~ MSB) = d8 07 2d 0a 4a 38 46 99 17 29 91 cc 73 6a a6 9b 
09-02 11:37:08.077  7032  7106 W bt-btm  : Stopping oneshot timer
09-02 11:37:08.078  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 11:37:08.082  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:08.083  1942  2110 D LGBluetoothAPIService: Message: 1
09-02 11:37:08.083  1942  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 11:37:08.083  1942  2110 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-02 11:37:08.083  1942  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-02 11:37:08.085  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-02 11:37:08.089  7032  7106 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 11:37:08.089  7032  7106 W bt-smp  : Plain text(LSB ~ MSB) = 14 47 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 11:37:08.089  7032  7106 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 dd 0b 3b 8c 27 4f 38 c5 6c 71 30 5f 09 cc 40 
09-02 11:37:08.089  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:08.089  7032  7106 W bt-btm  : Stopping oneshot timer
09-02 11:37:08.089  1036  1118 D BluetoothManagerService: Message: 40
09-02 11:37:08.089  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 11:37:08.089  6319  6319 D HeadsetProfile: Bluetooth service connected
09-02 11:37:08.092  7032  7032 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:08.092  7032  7032 D BluetoothMapService: STATE_ON
09-02 11:37:08.092  7032  7032 V BluetoothMapService: Handler(): got msg=1
09-02 11:37:08.092  7032  7032 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 11:37:08.094  7032  7165 D BluetoothMapMasInstance: MAS initSocket()
09-02 11:37:08.095  7032  7165 D BluetoothMapMasInstance:   masId = 00
09-02 11:37:08.095  7032  7165 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 11:37:08.095  7032  7165 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 11:37:08.095  7032  7165 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 11:37:08.097  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:08.103  7032  7165 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 11:37:08.107  7032  7165 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 11:37:08.108  7032  7165 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 11:37:08.108  7032  7165 D BluetoothMapMasInstance: Accepting socket connection...
09-02 11:37:08.108  7032  7068 D BluetoothAdapterProperties: Scan Mode:21
09-02 11:37:08.108  7032  7068 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 11:37:08.111  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:08.112  7032  7032 V BluetoothPbapService: Pbap Service onCreate
09-02 11:37:08.112  7032  7032 V BluetoothPbapService: Starting PBAP service
09-02 11:37:08.112  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:08.113  7032  7032 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 11:37:08.114  7032  7032 V BluetoothPbapService: Pbap Service onBind
09-02 11:37:08.115  7032  7032 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:08.115  7032  7032 V BluetoothPbapService: state: 12
09-02 11:37:08.115  7032  7032 V BluetoothPbapService: Handler(): got msg=1
09-02 11:37:08.116  7032  7032 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 11:37:08.117  7032  7168 V BluetoothPbapService: Pbap Service initSocket
,09-02 11:37:08.123  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:08.125  7032  7168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:37:08.126  7032  7168 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 11:37:08.126  7032  7168 V BluetoothPbapService: Succeed to create listening socket 
09-02 11:37:08.126  7032  7168 V BluetoothPbapService: Accepting socket connection...
09-02 11:37:08.128  6319  6319 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 11:37:08.242  1036  1626 I art     : Explicit concurrent mark sweep GC freed 36419(1738KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.683ms total 113.442ms
,09-02 11:37:08.243  6319  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 11:37:08.245  6319  6319 D BluetoothPbap: Proxy object connected
09-02 11:37:08.245  6319  6319 D PbapServerProfile: Bluetooth service connected
09-02 11:37:08.248  7032  7032 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 11:37:08.248  7032  7032 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:08.248  7032  7032 V BluetoothPbapReceiver: ***********state = 12
09-02 11:37:08.255  6319  6319 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:37:08.256  2080  2080 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:37:08.258  2080  2080 D c       : Getting all permits...
09-02 11:37:08.258  2080  2080 D a       : Opening database...
09-02 11:37:08.268  2080  2080 D a       : Opening database auth.proximity.permit_store...
,09-02 11:37:08.270  2080  2080 D a       : Closing database...
09-02 11:37:08.282  6319  6319 D BluetoothPermissionRequest: onReceive
,09-02 11:37:08.285  6319  6319 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-02 11:37:08.287  6319  6319 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 11:37:08.290  7032  7032 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 11:37:08.291  7032  7032 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 11:37:08.297  7032  7032 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 11:37:08.316  7032  7032 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 11:37:08.316  7032  7032 V BtOppService: onCreate
,09-02 11:37:08.321  7032  7032 V BluetoothOppNotification: send message
09-02 11:37:08.326  7032  7032 V BtOppService: Starting RfcommListener
09-02 11:37:08.332  7032  7172 V BtOppService: Deleted complete outbound shares, number =  0
09-02 11:37:08.334  7032  7172 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 11:37:08.334  7032  7172 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,09-02 11:37:08.336  7032  7172 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@63c6a62 on behalf of 
09-02 11:37:08.337  7032  7032 D BluetoothOppPreference: Dumping Names:  
09-02 11:37:08.337  7032  7032 D BluetoothOppPreference: {}
09-02 11:37:08.338  7032  7032 D BluetoothOppPreference: Dumping Channels:  
09-02 11:37:08.338  7032  7032 D BluetoothOppPreference: {}
09-02 11:37:08.339  7032  7032 V BtOppService: onStartCommand
09-02 11:37:08.340  7032  7175 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 11:37:08.340  7032  7175 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 11:37:08.341  7032  7175 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10a6acb0 on behalf of 
09-02 11:37:08.342  7032  7175 V BluetoothOppNotification: update too frequent, put in queue
09-02 11:37:08.343  7032  7175 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 11:37:08.343  7032  7175 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 11:37:08.344  7032  7175 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fb55729 on behalf of 
09-02 11:37:08.345  7032  7175 V BluetoothOppNotification: update too frequent, put in queue
,09-02 11:37:08.345  7032  7032 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:08.346  7032  7175 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 11:37:08.346  7032  7032 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 11:37:08.351  7032  7032 V BluetoothOppNotification: new notify threadi!
09-02 11:37:08.353  7032  7032 V BluetoothOppNotification: send delay message
09-02 11:37:08.354  7032  7032 V BtOppService: start RfcommListener
09-02 11:37:08.356  7032  7176 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 11:37:08.359  7032  7176 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@137acaae on behalf of 
,09-02 11:37:08.361  7032  7176 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 11:37:08.361  7032  7032 V BtOppService: RfcommListener started
09-02 11:37:08.362  7032  7032 V BtOppService: ContentObserver received notification
,09-02 11:37:08.364  7032  7032 V BtOppService: ContentObserver received notification
09-02 11:37:08.364  7032  7177 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 11:37:08.365  1036  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:08.367  7032  7177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:37:08.367  7032  7178 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 11:37:08.368  7032  7178 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 11:37:08.368  7032  7176 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 11:37:08.370  7032  7178 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@259d804f on behalf of 
09-02 11:37:08.370  7032  7177 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-02 11:37:08.370  7032  7177 V BtOppRfcommListener: Started RFCOMM listener....
09-02 11:37:08.370  7032  7177 I BtOppRfcommListener: Accept thread started.
09-02 11:37:08.371  7032  7177 V BtOppRfcommListener: Accepting connection...
,09-02 11:37:08.374  7032  7178 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-02 11:37:08.374  7032  7176 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d41e3dc on behalf of 
09-02 11:37:08.376  7032  7176 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 11:37:08.378  7032  7176 V BluetoothOppNotification: outbound notification was removed.
09-02 11:37:08.378  7032  7176 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 11:37:08.380  7032  7176 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10a33ce5 on behalf of 
09-02 11:37:08.380  7032  7176 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 11:37:08.382  7032  7176 V BluetoothOppNotification: inbound notification was removed.
09-02 11:37:08.382  7032  7176 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-02 11:37:08.383  7032  7176 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@102ce3ba on behalf of 
09-02 11:37:08.386  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:08.386  7032  7032 V BluetoothFtpService: Ftp Service onCreate
09-02 11:37:08.386  7032  7032 I BluetoothFtpService: Ftp Service onCreate
,09-02 11:37:08.386  7032  7032 V BluetoothFtpService: Ftp Service onStartCommand
09-02 11:37:08.386  7032  7032 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:08.387  7032  7032 V BluetoothFtpService: Starting Listening on sockets
09-02 11:37:08.387  7032  7032 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 11:37:08.387  7032  7032 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 11:37:08.387  7032  7032 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 11:37:08.387  7032  7032 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:37:08.387  7032  7032 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 11:37:08.387  7032  7032 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 11:37:08.389  7032  7032 V BluetoothFtpService: Handler(): got msg=1
09-02 11:37:08.390  7032  7032 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 11:37:08.390  7032  7032 V BluetoothFtpService: Ftp Service initSocket
09-02 11:37:08.399  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:08.400  7032  7032 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 11:37:08.401  7032  7032 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
,09-02 11:37:08.401  7032  7032 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 11:37:08.403  7032  7180 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-02 11:37:08.422  7032  7032 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a81e87
09-02 11:37:08.423  7032  7032 V BluetoothSapService: Sap Service onCreate
,09-02 11:37:08.425  7032  7032 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-02 11:37:08.425  7032  7032 V BluetoothSapService: state: 12
09-02 11:37:08.425  7032  7032 V BluetoothSapService: Starting SAP server process
09-02 11:37:08.427  7032  7032 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 11:37:08.418  7181  7181 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:08.418  7181  7181 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:08.430  7032  7182 V BluetoothSapService: Sap Service initRfcommSocket
09-02 11:37:08.431  1036  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:08.431  7032  7182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:37:08.433  7032  7182 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-02 11:37:08.434  7032  7182 V BluetoothSapService: Succeed to create listening socket 
09-02 11:37:08.434  7032  7182 V BluetoothSapService: Accepting socket connection...
09-02 11:37:08.449  7181  7181 V BT_SAP  : Event pipe created
09-02 11:37:08.449  7181  7181 V BT_SAP  : create_server_socket qcom.sap.server
09-02 11:37:08.449  7181  7181 V BT_SAP  : created socket fd 6
,09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:37:08.786  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:37:08.796  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:37:08.800  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:08.800  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cdb2368 added. We now have 8 listener(s)
09-02 11:37:08.800  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:08.804  1036  2013 D WifiServiceImplEx: setWifiEnabled: false pid=6204, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 11:37:08.805  1036  2013 D WifiService: setWifiEnabled: false pid=6204, uid=10118
09-02 11:37:08.805  1036  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:37:08.811  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:08.812  1036  1977 D WifiServiceImplEx: setWifiEnabled: true pid=6204, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 11:37:08.814  1036  1977 D WifiService: setWifiEnabled: true pid=6204, uid=10118
09-02 11:37:08.814  1036  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:37:08.846  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 11:37:08.847  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 11:37:08.847  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-02 11:37:08.848  1036  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 11:37:08.848  1036  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-02 11:37:08.857  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 11:37:08.857  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 11:37:08.857  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 11:37:08.857  1036  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 11:37:08.857  1036  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 11:37:08.857  1036  1536 E WifiHW  : unknown target_country: EU , set to default
09-02 11:37:08.857  1036  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 11:37:08.857  1036  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 11:37:08.857  1036  1536 I WifiUtil: gEnableBmps=1
,09-02 11:37:09.354  7032  7032 V BluetoothOppNotification: new notify threadi!
,09-02 11:37:09.355  7032  7032 V BluetoothOppNotification: send delay message
,09-02 11:37:09.368  7032  7201 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 11:37:09.374  7032  7201 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e632a47 on behalf of 
09-02 11:37:09.375  7032  7201 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-02 11:37:09.378  7032  7201 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 11:37:09.380  7032  7201 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@104d274 on behalf of 
09-02 11:37:09.381  7032  7201 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 11:37:09.382  7032  7201 V BluetoothOppNotification: outbound notification was removed.
09-02 11:37:09.384  7032  7201 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 11:37:09.385  7032  7201 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20e5239d on behalf of 
09-02 11:37:09.385  7032  7201 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-02 11:37:09.388  7032  7201 V BluetoothOppNotification: inbound notification was removed.
09-02 11:37:09.389  7032  7201 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 11:37:09.390  7032  7201 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ad83012 on behalf of 
09-02 11:37:09.439   315   894 D SoftapController: Softap fwReload - Ok
,09-02 11:37:09.450  1036  1536 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (582ms)
09-02 11:37:09.461   315   894 D CommandListener: Setting iface cfg
09-02 11:37:09.461   315   894 D CommandListener: Trying to bring down wlan0
,09-02 11:37:09.465  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 11:37:09.465  1036  1118 D Tethering: InitialState.processMessage what=4
09-02 11:37:09.465  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 11:37:09.478   315   894 D CommandListener: Clearing all IP addresses on wlan0
09-02 11:37:09.480  1036  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 11:37:09.504  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:37:09.504  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:37:09.504  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 11:37:09.498  7203  7203 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:09.511  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:09.498  7203  7203 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:09.522  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-02 11:37:09.568  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:09.570  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-02 11:37:09.570  1036  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 11:37:09.571  1036  1536 D WifiMonitor: connecting to supplicant
,09-02 11:37:09.575  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:37:09.575  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 11:37:09.575  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:37:09.575  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 11:37:09.576  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:37:09.578  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:37:09.578  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 11:37:09.578  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:37:09.578  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:37:09.578  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 11:37:09.578  7203  7203 I wpa_supplicant: Successfully initialized wpa_supplicant
09-02 11:37:09.579  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 11:37:09.584  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:37:09.584  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 11:37:09.584  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:37:09.584  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-02 11:37:09.592  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:37:09.594  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:37:09.594  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 11:37:09.594  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:37:09.594  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:37:09.594  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 11:37:09.594  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 11:37:09.601  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 11:37:09.606  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 11:37:09.613  6428  7221 W FormManager: Network not available. Please check & try again.
,09-02 11:37:09.615  6428  7222 V FormManager: Network unavailable.
,09-02 11:37:09.617  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:09.623  7203  7203 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 11:37:09.624  7203  7203 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-02 11:37:09.631  6428  7222 V FormManager: Network unavailable.
,09-02 11:37:09.738  7203  7203 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 11:37:09.757  7203  7203 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-02 11:37:09.763  7203  7203 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-02 11:37:09.763  7203  7203 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-02 11:37:09.766  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 11:37:09.767  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 11:37:09.768  1036  7224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,09-02 11:37:09.768  1036  7224 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 11:37:09.768  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 11:37:09.768  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 11:37:09.768  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 11:37:09.768  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 11:37:09.769  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 11:37:09.770  1036  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 11:37:09.771  1036  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:37:09.773  1036  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-02 11:37:09.774  1036  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 11:37:09.774  1036  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 11:37:09.774  1036  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 11:37:09.775  1036  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 11:37:09.775  1036  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 11:37:09.775  1036  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 11:37:09.775  1036  1536 E WifiStateMachine: useWiFiOffloading() : false
09-02 11:37:09.775  1036  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 11:37:09.776  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:09.776  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:09.777  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:09.777  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:09.777  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-02 11:37:09.780  1942  1942 D WfdService: Waiting for WifiP2p enabling
09-02 11:37:09.781  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:09.785  1036  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 11:37:09.788  1036  1536 D WifiNative-wlan0: SET update_config 1: returned true
09-02 11:37:09.788  1036  1536 D WifiConfigStore: Loading config and enabling all networks 
09-02 11:37:09.788  1036  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 11:37:09.788  1036  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:37:09.792  6204  6204 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:37:09.794  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 11:37:09.795  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 11:37:09.796  1036  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 11:37:09.798  6204  6204 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:37:09.802  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 11:37:09.807  1036  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 11:37:09.807  1036  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 11:37:09.808  1036  1536 D WifiStateMachine: enableVerboseLogging : level 2
09-02 11:37:09.808  1036  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-02 11:37:09.809  1036  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 11:37:09.810  1036  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 11:37:09.810  1036  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 11:37:09.810  1036  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 11:37:09.811  1036  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 11:37:09.811  1036  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 11:37:09.811  1036  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 11:37:09.811  1036  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 11:37:09.812  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 11:37:09.812  1036  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 11:37:09.812  1036  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 11:37:09.813  1036  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 11:37:09.813  1036  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 11:37:09.813  1036  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 11:37:09.814  1036  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 11:37:09.814  1036  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 11:37:09.814  1942  1942 D WfdsService: Supplicant Connection state is changed : true
09-02 11:37:09.814  1036  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 11:37:09.814  1036  1536 D WifiNative-HAL: Setting external_sim to 1
09-02 11:37:09.814  1942  2258 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 11:37:09.815  1942  2258 D WfdsService: Set the WFDS Monitor: true
09-02 11:37:09.815  1036  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 11:37:09.815  1942  2258 D WfdsMonitor: WfdsMonitorThread create
09-02 11:37:09.815  1942  2258 D WfdsMonitor: WFDS Monitor is created and started
09-02 11:37:09.815  1942  2258 D WfdsService: WiFi: Supplicant connection re-established
09-02 11:37:09.815  1036  1536 D WifiNative-wlan0: SET external_sim 1: returned true
,09-02 11:37:09.815  1036  1536 I WifiNative-HAL: startHal
09-02 11:37:09.815  1036  1536 D wifi    : setting scan oui 0xaf56f040
09-02 11:37:09.816  1942  7228 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 11:37:09.816  1036  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 11:37:09.816  1036  1536 I WifiNative-HAL: startHal
09-02 11:37:09.816  1036  1536 D wifi    : setting scan oui 0xaf56f040
09-02 11:37:09.816  1942  7228 E CtrlSupplicant: Succeed to open control connection
09-02 11:37:09.816  1036  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 11:37:09.816  1942  7228 E CtrlSupplicant: Succeed to open monitor connection
09-02 11:37:09.817  1036  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 11:37:09.817  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 11:37:09.817  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 11:37:09.817  1942  7228 D WfdsMonitor: Supplicant connection established
09-02 11:37:09.817  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 11:37:09.818  1942  2258 D WfdsService: Connected to the supplicant for wfds
09-02 11:37:09.818  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 11:37:09.818  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 11:37:09.819  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 11:37:09.819  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 11:37:09.819  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 11:37:09.819  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:09.820  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 11:37:09.820  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 11:37:09.820  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 11:37:09.820  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 11:37:09.820  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 11:37:09.820  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 11:37:09.821  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 11:37:09.821  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 11:37:09.821  7203  7203 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 11:37:09.822  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 11:37:09.822  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 11:37:09.822  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 11:37:09.822  1036  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 11:37:09.824  1036  1536 E WifiNative: : [205,349,667 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 11:37:09.824  1036  1536 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 11:37:09.824  1036  1536 D WifiNative-wlan0: RECONNECT: returned true
09-02 11:37:09.824  1036  1536 D WifiNative-wlan0: doString: [STATUS]
09-02 11:37:09.824  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 11:37:09.825  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 11:37:09.825  1036  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 11:37:09.825  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 11:37:09.825  6428  7226 W FormManager: Network not available. Please check & try again.
09-02 11:37:09.825  1036  1536 D WifiNative-wlan0: SET ps 1: returned true
09-02 11:37:09.825  1036  1535 D LGWifiP2pService: P2pDisabledStat,e{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.827  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 11:37:09.827  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-02 11:37:09.827  1036  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.827  1036  1554 I WifiNative-HAL: startHal
09-02 11:37:09.827  1036  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf56f040
09-02 11:37:09.827  1036  1554 D wifi    : failed to get capabilities : -3
09-02 11:37:09.827  1036  1554 E WifiScanningService: could not get scan capabilities
09-02 11:37:09.827  1036  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 11:37:09.827  1036  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.828  1036  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 11:37:09.828  1036  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,09-02 11:37:09.829  1036  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 11:37:09.829  1036  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 11:37:09.829  1036  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 11:37:09.830  1036  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 11:37:09.830  1036  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 11:37:09.830  7203  7203 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 11:37:09.831  1036  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 11:37:09.831  1036  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 11:37:09.832  1036  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 11:37:09.832  1036  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 11:37:09.832  7203  7203 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 11:37:09.833  1036  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 11:37:09.833  1036  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 11:37:09.834   315   894 D CommandListener: Setting iface cfg
09-02 11:37:09.834   315   894 D CommandListener: Trying to bring up p2p0
09-02 11:37:09.834  1036  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 11:37:09.834  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,09-02 11:37:09.834  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 11:37:09.835  7203  7203 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.835  1036  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 11:37:09.835  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 11:37:09.835  1036  1535 D LGWifiP2pService: P2pEnablingState
09-02 11:37:09.835  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.836  7203  7203 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 11:37:09.836  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.836  1036  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.836  1036  1535 D LGWifiP2pService: P2p socket connection successful
09-02 11:37:09.836  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.836  1036  1535 D LGWifiP2pService: P2pEnabledState
09-02 11:37:09.836  7203  7203 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.836  1036  7224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.836  1036  7224 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.836  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.836  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.836  1036  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 11:37:09.836  7203  7203 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.837  1036  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 11:37:09.837  1036  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 11:37:09.837  1942  7228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.837  1942  7228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.837  1036  7224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.837  1036  7224 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-02 11:37:09.837  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.837  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.838  1036  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 11:37:09.838  1036  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 11:37:09.838  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 11:37:09.838  1036  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 11:37:09.838  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 11:37:09.838  7203  7203 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 11:37:09.839  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 11:37:09.839  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
09-02 11:37:09.839  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 11:37:09.839  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-02 11:37:09.839  1036  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 11:37:09.839  1036  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 11:37:09.840  1036  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 11:37:09.840  1036  1536 D WifiNative-wlan0: doBoolean: SCAN
,09-02 11:37:09.840  1036  1536 D WifiNative-wlan0: SCAN: returned false
09-02 11:37:09.840  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 11:37:09.840  1942  1942 D WfdsService: WifiP2pState is changed : true
09-02 11:37:09.841  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=205367  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-02 11:37:09.841  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 11:37:09.841  1942  2258 D WfdsService: Receive the WFDS_ENABLE Method
,09-02 11:37:09.841  1942  2258 D WfdsService: Set the WFDS Monitor: true
09-02 11:37:09.841  1942  2258 D WfdsService: Connected to the supplicant for wfds
09-02 11:37:09.841  1942  2258 D WfdsJNI : doCommand: WFDS_SET TRUE
,09-02 11:37:09.842  7203  7203 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 11:37:09.842  1942  1942 D WfdsService: isConnected: false
09-02 11:37:09.842  1942  2258 D WfdsService: selectPreferredScanChannel [36]
09-02 11:37:09.842  1942  2258 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-02 11:37:09.842  1036  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 11:37:09.842  1036  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 11:37:09.843  1036  1535 D WifiNative-p2p0: SET device_name G3: returned true
09-02 11:37:09.843  1036  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 11:37:09.843  1036  1535 D LGWifiP2pService: before postfix = G3
09-02 11:37:09.843  1036  1535 D WifiServerServiceExt: postfix byte check : 2,
09-02 11:37:09.843  1036  1535 D LGWifiP2pService: after postfix = G3
,09-02 11:37:09.844  1036  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 11:37:09.844  1036  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 11:37:09.844  1036  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 11:37:09.845  1036  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 11:37:09.845  1036  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 11:37:09.846  1036  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 11:37:09.846  1036  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 11:37:09.846  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=205372  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 11:37:09.846  1036  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:37:09.847  1036  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:37:09.848  1036  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 11:37:09.848  1036  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-02 11:37:09.848  1036  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-02 11:37:09.849  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:09.849  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:09.850  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:09.851  1036  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:37:09.852  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:09.852  1036  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:37:09.852  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:09.852  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 11:37:09.852  1036  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 11:37:09.853  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 11:37:09.853  4241  4241 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 11:37:09.854  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:37:09.854  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-02 11:37:09.855  1036  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-02 11:37:09.855  1036  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,09-02 11:37:09.855  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:37:09.856  1036  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 11:37:09.856  1036  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 11:37:09.856  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 11:37:09.856  1036  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 11:37:09.856  1036  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 11:37:09.857  1036  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 11:37:09.857  1036  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-02 11:37:09.858  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 11:37:09.858  1942  1942 D WfdsService: Update P2p Interface State: 3
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:37:09.859  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:37:09.859  4241  4241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 11:37:09.860  6428  7227 V FormManager: Network unavailable.
09-02 11:37:09.862  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:37:09.865  4241  7229 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 11:37:09.867  4241  7230 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 11:37:09.867  6204  6283 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-02 11:37:09.867  4241  7230 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 11:37:09.867  6204  6283 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 11:37:09.869  6204  6283 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3d6248aa Bundle[{}]
09-02 11:37:09.870  6204  6283 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 11:37:09.870  6204  6283 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-02 11:37:09.871  6204  6283 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-02 11:37:09.872  6204  6283 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 11:37:09.872  6204  6283 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 11:37:09.873  6204  6283 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-02 11:37:09.878  6204  6283 I System.out: Running OutgoingSocketThread
09-02 11:37:09.879  6204  7231 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 791)
,09-02 11:37:09.880  6204  7231 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46013
09-02 11:37:09.880  6204  7231 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-02 11:37:09.882  1036  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-02 11:37:09.882  1036  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-02 11:37:09.901  1036  1051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7232 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 11:37:09.902  1036  1535 D LGWifiP2pService: InactiveState
09-02 11:37:09.902  1036  1535 D LGWifiP2pService: InactiveState{ when=-66ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.902  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-66ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.902  1036  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 11:37:09.903  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 11:37:09.903  7203  7203 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.903  1036  7224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 11:37:09.903  1036  7224 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.903  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.903  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 11:37:09.904  7203  7203 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 11:37:09.904  7203  7203 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.904  1036  7224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.904  1036  7224 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.904  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.904  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.904  7203  7203 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.904  1036  7224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.904  1036  7224 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.904  1036  7224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.904  1036  7224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 11:37:09.905  1942  7228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 11:37:09.905  1942  7228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.905  1942  7228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 11:37:09.906  1036  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: InactiveState{ when=-50ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-50ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D, LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.906  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.907  1036  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.907  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.907  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.907  1942  2258 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 11:37:09.907  1036  1535 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:09.907  1036  1036 E WifiServerServiceExt: No p2p device connected
09-02 11:37:09.908  6428  7227 V FormManager: Network unavailable.
,09-02 11:37:09.968  7232  7232 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 11:37:09.968  7232  7232 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 11:37:09.974  7232  7232 V [BNRBootReceiver]: Boot Receiver Return
,09-02 11:37:09.974  7232  7232 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 11:37:09.978  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:37:09.991  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:09.996  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.006  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.006  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.007  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 11:37:10.009  1036  1941 I ActivityManager: Killing 6688:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-02 11:37:10.041  1036  1626 W libprocessgroup: failed to open /acct/uid_10011/pid_6688/cgroup.procs: No such file or directory
,09-02 11:37:10.352  7203  7203 E wpa_supplicant: USIM:  scard_init function
,09-02 11:37:10.357  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 11:37:10.357  1036  7224 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 11:37:10.359  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 11:37:10.359  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
09-02 11:37:10.359  1036  7224 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 11:37:10.360  7203  7203 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-02 11:37:10.362  1036  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-02 11:37:10.362  1036  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-02 11:37:10.365  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 11:37:10.365  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 11:37:10.366  1036  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-02 11:37:10.367  1036  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-02 11:37:10.367  1036  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-02 11:37:10.386  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=205912  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 11:37:10.394  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.394  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:10.396  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.399  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.399  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.399  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-02 11:37:10.409  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.409  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.409  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 11:37:10.410  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=205937  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 11:37:10.411  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:37:10.411  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-02 11:37:10.418  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.418  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:10.419  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 11:37:10.426  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:37:10.434  6319  6319 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 11:37:10.439  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 11:37:10.453  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:10.466  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 11:37:10.486  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.486  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 11:37:10.488  7203  7203 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-02 11:37:10.494  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 11:37:10.494  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 11:37:10.494  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 11:37:10.495  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 11:37:10.495  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:37:10.495  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:37:10.502  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=206029  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-02 11:37:10.504  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=206030  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 11:37:10.505  1036  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206031
09-02 11:37:10.506  7203  7203 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 11:37:10.506  7203  7203 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 11:37:10.508  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:37:10.508  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:37:10.508  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 11:37:10.509  6385  6385 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 11:37:10.512  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 11:37:10.512  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 11:37:10.512  1036  7224 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 11:37:10.512  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 11:37:10.512  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 11:37:10.512  1036  7224 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 11:37:10.512  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:37:10.514  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:37:10.516  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 11:37:10.516  1036  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206043
09-02 11:37:10.517  1036  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206044
09-02 11:37:10.517  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206044
09-02 11:37:10.518  1036  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206044
09-02 11:37:10.518  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=206045  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 11:37:10.522  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=206049  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 11:37:10.523  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.523  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:10.525  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.526  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.526  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.526  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 11:37:10.527  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.527  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.527  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 11:37:10.529  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:10.530  1036  1536 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:37:10.530  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:37:10.531  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 11:37:10.531  1036  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:37:10.531  1036  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:37:10.531  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:37:10.532  1036  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 11:37:10.532  1036  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=206059  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 11:37:10.534  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=206060  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 11:37:10.534  1036  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206061
09-02 11:37:10.535  1036  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206062
09-02 11:37:10.535  1036  1536 D WifiNative-wlan0: doString: [STATUS]
09-02 11:37:10.536  1036  7224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 11:37:10.536  1036  7224 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 11:37:10.537  1036  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 11:37:10.538  1036  1536 I WifiServiceExtension: setVHTCapabilityType  : false
09-02 11:37:10.540  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.545  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.545  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:10.546  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:37:10.548  1036  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 11:37:10.548  1036  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-02 11:37:10.552  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.552  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.552  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-02 11:37:10.556  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.557  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.557  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 11:37:10.565  1036  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,09-02 11:37:10.565  1036  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 11:37:10.565  1036  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 11:37:10.565  1036  1543 D ConnectivityService: Got NetworkAgent Messenger
09-02 11:37:10.565  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 11:37:10.565  1036  1543 D ConnectivityService: NetworkAgent connected
09-02 11:37:10.565  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.565  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.566  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 11:37:10.566  1036  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 11:37:10.566  1036  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 11:37:10.569  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.569  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:10.569  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 11:37:10.569  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 11:37:10.569  6319  6319 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 11:37:10.569  6319  6319 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 11:37:10.570  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 11:37:10.570  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.571  6319  6319 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 11:37:10.571  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 11:37:10.571  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 11:37:10.571  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 11:37:10.571  6319  6319 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 11:37:10.571  6319  6319 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 11:37:10.571  6319  6319 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 11:37:10.572  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.572  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:10.574  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:37:10.576  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 11:37:10.582  1036  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 11:37:10.582  1036  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 11:37:10.582  1036  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 11:37:10.583  1036  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 11:37:10.583  1036  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 11:37:10.584  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:10.589  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.596  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.596  1036  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 11:37:10.596  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.597  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:37:10.600   315   894 D CommandListener: Setting iface cfg
,09-02 11:37:10.601  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 11:37:10.609  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:37:10.610  1036  1536 E WifiStateMachine: Start Dhcp Watchdog 2
09-02 11:37:10.610  1036  7278 D DhcpStateMachine: StoppedState
09-02 11:37:10.610  1036  7278 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.610  1036  7278 D DhcpStateMachine: WaitBeforeStartState
09-02 11:37:10.610  1036  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=206137  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:37:10.611  1036  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=206137  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:37:10.611  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=206138  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:37:10.612  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:37:10.612  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-02 11:37:10.613  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:37:10.613  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 11:37:10.613  1036  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=206139  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:37:10.614  1036  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=206140  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:37:10.614  1036  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=206141  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 11:37:10.615  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14266] from screen [on:0 period:-364751913] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 11:37:10.616  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-364751912] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 11:37:10.616  1036  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 11:37:10.617  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.620  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.621  1036  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-02 11:37:10.621  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.622  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.622  1036  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.623  1036  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.623  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.623  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 11:37:10.624  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 11:37:10.624  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=15,0,0
09-02 11:37:10.624  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=15,0,0
09-02 11:37:10.624  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 11:37:10.624  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.625  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 11:37:10.625  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.625  1036  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 11:37:10.625  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 11:37:10.625  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:37:10.625  1036  1536 D WifiNative-wlan0: SET ps 0: returned true
09-02 11:37:10.625  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 11:37:10.626  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 11:37:10.626  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 11:37:10.626  1036  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11662312 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.626  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11662312 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.626  1036  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 11:37:10.626  1036  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 11:37:10.626  1036  7278 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.626  1036  7278 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 11:37:10.626  1036  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 11:37:10.627   315   894 D CommandListener: Setting iface cfg
09-02 11:37:10.627   315   894 D CommandListener: Trying to bring up wlan0
09-02 11:37:10.628  1036  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 11:37:10.630  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:37:10.631  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:37:10.631  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 11:37:10.636  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:10.639  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 11:37:10.639  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 11:37:10.641  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.642  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.642  1036  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.642  1036  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.643  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.643  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.643  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 11:37:10.644  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 11:37:10.644  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 11:37:10.644  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 11:37:10.644  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 11:37:10.645  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 11:37:10.645  1036  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.645  1036  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.645  1036  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 11:37:10.645  1036  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 11:37:10.645  7203  7203 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 11:37:10.646  1036  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 11:37:10.646  1036  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 11:37:10.649  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.649  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.650  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 11:37:10.653  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 11:37:10.659  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:37:10.662  1036  1536 D WifiNative-wlan0: SET ps 1: returned true
09-02 11:37:10.663  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-02 11:37:10.664  1036  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 11:37:10.664  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 11:37:10.664  1036  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 11:37:10.664  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.665  1036  1543 D ConnectivityService: ignoring duplicate network state non-change
09-02 11:37:10.669  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 11:37:10.670  1036  1543 D ConnectivityService: Adding iface wlan0 to network 101
09-02 11:37:10.671  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.671  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 11:37:10.671  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 11:37:10.673  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.673  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 11:37:10.675  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.678  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.678  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.678  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 11:37:10.679  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.679  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 11:37:10.680  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.683  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.684  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.684  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 11:37:10.687  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.687  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.687  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-02 11:37:10.688  1036  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 11:37:10.688  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:37:10.689  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 11:37:10.692  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 11:37:10.694  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.695  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:37:10.695  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 11:37:10.695  1036  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 11:37:10.696  1036  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-02 11:37:10.697  1036  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-02 11:37:10.698   315   894 E Netd    : netlink response contains error (File exists)
09-02 11:37:10.698  1036  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-02 11:37:10.699  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:37:10.699  1036  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 11:37:10.699  1036  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-02 11:37:10.699  1036  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-02 11:37:10.700  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.701  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 11:37:10.701  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:37:10.703  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 11:37:10.703  1036  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 11:37:10.704  1036  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-02 11:37:10.704  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-02 11:37:10.704  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:37:10.704  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:10.704  1036  7277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.704  1036  7277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 11:37:10.704  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 11:37:10.704  1036  7277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 11:37:10.704  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.704  1036  7277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 11:37:10.704  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 11:37:10.704  1036  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-02 11:37:10.704  1036  1543 D ConnectivityService:    accepting network in place of null
09-02 11:37:10.704  1036  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.706  1036  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.706  1036  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 11:37:10.706  1036  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:37:10.706  1036  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 11:37:10.706  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 11:37:10.707   315  7283 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 11:37:10.708  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.708  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WI,FI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 11:37:10.708  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 11:37:10.708  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 11:37:10.709  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.716  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 11:37:10.716  1036  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,09-02 11:37:10.718  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 11:37:10.718  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 11:37:10.718  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 11:37:10.718  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 11:37:10.720  1036  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-02 11:37:10.722  1036  1543 D ConnectivityService: validation of new default Network = false
09-02 11:37:10.722  1036  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 11:37:10.722  1036  1543 D DSQN    : enableDataServiceNotify 
09-02 11:37:10.722  1036  1543 D DSQN    : start dsqn bin
09-02 11:37:10.723  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:10.732  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 11:37:10.745  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 11:37:10.746  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.746  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:10.746  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:10.746  1601  2128 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 11:37:10.738  7285  7285 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:10.738  7285  7285 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:10.749  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.750  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.751  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 11:37:10.751  1036  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-02 11:37:10.755   315  7283 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 11:37:10.756  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:37:10.761  7285  7285 E DSQN    : DSQN ssw
09-02 11:37:10.762  1816  7284 I CheckinService: active receiver: enabled
,09-02 11:37:10.785  1816  7284 I CheckinService: Preparing to send checkin request
09-02 11:37:10.786  1816  7284 I EventLogService: Accumulating logs since 1472808475755
09-02 11:37:10.791  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:10.798   315  7283 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-02 11:37:10.801  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 11:37:10.802  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.802  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.803  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.808  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 11:37:10.808  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 11:37:10.809  6385  6385 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 11:37:10.812  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:37:10.816  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 11:37:10.816  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:37:10.821  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 11:37:10.826  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 11:37:10.828  1036  7278 D DhcpStateMachine: DHCPV4 request on wlan0
,09-02 11:37:10.830   315   893 D LGDataListener: argv[0]=dsqncommand
09-02 11:37:10.830   315   893 D LGDataListener: argv[1]=wlan0
09-02 11:37:10.830   315   893 D LGDataListener: argv[2]=1
09-02 11:37:10.830   315   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 11:37:10.830  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 11:37:10.830  1036  1116 D DSQN    : start to monitor internet connection
09-02 11:37:10.830  1036  7278 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 11:37:10.830  1036  7278 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 11:37:10.832  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.832  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.835  6385  6385 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 11:37:10.836  6385  6385 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 11:37:10.836  6385  6385 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 11:37:10.828  7291  7291 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 11:37:10.828  7291  7291 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 11:37:10.841  7291  7291 I dhcpcd  : version 5.5.6 starting
09-02 11:37:10.843  7291  7291 E dhcpcd  : get_duid: m
09-02 11:37:10.843  7291  7291 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 11:37:10.843  7291  7291 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 11:37:10.849  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 11:37:10.854  6336  6336 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 11:37:10.854  6336  6336 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 11:37:10.858  6319  6319 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 11:37:10.862  6319  6319 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 11:37:10.864  1036  7277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 09:37:10 GMT], X-Android-Received-Millis=[1472809030864], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472809030829]}
09-02 11:37:10.864  1036  7277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 11:37:10.864  1036  7277 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 11:37:10.864  1036  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-02 11:37:10.864  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-02 11:37:10.864  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:37:10.864  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:10.865  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 11:37:10.865  1036  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-02 11:37:10.865  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 11:37:10.865  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.865  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:10.865  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:10.865  1036  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.865  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 11:37:10.866  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.866  1601  2128 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 11:37:10.866  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 11:37:10.867  1036  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:10.867  6385  6385 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 11:37:10.867  1036  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 11:37:10.867  6385  6385 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 11:37:10.868  6385  6385 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 11:37:10.868  6385  6385 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 11:37:10.869  6385  6385 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSID,s.
09-02 11:37:10.879  6204  6283 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 792)
09-02 11:37:10.879  6204  6283 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 792)
09-02 11:37:10.881  1816  7284 W EventLogAggregator: Unknown tag: snet_gcore
09-02 11:37:10.881  1816  7284 W EventLogAggregator: Unknown tag: snet_launch_service
,09-02 11:37:10.883  6204  6283 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 797)
09-02 11:37:10.884  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 11:37:10.885  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 11:37:10.886  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 11:37:10.886  6204  6283 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-02 11:37:10.886  6204  6283 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 798)
09-02 11:37:10.889  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.890  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3887f381 added. We now have 2 listener(s)
09-02 11:37:10.890  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.892  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.892  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.892  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.892  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:10.893  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da2c26 added. We now have 9 listener(s)
09-02 11:37:10.893  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:10.893  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:37:10.896  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:37:10.899  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:37:10.900  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:10.900  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:37:10.902  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:10.904  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:10.904  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.904  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf30e14 added. We now have 3 listener(s)
09-02 11:37:10.904  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.906  7291  7291 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 11:37:10.906  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.906  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.906  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.907  7291  7291 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 11:37:10.907  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:37:10.907  7291  7291 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-02 11:37:10.907  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c3f46bd added. We now have 10 listener(s)
09-02 11:37:10.907  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:37:10.907  7291  7291 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 11:37:10.907  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:37:10.907  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:37:10.907  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:37:10.907  7291  7291 D dhcpcd  : wlan0: sending REQUEST (xid 0xf60aa4aa), next in 3.31 seconds
09-02 11:37:10.907  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:10.907  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.907  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:10.907  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:10.907  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3887f381 removed from the list
09-02 11:37:10.907  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.907  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da2c26 removed from the list
,09-02 11:37:10.907  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:37:10.907  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.908  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.908  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.908  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:10.908  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 11:37:10.908  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.908  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da2c26 not in the list
09-02 11:37:10.908  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.908  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.909  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:10.909  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 11:37:10.909  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.909  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c3f46bd removed from the list
09-02 11:37:10.909  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:10.909  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.909  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.909  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:10.909  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf30e14 removed from the list
09-02 11:37:10.909  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.909  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11ace4b2 added. We now have 2 listener(s)
,09-02 11:37:10.910  1036  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.911  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.911  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.911  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.911  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:10.911  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f7cc03 added. We now have 9 listener(s)
09-02 11:37:10.912  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:10.912  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:37:10.915  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:37:10.918  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:37:10.919  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:10.919  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:37:10.919  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.919  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91e91b9 added. We now have 3 listener(s)
09-02 11:37:10.920  1036  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.921  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:10.922  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:10.923  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.923  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.923  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.923  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:10.923  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@208099fe added. We now have 10 listener(s)
09-02 11:37:10.923  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:10.923  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:37:10.923  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:37:10.923  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:37:10.923  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:37:10.923  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:37:10.925  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 11:37:10.925  1036  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 fore,groundUser=0
09-02 11:37:10.929  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 11:37:10.929  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 11:37:10.930  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:37:10.930  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:10.931  6204  6283 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 11:37:10.931  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:37:10.931  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:37:10.933  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:37:10.933  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:37:10.933  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:37:10.933  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:10.933  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.933  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:10.933  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:10.933  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11ace4b2 removed from the list
09-02 11:37:10.933  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.933  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f7cc03 removed from the list
09-02 11:37:10.933  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:37:10.933  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.934  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.934  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.934  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:10.934  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:10.934  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.934  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f7cc03 not in the list
09-02 11:37:10.934  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.934  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.935  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:10.935  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:37:10.935  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stoppe,d
09-02 11:37:10.935  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:10.935  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.936  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@208099fe removed from the list
09-02 11:37:10.936  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:10.936  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.936  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.936  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:10.936  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91e91b9 removed from the list
09-02 11:37:10.936  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.936  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40d9075 added. We now have 2 listener(s)
09-02 11:37:10.937  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.938  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.938  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.938  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.939  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:10.939  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b48580a added. We now have 9 listener(s)
09-02 11:37:10.939  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:10.939  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:37:10.942  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:37:10.947  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:37:10.948  7291  7291 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-02 11:37:10.949  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:10.949  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:37:10.949  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.949  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d23698 added. We now have 3 listener(s)
09-02 11:37:10.950  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:10.951  1036  1626 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.951  1816  7284 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-02 11:37:10.952  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:10.954  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.954  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.954  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.954  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:10.954  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb3bef1 added. We now have 10 listener(s)
09-02 11:37:10.954  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:10.954  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:37:10.955  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:37:10.955  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:37:10.955  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:37:10.955  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:37:10.955  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 11:37:10.958  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 11:37:10.958  1036  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.963  1036  1542 D WifiService: New client listening to asynchronous messages
09-02 11:37:10.963  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 11:37:10.963  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 11:37:10.965  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 11:37:10.965  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:10.967  6204  6283 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 11:37:10.967  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:37:10.967  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:37:10.967  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:37:10.967  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:10.967  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.967  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:10.967  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 11:37:10.968  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40d9075 removed from the list
09-02 11:37:10.968  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.968  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b48580a removed from the list
09-02 11:37:10.968  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:37:10.968  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.968  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.968  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.969  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:10.969  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:10.969  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.969  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b48580a not in the list
09-02 11:37:10.969  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.969  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.970  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:10.971  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:37:10.971  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:37:10.971  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:10.971  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:10.971  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb3bef1 removed from the list
09-02 11:37:10.971  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:10.971  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:10.971  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:10.971  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:10.971  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d23698 removed from the list
09-02 11:37:10.972  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.972  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38002444 added. We now have 2 listener(s)
09-02 11:37:10.972  1036  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:10.973  7291  7291 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 11:37:10.973  7291  7291 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 11:37:10.973  7291  7291 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 11:37:10.973  7291  7291 D d,hcpcd  : wlan0: adding default route via 192.168.1.1
09-02 11:37:10.973  7291  7291 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 11:37:10.973  7291  7291 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 11:37:10.973  7291  7291 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 11:37:10.974  7291  7291 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 11:37:10.975  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.976  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.976  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.976  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:10.976  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b4592d added. We now have 9 listener(s)
09-02 11:37:10.976  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:10.976  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:37:10.978  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:37:10.982  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:37:10.993  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-02 11:37:10.993  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:37:10.993  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:10.993  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef3bbf3 added. We now have 3 listener(s)
09-02 11:37:10.994  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 11:37:10.996  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:37:10.997  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:10.997  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:10.997  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:10.997  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:10.997  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fd40b0 added. We now have 10 listener(s)
09-02 11:37:10.997  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:10.998  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:37:10.998  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:37:10.998  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:37:10.998  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:37:10.998  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:37:10.999  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:11.002  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 11:37:11.002  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:11.007  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 11:37:11.008  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 11:37:11.012  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:37:11.012  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:11.015  6204  6283 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-02 11:37:11.018  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:37:11.018  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:37:11.018  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:37:11.018  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:11.018  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.018  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:11.018  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:11.018  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38002444 removed from the list
09-02 11:37:11.018  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:11.018  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b4592d removed from the list
09-02 11:37:11.018  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:37:11.018  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.019  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.019  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.020  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:11.020  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:11.020  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:11.020  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b4592d not in the list
09-02 11:37:11.020  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.020  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.021  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:37:11.022  6204  6283 D BluetoothLeScanner: could not find callback wrapper
09-02 11:37:11.022  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:37:11.022  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:11.022  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:11.022  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fd40b0 removed from the list
09-02 11:37:11.023  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:11.023  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.023  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.023  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:11.023  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef3bbf3 removed from the list
09-02 11:37:11.024  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 11:37:11.024  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1084244f added. We now have 2 listener(s)
09-02 11:37:11.025  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:11.030  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:11.030  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:11.030  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:11.030  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:11.030  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6db7dc added. We now have 9 listener(s)
09-02 11:37:11.030  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:11.030  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:37:11.034  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:37:11.038  6204  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:37:11.040  6204  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:37:11.040  6204  6283 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:37:11.040  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:37:11.040  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19aed7ba added. We now have 3 listener(s)
09-02 11:37:11.041  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 11:37:11.042  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:11.044  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:37:11.045  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 11:37:11.045  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:37:11.045  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:37:11.045  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:37:11.046  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@908b66b added. We now have 10 listener(s)
09-02 11:37:11.046  6204  6283 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:37:11.046  6204  6283 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:37:11.046  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:37:11.046  6204  6283 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:37:11.047  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:11.047  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.047  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:37:11.047  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:11.047  6204  6283 V org.thal,iproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1084244f removed from the list
09-02 11:37:11.047  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:11.047  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6db7dc removed from the list
09-02 11:37:11.047  6204  6283 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:37:11.047  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.047  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.047  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.048  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:11.048  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:11.048  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:11.048  6204  6283 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6db7dc not in the list
09-02 11:37:11.048  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.048  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.049  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:37:11.049  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:37:11.049  6204  6283 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:37:11.049  6204  6283 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@908b66b removed from the list
09-02 11:37:11.049  6204  6283 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:37:11.049  6204  6283 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:37:11.049  6204  6283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:37:11.049  6204  6283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:37:11.049  6204  6283 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19aed7ba removed from the list
09-02 11:37:11.051  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 11:37:11.051  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 11:37:11.051  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 11:37:11.051  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:37:11.051  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState:, Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 11:37:11.052  6204  6283 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 11:37:11.063  6204  7308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 805, name: My test thread name)
09-02 11:37:11.064  6204  7308 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 805, thread name: My test thread name)
09-02 11:37:11.064  6204  7308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 805, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 11:37:11.067  6204  7310 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 807, name: My test thread name)
09-02 11:37:11.068  6204  7310 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 807, thread name: My test thread name)
09-02 11:37:11.068  6204  7310 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 807, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 11:37:11.070  6204  6283 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 11:37:11.070  6204  6283 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 11:37:11.071  6204  6283 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 11:37:11.071  6204  6283 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 11:37:11.071  6204  6283 D com.test.thalitest.ThaliTestRunner: Total duration: 22769 ms
09-02 11:37:11.072  6204  6283 I jxcore-log: *Native tests were executed*
09-02 11:37:11.072  6204  6283 I jxcore-log: 
09-02 11:37:11.072  6204  6283 I jxcore-log: Total number of executed tests:  80
09-02 11:37:11.072  6204  6283 I jxcore-log: 
09-02 11:37:11.072  6204  6283 I jxcore-log: Number of passed tests:  80
09-02 11:37:11.072  6204  6283 I jxcore-log: 
09-02 11:37:11.073  6204  6283 I jxcore-log: Number of failed tests:  0
09-02 11:37:11.073  6204  6283 I jxcore-log: 
09-02 11:37:11.073  6204  6283 I jxcore-log: Number of ignored tests:  0
09-02 11:37:11.073  6204  6283 I jxcore-log: 
09-02 11:37:11.074  6204  6283 I jxcore-log: Total duration:  22769
09-02 11:37:11.074  6204  6283 I jxcore-log: 
09-02 11:37:11.074  6204  6283 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 11:37:11.074  6204  6283 I jxcore-log: 
09-02 11:37:11.080  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.080  6204  6283 I jxcore-log: 
09-02 11:37:11.085  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.085  6204  6283 I jxcore-log: 
09-02 11:37:11.087  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.087  6204  6283 I jxcore-log: 
09-02 11:37:11.088  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.088  6204  6283 I jxcore-log: 
09-02 11:37:11.089  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.089  6204  6283 I jxcore-log: 
09-02 11:37:11.090  6204  6204 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 11:37:11.091  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.091  6204  6283 I jxcore-log: 
09-02 11:37:11.094  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.094  6204  6283 I jxcore-log: 
,09-02 11:37:11.097  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.097  6204  6283 I jxcore-log: 
09-02 11:37:11.098  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 11:37:11.098  6204  6283 I jxcore-log: 
09-02 11:37:11.099  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.099  6204  6283 I jxcore-log: 
09-02 11:37:11.100  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.100  6204  6283 I jxcore-log: 
09-02 11:37:11.101  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.101  6204  6283 I jxcore-log: 
09-02 11:37:11.102  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.102  6204  6283 I jxcore-log: 
09-02 11:37:11.104  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.104  6204  6283 I jxcore-log: 
09-02 11:37:11.104  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.104  6204  6283 I jxcore-log: 
09-02 11:37:11.105  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.105  6204  6283 I jxcore-log: 
09-02 11:37:11.106  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.106  6204  6283 I jxcore-log: 
09-02 11:37:11.107  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.107  6204  6283 I jxcore-log: 
09-02 11:37:11.108  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:37:11.108  6204  6283 I jxcore-log: 
09-02 11:37:11.109  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.109  6204  6283 I jxcore-log: 
09-02 11:37:11.110  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:37:11.110  6204  6283 I jxcore-log: 
09-02 11:37:11.110  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:37:11.110  6204  6283 I jxcore-log: 
09-02 11:37:11.111  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:37:11.111  6204  6283 I jxcore-log: 
09-02 11:37:11.112  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:37:11.112  6204  6283 I jxcore-log: 
09-02 11:37:11.113  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:37:11.113  6204  6283 I jxcore-log: 
09-02 11:37:11.114  6204  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:37:11.114  6204  6283 I jxcore-log: 
09-02 11:37:11.136  1036  1885 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7317 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-02 11:37:11.188  7317  7317 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-02 11:37:11.189  7317  7317 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-02 11:37:11.220  7317  7317 I MultiDex: VM with version 2.1.0 has multidex support
,09-02 11:37:11.220  7317  7317 I MultiDex: install
,09-02 11:37:11.221  7317  7317 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-02 11:37:11.234  7317  7317 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-02 11:37:11.238  1036  7278 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-02 11:37:11.241  1036  7278 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-02 11:37:11.242  1036  7278 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 11:37:11.242  1036  7278 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,09-02 11:37:11.242  1036  7278 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 11:37:11.242  1036  7278 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 11:37:11.242  1036  7278 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 11:37:11.242  1036  7278 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 11:37:11.243  1036  7278 D DhcpStateMachine: RunningState
,09-02 11:37:11.246  2080  2080 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-02 11:37:11.261  2080  2080 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-02 11:37:11.261  2080  2080 D c       : Getting all permits...
,09-02 11:37:11.261  2080  2080 D a       : Opening database...
09-02 11:37:11.268  2080  2080 D a       : Opening database auth.proximity.permit_store...
09-02 11:37:11.269  2080  2080 D a       : Closing database...
09-02 11:37:11.318  7338  7338 D AndroidRuntime: 
09-02 11:37:11.318  7338  7338 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 11:37:11.320  7338  7338 D AndroidRuntime: CheckJNI is OFF
,09-02 11:37:11.344  7317  7335 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-02 11:37:11.364   315  7352 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-02 11:37:11.364   315  7352 D libc-netbsd: res_queryN name = www.googleapis.com, class = 1, type = 1
,09-02 11:37:11.399   315  7352 D libc-netbsd: res_queryN name = www.googleapis.com succeed
,09-02 11:37:11.451  7338  7338 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 11:37:11.467  1036  1102 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-02 11:37:11.469  1036  1102 I ActivityManager: Killing 6204:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-02 11:37:11.551  1036  1542 D WifiService: Client connection lost with reason: 4
,09-02 11:37:11.552  1036  1051 I WindowState: WIN DEATH: Window{38294200 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-02 11:37:11.570  1036  1051 D InputDispatcher: Window went away: Window{38294200 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 11:37:11.684  1036  1102 I ActivityManager:   Force finishing activity ActivityRecord{1d3a2415 u0 com.test.thalitest/.MainActivity t6}
,09-02 11:37:11.697  1036  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:37:11.698  1036  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:37:11.699  1036  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:37:11.701  1036  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-02 11:37:11.702  1036  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-02 11:37:11.704  1036  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 11:37:11.707  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-02 11:37:11.707  1036  1543 D ConnectivityService: identical MTU - not setting
09-02 11:37:11.707  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 11:37:11.707  1036  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 11:37:11.708  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:37:11.708  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:11.709  1036  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 11:37:11.711  1601  2128 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-02 11:37:11.720   346   386 E GBMv2   : DFP En is all cleared set to be enabled
09-02 11:37:11.720  1036  1785 W ActivityManager: Spurious death for ProcessRecord{e1d63be 6204:com.test.thalitest/u0a118}, curProc for 6204: null
09-02 11:37:11.725  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-02 11:37:11.730  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{1d3a2415 u0 com.test.thalitest/.MainActivity t6 f}
09-02 11:37:11.730  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{1d3a2415 u0 com.test.thalitest/.MainActivity t6 f}
,09-02 11:37:11.764  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-02 11:37:11.764  1942  3866 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-02 11:37:11.765  1942  3866 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4ccf43b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-02 11:37:11.765  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-02 11:37:11.768  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-02 11:37:11.768  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e502758 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-02 11:37:11.770  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-02 11:37:11.772  2033  2073 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-02 11:37:11.777  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-02 11:37:11.808  2748  2748 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-02 11:37:11.813  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-02 11:37:11.814  7032  7032 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-02 11:37:11.814  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-02 11:37:11.825  2466  2633 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-02 11:37:11.830  1036  1457 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-02 11:37:11.842  1036  1100 W InputMethodInfo: Duplicated subtype definition found: , voice
09-02 11:37:11.836  4383  4383 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-02 11:37:11.843  4383  4383 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-02 11:37:11.843  4383  4383 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-02 11:37:11.843  4383  4383 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-02 11:37:11.843  4383  4383 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 11:37:11.843  4383  4383 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 11:37:11.843  4383  4383 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 11:37:11.843  4383  4383 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 11:37:11.843  4383  4383 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:37:11.843  4383  4383 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 11:37:11.843  4383  4383 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 11:37:11.843  4383  4383 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 11:37:11.847  1036  2032 V SIM_STK : Menu title from STK is T-Mobile
,09-02 11:37:11.868  4508  4508 I art     : Explicit concurrent mark sweep GC freed 650(41KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 471us total 119.215ms
,09-02 11:37:11.881  1036  1036 D administrator: Handling package changes for user 0
09-02 11:37:11.881  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-02 11:37:11.918  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-02 11:37:11.919  1868  1868 D SplitUIService: removed split : 
,09-02 11:37:11.933  1036  1959 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7360 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-02 11:37:11.944   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 268us total 13.356ms
09-02 11:37:11.947  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-02 11:37:11.947  1906  1906 D ActionManagerService: notifyUserLog: 1000003
09-02 11:37:11.948  2748  4411 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-02 11:37:11.957   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 12.364ms
,09-02 11:37:11.967  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-02 11:37:11.968  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,09-02 11:37:11.970   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 247us total 11.660ms
09-02 11:37:11.972  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-02 11:37:11.972  1868  1868 I SplitUIService: split app #11
09-02 11:37:11.978  1036  1903 V SIM_STK : Menu title from STK is T-Mobile
09-02 11:37:11.978  1036  1903 V SIM_STK : Menu title from STK is T-Mobile
09-02 11:37:11.981  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-02 11:37:11.982  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-02 11:37:11.983  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-02 11:37:11.993  2080  2080 I ConfigService: onCreate
09-02 11:37:11.997  2080  2080 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-02 11:37:12.003  2080  2080 I ConfigService: onBind returning update interface
09-02 11:37:12.012  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-02 11:37:12.015  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-02 11:37:12.016  1906  1906 D ActionManagerService: notifyUserLog: 1000004
09-02 11:37:12.017  2748  2780 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 11:37:12.017  2748  4411 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-02 11:37:12.017  2080  2080 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-02 11:37:12.017  2080  2080 I ConfigService: onBind returning config service
09-02 11:37:12.020  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-02 11:37:12.020  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , display: false
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , animation: false }
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , display: false
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , animation: false }
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , create_time: 1472216588858
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , display: false
09-02 11:37:12.020  2033  2033 I GBoardWebViewUtils: , animation: false }
09-02 11:37:12.027  1816  1816 I ConfigFetchService: service connected
,09-02 11:37:12.031  2033  7378 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-02 11:37:12.031  1816  1816 I ConfigClient: service connected
09-02 11:37:12.031  1036  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 11:37:12.032  7032  7032 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 11:37:12.035  2080  2080 I ConfigService: onDestroy
09-02 11:37:12.039  1816  7380 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-02 11:37:12.042  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 11:37:12.042  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-02 11:37:12.043  7360  7360 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,09-02 11:37:12.058  1036  1785 V SIM_STK : Menu title from STK is T-Mobile
09-02 11:37:12.082  1036  2013 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7383 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-02 11:37:12.086  1601  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 11:37:12.086  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.087  1601  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 11:37:12.087  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.094  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 11:37:12.094  1601  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 11:37:12.094  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 11:37:12.095  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 11:37:12.096  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 11:37:12.096  1601  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-02 11:37:12.101  1601  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 11:37:12.101  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.107  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-02 11:37:12.107  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 11:37:12.108  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-02 11:37:12.113  1036  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-02 11:37:12.119  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 11:37:12.119  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 11:37:12.123   329   414 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-02 11:37:12.123  3197  7399 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-02 11:37:12.125  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 11:37:12.125  1601  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-02 11:37:12.131  1601  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 11:37:12.131  1601  1665 D KeyguardModel: createShortcutInfo...
,09-02 11:37:12.135  1601  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 11:37:12.135  1601  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 11:37:12.135  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 11:37:12.135  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 11:37:12.136  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 11:37:12.136  1601  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 11:37:12.138  1601  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 11:37:12.138  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.142  1036  2012 I ActivityManager: Killing 6726:com.lge.email/u0a23 (adj 15): empty #17
09-02 11:37:12.144  5542  7403 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-02 11:37:12.151  1816  7405 I PeopleContactsSync: CP2 sync disabled
09-02 11:37:12.162  1036  1124 I art     : Explicit concurrent mark sweep GC freed 77050(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 7.774ms total 374.234ms
,09-02 11:37:12.189  7383  7383 I AppUp4:AppBoxCP: onCreate
09-02 11:37:12.189  7383  7383 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-02 11:37:12.194  7383  7383 I AppUp4:DB:  setFingerPrint start
09-02 11:37:12.194  7383  7383 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-02 11:37:12.198  7383  7383 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-02 11:37:12.198  7383  7383 I AppUp4:DB:  SDK version = 21
09-02 11:37:12.198  7383  7383 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-02 11:37:12.230  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-02 11:37:12.234  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 11:37:12.235  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-02 11:37:12.237  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-02 11:37:12.237  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-02 11:37:12.238  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-02 11:37:12.245  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-02 11:37:12.245  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 11:37:12.249  1036  1923 W libprocessgroup: failed to open /acct/uid_10023/pid_6726/cgroup.procs: No such file or directory
,09-02 11:37:12.253  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-02 11:37:12.253  7383  7383 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-02 11:37:12.254  1601  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 11:37:12.254  1601  1665 D KeyguardModel: createShortcutInfo...
,09-02 11:37:12.257  1601  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 11:37:12.257  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.257  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 11:37:12.257  1601  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-02 11:37:12.258  1601  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 11:37:12.258  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.259  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 11:37:12.259  1601  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-02 11:37:12.260  1601  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 11:37:12.260  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.261  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 11:37:12.261  1601  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 11:37:12.262  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-02 11:37:12.262  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 11:37:12.266  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f2d0370 u0 com.lge.launcher2/.Launcher t5} time:207803
09-02 11:37:12.273  1601  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 11:37:12.273  1601  1665 D KeyguardModel: createShortcutInfo...
09-02 11:37:12.277  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-02 11:37:12.278  1816  4568 I Icing   : doRemovePackageData com.test.thalitest
09-02 11:37:12.279  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 11:37:12.279  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 11:37:12.280  2033  2807 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-02 11:37:12.280  2033  2807 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-02 11:37:12.288  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-02 11:37:12.291  2033  2033 D [Concierge]WidgetView: change position of spinner
09-02 11:37:12.292  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1472809032292
09-02 11:37:12.292  2610  2610 D [Concierge]Service: onStartCommand(). Type : 8
09-02 11:37:12.292  2610  2610 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,09-02 11:37:12.294  2610  2610 D [Concierge]Service: Update widget ID : 11
09-02 11:37:12.294  2610  2610 D [Concierge]Service: onStartCommand(). Type : 0
09-02 11:37:12.297  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-02 11:37:12.297  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 11:37:12.302  1816  7404 I art     : Explicit concurrent mark sweep GC freed 16652(1109KB) AllocSpace objects, 13(208KB) LOS objects, 51% free, 29MB/61MB, paused 961us total 52.553ms
09-02 11:37:12.310  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 907457299
09-02 11:37:12.311  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-02 11:37:12.311  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-02 11:37:12.314  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3fcfc5ca
09-02 11:37:12.314  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-02 11:37:12.316  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 11:37:12.316  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 11:37:12.319  7317  7335 D LgDataFeature: LgDataFeature() Constructor: none
09-02 11:37:12.319  7317  7335 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 11:37:12.321  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-02 11:37:12.322  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
,09-02 11:37:12.322  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 11:37:12.322  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472808852760, New one : 1472809032292
09-02 11:37:12.322  2033  2033 D [Concierge]WidgetView: Unregister all receivers
09-02 11:37:12.323  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 11:37:12.323  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 11:37:12.324  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,09-02 11:37:12.326  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-02 11:37:12.327  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-02 11:37:12.328  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-02 11:37:12.329  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-02 11:37:12.332  1816  7404 W GmsApplication: Using Auth Proxy for data requests.
09-02 11:37:12.336  1816  7404 W GmsApplication: Using Auth Proxy for data requests.
09-02 11:37:12.347  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 11:37:12.347  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 11:37:12.353  7383  7383 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-02 11:37:12.358  1036  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 11:37:12.363  1036  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-02 11:37:12.376  7338  7338 D AndroidRuntime: Shutting down VM
,09-02 11:37:12.383  1036  1923 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7410 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-02 11:37:12.384  1036  1923 I ActivityManager: Killing 6777:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-02 11:37:12.400  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-02 11:37:12.407  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-02 11:37:12.408  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-02 11:37:12.408  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 11:37:12.428  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@102accf8 time:207965
,09-02 11:37:12.469  7427  7427 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-02 11:37:12.498  1036  1977 W libprocessgroup: failed to open /acct/uid_10046/pid_6777/cgroup.procs: No such file or directory
,09-02 11:37:12.502  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-02 11:37:12.503  7427  7427 I dex2oat : dex2oat took 34.351ms (threads: 4)
09-02 11:37:12.512  7317  7335 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 11:37:12.512  7317  7335 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 11:37:12.512  7317  7335 I Adreno-EGL: Build Date: 12/12/14 금
09-02 11:37:12.512  7317  7335 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 11:37:12.512  7317  7335 I Adreno-EGL: Remote Branch: 
09-02 11:37:12.512  7317  7335 I Adreno-EGL: Local Patches: 
09-02 11:37:12.512  7317  7335 I Adreno-EGL: Reconstruct Branch: 
09-02 11:37:12.515  7410  7410 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 11:37:12.516  7410  7410 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 11:37:12.516  7410  7410 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 11:37:12.517  7410  7410 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-02 11:37:12.517  7410  7410 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-02 11:37:12.524  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7433 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-02 11:37:12.569  2080  2096 I art     : Explicit concurrent mark sweep GC freed 5420(313KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 689us total 18.402ms
,09-02 11:37:12.587  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-02 11:37:12.591  1036  1052 I ActivityManager: Killing 6806:com.android.chrome/u0a57 (adj 15): empty #17
09-02 11:37:12.603  7317  7335 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 11:37:12.603  7317  7335 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 11:37:12.603  7317  7335 I Adreno-EGL: Build Date: 12/12/14 금
09-02 11:37:12.603  7317  7335 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 11:37:12.603  7317  7335 I Adreno-EGL: Remote Branch: 
09-02 11:37:12.603  7317  7335 I Adreno-EGL: Local Patches: 
09-02 11:37:12.603  7317  7335 I Adreno-EGL: Reconstruct Branch: 
,09-02 11:37:12.612  7410  7410 I SystemConfig: BUILD Country: EU
09-02 11:37:12.612  7410  7410 I SystemConfig: BUILD Operator: OPEN
09-02 11:37:12.630  2033  2861 I GBoardtInterface: onReloaded()
,09-02 11:37:12.632  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-02 11:37:12.683  1036  1785 W libprocessgroup: failed to open /acct/uid_10057/pid_6806/cgroup.procs: No such file or directory
,09-02 11:37:12.686  2748  2768 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 11:37:12.687  1036  1903 I ActivityManager: Killing 6840:com.lge.drmservice/u0a62 (adj 15): empty #17
09-02 11:37:12.704  1036  2050 W libprocessgroup: failed to open /acct/uid_10062/pid_6840/cgroup.procs: No such file or directory
,09-02 11:37:12.707  2353  2529 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
09-02 11:37:12.708  2353  2529 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 11:37:12.709  7410  7455 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-02 11:37:12.709  7410  7455 I SystemConfig: existFile = false
09-02 11:37:12.709  7410  7455 I SystemConfig: canReadFile = false
09-02 11:37:12.709  7410  7455 I SystemConfig: systemFeature RCS result false
09-02 11:37:12.710  7410  7455 D SystemConfig: refreshRcsSupport() :false
09-02 11:37:12.711  2748  2767 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 11:37:12.712  2353  7457 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-02 11:37:12.718  2353  7457 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-02 11:37:12.718  2353  7457 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-02 11:37:12.718  2353  7457 E AndroidRuntime: Process: android.process.acore, PID: 2353
09-02 11:37:12.718  2353  7457 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteD,atabase.java:1600)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-02 11:37:12.718  2353  7457 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 11:37:12.737  1036  1904 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7458 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 11:37:12.741  2353  7457 I Process : Sending signal. PID: 2353 SIG: 9
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: Can't write: system_app_crash
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 11:37:12.745  1036  7464 E DropBoxManagerService: 	... 5 more
09-02 11:37:12.747  4383  4441 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
,09-02 11:37:12.747  1906  1906 D ActionManagerService: notifyUserLog: 1000001
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: Error inserting f004=13 f005=7458 f002=1472809032742 f003=com.lge.email f006=10023
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-02 11:37:12.748  4383  4441 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
09-02 11:37:12.748  2748  4411 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 11:37:12.748  2748  4411 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 11:37:12.751  1906  1906 D ActionManagerService: notifyUserLog: 1000001
09-02 11:37:12.753  2748  4411 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 11:37:12.753  2748  4411 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 11:37:12.753  2748  4411 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-02 11:37:12.753  2748  4411 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-02 11:37:12.753  2748  2767 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)

```
