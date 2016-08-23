#### Test 79763830b1f5deb_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 17:05:00.071  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:05:00.083  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:05:08.374  6207  6207 D AndroidRuntime: 
08-23 17:05:08.374  6207  6207 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 17:05:08.381  6207  6207 D AndroidRuntime: CheckJNI is OFF
08-23 17:05:08.585  6207  6207 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 17:05:08.596  1033  1998 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 17:05:08.612  1945  3911 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 17:05:08.618  1033  1998 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 17:05:08.620  1033  1998 D ActivityManager: setTaskToReturnTo : TaskRecord{39277612 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 17:05:08.620  1033  1998 D ActivityManager: setTaskToReturnTo : TaskRecord{39277612 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 17:05:08.622  1033  1998 D WindowStateEx: AppWindowTokenEx init.. 
08-23 17:05:08.623   342   360 E GBMv2   : DFP En is all cleared set to be enabled
08-23 17:05:08.652  1033  1998 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6222 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 17:05:08.654  6207  6207 D AndroidRuntime: Shutting down VM
08-23 17:05:08.711  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 17:05:08.711  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35103429 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 17:05:08.712  1945  1962 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 17:05:08.712  1945  1962 D SplitWindowPolicy: topRunningActivity=ActivityInfo{880e3ae co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 17:05:08.768  6222  6222 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 17:05:08.840  6222  6222 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 17:05:08.847  6222  6222 I LibraryLoader: Loading: webviewchromium
08-23 17:05:08.850  6222  6222 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3180-3183)
08-23 17:05:08.850  6222  6222 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 17:05:08.874  6222  6222 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d6942d5}
,08-23 17:05:08.877  6222  6222 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 17:05:08.878  6222  6222 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 17:05:08.888  6222  6222 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 17:05:08.889  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 17:05:08.900  6222  6247 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-23 17:05:08.906  6222  6222 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-23 17:05:08.909  6222  6222 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 17:05:08.910  6222  6222 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 17:05:08.920   317  1788 V AudioPolicyService: registerClient() client 0xb1019320, uid 10118
,08-23 17:05:08.925  1033  1111 D BluetoothManagerService: Message: 20
08-23 17:05:08.925  1033  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1019120c:true
08-23 17:05:08.949  6222  6222 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 17:05:08.949  6222  6222 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 17:05:08.949  6222  6222 I Adreno-EGL: Build Date: 12/12/14 금
08-23 17:05:08.949  6222  6222 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 17:05:08.949  6222  6222 I Adreno-EGL: Remote Branch: 
08-23 17:05:08.949  6222  6222 I Adreno-EGL: Local Patches: 
08-23 17:05:08.949  6222  6222 I Adreno-EGL: Reconstruct Branch: 
,08-23 17:05:09.034  6222  6257 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 17:05:09.038  6222  6222 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 17:05:09.053  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 17:05:09.058  6222  6222 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 17:05:09.062  6222  6222 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 17:05:09.064  6222  6222 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 17:05:09.064  6222  6222 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-23 17:05:09.078  6222  6222 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-23 17:05:09.084  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 17:05:09.084  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 17:05:09.126  6222  6269 D OpenGLRenderer: Render dirty regions requested: true
08-23 17:05:09.126  6222  6269 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 17:05:09.134  6222  6269 D OpenGLRenderer: Enabling debug mode 0
,08-23 17:05:09.144  6222  6222 D Atlas   : Validating map...
08-23 17:05:09.148  1033  2035 D SplitWindow: check instance of lgWin Window{390620e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 17:05:09.191  6222  6267 D LgDataFeature: LgDataFeature() Constructor: none
08-23 17:05:09.192  6222  6267 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 17:05:09.210  1033  1093 W ActivityManager: Activity pause timeout for ActivityRecord{3fb2f1e3 u0 com.test.thalitest/.MainActivity t6}
,08-23 17:05:09.256  1033  1900 I art     : Explicit concurrent mark sweep GC freed 39723(1809KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 42MB/64MB, paused 1.954ms total 96.571ms
,08-23 17:05:09.362  1033  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +652ms (total +738ms)
08-23 17:05:09.363  1033  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fb2f1e3 u0 com.test.thalitest/.MainActivity t6} time:163696
08-23 17:05:09.365  6222  6222 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c534ba8 time:163699
,08-23 17:05:09.455  6222  6222 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 17:05:09.485  6222  6222 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 17:05:09.485  6222  6222 I chromium: 
,08-23 17:05:09.628  6222  6280 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435139584
,08-23 17:05:09.644  6222  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 17:05:09.644  6222  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 17:05:09.644  6222  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 17:05:09.644  6222  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 17:05:09.644  6222  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 17:05:09.644  6222  6280 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1645bfec added. We now have 1 listener(s)
,08-23 17:05:09.651  1033  1586 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 17:05:09.653  6222  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 17:05:09.657  6222  6280 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-23 17:05:09.660  6222  6280 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 17:05:09.661  6222  6280 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 17:05:09.670  6222  6280 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@158229bb added. We now have 1 listener(s)
08-23 17:05:09.670  6222  6280 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 17:05:09.674  1033  1545 D WifiService: New client listening to asynchronous messages
08-23 17:05:09.679  6222  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 17:05:09.679  6222  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 17:05:09.681  6222  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 17:05:09.681  6222  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 17:05:09.681  6222  6280 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 17:05:09.686  6222  6280 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 17:05:09.688  1033  2039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 17:05:09.689  6222  6280 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 17:05:09.706  6222  6280 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 17:05:09.707  6222  6280 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 17:05:09.708  6222  6280 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 17:05:09.708  6222  6280 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 17:05:09.712  6222  6222 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 17:05:09.715  6222  6280 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 17:05:09.761  6222  6267 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 17:05:09.761  6222  6267 I chromium: 
,08-23 17:05:09.840  6222  6222 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 17:05:10.483  6222  6283 W jxcore-log: Initializing JXcore engine
08-23 17:05:10.483  6222  6283 W jxcore-log: JXcore engine is ready
,08-23 17:05:10.488   342   362 E GBMv2   : DFP En is all cleared set to be enabled
08-23 17:05:10.488   342   362 E GBMv2   : Set value is all cleared set the max
08-23 17:05:10.489   342   362 I GBMv2   : DFP Enabled. Ignore VFP set
08-23 17:05:10.509  6283  6283 W Thread-692: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10269]" dev="sockfs" ino=10269 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 17:05:10.509  6283  6283 W Thread-692: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 17:05:10.509  6283  6283 W Thread-692: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9970]" dev="sockfs" ino=9970 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 17:05:10.509  6283  6283 W Thread-692: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-23 17:05:10.509  6283  6283 W Thread-692: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[29952]" dev="sockfs" ino=29952 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-23 17:05:10.535  6222  6283 W jxcore-log: Starting JXcore engine
08-23 17:05:10.615  6222  6283 W jxcore-log: Platform android
08-23 17:05:10.615  6222  6283 W jxcore-log: 
08-23 17:05:10.615  6222  6283 W jxcore-log: Process ARCH arm
08-23 17:05:10.615  6222  6283 W jxcore-log: 
,08-23 17:05:10.804  6222  6283 I jxcore-log: JXcore Cordova bridge is ready!
08-23 17:05:10.804  6222  6283 I jxcore-log: 
08-23 17:05:10.805  6222  6283 W jxcore-log: JXcore engine is started
,08-23 17:05:10.817  6222  6280 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 17:05:10.821  6222  6222 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 17:05:21.914  1033  1391 V AlarmManager: ELAPSED_WAKEUP set : Alarm{385e866c type 2 when 176224 com.google.android.gms} when 176224
,08-23 17:05:22.568  6222  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 17:05:22.568  6222  6283 I jxcore-log: 
,08-23 17:05:22.575  6222  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 17:05:22.575  6222  6283 I jxcore-log: 
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 17:05:22.579  6222  6283 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 17:05:22.584  6222  6283 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 17:05:22.587  6222  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 17:05:22.587  6222  6283 I jxcore-log: 
08-23 17:05:22.590  6222  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 17:05:22.590  6222  6283 I jxcore-log: 
08-23 17:05:23.544  6222  6283 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-23 17:05:23.544  6222  6283 I jxcore-log: Failed to execute UT.
08-23 17:05:23.544  6222  6283 I jxcore-log: 
,08-23 17:05:23.549  6222  6283 I jxcore-log: Unit Test app is loaded
08-23 17:05:23.549  6222  6283 I jxcore-log: 
08-23 17:05:23.565  6222  6283 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 17:05:23.565  6222  6283 I jxcore-log: 
,08-23 17:05:23.574  6222  6222 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 17:05:23.582  6222  6283 I jxcore-log: My device name is: LGE-LG-D855
08-23 17:05:23.582  6222  6283 I jxcore-log: 
08-23 17:05:23.584  6222  6283 I jxcore-log: WARN testUtils: myNameCallback not set!
08-23 17:05:23.584  6222  6283 I jxcore-log: 
,08-23 17:05:31.347  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 17:05:31.347  6222  6283 I jxcore-log: 
,08-23 17:05:32.455  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 17:05:32.455  6222  6283 I jxcore-log: 
,08-23 17:05:32.481  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 17:05:32.481  6222  6283 I jxcore-log: 
,08-23 17:05:32.486  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 17:05:32.486  6222  6283 I jxcore-log: 
08-23 17:05:32.501  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 17:05:32.501  6222  6283 I jxcore-log: 
,08-23 17:05:32.505  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 17:05:32.505  6222  6283 I jxcore-log: 
08-23 17:05:35.620  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 17:05:35.620  6222  6283 I jxcore-log: 
,08-23 17:05:35.633  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-23 17:05:35.633  6222  6283 I jxcore-log: 
,08-23 17:05:35.643  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-23 17:05:35.643  6222  6283 I jxcore-log: 
08-23 17:05:35.800  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 17:05:35.800  6222  6283 I jxcore-log: 
,08-23 17:05:36.598  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 17:05:36.598  6222  6283 I jxcore-log: 
,08-23 17:05:36.842  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 17:05:36.842  6222  6283 I jxcore-log: 
,08-23 17:05:36.848  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-23 17:05:36.848  6222  6283 I jxcore-log: 
,08-23 17:05:37.035  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 17:05:37.035  6222  6283 I jxcore-log: 
,08-23 17:05:37.057  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 17:05:37.057  6222  6283 I jxcore-log: 
,08-23 17:05:37.061  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 17:05:37.061  6222  6283 I jxcore-log: 
,08-23 17:05:37.067  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 17:05:37.067  6222  6283 I jxcore-log: 
,08-23 17:05:37.081  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-23 17:05:37.081  6222  6283 I jxcore-log: 
,08-23 17:05:37.099  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-23 17:05:37.099  6222  6283 I jxcore-log: 
,08-23 17:05:37.179  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-23 17:05:37.179  6222  6283 I jxcore-log: 
,08-23 17:05:37.185  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-23 17:05:37.185  6222  6283 I jxcore-log: 
,08-23 17:05:37.210  6222  6283 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-23 17:05:37.210  6222  6283 I jxcore-log: 
,08-23 17:05:37.222  6222  6283 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-23 17:05:37.224  6222  6283 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-23 17:05:37.224  6222  6283 I jxcore-log: 
,08-23 17:06:00.038  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:06:00.038  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:06:00.039  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:06:00.039  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:06:00.050  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:06:00.051  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:06:00.053  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:06:00.055  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 17:06:27.458  1033  1391 D PowerManagerServiceEx: acquireWakeLockInternal: lock=690155694, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-23 17:06:27.469  1033  1391 V AlarmManager: ELAPSED_WAKEUP set : Alarm{37d630ca type 2 when 222105 android} when 222105
08-23 17:06:27.483   313  6314 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-23 17:06:27.486  1033  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-23 17:06:27.511  2587  2587 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 17:06:27.545  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=690155694 [*alarm*], flags=0x0
,08-23 17:07:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:07:00.051  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:07:00.051  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:07:00.051  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:07:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:07:00.062  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:07:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:07:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:08:00.052  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:08:00.052  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:08:00.052  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:08:00.053  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:08:00.063  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:08:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:08:00.066  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:08:00.069  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:08:00.410  1033  3504 I LocationManagerService: remove 16231a2e
,08-23 17:08:00.413  1033  3504 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-23 17:08:00.413  1033  3504 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 17:08:00.414  1033  3504 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-23 17:08:00.415  1033  3504 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-23 17:08:00.415  1033  3504 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-23 17:08:11.491  1033  1391 D PowerManagerServiceEx: acquireWakeLockInternal: lock=690155694, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-23 17:08:11.543  2587  2587 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 17:08:11.574  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=690155694 [*alarm*], flags=0x0
,08-23 17:09:00.051  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:09:00.052  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:09:00.052  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:09:00.052  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:09:00.063  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:09:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:09:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:09:00.069  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:10:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:10:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:10:00.051  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:10:00.051  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:10:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:10:00.062  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:10:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:10:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:10:34.827  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 17:10:34.827  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 17:10:34.838  1945  2106 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 17:10:34.838  1945  2106 D LEDHandler: Battery Level Remaining: 100%
08-23 17:10:34.838  1945  2106 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-23 17:10:34.839  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-23 17:10:34.839  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-23 17:10:34.842  1033  1545 D WifiController: battery changed pluggedType: 2
08-23 17:10:34.847  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 17:10:34.847  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 17:10:34.849  3812  3924 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 17:10:34.849  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 17:10:34.854  5096  5096 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 17:11:00.052  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:11:00.052  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:11:00.052  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:11:00.053  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:11:00.063  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:11:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:11:00.066  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:11:00.069  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:12:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:12:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:12:00.050  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:12:00.051  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:12:00.061  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:12:00.061  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:12:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:12:00.065  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 17:13:00.049  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:13:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:13:00.050  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:13:00.050  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:13:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:13:00.062  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:13:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:13:00.067  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:14:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:14:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:14:00.050  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:14:00.051  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:14:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:14:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:14:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:14:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:15:00.098  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:15:00.098  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:15:00.099  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:15:00.099  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:15:00.111  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:15:00.111  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:15:00.113  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:15:00.115  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 17:15:16.240  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 17:15:16.240  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 17:15:16.256  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 17:15:16.256  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 17:15:16.257  1033  1545 D WifiController: battery changed pluggedType: 2
08-23 17:15:16.261  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
08-23 17:15:16.261  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 17:15:16.263  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 17:15:16.264  1945  2106 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 17:15:16.264  1945  2106 D LEDHandler: Battery Level Remaining: 100%
08-23 17:15:16.264  1945  2106 D LEDHandler: Battery Temp: 282, mChargingStatus=5, mChargingStop=false
08-23 17:15:16.266  3812  3924 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 17:15:16.270  5096  5096 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 17:16:00.051  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:16:00.051  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:16:00.051  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:16:00.052  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:16:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:16:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:16:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:16:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:17:00.051  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:17:00.051  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:17:00.051  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:17:00.052  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:17:00.063  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:17:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:17:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:17:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:18:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:18:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:18:00.051  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:18:00.051  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:18:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:18:00.062  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:18:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:18:00.066  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 17:18:07.235  1033  1391 D PowerManagerServiceEx: acquireWakeLockInternal: lock=690155694, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-23 17:18:07.259  1033  1391 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f4c823b type 2 when 941550 com.android.bluetooth} when 941550
,08-23 17:18:07.265  3812  3997 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 17:18:07.265  3812  3997 W bt-smp  : Plain text(LSB ~ MSB) = e5 15 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 17:18:07.265  3812  3997 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 a2 ce c2 b0 9e 2d 68 c0 a0 f9 30 c7 ac 14 b2 
08-23 17:18:07.265  3812  3997 W bt-btm  : Stopping oneshot timer
08-23 17:18:07.299  2587  2587 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 17:18:07.324  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=690155694 [*alarm*], flags=0x0
,08-23 17:18:46.137  1033  1391 V AlarmManager: RTC_WAKEUP set : Alarm{7e39d58 type 0 when 1471965519735 com.google.android.gms} when 1471965519735
,08-23 17:18:46.173  1821  6325 I EventLogService: Aggregate from 1471963719650 (log), 1471963719650 (data)
,08-23 17:18:46.285  1821  6325 W EventLogAggregator: Unknown tag: snet_gcore
08-23 17:18:46.285  1821  6325 W EventLogAggregator: Unknown tag: snet_launch_service
,08-23 17:19:00.072  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:19:00.072  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:19:00.072  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:19:00.073  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:19:00.080  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:19:00.080  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:19:00.081  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:19:00.082  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 17:19:12.460  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 17:19:12.460  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 17:19:12.475  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 17:19:12.475  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 17:19:12.477  1033  1545 D WifiController: battery changed pluggedType: 2
08-23 17:19:12.481  1945  2106 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 17:19:12.481  1945  2106 D LEDHandler: Battery Level Remaining: 100%
08-23 17:19:12.481  1945  2106 D LEDHandler: Battery Temp: 281, mChargingStatus=5, mChargingStop=false
08-23 17:19:12.481  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
08-23 17:19:12.483  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 17:19:12.484  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 17:19:12.486  3812  3924 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:19:12.491  5096  5096 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-23 17:20:00.078  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:20:00.078  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:20:00.079  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:20:00.079  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:20:00.091  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:20:00.091  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:20:00.094  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:20:00.095  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:21:00.051  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:21:00.051  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:21:00.051  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:21:00.052  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:21:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:21:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:21:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:21:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:22:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:22:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:22:00.051  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:22:00.051  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:22:00.062  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:22:00.062  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:22:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:22:00.067  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:22:45.742  1033  1092 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 17:23:00.052  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:23:00.052  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:23:00.053  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:23:00.053  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:23:00.064  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:23:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:23:00.067  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:23:00.070  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:24:00.052  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:24:00.052  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:24:00.052  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:24:00.053  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:24:00.064  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:24:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:24:00.067  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:24:00.071  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:25:00.052  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:25:00.052  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:25:00.052  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:25:00.053  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:25:00.064  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:25:00.064  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:25:00.066  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:25:00.071  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:26:00.053  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:26:00.053  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:26:00.053  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:26:00.054  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:26:00.065  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:26:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:26:00.067  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:26:00.069  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 17:27:00.050  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:27:00.050  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:27:00.050  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:27:00.051  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:27:00.063  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:27:00.063  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:27:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:27:00.069  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:28:00.052  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 17:28:00.053  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 17:28:00.053  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 17:28:00.053  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-23 17:28:00.064  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 17:28:00.065  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-23 17:28:00.068  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
