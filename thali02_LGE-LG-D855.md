#### Test 797638305c870dd_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-30 16:01:04.572  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=372197663 [*alarm*], flags=0x0
,--------- beginning of main
08-30 16:01:28.291  6225  6225 D AndroidRuntime: 
08-30 16:01:28.291  6225  6225 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 16:01:28.298  6225  6225 D AndroidRuntime: CheckJNI is OFF
08-30 16:01:28.499  6225  6225 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 16:01:28.510  1036  1576 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 16:01:28.526  1984  2811 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 16:01:28.531  1036  1576 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 16:01:28.533  1036  1576 D ActivityManager: setTaskToReturnTo : TaskRecord{7fd4998 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 16:01:28.533  1036  1576 D ActivityManager: setTaskToReturnTo : TaskRecord{7fd4998 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 16:01:28.534  1036  1576 D WindowStateEx: AppWindowTokenEx init.. 
08-30 16:01:28.535   342   368 E GBMv2   : DFP En is all cleared set to be enabled
08-30 16:01:28.563  1036  1576 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6240 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 16:01:28.566  6225  6225 D AndroidRuntime: Shutting down VM
08-30 16:01:28.702  1036  1051 I art     : Explicit concurrent mark sweep GC freed 38499(1767KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.870ms total 91.440ms
08-30 16:01:28.728  1984  2000 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 16:01:28.728  1984  2000 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ae371e4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 16:01:28.731  1984  1999 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 16:01:28.731  1984  1999 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39e3264d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 16:01:28.773  6240  6240 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-30 16:01:28.887  6240  6240 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 16:01:28.896  6240  6240 I LibraryLoader: Loading: webviewchromium
08-30 16:01:28.899  6240  6240 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8562-8565)
08-30 16:01:28.899  6240  6240 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:01:28.930  6240  6240 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13b7cc00}
,08-30 16:01:28.931  6240  6240 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:01:28.931  6240  6240 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 16:01:28.942  6240  6240 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 16:01:28.943  6240  6240 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 16:01:28.949  6240  6275 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-30 16:01:28.953  6240  6240 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 16:01:28.954  6240  6240 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 16:01:28.955   322   322 V AudioPolicyService: registerClient() client 0xb558a4c0, uid 10118
08-30 16:01:28.955  6240  6240 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-30 16:01:28.959  1036  1097 D BluetoothManagerService: Message: 20
08-30 16:01:28.959  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@221e5962:true
08-30 16:01:28.971  6240  6240 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:01:28.971  6240  6240 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:01:28.971  6240  6240 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:01:28.971  6240  6240 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:01:28.971  6240  6240 I Adreno-EGL: Remote Branch: 
08-30 16:01:28.971  6240  6240 I Adreno-EGL: Local Patches: 
08-30 16:01:28.971  6240  6240 I Adreno-EGL: Reconstruct Branch: 
,08-30 16:01:29.047  6240  6286 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 16:01:29.048  6240  6240 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 16:01:29.063  6240  6240 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:01:29.067  6240  6240 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 16:01:29.069  6240  6240 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 16:01:29.071  6240  6240 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 16:01:29.071  6240  6240 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 16:01:29.083  6240  6240 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 16:01:29.089  6240  6240 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 16:01:29.089  6240  6240 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:01:29.124  6240  6299 D OpenGLRenderer: Render dirty regions requested: true
08-30 16:01:29.124  6240  6299 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 16:01:29.127  6240  6299 D OpenGLRenderer: Enabling debug mode 0
,08-30 16:01:29.133  6240  6240 D Atlas   : Validating map...
08-30 16:01:29.136  1036  2129 D SplitWindow: check instance of lgWin Window{23a330c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 16:01:29.215  6240  6297 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 16:01:29.216  6240  6297 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:01:29.221  6240  6240 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@77702cf time:168888
08-30 16:01:29.221  1036  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +495ms (total +685ms)
08-30 16:01:29.221  1036  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16d4d5f1 u0 com.test.thalitest/.MainActivity t6} time:168888
08-30 16:01:29.389  6240  6240 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 16:01:29.486  6240  6297 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 16:01:29.486  6240  6297 I chromium: 
,08-30 16:01:29.611  6240  6315 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435222016
,08-30 16:01:29.625  6240  6315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 16:01:29.625  6240  6315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 16:01:29.625  6240  6315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 16:01:29.625  6240  6315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 16:01:29.625  6240  6315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 16:01:29.626  6240  6315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f381e63 added. We now have 1 listener(s)
,08-30 16:01:29.631  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:29.634  6240  6315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 16:01:29.637  6240  6315 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 16:01:29.638  6240  6315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:29.638  6240  6315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:29.645  6240  6240 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 16:01:29.645  6240  6240 I chromium: 
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 16:01:29.646  6240  6315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@165957de added. We now have 1 listener(s)
08-30 16:01:29.647  6240  6315 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:29.652  1036  1484 D WifiService: New client listening to asynchronous messages
,08-30 16:01:29.656  6240  6315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:01:29.656  6240  6315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 16:01:29.656  6240  6315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 16:01:29.656  6240  6315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 16:01:29.656  6240  6315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 16:01:29.659  6240  6315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:29.661  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:29.664  6240  6315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-30 16:01:29.676  6240  6315 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:29.676  6240  6315 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:29.676  6240  6315 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 16:01:29.676  6240  6315 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:29.677  6240  6315 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:01:29.677  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:29.721  6240  6240 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 16:01:30.215   342   370 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 16:01:30.215   342   370 E GBMv2   : Set value is all cleared set the max
08-30 16:01:30.215   342   370 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 16:01:30.932  6240  6318 W jxcore-log: Initializing JXcore engine
08-30 16:01:30.932  6240  6318 W jxcore-log: JXcore engine is ready
,08-30 16:01:30.995  6318  6318 W Thread-696: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[9347]" dev="sockfs" ino=9347 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 16:01:30.995  6318  6318 W Thread-696: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 16:01:30.995  6318  6318 W Thread-696: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9431]" dev="sockfs" ino=9431 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 16:01:30.995  6318  6318 W Thread-696: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 16:01:30.995  6318  6318 W Thread-696: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[30964]" dev="sockfs" ino=30964 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 16:01:31.023  6240  6318 W jxcore-log: Starting JXcore engine
,08-30 16:01:31.127  6240  6318 W jxcore-log: Platform android
08-30 16:01:31.127  6240  6318 W jxcore-log: 
08-30 16:01:31.127  6240  6318 W jxcore-log: Process ARCH arm
08-30 16:01:31.127  6240  6318 W jxcore-log: 
,08-30 16:01:31.330  6240  6318 I jxcore-log: JXcore Cordova bridge is ready!
08-30 16:01:31.330  6240  6318 I jxcore-log: 
08-30 16:01:31.330  6240  6318 W jxcore-log: JXcore engine is started
,08-30 16:01:31.338  6240  6315 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 16:01:31.344  6240  6240 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 16:01:37.316  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3a0e30c2 type 2 when 176964 com.google.android.gms} when 176964
,08-30 16:01:48.556  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 16:01:48.556  6240  6318 I jxcore-log: 
,08-30 16:01:48.558  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 16:01:48.558  6240  6318 I jxcore-log: 
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:48.562  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:48.564  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:48.566  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 16:01:48.566  6240  6318 I jxcore-log: 
08-30 16:01:48.568  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 16:01:48.568  6240  6318 I jxcore-log: 
08-30 16:01:49.066  6240  6318 D executeNativeTests: Running unit tests
,08-30 16:01:49.147  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:49.147  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad added. We now have 2 listener(s)
08-30 16:01:49.148  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 16:01:49.149  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:01:49.149  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:49.149  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:49.149  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:49.149  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 added. We now have 2 listener(s)
08-30 16:01:49.149  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:49.150  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:01:49.151  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.154  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:01:49.155  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:01:49.155  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:49.156  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.158  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:01:49.159  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-30 16:01:49.160  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 16:01:49.161  6240  6318 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,08-30 16:01:49.162  6240  6318 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-30 16:01:49.162  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:01:49.162  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:01:49.162  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 16:01:49.162  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.163  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.163  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.163  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.163  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:49.163  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:49.163  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:49.164  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad removed from the list
08-30 16:01:49.164  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.164  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 removed from the list,
08-30 16:01:49.164  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.164  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.165  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.165  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.165  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 16:01:49.165  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.165  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.165  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.167  6240  6318 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 16:01:49.168  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:01:49.168  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.168  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.168  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.168  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.168  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.168  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.168  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.169  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.169  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.169  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.169  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.169  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.169  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.169  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:01:49.169  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.169  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.169  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:01:49.174  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:01:49.175  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.175  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.175  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.175  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-30 16:01:49.175  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.175  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.175  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.175  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.175  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list,
08-30 16:01:49.175  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.175  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.175  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.176  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.176  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:49.178  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.178  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.178  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.178  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.179  6240  6318 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 16:01:49.181  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.182  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:01:49.183  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:49.183  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:49.184  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.185  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:01:49.185  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-30 16:01:49.185  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:01:49.185  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:49.185  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:01:49.187  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:01:49.188  1036  2074 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:49.191  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:01:49.195  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-30 16:01:49.196  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 16:01:49.197  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:01:49.198  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:49.199  6240  6318 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:01:49.199  6240  6318 I io.jxcore.node.ConnectionHelper: start: OK,
08-30 16:01:49.201  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.201  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.201  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.201  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.201  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:49.202  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:49.202  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.202  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.202  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.202  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 16:01:49.202  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.202  6240  6318 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:01:49.203  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.205  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:01:49.205  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-30 16:01:49.206  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:49.206  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.206  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:01:49.206  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:01:49.206  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:01:49.206  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:49.207  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:01:49.209  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:01:49.209  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:49.211  6240  6318 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:01:49.211  6240  6318 I io.jxcore.node.ConnectionHelper: start: OK
08-30 16:01:49.212  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.212  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:01:49.212  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.212  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.212  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.212  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:49.212  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
,08-30 16:01:49.212  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.212  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.212  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.212  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.212  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:49.212  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.213  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.213  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.214  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.214  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:01:49.214  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.214  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.215  6240  6318 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:01:49.216  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.217  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:49.218  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:01:49.218  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:49.219  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.219  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:01:49.219  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:01:49.219  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:01:49.219  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:49.219  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:01:49.222  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:01:49.222  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:49.223  6240  6318 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 16:01:49.223  6240  6318 I io.jxcore.node.ConnectionHelper: start: OK
08-30 16:01:49.223  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.223  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.223  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.224  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.224  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-30 16:01:49.224  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.224  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.224  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.224  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:01:49.224  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.224  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.224  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.224  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.225  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:49.225  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.225  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.225  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.225  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.226  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.226  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.226  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.226  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.226  6240  6318 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 16:01:49.226  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.226  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.226  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.227  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.227  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 16:01:49.227  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.227  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.227  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.227  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.227  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:01:49.227  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.227  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.227  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.227  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:49.228  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.228  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.228  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.228  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.228  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.228  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.229  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:01:49.229  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.229  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.229  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.229  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.229  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.229  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.229  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.229  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.229  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.229  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.229  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.229  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.229  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.229  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.230  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.230  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.230  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.230  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.230  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.231  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.231  6240  6318 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 16:01:49.231  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.231  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: ,false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.231  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.231  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.232  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.232  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.232  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.232  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.232  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.232  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.232  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.232  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.232  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.232  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.232  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.232  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.233  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.233  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.233  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.233  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.234  6240  6318 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 16:01:49.234  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.234  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.234  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.234  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.234  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.234  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.234  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.234  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.234  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.234  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.234  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.234  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.234  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.235  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.235  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.235  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.236  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.236  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.236  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.236  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.236  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:01:49.236  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:01:49.236  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:01:49.236  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:01:49.236  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:01:49.236  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:01:49.236  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.236  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.236  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.237  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.237  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.237  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.237  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.237  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.237  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.237  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.237  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.237  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.237  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.237  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.238  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.238  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.238  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.238  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.238  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.238  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.239  6240  6318 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:01:49.239  6240  6318 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:01:49.239  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:01:49.240  6240  6318 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:01:49.241  6240  6318 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:01:49.241  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:01:49.241  6240  6318 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 16:01:49.241  6240  6318 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:01:49.241  6240  6318 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 16:01:49.242  6240  6318 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:01:49.242  6240  6318 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:01:49.242  6240  6318 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 16:01:49.242  6240  6318 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:01:49.242  6240  6318 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:01:49.242  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 16:01:49.244  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 16:01:49.244  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 16:01:49.244  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 16:01:49.245  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 16:01:49.245  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 16:01:49.245  6240  6318 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 16:01:49.245  6240  6318 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:01:49.245  6240  6318 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 16:01:49.245  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.246  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.246  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.246  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:01:49.246  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.246  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.247  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 16:01:49.247  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.247  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.247  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.247  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.247  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.247  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.247  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.247  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.248  6240  6338 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 760)
08-30 16:01:49.253  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.253  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.254  6240  6339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 760
08-30 16:01:49.254  6240  6339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 760)
08-30 16:01:49.254  6240  6339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 760)
08-30 16:01:49.255  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.255  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.255  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.255  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.255  6240  6318 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 16:01:49.255  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.255  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.256  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.256  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.256  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.256  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.256  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.256  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.256  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.256  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.256  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.256  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.256  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.256  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.257  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.257  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.258  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.258  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.258  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.258  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.258  6240  6318 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 16:01:49.259  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.259  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.259  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.259  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.259  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.259  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.259  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.259  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.259  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.259  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.259  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.259  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.259  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.259  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.260  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.260  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.260  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.260  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.260  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.260  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.261  6240  6318 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 16:01:49.261  6240  6318 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 16:01:49.261  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:01:49.261  6240  6318 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 16:01:49.261  6240  6318 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:01:49.261  6240  6318 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 16:01:49.261  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:01:49.261  6240  6318 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 16:01:49.261  6240  6318 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:01:49.261  6240  6318 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:01:49.261  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:01:49.261  6240  6318 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 16:01:49.261  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.261  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.262  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.262  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.262  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.262  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.262  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.262  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.262  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.262  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.262  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.262  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.262  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.262  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.263  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.263  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.264  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.264  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.264  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.264  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.264  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.264  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.264  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.264  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.264  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.264  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.264  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.264  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.264  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.265  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.265  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.265  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.265  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.265  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.265  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.265  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.265  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.265  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.265  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.265  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.265  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.265  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.265  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.265  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.265  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.265  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.265  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.265  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.265  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.266  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.266  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.273  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.273  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.273  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.273  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.274  6240  6318 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 16:01:49.274  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:49.275  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 16:01:49.275  6240  6318 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 16:01:49.275  6240  6318 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 16:01:49.276  6240  6240 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 16:01:49.276  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 16:01:49.276  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:01:49.276  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.276  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 16:01:49.276  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 16:01:49.277  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 16:01:49.277  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.277  6240  6318 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 16:01:49.277  6240  6240 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 16:01:49.277  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.277  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.277  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:01:49.277  6240  6318 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:01:49.277  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:01:49.278  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:01:49.283  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:01:49.283  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:49.283  6240  6318 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:01:49.283  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.283  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.284  6240  6318 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:01:49.284  6240  6240 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:01:49.284  6240  6240 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:01:49.284  6240  6240 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:01:49.284  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.284  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.285  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.285  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.285  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.285  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.285  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.285  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.285  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.285  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.285  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.285  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.285  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.285  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.285  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.286  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.286  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.286  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.286  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.286  6240  6318 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 16:01:49.287  6240  6318 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:01:49.287  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:01:49.287  6240  6318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:01:49.287  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.287  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.287  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.287  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.287  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.287  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.287  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.287  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.287  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.287  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.287  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.287  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.287  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.287  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.288  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.288  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.288  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.288  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.289  1036  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:49.289  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:49.290  1036  1711 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:49.290  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.290  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.290  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.290  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.290  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.290  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.290  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.290  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.291  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.291  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.291  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.291  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.291  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.291  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.291  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.291  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.291  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.291  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.292  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:49.292  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:49.292  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:49.292  6240  6346 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 16:01:49.292  6240  6346 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 16:01:49.293  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:49.293  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.293  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.293  6240  6318 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f238fad not in the list
08-30 16:01:49.293  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.293  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.293  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:49.293  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.293  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.293  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:49.293  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:49.294  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:49.294  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:49.294  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:49.294  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b912e2 not in the list
08-30 16:01:49.295  6240  6318 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 16:01:49.295  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:01:49.295  6240  6318 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 16:01:49.295  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:01:49.295  6240  6318 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 16:01:49.295  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:01:49.296  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:01:49.296  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 16:01:49.297  6240  6318 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 16:01:49.297  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:01:49.297  6240  6318 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 16:01:49.297  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:01:49.297  6240  6318 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 16:01:49.297  6240  6318 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 16:01:49.297  6240  6318 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 16:01:49.297  6240  6318 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 16:01:49.298  6240  6318 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 16:01:49.298  6240  6318 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 16:01:49.298  6240  6318 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 16:01:49.298  6240  6240 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 16:01:49.298  6240  6318 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 16:01:49.313  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:01:49.313  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@238fe0eb added. We now have 2 listener(s)
08-30 16:01:49.313  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:49.314  6240  6318 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 16:01:49.315  1036  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6240, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:01:49.315  1036  1051 D WifiService: setWifiEnabled: true pid=6240, uid=10118
08-30 16:01:49.315  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:01:49.316  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:49.317  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b8c8e48 added. We now have 3 listener(s)
08-30 16:01:49.317  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:49.320  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:49.321  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21e2b4e1 added. We now have 4 listener(s)
08-30 16:01:49.321  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:49.322  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:49.323  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a9c206 added. We now have 5 listener(s)
08-30 16:01:49.323  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:49.327  1036  2056 D WifiServiceImplEx: setWifiEnabled: false pid=6240, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:01:49.328  1036  2056 D WifiService: setWifiEnabled: false pid=6240, uid=10118
08-30 16:01:49.328  1036  2056 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:01:49.332  6240  6338 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 16:01:49.333  6240  6338 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 760)
08-30 16:01:49.336  1036  1711 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:49.336  1036  1711 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@66fe135 mBinding = false
08-30 16:01:49.337  1036  1438 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:49.337  1036  1438 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:49.337  1036  1438 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:49.338  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:01:49.338  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:01:49.338  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:01:49.338  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:49.339  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:49.339  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 16:01:49.339  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:49.339  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-30 16:01:49.339  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:49.339  1036  1392 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@135bf09e
08-30 16:01:49.339  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:49.339  1036  1392 D LGWifiP2pService: P2pDisablingState
08-30 16:01:49.339  1036  1392 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:49.339  1036  1392 D LGWifiP2pService: p2p socket connection lost
08-30 16:01:49.340  1036  1392 D LGWifiP2pService: P2pDisabledState
08-30 16:01:49.340  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 16:01:49.340  1984  1984 D WfdsService: WifiP2pState is changed : false
08-30 16:01:49.341  1984  2321 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 16:01:49.341  1984  2321 D WfdsService: Set the WFDS Monitor: false
08-30 16:01:49.342  1984  2321 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:01:49.342  1984  2321 D WfdsService: STATE : WfdsDisabledState - enter
08-30 16:01:49.342  1984  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 16:01:49.343  1984  2812 D CtrlSupplicant: Received on exit socket, terminate
08-30 16:01:49.343  1984  2812 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 16:01:49.343  1984  2812 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 16:01:49.343  1984  2812 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 16:01:49.343  1036  1438 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 16:01:49.343   318   906 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:01:49.345  1984  2321 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 16:01:49.346  1036  1097 D BluetoothManagerService: Message: 2
08-30 16:01:49.347  1036  1097 D BluetoothManagerService: Sending off request.
08-30 16:01:49.348  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 16:01:49.348  3802  3822 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 16:01:49.348  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:49.348  3802  3885 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 16:01:49.348  3802  3885 D BluetoothAdapterProperties: Setting state to 13
08-30 16:01:49.348  3802  3885 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 16:01:49.349  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:49.349  3802  3885 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 16:01:49.349  3802  3885 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 16:01:49.350  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 16:01:49.351  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:49.352  3802  3891 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:01:49.352  3802  3885 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 16:01:49.352  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:01:49.352  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 16:01:49.352  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 16:01:49.352  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 16:01:49.353  3802  3966 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-30 16:01:49.353  3802  3885 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:01:49.353  3802  4169 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:01:49.353  3802  4127 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:01:49.354  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.354  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:49.355  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:49.355  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:49.355  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:01:49.355  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:01:49.355  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:01:49.355  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:01:49.356  3802  4167 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:01:49.356  3802  4172 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 16:01:49.356  3802  4123 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 16:01:49.356  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is, disabled - will return stored value
08-30 16:01:49.357  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:49.357  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:49.357  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:49.358  3802  3802 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:49.358  3802  3802 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:01:49.358  3802  3802 V BtOppService: Receiver DISABLED_ACTION 
08-30 16:01:49.359  3802  3802 V BluetoothMapService: Handler(): got msg=4
08-30 16:01:49.359  3802  3802 D BluetoothMapService: MAP Service closeService in
08-30 16:01:49.359  3802  3802 D BluetoothMapMasInstance: MAP Service shutdown
08-30 16:01:49.359  3802  3802 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:01:49.359  3802  3802 V BluetoothMapService: MAP Service closeService out
08-30 16:01:49.359  3802  3802 I BtOppRfcommListener: stopping Accept Thread
08-30 16:01:49.359  3802  3802 V BtOppRfcommListener: close mBtServerSocket
08-30 16:01:49.359  3802  3802 V BtOppRfcommListener: waiting for thread to terminate
08-30 16:01:49.360  3802  4167 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:01:49.360  3802  3802 V BtOppRfcommListener: done waiting for thread to terminate
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 16:01:49.360  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 16:01:49.360  3802  3966 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 16:01:49.361  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.362  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:49.364  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.364  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:49.365  6240  6240 W org.thaliproject.p2p.,btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:49.365  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:49.366  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.366  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.367  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.371  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:01:49.403  1036  1093 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6356 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:01:49.403  1036  1438 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 16:01:49.404  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 16:01:49.405  1036  1438 D WifiNative-p2p0: TERMINATE: returned true
08-30 16:01:49.406  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:01:49.406  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:01:49.406  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:01:49.406  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:49.406  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:49.406  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:01:49.407  3802  3802 V BtOppService: onDestroy
08-30 16:01:49.408  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 16:01:49.408  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:49.409  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:49.449  1036  2028 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6374 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:01:49.451  3802  3802 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 16:01:49.455  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 16:01:49.456  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:49.458  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 16:01:49.458  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.458  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:49.458  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:49.459  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:49.459  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:49.459  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 16:01:49.461  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:49.461  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:01:49.461  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:49.461  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:49.478  6356  6356 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:01:49.478  6356  6356 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 16:01:49.478  6356  6356 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 16:01:49.478  6356  6356 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 16:01:49.480  6356  6356 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 16:01:49.481  6356  6356 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 16:01:49.494  2657  2657 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 16:01:49.494  2657  2657 I wpa_supplicant: monitor socket send errors count : 1
08-30 16:01:49.494  2657  2657 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1984-2\x00 that cannot receive messages
,08-30 16:01:49.496  1036  2794 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 16:01:49.497  1036  2794 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 16:01:49.527  6374  6374 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 16:01:49.530  6374  6374 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:01:49.531  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:49.532  1036  2074 I ActivityManager: Killing 4886:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 16:01:49.532  2657  2657 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:01:49.533  1036  1097 D Tethering: InitialState.processMessage what=4
08-30 16:01:49.533  1036  2794 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-30 16:01:49.533  1036  2794 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:01:49.533  1036  2794 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:01:49.533  2657  2657 W wpa_supplicant: USIM:  scard_deinit function
08-30 16:01:49.534  1036  2794 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 16:01:49.534  1036  2794 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:01:49.534  1036  2794 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:01:49.535  1036  1438 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189189
08-30 16:01:49.535  1036  1438 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189190
08-30 16:01:49.536  1036  1438 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=189190  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:01:49.536  1036  1438 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=189191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:01:49.561  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:01:49.562  1036  2128 W libprocessgroup: failed to open /acct/uid_10014/pid_4886/cgroup.procs: No such file or directory
,08-30 16:01:49.564  1036  1438 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:49.564  1036  1438 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:49.565   318  6394 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 16:01:49.565  1036  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 16:01:49.612  6356  6356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 16:01:49.619  3802  3802 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:01:49.619  3802  3802 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:49.619  3802  3802 V BluetoothPbapReceiver: ***********state = 13
08-30 16:01:49.621  3802  3802 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 16:01:49.622  3802  3802 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:49.622  3802  3802 V BluetoothPbapService: state: 13
08-30 16:01:49.622  3802  3802 V BluetoothPbapService: Pbap Service closeService in
08-30 16:01:49.626  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:01:49.629  3802  3802 V BluetoothPbapService: successfully stopped pbap service
08-30 16:01:49.629  3802  3802 V BluetoothPbapService: Pbap Service closeService out
08-30 16:01:49.629  3802  3802 V BluetoothPbapService: Pbap Service onDestroy
08-30 16:01:49.629  3802  3802 V BluetoothPbapService: Pbap Service closeService in
08-30 16:01:49.630  3802  3802 V BluetoothPbapService: Pbap Service closeService out
08-30 16:01:49.630  3802  3802 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 16:01:49.636  2657  2657 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 16:01:49.636  1036  2794 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 16:01:49.636  1036  2794 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 16:01:49.636  1036  2794 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 16:01:49.637  1036  1438 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
,08-30 16:01:49.647  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:49.668  1036  1052 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6396 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 16:01:49.683  6356  6356 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:01:49.684  6356  6356 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:01:49.694  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:01:49.703  1036  1097 D BluetoothManagerService: Message: 20
,08-30 16:01:49.703  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3062c17:true
08-30 16:01:49.714  1036  1097 D BluetoothManagerService: Message: 30
08-30 16:01:49.719  1036  1097 D BluetoothManagerService: Message: 30
,08-30 16:01:49.724  6356  6356 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 16:01:49.726  6356  6356 D BluetoothMap: Create BluetoothMap proxy object
08-30 16:01:49.726  1036  1097 D BluetoothManagerService: Message: 30
08-30 16:01:49.730  1036  1097 D BluetoothManagerService: Message: 30
,08-30 16:01:49.732  6356  6356 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 16:01:49.733  6356  6356 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 16:01:49.739  1984  1984 D WfdsService: Supplicant Connection state is changed : false
08-30 16:01:49.739  1984  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 16:01:49.739  1984  2321 D WfdsService: Set the WFDS Monitor: false
08-30 16:01:49.739  1984  2321 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:01:49.739  1036  1438 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 16:01:49.740  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:01:49.740  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:01:49.740  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:01:49.742  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:49.743  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-30 16:01:49.744  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 16:01:49.744  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:49.744  1036  1467 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 16:01:49.744  1036  1467 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 16:01:49.745  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.747  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:49.750  6356  6356 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-30 16:01:49.756  6356  6356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 16:01:49.766  6356  6356 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:01:49.775  6356  6356 D BluetoothInputDevice: Proxy object connected
08-30 16:01:49.776  6356  6356 D HidProfile: Bluetooth service connected
08-30 16:01:49.777  6356  6356 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:01:49.777  6356  6356 D PanProfile: Bluetooth service connected
,08-30 16:01:49.779  6356  6356 D BluetoothMap: Proxy object connected
08-30 16:01:49.779  6356  6356 D MapProfile: Bluetooth service connected
08-30 16:01:49.779  6356  6356 D BluetoothMap: getConnectedDevices()
08-30 16:01:49.780  6356  6356 D BluetoothMap: Bluetooth is Not enabled
08-30 16:01:49.780  6356  6356 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 16:01:49.785  6240  6240 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 16:01:49.833  1036  1711 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6420 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-30 16:01:49.835  1036  1711 I ActivityManager: Killing 5684:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-30 16:01:49.896  1036  1959 W libprocessgroup: failed to open /acct/uid_10004/pid_5684/cgroup.procs: No such file or directory
08-30 16:01:49.896  6396  6396 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 16:01:49.896  6396  6396 W LG Account v2.2: No ProfileInfo entries
08-30 16:01:49.896  6396  6396 I LG Account v2.2: isEnabled: false
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Country: EU
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Operator: OPEN
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Ranking support: false
,08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Comfort support: false
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Accessory: true
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Health device: true
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Extra Pedometer: false
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Blood glucose device: false
08-30 16:01:49.897  6396  6396 I Feature : [Lifetracker]Device Number: 3
08-30 16:01:49.920  6356  6356 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 16:01:49.931  6356  6356 D BluetoothPermissionRequest: onReceive
08-30 16:01:49.935  6356  6356 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 16:01:49.944  6420  6420 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 16:01:49.950  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 16:01:49.954  1036  1711 I ActivityManager: Killing 5802:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 16:01:49.988  3802  3802 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 16:01:49.988  3802  3802 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 16:01:49.988  3802  3802 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 16:01:49.990  1036  2129 W libprocessgroup: failed to open /acct/uid_10008/pid_5802/cgroup.procs: No such file or directory
,08-30 16:01:49.991  6420  6420 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 16:01:49.999  3802  3802 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:50.000  3802  3802 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 16:01:50.005  3802  3802 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:01:50.005  3802  3802 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:50.006  3802  3802 V BluetoothFtpService: Ftp Service closeService
08-30 16:01:50.006  3802  3802 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-30 16:01:50.007  3802  3802 V BluetoothFtpService: successfully stopped ftp service
08-30 16:01:50.009  3802  3802 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:01:50.009  3802  3802 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:01:50.009  3802  3802 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:01:50.009  3802  3802 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:50.009  3802  3802 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 16:01:50.009  3802  3802 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:01:50.011  3802  3802 V BluetoothFtpService: Ftp Service onDestroy
08-30 16:01:50.011  3802  3802 V BluetoothFtpService: Ftp Service closeService
08-30 16:01:50.051  6420  6420 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 16:01:50.051  6420  6420 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 16:01:50.052  6420  6420 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 16:01:50.052  6420  6420 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 16:01:50.053  6420  6420 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 16:01:50.055  6420  6420 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 16:01:50.063  6420  6420 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 16:01:50.079  1036  1956 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6439 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:01:50.083  3802  3802 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:50.083  3802  3802 V BluetoothSapService: state: 13
08-30 16:01:50.083  3802  3802 V BluetoothSapService: Stopping SAP server process
08-30 16:01:50.084  3802  3802 V BluetoothSapService: Sap Service closeSapService in
08-30 16:01:50.084  3802  3802 V BluetoothSapService: Close listen Socket : 
08-30 16:01:50.084  3802  3802 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:01:50.084  3802  3802 V BluetoothSapService: Close sapd  Socket : 
08-30 16:01:50.086  3802  3802 V BluetoothSapService: Sap Service closeSapService out
08-30 16:01:50.086  3802  3802 V BluetoothSapService: Sap Service onDestroy
08-30 16:01:50.086  3802  3802 V BluetoothSapService: Sap Service closeSapService in
08-30 16:01:50.086  3802  3802 V BluetoothSapService: Close listen Socket : 
08-30 16:01:50.086  3802  3802 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:01:50.086  3802  3802 V BluetoothSapService: Close sapd  Socket : 
08-30 16:01:50.086  3802  3802 V BluetoothSapService: Sap Service closeSapService out
08-30 16:01:50.095  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:01:50.101  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:50.114  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 16:01:50.118  6420  6420 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 16:01:50.119  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:50.122  6420  6420 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 16:01:50.123  6374  6374 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:01:50.123  6374  6374 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:01:50.123  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:50.128  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:50.135  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:50.143  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:50.143  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:01:50.145  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:01:50.150  6439  6439 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:01:50.211  1036  2013 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6459 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 16:01:50.217  1036  2013 I ActivityManager: Killing 5833:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-30 16:01:50.285  1036  2074 W libprocessgroup: failed to open /acct/uid_10011/pid_5833/cgroup.procs: No such file or directory
,08-30 16:01:50.365  3802  3966 W bt-btif : ag scb idx 1 not allocated
08-30 16:01:50.365  3802  3891 D bt_hci_bdroid: cleanup
08-30 16:01:50.365  3802  3966 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:01:50.365  3802  4092 I bt_userial_mct: exiting userial_read_thread
08-30 16:01:50.365  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:01:50.365  3802  4092 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 16:01:50.366  3802  3968 I bt_lpm  : LPM is already off!!!
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:01:50.366  3802  3891 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:01:50.366  3802  3968 I bt_vendor: hw_epilog_process
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:01:50.366  3802  3966 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:01:50.366  3802  3966 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 16:01:50.366  3802  3891 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 16:01:50.366  3802  3891 D bt_userial_mct: userial_close
08-30 16:01:50.366  3802  3891 E bt_userial_mct: pthread_join() FAILED result:3
08-30 16:01:50.366  3802  3891 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 16:01:50.386  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:01:50.391  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:01:50.404  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:50.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:01:50.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-30 16:01:50.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:01:50.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:01:50.429  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:01:50.432  6459  6482 W FormManager: Network not available. Please check & try again.
08-30 16:01:50.434  3802  3891 D bt_hci_bdroid: set_power 0
08-30 16:01:50.434  3802  3891 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 16:01:50.434  3802  3891 I bt_vendor: bluetooth satus is on
08-30 16:01:50.434  3802  3891 I bt_vendor: bt-vendor : resetting BT status
08-30 16:01:50.434  3802  3891 I bt_vendor: Starting hciattach daemon
08-30 16:01:50.434  3802  3891 I bt_vendor: try to set false
08-30 16:01:50.435  3802  3891 I bt_vendor: Starting hciattach daemon
08-30 16:01:50.435  3802  3891 I bt_vendor: try to set false
08-30 16:01:50.436  3802  3891 I bt_vendor: cleanup
08-30 16:01:50.436  3802  3966 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 16:01:50.437  3802  3891 I GKI_LINUX: GKI_exit_task 0 done
08-30 16:01:50.437  3802  3891 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 16:01:50.438  3802  3885 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 16:01:50.442  3802  3802 D HeadsetService: Received stop request...Stopping profile...
08-30 16:01:50.446  3802  3802 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:01:50.446  3802  3802 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:01:50.446  3802  3919 D HeadsetStateMachine: Exit Disconnected: -1
08-30 16:01:50.446  3802  3802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6a0c39
08-30 16:01:50.448  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-30 16:01:50.448  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 16:01:50.449  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-30 16:01:50.449  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-30 16:01:50.449  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-30 16:01:50.451  3802  3802 D A2dpService: Received stop request...Stopping profile...
08-30 16:01:50.452  3802  3950 D A2dpStateMachine: Exit Disconnected: -1
08-30 16:01:50.452  3802  3802 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-30 16:01:50.454  3802  3802 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 16:01:50.454  3802  3802 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:01:50.455  3802  3802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6a0c39
08-30 16:01:50.458  3802  3885 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 16:01:50.458  3802  3802 D HidService: Received stop request...Stopping profile...
08-30 16:01:50.458  3802  3802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6a0c39
08-30 16:01:50.459  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-30 16:01:50.459  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 16:01:50.459  3802  3802 D HealthService: Received stop request...Stopping profile...
08-30 16:01:50.460  3802  3802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6a0c39
08-30 16:01:50.460  3802  3802 D HeadsetStateMachine: Unbinding service...
08-30 16:01:50.462  3802  3802 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:01:50.462  3802  3802 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:01:50.462  3802  3802 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:01:50.462  3802  3802 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:01:50.462  3802  3802 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:01:50.462  3802  3802 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:01:50.462  3802  3802 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:01:50.463  3802  3802 D PanService: Received stop request...Stopping profile...
08-30 16:01:50.465  3802  3802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6a0c39
,08-30 16:01:50.468  3802  3802 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:01:50.469  3802  3802 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 16:01:50.469  3802  3802 D BtGatt.GattService: stop()
08-30 16:01:50.469  3802  3802 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 16:01:50.470  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:01:50.470  3802  3802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6a0c39
08-30 16:01:50.471  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:01:50.471  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:01:50.471  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:01:50.471  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:01:50.471  6459  6483 V FormManager: Network unavailable.
08-30 16:01:50.472  3802  3802 I BluetoothA2dpServiceJni: cleanupNative
08-30 16:01:50.472  3802  3951 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 16:01:50.473  3802  3802 I GKI_LINUX: GKI_exit_task 2 done
08-30 16:01:50.473  3802  3802 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 16:01:50.473  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:01:50.473  6356  6356 D BluetoothInputDevice: Proxy object disconnected
08-30 16:01:50.473  6356  6356 D HidProfile: Bluetooth service disconnected
08-30 16:01:50.474  6356  6356 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:01:50.474  6356  6356 D PanProfile: Bluetooth service disconnected
08-30 16:01:50.474  3802  3802 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:01:50.474  3802  3802 D BluetoothMapService: stop()
08-30 16:01:50.477  3802  3802 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 16:01:50.477  3802  3802 D BluetoothMapEmailAppObserver: removeReceiver()
,08-30 16:01:50.478  3802  3802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6a0c39
08-30 16:01:50.480  3802  3802 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:01:50.480  3802  3802 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:01:50.481  3802  3802 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 16:01:50.481  3802  3802 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:01:50.481  3802  3802 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:01:50.481  6459  6483 V FormManager: Network unavailable.
08-30 16:01:50.481  3802  3802 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:01:50.481  3802  3802 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:01:50.481  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:01:50.482  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:01:50.483  3802  3802 V BluetoothMapService: Handler(): got msg=4
08-30 16:01:50.483  3802  3802 D BluetoothMapService: MAP Service closeService in
08-30 16:01:50.483  3802  3802 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:01:50.483  3802  3802 V BluetoothMapService: MAP Service closeService out
08-30 16:01:50.483  6356  6356 D BluetoothMap: Proxy object disconnected
08-30 16:01:50.483  6356  6356 D MapProfile: Bluetooth service disconnected
08-30 16:01:50.484  3802  3885 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 16:01:50.484  3802  3885 D BluetoothAdapterProperties: Setting state to 10
08-30 16:01:50.484  3802  3885 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 16:01:50.484  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:01:50.484  3802  3885 I BluetoothAdapterState: Entering OffState
08-30 16:01:50.484  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 16:01:50.484  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 16:01:50.484  3802  3802 D BluetoothMapService: cleanup()
08-30 16:01:50.484  3802  3802 D BluetoothMapService: MAP Service closeService in
08-30 16:01:50.484  3802  3802 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:01:50.484  3802  3802 V BluetoothMapService: MAP Service closeService out
08-30 16:01:50.485  6356  6372 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:01:50.486  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:01:50.486  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:01:50.486  1877  2862 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:01:50.487  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:01:50.488  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:01:50.488  6356  6373 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 16:01:50.489  6356  6372 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:01:50.491  6356  6373 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:01:50.494  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 16:01:50.494  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:50.494  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 16:01:50.496  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:50.497  1036  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 16:01:50.497  1036  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 16:01:50.497  1036  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@66fe135 mBinding = false
08-30 16:01:50.498  1036  1097 D BluetoothManagerService: Sending unbind request.
08-30 16:01:50.502  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-30 16:01:50.507  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:50.509  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:50.509  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:01:50.511  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:50.511  1984  2179 D LGBluetoothAPIService: Message: 2
08-30 16:01:50.511  1984  2179 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@7f0f502 mBinding = false
08-30 16:01:50.511  4272  6487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:01:50.511  1984  2179 D LGBluetoothAPIService: Sending unbind request.
08-30 16:01:50.512  3802  3891 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 16:01:50.512  3802  3802 I GKI_LINUX: GKI_exit_task 1 done
08-30 16:01:50.512  3802  3802 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 16:01:50.513  3802  3802 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 16:01:50.513  3802  3802 I art     : --- WEIRD: removing null entry 246
08-30 16:01:50.513  3802  3802 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 16:01:50.513  3802  3802 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 16:01:50.513  4272  6487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:01:50.514  6356  6356 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:01:50.515  6356  6356 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 16:01:50.516  6356  6356 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-30 16:01:50.519  3802  3802 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 16:01:50.520  1602  1602 D BluetoothAdapter: 960388475: getState() :  mService = null. Returning STATE_OFF
08-30 16:01:50.521  1602  1602 D BluetoothAdapter: 960388475: getState() :  mService = null. Returning STATE_OFF
08-30 16:01:50.522  6356  6356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 16:01:50.523  3802  3802 I art     : System.exit called, status: 0
08-30 16:01:50.523  3802  3802 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 16:01:50.525  6374  6374 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 16:01:50.525  6374  6374 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:01:50.525  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:50.537  4272  6486 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 16:01:50.543   322  1399 V AudioFlinger: 3802 died, releasing its sessions
08-30 16:01:50.543   322  1399 V AudioFlinger:  pid 1877 @ 0
08-30 16:01:50.543   322  1399 V AudioFlinger:  pid 3343 @ 1
,08-30 16:01:50.543   322  1399 V AudioFlinger:  pid 3343 @ 2
08-30 16:01:50.545  6356  6356 D DockEventReceiver: finishStartingService: stopping service
08-30 16:01:50.546  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:01:50.552  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:50.552  6356  6356 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-30 16:01:50.633  1036  2075 I ActivityManager: Process com.android.bluetooth (pid 3802) has died
,08-30 16:01:50.634  1036  2075 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 16:01:50.722  1036  1051 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6498 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 16:01:50.725  6459  6490 W FormManager: Network not available. Please check & try again.
08-30 16:01:50.740  6459  6491 V FormManager: Network unavailable.
,08-30 16:01:50.752  6459  6491 V FormManager: Network unavailable.
08-30 16:01:50.754  6420  6420 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 16:01:50.756  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 16:01:50.756  6420  6420 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 16:01:50.767  1036  2075 I ActivityManager: Killing 5851:com.android.contacts/u0a19 (adj 15): empty #17
08-30 16:01:50.800  6420  6420 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 16:01:50.800  6420  6420 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:01:50.809  6420  6420 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 16:01:50.810  6420  6420 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 16:01:50.810  6420  6420 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 16:01:50.811  6420  6420 V SoundPool: doLoad: loading sample sampleID=1
08-30 16:01:50.812  6420  6420 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 16:01:50.814  6420  6518 V SoundPool: Start decode
08-30 16:01:50.814  6420  6518 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 16:01:50.815   322  3923 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 16:01:50.815   322  3923 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 16:01:50.815   322  3923 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 16:01:50.815   322  3923 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 16:01:50.815   322  3923 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 16:01:50.815   322  3923 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 16:01:50.815   322  3923 V MediaPlayerService: player type = 3
08-30 16:01:50.815   322  3923 V AwesomePlayer: AwesomePlayer create()
08-30 16:01:50.815   322  3923 V AwesomePlayer: reset_l() 
08-30 16:01:50.815   322  3923 V AwesomePlayer: cancelPlayerEvents
08-30 16:01:50.815   322  3923 V AwesomePlayer: setAudioSink() 
08-30 16:01:50.816   322  3923 V AwesomePlayer: reset_l() 
08-30 16:01:50.816   322  3923 V AudioCache: notify(0xb5474680, 8, 0, 0)
08-30 16:01:50.816   322  3923 V AudioCache: ignored
08-30 16:01:50.816   322  3923 V AwesomePlayer: cancelPlayerEvents
08-30 16:01:50.816   322  3923 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 16:01:50.816   322  3923 V AwesomePlayer: setDataSource_l dataSource
08-30 16:01:50.816   322  3923 V LGParserOSAL: SniffLGParser start
08-30 16:01:50.816   322  3923 V LGParserOSAL: MainType:5, SubType=0
08-30 16:01:50.816   322  3923 V LGParserOSAL: #### check Mime : application/ogg
08-30 16:01:50.816   322  3923 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 16:01:50.816   322  3923 E MediaExtractor: Use LGExtractor :application/ogg 
,08-30 16:01:50.844  1036  2129 W libprocessgroup: failed to open /acct/uid_10019/pid_5851/cgroup.procs: No such file or directory
,08-30 16:01:50.854  6147  6147 D UEI.SmartControl: QS Service created
,08-30 16:01:50.859  6420  6420 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 16:01:50.864  6420  6420 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:01:50.865  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 16:01:50.872   322  3923 V LGParserOSAL: supported mime: application/ogg
08-30 16:01:50.872   322  3923 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 16:01:50.872   322  3923 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-30 16:01:50.872   322  3923 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 16:01:50.872   322  3923 V AwesomePlayer: AudioTrack Setting
08-30 16:01:50.872   322  3923 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 16:01:50.872  6147  6147 I UEI.SmartControl: Service initServices...
08-30 16:01:50.872   322  3923 V AwesomePlayer: setAudioSource() 
08-30 16:01:50.872   322  3923 V MediaPlayerService: prepare
08-30 16:01:50.872   322  3923 V AwesomePlayer: prepareAsync_l() 
08-30 16:01:50.873  6147  6147 D UEI.SmartControl: QS start get config
08-30 16:01:50.874   322  3923 V MediaPlayerService: wait for prepare
08-30 16:01:50.875   322  6519 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 16:01:50.875   322  6519 V AwesomePlayer: initAudioDecoder() 
08-30 16:01:50.875   322  6519 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 16:01:50.875   322  6519 V AudioSystem: isOffloadSupported()
08-30 16:01:50.875   322  6519 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 16:01:50.875   322  6519 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 16:01:50.875   322  6519 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 16:01:50.875   322  6519 V AwesomePlayer: getUseOffload() = 0 
08-30 16:01:50.875   322  6519 V OMXCodec: OMXCodec::Create
08-30 16:01:50.875   322  6519 V OMXCodec: findMatchingCodecs()
08-30 16:01:50.875   322  6519 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 16:01:50.875   322  6519 V OMXCodec: matchingCodecs.size()=1
08-30 16:01:50.875   322  6519 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 16:01:50.877   322  6519 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 16:01:50.877   322  6519 V LGCodecAdapter: LG Codec Adapter start
08-30 16:01:50.877   322  6519 V OMXCodec: OMXCodec Createtor
08-30 16:01:50.877   322  6519 V OMXCodec: setComponentRole
08-30 16:01:50.877   322  6519 V OMXCodec: configureCodec protected=0
08-30 16:01:50.878   322  6519 V LGCodecAdapter: called getLGCodecSpecificData
08-30 16:01:50.878   322  6519 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 16:01:50.878   322  6519 V LGCodecOSAL: Called LGconfigureCodecMETA
,08-30 16:01:50.878   322  6519 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 16:01:50.878   322  6519 V LGCodecOSAL: Not support LGCodec
08-30 16:01:50.878   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 16:01:50.878   322  6519 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 16:01:50.878   322  6519 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 16:01:50.878   322  6519 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 16:01:50.878   322  6519 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 16:01:50.878   322  6519 V AudioSystem: isOffloadSupported()
08-30 16:01:50.878   322  6519 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 16:01:50.878   322  6519 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 16:01:50.878   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 16:01:50.878   322  6519 V OMXCodec: init()
08-30 16:01:50.878   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 16:01:50.878   322  6519 V OMXCodec: allocateBuffers
08-30 16:01:50.878   322  6519 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 16:01:50.878   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-30 16:01:50.879   322  6519 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-30 16:01:50.879   322  6519 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
08-30 16:01:50.879   322  6519 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 16:01:50.879   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 16:01:50.879   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 16:01:50.879   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 16:01:50.879   322  6519 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 16:01:50.879   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 16:01:50.879   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 16:01:50.879   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 16:01:50.879   322  6519 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 16:01:50.880   322  6519 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 16:01:50.880   322  6519 V AudioCache: notify(0xb5474680, 5, 0, 0)
08-30 16:01:50.880   322  6519 V AudioCache: ignored
08-30 16:01:50.880   322  6519 V AudioCache: notify(0xb5474680, 1, 0, 0)
08-30 16:01:50.880   322  6519 V AudioCache: prepared
08-30 16:01:50.880   322  3923 V AudioCache: wait - success
08-30 16:01:50.880   322  3923 V MediaPlayerService: star,t
08-30 16:01:50.880   322  3923 V AwesomePlayer: play_l() 
08-30 16:01:50.880   322  3923 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 16:01:50.880   322  3923 V AwesomePlayer: createAudioPlayer_l
08-30 16:01:50.880   322  3923 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 16:01:50.880   322  3923 V AwesomePlayer: startAudioPlayer_l() 
08-30 16:01:50.880   322  3923 D AudioPlayer: start of Playback, useOffload 0
08-30 16:01:50.880   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 16:01:50.880   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-30 16:01:50.883   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975264
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 16:01:50.884   322  6521 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 16:01:50.884   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 16:01:50.886   322  3923 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 16:01:50.887   322  3923 V AudioCache: notify(0xb5474680, 6, 0, 0)
08-30 16:01:50.887   322  3923 V AudioCache: ignored
08-30 16:01:50.887   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.887   322  6522 V AudioCache: memcpy(0xac100000, 0xb57f0000, 4096)
08-30 16:01:50.888   322  3923 V MediaPlayerService: wait for playback complete
08-30 16:01:50.894   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.894   322  6522 V AudioCache: memcpy(0xac101000, 0xb57f0000, 4096)
08-30 16:01:50.894   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.894   322  6522 V AudioCache: memcpy(0xac102000, 0xb57f0000, 4096)
08-30 16:01:50.895   322  6522 V AudioCache: write(0xb57f0000, 4096)
,08-30 16:01:50.895   322  6522 V AudioCache: memcpy(0xac103000, 0xb57f0000, 4096)
08-30 16:01:50.896  6498  6498 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 16:01:50.896   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.896   322  6522 V AudioCache: memcpy(0xac104000, 0xb57f0000, 4096)
08-30 16:01:50.897   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.897   322  6522 V AudioCache: memcpy(0xac105000, 0xb57f0000, 4096)
08-30 16:01:50.897  6498  6498 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:01:50.897   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.897   322  6522 V AudioCache: memcpy(0xac106000, 0xb57f0000, 4096)
08-30 16:01:50.898  6498  6498 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 16:01:50.898   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.898   322  6522 V AudioCache: memcpy(0xac107000, 0xb57f0000, 4096)
08-30 16:01:50.899   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.899   322  6522 V AudioCache: memcpy(0xac108000, 0xb57f0000, 4096)
08-30 16:01:50.900  6498  6498 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 16:01:50.904   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.904   322  6522 V AudioCache: memcpy(0xac109000, 0xb57f0000, 4096)
08-30 16:01:50.904   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.904   322  6522 V AudioCache: memcpy(0xac10a000, 0xb57f0000, 4096)
08-30 16:01:50.905   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.905   322  6522 V AudioCache: memcpy(0xac10b000, 0xb57f0000, 4096)
08-30 16:01:50.906   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.906   322  6522 V AudioCache: memcpy(0xac10c000, 0xb57f0000, 4096)
08-30 16:01:50.906   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.907   322  6522 V AudioCache: memcpy(0xac10d000, 0xb57f0000, 4096)
08-30 16:01:50.908   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.908   322  6522 V AudioCache: memcpy(0xac10e000, 0xb57f0000, 4096)
08-30 16:01:50.909   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.909   322  6522 V AudioCache: memcpy(0xac10f000, 0xb57f0000, 4096)
08-30 16:01:50.909   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.909   322  6522 V AudioCache: memcpy(0xac110000, 0xb57f0000, 4096)
08-30 16:01:50.910   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.910   322  6522 V AudioCache: memcpy(0xac111000, 0xb57f0000, 4096)
08-30 16:01:50.910   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.910   322  6522 V AudioCache: memcpy(0xac112000, 0xb57f0000, 4096)
08-30 16:01:50.911   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.911   322  6522 V AudioCache: memcpy(0xac113000, 0xb57f0000, 4096)
08-30 16:01:50.911   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.911   322  6522 V AudioCache: memcpy(0xac114000, 0xb57f0000, 4096)
08-30 16:01:50.912   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.912   322  6522 V AudioCache: memcpy(0xac115000, 0xb57f0000, 4096)
08-30 16:01:50.913   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.913   322  6522 V AudioCache: memcpy(0xac116000, 0xb57f0000, 4096)
08-30 16:01:50.914   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.914   322  6522 V AudioCache: memcpy(0xac117000, 0xb57f0000, 4096)
08-30 16:01:50.914   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.914   322  6522 V AudioCache: memcpy(0xac118000, 0xb57f0000, 4096)
08-30 16:01:50.915   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.915   322  6522 V AudioCache: memcpy(0xac119000, 0xb57f0000, 4096)
08-30 16:01:50.916   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.916   322  6522 V AudioCache: memcpy(0xac11a000, 0xb57f0000, 4096)
08-30 16:01:50.917   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.917   322  6522 V AudioCache: memcpy(0xac11b000, 0xb57f0000, 4096)
08-30 16:01:50.917  6420  6420 V LGMDMManager: Create singleton instance
08-30 16:01:50.918   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.918   322  6522 V AudioCache: memcpy(0xac11c000, 0xb57f0000, 4096)
08-30 16:01:50.918   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.918   322  6522 V AudioCache: memcpy(0xac11d000, 0xb57f0000, 4096)
08-30 16:01:50.919   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.919   322  6522 V AudioCache: memcpy(0xac11e000, 0xb57f0000, 4096)
08-30 16:01:50.920   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.920   322  6522 V AudioCache: memcpy(0xac11f000, 0xb57f0000, 4096)
08-30 16:01:50.920  6498  6498 D BluetoothAdapterApp: Loading JNI Library
08-30 16:01:50.921   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.921   322  6522 V AudioCache: memcpy(0xac120000, 0xb57f0000, 4096)
08-30 16:01:50.921   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.922   322  6522 V AudioCache: memcpy(0xac121000, 0xb57f0000, 4096)
08-30 16:01:50.922   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.922   322  6522 V AudioCache: memcpy(0xac122000, 0xb57f0000, 4096)
08-30 16:01:50.923   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.923   322  6522 V AudioCache: memcpy(0xac123000, 0xb57f0000, 4096)
08-30 16:01:50.924   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.924   322  6522 V AudioCache: memcpy(0xac124000, 0xb57f0000, 4096)
08-30 16:01:50.925   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.925   322  6522 V AudioCache: memcpy(0xac125000, 0xb57f0000, 4096)
08-30 16:01:50.925   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.925   322  6522 V AudioCache: memcpy(0xac126000, 0xb57f0000, 4096)
08-30 16:01:50.926   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.926   322  6522 V AudioCache: memcpy(0xac127000, 0xb57f0000, 4096)
08-30 16:01:50.927   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.927   322  6522 V AudioCache: memcpy(0xac128000, 0xb57f0000, 4096)
08-30 16:01:50.927   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.927   322  6522 V AudioCache: memcpy(0xac129000, 0xb57f0000, 4096)
08-30 16:01:50.928   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.928   322  6522 V AudioCache: memcpy(0xac12a000, 0xb57f0000, 4096)
08-30 16:01:50.929   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.929   322  6522 V AudioCache: memcpy(0xac12b000, 0xb57f0000, 4096)
08-30 16:01:50.930   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.930   322  6522 V AudioCache: memcpy(0xac12c000, 0xb57f0000, 4096)
08-30 16:01:50.930   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.930   322  6522 V AudioCache: memcpy(0xac12d000, 0xb57f0000, 4096)
08-30 16:01:50.931   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.931   322  6522 V AudioCache: memcpy(0xac12e000, 0xb57f0000, 4096)
08-30 16:01:50.932   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.932   322  6522 V AudioCache: memcpy(0xac12f000, 0xb57f0000, 4096)
08-30 16:01:50.932   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.932   322  6522 V AudioCache: memcpy(0xac130000, 0xb57f0000, 4096)
08-30 16:01:50.933   322  6522 V AudioCache: write(0xb57f0000, 4096)
08-30 16:01:50.933   322  6522 V AudioCache: memcpy(0xac131000, 0xb57f0000, 4096)
08-30 16:01:50.933   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 16:01:50.933   322  6522 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 16:01:50.933   322  6522 V AwesomePlayer: postAudioEOS() 
08-30 16:01:50.933   322  6522 V AudioCache: write(0xb57f0000, 280)
08-30 16:01:50.933   322  6522 V AudioCache: memcpy(0xac132000, 0xb57f0000, 280)
08-30 16:01:50.943   322  6519 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 16:01:50.943   322  6519 V AwesomePlayer: onStreamDone
08-30 16:01:50.943   322  6519 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 16:01:50.943   322  6519 V AudioCache: notify(0xb5474680, 2, 0, 0)
08-30 16:01:50.943   322  6519 V AudioCache: playback complete
08-30 16:01:50.943   322  6519 V AwesomePlayer: pause_l() 
08-30 16:01:50.943   322  6519 V AudioCache: notify(0xb5474680, 7, 0, 0)
08-30 16:01:50.943   322  6519 V AudioCache: ignored
08-30 16:01:50.943   322  6519 V AwesomePlayer: cancelPlayerEvents
08-30 16:01:50.943   322  3923 V AudioCache: wait - success
08-30 16:01:50.943   322  3923 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 16:01:50.943   322  6519 D AudioPlayer: Pause Playback at 1068125
08-30 16:01:50.944   322  3923 V AwesomePlayer: reset_l() 
08-30 16:01:50.944   322  3923 V AudioCache: notify(0xb5474680, 8, 0, 0)
08-30 16:01:50.944   322  3923 V AudioCache: ignored
08-30 16:01:50.944   322  3923 V AwesomePlayer: cancelPlayerEvents
08-30 16:01:50.944   322  3923 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 16:01:50.944   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 16:01:50.944   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 16:01:50.944   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 16:01:50.944   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 16:01:50.944   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 16:01:50.945   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 16:01:50.945   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 16:01:50.945   322  6521 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 16:01:50.945   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 16:01:50.945   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 16:01:50.945   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 16:01:50.946   322  3923 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 16:01:50.946   322  3923 D AudioPlayer: AudioPlayer releasing audio source
08-30 16:01:50.946   322  3923 D AudioPlayer: AudioPlayer done releasing audio source
08-30 16:01:50.946   322  3923 V AwesomePlayer: reset_l() 
08-30 16:01:50.947   322  3923 V AwesomePlayer: cancelPlayerEvents
08-30 16:01:50.947   322  3923 V AwesomePlayer: ~AwesomePlayer call
08-30 16:01:50.947   322  3923 V AwesomePlayer: reset_l() 
08-30 16:01:50.947   322  3923 V AwesomePlayer: cancelPlayerEvents
08-30 16:01:50.947  6420  6518 V SoundPool: close(31)
08-30 16:01:50.948  6420  6518 V SoundPool: pointer = 0xa0006000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 16:01:50.955  6498  6498 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1185c4a6 Instance Count = 1
08-30 16:01:50.961  6498  6498 D BluetoothAdapterApp: onCreate
,08-30 16:01:50.982  6498  6498 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 16:01:50.982  6498  6498 D ProfileConfigQcom: Adding HeadsetService
08-30 16:01:50.982  6498  6498 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 16:01:50.982  6498  6498 D ProfileConfigQcom: Adding A2dpService
08-30 16:01:50.983  6498  6498 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 16:01:50.983  6498  6498 D ProfileConfigQcom: Adding HidService
08-30 16:01:50.983  6498  6498 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 16:01:50.983  6498  6498 D ProfileConfigQcom: Adding HealthService
08-30 16:01:50.984  6498  6498 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-30 16:01:50.985  6498  6498 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 16:01:50.985  6498  6498 D ProfileConfigQcom: Adding PanService
08-30 16:01:50.985  6498  6498 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 16:01:50.986  6498  6498 D ProfileConfigQcom: Adding GattService
08-30 16:01:50.986  6498  6498 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 16:01:50.986  6498  6498 D ProfileConfigQcom: Adding BluetoothMapService
08-30 16:01:50.986  6498  6498 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 16:01:50.987  6498  6498 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:01:50.988  6498  6498 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:50.988  6498  6498 V BluetoothPbapReceiver: ***********state = 10
08-30 16:01:50.990  6498  6498 V LGMDMManagerInternal: Create singleton instance
08-30 16:01:50.991  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 16:01:50.992  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 16:01:50.994  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7835
08-30 16:01:51.051  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:01:51.060  6356  6356 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 16:01:51.064  6356  6356 D BluetoothPermissionRequest: onReceive
08-30 16:01:51.066  6356  6356 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 16:01:51.066  6356  6356 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 16:01:51.069  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 16:01:51.073  6498  6498 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 16:01:51.078  6498  6498 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:51.081  6498  6498 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 16:01:51.081  6498  6498 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:01:51.081  6498  6498 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:01:51.082  6498  6498 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:51.082  6498  6498 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 16:01:51.089  6439  6439 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 16:01:51.295  6147  6147 I UEI.SmartControl: Supports setup maps: true
,08-30 16:01:51.301  6147  6147 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 16:01:51.301  6147  6147 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 16:01:51.301  6147  6147 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 16:01:51.301  6147  6147 I UEI.SmartControl: ### init IR Blaster...
08-30 16:01:51.305  6147  6147 D serial_port: Configuring serial port
08-30 16:01:51.305  6147  6147 E UEI.SmartControl: UEIBLaster setting for 616
08-30 16:01:51.306  6147  6147 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 16:01:51.306  6147  6147 I UEI.SmartControl: configuring settings for MAXQ616
08-30 16:01:51.306  6147  6147 I UEI.SmartControl: Get version...
08-30 16:01:51.324  6147  6528 D UEI.SmartControl: serial port data available: 21
,08-30 16:01:51.351  6147  6147 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 16:01:51.351  6147  6147 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 16:01:51.351  6147  6147 I UEI.SmartControl: QS saving settings...
08-30 16:01:51.355  6147  6147 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 16:01:51.372  6147  6528 D UEI.SmartControl: serial port data available: 4
,08-30 16:01:51.401  6147  6534 I UEI.SmartControl: Device manager: loading config....
,08-30 16:01:51.403  6147  6534 D UEI.SmartControl: ----------- loading internal config...
,08-30 16:01:51.403  6147  6147 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 16:01:51.407  6147  6147 E UEI.SmartControl: Services init done
08-30 16:01:51.407  6147  6147 D UEI.SmartControl: QS Service init finished
08-30 16:01:51.409  6147  6147 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 16:01:51.410  6147  6147 D UEI.SmartControl: QS Service version code: 201091
,08-30 16:01:51.410  6147  6147 D UEI.SmartControl: Service requested: Control
08-30 16:01:51.411  6147  6534 E UEI.SmartControl: Loading SETTINGS...
08-30 16:01:51.413  6420  6420 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 16:01:51.413  6147  6147 D UEI.SmartControl: Internal service binding...
08-30 16:01:51.414  6147  6163 I UEI.SmartControl: ------ IControl API: 11
08-30 16:01:51.414  6147  6163 D UEI.SmartControl: File observer start...
08-30 16:01:51.415  6147  6163 E UEI.SmartControl: IR Port is disabled: false
08-30 16:01:51.415  6147  6163 D UEI.SmartControl: Starting file observer...
08-30 16:01:51.415  6147  6163 I UEI.SmartControl: Registering callback...
,08-30 16:01:51.416  6147  6162 I UEI.SmartControl: ------ IControl API: 19,
08-30 16:01:51.418  6147  6162 I UEI.SmartControl: Registering Services Ready callback...
08-30 16:01:51.422  6147  6534 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 16:01:51.440  6147  6533 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 16:01:51.440  6147  6533 D UEI.SmartControl: -----service ready thread exits
08-30 16:01:51.441  6420  6436 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 16:01:51.442  6420  6516 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 16:01:51.442  6420  6516 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 16:01:51.443  6420  6420 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 16:01:51.443  6420  6420 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 16:01:51.444  6147  6176 I UEI.SmartControl: ------ IControl API: 8
08-30 16:01:51.445  6420  6420 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 16:01:51.446  6420  6420 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 16:01:51.446  6420  6420 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 16:01:51.446  6420  6420 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 16:01:51.447  6420  6420 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 16:01:51.447  6420  6420 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 16:01:51.449  6420  6420 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 16:01:51.451  6420  6420 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 16:01:51.452  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 16:01:51.453  6420  6420 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:01:51.454  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-30 16:01:51.455  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 16:01:51.456  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 16:01:51.456  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 16:01:51.457  6420  6420 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472565711457]
08-30 16:01:51.461  6420  6420 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 16:01:51.463  1036  1959 I ActivityManager: Killing 5916:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-30 16:01:51.484  6420  6536 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 16:01:51.503  1036  1959 I ActivityManager: Killing 5874:com.lge.email/u0a23 (adj 15): empty #18
,08-30 16:01:51.533  1036  1711 W libprocessgroup: failed to open /acct/uid_10027/pid_5916/cgroup.procs: No such file or directory
,08-30 16:01:51.540  1036  2074 W libprocessgroup: failed to open /acct/uid_10023/pid_5874/cgroup.procs: No such file or directory
08-30 16:01:51.544  6420  6420 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 16:01:51.545  6420  6420 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 16:01:51.546  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 16:01:51.546  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 16:01:51.546  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 16:01:51.547  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-30 16:01:51.547  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 16:01:51.558  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-30 16:01:52.361  1036  2056 D WifiServiceImplEx: setWifiEnabled: true pid=6240, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 16:01:52.371  1036  2056 D WifiService: setWifiEnabled: true pid=6240, uid=10118
08-30 16:01:52.371  1036  2056 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:01:52.393  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:01:52.393  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:01:52.393  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:01:52.395  1036  1438 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 16:01:52.395  1036  1438 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 16:01:52.398  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 16:01:52.398  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 16:01:52.398  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 16:01:52.398  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 16:01:52.398  1036  1438 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 16:01:52.398  1036  1438 E WifiHW  : unknown target_country: EU , set to default
08-30 16:01:52.398  1036  1438 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 16:01:52.398  1036  1438 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 16:01:52.398  1036  1438 I WifiUtil: gEnableBmps=1
08-30 16:01:52.968  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 16:01:52.981   318   906 D SoftapController: Softap fwReload - Ok
,08-30 16:01:52.986  1036  1438 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (583ms)
08-30 16:01:52.994   318   906 D CommandListener: Setting iface cfg
08-30 16:01:52.994   318   906 D CommandListener: Trying to bring down wlan0
,08-30 16:01:53.003   318  6548 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 16:01:53.007  1036  1097 D Tethering: InitialState.processMessage what=4
,08-30 16:01:53.009   318   906 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:01:53.011  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 16:01:53.028  1036  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 16:01:53.028  1036  1438 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 16:01:53.033  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:01:53.033  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:01:53.033  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:01:53.025  6549  6549 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:53.025  6549  6549 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 16:01:53.045  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:53.046  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 16:01:53.073  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:53.077  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:53.077  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 16:01:53.077  1036  1438 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 16:01:53.077  1036  1438 D WifiMonitor: connecting to supplicant
08-30 16:01:53.092  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:01:53.092  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:01:53.092  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:01:53.092  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 16:01:53.102  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:01:53.104  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-30 16:01:53.104  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 16:01:53.104  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:01:53.104  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:01:53.105  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:01:53.105  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 16:01:53.107  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:01:53.111  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:01:53.111  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:01:53.112  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:01:53.112  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:01:53.113  6549  6549 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 16:01:53.113  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:01:53.114  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:01:53.114  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:01:53.114  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:01:53.114  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:01:53.114  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:01:53.114  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 16:01:53.121  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:53.125  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:01:53.128  6549  6549 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 16:01:53.128  6549  6549 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 16:01:53.130  6459  6568 W FormManager: Network not available. Please check & try again.
08-30 16:01:53.131  6459  6569 V FormManager: Network unavailable.
08-30 16:01:53.132  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:53.135  6459  6569 V FormManager: Network unavailable.
,08-30 16:01:53.198  6549  6549 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 16:01:53.274  6549  6549 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 16:01:53.281  6549  6549 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 16:01:53.281  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 16:01:53.282  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-30 16:01:53.283  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-30 16:01:53.283  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:01:53.284  1036  1438 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:01:53.284  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:53.285  1036  1438 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:53.285  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:53.285  1036  6571 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 16:01:53.286  1036  6571 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 16:01:53.286  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 16:01:53.286  1036  1438 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:53.286  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 16:01:53.286  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:01:53.286  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:01:53.286  1036  1438 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 16:01:53.286  1036  1438 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 16:01:53.288  1036  1438 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-30 16:01:53.288  1036  1438 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,08-30 16:01:53.288  1036  1438 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 16:01:53.290  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:01:53.290  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:01:53.290  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 16:01:53.290  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.290  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.291  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.291  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:01:53.291  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:01:53.291  1036  1438 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 16:01:53.293  1984  1984 D WfdService: Waiting for WifiP2p enabling
,08-30 16:01:53.295  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:53.294  1036  1438 D WifiNative-wlan0: SET update_config 1: returned true
,08-30 16:01:53.296  1036  1438 D WifiConfigStore: Loading config and enabling all networks 
08-30 16:01:53.296  1036  1438 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 16:01:53.297  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:53.297  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:01:53.297  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:53.297  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:01:53.297  1036  1438 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-30 16:01:53.298  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:53.299  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:53.299  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:53.299  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:01:53.299  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 16:01:53.300  1036  1467 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-30 16:01:53.314  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:53.315  6459  6573 W FormManager: Network not available. Please check & try again.
,08-30 16:01:53.317  1036  1438 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 16:01:53.319  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:01:53.322  6459  6574 V FormManager: Network unavailable.
08-30 16:01:53.324  6459  6574 V FormManager: Network unavailable.
,08-30 16:01:53.328  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:53.329  1036  1438 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 16:01:53.329  1036  1438 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 16:01:53.332  1036  1438 D WifiStateMachine: enableVerboseLogging : level 2
08-30 16:01:53.332  1036  1438 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 16:01:53.333  1036  1438 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-30 16:01:53.333  1036  1438 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 16:01:53.333  1036  1438 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 16:01:53.333  1036  1438 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 16:01:53.333  1036  1438 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 16:01:53.334  1036  1438 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 16:01:53.334  1036  1438 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 16:01:53.334  1036  1438 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 16:01:53.334  1036  1438 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 16:01:53.334  1036  1438 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 16:01:53.335  1036  1438 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 16:01:53.335  1036  1438 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 16:01:53.335  1036  1438 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 16:01:53.336  1036  1438 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:01:53.336  1036  1438 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 16:01:53.336  1036  1438 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 16:01:53.336  1036  1438 D WifiNative-HAL: Setting external_sim to 1
08-30 16:01:53.336  1984  1984 D WfdsService: Supplicant Connection state is changed : true
08-30 16:01:53.336  1036  1438 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 16:01:53.337  1984  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 16:01:53.337  1984  2321 D WfdsService: Set the WFDS Monitor: true
08-30 16:01:53.337  1984  2321 D WfdsMonitor: WfdsMonitorThread create
08-30 16:01:53.337  1984  2321 D WfdsMonitor: WFDS Monitor is created and started
08-30 16:01:53.337  1984  2321 D WfdsService: WiFi: Supplicant connection re-established
08-30 16:01:53.337  1036  1438 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 16:01:53.337  1036  1438 I WifiNative-HAL: startHal
08-30 16:01:53.337  1036  1438 D wifi    : setting scan oui 0xaf660040
08-30 16:01:53.338  1036  1438 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:01:53.338  1036  1438 I WifiNative-HAL: startHal
08-30 16:01:53.338  1036  1438 D wifi    : setting scan oui 0xaf660040
08-30 16:01:53.338  1984  6575 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 16:01:53.338  1036  1438 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 16:01:53.339  1036  1438 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 16:01:53.339  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 16:01:53.339  1984  6575 E CtrlSupplicant: Succeed to open control connection
08-30 16:01:53.339  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 16:01:53.339  1984  6575 E CtrlSupplicant: Succeed to open monitor connection
08-30 16:01:53.339  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 16:01:53.339  1984  6575 D WfdsMonitor: Supplicant connection established
08-30 16:01:53.339  1984  2321 D WfdsService: Connected to the supplicant for wfds
08-30 16:01:53.339  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:01:53.340  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:01:53.340  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:01:53.340  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 16:01:53.340  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 16:01:53.340  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 16:01:53.340  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:01:53.341  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:01:53.341  10,36  1438 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:01:53.341  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:01:53.341  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:01:53.341  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:01:53.341  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 16:01:53.341  6549  6549 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 16:01:53.342  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 16:01:53.342  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:01:53.342  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:01:53.342  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:01:53.343  1036  1438 E WifiNative: : [192,997,203 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 16:01:53.343  1036  1438 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 16:01:53.344  1036  1438 D WifiNative-wlan0: RECONNECT: returned true
08-30 16:01:53.344  1036  1438 D WifiNative-wlan0: doString: [STATUS]
08-30 16:01:53.345  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:01:53.345  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-30 16:01:53.345  1036  1438 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:01:53.345  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:01:53.346  1036  1438 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:01:53.346  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.346  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:01:53.347  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:01:53.348   318   906 D CommandListener: Setting iface cfg
08-30 16:01:53.348   318   906 D CommandListener: Trying to bring up p2p0
08-30 16:01:53.348  1036  1392 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 16:01:53.348  1036  1392 D LGWifiP2pService: P2pEnablingState
08-30 16:01:53.348  1036  1392 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:01:53.349  1036  1392 D LGWifiP2pService: P2p socket connection successful
08-30 16:01:53.349  1036  1392 D LGWifiP2pService: P2pEnabledState
08-30 16:01:53.349  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 16:01:53.349  1036  1392 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 16:01:53.349  1036  1036 D RttService: SCAN_AVAILABLE : 3
,08-30 16:01:53.349  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.349  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.350  1036  1557 I WifiNative-HAL: startHal
08-30 16:01:53.350  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf660040
08-30 16:01:53.350  1036  1557 D wifi    : failed to get capabilities : -3
08-30 16:01:53.350  1036  1557 E WifiScanningService: could not get scan capabilities
08-30 16:01:53.350  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 16:01:53.350  1984  1984 D WfdsService: WifiP2pState is changed : true
08-30 16:01:53.351  1984  2321 D WfdsService: Receive the WFDS_ENABLE Method
08-30 16:01:53.351  1984  2321 D WfdsService: Set the WFDS Monitor: true
08-30 16:01:53.351  1984  2321 D WfdsService: Connected to the supplicant for wfds
08-30 16:01:53.351  1984  2321 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 16:01:53.351  6549  6549 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 16:01:53.351  1984  2321 D WfdsService: selectPreferredScanChannel [36]
08-30 16:01:53.351  1984  2321 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 16:01:53.351  1036  1392 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 16:01:53.352  1036  1392 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 16:01:53.352  1036  1438 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 16:01:53.352  1036  1438 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 16:01:53.353  1036  1438 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 16:01:53.353  1984  1984 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 16:01:53.353  1036  1438 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 16:01:53.354  1984  1984 D WfdsService: isConnected: false
08-30 16:01:53.354  1036  1438 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 16:01:53.354  1036  1392 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 16:01:53.354  1036  1438 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 16:01:53.354  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:53.354  1036  1392 D WifiNative-p2p0: SET device_name G3: returned true
08-30 16:01:53.355  1036  1392 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 16:01:53.355  1036  1392 D LGWifiP2pService: before postfix = G3
08-30 16:01:53.355  1036  1392 D WifiServerServiceExt: postfix byte check : 2
08-30 16:01:53.355  1036  1392 D LGWifiP2pService: after postfix = G3
08-30 16:01:53.355  1036  1392 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 16:01:53.355  1036  1438 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 16:01:53.355  1036  1438 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 16:01:53.355  6549  6549 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 16:01:53.355  1036  1392 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 16:01:53.355  1036  1392 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 16:01:53.356  1036  1392 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 16:01:53.356  1036  1392 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 16:01:53.356  1036  1392 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 16:01:53.356  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SET co,nc_pref p2p
08-30 16:01:53.356  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:53.356  1036  1392 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 16:01:53.356  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress
08-30 16:01:53.357  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress returning 
,08-30 16:01:53.359  1984  1984 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 16:01:53.359  1984  1984 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 16:01:53.359  1984  1984 D WfdsService: Update P2p Interface State: 3
08-30 16:01:53.359  1036  1392 D LGWifiP2pService: DeviceAddress: 
08-30 16:01:53.359  1036  1392 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 16:01:53.360  1036  1438 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 16:01:53.360  1036  1438 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 16:01:53.361  1036  1438 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 16:01:53.361  1036  1438 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 16:01:53.361  6549  6549 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 16:01:53.361  1036  1392 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 16:01:53.361  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 16:01:53.362  1036  1392 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 16:01:53.362  1036  1392 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 16:01:53.362  1036  1392 D WifiNative-p2p0:    returned OK
08-30 16:01:53.362  1036  1392 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 16:01:53.363  6118  6118 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 16:01:53.363  1036  1392 D WifiNative-p2p0: SAVE_CONFIG: returned false
08-30 16:01:53.363  1036  1392 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 16:01:53.363  1036  1392 D LGWifiP2pService: InactiveState
08-30 16:01:53.363  6118  6118 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-30 16:01:53.363  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.363  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.363  1036  1392 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 16:01:53.365  4272  6576 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:01:53.368  4272  6577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:01:53.368  4272  6577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:01:53.372  6118  6118 V [BNRBootReceiver]: Boot Receiver Return
,08-30 16:01:53.375  1036  1438 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 16:01:53.375  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 16:01:53.375  1036  1438 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 16:01:53.375  6549  6549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.376  1036  6571 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:01:53.376  1036  6571 E WifiMonitor: WifiMonitor:p2p0 cnt=16 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.376  1984  6575 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:01:53.376  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.376  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.376  6549  6549 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:01:53.376  6549  6549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.376  1036  1438 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 16:01:53.376  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 16:01:53.377  1036  6571 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.377  1036  1392 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 16:01:53.377  1036  6571 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.377  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: InactiveState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.377  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.377  6549  6549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: DefaultState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.377  1036  6571 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.377  1036  6571 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: InactiveState{ when=-14ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.377  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.377  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: DefaultState{ when=-14ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: InactiveState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.377  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.378  1036  1392 D LGWifiP2pService: DefaultState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.378  1984  6575 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.378  1036  1392 D LGWi,fiP2pService: InactiveState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.378  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.378  1984  6575 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.378  1036  1392 D LGWifiP2pService: DefaultState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.378  1036  1036 E WifiServerServiceExt: No p2p device connected
08-30 16:01:53.378  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 16:01:53.378  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.379  1984  2321 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 16:01:53.379  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:01:53.379  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.379  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.379  6549  6549 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:01:53.379  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:01:53.379  6549  6549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.379  1036  1438 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 16:01:53.380  1984  6575 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.380  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.380  6549  6549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.380  1036  1438 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:01:53.380  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:53.380  1036  1438 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:01:53.380  1984  6575 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.381  1036  1438 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:01:53.381  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-30 16:01:53.381  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 16:01:53.381  1036  6571 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.381  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:01:53.381  1036  6571 E WifiMonitor: WifiMonitor:p2p0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.381  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.381  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.381  1036  6571 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:01:53.381  1036  6571 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.381  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-30 16:01:53.381  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:01:53.381  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 16:01:53.381  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:01:53.381  1036  6571 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:01:53.381  1036  6571 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:01:53.382  1036  1438 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 16:01:53.382  1036  1438 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 16:01:53.382  1036  1438 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-30 16:01:53.382  1036  1438 D WifiNative-wlan0: doBoolean: SCAN
08-30 16:01:53.382  1036  1438 D WifiNative-wlan0: SCAN: returned false
08-30 16:01:53.383  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=193037  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:01:53.384  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=193038  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-30 16:01:53.385  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:53.385  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:53.386  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:53.386  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.387  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.387  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 16:01:53.388  1036  1438 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:01:53.388  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:53.389  1036  1438 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:01:53.389  1036  1438 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:01:53.390  1036  1438 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:01:53.390  1036  1438 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:01:53.393  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:53.393  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 16:01:53.396  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:53.402  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:53.408  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:53.409  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:53.410  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 16:01:53.914  6549  6549 E wpa_supplicant: USIM:  scard_init function
08-30 16:01:53.915  6549  6549 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 16:01:53.924  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 16:01:53.924  1036  6571 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 16:01:53.925  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 16:01:53.925  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: WPS-AP-AVAILABLE 
08-30 16:01:53.925  1036  6571 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 16:01:53.925  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:01:53.925  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 16:01:53.935  1036  1438 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 16:01:53.935  1036  1438 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 16:01:53.936  1036  1438 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 16:01:53.936  1036  1438 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 16:01:53.936  1036  1438 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 16:01:53.953  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=193608  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 16:01:53.962  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.962  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.963  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 16:01:53.968  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.968  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:53.968  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 16:01:53.971  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=193626  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 16:01:53.973  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:53.975  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 16:01:53.977  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 16:01:53.979  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:53.979  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 16:01:53.987  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:53.991  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:53.991  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:53.992  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:01:54.004  6356  6356 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 16:01:54.012  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:01:54.024  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:54.034  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:54.042  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:54.042  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:01:54.048  6549  6549 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 16:01:54.053  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 16:01:54.054  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 16:01:54.054  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 16:01:54.054  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 16:01:54.054  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:01:54.054  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:01:54.057  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=193711  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 16:01:54.058  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=193712  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-30 16:01:54.063  6549  6549 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:01:54.063  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:01:54.066  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:01:54.066  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:01:54.067  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 16:01:54.067  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:01:54.067  1036  6571 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:01:54.067  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 16:01:54.067  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:01:54.067  1036  6571 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:01:54.067  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:01:54.067  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:01:54.069  1036  1438 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193723
08-30 16:01:54.069  1036  1438 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193723
08-30 16:01:54.069  1036  1438 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193724
08-30 16:01:54.071  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 16:01:54.080  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193734
08-30 16:01:54.080  1036  1438 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193735
08-30 16:01:54.081  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=193735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 16:01:54.096  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:01:54.099  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:54.099  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:54.100  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:01:54.104  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.104  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.104  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 16:01:54.107  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=193762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 16:01:54.111  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.111  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.111  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 16:01:54.117  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:01:54.121  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:54.121  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 16:01:54.122  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=193776  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:01:54.128  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:54.128  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:54.129  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=193783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:01:54.131  1036  1438 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193785
,08-30 16:01:54.131  1036  1438 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193786
08-30 16:01:54.134  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:54.134  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:54.134  1036  1438 D WifiNative-wlan0: doString: [STATUS]
08-30 16:01:54.135  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:01:54.135  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:01:54.135  1036  1438 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:01:54.138  1036  1438 I WifiServiceExtension: setVHTCapabilityType  : false
,08-30 16:01:54.144  1036  1438 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 16:01:54.144  1036  1438 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 16:01:54.148  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.148  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.148  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 16:01:54.153  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:01:54.158  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:54.158  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.158  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:54.158  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:54.158  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 16:01:54.163  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:54.165  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:54.165  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:54.166  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:54.166  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:54.166  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:01:54.172  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:01:54.172  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:01:54.172  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:01:54.172  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:01:54.172  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:54.173  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:01:54.174  1036  1438 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 16:01:54.174  1036  1494 D ConnectivityService: Got NetworkAgent Messenger
08-30 16:01:54.175  1036  1494 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 16:01:54.175  1036  1494 D ConnectivityService: NetworkAgent connected
08-30 16:01:54.175  1036  1438 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:01:54.175  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:01:54.175  1036  1438 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:01:54.176  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 16:01:54.176  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:01:54.176  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:01:54.176  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:01:54.176  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 16:01:54.176  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:01:54.177  1036  1438 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:01:54.177  1036  1438 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:01:54.179  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:54.181  1036  1438 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:01:54.181  1036  1438 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:01:54.181  1036  1438 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:01:54.181  1036  1438 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:01:54.181  1036  1438 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 16:01:54.185  1036  1438 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:01:54.188   318   906 D CommandListener: Setting iface cfg
08-30 16:01:54.192  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:54.192  1036  1438 E WifiStateMachine: Start Dhcp Watchdog 1
08-30 16:01:54.192  1036  6607 D DhcpStateMachine: StoppedState
08-30 16:01:54.192  1036  6607 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:54.193  1036  6607 D DhcpStateMachine: WaitBeforeStartState
08-30 16:01:54.193  1036  1438 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=193847  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:01:54.193  1036  1438 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=193848  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:01:54.194  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=193848  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:01:54.194  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-30 16:01:54.194  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:54.195  1036  1438 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:54.195  1036  1438 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:54.196  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:54.196  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:54.196  1036  1438 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:54.198  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:54.198  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 16:01:54.198  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:54.198  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 16:01:54.198  1036  1438 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=193853  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:01:54.199  1036  1438 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=193853  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:01:54.199  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=193854  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:01:54.201  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-608068327] from screen [on:0 period:-608068327]
08-30 16:01:54.201  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:54.201  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:54.202  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-608068327]
08-30 16:01:54.202  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:01:54.202  1036  1438 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 16:01:54.204  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:01:54.209  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:54.209  1036  1494 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-30 16:01:54.210  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.211  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.211  1036  1438 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.212  1036  1438 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 16:01:54.212  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:54.212  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.212  1036  1438 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.213  1036  1494 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-30 16:01:54.214  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-30 16:01:54.214  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-30 16:01:54.214  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 16:01:54.214  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 16:01:54.215  1036  1438 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 16:01:54.215  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 16:01:54.215  1036  1438 D WifiNative-wlan0: SET ps 0: returned true
08-30 16:01:54.215  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 16:01:54.215  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 16:01:54.216  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 16:01:54.216  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2ac6c8e1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:01:54.216  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:54.216  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2ac6c8e1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:54.216  1036  6607 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:54.216  1036  6607 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 16:01:54.217  1036  1438 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 16:01:54.217  1036  1438 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:01:54.218  1036  1438 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:01:54.218  1036  1438 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
,08-30 16:01:54.221  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:54.221  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 16:01:54.221  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:54.221  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 16:01:54.221  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:54.222  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:54.222  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:01:54.224  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:54.229  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:54.233  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:54.239  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:54.239  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:54.240  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:01:54.246  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:01:54.254  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:54.260  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:54.266  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:54.267  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:54.268  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:01:54.339  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:54.340  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:54.340  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:01:54.407  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-30 16:01:54.407  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:01:54.408  1036  1438 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:01:54.409  1036  1438 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:01:54.409  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:01:54.410  1036  1438 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 16:01:54.419  1036  6607 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 16:01:54.420  1036  6607 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 16:01:54.420  1036  6607 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 16:01:54.425  6608  6608 W dhcpcd  : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:54.425  6608  6608 W dhcpcd  : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 16:01:54.463  6608  6608 I dhcpcd  : version 5.5.6 starting
,08-30 16:01:54.469  6608  6608 E dhcpcd  : get_duid: m
08-30 16:01:54.469  6608  6608 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
,08-30 16:01:54.470  6608  6608 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 16:01:54.572  6608  6608 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-30 16:01:54.573  6608  6608 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-30 16:01:54.573  6608  6608 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:01:54.576  6608  6608 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 16:01:54.577  6608  6608 D dhcpcd  : wlan0: sending REQUEST (xid 0xaac5b3f6), next in 3.72 seconds
08-30 16:01:54.590  6608  6608 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 16:01:54.595  6608  6608 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 16:01:54.595  6608  6608 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 16:01:54.598  6608  6608 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 16:01:54.598  6608  6608 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 16:01:54.598  6608  6608 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:01:54.599  6608  6608 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 16:01:54.599  6608  6608 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 16:01:54.599  6608  6608 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 16:01:54.599  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.600  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.601  1036  1438 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.601  1036  1438 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.602  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.603  1036  1438 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:54.604  1036  1494 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-30 16:01:55.024  1036  6607 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 16:01:55.038  1036  6607 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 16:01:55.039  1036  6607 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:01:55.040  1036  6607 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 16:01:55.040  1036  6607 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 16:01:55.040  1036  6607 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:01:55.040  1036  6607 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-30 16:01:55.044  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 16:01:55.045  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-30 16:01:55.048  1036  1392 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.048  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.049  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:01:55.049  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:01:55.050  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:01:55.050  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 16:01:55.050  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 16:01:55.050  1036  1438 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 16:01:55.051  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:01:55.051  1036  6607 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 16:01:55.052  1036  6607 D DhcpStateMachine: RunningState
08-30 16:01:55.068  1036  1438 D WifiNative-wlan0: SET ps 1: returned true
,08-30 16:01:55.072  1036  1494 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-30 16:01:55.074  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:01:55.074  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:01:55.074  1036  1438 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 16:01:55.075  1036  1494 D ConnectivityService: ignoring duplicate network state non-change
08-30 16:01:55.088  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:55.088  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 16:01:55.100  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.100  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.100  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 16:01:55.107  1036  1494 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 16:01:55.111  1036  1494 D ConnectivityService: Adding iface wlan0 to network 100
08-30 16:01:55.116  1036  1438 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 16:01:55.145  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.146  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.146  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-30 16:01:55.153  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.156  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:55.156  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 16:01:55.167  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 16:01:55.204  1984  1984 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-30 16:01:55.206  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.207  1036  1494 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 16:01:55.208  1036  1494 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-30 16:01:55.209  1036  1494 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-30 16:01:55.210  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.210  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.210  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 16:01:55.211  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 16:01:55.215  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:55.216  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.216  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.216  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 16:01:55.218  1036  1494 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-30 16:01:55.218  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-30 16:01:55.219  1036  1494 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 16:01:55.220  1036  1494 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-30 16:01:55.220  1036  1494 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-30 16:01:55.224  1036  1494 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 16:01:55.224  1036  1494 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.224  1036  1494 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.225  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.225  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 16:01:55.225  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.226  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-30 16:01:55.231   318  6658 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 16:01:55.232  1036  1494 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.232  1036  1494 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:01:55.232  1036  1494 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:01:55.232  1036  1494 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 16:01:55.232  1036  1494 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.233  1036  1494 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 16:01:55.235  1036  1494 D ConnectivityService: currentScore = 0, newScore = 20
08-30 16:01:55.235  1036  1494 D ConnectivityService:    accepting network in place of null
08-30 16:01:55.235  1036  1494 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.236  1036  1438 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.236  1036  1438 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:01:55.236  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.236  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:01:55.236  1036  1494 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-30 16:01:55.241  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.243  1036  1494 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 16:01:55.243  1036  1494 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 16:01:55.244  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:01:55.244  1036  1494 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:55.244  1036  1494 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 16:01:55.245  1036  1494 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp,{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 16:01:55.245  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 16:01:55.246  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:01:55.246  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:01:55.246  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:01:55.246  1036  1036 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
,08-30 16:01:55.248  1036  1494 D ConnectivityService: validation of new default Network = false
08-30 16:01:55.248  1036  1494 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 16:01:55.248  1036  1494 D DSQN    : enableDataServiceNotify 
08-30 16:01:55.248  1036  1494 D DSQN    : start dsqn bin
08-30 16:01:55.250   318  6663 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 16:01:55.250   318  6663 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-30 16:01:55.254  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:55.255  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 16:01:55.255  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.255   318  6666 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 16:01:55.256   318  6666 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-30 16:01:55.256  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:55.245  6667  6667 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:55.245  6667  6667 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:55.273  1036  1494 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.273  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.273  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:01:55.274  1036  1494 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 16:01:55.275  6667  6667 E DSQN    : DSQN ssw
08-30 16:01:55.277  1602  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 16:01:55.283   318  6663 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
,08-30 16:01:55.291  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:01:55.292  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.293  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.296   318  6658 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 16:01:55.297  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:55.302  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:55.303   318  6666 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
,08-30 16:01:55.313  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:55.313  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:55.319  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:01:55.324  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:55.334  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:55.339  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:55.343  1036  1391 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 16:01:55.344   318  6658 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 16:01:55.348  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:55.348  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:55.349  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:01:55.353  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:55.360  6374  6374 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 16:01:55.365  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:55.369  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:55.371  1036  6664 D LocSvc_java: NTP server : europe.pool.ntp.org
08-30 16:01:55.372   318   905 D LGDataListener: argv[0]=dsqncommand
08-30 16:01:55.372   318   905 D LGDataListener: argv[1]=wlan0
08-30 16:01:55.372   318   905 D LGDataListener: argv[2]=1
08-30 16:01:55.372   318   905 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 16:01:55.372  1036  6664 D LocSvc_java: NTP server returned: 1472565714649 (Tue Aug 30 16:01:54 GMT+02:00 2016) reference: 195025 certainty: 33 system time offset: -722
08-30 16:01:55.372  1036  6664 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-30 16:01:55.372  1036  1095 D DSQN    : DSQM DsqnNotification wlan0  1
,08-30 16:01:55.372  1036  1095 D DSQN    : start to monitor internet connection
08-30 16:01:55.377  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:55.391  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:01:55.392  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:55.393  6420  6420 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 16:01:55.395  6420  6420 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:01:55.396  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:01:54 GMT], X-Android-Received-Millis=[1472565715395], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472565715370]}
08-30 16:01:55.396  6420  6420 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 16:01:55.396  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 16:01:55.397  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 16:01:55.398  1036  1494 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.398  1036  1494 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.399  1036  1494 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:01:55.399  1036  2028 D WifiServiceImplEx: setWifiEnabled: false pid=6240, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:01:55.399  1036  1494 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:01:55.399  1036  1494 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 16:01:55.399  1036  2028 D WifiService: setWifiEnabled: false pid=6240, uid=10118
08-30 16:01:55.399  1036  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:01:55.400  1036  1494 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-30 16:01:55.400  1036  1494 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.400  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.400  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:01:55.401  1036  1494 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:01:55.403  1602  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 16:01:55.403  1036  1494 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.404  1036  1438 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.404  1036  1438 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:01:55.404  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.405  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:01:55.405  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 16:01:55.410  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net,.wifi.STATE_CHANGE'.
,08-30 16:01:55.416  1036  1438 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:55.416  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:55.416  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:01:55.417  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:01:55.417  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:01:55.418  1036  1438 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:55.419  1036  1438 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:55.419  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 16:01:55.420  1036  1438 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 16:01:55.420  1036  1438 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:01:55.420  1036  1438 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:01:55.421  1036  1438 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:01:55.421  1036  1438 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:01:55.429  1036  1438 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:01:55.429  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:01:55.429  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:01:55.430  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.430  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.430  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:01:55.430  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:01:55.431  1036  1438 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:01:55.431   318   906 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:01:55.431  6374  6374 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 16:01:55.433  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:01:55.434  1036  6607 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.445  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:55.460  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:01:55.465  1036  1494 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 16:01:55.466  1036  1494 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 16:01:55.467  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.467  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.467  1036  1392 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@135bf09e
08-30 16:01:55.468  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 16:01:55.470  1984  1984 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 16:01:55.472  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.472  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.473  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:01:55.474  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 16:01:55.474  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.474  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.474  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:01:55.474  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 16:01:55.474  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-30 16:01:55.475  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.475  1036  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.475  1036  1438 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:55.476  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:55.476  1036  1438 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:55.477  1036  1438 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:55.477  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:55.478  1036  1438 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:01:55.478  1036  1438 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:01:55.480  1036  1392 D LGWifiP2pService: P2pDisablingState
08-30 16:01:55.480  1036  1392 D LGWifiP2pService: P2pDisablingState{ when=-13ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.480  1036  1392 D LGWifiP2pService: p2p socket connection lost
08-30 16:01:55.480  1036  1392 D LGWifiP2pService: P2pDisabledState
08-30 16:01:55.480  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:01:55.481  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.482  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.483  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 16:01:55.483  1984  1984 D WfdsService: WifiP2pState is changed : false
08-30 16:01:55.484  1984  2321 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 16:01:55.484  1984  2321 D WfdsService,: Set the WFDS Monitor: false
08-30 16:01:55.484  1984  2321 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:01:55.484  1984  2321 D WfdsService: STATE : WfdsDisabledState - enter
08-30 16:01:55.485  1984  6575 D CtrlSupplicant: Received on exit socket, terminate
08-30 16:01:55.485  1984  6575 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 16:01:55.485  1984  6575 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 16:01:55.485  1984  6575 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 16:01:55.485  1984  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 16:01:55.485  1984  2321 W WfdsService: DefaultState - msg [9445378] is not handled
,08-30 16:01:55.487  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:55.487  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:55.488  1036  1438 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 16:01:55.488  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:55.488  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.488  1036  1392 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.489  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:55.489  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:01:55.489  6549  6549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:01:55.489  6420  6420 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 16:01:55.489  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:01:55.489  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:01:55.490  6420  6420 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:01:55.490  6420  6420 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 16:01:55.490  1036  1438 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:01:55.491  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.494  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:55.494  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:55.494  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.498  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:01:55.502  6374  6374 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:01:55.502  6374  6374 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:01:55.502  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:55.504  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:01:55.513  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:55.519  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:55.519  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:55.521  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:01:55.523  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:01:55.525   318   906 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:01:55.525  1036  1494 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 16:01:55.526  1036  1494 D DSQN    : disableDataServiceNotify
08-30 16:01:55.526  1036  1494 D DSQN    : stop dsqn bin
08-30 16:01:55.527  6374  6374 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:01:55.527  6374  6374 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:01:55.527  1036  1438 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 16:01:55.527  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:55.528  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 16:01:55.528  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:01:55.529  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 16:01:55.529  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.530  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.530  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.530  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:01:55.530  1036  1438 D WifiNative-p2p0: TERMINATE: returned true
08-30 16:01:55.530  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:01:55.530  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:01:55.530  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:01:55.532  1036  1494 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 16:01:55.532  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.533  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:01:55.533  1036  1494 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:01:55.533  1036  1494 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 16:01:55.533  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.533  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.534  1036  1494 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
,08-30 16:01:55.534  1036  6605 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 16:01:55.534  1036  1494 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 16:01:55.534  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:01:55.534  1602  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 16:01:55.535  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-30 16:01:55.535  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 16:01:55.535  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:01:55.535  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 16:01:55.536  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:55.536  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:01:55.536  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:55.536  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:55.540  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:55.541  1036  1494 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:55.542  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:01:55.542  1036  1494 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:55.542  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:55.542  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:01:55.542  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:55.542  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:55.543  1036  1494 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.543  1036  1494 D ConnectivityService: sending new Min ,Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.544  1036  1494 D NetworkManagementService: Removing idletimer
08-30 16:01:55.544  1877  1877 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.544  1036  1438 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:01:55.544  1036  1438 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:01:55.544  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:01:55.544  1036  1494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.544  1036  1391 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 16:01:55.544  1036  1494 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 16:01:55.545  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 16:01:55.545  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:01:55.545  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:01:55.545  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 16:01:55.547  1036  1391 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-30 16:01:55.547  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 16:01:55.548  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:01:55.548  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:01:55.548  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:01:55.551  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.552  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:55.561  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:55.561  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:01:55.564  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:01:55.567  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:01:55.570  6374  6374 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 16:01:55.570  6374  6374 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:01:55.570  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:55.574  6549  6549 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 16:01:55.574  6549  6549 I wpa_supplicant: monitor socket send errors count : 1
08-30 16:01:55.574  6549  6549 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1984-4\x00 that cannot receive messages
,08-30 16:01:55.574  1036  6571 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 16:01:55.575  1036  6571 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 16:01:55.576  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:01:55.581  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:01:55.590  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:01:55.591  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:01:55.594  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:01:55.599  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:01:55.600  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 16:01:55.600  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:01:55.600  1036  6571 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:01:55.600  6549  6549 W wpa_supplicant: USIM:  scard_deinit function
08-30 16:01:55.601  1036  6571 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 16:01:55.601  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:01:55.601  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:01:55.601  1036  1438 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=195256
08-30 16:01:55.602  1036  1438 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=195256
,08-30 16:01:55.602  1036  1097 D Tethering: InitialState.processMessage what=4
08-30 16:01:55.602  1036  1438 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=195257  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:01:55.604  1036  1438 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=195258  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 16:01:55.606  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:01:55.607  1036  1438 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:55.608  1036  1438 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:01:55.609  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:01:55.609  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:01:55.611  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.612  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:01:55.619  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:01:55.625  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:55.631  6459  6682 W FormManager: Network not available. Please check & try again.
,08-30 16:01:55.640  6459  6683 V FormManager: Network unavailable.
08-30 16:01:55.642  1036  6607 D DhcpStateMachine: StoppedState
08-30 16:01:55.642  1036  6607 D DhcpStateMachine: StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:01:55.643  1036  1438 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-30 16:01:55.644  1036  1438 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 16:01:55.644  6459  6683 V FormManager: Network unavailable.
,08-30 16:01:55.650  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:01:55.650  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:01:55.650  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:01:55.650  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:01:55.651  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:01:55.652  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:01:55.653  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:01:55.653  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:01:55.653  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:01:55.653  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:01:55.653  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 16:01:55.664  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 16:01:55.664  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:01:55.664  1036  6571 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 16:01:55.664  1036  6571 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 16:01:55.664  1036  6571 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 16:01:55.665  1036  1438 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 36 0
08-30 16:01:55.665  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.666  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.770  1984  1984 D WfdsService: Supplicant Connection state is changed : false
08-30 16:01:55.770  1984  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 16:01:55.770  1984  2321 D WfdsService: Set the WFDS Monitor: false
08-30 16:01:55.771  1984  2321 D WfdsMonitor: WFDS Monitor is stopped
08-30 16:01:55.773  1036  1438 D WifiOffDelayIfNotUsed: stopMonitoring
,08-30 16:01:55.773  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:01:55.773  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:01:55.773  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:01:55.776  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:01:55.777  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:01:55.777  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 16:01:55.782  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:01:55.783  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:55.783  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:55.786  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 16:01:55.787  1036  1467 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 16:01:55.788  1036  1467 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 16:01:55.790  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:55.790  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:55.792  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:55.792  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:01:55.796  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:55.802  4272  6684 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:01:55.810  6374  6374 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 16:01:55.810  6374  6374 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 16:01:55.810  6374  6374 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:01:55.814  4272  6685 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:01:55.815  4272  6685 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 16:01:55.820  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:01:55.825  6459  6687 W FormManager: Network not available. Please check & try again.
,08-30 16:01:55.830  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:01:55.831  6459  6688 V FormManager: Network unavailable.
08-30 16:01:55.838  6459  6688 V FormManager: Network unavailable.
,08-30 16:01:56.402  6147  6535 D UEI.SmartControl: Internal timer expired: 2
08-30 16:01:56.402  6147  6535 D UEI.SmartControl: unbind internal service
,08-30 16:01:56.727  6147  6529 D serial_port: close(fd = 24)
,08-30 16:01:56.738  6147  6529 I UEI.SmartControl: Serial port is closed.
08-30 16:01:57.214  1036  1438 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-608065316] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 16:01:57.216  1036  1438 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-608065312] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 16:01:58.248  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:01:58.274  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:01:58.281  1036  1097 D Tethering: MasterInitialState.processMessage what=3
08-30 16:01:58.284  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:58.287  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:58.298  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 16:01:58.300  3703  6354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 16:01:58.319  5397  5397 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 16:01:58.337  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 16:01:58.368  2286  2286 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:01:58.453  1036  1576 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6710 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 16:01:58.459  1036  2074 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:58.459  1036  2074 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-30 16:01:58.461  1036  1092 E GpsLocationProvider: No APN found to select.
08-30 16:01:58.470   352   352 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 477us total 24.016ms
,08-30 16:01:58.473  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:01:58.473  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:01:58.474  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:01:58.483  1036  1097 D BluetoothManagerService: Message: 1
08-30 16:01:58.483  1036  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 16:01:58.496   352   352 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 24.538ms
,08-30 16:01:58.511  1036  1097 D BluetoothManagerService: Message: 20
08-30 16:01:58.511  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f6ccedb:true
,08-30 16:01:58.511  6498  6498 D BluetoothAdapterState: make
08-30 16:01:58.517   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 19.312ms
08-30 16:01:58.517  6498  6498 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 16:01:58.518  6498  6498 I bluedroid-qcom: init
08-30 16:01:58.518  6498  6730 I BluetoothAdapterState: Entering OffState
08-30 16:01:58.519  6498  6498 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 16:01:58.519  6498  6498 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 16:01:58.519  6498  6498 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:01:58.519  6498  6498 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:01:58.519  6498  6498 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 16:01:58.520  6498  6498 I bluedroid-qcom: get_profile_interface socket
08-30 16:01:58.520  6498  6733 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 16:01:58.521  6498  6498 I bluedroid-qcom: get_profile_interface map_client
08-30 16:01:58.505  6734  6734 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:58.505  6734  6734 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:58.523  6498  6733 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 16:01:58.526  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:01:58.526  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 16:01:58.529  6498  6733 D BluetoothAdapterProperties: Name is: G3
08-30 16:01:58.530  6734  6734 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 16:01:58.530  6734  6734 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 16:01:58.530  6734  6734 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 16:01:58.530  6734  6734 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 16:01:58.533  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 16:01:58.533  1036  1097 D BluetoothManagerService: Message: 40
08-30 16:01:58.533  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 16:01:58.534  6498  6514 I bluedroid-qcom: config_hci_snoop_log
08-30 16:01:58.534  6734  6734 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 16:01:58.534  6734  6734 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 16:01:58.536  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 16:01:58.536  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 16:01:58.541  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:58.542  6498  6730 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 16:01:58.542  6498  6730 D BluetoothAdapterProperties: Setting state to 11
08-30 16:01:58.542  6498  6730 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 16:01:58.542  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:01:58.543  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 16:01:58.543  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 16:01:58.543  6498  6730 I LGBluetoothServiceJni: classInitNative: succeeds
,08-30 16:01:58.545  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:58.547  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:58.549  1036  1097 D Tethering: MasterInitialState.processMessage what=3
08-30 16:01:58.552  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:58.554  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:58.556  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:01:58.559  1036  1097 D Tethering: MasterInitialState.processMessage what=3
08-30 16:01:58.561  6356  6356 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 16:01:58.562  5397  5397 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 16:01:58.562  6498  6730 D BluetoothBondStateMachine: make
08-30 16:01:58.563  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:58.569  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:58.573  6498  6498 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:01:58.573  6498  6498 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:58.573  6498  6498 V BluetoothPbapReceiver: ***********state = 11
,08-30 16:01:58.577  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:58.579  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:58.583  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:58.584  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:01:58.584  6498  6730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.585  6498  6730 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 16:01:58.585  6498  6730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.585  6498  6730 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 16:01:58.585  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:58.586  6498  6730 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 16:01:58.588  5397  5397 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 16:01:58.590  6498  6742 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 16:01:58.593  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:58.593  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:01:58.597  6498  6730 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:01:58.598  6356  6356 D BluetoothPermissionRequest: onReceive
08-30 16:01:58.603  6498  6730 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:01:58.603  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 16:01:58.606  6498  6498 D HeadsetService: Received start request. Starting profile...
08-30 16:01:58.607  6498  6498 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:01:58.607  6498  6498 D LGBluetoothHfpAdapter: Version 1.6
08-30 16:01:58.610  6710  6710 I AppUp4:AppBoxCP: onCreate
08-30 16:01:58.611  6498  6498 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:01:58.611  6710  6710 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 16:01:58.612  6498  6498 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:01:58.612  6498  6498 D HeadsetStateMachine: make
08-30 16:01:58.613  6498  6730 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:01:58.619  6498  6730 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:01:58.623  6710  6710 I AppUp4:DB:  setFingerPrint start
08-30 16:01:58.623  6710  6710 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 16:01:58.624  6498  6730 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:01:58.629  6498  6730 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:01:58.633  6710  6710 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 16:01:58.633  6710  6710 I AppUp4:DB:  SDK version = 21
08-30 16:01:58.633  6710  6710 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 16:01:58.634  6710  6710 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 16:01:58.635  6498  6730 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:01:58.636  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 16:01:58.636  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:58.639  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:01:58.640  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 16:01:58.644  6710  6710 I AppUp4:CustModeStarterReceiver: onReceive
08-30 16:01:58.650  6498  6730 V LGMDMManager: Create singleton instance
,08-30 16:01:58.653  6498  6498 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:01:58.653  6498  6730 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 16:01:58.653  6498  6498 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:01:58.658  6498  6498 D HeadsetStateMachine: max_hf_connections = 1
08-30 16:01:58.658  6498  6498 I bluedroid-qcom: get_profile_interface handsfree
08-30 16:01:58.660  6498  6498 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 16:01:58.661   322   322 V AudioPolicyService: registerClient() client 0xb557c040, uid 1002
08-30 16:01:58.661   322  1399 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:01:58.661   322  1399 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:01:58.661   322  1399 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:01:58.661  6498  6498 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 16:01:58.662   322  1398 V AudioFlinger: registerClient() client 0xb1433178, pid 6498
,08-30 16:01:58.662   322  1394 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:01:58.662   322  1394 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:01:58.662  1036  2129 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:01:58.662  1036  2129 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:01:58.662  1602  3126 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:01:58.662  1602  3126 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:01:58.663  1877  1892 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:01:58.663  1877  1892 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:01:58.663   322  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:01:58.663   322  1393 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:01:58.663  2203  2221 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:01:58.663  2203  2221 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:01:58.663  6498  6498 V ToneGenerator: Create Track: 0xb4929480
08-30 16:01:58.663  3343  3359 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:01:58.663  3343  3359 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:01:58.663  6498  6498 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 16:01:58.663  6498  6498 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 16:01:58.663   322  1399 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:01:58.663  1877  4372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:01:58.663  1877  4372 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:01:58.663   322  1399 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:01:58.663   322  1399 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:01:58.664   322  1399 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:01:58.664  1602  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:01:58.664  1602  1619 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:01:58.664  6498  6498 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 16:01:58.664  2203  4454 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:01:58.664  2203  4454 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:01:58.664  3343  3358 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:01:58.664  3343  3358 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:01:58.664  6498  6515 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:01:58.664  6498  6515 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 16:01:58.664  6498  6515 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:01:58.664  1036  2056 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:01:58.664  1036  2056 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:01:58.664  6498  6515 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 16:01:58.665   322   322 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 16:01:58.665   322  3923 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:01:58.665   322  3923 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 16:01:58.665   322  3923 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:01:58.665   322  3923 V AudioPolicyManagerEx: getOutput(,) returns output 2
08-30 16:01:58.665  6498  6498 V AudioSystem: getLatency() output 2, latency 50
08-30 16:01:58.665  6498  6498 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 16:01:58.665  6498  6498 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 16:01:58.665   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:01:58.665   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:01:58.665   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:01:58.665   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:01:58.665   322  1399 V AudioFlinger: createTrack() lSessionId: 22
08-30 16:01:58.666  6498  6498 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 16:01:58.667   322  1398 V AudioFlinger: acquiring 22 from 6498, for 6498
08-30 16:01:58.667   322  1398 V AudioFlinger:  added new entry for 22
08-30 16:01:58.667  6498  6498 V ToneGenerator: ToneGenerator INIT OK, time: 198334
08-30 16:01:58.667  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.667  6498  6744 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 16:01:58.667  6498  6744 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:01:58.668  6498  6744 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:01:58.668  6498  6744 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 16:01:58.668   322   322 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6498
08-30 16:01:58.668   322   322 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 16:01:58.668   322   322 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 16:01:58.668   322   322 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 16:01:58.668   322   322 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 16:01:58.668  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.668   322   322 V voice   : voice_set_parameters: exit with code(0)
08-30 16:01:58.668   322   322 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 16:01:58.668   322   322 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 16:01:58.669   322   322 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 16:01:58.669   322   322 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 16:01:58.669   322   322 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 16:01:58.669   322   322 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 16:01:58.669  6498  6744 V ToneGenerator: ToneGenerator destructor
,08-30 16:01:58.669  6498  6744 V ToneGenerator: stopTone
08-30 16:01:58.669  6498  6744 V ToneGenerator: Delete Track: 0xb4929480
08-30 16:01:58.669  6498  6744 V AudioTrack: ~AudioTrack, releasing session id from 6498 on behalf of 6498
08-30 16:01:58.669   322  3923 V AudioFlinger: releasing 22 from 6498 for 6498
08-30 16:01:58.669   322  3923 V AudioFlinger:  decremented refcount to 0
08-30 16:01:58.669   322  3923 V AudioFlinger: purging stale effects
08-30 16:01:58.669   322  3923 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 16:01:58.669   322  3923 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 16:01:58.669   322  1259 V AudioPolicyService: AudioCommandThread() waking up
08-30 16:01:58.670   322  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 16:01:58.670   322  1259 V AudioPolicyManager: releaseOutput() 2
,08-30 16:01:58.670   322  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 16:01:58.670   322  3923 V AudioFlinger: PlaybackThread::Track destructor
08-30 16:01:58.670   322  3923 V AudioFlinger: removeClient_l() pid 6498, calling pid 322
08-30 16:01:58.670  6498  6498 D A2dpService: Received start request. Starting profile...
08-30 16:01:58.672  6498  6498 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:01:58.673  6498  6498 V Avrcp   : make
08-30 16:01:58.674  1036  1766 W Process : Unable to open /proc/6747/status
08-30 16:01:58.674  6498  6498 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 16:01:58.674  6498  6498 I bluedroid-qcom: get_profile_interface avrcp
,08-30 16:01:58.684  6498  6498 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 16:01:58.689  6498  6498 E AudioManager: No RCC entry present to update
08-30 16:01:58.689  6498  6498 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 16:01:58.693  6498  6498 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 16:01:58.694  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 16:01:58.694  6498  6498 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 16:01:58.699  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 16:01:58.707  6710  6710 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 16:01:58.707  6710  6710 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:01:58.717  6710  6710 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13b7cc00
08-30 16:01:58.717  6710  6710 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:01:58.717  6710  6710 D AppUp4:CustFacade: isPhone : true
08-30 16:01:58.746  6710  6710 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:01:58.746  6710  6710 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 16:01:58.747  6710  6710 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-30 16:01:58.754  6710  6745 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 16:01:58.754  6710  6745 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 16:01:58.754  6710  6745 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 16:01:58.759  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:58.760  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 16:01:58.766  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:58.769  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:01:58.787  4272  6750 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 16:01:58.791  4272  6751 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:58.792  4272  6751 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:01:58.813  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:01:58.813  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:01:58.834  1036  1576 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6752 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 16:01:58.866  1036  1956 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 16:01:58.871  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 16:01:58.874  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 16:01:58.874  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-30 16:01:58.874  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 16:01:58.874  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 16:01:58.875  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:01:58.875  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 16:01:58.875  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 16:01:58.875  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 16:01:58.875  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:01:58.875  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 16:01:58.875  6498  6498 I BluetoothA2dpServiceJni: classInitNative
08-30 16:01:58.875  6498  6498 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:01:58.875  6498  6498 D A2dpStateMachine: make
08-30 16:01:58.876  6498  6498 I bluedroid-qcom: get_profile_interface a2dp
08-30 16:01:58.876  6498  6770 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 16:01:58.878  6498  6498 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:01:58.878  6498  6498 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 16:01:58.879  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.879  6498  6769 D A2dpStateMachine: Enter Disconnected: -2
08-30 16:01:58.880  6498  6498 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 16:01:58.881  6498  6498 D HidService: Received start request. Starting profile...
08-30 16:01:58.881  6498  6498 I bluedroid-qcom: get_profile_interface hidhost
08-30 16:01:58.881  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.881  6498  6498 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:01:58.882  6498  6498 D HealthService: Received start request. Starting profile...
08-30 16:01:58.883  6752  6752 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:01:58.883  6752  6752 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:01:58.884  6498  6498 I bluedroid-qcom: get_profile_interface health
08-30 16:01:58.884  6498  6498 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:01:58.884  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.885  6752  6752 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 16:01:58.885  6752  6752 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 16:01:58.885  6498  6498 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 16:01:58.890  6498  6498 D PanService: Received start request. Starting profile...
08-30 16:01:58.890  6498  6498 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:01:58.890  6498  6498 I bluedroid-qcom: get_profile_interface pan
08-30 16:01:58.896  6498  6498 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 16:01:58.896  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.897  6498  6498 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 16:01:58.903  6498  6498 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:01:58.903  6498  6498 D BtGatt.GattService: Received start request. Starting profile...
08-30 16:01:58.903  6498  6498 D BtGatt.GattService: start()
08-30 16:01:58.903  6498  6498 I bluedroid-qcom: get_profile_interface gatt
08-30 16:01:58.904  6498  6498 D BtGatt.AdvertiseManager: advertise manager created
08-30 16:01:58.908  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.909  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.910  6498  6498 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 16:01:58.910  6498  6498 V BluetoothMapService: BluetoothMapBinder()
08-30 16:01:58.911  6498  6498 D BluetoothMapService: Received start request. Starting profile...
08-30 16:01:58.911  6498  6498 D BluetoothMapService: start()
08-30 16:01:58.914  6498  6498 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 16:01:58.914  6498  6498 D BluetoothMapEmailAppObserver: createReceiver()
08-30 16:01:58.914  6498  6498 D BluetoothMapEmailAppObserver: initObservers()
08-30 16:01:58.915  6498  6498 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 16:01:58.919  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:58.919  6498  6498 D HeadsetStateMachine: Proxy object connected
08-30 16:01:58.920  6498  6498 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 16:01:58.920  6498  6498 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 16:01:58.921  6498  6744 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 16:01:58.921  6498  6744 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:01:58.921  6498  6744 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-30 16:01:58.923  6498  6498 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 16:01:58.924  6498  6498 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:58.927  6498  6498 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:01:58.928  6498  6498 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:01:58.930  6498  6498 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:01:58.930  6498  6498 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 16:01:58.932  6498  6498 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 16:01:58.936  6498  6498 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 16:01:58.936  6498  6498 V BluetoothMapService: Handler(): got msg=1
08-30 16:01:58.936  6498  6498 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:01:58.936  6498  6730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 16:01:58.936  6498  6498 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:01:58.937  6498  6498 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:01:58.937  6498  6730 I bluedroid-qcom: enable
08-30 16:01:58.937  6498  6498 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:58.937  6498  6498 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 16:01:58.937  6498  6777 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 16:01:58.937  6498  6777 I bt-btu  : btu_task pending for preload complete event
08-30 16:01:58.937  6498  6730 I bt_hci_bdroid: init
08-30 16:01:58.937  6498  6730 I bt_vendor: bt-vendor : init
08-30 16:01:58.937  6498  6730 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 16:01:58.937  6498  6730 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 16:01:58.937  6498  6730 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 16:01:58.938  6498  6730 D bt_userial_mct: userial_init
08-30 16:01:58.938  6498  6730 D bt_hci_bdroid: set_power 1
08-30 16:01:58.938  6498  6730 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 16:01:58.938  6498  6730 I bt_vendor: Starting hciattach daemon
08-30 16:01:58.938  6498  6730 I bt_vendor: try to set true
08-30 16:01:58.925  6780  6780 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:58.925  6780  6780 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:58.940  6752  6752 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 16:01:58.948  6752  6752 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 16:01:58.958  6781  6781 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 16:01:59.016  6788  6788 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 16:01:59.028  6789  6789 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 16:01:59.056  6791  6791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 16:01:59.060  1036  2056 I art     : Explicit concurrent mark sweep GC freed 127052(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.452ms total 77.575ms
,08-30 16:01:59.073  6752  6752 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 16:01:59.079  6792  6792 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 16:01:59.092  6794  6794 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 16:01:59.095  6752  6752 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:01:59.095  6752  6752 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:01:59.102  6795  6795 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 16:01:59.122  6798  6798 I libmdmdetect: ESOC framework not supported
08-30 16:01:59.123  6798  6798 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 16:01:59.131  6798  6798 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 16:01:59.131  6798  6798 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 16:01:59.131  6798  6798 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 16:01:59.131  6798  6798 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 16:01:59.131  6798  6798 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 16:01:59.131  6798  6798 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 16:01:59.131  6798  6798 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 16:01:59.173  6798  6799 E QC-QMI  : qmi_client [6798] 14: failed to locate client data
08-30 16:01:59.175   456   456 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 16:01:59.176   456   456 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 16:01:59.228  6752  6752 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 16:01:59.246  6805  6805 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 16:01:59.260  6806  6806 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 16:01:59.285  6752  6752 I HubEmail: JNI_OnLoad()
08-30 16:01:59.285  6752  6752 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 16:01:59.285  6752  6752 I HubEmail: registerNatives()
08-30 16:01:59.285  6752  6752 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 16:01:59.285  6752  6752 I HubEmail: registerNativeMethods()
08-30 16:01:59.285  6752  6752 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 16:01:59.285  6752  6752 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-30 16:01:59.289  3343  3343 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 16:01:59.289  3343  3343 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:01:59.290  6498  6730 I bt_vendor: bluetooth satus is on
08-30 16:01:59.290  6498  6730 D bt_hci_bdroid: preload
08-30 16:01:59.290  6498  6779 D bt_userial_mct: userial_open(port:0)
08-30 16:01:59.290  6498  6779 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 16:01:59.291  3343  3343 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 16:01:59.292  3343  3343 D PhoneState: setPdpRejectCasuse : false
08-30 16:01:59.293  6459  6810 W FormManager: Network not available. Please check & try again.
08-30 16:01:59.293  6498  6779 I bt_vendor: Done intiailizing UART
08-30 16:01:59.294  6498  6779 I bt_vendor: Done intiailizing UART
08-30 16:01:59.294  6498  6779 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 16:01:59.294  6498  6779 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 16:01:59.294  6498  6813 D bt_userial_mct: Entering userial_read_thread()
08-30 16:01:59.295  6498  6777 I bt-btu  : btu_task received preload complete event
08-30 16:01:59.295  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 16:01:59.295  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 16:01:59.297  6459  6811 V FormManager: Network unavailable.
08-30 16:01:59.298  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-30 16:01:59.302  6498  6777 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:01:59.303  6498  6777 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 16:01:59.348  1036  1959 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6814 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 16:01:59.355  6459  6811 V FormManager: Network unavailable.
08-30 16:01:59.356  6498  6777 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 16:01:59.356  6498  6777 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0214061 
08-30 16:01:59.356  6498  6777 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0214061 
,08-30 16:01:59.361  6752  6812 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:01:59.361  1036  1052 I ActivityManager: Killing 2203:com.lge.music/u0a34 (adj 15): empty #17
08-30 16:01:59.375  6498  6733 E bt-btif : Calling BTA_HhEnable
08-30 16:01:59.375  6498  6733 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 16:01:59.375  6498  6733 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 16:01:59.376  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 16:01:59.376  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 16:01:59.376  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 16:01:59.376  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 16:01:59.376  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-30 16:01:59.387   322  3923 V AudioFlinger: 2203 died, releasing its sessions
,08-30 16:01:59.387   322  3923 V AudioFlinger:  pid 1877 @ 0
08-30 16:01:59.387   322  3923 V AudioFlinger:  pid 3343 @ 1
08-30 16:01:59.387   322  3923 V AudioFlinger:  pid 3343 @ 2
08-30 16:01:59.389  6498  6777 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:01:59.389  6498  6777 W bt-smp  : Plain text(LSB ~ MSB) = 18 f0 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:01:59.389  6498  6777 W bt-smp  : Encrypted text(LSB ~ MSB) = e7 2b 18 09 ea 67 0f ef 6f b4 c8 8e 35 2f 67 13 
08-30 16:01:59.389  6498  6777 W bt-btm  : Stopping oneshot timer
08-30 16:01:59.414  6498  6733 D BluetoothAdapterProperties: Name is: G3
,08-30 16:01:59.415  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:01:59.415  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 16:01:59.420  1036  2056 W libprocessgroup: failed to open /acct/uid_10034/pid_2203/cgroup.procs: No such file or directory
08-30 16:01:59.423  6498  6733 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:01:59.423  6498  6733 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:01:59.423  6498  6733 D bt_hci_bdroid: postload
08-30 16:01:59.424  6498  6779 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:01:59.424  6498  6777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 16:01:59.424  6498  6733 D bte_conf: Device ID record 1 : primary
08-30 16:01:59.424  6498  6733 D bte_conf:   vendorId            = 00c4
08-30 16:01:59.424  6498  6733 D bte_conf:   vendorIdSource      = 0001
08-30 16:01:59.424  6498  6733 D bte_conf:   product             = 13a1
08-30 16:01:59.424  6498  6733 D bte_conf:   version             = 1000
08-30 16:01:59.424  6498  6733 D bte_conf:   clientExecutableURL = 
08-30 16:01:59.424  6498  6733 D bte_conf:   serviceDescription  = 
08-30 16:01:59.424  6498  6733 D bte_conf:   documentationURL    = 
08-30 16:01:59.424  6498  6733 D bte_conf: bte_load_did_conf no section named DID2.
08-30 16:01:59.425  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:59.427  6498  6730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 16:01:59.415  6833  6833 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:59.415  6833  6833 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 16:01:59.427  6498  6779 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:01:59.427  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:59.429  6498  6779 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:01:59.429  6498  6779 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:01:59.429  6498  6730 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:01:59.430  6498  6730 D BluetoothAdapterProperties: State =  11
,08-30 16:01:59.430  6498  6730 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 16:01:59.430  6498  6730 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 16:01:59.430  6498  6730 D BluetoothAdapterProperties: Setting state to 12
08-30 16:01:59.430  6498  6730 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 16:01:59.431  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:01:59.431  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 16:01:59.431  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 16:01:59.431  6498  6730 I BluetoothAdapterState: Entering On State
08-30 16:01:59.432  6498  6733 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:01:59.433  6498  6813 E bt_mct  : hci lib postload completed
08-30 16:01:59.434  6356  6372 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:01:59.434  6498  6730 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 16:01:59.435  6498  6730 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 16:01:59.435  6498  6730 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 16:01:59.435  6498  6730 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 16:01:59.435  6498  6733 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:01:59.437  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:01:59.438  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:01:59.439  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:01:59.440  1036  1036 D BluetoothHeadset: Proxy object connected
08-30 16:01:59.443  1877  1877 D BluetoothHeadset: Proxy object connected
08-30 16:01:59.444  1036  1036 D BluetoothA2dp: Proxy object connected
,08-30 16:01:59.450  6356  6356 D BluetoothInputDevice: Proxy object connected
08-30 16:01:59.451  6356  6356 D HidProfile: Bluetooth service connected
08-30 16:01:59.452  1877  2540 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:01:59.455  1877  1877 D BluetoothHeadset: Proxy object connected
08-30 16:01:59.455  1877  2862 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:01:59.457  1877  1877 D BluetoothHeadset: Proxy object connected
08-30 16:01:59.457  6356  6372 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:01:59.459  6498  6733 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:01:59.460  6356  6373 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:01:59.460  6498  6733 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 16:01:59.466  6356  6373 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:01:59.466  6356  6373 D BluetoothPan: onBluetoothStateChange call bindService
08-30 16:01:59.469  6356  6356 D BluetoothMap: Proxy object connected
08-30 16:01:59.469  6356  6356 D MapProfile: Bluetooth service connected
08-30 16:01:59.469  6356  6356 D BluetoothMap: getConnectedDevices()
,08-30 16:01:59.475  1036  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 16:01:59.475  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 16:01:59.475  6498  6739 V BluetoothMapService: getConnectedDevices()
08-30 16:01:59.477  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.477  1984  2179 D LGBluetoothAPIService: Message: 1
08-30 16:01:59.477  1984  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 16:01:59.481  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:01:59.482  6498  6730 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 16:01:59.482  1984  2179 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-30 16:01:59.487  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 16:01:59.487  1036  1097 D BluetoothManagerService: Message: 40
08-30 16:01:59.487  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 16:01:59.491  6498  6498 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.491  6498  6498 D BluetoothMapService: STATE_ON
08-30 16:01:59.493  6498  6498 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 16:01:59.493  6498  6498 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 16:01:59.495  6498  6498 V BluetoothMapService: Handler(): got msg=1
08-30 16:01:59.496  6838  6838 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 16:01:59.498  6240  6240 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 16:01:59.499  6498  6498 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 16:01:59.499  1984  1984 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 16:01:59.499  1984  2179 D LGBluetoothAPIService: Message: 100
08-30 16:01:59.499  1984  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 16:01:59.500  6356  6356 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:01:59.500  6356  6356 D PanProfile: Bluetooth service connected
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:59.507  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:59.507  6356  6356 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 16:01:59.509  6498  6839 D BluetoothMapMasInstance: MAS initSocket()
08-30 16:01:59.510  6498  6839 D BluetoothMapMasInstance:   masId = 00
08-30 16:01:59.510  6498  6839 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 16:01:59.510  6498  6839 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 16:01:59.510  6498  6839 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 16:01:59.510  1036  1097 D BluetoothManagerService: Message: 30
08-30 16:01:59.511  1036  2074 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 16:01:59.515  6498  6839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:01:59.516  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:59.517  6498  6839 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 16:01:59.517  6498  6839 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 16:01:59.517  6498  6839 D BluetoothMapMasInstance: Accepting socket connection...
08-30 16:01:59.518  6498  6733 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:01:59.518  6498  6733 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 16:01:59.523  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:59.523  6498  6498 V BluetoothPbapService: Pbap Service onCreate
,08-30 16:01:59.523  6498  6498 V BluetoothPbapService: Starting PBAP service
08-30 16:01:59.526  6498  6498 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 16:01:59.526  6498  6498 V BluetoothPbapService: Pbap Service onBind
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:59.527  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:01:59.528  6356  6356 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 16:01:59.528  6498  6498 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.528  6498  6498 V BluetoothPbapService: state: 12
,08-30 16:01:59.528  6498  6498 V BluetoothPbapService: Handler(): got msg=1
08-30 16:01:59.529  6498  6498 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 16:01:59.530  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:59.531  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:59.533  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:59.535  6498  6845 V BluetoothPbapService: Pbap Service initSocket
08-30 16:01:59.535  1036  1097 D BluetoothManagerService: Message: 30
08-30 16:01:59.536  1036  2128 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 16:01:59.537  6498  6845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:01:59.539  6498  6845 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 16:01:59.539  6498  6845 V BluetoothPbapService: Succeed to create listening socket 
08-30 16:01:59.539  6498  6845 V BluetoothPbapService: Accepting socket connection...
08-30 16:01:59.542  6356  6356 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 16:01:59.543  6356  6356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 16:01:59.549  6356  6356 D BluetoothA2dp: Proxy object connected
08-30 16:01:59.549  6356  6356 D A2dpProfile: Bluetooth service connected
,08-30 16:01:59.551  6498  6498 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:01:59.551  6498  6498 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.551  6498  6498 V BluetoothPbapReceiver: ***********state = 12
08-30 16:01:59.555  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:01:59.556  2286  2286 D c       : Getting all permits...
08-30 16:01:59.556  2286  2286 D a       : Opening database...
08-30 16:01:59.560  2286  2286 D a       : Opening database auth.proximity.permit_store...
08-30 16:01:59.560  2286  2286 D a       : Closing database...
08-30 16:01:59.561  6356  6356 D BluetoothPbap: Proxy object connected
,08-30 16:01:59.562  6356  6356 D PbapServerProfile: Bluetooth service connected
08-30 16:01:59.562  6356  6356 D BluetoothHeadset: Proxy object connected
08-30 16:01:59.564  6356  6356 D HeadsetProfile: Bluetooth service connected
08-30 16:01:59.574  6356  6356 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:01:59.580  6356  6356 D BluetoothPermissionRequest: onReceive
08-30 16:01:59.582  6356  6356 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 16:01:59.584  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:01:59.587  6814  6814 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:01:59.587  6814  6814 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:01:59.588  6498  6498 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 16:01:59.589  6498  6498 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 16:01:59.592  6814  6814 D PhoneMonitor: Register our PhoneStateListener
08-30 16:01:59.597  6498  6498 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 16:01:59.611  6814  6814 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 16:01:59.613  6814  6814 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 16:01:59.618  6498  6498 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:01:59.618  6498  6498 V BtOppService: onCreate
08-30 16:01:59.624  6498  6498 V BluetoothOppNotification: send message
,08-30 16:01:59.631  6814  6814 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 16:01:59.633  6814  6814 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 16:01:59.633  6814  6814 D TelephonyAutoProfiling: [parse] Load xml
08-30 16:01:59.636  6498  6851 V BtOppService: Deleted complete outbound shares, number =  0
08-30 16:01:59.636  6814  6814 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 16:01:59.636  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 16:01:59.636  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 16:01:59.636  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 16:01:59.637  6814  6814 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 16:01:59.637  6814  6814 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-30 16:01:59.638  6498  6851 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 16:01:59.639  6498  6851 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 16:01:59.640  6498  6851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@291c4b9a on behalf of 
08-30 16:01:59.643  6814  6814 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-30 16:01:59.690  1036  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6853 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:01:59.692  1036  1051 I ActivityManager: Killing 5979:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-30 16:01:59.694  6498  6498 V BtOppService: Starting RfcommListener
08-30 16:01:59.699  6498  6498 D BluetoothOppPreference: Dumping Names:  
08-30 16:01:59.699  6498  6498 D BluetoothOppPreference: {}
08-30 16:01:59.699  6498  6498 D BluetoothOppPreference: Dumping Channels:  
08-30 16:01:59.699  6498  6498 D BluetoothOppPreference: {}
08-30 16:01:59.699  6498  6498 V BtOppService: onStartCommand
08-30 16:01:59.707  6498  6866 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:01:59.708  6498  6866 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 16:01:59.723  6498  6866 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@165bca8 on behalf of 
08-30 16:01:59.724  6498  6866 V BluetoothOppNotification: update too frequent, put in queue
,08-30 16:01:59.725  6498  6866 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 16:01:59.764  6498  6498 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.764  1036  2128 W libprocessgroup: failed to open /acct/uid_10061/pid_5979/cgroup.procs: No such file or directory
08-30 16:01:59.765  6498  6498 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 16:01:59.773  6498  6498 V BluetoothOppNotification: new notify threadi!
08-30 16:01:59.774  6498  6498 V BluetoothOppNotification: send delay message
08-30 16:01:59.774  6498  6498 V BtOppService: ContentObserver received notification
08-30 16:01:59.775  6498  6498 V BtOppService: ContentObserver received notification
08-30 16:01:59.775  6498  6873 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 16:01:59.775  6498  6498 V BtOppService: start RfcommListener
08-30 16:01:59.777  6498  6873 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29bcb3c1 on behalf of 
,08-30 16:01:59.777  6498  6874 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:01:59.777  6498  6874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:01:59.777  6498  6873 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 16:01:59.778  6498  6498 V BtOppService: RfcommListener started
08-30 16:01:59.779  6498  6874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c638766 on behalf of 
08-30 16:01:59.779  6498  6875 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 16:01:59.779  1036  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:59.780  6498  6874 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 16:01:59.780  6498  6875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:01:59.780  6498  6873 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 16:01:59.781  6498  6875 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 16:01:59.781  6498  6875 V BtOppRfcommListener: Started RFCOMM listener....
08-30 16:01:59.781  6498  6875 I BtOppRfcommListener: Accept thread started.
08-30 16:01:59.781  6498  6875 V BtOppRfcommListener: Accepting connection...
08-30 16:01:59.782  6498  6873 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3885eaa7 on behalf of 
08-30 16:01:59.782  6498  6873 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 16:01:59.784  6498  6873 V BluetoothOppNotification: outbound notification was removed.
08-30 16:01:59.784  6498  6873 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 16:01:59.785  6498  6873 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2adfb54 on behalf of 
08-30 16:01:59.786  6498  6873 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 16:01:59.787  6498  6873 V BluetoothOppNotification: inbound notification was removed.
08-30 16:01:59.787  6498  6873 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 16:01:59.788  6498  6873 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d9fcafd on behalf of 
,08-30 16:01:59.792  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:59.792  6498  6498 V BluetoothFtpService: Ftp Service onCreate
08-30 16:01:59.792  6498  6498 I BluetoothFtpService: Ftp Service onCreate
08-30 16:01:59.792  6498  6498 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:01:59.792  6498  6498 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.792  6498  6498 V BluetoothFtpService: Starting Listening on sockets
08-30 16:01:59.793  6498  6498 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:01:59.793  6498  6498 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:01:59.793  6498  6498 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:01:59.793  6498  6498 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.793  6498  6498 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 16:01:59.793  6498  6498 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:01:59.794  6498  6498 V BluetoothFtpService: Handler(): got msg=1
08-30 16:01:59.795  6498  6498 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 16:01:59.795  6498  6498 V BluetoothFtpService: Ftp Service initSocket
08-30 16:01:59.799  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:59.800  6498  6498 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:01:59.800  6498  6498 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 16:01:59.801  6498  6498 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 16:01:59.802  6498  6876 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 16:01:59.814  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:01:59.814  6498  6498 V BluetoothSapService: Sap Service onCreate
,08-30 16:01:59.815  6498  6498 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:01:59.815  6498  6498 V BluetoothSapService: state: 12
08-30 16:01:59.815  6498  6498 V BluetoothSapService: Starting SAP server process
08-30 16:01:59.817  6498  6498 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 16:01:59.805  6877  6877 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:59.805  6877  6877 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:01:59.818  6498  6878 V BluetoothSapService: Sap Service initRfcommSocket
08-30 16:01:59.818  1036  2074 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:01:59.819  6498  6878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:01:59.820  6498  6878 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 16:01:59.820  6498  6878 V BluetoothSapService: Succeed to create listening socket 
08-30 16:01:59.820  6498  6878 V BluetoothSapService: Accepting socket connection...
08-30 16:01:59.825  6877  6877 V BT_SAP  : Event pipe created
08-30 16:01:59.825  6877  6877 V BT_SAP  : create_server_socket qcom.sap.server
08-30 16:01:59.825  6877  6877 V BT_SAP  : created socket fd 6
08-30 16:02:00.000  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=372197663, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-30 16:02:00.048  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 16:02:00.048  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-30 16:02:00.048  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 16:02:00.049  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-30 16:02:00.051  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 16:02:00.051  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-30 16:02:00.052  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-30 16:02:00.052  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 16:02:00.060  2639  2639 D [Concierge]Service: onStartCommand(). Type : 9
08-30 16:02:00.208  1036  2094 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6880 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 16:02:00.212  1036  2094 I ActivityManager: Killing 6035:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 16:02:00.264  1036  2056 W libprocessgroup: failed to open /acct/uid_10080/pid_6035/cgroup.procs: No such file or directory
,08-30 16:02:00.320  6880  6880 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-30 16:02:00.323  6880  6880 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-30 16:02:00.333  6880  6880 V DrmService: Service onCreate
08-30 16:02:00.333  6880  6880 D DrmService: Received new request = 2
,08-30 16:02:00.340  6880  6897 I DrmSntpClient: Start Sync process
08-30 16:02:00.340  6880  6897 D DrmSntpClient: Server : 0
08-30 16:02:00.390  1036  2014 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6898 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:02:00.395  6880  6897 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-30 16:02:00.398  6880  6880 D DrmService: Completed !! request = 2
08-30 16:02:00.399  6880  6880 D DrmService: Request count = 0
08-30 16:02:00.401  6880  6880 V DrmService: Service onDestroy
08-30 16:02:00.403  1036  1766 I ActivityManager: Killing 6056:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 16:02:00.454  1036  1052 W libprocessgroup: failed to open /acct/uid_10097/pid_6056/cgroup.procs: No such file or directory
,08-30 16:02:00.483  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:02:00.483  1036  1392 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:02:00.492  6898  6898 I art     : Almond Protected OAT
08-30 16:02:00.535  1036  1438 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 16:02:00.536  1036  1438 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 16:02:00.551  6898  6898 D WeatherApplication: removeAccount
,08-30 16:02:00.552  6898  6898 D WeatherApplication: Account.length = 0
08-30 16:02:00.553  6898  6898 E WeatherApplication: OPERATOR:OPEN
08-30 16:02:00.558  6898  6898 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:0
08-30 16:02:00.562  6898  6898 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 16:02:00.562  6898  6898 D Weather.Utils: 2 : All the weather widget is gone.
08-30 16:02:00.564  6898  6898 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-30 16:02:00.568  6898  6898 D WeatherAncestor: connectivity changed - connection : true
08-30 16:02:00.569  6898  6898 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 16:02:00.581  6898  6898 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 16:02:00.581  6898  6898 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 16:02:00.582  6898  6898 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 16:02:00.601  6898  6898 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 16:02:00.602  6898  6898 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:0
,08-30 16:02:00.682  1036  2129 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6916 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:02:00.689  1036  2129 I ActivityManager: Killing 6090:com.lge.eula/1000 (adj 15): empty #17
,08-30 16:02:00.734  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6090/cgroup.procs: No such file or directory
,08-30 16:02:00.776  6498  6498 V BluetoothOppNotification: new notify threadi!
08-30 16:02:00.776  6498  6498 V BluetoothOppNotification: send delay message
08-30 16:02:00.777  6498  6936 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 16:02:00.780  6498  6936 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35f21d3e on behalf of 
08-30 16:02:00.781  6498  6936 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 16:02:00.782  6498  6936 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 16:02:00.783  6498  6936 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18f3879f on behalf of 
08-30 16:02:00.784  6498  6936 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 16:02:00.787  6498  6936 V BluetoothOppNotification: outbound notification was removed.
08-30 16:02:00.787  6498  6936 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 16:02:00.793  6498  6936 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16fd60ec on behalf of 
08-30 16:02:00.794  6498  6936 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 16:02:00.797  6498  6936 V BluetoothOppNotification: inbound notification was removed.
08-30 16:02:00.797  6498  6936 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 16:02:00.799  6498  6936 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff25cb5 on behalf of 
08-30 16:02:00.850   278   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 16:02:00.850   278   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 16:02:00.850   278   365 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 16:02:00.851  6916  6938 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 16:02:00.854   278   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 16:02:00.854   278   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,08-30 16:02:00.854   278   365 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 16:02:00.854  6916  6938 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 16:02:00.870   278   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 16:02:00.870   278   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 16:02:00.870   278   365 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 16:02:00.870  6916  6940 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 16:02:00.874   278   365 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 16:02:00.875   278   365 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 16:02:00.875   278   365 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:02:00.875  6916  6940 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 16:02:01.166  6916  6916 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 16:02:01.185  6916  6916 I LibraryLoader: Loading: webviewchromium
,08-30 16:02:01.193  6916  6916 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 850-859)
08-30 16:02:01.193  6916  6916 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:02:01.199  6916  6916 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {205ac365}
08-30 16:02:01.201  6916  6916 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:02:01.202  6916  6916 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 16:02:01.216  6916  6916 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 16:02:01.217  6916  6916 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:02:01.231  6916  6916 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 16:02:01.240  6916  6916 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 16:02:01.241  6916  6916 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 16:02:01.245   322  1399 V AudioPolicyService: registerClient() client 0xb0410580, uid 10093
,08-30 16:02:01.249  6916  6965 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 16:02:01.263  6916  6916 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:02:01.263  6916  6916 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:02:01.263  6916  6916 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:02:01.263  6916  6916 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:02:01.263  6916  6916 I Adreno-EGL: Remote Branch: 
08-30 16:02:01.263  6916  6916 I Adreno-EGL: Local Patches: 
08-30 16:02:01.263  6916  6916 I Adreno-EGL: Reconstruct Branch: 
,08-30 16:02:01.370  6916  6916 I NSApplication: Starting up...
,08-30 16:02:01.437  1036  2014 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6978 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 16:02:01.439  1036  2013 I ActivityManager: Killing 5936:com.android.vending/u0a44 (adj 15): empty #17
08-30 16:02:01.505  1036  2094 W libprocessgroup: failed to open /acct/uid_10044/pid_5936/cgroup.procs: No such file or directory
,08-30 16:02:01.508  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:01.508  1036  2075 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@168a1aa4 mBinding = false
08-30 16:02:01.525  1036  1097 D BluetoothManagerService: Message: 2
,08-30 16:02:01.526  1036  1097 D BluetoothManagerService: Sending off request.
08-30 16:02:01.527  6498  6741 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 16:02:01.527  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:02:01.528  6498  6730 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 16:02:01.528  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:02:01.528  6498  6730 D BluetoothAdapterProperties: Setting state to 13
08-30 16:02:01.528  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:02:01.528  6498  6730 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 16:02:01.529  6498  6730 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 16:02:01.529  6498  6730 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 16:02:01.530  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:02:01.530  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 16:02:01.530  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 16:02:01.531  6498  6733 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:02:01.532  6498  6730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 16:02:01.533  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 16:02:01.533  6498  6777 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 16:02:01.535  6498  6876 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 16:02:01.535  6498  6878 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:02:01.535  6498  6845 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:02:01.536  6498  6875 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:02:01.536  6498  6730 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:02:01.536  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.536  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 16:02:01.541  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:02:01.541  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:02:01.542  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:02:01.542  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:02:01.548  6356  6356 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 16:02:01.549  6498  6839 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 16:02:01.550  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 16:02:01.551  6498  6777 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-30 16:02:01.552  6498  6498 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.553  6498  6498 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:02:01.553  6498  6498 V BluetoothMapService: Handler(): got msg=4
08-30 16:02:01.553  6498  6498 D BluetoothMapService: MAP Service closeService in
08-30 16:02:01.553  6498  6498 D BluetoothMapMasInstance: MAP Service shutdown
08-30 16:02:01.554  6498  6498 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:02:01.554  6498  6498 V BluetoothMapService: MAP Service closeService out
08-30 16:02:01.555  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:02:01.555  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:02:01.556  6498  6498 V BtOppService: Receiver DISABLED_ACTION 
08-30 16:02:01.556  6498  6498 I BtOppRfcommListener: stopping Accept Thread
08-30 16:02:01.556  6498  6498 V BtOppRfcommListener: close mBtServerSocket
08-30 16:02:01.557  6498  6498 V BtOppRfcommListener: waiting for thread to terminate
08-30 16:02:01.557  6498  6875 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:02:01.558  6498  6498 V BtOppRfcommListener: done waiting for thread to terminate
08-30 16:02:01.558  6240  6240 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:02:01.558  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:02:01.560  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:01.560  6356  6356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 16:02:01.563  6498  6498 V BtOppService: onDestroy
,08-30 16:02:01.564  6498  6498 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 16:02:01.565  6498  6498 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:02:01.565  6498  6498 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.565  6498  6498 V BluetoothPbapReceiver: ***********state = 13
08-30 16:02:01.567  6498  6498 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 16:02:01.568  6498  6498 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.568  6498  6498 V BluetoothPbapService: state: 13
08-30 16:02:01.569  6498  6498 V BluetoothPbapService: Pbap Service closeService in
08-30 16:02:01.569  6356  6356 D DockEventReceiver: finishStartingService: stopping service
08-30 16:02:01.569  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:01.571  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:02:01.574  6498  6498 V BluetoothPbapService: successfully stopped pbap service
08-30 16:02:01.574  6356  6356 D BluetoothPbap: Proxy object disconnected
08-30 16:02:01.574  6498  6498 V BluetoothPbapService: Pbap Service closeService out
08-30 16:02:01.574  6356  6356 D PbapServerProfile: Bluetooth service disconnected
08-30 16:02:01.574  6498  6498 V BluetoothPbapService: Pbap Service onDestroy
08-30 16:02:01.574  6498  6498 V BluetoothPbapService: Pbap Service closeService in
08-30 16:02:01.574  6498  6498 V BluetoothPbapService: Pbap Service closeService out
08-30 16:02:01.574  6498  6498 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 16:02:01.584  6356  6356 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 16:02:01.589  6978  6978 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:02:01.594  6356  6356 D BluetoothPermissionRequest: onReceive
08-30 16:02:01.594  6356  6356 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 16:02:01.601  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:02:01.604  6498  6498 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 16:02:01.605  6498  6498 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 16:02:01.606  6498  6498 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 16:02:01.610  6498  6498 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.610  6498  6498 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 16:02:01.611  6498  6498 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:02:01.611  6498  6498 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.612  6498  6498 V BluetoothFtpService: Ftp Service closeService
08-30 16:02:01.612  6498  6498 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 16:02:01.613  6498  6498 V BluetoothFtpService: successfully stopped ftp service
08-30 16:02:01.614  6498  6498 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:02:01.614  6498  6498 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:02:01.614  6498  6498 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:02:01.614  6498  6498 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.614  6498  6498 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 16:02:01.614  6498  6498 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:02:01.615  6498  6498 V BluetoothFtpService: Ftp Service onDestroy
08-30 16:02:01.615  6498  6498 V BluetoothFtpService: Ftp Service closeService
08-30 16:02:01.618  6498  6498 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:01.618  6498  6498 V BluetoothSapService: state: 13
08-30 16:02:01.618  6498  6498 V BluetoothSapService: Stopping SAP server process
08-30 16:02:01.619  6498  6498 V BluetoothSapService: Sap Service closeSapService in
08-30 16:02:01.619  6498  6498 V BluetoothSapService: Close listen Socket : 
08-30 16:02:01.619  6498  6498 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:02:01.619  6498  6498 V BluetoothSapService: Close sapd  Socket : 
08-30 16:02:01.620  6498  6498 V BluetoothSapService: Sap Service closeSapService out
08-30 16:02:01.620  6498  6498 V BluetoothSapService: Sap Service onDestroy
08-30 16:02:01.620  6498  6498 V BluetoothSapService: Sap Service closeSapService in
08-30 16:02:01.620  6498  6498 V BluetoothSapService: Close listen Socket : 
08-30 16:02:01.620  6498  6498 V BluetoothSapService: Close rfcomm Socket : 
08-30 16:02:01.620  6498  6498 V BluetoothSapService: Close sapd  Socket : 
08-30 16:02:01.621  6498  6498 V BluetoothSapService: Sap Service closeSapService out
08-30 16:02:01.795  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 16:02:01.797  3703  6354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 16:02:01.819  2286  2286 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:02:01.826  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 16:02:01.826  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:02:01.826  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:02:01.826  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 16:02:01.829  6710  6710 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 16:02:01.834  6710  6710 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13b7cc00
08-30 16:02:01.834  6710  6710 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:02:01.834  6710  6710 D AppUp4:CustFacade: isPhone : true
,08-30 16:02:01.835  6710  6710 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:02:01.835  6710  6710 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 16:02:01.838  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 16:02:01.839  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:02:01.840  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:02:01.842  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:02:01.849  4272  7018 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:02:01.849  6752  6752 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 16:02:01.852  4272  7019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:02:01.853  4272  7019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:02:01.870  3343  3343 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 16:02:01.870  3343  3343 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:02:01.871  3343  3343 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 16:02:01.877  6814  6814 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 16:02:01.877  6814  6814 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 16:02:01.878  6459  7022 W FormManager: Network not available. Please check & try again.
08-30 16:02:01.883  6752  7026 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:02:01.888  6459  7023 V FormManager: Network unavailable.
08-30 16:02:01.894  6898  6898 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:1
08-30 16:02:01.895  6459  7023 V FormManager: Network unavailable.
,08-30 16:02:01.896  6898  6898 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 16:02:01.896  6898  6898 D Weather.Utils: 2 : All the weather widget is gone.
08-30 16:02:01.896  6898  6898 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 16:02:01.896  6898  6898 D WeatherAncestor: connectivity changed - connection : true
08-30 16:02:01.897  6898  6898 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12f6c27e
08-30 16:02:01.897  6898  6898 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 16:02:01.898  6898  6898 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 16:02:01.898  6898  6898 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-30 16:02:01.898  6898  6898 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 16:02:01.898  6898  6898 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:1
08-30 16:02:01.924  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 16:02:01.927  3703  6354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 16:02:01.945  2286  2286 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:02:01.955  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 16:02:01.956  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:02:01.956  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 16:02:01.956  6710  6710 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 16:02:01.958  6710  6710 I AppUp4:CustModeStarterReceiver: onReceive
08-30 16:02:01.962  6710  6710 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13b7cc00
08-30 16:02:01.962  6710  6710 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 16:02:01.963  6710  6710 D AppUp4:CustFacade: isPhone : true
08-30 16:02:01.963  6710  6710 D AppUp4:CustModeStarterReceiver: begin check event
08-30 16:02:01.963  6710  6710 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 16:02:01.969  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:02:01.970  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:02:01.974  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:02:01.977  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:02:01.987  6752  6752 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 16:02:01.989  4272  7028 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 16:02:01.999  4272  7029 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 16:02:01.999  4272  7029 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:02:02.014  6752  7032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:02:02.020  3343  3343 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-30 16:02:02.020  3343  3343 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 16:02:02.020  3343  3343 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 16:02:02.024  6459  7031 W FormManager: Network not available. Please check & try again.
08-30 16:02:02.028  6814  6814 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 16:02:02.029  6814  6814 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 16:02:02.030  6459  7033 V FormManager: Network unavailable.
,08-30 16:02:02.038  6459  7033 V FormManager: Network unavailable.
08-30 16:02:02.041  6898  6898 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:2
,08-30 16:02:02.045  6898  6898 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 16:02:02.045  6898  6898 D Weather.Utils: 2 : All the weather widget is gone.
08-30 16:02:02.045  6898  6898 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 16:02:02.046  6898  6898 D WeatherAncestor: connectivity changed - connection : true
08-30 16:02:02.046  6898  6898 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12f6c27e
08-30 16:02:02.046  6898  6898 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 16:02:02.046  6898  6898 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 16:02:02.046  6898  6898 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 16:02:02.047  6898  6898 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 16:02:02.047  6898  6898 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:2
08-30 16:02:02.082  6420  6420 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-30 16:02:02.084  6420  6420 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7835
08-30 16:02:02.085  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=372197663 [*alarm*], flags=0x0
08-30 16:02:02.437  6498  6733 D bt_hci_bdroid: cleanup
,08-30 16:02:02.440  6498  6779 I bt_lpm  : LPM is already off!!!
08-30 16:02:02.440  6498  6813 I bt_userial_mct: exiting userial_read_thread
08-30 16:02:02.440  6498  6813 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 16:02:02.440  6498  6777 W bt-btif : ag scb idx 1 not allocated
08-30 16:02:02.441  6498  6777 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 16:02:02.441  6498  6777 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:02:02.441  6498  6777 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 16:02:02.442  6498  6733 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 16:02:02.442  6498  6779 I bt_vendor: hw_epilog_process
08-30 16:02:02.443  6498  6733 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 16:02:02.443  6498  6733 D bt_userial_mct: userial_close
08-30 16:02:02.443  6498  6733 E bt_userial_mct: pthread_join() FAILED result:3
08-30 16:02:02.443  6498  6733 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 16:02:02.464  6498  6733 D bt_hci_bdroid: set_power 0
08-30 16:02:02.464  6498  6733 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 16:02:02.464  6498  6733 I bt_vendor: bluetooth satus is on
08-30 16:02:02.464  6498  6733 I bt_vendor: bt-vendor : resetting BT status
08-30 16:02:02.464  6498  6733 I bt_vendor: Starting hciattach daemon
08-30 16:02:02.464  6498  6733 I bt_vendor: try to set false
,08-30 16:02:02.471  6498  6733 I bt_vendor: Starting hciattach daemon
08-30 16:02:02.471  6498  6733 I bt_vendor: try to set false
08-30 16:02:02.472  6498  6733 I bt_vendor: cleanup
08-30 16:02:02.472  6498  6777 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 16:02:02.473  6498  6733 I GKI_LINUX: GKI_exit_task 0 done
08-30 16:02:02.473  6498  6733 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 16:02:02.475  6498  6730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 16:02:02.478  6498  6498 D HeadsetService: Received stop request...Stopping profile...
,08-30 16:02:02.482  6498  6498 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:02:02.482  6498  6498 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:02:02.482  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:02.482  6498  6744 D HeadsetStateMachine: Exit Disconnected: -1
08-30 16:02:02.485  6498  6498 D HeadsetStateMachine: Unbinding service...
08-30 16:02:02.487  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-30 16:02:02.487  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 16:02:02.488  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-30 16:02:02.488  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-30 16:02:02.488  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-30 16:02:02.489  6498  6498 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:02:02.489  6498  6498 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:02:02.489  6498  6498 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:02:02.489  6498  6498 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:02:02.489  6498  6498 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:02:02.489  6498  6498 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:02:02.489  6498  6498 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 16:02:02.491  6498  6498 D A2dpService: Received stop request...Stopping profile...
,08-30 16:02:02.496  6498  6769 D A2dpStateMachine: Exit Disconnected: -1
08-30 16:02:02.498  6498  6498 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 16:02:02.502  6498  6730 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 16:02:02.502  6498  6498 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 16:02:02.502  6498  6498 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:02:02.502  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:02.505  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-30 16:02:02.505  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 16:02:02.508  6498  6498 D HidService: Received stop request...Stopping profile...
08-30 16:02:02.508  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:02.511  6498  6498 D HealthService: Received stop request...Stopping profile...
08-30 16:02:02.511  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:02.514  6498  6498 D PanService: Received stop request...Stopping profile...
08-30 16:02:02.514  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:02.516  6498  6498 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:02:02.516  6498  6498 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 16:02:02.516  6498  6498 D BtGatt.GattService: stop()
08-30 16:02:02.517  6498  6498 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 16:02:02.520  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:02.522  6498  6498 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:02:02.522  6498  6498 D BluetoothMapService: stop()
08-30 16:02:02.522  6498  6498 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 16:02:02.523  6498  6498 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 16:02:02.524  6498  6498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:02.525  6498  6498 V BluetoothMapService: Handler(): got msg=4
08-30 16:02:02.525  6498  6498 D BluetoothMapService: MAP Service closeService in
08-30 16:02:02.525  6498  6498 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:02:02.525  6498  6498 V BluetoothMapService: MAP Service closeService out
08-30 16:02:02.525  6498  6730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 16:02:02.525  6498  6730 D BluetoothAdapterProperties: Setting state to 10
08-30 16:02:02.525  6498  6730 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 16:02:02.526  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:02:02.526  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 16:02:02.526  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 16:02:02.527  6498  6730 I BluetoothAdapterState: Entering OffState
08-30 16:02:02.527  6356  6372 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:02:02.528  6356  6372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:02:02.529  6498  6498 I BluetoothA2dpServiceJni: cleanupNative
,08-30 16:02:02.531  6498  6770 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 16:02:02.533  6498  6498 I GKI_LINUX: GKI_exit_task 2 done
08-30 16:02:02.533  6498  6498 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 16:02:02.534  6356  6372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:02:02.535  6498  6498 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:02:02.535  6498  6498 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:02:02.538  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:02:02.538  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:02:02.538  1877  4372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:02:02.539  1877  2862 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:02:02.539  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:02:02.540  6356  6372 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:02:02.541  6498  6498 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 16:02:02.543  6498  6498 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:02:02.543  6498  6498 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:02:02.545  6498  6498 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:02:02.545  6498  6498 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:02:02.547  6498  6498 D BluetoothMapService: cleanup()
08-30 16:02:02.547  6498  6498 D BluetoothMapService: MAP Service closeService in
08-30 16:02:02.547  6498  6498 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 16:02:02.547  6498  6498 V BluetoothMapService: MAP Service closeService out
08-30 16:02:02.548  6356  6372 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:02:02.549  6356  6372 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:02:02.550  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 16:02:02.550  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 16:02:02.552  1036  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 16:02:02.552  1036  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 16:02:02.552  1036  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@168a1aa4 mBinding = false
08-30 16:02:02.552  1036  1097 D BluetoothManagerService: Sending unbind request.
,08-30 16:02:02.559  6498  6733 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 16:02:02.561  6498  6498 I GKI_LINUX: GKI_exit_task 1 done
08-30 16:02:02.561  6498  6498 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 16:02:02.561  6498  6498 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 16:02:02.561  6498  6498 I art     : --- WEIRD: removing null entry 248
08-30 16:02:02.561  6498  6498 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 16:02:02.561  6498  6498 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 16:02:02.562  6498  6498 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 16:02:02.564  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-30 16:02:02.567  6498  6498 I art     : System.exit called, status: 0
08-30 16:02:02.567  6498  6498 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 16:02:02.579  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:02.582  1984  2179 D LGBluetoothAPIService: Message: 2
08-30 16:02:02.582  1984  2179 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@dcb1e13 mBinding = false
08-30 16:02:02.582  1984  2179 D LGBluetoothAPIService: Sending unbind request.
08-30 16:02:02.586  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 16:02:02.598  1602  1602 D BluetoothAdapter: 960388475: getState() :  mService = null. Returning STATE_OFF
08-30 16:02:02.598  1602  1602 D BluetoothAdapter: 960388475: getState() :  mService = null. Returning STATE_OFF
08-30 16:02:02.603   322  3923 V AudioFlinger: 6498 died, releasing its sessions
08-30 16:02:02.603   322  3923 V AudioFlinger:  pid 1877 @ 0
08-30 16:02:02.603   322  3923 V AudioFlinger:  pid 3343 @ 1
08-30 16:02:02.603   322  3923 V AudioFlinger:  pid 3343 @ 2
08-30 16:02:02.604  6356  6356 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 16:02:02.604  6356  6356 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 16:02:02.604  6356  6356 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 16:02:02.604  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:02.605  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:02.608  1036  1051 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-30 16:02:02.608  1036  1051 W ActivityManager: android.os.DeadObjectException
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-30 16:02:02.608  1036  1051 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 16:02:02.608  6356  6356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 16:02:02.664  1036  2128 I ActivityManager: Process com.android.bluetooth (pid 6498) has died
08-30 16:02:02.664  1036  2128 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-30 16:02:02.725  1036  2074 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7062 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 16:02:02.727  6356  6356 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:02:02.834  7062  7062 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 16:02:02.835  7062  7062 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:02:02.835  7062  7062 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 16:02:02.836  7062  7062 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 16:02:02.857  7062  7062 D BluetoothAdapterApp: Loading JNI Library
,08-30 16:02:02.897  7062  7062 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1185c4a6 Instance Count = 1
,08-30 16:02:03.062  1036  2056 I art     : Explicit concurrent mark sweep GC freed 35847(1672KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.430ms total 158.899ms
,08-30 16:02:03.065  7062  7062 D BluetoothAdapterApp: onCreate
08-30 16:02:03.085  7062  7062 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 16:02:03.085  7062  7062 D ProfileConfigQcom: Adding HeadsetService
08-30 16:02:03.085  7062  7062 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 16:02:03.085  7062  7062 D ProfileConfigQcom: Adding A2dpService
08-30 16:02:03.085  7062  7062 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 16:02:03.086  7062  7062 D ProfileConfigQcom: Adding HidService
08-30 16:02:03.086  7062  7062 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 16:02:03.086  7062  7062 D ProfileConfigQcom: Adding HealthService
08-30 16:02:03.086  7062  7062 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 16:02:03.087  7062  7062 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 16:02:03.087  7062  7062 D ProfileConfigQcom: Adding PanService
08-30 16:02:03.088  7062  7062 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 16:02:03.088  7062  7062 D ProfileConfigQcom: Adding GattService
08-30 16:02:03.088  7062  7062 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 16:02:03.088  7062  7062 D ProfileConfigQcom: Adding BluetoothMapService
08-30 16:02:03.088  7062  7062 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 16:02:03.089  7062  7062 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:02:03.090  7062  7062 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:02:03.090  7062  7062 V BluetoothPbapReceiver: ***********state = 10
08-30 16:02:03.092  7062  7062 V LGMDMManagerInternal: Create singleton instance
08-30 16:02:03.161  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:02:03.168  6356  6356 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 16:02:03.172  1036  2075 I ActivityManager: Killing 6118:com.lge.bnr/1000 (adj 15): empty #17
08-30 16:02:03.260  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6118/cgroup.procs: No such file or directory
,08-30 16:02:03.275  6356  6356 D BluetoothPermissionRequest: onReceive
,08-30 16:02:03.278  6356  6356 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 16:02:03.278  6356  6356 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 16:02:03.281  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 16:02:03.289  7062  7062 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 16:02:03.293  7062  7062 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:03.297  7062  7062 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:02:03.297  7062  7062 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:02:03.298  7062  7062 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:02:03.299  7062  7062 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:03.299  7062  7062 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-30 16:02:03.306  6439  6439 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 16:02:04.526  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:02:04.526  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:02:05.556  1036  1494 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-30 16:02:05.890  6916  6941 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 16:02:06.799  1036  2129 I ActivityManager: Killing 6374:com.lge.sync/1000 (adj 15): empty #17
,08-30 16:02:06.830  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6374/cgroup.procs: No such file or directory
,08-30 16:02:07.542  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:07.542  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@300ff892 added. We now have 6 listener(s)
08-30 16:02:07.542  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:02:07.554  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:07.554  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27758263 added. We now have 7 listener(s)
08-30 16:02:07.554  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:07.555  6240  6318 I System.out: IsBluetoothEnabled
08-30 16:02:07.556  1036  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:07.556  1036  1959 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 16:02:07.559  1036  1097 D BluetoothManagerService: Message: 2
,08-30 16:02:07.563  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:07.563  1036  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:07.563  1036  2028 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 16:02:07.580  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:02:07.580  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:02:07.580  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:02:07.581  1036  1097 D BluetoothManagerService: Message: 1
08-30 16:02:07.581  1036  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 16:02:07.607  1036  1097 D BluetoothManagerService: Message: 20
08-30 16:02:07.607  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1859563b:true
,08-30 16:02:07.611  7062  7062 D BluetoothAdapterState: make
08-30 16:02:07.616  7062  7062 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 16:02:07.616  7062  7062 I bluedroid-qcom: init
08-30 16:02:07.617  7062  7095 I BluetoothAdapterState: Entering OffState
08-30 16:02:07.618  7062  7062 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 16:02:07.618  7062  7062 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 16:02:07.618  7062  7062 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:02:07.618  7062  7062 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:02:07.618  7062  7062 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 16:02:07.620  7062  7062 I bluedroid-qcom: get_profile_interface socket
08-30 16:02:07.620  7062  7062 I bluedroid-qcom: get_profile_interface map_client
,08-30 16:02:07.625  7062  7099 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 16:02:07.627  7062  7099 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 16:02:07.615  7098  7098 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:07.615  7098  7098 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:07.639  7098  7098 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 16:02:07.639  7098  7098 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 16:02:07.639  7098  7098 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 16:02:07.642  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:02:07.642  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 16:02:07.644  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 16:02:07.645  1036  1097 D BluetoothManagerService: Message: 40
08-30 16:02:07.645  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 16:02:07.645  7062  7079 I bluedroid-qcom: config_hci_snoop_log
08-30 16:02:07.647  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 16:02:07.647  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 16:02:07.647  7098  7098 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 16:02:07.649  7062  7099 D BluetoothAdapterProperties: Name is: G3
08-30 16:02:07.654  7098  7098 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 16:02:07.654  7098  7098 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 16:02:07.660  7062  7095 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 16:02:07.660  7062  7095 D BluetoothAdapterProperties: Setting state to 11
08-30 16:02:07.660  7062  7095 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 16:02:07.661  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:02:07.661  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 16:02:07.661  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 16:02:07.663  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:07.664  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:02:07.668  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:02:07.672  6356  6356 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 16:02:07.679  7062  7062 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:02:07.679  7062  7062 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:07.679  7062  7062 V BluetoothPbapReceiver: ***********state = 11
08-30 16:02:07.683  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:02:07.696  7062  7095 I LGBluetoothServiceJni: classInitNative: succeeds
,08-30 16:02:07.719  7062  7095 D BluetoothBondStateMachine: make
,08-30 16:02:07.722  7062  7095 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:07.722  7062  7095 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 16:02:07.722  7062  7095 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:07.723  7062  7095 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 16:02:07.724  7062  7095 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 16:02:07.725  7062  7114 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 16:02:07.725  6356  6356 D BluetoothPermissionRequest: onReceive
08-30 16:02:07.729  7062  7095 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:02:07.729  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:02:07.741  7062  7062 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:02:07.744  7062  7095 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:02:07.745  7062  7062 D HeadsetService: Received start request. Starting profile...
08-30 16:02:07.746  7062  7062 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:02:07.746  7062  7062 D LGBluetoothHfpAdapter: Version 1.6
08-30 16:02:07.749  7062  7062 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:02:07.751  7062  7062 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:02:07.751  7062  7062 D HeadsetStateMachine: make
08-30 16:02:07.766  7062  7095 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:02:07.774  7062  7095 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:02:07.779  7062  7095 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:02:07.786  7062  7095 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 16:02:07.791  7062  7062 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:02:07.791  7062  7062 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 16:02:07.793  7062  7095 E BluetoothAdapterService: File transfer profiles supported!!
08-30 16:02:07.798  7062  7062 D HeadsetStateMachine: max_hf_connections = 1
08-30 16:02:07.798  7062  7062 I bluedroid-qcom: get_profile_interface handsfree
,08-30 16:02:07.800  7062  7062 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 16:02:07.801   322  1398 V AudioPolicyService: registerClient() client 0xb04107c0, uid 1002
08-30 16:02:07.802   322   322 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:02:07.802   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:02:07.802   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:02:07.802  7062  7062 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 16:02:07.802   322  3923 V AudioFlinger: registerClient() client 0xb55817a8, pid 7062
08-30 16:02:07.803   322  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:02:07.803   322  1393 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:02:07.803   322  1394 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:02:07.803   322  1394 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:02:07.804  7062  7078 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:02:07.804  7062  7078 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 16:02:07.805  7062  7079 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:02:07.805  7062  7079 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 16:02:07.805  1036  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:02:07.805  1036  2094 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:02:07.805  1036  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:02:07.805  1036  2094 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:02:07.805  3343  3358 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:02:07.805  1602  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:02:07.805  3343  3358 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:02:07.805  1602  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:02:07.806  3343  3358 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:02:07.806  3343  3358 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:02:07.806  1602  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:02:07.806  1602  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:02:07.806  1877  4372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 16:02:07.806  1877  4372 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 16:02:07.806  1877  4372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 16:02:07.806  1877  4372 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 16:02:07.806  7062  7062 V ToneGenerator: Create Track: 0xb4928080
08-30 16:02:07.806  7062  7062 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 16:02:07.806  7062  7062 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 16:02:07.806   322  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:02:07.806   322  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 16:02:07.806   322  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:02:07.806   322  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:02:07.807   322   322 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 16:02:07.807   322  3923 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 16:02:07.807   322  3923 V AudioPolicyManager: ,getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 16:02:07.807   322  3923 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 16:02:07.807   322  3923 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 16:02:07.807  7062  7095 V LGMDMManager: Create singleton instance
08-30 16:02:07.807  7062  7062 V AudioSystem: getLatency() output 2, latency 50
08-30 16:02:07.807  7062  7062 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 16:02:07.807  7062  7062 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 16:02:07.808   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:02:07.808   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:02:07.808   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 16:02:07.808   322  1399 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 16:02:07.808   322  1399 V AudioFlinger: createTrack() lSessionId: 23
08-30 16:02:07.809  7062  7095 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 16:02:07.809  7062  7062 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 16:02:07.810   322  1398 V AudioFlinger: acquiring 23 from 7062, for 7062
08-30 16:02:07.810   322  1398 V AudioFlinger:  added new entry for 23
08-30 16:02:07.810  7062  7062 V ToneGenerator: ToneGenerator INIT OK, time: 207477
08-30 16:02:07.810  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:07.810  7062  7118 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 16:02:07.811  7062  7118 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 16:02:07.811  7062  7118 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 16:02:07.811  7062  7118 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 16:02:07.811   322   322 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7062
,08-30 16:02:07.812   322   322 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 16:02:07.812   322   322 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 16:02:07.812   322   322 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 16:02:07.812   322   322 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 16:02:07.812   322   322 V voice   : voice_set_parameters: exit with code(0)
08-30 16:02:07.813   322   322 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 16:02:07.813   322   322 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 16:02:07.813  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:07.813   322   322 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 16:02:07.813   322   322 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 16:02:07.813   322   322 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 16:02:07.813   322   322 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 16:02:07.813  7062  7062 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:02:07.813  7062  7062 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:02:07.813  7062  7062 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:02:07.813  7062  7062 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:07.813  7062  7062 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 16:02:07.814  7062  7118 V ToneGenerator: ToneGenerator destructor
08-30 16:02:07.814  7062  7118 V ToneGenerator: stopTone
08-30 16:02:07.814  7062  7118 V ToneGenerator: Delete Track: 0xb4928080
08-30 16:02:07.815  7062  7118 V AudioTrack: ~AudioTrack, releasing session id from 7062 on behalf of 7062
08-30 16:02:07.816   322  3923 V AudioFlinger: releasing 23 from 7062 for 7062
08-30 16:02:07.816   322  3923 V AudioFlinger:  decremented refcount to 0
08-30 16:02:07.816   322  3923 V AudioFlinger: purging stale effects
08-30 16:02:07.816   322  3923 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 16:02:07.816   322  3923 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 16:02:07.816   322  3923 V AudioFlinger: PlaybackThread::Track destructor
08-30 16:02:07.816   322  1259 V AudioPolicyService: AudioCommandThread() waking up
08-30 16:02:07.816   322  3923 V AudioFlinger: removeClient_l() pid 7062, calling pid 322
08-30 16:02:07.816   322  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 16:02:07.816   322  1259 V AudioPolicyManager: releaseOutput() 2
08-30 16:02:07.816  7062  7062 D A2dpService: Received start request. Starting profile...
08-30 16:02:07.816   322  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 16:02:07.817  7062  7062 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:02:07.818  7062  7062 V Avrcp   : make
08-30 16:02:07.818  7062  7062 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 16:02:07.818  7062  7062 I bluedroid-qcom: get_profile_interface avrcp
08-30 16:02:07.828  7062  7062 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 16:02:07.829  7062  7062 E AudioManager: No RCC entry present to update
08-30 16:02:07.830  7062  7062 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 16:02:07.833  7062  7062 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 16:02:07.834  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 16:02:07.834  7062  7062 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 16:02:07.839  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 16:02:07.998  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:02:07.998  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:02:08.125  1036  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 16:02:08.140  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 16:02:08.146  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 16:02:08.147  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:02:08.148  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 16:02:08.148  7062  7062 I BluetoothA2dpServiceJni: classInitNative
08-30 16:02:08.148  7062  7062 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:02:08.148  7062  7062 D A2dpStateMachine: make
08-30 16:02:08.151  7062  7062 I bluedroid-qcom: get_profile_interface a2dp
08-30 16:02:08.151  7062  7130 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 16:02:08.154  7062  7062 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:02:08.154  7062  7062 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 16:02:08.155  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.156  7062  7062 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 16:02:08.156  7062  7129 D A2dpStateMachine: Enter Disconnected: -2
08-30 16:02:08.158  7062  7062 D HidService: Received start request. Starting profile...
08-30 16:02:08.158  7062  7062 I bluedroid-qcom: get_profile_interface hidhost
08-30 16:02:08.158  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.159  7062  7062 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:02:08.161  7062  7062 D HealthService: Received start request. Starting profile...
,08-30 16:02:08.162  7062  7062 I bluedroid-qcom: get_profile_interface health
08-30 16:02:08.164  7062  7062 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:02:08.164  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.165  7062  7062 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 16:02:08.166  7062  7062 D PanService: Received start request. Starting profile...
08-30 16:02:08.166  7062  7062 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:02:08.166  7062  7062 I bluedroid-qcom: get_profile_interface pan
08-30 16:02:08.176  7062  7062 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 16:02:08.176  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.179  7062  7062 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 16:02:08.194  7062  7062 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:02:08.194  7062  7062 D BtGatt.GattService: Received start request. Starting profile...
08-30 16:02:08.194  7062  7062 D BtGatt.GattService: start()
08-30 16:02:08.194  7062  7062 I bluedroid-qcom: get_profile_interface gatt
08-30 16:02:08.195  7062  7062 D BtGatt.AdvertiseManager: advertise manager created
08-30 16:02:08.200  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.201  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.202  7062  7062 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 16:02:08.203  7062  7062 V BluetoothMapService: BluetoothMapBinder()
08-30 16:02:08.203  7062  7062 D BluetoothMapService: Received start request. Starting profile...
08-30 16:02:08.203  7062  7062 D BluetoothMapService: start()
08-30 16:02:08.206  7062  7062 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-30 16:02:08.206  7062  7062 D BluetoothMapEmailAppObserver: createReceiver()
08-30 16:02:08.207  7062  7062 D BluetoothMapEmailAppObserver: initObservers()
08-30 16:02:08.207  7062  7062 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 16:02:08.216  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.216  7062  7062 D HeadsetStateMachine: Proxy object connected
08-30 16:02:08.217  7062  7062 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 16:02:08.217  7062  7062 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 16:02:08.220  7062  7118 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 16:02:08.220  7062  7118 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:02:08.221  7062  7118 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-30 16:02:08.224  7062  7062 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 16:02:08.226  7062  7062 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:02:08.228  7062  7062 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:02:08.230  7062  7062 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 16:02:08.230  7062  7062 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 16:02:08.232  7062  7062 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 16:02:08.237  7062  7062 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 16:02:08.237  7062  7062 V BluetoothMapService: Handler(): got msg=1
08-30 16:02:08.238  7062  7095 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 16:02:08.238  7062  7095 I bluedroid-qcom: enable
08-30 16:02:08.238  7062  7137 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 16:02:08.238  7062  7137 I bt-btu  : btu_task pending for preload complete event
08-30 16:02:08.238  7062  7095 I bt_hci_bdroid: init
08-30 16:02:08.240  7062  7095 I bt_vendor: bt-vendor : init
08-30 16:02:08.240  7062  7095 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 16:02:08.240  7062  7095 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 16:02:08.240  7062  7095 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 16:02:08.240  7062  7095 D bt_userial_mct: userial_init
08-30 16:02:08.240  7062  7095 D bt_hci_bdroid: set_power 1
08-30 16:02:08.240  7062  7095 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 16:02:08.240  7062  7095 I bt_vendor: Starting hciattach daemon
08-30 16:02:08.240  7062  7095 I bt_vendor: try to set true
08-30 16:02:08.235  7140  7140 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:08.235  7140  7140 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:08.268  7141  7141 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 16:02:08.333  7147  7147 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 16:02:08.355  7148  7148 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 16:02:08.378  7150  7150 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 16:02:08.389  7151  7151 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 16:02:08.400  7152  7152 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 16:02:08.413  7153  7153 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 16:02:08.438  7155  7155 I libmdmdetect: ESOC framework not supported
,08-30 16:02:08.438  7155  7155 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 16:02:08.447  7155  7155 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 16:02:08.447  7155  7155 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 16:02:08.447  7155  7155 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-30 16:02:08.447  7155  7155 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 16:02:08.447  7155  7155 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 16:02:08.447  7155  7155 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 16:02:08.447  7155  7155 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings,
08-30 16:02:08.487  7155  7156 E QC-QMI  : qmi_client [7155] 15: failed to locate client data
08-30 16:02:08.488   456   456 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-30 16:02:08.489   456   456 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 16:02:08.521  7157  7157 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 16:02:08.536  7158  7158 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 16:02:08.595  7062  7095 I bt_vendor: bluetooth satus is on
08-30 16:02:08.595  7062  7095 D bt_hci_bdroid: preload
,08-30 16:02:08.596  7062  7139 D bt_userial_mct: userial_open(port:0)
08-30 16:02:08.596  7062  7139 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 16:02:08.601  7062  7139 I bt_vendor: Done intiailizing UART
08-30 16:02:08.605  7062  7139 I bt_vendor: Done intiailizing UART
08-30 16:02:08.605  7062  7139 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 16:02:08.606  7062  7139 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 16:02:08.606  7062  7160 D bt_userial_mct: Entering userial_read_thread()
08-30 16:02:08.607  7062  7137 I bt-btu  : btu_task received preload complete event
08-30 16:02:08.608  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 16:02:08.609  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-30 16:02:08.617  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:02:08.623  7062  7137 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:02:08.624  7062  7137 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:02:08.693  7062  7137 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 16:02:08.693  7062  7137 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0214061 
08-30 16:02:08.693  7062  7137 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0214061 
,08-30 16:02:08.710  7062  7099 E bt-btif : Calling BTA_HhEnable
08-30 16:02:08.710  7062  7099 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 16:02:08.710  7062  7099 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 16:02:08.715  7062  7099 D BluetoothAdapterProperties: Name is: G3
08-30 16:02:08.717  7062  7099 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:02:08.718  7062  7099 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:02:08.719  7062  7099 D bt_hci_bdroid: postload
08-30 16:02:08.720  7062  7099 D bte_conf: Device ID record 1 : primary
08-30 16:02:08.720  7062  7099 D bte_conf:   vendorId            = 00c4
08-30 16:02:08.720  7062  7099 D bte_conf:   vendorIdSource      = 0001
08-30 16:02:08.720  7062  7099 D bte_conf:   product             = 13a1
08-30 16:02:08.720  7062  7099 D bte_conf:   version             = 1000
08-30 16:02:08.720  7062  7099 D bte_conf:   clientExecutableURL = 
08-30 16:02:08.720  7062  7099 D bte_conf:   serviceDescription  = 
08-30 16:02:08.720  7062  7099 D bte_conf:   documentationURL    = 
08-30 16:02:08.721  7062  7139 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 16:02:08.721  7062  7099 D bte_conf: bte_load_did_conf no section named DID2.
08-30 16:02:08.722  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 16:02:08.724  7062  7139 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 16:02:08.715  7165  7165 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:08.732  7062  7095 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 16:02:08.732  7062  7095 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:02:08.732  7062  7095 D BluetoothAdapterProperties: State =  11
08-30 16:02:08.732  7062  7095 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 16:02:08.734  7062  7095 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 16:02:08.734  7062  7095 D BluetoothAdapterProperties: Setting state to 12
08-30 16:02:08.734  7062  7095 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 16:02:08.735  1036  1097 D BluetoothManagerService: Message: 60
08-30 16:02:08.735  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 16:02:08.735  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 16:02:08.737  7062  7095 I BluetoothAdapterState: Entering On State
,08-30 16:02:08.725  7165  7165 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:08.743  7062  7160 E bt_mct  : hci lib postload completed
08-30 16:02:08.744  7062  7099 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:02:08.761  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:02:08.769  7062  7099 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:02:08.769  7062  7099 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 16:02:08.770  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 16:02:08.773  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:02:08.775  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 16:02:08.775  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 16:02:08.776  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-30 16:02:08.777  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 16:02:08.777  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 16:02:08.777  7062  7137 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 16:02:08.778  7062  7099 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:02:08.786  7062  7095 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 16:02:08.786  7062  7095 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 16:02:08.786  7062  7095 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 16:02:08.791  7062  7095 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 16:02:08.791  7062  7095 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-30 16:02:08.794  6356  6373 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:02:08.804  7062  7137 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:02:08.804  7062  7137 W bt-smp  : Plain text(LSB ~ MSB) = 3b 6f 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:02:08.804  7062  7137 W bt-smp  : Encrypted text(LSB ~ MSB) = 0e 14 9b 29 81 bf 72 78 e8 3b 12 78 65 2b 93 8a 
,08-30 16:02:08.806  7062  7137 W bt-btm  : Stopping oneshot timer
08-30 16:02:08.807  6356  6372 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:02:08.818  6356  6373 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:02:08.830  6356  6356 D BluetoothInputDevice: Proxy object connected
08-30 16:02:08.830  6356  6356 D HidProfile: Bluetooth service connected
08-30 16:02:08.841  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:02:08.845  1036  1036 D BluetoothHeadset: Proxy object connected
08-30 16:02:08.847  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:02:08.848  1036  1036 D BluetoothA2dp: Proxy object connected
08-30 16:02:08.850  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:02:08.852  1877  1877 D BluetoothHeadset: Proxy object connected
08-30 16:02:08.854  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:02:08.856  7062  7137 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:02:08.856  7062  7137 W bt-smp  : Plain text(LSB ~ MSB) = c6 4a 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:02:08.856  7062  7137 W bt-smp  : Encrypted text(LSB ~ MSB) = 23 e3 14 d2 63 da d6 e7 7c 30 50 d5 8a 98 82 0d 
08-30 16:02:08.856  7062  7137 W bt-btm  : Stopping oneshot timer
08-30 16:02:08.857  6356  6356 D BluetoothHeadset: Proxy object connected
08-30 16:02:08.857  6356  6356 D HeadsetProfile: Bluetooth service connected
08-30 16:02:08.861  1877  1877 D BluetoothHeadset: Proxy object connected
08-30 16:02:08.862  1877  2862 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:02:08.868  1877  1877 D BluetoothHeadset: Proxy object connected
,08-30 16:02:08.868  6356  6373 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:02:08.871  6356  7168 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:02:08.872  6356  6356 D BluetoothA2dp: Proxy object connected
08-30 16:02:08.872  6356  6356 D A2dpProfile: Bluetooth service connected
08-30 16:02:08.876  6356  6372 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:02:08.876  6356  6372 D BluetoothPan: onBluetoothStateChange call bindService
08-30 16:02:08.876  6356  6356 D BluetoothMap: Proxy object connected
08-30 16:02:08.876  6356  6356 D MapProfile: Bluetooth service connected
08-30 16:02:08.876  6356  6356 D BluetoothMap: getConnectedDevices()
08-30 16:02:08.877  7062  7078 V BluetoothMapService: getConnectedDevices()
08-30 16:02:08.879  6356  6356 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 16:02:08.879  6356  6356 D PanProfile: Bluetooth service connected
08-30 16:02:08.880  7062  7137 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:02:08.880  7062  7137 W bt-smp  : Plain text(LSB ~ MSB) = d5 02 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:02:08.880  7062  7137 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 5b 15 36 ba b7 bf af b2 bb 4a 05 a9 b2 67 ab 
08-30 16:02:08.880  7062  7137 W bt-btm  : Stopping oneshot timer
08-30 16:02:08.880  1036  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 16:02:08.880  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 16:02:08.883  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 16:02:08.885  7188  7188 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 16:02:08.888  1984  1984 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:08.888  1984  2179 D LGBluetoothAPIService: Message: 1
08-30 16:02:08.888  1984  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 16:02:08.889  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 16:02:08.890  1036  1097 D BluetoothManagerService: Message: 40
08-30 16:02:08.890  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 16:02:08.890  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:08.894  7062  7137 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:02:08.894  7062  7137 W bt-smp  : Plain text(LSB ~ MSB) = 24 d5 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:02:08.894  7062  7137 W bt-smp  : Encrypted text(LSB ~ MSB) = d9 66 93 6e 58 bc 1e c7 e7 13 0b c7 30 35 73 eb 
08-30 16:02:08.894  7062  7137 W bt-btm  : Stopping oneshot timer
,08-30 16:02:08.895  1984  2179 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 16:02:08.899  7062  7062 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:08.899  7062  7062 D BluetoothMapService: STATE_ON
08-30 16:02:08.901  7062  7062 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 16:02:08.901  7062  7062 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 16:02:08.902  7062  7062 V BluetoothMapService: Handler(): got msg=1
08-30 16:02:08.902  1984  1984 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 16:02:08.902  1984  2179 D LGBluetoothAPIService: Message: 100
08-30 16:02:08.902  1984  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 16:02:08.903  7062  7062 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 16:02:08.904  7062  7193 D BluetoothMapMasInstance: MAS initSocket()
08-30 16:02:08.904  7062  7137 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 16:02:08.904  7062  7137 W bt-smp  : Plain text(LSB ~ MSB) = 34 01 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 16:02:08.904  7062  7137 W bt-smp  : Encrypted text(LSB ~ MSB) = e6 2a 42 49 97 16 2e bb df 60 4d 05 25 64 62 03 
08-30 16:02:08.905  7062  7137 W bt-btm  : Stopping oneshot timer
08-30 16:02:08.905  6356  6356 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 16:02:08.905  7062  7193 D BluetoothMapMasInstance:   masId = 00
08-30 16:02:08.905  7062  7193 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 16:02:08.905  7062  7193 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 16:02:08.905  7062  7193 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 16:02:08.906  6356  6356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 16:02:08.906  1036  1711 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:08.908  7062  7193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:02:08.910  7062  7193 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 16:02:08.911  7062  7193 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 16:02:08.911  7062  7193 D BluetoothMapMasInstance: Accepting socket connection...
08-30 16:02:08.915  7062  7099 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:02:08.915  7062  7099 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 16:02:08.920  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:08.922  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:08.922  7062  7062 V BluetoothPbapService: Pbap Service onCreate
08-30 16:02:08.922  7062  7062 V BluetoothPbapService: Starting PBAP service
08-30 16:02:08.922  6356  6356 D DockEventReceiver: finishStartingService: stopping service
08-30 16:02:08.924  7062  7062 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-30 16:02:08.924  7062  7062 V BluetoothPbapService: Pbap Service onBind
08-30 16:02:08.926  6356  6356 D BluetoothPbap: Proxy object connected
08-30 16:02:08.926  6356  6356 D PbapServerProfile: Bluetooth service connected
08-30 16:02:08.926  7062  7062 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:08.926  7062  7062 V BluetoothPbapService: state: 12
08-30 16:02:08.927  7062  7062 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 16:02:08.927  7062  7062 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:08.927  7062  7062 V BluetoothPbapReceiver: ***********state = 12
,08-30 16:02:08.929  7062  7062 V BluetoothPbapService: Handler(): got msg=1
08-30 16:02:08.929  7062  7062 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 16:02:08.931  7062  7195 V BluetoothPbapService: Pbap Service initSocket
08-30 16:02:08.931  2286  2286 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:02:08.931  1036  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:08.931  2286  2286 D c       : Getting all permits...
08-30 16:02:08.932  2286  2286 D a       : Opening database...
08-30 16:02:08.932  7062  7195 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:02:08.933  7062  7195 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 16:02:08.933  7062  7195 V BluetoothPbapService: Succeed to create listening socket 
08-30 16:02:08.933  7062  7195 V BluetoothPbapService: Accepting socket connection...
08-30 16:02:08.936  2286  2286 D a       : Opening database auth.proximity.permit_store...
08-30 16:02:08.937  2286  2286 D a       : Closing database...
08-30 16:02:08.947  6356  6356 D BluetoothPermissionRequest: onReceive
,08-30 16:02:08.949  6356  6356 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 16:02:08.951  6356  6356 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 16:02:08.955  7062  7062 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 16:02:08.957  7062  7062 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 16:02:08.966  7062  7062 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 16:02:09.003  7062  7062 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 16:02:09.004  7062  7062 V BtOppService: onCreate
,08-30 16:02:09.009  7062  7062 V BluetoothOppNotification: send message
,08-30 16:02:09.014  7062  7062 V BtOppService: Starting RfcommListener
08-30 16:02:09.022  7062  7062 D BluetoothOppPreference: Dumping Names:  
08-30 16:02:09.022  7062  7062 D BluetoothOppPreference: {}
08-30 16:02:09.022  7062  7062 D BluetoothOppPreference: Dumping Channels:  
08-30 16:02:09.022  7062  7062 D BluetoothOppPreference: {}
,08-30 16:02:09.023  7062  7062 V BtOppService: onStartCommand
08-30 16:02:09.031  7062  7201 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 16:02:09.031  7062  7062 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:09.031  7062  7062 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 16:02:09.035  7062  7201 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:02:09.037  7062  7062 V BluetoothOppNotification: new notify threadi!
08-30 16:02:09.038  7062  7062 V BluetoothOppNotification: send delay message
,08-30 16:02:09.039  7062  7062 V BtOppService: start RfcommListener
08-30 16:02:09.043  7062  7202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 16:02:09.044  7062  7198 V BtOppService: Deleted complete outbound shares, number =  0
08-30 16:02:09.045  7062  7201 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33314ccb on behalf of 
08-30 16:02:09.049  7062  7062 V BtOppService: RfcommListener started
08-30 16:02:09.049  7062  7198 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 16:02:09.049  7062  7198 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 16:02:09.050  7062  7203 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 16:02:09.051  7062  7202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@165bca8 on behalf of 
08-30 16:02:09.051  7062  7198 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29bcb3c1 on behalf of 
08-30 16:02:09.051  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:09.052  7062  7201 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 16:02:09.053  7062  7202 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 16:02:09.054  7062  7203 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:02:09.056  7062  7203 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 16:02:09.057  7062  7202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 16:02:09.057  7062  7203 V BtOppRfcommListener: Started RFCOMM listener....
08-30 16:02:09.058  7062  7203 I BtOppRfcommListener: Accept thread started.
08-30 16:02:09.058  7062  7203 V BtOppRfcommListener: Accepting connection...
08-30 16:02:09.059  7062  7202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c638766 on behalf of 
08-30 16:02:09.060  7062  7202 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 16:02:09.062  7062  7202 V BluetoothOppNotification: outbound notification was removed.
08-30 16:02:09.062  7062  7202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 16:02:09.063  7062  7202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3885eaa7 on behalf of 
08-30 16:02:09.064  7062  7202 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 16:02:09.065  7062  7202 V BluetoothOppNotification: inbound notification was removed.
08-30 16:02:09.065  7062  7202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 16:02:09.067  7062  7202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2adfb54 on behalf of 
,08-30 16:02:09.071  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
08-30 16:02:09.071  7062  7062 V BluetoothFtpService: Ftp Service onCreate
08-30 16:02:09.071  7062  7062 I BluetoothFtpService: Ftp Service onCreate
08-30 16:02:09.072  7062  7062 V BluetoothFtpService: Ftp Service onStartCommand
08-30 16:02:09.072  7062  7062 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:09.072  7062  7062 V BluetoothFtpService: Starting Listening on sockets
08-30 16:02:09.072  7062  7062 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 16:02:09.072  7062  7062 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 16:02:09.072  7062  7062 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 16:02:09.072  7062  7062 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:09.073  7062  7062 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 16:02:09.073  7062  7062 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 16:02:09.075  7062  7062 V BtOppService: ContentObserver received notification
08-30 16:02:09.075  7062  7062 V BtOppService: ContentObserver received notification
08-30 16:02:09.075  7062  7062 V BluetoothFtpService: Handler(): got msg=1
08-30 16:02:09.076  7062  7062 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 16:02:09.076  7062  7062 V BluetoothFtpService: Ftp Service initSocket
08-30 16:02:09.078  7062  7204 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 16:02:09.079  7062  7204 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 16:02:09.081  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:09.081  7062  7204 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@990b3f2 on behalf of 
08-30 16:02:09.081  7062  7204 V BluetoothOppNotification: update too frequent, put in queue
08-30 16:02:09.082  7062  7204 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 16:02:09.083  7062  7062 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:02:09.085  7062  7062 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-30 16:02:09.085  7062  7062 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 16:02:09.087  7062  7205 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-30 16:02:09.101  7062  7062 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12f6c27e
,08-30 16:02:09.102  7062  7062 V BluetoothSapService: Sap Service onCreate
08-30 16:02:09.104  7062  7062 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:02:09.104  7062  7062 V BluetoothSapService: state: 12
08-30 16:02:09.104  7062  7062 V BluetoothSapService: Starting SAP server process
,08-30 16:02:09.107  7062  7062 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-30 16:02:09.095  7206  7206 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:09.095  7206  7206 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:09.109  7062  7207 V BluetoothSapService: Sap Service initRfcommSocket
08-30 16:02:09.110  1036  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:09.110  7062  7207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:02:09.112  7062  7207 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 16:02:09.112  7062  7207 V BluetoothSapService: Succeed to create listening socket 
08-30 16:02:09.112  7062  7207 V BluetoothSapService: Accepting socket connection...
08-30 16:02:09.134  7206  7206 V BT_SAP  : Event pipe created
08-30 16:02:09.134  7206  7206 V BT_SAP  : create_server_socket qcom.sap.server
08-30 16:02:09.135  7206  7206 V BT_SAP  : created socket fd 6
,08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:02:09.614  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:02:09.631  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:02:09.637  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:09.637  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1654de60 added. We now have 8 listener(s)
08-30 16:02:09.637  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:09.640  1036  2056 D WifiServiceImplEx: setWifiEnabled: false pid=6240, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:02:09.641  1036  2056 D WifiService: setWifiEnabled: false pid=6240, uid=10118
08-30 16:02:09.641  1036  2056 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:02:09.646  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:02:09.650  1036  2075 D WifiServiceImplEx: setWifiEnabled: true pid=6240, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 16:02:09.651  1036  2075 D WifiService: setWifiEnabled: true pid=6240, uid=10118
08-30 16:02:09.651  1036  2075 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:02:09.671  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 16:02:09.671  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 16:02:09.671  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 16:02:09.673  1036  1438 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 16:02:09.673  1036  1438 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 16:02:09.676  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 16:02:09.676  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 16:02:09.676  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 16:02:09.676  1036  1438 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 16:02:09.676  1036  1438 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 16:02:09.676  1036  1438 E WifiHW  : unknown target_country: EU , set to default
08-30 16:02:09.676  1036  1438 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 16:02:09.676  1036  1438 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 16:02:09.676  1036  1438 I WifiUtil: gEnableBmps=1
08-30 16:02:10.041  7062  7062 V BluetoothOppNotification: new notify threadi!
08-30 16:02:10.041  7062  7062 V BluetoothOppNotification: send delay message
,08-30 16:02:10.079  7062  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 16:02:10.087  7062  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35f21d3e on behalf of 
08-30 16:02:10.088  7062  7220 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 16:02:10.105  7062  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 16:02:10.109  7062  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18f3879f on behalf of 
08-30 16:02:10.110  7062  7220 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 16:02:10.111  7062  7220 V BluetoothOppNotification: outbound notification was removed.
08-30 16:02:10.112  7062  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 16:02:10.113  7062  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16fd60ec on behalf of 
08-30 16:02:10.114  7062  7220 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 16:02:10.115  7062  7220 V BluetoothOppNotification: inbound notification was removed.
08-30 16:02:10.115  7062  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 16:02:10.116  7062  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff25cb5 on behalf of 
08-30 16:02:10.281   318   906 D SoftapController: Softap fwReload - Ok
,08-30 16:02:10.286  1036  1438 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (607ms)
08-30 16:02:10.303  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:02:10.304  1036  1097 D Tethering: InitialState.processMessage what=4
08-30 16:02:10.304  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 16:02:10.314   318   906 D CommandListener: Setting iface cfg
08-30 16:02:10.314   318   906 D CommandListener: Trying to bring down wlan0
08-30 16:02:10.320   318   906 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:02:10.324  1036  1438 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 16:02:10.344  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:02:10.344  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:02:10.344  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 16:02:10.335  7228  7228 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:10.335  7228  7228 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:10.356  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 16:02:10.366  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 16:02:10.409  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:02:10.415  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:02:10.415  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:02:10.415  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:02:10.415  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:02:10.416  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:02:10.418  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:02:10.418  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:02:10.418  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:02:10.419  7228  7228 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 16:02:10.419  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:02:10.419  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:02:10.419  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:02:10.423  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 16:02:10.423  1036  1438 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 16:02:10.423  1036  1438 D WifiMonitor: connecting to supplicant
08-30 16:02:10.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:02:10.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:02:10.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:02:10.426  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:02:10.429  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:02:10.431  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:02:10.431  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 16:02:10.431  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:02:10.431  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:02:10.431  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:02:10.432  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:02:10.464  7228  7228 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 16:02:10.464  7228  7228 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 16:02:10.490  1036  2075 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7249 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 16:02:10.495  6459  7247 W FormManager: Network not available. Please check & try again.
08-30 16:02:10.499  6459  7248 V FormManager: Network unavailable.
08-30 16:02:10.501  6459  7248 V FormManager: Network unavailable.
,08-30 16:02:10.532  7228  7228 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 16:02:10.584  7249  7249 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 16:02:10.587  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:02:10.591  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:10.596  7228  7228 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 16:02:10.600  7228  7228 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-30 16:02:10.602  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 16:02:10.603  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 16:02:10.603  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:02:10.603  1036  7269 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 16:02:10.603  1036  7269 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 16:02:10.604  1036  1438 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 16:02:10.604  1036  1438 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:10.605  1036  1438 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:10.605  7228  7228 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 16:02:10.605  1036  1438 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 16:02:10.605  1036  1438 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 16:02:10.606  1036  1438 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 16:02:10.606  1036  1438 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 16:02:10.606  1036  1438 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 16:02:10.607  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:02:10.607  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 16:02:10.607  1036  1438 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 16:02:10.607  1036  1438 E WifiStateMachine: useWiFiOffloading() : false
08-30 16:02:10.607  1036  1438 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 16:02:10.607  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.607  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 16:02:10.607  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 16:02:10.607  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:02:10.607  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.607  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 16:02:10.607  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.607  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.608  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 16:02:10.608  1036  1438 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 16:02:10.609  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:10.610  1984  1984 D WfdService: Waiting for WifiP2p enabling
08-30 16:02:10.610  1036  1438 D WifiNative-wlan0: SET update_config 1: returned true
08-30 16:02:10.610  1036  1438 D WifiConfigStore: Loading config and enabling all networks 
08-30 16:02:10.610  1036  1438 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 16:02:10.611  1036  1438 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 16:02:10.611  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 16:02:10.612  1036  1467 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 16:02:10.613  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:02:10.613  6240  6240 V io.jxcore.node.,ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:10.613  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:10.613  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:02:10.613  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:10.613  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:02:10.613  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:02:10.613  6240  6240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:02:10.615  6240  6240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:02:10.619  7249  7249 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:02:10.624  1036  1438 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 16:02:10.626  6459  7271 W FormManager: Network not available. Please check & try again.
,08-30 16:02:10.630  6459  7272 V FormManager: Network unavailable.
08-30 16:02:10.630  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 16:02:10.632  1036  1438 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 16:02:10.632  1036  1438 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 16:02:10.633  1036  1438 D WifiStateMachine: enableVerboseLogging : level 2
08-30 16:02:10.633  1036  1438 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 16:02:10.633  1036  1438 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 16:02:10.633  1036  1438 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 16:02:10.634  1036  1438 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 16:02:10.634  1036  1438 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 16:02:10.634  6459  7272 V FormManager: Network unavailable.
08-30 16:02:10.634  1036  1438 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 16:02:10.634  1036  1438 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 16:02:10.634  1036  1438 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 16:02:10.634  1036  1438 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 16:02:10.635  1036  1438 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 16:02:10.635  1036  1438 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 16:02:10.635  1036  1438 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 16:02:10.635  1036  1438 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 16:02:10.635  1036  1438 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-30 16:02:10.637  1984  1984 D WfdsService: Supplicant Connection state is changed : true
08-30 16:02:10.637  1984  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 16:02:10.637  1036  1438 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:02:10.637  1984  2321 D WfdsService: Set the WFDS Monitor: true
08-30 16:02:10.637  1036  1438 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 16:02:10.637  1984  2321 D WfdsMonitor: WfdsMonitorThread create
08-30 16:02:10.637  1984  2321 D WfdsMonitor: WFDS Monitor is created and started
08-30 16:02:10.637  1984  2321 D WfdsService: WiFi: Supplicant connection re-established
08-30 16:02:10.637  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:10.638  1036  1438 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 16:02:10.638  1036  1438 D WifiNative-HAL: Setting external_sim to 1
08-30 16:02:10.638  1036  1438 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 16:02:10.638  1036  1438 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 16:02:10.638  1036  1438 I WifiNative-HAL: startHal
08-30 16:02:10.638  1036  1438 D wifi    : setting scan oui 0xaf660040
08-30 16:02:10.639  1984  7273 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 16:02:10.639  1036  1438 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:02:10.639  1036  1438 I WifiNative-HAL: startHal
08-30 16:02:10.639  1036  1438 D wifi    : setting scan oui 0xaf660040
08-30 16:02:10.639  1036  1438 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 16:02:10.640  1984  7273 E CtrlSupplicant: Succeed to open control connection
08-30 16:02:10.640  1036  1438 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 16:02:10.640  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 16:02:10.640  1984  7273 E CtrlSupplicant: Succeed to open monitor connection
08-30 16:02:10.640  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 16:02:10.640  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 16:02:10.641  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:02:10.641  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:02:10.641  1984  7273 D WfdsMonitor: Supplicant connection established
08-30 16:02:10.641  1984  2321 D WfdsService: Connected to the supplicant for wfds
08-30 16:02:10.641  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:02:10.641  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 16:02:10.641  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 16:02:10.642  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 16:02:10.642  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:02:10.642  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:02:10.642  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:02:10.642  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 16:02:10.642  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 16:02:10.642  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 16:02:10.642  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 16:02:10.642  7228  7228 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 16:02:10.643  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 16:02:10.643  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 16:02:10.643  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 16:02:10.643  1036  1438 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 16:02:10.644  1036  1438 E WifiNative: : [210,298,426 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 16:02:10.644  1036,  1438 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 16:02:10.645  1036  1438 D WifiNative-wlan0: RECONNECT: returned true
08-30 16:02:10.645  1036  1438 D WifiNative-wlan0: doString: [STATUS]
08-30 16:02:10.646  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:02:10.646  1036  1438 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:02:10.646  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:02:10.646  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 16:02:10.646  1036  1438 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:02:10.646  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:02:10.648   318   906 D CommandListener: Setting iface cfg
08-30 16:02:10.648   318   906 D CommandListener: Trying to bring up p2p0
08-30 16:02:10.648  1036  1392 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 16:02:10.648  1036  1392 D LGWifiP2pService: P2pEnablingState
08-30 16:02:10.648  1036  1392 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.649  1036  1392 D LGWifiP2pService: P2p socket connection successful
08-30 16:02:10.649  1036  1392 D LGWifiP2pService: P2pEnabledState
08-30 16:02:10.650  1036  1392 D LGWifiP2pService: sending p2p connection changed broadcast
,08-30 16:02:10.651  1984  1984 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 16:02:10.651  1984  1984 D WfdsService: WifiP2pState is changed : true
08-30 16:02:10.651  1984  2321 D WfdsService: Receive the WFDS_ENABLE Method
08-30 16:02:10.651  1984  2321 D WfdsService: Set the WFDS Monitor: true
08-30 16:02:10.651  1984  2321 D WfdsService: Connected to the supplicant for wfds
,08-30 16:02:10.651  1984  2321 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 16:02:10.651  7228  7228 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 16:02:10.651  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 16:02:10.652  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-30 16:02:10.652  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.652  1036  1557 I WifiNative-HAL: startHal
08-30 16:02:10.652  1984  2321 D WfdsService: selectPreferredScanChannel [36]
08-30 16:02:10.652  1984  2321 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 16:02:10.652  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf660040
08-30 16:02:10.652  1036  1557 D wifi    : failed to get capabilities : -3
08-30 16:02:10.652  1036  1557 E WifiScanningService: could not get scan capabilities
08-30 16:02:10.652  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.653  1036  1438 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 16:02:10.653  1036  1438 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 16:02:10.654  1036  1438 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 16:02:10.654  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:02:10.654  4272  4272 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 16:02:10.654  1036  1438 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 16:02:10.655  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=210309  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:02:10.656  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:02:10.657  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=210311  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:02:10.657  1036  1438 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 16:02:10.657  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:10.657  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:10.657  1036  1438 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 16:02:10.658  1036  1438 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 16:02:10.658  1036  1438 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 16:02:10.658  7228  7228 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 16:02:10.659  1036  1438 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 16:02:10.659  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:10.659  1036  1438 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 16:02:10.659  1036  1438 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 16:02:10.659  1036  1438 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 16:02:10.659  7228  7228 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 16:02:10.660  1036  1438 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 16:02:10.660  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.Syste,m to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.660  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.660  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 16:02:10.660  1036  1438 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 16:02:10.661  1036  1438 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 16:02:10.661  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 16:02:10.661  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-30 16:02:10.662  7228  7228 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.663  7228  7228 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:02:10.663  7228  7228 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.663  1036  1438 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 16:02:10.663  7228  7228 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.664  1036  1438 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:02:10.664  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:02:10.664  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.664  1036  1392 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 16:02:10.664  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.664  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.664  1036  1438 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:02:10.664  1036  7269 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.664  1036  7269 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.664  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.664  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.664  1036  7269 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.665  1036  7269 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.665  1036  1392 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 16:02:10.665  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.665  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.665  1036  1438 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 16:02:10.665  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 16:02:10.665  1036  1392 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 16:02:10.665  1984  7273 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.665  1984  7273 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.665  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 16:02:10.665  7228  7228 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:02:10.666  1036  1438 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 16:02:10.666  1984  1984 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 16:02:10.666  1036  1438 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 16:02:10.666  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 16:02:10.666  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:02:10.666  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:02:10.666  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 16:02:10.666  4272  4272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onR,eceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 16:02:10.666  1036  1392 D WifiNative-p2p0: SET device_name G3: returned true
08-30 16:02:10.666  1036  1392 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 16:02:10.667  1036  1438 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 16:02:10.667  1036  1438 D WifiNative-wlan0: doBoolean: SCAN
08-30 16:02:10.667  1984  1984 D WfdsService: isConnected: false
08-30 16:02:10.667  1036  1438 D WifiNative-wlan0: SCAN: returned false
08-30 16:02:10.667  1036  1392 D LGWifiP2pService: before postfix = G3
08-30 16:02:10.667  1036  1392 D WifiServerServiceExt: postfix byte check : 2
08-30 16:02:10.667  1036  1392 D LGWifiP2pService: after postfix = G3
08-30 16:02:10.667  1036  1392 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 16:02:10.667  1036  1392 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 16:02:10.667  1036  1392 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 16:02:10.668  1036  1392 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 16:02:10.668  1036  1392 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 16:02:10.668  1036  1392 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 16:02:10.668  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 16:02:10.668  1036  1392 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 16:02:10.668  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress
08-30 16:02:10.669  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 16:02:10.669  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=210324  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:02:10.671  4272  7274 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 16:02:10.671  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=210326  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 16:02:10.673  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.673  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:10.673  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-30 16:02:10.675  4272  7275 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 16:02:10.675  4272  7275 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 16:02:10.677  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:02:10.677  1036  1438 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:02:10.677  1036  1438 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:02:10.678  1036  1438 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:02:10.678  1036  1392 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 16:02:10.678  1036  1392 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 16:02:10.681  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:10.681  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-30 16:02:10.681  1984  1984 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 16:02:10.681  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:10.681  1984  1984 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 16:02:10.681  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:10.681  1984  1984 D WfdsService: Update P2p Interface State: 3
08-30 16:02:10.681  1036  1438 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:02:10.681  1036  1392 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 16:02:10.682  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 16:02:10.682  1036  1392 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 16:02:10.682  1036  1392 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 16:02:10.682  1036  1438 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 16:02:10.682  1036  1392 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 16:02:10.682  1036  1392 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 16:02:10.683  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:10.684  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:10.684  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 16:02:10.689  1036  1392 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 16:02:10.689  1036  1392 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:02:10.689  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:02:10.691  1036  1392 D LGWifiP2pService: InactiveState
,08-30 16:02:10.691  1036  1392 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.691  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.691  1036  1392 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 16:02:10.691  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-30 16:02:10.692  7228  7228 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.692  1036  7269 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:02:10.692  1036  7269 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.692  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.692  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 16:02:10.692  1984  7273 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 16:02:10.692  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:02:10.692  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:02:10.692  7228  7228 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 16:02:10.692  7228  7228 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.693  1984  7273 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.693  1036  7269 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.693  1036  7269 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.693  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.693  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.693  1036  1392 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.693  7228  7228 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.693  1036  1392 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.694  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.694  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.694  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.694  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.694  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:10.694  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal,.util.StateMachine$SmHandler }
08-30 16:02:10.694  1036  1036 E WifiServerServiceExt: No p2p device connected
08-30 16:02:10.694  1036  7269 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.694  1036  7269 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.694  1036  7269 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.694  1036  7269 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 16:02:10.695  1984  2321 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 16:02:10.695  1984  7273 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 16:02:10.698  6240  6318 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 16:02:10.698  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:10.699  6240  6318 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 16:02:10.702  6240  6318 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e799ee2 Bundle[{}]
,08-30 16:02:10.703  6240  6318 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:02:10.703  6240  6318 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 16:02:10.704  6240  6318 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 16:02:10.704  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:10.704  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:10.704  6240  6318 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 16:02:10.705  6240  6318 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 16:02:10.705  6240  6318 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 16:02:10.706  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:02:10.712  6240  6318 I System.out: Running OutgoingSocketThread
08-30 16:02:10.713  6240  7276 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 790)
08-30 16:02:10.714  6240  7276 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45887
08-30 16:02:10.714  6240  7276 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 16:02:10.742  1036  1576 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7277 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 16:02:10.839  7277  7277 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 16:02:10.840  7277  7277 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 16:02:10.849  7277  7277 V [BNRBootReceiver]: Boot Receiver Return
,08-30 16:02:10.849  7277  7277 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 16:02:10.855  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:02:10.867  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:02:10.873  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:10.883  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 16:02:10.883  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:02:10.885  6420  6420 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 16:02:10.887  1036  2075 I ActivityManager: Killing 6710:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 16:02:10.978  1036  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_6710/cgroup.procs: No such file or directory
,08-30 16:02:11.272  7228  7228 E wpa_supplicant: USIM:  scard_init function
,08-30 16:02:11.279  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 16:02:11.279  1036  7269 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 16:02:11.280  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 16:02:11.280  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-30 16:02:11.280  1036  7269 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 16:02:11.282  1036  1438 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 16:02:11.284  7228  7228 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 16:02:11.289  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 16:02:11.289  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-30 16:02:11.293  1036  1438 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 16:02:11.294  1036  1438 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 16:02:11.294  1036  1438 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 16:02:11.294  1036  1438 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 16:02:11.310  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=210964  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 16:02:11.316  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.316  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:11.318  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.322  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.322  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.322  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 16:02:11.325  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=210979  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 16:02:11.329  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:11.329  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 16:02:11.330  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 16:02:11.346  6356  6356 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 16:02:11.351  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:02:11.361  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:02:11.370  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:11.378  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.379  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.379  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 16:02:11.399  7228  7228 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 16:02:11.407  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 16:02:11.407  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 16:02:11.409  7228  7228 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:02:11.409  7228  7228 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:02:11.413  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 16:02:11.413  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 16:02:11.414  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:02:11.414  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:02:11.414  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:02:11.414  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:02:11.414  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 16:02:11.414  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:02:11.414  1036  7269 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:02:11.414  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 16:02:11.414  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:02:11.414  1036  7269 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 16:02:11.415  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:02:11.415  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:02:11.417  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=211071  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 16:02:11.418  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=211072  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 16:02:11.418  1036  1438 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211073
,08-30 16:02:11.424  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 16:02:11.433  1036  1438 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211088
,08-30 16:02:11.435  1036  1438 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211089
08-30 16:02:11.435  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211090
08-30 16:02:11.436  1036  1438 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211090
08-30 16:02:11.436  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=211091  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 16:02:11.440  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.441  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.441  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 16:02:11.446  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.446  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 16:02:11.454  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 16:02:11.454  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 16:02:11.454  6356  6356 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 16:02:11.454  6356  6356 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 16:02:11.457  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.460  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=211114  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 16:02:11.461  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.462  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.462  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-30 16:02:11.463  1036  1438 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=211117  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:02:11.464  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=211118  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 16:02:11.464  1036  1438 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=211119
08-30 16:02:11.465  1036  1438 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=211119
08-30 16:02:11.465  1036  1438 D WifiNative-wlan0: doString: [STATUS]
08-30 16:02:11.466  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.466  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:11.466  1036  1438 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 16:02:11.466  1036  7269 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 16:02:11.467  1036  7269 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 16:02:11.467  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 16:02:11.467  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.468  1036  1438 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 16:02:11.470  6356  6356 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 16:02:11.470  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 16:02:11.470  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 16:02:11.470  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 16:02:11.470  6356  6356 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 16:02:11.470  6356  6356 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 16:02:11.470  6356  6356 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 16:02:11.475  1036  1438 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 16:02:11.475  1036  1438 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 16:02:11.478  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.478  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.478  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 16:02:11.480  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:02:11.482  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.482  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.482  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 16:02:11.488  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 16:02:11.488  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:11.489  1036  1438 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 16:02:11.489  1036  1438 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:02:11.489  1036  1438 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:02:11.490  1036  1494 D ConnectivityService: Got NetworkAgent Messenger
08-30 16:02:11.490  1036  1494 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 16:02:11.490  1036  1438 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:02:11.490  1036  1494 D ConnectivityService: NetworkAgent connected
08-30 16:02:11.490  1036  1438 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 16:02:11.492  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.494  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.494  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:11.495  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.497  1036  1438 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:02:11.497  1036  1438 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:02:11.497  1036  1438 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 16:02:11.498  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:02:11.498  1036  1438 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 16:02:11.498  1036  1438 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 16:02:11.506  1036  1438 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 16:02:11.508   318   906 D CommandListener: Setting iface cfg
08-30 16:02:11.508  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:11.511  1036  1438 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 16:02:11.511  1036  7321 D DhcpStateMachine: StoppedState
08-30 16:02:11.511  1036  7321 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:11.511  1036  7321 D DhcpStateMachine: WaitBeforeStartState
,08-30 16:02:11.512  1036  1438 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=211166  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:02:11.513  1036  1438 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=211167  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:02:11.514  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=211168  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:02:11.514  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.514  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 16:02:11.515  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:11.515  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:11.515  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 16:02:11.515  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:02:11.515  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:11.516  1036  1438 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:11.516  1036  1438 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:11.517  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:11.517  1036  1438 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 16:02:11.518  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:11.518  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 16:02:11.518  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:02:11.519  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:11.519  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 16:02:11.524  1036  1438 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=211178  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:02:11.524  1036  1438 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=211179  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:02:11.525  1036  1438 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=211179  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 16:02:11.526  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:02:11.526  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14309] from screen [on:0 period:-608051002] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 16:02:11.527  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-608051001] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 16:02:11.527  1036  1438 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 16:02:11.531  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.533  1036  1494 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 16:02:11.534  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.534  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.534  1036  1438 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.535  1036  1438 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.535  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.536  1036  1438 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.536  1036  1494 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 16:02:11.536  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=13,0,0
08-30 16:02:11.537  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=13,0,0
08-30 16:02:11.537  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 16:02:11.537  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 16:02:11.538  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:11.538  1036  1438 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 16:02:11.538  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 16:02:11.539  1036  1438 D WifiNative-wlan0: SET ps 0: returned true
08-30 16:02:11.539  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 16:02:11.539  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 16:02:11.540  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-30 16:02:11.540  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@a47ee9f target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:11.540  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@a47ee9f target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:11.541  1036  7321 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:11.541  1036  7321 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 16:02:11.542  1036  1438 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 16:02:11.542  1036  1438 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:02:11.542  1036  1438 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:02:11.543   318   906 D CommandListener: Setting iface cfg
08-30 16:02:11.543   318   906 D CommandListener: Trying to bring up wlan0
08-30 16:02:11.545  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.545  1036  1438 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 16:02:11.545  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.545  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:11.545  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 16:02:11.546  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:02:11.547  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 16:02:11.547  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 16:02:11.547  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.547  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.548  1036  1438 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.548  1036  1438 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.549  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.549  1036  1438 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 16:02:11.549  1036  1494 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 16:02:11.550  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 16:02:11.550  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 16:02:11.550  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 16:02:11.550  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:11.551  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 16:02:11.551  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:02:11.551  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:02:11.551  1036  1438 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 16:02:11.551  1036  1438 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 16:02:11.551  7228  7228 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-30 16:02:11.552  1036  1438 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 16:02:11.552  1036  1438 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 16:02:11.558  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:02:11.563  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:02:11.568  1036  1438 D WifiNative-wlan0: SET ps 1: returned true
08-30 16:02:11.569  1036  1438 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:02:11.569  1036  1494 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 16:02:11.569  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 16:02:11.569  1036  1438 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 16:02:11.570  1036  1494 D ConnectivityService: ignoring duplicate network state non-change
08-30 16:02:11.571  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.572  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.572  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:11.573  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.573  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.574  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 16:02:11.574  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.574  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.575  1036  1494 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 16:02:11.575  1036  1494 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 16:02:11.577  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:02:11.580  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.580  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.580  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 16:02:11.581  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 16:02:11.584  1984  1984 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 16:02:11.585  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.585  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.586  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 16:02:11.591  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:02:11.592  1036  1438 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 16:02:11.593  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 16:02:11.596  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.596  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 16:02:11.597  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.597  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.598  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:02:11.598  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 16:02:11.600  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.600  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 16:02:11.600  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.602  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:02:11.603  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 16:02:11.603  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.606  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:02:11.612  1036  1494 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 16:02:11.612  1036  1494 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 16:02:11.613  1036  1494 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 16:02:11.614   318   906 E Netd    : netlink response contains error (File exists)
08-30 16:02:11.615  1036  1494 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 16:02:11.616  1036  1494 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 16:02:11.616  1036  1494 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 16:02:11.616  1036  1494 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 16:02:11.617  1036  1494 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 16:02:11.617  1036  1494 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 16:02:11.617  1036  1494 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 16:02:11.617  1036  1494 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 16:02:11.617  1036  1494 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:02:11.617  1036  1494 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:02:11.617  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:11.617  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 16:02:11.617  1036  1494 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 16:02:11.617  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:02:11.617  1036  1494 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.617  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 16:02:11.617  1036  1494 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 16:02:11.617  1036  1494 D ConnectivityService: currentScore = 0, newScore = 20
08-30 16:02:11.617  1036  1494 D ConnectivityService:    accepting network in place of null
,08-30 16:02:11.618  1036  1494 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.619  1036  1438 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.619  1036  1438 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:02:11.620  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:11.620  1036  1494 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 16:02:11.620  1036  1494 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 16:02:11.621   318  7327 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 16:02:11.621  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 16:02:11.623  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.623  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 16:02:11.626  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 16:02:11.626  1036  1494 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:02:11.626  1036  1494 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 16:02:11.627  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 16:02:11.627  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 16:02:11.627  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 16:02:11.628  1036  1494 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 16:02:11.628  1036  1494 D ConnectivityService: validation of new default Network = false
08-30 16:02:11.628  1036  1494 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 16:02:11.628  1036  1494 D DSQN    : enableDataServiceNotify 
0,8-30 16:02:11.628  1036  1494 D DSQN    : start dsqn bin
,08-30 16:02:11.635  1036  1494 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 16:02:11.635  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.635  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:02:11.635  1036  1494 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:02:11.636  1602  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 16:02:11.625  7328  7328 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:11.625  7328  7328 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:11.640  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.640  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.641  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:02:11.645  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:02:11.651  7328  7328 E DSQN    : DSQN ssw
08-30 16:02:11.659  1036  1391 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 16:02:11.667  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:02:11.669  1842  7331 I CheckinService: active receiver: enabled
08-30 16:02:11.672   318  7327 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 16:02:11.673  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 16:02:11.681  1842  7331 I CheckinService: Preparing to send checkin request
08-30 16:02:11.682  1842  7331 I EventLogService: Accumulating logs since 1472565561959
08-30 16:02:11.687  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.687  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.688  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:02:11.689  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:02:11.689  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.690  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.691  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:02:11.697  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 16:02:11.701  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:11.706   318  7327 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 16:02:11.706  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.707  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.708  6420  6420 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 16:02:11.712  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 16:02:11.714  6240  6318 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 791)
08-30 16:02:11.714  6240  6318 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 791)
08-30 16:02:11.716  7249  7249 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 16:02:11.717  6240  6318 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 796)
08-30 16:02:11.718  6240  6318 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 16:02:11.718  6240  6318 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 797)
08-30 16:02:11.719  7249  7249 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:02:11.721  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.721  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c241f19 added. We now have 2 listener(s)
08-30 16:02:11.723  1036  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.723  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:02:11.725  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.725  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.725  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.725  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.725  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3310bde added. We now have 9 listener(s)
08-30 16:02:11.725  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.725  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:02:11.728  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:02:11.731   318   905 D LGDataListener: argv[0]=dsqncommand
08-30 16:02:11.731   318   905 D LGDataListener: argv[1]=wlan0
08-30 16:02:11.731   318   905 D LGDataListener: argv[2]=1
08-30 16:02:11.731   318   905 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 16:02:11.732  1036  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 16:02:11.732  1036  1095 D DSQN    : start to monitor internet connection
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:02:11.733  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:02:11.736  1842  7331 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 16:02:11.736  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.736  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:02:11.736  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.736  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2299808c added. We now have 3 listener(s)
08-30 16:02:11.737  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.738  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.738  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.738  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.738  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.739  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.739  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ce93d5 added. We now have 10 listener(s)
08-30 16:02:11.739  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.739  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:02:11.739  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:02:11.739  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:02:11.739  6240  6318 I org.thalipr,oject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.739  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.739  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:02:11.739  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.739  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c241f19 removed from the list
08-30 16:02:11.739  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.739  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3310bde removed from the list
08-30 16:02:11.739  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:11.740  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.740  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:02:11.740  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:02:11.741  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.741  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.742  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.742  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.742  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.742  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3310bde not in the list
08-30 16:02:11.742  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.742  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.743  1036  7321 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 16:02:11.743  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.743  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.743  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.744  1036  7321 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 16:02:11.744  1036  7321 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 16:02:11.744  1036  1484 D WifiService: New client listening to asynchronous messages
08-30 16:02:11.745  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ce93d5 removed from the list
08-30 16:02:11.745  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.745  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.745  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.735  7337  7337 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:11.745  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.745  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2299808c removed from the list
08-30 16:02:11.746  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.746  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbe07ea added. We now have 2 listener(s)
08-30 16:02:11.746  1036  2074 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.735  7337  7337 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 16:02:11.748  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.748  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth nam,e: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.748  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.748  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.748  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4edadb added. We now have 9 listener(s)
08-30 16:02:11.748  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.748  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:02:11.750  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:02:11.752  7337  7337 I dhcpcd  : version 5.5.6 starting
,08-30 16:02:11.755  7337  7337 E dhcpcd  : get_duid: m
08-30 16:02:11.755  7337  7337 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 16:02:11.755  7337  7337 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 16:02:11.755  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.755  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.756  6420  6420 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:02:11.756  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:02:11.757  6420  6420 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:02:11.757  6420  6420 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 16:02:11.758  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.758  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:02:11.758  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.758  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14719851 added. We now have 3 listener(s)
08-30 16:02:11.760  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.761  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:02:11 GMT], X-Android-Received-Millis=[1472565731760], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472565731731]}
08-30 16:02:11.761  1036  1711 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.761  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 16:02:11.761  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 16:02:11.761  1036  1494 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 16:02:11.761  1036  1494 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 16:02:11.761  1036  1494 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:02:11.761  1036  1494 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:02:11.761  1036  1494 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 16:02:11.761  1036  1494 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 16:02:11.761  1036  1494 D ConnectivityService: notifyType AVAILABLE for NetworkAgent,Info [WIFI () - 101]
08-30 16:02:11.761  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.761  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:02:11.762  1036  1494 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:02:11.762  1036  1494 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.762  1602  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 16:02:11.763  1036  1494 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 16:02:11.763  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.763  1036  1438 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:11.763  1036  1438 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:02:11.763  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-30 16:02:11.765  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.765  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 16:02:11.768  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.769  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.769  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.769  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.769  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@306cb8b6 added. We now have 10 listener(s)
08-30 16:02:11.769  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.769  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:02:11.769  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:02:11.769  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:02:11.769  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:02:11.769  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:02:11.772  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:02:11.772  1036  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.772  7249  7249 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 16:02:11.774  7249  7249 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 16:02:11.776  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:02:11.776  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:02:11.778  6356  6356 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 16:02:11.779  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:02:11.779  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:02:11.783  6240  6318 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:02:11.784  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:02:11.784  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:02:11.785  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 16:02:11.786  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.786  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 16:02:11.788  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:02:11.788  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:02:11.788  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:02:11.788  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.788  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.788  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:02:11.788  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.788  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbe07ea removed from the list
08-30 16:02:11.788  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:02:11.788  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4edadb removed from the list
08-30 16:02:11.788  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:02:11.788  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.789  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.789  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.790  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.790  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.790  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.790  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4edadb not in the list
,08-30 16:02:11.790  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.790  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.791  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.792  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:02:11.792  6356  6356 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 16:02:11.792  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:02:11.792  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.792  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.792  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@306cb8b6 removed from the list
08-30 16:02:11.792  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.792  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.792  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.792  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.792  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14719851 removed from the list
08-30 16:02:11.793  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.793  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c66688d added. We now have 2 listener(s)
08-30 16:02:11.793  1036  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.797  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.797  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.797  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.797  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.797  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583aa42 added. We now have 9 listener(s)
08-30 16:02:11.797  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.797  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:02:11.799  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:02:11.801  6420  6420 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 16:02:11.801  6420  6420 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 16:02:11.801  6420  6420 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:02:11.802  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:02:11.802  6420  6420 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 16:02:11.802  6420  6420 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 16:02:11.803  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.803  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:02:11.803  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.803  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0c9f90 added. We now have 3 listener(s)
08-30 16:02:11.803  7337  7337 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 16:02:11.803  1036  2074 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.803  7337  7337 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 16:02:11.803  7337  7337 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:02:11.804  7337  7337 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 16:02:11.804  7337  7337 D dhcpcd  : wlan0: sending REQUEST (xid 0x3787c087), next in 4.05 seconds
,08-30 16:02:11.805  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.806  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.807  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.807  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.807  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.807  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.808  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205e0089 added. We now have 10 listener(s)
08-30 16:02:11.808  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.808  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:02:11.808  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:02:11.808  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:02:11.808  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:02:11.808  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:02:11.808  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:02:11.810  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:02:11.810  1036  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.813  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:02:11.813  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:02:11.814  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:02:11.815  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:02:11.816  6240  6318 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 16:02:11.816  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:02:11.816  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:02:11.816  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:02:11.816  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.816  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.817  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:02:11.817  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.817  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c66688d removed from the list
08-30 16:02:11.817  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.817  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583aa42 removed from the list
08-30 16:02:11.817  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:02:11.817  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.817  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.817  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.818  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.818  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.818  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.818  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583aa42 not in the list
08-30 16:02:11.818  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.818  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.819  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.819  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:02:11.819  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:02:11.819  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.819  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.819  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205e0089 removed from the list
08-30 16:02:11.819  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.819  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.819  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16,:02:11.819  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.820  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0c9f90 removed from the list
08-30 16:02:11.820  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.820  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14c424bc added. We now have 2 listener(s)
08-30 16:02:11.820  1036  2128 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.822  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.822  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.822  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.822  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.822  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d1c45 added. We now have 9 listener(s)
08-30 16:02:11.822  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.822  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:02:11.824  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:02:11.827  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:02:11.829  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:02:11.829  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:02:11.829  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.829  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107830cb added. We now have 3 listener(s)
08-30 16:02:11.830  1036  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.831  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.831  7337  7337 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 16:02:11.831  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.831  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.832  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.832  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.832  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0cd0a8 added. We now have 10 listener(s)
08-30 16:02:11.832  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:02:11.832  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:02:11.832  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:02:11.832  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:02:11.832  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:02:11.832  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:02:11.833  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.834  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:02:11.834  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.838  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:02:11.838  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:02:11.840  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:02:11.840  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:02:11.842  6240  6318 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 16:02:11.843  7337  7337 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 16:02:11.843  7337  7337 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 16:02:11.843  7337  7337 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 16:02:11.843  7337  7337 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 16:02:11.843  7337  7337 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 16:02:11.843  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:02:11.843  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:02:11.843  7337  7337 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 16:02:11.843  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:02:11.843  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.844  7337  7337 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 16:02:11.844  7337  7337 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 16:02:11.844  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.844  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:02:11.844  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.844  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14c424bc removed from the list
08-30 16:02:11.844  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.844  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d1c45 removed from the list
08-30 16:02:11.844  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:02:11.844  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.844  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.844  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.851  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.852  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.852  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.852  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d1c45 not in the list
08-30 16:02:11.852  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.852  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.853  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.854  6240  6318 D BluetoothLeScanner: could not find callback wrapper
08-30 16:02:11.854  6240  6318 D org.thali,project.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:02:11.854  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.854  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.854  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0cd0a8 removed from the list
08-30 16:02:11.854  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.854  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.854  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.854  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.854  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107830cb removed from the list
08-30 16:02:11.855  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.855  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d570ea7 added. We now have 2 listener(s)
08-30 16:02:11.855  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.857  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.857  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.858  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.858  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:02:11.858  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b24f54 added. We now have 9 listener(s)
08-30 16:02:11.858  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:02:11.858  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:02:11.863  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:02:11.867  6240  6318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:02:11.868  6240  6318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:02:11.868  6240  6318 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:02:11.869  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:02:11.869  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdf27f2 added. We now have 3 listener(s)
08-30 16:02:11.869  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 16:02:11.871  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.872  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 16:02:11.872  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:02:11.872  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:02:11.872  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:02:11.872  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235bee43 added. We now have 10 listener(s)
08-30 16:02:11.872  6240  6318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:02:11.873  6240  6318 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:02:11.873  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:02:11.873  6240  6318 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:02:11.873  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.873  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.873  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:02:11.873  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:02:11.873  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d570ea7 removed from the list
08-30 16:02:11.873  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.873  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b24f54 removed from the list
08-30 16:02:11.876  6240  6240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:02:11.876  6240  6318 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:02:11.876  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.877  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.877  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.878  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.878  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.878  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.878  6240  6318 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b24f54 not in the list
08-30 16:02:11.878  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.878  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.879  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:02:11.879  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:02:11.879  6240  6318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:02:11.879  6240  6318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235bee43 removed from the list
08-30 16:02:11.879  6240  6318 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:02:11.879  6240  6318 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:02:11.879  6240  6318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:02:11.879  6240  6318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothConnector: shutdown: Shutting down...
08-30 16:02:11.879  6240  6318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdf27f2 removed from the list
08-30 16:02:11.880  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 16:02:11.880  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 16:02:11.881  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 16:02:11.881  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:02:11.881  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 16:02:11.881  6240  6318 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:02:11.892  6240  7349 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 804, name: My test thread name)
08-30 16:02:11.892  6240  7349 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 804, thread name: My test thread name)
08-30 16:02:11.892  6240  7349 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 804, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 16:02:11.895  6240  7350 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 806, name: My test thread name)
08-30 16:02:11.895  6240  7350 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 806, thread name: My test thread name)
08-30 16:02:11.895  6240  7350 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 806, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 16:02:11.897  6240  6318 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 16:02:11.897  6240  6318 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 16:02:11.897  6240  6318 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 16:02:11.897  6240  6318 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 16:02:11.897  6240  6318 D com.test.thalitest.ThaliTestRunner: Total duration: 22752 ms
08-30 16:02:11.904  6240  6318 I jxcore-log: *Native tests were executed*
08-30 16:02:11.904  6240  6318 I jxcore-log: 
08-30 16:02:11.904  6240  6318 I jxcore-log: Total number of executed tests:  80
08-30 16:02:11.904  6240  6318 I jxcore-log: 
08-30 16:02:11.904  6240  6318 I jxcore-log: Number of passed tests:  80
08-30 16:02:11.904  6240  6318 I jxcore-log: 
08-30 16:02:11.905  6240  6318 I jxcore-log: Number of failed tests:  0
08-30 16:02:11.905  6240  6318 I jxcore-log: 
08-30 16:02:11.905  6240  6318 I jxcore-log: Number of ignored tests:  0
08-30 16:02:11.905  6240  6318 I jxcore-log: 
,08-30 16:02:11.906  6240  6318 I jxcore-log: Total duration:  22752
08-30 16:02:11.906  6240  6318 I jxcore-log: 
08-30 16:02:11.906  6240  6318 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 16:02:11.906  6240  6318 I jxcore-log: 
08-30 16:02:11.914  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.914  6240  6318 I jxcore-log: 
08-30 16:02:11.917  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.917  6240  6318 I jxcore-log: 
,08-30 16:02:11.918  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.918  6240  6318 I jxcore-log: 
08-30 16:02:11.919  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.919  6240  6318 I jxcore-log: 
08-30 16:02:11.920  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.920  6240  6318 I jxcore-log: 
08-30 16:02:11.922  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.922  6240  6318 I jxcore-log: 
08-30 16:02:11.928  6240  6240 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 16:02:11.929  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.929  6240  6318 I jxcore-log: 
08-30 16:02:11.931  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.931  6240  6318 I jxcore-log: 
08-30 16:02:11.932  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.932  6240  6318 I jxcore-log: 
08-30 16:02:11.933  1036  1766 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7354 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-30 16:02:11.934  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:02:11.934  6240  6318 I jxcore-log: 
08-30 16:02:11.935  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.935  6240  6318 I jxcore-log: 
08-30 16:02:11.936  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.936  6240  6318 I jxcore-log: 
08-30 16:02:11.937  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.937  6240  6318 I jxcore-log: 
08-30 16:02:11.938  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.938  6240  6318 I jxcore-log: 
08-30 16:02:11.938  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.938  6240  6318 I jxcore-log: 
08-30 16:02:11.939  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.939  6240  6318 I jxcore-log: 
,08-30 16:02:11.940  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.940  6240  6318 I jxcore-log: 
08-30 16:02:11.941  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.941  6240  6318 I jxcore-log: 
,08-30 16:02:11.942  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.942  6240  6318 I jxcore-log: 
08-30 16:02:11.942  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:02:11.942  6240  6318 I jxcore-log: 
08-30 16:02:11.946   352   352 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.464ms total 19.710ms
08-30 16:02:11.947  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.947  6240  6318 I jxcore-log: 
08-30 16:02:11.948  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:02:11.948  6240  6318 I jxcore-log: 
08-30 16:02:11.948  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:02:11.948  6240  6318 I jxcore-log: 
08-30 16:02:11.949  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:02:11.949  6240  6318 I jxcore-log: 
08-30 16:02:11.949  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:02:11.949  6240  6318 I jxcore-log: 
08-30 16:02:11.950  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:02:11.950  6240  6318 I jxcore-log: 
08-30 16:02:11.951  6240  6318 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:02:11.951  6240  6318 I jxcore-log: 
,08-30 16:02:11.966   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 513us total 20.275ms
08-30 16:02:11.984  7354  7354 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 16:02:11.985  7354  7354 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 16:02:11.985   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 256us total 18.536ms
,08-30 16:02:12.013  7354  7354 I MultiDex: VM with version 2.1.0 has multidex support
08-30 16:02:12.014  7354  7354 I MultiDex: install
08-30 16:02:12.014  7354  7354 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 16:02:12.024  7354  7354 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 16:02:12.028  2286  2286 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 16:02:12.038  2286  2286 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 16:02:12.039  2286  2286 D c       : Getting all permits...
08-30 16:02:12.039  2286  2286 D a       : Opening database...
,08-30 16:02:12.042  2286  2286 D a       : Opening database auth.proximity.permit_store...
08-30 16:02:12.043  2286  2286 D a       : Closing database...
08-30 16:02:12.118  7377  7377 D AndroidRuntime: 
08-30 16:02:12.118  7377  7377 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 16:02:12.120  7377  7377 D AndroidRuntime: CheckJNI is OFF
08-30 16:02:12.146  1036  7321 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 16:02:12.147  1036  7321 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 16:02:12.147  1036  7321 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 16:02:12.147  1036  7321 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 16:02:12.147  1036  7321 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 16:02:12.147  1036  7321 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 16:02:12.147  1036  7321 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 16:02:12.147  1036  7321 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 16:02:12.147  1036  7321 D DhcpStateMachine: RunningState
08-30 16:02:12.417  7377  7377 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 16:02:12.431  1036  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 16:02:12.432  1036  1093 I ActivityManager: Killing 6240:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 16:02:12.453  7354  7372 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:02:12.453  7354  7372 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:02:12.496  1036  2075 I WindowState: WIN DEATH: Window{23a330c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 16:02:12.496  1036  1484 D WifiService: Client connection lost with reason: 4
,08-30 16:02:12.508  1036  2075 D InputDispatcher: Window went away: Window{23a330c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 16:02:12.657  1036  1093 I ActivityManager:   Force finishing activity ActivityRecord{16d4d5f1 u0 com.test.thalitest/.MainActivity t6}
,08-30 16:02:12.703   342   368 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 16:02:12.712  1036  1956 W ActivityManager: Spurious death for ProcessRecord{1e2f204c 6240:com.test.thalitest/u0a118}, curProc for 6240: null
08-30 16:02:12.713  1036  1118 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 16:02:12.715  1036  1118 I ActivityManager:   Force finishing activity ActivityRecord{16d4d5f1 u0 com.test.thalitest/.MainActivity t6 f}
08-30 16:02:12.716  1036  1118 W ActivityManager: Duplicate finish request for ActivityRecord{16d4d5f1 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 16:02:12.769  2099  2099 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 16:02:12.771  2099  2099 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-30 16:02:12.775  1984  1999 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 16:02:12.776  1984  1999 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1857c850 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 16:02:12.777  2099  2099 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 16:02:12.778  2099  2180 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 16:02:12.780  1984  2000 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 16:02:12.781  1984  2000 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a48da49 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 16:02:12.782  4553  4553 I art     : Explicit concurrent mark sweep GC freed 764(44KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 618us total 44.578ms
08-30 16:02:12.786  1937  1937 D ActionManagerService: notifyUserLog: 1000003
,08-30 16:02:12.787  2099  2099 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 16:02:12.788  2772  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 16:02:12.788  2099  2099 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 16:02:12.789  2099  2099 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 16:02:12.790  2099  2099 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 16:02:12.794  1937  1937 D ActionManagerService: notifyUserLog: 1000004
08-30 16:02:12.794  2772  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 16:02:12.795  2099  2099 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 16:02:12.796  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 16:02:12.800  1036  1382 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 16:02:12.806  2507  2620 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 16:02:12.834  2057  2057 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 16:02:12.834  2772  2772 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 16:02:12.839  2772  2791 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 16:02:12.840  7062  7062 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 16:02:12.840  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 16:02:12.846  3703  3703 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 16:02:12.848  4432  4432 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 16:02:12.848  4432  4432 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 16:02:12.848  4432  4432 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 16:02:12.848  4432  4432 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
,08-30 16:02:12.848  4432  4432 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:02:12.848  4432  4432 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:02:12.848  4432  4432 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 16:02:12.848  4432  4432 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 16:02:12.848  4432  4432 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:02:12.848  4432  4432 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:02:12.848  4432  4432 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 16:02:12.848  4432  4432 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 16:02:12.854  1036  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 16:02:12.886  1036  2013 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:02:12.894  1036  2075 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7417 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-30 16:02:12.928  1036  1036 I art     : Explicit concurrent mark sweep GC freed 76672(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.213ms total 200.655ms
,08-30 16:02:12.932  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , expire_time: 0
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , display: false
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , animation: false }
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , expire_time: 0
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , display: false
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , animation: false }
,08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , expire_time: 0
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , display: false
08-30 16:02:12.933  2099  2099 I GBoardWebViewUtils: , animation: false }
08-30 16:02:12.939  1842  1842 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 16:02:12.939  1901  1901 D SplitUIManager: split_name #11 / not available #0
08-30 16:02:12.940  1901  1901 D SplitUIService: removed split : 
08-30 16:02:12.949  2286  2286 I ConfigService: onCreate
08-30 16:02:12.950  2286  2286 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 16:02:12.956  2099  7435 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-30 16:02:12.957  1842  1842 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 16:02:12.960  1036  2129 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:02:12.960  1036  2129 V SIM_STK : Menu title from STK is T-Mobile
08-30 16:02:12.962  2099  2099 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 16:02:12.964  2286  2286 I ConfigService: onBind returning update interface
08-30 16:02:12.975  2286  2286 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 16:02:12.975  2286  2286 I ConfigService: onBind returning config service
,08-30 16:02:12.994  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 16:02:12.994  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-30 16:02:13.011  1036  1959 V SIM_STK : Menu title from STK is T-Mobile
,08-30 16:02:13.026  1901  1901 D SplitUIManager: split_name #11 / not available #0
08-30 16:02:13.026  1901  1901 I SplitUIService: split app #11
,08-30 16:02:13.031  1036  2094 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 16:02:13.031  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 16:02:13.032  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 16:02:13.032  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 16:02:13.032  7062  7062 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 16:02:13.035  2286  2286 I ConfigService: onDestroy
08-30 16:02:13.038  1842  7440 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 16:02:13.038  2099  2099 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 16:02:13.040  2099  2099 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 16:02:13.052  7417  7417 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-30 16:02:13.058  2099  2118 I art     : Background partial concurrent mark sweep GC freed 6847(301KB) AllocSpace objects, 3(324KB) LOS objects, 28% free, 79MB/111MB, paused 11.475ms total 28.767ms
,08-30 16:02:13.079  1036  2028 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7444 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 16:02:13.082   331   435 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 16:02:13.082  3222  7443 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 16:02:13.087  1036  1036 D administrator: Handling package changes for user 0
08-30 16:02:13.095  1602  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 16:02:13.095  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.096  1602  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 16:02:13.096  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.099  7450  7450 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-30 16:02:13.102  1602  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 16:02:13.102  1602  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:02:13.103  1602  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-30 16:02:13.104  1602  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 16:02:13.105  1602  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:02:13.105  1602  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 16:02:13.107  1602  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 16:02:13.107  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.110  1602  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 16:02:13.111  1602  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 16:02:13.116  1602  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:02:13.116  1602  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 16:02:13.120  1602  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 16:02:13.120  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.125  1036  1438 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:02:13.125  1036  1438 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:02:13.125  1036  1438 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:02:13.126  1036  1438 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:02:13.126  1036  1438 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:02:13.126  1036  1438 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 16:02:13.126  1036  1494 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-30 16:02:13.127  1036  1494 D ConnectivityService: identical MTU - not setting
08-30 16:02:13.127  1036  1494 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 16:02:13.127  1036  1494 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 16:02:13.127  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:02:13.127  1036  1494 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 16:02:13.127  1036  1494 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 16:02:13.128  1602  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 16:02:13.134  5569  7462 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 16:02:13.137  1602  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:02:13.137  1602  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 16:02:13.138  1602  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 16:02:13.138  1602  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 16:02:13.146  2099  2099 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-30 16:02:13.149  1602  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:02:13.149  1602  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 16:02:13.150  1602  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 16:02:13.150  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.155  1036  1959 I ActivityManager: Killing 6752:com.lge.email/u0a23 (adj 15): empty #17
08-30 16:02:13.156  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.165  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-30 16:02:13.166  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,08-30 16:02:13.169  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 16:02:13.171  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 16:02:13.192  2099  2099 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 16:02:13.192  2099  2838 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 16:02:13.192  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.192  2099  2838 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-30 16:02:13.207  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 16:02:13.208  1842  1859 I art     : Explicit concurrent mark sweep GC freed 21908(1470KB) AllocSpace objects, 18(288KB) LOS objects, 51% free, 29MB/61MB, paused 1.595ms total 93.312ms
,08-30 16:02:13.215  2099  2099 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 16:02:13.215  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.217  1842  7475 I PeopleContactsSync: CP2 sync disabled
08-30 16:02:13.222  2099  2099 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-30 16:02:13.223  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-30 16:02:13.223  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 16:02:13.224  7450  7450 I dex2oat : dex2oat took 124.358ms (threads: 4)
08-30 16:02:13.230  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 16:02:13.230  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 16:02:13.230  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 16:02:13.234  7354  7372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:02:13.234  7354  7372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:02:13.234  7354  7372 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:02:13.234  7354  7372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:02:13.234  7354  7372 I Adreno-EGL: Remote Branch: 
08-30 16:02:13.234  7354  7372 I Adreno-EGL: Local Patches: 
08-30 16:02:13.234  7354  7372 I Adreno-EGL: Reconstruct Branch: 
08-30 16:02:13.235  1602  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 16:02:13.236  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.238  2639  2639 D [Concierge]Service: onStartCommand(). Type : 8
08-30 16:02:13.238  2639  2639 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 16:02:13.238  1036  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d6cc73f u0 com.lge.launcher2/.Launcher t5} time:212905
08-30 16:02:13.239  2639  2639 D [Concierge]Service: Update widget ID : 11
08-30 16:02:13.240  1036  2013 W libprocessgroup: failed to open /acct/uid_10023/pid_6752/cgroup.procs: No such file or directory
08-30 16:02:13.240  2099  2099 D [Concierge]WidgetView: change position of spinner
08-30 16:02:13.241  1842  4712 I Icing   : doRemovePackageData com.test.thalitest
,08-30 16:02:13.243  1602  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 16:02:13.243  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.245  1602  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:02:13.245  1602  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 16:02:13.247  1602  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 16:02:13.247  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.250  1602  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 16:02:13.250  1602  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 16:02:13.250  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 16:02:13.251  2099  2099 I [Concierge]WidgetView: initWebView(). Time : 1472565733251
08-30 16:02:13.252  2639  2639 D [Concierge]Service: onStartCommand(). Type : 0
08-30 16:02:13.254  1602  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 16:02:13.254  1602  1649 D KeyguardModel: createShortcutInfo...
08-30 16:02:13.256  1602  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 16:02:13.256  1602  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 16:02:13.257  1602  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 16:02:13.257  1602  1649 D KeyguardModel: createShortcutInfo...
,08-30 16:02:13.263  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-30 16:02:13.263  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 16:02:13.268  2099  2099 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 326610407
08-30 16:02:13.268  2099  2099 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 16:02:13.268  2099  2099 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 16:02:13.271  2099  2099 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@13ab7002
08-30 16:02:13.271  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 16:02:13.272  2099  2099 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 16:02:13.272  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.273  1842  7473 W GmsApplication: Using Auth Proxy for data requests.
08-30 16:02:13.277  7444  7444 I AppUp4:AppBoxCP: onCreate
08-30 16:02:13.277  7444  7444 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 16:02:13.286  7444  7444 I AppUp4:DB:  setFingerPrint start
08-30 16:02:13.286  7444  7444 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 16:02:13.288  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 16:02:13.288  2099  2099 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 16:02:13.288  2099  2099 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 16:02:13.289  2099  2099 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472565549082, New one : 1472565733251
08-30 16:02:13.289  2099  2099 D [Concierge]WidgetView: Unregister all receivers
08-30 16:02:13.289  2099  2099 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 16:02:13.290  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.291  7444  7444 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 16:02:13.291  7444  7444 I AppUp4:DB:  SDK version = 21
08-30 16:02:13.291  7444  7444 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 16:02:13.292  7444  7444 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 16:02:13.297  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-30 16:02:13.298  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 16:02:13.300  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 16:02:13.301  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 16:02:13.301  1842  7473 W GmsApplication: Using Auth Proxy for data requests.
08-30 16:02:13.302  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 16:02:13.309  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.310  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.321  7354  7372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:02:13.321  7354  7372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:02:13.321  7354  7372 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:02:13.321  7354  7372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:02:13.321  7354  7372 I Adreno-EGL: Remote Branch: 
08-30 16:02:13.321  7354  7372 I Adreno-EGL: Local Patches: 
08-30 16:02:13.321  7354  7372 I Adreno-EGL: Reconstruct Branch: 
08-30 16:02:13.323  7444  7444 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 16:02:13.346  1036  1118 I art     : Explicit concurrent mark sweep GC freed 15160(922KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.755ms total 385.589ms
,08-30 16:02:13.351  1036  2013 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7477 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 16:02:13.352  1036  2013 I ActivityManager: Killing 6814:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-30 16:02:13.369  2099  2099 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 16:02:13.378  2099  2099 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 16:02:13.378  2099  2099 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 16:02:13.380  2099  2099 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 16:02:13.401  2099  2099 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15c91f0 time:213068
,08-30 16:02:13.443  7377  7377 D AndroidRuntime: Shutting down VM
,08-30 16:02:13.453  1036  1956 W libprocessgroup: failed to open /acct/uid_10046/pid_6814/cgroup.procs: No such file or directory
,08-30 16:02:13.456  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 16:02:13.463  7354  7372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 16:02:13.463  7354  7372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 16:02:13.463  7354  7372 I Adreno-EGL: Build Date: 12/12/14 금
08-30 16:02:13.463  7354  7372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 16:02:13.463  7354  7372 I Adreno-EGL: Remote Branch: 
08-30 16:02:13.463  7354  7372 I Adreno-EGL: Local Patches: 
08-30 16:02:13.463  7354  7372 I Adreno-EGL: Reconstruct Branch: 
08-30 16:02:13.465  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 16:02:13.474  7477  7477 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:02:13.475  7477  7477 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:02:13.475  7477  7477 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-30 16:02:13.483  7477  7477 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 16:02:13.483  7477  7477 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 16:02:13.496  1036  1118 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7494 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 16:02:13.500  2099  2099 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 16:02:13.523  2286  2307 I art     : Explicit concurrent mark sweep GC freed 4984(286KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 470us total 16.917ms
08-30 16:02:13.544  2099  2099 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 16:02:13.554  1036  1576 I ActivityManager: Killing 6853:com.android.chrome/u0a57 (adj 15): empty #17
08-30 16:02:13.577  7477  7477 I SystemConfig: BUILD Country: EU
,08-30 16:02:13.577  7477  7477 I SystemConfig: BUILD Operator: OPEN
08-30 16:02:13.586  2099  2891 I GBoardtInterface: onReloaded()
08-30 16:02:13.588  2099  2099 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-30 16:02:13.633  1036  1956 W libprocessgroup: failed to open /acct/uid_10057/pid_6853/cgroup.procs: No such file or directory
,08-30 16:02:13.635  2772  2792 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 16:02:13.637  2772  2787 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 16:02:13.639  1036  2014 I ActivityManager: Killing 6880:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 16:02:13.665  1036  2028 W libprocessgroup: failed to open /acct/uid_10062/pid_6880/cgroup.procs: No such file or directory
,08-30 16:02:13.667  7477  7513 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 16:02:13.667  7477  7513 I SystemConfig: existFile = false
,08-30 16:02:13.667  7477  7513 I SystemConfig: canReadFile = false
08-30 16:02:13.667  7477  7513 I SystemConfig: systemFeature RCS result false
08-30 16:02:13.667  7477  7513 D SystemConfig: refreshRcsSupport() :false
08-30 16:02:13.671  2157  7515 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 16:02:13.682   318  7517 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 16:02:13.682   318  7517 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 16:02:13.687  1036  2013 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7518 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 16:02:13.688  1937  1937 D ActionManagerService: notifyUserLog: 1000001
08-30 16:02:13.689  2772  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 16:02:13.689  2772  4453 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 16:02:13.691  1937  1937 D ActionManagerService: notifyUserLog: 1000001
08-30 16:02:13.691  2772  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 16:02:13.691  2772  4453 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 16:02:13.691  2772  4453 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 16:02:13.692  2772  4453 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 16:02:13.692  2772  2787 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 16:02:13.694  2099  2099 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,08-30 16:02:13.694  2099  2099 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 16:02:13.696  2099  2099 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 16:02:13.696  2099  2099 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 16:02:13.698  2099  2099 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 16:02:13.698  2099  2099 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-30 16:02:13.719  7518  7518 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:02:13.720  7518  7518 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 16:02:13.720   318  7517 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-30 16:02:13.720  7518  7518 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 16:02:13.721  7518  7518 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 16:02:13.765  7518  7518 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 16:02:13.773  7518  7518 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 16:02:13.792  7518  7518 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 16:02:13.810  7518  7518 D LgDataFeature: LgDataFeature() Constructor: none
08-30 16:02:13.810  7518  7518 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 16:02:13.848  1842  7331 I CheckinTask: Sending checkin request (7885 bytes)
,08-30 16:02:13.865  7518  7518 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 16:02:13.893  1036  1051 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7541 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-30 16:02:13.894  1036  1051 I ActivityManager: Killing 6898:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17

```
