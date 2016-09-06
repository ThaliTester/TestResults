#### Test 82894682e70646c_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-06 19:04:04.684   314  6868 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-06 19:04:20.853  6883  6883 D AndroidRuntime: 
09-06 19:04:20.853  6883  6883 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:04:20.860  6883  6883 D AndroidRuntime: CheckJNI is OFF
09-06 19:04:21.063  6883  6883 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 19:04:21.074  1032  1981 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:04:21.088  1929  1945 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-06 19:04:21.094  1032  1981 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-06 19:04:21.095  1032  1981 D ActivityManager: setTaskToReturnTo : TaskRecord{2e69fb05 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:04:21.095  1032  1981 D ActivityManager: setTaskToReturnTo : TaskRecord{2e69fb05 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:04:21.097  1032  1981 D WindowStateEx: AppWindowTokenEx init.. 
09-06 19:04:21.098   342   346 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:04:21.126  1032  1981 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6898 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:04:21.127  6883  6883 D AndroidRuntime: Shutting down VM
09-06 19:04:21.184  1929  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-06 19:04:21.184  1929  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{393ee945 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:04:21.186  1929  2940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-06 19:04:21.186  1929  2940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3b3a889a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:04:21.232  6898  6898 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-06 19:04:21.340  6898  6898 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 19:04:21.348  6898  6898 I LibraryLoader: Loading: webviewchromium
09-06 19:04:21.351  6898  6898 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6072-6076)
,09-06 19:04:21.352  6898  6898 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:04:21.376  6898  6898 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fa7b83b}
,09-06 19:04:21.377  6898  6898 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:04:21.377  6898  6898 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:04:21.387  6898  6898 I BrowserStartupController: Initializing chromium process, renderers=0
,09-06 19:04:21.388  6898  6898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:04:21.404  6898  6898 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-06 19:04:21.405  6898  6898 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-06 19:04:21.405  6898  6898 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-06 19:04:21.406   325   325 V AudioPolicyService: registerClient() client 0xb558ad00, uid 10118
09-06 19:04:21.414  1032  1103 D BluetoothManagerService: Message: 20
09-06 19:04:21.414  1032  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cef767:true
09-06 19:04:21.436  6898  6898 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:04:21.436  6898  6898 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:04:21.436  6898  6898 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:04:21.436  6898  6898 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:04:21.436  6898  6898 I Adreno-EGL: Remote Branch: 
09-06 19:04:21.436  6898  6898 I Adreno-EGL: Local Patches: 
09-06 19:04:21.436  6898  6898 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:04:21.526  6898  6943 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-06 19:04:21.532  6898  6898 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-06 19:04:21.560  6898  6898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:04:21.567  6898  6898 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:04:21.570  6898  6898 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-06 19:04:21.573  6898  6898 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-06 19:04:21.573  6898  6898 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-06 19:04:21.588  6898  6898 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-06 19:04:21.596  6898  6898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:04:21.596  6898  6898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:04:21.678  1032  1092 W ActivityManager: Activity pause timeout for ActivityRecord{3879975a u0 com.test.thalitest/.MainActivity t6}
,09-06 19:04:21.695  6898  6956 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:04:21.696  6898  6956 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:04:21.749  1032  1893 I art     : Explicit concurrent mark sweep GC freed 34494(1605KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.850ms total 121.056ms
,09-06 19:04:21.759  6898  6965 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:04:21.760  6898  6965 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:04:21.764  6898  6965 D OpenGLRenderer: Enabling debug mode 0
09-06 19:04:21.771  6898  6898 D Atlas   : Validating map...
,09-06 19:04:21.774  1032  1939 D SplitWindow: check instance of lgWin Window{223b4a29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:04:21.858  1032  1104 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +680ms (total +759ms)
,09-06 19:04:21.859  1032  1104 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3879975a u0 com.test.thalitest/.MainActivity t6} time:166584
09-06 19:04:21.859  6898  6898 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22f4b846 time:166584
09-06 19:04:21.933  6898  6898 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:04:21.964  6898  6898 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-06 19:04:21.964  6898  6898 I chromium: 
,09-06 19:04:22.101  6898  6972 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,09-06 19:04:22.120  6898  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:04:22.120  6898  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:04:22.120  6898  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:04:22.120  6898  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:04:22.120  6898  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 19:04:22.120  6898  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23032a2a added. We now have 1 listener(s)
,09-06 19:04:22.128  1032  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:22.131  6898  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-06 19:04:22.135  6898  6972 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-06 19:04:22.140  6898  6972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:22.141  6898  6972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:04:22.150  6898  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b9cf91 added. We now have 1 listener(s)
09-06 19:04:22.151  6898  6972 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:04:22.158  1032  1530 D WifiService: New client listening to asynchronous messages
09-06 19:04:22.166   342   348 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:04:22.166   342   348 E GBMv2   : Set value is all cleared set the max
09-06 19:04:22.166   342   348 I GBMv2   : DFP Enabled. Ignore VFP set
,09-06 19:04:22.167  6898  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:04:22.168  6898  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:04:22.168  6898  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:04:22.169  6898  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:04:22.169  6898  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 19:04:22.175  6898  6972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:22.180  1032  1856 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:04:22.185  6898  6972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-06 19:04:22.200  6898  6972 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:22.200  6898  6972 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:04:22.203  6898  6972 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:04:22.203  6898  6972 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:22.207  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:22.209  6898  6972 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:04:22.209  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:22.253  6898  6956 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-06 19:04:22.253  6898  6956 I chromium: 
,09-06 19:04:22.325  6898  6898 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:04:22.955  1804  2384 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-06 19:04:22.956  1804  1804 I ConfigFetchService: fetch service done; releasing wakelock
,09-06 19:04:22.958  1804  1804 I ConfigFetchService: stopping self
09-06 19:04:22.991  2172  2172 I ConfigService: onDestroy
,09-06 19:04:23.384  6898  6975 W jxcore-log: Initializing JXcore engine
,09-06 19:04:23.384  6898  6975 W jxcore-log: JXcore engine is ready
09-06 19:04:23.470  6975  6975 W Thread-772: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9896]" dev="sockfs" ino=9896 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 19:04:23.470  6975  6975 W Thread-772: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-06 19:04:23.470  6975  6975 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8571]" dev="sockfs" ino=8571 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 19:04:23.470  6975  6975 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-06 19:04:23.470  6975  6975 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32770]" dev="sockfs" ino=32770 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-06 19:04:23.502  6898  6975 W jxcore-log: Starting JXcore engine
,09-06 19:04:23.661  6898  6975 W jxcore-log: Platform android
09-06 19:04:23.661  6898  6975 W jxcore-log: 
,09-06 19:04:23.662  6898  6975 W jxcore-log: Process ARCH arm
09-06 19:04:23.662  6898  6975 W jxcore-log: 
,09-06 19:04:23.997  6898  6975 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:04:23.997  6898  6975 I jxcore-log: 
09-06 19:04:23.997  6898  6975 W jxcore-log: JXcore engine is started
,09-06 19:04:24.005  6898  6972 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:04:24.007  6898  6898 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:04:33.386  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:04:33.386  6898  6975 I jxcore-log: 
,09-06 19:04:33.389  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:04:33.389  6898  6975 I jxcore-log: 
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:33.394  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:33.397  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:33.401  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:04:33.401  6898  6975 I jxcore-log: 
,09-06 19:04:33.403  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:04:33.403  6898  6975 I jxcore-log: 
,09-06 19:04:33.898  6898  6975 D executeNativeTests: Running unit tests
,09-06 19:04:33.983  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:33.983  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a added. We now have 2 listener(s)
09-06 19:04:33.984  1032  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:04:33.987  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:33.987  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:33.987  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:33.987  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:33.987  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b added. We now have 2 listener(s)
09-06 19:04:33.987  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:33.987  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:04:33.990  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:33.993  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:04:33.994  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:33.995  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:33.997  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:33.999  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:04:34.001  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:04:34.001  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:04:34.003  6898  6975 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 19:04:34.004  6898  6975 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:04:34.004  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:04:34.004  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:04:34.004  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:04:34.005  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.006  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.006  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.006  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:04:34.006  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.006  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:34.006  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:34.006  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a removed from the list
09-06 19:04:34.006  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.006  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b removed from the list,
09-06 19:04:34.012  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:34.014  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop,
09-06 19:04:34.014  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.014  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.014  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.016  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:04:34.016  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.016  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.016  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.017  6898  6975 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:04:34.018  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:04:34.018  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.018  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.018  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.018  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.018  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:04:34.018  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.018  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.018  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.018  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:04:34.018  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.018  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.018  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.018  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.019  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:04:34.019  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.019  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.019  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:04:34.023  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:04:34.024  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
09-06 19:04:34.024  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:04:34.024  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:04:34.024  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.024  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:04:34.024  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.024  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.024  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.024  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.024  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
,09-06 19:04:34.024  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.024  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.024  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.024  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.024  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:04:34.024  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:04:34.024  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:04:34.026  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:04:34.026  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.026  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.026  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.027  6898  6975 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:04:34.028  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
09-06 19:04:34.030  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:34.031  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.031  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:34.032  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.033  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:34.033  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:34.033  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:04:34.033  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:04:34.033  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.033  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:04:34.036  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:04:34.036  1032  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:04:34.040  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-06 19:04:34.043  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:04:34.045  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:04:34.046  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:04:34.046  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:04:34.047  6898  6975 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:04:34.047  6898  6975 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:04:34.049  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.049  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,09-06 19:04:34.049  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:04:34.050  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.050  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.050  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:34.050  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.050  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.050  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.050  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.050  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.050  6898  6975 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:04:34.052  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:34.053  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:34.054  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.054  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:34.055  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:34.055  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:04:34.055  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:04:34.055  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.055  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:04:34.056  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.057  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.058  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:04:34.059  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:34.060  6898  6975 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:04:34.060  6898  6,975 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:04:34.061  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.061  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.061  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.061  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.061  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.062  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:34.062  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.062  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.062  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.062  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.062  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.062  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.062  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.063  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.063  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.064  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.064  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.064  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.064  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.064  6898  6975 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:04:34.066  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:34.068  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:34.068  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.069  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:34.070  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.070  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:34.070  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:04:34.070  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:04:34.070  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.070  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:04:34.072  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.074  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:04:34.074  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:34.076  6898  6975 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:04:34.076  6898  6975 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:04:34.076  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.076  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.076  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.076  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.076  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.076  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.077  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.077  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.077  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:34.077  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.077  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.077  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.077  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.077  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.077  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.077  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.077  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.077  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.078  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.078  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.078  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.078  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.078  6898  6975 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:04:34.078  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.079  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.079  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.079  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.079  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.079  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.079  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.079  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.079  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.079  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.079  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.079  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.079  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.079  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.080  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.080  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.080  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.080  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.080  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.080  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.081  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:04:34.081  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.081  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.081  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.081  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.081  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.081  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.081  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.081  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.082  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.082  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.082  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.082  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.082  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.082  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.082  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.082  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.082  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.082  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.082  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.082  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.083  6898  6975 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:04:34.083  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.083  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.083  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:04:34.085  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.085  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.085  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.085  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.085  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.085  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.085  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.085  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.086  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.086  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.086  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.088  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.088  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.088  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.088  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.088  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.088  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.089  6898  6975 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:04:34.089  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.089  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.089  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.089  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.089  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.089  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.089  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.089  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.089  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.089  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.089  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.089  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.089  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.089  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.090  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.090  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.091  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.091  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.091  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.091  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.091  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:04:34.091  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:04:34.091  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:04:34.091  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:04:34.091  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:04:34.091  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:04:34.091  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.091  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.091  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.092  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.092  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.092  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.092  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.092  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.092  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.092  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.092  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.092  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.092  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.092  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.093  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.093  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.094  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.094  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.094  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.094  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.094  6898  6975 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:04:34.094  6898  6975 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:04:34.094  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:04:34.096  6898  6975 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:04:34.096  6898  6975 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:04:34.096  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:04:34.097  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:04:34.097  6898  6975 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:04:34.097  6898  6975 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:04:34.097  6898  6975 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:04:34.097  6898  6975 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:04:34.097  6898  6975 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:04:34.097  6898  6975 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:04:34.097  6898  6975 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:04:34.097  6898  6975 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:04:34.097  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:04:34.099  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:04:34.100  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:04:34.100  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:04:34.100  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:04:34.101  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:04:34.101  6898  6975 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:04:34.101  6898  6975 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:04:34.101  6898  6975 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:04:34.101  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.101  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.101  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.101  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.101  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.101  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.102  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:04:34.102  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.102  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.102  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.102  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.102  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.102  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.102  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.102  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.103  6898  6976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
09-06 19:04:34.106  6898  6977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
09-06 19:04:34.106  6898  6977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
09-06 19:04:34.106  6898  6977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
09-06 19:04:34.114  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.114  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.120  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.120  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.120  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.120  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.121  6898  6975 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:04:34.121  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.121  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.121  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.122  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.122  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.122  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.122  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.122  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.122  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.122  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.122  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.122  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.122  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.122  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.123  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.123  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.123  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.123  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.123  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.123  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.124  6898  6975 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:04:34.124  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.124  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.124  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.129  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.129  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.129  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:04:34.131  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.131  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.131  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.131  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.131  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.131  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.131  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.131  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.132  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.132  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.132  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.132  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.132  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.132  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.133  6898  6975 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:04:34.133  6898  6975 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:04:34.133  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:04:34.134  6898  6975 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:04:34.134  6898  6975 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:04:34.134  6898  6975 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:04:34.134  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:04:34.134  6898  6975 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:04:34.134  6898  6975 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:04:34.134  6898  6975 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:04:34.134  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:04:34.134  6898  6975 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:04:34.134  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.134  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.134  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.135  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.135  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.135  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.135  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.135  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.135  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.135  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.135  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.135  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.135  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.135  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.137  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.137  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.137  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.137  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.137  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.137  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.138  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.138  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.138  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.138  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.138  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.138  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.138  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.138  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.138  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.138  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.138  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.138  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.138  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.138  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.138  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.138  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.138  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.138  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.139  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.139  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.139  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.139  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.139  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.139  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.139  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.139  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.139  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.139  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.139  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.140  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.140  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.141  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.141  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.141  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.141  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.142  6898  6975 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:04:34.142  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.155  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:04:34.156  6898  6975 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:04:34.156  6898  6975 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:04:34.156  6898  6898 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:04:34.156  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:04:34.156  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:04:34.157  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.157  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:04:34.157  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:04:34.157  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:04:34.157  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.157  6898  6975 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:04:34.158  6898  6978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:04:34.158  6898  6978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:04:34.158  6898  6898 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:04:34.159  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.159  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.159  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:04:34.159  6898  6975 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:04:34.159  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:04:34.159  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:04:34.160  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:34.160  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:34.160  6898  6975 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:04:34.160  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.160  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.161  6898  6975 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:04:34.161  6898  6898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:04:34.161  6898  6898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:04:34.161  6898  6898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:04:34.161  6898  6898 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:04:34.162  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.162  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.162  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.162  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.162  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.162  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.162  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.162  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.162  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.162  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.162  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.162  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.162  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.162  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.162  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.163  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.163  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.163  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.163  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.163  6898  6975 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:04:34.164  6898  6975 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:04:34.164  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:04:34.165  6898  6975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:04:34.165  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.165  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.165  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.165  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.165  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.165  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.165  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.165  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.165  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.165  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.165  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.165  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.165  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.166  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.166  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.166  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.166  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.166  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
,09-06 19:04:34.167  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:34.168  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:34.169  1032  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:34.169  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.169  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.169  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.169  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.169  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.169  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.169  6898  6975 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.169  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.170  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.170  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.170  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.170  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.170  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.170  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.170  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.170  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.170  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.170  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.171  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:34.171  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:34.171  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:34.171  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:34.171  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.171  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.171  6898  6975 E org.thaliproject.p2p.btconnectorlib.C,onnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d8227a not in the list
09-06 19:04:34.171  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.171  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.171  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:34.171  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:34.171  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.171  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:04:34.171  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:34.172  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:34.172  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:34.172  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:34.172  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be40a2b not in the list
09-06 19:04:34.173  6898  6975 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:04:34.173  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:04:34.173  6898  6975 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:04:34.173  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:04:34.173  6898  6975 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:04:34.173  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:04:34.175  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:04:34.175  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:04:34.175  6898  6975 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:04:34.176  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:04:34.176  6898  6975 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:04:34.176  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:04:34.176  6898  6975 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:04:34.176  6898  6975 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:04:34.176  6898  6975 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:04:34.176  6898  6975 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:04:34.177  6898  6975 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:04:34.177  6898  6975 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:04:34.177  6898  6975 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:04:34.177  6898  6975 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:04:34.177  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:34.177  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3985b6a0 added. We now have 2 listener(s)
09-06 19:04:34.178  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:34.179  6898  6975 D BluetoothAdapter: enable(): BT is already enabled..,!
,09-06 19:04:34.181  1032  1883 D WifiServiceImplEx: setWifiEnabled: true pid=6898, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:04:34.181  1032  1883 D WifiService: setWifiEnabled: true pid=6898, uid=10118
09-06 19:04:34.181  1032  1883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:04:34.187  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:34.187  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b53b259 added. We now have 3 listener(s)
09-06 19:04:34.187  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:34.191  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:34.191  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cd03e1e added. We now have 4 listener(s)
09-06 19:04:34.191  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:34.193  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:34.193  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30cbc6ff added. We now have 5 listener(s)
09-06 19:04:34.193  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:34.197  1032  1564 D WifiServiceImplEx: setWifiEnabled: false pid=6898, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:04:34.197  1032  1564 D WifiService: setWifiEnabled: false pid=6898, uid=10118
09-06 19:04:34.197  1032  1564 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:04:34.206  6898  6976 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-06 19:04:34.207  6898  6976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
09-06 19:04:34.209  1032  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:34.209  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:34.209  1032  1856 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:34.209  1032  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:34.209  1032  1856 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18ba210 mBinding = false
09-06 19:04:34.209  1032  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:34.209  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:34.210  1032  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:04:34.210  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:34.210  1032  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:04:34.210  1032  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:04:34.210  1032  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:04:34.210  1032  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:04:34.211  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:34.211  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-06 19:04:34.216  1032  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:04:34.216  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:04:34.216  2709  2709 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:04:34.216  1032  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.216  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.216  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:04:34.216  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:04:34.217  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:04:34.217   314   876 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:04:34.218  1032  1103 D BluetoothManagerService: Message: 2
09-06 19:04:34.219  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:34.219  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:34.220  1032  1103 D BluetoothManagerService: Sending off request.
09-06 19:04:34.220  3871  3889 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:04:34.221  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:34.223  3871  3947 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:04:34.223  3871  3947 D BluetoothAdapterProperties: Setting state to 13
09-06 19:04:34.223  3871  3947 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:04:34.224  3871  3947 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:04:34.224  3871  3947 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:04:34.225  1032  2856 D DhcpStateMachine: RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.227  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:34.227  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:04:34.227  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:04:34.230  3871  3952 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:04:34.230  3871  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:04:34.230  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:34.230  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:34.231  3871  4171 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:34.231  3871  3947 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:04:34.231  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:04:34.232  3871  4046 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:04:34.233  3871  4194 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:34.233  3871  4195 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:34.234  3871  4197 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:04:34.234  3871  4163 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 19:04:34.236  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:34.236  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:34.236  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister(,) called for PSM: 0x001b
09-06 19:04:34.236  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:34.236  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:34.237  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:34.237  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:34.237  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:34.237  3871  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:34.237  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:04:34.237  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:04:34.237  3871  4046 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:04:34.238  3871  3871 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:34.239  3871  3871 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:04:34.239  3871  3871 V BluetoothMapService: Handler(): got msg=4
09-06 19:04:34.239  3871  3871 D BluetoothMapService: MAP Service closeService in
,09-06 19:04:34.239  3871  3871 D BluetoothMapMasInstance: MAP Service shutdown
09-06 19:04:34.240  3871  3871 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:04:34.240  3871  3871 V BluetoothMapService: MAP Service closeService out
09-06 19:04:34.241  3871  3871 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:04:34.241  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:34.241  3871  3871 I BtOppRfcommListener: stopping Accept Thread
09-06 19:04:34.242  3871  3871 V BtOppRfcommListener: close mBtServerSocket
09-06 19:04:34.243  3871  3871 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:04:34.243  3871  4194 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:04:34.243  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:34.245  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:04:34.245  3871  3871 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:04:34.248  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.248  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:34.248  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:34.254  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:04:34.254  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-06 19:04:34.256  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:34.259  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:34.259  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:34.259  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.259  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:34.261  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:34.262  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:34.262  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.262  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:34.264  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.267  1032  2015 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-06 19:04:34.267  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.268  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.268  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:04:34.268  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.268  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,09-06 19:04:34.285  1032  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6996 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:04:34.287  3871  3871 V BtOppService: onDestroy
09-06 19:04:34.289  1032  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.289  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.289  1032  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@353c4b51
09-06 19:04:34.290  3871  3871 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 19:04:34.291  1032  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.291  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.291  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.292  1032  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.292  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.293  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.293  1032  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:04:34.294  1032  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.294  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.295  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:34.296  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:04:34.296  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.296  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.296  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:04:34.296  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:04:34.296  1032  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:04:34.296  1032  1531 D DSQN    : disableDataServiceNotify
09-06 19:04:34.296  1032  1531 D DSQN    : stop dsqn bin
09-06 19:04:34.296  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.297  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.297  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:04:34.297  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:04:34.297  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-06 19:04:34.297  1032  1545 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.297   314  7013 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:04:34.298  1032  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:04:34.298  1032  1546 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.298  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-06 19:04:34.298  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-06 19:04:34.301  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.303  1032  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 19:04:34.303  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:34.303  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:34.303  1032  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:34.304  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.304  1032  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:04:34.304  1591  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:04:34.305  1032  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:04:34.305  1032  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:04:34.305  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:04:34.305  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.305  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.305  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:04:34.309  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:34.309  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:34.310  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:34.314  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:34.314  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:34.315  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:34.327  1032  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7016 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-06 19:04:34.328  1032  1522 D LGWifiP2pService: P2pDisablingState
09-06 19:04:34.328  1032  1522 D LGWifiP2pService: P2pDisablingState{ when=-39ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.328  1032  1522 D LGWifiP2pService: p2p socket connection lost
,09-06 19:04:34.328  1032  1522 D LGWifiP2pService: P2pDisabledState
09-06 19:04:34.329  1032  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:04:34.329  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:04:34.329  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:04:34.329  1929  1929 D WfdsService: WifiP2pState is changed : false
09-06 19:04:34.329  2709  2709 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:04:34.329  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:04:34.329  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:04:34.330  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
,09-06 19:04:34.330   314   876 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:04:34.330  1032  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.330  1032  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.332  1929  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:04:34.332  1929  2284 D WfdsService: Set the WFDS Monitor: false
09-06 19:04:34.332  1032  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:34.332  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:04:34.332  1032  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:34.332  1032  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:34.332  1032  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:34.332  1929  2284 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:04:34.332  1929  2284 D WfdsService: STATE : WfdsDisabledState - enter
09-06 19:04:34.333  1032  1531 D NetworkManagementService: Removing idletimer
09-06 19:04:34.333  1929  2765 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:04:34.333  1929  2765 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:04:34.333  1929  2765 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:04:34.333  1929  2765 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:04:34.333  1032  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.333  1929  2289 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:04:34.333  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:34.333  1929  2284 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 19:04:34.333  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:04:34.335  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:04:34.335  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:04:34.335  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:04:34.335  1032  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:04:34.335  1032  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:04:34.336  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:04:34.336  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:04:34.336  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:04:34.336  1032  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 19:04:34.336  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:04:34.336  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:04:34.336  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:04:34.338  1032  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 19:04:34.339  1032  1523 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:04:34.339  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:34.339  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:34.339  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:04:34.341  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.341  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.341  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-06 19:04:34.342  1032  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:34.342  1032  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:34.343  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 19:04:34.347  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:04:34.347  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:34.347  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 19:04:34.348  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:34.348  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:34.348  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.348  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:04:34.350  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:34.350  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:34.350  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:34.350  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:34.360  6996  6996 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:04:34.360  6996  6996 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-06 19:04:34.361  6996  6996 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:04:34.361  6996  6996 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-06 19:04:34.362  6996  6996 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:04:34.363  6996  6996 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:04:34.363  1591  1591 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-06 19:04:34.364  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:34.364  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:34.397  1591  1591 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:04:34.398  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:34.399  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:34.399  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:04:34.399  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:34.400  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:34.422  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:34.429  1032  2856 D DhcpStateMachine: StoppedState
09-06 19:04:34.429  1032  2856 D DhcpStateMachine: StoppedState{ when=-100ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:34.430  1032  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:04:34.430  1032  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 19:04:34.432  7016  7016 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:04:34.432  7016  7016 W LG Account v2.2: No ProfileInfo entries
09-06 19:04:34.432  7016  7016 I LG Account v2.2: isEnabled: false
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Country: EU
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Operator: OPEN
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Ranking support: false
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Comfort support: false
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Accessory: true
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Health device: true
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:04:34.432  7016  7016 I Feature : [Lifetracker]Device Number: 3
09-06 19:04:34.439  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:34.472  1032  1893 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7036 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:04:34.474  1032  1893 I ActivityManager: Killing 6322:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-06 19:04:34.477  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:04:34.488  2709  2709 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:04:34.489  2709  2709 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:04:34.489  2709  2709 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-2\x00 that cannot receive messages
09-06 19:04:34.491  1032  2760 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:04:34.492  1032  2760 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:04:34.531  1032  1856 W libprocessgroup: failed to open /acct/uid_10014/pid_6322/cgroup.procs: No such file or directory
,09-06 19:04:34.542  3871  3871 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:04:34.542  3871  3871 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:34.542  3871  3871 V BluetoothPbapReceiver: ***********state = 13
09-06 19:04:34.543  2709  2709 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:04:34.544  1032  2760 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 19:04:34.544  1032  2760 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:04:34.544  1032  2760 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:04:34.544  1032  2760 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:04:34.545  1032  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179258
09-06 19:04:34.545  1032  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179258
09-06 19:04:34.546  1032  1103 D Tethering: InitialState.processMessage what=4
,09-06 19:04:34.547  3871  3871 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-06 19:04:34.550  2709  2709 W wpa_supplicant: USIM:  scard_deinit function
09-06 19:04:34.550  3871  3871 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:34.550  3871  3871 V BluetoothPbapService: state: 13
09-06 19:04:34.551  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:04:34.551  3871  3871 V BluetoothPbapService: Pbap Service closeService in
09-06 19:04:34.551  1032  2760 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:34.552  1032  2760 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:34.554  1032  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179267  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:04:34.554  1032  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179267  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:04:34.556  1032  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:04:34.556  1032  1103 D BluetoothManagerService: Message: 20
09-06 19:04:34.556  1032  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@942bd4b:true
09-06 19:04:34.557  3871  3871 V BluetoothPbapService: successfully stopped pbap service
09-06 19:04:34.557  3871  3871 V BluetoothPbapService: Pbap Service closeService out
09-06 19:04:34.558  3871  3871 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:04:34.558  3871  3871 V BluetoothPbapService: Pbap Service closeService in
09-06 19:04:34.558  3871  3871 V BluetoothPbapService: Pbap Service closeService out
09-06 19:04:34.558  3871  3871 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-06 19:04:34.563  1032  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:34.564  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:34.577  1032  1103 D BluetoothManagerService: Message: 30
,09-06 19:04:34.581  1032  1103 D BluetoothManagerService: Message: 30
09-06 19:04:34.584  6996  6996 D LocalBluetoothProfileManager: Adding local MAP profile
09-06 19:04:34.586  6996  6996 D BluetoothMap: Create BluetoothMap proxy object
09-06 19:04:34.586  1032  1103 D BluetoothManagerService: Message: 30
09-06 19:04:34.590  1032  1103 D BluetoothManagerService: Message: 30
,09-06 19:04:34.592  6996  6996 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-06 19:04:34.593  6996  6996 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-06 19:04:34.600  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:04:34.603  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:34.604  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:04:34.607  1032  1981 I ActivityManager: Killing 6429:com.android.defcontainer/u0a4 (adj 15): empty #17
09-06 19:04:34.638  6996  6996 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-06 19:04:34.638  1032  1939 W libprocessgroup: failed to open /acct/uid_10004/pid_6429/cgroup.procs: No such file or directory
,09-06 19:04:34.641  2709  2709 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:04:34.642  1032  2760 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:04:34.642  1032  2760 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 19:04:34.642  1032  2760 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 19:04:34.643  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-06 19:04:34.643  1032  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-06 19:04:34.658  6996  6996 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:04:34.662  6898  6898 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:04:34.673  6996  6996 D BluetoothInputDevice: Proxy object connected
,09-06 19:04:34.674  6996  6996 D HidProfile: Bluetooth service connected
,09-06 19:04:34.676  6996  6996 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:04:34.677  6996  6996 D PanProfile: Bluetooth service connected
09-06 19:04:34.678  6996  6996 D BluetoothMap: Proxy object connected
09-06 19:04:34.679  6996  6996 D MapProfile: Bluetooth service connected
09-06 19:04:34.679  6996  6996 D BluetoothMap: getConnectedDevices()
09-06 19:04:34.680  6996  6996 D BluetoothMap: Bluetooth is Not enabled
09-06 19:04:34.698  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:34.742  6996  6996 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:34.742  6996  6996 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:34.745  1032  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 19:04:34.745  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:34.745  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:34.745  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:04:34.749  1929  1929 D WfdsService: Supplicant Connection state is changed : false
09-06 19:04:34.749  1929  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:04:34.749  1929  2284 D WfdsService: Set the WFDS Monitor: false
09-06 19:04:34.749  1929  2284 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:04:34.751  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:04:34.751  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:34.756  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,09-06 19:04:34.756  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:34.756  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:04:34.757  1032  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:04:34.758  1032  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 19:04:34.759  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:04:34.761  2494  2494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:34.761  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.764  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:34.765  6996  6996 D BluetoothPermissionRequest: onReceive
09-06 19:04:34.767  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:04:34.777  1032  1564 I ActivityManager: Killing 6628:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-06 19:04:34.779  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:34.807  3871  3871 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-06 19:04:34.807  3871  3871 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-06 19:04:34.807  1032  1688 W libprocessgroup: failed to open /acct/uid_10008/pid_6628/cgroup.procs: No such file or directory
09-06 19:04:34.808  3871  3871 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 19:04:34.877  1032  1856 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7066 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-06 19:04:34.877  3871  3871 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:34.878  3871  3871 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:04:34.879  3871  3871 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:04:34.879  3871  3871 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:34.880  3871  3871 V BluetoothFtpService: Ftp Service closeService
09-06 19:04:34.880  3871  3871 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,09-06 19:04:34.887  3871  3871 V BluetoothFtpService: successfully stopped ftp service
09-06 19:04:34.888  3871  3871 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:04:34.888  3871  3871 V BluetoothFtpService: Ftp Service closeService
09-06 19:04:34.892  3871  3871 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:34.892  3871  3871 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:34.892  3871  3871 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:34.892  3871  3871 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:04:34.892  3871  3871 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:04:34.892  3871  3871 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:04:34.894  3871  3871 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:34.894  3871  3871 V BluetoothSapService: state: 13
09-06 19:04:34.894  3871  3871 V BluetoothSapService: Stopping SAP server process
,09-06 19:04:34.898  3871  3871 V BluetoothSapService: Sap Service closeSapService in
09-06 19:04:34.898  3871  3871 V BluetoothSapService: Close listen Socket : 
09-06 19:04:34.898  3871  3871 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:04:34.898  3871  3871 V BluetoothSapService: Close sapd  Socket : 
09-06 19:04:34.899  3871  3871 V BluetoothSapService: Sap Service closeSapService out
09-06 19:04:34.900  3871  3871 V BluetoothSapService: Sap Service onDestroy
09-06 19:04:34.900  3871  3871 V BluetoothSapService: Sap Service closeSapService in
09-06 19:04:34.900  3871  3871 V BluetoothSapService: Close listen Socket : 
09-06 19:04:34.900  3871  3871 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:04:34.900  3871  3871 V BluetoothSapService: Close sapd  Socket : 
09-06 19:04:34.919   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 37.747ms
,09-06 19:04:34.940   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 20.996ms
,09-06 19:04:34.958   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 370us total 17.776ms
,09-06 19:04:35.007  1032  1856 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7083 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:04:35.008  3871  3871 V BluetoothSapService: Sap Service closeSapService out
,09-06 19:04:35.049  7066  7066 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:04:35.066  7083  7083 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:04:35.078  7066  7066 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-06 19:04:35.082  1032  1564 I ActivityManager: Killing 6075:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-06 19:04:35.173  1032  1981 W libprocessgroup: failed to open /acct/uid_10011/pid_6075/cgroup.procs: No such file or directory
,09-06 19:04:35.233  7066  7066 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-06 19:04:35.233  7066  7066 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 19:04:35.234  7066  7066 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:04:35.234  7066  7066 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:04:35.235  7066  7066 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:04:35.238  7066  7066 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-06 19:04:35.241  3871  3952 D bt_hci_bdroid: cleanup
09-06 19:04:35.241  3871  4048 I bt_lpm  : LPM is already off!!!
09-06 19:04:35.241  3871  4127 I bt_userial_mct: exiting userial_read_thread
09-06 19:04:35.241  3871  4046 W bt-btif : ag scb idx 1 not allocated
,09-06 19:04:35.241  3871  4046 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:35.242  3871  4046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:35.243  3871  4046 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:04:35.243  3871  4127 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:04:35.243  3871  3952 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:04:35.243  3871  4048 I bt_vendor: hw_epilog_process
09-06 19:04:35.244  3871  3952 D bt_hci_bdroid: cleanup Finalizing cleanup
,09-06 19:04:35.244  3871  3952 D bt_userial_mct: userial_close
09-06 19:04:35.244  3871  3952 E bt_userial_mct: pthread_join() FAILED result:3,
09-06 19:04:35.244  3871  3952 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
09-06 19:04:35.245  7066  7066 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-06 19:04:35.253  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:04:35.259  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:35.281  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:04:35.284  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:35.286  7066  7066 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 19:04:35.289  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:04:35.290  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:35.290  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:35.290  7066  7066 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 19:04:35.299  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:35.310  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:35.315  3871  3952 D bt_hci_bdroid: set_power 0
,09-06 19:04:35.315  3871  3952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:04:35.315  3871  3952 I bt_vendor: bluetooth satus is on
09-06 19:04:35.315  3871  3952 I bt_vendor: bt-vendor : resetting BT status
09-06 19:04:35.315  3871  3952 I bt_vendor: Starting hciattach daemon
09-06 19:04:35.315  3871  3952 I bt_vendor: try to set false
09-06 19:04:35.317  3871  3952 I bt_vendor: Starting hciattach daemon
09-06 19:04:35.317  3871  3952 I bt_vendor: try to set false
09-06 19:04:35.318  3871  3952 I bt_vendor: cleanup
09-06 19:04:35.319  3871  4046 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:04:35.320  3871  3952 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:04:35.320  3871  3952 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:04:35.322  3871  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:04:35.323  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:35.324  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:35.329  3871  3871 D HeadsetService: Received stop request...Stopping profile...
09-06 19:04:35.329  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:04:35.334  3871  3871 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:04:35.334  3871  3871 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:04:35.334  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d2d9b58
09-06 19:04:35.334  3871  3977 D HeadsetStateMachine: Exit Disconnected: -1
09-06 19:04:35.338  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:35.342  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:35.342  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:04:35.343  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:35.343  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:35.344  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:35.347  3871  3871 D A2dpService: Received stop request...Stopping profile...
09-06 19:04:35.347  3871  4013 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:04:35.348  3871  3871 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 19:04:35.350  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:04:35.350  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:35.350  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:35.352  3871  3947 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:04:35.353  3871  3871 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:04:35.353  3871  3871 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:04:35.353  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d2d9b58
,09-06 19:04:35.357  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-06 19:04:35.357  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:04:35.358  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:04:35.359  3871  3871 D HidService: Received stop request...Stopping profile...
09-06 19:04:35.359  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d2d9b58
09-06 19:04:35.360  3871  3871 D HealthService: Received stop request...Stopping profile...
09-06 19:04:35.360  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d2d9b58
09-06 19:04:35.362  3871  3871 D PanService: Received stop request...Stopping profile...
09-06 19:04:35.363  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d2d9b58
09-06 19:04:35.364  3871  3871 D HeadsetStateMachine: Unbinding service...
09-06 19:04:35.365  3871  3871 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:04:35.365  3871  3871 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:04:35.365  3871  3871 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:04:35.365  3871  3871 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:04:35.365  3871  3871 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:04:35.365  3871  3871 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:04:35.365  3871  3871 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:04:35.365  3871  3871 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:04:35.366  3871  3871 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:04:35.366  3871  3871 D BtGatt.GattService: stop()
09-06 19:04:35.366  3871  3871 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:04:35.370  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d2d9b58
09-06 19:04:35.371  3871  3871 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:04:35.371  3871  3871 D BluetoothMapService: stop()
09-06 19:04:35.371  3871  3871 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:04:35.372  3871  3871 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 19:04:35.372  3871  3871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d2d9b58
09-06 19:04:35.372  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:35.373  3871  3871 I BluetoothA2dpServiceJni: cleanupNative
09-06 19:04:35.373  3871  4014 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:04:35.374  3871  3871 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:04:35.374  3871  3871 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:04:35.374  3871  3871 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:04:35.374  3871  3871 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:04:35.374  3871  3871 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:04:35.375  3871  3871 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:04:35.375  3871  3871 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:04:35.375  3871  3871 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:04:35.375  3871  3871 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:04:35.376  3871  3871 V BluetoothMapService: Handler(): got msg=4
09-06 19:04:35.376  3871  3871 D BluetoothMapService: MAP Service closeService in
09-06 19:04:35.376  3871  3871 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:04:35.376  3871  3871 V BluetoothMapService: MAP Service closeService out
09-06 19:04:35.376  6996  6996 D BluetoothInputDevice: Proxy object disconnected
09-06 19:04:35.376  6996  6996 D HidProfile: Bluetooth service disconnected
09-06 19:04:35.376  3871  3871 D BluetoothMapService: cleanup()
09-06 19:04:35.376  3871  3871 D BluetoothMapService: MAP Service closeService in
09-06 19:04:35.376  3871  3871 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:04:35.376  3871  3871 V BluetoothMapService: MAP Service closeService out
09-06 19:04:35.376  3871  3947 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:04:35.376  6996  6996 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:04:35.376  6996  6996 D PanProfile: Bluetooth service disconnected
09-06 19:04:35.376  3871  3947 D BluetoothAdapterProperties: Setting state to 10
09-06 19:04:35.376  3871  3947 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:04:35.377  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:35.377  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:04:35.377  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-06 19:04:35.377  3871  3947 I BluetoothAdapterState: Entering OffState
09-06 19:04:35.377  6996  6996 D BluetoothMap: Proxy object disconnected
09-06 19:04:35.377  6996  6996 D MapProfile: Bluetooth service disconnected
09-06 19:04:35.378  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:35.379  1032  1103 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:04:35.379  6996  7015 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:04:35.383  1032  1103 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:04:35.383  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:35.384  6996  7014 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:04:35.384  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:35.384  6996  7107 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:04:35.386  1839  2443 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:35.386  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:04:35.386  6996  7015 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:04:35.426  1032  1981 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7112 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-06 19:04:35.429  1839  2408 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:35.431  1032  1103 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:04:35.431  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-06 19:04:35.436  1032  1103 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:04:35.436  1032  1103 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:04:35.436  1032  1103 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@18ba210 mBinding = false
09-06 19:04:35.438  1032  1103 D BluetoothManagerService: Sending unbind request.
09-06 19:04:35.441  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 19:04:35.444  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:04:35.446  1929  2090 D LGBluetoothAPIService: Message: 2
09-06 19:04:35.446  1929  2090 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@ea745cb mBinding = false
09-06 19:04:35.446  1929  2090 D LGBluetoothAPIService: Sending unbind request.
09-06 19:04:35.446  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:35.449  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:35.450  3871  3952 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:04:35.450  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:35.451  3871  3871 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:04:35.451  3871  3871 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:04:35.452  3871  3871 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:04:35.452  3871  3871 I art     : --- WEIRD: removing null entry 246
09-06 19:04:35.452  3871  3871 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-06 19:04:35.452  3871  3871 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 19:04:35.453  3871  3871 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:04:35.454  6996  6996 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:04:35.454  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,09-06 19:04:35.455  6996  6996 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 19:04:35.456  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:04:35.457  1591  1591 D BluetoothAdapter: 222413363: getState() :  mService = null. Returning STATE_OFF
09-06 19:04:35.457  1591  1591 D BluetoothAdapter: 222413363: getState() :  mService = null. Returning STATE_OFF
09-06 19:04:35.458  3871  3871 I art     : System.exit called, status: 0
09-06 19:04:35.458  3871  3871 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:04:35.465  6996  6996 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:04:35.479   325  1366 V AudioFlinger: 3871 died, releasing its sessions
09-06 19:04:35.479   325  1366 V AudioFlinger:  pid 1839 @ 0
09-06 19:04:35.479   325  1366 V AudioFlinger:  pid 3488 @ 1
09-06 19:04:35.479   325  1366 V AudioFlinger:  pid 3488 @ 2
09-06 19:04:35.479  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 19:04:35.505  1032  1981 I ActivityManager: Process com.android.bluetooth (pid 3871) has died
,09-06 19:04:35.506  1032  1981 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-06 19:04:35.518  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:04:35.537  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:04:35.549  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:04:35.554  7112  7135 W FormManager: Network not available. Please check & try again.
09-06 19:04:35.561  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:35.564  6996  6996 D BluetoothPermissionRequest: onReceive
09-06 19:04:35.566  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:04:35.566  6996  6996 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-06 19:04:35.572  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:35.572  7112  7136 V FormManager: Network unavailable.
09-06 19:04:35.632  1032  1048 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7138 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 19:04:35.652  7112  7136 V FormManager: Network unavailable.
,09-06 19:04:35.676  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:04:35.676  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:04:35.677  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:04:35.677  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:04:35.678  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 19:04:35.697  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:04:35.697  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:04:35.697  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:04:35.697  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:04:35.697  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:04:35.698  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-06 19:04:35.700  1032  1928 I ActivityManager: Killing 6096:com.android.contacts/u0a19 (adj 15): empty #17
,09-06 19:04:35.705  7138  7138 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:04:35.705  7138  7138 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:04:35.706  7138  7138 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 19:04:35.706  7138  7138 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:04:35.724  7138  7138 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:04:35.759  7138  7138 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2952ff79 Instance Count = 1
,09-06 19:04:35.780  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:04:35.781  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:04:35.781  1032  2039 W libprocessgroup: failed to open /acct/uid_10019/pid_6096/cgroup.procs: No such file or directory
,09-06 19:04:35.787  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:35.788  7138  7138 D BluetoothAdapterApp: onCreate
09-06 19:04:35.791  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:35.801  4301  7156 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:04:35.806  4301  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:04:35.806  4301  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:04:35.811  7036  7036 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 19:04:35.811  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:35.811  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:35.812  7138  7138 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 19:04:35.812  7138  7138 D ProfileConfigQcom: Adding HeadsetService
09-06 19:04:35.813  7138  7138 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 19:04:35.813  7138  7138 D ProfileConfigQcom: Adding A2dpService
09-06 19:04:35.814  7138  7138 D ProfileConfigQcom: [BTUI] HidService is supported
09-06 19:04:35.814  7138  7138 D ProfileConfigQcom: Adding HidService
09-06 19:04:35.815  7138  7138 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-06 19:04:35.816  7138  7138 D ProfileConfigQcom: Adding HealthService
09-06 19:04:35.816  7138  7138 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-06 19:04:35.818  7138  7138 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 19:04:35.819  7138  7138 D ProfileConfigQcom: Adding PanService
09-06 19:04:35.819  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:04:35.819  7138  7138 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 19:04:35.820  7138  7138 D ProfileConfigQcom: Adding GattService
09-06 19:04:35.820  7112  7160 W FormManager: Network not available. Please check & try again.
09-06 19:04:35.821  7138  7138 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 19:04:35.821  7138  7138 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:04:35.822  7138  7138 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 19:04:35.824  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:35.825  7112  7161 V FormManager: Network unavailable.
,09-06 19:04:35.826  7138  7138 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-06 19:04:35.832  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:04:35.833  7112  7161 V FormManager: Network unavailable.
09-06 19:04:35.834  7138  7138 V LGMDMManagerInternal: Create singleton instance
09-06 19:04:35.845  7066  7066 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 19:04:35.847  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:04:35.847  7066  7066 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 19:04:35.879  7066  7066 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:04:35.879  7066  7066 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:35.885  7066  7066 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 19:04:35.887  7066  7066 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 19:04:35.887  7066  7066 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
09-06 19:04:35.887  7066  7066 V SoundPool: doLoad: loading sample sampleID=1
09-06 19:04:35.887  7066  7164 V SoundPool: Start decode
09-06 19:04:35.887  7066  7164 V MediaPlayer[Native]: decode(32, 10857164, 17813)
09-06 19:04:35.888   325  1368 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 19:04:35.888   325  1368 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 19:04:35.889   325  1368 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 19:04:35.889   325  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 19:04:35.889   325  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 19:04:35.889   325  1368 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 19:04:35.889  7066  7066 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:04:35.889   325  1368 V MediaPlayerService: player type = 3
09-06 19:04:35.889   325  1368 V AwesomePlayer: AwesomePlayer create()
09-06 19:04:35.890   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:35.890   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:35.890   325  1368 V AwesomePlayer: setAudioSink() 
09-06 19:04:35.890   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:35.890   325  1368 V AudioCache: notify(0xb16a6300, 8, 0, 0)
09-06 19:04:35.890   325  1368 V AudioCache: ignored
09-06 19:04:35.890   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:35.891   325  1368 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 19:04:35.891   325  1368 V AwesomePlayer: setDataSource_l dataSource
09-06 19:04:35.891   325  1368 V LGParserOSAL: SniffLGParser start
09-06 19:04:35.891   325  1368 V LGParserOSAL: MainType:5, SubType=0
09-06 19:04:35.891   325  1368 V LGParserOSAL: #### check Mime : application/ogg
09-06 19:04:35.891   325  1368 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 19:04:35.892   325  1368 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 19:04:35.894  7138  7138 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:04:35.900  6786  6786 D UEI.SmartControl: QS Service created
09-06 19:04:35.902  7138  7138 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:35.902  7138  7138 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:35.902  7138  7138 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:35.903  7138  7138 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:35.903  7138  7138 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 19:04:35.904  7066  7066 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:04:35.905  7066  7066 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:04:35.905  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-06 19:04:35.910  7083  7083 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-06 19:04:35.914  7066  7066 V LGMDMManager: Create singleton instance
09-06 19:04:35.918  6786  6786 I UEI.SmartControl: Service initServices...
09-06 19:04:35.918  6786  6786 D UEI.SmartControl: QS start get config
09-06 19:04:35.947   325  1368 V LGParserOSAL: supported mime: application/ogg
09-06 19:04:35.947   325  1368 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 19:04:35.947   325  1368 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 19:04:35.947   325  1368 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 19:04:35.947   325  1368 V AwesomePlayer: AudioTrack Setting
09-06 19:04:35.947   325  1368 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 19:04:35.947   325  1368 V AwesomePlayer: setAudioSource() 
09-06 19:04:35.947   325  1368 V MediaPlayerService: prepare
09-06 19:04:35.947   325  1368 V AwesomePlayer: prepareAsync_l() 
09-06 19:04:35.947   325  1368 V MediaPlayerService: wait for prepare
09-06 19:04:35.947   325  7166 V AwesomePlayer: onPrepareAsyncEvent() 
,09-06 19:04:35.947   325  7166 V AwesomePlayer: initAudioDecoder() 
09-06 19:04:35.947   325  7166 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:04:35.947   325  7166 V AudioSystem: isOffloadSupported()
09-06 19:04:35.947   325  7166 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:04:35.947   325  7166 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:04:35.947   325  7166 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:04:35.947   325  7166 V AwesomePlayer: getUseOffload() = 0 
09-06 19:04:35.947   325  7166 V OMXCodec: OMXCodec::Create
09-06 19:04:35.947   325  7166 V OMXCodec: findMatchingCodecs()
09-06 19:04:35.947   325  7166 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 19:04:35.947   325  7166 V OMXCodec: matchingCodecs.size()=1
09-06 19:04:35.947   325  7166 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 19:04:35.949   325  7166 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 19:04:35.949   325  7166 V LGCodecAdapter: LG Codec Adapter start
09-06 19:04:35.949   325  7166 V OMXCodec: OMXCodec Createtor
09-06 19:04:35.949   325  7166 V OMXCodec: setComponentRole
09-06 19:04:35.949   325  7166 V OMXCodec: configureCodec protected=0
09-06 19:04:35.949   325  7166 V LGCodecAdapter: called getLGCodecSpecificData
09-06 19:04:35.949   325  7166 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 19:04:35.949   325  7166 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 19:04:35.949   325  7166 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 19:04:35.949   325  7166 V LGCodecOSAL: Not support LGCodec
09-06 19:04:35.949   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:04:35.949   325  7166 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 19:04:35.949   325  7166 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 19:04:35.949   325  7166 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 19:04:35.949   325  7166 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:04:35.949   325  7166 V AudioSystem: isOffloadSupported()
09-06 19:04:35.949   325  7166 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:04:35.949   325  7166 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:04:35.949   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 19:04:35.949   325  7166 V OMXCodec: init()
09-06 19:04:35.949   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 19:04:35.949   325  7166 V OMXCodec: allocateBuffers
09-06 19:04:35.949   325  7166 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 19:04:35.949   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-06 19:04:35.950   325  7166 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:04:35.95,0   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-06 19:04:35.950   325  7166 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c31f0 on output port
09-06 19:04:35.950   325  7166 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:04:35.950   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:04:35.950   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:04:35.950   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 19:04:35.950   325  7166 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:04:35.951   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 19:04:35.951   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 19:04:35.951   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 19:04:35.951   325  7166 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 19:04:35.951   325  7166 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 19:04:35.951   325  7166 V AudioCache: notify(0xb16a6300, 5, 0, 0)
09-06 19:04:35.951   325  7166 V AudioCache: ignored
09-06 19:04:35.951   325  7166 V AudioCache: notify(0xb16a6300, 1, 0, 0)
09-06 19:04:35.951   325  7166 V AudioCache: prepared
09-06 19:04:35.951   325  1368 V AudioCache: wait - success
09-06 19:04:35.951   325  1368 V MediaPlayerService: start
09-06 19:04:35.951   325  1368 V AwesomePlayer: play_l() 
09-06 19:04:35.951   325  1368 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 19:04:35.951   325  1368 V AwesomePlayer: createAudioPlayer_l
09-06 19:04:35.951   325  1368 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 19:04:35.951   325  1368 V AwesomePlayer: startAudioPlayer_l() 
09-06 19:04:35.951   325  1368 D AudioPlayer: start of Playback, useOffload 0
09-06 19:04:35.951   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:04:35.951   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:35.952   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815344
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 19,:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 19:04:35.953   325  7168 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c36f0 on output port
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 19:04:35.953   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 19:04:35.954   325  1368 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 19:04:35.954  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:04:35.954   325  1368 V AudioCache: notify(0xb16a6300, 6, 0, 0)
09-06 19:04:35.954   325  1368 V AudioCache: ignored
09-06 19:04:35.955   325  1368 V MediaPlayerService: wait for playback complete
09-06 19:04:35.955  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 19:04:35.955   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.956   325  7169 V AudioCache: memcpy(0xaf006000, 0xb0407000, 4096)
09-06 19:04:35.956   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.956   325  7169 V AudioCache: memcpy(0xaf007000, 0xb0407000, 4096)
09-06 19:04:35.956   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.956   325  7169 V AudioCache: memcpy(0xaf008000, 0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: memcpy(0xaf009000, 0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: memcpy(0xaf00a000, 0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: memcpy(0xaf00b000, 0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.957   325  7169 V AudioCache: memcpy(0xaf00c000, 0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: memcpy(0xaf00d000, 0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: memcpy(0xaf00e000, 0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: memcpy(0xaf00f000, 0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.958   325  7169 V AudioCache: memcpy(0xaf010000, 0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: memcpy(0xaf011000, 0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: memcpy(0xaf012000, 0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: memcpy(0xaf013000, 0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.959   325  7169 V AudioCache: memcpy(0xaf014000, 0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: memcpy(0xaf015000, 0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: memcpy(0xaf016000, 0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: memcpy(0xaf017000, 0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.960   325  7169 V AudioCache: memcpy(0xaf018000, 0xb0407000, 4096)
09-06 19:04:35.961  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3352
09-06 19:04:35.962   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.962   325  7169 V AudioCache: memcpy(0xaf019000, 0xb0407000, 4096)
09-06 19:04:35.962   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.962   325  7169 V AudioCache: memcpy(0xaf01a000, 0xb0407000, 4096)
09-06 19:04:35.962   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.962   325  7169 V AudioCache: memcpy(0xaf01b000, 0xb0407000, 4096)
09-06 19:04:35.962   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.962   325  7169 V AudioCache: memcpy(0xaf01c000, 0xb0407000, 4096)
09-06 19:04:35.963   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.963   325  7169 V AudioCache: memcpy(0xaf01d000, 0xb0407000, 4096)
09-06 19:04:35.963   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.963   325  7169 V AudioCache: memcpy(0xaf01e000, 0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: memcpy(0xaf01f000, 0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: memcpy(0xaf020000, 0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: memcpy(0xaf021000, 0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.964   325  7169 V AudioCache: memcpy(0xaf022000, 0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: memcpy(0xaf023000, 0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: memcpy(0xaf024000, 0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: memcpy(0xaf025000, 0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.965   325  7169 V AudioCache: memcpy(0xaf026000, 0xb0407000, 4096)
09-06 19:04:35.966   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.966   325  7169 V AudioCache: memcpy(0xaf027000, 0xb0407000, 4096)
09-06 19:04:35.966   325  7169 V AudioCache: write(0xb0407000, 4096)
,09-06 19:04:35.966   325  7169 V AudioCache: memcpy(0xaf028000, 0xb0407000, 4096)
,09-06 19:04:35.966   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.966   325  7169 V AudioCache: memcpy(0xaf029000, 0xb0407000, 4096)
09-06 19:04:35.966   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.966   325  7169 V AudioCache: memcpy(0xaf02a000, 0xb0407000, 4096)
09-06 19:04:35.967   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.967   325  7169 V AudioCache: memcpy(0xaf02b000, 0xb0407000, 4096)
09-06 19:04:35.967   325  7169 V AudioCache: write(0xb0407000, 4096)
,09-06 19:04:35.967   325  7169 V AudioCache: memcpy(0xaf02c000, 0xb0407000, 4096)
09-06 19:04:35.967   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.967   325  7169 V AudioCache: memcpy(0xaf02d000, 0xb0407000, 4096)
09-06 19:04:35.967   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.967   325  7169 V AudioCache: memcpy(0xaf02e000, 0xb0407000, 4096)
,09-06 19:04:35.968   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.968   325  7169 V AudioCache: memcpy(0xaf02f000, 0xb0407000, 4096)
09-06 19:04:35.968   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.968   325  7169 V AudioCache: memcpy(0xaf030000, 0xb0407000, 4096)
09-06 19:04:35.968   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.968   325  7169 V AudioCache: memcpy(0xaf031000, 0xb0407000, 4096)
09-06 19:04:35.968   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.968   325  7169 V AudioCache: memcpy(0xaf032000, 0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: memcpy(0xaf033000, 0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: write(0xb0407000, 4096)
,09-06 19:04:35.969   325  7169 V AudioCache: memcpy(0xaf034000, 0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: memcpy(0xaf035000, 0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: memcpy(0xaf036000, 0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: write(0xb0407000, 4096)
09-06 19:04:35.969   325  7169 V AudioCache: memcpy(0xaf037000, 0xb0407000, 4096)
09-06 19:04:35.970   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 19:04:35.970   325  7169 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:04:35.970   325  7169 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:04:35.970   325  7169 V AwesomePlayer: postAudioEOS() 
09-06 19:04:35.970   325  7169 V AudioCache: write(0xb0407000, 280)
09-06 19:04:35.970   325  7169 V AudioCache: memcpy(0xaf038000, 0xb0407000, 280)
09-06 19:04:35.971   325  7166 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 19:04:35.971   325  7166 V AwesomePlayer: onStreamDone
,09-06 19:04:35.971   325  7166 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 19:04:35.971   325  7166 V AudioCache: notify(0xb16a6300, 2, 0, 0)
09-06 19:04:35.971   325  7166 V AudioCache: playback complete
09-06 19:04:35.971   325  7166 V AwesomePlayer: pause_l() 
09-06 19:04:35.971   325  7166 V AudioCache: notify(0xb16a6300, 7, 0, 0)
09-06 19:04:35.971   325  7166 V AudioCache: ignored
09-06 19:04:35.971   325  1368 V AudioCache: wait - success
09-06 19:04:35.971   325  7166 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:35.971   325  1368 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 19:04:35.971   325  7166 D AudioPlayer: Pause Playback at 1068125
09-06 19:04:35.972   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:35.972   325  1368 V AudioCache: notify(0xb16a6300, 8, 0, 0)
09-06 19:04:35.972   325  1368 V AudioCache: ignored
09-06 19:04:35.972   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:35.972   325  1368 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 19:04:35.972   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
,09-06 19:04:35.972   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 19:04:35.972   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 19:04:35.972   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c36f0 on port 1
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 19:04:35.972   325  7168 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 19:04:35.972   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:04:35.972   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,09-06 19:04:35.972   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 19:04:35.973   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 19:04:35.973   325  1368 D AudioPlayer: AudioPlayer releasing audio source
09-06 19:04:35.973   325  1368 D AudioPlayer: AudioPlayer done releasing audio source
09-06 19:04:35.973   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:35.973   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:35.973   325  1368 V AwesomePlayer: ~AwesomePlayer call
09-06 19:04:35.973   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:35.973   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:35.974  7066  7164 V SoundPool: close(32)
09-06 19:04:35.974  7066  7164 V SoundPool: pointer = 0x9fe83000, size = 205080, sampleRate = 48000, numChannels = 2
09-06 19:04:36.192  6786  6786 I UEI.SmartControl: Supports setup maps: true
09-06 19:04:36.195  6786  6786 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:04:36.195  6786  6786 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:04:36.195  6786  6786 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:04:36.195  6786  6786 I UEI.SmartControl: ### init IR Blaster...
,09-06 19:04:36.198  6786  6786 D serial_port: Configuring serial port
09-06 19:04:36.199  6786  6786 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:04:36.199  6786  6786 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:04:36.199  6786  6786 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:04:36.199  6786  6786 I UEI.SmartControl: Get version...
,09-06 19:04:36.218  6786  7170 D UEI.SmartControl: serial port data available: 21
,09-06 19:04:36.244  6786  6786 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-06 19:04:36.244  6786  6786 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:04:36.244  6786  6786 I UEI.SmartControl: QS saving settings...
,09-06 19:04:36.246  6786  6786 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:04:36.265  6786  7170 D UEI.SmartControl: serial port data available: 4
,09-06 19:04:36.295  6786  7176 I UEI.SmartControl: Device manager: loading config....
,09-06 19:04:36.295  6786  7176 D UEI.SmartControl: ----------- loading internal config...
09-06 19:04:36.296  6786  6786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 19:04:36.298  6786  6786 E UEI.SmartControl: Services init done
09-06 19:04:36.299  6786  6786 D UEI.SmartControl: QS Service init finished
09-06 19:04:36.300  6786  6786 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:04:36.300  6786  6786 D UEI.SmartControl: QS Service version code: 201091
09-06 19:04:36.300  6786  6786 D UEI.SmartControl: Service requested: Control
09-06 19:04:36.309  6786  7176 E UEI.SmartControl: Loading SETTINGS...
,09-06 19:04:36.312  6786  6786 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 19:04:36.323  6786  6786 D UEI.SmartControl: Internal service binding...
,09-06 19:04:36.324  7066  7066 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 19:04:36.326  6786  6802 I UEI.SmartControl: ------ IControl API: 11
09-06 19:04:36.327  6786  6802 D UEI.SmartControl: File observer start...
09-06 19:04:36.328  6786  6802 E UEI.SmartControl: IR Port is disabled: false
09-06 19:04:36.328  6786  6802 D UEI.SmartControl: Starting file observer...
09-06 19:04:36.330  6786  6802 I UEI.SmartControl: Registering callback...
09-06 19:04:36.331  6786  6801 I UEI.SmartControl: ------ IControl API: 19
09-06 19:04:36.333  6786  6801 I UEI.SmartControl: Registering Services Ready callback...
09-06 19:04:36.334  6786  7176 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-06 19:04:36.358  6786  7175 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:04:36.358  6786  7175 D UEI.SmartControl: -----service ready thread exits
,09-06 19:04:36.358  7066  7081 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 19:04:36.360  7066  7162 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 19:04:36.360  7066  7162 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 19:04:36.361  7066  7066 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 19:04:36.361  7066  7066 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 19:04:36.361  6786  6802 I UEI.SmartControl: ------ IControl API: 8
09-06 19:04:36.363  7066  7066 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 19:04:36.363  7066  7066 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 19:04:36.364  7066  7066 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 19:04:36.364  7066  7066 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 19:04:36.365  7066  7066 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 19:04:36.366  7066  7066 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 19:04:36.367  7066  7066 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-06 19:04:36.369  7066  7066 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 19:04:36.371  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:04:36.372  7066  7066 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:04:36.372  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:04:36.374  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:04:36.375  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 19:04:36.376  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 19:04:36.377  7066  7066 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473181476376]
09-06 19:04:36.381  7066  7066 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 19:04:36.383  1032  2039 I ActivityManager: Killing 6126:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-06 19:04:36.408  7066  7181 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 19:04:36.415  1032  2039 I ActivityManager: Killing 6678:com.lge.email/u0a23 (adj 15): empty #18
09-06 19:04:36.445  1032  1564 W libprocessgroup: failed to open /acct/uid_10027/pid_6126/cgroup.procs: No such file or directory
,09-06 19:04:36.459  1032  2000 W libprocessgroup: failed to open /acct/uid_10023/pid_6678/cgroup.procs: No such file or directory
,09-06 19:04:36.461  7066  7066 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-06 19:04:36.465  7066  7066 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:04:36.466  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 19:04:36.467  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 19:04:36.468  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-06 19:04:36.468  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 19:04:36.469  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 19:04:36.483  7066  7066 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-06 19:04:37.253  1032  1048 D WifiServiceImplEx: setWifiEnabled: true pid=6898, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:04:37.255  1032  1048 D WifiService: setWifiEnabled: true pid=6898, uid=10118
09-06 19:04:37.255  1032  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:04:37.283  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:37.284  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:37.284  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:04:37.285  1032  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 19:04:37.285  1032  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 19:04:37.288  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 19:04:37.288  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:04:37.288  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 19:04:37.288  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:04:37.288  1032  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 19:04:37.288  1032  1523 E WifiHW  : unknown target_country: EU , set to default
09-06 19:04:37.288  1032  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,09-06 19:04:37.288  1032  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
09-06 19:04:37.289  1032  1523 I WifiUtil: gEnableBmps=1
09-06 19:04:37.336  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:37.361  1032  1103 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:04:37.371  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:37.372  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:37.378  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:37.382  1032  1103 D Tethering: MasterInitialState.processMessage what=3
09-06 19:04:37.392  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:37.396  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:37.396  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:37.398  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:04:37.401  6568  7035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:04:37.413  5833  5833 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:04:37.421  5833  5833 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:04:37.439  2172  2172 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:37.495  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:37.531  1032  1939 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7186 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-06 19:04:37.537  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:37.538  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:04:37.601  7186  7186 I AppUp4:AppBoxCP: onCreate
,09-06 19:04:37.602  7186  7186 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-06 19:04:37.613  7186  7186 I AppUp4:DB:  setFingerPrint start
09-06 19:04:37.614  7186  7186 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-06 19:04:37.622  7186  7186 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-06 19:04:37.622  7186  7186 I AppUp4:DB:  SDK version = 21
,09-06 19:04:37.623  7186  7186 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-06 19:04:37.625  7186  7186 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-06 19:04:37.626  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:04:37.626  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:37.630  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-06 19:04:37.630  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 19:04:37.637  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:04:37.680  7186  7186 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:37.680  7186  7186 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:37.689  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fa7b83b
09-06 19:04:37.689  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:04:37.689  7186  7186 D AppUp4:CustFacade: isPhone : true
09-06 19:04:37.690  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:04:37.690  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-06 19:04:37.690  7186  7186 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-06 19:04:37.691  7186  7218 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-06 19:04:37.691  7186  7218 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-06 19:04:37.692  7186  7218 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-06 19:04:37.694  1032  1047 I ActivityManager: Killing 6712:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-06 19:04:37.738  1032  2023 W libprocessgroup: failed to open /acct/uid_10061/pid_6712/cgroup.procs: No such file or directory
09-06 19:04:37.740  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:37.740  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:04:37.742  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:04:37.747  1032  1367 V AlarmManager: ELAPSED_WAKEUP set : Alarm{647cda0 type 2 when 182437 com.google.android.gms} when 182437
09-06 19:04:37.751  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:37.762  4301  7221 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:04:37.767  4301  7222 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:37.768  4301  7222 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:04:37.816  1032  2000 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7223 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 19:04:37.895  7223  7223 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:04:37.896  7223  7223 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:04:37.897  7223  7223 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:04:37.898  7223  7223 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:04:37.986  7223  7223 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-06 19:04:38.001  7223  7223 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-06 19:04:38.034  1032  1103 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 19:04:38.037  1032  1103 D Tethering: InitialState.processMessage what=4
09-06 19:04:38.038  1032  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:04:38.044   314   876 D SoftapController: Softap fwReload - Ok
,09-06 19:04:38.051  1032  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (749ms)
09-06 19:04:38.054   314   876 D CommandListener: Setting iface cfg
09-06 19:04:38.054   314   876 D CommandListener: Trying to bring down wlan0
09-06 19:04:38.055   314   876 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:04:38.057  1032  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 19:04:38.059  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:38.059  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:38.059  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:04:38.050  7252  7252 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:38.050  7252  7252 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:04:38.069  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:38.073  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:38.074  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 19:04:38.074  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:38.075  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 19:04:38.076  1032  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:04:38.076  1032  1523 D WifiMonitor: connecting to supplicant
09-06 19:04:38.084  7252  7252 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:04:38.090  7223  7223 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:04:38.115  7252  7252 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:04:38.116  7252  7252 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-06 19:04:38.130  7223  7223 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:38.130  7223  7223 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:38.194  7252  7252 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:04:38.223  7223  7223 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:04:38.238  7252  7252 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-06 19:04:38.244  7252  7252 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-06 19:04:38.246  7252  7252 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 19:04:38.247  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:04:38.247  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 19:04:38.248  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:04:38.248  1032  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:04:38.249  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:38.249  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:38.249  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:38.250  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:38.250  7223  7223 I HubEmail: JNI_OnLoad()
09-06 19:04:38.250  7223  7223 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:04:38.250  7223  7223 I HubEmail: registerNatives()
09-06 19:04:38.250  7223  7223 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:04:38.250  7223  7223 I HubEmail: registerNativeMethods()
09-06 19:04:38.250  7223  7223 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:04:38.250  1032  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:04:38.250  1032  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 19:04:38.250  7223  7223 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-06 19:04:38.251  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:04:38.251  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:38.251  1032  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 19:04:38.251  1032  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:04:38.251  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:04:38.251  1032  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-06 19:04:38.252  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:38.252  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:38.252  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:04:38.252  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.253  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.253  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.253  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.253  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-06 19:04:38.255  1032  7258 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-06 19:04:38.255  1032  7258 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:04:38.255  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:04:38.255  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:04:38.255  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 19:04:38.255  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 19:04:38.255  1032  7258 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:04:38.255  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:04:38.278  1032  1047 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7262 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-06 19:04:38.285  1032  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:04:38.286  1032  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-06 19:04:38.286  1032  1523 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:04:38.286  1032  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:04:38.286  1929  1929 D WfdService: Waiting for WifiP2p enabling
09-06 19:04:38.287  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:38.287  1032  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:04:38.289  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:38.289  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:38.289  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:38.289  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:38.290  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:38.290  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:38.290  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:38.290  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:38.290  7112  7259 W FormManager: Network not available. Please check & try again.
09-06 19:04:38.290  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:04:38.290  1032  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 19:04:38.291  7112  7260 V FormManager: Network unavailable.
09-06 19:04:38.293  7112  7260 V FormManager: N,etwork unavailable.
,09-06 19:04:38.295  1032  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 19:04:38.300  1032  1964 I ActivityManager: Killing 6193:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-06 19:04:38.303  7223  7261 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.310  1032  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-06 19:04:38.311  1032  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:04:38.346  1032  2000 W libprocessgroup: failed to open /acct/uid_10080/pid_6193/cgroup.procs: No such file or directory
,09-06 19:04:38.347  1032  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:04:38.347  1032  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 19:04:38.348  1032  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:04:38.348  1032  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:04:38.348  1032  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:04:38.349  1032  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:04:38.349  1032  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:04:38.349  1032  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:04:38.349  1032  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:04:38.349  1032  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:04:38.350  1032  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:04:38.350  1032  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 19:04:38.350  1032  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:04:38.350  1032  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 19:04:38.350  1032  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 19:04:38.351  1032  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:04:38.351  1032  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 19:04:38.351  1032  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 19:04:38.351  1032  1523 D WifiNative-HAL: Setting external_sim to 1
09-06 19:04:38.351  1032  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 19:04:38.351  1929  1929 D WfdsService: Supplicant Connection state is changed : true
09-06 19:04:38.351  1032  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:04:38.351  1032  1523 I WifiNative-HAL: startHal
09-06 19:04:38.351  1929  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:04:38.352  1929  2284 D WfdsService: Set the WFDS Monitor: true
09-06 19:04:38.352  1032  1523 D wifi    : setting scan oui 0xaf6e24c0
09-06 19:04:38.352  1929  2284 D WfdsMonitor: WfdsMonitorThread create
09-06 19:04:38.352  1929  2284 D WfdsMonitor: WFDS Monitor is created and started
09-06 19:04:38.352  1929  2284 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:04:38.352  1032  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:04:38.352  1032  1523 I WifiNative-HAL: startHal
09-06 19:04:38.352  1032  1523 D wifi    : setting scan oui 0xaf6e24c0
09-06 19:04:38.352  1032  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 19:04:38.353  1032  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 19:04:38.353  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 19:04:38.353  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 19:04:38.353  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,09-06 19:04:38.353  1929  7283 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:04:38.354  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:04:38.354  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:04:38.354  1929  7283 E CtrlSupplicant: Succeed to open control connection
,09-06 19:04:38.354  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:04:38.354  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:04:38.354  1929  7283 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:04:38.354  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,09-06 19:04:38.354  1929  7283 D WfdsMonitor: Supplicant connection established
09-06 19:04:38.355  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:04:38.355  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:04:38.355  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-06 19:04:38.355  1929  2284 D WfdsService: Connected to the supplicant for wfds
09-06 19:04:38.355  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:04:38.356  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:04:38.356  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-06 19:04:38.356  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:04:38.356  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 19:04:38.357  7252  7252 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:04:38.357  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,09-06 19:04:38.357  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:04:38.357  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-06 19:04:38.360  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:04:38.361  1032  1523 E WifiNative: : [183,073,221 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions,
,09-06 19:04:38.361  1032  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:04:38.362  1032  1523 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:04:38.362  1032  1523 D WifiNative-wlan0: doString: [STATUS]
09-06 19:04:38.362  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=],
09-06 19:04:38.362  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:04:38.362  1032  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:04:38.362  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
,09-06 19:04:38.363  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:04:38.363  1032  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.366   314   876 D CommandListener: Setting iface cfg
,09-06 19:04:38.366   314   876 D CommandListener: Trying to bring up p2p0
09-06 19:04:38.366  1032  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:04:38.366  1032  1522 D LGWifiP2pService: P2pEnablingState
,09-06 19:04:38.367  1032  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.367  1032  1522 D LGWifiP2pService: P2p socket connection successful
09-06 19:04:38.367  1032  1522 D LGWifiP2pService: P2pEnabledState
,09-06 19:04:38.369  1032  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:04:38.369  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:04:38.369  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-06 19:04:38.369  1032  1545 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:04:38.369  1032  1545 I WifiNative-HAL: startHal
09-06 19:04:38.369  1032  1545 D wifi    : getting scan capabilities on interface[1] = 0xaf6e24c0
09-06 19:04:38.369  1032  1545 D wifi    : failed to get capabilities : -3
09-06 19:04:38.369  1032  1545 E WifiScanningService: could not get scan capabilities
,09-06 19:04:38.369  1032  1546 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.370  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:04:38.370  1929  1929 D WfdsService: WifiP2pState is changed : true
09-06 19:04:38.370  1929  2284 D WfdsService: Receive the WFDS_ENABLE Method
,09-06 19:04:38.370  1929  2284 D WfdsService: Set the WFDS Monitor: true
09-06 19:04:38.370  1929  2284 D WfdsService: Connected to the supplicant for wfds
09-06 19:04:38.371  1929  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 19:04:38.371  7252  7252 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE,
09-06 19:04:38.371  1032  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:04:38.371  1929  2284 D WfdsService: selectPreferredScanChannel [36]
09-06 19:04:38.371  1929  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-06 19:04:38.371  1032  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:04:38.371  1032  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0,
,09-06 19:04:38.372  1032  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:04:38.372  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=183085  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:38.373  1032  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:04:38.373  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=183086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:38.373  1032  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 19:04:38.374  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:04:38.374  1032  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 19:04:38.374  1929  1929 D WfdsService: isConnected: false
09-06 19:04:38.374  1032  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
,09-06 19:04:38.375  1032  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:04:38.375  1032  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:04:38.375  1032  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,09-06 19:04:38.376  7252  7252 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:04:38.376  1032  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:04:38.376  1032  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:04:38.377  1032  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:04:38.377  1032  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 19:04:38.377  7252  7252 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 19:04:38.377  1032  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:04:38.377  1032  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:04:38.377  1032  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:04:38.377  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 19:04:38.377  1032  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-06 19:04:38.378  1032  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:04:38.378  1032  1522 D LGWifiP2pService: before postfix = G3
,09-06 19:04:38.378  1032  1522 D WifiServerServiceExt: postfix byte check : 2
09-06 19:04:38.378  1032  1522 D LGWifiP2pService: after postfix = G3
09-06 19:04:38.378  1032  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 19:04:38.378  1032  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:04:38.379  1032  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:04:38.379  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:04:38.380  7252  7252 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.380  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:38.380  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:38.380  7252  7252 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:04:38.380  7252  7252 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.381  7252  7252 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.381  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.381  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.381  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-06 19:04:38.381  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:04:38.381  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.381  1032  7258 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.381  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.381  1032  7258 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.381  1032  7258 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.382  1032  7258 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.382  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.382  1032  7258 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.382  1032  7258 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.382  1032  7258 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.382  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.382  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:38.382  1929  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.382  1929  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.382  1032  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:04:38.383  1032  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:04:38.383  1032  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 19:04:38.383  1032  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
,09-06 19:04:38.383  1032  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:04:38.383  1032  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 19:04:38.384  1032  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:04:38.384  1032  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 19:04:38.384  1032  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 19:04:38.384  1032  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 19:04:38.384  1032  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 19:04:38.384  1032  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 19:04:38.385  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:04:38.385  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:04:38.385  1929  1929 D WfdsService: Update P2p Interface State: 3
09-06 19:04:38.385  1032  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:04:38.385  1032  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:04:38.386  1032  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 19:04:38.386  1032  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 19:04:38.387  1032  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:04:38.387  1032  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,09-06 19:04:38.387  1032  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:04:38.387  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:04:38.398  1032  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 19:04:38.398  1032  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:04:38.398  1032  1522 D LGWifiP2pService: InactiveState
09-06 19:04:38.398  1032  1522 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.398  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.398  1032  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 19:04:38.400  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-06 19:04:38.400  7252  7252 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.400  1929  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,09-06 19:04:38.400  1032  7258 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,09-06 19:04:38.400  1032  7258 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.400  1032  7258 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.400  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:38.401  7252  7252 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:04:38.401  7252  7252 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.401  1032  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  7252  7252 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.401  1032  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:38.402  1929  2284 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 19:04:38.402  1032  1032 E WifiServerServiceExt: No p2p device connected
09-06 19:04:38.402  1929  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.402  1929  7283 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.402  1032  7258 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.402  1032  7258 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.402  1032  7258 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.402  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.402  1032  7258 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:38.402  1032  7258 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.402  1032  7258 E WifiMonitor: handleE,vent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.402  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:38.402  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:04:38.402  7252  7252 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:38.402  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:04:38.402  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:38.402  1032  7258 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:38.402  1032  7258 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:38.405  1032  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:04:38.405  1032  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:04:38.406  1032  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:04:38.406  1032  1523 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:04:38.406  1032  1523 D WifiNative-wlan0: SCAN: returned false
09-06 19:04:38.407  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=183120  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:38.408  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=183121  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:38.408  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:38.408  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:38.409  1032  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:38.409  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.409  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.409  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:04:38.409  1032  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:38.409  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:38.410  1032  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:38.410  1032  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:38.410  1032  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:38.411  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:38.411  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:04:38.412  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:38.412  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-06 19:04:38.421  7262  7262 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:38.422  7262  7262 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:04:38.423  7262  7262 D PhoneMonitor: Register our PhoneStateListener
09-06 19:04:38.432  7262  7262 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:04:38.433  7262  7262 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-06 19:04:38.441  7262  7262 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-06 19:04:38.442  7262  7262 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-06 19:04:38.442  7262  7262 D TelephonyAutoProfiling: [parse] Load xml
09-06 19:04:38.445  7262  7262 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-06 19:04:38.445  7262  7262 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-06 19:04:38.446  7262  7262 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-06 19:04:38.450  7262  7262 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-06 19:04:38.484  1032  1688 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7288 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:04:38.484  1032  1688 I ActivityManager: Killing 6225:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-06 19:04:38.547  1032  1964 W libprocessgroup: failed to open /acct/uid_10097/pid_6225/cgroup.procs: No such file or directory
,09-06 19:04:38.792  1032  1688 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7309 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-06 19:04:38.794  1032  1688 I ActivityManager: Killing 6751:com.lge.eula/1000 (adj 15): empty #17
09-06 19:04:38.799  7252  7252 E wpa_supplicant: USIM:  scard_init function
09-06 19:04:38.799  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 19:04:38.800  1032  7258 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 19:04:38.800  7252  7252 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 19:04:38.802  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 19:04:38.802  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-06 19:04:38.802  1032  7258 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:04:38.802  1032  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:38.803  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:04:38.803  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 19:04:38.803  1032  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:38.803  1032  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:38.804  1032  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:38.804  1032  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 19:04:38.847  1032  1964 W libprocessgroup: failed to open /acct/uid_1000/pid_6751/cgroup.procs: No such file or directory
,09-06 19:04:38.850  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183563  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:04:38.851  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183564  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:04:38.857  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:38.857  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:38.859  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.859  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.859  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:04:38.859  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:38.859  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:04:38.862  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:38.915  7252  7252 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:04:38.918  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:04:38.918  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:04:38.918  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:04:38.918  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:04:38.919  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:38.919  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:38.920  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=183632  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:04:38.920  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=183633  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:04:38.921  1032  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183634
09-06 19:04:38.921  1032  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183634
09-06 19:04:38.922  1032  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183635
09-06 19:04:38.922  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183635
,09-06 19:04:38.922  1032  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183635
09-06 19:04:38.923  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183636  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:04:38.926  7252  7252 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:04:38.927  7252  7252 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:04:38.929  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:38.929  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:38.929  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:04:38.929  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:04:38.929  1032  7258 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:04:38.930  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:04:38.930  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:04:38.930  1032  7258 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:04:38.930  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:38.930  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:38.935  1032  2023 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7326 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:04:38.939  1032  2023 I ActivityManager: Killing 6768:com.lge.bnr/1000 (adj 15): empty #17
09-06 19:04:38.987  1032  1103 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 19:04:38.987  1032  1939 W libprocessgroup: failed to open /acct/uid_1000/pid_6768/cgroup.procs: No such file or directory
09-06 19:04:38.996  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183708  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:04:38.997  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.997  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:38.997  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:04:38.998  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:04:38.998  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:39.001  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.001  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.001  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:04:39.002  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=183715  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:04:39.002  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.002  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=183715  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:04:39.003  1032  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183716
09-06 19:04:39.003  1032  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183716
09-06 19:04:39.004  1032  1523 D WifiNative-wlan0: doString: [STATUS]
09-06 19:04:39.005  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:39.005  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:04:39.005  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:39.005  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 19:04:39.007  1032  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:04:39.008  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:39.008  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:39.010  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.010  1032  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 19:04:39.016  1032  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 19:04:39.016  1032  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-06 19:04:39.025  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.025  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.025  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:04:39.031  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:04:39.031  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:39.035  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.037  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.037  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.037  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:04:39.038  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:39.038  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:39.038  1032  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 19:04:39.038  1032  1531 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:04:39.038  1032  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:04:39.038  1032  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:04:39.038  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:04:39.038  1032  1531 D ConnectivityService: NetworkAgent connected
09-06 19:04:39.039  1032  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:04:39.039  1032  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:04:39.040  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.042  7326  7326 I art     : Almond Protected OAT
,09-06 19:04:39.045  1032  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:04:39.045  1032  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:04:39.045  1032  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:04:39.045  1032  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:04:39.045  1032  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 19:04:39.051  1032  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:04:39.052   314   876 D CommandListener: Setting iface cfg
09-06 19:04:39.056  1032  1523 E WifiStateMachine: Start Dhcp Watchdog 2
09-06 19:04:39.056  1032  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183769  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-06 19:04:39.057  1032  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183770  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:39.057  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183770  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:39.058  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:39.058  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:39.059  1032  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:39.059  1032  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:39.060  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:39.060  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:39.061  1032  7349 D DhcpStateMachine: StoppedState
09-06 19:04:39.061  1032  7349 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.062  1032  7349 D DhcpStateMachine: WaitBeforeStartState
09-06 19:04:39.062  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:39.062  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-06 19:04:39.064  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:39.064  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:04:39.065  1032  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=183778  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:39.066  1032  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=183779  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:39.066  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=183779  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:39.068  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:138253] from screen [on:0 period:7696539] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-06 19:04:39.069  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:7696540] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-06 19:04:39.069  1032  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:04:39.073  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.073  1032  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-06 19:04:39.073  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.074  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.074  1032  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.075  1032  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.075  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.075  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.076  1032  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:04:39.077  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:39.077  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:04:39.077  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
09-06 19:04:39.078  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
09-06 19:04:39.078  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:04:39.078  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:04:39.079  1032  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:04:39.079  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:04:39.079  1032  1523 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:04:39.079  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 19:04:39.079  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 19:04:39.080  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:04:39.080  1032  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a98ab19 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.080  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a98ab19 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.080  1032  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:04:39.080  1032  7349 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.080  1032  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:04:39.080  1032  7349 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 19:04:39.080  1032  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:04:39.081   314   876 D CommandListener: Setting iface cfg
09-06 19:04:39.082   314   876 D CommandListener: Trying to bring up wlan0
09-06 19:04:39.083  1032  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:04:39.084  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.084  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:39.084  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:04:39.084  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.085  1032  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.085  1032  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.086  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.086  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:39.086  1032  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:04:39.087  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:04:39.087  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:04:39.087  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:04:39.087  1032  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.087  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.087  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:04:39.088  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:04:39.088  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:04:39.088  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:04:39.088  1032  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:04:39.088  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
,09-06 19:04:39.106  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:04:39.106  7326  7326 D WeatherApplication: removeAccount
,09-06 19:04:39.106  1032  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-06 19:04:39.107  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:04:39.107  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:04:39.107  1032  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:04:39.108  1032  1531 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:04:39.108  7326  7326 D WeatherApplication: Account.length = 0
,09-06 19:04:39.110  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:39.110  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:39.111  7326  7326 E WeatherApplication: OPERATOR:OPEN
09-06 19:04:39.111  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.111  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.111  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:04:39.112  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.114  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:04:39.115  1032  1531 D ConnectivityService: Adding iface wlan0 to network 101
09-06 19:04:39.117  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.117  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.118  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:04:39.120  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:04:39.121  7326  7326 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:39
09-06 19:04:39.123  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-06 19:04:39.125  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.125  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.126  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:04:39.127  1032  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:04:39.129  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:04:39.130  7326  7326 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:04:39.130  7326  7326 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:04:39.132  7326  7326 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:04:39.133  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:39.133  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:39.134  7326  7326 D WeatherAncestor: connectivity changed - connection : true
09-06 19:04:39.135  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.135  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:39.135  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:04:39.136  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:39.136  7326  7326 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-06 19:04:39.144  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:39.144  1591  1591 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:04:39.144  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.146  7326  7326 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:04:39.146  7326  7326 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:04:39.146  7326  7326 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-06 19:04:39.148  1032  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:04:39.148  1032  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-06 19:04:39.149  1032  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-06 19:04:39.150   314   876 E Netd    : netlink response contains error (File exists)
09-06 19:04:39.150  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:39.150  1591  1591 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:04:39.150  1032  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-06 19:04:39.150  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.151  1032  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:04:39.151  1032  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-06 19:04:39.152  1032  1531 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-06 19:04:39.153  1032  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:04:39.153  1032  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:04:39.153  1032  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-06 19:04:39.153  1032  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 19:04:39.153  1032  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:39.153  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.153  1032  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:39.153  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:04:39.153  1032  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:04:39.153  1032  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:39.153  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.153  1032  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:04:39.153  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:04:39.153 , 1032  1531 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:04:39.153  1032  1531 D ConnectivityService:    accepting network in place of null
09-06 19:04:39.153  1032  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:39.155  1032  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:39.155  1032  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:39.156  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:04:39.156  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:04:39.157  1032  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:04:39.157  1032  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:04:39.157  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:04:39.159   314  7355 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 19:04:39.161  1032  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:39.161  1032  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:04:39.161  1032  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:04:39.162  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:04:39.162  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:04:39.162  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:04:39.162  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:04:39.164  1032  1531 D ConnectivityService: validation of new default Network = false
09-06 19:04:39.164  1032  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:04:39.164  1032  1531 D DSQN    : enableDataServiceNotify 
09-06 19:04:39.164  1032  1531 D DSQN    : start dsqn bin
,09-06 19:04:39.169  1032  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 19:04:39.170  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:39.170  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:39.170  1032  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:39.171  1591  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:04:39.160  7356  7356 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:39.160  7356  7356 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:39.184  7356  7356 E DSQN    : DSQN ssw
09-06 19:04:39.184  1032  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-06 19:04:39.186  7326  7326 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:04:39.188  7326  7326 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:39
09-06 19:04:39.239  1032  1047 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7361 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:04:39.240  1032  1047 I ActivityManager: Killing 2151:com.lge.music/u0a34 (adj 15): empty #17
,09-06 19:04:39.277   325  2142 V AudioFlinger: 2151 died, releasing its sessions
09-06 19:04:39.277   325  2142 V AudioFlinger:  pid 1839 @ 0
09-06 19:04:39.277   325  2142 V AudioFlinger:  pid 3488 @ 1
09-06 19:04:39.277   325  2142 V AudioFlinger:  pid 3488 @ 2
,09-06 19:04:39.282  1032  7349 D DhcpStateMachine: DHCPV4 request on wlan0
,09-06 19:04:39.282  1032  7349 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-06 19:04:39.282  1032  7349 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 19:04:39.270  7378  7378 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:39.280  7378  7378 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:39.293  7378  7378 I dhcpcd  : version 5.5.6 starting
09-06 19:04:39.296  7378  7378 E dhcpcd  : get_duid: m
09-06 19:04:39.296  7378  7378 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:04:39.296  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-06 19:04:39.329  1032  1522 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:39.329  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:04:39.329  1032  1522 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:04:39.340  1032  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:04:39.341  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:04:39.342  1032  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:04:39.343  1032  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:04:39.343  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-06 19:04:39.344  1032  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-06 19:04:39.367  1032  1564 W libprocessgroup: failed to open /acct/uid_10034/pid_2151/cgroup.procs: No such file or directory
,09-06 19:04:39.367  1804  7358 I CheckinService: active receiver: enabled
09-06 19:04:39.370  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:04:39.370  7378  7378 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:04:39.370  7378  7378 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:04:39.370  7378  7378 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 19:04:39.371  7378  7378 D dhcpcd  : wlan0: sending REQUEST (xid 0x7cfa67fa), next in 4.30 seconds
09-06 19:04:39.390  1804  7358 I CheckinService: Preparing to send checkin request
09-06 19:04:39.390  1804  7358 I EventLogService: Accumulating logs since 1473181353688
,09-06 19:04:39.406  7378  7378 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-06 19:04:39.409  1591  1591 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:04:39.410  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.411  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:39.430  1804  7358 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-06 19:04:39.431  7378  7378 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:04:39.431  7378  7378 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 19:04:39.431  7378  7378 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:04:39.431  7378  7378 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 19:04:39.431  7378  7378 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:04:39.432  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:04:39.432  7378  7378 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:04:39.432  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-06 19:04:39.503   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:04:39.503   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:04:39.503   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:04:39.504  7361  7393 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 19:04:39.505   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:04:39.505   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:04:39.505   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:04:39.506  7361  7393 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-06 19:04:39.524   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:04:39.524   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:04:39.524   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:04:39.525  7361  7397 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-06 19:04:39.531   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:04:39.531   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:04:39.531   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:04:39.532  7361  7397 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-06 19:04:39.591  1032  1981 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7405 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-06 19:04:39.614   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 23.554ms
,09-06 19:04:39.637   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 20.868ms
,09-06 19:04:39.646  7405  7405 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 19:04:39.646  7405  7405 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-06 19:04:39.656   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 355us total 18.595ms
09-06 19:04:39.666  7405  7405 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:04:39.666  7405  7405 I MultiDex: install
09-06 19:04:39.666  7405  7405 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:04:39.685  1032  7349 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-06 19:04:39.685  1032  7349 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 19:04:39.685  1032  7349 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:04:39.686  1032  7349 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:04:39.686  1032  7349 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 19:04:39.686  1032  7349 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:04:39.686  1032  7349 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:04:39.686  1032  7349 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 19:04:39.686  1032  7349 D DhcpStateMachine: RunningState
09-06 19:04:39.756  1032  2023 I art     : Explicit concurrent mark sweep GC freed 101887(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 1.311ms total 85.548ms
,09-06 19:04:39.760  7405  7405 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-06 19:04:39.791  7361  7361 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 19:04:39.801  7361  7361 I LibraryLoader: Loading: webviewchromium
,09-06 19:04:39.804  7361  7361 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4525-4528)
09-06 19:04:39.804  7361  7361 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:04:39.809  7361  7361 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35b412d2}
09-06 19:04:39.810  7361  7361 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:04:39.811  7361  7361 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:04:39.821  7361  7361 I BrowserStartupController: Initializing chromium process, renderers=0
,09-06 19:04:39.822  7361  7361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:04:39.832   325  2146 V AudioPolicyService: registerClient() client 0xb558a620, uid 10093
09-06 19:04:39.833  7361  7361 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 19:04:39.833  7361  7361 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-06 19:04:39.834  7361  7361 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-06 19:04:39.834  7361  7451 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 19:04:39.847  7361  7361 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:04:39.847  7361  7361 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:04:39.847  7361  7361 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:04:39.847  7361  7361 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:04:39.847  7361  7361 I Adreno-EGL: Remote Branch: 
09-06 19:04:39.847  7361  7361 I Adreno-EGL: Local Patches: 
09-06 19:04:39.847  7361  7361 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:04:39.926  7361  7361 I NSApplication: Starting up...
,09-06 19:04:40.002  1032  2039 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7465 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-06 19:04:40.005  1032  1892 I ActivityManager: Killing 6154:com.android.vending/u0a44 (adj 15): empty #17
09-06 19:04:40.029  7464  7464 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 19:04:40.093  7464  7464 I dex2oat : dex2oat took 63.513ms (threads: 4)
09-06 19:04:40.097  1032  2023 W libprocessgroup: failed to open /acct/uid_10044/pid_6154/cgroup.procs: No such file or directory
09-06 19:04:40.114  7405  7423 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:04:40.114  7405  7423 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:04:40.114  7405  7423 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:04:40.114  7405  7423 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:04:40.114  7405  7423 I Adreno-EGL: Remote Branch: 
09-06 19:04:40.114  7405  7423 I Adreno-EGL: Local Patches: 
09-06 19:04:40.114  7405  7423 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:04:40.121  7465  7465 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:04:40.172  1032  1531 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 19:04:40.288  1032  1688 D WifiServiceImplEx: setWifiEnabled: false pid=6898, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:04:40.288  1032  1688 D WifiService: setWifiEnabled: false pid=6898, uid=10118
09-06 19:04:40.288  1032  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:04:40.312  1032  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:40.313  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-06 19:04:40.314  1032  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:40.315  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:40.316  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:40.316  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:04:40.317  1032  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:40.318  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:04:40.318  1032  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:04:40.319  1032  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:04:40.319  1032  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:04:40.320  1032  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-06 19:04:40.321  1032  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:04:40.333  1032  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:04:40.335  1032  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.335  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.335  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:04:40.336  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:04:40.336  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:04:40.336  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:04:40.336  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:04:40.337  1032  7349 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.337   314   876 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:04:40.342  7405  7423 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:40.343  7405  7423 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:40.372  1032  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:40.372  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:40.373  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 19:04:40.373  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:40.373  1032  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:40.374  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:40.374  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:40.374  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:04:40.374  1032  1531 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:04:40.375  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-06 19:04:40.375  1032  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:04:40.375  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:40.376  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:40.376  1032  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.376  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:04:40.376  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.376  1032  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@353c4b51
09-06 19:04:40.376  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.377  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.377  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:04:40.377  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:04:40.378  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.380  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:40.380  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:40.382  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.382  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.382  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.382  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:04:40.383  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:04:40.383  1032  1545 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.383  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-06 19:04:40.383  1032  1546 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.385  1032  1522 D LGWifiP2pService: P2pDisablingState
09-06 19:04:40.385  1032  1522 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.387  1032  1522 D LGWifiP2pService: p2p socket connection lost
09-06 19:04:40.387  1032  1522 D LGWifiP2pService: P2pDisabledState
,09-06 19:04:40.387  1032  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:04:40.387  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:04:40.387  7252  7252 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:04:40.387  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:04:40.387  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:04:40.388  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:04:40.388  1032  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.388  1032  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:40.392  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:04:40.392  1929  1929 D WfdsService: WifiP2pState is changed : false
09-06 19:04:40.395  1929  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:04:40.395  1929  2284 D WfdsService: Set the WFDS Monitor: false
09-06 19:04:40.396  1929  2284 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:04:40.396  1929  2284 D WfdsService: STATE : WfdsDisabledState - enter
09-06 19:04:40.396  1929  7283 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:04:40.396  1929  7283 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:04:40.396  1929  7283 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:04:40.396  1929  7283 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:04:40.396  1929  2289 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:04:40.397  1929  2284 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 19:04:40.410   314   876 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:04:40.411  1032  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:04:40.411  1032  1531 D DSQN    : disableDataServiceNotify
09-06 19:04:40.411  1032  1531 D DSQN    : stop dsqn bin
09-06 19:04:40.413  1032  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 19:04:40.414  1032  1523 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:04:40.414  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:40.414  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:40.414  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:04:40.415  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:04:40.415  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.415  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.415  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:04:40.418  1032  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 19:04:40.419  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:40.419  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:40.419  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:04:40.419  1032  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:40.419  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:40.420  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 19:04:40.421  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:04:40.421  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:40.421  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 19:04:40.426  1032  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:04:40.426  1591  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:04:40.426  1032  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:04:40.426  1032  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:04:40.426  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:04:40.426  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.427  1032  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:40.427  1032  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:04:40.427  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:04:40.428  1032  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:40.428  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.428  1032  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:40.428  1032  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:40.428  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:04:40.428  1032  1531 D NetworkManagementService: Removing idletimer
09-06 19:04:40.428  1032  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.428  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:04:40.428  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:04:40.428  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:04:40.429  1032  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:40.429  1032  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:40.430  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:40.430  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:04:40.430  1032  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:04:40.430  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:04:40.430  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:04:40.430  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:04:40.430  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:04:40.433  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:40.433  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:40.433  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:40.433  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:40.433  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:04:40.434  6568  7035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:04:40.435  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:40.435  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:40.435  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:40.435  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:04:40.453  2172  2172 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:40.466  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:04:40.466  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:40.466  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:04:40.466  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:04:40.472  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:04:40.476  1591  1591 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:04:40.476  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.477  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fa7b83b
09-06 19:04:40.477  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:04:40.477  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.477  7186  7186 D AppUp4:CustFacade: isPhone : true
09-06 19:04:40.477  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:04:40.478  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:04:40.481  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:40.481  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:04:40.482  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:40.484  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:04:40.492  7223  7223 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:04:40.497  4301  7502 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:04:40.499  1591  1591 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:04:40.500  4301  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:40.500  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.500  4301  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:04:40.501  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.506  7252  7252 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:04:40.506  7252  7252 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:04:40.506  7252  7252 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-4\x00 that cannot receive messages
09-06 19:04:40.506  1032  7258 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:04:40.506  1032  7258 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:04:40.513  7223  7505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:04:40.516  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:04:40.516  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:40.518  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:04:40.518  7112  7508 W FormManager: Network not available. Please check & try again.
09-06 19:04:40.519  7262  7262 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:04:40.519  7262  7262 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:04:40.519  7405  7423 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:04:40.519  7405  7423 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:04:40.519  7405  7423 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:04:40.519  7405  7423 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:04:40.519  7405  7423 I Adreno-EGL: Remote Branch: 
09-06 19:04:40.519  7405  7423 I Adreno-EGL: Local Patches: 
09-06 19:04:40.519  7405  7423 I Adreno-EGL: Reconstruct Branch: 
09-06 19:04:40.528  7326  7326 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:40
09-06 19:04:40.529  7112  7509 V FormManager: Network unavailable.
,09-06 19:04:40.532  7326  7326 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:04:40.532  7326  7326 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:04:40.533  7326  7326 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:04:40.533  7112  7509 V FormManager: Network unavailable.
09-06 19:04:40.533  7326  7326 D WeatherAncestor: connectivity changed - connection : true
09-06 19:04:40.533  7326  7326 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fd024b1
09-06 19:04:40.533  7326  7326 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:04:40.533  7326  7326 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:04:40.534  7326  7326 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:04:40.534  7326  7326 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:04:40.534  7326  7326 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:40
09-06 19:04:40.542  1032  7349 D DhcpStateMachine: StoppedState
09-06 19:04:40.542  1032  7349 D DhcpStateMachine: StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:04:40.543  1032  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:04:40.543  1032  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 19:04:40.544  7252  7252 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:04:40.545  7252  7252 W wpa_supplicant: USIM:  scard_deinit function
09-06 19:04:40.545  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 19:04:40.545  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:04:40.545  1032  7258 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:04:40.546  1032  1103 D Tethering: InitialState.processMessage what=4
09-06 19:04:40.546  1032  7258 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:04:40.547  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:40.547  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:40.547  1032  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185260
09-06 19:04:40.547  1032  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185260
09-06 19:04:40.547  1032  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=185260  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:04:40.548  1032  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:04:40.548  1032  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=185261  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:04:40.549  1032  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:40.549  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:40.554  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-06 19:04:40.555  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:04:40.555  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:04:40.555  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:04:40.556   314  7514 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:04:40.556  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:04:40.556  1032  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:04:40.556  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:04:40.556  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:04:40.556  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:04:40.556  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:04:40.556  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:04:40.557  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-06 19:04:40.560  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:40.562  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:04:40.565  7112  7516 W FormManager: Network not available. Please check & try again.
,09-06 19:04:40.576  7112  7517 V FormManager: Network unavailable.
09-06 19:04:40.577  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:04:40.581  7112  7517 V FormManager: Network unavailable.
09-06 19:04:40.584  7405  7423 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:04:40.584  7405  7423 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:04:40.584  7405  7423 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:04:40.584  7405  7423 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:04:40.584  7405  7423 I Adreno-EGL: Remote Branch: 
09-06 19:04:40.584  7405  7423 I Adreno-EGL: Local Patches: 
09-06 19:04:40.584  7405  7423 I Adreno-EGL: Reconstruct Branch: 
09-06 19:04:40.596  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:40.599  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:04:40.603  7112  7519 W FormManager: Network not available. Please check & try again.
09-06 19:04:40.605  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:40.607  7112  7520 V FormManager: Network unavailable.
09-06 19:04:40.608  7112  7520 V FormManager: Network unavailable.
09-06 19:04:40.614  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-06 19:04:40.614  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:04:40.615  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:40.616  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:40.618  4301  7521 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:04:40.619  4301  7522 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:04:40.619  4301  7522 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:04:40.644  1032  1964 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7523 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-06 19:04:40.654   314  7541 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-06 19:04:40.654  1804  7358 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-06 19:04:40.654  1032  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:04:40.659  1804  7358 I CheckinService: active receiver: disabled
09-06 19:04:40.666  7252  7252 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:04:40.668  1032  7258 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:04:40.668  1032  7258 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 19:04:40.668  1032  7258 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-06 19:04:40.669  1032  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
09-06 19:04:40.710  7523  7523 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:04:40.710  7523  7523 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 19:04:40.717  7523  7523 V [BNRBootReceiver]: Boot Receiver Return
,09-06 19:04:40.718  7523  7523 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:04:40.720  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:40.727  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:40.735  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:40.750  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:04:40.751  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:40.752  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:04:40.759  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:40.771  1032  1523 D WifiOffDelayIfNotUsed: stopMonitoring
,09-06 19:04:40.772  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:40.772  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:40.772  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:04:40.772  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:40.774  1929  1929 D WfdsService: Supplicant Connection state is changed : false
09-06 19:04:40.774  1929  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:04:40.774  1929  2284 D WfdsService: Set the WFDS Monitor: false
09-06 19:04:40.774  1929  2284 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:04:40.777  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:40.777  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:04:40.780  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 19:04:40.781  1032  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:04:40.781  1032  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 19:04:40.782  2494  2494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:40.782  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:40.782  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:40.784  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:40.797  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:40.807  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:40.808  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:40.810  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:04:40.814  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-06 19:04:40.828  6996  6996 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 19:04:40.832  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:40.839  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:40.848  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:40.857  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:04:40.858  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:40.858  7066  7066 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:04:40.865  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:40.875  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:40.884  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:40.898  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:40.899  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:40.899  7066  7066 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:04:40.904  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:40.916  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:40.927  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:40.940  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:40.941  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:40.941  7066  7066 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:40.949  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:40.958  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:40.966  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:40.974  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:40.974  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:40.975  7066  7066 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:40.980  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:40.993  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:41.003  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:04:41.013  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:41.014  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:41.015  7066  7066 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:41.030  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:41.049  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:41.060  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:41.072  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:41.073  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:41.080  7066  7066 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:41.092  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:41.108  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:41.117  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:04:41.127  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:41.127  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:41.128  7066  7066 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:41.134  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:41.142  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:04:41.157  1032  1530 D WifiService: New client listening to asynchronous messages
,09-06 19:04:41.157  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:41.162  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:04:41.178  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:04:41.190  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:41.191  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:41.193  7066  7066 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:04:41.194  7066  7066 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:04:41.195  7066  7066 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:04:41.206  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:41.214  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 19:04:41.217  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:41.224  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:41.234  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:41.247  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:41.248  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:41.249  7066  7066 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-06 19:04:41.251  7066  7066 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:04:41.251  7066  7066 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:04:41.256  1032  2015 I ActivityManager: Killing 7016:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-06 19:04:41.295  6786  7177 D UEI.SmartControl: Internal timer expired: 2
09-06 19:04:41.295  6786  7177 D UEI.SmartControl: unbind internal service
,09-06 19:04:41.317  1032  1856 W libprocessgroup: failed to open /acct/uid_10037/pid_7016/cgroup.procs: No such file or directory
,09-06 19:04:41.326  2172  2172 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-06 19:04:41.341  2172  2172 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-06 19:04:41.342  2172  2172 D c       : Getting all permits...
09-06 19:04:41.342  2172  2172 D a       : Opening database...
09-06 19:04:41.352  2172  2172 D a       : Opening database auth.proximity.permit_store...
09-06 19:04:41.353  2172  2172 D a       : Closing database...
09-06 19:04:41.363  6786  7171 D serial_port: close(fd = 24)
,09-06 19:04:41.369  6786  7171 I UEI.SmartControl: Serial port is closed.
09-06 19:04:41.375  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:41.383  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:04:41.383  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:41.384  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:04:41.394  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:41.405  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:41.421  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:41.421  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:41.424  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:04:41.433  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:41.443  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:04:41.443  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:41.443  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:04:41.455  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:41.465  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:41.478  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:41.479  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:41.482  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:04:41.489  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:41.495  7036  7036 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-06 19:04:41.495  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:41.495  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:41.503  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:41.512  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:41.526  7066  7066 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:04:41.527  7066  7066 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:41.530  7066  7066 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:04:41.545  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:04:41.551  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:04:41.562  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:41.564  7112  7550 W FormManager: Network not available. Please check & try again.
09-06 19:04:41.570  7112  7551 V FormManager: Network unavailable.
,09-06 19:04:41.581  7112  7551 V FormManager: Network unavailable.
09-06 19:04:41.587  2172  2172 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-06 19:04:41.608  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:04:41.609  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:04:41.611  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:41.616  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:41.621  4301  7552 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:04:41.623  4301  7553 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:04:41.623  4301  7553 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:04:41.629  7036  7036 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,09-06 19:04:41.629  7036  7036 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:04:41.629  7036  7036 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:41.634  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:04:41.637  7112  7555 W FormManager: Network not available. Please check & try again.
09-06 19:04:41.644  7112  7556 V FormManager: Network unavailable.
,09-06 19:04:41.649  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:41.660  7112  7556 V FormManager: Network unavailable.
,09-06 19:04:42.077  1032  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:7699549] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:04:42.079  1032  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:7699551] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 19:04:42.163  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:42.181  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:42.184  1032  1103 D Tethering: MasterInitialState.processMessage what=3
09-06 19:04:42.189  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:42.190  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:42.197  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 19:04:42.202  6568  7035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:04:42.214  5833  5833 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:04:42.236  2172  2172 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:42.265  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:04:42.265  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:42.265  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:04:42.265  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 19:04:42.272  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:04:42.276  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fa7b83b
09-06 19:04:42.276  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:04:42.276  7186  7186 D AppUp4:CustFacade: isPhone : true
09-06 19:04:42.276  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:04:42.277  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:04:42.283  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:42.284  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:04:42.289  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:42.293  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:42.306  7223  7223 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:04:42.331  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:04:42.342  4301  7570 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:04:42.349  4301  7585 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:42.349  4301  7585 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:04:42.360  7223  7583 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:42.361  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:04:42.361  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:42.362  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = true
09-06 19:04:42.362  3488  3488 D PhoneState: setPdpRejectCasuse : false
,09-06 19:04:42.369  7112  7588 W FormManager: Network not available. Please check & try again.
09-06 19:04:42.372  7262  7262 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:04:42.372  7262  7262 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:04:42.375  7112  7589 V FormManager: Network unavailable.
,09-06 19:04:42.380  7112  7589 V FormManager: Network unavailable.
09-06 19:04:42.387  7326  7326 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:42
09-06 19:04:42.388  7326  7326 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:04:42.388  7326  7326 D Weather.Utils: 2 : All the weather widget is gone.
,09-06 19:04:42.390  7326  7326 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-06 19:04:42.390  7326  7326 D WeatherAncestor: connectivity changed - connection : true
09-06 19:04:42.390  7326  7326 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fd024b1
09-06 19:04:42.391  7326  7326 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:04:42.391  7326  7326 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:04:42.391  7326  7326 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:04:42.391  7326  7326 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:04:42.391  7326  7326 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:42
09-06 19:04:43.313  1032  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:43.314  1032  1564 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 19:04:43.346  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:43.346  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:43.346  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:04:43.347  1032  1103 D BluetoothManagerService: Message: 1
09-06 19:04:43.347  1032  1103 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-06 19:04:43.379  1032  1103 D BluetoothManagerService: Message: 20
09-06 19:04:43.379  1032  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2203e995:true
,09-06 19:04:43.384  7138  7138 D BluetoothAdapterState: make
09-06 19:04:43.389  7138  7138 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:04:43.389  7138  7138 I bluedroid-qcom: init
09-06 19:04:43.391  7138  7604 I BluetoothAdapterState: Entering OffState
09-06 19:04:43.391  7138  7138 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:04:43.391  7138  7138 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:04:43.391  7138  7138 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:04:43.391  7138  7138 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:04:43.391  7138  7138 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:04:43.393  7138  7138 I bluedroid-qcom: get_profile_interface socket
09-06 19:04:43.393  7138  7138 I bluedroid-qcom: get_profile_interface map_client
,09-06 19:04:43.399  7138  7608 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:04:43.401  7138  7608 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:04:43.390  7607  7607 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:43.390  7607  7607 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:43.410  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:04:43.411  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,09-06 19:04:43.418  7607  7607 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:04:43.418  7607  7607 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:04:43.418  7607  7607 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-06 19:04:43.420  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 19:04:43.420  1032  1103 D BluetoothManagerService: Message: 40
09-06 19:04:43.420  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 19:04:43.421  7138  7154 I bluedroid-qcom: config_hci_snoop_log
09-06 19:04:43.423  1032  1103 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:04:43.423  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:04:43.424  7607  7607 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-06 19:04:43.428  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.431  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.437  7607  7607 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:04:43.437  7607  7607 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-06 19:04:43.446  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:43.447  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:43.460  1032  1103 D Tethering: MasterInitialState.processMessage what=3
09-06 19:04:43.460  1032  1103 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:04:43.463  7138  7604 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 19:04:43.464  7138  7608 D BluetoothAdapterProperties: Name is: G3
09-06 19:04:43.469  7138  7604 D BluetoothAdapterProperties: Setting state to 11
09-06 19:04:43.469  7138  7604 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:04:43.471  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:43.471  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:04:43.471  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 19:04:43.473  7138  7604 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 19:04:43.478  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:04:43.479  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:43.482  6568  7035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:04:43.502  7138  7604 D BluetoothBondStateMachine: make
,09-06 19:04:43.508  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:43.510  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:43.511  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 19:04:43.512  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:43.514  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:43.516  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:43.520  7138  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
,09-06 19:04:43.520  7138  7619 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 19:04:43.520  7138  7604 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:04:43.520  7138  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.521  7138  7604 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 19:04:43.521  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.521  7138  7604 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,09-06 19:04:43.523  7138  7138 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:04:43.524  5833  5833 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:04:43.524  7138  7138 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:43.525  7138  7138 V BluetoothPbapReceiver: ***********state = 11
09-06 19:04:43.528  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:43.530  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:04:43.532  7138  7604 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:04:43.535  5833  5833 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:04:43.539  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:43.540  7138  7138 D HeadsetService: Received start request. Starting profile...
09-06 19:04:43.541  7138  7138 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:04:43.541  7138  7138 D LGBluetoothHfpAdapter: Version 1.6
09-06 19:04:43.541  7138  7604 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:43.545  7138  7138 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:04:43.546  7138  7138 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:04:43.547  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:43.547  7138  7138 D HeadsetStateMachine: make
,09-06 19:04:43.574  1032  1928 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7629 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-06 19:04:43.582  7138  7604 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:43.589  7138  7604 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:43.590  2172  2172 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.591  7138  7138 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:43.591  7138  7138 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:43.598  7138  7138 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:04:43.598  7138  7138 I bluedroid-qcom: get_profile_interface handsfree
09-06 19:04:43.598  7138  7604 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:43.600  7138  7138 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 19:04:43.600   325  1368 V AudioPolicyService: registerClient() client 0xb558aae0, uid 1002
09-06 19:04:43.601   325  2142 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:04:43.601   325  2142 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:04:43.601   325  2142 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:04:43.601  7138  7138 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:04:43.601   325  2146 V AudioFlinger: registerClient() client 0xb1433118, pid 7138
09-06 19:04:43.602   325  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:43.602   325  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:43.602  1591  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:43.602  1839  2408 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:43.602  1839  2408 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:43.602  3488  3503 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:43.602  3488  3503 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:43.602   325  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:43.602   325  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:43.602  3488  3504 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:43.602  1591  1610 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:43.602  3488  3504 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:43.602  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:43.602  1591  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:43.602  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:43.603  1591  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:43.603  1032  1928 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:43.603  1032  1928 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:43.603  1032  1928 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:43.603  1032  1928 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:43.604  7138  7138 V ToneGenerator: Create Track: 0xb4928080
,09-06 19:04:43.604  7138  7138 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:04:43.604  7138  7138 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:04:43.604  7138  7154 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:43.604   325   325 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:04:43.604   325   325 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:04:43.604  7138  7154 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:04:43.604   325   325 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:04:43.604   325   325 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:04:43.604  7138  7154 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:43.604  7138  7154 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:04:43.604   325  1368 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:04:43.604   325  2142 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:04:43.604   325  2142 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:04:43.604   325  2142 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:04:43.604   325  2142 V AudioPolicyManagerEx: getOutput() returns output 2
,09-06 19:04:43.604  7138  7138 V AudioSystem: getLatency() output 2, latency 50
09-06 19:04:43.604  7138  7138 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:04:43.604  7138  7138 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:04:43.605   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:04:43.605   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:04:43.605   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,09-06 19:04:43.605   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:04:43.605   325  2146 V AudioFlinger: createTrack() lSessionId: 22
09-06 19:04:43.607  7138  7138 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:04:43.607   325  1366 V AudioFlinger: acquiring 22 from 7138, for 7138
09-06 19:04:43.607   325  1366 V AudioFlinger:  added new entry for 22
09-06 19:04:43.607  7138  7138 V ToneGenerator: ToneGenerator INIT OK, time: 188331
09-06 19:04:43.607  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.608  7138  7628 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:04:43.608  7138  7628 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:04:43.608  7138  7628 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:04:43.608  7138  7628 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:04:43.608   325   325 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7138
09-06 19:04:43.609  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.610   325   325 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:04:43.610   325   325 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:04:43.610   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 19:04:43.610   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 19:04:43.610   325   325 V voice   : voice_set_parameters: exit with code(0)
09-06 19:04:43.610   325   325 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:04:43.610   325   325 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 19:04:43.610   325   325 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:04:43.610   325   325 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:04:43.610   325   325 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:04:43.610   325   325 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:04:43.611  7138  7138 D A2dpService: Received start request. Starting profile...
09-06 19:04:43.611  7138  7628 V ToneGenerator: ToneGenerator destructor
09-06 19:04:43.611  7138  7628 V ToneGenerator: stopTone
09-06 19:04:43.611  7138  7628 V ToneGenerator: Delete Track: 0xb4928080
09-06 19:04:43.611  7138  7138 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:04:43.612  7138  7628 V AudioTrack: ~AudioTrack, releasing session id from 7138 on behalf of 7138
09-06 19:04:43.612  7138  7138 V Avrcp   : make
09-06 19:04:43.612   325  1368 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 19:04:43.612   325  1368 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:04:43.612   325  1368 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:04:43.612   325  1368 V AudioFlinger: removeClient_l() pid 7138, calling pid 325
09-06 19:04:43.612  1032  2039 W Process : Unable to open /proc/7645/status
09-06 19:04:43.612   325  2142 V AudioFlinger: releasing 22 from 7138 for 7138
09-06 19:04:43.612   325  2142 V AudioFlinger:  decremented refcount to 0
09-06 19:04:43.612   325  2142 V AudioFlinger: purging stale effects
09-06 19:04:43.612   325  1111 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:04:43.612   325  1111 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:04:43.612  7138  7138 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:04:43.612   325  1111 V AudioPolicyManager: releaseOutput() 2
09-06 19:04:43.612   325  1111 V AudioPolicyService: AudioCommandThread() going to sleep,
09-06 19:04:43.612  7138  7138 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:04:43.614  7138  7604 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:43.617  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:04:43.617  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.619  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:04:43.619  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:04:43.621  7138  7138 V AudioManager: registerRemoteController: size of Media player list: 0
,09-06 19:04:43.623  7138  7138 E AudioManager: No RCC entry present to update
09-06 19:04:43.623  7138  7138 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:04:43.623  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:04:43.624  7138  7604 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:43.626  7138  7138 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 19:04:43.626  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:04:43.626  7138  7138 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-06 19:04:43.635  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fa7b83b
09-06 19:04:43.635  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:04:43.635  7186  7186 D AppUp4:CustFacade: isPhone : true
09-06 19:04:43.635  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:04:43.637  7138  7604 V LGMDMManager: Create singleton instance
09-06 19:04:43.638  7138  7604 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:04:43.645  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:04:43.645  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:04:43.688  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.688  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:04:43.694  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:43.705  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:04:43.719  7629  7629 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:04:43.719  7629  7629 W LG Account v2.2: No ProfileInfo entries
09-06 19:04:43.719  7629  7629 I LG Account v2.2: isEnabled: false
09-06 19:04:43.719  7629  7629 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:04:43.719  7629  7629 I Feature : [Lifetracker]Country: EU
09-06 19:04:43.719  7629  7629 I Feature : [Lifetracker]Operator: OPEN
09-06 19:04:43.719  7629  7629 I Feature : [Lifetracker]Ranking support: false
09-06 19:04:43.720  7629  7629 I Feature : [Lifetracker]Comfort support: false
09-06 19:04:43.720  7629  7629 I Feature : [Lifetracker]Accessory: true
09-06 19:04:43.720  7629  7629 I Feature : [Lifetracker]Health device: true
09-06 19:04:43.720  7629  7629 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:04:43.720  7629  7629 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:04:43.720  7629  7629 I Feature : [Lifetracker]Device Number: 3
09-06 19:04:43.724  7223  7223 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:04:43.728  4301  7652 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:04:43.732  4301  7653 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.732  4301  7653 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:04:43.739  6996  6996 D BluetoothPermissionRequest: onReceive
,09-06 19:04:43.742  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:43.760  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:04:43.760  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.760  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 19:04:43.767  7262  7262 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:04:43.767  7262  7262 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:04:43.767  1032  1047 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:04:43.767  1032  1047 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:04:43.768  7112  7657 W FormManager: Network not available. Please check & try again.
09-06 19:04:43.777  7112  7658 V FormManager: Network unavailable.
,09-06 19:04:43.780  7326  7326 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:43
,09-06 19:04:43.781  7223  7655 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:43.782  7112  7658 V FormManager: Network unavailable.
09-06 19:04:43.783  7326  7326 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:04:43.783  7326  7326 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:04:43.784  7326  7326 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:04:43.784  7326  7326 D WeatherAncestor: connectivity changed - connection : true
09-06 19:04:43.784  7326  7326 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fd024b1
09-06 19:04:43.784  7326  7326 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:04:43.784  7326  7326 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:04:43.784  7326  7326 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:04:43.784  7326  7326 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:04:43.784  7326  7326 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:43
09-06 19:04:43.803  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 19:04:43.804  6568  7035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:04:43.819  2172  2172 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:04:43.827  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-06 19:04:43.827  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.827  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:04:43.827  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:04:43.828  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:04:43.831  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fa7b83b
09-06 19:04:43.831  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:04:43.831  7186  7186 D AppUp4:CustFacade: isPhone : true
09-06 19:04:43.831  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
,09-06 19:04:43.831  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:04:43.834  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.834  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:04:43.836  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:43.838  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:43.843  7223  7223 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:04:43.843  4301  7659 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:04:43.846  4301  7660 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.846  4301  7660 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:04:43.869  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:04:43.869  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:43.870  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 19:04:43.870  1032  2039 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-06 19:04:43.872  7223  7661 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:43.874  7112  7664 W FormManager: Network not available. Please check & try again.
09-06 19:04:43.875  7262  7262 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:04:43.875  7262  7262 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:04:43.880  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-06 19:04:43.882  7326  7326 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:43
09-06 19:04:43.882  7112  7665 V FormManager: Network unavailable.
09-06 19:04:43.884  7112  7665 V FormManager: Network unavailable.
09-06 19:04:43.885  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:04:43.885  7326  7326 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:04:43.885  7326  7326 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:04:43.886  7326  7326 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:04:43.886  7326  7326 D WeatherAncestor: connectivity changed - connection : true
09-06 19:04:43.886  7326  7326 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fd024b1
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:04:43.886  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:04:43.887  7326  7326 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:04:43.887  7326  7326 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:04:43.887  7326  7326 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:04:43.887  7326  7326 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:04:43.887  7326  7326 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:4:43
09-06 19:04:43.887  7138  7138 I BluetoothA2dpServiceJni: classInitNative
09-06 19:04:43.887  7138  7138 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:04:43.887  7138  7138 D A2dpStateMachine: make
09-06 19:04:43.891  7138  7138 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:04:43.892  7138  7667 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:04:43.894  7138  7138 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:04:43.894  7138  7138 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:04:43.895  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
,09-06 19:04:43.896  7138  7138 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:04:43.898  7138  7138 D HidService: Received start request. Starting profile...
09-06 19:04:43.898  7138  7138 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:04:43.898  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.898  7138  7138 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:04:43.899  7138  7666 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:04:43.900  7138  7138 D HealthService: Received start request. Starting profile...
09-06 19:04:43.901  7138  7138 I bluedroid-qcom: get_profile_interface health
09-06 19:04:43.901  7138  7138 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:04:43.901  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.901  7138  7138 D HeadsetStateMachine: Proxy object connected
09-06 19:04:43.902  7138  7138 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:04:43.902  7138  7138 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-06 19:04:43.905  7138  7138 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:04:43.906  7138  7138 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:04:43.907  7138  7138 D PanService: Received start request. Starting profile...
09-06 19:04:43.907  7138  7138 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:04:43.907  7138  7138 I bluedroid-qcom: get_profile_interface pan
09-06 19:04:43.912  7138  7138 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 19:04:43.912  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.913  7138  7138 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 19:04:43.913  7138  7628 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:04:43.913  7138  7628 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:04:43.913  7138  7628 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 19:04:43.918  7138  7138 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:04:43.918  7138  7138 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:04:43.918  7138  7138 D BtGatt.GattService: start()
09-06 19:04:43.919  7138  7138 I bluedroid-qcom: get_profile_interface gatt
09-06 19:04:43.919  7138  7138 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:04:43.923  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.925  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.925  7138  7138 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:04:43.926  7138  7138 V BluetoothMapService: BluetoothMapBinder()
09-06 19:04:43.927  7138  7138 D BluetoothMapService: Received start request. Starting profile...
09-06 19:04:43.927  7138  7138 D BluetoothMapService: start()
09-06 19:04:43.929  7138  7138 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-06 19:04:43.929  7138  7138 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:04:43.930  7138  7138 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:04:43.930  7138  7138 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 19:04:43.938  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:43.941  7138  7138 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:04:43.944  7138  7138 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:04:43.946  7138  7138 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:04:43.946  7138  7138 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 19:04:43.949  7138  7138 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:04:43.952  7138  7138 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 19:04:43.952  7138  7138 V BluetoothMapService: Handler(): got msg=1
,09-06 19:04:43.953  7138  7604 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:04:43.953  7138  7604 I bluedroid-qcom: enable
09-06 19:04:43.953  7138  7604 I bt_hci_bdroid: init
09-06 19:04:43.954  7138  7674 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:04:43.954  7138  7674 I bt-btu  : btu_task pending for preload complete event
09-06 19:04:43.954  7138  7138 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:43.955  7138  7604 I bt_vendor: bt-vendor : init
09-06 19:04:43.955  7138  7604 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:04:43.955  7138  7604 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:04:43.955  7138  7604 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:04:43.955  7138  7604 D bt_userial_mct: userial_init
09-06 19:04:43.955  7138  7604 D bt_hci_bdroid: set_power 1
09-06 19:04:43.955  7138  7604 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:04:43.955  7138  7604 I bt_vendor: Starting hciattach daemon
09-06 19:04:43.955  7138  7604 I bt_vendor: try to set true
09-06 19:04:43.956  7138  7138 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:43.956  7138  7138 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:43.956  7138  7138 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:43.956  7138  7138 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:43.956  7138  7138 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:04:43.950  7677  7677 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:43.950  7677  7677 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:43.975  7678  7678 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:04:44.047  7684  7684 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:04:44.059  7685  7685 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-06 19:04:44.079  7687  7687 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:04:44.096  7688  7688 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 19:04:44.115  7689  7689 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:04:44.127  7690  7690 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:04:44.155  7692  7692 I libmdmdetect: ESOC framework not supported
,09-06 19:04:44.156  7692  7692 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 19:04:44.162   314  7355 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-06 19:04:44.163   314  7355 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
,09-06 19:04:44.164   314  7355 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
09-06 19:04:44.166  1032  1101 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:04:44.166  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-06 19:04:44.166  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3s741ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:44.166  7692  7692 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 19:04:44.166  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3s741ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:44.167  7692  7692 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 19:04:44.167  1032  7347 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:04:44.167  7692  7692 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 19:04:44.167  7692  7692 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 19:04:44.167  7692  7692 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 19:04:44.167  7692  7692 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:04:44.167  7692  7692 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 19:04:44.213  7692  7693 E QC-QMI  : qmi_client [7692] 14: failed to locate client data
09-06 19:04:44.214   457   457 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 19:04:44.215   457   457 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-06 19:04:44.264  7700  7700 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 19:04:44.279  7701  7701 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:04:44.309  7138  7604 I bt_vendor: bluetooth satus is on
,09-06 19:04:44.309  7138  7604 D bt_hci_bdroid: preload
09-06 19:04:44.309  7138  7676 D bt_userial_mct: userial_open(port:0)
09-06 19:04:44.309  7138  7676 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:04:44.313  7138  7676 I bt_vendor: Done intiailizing UART
,09-06 19:04:44.314  7138  7676 I bt_vendor: Done intiailizing UART
09-06 19:04:44.314  7138  7676 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-06 19:04:44.314  7138  7676 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:04:44.314  7138  7674 I bt-btu  : btu_task received preload complete event
09-06 19:04:44.315  7138  7703 D bt_userial_mct: Entering userial_read_thread()
09-06 19:04:44.315  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:04:44.315  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 19:04:44.318  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:04:44.321  7138  7674 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:04:44.421  7138  7674 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-06 19:04:44.421  7138  7674 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0199061 
09-06 19:04:44.421  7138  7674 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0199061 
,09-06 19:04:44.442  7138  7608 E bt-btif : Calling BTA_HhEnable
09-06 19:04:44.442  7138  7608 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 19:04:44.442  7138  7608 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:04:44.443  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 19:04:44.443  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 19:04:44.443  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 19:04:44.443  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:04:44.443  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:04:44.444  7138  7608 D BluetoothAdapterProperties: Name is: G3
09-06 19:04:44.445  7138  7608 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:04:44.445  7138  7608 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:04:44.445  7138  7608 D bt_hci_bdroid: postload
09-06 19:04:44.445  7138  7676 D bt_hci_bdroid: Used up Tx Cmd credits
,09-06 19:04:44.446  7138  7674 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:04:44.447  7138  7676 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:04:44.447  7138  7608 D bte_conf: Device ID record 1 : primary
09-06 19:04:44.447  7138  7608 D bte_conf:   vendorId            = 00c4
09-06 19:04:44.447  7138  7608 D bte_conf:   vendorIdSource      = 0001
,09-06 19:04:44.447  7138  7608 D bte_conf:   product             = 13a1
09-06 19:04:44.447  7138  7608 D bte_conf:   version             = 1000
09-06 19:04:44.447  7138  7608 D bte_conf:   clientExecutableURL = 
09-06 19:04:44.447  7138  7608 D bte_conf:   serviceDescription  = 
09-06 19:04:44.447  7138  7608 D bte_conf:   documentationURL    = 
09-06 19:04:44.447  7138  7608 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:04:44.448  7138  7676 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:04:44.448  7138  7676 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:04:44.440  7705  7705 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:44.440  7705  7705 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:44.452  7138  7676 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:04:44.453  7138  7604 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:04:44.453  7138  7604 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:04:44.453  7138  7604 D BluetoothAdapterProperties: State =  11
09-06 19:04:44.454  7138  7604 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 19:04:44.454  7138  7604 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:04:44.454  7138  7604 D BluetoothAdapterProperties: Setting state to 12
09-06 19:04:44.454  7138  7604 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:04:44.455  7138  7703 E bt_mct  : hci lib postload completed
09-06 19:04:44.455  7138  7608 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:04:44.455  7138  7608 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:04:44.461  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:44.461  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:04:44.462  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-06 19:04:44.462  7138  7604 I BluetoothAdapterState: Entering On State
,09-06 19:04:44.465  7138  7674 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:44.465  7138  7674 W bt-smp  : Plain text(LSB ~ MSB) = a2 83 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:44.465  7138  7674 W bt-smp  : Encrypted text(LSB ~ MSB) = ed ed 2f 7f 80 07 d7 1a 39 67 25 93 e8 7c df 4e 
09-06 19:04:44.465  7138  7674 W bt-btm  : Stopping oneshot timer
09-06 19:04:44.466  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:04:44.469  7138  7604 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:04:44.469  7138  7604 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:04:44.469  7138  7604 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 19:04:44.470  7138  7604 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:04:44.472  7138  7608 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:04:44.472  7138  7608 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 19:04:44.477  1839  1839 D BluetoothHeadset: Proxy object connected
,09-06 19:04:44.480  1032  1103 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:04:44.482  1032  1032 D BluetoothHeadset: Proxy object connected
09-06 19:04:44.484  6996  7014 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:04:44.496  7138  7674 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:44.496  7138  7674 W bt-smp  : Plain text(LSB ~ MSB) = 4d bc 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:44.496  7138  7674 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a 53 d8 32 c0 93 25 e0 f5 0b 07 4b 5f fa b3 97 
09-06 19:04:44.496  7138  7674 W bt-btm  : Stopping oneshot timer
,09-06 19:04:44.502  1032  1103 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:04:44.508  1032  1032 D BluetoothA2dp: Proxy object connected
09-06 19:04:44.510  6996  6996 D BluetoothMap: Proxy object connected
09-06 19:04:44.510  6996  6996 D MapProfile: Bluetooth service connected
09-06 19:04:44.510  6996  6996 D BluetoothMap: getConnectedDevices()
,09-06 19:04:44.513  6996  7107 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:04:44.515  6996  7014 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:04:44.515  7138  7604 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 19:04:44.516  7138  7674 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:44.516  7138  7674 W bt-smp  : Plain text(LSB ~ MSB) = a6 51 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:44.516  7138  7674 W bt-smp  : Encrypted text(LSB ~ MSB) = ac de 05 8c f6 01 45 7c e1 d5 b9 51 5c ac 85 dd 
09-06 19:04:44.516  7138  7674 W bt-btm  : Stopping oneshot timer
09-06 19:04:44.516  6996  7014 D BluetoothPan: onBluetoothStateChange call bindService
09-06 19:04:44.521  1839  2443 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:04:44.525  7716  7716 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-06 19:04:44.528  7138  7674 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:44.528  7138  7674 W bt-smp  : Plain text(LSB ~ MSB) = c1 75 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:44.528  7138  7674 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 be 26 49 7f 91 fc 0c 27 06 ec 2a 49 eb 5e d0 
09-06 19:04:44.528  7138  7154 V BluetoothMapService: getConnectedDevices()
09-06 19:04:44.528  7138  7674 W bt-btm  : Stopping oneshot timer
09-06 19:04:44.531  1839  1839 D BluetoothHeadset: Proxy object connected
09-06 19:04:44.532  6996  7015 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:04:44.532  6996  6996 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:04:44.532  6996  6996 D PanProfile: Bluetooth service connected
09-06 19:04:44.534  1839  2408 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:04:44.535  6996  6996 D BluetoothInputDevice: Proxy object connected
09-06 19:04:44.535  6996  6996 D HidProfile: Bluetooth service connected
09-06 19:04:44.536  1839  1839 D BluetoothHeadset: Proxy object connected
09-06 19:04:44.537  1032  1103 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:04:44.537  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 19:04:44.538  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:04:44.538  1032  1103 D BluetoothManagerService: Message: 40
,09-06 19:04:44.538  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:04:44.545  7138  7674 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:44.545  7138  7674 W bt-smp  : Plain text(LSB ~ MSB) = 69 50 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:44.545  7138  7674 W bt-smp  : Encrypted text(LSB ~ MSB) = 9a 0b 04 f4 4f 86 dd e2 af a2 41 57 b4 f1 d0 2e 
09-06 19:04:44.545  7138  7674 W bt-btm  : Stopping oneshot timer
09-06 19:04:44.546  7361  7396 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-06 19:04:44.556  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:04:44.557  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,09-06 19:04:44.560  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.560  1929  2090 D LGBluetoothAPIService: Message: 1
09-06 19:04:44.560  1929  2090 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:04:44.561  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:44.562  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:44.564  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:44.570  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:04:44.572  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:44.574  6898  6898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:04:44.577  7138  7138 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.577  7138  7138 D BluetoothMapService: STATE_ON
09-06 19:04:44.577  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:44.577  1929  2090 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-06 19:04:44.578  6996  6996 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 19:04:44.579  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:44.579  7138  7138 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 19:04:44.579  7138  7138 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 19:04:44.580  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 19:04:44.580  1929  2090 D LGBluetoothAPIService: Message: 100
09-06 19:04:44.580  1929  2090 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:04:44.580  7138  7138 V BluetoothMapService: Handler(): got msg=1
09-06 19:04:44.581  7138  7138 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:04:44.581  1032  1103 D BluetoothManagerService: Message: 30
,09-06 19:04:44.583  7138  7726 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:04:44.583  7138  7726 D BluetoothMapMasInstance:   masId = 00
09-06 19:04:44.583  7138  7726 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:04:44.583  7138  7726 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:04:44.583  7138  7726 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 19:04:44.586  1032  1688 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:44.586  6996  6996 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-06 19:04:44.587  7138  7726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:44.589  7138  7726 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:04:44.589  7138  7726 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:04:44.589  7138  7608 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:04:44.589  7138  7726 D BluetoothMapMasInstance: Accepting socket connection...
09-06 19:04:44.589  7138  7608 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:04:44.590  1032  1103 D BluetoothManagerService: Message: 30
09-06 19:04:44.592  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:44.595  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:44.600  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 19:04:44.600  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:44.601  7138  7138 V BluetoothPbapService: Pbap Service onCreate
09-06 19:04:44.601  7138  7138 V BluetoothPbapService: Starting PBAP service
09-06 19:04:44.601  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:04:44.602  7138  7138 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:04:44.602  7138  7138 V BluetoothPbapService: Pbap Service onBind
09-06 19:04:44.604  7138  7138 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.604  7138  7138 V BluetoothPbapService: state: 12
09-06 19:04:44.604  7138  7138 V BluetoothPbapService: Handler(): got msg=1
09-06 19:04:44.605  7138  7138 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:04:44.606  6996  6996 D BluetoothA2dp: Proxy object connected
09-06 19:04:44.606  7138  7138 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:04:44.606  7138  7138 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.606  7138  7727 V BluetoothPbapService: Pbap Service initSocket
09-06 19:04:44.606  7138  7138 V BluetoothPbapReceiver: ***********state = 12
09-06 19:04:44.607  6996  6996 D A2dpProfile: Bluetooth service connected
09-06 19:04:44.607  1032  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:04:44.610  7138  7727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:44.611  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:04:44.612  2172  2172 D c       : Getting all permits...
09-06 19:04:44.612  2172  2172 D a       : Opening database...
09-06 19:04:44.613  7138  7727 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 19:04:44.613  7138  7727 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:04:44.613  7138  7727 V BluetoothPbapService: Accepting socket connection...
09-06 19:04:44.613  6996  6996 D BluetoothHeadset: Proxy object connected
09-06 19:04:44.614  6996  6996 D HeadsetProfile: Bluetooth service connected
09-06 19:04:44.616  2172  2172 D a       : Opening database auth.proximity.permit_store...
09-06 19:04:44.617  2172  2172 D a       : Closing database...
09-06 19:04:44.626  6996  6996 D DockEventReceiver: finishStartingService: stopping service
09-06 19:04:44.627  6996  6996 D BluetoothPbap: Proxy object connected
,09-06 19:04:44.628  6996  6996 D PbapServerProfile: Bluetooth service connected
,09-06 19:04:44.633  6996  6996 D BluetoothPermissionRequest: onReceive
09-06 19:04:44.635  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:04:44.637  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:44.640  7138  7138 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-06 19:04:44.642  7138  7138 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:04:44.649  7138  7138 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-06 19:04:44.690  7138  7138 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:04:44.690  7138  7138 V BtOppService: onCreate
,09-06 19:04:44.696  7138  7138 V BluetoothOppNotification: send message
09-06 19:04:44.700  7138  7138 V BtOppService: Starting RfcommListener
09-06 19:04:44.709  7138  7138 D BluetoothOppPreference: Dumping Names:  
09-06 19:04:44.709  7138  7138 D BluetoothOppPreference: {}
09-06 19:04:44.709  7138  7138 D BluetoothOppPreference: Dumping Channels:  
09-06 19:04:44.709  7138  7138 D BluetoothOppPreference: {}
09-06 19:04:44.710  7138  7138 V BtOppService: onStartCommand
,09-06 19:04:44.715  7138  7735 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:04:44.715  7138  7138 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.715  7138  7138 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:04:44.720  7138  7138 V BluetoothOppNotification: new notify threadi!
09-06 19:04:44.721  7138  7138 V BluetoothOppNotification: send delay message
09-06 19:04:44.722  7138  7138 V BtOppService: start RfcommListener
09-06 19:04:44.725  7138  7138 V BtOppService: RfcommListener started
,09-06 19:04:44.731  7138  7737 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 19:04:44.731  1032  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:44.732  7138  7737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:44.734  7138  7737 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-06 19:04:44.734  7138  7732 V BtOppService: Deleted complete outbound shares, number =  0
09-06 19:04:44.734  7138  7737 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:04:44.734  7138  7737 I BtOppRfcommListener: Accept thread started.
09-06 19:04:44.735  7138  7737 V BtOppRfcommListener: Accepting connection...
,09-06 19:04:44.736  7138  7735 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:04:44.737  7138  7732 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 19:04:44.737  7138  7732 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:04:44.736  7138  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:04:44.740  7138  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e1a3b83 on behalf of 
09-06 19:04:44.740  7138  7732 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d1d6232 on behalf of 
09-06 19:04:44.741  7138  7736 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:04:44.742  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:44.742  7138  7138 V BluetoothFtpService: Ftp Service onCreate
09-06 19:04:44.742  7138  7138 I BluetoothFtpService: Ftp Service onCreate
09-06 19:04:44.742  7138  7138 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:04:44.743  7138  7138 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.743  7138  7138 V BluetoothFtpService: Starting Listening on sockets
09-06 19:04:44.743  7138  7138 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:44.743  7138  7138 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:44.743  7138  7138 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:44.743  7138  7138 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.743  7138  7138 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,09-06 19:04:44.744  7138  7138 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:04:44.747  7138  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:44.747  7138  7735 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13514d39 on behalf of 
09-06 19:04:44.748  7138  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@323b6f7e on behalf of 
09-06 19:04:44.749  7138  7736 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:04:44.750  7138  7138 V BtOppService: ContentObserver received notification
09-06 19:04:44.750  7138  7138 V BtOppService: ContentObserver received notification
09-06 19:04:44.750  7138  7138 V BluetoothFtpService: Handler(): got msg=1
09-06 19:04:44.750  7138  7735 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:04:44.750  7138  7735 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:04:44.751  7138  7138 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:04:44.751  7138  7138 V BluetoothFtpService: Ftp Service initSocket
09-06 19:04:44.752  7138  7735 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38bb0cdf on behalf of 
09-06 19:04:44.753  7138  7736 V BluetoothOppNotification: outbound notification was removed.
09-06 19:04:44.753  7138  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:44.753  7138  7735 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:04:44.754  7138  7735 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-06 19:04:44.756  1032  1856 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:44.757  7138  7138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:44.758  7138  7138 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-06 19:04:44.759  7138  7138 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:04:44.761  7138  7738 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 19:04:44.779  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:44.779  7138  7138 V BluetoothSapService: Sap Service onCreate
,09-06 19:04:44.782  7138  7138 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:44.782  7138  7138 V BluetoothSapService: state: 12
09-06 19:04:44.782  7138  7138 V BluetoothSapService: Starting SAP server process
09-06 19:04:44.770  7739  7739 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:44.785  7138  7138 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 19:04:44.780  7739  7739 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:44.786  7138  7740 V BluetoothSapService: Sap Service initRfcommSocket
09-06 19:04:44.787  1032  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:44.788  7138  7740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:44.792  7138  7740 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 19:04:44.792  7138  7740 V BluetoothSapService: Succeed to create listening socket 
09-06 19:04:44.792  7138  7740 V BluetoothSapService: Accepting socket connection...
,09-06 19:04:44.799  7739  7739 V BT_SAP  : Event pipe created
09-06 19:04:44.799  7739  7739 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:04:44.799  7739  7739 V BT_SAP  : created socket fd 6
,09-06 19:04:44.876  1032  2015 I art     : Explicit concurrent mark sweep GC freed 94418(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.593ms total 120.813ms
09-06 19:04:44.876  1032  1045 I art     : WaitForGcToComplete blocked for 119.668ms for cause HeapTrim
,09-06 19:04:44.878  7138  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@56d97fb on behalf of 
,09-06 19:04:44.879  7138  7736 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:04:44.881  7138  7736 V BluetoothOppNotification: inbound notification was removed.
09-06 19:04:44.882  7138  7736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:04:44.884  7138  7736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b1a6018 on behalf of 
09-06 19:04:45.389  1032  1522 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:45.389  1032  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:04:45.418  1032  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 19:04:45.427  1032  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-06 19:04:45.440  1032  1939 I ActivityManager: Killing 7523:com.lge.bnr/1000 (adj 15): empty #17
,09-06 19:04:45.472  1032  1688 W libprocessgroup: failed to open /acct/uid_1000/pid_7523/cgroup.procs: No such file or directory
,09-06 19:04:45.663  1032  1856 I ActivityManager: Killing 6786:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-06 19:04:45.694  7066  7066 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-06 19:04:45.694  7066  7066 W System.err: android.os.DeadObjectException
09-06 19:04:45.694  7066  7066 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:04:45.694  7066  7066 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:04:45.694  7066  7066 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 19:04:45.694  7066  7066 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 19:04:45.694  7066  7066 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:04:45.694  7066  7066 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:04:45.695  7066  7066 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:04:45.695  7066  7066 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:04:45.695  7066  7066 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:04:45.695  7066  7066 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:04:45.695  7066  7066 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:04:45.695  7066  7066 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:04:45.695  7066  7066 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:04:45.695  7066  7066 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 19:04:45.699  7066  7066 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 19:04:45.700  7066  7066 W System.err: android.os.DeadObjectException
09-06 19:04:45.700  7066  7066 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:04:45.700  7066  7066 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:04:45.700  7066  7066 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 19:04:45.701  7066  7066 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 19:04:45.701  7066  7066 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:04:45.701  7066  7066 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:04:45.701  7066  7066 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:04:45.701  7066  7066 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:04:45.701  7066  7066 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:04:45.701  7066  7066 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:04:45.701  7066  7066 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:04:45.701  7066  7066 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:04:45.701  7066  7066 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:04:45.701  7066  7066 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:04:45.701  7066  7066 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 19:04:45.702  7066  7066 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-06 19:04:45.723  7138  7138 V BluetoothOppNotification: new notify threadi!
09-06 19:04:45.723  7138  7138 V BluetoothOppNotification: send delay message
,09-06 19:04:45.728  7138  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:04:45.729  7138  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e126a71 on behalf of 
09-06 19:04:45.730  7138  7750 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:04:45.731  7138  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:45.732  7138  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2eabf056 on behalf of 
09-06 19:04:45.732  7138  7750 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:04:45.734  7138  7750 V BluetoothOppNotification: outbound notification was removed.
09-06 19:04:45.734  7138  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:45.735  7138  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3af3b8d7 on behalf of 
09-06 19:04:45.735  7138  7750 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-06 19:04:45.740  7138  7750 V BluetoothOppNotification: inbound notification was removed.
09-06 19:04:45.740  7138  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:04:45.741  7138  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@296165c4 on behalf of 
09-06 19:04:45.744  1032  1883 W libprocessgroup: failed to open /acct/uid_1000/pid_6786/cgroup.procs: No such file or directory
09-06 19:04:45.744  1032  1883 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-06 19:04:45.749  7066  7066 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 19:04:45.749  7066  7066 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-06 19:04:45.822  1032  1981 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7751 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:04:45.874  7066  7066 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:04:45.903  7751  7751 D UEI.SmartControl: Quickset Services start...
,09-06 19:04:45.910  7751  7751 I UEI.SmartControl: Manufacture = LGE
09-06 19:04:45.911  7751  7751 D UEI.SmartControl: Id = LGNevo
09-06 19:04:45.912  7751  7751 D UEI.SmartControl: File observer start...
09-06 19:04:45.913  7751  7751 E UEI.SmartControl: IR Port is disabled: false
09-06 19:04:45.913  7751  7751 D UEI.SmartControl: Starting file observer...
09-06 19:04:45.913  7751  7751 D UEI.SmartControl: Extracting JNI libs...
09-06 19:04:45.913  7751  7751 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-06 19:04:46.017  7751  7751 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-06 19:04:46.017  7751  7751 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-06 19:04:46.017  7751  7751 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-06 19:04:46.059  7751  7751 I UEI.SmartControl: --- Selecting new region: 6
,09-06 19:04:46.062  7751  7751 I UEI.SmartControl: Model = LG-D855
09-06 19:04:46.064  7751  7751 D UEI.SmartControl: QS Service created
,09-06 19:04:46.082  7751  7751 I UEI.SmartControl: Service initServices...
,09-06 19:04:46.088  7751  7751 D UEI.SmartControl: QS start get config
09-06 19:04:46.142  7751  7751 D UEI.SmartControl: Loading JNI Libs...
,09-06 19:04:46.357  1032  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:46.358  1032  1964 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18e31304 mBinding = false
,09-06 19:04:46.379  1032  1103 D BluetoothManagerService: Message: 2
09-06 19:04:46.381  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:46.382  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:46.382  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:04:46.383  1032  1103 D BluetoothManagerService: Sending off request.
09-06 19:04:46.384  7138  7724 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:04:46.384  7138  7604 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:04:46.384  7138  7604 D BluetoothAdapterProperties: Setting state to 13
09-06 19:04:46.384  7138  7604 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:04:46.385  7138  7604 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:04:46.385  7138  7604 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:04:46.387  7138  7608 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:04:46.388  7138  7604 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:04:46.389  7138  7604 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:04:46.389  7138  7726 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 19:04:46.390  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:04:46.390  7138  7674 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:46.391  7138  7674 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:46.392  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:04:46.392  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:04:46.392  7138  7727 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:46.392  7138  7674 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-06 19:04:46.395  7138  7738 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:46.395  7138  7737 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:46.398  7138  7740 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:04:46.403  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:46.403  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:46.404  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:46.404  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:04:46.407  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:46.407  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:46.408  6898  6898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:04:46.408  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:46.408  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:46.408  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:04:46.408  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:04:46.410  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.411  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:46.414  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-06 19:04:46.414  7138  7138 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.415  7138  7138 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:04:46.415  7138  7138 V BluetoothMapService: Handler(): got msg=4
09-06 19:04:46.415  7138  7138 D BluetoothMapService: MAP Service closeService in
09-06 19:04:46.415  7138  7138 D BluetoothMapMasInstance: MAP Service shutdown
09-06 19:04:46.415  7138  7138 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:04:46.415  7138  7138 V BluetoothMapService: MAP Service closeService out
09-06 19:04:46.416  7138  7138 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:04:46.416  7138  7138 I BtOppRfcommListener: stopping Accept Thread
09-06 19:04:46.416  7138  7138 V BtOppRfcommListener: close mBtServerSocket
,09-06 19:04:46.417  7138  7737 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:04:46.418  7138  7138 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:04:46.419  7138  7138 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:04:46.424  7138  7138 V BtOppService: onDestroy
09-06 19:04:46.426  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:46.427  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:46.428  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:04:46.429  7138  7138 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-06 19:04:46.438  7138  7138 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:04:46.438  7138  7138 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.438  7138  7138 V BluetoothPbapReceiver: ***********state = 13
09-06 19:04:46.440  7138  7138 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 19:04:46.441  6996  6996 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:04:46.444  7138  7138 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.444  7138  7138 V BluetoothPbapService: state: 13
09-06 19:04:46.444  7138  7138 V BluetoothPbapService: Pbap Service closeService in
09-06 19:04:46.447  7138  7138 V BluetoothPbapService: successfully stopped pbap service
09-06 19:04:46.447  7138  7138 V BluetoothPbapService: Pbap Service closeService out
09-06 19:04:46.448  7138  7138 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:04:46.448  7138  7138 V BluetoothPbapService: Pbap Service closeService in
09-06 19:04:46.448  7138  7138 V BluetoothPbapService: Pbap Service closeService out
09-06 19:04:46.448  7138  7138 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 19:04:46.449  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:04:46.452  6996  6996 D BluetoothPbap: Proxy object disconnected
09-06 19:04:46.452  6996  6996 D PbapServerProfile: Bluetooth service disconnected
09-06 19:04:46.459  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:04:46.463  6996  6996 D BluetoothPermissionRequest: onReceive
09-06 19:04:46.463  6996  6996 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:04:46.472  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:46.476  7138  7138 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 19:04:46.477  7138  7138 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-06 19:04:46.480  7138  7138 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 19:04:46.485  7138  7138 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.486  7138  7138 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:04:46.487  7138  7138 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:04:46.487  7138  7138 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.487  7138  7138 V BluetoothFtpService: Ftp Service closeService
09-06 19:04:46.487  7138  7138 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 19:04:46.490  7138  7138 V BluetoothFtpService: successfully stopped ftp service
09-06 19:04:46.490  7138  7138 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:46.490  7138  7138 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:46.490  7138  7138 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:46.490  7138  7138 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.490  7138  7138 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:04:46.490  7138  7138 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:04:46.491  7138  7138 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:04:46.491  7138  7138 V BluetoothFtpService: Ftp Service closeService
09-06 19:04:46.494  7138  7138 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:46.494  7138  7138 V BluetoothSapService: state: 13
09-06 19:04:46.495  7138  7138 V BluetoothSapService: Stopping SAP server process
,09-06 19:04:46.497  7138  7138 V BluetoothSapService: Sap Service closeSapService in
,09-06 19:04:46.497  7138  7138 V BluetoothSapService: Close listen Socket : 
09-06 19:04:46.497  7138  7138 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:04:46.497  7138  7138 V BluetoothSapService: Close sapd  Socket : 
09-06 19:04:46.499  7138  7138 V BluetoothSapService: Sap Service closeSapService out
09-06 19:04:46.499  7138  7138 V BluetoothSapService: Sap Service onDestroy
,09-06 19:04:46.499  7138  7138 V BluetoothSapService: Sap Service closeSapService in
09-06 19:04:46.499  7138  7138 V BluetoothSapService: Close listen Socket : 
09-06 19:04:46.499  7138  7138 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:04:46.499  7138  7138 V BluetoothSapService: Close sapd  Socket : 
09-06 19:04:46.501  7138  7138 V BluetoothSapService: Sap Service closeSapService out
09-06 19:04:46.504  7751  7751 I UEI.SmartControl: Supports setup maps: true
09-06 19:04:46.507  7751  7751 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:04:46.507  7751  7751 I UEI.SmartControl: QS version = v2.7.10.1_RC1,
09-06 19:04:46.507  7751  7751 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:04:46.507  7751  7751 I UEI.SmartControl: ### init IR Blaster...
,09-06 19:04:46.512  7751  7751 D serial_port: Configuring serial port
,09-06 19:04:46.515  7751  7751 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:04:46.515  7751  7751 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:04:46.515  7751  7751 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:04:46.515  7751  7751 I UEI.SmartControl: Get version...
09-06 19:04:46.531  7751  7795 D UEI.SmartControl: serial port data available: 21
,09-06 19:04:46.560  7751  7751 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:04:46.561  7751  7751 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-06 19:04:46.561  7751  7751 I UEI.SmartControl: QS saving settings...
09-06 19:04:46.564  7751  7751 D UEI.SmartControl: IR Blaster version: 25672567
09-06 19:04:46.582  7751  7795 D UEI.SmartControl: serial port data available: 4
,09-06 19:04:46.622  7751  7799 I UEI.SmartControl: Device manager: loading config....
09-06 19:04:46.624  7751  7799 D UEI.SmartControl: ----------- loading internal config...
,09-06 19:04:46.633  7751  7751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:04:46.640  7751  7751 E UEI.SmartControl: Services init done
,09-06 19:04:46.640  7751  7751 D UEI.SmartControl: QS Service init finished
09-06 19:04:46.642  7751  7751 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:04:46.643  7751  7751 D UEI.SmartControl: QS Service version code: 201091
09-06 19:04:46.645  7751  7751 D UEI.SmartControl: Service requested: Control
,09-06 19:04:46.651  7751  7751 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 19:04:46.652  7751  7799 E UEI.SmartControl: Loading SETTINGS...
09-06 19:04:46.658  7066  7066 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 19:04:46.658  7751  7766 I UEI.SmartControl: ------ IControl API: 11
09-06 19:04:46.659  7751  7766 I UEI.SmartControl: Registering callback...
09-06 19:04:46.660  1032  2039 I ActivityManager: Killing 7066:com.lge.qremote/u0a112 (adj 15): empty #17
,09-06 19:04:46.667  7751  7799 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:04:46.682  7751  7798 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:04:46.683  7751  7798 D UEI.SmartControl: -----service ready thread exits
,09-06 19:04:46.716  1032  1981 W libprocessgroup: failed to open /acct/uid_10112/pid_7066/cgroup.procs: No such file or directory
,09-06 19:04:46.716  7751  7751 D UEI.SmartControl: Internal service binding...
,09-06 19:04:47.326  7138  7608 D bt_hci_bdroid: cleanup
,09-06 19:04:47.334  7138  7676 I bt_lpm  : LPM is already off!!!
09-06 19:04:47.335  7138  7703 I bt_userial_mct: exiting userial_read_thread
09-06 19:04:47.335  7138  7703 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:04:47.337  7138  7674 W bt-btif : ag scb idx 1 not allocated
09-06 19:04:47.337  7138  7674 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:04:47.337  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:47.337  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:47.337  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:04:47.338  7138  7674 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:04:47.338  7138  7674 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:04:47.339  7138  7608 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:04:47.339  7138  7676 I bt_vendor: hw_epilog_process
09-06 19:04:47.339  7138  7608 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 19:04:47.340  7138  7608 D bt_userial_mct: userial_close
09-06 19:04:47.340  7138  7608 E bt_userial_mct: pthread_join() FAILED result:3
09-06 19:04:47.340  7138  7608 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-06 19:04:47.346  7138  7608 D bt_hci_bdroid: set_power 0
09-06 19:04:47.346  7138  7608 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:04:47.346  7138  7608 I bt_vendor: bluetooth satus is on
09-06 19:04:47.346  7138  7608 I bt_vendor: bt-vendor : resetting BT status
09-06 19:04:47.346  7138  7608 I bt_vendor: Starting hciattach daemon
09-06 19:04:47.346  7138  7608 I bt_vendor: try to set false
,09-06 19:04:47.353  7138  7608 I bt_vendor: Starting hciattach daemon
09-06 19:04:47.353  7138  7608 I bt_vendor: try to set false
09-06 19:04:47.354  7138  7608 I bt_vendor: cleanup
09-06 19:04:47.355  7138  7674 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:04:47.355  7138  7608 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:04:47.355  7138  7608 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:04:47.357  7138  7604 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:04:47.362  7138  7138 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:04:47.367  7138  7138 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:04:47.367  7138  7138 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:04:47.367  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:47.367  7138  7628 D HeadsetStateMachine: Exit Disconnected: -1
09-06 19:04:47.372  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:47.372  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:47.372  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:47.374  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-06 19:04:47.374  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:04:47.375  7138  7604 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 19:04:47.378  7138  7138 D A2dpService: Received stop request...Stopping profile...
09-06 19:04:47.379  7138  7666 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:04:47.381  7138  7138 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 19:04:47.383  7138  7138 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:04:47.383  7138  7138 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:04:47.383  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:47.385  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-06 19:04:47.385  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:04:47.385  7138  7138 D HidService: Received stop request...Stopping profile...
09-06 19:04:47.386  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:47.388  7138  7138 D HealthService: Received stop request...Stopping profile...
09-06 19:04:47.388  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
,09-06 19:04:47.393  7138  7138 D HeadsetStateMachine: Unbinding service...
09-06 19:04:47.393  7138  7138 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:04:47.393  7138  7138 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:04:47.393  7138  7138 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:04:47.393  7138  7138 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:04:47.393  7138  7138 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:04:47.393  7138  7138 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:04:47.394  7138  7138 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:04:47.395  7138  7138 D PanService: Received stop request...Stopping profile...
09-06 19:04:47.396  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:47.397  7138  7138 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:04:47.397  7138  7138 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:04:47.397  7138  7138 D BtGatt.GattService: stop()
09-06 19:04:47.397  7138  7138 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:04:47.398  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:47.401  7138  7138 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:04:47.401  7138  7138 D BluetoothMapService: stop()
,09-06 19:04:47.405  7138  7138 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:04:47.405  7138  7138 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 19:04:47.406  7138  7138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd024b1
09-06 19:04:47.407  7138  7138 I BluetoothA2dpServiceJni: cleanupNative
09-06 19:04:47.407  7138  7667 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:04:47.407  7138  7138 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:04:47.407  7138  7138 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:04:47.408  7138  7138 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:04:47.408  7138  7138 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:04:47.408  7138  7138 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:04:47.408  7138  7138 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:04:47.408  7138  7138 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:04:47.409  7138  7138 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:04:47.409  7138  7138 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:04:47.411  7138  7138 V BluetoothMapService: Handler(): got msg=4
09-06 19:04:47.411  7138  7138 D BluetoothMapService: MAP Service closeService in
09-06 19:04:47.411  7138  7138 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:04:47.411  7138  7138 V BluetoothMapService: MAP Service closeService out
09-06 19:04:47.412  7138  7604 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:04:47.412  7138  7604 D BluetoothAdapterProperties: Setting state to 10
09-06 19:04:47.412  7138  7604 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:04:47.412  7138  7138 D BluetoothMapService: cleanup()
09-06 19:04:47.413  7138  7138 D BluetoothMapService: MAP Service closeService in
09-06 19:04:47.413  7138  7138 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:04:47.413  7138  7138 V BluetoothMapService: MAP Service closeService out
09-06 19:04:47.415  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:47.415  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:04:47.415  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,09-06 19:04:47.418  7138  7604 I BluetoothAdapterState: Entering OffState
09-06 19:04:47.419  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:47.419  1032  1103 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:47.419  6996  7107 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:04:47.420  6996  7107 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:47.421  6996  7107 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:04:47.421  1032  1103 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:04:47.421  6996  7107 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:04:47.422  6996  7107 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:04:47.425  1839  2712 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:47.427  6996  7107 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:04:47.429  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:04:47.430  1032  1103 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:04:47.430  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 19:04:47.432  1032  1103 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:04:47.432  1032  1103 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:04:47.432  1032  1103 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@18e31304 mBinding = false
09-06 19:04:47.432  1032  1103 D BluetoothManagerService: Sending unbind request.
09-06 19:04:47.437  7138  7608 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:04:47.439  7138  7138 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:04:47.439  7138  7138 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:04:47.439  7138  7138 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:04:47.439  7138  7138 I art     : --- WEIRD: removing null entry 248
09-06 19:04:47.439  7138  7138 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-06 19:04:47.439  7138  7138 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,09-06 19:04:47.442  7138  7138 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:04:47.443  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 19:04:47.446  7138  7138 I art     : System.exit called, status: 0
09-06 19:04:47.446  7138  7138 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:04:47.465   325  1368 V AudioFlinger: 7138 died, releasing its sessions
09-06 19:04:47.465   325  1368 V AudioFlinger:  pid 1839 @ 0
09-06 19:04:47.465   325  1368 V AudioFlinger:  pid 3488 @ 1
09-06 19:04:47.465   325  1368 V AudioFlinger:  pid 3488 @ 2
,09-06 19:04:47.469  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,09-06 19:04:47.469  1929  2090 D LGBluetoothAPIService: Message: 101
09-06 19:04:47.469  1929  2090 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-06 19:04:47.469  1929  2090 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
,09-06 19:04:47.470  1929  2090 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-06 19:04:47.472  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 19:04:47.477  1032  1048 I ActivityManager: Process com.android.bluetooth (pid 7138) has died
,09-06 19:04:47.480  1032  1048 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-06 19:04:47.480  1032  1048 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,09-06 19:04:47.493  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:47.493  1929  2090 D LGBluetoothAPIService: Message: 2
09-06 19:04:47.493  1929  2090 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-06 19:04:47.494  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:47.495  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:47.499  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:47.499  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 19:04:47.499  6996  6996 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 19:04:47.503  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:04:47.504  1591  1591 D BluetoothAdapter: 222413363: getState() :  mService = null. Returning STATE_OFF
09-06 19:04:47.504  1591  1591 D BluetoothAdapter: 222413363: getState() :  mService = null. Returning STATE_OFF
09-06 19:04:47.549  1032  1564 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7830 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-06 19:04:47.550  6996  6996 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:04:47.631  7830  7830 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:04:47.632  7830  7830 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:04:47.632  7830  7830 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 19:04:47.633  7830  7830 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:04:47.654  7830  7830 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:04:47.689  7830  7830 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2952ff79 Instance Count = 1
,09-06 19:04:47.695  7830  7830 D BluetoothAdapterApp: onCreate
,09-06 19:04:47.721  7830  7830 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 19:04:47.721  7830  7830 D ProfileConfigQcom: Adding HeadsetService
09-06 19:04:47.722  7830  7830 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-06 19:04:47.722  7830  7830 D ProfileConfigQcom: Adding A2dpService
09-06 19:04:47.723  7830  7830 D ProfileConfigQcom: [BTUI] HidService is supported
09-06 19:04:47.723  7830  7830 D ProfileConfigQcom: Adding HidService
09-06 19:04:47.724  7830  7830 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 19:04:47.724  7830  7830 D ProfileConfigQcom: Adding HealthService
,09-06 19:04:47.726  7830  7830 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-06 19:04:47.728  7830  7830 D ProfileConfigQcom: [BTUI] PanService is supported
,09-06 19:04:47.728  7830  7830 D ProfileConfigQcom: Adding PanService
09-06 19:04:47.729  7830  7830 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 19:04:47.729  7830  7830 D ProfileConfigQcom: Adding GattService
,09-06 19:04:47.730  7830  7830 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 19:04:47.730  7830  7830 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:04:47.731  7830  7830 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,09-06 19:04:47.733  7830  7830 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:04:47.736  7830  7830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:47.736  7830  7830 V BluetoothPbapReceiver: ***********state = 10
,09-06 19:04:47.738  7830  7830 V LGMDMManagerInternal: Create singleton instance
,09-06 19:04:47.822  7830  7830 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 19:04:47.823  7830  7830 D LGBluetoothAPIServer: [BTUI] onBind()
,09-06 19:04:47.826  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:04:47.830  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 19:04:47.830  1929  2090 D LGBluetoothAPIService: Message: 100
09-06 19:04:47.830  1929  2090 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:04:47.839  6996  6996 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-06 19:04:47.846  6996  6996 D BluetoothPermissionRequest: onReceive
,09-06 19:04:47.849  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:04:47.849  6996  6996 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 19:04:47.851  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:47.859  7830  7830 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-06 19:04:47.865  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:47.868  7830  7830 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:47.868  7830  7830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:47.868  7830  7830 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:47.869  7830  7830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:47.869  7830  7830 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 19:04:47.873  7083  7083 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-06 19:04:49.383  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:04:49.383  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:04:49.470  1591  1591 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-06 19:04:49.506  1032  1435 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:04:49.554  1032  1032 D administrator: Handling package changes for user 0
,09-06 19:04:49.568  1032  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7859 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 19:04:49.576  1591  1591 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-06 19:04:49.576  1591  1591 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-06 19:04:49.600  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 19:04:49.650  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:49.672  7859  7859 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:04:49.715  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-06 19:04:49.716  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 19:04:49.759  1032  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:04:49.765  1032  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-06 19:04:49.770  7859  7859 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:04:49.770  7859  7859 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:04:49.771  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-06 19:04:49.774  2494  2494 V GmsNetworkLocationProvi: DISABLE
09-06 19:04:49.805  1032  1091 D LocationProviderProxy: applying state to connected service
,09-06 19:04:49.808  2494  2494 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-06 19:04:49.878  7859  7904 I Babel   : MmsConfig: mnc/mcc: 0/0
09-06 19:04:49.878  7859  7904 I Babel   : MmsConfig.loadMmsSettings
09-06 19:04:49.883  7859  7904 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 19:04:49.883  7859  7904 I Babel   : MmsConfig.loadFromDatabase
,09-06 19:04:49.898  7859  7904 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-06 19:04:49.898  7859  7904 I Babel   : MmsConfig.loadFromResources
09-06 19:04:49.900  7859  7904 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-06 19:04:49.901  7859  7904 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 19:04:49.910  7859  7859 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:49.911  7859  7902 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:04:49.912  7859  7902 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 19:04:49.914  7859  7902 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:04:49.924  7859  7902 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-06 19:04:49.925  7859  7902 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 19:04:49.926  7859  7902 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:04:49.939  1804  7906 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-06 19:04:49.939  1804  7906 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-06 19:04:49.943  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:04:49.946  7859  7902 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-06 19:04:49.947  7859  7902 W VideoCapabilities: Unsupported mime video/divx
09-06 19:04:49.947  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fa7b83b
09-06 19:04:49.948  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:04:49.948  7186  7186 D AppUp4:CustFacade: isPhone : true
09-06 19:04:49.948  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:04:49.948  7186  7186 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-06 19:04:49.950  1804  4752 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-06 19:04:49.958  7859  7902 W VideoCapabilities: Unsupported mime video/divx311
09-06 19:04:49.960  7859  7902 W VideoCapabilities: Unsupported mime video/divx4
09-06 19:04:49.976  7859  7902 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:04:49.988  7859  7902 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-06 19:04:49.991  7859  7902 W AudioCapabilities: Unsupported mime audio/eac3
,09-06 19:04:49.992  7859  7902 W AudioCapabilities: Unsupported mime audio/ac3
09-06 19:04:49.993  7859  7902 W AudioCapabilities: Unsupported mime audio/g726
09-06 19:04:49.993  7859  7902 W AudioCapabilities: Unsupported mime audio/wma-voice
09-06 19:04:49.994  1032  1928 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7910 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-06 19:04:49.997  7859  7902 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 19:04:49.999  1032  1981 I ActivityManager: Killing 7036:com.lge.sync/1000 (adj 15): empty #17
09-06 19:04:50.000  7859  7902 W AudioCapabilities: Unsupported mime audio/adpcm
09-06 19:04:50.006  7859  7902 W VideoCapabilities: Unsupported mime video/theora
,09-06 19:04:50.008  7859  7902 W VideoCapabilities: Unsupported mime video/mjpg
09-06 19:04:50.019  1032  1530 D WifiService: Client connection lost with reason: 4
,09-06 19:04:50.128  1032  1939 W libprocessgroup: failed to open /acct/uid_1000/pid_7036/cgroup.procs: No such file or directory
,09-06 19:04:50.174  7910  7910 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:04:50.175  7910  7910 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:04:50.175  7910  7910 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-06 19:04:50.177  7910  7910 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-06 19:04:50.177  7910  7910 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:04:50.267  7910  7910 I SystemConfig: BUILD Country: EU
09-06 19:04:50.268  7910  7910 I SystemConfig: BUILD Operator: OPEN
,09-06 19:04:50.314  1032  1856 I ActivityManager: Killing 7223:com.lge.email/u0a23 (adj 15): empty #17
,09-06 19:04:50.394  1032  2000 W libprocessgroup: failed to open /acct/uid_10023/pid_7223/cgroup.procs: No such file or directory
,09-06 19:04:50.436  1032  1531 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-06 19:04:50.483  1032  1856 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7930 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-06 19:04:50.490  7910  7928 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-06 19:04:50.491  7910  7928 I SystemConfig: existFile = false
09-06 19:04:50.491  7910  7928 I SystemConfig: canReadFile = false
09-06 19:04:50.491  7910  7928 I SystemConfig: systemFeature RCS result false
09-06 19:04:50.491  7910  7928 D SystemConfig: refreshRcsSupport() :false
,09-06 19:04:50.564  7930  7930 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:04:50.565  7930  7930 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:04:50.565  7930  7930 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-06 19:04:50.566  7930  7930 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:04:50.698  7930  7930 I AppConfig: Total System Memory = 2995761152
,09-06 19:04:50.710  7930  7930 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-06 19:04:50.789  1032  1688 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7952 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:04:50.790  1032  1688 I ActivityManager: Killing 7112:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-06 19:04:50.847  1032  1047 W libprocessgroup: failed to open /acct/uid_10026/pid_7112/cgroup.procs: No such file or directory
,09-06 19:04:51.087  7952  7952 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-06 19:04:51.200  7952  7952 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:51.201  7952  7952 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:51.256  7952  7952 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-06 19:04:51.276  7952  7952 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:04:51.279  7952  7952 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-06 19:04:51.293  7952  7952 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-06 19:04:51.294  7952  7952 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-06 19:04:51.314  1032  2039 I ActivityManager: Killing 6568:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-06 19:04:51.389  1032  1688 W libprocessgroup: failed to open /acct/uid_1000/pid_6568/cgroup.procs: No such file or directory
,09-06 19:04:51.427  4567  7994 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-06 19:04:51.474  1032  1893 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7996 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-06 19:04:51.553  2830  2846 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-06 19:04:51.557  2830  2846 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b8db6ce on behalf of 7952
,09-06 19:04:51.571  7952  7952 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-06 19:04:51.589  7952  7952 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-06 19:04:51.593  7996  7996 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-06 19:04:51.615  7996  7996 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-06 19:04:51.615  7996  7996 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-06 19:04:51.615  7996  7996 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-06 19:04:51.615  7996  7996 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-06 19:04:51.615  7996  7996 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-06 19:04:51.615  7996  7996 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-06 19:04:51.629  7751  7800 D UEI.SmartControl: Internal timer expired: 1
,09-06 19:04:51.629  7751  7800 D UEI.SmartControl: unbind internal service
09-06 19:04:51.632  7751  7751 D UEI.SmartControl: Service.onUnbind: IControl
09-06 19:04:51.636  7751  7751 D UEI.SmartControl: Service.onDestroy
09-06 19:04:51.637  7751  7751 D UEI.SmartControl: Lock is in USE false
09-06 19:04:51.637  7751  7751 D UEI.SmartControl: unbind internal service
09-06 19:04:51.637  7751  7751 D serial_port: close(fd = 25)
09-06 19:04:51.640  7751  7751 I UEI.SmartControl: Serial port is closed.
09-06 19:04:51.640  7751  7751 I UEI.SmartControl: Serial port is closed.
09-06 19:04:51.640  7751  7751 D UEI.SmartControl: Blaster closed
09-06 19:04:51.641  7751  7751 D UEI.SmartControl: Shut down QS...
09-06 19:04:51.641  7751  7751 D UEI.SmartControl: Stopping QS lib
09-06 19:04:51.641  7751  7751 D UEI.SmartControl: QS lib stop result = true
09-06 19:04:51.641  7751  7751 D UEI.SmartControl: Stopped QS lib
09-06 19:04:51.641  7751  7751 D UEI.SmartControl: Stopped file observer...
09-06 19:04:51.641  7751  7751 D UEI.SmartControl: QS shutdown complete
09-06 19:04:51.642  1032  1856 I ActivityManager: Killing 7262:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-06 19:04:51.687  1032  1893 W libprocessgroup: failed to open /acct/uid_10046/pid_7262/cgroup.procs: No such file or directory
,09-06 19:04:51.858  1032  1048 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:04:51.883  4567  7994 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 456 ms] updated apps [took 456 ms] 
,09-06 19:04:52.398  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:04:52.398  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18841b15 added. We now have 6 listener(s)
,09-06 19:04:52.398  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:52.410  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:04:52.410  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37be1e2a added. We now have 7 listener(s)
09-06 19:04:52.410  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:04:52.417  6898  6975 I System.out: IsBluetoothEnabled
09-06 19:04:52.419  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:52.419  1032  2023 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-06 19:04:52.420  1032  1103 D BluetoothManagerService: Message: 2
09-06 19:04:52.424  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:52.424  1032  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:52.424  1032  1893 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 19:04:52.440  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:52.440  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:52.440  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:04:52.441  1032  1103 D BluetoothManagerService: Message: 1
09-06 19:04:52.441  1032  1103 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-06 19:04:52.467  1032  1103 D BluetoothManagerService: Message: 20
09-06 19:04:52.467  1032  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34067484:true
,09-06 19:04:52.471  7830  7830 D BluetoothAdapterState: make
09-06 19:04:52.477  7830  7830 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:04:52.477  7830  7830 I bluedroid-qcom: init
09-06 19:04:52.478  7830  8047 I BluetoothAdapterState: Entering OffState
09-06 19:04:52.478  7830  7830 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:04:52.478  7830  7830 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:04:52.478  7830  7830 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:04:52.479  7830  7830 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:04:52.479  7830  7830 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:04:52.482  7830  7830 I bluedroid-qcom: get_profile_interface socket
09-06 19:04:52.482  7830  7830 I bluedroid-qcom: get_profile_interface map_client
,09-06 19:04:52.486  7830  8051 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:04:52.480  8050  8050 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:52.480  8050  8050 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:52.497  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-06 19:04:52.500  1032  1103 D BluetoothManagerService: Message: 40
09-06 19:04:52.500  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 19:04:52.501  7830  7847 I bluedroid-qcom: config_hci_snoop_log
09-06 19:04:52.502  1032  1103 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:04:52.502  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:04:52.508  8050  8050 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:04:52.508  8050  8050 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:04:52.508  8050  8050 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-06 19:04:52.511  8050  8050 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-06 19:04:52.517  8050  8050 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:04:52.517  8050  8050 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 19:04:52.519  7830  8047 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 19:04:52.519  7830  8047 D BluetoothAdapterProperties: Setting state to 11
09-06 19:04:52.520  7830  8047 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:04:52.520  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:52.520  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:04:52.521  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 19:04:52.525  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:04:52.528  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:52.531  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:52.533  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 19:04:52.541  7830  8051 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 19:04:52.544  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-06 19:04:52.545  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:04:52.545  7830  7830 V BluetoothPbapReceiver: PbapReceiver onReceive ,
09-06 19:04:52.545  7830  7830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:52.545  7830  7830 V BluetoothPbapReceiver: ***********state = 11
09-06 19:04:52.552  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:04:52.562  7830  8047 I LGBluetoothServiceJni: classInitNative: succeeds
,09-06 19:04:52.571  7830  8051 D BluetoothAdapterProperties: Name is: G3
09-06 19:04:52.583  7830  8047 D BluetoothBondStateMachine: make
,09-06 19:04:52.585  6996  6996 D BluetoothPermissionRequest: onReceive
09-06 19:04:52.590  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:52.591  7830  8047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:52.591  7830  8047 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:04:52.591  7830  8047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:52.591  7830  8047 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 19:04:52.593  7830  8047 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 19:04:52.594  7830  8067 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 19:04:52.598  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:04:52.600  7830  7830 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:52.600  7830  7830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:52.600  7830  7830 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:52.600  7830  7830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:52.600  7830  7830 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:04:52.601  7830  8047 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:52.610  7830  8047 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:52.612  7830  7830 D HeadsetService: Received start request. Starting profile...
09-06 19:04:52.612  7830  7830 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:04:52.613  7830  7830 D LGBluetoothHfpAdapter: Version 1.6
,09-06 19:04:52.616  7830  7830 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:04:52.617  7830  8047 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:52.617  7830  7830 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:04:52.618  7830  7830 D HeadsetStateMachine: make
09-06 19:04:52.622  7830  8047 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:52.628  7830  8047 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:52.633  7830  8047 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:04:52.639  7830  8047 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:04:52.656  7830  8047 V LGMDMManager: Create singleton instance
,09-06 19:04:52.659  7830  7830 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:52.659  7830  7830 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:04:52.659  7830  8047 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:04:52.664  7830  7830 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:04:52.664  7830  7830 I bluedroid-qcom: get_profile_interface handsfree
,09-06 19:04:52.666  7830  7830 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 19:04:52.667   325  2142 V AudioPolicyService: registerClient() client 0xb0410580, uid 1002
09-06 19:04:52.667   325  1366 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:04:52.667   325  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:04:52.667   325  1366 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:04:52.668  7830  7830 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:04:52.668   325  2146 V AudioFlinger: registerClient() client 0xb1433100, pid 7830
09-06 19:04:52.668   325  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:52.668   325  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:52.669  3488  3503 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:52.669  3488  3503 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:52.669  1839  2712 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:52.669  1839  2712 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:52.669  1032  2023 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:52.669  1032  2023 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-06 19:04:52.669   325  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:52.669   325  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:52.669  1591  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:52.669  1591  2094 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:04:52.670  1591  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:52.670  1591  2094 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:52.670  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:52.670  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:52.670  1032  1564 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:52.670  1032  1564 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:52.670  3488  3504 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:52.670  3488  3504 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:04:52.671  7830  7847 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:04:52.671  7830  7847 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:04:52.671  7830  7847 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:04:52.671  7830  7847 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:04:52.671  7830  7830 V ToneGenerator: Create Track: 0xb4928a80
09-06 19:04:52.671  7830  7830 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:04:52.671  7830  7830 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:04:52.672   325  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:04:52.672   325  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:04:52.672   325  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:04:52.672   325  1368 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:04:52.672   325  2142 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:04:52.672   325  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:04:52.672   325  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:04:52.672   325  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:04:52.672   325  1366 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:04:52.673  7830  7830 V AudioSystem: getLatency() output 2, latency 50
09-06 19:04:52.673  7830  7830 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:04:52.673  7830  7830 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:04:52.673   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:04:52.673   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:04:52.673   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:04:52.673   325  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:04:52.673   325  2146 V AudioFlinger: createTrack() lSessionId: 23
09-06 19:04:52.674  7830  7830 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:04:52.674   325  2146 V AudioFlinger: acquiring 23 from 7830, for 7830
09-06 19:04:52.674   325  2146 V AudioFlinger:  added new entry for 23
09-06 19:04:52.675  7830  7830 V ToneGenerator: ToneGenerator INIT OK, time: 197399
09-06 19:04:52.675  7830  7830 D BluetoothAdapterService: getAdapterService() - returni,ng com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:52.676  7830  8071 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:04:52.676  7830  8071 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:04:52.676  7830  8071 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:04:52.676  7830  8071 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:04:52.676  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:52.678   325   325 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7830
,09-06 19:04:52.678  7830  7830 D A2dpService: Received start request. Starting profile...
09-06 19:04:52.679   325   325 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:04:52.679   325   325 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:04:52.679   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 19:04:52.679   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: exit
,09-06 19:04:52.679   325   325 V voice   : voice_set_parameters: exit with code(0)
09-06 19:04:52.679   325   325 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:04:52.679   325   325 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 19:04:52.679   325   325 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:04:52.679   325   325 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:04:52.679  7830  7830 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:04:52.679   325   325 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:04:52.679   325   325 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:04:52.680  7830  8071 V ToneGenerator: ToneGenerator destructor
09-06 19:04:52.680  7830  8071 V ToneGenerator: stopTone
,09-06 19:04:52.680  7830  8071 V ToneGenerator: Delete Track: 0xb4928a80
09-06 19:04:52.680  7830  7830 V Avrcp   : make
09-06 19:04:52.681  7830  7830 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:04:52.681  7830  7830 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:04:52.681   325  1368 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 19:04:52.681   325  1368 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:04:52.681   325  1111 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:04:52.681   325  1111 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:04:52.681   325  1111 V AudioPolicyManager: releaseOutput() 2
09-06 19:04:52.681   325  1111 V AudioPolicyService: AudioCommandThread() going to sleep
,09-06 19:04:52.681   325  1368 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:04:52.681   325  1368 V AudioFlinger: removeClient_l() pid 7830, calling pid 325
09-06 19:04:52.682  7830  8071 V AudioTrack: ~AudioTrack, releasing session id from 7830 on behalf of 7830
09-06 19:04:52.682   325  2146 V AudioFlinger: releasing 23 from 7830 for 7830
09-06 19:04:52.682   325  2146 V AudioFlinger:  decremented refcount to 0
09-06 19:04:52.682   325  2146 V AudioFlinger: purging stale effects
,09-06 19:04:52.696  7830  7830 V AudioManager: registerRemoteController: size of Media player list: 0
09-06 19:04:52.699  7830  7830 E AudioManager: No RCC entry present to update
09-06 19:04:52.699  7830  7830 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:04:52.703  7830  7830 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,09-06 19:04:52.704  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:04:52.704  7830  7830 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 19:04:52.709  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:04:52.842  1032  1893 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:04:52.843  1032  1893 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:04:52.920  1032  1981 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:04:52.928  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-06 19:04:52.931  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:04:52.932  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:04:52.932  7830  7830 I BluetoothA2dpServiceJni: classInitNative
09-06 19:04:52.933  7830  7830 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:04:52.933  7830  7830 D A2dpStateMachine: make
09-06 19:04:52.936  7830  7830 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:04:52.936  7830  8079 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:04:52.942  7830  7830 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:04:52.942  7830  7830 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:04:52.946  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:52.946  7830  8078 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:04:52.949  7830  7830 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:04:52.956  7830  7830 D HidService: Received start request. Starting profile...
09-06 19:04:52.956  7830  7830 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:04:52.957  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:52.960  7830  7830 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:04:52.966  7830  7830 D HealthService: Received start request. Starting profile...
,09-06 19:04:52.972  7830  7830 I bluedroid-qcom: get_profile_interface health
,09-06 19:04:52.973  7830  7830 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:04:52.973  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
,09-06 19:04:52.974  7830  7830 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:04:52.977  7830  7830 D PanService: Received start request. Starting profile...
,09-06 19:04:52.977  7830  7830 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:04:52.977  7830  7830 I bluedroid-qcom: get_profile_interface pan
09-06 19:04:52.987  7830  7830 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 19:04:52.987  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:52.988  7830  7830 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 19:04:52.995  7830  7830 D BtGatt.DebugUtils: handleDebugAction() action=null,
09-06 19:04:52.996  7830  7830 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:04:52.997  7830  7830 D BtGatt.GattService: start()
09-06 19:04:52.997  7830  7830 I bluedroid-qcom: get_profile_interface gatt,
09-06 19:04:52.997  7830  7830 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:04:53.004  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
,09-06 19:04:53.006  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:53.007  7830  7830 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:04:53.008  7830  7830 V BluetoothMapService: BluetoothMapBinder()
09-06 19:04:53.009  7830  7830 D BluetoothMapService: Received start request. Starting profile...
09-06 19:04:53.009  7830  7830 D BluetoothMapService: start()
09-06 19:04:53.013  7830  7830 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 19:04:53.013  7830  7830 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:04:53.014  7830  7830 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:04:53.015  7830  7830 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-06 19:04:53.024  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
,09-06 19:04:53.025  7830  7830 D HeadsetStateMachine: Proxy object connected
09-06 19:04:53.026  7830  7830 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:04:53.027  7830  7830 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-06 19:04:53.032  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:04:53.033  7830  8071 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:04:53.034  7830  8071 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:04:53.034  7830  8071 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-06 19:04:53.042  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:04:53.047  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:04:53.050  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:04:53.051  7830  7830 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 19:04:53.054  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:04:53.058  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-06 19:04:53.058  7830  7830 V BluetoothMapService: Handler(): got msg=1
09-06 19:04:53.059  7830  8047 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:04:53.060  7830  8047 I bluedroid-qcom: enable
09-06 19:04:53.060  7830  8047 I bt_hci_bdroid: init
09-06 19:04:53.062  7830  8047 I bt_vendor: bt-vendor : init
09-06 19:04:53.062  7830  8047 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:04:53.062  7830  8047 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:04:53.062  7830  8047 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:04:53.062  7830  8047 D bt_userial_mct: userial_init
,09-06 19:04:53.062  7830  8089 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 19:04:53.062  7830  8089 I bt-btu  : btu_task pending for preload complete event
09-06 19:04:53.062  7830  8047 D bt_hci_bdroid: set_power 1
,09-06 19:04:53.063  7830  8047 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:04:53.063  7830  8047 I bt_vendor: Starting hciattach daemon
,09-06 19:04:53.063  7830  8047 I bt_vendor: try to set true
09-06 19:04:53.060  8092  8092 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:04:53.060  8092  8092 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:53.104  8097  8097 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:04:53.184  8105  8105 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:04:53.202  8106  8106 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:04:53.240  8108  8108 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:04:53.254  8109  8109 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 19:04:53.268  8110  8110 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:04:53.294  8111  8111 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:04:53.319  8113  8113 I libmdmdetect: ESOC framework not supported
09-06 19:04:53.321  8113  8113 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 19:04:53.333  8113  8113 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 19:04:53.333  8113  8113 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 19:04:53.333  8113  8113 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 19:04:53.333  8113  8113 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,09-06 19:04:53.333  8113  8113 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-06 19:04:53.333  8113  8113 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:04:53.333  8113  8113 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 19:04:53.377  8113  8114 E QC-QMI  : qmi_client [8113] 15: failed to locate client data
09-06 19:04:53.378   457   457 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 19:04:53.378   457   457 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-06 19:04:53.438  8118  8118 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 ,
,09-06 19:04:53.467  8119  8119 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:04:53.522  7830  8047 I bt_vendor: bluetooth satus is on
09-06 19:04:53.522  7830  8047 D bt_hci_bdroid: preload
,09-06 19:04:53.524  7830  8091 D bt_userial_mct: userial_open(port:0)
,09-06 19:04:53.524  7830  8091 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-06 19:04:53.528  7830  8091 I bt_vendor: Done intiailizing UART
09-06 19:04:53.532  7830  8091 I bt_vendor: Done intiailizing UART
09-06 19:04:53.532  7830  8091 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-06 19:04:53.533  7830  8091 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:04:53.534  7830  8089 I bt-btu  : btu_task received preload complete event
,09-06 19:04:53.535  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:04:53.544  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 19:04:53.548  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 19:04:53.553  7830  8124 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_GAP,
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_SMP,
,09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-06 19:04:53.557  7830  8089 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:04:53.659  7830  8089 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-06 19:04:53.659  7830  8089 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0199061 ,
09-06 19:04:53.659  7830  8089 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0199061 ,
,09-06 19:04:53.699  7830  8051 E bt-btif : Calling BTA_HhEnable
09-06 19:04:53.699  7830  8051 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 19:04:53.700  7830  8051 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 19:04:53.704  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:04:53.704  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:04:53.705  7830  8051 D BluetoothAdapterProperties: Name is: G3
09-06 19:04:53.706  7830  8051 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:04:53.706  7830  8051 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:04:53.706  7830  8051 D bt_hci_bdroid: postload
09-06 19:04:53.707  7830  8051 D bte_conf: Device ID record 1 : primary
09-06 19:04:53.707  7830  8051 D bte_conf:   vendorId            = 00c4
09-06 19:04:53.707  7830  8051 D bte_conf:   vendorIdSource      = 0001
09-06 19:04:53.707  7830  8051 D bte_conf:   product             = 13a1
09-06 19:04:53.707  7830  8051 D bte_conf:   version             = 1000
09-06 19:04:53.707  7830  8051 D bte_conf:   clientExecutableURL = 
09-06 19:04:53.707  7830  8051 D bte_conf:   serviceDescription  = 
09-06 19:04:53.707  7830  8051 D bte_conf:   documentationURL    = 
09-06 19:04:53.708  7830  8091 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:04:53.708  7830  8051 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:04:53.711  7830  8047 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:04:53.711  7830  8047 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:04:53.711  7830  8047 D BluetoothAdapterProperties: State =  11
09-06 19:04:53.712  7830  8047 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 19:04:53.712  7830  8047 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:04:53.712  7830  8047 D BluetoothAdapterProperties: Setting state to 12
09-06 19:04:53.712  7830  8047 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:04:53.713  7830  8051 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:04:53.710  8126  8126 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:53.720  1032  1103 D BluetoothManagerService: Message: 60
09-06 19:04:53.720  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:04:53.720  1032  1103 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-06 19:04:53.710  8126  8126 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:53.728  7830  8091 D bt_hci_bdroid: Used up Tx Cmd credits
,09-06 19:04:53.740  7830  8124 E bt_mct  : hci lib postload completed
,09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:53.755  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:04:53.761  7830  8051 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:04:53.761  7830  8051 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 19:04:53.762  7830  8047 I BluetoothAdapterState: Entering On State
09-06 19:04:53.762  1839  2443 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:04:53.772  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:04:53.787  7830  8047 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:04:53.787  7830  8047 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:04:53.787  7830  8047 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-06 19:04:53.790  7830  8047 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:04:53.796  1839  1839 D BluetoothHeadset: Proxy object connected
09-06 19:04:53.796  1032  1103 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:04:53.797  1032  1032 D BluetoothHeadset: Proxy object connected
09-06 19:04:53.807  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 19:04:53.807  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 19:04:53.807  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,09-06 19:04:53.810  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:04:53.810  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:04:53.810  7830  8089 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:04:53.811  7830  8051 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:04:53.811  7830  8047 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 19:04:53.832  8131  8131 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-06 19:04:53.838  6996  7014 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:04:53.842  6996  7014 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:04:53.843  6996  7107 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:04:53.845  7830  8089 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:53.846  7830  8089 W bt-smp  : Plain text(LSB ~ MSB) = ee f5 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:53.846  7830  8089 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a 8c 46 73 c5 0a 47 71 07 cf f1 c3 c9 8e 1f 2f 
09-06 19:04:53.846  7830  8089 W bt-btm  : Stopping oneshot timer
09-06 19:04:53.849  1032  1103 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:04:53.852  1032  1032 D BluetoothA2dp: Proxy object connected
09-06 19:04:53.853  6996  7014 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:04:53.857  6996  7107 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:04:53.857  6996  7107 D BluetoothPan: onBluetoothStateChange call bindService
09-06 19:04:53.857  6996  6996 D BluetoothMap: Proxy object connected
09-06 19:04:53.857  6996  6996 D MapProfile: Bluetooth service connected
09-06 19:04:53.857  6996  6996 D BluetoothMap: getConnectedDevices()
09-06 19:04:53.863  1839  2712 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:04:53.870  1839  1839 D BluetoothHeadset: Proxy object connected
09-06 19:04:53.871  7830  8089 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:53.871  7830  8089 W bt-smp  : Plain text(LSB ~ MSB) = 14 0e 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:53.871  7830  8089 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 b7 9e 33 1f 27 25 97 12 c2 e8 be 8f c1 60 ff 
09-06 19:04:53.871  7830  8089 W bt-btm  : Stopping oneshot timer
09-06 19:04:53.873  6996  7015 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:04:53.878  1839  2443 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:04:53.882  7830  7847 V BluetoothMapService: getConnectedDevices()
09-06 19:04:53.887  1839  1839 D BluetoothHeadset: Proxy object connected
09-06 19:04:53.889  1032  1103 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:04:53.889  6996  6996 D BluetoothHeadset: Proxy object connected
,09-06 19:04:53.889  6996  6996 D HeadsetProfile: Bluetooth service connected
09-06 19:04:53.889  1032  1103 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 19:04:53.890  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:04:53.891  7830  8089 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:53.891  7830  8089 W bt-smp  : Plain text(LSB ~ MSB) = a2 f8 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:53.891  7830  8089 W bt-smp  : Encrypted text(LSB ~ MSB) = 54 ca c3 89 9c f6 69 62 d1 a9 d4 02 85 ba c0 63 
,09-06 19:04:53.891  7830  8089 W bt-btm  : Stopping oneshot timer
09-06 19:04:53.893  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:53.893  1929  2090 D LGBluetoothAPIService: Message: 1
09-06 19:04:53.893  1929  2090 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:04:53.893  1929  2090 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-06 19:04:53.893  1591  1591 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:04:53.895  1929  2090 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 19:04:53.897  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:53.901  1032  1103 D BluetoothManagerService: Message: 40
09-06 19:04:53.901  1032  1103 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:04:53.901  7830  8089 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:53.901  7830  8089 W bt-smp  : Plain text(LSB ~ MSB) = 4e 10 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:53.901  7830  8089 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 f5 b8 fe 6d c9 10 f1 16 a3 f0 ab 2b ca d0 bf 
09-06 19:04:53.901  7830  8089 W bt-btm  : Stopping oneshot timer
09-06 19:04:53.903  7830  7830 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:04:53.903  7830  7830 D BluetoothMapService: STATE_ON
09-06 19:04:53.906  6996  6996 D BluetoothA2dp: Proxy object connected
09-06 19:04:53.906  6996  6996 D A2dpProfile: Bluetooth service connected
09-06 19:04:53.908  6996  6996 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:04:53.908  6996  6996 D PanProfile: Bluetooth service connected
09-06 19:04:53.911  6996  6996 D BluetoothInputDevice: Proxy object connected
09-06 19:04:53.911  6996  6996 D HidProfile: Bluetooth service connected
09-06 19:04:53.918  7830  8089 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:04:53.918  7830  8089 W bt-smp  : Plain text(LSB ~ MSB) = 57 b8 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:04:53.918  7830  8089 W bt-smp  : Encrypted text(LSB ~ MSB) = 3e 92 c3 a2 86 d6 7e fd 90 54 44 c9 e2 37 61 6a 
09-06 19:04:53.918  7830  8089 W bt-btm  : Stopping oneshot timer
,09-06 19:04:53.921  6996  6996 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 19:04:53.921  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:53.921  7830  7830 V BluetoothPbapService: Pbap Service onCreate
09-06 19:04:53.921  7830  7830 V BluetoothPbapService: Starting PBAP service
09-06 19:04:53.922  6996  6996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:04:53.923  7830  7830 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:04:53.923  7830  7830 V BluetoothPbapService: Pbap Service onBind
09-06 19:04:54.040  1032  2023 I art     : Explicit concurrent mark sweep GC freed 27804(1366KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.778ms total 116.820ms
,09-06 19:04:54.045  7830  7830 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:54.046  7830  7830 V BluetoothPbapService: state: 12
09-06 19:04:54.046  7830  7830 V BluetoothMapService: Handler(): got msg=1
09-06 19:04:54.047  7830  7830 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:04:54.047  7830  7830 V BluetoothPbapService: Handler(): got msg=1
09-06 19:04:54.047  7830  7830 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:04:54.048  6996  6996 D DockEventReceiver: finishStartingService: stopping service
09-06 19:04:54.048  6996  6996 D BluetoothPbap: Proxy object connected
09-06 19:04:54.048  6996  6996 D PbapServerProfile: Bluetooth service connected
09-06 19:04:54.048  7830  7830 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:04:54.049  7830  7830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:54.049  7830  7830 V BluetoothPbapReceiver: ***********state = 12
09-06 19:04:54.049  7830  8154 V BluetoothPbapService: Pbap Service initSocket
09-06 19:04:54.052  7830  8153 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:04:54.053  7830  8153 D BluetoothMapMasInstance:   masId = 00
09-06 19:04:54.053  7830  8153 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:04:54.053  7830  8153 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:04:54.053  7830  8153 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 19:04:54.054  1032  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:54.057  7830  8154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:04:54.072  2172  2172 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:04:54.073  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:54.073  2172  2172 D c       : Getting all permits...
09-06 19:04:54.073  2172  2172 D a       : Opening database...
09-06 19:04:54.073  7830  8153 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:54.076  7830  8153 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:04:54.076  7830  8051 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:04:54.076  7830  8153 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:04:54.076  7830  8051 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:04:54.076  7830  8153 D BluetoothMapMasInstance: Accepting socket connection...
09-06 19:04:54.077  7830  8154 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 19:04:54.077  7830  8154 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:04:54.077  7830  8154 V BluetoothPbapService: Accepting socket connection...
09-06 19:04:54.078  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:54.079  2172  2172 D a       : Opening database auth.proximity.permit_store...
09-06 19:04:54.079  2172  2172 D a       : Closing database...
09-06 19:04:54.090  6996  6996 D BluetoothPermissionRequest: onReceive
09-06 19:04:54.091  6996  6996 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-06 19:04:54.092  6996  6996 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:04:54.095  7830  7830 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 19:04:54.096  7830  7830 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:04:54.102  7830  7830 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 19:04:54.121  7830  7830 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 19:04:54.121  7830  7830 V BtOppService: onCreate
,09-06 19:04:54.125  7830  7830 V BluetoothOppNotification: send message
09-06 19:04:54.129  7830  7830 V BtOppService: Starting RfcommListener
09-06 19:04:54.138  7830  7830 D BluetoothOppPreference: Dumping Names:  
09-06 19:04:54.138  7830  7830 D BluetoothOppPreference: {}
,09-06 19:04:54.138  7830  7830 D BluetoothOppPreference: Dumping Channels:  
09-06 19:04:54.138  7830  7830 D BluetoothOppPreference: {}
09-06 19:04:54.139  7830  7830 V BtOppService: onStartCommand
,09-06 19:04:54.143  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:54.144  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:04:54.144  7830  8161 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:04:54.146  7830  8158 V BtOppService: Deleted complete outbound shares, number =  0
09-06 19:04:54.148  7830  7830 V BluetoothOppNotification: new notify threadi!
09-06 19:04:54.148  7830  8161 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:04:54.149  7830  7830 V BluetoothOppNotification: send delay message
09-06 19:04:54.149  7830  8158 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 19:04:54.150  7830  7830 V BtOppService: start RfcommListener
09-06 19:04:54.150  7830  8158 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:04:54.151  7830  8162 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 19:04:54.153  7830  8161 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d1d6232 on behalf of 
09-06 19:04:54.153  7830  8158 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e1a3b83 on behalf of 
09-06 19:04:54.154  7830  7830 V BtOppService: RfcommListener started
09-06 19:04:54.154  7830  7830 V BtOppService: ContentObserver received notification
09-06 19:04:54.157  7830  8163 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 19:04:54.158  1032  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:54.160  7830  8163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:54.161  7830  8163 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-06 19:04:54.162  7830  8163 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:04:54.162  7830  8163 I BtOppRfcommListener: Accept thread started.
09-06 19:04:54.162  7830  8163 V BtOppRfcommListener: Accepting connection...
09-06 19:04:54.166  7830  8162 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@99f7100 on behalf of 
09-06 19:04:54.167  7830  8162 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-06 19:04:54.168  7830  8161 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:04:54.169  7830  8161 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:04:54.171  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:54.171  7830  7830 V BluetoothFtpService: Ftp Service onCreate
09-06 19:04:54.171  7830  7830 I BluetoothFtpService: Ftp Service onCreate
09-06 19:04:54.171  7830  8161 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@323b6f7e on behalf of 
09-06 19:04:54.171  7830  7830 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:04:54.171  7830  7830 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:54.171  7830  7830 V BluetoothFtpService: Starting Listening on sockets
09-06 19:04:54.172  7830  7830 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:04:54.172  7830  7830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:04:54.172  7830  7830 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:04:54.172  7830  8161 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:04:54.172  7830  7830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:54.172  7830  7830 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 19:04:54.172  7830  8162 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:54.172  7830  7830 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:04:54.175  7830  7830 V BtOppService: ContentObserver received notification
09-06 19:04:54.175  7830  7830 V BluetoothFtpService: Handler(): got msg=1
09-06 19:04:54.175  7830  7830 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:04:54.176  7830  7830 V BluetoothFtpService: Ftp Service initSocket
09-06 19:04:54.176  7830  8161 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:04:54.176  7830  8161 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:04:54.178  7830  8161 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38bb0cdf on behalf of 
09-06 19:04:54.178  7830  8162 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@390a9d2c on behalf of 
09-06 19:04:54.178  1032  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:54.179  7830  8161 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:04:54.180  7830  8162 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 19:04:54.181  7830  7830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:54.183  7830  8162 V BluetoothOppNotification: outbound notification was removed.
09-06 19:04:54.184  7830  8162 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:54.184  7830  8161 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:04:54.184  7830  7830 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:04:54.185  7830  8162 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17083f5 on behalf of 
09-06 19:04:54.186  7830  8164 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 19:04:54.186  7830  8162 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:04:54.188  7830  8162 V BluetoothOppNotification: inbound notification was removed.
09-06 19:04:54.188  7830  8162 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:04:54.189  7830  8162 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@299b058a on behalf of 
09-06 19:04:54.206  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38b3bd96
09-06 19:04:54.207  7830  7830 V BluetoothSapService: Sap Service onCreate
09-06 19:04:54.209  7830  7830 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:04:54.209  7830  7830 V BluetoothSapService: state: 12
09-06 19:04:54.209  7830  7830 V BluetoothSapService: Starting SAP server process
,09-06 19:04:54.210  7830  7830 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 19:04:54.212  7830  8166 V BluetoothSapService: Sap Service initRfcommSocket
,09-06 19:04:54.212  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:54.200  8165  8165 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:54.200  8165  8165 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:54.214  7830  8166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:04:54.216  7830  8166 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 19:04:54.216  7830  8166 V BluetoothSapService: Succeed to create listening socket 
09-06 19:04:54.216  7830  8166 V BluetoothSapService: Accepting socket connection...
09-06 19:04:54.225  8165  8165 V BT_SAP  : Event pipe created
09-06 19:04:54.225  8165  8165 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:04:54.225  8165  8165 V BT_SAP  : created socket fd 6
,09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:54.497  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:04:54.500  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:54.503  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:54.503  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@279fd41b added. We now have 8 listener(s)
09-06 19:04:54.503  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:54.506  1032  2023 D WifiServiceImplEx: setWifiEnabled: false pid=6898, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:04:54.506  1032  2023 D WifiService: setWifiEnabled: false pid=6898, uid=10118
09-06 19:04:54.506  1032  2023 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:04:54.513  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:54.516  1032  1564 D WifiServiceImplEx: setWifiEnabled: true pid=6898, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-06 19:04:54.516  1032  1564 D WifiService: setWifiEnabled: true pid=6898, uid=10118
09-06 19:04:54.516  1032  1564 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:04:54.531  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:04:54.531  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:04:54.531  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:04:54.533  1032  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 19:04:54.533  1032  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-06 19:04:54.536  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-06 19:04:54.536  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:04:54.536  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-06 19:04:54.536  1032  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:04:54.537  1032  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 19:04:54.537  1032  1523 E WifiHW  : unknown target_country: EU , set to default
09-06 19:04:54.537  1032  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 19:04:54.537  1032  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 19:04:54.537  1032  1523 I WifiUtil: gEnableBmps=1
09-06 19:04:54.661  7859  7885 W art     : Suspending all threads took: 5.861ms
,09-06 19:04:55.152  7830  7830 V BluetoothOppNotification: new notify threadi!
,09-06 19:04:55.152  7830  7830 V BluetoothOppNotification: send delay message
,09-06 19:04:55.172  7830  8185 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 19:04:55.215  7830  8185 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2eabf056 on behalf of 
09-06 19:04:55.216  7830  8185 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-06 19:04:55.234   314   876 D SoftapController: Softap fwReload - Ok
,09-06 19:04:55.274  1032  1523 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (734ms)
,09-06 19:04:55.287  1032  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:04:55.287  1032  1103 D Tethering: InitialState.processMessage what=4
,09-06 19:04:55.293   314   876 D CommandListener: Setting iface cfg
09-06 19:04:55.293   314   876 D CommandListener: Trying to bring down wlan0
09-06 19:04:55.293   314   876 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:04:55.299  1032  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-06 19:04:55.318  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:55.318  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:55.318  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-06 19:04:55.320  8187  8187 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:55.320  8187  8187 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:04:55.359  1032  1103 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:04:55.366  1032  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:04:55.366  1032  1523 D WifiMonitor: connecting to supplicant
09-06 19:04:55.368  7830  8185 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:55.374  8187  8187 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:04:55.377  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 19:04:55.380  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:55.381  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 19:04:55.383  7830  8185 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3af3b8d7 on behalf of 
09-06 19:04:55.383  7830  8185 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:04:55.385  7830  8185 V BluetoothOppNotification: outbound notification was removed.
09-06 19:04:55.385  7830  8185 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:04:55.386  7830  8185 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@296165c4 on behalf of 
09-06 19:04:55.387  7830  8185 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-06 19:04:55.390  7830  8185 V BluetoothOppNotification: inbound notification was removed.
09-06 19:04:55.390  7830  8185 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:04:55.392  7830  8185 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5123cad on behalf of 
09-06 19:04:55.397  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:55.399  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:04:55.399  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:04:55.399  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:04:55.399  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:04:55.399  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 19:04:55.402  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:04:55.402  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:04:55.402  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:04:55.402  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:04:55.402  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:04:55.403  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:04:55.406  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-06 19:04:55.407  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:04:55.407  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:04:55.407  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:04:55.407  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:04:55.408  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:04:55.408  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:04:55.408  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:04:55.408  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:04:55.408  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:04:55.408  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:04:55.412  8187  8187 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:04:55.412  8187  8187 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-06 19:04:55.465  1032  2015 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8204 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-06 19:04:55.487  8187  8187 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:04:55.487   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 18.606ms
,09-06 19:04:55.505   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 15.596ms
,09-06 19:04:55.521   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 256us total 14.780ms
09-06 19:04:55.538  8187  8187 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-06 19:04:55.545  8187  8187 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-06 19:04:55.546  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:04:55.547  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 19:04:55.547  8187  8187 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 19:04:55.547  1032  8223 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-06 19:04:55.547  1032  8223 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:04:55.547  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:04:55.547  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:04:55.547  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 19:04:55.547  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 19:04:55.547  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:04:55.547  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:04:55.548  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:04:55.548  1032  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:04:55.549  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:55.549  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:55.551  1032  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-06 19:04:55.552  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:55.552  1032  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:04:55.552  1032  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 19:04:55.553  1032  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,09-06 19:04:55.553  1032  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:04:55.553  1032  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-06 19:04:55.597  1032  1883 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8228 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:04:55.600  1032  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:04:55.600  1032  1523 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:04:55.600  1032  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:04:55.601  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.601  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.601  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.601  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.601  1032  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:04:55.601  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:04:55.602  1929  1929 D WfdService: Waiting for WifiP2p enabling
09-06 19:04:55.602  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:55.605  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:04:55.605  1032  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-06 19:04:55.606  1032  1523 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:04:55.606  1032  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:04:55.606  1032  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:04:55.607  1032  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 19:04:55.610  8204  8226 W FormManager: Network not available. Please check & try again.
,09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:55.616  6898  6898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:04:55.617  1032  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 19:04:55.618  6898  6898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:55.621  8204  8227 V FormManager: Network unavailable.
09-06 19:04:55.624  8204  8227 V FormManager: Network unavailable.
09-06 19:04:55.630  1032  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-06 19:04:55.630  1032  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:04:55.632  1032  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:04:55.632  1032  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 19:04:55.632  1032  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:04:55.632  1032  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:04:55.633  1032  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:04:55.633  1032  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:04:55.633  1032  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:04:55.633  1032  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:04:55.634  1032  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:04:55.634  1032  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:04:55.634  1032  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:04:55.634  1032  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 19:04:55.635  1032  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:04:55.635  1032  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,09-06 19:04:55.635  1032  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 19:04:55.639  1929  1929 D WfdsService: Supplicant Connection state is changed : true
09-06 19:04:55.639  1929  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:04:55.639  1032  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:04:55.639  1929  2284 D WfdsService: Set the WFDS Monitor: true
09-06 19:04:55.639  1032  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 19:04:55.639  1929  2284 D WfdsMonitor: WfdsMonitorThread create
09-06 19:04:55.639  1929  2284 D WfdsMonitor: WFDS Monitor is created and started
09-06 19:04:55.639  1929  2284 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:04:55.640  1032  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 19:04:55.640  1032  1523 D WifiNative-HAL: Setting external_sim to 1
,09-06 19:04:55.640  1032  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 19:04:55.640  1032  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:04:55.640  1032  1523 I WifiNative-HAL: startHal
09-06 19:04:55.640  1032  1523 D wifi    : setting scan oui 0xaf6e24c0
09-06 19:04:55.641  1032  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:04:55.641  1032  1523 I WifiNative-HAL: startHal
09-06 19:04:55.641  1032  1523 D wifi    : setting scan oui 0xaf6e24c0
09-06 19:04:55.641  1032  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 19:04:55.641  7859  7859 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.642  1929  8246 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:04:55.642  1032  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 19:04:55.642  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 19:04:55.642  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 19:04:55.642  1929  8246 E CtrlSupplicant: Succeed to open control connection
09-06 19:04:55.642  1929  8246 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:04:55.643  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 19:04:55.643  1929  8246 D WfdsMonitor: Supplicant connection established
09-06 19:04:55.643  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:04:55.643  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:04:55.643  1032  1893 I ActivityManager: Killing 7288:com.android.chrome/u0a57 (adj 15): empty #17
09-06 19:04:55.643  1929  2284 D WfdsService: Connected to the supplicant for wfds
09-06 19:04:55.643  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:04:55.643  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:04:55.644  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,09-06 19:04:55.644  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:04:55.644  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:04:55.644  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:04:55.644  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:04:55.645  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:04:55.645  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:04:55.645  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:04:55.645  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,09-06 19:04:55.645  8187  8187 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:04:55.646  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 19:04:55.646  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:04:55.646  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-06 19:04:55.646  1032  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:04:55.647  1032  1523 E WifiNative: : [200,359,935 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 19:04:55.647  1032  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:04:55.648  1032  1523 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:04:55.648  1032  1523 D WifiNative-wlan0: doString: [STATUS]
09-06 19:04:55.648  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:04:55.648  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:04:55.649  1032  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:04:55.649  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:04:55.649  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:04:55.649  1032  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.651   314   876 D CommandListener: Setting iface cfg
09-06 19:04:55.651   314   876 D CommandListener: Trying to bring up p2p0
09-06 19:04:55.651  1032  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:04:55.651  1032  1522 D LGWifiP2pService: P2pEnablingState
09-06 19:04:55.651  1032  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.651  1032  1522 D LGWifiP2pService: P2p socket connection successful
09-06 19:04:55.652  1032  1522 D LGWifiP2pService: P2pEnabledState
09-06 19:04:55.665  8228  8228 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:04:55.686  1032  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:04:55.687  1032  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:04:55.687  1032  1964 W libprocessgroup: failed to open /acct/uid_10057/pid_7288/cgroup.procs: No such file or directory
09-06 19:04:55.687  1032  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:04:55.687  1032  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:04:55.688  1032  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 19:04:55.688  1032  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 19:04:55.688  1032  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 19:04:55.688  1032  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:04:55.688  1032  1522 D WifiNative-p2p0: SET device_name G3: returned true
,09-06 19:04:55.688  1032  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:04:55.688  1032  1522 D LGWifiP2pService: before postfix = G3
09-06 19:04:55.688  1032  1522 D WifiServerServiceExt: postfix byte check : 2
09-06 19:04:55.688  1032  1522 D LGWifiP2pService: after postfix = G3
09-06 19:04:55.688  1032  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 19:04:55.689  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200402  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:55.689  1032  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:04:55.689  1032  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:04:55.689  1032  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:04:55.689  1032  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 19:04:55.690  1032  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 19:04:55.690  1032  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:04:55.691  1032  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 19:04:55.691  1032  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:04:55.691  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:04:55.691  1929  1929 D WfdsService: WifiP2pState is changed : true
09-06 19:04:55.691  1929  2284 D WfdsService: Receive the WFDS_ENABLE Method
09-06 19:04:55.691  1929  2284 D WfdsService: Set the WFDS Monitor: true
09-06 19:04:55.692  1929  2284 D WfdsService: Connected to the supplicant for wfds
09-06 19:04:55.692  1929  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 19:04:55.692  8187  8187 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 19:04:55.692  1032  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 19:04:55.692  1929  2284 D WfdsService: selectPreferredScanChannel [36]
09-06 19:04:55.692  1929  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 19:04:55.692  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:04:55.692  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-06 19:04:55.692  1032  1545 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.692  1032  1545 I WifiNative-HAL: startHal
09-06 19:04:55.692  1032  1545 D wifi    : getting scan capabilities on interface[1] = 0xaf6e24c0
09-06 19:04:55.692  1032  1545 D wifi    : failed to get capabilities : -3
09-06 19:04:55.692  1032  1545 E WifiScanningService: could not get scan capabilities
09-06 19:04:55.692  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:04:55.693  1032  1546 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.693  1929  1929 D WfdsService: isConnected: false
09-06 19:04:55.694  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:04:55.695  1032  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 19:04:55.695  1032  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 19:04:55.695  1032  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 19:04:55.696  1032  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 19:04:55.696  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200409  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:55.696  1032  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:04:55.696  1032  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:04:55.696  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:04:55.696  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:04:55.696  1929  1929 D WfdsService: U,pdate P2p Interface State: 3
09-06 19:04:55.696  1032  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 19:04:55.697  1032  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 19:04:55.697  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:55.697  1032  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 19:04:55.697  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:55.697  1032  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:04:55.697  1032  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:04:55.697  1032  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 19:04:55.698  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:55.700  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.700  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.701  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-06 19:04:55.706  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:55.707  1032  2039 I ActivityManager: Killing 7309:com.lge.drmservice/u0a62 (adj 15): empty #17
09-06 19:04:55.710  8187  8187 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:04:55.710  1032  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:04:55.710  1032  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:04:55.711  1032  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:04:55.711  1032  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 19:04:55.711  8187  8187 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 19:04:55.712  1032  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:04:55.712  1032  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:04:55.712  1032  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:04:55.712  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 19:04:55.713  1032  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 19:04:55.713  1032  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:04:55.713  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-06 19:04:55.714  8187  8187 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.714  8187  8187 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:04:55.714  8187  8187 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-06 19:04:55.715  8187  8187 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.715  1929  8246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:55.716  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:04:55.716  1929  8246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:55.716  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.716  1032  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:04:55.716  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.716  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.716  1032  8223 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-06 19:04:55.716  1032  8223 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.716  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.716  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.716  1032  8223 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:55.716  1032  8223 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.716  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.716  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.716  1032  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:04:55.717  1032  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:04:55.718  1032  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:04:55.718  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:04:55.718  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:04:55.718  8187  8187 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:55.718  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:04:55.718  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:55.718  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:55.718  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:04:55.719  1032  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:04:55.719  1032  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:04:55.719  1032  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:04:55.719  1032  1523 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:04:55.719  1032  1523 D WifiNative-wlan0: SCAN: returned false
09-06 19:04:55.719  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=200432  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:55.756  1032  1522 D LGWifiP2pService: InactiveState
09-06 19:04:55.757  1032  1522 D LGWifiP2pService: InactiveState{ when=-60ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.757  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-60ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.757  1032  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 19:04:55.757  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:04:55.758  8187  8187 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.760  8187  8187 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,09-06 19:04:55.760  8187  8187 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.761  1032  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: InactiveState{ when=-45ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-45ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  8223 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  8223 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.761  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.762  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:04:55.762  1032  8223 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:55.762  1032  8223 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.762  8187  8187 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.762  1929  2284 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 19:04:55.762  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.762  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.762  1929  8246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:04:55.762  1032  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.762  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.762  1929  8246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:55.762  1032  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:55.762  1929  8246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:55.763  1032  1032 E WifiServerServiceExt: No p2p device connected
09-06 19:04:55.763  1032  8223 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:04:55.763  1032  8223 E Wi,fiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.763  1032  8223 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.763  1032  8223 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:04:55.764  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=200477  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:04:55.764  1032  1939 W libprocessgroup: failed to open /acct/uid_10062/pid_7309/cgroup.procs: No such file or directory
09-06 19:04:55.764  1032  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:55.765  1032  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:55.765  1032  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:55.766  1032  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:55.767  1032  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:04:55.778  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:55.778  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:55.781  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:55.785  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:04:55.785  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:55.786  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:04:55.793  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:55.793  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:04:55.794  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:55.794  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-06 19:04:55.810  8228  8228 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:04:55.813  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:04:55.820  8204  8250 W FormManager: Network not available. Please check & try again.
09-06 19:04:55.821  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:55.827  8204  8251 V FormManager: Network unavailable.
,09-06 19:04:55.836  8204  8251 V FormManager: Network unavailable.
09-06 19:04:55.842  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-06 19:04:55.842  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:04:55.844  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:55.847  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:04:55.855  4301  8252 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:04:55.862  4301  8253 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:04:55.862  4301  8253 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:04:55.909  1032  1939 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8254 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 19:04:56.019  8254  8254 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:04:56.019  8254  8254 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 19:04:56.028  8254  8254 V [BNRBootReceiver]: Boot Receiver Return
09-06 19:04:56.028  8254  8254 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:04:56.108  1032  2015 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8275 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:04:56.111  1032  2015 I ActivityManager: Killing 7326:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-06 19:04:56.158  1032  1047 W libprocessgroup: failed to open /acct/uid_10085/pid_7326/cgroup.procs: No such file or directory
,09-06 19:04:56.184  8275  8275 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:04:56.209  8275  8275 D PluginManager: init()
09-06 19:04:56.210  8187  8187 E wpa_supplicant: USIM:  scard_init function
09-06 19:04:56.211  8187  8187 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 19:04:56.212  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 19:04:56.212  1032  8223 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 19:04:56.212  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,09-06 19:04:56.213  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
,09-06 19:04:56.213  1032  8223 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:04:56.213  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:04:56.213  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 19:04:56.214  1032  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:56.216  1032  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:56.217  1032  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:56.218  1032  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 19:04:56.218  1032  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 19:04:56.232  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=200945  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:04:56.239  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.239  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:56.239  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.239  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.239  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:04:56.240  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=200953  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:04:56.241  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:56.241  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:04:56.242  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:56.448  8187  8187 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:04:56.455  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:04:56.455  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:04:56.455  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:04:56.455  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:04:56.455  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:56.455  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:56.456  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=201169  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:04:56.456  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=201169  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:04:56.457  1032  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201170
09-06 19:04:56.457  1032  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201170
09-06 19:04:56.457  1032  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201170
09-06 19:04:56.457  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201170
09-06 19:04:56.457  1032  1103 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:04:56.458  1032  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201171
09-06 19:04:56.458  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=201171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:04:56.459  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=201172  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-06 19:04:56.459  1032  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:56.459  1032  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:56.460  1032  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:56.460  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:56.460  1032  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:04:56.463  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.463  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:56.464  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.465  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:56.465  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:56.466  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.466  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.466  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:04:56.466  1032  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=201179  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:04:56.466  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.466  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.466  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:04:56.466  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:56.466  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:04:56.466  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:56.466  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=201179  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:04:56.466  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-06 19:04:56.468  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.468  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:56.468  8187  8187 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:04:56.468  8187  8187 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-06 19:04:56.469  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.470  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:56.470  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:04:56.470  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:04:56.470  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:04:56.470  1032  8223 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:04:56.470  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:04:56.470  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:04:56.470  1032  8223 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:04:56.471  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:56.471  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:56.471  1032  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=201184
09-06 19:04:56.472  1032  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=201185
09-06 19:04:56.472  1032  1523 D WifiNative-wlan0: doString: [STATUS]
09-06 19:04:56.473  1032  8223 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:04:56.473  1032  8223 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:04:56.474  1032  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:04:56.476  1032  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 19:04:56.482  1032  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 19:04:56.482  1032  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-06 19:04:56.486  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.486  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:56.486  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.486  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.487  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.487  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:04:56.489  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.489  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.489  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:04:56.493  1032  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 19:04:56.493  1032  1531 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:04:56.493  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:04:56.493  1032  1531 D ConnectivityService: NetworkAgent connected
09-06 19:04:56.494  1032  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:04:56.494  1032  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:04:56.494  1032  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:04:56.494  1032  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:04:56.499  1032  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:04:56.499  1032  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:04:56.499  1032  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:04:56.500  1032  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:04:56.500  1032  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 19:04:56.505  1032  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:04:56.506  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.507  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:56.507   314   876 D CommandListener: Setting iface cfg
09-06 19:04:56.508  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.512  1032  1523 E WifiStateMachine: Start Dhcp Watchdog 3
09-06 19:04:56.513  1032  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=201225  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-06 19:04:56.513  1032  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=201226  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:56.514  1032  8293 D DhcpStateMachine: StoppedState
09-06 19:04:56.514  1032  8293 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.514  1032  8293 D DhcpStateMachine: WaitBeforeStartState
09-06 19:04:56.514  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=201227  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:56.515  1032  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=201228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:56.515  1032  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=201228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:56.516  1032  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=201229  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:04:56.517  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14437] from screen [on:0 period:7713989] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:04:56.518  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:7713990] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:04:56.518  1032  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:04:56.521  1032  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-06 19:04:56.522  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.522  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.523  1032  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.523  1032  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.523  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.524  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.524  1032  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:04:56.524  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
09-06 19:04:56.525  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
09-06 19:04:56.525  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:04:56.525  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:04:56.525  1032  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:04:56.525  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:04:56.526  1032  1523 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:04:56.526  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 19:04:56.526  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,09-06 19:04:56.526  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:04:56.527  1032  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36c1a735 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.527  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36c1a735 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.527  1032  8293 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.527  1032  8293 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 19:04:56.529  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.529  1032  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:04:56.529  1032  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:04:56.529  1032  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:04:56.530   314   876 D CommandListener: Setting iface cfg
09-06 19:04:56.530   314   876 D CommandListener: Trying to bring up wlan0
09-06 19:04:56.531  1032  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:04:56.532  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:56.532  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:04:56.533  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:04:56.533  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:04:56.533  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.533  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.534  1032  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.534  1032  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.534  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.534  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:04:56.535  1032  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:04:56.535  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:04:56.535  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:04:56.536  1032  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.536  1032  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.536  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:04:56.536  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:04:56.536  1032  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:04:56.536  1032  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:04:56.536  8187  8187 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:04:56.536  1032  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:04:56.537  1032  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Blue,tooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:04:56.546  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:04:56.549  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:04:56.553  1032  1523 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:04:56.554  1032  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:04:56.554  6898  6975 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 19:04:56.554  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:04:56.554  1032  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:04:56.555  1032  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:04:56.555  1032  1531 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:04:56.555  6898  6975 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:04:56.557  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.557  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:56.558  6898  6975 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ea7faa5 Bundle[{}]
09-06 19:04:56.559  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.559  6898  6975 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:04:56.559  6898  6975 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-06 19:04:56.560  6898  6975 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:04:56.561  6898  6975 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:04:56.562  6898  6975 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-06 19:04:56.563  6898  6975 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 19:04:56.565  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.565  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.566  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-06 19:04:56.567  1032  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:04:56.568  1032  1531 D ConnectivityService: Adding iface wlan0 to network 102
09-06 19:04:56.570  1032  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:04:56.573  6898  6975 I System.out: Running OutgoingSocketThread
09-06 19:04:56.576  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.576  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.576  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:04:56.576  6898  8300 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
09-06 19:04:56.577  6898  8300 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47602
09-06 19:04:56.577  6898  8300 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-06 19:04:56.577  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-06 19:04:56.581  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 19:04:56.584  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.584  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.584  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:04:56.587  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-06 19:04:56.587  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.587  1591  1591 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:04:56.588  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.590  1032  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:04:56.590  1032  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 19:04:56.591  1032  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-06 19:04:56.591  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.591  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:04:56.591  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:04:56.592   314   876 E Netd    : netlink response contains error (File exists)
09-06 19:04:56.592  1032  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-06 19:04:56.593  1032  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:04:56.593  1032  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-06 19:04:56.593  1032  1531 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-06 19:04:56.593  1032  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:04:56.594  1032  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:04:56.594  1032  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-06 19:04:56.594  1032  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 19:04:56.594  1032  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:56.594  1032  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:56.594  1032  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:04:56.594  1032  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.594  1032  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:04:56.594  1032  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:04:56.594  1032  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:04:56.594  1032  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:56.594  1032  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:04:56.595  1032  1531 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:04:56.595  1032  1531 D ConnectivityService:    accepting network in place of null
09-06 19:04:56.595  1032  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:56.595  1032  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:56.595  1032  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:56.596  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:56.596  1032  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:04:56.596  1032  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 19:04:56.597  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:04:56.597  1032  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:04:56.597  1032  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:04:56.596  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:04:56.597  1032  1531 D ConnectivityService: Switching to new, default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:04:56.598   314  8303 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 19:04:56.598  1032  1531 D ConnectivityService: validation of new default Network = false
09-06 19:04:56.599  1032  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:04:56.599  1032  1531 D DSQN    : enableDataServiceNotify 
09-06 19:04:56.599  1032  1531 D DSQN    : start dsqn bin
09-06 19:04:56.599  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:04:56.599  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:04:56.599  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:04:56.599  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:04:56.603  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.603  1591  1591 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:04:56.604  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.604  1032  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 19:04:56.604  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:56.604  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:56.605  1032  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:56.606  1591  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:04:56.600  8304  8304 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:56.600  8304  8304 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:56.610  1591  1591 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:04:56.610  1591  1591 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:04:56.610  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.612  1032  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-06 19:04:56.621  8304  8304 E DSQN    : DSQN ssw
,09-06 19:04:56.629  1591  1591 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:04:56.629  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:56.630  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:56.672  8275  8275 W ExternalStrings: load override strings
09-06 19:04:56.672  8275  8275 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:04:56.672  8275  8275 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 19:04:56.674  8275  8275 D StatusProvider: onCreate
09-06 19:04:56.709  8275  8275 V Signer  : override build config not found
09-06 19:04:56.710  8275  8275 D Signer  : value of property debug is false
,09-06 19:04:56.731  1032  8293 D DhcpStateMachine: DHCPV4 request on wlan0
,09-06 19:04:56.733  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-06 19:04:56.733  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-06 19:04:56.733  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-06 19:04:56.733  1032  8293 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 19:04:56.733  1032  8293 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 19:04:56.733  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-06 19:04:56.733  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-06 19:04:56.734  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-06 19:04:56.734  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-06 19:04:56.734  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-06 19:04:56.734  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-06 19:04:56.734  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-06 19:04:56.734  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-06 19:04:56.734  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-06 19:04:56.735  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-06 19:04:56.730  8308  8308 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:56.730  8308  8308 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:04:56.742  8275  8275 V LGMDMManager: Create singleton instance
09-06 19:04:56.758  8308  8308 I dhcpcd  : version 5.5.6 starting
09-06 19:04:56.760  8308  8308 E dhcpcd  : get_duid: m
09-06 19:04:56.760  8308  8308 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:04:56.760  8308  8308 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-06 19:04:56.783  8275  8275 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-06 19:04:56.830  8308  8308 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-06 19:04:56.830  8308  8308 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:04:56.830  8308  8308 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-06 19:04:56.831  8308  8308 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 19:04:56.831  8308  8308 D dhcpcd  : wlan0: sending REQUEST (xid 0xc9f6ffe6), next in 4.48 seconds
09-06 19:04:56.848  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:56.849  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:04:56.855  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:56.859  8308  8308 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-06 19:04:56.861  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:56.875  8308  8308 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:04:56.875  8308  8308 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 19:04:56.876  8308  8308 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:04:56.876  8308  8308 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 19:04:56.876  8308  8308 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:04:56.876  8308  8308 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:04:56.876  8308  8308 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:04:56.876  8308  8308 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-06 19:04:56.926  1032  1856 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8325 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-06 19:04:56.927  1032  1856 I ActivityManager: Killing 7361:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-06 19:04:56.928   314  8303 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-06 19:04:56.988   314  8303 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 19:04:57.038   314   875 D LGDataListener: argv[0]=dsqncommand
09-06 19:04:57.038   314   875 D LGDataListener: argv[1]=wlan0
09-06 19:04:57.038   314   875 D LGDataListener: argv[2]=1
09-06 19:04:57.038   314   875 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-06 19:04:57.039  1032  1101 D DSQN    : DSQM DsqnNotification wlan0  1
09-06 19:04:57.039  1032  1101 D DSQN    : start to monitor internet connection
,09-06 19:04:57.051  8275  8317 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:04:57.106  1032  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:04:57 GMT], X-Android-Received-Millis=[1473181497105], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473181497036]}
09-06 19:04:57.106  1032  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-06 19:04:57.106  1032  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-06 19:04:57.106  1032  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-06 19:04:57.106  1032  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 19:04:57.106  1032  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:57.106  1032  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:57.106  1032  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:04:57.106  1032  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-06 19:04:57.106  1032  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 19:04:57.106  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:57.106  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:57.107  1032  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:57.107  1032  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:57.107  1032  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:04:57.107  1591  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:04:57.107  1032  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:57.107  1032  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:04:57.108  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:57.108  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:04:57.138  1032  8293 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-06 19:04:57.142  1032  8293 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 19:04:57.142  1032  8293 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-06 19:04:57.143  1032  8293 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:04:57.143  1032  8293 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 19:04:57.143  1032  8293 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:04:57.143  1032  8293 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:04:57.143  1032  8293 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 19:04:57.144  1032  8293 D DhcpStateMachine: RunningState
09-06 19:04:57.152  1032  1883 W libprocessgroup: failed to open /acct/uid_10093/pid_7361/cgroup.procs: No such file or directory
,09-06 19:04:57.182  8325  8325 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:04:57.184  1591  1591 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:04:57.185  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:57.186  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:04:57.211  8325  8325 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-06 19:04:57.241  8325  8325 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-06 19:04:57.242  8325  8325 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 19:04:57.242  8325  8325 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:04:57.242  8325  8325 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:04:57.243  8325  8325 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:04:57.244  8325  8325 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 19:04:57.248  8325  8325 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 19:04:57.253  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.255  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.271  8325  8325 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:04:57.273  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.273  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:04:57.274  8325  8325 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-06 19:04:57.277  8325  8325 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 19:04:57.281  8275  8317 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:57.281  8275  8317 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:04:57.285  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.294  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:57.302  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.303  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.304  8325  8325 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:04:57.306  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 19:04:57.311  6996  6996 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 19:04:57.317  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:04:57.318  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.328  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.334  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:57.341  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.342  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.342  8325  8325 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:57.345  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:04:57.345  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:04:57.345  6996  6996 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:04:57.345  6996  6996 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:04:57.346  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:04:57.346  6996  6996 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:04:57.346  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:04:57.346  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:04:57.347  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:04:57.347  6996  6996 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:04:57.347  6996  6996 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:04:57.347  6996  6996 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:04:57.351  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.351  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:04:57.358  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.364  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:57.375  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.375  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.375  8325  8325 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:57.383  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.383  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:04:57.396  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.402  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:04:57.410  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.410  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:57.412  8325  8325 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:57.417  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.417  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:04:57.423  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.429  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:57.435  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.435  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.436  8325  8325 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:57.439  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.439  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:04:57.444  8275  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-06 19:04:57.445  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.456  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:04:57.463  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.463  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:04:57.464  8325  8325 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:04:57.473  8275  8317 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-06 19:04:57.476  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:04:57.477  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:57.485  8275  8317 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-06 19:04:57.487  8275  8317 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 19:04:57.489  8275  8317 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,09-06 19:04:57.490  8275  8317 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-06 19:04:57.491  8275  8317 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-06 19:04:57.497  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:04:57.498  8275  8317 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-06 19:04:57.502  8275  8317 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-06 19:04:57.508  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:57.516  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:04:57.517  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.523  8325  8325 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:04:57.527  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.528  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:04:57.534  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:04:57.540  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:04:57.547  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.548  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.549  8325  8325 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:04:57.552  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.552  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:04:57.556  8228  8228 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:04:57.561  8228  8228 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:57.564  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.571  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:57.577  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:04:57.578  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.579  8325  8325 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:04:57.579  6898  6975 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
09-06 19:04:57.579  6898  6975 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
09-06 19:04:57.580  8325  8325 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:04:57.581  8325  8325 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:04:57.585  6898  6975 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
09-06 19:04:57.587  6898  6975 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 19:04:57.587  6898  6975 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
09-06 19:04:57.587  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.587  8275  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:04:57.590  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.590  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398fb9b8 added. We now have 2 listener(s)
09-06 19:04:57.591  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.592  8228  8228 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:04:57.595  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.595  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.595  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.595  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.595  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29185391 added. We now have 9 listener(s)
09-06 19:04:57.595  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.595  8228  8228 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:04:57.596  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:04:57.601  6996  6996 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:04:57.604  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:57.611  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:57.611  6996  6996 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:04:57.615  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.615  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:57.616  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:04:57.616  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14dd96f7 added. We now have 3 listener(s)
09-06 19:04:57.619  8325  8325 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:04:57.620  8325  8325 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:04:57.620  8325  8325 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:04:57.621  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:57.621  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.623  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:57.623  8325  8325 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:04:57.624  8325  8325 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:04:57.624  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.625  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.625  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.625  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.625  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2062b964 added. We now have 10 listener(s)
09-06 19:04:57.625  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.625  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:57.625  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:57.625  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:57.625  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.625  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.625  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.625  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.626  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398fb9b8 removed from the list
09-06 19:04:57.626  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.626  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29185391 removed from the list
09-06 19:04:57.626  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:57.626  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
09-06 19:04:57.627  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.627  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.627  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 19:04:57.628  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.628  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.628  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.628  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29185391 not in the list
09-06 19:04:57.628  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.628  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.629  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.630  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.630  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.630  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2062b964 removed from the list
09-06 19:04:57.630  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.630  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.630  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.630  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.630  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14dd96f7 removed from the list
09-06 19:04:57.631  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:04:57.631  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25dd97cd added. We now have 2 listener(s)
09-06 19:04:57.631  1032  1688 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:04:57.633  8325  8325 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 19:04:57.634  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.634  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.634  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.634  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.634  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19284882 added. We now have 9 listener(s)
09-06 19:04:57.634  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.634  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:04:57.635  8325  8325 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 19:04:57.635  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:04:57.638  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:57.641  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:57.643  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.643  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:57.643  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.643  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74407d0 added. We now have 3 listener(s)
09-06 19:04:57.644  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.646  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.646  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.646  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.647  6898  6975 V org.thaliproject.p2p.btconnectorli,b.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.647  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d38e3c9 added. We now have 10 listener(s)
09-06 19:04:57.647  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.647  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:57.647  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:04:57.647  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:04:57.647  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:57.647  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:04:57.648  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:57.650  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:57.656  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:04:57.656  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.661  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:04:57.661  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:04:57.663  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:04:57.664  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.665  6898  6975 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:04:57.665  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:57.665  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:57.667  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:57.667  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:57.667  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:57.668  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.668  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.668  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.668  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.668  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25dd97cd removed from the list
09-06 19:04:57.668  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.668  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19284882 removed from the list
09-06 19:04:57.668  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:57.668  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.668  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.668  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.669  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.669  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.669  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.669  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19284882 not in the list
09-06 19:04:57.669  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.669  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.670  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.671  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:57.671  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stop,ped
09-06 19:04:57.671  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.671  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.671  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d38e3c9 removed from the list
09-06 19:04:57.671  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.671  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.671  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.671  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.671  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74407d0 removed from the list
09-06 19:04:57.672  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.672  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a9d0fc added. We now have 2 listener(s)
09-06 19:04:57.672  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.676  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.676  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.676  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.676  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.676  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e2f385 added. We now have 9 listener(s)
09-06 19:04:57.676  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.676  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:04:57.679  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:57.683  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:57.684  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.684  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:57.684  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.684  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f99fa0b added. We now have 3 listener(s)
09-06 19:04:57.684  1032  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.687  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.687  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.687  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.688  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.688  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4100e8 added. We now have 10 listener(s)
09-06 19:04:57.688  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.688  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:57.688  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:57.689  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:57.689  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:04:57.689  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:04:57.689  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:57.689  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:04:57.691  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:57.692  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:04:57.693  1032  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.697  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:04:57.697  8325  8325 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:57.697  8325  8325 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:04:57.697  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:04:57.699  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:04:57.699  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.701  6898  6975 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-06 19:04:57.701  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:57.701  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:57.701  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:57.702  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.702  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.702  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.702  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.702  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a9d0fc removed from the list
09-06 19:04:57.702  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.702  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e2f385 removed from the list
09-06 19:04:57.702  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:57.702  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.703  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.703  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.704  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.704  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.704  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.704  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e2f385 not in the list
09-06 19:04:57.704  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.704  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.705  8325  8325 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 19:04:57.705  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.706  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:57.706  8325  8325 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 19:04:57.706  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:57.706  8325  8325 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 19:04:57.706  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.706  8325  8325 V SoundPool: doLoad: loading sample sampleID=1
09-06 19:04:57.706  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.706  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4100e8 removed from the list
09-06 19:04:57.706  6898 , 6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.706  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.706  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.706  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.706  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f99fa0b removed from the list
09-06 19:04:57.707  8325  8325 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:04:57.707  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.707  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ec2be7 added. We now have 2 listener(s)
09-06 19:04:57.708  1032  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.708  8325  8377 V SoundPool: Start decode
09-06 19:04:57.709  8325  8377 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 19:04:57.709   325  1368 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 19:04:57.709   325  1368 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 19:04:57.709   325  1368 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 19:04:57.709   325  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 19:04:57.709   325  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 19:04:57.709   325  1368 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 19:04:57.709   325  1368 V MediaPlayerService: player type = 3
09-06 19:04:57.710   325  1368 V AwesomePlayer: AwesomePlayer create()
,09-06 19:04:57.710  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.710  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.710  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.711  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.711  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d994394 added. We now have 9 listener(s)
09-06 19:04:57.711  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.711  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:04:57.713   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:57.713   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:57.713  7751  7751 D UEI.SmartControl: QS Service created
09-06 19:04:57.713   325  1368 V AwesomePlayer: setAudioSink() 
,09-06 19:04:57.713   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:57.713   325  1368 V AudioCache: notify(0xb100b1c0, 8, 0, 0)
09-06 19:04:57.713   325  1368 V AudioCache: ignored
09-06 19:04:57.713   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:57.713  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:57.713   325  1368 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 19:04:57.713   325  1368 V AwesomePlayer: setDataSource_l dataSource
,09-06 19:04:57.713   325  1368 V LGParserOSAL: SniffLGParser start
09-06 19:04:57.713   325  1368 V LGParserOSAL: MainType:5, SubType=0
09-06 19:04:57.713   325  1368 V LGParserOSAL: #### check Mime : application/ogg
09-06 19:04:57.713  8325  8325 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:04:57.713   325  1368 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 19:04:57.713   325  1368 E MediaExtractor: Use LGExtractor :application/ogg 
,09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:57.717  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:57.718  8325  8325 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:04:57.719  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:04:57.719  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.720  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:57.720  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.720  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1607d632 added. We now have 3 listener(s)
09-06 19:04:57.720  1032  1688 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.723  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.723  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.724  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.724  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.724  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21459f83 added. We now have 10 listener(s)
09-06 19:04:57.724  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.724  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:57.724  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:04:57.724  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:04:57.724  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:04:57.724  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:04:57.730  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:57.731  7751  7751 I UEI.SmartControl: Service initServices...
09-06 19:04:57.731  7751  7751 D UEI.SmartControl: QS start get config
09-06 19:04:57.735  8325  8325 V LGMDMManager: Create singleton instance
09-06 19:04:57.736  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:57.737  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:04:57.737  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.741  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:04:57.742  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:04:57.744  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:04:57.744  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.746  6898  6975 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:04:57.748  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:04:57.748  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:57.748  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:57.748  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.748  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.748  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.748  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.748  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ec2be7 removed from the list
09-06 19:04:57.749  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.749  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d994394 removed from the list
09-06 19:04:57.749  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:57.749  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.749  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.749  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.750  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.750  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.750  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.750  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d994394 not in the list
09-06 19:04:57.750  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.750  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.751  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.751  6898  6975 D BluetoothLeScanner: could not find callback wrapper
09-06 19:04:57.751  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:04:57.752  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.752  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.752  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21459f83 removed from the list
09-0,6 19:04:57.752  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.752  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.752  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.752  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.752  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1607d632 removed from the list
09-06 19:04:57.753  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.753  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3159237e added. We now have 2 listener(s)
09-06 19:04:57.753  1032  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.756  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.756  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.756  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.756  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.756  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d38b0df added. We now have 9 listener(s)
09-06 19:04:57.756  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.757  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:04:57.759  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:04:57.763  6898  6975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:04:57.765  6898  6975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:04:57.765  6898  6975 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:04:57.767  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:04:57.767  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a0c7f5 added. We now have 3 listener(s)
09-06 19:04:57.767  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:04:57.767  1032  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:04:57.770  6898  6898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:04:57.772  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:04:57.772  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:04:57.772  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:04:57.772  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:04:57.772  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edff98a added. We now have 10 listener(s)
09-06 19:04:57.772  6898  6975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:04:57.773  6898  6975 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:04:57.773  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:57.773  6898  6975 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:04:57.773  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.773  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.773  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:04:57.773  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.773  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3159237e removed from the list
09-06 19:04:57.773  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.773  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d38b0df removed from the list
09-06 19:04:57.773  6898  6975 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:04:57.773  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.773   325  1368 V LGParserOSAL: supported mime: application/ogg
09-06 19:04:57.773   325  1368 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 19:04:57.773   325  1368 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 19:04:57.773   325  1368 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 19:04:57.773   325  1368 V AwesomePlayer: AudioTrack Setting
09-06 19:04:57.773   325  1368 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 19:04:57.773   325  1368 V AwesomePlayer: setAudioSource() 
09-06 19:04:57.773   325  1368 V MediaPlayerService: prepare
09-06 19:04:57.773   325  1368 V AwesomePlayer: prepareAsync_l() 
09-06 19:04:57.773   325  1368 V MediaPlayerService: wait for prepare
09-06 19:04:57.774  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.774  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.774   325  8378 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 19:04:57.774   325  8378 V AwesomePlayer: initAudioDecoder() 
09-06 19:04:57.774   325  8378 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:04:57.774   325  8378 V AudioSystem: isOffloadSupported()
09-06 19:04:57.774   325  8378 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:04:57.774   325  8378 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:04:57.774   325  8378 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:04:57.774   325  8378 V AwesomePlayer: getUseOffload() = 0 
09-06 19:04:57.774   325  8378 V OMXCodec: OMXCodec::Create
09-06 19:04:57.774   325  8378 V OMXCodec: findMatchingCodecs()
09-06 19:04:57.774   325  8378 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 19:04:57.774   325  8378 V OMXCodec: matchingCodecs.size()=1
09-06 19:04:57.774   325  8378 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 19:04:57.776  6898  6975 I org.thaliproject.p2p.bt,connectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.776  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.776  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.776   325  8378 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 19:04:57.776   325  8378 V LGCodecAdapter: LG Codec Adapter start
09-06 19:04:57.776  6898  6975 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d38b0df not in the list
09-06 19:04:57.776   325  8378 V OMXCodec: OMXCodec Createtor
09-06 19:04:57.776   325  8378 V OMXCodec: setComponentRole
09-06 19:04:57.776  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.776  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.776   325  8378 V OMXCodec: configureCodec protected=0
09-06 19:04:57.776   325  8378 V LGCodecAdapter: called getLGCodecSpecificData
09-06 19:04:57.776   325  8378 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 19:04:57.776   325  8378 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 19:04:57.776   325  8378 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 19:04:57.776   325  8378 V LGCodecOSAL: Not support LGCodec
09-06 19:04:57.777   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:04:57.777   325  8378 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 19:04:57.777   325  8378 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 19:04:57.777   325  8378 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 19:04:57.777   325  8378 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:04:57.777   325  8378 V AudioSystem: isOffloadSupported()
09-06 19:04:57.777   325  8378 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:04:57.777   325  8378 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:04:57.777   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 19:04:57.777   325  8378 V OMXCodec: init()
09-06 19:04:57.777   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 19:04:57.777   325  8378 V OMXCodec: allocateBuffers
09-06 19:04:57.777   325  8378 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 19:04:57.777   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 19:04:57.777  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:04:57.777  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:04:57.777  6898  6975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:04:57.777  6898  6975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edff98a removed from the list
09-06 19:04:57.777  6898  6975 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:04:57.777  6898  6975 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:04:57.777  6898  6975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:04:57.777   325  8378 V OMXCodec: [O,MX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
09-06 19:04:57.777  6898  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:04:57.777   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-06 19:04:57.777  6898  6975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a0c7f5 removed from the list
09-06 19:04:57.778   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-06 19:04:57.778   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-06 19:04:57.778   325  8378 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:04:57.778   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:04:57.778   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-06 19:04:57.778   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-06 19:04:57.778   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-06 19:04:57.778   325  8378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-06 19:04:57.778   325  8378 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:04:57.778  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:04:57.778  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:04:57.779  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:04:57.779  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:04:57.779  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:04:57.779  6898  6975 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:04:57.785   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:04:57.785   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:04:57.785   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 19:04:57.786   325  8378 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:04:57.787   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 19:04:57.787   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 19:04:57.787   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 19:04:57.787   325  8378 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 19:04:57.787   325  8378 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 19:04:57.787   325  8378 V AudioCache: notify(0xb100b1c0, 5, 0, 0)
09-06 19:04:57.787   325  8378 V AudioCache: ignored
09-06 19:04:57.787   325  8378 V AudioCache: notify(0xb100b1c0, 1, 0, 0)
09-06 19:04:57.787   325  8378 V AudioCache: prepared
09-06 19:04:57.787   325  1368 V AudioCache: wait - success
09-06 19:04:57.787   325  1368 V MediaPlayerService: start
09-06 19:04:57.787   325  1368 V AwesomePlayer: play_l() 
09-06 19:04:57.787   325  1368 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 19:04:57.787   325  1368 V AwesomePlayer: createAudioPlayer_l
09-06 19:04:57.787   325  1368 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 19:04:57.787   325  1368 V AwesomePlayer: startAudioPlayer_l() 
09-06 19:04:57.787   325  1368 D AudioPlayer: start of Playback, useOffload 0
09-06 19:04:57.787   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:04:57.787   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:04:57.788  6898  8381 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
09-06 19:04:57.789  6898  8381 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
09-06 19:04:57.789  6898  8381 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:57.789   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 19:04:57.790   325  8380 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 19:04:57.790   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 19:04:57.791   325  1368 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 19:04:57.791   325  1368 V AudioCache: notify(0xb100b1c0, 6, 0, 0)
,09-06 19:04:57.791   325  1368 V AudioCache: ignored
09-06 19:04:57.791   325  1368 V MediaPlayerService: wait for playback complete
09-06 19:04:57.791  6898  8382 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: My test thread name)
09-06 19:04:57.791  6898  8382 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
09-06 19:04:57.791  6898  8382 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:04:57.793  6898  6975 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:04:57.794  6898  6975 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:04:57.794  6898  6975 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:04:57.794  6898  6975 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:04:57.794  6898  6975 D com.test.thalitest.ThaliTestRunner: Total duration: 23813 ms
09-06 19:04:57.795  6898  6975 I jxcore-log: *Native tests were executed*
09-06 19:04:57.795  6898  6975 I jxcore-log: 
09-06 19:04:57.795  6898  6975 I jxcore-log: Total number of executed tests:  80
09-06 19:04:57.795  6898  6975 I jxcore-log: 
09-06 19:04:57.795  6898  6975 I jxcore-log: Number of passed tests:  80
09-06 19:04:57.795  6898  6975 I jxcore-log: 
09-06 19:04:57.796  6898  6975 I jxcore-log: Number of failed tests:  0
09-06 19:04:57.796  6898  6975 I jxcore-log: 
09-06 19:04:57.796  6898  6975 I jxcore-log: Number of ignored tests:  0
09-06 19:04:57.796  6898  6975 I jxcore-log: 
09-06 19:04:57.796  6898  6975 I jxcore-log: Total duration:  23813
09-06 19:04:57.796  6898  6975 I jxcore-log: 
09-06 19:04:57.796  6898  6975 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:04:57.796  6898  6975 I jxcore-log: 
09-06 19:04:57.802  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.802  6898  6975 I jxcore-log: 
09-06 19:04:57.804   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.804   325  8383 V AudioCache: memcpy(0xaf006000, 0xb16eb000, 4096)
09-06 19:04:57.807  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.807  6898  6975 I jxcore-log: 
09-06 19:04:57.808   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.808   325  8383 V AudioCache: memcpy(0xaf007000, 0xb16eb000, 4096)
09-06 19:04:57.808   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.808   325  8383 V AudioCache: memcpy(0xaf008000, 0xb16eb000, 4096)
09-06 19:04:57.808  6898  6898 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:04:57.809   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.809   325  8383 V AudioCache: memcpy(0xaf009000, 0xb16eb000, 4096)
09-06 19:04:57.809  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.809  6898  6975 I jxcore-log: 
09-06 19:04:57.810  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.810  6898  6975 I jxcore-log: 
09-06 19:04:57.810   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.810   325  8383 V AudioCache: memcpy(0xaf00a000, 0xb16eb000, 4096)
09-06 19:04:57.810   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.810   325  8383 V AudioCache: memcpy(0xaf00b000, 0xb16eb000, 4096)
09-06 19:04:57.810   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.810   325  8383 V AudioCache: memcpy(0xaf00c000, 0xb16eb000, 4096)
09-06 19:04:57.810   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.810   325  8383 V AudioCache: memcpy(0xaf00d000, 0xb16eb000, 4096)
09-06 19:04:57.811   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.811   325  8383 V AudioCache: memcpy(0xaf00e000, 0xb16eb000, 4096)
09-06 19:04:57.811  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.811  6898  6975 I jxcore-log: 
09-06 19:04:57.811   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.811   325  8383 V AudioCache: memcpy(0xaf00f000, 0xb16eb000, 4096)
09-06 19:04:57.811   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.811   325  8383 V AudioCache: memcpy(0xaf010000, 0xb16eb000, 4096)
09-06 19:04:57.812  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:04:57.812  6898  6975 I jxcore-log: 
09-06 19:04:57.812   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.812   325  8383 V AudioCache: memcpy(0xaf011000, 0xb16eb000, 4096)
09-06 19:04:57.812   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.812   325  8383 V AudioCache: memcpy(0xaf012000, 0xb16eb000, 4096)
09-06 19:04:57.813   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.813   325  8383 V AudioCache: memcpy(0xaf013000, 0xb16eb000, 4096)
09-06 19:04:57.813   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.813   325  8383 V AudioCache: memcpy(0xaf014000, 0xb16eb000, 4096)
09-06 19:04:57.814   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.814   325  8383 V AudioCache: memcpy(0xaf015000, 0xb16eb000, 4096)
09-06 19:04:57.814   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.814   325  8383 V AudioCache: memcpy(0xaf016000, 0xb16eb000, 4096)
09-06 19:04:57.814  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:04:57.814  6898  6975 I jxcore-log: 
09-06 19:04:57.815   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.815   325  8383 V AudioCache: memcpy(0xaf017000, 0xb16eb000, 4096)
09-06 19:04:57.817  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.817  6898  6975 I jxcore-log: 
09-06 19:04:57.818  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.818  6898  6975 I jxcore-log: 
09-06 19:04:57.819   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.819   325  8383 V AudioCache: memcpy(0xaf018000, 0xb16eb000, 4096)
09-06 19:04:57.819  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.819  6898  6975 I jxcore-log: 
09-06 19:04:57.820   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.820   325  8383 V AudioCache: memcpy(0xaf019000, 0xb16eb000, 4096)
09-06 19:04:57.820   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.820   325  8383 V AudioCache: memcpy(0xaf01a000, 0xb16eb000, 4096)
09-06 19:04:57.820  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:04:57.820  6898  6975 I jxcore-log: 
09-06 19:04:57.820   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.820   325  8383 V AudioCache: memcpy(0xaf01b000, 0xb16eb000, 4096)
09-06 19:04:57.821   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.821   325  8383 V AudioCache: memcpy(0xaf01c000, 0xb16eb000, 4096)
09-06 19:04:57.821  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:04:57.821  6898  6975 I jxcore-log: 
09-06 19:04:57.821   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.821   325  8383 V AudioCache: memcpy(0xaf01d000, 0xb16eb000, 4096)
09-06 19:04:57.822   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.822   325  8383 V AudioCache: memcpy(0xaf01e000, 0xb16eb000, 4096)
09-06 19:04:57.822  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:04:57.822  6898  6975 I jxcore-log: 
09-06 19:04:57.822   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.822   325  8383 V AudioCache: memcpy(0xaf01f000, 0xb16eb000, 4096)
09-06 19:04:57.823   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.823   325  8383 V AudioCache: memcpy(0xaf020000, 0xb16eb000, 4096)
09-06 19:04:57.823  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.823  6898  6975 I jxcore-log: 
09-06 19:04:57.823   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.823   325  8383 V AudioCache: memcpy(0xaf021000, 0xb16eb000, 4096)
09-06 19:04:57.823  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.823  6898  6975 I jxcore-log: 
09-06 19:04:57.824   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.824   325  8383 V AudioCache: memcpy(0xaf022000, 0xb16eb000, 4096)
09-06 19:04:57.824  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.824  6898  6975 I jxcore-log: 
09-06 19:04:57.824   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.824   325  8383 V AudioCache: memcpy(0xaf023000, 0xb16eb000, 4096)
09-06 19:04:57.824  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.824  6898  6975 I jxcore-log: 
09-06 19:04:57.824   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.824   325  8383 V AudioCache: memcpy(0xaf024000, 0xb16eb000, 4096)
09-06 19:04:57.825   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.825   325  8383 V AudioCache: memcpy(0xaf025000, 0xb16eb000, 4096)
09-06 19:04:57.825  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.825  6898  6975 I jxcore-log: 
09-06 19:04:57.825   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.825   325  8383 V AudioCache: memcpy(0xaf026000, 0xb16eb000, 4096)
09-06 19:04:57.826  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.826  6898  6975 I jxcore-log: 
09-06 19:04:57.826   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.826   325  8383 V AudioCache: memcpy(0xaf027000, 0xb16eb000, 4096)
09-06 19:04:57.826  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.826  6898  6975 I jxcore-log: 
09-06 19:04:57.826   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.826   325  8383 V AudioCache: memcpy(0xaf028000, 0xb16eb000, 4096)
09-06 19:04:57.827   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.827   325  8383 V AudioCache: memcpy(0xaf029000, 0xb16eb000, 4096)
09-06 19:04:57.827  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:04:57.827  6898  6975 I jxcore-log: 
09-06 19:04:57.827   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.827   325  8383 V AudioCache: memcpy(0xaf02a000, 0xb16eb000, 4096)
09-06 19:04:57.827  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:04:57.827  6898  6975 I jxcore-log: 
09-06 19:04:57.828   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.828   325  8383 V AudioCache: memcpy(0xaf02b000, 0xb16eb000, 4096)
09-06 19:04:57.828  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:04:57.828  6898  6975 I jxcore-log: 
09-06 19:04:57.828   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.828   325  8383 V AudioCache: memcpy(0xaf02c000, 0xb16eb000, 4096)
09-06 19:04:57.829  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.829  6898  6975 I jxcore-log: 
09-06 19:04:57.829   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.829   325  8383 V AudioCache: memcpy(0xaf02d000, 0xb16eb000, 4096)
09-06 19:04:57.829   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.829   325  8383 V AudioCache: memcpy(0xaf02e000, 0xb16eb000, 4096)
09-06 19:04:57.829  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.829  6898  6975 I jxcore-log: 
09-06 19:04:57.829   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.829   325  8383 V AudioCache: memcpy(0xaf02f000, 0xb16eb000, 4096)
09-06 19:04:57.830  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.830  6898  6975 I jxcore-log: 
09-06 19:04:57.830   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.830   325  8383 V AudioCache: memcpy(0xaf030000, 0xb16eb000, 4096)
09-06 19:04:57.830  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.830  6898  6975 I jxcore-log: 
09-06 19:04:57.830   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.830   325  8383 V AudioCache: memcpy(0xaf031000, 0xb16eb000, 4096)
09-06 19:04:57.831   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.831   325  8383 V AudioCache: memcpy(0xaf032000, 0xb16eb000, 4096)
09-06 19:04:57.831  6898  6975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:04:57.831  6898  6975 I jxcore-log: 
09-06 19:04:57.831   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.831   325  8383 V AudioCache: memcpy(0xaf033000, 0xb16eb000, 4096)
09-06 19:04:57.833   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.833   325  8383 V AudioCache: memcpy(0xaf034000, 0xb16eb000, 4096)
09-06 19:04:57.835  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:04:57.835   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.835   325  8383 V AudioCache: memcpy(0xaf035000, 0xb16eb000, 4096)
09-06 19:04:57.836   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.836   325  8383 V AudioCache: memcpy(0xaf036000, 0xb16eb000, 4096)
09-06 19:04:57.836   325  8383 V AudioCache: write(0xb16eb000, 4096)
09-06 19:04:57.836   325  8383 V AudioCache: memcpy(0xaf037000, 0xb16eb000, 4096)
09-06 19:04:57.837   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 19:04:57.837   325  8383 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:04:57.837   325  8383 V AwesomePlayer: postAudioEOS() 
09-06 19:04:57.837   325  8383 V AudioCache: write(0xb16eb000, 280)
09-06 19:04:57.837   325  8383 V AudioCache: memcpy(0xaf038000, 0xb16eb000, 280)
09-06 19:04:57.837  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 19:04:57.838   325  8378 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 19:04:57.838   325  8378 V AwesomePlayer: onStreamDone
09-06 19:04:57.838   325  8378 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 19:04:57.838   325  8378 V AudioCache: notify(0xb100b1c0, 2, 0, 0)
09-06 19:04:57.838   325  8378 V AudioCache: playback complete
09-06 19:04:57.838   325  8378 V AwesomePlayer: pause_l() 
09-06 19:04:57.838   325  8378 V AudioCache: notify(0xb100b1c0, 7, 0, 0)
09-06 19:04:57.838  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7635
09-06 19:04:57.838   325  8378 V AudioCache: ignored
09-06 19:04:57.838   325  8378 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:57.839   325  8378 D AudioPlayer: Pause Playback at 1068125
09-06 19:04:57.839   325  1368 V AudioCache: wait - success
09-06 19:04:57.839   325  1368 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 19:04:57.839   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:57.839   325  1368 V AudioCache: notify(0xb100b1c0, 8, 0, 0)
09-06 19:04:57.839   325  1368 V AudioCache: ignored
09-06 19:04:57.839   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:57.839   325  1368 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 19:04:57.839   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 19:04:57.839   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 19:04:57.839   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 19:04:57.839   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 19:04:57.840   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
09-06 19:04:57.841  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 19:04:57.841   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:04:57.841   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 19:04:57.841   325  8380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 19:04:57.843   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:04:57.843   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 19:04:57.843   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 19:04:57.844   325  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 19:04:57.844   325  1368 D AudioPlayer: AudioPlayer releasing audio source
09-06 19:04:57.844   325  1368 D AudioPlayer: AudioPlayer done releasing audio source
09-06 19:04:57.844   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:57.844   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:57.844   325  1368 V AwesomePlayer: ~AwesomePlayer call
09-06 19:04:57.844   325  1368 V AwesomePlayer: reset_l() 
09-06 19:04:57.844   325  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:04:57.845  8325  8377 V SoundPool: close(31)
09-06 19:04:57.845  8325  8377 V SoundPool: pointer = 0x9fe8d000, size = 205080, sampleRate = 48000, numChannels = 2
09-06 19:04:57.861  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.862  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:57.866  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.868  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.870  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.873  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.875  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:04:57.878  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:57.880  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:04:58.068  7751  7751 I UEI.SmartControl: Supports setup maps: true
,09-06 19:04:58.074  7751  7751 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:04:58.074  7751  7751 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:04:58.074  7751  7751 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:04:58.074  7751  7751 I UEI.SmartControl: ### init IR Blaster...
,09-06 19:04:58.077  7751  7751 D serial_port: Configuring serial port
09-06 19:04:58.078  7751  7751 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:04:58.078  7751  7751 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:04:58.078  7751  7751 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:04:58.078  7751  7751 I UEI.SmartControl: Get version...
09-06 19:04:58.096  7751  8387 D UEI.SmartControl: serial port data available: 21
,09-06 19:04:58.126  7751  7751 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:04:58.126  7751  7751 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:04:58.126  7751  7751 I UEI.SmartControl: QS saving settings...
09-06 19:04:58.127  7751  7751 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:04:58.143  7751  8387 D UEI.SmartControl: serial port data available: 4
,09-06 19:04:58.146  8385  8385 D AndroidRuntime: 
09-06 19:04:58.146  8385  8385 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:04:58.148  8385  8385 D AndroidRuntime: CheckJNI is OFF
09-06 19:04:58.158  1032  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-06 19:04:58.158  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:04:58.159  1032  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:04:58.160  1032  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:04:58.160  1032  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:04:58.162  1032  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:04:58.162  1032  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-06 19:04:58.162  1032  1531 D ConnectivityService: identical MTU - not setting
09-06 19:04:58.163  1032  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:04:58.163  1032  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:04:58.163  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:04:58.163  1032  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:58.164  1032  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:04:58.165  1591  2047 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:04:58.173  7751  8393 I UEI.SmartControl: Device manager: loading config....
,09-06 19:04:58.176  7751  7751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 19:04:58.177  7751  7751 E UEI.SmartControl: Services init done
09-06 19:04:58.177  7751  7751 D UEI.SmartControl: QS Service init finished
09-06 19:04:58.178  7751  7751 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:04:58.178  7751  7751 D UEI.SmartControl: QS Service version code: 201091
09-06 19:04:58.178  7751  7751 D UEI.SmartControl: Service requested: Control
09-06 19:04:58.178  7751  8393 D UEI.SmartControl: ----------- loading internal config...
09-06 19:04:58.185  7751  8393 E UEI.SmartControl: Loading SETTINGS...
09-06 19:04:58.188  7751  7751 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-06 19:04:58.191  8325  8325 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 19:04:58.191  7751  7751 D UEI.SmartControl: Internal service binding...
09-06 19:04:58.191  7751  7766 I UEI.SmartControl: ------ IControl API: 11
09-06 19:04:58.191  7751  7766 D UEI.SmartControl: File observer start...
09-06 19:04:58.192  7751  7766 E UEI.SmartControl: IR Port is disabled: false
09-06 19:04:58.192  7751  7766 D UEI.SmartControl: Starting file observer...
09-06 19:04:58.192  7751  7766 I UEI.SmartControl: Registering callback...
09-06 19:04:58.193  7751  7767 I UEI.SmartControl: ------ IControl API: 19
09-06 19:04:58.194  7751  7767 I UEI.SmartControl: Registering Services Ready callback...
09-06 19:04:58.197  7751  8393 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:04:58.202  7751  8392 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-06 19:04:58.205  8325  8342 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 19:04:58.206  7751  8392 D UEI.SmartControl: -----service ready thread exits
09-06 19:04:58.215  8325  8375 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,09-06 19:04:58.216  8325  8375 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 19:04:58.217  8325  8325 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 19:04:58.218  8325  8325 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 19:04:58.219  7751  7766 I UEI.SmartControl: ------ IControl API: 8
09-06 19:04:58.222  8325  8325 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 19:04:58.222  8325  8325 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 19:04:58.223  8325  8325 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 19:04:58.224  8325  8325 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 19:04:58.226  8325  8325 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 19:04:58.226  8325  8325 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 19:04:58.229  8325  8325 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-06 19:04:58.233  8325  8325 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 19:04:58.234  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:04:58.236  8325  8325 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:04:58.236  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:04:58.237  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:04:58.239  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 19:04:58.239  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 19:04:58.240  8325  8325 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473181498240]
09-06 19:04:58.241  8325  8325 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 19:04:58.244  1032  1688 I ActivityManager: Killing 7405:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-06 19:04:58.262  8325  8405 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 19:04:58.282  8385  8385 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:04:58.366  1032  2023 W libprocessgroup: failed to open /acct/uid_10005/pid_7405/cgroup.procs: No such file or directory
09-06 19:04:58.369  1032  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-06 19:04:58.370  1032  1092 I ActivityManager: Killing 6898:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-06 19:04:58.458  1032  2000 I WindowState: WIN DEATH: Window{223b4a29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 19:04:58.461  1032  1530 D WifiService: Client connection lost with reason: 4
,09-06 19:04:58.481  1032  2000 D InputDispatcher: Window went away: Window{223b4a29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 19:04:58.586  1032  1092 I ActivityManager:   Force finishing activity ActivityRecord{3879975a u0 com.test.thalitest/.MainActivity t6}
,09-06 19:04:58.642   342   346 E GBMv2   : DFP En is all cleared set to be enabled
,09-06 19:04:58.651  1032  2039 W ActivityManager: Spurious death for ProcessRecord{2e79fc85 6898:com.test.thalitest/u0a118}, curProc for 6898: null
09-06 19:04:58.653  1032  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-06 19:04:58.658  1032  1117 I ActivityManager:   Force finishing activity ActivityRecord{3879975a u0 com.test.thalitest/.MainActivity t6 f}
09-06 19:04:58.658  8325  8325 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-06 19:04:58.658  1032  1117 W ActivityManager: Duplicate finish request for ActivityRecord{3879975a u0 com.test.thalitest/.MainActivity t6 f}
09-06 19:04:58.660  8325  8325 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:04:58.663  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 19:04:58.663  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 19:04:58.663  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,09-06 19:04:58.664  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 19:04:58.664  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 19:04:58.682  2021  2021 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-06 19:04:58.683  1929  2940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,09-06 19:04:58.683  1929  2940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ea89466 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:04:58.684  2021  2021 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-06 19:04:58.686  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-06 19:04:58.686  1929  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-06 19:04:58.687  1929  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{27e273a7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:04:58.687  2021  2093 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-06 19:04:58.692  8325  8325 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-06 19:04:58.696  1591  1591 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-06 19:04:58.699  3809  3809 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-06 19:04:58.703  7830  7830 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-06 19:04:58.703  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:04:58.706  1983  1983 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 19:04:58.716  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-06 19:04:58.719  4463  4463 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-06 19:04:58.719  4463  4463 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-06 19:04:58.719  4463  4463 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-06 19:04:58.719  4463  4463 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-06 19:04:58.719  4463  4463 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:04:58.719  4463  4463 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:04:58.719  4463  4463 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:04:58.719  4463  4463 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:04:58.719  4463  4463 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:04:58.719  4463  4463 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:04:58.719  4463  4463 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:04:58.719  4463  4463 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:04:58.720  1804  1804 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-06 19:04:58.730  2494  2652 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:04:58.731  1591  1591 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-06 19:04:58.735  4567  4567 I art     : Explicit concurrent mark sweep GC freed 8186(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 671us total 65.113ms
09-06 19:04:58.736  1894  1894 D ActionManagerService: notifyUserLog: 1000003
09-06 19:04:58.738  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-06 19:04:58.739  3809  4454 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-06 19:04:58.750  1032  1435 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:04:58.761  1591  1591 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-06 19:04:58.761  1591  1591 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-06 19:04:58.778  1032  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
09-06 19:04:58.783  1032  1048 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:04:58.812  1032  1032 D administrator: Handling package changes for user 0
,09-06 19:04:58.816  2021  2021 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-06 19:04:58.817  2021  2021 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-06 19:04:58.817  1591  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 19:04:58.817  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.818  2021  2021 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-06 19:04:58.821  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-06 19:04:58.821  1894  1894 D ActionManagerService: notifyUserLog: 1000004
09-06 19:04:58.822  3809  4454 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-06 19:04:58.822  3809  4447 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262123
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , display: false
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , animation: false }
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262287
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , display: false
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , animation: false }
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , create_time: 1472828323917
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , display: false
09-06 19:04:58.826  2021  2021 I GBoardWebViewUtils: , animation: false }
,09-06 19:04:58.830  1591  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:04:58.830  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.834  1591  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:04:58.834  1591  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:04:58.834  1591  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 19:04:58.848  1591  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:04:58.849  2172  2172 I ConfigService: onCreate
,09-06 19:04:58.849  2172  2172 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-06 19:04:58.853  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-06 19:04:58.853  1857  1857 D SplitUIService: removed split : 
09-06 19:04:58.860  1804  1804 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-06 19:04:58.868  1591  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:04:58.868  1591  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 19:04:58.868  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:04:58.869  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-06 19:04:58.869  1591  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:04:58.869  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.880  1591  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:04:58.880  1591  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:04:58.885  1591  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:04:58.885  1591  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 19:04:58.888  1591  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:04:58.888  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.892  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-06 19:04:58.892  1857  1857 I SplitUIService: split app #11
09-06 19:04:58.896  1591  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:04:58.896  1591  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:04:58.896  1591  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 19:04:58.896  1591  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:04:58.901  2172  2172 I ConfigService: onBind returning update interface
09-06 19:04:58.903  1032  1564 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:04:58.903  1032  1564 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:04:58.906  2172  2172 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-06 19:04:58.906  2172  2172 I ConfigService: onBind returning config service
09-06 19:04:58.906  2021  8414 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-06 19:04:58.925  1591  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:04:58.925  1591  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 19:04:58.926  2172  2172 I ConfigService: onDestroy
09-06 19:04:58.928  1591  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:04:58.928  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.932  1591  1591 D KeyguardModel: handleShortcutListChanged...
09-06 19:04:58.932  1591  1591 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-06 19:04:58.938  1591  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 19:04:58.938  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.939  1591  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:04:58.939  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.940  1591  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:04:58.940  1591  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-06 19:04:58.941  1591  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:04:58.941  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.942  1591  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:04:58.942  1591  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 19:04:58.947  1591  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:04:58.947  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.948  1804  8418 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-06 19:04:58.948  1591  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:04:58.948  1591  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 19:04:58.949  1591  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:04:58.949  1591  1650 D KeyguardModel: createShortcutInfo...
09-06 19:04:58.957  1032  1688 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:04:58.967  1032  2015 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:04:58.968  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-06 19:04:58.972  2021  2021 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-06 19:04:58.999  6002  8424 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-06 19:04:59.001  1591  1591 D KeyguardModel: handleShortcutListChanged...
09-06 19:04:59.001  1591  1591 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 19:04:59.006  1804  8426 I PeopleContactsSync: CP2 sync disabled
09-06 19:04:59.011  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-06 19:04:59.011  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:04:59.011  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:04:59.014  1032  1566 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-06 19:04:59.020  1804  4752 I Icing   : doRemovePackageData com.test.thalitest
09-06 19:04:59.021  1804  8423 W GmsApplication: Using Auth Proxy for data requests.
09-06 19:04:59.029  1804  8423 W GmsApplication: Using Auth Proxy for data requests.
,09-06 19:04:59.044  7186  7186 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-06 19:04:59.065  2347  8428 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:04:59.084  1032  1883 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8430 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 19:04:59.085   335   407 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-06 19:04:59.087  3192  8429 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-06 19:04:59.090  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-06 19:04:59.091  1032  1117 I art     : Explicit concurrent mark sweep GC freed 86929(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.797ms total 406.689ms
09-06 19:04:59.091  1032  1045 I art     : WaitForGcToComplete blocked for 51.058ms for cause HeapTrim
09-06 19:04:59.093  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:59.095  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-06 19:04:59.096  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,09-06 19:04:59.097  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-06 19:04:59.099  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-06 19:04:59.122  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-06 19:04:59.122  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:59.125  1032  1104 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3bb3e669 u0 com.lge.launcher2/.Launcher t5} time:203850
,09-06 19:04:59.130  2021  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-06 19:04:59.131  2021  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-06 19:04:59.137  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-06 19:04:59.138  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 19:04:59.138  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:59.140  8385  8385 D AndroidRuntime: Shutting down VM
,09-06 19:04:59.180  2021  2021 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-06 19:04:59.194  1032  1117 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8450 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:04:59.195  8430  8430 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:04:59.195  8430  8430 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:04:59.196  2570  2570 D [Concierge]Service: onStartCommand(). Type : 8
09-06 19:04:59.196  2570  2570 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-06 19:04:59.198  2570  2570 D [Concierge]Service: Update widget ID : 11
09-06 19:04:59.198  2021  2021 D [Concierge]WidgetView: change position of spinner
09-06 19:04:59.199  8430  8430 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:04:59.199  8430  8430 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:04:59.200  2021  2021 I [Concierge]WidgetView: initWebView(). Time : 1473181499200
09-06 19:04:59.200  2570  2570 D [Concierge]Service: onStartCommand(). Type : 0
09-06 19:04:59.212  2021  2021 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 578207678
,09-06 19:04:59.214  2021  2021 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-06 19:04:59.215  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-06 19:04:59.218  2021  2021 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@fa4b53e
09-06 19:04:59.218  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-06 19:04:59.219  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 19:04:59.220  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:59.224  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-06 19:04:59.225  2021  2021 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-06 19:04:59.225  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-06 19:04:59.227  2021  2021 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473181322957, New one : 1473181499200
09-06 19:04:59.227  2021  2021 D [Concierge]WidgetView: Unregister all receivers
09-06 19:04:59.227  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 19:04:59.227  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:59.230  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-06 19:04:59.231  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-06 19:04:59.233  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-06 19:04:59.234  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-06 19:04:59.235  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-06 19:04:59.236  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:59.242  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 19:04:59.248  1032  2000 I ActivityManager: Killing 7859:com.google.android.talk/u0a72 (adj 15): empty #17
09-06 19:04:59.251  1032  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:04:59.255  1032  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-06 19:04:59.273  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-06 19:04:59.281  2021  2021 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-06 19:04:59.281  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-06 19:04:59.282  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:04:59.302  2021  2021 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2fd075eb time:204027
,09-06 19:04:59.326  1032  1981 W libprocessgroup: failed to open /acct/uid_10072/pid_7859/cgroup.procs: No such file or directory
,09-06 19:04:59.328  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 19:04:59.330  8430  8430 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-06 19:04:59.337  8430  8430 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-06 19:04:59.358  8430  8430 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:04:59.379  8430  8430 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:04:59.379  8430  8430 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:04:59.425  8430  8430 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-06 19:04:59.432  2021  2021 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-06 19:04:59.451  1032  1856 I ActivityManager: Killing 7952:com.android.vending/u0a44 (adj 15): empty #17
,09-06 19:04:59.468  2021  2967 I GBoardtInterface: onReloaded()
,09-06 19:04:59.470  2021  2021 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-06 19:04:59.486  1983  1983 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 19:04:59.486  1983  1983 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,09-06 19:04:59.487  1032  1964 W libprocessgroup: failed to open /acct/uid_10044/pid_7952/cgroup.procs: No such file or directory
09-06 19:04:59.489  1983  1983 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-06 19:04:59.489  3809  4447 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:04:59.492  3809  3825 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java,:372)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:04:59.494  8275  8275 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:04:59.495  8275  8275 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 19:04:59.498  1894  1894 D ActionManagerService: notifyUserLog: 1000001
09-06 19:04:59.499  7629  7629 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,09-06 19:04:59.499  3809  4454 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 19:04:59.499  3809  4454 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-06 19:04:59.502  6996  6996 D PackageIntentReceiver: Not supported Hotkey customization function 
09-06 19:04:59.504  1894  1894 D ActionManagerService: notifyUserLog: 1000001
09-06 19:04:59.505  3809  4454 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 19:04:59.505  3809  4454 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-06 19:04:59.505  3809  4454 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-06 19:04:59.505  3809  4454 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-06 19:04:59.505  3809  4447 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:04:59.507  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-06 19:04:59.507  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-06 19:04:59.509  6996  6996 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-06 19:04:59.509  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-06 19:04:59.509  6996  6996 D HideNavigationAppsReceiver: replacing : false
09-06 19:04:59.509  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 19:04:59.511  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
,09-06 19:04:59.511  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 19:04:59.511  6996  6996 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-06 19:04:59.514  6996  6996 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-06 19:04:59.514  6996  6996 D ButtonCombinationReceiver: replacing : false
09-06 19:04:59.523  1032  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2437 sc=60 link=72 tx=75.5, 0.0, 0.0  rx=86.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:7716995] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:04:59.524  1032  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2437 sc=60 link=72 tx=75.5, 0.0, 0.0  rx=86.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:7716996] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 19:04:59.524  1032  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-06 19:04:59.533  1032  1047 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8475 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:04:59.537  1591  1591 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:04:59.541  4463  4509 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: Error inserting f004=13 f005=8475 f002=1473181499539 f003=com.android.vending f006=10044
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:04:59.543  4463  4509 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)

```
