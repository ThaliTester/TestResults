#### Test 822030602c9dbcd_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-22 18:31:19.470  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=345060928 [*alarm*], flags=0x0
,--------- beginning of main
08-22 18:31:40.894  6196  6196 D AndroidRuntime: 
08-22 18:31:40.894  6196  6196 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 18:31:40.901  6196  6196 D AndroidRuntime: CheckJNI is OFF
08-22 18:31:41.104  6196  6196 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 18:31:41.115  1034  1574 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 18:31:41.129  1966  1981 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-22 18:31:41.135  1034  1574 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-22 18:31:41.136  1034  1574 D ActivityManager: setTaskToReturnTo : TaskRecord{19ccd7d6 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 18:31:41.136  1034  1574 D ActivityManager: setTaskToReturnTo : TaskRecord{19ccd7d6 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 18:31:41.138  1034  1574 D WindowStateEx: AppWindowTokenEx init.. 
08-22 18:31:41.139   343   352 E GBMv2   : DFP En is all cleared set to be enabled
08-22 18:31:41.169  1034  1574 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6211 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 18:31:41.172  6196  6196 D AndroidRuntime: Shutting down VM
08-22 18:31:41.226  1966  1982 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-22 18:31:41.226  1966  1982 D SplitWindowPolicy: topRunningActivity=ActivityInfo{46e3813 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-22 18:31:41.227  1966  1981 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-22 18:31:41.227  1966  1981 D SplitWindowPolicy: topRunningActivity=ActivityInfo{29b5da50 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-22 18:31:41.263  6211  6211 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-22 18:31:41.377  6211  6211 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-22 18:31:41.385  6211  6211 I LibraryLoader: Loading: webviewchromium
08-22 18:31:41.388  6211  6211 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 299-302)
08-22 18:31:41.388  6211  6211 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 18:31:41.400  6211  6211 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32109ddf}
,08-22 18:31:41.401  6211  6211 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 18:31:41.401  6211  6211 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 18:31:41.410  6211  6211 I BrowserStartupController: Initializing chromium process, renderers=0
08-22 18:31:41.411  6211  6211 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 18:31:41.419  6211  6247 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,08-22 18:31:41.424   323  2986 V AudioPolicyService: registerClient() client 0xb1427800, uid 10118
08-22 18:31:41.428  6211  6211 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-22 18:31:41.429  6211  6211 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-22 18:31:41.429  6211  6211 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-22 18:31:41.431  1034  1096 D BluetoothManagerService: Message: 20
08-22 18:31:41.431  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@159ec5b0:true
,08-22 18:31:41.463  6211  6211 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 18:31:41.463  6211  6211 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 18:31:41.463  6211  6211 I Adreno-EGL: Build Date: 12/12/14 금
08-22 18:31:41.463  6211  6211 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-22 18:31:41.463  6211  6211 I Adreno-EGL: Remote Branch: 
08-22 18:31:41.463  6211  6211 I Adreno-EGL: Local Patches: 
08-22 18:31:41.463  6211  6211 I Adreno-EGL: Reconstruct Branch: 
,08-22 18:31:41.557  6211  6257 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-22 18:31:41.566  6211  6211 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-22 18:31:41.588  6211  6211 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:31:41.593  6211  6211 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-22 18:31:41.596  6211  6211 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-22 18:31:41.599  6211  6211 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-22 18:31:41.599  6211  6211 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-22 18:31:41.613  6211  6211 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-22 18:31:41.621  6211  6211 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:31:41.621  6211  6211 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:31:41.673  6211  6275 D OpenGLRenderer: Render dirty regions requested: true
08-22 18:31:41.674  6211  6275 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 18:31:41.682  6211  6275 D OpenGLRenderer: Enabling debug mode 0
08-22 18:31:41.690  6211  6211 D Atlas   : Validating map...
,08-22 18:31:41.696  1034  1050 D SplitWindow: check instance of lgWin Window{132b406a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 18:31:41.774  6211  6273 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:31:41.774  6211  6273 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 18:31:41.810  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +585ms (total +670ms)
,08-22 18:31:41.810  6211  6211 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@102eaa3a time:170725
,08-22 18:31:41.813  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b7f4a57 u0 com.test.thalitest/.MainActivity t6} time:170727
08-22 18:31:41.955  6211  6211 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-22 18:31:41.955  6211  6211 I chromium: 
,08-22 18:31:42.001  6211  6211 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 18:31:42.156  6211  6286 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435160064
,08-22 18:31:42.173  6211  6286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 18:31:42.173  6211  6286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 18:31:42.173  6211  6286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 18:31:42.173  6211  6286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 18:31:42.173  6211  6286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-22 18:31:42.173  6211  6286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1439de added. We now have 1 listener(s)
,08-22 18:31:42.180  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:31:42.183  6211  6286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-22 18:31:42.187  6211  6286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-22 18:31:42.189  6211  6286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:42.190  6211  6286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 18:31:42.199  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 18:31:42.200  6211  6286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d3619d5 added. We now have 1 listener(s)
,08-22 18:31:42.200  6211  6286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:42.205  1034  1453 D WifiService: New client listening to asynchronous messages
08-22 18:31:42.210  6211  6286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:31:42.210  6211  6286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-22 18:31:42.212  6211  6286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 18:31:42.212  6211  6286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 18:31:42.212  6211  6286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 18:31:42.221  6211  6286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:42.224  1034  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-22 18:31:42.226  6211  6286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-22 18:31:42.237  6211  6286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:42.239  6211  6286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:42.239  6211  6286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 18:31:42.239  6211  6286 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:42.241  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:42.243  6211  6286 I io.jxcore.node.LifeCycleMonitor: start: OK
08-22 18:31:42.284  6211  6273 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-22 18:31:42.284  6211  6273 I chromium: 
,08-22 18:31:42.378  6211  6211 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 18:31:42.897   343   354 E GBMv2   : DFP En is all cleared set to be enabled
08-22 18:31:42.898   343   354 E GBMv2   : Set value is all cleared set the max
08-22 18:31:42.898   343   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-22 18:31:43.287  6211  6289 W jxcore-log: Initializing JXcore engine
08-22 18:31:43.287  6211  6289 W jxcore-log: JXcore engine is ready
,08-22 18:31:43.318  6289  6289 W Thread-702: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7606]" dev="sockfs" ino=7606 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-22 18:31:43.318  6289  6289 W Thread-702: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-22 18:31:43.318  6289  6289 W Thread-702: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9854]" dev="sockfs" ino=9854 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-22 18:31:43.318  6289  6289 W Thread-702: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-22 18:31:43.318  6289  6289 W Thread-702: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[29093]" dev="sockfs" ino=29093 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-22 18:31:43.336  6211  6289 W jxcore-log: Starting JXcore engine
,08-22 18:31:43.516  6211  6289 W jxcore-log: Platform android
08-22 18:31:43.516  6211  6289 W jxcore-log: 
,08-22 18:31:43.517  6211  6289 W jxcore-log: Process ARCH arm
08-22 18:31:43.517  6211  6289 W jxcore-log: 
08-22 18:31:43.808  6211  6289 I jxcore-log: JXcore Cordova bridge is ready!
08-22 18:31:43.808  6211  6289 I jxcore-log: 
08-22 18:31:43.808  6211  6289 W jxcore-log: JXcore engine is started
,08-22 18:31:43.815  6211  6286 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-22 18:31:43.817  6211  6211 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-22 18:31:46.468  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{63edc10 type 2 when 175371 com.google.android.gms} when 175371
,08-22 18:31:55.084  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 18:31:55.084  6211  6289 I jxcore-log: 
,08-22 18:31:55.091  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 18:31:55.091  6211  6289 I jxcore-log: 
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:55.095  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:55.098  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:55.104  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 18:31:55.104  6211  6289 I jxcore-log: 
08-22 18:31:55.107  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 18:31:55.107  6211  6289 I jxcore-log: 
08-22 18:31:56.064  6211  6289 D ExecuteNativeTests: Running unit tests
,08-22 18:31:56.202  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:56.202  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 added. We now have 2 listener(s)
,08-22 18:31:56.204  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:31:56.207  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:31:56.207  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:56.207  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:56.207  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:56.208  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 added. We now have 2 listener(s)
08-22 18:31:56.208  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:56.208  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:31:56.211  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.214  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:56.219  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:56.219  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:56.220  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.224  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:31:56.226  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:31:56.226  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 18:31:56.232  6211  6289 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-22 18:31:56.234  6211  6289 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 18:31:56.234  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:31:56.236  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:31:56.236  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:31:56.237  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.238  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.238  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.239  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.240  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.240  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:56.240  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:56.240  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 removed from the list
08-22 18:31:56.241  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.241  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 removed from the list
08-22 18:31:56.241  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.241  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:56.244  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.244  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.246  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.246  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.246  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.246  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.248  6211  6289 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-22 18:31:56.249  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.249  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.249  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.250  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.250  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.250  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.250  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.250  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.250  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.250  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.250  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.250  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.250  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.250  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.251  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.252  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.252  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.252  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.258  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 1,8:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 18:31:56.259  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 18:31:56.260  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 18:31:56.260  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 18:31:56.260  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 18:31:56.260  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 18:31:56.260  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 18:31:56.260  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 18:31:56.260  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 18:31:56.260  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:31:56.260  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.260  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:56.268  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.268  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.268  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.268  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.268  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.268  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.268  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.269  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.269  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.269  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.269  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.270  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.270  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.270  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.270  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.272  6211  6289 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 18:31:56.274  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.279  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:56.280  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:56.280  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:56.282  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.282  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:56.282  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:56.282  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:31:56.282  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.282  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:31:56.287  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:31:56.289  1034  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:31:56.296  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 18:31:56.302  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:31:56.307  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-22 18:31:56.309  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:31:56.309  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:56.311  6211  6289 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-22 18:31:56.312  6211  6289 I io.jxcore.node.ConnectionHelper: start: OK
08-22 18:31:56.317  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.317  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.317  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:56.319  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.319  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.319  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:56.319  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.319  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.319  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.320  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.320  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.320  6211  6289 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 18:31:56.322  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.324  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:56.326  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:56.326  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:56.327  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.328  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:56.328  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:56.328  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:31:56.328  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.328  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:31:56.333  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 18:31:56.335  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:56.337  6211  6289 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-22 18:31:56.337  6211  6289 I io.jxcore.node.ConnectionHelper: start: OK
08-22 18:31:56.339  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.339  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.339  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.340  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.340  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.340  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:56.340  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.340  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.340  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.340  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.340  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.341  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.341  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.342  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.342  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.344  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.344  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.344  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.344  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
,08-22 18:31:56.347  6211  6289 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 18:31:56.350  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.352  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:56.354  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:56.354  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:56.356  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:56.357  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:56.357  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:56.357  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:31:56.357  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.357  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:31:56.362  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:31:56.363  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:56.364  6211  6289 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-22 18:31:56.365  6211  6289 I io.jxcore.node.ConnectionHelper: start: OK
08-22 18:31:56.365  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.367  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.367  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:56.373  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.374  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.374  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.375  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.375  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.375  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:56.375  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.375  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.375  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.375  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.376  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.377  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.378  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.381  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.381  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:31:56.386  6211  6289 D BluetoothLeScanner: could not find callback wrapper
,08-22 18:31:56.386  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.386  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.386  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.387  6211  6289 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-22 18:31:56.387  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.387  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.387  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.387  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.388  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.388  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.388  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.388  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.388  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.388  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.388  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.388  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.388  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.388  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.389  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.389  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.390  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.390  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.390  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.390  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.391  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 18:31:56.391  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.391  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.392  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:56.392  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.392  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.392  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.392  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.392  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.392  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.392  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.392  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.392  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.392  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.392  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.394  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.394  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.394  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.394  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.394  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.394  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.396  6211  6289 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-22 18:31:56.396  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.396  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.396  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.397  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.397  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.397  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.397  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.397  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.397  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.397  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.397  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.398  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.398  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.398  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.399  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.399  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.400  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.400  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.400  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.400  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.402  6211  6289 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 18:31:56.402  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.402  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.402  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.402  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.402  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.402  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.402  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.402  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.402  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.402  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.402  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.402  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.403  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.403  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.404  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.404  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.404  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.405  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.405  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.405  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.405  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:31:56.407  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:31:56.407  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:31:56.407  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:31:56.407  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:31:56.408  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:31:56.408  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.408  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.408  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.408  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.408  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.408  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.408  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.408  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.408  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.408  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.408  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.408  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.408  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.408  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.410  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.410  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.410  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.410  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 18:31:56.410  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.410  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.416  6211  6289 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:31:56.417  6211  6289 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 18:31:56.417  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 18:31:56.424  6211  6289 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:31:56.424  6211  6289 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 18:31:56.424  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 18:31:56.424  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 18:31:56.424  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 18:31:56.424  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 18:31:56.424  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 18:31:56.424  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 18:31:56.424  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 18:31:56.425  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 18:31:56.426  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 18:31:56.426  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 18:31:56.426  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 18:31:56.426  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 18:31:56.426  6211  6289 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 18:31:56.426  6211  6289 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:31:56.426  6211  6289 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 18:31:56.426  6211  6289 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:31:56.426  6211  6289 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:31:56.426  6211  6289 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-22 18:31:56.426  6211  6289 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:31:56.427  6211  6289 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:31:56.427  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-22 18:31:56.429  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-22 18:31:56.430  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 18:31:56.430  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-22 18:31:56.432  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 18:31:56.432  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 18:31:56.432  6211  6289 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 18:31:56.433  6211  6289 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:31:56.433  6211  6289 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 18:31:56.434  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.434  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.434  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.435  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.435  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.435  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.436  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-22 18:31:56.437  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.437  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.437  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.437  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.437  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.437  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.438  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.438  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.439  6211  6309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 766)
08-22 18:31:56.439  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.439  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.440  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.440  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.440  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.440  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.441  6211  6289 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-22 18:31:56.441  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.441  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.441  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.442  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.442  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.442  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.442  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.442  6211  6310 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 766
08-22 18:31:56.442  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.442  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.442  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.442  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.442  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.442  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.442  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.443  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.443  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.444  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.445  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.445  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.446  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.447  6211  6289 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 18:31:56.449  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.449  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.450  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.450  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.450  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.450  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.450  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.450  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.450  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.450  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.450  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.450  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.450  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.450  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.454  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.454  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.455  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.455  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.455  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.455  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.456  6211  6289 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 18:31:56.456  6211  6289 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 18:31:56.457  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:31:56.457  6211  6289 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 18:31:56.457  6211  6289 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 18:31:56.457  6211  6289 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 18:31:56.457  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:31:56.457  6211  6289 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 18:31:56.457  6211  6289 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 18:31:56.457  6211  6289 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 18:31:56.457  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:31:56.457  6211  6289 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 18:31:56.458  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.458  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.458  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.459  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.459  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.459  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.459  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.459  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.459  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.459  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.459  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.459  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.459  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.459  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.460  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.460  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:31:56.461  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.461  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.461  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.461  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.462  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.462  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.462  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.462  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.462  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.462  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.462  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.462  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.462  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.463  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.463  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.463  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.463  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.463  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.463  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.463  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.463  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.463  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.464  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.464  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.464  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.465  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.465  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.465  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.465  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.466  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.466  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.466  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.466  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.470  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.470  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.471  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.471  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.471  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.471  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.473  6211  6289 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-22 18:31:56.473  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.473  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-22 18:31:56.474  6211  6289 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 18:31:56.474  6211  6289 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-22 18:31:56.475  6211  6211 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 18:31:56.475  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-22 18:31:56.475  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:31:56.476  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.476  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 18:31:56.476  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-22 18:31:56.476  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 18:31:56.476  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.476  6211  6289 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 18:31:56.476  6211  6211 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 18:31:56.476  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.476  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.477  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:31:56.477  6211  6289 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:31:56.477  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:31:56.477  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:31:56.479  6211  6319 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 18:31:56.479  6211  6319 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-22 18:31:56.480  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:31:56.480  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:56.480  6211  6289 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:31:56.480  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.480  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.481  6211  6289 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:31:56.482  6211  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:56.482  6211  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:56.482  6211  6211 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-22 18:31:56.482  6211  6211 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:31:56.482  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.482  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.482  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.482  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.483  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.483  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.483  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.483  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.483  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.483  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.483  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.483  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.483  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.483  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.483  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.484  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.484  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.484  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.484  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.485  6211  6289 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-22 18:31:56.485  6211  6289 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 18:31:56.485  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:31:56.486  6211  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:31:56.487  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.487  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.487  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.487  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.487  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.487  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.487  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.487  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.487  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.487  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.487  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.487  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.487  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.487  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.488  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.488  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.488  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.488  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.489  1034  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:31:56.490  1034  2127 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:31:56.491  1034  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:31:56.492  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.492  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.492  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.492  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.492  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.492  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.492  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.492  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.492  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.492  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.492  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.492  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.493  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.493  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.494  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.494  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.494  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.494  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.495  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:56.495  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:56.495  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:56.495  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:56.495  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.495  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.495  6211  6289 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0fdb30 not in the list
08-22 18:31:56.495  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.495  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.496  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:56.496  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.496  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.496  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:56.496  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:56.496  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:56.496  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:56.496  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:56.496  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a923a9 not in the list
08-22 18:31:56.497  6211  6289 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 18:31:56.497  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:31:56.498  6211  6289 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 18:31:56.498  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:31:56.498  6211  6289 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 18:31:56.498  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:31:56.499  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 18:31:56.499  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-22 18:31:56.500  6211  6289 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-22 18:31:56.500  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 18:31:56.500  6211  6289 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 18:31:56.500  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 18:31:56.500  6211  6289 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 18:31:56.500  6211  6289 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-22 18:31:56.501  6211  6289 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 18:31:56.501  6211  6289 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-22 18:31:56.502  6211  6289 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 18:31:56.502  6211  6289 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 18:31:56.502  6211  6289 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 18:31:56.502  6211  6289 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-22 18:31:56.503  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:56.503  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f126406 added. We now have 2 listener(s)
08-22 18:31:56.503  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:56.509  6211  6289 D BluetoothAdapter: enable(): BT is already enabled..!
08-22 18:31:56.510  1034  2004 D WifiServiceImplEx: setWifiEnabled: true pid=6211, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-22 18:31:56.510  1034  2004 D WifiService: setWifiEnabled: true pid=6211, uid=10118
08-22 18:31:56.510  1034  2004 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 18:31:56.512  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:56.512  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17f29ac7 added. We now have 3 listener(s)
08-22 18:31:56.512  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:56.516  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:56.516  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a5eb8f4 added. We now have 4 listener(s)
08-22 18:31:56.516  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:56.518  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:56.518  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1767481d added. We now have 5 listener(s)
08-22 18:31:56.518  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:56.520  1034  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6211, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-22 18:31:56.521  1034  1051 D WifiService: setWifiEnabled: false pid=6211, uid=10118
08-22 18:31:56.521  1034  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 18:31:56.533  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-22 18:31:56.533  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-22 18:31:56.533  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-22 18:31:56.534  1034  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:31:56.534  1034  2037 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1c3c313b mBinding = false
08-22 18:31:56.534  1034  1399 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-22 18:31:56.535  1034  1399 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-22 18:31:56.535  1034  1399 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-22 18:31:56.536  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-22 18:31:56.537  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-22 18:31:56.537  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-22 18:31:56.537  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:56.537  1034  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:56.538  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:56.538  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:56.538  1034  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@a631995
08-22 18:31:56.538  1034  1389 D LGWifiP2pService: P2pDisablingState
08-22 18:31:56.539  1034  1389 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:56.539  1034  1389 D LGWifiP2pService: p2p socket connection lost
08-22 18:31:56.539  1034  1389 D LGWifiP2pService: P2pDisabledState
08-22 18:31:56.540  1034  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-22 18:31:56.540  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-22 18:31:56.540  1966  1966 D WfdsService: WifiP2pState is changed : false
08-22 18:31:56.540  1966  2373 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-22 18:31:56.540  1966  2373 D WfdsService: Set the WFDS Monitor: false
08-22 18:31:56.541  1966  2373 D WfdsMonitor: WFDS Monitor is stopped
08-22 18:31:56.541  1966  2373 D WfdsService: STATE : WfdsDisabledState - enter
08-22 18:31:56.542  1966  2814 D CtrlSupplicant: Received on exit socket, terminate
08-22 18:31:56.542  1966  2814 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-22 18:31:56.542  1966  2814 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-22 18:31:56.542  1966  2814 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-22 18:31:56.542  1966  2374 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-22 18:31:56.543  1034  1096 D BluetoothManagerService: Message: 2
,08-22 18:31:56.545  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-22 18:31:56.545  1966  2373 W WfdsService: DefaultState - msg [9445378] is not handled
08-22 18:31:56.545  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-22 18:31:56.546  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-22 18:31:56.546  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:56.546  1034  1096 D BluetoothManagerService: Sending off request.
08-22 18:31:56.547   315   894 D CommandListener: Clearing all IP addresses on wlan0
08-22 18:31:56.549  3763  3782 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-22 18:31:56.550  3763  3866 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-22 18:31:56.550  3763  3866 D BluetoothAdapterProperties: Setting state to 13
08-22 18:31:56.550  3763  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 18:31:56.550  3763  3866 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 18:31:56.550  3763  3866 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.551  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:56.551  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:31:56.551  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-22 18:31:56.551  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:31:56.551  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-22 18:31:56.551  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:56.551  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:56.552  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-22 18:31:56.553  6211  6309 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-22 18:31:56.554  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 18:31:56.554  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:31:56.555  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:31:56.555  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:31:56.555  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-22 18,:31:56.556  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:31:56.556  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.556  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:56.556  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:31:56.556  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:56.557  6211  6309 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:31:56.559  1034  1399 D WifiNative-p2p0: doBoolean: TERMINATE
08-22 18:31:56.560  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-22 18:31:56.560  1034  1399 D WifiNative-p2p0: TERMINATE: returned true
08-22 18:31:56.560  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:31:56.560  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:31:56.560  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-22 18:31:56.563  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:31:56.563  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:31:56.563  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-22 18:31:56.566  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:31:56.567  3763  4247 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:56.568  3763  3953 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-22 18:31:56.568  3763  4247 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
,08-22 18:31:56.568  3763  3871 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:31:56.568  3763  3866 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-22 18:31:56.569  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-22 18:31:56.569  3763  3953 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-22 18:31:56.569  3763  4264 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:31:56.569  6211  6309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 766)
08-22 18:31:56.569  3763  3866 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-22 18:31:56.570  3763  4188 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:31:56.571  3763  4271 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-22 18:31:56.571  3763  4176 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-22 18:31:56.571  3763  4248 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:31:56.571  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:56.575  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-22 18:31:56.576  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-22 18:31:56.577  3763  3953 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-22 18:31:56.577  3763  3763 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:56.577  3763  3763 D BluetoothMapService: STATE_TURNING_OFF
08-22 18:31:56.577  3763  3763 V BluetoothMapService: Handler(): got msg=4
08-22 18:31:56.577  3763  3763 D BluetoothMapService: MAP Service closeService in
08-22 18:31:56.577  3763  3763 D BluetoothMapMasInstance: MAP Service shutdown
,08-22 18:31:56.577  3763  3763 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-22 18:31:56.577  3763  3763 V BluetoothMapService: MAP Service closeService out
08-22 18:31:56.578  3763  3763 V BtOppService: Receiver DISABLED_ACTION 
08-22 18:31:56.578  3763  3763 I BtOppRfcommListener: stopping Accept Thread
08-22 18:31:56.578  3763  3763 V BtOppRfcommListener: close mBtServerSocket
08-22 18:31:56.578  3763  3763 V BtOppRfcommListener: waiting for thread to terminate
08-22 18:31:56.578  3763  4248 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 18:31:56.578  3763  3763 V BtOppRfcommListener: done waiting for thread to terminate
08-22 18:31:56.580  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.580  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:56.580  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:31:56.580  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:56.581  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:56.581  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:56.582  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 18:31:56.582  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:31:56.582  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:31:56.582  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:56.582  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:31:56.607  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-22 18:31:56.617  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6329 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-22 18:31:56.619  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-22 18:31:56.620  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.620  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.621  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.623  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.636  2649  2649 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-22 18:31:56.636  2649  2649 I wpa_supplicant: monitor socket send errors count : 1
08-22 18:31:56.636  2649  2649 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1966-2\x00 that cannot receive messages
,08-22 18:31:56.639  1034  2808 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-22 18:31:56.639  1034  2808 D WifiMonitor: Dropping event because (p2p0) is stopped
08-22 18:31:56.643  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:31:56.664  1034  1947 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6347 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-22 18:31:56.667  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-22 18:31:56.667  3763  3763 V BtOppService: onDestroy
08-22 18:31:56.671  2649  2649 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 18:31:56.673  2649  2649 W wpa_supplicant: USIM:  scard_deinit function
08-22 18:31:56.673  1034  1096 D Tethering: InitialState.processMessage what=4
08-22 18:31:56.673  1034  2808 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-22 18:31:56.673  1034  2808 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 18:31:56.673  3763  3763 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-22 18:31:56.673  1034  2808 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 18:31:56.674  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:31:56.674  1034  2808 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-22 18:31:56.674  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-22 18:31:56.674  1034  2808 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:31:56.674  1034  2808 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:31:56.674  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 18:31:56.675  1034  1399 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185578
08-22 18:31:56.676  1034  1399 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185579
08-22 18:31:56.677  1034  1399 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=185580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-22 18:31:56.677   315  6357 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-22 18:31:56.677  1034  1399 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=185581  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-22 18:31:56.678  1034  1399 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:31:56.678  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-22 18:31:56.679  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-22 18:31:56.689  6329  6329 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:31:56.689  6329  6329 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-22 18:31:56.690  6329  6329 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-22 18:31:56.690  6329  6329 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-22 18:31:56.691  6329  6329 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-22 18:31:56.691  6329  6329 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 18:31:56.750  6347  6347 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-22 18:31:56.758  6347  6347 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-22 18:31:56.758  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:31:56.760  1034  2127 I ActivityManager: Killing 4868:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-22 18:31:56.797  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-22 18:31:56.818  2649  2649 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-22 18:31:56.819  1034  2808 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-22 18:31:56.819  1034  2808 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-22 18:31:56.819  1034  2808 D WifiMonitor: Disconnecting from the supplicant, no more events
08-22 18:31:56.820  1034  1399 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
,08-22 18:31:56.829  1034  1947 W libprocessgroup: failed to open /acct/uid_10014/pid_4868/cgroup.procs: No such file or directory
08-22 18:31:56.851  3763  3763 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-22 18:31:56.852  3763  3763 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:56.852  3763  3763 V BluetoothPbapReceiver: ***********state = 13
,08-22 18:31:56.856  3763  3763 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-22 18:31:56.859  3763  3763 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:56.859  3763  3763 V BluetoothPbapService: state: 13
08-22 18:31:56.859  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:31:56.859  3763  3763 V BluetoothPbapService: Pbap Service closeService in
08-22 18:31:56.862  3763  3763 V BluetoothPbapService: successfully stopped pbap service
08-22 18:31:56.862  3763  3763 V BluetoothPbapService: Pbap Service closeService out
08-22 18:31:56.862  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:31:56.862  3763  3763 V BluetoothPbapService: Pbap Service onDestroy
08-22 18:31:56.862  3763  3763 V BluetoothPbapService: Pbap Service closeService in
08-22 18:31:56.863  3763  3763 V BluetoothPbapService: Pbap Service closeService out
08-22 18:31:56.863  3763  3763 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-22 18:31:56.906  6329  6329 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:31:56.906  6329  6329 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 18:31:56.921  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:31:56.929  1034  1096 D BluetoothManagerService: Message: 20
08-22 18:31:56.929  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d1a0bed:true
08-22 18:31:56.938  1034  2037 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6369 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-22 18:31:56.940  1034  1399 D WifiOffDelayIfNotUsed: stopMonitoring
08-22 18:31:56.940  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:31:56.940  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:31:56.940  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-22 18:31:56.943  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:31:56.945  1966  1966 D WfdsService: Supplicant Connection state is changed : false
08-22 18:31:56.945  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-22 18:31:56.945  2472  2472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:31:56.945  1966  2373 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-22 18:31:56.946  1966  2373 D WfdsService: Set the WFDS Monitor: false
08-22 18:31:56.946  1966  2373 D WfdsMonitor: WFDS Monitor is stopped
08-22 18:31:56.948  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.948  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-22 18:31:56.948  1034  1443 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-22 18:31:56.949  1034  1443 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-22 18:31:56.950  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:56.954  1034  1096 D BluetoothManagerService: Message: 30
,08-22 18:31:56.962  1034  1096 D BluetoothManagerService: Message: 30
08-22 18:31:56.965  6329  6329 D LocalBluetoothProfileManager: Adding local MAP profile
08-22 18:31:56.967  6329  6329 D BluetoothMap: Create BluetoothMap proxy object
08-22 18:31:56.967  1034  1096 D BluetoothManagerService: Message: 30
,08-22 18:31:56.973  1034  1096 D BluetoothManagerService: Message: 30
08-22 18:31:56.974  6329  6329 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-22 18:31:56.977  6329  6329 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-22 18:31:56.983  6211  6211 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 18:31:56.997  6329  6329 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-22 18:31:57.001  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-22 18:31:57.013  6329  6329 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:31:57.022  6329  6329 D BluetoothInputDevice: Proxy object connected
08-22 18:31:57.025  6329  6329 D HidProfile: Bluetooth service connected
,08-22 18:31:57.029  6329  6329 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:31:57.029  6329  6329 D PanProfile: Bluetooth service connected
08-22 18:31:57.030  6329  6329 D BluetoothMap: Proxy object connected
08-22 18:31:57.031  6329  6329 D MapProfile: Bluetooth service connected
08-22 18:31:57.031  6329  6329 D BluetoothMap: getConnectedDevices()
08-22 18:31:57.032  6329  6329 D BluetoothMap: Bluetooth is Not enabled
08-22 18:31:57.032  6329  6329 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-22 18:31:57.069  1034  2127 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6392 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-22 18:31:57.070  1034  2127 I ActivityManager: Killing 5660:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-22 18:31:57.127  1034  1574 W libprocessgroup: failed to open /acct/uid_10004/pid_5660/cgroup.procs: No such file or directory
08-22 18:31:57.127  6369  6369 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-22 18:31:57.128  6369  6369 W LG Account v2.2: No ProfileInfo entries
08-22 18:31:57.129  6369  6369 I LG Account v2.2: isEnabled: false
,08-22 18:31:57.129  6369  6369 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-22 18:31:57.129  6369  6369 I Feature : [Lifetracker]Country: EU
08-22 18:31:57.129  6369  6369 I Feature : [Lifetracker]Operator: OPEN
08-22 18:31:57.130  6369  6369 I Feature : [Lifetracker]Ranking support: false
08-22 18:31:57.130  6369  6369 I Feature : [Lifetracker]Comfort support: false
08-22 18:31:57.130  6369  6369 I Feature : [Lifetracker]Accessory: true
08-22 18:31:57.130  6369  6369 I Feature : [Lifetracker]Health device: true
08-22 18:31:57.130  6369  6369 I Feature : [Lifetracker]Extra Pedometer: false
08-22 18:31:57.131  6369  6369 I Feature : [Lifetracker]Blood glucose device: false
08-22 18:31:57.131  6369  6369 I Feature : [Lifetracker]Device Number: 3
08-22 18:31:57.144  6329  6329 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-22 18:31:57.151  6329  6329 D BluetoothPermissionRequest: onReceive
08-22 18:31:57.153  6329  6329 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-22 18:31:57.168  6392  6392 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-22 18:31:57.171  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-22 18:31:57.174  1034  2127 I ActivityManager: Killing 5808:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-22 18:31:57.209  3763  3763 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-22 18:31:57.209  3763  3763 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-22 18:31:57.211  3763  3763 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-22 18:31:57.212  1034  1776 W libprocessgroup: failed to open /acct/uid_10008/pid_5808/cgroup.procs: No such file or directory
08-22 18:31:57.220  6392  6392 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-22 18:31:57.220  3763  3763 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:57.221  3763  3763 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-22 18:31:57.224  3763  3763 V BluetoothFtpService: Ftp Service onStartCommand
08-22 18:31:57.225  3763  3763 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:57.225  3763  3763 V BluetoothFtpService: Ftp Service closeService
08-22 18:31:57.226  3763  3763 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-22 18:31:57.227  3763  3763 V BluetoothFtpService: successfully stopped ftp service
08-22 18:31:57.228  3763  3763 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:31:57.228  3763  3763 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:31:57.228  3763  3763 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:31:57.228  3763  3763 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:57.229  3763  3763 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-22 18:31:57.229  3763  3763 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-22 18:31:57.231  3763  3763 V BluetoothFtpService: Ftp Service onDestroy
08-22 18:31:57.231  3763  3763 V BluetoothFtpService: Ftp Service closeService
08-22 18:31:57.261  6392  6392 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-22 18:31:57.261  6392  6392 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-22 18:31:57.262  6392  6392 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-22 18:31:57.262  6392  6392 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-22 18:31:57.263  6392  6392 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-22 18:31:57.265  6392  6392 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-22 18:31:57.271  6392  6392 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-22 18:31:57.314  1034  2033 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6415 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-22 18:31:57.315  3763  3763 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:31:57.315  3763  3763 V BluetoothSapService: state: 13
08-22 18:31:57.316  3763  3763 V BluetoothSapService: Stopping SAP server process
08-22 18:31:57.318  3763  3763 V BluetoothSapService: Sap Service closeSapService in
08-22 18:31:57.318  3763  3763 V BluetoothSapService: Close listen Socket : 
08-22 18:31:57.318  3763  3763 V BluetoothSapService: Close rfcomm Socket : 
08-22 18:31:57.318  3763  3763 V BluetoothSapService: Close sapd  Socket : 
08-22 18:31:57.322  3763  3763 V BluetoothSapService: Sap Service closeSapService out
08-22 18:31:57.322  3763  3763 V BluetoothSapService: Sap Service onDestroy
08-22 18:31:57.322  3763  3763 V BluetoothSapService: Sap Service closeSapService in
08-22 18:31:57.322  3763  3763 V BluetoothSapService: Close listen Socket : 
08-22 18:31:57.322  3763  3763 V BluetoothSapService: Close rfcomm Socket : 
08-22 18:31:57.322  3763  3763 V BluetoothSapService: Close sapd  Socket : 
08-22 18:31:57.323  3763  3763 V BluetoothSapService: Sap Service closeSapService out
08-22 18:31:57.330  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-22 18:31:57.335  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:31:57.349  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:31:57.352  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:31:57.355  6347  6347 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-22 18:31:57.355  6347  6347 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-22 18:31:57.355  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-22 18:31:57.356  6392  6392 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-22 18:31:57.358  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:31:57.360  6392  6392 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-22 18:31:57.368  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:31:57.376  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:31:57.376  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:31:57.377  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:31:57.392  6415  6415 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-22 18:31:57.414  1034  2004 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6435 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-22 18:31:57.417  1034  2004 I ActivityManager: Killing 5839:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-22 18:31:57.510  1034  2033 W libprocessgroup: failed to open /acct/uid_10011/pid_5839/cgroup.procs: No such file or directory
,08-22 18:31:57.579  3763  3955 I bt_lpm  : LPM is already off!!!
08-22 18:31:57.579  3763  3871 D bt_hci_bdroid: cleanup
,08-22 18:31:57.580  3763  4141 I bt_userial_mct: exiting userial_read_thread
,08-22 18:31:57.580  3763  4141 D bt_userial_mct: Leaving userial_evt_read_thread()
08-22 18:31:57.581  3763  3953 W bt-btif : ag scb idx 1 not allocated
08-22 18:31:57.581  3763  3953 E bt-btif : BTA AG is already disabled, ignoring ...
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:31:57.581  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:31:57.582  3763  3953 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:31:57.582  3763  3953 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-22 18:31:57.585  3763  3871 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-22 18:31:57.585  3763  3955 I bt_vendor: hw_epilog_process
08-22 18:31:57.586  3763  3871 D bt_hci_bdroid: cleanup Finalizing cleanup
08-22 18:31:57.586  3763  3871 D bt_userial_mct: userial_close
08-22 18:31:57.586  3763  3871 E bt_userial_mct: pthread_join() FAILED result:3
08-22 18:31:57.586  3763  3871 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-22 18:31:57.598  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-22 18:31:57.604  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-22 18:31:57.611  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-22 18:31:57.644  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:31:57.644  6435  6455 W FormManager: Network not available. Please check & try again.
08-22 18:31:57.644  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-22 18:31:57.645  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:31:57.646  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-22 18:31:57.647  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-22 18:31:57.657  3763  3871 D bt_hci_bdroid: set_power 0
08-22 18:31:57.657  3763  3871 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-22 18:31:57.657  3763  3871 I bt_vendor: bluetooth satus is on
08-22 18:31:57.657  3763  3871 I bt_vendor: bt-vendor : resetting BT status
08-22 18:31:57.657  3763  3871 I bt_vendor: Starting hciattach daemon
08-22 18:31:57.657  3763  3871 I bt_vendor: try to set false
08-22 18:31:57.657  6435  6456 V FormManager: Network unavailable.
08-22 18:31:57.657  3763  3871 I bt_vendor: Starting hciattach daemon
08-22 18:31:57.657  3763  3871 I bt_vendor: try to set false
08-22 18:31:57.658  3763  3871 I bt_vendor: cleanup
08-22 18:31:57.659  3763  3953 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-22 18:31:57.659  3763  3871 I GKI_LINUX: GKI_exit_task 0 done
08-22 18:31:57.659  3763  3871 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-22 18:31:57.660  6435  6456 V FormManager: Network unavailable.
08-22 18:31:57.660  3763  3866 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-22 18:31:57.662  3763  3763 D HeadsetService: Received stop request...Stopping profile...
08-22 18:31:57.664  3763  3763 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-22 18:31:57.664  3763  3763 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:31:57.664  3763  3763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa75a2c
08-22 18:31:57.665  3763  3905 D HeadsetStateMachine: Exit Disconnected: -1
08-22 18:31:57.665  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-22 18:31:57.665  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-22 18:31:57.666  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-22 18:31:57.666  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-22 18:31:57.667  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-22 18:31:57.667  3763  3763 D A2dpService: Received stop request...Stopping profile...
08-22 18:31:57.667  3763  3935 D A2dpStateMachine: Exit Disconnected: -1
08-22 18:31:57.669  3763  3763 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-22 18:31:57.671  3763  3866 D BluetoothAdapterState: Stopping profile services that were post enabled
08-22 18:31:57.671  3763  3763 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-22 18:31:57.671  3763  3763 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:31:57.671  3763  3763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa75a2c
08-22 18:31:57.672  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-22 18:31:57.672  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-22 18:31:57.673  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:31:57.673  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-22 18:31:57.673  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:31:57.673  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:31:57.673  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:31:57.674  3763  3763 D HidService: Received stop request...Stopping profile...
08-22 18:31:57.674  3763  3763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa75a2c
08-22 18:31:57.674  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:31:57.676  3763  3763 D HeadsetStateMachine: Unbinding service...
,08-22 18:31:57.682  6329  6329 D BluetoothInputDevice: Proxy object disconnected
08-22 18:31:57.682  6329  6329 D HidProfile: Bluetooth service disconnected
08-22 18:31:57.683  3763  3763 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-22 18:31:57.683  3763  3763 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-22 18:31:57.683  3763  3763 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-22 18:31:57.683  3763  3763 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-22 18:31:57.683  3763  3763 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 18:31:57.683  3763  3763 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:31:57.683  3763  3763 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-22 18:31:57.683  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:31:57.684  3763  3763 D HealthService: Received stop request...Stopping profile...
08-22 18:31:57.684  3763  3763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa75a2c
08-22 18:31:57.684  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-22 18:31:57.687  3763  3763 D PanService: Received stop request...Stopping profile...
08-22 18:31:57.687  3763  3763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa75a2c
08-22 18:31:57.687  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:31:57.688  3763  3763 D BtGatt.DebugUtils: handleDebugAction() action=null
08-22 18:31:57.689  3763  3763 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 18:31:57.689  3763  3763 D BtGatt.GattService: stop()
08-22 18:31:57.689  3763  3763 D BtGatt.AdvertiseManager: advertise clients cleared
08-22 18:31:57.689  1034  1050 I ActivityManager: Killing 5856:com.android.contacts/u0a19 (adj 15): empty #17
,08-22 18:31:57.689  6329  6329 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 18:31:57.690  6329  6329 D PanProfile: Bluetooth service disconnected
08-22 18:31:57.720  1034  2033 W libprocessgroup: failed to open /acct/uid_10019/pid_5856/cgroup.procs: No such file or directory
08-22 18:31:57.720  3763  3763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa75a2c
,08-22 18:31:57.721  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:31:57.724  3763  3763 D BluetoothMapService: Received stop request...Stopping profile...
08-22 18:31:57.724  3763  3763 D BluetoothMapService: stop()
08-22 18:31:57.725  3763  3763 D BluetoothMapEmailAppObserver: deinitObservers()
08-22 18:31:57.725  3763  3763 D BluetoothMapEmailAppObserver: removeReceiver()
08-22 18:31:57.730  3763  3763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa75a2c
08-22 18:31:57.733  3763  3763 I BluetoothA2dpServiceJni: cleanupNative
08-22 18:31:57.733  3763  3937 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-22 18:31:57.733  6329  6329 D BluetoothMap: Proxy object disconnected
08-22 18:31:57.733  6329  6329 D MapProfile: Bluetooth service disconnected
08-22 18:31:57.733  3763  3763 I GKI_LINUX: GKI_exit_task 2 done
08-22 18:31:57.734  3763  3763 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-22 18:31:57.734  3763  3763 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 18:31:57.734  3763  3763 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 18:31:57.735  3763  3763 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 18:31:57.735  3763  3763 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 18:31:57.735  3763  3763 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 18:31:57.736  3763  3763 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 18:31:57.736  3763  3763 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 18:31:57.737  4250  6460 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:31:57.738  3763  3763 V BluetoothMapService: Handler(): got msg=4
08-22 18:31:57.738  3763  3763 D BluetoothMapService: MAP Service closeService in
08-22 18:31:57.738  3763  3763 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-22 18:31:57.738  3763  3763 V BluetoothMapService: MAP Service closeService out
08-22 18:31:57.739  3763  3866 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-22 18:31:57.739  3763  3866 D BluetoothAdapterProperties: Setting state to 10
08-22 18:31:57.739  3763  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 18:31:57.739  3763  3763 D BluetoothMapService: cleanup()
08-22 18:31:57.740  3763  3763 D BluetoothMapService: MAP Service closeService in
08-22 18:31:57.740  3763  3763 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-22 18:31:57.740  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:31:57.740  3763  3763 V BluetoothMapService: MAP Service closeService out
08-22 18:31:57.740  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-22 18:31:57.740  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-22 18:31:57.740  3763  3866 I BluetoothAdapterState: Entering OffState
08-22 18:31:57.741  6329  6345 D BluetoothMap: onBluetoothStateChange: up=false
08-22 18:31:57.741  4250  6460 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-22 18:31:57.743  6329  6344 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 18:31:57.744  6329  6345 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 18:31:57.744  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:31:57.745  1877  3904 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 18:31:57.746  4250  6459 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-22 18:31:57.748  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:31:57.749  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:31:57.749  6329  6344 D BluetoothPan: onBluetoothStateChange on: false
08-22 18:31:57.752  1877  2557 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:31:57.752  6347  6347 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-22 18:31:57.752  6347  6347 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-22 18:31:57.753  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:31:57.753  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-22 18:31:57.754  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-22 18:31:57.757  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-22 18:31:57.758  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-22 18:31:57.758  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1c3c313b mBinding = false
08-22 18:31:57.759  1034  1096 D BluetoothManagerService: Sending unbind request.
,08-22 18:31:57.761  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-22 18:31:57.762  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-22 18:31:57.765  6435  6463 W FormManager: Network not available. Please check & try again.
08-22 18:31:57.766  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-22 18:31:57.769  3763  3871 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-22 18:31:57.769  3763  3763 I GKI_LINUX: GKI_exit_task 1 done
08-22 18:31:57.769  3763  3763 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-22 18:31:57.769  3763  3763 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 18:31:57.771  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:57.771  1966  2199 D LGBluetoothAPIService: Message: 2
08-22 18:31:57.771  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:57.771  1966  2199 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@14d28449 mBinding = false
08-22 18:31:57.771  1966  2199 D LGBluetoothAPIService: Sending unbind request.
08-22 18:31:57.772  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:57.772  3763  3763 I art     : --- WEIRD: removing null entry 246
08-22 18:31:57.772  3763  3763 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-22 18:31:57.772  3763  3763 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-22 18:31:57.776  1601  1601 D BluetoothAdapter: 12170710: getState() :  mService = null. Returning STATE_OFF
08-22 18:31:57.776  1601  1601 D BluetoothAdapter: 12170710: getState() :  mService = null. Returning STATE_OFF
08-22 18:31:57.777  3763  3763 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-22 18:31:57.779  6435  6464 V FormManager: Network unavailable.
08-22 18:31:57.780  3763  3763 I art     : System.exit called, status: 0
08-22 18:31:57.780  3763  3763 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-22 18:31:57.781  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:31:57.782  6329  6329 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-22 18:31:57.783  6329  6329 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-22 18:31:57.783  6329  6329 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-22 18:31:57.787  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-22 18:31:57.787  6435  6464 V FormManager: Network unavailable.
08-22 18:31:57.804   323   323 V AudioFlinger: 3763 died, releasing its sessions
08-22 18:31:57.804   323   323 V AudioFlinger:  pid 1877 @ 0
,08-22 18:31:57.804   323   323 V AudioFlinger:  pid 3130 @ 1
,08-22 18:31:57.804   323   323 V AudioFlinger:  pid 3130 @ 2
08-22 18:31:57.804  6329  6329 D DockEventReceiver: finishStartingService: stopping service
08-22 18:31:57.806  6329  6329 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-22 18:31:57.817  1034  2004 I ActivityManager: Process com.android.bluetooth (pid 3763) has died
08-22 18:31:57.817  1034  2004 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-22 18:31:57.824  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:31:57.848  6329  6329 D BluetoothPermissionRequest: onReceive
,08-22 18:31:57.852  6392  6392 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-22 18:31:57.852  6329  6329 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-22 18:31:57.853  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-22 18:31:57.853  6329  6329 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-22 18:31:57.854  6392  6392 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-22 18:31:57.859  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-22 18:31:57.896  6392  6392 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:31:57.897  6392  6392 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 18:31:57.909  6392  6392 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-22 18:31:57.912  6392  6392 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-22 18:31:57.912  6392  6392 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-22 18:31:57.912  6392  6392 V SoundPool: doLoad: loading sample sampleID=1
08-22 18:31:57.913  6392  6392 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-22 18:31:57.914  6392  6477 V SoundPool: Start decode
08-22 18:31:57.914  6392  6477 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-22 18:31:57.917   323  1396 V MediaPlayerService: decode(22, 10857164, 17813)
08-22 18:31:57.917   323  1396 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-22 18:31:57.917   323  1396 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-22 18:31:57.917   323  1396 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-22 18:31:57.917   323  1396 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-22 18:31:57.917   323  1396 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-22 18:31:57.917   323  1396 V MediaPlayerService: player type = 3
08-22 18:31:57.917   323  1396 V AwesomePlayer: AwesomePlayer create()
08-22 18:31:57.918  1034  2033 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6474 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-22 18:31:57.918   323  1396 V AwesomePlayer: reset_l() 
08-22 18:31:57.918   323  1396 V AwesomePlayer: cancelPlayerEvents
08-22 18:31:57.918   323  1396 V AwesomePlayer: setAudioSink() 
08-22 18:31:57.918   323  1396 V AwesomePlayer: reset_l() 
08-22 18:31:57.918   323  1396 V AudioCache: notify(0xb10113c0, 8, 0, 0)
08-22 18:31:57.918   323  1396 V AudioCache: ignored
08-22 18:31:57.918   323  1396 V AwesomePlayer: cancelPlayerEvents
08-22 18:31:57.919   323  1396 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-22 18:31:57.919   323  1396 V AwesomePlayer: setDataSource_l dataSource
08-22 18:31:57.919   323  1396 V LGParserOSAL: SniffLGParser start
08-22 18:31:57.919   323  1396 V LGParserOSAL: MainType:5, SubType=0
08-22 18:31:57.919   323  1396 V LGParserOSAL: #### check Mime : application/ogg
08-22 18:31:57.919   323  1396 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-22 18:31:57.919   323  1396 E MediaExtractor: Use LGExtractor :application/ogg 
08-22 18:31:57.926  6121  6121 D UEI.SmartControl: QS Service created
,08-22 18:31:57.928  6392  6392 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-22 18:31:57.933  6392  6392 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-22 18:31:57.933  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-22 18:31:57.953   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 36.698ms
08-22 18:31:57.954  6392  6392 V LGMDMManager: Create singleton instance
,08-22 18:31:57.964  6121  6121 I UEI.SmartControl: Service initServices...
08-22 18:31:57.964  6121  6121 D UEI.SmartControl: QS start get config
08-22 18:31:57.976   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.628ms
,08-22 18:31:57.980   323  1396 V LGParserOSAL: supported mime: application/ogg
08-22 18:31:57.980   323  1396 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-22 18:31:57.980   323  1396 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-22 18:31:57.980   323  1396 V AwesomePlayer: mBitrate = -1 bits/sec
08-22 18:31:57.980   323  1396 V AwesomePlayer: AudioTrack Setting
08-22 18:31:57.980   323  1396 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-22 18:31:57.980   323  1396 V AwesomePlayer: setAudioSource() 
08-22 18:31:57.980   323  1396 V MediaPlayerService: prepare
08-22 18:31:57.980   323  1396 V AwesomePlayer: prepareAsync_l() 
08-22 18:31:57.980   323  1396 V MediaPlayerService: wait for prepare
08-22 18:31:57.981   323  6493 V AwesomePlayer: onPrepareAsyncEvent() 
08-22 18:31:57.981   323  6493 V AwesomePlayer: initAudioDecoder() 
08-22 18:31:57.981   323  6493 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-22 18:31:57.981   323  6493 V AudioSystem: isOffloadSupported()
08-22 18:31:57.981   323  6493 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-22 18:31:57.981   323  6493 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-22 18:31:57.981   323  6493 I AudioFlinger: isAudioPlaybackHookOn() false
08-22 18:31:57.981   323  6493 V AwesomePlayer: getUseOffload() = 0 
08-22 18:31:57.982   323  6493 V OMXCodec: OMXCodec::Create
08-22 18:31:57.982   323  6493 V OMXCodec: findMatchingCodecs()
08-22 18:31:57.982   323  6493 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-22 18:31:57.982   323  6493 V OMXCodec: matchingCodecs.size()=1
08-22 18:31:57.982   323  6493 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-22 18:31:57.986   323  6493 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-22 18:31:57.986   323  6493 V LGCodecAdapter: LG Codec Adapter start
08-22 18:31:57.986   323  6493 V OMXCodec: OMXCodec Createtor
08-22 18:31:57.986   323  6493 V OMXCodec: setComponentRole
08-22 18:31:57.986   323  6493 V OMXCodec: configureCodec protected=0
08-22 18:31:57.986   323  6493 V LGCodecAdapter: called getLGCodecSpecificData
08-22 18:31:57.986   323  6493 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-22 18:31:57.986   323  6493 V LGCodecOSAL: Called LGconfigureCodecMETA
08-22 18:31:57.986   323  6493 V LGCodecOSAL: Called LGconfigureCodecMSG
08-22 18:31:57.986   323  6493 V LGCodecOSAL: Not support LGCodec
,08-22 18:31:57.986   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-22 18:31:57.986   323  6493 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-22 18:31:57.986   323  6493 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-22 18:31:57.986   323  6493 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-22 18:31:57.986   323  6493 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-22 18:31:57.986   323  6493 V AudioSystem: isOffloadSupported()
08-22 18:31:57.986   323  6493 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-22 18:31:57.986   323  6493 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,08-22 18:31:57.986   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-22 18:31:57.986   323  6493 V OMXCodec: init()
08-22 18:31:57.986   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-22 18:31:57.986   323  6493 V OMXCodec: allocateBuffers
08-22 18:31:57.986   323  6493 V OMXCodec: allocateBuffersOnPort portIndex=0
08-22 18:31:57.986   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c01f0 on input port
08-22 18:31:57.987   323  6493 V OMXCodec: allocateBuffersOnPort portIndex=1
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on output port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0ec0 on output port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0f60 on output port
08-22 18:31:57.987   323  6493 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0fb0 on output port
08-22 18:31:57.987   323  6493 V OMXCodec: init() mAsyncCompletion wait!!! 
08-22 18:31:57.987   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-22 18:31:57.987   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-22 18:31:57.987   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-22 18:31:57.987   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-22 18:31:57.987   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-22 18:31:57.988   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-22 18:31:57.989   323  6493 V OMXCodec: init() mAsyncCompletion wait free! 
08-22 18:31:57.989   323  6493 V AwesomePlayer: finishAsyncPrepare_l() 
08-22 18:31:57.989   323  6493 V AudioCache: notify(0xb10113c0, 5, 0, 0)
08-22 18:31:57.989   323  6493 V AudioCache: ignored
08-22 18:31:57.989   323  6493 V AudioCache: notify(0xb10113c0, 1, 0, 0)
08-22 18:31:57.989   323  6493 V AudioCache: prepared
08-22 18:31:57.990   323  1396 V AudioCache: wait - success
08-22 18:31:57.990   323  1396 V MediaPlayerService: start
08-22 18:31:57.990   323  1396 V AwesomePlayer: play_l() 
08-22 18:31:57.990   323  1396 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-22 18:31:57.990   323  1396 V AwesomePlayer: createAudioPlayer_l
08-22 18:31:57.990   323  1396 V AwesomePlayer: seekAudioIfNecessary_l() 
08-22 18:31:57.990   323  1396 V AwesomePlayer: startAudioPlayer_l() 
08-22 18:31:57.990   323  1396 D AudioPlayer: start of Playback, useOffload 0
08-22 18:31:57.990   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-22 18:31:57.990   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-22 18:31:57.993   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-22 18:31:57.993   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-22 18:31:57.993   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-22 18:31:57.993   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-22 18:31:57.993   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-22 18:31:57.993   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-22 18:31:,57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550224
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974551744
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974551904
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974551984
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-22 18:31:57.994   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-22 18:31:57.995   323  6495 V OMXCodec: allocateBuffersOnPort portIndex=1
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0f60 on output port
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0ec0 on output port
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on output port
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on output port
08-22 18:31:57.995   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-22 18:31:57.996   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-22 18:31:57.997   323  1396 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-22 18:31:57.997   323  1396 V AudioCache: notify(0xb10113c0, 6, 0, 0)
08-22 18:31:57.997   323  1396 V AudioCache: ignored
08-22 18:31:57.998   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 20.941ms
08-22 18:31:57.998   323  1396 V MediaPlayerService: wait for playback complete
08-22 18:31:58.000   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.000   323  6496 V AudioCache: memcpy(0xaf0f9000, 0xb57fd000, 4096)
,08-22 18:31:58.003   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.003   323  6496 V AudioCache: memcpy(0xaf0fa000, 0xb57fd000, 4096)
08-22 18:31:58.004   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.004   323  6496 V AudioCache: memcpy(0xaf0fb000, 0xb57fd000, 4096)
08-22 18:31:58.005   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.005   323  6496 V AudioCache: memcpy(0xaf0fc000, 0xb57fd000, 4096)
08-22 18:31:58.006   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.006   323  6496 V AudioCache: memcpy(0xaf0fd000, 0xb57fd000, 4096)
08-22 18:31:58.007   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.007   323  6496 V AudioCache: memcpy(0xaf0fe000, 0xb57fd000, 4096)
08-22 18:31:58.008   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.008   323  6496 V AudioCache: memcpy(0xaf0ff000, 0xb57fd000, 4096)
08-22 18:31:58.009   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.009   323  6496 V AudioCache: memcpy(0xaf100000, 0xb57fd000, 4096)
08-22 18:31:58.010   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.010   323  6496 V AudioCache: memcpy(0xaf101000, 0xb57fd000, 4096)
08-22 18:31:58.010   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.010   323  6496 V AudioCache: memcpy(0xaf102000, 0xb57fd000, 4096)
08-22 18:31:58.011   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.011   323  6496 V AudioCache: memcpy(0xaf103000, 0xb57fd000, 4096)
08-22 18:31:58.012   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.012   323  6496 V AudioCache: memcpy(0xaf104000, 0xb57fd000, 4096)
08-22 18:31:58.012   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.012   323  6496 V AudioCache: memcpy(0xaf105000, 0xb57fd000, 4096)
08-22 18:31:58.013   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.013   323  6496 V AudioCache: memcpy(0xaf106000, 0xb57fd000, 4096)
08-22 18:31:58.014   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.014   323  6496 V AudioCache: memcpy(0xaf107000, 0xb57fd000, 4096)
08-22 18:31:58.015   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.015   323  6496 V AudioCache: memcpy(0xaf108000, 0xb57fd000, 4096)
08-22 18:31:58.016   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.016   323  6496 V AudioCache: memcpy(0xaf109000, 0xb57fd000, 4096)
08-22 18:31:58.016   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.016   323  6496 V AudioCache: memcpy(0xaf10a000, 0xb57fd000, 4096)
08-22 18:31:58.017  6474  6474 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-22 18:31:58.017   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.017   323  6496 V AudioCache: memcpy(0xaf10b000, 0xb57fd000, 4096)
08-22 18:31:58.017  6474  6474 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-22 18:31:58.018  6474  6474 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-22 18:31:58.018   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.018   323  6496 V AudioCache: memcpy(0xaf10c000, 0xb57fd000, 4096)
08-22 18:31:58.018  6474  6474 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-22 18:31:58.019   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.019   323  6496 V AudioCache: memcpy(0xaf10d000, 0xb57fd000, 4096)
08-22 18:31:58.019   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.019   323  6496 V AudioCache: memcpy(0xaf10e000, 0xb57fd000, 4096)
08-22 18:31:58.020   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.020   323  6496 V AudioCache: memcpy(0xaf10f000, 0xb57fd000, 4096)
08-22 18:31:58.021   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.021   323  6496 V AudioCache: memcpy(0xaf110000, 0xb57fd000, 4096)
08-22 1,8:31:58.022   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.022   323  6496 V AudioCache: memcpy(0xaf111000, 0xb57fd000, 4096)
08-22 18:31:58.023   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.023   323  6496 V AudioCache: memcpy(0xaf112000, 0xb57fd000, 4096)
08-22 18:31:58.023   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.024   323  6496 V AudioCache: memcpy(0xaf113000, 0xb57fd000, 4096)
08-22 18:31:58.024   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.024   323  6496 V AudioCache: memcpy(0xaf114000, 0xb57fd000, 4096)
08-22 18:31:58.024   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.024   323  6496 V AudioCache: memcpy(0xaf115000, 0xb57fd000, 4096)
08-22 18:31:58.024   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.024   323  6496 V AudioCache: memcpy(0xaf116000, 0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: memcpy(0xaf117000, 0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: memcpy(0xaf118000, 0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: memcpy(0xaf119000, 0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.027   323  6496 V AudioCache: memcpy(0xaf11a000, 0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: memcpy(0xaf11b000, 0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: memcpy(0xaf11c000, 0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: memcpy(0xaf11d000, 0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.029   323  6496 V AudioCache: memcpy(0xaf11e000, 0xb57fd000, 4096)
08-22 18:31:58.030   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.030   323  6496 V AudioCache: memcpy(0xaf11f000, 0xb57fd000, 4096)
08-22 18:31:58.031   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.031   323  6496 V AudioCache: memcpy(0xaf120000, 0xb57fd000, 4096)
08-22 18:31:58.031   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.031   323  6496 V AudioCache: memcpy(0xaf121000, 0xb57fd000, 4096)
08-22 18:31:58.032   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.032   323  6496 V AudioCache: memcpy(0xaf122000, 0xb57fd000, 4096)
08-22 18:31:58.033   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.033   323  6496 V AudioCache: memcpy(0xaf123000, 0xb57fd000, 4096)
08-22 18:31:58.033   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.033   323  6496 V AudioCache: memcpy(0xaf124000, 0xb57fd000, 4096)
08-22 18:31:58.034   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.034   323  6496 V AudioCache: memcpy(0xaf125000, 0xb57fd000, 4096)
08-22 18:31:58.034  6474  6474 D BluetoothAdapterApp: Loading JNI Library
,08-22 18:31:58.034  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-22 18:31:58.035   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.035   323  6496 V AudioCache: memcpy(0xaf126000, 0xb57fd000, 4096)
08-22 18:31:58.035  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-22 18:31:58.036   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.036   323  6496 V AudioCache: memcpy(0xaf127000, 0xb57fd000, 4096)
08-22 18:31:58.036   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.036   323  6496 V AudioCache: memcpy(0xaf128000, 0xb57fd000, 4096)
08-22 18:31:58.036  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:370
08-22 18:31:58.037   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.037   323  6496 V AudioCache: memcpy(0xaf129000, 0xb57fd000, 4096)
08-22 18:31:58.037   323  6496 V AudioCache: write(0xb57fd000, 4096)
08-22 18:31:58.037   323  6496 V AudioCache: memcpy(0xaf12a000, 0xb57fd000, 4096)
08-22 18:31:58.037   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-22 18:31:58.037   323  6496 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-22 18:31:58.037   323  6496 V AwesomePlayer: postAudioEOS() 
08-22 18:31:58.038   323  6496 V AudioCache: write(0xb57fd000, 280)
08-22 18:31:58.038   323  6496 V AudioCache: memcpy(0xaf12b000, 0xb57fd000, 280)
08-22 18:31:58.039   323  6493 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-22 18:31:58.039   323  6493 V AwesomePlayer: onStreamDone
08-22 18:31:58.039   323  6493 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-22 18:31:58.039   323  6493 V AudioCache: notify(0xb10113c0, 2, 0, 0)
08-22 18:31:58.039   323  6493 V AudioCache: playback complete
08-22 18:31:58.039   323  6493 V AwesomePlayer: pause_l() 
08-22 18:31:58.039   323  6493 V AudioCache: notify(0xb10113c0, 7, 0, 0)
08-22 18:31:58.039   323  6493 V AudioCache: ignored
08-22 18:31:58.039   323  6493 V AwesomePlayer: cancelPlayerEvents
08-22 18:31:58.039   323  1396 V AudioCache: wait - success
,08-22 18:31:58.039   323  1396 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-22 18:31:58.039   323  6493 D AudioPlayer: Pause Playback at 1068125
08-22 18:31:58.040   323  1396 V AwesomePlayer: reset_l() 
08-22 18:31:58.040   323  1396 V AudioCache: notify(0xb10113c0, 8, 0, 0)
08-22 18:31:58.040   323  1396 V AudioCache: ignored
08-22 18:31:58.040   323  1396 V AwesomePlayer: cancelPlayerEvents
08-22 18:31:58.040   323  1396 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-22 18:31:58.040   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-22 18:31:58.040   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-22 18:31:58.040   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-22 18:31:58.040   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c01f0 on port 0
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 1
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-22 18:31:58.040   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c08d0 on port 1
,08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0ec0 on port 1
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0f60 on port 1
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-22 18:31:58.041   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-22 18:31:58.041   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-22 18:31:58.041   323  6495 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-22 18:31:58.041   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-22 18:31:58.041   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-22 18:31:58.041   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,08-22 18:31:58.042   323  1396 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-22 18:31:58.042   323  1396 D AudioPlayer: AudioPlayer releasing audio source
08-22 18:31:58.042   323  1396 D AudioPlayer: AudioPlayer done releasing audio source
08-22 18:31:58.042   323  1396 V AwesomePlayer: reset_l() 
08-22 18:31:58.042   323  1396 V AwesomePlayer: cancelPlayerEvents
08-22 18:31:58.042   323  1396 V AwesomePlayer: ~AwesomePlayer call
,08-22 18:31:58.042   323  1396 V AwesomePlayer: reset_l() 
,08-22 18:31:58.042   323  1396 V AwesomePlayer: cancelPlayerEvents
08-22 18:31:58.043  6392  6477 V SoundPool: close(31)
08-22 18:31:58.043  6392  6477 V SoundPool: pointer = 0x9fff5000, size = 205080, sampleRate = 48000, numChannels = 2
08-22 18:31:58.063  6474  6474 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3915a33d Instance Count = 1
,08-22 18:31:58.067  6474  6474 D BluetoothAdapterApp: onCreate
08-22 18:31:58.083  6474  6474 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-22 18:31:58.083  6474  6474 D ProfileConfigQcom: Adding HeadsetService
08-22 18:31:58.083  6474  6474 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-22 18:31:58.083  6474  6474 D ProfileConfigQcom: Adding A2dpService
08-22 18:31:58.083  6474  6474 D ProfileConfigQcom: [BTUI] HidService is supported
08-22 18:31:58.083  6474  6474 D ProfileConfigQcom: Adding HidService
08-22 18:31:58.084  6474  6474 D ProfileConfigQcom: [BTUI] HealthService is supported
08-22 18:31:58.084  6474  6474 D ProfileConfigQcom: Adding HealthService
08-22 18:31:58.084  6474  6474 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-22 18:31:58.084  6474  6474 D ProfileConfigQcom: [BTUI] PanService is supported
08-22 18:31:58.085  6474  6474 D ProfileConfigQcom: Adding PanService
08-22 18:31:58.085  6474  6474 D ProfileConfigQcom: [BTUI] GattService is supported
08-22 18:31:58.085  6474  6474 D ProfileConfigQcom: Adding GattService
08-22 18:31:58.085  6474  6474 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-22 18:31:58.085  6474  6474 D ProfileConfigQcom: Adding BluetoothMapService
08-22 18:31:58.086  6474  6474 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-22 18:31:58.087  6474  6474 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-22 18:31:58.091  6329  6329 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-22 18:31:58.092  6474  6474 V LGMDMManagerInternal: Create singleton instance
,08-22 18:31:58.147  6474  6474 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:31:58.152  6474  6474 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:31:58.152  6474  6474 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:31:58.152  6474  6474 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:31:58.153  6474  6474 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:31:58.153  6474  6474 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-22 18:31:58.167  6415  6415 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-22 18:31:58.256  6121  6121 I UEI.SmartControl: Supports setup maps: true
,08-22 18:31:58.259  6121  6121 D UEI.SmartControl: QS start statue = true Error code = 0
08-22 18:31:58.259  6121  6121 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-22 18:31:58.259  6121  6121 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-22 18:31:58.259  6121  6121 I UEI.SmartControl: ### init IR Blaster...
08-22 18:31:58.262  6121  6121 D serial_port: Configuring serial port
08-22 18:31:58.263  6121  6121 E UEI.SmartControl: UEIBLaster setting for 616
08-22 18:31:58.263  6121  6121 I UEI.SmartControl: Setting serial record hearder size = 2
08-22 18:31:58.263  6121  6121 I UEI.SmartControl: configuring settings for MAXQ616
08-22 18:31:58.263  6121  6121 I UEI.SmartControl: Get version...
08-22 18:31:58.282  6121  6499 D UEI.SmartControl: serial port data available: 21
,08-22 18:31:58.308  6121  6121 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-22 18:31:58.309  6121  6121 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-22 18:31:58.309  6121  6121 I UEI.SmartControl: QS saving settings...
08-22 18:31:58.311  6121  6121 D UEI.SmartControl: IR Blaster version: 25672567
,08-22 18:31:58.328  6121  6499 D UEI.SmartControl: serial port data available: 4
,08-22 18:31:58.362  6121  6121 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-22 18:31:58.370  6121  6121 E UEI.SmartControl: Services init done
08-22 18:31:58.370  6121  6121 D UEI.SmartControl: QS Service init finished
08-22 18:31:58.372  6121  6121 D UEI.SmartControl: QS Service version name: 2.1.91
08-22 18:31:58.372  6121  6121 D UEI.SmartControl: QS Service version code: 201091
08-22 18:31:58.373  6121  6121 D UEI.SmartControl: Service requested: Control
08-22 18:31:58.377  6121  6121 D UEI.SmartControl: Internal service binding...
08-22 18:31:58.378  6392  6392 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-22 18:31:58.380  6121  6137 I UEI.SmartControl: ------ IControl API: 11
08-22 18:31:58.380  6121  6508 I UEI.SmartControl: Device manager: loading config....
08-22 18:31:58.380  6121  6137 D UEI.SmartControl: File observer start...
08-22 18:31:58.380  6121  6508 D UEI.SmartControl: ----------- loading internal config...
08-22 18:31:58.381  6121  6137 E UEI.SmartControl: IR Port is disabled: false
08-22 18:31:58.381  6121  6137 D UEI.SmartControl: Starting file observer...
08-22 18:31:58.382  6121  6137 I UEI.SmartControl: Registering callback...
08-22 18:31:58.386  6121  6508 E UEI.SmartControl: Loading SETTINGS...
08-22 18:31:58.386  6121  6136 I UEI.SmartControl: ------ IControl API: 19
08-22 18:31:58.386  6121  6136 I UEI.SmartControl: Registering Services Ready callback...
08-22 18:31:58.391  6121  6508 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-22 18:31:58.398  6121  6507 I UEI.SmartControl: Notify AllClients services are ready: 0
08-22 18:31:58.399  6392  6408 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-22 18:31:58.399  6392  6473 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-22 18:31:58.400  6121  6507 D UEI.SmartControl: -----service ready thread exits
08-22 18:31:58.400  6392  6473 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-22 18:31:58.400  6392  6392 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-22 18:31:58.401  6392  6392 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-22 18:31:58.401  6121  6137 I UEI.SmartControl: ------ IControl API: 8
08-22 18:31:58.403  6392  6392 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-22 18:31:58.403  6392  6392 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-22 18:31:58.403  6392  6392 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-22 18:31:58.404  6392  6392 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-22 18:31:58.404  6392  6392 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-22 18:31:58.405  6392  6392 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-22 18:31:58.406  6392  6392 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-22 18:31:58.409  6392  6392 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-22 18:31:58.410  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-22 18:31:58.411  6392  6392 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-22 18:31:58.411  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-22 18:31:58.412  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-22 18:31:58.413  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-22 18:31:58.413  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-22 18:31:58.414  6392  6392 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471883518414]
,08-22 18:31:58.418  6392  6392 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-22 18:31:58.419  1034  2029 I ActivityManager: Killing 5916:com.android.gallery3d/u0a27 (adj 15): empty #17
08-22 18:31:58.438  6392  6510 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-22 18:31:58.456  1034  2029 I ActivityManager: Killing 5883:com.lge.email/u0a23 (adj 15): empty #18
,08-22 18:31:58.487  1034  2075 W libprocessgroup: failed to open /acct/uid_10027/pid_5916/cgroup.procs: No such file or directory
,08-22 18:31:58.497  1034  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_5883/cgroup.procs: No such file or directory
08-22 18:31:58.501  6392  6392 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-22 18:31:58.504  6392  6392 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-22 18:31:58.505  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-22 18:31:58.506  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-22 18:31:58.507  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-22 18:31:58.508  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-22 18:31:58.509  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-22 18:31:58.523  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-22 18:31:59.450  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-22 18:31:59.450  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-22 18:31:59.477  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-22 18:31:59.477  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-22 18:31:59.481  1966  2165 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-22 18:31:59.481  1966  2165 D LEDHandler: Battery Level Remaining: 100%
08-22 18:31:59.481  1966  2165 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
08-22 18:31:59.482  1034  1453 D WifiController: battery changed pluggedType: 2
08-22 18:31:59.482  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-22 18:31:59.489  6103  6103 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-22 18:31:59.556  1034  2029 D WifiServiceImplEx: setWifiEnabled: true pid=6211, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-22 18:31:59.558  1034  2029 D WifiService: setWifiEnabled: true pid=6211, uid=10118
08-22 18:31:59.558  1034  2029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:31:59.581  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-22 18:31:59.581  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-22 18:31:59.581  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-22 18:31:59.585  1034  1399 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-22 18:31:59.586  1034  1399 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-22 18:31:59.588  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-22 18:31:59.588  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-22 18:31:59.588  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-22 18:31:59.588  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-22 18:31:59.589  1034  1399 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-22 18:31:59.589  1034  1399 E WifiHW  : unknown target_country: EU , set to default
08-22 18:31:59.589  1034  1399 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-22 18:31:59.589  1034  1399 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-22 18:31:59.589  1034  1399 I WifiUtil: gEnableBmps=1
08-22 18:32:00.050  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-22 18:32:00.050  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-22 18:32:00.050  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-22 18:32:00.050  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-22 18:32:00.066  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-22 18:32:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-22 18:32:00.067  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
,08-22 18:32:00.071  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-22 18:32:00.180   315   894 D SoftapController: Softap fwReload - Ok
,08-22 18:32:00.185  1034  1399 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (589ms)
08-22 18:32:00.189  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-22 18:32:00.200   315   894 D CommandListener: Setting iface cfg
08-22 18:32:00.201   315   894 D CommandListener: Trying to bring down wlan0
08-22 18:32:00.204   315  6522 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-22 18:32:00.217  1034  1096 D Tethering: InitialState.processMessage what=4
08-22 18:32:00.218  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-22 18:32:00.222   315   894 D CommandListener: Clearing all IP addresses on wlan0
08-22 18:32:00.224  1034  1399 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-22 18:32:00.225  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-22 18:32:00.218  6523  6523 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-22 18:32:00.228  6523  6523 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:00.239  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:32:00.239  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:32:00.239  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-22 18:32:00.251  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:00.255  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-22 18:32:00.266  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-22 18:32:00.277  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:00.278  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:00.278  1034  1399 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-22 18:32:00.279  1034  1399 D WifiMonitor: connecting to supplicant
,08-22 18:32:00.312  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:32:00.312  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-22 18:32:00.312  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:32:00.312  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-22 18:32:00.312  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-22 18:32:00.313  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:32:00.313  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-22 18:32:00.313  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:32:00.313  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:32:00.313  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:32:00.313  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-22 18:32:00.314  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:32:00.317  6523  6523 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-22 18:32:00.336  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:32:00.336  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-22 18:32:00.336  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:32:00.336  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-22 18:32:00.337  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-22 18:32:00.338  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:32:00.339  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-22 18:32:00.339  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:32:00.339  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:32:00.339  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:32:00.339  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:32:00.349  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:00.353  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:32:00.359  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:00.366  6523  6523 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 18:32:00.366  6523  6523 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-22 18:32:00.372  6435  6540 W FormManager: Network not available. Please check & try again.
08-22 18:32:00.372  6435  6541 V FormManager: Network unavailable.
08-22 18:32:00.374  6435  6541 V FormManager: Network unavailable.
08-22 18:32:00.468  6523  6523 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 18:32:00.488  6523  6523 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-22 18:32:00.496  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-22 18:32:00.496  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-22 18:32:00.497  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-22 18:32:00.497  1034  1399 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-22 18:32:00.498  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:00.498  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:00.499  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:00.499  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:00.500  1034  1399 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-22 18:32:00.500  1034  1399 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-22 18:32:00.501  1034  1399 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-22 18:32:00.501  1034  1399 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-22 18:32:00.501  1034  1399 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-22 18:32:00.501  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:32:00.501  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:32:00.501  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-22 18:32:00.502  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.502  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.503  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.503  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.503  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-22 18:32:00.507  1034  1399 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-22 18:32:00.508  1966  1966 D WfdService: Waiting for WifiP2p enabling
08-22 18:32:00.509  1034  1399 D WifiNative-wlan0: SET update_config 1: returned true
08-22 18:32:00.510  1034  1399 D WifiConfigStore: Loading config and enabling all networks 
08-22 18:32:00.510  1034  1399 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-22 18:32:00.510  1034  1399 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-22 18:32:00.513  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:00.513  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:00.513  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:00.513  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:00.516  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-22 18:32:00.516  1034  1443 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-22 18:32:00.517  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:00.517  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:00.517  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:00.517  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:00.517  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:00.517  1034  1399 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-22 18:32:00.528  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:00.530  1034  1399 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-22 18:32:00.530  1034  1399 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 18:32:00.535  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-22 18:32:00.539  1034  1399 D WifiStateMachine: enableVerboseLogging : level 2
08-22 18:32:00.539  1034  1399 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-22 18:32:00.540  1034  1399 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-22 18:32:00.540  1034  1399 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-22 18:32:00.540  1034  1399 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-22 18:32:00.541  1034  1399 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-22 18:32:00.541  1034  1399 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-22 18:32:00.541  1034  1399 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-22 18:32:00.541  1034  1399 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-22 18:32:00.541  1034  1399 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-22 18:32:00.542  1034  1399 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-22 18:32:00.542  1034  1399 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-22 18:32:00.542  1034  1399 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-22 18:32:00.543  1034  1399 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-22 18:32:00.543  6435  6547 W FormManager: Network not available. Please check & try again.
,08-22 18:32:00.543  1034  1399 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-22 18:32:00.545  1034  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 18:32:00.545  1034  1399 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-22 18:32:00.545  1966  1966 D WfdsService: Supplicant Connection state is changed : true
08-22 18:32:00.545  1034  1399 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-22 18:32:00.545  1034  1399 D WifiNative-HAL: Setting external_sim to 1
08-22 18:32:00.546  1034  1399 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-22 18:32:00.546  1966  2373 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-22 18:32:00.546  1966  2373 D WfdsService: Set the WFDS Monitor: true
08-22 18:32:00.546  1966  2373 D WfdsMonitor: WfdsMonitorThread create
08-22 18:32:00.546  1966  2373 D WfdsMonitor: WFDS Monitor is created and started
08-22 18:32:00.546  1966  2373 D WfdsService: WiFi: Supplicant connection re-established
08-22 18:32:00.547  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-22 18:32:00.547  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-22 18:32:00.547  6523  6523 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-22 18:32:00.547  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-22 18:32:00.547  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-22 18:32:00.547  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-22 18:32:00.547  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-22 18:32:00.548  1034  1399 D WifiNative-wlan0: SET external_sim 1: returned true
08-22 18:32:00.548  1034  1399 I WifiNative-HAL: startHal
08-22 18:32:00.548  1034  1399 D wifi    : setting scan oui 0xaf6c4fe0
08-22 18:32:00.548  1966  6549 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-22 18:32:00.548  1034  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 18:32:00.548  1034  1399 I WifiNative-HAL: startHal
08-22 18:32:00.548  1034  1399 D wifi    : setting scan oui 0xaf6c4fe0
08-22 18:32:00.548  1966  6549 E CtrlSupplicant: Succeed to open control connection
08-22 18:32:00.549  1966  6549 E CtrlSupplicant: Succeed to open monitor connection
08-22 18:32:00.549  1034  1399 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-22 18:32:00.550  6435  6548 V FormManager: Network unavailable.
08-22 18:32:00.550  1966  6549 D WfdsMonitor: Supplicant connection established
08-22 18:32:00.550  1966  2373 D WfdsService: Connected to the supplicant for wfds
08-22 18:32:00.550  1034  1399 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-22 18:32:00.550  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-22 18:32:00.550  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-22 18:32:00.550  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-22 18:32:00.551  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-22 18:32:00.551  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-22 18:32:00.551  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-22 18:32:00.551  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-22 18:32:00.551  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-22 18:32:00.551  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-22 18:32:00.552  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-22 18:32:00.552  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-22 18:32:00.552  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:00.553  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-22 18:32:00.553  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-22 18:32:00.553  6435  6548 V FormManager: Network unavailable.
08-22 18:32:00.553  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-22 18:32:00.553  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-22 18:32:00.554  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-22 18:32:00.554  6523  6523 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-22 18:32:00.554  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-22 18:32:00.554  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-22 18:32:00.554  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-22 18:32:00.555  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-22 18:32:00.556  1034  1399 E WifiNative: : [189,459,227 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-22 18:32:00.556  1034  1399 D WifiNative-wlan0: doBoolean: RECONNECT
08-22 18:32:00.557  1034  1399 D WifiNative-wlan0: RECONNECT: returned true
08-22 18:32:00.557  1034  1399 D WifiNative-wlan0: doString: [STATUS]
08-22 18:32:00.558  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1, state=3 BSSID=00:00:00:00:00:00 SSID=]
08-22 18:32:00.558  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-22 18:32:00.558  1034  1399 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-22 18:32:00.558  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-22 18:32:00.559  1034  1399 D WifiNative-wlan0: SET ps 1: returned true
08-22 18:32:00.559  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.560  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-22 18:32:00.560  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-22 18:32:00.561  1034  1399 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-22 18:32:00.561  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.561  1034  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.561  1034  1555 I WifiNative-HAL: startHal
08-22 18:32:00.561  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6c4fe0
08-22 18:32:00.561  1034  1555 D wifi    : failed to get capabilities : -3
08-22 18:32:00.561  1034  1555 E WifiScanningService: could not get scan capabilities
08-22 18:32:00.561  1034  1399 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-22 18:32:00.561  1034  1399 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-22 18:32:00.562   315   894 D CommandListener: Setting iface cfg
08-22 18:32:00.562   315   894 D CommandListener: Trying to bring up p2p0
08-22 18:32:00.562  1034  1399 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-22 18:32:00.562  1034  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-22 18:32:00.562  1034  1389 D LGWifiP2pService: P2pEnablingState
08-22 18:32:00.562  1034  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.562  1034  1389 D LGWifiP2pService: P2p socket connection successful
08-22 18:32:00.562  1034  1399 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-22 18:32:00.562  1034  1389 D LGWifiP2pService: P2pEnabledState
08-22 18:32:00.564  1034  1399 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-22 18:32:00.565  1034  1399 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-22 18:32:00.565  1034  1399 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-22 18:32:00.565  6523  6523 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-22 18:32:00.566  1034  1399 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-22 18:32:00.566  1034  1399 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-22 18:32:00.566  1034  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-22 18:32:00.567  1034  1399 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-22 18:32:00.567  1034  1399 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-22 18:32:00.567  6523  6523 E wpa_supplicant: disconnect_rssi_lvl: -100
08-22 18:32:00.567  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-22 18:32:00.567  1966  1966 D WfdsService: WifiP2pState is changed : true
08-22 18:32:00.568  1966  2373 D WfdsService: Receive the WFDS_ENABLE Method
08-22 18:32:00.568  1966  2373 D WfdsService: Set the WFDS Monitor: true
08-22 18:32:00.568  1966  2373 D WfdsService: Connected to the supplicant for wfds
08-22 18:32:00.568  1966  2373 D WfdsJNI : doCommand: WFDS_SET TRUE
08-22 18:32:00.568  6523  6523 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-22 18:32:00.568  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=189471  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-22 18:32:00.568  1966  2373 D WfdsService: selectPreferredScanChannel [36]
08-22 18:32:00.568  1966  2373 D WfdsService: STATE : WfdsEnabledState - enter: this d,evice mac 02:9a:02:7f:fb:5d
08-22 18:32:00.572  1034  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-22 18:32:00.572  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=189476  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-22 18:32:00.573  1034  1399 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-22 18:32:00.573  1034  1399 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-22 18:32:00.574  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:00.574  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:00.574  1034  1399 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-22 18:32:00.574  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-22 18:32:00.575  1034  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-22 18:32:00.576  1034  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-22 18:32:00.576  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-22 18:32:00.576  1966  1966 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-22 18:32:00.577  6523  6523 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:00.577  1966  1966 D WfdsService: isConnected: false
08-22 18:32:00.577  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-22 18:32:00.577  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:00.577  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:00.577  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:00.577  6523  6523 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-22 18:32:00.577  6523  6523 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.578  1034  1399 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-22 18:32:00.578  1034  6543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:00.578  1034  6543 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.578  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.578  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.578  6523  6523 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.578  1034  1399 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-22 18:32:00.578  1034  6543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:00.578  1034  6543 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.578  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.578  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.579  1034  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-22 18:32:00.579  1034  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-22 18:32:00.579  1034  1389 D LGWifiP2pService: before postfix = G3
08-22 18:32:00.579  1034  1389 D WifiServerServiceExt: postfix byte check : 2
08-22 18:32:00.579  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.579  1034  1389 D LGWifiP2pService: after postfix = G3
08-22 18:32:00.579  1034  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-22 18:32,:00.579  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.579  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-22 18:32:00.579  1034  1399 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-22 18:32:00.579  1034  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-22 18:32:00.579  1034  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-22 18:32:00.579  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:00.579  1034  1399 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-22 18:32:00.579  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-22 18:32:00.580  1034  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-22 18:32:00.580  1966  6549 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:00.580  1966  6549 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:00.580  1034  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-22 18:32:00.580  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-22 18:32:00.580  6523  6523 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:00.580  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-22 18:32:00.580  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:00.580  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:00.580  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:00.581  1034  1399 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-22 18:32:00.581  1034  1399 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-22 18:32:00.581  1034  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-22 18:32:00.581  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-22 18:32:00.582  1034  1399 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-22 18:32:00.582  1034  1399 D WifiNative-wlan0: doBoolean: SCAN
08-22 18:32:00.582  1034  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-22 18:32:00.582  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-22 18:32:00.583  1034  1399 D WifiNative-wlan0: SCAN: returned false
08-22 18:32:00.583  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-22 18:32:00.584  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=189487  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-22 18:32:00.585  1034  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-22 18:32:00.585  1034  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-22 18:32:00.586  1034  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-22 18:32:00.586  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-22 18:32:00.586  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=189490  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-22 18:32:00.587  1034  1399 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:00.588  1034  1399 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:00.588  1966  1966 I WfdStateTracker: handleP2pThisDeviceChanged
08-22 18:32:00.588  1966  1966 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-22 18:32:00.588  1034  1399 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:00.588  1966  1966 D WfdsService: Update P2p Interface State: 3
08-22 18:32:00.588  1034  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-22 18:32:00.589  1034  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-22 18:32:00.589  1034  1399 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:00.589  1034  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-22 18:32:00.589  1034  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-22 18:32:00.589  1034  1399 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:00.589  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:32:00.590  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-22 18:32:00.592  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.592  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:00.592  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-22 18:32:00.593  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:00.593  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-22 18:32:00.594  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:00.597  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:00.597  1034  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-22 18:32:00.598  1034  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-22 18:32:00.598  1034  1389 D LGWifiP2pService: InactiveState
08-22 18:32:00.598  1034  1389 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.598  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.598  1034  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-22 18:32:00.599  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_drive,r_cmd COUNTRY CZ
08-22 18:32:00.599  6523  6523 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:00.599  1966  6549 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-22 18:32:00.600  6523  6523 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-22 18:32:00.600  6523  6523 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.600  1966  6549 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:00.600  6523  6523 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.601  1966  6549 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-22 18:32:00.601  1034  6543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-22 18:32:00.601  1034  6543 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:00.601  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:00.601  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-22 18:32:00.601  1034  6543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:00.601  1034  6543 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.602  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.602  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.602  1034  6543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:00.602  1034  6543 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.602  1034  6543 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.602  1034  6543 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:00.602  1034  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.603  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.604  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.604  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.604  4250  6550 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-22 18:32:00.605  1966  2373 W WfdsService: DefaultState - msg [9441285] is not handled
08-22 18:32:00.607  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:00.607  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:00.607  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:00.607  1034  1034 E WifiServerServiceExt: No p2p device connected
08-22 18:32:00.608  6103  6103 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-22 18:32:00.608  6103  6103 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-2,2 18:32:00.608  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:00.609  4250  6551 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:32:00.609  4250  6551 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-22 18:32:00.613  6103  6103 V [BNRBootReceiver]: Boot Receiver Return
,08-22 18:32:00.617  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:00.623  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:00.629  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:00.635  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:00.636  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:00.637  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:32:00.641  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:00.651  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:00.657  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:00.670  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:00.671  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-22 18:32:00.674  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:32:01.140  6523  6523 E wpa_supplicant: USIM:  scard_init function
08-22 18:32:01.142  6523  6523 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-22 18:32:01.149  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-22 18:32:01.149  1034  6543 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-22 18:32:01.150  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-22 18:32:01.150  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
08-22 18:32:01.151  1034  1399 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-22 18:32:01.150  1034  6543 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-22 18:32:01.151  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-22 18:32:01.151  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-22 18:32:01.152  1034  1399 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-22 18:32:01.152  1034  1399 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-22 18:32:01.153  1034  1399 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-22 18:32:01.153  1034  1399 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-22 18:32:01.177  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=190080  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-22 18:32:01.183  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=190086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-22 18:32:01.186  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.186  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.186  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-22 18:32:01.187  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:01.187  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:01.190  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:01.196  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:01.196  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-22 18:32:01.200  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-22 18:32:01.206  6329  6329 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-22 18:32:01.215  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:01.229  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:01.237  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:01.245  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:01.245  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-22 18:32:01.249  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:01.268  6523  6523 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 18:32:01.275  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-22 18:32:01.275  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-22 18:32:01.276  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-22 18:32:01.276  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-22 18:32:01.276  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:01.276  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:01.280  6523  6523 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 18:32:01.280  6523  6523 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-22 18:32:01.282  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=190186  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-22 18:32:01.287  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 18:32:01.298  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:32:01.298  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-22 18:32:01.298  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:32:01.298  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-22 18:32:01.306  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:01.306  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:01.306  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-22 18:32:01.307  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 18:32:01.307  1034  6543 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 18:32:01.307  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-22 18:32:01.307  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-22 18:32:01.307  1034  6543 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-22 18:32:01.308  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:01.308  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:01.308  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=190198  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-22 18:32:01.310  1034  1399 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=190214
08-22 18:32:01.311  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-22 18:32:01.312  1034  1399 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=190215
08-22 18:32:01.313  1034  1399 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=190216
08-22 18:32:01.313  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:32:01.313  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-22 18:32:01.313  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:32:01.313  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:32:01.313  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:32:01.314  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-22 18:32:01.314  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:32:01.314  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=190217
08-22 18:32:01.315  1034  1399 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=190219
,08-22 18:32:01.317  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=190220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-22 18:32:01.322  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:01.322  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:01.323  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.324  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.324  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-22 18:32:01.325  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=190228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-22 18:32:01.325  1034  1399 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:01.325  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:01.326  1034  1399 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:01.326  1034  1399 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:01.326  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:01.326  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:01.327  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:01.327  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=190231  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-22 18:32:01.328  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=190232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-22 18:32:01.329  1034  1399 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=190232
08-22 18:32:01.329  1034  1399 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=190233
08-22 18:32:01.329  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.330  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.330  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-22 18:32:01.330  1034  1399 D WifiNative-wlan0: doString: [STATUS]
08-22 18:32:01.331  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:01.331  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-22 18:32:01.336  1034  1399 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-22 18:32:01.339  1034  1399 I WifiServiceExtension: setVHTCapabilityType  : false
08-22 18:32:01.343  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:01.345  1034  1399 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-22 18:32:01.345  1034  1399 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-22 18:32:01.346  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:01.346  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-22 18:32:01.348  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:01.352  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.352  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.352  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-22 18:32:01.355  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.355  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:01.355  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-22 18:32:01.358  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-22 18:32:01.367  1034  1399 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-22 18:32:01.368  1034  1468 D ConnectivityService: Got NetworkAgent Messenger
08-22 18:32:01.368  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:01.368  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:01.368  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:01.368  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:01.368  1034  1468 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-22 18:32:01.369  1034  1468 D ConnectivityService: NetworkAgent connected
08-22 18:32:01.369  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:01.370  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:01.370  1034  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 18:32:01.370  1034  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-22 18:32:01.372  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:01.372  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:01.373  1034  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-22 18:32:01.373  1034  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-22 18:32:01.374  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:01.375  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:01.377  1034  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-22 18:32:01.377  1034  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 18:32:01.377  1034  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-22 18:32:01.378  1034  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-22 18:32:01.378  1034  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-22 18:32:01.381  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:01.382  1034  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-22 18:32:01.386   315   894 D CommandListener: Setting iface cfg
,08-22 18:32:01.388  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:01.394  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-22 18:32:01.394  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:01.395  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:01.400  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:01.401  1034  1399 E WifiStateMachine: Start Dhcp Watchdog 1
08-22 18:32:01.401  1034  6580 D DhcpStateMachine: StoppedState
08-22 18:32:01.401  1034  6580 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:01.402  1034  6580 D DhcpStateMachine: WaitBeforeStartState
08-22 18:32:01.405  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:01.405  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-22 18:32:01.405  1034  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=190308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:01.406  1034  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=190309  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:01.406  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=190309  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-22 18:32:01.409  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:01.410  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:01.410  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-22 18:32:01.410  1034  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=190313  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:01.410  1034  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=190314  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:01.411  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=190314  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:01.412  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1290261116] from screen [on:0 period:-1290261116]
08-22 18:32:01.413  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1290261115]
08-22 18:32:01.413  1034  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-22 18:32:01.415  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:01.419  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:01.420  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.420  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.421  1034  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.421  1034  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.421  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.422  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:01.422  1034  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.422  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:01.422  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:01.423  1034  1468 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-22 18:32:01.423  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-22 18:32:01.423  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-22 18:32:01.423  1034  1468 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-22 18:32:01.424  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-22 18:32:01.424  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-22 18:32:01.424  1034  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-22 18:32:01.424  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 0
08-22 18:32:01.425  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:01.425  1034  1399 D WifiNative-wlan0: SET ps 0: returned true
08-22 18:32:01.425  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-22 18:32:01.426  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-22 18:32:01.426  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-22 18:32:01.426  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25b97e92 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:01.426  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25b97e92 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:01.426  1034  1399 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-22 18:32:01.426  1034  1399 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-22 18:32:01.427  1034  1399 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-22 18:32:01.427  1034  1399 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-22 18:32:01.427  1034  6580 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:01.428  1034  6580 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-22 18:32:01.429  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:01.429  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-22 18:32:01.431  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:01.431  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-22 18:32:01.435  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:01.440  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:01.446  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:01.447  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:01.447  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-22 18:32:01.539  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:01.539  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:01.539  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 18:32:01.567  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-22 18:32:01.568  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-22 18:32:01.569  1034  1399 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-22 18:32:01.570  1034  1399 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-22 18:32:01.572  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-22 18:32:01.573  1034  1399 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-22 18:32:01.630  1034  6580 D DhcpStateMachine: DHCPV4 request on wlan0
,08-22 18:32:01.633  1034  6580 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-22 18:32:01.633  1034  6580 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-22 18:32:01.628  6582  6582 W dhcpcd  : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-22 18:32:01.628  6582  6582 W dhcpcd  : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:01.651  6582  6582 I dhcpcd  : version 5.5.6 starting
08-22 18:32:01.653  6582  6582 E dhcpcd  : get_duid: m
08-22 18:32:01.653  6582  6582 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-22 18:32:01.653  6582  6582 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-22 18:32:01.770  6582  6582 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-22 18:32:01.770  6582  6582 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-22 18:32:01.770  6582  6582 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-22 18:32:01.773  6582  6582 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-22 18:32:01.774  6582  6582 D dhcpcd  : wlan0: sending REQUEST (xid 0x5971c428), next in 3.58 seconds
08-22 18:32:01.788  6582  6582 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-22 18:32:01.805  6582  6582 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-22 18:32:01.805  6582  6582 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-22 18:32:01.806  6582  6582 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-22 18:32:01.808  6582  6582 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-22 18:32:01.808  6582  6582 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-22 18:32:01.809  6582  6582 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-22 18:32:01.809  6582  6582 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-22 18:32:01.809  6582  6582 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-22 18:32:01.815  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.816  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.818  1034  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.819  1034  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.820  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.821  1034  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:01.822  1034  1468 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,08-22 18:32:02.236  1034  6580 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-22 18:32:02.240  1034  6580 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-22 18:32:02.240  1034  6580 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-22 18:32:02.241  1034  6580 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-22 18:32:02.242  1034  6580 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-22 18:32:02.242  1034  6580 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-22 18:32:02.242  1034  6580 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-22 18:32:02.242  1034  6580 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-22 18:32:02.244  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-22 18:32:02.246  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-22 18:32:02.247  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-22 18:32:02.247  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.247  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-22 18:32:02.248  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.248  1034  6580 D DhcpStateMachine: RunningState
,08-22 18:32:02.248  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-22 18:32:02.249  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-22 18:32:02.249  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-22 18:32:02.250  1034  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true,
08-22 18:32:02.250  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 1
,08-22 18:32:02.272  1034  1399 D WifiNative-wlan0: SET ps 1: returned true
,08-22 18:32:02.286  1034  1468 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-22 18:32:02.288  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-22 18:32:02.288  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-22 18:32:02.288  1034  1399 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-22 18:32:02.289  1034  1468 D ConnectivityService: ignoring duplicate network state non-change
,08-22 18:32:02.312  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.313  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.313  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-22 18:32:02.330  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:02.330  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-22 18:32:02.334  1034  1468 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-22 18:32:02.336  1034  1468 D ConnectivityService: Adding iface wlan0 to network 100
08-22 18:32:02.345  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.346  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.346  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-22 18:32:02.353  1034  1399 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-22 18:32:02.367  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:02.378  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-22 18:32:02.387  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-22 18:32:02.388  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:02.388  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-22 18:32:02.402  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.402  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.402  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-22 18:32:02.404  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-22 18:32:02.429  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:02.436  1034  1468 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-22 18:32:02.437  1034  1468 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-22 18:32:02.438  1034  1468 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-22 18:32:02.439  1034  1468 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-22 18:32:02.440  1034  1468 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-22 18:32:02.441  1034  1468 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-22 18:32:02.441  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:02.441  1034  1468 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-22 18:32:02.445  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-22 18:32:02.446  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.448  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.448  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.448  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-22 18:32:02.450  1034  1468 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-22 18:32:02.451  1034  1468 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.451  1034  1468 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.453  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.453  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-22 18:32:02.453  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.454  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-22 18:32:02.460  1034  1468 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.460  1034  1468 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:02.460  1034  1468 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.460  1034  1468 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-22 18:32:02.460  1034  1468 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.460  1034  1468 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-22 18:32:02.461  1034  1468 D ConnectivityService: currentScore = 0, newScore = 20
08-22 18:32:02.461  1034  1468 D ConnectivityService:    accepting network in place of null
08-22 18:32:02.461  1034  1468 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.462   315  6632 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-22 18:32:02.469  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:02.469  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-22 18:32:02.470  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.472  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.472  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-22 18:32:02.473  1034  1468 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-22 18:32:02.475  1034  1399 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.475  1034  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:02.480  1034  1468 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-22 18:32:02.481  1034  1468 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-22 18:32:02.481  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 18:32:02.481  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:02.484  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-22 18:32:02.484   315  6637 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-22 18:32:02.485   315  6637 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-22 18:32:02.485  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-22 18:32:02.486  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-22 18:32:02.486  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-22 18:32:02.486  1034  1034 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-22 18:32:02.487   315  6637 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-22 18:32:02.488  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-22 18:32:02.490  1034  1468 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:02.491  1034  1468 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-22 18:32:02.491  1034  1468 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-22 18:32:02.493   315  6640 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-22 18:32:02.494   315  6640 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-22 18:32:02.496  1034  1468 D ConnectivityService: validation of new default Network = false
08-22 18:32:02.497  1034  1468 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-22 18:32:02.497  1034  1468 D DSQN    : enableDataServiceNotify 
08-22 18:32:02.497  1034  1468 D DSQN    : start dsqn bin
08-22 18:32:02.506  1034  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-22 18:32:02.515  1034  1468 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.515  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.515  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.516  1034  1468 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.516  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:02.508  6642  6642 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:02.508  6642  6642 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:02.519  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 18:32:02.524   315  6632 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-22 18:32:02.526  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.529   315  6640 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
,08-22 18:32:02.535  6642  6642 E DSQN    : DSQN ssw
,08-22 18:32:02.535  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-22 18:32:02.537  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.537  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.539  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:02.540  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:02.547  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-22 18:32:02.551  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:02.558  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:02.560   315  6632 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-22 18:32:02.564  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.569  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:02.570  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:02.570  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:02.574  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:02.577  6347  6347 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-22 18:32:02.577  1034  6639 D LocSvc_java: NTP server : europe.pool.ntp.org
08-22 18:32:02.578  1034  6639 D LocSvc_java: NTP server returned: 1471883522429 (Mon Aug 22 18:32:02 GMT+02:00 2016) reference: 191481 certainty: 23 system time offset: -148
08-22 18:32:02.578  1034  6639 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-22 18:32:02.582  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:02.584  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:02.586   315   893 D LGDataListener: argv[0]=dsqncommand
08-22 18:32:02.586   315   893 D LGDataListener: argv[1]=wlan0
08-22 18:32:02.586   315   893 D LGDataListener: argv[2]=1
08-22 18:32:02.586   315   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-22 18:32:02.587  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-22 18:32:02.587  1034  1094 D DSQN    : start to monitor internet connection
,08-22 18:32:02.588  1034  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6211, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-22 18:32:02.588  1034  1051 D WifiService: setWifiEnabled: false pid=6211, uid=10118
08-22 18:32:02.588  1034  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 18:32:02.591  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.597  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:02.598  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:02.599  6392  6392 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-22 18:32:02.600  6392  6392 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-22 18:32:02.600  6392  6392 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-22 18:32:02.605  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:02.609  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-22 18:32:02.609  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-22 18:32:02.609  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-22 18:32:02.610  1034  1399 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-22 18:32:02.610  6347  6347 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-22 18:32:02.610  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-22 18:32:02.610  1034  1399 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-22 18:32:02.611  1034  1399 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-22 18:32:02.611  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:02.611  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-22 18:32:02.611  1034  1399 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-22 18:32:02.611  1034  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 18:32:02.611  1034  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-22 18:32:02.612  1034  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-22 18:32:02.612  1034  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-22 18:32:02.615  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:02.617  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 16:32:02 GMT], X-Android-Received-Millis=[1471883522616], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471883522586]}
08-22 18:32:02.617  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-22 18:32:02.617  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-22 18:32:02.617  1034  1468 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.617  1034  1468 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.617  1034  1468 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:02.618  1034  1468 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.618  1034  1468 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-22 18:32:02.618  1034  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-22 18:32:02.618  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-22 18:32:02.618  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.618  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.618  1034  1468 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-22 18:32:02.618  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-22 18:32:02.618  1034  1468 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.618  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.618  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.618  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-22 18:32:02.618  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-22 18:32:02.618  1034  1468 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.619  1034  1399 D WifiNative-wlan0: SET ps 1: returned true
08-22 18:32:02.619  1034  1468 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.619  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 18:32:02.619  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-22 18:32:02.619  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.620  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-22 18:32:02.621  1034  6580 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.621  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.621   315   894 D CommandListener: Clearing all IP addresses on wlan0
08-22 18:32:02.631  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:02.631  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETW,ORK_STATE_CHANGED_ACTION
08-22 18:32:02.632  6392  6392 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-22 18:32:02.633  6392  6392 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-22 18:32:02.633  6392  6392 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-22 18:32:02.645  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-22 18:32:02.646  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.647  1034  1468 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-22 18:32:02.647  1034  1468 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-22 18:32:02.647  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.650  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-22 18:32:02.651  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-22 18:32:02.652  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:02.652  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:02.654  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.654  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.654  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-22 18:32:02.654  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.656  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:02.657  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-22 18:32:02.660  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.660  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.660  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-22 18:32:02.661  1034  1399 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.661  1034  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:02.661  1034  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-22 18:32:02.662  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:02.662  1034  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:02.663  1034  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:02.663  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:02.663  1034  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:02.664  1034  1399 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 18:32:02.665  1034  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.665  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.665  1034  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@a631995
08-22 18:32:02.665  1034  1389 D LGWifiP2pService: P2pDisablingState
08-22 18:32:02.665  1034  1389 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.665  1034  1389 D LGWifiP2pService: p2p socket connection lost
08-22 18:32:02.667  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-22 18:32:02.667  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-22 18:32:02.667  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-22 18:32:02.667  1966  1966 D WfdsService: WifiP2pState is changed : false
08-22 18:32:02.668  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.668  1966  2373 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-22 18:32:02.668  1966  2373 D WfdsService: Set the WFDS Monitor: false
08-22 18:32:02.668  1034  1389 D LGWifiP2pService: P2pDisabledState
,08-22 18:32:02.668  1966  2373 D WfdsMonitor: WFDS Monitor is stopped
08-22 18:32:02.668  1966  2373 D WfdsService: STATE : WfdsDisabledState - enter
08-22 18:32:02.668  1966  6549 D CtrlSupplicant: Received on exit socket, terminate
08-22 18:32:02.668  1966  6549 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-22 18:32:02.668  1966  6549 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-22 18:32:02.668  1966  6549 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-22 18:32:02.669  6347  6347 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-22 18:32:02.669  6347  6347 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-22 18:32:02.669  1966  2374 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-22 18:32:02.669  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:02.669  1034  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.669  1966  2373 W WfdsService: DefaultState - msg [9445378] is not handled
08-22 18:32:02.670  1034  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-22 18:32:02.670  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-22 18:32:02.670  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.670  1034  1389 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.670  6523  6523 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-22 18:32:02.671  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-22 18:32:02.671  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-22 18:32:02.671  1034  1399 D WifiNative-wlan0: SET ps 1: returned true
08-22 18:32:02.676  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:02.676  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-22 18:32:02.678  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:02.679  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:02.686  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.692   315   894 D CommandListener: Clearing all IP addresses on wlan0
,08-22 18:32:02.692  1034  1468 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-22 18:32:02.692  1034  1468 D DSQN    : disableDataServiceNotify
08-22 18:32:02.692  1034  1468 D DSQN    : stop dsqn bin
,08-22 18:32:02.692  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:02.693  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:02.693  1034  1399 D WifiNative-p2p0: doBoolean: TERMINATE
08-22 18:32:02.694  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-22 18:32:02.694  1034  1399 D WifiNative-p2p0: TERMINATE: returned true
08-22 18:32:02.694  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:32:02.694  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:32:02.694  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-22 18:32:02.696  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.696  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.696  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-22 18:32:02.697  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:32:02.698  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 18:32:02.698  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:02.698  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-22 18:32:02.699  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:02.699  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:32:02.699  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:02.699  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:02.699  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-22 18:32:02.699  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.700  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement sup,ported: NOT_SUPPORTED
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:02.700  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:32:02.700  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:02.700  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:02.700  1034  1468 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-22 18:32:02.700  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.700  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.701  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:02.701  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-22 18:32:02.701  1034  1468 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:02.701  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.702  1034  1468 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-22 18:32:02.702  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.702  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.702  1034  6578 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-22 18:32:02.702  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:02.702  1034  1468 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-22 18:32:02.702  1034  1468 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-22 18:32:02.703  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 18:32:02.703  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-22 18:32:02.703  1034  1468 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:02.703  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 18:32:02.703  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnecte,d  type  :1
08-22 18:32:02.703  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-22 18:32:02.704  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-22 18:32:02.704  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-22 18:32:02.704  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-22 18:32:02.705  1034  1468 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:02.705  1034  1468 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.706  1034  1468 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.706  1034  1468 D NetworkManagementService: Removing idletimer
08-22 18:32:02.706  1034  1468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:02.707  1034  1468 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-22 18:32:02.707  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-22 18:32:02.707  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-22 18:32:02.707  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-22 18:32:02.707  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-22 18:32:02.707  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-22 18:32:02.707  1877  1877 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.708  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-22 18:32:02.708  1034  1399 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:02.708  1034  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:02.709  6347  6347 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-22 18:32:02.709  6347  6347 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-22 18:32:02.710  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:02.713  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:02.718  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.723  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:02.723  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:02.725  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:32:02.729  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:02.733  6347  6347 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-22 18:32:02.733  6347  6347 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-22 18:32:02.733  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:02.737  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:02.741  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.748  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:02.748  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:02.750  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-22 18:32:02.754  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-22 18:32:02.755  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.756  6523  6523 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-22 18:32:02.756  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.756  6523  6523 I wpa_supplicant: monitor socket send errors count : 1
08-22 18:32:02.756  6523  6523 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1966-4\x00 that cannot receive messages
08-22 18:32:02.757  1034  6543 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-22 18:32:02.757  1034  6543 D WifiMonitor: Dropping event because (p2p0) is stopped
08-22 18:32:02.757  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:02.759  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:32:02.764  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:02.770  6435  6655 W FormManager: Network not available. Please check & try again.
08-22 18:32:02.773  6435  6656 V FormManager: Network unavailable.
,08-22 18:32:02.778  6435  6656 V FormManager: Network unavailable.
08-22 18:32:02.781  6523  6523 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 18:32:02.781  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-22 18:32:02.782  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 18:32:02.782  1034  6543 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 18:32:02.782  1034  6543 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-22 18:32:02.782  1034  1096 D Tethering: InitialState.processMessage what=4
08-22 18:32:02.782  6523  6523 W wpa_supplicant: USIM:  scard_deinit function
08-22 18:32:02.782  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:02.782  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:02.782  1034  1399 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=191686
08-22 18:32:02.783  1034  1399 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=191686
08-22 18:32:02.785  1034  1399 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=191688  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-22 18:32:02.785  1034  1399 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=191689  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-22 18:32:02.787  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 18:32:02.787  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-22 18:32:02.788  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.788  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.790  1034  1399 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:02.790  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:02.792  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:32:02.792  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-22 18:32:02.792  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:32:02.792  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-22 18:32:02.792  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-22 18:32:02.793  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:32:02.793  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-22 18:32:02.793  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:32:02.793  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:32:02.793  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:32:02.793  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:32:02.816  6523  6523 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-22 18:32:02.816  1034  6543 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-22 18:32:02.816  1034  6543 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
08-22 18:32:02.816  1034  6543 D WifiMonitor: Disconnecting from the supplicant, no more events
08-22 18:32:02.817  1034  1399 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
,08-22 18:32:02.828  1034  6580 D DhcpStateMachine: StoppedState
,08-22 18:32:02.828  1034  6580 D DhcpStateMachine: StoppedState{ when=-156ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:02.920  1966  1966 D WfdsService: Supplicant Connection state is changed : false
08-22 18:32:02.920  1966  2373 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-22 18:32:02.920  1966  2373 D WfdsService: Set the WFDS Monitor: false
,08-22 18:32:02.920  1966  2373 D WfdsMonitor: WFDS Monitor is stopped
08-22 18:32:02.928  1034  1399 D WifiOffDelayIfNotUsed: stopMonitoring
08-22 18:32:02.929  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:32:02.929  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:32:02.929  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-22 18:32:02.931  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:32:02.932  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-22 18:32:02.933  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:02.936  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-22 18:32:02.939  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-22 18:32:02.943  2472  2472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 18:32:02.945  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-22 18:32:02.946  1034  1443 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-22 18:32:02.946  1034  1443 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-22 18:32:02.947  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:02.947  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:02.949  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:02.949  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:02.953  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-22 18:32:02.964  4250  6658 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-22 18:32:02.966  4250  6659 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:32:02.967  4250  6659 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-22 18:32:02.968  6347  6347 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-22 18:32:02.968  6347  6347 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-22 18:32:02.968  6347  6347 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-22 18:32:02.972  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-22 18:32:02.979  6435  6661 W FormManager: Network not available. Please check & try again.
08-22 18:32:02.982  6435  6662 V FormManager: Network unavailable.
,08-22 18:32:02.983  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-22 18:32:02.990  6435  6662 V FormManager: Network unavailable.
08-22 18:32:03.038  1034  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=345060928, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-22 18:32:03.047  6392  6392 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-22 18:32:03.047  6392  6392 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:370
08-22 18:32:03.107  2671  2671 D [Concierge]Service: onStartCommand(). Type : 9
,08-22 18:32:03.134  1034  1399 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,08-22 18:32:03.136  1034  1399 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-22 18:32:03.140  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=345060928 [*alarm*], flags=0x0
,08-22 18:32:03.362  6121  6509 D UEI.SmartControl: Internal timer expired: 2
,08-22 18:32:03.376  6121  6509 D UEI.SmartControl: unbind internal service
08-22 18:32:03.651  6121  6503 D serial_port: close(fd = 24)
,08-22 18:32:03.663  6121  6503 I UEI.SmartControl: Serial port is closed.
08-22 18:32:04.422  1034  1399 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1290258106] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-22 18:32:04.425  1034  1399 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1290258104] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-22 18:32:05.494  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:32:05.511  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:05.515  1034  1096 D Tethering: MasterInitialState.processMessage what=3
,08-22 18:32:05.522  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:05.523  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:05.534  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-22 18:32:05.538  3660  6327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-22 18:32:05.556  5382  5382 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-22 18:32:05.572  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-22 18:32:05.604  1034  1091 E GpsLocationProvider: No APN found to select.
,08-22 18:32:05.611  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:05.611  1034  1050 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-22 18:32:05.622  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:32:05.665  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-22 18:32:05.666  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-22 18:32:05.666  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-22 18:32:05.669  1034  1096 D BluetoothManagerService: Message: 1
08-22 18:32:05.669  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-22 18:32:05.697  1034  1649 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6675 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-22 18:32:05.707  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:05.729  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:32:05.731  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-22 18:32:05.733  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:05.734  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:05.738  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-22 18:32:05.747  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:32:05.749  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:05.750  5382  5382 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-22 18:32:05.754  5382  5382 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-22 18:32:05.758  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:05.759  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:05.759  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:05.760  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:05.760  1034  1096 D BluetoothManagerService: Message: 20
08-22 18:32:05.760  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26bf6b24:true
,08-22 18:32:05.761  6474  6474 D BluetoothAdapterState: make
08-22 18:32:05.767  6474  6474 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-22 18:32:05.767  6474  6474 I bluedroid-qcom: init
08-22 18:32:05.767  6474  6707 I BluetoothAdapterState: Entering OffState
08-22 18:32:05.768  6474  6474 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-22 18:32:05.769  6474  6474 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 18:32:05.769  6474  6474 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 18:32:05.769  6474  6474 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 18:32:05.769  6474  6474 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-22 18:32:05.770  6474  6474 I bluedroid-qcom: get_profile_interface socket
08-22 18:32:05.758  6710  6710 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:05.758  6710  6710 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-22 18:32:05.772  6474  6711 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-22 18:32:05.779  6710  6710 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-22 18:32:05.779  6710  6710 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-22 18:32:05.779  6710  6710 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-22 18:32:05.779  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-22 18:32:05.779  1034  1096 D BluetoothManagerService: Message: 40
08-22 18:32:05.779  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-22 18:32:05.780  6474  6711 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-22 18:32:05.781  6474  6492 I bluedroid-qcom: config_hci_snoop_log
08-22 18:32:05.782  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-22 18:32:05.782  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-22 18:32:05.783  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-22 18:32:05.783  6474  6711 D BluetoothAdapterProperties: Name is: G3
08-22 18:32:05.783  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-22 18:32:05.783  6710  6710 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-22 18:32:05.789  6474  6707 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-22 18:32:05.789  6474  6707 D BluetoothAdapterProperties: Setting state to 11
08-22 18:32:05.790  6474  6707 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-22 18:32:05.791  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:32:05.791  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-22 18:32:05.791  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-22 18:32:05.791  6474  6707 I LGBluetoothServiceJni: classInitNative: succeeds
08-22 18:32:05.792  6710  6710 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-22 18:32:05.792  6710  6710 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-22 18:32:05.794  6329  6329 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-22 18:32:05.795  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-22 18:32:05.796  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:05.796  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:05.800  6474  6707 D BluetoothBondStateMachine: make
08-22 18:32:05.800  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:05.803  6474  6474 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-22 18:32:05.804  6474  6474 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:05.804  6474  6474 V BluetoothPbapReceiver: ***********state = 11
,08-22 18:32:05.808  6474  6707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:05.808  6474  6707 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-22 18:32:05.808  6474  6707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:05.808  6474  6707 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-22 18:32:05.808  6474  6707 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-22 18:32:05.809  6474  6713 I BluetoothBondStateMachine: StableState(): Entering Off State
08-22 18:32:05.810  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:32:05.814  6474  6707 E BluetoothAdapterService: File transfer profiles supported!!
,08-22 18:32:05.821  6474  6707 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:05.822  6474  6474 D HeadsetService: Received start request. Starting profile...
08-22 18:32:05.823  6474  6474 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-22 18:32:05.823  6474  6474 D LGBluetoothHfpAdapter: Version 1.6
08-22 18:32:05.826  6329  6329 D BluetoothPermissionRequest: onReceive
08-22 18:32:05.826  6474  6474 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-22 18:32:05.828  6474  6474 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-22 18:32:05.828  6474  6474 D HeadsetStateMachine: make
08-22 18:32:05.833  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-22 18:32:05.834  6474  6707 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:05.841  6675  6675 I AppUp4:AppBoxCP: onCreate
,08-22 18:32:05.841  6474  6707 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:05.843  6675  6675 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-22 18:32:05.846  6474  6707 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:05.850  6474  6707 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:05.855  6474  6707 E BluetoothAdapterService: File transfer profiles supported!!
,08-22 18:32:05.860  6675  6675 I AppUp4:DB:  setFingerPrint start
08-22 18:32:05.861  6675  6675 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-22 18:32:05.864  6474  6474 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:32:05.864  6474  6474 D LgDataFeature: LgDataFeature() Constructor Done, null
08-22 18:32:05.866  6474  6707 V LGMDMManager: Create singleton instance
08-22 18:32:05.867  6474  6707 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-22 18:32:05.868  6675  6675 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-22 18:32:05.868  6675  6675 I AppUp4:DB:  SDK version = 21
08-22 18:32:05.868  6675  6675 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-22 18:32:05.868  6474  6474 D HeadsetStateMachine: max_hf_connections = 1
08-22 18:32:05.868  6474  6474 I bluedroid-qcom: get_profile_interface handsfree
08-22 18:32:05.869  6675  6675 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-22 18:32:05.870  6474  6474 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-22 18:32:05.870   323   323 V AudioPolicyService: registerClient() client 0xb14bfe80, uid 1002
08-22 18:32:05.871   323  1397 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-22 18:32:05.871   323  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-22 18:32:05.871   323  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-22 18:32:05.871  6474  6474 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-22 18:32:05.871  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-22 18:32:05.871  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:05.871   323  2986 V AudioFlinger: registerClient() client 0xb1024ad8, pid 6474
08-22 18:32:05.871   323  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:05.871   323  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:05.871  2174  2195 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:05.871  2174  2195 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:05.872   323  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:05.872   323  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:05.872  3130  3145 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:05.872  3130  3145 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:05.872  6474  6491 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:05.872  6474  6491 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-22 18:32:05.872  6474  6491 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:05.872  1601  1937 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:05.872  1601  1937 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:05.872  6474  6491 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-22 18:32:05.872  1601  1937 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:05.872  1601  1937 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:05.872  2174  2198 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:05.872  2174  2198 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:05.872  1877  1893 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:05.872  1877  1893 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:05.872  6474  6474 V ToneGenerator: Create Track: 0xb4928a80
08-22 18:32:05.872  1877  1893 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:05.872  6474  6474 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-22 18:32:05.872  1877  1893 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:05.872  6474  6474 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-22 18:32:05.872  1034  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle ,2
08-22 18:32:05.872  1034  2033 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:05.872   323  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-22 18:32:05.872  1034  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:05.872   323  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-22 18:32:05.872  1034  2033 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:05.872   323  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-22 18:32:05.872   323  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-22 18:32:05.872  3130  3146 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:05.872  3130  3146 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:05.872   323  2986 I AudioFlinger: isAudioPlaybackHookOn() false
08-22 18:32:05.873   323   323 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-22 18:32:05.873   323   323 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-22 18:32:05.873   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-22 18:32:05.873   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
08-22 18:32:05.873  6474  6474 V AudioSystem: getLatency() output 2, latency 50
08-22 18:32:05.873  6474  6474 V AudioSystem: getFrameCount() output 2, frameCount 960
08-22 18:32:05.873  6474  6474 V AudioTrack: createTrack_l() output 2 afLatency 50
08-22 18:32:05.873   323  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-22 18:32:05.873   323  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-22 18:32:05.873   323  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-22 18:32:05.873   323  1396 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-22 18:32:05.873   323  1396 V AudioFlinger: createTrack() lSessionId: 20
08-22 18:32:05.874  6474  6474 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-22 18:32:05.874  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-22 18:32:05.874  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-22 18:32:05.874   323  1397 V AudioFlinger: acquiring 20 from 6474, for 6474
08-22 18:32:05.874   323  1397 V AudioFlinger:  added new entry for 20
08-22 18:32:05.875  6474  6474 V ToneGenerator: ToneGenerator INIT OK, time: 194790
08-22 18:32:05.875  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:05.876  6474  6716 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-22 18:32:05.876  6474  6716 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-22 18:32:05.876  6474  6716 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-22 18:32:05.876  6474  6716 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-22 18:32:05.877   323  2986 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6474
08-22 18:32:05.877  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:05.877   323  2986 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-22 18:32:05.877   323  2986 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-22 18:32:05.877   323  2986 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-22 18:32:05.878   323  2986 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-22 18:32:05.878   323  2986 V voice   : voice_set_parameters: exit with code(0)
08-22 18:32:05.878   323  2986 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-22 18:32:05.878   323  2986 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-22 18:32:05.878   323  2986 V msm8974_platform: platform_set_parameters: exit with code(0)
08-22 18:32:05.878   323  2986 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-22 18:32:05.878   323  2986 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-22 18:32:05.878   323  2986 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-22 18:32:05.878  6474  6716 V ToneGenerator: ToneGenerator destructor
08-22 18:32:05.878  6474  6716 V ToneGenerator: stopTone
08-22 18:32:05.878  6474  6716 V ToneGenerator: Delete Track: 0xb4928a80
08-22 18:32:05.878  6474  6716 V AudioTrack: ~AudioTrack, releasing session id from 6474 on behalf of 6474
08-22 18:32:05.878   323  1396 V AudioPolicyService: AudioCommandThread() adding release output 2
08-22 18:32:05.878   323  1396 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-22 18:32:05.878   323  1258 V AudioPolicyService: AudioCommandThread() waking up
08-22 18:32:05.879   323  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-22 18:32:05.879   323  1258 V AudioPolicyManager: releaseOutput() 2
08-22 18:32:05.879   323  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 18:32:05.879   323  1396 V AudioFlinger: PlaybackThread::Track destructor
08-22 18:32:05.879   323  1396 V AudioFlinger: removeClient_l() pid 6474, calling pid 323
08-22 18:32:05.879  6474  6474 D A2dpService: Received start request. Starting profile...
08-22 18:32:05.879   323  1396 V AudioFlinger: releasing 20 from 6474 for 6474
08-22 18:32:05.879   323  1396 V AudioFlinger:  decremented refcount to 0
08-22 18:32:05.879   323  1396 V AudioFlinger: purging stale effects
08-22 18:32:05.879  6675  6675 I AppUp4:CustModeStarterReceiver: onReceive
08-22 18:32:05.880  6474  6474 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 18:32:05.881  6474  6474 V Avrcp   : make
08-22 18:32:05.881  6474  6474 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-22 18:32:05.881  6474  6474 I bluedroid-qcom: get_profile_interface avrcp
08-22 18:32:05.882  1034  1051 W Process : Unable to open /proc/6717/status
08-22 18:32:05.888  6474  6474 V AudioManager: registerRemoteController: size of Media player list: 0
08-22 18:32:05.892  6474  6474 E AudioManager: No RCC entry present to update
08-22 18:32:05.892  6474  6474 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-22 18:32:05.895  6474  6474 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-22 18:32:05.896  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-22 18:32:05.896  6474  6474 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-22 18:32:05.899  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-22 18:32:05.920  6675  6675 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:32:05.920  6675  6675 D LgDataFeature: LgDataFeature() Constructor Done, null
08-22 18:32:05.926  6675  6675 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32109ddf
08-22 18:32:05.926  6675  6675 D AppUp4:CustFacade: isCustomizationCompleted : false
08-22 18:32:05.926  6675  6675 D AppUp4:CustFacade: isPhone : true
08-22 18:32:05.928  6675  6675 D AppUp4:CustModeStarterReceiver: begin check event
08-22 18:32:05.928  6675  6675 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-22 18:32:05.928  6675  6675 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-22 18:32:05.947  6675  6718 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-22 18:32:05.947  6675  6718 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-22 18:32:05.948  6675  6718 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-22 18:32:05.952  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:05.952  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-22 18:32:05.954  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:05.956  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:05.966  4250  6722 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-22 18:32:05.973  4250  6723 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:05.973  4250  6723 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-22 18:32:05.984  1034  1946 V SIM_STK : Menu title from STK is T-Mobile
08-22 18:32:05.984  1034  1946 V SIM_STK : Menu title from STK is T-Mobile
,08-22 18:32:06.017  1034  2075 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6724 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-22 18:32:06.036  1034  1574 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-22 18:32:06.042  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-22 18:32:06.045  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-22 18:32:06.046  6474  6474 I BluetoothA2dpServiceJni: classInitNative
08-22 18:32:06.046  6474  6474 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 18:32:06.046  6474  6474 D A2dpStateMachine: make
08-22 18:32:06.048  6474  6474 I bluedroid-qcom: get_profile_interface a2dp
08-22 18:32:06.048  6474  6742 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-22 18:32:06.050  6474  6474 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-22 18:32:06.051  6474  6474 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-22 18:32:06.052  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.053  6474  6474 I BluetoothHidServiceJni: classInitNative: succeeds
08-22 18:32:06.055  6474  6741 D A2dpStateMachine: Enter Disconnected: -2
08-22 18:32:06.055  6474  6474 D HidService: Received start request. Starting profile...
08-22 18:32:06.055  6474  6474 I bluedroid-qcom: get_profile_interface hidhost
08-22 18:32:06.055  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.056  6474  6474 I BluetoothHealthServiceJni: classInitNative: succeeds
08-22 18:32:06.057  6474  6474 D HealthService: Received start request. Starting profile...
08-22 18:32:06.059  6474  6474 I bluedroid-qcom: get_profile_interface health
08-22 18:32:06.059  6474  6474 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-22 18:32:06.059  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.060  6474  6474 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-22 18:32:06.061  6474  6474 D PanService: Received start request. Starting profile...
08-22 18:32:06.061  6474  6474 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 18:32:06.061  6474  6474 I bluedroid-qcom: get_profile_interface pan
08-22 18:32:06.066  6474  6474 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-22 18:32:06.066  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.067  6474  6474 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-22 18:32:06.072  6474  6474 D BtGatt.DebugUtils: handleDebugAction() action=null
08-22 18:32:06.072  6474  6474 D BtGatt.GattService: Received start request. Starting profile...
08-22 18:32:06.072  6474  6474 D BtGatt.GattService: start()
08-22 18:32:06.072  6474  6474 I bluedroid-qcom: get_profile_interface gatt
08-22 18:32:06.072  6474  6474 D BtGatt.AdvertiseManager: advertise manager created
08-22 18:32:06.075  6724  6724 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:32:06.076  6724  6724 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-22 18:32:06.077  6724  6724 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-22 18:32:06.077  6724  6724 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-22 18:32:06.077  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
,08-22 18:32:06.078  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.079  6474  6474 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-22 18:32:06.079  6474  6474 V BluetoothMapService: BluetoothMapBinder()
08-22 18:32:06.080  6474  6474 D BluetoothMapService: Received start request. Starting profile...
08-22 18:32:06.080  6474  6474 D BluetoothMapService: start()
08-22 18:32:06.083  6474  6474 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-22 18:32:06.083  6474  6474 D BluetoothMapEmailAppObserver: createReceiver()
08-22 18:32:06.084  6474  6474 D BluetoothMapEmailAppObserver: initObservers()
08-22 18:32:06.084  6474  6474 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-22 18:32:06.091  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
,08-22 18:32:06.091  6474  6474 D HeadsetStateMachine: Proxy object connected
08-22 18:32:06.092  6474  6474 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-22 18:32:06.092  6474  6474 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-22 18:32:06.096  6474  6474 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:06.096  6474  6716 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-22 18:32:06.097  6474  6716 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 18:32:06.097  6474  6716 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-22 18:32:06.099  6474  6474 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:06.102  6474  6474 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:06.104  6474  6474 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-22 18:32:06.105  6474  6474 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.105  6474  6474 V PanService: [BTUI] SIM Extra State :ABSENT
08-22 18:32:06.108  6474  6474 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:06.110  6474  6474 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-22 18:32:06.110  6474  6474 V BluetoothMapService: Handler(): got msg=1
08-22 18:32:06.111  6474  6707 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-22 18:32:06.111  6474  6707 I bluedroid-qcom: enable
08-22 18:32:06.111  6474  6474 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:32:06.111  6474  6474 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:32:06.111  6474  6474 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:32:06.111  6474  6707 I bt_hci_bdroid: init
08-22 18:32:06.112  6474  6749 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-22 18:32:06.112  6474  6474 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.112  6474  6474 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-22 18:32:06.113  6474  6707 I bt_vendor: bt-vendor : init
08-22 18:32:06.113  6474  6707 I bt_vendor: bt-vendor : get_bt_soc_type
08-22 18:32:06.113  6474  6707 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-22 18:32:06.113  6474  6707 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-22 18:32:06.113  6474  6707 D bt_userial_mct: userial_init
08-22 18:32:06.113  6474  6749 I bt-btu  : btu_task pending for preload complete event
08-22 18:32:06.113  6474  6707 D bt_hci_bdroid: set_power 1
08-22 18:32:06.114  6474  6707 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-22 18:32:06.114  6474  6707 I bt_vendor: Starting hciattach daemon
08-22 18:32:06.114  6474  6707 I bt_vendor: try to set true
08-22 18:32:06.108  6752  6752 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:06.108  6752  6752 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-22 18:32:06.130  6753  6753 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-22 18:32:06.202  6760  6760 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-22 18:32:06.217  6761  6761 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-22 18:32:06.245  6763  6763 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-22 18:32:06.267  6764  6764 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-22 18:32:06.280  6765  6765 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-22 18:32:06.293  6766  6766 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-22 18:32:06.321  1034  1776 I art     : Explicit concurrent mark sweep GC freed 137167(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 3.157ms total 163.903ms
08-22 18:32:06.324  6724  6724 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-22 18:32:06.330  6768  6768 I libmdmdetect: ESOC framework not supported
08-22 18:32:06.331  6768  6768 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-22 18:32:06.339  6768  6768 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-22 18:32:06.339  6768  6768 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-22 18:32:06.339  6768  6768 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-22 18:32:06.339  6768  6768 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-22 18:32:06.339  6768  6768 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-22 18:32:06.339  6768  6768 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-22 18:32:06.339  6768  6768 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-22 18:32:06.350  6724  6724 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-22 18:32:06.379  6768  6769 E QC-QMI  : qmi_client [6768] 14: failed to locate client data
,08-22 18:32:06.380   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-22 18:32:06.380   479   479 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-22 18:32:06.391  6724  6724 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 18:32:06.425  6724  6724 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:32:06.425  6724  6724 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 18:32:06.480  6777  6777 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-22 18:32:06.495  6780  6780 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-22 18:32:06.515  6474  6707 I bt_vendor: bluetooth satus is on
08-22 18:32:06.515  6474  6707 D bt_hci_bdroid: preload
,08-22 18:32:06.515  6474  6751 D bt_userial_mct: userial_open(port:0)
08-22 18:32:06.515  6474  6751 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-22 18:32:06.519  6474  6751 I bt_vendor: Done intiailizing UART
08-22 18:32:06.519  6474  6751 I bt_vendor: Done intiailizing UART
08-22 18:32:06.519  6474  6751 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-22 18:32:06.520  6474  6751 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-22 18:32:06.520  6474  6749 I bt-btu  : btu_task received preload complete event
08-22 18:32:06.520  6474  6782 D bt_userial_mct: Entering userial_read_thread()
08-22 18:32:06.520  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-22 18:32:06.520  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-22 18:32:06.522  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_HCI
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 18:32:06.524  6474  6749 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 18:32:06.525  6474  6749 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 18:32:06.525  6474  6749 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 18:32:06.525  6474  6749 I         : BTE_InitTraceLevels -- TRC_BTIF
08-22 18:32:06.564  6724  6724 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-22 18:32:06.586  6474  6749 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-22 18:32:06.586  6474  6749 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0203061 
08-22 18:32:06.586  6474  6749 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0203061 
,08-22 18:32:06.612  6474  6711 E bt-btif : Calling BTA_HhEnable
08-22 18:32:06.612  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-22 18:32:06.612  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-22 18:32:06.612  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called fo service_mask:0x214004
08-22 18:32:06.612  6474  6711 E bt-btif : L2CAP - L2CA_Register() called fo service_mask:0x2140040
08-22 18:32:06.612  6474  6711 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-22 18:32:06.613  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-22 18:32:06.613  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-22 18:32:06.614  6474  6711 D BluetoothAdapterProperties: Name is: G3
08-22 18:32:06.614  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-22 18:32:06.614  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-22 18:32:06.615  6474  6711 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:32:06.615  6474  6711 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 18:32:06.615  6474  6711 D bt_hci_bdroid: postload
08-22 18:32:06.615  6474  6751 D bt_hci_bdroid: Used up Tx Cmd credits
08-22 18:32:06.616  6474  6749 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-22 18:32:06.616  6474  6711 D bte_conf: Device ID record 1 : primary
08-22 18:32:06.616  6474  6711 D bte_conf:   vendorId            = 00c4
08-22 18:32:06.616  6474  6711 D bte_conf:   vendorIdSource      = 0001
08-22 18:32:06.616  6474  6711 D bte_conf:   product             = 13a1
08-22 18:32:06.616  6474  6711 D bte_conf:   version             = 1000
08-22 18:32:06.616  6474  6711 D bte_conf:   clientExecutableURL = 
08-22 18:32:06.616  6474  6711 D bte_conf:   serviceDescription  = 
08-22 18:32:06.616  6474  6711 D bte_conf:   documentationURL    = 
08-22 18:32:06.616  6474  6711 D bte_conf: bte_load_did_conf no section named DID2.
08-22 18:32:06.618  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:06.620  6474  6751 D bt_hci_bdroid: Used up Tx Cmd credits
08-22 18:32:06.620  6474  6751 D bt_hci_bdroid: Used up Tx Cmd credits
08-22 18:32:06.620  6474  6751 D bt_hci_bdroid: Used up Tx Cmd credits
,08-22 18:32:06.621  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:06.622  6474  6751 D bt_hci_bdroid: Used up Tx Cmd credits
08-22 18:32:06.608  6784  6784 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:06.622  6474  6707 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-22 18:32:06.623  6474  6707 D BluetoothAdapterProperties: ScanMode =  20
08-22 18:32:06.623  6474  6707 D BluetoothAdapterProperties: State =  11
08-22 18:32:06.608  6784  6784 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:06.623  6474  6711 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 18:32:06.623  6474  6707 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-22 18:32:06.623  6474  6707 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-22 18:32:06.624  6474  6707 D BluetoothAdapterProperties: Setting state to 12
08-22 18:32:06.624  6474  6707 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-22 18:32:06.624  6474  6711 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-22 18:32:06.627  6474  6782 E bt_mct  : hci lib postload completed
08-22 18:32:06.628  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:32:06.628  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-22 18:32:06.628  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-22 18:32:06.629  6329  6345 D BluetoothMap: onBluetoothStateChange: up=true
08-22 18:32:06.630  6474  6707 I BluetoothAdapterState: Entering On State
08-22 18:32:06.633  6474  6707 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-22 18:32:06.633  6474  6707 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-22 18:32:06.633  6474  6707 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-22 18:32:06.638  6474  6749 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:06.638  6474  6749 W bt-smp  : Plain text(LSB ~ MSB) = ef 4a 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:06.638  6474  6749 W bt-smp  : Encrypted text(LSB ~ MSB) = cb 88 a6 9a a3 86 eb 35 d9 e6 21 97 32 9c db 9d 
08-22 18:32:06.638  6474  6749 W bt-btm  : Stopping oneshot timer
08-22 18:32:06.639  6474  6707 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-22 18:32:06.640  6329  6344 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 18:32:06.642  6329  6345 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 18:32:06.645  6329  6329 D BluetoothMap: Proxy object connected
08-22 18:32:06.645  6329  6329 D MapProfile: Bluetooth service connected
08-22 18:32:06.645  6329  6329 D BluetoothMap: getConnectedDevices()
,08-22 18:32:06.650  6474  6492 V BluetoothMapService: getConnectedDevices()
08-22 18:32:06.656  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:32:06.657  6329  6329 D BluetoothInputDevice: Proxy object connected
08-22 18:32:06.657  6329  6329 D HidProfile: Bluetooth service connected
,08-22 18:32:06.670  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:32:06.671  1034  1034 D BluetoothA2dp: Proxy object connected
08-22 18:32:06.674  1877  1877 D BluetoothHeadset: Proxy object connected
,08-22 18:32:06.676  1877  3904 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:32:06.680  6474  6707 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-22 18:32:06.681  6474  6749 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:06.681  6474  6749 W bt-smp  : Plain text(LSB ~ MSB) = 38 a5 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:06.681  6474  6749 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e 66 38 b4 a6 00 db 56 4a 0b a7 f2 d9 dd d1 d6 
08-22 18:32:06.681  6474  6749 W bt-btm  : Stopping oneshot timer
,08-22 18:32:06.681  6724  6724 I HubEmail: JNI_OnLoad()
08-22 18:32:06.681  6724  6724 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-22 18:32:06.681  6724  6724 I HubEmail: registerNatives()
08-22 18:32:06.681  6724  6724 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-22 18:32:06.682  6724  6724 I HubEmail: registerNativeMethods()
08-22 18:32:06.682  6724  6724 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-22 18:32:06.682  6724  6724 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-22 18:32:06.687  1877  1877 D BluetoothHeadset: Proxy object connected
08-22 18:32:06.687  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:32:06.688  6329  6771 D BluetoothPan: onBluetoothStateChange on: true
,08-22 18:32:06.688  6329  6771 D BluetoothPan: onBluetoothStateChange call bindService
08-22 18:32:06.690  1034  1034 D BluetoothHeadset: Proxy object connected
08-22 18:32:06.693  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:32:06.694  6474  6749 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:06.694  6474  6749 W bt-smp  : Plain text(LSB ~ MSB) = 93 a6 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:06.694  6474  6749 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 46 7a 06 e0 35 eb 13 46 49 ad 9e 63 5b 50 b6 
08-22 18:32:06.694  6474  6749 W bt-btm  : Stopping oneshot timer
08-22 18:32:06.695  6329  6329 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:32:06.695  6329  6329 D PanProfile: Bluetooth service connected
08-22 18:32:06.697  3130  3130 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-22 18:32:06.697  3130  3130 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:06.699  3130  3130 I LgeMiscReceiver: networkInfo.isConnected() = true
08-22 18:32:06.699  3130  3130 D PhoneState: setPdpRejectCasuse : false
,08-22 18:32:06.700  1877  1877 D BluetoothHeadset: Proxy object connected
08-22 18:32:06.701  6793  6793 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-22 18:32:06.706  6474  6749 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:06.706  6474  6749 W bt-smp  : Plain text(LSB ~ MSB) = 15 85 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:06.706  6474  6749 W bt-smp  : Encrypted text(LSB ~ MSB) = a1 c9 d6 3c 47 4d 8e 58 e4 2f cb d9 f8 6a a4 9a 
08-22 18:32:06.706  6474  6749 W bt-btm  : Stopping oneshot timer
08-22 18:32:06.715  6474  6711 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 18:32:06.716  6474  6711 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-22 18:32:06.719  6474  6749 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:06.719  6474  6749 W bt-smp  : Plain text(LSB ~ MSB) = af 47 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:06.719  6474  6749 W bt-smp  : Encrypted text(LSB ~ MSB) = df de c1 d8 dc 2d 92 f3 ad 07 a9 7e 63 cd 95 ac 
08-22 18:32:06.719  6474  6749 W bt-btm  : Stopping oneshot timer
08-22 18:32:06.751  1034  1983 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6799 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-22 18:32:06.753  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-22 18:32:06.753  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-22 18:32:06.756  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-22 18:32:06.756  1034  1096 D BluetoothManagerService: Message: 40
08-22 18:32:06.756  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-22 18:32:06.756  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.757  1966  2199 D LGBluetoothAPIService: Message: 1
08-22 18:32:06.757  1966  2199 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-22 18:32:06.757  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-22 18:32:06.761  6211  6211 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-22 18:32:06.768  1966  2199 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-22 18:32:06.770  6474  6474 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.770  6329  6329 D LocalBluetoothProfileManager: Adding local A2DP profile
08-22 18:32:06.770  6474  6474 D BluetoothMapService: STATE_ON
,08-22 18:32:06.772  6474  6474 D LGBluetoothAPIServer: [BTUI] onCreate()
08-22 18:32:06.772  1034  1096 D BluetoothManagerService: Message: 30
08-22 18:32:06.773  6474  6474 D LGBluetoothAPIServer: [BTUI] onBind()
08-22 18:32:06.773  6435  6790 V FormManager: Network unavailable.
08-22 18:32:06.773  6435  6789 W FormManager: Network not available. Please check & try again.
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:06.776  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:06.777  6329  6329 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-22 18:32:06.777  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-22 18:32:06.777  1966  2199 D LGBluetoothAPIService: Message: 100
08-22 18:32:06.777  1966  2199 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-22 18:32:06.778  6724  6794 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:06.779  1034  1096 D BluetoothManagerService: Message: 30
08-22 18:32:06.784  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:06.784  6435  6790 V FormManager: Network unavailable.
,08-22 18:32:06.789  6329  6329 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-22 18:32:06.791  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-22 18:32:06.793  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.793  6474  6474 V BluetoothPbapService: Pbap Service onCreate
08-22 18:32:06.793  6474  6474 V BluetoothPbapService: Starting PBAP service
08-22 18:32:06.793  6329  6329 D BluetoothA2dp: Proxy object connected
08-22 18:32:06.794  6329  6329 D A2dpProfile: Bluetooth service connected
08-22 18:32:06.795  6474  6474 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:06.795  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:32:06.795  6474  6474 V BluetoothMapService: Handler(): got msg=1
08-22 18:32:06.796  6474  6474 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-22 18:32:06.796  6474  6474 V BluetoothPbapService: Pbap Service onBind
08-22 18:32:06.797  6474  6818 D BluetoothMapMasInstance: MAS initSocket()
08-22 18:32:06.797  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:06.797  6474  6818 D BluetoothMapMasInstance:   masId = 00
08-22 18:32:06.797  6474  6818 D BluetoothMapMasInstance:   msgTypes = 0e
08-22 18:32:06.797  6474  6818 D BluetoothMapMasInstance:   masName = SMS/MMS
08-22 18:32:06.797  6474  6818 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-22 18:32:06.799  1034  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:06.799  6474  6474 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.799  6474  6474 V BluetoothPbapService: state: 12
08-22 18:32:06.799  6474  6474 V BluetoothPbapService: Handler(): got msg=1
,08-22 18:32:06.800  6474  6474 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-22 18:32:06.800  6329  6329 D BluetoothHeadset: Proxy object connected
08-22 18:32:06.800  6474  6474 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-22 18:32:06.800  6474  6474 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.800  6474  6474 V BluetoothPbapReceiver: ***********state = 12
08-22 18:32:06.801  6329  6329 D HeadsetProfile: Bluetooth service connected
08-22 18:32:06.802  6474  6818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:06.803  6474  6820 V BluetoothPbapService: Pbap Service initSocket
08-22 18:32:06.803  6474  6818 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-22 18:32:06.804  6474  6818 V BluetoothMapMasInstance: Succeed to create listening socket 
08-22 18:32:06.804  6474  6818 D BluetoothMapMasInstance: Accepting socket connection...
08-22 18:32:06.804  1034  2127 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:06.804  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:32:06.804  6474  6711 D BluetoothAdapterProperties: Scan Mode:21
08-22 18:32:06.804  6474  6711 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-22 18:32:06.805  2221  2221 D c       : Getting all permits...
08-22 18:32:06.805  2221  2221 D a       : Opening database...
08-22 18:32:06.806  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:06.807  6329  6329 D DockEventReceiver: finishStartingService: stopping service
08-22 18:32:06.807  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:06.808  6329  6329 D BluetoothPbap: Proxy object connected
08-22 18:32:06.808  6329  6329 D PbapServerProfile: Bluetooth service connected
08-22 18:32:06.810  1034  1050 I ActivityManager: Killing 5978:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-22 18:32:06.811  6474  6820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:06.811  2221  2221 D a       : Opening database auth.proximity.permit_store...
,08-22 18:32:06.813  2221  2221 D a       : Closing database...
08-22 18:32:06.849  1034  1947 W libprocessgroup: failed to open /acct/uid_10061/pid_5978/cgroup.procs: No such file or directory
,08-22 18:32:06.854  6474  6820 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-22 18:32:06.854  6474  6820 V BluetoothPbapService: Succeed to create listening socket 
08-22 18:32:06.854  6474  6820 V BluetoothPbapService: Accepting socket connection...
08-22 18:32:06.872  6329  6329 D BluetoothPermissionRequest: onReceive
,08-22 18:32:06.875  6329  6329 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-22 18:32:06.877  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-22 18:32:06.880  6474  6474 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-22 18:32:06.881  6474  6474 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-22 18:32:06.887  6474  6474 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-22 18:32:06.906  6474  6474 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-22 18:32:06.906  6474  6474 V BtOppService: onCreate
,08-22 18:32:06.912  6474  6474 V BluetoothOppNotification: send message
08-22 18:32:06.915  6474  6474 V BtOppService: Starting RfcommListener
08-22 18:32:06.922  6474  6474 D BluetoothOppPreference: Dumping Names:  
08-22 18:32:06.922  6474  6474 D BluetoothOppPreference: {}
,08-22 18:32:06.922  6474  6474 D BluetoothOppPreference: Dumping Channels:  
08-22 18:32:06.922  6474  6474 D BluetoothOppPreference: {}
08-22 18:32:06.923  6474  6474 V BtOppService: onStartCommand
08-22 18:32:06.929  6474  6828 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-22 18:32:06.930  6474  6474 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.930  6474  6828 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-22 18:32:06.930  6474  6825 V BtOppService: Deleted complete outbound shares, number =  0
08-22 18:32:06.930  6474  6474 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-22 18:32:06.933  6474  6474 V BluetoothOppNotification: new notify threadi!
08-22 18:32:06.933  6474  6825 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-22 18:32:06.934  6474  6474 V BluetoothOppNotification: send delay message
08-22 18:32:06.935  6474  6825 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-22 18:32:06.935  6474  6474 V BtOppService: start RfcommListener
08-22 18:32:06.935  6474  6829 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-22 18:32:06.936  6474  6825 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ee52966 on behalf of 
08-22 18:32:06.938  6474  6829 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3513e4a7 on behalf of 
08-22 18:32:06.939  6474  6829 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-22 18:32:06.940  6474  6829 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-22 18:32:06.942  6474  6829 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@294d6d54 on behalf of 
08-22 18:32:06.942  6474  6474 V BtOppService: RfcommListener started
08-22 18:32:06.942  6474  6474 V BtOppService: ContentObserver received notification
08-22 18:32:06.944  6474  6830 V BtOppRfcommListener: Starting RFCOMM listener....
08-22 18:32:06.944  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:06.946  6474  6830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:06.946  6474  6828 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@103f54fd on behalf of 
,08-22 18:32:06.947  6474  6830 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-22 18:32:06.948  6474  6830 V BtOppRfcommListener: Started RFCOMM listener....
08-22 18:32:06.948  6474  6830 I BtOppRfcommListener: Accept thread started.
08-22 18:32:06.948  6474  6830 V BtOppRfcommListener: Accepting connection...
08-22 18:32:06.950  6474  6829 V BluetoothOppNotification: outbound: succ-0  fail-0
08-22 18:32:06.951  6474  6828 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-22 18:32:06.951  6474  6828 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-22 18:32:06.951  6474  6829 V BluetoothOppNotification: outbound notification was removed.
08-22 18:32:06.951  6474  6829 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-22 18:32:06.967  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.967  6474  6474 V BluetoothFtpService: Ftp Service onCreate
08-22 18:32:06.967  6474  6474 I BluetoothFtpService: Ftp Service onCreate
08-22 18:32:06.967  6474  6474 V BluetoothFtpService: Ftp Service onStartCommand
08-22 18:32:06.967  6474  6474 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.967  6474  6474 V BluetoothFtpService: Starting Listening on sockets
08-22 18:32:06.967  6474  6474 V BtOppService: ContentObserver received notification
08-22 18:32:06.967  6474  6474 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:32:06.968  6799  6799 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:32:06.968  6474  6474 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:32:06.968  6474  6474 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:32:06.968  6474  6474 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:06.968  6799  6799 D LgDataFeature: LgDataFeature() Constructor Done, null
08-22 18:32:06.968  6474  6474 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-22 18:32:06.968  6474  6474 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-22 18:32:06.970  6799  6799 D PhoneMonitor: Register our PhoneStateListener
08-22 18:32:06.971  6474  6474 V BluetoothFtpService: Handler(): got msg=1
08-22 18:32:06.973  6474  6829 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19102443 on behalf of 
08-22 18:32:06.973  6474  6474 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-22 18:32:06.973  6474  6474 V BluetoothFtpService: Ftp Service initSocket
08-22 18:32:06.974  6474  6828 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25be0ac0 on behalf of 
08-22 18:32:06.975  6474  6828 V BluetoothOppNotification: update too frequent, put in queue
08-22 18:32:06.976  6474  6828 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-22 18:32:06.976  6474  6828 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-22 18:32:06.977  6474  6829 V BluetoothOppNotification: inbound: succ-0  fail-0
08-22 18:32:06.977  1034  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:06.978  6474  6828 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9b143f9 on behalf of 
08-22 18:32:06.981  6474  6828 V BluetoothOppNotification: update too frequent, put in queue
08-22 18:32:06.981  6474  6474 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:32:06.982  6474  6474 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-22 18:32:06.982  6474  6474 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-22 18:32:06.984  6474  6832 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-22 18:32:06.984  6474  6828 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-22 18:32:06.985  6474  6829 V BluetoothOppNotification: inbound notification was removed.
08-22 18:32:06.986  6474  6829 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-22 18:32:06.987  6474  6829 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ec5ff3e on behalf of 
08-22 18:32:06.988  6799  6799 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-22 18:32:06.990  6799  6799 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-22 18:32:06.995  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:06.995  6474  6474 V BluetoothSapService: Sap Service onCreate
08-22 18:32:07.003  6799  6799 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-22 18:32:07.003  6799  6799 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-22 18:32:07.003  6799  6799 D TelephonyAutoProfiling: [parse] Load xml
08-22 18:32:07.005  6799  6799 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-22 18:32:07.005  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-22 18:32:07.005  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-22 18:32:07.005  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-22 18:32:07.005  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-22 18:32:07.005  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-22 18:32:07.005  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-22 18:32:07.005  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-22 18:32:07.006  6799  6799 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-22 18:32:07.006  6799  6799 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-22 18:32:07.010  6799  6799 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-22 18:32:07.037  1034  2029 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6835 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 18:32:07.037  6474  6474 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:07.037  6474  6474 V BluetoothSapService: state: 12
08-22 18:32:07.038  6474  6474 V BluetoothSapService: Starting SAP server process
08-22 18:32:07.038  1034  2029 I ActivityManager: Killing 6024:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-22 18:32:07.039  6474  6474 V BluetoothSapService: SAP Service startRfcommListenerThread
08-22 18:32:07.040  6474  6849 V BluetoothSapService: Sap Service initRfcommSocket
08-22 18:32:07.028  6845  6845 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:07.028  6845  6845 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:07.048  6845  6845 V BT_SAP  : Event pipe created
08-22 18:32:07.048  6845  6845 V BT_SAP  : create_server_socket qcom.sap.server
08-22 18:32:07.048  6845  6845 V BT_SAP  : created socket fd 6
,08-22 18:32:07.076  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:07.076  1034  1574 W libprocessgroup: failed to open /acct/uid_10080/pid_6024/cgroup.procs: No such file or directory
,08-22 18:32:07.077  6474  6849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:07.085  6474  6849 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-22 18:32:07.085  6474  6849 V BluetoothSapService: Succeed to create listening socket 
08-22 18:32:07.086  6474  6849 V BluetoothSapService: Accepting socket connection...
08-22 18:32:07.289  1034  1776 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6858 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-22 18:32:07.290  1034  1776 I ActivityManager: Killing 2174:com.lge.music/u0a34 (adj 15): empty #17
08-22 18:32:07.297  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 6795
08-22 18:32:07.298  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 6798
08-22 18:32:07.310   323  1396 V AudioFlinger: 2174 died, releasing its sessions
08-22 18:32:07.310   323  1396 V AudioFlinger:  pid 1877 @ 0
08-22 18:32:07.310   323  1396 V AudioFlinger:  pid 3130 @ 1
08-22 18:32:07.310   323  1396 V AudioFlinger:  pid 3130 @ 2
,08-22 18:32:07.328  1034  2075 W libprocessgroup: failed to open /acct/uid_10034/pid_2174/cgroup.procs: No such file or directory
,08-22 18:32:07.356  6858  6858 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-22 18:32:07.358  6858  6858 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-22 18:32:07.362  6858  6858 V DrmService: Service onCreate
08-22 18:32:07.362  6858  6858 D DrmService: Received new request = 2
08-22 18:32:07.366  6858  6875 I DrmSntpClient: Start Sync process
08-22 18:32:07.366  6858  6875 D DrmSntpClient: Server : 0
08-22 18:32:07.425  1034  1776 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6876 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 18:32:07.431  6858  6875 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-22 18:32:07.432  6858  6858 D DrmService: Completed !! request = 2
08-22 18:32:07.433  6858  6858 D DrmService: Request count = 0
08-22 18:32:07.434  6858  6858 V DrmService: Service onDestroy
08-22 18:32:07.436  1034  1051 I ActivityManager: Killing 6075:com.lge.eula/1000 (adj 15): empty #17
08-22 18:32:07.470  1034  1947 W libprocessgroup: failed to open /acct/uid_1000/pid_6075/cgroup.procs: No such file or directory
,08-22 18:32:07.508  6876  6876 I art     : Almond Protected OAT
,08-22 18:32:07.567  6876  6876 D WeatherApplication: removeAccount
,08-22 18:32:07.569  6876  6876 D WeatherApplication: Account.length = 0
08-22 18:32:07.569  6876  6876 E WeatherApplication: OPERATOR:OPEN
08-22 18:32:07.575  6876  6876 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:32:7
08-22 18:32:07.579  6876  6876 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-22 18:32:07.579  6876  6876 D Weather.Utils: 2 : All the weather widget is gone.
08-22 18:32:07.582  6876  6876 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-22 18:32:07.585  6876  6876 D WeatherAncestor: connectivity changed - connection : true
08-22 18:32:07.586  6876  6876 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-22 18:32:07.601  6876  6876 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-22 18:32:07.601  6876  6876 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-22 18:32:07.601  6876  6876 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-22 18:32:07.648  6876  6876 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-22 18:32:07.648  6876  6876 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:32:7
,08-22 18:32:07.667  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:07.667  1034  1389 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 18:32:07.699  1034  1399 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-22 18:32:07.700  1034  1399 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-22 18:32:07.732  1034  2004 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6894 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 18:32:07.735  1034  2004 I ActivityManager: Killing 6041:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-22 18:32:07.797  1034  1050 W libprocessgroup: failed to open /acct/uid_10097/pid_6041/cgroup.procs: No such file or directory
,08-22 18:32:07.926   279   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-22 18:32:07.926   279   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-22 18:32:07.926   279   443 W Vold    : Returning OperationFailed - no handler for errno 0
08-22 18:32:07.928  6894  6912 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-22 18:32:07.934   279   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-22 18:32:07.935   279   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-22 18:32:07.935   279   443 W Vold    : Returning OperationFailed - no handler for errno 0
08-22 18:32:07.935  6894  6912 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-22 18:32:07.936  6474  6474 V BluetoothOppNotification: new notify threadi!
08-22 18:32:07.937  6474  6474 V BluetoothOppNotification: send delay message
08-22 18:32:07.940  6474  6915 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-22 18:32:07.942  6474  6915 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a9ed14a on behalf of 
08-22 18:32:07.943  6474  6915 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-22 18:32:07.947  6474  6915 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-22 18:32:07.949  6474  6915 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129fd8bb on behalf of 
08-22 18:32:07.950  6474  6915 V BluetoothOppNotification: outbound: succ-0  fail-0
08-22 18:32:07.952  6474  6915 V BluetoothOppNotification: outbound notification was removed.
08-22 18:32:07.952  6474  6915 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-22 18:32:07.952   279   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-22 18:32:07.952   279   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-22 18:32:07.952   279   443 W Vold    : Returning OperationFailed - no handler for errno 0
08-22 18:32:07.953  6894  6916 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-22 18:32:07.953  6474  6915 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dba71d8 on behalf of 
08-22 18:32:07.953  6474  6915 V BluetoothOppNotification: inbound: succ-0  fail-0
08-22 18:32:07.955  6474  6915 V BluetoothOppNotification: inbound notification was removed.
08-22 18:32:07.957  6474  6915 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-22 18:32:07.959   279   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-22 18:32:07.959   279   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-22 18:32:07.959   279   443 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:32:07.962  6894  6916 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-22 18:32:07.962  6474  6915 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c227931 on behalf of 
08-22 18:32:08.204  6894  6894 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-22 18:32:08.218  6894  6894 I LibraryLoader: Loading: webviewchromium
,08-22 18:32:08.223  6894  6894 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7131-7137)
,08-22 18:32:08.223  6894  6894 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 18:32:08.234  6894  6894 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {361acc48}
,08-22 18:32:08.238  6894  6894 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 18:32:08.239  6894  6894 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 18:32:08.257  6894  6894 I BrowserStartupController: Initializing chromium process, renderers=0
08-22 18:32:08.258  6894  6894 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:32:08.283  6894  6894 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-22 18:32:08.287  6894  6894 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-22 18:32:08.291  6894  6894 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-22 18:32:08.296   323   323 V AudioPolicyService: registerClient() client 0xb57c2d60, uid 10093
,08-22 18:32:08.298  6894  6937 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-22 18:32:08.326  6894  6894 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 18:32:08.326  6894  6894 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 18:32:08.326  6894  6894 I Adreno-EGL: Build Date: 12/12/14 금
08-22 18:32:08.326  6894  6894 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-22 18:32:08.326  6894  6894 I Adreno-EGL: Remote Branch: 
08-22 18:32:08.326  6894  6894 I Adreno-EGL: Local Patches: 
08-22 18:32:08.326  6894  6894 I Adreno-EGL: Reconstruct Branch: 
,08-22 18:32:08.426  6894  6894 I NSApplication: Starting up...
,08-22 18:32:08.493  1034  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6954 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-22 18:32:08.500  1034  1574 I ActivityManager: Killing 5937:com.android.vending/u0a44 (adj 15): empty #17
08-22 18:32:08.558  1034  2075 W libprocessgroup: failed to open /acct/uid_10044/pid_5937/cgroup.procs: No such file or directory
,08-22 18:32:08.596  6954  6954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 18:32:08.677  1034  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:08.677  1034  2037 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@16b8ba09 mBinding = false
,08-22 18:32:08.699  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-22 18:32:08.702  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-22 18:32:08.702  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-22 18:32:08.702  1034  1096 D BluetoothManagerService: Message: 2
08-22 18:32:08.703  1034  1096 D BluetoothManagerService: Sending off request.
08-22 18:32:08.703  6474  6809 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-22 18:32:08.704  6474  6707 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-22 18:32:08.704  6474  6707 D BluetoothAdapterProperties: Setting state to 13
08-22 18:32:08.704  6474  6707 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 18:32:08.705  6474  6707 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 18:32:08.705  6474  6707 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-22 18:32:08.706  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:32:08.706  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-22 18:32:08.706  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-22 18:32:08.706  6474  6711 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:32:08.707  6474  6707 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-22 18:32:08.708  6474  6707 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-22 18:32:08.709  6474  6818 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-22 18:32:08.710  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-22 18:32:08.710  6474  6749 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-22 18:32:08.711  6474  6820 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:32:08.712  6474  6830 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:32:08.713  6474  6832 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:32:08.713  6474  6849 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-22 18:32:08.718  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:32:08.718  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:32:08.718  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-22 18:32:08.719  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-22 18:32:08.719  6474  6749 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-22 18:32:08.722  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-22 18:32:08.723  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:08.723  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:08.724  6474  6474 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.724  6474  6474 D BluetoothMapService: STATE_TURNING_OFF
08-22 18:32:08.724  6474  6474 V BluetoothMapService: Handler(): got msg=4
08-22 18:32:08.725  6474  6474 D BluetoothMapService: MAP Service closeService in
08-22 18:32:08.725  6474  6474 D BluetoothMapMasInstance: MAP Service shutdown
08-22 18:32:08.725  6474  6474 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-22 18:32:08.725  6474  6474 V BluetoothMapService: MAP Service closeService out
08-22 18:32:08.726  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.726  6474  6474 V BtOppService: Receiver DISABLED_ACTION 
08-22 18:32:08.727  6474  6474 I BtOppRfcommListener: stopping Accept Thread
,08-22 18:32:08.727  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:08.727  6474  6474 V BtOppRfcommListener: close mBtServerSocket
,08-22 18:32:08.727  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:08.727  6474  6474 V BtOppRfcommListener: waiting for thread to terminate
08-22 18:32:08.731  6474  6830 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 18:32:08.731  6474  6474 V BtOppRfcommListener: done waiting for thread to terminate
08-22 18:32:08.734  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:08.734  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:08.734  6211  6211 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:32:08.734  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:08.739  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:08.740  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:32:08.743  6329  6329 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-22 18:32:08.747  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-22 18:32:08.749  6474  6474 V BtOppService: onDestroy
,08-22 18:32:08.750  6474  6474 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-22 18:32:08.758  6474  6474 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-22 18:32:08.758  6474  6474 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.758  6474  6474 V BluetoothPbapReceiver: ***********state = 13
08-22 18:32:08.760  6474  6474 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-22 18:32:08.761  6474  6474 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.761  6474  6474 V BluetoothPbapService: state: 13
08-22 18:32:08.761  6474  6474 V BluetoothPbapService: Pbap Service closeService in
08-22 18:32:08.766  6474  6474 V BluetoothPbapService: successfully stopped pbap service
08-22 18:32:08.766  6474  6474 V BluetoothPbapService: Pbap Service closeService out
08-22 18:32:08.767  6474  6474 V BluetoothPbapService: Pbap Service onDestroy
08-22 18:32:08.767  6474  6474 V BluetoothPbapService: Pbap Service closeService in
08-22 18:32:08.767  6474  6474 V BluetoothPbapService: Pbap Service closeService out
08-22 18:32:08.767  6474  6474 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-22 18:32:08.768  6329  6329 D DockEventReceiver: finishStartingService: stopping service
08-22 18:32:08.769  6329  6329 D BluetoothPbap: Proxy object disconnected
08-22 18:32:08.769  6329  6329 D PbapServerProfile: Bluetooth service disconnected
,08-22 18:32:08.775  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:32:08.784  6329  6329 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-22 18:32:08.802  6329  6329 D BluetoothPermissionRequest: onReceive
08-22 18:32:08.802  6329  6329 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-22 18:32:08.811  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-22 18:32:08.817  6474  6474 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-22 18:32:08.817  6474  6474 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-22 18:32:08.818  6474  6474 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-22 18:32:08.826  6474  6474 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.826  6474  6474 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-22 18:32:08.828  6474  6474 V BluetoothFtpService: Ftp Service onStartCommand
08-22 18:32:08.828  6474  6474 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.829  6474  6474 V BluetoothFtpService: Ftp Service closeService
08-22 18:32:08.829  6474  6474 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-22 18:32:08.832  6474  6474 V BluetoothFtpService: successfully stopped ftp service
08-22 18:32:08.832  6474  6474 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:32:08.832  6474  6474 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:32:08.832  6474  6474 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:32:08.832  6474  6474 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.832  6474  6474 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-22 18:32:08.832  6474  6474 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-22 18:32:08.833  6474  6474 V BluetoothFtpService: Ftp Service onDestroy
08-22 18:32:08.833  6474  6474 V BluetoothFtpService: Ftp Service closeService
08-22 18:32:08.837  6474  6474 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:08.837  6474  6474 V BluetoothSapService: state: 13
08-22 18:32:08.837  6474  6474 V BluetoothSapService: Stopping SAP server process
08-22 18:32:08.840  6474  6474 V BluetoothSapService: Sap Service closeSapService in
08-22 18:32:08.840  6474  6474 V BluetoothSapService: Close listen Socket : 
08-22 18:32:08.840  6474  6474 V BluetoothSapService: Close rfcomm Socket : 
08-22 18:32:08.840  6474  6474 V BluetoothSapService: Close sapd  Socket : 
08-22 18:32:08.844  6474  6474 V BluetoothSapService: Sap Service closeSapService out
08-22 18:32:08.845  6474  6474 V BluetoothSapService: Sap Service onDestroy
08-22 18:32:08.845  6474  6474 V BluetoothSapService: Sap Service closeSapService in
08-22 18:32:08.845  6474  6474 V BluetoothSapService: Close listen Socket : 
08-22 18:32:08.845  6474  6474 V BluetoothSapService: Close rfcomm Socket : 
08-22 18:32:08.845  6474  6474 V BluetoothSapService: Close sapd  Socket : 
08-22 18:32:08.845  6474  6474 V BluetoothSapService: Sap Service closeSapService out
,08-22 18:32:08.988  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-22 18:32:08.992  3660  6327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-22 18:32:09.032  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:32:09.050  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-22 18:32:09.050  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:32:09.050  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-22 18:32:09.050  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-22 18:32:09.052  6675  6675 I AppUp4:CustModeStarterReceiver: onReceive
08-22 18:32:09.057  6675  6675 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32109ddf
08-22 18:32:09.057  6675  6675 D AppUp4:CustFacade: isCustomizationCompleted : false
08-22 18:32:09.057  6675  6675 D AppUp4:CustFacade: isPhone : true
08-22 18:32:09.057  6675  6675 D AppUp4:CustModeStarterReceiver: begin check event
08-22 18:32:09.058  6675  6675 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-22 18:32:09.062  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:32:09.062  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-22 18:32:09.067  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:09.070  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:09.077  6724  6724 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-22 18:32:09.077  4250  6994 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-22 18:32:09.079  4250  6995 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:09.079  4250  6995 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-22 18:32:09.103  6724  6996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 18:32:09.113  6435  6999 W FormManager: Network not available. Please check & try again.
08-22 18:32:09.116  3130  3130 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-22 18:32:09.116  3130  3130 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:09.116  6435  7000 V FormManager: Network unavailable.
,08-22 18:32:09.116  3130  3130 I LgeMiscReceiver: networkInfo.isConnected() = false
08-22 18:32:09.121  6799  6799 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-22 18:32:09.122  6799  6799 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-22 18:32:09.137  6876  6876 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:32:9
,08-22 18:32:09.140  6435  7000 V FormManager: Network unavailable.
08-22 18:32:09.141  6876  6876 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-22 18:32:09.141  6876  6876 D Weather.Utils: 2 : All the weather widget is gone.
08-22 18:32:09.142  6876  6876 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-22 18:32:09.142  6876  6876 D WeatherAncestor: connectivity changed - connection : true
08-22 18:32:09.142  6876  6876 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c2fcf5
08-22 18:32:09.143  6876  6876 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-22 18:32:09.143  6876  6876 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-22 18:32:09.143  6876  6876 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-22 18:32:09.143  6876  6876 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-22 18:32:09.144  6876  6876 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:32:9
08-22 18:32:09.177  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-22 18:32:09.183  3660  6327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-22 18:32:09.196  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:32:09.210  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-22 18:32:09.210  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:09.210  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-22 18:32:09.210  6675  6675 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-22 18:32:09.213  6675  6675 I AppUp4:CustModeStarterReceiver: onReceive
08-22 18:32:09.217  6675  6675 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32109ddf
08-22 18:32:09.217  6675  6675 D AppUp4:CustFacade: isCustomizationCompleted : false
08-22 18:32:09.217  6675  6675 D AppUp4:CustFacade: isPhone : true
08-22 18:32:09.218  6675  6675 D AppUp4:CustModeStarterReceiver: begin check event
08-22 18:32:09.218  6675  6675 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-22 18:32:09.222  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:09.222  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-22 18:32:09.224  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-22 18:32:09.227  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:09.232  4250  7004 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-22 18:32:09.234  6724  6724 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-22 18:32:09.235  4250  7005 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:09.235  4250  7005 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-22 18:32:09.254  6724  7006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 18:32:09.262  3130  3130 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-22 18:32:09.262  3130  3130 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:09.262  3130  3130 I LgeMiscReceiver: networkInfo.isConnected() = false
08-22 18:32:09.263  6435  7008 W FormManager: Network not available. Please check & try again.
08-22 18:32:09.267  6799  6799 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-22 18:32:09.267  6799  6799 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-22 18:32:09.280  6435  7009 V FormManager: Network unavailable.
,08-22 18:32:09.289  6876  6876 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:32:9
08-22 18:32:09.290  6435  7009 V FormManager: Network unavailable.
08-22 18:32:09.291  6876  6876 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-22 18:32:09.291  6876  6876 D Weather.Utils: 2 : All the weather widget is gone.
08-22 18:32:09.292  6876  6876 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-22 18:32:09.292  6876  6876 D WeatherAncestor: connectivity changed - connection : true
08-22 18:32:09.292  6876  6876 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c2fcf5
,08-22 18:32:09.293  6876  6876 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-22 18:32:09.293  6876  6876 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-22 18:32:09.293  6876  6876 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-22 18:32:09.293  6876  6876 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-22 18:32:09.293  6876  6876 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:32:9
,08-22 18:32:09.618  6474  6711 D bt_hci_bdroid: cleanup
,08-22 18:32:09.619  6474  6751 I bt_lpm  : LPM is already off!!!
08-22 18:32:09.620  6474  6782 I bt_userial_mct: exiting userial_read_thread
08-22 18:32:09.620  6474  6782 D bt_userial_mct: Leaving userial_evt_read_thread()
08-22 18:32:09.620  6474  6749 W bt-btif : ag scb idx 1 not allocated
08-22 18:32:09.620  6474  6749 E bt-btif : BTA AG is already disabled, ignoring ...
08-22 18:32:09.620  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:32:09.620  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:32:09.620  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:32:09.620  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-22 18:32:09.621  6474  6749 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:32:09.621  6474  6749 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-22 18:32:09.622  6474  6711 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-22 18:32:09.622  6474  6751 I bt_vendor: hw_epilog_process
08-22 18:32:09.624  6474  6711 D bt_hci_bdroid: cleanup Finalizing cleanup
08-22 18:32:09.624  6474  6711 D bt_userial_mct: userial_close
08-22 18:32:09.624  6474  6711 E bt_userial_mct: pthread_join() FAILED result:3
08-22 18:32:09.624  6474  6711 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-22 18:32:09.655  6474  6711 D bt_hci_bdroid: set_power 0
08-22 18:32:09.655  6474  6711 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-22 18:32:09.655  6474  6711 I bt_vendor: bluetooth satus is on
08-22 18:32:09.655  6474  6711 I bt_vendor: bt-vendor : resetting BT status
08-22 18:32:09.655  6474  6711 I bt_vendor: Starting hciattach daemon
08-22 18:32:09.655  6474  6711 I bt_vendor: try to set false
08-22 18:32:09.656  6474  6711 I bt_vendor: Starting hciattach daemon
08-22 18:32:09.656  6474  6711 I bt_vendor: try to set false
08-22 18:32:09.657  6474  6711 I bt_vendor: cleanup
08-22 18:32:09.658  6474  6749 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-22 18:32:09.659  6474  6711 I GKI_LINUX: GKI_exit_task 0 done
,08-22 18:32:09.659  6474  6711 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-22 18:32:09.660  6474  6707 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-22 18:32:09.663  6474  6474 D HeadsetService: Received stop request...Stopping profile...
08-22 18:32:09.664  6474  6474 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-22 18:32:09.664  6474  6474 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:32:09.664  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:09.664  6474  6716 D HeadsetStateMachine: Exit Disconnected: -1
08-22 18:32:09.666  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-22 18:32:09.666  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-22 18:32:09.666  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-22 18:32:09.667  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-22 18:32:09.667  1877  1877 D BluetoothHeadset: Proxy object disconnected
08-22 18:32:09.668  6474  6474 D HeadsetStateMachine: Unbinding service...
08-22 18:32:09.668  6474  6474 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-22 18:32:09.668  6474  6474 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-22 18:32:09.668  6474  6474 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-22 18:32:09.668  6474  6474 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-22 18:32:09.669  6474  6474 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 18:32:09.669  6474  6474 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:32:09.669  6474  6474 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-22 18:32:09.670  6474  6474 D A2dpService: Received stop request...Stopping profile...
08-22 18:32:09.670  6474  6741 D A2dpStateMachine: Exit Disconnected: -1
,08-22 18:32:09.673  6474  6474 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-22 18:32:09.676  6329  6329 D BluetoothHeadset: Proxy object disconnected
08-22 18:32:09.676  6329  6329 D HeadsetProfile: Bluetooth service disconnected
08-22 18:32:09.676  6474  6474 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-22 18:32:09.676  6474  6474 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:32:09.676  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:09.678  6474  6474 D HidService: Received stop request...Stopping profile...
08-22 18:32:09.678  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:09.679  6474  6707 D BluetoothAdapterState: Stopping profile services that were post enabled
08-22 18:32:09.680  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-22 18:32:09.680  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-22 18:32:09.680  6329  6329 D BluetoothA2dp: Proxy object disconnected
08-22 18:32:09.680  6329  6329 D A2dpProfile: Bluetooth service disconnected
08-22 18:32:09.680  6329  6329 D BluetoothInputDevice: Proxy object disconnected
08-22 18:32:09.680  6474  6474 D HealthService: Received stop request...Stopping profile...
08-22 18:32:09.680  6329  6329 D HidProfile: Bluetooth service disconnected
08-22 18:32:09.680  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:09.682  6474  6474 D PanService: Received stop request...Stopping profile...
08-22 18:32:09.682  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:09.683  6329  6329 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 18:32:09.683  6329  6329 D PanProfile: Bluetooth service disconnected
08-22 18:32:09.683  6474  6474 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:32:09.686  6474  6474 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 18:32:09.686  6474  6474 D BtGatt.GattService: stop()
08-22 18:32:09.688  6474  6474 D BtGatt.AdvertiseManager: advertise clients cleared
08-22 18:32:09.689  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:09.690  6474  6474 I BluetoothA2dpServiceJni: cleanupNative
08-22 18:32:09.690  6474  6742 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-22 18:32:09.690  6474  6474 I GKI_LINUX: GKI_exit_task 2 done
08-22 18:32:09.690  6474  6474 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-22 18:32:09.691  6474  6474 D BluetoothMapService: Received stop request...Stopping profile...
08-22 18:32:09.691  6474  6474 D BluetoothMapService: stop()
08-22 18:32:09.691  6474  6474 D BluetoothMapEmailAppObserver: deinitObservers()
08-22 18:32:09.691  6474  6474 D BluetoothMapEmailAppObserver: removeReceiver()
08-22 18:32:09.692  6474  6474 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:09.693  6474  6474 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 18:32:09.693  6474  6474 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 18:32:09.693  6329  6329 D BluetoothMap: Proxy object disconnected
08-22 18:32:09.693  6329  6329 D MapProfile: Bluetooth service disconnected
08-22 18:32:09.693  6474  6474 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 18:32:09.693  6474  6474 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 18:32:09.693  6474  6474 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 18:32:09.694  6474  6474 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 18:32:09.694  6474  6474 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 18:32:09.695  6474  6474 V BluetoothMapService: Handler(): got msg=4
08-22 18:32:09.695  6474  6474 D BluetoothMapService: MAP Service closeService in
08-22 18:32:09.695  6474  6474 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-22 18:32:09.695  6474  6474 V BluetoothMapService: MAP Service closeService out
08-22 18:32:09.696  6474  6707 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-22 18:32:09.696  6474  6707 D BluetoothAdapterProperties: Setting state to 10
08-22 18:32:09.696  6474  6707 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-22 18:32:09.698  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:32:09.698  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-22 18:32:09.698  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-22 18:32:09.698  6474  6474 D BluetoothMapService: cleanup()
08-22 18:32:09.698  6474  6474 D BluetoothMapService: MAP Service closeService in
08-22 18:32:09.698  6474  6474 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-22 18:32:09.698  6474  6474 V BluetoothMapService: MAP Service closeService out
08-22 18:32:09.699  6474  6707 I BluetoothAdapterState: Entering OffState
08-22 18:32:09.699  6329  6344 D BluetoothMap: onBluetoothStateChange: up=false
08-22 18:32:09.700  6329  6771 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 18:32:09.700  6329  6345 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 18:32:09.701  6329  6344 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:32:09.702  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:32:09.702  1877  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:32:09.702  1877  3904 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:32:09.703  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:32:09.703  6329  6771 D BluetoothPan: onBluetoothStateChange on: false
08-22 18:32:09.704  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:32:09.704  6329  6345 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:32:09.706  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-22 18:32:09.706  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-22 18:32:09.707  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-22 18:32:09.707  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-22 18:32:09.707  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@16b8ba09 mBinding = false
08-22 18:32:09.708  1034  1096 D BluetoothManagerService: Sending unbind request.
,08-22 18:32:09.713  6474  6711 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-22 18:32:09.714  6474  6474 I GKI_LINUX: GKI_exit_task 1 done
08-22 18:32:09.714  6474  6474 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-22 18:32:09.714  6474  6474 I BluetoothServiceJni: cleanupNative: return from cleanup
08-22 18:32:09.714  6474  6474 I art     : --- WEIRD: removing null entry 248
08-22 18:32:09.714  6474  6474 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-22 18:32:09.714  6474  6474 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-22 18:32:09.715  6474  6474 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-22 18:32:09.716  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-22 18:32:09.718  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:09.719  1966  2199 D LGBluetoothAPIService: Message: 2
08-22 18:32:09.719  1966  2199 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1b66c14e mBinding = false
08-22 18:32:09.719  1966  2199 D LGBluetoothAPIService: Sending unbind request.
,08-22 18:32:09.722  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-22 18:32:09.728  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:32:09.729  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:09.731  6329  6329 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-22 18:32:09.731  6329  6329 D LGBluetoothEventManager: [BTUI] clear device connection state
08-22 18:32:09.734  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-22 18:32:09.738  1601  1601 D BluetoothAdapter: 12170710: getState() :  mService = null. Returning STATE_OFF
08-22 18:32:09.738  1601  1601 D BluetoothAdapter: 12170710: getState() :  mService = null. Returning STATE_OFF
08-22 18:32:09.744  6329  6329 D DockEventReceiver: finishStartingService: stopping service
08-22 18:32:09.746  6474  6474 I art     : System.exit called, status: 0
08-22 18:32:09.746  6474  6474 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-22 18:32:09.770   323  1397 V AudioFlinger: 6474 died, releasing its sessions
08-22 18:32:09.770   323  1397 V AudioFlinger:  pid 1877 @ 0
08-22 18:32:09.770   323  1397 V AudioFlinger:  pid 3130 @ 1
08-22 18:32:09.770   323  1397 V AudioFlinger:  pid 3130 @ 2
,08-22 18:32:09.773  6329  6329 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-22 18:32:09.806  1034  2004 I ActivityManager: Process com.android.bluetooth (pid 6474) has died
08-22 18:32:09.806  1034  2004 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-22 18:32:09.816  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:32:09.840  6329  6329 D BluetoothPermissionRequest: onReceive
,08-22 18:32:09.843  6329  6329 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-22 18:32:09.843  6329  6329 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-22 18:32:09.847  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-22 18:32:09.910  1034  2029 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7030 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-22 18:32:10.016  7030  7030 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-22 18:32:10.017  7030  7030 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-22 18:32:10.017  7030  7030 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-22 18:32:10.019  7030  7030 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-22 18:32:10.059  7030  7030 D BluetoothAdapterApp: Loading JNI Library
,08-22 18:32:10.094  7030  7030 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3915a33d Instance Count = 1
,08-22 18:32:10.133  1034  1092 I art     : Explicit concurrent mark sweep GC freed 36094(1679KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 42MB/64MB, paused 2.766ms total 144.517ms
,08-22 18:32:10.135  7030  7030 D BluetoothAdapterApp: onCreate
08-22 18:32:10.156  7030  7030 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-22 18:32:10.157  7030  7030 D ProfileConfigQcom: Adding HeadsetService
,08-22 18:32:10.157  7030  7030 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-22 18:32:10.158  7030  7030 D ProfileConfigQcom: Adding A2dpService
08-22 18:32:10.159  7030  7030 D ProfileConfigQcom: [BTUI] HidService is supported
08-22 18:32:10.160  7030  7030 D ProfileConfigQcom: Adding HidService
08-22 18:32:10.160  7030  7030 D ProfileConfigQcom: [BTUI] HealthService is supported
08-22 18:32:10.161  7030  7030 D ProfileConfigQcom: Adding HealthService
08-22 18:32:10.162  7030  7030 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-22 18:32:10.163  7030  7030 D ProfileConfigQcom: [BTUI] PanService is supported
08-22 18:32:10.164  7030  7030 D ProfileConfigQcom: Adding PanService
08-22 18:32:10.164  7030  7030 D ProfileConfigQcom: [BTUI] GattService is supported
08-22 18:32:10.165  7030  7030 D ProfileConfigQcom: Adding GattService
08-22 18:32:10.166  7030  7030 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-22 18:32:10.166  7030  7030 D ProfileConfigQcom: Adding BluetoothMapService
08-22 18:32:10.166  7030  7030 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-22 18:32:10.168  7030  7030 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-22 18:32:10.173  6329  6329 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-22 18:32:10.175  7030  7030 V LGMDMManagerInternal: Create singleton instance
08-22 18:32:10.263  7030  7030 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:32:10.268  7030  7030 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:32:10.268  7030  7030 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:32:10.269  7030  7030 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:32:10.270  7030  7030 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:10.270  7030  7030 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-22 18:32:10.276  6415  6415 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-22 18:32:10.281  1034  2037 I ActivityManager: Killing 6103:com.lge.bnr/1000 (adj 15): empty #17
,08-22 18:32:10.312  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6103/cgroup.procs: No such file or directory
,08-22 18:32:11.707  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:32:11.707  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:32:12.717  1034  1468 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-22 18:32:12.963  6894  6914 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-22 18:32:13.990  1034  2075 I ActivityManager: Killing 6347:com.lge.sync/1000 (adj 15): empty #17
,08-22 18:32:14.021  1034  2029 W libprocessgroup: failed to open /acct/uid_1000/pid_6347/cgroup.procs: No such file or directory
,08-22 18:32:14.720  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:14.721  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b54919 added. We now have 6 listener(s)
08-22 18:32:14.721  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:32:14.729  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:14.729  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26cbedde added. We now have 7 listener(s)
08-22 18:32:14.729  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:14.730  6211  6289 I System.out: IsBluetoothEnabled
08-22 18:32:14.731  1034  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:14.731  1034  2004 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-22 18:32:14.732  1034  1096 D BluetoothManagerService: Message: 2
08-22 18:32:14.735  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:14.735  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:14.735  1034  1050 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-22 18:32:14.756  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-22 18:32:14.756  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-22 18:32:14.756  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-22 18:32:14.757  1034  1096 D BluetoothManagerService: Message: 1
08-22 18:32:14.757  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-22 18:32:14.784  1034  1096 D BluetoothManagerService: Message: 20
08-22 18:32:14.785  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ea7522:true
,08-22 18:32:14.788  7030  7030 D BluetoothAdapterState: make
08-22 18:32:14.793  7030  7030 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-22 18:32:14.793  7030  7030 I bluedroid-qcom: init
08-22 18:32:14.795  7030  7064 I BluetoothAdapterState: Entering OffState
08-22 18:32:14.795  7030  7030 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-22 18:32:14.795  7030  7030 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 18:32:14.795  7030  7030 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 18:32:14.795  7030  7030 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 18:32:14.796  7030  7030 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-22 18:32:14.797  7030  7030 I bluedroid-qcom: get_profile_interface socket
08-22 18:32:14.798  7030  7030 I bluedroid-qcom: get_profile_interface map_client
,08-22 18:32:14.802  7030  7068 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-22 18:32:14.788  7067  7067 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:14.798  7067  7067 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:14.815  7067  7067 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-22 18:32:14.815  7067  7067 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-22 18:32:14.815  7067  7067 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-22 18:32:14.820  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-22 18:32:14.820  1034  1096 D BluetoothManagerService: Message: 40
08-22 18:32:14.820  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-22 18:32:14.821  7030  7045 I bluedroid-qcom: config_hci_snoop_log
08-22 18:32:14.822  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-22 18:32:14.822  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-22 18:32:14.823  7030  7068 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-22 18:32:14.824  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-22 18:32:14.824  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-22 18:32:14.825  7030  7068 D BluetoothAdapterProperties: Name is: G3
08-22 18:32:14.826  7067  7067 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-22 18:32:14.830  7067  7067 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-22 18:32:14.830  7067  7067 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-22 18:32:14.837  7030  7064 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-22 18:32:14.838  7030  7064 D BluetoothAdapterProperties: Setting state to 11
08-22 18:32:14.838  7030  7064 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-22 18:32:14.839  7030  7064 I LGBluetoothServiceJni: classInitNative: succeeds
08-22 18:32:14.842  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:32:14.842  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-22 18:32:14.842  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-22 18:32:14.846  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:32:14.848  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-22 18:32:14.853  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:14.855  6329  6329 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-22 18:32:14.861  7030  7030 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-22 18:32:14.862  7030  7030 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:14.862  7030  7030 V BluetoothPbapReceiver: ***********state = 11
,08-22 18:32:14.876  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 18:32:14.880  7030  7064 D BluetoothBondStateMachine: make
08-22 18:32:14.886  7030  7064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:14.887  7030  7064 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-22 18:32:14.887  7030  7064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:14.887  7030  7064 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-22 18:32:14.887  7030  7064 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-22 18:32:14.889  7030  7082 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 18:32:14.891  7030  7064 E BluetoothAdapterService: File transfer profiles supported!!
,08-22 18:32:14.894  6329  6329 D BluetoothPermissionRequest: onReceive
08-22 18:32:14.900  7030  7064 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:14.901  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-22 18:32:14.901  7030  7030 D HeadsetService: Received start request. Starting profile...
08-22 18:32:14.902  7030  7030 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 18:32:14.904  7030  7030 D LGBluetoothHfpAdapter: Version 1.6
08-22 18:32:14.908  7030  7030 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-22 18:32:14.909  7030  7030 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-22 18:32:14.909  7030  7030 D HeadsetStateMachine: make
08-22 18:32:14.910  7030  7064 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:14.917  7030  7064 E BluetoothAdapterService: File transfer profiles supported!!
,08-22 18:32:14.923  7030  7064 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:14.928  7030  7064 E BluetoothAdapterService: File transfer profiles supported!!
,08-22 18:32:14.934  7030  7064 E BluetoothAdapterService: File transfer profiles supported!!
08-22 18:32:14.948  7030  7064 V LGMDMManager: Create singleton instance
,08-22 18:32:14.950  7030  7030 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:32:14.950  7030  7030 D LgDataFeature: LgDataFeature() Constructor Done, null
08-22 18:32:14.950  7030  7064 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-22 18:32:14.956  7030  7030 D HeadsetStateMachine: max_hf_connections = 1
08-22 18:32:14.956  7030  7030 I bluedroid-qcom: get_profile_interface handsfree
08-22 18:32:14.959  7030  7030 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-22 18:32:14.959   323  1397 V AudioPolicyService: registerClient() client 0xb14bf840, uid 1002
08-22 18:32:14.960   323  1397 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-22 18:32:14.960   323  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-22 18:32:14.960   323  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-22 18:32:14.962  7030  7030 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-22 18:32:14.963   323   323 V AudioFlinger: registerClient() client 0xb1433148, pid 7030
,08-22 18:32:14.964   323  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:14.964   323  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:14.964  3130  3146 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:14.964  3130  3146 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:14.964  1034  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:14.965  1034  1574 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:14.965  1601  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:14.965  1601  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:14.965  1877  1892 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:14.965  1877  1892 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-22 18:32:14.965  7030  7046 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-22 18:32:14.965   323  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:14.965  7030  7030 V ToneGenerator: Create Track: 0xb4928080
08-22 18:32:14.965   323  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:14.965  7030  7046 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-22 18:32:14.965  7030  7030 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-22 18:32:14.965  7030  7030 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-22 18:32:14.966  1601  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:14.966  1601  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:14.966  1877  2557 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:14.966   323  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-22 18:32:14.966  1877  2557 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:14.966   323  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-22 18:32:14.966  7030  7045 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:14.966  7030  7045 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-22 18:32:14.966  3130  3145 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:14.966  3130  3145 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:14.966   323  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-22 18:32:14.966   323  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-22 18:32:14.967  1034  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-22 18:32:14.967  1034  2033 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-22 18:32:14.967   323  1396 I AudioFlinger: isAudioPlaybackHookOn() false
08-22 18:32:14.967   323  2986 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-22 18:32:14.967   323  2986 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-22 18:32:14.967   323  2986 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-22 18:32:14.968   323  2986 V AudioPolicyManagerEx: getOutput() returns output 2
08-22 18:32:14.968  7030  7030 V AudioSystem: getLatency() output 2, latency 50
08-22 18:32:14.968  7030  7030 V AudioSystem: getFrameCount() output 2, frameCount 960
08-22 18:32:14.968  7030  7030 V AudioTrack: createTrack_l() output 2 afLatency 50
08-22 18:32:14.968   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-22 18:32:14.968   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), ,curLvl = 31 
08-22 18:32:14.968   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-22 18:32:14.968   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-22 18:32:14.968   323   323 V AudioFlinger: createTrack() lSessionId: 21
08-22 18:32:14.970  7030  7030 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-22 18:32:14.970   323  1397 V AudioFlinger: acquiring 21 from 7030, for 7030
08-22 18:32:14.970   323  1397 V AudioFlinger:  added new entry for 21
08-22 18:32:14.970  7030  7030 V ToneGenerator: ToneGenerator INIT OK, time: 203885
08-22 18:32:14.971  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:14.972  7030  7087 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-22 18:32:14.972  7030  7087 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-22 18:32:14.972  7030  7087 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-22 18:32:14.972  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
,08-22 18:32:14.975  7030  7030 D A2dpService: Received start request. Starting profile...
08-22 18:32:14.976  7030  7030 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 18:32:14.977  7030  7030 V Avrcp   : make
08-22 18:32:14.977  7030  7030 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-22 18:32:14.977  7030  7030 I bluedroid-qcom: get_profile_interface avrcp
08-22 18:32:14.978  7030  7087 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-22 18:32:14.979   323  1396 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7030
08-22 18:32:14.980   323  1396 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-22 18:32:14.981   323  1396 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-22 18:32:14.981   323  1396 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-22 18:32:14.981   323  1396 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-22 18:32:14.981   323  1396 V voice   : voice_set_parameters: exit with code(0)
08-22 18:32:14.981   323  1396 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-22 18:32:14.981   323  1396 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-22 18:32:14.981   323  1396 V msm8974_platform: platform_set_parameters: exit with code(0)
08-22 18:32:14.981   323  1396 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-22 18:32:14.981   323  1396 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-22 18:32:14.981   323  1396 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-22 18:32:14.981  7030  7087 V ToneGenerator: ToneGenerator destructor
08-22 18:32:14.981  7030  7087 V ToneGenerator: stopTone
08-22 18:32:14.981  7030  7087 V ToneGenerator: Delete Track: 0xb4928080
08-22 18:32:14.982  7030  7087 V AudioTrack: ~AudioTrack, releasing session id from 7030 on behalf of 7030
08-22 18:32:14.982   323  2986 V AudioFlinger: releasing 21 from 7030 for 7030
08-22 18:32:14.982   323  2986 V AudioFlinger:  decremented refcount to 0
08-22 18:32:14.982   323  2986 V AudioFlinger: purging stale effects
08-22 18:32:14.982   323  1397 V AudioPolicyService: AudioCommandThread() adding release output 2
08-22 18:32:14.982   323  1397 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-22 18:32:14.982   323  1258 V AudioPolicyService: AudioCommandThread() waking up
,08-22 18:32:14.982   323  1397 V AudioFlinger: PlaybackThread::Track destructor
08-22 18:32:14.982   323  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-22 18:32:14.982   323  1258 V AudioPolicyManager: releaseOutput() 2
08-22 18:32:14.982   323  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 18:32:14.982   323  1397 V AudioFlinger: removeClient_l() pid 7030, calling pid 323
08-22 18:32:14.991  7030  7030 V AudioManager: registerRemoteController: size of Media player list: 0
,08-22 18:32:14.996  7030  7030 E AudioManager: No RCC entry present to update
,08-22 18:32:14.996  7030  7030 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-22 18:32:15.001  7030  7030 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-22 18:32:15.003  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-22 18:32:15.003  7030  7030 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-22 18:32:15.008  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-22 18:32:15.165  1034  2075 V SIM_STK : Menu title from STK is T-Mobile
,08-22 18:32:15.165  1034  2075 V SIM_STK : Menu title from STK is T-Mobile
,08-22 18:32:15.314  1034  1776 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-22 18:32:15.325  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-22 18:32:15.332  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-22 18:32:15.333  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-22 18:32:15.334  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-22 18:32:15.334  7030  7030 I BluetoothA2dpServiceJni: classInitNative
08-22 18:32:15.334  7030  7030 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 18:32:15.335  7030  7030 D A2dpStateMachine: make
08-22 18:32:15.337  7030  7030 I bluedroid-qcom: get_profile_interface a2dp
08-22 18:32:15.338  7030  7100 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-22 18:32:15.341  7030  7030 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-22 18:32:15.341  7030  7030 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-22 18:32:15.342  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:15.342  7030  7099 D A2dpStateMachine: Enter Disconnected: -2
08-22 18:32:15.344  7030  7030 I BluetoothHidServiceJni: classInitNative: succeeds
08-22 18:32:15.346  7030  7030 D HidService: Received start request. Starting profile...
08-22 18:32:15.346  7030  7030 I bluedroid-qcom: get_profile_interface hidhost
08-22 18:32:15.346  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:15.347  7030  7030 I BluetoothHealthServiceJni: classInitNative: succeeds
08-22 18:32:15.350  7030  7030 D HealthService: Received start request. Starting profile...
,08-22 18:32:15.352  7030  7030 I bluedroid-qcom: get_profile_interface health
08-22 18:32:15.352  7030  7030 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-22 18:32:15.352  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:15.354  7030  7030 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-22 18:32:15.356  7030  7030 D PanService: Received start request. Starting profile...
08-22 18:32:15.356  7030  7030 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 18:32:15.356  7030  7030 I bluedroid-qcom: get_profile_interface pan
08-22 18:32:15.365  7030  7030 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-22 18:32:15.365  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
,08-22 18:32:15.366  7030  7030 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-22 18:32:15.373  7030  7030 D BtGatt.DebugUtils: handleDebugAction() action=null
08-22 18:32:15.373  7030  7030 D BtGatt.GattService: Received start request. Starting profile...
08-22 18:32:15.373  7030  7030 D BtGatt.GattService: start()
08-22 18:32:15.373  7030  7030 I bluedroid-qcom: get_profile_interface gatt
08-22 18:32:15.374  7030  7030 D BtGatt.AdvertiseManager: advertise manager created
08-22 18:32:15.382  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
,08-22 18:32:15.384  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:15.385  7030  7030 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-22 18:32:15.386  7030  7030 V BluetoothMapService: BluetoothMapBinder()
08-22 18:32:15.387  7030  7030 D BluetoothMapService: Received start request. Starting profile...
08-22 18:32:15.387  7030  7030 D BluetoothMapService: start()
08-22 18:32:15.391  7030  7030 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-22 18:32:15.391  7030  7030 D BluetoothMapEmailAppObserver: createReceiver()
08-22 18:32:15.392  7030  7030 D BluetoothMapEmailAppObserver: initObservers()
08-22 18:32:15.392  7030  7030 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-22 18:32:15.401  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
,08-22 18:32:15.401  7030  7030 D HeadsetStateMachine: Proxy object connected
08-22 18:32:15.402  7030  7030 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-22 18:32:15.402  7030  7030 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-22 18:32:15.408  7030  7030 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:15.409  7030  7087 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-22 18:32:15.409  7030  7087 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 18:32:15.410  7030  7087 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-22 18:32:15.411  7030  7030 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:15.416  7030  7030 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-22 18:32:15.420  7030  7030 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:15.423  7030  7030 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:15.423  7030  7030 V PanService: [BTUI] SIM Extra State :ABSENT
08-22 18:32:15.427  7030  7030 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-22 18:32:15.431  7030  7030 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-22 18:32:15.431  7030  7030 V BluetoothMapService: Handler(): got msg=1
,08-22 18:32:15.437  7030  7030 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:32:15.437  7030  7030 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:32:15.437  7030  7030 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:32:15.437  7030  7030 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:15.437  7030  7064 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-22 18:32:15.437  7030  7030 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-22 18:32:15.437  7030  7064 I bluedroid-qcom: enable
08-22 18:32:15.438  7030  7064 I bt_hci_bdroid: init
08-22 18:32:15.441  7030  7112 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-22 18:32:15.442  7030  7112 I bt-btu  : btu_task pending for preload complete event
08-22 18:32:15.442  7030  7064 I bt_vendor: bt-vendor : init
08-22 18:32:15.442  7030  7064 I bt_vendor: bt-vendor : get_bt_soc_type
08-22 18:32:15.442  7030  7064 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-22 18:32:15.442  7030  7064 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-22 18:32:15.443  7030  7064 D bt_userial_mct: userial_init
08-22 18:32:15.443  7030  7064 D bt_hci_bdroid: set_power 1
08-22 18:32:15.443  7030  7064 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-22 18:32:15.443  7030  7064 I bt_vendor: Starting hciattach daemon
08-22 18:32:15.443  7030  7064 I bt_vendor: try to set true
,08-22 18:32:15.438  7116  7116 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:15.438  7116  7116 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:15.473  7117  7117 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-22 18:32:15.570  7123  7123 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-22 18:32:15.598  7124  7124 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-22 18:32:15.641  7126  7126 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-22 18:32:15.667  7127  7127 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-22 18:32:15.683  7128  7128 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-22 18:32:15.697  7129  7129 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-22 18:32:15.733  7131  7131 I libmdmdetect: ESOC framework not supported
08-22 18:32:15.734  7131  7131 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-22 18:32:15.747  7131  7131 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-22 18:32:15.747  7131  7131 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-22 18:32:15.747  7131  7131 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-22 18:32:15.747  7131  7131 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-22 18:32:15.747  7131  7131 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-22 18:32:15.747  7131  7131 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-22 18:32:15.747  7131  7131 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-22 18:32:15.781  7131  7132 E QC-QMI  : qmi_client [7131] 15: failed to locate client data
,08-22 18:32:15.782   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-22 18:32:15.782   479   479 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-22 18:32:15.848  7139  7139 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-22 18:32:15.861  7140  7140 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-22 18:32:15.876  7030  7064 I bt_vendor: bluetooth satus is on
08-22 18:32:15.877  7030  7064 D bt_hci_bdroid: preload
,08-22 18:32:15.879  7030  7114 D bt_userial_mct: userial_open(port:0)
08-22 18:32:15.879  7030  7114 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-22 18:32:15.882  7030  7114 I bt_vendor: Done intiailizing UART
08-22 18:32:15.883  7030  7114 I bt_vendor: Done intiailizing UART
08-22 18:32:15.883  7030  7114 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-22 18:32:15.883  7030  7114 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-22 18:32:15.883  7030  7112 I bt-btu  : btu_task received preload complete event
08-22 18:32:15.883  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-22 18:32:15.884  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-22 18:32:15.886  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-22 18:32:15.888  7030  7142 D bt_userial_mct: Entering userial_read_thread()
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_HCI
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 18:32:15.889  7030  7112 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 18:32:15.954  7030  7112 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-22 18:32:15.954  7030  7112 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0203061 
08-22 18:32:15.954  7030  7112 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0203061 
,08-22 18:32:15.985  7030  7068 E bt-btif : Calling BTA_HhEnable
08-22 18:32:15.985  7030  7068 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-22 18:32:15.986  7030  7068 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-22 18:32:15.992  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-22 18:32:15.993  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-22 18:32:15.994  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-22 18:32:15.994  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-22 18:32:15.994  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-22 18:32:15.994  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-22 18:32:15.994  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-22 18:32:15.996  7030  7068 D BluetoothAdapterProperties: Name is: G3
08-22 18:32:15.998  7030  7068 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:32:15.998  7030  7068 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 18:32:15.998  7030  7068 D bt_hci_bdroid: postload
08-22 18:32:15.999  7030  7114 D bt_hci_bdroid: Used up Tx Cmd credits
,08-22 18:32:16.007  7030  7112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-22 18:32:16.007  7030  7068 D bte_conf: Device ID record 1 : primary
08-22 18:32:16.007  7030  7068 D bte_conf:   vendorId            = 00c4
08-22 18:32:16.007  7030  7068 D bte_conf:   vendorIdSource      = 0001
08-22 18:32:16.007  7030  7068 D bte_conf:   product             = 13a1
08-22 18:32:16.007  7030  7068 D bte_conf:   version             = 1000
08-22 18:32:16.007  7030  7068 D bte_conf:   clientExecutableURL = 
08-22 18:32:16.007  7030  7068 D bte_conf:   serviceDescription  = 
08-22 18:32:16.007  7030  7068 D bte_conf:   documentationURL    = 
08-22 18:32:16.007  7030  7068 D bte_conf: bte_load_did_conf no section named DID2.
08-22 18:32:16.008  7030  7114 D bt_hci_bdroid: Used up Tx Cmd credits
08-22 18:32:16.011  7030  7064 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-22 18:32:16.011  7030  7064 D BluetoothAdapterProperties: ScanMode =  20
08-22 18:32:16.011  7030  7064 D BluetoothAdapterProperties: State =  11
08-22 18:32:16.012  7030  7064 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-22 18:32:16.012  7030  7064 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-22 18:32:16.012  7030  7064 D BluetoothAdapterProperties: Setting state to 12
08-22 18:32:16.012  7030  7064 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-22 18:32:16.014  7030  7068 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 18:32:16.015  7030  7068 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-22 18:32:16.008  7144  7144 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:16.008  7144  7144 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:16.026  1034  1096 D BluetoothManagerService: Message: 60
08-22 18:32:16.026  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-22 18:32:16.026  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-22 18:32:16.028  7030  7114 D bt_hci_bdroid: Used up Tx Cmd credits
,08-22 18:32:16.032  7030  7114 D bt_hci_bdroid: Used up Tx Cmd credits
08-22 18:32:16.032  7030  7142 E bt_mct  : hci lib postload completed
08-22 18:32:16.042  7030  7112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:16.042  7030  7112 W bt-smp  : Plain text(LSB ~ MSB) = c2 b6 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:16.042  7030  7112 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 9e 38 f7 7e f9 a1 0e 7e ce 98 a1 80 e6 e3 fc 
,08-22 18:32:16.044  7030  7112 W bt-btm  : Stopping oneshot timer
08-22 18:32:16.045  7030  7068 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 18:32:16.046  7030  7068 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-22 18:32:16.053  7030  7064 I BluetoothAdapterState: Entering On State
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:16.063  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:32:16.074  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:16.078  7030  7112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:16.078  7030  7112 W bt-smp  : Plain text(LSB ~ MSB) = 2c 2b 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:16.078  7030  7112 W bt-smp  : Encrypted text(LSB ~ MSB) = eb e2 14 d0 55 c6 9c 0f 17 78 27 f8 b1 61 21 66 
,08-22 18:32:16.080  7030  7112 W bt-btm  : Stopping oneshot timer
08-22 18:32:16.089  7030  7064 D LGBluetoothServiceAdapter: [BTUI] OnState
08-22 18:32:16.089  7030  7064 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-22 18:32:16.089  7030  7064 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-22 18:32:16.090  7030  7064 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-22 18:32:16.093  6329  6344 D BluetoothMap: onBluetoothStateChange: up=true
08-22 18:32:16.102  7030  7064 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-22 18:32:16.106  7030  7112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:16.106  7030  7112 W bt-smp  : Plain text(LSB ~ MSB) = 69 43 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:16.106  7030  7112 W bt-smp  : Encrypted text(LSB ~ MSB) = ed e2 59 3b de 87 06 fd 67 ca bc b8 a5 e7 54 2c 
08-22 18:32:16.107  7030  7112 W bt-btm  : Stopping oneshot timer
08-22 18:32:16.107  6329  6344 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 18:32:16.115  6329  6345 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 18:32:16.126  7030  7112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:16.126  7030  7112 W bt-smp  : Plain text(LSB ~ MSB) = f4 04 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:16.126  7030  7112 W bt-smp  : Encrypted text(LSB ~ MSB) = 7c 7a f4 be 51 3c e3 ec f5 14 ef 6c 6d b2 52 84 
08-22 18:32:16.126  7030  7112 W bt-btm  : Stopping oneshot timer
08-22 18:32:16.145  6329  6344 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 18:32:16.147  7150  7150 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-22 18:32:16.154  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:32:16.159  1034  1034 D BluetoothA2dp: Proxy object connected
08-22 18:32:16.164  6329  6329 D BluetoothMap: Proxy object connected
,08-22 18:32:16.164  6329  6329 D MapProfile: Bluetooth service connected
08-22 18:32:16.164  6329  6329 D BluetoothMap: getConnectedDevices()
,08-22 18:32:16.169  7030  7112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-22 18:32:16.169  7030  7112 W bt-smp  : Plain text(LSB ~ MSB) = 28 82 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-22 18:32:16.169  7030  7112 W bt-smp  : Encrypted text(LSB ~ MSB) = 75 00 d7 f6 cd 62 84 0d de dd 28 72 9d 58 44 70 
08-22 18:32:16.169  7030  7112 W bt-btm  : Stopping oneshot timer
08-22 18:32:16.171  7030  7046 V BluetoothMapService: getConnectedDevices()
08-22 18:32:16.172  1877  3904 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:32:16.179  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 18:32:16.182  1877  1877 D BluetoothHeadset: Proxy object connected
08-22 18:32:16.182  6329  6329 D BluetoothInputDevice: Proxy object connected
08-22 18:32:16.182  6329  6329 D HidProfile: Bluetooth service connected
08-22 18:32:16.183  1877  1877 D BluetoothHeadset: Proxy object connected
08-22 18:32:16.183  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:32:16.185  1034  1034 D BluetoothHeadset: Proxy object connected
08-22 18:32:16.185  6329  6329 D BluetoothA2dp: Proxy object connected
08-22 18:32:16.185  6329  6345 D BluetoothPan: onBluetoothStateChange on: true
08-22 18:32:16.185  6329  6329 D A2dpProfile: Bluetooth service connected
08-22 18:32:16.185  6329  6345 D BluetoothPan: onBluetoothStateChange call bindService
08-22 18:32:16.190  1877  2557 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:32:16.194  1877  1877 D BluetoothHeadset: Proxy object connected
,08-22 18:32:16.194  6329  6771 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 18:32:16.195  6329  6329 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:32:16.195  6329  6329 D PanProfile: Bluetooth service connected
08-22 18:32:16.199  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-22 18:32:16.199  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-22 18:32:16.202  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-22 18:32:16.203  1034  1096 D BluetoothManagerService: Message: 40
08-22 18:32:16.203  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-22 18:32:16.203  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.203  1966  2199 D LGBluetoothAPIService: Message: 1
08-22 18:32:16.203  1966  2199 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-22 18:32:16.204  6329  6329 D BluetoothHeadset: Proxy object connected
08-22 18:32:16.204  6329  6329 D HeadsetProfile: Bluetooth service connected
08-22 18:32:16.206  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-22 18:32:16.212  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:16.217  1966  2199 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-22 18:32:16.218  7030  7030 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.218  7030  7030 D BluetoothMapService: STATE_ON
08-22 18:32:16.220  7030  7030 D LGBluetoothAPIServer: [BTUI] onCreate()
08-22 18:32:16.220  7030  7030 D LGBluetoothAPIServer: [BTUI] onBind()
08-22 18:32:16.221  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-22 18:32:16.221  1966  2199 D LGBluetoothAPIService: Message: 100
08-22 18:32:16.221  1966  2199 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-22 18:32:16.223  6329  6329 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-22 18:32:16.225  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-22 18:32:16.239  6329  6329 D DockEventReceiver: finishStartingService: stopping service
08-22 18:32:16.242  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:16.243  7030  7030 V BluetoothPbapService: Pbap Service onCreate
,08-22 18:32:16.243  7030  7030 V BluetoothPbapService: Starting PBAP service
08-22 18:32:16.244  7030  7030 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-22 18:32:16.245  7030  7030 V BluetoothMapService: Handler(): got msg=1
08-22 18:32:16.245  7030  7030 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-22 18:32:16.246  7030  7030 V BluetoothPbapService: Pbap Service onBind
08-22 18:32:16.247  7030  7171 D BluetoothMapMasInstance: MAS initSocket()
08-22 18:32:16.247  6329  6329 D BluetoothPbap: Proxy object connected
08-22 18:32:16.247  6329  6329 D PbapServerProfile: Bluetooth service connected
08-22 18:32:16.247  7030  7030 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.248  7030  7030 V BluetoothPbapService: state: 12
08-22 18:32:16.248  7030  7030 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-22 18:32:16.248  7030  7030 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.248  7030  7030 V BluetoothPbapReceiver: ***********state = 12
08-22 18:32:16.249  7030  7171 D BluetoothMapMasInstance:   masId = 00
08-22 18:32:16.249  7030  7171 D BluetoothMapMasInstance:   msgTypes = 0e
08-22 18:32:16.249  7030  7171 D BluetoothMapMasInstance:   masName = SMS/MMS
08-22 18:32:16.249  7030  7171 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-22 18:32:16.250  7030  7030 V BluetoothPbapService: Handler(): got msg=1
08-22 18:32:16.250  7030  7030 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-22 18:32:16.251  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:32:16.252  1034  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:16.252  2221  2221 D c       : Getting all permits...
08-22 18:32:16.252  2221  2221 D a       : Opening database...
08-22 18:32:16.254  7030  7171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:16.255  7030  7172 V BluetoothPbapService: Pbap Service initSocket
08-22 18:32:16.255  7030  7171 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-22 18:32:16.256  7030  7171 V BluetoothMapMasInstance: Succeed to create listening socket 
08-22 18:32:16.256  7030  7171 D BluetoothMapMasInstance: Accepting socket connection...
08-22 18:32:16.256  7030  7068 D BluetoothAdapterProperties: Scan Mode:21
08-22 18:32:16.256  7030  7068 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-22 18:32:16.258  2221  2221 D a       : Opening database auth.proximity.permit_store...
,08-22 18:32:16.259  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:16.260  1034  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:16.260  2221  2221 D a       : Closing database...
08-22 18:32:16.261  7030  7172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:16.265  7030  7172 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-22 18:32:16.265  7030  7172 V BluetoothPbapService: Succeed to create listening socket 
08-22 18:32:16.265  7030  7172 V BluetoothPbapService: Accepting socket connection...
08-22 18:32:16.273  6329  6329 D BluetoothPermissionRequest: onReceive
,08-22 18:32:16.276  6329  6329 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-22 18:32:16.277  6329  6329 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-22 18:32:16.280  7030  7030 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-22 18:32:16.282  7030  7030 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-22 18:32:16.289  7030  7030 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-22 18:32:16.309  7030  7030 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-22 18:32:16.309  7030  7030 V BtOppService: onCreate
,08-22 18:32:16.316  7030  7030 V BluetoothOppNotification: send message
08-22 18:32:16.320  7030  7030 V BtOppService: Starting RfcommListener
08-22 18:32:16.326  7030  7175 V BtOppService: Deleted complete outbound shares, number =  0
08-22 18:32:16.326  7030  7030 D BluetoothOppPreference: Dumping Names:  
08-22 18:32:16.326  7030  7030 D BluetoothOppPreference: {}
08-22 18:32:16.327  7030  7030 D BluetoothOppPreference: Dumping Channels:  
08-22 18:32:16.327  7030  7030 D BluetoothOppPreference: {}
,08-22 18:32:16.328  7030  7030 V BtOppService: onStartCommand
08-22 18:32:16.328  7030  7175 V BtOppService: Deleted complete inbound failed shares, number = 0
08-22 18:32:16.329  7030  7175 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-22 18:32:16.331  7030  7175 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ee52966 on behalf of 
08-22 18:32:16.333  7030  7178 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-22 18:32:16.334  7030  7178 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-22 18:32:16.335  7030  7030 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.335  7030  7030 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-22 18:32:16.337  7030  7178 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3513e4a7 on behalf of 
08-22 18:32:16.343  7030  7178 V BluetoothOppNotification: update too frequent, put in queue
,08-22 18:32:16.344  7030  7030 V BluetoothOppNotification: new notify threadi!
08-22 18:32:16.346  7030  7030 V BluetoothOppNotification: send delay message
08-22 18:32:16.347  7030  7178 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-22 18:32:16.347  7030  7030 V BtOppService: start RfcommListener
08-22 18:32:16.348  7030  7179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-22 18:32:16.350  7030  7179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@294d6d54 on behalf of 
08-22 18:32:16.351  7030  7179 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-22 18:32:16.352  7030  7179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-22 18:32:16.353  7030  7179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@103f54fd on behalf of 
08-22 18:32:16.354  7030  7179 V BluetoothOppNotification: outbound: succ-0  fail-0
08-22 18:32:16.355  7030  7179 V BluetoothOppNotification: outbound notification was removed.
08-22 18:32:16.355  7030  7030 V BtOppService: RfcommListener started
,08-22 18:32:16.356  7030  7030 V BtOppService: ContentObserver received notification
08-22 18:32:16.356  7030  7180 V BtOppRfcommListener: Starting RFCOMM listener....
08-22 18:32:16.356  7030  7179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-22 18:32:16.357  7030  7030 V BtOppService: ContentObserver received notification
08-22 18:32:16.358  1034  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:16.358  7030  7180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:16.359  7030  7181 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-22 18:32:16.359  7030  7180 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-22 18:32:16.359  7030  7180 V BtOppRfcommListener: Started RFCOMM listener....
08-22 18:32:16.360  7030  7180 I BtOppRfcommListener: Accept thread started.
08-22 18:32:16.360  7030  7180 V BtOppRfcommListener: Accepting connection...
08-22 18:32:16.360  7030  7181 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-22 18:32:16.361  7030  7181 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f8a75f2 on behalf of 
08-22 18:32:16.361  7030  7179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19102443 on behalf of 
08-22 18:32:16.363  7030  7179 V BluetoothOppNotification: inbound: succ-0  fail-0
08-22 18:32:16.365  7030  7181 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-22 18:32:16.366  7030  7179 V BluetoothOppNotification: inbound notification was removed.
08-22 18:32:16.366  7030  7179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-22 18:32:16.369  7030  7179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25be0ac0 on behalf of 
,08-22 18:32:16.384  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
,08-22 18:32:16.384  7030  7030 V BluetoothFtpService: Ftp Service onCreate
08-22 18:32:16.384  7030  7030 I BluetoothFtpService: Ftp Service onCreate
08-22 18:32:16.384  7030  7030 V BluetoothFtpService: Ftp Service onStartCommand
08-22 18:32:16.385  7030  7030 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.385  7030  7030 V BluetoothFtpService: Starting Listening on sockets
08-22 18:32:16.385  7030  7030 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-22 18:32:16.385  7030  7030 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-22 18:32:16.385  7030  7030 V BluetoothSapReceiver: SapReceiver onReceive 
08-22 18:32:16.385  7030  7030 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.385  7030  7030 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-22 18:32:16.385  7030  7030 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-22 18:32:16.388  7030  7030 V BluetoothFtpService: Handler(): got msg=1
08-22 18:32:16.389  7030  7030 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-22 18:32:16.389  7030  7030 V BluetoothFtpService: Ftp Service initSocket
08-22 18:32:16.395  1034  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:16.396  7030  7030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:32:16.400  7030  7030 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
,08-22 18:32:16.400  7030  7030 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-22 18:32:16.403  7030  7182 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-22 18:32:16.423  7030  7030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2fcf5
08-22 18:32:16.423  7030  7030 V BluetoothSapService: Sap Service onCreate
08-22 18:32:16.426  7030  7030 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:32:16.426  7030  7030 V BluetoothSapService: state: 12
08-22 18:32:16.426  7030  7030 V BluetoothSapService: Starting SAP server process
,08-22 18:32:16.430  7030  7030 V BluetoothSapService: SAP Service startRfcommListenerThread
08-22 18:32:16.418  7183  7183 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:16.418  7183  7183 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:16.432  7030  7184 V BluetoothSapService: Sap Service initRfcommSocket
08-22 18:32:16.433  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:16.434  7030  7184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:32:16.436  7030  7184 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-22 18:32:16.436  7030  7184 V BluetoothSapService: Succeed to create listening socket 
08-22 18:32:16.436  7030  7184 V BluetoothSapService: Accepting socket connection...
08-22 18:32:16.446  7183  7183 V BT_SAP  : Event pipe created
08-22 18:32:16.446  7183  7183 V BT_SAP  : create_server_socket qcom.sap.server
08-22 18:32:16.446  7183  7183 V BT_SAP  : created socket fd 6
,08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:16.799  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:32:16.809  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:16.811  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:16.811  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f021bbf added. We now have 8 listener(s)
08-22 18:32:16.811  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:16.814  1034  1983 D WifiServiceImplEx: setWifiEnabled: false pid=6211, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-22 18:32:16.814  1034  1983 D WifiService: setWifiEnabled: false pid=6211, uid=10118
08-22 18:32:16.814  1034  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:32:16.822  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:16.823  1034  1776 D WifiServiceImplEx: setWifiEnabled: true pid=6211, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-22 18:32:16.824  1034  1776 D WifiService: setWifiEnabled: true pid=6211, uid=10118
08-22 18:32:16.824  1034  1776 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:32:16.840  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-22 18:32:16.840  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-22 18:32:16.840  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-22 18:32:16.842  1034  1399 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-22 18:32:16.842  1034  1399 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-22 18:32:16.844  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-22 18:32:16.844  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-22 18:32:16.844  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-22 18:32:16.844  1034  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-22 18:32:16.845  1034  1399 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-22 18:32:16.845  1034  1399 E WifiHW  : unknown target_country: EU , set to default
,08-22 18:32:16.845  1034  1399 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
08-22 18:32:16.845  1034  1399 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-22 18:32:16.845  1034  1399 I WifiUtil: gEnableBmps=1
08-22 18:32:17.348  7030  7030 V BluetoothOppNotification: new notify threadi!
08-22 18:32:17.349  7030  7030 V BluetoothOppNotification: send delay message
,08-22 18:32:17.369  7030  7203 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-22 18:32:17.370  7030  7203 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b926b5 on behalf of 
08-22 18:32:17.371  7030  7203 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-22 18:32:17.372  7030  7203 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-22 18:32:17.374  7030  7203 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a9ed14a on behalf of 
08-22 18:32:17.375  7030  7203 V BluetoothOppNotification: outbound: succ-0  fail-0
08-22 18:32:17.378  7030  7203 V BluetoothOppNotification: outbound notification was removed.
08-22 18:32:17.378  7030  7203 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-22 18:32:17.379  7030  7203 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129fd8bb on behalf of 
08-22 18:32:17.379  7030  7203 V BluetoothOppNotification: inbound: succ-0  fail-0
08-22 18:32:17.381  7030  7203 V BluetoothOppNotification: inbound notification was removed.
08-22 18:32:17.381  7030  7203 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-22 18:32:17.382  7030  7203 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dba71d8 on behalf of 
08-22 18:32:17.443   315   894 D SoftapController: Softap fwReload - Ok
,08-22 18:32:17.448  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 18:32:17.448  1034  1096 D Tethering: InitialState.processMessage what=4
08-22 18:32:17.456  1034  1399 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (588ms)
08-22 18:32:17.467   315   894 D CommandListener: Setting iface cfg
08-22 18:32:17.467   315   894 D CommandListener: Trying to bring down wlan0
,08-22 18:32:17.471   315   894 D CommandListener: Clearing all IP addresses on wlan0
08-22 18:32:17.476   315  7205 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-22 18:32:17.487  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-22 18:32:17.492  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-22 18:32:17.506  1034  1399 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-22 18:32:17.498  7206  7206 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:17.515  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:32:17.515  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:32:17.515  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-22 18:32:17.508  7206  7206 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:17.524  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:17.527  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-22 18:32:17.567  1034  1399 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-22 18:32:17.567  1034  1399 D WifiMonitor: connecting to supplicant
08-22 18:32:17.567  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:32:17.567  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-22 18:32:17.567  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:32:17.567  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-22 18:32:17.568  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-22 18:32:17.572  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:17.572  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-22 18:32:17.574  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:32:17.574  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-22 18:32:17.574  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:32:17.574  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:32:17.574  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:32:17.575  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:32:17.579  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:32:17.579  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-22 18:32:17.579  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:32:17.579  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-22 18:32:17.579  7206  7206 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-22 18:32:17.581  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-22 18:32:17.582  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:32:17.582  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-22 18:32:17.582  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:32:17.582  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:32:17.583  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:32:17.583  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:32:17.615  7206  7206 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 18:32:17.615  7206  7206 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-22 18:32:17.639  1034  1946 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-22 18:32:17.647  6435  7219 W FormManager: Network not available. Please check & try again.
,08-22 18:32:17.649  6435  7220 V FormManager: Network unavailable.
08-22 18:32:17.651  6435  7220 V FormManager: Network unavailable.
,08-22 18:32:17.704  7206  7206 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 18:32:17.740  7226  7226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:17.742  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:32:17.747  7206  7206 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-22 18:32:17.748  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:17.751  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-22 18:32:17.752  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-22 18:32:17.754  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-22 18:32:17.755  1034  1399 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-22 18:32:17.759  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:17.760  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:17.760  1034  1399 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:17.760  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:17.760  1034  1399 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-22 18:32:17.760  1034  1399 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-22 18:32:17.761  1034  1399 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-22 18:32:17.761  1034  1399 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-22 18:32:17.761  1034  1399 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-22 18:32:17.761  1034  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-22 18:32:17.761  1034  1399 E WifiStateMachine: useWiFiOffloading() : false
08-22 18:32:17.761  1034  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-22 18:32:17.762  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.762  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.762  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.762  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.762  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-22 18:32:17.762  1034  1399 D WifiNative-wlan0: doBoolean: SET update_config 1
08-22 18:32:17.763  1034  1399 D WifiNative-wlan0: SET update_config 1: returned true
08-22 18:32:17.763  1034  1399 D WifiConfigStore: Loading config and enabling all networks 
08-22 18:32:17.763  1034  1399 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-22 18:32:17.763  1034  1399 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-22 18:32:17.764  1966  1966 D WfdService: Waiting for WifiP2p enabling
08-22 18:32:17.766  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:17.768  1034  1399 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-22 18:32:17.769  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-22 18:32:17.769  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-22 18:32:17.769  7206  7206 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-22 18:32:17.769  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-22 18:32:17.769  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-22 18:32:17.769  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-22 18:32:17.769  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - ,BSSID name: null
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:17.770  6211  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:17.772  6211  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:17.773  1034  1399 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-22 18:32:17.774  1034  1399 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 18:32:17.776  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-22 18:32:17.776  1034  1443 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-22 18:32:17.776  1034  1399 D WifiStateMachine: enableVerboseLogging : level 2
08-22 18:32:17.776  1034  1399 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-22 18:32:17.777  1034  1399 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-22 18:32:17.778  1034  1399 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-22 18:32:17.778  1034  1399 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-22 18:32:17.778  1034  1399 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-22 18:32:17.778  1034  1399 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-22 18:32:17.778  1034  1399 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-22 18:32:17.780  1034  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 18:32:17.780  1034  1399 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-22 18:32:17.780  1034  1399 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-22 18:32:17.780  1034  1399 D WifiNative-HAL: Setting external_sim to 1
08-22 18:32:17.780  1034  1399 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-22 18:32:17.781  1034  1399 D WifiNative-wlan0: SET external_sim 1: returned true
08-22 18:32:17.781  1034  1399 I WifiNative-HAL: startHal
08-22 18:32:17.781  1034  1399 D wifi    : setting scan oui 0xaf6c4fe0
08-22 18:32:17.781  7226  7226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:17.781  1034  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 18:32:17.781  1034  1399 I WifiNative-HAL: startHal
08-22 18:32:17.781  1034  1399 D wifi    : setting scan oui 0xaf6c4fe0
08-22 18:32:17.781  1034  1399 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-22 18:32:17.781  1034  1399 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-22 18:32:17.781  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-22 18:32:17.782  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-22 18:32:17.782  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-22 18:32:17.782  1966  1966 D WfdsService: Supplicant Connection state is changed : true
08-22 18:32:17.782  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-22 18:32:17.782  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-22 18:32:17.782  1966  2373 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-22 18:32:17.782  1966  2373 D WfdsService: Set the WFDS Monitor: true
08-22 18:32:17.782  1966  2373 D WfdsMonitor: WfdsMonitorThread create
08-22 18:32:17.782  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-22 18:32:17.782  1966  2373 D WfdsMonitor: WFDS Monitor is created and started
08-22 18:32:17.782  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-22 18:32:17.782  1966  2373 D WfdsService: WiFi: Supplicant connection re-established
08-22 18:32:17.782  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-22 18:32:17.783  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-22 18:32:17.783  1034  ,1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-22 18:32:17.783  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-22 18:32:17.783  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-22 18:32:17.783  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-22 18:32:17.783  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-22 18:32:17.783  1966  7247 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-22 18:32:17.783  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-22 18:32:17.783  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-22 18:32:17.783  7206  7206 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-22 18:32:17.783  1966  7247 E CtrlSupplicant: Succeed to open control connection
08-22 18:32:17.784  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-22 18:32:17.784  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-22 18:32:17.784  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-22 18:32:17.784  1034  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-22 18:32:17.785  1034  1399 E WifiNative: : [206,688,034 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-22 18:32:17.785  1034  1399 D WifiNative-wlan0: doBoolean: RECONNECT
08-22 18:32:17.785  1034  1399 D WifiNative-wlan0: RECONNECT: returned true
08-22 18:32:17.785  1034  1399 D WifiNative-wlan0: doString: [STATUS]
08-22 18:32:17.785  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-22 18:32:17.785  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-22 18:32:17.786  1034  1399 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-22 18:32:17.786  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-22 18:32:17.786  1034  1399 D WifiNative-wlan0: SET ps 1: returned true
08-22 18:32:17.786  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 18:32:17.787  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-22 18:32:17.787  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-22 18:32:17.787   315   894 D CommandListener: Setting iface cfg
08-22 18:32:17.787   315   894 D CommandListener: Trying to bring up p2p0
08-22 18:32:17.788  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.788  1034  1555 I WifiNative-HAL: startHal
08-22 18:32:17.788  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6c4fe0
08-22 18:32:17.788  1034  1555 D wifi    : failed to get capabilities : -3
08-22 18:32:17.788  1034  1555 E WifiScanningService: could not get scan capabilities
,08-22 18:32:17.788  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-22 18:32:17.788  1034  1399 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-22 18:32:17.788  1966  7247 E CtrlSupplicant: Succeed to open monitor connection
08-22 18:32:17.788  1034  1399 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-22 18:32:17.788  1966  7247 D WfdsMonitor: Supplicant connection established
08-22 18:32:17.789  1034  1399 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-22 18:32:17.789  1034  1399 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-22 18:32:17.789  1966  2373 D WfdsService: Connected to the supplicant for wfds
08-22 18:32:17.789  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206692  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-22 18:32:17.789  1034  1556 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.790  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206693  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-22 18:32:17.790  1034  1399 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-22 18:32:17.790  1034  1399 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-22 18:32:17.791  1034  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-22 18:32:17.791  1034  1389 D LGWifiP2pService: P2pEnablingState
08-22 18:32:17.791  1034  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.791  1034  1389 D LGWifiP2pService: P2p socket connection successful
08-22 18:32:17.791  1034  1389 D LGWifiP2pService: P2pEnabledState
08-22 18:32:17.791  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:17.791  1034  1399 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-22 18:32:17.791  1034  1399 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-22 18:32:17.791  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:17.791  7206  7206 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-22 18:32:17.792  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.792  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.793  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-22 18:32:17.793  1034  1399 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-22 18:32:17.793  1034  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-22 18:32:17.793  1034  1399 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-22 18:32:17.793  1034  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-22 18:32:17.793  1034  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-22 18:32:17.794  1034  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-22 18:32:17.794  1034  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-22 18:32:17.794  1034  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-22 18:32:17.794  1034  1389 D LGWifiP2pService: before postfix = G3
08-22 18:32:17.794  1034  1389 D WifiServerServiceExt: postfix byte check : 2
08-22 18:32:17.794  1034  1389 D LGWifiP2pService: after postfix = G3
08-22 18:32:17.794  1034  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-22 18:32:17.794  1034  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-22 18:32:17.794  1034,  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-22 18:32:17.795  1034  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-22 18:32:17.795  1034  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-22 18:32:17.795  1034  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-22 18:32:17.795  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-22 18:32:17.796  1034  1399 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-22 18:32:17.796  1034  1399 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-22 18:32:17.796  1034  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-22 18:32:17.796  7206  7206 E wpa_supplicant: disconnect_rssi_lvl: -100
08-22 18:32:17.796  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:17.796  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-22 18:32:17.796  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-22 18:32:17.797  1034  1399 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-22 18:32:17.797  1034  1399 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-22 18:32:17.798  1034  1399 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-22 18:32:17.798  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-22 18:32:17.798  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-22 18:32:17.799  7206  7206 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.799  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-22 18:32:17.799  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.799  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.799  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.799  7206  7206 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-22 18:32:17.799  7206  7206 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.799  1966  7247 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:17.799  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-22 18:32:17.799  1034  7246 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:17.799  1034  7246 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.800  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.800  1966  1966 D WfdsService: WifiP2pState is changed : true
08-22 18:32:17.800  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.800  1034  1399 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-22 18:32:17.800  1966  1966 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-22 18:32:17.800  7206  7206 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.800  1966  1966 D WfdsService: isConnected: false
08-22 18:32:17.800  1966  2373 D WfdsService: Receive the WFDS_ENABLE Method
08-22 18:32:17.800  1966  2373 D WfdsService: Set the WFDS Monitor: true
08-22 18:32:17.800  1966  2373 D WfdsService: Connected to the supplicant for wfds
08-22 18:32:17.800  1966  2373 D WfdsJNI : doCommand: WFDS_SET TRUE
08-22 18:32:17.801  7206  7206 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-22 18:32:17.801  1966  2373 D WfdsService: selectPreferredScanChannel [36]
08-22 18:32:17.801  1034  7246 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANG,E init=DRIVER type=WORLD]
08-22 18:32:17.801  1966  2373 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-22 18:32:17.801  1034  7246 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.801  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.801  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.801  1966  7247 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:17.801  1034  1399 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-22 18:32:17.801  1034  1399 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-22 18:32:17.802  1034  1399 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-22 18:32:17.802  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-22 18:32:17.803  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-22 18:32:17.803  7206  7206 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:17.803  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-22 18:32:17.803  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:17.803  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:17.804  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-22 18:32:17.804  1034  1399 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-22 18:32:17.804  1034  1399 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-22 18:32:17.804  1034  1389 D LGWifiP2pService: DeviceAddress: 
08-22 18:32:17.804  1034  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-22 18:32:17.804  1034  1399 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-22 18:32:17.804  1034  1399 D WifiNative-wlan0: doBoolean: SCAN
08-22 18:32:17.804  1034  1399 D WifiNative-wlan0: SCAN: returned false
08-22 18:32:17.805  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=206708  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-22 18:32:17.805  1966  1966 I WfdStateTracker: handleP2pThisDeviceChanged
08-22 18:32:17.805  1966  1966 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-22 18:32:17.805  1966  1966 D WfdsService: Update P2p Interface State: 3
08-22 18:32:17.806  1034  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-22 18:32:17.806  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=206709  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-22 18:32:17.806  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-22 18:32:17.806  1034  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-22 18:32:17.806  1034  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-22 18:32:17.806  1034  1399 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:17.806  1034  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-22 18:32:17.806  1034  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-22 18:32:17.807  1034  1399 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:17.807  1034  1399 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:17.807  1034  1399 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:17.808  1034  1399 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-22 18:32:17.809  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:17.809  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.809  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:17.809  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-22 18:32:17.809  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:17.809  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-22 18:32:17.810  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:17.810  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-22 18:32:17.817  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:17.817  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:17.818  6435  7251 V FormManager: Network unavailable.
08-22 18:32:17.818  6435  7250 W FormManager: Network not available. Please check & try again.
08-22 18:32:17.819  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:32:17.820  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:17.820  4250  4250 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-22 18:32:17.821  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:17.821  6435  7251 V FormManager: Network unavailable.
08-22 18:32:17.823  4250  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-22 18:32:17.825  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:17.829  4250  7252 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-22 18:32:17.831  1034  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-22 18:32:17.831  1034  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-22 18:32:17.831  1034  1389 D LGWifiP2pService: InactiveState
08-22 18:32:17.831  1034  1389 D LGWifiP2pService: InactiveState{ when=-32ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.831  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-32ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.831  1034  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-22 18:32:17.832  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-22 18:32:17.832  7206  7206 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.832  7206  7206 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-22 18:32:17.833  7206  7206 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.833  7206  7206 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.833  1034  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-22 18:32:17.833  1034  1389 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.833  1966  7247 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-22 18:32:17.833  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.833  1966  7247 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:17.833  1966  7247 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:17.833  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  7246 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  7246 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.834  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  7246 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:17.834  1034  7246 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.834  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  7246 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-22 18:32:17.834  1034  7246 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.834  1034  7246 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  7246 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:17.834  1966  2373 W WfdsService: DefaultState - msg [9441285] is not handled
08-22 18:32:17.835  1034  1034 E WifiServerServiceExt: No p2p device connected
08-22 18:32:17.835  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:17.836  4250  7253 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-22 18:32:17.836  4250  7253 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-22 18:32:17.840  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:17.844  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:17.845  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:17.846  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:32:17.856  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:32:17.857  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:32:17.866  6211  6289 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-22 18:32:17.866  6211  6289 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-22 18:32:17.868  6211  6289 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2b3c1fa9 Bundle[{}]
,08-22 18:32:17.869  6211  6289 I io.jxcore.node.LifeCycleMonitor: start: OK
08-22 18:32:17.869  6211  6289 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-22 18:32:17.870  6211  6289 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-22 18:32:17.871  6211  6289 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 18:32:17.872  6211  6289 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-22 18:32:17.873  6211  6289 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-22 18:32:17.879  6211  6289 I System.out: Running OutgoingSocketThread
08-22 18:32:17.880  6211  7256 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 796)
08-22 18:32:17.881  6211  7256 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56326
,08-22 18:32:17.881  6211  7256 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-22 18:32:17.886  1034  1964 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7254 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-22 18:32:17.907   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 22.085ms
,08-22 18:32:17.920   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 251us total 11.758ms
08-22 18:32:17.933   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 11.700ms
,08-22 18:32:17.971  7254  7254 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 18:32:17.971  7254  7254 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-22 18:32:17.976  7254  7254 V [BNRBootReceiver]: Boot Receiver Return
08-22 18:32:17.977  7254  7254 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-22 18:32:17.984  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:18.001  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:18.011  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.023  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-22 18:32:18.024  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-22 18:32:18.027  6392  6392 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-22 18:32:18.029  1034  1947 I ActivityManager: Killing 6675:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-22 18:32:18.090  1034  2075 W libprocessgroup: failed to open /acct/uid_10011/pid_6675/cgroup.procs: No such file or directory
,08-22 18:32:18.332  7206  7206 E wpa_supplicant: USIM:  scard_init function
,08-22 18:32:18.339  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-22 18:32:18.341  7206  7206 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-22 18:32:18.348  1034  7246 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-22 18:32:18.350  1034  1399 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-22 18:32:18.352  1034  1399 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-22 18:32:18.353  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-22 18:32:18.353  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: WPS-AP-AVAILABLE 
08-22 18:32:18.353  1034  7246 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-22 18:32:18.353  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-22 18:32:18.353  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-22 18:32:18.354  1034  1399 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-22 18:32:18.354  1034  1399 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-22 18:32:18.354  1034  1399 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-22 18:32:18.371  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=207274  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-22 18:32:18.377  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=207281  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-22 18:32:18.381  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.381  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.381  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-22 18:32:18.382  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.382  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:18.385  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:18.390  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:18.391  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-22 18:32:18.395  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-22 18:32:18.402  6329  6329 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-22 18:32:18.410  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:18.423  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:18.433  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.441  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.442  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.442  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-22 18:32:18.468  7206  7206 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 18:32:18.474  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-22 18:32:18.474  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-22 18:32:18.475  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-22 18:32:18.475  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-22 18:32:18.475  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:18.477  7206  7206 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 18:32:18.477  7206  7206 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-22 18:32:18.475  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:18.483  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:18.483  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:18.483  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-22 18:32:18.483  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 18:32:18.483  1034  7246 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 18:32:18.487  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=207386  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-22 18:32:18.488  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=207391  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-22 18:32:18.488  1034  1399 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=207392
08-22 18:32:18.489  1034  1399 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=207392
08-22 18:32:18.489  1034  1399 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=207393
08-22 18:32:18.490  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=207393
08-22 18:32:18.490  1034  1399 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=207393
08-22 18:32:18.490  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=207394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-22 18:32:18.483  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-22 18:32:18.492  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-22 18:32:18.492  1034  7246 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-22 18:32:18.492  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:18.492  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:18.495  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 18:32:18.497  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.498  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.498  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-22 18:32:18.505  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.505  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:18.507  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:18.523  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.524  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.524  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-22 18:32:18.527  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.528  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-22 18:32:18.531  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=207434  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-22 18:32:18.532  1034  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=207435  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-22 18:32:18.532  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=207436  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-22 18:32:18.534  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.536  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:18.536  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-22 18:32:18.536  1034  1399 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=207440
08-22 18:32:18.537  1034  1399 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=207440
08-22 18:32:18.537  1034  1399 D WifiNative-wlan0: doString: [STATUS]
08-22 18:32:18.538  1034  7246 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-22 18:32:18.538  1034  7246 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-22 18:32:18.540  1034  1399 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-22 18:32:18.542  1034  1399 I WifiServiceExtension: setVHTCapabilityType  : false
,08-22 18:32:18.547  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:18.562  1034  1399 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-22 18:32:18.562  1034  1399 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-22 18:32:18.573  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:18.581  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.581  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:18.584  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.584  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.585  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-22 18:32:18.587  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:18.597  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.597  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.597  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-22 18:32:18.598  1034  1399 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-22 18:32:18.598  1034  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 18:32:18.598  1034  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-22 18:32:18.598  1034  1468 D ConnectivityService: Got NetworkAgent Messenger
08-22 18:32:18.598  1034  1468 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-22 18:32:18.598  1034  1468 D ConnectivityService: NetworkAgent connected
08-22 18:32:18.599  1034  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-22 18:32:18.599  1034  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-22 18:32:18.602  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.607  1034  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-22 18:32:18.607  1034  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 18:32:18.607  1034  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-22 18:32:18.608  1034  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-22 18:32:18.608  1034  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-22 18:32:18.608  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.609  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-22 18:32:18.610  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.611  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.612  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.612  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:18.617  1034  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-22 18:32:18.619  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-22 18:32:18.620  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-22 18:32:18.620   315   894 D CommandListener: Setting iface cfg
08-22 18:32:18.620  6329  6329 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-22 18:32:18.620  6329  6329 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-22 18:32:18.621  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-22 18:32:18.623  6329  6329 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-22 18:32:18.623  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-22 18:32:18.623  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-22 18:32:18.623  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-22 18:32:18.623  6329  6329 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-22 18:32:18.623  6329  6329 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-22 18:32:18.623  6329  6329 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-22 18:32:18.628  1034  1399 E WifiStateMachine: Start Dhcp Watchdog 2
08-22 18:32:18.629  1034  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=207532  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:18.630  1034  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=207533  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:18.631  1034  7298 D DhcpStateMachine: StoppedState
08-22 18:32:18.631  1034  7298 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.631  1034  7298 D DhcpStateMachine: WaitBeforeStartState
08-22 18:32:18.631  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=207534  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:18.632  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-22 18:32:18.634  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:18.636  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:18.636  1034  1399 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:18.636  1034  1399 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:18.637  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-22 18:32:18.637  1034  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-22 18:32:18.640  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:18.640  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-22 18:32:18.640  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:18.640  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-22 18:32:18.641  1034  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=207544  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:18.641  1034  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=207544  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-22 18:32:18.642  1034  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=207545  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-22 18:32:18.643  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14209] from screen [on:0 period:-1290243885] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-22 18:32:18.644  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:18.644  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1290243884] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-22 18:32:18.644  1034  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-22 18:32:18.648  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.649  1034  1468 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-22 18:32:18.650  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.650  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.651  1034  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.652  1034  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.652  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.652  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.653  1034  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.654  1034  1468 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-22 18:32:18.654  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=11,0,0
08-22 18:32:18.654  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=11,0,0
08-22 18:32:18.654  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-22 18:32:18.655  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-22 18:32:18.655  1034  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-22 18:32:18.656  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 0
08-22 18:32:18.656  1034  1399 D WifiNative-wlan0: SET ps 0: returned true
08-22 18:32:18.656  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-22 18:32:18.657  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-22 18:32:18.657  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-22 18:32:18.657  1034  1399 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-22 18:32:18.657  1034  1399 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-22 18:32:18.657  1034  1399 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-22 18:32:18.658  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@293bb16 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.658  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@293bb16 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.658  1034  7298 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.658  1034  7298 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-22 18:32:18.659   315   894 D CommandListener: Setting iface cfg
08-22 18:32:18.660   315   894 D CommandListener: Trying to bring up wlan0
08-22 18:32:18.662  1034  1399 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-22 18:32:18.663  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:18.663  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-22 18:32:18.663  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.664  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.664  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:18.665  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-22 18:32:18.665  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-22 18:32:18.666  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.667  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.667  1034  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.669  1034  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.669  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:18.669  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.669  1034  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-22 18:32:18.670  1034  1468 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-22 18:32:18.671  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-22 18:32:18.672  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-22 18:32:18.673  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-22 18:32:18.673  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.673  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.673  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-22 18:32:18.673  1034  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-22 18:32:18.673  1034  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-22 18:32:18.673  7206  7206 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-22 18:32:18.674  1034  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-22 18:32:18.674  1034  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-22 18:32:18.678  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:18.683  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.690  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.690  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.690  1034  1399 D WifiNative-wlan0: SET ps 1: returned true
08-22 18:32:18.690  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:18.691  1034  1399 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-22 18:32:18.691  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-22 18:32:18.691  1034  1399 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-22 18:32:18.692  1034  1468 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-22 18:32:18.692  1034  1468 D ConnectivityService: ignoring duplicate network state non-change
08-22 18:32:18.696  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.696  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-22 18:32:18.697  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.698  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.698  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.698  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-22 18:32:18.701  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:18.702  1034  1468 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-22 18:32:18.703  1034  1468 D ConnectivityService: Adding iface wlan0 to network 101
08-22 18:32:18.707  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.707  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.707  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-22 18:32:18.709  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-22 18:32:18.711  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-22 18:32:18.712  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.712  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.712  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-22 18:32:18.717  1034  1399 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-22 18:32:18.720  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.720  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-22 18:32:18.721  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-22 18:32:18.723  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.723  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.723  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:32:18.723  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-22 18:32:18.726  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.726  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-22 18:32:18.726  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.727  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:18.728  1034  1468 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-22 18:32:18.728  1034  1468 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-22 18:32:18.729  1034  1468 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-22 18:32:18.730   315   894 E Netd    : netlink response contains error (File exists)
08-22 18:32:18.730  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:32:18.730  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-22 18:32:18.731  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.731  1034  1468 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-22 18:32:18.732  1034  1468 D ConnectivityService: addLocalRoutetoDefaultNetwork
,08-22 18:32:18.732  1034  1468 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-22 18:32:18.732  1034  1468 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-22 18:32:18.733  1034  1468 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-22 18:32:18.733  1034  1468 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-22 18:32:18.733  1034  1468 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-22 18:32:18.733  1034  1468 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-22 18:32:18.733  1034  1468 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:18.733  1034  1468 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:18.733  1034  1468 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-22 18:32:18.734  1034  1468 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.734  1034  1468 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-22 18:32:18.734  1034  1468 D ConnectivityService: currentScore = 0, newScore = 20
08-22 18:32:18.734  1034  1468 D ConnectivityService:    accepting network in place of null
08-22 18:32:18.734  1034  1468 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.735  1034  7293 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.735  1034  7293 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-22 18:32:18.735  1034  7293 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:32:18.735  1034  7293 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-22 18:32:18.736  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.736  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-22 18:32:18.736  1034  1468 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-22 18:32:18.736  1034  1468 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-22 18:32:18.737  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 18:32:18.738  1034  1468 D ConnectivityService: sendStic,kyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-22 18:32:18.738  1034  1468 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-22 18:32:18.738  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-22 18:32:18.738  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-22 18:32:18.738  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-22 18:32:18.738  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-22 18:32:18.738  1034  1399 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.739  1034  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:18.739  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.739  1034  1468 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-22 18:32:18.741  1034  1468 D ConnectivityService: validation of new default Network = false
08-22 18:32:18.741  1034  1468 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-22 18:32:18.741  1034  1468 D DSQN    : enableDataServiceNotify 
08-22 18:32:18.741  1034  1468 D DSQN    : start dsqn bin
08-22 18:32:18.742   315  7304 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-22 18:32:18.743   315  7304 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-22 18:32:18.743   315  7305 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-22 18:32:18.743   315  7305 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,08-22 18:32:18.751  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.751  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.751  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:18.755  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:18.758  1034  1468 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-22 18:32:18.758  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.758  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:18.758  1034  1468 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-22 18:32:18.759  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 18:32:18.748  7307  7307 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:18.748  7307  7307 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:18.774  7307  7307 E DSQN    : DSQN ssw
,08-22 18:32:18.775  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:18.780  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.783  1835  7311 I CheckinService: active receiver: enabled
08-22 18:32:18.792   315  7304 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-22 18:32:18.800  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.800  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.801  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-22 18:32:18.801  1835  7311 I CheckinService: Preparing to send checkin request
08-22 18:32:18.801  1835  7311 I EventLogService: Accumulating logs since 1471883458427
,08-22 18:32:18.804  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-22 18:32:18.805   315  7305 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-22 18:32:18.805  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.806  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.807  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:18.812  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:18.817   315   893 D LGDataListener: argv[0]=dsqncommand
08-22 18:32:18.817   315   893 D LGDataListener: argv[1]=wlan0
08-22 18:32:18.817   315   893 D LGDataListener: argv[2]=1
08-22 18:32:18.817   315   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-22 18:32:18.817  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-22 18:32:18.817  1034  1094 D DSQN    : start to monitor internet connection
08-22 18:32:18.820  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.826  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.826  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.827  6392  6392 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-22 18:32:18.832  1034  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-22 18:32:18.835  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:18.839  7226  7226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-22 18:32:18.842  7226  7226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:18.845  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-22 18:32:18.848  1835  7311 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-22 18:32:18.850  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-22 18:32:18.854  1034  7293 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 16:32:18 GMT], X-Android-Received-Millis=[1471883538854], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471883538817]}
,08-22 18:32:18.854  1034  7293 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-22 18:32:18.854  1034  7293 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-22 18:32:18.855  1034  1468 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-22 18:32:18.855  1034  1468 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-22 18:32:18.855  1034  1468 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:18.855  1034  1468 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:18.855  1034  1468 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-22 18:32:18.855  1034  1468 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-22 18:32:18.855  1034  1468 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-22 18:32:18.855  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.855  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:18.855  1034  1468 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:18.856  1034  1468 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.856  1034  1468 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-22 18:32:18.856  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.856  1034  1399 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:18.856  1034  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:32:18.856  1034  1453 D WifiService: New client listening to asynchronous messages
08-22 18:32:18.856  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-22 18:32:18.856  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.856  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 18:32:18.857  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.858  6392  6392 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-22 18:32:18.858  6392  6392 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-22 18:32:18.858  6392  6392 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-22 18:32:18.860  1034  7298 D DhcpStateMachine: DHCPV4 request on wlan0
08-22 18:32:18.860  1034  7298 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-22 18:32:18.860  1034  7298 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-22 18:32:18.862  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-22 18:32:18.848  7316  7316 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpf,s" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-22 18:32:18.848  7316  7316 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-22 18:32:18.867  7226  7226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-22 18:32:18.867  7226  7226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-22 18:32:18.873  6329  6329 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-22 18:32:18.875  7316  7316 I dhcpcd  : version 5.5.6 starting
08-22 18:32:18.877  7316  7316 E dhcpcd  : get_duid: m
08-22 18:32:18.877  7316  7316 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-22 18:32:18.877  7316  7316 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-22 18:32:18.880  6211  6289 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 797)
08-22 18:32:18.880  6211  6289 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 797)
08-22 18:32:18.884  6211  6289 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 802)
08-22 18:32:18.885  6211  6289 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-22 18:32:18.885  6211  6289 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 803)
08-22 18:32:18.888  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:18.888  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d14328c added. We now have 2 listener(s)
08-22 18:32:18.889  1034  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-22 18:32:18.893  6329  6329 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-22 18:32:18.895  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:18.895  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:18.895  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:18.895  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:18.895  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d485dd5 added. We now have 9 listener(s)
08-22 18:32:18.895  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:18.902  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:32:18.905  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-22 18:32:18.906  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:32:18.908  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-22 18:32:18.909  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-22 18:32:18.923  6392  6392 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:32:18.923  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:32:18.923  6392  6392 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-22 18:32:18.924  6392  6392 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-22 18:32:18.925  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:18.925  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:32:18.925  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:18.925  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c6b4db added. We now have 3 listener(s)
08-22 18:32:18.926  6392  6392 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-22 18:32:18.926  1034  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:18.926  6392  6392 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-22 18:32:18.929  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:18.931  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:18.931  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:18.931  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:18.932  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:18.932  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3117eb78 added. We now have 10 listener(s)
08-22 18:32:18.932  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:18.932  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:32:18.932  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:32:18.932  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:32:18.932  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: di,spose
08-22 18:32:18.932  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.932  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:18.932  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:18.932  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d14328c removed from the list
08-22 18:32:18.932  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:18.932  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d485dd5 removed from the list
08-22 18:32:18.934  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:18.934  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:32:18.934  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:18.935  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.935  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:32:18.936  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:18.936  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:32:18.936  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:18.936  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d485dd5 not in the list
08-22 18:32:18.936  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.936  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:18.937  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:32:18.937  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:18.937  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:32:18.937  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3117eb78 removed from the list
08-22 18:32:18.937  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:18.937  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.937  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:18.937  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:18.937  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c6b4db removed from the list
08-22 18:32:18.937  7316  7316 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-22 18:32:18.937  7316  7316 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-22 18:32:18.937  7316  7316 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-22 18:32:18.938  7316  7316 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-22 18:32:18.938  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:18.938  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7be0251 added. We now have 2 listener(s)
08-22 18:32:18.938  7316  7316 D dhcpcd  : wlan0: sending REQUEST (xid 0x2d9f919a), next in 3.63 seconds
08-22 18:32:18.938  1034  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:18.941  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:18.941  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:18.941  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:18.941  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:18.941  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c41dab6 added. We now have 9 listener(s)
08-22 18:32:18.941  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:18.942  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:32:18.945  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - ,is connected/connecting to active network: true
08-22 18:32:18.948  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:32:18.951  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:32:18.951  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:32:18.952  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:18.952  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9c4724 added. We now have 3 listener(s)
08-22 18:32:18.953  1034  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:18.953  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:18.956  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:18.956  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:18.956  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:18.956  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:18.956  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390f728d added. We now have 10 listener(s)
08-22 18:32:18.956  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:18.956  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:18.956  7316  7316 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-22 18:32:18.956  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:32:18.956  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:32:18.956  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:32:18.956  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:32:18.956  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:32:18.959  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 18:32:18.960  1034  2127 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:18.964  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:32:18.966  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 18:32:18.967  7316  7316 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-22 18:32:18.967  7316  7316 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-22 18:32:18.967  7316  7316 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-22 18:32:18.967  7316  7316 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-22 18:32:18.967  7316  7316 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-22 18:32:18.968  7316  7316 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-22 18:32:18.968  7316  7316 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-22 18:32:18.968  7316  7316 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-22 18:32:18.970  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:32:18.971  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:18.972  6211  6289 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-22 18:32:18.972  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:32:18.972  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:32:18.974  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:32:18.974  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:32:18.974  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:32:18.975  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:18.975  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.975  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:18.975  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:18.975  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7be0251 removed from the list
08-22 18:32:18.975  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:18.975  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c41dab6 removed from the list
08-22 18:32:18.975  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:32:18.975  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:18.976  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.976  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:18.976  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:18.976  6211  6289 I org.thaliproject.p2p.btconnectorl,ib.DiscoveryManager: stopDiscovery
08-22 18:32:18.976  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:18.977  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c41dab6 not in the list
08-22 18:32:18.977  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.977  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:18.978  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:32:18.979  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:32:18.979  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:32:18.979  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:18.979  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:18.980  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390f728d removed from the list
08-22 18:32:18.980  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:18.980  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:18.980  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:18.980  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:18.980  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9c4724 removed from the list
08-22 18:32:18.981  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:18.981  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e8b190 added. We now have 2 listener(s)
08-22 18:32:18.982  1034  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:18.987  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:18.987  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:18.987  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:18.987  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:18.987  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8daa89 added. We now have 9 listener(s)
08-22 18:32:18.987  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:18.988  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:32:18.991  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:32:18.996  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:32:18.997  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:18.998  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:32:18.998  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:18.998  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a3f72af added. We now have 3 listener(s)
08-22 18:32:18.998  1034  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:19.000  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:19.001  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:19.004  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:19.004  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:19.004  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:19.004  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:19.004  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@344f56bc added. We now have 10 listener(s)
08-22 18:32:19.004  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:19.004  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:32:19.005  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:32:19.005  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:32:19.005  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:32:19.005  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:32:19.005  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 18:32:19.008  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 18:32:19.009  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:19.012  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 18:32:19.013  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 18:32:19.014  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 18:32:19.015  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:19.016  6211  6289 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-22 18:32:19.016  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:32:19.016  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:32:19.016  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:32:19.016  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:19.016  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.016  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:19.016  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:19.016  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e8b190 removed from the list
08-22 18:32:19.017  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.017  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8daa89 removed from the list
08-22 18:32:19.017  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:32:19.017  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.017  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.017  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.018  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:19.018  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:32:19.018  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.018  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8daa89 not in the list
08-22 18:32:19.018  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.018  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.018  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:32:19.020  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:32:19.020  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:32:19.020  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:19.020  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.020  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@344f56bc removed from the list
08-22 18:32:19.020  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:19.020  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.020  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.020  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:19.020  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a3f72af removed from the list
08-22 18:32:19.021  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:19.021  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a8acb added. We now have 2 listener(s)
08-22 18:32:19.021  1034  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:19.024  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:19.024  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:19.024  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:19.024  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:19.024  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1922a8 added. We now have 9 listener(s)
08-22 18:32:19.024  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:19.025  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:32:19.028  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:32:19.031  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network ty,pe is Wi-Fi: true
,08-22 18:32:19.033  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:19.033  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:32:19.034  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:19.034  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17545d66 added. We now have 3 listener(s)
08-22 18:32:19.034  1034  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:19.035  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:19.037  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:19.037  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:19.037  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:19.037  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:19.038  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:19.038  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64508a7 added. We now have 10 listener(s)
08-22 18:32:19.038  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:19.038  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:32:19.038  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:32:19.038  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:32:19.038  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:32:19.038  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:32:19.040  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 18:32:19.040  1034  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:19.044  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:32:19.045  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 18:32:19.047  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:32:19.048  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:19.055  6211  6289 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-22 18:32:19.057  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:32:19.057  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:32:19.057  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:32:19.058  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:19.058  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.058  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:19.058  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:19.058  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a8acb removed from the list
08-22 18:32:19.059  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.059  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1922a8 removed from the list
08-22 18:32:19.059  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:32:19.059  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.084  1034  1574 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7334 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-22 18:32:19.084  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.084  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.085  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:19.085  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:32:19.085  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.085  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1922a8 not in the list
,08-22 18:32:19.085  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.085  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.086  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:32:19.087  6211  6289 D BluetoothLeScanner: could not find callback wrapper
08-22 18:32:19.087  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:32:19.087  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:19.087  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.087  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64508a7 removed from the list
08-22 18:32:19.087  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:19.087  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.087  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.087  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:19.087  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17545d66 removed from the list
08-22 18:32:19.088  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:19.088  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b8e9f2 added. We now have 2 listener(s)
08-22 18:32:19.089  1034  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:19.091  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:19.091  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:19.091  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:19.091  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:19.091  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@362f8843 added. We now have 9 listener(s)
08-22 18:32:19.091  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:19.092  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:32:19.094  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:32:19.097  6211  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:32:19.100  6211  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:32:19.100  6211  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:32:19.101  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:32:19.101  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b947f9 added. We now have 3 listener(s)
08-22 18:32:19.101  1034  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 18:32:19.103  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:19.103  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 18:32:19.103  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:32:19.103  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:32:19.103  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:32:19.103  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2767b33e added. We now have 10 listener(s)
08-22 18:32:19.103  6211  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:32:19.104  6211  6289 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:32:19.104  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:32:19.104  6211  6289 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:32:19.104  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:19.104  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.104  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:32:19.104  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:19.104  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b8e9f2 removed from the list
08-22 18:32:19.104  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.104  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@362f8843 removed from the list
08-22 18:32:19.105  6211  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:32:19.105  6211  6289 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:32:19.106  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.106  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.106  6211  6289 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.107  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:19.108  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:32:19.108  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.108  6211  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@362f8843 not in the list
08-22 18:32:19.108  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.108  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.109  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:32:19.109  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:32:19.109  6211  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:32:19.109  6211  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2767b33e removed from the list
08-22 18:32:19.109  6211  6289 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:32:19.109  6211  6289 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:32:19.109  6211  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:32:19.109  6211  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:32:19.110  6211  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b947f9 removed from the list
08-22 18:32:19.111  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-22 18:32:19.111  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-22 18:32:19.111  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 18:32:19.111  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:32:19.112  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 18:32:19.112  6211  6289 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:32:19.133  6211  7355 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 810, name: My test thread name)
08-22 18:32:19.133  6211  7355 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 810, thread name: My test thread name)
,08-22 18:32:19.134  6211  7355 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 810, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-22 18:32:19.137  6211  7357 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 812, name: My test thread name)
08-22 18:32:19.137  6211  7357 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 812, thread name: My test thread name)
08-22 18:32:19.137  6211  7357 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 812, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-22 18:32:19.139  6211  6289 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-22 18:32:19.139  6211  6289 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-22 18:32:19.139  6211  6289 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 18:32:19.139  6211  6289 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 18:32:19.139  6211  6289 D com.test.thalitest.ThaliTestRunner: Total duration: 22941 ms
08-22 18:32:19.140  6211  6289 I jxcore-log: Total number of executed tests:  80
08-22 18:32:19.140  6211  6289 I jxcore-log: 
08-22 18:32:19.140  6211  6289 I jxcore-log: Number of passed tests:  80
08-22 18:32:19.140  6211  6289 I jxcore-log: 
08-22 18:32:19.140  6211  6289 I jxcore-log: Number of failed tests:  0
08-22 18:32:19.140  6211  6289 I jxcore-log: 
08-22 18:32:19.141  6211  6289 I jxcore-log: Number of ignored tests:  0
08-22 18:32:19.141  6211  6289 I jxcore-log: 
08-22 18:32:19.141  6211  6289 I jxcore-log: Total duration:  22941
08-22 18:32:19.141  6211  6289 I jxcore-log: 
08-22 18:32:19.141  6211  6289 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 18:32:19.141  6211  6289 I jxcore-log: 
08-22 18:32:19.142  7334  7334 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-22 18:32:19.143  7334  7334 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-22 18:32:19.144  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.144  6211  6289 I jxcore-log: 
08-22 18:32:19.147  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.147  6211  6289 I jxcore-log: 
08-22 18:32:19.148  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.148  6211  6289 I jxcore-log: 
08-22 18:32:19.149  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.149  6211  6289 I jxcore-log: 
08-22 18:32:19.150  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.150  6211  6289 I jxcore-log: 
08-22 18:32:19.151  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.151  6211  6289 I jxcore-log: 
08-22 18:32:19.154  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.154  6211  6289 I jxcore-log: 
08-22 18:32:19.155  6211  6211 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-22 18:32:19.157  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.157  6211  6289 I jxcore-log: 
08-22 18:32:19.158  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.158  6211  6289 I jxcore-log: 
08-22 18:32:19.159  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:32:19.159  6211  6289 I jxcore-log: 
08-22 18:32:19.160  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.160  6211  6289 I jxcore-log: 
08-22 18:32:19.161  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.161  6211  6289 I jxcore-log: 
08-22 18:32:19.162  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.162  6211  6289 I jxcore-log: 
08-22 18:32:19.163  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.163  6211  6289 I jxcore-log: 
08-22 18:32:19.164  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.164  6211  6289 I jxcore-log: 
08-22 18:32:19.165  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.165  6211  6289 I jxcore-log: 
08-22 18:32:19.166  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.166  6211  6289 I jxcore-log: 
08-22 18:32:19.167  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.167  6211  6289 I jxcore-log: 
08-22 18:32:19.168  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.168  6211  6289 I jxcore-log: 
08-22 18:32:19.169  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:32:19.169  6211  6289 I jxcore-log: 
08-22 18:32:19.169  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.169  6211  6289 I jxcore-log: 
08-22 18:32:19.170  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:32:19.170  6211  6289 I jxcore-log: 
08-22 18:32:19.171  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:32:19.171  6211  6289 I jxcore-log: 
08-22 18:32:19.171  7334  7334 I MultiDex: VM with version 2.1.0 has multidex support
08-22 18:32:19.172  7334  7334 I MultiDex: install
08-22 18:32:19.172  7334  7334 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-22 18:32:19.172  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:32:19.172  6211  6289 I jxcore-log: 
08-22 18:32:19.173  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:32:19.173  6211  6289 I jxcore-log: 
08-22 18:32:19.174  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:32:19.174  6211  6289 I jxcore-log: 
08-22 18:32:19.174  6211  6289 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:32:19.174  6211  6289 I jxcore-log: 
08-22 18:32:19.181  7334  7334 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-22 18:32:19.184  2221  2221 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-22 18:32:19.191  2221  2221 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-22 18:32:19.192  2221  2221 D c       : Getting all permits...
08-22 18:32:19.192  2221  2221 D a       : Opening database...
08-22 18:32:19.195  2221  2221 D a       : Opening database auth.proximity.permit_store...
08-22 18:32:19.195  2221  2221 D a       : Closing database...
,08-22 18:32:19.262  1034  7298 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-22 18:32:19.264  1034  7298 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-22 18:32:19.264  1034  7298 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-22 18:32:19.265  1034  7298 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-22 18:32:19.265  1034  7298 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-22 18:32:19.265  1034  7298 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-22 18:32:19.265  1034  7298 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-22 18:32:19.265  1034  7298 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-22 18:32:19.266  1034  7298 D DhcpStateMachine: RunningState
08-22 18:32:19.439  7365  7365 D AndroidRuntime: 
08-22 18:32:19.439  7365  7365 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 18:32:19.441  7365  7365 D AndroidRuntime: CheckJNI is OFF
,08-22 18:32:19.608  7365  7365 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 18:32:19.621  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-22 18:32:19.622  1034  1092 I ActivityManager: Killing 6211:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-22 18:32:19.675  1034  2004 I WindowState: WIN DEATH: Window{132b406a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 18:32:19.677  1034  1453 D WifiService: Client connection lost with reason: 4
,08-22 18:32:19.682  1034  2004 D InputDispatcher: Window went away: Window{132b406a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 18:32:19.732  7382  7382 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-22 18:32:19.800  7382  7382 I dex2oat : dex2oat took 67.998ms (threads: 4)
,08-22 18:32:19.831  7334  7354 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 18:32:19.831  7334  7354 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 18:32:19.831  7334  7354 I Adreno-EGL: Build Date: 12/12/14 금
08-22 18:32:19.831  7334  7354 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-22 18:32:19.831  7334  7354 I Adreno-EGL: Remote Branch: 
08-22 18:32:19.831  7334  7354 I Adreno-EGL: Local Patches: 
08-22 18:32:19.831  7334  7354 I Adreno-EGL: Reconstruct Branch: 
08-22 18:32:19.832  1034  1092 E libprocessgroup: failed to kill 1 processes for processgroup 6211
,08-22 18:32:19.834  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{2b7f4a57 u0 com.test.thalitest/.MainActivity t6}
,08-22 18:32:19.871   343   352 E GBMv2   : DFP En is all cleared set to be enabled
,08-22 18:32:19.874  1034  1983 W ActivityManager: Spurious death for ProcessRecord{25fb2277 6211:com.test.thalitest/u0a118}, curProc for 6211: null
08-22 18:32:19.875  1034  1109 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-22 18:32:19.877  1034  1109 I ActivityManager:   Force finishing activity ActivityRecord{2b7f4a57 u0 com.test.thalitest/.MainActivity t6 f}
08-22 18:32:19.877  1034  1109 W ActivityManager: Duplicate finish request for ActivityRecord{2b7f4a57 u0 com.test.thalitest/.MainActivity t6 f}
,08-22 18:32:19.918  2076  2076 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-22 18:32:19.919  1966  7394 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-22 18:32:19.919  1966  7394 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9fa426f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-22 18:32:19.920  1966  1981 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,08-22 18:32:19.921  1966  1981 D SplitWindowPolicy: topRunningActivity=ActivityInfo{10a64b7c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-22 18:32:19.921  2076  2076 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-22 18:32:19.925  2076  2076 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-22 18:32:19.927  2076  2194 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-22 18:32:19.930  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-22 18:32:19.937  2472  2627 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 18:32:19.937  7030  7030 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-22 18:32:19.937  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-22 18:32:19.938  3624  3624 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-22 18:32:19.947  2040  2040 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-22 18:32:19.962  1034  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 18:32:19.966  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-22 18:32:19.989  2076  2076 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-22 18:32:19.990  1928  1928 D ActionManagerService: notifyUserLog: 1000003
,08-22 18:32:19.991  2076  2076 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-22 18:32:19.992  3624  4431 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-22 18:32:19.995  3660  3660 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-22 18:32:20.028  1034  2127 V SIM_STK : Menu title from STK is T-Mobile
08-22 18:32:20.028  1034  2075 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7396 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-22 18:32:20.036  4538  4538 I art     : Explicit concurrent mark sweep GC freed 763(44KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 707us total 136.021ms
08-22 18:32:20.038  1894  1894 D SplitUIManager: split_name #11 / not available #0
08-22 18:32:20.038  1894  1894 D SplitUIService: removed split : 
08-22 18:32:20.039  1835  1835 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-22 18:32:20.040  2076  2076 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-22 18:32:20.042  2076  2076 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-22 18:32:20.045  1034  1946 V SIM_STK : Menu title from STK is T-Mobile
08-22 18:32:20.045  1034  1946 V SIM_STK : Menu title from STK is T-Mobile
08-22 18:32:20.051  1928  1928 D ActionManagerService: notifyUserLog: 1000004
08-22 18:32:20.052  2076  2076 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-22 18:32:20.052  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-22 18:32:20.053  3624  4431 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-22 18:32:20.058  2221  2221 I ConfigService: onCreate
08-22 18:32:20.059  3624  3639 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , create_time: 1430832262123
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , expire_time: 0
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , display: false
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , animation: false }
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , create_time: 1430832262287
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , expire_time: 0
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , display: false
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , animation: false }
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , create_time: 1471602816196
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , expire_time: 0
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , display: false
08-22 18:32:20.060  2076  2076 I GBoardWebViewUtils: , animation: false }
08-22 18:32:20.066  2221  2221 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-22 18:32:20.071  1835  1835 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-22 18:32:20.075  2076  2076 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 18:32:20.076  2076  2076 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-22 18:32:20.077  4409  4409 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-22 18:32:20.077  4409  4409 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-22 18:32:20.077  4409  4409 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-22 18:32:20.077  4409  4409 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-22 18:32:20.077  4409  4409 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 18:32:20.077  4409  4409 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 18:32:20.077  4409  4409 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-22 18:32:20.077  4409  4409 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-22 18:32:20.077  4409  4409 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:32:20.077  4409  4409 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:32:20.07,7  4409  4409 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-22 18:32:20.077  4409  4409 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-22 18:32:20.080  2221  2221 I ConfigService: onBind returning update interface
08-22 18:32:20.085  2221  2221 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-22 18:32:20.085  2221  2221 I ConfigService: onBind returning config service
,08-22 18:32:20.088  2221  2221 I ConfigService: onDestroy
08-22 18:32:20.094  2076  7415 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-22 18:32:20.106  1034  1034 I art     : Explicit concurrent mark sweep GC freed 79832(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 6.542ms total 195.833ms
08-22 18:32:20.111  1894  1894 D SplitUIManager: split_name #11 / not available #0
08-22 18:32:20.111  1894  1894 I SplitUIService: split app #11
08-22 18:32:20.136  1034  1574 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-22 18:32:20.137  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-22 18:32:20.138  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-22 18:32:20.138  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-22 18:32:20.138  7030  7030 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-22 18:32:20.146  1835  5804 I art     : Explicit concurrent mark sweep GC freed 19178(1335KB) AllocSpace objects, 17(272KB) LOS objects, 51% free, 29MB/61MB, paused 805us total 32.462ms
08-22 18:32:20.151  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-22 18:32:20.151  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-22 18:32:20.154  2076  2076 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-22 18:32:20.156  2076  2090 I art     : Background sticky concurrent mark sweep GC freed 2111(118KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 16.643ms total 33.256ms
08-22 18:32:20.158  1835  7417 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-22 18:32:20.185  1034  1050 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7420 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-22 18:32:20.186  7396  7396 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,08-22 18:32:20.198  1034  1034 D administrator: Handling package changes for user 0
08-22 18:32:20.225  5538  7439 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-22 18:32:20.238   337   432 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-22 18:32:20.238  3282  7442 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-22 18:32:20.248  1835  7443 I PeopleContactsSync: CP2 sync disabled
08-22 18:32:20.249  1601  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-22 18:32:20.249  1601  1655 D KeyguardModel: createShortcutInfo...
,08-22 18:32:20.259  1034  1776 V SIM_STK : Menu title from STK is T-Mobile
08-22 18:32:20.259  7334  7354 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 18:32:20.259  7334  7354 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 18:32:20.259  7334  7354 I Adreno-EGL: Build Date: 12/12/14 금
08-22 18:32:20.259  7334  7354 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-22 18:32:20.259  7334  7354 I Adreno-EGL: Remote Branch: 
08-22 18:32:20.259  7334  7354 I Adreno-EGL: Local Patches: 
08-22 18:32:20.259  7334  7354 I Adreno-EGL: Reconstruct Branch: 
08-22 18:32:20.277  1835  7438 W GmsApplication: Using Auth Proxy for data requests.
08-22 18:32:20.282  1835  7438 W GmsApplication: Using Auth Proxy for data requests.
,08-22 18:32:20.294  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-22 18:32:20.298  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 18:32:20.300  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-22 18:32:20.301  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-22 18:32:20.302  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-22 18:32:20.303  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-22 18:32:20.314  1601  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-22 18:32:20.314  1601  1655 D KeyguardModel: createShortcutInfo...
,08-22 18:32:20.318  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-22 18:32:20.318  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 18:32:20.318  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-22 18:32:20.320  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{189d4d6a u0 com.lge.launcher2/.Launcher t5} time:209235
08-22 18:32:20.320  1034  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-22 18:32:20.323  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-22 18:32:20.323  1601  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:32:20.323  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-22 18:32:20.324  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-22 18:32:20.325  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 18:32:20.325  1601  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-22 18:32:20.325  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-22 18:32:20.325  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 18:32:20.327  1835  4691 I Icing   : doRemovePackageData com.test.thalitest
08-22 18:32:20.329  2076  2852 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-22 18:32:20.329  2076  2852 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-22 18:32:20.336  1601  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-22 18:32:20.336  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.336  7334  7354 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 18:32:20.336  7334  7354 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 18:32:20.336  7334  7354 I Adreno-EGL: Build Date: 12/12/14 금
08-22 18:32:20.336  7334  7354 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-22 18:32:20.336  7334  7354 I Adreno-EGL: Remote Branch: 
08-22 18:32:20.336  7334  7354 I Adreno-EGL: Local Patches: 
08-22 18:32:20.336  7334  7354 I Adreno-EGL: Reconstruct Branch: 
08-22 18:32:20.341  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-22 18:32:20.341  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-22 18:32:20.342  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-22 18:32:20.343  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-22 18:32:20.343  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 18:32:20.343  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 18:32:20.343  1601  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-22 18:32:20.345  1601  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-22 18:32:20.346  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.349  1601  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:32:20.349  1601  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-22 18:32:20.349  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-22 18:32:20.349  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-22 18:32:20.349  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 18:32:20.350  1601  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-22 18:32:20.351  1601  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-22 18:32:20.351  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.352  2076  2076 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-22 18:32:20.353  2671  2671 D [Concierge]Service: onStartCommand(). Type : 8
08-22 18:32:20.353  2671  2671 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-22 18:32:20.354  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-22 18:32:20.354  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-22 18:32:20.356  2076  2076 D [Concierge]WidgetView: change position of spinner
,08-22 18:32:20.359  2671  2671 D [Concierge]Service: Update widget ID : 11
08-22 18:32:20.360  2671  2671 D [Concierge]Service: onStartCommand(). Type : 0
08-22 18:32:20.360  2076  2076 I [Concierge]WidgetView: initWebView(). Time : 1471883540360
08-22 18:32:20.364  1601  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-22 18:32:20.364  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.367  1601  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-22 18:32:20.367  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.368  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 18:32:20.368  1601  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-22 18:32:20.371  1601  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-22 18:32:20.371  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.374  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 18:32:20.374  1601  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-22 18:32:20.377  2076  2076 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 318299011
08-22 18:32:20.377  2076  2076 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-22 18:32:20.378  2076  2076 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-22 18:32:20.380  1601  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-22 18:32:20.380  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.381  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 18:32:20.381  1601  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-22 18:32:20.382  2076  2076 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3895ec4e
08-22 18:32:20.382  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-22 18:32:20.382  1601  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-22 18:32:20.382  1601  1655 D KeyguardModel: createShortcutInfo...
08-22 18:32:20.384  2221  2246 I art     : Explicit concurrent mark sweep GC freed 5106(291KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 868us total 29.550ms
08-22 18:32:20.385  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-22 18:32:20.385  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 18:32:20.387  7420  7420 I AppUp4:AppBoxCP: onCreate
08-22 18:32:20.389  7420  7420 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-22 18:32:20.392  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-22 18:32:20.392  2076  2076 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-22 18:32:20.393  2076  2076 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-22 18:32:20.393  2076  2076 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471883359601, New one : 1471883540360
08-22 18:32:20.393  2076  2076 D [Concierge]WidgetView: Unregister all receivers
08-22 18:32:20.393  2076  2076 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-22 18:32:20.394  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 18:32:20.394  7420  7420 I AppUp4:DB:  setFingerPrint start
08-22 18:32:20.394  7420  7420 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-22 18:32:20.395  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-22 18:32:20.397  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-22 18:32:20.398  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-22 18:32:20.399  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-22 18:32:20.400  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-22 18:32:20.405  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 18:32:20.405  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 18:32:20.406  7420  7420 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-22 18:32:20.406  7420  7420 I AppUp4:DB:  SDK version = 21
08-22 18:32:20.406  7420  7420 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-22 18:32:20.408  1034  2033 I ActivityManager: Killing 6724:com.lge.email/u0a23 (adj 15): empty #17
08-22 18:32:20.412  7334  7354 D LgDataFeature: LgDataFeature() Constructor: none
08-22 18:32:20.412  7334  7354 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 18:32:20.453  2076  2076 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-22 18:32:20.462  2076  2076 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-22 18:32:20.462  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-22 18:32:20.464  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-22 18:32:20.484  2076  2076 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3829508f time:209398
,08-22 18:32:20.512  1034  1109 I art     : Explicit concurrent mark sweep GC freed 12701(802KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.107ms total 312.111ms
,08-22 18:32:20.547  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 18:32:20.554  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-22 18:32:20.556  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-22 18:32:20.556  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-22 18:32:20.556  1034  2037 W libprocessgroup: failed to open /acct/uid_10023/pid_6724/cgroup.procs: No such file or directory
08-22 18:32:20.557  1034  1399 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-22 18:32:20.557  1034  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-22 18:32:20.557  1034  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-22 18:32:20.558  1034  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-22 18:32:20.558  1034  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-22 18:32:20.558  1034  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-22 18:32:20.559  1034  1468 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-22 18:32:20.559  1034  1468 D ConnectivityService: identical MTU - not setting
08-22 18:32:20.559  1034  1468 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-22 18:32:20.559  1034  1468 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-22 18:32:20.559  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:32:20.559  1034  1468 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-22 18:32:20.560  1034  1468 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-22 18:32:20.560  1601  1809 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-22 18:32:20.562  7420  7420 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-22 18:32:20.568  2076  2076 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-22 18:32:20.585  7420  7420 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-22 18:32:20.588  7365  7365 D AndroidRuntime: Shutting down VM
08-22 18:32:20.606   315  7449 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-22 18:32:20.606   315  7449 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-22 18:32:20.614  1034  1983 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7450 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-22 18:32:20.614  1034  1983 I ActivityManager: Killing 6799:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-22 18:32:20.630  2076  2076 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-22 18:32:20.658   315  7449 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-22 18:32:20.677  2076  2883 I GBoardtInterface: onReloaded()
,08-22 18:32:20.679  2076  2076 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-22 18:32:20.687  1034  1964 W libprocessgroup: failed to open /acct/uid_10046/pid_6799/cgroup.procs: No such file or directory
,08-22 18:32:20.698  3624  3639 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-22 18:32:20.700  3624  4407 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-22 18:32:20.705  1928  1928 D ActionManagerService: notifyUserLog: 1000001
08-22 18:32:20.706  3624  4431 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-22 18:32:20.706  3624  4431 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-22 18:32:20.708  7450  7450 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:32:20.708  7450  7450 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-22 18:32:20.709  7450  7450 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-22 18:32:20.709  1928  1928 D ActionManagerService: notifyUserLog: 1000001
08-22 18:32:20.709  7450  7450 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-22 18:32:20.709  7450  7450 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-22 18:32:20.710  3624  4431 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-22 18:32:20.710  3624  4431 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-22 18:32:20.710  3624  4431 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-22 18:32:20.710  3624  3639 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-22 18:32:20.711  3624  4431 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-22 18:32:20.712  2076  2076 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-22 18:32:20.712  2076  2076 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-22 18:32:20.714  2076  2076 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-22 18:32:20.714  2076  2076 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-22 18:32:20.716  2076  2076 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-22 18:32:20.716  2076  2076 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-22 18:32:20.730  1835  7311 I CheckinTask: Sending checkin request (7969 bytes)
,08-22 18:32:20.762  7450  7450 I SystemConfig: BUILD Country: EU
08-22 18:32:20.763  7450  7450 I SystemConfig: BUILD Operator: OPEN
,08-22 18:32:20.830  1034  1109 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7469 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-22 18:32:20.831  1034  2075 I ActivityManager: Killing 6835:com.android.chrome/u0a57 (adj 15): empty #17
08-22 18:32:20.903   343   354 E GBMv2   : DFP En is all cleared set to be enabled
08-22 18:32:20.903   343   354 E GBMv2   : Set value is all cleared set the max
08-22 18:32:20.903   343   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-22 18:32:20.917  1034  1983 W libprocessgroup: failed to open /acct/uid_10057/pid_6835/cgroup.procs: No such file or directory
,08-22 18:32:20.927  7450  7467 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-22 18:32:20.927  7450  7467 I SystemConfig: existFile = false
08-22 18:32:20.928  7450  7467 I SystemConfig: canReadFile = false
08-22 18:32:20.928  7450  7467 I SystemConfig: systemFeature RCS result false
08-22 18:32:20.928  7450  7467 D SystemConfig: refreshRcsSupport() :false
08-22 18:32:20.929  2201  7491 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-22 18:32:20.931  2201  2363 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-22 18:32:20.932  2201  2363 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 18:32:20.947  1034  1574 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7492 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-22 18:32:20.950  2201  7491 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-22 18:32:20.951  2201  7491 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-22 18:32:20.951  2201  7491 E AndroidRuntime: Process: android.process.acore, PID: 2201
08-22 18:32:20.951  2201  7491 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-22 18:32:20.951  2201  7491 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 18:32:20.954  4409  4479 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: Error inserting f004=13 f005=7492 f002=1471883540949 f003=com.lge.email f006=10023
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-22 18:32:20.955  4409  4479 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider
```
